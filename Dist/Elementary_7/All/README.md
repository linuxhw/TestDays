Elementary 7 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Elementary 7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_7/Desktop/README.md) and [notebooks](/Dist/Elementary_7/Notebook/README.md).

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

Total: 168

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 1998                        | Desktop     | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [97acececd3](https://linux-hardware.org/?probe=97acececd3) | Apr 28, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [c188ae4d7d](https://linux-hardware.org/?probe=c188ae4d7d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [2a9fcae8c3](https://linux-hardware.org/?probe=2a9fcae8c3) | Apr 28, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [87c8761eff](https://linux-hardware.org/?probe=87c8761eff) | Apr 27, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [53dd8334ac](https://linux-hardware.org/?probe=53dd8334ac) | Apr 26, 2023 |
| HP            | 8055                        | Desktop     | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| ASRock        | B660M-C                     | Desktop     | [849fc5d462](https://linux-hardware.org/?probe=849fc5d462) | Apr 25, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [8fd18554d1](https://linux-hardware.org/?probe=8fd18554d1) | Apr 24, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | Desktop     | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| Dell          | Latitude E4300              | Notebook    | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [763953fb60](https://linux-hardware.org/?probe=763953fb60) | Apr 22, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [50a18b5e94](https://linux-hardware.org/?probe=50a18b5e94) | Apr 19, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d60e2b7da](https://linux-hardware.org/?probe=4d60e2b7da) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [94bf014457](https://linux-hardware.org/?probe=94bf014457) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [2ebc6a2f61](https://linux-hardware.org/?probe=2ebc6a2f61) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ff6dbdcc10](https://linux-hardware.org/?probe=ff6dbdcc10) | Apr 15, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845e7bfdd1](https://linux-hardware.org/?probe=845e7bfdd1) | Apr 15, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [936a7d1fe3](https://linux-hardware.org/?probe=936a7d1fe3) | Apr 15, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4c6427b3fc](https://linux-hardware.org/?probe=4c6427b3fc) | Apr 14, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e311d21def](https://linux-hardware.org/?probe=e311d21def) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [c750ece414](https://linux-hardware.org/?probe=c750ece414) | Apr 12, 2023 |
| Dell          | Latitude E5570              | Notebook    | [81eaf54f19](https://linux-hardware.org/?probe=81eaf54f19) | Apr 07, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [5c12ed53b7](https://linux-hardware.org/?probe=5c12ed53b7) | Apr 05, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [6896e5d9e2](https://linux-hardware.org/?probe=6896e5d9e2) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [d3bd81c4fd](https://linux-hardware.org/?probe=d3bd81c4fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [f7f207f61c](https://linux-hardware.org/?probe=f7f207f61c) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e06d57c27a](https://linux-hardware.org/?probe=e06d57c27a) | Apr 01, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d4c718bdab](https://linux-hardware.org/?probe=d4c718bdab) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [448d1a491c](https://linux-hardware.org/?probe=448d1a491c) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| Dell          | Latitude E7440              | Notebook    | [1159c854cd](https://linux-hardware.org/?probe=1159c854cd) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a9a8004509](https://linux-hardware.org/?probe=a9a8004509) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1dccfbe9f4](https://linux-hardware.org/?probe=1dccfbe9f4) | Mar 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d714c46c4f](https://linux-hardware.org/?probe=d714c46c4f) | Mar 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [5590ec1365](https://linux-hardware.org/?probe=5590ec1365) | Mar 28, 2023 |
| AZW           | U59                         | Desktop     | [7674bb8dc9](https://linux-hardware.org/?probe=7674bb8dc9) | Mar 27, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [39995c1c00](https://linux-hardware.org/?probe=39995c1c00) | Mar 24, 2023 |
| Dell          | Latitude E7440              | Notebook    | [1a986dbeb8](https://linux-hardware.org/?probe=1a986dbeb8) | Mar 24, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [df318ed208](https://linux-hardware.org/?probe=df318ed208) | Mar 21, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Latitude E5570              | Notebook    | [a15d1b43ca](https://linux-hardware.org/?probe=a15d1b43ca) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dd07b0c3b3](https://linux-hardware.org/?probe=dd07b0c3b3) | Mar 17, 2023 |
| Dell          | G3 3590                     | Notebook    | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [03e5d43f27](https://linux-hardware.org/?probe=03e5d43f27) | Mar 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [4c49d73583](https://linux-hardware.org/?probe=4c49d73583) | Mar 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [c6ff6d14a0](https://linux-hardware.org/?probe=c6ff6d14a0) | Mar 15, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [28f8273eb5](https://linux-hardware.org/?probe=28f8273eb5) | Mar 15, 2023 |
| HP            | 805A                        | Desktop     | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | Notebook    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [023f42d6d1](https://linux-hardware.org/?probe=023f42d6d1) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK A359               | Notebook    | [0fa1ebbc11](https://linux-hardware.org/?probe=0fa1ebbc11) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK A359               | Notebook    | [f977012127](https://linux-hardware.org/?probe=f977012127) | Mar 11, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [fce6120754](https://linux-hardware.org/?probe=fce6120754) | Mar 11, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [a4ba2ff90e](https://linux-hardware.org/?probe=a4ba2ff90e) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | Notebook    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Sony          | VPCEH2C5E                   | Notebook    | [adf4a69310](https://linux-hardware.org/?probe=adf4a69310) | Mar 07, 2023 |
| Sony          | VPCEH2C5E                   | Notebook    | [9e5b625dda](https://linux-hardware.org/?probe=9e5b625dda) | Mar 07, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [3547dd712b](https://linux-hardware.org/?probe=3547dd712b) | Mar 07, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [4ecfeecd31](https://linux-hardware.org/?probe=4ecfeecd31) | Mar 06, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| Microsoft     | Surface Book                | Tablet      | [cc3ad3e0d2](https://linux-hardware.org/?probe=cc3ad3e0d2) | Mar 02, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d58385d1e6](https://linux-hardware.org/?probe=d58385d1e6) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [e189c60b09](https://linux-hardware.org/?probe=e189c60b09) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3883ba28c7](https://linux-hardware.org/?probe=3883ba28c7) | Mar 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1c5f8fef49](https://linux-hardware.org/?probe=1c5f8fef49) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [216ad20179](https://linux-hardware.org/?probe=216ad20179) | Feb 28, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [371a95fb3d](https://linux-hardware.org/?probe=371a95fb3d) | Feb 28, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [e331c5e257](https://linux-hardware.org/?probe=e331c5e257) | Feb 27, 2023 |
| Acer          | Predator G3620              | Desktop     | [72f3382b60](https://linux-hardware.org/?probe=72f3382b60) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [73c974942f](https://linux-hardware.org/?probe=73c974942f) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a66f75c107](https://linux-hardware.org/?probe=a66f75c107) | Feb 26, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [ce9dda227f](https://linux-hardware.org/?probe=ce9dda227f) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [b815c24c07](https://linux-hardware.org/?probe=b815c24c07) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [e578b951f9](https://linux-hardware.org/?probe=e578b951f9) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [0dc5add67b](https://linux-hardware.org/?probe=0dc5add67b) | Feb 24, 2023 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [b101883e65](https://linux-hardware.org/?probe=b101883e65) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [6db3a90234](https://linux-hardware.org/?probe=6db3a90234) | Feb 24, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [0a3d750f36](https://linux-hardware.org/?probe=0a3d750f36) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [7ee9e59831](https://linux-hardware.org/?probe=7ee9e59831) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [2751aac3e0](https://linux-hardware.org/?probe=2751aac3e0) | Feb 16, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [76ab936a75](https://linux-hardware.org/?probe=76ab936a75) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [e0f89bbca1](https://linux-hardware.org/?probe=e0f89bbca1) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| HP            | 550                         | Notebook    | [81b67f211d](https://linux-hardware.org/?probe=81b67f211d) | Feb 15, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [150c1de326](https://linux-hardware.org/?probe=150c1de326) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e8a460c42c](https://linux-hardware.org/?probe=e8a460c42c) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [a92df0196e](https://linux-hardware.org/?probe=a92df0196e) | Feb 15, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| HP            | 805D                        | Desktop     | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [f22c83d683](https://linux-hardware.org/?probe=f22c83d683) | Feb 14, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [12431d8083](https://linux-hardware.org/?probe=12431d8083) | Feb 14, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f0899499e5](https://linux-hardware.org/?probe=f0899499e5) | Feb 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [537d29b0d5](https://linux-hardware.org/?probe=537d29b0d5) | Feb 12, 2023 |
| Acer          | Extensa 5230                | Notebook    | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [b906f960a0](https://linux-hardware.org/?probe=b906f960a0) | Feb 08, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [1e6a345b00](https://linux-hardware.org/?probe=1e6a345b00) | Feb 07, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [c3607bb4c2](https://linux-hardware.org/?probe=c3607bb4c2) | Feb 07, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [07ea9d3c2f](https://linux-hardware.org/?probe=07ea9d3c2f) | Feb 06, 2023 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [30e2a88930](https://linux-hardware.org/?probe=30e2a88930) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | Notebook    | [10f8560601](https://linux-hardware.org/?probe=10f8560601) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | Notebook    | [be37cc70f5](https://linux-hardware.org/?probe=be37cc70f5) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [8d67e1438d](https://linux-hardware.org/?probe=8d67e1438d) | Feb 05, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8bdb86b164](https://linux-hardware.org/?probe=8bdb86b164) | Feb 04, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [3786e7a211](https://linux-hardware.org/?probe=3786e7a211) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [8aa57f1d6d](https://linux-hardware.org/?probe=8aa57f1d6d) | Feb 03, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [78919f6127](https://linux-hardware.org/?probe=78919f6127) | Feb 03, 2023 |
| Alienware     | x17 R2                      | Notebook    | [474a70c148](https://linux-hardware.org/?probe=474a70c148) | Feb 03, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [42c3899a37](https://linux-hardware.org/?probe=42c3899a37) | Feb 02, 2023 |
| Sony          | SVF1521O4E                  | Notebook    | [e2d47879d4](https://linux-hardware.org/?probe=e2d47879d4) | Feb 02, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [fdf7b5e80e](https://linux-hardware.org/?probe=fdf7b5e80e) | Feb 02, 2023 |
| Lenovo        | ThinkPad X230 23259S9       | Notebook    | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [1ce7db78c1](https://linux-hardware.org/?probe=1ce7db78c1) | Feb 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c2a4529e33](https://linux-hardware.org/?probe=c2a4529e33) | Jan 30, 2023 |
| Star Labs     | StarBook                    | Notebook    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Unknown       | HX90                        | Desktop     | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-58-generic      | 32        | 27.12%  |
| 5.19.0-35-generic      | 23        | 19.49%  |
| 5.19.0-32-generic      | 22        | 18.64%  |
| 5.19.0-38-generic      | 16        | 13.56%  |
| 5.15.0-60-generic      | 9         | 7.63%   |
| 5.19.0-40-generic      | 6         | 5.08%   |
| 5.19.0-41-generic      | 3         | 2.54%   |
| 5.15.0-56-generic      | 2         | 1.69%   |
| 6.2.8-3-liquorix-amd64 | 1         | 0.85%   |
| 6.2.7-060207-generic   | 1         | 0.85%   |
| 6.2.2-surface          | 1         | 0.85%   |
| 6.1.9-060109-generic   | 1         | 0.85%   |
| 6.1.6-060106-generic   | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 66        | 57.89%  |
| 5.15.0  | 43        | 37.72%  |
| 6.2.8   | 1         | 0.88%   |
| 6.2.7   | 1         | 0.88%   |
| 6.2.2   | 1         | 0.88%   |
| 6.1.9   | 1         | 0.88%   |
| 6.1.6   | 1         | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 66        | 57.89%  |
| 5.15    | 43        | 37.72%  |
| 6.2     | 3         | 2.63%   |
| 6.1     | 2         | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 113       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 113       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 113       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 95        | 84.07%  |
| LightDM | 18        | 15.93%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 46        | 40.71%  |
| de_DE | 18        | 15.93%  |
| es_ES | 8         | 7.08%   |
| ru_RU | 7         | 6.19%   |
| fr_FR | 5         | 4.42%   |
| en_GB | 4         | 3.54%   |
| pt_BR | 3         | 2.65%   |
| pl_PL | 3         | 2.65%   |
| it_IT | 3         | 2.65%   |
| sv_SE | 2         | 1.77%   |
| en_AU | 2         | 1.77%   |
| uk_UA | 1         | 0.88%   |
| sk_SK | 1         | 0.88%   |
| pt_PT | 1         | 0.88%   |
| nl_NL | 1         | 0.88%   |
| nb_NO | 1         | 0.88%   |
| ja_JP | 1         | 0.88%   |
| hu_HU | 1         | 0.88%   |
| fi_FI | 1         | 0.88%   |
| en_CA | 1         | 0.88%   |
| el_GR | 1         | 0.88%   |
| da_DK | 1         | 0.88%   |
| cs_CZ | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 99        | 87.61%  |
| EFI  | 14        | 12.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 108       | 94.74%  |
| Btrfs | 3         | 2.63%   |
| Xfs   | 2         | 1.75%   |
| Tmpfs | 1         | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 95        | 84.07%  |
| GPT     | 17        | 15.04%  |
| MBR     | 1         | 0.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 94.69%  |
| Yes       | 6         | 5.31%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 17        | 15.04%  |
| Apple               | 16        | 14.16%  |
| ASUSTek Computer    | 15        | 13.27%  |
| Lenovo              | 14        | 12.39%  |
| Dell                | 10        | 8.85%   |
| MSI                 | 8         | 7.08%   |
| Acer                | 6         | 5.31%   |
| Gigabyte Technology | 5         | 4.42%   |
| Fujitsu             | 3         | 2.65%   |
| Toshiba             | 2         | 1.77%   |
| Sony                | 2         | 1.77%   |
| HUAWEI              | 2         | 1.77%   |
| Foxconn             | 2         | 1.77%   |
| Unknown             | 2         | 1.77%   |
| Star Labs           | 1         | 0.88%   |
| Microsoft           | 1         | 0.88%   |
| MACHINIST           | 1         | 0.88%   |
| Inventec            | 1         | 0.88%   |
| HONOR               | 1         | 0.88%   |
| GPU Company         | 1         | 0.88%   |
| AZW                 | 1         | 0.88%   |
| ASRock              | 1         | 0.88%   |
| Alienware           | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP 255 G7 Notebook PC                    | 2         | 1.77%   |
| ASUS H110M-A/M.2                         | 2         | 1.77%   |
| Apple iMac12,1                           | 2         | 1.77%   |
| Unknown                                  | 2         | 1.77%   |
| Toshiba TECRA Z40-C                      | 1         | 0.88%   |
| Toshiba Satellite C660                   | 1         | 0.88%   |
| Star Labs StarBook                       | 1         | 0.88%   |
| Sony VPCEH2C5E                           | 1         | 0.88%   |
| Sony SVF1521O4E                          | 1         | 0.88%   |
| MSI PE70 6QE                             | 1         | 0.88%   |
| MSI MS-7C31                              | 1         | 0.88%   |
| MSI MS-7C02                              | 1         | 0.88%   |
| MSI MS-7B84                              | 1         | 0.88%   |
| MSI MS-7816                              | 1         | 0.88%   |
| MSI GT72 2QE                             | 1         | 0.88%   |
| MSI GE62VR 6RF                           | 1         | 0.88%   |
| MSI CX61 2PC                             | 1         | 0.88%   |
| Microsoft Surface Pro 7                  | 1         | 0.88%   |
| MACHINIST E5-MR9A PRO V1.1               | 1         | 0.88%   |
| Lenovo Yoga 6 13ALC7 82UD                | 1         | 0.88%   |
| Lenovo V14 G2 ITL 82KA                   | 1         | 0.88%   |
| Lenovo ThinkPad X240 20AMS0XP0S          | 1         | 0.88%   |
| Lenovo ThinkPad X230 23259S9             | 1         | 0.88%   |
| Lenovo ThinkPad X13 Gen 1 20T3S3SH0U     | 1         | 0.88%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW | 1         | 0.88%   |
| Lenovo ThinkPad T495 20NKS01W02          | 1         | 0.88%   |
| Lenovo ThinkPad T440p 20AWS38H0G         | 1         | 0.88%   |
| Lenovo ThinkPad T400s 2808D9G            | 1         | 0.88%   |
| Lenovo ThinkPad E560 20EV003DSP          | 1         | 0.88%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 0.88%   |
| Lenovo IdeaPad 320-15ABR 80XS            | 1         | 0.88%   |
| Lenovo H500s 10157                       | 1         | 0.88%   |
| Lenovo G580 20150                        | 1         | 0.88%   |
| Inventec Z CLASS                         | 1         | 0.88%   |
| HUAWEI NBD-WXX9                          | 1         | 0.88%   |
| HUAWEI BOD-WXX9                          | 1         | 0.88%   |
| HONOR HYM-WXX                            | 1         | 0.88%   |
| HP ProDesk 600 G2 SFF                    | 1         | 0.88%   |
| HP ProBook 450 15.6 inch G9 Notebook PC  | 1         | 0.88%   |
| HP Pavilion Laptop 15-eh0xxx             | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 8         | 7.08%   |
| Acer Aspire        | 5         | 4.42%   |
| HP Pavilion        | 4         | 3.54%   |
| Dell Latitude      | 4         | 3.54%   |
| ASUS ZenBook       | 4         | 3.54%   |
| Fujitsu LIFEBOOK   | 3         | 2.65%   |
| Dell XPS           | 3         | 2.65%   |
| HP Laptop          | 2         | 1.77%   |
| HP EliteDesk       | 2         | 1.77%   |
| HP 255             | 2         | 1.77%   |
| ASUS H110M-A       | 2         | 1.77%   |
| Apple MacBookPro5  | 2         | 1.77%   |
| Apple MacBookPro11 | 2         | 1.77%   |
| Apple MacBookAir3  | 2         | 1.77%   |
| Apple iMac12       | 2         | 1.77%   |
| Unknown            | 2         | 1.77%   |
| Toshiba TECRA      | 1         | 0.88%   |
| Toshiba Satellite  | 1         | 0.88%   |
| Star Labs StarBook | 1         | 0.88%   |
| Sony VPCEH2C5E     | 1         | 0.88%   |
| Sony SVF1521O4E    | 1         | 0.88%   |
| MSI PE70           | 1         | 0.88%   |
| MSI MS-7C31        | 1         | 0.88%   |
| MSI MS-7C02        | 1         | 0.88%   |
| MSI MS-7B84        | 1         | 0.88%   |
| MSI MS-7816        | 1         | 0.88%   |
| MSI GT72           | 1         | 0.88%   |
| MSI GE62VR         | 1         | 0.88%   |
| MSI CX61           | 1         | 0.88%   |
| Microsoft Surface  | 1         | 0.88%   |
| MACHINIST E5-MR9A  | 1         | 0.88%   |
| Lenovo Yoga        | 1         | 0.88%   |
| Lenovo V14         | 1         | 0.88%   |
| Lenovo Legion      | 1         | 0.88%   |
| Lenovo IdeaPad     | 1         | 0.88%   |
| Lenovo H500s       | 1         | 0.88%   |
| Lenovo G580        | 1         | 0.88%   |
| Inventec Z         | 1         | 0.88%   |
| HUAWEI NBD-WXX9    | 1         | 0.88%   |
| HUAWEI BOD-WXX9    | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 11        | 9.73%   |
| 2012 | 11        | 9.73%   |
| 2020 | 10        | 8.85%   |
| 2016 | 10        | 8.85%   |
| 2013 | 10        | 8.85%   |
| 2022 | 8         | 7.08%   |
| 2019 | 8         | 7.08%   |
| 2015 | 7         | 6.19%   |
| 2009 | 7         | 6.19%   |
| 2008 | 7         | 6.19%   |
| 2018 | 5         | 4.42%   |
| 2014 | 5         | 4.42%   |
| 2010 | 5         | 4.42%   |
| 2017 | 4         | 3.54%   |
| 2011 | 3         | 2.65%   |
| 2023 | 2         | 1.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 69        | 61.06%  |
| Desktop     | 33        | 29.2%   |
| All in one  | 6         | 5.31%   |
| Convertible | 3         | 2.65%   |
| Tablet      | 1         | 0.88%   |
| Mini pc     | 1         | 0.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 109       | 96.46%  |
| Enabled  | 4         | 3.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 99.12%  |
| Yes  | 1         | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 32        | 28.32%  |
| 8.01-16.0   | 24        | 21.24%  |
| 16.01-24.0  | 23        | 20.35%  |
| 3.01-4.0    | 20        | 17.7%   |
| 32.01-64.0  | 8         | 7.08%   |
| 64.01-256.0 | 3         | 2.65%   |
| 1.01-2.0    | 2         | 1.77%   |
| 2.01-3.0    | 1         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 51        | 43.97%  |
| 1.01-2.0  | 25        | 21.55%  |
| 3.01-4.0  | 19        | 16.38%  |
| 4.01-8.0  | 17        | 14.66%  |
| 8.01-16.0 | 3         | 2.59%   |
| 0.51-1.0  | 1         | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 75        | 65.79%  |
| 2      | 30        | 26.32%  |
| 3      | 4         | 3.51%   |
| 4      | 3         | 2.63%   |
| 5      | 2         | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 61.06%  |
| Yes       | 44        | 38.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 84.07%  |
| No        | 18        | 15.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 84.07%  |
| No        | 18        | 15.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 75.22%  |
| No        | 28        | 24.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 23        | 20.35%  |
| Germany      | 21        | 18.58%  |
| Russia       | 6         | 5.31%   |
| Spain        | 5         | 4.42%   |
| France       | 5         | 4.42%   |
| UK           | 4         | 3.54%   |
| Poland       | 4         | 3.54%   |
| Brazil       | 4         | 3.54%   |
| Netherlands  | 3         | 2.65%   |
| Italy        | 3         | 2.65%   |
| Australia    | 3         | 2.65%   |
| Thailand     | 2         | 1.77%   |
| Norway       | 2         | 1.77%   |
| Ireland      | 2         | 1.77%   |
| Greece       | 2         | 1.77%   |
| Czechia      | 2         | 1.77%   |
| Canada       | 2         | 1.77%   |
| Tunisia      | 1         | 0.88%   |
| Sweden       | 1         | 0.88%   |
| South Africa | 1         | 0.88%   |
| Slovakia     | 1         | 0.88%   |
| Puerto Rico  | 1         | 0.88%   |
| Portugal     | 1         | 0.88%   |
| Mexico       | 1         | 0.88%   |
| Kazakhstan   | 1         | 0.88%   |
| Japan        | 1         | 0.88%   |
| Israel       | 1         | 0.88%   |
| India        | 1         | 0.88%   |
| Hungary      | 1         | 0.88%   |
| Georgia      | 1         | 0.88%   |
| Finland      | 1         | 0.88%   |
| Denmark      | 1         | 0.88%   |
| Cyprus       | 1         | 0.88%   |
| China        | 1         | 0.88%   |
| Chile        | 1         | 0.88%   |
| Belgium      | 1         | 0.88%   |
| Albania      | 1         | 0.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Wilster            | 2         | 1.74%   |
| Warsaw             | 2         | 1.74%   |
| Stuttgart          | 2         | 1.74%   |
| Moscow             | 2         | 1.74%   |
| Melbourne          | 2         | 1.74%   |
| Madrid             | 2         | 1.74%   |
| Las Vegas          | 2         | 1.74%   |
| Hamm               | 2         | 1.74%   |
| Brampton           | 2         | 1.74%   |
| Berlin             | 2         | 1.74%   |
| Bangkok            | 2         | 1.74%   |
| Aubagne            | 2         | 1.74%   |
| Athens             | 2         | 1.74%   |
| Znojmo             | 1         | 0.87%   |
| Zhuantang          | 1         | 0.87%   |
| Wuppertal          | 1         | 0.87%   |
| West Monroe        | 1         | 0.87%   |
| Wellingborough     | 1         | 0.87%   |
| Wauconda           | 1         | 0.87%   |
| Vigo               | 1         | 0.87%   |
| Twickenham         | 1         | 0.87%   |
| Tunis              | 1         | 0.87%   |
| Tucson             | 1         | 0.87%   |
| Tuam               | 1         | 0.87%   |
| Tromsø            | 1         | 0.87%   |
| Tremblay-en-France | 1         | 0.87%   |
| Tower City         | 1         | 0.87%   |
| Tirana             | 1         | 0.87%   |
| The Hague          | 1         | 0.87%   |
| Tel Aviv           | 1         | 0.87%   |
| Tbilisi            | 1         | 0.87%   |
| Stockholm          | 1         | 0.87%   |
| Stará Ľubovňa   | 1         | 0.87%   |
| St Petersburg      | 1         | 0.87%   |
| Soborg             | 1         | 0.87%   |
| Sarasota           | 1         | 0.87%   |
| Sao Paulo          | 1         | 0.87%   |
| Santiago           | 1         | 0.87%   |
| San Marcos         | 1         | 0.87%   |
| Salzgitter         | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 18        | 18     | 11.32%  |
| Samsung Electronics         | 18        | 23     | 11.32%  |
| Seagate                     | 13        | 16     | 8.18%   |
| SanDisk                     | 11        | 12     | 6.92%   |
| Toshiba                     | 9         | 11     | 5.66%   |
| Kingston                    | 9         | 9      | 5.66%   |
| Crucial                     | 8         | 9      | 5.03%   |
| Apple                       | 6         | 6      | 3.77%   |
| Unknown                     | 5         | 5      | 3.14%   |
| SK hynix                    | 3         | 4      | 1.89%   |
| KIOXIA                      | 3         | 3      | 1.89%   |
| Intenso                     | 3         | 4      | 1.89%   |
| Hitachi                     | 3         | 3      | 1.89%   |
| China                       | 3         | 3      | 1.89%   |
| Team                        | 2         | 3      | 1.26%   |
| Silicon Motion              | 2         | 2      | 1.26%   |
| PNY                         | 2         | 2      | 1.26%   |
| Phison Electronics          | 2         | 2      | 1.26%   |
| Netac                       | 2         | 3      | 1.26%   |
| Micron/Crucial Technology   | 2         | 2      | 1.26%   |
| Micron Technology           | 2         | 2      | 1.26%   |
| Intel                       | 2         | 3      | 1.26%   |
| HGST                        | 2         | 2      | 1.26%   |
| Fujitsu                     | 2         | 2      | 1.26%   |
| Yeestor                     | 1         | 1      | 0.63%   |
| USB 3.0                     | 1         | 1      | 0.63%   |
| Union Memory                | 1         | 2      | 0.63%   |
| T-FORCE                     | 1         | 1      | 0.63%   |
| Star Drive                  | 1         | 1      | 0.63%   |
| SPCC                        | 1         | 1      | 0.63%   |
| Solid State Storage         | 1         | 1      | 0.63%   |
| SD                          | 1         | 1      | 0.63%   |
| Realtek Semiconductor       | 1         | 2      | 0.63%   |
| OWC                         | 1         | 1      | 0.63%   |
| NGFF                        | 1         | 1      | 0.63%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.63%   |
| LITEONIT                    | 1         | 1      | 0.63%   |
| LITEON                      | 1         | 1      | 0.63%   |
| Kingston Technology Company | 1         | 1      | 0.63%   |
| KingDian                    | 1         | 2      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 5         | 2.98%   |
| WDC WD10EZEX-60WN4A0 1TB                           | 4         | 2.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 2         | 1.19%   |
| Unknown MMC Card  7GB                              | 2         | 1.19%   |
| Unknown MMC Card  32GB                             | 2         | 1.19%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 1.19%   |
| Seagate ST9500325AS 500GB                          | 2         | 1.19%   |
| Seagate Expansion 4TB                              | 2         | 1.19%   |
| Samsung SSD 860 EVO 1TB                            | 2         | 1.19%   |
| Samsung SSD 850 EVO 250GB                          | 2         | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 1.19%   |
| Phison E12 NVMe Controller 512GB                   | 2         | 1.19%   |
| Intenso SSD SATAIII 256GB                          | 2         | 1.19%   |
| HGST HTS721010A9E630 1TB                           | 2         | 1.19%   |
| Crucial CT500MX500SSD1 500GB                       | 2         | 1.19%   |
| Crucial CT250MX500SSD1 250GB                       | 2         | 1.19%   |
| Yeestor 512GB                                      | 1         | 0.6%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 1         | 0.6%    |
| WDC WDS480G2G0C-00AJM0 480GB                       | 1         | 0.6%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1         | 0.6%    |
| WDC WDS100T2B0B-00YS70 1TB SSD                     | 1         | 0.6%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                     | 1         | 0.6%    |
| WDC WD5000AAKX-08U6AA0 500GB                       | 1         | 0.6%    |
| WDC WD2500JB-55GVA0 250GB                          | 1         | 0.6%    |
| WDC WD10SPCX-08S8TT0 1TB                           | 1         | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.6%    |
| WDC WD10EZEX-60ZF5A0 1TB                           | 1         | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB                           | 1         | 0.6%    |
| WDC WD10EZEX-00BBHA0 1TB                           | 1         | 0.6%    |
| USB 3.0 Device 250GB                               | 1         | 0.6%    |
| Unknown MMC Card  128GB                            | 1         | 0.6%    |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB            | 1         | 0.6%    |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD           | 1         | 0.6%    |
| Toshiba THNSNJ128GCSU 128GB SSD                    | 1         | 0.6%    |
| Toshiba THNSNJ128G8NU 128GB SSD                    | 1         | 0.6%    |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD            | 1         | 0.6%    |
| Toshiba NVMe Controller 512GB                      | 1         | 0.6%    |
| Toshiba MQ01ABF050 500GB                           | 1         | 0.6%    |
| Toshiba DT01ACA100 1TB                             | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 30.56%  |
| Seagate             | 11        | 12     | 30.56%  |
| Toshiba             | 4         | 4      | 11.11%  |
| Hitachi             | 3         | 3      | 8.33%   |
| HGST                | 2         | 2      | 5.56%   |
| Fujitsu             | 2         | 2      | 5.56%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| JMicron Technology  | 1         | 1      | 2.78%   |
| ASMT                | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 14     | 15.28%  |
| Kingston            | 9         | 9      | 12.5%   |
| Crucial             | 8         | 9      | 11.11%  |
| WDC                 | 6         | 6      | 8.33%   |
| SanDisk             | 6         | 6      | 8.33%   |
| Apple               | 5         | 5      | 6.94%   |
| Toshiba             | 4         | 6      | 5.56%   |
| China               | 3         | 3      | 4.17%   |
| Team                | 2         | 3      | 2.78%   |
| Seagate             | 2         | 2      | 2.78%   |
| PNY                 | 2         | 2      | 2.78%   |
| Intenso             | 2         | 3      | 2.78%   |
| SPCC                | 1         | 1      | 1.39%   |
| OWC                 | 1         | 1      | 1.39%   |
| NGFF                | 1         | 1      | 1.39%   |
| Netac               | 1         | 1      | 1.39%   |
| LITEONIT            | 1         | 1      | 1.39%   |
| LITEON              | 1         | 1      | 1.39%   |
| KingDian            | 1         | 2      | 1.39%   |
| Inland              | 1         | 1      | 1.39%   |
| HS-SSD-E100         | 1         | 1      | 1.39%   |
| Corsair             | 1         | 1      | 1.39%   |
| Apacer              | 1         | 1      | 1.39%   |
| A-DATA Technology   | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 66        | 81     | 44.59%  |
| NVMe    | 36        | 44     | 24.32%  |
| HDD     | 29        | 37     | 19.59%  |
| Unknown | 12        | 13     | 8.11%   |
| MMC     | 5         | 5      | 3.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85        | 120    | 62.5%   |
| NVMe | 36        | 44     | 26.47%  |
| SAS  | 10        | 11     | 7.35%   |
| MMC  | 5         | 5      | 3.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 75     | 63.27%  |
| 0.51-1.0   | 25        | 32     | 25.51%  |
| 1.01-2.0   | 8         | 8      | 8.16%   |
| 3.01-4.0   | 3         | 3      | 3.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 43.86%  |
| 251-500        | 28        | 24.56%  |
| 501-1000       | 22        | 19.3%   |
| 51-100         | 9         | 7.89%   |
| 2001-3000      | 2         | 1.75%   |
| More than 3000 | 1         | 0.88%   |
| 21-50          | 1         | 0.88%   |
| 1001-2000      | 1         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 55        | 47.83%  |
| 21-50          | 26        | 22.61%  |
| 101-250        | 16        | 13.91%  |
| 51-100         | 14        | 12.17%  |
| 1001-2000      | 2         | 1.74%   |
| More than 3000 | 1         | 0.87%   |
| 251-500        | 1         | 0.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 103       | 166    | 88.03%  |
| Works    | 13        | 13     | 11.11%  |
| Malfunc  | 1         | 1      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 74        | 53.62%  |
| AMD                            | 17        | 12.32%  |
| Samsung Electronics            | 10        | 7.25%   |
| SanDisk                        | 6         | 4.35%   |
| Nvidia                         | 5         | 3.62%   |
| SK hynix                       | 3         | 2.17%   |
| Phison Electronics             | 3         | 2.17%   |
| KIOXIA                         | 3         | 2.17%   |
| Silicon Motion                 | 2         | 1.45%   |
| Micron/Crucial Technology      | 2         | 1.45%   |
| Micron Technology              | 2         | 1.45%   |
| Marvell Technology Group       | 2         | 1.45%   |
| ASMedia Technology             | 2         | 1.45%   |
| Union Memory (Shenzhen)        | 1         | 0.72%   |
| Toshiba America Info Systems   | 1         | 0.72%   |
| Solid State Storage Technology | 1         | 0.72%   |
| Realtek Semiconductor          | 1         | 0.72%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.72%   |
| Kingston Technology Company    | 1         | 0.72%   |
| Biwin Storage Technology       | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 8.44%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 4.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 3.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 3.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 3.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 2.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 2.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 2.6%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 1.95%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.95%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 1.95%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.95%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.3%    |
| Samsung Apple PCIe SSD                                                         | 2         | 1.3%    |
| Phison E12 NVMe Controller                                                     | 2         | 1.3%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 1.3%    |
| Micron NVMe Storage Controller                                                 | 2         | 1.3%    |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.3%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 1.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.3%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.65%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.65%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 88        | 61.54%  |
| NVMe | 36        | 25.17%  |
| RAID | 12        | 8.39%   |
| IDE  | 7         | 4.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 90        | 79.65%  |
| AMD    | 23        | 20.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i9-9900K CPU @ 3.60GHz        | 2         | 1.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 2         | 1.77%   |
| Intel Core i3-3120M CPU @ 2.50GHz        | 2         | 1.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 2         | 1.77%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz  | 2         | 1.77%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz      | 1         | 0.88%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 0.88%   |
| Intel Pentium CPU P6200 @ 2.13GHz        | 1         | 0.88%   |
| Intel Pentium CPU J2900 @ 2.41GHz        | 1         | 0.88%   |
| Intel Pentium CPU G2020 @ 2.90GHz        | 1         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 1         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 1         | 0.88%   |
| Intel Core i7-7700 CPU @ 3.60GHz         | 1         | 0.88%   |
| Intel Core i7-6700T CPU @ 2.80GHz        | 1         | 0.88%   |
| Intel Core i7-6700K CPU @ 4.00GHz        | 1         | 0.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 1         | 0.88%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 1         | 0.88%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz       | 1         | 0.88%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz       | 1         | 0.88%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz       | 1         | 0.88%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 1         | 0.88%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 0.88%   |
| Intel Core i7-4510U CPU @ 2.00GHz        | 1         | 0.88%   |
| Intel Core i7-3770S CPU @ 3.10GHz        | 1         | 0.88%   |
| Intel Core i7-3770K CPU @ 3.50GHz        | 1         | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 1         | 0.88%   |
| Intel Core i7-3720QM CPU @ 2.60GHz       | 1         | 0.88%   |
| Intel Core i7-2720QM CPU @ 2.20GHz       | 1         | 0.88%   |
| Intel Core i7-2600S CPU @ 2.80GHz        | 1         | 0.88%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 1         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 0.88%   |
| Intel Core i5-8300H CPU @ 2.30GHz        | 1         | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 0.88%   |
| Intel Core i5-7500T CPU @ 2.70GHz        | 1         | 0.88%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz       | 1         | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 0.88%   |
| Intel Core i5-6600 CPU @ 3.30GHz         | 1         | 0.88%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 1         | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 0.88%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 23        | 20.35%  |
| Intel Core i5        | 23        | 20.35%  |
| Other                | 14        | 12.39%  |
| Intel Core 2 Duo     | 12        | 10.62%  |
| Intel Core i3        | 7         | 6.19%   |
| Intel Celeron        | 5         | 4.42%   |
| AMD Ryzen 7          | 5         | 4.42%   |
| AMD Ryzen 5          | 4         | 3.54%   |
| Intel Pentium        | 3         | 2.65%   |
| Intel Core i9        | 2         | 1.77%   |
| AMD Ryzen 5 PRO      | 2         | 1.77%   |
| AMD Athlon           | 2         | 1.77%   |
| Intel Xeon           | 1         | 0.88%   |
| Intel Pentium Silver | 1         | 0.88%   |
| AMD Sempron          | 1         | 0.88%   |
| AMD Ryzen 9          | 1         | 0.88%   |
| AMD Ryzen 3          | 1         | 0.88%   |
| AMD Phenom II X6     | 1         | 0.88%   |
| AMD G                | 1         | 0.88%   |
| AMD A8               | 1         | 0.88%   |
| AMD A6               | 1         | 0.88%   |
| AMD A4               | 1         | 0.88%   |
| AMD A12              | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 44        | 38.94%  |
| 4      | 40        | 35.4%   |
| 8      | 10        | 8.85%   |
| 6      | 7         | 6.19%   |
| 1      | 5         | 4.42%   |
| 12     | 4         | 3.54%   |
| 14     | 1         | 0.88%   |
| 10     | 1         | 0.88%   |
| 5      | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 113       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 78        | 69.03%  |
| 1      | 35        | 30.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 113       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 81.58%  |
| 0x806d1    | 2         | 1.75%   |
| 0x806c1    | 2         | 1.75%   |
| 0x706e5    | 2         | 1.75%   |
| 0x0a50000c | 2         | 1.75%   |
| 0x906ec    | 1         | 0.88%   |
| 0x906e9    | 1         | 0.88%   |
| 0x906c0    | 1         | 0.88%   |
| 0x906a4    | 1         | 0.88%   |
| 0x906a3    | 1         | 0.88%   |
| 0x806ec    | 1         | 0.88%   |
| 0x806ea    | 1         | 0.88%   |
| 0x40661    | 1         | 0.88%   |
| 0x40651    | 1         | 0.88%   |
| 0x306a9    | 1         | 0.88%   |
| 0x10676    | 1         | 0.88%   |
| 0x08108109 | 1         | 0.88%   |
| 0x010000c8 | 1         | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 11.5%   |
| Haswell          | 13        | 11.5%   |
| Penryn           | 11        | 9.73%   |
| IvyBridge        | 11        | 9.73%   |
| Skylake          | 9         | 7.96%   |
| TigerLake        | 6         | 5.31%   |
| Zen+             | 5         | 4.42%   |
| Unknown          | 5         | 4.42%   |
| Zen 3            | 4         | 3.54%   |
| Zen 2            | 4         | 3.54%   |
| SandyBridge      | 4         | 3.54%   |
| IceLake          | 4         | 3.54%   |
| Goldmont plus    | 3         | 2.65%   |
| Westmere         | 2         | 1.77%   |
| Steamroller      | 2         | 1.77%   |
| Silvermont       | 2         | 1.77%   |
| K10              | 2         | 1.77%   |
| Excavator        | 2         | 1.77%   |
| Core             | 2         | 1.77%   |
| Alderlake Hybrid | 2         | 1.77%   |
| Zen              | 1         | 0.88%   |
| Tremont          | 1         | 0.88%   |
| Piledriver       | 1         | 0.88%   |
| Nehalem          | 1         | 0.88%   |
| CometLake        | 1         | 0.88%   |
| Broadwell        | 1         | 0.88%   |
| Bobcat           | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 66        | 49.25%  |
| Nvidia | 37        | 27.61%  |
| AMD    | 31        | 23.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 5.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 2.9%    |
| Intel HD Graphics 530                                                     | 4         | 2.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 2.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 2.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 3         | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 2.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 2.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.17%   |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.45%   |
| Nvidia GK107 [GeForce GT 640]                                             | 2         | 1.45%   |
| Nvidia C79 [GeForce 9400M]                                                | 2         | 1.45%   |
| Intel UHD Graphics 620                                                    | 2         | 1.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.45%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 2         | 1.45%   |
| Intel HD Graphics 630                                                     | 2         | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.45%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 1.45%   |
| AMD Renoir                                                                | 2         | 1.45%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 2         | 1.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 2         | 1.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.72%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 0.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.72%   |
| Nvidia GT218 [GeForce 210]                                                | 1         | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1         | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.72%   |
| Nvidia GP104 [GeForce GTX 1070]                                           | 1         | 0.72%   |
| Nvidia GM204M [GeForce GTX 980M]                                          | 1         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.72%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                               | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 41.59%  |
| 1 x AMD        | 25        | 22.12%  |
| 1 x Nvidia     | 19        | 16.81%  |
| Intel + Nvidia | 15        | 13.27%  |
| 2 x AMD        | 2         | 1.77%   |
| Intel + AMD    | 2         | 1.77%   |
| AMD + Nvidia   | 2         | 1.77%   |
| 2 x Nvidia     | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 105       | 92.92%  |
| Proprietary | 7         | 6.19%   |
| Unknown     | 1         | 0.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 92.04%  |
| 7.01-8.0   | 3         | 2.65%   |
| 0.51-1.0   | 2         | 1.77%   |
| 0.01-0.5   | 2         | 1.77%   |
| 3.01-4.0   | 1         | 0.88%   |
| 1.01-2.0   | 1         | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 16        | 12.6%   |
| LG Display              | 15        | 11.81%  |
| Samsung Electronics     | 12        | 9.45%   |
| BOE                     | 12        | 9.45%   |
| AU Optronics            | 11        | 8.66%   |
| Chimei Innolux          | 9         | 7.09%   |
| Goldstar                | 8         | 6.3%    |
| Dell                    | 5         | 3.94%   |
| Sharp                   | 3         | 2.36%   |
| Philips                 | 3         | 2.36%   |
| Hewlett-Packard         | 3         | 2.36%   |
| Sceptre Tech            | 2         | 1.57%   |
| Lenovo                  | 2         | 1.57%   |
| BenQ                    | 2         | 1.57%   |
| Vizio                   | 1         | 0.79%   |
| Toshiba                 | 1         | 0.79%   |
| Sony                    | 1         | 0.79%   |
| PANDA                   | 1         | 0.79%   |
| Panasonic               | 1         | 0.79%   |
| NSL                     | 1         | 0.79%   |
| MYS                     | 1         | 0.79%   |
| MSI                     | 1         | 0.79%   |
| Mi                      | 1         | 0.79%   |
| LG Philips              | 1         | 0.79%   |
| Kogan                   | 1         | 0.79%   |
| Idek Iiyama             | 1         | 0.79%   |
| Hitachi                 | 1         | 0.79%   |
| HannStar                | 1         | 0.79%   |
| Fujitsu Siemens         | 1         | 0.79%   |
| Eizo                    | 1         | 0.79%   |
| CVT                     | 1         | 0.79%   |
| CPT                     | 1         | 0.79%   |
| Cisco                   | 1         | 0.79%   |
| Chi Mei Optoelectronics | 1         | 0.79%   |
| ASUSTek Computer        | 1         | 0.79%   |
| AOC                     | 1         | 0.79%   |
| Ancor Communications    | 1         | 0.79%   |
| Acer                    | 1         | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 2.33%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 1.55%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 2         | 1.55%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                      | 2         | 1.55%   |
| Apple Color LCD APP9C6C 1920x1200 520x320mm 24.0-inch                 | 2         | 1.55%   |
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 1         | 0.78%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.78%   |
| Sony TV SNY7A02 1360x768 708x398mm 32.0-inch                          | 1         | 0.78%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.78%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 0.78%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.78%   |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch        | 1         | 0.78%   |
| Sceptre Tech E248W-19203S SPT099D 1920x1080 443x249mm 20.0-inch       | 1         | 0.78%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch  | 1         | 0.78%   |
| Samsung Electronics SMB2030HD SAM0709 1600x900 443x249mm 20.0-inch    | 1         | 0.78%   |
| Samsung Electronics S27A950D SAM079F 1920x1080 598x336mm 27.0-inch    | 1         | 0.78%   |
| Samsung Electronics S24E450 SAM0C7F 1920x1080 521x293mm 23.5-inch     | 1         | 0.78%   |
| Samsung Electronics LS27AG55x SAM71E0 2560x1440 597x336mm 27.0-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 1         | 0.78%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1         | 0.78%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 0.78%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 1         | 0.78%   |
| Philips 220TS PHLC06B 1920x1080 477x268mm 21.5-inch                   | 1         | 0.78%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.78%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                    | 1         | 0.78%   |
| NSL RGB-27QHD NSL2711 2560x1440 597x336mm 27.0-inch                   | 1         | 0.78%   |
| MYS LCD Monitor MYS1700 1280x1024 360x240mm 17.0-inch                 | 1         | 0.78%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                        | 1         | 0.78%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 1         | 0.78%   |
| LG Philips LCD Monitor LPLB900 1280x800 330x210mm 15.4-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 45.9%   |
| 1366x768 (WXGA)    | 20        | 16.39%  |
| 1920x1200 (WUXGA)  | 8         | 6.56%   |
| 2560x1440 (QHD)    | 7         | 5.74%   |
| 3840x2160 (4K)     | 6         | 4.92%   |
| 1280x800 (WXGA)    | 5         | 4.1%    |
| 2880x1800          | 4         | 3.28%   |
| 1600x900 (HD+)     | 3         | 2.46%   |
| 1280x1024 (SXGA)   | 3         | 2.46%   |
| 1440x900 (WXGA+)   | 2         | 1.64%   |
| 3840x2400          | 1         | 0.82%   |
| 3440x1440          | 1         | 0.82%   |
| 3360x1080          | 1         | 0.82%   |
| 2736x1824          | 1         | 0.82%   |
| 2560x1080          | 1         | 0.82%   |
| 1680x1050 (WSXGA+) | 1         | 0.82%   |
| 1360x768           | 1         | 0.82%   |
| Unknown            | 1         | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 25.2%   |
| 14      | 13        | 10.24%  |
| 27      | 11        | 8.66%   |
| 13      | 11        | 8.66%   |
| 24      | 10        | 7.87%   |
| 21      | 10        | 7.87%   |
| 17      | 10        | 7.87%   |
| 31      | 4         | 3.15%   |
| 23      | 4         | 3.15%   |
| 18      | 3         | 2.36%   |
| Unknown | 3         | 2.36%   |
| 84      | 2         | 1.57%   |
| 34      | 2         | 1.57%   |
| 26      | 2         | 1.57%   |
| 20      | 2         | 1.57%   |
| 12      | 2         | 1.57%   |
| 65      | 1         | 0.79%   |
| 42      | 1         | 0.79%   |
| 32      | 1         | 0.79%   |
| 19      | 1         | 0.79%   |
| 16      | 1         | 0.79%   |
| 11      | 1         | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 36%     |
| 501-600     | 25        | 20%     |
| 401-500     | 15        | 12%     |
| 351-400     | 13        | 10.4%   |
| 201-300     | 13        | 10.4%   |
| 601-700     | 4         | 3.2%    |
| 701-800     | 3         | 2.4%    |
| Unknown     | 3         | 2.4%    |
| 1501-2000   | 2         | 1.6%    |
| 1001-1500   | 1         | 0.8%    |
| 901-1000    | 1         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 86        | 74.14%  |
| 16/10   | 20        | 17.24%  |
| Unknown | 3         | 2.59%   |
| 4/3     | 2         | 1.72%   |
| 3/2     | 2         | 1.72%   |
| 21/9    | 2         | 1.72%   |
| 5/4     | 1         | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 27.2%   |
| 201-250        | 16        | 12.8%   |
| 81-90          | 15        | 12%     |
| 301-350        | 12        | 9.6%    |
| 71-80          | 9         | 7.2%    |
| 351-500        | 7         | 5.6%    |
| 121-130        | 6         | 4.8%    |
| 251-300        | 5         | 4%      |
| 151-200        | 5         | 4%      |
| 131-140        | 4         | 3.2%    |
| More than 1000 | 3         | 2.4%    |
| 141-150        | 3         | 2.4%    |
| Unknown        | 3         | 2.4%    |
| 61-70          | 1         | 0.8%    |
| 51-60          | 1         | 0.8%    |
| 501-1000       | 1         | 0.8%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 37        | 30.83%  |
| 51-100        | 35        | 29.17%  |
| 101-120       | 33        | 27.5%   |
| 161-240       | 8         | 6.67%   |
| Unknown       | 3         | 2.5%    |
| More than 240 | 2         | 1.67%   |
| 1-50          | 2         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 95        | 84.07%  |
| 2     | 16        | 14.16%  |
| 3     | 1         | 0.88%   |
| 0     | 1         | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 51        | 29.82%  |
| Realtek Semiconductor             | 48        | 28.07%  |
| Broadcom                          | 21        | 12.28%  |
| Qualcomm Atheros                  | 20        | 11.7%   |
| Samsung Electronics               | 4         | 2.34%   |
| Marvell Technology Group          | 4         | 2.34%   |
| Nvidia                            | 3         | 1.75%   |
| Xiaomi                            | 2         | 1.17%   |
| Ralink Technology                 | 2         | 1.17%   |
| MediaTek                          | 2         | 1.17%   |
| Ericsson Business Mobile Networks | 2         | 1.17%   |
| Dell                              | 2         | 1.17%   |
| Broadcom Limited                  | 2         | 1.17%   |
| TP-Link                           | 1         | 0.58%   |
| Ralink                            | 1         | 0.58%   |
| Qualcomm                          | 1         | 0.58%   |
| OPPO Electronics                  | 1         | 0.58%   |
| Motorola PCS                      | 1         | 0.58%   |
| Linksys                           | 1         | 0.58%   |
| ASUSTek Computer                  | 1         | 0.58%   |
| ASIX Electronics                  | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 16.75%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.87%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 2.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 1.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.91%   |
| Intel Wireless 8260                                               | 4         | 1.91%   |
| Intel Wireless 7260                                               | 4         | 1.91%   |
| Intel Wireless 3165                                               | 4         | 1.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.91%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.91%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.44%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 1.44%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.44%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.44%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 1.44%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 3         | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.96%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.96%   |
| Intel Wireless 7265                                               | 2         | 0.96%   |
| Intel Ultimate N WiFi Link 5300                                   | 2         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.96%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.96%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2         | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 41        | 41.41%  |
| Realtek Semiconductor    | 17        | 17.17%  |
| Broadcom                 | 17        | 17.17%  |
| Qualcomm Atheros         | 13        | 13.13%  |
| Ralink Technology        | 2         | 2.02%   |
| MediaTek                 | 2         | 2.02%   |
| Ralink                   | 1         | 1.01%   |
| Qualcomm                 | 1         | 1.01%   |
| Marvell Technology Group | 1         | 1.01%   |
| Linksys                  | 1         | 1.01%   |
| Dell                     | 1         | 1.01%   |
| Broadcom Limited         | 1         | 1.01%   |
| ASUSTek Computer         | 1         | 1.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 6.06%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 5.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 4.04%   |
| Intel Wireless 8260                                            | 4         | 4.04%   |
| Intel Wireless 7260                                            | 4         | 4.04%   |
| Intel Wireless 3165                                            | 4         | 4.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 4.04%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 4.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 3.03%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 3.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 2.02%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 2.02%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 2.02%   |
| Intel Wireless 7265                                            | 2         | 2.02%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 2.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.02%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2         | 2.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 2.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 2.02%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.01%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.01%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.01%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.01%   |
| Ralink RT2070 Wireless Adapter                                 | 1         | 1.01%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.01%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.01%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1.01%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter             | 1         | 1.01%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 40.95%  |
| Intel                    | 29        | 27.62%  |
| Qualcomm Atheros         | 10        | 9.52%   |
| Broadcom                 | 8         | 7.62%   |
| Samsung Electronics      | 3         | 2.86%   |
| Nvidia                   | 3         | 2.86%   |
| Marvell Technology Group | 3         | 2.86%   |
| Xiaomi                   | 2         | 1.9%    |
| TP-Link                  | 1         | 0.95%   |
| OPPO Electronics         | 1         | 0.95%   |
| Broadcom Limited         | 1         | 0.95%   |
| ASIX Electronics         | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 3.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 3.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 2.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 2.86%   |
| Nvidia MCP79 Ethernet                                             | 3         | 2.86%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 2.86%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.86%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.9%    |
| Intel Ethernet Connection I219-V                                  | 2         | 1.9%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.9%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.9%    |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.9%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.95%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.95%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1         | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.95%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 0.95%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.95%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.95%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.95%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.95%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.95%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 48.72%  |
| Ethernet | 95        | 48.72%  |
| Modem    | 4         | 2.05%   |
| Unknown  | 1         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 57.89%  |
| Ethernet | 48        | 42.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 62.83%  |
| 1     | 39        | 34.51%  |
| 3     | 2         | 1.77%   |
| 0     | 1         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 76        | 67.26%  |
| Yes  | 37        | 32.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 42.35%  |
| Apple                           | 14        | 16.47%  |
| Realtek Semiconductor           | 12        | 14.12%  |
| Qualcomm Atheros Communications | 5         | 5.88%   |
| Cambridge Silicon Radio         | 4         | 4.71%   |
| Broadcom                        | 4         | 4.71%   |
| Lite-On Technology              | 3         | 3.53%   |
| Foxconn / Hon Hai               | 2         | 2.35%   |
| Toshiba                         | 1         | 1.18%   |
| MediaTek                        | 1         | 1.18%   |
| IMC Networks                    | 1         | 1.18%   |
| ASUSTek Computer                | 1         | 1.18%   |
| Askey Computer                  | 1         | 1.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 16.47%  |
| Intel AX201 Bluetooth                               | 11        | 12.94%  |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 8.24%   |
| Apple Bluetooth Host Controller                     | 5         | 5.88%   |
| Realtek Bluetooth Radio                             | 4         | 4.71%   |
| Intel AX210 Bluetooth                               | 4         | 4.71%   |
| Intel AX200 Bluetooth                               | 4         | 4.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 4.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.53%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 3.53%   |
| Apple Bluetooth USB Host Controller                 | 3         | 3.53%   |
| Apple Bluetooth HCI                                 | 3         | 3.53%   |
| Lite-On Bluetooth Device                            | 2         | 2.35%   |
| Toshiba Bluetooth Device                            | 1         | 1.18%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.18%   |
| MediaTek Wireless_Device                            | 1         | 1.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.18%   |
| Intel Bluetooth Device                              | 1         | 1.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.18%   |
| IMC Networks Bluetooth                              | 1         | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.18%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 1.18%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 1.18%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.18%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.18%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.18%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.18%   |
| Askey Bluetooth Device                              | 1         | 1.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 85        | 53.46%  |
| AMD                      | 31        | 19.5%   |
| Nvidia                   | 28        | 17.61%  |
| Logitech                 | 4         | 2.52%   |
| C-Media Electronics      | 4         | 2.52%   |
| Razer USA                | 1         | 0.63%   |
| Nordic Semiconductor ASA | 1         | 0.63%   |
| KTMicro                  | 1         | 0.63%   |
| Goldvish                 | 1         | 0.63%   |
| Generalplus Technology   | 1         | 0.63%   |
| Creative Labs            | 1         | 0.63%   |
| ASUSTek Computer         | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 4.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 4.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 3.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 3.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 3.21%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 3.21%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 2.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 2.14%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 2.14%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.14%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 1.6%    |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 1.6%    |
| AMD FCH Azalia Controller                                                  | 3         | 1.6%    |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.07%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.07%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.07%   |
| Nvidia Audio device                                                        | 2         | 1.07%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.07%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.07%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.07%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.07%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.07%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 1.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.07%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 1.07%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.07%   |
| Razer USA Razer Barracuda X                                                | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 30.77%  |
| SK hynix            | 4         | 15.38%  |
| Micron Technology   | 4         | 15.38%  |
| Kingston            | 2         | 7.69%   |
| Unknown (0x5846)    | 1         | 3.85%   |
| Ramaxel Technology  | 1         | 3.85%   |
| pqi                 | 1         | 3.85%   |
| GSkill              | 1         | 3.85%   |
| CSX                 | 1         | 3.85%   |
| Corsair             | 1         | 3.85%   |
| Apacer              | 1         | 3.85%   |
| Unknown             | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM U6E3S4AA-MGCR 4GB Row Of Chips LPDDR4 4267MT/s    | 2         | 7.69%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1         | 3.85%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 3.85%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s       | 1         | 3.85%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 3.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 3.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s   | 1         | 3.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 3.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 3.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 3.85%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s  | 1         | 3.85%   |
| Ramaxel RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 3.85%   |
| pqi RAM Module 2GB SODIMM DDR2 667MT/s                        | 1         | 3.85%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s | 1         | 3.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s         | 1         | 3.85%   |
| Micron RAM 16ATF4G64HZ-3G2E2 32GB SODIMM DDR4 3200MT/s        | 1         | 3.85%   |
| Micron RAM 16ATF2G64HZ-2G6E3 16GB SODIMM DDR4 2667MT/s        | 1         | 3.85%   |
| Kingston RAM HX426C16FB/4 4GB DIMM DDR4 2800MT/s              | 1         | 3.85%   |
| Kingston RAM ASU16D3LU1KBG/4G 4GB DIMM DDR3 3200MT/s          | 1         | 3.85%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s         | 1         | 3.85%   |
| CSX RAM V01D3L82GB26826813 2GB DIMM 1066MT/s                  | 1         | 3.85%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s          | 1         | 3.85%   |
| Apacer RAM 78.CAGP7.C7Z0B 8GB DIMM DDR4 2400MT/s              | 1         | 3.85%   |
| Unknown                                                       | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 13        | 56.52%  |
| LPDDR4  | 3         | 13.04%  |
| DDR3    | 3         | 13.04%  |
| SDRAM   | 1         | 4.35%   |
| LPDDR3  | 1         | 4.35%   |
| DDR2    | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 56.52%  |
| Row Of Chips | 6         | 26.09%  |
| DIMM         | 4         | 17.39%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 50%     |
| 4096  | 6         | 25%     |
| 16384 | 3         | 12.5%   |
| 2048  | 2         | 8.33%   |
| 32768 | 1         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 8         | 33.33%  |
| 2667  | 5         | 20.83%  |
| 4267  | 3         | 12.5%   |
| 2800  | 2         | 8.33%   |
| 2400  | 1         | 4.17%   |
| 2133  | 1         | 4.17%   |
| 1600  | 1         | 4.17%   |
| 1066  | 1         | 4.17%   |
| 667   | 1         | 4.17%   |
| 533   | 1         | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung M2020 Series               | 1         | 33.33%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 33.33%  |
| Canon MF4320-4350                  | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson ES-H300 [GT-2500] | 1         | 50%     |
| Canon CanoScan LiDE 100       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Apple                                  | 15        | 20%     |
| Chicony Electronics                    | 14        | 18.67%  |
| Microdia                               | 8         | 10.67%  |
| IMC Networks                           | 7         | 9.33%   |
| Quanta                                 | 6         | 8%      |
| Sunplus Innovation Technology          | 4         | 5.33%   |
| Syntek                                 | 2         | 2.67%   |
| Samsung Electronics                    | 2         | 2.67%   |
| Realtek Semiconductor                  | 2         | 2.67%   |
| Generalplus Technology                 | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.67%   |
| Bison Electronics                      | 2         | 2.67%   |
| Acer                                   | 2         | 2.67%   |
| Suyin                                  | 1         | 1.33%   |
| SunplusIT                              | 1         | 1.33%   |
| Logitech                               | 1         | 1.33%   |
| Lenovo                                 | 1         | 1.33%   |
| Intel                                  | 1         | 1.33%   |
| Cisco Systems                          | 1         | 1.33%   |
| Alcor Micro                            | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 5         | 6.58%   |
| Apple Built-in iSight                    | 5         | 6.58%   |
| IMC Networks USB2.0 HD UVC WebCam        | 4         | 5.26%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 5.26%   |
| Microdia Integrated_Webcam_HD            | 3         | 3.95%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 3         | 3.95%   |
| Samsung Galaxy series, misc. (MTP mode)  | 2         | 2.63%   |
| Quanta HD Webcam                         | 2         | 2.63%   |
| Microdia Integrated Webcam               | 2         | 2.63%   |
| Chicony HP TrueVision HD Camera          | 2         | 2.63%   |
| Apple FaceTime HD Camera                 | 2         | 2.63%   |
| Apple FaceTime Camera                    | 2         | 2.63%   |
| Syntek Lenovo EasyCamera                 | 1         | 1.32%   |
| Syntek EasyCamera                        | 1         | 1.32%   |
| Suyin HD Video WebCam                    | 1         | 1.32%   |
| SunplusIT HD Camera                      | 1         | 1.32%   |
| Sunplus MTD Camera                       | 1         | 1.32%   |
| Sunplus HD Webcam                        | 1         | 1.32%   |
| Sunplus FHD Camera Microphone            | 1         | 1.32%   |
| Sunplus Dell E5570 integrated webcam     | 1         | 1.32%   |
| Realtek Integrated_Webcam_HD             | 1         | 1.32%   |
| Realtek HP Webcam                        | 1         | 1.32%   |
| Quanta USB2.0 HD UVC WebCam              | 1         | 1.32%   |
| Quanta ov9734_techfront_camera           | 1         | 1.32%   |
| Quanta HP Wide Vision HD Camera          | 1         | 1.32%   |
| Quanta HP Webcam                         | 1         | 1.32%   |
| Microdia Webcam Vitade AF                | 1         | 1.32%   |
| Microdia USB 2.0 Camera                  | 1         | 1.32%   |
| Microdia Integrated_Webcam_2M            | 1         | 1.32%   |
| Logitech C922 Pro Stream Webcam          | 1         | 1.32%   |
| Lenovo Integrated Webcam [R5U877]        | 1         | 1.32%   |
| Intel RealSense 3D Camera (Front F200)   | 1         | 1.32%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 1         | 1.32%   |
| IMC Networks Integrated Camera           | 1         | 1.32%   |
| IMC Networks HD Camera                   | 1         | 1.32%   |
| Generalplus WEB CAM                      | 1         | 1.32%   |
| Generalplus 808 Camera                   | 1         | 1.32%   |
| Cisco Systems Desk Pro Web Camera        | 1         | 1.32%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 1.32%   |
| Chicony Sony Visual Communication Camera | 1         | 1.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 31.25%  |
| Shenzhen Goodix Technology | 5         | 31.25%  |
| Synaptics                  | 2         | 12.5%   |
| Elan Microelectronics      | 2         | 12.5%   |
| Upek                       | 1         | 6.25%   |
| LighTuning Technology      | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 3         | 18.75%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 12.5%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 1         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.25%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.25%   |
| LighTuning Fingerprint Reader                          | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                  | 1         | 6.25%   |
| Elan ELAN:ARM-M4                                       | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Upek        | 1         | 20%     |
| O2 Micro    | 1         | 20%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 72        | 63.72%  |
| 1     | 33        | 29.2%   |
| 2     | 8         | 7.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 30.61%  |
| Net/wireless             | 10        | 20.41%  |
| Multimedia controller    | 9         | 18.37%  |
| Graphics card            | 6         | 12.24%  |
| Chipcard                 | 5         | 10.2%   |
| Net/ethernet             | 2         | 4.08%   |
| Storage                  | 1         | 2.04%   |
| Communication controller | 1         | 2.04%   |

