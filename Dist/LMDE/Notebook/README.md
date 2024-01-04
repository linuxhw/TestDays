LMDE - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for LMDE.

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

Total: 903

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ZBook Fury 17.3 inch G8 ... | [65ddbd761c](https://linux-hardware.org/?probe=65ddbd761c) | Jan 02, 2024 |
| Dell          | Latitude E6320              | [1833dcdd43](https://linux-hardware.org/?probe=1833dcdd43) | Dec 31, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [fc3a637b52](https://linux-hardware.org/?probe=fc3a637b52) | Dec 31, 2023 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [86a499d322](https://linux-hardware.org/?probe=86a499d322) | Dec 30, 2023 |
| Sony          | VGN-FW21E                   | [52ff803e03](https://linux-hardware.org/?probe=52ff803e03) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [242659bbee](https://linux-hardware.org/?probe=242659bbee) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3673afc1cd](https://linux-hardware.org/?probe=3673afc1cd) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [9b570f14f6](https://linux-hardware.org/?probe=9b570f14f6) | Dec 26, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [d3e1c0dbdc](https://linux-hardware.org/?probe=d3e1c0dbdc) | Dec 25, 2023 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [942da4e853](https://linux-hardware.org/?probe=942da4e853) | Dec 20, 2023 |
| Sony          | SVE1511A1EW                 | [2f0fde3487](https://linux-hardware.org/?probe=2f0fde3487) | Dec 19, 2023 |
| Sony          | SVE1511A1EW                 | [e5531ecc00](https://linux-hardware.org/?probe=e5531ecc00) | Dec 19, 2023 |
| Irbis         | NB264                       | [8c32d8fb0b](https://linux-hardware.org/?probe=8c32d8fb0b) | Dec 18, 2023 |
| Medion        | E6214                       | [1bc5839854](https://linux-hardware.org/?probe=1bc5839854) | Dec 17, 2023 |
| Medion        | E6214                       | [5269b6e576](https://linux-hardware.org/?probe=5269b6e576) | Dec 17, 2023 |
| Dell          | Inspiron 3542               | [6b3cd841db](https://linux-hardware.org/?probe=6b3cd841db) | Dec 17, 2023 |
| Dell          | Latitude E6430              | [13af5c2dc4](https://linux-hardware.org/?probe=13af5c2dc4) | Dec 17, 2023 |
| Lenovo        | ThinkPad X230 2325BA3       | [1c573f00c0](https://linux-hardware.org/?probe=1c573f00c0) | Dec 16, 2023 |
| Medion        | E6214                       | [806be57bd5](https://linux-hardware.org/?probe=806be57bd5) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8f7755936c](https://linux-hardware.org/?probe=8f7755936c) | Dec 14, 2023 |
| HP            | ProBook 650 G2              | [9936eed724](https://linux-hardware.org/?probe=9936eed724) | Dec 12, 2023 |
| MSI           | GF63 Thin 11UC              | [78562df77d](https://linux-hardware.org/?probe=78562df77d) | Dec 11, 2023 |
| Dell          | Precision 3550              | [0235a02831](https://linux-hardware.org/?probe=0235a02831) | Dec 10, 2023 |
| ASUSTek       | X505BP                      | [408ad7dd06](https://linux-hardware.org/?probe=408ad7dd06) | Dec 10, 2023 |
| HUAWEI        | BOM-WXX9                    | [0d970bde9a](https://linux-hardware.org/?probe=0d970bde9a) | Dec 09, 2023 |
| Acer          | Aspire E5-575               | [e6fd8cf7f1](https://linux-hardware.org/?probe=e6fd8cf7f1) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [e33632af4f](https://linux-hardware.org/?probe=e33632af4f) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [f86dd8a709](https://linux-hardware.org/?probe=f86dd8a709) | Dec 02, 2023 |
| HP            | ProBook 450 G3              | [b53f576b27](https://linux-hardware.org/?probe=b53f576b27) | Dec 02, 2023 |
| Lenovo        | G50-80 80E5                 | [75dcedad41](https://linux-hardware.org/?probe=75dcedad41) | Nov 30, 2023 |
| Dell          | XPS 13 9360                 | [8a91691d0b](https://linux-hardware.org/?probe=8a91691d0b) | Nov 30, 2023 |
| Alienware     | 17                          | [1c23fa6051](https://linux-hardware.org/?probe=1c23fa6051) | Nov 29, 2023 |
| LETSUNG       | Unknown                     | [bfbf7dfeaa](https://linux-hardware.org/?probe=bfbf7dfeaa) | Nov 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS07C01    | [c05294f5f5](https://linux-hardware.org/?probe=c05294f5f5) | Nov 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS07C01    | [dc051898f5](https://linux-hardware.org/?probe=dc051898f5) | Nov 26, 2023 |
| Apple         | MacBookPro8,1               | [1a31182007](https://linux-hardware.org/?probe=1a31182007) | Nov 26, 2023 |
| Medion        | E6214                       | [83d5d32938](https://linux-hardware.org/?probe=83d5d32938) | Nov 26, 2023 |
| HP            | Pavilion TS Sleekbook 15    | [3a3a75aa94](https://linux-hardware.org/?probe=3a3a75aa94) | Nov 26, 2023 |
| HP            | Pavilion TS Sleekbook 15    | [9c76ca1014](https://linux-hardware.org/?probe=9c76ca1014) | Nov 25, 2023 |
| HP            | 250 G7 Notebook PC          | [7fce567d9e](https://linux-hardware.org/?probe=7fce567d9e) | Nov 25, 2023 |
| HP            | 245 G7                      | [42ee8e6975](https://linux-hardware.org/?probe=42ee8e6975) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [8131bff614](https://linux-hardware.org/?probe=8131bff614) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a8b99ab7f3](https://linux-hardware.org/?probe=a8b99ab7f3) | Nov 23, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [9f4829b792](https://linux-hardware.org/?probe=9f4829b792) | Nov 22, 2023 |
| HP            | Pavilion 15                 | [b12a3ea8d6](https://linux-hardware.org/?probe=b12a3ea8d6) | Nov 21, 2023 |
| HP            | Pavilion 15                 | [7239efa8fe](https://linux-hardware.org/?probe=7239efa8fe) | Nov 20, 2023 |
| Acer          | Aspire E5-575G              | [41d4402bf3](https://linux-hardware.org/?probe=41d4402bf3) | Nov 17, 2023 |
| HP            | 250 G5 Notebook PC          | [f6d6d655df](https://linux-hardware.org/?probe=f6d6d655df) | Nov 16, 2023 |
| Dell          | XPS 13 9360                 | [b9f38bd221](https://linux-hardware.org/?probe=b9f38bd221) | Nov 15, 2023 |
| Toshiba       | Satellite Pro L100          | [429902b4e5](https://linux-hardware.org/?probe=429902b4e5) | Nov 15, 2023 |
| Acer          | AOA110                      | [a6b7a86c67](https://linux-hardware.org/?probe=a6b7a86c67) | Nov 14, 2023 |
| MSI           | Thin GF63 12HW              | [087220685a](https://linux-hardware.org/?probe=087220685a) | Nov 14, 2023 |
| Toshiba       | Satellite Pro L100          | [ade0fd48dc](https://linux-hardware.org/?probe=ade0fd48dc) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [c00b5e7c16](https://linux-hardware.org/?probe=c00b5e7c16) | Nov 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | [e45cab7f2c](https://linux-hardware.org/?probe=e45cab7f2c) | Nov 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [feaa9f3eac](https://linux-hardware.org/?probe=feaa9f3eac) | Nov 11, 2023 |
| HP            | 250 G8 Notebook PC          | [54073a3305](https://linux-hardware.org/?probe=54073a3305) | Nov 09, 2023 |
| Toshiba       | Satellite L745              | [4dbd78f68d](https://linux-hardware.org/?probe=4dbd78f68d) | Nov 09, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [c594d3daae](https://linux-hardware.org/?probe=c594d3daae) | Nov 09, 2023 |
| IBM           | ThinkPad T40 23736G4        | [5c1d0bcbb2](https://linux-hardware.org/?probe=5c1d0bcbb2) | Nov 08, 2023 |
| Acer          | Aspire A315-21              | [f51da852ca](https://linux-hardware.org/?probe=f51da852ca) | Nov 07, 2023 |
| Acer          | Aspire A315-21              | [35b7b043ff](https://linux-hardware.org/?probe=35b7b043ff) | Nov 07, 2023 |
| Google        | Akemi                       | [f19a7fb862](https://linux-hardware.org/?probe=f19a7fb862) | Nov 06, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [d86018bbd8](https://linux-hardware.org/?probe=d86018bbd8) | Nov 06, 2023 |
| Dell          | XPS 17 9720                 | [39e8a692ae](https://linux-hardware.org/?probe=39e8a692ae) | Nov 05, 2023 |
| HP            | 250 G8 Notebook PC          | [a2fbd58a8c](https://linux-hardware.org/?probe=a2fbd58a8c) | Nov 05, 2023 |
| Google        | Akemi                       | [350f53d84a](https://linux-hardware.org/?probe=350f53d84a) | Nov 05, 2023 |
| Medion        | E6214                       | [776be82bf6](https://linux-hardware.org/?probe=776be82bf6) | Nov 04, 2023 |
| Medion        | E6214                       | [65976063e7](https://linux-hardware.org/?probe=65976063e7) | Nov 04, 2023 |
| HP            | 246 G6 Notebook PC          | [cd997e5a97](https://linux-hardware.org/?probe=cd997e5a97) | Nov 03, 2023 |
| HP            | 255 G6 Notebook PC          | [b73e7cf536](https://linux-hardware.org/?probe=b73e7cf536) | Nov 03, 2023 |
| Multilaser    | PC13X                       | [1c6a314055](https://linux-hardware.org/?probe=1c6a314055) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [a0c7507d6d](https://linux-hardware.org/?probe=a0c7507d6d) | Nov 03, 2023 |
| Google        | Akemi                       | [20ec65943c](https://linux-hardware.org/?probe=20ec65943c) | Nov 02, 2023 |
| ASUSTek       | X456UR                      | [9a0a4dfd02](https://linux-hardware.org/?probe=9a0a4dfd02) | Nov 02, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [826dc000ff](https://linux-hardware.org/?probe=826dc000ff) | Nov 01, 2023 |
| HP            | Notebook                    | [b1491b73ae](https://linux-hardware.org/?probe=b1491b73ae) | Oct 31, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [1107919053](https://linux-hardware.org/?probe=1107919053) | Oct 31, 2023 |
| ASUSTek       | X540YA                      | [082e5b7e0b](https://linux-hardware.org/?probe=082e5b7e0b) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [1267d6df00](https://linux-hardware.org/?probe=1267d6df00) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9f0452aba6](https://linux-hardware.org/?probe=9f0452aba6) | Oct 29, 2023 |
| Lenovo        | ThinkPad T420 4236W1Y       | [2ff5cba7a7](https://linux-hardware.org/?probe=2ff5cba7a7) | Oct 29, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [a899ecd171](https://linux-hardware.org/?probe=a899ecd171) | Oct 27, 2023 |
| Toshiba       | Satellite L745              | [c126c9e041](https://linux-hardware.org/?probe=c126c9e041) | Oct 27, 2023 |
| Avell High... | 1513 Mxti                   | [9f5d60c02b](https://linux-hardware.org/?probe=9f5d60c02b) | Oct 27, 2023 |
| ASUSTek       | X505BP                      | [884529eef1](https://linux-hardware.org/?probe=884529eef1) | Oct 26, 2023 |
| ASUSTek       | X505BP                      | [f32e8922c8](https://linux-hardware.org/?probe=f32e8922c8) | Oct 26, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD000... | [4e393023d7](https://linux-hardware.org/?probe=4e393023d7) | Oct 25, 2023 |
| HP            | Pavilion dv7                | [c3e7ebfd20](https://linux-hardware.org/?probe=c3e7ebfd20) | Oct 23, 2023 |
| Unknown       | Unknown                     | [251baa33d7](https://linux-hardware.org/?probe=251baa33d7) | Oct 23, 2023 |
| Unknown       | Unknown                     | [a06cdb13fc](https://linux-hardware.org/?probe=a06cdb13fc) | Oct 23, 2023 |
| Framework     | Laptop                      | [f78c8c1b58](https://linux-hardware.org/?probe=f78c8c1b58) | Oct 22, 2023 |
| HP            | 250 G7 Notebook PC          | [b9698d48be](https://linux-hardware.org/?probe=b9698d48be) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [77fb62615e](https://linux-hardware.org/?probe=77fb62615e) | Oct 22, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [21a31e5298](https://linux-hardware.org/?probe=21a31e5298) | Oct 21, 2023 |
| HP            | Pavilion dv7                | [3379c8b4e7](https://linux-hardware.org/?probe=3379c8b4e7) | Oct 21, 2023 |
| HP            | Pavilion dv6                | [d5669e2ea8](https://linux-hardware.org/?probe=d5669e2ea8) | Oct 19, 2023 |
| Alienware     | 13                          | [15e7dfbbab](https://linux-hardware.org/?probe=15e7dfbbab) | Oct 19, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [041aba02ce](https://linux-hardware.org/?probe=041aba02ce) | Oct 17, 2023 |
| HP            | EliteBook 840 G6            | [1d624b8227](https://linux-hardware.org/?probe=1d624b8227) | Oct 17, 2023 |
| Alienware     | 13                          | [24ce621e56](https://linux-hardware.org/?probe=24ce621e56) | Oct 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | [36282033c6](https://linux-hardware.org/?probe=36282033c6) | Oct 15, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [cf68d0c810](https://linux-hardware.org/?probe=cf68d0c810) | Oct 14, 2023 |
| HP            | ENVY dv7                    | [0972d8543e](https://linux-hardware.org/?probe=0972d8543e) | Oct 14, 2023 |
| HP            | 250 G7 Notebook PC          | [809ff050d7](https://linux-hardware.org/?probe=809ff050d7) | Oct 13, 2023 |
| Alienware     | m15                         | [9ac9acc336](https://linux-hardware.org/?probe=9ac9acc336) | Oct 12, 2023 |
| Alienware     | m15                         | [8b4a8c8fc9](https://linux-hardware.org/?probe=8b4a8c8fc9) | Oct 12, 2023 |
| Dell          | Latitude E6520              | [e29f6e9ba8](https://linux-hardware.org/?probe=e29f6e9ba8) | Oct 11, 2023 |
| Acer          | AOD270                      | [b45399c83c](https://linux-hardware.org/?probe=b45399c83c) | Oct 11, 2023 |
| Lenovo        | ThinkPad T490 20N3S7DP00    | [eb9d7ec72c](https://linux-hardware.org/?probe=eb9d7ec72c) | Oct 10, 2023 |
| Lenovo        | ThinkPad T430 2349STC       | [53e8d1302b](https://linux-hardware.org/?probe=53e8d1302b) | Oct 05, 2023 |
| Apple         | MacBookPro9,2               | [8008433230](https://linux-hardware.org/?probe=8008433230) | Oct 02, 2023 |
| Lenovo        | ThinkPad T420s 4176W23      | [0d27b7532c](https://linux-hardware.org/?probe=0d27b7532c) | Oct 02, 2023 |
| Acer          | Aspire E1-572G              | [271131f10a](https://linux-hardware.org/?probe=271131f10a) | Oct 01, 2023 |
| Acer          | Aspire E1-572G              | [438271a68c](https://linux-hardware.org/?probe=438271a68c) | Oct 01, 2023 |
| Acer          | Aspire E1-572G              | [f7375967ee](https://linux-hardware.org/?probe=f7375967ee) | Sep 30, 2023 |
| Acer          | Aspire E1-572G              | [9fe3adb466](https://linux-hardware.org/?probe=9fe3adb466) | Sep 29, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [99fb3ec5e9](https://linux-hardware.org/?probe=99fb3ec5e9) | Sep 29, 2023 |
| HP            | 250 G7 Notebook PC          | [7fb0e4c19c](https://linux-hardware.org/?probe=7fb0e4c19c) | Sep 28, 2023 |
| Dell          | Latitude E5570              | [150f9e624b](https://linux-hardware.org/?probe=150f9e624b) | Sep 28, 2023 |
| HP            | 620                         | [1bdfd56638](https://linux-hardware.org/?probe=1bdfd56638) | Sep 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [e87c0e3c00](https://linux-hardware.org/?probe=e87c0e3c00) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [b62d121676](https://linux-hardware.org/?probe=b62d121676) | Sep 26, 2023 |
| Dell          | Latitude 7390               | [7e142652b2](https://linux-hardware.org/?probe=7e142652b2) | Sep 25, 2023 |
| Acer          | Aspire A317-51G             | [16870a488b](https://linux-hardware.org/?probe=16870a488b) | Sep 24, 2023 |
| Lenovo        | ThinkPad Edge E430c 3365... | [74351c4243](https://linux-hardware.org/?probe=74351c4243) | Sep 23, 2023 |
| Toshiba       | Satellite P505              | [2b70bd8027](https://linux-hardware.org/?probe=2b70bd8027) | Sep 19, 2023 |
| Toshiba       | Satellite P505              | [a18f0420ac](https://linux-hardware.org/?probe=a18f0420ac) | Sep 18, 2023 |
| HP            | Compaq Mini 311-1100        | [eefc7ef22f](https://linux-hardware.org/?probe=eefc7ef22f) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | [ba678c25e1](https://linux-hardware.org/?probe=ba678c25e1) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | [b056244ce9](https://linux-hardware.org/?probe=b056244ce9) | Sep 17, 2023 |
| HP            | x2 210                      | [776f895eec](https://linux-hardware.org/?probe=776f895eec) | Sep 13, 2023 |
| Acer          | Aspire E1-572G              | [d508e799c4](https://linux-hardware.org/?probe=d508e799c4) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | [7b302f492e](https://linux-hardware.org/?probe=7b302f492e) | Sep 10, 2023 |
| Dell          | System Vostro 3750          | [00a11a78f5](https://linux-hardware.org/?probe=00a11a78f5) | Sep 09, 2023 |
| Dell          | Precision M4700             | [919035c3c7](https://linux-hardware.org/?probe=919035c3c7) | Sep 08, 2023 |
| Dell          | Precision M4700             | [2c666d6616](https://linux-hardware.org/?probe=2c666d6616) | Sep 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1591677e7f](https://linux-hardware.org/?probe=1591677e7f) | Sep 07, 2023 |
| HP            | Laptop 14-dk1xxx            | [c7bea10745](https://linux-hardware.org/?probe=c7bea10745) | Sep 07, 2023 |
| Dell          | Precision M4700             | [3e354770b6](https://linux-hardware.org/?probe=3e354770b6) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [0deab6fc8b](https://linux-hardware.org/?probe=0deab6fc8b) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [479d5ea49e](https://linux-hardware.org/?probe=479d5ea49e) | Sep 06, 2023 |
| Lenovo        | 3000 N200 0769EGG           | [44fd3c6e60](https://linux-hardware.org/?probe=44fd3c6e60) | Sep 04, 2023 |
| Lenovo        | ThinkPad L390 20NR000FUS    | [b4d7adfb97](https://linux-hardware.org/?probe=b4d7adfb97) | Sep 01, 2023 |
| HP            | ENVY m6                     | [eea19d891e](https://linux-hardware.org/?probe=eea19d891e) | Aug 31, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [decfff1e51](https://linux-hardware.org/?probe=decfff1e51) | Aug 25, 2023 |
| Dell          | XPS 13 9310                 | [e6c72eb614](https://linux-hardware.org/?probe=e6c72eb614) | Aug 24, 2023 |
| Lenovo        | ThinkPad P51s 20HCS0660Y    | [e5c40536c3](https://linux-hardware.org/?probe=e5c40536c3) | Aug 23, 2023 |
| Lenovo        | ThinkPad P51s 20HCS0660Y    | [0f2259e2b8](https://linux-hardware.org/?probe=0f2259e2b8) | Aug 22, 2023 |
| Positivo      | CHT14B                      | [28106aa94b](https://linux-hardware.org/?probe=28106aa94b) | Aug 19, 2023 |
| Gateway       | NE71B                       | [ba5e9df4ec](https://linux-hardware.org/?probe=ba5e9df4ec) | Aug 18, 2023 |
| Multilaser    | PC13X                       | [d79767b027](https://linux-hardware.org/?probe=d79767b027) | Aug 15, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | [61edf8f5ee](https://linux-hardware.org/?probe=61edf8f5ee) | Aug 14, 2023 |
| HP            | Laptop 15-da0xxx            | [0cb4da66e3](https://linux-hardware.org/?probe=0cb4da66e3) | Aug 07, 2023 |
| HP            | Notebook                    | [499fc30d3a](https://linux-hardware.org/?probe=499fc30d3a) | Aug 03, 2023 |
| GPU Compan... | GWTN156-5                   | [9d7e65fc0f](https://linux-hardware.org/?probe=9d7e65fc0f) | Jul 29, 2023 |
| Gateway       | NE71B                       | [341f524bc5](https://linux-hardware.org/?probe=341f524bc5) | Jul 26, 2023 |
| Lenovo        | IdeaPadFlex 14D 20333       | [65dfd39fb4](https://linux-hardware.org/?probe=65dfd39fb4) | Jul 21, 2023 |
| Lenovo        | IdeaPadFlex 14D 20333       | [f7fcf9f782](https://linux-hardware.org/?probe=f7fcf9f782) | Jul 21, 2023 |
| Teclast       | F6 Pro                      | [d9f3a038e0](https://linux-hardware.org/?probe=d9f3a038e0) | Jul 17, 2023 |
| Lenovo        | ThinkPad W530 2447CN4       | [670e470556](https://linux-hardware.org/?probe=670e470556) | Jul 16, 2023 |
| Dell          | Inspiron 1525               | [d63b2efc8b](https://linux-hardware.org/?probe=d63b2efc8b) | Jul 13, 2023 |
| Fujitsu Si... | AMILO Pa 1510               | [b51a760728](https://linux-hardware.org/?probe=b51a760728) | Jul 09, 2023 |
| Lenovo        | ThinkPad X240 20AMS3S919    | [63e13bb1f2](https://linux-hardware.org/?probe=63e13bb1f2) | Jul 08, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [bdc65d0c9f](https://linux-hardware.org/?probe=bdc65d0c9f) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [da20e0f159](https://linux-hardware.org/?probe=da20e0f159) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d8113bbdf6](https://linux-hardware.org/?probe=d8113bbdf6) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | [703ae4bd0b](https://linux-hardware.org/?probe=703ae4bd0b) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | [bf3c982248](https://linux-hardware.org/?probe=bf3c982248) | Jun 30, 2023 |
| Acer          | Aspire xxxx                 | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4ae6c879aa](https://linux-hardware.org/?probe=4ae6c879aa) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [888133764a](https://linux-hardware.org/?probe=888133764a) | Jun 21, 2023 |
| HP            | EliteBook 820 G2            | [d4f506e331](https://linux-hardware.org/?probe=d4f506e331) | Jun 21, 2023 |
| HP            | Compaq 15                   | [d89a75cb42](https://linux-hardware.org/?probe=d89a75cb42) | Jun 20, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [e6e1708182](https://linux-hardware.org/?probe=e6e1708182) | Jun 18, 2023 |
| HP            | Compaq 15                   | [a60f50ade5](https://linux-hardware.org/?probe=a60f50ade5) | Jun 18, 2023 |
| Medion        | E6214                       | [5547ea042f](https://linux-hardware.org/?probe=5547ea042f) | Jun 17, 2023 |
| Medion        | E6214                       | [98ddb6700a](https://linux-hardware.org/?probe=98ddb6700a) | Jun 17, 2023 |
| STONE COMP... | NOTCHA-286                  | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [3eb12fd9bc](https://linux-hardware.org/?probe=3eb12fd9bc) | Jun 10, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| Google        | Lick                        | [d220804cab](https://linux-hardware.org/?probe=d220804cab) | Jun 08, 2023 |
| Dell          | G5 5587                     | [909f234c06](https://linux-hardware.org/?probe=909f234c06) | Jun 06, 2023 |
| Acer          | Aspire 7745G                | [135ce50995](https://linux-hardware.org/?probe=135ce50995) | Jun 03, 2023 |
| Dell          | Inspiron N4030              | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Lenovo        | G50-45 80E3                 | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Framework     | Laptop                      | [cdc855ea4c](https://linux-hardware.org/?probe=cdc855ea4c) | May 26, 2023 |
| Lenovo        | ThinkPad E495 20NES0RS00    | [6f507e12bc](https://linux-hardware.org/?probe=6f507e12bc) | May 25, 2023 |
| Dell          | Latitude E6520              | [bb8bc9b8ae](https://linux-hardware.org/?probe=bb8bc9b8ae) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | [91945b5bb5](https://linux-hardware.org/?probe=91945b5bb5) | May 23, 2023 |
| Timi          | RedmiBook 14-APCS           | [04d3c59d2c](https://linux-hardware.org/?probe=04d3c59d2c) | May 22, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| Acer          | Aspire A515-56              | [feb9ed8589](https://linux-hardware.org/?probe=feb9ed8589) | May 19, 2023 |
| Acer          | Aspire A515-56              | [42d9eb5bf8](https://linux-hardware.org/?probe=42d9eb5bf8) | May 13, 2023 |
| Acer          | Aspire A515-56              | [7c946d461d](https://linux-hardware.org/?probe=7c946d461d) | May 13, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| Dell          | Latitude 7400               | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| AZW           | SEi                         | [4cd6ab54ba](https://linux-hardware.org/?probe=4cd6ab54ba) | May 08, 2023 |
| Medion        | E6214                       | [869c63244c](https://linux-hardware.org/?probe=869c63244c) | May 06, 2023 |
| Medion        | E6214                       | [64eeb6e165](https://linux-hardware.org/?probe=64eeb6e165) | May 06, 2023 |
| HP            | Compaq Presario CQ60        | [c8347acd5d](https://linux-hardware.org/?probe=c8347acd5d) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Dell          | Latitude 7480               | [fd7043408f](https://linux-hardware.org/?probe=fd7043408f) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [3e42d222a0](https://linux-hardware.org/?probe=3e42d222a0) | May 02, 2023 |
| Dell          | Studio 1555                 | [4f9f0dc9bf](https://linux-hardware.org/?probe=4f9f0dc9bf) | May 01, 2023 |
| Lenovo        | 4068AGJ                     | [6a2c3207b5](https://linux-hardware.org/?probe=6a2c3207b5) | May 01, 2023 |
| HP            | Compaq 15                   | [0c65bb3d3c](https://linux-hardware.org/?probe=0c65bb3d3c) | May 01, 2023 |
| Medion        | E6214                       | [7bb9f39d76](https://linux-hardware.org/?probe=7bb9f39d76) | Apr 30, 2023 |
| Medion        | E6214                       | [39747632e6](https://linux-hardware.org/?probe=39747632e6) | Apr 30, 2023 |
| Toshiba       | Satellite C850-D8K          | [a27eb72e94](https://linux-hardware.org/?probe=a27eb72e94) | Apr 29, 2023 |
| HP            | 250 G7 Notebook PC          | [e5fe9aa407](https://linux-hardware.org/?probe=e5fe9aa407) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | [73e11e9235](https://linux-hardware.org/?probe=73e11e9235) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | [f2f50094ba](https://linux-hardware.org/?probe=f2f50094ba) | Apr 28, 2023 |
| ASUSTek       | Z550SA                      | [7c6c0c9599](https://linux-hardware.org/?probe=7c6c0c9599) | Apr 28, 2023 |
| GPU Compan... | GWTN156-5                   | [60d207eb63](https://linux-hardware.org/?probe=60d207eb63) | Apr 27, 2023 |
| GPU Compan... | GWTN156-5                   | [df6b1e8e17](https://linux-hardware.org/?probe=df6b1e8e17) | Apr 26, 2023 |
| GPU Compan... | GWTN156-5                   | [a22605adc9](https://linux-hardware.org/?probe=a22605adc9) | Apr 25, 2023 |
| Acer          | Aspire A515-56              | [a3a13c5cb1](https://linux-hardware.org/?probe=a3a13c5cb1) | Apr 24, 2023 |
| Acer          | Aspire A515-56              | [1d5b5dcfc7](https://linux-hardware.org/?probe=1d5b5dcfc7) | Apr 24, 2023 |
| LG Electro... | A530-T.BE76P1               | [8bb0353706](https://linux-hardware.org/?probe=8bb0353706) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [b699c8ed48](https://linux-hardware.org/?probe=b699c8ed48) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [f5c282ca6c](https://linux-hardware.org/?probe=f5c282ca6c) | Apr 22, 2023 |
| GPU Compan... | GWTN156-2BK                 | [3f172b49f2](https://linux-hardware.org/?probe=3f172b49f2) | Apr 21, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [ac404082b4](https://linux-hardware.org/?probe=ac404082b4) | Apr 18, 2023 |
| Apple         | MacBookPro9,2               | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Gear          | Geranium                    | [5e67931961](https://linux-hardware.org/?probe=5e67931961) | Apr 17, 2023 |
| Gear          | Geranium                    | [fe70506e6c](https://linux-hardware.org/?probe=fe70506e6c) | Apr 17, 2023 |
| Medion        | E6214                       | [ff06e74c6d](https://linux-hardware.org/?probe=ff06e74c6d) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| Medion        | E6214                       | [ab33cd63b8](https://linux-hardware.org/?probe=ab33cd63b8) | Apr 16, 2023 |
| Apple         | MacBookPro11,1              | [12cb955c6f](https://linux-hardware.org/?probe=12cb955c6f) | Apr 15, 2023 |
| Unknown       | Unknown                     | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| HP            | ZBook 15 G4                 | [816bb7a55c](https://linux-hardware.org/?probe=816bb7a55c) | Apr 06, 2023 |
| Dell          | Precision M4800             | [9283851416](https://linux-hardware.org/?probe=9283851416) | Apr 06, 2023 |
| Kruger&Mat... | KM1406                      | [1b536904d4](https://linux-hardware.org/?probe=1b536904d4) | Apr 05, 2023 |
| GPU Compan... | GWTN156-2BK                 | [3ebdd0188a](https://linux-hardware.org/?probe=3ebdd0188a) | Apr 05, 2023 |
| HP            | 250 G7 Notebook PC          | [3995abb8b8](https://linux-hardware.org/?probe=3995abb8b8) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Medion        | E6214                       | [79f326e572](https://linux-hardware.org/?probe=79f326e572) | Apr 01, 2023 |
| Medion        | E6214                       | [5766389c97](https://linux-hardware.org/?probe=5766389c97) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Medion        | E6214                       | [298e2f9c69](https://linux-hardware.org/?probe=298e2f9c69) | Mar 31, 2023 |
| HP            | Pavilion dm4                | [b7f2f9e2ab](https://linux-hardware.org/?probe=b7f2f9e2ab) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [3844e429b1](https://linux-hardware.org/?probe=3844e429b1) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [9cb1834208](https://linux-hardware.org/?probe=9cb1834208) | Mar 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [6ac9c53a7e](https://linux-hardware.org/?probe=6ac9c53a7e) | Mar 26, 2023 |
| Medion        | E6214                       | [8ff346be04](https://linux-hardware.org/?probe=8ff346be04) | Mar 26, 2023 |
| Haier         | S15                         | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| Acer          | Aspire E1-572G              | [ce4febfe16](https://linux-hardware.org/?probe=ce4febfe16) | Mar 25, 2023 |
| Haier         | S15                         | [083feb0355](https://linux-hardware.org/?probe=083feb0355) | Mar 25, 2023 |
| Toshiba       | Satellite Pro A50-C         | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| Star Labs     | StarBook                    | [b3957ad08f](https://linux-hardware.org/?probe=b3957ad08f) | Mar 22, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [f7727e4bcb](https://linux-hardware.org/?probe=f7727e4bcb) | Mar 17, 2023 |
| Acer          | Swift SF314-51              | [b410a4c017](https://linux-hardware.org/?probe=b410a4c017) | Mar 14, 2023 |
| HP            | Pavilion dv6                | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| Dell          | Inspiron 5515               | [22dd14abae](https://linux-hardware.org/?probe=22dd14abae) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-G         | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| Lenovo        | ThinkPad Z61m 9450HAG       | [5aa66edd35](https://linux-hardware.org/?probe=5aa66edd35) | Mar 04, 2023 |
| Acer          | Aspire 5732Z                | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| HIPER         | WORKBOOK                    | [85085220c9](https://linux-hardware.org/?probe=85085220c9) | Mar 01, 2023 |
| Toshiba       | Satellite L300              | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| HP            | 2000                        | [2e234233cc](https://linux-hardware.org/?probe=2e234233cc) | Feb 25, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [5ad40efe5c](https://linux-hardware.org/?probe=5ad40efe5c) | Feb 24, 2023 |
| HP            | 250 G8 Notebook PC          | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [aa5d23bc20](https://linux-hardware.org/?probe=aa5d23bc20) | Feb 19, 2023 |
| itel Mobil... | SPIRIT 2                    | [8c370ddf38](https://linux-hardware.org/?probe=8c370ddf38) | Feb 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [392442adfb](https://linux-hardware.org/?probe=392442adfb) | Feb 16, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [da4802f871](https://linux-hardware.org/?probe=da4802f871) | Feb 12, 2023 |
| Compaq        | 420                         | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| HP            | ProBook 650 G2              | [b8854f5844](https://linux-hardware.org/?probe=b8854f5844) | Feb 12, 2023 |
| Star Labs     | StarBook                    | [08e31c8ad5](https://linux-hardware.org/?probe=08e31c8ad5) | Feb 10, 2023 |
| Dell          | Precision M4800             | [3f97bef125](https://linux-hardware.org/?probe=3f97bef125) | Feb 08, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3e0851346e](https://linux-hardware.org/?probe=3e0851346e) | Feb 08, 2023 |
| TUXEDO        | N8xxEZ                      | [680bdf5ada](https://linux-hardware.org/?probe=680bdf5ada) | Feb 07, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3301121a5c](https://linux-hardware.org/?probe=3301121a5c) | Feb 04, 2023 |
| Samsung       | RV415/RV515                 | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Samsung       | RV415/RV515                 | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| Acer          | Aspire 3810T                | [a7b93a7119](https://linux-hardware.org/?probe=a7b93a7119) | Jan 29, 2023 |
| Google        | Candy                       | [2b2368d61b](https://linux-hardware.org/?probe=2b2368d61b) | Jan 28, 2023 |
| Acer          | Aspire 3810T                | [c77f7df143](https://linux-hardware.org/?probe=c77f7df143) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Compaq        | 420                         | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| Toshiba       | Satellite L305              | [d1a0c1ddf7](https://linux-hardware.org/?probe=d1a0c1ddf7) | Jan 23, 2023 |
| Dell          | Precision 5520              | [f2b0c15a6d](https://linux-hardware.org/?probe=f2b0c15a6d) | Jan 22, 2023 |
| Dell          | Precision 5520              | [c202a2fa19](https://linux-hardware.org/?probe=c202a2fa19) | Jan 22, 2023 |
| Fujitsu       | M2010                       | [dec6151200](https://linux-hardware.org/?probe=dec6151200) | Jan 20, 2023 |
| Toshiba       | PORTEGE M780                | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| Google        | Candy                       | [f1609bed25](https://linux-hardware.org/?probe=f1609bed25) | Jan 16, 2023 |
| Toshiba       | PORTEGE Z30-B               | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Lenovo        | B50-70 20384                | [0153a9926a](https://linux-hardware.org/?probe=0153a9926a) | Jan 13, 2023 |
| Lenovo        | B560                        | [e5a272b9c1](https://linux-hardware.org/?probe=e5a272b9c1) | Jan 13, 2023 |
| ASUSTek       | K54L                        | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Fujitsu       | LIFEBOOK E736               | [96cf85d764](https://linux-hardware.org/?probe=96cf85d764) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| Chuwi         | GemiBook Pro                | [ed8c1ab25e](https://linux-hardware.org/?probe=ed8c1ab25e) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Dell          | Vostro 1700                 | [66199c3f54](https://linux-hardware.org/?probe=66199c3f54) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fb967bb48d](https://linux-hardware.org/?probe=fb967bb48d) | Jan 01, 2023 |
| Google        | Ultima                      | [b389ad5a98](https://linux-hardware.org/?probe=b389ad5a98) | Dec 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [9a2f55886f](https://linux-hardware.org/?probe=9a2f55886f) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| Fujitsu       | LIFEBOOK S751               | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| TUXEDO        | N8xxEZ                      | [2e8ecb2ca4](https://linux-hardware.org/?probe=2e8ecb2ca4) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | [1055ea57f9](https://linux-hardware.org/?probe=1055ea57f9) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Apple         | MacBookAir5,1               | [f80de6076d](https://linux-hardware.org/?probe=f80de6076d) | Dec 18, 2022 |
| HP            | Notebook                    | [ef017285ee](https://linux-hardware.org/?probe=ef017285ee) | Dec 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | [917150ffce](https://linux-hardware.org/?probe=917150ffce) | Dec 18, 2022 |
| Apple         | MacBookPro13,3              | [26a498297f](https://linux-hardware.org/?probe=26a498297f) | Dec 16, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| HP            | Laptop 15s-fq2xxx           | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HP            | Madoo                       | [6a38e78ecf](https://linux-hardware.org/?probe=6a38e78ecf) | Dec 10, 2022 |
| HP            | 250 G8 Notebook PC          | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| HP            | ZBook 15 G2                 | [83117100d0](https://linux-hardware.org/?probe=83117100d0) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| Acer          | Aspire E1-570G              | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| HP            | Mini 110-1100               | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| HP            | Victus by Gaming Laptop ... | [e1dcd6d119](https://linux-hardware.org/?probe=e1dcd6d119) | Nov 28, 2022 |
| HP            | EliteBook 820 G3            | [3ca3320525](https://linux-hardware.org/?probe=3ca3320525) | Nov 24, 2022 |
| Kruger&Mat... | KM1406                      | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | [98fac29e02](https://linux-hardware.org/?probe=98fac29e02) | Nov 22, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | [53882f751e](https://linux-hardware.org/?probe=53882f751e) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Dell          | G15 5510                    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | [e656990178](https://linux-hardware.org/?probe=e656990178) | Nov 16, 2022 |
| HP            | Laptop 14-cf3xxx            | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| Sony          | SVF1532W4E                  | [33d278cd7a](https://linux-hardware.org/?probe=33d278cd7a) | Nov 12, 2022 |
| ASUSTek       | K54LY                       | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| HP            | ProBook 650 G4              | [2aec71897b](https://linux-hardware.org/?probe=2aec71897b) | Nov 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2e0c6e37a4](https://linux-hardware.org/?probe=2e0c6e37a4) | Nov 07, 2022 |
| HP            | Unknown                     | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Toshiba       | Satellite L855D             | [8ac5a3b401](https://linux-hardware.org/?probe=8ac5a3b401) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| Acer          | Aspire 3000                 | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| HP            | Pavilion dv6                | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-da0xxx            | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| HP            | Laptop 15-dw3xxx            | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| Dell          | XPS L701X                   | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| HP            | Laptop 14-cf3xxx            | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| HP            | Laptop 15-da0xxx            | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| ASUSTek       | K56CB                       | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
| Medion        | P15648                      | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Lenovo        | Yoga 2 11 20332             | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| Acer          | Aspire 5930                 | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | Latitude E6330              | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Lenovo        | G500 20236                  | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| Microtech     | ebookPro                    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| HP            | Notebook                    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| HP            | Laptop 14-cf3xxx            | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| HP            | Laptop 14-cf3xxx            | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| HP            | Laptop 14-cf3xxx            | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
| Acer          | Aspire 3820                 | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Framework     | Laptop                      | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| HP            | Laptop 14-cf3xxx            | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | Laptop 14-dk1xxx            | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| AMI           | T3 MRD                      | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| HP            | 255 G5 Notebook PC          | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Multilaser    | PC150                       | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| HP            | Laptop 14-cf3xxx            | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| Dell          | XPS 13 9305                 | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron 5566               | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Philco        | 10D                         | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| Acer          | Aspire E1-532               | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| HP            | Presario C500 (GF581UA#A... | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Acer          | AOD270                      | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Apple         | MacBookPro14,1              | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Acer          | AOD270                      | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Toshiba       | Satellite L455              | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Howard Com... | R7X                         | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [6fbd04d8fd](https://linux-hardware.org/?probe=6fbd04d8fd) | Apr 11, 2022 |
| Howard Com... | R7X                         | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| Dell          | Latitude 5511               | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| Dell          | Precision 7520              | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| LincPlus      | LINNCPLUS P1                | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| ASUSTek       | 901                         | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| Packard Be... | DOT S                       | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Dell          | Latitude D620               | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| Toshiba       | Satellite L455              | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| Acer          | TravelMate 420              | [13cae0e399](https://linux-hardware.org/?probe=13cae0e399) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z470                | [b1ca65b3e0](https://linux-hardware.org/?probe=b1ca65b3e0) | Mar 08, 2022 |
| ASUSTek       | X101CH                      | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Dell          | Latitude D620               | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| HP            | ENVY 6                      | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z470                | [d163816373](https://linux-hardware.org/?probe=d163816373) | Mar 02, 2022 |
| ASUSTek       | UX490UAR                    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| Acer          | Swift SF315-52              | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [e2ab1c19df](https://linux-hardware.org/?probe=e2ab1c19df) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| EVOO          | EVC141-12                   | [25710a76b8](https://linux-hardware.org/?probe=25710a76b8) | Feb 18, 2022 |
| Samsung       | NC210/NC110                 | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| ASUSTek       | X101CH                      | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| ASUSTek       | 901                         | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Acer          | Aspire 3820                 | [e6091c93a9](https://linux-hardware.org/?probe=e6091c93a9) | Feb 02, 2022 |
| Toshiba       | Satellite A200              | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| LG Electro... | A530-T.BE76P1               | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Google        | Falco                       | [f450676688](https://linux-hardware.org/?probe=f450676688) | Jan 09, 2022 |
| Packard Be... | EasyNote TE69BM             | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [41e93113b5](https://linux-hardware.org/?probe=41e93113b5) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [c977f6d6af](https://linux-hardware.org/?probe=c977f6d6af) | Jan 05, 2022 |
| ASUSTek       | K46CA                       | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| Advent        | Monza T100                  | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| Acer          | Aspire V5-573G              | [4c03d73b65](https://linux-hardware.org/?probe=4c03d73b65) | Dec 18, 2021 |
| HP            | Pavilion 14                 | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire 3820                 | [b2f24124da](https://linux-hardware.org/?probe=b2f24124da) | Dec 14, 2021 |
| Acer          | Aspire 3820                 | [c4ed088328](https://linux-hardware.org/?probe=c4ed088328) | Dec 14, 2021 |
| Sony          | VPCP116KG                   | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| Fujitsu       | STYLISTIC Q550              | [e5d7b73e7f](https://linux-hardware.org/?probe=e5d7b73e7f) | Dec 12, 2021 |
| Fujitsu       | STYLISTIC Q550              | [8138236f20](https://linux-hardware.org/?probe=8138236f20) | Dec 12, 2021 |
| Lenovo        | G40-30 80FY                 | [43ff865e00](https://linux-hardware.org/?probe=43ff865e00) | Nov 28, 2021 |
| HP            | Pavilion dv6                | [5300296119](https://linux-hardware.org/?probe=5300296119) | Nov 27, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| Samsung       | 305U1A                      | [c602ad4903](https://linux-hardware.org/?probe=c602ad4903) | Nov 18, 2021 |
| Acer          | Aspire 3000                 | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| Acer          | Aspire 3000                 | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Toshiba       | Satellite L50-C             | [5a9ebbcad0](https://linux-hardware.org/?probe=5a9ebbcad0) | Nov 09, 2021 |
| Acer          | Aspire E5-411               | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Latitude D630               | [ac9f57ab8f](https://linux-hardware.org/?probe=ac9f57ab8f) | Nov 02, 2021 |
| TUXEDO        | BC1510 1710                 | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| Acer          | Aspire A315-55G             | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| Acer          | Swift SF515-51T             | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| HP            | 520                         | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| Dell          | Precision M2800             | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Apple         | MacBookPro5,4               | [d5625a9406](https://linux-hardware.org/?probe=d5625a9406) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| Qbex          | UDPAIOQBEX01                | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| IBM           | ThinkPad T41 23737JY        | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| HP            | 250 G2                      | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| Matsushita... | CF-19DDGZXVM                | [6f54a42d76](https://linux-hardware.org/?probe=6f54a42d76) | Sep 08, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Dell          | XPS M1330                   | [9dbd1f4ad9](https://linux-hardware.org/?probe=9dbd1f4ad9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASUSTek       | M51Sn                       | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| ASUSTek       | N550JV                      | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [53ee243536](https://linux-hardware.org/?probe=53ee243536) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [eafe3a403f](https://linux-hardware.org/?probe=eafe3a403f) | Jul 30, 2021 |
| Toshiba       | Satellite L855              | [354b3bf7c6](https://linux-hardware.org/?probe=354b3bf7c6) | Jul 30, 2021 |
| ASUSTek       | 1201NL                      | [1ff8ed5a66](https://linux-hardware.org/?probe=1ff8ed5a66) | Jul 29, 2021 |
| ASUSTek       | 1201NL                      | [78fb5dfca9](https://linux-hardware.org/?probe=78fb5dfca9) | Jul 29, 2021 |
| HP            | EliteBook 8470p             | [5ea0d9d644](https://linux-hardware.org/?probe=5ea0d9d644) | Jul 29, 2021 |
| Dell          | Inspiron 15-3567            | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [10ca362cf0](https://linux-hardware.org/?probe=10ca362cf0) | Jul 19, 2021 |
| Dell          | XPS M1330                   | [55de50364d](https://linux-hardware.org/?probe=55de50364d) | Jul 17, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | [a3f3785bc1](https://linux-hardware.org/?probe=a3f3785bc1) | Jul 15, 2021 |
| Dell          | Latitude E5520              | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Fujitsu Si... | AMILO Pa 2510               | [a4303cc0cf](https://linux-hardware.org/?probe=a4303cc0cf) | Jul 12, 2021 |
| Qbex          | UDPAIOQBEX01                | [9b96573429](https://linux-hardware.org/?probe=9b96573429) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| ASUSTek       | M6Ne                        | [ae1c7d3df6](https://linux-hardware.org/?probe=ae1c7d3df6) | Jul 11, 2021 |
| Dell          | Inspiron 7520               | [fbc1ae17b4](https://linux-hardware.org/?probe=fbc1ae17b4) | Jul 10, 2021 |
| Dell          | Inspiron 7520               | [e9bbf0622c](https://linux-hardware.org/?probe=e9bbf0622c) | Jul 10, 2021 |
| HP            | Laptop 14-df0xxx            | [ce0ac9c2fe](https://linux-hardware.org/?probe=ce0ac9c2fe) | Jul 10, 2021 |
| Samsung       | R59/R60/R61                 | [c0f5798a5b](https://linux-hardware.org/?probe=c0f5798a5b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [f9a80b7b6b](https://linux-hardware.org/?probe=f9a80b7b6b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [c7ddbbda0a](https://linux-hardware.org/?probe=c7ddbbda0a) | Jun 27, 2021 |
| Lenovo        | ThinkPad X100e 28762FP      | [95661d2e39](https://linux-hardware.org/?probe=95661d2e39) | Jun 27, 2021 |
| SAELITE       | ES1AU11                     | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| Acer          | Aspire 3000                 | [d0c68c57a8](https://linux-hardware.org/?probe=d0c68c57a8) | Jun 26, 2021 |
| Samsung       | RV413/RV513                 | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Gateway       | M675                        | [ebdf5aa678](https://linux-hardware.org/?probe=ebdf5aa678) | Jun 25, 2021 |
| Acer          | Aspire one                  | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | [b96ab4b06e](https://linux-hardware.org/?probe=b96ab4b06e) | Jun 18, 2021 |
| HP            | Presario R4100 (EC375UA#... | [9072bce23d](https://linux-hardware.org/?probe=9072bce23d) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | [b557ccbf94](https://linux-hardware.org/?probe=b557ccbf94) | Jun 17, 2021 |
| Dell          | Latitude E6410              | [bd3a2db03c](https://linux-hardware.org/?probe=bd3a2db03c) | Jun 16, 2021 |
| HP            | Notebook                    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| ASUSTek       | X550LN                      | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| Gateway       | LT40                        | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| ASUSTek       | X555UJ                      | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| HP            | Pavilion dv6                | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | [4f117c46f3](https://linux-hardware.org/?probe=4f117c46f3) | May 09, 2021 |
| Acer          | Aspire E5-571               | [2c91167099](https://linux-hardware.org/?probe=2c91167099) | May 07, 2021 |
| Acer          | Aspire E5-571               | [c0b2f54ba4](https://linux-hardware.org/?probe=c0b2f54ba4) | May 07, 2021 |
| HP            | 530                         | [e94b7216d1](https://linux-hardware.org/?probe=e94b7216d1) | May 06, 2021 |
| HP            | 530                         | [8e3d65488a](https://linux-hardware.org/?probe=8e3d65488a) | May 06, 2021 |
| Acer          | Aspire A515-41G             | [38e06153e9](https://linux-hardware.org/?probe=38e06153e9) | May 04, 2021 |
| Dell          | Inspiron 7520               | [3a72f19dd7](https://linux-hardware.org/?probe=3a72f19dd7) | May 01, 2021 |
| Toshiba       | dynabook Satellite J61 1... | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| Lenovo        | ThinkPad X60 1706AA7        | [34a54e1198](https://linux-hardware.org/?probe=34a54e1198) | Apr 27, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | [66346c1594](https://linux-hardware.org/?probe=66346c1594) | Apr 26, 2021 |
| Unknown       | Unknown                     | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [f961a0339b](https://linux-hardware.org/?probe=f961a0339b) | Apr 22, 2021 |
| HP            | Pavilion dv7                | [662a781c83](https://linux-hardware.org/?probe=662a781c83) | Apr 22, 2021 |
| HP            | Pavilion dv7                | [edf38b6c4a](https://linux-hardware.org/?probe=edf38b6c4a) | Apr 21, 2021 |
| HP            | 255 G7 Notebook PC          | [b243c0380f](https://linux-hardware.org/?probe=b243c0380f) | Apr 21, 2021 |
| HP            | Pavilion dv7                | [0c3668cad6](https://linux-hardware.org/?probe=0c3668cad6) | Apr 19, 2021 |
| Toshiba       | NI 1403                     | [a3789d1a53](https://linux-hardware.org/?probe=a3789d1a53) | Apr 15, 2021 |
| HP            | Pavilion dv5                | [2df1512442](https://linux-hardware.org/?probe=2df1512442) | Apr 12, 2021 |
| HP            | Pavilion dv5                | [963a9c98df](https://linux-hardware.org/?probe=963a9c98df) | Apr 12, 2021 |
| ASUSTek       | X101CH                      | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| LG Electro... | X300-L.CR31B1               | [728ce1cec3](https://linux-hardware.org/?probe=728ce1cec3) | Apr 02, 2021 |
| HP            | Mini 210-1100               | [4b8539128d](https://linux-hardware.org/?probe=4b8539128d) | Apr 01, 2021 |
| HP            | Mini 210-1100               | [a2a1a61099](https://linux-hardware.org/?probe=a2a1a61099) | Apr 01, 2021 |
| LG Electro... | X300-L.CR31B1               | [2dee5439bd](https://linux-hardware.org/?probe=2dee5439bd) | Apr 01, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| HP            | Unknown                     | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| HP            | Unknown                     | [2f594364bb](https://linux-hardware.org/?probe=2f594364bb) | Mar 20, 2021 |
| Toshiba       | Satellite L750              | [06207199fa](https://linux-hardware.org/?probe=06207199fa) | Mar 16, 2021 |
| ASUSTek       | X542UAR                     | [4a2b4a2f3d](https://linux-hardware.org/?probe=4a2b4a2f3d) | Mar 15, 2021 |
| ASUSTek       | X542UAR                     | [824a5703c6](https://linux-hardware.org/?probe=824a5703c6) | Mar 15, 2021 |
| Sony          | VGN-FZ140E                  | [1d611ce57d](https://linux-hardware.org/?probe=1d611ce57d) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | [3bfba9b2a3](https://linux-hardware.org/?probe=3bfba9b2a3) | Mar 13, 2021 |
| ASUSTek       | K46CA                       | [553bb797b4](https://linux-hardware.org/?probe=553bb797b4) | Mar 09, 2021 |
| HP            | EliteBook 8540w             | [8589da1141](https://linux-hardware.org/?probe=8589da1141) | Mar 06, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | [1d54256d1d](https://linux-hardware.org/?probe=1d54256d1d) | Mar 04, 2021 |
| HP            | Compaq Presario CQ71        | [fba2e0f27a](https://linux-hardware.org/?probe=fba2e0f27a) | Mar 01, 2021 |
| HP            | Compaq Presario CQ71        | [65e004cebd](https://linux-hardware.org/?probe=65e004cebd) | Mar 01, 2021 |
| HP            | Compaq nx7400 (EY294ET#A... | [b253d7d3fa](https://linux-hardware.org/?probe=b253d7d3fa) | Mar 01, 2021 |
| Dell          | Inspiron 5559               | [0ca0e1f04f](https://linux-hardware.org/?probe=0ca0e1f04f) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | [0dcf8f701e](https://linux-hardware.org/?probe=0dcf8f701e) | Feb 27, 2021 |
| Samsung       | NC10                        | [968b0bf5ba](https://linux-hardware.org/?probe=968b0bf5ba) | Feb 26, 2021 |
| HP            | Pavilion dv6                | [1baf6f6c70](https://linux-hardware.org/?probe=1baf6f6c70) | Feb 26, 2021 |
| Lenovo        | Y50-70 20378                | [b0a6138136](https://linux-hardware.org/?probe=b0a6138136) | Feb 25, 2021 |
| Acer          | Aspire 7750G                | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Google        | Gnawty                      | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| Dell          | Latitude E6520              | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Notebook      | WID2010                     | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| HP            | EliteBook 820 G3            | [b67948603a](https://linux-hardware.org/?probe=b67948603a) | Feb 04, 2021 |
| Acer          | Aspire 5630                 | [26e90cd431](https://linux-hardware.org/?probe=26e90cd431) | Feb 02, 2021 |
| Acer          | Aspire 5630                 | [61a1c29323](https://linux-hardware.org/?probe=61a1c29323) | Feb 02, 2021 |
| Maibenben     | XiaoMai5                    | [bd1f26e401](https://linux-hardware.org/?probe=bd1f26e401) | Feb 01, 2021 |
| Toshiba       | Satellite C50-A-1DN         | [b5e359a765](https://linux-hardware.org/?probe=b5e359a765) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | [701f078d13](https://linux-hardware.org/?probe=701f078d13) | Jan 28, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [4845dac1e6](https://linux-hardware.org/?probe=4845dac1e6) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f86be88365](https://linux-hardware.org/?probe=f86be88365) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [e6066c8531](https://linux-hardware.org/?probe=e6066c8531) | Jan 26, 2021 |
| ASUSTek       | F5N                         | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Sony          | SVE1511N1ESI                | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Matsushita... | CF-19CHB23BE                | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Dell          | Inspiron 7520               | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Acer          | AOD270                      | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Exper         | E10IL1                      | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| Dell          | Precision M4800             | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| ASUSTek       | K55N                        | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
| Dell          | Inspiron 1010               | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | [d1a973f77f](https://linux-hardware.org/?probe=d1a973f77f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | [a9ece8f5d0](https://linux-hardware.org/?probe=a9ece8f5d0) | Dec 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [7f143b3e74](https://linux-hardware.org/?probe=7f143b3e74) | Dec 20, 2020 |
| Unknown       | Unknown                     | [64b25942e1](https://linux-hardware.org/?probe=64b25942e1) | Dec 20, 2020 |
| Toshiba       | NI 1403                     | [192f91ada6](https://linux-hardware.org/?probe=192f91ada6) | Dec 19, 2020 |
| Exo           | Unknown                     | [a6c445344b](https://linux-hardware.org/?probe=a6c445344b) | Dec 17, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [1b627fe180](https://linux-hardware.org/?probe=1b627fe180) | Dec 15, 2020 |
| Acer          | Aspire one                  | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| HP            | Laptop 15-bw0xx             | [dc7e6d3f5d](https://linux-hardware.org/?probe=dc7e6d3f5d) | Dec 14, 2020 |
| HP            | Pavilion ze2000 (EA772AV... | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| Acer          | Extensa 4620                | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Matsushita... | CF-19CHB23BE                | [a81d111827](https://linux-hardware.org/?probe=a81d111827) | Nov 25, 2020 |
| ASUSTek       | X550VX                      | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| Lenovo        | ThinkPad T60p 8742C4G       | [9d369e30fd](https://linux-hardware.org/?probe=9d369e30fd) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [dbac4eb570](https://linux-hardware.org/?probe=dbac4eb570) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [b070b2d112](https://linux-hardware.org/?probe=b070b2d112) | Nov 18, 2020 |
| HP            | Compaq Presario CQ60        | [c9f4c7eefd](https://linux-hardware.org/?probe=c9f4c7eefd) | Nov 16, 2020 |
| HP            | Unknown                     | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | N90SC                       | [219009d9ea](https://linux-hardware.org/?probe=219009d9ea) | Nov 13, 2020 |
| ASUSTek       | N90SC                       | [1b802fbae0](https://linux-hardware.org/?probe=1b802fbae0) | Nov 13, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| Lenovo        | ThinkPad T420s 4174EK3      | [256f53a883](https://linux-hardware.org/?probe=256f53a883) | Nov 08, 2020 |
| Acer          | Aspire 5735                 | [3863a67ce4](https://linux-hardware.org/?probe=3863a67ce4) | Nov 07, 2020 |
| Acer          | Aspire 5735                 | [80c240fcef](https://linux-hardware.org/?probe=80c240fcef) | Nov 07, 2020 |
| HP            | Laptop 17-ca0xxx            | [ac476c2272](https://linux-hardware.org/?probe=ac476c2272) | Nov 05, 2020 |
| Dell          | Latitude 5400               | [014e9b7e76](https://linux-hardware.org/?probe=014e9b7e76) | Nov 04, 2020 |
| HP            | Laptop 17-ca0xxx            | [ab7e244449](https://linux-hardware.org/?probe=ab7e244449) | Nov 03, 2020 |
| HP            | Compaq 8510p                | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | Latitude E6220              | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| HP            | EliteBook 8470p             | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| ASUSTek       | X551MA                      | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| ASUSTek       | GL503VM                     | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| Lenovo        | B71-80 80RJ                 | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| Unknown       | Unknown                     | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| Positivo      | H14CU01                     | [3a0013a489](https://linux-hardware.org/?probe=3a0013a489) | Sep 28, 2020 |
| Positivo      | H14CU01                     | [e0d8261056](https://linux-hardware.org/?probe=e0d8261056) | Sep 28, 2020 |
| Dell          | Inspiron 5566               | [a93a422684](https://linux-hardware.org/?probe=a93a422684) | Sep 23, 2020 |
| HP            | TouchSmart tm2              | [1a91d6cc06](https://linux-hardware.org/?probe=1a91d6cc06) | Sep 22, 2020 |
| ASUSTek       | GL503VM                     | [349cf8d805](https://linux-hardware.org/?probe=349cf8d805) | Sep 17, 2020 |
| Toshiba       | NI 1403                     | [d2f6023c70](https://linux-hardware.org/?probe=d2f6023c70) | Sep 17, 2020 |
| Lenovo        | V145-15AST 81MT             | [401a915579](https://linux-hardware.org/?probe=401a915579) | Sep 10, 2020 |
| Fujitsu       | LIFEBOOK A556/G             | [9484700de9](https://linux-hardware.org/?probe=9484700de9) | Sep 10, 2020 |
| MSI           | FX610                       | [61fe175928](https://linux-hardware.org/?probe=61fe175928) | Sep 04, 2020 |
| Acer          | Aspire A315-41              | [2f541fa7c6](https://linux-hardware.org/?probe=2f541fa7c6) | Aug 23, 2020 |
| HP            | EliteBook 2540p             | [682d1b7a8c](https://linux-hardware.org/?probe=682d1b7a8c) | Aug 22, 2020 |
| Acer          | Extensa 4620                | [9421ec33ce](https://linux-hardware.org/?probe=9421ec33ce) | Aug 18, 2020 |
| HP            | Laptop 15-bs0xx             | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Acer          | Extensa 4620                | [a7701181d6](https://linux-hardware.org/?probe=a7701181d6) | Aug 17, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Dell          | Latitude E5430 non-vPro     | [2a8cc9f92c](https://linux-hardware.org/?probe=2a8cc9f92c) | Aug 04, 2020 |
| HP            | Laptop 15-bs0xx             | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| Positivo      | W310CZ-T                    | [0a1a913ef9](https://linux-hardware.org/?probe=0a1a913ef9) | Jul 19, 2020 |
| Acer          | Aspire 1640                 | [187a648c68](https://linux-hardware.org/?probe=187a648c68) | Jul 16, 2020 |
| Lenovo        | ThinkPad T61 6457W9X        | [ccd11debcb](https://linux-hardware.org/?probe=ccd11debcb) | Jul 11, 2020 |
| HP            | ProBook 430 G5              | [ea27ca7285](https://linux-hardware.org/?probe=ea27ca7285) | Jul 01, 2020 |
| ASUSTek       | E402SA                      | [46b87025ae](https://linux-hardware.org/?probe=46b87025ae) | Jul 01, 2020 |
| Acer          | Aspire 5750G                | [1f45c104e4](https://linux-hardware.org/?probe=1f45c104e4) | Jun 26, 2020 |
| Acer          | Aspire 5750G                | [5613253a47](https://linux-hardware.org/?probe=5613253a47) | Jun 26, 2020 |
| Dell          | Inspiron 3442               | [8c0a32e7f4](https://linux-hardware.org/?probe=8c0a32e7f4) | Jun 19, 2020 |
| Dell          | Inspiron 3442               | [8ed5aa8505](https://linux-hardware.org/?probe=8ed5aa8505) | Jun 19, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [012f3cadc0](https://linux-hardware.org/?probe=012f3cadc0) | Jun 16, 2020 |
| ASUSTek       | K50C                        | [1d98006287](https://linux-hardware.org/?probe=1d98006287) | Jun 15, 2020 |
| ASUSTek       | K50C                        | [141d18f0ca](https://linux-hardware.org/?probe=141d18f0ca) | Jun 15, 2020 |
| HP            | 350 G2                      | [ac2b06957f](https://linux-hardware.org/?probe=ac2b06957f) | Jun 11, 2020 |
| ASUSTek       | 1005PX                      | [8d5b0aa8df](https://linux-hardware.org/?probe=8d5b0aa8df) | Jun 03, 2020 |
| Sony          | VGN-AW41MF_H                | [baf800f176](https://linux-hardware.org/?probe=baf800f176) | May 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f4679ca184](https://linux-hardware.org/?probe=f4679ca184) | May 29, 2020 |
| HP            | EliteBook 8540w             | [4fb041418f](https://linux-hardware.org/?probe=4fb041418f) | May 29, 2020 |
| HP            | EliteBook 8540w             | [b36f5a9ddf](https://linux-hardware.org/?probe=b36f5a9ddf) | May 28, 2020 |
| ASUSTek       | K50IJ                       | [7f22ac48a8](https://linux-hardware.org/?probe=7f22ac48a8) | May 26, 2020 |
| ASUSTek       | K50IJ                       | [be86e3ea15](https://linux-hardware.org/?probe=be86e3ea15) | May 26, 2020 |
| HP            | Presario CQ61               | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Acer          | Aspire 7551                 | [d9c150f3ee](https://linux-hardware.org/?probe=d9c150f3ee) | May 24, 2020 |
| Dell          | Inspiron N5110              | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| Acer          | Aspire 4830T                | [5494761310](https://linux-hardware.org/?probe=5494761310) | May 20, 2020 |
| ASUSTek       | X550LC                      | [9c46a8ee24](https://linux-hardware.org/?probe=9c46a8ee24) | May 20, 2020 |
| ASUSTek       | X550LC                      | [b7665aa8e1](https://linux-hardware.org/?probe=b7665aa8e1) | May 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [4d4f673fb2](https://linux-hardware.org/?probe=4d4f673fb2) | May 16, 2020 |
| HP            | EliteBook 8570p             | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| Dell          | G3 3590                     | [6b37af517b](https://linux-hardware.org/?probe=6b37af517b) | May 12, 2020 |
| Toshiba       | Satellite U300              | [ef95fa82d7](https://linux-hardware.org/?probe=ef95fa82d7) | May 11, 2020 |
| HP            | G61                         | [7393752623](https://linux-hardware.org/?probe=7393752623) | May 11, 2020 |
| Dell          | Latitude E5570              | [1c8dda10a4](https://linux-hardware.org/?probe=1c8dda10a4) | May 08, 2020 |
| Dell          | Latitude E5570              | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | System Inspiron N411Z       | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| HP            | Laptop 15-bs2xx             | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| HP            | Laptop 15-bs2xx             | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | Mobile                      | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | Mobile                      | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
| Acer          | Aspire E1-572               | [941e12751c](https://linux-hardware.org/?probe=941e12751c) | Apr 14, 2020 |
| Acer          | Aspire E1-570G              | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Latitude E6510              | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| Toshiba       | Satellite P300              | [93b28f5a7c](https://linux-hardware.org/?probe=93b28f5a7c) | Apr 03, 2020 |
| ASUSTek       | ZenBook UX431FA             | [3251d5e710](https://linux-hardware.org/?probe=3251d5e710) | Apr 03, 2020 |
| Dell          | Latitude D610               | [44901c9eb2](https://linux-hardware.org/?probe=44901c9eb2) | Mar 30, 2020 |
| Dell          | Latitude D610               | [5bfecb6e64](https://linux-hardware.org/?probe=5bfecb6e64) | Mar 30, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [5c90c49af6](https://linux-hardware.org/?probe=5c90c49af6) | Mar 29, 2020 |
| Dell          | Inspiron 3543               | [5055c4067a](https://linux-hardware.org/?probe=5055c4067a) | Mar 20, 2020 |
| HP            | EliteBook 820 G3            | [b2c3317256](https://linux-hardware.org/?probe=b2c3317256) | Mar 19, 2020 |
| HP            | EliteBook 820 G3            | [2cd8614e59](https://linux-hardware.org/?probe=2cd8614e59) | Mar 17, 2020 |
| HP            | EliteBook 820 G3            | [fcb4ff46b5](https://linux-hardware.org/?probe=fcb4ff46b5) | Mar 17, 2020 |
| Lenovo        | Y50-70 20378                | [7dbce6b0fc](https://linux-hardware.org/?probe=7dbce6b0fc) | Jan 15, 2020 |
| Lenovo        | Y50-70 20378                | [11b0d93285](https://linux-hardware.org/?probe=11b0d93285) | Jan 15, 2020 |
| Dell          | Inspiron 3593               | [9f8af004d3](https://linux-hardware.org/?probe=9f8af004d3) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | [7f4ce08df9](https://linux-hardware.org/?probe=7f4ce08df9) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | [a6ee735c5f](https://linux-hardware.org/?probe=a6ee735c5f) | Nov 29, 2019 |
| Acer          | Aspire V3-571G              | [9be63e6a28](https://linux-hardware.org/?probe=9be63e6a28) | Jan 09, 2019 |
| HP            | Pavilion dv7                | [4480bf8ff3](https://linux-hardware.org/?probe=4480bf8ff3) | Dec 24, 2018 |
| Acer          | Aspire V3-571               | [bb8f83433e](https://linux-hardware.org/?probe=bb8f83433e) | Nov 27, 2018 |
| Acer          | Aspire V3-571               | [1136588271](https://linux-hardware.org/?probe=1136588271) | Nov 27, 2018 |
| HP            | ProBook 4510s               | [dbc607e890](https://linux-hardware.org/?probe=dbc607e890) | Sep 08, 2018 |
| Dell          | Inspiron 11-3162            | [92dcc778ac](https://linux-hardware.org/?probe=92dcc778ac) | Mar 19, 2018 |
| Sony          | VPCEB1M1R                   | [25b5c0689e](https://linux-hardware.org/?probe=25b5c0689e) | Mar 16, 2018 |
| Sony          | VPCSB3M1R                   | [155309a9eb](https://linux-hardware.org/?probe=155309a9eb) | Aug 23, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| LMDE 5 | 276       | 47.5%   |
| LMDE 4 | 223       | 38.38%  |
| LMDE 6 | 73        | 12.56%  |
| LMDE 3 | 6         | 1.03%   |
| LMDE 2 | 3         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| LMDE | 573       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.10.0-21-amd64       | 43        | 6.73%   |
| 6.1.0-13-amd64        | 37        | 5.79%   |
| 5.10.0-12-amd64       | 35        | 5.48%   |
| 5.10.0-19-amd64       | 29        | 4.54%   |
| 5.10.0-23-amd64       | 28        | 4.38%   |
| 4.19.0-8-amd64        | 27        | 4.23%   |
| 4.19.0-18-amd64       | 24        | 3.76%   |
| 5.10.0-14-amd64       | 20        | 3.13%   |
| 4.19.0-17-amd64       | 20        | 3.13%   |
| 4.19.0-9-amd64        | 18        | 2.82%   |
| 6.1.0-12-amd64        | 17        | 2.66%   |
| 5.10.0-20-amd64       | 17        | 2.66%   |
| 5.10.0-25-amd64       | 16        | 2.5%    |
| 5.10.0-15-amd64       | 16        | 2.5%    |
| 4.19.0-16-amd64       | 16        | 2.5%    |
| 5.10.0-18-amd64       | 14        | 2.19%   |
| 5.10.0-13-amd64       | 14        | 2.19%   |
| 4.19.0-8-686          | 14        | 2.19%   |
| 4.19.0-17-686         | 14        | 2.19%   |
| 4.19.0-14-amd64       | 13        | 2.03%   |
| 4.19.0-13-amd64       | 12        | 1.88%   |
| 5.10.0-16-amd64       | 11        | 1.72%   |
| 4.19.0-16-686         | 11        | 1.72%   |
| 4.19.0-10-amd64       | 11        | 1.72%   |
| 4.19.0-18-686         | 10        | 1.56%   |
| 4.19.0-12-amd64       | 10        | 1.56%   |
| 5.10.0-17-amd64       | 9         | 1.41%   |
| 6.1.0-16-amd64        | 8         | 1.25%   |
| 5.10.0-22-amd64       | 8         | 1.25%   |
| 4.19.0-13-686         | 7         | 1.1%    |
| 4.19.0-11-amd64       | 6         | 0.94%   |
| 5.10.0-13-686         | 5         | 0.78%   |
| 4.19.0-12-686         | 5         | 0.78%   |
| 5.18.0-0.bpo.1-amd64  | 4         | 0.63%   |
| 5.16.0-0.bpo.4-amd64  | 4         | 0.63%   |
| 4.9.0-8-amd64         | 4         | 0.63%   |
| 6.1.0-15-amd64        | 3         | 0.47%   |
| 6.1.0-0.deb11.6-amd64 | 3         | 0.47%   |
| 5.10.0-24-amd64       | 3         | 0.47%   |
| 4.19.0-19-686         | 3         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 260       | 44.07%  |
| 4.19.0  | 212       | 35.93%  |
| 6.1.0   | 74        | 12.54%  |
| 5.18.0  | 6         | 1.02%   |
| 4.9.0   | 5         | 0.85%   |
| 5.16.0  | 4         | 0.68%   |
| 6.5.0   | 3         | 0.51%   |
| 3.16.0  | 3         | 0.51%   |
| 5.6.0   | 2         | 0.34%   |
| 5.4.0   | 2         | 0.34%   |
| 5.19.0  | 2         | 0.34%   |
| 5.15.59 | 2         | 0.34%   |
| 6.6.2   | 1         | 0.17%   |
| 6.5.11  | 1         | 0.17%   |
| 6.5.10  | 1         | 0.17%   |
| 6.4.0   | 1         | 0.17%   |
| 6.1.11  | 1         | 0.17%   |
| 5.9.12  | 1         | 0.17%   |
| 5.9.0   | 1         | 0.17%   |
| 5.8.0   | 1         | 0.17%   |
| 5.4.44  | 1         | 0.17%   |
| 5.19.10 | 1         | 0.17%   |
| 5.15.78 | 1         | 0.17%   |
| 5.15.70 | 1         | 0.17%   |
| 5.15.64 | 1         | 0.17%   |
| 5.15.56 | 1         | 0.17%   |
| 5.15.0  | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 260       | 44.37%  |
| 4.19    | 212       | 36.18%  |
| 6.1     | 75        | 12.8%   |
| 5.18    | 6         | 1.02%   |
| 4.9     | 5         | 0.85%   |
| 6.5     | 4         | 0.68%   |
| 5.16    | 4         | 0.68%   |
| 5.15    | 4         | 0.68%   |
| 5.4     | 3         | 0.51%   |
| 5.19    | 3         | 0.51%   |
| 3.16    | 3         | 0.51%   |
| 5.9     | 2         | 0.34%   |
| 5.6     | 2         | 0.34%   |
| 6.6     | 1         | 0.17%   |
| 6.4     | 1         | 0.17%   |
| 5.8     | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 487       | 84.99%  |
| i686   | 86        | 15.01%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 508       | 87.14%  |
| Cinnamon   | 49        | 8.4%    |
| MATE       | 10        | 1.72%   |
| Unknown    | 6         | 1.03%   |
| LXDE       | 3         | 0.51%   |
| XFCE       | 2         | 0.34%   |
| Trinity    | 1         | 0.17%   |
| KDE        | 1         | 0.17%   |
| i3         | 1         | 0.17%   |
| GNOME      | 1         | 0.17%   |
| awesome    | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 573       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 383       | 66.03%  |
| LightDM | 178       | 30.69%  |
| TDM     | 15        | 2.59%   |
| MDM     | 3         | 0.52%   |
| GDM     | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 187       | 32.41%  |
| de_DE   | 76        | 13.17%  |
| pt_BR   | 47        | 8.15%   |
| ru_RU   | 39        | 6.76%   |
| en_GB   | 28        | 4.85%   |
| it_IT   | 21        | 3.64%   |
| pl_PL   | 20        | 3.47%   |
| fr_FR   | 20        | 3.47%   |
| es_ES   | 15        | 2.6%    |
| es_MX   | 9         | 1.56%   |
| Unknown | 8         | 1.39%   |
| es_AR   | 7         | 1.21%   |
| en_AU   | 7         | 1.21%   |
| el_GR   | 6         | 1.04%   |
| de_CH   | 6         | 1.04%   |
| nl_NL   | 5         | 0.87%   |
| en_CA   | 5         | 0.87%   |
| tr_TR   | 4         | 0.69%   |
| ja_JP   | 4         | 0.69%   |
| es_BO   | 4         | 0.69%   |
| pt_PT   | 3         | 0.52%   |
| en_NZ   | 3         | 0.52%   |
| en_IN   | 3         | 0.52%   |
| de_AT   | 3         | 0.52%   |
| da_DK   | 3         | 0.52%   |
| zh_CN   | 2         | 0.35%   |
| nl_BE   | 2         | 0.35%   |
| ko_KR   | 2         | 0.35%   |
| hu_HU   | 2         | 0.35%   |
| fr_BE   | 2         | 0.35%   |
| es_EC   | 2         | 0.35%   |
| es_CL   | 2         | 0.35%   |
| en_ZA   | 2         | 0.35%   |
| en_SG   | 2         | 0.35%   |
| en_PH   | 2         | 0.35%   |
| en_IE   | 2         | 0.35%   |
| cs_CZ   | 2         | 0.35%   |
| bg_BG   | 2         | 0.35%   |
| unm_US  | 1         | 0.17%   |
| uk_UA   | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 289       | 50.09%  |
| BIOS | 288       | 49.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 525       | 91.15%  |
| Overlay | 19        | 3.3%    |
| Tmpfs   | 13        | 2.26%   |
| Btrfs   | 13        | 2.26%   |
| Unknown | 3         | 0.52%   |
| Xfs     | 2         | 0.35%   |
| Aufs    | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 379       | 65.57%  |
| GPT     | 136       | 23.53%  |
| MBR     | 63        | 10.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 539       | 93.41%  |
| Yes       | 38        | 6.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 514       | 89.08%  |
| Yes       | 63        | 10.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 131       | 22.86%  |
| Lenovo                         | 99        | 17.28%  |
| Dell                           | 75        | 13.09%  |
| Acer                           | 56        | 9.77%   |
| ASUSTek Computer               | 55        | 9.6%    |
| Toshiba                        | 22        | 3.84%   |
| Apple                          | 13        | 2.27%   |
| Sony                           | 12        | 2.09%   |
| Samsung Electronics            | 10        | 1.75%   |
| Fujitsu Siemens                | 7         | 1.22%   |
| Unknown                        | 6         | 1.05%   |
| MSI                            | 5         | 0.87%   |
| LG Electronics                 | 5         | 0.87%   |
| Google                         | 5         | 0.87%   |
| Fujitsu                        | 5         | 0.87%   |
| Alienware                      | 5         | 0.87%   |
| Positivo                       | 4         | 0.7%    |
| Medion                         | 4         | 0.7%    |
| Packard Bell                   | 3         | 0.52%   |
| HUAWEI                         | 3         | 0.52%   |
| Gateway                        | 3         | 0.52%   |
| TUXEDO                         | 2         | 0.35%   |
| Star Labs                      | 2         | 0.35%   |
| Multilaser                     | 2         | 0.35%   |
| Matsushita Electric Industrial | 2         | 0.35%   |
| IBM                            | 2         | 0.35%   |
| GPU Company                    | 2         | 0.35%   |
| Compaq                         | 2         | 0.35%   |
| Wortmann AG                    | 1         | 0.17%   |
| Timi                           | 1         | 0.17%   |
| Teclast                        | 1         | 0.17%   |
| STONE COMPUTERS                | 1         | 0.17%   |
| Semp Toshiba                   | 1         | 0.17%   |
| SAELITE                        | 1         | 0.17%   |
| Qbex                           | 1         | 0.17%   |
| Philco                         | 1         | 0.17%   |
| Notebook                       | 1         | 0.17%   |
| Microtech                      | 1         | 0.17%   |
| Maibenben                      | 1         | 0.17%   |
| LincPlus                       | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 13        | 2.27%   |
| HP Pavilion dv6                             | 5         | 0.87%   |
| HP Notebook                                 | 5         | 0.87%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 4         | 0.7%    |
| HP 250 G8 Notebook PC                       | 4         | 0.7%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 0.52%   |
| HP Pavilion dv7                             | 3         | 0.52%   |
| HP 250 G7 Notebook PC                       | 3         | 0.52%   |
| Dell Latitude E6400                         | 3         | 0.52%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA    | 3         | 0.52%   |
| Acer Aspire E1-570G                         | 3         | 0.52%   |
| Acer Aspire 5930                            | 3         | 0.52%   |
| Acer AOD270                                 | 3         | 0.52%   |
| Star Labs StarBook                          | 2         | 0.35%   |
| LG A530-T.BE76P1                            | 2         | 0.35%   |
| Lenovo V145-15AST 81MT                      | 2         | 0.35%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ            | 2         | 0.35%   |
| Lenovo IdeaPad 3 15ITL6 82H8                | 2         | 0.35%   |
| Lenovo G500 20236                           | 2         | 0.35%   |
| Lenovo G50-45 80E3                          | 2         | 0.35%   |
| HP ProBook 650 G2                           | 2         | 0.35%   |
| HP Pavilion Notebook                        | 2         | 0.35%   |
| HP Pavilion Laptop 15-cw1xxx                | 2         | 0.35%   |
| HP Laptop 15z-ef2xxx                        | 2         | 0.35%   |
| HP Laptop 15-dw3xxx                         | 2         | 0.35%   |
| HP Laptop 15-da0xxx                         | 2         | 0.35%   |
| HP Laptop 15-bw0xx                          | 2         | 0.35%   |
| HP Laptop 14-dk1xxx                         | 2         | 0.35%   |
| HP Laptop 14-df0xxx                         | 2         | 0.35%   |
| HP EliteBook 8540w                          | 2         | 0.35%   |
| HP EliteBook 820 G3                         | 2         | 0.35%   |
| HP Compaq Presario CQ71                     | 2         | 0.35%   |
| HP Compaq Presario CQ60                     | 2         | 0.35%   |
| HP 255 G7 Notebook PC                       | 2         | 0.35%   |
| HP 14                                       | 2         | 0.35%   |
| Dell XPS 13 9360                            | 2         | 0.35%   |
| Dell Precision M4800                        | 2         | 0.35%   |
| Dell Latitude E6520                         | 2         | 0.35%   |
| Dell Latitude E6430                         | 2         | 0.35%   |
| Dell Latitude E5570                         | 2         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 51        | 8.9%    |
| Acer Aspire             | 46        | 8.03%   |
| Dell Latitude           | 28        | 4.89%   |
| HP Pavilion             | 25        | 4.36%   |
| Lenovo IdeaPad          | 22        | 3.84%   |
| HP Laptop               | 21        | 3.66%   |
| Dell Inspiron           | 20        | 3.49%   |
| Toshiba Satellite       | 19        | 3.32%   |
| HP EliteBook            | 14        | 2.44%   |
| ASUS VivoBook           | 13        | 2.27%   |
| Unknown                 | 13        | 2.27%   |
| HP ProBook              | 10        | 1.75%   |
| HP Compaq               | 10        | 1.75%   |
| Dell Precision          | 9         | 1.57%   |
| HP 250                  | 8         | 1.4%    |
| Dell XPS                | 7         | 1.22%   |
| HP Notebook             | 5         | 0.87%   |
| HP ENVY                 | 5         | 0.87%   |
| HP 255                  | 4         | 0.7%    |
| ASUS ROG                | 4         | 0.7%    |
| Samsung RV411           | 3         | 0.52%   |
| Lenovo Yoga             | 3         | 0.52%   |
| Lenovo Legion           | 3         | 0.52%   |
| HP ZBook                | 3         | 0.52%   |
| HP Presario             | 3         | 0.52%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.52%   |
| Fujitsu Siemens AMILO   | 3         | 0.52%   |
| Fujitsu LIFEBOOK        | 3         | 0.52%   |
| Dell Vostro             | 3         | 0.52%   |
| Dell System             | 3         | 0.52%   |
| Acer AOD270             | 3         | 0.52%   |
| Toshiba PORTEGE         | 2         | 0.35%   |
| Star Labs StarBook      | 2         | 0.35%   |
| Packard Bell EasyNote   | 2         | 0.35%   |
| LG A530-T.BE76P1        | 2         | 0.35%   |
| Lenovo V145-15AST       | 2         | 0.35%   |
| Lenovo ThinkBook        | 2         | 0.35%   |
| Lenovo G500             | 2         | 0.35%   |
| Lenovo G50-45           | 2         | 0.35%   |
| IBM ThinkPad            | 2         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 48        | 8.38%   |
| 2011    | 42        | 7.33%   |
| 2013    | 40        | 6.98%   |
| 2010    | 40        | 6.98%   |
| 2020    | 38        | 6.63%   |
| 2018    | 38        | 6.63%   |
| 2021    | 36        | 6.28%   |
| 2016    | 35        | 6.11%   |
| 2009    | 35        | 6.11%   |
| 2019    | 34        | 5.93%   |
| 2008    | 33        | 5.76%   |
| 2017    | 26        | 4.54%   |
| 2014    | 25        | 4.36%   |
| 2007    | 25        | 4.36%   |
| 2015    | 23        | 4.01%   |
| 2006    | 16        | 2.79%   |
| 2022    | 15        | 2.62%   |
| 2023    | 11        | 1.92%   |
| 2005    | 7         | 1.22%   |
| 2003    | 2         | 0.35%   |
| Unknown | 2         | 0.35%   |
| 2004    | 1         | 0.17%   |
| 2002    | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 573       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 533       | 92.53%  |
| Enabled  | 43        | 7.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 565       | 98.6%   |
| Yes  | 8         | 1.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 146       | 25.39%  |
| 4.01-8.0    | 144       | 25.04%  |
| 16.01-24.0  | 78        | 13.57%  |
| 8.01-16.0   | 70        | 12.17%  |
| 2.01-3.0    | 49        | 8.52%   |
| 1.01-2.0    | 48        | 8.35%   |
| 32.01-64.0  | 20        | 3.48%   |
| 0.51-1.0    | 12        | 2.09%   |
| 64.01-256.0 | 6         | 1.04%   |
| 24.01-32.0  | 2         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 263       | 42.63%  |
| 2.01-3.0   | 160       | 25.93%  |
| 0.51-1.0   | 77        | 12.48%  |
| 3.01-4.0   | 55        | 8.91%   |
| 4.01-8.0   | 45        | 7.29%   |
| 8.01-16.0  | 9         | 1.46%   |
| 0.01-0.5   | 4         | 0.65%   |
| 16.01-24.0 | 2         | 0.32%   |
| 32.01-64.0 | 1         | 0.16%   |
| 24.01-32.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 425       | 72.65%  |
| 2      | 128       | 21.88%  |
| 3      | 17        | 2.91%   |
| 0      | 8         | 1.37%   |
| 4      | 5         | 0.85%   |
| 6      | 1         | 0.17%   |
| 5      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 326       | 56.4%   |
| Yes       | 252       | 43.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 489       | 85.34%  |
| No        | 84        | 14.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 562       | 98.08%  |
| No        | 11        | 1.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 380       | 66.2%   |
| No        | 194       | 33.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 84        | 14.58%  |
| USA         | 82        | 14.24%  |
| Brazil      | 48        | 8.33%   |
| Russia      | 43        | 7.47%   |
| Italy       | 33        | 5.73%   |
| Poland      | 24        | 4.17%   |
| UK          | 21        | 3.65%   |
| France      | 21        | 3.65%   |
| Spain       | 15        | 2.6%    |
| Mexico      | 11        | 1.91%   |
| Netherlands | 10        | 1.74%   |
| Canada      | 10        | 1.74%   |
| Australia   | 10        | 1.74%   |
| Ukraine     | 7         | 1.22%   |
| Switzerland | 7         | 1.22%   |
| Belgium     | 7         | 1.22%   |
| Argentina   | 7         | 1.22%   |
| Turkey      | 6         | 1.04%   |
| Indonesia   | 6         | 1.04%   |
| Greece      | 6         | 1.04%   |
| Bulgaria    | 6         | 1.04%   |
| Belarus     | 6         | 1.04%   |
| Austria     | 6         | 1.04%   |
| Portugal    | 5         | 0.87%   |
| India       | 5         | 0.87%   |
| Ecuador     | 5         | 0.87%   |
| Sweden      | 4         | 0.69%   |
| Romania     | 4         | 0.69%   |
| Philippines | 4         | 0.69%   |
| New Zealand | 4         | 0.69%   |
| Japan       | 4         | 0.69%   |
| Chile       | 4         | 0.69%   |
| Bolivia     | 4         | 0.69%   |
| Hungary     | 3         | 0.52%   |
| Denmark     | 3         | 0.52%   |
| China       | 3         | 0.52%   |
| Bahrain     | 3         | 0.52%   |
| Venezuela   | 2         | 0.35%   |
| Tunisia     | 2         | 0.35%   |
| South Korea | 2         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 9         | 1.5%    |
| St Petersburg        | 7         | 1.16%   |
| Sao Paulo            | 7         | 1.16%   |
| Krakow               | 6         | 1%      |
| Berlin               | 6         | 1%      |
| Wroclaw              | 4         | 0.66%   |
| Rome                 | 4         | 0.66%   |
| New York             | 4         | 0.66%   |
| Munich               | 4         | 0.66%   |
| Guayaquil            | 4         | 0.66%   |
| Wohlen               | 3         | 0.5%    |
| Sydney               | 3         | 0.5%    |
| Seville              | 3         | 0.5%    |
| Rio de Janeiro       | 3         | 0.5%    |
| Poznan               | 3         | 0.5%    |
| Oruro                | 3         | 0.5%    |
| Milan                | 3         | 0.5%    |
| Miami                | 3         | 0.5%    |
| Manama               | 3         | 0.5%    |
| Madrid               | 3         | 0.5%    |
| Lisbon               | 3         | 0.5%    |
| Freiburg im Breisgau | 3         | 0.5%    |
| Frankfurt am Main    | 3         | 0.5%    |
| Bremen               | 3         | 0.5%    |
| Bologna              | 3         | 0.5%    |
| Auckland             | 3         | 0.5%    |
| Athens               | 3         | 0.5%    |
| Aalten               | 3         | 0.5%    |
| Zurich               | 2         | 0.33%   |
| Voronezh             | 2         | 0.33%   |
| Vitebsk              | 2         | 0.33%   |
| Vienna               | 2         | 0.33%   |
| Verona               | 2         | 0.33%   |
| Turin                | 2         | 0.33%   |
| Stuttgart            | 2         | 0.33%   |
| Sofia                | 2         | 0.33%   |
| Santiago             | 2         | 0.33%   |
| San Jose             | 2         | 0.33%   |
| Rostov-on-Don        | 2         | 0.33%   |
| Rennes               | 2         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 101       | 115    | 14.35%  |
| WDC                       | 90        | 101    | 12.78%  |
| Seagate                   | 80        | 100    | 11.36%  |
| Unknown                   | 43        | 58     | 6.11%   |
| Toshiba                   | 41        | 43     | 5.82%   |
| SanDisk                   | 32        | 53     | 4.55%   |
| Kingston                  | 32        | 41     | 4.55%   |
| Hitachi                   | 30        | 30     | 4.26%   |
| SK hynix                  | 22        | 24     | 3.13%   |
| Intel                     | 20        | 21     | 2.84%   |
| Crucial                   | 20        | 22     | 2.84%   |
| HGST                      | 14        | 22     | 1.99%   |
| China                     | 14        | 15     | 1.99%   |
| Micron Technology         | 12        | 14     | 1.7%    |
| Fujitsu                   | 12        | 12     | 1.7%    |
| A-DATA Technology         | 10        | 12     | 1.42%   |
| Phison                    | 6         | 7      | 0.85%   |
| KingSpec                  | 6         | 7      | 0.85%   |
| GOODRAM                   | 6         | 6      | 0.85%   |
| Apple                     | 6         | 11     | 0.85%   |
| Transcend                 | 5         | 9      | 0.71%   |
| PNY                       | 5         | 6      | 0.71%   |
| Patriot                   | 5         | 7      | 0.71%   |
| JMicron Technology        | 5         | 6      | 0.71%   |
| Intenso                   | 5         | 5      | 0.71%   |
| Unknown                   | 5         | 5      | 0.71%   |
| KingDian                  | 3         | 4      | 0.43%   |
| Hewlett-Packard           | 3         | 4      | 0.43%   |
| Gigabyte Technology       | 3         | 5      | 0.43%   |
| Team                      | 2         | 3      | 0.28%   |
| Star Drive                | 2         | 2      | 0.28%   |
| SPCC                      | 2         | 2      | 0.28%   |
| Silicon Motion            | 2         | 2      | 0.28%   |
| SABRENT                   | 2         | 3      | 0.28%   |
| Netac                     | 2         | 2      | 0.28%   |
| Micron/Crucial Technology | 2         | 5      | 0.28%   |
| KIOXIA                    | 2         | 11     | 0.28%   |
| IBM/Hitachi               | 2         | 2      | 0.28%   |
| FORESEE                   | 2         | 4      | 0.28%   |
| Fanxiang                  | 2         | 3      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 1.39%   |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 1.11%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.97%   |
| Kingston SA400S37480G 480GB SSD                     | 7         | 0.97%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 0.83%   |
| Samsung SSD 860 EVO 500GB                           | 6         | 0.83%   |
| Samsung SSD 860 EVO 1TB                             | 6         | 0.83%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 5         | 0.69%   |
| Unknown MMC Card  7GB                               | 5         | 0.69%   |
| Unknown MMC Card  64GB                              | 5         | 0.69%   |
| Unknown MMC Card  32GB                              | 5         | 0.69%   |
| SanDisk NVMe SSD Drive 256GB                        | 5         | 0.69%   |
| Crucial CT1000BX500SSD1 1TB                         | 5         | 0.69%   |
| Unknown                                             | 5         | 0.69%   |
| Unknown SD/MMC/MS PRO 512GB                         | 4         | 0.56%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 0.56%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 0.56%   |
| Seagate ST9500325AS 500GB                           | 4         | 0.56%   |
| Seagate ST9250315AS 250GB                           | 4         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 0.56%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 0.56%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 0.56%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 3         | 0.42%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 3         | 0.42%   |
| Unknown MMC Card  128GB                             | 3         | 0.42%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 0.42%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 0.42%   |
| Seagate Expansion 2TB                               | 3         | 0.42%   |
| SanDisk SSD PLUS 480GB                              | 3         | 0.42%   |
| Samsung SSD 870 EVO 500GB                           | 3         | 0.42%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3         | 0.42%   |
| Samsung MZVLQ1T0HALB-00000 1TB                      | 3         | 0.42%   |
| Kingston SUV400S37240G 240GB SSD                    | 3         | 0.42%   |
| KingSpec MT-128 128GB SSD                           | 3         | 0.42%   |
| JMicron Tech 250GB                                  | 3         | 0.42%   |
| HGST HTS545050A7E680 500GB                          | 3         | 0.42%   |
| GOODRAM SSDPR-CL100-120-G3 120GB                    | 3         | 0.42%   |
| Gigabyte GP-GSTFS31120GNTD 120GB                    | 3         | 0.42%   |
| Crucial CT240BX500SSD1 240GB                        | 3         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 79        | 98     | 30.86%  |
| WDC                 | 69        | 78     | 26.95%  |
| Toshiba             | 32        | 34     | 12.5%   |
| Hitachi             | 30        | 30     | 11.72%  |
| HGST                | 14        | 22     | 5.47%   |
| Fujitsu             | 12        | 12     | 4.69%   |
| Samsung Electronics | 7         | 7      | 2.73%   |
| Unknown             | 4         | 4      | 1.56%   |
| SABRENT             | 2         | 3      | 0.78%   |
| IBM/Hitachi         | 2         | 2      | 0.78%   |
| USB3.0              | 1         | 1      | 0.39%   |
| Intenso             | 1         | 1      | 0.39%   |
| Initio              | 1         | 1      | 0.39%   |
| DAS                 | 1         | 4      | 0.39%   |
| ASMT                | 1         | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 57        | 67     | 22.18%  |
| Kingston            | 27        | 35     | 10.51%  |
| Crucial             | 20        | 22     | 7.78%   |
| SanDisk             | 17        | 29     | 6.61%   |
| China               | 12        | 13     | 4.67%   |
| WDC                 | 9         | 9      | 3.5%    |
| Intel               | 9         | 9      | 3.5%    |
| A-DATA Technology   | 9         | 11     | 3.5%    |
| KingSpec            | 6         | 7      | 2.33%   |
| GOODRAM             | 6         | 6      | 2.33%   |
| Transcend           | 5         | 9      | 1.95%   |
| Toshiba             | 5         | 5      | 1.95%   |
| PNY                 | 5         | 6      | 1.95%   |
| Patriot             | 5         | 7      | 1.95%   |
| Apple               | 5         | 5      | 1.95%   |
| Micron Technology   | 4         | 5      | 1.56%   |
| SK hynix            | 3         | 4      | 1.17%   |
| KingDian            | 3         | 4      | 1.17%   |
| Intenso             | 3         | 3      | 1.17%   |
| Hewlett-Packard     | 3         | 4      | 1.17%   |
| Gigabyte Technology | 3         | 5      | 1.17%   |
| Team                | 2         | 3      | 0.78%   |
| SPCC                | 2         | 2      | 0.78%   |
| Netac               | 2         | 2      | 0.78%   |
| JMicron Technology  | 2         | 2      | 0.78%   |
| FORESEE             | 2         | 4      | 0.78%   |
| Emtec               | 2         | 2      | 0.78%   |
| Corsair             | 2         | 2      | 0.78%   |
| Unknown             | 2         | 2      | 0.78%   |
| WINTEC              | 1         | 1      | 0.39%   |
| USB30               | 1         | 2      | 0.39%   |
| Unknown             | 1         | 1      | 0.39%   |
| SSD PHIS            | 1         | 1      | 0.39%   |
| SCCTS-603-001T      | 1         | 1      | 0.39%   |
| Plextor             | 1         | 1      | 0.39%   |
| Phison              | 1         | 1      | 0.39%   |
| ORICO               | 1         | 1      | 0.39%   |
| Mushkin             | 1         | 1      | 0.39%   |
| Microtech           | 1         | 2      | 0.39%   |
| LITEON              | 1         | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 245       | 298    | 36.9%   |
| SSD     | 234       | 316    | 35.24%  |
| NVMe    | 125       | 168    | 18.83%  |
| MMC     | 42        | 54     | 6.33%   |
| Unknown | 18        | 23     | 2.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 443       | 587    | 69%     |
| NVMe | 124       | 167    | 19.31%  |
| MMC  | 42        | 54     | 6.54%   |
| SAS  | 33        | 51     | 5.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 355       | 455    | 75.05%  |
| 0.51-1.0   | 100       | 135    | 21.14%  |
| 1.01-2.0   | 11        | 14     | 2.33%   |
| 4.01-10.0  | 5         | 8      | 1.06%   |
| 3.01-4.0   | 1         | 1      | 0.21%   |
| 2.01-3.0   | 1         | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 211       | 36.01%  |
| 251-500        | 149       | 25.43%  |
| 501-1000       | 81        | 13.82%  |
| 51-100         | 50        | 8.53%   |
| 1001-2000      | 28        | 4.78%   |
| 21-50          | 24        | 4.1%    |
| 1-20           | 21        | 3.58%   |
| More than 3000 | 10        | 1.71%   |
| 2001-3000      | 10        | 1.71%   |
| Unknown        | 2         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 272       | 44.08%  |
| 21-50          | 136       | 22.04%  |
| 51-100         | 75        | 12.16%  |
| 101-250        | 73        | 11.83%  |
| 251-500        | 23        | 3.73%   |
| 501-1000       | 22        | 3.57%   |
| 1001-2000      | 6         | 0.97%   |
| More than 3000 | 4         | 0.65%   |
| 2001-3000      | 4         | 0.65%   |
| Unknown        | 2         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WINTEC 240GB SATA3 SF2281 SSD         | 1         | 1      | 2.78%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 2.78%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 2.78%   |
| WDC WD3200BEVT-26A23T0 320GB          | 1         | 1      | 2.78%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 1      | 2.78%   |
| WDC WD1200BEVS-07LAT0 120GB           | 1         | 1      | 2.78%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1      | 2.78%   |
| Transcend TS512GMTS430S 512GB SSD     | 1         | 1      | 2.78%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 2.78%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 2.78%   |
| Seagate STM9120817AS 120GB            | 1         | 1      | 2.78%   |
| Seagate ST98823AS 80GB                | 1         | 1      | 2.78%   |
| Seagate ST9640423AS 640GB             | 1         | 1      | 2.78%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 2.78%   |
| Seagate ST9120821AS 120GB             | 1         | 1      | 2.78%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 2.78%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 2.78%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 2.78%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 980 PRO 1TB   | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 2.78%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 2.78%   |
| Samsung Electronics MP0402H 40GB      | 1         | 1      | 2.78%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 2.78%   |
| Phison ES 512GB                       | 1         | 1      | 2.78%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 2.78%   |
| Kingston SUV400S37240G 240GB SSD      | 1         | 1      | 2.78%   |
| Intenso SSD 256GB                     | 1         | 1      | 2.78%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 2.78%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 2.78%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 2.78%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.78%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 2.78%   |
| Fujitsu MHZ2080BJ FFS G2 80GB         | 1         | 1      | 2.78%   |
| Crucial M4-CT256M4SSD2 256GB          | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 22.86%  |
| Samsung Electronics | 6         | 7      | 17.14%  |
| WDC                 | 5         | 6      | 14.29%  |
| Kingston            | 2         | 2      | 5.71%   |
| Intel               | 2         | 2      | 5.71%   |
| Hitachi             | 2         | 2      | 5.71%   |
| WINTEC              | 1         | 1      | 2.86%   |
| Transcend           | 1         | 1      | 2.86%   |
| Toshiba             | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 1      | 2.86%   |
| SanDisk             | 1         | 1      | 2.86%   |
| Phison              | 1         | 1      | 2.86%   |
| Intenso             | 1         | 1      | 2.86%   |
| HGST                | 1         | 1      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |
| Crucial             | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 42.11%  |
| WDC                 | 5         | 6      | 26.32%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| HGST                | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 20     | 54.29%  |
| SSD  | 12        | 12     | 34.29%  |
| NVMe | 4         | 5      | 11.43%  |

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
| Detected | 412       | 607    | 67.99%  |
| Works    | 159       | 215    | 26.24%  |
| Malfunc  | 35        | 37     | 5.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 415       | 65.77%  |
| AMD                              | 76        | 12.04%  |
| Samsung Electronics              | 39        | 6.18%   |
| SanDisk                          | 24        | 3.8%    |
| SK hynix                         | 18        | 2.85%   |
| Phison Electronics               | 8         | 1.27%   |
| Nvidia                           | 8         | 1.27%   |
| Micron Technology                | 8         | 1.27%   |
| Silicon Integrated Systems [SiS] | 6         | 0.95%   |
| Kingston Technology Company      | 6         | 0.95%   |
| Toshiba America Info Systems     | 5         | 0.79%   |
| KIOXIA                           | 3         | 0.48%   |
| ADATA Technology                 | 3         | 0.48%   |
| VIA Technologies                 | 2         | 0.32%   |
| Union Memory (Shenzhen)          | 2         | 0.32%   |
| Silicon Motion                   | 2         | 0.32%   |
| Micron/Crucial Technology        | 2         | 0.32%   |
| Marvell Technology Group         | 2         | 0.32%   |
| Solid State Storage Technology   | 1         | 0.16%   |
| Apple                            | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 55        | 7.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 44        | 6.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 41        | 5.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 39        | 5.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 29        | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 29        | 4.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 20        | 2.81%   |
| Intel Volume Management Device NVMe RAID Controller                              | 19        | 2.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 19        | 2.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 16        | 2.24%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 16        | 2.24%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 16        | 2.24%   |
| Intel Tiger Lake-LP SATA Controller                                              | 14        | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 13        | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 13        | 1.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 1.68%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 12        | 1.68%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 12        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 1.26%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 8         | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 1.12%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 7         | 0.98%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 7         | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 0.98%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 6         | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.84%   |
| AMD IXP SB4x0 IDE Controller                                                     | 6         | 0.84%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 5         | 0.7%    |
| Intel SSD 660P Series                                                            | 5         | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 0.7%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 4         | 0.56%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 4         | 0.56%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 4         | 0.56%   |
| Phison E12 NVMe Controller                                                       | 4         | 0.56%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 395       | 57.92%  |
| NVMe | 126       | 18.48%  |
| IDE  | 94        | 13.78%  |
| RAID | 67        | 9.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 470       | 82.02%  |
| AMD          | 102       | 17.8%   |
| CentaurHauls | 1         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.92%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 10        | 1.75%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 10        | 1.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 1.57%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 8         | 1.4%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 1.22%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 7         | 1.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.87%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 0.87%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 5         | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.7%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 4         | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.7%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 0.7%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.7%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 4         | 0.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.7%    |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 0.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 0.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.7%    |
| AMD Ryzen 3 3250U with Radeon Graphics        | 4         | 0.7%    |
| Intel Pentium M processor 1.73GHz             | 3         | 0.52%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 3         | 0.52%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 3         | 0.52%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 3         | 0.52%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 0.52%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.52%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 3         | 0.52%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 3         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 111       | 19.37%  |
| Intel Core i7           | 87        | 15.18%  |
| Intel Core i3           | 55        | 9.6%    |
| Other                   | 42        | 7.33%   |
| Intel Core 2 Duo        | 38        | 6.63%   |
| Intel Atom              | 37        | 6.46%   |
| Intel Celeron           | 32        | 5.58%   |
| AMD Ryzen 5             | 22        | 3.84%   |
| Intel Pentium           | 20        | 3.49%   |
| AMD Ryzen 7             | 12        | 2.09%   |
| Intel Genuine           | 10        | 1.75%   |
| Intel Pentium M         | 8         | 1.4%    |
| Intel Core 2            | 8         | 1.4%    |
| AMD A4                  | 8         | 1.4%    |
| Intel Pentium Dual-Core | 7         | 1.22%   |
| Intel Pentium Dual      | 7         | 1.22%   |
| AMD Ryzen 3             | 6         | 1.05%   |
| AMD E2                  | 6         | 1.05%   |
| AMD E1                  | 5         | 0.87%   |
| AMD Turion 64 X2 Mobile | 4         | 0.7%    |
| AMD Ryzen 9             | 4         | 0.7%    |
| Intel Pentium Silver    | 3         | 0.52%   |
| Intel Core Duo          | 3         | 0.52%   |
| Intel Celeron M         | 3         | 0.52%   |
| AMD E                   | 3         | 0.52%   |
| AMD Athlon II           | 3         | 0.52%   |
| AMD A8                  | 3         | 0.52%   |
| AMD A10                 | 3         | 0.52%   |
| Intel Pentium 4         | 2         | 0.35%   |
| AMD Sempron             | 2         | 0.35%   |
| AMD Mobile Sempron      | 2         | 0.35%   |
| AMD Athlon 64 X2        | 2         | 0.35%   |
| AMD Athlon              | 2         | 0.35%   |
| AMD A6                  | 2         | 0.35%   |
| Intel Pentium Gold      | 1         | 0.17%   |
| Intel Mobile Pentium 4  | 1         | 0.17%   |
| Intel Core m3           | 1         | 0.17%   |
| Intel Core i9           | 1         | 0.17%   |
| Intel Core 2 Extreme    | 1         | 0.17%   |
| CentaurHauls VIA Eden   | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 347       | 60.45%  |
| 4      | 133       | 23.17%  |
| 1      | 47        | 8.19%   |
| 6      | 22        | 3.83%   |
| 8      | 15        | 2.61%   |
| 14     | 4         | 0.7%    |
| 12     | 3         | 0.52%   |
| 10     | 3         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 573       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 369       | 64.4%   |
| 1      | 204       | 35.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 523       | 91.27%  |
| 32-bit         | 50        | 8.73%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 7.92%   |
| 0x306a9    | 42        | 7.23%   |
| 0x206a7    | 41        | 7.06%   |
| 0x1067a    | 27        | 4.65%   |
| 0x406e3    | 26        | 4.48%   |
| 0x806c1    | 22        | 3.79%   |
| 0x40651    | 22        | 3.79%   |
| 0x806ec    | 17        | 2.93%   |
| 0x20655    | 17        | 2.93%   |
| 0x6fd      | 16        | 2.75%   |
| 0x106c2    | 16        | 2.75%   |
| 0x806e9    | 14        | 2.41%   |
| 0x806ea    | 12        | 2.07%   |
| 0x306c3    | 12        | 2.07%   |
| 0x30661    | 12        | 2.07%   |
| 0x406c4    | 11        | 1.89%   |
| 0x08108109 | 11        | 1.89%   |
| 0x06006705 | 11        | 1.89%   |
| 0x08608103 | 10        | 1.72%   |
| 0x6f6      | 9         | 1.55%   |
| 0x306d4    | 8         | 1.38%   |
| 0x30678    | 8         | 1.38%   |
| 0x20652    | 8         | 1.38%   |
| 0x10676    | 8         | 1.38%   |
| 0x706e5    | 7         | 1.2%    |
| 0x6ec      | 7         | 1.2%    |
| 0x906ea    | 6         | 1.03%   |
| 0x806eb    | 6         | 1.03%   |
| 0x6e8      | 6         | 1.03%   |
| 0x6d8      | 6         | 1.03%   |
| 0x706a1    | 5         | 0.86%   |
| 0x506e3    | 5         | 0.86%   |
| 0x406c3    | 5         | 0.86%   |
| 0x106e5    | 5         | 0.86%   |
| 0x0a50000c | 5         | 0.86%   |
| 0x08108102 | 5         | 0.86%   |
| 0x906e9    | 4         | 0.69%   |
| 0x706a8    | 4         | 0.69%   |
| 0x0a50000d | 4         | 0.69%   |
| 0x06001119 | 4         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 69        | 12.02%  |
| SandyBridge      | 42        | 7.32%   |
| IvyBridge        | 42        | 7.32%   |
| Penryn           | 38        | 6.62%   |
| Haswell          | 35        | 6.1%    |
| Skylake          | 33        | 5.75%   |
| Bonnell          | 32        | 5.57%   |
| Core             | 29        | 5.05%   |
| Westmere         | 26        | 4.53%   |
| Silvermont       | 26        | 4.53%   |
| TigerLake        | 23        | 4.01%   |
| P6               | 22        | 3.83%   |
| Zen+             | 16        | 2.79%   |
| Excavator        | 16        | 2.79%   |
| Unknown          | 16        | 2.79%   |
| K8 Hammer        | 11        | 1.92%   |
| Zen 3            | 10        | 1.74%   |
| Broadwell        | 10        | 1.74%   |
| IceLake          | 9         | 1.57%   |
| Goldmont plus    | 9         | 1.57%   |
| Alderlake Hybrid | 8         | 1.39%   |
| Puma             | 7         | 1.22%   |
| Zen 2            | 5         | 0.87%   |
| Nehalem          | 5         | 0.87%   |
| K10              | 5         | 0.87%   |
| Bobcat           | 5         | 0.87%   |
| Zen              | 4         | 0.7%    |
| Piledriver       | 4         | 0.7%    |
| Tremont          | 3         | 0.52%   |
| NetBurst         | 3         | 0.52%   |
| Jaguar           | 3         | 0.52%   |
| CometLake        | 3         | 0.52%   |
| K8 & K10 hybrid  | 2         | 0.35%   |
| K10 Llano        | 2         | 0.35%   |
| Goldmont         | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 400       | 58.82%  |
| AMD                              | 144       | 21.18%  |
| Nvidia                           | 129       | 18.97%  |
| Silicon Integrated Systems [SiS] | 5         | 0.74%   |
| VIA Technologies                 | 2         | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 40        | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 36        | 5%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 26        | 3.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 22        | 3.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 3.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 2.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 2.08%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 1.94%   |
| Intel HD Graphics 620                                                                    | 13        | 1.81%   |
| Intel UHD Graphics 620                                                                   | 12        | 1.67%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 12        | 1.67%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 12        | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.53%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 1.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.39%   |
| AMD Lucienne                                                                             | 10        | 1.39%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 8         | 1.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 1.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 1.11%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.97%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.69%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.69%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 5         | 0.69%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 5         | 0.69%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 5         | 0.69%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.56%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 0.56%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 4         | 0.56%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 4         | 0.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.56%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 4         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 297       | 51.83%  |
| 1 x AMD        | 108       | 18.85%  |
| Intel + Nvidia | 80        | 13.96%  |
| 1 x Nvidia     | 43        | 7.5%    |
| Intel + AMD    | 21        | 3.66%   |
| 2 x AMD        | 9         | 1.57%   |
| AMD + Nvidia   | 6         | 1.05%   |
| 1 x SiS        | 5         | 0.87%   |
| 1 x VIA        | 2         | 0.35%   |
| Other          | 1         | 0.17%   |
| 2 x Intel      | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 510       | 88.39%  |
| Proprietary | 35        | 6.07%   |
| Unknown     | 32        | 5.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 372       | 64.47%  |
| 0.01-0.5   | 98        | 16.98%  |
| 1.01-2.0   | 60        | 10.4%   |
| 0.51-1.0   | 29        | 5.03%   |
| 3.01-4.0   | 11        | 1.91%   |
| 5.01-6.0   | 4         | 0.69%   |
| 2.01-3.0   | 2         | 0.35%   |
| 8.01-16.0  | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 107       | 18.45%  |
| LG Display              | 93        | 16.03%  |
| BOE                     | 77        | 13.28%  |
| Chimei Innolux          | 71        | 12.24%  |
| Samsung Electronics     | 57        | 9.83%   |
| Chi Mei Optoelectronics | 21        | 3.62%   |
| Apple                   | 14        | 2.41%   |
| LG Philips              | 13        | 2.24%   |
| Sharp                   | 11        | 1.9%    |
| Goldstar                | 11        | 1.9%    |
| InfoVision              | 10        | 1.72%   |
| Lenovo                  | 9         | 1.55%   |
| HannStar                | 9         | 1.55%   |
| PANDA                   | 7         | 1.21%   |
| Dell                    | 7         | 1.21%   |
| BenQ                    | 6         | 1.03%   |
| Acer                    | 6         | 1.03%   |
| Sony                    | 4         | 0.69%   |
| Quanta Display          | 4         | 0.69%   |
| Philips                 | 4         | 0.69%   |
| CPT                     | 4         | 0.69%   |
| ViewSonic               | 3         | 0.52%   |
| SLD                     | 3         | 0.52%   |
| Panasonic               | 3         | 0.52%   |
| Hewlett-Packard         | 3         | 0.52%   |
| AOC                     | 3         | 0.52%   |
| Unknown                 | 2         | 0.34%   |
| Vestel Elektronik       | 1         | 0.17%   |
| TR_                     | 1         | 0.17%   |
| TFG                     | 1         | 0.17%   |
| STA                     | 1         | 0.17%   |
| Seiko/Epson             | 1         | 0.17%   |
| Sceptre Tech            | 1         | 0.17%   |
| Planar                  | 1         | 0.17%   |
| Packard Bell            | 1         | 0.17%   |
| MLT                     | 1         | 0.17%   |
| Insignia                | 1         | 0.17%   |
| InnoLux Display         | 1         | 0.17%   |
| Iiyama                  | 1         | 0.17%   |
| IBM                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 7         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 5         | 0.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.68%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 4         | 0.68%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.68%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.68%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 4         | 0.68%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 3         | 0.51%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 3         | 0.51%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.51%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.51%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch         | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 3         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 3         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 3         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 3         | 0.51%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.51%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.51%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 3         | 0.51%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.34%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 205       | 36.41%  |
| 1920x1080 (FHD)    | 190       | 33.75%  |
| 1280x800 (WXGA)    | 41        | 7.28%   |
| 1600x900 (HD+)     | 31        | 5.51%   |
| 1024x600           | 18        | 3.2%    |
| 3840x2160 (4K)     | 15        | 2.66%   |
| 1920x1200 (WUXGA)  | 13        | 2.31%   |
| 1440x900 (WXGA+)   | 9         | 1.6%    |
| 1280x1024 (SXGA)   | 5         | 0.89%   |
| 2560x1440 (QHD)    | 4         | 0.71%   |
| 1680x1050 (WSXGA+) | 4         | 0.71%   |
| 1024x768 (XGA)     | 4         | 0.71%   |
| 2560x1600          | 3         | 0.53%   |
| 3440x1440          | 2         | 0.36%   |
| 2880x1800          | 2         | 0.36%   |
| 2560x1080          | 2         | 0.36%   |
| 1360x768           | 2         | 0.36%   |
| 1280x768           | 2         | 0.36%   |
| 3840x2400          | 1         | 0.18%   |
| 3840x1080          | 1         | 0.18%   |
| 3200x1800 (QHD+)   | 1         | 0.18%   |
| 2256x1504          | 1         | 0.18%   |
| 2160x1440          | 1         | 0.18%   |
| 1920x540           | 1         | 0.18%   |
| 1680x945           | 1         | 0.18%   |
| 1400x1050          | 1         | 0.18%   |
| 1280x720 (HD)      | 1         | 0.18%   |
| 1024x576           | 1         | 0.18%   |
| Unknown            | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 269       | 46.3%   |
| 13      | 78        | 13.43%  |
| 14      | 63        | 10.84%  |
| 17      | 40        | 6.88%   |
| 10      | 18        | 3.1%    |
| 12      | 16        | 2.75%   |
| 24      | 14        | 2.41%   |
| 11      | 14        | 2.41%   |
| 27      | 9         | 1.55%   |
| Unknown | 9         | 1.55%   |
| 21      | 8         | 1.38%   |
| 23      | 7         | 1.2%    |
| 18      | 7         | 1.2%    |
| 34      | 5         | 0.86%   |
| 19      | 4         | 0.69%   |
| 16      | 4         | 0.69%   |
| 72      | 3         | 0.52%   |
| 31      | 3         | 0.52%   |
| 8       | 3         | 0.52%   |
| 84      | 1         | 0.17%   |
| 54      | 1         | 0.17%   |
| 48      | 1         | 0.17%   |
| 40      | 1         | 0.17%   |
| 28      | 1         | 0.17%   |
| 22      | 1         | 0.17%   |
| 20      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 371       | 64.52%  |
| 201-300     | 82        | 14.26%  |
| 351-400     | 49        | 8.52%   |
| 501-600     | 27        | 4.7%    |
| 401-500     | 17        | 2.96%   |
| Unknown     | 9         | 1.57%   |
| 701-800     | 5         | 0.87%   |
| 601-700     | 5         | 0.87%   |
| 1501-2000   | 4         | 0.7%    |
| 101-200     | 3         | 0.52%   |
| 1001-1500   | 2         | 0.35%   |
| 801-900     | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 443       | 81.89%  |
| 16/10   | 74        | 13.68%  |
| 5/4     | 6         | 1.11%   |
| 4/3     | 5         | 0.92%   |
| Unknown | 5         | 0.92%   |
| 21/9    | 4         | 0.74%   |
| 3/2     | 3         | 0.55%   |
| 32/9    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 268       | 46.21%  |
| 81-90          | 115       | 19.83%  |
| 121-130        | 29        | 5%      |
| 71-80          | 25        | 4.31%   |
| 201-250        | 21        | 3.62%   |
| 41-50          | 18        | 3.1%    |
| 61-70          | 16        | 2.76%   |
| 51-60          | 14        | 2.41%   |
| 301-350        | 9         | 1.55%   |
| 141-150        | 9         | 1.55%   |
| 131-140        | 9         | 1.55%   |
| Unknown        | 9         | 1.55%   |
| 351-500        | 8         | 1.38%   |
| 151-200        | 8         | 1.38%   |
| More than 1000 | 6         | 1.03%   |
| 251-300        | 4         | 0.69%   |
| 91-100         | 4         | 0.69%   |
| 1-40           | 3         | 0.52%   |
| 111-120        | 3         | 0.52%   |
| 501-1000       | 2         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 234       | 40.84%  |
| 121-160       | 195       | 34.03%  |
| 51-100        | 94        | 16.4%   |
| 161-240       | 26        | 4.54%   |
| More than 240 | 9         | 1.57%   |
| Unknown       | 9         | 1.57%   |
| 1-50          | 6         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 497       | 85.4%   |
| 2     | 55        | 9.45%   |
| 0     | 27        | 4.64%   |
| 3     | 2         | 0.34%   |
| 4     | 1         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 305       | 32.87%  |
| Intel                                 | 248       | 26.72%  |
| Qualcomm Atheros                      | 156       | 16.81%  |
| Broadcom                              | 77        | 8.3%    |
| Broadcom Limited                      | 20        | 2.16%   |
| Marvell Technology Group              | 17        | 1.83%   |
| Ralink                                | 10        | 1.08%   |
| MediaTek                              | 10        | 1.08%   |
| Samsung Electronics                   | 8         | 0.86%   |
| Nvidia                                | 7         | 0.75%   |
| TP-Link                               | 6         | 0.65%   |
| Silicon Integrated Systems [SiS]      | 5         | 0.54%   |
| Ralink Technology                     | 4         | 0.43%   |
| Lenovo                                | 4         | 0.43%   |
| Ericsson Business Mobile Networks     | 4         | 0.43%   |
| Dell                                  | 4         | 0.43%   |
| Xiaomi                                | 3         | 0.32%   |
| JMicron Technology                    | 3         | 0.32%   |
| Google                                | 3         | 0.32%   |
| AMD                                   | 3         | 0.32%   |
| Spreadtrum Communications             | 2         | 0.22%   |
| Sierra Wireless                       | 2         | 0.22%   |
| Huawei Technologies                   | 2         | 0.22%   |
| Hewlett-Packard                       | 2         | 0.22%   |
| Edimax Technology                     | 2         | 0.22%   |
| DisplayLink                           | 2         | 0.22%   |
| Cisco Aironet Wireless Communications | 2         | 0.22%   |
| Attansic Technology                   | 2         | 0.22%   |
| ASIX Electronics                      | 2         | 0.22%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.11%   |
| VIA Technologies                      | 1         | 0.11%   |
| ST-Ericsson                           | 1         | 0.11%   |
| Qualcomm Atheros Communications       | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.11%   |
| NetGear                               | 1         | 0.11%   |
| Manta                                 | 1         | 0.11%   |
| Linksys                               | 1         | 0.11%   |
| Intersil                              | 1         | 0.11%   |
| Gemtek                                | 1         | 0.11%   |
| Davicom Semiconductor                 | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 163       | 14.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 76        | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 35        | 3.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 2.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 23        | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 22        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 21        | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 1.58%   |
| Intel Wireless 8265 / 8275                                              | 17        | 1.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 16        | 1.4%    |
| Intel Wireless 7260                                                     | 15        | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 1.32%   |
| Intel Wireless 8260                                                     | 14        | 1.23%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 12        | 1.05%   |
| Intel WiFi Link 5100                                                    | 12        | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 0.97%   |
| Intel Wireless 3165                                                     | 11        | 0.97%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 0.79%   |
| Intel Wireless 7265                                                     | 9         | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 8         | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 0.7%    |
| Intel Centrino Ultimate-N 6300                                          | 8         | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 7         | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 7         | 0.61%   |
| Intel Ethernet Connection I219-V                                        | 7         | 0.61%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                | 7         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 6         | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 6         | 0.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.53%   |
| Intel Wireless 3160                                                     | 6         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 227       | 38.34%  |
| Qualcomm Atheros                      | 129       | 21.79%  |
| Realtek Semiconductor                 | 120       | 20.27%  |
| Broadcom                              | 60        | 10.14%  |
| Broadcom Limited                      | 12        | 2.03%   |
| Ralink                                | 10        | 1.69%   |
| MediaTek                              | 8         | 1.35%   |
| TP-Link                               | 6         | 1.01%   |
| Ralink Technology                     | 4         | 0.68%   |
| Dell                                  | 3         | 0.51%   |
| Sierra Wireless                       | 2         | 0.34%   |
| Edimax Technology                     | 2         | 0.34%   |
| Cisco Aironet Wireless Communications | 2         | 0.34%   |
| Xiaomi                                | 1         | 0.17%   |
| Qualcomm Atheros Communications       | 1         | 0.17%   |
| NetGear                               | 1         | 0.17%   |
| Linksys                               | 1         | 0.17%   |
| Ericsson Business Mobile Networks     | 1         | 0.17%   |
| ASUSTek Computer                      | 1         | 0.17%   |
| Askey Computer                        | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 35        | 5.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 4.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 22        | 3.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 21        | 3.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 3.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 2.99%   |
| Intel Wireless 8265 / 8275                                              | 17        | 2.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 16        | 2.65%   |
| Intel Wireless 7260                                                     | 15        | 2.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 2.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 2.49%   |
| Intel Wireless 8260                                                     | 14        | 2.32%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 2.16%   |
| Intel WiFi Link 5100                                                    | 12        | 1.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.82%   |
| Intel Wireless 3165                                                     | 11        | 1.82%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.49%   |
| Intel Wireless 7265                                                     | 9         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                          | 8         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 1.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 6         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1%      |
| Intel Wireless 3160                                                     | 6         | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.83%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.66%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.66%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 263       | 51.27%  |
| Intel                            | 102       | 19.88%  |
| Qualcomm Atheros                 | 49        | 9.55%   |
| Broadcom                         | 27        | 5.26%   |
| Marvell Technology Group         | 17        | 3.31%   |
| Broadcom Limited                 | 8         | 1.56%   |
| Nvidia                           | 7         | 1.36%   |
| Samsung Electronics              | 6         | 1.17%   |
| Silicon Integrated Systems [SiS] | 5         | 0.97%   |
| Lenovo                           | 3         | 0.58%   |
| JMicron Technology               | 3         | 0.58%   |
| Google                           | 3         | 0.58%   |
| Xiaomi                           | 2         | 0.39%   |
| Spreadtrum Communications        | 2         | 0.39%   |
| MediaTek                         | 2         | 0.39%   |
| Hewlett-Packard                  | 2         | 0.39%   |
| DisplayLink                      | 2         | 0.39%   |
| Attansic Technology              | 2         | 0.39%   |
| ASIX Electronics                 | 2         | 0.39%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.19%   |
| VIA Technologies                 | 1         | 0.19%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.19%   |
| Huawei Technologies              | 1         | 0.19%   |
| Gemtek                           | 1         | 0.19%   |
| Davicom Semiconductor            | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 163       | 31.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 76        | 14.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 4.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 1.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 7         | 1.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 1.36%   |
| Intel Ethernet Connection I219-V                                  | 7         | 1.36%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.36%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 1.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 1.17%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 1.17%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 6         | 1.17%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 5         | 0.97%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 5         | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.78%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.78%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.78%   |
| Intel 82573L Gigabit Ethernet Controller                          | 4         | 0.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3         | 0.58%   |
| Lenovo ThinkPad Lan                                               | 3         | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.58%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.58%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 3         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.39%   |
| Spreadtrum Unisoc Phone                                           | 2         | 0.39%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 2         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 561       | 52.28%  |
| Ethernet | 489       | 45.57%  |
| Modem    | 20        | 1.86%   |
| Unknown  | 3         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 438       | 73.61%  |
| Ethernet | 157       | 26.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 450       | 78.53%  |
| 1     | 105       | 18.32%  |
| 0     | 12        | 2.09%   |
| 3     | 5         | 0.87%   |
| 4     | 1         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 432       | 74.23%  |
| Yes  | 150       | 25.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 143       | 37.53%  |
| Realtek Semiconductor           | 62        | 16.27%  |
| Qualcomm Atheros Communications | 33        | 8.66%   |
| Broadcom                        | 29        | 7.61%   |
| Foxconn / Hon Hai               | 21        | 5.51%   |
| Lite-On Technology              | 16        | 4.2%    |
| IMC Networks                    | 16        | 4.2%    |
| Hewlett-Packard                 | 13        | 3.41%   |
| Apple                           | 11        | 2.89%   |
| Dell                            | 10        | 2.62%   |
| Cambridge Silicon Radio         | 6         | 1.57%   |
| Realtek                         | 3         | 0.79%   |
| Ralink                          | 3         | 0.79%   |
| Foxconn International           | 3         | 0.79%   |
| ASUSTek Computer                | 3         | 0.79%   |
| Toshiba                         | 2         | 0.52%   |
| Askey Computer                  | 2         | 0.52%   |
| Taiyo Yuden                     | 1         | 0.26%   |
| Ralink Technology               | 1         | 0.26%   |
| Qcom                            | 1         | 0.26%   |
| Chicony Electronics             | 1         | 0.26%   |
| Alps Electric                   | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 66        | 17.32%  |
| Realtek Bluetooth Radio                                                             | 38        | 9.97%   |
| Intel Bluetooth Device                                                              | 24        | 6.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 24        | 6.3%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 19        | 4.99%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 3.67%   |
| Intel AX200 Bluetooth                                                               | 12        | 3.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 9         | 2.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 7         | 1.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 7         | 1.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 1.57%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.57%   |
| Apple Bluetooth Host Controller                                                     | 6         | 1.57%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 1.31%   |
| Intel AX210 Bluetooth                                                               | 5         | 1.31%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.31%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.31%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 1.31%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 1.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 4         | 1.05%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.05%   |
| IMC Networks Wireless_Device                                                        | 4         | 1.05%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.05%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.05%   |
| Foxconn / Hon Hai Acer Module                                                       | 4         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 1.05%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.05%   |
| Realtek Bluetooth Radio                                                             | 3         | 0.79%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.79%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.79%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 0.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.79%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 0.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.79%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 0.79%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.52%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.52%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 450       | 67.16%  |
| AMD                              | 124       | 18.51%  |
| Nvidia                           | 70        | 10.45%  |
| Silicon Integrated Systems [SiS] | 6         | 0.9%    |
| C-Media Electronics              | 4         | 0.6%    |
| Texas Instruments                | 3         | 0.45%   |
| VIA Technologies                 | 2         | 0.3%    |
| Yamaha                           | 1         | 0.15%   |
| Tenx Technology                  | 1         | 0.15%   |
| Sennheiser Communications        | 1         | 0.15%   |
| Realtek Semiconductor            | 1         | 0.15%   |
| GN Netcom                        | 1         | 0.15%   |
| Generalplus Technology           | 1         | 0.15%   |
| Focusrite-Novation               | 1         | 0.15%   |
| Dell                             | 1         | 0.15%   |
| Creative Technology              | 1         | 0.15%   |
| CMX Systems                      | 1         | 0.15%   |
| Audioengine                      | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 56        | 7.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 51        | 6.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 46        | 5.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 43        | 5.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 36        | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 4.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 31        | 3.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 2.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 2.75%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 2.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 20        | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 2.5%    |
| AMD FCH Azalia Controller                                                                         | 17        | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 16        | 2%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 16        | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15        | 1.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.75%   |
| AMD High Definition Audio Controller                                                              | 14        | 1.75%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 1.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 1.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.25%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.75%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 6         | 0.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 6         | 0.75%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 6         | 0.75%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.63%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.63%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.63%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 61        | 26.29%  |
| SK hynix                     | 51        | 21.98%  |
| Unknown                      | 29        | 12.5%   |
| Micron Technology            | 25        | 10.78%  |
| Kingston                     | 18        | 7.76%   |
| G.Skill                      | 6         | 2.59%   |
| Ramaxel Technology           | 5         | 2.16%   |
| Nanya Technology             | 5         | 2.16%   |
| Corsair                      | 4         | 1.72%   |
| A-DATA Technology            | 4         | 1.72%   |
| Smart                        | 3         | 1.29%   |
| Elpida                       | 3         | 1.29%   |
| Crucial                      | 3         | 1.29%   |
| Unknown (ABCD)               | 2         | 0.86%   |
| GSkill                       | 2         | 0.86%   |
| Unknown                      | 2         | 0.86%   |
| Transcend                    | 1         | 0.43%   |
| Team                         | 1         | 0.43%   |
| Strontium                    | 1         | 0.43%   |
| PUSKILL                      | 1         | 0.43%   |
| Patriot Memory (PDP Systems) | 1         | 0.43%   |
| Patriot                      | 1         | 0.43%   |
| Lexar Co Limited             | 1         | 0.43%   |
| AMD                          | 1         | 0.43%   |
| 4ea5                         | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 2.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 1.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.18%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.18%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.18%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 3         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.18%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.78%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 2         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.78%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.78%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.78%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.78%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 2         | 0.78%   |
| SK hynix RAM HMT451S6AFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.78%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 2         | 0.78%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Micron RAM MT40A512M16TB-062E:R 4GB Row Of Chips DDR4 3200MT/s   | 2         | 0.78%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 0.78%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 2         | 0.78%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| G.Skill RAM F4-3200C22-32GRS 32GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 91        | 45.27%  |
| DDR3   | 70        | 34.83%  |
| DDR2   | 17        | 8.46%   |
| SDRAM  | 6         | 2.99%   |
| LPDDR4 | 6         | 2.99%   |
| DDR    | 4         | 1.99%   |
| LPDDR3 | 3         | 1.49%   |
| DRAM   | 2         | 1%      |
| LPDDR5 | 1         | 0.5%    |
| DDR5   | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 188       | 93.07%  |
| Row Of Chips | 10        | 4.95%   |
| Chip         | 2         | 0.99%   |
| Unknown      | 2         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 80        | 35.71%  |
| 4096    | 61        | 27.23%  |
| 2048    | 39        | 17.41%  |
| 16384   | 20        | 8.93%   |
| 1024    | 10        | 4.46%   |
| 512     | 7         | 3.13%   |
| 32768   | 6         | 2.68%   |
| Unknown | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 41        | 18.89%  |
| 3200    | 40        | 18.43%  |
| 2667    | 39        | 17.97%  |
| 2400    | 16        | 7.37%   |
| Unknown | 14        | 6.45%   |
| 2133    | 9         | 4.15%   |
| 1333    | 9         | 4.15%   |
| 1334    | 8         | 3.69%   |
| 1067    | 6         | 2.76%   |
| 3266    | 5         | 2.3%    |
| 667     | 5         | 2.3%    |
| 533     | 5         | 2.3%    |
| 800     | 3         | 1.38%   |
| 4267    | 2         | 0.92%   |
| 4199    | 2         | 0.92%   |
| 2048    | 2         | 0.92%   |
| 1867    | 2         | 0.92%   |
| 1066    | 2         | 0.92%   |
| 975     | 2         | 0.92%   |
| 5500    | 1         | 0.46%   |
| 4800    | 1         | 0.46%   |
| 4266    | 1         | 0.46%   |
| 2267    | 1         | 0.46%   |
| 1200    | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 60%     |
| Seiko Epson     | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-3100 Series | 1         | 20%     |
| HP OfficeJet 6200          | 1         | 20%     |
| HP DeskJet 4100 series     | 1         | 20%     |
| HP DeskJet 2700 series     | 1         | 20%     |
| Canon TR4600 series        | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 109       | 23.39%  |
| IMC Networks                           | 46        | 9.87%   |
| Microdia                               | 39        | 8.37%   |
| Suyin                                  | 32        | 6.87%   |
| Sunplus Innovation Technology          | 32        | 6.87%   |
| Bison Electronics                      | 32        | 6.87%   |
| Quanta                                 | 31        | 6.65%   |
| Realtek Semiconductor                  | 28        | 6.01%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 3.86%   |
| Apple                                  | 11        | 2.36%   |
| Silicon Motion                         | 10        | 2.15%   |
| Syntek                                 | 9         | 1.93%   |
| Luxvisions Innotech Limited            | 9         | 1.93%   |
| Alcor Micro                            | 9         | 1.93%   |
| Ricoh                                  | 8         | 1.72%   |
| Acer                                   | 8         | 1.72%   |
| Lite-On Technology                     | 5         | 1.07%   |
| Importek                               | 5         | 1.07%   |
| Z-Star Microelectronics                | 3         | 0.64%   |
| Sunplus Technology                     | 3         | 0.64%   |
| Lenovo                                 | 3         | 0.64%   |
| ALi                                    | 3         | 0.64%   |
| Sonix Technology                       | 2         | 0.43%   |
| OmniVision Technologies                | 2         | 0.43%   |
| ShineTech                              | 1         | 0.21%   |
| Samsung Electronics                    | 1         | 0.21%   |
| Logitech                               | 1         | 0.21%   |
| LG Electronics                         | 1         | 0.21%   |
| Intel                                  | 1         | 0.21%   |
| icSpring                               | 1         | 0.21%   |
| Generalplus Technology                 | 1         | 0.21%   |
| eMPIA Technology                       | 1         | 0.21%   |
| Alpha Imaging Technology               | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                      | 27        | 5.74%   |
| Microdia Integrated_Webcam_HD                                  | 18        | 3.83%   |
| Chicony HD WebCam                                              | 10        | 2.13%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 9         | 1.91%   |
| Realtek Integrated_Webcam_HD                                   | 8         | 1.7%    |
| Quanta HP Webcam                                               | 8         | 1.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                             | 8         | 1.7%    |
| IMC Networks Integrated Camera                                 | 8         | 1.7%    |
| Bison Integrated Camera                                        | 8         | 1.7%    |
| Quanta HP TrueVision HD Camera                                 | 7         | 1.49%   |
| Chicony HP TrueVision HD Camera                                | 7         | 1.49%   |
| Suyin HP TrueVision HD                                         | 6         | 1.28%   |
| Alcor Micro USB 2.0 Camera                                     | 6         | 1.28%   |
| Realtek USB camera                                             | 5         | 1.06%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 5         | 1.06%   |
| Chicony HP HD Camera                                           | 5         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 5         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 5         | 1.06%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 4         | 0.85%   |
| Sunplus HP TrueVision HD Camera                                | 4         | 0.85%   |
| Sunplus HD WebCam                                              | 4         | 0.85%   |
| Realtek Lenovo EasyCamera                                      | 4         | 0.85%   |
| Quanta VGA WebCam                                              | 4         | 0.85%   |
| IMC Networks EasyCamera                                        | 4         | 0.85%   |
| Chicony USB2.0 HD UVC WebCam                                   | 4         | 0.85%   |
| Bison Lenovo EasyCamera                                        | 4         | 0.85%   |
| Bison HD Webcam                                                | 4         | 0.85%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 4         | 0.85%   |
| Syntek Integrated Camera                                       | 3         | 0.64%   |
| Suyin HD WebCam                                                | 3         | 0.64%   |
| Suyin HD Video WebCam                                          | 3         | 0.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 3         | 0.64%   |
| Suyin Acer CrystalEye Webcam                                   | 3         | 0.64%   |
| Suyin 1.3M HD WebCam                                           | 3         | 0.64%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 3         | 0.64%   |
| Silicon Motion WebCam SC-0311139N                              | 3         | 0.64%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 3         | 0.64%   |
| Quanta HP HD Camera                                            | 3         | 0.64%   |
| Microdia USB Camera                                            | 3         | 0.64%   |
| Microdia Sonix USB 2.0 Camera                                  | 3         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 33        | 40.74%  |
| AuthenTec                  | 12        | 14.81%  |
| Synaptics                  | 11        | 13.58%  |
| Upek                       | 5         | 6.17%   |
| STMicroelectronics         | 5         | 6.17%   |
| Shenzhen Goodix Technology | 5         | 6.17%   |
| Elan Microelectronics      | 4         | 4.94%   |
| LighTuning Technology      | 3         | 3.7%    |
| Focal-systems.Corp         | 2         | 2.47%   |
| Microsoft                  | 1         | 1.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 6         | 7.41%   |
| Validity Sensors VFS301 Fingerprint Reader               | 5         | 6.17%   |
| Validity Sensors Fingerprint scanner                     | 5         | 6.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 5         | 6.17%   |
| STMicroelectronics Fingerprint Reader                    | 5         | 6.17%   |
| Shenzhen Goodix  Fingerprint Device                      | 4         | 4.94%   |
| AuthenTec AES1600                                        | 4         | 4.94%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 3         | 3.7%    |
| Validity Sensors VFS451 Fingerprint Reader               | 3         | 3.7%    |
| Elan ELAN:Fingerprint                                    | 3         | 3.7%    |
| AuthenTec Fingerprint Sensor                             | 3         | 3.7%    |
| AuthenTec AES2501 Fingerprint Sensor                     | 3         | 3.7%    |
| Validity Sensors VFS491                                  | 2         | 2.47%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 2.47%   |
| Validity Sensors Synaptics WBDI                          | 2         | 2.47%   |
| Synaptics UWP WBDI Device                                | 2         | 2.47%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 2.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 2         | 2.47%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 2.47%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 2         | 2.47%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 2         | 2.47%   |
| AuthenTec AES2810                                        | 2         | 2.47%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor        | 1         | 1.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 1.23%   |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 1.23%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 1.23%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 1.23%   |
| Synaptics WBDI                                           | 1         | 1.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 1.23%   |
| Synaptics Fingerprint reader [HP G6]                     | 1         | 1.23%   |
| Shenzhen Goodix FingerPrint                              | 1         | 1.23%   |
| Microsoft Fingerprint Reader                             | 1         | 1.23%   |
| LighTuning Fingerprint Reader                            | 1         | 1.23%   |
| Elan ELAN:ARM-M4                                         | 1         | 1.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 20        | 54.05%  |
| Alcor Micro           | 6         | 16.22%  |
| O2 Micro              | 5         | 13.51%  |
| Lenovo                | 3         | 8.11%   |
| Upek                  | 2         | 5.41%   |
| Gemalto (was Gemplus) | 1         | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 21.62%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 16.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 13.51%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 10.81%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 8.11%   |
| Broadcom 5880                                                                | 3         | 8.11%   |
| Broadcom 58200                                                               | 3         | 8.11%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.7%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 355       | 60.68%  |
| 1     | 175       | 29.91%  |
| 2     | 40        | 6.84%   |
| 3     | 12        | 2.05%   |
| 4     | 2         | 0.34%   |
| 6     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 80        | 26.85%  |
| Graphics card            | 72        | 24.16%  |
| Net/wireless             | 52        | 17.45%  |
| Chipcard                 | 35        | 11.74%  |
| Multimedia controller    | 25        | 8.39%   |
| Storage                  | 9         | 3.02%   |
| Communication controller | 6         | 2.01%   |
| Bluetooth                | 6         | 2.01%   |
| Flash memory             | 3         | 1.01%   |
| Camera                   | 3         | 1.01%   |
| Card reader              | 2         | 0.67%   |
| Storage/nvme             | 1         | 0.34%   |
| Sound                    | 1         | 0.34%   |
| Network                  | 1         | 0.34%   |
| Modem                    | 1         | 0.34%   |
| Dvb card                 | 1         | 0.34%   |

