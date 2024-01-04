Linux in Netherlands - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Netherlands.

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

Total: 3502

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | [95183ba54e](https://linux-hardware.org/?probe=95183ba54e) | Jan 01, 2024 |
| HP            | Pavilion Notebook           | [a7ff16d496](https://linux-hardware.org/?probe=a7ff16d496) | Jan 01, 2024 |
| Dell          | Latitude E4300              | [528165bb06](https://linux-hardware.org/?probe=528165bb06) | Dec 31, 2023 |
| Dell          | Latitude E7450              | [dd5f4a17c4](https://linux-hardware.org/?probe=dd5f4a17c4) | Dec 30, 2023 |
| Dell          | Latitude E6440              | [8c8ec73113](https://linux-hardware.org/?probe=8c8ec73113) | Dec 30, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | [017090bd57](https://linux-hardware.org/?probe=017090bd57) | Dec 30, 2023 |
| Dell          | Latitude E7450              | [0d3dc05a2d](https://linux-hardware.org/?probe=0d3dc05a2d) | Dec 29, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [53fc03e451](https://linux-hardware.org/?probe=53fc03e451) | Dec 29, 2023 |
| ASUSTek       | K75VM                       | [4f1fddffba](https://linux-hardware.org/?probe=4f1fddffba) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [242659bbee](https://linux-hardware.org/?probe=242659bbee) | Dec 27, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [eaa68fe0f5](https://linux-hardware.org/?probe=eaa68fe0f5) | Dec 27, 2023 |
| Acer          | Aspire 5736Z                | [36f131247e](https://linux-hardware.org/?probe=36f131247e) | Dec 27, 2023 |
| Medion        | P6613                       | [1f30069d6d](https://linux-hardware.org/?probe=1f30069d6d) | Dec 26, 2023 |
| Dell          | XPS 13 9380                 | [541f2d959f](https://linux-hardware.org/?probe=541f2d959f) | Dec 26, 2023 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [00e7af074b](https://linux-hardware.org/?probe=00e7af074b) | Dec 25, 2023 |
| Dell          | Latitude E6230              | [618343f74c](https://linux-hardware.org/?probe=618343f74c) | Dec 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [23f36cddd3](https://linux-hardware.org/?probe=23f36cddd3) | Dec 24, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [e6d150acea](https://linux-hardware.org/?probe=e6d150acea) | Dec 24, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [39e33e4510](https://linux-hardware.org/?probe=39e33e4510) | Dec 24, 2023 |
| Dell          | Latitude E7450              | [6758499db8](https://linux-hardware.org/?probe=6758499db8) | Dec 24, 2023 |
| Dell          | Latitude E7450              | [d3eb47d0a5](https://linux-hardware.org/?probe=d3eb47d0a5) | Dec 24, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [9a5d0ca94a](https://linux-hardware.org/?probe=9a5d0ca94a) | Dec 23, 2023 |
| Dell          | Latitude 5540               | [3716993a6e](https://linux-hardware.org/?probe=3716993a6e) | Dec 22, 2023 |
| Entroware     | Hybris                      | [870d0c5323](https://linux-hardware.org/?probe=870d0c5323) | Dec 22, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [e864a3cd22](https://linux-hardware.org/?probe=e864a3cd22) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [cb7f868a54](https://linux-hardware.org/?probe=cb7f868a54) | Dec 21, 2023 |
| ASUSTek       | X411UA                      | [a4a14550e8](https://linux-hardware.org/?probe=a4a14550e8) | Dec 21, 2023 |
| Lenovo        | ThinkPad X201 3680WXT       | [a6e0d33afd](https://linux-hardware.org/?probe=a6e0d33afd) | Dec 21, 2023 |
| Dell          | Latitude E5510              | [e1edf60996](https://linux-hardware.org/?probe=e1edf60996) | Dec 20, 2023 |
| Framework     | Laptop                      | [2aab7ea892](https://linux-hardware.org/?probe=2aab7ea892) | Dec 19, 2023 |
| Medion        | E15415                      | [03ee2b7f5e](https://linux-hardware.org/?probe=03ee2b7f5e) | Dec 19, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [923f390d62](https://linux-hardware.org/?probe=923f390d62) | Dec 18, 2023 |
| MSI           | Prestige 14Evo A11M         | [50ef2b12e3](https://linux-hardware.org/?probe=50ef2b12e3) | Dec 17, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | [b652245cca](https://linux-hardware.org/?probe=b652245cca) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [a7be5e66cd](https://linux-hardware.org/?probe=a7be5e66cd) | Dec 15, 2023 |
| Medion        | E4251 MD61435               | [7d20d738b1](https://linux-hardware.org/?probe=7d20d738b1) | Dec 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [7d584c6a4d](https://linux-hardware.org/?probe=7d584c6a4d) | Dec 13, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9a6a483608](https://linux-hardware.org/?probe=9a6a483608) | Dec 11, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [860c083099](https://linux-hardware.org/?probe=860c083099) | Dec 11, 2023 |
| HP            | Pavilion Notebook           | [0e463b364d](https://linux-hardware.org/?probe=0e463b364d) | Dec 10, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [37214745c0](https://linux-hardware.org/?probe=37214745c0) | Dec 10, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [c0797a823b](https://linux-hardware.org/?probe=c0797a823b) | Dec 10, 2023 |
| Apple         | MacBookPro11,2              | [817f57a6bf](https://linux-hardware.org/?probe=817f57a6bf) | Dec 10, 2023 |
| Dell          | Latitude E7240              | [93f24d2411](https://linux-hardware.org/?probe=93f24d2411) | Dec 09, 2023 |
| Dell          | Latitude 7400               | [71ba2c1398](https://linux-hardware.org/?probe=71ba2c1398) | Dec 08, 2023 |
| Medion        | E11201                      | [8e7e346f7f](https://linux-hardware.org/?probe=8e7e346f7f) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | [2d85c45e57](https://linux-hardware.org/?probe=2d85c45e57) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | [01177d538f](https://linux-hardware.org/?probe=01177d538f) | Dec 08, 2023 |
| Fujitsu       | LIFEBOOK E744               | [2b97f06319](https://linux-hardware.org/?probe=2b97f06319) | Dec 07, 2023 |
| HP            | EliteBook 840 G6            | [6e7af6d32b](https://linux-hardware.org/?probe=6e7af6d32b) | Dec 07, 2023 |
| ASUSTek       | K52Jc                       | [54e52154d1](https://linux-hardware.org/?probe=54e52154d1) | Dec 07, 2023 |
| HP            | Pavilion 17                 | [93ecaf88d6](https://linux-hardware.org/?probe=93ecaf88d6) | Dec 06, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [36fe4a1de9](https://linux-hardware.org/?probe=36fe4a1de9) | Dec 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [52ee43b1e5](https://linux-hardware.org/?probe=52ee43b1e5) | Dec 06, 2023 |
| HP            | Pavilion Notebook           | [e36be09527](https://linux-hardware.org/?probe=e36be09527) | Dec 06, 2023 |
| ASUSTek       | X540SAA                     | [86295630b8](https://linux-hardware.org/?probe=86295630b8) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | [1748ab2263](https://linux-hardware.org/?probe=1748ab2263) | Dec 05, 2023 |
| Acer          | Aspire A315-510P            | [3937003fd0](https://linux-hardware.org/?probe=3937003fd0) | Dec 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c64bc46e3a](https://linux-hardware.org/?probe=c64bc46e3a) | Dec 05, 2023 |
| HP            | Compaq 6730b (NA373UC#AB... | [7e0d2ebaaf](https://linux-hardware.org/?probe=7e0d2ebaaf) | Dec 04, 2023 |
| Dell          | Precision 5680              | [6982d86e8c](https://linux-hardware.org/?probe=6982d86e8c) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [58a0ae4fcc](https://linux-hardware.org/?probe=58a0ae4fcc) | Dec 02, 2023 |
| ASUSTek       | N71Jq                       | [f13e32bb82](https://linux-hardware.org/?probe=f13e32bb82) | Nov 29, 2023 |
| Acer          | TravelMate P614-51-G2       | [17c4552f25](https://linux-hardware.org/?probe=17c4552f25) | Nov 29, 2023 |
| Toshiba       | Satellite L70-A             | [3ac84816d0](https://linux-hardware.org/?probe=3ac84816d0) | Nov 28, 2023 |
| Dell          | Latitude 13                 | [bf50df43fa](https://linux-hardware.org/?probe=bf50df43fa) | Nov 27, 2023 |
| HP            | ZBook 15 G3                 | [03586846aa](https://linux-hardware.org/?probe=03586846aa) | Nov 27, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [be532e0503](https://linux-hardware.org/?probe=be532e0503) | Nov 27, 2023 |
| Lenovo        | G50-45 80E3                 | [6f475bfe64](https://linux-hardware.org/?probe=6f475bfe64) | Nov 26, 2023 |
| Samsung       | R520/R522/R620              | [36cde2f22a](https://linux-hardware.org/?probe=36cde2f22a) | Nov 25, 2023 |
| Dell          | Latitude 7490               | [a9d03c8349](https://linux-hardware.org/?probe=a9d03c8349) | Nov 25, 2023 |
| Dell          | Latitude E5540              | [33e3a21810](https://linux-hardware.org/?probe=33e3a21810) | Nov 25, 2023 |
| Lenovo        | Z710 20250                  | [c9522c065e](https://linux-hardware.org/?probe=c9522c065e) | Nov 24, 2023 |
| Toshiba       | Satellite Pro C70-B         | [97f5f12369](https://linux-hardware.org/?probe=97f5f12369) | Nov 24, 2023 |
| Dell          | Latitude E5450              | [fad9a32575](https://linux-hardware.org/?probe=fad9a32575) | Nov 23, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [ce955eaeb4](https://linux-hardware.org/?probe=ce955eaeb4) | Nov 22, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [194465c3c5](https://linux-hardware.org/?probe=194465c3c5) | Nov 22, 2023 |
| Dell          | Latitude 3580               | [c5c5d11d39](https://linux-hardware.org/?probe=c5c5d11d39) | Nov 22, 2023 |
| Sony          | VPCF23P1E                   | [0bfcf70f1a](https://linux-hardware.org/?probe=0bfcf70f1a) | Nov 21, 2023 |
| HP            | EliteBook 725 G2            | [b6cfe558cb](https://linux-hardware.org/?probe=b6cfe558cb) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [243ff5e0c9](https://linux-hardware.org/?probe=243ff5e0c9) | Nov 21, 2023 |
| HP            | ProBook 6560b               | [84d3b269c8](https://linux-hardware.org/?probe=84d3b269c8) | Nov 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [da5735e87b](https://linux-hardware.org/?probe=da5735e87b) | Nov 20, 2023 |
| BTO           | 17X1183                     | [6cd57738ff](https://linux-hardware.org/?probe=6cd57738ff) | Nov 20, 2023 |
| Apple         | MacBookPro11,2              | [b4c20e35e9](https://linux-hardware.org/?probe=b4c20e35e9) | Nov 19, 2023 |
| Apple         | MacBookPro11,2              | [050c215616](https://linux-hardware.org/?probe=050c215616) | Nov 19, 2023 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | [0b06f82d9d](https://linux-hardware.org/?probe=0b06f82d9d) | Nov 19, 2023 |
| Lenovo        | G510 20238                  | [2567713f24](https://linux-hardware.org/?probe=2567713f24) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [deea1f8184](https://linux-hardware.org/?probe=deea1f8184) | Nov 19, 2023 |
| Packard Be... | ENLE11BZ                    | [905ad855b3](https://linux-hardware.org/?probe=905ad855b3) | Nov 19, 2023 |
| Apple         | MacBookAir7,2               | [186bca6f10](https://linux-hardware.org/?probe=186bca6f10) | Nov 18, 2023 |
| Dell          | Latitude 3189               | [97c8d8041c](https://linux-hardware.org/?probe=97c8d8041c) | Nov 18, 2023 |
| Apple         | MacBookPro14,3              | [8f5057710c](https://linux-hardware.org/?probe=8f5057710c) | Nov 18, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [2be4a499cb](https://linux-hardware.org/?probe=2be4a499cb) | Nov 18, 2023 |
| HP            | ProBook 650 G1              | [d61fe67d3f](https://linux-hardware.org/?probe=d61fe67d3f) | Nov 18, 2023 |
| Dell          | Precision 5480              | [ee10103325](https://linux-hardware.org/?probe=ee10103325) | Nov 18, 2023 |
| Medion        | E4251 MD61435               | [01ea5c9a87](https://linux-hardware.org/?probe=01ea5c9a87) | Nov 17, 2023 |
| HP            | ProBook 650 G1              | [8cba43dfd6](https://linux-hardware.org/?probe=8cba43dfd6) | Nov 17, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [644a0b97d3](https://linux-hardware.org/?probe=644a0b97d3) | Nov 16, 2023 |
| HP            | EliteBook 840 14 inch G1... | [fd50b727cb](https://linux-hardware.org/?probe=fd50b727cb) | Nov 16, 2023 |
| Lenovo        | G50-70 20351                | [7f136c3e39](https://linux-hardware.org/?probe=7f136c3e39) | Nov 16, 2023 |
| Dell          | XPS 9320                    | [f0435ea4b7](https://linux-hardware.org/?probe=f0435ea4b7) | Nov 15, 2023 |
| HP            | EliteBook 830 G5            | [b87f339bd3](https://linux-hardware.org/?probe=b87f339bd3) | Nov 15, 2023 |
| Dell          | Latitude E6410              | [1e9606e755](https://linux-hardware.org/?probe=1e9606e755) | Nov 14, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [1baa2ce489](https://linux-hardware.org/?probe=1baa2ce489) | Nov 13, 2023 |
| Toshiba       | Satellite C870-15J          | [e71fa72088](https://linux-hardware.org/?probe=e71fa72088) | Nov 13, 2023 |
| Toshiba       | Satellite C870-15J          | [86aac4739f](https://linux-hardware.org/?probe=86aac4739f) | Nov 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [d74ee5702a](https://linux-hardware.org/?probe=d74ee5702a) | Nov 13, 2023 |
| HP            | Spectre x2 Pro              | [8363c9eb12](https://linux-hardware.org/?probe=8363c9eb12) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [c00b5e7c16](https://linux-hardware.org/?probe=c00b5e7c16) | Nov 12, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [99b19c5226](https://linux-hardware.org/?probe=99b19c5226) | Nov 11, 2023 |
| Dell          | Latitude 5580               | [41900c8211](https://linux-hardware.org/?probe=41900c8211) | Nov 10, 2023 |
| Notebook      | NS5x_NS7xAU                 | [0ecd643e18](https://linux-hardware.org/?probe=0ecd643e18) | Nov 10, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [f2e379d36f](https://linux-hardware.org/?probe=f2e379d36f) | Nov 10, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [ecb49b0454](https://linux-hardware.org/?probe=ecb49b0454) | Nov 09, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [5b67ed0642](https://linux-hardware.org/?probe=5b67ed0642) | Nov 09, 2023 |
| MSI           | Prestige 14Evo A12M         | [fc8b4307d1](https://linux-hardware.org/?probe=fc8b4307d1) | Nov 09, 2023 |
| Apple         | MacBookAir6,1               | [e3e009b3ce](https://linux-hardware.org/?probe=e3e009b3ce) | Nov 09, 2023 |
| Medion        | P6613                       | [549455ad75](https://linux-hardware.org/?probe=549455ad75) | Nov 08, 2023 |
| Medion        | P6613                       | [ad65262643](https://linux-hardware.org/?probe=ad65262643) | Nov 08, 2023 |
| Valve         | Jupiter                     | [ef2daabe89](https://linux-hardware.org/?probe=ef2daabe89) | Nov 07, 2023 |
| Valve         | Jupiter                     | [21df431e01](https://linux-hardware.org/?probe=21df431e01) | Nov 07, 2023 |
| ASUSTek       | N71Jq                       | [680e4d8cc9](https://linux-hardware.org/?probe=680e4d8cc9) | Nov 07, 2023 |
| Dell          | XPS 15 9500                 | [e07422acdd](https://linux-hardware.org/?probe=e07422acdd) | Nov 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a41a28625](https://linux-hardware.org/?probe=4a41a28625) | Nov 06, 2023 |
| Dell          | Inspiron 15-3567            | [b42102e397](https://linux-hardware.org/?probe=b42102e397) | Nov 06, 2023 |
| Dell          | Latitude 5590               | [913308d97b](https://linux-hardware.org/?probe=913308d97b) | Nov 05, 2023 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [27923cd021](https://linux-hardware.org/?probe=27923cd021) | Nov 05, 2023 |
| HP            | Compaq 6710b                | [7a0b2fd29b](https://linux-hardware.org/?probe=7a0b2fd29b) | Nov 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b390f8cd05](https://linux-hardware.org/?probe=b390f8cd05) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | [a8bb556bfe](https://linux-hardware.org/?probe=a8bb556bfe) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [aba7da7a37](https://linux-hardware.org/?probe=aba7da7a37) | Nov 04, 2023 |
| Dell          | Latitude E6420              | [1f2c5ea57b](https://linux-hardware.org/?probe=1f2c5ea57b) | Nov 03, 2023 |
| Irbis         | NB211                       | [694ca0f127](https://linux-hardware.org/?probe=694ca0f127) | Nov 03, 2023 |
| Packard Be... | EasyNote TK87               | [3ff2e66179](https://linux-hardware.org/?probe=3ff2e66179) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [a0c7507d6d](https://linux-hardware.org/?probe=a0c7507d6d) | Nov 03, 2023 |
| Medion        | ERAZER X7855 MD60892        | [b34c69b29d](https://linux-hardware.org/?probe=b34c69b29d) | Nov 03, 2023 |
| Irbis         | NB211                       | [3ebca4338a](https://linux-hardware.org/?probe=3ebca4338a) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [0929326be0](https://linux-hardware.org/?probe=0929326be0) | Nov 03, 2023 |
| HP            | EliteBook Folio 1040 G2     | [5c4a8fa3ed](https://linux-hardware.org/?probe=5c4a8fa3ed) | Nov 02, 2023 |
| MSI           | Titan GT77HX 13VI           | [1fb8b0ccb3](https://linux-hardware.org/?probe=1fb8b0ccb3) | Nov 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [317aadad91](https://linux-hardware.org/?probe=317aadad91) | Nov 01, 2023 |
| HP            | EliteBook 8470w             | [d4b6365e3f](https://linux-hardware.org/?probe=d4b6365e3f) | Nov 01, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [2abdc4603a](https://linux-hardware.org/?probe=2abdc4603a) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [48f8f53d3e](https://linux-hardware.org/?probe=48f8f53d3e) | Oct 30, 2023 |
| Dell          | Latitude 7430               | [b72f3f4264](https://linux-hardware.org/?probe=b72f3f4264) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [5863bd6189](https://linux-hardware.org/?probe=5863bd6189) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [1267d6df00](https://linux-hardware.org/?probe=1267d6df00) | Oct 29, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H10... | [0a7d468516](https://linux-hardware.org/?probe=0a7d468516) | Oct 29, 2023 |
| Dell          | XPS 9315                    | [6f3e496918](https://linux-hardware.org/?probe=6f3e496918) | Oct 29, 2023 |
| Notebook      | N85_N87HCHNHZ               | [751a447386](https://linux-hardware.org/?probe=751a447386) | Oct 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [91f7b242b9](https://linux-hardware.org/?probe=91f7b242b9) | Oct 28, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [aaf303e411](https://linux-hardware.org/?probe=aaf303e411) | Oct 28, 2023 |
| Lenovo        | G50-70 20351                | [39e2fb6be6](https://linux-hardware.org/?probe=39e2fb6be6) | Oct 27, 2023 |
| Dell          | Latitude 5440               | [e7d56ee207](https://linux-hardware.org/?probe=e7d56ee207) | Oct 26, 2023 |
| Dell          | Latitude 7490               | [58324a8dfd](https://linux-hardware.org/?probe=58324a8dfd) | Oct 26, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [d7ffb73521](https://linux-hardware.org/?probe=d7ffb73521) | Oct 26, 2023 |
| Acer          | Aspire SW5-171              | [3b2a04a910](https://linux-hardware.org/?probe=3b2a04a910) | Oct 26, 2023 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [0206625e43](https://linux-hardware.org/?probe=0206625e43) | Oct 24, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [f1e5521102](https://linux-hardware.org/?probe=f1e5521102) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [c03a4ad29d](https://linux-hardware.org/?probe=c03a4ad29d) | Oct 23, 2023 |
| Medion        | P6613                       | [c36f8ad846](https://linux-hardware.org/?probe=c36f8ad846) | Oct 23, 2023 |
| Acer          | Aspire A317-33              | [f48b2b4e3c](https://linux-hardware.org/?probe=f48b2b4e3c) | Oct 23, 2023 |
| Medion        | P6613                       | [18975f3ee4](https://linux-hardware.org/?probe=18975f3ee4) | Oct 23, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [93043f297f](https://linux-hardware.org/?probe=93043f297f) | Oct 22, 2023 |
| HP            | ProBook 6550b               | [da6e693794](https://linux-hardware.org/?probe=da6e693794) | Oct 22, 2023 |
| Apple         | MacBookAir4,2               | [dcef0a70af](https://linux-hardware.org/?probe=dcef0a70af) | Oct 21, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [a149fbf417](https://linux-hardware.org/?probe=a149fbf417) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [f4f7d19069](https://linux-hardware.org/?probe=f4f7d19069) | Oct 20, 2023 |
| HP            | EliteBook 8570p             | [5cea3b7124](https://linux-hardware.org/?probe=5cea3b7124) | Oct 18, 2023 |
| Acer          | Swift SF314-54              | [0df63f5012](https://linux-hardware.org/?probe=0df63f5012) | Oct 17, 2023 |
| Acer          | Swift SF314-54              | [0bb3061070](https://linux-hardware.org/?probe=0bb3061070) | Oct 17, 2023 |
| Dell          | XPS 15 9530                 | [96f3c530df](https://linux-hardware.org/?probe=96f3c530df) | Oct 17, 2023 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [d4a36e5a56](https://linux-hardware.org/?probe=d4a36e5a56) | Oct 17, 2023 |
| Gigabyte      | AORUS 15G XB                | [9e4c6d48d4](https://linux-hardware.org/?probe=9e4c6d48d4) | Oct 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c3e8cf453e](https://linux-hardware.org/?probe=c3e8cf453e) | Oct 15, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [46cc5e4c0a](https://linux-hardware.org/?probe=46cc5e4c0a) | Oct 15, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [398445f93d](https://linux-hardware.org/?probe=398445f93d) | Oct 14, 2023 |
| Lenovo        | G50-70 20351                | [bdd8aeaf43](https://linux-hardware.org/?probe=bdd8aeaf43) | Oct 14, 2023 |
| MSI           | GF75 Thin 9SC               | [e9bee28805](https://linux-hardware.org/?probe=e9bee28805) | Oct 14, 2023 |
| Dell          | Inspiron 3793               | [ef66b70c6f](https://linux-hardware.org/?probe=ef66b70c6f) | Oct 12, 2023 |
| Acer          | Aspire E5-575               | [ab55bb1001](https://linux-hardware.org/?probe=ab55bb1001) | Oct 12, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [2dbab85ec9](https://linux-hardware.org/?probe=2dbab85ec9) | Oct 12, 2023 |
| Dell          | Inspiron 3793               | [ec7d122a78](https://linux-hardware.org/?probe=ec7d122a78) | Oct 12, 2023 |
| HP            | ProBook 650 G1              | [b506ceb439](https://linux-hardware.org/?probe=b506ceb439) | Oct 11, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [5e8749954f](https://linux-hardware.org/?probe=5e8749954f) | Oct 11, 2023 |
| Acer          | Aspire A515-44G             | [58d145f207](https://linux-hardware.org/?probe=58d145f207) | Oct 11, 2023 |
| Acer          | Aspire A315-55G             | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| Acer          | Aspire 5732Z                | [d9c5086891](https://linux-hardware.org/?probe=d9c5086891) | Oct 09, 2023 |
| Notebook      | PCx0Dx                      | [9e8bfb1d9e](https://linux-hardware.org/?probe=9e8bfb1d9e) | Oct 09, 2023 |
| HP            | ProBook 650 G1              | [33dc949dff](https://linux-hardware.org/?probe=33dc949dff) | Oct 09, 2023 |
| Dell          | Vostro 3700                 | [5776334e3a](https://linux-hardware.org/?probe=5776334e3a) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| HP            | EliteBook 2540p             | [5cc0f3a697](https://linux-hardware.org/?probe=5cc0f3a697) | Oct 09, 2023 |
| ASUSTek       | G551JW                      | [7f805877ed](https://linux-hardware.org/?probe=7f805877ed) | Oct 08, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | [c975944c8e](https://linux-hardware.org/?probe=c975944c8e) | Oct 07, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [1c741fc115](https://linux-hardware.org/?probe=1c741fc115) | Oct 06, 2023 |
| Medion        | E4251 MD61435               | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| HP            | ZBook Studio G5             | [47a1dadfc2](https://linux-hardware.org/?probe=47a1dadfc2) | Oct 05, 2023 |
| Dell          | Latitude 5530               | [1a05adb467](https://linux-hardware.org/?probe=1a05adb467) | Oct 04, 2023 |
| ASUSTek       | E402BA                      | [ff16ab19fd](https://linux-hardware.org/?probe=ff16ab19fd) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [85af984a69](https://linux-hardware.org/?probe=85af984a69) | Oct 03, 2023 |
| HP            | Pavilion dv6                | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| VALE          | Notebook Classic C140       | [0516711124](https://linux-hardware.org/?probe=0516711124) | Oct 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| HP            | Pro Tablet 608 G1           | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [a3af35a207](https://linux-hardware.org/?probe=a3af35a207) | Sep 29, 2023 |
| Dell          | Latitude 3301               | [3859ed5445](https://linux-hardware.org/?probe=3859ed5445) | Sep 29, 2023 |
| SKIKK         | Sindri 14                   | [9766c80aa9](https://linux-hardware.org/?probe=9766c80aa9) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5828bffdb6](https://linux-hardware.org/?probe=5828bffdb6) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [58fdd789af](https://linux-hardware.org/?probe=58fdd789af) | Sep 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a95feaee78](https://linux-hardware.org/?probe=a95feaee78) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [f1623258a8](https://linux-hardware.org/?probe=f1623258a8) | Sep 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [2e717c304e](https://linux-hardware.org/?probe=2e717c304e) | Sep 25, 2023 |
| MSI           | Katana 15 B12VGK            | [9a6d33a191](https://linux-hardware.org/?probe=9a6d33a191) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42309ddc8c](https://linux-hardware.org/?probe=42309ddc8c) | Sep 23, 2023 |
| System76      | Gazelle                     | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| Notebook      | NH50_70RH                   | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| Acer          | Aspire A114-33              | [4b581786a8](https://linux-hardware.org/?probe=4b581786a8) | Sep 21, 2023 |
| Acer          | Aspire 7520                 | [5e16126a55](https://linux-hardware.org/?probe=5e16126a55) | Sep 21, 2023 |
| Lenovo        | ThinkPad L540 20AU006CRI    | [e8885911a0](https://linux-hardware.org/?probe=e8885911a0) | Sep 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [4ab55a6c83](https://linux-hardware.org/?probe=4ab55a6c83) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [a41b85a029](https://linux-hardware.org/?probe=a41b85a029) | Sep 21, 2023 |
| Chuwi         | MiniBook X                  | [50d0819b3b](https://linux-hardware.org/?probe=50d0819b3b) | Sep 20, 2023 |
| Clevo         | E7130                       | [38de5c7699](https://linux-hardware.org/?probe=38de5c7699) | Sep 20, 2023 |
| Acer          | Aspire 7520                 | [bbba1d5ea4](https://linux-hardware.org/?probe=bbba1d5ea4) | Sep 20, 2023 |
| Medion        | Akoya E7416                 | [f820e8515d](https://linux-hardware.org/?probe=f820e8515d) | Sep 19, 2023 |
| HP            | EliteBook 8570w             | [d90f46756b](https://linux-hardware.org/?probe=d90f46756b) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [acd1c47b9d](https://linux-hardware.org/?probe=acd1c47b9d) | Sep 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9e9652809d](https://linux-hardware.org/?probe=9e9652809d) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | [410df263b8](https://linux-hardware.org/?probe=410df263b8) | Sep 18, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [ebfe5ca0b0](https://linux-hardware.org/?probe=ebfe5ca0b0) | Sep 18, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | [5f99185bbb](https://linux-hardware.org/?probe=5f99185bbb) | Sep 17, 2023 |
| HP            | Laptop 15-dy2xxx            | [faa9a71ce1](https://linux-hardware.org/?probe=faa9a71ce1) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| ASUSTek       | K54L                        | [4b62e4c882](https://linux-hardware.org/?probe=4b62e4c882) | Sep 15, 2023 |
| HP            | EliteBook Revolve 810 G3    | [960947648b](https://linux-hardware.org/?probe=960947648b) | Sep 15, 2023 |
| Acer          | Aspire E5-774               | [3d3f930e69](https://linux-hardware.org/?probe=3d3f930e69) | Sep 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | [d0e8034434](https://linux-hardware.org/?probe=d0e8034434) | Sep 14, 2023 |
| Medion        | E11201                      | [c62ac67427](https://linux-hardware.org/?probe=c62ac67427) | Sep 10, 2023 |
| HP            | Pavilion g6                 | [f39fbfabcc](https://linux-hardware.org/?probe=f39fbfabcc) | Sep 10, 2023 |
| HP            | Pavilion g6                 | [e82f904ef8](https://linux-hardware.org/?probe=e82f904ef8) | Sep 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ecef237a9c](https://linux-hardware.org/?probe=ecef237a9c) | Sep 07, 2023 |
| Valve         | Jupiter                     | [85a4fe79c2](https://linux-hardware.org/?probe=85a4fe79c2) | Sep 07, 2023 |
| ASUSTek       | N751JX                      | [8ece217753](https://linux-hardware.org/?probe=8ece217753) | Sep 06, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [dccf0aaf61](https://linux-hardware.org/?probe=dccf0aaf61) | Sep 06, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [51e417460a](https://linux-hardware.org/?probe=51e417460a) | Sep 05, 2023 |
| Framework     | Laptop                      | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [312d4a06dc](https://linux-hardware.org/?probe=312d4a06dc) | Sep 05, 2023 |
| Toshiba       | Satellite A200              | [a26939af7b](https://linux-hardware.org/?probe=a26939af7b) | Sep 05, 2023 |
| HP            | ProBook 6550b               | [5881531377](https://linux-hardware.org/?probe=5881531377) | Sep 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9accfe317a](https://linux-hardware.org/?probe=9accfe317a) | Sep 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [945acb9ea2](https://linux-hardware.org/?probe=945acb9ea2) | Sep 04, 2023 |
| MSI           | Prestige 14Evo A12M         | [d7b4b0f2f1](https://linux-hardware.org/?probe=d7b4b0f2f1) | Sep 04, 2023 |
| Lenovo        | Z50-75 80EC                 | [12894bacfb](https://linux-hardware.org/?probe=12894bacfb) | Sep 03, 2023 |
| HUAWEI        | HN-WX9X                     | [efd67d7c17](https://linux-hardware.org/?probe=efd67d7c17) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [5032531f3e](https://linux-hardware.org/?probe=5032531f3e) | Sep 02, 2023 |
| Dell          | Latitude 5420               | [2acb1da32c](https://linux-hardware.org/?probe=2acb1da32c) | Sep 02, 2023 |
| Lenovo        | 14w Gen 2 82N9              | [87c8a118b5](https://linux-hardware.org/?probe=87c8a118b5) | Sep 02, 2023 |
| Acer          | Aspire V3-772               | [5cb3aa2368](https://linux-hardware.org/?probe=5cb3aa2368) | Aug 31, 2023 |
| HP            | EliteBook 2570p             | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| MSI           | Katana GF76 11UC            | [dd25d90357](https://linux-hardware.org/?probe=dd25d90357) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [338a8026f3](https://linux-hardware.org/?probe=338a8026f3) | Aug 29, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [87b94b4ea0](https://linux-hardware.org/?probe=87b94b4ea0) | Aug 28, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [8c0be85e0e](https://linux-hardware.org/?probe=8c0be85e0e) | Aug 28, 2023 |
| Valve         | Jupiter                     | [4d894addd1](https://linux-hardware.org/?probe=4d894addd1) | Aug 27, 2023 |
| Dell          | XPS 13 9310                 | [40802d54a7](https://linux-hardware.org/?probe=40802d54a7) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [5ef3048a11](https://linux-hardware.org/?probe=5ef3048a11) | Aug 26, 2023 |
| HP            | EliteBook 840 G3            | [25b5ca25b8](https://linux-hardware.org/?probe=25b5ca25b8) | Aug 26, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [14605463c1](https://linux-hardware.org/?probe=14605463c1) | Aug 26, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [738c091241](https://linux-hardware.org/?probe=738c091241) | Aug 26, 2023 |
| HP            | Notebook                    | [b27d20b450](https://linux-hardware.org/?probe=b27d20b450) | Aug 26, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6496a666d7](https://linux-hardware.org/?probe=6496a666d7) | Aug 26, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | [adb5d31da7](https://linux-hardware.org/?probe=adb5d31da7) | Aug 25, 2023 |
| Google        | Rammus                      | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| Google        | Rammus                      | [57b3596f63](https://linux-hardware.org/?probe=57b3596f63) | Aug 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3746b277b6](https://linux-hardware.org/?probe=3746b277b6) | Aug 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3e241db8f7](https://linux-hardware.org/?probe=3e241db8f7) | Aug 24, 2023 |
| Dell          | XPS 15 7590                 | [66b46e04d3](https://linux-hardware.org/?probe=66b46e04d3) | Aug 23, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [845b1d4d76](https://linux-hardware.org/?probe=845b1d4d76) | Aug 22, 2023 |
| Positivo      | Mobile                      | [e39dbd02a9](https://linux-hardware.org/?probe=e39dbd02a9) | Aug 22, 2023 |
| Dell          | XPS 15 9500                 | [23474c1faa](https://linux-hardware.org/?probe=23474c1faa) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [81bc5661ca](https://linux-hardware.org/?probe=81bc5661ca) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23243VG       | [be77bad24e](https://linux-hardware.org/?probe=be77bad24e) | Aug 21, 2023 |
| HP            | Presario CQ42               | [183f035603](https://linux-hardware.org/?probe=183f035603) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | [19675df004](https://linux-hardware.org/?probe=19675df004) | Aug 20, 2023 |
| Apple         | MacBookAir7,2               | [fb3c8c793c](https://linux-hardware.org/?probe=fb3c8c793c) | Aug 19, 2023 |
| HP            | EliteBook 2540p             | [dc150253e5](https://linux-hardware.org/?probe=dc150253e5) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [24a295f95b](https://linux-hardware.org/?probe=24a295f95b) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| Acer          | Aspire A515-52G             | [2d38a6554a](https://linux-hardware.org/?probe=2d38a6554a) | Aug 16, 2023 |
| Dell          | XPS 15 9500                 | [56759a6a05](https://linux-hardware.org/?probe=56759a6a05) | Aug 16, 2023 |
| HP            | Laptop 17-ca0xxx            | [bbf606d6e8](https://linux-hardware.org/?probe=bbf606d6e8) | Aug 16, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [7aac45ad2d](https://linux-hardware.org/?probe=7aac45ad2d) | Aug 15, 2023 |
| Apple         | MacBookPro9,2               | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| Valve         | Jupiter                     | [ed10f1ef39](https://linux-hardware.org/?probe=ed10f1ef39) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| AMI           | Unknown                     | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| Lenovo        | ThinkPad T490 20N3S8FN0F    | [cff61d75ae](https://linux-hardware.org/?probe=cff61d75ae) | Aug 12, 2023 |
| HP            | ProBook 6560b               | [01c0e5d78c](https://linux-hardware.org/?probe=01c0e5d78c) | Aug 12, 2023 |
| Dell          | Inspiron 1720               | [1cb123d894](https://linux-hardware.org/?probe=1cb123d894) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| ASUSTek       | X751LD                      | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| ASUSTek       | K75VJ                       | [7d1e95601c](https://linux-hardware.org/?probe=7d1e95601c) | Aug 09, 2023 |
| HP            | ProBook 4310s               | [ac0c1be078](https://linux-hardware.org/?probe=ac0c1be078) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| HP            | EliteBook 2540p             | [2a02492c01](https://linux-hardware.org/?probe=2a02492c01) | Aug 09, 2023 |
| HP            | EliteBook 2540p             | [509b979b88](https://linux-hardware.org/?probe=509b979b88) | Aug 09, 2023 |
| HONOR         | BOHK-WAX9X                  | [8a6ead436f](https://linux-hardware.org/?probe=8a6ead436f) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [c06b23398a](https://linux-hardware.org/?probe=c06b23398a) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | [60a28c22c7](https://linux-hardware.org/?probe=60a28c22c7) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | [9f044dbe9e](https://linux-hardware.org/?probe=9f044dbe9e) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [543719cf07](https://linux-hardware.org/?probe=543719cf07) | Aug 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [c1062b9705](https://linux-hardware.org/?probe=c1062b9705) | Aug 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [46a7513850](https://linux-hardware.org/?probe=46a7513850) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | [309b546405](https://linux-hardware.org/?probe=309b546405) | Aug 07, 2023 |
| Apple         | MacBookPro9,2               | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| Dell          | Latitude 7480               | [eeb7f6e8fe](https://linux-hardware.org/?probe=eeb7f6e8fe) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [fcc05278d6](https://linux-hardware.org/?probe=fcc05278d6) | Aug 04, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [deb7c70ef0](https://linux-hardware.org/?probe=deb7c70ef0) | Aug 02, 2023 |
| Dell          | Latitude E6440              | [57ce920c06](https://linux-hardware.org/?probe=57ce920c06) | Aug 01, 2023 |
| Apple         | MacBookAir3,1               | [9a3416654f](https://linux-hardware.org/?probe=9a3416654f) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4d875892d6](https://linux-hardware.org/?probe=4d875892d6) | Jul 30, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [f1db906c7c](https://linux-hardware.org/?probe=f1db906c7c) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | [c8391bd952](https://linux-hardware.org/?probe=c8391bd952) | Jul 29, 2023 |
| Acer          | TravelMate B115-M           | [ca01eab0e3](https://linux-hardware.org/?probe=ca01eab0e3) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [95e189ee7a](https://linux-hardware.org/?probe=95e189ee7a) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| VALE          | Notebook Classic C140       | [ec65662265](https://linux-hardware.org/?probe=ec65662265) | Jul 28, 2023 |
| HP            | ZBook 15 G5                 | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Dell          | XPS 15 9530                 | [d6855eabe2](https://linux-hardware.org/?probe=d6855eabe2) | Jul 26, 2023 |
| Minix         | NEO Z83-4A                  | [3a884d55d3](https://linux-hardware.org/?probe=3a884d55d3) | Jul 26, 2023 |
| Dell          | Latitude E7440              | [9b8234d640](https://linux-hardware.org/?probe=9b8234d640) | Jul 26, 2023 |
| MSI           | Prestige 14Evo A12M         | [4872d1fdf6](https://linux-hardware.org/?probe=4872d1fdf6) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [c73107bcac](https://linux-hardware.org/?probe=c73107bcac) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [1aeabb238f](https://linux-hardware.org/?probe=1aeabb238f) | Jul 25, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7970e46266](https://linux-hardware.org/?probe=7970e46266) | Jul 25, 2023 |
| Notebook      | NH50_70RH                   | [12c8f156b9](https://linux-hardware.org/?probe=12c8f156b9) | Jul 25, 2023 |
| Notebook      | NH50_70RH                   | [52d2901ce2](https://linux-hardware.org/?probe=52d2901ce2) | Jul 25, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [02cae62d32](https://linux-hardware.org/?probe=02cae62d32) | Jul 24, 2023 |
| Sony          | SVF1521A6EW                 | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| Medion        | E4251 MD61435               | [4cd0b97344](https://linux-hardware.org/?probe=4cd0b97344) | Jul 23, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [de58b924e1](https://linux-hardware.org/?probe=de58b924e1) | Jul 23, 2023 |
| HP            | EliteBook 820 G4            | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Standard      | Unknown                     | [74acf0f707](https://linux-hardware.org/?probe=74acf0f707) | Jul 21, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [2a3971e2fc](https://linux-hardware.org/?probe=2a3971e2fc) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| Lenovo        | G50-70 20351                | [a55acd567e](https://linux-hardware.org/?probe=a55acd567e) | Jul 19, 2023 |
| Notebook      | NH5x_7xDPx                  | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| HP            | Notebook                    | [4498c757a7](https://linux-hardware.org/?probe=4498c757a7) | Jul 18, 2023 |
| Dell          | Latitude E5510              | [3b006db4ec](https://linux-hardware.org/?probe=3b006db4ec) | Jul 18, 2023 |
| HP            | Pavilion 17                 | [7c39d851fd](https://linux-hardware.org/?probe=7c39d851fd) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | [d06ca4b9c2](https://linux-hardware.org/?probe=d06ca4b9c2) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | [103e7e5196](https://linux-hardware.org/?probe=103e7e5196) | Jul 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | [b62ed55325](https://linux-hardware.org/?probe=b62ed55325) | Jul 15, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [7872b8a730](https://linux-hardware.org/?probe=7872b8a730) | Jul 15, 2023 |
| HP            | ZBook 17 G2                 | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [038a62a49f](https://linux-hardware.org/?probe=038a62a49f) | Jul 15, 2023 |
| Apple         | MacBookPro8,1               | [4de092adb7](https://linux-hardware.org/?probe=4de092adb7) | Jul 14, 2023 |
| Dell          | Precision 7540              | [c862752535](https://linux-hardware.org/?probe=c862752535) | Jul 14, 2023 |
| HP            | ProBook 6570b               | [0c933d2dd8](https://linux-hardware.org/?probe=0c933d2dd8) | Jul 12, 2023 |
| Toshiba       | Satellite C850-1GL          | [e160b642b4](https://linux-hardware.org/?probe=e160b642b4) | Jul 12, 2023 |
| Acer          | Extensa 7630G               | [47c7ddbf85](https://linux-hardware.org/?probe=47c7ddbf85) | Jul 11, 2023 |
| Toshiba       | Satellite C850-1GL          | [f7305d0265](https://linux-hardware.org/?probe=f7305d0265) | Jul 11, 2023 |
| Dell          | XPS 15 9530                 | [f60d21d84f](https://linux-hardware.org/?probe=f60d21d84f) | Jul 10, 2023 |
| Acer          | TravelMate P2510-G2-M       | [c96a405528](https://linux-hardware.org/?probe=c96a405528) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| MSI           | Cyborg 15 A12VF             | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a3fd5e4b9d](https://linux-hardware.org/?probe=a3fd5e4b9d) | Jul 07, 2023 |
| ASUSTek       | G73Jw                       | [79053de50e](https://linux-hardware.org/?probe=79053de50e) | Jul 07, 2023 |
| ASUSTek       | Strix GL504GM_GL504GM       | [b482f282a5](https://linux-hardware.org/?probe=b482f282a5) | Jul 06, 2023 |
| Notebook      | NJx0PU                      | [29ebf426d1](https://linux-hardware.org/?probe=29ebf426d1) | Jul 06, 2023 |
| Acer          | TravelMate P215-53          | [d759c2c726](https://linux-hardware.org/?probe=d759c2c726) | Jul 06, 2023 |
| Dell          | Inspiron 5593               | [a40b38a093](https://linux-hardware.org/?probe=a40b38a093) | Jul 05, 2023 |
| HP            | EliteBook 820 G4            | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| HP            | Compaq Presario CQ60        | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| ASUSTek       | UX430UAR                    | [6a51948293](https://linux-hardware.org/?probe=6a51948293) | Jul 03, 2023 |
| Packard Be... | EasyNote TJ67               | [92be4d3a56](https://linux-hardware.org/?probe=92be4d3a56) | Jul 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [54987b03a1](https://linux-hardware.org/?probe=54987b03a1) | Jul 02, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | [88b4565c0b](https://linux-hardware.org/?probe=88b4565c0b) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | [7e1b98b585](https://linux-hardware.org/?probe=7e1b98b585) | Jul 01, 2023 |
| HP            | EliteBook 2540p             | [7b546735a4](https://linux-hardware.org/?probe=7b546735a4) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | [70ce1e280f](https://linux-hardware.org/?probe=70ce1e280f) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | [b5e0044759](https://linux-hardware.org/?probe=b5e0044759) | Jun 30, 2023 |
| ASUSTek       | X751MA                      | [b36ca5687c](https://linux-hardware.org/?probe=b36ca5687c) | Jun 29, 2023 |
| Acer          | Aspire 5745G                | [c3394b9eb0](https://linux-hardware.org/?probe=c3394b9eb0) | Jun 28, 2023 |
| Dell          | Latitude 7370               | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Acer          | Aspire A315-51              | [771e2e233a](https://linux-hardware.org/?probe=771e2e233a) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [3ea9e41d03](https://linux-hardware.org/?probe=3ea9e41d03) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| Intel Clie... | LAPRC710                    | [5aabe7850a](https://linux-hardware.org/?probe=5aabe7850a) | Jun 27, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [e16689358e](https://linux-hardware.org/?probe=e16689358e) | Jun 26, 2023 |
| HP            | EliteBook 2540p             | [f5e04da161](https://linux-hardware.org/?probe=f5e04da161) | Jun 26, 2023 |
| MSI           | GF75 Thin 9SC               | [554a954c22](https://linux-hardware.org/?probe=554a954c22) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | [9c925666a5](https://linux-hardware.org/?probe=9c925666a5) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | [ea814b3f7b](https://linux-hardware.org/?probe=ea814b3f7b) | Jun 26, 2023 |
| Apple         | MacBookPro11,2              | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [23c2fe2245](https://linux-hardware.org/?probe=23c2fe2245) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d7e8503e88](https://linux-hardware.org/?probe=d7e8503e88) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [4ab121533a](https://linux-hardware.org/?probe=4ab121533a) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| HP            | EliteBook 2540p             | [b33e52fa0a](https://linux-hardware.org/?probe=b33e52fa0a) | Jun 22, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [7782ddf809](https://linux-hardware.org/?probe=7782ddf809) | Jun 22, 2023 |
| HP            | EliteBook 865 16 inch G9... | [e4407d328d](https://linux-hardware.org/?probe=e4407d328d) | Jun 22, 2023 |
| Dell          | Latitude E6410              | [b34442d8c3](https://linux-hardware.org/?probe=b34442d8c3) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | [f9bf8920f7](https://linux-hardware.org/?probe=f9bf8920f7) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | [c436287876](https://linux-hardware.org/?probe=c436287876) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [bcd39f0607](https://linux-hardware.org/?probe=bcd39f0607) | Jun 19, 2023 |
| HP            | HDX18                       | [dec8492b2f](https://linux-hardware.org/?probe=dec8492b2f) | Jun 19, 2023 |
| ASUSTek       | X541NA                      | [2fa7c42c59](https://linux-hardware.org/?probe=2fa7c42c59) | Jun 18, 2023 |
| Dell          | Latitude 5430               | [cb097e3c83](https://linux-hardware.org/?probe=cb097e3c83) | Jun 18, 2023 |
| Dell          | Precision 7540              | [8b9ddcc1d8](https://linux-hardware.org/?probe=8b9ddcc1d8) | Jun 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | [8f32e75d6e](https://linux-hardware.org/?probe=8f32e75d6e) | Jun 18, 2023 |
| Dell          | Latitude 3189               | [c7f2d1b100](https://linux-hardware.org/?probe=c7f2d1b100) | Jun 17, 2023 |
| HP            | EliteBook 2540p             | [a62dc4b2ed](https://linux-hardware.org/?probe=a62dc4b2ed) | Jun 17, 2023 |
| Acer          | Aspire V5-571P              | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| HP            | HDX18                       | [9a49d14af9](https://linux-hardware.org/?probe=9a49d14af9) | Jun 15, 2023 |
| Dell          | Inspiron 15 3511            | [175aa8aae4](https://linux-hardware.org/?probe=175aa8aae4) | Jun 15, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [a8cc966bac](https://linux-hardware.org/?probe=a8cc966bac) | Jun 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| Dell          | Latitude 3310               | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| Acer          | Aspire V3-772               | [1f5318c2b4](https://linux-hardware.org/?probe=1f5318c2b4) | Jun 14, 2023 |
| Dell          | Latitude E5270              | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| Samsung       | 750XED                      | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [39d97bb85b](https://linux-hardware.org/?probe=39d97bb85b) | Jun 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [aca09b2a54](https://linux-hardware.org/?probe=aca09b2a54) | Jun 12, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [b815ac19d4](https://linux-hardware.org/?probe=b815ac19d4) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [b9c83e1b8a](https://linux-hardware.org/?probe=b9c83e1b8a) | Jun 12, 2023 |
| Notebook      | NJx0MU                      | [d2cb2b5360](https://linux-hardware.org/?probe=d2cb2b5360) | Jun 11, 2023 |
| Google        | Snappy                      | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| Samsung       | N150/N210/N220              | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Apple         | MacBookPro9,2               | [f502f89e9d](https://linux-hardware.org/?probe=f502f89e9d) | Jun 10, 2023 |
| Valve         | Jupiter                     | [7a36bdb92a](https://linux-hardware.org/?probe=7a36bdb92a) | Jun 09, 2023 |
| HUAWEI        | MACHC-WAX9                  | [6f26f51ef6](https://linux-hardware.org/?probe=6f26f51ef6) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Dell          | Precision 7540              | [41fe2f93ff](https://linux-hardware.org/?probe=41fe2f93ff) | Jun 09, 2023 |
| Lenovo        | ThinkPad T590 20N5000AMH    | [91c0d99427](https://linux-hardware.org/?probe=91c0d99427) | Jun 06, 2023 |
| Dell          | Latitude 7480               | [61c800a3b4](https://linux-hardware.org/?probe=61c800a3b4) | Jun 06, 2023 |
| Dell          | XPS 15 9560                 | [0d326774c9](https://linux-hardware.org/?probe=0d326774c9) | Jun 06, 2023 |
| Dell          | Precision 7540              | [a10ecca056](https://linux-hardware.org/?probe=a10ecca056) | Jun 04, 2023 |
| Toshiba       | Satellite Pro C70-B         | [d4bc6d6c8c](https://linux-hardware.org/?probe=d4bc6d6c8c) | Jun 04, 2023 |
| HP            | Laptop 17-cp0xxx            | [253c561829](https://linux-hardware.org/?probe=253c561829) | Jun 04, 2023 |
| AMI           | Intel                       | [cd2beb79d2](https://linux-hardware.org/?probe=cd2beb79d2) | Jun 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [6d8d7f6384](https://linux-hardware.org/?probe=6d8d7f6384) | Jun 04, 2023 |
| ASUSTek       | X553MA                      | [d07b3215b1](https://linux-hardware.org/?probe=d07b3215b1) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [4d1ad8d52a](https://linux-hardware.org/?probe=4d1ad8d52a) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| Apple         | MacBookAir6,1               | [20a14caf03](https://linux-hardware.org/?probe=20a14caf03) | Jun 03, 2023 |
| Dell          | XPS 15 9530                 | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| HUAWEI        | MACHC-WAX9                  | [c87d784c98](https://linux-hardware.org/?probe=c87d784c98) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [6b1168349b](https://linux-hardware.org/?probe=6b1168349b) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [3da98cc9bb](https://linux-hardware.org/?probe=3da98cc9bb) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [98b0b355db](https://linux-hardware.org/?probe=98b0b355db) | Jun 01, 2023 |
| Dell          | Precision 7540              | [de2fc5bc92](https://linux-hardware.org/?probe=de2fc5bc92) | Jun 01, 2023 |
| Valve         | Jupiter                     | [06000e9b0e](https://linux-hardware.org/?probe=06000e9b0e) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [7210e5c07e](https://linux-hardware.org/?probe=7210e5c07e) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6d6d7c65a8](https://linux-hardware.org/?probe=6d6d7c65a8) | May 31, 2023 |
| Dell          | XPS 13 9310                 | [a3e4ffb4fd](https://linux-hardware.org/?probe=a3e4ffb4fd) | May 30, 2023 |
| Acer          | Aspire 5750                 | [fa8eeaabff](https://linux-hardware.org/?probe=fa8eeaabff) | May 30, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9178413d40](https://linux-hardware.org/?probe=9178413d40) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [cc9d03264f](https://linux-hardware.org/?probe=cc9d03264f) | May 27, 2023 |
| Toshiba       | Satellite Pro C70-B         | [3058a75499](https://linux-hardware.org/?probe=3058a75499) | May 26, 2023 |
| MSI           | CX700                       | [ecb1aaf9c1](https://linux-hardware.org/?probe=ecb1aaf9c1) | May 26, 2023 |
| Dell          | XPS 13 9310                 | [689eec8b51](https://linux-hardware.org/?probe=689eec8b51) | May 26, 2023 |
| Dell          | Latitude 5290               | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| Dell          | Precision 7540              | [99c7b41c6b](https://linux-hardware.org/?probe=99c7b41c6b) | May 25, 2023 |
| Dell          | Inspiron 5759               | [52b95d45ca](https://linux-hardware.org/?probe=52b95d45ca) | May 23, 2023 |
| Apple         | MacBookPro9,1               | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [c77cb59a5c](https://linux-hardware.org/?probe=c77cb59a5c) | May 23, 2023 |
| Dell          | Precision 7540              | [95bbab11f1](https://linux-hardware.org/?probe=95bbab11f1) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| ASUSTek       | X551MA                      | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASUSTek       | X551MA                      | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| Dell          | XPS 9315                    | [6c3fdbf590](https://linux-hardware.org/?probe=6c3fdbf590) | May 22, 2023 |
| HP            | ZBook 14u G5                | [a655c52b88](https://linux-hardware.org/?probe=a655c52b88) | May 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | [536b91dce1](https://linux-hardware.org/?probe=536b91dce1) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| Lenovo        | ThinkPad T410 2537V32       | [cece14e931](https://linux-hardware.org/?probe=cece14e931) | May 21, 2023 |
| Toshiba       | Satellite C870-1FZ          | [1f2563578e](https://linux-hardware.org/?probe=1f2563578e) | May 20, 2023 |
| HP            | ProBook 650 G3              | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| Sony          | SVF1521A6EW                 | [49a9f77ea9](https://linux-hardware.org/?probe=49a9f77ea9) | May 18, 2023 |
| Dell          | Latitude 5500               | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| Acer          | Aspire A114-32              | [d17a909427](https://linux-hardware.org/?probe=d17a909427) | May 18, 2023 |
| Acer          | Aspire 7535                 | [32b02980a7](https://linux-hardware.org/?probe=32b02980a7) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Dell          | Latitude E5510              | [74ecc09f16](https://linux-hardware.org/?probe=74ecc09f16) | May 17, 2023 |
| Dell          | Inspiron 5759               | [228fa2798d](https://linux-hardware.org/?probe=228fa2798d) | May 16, 2023 |
| Dell          | Inspiron 5759               | [32d4567b37](https://linux-hardware.org/?probe=32d4567b37) | May 16, 2023 |
| Framework     | Laptop                      | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [de2456eae8](https://linux-hardware.org/?probe=de2456eae8) | May 16, 2023 |
| Dell          | Latitude 5320               | [c33be8e25c](https://linux-hardware.org/?probe=c33be8e25c) | May 16, 2023 |
| Dell          | Latitude 5320               | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Samsung       | N150/N210/N220              | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| HP            | ZBook 15u G5                | [4f1f52ce64](https://linux-hardware.org/?probe=4f1f52ce64) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| MSI           | Stealth GS77 12UH           | [08fdf9cb20](https://linux-hardware.org/?probe=08fdf9cb20) | May 12, 2023 |
| HP            | EliteBook 720 G2            | [d6a156003b](https://linux-hardware.org/?probe=d6a156003b) | May 12, 2023 |
| Dell          | Latitude E7450              | [9dbbae1356](https://linux-hardware.org/?probe=9dbbae1356) | May 12, 2023 |
| HP            | 255 G7 Notebook PC          | [341a5673f2](https://linux-hardware.org/?probe=341a5673f2) | May 12, 2023 |
| HP            | EliteBook 820 G4            | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Notebook      | N14xWU                      | [0e4f386b46](https://linux-hardware.org/?probe=0e4f386b46) | May 11, 2023 |
| HP            | EliteBook 820 G4            | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| Acer          | TravelMate P653-M           | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Dell          | XPS 9315                    | [291a190f04](https://linux-hardware.org/?probe=291a190f04) | May 10, 2023 |
| Dell          | XPS 15 9520                 | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| Toshiba       | Satellite L650              | [ba32d27df1](https://linux-hardware.org/?probe=ba32d27df1) | May 08, 2023 |
| Acer          | Aspire 5732Z                | [ec45ea6206](https://linux-hardware.org/?probe=ec45ea6206) | May 08, 2023 |
| PC Special... | NP5x_NP6x_NP7xPNP           | [72d9dac16b](https://linux-hardware.org/?probe=72d9dac16b) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [148433c97e](https://linux-hardware.org/?probe=148433c97e) | May 07, 2023 |
| Timi          | TM1701                      | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [0d6a9b046a](https://linux-hardware.org/?probe=0d6a9b046a) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Dell          | Latitude E5530 non-vPro     | [3bea2bcd99](https://linux-hardware.org/?probe=3bea2bcd99) | May 05, 2023 |
| Unknown       | Cherry Trail CR             | [9569a530e8](https://linux-hardware.org/?probe=9569a530e8) | May 05, 2023 |
| Dell          | Precision 7720              | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| Acer          | TravelMate P214-53          | [8e78c8d139](https://linux-hardware.org/?probe=8e78c8d139) | May 05, 2023 |
| HP            | EliteBook 8470p             | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Valve         | Jupiter                     | [0a6a9a6675](https://linux-hardware.org/?probe=0a6a9a6675) | May 03, 2023 |
| Dell          | Latitude 7420               | [7986f6779d](https://linux-hardware.org/?probe=7986f6779d) | May 03, 2023 |
| HP            | EliteBook Folio G1          | [a31ef5e00e](https://linux-hardware.org/?probe=a31ef5e00e) | May 02, 2023 |
| Toshiba       | Satellite C870-1FZ          | [dfbf38e06f](https://linux-hardware.org/?probe=dfbf38e06f) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| VIOS          | LTH17                       | [4d1a86ee61](https://linux-hardware.org/?probe=4d1a86ee61) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| Insyde        | M890BAP                     | [151efb0278](https://linux-hardware.org/?probe=151efb0278) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | [a9f658c8af](https://linux-hardware.org/?probe=a9f658c8af) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Latitude 3301               | [3a0aad0e75](https://linux-hardware.org/?probe=3a0aad0e75) | Apr 29, 2023 |
| HP            | Pavilion dv7                | [e3f05fe37f](https://linux-hardware.org/?probe=e3f05fe37f) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [da542ba626](https://linux-hardware.org/?probe=da542ba626) | Apr 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b5a953a984](https://linux-hardware.org/?probe=b5a953a984) | Apr 28, 2023 |
| Dell          | Latitude 3301               | [855564b077](https://linux-hardware.org/?probe=855564b077) | Apr 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [858404838d](https://linux-hardware.org/?probe=858404838d) | Apr 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [0bf066e179](https://linux-hardware.org/?probe=0bf066e179) | Apr 27, 2023 |
| Medion        | E2215T MD60198              | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Swift SF114-34              | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [5236dde38f](https://linux-hardware.org/?probe=5236dde38f) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | [40df32580a](https://linux-hardware.org/?probe=40df32580a) | Apr 25, 2023 |
| Notebook      | P95_96_97Ex,Rx              | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| Apple         | MacBookPro15,2              | [09eb88ba6c](https://linux-hardware.org/?probe=09eb88ba6c) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| BTO           | 17X1183                     | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| Dell          | Latitude 9520               | [0ab9a83db6](https://linux-hardware.org/?probe=0ab9a83db6) | Apr 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b906572f4b](https://linux-hardware.org/?probe=b906572f4b) | Apr 23, 2023 |
| Notebook      | NLxxPUx                     | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Apple         | MacBookPro12,1              | [65ba6571a2](https://linux-hardware.org/?probe=65ba6571a2) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Dell          | Latitude E4300              | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Medion        | E4251                       | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | [a26039eb50](https://linux-hardware.org/?probe=a26039eb50) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | [7e7a982c3c](https://linux-hardware.org/?probe=7e7a982c3c) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Acer          | TP-SW3-013-181M             | [d231dc8846](https://linux-hardware.org/?probe=d231dc8846) | Apr 22, 2023 |
| Notebook      | N13_N140ZU                  | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| ASUSTek       | ZenBook UX333FN_RX333FN     | [8027ff2b04](https://linux-hardware.org/?probe=8027ff2b04) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| Chuwi         | HeroBook Pro                | [e8332849a1](https://linux-hardware.org/?probe=e8332849a1) | Apr 20, 2023 |
| Dell          | Latitude 5400               | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| ASUSTek       | K501LX                      | [00676747c4](https://linux-hardware.org/?probe=00676747c4) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| Dell          | XPS 15 7590                 | [abcb6ed7e8](https://linux-hardware.org/?probe=abcb6ed7e8) | Apr 19, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Acer          | Iconia                      | [1ebc88d3ab](https://linux-hardware.org/?probe=1ebc88d3ab) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Apple         | MacBookPro9,2               | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Dell          | Latitude 5500               | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| HP            | EliteBook 840 G1            | [5994a04ee0](https://linux-hardware.org/?probe=5994a04ee0) | Apr 16, 2023 |
| HP            | ZBook 14u G5                | [fcf729207a](https://linux-hardware.org/?probe=fcf729207a) | Apr 15, 2023 |
| HP            | EliteBook 830 G6            | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| ASUSTek       | GL502VM                     | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| Wortmann      | TERRA_MOBILE_1160           | [d40eed27fd](https://linux-hardware.org/?probe=d40eed27fd) | Apr 13, 2023 |
| HP            | Compaq Presario C700        | [0519471935](https://linux-hardware.org/?probe=0519471935) | Apr 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [0a09da06be](https://linux-hardware.org/?probe=0a09da06be) | Apr 13, 2023 |
| HP            | ZBook 15 G3                 | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| Notebook      | NH55RGQ                     | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| Apple         | MacBookAir7,2               | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Apple         | MacBookPro8,1               | [5a903505c7](https://linux-hardware.org/?probe=5a903505c7) | Apr 10, 2023 |
| HP            | EliteBook 8570p             | [854ec28c71](https://linux-hardware.org/?probe=854ec28c71) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [02bbb66fe9](https://linux-hardware.org/?probe=02bbb66fe9) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [76af734c86](https://linux-hardware.org/?probe=76af734c86) | Apr 07, 2023 |
| Notebook      | N141CU                      | [8648ddb323](https://linux-hardware.org/?probe=8648ddb323) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [405f73f1fd](https://linux-hardware.org/?probe=405f73f1fd) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [0af2f7cc7f](https://linux-hardware.org/?probe=0af2f7cc7f) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [10213d8aa1](https://linux-hardware.org/?probe=10213d8aa1) | Apr 05, 2023 |
| Valve         | Jupiter                     | [e8a69f8de9](https://linux-hardware.org/?probe=e8a69f8de9) | Apr 05, 2023 |
| Dell          | XPS 9320                    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| HP            | EliteBook 2530p             | [519d2a4d5a](https://linux-hardware.org/?probe=519d2a4d5a) | Apr 04, 2023 |
| HP            | ProBook 6570b               | [d42564b34f](https://linux-hardware.org/?probe=d42564b34f) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | [1af731cc92](https://linux-hardware.org/?probe=1af731cc92) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| Toxic         | GM5MPHY                     | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| ilife         | S806                        | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ac5393930b](https://linux-hardware.org/?probe=ac5393930b) | Apr 02, 2023 |
| ilife         | S806                        | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| HUAWEI        | MACHC-WAX9                  | [3494157f4b](https://linux-hardware.org/?probe=3494157f4b) | Apr 01, 2023 |
| Dell          | Latitude E7450              | [8bf693a890](https://linux-hardware.org/?probe=8bf693a890) | Apr 01, 2023 |
| Acer          | Aspire 7741                 | [34bd6f42b1](https://linux-hardware.org/?probe=34bd6f42b1) | Mar 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | [6ade0ea04f](https://linux-hardware.org/?probe=6ade0ea04f) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | [0028f21c3e](https://linux-hardware.org/?probe=0028f21c3e) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [61ede0b764](https://linux-hardware.org/?probe=61ede0b764) | Mar 29, 2023 |
| Acer          | Aspire E5-773G              | [3cb72ca21c](https://linux-hardware.org/?probe=3cb72ca21c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Apple         | MacBookPro11,2              | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| Valve         | Jupiter                     | [68175ccbea](https://linux-hardware.org/?probe=68175ccbea) | Mar 27, 2023 |
| Unknown       | Unknown                     | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [79c876bced](https://linux-hardware.org/?probe=79c876bced) | Mar 25, 2023 |
| Haier         | S15                         | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| Acer          | Aspire 5733Z                | [8a7f87172d](https://linux-hardware.org/?probe=8a7f87172d) | Mar 24, 2023 |
| Framework     | Laptop                      | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| Dell          | XPS 15 9520                 | [06d6af1db0](https://linux-hardware.org/?probe=06d6af1db0) | Mar 23, 2023 |
| Dell          | XPS 13 9310                 | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| HP            | ZBook 15 G5                 | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| Dell          | Latitude E6520              | [82f97b14f4](https://linux-hardware.org/?probe=82f97b14f4) | Mar 20, 2023 |
| Valve         | Jupiter                     | [b73f7b46c4](https://linux-hardware.org/?probe=b73f7b46c4) | Mar 20, 2023 |
| Dell          | Latitude E6520              | [7f92514d4e](https://linux-hardware.org/?probe=7f92514d4e) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [92ae74e13d](https://linux-hardware.org/?probe=92ae74e13d) | Mar 19, 2023 |
| Dell          | Inspiron 15-3567            | [e90a87f6f2](https://linux-hardware.org/?probe=e90a87f6f2) | Mar 18, 2023 |
| Dell          | Latitude E7240              | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| HP            | Compaq 6730s                | [7e2310fcf0](https://linux-hardware.org/?probe=7e2310fcf0) | Mar 17, 2023 |
| Dell          | Latitude E7440              | [edf7e8521c](https://linux-hardware.org/?probe=edf7e8521c) | Mar 17, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [a78f938382](https://linux-hardware.org/?probe=a78f938382) | Mar 15, 2023 |
| HP            | EliteBook 2570p             | [1c6475f7da](https://linux-hardware.org/?probe=1c6475f7da) | Mar 15, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fcb50f0e4f](https://linux-hardware.org/?probe=fcb50f0e4f) | Mar 14, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fc7320db54](https://linux-hardware.org/?probe=fc7320db54) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b3e091147a](https://linux-hardware.org/?probe=b3e091147a) | Mar 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [e6d2f2a3b4](https://linux-hardware.org/?probe=e6d2f2a3b4) | Mar 14, 2023 |
| Acer          | Aspire A715-74G             | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| HP            | Pavilion dv7                | [66f70aa8f4](https://linux-hardware.org/?probe=66f70aa8f4) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [eb987f6db2](https://linux-hardware.org/?probe=eb987f6db2) | Mar 12, 2023 |
| Medion        | E4251                       | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Acer          | Aspire 8930                 | [7434247d21](https://linux-hardware.org/?probe=7434247d21) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Acer          | Aspire A715-75G             | [3283454c2d](https://linux-hardware.org/?probe=3283454c2d) | Mar 10, 2023 |
| HP            | ProBook 430 G2              | [21595cd5ed](https://linux-hardware.org/?probe=21595cd5ed) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| HP            | ZBook 15 G3                 | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Google        | Rammus                      | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HUAWEI        | MACHC-WAX9                  | [53b112adac](https://linux-hardware.org/?probe=53b112adac) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Studio XPS 1647             | [484c629656](https://linux-hardware.org/?probe=484c629656) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| Alienware     | m15                         | [180a0251f5](https://linux-hardware.org/?probe=180a0251f5) | Mar 02, 2023 |
| HP            | Notebook                    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [5cb58db69b](https://linux-hardware.org/?probe=5cb58db69b) | Mar 02, 2023 |
| ASUSTek       | N76VB                       | [0043164762](https://linux-hardware.org/?probe=0043164762) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HP            | ProBook 6570b               | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| Sony          | VGN-FW11M                   | [06b355e1de](https://linux-hardware.org/?probe=06b355e1de) | Feb 28, 2023 |
| Unknown       | Unknown                     | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3aae5788cf](https://linux-hardware.org/?probe=3aae5788cf) | Feb 25, 2023 |
| HP            | Pavilion g7                 | [8f46d24897](https://linux-hardware.org/?probe=8f46d24897) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [2978ec71b8](https://linux-hardware.org/?probe=2978ec71b8) | Feb 25, 2023 |
| HP            | Laptop 15s-fq1xxx           | [ca2ef50547](https://linux-hardware.org/?probe=ca2ef50547) | Feb 25, 2023 |
| HP            | Laptop 15s-fq1xxx           | [3899b2f13e](https://linux-hardware.org/?probe=3899b2f13e) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| Acer          | Aspire 5732Z                | [2cb9f58eae](https://linux-hardware.org/?probe=2cb9f58eae) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| HP            | Laptop 14s-dq1xxx           | [1cca7fe830](https://linux-hardware.org/?probe=1cca7fe830) | Feb 22, 2023 |
| HP            | EliteBook 820 G4            | [de79cbb975](https://linux-hardware.org/?probe=de79cbb975) | Feb 22, 2023 |
| Valve         | Jupiter                     | [5e92cdeee7](https://linux-hardware.org/?probe=5e92cdeee7) | Feb 22, 2023 |
| HP            | Pavilion dv7                | [1ecf49cbaf](https://linux-hardware.org/?probe=1ecf49cbaf) | Feb 21, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e1c694b371](https://linux-hardware.org/?probe=e1c694b371) | Feb 20, 2023 |
| Dell          | Latitude 7300               | [65690f7efc](https://linux-hardware.org/?probe=65690f7efc) | Feb 20, 2023 |
| Dell          | Latitude E6320              | [0b5bcfefc5](https://linux-hardware.org/?probe=0b5bcfefc5) | Feb 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [8ca2b786db](https://linux-hardware.org/?probe=8ca2b786db) | Feb 19, 2023 |
| Unknown       | Unknown                     | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Dell          | Inspiron 15-3567            | [c2e0245ec5](https://linux-hardware.org/?probe=c2e0245ec5) | Feb 19, 2023 |
| Dell          | Latitude E6320              | [8110ff7717](https://linux-hardware.org/?probe=8110ff7717) | Feb 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [3886d9287f](https://linux-hardware.org/?probe=3886d9287f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [1b401aa3cf](https://linux-hardware.org/?probe=1b401aa3cf) | Feb 17, 2023 |
| Unknown       | Unknown                     | [c59694e05c](https://linux-hardware.org/?probe=c59694e05c) | Feb 17, 2023 |
| Unknown       | Unknown                     | [c614caec4a](https://linux-hardware.org/?probe=c614caec4a) | Feb 17, 2023 |
| Alienware     | 15 R3                       | [c273319d9d](https://linux-hardware.org/?probe=c273319d9d) | Feb 17, 2023 |
| HP            | EliteBook 2570p             | [4fe16ec4fe](https://linux-hardware.org/?probe=4fe16ec4fe) | Feb 16, 2023 |
| HP            | Notebook                    | [3de841fd56](https://linux-hardware.org/?probe=3de841fd56) | Feb 16, 2023 |
| HP            | Pavilion dv7                | [130fe12846](https://linux-hardware.org/?probe=130fe12846) | Feb 16, 2023 |
| HP            | Pavilion dv7                | [7ca9bf386b](https://linux-hardware.org/?probe=7ca9bf386b) | Feb 16, 2023 |
| Google        | Helios                      | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| Dell          | Latitude 3320               | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [3039ccd4b0](https://linux-hardware.org/?probe=3039ccd4b0) | Feb 14, 2023 |
| HP            | EliteBook 8570w             | [0d16c9013f](https://linux-hardware.org/?probe=0d16c9013f) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E5570              | [16e090c63c](https://linux-hardware.org/?probe=16e090c63c) | Feb 13, 2023 |
| Acer          | TravelMate P215-53          | [7c1423b767](https://linux-hardware.org/?probe=7c1423b767) | Feb 13, 2023 |
| Dell          | Precision 3571              | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Acer          | Predator PH315-52           | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| Valve         | Jupiter                     | [5629f3ed8c](https://linux-hardware.org/?probe=5629f3ed8c) | Feb 12, 2023 |
| HP            | Compaq 6820s                | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| Acer          | Aspire V3-772               | [95875d4afc](https://linux-hardware.org/?probe=95875d4afc) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| Dell          | Precision 3571              | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [353bd3a5b2](https://linux-hardware.org/?probe=353bd3a5b2) | Feb 09, 2023 |
| Acer          | TravelMate P215-53          | [f3eb8a2592](https://linux-hardware.org/?probe=f3eb8a2592) | Feb 09, 2023 |
| HP            | EliteBook 850 G3            | [7091e6ba95](https://linux-hardware.org/?probe=7091e6ba95) | Feb 08, 2023 |
| Dell          | Latitude E7450              | [2513ec83c8](https://linux-hardware.org/?probe=2513ec83c8) | Feb 08, 2023 |
| HP            | ZBook 15 G2                 | [20d7058e4f](https://linux-hardware.org/?probe=20d7058e4f) | Feb 08, 2023 |
| Valve         | Jupiter                     | [b376c55e80](https://linux-hardware.org/?probe=b376c55e80) | Feb 07, 2023 |
| Dell          | Latitude E6320              | [6d1fe4f041](https://linux-hardware.org/?probe=6d1fe4f041) | Feb 06, 2023 |
| Lenovo        | ThinkPad T510 4349AF5       | [5d737e59ae](https://linux-hardware.org/?probe=5d737e59ae) | Feb 06, 2023 |
| Apple         | MacBookPro8,2               | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| Standard      | Unknown                     | [c983c471de](https://linux-hardware.org/?probe=c983c471de) | Feb 05, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [b6333de3ab](https://linux-hardware.org/?probe=b6333de3ab) | Feb 05, 2023 |
| Valve         | Jupiter                     | [8dee1d9415](https://linux-hardware.org/?probe=8dee1d9415) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | [2a25e1c4d6](https://linux-hardware.org/?probe=2a25e1c4d6) | Feb 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| HP            | EliteBook 2560p             | [798466ab86](https://linux-hardware.org/?probe=798466ab86) | Jan 31, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [2469884587](https://linux-hardware.org/?probe=2469884587) | Jan 30, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [debdb8208f](https://linux-hardware.org/?probe=debdb8208f) | Jan 29, 2023 |
| HP            | Pavilion Sleekbook 15       | [d17dc00a8a](https://linux-hardware.org/?probe=d17dc00a8a) | Jan 29, 2023 |
| Lenovo        | G550 2958                   | [8bee986aca](https://linux-hardware.org/?probe=8bee986aca) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Lenovo        | G550 2958                   | [a50b0e3645](https://linux-hardware.org/?probe=a50b0e3645) | Jan 28, 2023 |
| Acer          | Aspire E5-774               | [86e3285b31](https://linux-hardware.org/?probe=86e3285b31) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| HP            | ZBook 15 G2                 | [b9793eca79](https://linux-hardware.org/?probe=b9793eca79) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [ee769c62bf](https://linux-hardware.org/?probe=ee769c62bf) | Jan 27, 2023 |
| Dell          | XPS 13 9305                 | [c0468fe8fd](https://linux-hardware.org/?probe=c0468fe8fd) | Jan 27, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| Valve         | Jupiter                     | [cb8c4c9711](https://linux-hardware.org/?probe=cb8c4c9711) | Jan 26, 2023 |
| Valve         | Jupiter                     | [076783b777](https://linux-hardware.org/?probe=076783b777) | Jan 26, 2023 |
| Toshiba       | Satellite C870-12F          | [fc9a6d3a7e](https://linux-hardware.org/?probe=fc9a6d3a7e) | Jan 25, 2023 |
| HP            | Laptop 17-cp0xxx            | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| ASUSTek       | K72Jr                       | [9b7c80b059](https://linux-hardware.org/?probe=9b7c80b059) | Jan 25, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | [dad68fd07f](https://linux-hardware.org/?probe=dad68fd07f) | Jan 24, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | [b61b0f981e](https://linux-hardware.org/?probe=b61b0f981e) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | [3194fb8316](https://linux-hardware.org/?probe=3194fb8316) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | [8e124bc501](https://linux-hardware.org/?probe=8e124bc501) | Jan 24, 2023 |
| Acer          | Aspire A715-51G             | [75362fb07d](https://linux-hardware.org/?probe=75362fb07d) | Jan 24, 2023 |
| Valve         | Jupiter                     | [8c427938e2](https://linux-hardware.org/?probe=8c427938e2) | Jan 24, 2023 |
| HP            | EliteBook 735 G6            | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| Valve         | Jupiter                     | [5ca72b0d88](https://linux-hardware.org/?probe=5ca72b0d88) | Jan 24, 2023 |
| Acer          | Aspire SW5-012              | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ZBook 15 G2                 | [5e4253b22d](https://linux-hardware.org/?probe=5e4253b22d) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | [b4b7ebe3f9](https://linux-hardware.org/?probe=b4b7ebe3f9) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| ASUSTek       | K72Jr                       | [54313c1c76](https://linux-hardware.org/?probe=54313c1c76) | Jan 23, 2023 |
| HP            | EliteBook 840 G4            | [459ab8ae3d](https://linux-hardware.org/?probe=459ab8ae3d) | Jan 23, 2023 |
| Medion        | E4251                       | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | [b2792832c2](https://linux-hardware.org/?probe=b2792832c2) | Jan 22, 2023 |
| Dell          | Latitude 5520               | [a3541758f7](https://linux-hardware.org/?probe=a3541758f7) | Jan 22, 2023 |
| ASUSTek       | GL553VD                     | [eeea0542b8](https://linux-hardware.org/?probe=eeea0542b8) | Jan 21, 2023 |
| Dell          | XPS 13 9310                 | [5d606f2c60](https://linux-hardware.org/?probe=5d606f2c60) | Jan 21, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| HP            | ProBook 650 G1              | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | Notebook                    | [63f0c0b90c](https://linux-hardware.org/?probe=63f0c0b90c) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [da0d1f442a](https://linux-hardware.org/?probe=da0d1f442a) | Jan 19, 2023 |
| HP            | ProBook 430 G1              | [3591fb1d6c](https://linux-hardware.org/?probe=3591fb1d6c) | Jan 19, 2023 |
| Acer          | Aspire A715-75G             | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Dell          | Latitude E6540              | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| Dell          | Precision M6800             | [62d01a5b26](https://linux-hardware.org/?probe=62d01a5b26) | Jan 18, 2023 |
| Dell          | Precision M6800             | [09e31ee1c8](https://linux-hardware.org/?probe=09e31ee1c8) | Jan 18, 2023 |
| Dell          | Latitude 5530               | [f9325236bb](https://linux-hardware.org/?probe=f9325236bb) | Jan 17, 2023 |
| Dell          | Latitude 5530               | [fafa35ef88](https://linux-hardware.org/?probe=fafa35ef88) | Jan 17, 2023 |
| HP            | ProBook 4540s               | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [856324369f](https://linux-hardware.org/?probe=856324369f) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| HP            | ProBook 4540s               | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| Dell          | XPS 15 9550                 | [4da81f73f5](https://linux-hardware.org/?probe=4da81f73f5) | Jan 16, 2023 |
| Google        | Banon                       | [6bb3ed04f9](https://linux-hardware.org/?probe=6bb3ed04f9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Acer          | Aspire 5680                 | [dc5f6d7ac6](https://linux-hardware.org/?probe=dc5f6d7ac6) | Jan 16, 2023 |
| HP            | Pavilion 17                 | [895f75daf7](https://linux-hardware.org/?probe=895f75daf7) | Jan 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | [57cd4eaca3](https://linux-hardware.org/?probe=57cd4eaca3) | Jan 15, 2023 |
| Acer          | Aspire 5736Z                | [bdfc087b4d](https://linux-hardware.org/?probe=bdfc087b4d) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| Dell          | Latitude E5410              | [909ca0fd93](https://linux-hardware.org/?probe=909ca0fd93) | Jan 14, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [116b26047d](https://linux-hardware.org/?probe=116b26047d) | Jan 14, 2023 |
| Apple         | MacBookAir5,2               | [c4cfa1aa47](https://linux-hardware.org/?probe=c4cfa1aa47) | Jan 13, 2023 |
| HP            | ZBook Studio G4             | [67168cc8a9](https://linux-hardware.org/?probe=67168cc8a9) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| realme        | CloudProXXXX                | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| Dell          | Latitude 3350               | [065c4a4a95](https://linux-hardware.org/?probe=065c4a4a95) | Jan 12, 2023 |
| Lenovo        | G770 1037                   | [da21020be1](https://linux-hardware.org/?probe=da21020be1) | Jan 12, 2023 |
| Notebook      | NS50MU                      | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| Standard      | Unknown                     | [b6f4b12847](https://linux-hardware.org/?probe=b6f4b12847) | Jan 12, 2023 |
| HP            | Pavilion dv9500             | [0f8c99e8d7](https://linux-hardware.org/?probe=0f8c99e8d7) | Jan 11, 2023 |
| Sony          | VPCEB3L9E                   | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| Dell          | XPS 15 9500                 | [69b3403f94](https://linux-hardware.org/?probe=69b3403f94) | Jan 10, 2023 |
| Acer          | Aspire 5735                 | [27b63fd8b1](https://linux-hardware.org/?probe=27b63fd8b1) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5663965a51](https://linux-hardware.org/?probe=5663965a51) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| Acer          | Aspire One 721              | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| Acer          | TravelMate P614-51-G2       | [0d0c035342](https://linux-hardware.org/?probe=0d0c035342) | Jan 08, 2023 |
| Lenovo        | ThinkPad Edge E145 20BC0... | [8ca4d7b38b](https://linux-hardware.org/?probe=8ca4d7b38b) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Medion        | E4251 MD61435               | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| HP            | Pavilion 17                 | [fe325358d6](https://linux-hardware.org/?probe=fe325358d6) | Jan 04, 2023 |
| Dell          | Latitude E6330              | [0341a89f2f](https://linux-hardware.org/?probe=0341a89f2f) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Apple         | MacBookAir7,2               | [2f148d690a](https://linux-hardware.org/?probe=2f148d690a) | Jan 03, 2023 |
| Acer          | Aspire E5-774               | [96c68886cf](https://linux-hardware.org/?probe=96c68886cf) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Acer          | Aspire V3-574G              | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1E70... | [e8b6dd6f1f](https://linux-hardware.org/?probe=e8b6dd6f1f) | Jan 01, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [d1f655b9b1](https://linux-hardware.org/?probe=d1f655b9b1) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [c87d61d0cd](https://linux-hardware.org/?probe=c87d61d0cd) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [bbf52af119](https://linux-hardware.org/?probe=bbf52af119) | Dec 31, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [fc108fb0d8](https://linux-hardware.org/?probe=fc108fb0d8) | Dec 31, 2022 |
| HP            | EliteBook 820 G4            | [9e794046d8](https://linux-hardware.org/?probe=9e794046d8) | Dec 30, 2022 |
| Acer          | Aspire 5680                 | [c14cfe5386](https://linux-hardware.org/?probe=c14cfe5386) | Dec 29, 2022 |
| Acer          | Aspire V3-772               | [9f431b484a](https://linux-hardware.org/?probe=9f431b484a) | Dec 29, 2022 |
| Alienware     | x17 R2                      | [5a7ea2683a](https://linux-hardware.org/?probe=5a7ea2683a) | Dec 28, 2022 |
| Dell          | Latitude 2120               | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Valve         | Jupiter                     | [488d26f3e8](https://linux-hardware.org/?probe=488d26f3e8) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| LG Electro... | 17Z90Q-G.AA79G              | [59d7266746](https://linux-hardware.org/?probe=59d7266746) | Dec 26, 2022 |
| Apple         | MacBookPro8,2               | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| Medion        | E4251 MD61435               | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| Toshiba       | Satellite C70D-B            | [82cc0b362d](https://linux-hardware.org/?probe=82cc0b362d) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | [b5c5aba33a](https://linux-hardware.org/?probe=b5c5aba33a) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF003QU... | [5145350f9a](https://linux-hardware.org/?probe=5145350f9a) | Dec 21, 2022 |
| Acer          | Aspire 5680                 | [9b188c358e](https://linux-hardware.org/?probe=9b188c358e) | Dec 21, 2022 |
| Valve         | Jupiter                     | [90331ea7da](https://linux-hardware.org/?probe=90331ea7da) | Dec 21, 2022 |
| Dell          | Latitude 5521               | [6fcbfd9271](https://linux-hardware.org/?probe=6fcbfd9271) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| ASUSTek       | N750JK                      | [8d876c21b0](https://linux-hardware.org/?probe=8d876c21b0) | Dec 18, 2022 |
| ASUSTek       | N750JK                      | [71575f3d8c](https://linux-hardware.org/?probe=71575f3d8c) | Dec 18, 2022 |
| Acer          | Aspire 5680                 | [64f5eb2f4b](https://linux-hardware.org/?probe=64f5eb2f4b) | Dec 17, 2022 |
| ASUSTek       | K50IE                       | [5681babfa5](https://linux-hardware.org/?probe=5681babfa5) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Acer          | Aspire E5-575               | [3fd939cef5](https://linux-hardware.org/?probe=3fd939cef5) | Dec 17, 2022 |
| Toshiba       | Satellite C70D-B            | [182e467ce6](https://linux-hardware.org/?probe=182e467ce6) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| Dell          | Latitude 3120               | [e886df2722](https://linux-hardware.org/?probe=e886df2722) | Dec 16, 2022 |
| Acer          | Nitro AN517-54              | [cb963df304](https://linux-hardware.org/?probe=cb963df304) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [de26ffa293](https://linux-hardware.org/?probe=de26ffa293) | Dec 14, 2022 |
| Dell          | Inspiron 15-3567            | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Acer          | Aspire 5742G                | [ee22896cd2](https://linux-hardware.org/?probe=ee22896cd2) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| Toshiba       | Satellite C70D-B            | [56adac1fcb](https://linux-hardware.org/?probe=56adac1fcb) | Dec 12, 2022 |
| Medion        | E4251                       | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Medion        | E4251                       | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Aspire 5742G                | [869e2a9671](https://linux-hardware.org/?probe=869e2a9671) | Dec 09, 2022 |
| HP            | Compaq Presario CQ71        | [503b61f120](https://linux-hardware.org/?probe=503b61f120) | Dec 09, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| Apple         | MacBookPro9,2               | [27dc9420ed](https://linux-hardware.org/?probe=27dc9420ed) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | [9b7c1953a6](https://linux-hardware.org/?probe=9b7c1953a6) | Dec 07, 2022 |
| Lenovo        | ThinkPad T510 4349AF5       | [a7d8d66fb7](https://linux-hardware.org/?probe=a7d8d66fb7) | Dec 07, 2022 |
| Dell          | XPS 9320                    | [34c3b0b6a0](https://linux-hardware.org/?probe=34c3b0b6a0) | Dec 06, 2022 |
| Medion        | E4251                       | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Acer          | Aspire 5742G                | [da82fb083d](https://linux-hardware.org/?probe=da82fb083d) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Acer          | Aspire V3-772               | [942312fe9e](https://linux-hardware.org/?probe=942312fe9e) | Dec 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [344b0c3082](https://linux-hardware.org/?probe=344b0c3082) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| Valve         | Jupiter                     | [d8890572a5](https://linux-hardware.org/?probe=d8890572a5) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| HP            | EliteBook 820 G4            | [b0437249b0](https://linux-hardware.org/?probe=b0437249b0) | Dec 03, 2022 |
| Packard Be... | EasyNote TE11HC             | [5864876eff](https://linux-hardware.org/?probe=5864876eff) | Dec 02, 2022 |
| Acer          | Iconia W4-820               | [cf25eeba85](https://linux-hardware.org/?probe=cf25eeba85) | Dec 01, 2022 |
| MSI           | GL62M 7RE                   | [5fcb394edb](https://linux-hardware.org/?probe=5fcb394edb) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | [29c5e0f7b1](https://linux-hardware.org/?probe=29c5e0f7b1) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| Lenovo        | 3000 V100 076346G           | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [dae405ee81](https://linux-hardware.org/?probe=dae405ee81) | Nov 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9216162e85](https://linux-hardware.org/?probe=9216162e85) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [39e771bd92](https://linux-hardware.org/?probe=39e771bd92) | Nov 28, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | [43fa54b5bc](https://linux-hardware.org/?probe=43fa54b5bc) | Nov 28, 2022 |
| Dell          | Latitude E6320              | [bcbdb4bf67](https://linux-hardware.org/?probe=bcbdb4bf67) | Nov 28, 2022 |
| Dell          | Latitude E6320              | [f77e444066](https://linux-hardware.org/?probe=f77e444066) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [4c6d3faf86](https://linux-hardware.org/?probe=4c6d3faf86) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [cd98ebccb9](https://linux-hardware.org/?probe=cd98ebccb9) | Nov 28, 2022 |
| Valve         | Jupiter                     | [81b0ea6c7a](https://linux-hardware.org/?probe=81b0ea6c7a) | Nov 27, 2022 |
| HP            | ProBook 5330m               | [3763f505a0](https://linux-hardware.org/?probe=3763f505a0) | Nov 27, 2022 |
| Valve         | Jupiter                     | [bee2852cb0](https://linux-hardware.org/?probe=bee2852cb0) | Nov 27, 2022 |
| HP            | EliteBook 830 G5            | [bda395e731](https://linux-hardware.org/?probe=bda395e731) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [0138561b29](https://linux-hardware.org/?probe=0138561b29) | Nov 26, 2022 |
| ASUSTek       | A6R                         | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [8de1db7f12](https://linux-hardware.org/?probe=8de1db7f12) | Nov 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [eaab6a8319](https://linux-hardware.org/?probe=eaab6a8319) | Nov 23, 2022 |
| Valve         | Jupiter                     | [6049221fab](https://linux-hardware.org/?probe=6049221fab) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | [4adc436e33](https://linux-hardware.org/?probe=4adc436e33) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | [84a0005ad3](https://linux-hardware.org/?probe=84a0005ad3) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| Dell          | Latitude 5401               | [f964652e0c](https://linux-hardware.org/?probe=f964652e0c) | Nov 22, 2022 |
| Dell          | Latitude E6530              | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| ASUSTek       | E200HA                      | [635e9fe863](https://linux-hardware.org/?probe=635e9fe863) | Nov 21, 2022 |
| Dell          | XPS 15 9510                 | [09e98d8c02](https://linux-hardware.org/?probe=09e98d8c02) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | [e80e97466d](https://linux-hardware.org/?probe=e80e97466d) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | [12799c9216](https://linux-hardware.org/?probe=12799c9216) | Nov 21, 2022 |
| Valve         | Jupiter                     | [1e7b9730a4](https://linux-hardware.org/?probe=1e7b9730a4) | Nov 21, 2022 |
| HP            | Unknown                     | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| HP            | Compaq Presario CQ71        | [52c86bac3f](https://linux-hardware.org/?probe=52c86bac3f) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| Acer          | Aspire 5742G                | [9c9af5a79e](https://linux-hardware.org/?probe=9c9af5a79e) | Nov 20, 2022 |
| Apple         | MacBookPro11,5              | [3b5c35b319](https://linux-hardware.org/?probe=3b5c35b319) | Nov 19, 2022 |
| HP            | Notebook                    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | [5170b27e5c](https://linux-hardware.org/?probe=5170b27e5c) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Apple         | MacBookPro11,5              | [62586ed7f9](https://linux-hardware.org/?probe=62586ed7f9) | Nov 16, 2022 |
| HP            | EliteBook 8570w             | [d5a16ba775](https://linux-hardware.org/?probe=d5a16ba775) | Nov 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 299       | 11.82%  |
| Ubuntu 22.04                 | 180       | 7.12%   |
| Ubuntu 18.04                 | 156       | 6.17%   |
| OpenMandriva 4.3             | 85        | 3.36%   |
| Zorin 16                     | 60        | 2.37%   |
| Debian 11                    | 56        | 2.21%   |
| Fedora 38                    | 44        | 1.74%   |
| Linux Mint 20.3              | 43        | 1.7%    |
| Pop!_OS 22.04                | 41        | 1.62%   |
| Arch Rolling                 | 40        | 1.58%   |
| openSUSE Tumbleweed-XXXXXXXX | 39        | 1.54%   |
| Arch                         | 38        | 1.5%    |
| Fedora 34                    | 37        | 1.46%   |
| Manjaro                      | 34        | 1.34%   |
| Linux Mint 20.2              | 33        | 1.3%    |
| Linux Mint 21.1              | 32        | 1.27%   |
| Fedora 36                    | 32        | 1.27%   |
| Fedora 37                    | 31        | 1.23%   |
| Xubuntu 20.04                | 30        | 1.19%   |
| Ubuntu 21.10                 | 28        | 1.11%   |
| KDE neon 20.04               | 26        | 1.03%   |
| Fedora 31                    | 26        | 1.03%   |
| Ubuntu 21.04                 | 25        | 0.99%   |
| Linux Mint 20.1              | 25        | 0.99%   |
| Fedora 35                    | 25        | 0.99%   |
| Pop!_OS 20.10                | 24        | 0.95%   |
| Linux Mint 21.2              | 24        | 0.95%   |
| Ubuntu 20.10                 | 23        | 0.91%   |
| Pop!_OS 21.04                | 23        | 0.91%   |
| Fedora 33                    | 23        | 0.91%   |
| Ubuntu 22.10                 | 22        | 0.87%   |
| Linux Mint 19.3              | 22        | 0.87%   |
| Fedora 32                    | 22        | 0.87%   |
| OpenMandriva 4.2             | 21        | 0.83%   |
| Zorin 15                     | 20        | 0.79%   |
| Pop!_OS 20.04                | 20        | 0.79%   |
| OpenMandriva 23.01           | 20        | 0.79%   |
| Debian 12                    | 20        | 0.79%   |
| ArcoLinux Rolling            | 20        | 0.79%   |
| Ubuntu 23.04                 | 19        | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 778       | 32.53%  |
| Fedora        | 234       | 9.78%   |
| Linux Mint    | 219       | 9.16%   |
| OpenMandriva  | 163       | 6.81%   |
| Pop!_OS       | 114       | 4.77%   |
| Debian        | 107       | 4.47%   |
| Manjaro       | 99        | 4.14%   |
| Zorin         | 85        | 3.55%   |
| Arch          | 77        | 3.22%   |
| Xubuntu       | 51        | 2.13%   |
| Kubuntu       | 50        | 2.09%   |
| openSUSE      | 49        | 2.05%   |
| KDE neon      | 41        | 1.71%   |
| SteamOS       | 24        | 1%      |
| Kali          | 22        | 0.92%   |
| Gentoo        | 21        | 0.88%   |
| EndeavourOS   | 21        | 0.88%   |
| ArcoLinux     | 21        | 0.88%   |
| Elementary    | 19        | 0.79%   |
| Lubuntu       | 18        | 0.75%   |
| Parrot        | 12        | 0.5%    |
| Clear Linux   | 12        | 0.5%    |
| Ubuntu MATE   | 11        | 0.46%   |
| ROSA          | 11        | 0.46%   |
| MX            | 11        | 0.46%   |
| Ubuntu Budgie | 10        | 0.42%   |
| LMDE          | 10        | 0.42%   |
| Ubuntu Unity  | 9         | 0.38%   |
| Peppermint    | 9         | 0.38%   |
| Solus         | 7         | 0.29%   |
| Endless       | 7         | 0.29%   |
| NixOS         | 5         | 0.21%   |
| Garuda Linux  | 5         | 0.21%   |
| RHEL          | 4         | 0.17%   |
| Xero          | 3         | 0.13%   |
| Oracle Linux  | 3         | 0.13%   |
| Chrome OS     | 3         | 0.13%   |
| CentOS        | 3         | 0.13%   |
| BlackPanther  | 3         | 0.13%   |
| Artix         | 3         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 85        | 3.04%   |
| 5.4.0-42-generic         | 30        | 1.07%   |
| 5.15.0-56-generic        | 23        | 0.82%   |
| 5.15.0-58-generic        | 22        | 0.79%   |
| 5.10.14-desktop-1omv4002 | 21        | 0.75%   |
| 5.4.0-58-generic         | 20        | 0.72%   |
| 5.15.0-46-generic        | 18        | 0.64%   |
| 5.11.0-38-generic        | 18        | 0.64%   |
| 5.8.0-50-generic         | 17        | 0.61%   |
| 5.4.0-48-generic         | 17        | 0.61%   |
| 5.15.0-43-generic        | 17        | 0.61%   |
| 5.8.0-43-generic         | 16        | 0.57%   |
| 6.2.6-desktop-1omv2390   | 15        | 0.54%   |
| 5.4.0-26-generic         | 15        | 0.54%   |
| 5.13.0-28-generic        | 15        | 0.54%   |
| 6.2.0-26-generic         | 14        | 0.5%    |
| 6.1.1-desktop-1omv2290   | 14        | 0.5%    |
| 5.4.0-29-generic         | 14        | 0.5%    |
| 5.15.0-60-generic        | 14        | 0.5%    |
| 5.8.0-53-generic         | 13        | 0.47%   |
| 5.4.0-77-generic         | 13        | 0.47%   |
| 5.4.0-52-generic         | 13        | 0.47%   |
| 5.4.0-33-generic         | 13        | 0.47%   |
| 5.15.0-52-generic        | 13        | 0.47%   |
| 5.15.0-48-generic        | 13        | 0.47%   |
| 5.11.0-27-generic        | 13        | 0.47%   |
| 6.2.0-37-generic         | 12        | 0.43%   |
| 6.2.0-36-generic         | 12        | 0.43%   |
| 5.8.0-7630-generic       | 12        | 0.43%   |
| 5.4.0-74-generic         | 12        | 0.43%   |
| 5.4.0-45-generic         | 12        | 0.43%   |
| 5.3.0-46-generic         | 12        | 0.43%   |
| 5.19.0-35-generic        | 12        | 0.43%   |
| 5.13.0-valve36-1-neptune | 11        | 0.39%   |
| 5.13.0-39-generic        | 11        | 0.39%   |
| 6.2.0-34-generic         | 10        | 0.36%   |
| 5.4.0-89-generic         | 10        | 0.36%   |
| 5.4.0-7634-generic       | 10        | 0.36%   |
| 5.4.0-65-generic         | 10        | 0.36%   |
| 5.4.0-37-generic         | 10        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 363       | 13.86%  |
| 5.15.0  | 242       | 9.24%   |
| 5.8.0   | 137       | 5.23%   |
| 4.15.0  | 125       | 4.77%   |
| 5.13.0  | 122       | 4.66%   |
| 5.11.0  | 121       | 4.62%   |
| 5.19.0  | 89        | 3.4%    |
| 6.2.0   | 86        | 3.28%   |
| 5.16.7  | 86        | 3.28%   |
| 5.10.0  | 72        | 2.75%   |
| 5.3.0   | 70        | 2.67%   |
| 5.0.0   | 54        | 2.06%   |
| 4.18.0  | 40        | 1.53%   |
| 6.1.0   | 36        | 1.37%   |
| 6.2.6   | 23        | 0.88%   |
| 5.10.14 | 22        | 0.84%   |
| 4.19.0  | 19        | 0.73%   |
| 6.1.1   | 17        | 0.65%   |
| 5.14.0  | 17        | 0.65%   |
| 6.5.0   | 15        | 0.57%   |
| 6.4.6   | 11        | 0.42%   |
| 5.6.0   | 11        | 0.42%   |
| 6.2.9   | 10        | 0.38%   |
| 6.4.11  | 9         | 0.34%   |
| 6.3.0   | 9         | 0.34%   |
| 6.0.0   | 9         | 0.34%   |
| 5.9.16  | 9         | 0.34%   |
| 6.5.6   | 8         | 0.31%   |
| 6.0.6   | 8         | 0.31%   |
| 5.17.1  | 8         | 0.31%   |
| 6.6.2   | 7         | 0.27%   |
| 6.2.10  | 7         | 0.27%   |
| 6.1.4   | 7         | 0.27%   |
| 5.4.8   | 7         | 0.27%   |
| 5.18.0  | 7         | 0.27%   |
| 5.17.0  | 7         | 0.27%   |
| 4.4.0   | 7         | 0.27%   |
| 6.6.7   | 6         | 0.23%   |
| 6.5.8   | 6         | 0.23%   |
| 6.1.11  | 6         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 401       | 15.5%   |
| 5.15    | 298       | 11.52%  |
| 5.8     | 167       | 6.46%   |
| 5.11    | 151       | 5.84%   |
| 5.13    | 148       | 5.72%   |
| 6.2     | 147       | 5.68%   |
| 4.15    | 125       | 4.83%   |
| 5.10    | 123       | 4.75%   |
| 5.16    | 116       | 4.48%   |
| 5.19    | 112       | 4.33%   |
| 6.1     | 100       | 3.87%   |
| 5.3     | 88        | 3.4%    |
| 5.0     | 57        | 2.2%    |
| 6.5     | 49        | 1.89%   |
| 6.0     | 49        | 1.89%   |
| 5.17    | 46        | 1.78%   |
| 5.14    | 45        | 1.74%   |
| 4.18    | 45        | 1.74%   |
| 6.3     | 40        | 1.55%   |
| 6.4     | 35        | 1.35%   |
| 5.9     | 32        | 1.24%   |
| 5.18    | 31        | 1.2%    |
| 5.6     | 30        | 1.16%   |
| 6.6     | 26        | 1.01%   |
| 5.7     | 23        | 0.89%   |
| 5.12    | 23        | 0.89%   |
| 4.19    | 23        | 0.89%   |
| 5.5     | 15        | 0.58%   |
| 4.9     | 11        | 0.43%   |
| 4.4     | 8         | 0.31%   |
| 5.2     | 6         | 0.23%   |
| 4.16    | 3         | 0.12%   |
| 4.12    | 3         | 0.12%   |
| 4.10    | 3         | 0.12%   |
| 4.20    | 2         | 0.08%   |
| 5.17.1  | 1         | 0.04%   |
| 5.1     | 1         | 0.04%   |
| 4.7     | 1         | 0.04%   |
| 4.17    | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2252      | 97.32%  |
| i686    | 61        | 2.64%   |
| aarch64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1114      | 46.09%  |
| KDE5             | 424       | 17.54%  |
| Unknown          | 262       | 10.84%  |
| X-Cinnamon       | 176       | 7.28%   |
| XFCE             | 173       | 7.16%   |
| MATE             | 55        | 2.28%   |
| KDE              | 51        | 2.11%   |
| Cinnamon         | 23        | 0.95%   |
| Pantheon         | 19        | 0.79%   |
| LXQt             | 18        | 0.74%   |
| Budgie           | 16        | 0.66%   |
| i3               | 15        | 0.62%   |
| LXDE             | 14        | 0.58%   |
| Unity            | 9         | 0.37%   |
| KDE4             | 7         | 0.29%   |
| GNOME Flashback  | 7         | 0.29%   |
| sway             | 5         | 0.21%   |
| icewm            | 5         | 0.21%   |
| Deepin           | 4         | 0.17%   |
| qtile            | 3         | 0.12%   |
| openbox          | 2         | 0.08%   |
| GNOME Classic    | 2         | 0.08%   |
| awesome          | 2         | 0.08%   |
| xmonad           | 1         | 0.04%   |
| Trinity          | 1         | 0.04%   |
| none+i3          | 1         | 0.04%   |
| lightdm-xsession | 1         | 0.04%   |
| herbstluftwm     | 1         | 0.04%   |
| gamescope        | 1         | 0.04%   |
| fluxbox          | 1         | 0.04%   |
| enlightenment    | 1         | 0.04%   |
| DWM              | 1         | 0.04%   |
| Core             | 1         | 0.04%   |
| bspwm            | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1698      | 71.25%  |
| Wayland | 519       | 21.78%  |
| Unknown | 140       | 5.87%   |
| Tty     | 26        | 1.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1131      | 47.2%   |
| SDDM    | 328       | 13.69%  |
| GDM3    | 318       | 13.27%  |
| GDM     | 311       | 12.98%  |
| LightDM | 244       | 10.18%  |
| TDM     | 47        | 1.96%   |
| KDM     | 7         | 0.29%   |
| XDM     | 4         | 0.17%   |
| GREETD  | 2         | 0.08%   |
| SLiM    | 1         | 0.04%   |
| NODM    | 1         | 0.04%   |
| Ly      | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 1212      | 50.92%  |
| nl_NL       | 602       | 25.29%  |
| Unknown     | 228       | 9.58%   |
| en_GB       | 114       | 4.79%   |
| C           | 27        | 1.13%   |
| ru_RU       | 26        | 1.09%   |
| pl_PL       | 26        | 1.09%   |
| de_DE       | 24        | 1.01%   |
| POSIX       | 11        | 0.46%   |
| en_NL       | 10        | 0.42%   |
| fr_FR       | 9         | 0.38%   |
| en_IE       | 7         | 0.29%   |
| it_IT       | 6         | 0.25%   |
| en_IN       | 6         | 0.25%   |
| nl_BE       | 5         | 0.21%   |
| es_ES       | 5         | 0.21%   |
| es_MX       | 4         | 0.17%   |
| en_DK       | 4         | 0.17%   |
| sk_SK       | 3         | 0.13%   |
| pt_PT       | 3         | 0.13%   |
| nb_NO       | 3         | 0.13%   |
| en_CA       | 3         | 0.13%   |
| cs_CZ       | 3         | 0.13%   |
| zh_CN       | 2         | 0.08%   |
| uk_UA       | 2         | 0.08%   |
| sv_SE       | 2         | 0.08%   |
| hu_HU       | 2         | 0.08%   |
| fr_BE       | 2         | 0.08%   |
| en_ZA       | 2         | 0.08%   |
| en_US.utf-8 | 2         | 0.08%   |
| en_SG       | 2         | 0.08%   |
| en_AG       | 2         | 0.08%   |
| ca_ES       | 2         | 0.08%   |
| tr_TR       | 1         | 0.04%   |
| ru_UA       | 1         | 0.04%   |
| ro_RO       | 1         | 0.04%   |
| pt_BR       | 1         | 0.04%   |
| nl_AW       | 1         | 0.04%   |
| lt_LT       | 1         | 0.04%   |
| hr_HR       | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1313      | 55.31%  |
| BIOS | 1061      | 44.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1728      | 72.57%  |
| Btrfs   | 276       | 11.59%  |
| Overlay | 178       | 7.48%   |
| Tmpfs   | 78        | 3.28%   |
| Unknown | 62        | 2.6%    |
| Xfs     | 30        | 1.26%   |
| Zfs     | 15        | 0.63%   |
| F2fs    | 6         | 0.25%   |
| Ext2    | 3         | 0.13%   |
| Ext3    | 2         | 0.08%   |
| Aufs    | 2         | 0.08%   |
| Jfs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1218      | 51.54%  |
| GPT     | 965       | 40.84%  |
| MBR     | 180       | 7.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2057      | 87.27%  |
| Yes       | 300       | 12.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1735      | 74.08%  |
| Yes       | 607       | 25.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Hewlett-Packard      | 458       | 19.82%  |
| Dell                 | 448       | 19.39%  |
| Lenovo               | 425       | 18.39%  |
| ASUSTek Computer     | 222       | 9.61%   |
| Acer                 | 200       | 8.65%   |
| Apple                | 84        | 3.63%   |
| Toshiba              | 59        | 2.55%   |
| Notebook             | 58        | 2.51%   |
| MSI                  | 48        | 2.08%   |
| Medion               | 30        | 1.3%    |
| Samsung Electronics  | 24        | 1.04%   |
| Packard Bell         | 23        | 1%      |
| Valve                | 22        | 0.95%   |
| Sony                 | 17        | 0.74%   |
| Google               | 17        | 0.74%   |
| Fujitsu              | 17        | 0.74%   |
| HUAWEI               | 15        | 0.65%   |
| Alienware            | 9         | 0.39%   |
| Unknown              | 9         | 0.39%   |
| Fujitsu Siemens      | 7         | 0.3%    |
| TUXEDO               | 6         | 0.26%   |
| Timi                 | 6         | 0.26%   |
| Insyde               | 6         | 0.26%   |
| Gigabyte Technology  | 6         | 0.26%   |
| System76             | 5         | 0.22%   |
| PC Specialist        | 5         | 0.22%   |
| Chuwi                | 5         | 0.22%   |
| SLIMBOOK             | 4         | 0.17%   |
| TrekStor             | 3         | 0.13%   |
| SKIKK                | 3         | 0.13%   |
| Intel Client Systems | 3         | 0.13%   |
| Intel                | 3         | 0.13%   |
| Hampoo               | 3         | 0.13%   |
| Framework            | 3         | 0.13%   |
| Clevo                | 3         | 0.13%   |
| VALE                 | 2         | 0.09%   |
| Toxic                | 2         | 0.09%   |
| TongFang             | 2         | 0.09%   |
| Standard             | 2         | 0.09%   |
| Schenker             | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Dell Latitude 3310                    | 32        | 1.38%   |
| Valve Jupiter                         | 22        | 0.95%   |
| Unknown                               | 19        | 0.82%   |
| Dell XPS 15 7590                      | 13        | 0.56%   |
| HP Notebook                           | 11        | 0.48%   |
| Dell XPS 15 9500                      | 10        | 0.43%   |
| Apple MacBookPro9,2                   | 10        | 0.43%   |
| HP Pavilion dv7                       | 9         | 0.39%   |
| Dell XPS 15 9560                      | 9         | 0.39%   |
| Dell Latitude E6410                   | 9         | 0.39%   |
| HP ZBook Studio G5                    | 8         | 0.35%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 8         | 0.35%   |
| HP Pavilion g7                        | 8         | 0.35%   |
| HP Pavilion g6                        | 8         | 0.35%   |
| Dell XPS 13 9310                      | 8         | 0.35%   |
| Dell Latitude 3300                    | 8         | 0.35%   |
| Dell Latitude 3189                    | 8         | 0.35%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 7         | 0.3%    |
| HP ProBook 6570b                      | 7         | 0.3%    |
| HP Pavilion Laptop 15-cw1xxx          | 7         | 0.3%    |
| HP Pavilion dv6                       | 7         | 0.3%    |
| HP EliteBook 8570w                    | 7         | 0.3%    |
| Lenovo Legion 5 Pro 16ACH6H 82JQ      | 6         | 0.26%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 6         | 0.26%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 6         | 0.26%   |
| HP ProBook 650 G1                     | 6         | 0.26%   |
| HP EliteBook 8460p                    | 6         | 0.26%   |
| Dell XPS 15 9570                      | 6         | 0.26%   |
| Dell XPS 15 9550                      | 6         | 0.26%   |
| Dell XPS 13 9360                      | 6         | 0.26%   |
| Dell Latitude E6420                   | 6         | 0.26%   |
| Dell Latitude E6320                   | 6         | 0.26%   |
| Dell Latitude D630                    | 6         | 0.26%   |
| Apple MacBookPro8,1                   | 6         | 0.26%   |
| Apple MacBookPro12,1                  | 6         | 0.26%   |
| Apple MacBookAir7,2                   | 6         | 0.26%   |
| Lenovo Yoga Slim 7 13ACN5 82CY        | 5         | 0.22%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 5         | 0.22%   |
| HP ZBook 15 G3                        | 5         | 0.22%   |
| HP ProBook 6550b                      | 5         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 244       | 10.56%  |
| Lenovo ThinkPad       | 236       | 10.21%  |
| Acer Aspire           | 144       | 6.23%   |
| HP EliteBook          | 115       | 4.98%   |
| Dell XPS              | 99        | 4.28%   |
| HP Pavilion           | 96        | 4.15%   |
| Lenovo IdeaPad        | 86        | 3.72%   |
| HP ProBook            | 76        | 3.29%   |
| Toshiba Satellite     | 55        | 2.38%   |
| Dell Inspiron         | 44        | 1.9%    |
| HP ZBook              | 38        | 1.64%   |
| HP Compaq             | 36        | 1.56%   |
| ASUS VivoBook         | 32        | 1.38%   |
| Lenovo Legion         | 31        | 1.34%   |
| Dell Precision        | 27        | 1.17%   |
| HP Laptop             | 24        | 1.04%   |
| Valve Jupiter         | 22        | 0.95%   |
| Packard Bell EasyNote | 22        | 0.95%   |
| Lenovo ThinkBook      | 20        | 0.87%   |
| Unknown               | 19        | 0.82%   |
| ASUS ROG              | 17        | 0.74%   |
| Lenovo Yoga           | 16        | 0.69%   |
| Fujitsu LIFEBOOK      | 16        | 0.69%   |
| Acer TravelMate       | 15        | 0.65%   |
| Acer Swift            | 15        | 0.65%   |
| ASUS ZenBook          | 14        | 0.61%   |
| HP Notebook           | 11        | 0.48%   |
| Apple MacBookPro9     | 11        | 0.48%   |
| Apple MacBookPro8     | 11        | 0.48%   |
| HP OMEN               | 10        | 0.43%   |
| Apple MacBookPro11    | 10        | 0.43%   |
| HP ENVY               | 9         | 0.39%   |
| Dell System           | 9         | 0.39%   |
| Dell Vostro           | 8         | 0.35%   |
| Dell Studio           | 7         | 0.3%    |
| Apple MacBookAir7     | 7         | 0.3%    |
| Acer Nitro            | 7         | 0.3%    |
| ASUS ASUS             | 6         | 0.26%   |
| Apple MacBookPro5     | 6         | 0.26%   |
| Apple MacBookPro12    | 6         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 268       | 11.6%   |
| 2020    | 195       | 8.44%   |
| 2018    | 194       | 8.39%   |
| 2021    | 180       | 7.79%   |
| 2012    | 172       | 7.44%   |
| 2011    | 150       | 6.49%   |
| 2013    | 144       | 6.23%   |
| 2017    | 142       | 6.14%   |
| 2010    | 125       | 5.41%   |
| 2015    | 124       | 5.37%   |
| 2014    | 113       | 4.89%   |
| 2016    | 112       | 4.85%   |
| 2022    | 106       | 4.59%   |
| 2008    | 87        | 3.76%   |
| 2009    | 78        | 3.38%   |
| 2007    | 66        | 2.86%   |
| 2023    | 32        | 1.38%   |
| 2006    | 17        | 0.74%   |
| 2005    | 3         | 0.13%   |
| Unknown | 2         | 0.09%   |
| 2004    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2311      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2068      | 88.68%  |
| Enabled  | 264       | 11.32%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2287      | 98.96%  |
| Yes  | 24        | 1.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 601       | 25.68%  |
| 3.01-4.0    | 478       | 20.43%  |
| 16.01-24.0  | 425       | 18.16%  |
| 8.01-16.0   | 392       | 16.75%  |
| 32.01-64.0  | 195       | 8.33%   |
| 1.01-2.0    | 93        | 3.97%   |
| 2.01-3.0    | 56        | 2.39%   |
| 24.01-32.0  | 42        | 1.79%   |
| 64.01-256.0 | 39        | 1.67%   |
| 0.51-1.0    | 19        | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 871       | 33.92%  |
| 2.01-3.0   | 649       | 25.27%  |
| 4.01-8.0   | 383       | 14.91%  |
| 3.01-4.0   | 340       | 13.24%  |
| 0.51-1.0   | 155       | 6.04%   |
| 8.01-16.0  | 134       | 5.22%   |
| 16.01-24.0 | 19        | 0.74%   |
| 0.01-0.5   | 13        | 0.51%   |
| 24.01-32.0 | 3         | 0.12%   |
| 32.01-64.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1692      | 71.76%  |
| 2      | 552       | 23.41%  |
| 3      | 68        | 2.88%   |
| 0      | 35        | 1.48%   |
| 4      | 8         | 0.34%   |
| 5      | 2         | 0.08%   |
| 7      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1559      | 67.14%  |
| Yes       | 763       | 32.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1854      | 79.95%  |
| No        | 465       | 20.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2258      | 97.62%  |
| No        | 55        | 2.38%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1808      | 77%     |
| No        | 540       | 23%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Netherlands | 2311      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Amsterdam              | 448       | 18.25%  |
| The Hague              | 124       | 5.05%   |
| Rotterdam              | 84        | 3.42%   |
| Utrecht                | 65        | 2.65%   |
| Delft                  | 61        | 2.48%   |
| Schagen                | 58        | 2.36%   |
| Haarlem                | 52        | 2.12%   |
| Naaldwijk              | 42        | 1.71%   |
| Eindhoven              | 42        | 1.71%   |
| Groningen              | 39        | 1.59%   |
| Almere Stad            | 33        | 1.34%   |
| Tilburg                | 27        | 1.1%    |
| Enschede               | 27        | 1.1%    |
| Amersfoort             | 26        | 1.06%   |
| Leiden                 | 23        | 0.94%   |
| Apeldoorn              | 20        | 0.81%   |
| Zoetermeer             | 18        | 0.73%   |
| Heerlen                | 18        | 0.73%   |
| Nijmegen               | 17        | 0.69%   |
| Breda                  | 17        | 0.69%   |
| Amstelveen             | 16        | 0.65%   |
| Zwolle                 | 15        | 0.61%   |
| Arnhem                 | 15        | 0.61%   |
| Zeist                  | 14        | 0.57%   |
| Maastricht             | 14        | 0.57%   |
| Capelle aan den IJssel | 14        | 0.57%   |
| Almelo                 | 14        | 0.57%   |
| Roosendaal             | 13        | 0.53%   |
| Dordrecht              | 13        | 0.53%   |
| Alkmaar                | 13        | 0.53%   |
| Meppel                 | 12        | 0.49%   |
| Gouda                  | 12        | 0.49%   |
| Rijswijk               | 11        | 0.45%   |
| Oss                    | 11        | 0.45%   |
| Leeuwarden             | 11        | 0.45%   |
| Hilversum              | 11        | 0.45%   |
| 's-Hertogenbosch       | 11        | 0.45%   |
| Purmerend              | 10        | 0.41%   |
| Nieuwegein             | 10        | 0.41%   |
| Lelystad               | 10        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 643       | 934    | 22.73%  |
| WDC                         | 249       | 313    | 8.8%    |
| Seagate                     | 230       | 290    | 8.13%   |
| Toshiba                     | 197       | 244    | 6.96%   |
| SanDisk                     | 175       | 212    | 6.19%   |
| SK hynix                    | 168       | 206    | 5.94%   |
| Unknown                     | 160       | 190    | 5.66%   |
| Kingston                    | 158       | 199    | 5.59%   |
| Intel                       | 98        | 121    | 3.46%   |
| Crucial                     | 96        | 117    | 3.39%   |
| Hitachi                     | 90        | 104    | 3.18%   |
| Micron Technology           | 76        | 91     | 2.69%   |
| HGST                        | 71        | 91     | 2.51%   |
| Apple                       | 46        | 68     | 1.63%   |
| KIOXIA                      | 38        | 39     | 1.34%   |
| LITEON                      | 34        | 44     | 1.2%    |
| A-DATA Technology           | 23        | 25     | 0.81%   |
| LITEONIT                    | 21        | 23     | 0.74%   |
| Fujitsu                     | 20        | 22     | 0.71%   |
| Phison                      | 15        | 23     | 0.53%   |
| China                       | 12        | 23     | 0.42%   |
| Unknown                     | 12        | 13     | 0.42%   |
| Phison Electronics          | 10        | 15     | 0.35%   |
| OCZ                         | 10        | 13     | 0.35%   |
| PNY                         | 9         | 10     | 0.32%   |
| Intenso                     | 9         | 9      | 0.32%   |
| GOODRAM                     | 8         | 8      | 0.28%   |
| SPCC                        | 7         | 7      | 0.25%   |
| Kingston Technology Company | 7         | 9      | 0.25%   |
| Transcend                   | 6         | 7      | 0.21%   |
| O2 Micro                    | 6         | 6      | 0.21%   |
| KingFast                    | 6         | 10     | 0.21%   |
| Corsair                     | 6         | 6      | 0.21%   |
| ASMT                        | 6         | 7      | 0.21%   |
| SSSTC                       | 5         | 6      | 0.18%   |
| JMicron Technology          | 5         | 5      | 0.18%   |
| Union Memory (Shenzhen)     | 4         | 4      | 0.14%   |
| Netac                       | 4         | 4      | 0.14%   |
| Micron/Crucial Technology   | 4         | 6      | 0.14%   |
| Gigabyte Technology         | 4         | 6      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 38        | 1.28%   |
| Samsung SSD 850 EVO 250GB                           | 32        | 1.08%   |
| Unknown MMC Card  32GB                              | 31        | 1.04%   |
| HGST HTS721010A9E630 1TB                            | 26        | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                      | 24        | 0.81%   |
| Seagate ST9500325AS 500GB                           | 21        | 0.71%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.71%   |
| Unknown MMC Card  64GB                              | 20        | 0.67%   |
| Toshiba MQ01ABF050 500GB                            | 20        | 0.67%   |
| Samsung SSD 850 EVO 500GB                           | 20        | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 20        | 0.67%   |
| Kingston SA400S37240G 240GB SSD                     | 20        | 0.67%   |
| Samsung SSD 860 EVO 500GB                           | 18        | 0.61%   |
| Samsung NVMe SSD Drive 1TB                          | 18        | 0.61%   |
| Toshiba MQ01ABD100 1TB                              | 17        | 0.57%   |
| SanDisk NVMe SSD Drive 512GB                        | 17        | 0.57%   |
| Samsung SSD 980 1TB                                 | 17        | 0.57%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 17        | 0.57%   |
| Samsung NVMe SSD Drive 512GB                        | 16        | 0.54%   |
| Samsung NVMe SSD Drive 500GB                        | 15        | 0.5%    |
| Samsung NVMe SSD Drive 1024GB                       | 15        | 0.5%    |
| Toshiba NVMe SSD Drive 512GB                        | 14        | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                     | 13        | 0.44%   |
| Samsung SSD 840 EVO 250GB                           | 13        | 0.44%   |
| HGST HTS725050A7E630 500GB                          | 13        | 0.44%   |
| Toshiba NVMe SSD Drive 256GB                        | 12        | 0.4%    |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.4%    |
| Seagate Expansion 2TB                               | 12        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                        | 12        | 0.4%    |
| Kingston SV300S37A120G 120GB SSD                    | 12        | 0.4%    |
| HGST HTS541010A9E680 1TB                            | 12        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                        | 12        | 0.4%    |
| Unknown                                             | 12        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 11        | 0.37%   |
| SanDisk NVMe SSD Drive 256GB                        | 11        | 0.37%   |
| Samsung SSD 860 EVO 1TB                             | 11        | 0.37%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 11        | 0.37%   |
| Seagate ST1000LM049-2GH172 1TB                      | 10        | 0.34%   |
| Samsung SSD 970 EVO 1TB                             | 10        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 226       | 283    | 31.83%  |
| WDC                 | 160       | 190    | 22.54%  |
| Toshiba             | 108       | 139    | 15.21%  |
| Hitachi             | 90        | 104    | 12.68%  |
| HGST                | 71        | 91     | 10%     |
| Fujitsu             | 20        | 22     | 2.82%   |
| Samsung Electronics | 15        | 17     | 2.11%   |
| Unknown             | 4         | 4      | 0.56%   |
| ASMT                | 3         | 4      | 0.42%   |
| Apple               | 3         | 4      | 0.42%   |
| SABRENT             | 2         | 2      | 0.28%   |
| External            | 2         | 4      | 0.28%   |
| USB3.0              | 1         | 1      | 0.14%   |
| StoreJet            | 1         | 1      | 0.14%   |
| SSK                 | 1         | 1      | 0.14%   |
| KESU                | 1         | 1      | 0.14%   |
| Intenso             | 1         | 1      | 0.14%   |
| HGST HTS            | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 303       | 426    | 30.76%  |
| Kingston            | 118       | 147    | 11.98%  |
| Crucial             | 91        | 111    | 9.24%   |
| SanDisk             | 90        | 103    | 9.14%   |
| SK hynix            | 41        | 55     | 4.16%   |
| WDC                 | 35        | 56     | 3.55%   |
| Micron Technology   | 33        | 42     | 3.35%   |
| Intel               | 31        | 33     | 3.15%   |
| Apple               | 31        | 43     | 3.15%   |
| LITEON              | 26        | 36     | 2.64%   |
| LITEONIT            | 21        | 23     | 2.13%   |
| Toshiba             | 20        | 26     | 2.03%   |
| A-DATA Technology   | 19        | 21     | 1.93%   |
| China               | 12        | 23     | 1.22%   |
| OCZ                 | 10        | 13     | 1.02%   |
| PNY                 | 9         | 10     | 0.91%   |
| Intenso             | 8         | 8      | 0.81%   |
| GOODRAM             | 8         | 8      | 0.81%   |
| SPCC                | 7         | 7      | 0.71%   |
| Corsair             | 6         | 6      | 0.61%   |
| Transcend           | 5         | 6      | 0.51%   |
| Netac               | 4         | 4      | 0.41%   |
| KingFast            | 4         | 6      | 0.41%   |
| JMicron Technology  | 4         | 4      | 0.41%   |
| Team                | 3         | 5      | 0.3%    |
| KingSpec            | 3         | 3      | 0.3%    |
| ASMT                | 3         | 3      | 0.3%    |
| Vaseky              | 2         | 2      | 0.2%    |
| Unknown             | 2         | 2      | 0.2%    |
| SSSTC               | 2         | 2      | 0.2%    |
| Phison              | 2         | 8      | 0.2%    |
| Patriot             | 2         | 4      | 0.2%    |
| KingDian            | 2         | 3      | 0.2%    |
| WDC WDS2            | 1         | 1      | 0.1%    |
| WALRAM              | 1         | 1      | 0.1%    |
| ValueTech           | 1         | 1      | 0.1%    |
| TrekStor            | 1         | 1      | 0.1%    |
| Teclast             | 1         | 2      | 0.1%    |
| Seagate             | 1         | 1      | 0.1%    |
| Reeinno             | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 925       | 1256   | 34.01%  |
| SSD     | 925       | 1281   | 34.01%  |
| HDD     | 684       | 870    | 25.15%  |
| MMC     | 168       | 197    | 6.18%   |
| Unknown | 18        | 21     | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1408      | 2038   | 53.95%  |
| NVMe | 924       | 1252   | 35.4%   |
| MMC  | 168       | 197    | 6.44%   |
| SAS  | 110       | 138    | 4.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1158      | 1576   | 73.01%  |
| 0.51-1.0   | 352       | 471    | 22.19%  |
| 1.01-2.0   | 62        | 83     | 3.91%   |
| 4.01-10.0  | 8         | 10     | 0.5%    |
| 3.01-4.0   | 5         | 10     | 0.32%   |
| 2.01-3.0   | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 715       | 29.27%  |
| 251-500        | 575       | 23.54%  |
| 501-1000       | 319       | 13.06%  |
| 1-20           | 224       | 9.17%   |
| 51-100         | 169       | 6.92%   |
| 1001-2000      | 168       | 6.88%   |
| 21-50          | 113       | 4.63%   |
| Unknown        | 65        | 2.66%   |
| More than 3000 | 58        | 2.37%   |
| 2001-3000      | 37        | 1.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 999       | 39.39%  |
| 21-50          | 447       | 17.63%  |
| 101-250        | 339       | 13.37%  |
| 51-100         | 297       | 11.71%  |
| 251-500        | 205       | 8.08%   |
| 501-1000       | 112       | 4.42%   |
| Unknown        | 65        | 2.56%   |
| 1001-2000      | 45        | 1.77%   |
| More than 3000 | 15        | 0.59%   |
| 2001-3000      | 11        | 0.43%   |
| 0              | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB              | 5         | 6      | 4.63%   |
| Seagate ST9250410AS 250GB             | 3         | 3      | 2.78%   |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 2.78%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 1.85%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 1.85%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 1.85%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 1.85%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 1.85%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 1.85%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 1.85%   |
| Intel SSDMAEXC024G3H 24GB             | 2         | 2      | 1.85%   |
| Hitachi HTS725050A7E630 500GB         | 2         | 3      | 1.85%   |
| Fujitsu MHZ2320BH G2 320GB            | 2         | 2      | 1.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.93%   |
| WDC WD7500BPVT-08HXZT3 752GB          | 1         | 1      | 0.93%   |
| WDC WD600UE-22HCT0 64GB               | 1         | 1      | 0.93%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 0.93%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 1      | 0.93%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.93%   |
| WDC WD2500BEVT-22ZCT0 250GB           | 1         | 1      | 0.93%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 0.93%   |
| WDC WD1600BEVT-22A23T0 160GB          | 1         | 1      | 0.93%   |
| WDC WD10SPZX-24Z10T0 1TB              | 1         | 1      | 0.93%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 0.93%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD  | 1         | 1      | 0.93%   |
| Toshiba MK5061GSYN 500GB              | 1         | 1      | 0.93%   |
| Toshiba MK3265GSX 320GB               | 1         | 1      | 0.93%   |
| Toshiba MK1252GSX 120GB               | 1         | 1      | 0.93%   |
| Toshiba MK1234GSX 120GB               | 1         | 1      | 0.93%   |
| SK hynix SC401 SATA 512GB SSD         | 1         | 1      | 0.93%   |
| SK hynix SC210 mSATA 256GB SSD        | 1         | 1      | 0.93%   |
| SK hynix HFS256G32TND-N210A 256GB SSD | 1         | 1      | 0.93%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 0.93%   |
| Seagate ST9320320AS 320GB             | 1         | 1      | 0.93%   |
| Seagate ST9200420ASG 200GB            | 1         | 2      | 0.93%   |
| Seagate ST9160821A 137GB              | 1         | 1      | 0.93%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 0.93%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 0.93%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 16        | 17     | 14.81%  |
| HGST                        | 12        | 14     | 11.11%  |
| WDC                         | 11        | 11     | 10.19%  |
| Hitachi                     | 11        | 12     | 10.19%  |
| Toshiba                     | 9         | 9      | 8.33%   |
| SK hynix                    | 6         | 6      | 5.56%   |
| Kingston                    | 6         | 8      | 5.56%   |
| Intel                       | 6         | 6      | 5.56%   |
| SanDisk                     | 5         | 5      | 4.63%   |
| Samsung Electronics         | 4         | 4      | 3.7%    |
| Micron Technology           | 4         | 4      | 3.7%    |
| Fujitsu                     | 4         | 4      | 3.7%    |
| LITEON                      | 3         | 6      | 2.78%   |
| Crucial                     | 2         | 2      | 1.85%   |
| Realtek                     | 1         | 1      | 0.93%   |
| OCZ                         | 1         | 1      | 0.93%   |
| Micron/Crucial Technology   | 1         | 1      | 0.93%   |
| Kingston Technology Company | 1         | 1      | 0.93%   |
| Intenso                     | 1         | 1      | 0.93%   |
| GOODRAM                     | 1         | 1      | 0.93%   |
| Corsair                     | 1         | 1      | 0.93%   |
| Apple                       | 1         | 1      | 0.93%   |
| A-DATA Technology           | 1         | 1      | 0.93%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 17     | 25.4%   |
| HGST                | 12        | 14     | 19.05%  |
| Hitachi             | 11        | 12     | 17.46%  |
| WDC                 | 10        | 10     | 15.87%  |
| Toshiba             | 8         | 8      | 12.7%   |
| Fujitsu             | 4         | 4      | 6.35%   |
| Samsung Electronics | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 67     | 59.43%  |
| SSD  | 36        | 42     | 33.96%  |
| NVMe | 7         | 8      | 6.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Toshiba MK5065GSXN 500GB     | 1         | 1      | 50%     |
| Crucial M4-CT256M4SSD3 256GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Crucial | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1465      | 2338   | 60.19%  |
| Works    | 862       | 1168   | 35.41%  |
| Malfunc  | 105       | 117    | 4.31%   |
| Failed   | 2         | 2      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1560      | 57.35%  |
| Samsung Electronics                     | 377       | 13.86%  |
| AMD                                     | 174       | 6.4%    |
| SanDisk                                 | 134       | 4.93%   |
| SK hynix                                | 125       | 4.6%    |
| Toshiba America Info Systems            | 76        | 2.79%   |
| Kingston Technology Company             | 47        | 1.73%   |
| Micron Technology                       | 43        | 1.58%   |
| KIOXIA                                  | 38        | 1.4%    |
| Nvidia                                  | 27        | 0.99%   |
| Phison Electronics                      | 26        | 0.96%   |
| Silicon Integrated Systems [SiS]        | 13        | 0.48%   |
| Apple                                   | 13        | 0.48%   |
| Lite-On Technology                      | 11        | 0.4%    |
| Micron/Crucial Technology               | 8         | 0.29%   |
| Union Memory (Shenzhen)                 | 6         | 0.22%   |
| Solid State Storage Technology          | 6         | 0.22%   |
| O2 Micro                                | 6         | 0.22%   |
| Realtek Semiconductor                   | 4         | 0.15%   |
| VIA Technologies                        | 3         | 0.11%   |
| Seagate Technology                      | 3         | 0.11%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.11%   |
| JMicron Technology                      | 3         | 0.11%   |
| Silicon Motion                          | 2         | 0.07%   |
| Shenzhen Unionmemory Information System | 2         | 0.07%   |
| ASMedia Technology                      | 2         | 0.07%   |
| ADATA Technology                        | 2         | 0.07%   |
| Transcend                               | 1         | 0.04%   |
| Silicon Image                           | 1         | 0.04%   |
| Shenzhen Longsys Electronics            | 1         | 0.04%   |
| Marvell Technology Group                | 1         | 0.04%   |
| Lenovo                                  | 1         | 0.04%   |
| Biwin Storage Technology                | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 180       | 6.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 170       | 5.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 153       | 5.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 145       | 4.98%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 144       | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 115       | 3.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 97        | 3.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 92        | 3.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 81        | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 73        | 2.51%   |
| Intel Volume Management Device NVMe RAID Controller                            | 70        | 2.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 70        | 2.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 62        | 2.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 60        | 2.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 51        | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 46        | 1.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 44        | 1.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 43        | 1.48%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 40        | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 40        | 1.37%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 38        | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 37        | 1.27%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 31        | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 30        | 1.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 28        | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                            | 27        | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 26        | 0.89%   |
| Intel SSD 660P Series                                                          | 24        | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 23        | 0.79%   |
| SK hynix BC511 NVMe SSD                                                        | 22        | 0.75%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 21        | 0.72%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 19        | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 19        | 0.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 19        | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 19        | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 18        | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 18        | 0.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 17        | 0.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 17        | 0.58%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 16        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1460      | 52.25%  |
| NVMe | 933       | 33.39%  |
| RAID | 239       | 8.55%   |
| IDE  | 162       | 5.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1975      | 85.46%  |
| AMD    | 335       | 14.5%   |
| ARM    | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 46        | 1.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 41        | 1.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 39        | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 35        | 1.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 34        | 1.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 34        | 1.47%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 31        | 1.34%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 29        | 1.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 1.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 26        | 1.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 25        | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 24        | 1.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 1.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 24        | 1.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 22        | 0.95%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 22        | 0.95%   |
| AMD Custom APU 0405                           | 22        | 0.95%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 21        | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 20        | 0.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 0.82%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 18        | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 18        | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 0.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 17        | 0.74%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 16        | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 16        | 0.69%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 16        | 0.69%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 15        | 0.65%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 14        | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 14        | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.56%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 13        | 0.56%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 0.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 12        | 0.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 12        | 0.52%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 12        | 0.52%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.52%   |
| Intel 12th Gen Core i7-12700H                 | 12        | 0.52%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 12        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 570       | 24.66%  |
| Intel Core i7                  | 559       | 24.19%  |
| Other                          | 229       | 9.91%   |
| Intel Core i3                  | 179       | 7.75%   |
| Intel Core 2 Duo               | 107       | 4.63%   |
| AMD Ryzen 7                    | 90        | 3.89%   |
| Intel Celeron                  | 88        | 3.81%   |
| Intel Pentium                  | 64        | 2.77%   |
| AMD Ryzen 5                    | 62        | 2.68%   |
| Intel Atom                     | 59        | 2.55%   |
| Intel Pentium Dual-Core        | 29        | 1.25%   |
| AMD Ryzen 7 PRO                | 26        | 1.13%   |
| Intel Core i9                  | 22        | 0.95%   |
| Intel Pentium Dual             | 21        | 0.91%   |
| Intel Genuine                  | 20        | 0.87%   |
| AMD A6                         | 18        | 0.78%   |
| AMD Ryzen 9                    | 17        | 0.74%   |
| AMD Ryzen 5 PRO                | 16        | 0.69%   |
| Intel Core 2                   | 15        | 0.65%   |
| Intel Pentium Silver           | 10        | 0.43%   |
| AMD E1                         | 9         | 0.39%   |
| AMD A10                        | 8         | 0.35%   |
| Intel Core m3                  | 7         | 0.3%    |
| AMD E                          | 7         | 0.3%    |
| AMD A8                         | 7         | 0.3%    |
| AMD A4                         | 7         | 0.3%    |
| Intel Xeon                     | 6         | 0.26%   |
| Intel Celeron M                | 4         | 0.17%   |
| Intel Celeron Dual-Core        | 4         | 0.17%   |
| AMD E2                         | 4         | 0.17%   |
| AMD Athlon X2                  | 4         | 0.17%   |
| Intel Core m7                  | 3         | 0.13%   |
| Intel Core m5                  | 3         | 0.13%   |
| AMD Ryzen 3                    | 3         | 0.13%   |
| AMD Athlon II                  | 3         | 0.13%   |
| AMD Athlon 64 X2               | 3         | 0.13%   |
| Intel Core Duo                 | 2         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.09%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.09%   |
| AMD Ryzen 3 PRO                | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1072      | 46.37%  |
| 4      | 778       | 33.65%  |
| 6      | 172       | 7.44%   |
| 8      | 164       | 7.09%   |
| 1      | 47        | 2.03%   |
| 10     | 31        | 1.34%   |
| 14     | 26        | 1.12%   |
| 12     | 16        | 0.69%   |
| 24     | 4         | 0.17%   |
| 16     | 2         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2311      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1756      | 75.98%  |
| 1      | 553       | 23.93%  |
| 8      | 1         | 0.04%   |
| 4      | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2266      | 97.76%  |
| Unknown        | 30        | 1.29%   |
| 32-bit         | 21        | 0.91%   |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 717       | 29.81%  |
| 0x306a9    | 138       | 5.74%   |
| 0x206a7    | 118       | 4.91%   |
| 0x806ec    | 105       | 4.37%   |
| 0x906ea    | 80        | 3.33%   |
| 0x40651    | 69        | 2.87%   |
| 0x1067a    | 66        | 2.74%   |
| 0x406e3    | 62        | 2.58%   |
| 0x806ea    | 61        | 2.54%   |
| 0x806c1    | 60        | 2.49%   |
| 0x20655    | 58        | 2.41%   |
| 0x306c3    | 53        | 2.2%    |
| 0x806e9    | 50        | 2.08%   |
| 0x6fd      | 48        | 2%      |
| 0x306d4    | 47        | 1.95%   |
| 0x0a50000c | 40        | 1.66%   |
| 0x08600106 | 33        | 1.37%   |
| 0x906e9    | 32        | 1.33%   |
| 0x806eb    | 32        | 1.33%   |
| 0x30678    | 30        | 1.25%   |
| 0xa0652    | 27        | 1.12%   |
| 0x506e3    | 25        | 1.04%   |
| 0x08108102 | 21        | 0.87%   |
| 0x20652    | 20        | 0.83%   |
| 0x506c9    | 19        | 0.79%   |
| 0x906a4    | 17        | 0.71%   |
| 0x906a3    | 17        | 0.71%   |
| 0x706e5    | 16        | 0.67%   |
| 0x08108109 | 16        | 0.67%   |
| 0x10676    | 15        | 0.62%   |
| 0x08608103 | 15        | 0.62%   |
| 0x906ed    | 14        | 0.58%   |
| 0x806d1    | 14        | 0.58%   |
| 0x08600103 | 14        | 0.58%   |
| 0x406c4    | 13        | 0.54%   |
| 0x406c3    | 13        | 0.54%   |
| 0x40661    | 11        | 0.46%   |
| 0x706a8    | 10        | 0.42%   |
| 0x6f6      | 10        | 0.42%   |
| 0x6e8      | 10        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 515       | 22.23%  |
| IvyBridge        | 180       | 7.77%   |
| Haswell          | 170       | 7.34%   |
| SandyBridge      | 156       | 6.73%   |
| Skylake          | 130       | 5.61%   |
| Penryn           | 112       | 4.83%   |
| Westmere         | 108       | 4.66%   |
| Unknown          | 97        | 4.19%   |
| TigerLake        | 96        | 4.14%   |
| Core             | 85        | 3.67%   |
| Silvermont       | 84        | 3.63%   |
| Broadwell        | 70        | 3.02%   |
| Zen 3            | 67        | 2.89%   |
| Zen 2            | 65        | 2.81%   |
| Alderlake Hybrid | 57        | 2.46%   |
| CometLake        | 47        | 2.03%   |
| Zen+             | 40        | 1.73%   |
| Icelake          | 37        | 1.6%    |
| Goldmont         | 29        | 1.25%   |
| Goldmont plus    | 20        | 0.86%   |
| Excavator        | 17        | 0.73%   |
| P6               | 16        | 0.69%   |
| Bonnell          | 15        | 0.65%   |
| Bobcat           | 12        | 0.52%   |
| Jaguar           | 11        | 0.47%   |
| Puma             | 10        | 0.43%   |
| Nehalem          | 10        | 0.43%   |
| Piledriver       | 9         | 0.39%   |
| K8 Hammer        | 9         | 0.39%   |
| K8 & K10 hybrid  | 9         | 0.39%   |
| Zen              | 8         | 0.35%   |
| K10 Llano        | 8         | 0.35%   |
| K10              | 7         | 0.3%    |
| Tremont          | 6         | 0.26%   |
| Steamroller      | 4         | 0.17%   |
| Gracemont        | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1757      | 60.4%   |
| Nvidia                           | 680       | 23.38%  |
| AMD                              | 461       | 15.85%  |
| Silicon Integrated Systems [SiS] | 8         | 0.28%   |
| VIA Technologies                 | 3         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 162       | 5.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 143       | 4.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 124       | 4.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 117       | 3.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 90        | 3.02%   |
| Intel UHD Graphics 620                                                                   | 82        | 2.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 79        | 2.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 72        | 2.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 71        | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 71        | 2.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 63        | 2.11%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 62        | 2.08%   |
| Intel HD Graphics 620                                                                    | 61        | 2.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 53        | 1.78%   |
| Intel HD Graphics 5500                                                                   | 49        | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 48        | 1.61%   |
| Intel HD Graphics 630                                                                    | 47        | 1.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 45        | 1.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 44        | 1.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 42        | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 42        | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 41        | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 40        | 1.34%   |
| Intel HD Graphics 530                                                                    | 32        | 1.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 31        | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 31        | 1.04%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 26        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 22        | 0.74%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 22        | 0.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 21        | 0.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 20        | 0.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 19        | 0.64%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 19        | 0.64%   |
| AMD Lucienne                                                                             | 19        | 0.64%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 17        | 0.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 0.57%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 17        | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 16        | 0.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 16        | 0.54%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 16        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1197      | 51.51%  |
| Intel + Nvidia | 485       | 20.87%  |
| 1 x AMD        | 333       | 14.33%  |
| 1 x Nvidia     | 155       | 6.67%   |
| Intel + AMD    | 66        | 2.84%   |
| AMD + Nvidia   | 41        | 1.76%   |
| 2 x AMD        | 20        | 0.86%   |
| 2 x Intel      | 9         | 0.39%   |
| 1 x SiS        | 8         | 0.34%   |
| 2 x Nvidia     | 4         | 0.17%   |
| Other          | 3         | 0.13%   |
| 1 x VIA        | 3         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1960      | 83.48%  |
| Proprietary | 325       | 13.84%  |
| Unknown     | 63        | 2.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1600      | 67.54%  |
| 0.01-0.5   | 235       | 9.92%   |
| 1.01-2.0   | 209       | 8.82%   |
| 3.01-4.0   | 139       | 5.87%   |
| 0.51-1.0   | 117       | 4.94%   |
| 7.01-8.0   | 32        | 1.35%   |
| 5.01-6.0   | 24        | 1.01%   |
| 2.01-3.0   | 11        | 0.46%   |
| 8.01-16.0  | 2         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 555       | 21.01%  |
| LG Display              | 366       | 13.86%  |
| Chimei Innolux          | 301       | 11.4%   |
| BOE                     | 283       | 10.72%  |
| Samsung Electronics     | 281       | 10.64%  |
| Sharp                   | 94        | 3.56%   |
| Apple                   | 84        | 3.18%   |
| Dell                    | 78        | 2.95%   |
| Chi Mei Optoelectronics | 64        | 2.42%   |
| Goldstar                | 60        | 2.27%   |
| Iiyama                  | 45        | 1.7%    |
| Philips                 | 42        | 1.59%   |
| Lenovo                  | 39        | 1.48%   |
| Hewlett-Packard         | 38        | 1.44%   |
| LG Philips              | 36        | 1.36%   |
| CSO                     | 23        | 0.87%   |
| PANDA                   | 22        | 0.83%   |
| Acer                    | 22        | 0.83%   |
| AOC                     | 20        | 0.76%   |
| InfoVision              | 19        | 0.72%   |
| Valve                   | 15        | 0.57%   |
| BenQ                    | 14        | 0.53%   |
| Sony                    | 12        | 0.45%   |
| Ancor Communications    | 10        | 0.38%   |
| LGD                     | 8         | 0.3%    |
| Toshiba                 | 7         | 0.27%   |
| Seiko/Epson             | 6         | 0.23%   |
| CPT                     | 6         | 0.23%   |
| Panasonic               | 5         | 0.19%   |
| MSI                     | 5         | 0.19%   |
| HannStar                | 5         | 0.19%   |
| Unknown                 | 4         | 0.15%   |
| Quanta Display          | 4         | 0.15%   |
| JDI                     | 4         | 0.15%   |
| Eizo                    | 4         | 0.15%   |
| ASUSTek Computer        | 4         | 0.15%   |
| Analogix                | 4         | 0.15%   |
| ViewSonic               | 3         | 0.11%   |
| Vestel Elektronik       | 3         | 0.11%   |
| RTK                     | 3         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 25        | 0.93%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch            | 23        | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 19        | 0.71%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 18        | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 18        | 0.67%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 15        | 0.56%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 15        | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 14        | 0.52%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 14        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 13        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 12        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 12        | 0.45%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 11        | 0.41%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 10        | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 10        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.34%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 9         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 9         | 0.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 9         | 0.34%   |
| LGD LCD Monitor 1920x1080                                                 | 8         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 8         | 0.3%    |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                     | 8         | 0.3%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 8         | 0.3%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 8         | 0.3%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                   | 7         | 0.26%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 7         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 7         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch            | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch            | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch            | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 7         | 0.26%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 7         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1087      | 43.36%  |
| 1366x768 (WXGA)    | 501       | 19.98%  |
| 1600x900 (HD+)     | 180       | 7.18%   |
| 3840x2160 (4K)     | 117       | 4.67%   |
| 1280x800 (WXGA)    | 114       | 4.55%   |
| 2560x1440 (QHD)    | 91        | 3.63%   |
| 1440x900 (WXGA+)   | 71        | 2.83%   |
| 1920x1200 (WUXGA)  | 59        | 2.35%   |
| 2560x1600          | 44        | 1.76%   |
| 3840x2400          | 29        | 1.16%   |
| 2880x1800          | 29        | 1.16%   |
| 1680x1050 (WSXGA+) | 21        | 0.84%   |
| 3440x1440          | 19        | 0.76%   |
| 800x1280           | 18        | 0.72%   |
| 1280x1024 (SXGA)   | 18        | 0.72%   |
| 2560x1080          | 15        | 0.6%    |
| 1360x768           | 14        | 0.56%   |
| Unknown            | 8         | 0.32%   |
| 3456x2160          | 7         | 0.28%   |
| 3200x1800 (QHD+)   | 6         | 0.24%   |
| 3000x2000          | 5         | 0.2%    |
| 2160x1440          | 5         | 0.2%    |
| 1024x600           | 5         | 0.2%    |
| 3840x1080          | 4         | 0.16%   |
| 2256x1504          | 4         | 0.16%   |
| 1024x768 (XGA)     | 4         | 0.16%   |
| 3840x1600          | 3         | 0.12%   |
| 3072x1920          | 3         | 0.12%   |
| 1920x540           | 3         | 0.12%   |
| 1680x945           | 3         | 0.12%   |
| 2304x1440          | 2         | 0.08%   |
| 2240x1400          | 2         | 0.08%   |
| 1280x720 (HD)      | 2         | 0.08%   |
| 8960x2160          | 1         | 0.04%   |
| 5440x1800          | 1         | 0.04%   |
| 4480x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3840x1100          | 1         | 0.04%   |
| 3600x1080          | 1         | 0.04%   |
| 3200x2000          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 965       | 36.53%  |
| 13      | 363       | 13.74%  |
| 17      | 294       | 11.13%  |
| 14      | 270       | 10.22%  |
| 24      | 102       | 3.86%   |
| 27      | 92        | 3.48%   |
| 12      | 80        | 3.03%   |
| 11      | 65        | 2.46%   |
| 23      | 56        | 2.12%   |
| Unknown | 50        | 1.89%   |
| 16      | 49        | 1.85%   |
| 21      | 37        | 1.4%    |
| 31      | 33        | 1.25%   |
| 34      | 32        | 1.21%   |
| 18      | 20        | 0.76%   |
| 7       | 15        | 0.57%   |
| 19      | 14        | 0.53%   |
| 22      | 11        | 0.42%   |
| 10      | 11        | 0.42%   |
| 25      | 9         | 0.34%   |
| 72      | 8         | 0.3%    |
| 54      | 7         | 0.26%   |
| 84      | 6         | 0.23%   |
| 20      | 5         | 0.19%   |
| 40      | 4         | 0.15%   |
| 37      | 4         | 0.15%   |
| 3       | 4         | 0.15%   |
| 86      | 3         | 0.11%   |
| 65      | 3         | 0.11%   |
| 32      | 3         | 0.11%   |
| 29      | 3         | 0.11%   |
| 28      | 3         | 0.11%   |
| 52      | 2         | 0.08%   |
| 48      | 2         | 0.08%   |
| 46      | 2         | 0.08%   |
| 36      | 2         | 0.08%   |
| 35      | 2         | 0.08%   |
| 8       | 2         | 0.08%   |
| 60      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1381      | 52.79%  |
| 201-300     | 388       | 14.83%  |
| 351-400     | 334       | 12.77%  |
| 501-600     | 234       | 8.94%   |
| 401-500     | 72        | 2.75%   |
| Unknown     | 50        | 1.91%   |
| 601-700     | 49        | 1.87%   |
| 701-800     | 38        | 1.45%   |
| 1001-1500   | 22        | 0.84%   |
| 1-100       | 18        | 0.69%   |
| 1501-2000   | 15        | 0.57%   |
| 801-900     | 12        | 0.46%   |
| 101-200     | 2         | 0.08%   |
| 901-1000    | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1822      | 77.66%  |
| 16/10   | 370       | 15.77%  |
| Unknown | 39        | 1.66%   |
| 21/9    | 37        | 1.58%   |
| 3/2     | 25        | 1.07%   |
| 5/4     | 18        | 0.77%   |
| 0.67    | 15        | 0.64%   |
| 4/3     | 7         | 0.3%    |
| 6/5     | 4         | 0.17%   |
| 32/9    | 3         | 0.13%   |
| 0.56    | 3         | 0.13%   |
| 3.40    | 1         | 0.04%   |
| 3.33    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 954       | 36.2%   |
| 81-90          | 450       | 17.08%  |
| 121-130        | 245       | 9.3%    |
| 71-80          | 179       | 6.79%   |
| 201-250        | 163       | 6.19%   |
| 301-350        | 93        | 3.53%   |
| 61-70          | 80        | 3.04%   |
| 351-500        | 75        | 2.85%   |
| 51-60          | 67        | 2.54%   |
| 111-120        | 54        | 2.05%   |
| Unknown        | 50        | 1.9%    |
| 131-140        | 46        | 1.75%   |
| 251-300        | 38        | 1.44%   |
| More than 1000 | 32        | 1.21%   |
| 151-200        | 32        | 1.21%   |
| 141-150        | 22        | 0.83%   |
| 1-40           | 20        | 0.76%   |
| 501-1000       | 18        | 0.68%   |
| 41-50          | 10        | 0.38%   |
| 91-100         | 7         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1085      | 41.84%  |
| 101-120       | 624       | 24.06%  |
| 51-100        | 415       | 16%     |
| 161-240       | 248       | 9.56%   |
| More than 240 | 133       | 5.13%   |
| Unknown       | 50        | 1.93%   |
| 1-50          | 38        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1819      | 76.65%  |
| 2     | 417       | 17.57%  |
| 0     | 89        | 3.75%   |
| 3     | 44        | 1.85%   |
| 4     | 3         | 0.13%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1375      | 37.29%  |
| Realtek Semiconductor                  | 1093      | 29.64%  |
| Qualcomm Atheros                       | 446       | 12.1%   |
| Broadcom                               | 259       | 7.02%   |
| Broadcom Limited                       | 67        | 1.82%   |
| MediaTek                               | 52        | 1.41%   |
| Ralink                                 | 36        | 0.98%   |
| ASIX Electronics                       | 35        | 0.95%   |
| Marvell Technology Group               | 34        | 0.92%   |
| Dell                                   | 31        | 0.84%   |
| DisplayLink                            | 30        | 0.81%   |
| TP-Link                                | 26        | 0.71%   |
| Hewlett-Packard                        | 26        | 0.71%   |
| Nvidia                                 | 20        | 0.54%   |
| Ralink Technology                      | 19        | 0.52%   |
| JMicron Technology                     | 13        | 0.35%   |
| Silicon Integrated Systems [SiS]       | 12        | 0.33%   |
| Sierra Wireless                        | 12        | 0.33%   |
| Qualcomm                               | 12        | 0.33%   |
| Ericsson Business Mobile Networks      | 12        | 0.33%   |
| Samsung Electronics                    | 10        | 0.27%   |
| Lenovo                                 | 10        | 0.27%   |
| Huawei Technologies                    | 7         | 0.19%   |
| NetGear                                | 5         | 0.14%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.11%   |
| ASUSTek Computer                       | 4         | 0.11%   |
| Xiaomi                                 | 3         | 0.08%   |
| VIA Technologies                       | 3         | 0.08%   |
| Sitecom Europe                         | 3         | 0.08%   |
| Fibocom                                | 3         | 0.08%   |
| Arduino SA                             | 3         | 0.08%   |
| MosChip Semiconductor                  | 2         | 0.05%   |
| Dresden Elektronik                     | 2         | 0.05%   |
| D-Link                                 | 2         | 0.05%   |
| Apple                                  | 2         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Senao                                  | 1         | 0.03%   |
| Sagem                                  | 1         | 0.03%   |
| Prusa                                  | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 702       | 15.82%  |
| Intel Wi-Fi 6 AX200                                                     | 154       | 3.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 149       | 3.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 121       | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 107       | 2.41%   |
| Intel Wireless 8265 / 8275                                              | 106       | 2.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 102       | 2.3%    |
| Intel Wireless 7265                                                     | 90        | 2.03%   |
| Intel Wi-Fi 6 AX201                                                     | 75        | 1.69%   |
| Intel Wireless 7260                                                     | 73        | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 66        | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 61        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 61        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 60        | 1.35%   |
| Intel Wireless 8260                                                     | 58        | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 55        | 1.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 51        | 1.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 50        | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 49        | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 44        | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 44        | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 39        | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                   | 38        | 0.86%   |
| Intel Centrino Ultimate-N 6300                                          | 38        | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 36        | 0.81%   |
| Intel 82577LM Gigabit Network Connection                                | 36        | 0.81%   |
| Intel Centrino Advanced-N 6200                                          | 35        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 33        | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 0.74%   |
| Intel Wireless 3165                                                     | 32        | 0.72%   |
| Intel Ethernet Connection I219-LM                                       | 32        | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                           | 32        | 0.72%   |
| Intel Wireless-AC 9260                                                  | 31        | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 31        | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 30        | 0.68%   |
| Intel Wireless 3160                                                     | 27        | 0.61%   |
| Intel Ethernet Connection I218-LM                                       | 27        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 27        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 26        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 24        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1322      | 55.36%  |
| Qualcomm Atheros                      | 382       | 16%     |
| Realtek Semiconductor                 | 265       | 11.1%   |
| Broadcom                              | 189       | 7.91%   |
| MediaTek                              | 51        | 2.14%   |
| Ralink                                | 36        | 1.51%   |
| Broadcom Limited                      | 32        | 1.34%   |
| TP-Link                               | 20        | 0.84%   |
| Dell                                  | 20        | 0.84%   |
| Ralink Technology                     | 19        | 0.8%    |
| Sierra Wireless                       | 12        | 0.5%    |
| Qualcomm                              | 10        | 0.42%   |
| Hewlett-Packard                       | 6         | 0.25%   |
| NetGear                               | 5         | 0.21%   |
| ASUSTek Computer                      | 4         | 0.17%   |
| Sitecom Europe                        | 3         | 0.13%   |
| Fibocom                               | 3         | 0.13%   |
| D-Link                                | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.04%   |
| Senao                                 | 1         | 0.04%   |
| Sagem                                 | 1         | 0.04%   |
| Microsoft                             | 1         | 0.04%   |
| Linksys                               | 1         | 0.04%   |
| BUFFALO                               | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 154       | 6.41%   |
| Intel Wireless 8265 / 8275                                              | 106       | 4.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 102       | 4.25%   |
| Intel Wireless 7265                                                     | 90        | 3.75%   |
| Intel Wi-Fi 6 AX201                                                     | 75        | 3.12%   |
| Intel Wireless 7260                                                     | 73        | 3.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 66        | 2.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 61        | 2.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 61        | 2.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 60        | 2.5%    |
| Intel Wireless 8260                                                     | 58        | 2.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 55        | 2.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 51        | 2.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 50        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 49        | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 44        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 44        | 1.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 39        | 1.62%   |
| Intel Centrino Ultimate-N 6300                                          | 38        | 1.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 36        | 1.5%    |
| Intel Centrino Advanced-N 6200                                          | 35        | 1.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 33        | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 1.37%   |
| Intel Wireless 3165                                                     | 32        | 1.33%   |
| Intel Wireless-AC 9260                                                  | 31        | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 31        | 1.29%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 30        | 1.25%   |
| Intel Wireless 3160                                                     | 27        | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 27        | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 24        | 1%      |
| Broadcom BCM43142 802.11b/g/n                                           | 24        | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 23        | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 21        | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 21        | 0.87%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 21        | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 19        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 18        | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 18        | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 17        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 983       | 50.51%  |
| Intel                                  | 491       | 25.23%  |
| Qualcomm Atheros                       | 124       | 6.37%   |
| Broadcom                               | 115       | 5.91%   |
| Broadcom Limited                       | 35        | 1.8%    |
| ASIX Electronics                       | 35        | 1.8%    |
| Marvell Technology Group               | 34        | 1.75%   |
| DisplayLink                            | 30        | 1.54%   |
| Nvidia                                 | 19        | 0.98%   |
| JMicron Technology                     | 13        | 0.67%   |
| Silicon Integrated Systems [SiS]       | 11        | 0.57%   |
| Lenovo                                 | 10        | 0.51%   |
| Samsung Electronics                    | 8         | 0.41%   |
| TP-Link                                | 6         | 0.31%   |
| Hewlett-Packard                        | 6         | 0.31%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.21%   |
| Huawei Technologies                    | 4         | 0.21%   |
| Xiaomi                                 | 3         | 0.15%   |
| VIA Technologies                       | 3         | 0.15%   |
| Qualcomm                               | 2         | 0.1%    |
| MosChip Semiconductor                  | 2         | 0.1%    |
| Apple                                  | 2         | 0.1%    |
| Spreadtrum Communications              | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Motorola PCS                           | 1         | 0.05%   |
| Jolla Oy                               | 1         | 0.05%   |
| Google                                 | 1         | 0.05%   |
| ADMtek                                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 702       | 35.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 149       | 7.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 121       | 6.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 107       | 5.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 38        | 1.92%   |
| Intel 82577LM Gigabit Network Connection                          | 36        | 1.82%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 1.61%   |
| ASIX AX88179 Gigabit Ethernet                                     | 32        | 1.61%   |
| Intel Ethernet Connection I218-LM                                 | 27        | 1.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 26        | 1.31%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 1.01%   |
| Intel Ethernet Connection (6) I219-V                              | 20        | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 1.01%   |
| Intel Ethernet Connection (6) I219-LM                             | 19        | 0.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 18        | 0.91%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.81%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.76%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 15        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 14        | 0.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 13        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.66%   |
| Intel 82567LM Gigabit Network Connection                          | 13        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 12        | 0.61%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 11        | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 11        | 0.55%   |
| Nvidia MCP79 Ethernet                                             | 11        | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 10        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 10        | 0.5%    |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 10        | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 10        | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 9         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2257      | 54.23%  |
| Ethernet | 1853      | 44.52%  |
| Modem    | 50        | 1.2%    |
| Unknown  | 2         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1888      | 75.7%   |
| Ethernet | 606       | 24.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1662      | 71.79%  |
| 1     | 590       | 25.49%  |
| 0     | 38        | 1.64%   |
| 3     | 25        | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1818      | 76.81%  |
| Yes  | 549       | 23.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1007      | 55.24%  |
| Realtek Semiconductor           | 128       | 7.02%   |
| Qualcomm Atheros Communications | 114       | 6.25%   |
| Broadcom                        | 102       | 5.6%    |
| IMC Networks                    | 84        | 4.61%   |
| Foxconn / Hon Hai               | 72        | 3.95%   |
| Apple                           | 71        | 3.89%   |
| Lite-On Technology              | 58        | 3.18%   |
| Hewlett-Packard                 | 46        | 2.52%   |
| Dell                            | 36        | 1.97%   |
| Cambridge Silicon Radio         | 32        | 1.76%   |
| Toshiba                         | 21        | 1.15%   |
| ASUSTek Computer                | 12        | 0.66%   |
| Ralink                          | 9         | 0.49%   |
| Realtek                         | 5         | 0.27%   |
| Foxconn International           | 4         | 0.22%   |
| Alps Electric                   | 4         | 0.22%   |
| USI                             | 3         | 0.16%   |
| Ralink Technology               | 3         | 0.16%   |
| Integrated System Solution      | 3         | 0.16%   |
| MediaTek                        | 2         | 0.11%   |
| TP-Link                         | 1         | 0.05%   |
| Sitecom Europe                  | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Conwise Technology              | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 363       | 19.87%  |
| Intel Bluetooth Device                              | 213       | 11.66%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 169       | 9.25%   |
| Intel AX200 Bluetooth                               | 151       | 8.26%   |
| Realtek Bluetooth Radio                             | 76        | 4.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 42        | 2.3%    |
| Apple Bluetooth Host Controller                     | 41        | 2.24%   |
| Realtek  Bluetooth 4.2 Adapter                      | 38        | 2.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 32        | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 31        | 1.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 29        | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 28        | 1.53%   |
| Foxconn / Hon Hai Bluetooth Device                  | 26        | 1.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 24        | 1.31%   |
| HP Broadcom 2070 Bluetooth Combo                    | 24        | 1.31%   |
| Apple Bluetooth USB Host Controller                 | 23        | 1.26%   |
| Intel AX210 Bluetooth                               | 22        | 1.2%    |
| IMC Networks 802.11ac WLAN Adapter                  | 22        | 1.2%    |
| Lite-On Bluetooth Device                            | 21        | 1.15%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 21        | 1.15%   |
| Dell DW375 Bluetooth Module                         | 20        | 1.09%   |
| Broadcom HP Portable SoftSailing                    | 20        | 1.09%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 19        | 1.04%   |
| IMC Networks Bluetooth Device                       | 18        | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                         | 18        | 0.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 0.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 16        | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 15        | 0.82%   |
| IMC Networks Wireless_Device                        | 15        | 0.82%   |
| IMC Networks Bluetooth Radio                        | 14        | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 0.71%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 0.6%    |
| Broadcom BCM2045 Bluetooth                          | 11        | 0.6%    |
| Broadcom HP Portable Bumble Bee                     | 10        | 0.55%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.33%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1891      | 65.41%  |
| AMD                              | 410       | 14.18%  |
| Nvidia                           | 357       | 12.35%  |
| Realtek Semiconductor            | 30        | 1.04%   |
| C-Media Electronics              | 26        | 0.9%    |
| GN Netcom                        | 23        | 0.8%    |
| Logitech                         | 21        | 0.73%   |
| Hewlett-Packard                  | 16        | 0.55%   |
| Silicon Integrated Systems [SiS] | 13        | 0.45%   |
| Plantronics                      | 8         | 0.28%   |
| Texas Instruments                | 7         | 0.24%   |
| Lenovo                           | 7         | 0.24%   |
| Apple                            | 7         | 0.24%   |
| BEHRINGER International          | 6         | 0.21%   |
| JMTek                            | 5         | 0.17%   |
| SteelSeries ApS                  | 4         | 0.14%   |
| Kingston Technology              | 4         | 0.14%   |
| VIA Technologies                 | 3         | 0.1%    |
| Sennheiser Communications        | 3         | 0.1%    |
| Razer USA                        | 3         | 0.1%    |
| No brand                         | 3         | 0.1%    |
| GYROCOM C&C                      | 3         | 0.1%    |
| Veho                             | 2         | 0.07%   |
| Sony                             | 2         | 0.07%   |
| Focusrite-Novation               | 2         | 0.07%   |
| Creative Technology              | 2         | 0.07%   |
| Corsair                          | 2         | 0.07%   |
| YZ Technology                    | 1         | 0.03%   |
| Yealink Network Technology       | 1         | 0.03%   |
| XMOS                             | 1         | 0.03%   |
| Tenx Technology                  | 1         | 0.03%   |
| Syntek                           | 1         | 0.03%   |
| Shenzhen Riitek Technology       | 1         | 0.03%   |
| SAVITECH                         | 1         | 0.03%   |
| RODE Microphones                 | 1         | 0.03%   |
| PreSonus Audio Electronics       | 1         | 0.03%   |
| Polycom                          | 1         | 0.03%   |
| Pioneer DJ                       | 1         | 0.03%   |
| Philips (or NXP)                 | 1         | 0.03%   |
| Other World Computing            | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 243       | 7.17%   |
| AMD Family 17h/19h HD Audio Controller                                     | 214       | 6.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 204       | 6.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 132       | 3.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 129       | 3.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 127       | 3.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 121       | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 118       | 3.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 96        | 2.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 93        | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 86        | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 82        | 2.42%   |
| Intel 8 Series HD Audio Controller                                         | 82        | 2.42%   |
| Intel Broadwell-U Audio Controller                                         | 70        | 2.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 69        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 63        | 1.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 54        | 1.59%   |
| Intel CM238 HD Audio Controller                                            | 52        | 1.53%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 52        | 1.53%   |
| Intel Comet Lake PCH-LP cAVS                                               | 50        | 1.47%   |
| AMD FCH Azalia Controller                                                  | 48        | 1.42%   |
| Intel Comet Lake PCH cAVS                                                  | 45        | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 45        | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 41        | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 41        | 1.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 39        | 1.15%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 38        | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                              | 34        | 1%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 33        | 0.97%   |
| Realtek Semiconductor USB Audio                                            | 29        | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 29        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 28        | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                              | 26        | 0.77%   |
| Nvidia Audio device                                                        | 23        | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 23        | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 22        | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 22        | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 22        | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 21        | 0.62%   |
| Nvidia GA106 High Definition Audio Controller                              | 21        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 392       | 28.41%  |
| Samsung Electronics | 372       | 26.96%  |
| Micron Technology   | 177       | 12.83%  |
| Kingston            | 106       | 7.68%   |
| Unknown             | 77        | 5.58%   |
| Crucial             | 57        | 4.13%   |
| Ramaxel Technology  | 30        | 2.17%   |
| Corsair             | 28        | 2.03%   |
| A-DATA Technology   | 23        | 1.67%   |
| Elpida              | 19        | 1.38%   |
| Nanya Technology    | 17        | 1.23%   |
| G.Skill             | 14        | 1.01%   |
| Unknown             | 11        | 0.8%    |
| Team                | 7         | 0.51%   |
| Unknown (ABCD)      | 6         | 0.43%   |
| GOODRAM             | 6         | 0.43%   |
| ASint Technology    | 5         | 0.36%   |
| Qimonda             | 4         | 0.29%   |
| 48spaces            | 4         | 0.29%   |
| Wilk                | 3         | 0.22%   |
| Transcend           | 3         | 0.22%   |
| Toshiba             | 2         | 0.14%   |
| Lexar               | 2         | 0.14%   |
| Goldkey             | 2         | 0.14%   |
| ZIFEI               | 1         | 0.07%   |
| Unifosa             | 1         | 0.07%   |
| Timetec             | 1         | 0.07%   |
| tigo                | 1         | 0.07%   |
| Smart               | 1         | 0.07%   |
| SHARETRONIC         | 1         | 0.07%   |
| Sesame              | 1         | 0.07%   |
| PKI/Kingston        | 1         | 0.07%   |
| Micron/Elpida       | 1         | 0.07%   |
| Lenovo              | 1         | 0.07%   |
| Kllisre             | 1         | 0.07%   |
| Golden Empire       | 1         | 0.07%   |
| Apacer              | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 1.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 1.17%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 1.03%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 14        | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.89%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 0.89%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.82%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 12        | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.75%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.75%   |
| Unknown                                                          | 11        | 0.75%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 10        | 0.69%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 10        | 0.69%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 9         | 0.62%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 9         | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 9         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.62%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 8         | 0.55%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 8         | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 8         | 0.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.55%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.55%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 7         | 0.48%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 7         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 7         | 0.48%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.48%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.48%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 7         | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.48%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 6         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 0.41%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 6         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 594       | 49.87%  |
| DDR3    | 362       | 30.39%  |
| LPDDR4  | 54        | 4.53%   |
| LPDDR3  | 53        | 4.45%   |
| DDR2    | 41        | 3.44%   |
| DDR5    | 28        | 2.35%   |
| SDRAM   | 25        | 2.1%    |
| LPDDR5  | 21        | 1.76%   |
| DDR     | 5         | 0.42%   |
| Unknown | 5         | 0.42%   |
| DRAM    | 3         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1046      | 87.02%  |
| Row Of Chips | 130       | 10.82%  |
| DIMM         | 12        | 1%      |
| Unknown      | 8         | 0.67%   |
| Chip         | 6         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 506       | 38.98%  |
| 4096  | 305       | 23.5%   |
| 16384 | 225       | 17.33%  |
| 2048  | 159       | 12.25%  |
| 32768 | 49        | 3.78%   |
| 1024  | 47        | 3.62%   |
| 512   | 5         | 0.39%   |
| 3072  | 1         | 0.08%   |
| 64    | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 266       | 21.11%  |
| 3200    | 247       | 19.6%   |
| 1600    | 235       | 18.65%  |
| 2133    | 74        | 5.87%   |
| 2400    | 72        | 5.71%   |
| 1334    | 59        | 4.68%   |
| 1333    | 50        | 3.97%   |
| 4267    | 28        | 2.22%   |
| 667     | 25        | 1.98%   |
| 4800    | 24        | 1.9%    |
| Unknown | 23        | 1.83%   |
| 1867    | 21        | 1.67%   |
| 6400    | 19        | 1.51%   |
| 800     | 15        | 1.19%   |
| 3266    | 13        | 1.03%   |
| 1067    | 13        | 1.03%   |
| 8400    | 12        | 0.95%   |
| 4199    | 9         | 0.71%   |
| 4266    | 8         | 0.63%   |
| 2048    | 8         | 0.63%   |
| 1066    | 8         | 0.63%   |
| 1866    | 7         | 0.56%   |
| 1639    | 6         | 0.48%   |
| 5600    | 4         | 0.32%   |
| 533     | 3         | 0.24%   |
| 3000    | 2         | 0.16%   |
| 31582   | 1         | 0.08%   |
| 7500    | 1         | 0.08%   |
| 7467    | 1         | 0.08%   |
| 5200    | 1         | 0.08%   |
| 3733    | 1         | 0.08%   |
| 3600    | 1         | 0.08%   |
| 3500    | 1         | 0.08%   |
| 3400    | 1         | 0.08%   |
| 975     | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 5         | 33.33%  |
| Hewlett-Packard     | 4         | 26.67%  |
| Seiko Epson         | 2         | 13.33%  |
| Dymo-CoStar         | 2         | 13.33%  |
| Samsung Electronics | 1         | 6.67%   |
| Brother Industries  | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| HP DeskJet 2700 series      | 2         | 13.33%  |
| Seiko Epson XP-200 Series   | 1         | 6.67%   |
| Seiko Epson ET-2720 Series  | 1         | 6.67%   |
| Samsung CLX-3180 Series     | 1         | 6.67%   |
| HP Printing Support         | 1         | 6.67%   |
| HP OfficeJet 3830 series    | 1         | 6.67%   |
| Dymo-CoStar LabelWriter 450 | 1         | 6.67%   |
| Dymo-CoStar LabelWriter 400 | 1         | 6.67%   |
| Canon TR4600 series         | 1         | 6.67%   |
| Canon PIXMA MX920 Series    | 1         | 6.67%   |
| Canon PIXMA MG5600 Series   | 1         | 6.67%   |
| Canon LBP6680/3480 UFR II   | 1         | 6.67%   |
| Canon LBP2900               | 1         | 6.67%   |
| Brother MFC-J4540DW         | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Canon          | 4         | 66.67%  |
| Seiko Epson    | 1         | 16.67%  |
| Mustek Systems | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan N650U/N656U                    | 2         | 33.33%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 16.67%  |
| Mustek Systems BearPaw 2400 CU Plus           | 1         | 16.67%  |
| Canon CanoScan LiDE 210                       | 1         | 16.67%  |
| Canon CanoScan 5600F                          | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 509       | 25.14%  |
| Microdia                               | 205       | 10.12%  |
| IMC Networks                           | 203       | 10.02%  |
| Realtek Semiconductor                  | 170       | 8.4%    |
| Sunplus Innovation Technology          | 128       | 6.32%   |
| Bison Electronics                      | 116       | 5.73%   |
| Cheng Uei Precision Industry (Foxlink) | 97        | 4.79%   |
| Quanta                                 | 79        | 3.9%    |
| Suyin                                  | 75        | 3.7%    |
| Apple                                  | 58        | 2.86%   |
| Acer                                   | 51        | 2.52%   |
| Lite-On Technology                     | 47        | 2.32%   |
| Logitech                               | 41        | 2.02%   |
| Syntek                                 | 30        | 1.48%   |
| Luxvisions Innotech Limited            | 30        | 1.48%   |
| Ricoh                                  | 19        | 0.94%   |
| Silicon Motion                         | 18        | 0.89%   |
| Lenovo                                 | 16        | 0.79%   |
| Primax Electronics                     | 14        | 0.69%   |
| Alcor Micro                            | 14        | 0.69%   |
| Samsung Electronics                    | 11        | 0.54%   |
| Sonix Technology                       | 10        | 0.49%   |
| Importek                               | 8         | 0.4%    |
| Microsoft                              | 6         | 0.3%    |
| SunplusIT                              | 5         | 0.25%   |
| ALi                                    | 5         | 0.25%   |
| Z-Star Microelectronics                | 4         | 0.2%    |
| Y Media                                | 3         | 0.15%   |
| OmniVision Technologies                | 3         | 0.15%   |
| Jieli Technology                       | 3         | 0.15%   |
| ARC International                      | 3         | 0.15%   |
| Alpha Imaging Technology               | 3         | 0.15%   |
| Tobii Technology AB                    | 2         | 0.1%    |
| MacroSilicon                           | 2         | 0.1%    |
| Intel                                  | 2         | 0.1%    |
| icSpring                               | 2         | 0.1%    |
| Genesys Logic                          | 2         | 0.1%    |
| Generalplus Technology                 | 2         | 0.1%    |
| DigiTech                               | 2         | 0.1%    |
| Creative Technology                    | 2         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 119       | 5.84%   |
| Chicony Integrated Camera                                                  | 82        | 4.03%   |
| Realtek Integrated_Webcam_HD                                               | 75        | 3.68%   |
| IMC Networks Integrated Camera                                             | 70        | 3.44%   |
| Chicony HD WebCam                                                          | 61        | 2.99%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 50        | 2.45%   |
| Sunplus Integrated_Webcam_HD                                               | 47        | 2.31%   |
| Bison Integrated Camera                                                    | 44        | 2.16%   |
| Chicony HP HD Camera                                                       | 35        | 1.72%   |
| Chicony USB2.0 Camera                                                      | 28        | 1.37%   |
| Acer BisonCam,NB Pro                                                       | 23        | 1.13%   |
| Apple FaceTime HD Camera                                                   | 21        | 1.03%   |
| Chicony USB 2.0 Camera                                                     | 19        | 0.93%   |
| Chicony TOSHIBA Web Camera - HD                                            | 19        | 0.93%   |
| Lite-On HP HD Camera                                                       | 18        | 0.88%   |
| Syntek Integrated Camera                                                   | 17        | 0.83%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 17        | 0.83%   |
| Sunplus HD WebCam                                                          | 17        | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 17        | 0.83%   |
| Chicony Integrated HP HD Webcam                                            | 16        | 0.79%   |
| Microdia Integrated Webcam                                                 | 15        | 0.74%   |
| Chicony HP Wide Vision HD Camera                                           | 15        | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 15        | 0.74%   |
| Quanta HP HD Camera                                                        | 14        | 0.69%   |
| Quanta HD User Facing                                                      | 14        | 0.69%   |
| Lite-On Integrated Camera                                                  | 14        | 0.69%   |
| Chicony FJ Camera                                                          | 13        | 0.64%   |
| Apple Built-in iSight                                                      | 13        | 0.64%   |
| Primax HP HD Webcam [Fixed]                                                | 12        | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 12        | 0.59%   |
| IMC Networks Integrated Webcam                                             | 12        | 0.59%   |
| Chicony USB2.0 HD UVC WebCam                                               | 12        | 0.59%   |
| Chicony HP HD Webcam                                                       | 12        | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 12        | 0.59%   |
| Bison SunplusIT Integrated Camera                                          | 12        | 0.59%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 11        | 0.54%   |
| Realtek USB Camera                                                         | 11        | 0.54%   |
| Quanta HP Wide Vision HD Camera                                            | 11        | 0.54%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 11        | 0.54%   |
| Chicony Integrated Camera (1280x720@30)                                    | 11        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 164       | 35.65%  |
| Synaptics                          | 132       | 28.7%   |
| Shenzhen Goodix Technology         | 59        | 12.83%  |
| AuthenTec                          | 34        | 7.39%   |
| Elan Microelectronics              | 24        | 5.22%   |
| LighTuning Technology              | 23        | 5%      |
| Upek                               | 20        | 4.35%   |
| STMicroelectronics                 | 3         | 0.65%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 56        | 12.17%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 44        | 9.57%   |
| Shenzhen Goodix  FingerPrint Device                                        | 28        | 6.09%   |
| Shenzhen Goodix FingerPrint                                                | 22        | 4.78%   |
| Validity Sensors VFS491                                                    | 21        | 4.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 4.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 3.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 3.04%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 3.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 3.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 2.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 2.83%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 2.83%   |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 2.61%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.61%   |
| Elan ELAN:ARM-M4                                                           | 12        | 2.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.17%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.96%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 1.96%   |
| AuthenTec AES2810                                                          | 9         | 1.96%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.52%   |
| Synaptics TouchPad                                                         | 7         | 1.52%   |
| AuthenTec AES1600                                                          | 7         | 1.52%   |
| Unknown                                                                    | 7         | 1.52%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.09%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.09%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.09%   |
| Synaptics  WBDI                                                            | 5         | 1.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.09%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.09%   |
| Synaptics WBDI Device                                                      | 4         | 0.87%   |
| Synaptics WBDI                                                             | 4         | 0.87%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 0.87%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.65%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.65%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.43%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 126       | 54.78%  |
| Alcor Micro               | 60        | 26.09%  |
| O2 Micro                  | 24        | 10.43%  |
| Upek                      | 8         | 3.48%   |
| Lenovo                    | 6         | 2.61%   |
| Gemalto (was Gemplus)     | 2         | 0.87%   |
| Yubico.com                | 1         | 0.43%   |
| SCM Microsystems          | 1         | 0.43%   |
| Fujitsu Siemens Computers | 1         | 0.43%   |
| Advanced Card Systems     | 1         | 0.43%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 60        | 26.09%  |
| Broadcom BCM5880 Secure Applications Processor                               | 41        | 17.83%  |
| Broadcom 58200                                                               | 34        | 14.78%  |
| Broadcom 5880                                                                | 29        | 12.61%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 9.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 9.57%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 3.48%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 2.61%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.87%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.43%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.43%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.43%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.43%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.43%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.43%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1345      | 56.47%  |
| 1     | 803       | 33.71%  |
| 2     | 194       | 8.14%   |
| 3     | 29        | 1.22%   |
| 4     | 6         | 0.25%   |
| 5     | 2         | 0.08%   |
| 9     | 1         | 0.04%   |
| 8     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 457       | 35.79%  |
| Graphics card            | 262       | 20.52%  |
| Chipcard                 | 199       | 15.58%  |
| Net/wireless             | 111       | 8.69%   |
| Multimedia controller    | 89        | 6.97%   |
| Camera                   | 39        | 3.05%   |
| Bluetooth                | 22        | 1.72%   |
| Storage                  | 21        | 1.64%   |
| Communication controller | 20        | 1.57%   |
| Card reader              | 16        | 1.25%   |
| Sound                    | 12        | 0.94%   |
| Net/ethernet             | 9         | 0.7%    |
| Flash memory             | 8         | 0.63%   |
| Network                  | 5         | 0.39%   |
| Modem                    | 3         | 0.23%   |
| Storage/nvme             | 1         | 0.08%   |
| Storage/ide              | 1         | 0.08%   |
| Storage/ata              | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |

