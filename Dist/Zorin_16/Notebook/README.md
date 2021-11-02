Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite Pro T110          | [3ae7a19459](https://linux-hardware.org/?probe=3ae7a19459) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [e3fc4e0622](https://linux-hardware.org/?probe=e3fc4e0622) | Oct 31, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83d642714b](https://linux-hardware.org/?probe=83d642714b) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [eabb3946ad](https://linux-hardware.org/?probe=eabb3946ad) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [3861fce83e](https://linux-hardware.org/?probe=3861fce83e) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [2388e68622](https://linux-hardware.org/?probe=2388e68622) | Oct 31, 2021 |
| Dell          | Inspiron 7720               | [9f298535a5](https://linux-hardware.org/?probe=9f298535a5) | Oct 31, 2021 |
| HP            | 255 G8 Notebook PC          | [cb9c15cf6f](https://linux-hardware.org/?probe=cb9c15cf6f) | Oct 30, 2021 |
| Dell          | Latitude E6500              | [e475348b1e](https://linux-hardware.org/?probe=e475348b1e) | Oct 30, 2021 |
| MECER         | Z140C+Home                  | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| HP            | Pavilion Notebook           | [85a55f5c3c](https://linux-hardware.org/?probe=85a55f5c3c) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | [16ebdc4388](https://linux-hardware.org/?probe=16ebdc4388) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | [6260be6de5](https://linux-hardware.org/?probe=6260be6de5) | Oct 30, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [af0a995721](https://linux-hardware.org/?probe=af0a995721) | Oct 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [88286c36e9](https://linux-hardware.org/?probe=88286c36e9) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [f5f4e2457b](https://linux-hardware.org/?probe=f5f4e2457b) | Oct 29, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c74557d180](https://linux-hardware.org/?probe=c74557d180) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [35b5fcb787](https://linux-hardware.org/?probe=35b5fcb787) | Oct 28, 2021 |
| ASUSTek       | N71Jv                       | [29e3747e17](https://linux-hardware.org/?probe=29e3747e17) | Oct 28, 2021 |
| ASUSTek       | X750JB                      | [90fd9f38fc](https://linux-hardware.org/?probe=90fd9f38fc) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| Toshiba       | PORTEGE Z20t-C              | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Lenovo        | Legion Y920-17IKB Laptop... | [830d4c9d9d](https://linux-hardware.org/?probe=830d4c9d9d) | Oct 26, 2021 |
| Acer          | Aspire 5737Z                | [9bbf3befab](https://linux-hardware.org/?probe=9bbf3befab) | Oct 26, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [4104e265ea](https://linux-hardware.org/?probe=4104e265ea) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [ed4e9d1a03](https://linux-hardware.org/?probe=ed4e9d1a03) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [f5b1e904b7](https://linux-hardware.org/?probe=f5b1e904b7) | Oct 26, 2021 |
| HP            | ProBook 445 G7              | [87b3274937](https://linux-hardware.org/?probe=87b3274937) | Oct 26, 2021 |
| HP            | Stream Notebook PC 11       | [c240a088a9](https://linux-hardware.org/?probe=c240a088a9) | Oct 26, 2021 |
| HP            | ENVY m7 Notebook            | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| Dell          | Latitude E6430              | [fa4d12994d](https://linux-hardware.org/?probe=fa4d12994d) | Oct 25, 2021 |
| Schenker      | VIA 15 Pro                  | [7242436545](https://linux-hardware.org/?probe=7242436545) | Oct 24, 2021 |
| Toshiba       | Satellite C70-B             | [a17b7c3888](https://linux-hardware.org/?probe=a17b7c3888) | Oct 24, 2021 |
| Thomson       | N17C512                     | [20abb09d3a](https://linux-hardware.org/?probe=20abb09d3a) | Oct 24, 2021 |
| Notebook      | X170SM                      | [2054d0dee6](https://linux-hardware.org/?probe=2054d0dee6) | Oct 24, 2021 |
| Notebook      | X170SM                      | [f704af17a3](https://linux-hardware.org/?probe=f704af17a3) | Oct 24, 2021 |
| Dell          | Latitude D630               | [1cfebe8169](https://linux-hardware.org/?probe=1cfebe8169) | Oct 23, 2021 |
| Dell          | Latitude E6410              | [f4cdc942dc](https://linux-hardware.org/?probe=f4cdc942dc) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [db85bd77fc](https://linux-hardware.org/?probe=db85bd77fc) | Oct 23, 2021 |
| HP            | ProBook 6550b               | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | [c6582bba7d](https://linux-hardware.org/?probe=c6582bba7d) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| HP            | Notebook                    | [11013f1334](https://linux-hardware.org/?probe=11013f1334) | Oct 22, 2021 |
| Google        | Kindred                     | [675265477a](https://linux-hardware.org/?probe=675265477a) | Oct 22, 2021 |
| HP            | 255 G4 Notebook PC          | [e7e49e8cc0](https://linux-hardware.org/?probe=e7e49e8cc0) | Oct 22, 2021 |
| Dell          | Latitude E7470              | [061c5e449c](https://linux-hardware.org/?probe=061c5e449c) | Oct 22, 2021 |
| MSI           | Modern 14 B10MW             | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [8668abcc62](https://linux-hardware.org/?probe=8668abcc62) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [18cf55aa72](https://linux-hardware.org/?probe=18cf55aa72) | Oct 21, 2021 |
| Toshiba       | Satellite L755              | [985ff9ba03](https://linux-hardware.org/?probe=985ff9ba03) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [6d2d97674c](https://linux-hardware.org/?probe=6d2d97674c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [facdd98487](https://linux-hardware.org/?probe=facdd98487) | Oct 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [961f066acf](https://linux-hardware.org/?probe=961f066acf) | Oct 19, 2021 |
| Dell          | Latitude E7470              | [fdc6203a6e](https://linux-hardware.org/?probe=fdc6203a6e) | Oct 18, 2021 |
| Dell          | Latitude E6420              | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6210b749a1](https://linux-hardware.org/?probe=6210b749a1) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dbf1e020b0](https://linux-hardware.org/?probe=dbf1e020b0) | Oct 18, 2021 |
| Dell          | Inspiron 3521               | [2ffe8489e1](https://linux-hardware.org/?probe=2ffe8489e1) | Oct 18, 2021 |
| Toshiba       | Satellite C870-1C2          | [076883700d](https://linux-hardware.org/?probe=076883700d) | Oct 17, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [10f8e5f5cf](https://linux-hardware.org/?probe=10f8e5f5cf) | Oct 17, 2021 |
| Acer          | Aspire R3-131T              | [014464c088](https://linux-hardware.org/?probe=014464c088) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [15ce74dcd6](https://linux-hardware.org/?probe=15ce74dcd6) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [97c3495c65](https://linux-hardware.org/?probe=97c3495c65) | Oct 17, 2021 |
| Unknown       | CherryTrail                 | [01d095b201](https://linux-hardware.org/?probe=01d095b201) | Oct 17, 2021 |
| Acer          | Aspire E5-571               | [76090a2652](https://linux-hardware.org/?probe=76090a2652) | Oct 16, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [ff6de8e062](https://linux-hardware.org/?probe=ff6de8e062) | Oct 16, 2021 |
| Lenovo        | G50-70 20351                | [d0d0d99be6](https://linux-hardware.org/?probe=d0d0d99be6) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | [ef609865b5](https://linux-hardware.org/?probe=ef609865b5) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | [4fc5c2f99f](https://linux-hardware.org/?probe=4fc5c2f99f) | Oct 16, 2021 |
| Dell          | Latitude E7440              | [cfe53904bc](https://linux-hardware.org/?probe=cfe53904bc) | Oct 16, 2021 |
| Unknown       | Unknown                     | [3233e1293c](https://linux-hardware.org/?probe=3233e1293c) | Oct 15, 2021 |
| Acer          | Aspire E5-576G              | [6f17f5d2c0](https://linux-hardware.org/?probe=6f17f5d2c0) | Oct 15, 2021 |
| HP            | Pavilion dv7                | [2d35a2ee5d](https://linux-hardware.org/?probe=2d35a2ee5d) | Oct 15, 2021 |
| HP            | ENVY m7 Notebook            | [f0af05f6f9](https://linux-hardware.org/?probe=f0af05f6f9) | Oct 15, 2021 |
| Unknown       | Unknown                     | [ddc6d80716](https://linux-hardware.org/?probe=ddc6d80716) | Oct 15, 2021 |
| Toshiba       | Satellite L755              | [fdaa2dd77e](https://linux-hardware.org/?probe=fdaa2dd77e) | Oct 14, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [3f90ae6d67](https://linux-hardware.org/?probe=3f90ae6d67) | Oct 14, 2021 |
| Dell          | Latitude E6420              | [14b08ab14d](https://linux-hardware.org/?probe=14b08ab14d) | Oct 14, 2021 |
| ASUSTek       | GL702VI                     | [c342d6fdc1](https://linux-hardware.org/?probe=c342d6fdc1) | Oct 14, 2021 |
| HP            | 15                          | [5534f9e3fc](https://linux-hardware.org/?probe=5534f9e3fc) | Oct 14, 2021 |
| Acer          | Swift SF314-59              | [2cd9b13bb1](https://linux-hardware.org/?probe=2cd9b13bb1) | Oct 14, 2021 |
| HP            | 15                          | [bfc196e22b](https://linux-hardware.org/?probe=bfc196e22b) | Oct 13, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| HP            | Notebook                    | [58c6628ba2](https://linux-hardware.org/?probe=58c6628ba2) | Oct 12, 2021 |
| HP            | Notebook                    | [f3f5e6256d](https://linux-hardware.org/?probe=f3f5e6256d) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | [a13d0383b6](https://linux-hardware.org/?probe=a13d0383b6) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | [686377ccd0](https://linux-hardware.org/?probe=686377ccd0) | Oct 12, 2021 |
| HP            | EliteBook 840 G1            | [9bb8ba744e](https://linux-hardware.org/?probe=9bb8ba744e) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| Giani Limi... | ENY1158M                    | [1f9a85e980](https://linux-hardware.org/?probe=1f9a85e980) | Oct 11, 2021 |
| Giani Limi... | ENY1158M                    | [4516242881](https://linux-hardware.org/?probe=4516242881) | Oct 11, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| Unknown       | Z3735F-T02 V1.2             | [6ef4e9edf6](https://linux-hardware.org/?probe=6ef4e9edf6) | Oct 11, 2021 |
| Dell          | Inspiron 3537               | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f5147cd609](https://linux-hardware.org/?probe=f5147cd609) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [e1a73cbf10](https://linux-hardware.org/?probe=e1a73cbf10) | Oct 09, 2021 |
| Samsung       | 700Z3C/700Z5C               | [007ba2bac1](https://linux-hardware.org/?probe=007ba2bac1) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [63e608b4af](https://linux-hardware.org/?probe=63e608b4af) | Oct 09, 2021 |
| Acer          | Aspire E5-571               | [e988105956](https://linux-hardware.org/?probe=e988105956) | Oct 09, 2021 |
| ASUSTek       | X555YA                      | [7bbcc6c5af](https://linux-hardware.org/?probe=7bbcc6c5af) | Oct 09, 2021 |
| HP            | Laptop 17z-cp000            | [db7c1566db](https://linux-hardware.org/?probe=db7c1566db) | Oct 09, 2021 |
| HP            | ENVY dv6                    | [21a3477c3d](https://linux-hardware.org/?probe=21a3477c3d) | Oct 08, 2021 |
| MSI           | GE66 Raider 10UH            | [43c72c2ff3](https://linux-hardware.org/?probe=43c72c2ff3) | Oct 08, 2021 |
| HP            | Unknown                     | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| Acer          | TravelMate P259-MG          | [c62543cf86](https://linux-hardware.org/?probe=c62543cf86) | Oct 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | [b81ab61049](https://linux-hardware.org/?probe=b81ab61049) | Oct 07, 2021 |
| HP            | Pavilion dv7                | [e139664dbf](https://linux-hardware.org/?probe=e139664dbf) | Oct 07, 2021 |
| Lenovo        | Z50-75 80EC                 | [2550a17ad0](https://linux-hardware.org/?probe=2550a17ad0) | Oct 07, 2021 |
| Star Labs     | LabTop                      | [711f2b9e6d](https://linux-hardware.org/?probe=711f2b9e6d) | Oct 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ae113c0df0](https://linux-hardware.org/?probe=ae113c0df0) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [6878f58676](https://linux-hardware.org/?probe=6878f58676) | Oct 06, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a87e581c64](https://linux-hardware.org/?probe=a87e581c64) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [b69897eca3](https://linux-hardware.org/?probe=b69897eca3) | Oct 06, 2021 |
| Dell          | Latitude E5530 non-vPro     | [afe8fca994](https://linux-hardware.org/?probe=afe8fca994) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [dc9074514c](https://linux-hardware.org/?probe=dc9074514c) | Oct 06, 2021 |
| ASUSTek       | X550LB                      | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6717c35dc9](https://linux-hardware.org/?probe=6717c35dc9) | Oct 05, 2021 |
| Dell          | Inspiron 3542               | [f67c2f8d32](https://linux-hardware.org/?probe=f67c2f8d32) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| HP            | Notebook                    | [88b07c9f57](https://linux-hardware.org/?probe=88b07c9f57) | Oct 05, 2021 |
| HP            | Notebook                    | [28c9b584b1](https://linux-hardware.org/?probe=28c9b584b1) | Oct 05, 2021 |
| Dell          | Inspiron 3521               | [9e18ebff31](https://linux-hardware.org/?probe=9e18ebff31) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| HP            | ProBook 430 G1              | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Toshiba       | Satellite C70-B             | [2d4b467fdc](https://linux-hardware.org/?probe=2d4b467fdc) | Oct 04, 2021 |
| Dell          | Latitude E5570              | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | EliteBook 8440p             | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6d94d45cf0](https://linux-hardware.org/?probe=6d94d45cf0) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [ab6b537db8](https://linux-hardware.org/?probe=ab6b537db8) | Oct 04, 2021 |
| HP            | Notebook                    | [c405133048](https://linux-hardware.org/?probe=c405133048) | Oct 03, 2021 |
| Dell          | Latitude 7390               | [50080eb85e](https://linux-hardware.org/?probe=50080eb85e) | Oct 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [a2ee189c63](https://linux-hardware.org/?probe=a2ee189c63) | Oct 03, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a4f833babc](https://linux-hardware.org/?probe=a4f833babc) | Oct 03, 2021 |
| HP            | Pavilion dv7                | [30875abc8f](https://linux-hardware.org/?probe=30875abc8f) | Oct 03, 2021 |
| Dell          | Inspiron 7773               | [2713f21dd7](https://linux-hardware.org/?probe=2713f21dd7) | Oct 03, 2021 |
| Dell          | Latitude E5400              | [ffc2d5a399](https://linux-hardware.org/?probe=ffc2d5a399) | Oct 03, 2021 |
| Toshiba       | Satellite L455D             | [9413906eaa](https://linux-hardware.org/?probe=9413906eaa) | Oct 03, 2021 |
| Dell          | Inspiron 3542               | [e3247b14fa](https://linux-hardware.org/?probe=e3247b14fa) | Oct 02, 2021 |
| Dell          | Latitude E5400              | [529e29fb9d](https://linux-hardware.org/?probe=529e29fb9d) | Oct 02, 2021 |
| Toshiba       | Satellite Pro T110          | [3bd8210e7e](https://linux-hardware.org/?probe=3bd8210e7e) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| Dell          | Latitude E6520              | [e1bf1df5ae](https://linux-hardware.org/?probe=e1bf1df5ae) | Oct 01, 2021 |
| Unknown       | Unknown                     | [f92fca6d48](https://linux-hardware.org/?probe=f92fca6d48) | Oct 01, 2021 |
| Acer          | Nitro AN515-44              | [a7a50b0dbf](https://linux-hardware.org/?probe=a7a50b0dbf) | Oct 01, 2021 |
| HP            | Pavilion dv7                | [590a48aff9](https://linux-hardware.org/?probe=590a48aff9) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| HP            | ENVY 15                     | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [3688fae067](https://linux-hardware.org/?probe=3688fae067) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [3befe3f6e3](https://linux-hardware.org/?probe=3befe3f6e3) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [cc9cc9e925](https://linux-hardware.org/?probe=cc9cc9e925) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6cf7de2b6b](https://linux-hardware.org/?probe=6cf7de2b6b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | [7e0b76f736](https://linux-hardware.org/?probe=7e0b76f736) | Sep 28, 2021 |
| Acer          | Aspire 4830T                | [d36367eb22](https://linux-hardware.org/?probe=d36367eb22) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [f322cce11b](https://linux-hardware.org/?probe=f322cce11b) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| ASUSTek       | X405UA                      | [3a78f7edf5](https://linux-hardware.org/?probe=3a78f7edf5) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| Lenovo        | ThinkPad T520 4242W19       | [0bbb8d9004](https://linux-hardware.org/?probe=0bbb8d9004) | Sep 26, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| Acer          | Aspire V3-571G              | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [9267f59e81](https://linux-hardware.org/?probe=9267f59e81) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [5404d5874a](https://linux-hardware.org/?probe=5404d5874a) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Dell          | Latitude E6220              | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6b6f1c017d](https://linux-hardware.org/?probe=6b6f1c017d) | Sep 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [953ed13df8](https://linux-hardware.org/?probe=953ed13df8) | Sep 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | [a65f8af3ac](https://linux-hardware.org/?probe=a65f8af3ac) | Sep 24, 2021 |
| Apple         | MacBookPro14,1              | [2d0d6ceff3](https://linux-hardware.org/?probe=2d0d6ceff3) | Sep 24, 2021 |
| KOGAN         | KAL11C250SB                 | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1af2027db5](https://linux-hardware.org/?probe=1af2027db5) | Sep 24, 2021 |
| Dell          | Latitude E6430              | [5e66bde0c9](https://linux-hardware.org/?probe=5e66bde0c9) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| HP            | Presario V6000 (GM018UA#... | [944d6af89a](https://linux-hardware.org/?probe=944d6af89a) | Sep 23, 2021 |
| MSI           | Modern 15 A11M              | [fe99af6254](https://linux-hardware.org/?probe=fe99af6254) | Sep 23, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [4d2aa790e0](https://linux-hardware.org/?probe=4d2aa790e0) | Sep 23, 2021 |
| Apple         | MacBookPro9,2               | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| HP            | Notebook                    | [91d439a6a4](https://linux-hardware.org/?probe=91d439a6a4) | Sep 22, 2021 |
| Dynabook      | PORTEGE A30-E               | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | PORTEGE A30-E               | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [a43f2dc4bf](https://linux-hardware.org/?probe=a43f2dc4bf) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [069c0cafd0](https://linux-hardware.org/?probe=069c0cafd0) | Sep 21, 2021 |
| Toshiba       | Satellite L755              | [10baeecbf5](https://linux-hardware.org/?probe=10baeecbf5) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [699803b74c](https://linux-hardware.org/?probe=699803b74c) | Sep 21, 2021 |
| UNOWHY        | Y13G011S4EI                 | [70511c9675](https://linux-hardware.org/?probe=70511c9675) | Sep 21, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| Acer          | Aspire E1-532               | [b0407bdd1c](https://linux-hardware.org/?probe=b0407bdd1c) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| TianBei       | TB-H7                       | [06300b96a7](https://linux-hardware.org/?probe=06300b96a7) | Sep 19, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| Toshiba       | Satellite C870-1C2          | [6129e531d9](https://linux-hardware.org/?probe=6129e531d9) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Acer          | Aspire 4352                 | [3a9aedb538](https://linux-hardware.org/?probe=3a9aedb538) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| Dell          | XPS 13 9350                 | [4dda7e9a7e](https://linux-hardware.org/?probe=4dda7e9a7e) | Sep 18, 2021 |
| ASUSTek       | U31F                        | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Dell          | XPS L321X                   | [2345076968](https://linux-hardware.org/?probe=2345076968) | Sep 18, 2021 |
| Dell          | Latitude E6430              | [2d96c4a645](https://linux-hardware.org/?probe=2d96c4a645) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| Dell          | Latitude E5470              | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| HP            | Notebook                    | [6b2785c2e0](https://linux-hardware.org/?probe=6b2785c2e0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite L755              | [142e3e40c2](https://linux-hardware.org/?probe=142e3e40c2) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| Acer          | Aspire 5733Z                | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Dell          | Latitude E5470              | [032f256bab](https://linux-hardware.org/?probe=032f256bab) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| HP            | Victus by HP Laptop 16-e... | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| Dell          | Latitude E6430              | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| Acer          | Aspire 4830T                | [4e69ac73e4](https://linux-hardware.org/?probe=4e69ac73e4) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| Acer          | V5-171                      | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| HP            | Pavilion dv5                | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Lenovo        | G505s 20255                 | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| ASUSTek       | GR8                         | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | ENVY 15                     | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | Pavilion 15                 | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| Acer          | Aspire 5100                 | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Acer          | AO722                       | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| TianBei       | TB-H7                       | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Aspire 8940G                | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| HP            | ProBook 450 G2              | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Acer          | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP            | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell          | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell          | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell          | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer         | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell          | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 89        | 29.08%  |
| 5.11.0-37-generic | 71        | 23.2%   |
| 5.11.0-34-generic | 57        | 18.63%  |
| 5.11.0-38-generic | 36        | 11.76%  |
| 5.11.0-36-generic | 22        | 7.19%   |
| 5.11.0-25-generic | 8         | 2.61%   |
| 5.8.0-53-generic  | 6         | 1.96%   |
| 5.8.0-59-generic  | 5         | 1.63%   |
| 5.8.0-55-generic  | 5         | 1.63%   |
| 5.8.0-50-generic  | 4         | 1.31%   |
| 5.8.0-63-generic  | 1         | 0.33%   |
| 5.13.18-xanmod1   | 1         | 0.33%   |
| 5.10.0-1044-oem   | 1         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 266       | 92.04%  |
| 5.8.0   | 21        | 7.27%   |
| 5.13.18 | 1         | 0.35%   |
| 5.10.0  | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 266       | 92.04%  |
| 5.8     | 21        | 7.27%   |
| 5.13    | 1         | 0.35%   |
| 5.10    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 287       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 285       | 98.96%  |
| Unknown | 3         | 1.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 282       | 97.92%  |
| Wayland | 4         | 1.39%   |
| Unknown | 2         | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 247       | 85.47%  |
| GDM     | 32        | 11.07%  |
| GDM3    | 10        | 3.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 107       | 37.28%  |
| en_GB | 28        | 9.76%   |
| de_DE | 26        | 9.06%   |
| pt_BR | 16        | 5.57%   |
| en_IN | 15        | 5.23%   |
| es_ES | 10        | 3.48%   |
| en_CA | 10        | 3.48%   |
| fr_FR | 8         | 2.79%   |
| es_MX | 7         | 2.44%   |
| it_IT | 6         | 2.09%   |
| ru_RU | 5         | 1.74%   |
| nl_NL | 5         | 1.74%   |
| es_CL | 5         | 1.74%   |
| en_AU | 5         | 1.74%   |
| pt_PT | 4         | 1.39%   |
| en_ZA | 4         | 1.39%   |
| cs_CZ | 4         | 1.39%   |
| sv_SE | 3         | 1.05%   |
| en_NZ | 3         | 1.05%   |
| hu_HU | 2         | 0.7%    |
| bg_BG | 2         | 0.7%    |
| sk_SK | 1         | 0.35%   |
| ru_UA | 1         | 0.35%   |
| pl_PL | 1         | 0.35%   |
| ja_JP | 1         | 0.35%   |
| fr_BE | 1         | 0.35%   |
| es_PE | 1         | 0.35%   |
| es_AR | 1         | 0.35%   |
| en_SG | 1         | 0.35%   |
| en_PH | 1         | 0.35%   |
| de_CH | 1         | 0.35%   |
| de_AT | 1         | 0.35%   |
| C     | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 194       | 67.36%  |
| BIOS | 94        | 32.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 270       | 94.08%  |
| Zfs     | 7         | 2.44%   |
| Btrfs   | 5         | 1.74%   |
| Overlay | 3         | 1.05%   |
| Xfs     | 1         | 0.35%   |
| Ext2    | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 255       | 88.24%  |
| GPT     | 33        | 11.42%  |
| MBR     | 1         | 0.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 284       | 98.61%  |
| Yes       | 4         | 1.39%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 261       | 90.31%  |
| Yes       | 28        | 9.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 58        | 20.21%  |
| Lenovo              | 51        | 17.77%  |
| Dell                | 51        | 17.77%  |
| Acer                | 34        | 11.85%  |
| ASUSTek Computer    | 30        | 10.45%  |
| Toshiba             | 13        | 4.53%   |
| Apple               | 9         | 3.14%   |
| Unknown             | 7         | 2.44%   |
| MSI                 | 6         | 2.09%   |
| LG Electronics      | 4         | 1.39%   |
| Sony                | 3         | 1.05%   |
| Samsung Electronics | 3         | 1.05%   |
| Notebook            | 2         | 0.7%    |
| Fujitsu             | 2         | 0.7%    |
| UNOWHY              | 1         | 0.35%   |
| TianBei             | 1         | 0.35%   |
| Thomson             | 1         | 0.35%   |
| Star Labs           | 1         | 0.35%   |
| Schenker            | 1         | 0.35%   |
| Razer               | 1         | 0.35%   |
| Packard Bell        | 1         | 0.35%   |
| MECER               | 1         | 0.35%   |
| KOGAN               | 1         | 0.35%   |
| Jumper              | 1         | 0.35%   |
| Insyde              | 1         | 0.35%   |
| Google              | 1         | 0.35%   |
| Giani Limited       | 1         | 0.35%   |
| Dynabook            | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 9         | 3.14%   |
| HP Notebook                                           | 4         | 1.39%   |
| Lenovo Yoga 3 Pro-1370 80HE                           | 2         | 0.7%    |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 0.7%    |
| Lenovo IdeaPad 3 15IIL05 81WE                         | 2         | 0.7%    |
| HP Pavilion Notebook                                  | 2         | 0.7%    |
| HP ENVY Sleekbook 4 PC                                | 2         | 0.7%    |
| HP EliteBook 840 G1                                   | 2         | 0.7%    |
| HP 15                                                 | 2         | 0.7%    |
| Dell Latitude E7470                                   | 2         | 0.7%    |
| Dell Latitude E7440                                   | 2         | 0.7%    |
| Dell Latitude E6520                                   | 2         | 0.7%    |
| Dell Latitude E6430                                   | 2         | 0.7%    |
| Dell Latitude E6420                                   | 2         | 0.7%    |
| Dell Inspiron 5566                                    | 2         | 0.7%    |
| Dell Inspiron 3542                                    | 2         | 0.7%    |
| Dell Inspiron 15 7000 Gaming                          | 2         | 0.7%    |
| ASUS X405UA                                           | 2         | 0.7%    |
| Acer Aspire V3-571G                                   | 2         | 0.7%    |
| Acer Aspire ES1-512                                   | 2         | 0.7%    |
| UNOWHY Y13G011S4EI                                    | 1         | 0.35%   |
| Toshiba Satellite S75Dt-A                             | 1         | 0.35%   |
| Toshiba Satellite Pro T110                            | 1         | 0.35%   |
| Toshiba Satellite Pro L450D                           | 1         | 0.35%   |
| Toshiba Satellite L755                                | 1         | 0.35%   |
| Toshiba Satellite L455D                               | 1         | 0.35%   |
| Toshiba Satellite C870-1C2                            | 1         | 0.35%   |
| Toshiba Satellite C850D-11C                           | 1         | 0.35%   |
| Toshiba Satellite C850-1CP                            | 1         | 0.35%   |
| Toshiba Satellite C75D-B                              | 1         | 0.35%   |
| Toshiba Satellite C70-B                               | 1         | 0.35%   |
| Toshiba PORTEGE Z30-A                                 | 1         | 0.35%   |
| Toshiba PORTEGE Z20t-C                                | 1         | 0.35%   |
| Toshiba PORTEGE R700                                  | 1         | 0.35%   |
| TianBei TB-H7                                         | 1         | 0.35%   |
| Thomson N17C512                                       | 1         | 0.35%   |
| Star Labs LabTop                                      | 1         | 0.35%   |
| Sony VPCS135FX                                        | 1         | 0.35%   |
| Sony VPCF215FX                                        | 1         | 0.35%   |
| Sony VGN-SR5                                          | 1         | 0.35%   |
| Schenker VIA 15 Pro                                   | 1         | 0.35%   |
| Samsung 700Z3C/700Z5C                                 | 1         | 0.35%   |
| Samsung 550P5C/550P7C                                 | 1         | 0.35%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.35%   |
| Razer Book 13 - RZ09-0357                             | 1         | 0.35%   |
| Packard Bell DOT S                                    | 1         | 0.35%   |
| Notebook X170SM                                       | 1         | 0.35%   |
| Notebook W94_95_97SU2,SUY,-C,-T                       | 1         | 0.35%   |
| MSI Modern 15 A11M                                    | 1         | 0.35%   |
| MSI Modern 14 B10MW                                   | 1         | 0.35%   |
| MSI GS75 Stealth 10SF                                 | 1         | 0.35%   |
| MSI GL62 7RDX                                         | 1         | 0.35%   |
| MSI GE75 Raider 8RF                                   | 1         | 0.35%   |
| MSI GE66 Raider 10UH                                  | 1         | 0.35%   |
| MECER Z140C+Home                                      | 1         | 0.35%   |
| LG S460-G.BG31P1                                      | 1         | 0.35%   |
| LG C400-G.BC22P1                                      | 1         | 0.35%   |
| LG A410-K.BE47P1                                      | 1         | 0.35%   |
| LG 17U70N-R.AAS7U1                                    | 1         | 0.35%   |
| Lenovo Z50-75 80EC                                    | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 26        | 9.06%   |
| Dell Latitude      | 21        | 7.32%   |
| Lenovo IdeaPad     | 18        | 6.27%   |
| Lenovo ThinkPad    | 17        | 5.92%   |
| Dell Inspiron      | 16        | 5.57%   |
| HP Pavilion        | 12        | 4.18%   |
| Toshiba Satellite  | 10        | 3.48%   |
| Unknown            | 9         | 3.14%   |
| HP EliteBook       | 8         | 2.79%   |
| HP ProBook         | 7         | 2.44%   |
| HP ENVY            | 7         | 2.44%   |
| Dell XPS           | 7         | 2.44%   |
| ASUS VivoBook      | 6         | 2.09%   |
| HP Notebook        | 4         | 1.39%   |
| HP Laptop          | 4         | 1.39%   |
| HP 255             | 4         | 1.39%   |
| Toshiba PORTEGE    | 3         | 1.05%   |
| Dell Vostro        | 3         | 1.05%   |
| Dell Precision     | 3         | 1.05%   |
| Apple MacBookPro11 | 3         | 1.05%   |
| Acer Swift         | 3         | 1.05%   |
| MSI Modern         | 2         | 0.7%    |
| Lenovo Yoga        | 2         | 0.7%    |
| Lenovo Legion      | 2         | 0.7%    |
| HP Stream          | 2         | 0.7%    |
| HP 15              | 2         | 0.7%    |
| Fujitsu LIFEBOOK   | 2         | 0.7%    |
| ASUS ZenBook       | 2         | 0.7%    |
| ASUS X405UA        | 2         | 0.7%    |
| ASUS ROG           | 2         | 0.7%    |
| ASUS ASUS          | 2         | 0.7%    |
| Acer Nitro         | 2         | 0.7%    |
| UNOWHY Y13G011S4EI | 1         | 0.35%   |
| TianBei TB-H7      | 1         | 0.35%   |
| Thomson N17C512    | 1         | 0.35%   |
| Star Labs LabTop   | 1         | 0.35%   |
| Sony VPCS135FX     | 1         | 0.35%   |
| Sony VPCF215FX     | 1         | 0.35%   |
| Sony VGN-SR5       | 1         | 0.35%   |
| Schenker VIA       | 1         | 0.35%   |
| Samsung 700Z3C     | 1         | 0.35%   |
| Samsung 550P5C     | 1         | 0.35%   |
| Samsung 300E5EV    | 1         | 0.35%   |
| Razer Book         | 1         | 0.35%   |
| Packard Bell DOT   | 1         | 0.35%   |
| Notebook X170SM    | 1         | 0.35%   |
| Notebook W94       | 1         | 0.35%   |
| MSI GS75           | 1         | 0.35%   |
| MSI GL62           | 1         | 0.35%   |
| MSI GE75           | 1         | 0.35%   |
| MSI GE66           | 1         | 0.35%   |
| MECER Z140C+Home   | 1         | 0.35%   |
| LG S460-G.BG31P1   | 1         | 0.35%   |
| LG C400-G.BC22P1   | 1         | 0.35%   |
| LG A410-K.BE47P1   | 1         | 0.35%   |
| LG 17U70N-R.AAS7U1 | 1         | 0.35%   |
| Lenovo Z50-75      | 1         | 0.35%   |
| Lenovo Y520-15IKBM | 1         | 0.35%   |
| Lenovo ThinkBook   | 1         | 0.35%   |
| Lenovo G580        | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 57        | 19.86%  |
| 2020 | 43        | 14.98%  |
| 2019 | 28        | 9.76%   |
| 2018 | 28        | 9.76%   |
| 2011 | 22        | 7.67%   |
| 2014 | 19        | 6.62%   |
| 2012 | 17        | 5.92%   |
| 2015 | 15        | 5.23%   |
| 2013 | 13        | 4.53%   |
| 2017 | 12        | 4.18%   |
| 2016 | 9         | 3.14%   |
| 2010 | 7         | 2.44%   |
| 2009 | 7         | 2.44%   |
| 2008 | 6         | 2.09%   |
| 2007 | 3         | 1.05%   |
| 2006 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 287       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 237       | 82.29%  |
| Enabled  | 51        | 17.71%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 285       | 99.3%   |
| Yes  | 2         | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 107       | 37.28%  |
| 3.01-4.0    | 77        | 26.83%  |
| 8.01-16.0   | 47        | 16.38%  |
| 16.01-24.0  | 29        | 10.1%   |
| 32.01-64.0  | 13        | 4.53%   |
| 1.01-2.0    | 10        | 3.48%   |
| 64.01-256.0 | 2         | 0.7%    |
| 24.01-32.0  | 1         | 0.35%   |
| 2.01-3.0    | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 133       | 43.89%  |
| 2.01-3.0   | 95        | 31.35%  |
| 3.01-4.0   | 44        | 14.52%  |
| 4.01-8.0   | 25        | 8.25%   |
| 0.51-1.0   | 4         | 1.32%   |
| 24.01-32.0 | 1         | 0.33%   |
| 8.01-16.0  | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 220       | 76.39%  |
| 2      | 60        | 20.83%  |
| 3      | 7         | 2.43%   |
| 4      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 175       | 60.76%  |
| Yes       | 113       | 39.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 239       | 83.28%  |
| No        | 48        | 16.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 278       | 96.86%  |
| No        | 9         | 3.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 222       | 77.08%  |
| No        | 66        | 22.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 56        | 19.51%  |
| Germany      | 34        | 11.85%  |
| UK           | 22        | 7.67%   |
| Brazil       | 22        | 7.67%   |
| India        | 16        | 5.57%   |
| Spain        | 11        | 3.83%   |
| Canada       | 10        | 3.48%   |
| Mexico       | 9         | 3.14%   |
| France       | 9         | 3.14%   |
| South Africa | 7         | 2.44%   |
| Netherlands  | 7         | 2.44%   |
| Italy        | 7         | 2.44%   |
| Chile        | 5         | 1.74%   |
| Australia    | 5         | 1.74%   |
| Sweden       | 4         | 1.39%   |
| Czechia      | 4         | 1.39%   |
| Austria      | 4         | 1.39%   |
| Russia       | 3         | 1.05%   |
| New Zealand  | 3         | 1.05%   |
| Japan        | 3         | 1.05%   |
| Hungary      | 3         | 1.05%   |
| Switzerland  | 2         | 0.7%    |
| Romania      | 2         | 0.7%    |
| Portugal     | 2         | 0.7%    |
| Philippines  | 2         | 0.7%    |
| Morocco      | 2         | 0.7%    |
| Bulgaria     | 2         | 0.7%    |
| Belgium      | 2         | 0.7%    |
| Argentina    | 2         | 0.7%    |
| Vietnam      | 1         | 0.35%   |
| Venezuela    | 1         | 0.35%   |
| Ukraine      | 1         | 0.35%   |
| Turkey       | 1         | 0.35%   |
| Thailand     | 1         | 0.35%   |
| Tanzania     | 1         | 0.35%   |
| Slovakia     | 1         | 0.35%   |
| Singapore    | 1         | 0.35%   |
| Qatar        | 1         | 0.35%   |
| Poland       | 1         | 0.35%   |
| Norway       | 1         | 0.35%   |
| Nigeria      | 1         | 0.35%   |
| Nepal        | 1         | 0.35%   |
| Malaysia     | 1         | 0.35%   |
| Madagascar   | 1         | 0.35%   |
| Kenya        | 1         | 0.35%   |
| Jersey       | 1         | 0.35%   |
| Israel       | 1         | 0.35%   |
| Ireland      | 1         | 0.35%   |
| Indonesia    | 1         | 0.35%   |
| Greece       | 1         | 0.35%   |
| Ghana        | 1         | 0.35%   |
| Egypt        | 1         | 0.35%   |
| Colombia     | 1         | 0.35%   |
| Belarus      | 1         | 0.35%   |
| Bangladesh   | 1         | 0.35%   |
| Angola       | 1         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 3         | 1.03%   |
| S??o Lu?­s       | 3         | 1.03%   |
| Rome             | 3         | 1.03%   |
| London           | 3         | 1.03%   |
| Johannesburg     | 3         | 1.03%   |
| Hyderabad        | 3         | 1.03%   |
| Glasgow          | 3         | 1.03%   |
| Taboao da Serra  | 2         | 0.69%   |
| Sydney           | 2         | 0.69%   |
| Santiago         | 2         | 0.69%   |
| San Francisco    | 2         | 0.69%   |
| Rochester        | 2         | 0.69%   |
| Paris            | 2         | 0.69%   |
| Munich           | 2         | 0.69%   |
| Moscow           | 2         | 0.69%   |
| Montreal         | 2         | 0.69%   |
| Milan            | 2         | 0.69%   |
| Madrid           | 2         | 0.69%   |
| Maca?©           | 2         | 0.69%   |
| Kolkata          | 2         | 0.69%   |
| Kaiserslautern   | 2         | 0.69%   |
| Independence     | 2         | 0.69%   |
| Ernakulam        | 2         | 0.69%   |
| Chicago          | 2         | 0.69%   |
| Chennai          | 2         | 0.69%   |
| Berlin           | 2         | 0.69%   |
| Barcelona        | 2         | 0.69%   |
| Auckland         | 2         | 0.69%   |
| Amsterdam        | 2         | 0.69%   |
| Ahmedabad        | 2         | 0.69%   |
| Zurich           | 1         | 0.34%   |
| Zionsville       | 1         | 0.34%   |
| Zdounky          | 1         | 0.34%   |
| Zaventem         | 1         | 0.34%   |
| Zacatecas City   | 1         | 0.34%   |
| Zabrze           | 1         | 0.34%   |
| Yokohama         | 1         | 0.34%   |
| Winston-Salem    | 1         | 0.34%   |
| Wigan            | 1         | 0.34%   |
| Weymouth         | 1         | 0.34%   |
| West Jordan      | 1         | 0.34%   |
| Vogtsburg        | 1         | 0.34%   |
| Veracruz         | 1         | 0.34%   |
| Varna            | 1         | 0.34%   |
| Vancouver        | 1         | 0.34%   |
| Twinsburg        | 1         | 0.34%   |
| Tunnel Hill      | 1         | 0.34%   |
| Triunfo          | 1         | 0.34%   |
| Toulouse         | 1         | 0.34%   |
| Tokyo            | 1         | 0.34%   |
| Teltow           | 1         | 0.34%   |
| Tatu?­           | 1         | 0.34%   |
| Tangier          | 1         | 0.34%   |
| Sutton Coldfield | 1         | 0.34%   |
| Stuttgart        | 1         | 0.34%   |
| Stockholm        | 1         | 0.34%   |
| Stadskanaal      | 1         | 0.34%   |
| Spremberg        | 1         | 0.34%   |
| South Charleston | 1         | 0.34%   |
| Sigless          | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 60        | 72     | 17.91%  |
| Seagate             | 45        | 50     | 13.43%  |
| WDC                 | 30        | 30     | 8.96%   |
| Toshiba             | 29        | 29     | 8.66%   |
| SanDisk             | 22        | 26     | 6.57%   |
| Unknown             | 21        | 27     | 6.27%   |
| Crucial             | 14        | 14     | 4.18%   |
| Kingston            | 12        | 15     | 3.58%   |
| Hitachi             | 12        | 14     | 3.58%   |
| SK Hynix            | 11        | 16     | 3.28%   |
| HGST                | 9         | 11     | 2.69%   |
| Micron Technology   | 8         | 9      | 2.39%   |
| Intel               | 7         | 8      | 2.09%   |
| A-DATA Technology   | 7         | 8      | 2.09%   |
| Intenso             | 5         | 5      | 1.49%   |
| Apple               | 5         | 6      | 1.49%   |
| SPCC                | 4         | 5      | 1.19%   |
| LITEONIT            | 4         | 5      | 1.19%   |
| KIOXIA              | 4         | 4      | 1.19%   |
| Fujitsu             | 3         | 4      | 0.9%    |
| SABRENT             | 2         | 2      | 0.6%    |
| PNY                 | 2         | 3      | 0.6%    |
| Lite-On             | 2         | 3      | 0.6%    |
| JMicron             | 2         | 3      | 0.6%    |
| Unknown             | 2         | 2      | 0.6%    |
| Verbatim            | 1         | 1      | 0.3%    |
| Vaseky              | 1         | 2      | 0.3%    |
| Transcend           | 1         | 1      | 0.3%    |
| Team                | 1         | 1      | 0.3%    |
| Star                | 1         | 1      | 0.3%    |
| Phison              | 1         | 1      | 0.3%    |
| Patriot             | 1         | 1      | 0.3%    |
| Netac               | 1         | 1      | 0.3%    |
| KingSpec            | 1         | 1      | 0.3%    |
| GOODRAM             | 1         | 1      | 0.3%    |
| E535N               | 1         | 1      | 0.3%    |
| China               | 1         | 2      | 0.3%    |
| BUFFALO             | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                  | 9         | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB          | 8         | 2.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 8         | 2.28%   |
| Unknown MMC Card  64GB                  | 7         | 1.99%   |
| Samsung PM963 2.5" NVMe PCIe SSD 512GB  | 7         | 1.99%   |
| Toshiba MQ01ABF050 500GB                | 6         | 1.71%   |
| Samsung NVMe SSD Drive 256GB            | 5         | 1.42%   |
| Sandisk NVMe SSD Drive 256GB            | 4         | 1.14%   |
| Samsung SSD 860 EVO 250GB               | 4         | 1.14%   |
| Samsung NVMe SSD Drive 500GB            | 4         | 1.14%   |
| WDC WD10JPVX-22JC3T0 1TB                | 3         | 0.85%   |
| Unknown SD/MMC/MS PRO 128GB             | 3         | 0.85%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 0.85%   |
| SK Hynix NVMe SSD Drive 256GB           | 3         | 0.85%   |
| Seagate ST9500325AS 500GB               | 3         | 0.85%   |
| Sandisk NVMe SSD Drive 512GB            | 3         | 0.85%   |
| Samsung SSD 860 EVO 500GB               | 3         | 0.85%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.85%   |
| Samsung SSD 850 EVO 500GB               | 3         | 0.85%   |
| Micron NVMe SSD Drive 512GB             | 3         | 0.85%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.85%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 0.85%   |
| Hitachi HTS547575A9E384 752GB           | 3         | 0.85%   |
| HGST HTS725050A7E630 500GB              | 3         | 0.85%   |
| Crucial CT500MX500SSD1 500GB            | 3         | 0.85%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 2         | 0.57%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.57%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB    | 2         | 0.57%   |
| Toshiba MQ02ABD100H 1TB                 | 2         | 0.57%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.57%   |
| Toshiba MK2555GSX 250GB                 | 2         | 0.57%   |
| Toshiba MK2552GSX 250GB                 | 2         | 0.57%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 0.57%   |
| SPCC SPCCSolidStateDisk 256GB SSD       | 2         | 0.57%   |
| SK Hynix NVMe SSD Drive 512GB           | 2         | 0.57%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 0.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 0.57%   |
| Seagate ST320LT007-9ZV142 320GB         | 2         | 0.57%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.57%   |
| SanDisk SSD PLUS 480GB                  | 2         | 0.57%   |
| SanDisk SSD PLUS 240GB                  | 2         | 0.57%   |
| Sandisk NVMe SSD Drive 1TB              | 2         | 0.57%   |
| Samsung SSD 870 QVO 1TB                 | 2         | 0.57%   |
| Samsung SSD 860 QVO 1TB                 | 2         | 0.57%   |
| Samsung SSD 850 EVO 250GB               | 2         | 0.57%   |
| Samsung SSD 840 EVO 250GB               | 2         | 0.57%   |
| Samsung NVMe SSD Drive 2TB              | 2         | 0.57%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.57%   |
| SABRENT Disk 320GB                      | 2         | 0.57%   |
| KIOXIA NVMe SSD Drive 512GB             | 2         | 0.57%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 0.57%   |
| Intel NVMe SSD Drive 512GB              | 2         | 0.57%   |
| Intel NVMe SSD Drive 1024GB             | 2         | 0.57%   |
| Hitachi HTS545032B9A300 320GB           | 2         | 0.57%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.57%   |
| HGST HTS545050A7E380 500GB              | 2         | 0.57%   |
| Crucial CT480BX500SSD1 480GB            | 2         | 0.57%   |
| Apple SSD SM0256F 256GB                 | 2         | 0.57%   |
| A-DATA SU800 512GB SSD                  | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 48     | 36.36%  |
| Toshiba             | 22        | 22     | 18.18%  |
| WDC                 | 20        | 20     | 16.53%  |
| Hitachi             | 12        | 14     | 9.92%   |
| HGST                | 9         | 11     | 7.44%   |
| Unknown             | 3         | 3      | 2.48%   |
| Samsung Electronics | 3         | 3      | 2.48%   |
| Fujitsu             | 3         | 4      | 2.48%   |
| SABRENT             | 2         | 2      | 1.65%   |
| JMicron             | 1         | 2      | 0.83%   |
| Intenso             | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 36     | 27.64%  |
| Crucial             | 14        | 14     | 11.38%  |
| Kingston            | 12        | 15     | 9.76%   |
| SanDisk             | 11        | 14     | 8.94%   |
| WDC                 | 5         | 5      | 4.07%   |
| SK Hynix            | 5         | 5      | 4.07%   |
| A-DATA Technology   | 5         | 6      | 4.07%   |
| Toshiba             | 4         | 4      | 3.25%   |
| SPCC                | 4         | 5      | 3.25%   |
| Micron Technology   | 4         | 5      | 3.25%   |
| LITEONIT            | 4         | 5      | 3.25%   |
| Intenso             | 4         | 4      | 3.25%   |
| Apple               | 3         | 3      | 2.44%   |
| PNY                 | 2         | 3      | 1.63%   |
| Intel               | 2         | 2      | 1.63%   |
| Verbatim            | 1         | 1      | 0.81%   |
| Transcend           | 1         | 1      | 0.81%   |
| Team                | 1         | 1      | 0.81%   |
| Star                | 1         | 1      | 0.81%   |
| Patriot             | 1         | 1      | 0.81%   |
| Netac               | 1         | 1      | 0.81%   |
| KingSpec            | 1         | 1      | 0.81%   |
| GOODRAM             | 1         | 1      | 0.81%   |
| China               | 1         | 2      | 0.81%   |
| BUFFALO             | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 118       | 137    | 36.09%  |
| HDD     | 118       | 131    | 36.09%  |
| NVMe    | 67        | 86     | 20.49%  |
| MMC     | 18        | 24     | 5.5%    |
| Unknown | 6         | 8      | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 221       | 262    | 69.5%   |
| NVMe | 67        | 86     | 21.07%  |
| MMC  | 18        | 24     | 5.66%   |
| SAS  | 12        | 14     | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 160       | 186    | 68.38%  |
| 0.51-1.0   | 66        | 72     | 28.21%  |
| 1.01-2.0   | 7         | 9      | 2.99%   |
| 3.01-4.0   | 1         | 1      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 101       | 34.83%  |
| 251-500        | 82        | 28.28%  |
| 501-1000       | 39        | 13.45%  |
| 51-100         | 35        | 12.07%  |
| 21-50          | 12        | 4.14%   |
| 1001-2000      | 8         | 2.76%   |
| Unknown        | 5         | 1.72%   |
| 2001-3000      | 3         | 1.03%   |
| 1-20           | 3         | 1.03%   |
| More than 3000 | 2         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 134       | 45.58%  |
| 21-50          | 88        | 29.93%  |
| 101-250        | 27        | 9.18%   |
| 51-100         | 25        | 8.5%    |
| 251-500        | 8         | 2.72%   |
| 501-1000       | 6         | 2.04%   |
| Unknown        | 5         | 1.7%    |
| More than 3000 | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB    | 2         | 2      | 40%     |
| WDC WD10JPVX-22JC3T0 1TB   | 1         | 1      | 20%     |
| Seagate ST9200420ASG 200GB | 1         | 1      | 20%     |
| HGST HTS725050A7E630 500GB | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 255       | 343    | 87.33%  |
| Works    | 31        | 37     | 10.62%  |
| Malfunc  | 5         | 5      | 1.71%   |
| Failed   | 1         | 1      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 206       | 64.58%  |
| AMD                              | 42        | 13.17%  |
| Samsung Electronics              | 30        | 9.4%    |
| Sandisk                          | 15        | 4.7%    |
| SK Hynix                         | 6         | 1.88%   |
| KIOXIA                           | 5         | 1.57%   |
| Micron Technology                | 4         | 1.25%   |
| Toshiba America Info Systems     | 2         | 0.63%   |
| Nvidia                           | 2         | 0.63%   |
| Lite-On Technology               | 2         | 0.63%   |
| ADATA Technology                 | 2         | 0.63%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Phison Electronics               | 1         | 0.31%   |
| Apple                            | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 37        | 10.91%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 28        | 8.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 21        | 6.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 6.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 21        | 6.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 20        | 5.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 3.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 2.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 2.65%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 7         | 2.06%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 2.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 1.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 1.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.77%   |
| KIOXIA Non-Volatile memory controller                                            | 5         | 1.47%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 5         | 1.47%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.47%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.18%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.18%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 0.88%   |
| Intel SSD 660P Series                                                            | 3         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.88%   |
| SK Hynix BC511                                                                   | 2         | 0.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.59%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.59%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.59%   |
| Samsung Apple PCIe SSD                                                           | 2         | 0.59%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.59%   |
| Lite-On Non-Volatile memory controller                                           | 2         | 0.59%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.59%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 2         | 0.59%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile       | 2         | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.59%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.29%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.29%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.29%   |
| Samsung Electronics SATA controller                                              | 1         | 0.29%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.29%   |
| Intel SSD 600P Series                                                            | 1         | 0.29%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.29%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.29%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 0.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 0.29%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 0.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 219       | 66.57%  |
| NVMe | 67        | 20.36%  |
| RAID | 26        | 7.9%    |
| IDE  | 17        | 5.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 235       | 81.88%  |
| AMD    | 52        | 18.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 3.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 2.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 2.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 2.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.39%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 1.39%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.05%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 1.05%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.05%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.05%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 1.05%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.05%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.05%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.05%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 1.05%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 1.05%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 1.05%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 3         | 1.05%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 1.05%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.05%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 1.05%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 3         | 1.05%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 0.7%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.7%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.7%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.7%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.7%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.7%    |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.7%    |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 0.7%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.7%    |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.7%    |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.7%    |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.7%    |
| Intel Core i3-2370M CPU @ 2.40GHz             | 2         | 0.7%    |
| Intel Core i3-2328M CPU @ 2.20GHz             | 2         | 0.7%    |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 0.7%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 0.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.7%    |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 0.7%    |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 0.7%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.7%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 90        | 31.36%  |
| Intel Core i7                        | 55        | 19.16%  |
| Intel Core i3                        | 26        | 9.06%   |
| Intel Celeron                        | 20        | 6.97%   |
| Intel Core 2 Duo                     | 15        | 5.23%   |
| AMD Ryzen 5                          | 12        | 4.18%   |
| Other                                | 9         | 3.14%   |
| Intel Pentium                        | 8         | 2.79%   |
| AMD Ryzen 7                          | 8         | 2.79%   |
| AMD A6                               | 8         | 2.79%   |
| Intel Atom                           | 7         | 2.44%   |
| AMD A10                              | 4         | 1.39%   |
| AMD A8                               | 3         | 1.05%   |
| AMD Ryzen 3                          | 2         | 0.7%    |
| AMD FX                               | 2         | 0.7%    |
| AMD E2                               | 2         | 0.7%    |
| AMD E1                               | 2         | 0.7%    |
| Intel Pentium Silver                 | 1         | 0.35%   |
| Intel Pentium Dual-Core              | 1         | 0.35%   |
| Intel Core m5                        | 1         | 0.35%   |
| Intel Core M                         | 1         | 0.35%   |
| Intel Core i9                        | 1         | 0.35%   |
| Intel Celeron M                      | 1         | 0.35%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.35%   |
| AMD Turion 64 Mobile                 | 1         | 0.35%   |
| AMD Sempron                          | 1         | 0.35%   |
| AMD Ryzen 7 PRO                      | 1         | 0.35%   |
| AMD E                                | 1         | 0.35%   |
| AMD C-60                             | 1         | 0.35%   |
| AMD Athlon                           | 1         | 0.35%   |
| AMD A4                               | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 165       | 57.49%  |
| 4      | 100       | 34.84%  |
| 8      | 9         | 3.14%   |
| 6      | 8         | 2.79%   |
| 1      | 4         | 1.39%   |
| 10     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 287       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 208       | 72.47%  |
| 1      | 79        | 27.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 287       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 30        | 10.38%  |
| 0x40651    | 21        | 7.27%   |
| 0x306a9    | 21        | 7.27%   |
| Unknown    | 19        | 6.57%   |
| 0x806ea    | 16        | 5.54%   |
| 0x406e3    | 10        | 3.46%   |
| 0x20655    | 10        | 3.46%   |
| 0x806ec    | 9         | 3.11%   |
| 0x306d4    | 9         | 3.11%   |
| 0x1067a    | 9         | 3.11%   |
| 0x706e5    | 8         | 2.77%   |
| 0x906e9    | 7         | 2.42%   |
| 0x806e9    | 7         | 2.42%   |
| 0x30678    | 7         | 2.42%   |
| 0x08108102 | 7         | 2.42%   |
| 0x806c1    | 6         | 2.08%   |
| 0x506c9    | 6         | 2.08%   |
| 0x906ea    | 5         | 1.73%   |
| 0x406c4    | 5         | 1.73%   |
| 0x306c3    | 5         | 1.73%   |
| 0x07030105 | 5         | 1.73%   |
| 0xa0652    | 4         | 1.38%   |
| 0x20652    | 4         | 1.38%   |
| 0x08108109 | 4         | 1.38%   |
| 0x6fb      | 3         | 1.04%   |
| 0x07030106 | 3         | 1.04%   |
| 0x05000119 | 3         | 1.04%   |
| 0x806eb    | 2         | 0.69%   |
| 0x706a8    | 2         | 0.69%   |
| 0x6fd      | 2         | 0.69%   |
| 0x506e3    | 2         | 0.69%   |
| 0x40661    | 2         | 0.69%   |
| 0x10676    | 2         | 0.69%   |
| 0x08608103 | 2         | 0.69%   |
| 0x08600106 | 2         | 0.69%   |
| 0x08600104 | 2         | 0.69%   |
| 0x08600103 | 2         | 0.69%   |
| 0x06006705 | 2         | 0.69%   |
| 0x06006704 | 2         | 0.69%   |
| 0x0600611a | 2         | 0.69%   |
| 0x06003106 | 2         | 0.69%   |
| 0x06001119 | 2         | 0.69%   |
| 0x02000057 | 2         | 0.69%   |
| 0xa0655    | 1         | 0.35%   |
| 0x906c0    | 1         | 0.35%   |
| 0x706a1    | 1         | 0.35%   |
| 0x6fa      | 1         | 0.35%   |
| 0x6f6      | 1         | 0.35%   |
| 0x406c3    | 1         | 0.35%   |
| 0x30661    | 1         | 0.35%   |
| 0x106e5    | 1         | 0.35%   |
| 0x0a50000c | 1         | 0.35%   |
| 0x08608102 | 1         | 0.35%   |
| 0x07030104 | 1         | 0.35%   |
| 0x07000110 | 1         | 0.35%   |
| 0x0700010f | 1         | 0.35%   |
| 0x03000027 | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 52        | 18.12%  |
| SandyBridge     | 31        | 10.8%   |
| Haswell         | 29        | 10.1%   |
| IvyBridge       | 21        | 7.32%   |
| Westmere        | 15        | 5.23%   |
| Silvermont      | 14        | 4.88%   |
| Skylake         | 13        | 4.53%   |
| Zen+            | 12        | 4.18%   |
| Penryn          | 11        | 3.83%   |
| Puma            | 9         | 3.14%   |
| Broadwell       | 9         | 3.14%   |
| IceLake         | 8         | 2.79%   |
| Zen 2           | 7         | 2.44%   |
| TigerLake       | 7         | 2.44%   |
| Core            | 7         | 2.44%   |
| Goldmont        | 6         | 2.09%   |
| Excavator       | 6         | 2.09%   |
| CometLake       | 5         | 1.74%   |
| Goldmont plus   | 3         | 1.05%   |
| Bobcat          | 3         | 1.05%   |
| Unknown         | 3         | 1.05%   |
| Zen 3           | 2         | 0.7%    |
| Steamroller     | 2         | 0.7%    |
| Piledriver      | 2         | 0.7%    |
| Nehalem         | 2         | 0.7%    |
| K8 & K10 hybrid | 2         | 0.7%    |
| Jaguar          | 2         | 0.7%    |
| Tremont         | 1         | 0.35%   |
| K8 Hammer       | 1         | 0.35%   |
| K10 Llano       | 1         | 0.35%   |
| Bonnell         | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 212       | 61.63%  |
| Nvidia                           | 67        | 19.48%  |
| AMD                              | 64        | 18.6%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 7.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 6.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 5.92%   |
| Intel UHD Graphics 620                                                                   | 16        | 4.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 3.66%   |
| AMD Picasso                                                                              | 12        | 3.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.54%   |
| Intel HD Graphics 620                                                                    | 9         | 2.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.25%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1.97%   |
| Intel HD Graphics 630                                                                    | 7         | 1.97%   |
| AMD Renoir                                                                               | 7         | 1.97%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 1.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.69%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.13%   |
| Intel HD Graphics 500                                                                    | 4         | 1.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.13%   |
| Nvidia TU117M                                                                            | 3         | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.85%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.85%   |
| AMD Lucienne                                                                             | 3         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.56%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.56%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 2         | 0.56%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.56%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.56%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 0.56%   |
| Intel HD Graphics 5300                                                                   | 2         | 0.56%   |
| Intel HD Graphics 530                                                                    | 2         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 2         | 0.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.56%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.56%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.56%   |
| AMD Richland [Radeon HD 8650G]                                                           | 2         | 0.56%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 2         | 0.56%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                                       | 2         | 0.56%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.28%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.28%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.28%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.28%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.28%   |
| Nvidia GT216M [GeForce GT 325M]                                                          | 1         | 0.28%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.28%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.28%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 162       | 56.45%  |
| 1 x AMD        | 44        | 15.33%  |
| Intel + Nvidia | 43        | 14.98%  |
| 1 x Nvidia     | 17        | 5.92%   |
| Intel + AMD    | 7         | 2.44%   |
| AMD + Nvidia   | 7         | 2.44%   |
| 2 x AMD        | 6         | 2.09%   |
| 1 x SiS        | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 247       | 86.06%  |
| Proprietary | 36        | 12.54%  |
| Unknown     | 4         | 1.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 188       | 64.6%   |
| 1.01-2.0   | 31        | 10.65%  |
| 0.51-1.0   | 26        | 8.93%   |
| 0.01-0.5   | 26        | 8.93%   |
| 3.01-4.0   | 11        | 3.78%   |
| 5.01-6.0   | 4         | 1.37%   |
| 7.01-8.0   | 3         | 1.03%   |
| 2.01-3.0   | 1         | 0.34%   |
| 8.01-16.0  | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 67        | 21.61%  |
| Chimei Innolux          | 46        | 14.84%  |
| LG Display              | 40        | 12.9%   |
| BOE                     | 39        | 12.58%  |
| Samsung Electronics     | 38        | 12.26%  |
| Sharp                   | 9         | 2.9%    |
| Chi Mei Optoelectronics | 9         | 2.9%    |
| Apple                   | 9         | 2.9%    |
| PANDA                   | 8         | 2.58%   |
| Lenovo                  | 5         | 1.61%   |
| Goldstar                | 5         | 1.61%   |
| Dell                    | 5         | 1.61%   |
| LGD                     | 4         | 1.29%   |
| Acer                    | 4         | 1.29%   |
| Vizio                   | 3         | 0.97%   |
| Iiyama                  | 2         | 0.65%   |
| Hewlett-Packard         | 2         | 0.65%   |
| HannStar                | 2         | 0.65%   |
| BenQ                    | 2         | 0.65%   |
| AOC                     | 2         | 0.65%   |
| Unknown                 | 1         | 0.32%   |
| Sceptre Tech            | 1         | 0.32%   |
| Philips                 | 1         | 0.32%   |
| MStar                   | 1         | 0.32%   |
| LG Philips              | 1         | 0.32%   |
| InnoLux Display         | 1         | 0.32%   |
| Gateway                 | 1         | 0.32%   |
| CPT                     | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 1.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 5         | 1.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch          | 4         | 1.28%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 3         | 0.96%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.96%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.96%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch     | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch     | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 2         | 0.64%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.64%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 2         | 0.64%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.64%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 2         | 0.64%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch          | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 0.64%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.64%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 310x170mm 13.9-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.64%   |
| Apple Color LCD APP9C5B 1280x800 290x180mm 13.4-inch                     | 2         | 0.64%   |
| Vizio M422i-B1 VIZ1006 1920x1080 930x523mm 42.0-inch                     | 1         | 0.32%   |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                      | 1         | 0.32%   |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                      | 1         | 0.32%   |
| Unknown LCD Monitor CSO 2560x1600                                        | 1         | 0.32%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 0.32%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                  | 1         | 0.32%   |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                         | 1         | 0.32%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch            | 1         | 0.32%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch      | 1         | 0.32%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch        | 1         | 0.32%   |
| Samsung Electronics LF27T450F SAM7097 1920x1080 600x340mm 27.2-inch      | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch     | 1         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 121       | 39.8%   |
| 1920x1080 (FHD)    | 108       | 35.53%  |
| 1600x900 (HD+)     | 21        | 6.91%   |
| 1280x800 (WXGA)    | 11        | 3.62%   |
| 3840x2160 (4K)     | 9         | 2.96%   |
| 1440x900 (WXGA+)   | 4         | 1.32%   |
| Unknown            | 4         | 1.32%   |
| 3200x1800 (QHD+)   | 3         | 0.99%   |
| 2880x1800          | 3         | 0.99%   |
| 2560x1600          | 3         | 0.99%   |
| 2560x1440 (QHD)    | 3         | 0.99%   |
| 3840x2400          | 2         | 0.66%   |
| 2256x1504          | 2         | 0.66%   |
| 4480x1600          | 1         | 0.33%   |
| 3840x1200          | 1         | 0.33%   |
| 3840x1080          | 1         | 0.33%   |
| 3600x1080          | 1         | 0.33%   |
| 2560x1080          | 1         | 0.33%   |
| 1920x515           | 1         | 0.33%   |
| 1920x1200 (WUXGA)  | 1         | 0.33%   |
| 1680x945           | 1         | 0.33%   |
| 1680x1050 (WSXGA+) | 1         | 0.33%   |
| 1024x600           | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 131       | 42.81%  |
| 13      | 59        | 19.28%  |
| 14      | 30        | 9.8%    |
| 17      | 22        | 7.19%   |
| Unknown | 10        | 3.27%   |
| 24      | 8         | 2.61%   |
| 11      | 8         | 2.61%   |
| 27      | 7         | 2.29%   |
| 12      | 5         | 1.63%   |
| 18      | 4         | 1.31%   |
| 23      | 3         | 0.98%   |
| 21      | 3         | 0.98%   |
| 20      | 2         | 0.65%   |
| 10      | 2         | 0.65%   |
| 84      | 1         | 0.33%   |
| 74      | 1         | 0.33%   |
| 64      | 1         | 0.33%   |
| 52      | 1         | 0.33%   |
| 49      | 1         | 0.33%   |
| 48      | 1         | 0.33%   |
| 46      | 1         | 0.33%   |
| 37      | 1         | 0.33%   |
| 34      | 1         | 0.33%   |
| 25      | 1         | 0.33%   |
| 19      | 1         | 0.33%   |
| 16      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 186       | 60.78%  |
| 201-300     | 44        | 14.38%  |
| 351-400     | 28        | 9.15%   |
| 501-600     | 18        | 5.88%   |
| 401-500     | 10        | 3.27%   |
| Unknown     | 10        | 3.27%   |
| 1001-1500   | 5         | 1.63%   |
| 1501-2000   | 2         | 0.65%   |
| 801-900     | 1         | 0.33%   |
| 701-800     | 1         | 0.33%   |
| 601-700     | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 244       | 87.14%  |
| 16/10   | 24        | 8.57%   |
| Unknown | 8         | 2.86%   |
| 3/2     | 2         | 0.71%   |
| 3.73    | 1         | 0.36%   |
| 21/9    | 1         | 0.36%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 132       | 43%     |
| 81-90          | 68        | 22.15%  |
| 71-80          | 21        | 6.84%   |
| 121-130        | 20        | 6.51%   |
| 201-250        | 13        | 4.23%   |
| Unknown        | 10        | 3.26%   |
| 51-60          | 8         | 2.61%   |
| 301-350        | 7         | 2.28%   |
| More than 1000 | 6         | 1.95%   |
| 61-70          | 5         | 1.63%   |
| 151-200        | 5         | 1.63%   |
| 141-150        | 3         | 0.98%   |
| 41-50          | 2         | 0.65%   |
| 131-140        | 2         | 0.65%   |
| 501-1000       | 2         | 0.65%   |
| 351-500        | 1         | 0.33%   |
| 251-300        | 1         | 0.33%   |
| 91-100         | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 131       | 43.38%  |
| 121-160       | 96        | 31.79%  |
| 51-100        | 35        | 11.59%  |
| 161-240       | 16        | 5.3%    |
| Unknown       | 10        | 3.31%   |
| More than 240 | 9         | 2.98%   |
| 1-50          | 5         | 1.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 249       | 86.16%  |
| 2     | 35        | 12.11%  |
| 0     | 4         | 1.38%   |
| 3     | 1         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 156       | 33.69%  |
| Intel                             | 138       | 29.81%  |
| Qualcomm Atheros                  | 71        | 15.33%  |
| Broadcom                          | 35        | 7.56%   |
| Broadcom Limited                  | 14        | 3.02%   |
| Ralink                            | 5         | 1.08%   |
| Dell                              | 5         | 1.08%   |
| ASIX Electronics                  | 5         | 1.08%   |
| DisplayLink                       | 4         | 0.86%   |
| Marvell Technology Group          | 3         | 0.65%   |
| Huawei Technologies               | 3         | 0.65%   |
| Xiaomi                            | 2         | 0.43%   |
| T & A Mobile Phones               | 2         | 0.43%   |
| Qualcomm                          | 2         | 0.43%   |
| MediaTek                          | 2         | 0.43%   |
| ZyXEL Communications              | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.22%   |
| Sierra Wireless                   | 1         | 0.22%   |
| Samsung Electronics               | 1         | 0.22%   |
| OPPO Electronics                  | 1         | 0.22%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.22%   |
| Nvidia                            | 1         | 0.22%   |
| Novatel Wireless                  | 1         | 0.22%   |
| NetGear                           | 1         | 0.22%   |
| Motorola PCS                      | 1         | 0.22%   |
| Motorola BCS                      | 1         | 0.22%   |
| Linksys                           | 1         | 0.22%   |
| ICS Advent                        | 1         | 0.22%   |
| Exar                              | 1         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.22%   |
| D-Link System                     | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 16.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 5.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 19        | 3.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 2.35%   |
| Intel Wireless 7260                                               | 11        | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.81%   |
| Intel Wireless 8260                                               | 10        | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 1.63%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.45%   |
| Intel Wireless 7265                                               | 7         | 1.27%   |
| Intel Wireless 3165                                               | 7         | 1.27%   |
| Intel WiFi Link 5100                                              | 7         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.08%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.08%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.9%    |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.9%    |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.72%   |
| Intel Wireless 3160                                               | 4         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.72%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.72%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.54%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.54%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.54%   |
| Dell DW5550                                                       | 3         | 0.54%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 3         | 0.54%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.36%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 2         | 0.36%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.36%   |
| Realtek 802.11ac NIC                                              | 2         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 128       | 44.44%  |
| Qualcomm Atheros      | 62        | 21.53%  |
| Realtek Semiconductor | 50        | 17.36%  |
| Broadcom              | 24        | 8.33%   |
| Broadcom Limited      | 10        | 3.47%   |
| Ralink                | 5         | 1.74%   |
| Dell                  | 2         | 0.69%   |
| ZyXEL Communications  | 1         | 0.35%   |
| Sierra Wireless       | 1         | 0.35%   |
| Qualcomm              | 1         | 0.35%   |
| NetGear               | 1         | 0.35%   |
| MEDIATEK              | 1         | 0.35%   |
| Linksys               | 1         | 0.35%   |
| D-Link System         | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 19        | 6.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 4.48%   |
| Intel Wireless 7260                                            | 11        | 3.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.45%   |
| Intel Wireless 8260                                            | 10        | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 3.1%    |
| Intel Wireless 8265 / 8275                                     | 9         | 3.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 2.76%   |
| Intel Wireless 7265                                            | 7         | 2.41%   |
| Intel Wireless 3165                                            | 7         | 2.41%   |
| Intel WiFi Link 5100                                           | 7         | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.07%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.07%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 2.07%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.72%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.72%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.38%   |
| Intel Wireless 3160                                            | 4         | 1.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.38%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 1.38%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.38%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.03%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 1.03%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 2         | 0.69%   |
| Realtek 802.11ac NIC                                           | 2         | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 0.69%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.69%   |
| Dell Hub of E-Port Replicator                                  | 2         | 0.69%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 0.69%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 2         | 0.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 0.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 0.69%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 0.69%   |
| ZyXEL NWD-270N Wireless N-lite USB Adapter                     | 1         | 0.34%   |
| Sierra Wireless EM7455                                         | 1         | 0.34%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.34%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.34%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.34%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.34%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.34%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.34%   |
| Realtek RTL8187SE Wireless LAN Controller                      | 1         | 0.34%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 139       | 54.72%  |
| Intel                            | 50        | 19.69%  |
| Qualcomm Atheros                 | 18        | 7.09%   |
| Broadcom                         | 14        | 5.51%   |
| Broadcom Limited                 | 5         | 1.97%   |
| ASIX Electronics                 | 5         | 1.97%   |
| DisplayLink                      | 4         | 1.57%   |
| Marvell Technology Group         | 3         | 1.18%   |
| Huawei Technologies              | 3         | 1.18%   |
| Xiaomi                           | 2         | 0.79%   |
| Silicon Integrated Systems [SiS] | 1         | 0.39%   |
| Samsung Electronics              | 1         | 0.39%   |
| Qualcomm                         | 1         | 0.39%   |
| OPPO Electronics                 | 1         | 0.39%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.39%   |
| Nvidia                           | 1         | 0.39%   |
| Novatel Wireless                 | 1         | 0.39%   |
| Motorola PCS                     | 1         | 0.39%   |
| Motorola BCS                     | 1         | 0.39%   |
| MediaTek                         | 1         | 0.39%   |
| ICS Advent                       | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 36.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 6.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.52%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 2.34%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 1.95%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.56%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.17%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.17%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.17%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.17%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.78%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.78%   |
| Intel Ethernet controller                                         | 2         | 0.78%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.78%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.78%   |
| Huawei E353/E3131                                                 | 2         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.39%   |
| Qualcomm SDM660-MTP _SN:8F667B4D                                  | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.39%   |
| OPPO SDM712-MTP _SN:E0B69F21                                      | 1         | 0.39%   |
| OnePlus (Shenzhen) AC2003                                         | 1         | 0.39%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.39%   |
| Novatel Wireless MiFi 7730L                                       | 1         | 0.39%   |
| Motorola PCS moto g(7)                                            | 1         | 0.39%   |
| Motorola BCS SurfBoard SB5101 Cable Modem                         | 1         | 0.39%   |
| MediaTek moto g(8) power lite                                     | 1         | 0.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.39%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.39%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.39%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.39%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.39%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.39%   |
| Huawei BLA-L29                                                    | 1         | 0.39%   |
| DisplayLink USB-C Hybrid UHD Video Dock                           | 1         | 0.39%   |
| DisplayLink dynadock U3.0                                         | 1         | 0.39%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.39%   |
| DisplayLink Dell 4-in-1 Adapter                                   | 1         | 0.39%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.39%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 278       | 53.05%  |
| Ethernet | 239       | 45.61%  |
| Modem    | 5         | 0.95%   |
| Unknown  | 2         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 264       | 55.35%  |
| Ethernet | 212       | 44.44%  |
| Unknown  | 1         | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 214       | 74.56%  |
| 1     | 62        | 21.6%   |
| 0     | 8         | 2.79%   |
| 3     | 3         | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 201       | 69.55%  |
| Yes  | 88        | 30.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 40.89%  |
| Qualcomm Atheros Communications | 28        | 12.44%  |
| Realtek Semiconductor           | 27        | 12%     |
| Broadcom                        | 12        | 5.33%   |
| Lite-On Technology              | 11        | 4.89%   |
| Foxconn / Hon Hai               | 11        | 4.89%   |
| IMC Networks                    | 10        | 4.44%   |
| Apple                           | 8         | 3.56%   |
| Dell                            | 5         | 2.22%   |
| Toshiba                         | 4         | 1.78%   |
| Ralink                          | 4         | 1.78%   |
| Cambridge Silicon Radio         | 4         | 1.78%   |
| Hewlett-Packard                 | 2         | 0.89%   |
| Foxconn International           | 2         | 0.89%   |
| MediaTek                        | 1         | 0.44%   |
| Integrated System Solution      | 1         | 0.44%   |
| ASUSTek Computer                | 1         | 0.44%   |
| Askey Computer                  | 1         | 0.44%   |
| Alps Electric                   | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 31        | 13.78%  |
| Intel Bluetooth Device                                                              | 27        | 12%     |
| Realtek Bluetooth Radio                                                             | 16        | 7.11%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 6.22%   |
| Intel AX201 Bluetooth                                                               | 14        | 6.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 4.89%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 3.11%   |
| Intel AX200 Bluetooth                                                               | 6         | 2.67%   |
| Lite-On Bluetooth Device                                                            | 5         | 2.22%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 5         | 2.22%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 2.22%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 1.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.78%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.78%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.78%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.78%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 1.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 1.78%   |
| Apple Bluetooth Host Controller                                                     | 4         | 1.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 1.33%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.33%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.89%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.89%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.89%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.89%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.89%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.89%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.89%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.89%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.44%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.44%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.44%   |
| Toshiba Askey for                                                                   | 1         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.44%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.44%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.44%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.44%   |
| MediaTek MT7630e Bluetooth Adapter                                                  | 1         | 0.44%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.44%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.44%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.44%   |
| IMC Networks Bluetooth                                                              | 1         | 0.44%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.44%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.44%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.44%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.44%   |
| Broadcom Bluetooth                                                                  | 1         | 0.44%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.44%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.44%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.44%   |
| Askey Bluetooth Device                                                              | 1         | 0.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.44%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.44%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 227       | 67.56%  |
| AMD                              | 58        | 17.26%  |
| Nvidia                           | 43        | 12.8%   |
| Tenx Technology                  | 1         | 0.3%    |
| SteelSeries ApS                  | 1         | 0.3%    |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |
| Sennheiser Communications        | 1         | 0.3%    |
| Realtek Semiconductor            | 1         | 0.3%    |
| Razer USA                        | 1         | 0.3%    |
| Creative Technology              | 1         | 0.3%    |
| Corsair                          | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 9.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 6.95%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 24        | 5.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 5.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 5.28%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 5.28%   |
| AMD FCH Azalia Controller                                                                         | 18        | 4.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 4.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 3.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 2.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.16%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 2.16%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.92%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 1.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.44%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.2%    |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.2%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 0.96%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.72%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.48%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.48%   |
| Nvidia Audio device                                                                               | 2         | 0.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.48%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.48%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.48%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 0.48%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.24%   |
| SteelSeries ApS SteelSeries GameDAC                                                               | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.24%   |
| Sennheiser Communications EPOS GSA 70                                                             | 1         | 0.24%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 1         | 0.24%   |
| Razer USA Nari Ultimate                                                                           | 1         | 0.24%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.24%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.24%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.24%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.24%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 29.51%  |
| SK Hynix            | 13        | 21.31%  |
| Micron Technology   | 12        | 19.67%  |
| A-DATA Technology   | 5         | 8.2%    |
| Unknown             | 4         | 6.56%   |
| Kingston            | 3         | 4.92%   |
| Ramaxel Technology  | 2         | 3.28%   |
| Unknown (ABCD)      | 1         | 1.64%   |
| Strontium           | 1         | 1.64%   |
| Nanya Technology    | 1         | 1.64%   |
| Crucial             | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 4.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 4.55%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 2         | 3.03%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 2         | 3.03%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s              | 2         | 3.03%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                           | 1         | 1.52%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 1         | 1.52%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM DDR3 2400MT/s   | 1         | 1.52%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s                | 1         | 1.52%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.52%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1024MB SODIMM DDR3 1067MT/s           | 1         | 1.52%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.52%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 1.52%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.52%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 8192MB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.52%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 1.52%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.52%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 1.52%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 1.52%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 1.52%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s               | 1         | 1.52%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s            | 1         | 1.52%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.52%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.52%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s            | 1         | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 1.52%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.52%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s            | 1         | 1.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.52%   |
| Ramaxel RAM RMSA3270MB86H9F2400 4096MB SODIMM DDR4 2400MT/s         | 1         | 1.52%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.52%   |
| Nanya RAM NT1GT64U8HB0BN-3C 1024MB SODIMM DDR 667MT/s               | 1         | 1.52%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s   | 1         | 1.52%   |
| Micron RAM Module 2GB SODIMM DDR2 800MT/s                           | 1         | 1.52%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                         | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 1         | 1.52%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.52%   |
| Micron RAM 16KTF51264HZ-1G4M1 4096MB SODIMM DDR3 1333MT/s           | 1         | 1.52%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM 1334MT/s                | 1         | 1.52%   |
| Kingston RAM K821PJ-MID 16384MB SODIMM DDR4 2400MT/s                | 1         | 1.52%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s              | 1         | 1.52%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2667MT/s                       | 1         | 1.52%   |
| A-DATA RAM DOVF1B163BE 2048MB SODIMM DDR 800MT/s                    | 1         | 1.52%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4096MB SODIMM DDR4 2400MT/s             | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 28        | 51.85%  |
| DDR3   | 14        | 25.93%  |
| LPDDR4 | 4         | 7.41%   |
| LPDDR3 | 3         | 5.56%   |
| DDR2   | 3         | 5.56%   |
| SDRAM  | 2         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 86.79%  |
| Row Of Chips | 6         | 11.32%  |
| Chip         | 1         | 1.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 42.37%  |
| 8192  | 21        | 35.59%  |
| 2048  | 8         | 13.56%  |
| 16384 | 3         | 5.08%   |
| 1024  | 2         | 3.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 12        | 20.34%  |
| 1600  | 12        | 20.34%  |
| 3200  | 8         | 13.56%  |
| 2400  | 6         | 10.17%  |
| 3266  | 3         | 5.08%   |
| 2133  | 3         | 5.08%   |
| 1334  | 3         | 5.08%   |
| 4267  | 2         | 3.39%   |
| 4199  | 2         | 3.39%   |
| 1333  | 2         | 3.39%   |
| 800   | 2         | 3.39%   |
| 667   | 2         | 3.39%   |
| 1867  | 1         | 1.69%   |
| 1067  | 1         | 1.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3110 Series | 1         | 100%    |

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
| Chicony Electronics                    | 56        | 22.49%  |
| Realtek Semiconductor                  | 30        | 12.05%  |
| IMC Networks                           | 24        | 9.64%   |
| Sunplus Innovation Technology          | 18        | 7.23%   |
| Acer                                   | 17        | 6.83%   |
| Microdia                               | 16        | 6.43%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 5.22%   |
| Quanta                                 | 12        | 4.82%   |
| Suyin                                  | 11        | 4.42%   |
| Syntek                                 | 9         | 3.61%   |
| Lite-On Technology                     | 7         | 2.81%   |
| Ricoh                                  | 4         | 1.61%   |
| Apple                                  | 4         | 1.61%   |
| Silicon Motion                         | 3         | 1.2%    |
| Luxvisions Innotech Limited            | 3         | 1.2%    |
| Sunplus Technology                     | 2         | 0.8%    |
| Samsung Electronics                    | 2         | 0.8%    |
| Primax Electronics                     | 2         | 0.8%    |
| Alcor Micro                            | 2         | 0.8%    |
| YGTek                                  | 1         | 0.4%    |
| Y Media                                | 1         | 0.4%    |
| OmniVision Technologies                | 1         | 0.4%    |
| Logitech                               | 1         | 0.4%    |
| LG Electronics                         | 1         | 0.4%    |
| KYE Systems (Mouse Systems)            | 1         | 0.4%    |
| Importek                               | 1         | 0.4%    |
| icSpring                               | 1         | 0.4%    |
| Huawei Technologies                    | 1         | 0.4%    |
| Genesys Logic                          | 1         | 0.4%    |
| Generalplus Technology                 | 1         | 0.4%    |
| GEMBIRD                                | 1         | 0.4%    |
| DJKANA1RSF34LM                         | 1         | 0.4%    |
| ALi                                    | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 9         | 3.61%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 7         | 2.81%   |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 2.81%   |
| Chicony HD Webcam                                   | 7         | 2.81%   |
| Microdia Integrated_Webcam_HD                       | 6         | 2.41%   |
| Syntek Integrated Camera                            | 5         | 2.01%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 2.01%   |
| IMC Networks Integrated Camera                      | 5         | 2.01%   |
| Chicony Integrated Camera                           | 5         | 2.01%   |
| Acer Integrated Camera                              | 5         | 2.01%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.61%   |
| Realtek Integrated Webcam                           | 4         | 1.61%   |
| Microdia Integrated Webcam                          | 4         | 1.61%   |
| Chicony VGA Webcam                                  | 4         | 1.61%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 4         | 1.61%   |
| Chicony HP TrueVision HD                            | 4         | 1.61%   |
| Syntek Lenovo EasyCamera                            | 3         | 1.2%    |
| Suyin Laptop_Integrated_Webcam_HD                   | 3         | 1.2%    |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 1.2%    |
| Realtek USB Camera                                  | 3         | 1.2%    |
| Quanta HP Wide Vision HD Camera                     | 3         | 1.2%    |
| Chicony HD User Facing                              | 3         | 1.2%    |
| Chicony EasyCamera                                  | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 3         | 1.2%    |
| Acer Lenovo EasyCamera                              | 3         | 1.2%    |
| Suyin HP Truevision HD                              | 2         | 0.8%    |
| Sunplus HD WebCam                                   | 2         | 0.8%    |
| Samsung Galaxy A5 (MTP)                             | 2         | 0.8%    |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 2         | 0.8%    |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 0.8%    |
| Realtek Lenovo EasyCamera                           | 2         | 0.8%    |
| Realtek Integrated Webcam HD                        | 2         | 0.8%    |
| Quanta VGA WebCam                                   | 2         | 0.8%    |
| Quanta HP TrueVision HD Camera                      | 2         | 0.8%    |
| Quanta HD WebCam                                    | 2         | 0.8%    |
| Quanta HD User Facing                               | 2         | 0.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.8%    |
| Lite-On HP HD Camera                                | 2         | 0.8%    |
| IMC Networks USB Camera                             | 2         | 0.8%    |
| IMC Networks 2M Integrated Webcam                   | 2         | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.8%    |
| Chicony USB 2.0 Camera                              | 2         | 0.8%    |
| Chicony HP Wide Vision HD Camera                    | 2         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 0.8%    |
| Apple FaceTime HD Camera                            | 2         | 0.8%    |
| Acer Lenovo Integrated Webcam                       | 2         | 0.8%    |
| Acer Lenovo EasyCamera integrated webcam            | 2         | 0.8%    |
| Acer HD Webcam                                      | 2         | 0.8%    |
| YGTek webcam                                        | 1         | 0.4%    |
| Y Media USB Camera                                  | 1         | 0.4%    |
| Syntek USB Camera Device                            | 1         | 0.4%    |
| Suyin WebCam                                        | 1         | 0.4%    |
| Suyin HD Video WebCam                               | 1         | 0.4%    |
| Suyin 1.3M HD WebCam                                | 1         | 0.4%    |
| Sunplus General Image Devic                         | 1         | 0.4%    |
| Sunplus 1.3M HD WebCam                              | 1         | 0.4%    |
| Sunplus MTD Camera                                  | 1         | 0.4%    |
| Sunplus Lenovo EasyCamera                           | 1         | 0.4%    |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.4%    |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 21        | 48.84%  |
| Upek                       | 8         | 18.6%   |
| Shenzhen Goodix Technology | 5         | 11.63%  |
| AuthenTec                  | 3         | 6.98%   |
| Synaptics                  | 2         | 4.65%   |
| LighTuning Technology      | 2         | 4.65%   |
| STMicroelectronics         | 1         | 2.33%   |
| Focal-systems.Corp         | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 16.28%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 11.63%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 6.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 4.65%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 4.65%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 4.65%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 4.65%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 4.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.33%   |
| Validity Sensors VFS491                                                    | 1         | 2.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.33%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 2.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.33%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 2.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.33%   |
| LighTuning Fingerprint Reader                                              | 1         | 2.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.33%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.33%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.33%   |
| AuthenTec AES1600                                                          | 1         | 2.33%   |
| Unknown                                                                    | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 15        | 65.22%  |
| Alcor Micro | 3         | 13.04%  |
| O2 Micro    | 2         | 8.7%    |
| Lenovo      | 2         | 8.7%    |
| Yubico.com  | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 26.09%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 21.74%  |
| Broadcom 5880                                                                | 3         | 13.04%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 13.04%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8.7%    |
| Lenovo Integrated Smart Card Reader                                          | 2         | 8.7%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 186       | 63.92%  |
| 1     | 79        | 27.15%  |
| 2     | 24        | 8.25%   |
| 3     | 2         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 43        | 33.08%  |
| Graphics card         | 22        | 16.92%  |
| Chipcard              | 20        | 15.38%  |
| Net/wireless          | 16        | 12.31%  |
| Multimedia controller | 14        | 10.77%  |
| Bluetooth             | 6         | 4.62%   |
| Storage               | 5         | 3.85%   |
| Sound                 | 1         | 0.77%   |
| Net/ethernet          | 1         | 0.77%   |
| Flash memory          | 1         | 0.77%   |
| Dvb card              | 1         | 0.77%   |

