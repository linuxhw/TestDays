Linux in Denmark - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

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

Total: 604

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | N55SF                       | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Unknown       | Unknown                     | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| Acer          | Aspire E5-551               | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Dell          | XPS 13 9370                 | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | Z50-75 80EC                 | [e3f9c7a4f1](https://linux-hardware.org/?probe=e3f9c7a4f1) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | XPS 15 9570                 | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [87c9436154](https://linux-hardware.org/?probe=87c9436154) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d3047f6963](https://linux-hardware.org/?probe=d3047f6963) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [6ea648bc51](https://linux-hardware.org/?probe=6ea648bc51) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Acer          | Aspire E5-553               | [5db637f345](https://linux-hardware.org/?probe=5db637f345) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | [f0bbe89fe8](https://linux-hardware.org/?probe=f0bbe89fe8) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | [af2f12093c](https://linux-hardware.org/?probe=af2f12093c) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| Valve         | Jupiter                     | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [865455aae7](https://linux-hardware.org/?probe=865455aae7) | Sep 05, 2022 |
| Acer          | Aspire E5-553               | [de2cfb43d7](https://linux-hardware.org/?probe=de2cfb43d7) | Sep 03, 2022 |
| Apple         | MacBookPro9,2               | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| HP            | ProBook 6550b               | [662065bfe2](https://linux-hardware.org/?probe=662065bfe2) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | B50-50 80S2                 | [45f5a72c59](https://linux-hardware.org/?probe=45f5a72c59) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Dell          | XPS 13 9370                 | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [1d97fa15fb](https://linux-hardware.org/?probe=1d97fa15fb) | Aug 08, 2022 |
| Acer          | Aspire M3-581TG             | [5c73e4c75b](https://linux-hardware.org/?probe=5c73e4c75b) | Aug 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Notebook      | NS50_70MU                   | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [e6ccfdf23c](https://linux-hardware.org/?probe=e6ccfdf23c) | Jul 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| HP            | Laptop 15-gw0xxx            | [a7f15d1696](https://linux-hardware.org/?probe=a7f15d1696) | Jul 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Acer          | Aspire E5-553               | [e7cdc97a90](https://linux-hardware.org/?probe=e7cdc97a90) | Jul 11, 2022 |
| Dell          | Latitude 7490               | [b456bca385](https://linux-hardware.org/?probe=b456bca385) | Jul 06, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [0e23c1fc2b](https://linux-hardware.org/?probe=0e23c1fc2b) | Jul 02, 2022 |
| Lenovo        | ThinkPad T530 24295L4       | [1bdf25550e](https://linux-hardware.org/?probe=1bdf25550e) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6dfa236f76](https://linux-hardware.org/?probe=6dfa236f76) | Jun 18, 2022 |
| Notebook      | PB50_70DFx,DDx              | [21206dd6bf](https://linux-hardware.org/?probe=21206dd6bf) | Jun 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| Lenovo        | ThinkPad T550 20CK003HMD    | [ea8155f580](https://linux-hardware.org/?probe=ea8155f580) | Jun 14, 2022 |
| Dell          | Latitude E7440              | [6bbb1944af](https://linux-hardware.org/?probe=6bbb1944af) | Jun 12, 2022 |
| Google        | Babytiger                   | [18f6f97122](https://linux-hardware.org/?probe=18f6f97122) | Jun 12, 2022 |
| HP            | EliteBook 2560p             | [5f1e0dfee7](https://linux-hardware.org/?probe=5f1e0dfee7) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Acer          | Aspire ES1-523              | [242fc61e3a](https://linux-hardware.org/?probe=242fc61e3a) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [b9a30cba65](https://linux-hardware.org/?probe=b9a30cba65) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [3c14a5bf10](https://linux-hardware.org/?probe=3c14a5bf10) | Jun 08, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | V330-14ARR 81B1             | [dad2acbf49](https://linux-hardware.org/?probe=dad2acbf49) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| HP            | ProBook 6450b               | [8c35a4c278](https://linux-hardware.org/?probe=8c35a4c278) | May 26, 2022 |
| Dell          | Latitude E7440              | [975715a96b](https://linux-hardware.org/?probe=975715a96b) | May 26, 2022 |
| HP            | ProBook 6450b               | [863987eb13](https://linux-hardware.org/?probe=863987eb13) | May 26, 2022 |
| HP            | ProBook 650 G1              | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [62486fe8d6](https://linux-hardware.org/?probe=62486fe8d6) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f0f481f187](https://linux-hardware.org/?probe=f0f481f187) | May 21, 2022 |
| SLIMBOOK      | PROX14-10                   | [b0d5e9b290](https://linux-hardware.org/?probe=b0d5e9b290) | May 19, 2022 |
| Dell          | XPS 13 9370                 | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [6efbcdabfc](https://linux-hardware.org/?probe=6efbcdabfc) | May 17, 2022 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | [d3f3fff089](https://linux-hardware.org/?probe=d3f3fff089) | May 16, 2022 |
| Dell          | Precision 5750              | [11e888b7d9](https://linux-hardware.org/?probe=11e888b7d9) | May 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Packard Be... | EasyNote TE69BM             | [ed538d5b79](https://linux-hardware.org/?probe=ed538d5b79) | May 07, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [8694f28b60](https://linux-hardware.org/?probe=8694f28b60) | Apr 25, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [0cd6fe25ec](https://linux-hardware.org/?probe=0cd6fe25ec) | Apr 22, 2022 |
| Acer          | Aspire E5-553               | [1c736596fa](https://linux-hardware.org/?probe=1c736596fa) | Apr 21, 2022 |
| Lenovo        | B575e 36852EG               | [8f5e5f427a](https://linux-hardware.org/?probe=8f5e5f427a) | Apr 18, 2022 |
| Lenovo        | B575e 36852EG               | [4731516b58](https://linux-hardware.org/?probe=4731516b58) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440 20B7S1EV00    | [b035e7ae3e](https://linux-hardware.org/?probe=b035e7ae3e) | Apr 16, 2022 |
| HP            | EliteBook 820 G3            | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| MSI           | GF63 Thin 10SC              | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Acer          | Aspire V5-573G              | [2b608bcde8](https://linux-hardware.org/?probe=2b608bcde8) | Apr 04, 2022 |
| Lenovo        | ThinkPad X390 20Q0002LMX    | [22aaabe433](https://linux-hardware.org/?probe=22aaabe433) | Apr 03, 2022 |
| HP            | Laptop 14-dk1xxx            | [0ba5fd01fa](https://linux-hardware.org/?probe=0ba5fd01fa) | Mar 30, 2022 |
| HP            | Laptop 15-bw0xx             | [b9a21aea35](https://linux-hardware.org/?probe=b9a21aea35) | Mar 29, 2022 |
| Lenovo        | E31-80 80MX                 | [8dc93e34e9](https://linux-hardware.org/?probe=8dc93e34e9) | Mar 25, 2022 |
| HP            | Pavilion Notebook           | [3bf42ed5a6](https://linux-hardware.org/?probe=3bf42ed5a6) | Mar 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [72da14a2b2](https://linux-hardware.org/?probe=72da14a2b2) | Mar 23, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Apple         | MacBookPro11,5              | [abc4597fe1](https://linux-hardware.org/?probe=abc4597fe1) | Mar 18, 2022 |
| Notebook      | P65xHP                      | [3222aab43a](https://linux-hardware.org/?probe=3222aab43a) | Mar 16, 2022 |
| Acer          | Aspire 3830T                | [bad3a5c2d7](https://linux-hardware.org/?probe=bad3a5c2d7) | Mar 15, 2022 |
| HP            | EliteBook 850 G5            | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Latitude E6410              | [d4fa7879a4](https://linux-hardware.org/?probe=d4fa7879a4) | Mar 09, 2022 |
| Dell          | Precision M4800             | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| Dell          | Latitude E6410              | [6748e5a7aa](https://linux-hardware.org/?probe=6748e5a7aa) | Feb 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [30879c05cc](https://linux-hardware.org/?probe=30879c05cc) | Feb 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [505e1dc8cc](https://linux-hardware.org/?probe=505e1dc8cc) | Feb 21, 2022 |
| Lenovo        | ThinkPad L530 24812SG       | [6eb3e0ed53](https://linux-hardware.org/?probe=6eb3e0ed53) | Feb 19, 2022 |
| HP            | Pavilion g6                 | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-575               | [3e75911df8](https://linux-hardware.org/?probe=3e75911df8) | Feb 12, 2022 |
| Apple         | MacBookPro7,1               | [b059819620](https://linux-hardware.org/?probe=b059819620) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | [87f4740598](https://linux-hardware.org/?probe=87f4740598) | Feb 11, 2022 |
| Toshiba       | Satellite L40               | [ba6d18935b](https://linux-hardware.org/?probe=ba6d18935b) | Feb 08, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| Medion        | P7612                       | [e1c076ee06](https://linux-hardware.org/?probe=e1c076ee06) | Feb 03, 2022 |
| HP            | Compaq Presario CQ71        | [436407f045](https://linux-hardware.org/?probe=436407f045) | Feb 01, 2022 |
| Lenovo        | B50-50 80S2                 | [7602963c65](https://linux-hardware.org/?probe=7602963c65) | Feb 01, 2022 |
| Dell          | Latitude E6540              | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [478d5281bd](https://linux-hardware.org/?probe=478d5281bd) | Jan 29, 2022 |
| HP            | Pavilion dv7                | [e6ec9b5f6a](https://linux-hardware.org/?probe=e6ec9b5f6a) | Jan 26, 2022 |
| Medion        | P7612                       | [50be4d531e](https://linux-hardware.org/?probe=50be4d531e) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| HP            | EliteBook 840 G3            | [82cce77f87](https://linux-hardware.org/?probe=82cce77f87) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| DukaPC        | Notebook                    | [21b4827b4b](https://linux-hardware.org/?probe=21b4827b4b) | Jan 21, 2022 |
| Acer          | Aspire F5-572G              | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [cc39f1fd96](https://linux-hardware.org/?probe=cc39f1fd96) | Jan 18, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4ebb815948](https://linux-hardware.org/?probe=4ebb815948) | Jan 15, 2022 |
| HP            | Pavilion g7                 | [6efd331acf](https://linux-hardware.org/?probe=6efd331acf) | Jan 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [4cefa23802](https://linux-hardware.org/?probe=4cefa23802) | Jan 14, 2022 |
| Acer          | Aspire E5-553               | [149c0538ca](https://linux-hardware.org/?probe=149c0538ca) | Jan 13, 2022 |
| Lenovo        | M30-70 80H8                 | [2f61d772a4](https://linux-hardware.org/?probe=2f61d772a4) | Jan 12, 2022 |
| Lenovo        | Y50-70 20378                | [ab93bc517a](https://linux-hardware.org/?probe=ab93bc517a) | Jan 12, 2022 |
| Razer         | Blade                       | [afad6aaa95](https://linux-hardware.org/?probe=afad6aaa95) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1f327abc43](https://linux-hardware.org/?probe=1f327abc43) | Jan 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [53a3989606](https://linux-hardware.org/?probe=53a3989606) | Jan 03, 2022 |
| Acer          | Aspire V5-573G              | [a7e3940936](https://linux-hardware.org/?probe=a7e3940936) | Jan 02, 2022 |
| Dell          | Inspiron 7720               | [4e1ebc00ff](https://linux-hardware.org/?probe=4e1ebc00ff) | Jan 02, 2022 |
| Apple         | MacBookAir7,2               | [6246bb8ef6](https://linux-hardware.org/?probe=6246bb8ef6) | Dec 31, 2021 |
| Lenovo        | V330-14ARR 81B1             | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [369d18645c](https://linux-hardware.org/?probe=369d18645c) | Dec 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [e68ec90909](https://linux-hardware.org/?probe=e68ec90909) | Dec 24, 2021 |
| Medion        | P6630                       | [de245dfdb6](https://linux-hardware.org/?probe=de245dfdb6) | Dec 23, 2021 |
| Notebook      | N24_25JU                    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Quanta        | MW1/HW1                     | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| ASUSTek       | K53SV                       | [be7844ea44](https://linux-hardware.org/?probe=be7844ea44) | Dec 17, 2021 |
| Lenovo        | ThinkPad T460s 20FAS05Q0... | [3a4b9beb1d](https://linux-hardware.org/?probe=3a4b9beb1d) | Dec 12, 2021 |
| Toshiba       | Satellite P850              | [bfc37f531a](https://linux-hardware.org/?probe=bfc37f531a) | Dec 11, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [e7144e5f86](https://linux-hardware.org/?probe=e7144e5f86) | Dec 09, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | [7ff3493cfe](https://linux-hardware.org/?probe=7ff3493cfe) | Dec 08, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| DukaPC        | Notebook                    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| Razer         | Blade Stealth               | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [c224ffa45a](https://linux-hardware.org/?probe=c224ffa45a) | Nov 23, 2021 |
| Toshiba       | Satellite U300              | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| Dell          | Inspiron 7572               | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Acer          | Aspire 5810T                | [c41d1671bc](https://linux-hardware.org/?probe=c41d1671bc) | Nov 14, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e03bf03f1d](https://linux-hardware.org/?probe=e03bf03f1d) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [1def6bd5d8](https://linux-hardware.org/?probe=1def6bd5d8) | Nov 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d2a33ad9d9](https://linux-hardware.org/?probe=d2a33ad9d9) | Nov 07, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Apple         | MacBookPro14,1              | [68ebc1af79](https://linux-hardware.org/?probe=68ebc1af79) | Oct 28, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| Unknown       | Unknown                     | [a6e5e7b6ef](https://linux-hardware.org/?probe=a6e5e7b6ef) | Oct 18, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a7fa6a8110](https://linux-hardware.org/?probe=a7fa6a8110) | Oct 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Toshiba       | Satellite P55W-C            | [f16be2ec1b](https://linux-hardware.org/?probe=f16be2ec1b) | Oct 13, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Acer          | Aspire A315-41              | [3d5d3ddf84](https://linux-hardware.org/?probe=3d5d3ddf84) | Oct 09, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [93c695e5ba](https://linux-hardware.org/?probe=93c695e5ba) | Oct 08, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [85a242883c](https://linux-hardware.org/?probe=85a242883c) | Oct 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [56ce2c44cb](https://linux-hardware.org/?probe=56ce2c44cb) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [4d0eb4ccf2](https://linux-hardware.org/?probe=4d0eb4ccf2) | Oct 04, 2021 |
| Lenovo        | V330-14ARR 81B1             | [c8a0e5de69](https://linux-hardware.org/?probe=c8a0e5de69) | Oct 04, 2021 |
| HUAWEI        | EUL-WX9                     | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | Pavilion dv7                | [31b035faec](https://linux-hardware.org/?probe=31b035faec) | Sep 28, 2021 |
| Acer          | Aspire 5810T                | [be3f4d5a01](https://linux-hardware.org/?probe=be3f4d5a01) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [edfae5b796](https://linux-hardware.org/?probe=edfae5b796) | Sep 25, 2021 |
| HUAWEI        | MACHC-WAX9                  | [e2fc9d2585](https://linux-hardware.org/?probe=e2fc9d2585) | Sep 23, 2021 |
| Dell          | XPS 13 9370                 | [5df047615c](https://linux-hardware.org/?probe=5df047615c) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [d7ccece3d4](https://linux-hardware.org/?probe=d7ccece3d4) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [466841a201](https://linux-hardware.org/?probe=466841a201) | Sep 22, 2021 |
| HP            | ZBook 15                    | [206882306c](https://linux-hardware.org/?probe=206882306c) | Sep 20, 2021 |
| Lenovo        | V130-15IKB 81HN             | [f427b869d9](https://linux-hardware.org/?probe=f427b869d9) | Sep 17, 2021 |
| Lenovo        | ThinkPad X220 4291WAY       | [ca0ab89977](https://linux-hardware.org/?probe=ca0ab89977) | Sep 16, 2021 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [8dd2c7497e](https://linux-hardware.org/?probe=8dd2c7497e) | Sep 13, 2021 |
| Dell          | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| HP            | Pavilion dv7                | [2fd3b811f6](https://linux-hardware.org/?probe=2fd3b811f6) | Sep 12, 2021 |
| Dell          | XPS 15 9510                 | [1b80533734](https://linux-hardware.org/?probe=1b80533734) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | [4befd2306c](https://linux-hardware.org/?probe=4befd2306c) | Sep 11, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5cf3ed1411](https://linux-hardware.org/?probe=5cf3ed1411) | Aug 31, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [70585e2360](https://linux-hardware.org/?probe=70585e2360) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [9c0457479f](https://linux-hardware.org/?probe=9c0457479f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [23b7937411](https://linux-hardware.org/?probe=23b7937411) | Aug 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [9382443dc7](https://linux-hardware.org/?probe=9382443dc7) | Aug 27, 2021 |
| Google        | Relm                        | [12475037ed](https://linux-hardware.org/?probe=12475037ed) | Aug 27, 2021 |
| Google        | Relm                        | [36e7a1d7a1](https://linux-hardware.org/?probe=36e7a1d7a1) | Aug 26, 2021 |
| HP            | ProBook 650 G1              | [61f6289d2c](https://linux-hardware.org/?probe=61f6289d2c) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| HP            | ZBook 15 G6                 | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [8e75269d33](https://linux-hardware.org/?probe=8e75269d33) | Aug 20, 2021 |
| Lenovo        | G550 2958                   | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| HP            | ProBook 445 G7              | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| GPD           | P2 MAX                      | [78f79b2790](https://linux-hardware.org/?probe=78f79b2790) | Jul 31, 2021 |
| ASUSTek       | GL702VM                     | [bb9d228646](https://linux-hardware.org/?probe=bb9d228646) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [a02dac8dff](https://linux-hardware.org/?probe=a02dac8dff) | Jul 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [e52365f866](https://linux-hardware.org/?probe=e52365f866) | Jul 21, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [704fb2e1d1](https://linux-hardware.org/?probe=704fb2e1d1) | Jul 21, 2021 |
| Dell          | Latitude 7370               | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [7a03dbd869](https://linux-hardware.org/?probe=7a03dbd869) | Jul 17, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [ce58f3f770](https://linux-hardware.org/?probe=ce58f3f770) | Jul 16, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [a56195f1f1](https://linux-hardware.org/?probe=a56195f1f1) | Jul 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [440841d04a](https://linux-hardware.org/?probe=440841d04a) | Jul 12, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [3b106f1da0](https://linux-hardware.org/?probe=3b106f1da0) | Jul 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [f8872c9e84](https://linux-hardware.org/?probe=f8872c9e84) | Jul 05, 2021 |
| AMI           | Cherry Trail CR             | [4e6f9ccc6c](https://linux-hardware.org/?probe=4e6f9ccc6c) | Jul 05, 2021 |
| DukaPC        | Notebook                    | [6d87054512](https://linux-hardware.org/?probe=6d87054512) | Jul 02, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| Timi          | TM1703                      | [bd3756811d](https://linux-hardware.org/?probe=bd3756811d) | Jun 26, 2021 |
| DukaPC        | Notebook                    | [c29d208cdf](https://linux-hardware.org/?probe=c29d208cdf) | Jun 24, 2021 |
| Lenovo        | ThinkPad T420 4236Y19       | [48927432b4](https://linux-hardware.org/?probe=48927432b4) | Jun 20, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d8ad69d368](https://linux-hardware.org/?probe=d8ad69d368) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0Y70... | [5e57af6782](https://linux-hardware.org/?probe=5e57af6782) | Jun 11, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | [fa5abfccf8](https://linux-hardware.org/?probe=fa5abfccf8) | Jun 04, 2021 |
| HP            | Compaq Presario CQ71        | [d4deb2b08d](https://linux-hardware.org/?probe=d4deb2b08d) | Jun 01, 2021 |
| Dell          | Latitude E6520              | [d1d0976880](https://linux-hardware.org/?probe=d1d0976880) | May 31, 2021 |
| Lenovo        | ThinkPad T400 647358G       | [b4f44d7932](https://linux-hardware.org/?probe=b4f44d7932) | May 29, 2021 |
| Toshiba       | Satellite C660              | [58d3740c30](https://linux-hardware.org/?probe=58d3740c30) | May 28, 2021 |
| Acer          | Aspire E5-553               | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| LAMINA        | T-1012B NORD                | [71e70e946a](https://linux-hardware.org/?probe=71e70e946a) | May 25, 2021 |
| LAMINA        | T-1012B NORD                | [9dc2932064](https://linux-hardware.org/?probe=9dc2932064) | May 24, 2021 |
| ASUSTek       | X553SA                      | [c470382d2a](https://linux-hardware.org/?probe=c470382d2a) | May 24, 2021 |
| ASUSTek       | X553SA                      | [31d6a914fd](https://linux-hardware.org/?probe=31d6a914fd) | May 24, 2021 |
| Acer          | Aspire E5-511               | [9edec55620](https://linux-hardware.org/?probe=9edec55620) | May 23, 2021 |
| Acer          | Aspire E5-511               | [e20c93a2c1](https://linux-hardware.org/?probe=e20c93a2c1) | May 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a9e4c7793b](https://linux-hardware.org/?probe=a9e4c7793b) | May 18, 2021 |
| eMachines     | E725                        | [329f8f580e](https://linux-hardware.org/?probe=329f8f580e) | May 14, 2021 |
| ASUSTek       | K95VM                       | [58d4ed3c2b](https://linux-hardware.org/?probe=58d4ed3c2b) | May 10, 2021 |
| HP            | 15                          | [a13c097d59](https://linux-hardware.org/?probe=a13c097d59) | May 09, 2021 |
| HP            | 15                          | [c3cdcdab60](https://linux-hardware.org/?probe=c3cdcdab60) | May 09, 2021 |
| Alienware     | 17 R2                       | [a8470edc65](https://linux-hardware.org/?probe=a8470edc65) | May 06, 2021 |
| ASUSTek       | G74Sx                       | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| Lenovo        | ThinkPad T520 4243PC2       | [915d41f361](https://linux-hardware.org/?probe=915d41f361) | Apr 29, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [e2f8b2beda](https://linux-hardware.org/?probe=e2f8b2beda) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [684f1471b1](https://linux-hardware.org/?probe=684f1471b1) | Apr 23, 2021 |
| Lenovo        | E31-80 80MX                 | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [bd14a696eb](https://linux-hardware.org/?probe=bd14a696eb) | Apr 20, 2021 |
| Lenovo        | ThinkPad T520 42434YG       | [8e0b4ee3a1](https://linux-hardware.org/?probe=8e0b4ee3a1) | Apr 17, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [49e1959064](https://linux-hardware.org/?probe=49e1959064) | Apr 16, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [b2853266e8](https://linux-hardware.org/?probe=b2853266e8) | Apr 15, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [4b127c0ba4](https://linux-hardware.org/?probe=4b127c0ba4) | Apr 11, 2021 |
| HP            | Laptop 15-da1xxx            | [a844e710cc](https://linux-hardware.org/?probe=a844e710cc) | Apr 09, 2021 |
| Lenovo        | ThinkPad T60 20076RG        | [aa3ea77acf](https://linux-hardware.org/?probe=aa3ea77acf) | Apr 08, 2021 |
| HP            | G72                         | [2ab4eb5fcd](https://linux-hardware.org/?probe=2ab4eb5fcd) | Apr 05, 2021 |
| ASUSTek       | K95VM                       | [81a01884d2](https://linux-hardware.org/?probe=81a01884d2) | Mar 24, 2021 |
| Lenovo        | ThinkPad W520 4284Y54       | [8d564e495b](https://linux-hardware.org/?probe=8d564e495b) | Mar 23, 2021 |
| Toshiba       | Satellite L350D             | [b083513b72](https://linux-hardware.org/?probe=b083513b72) | Mar 23, 2021 |
| Acer          | Aspire E5-553               | [0c21dc1b96](https://linux-hardware.org/?probe=0c21dc1b96) | Mar 19, 2021 |
| HP            | Pavilion dm1                | [438cf03315](https://linux-hardware.org/?probe=438cf03315) | Mar 18, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [7e7a4bc992](https://linux-hardware.org/?probe=7e7a4bc992) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [1b8a078a19](https://linux-hardware.org/?probe=1b8a078a19) | Mar 16, 2021 |
| HP            | EliteBook 830 G5            | [248eb896a0](https://linux-hardware.org/?probe=248eb896a0) | Mar 15, 2021 |
| HP            | Compaq Presario CQ60        | [e4613a6f75](https://linux-hardware.org/?probe=e4613a6f75) | Mar 15, 2021 |
| Dell          | Latitude E5250              | [22067e0909](https://linux-hardware.org/?probe=22067e0909) | Mar 13, 2021 |
| Dell          | Latitude E5250              | [df9d913f0f](https://linux-hardware.org/?probe=df9d913f0f) | Mar 13, 2021 |
| HP            | Pavilion dv9700             | [f55ec4dd18](https://linux-hardware.org/?probe=f55ec4dd18) | Mar 11, 2021 |
| Dell          | XPS 13 9370                 | [865e070587](https://linux-hardware.org/?probe=865e070587) | Mar 10, 2021 |
| Dell          | Latitude E5250              | [78f0a24d9a](https://linux-hardware.org/?probe=78f0a24d9a) | Mar 07, 2021 |
| Acer          | Aspire E5-575G              | [18240d24d8](https://linux-hardware.org/?probe=18240d24d8) | Mar 06, 2021 |
| Toshiba       | Satellite L350D             | [ef8a29af20](https://linux-hardware.org/?probe=ef8a29af20) | Mar 05, 2021 |
| Acer          | Aspire E5-553               | [74e6da0017](https://linux-hardware.org/?probe=74e6da0017) | Feb 27, 2021 |
| HP            | 630                         | [6803747e34](https://linux-hardware.org/?probe=6803747e34) | Feb 22, 2021 |
| HP            | 630                         | [8b04fe81aa](https://linux-hardware.org/?probe=8b04fe81aa) | Feb 22, 2021 |
| Lenovo        | ThinkPad T61 7661W1D        | [6db91fdd34](https://linux-hardware.org/?probe=6db91fdd34) | Feb 17, 2021 |
| Lenovo        | 3000 G530 444622G           | [3ef99e25df](https://linux-hardware.org/?probe=3ef99e25df) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMA2AE00    | [2730f6215a](https://linux-hardware.org/?probe=2730f6215a) | Feb 12, 2021 |
| Dell          | XPS 13 9360                 | [564f71d6f3](https://linux-hardware.org/?probe=564f71d6f3) | Feb 10, 2021 |
| Acer          | Aspire E5-553               | [ab7532985d](https://linux-hardware.org/?probe=ab7532985d) | Feb 05, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [ed806c00b2](https://linux-hardware.org/?probe=ed806c00b2) | Feb 04, 2021 |
| HP            | EliteBook 2560p             | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| HP            | EliteBook 840 G5            | [19ef5f3adb](https://linux-hardware.org/?probe=19ef5f3adb) | Jan 29, 2021 |
| Dell          | Latitude E7440              | [ee2c17a895](https://linux-hardware.org/?probe=ee2c17a895) | Jan 26, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [964b7c1b1f](https://linux-hardware.org/?probe=964b7c1b1f) | Jan 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [82da77953a](https://linux-hardware.org/?probe=82da77953a) | Jan 19, 2021 |
| Dell          | Latitude 5500               | [d7e06bd87b](https://linux-hardware.org/?probe=d7e06bd87b) | Jan 18, 2021 |
| Dell          | Latitude 5500               | [f40a2d50bc](https://linux-hardware.org/?probe=f40a2d50bc) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| Lenovo        | ThinkPad P52 20M9001GMX     | [ffdee2c6e0](https://linux-hardware.org/?probe=ffdee2c6e0) | Jan 11, 2021 |
| Dell          | XPS 13 9300                 | [229b46a693](https://linux-hardware.org/?probe=229b46a693) | Jan 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [fa963386d8](https://linux-hardware.org/?probe=fa963386d8) | Jan 07, 2021 |
| Toshiba       | Satellite L40               | [bd26bbbe43](https://linux-hardware.org/?probe=bd26bbbe43) | Jan 06, 2021 |
| Lenovo        | G570 4334                   | [c643363b80](https://linux-hardware.org/?probe=c643363b80) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2ed1a3283e](https://linux-hardware.org/?probe=2ed1a3283e) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c0c38c5aee](https://linux-hardware.org/?probe=c0c38c5aee) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [65fe7eb049](https://linux-hardware.org/?probe=65fe7eb049) | Dec 30, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3f9fc25d4](https://linux-hardware.org/?probe=c3f9fc25d4) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [dbc2669fc0](https://linux-hardware.org/?probe=dbc2669fc0) | Dec 28, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [f514e54057](https://linux-hardware.org/?probe=f514e54057) | Dec 28, 2020 |
| ASUSTek       | PU401LAC                    | [c5bf49eabf](https://linux-hardware.org/?probe=c5bf49eabf) | Dec 26, 2020 |
| HP            | EliteBook 850 G5            | [ce2a32dd24](https://linux-hardware.org/?probe=ce2a32dd24) | Dec 22, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3e419467e2](https://linux-hardware.org/?probe=3e419467e2) | Dec 22, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [87c08ecbb6](https://linux-hardware.org/?probe=87c08ecbb6) | Dec 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [52e86fd2a9](https://linux-hardware.org/?probe=52e86fd2a9) | Dec 20, 2020 |
| Lenovo        | ThinkPad T490s 20NX001PM... | [af7d2d4eb5](https://linux-hardware.org/?probe=af7d2d4eb5) | Dec 20, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [14a84d3948](https://linux-hardware.org/?probe=14a84d3948) | Dec 20, 2020 |
| Lenovo        | ThinkPad T520 4243W54       | [15862aca5c](https://linux-hardware.org/?probe=15862aca5c) | Dec 20, 2020 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [01b87f6602](https://linux-hardware.org/?probe=01b87f6602) | Dec 18, 2020 |
| Lenovo        | Unknown                     | [92b19a0db9](https://linux-hardware.org/?probe=92b19a0db9) | Dec 18, 2020 |
| Dell          | Latitude E7270              | [bac2c2820f](https://linux-hardware.org/?probe=bac2c2820f) | Dec 17, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [5dfa78d268](https://linux-hardware.org/?probe=5dfa78d268) | Dec 15, 2020 |
| HP            | ProBook 650 G5              | [56c46edc3f](https://linux-hardware.org/?probe=56c46edc3f) | Dec 13, 2020 |
| HP            | ProBook 650 G5              | [a035f76fcb](https://linux-hardware.org/?probe=a035f76fcb) | Dec 12, 2020 |
| Acer          | Extensa 2519                | [17bdd3b68f](https://linux-hardware.org/?probe=17bdd3b68f) | Dec 10, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [e9f3972862](https://linux-hardware.org/?probe=e9f3972862) | Dec 04, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [f98c566bb6](https://linux-hardware.org/?probe=f98c566bb6) | Dec 03, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [ff051ee214](https://linux-hardware.org/?probe=ff051ee214) | Dec 01, 2020 |
| Dell          | Latitude E6540              | [5a0fbaa262](https://linux-hardware.org/?probe=5a0fbaa262) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8b31225bd7](https://linux-hardware.org/?probe=8b31225bd7) | Nov 27, 2020 |
| Apple         | MacBookPro7,1               | [ad6bb1f253](https://linux-hardware.org/?probe=ad6bb1f253) | Nov 24, 2020 |
| Lenovo        | ThinkPad P52 20M9001MMD     | [72ba2ae6cb](https://linux-hardware.org/?probe=72ba2ae6cb) | Nov 19, 2020 |
| Acer          | Aspire V3-575G              | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| Dell          | System XPS L321X            | [3fb9a4373c](https://linux-hardware.org/?probe=3fb9a4373c) | Nov 18, 2020 |
| Lenovo        | ThinkPad T530 24292VG       | [3460614c7f](https://linux-hardware.org/?probe=3460614c7f) | Nov 15, 2020 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [ee5da1d9b0](https://linux-hardware.org/?probe=ee5da1d9b0) | Nov 10, 2020 |
| Lenovo        | ThinkPad X301 2776LEG       | [2c4aa61663](https://linux-hardware.org/?probe=2c4aa61663) | Nov 09, 2020 |
| Dell          | XPS 13 9370                 | [b75b281fee](https://linux-hardware.org/?probe=b75b281fee) | Nov 08, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de9ea1422c](https://linux-hardware.org/?probe=de9ea1422c) | Nov 08, 2020 |
| HP            | Pavilion Notebook           | [1698bf3366](https://linux-hardware.org/?probe=1698bf3366) | Nov 07, 2020 |
| HP            | EliteBook 820 G3            | [e34831e959](https://linux-hardware.org/?probe=e34831e959) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | [bb40872a6b](https://linux-hardware.org/?probe=bb40872a6b) | Nov 05, 2020 |
| HP            | ProBook 4720s               | [acb46376ad](https://linux-hardware.org/?probe=acb46376ad) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [d65f8070e0](https://linux-hardware.org/?probe=d65f8070e0) | Nov 03, 2020 |
| HP            | Compaq 8510p                | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | XPS 15 9560                 | [5e06a37540](https://linux-hardware.org/?probe=5e06a37540) | Nov 01, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [1213098826](https://linux-hardware.org/?probe=1213098826) | Oct 30, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [de02478ef0](https://linux-hardware.org/?probe=de02478ef0) | Oct 29, 2020 |
| Lenovo        | E31-80 80MX                 | [d56dacea36](https://linux-hardware.org/?probe=d56dacea36) | Oct 29, 2020 |
| Razer         | Blade                       | [7aef75c2c6](https://linux-hardware.org/?probe=7aef75c2c6) | Oct 28, 2020 |
| Dell          | Vostro 3558                 | [eda9a94c60](https://linux-hardware.org/?probe=eda9a94c60) | Oct 28, 2020 |
| Acer          | Nitro AN515-53              | [08235cd1ad](https://linux-hardware.org/?probe=08235cd1ad) | Oct 25, 2020 |
| Acer          | Nitro AN515-53              | [80a32fe04b](https://linux-hardware.org/?probe=80a32fe04b) | Oct 24, 2020 |
| Dell          | Vostro 3558                 | [e22529c904](https://linux-hardware.org/?probe=e22529c904) | Oct 23, 2020 |
| Apple         | MacBookPro5,5               | [b7c6f0c157](https://linux-hardware.org/?probe=b7c6f0c157) | Oct 22, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [cbd374b1d9](https://linux-hardware.org/?probe=cbd374b1d9) | Oct 22, 2020 |
| Toshiba       | Satellite L40               | [3d02e46571](https://linux-hardware.org/?probe=3d02e46571) | Oct 22, 2020 |
| HP            | EliteBook 850 G5            | [1a2d14ded4](https://linux-hardware.org/?probe=1a2d14ded4) | Oct 20, 2020 |
| HP            | Pavilion dv6                | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| Toshiba       | Satellite P50-A-11J         | [720f19d566](https://linux-hardware.org/?probe=720f19d566) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [20453e8620](https://linux-hardware.org/?probe=20453e8620) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [eee8f03871](https://linux-hardware.org/?probe=eee8f03871) | Oct 10, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [4ffeac234f](https://linux-hardware.org/?probe=4ffeac234f) | Oct 09, 2020 |
| Acer          | Nitro AN515-53              | [fe2889ef02](https://linux-hardware.org/?probe=fe2889ef02) | Oct 08, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | [bea20b3463](https://linux-hardware.org/?probe=bea20b3463) | Oct 04, 2020 |
| Acer          | Aspire 7551                 | [0524a7f258](https://linux-hardware.org/?probe=0524a7f258) | Oct 04, 2020 |
| Acer          | Aspire VN7-792G             | [908eea39dd](https://linux-hardware.org/?probe=908eea39dd) | Oct 04, 2020 |
| Acer          | Nitro AN515-53              | [a1d00d9bc3](https://linux-hardware.org/?probe=a1d00d9bc3) | Oct 03, 2020 |
| Acer          | Nitro AN515-53              | [be2aafbbae](https://linux-hardware.org/?probe=be2aafbbae) | Oct 03, 2020 |
| HP            | ProBook 650 G2              | [f04b6dbdc5](https://linux-hardware.org/?probe=f04b6dbdc5) | Oct 02, 2020 |
| HP            | ProBook 650 G2              | [7b826236e8](https://linux-hardware.org/?probe=7b826236e8) | Oct 02, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [9a69eca48e](https://linux-hardware.org/?probe=9a69eca48e) | Oct 01, 2020 |
| Acer          | AOD270                      | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [3b51f51354](https://linux-hardware.org/?probe=3b51f51354) | Sep 29, 2020 |
| Notebook      | W54_55SU1,SUW               | [8616e28654](https://linux-hardware.org/?probe=8616e28654) | Sep 29, 2020 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [a3846db026](https://linux-hardware.org/?probe=a3846db026) | Sep 26, 2020 |
| Lenovo        | G710 20252                  | [6d3ef693db](https://linux-hardware.org/?probe=6d3ef693db) | Sep 23, 2020 |
| HP            | Pavilion Sleekbook 15       | [d5217dd737](https://linux-hardware.org/?probe=d5217dd737) | Sep 20, 2020 |
| Google        | Liara                       | [e6434b38e5](https://linux-hardware.org/?probe=e6434b38e5) | Sep 16, 2020 |
| HP            | 620                         | [3cd40bde20](https://linux-hardware.org/?probe=3cd40bde20) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [1f2fba4e2e](https://linux-hardware.org/?probe=1f2fba4e2e) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [46f7d12d9e](https://linux-hardware.org/?probe=46f7d12d9e) | Sep 11, 2020 |
| HP            | EliteBook 850 G5            | [826772015a](https://linux-hardware.org/?probe=826772015a) | Sep 09, 2020 |
| LG Electro... | 17Z90N-V.AA77G              | [eaeb99f180](https://linux-hardware.org/?probe=eaeb99f180) | Sep 06, 2020 |
| Apple         | MacBookPro10,1              | [3d676f563d](https://linux-hardware.org/?probe=3d676f563d) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325W3J       | [b076277c46](https://linux-hardware.org/?probe=b076277c46) | Sep 05, 2020 |
| Lenovo        | ThinkPad X240 20AMS39B00    | [b2f7ace5e9](https://linux-hardware.org/?probe=b2f7ace5e9) | Sep 05, 2020 |
| Notebook      | W35xSTQ_370ST               | [69960189a7](https://linux-hardware.org/?probe=69960189a7) | Sep 04, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [392b8d8877](https://linux-hardware.org/?probe=392b8d8877) | Sep 04, 2020 |
| Lenovo        | V110-15IAP 80TG             | [74a552046a](https://linux-hardware.org/?probe=74a552046a) | Sep 02, 2020 |
| Toshiba       | Satellite L755D             | [e3aa57d80d](https://linux-hardware.org/?probe=e3aa57d80d) | Aug 30, 2020 |
| HP            | 620                         | [2abb876aa3](https://linux-hardware.org/?probe=2abb876aa3) | Aug 27, 2020 |
| Purism        | Librem 13 v2                | [23cd34d2f6](https://linux-hardware.org/?probe=23cd34d2f6) | Aug 27, 2020 |
| HP            | Pavilion dm1                | [39154c83b0](https://linux-hardware.org/?probe=39154c83b0) | Aug 27, 2020 |
| Acer          | NC-SF314-51-56Y4            | [0627a672e7](https://linux-hardware.org/?probe=0627a672e7) | Aug 27, 2020 |
| Lenovo        | Unknown                     | [74313d4eb1](https://linux-hardware.org/?probe=74313d4eb1) | Aug 24, 2020 |
| Lenovo        | ThinkPad P50s 20FLS02200    | [68d5ec0716](https://linux-hardware.org/?probe=68d5ec0716) | Aug 24, 2020 |
| HP            | ProBook 650 G2              | [4a91b4b21f](https://linux-hardware.org/?probe=4a91b4b21f) | Aug 18, 2020 |
| Razer         | Blade                       | [b8e7f44d4a](https://linux-hardware.org/?probe=b8e7f44d4a) | Aug 17, 2020 |
| HP            | EliteBook 820 G3            | [0d1ad99429](https://linux-hardware.org/?probe=0d1ad99429) | Aug 13, 2020 |
| Toshiba       | Satellite L40               | [33ec17e21b](https://linux-hardware.org/?probe=33ec17e21b) | Aug 13, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [8e3eee2d07](https://linux-hardware.org/?probe=8e3eee2d07) | Aug 06, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [6b9f38754c](https://linux-hardware.org/?probe=6b9f38754c) | Aug 06, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [72a1412fb1](https://linux-hardware.org/?probe=72a1412fb1) | Aug 04, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [133bc3dd52](https://linux-hardware.org/?probe=133bc3dd52) | Aug 04, 2020 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [6d4445f122](https://linux-hardware.org/?probe=6d4445f122) | Aug 02, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [c535bd5654](https://linux-hardware.org/?probe=c535bd5654) | Jul 29, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [fa42e14984](https://linux-hardware.org/?probe=fa42e14984) | Jul 28, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [e748a3510c](https://linux-hardware.org/?probe=e748a3510c) | Jul 27, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [3122f02f2c](https://linux-hardware.org/?probe=3122f02f2c) | Jul 23, 2020 |
| Packard Be... | EasyNote LJ73               | [b7cb387fea](https://linux-hardware.org/?probe=b7cb387fea) | Jul 21, 2020 |
| Dell          | Latitude E6420              | [e9238dcfff](https://linux-hardware.org/?probe=e9238dcfff) | Jul 19, 2020 |
| Dell          | Latitude E6420              | [231cadfc4a](https://linux-hardware.org/?probe=231cadfc4a) | Jul 19, 2020 |
| Toshiba       | Satellite L755D             | [a0cdb2f0bf](https://linux-hardware.org/?probe=a0cdb2f0bf) | Jul 12, 2020 |
| Toshiba       | Satellite L755D             | [f4ab460d93](https://linux-hardware.org/?probe=f4ab460d93) | Jul 12, 2020 |
| Dell          | Latitude 7480               | [c265940ec9](https://linux-hardware.org/?probe=c265940ec9) | Jul 11, 2020 |
| Apple         | MacBookPro6,1               | [432c9e6acf](https://linux-hardware.org/?probe=432c9e6acf) | Jul 05, 2020 |
| Apple         | MacBookPro14,1              | [b1b965bcfa](https://linux-hardware.org/?probe=b1b965bcfa) | Jul 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [26dfef89d5](https://linux-hardware.org/?probe=26dfef89d5) | Jun 30, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [3f43b86780](https://linux-hardware.org/?probe=3f43b86780) | Jun 29, 2020 |
| Fujitsu       | LIFEBOOK U938               | [445cfe436d](https://linux-hardware.org/?probe=445cfe436d) | Jun 28, 2020 |
| ASUSTek       | K56CB                       | [bbdd76a080](https://linux-hardware.org/?probe=bbdd76a080) | Jun 21, 2020 |
| Fujitsu       | LIFEBOOK U938               | [6fab40c5c2](https://linux-hardware.org/?probe=6fab40c5c2) | Jun 20, 2020 |
| Acer          | Mantasta                    | [fae9194978](https://linux-hardware.org/?probe=fae9194978) | Jun 19, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [12d9fce39b](https://linux-hardware.org/?probe=12d9fce39b) | Jun 18, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [8307e528e0](https://linux-hardware.org/?probe=8307e528e0) | Jun 17, 2020 |
| HP            | Pavilion 15                 | [6d0c4b8b4f](https://linux-hardware.org/?probe=6d0c4b8b4f) | Jun 16, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [c9de665933](https://linux-hardware.org/?probe=c9de665933) | Jun 14, 2020 |
| Dell          | Latitude 7480               | [f1120b6914](https://linux-hardware.org/?probe=f1120b6914) | Jun 14, 2020 |
| Dell          | XPS 15 9560                 | [68f8b211cb](https://linux-hardware.org/?probe=68f8b211cb) | Jun 13, 2020 |
| Dell          | XPS 15 9560                 | [5e9c9bd030](https://linux-hardware.org/?probe=5e9c9bd030) | Jun 13, 2020 |
| Razer         | Blade                       | [5ed51b12b4](https://linux-hardware.org/?probe=5ed51b12b4) | Jun 12, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [6e1571661e](https://linux-hardware.org/?probe=6e1571661e) | Jun 12, 2020 |
| Lenovo        | ThinkPad W520 4284Y19       | [ac2ade7339](https://linux-hardware.org/?probe=ac2ade7339) | Jun 07, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [1431224dcf](https://linux-hardware.org/?probe=1431224dcf) | Jun 03, 2020 |
| Dell          | XPS 15 7590                 | [386ef00203](https://linux-hardware.org/?probe=386ef00203) | May 25, 2020 |
| Dell          | XPS 15 7590                 | [544670327d](https://linux-hardware.org/?probe=544670327d) | May 21, 2020 |
| Acer          | TravelMate 6592             | [9bb4619272](https://linux-hardware.org/?probe=9bb4619272) | May 17, 2020 |
| Acer          | TravelMate 6592             | [e4e54de319](https://linux-hardware.org/?probe=e4e54de319) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [788a18932c](https://linux-hardware.org/?probe=788a18932c) | May 16, 2020 |
| Acer          | Swift SF514-52T             | [93ede38f81](https://linux-hardware.org/?probe=93ede38f81) | May 16, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [b47983a36a](https://linux-hardware.org/?probe=b47983a36a) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [5fbd9385df](https://linux-hardware.org/?probe=5fbd9385df) | May 13, 2020 |
| Lenovo        | ThinkPad T410 2522WPH       | [236d1e64eb](https://linux-hardware.org/?probe=236d1e64eb) | May 10, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a54bb2200a](https://linux-hardware.org/?probe=a54bb2200a) | May 06, 2020 |
| HP            | 255 G7 Notebook PC          | [0a904bfe70](https://linux-hardware.org/?probe=0a904bfe70) | May 05, 2020 |
| TUXEDO        | Unknown                     | [3f23947dd8](https://linux-hardware.org/?probe=3f23947dd8) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [b85ac004b3](https://linux-hardware.org/?probe=b85ac004b3) | May 04, 2020 |
| Lenovo        | ThinkPad T480s 20L8S5U50... | [d295ec1834](https://linux-hardware.org/?probe=d295ec1834) | May 03, 2020 |
| Dell          | Latitude E7450              | [0f14ff60e1](https://linux-hardware.org/?probe=0f14ff60e1) | May 02, 2020 |
| HP            | EliteBook 840 G1            | [9c6700839f](https://linux-hardware.org/?probe=9c6700839f) | May 01, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [689865b9bf](https://linux-hardware.org/?probe=689865b9bf) | Apr 30, 2020 |
| Acer          | Aspire A715-72G             | [db52ab416a](https://linux-hardware.org/?probe=db52ab416a) | Apr 29, 2020 |
| HP            | EliteBook 840 G1            | [b77a2c1bdc](https://linux-hardware.org/?probe=b77a2c1bdc) | Apr 27, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [2ea2bebae7](https://linux-hardware.org/?probe=2ea2bebae7) | Apr 25, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [47ae6712b9](https://linux-hardware.org/?probe=47ae6712b9) | Apr 25, 2020 |
| HP            | Unknown                     | [7da32c9344](https://linux-hardware.org/?probe=7da32c9344) | Apr 21, 2020 |
| Dell          | Latitude E5510              | [a70ec059cf](https://linux-hardware.org/?probe=a70ec059cf) | Apr 13, 2020 |
| HP            | Pavilion dv9700             | [6096eebeb4](https://linux-hardware.org/?probe=6096eebeb4) | Apr 11, 2020 |
| Apple         | MacBookPro5,5               | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Lenovo        | B50-10 80QR                 | [587fb80750](https://linux-hardware.org/?probe=587fb80750) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [bfb0ade0c7](https://linux-hardware.org/?probe=bfb0ade0c7) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [26154d1d2c](https://linux-hardware.org/?probe=26154d1d2c) | Apr 01, 2020 |
| ASUSTek       | N76VB                       | [a771ac7748](https://linux-hardware.org/?probe=a771ac7748) | Mar 24, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [069d575f4a](https://linux-hardware.org/?probe=069d575f4a) | Mar 21, 2020 |
| HP            | Pavilion dv7                | [64000a6ec8](https://linux-hardware.org/?probe=64000a6ec8) | Mar 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [69559fb5ce](https://linux-hardware.org/?probe=69559fb5ce) | Mar 18, 2020 |
| Toshiba       | Satellite C670D-10C         | [bdcd7e9b36](https://linux-hardware.org/?probe=bdcd7e9b36) | Mar 17, 2020 |
| Toshiba       | Satellite C670D-10C         | [ab2ea68be0](https://linux-hardware.org/?probe=ab2ea68be0) | Mar 17, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [86e1d115b9](https://linux-hardware.org/?probe=86e1d115b9) | Mar 15, 2020 |
| HP            | ProBook 4720s               | [a32d5c092c](https://linux-hardware.org/?probe=a32d5c092c) | Mar 15, 2020 |
| Toshiba       | Satellite L40               | [467c320928](https://linux-hardware.org/?probe=467c320928) | Mar 11, 2020 |
| Lenovo        | ThinkPad Edge E530 3259C... | [7e0acb9bed](https://linux-hardware.org/?probe=7e0acb9bed) | Mar 06, 2020 |
| HP            | ProBook 4720s               | [823553cfbd](https://linux-hardware.org/?probe=823553cfbd) | Mar 03, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [de25ec2891](https://linux-hardware.org/?probe=de25ec2891) | Feb 28, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [b333f7015a](https://linux-hardware.org/?probe=b333f7015a) | Feb 28, 2020 |
| HP            | ZBook 14u G5                | [03871e6b83](https://linux-hardware.org/?probe=03871e6b83) | Feb 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [0937d2a588](https://linux-hardware.org/?probe=0937d2a588) | Feb 20, 2020 |
| Dell          | Inspiron 3542               | [5e00c1766c](https://linux-hardware.org/?probe=5e00c1766c) | Feb 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [7f8aef2f6b](https://linux-hardware.org/?probe=7f8aef2f6b) | Feb 19, 2020 |
| MSI           | MS-1738                     | [0cbf139f1d](https://linux-hardware.org/?probe=0cbf139f1d) | Feb 11, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [7773f702ab](https://linux-hardware.org/?probe=7773f702ab) | Feb 10, 2020 |
| ASUSTek       | UX331UA                     | [62bdf0c233](https://linux-hardware.org/?probe=62bdf0c233) | Feb 10, 2020 |
| HP            | EliteBook 850 G5            | [fc9101307a](https://linux-hardware.org/?probe=fc9101307a) | Feb 07, 2020 |
| Dell          | Precision 7530              | [bb59dc45d2](https://linux-hardware.org/?probe=bb59dc45d2) | Feb 06, 2020 |
| MSI           | MS-1738                     | [1f7c3ccb75](https://linux-hardware.org/?probe=1f7c3ccb75) | Jan 29, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [1435e47012](https://linux-hardware.org/?probe=1435e47012) | Jan 27, 2020 |
| ASUSTek       | X555UJ                      | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | [44ad91d4da](https://linux-hardware.org/?probe=44ad91d4da) | Jan 24, 2020 |
| Dell          | Latitude 5590               | [206a367d42](https://linux-hardware.org/?probe=206a367d42) | Jan 24, 2020 |
| HP            | EliteBook 850 G5            | [bcc6422548](https://linux-hardware.org/?probe=bcc6422548) | Jan 18, 2020 |
| Samsung       | N150/N210/N220              | [91718b856a](https://linux-hardware.org/?probe=91718b856a) | Jan 16, 2020 |
| HP            | EliteBook 840 G6            | [79936056dd](https://linux-hardware.org/?probe=79936056dd) | Jan 16, 2020 |
| HP            | Laptop 15-bw0xx             | [2aff706ca4](https://linux-hardware.org/?probe=2aff706ca4) | Jan 15, 2020 |
| Lenovo        | ThinkPad T430s 2356W1L      | [42b6186198](https://linux-hardware.org/?probe=42b6186198) | Jan 13, 2020 |
| HP            | ProBook 4710s               | [d6124de12a](https://linux-hardware.org/?probe=d6124de12a) | Jan 01, 2020 |
| HP            | ProBook 4710s               | [7eb0b2437d](https://linux-hardware.org/?probe=7eb0b2437d) | Jan 01, 2020 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [14015a6cde](https://linux-hardware.org/?probe=14015a6cde) | Dec 24, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [c7b13e4ba2](https://linux-hardware.org/?probe=c7b13e4ba2) | Dec 23, 2019 |
| Dell          | Inspiron 1545               | [adaa5b6d54](https://linux-hardware.org/?probe=adaa5b6d54) | Dec 10, 2019 |
| Lenovo        | ThinkPad P51 20HH001RMD     | [7ab81dbd28](https://linux-hardware.org/?probe=7ab81dbd28) | Nov 30, 2019 |
| HP            | Pavilion dv6                | [fdc46ce1cd](https://linux-hardware.org/?probe=fdc46ce1cd) | Nov 26, 2019 |
| Lenovo        | ThinkPad S5-S540 20B3005... | [e84f3912be](https://linux-hardware.org/?probe=e84f3912be) | Nov 10, 2019 |
| eMachines     | E725                        | [599a7f6c54](https://linux-hardware.org/?probe=599a7f6c54) | Nov 03, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [9607f525a8](https://linux-hardware.org/?probe=9607f525a8) | Oct 29, 2019 |
| Apple         | MacBookPro9,2               | [99702307ab](https://linux-hardware.org/?probe=99702307ab) | Oct 21, 2019 |
| HP            | OMEN by Laptop              | [90ef6677b7](https://linux-hardware.org/?probe=90ef6677b7) | Oct 15, 2019 |
| Dell          | XPS 15 9570                 | [6cdbd762c1](https://linux-hardware.org/?probe=6cdbd762c1) | Oct 13, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [acd2d7dfad](https://linux-hardware.org/?probe=acd2d7dfad) | Oct 12, 2019 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [98855b1409](https://linux-hardware.org/?probe=98855b1409) | Oct 09, 2019 |
| Lenovo        | ThinkPad E480 20KN001NMX    | [4f055c0cf5](https://linux-hardware.org/?probe=4f055c0cf5) | Oct 08, 2019 |
| Dell          | Latitude 7480               | [b6627cc113](https://linux-hardware.org/?probe=b6627cc113) | Oct 08, 2019 |
| Lenovo        | ThinkPad P51 20HH001RMD     | [14671c29e5](https://linux-hardware.org/?probe=14671c29e5) | Oct 07, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [402c3e5e59](https://linux-hardware.org/?probe=402c3e5e59) | Oct 05, 2019 |
| Acer          | Aspire ES1-311              | [d9d6c865ef](https://linux-hardware.org/?probe=d9d6c865ef) | Sep 26, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [98ed6c18c5](https://linux-hardware.org/?probe=98ed6c18c5) | Sep 21, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [fd17c2893e](https://linux-hardware.org/?probe=fd17c2893e) | Sep 19, 2019 |
| HP            | EliteBook 850 G5            | [b355ce68ad](https://linux-hardware.org/?probe=b355ce68ad) | Sep 15, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [01545dc8fb](https://linux-hardware.org/?probe=01545dc8fb) | Sep 11, 2019 |
| HP            | EliteBook 850 G5            | [f0c27f436e](https://linux-hardware.org/?probe=f0c27f436e) | Sep 10, 2019 |
| HP            | Pavilion dv2                | [b9b30ae45c](https://linux-hardware.org/?probe=b9b30ae45c) | Sep 10, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [121e1a0f7a](https://linux-hardware.org/?probe=121e1a0f7a) | Aug 27, 2019 |
| Samsung       | 940X3G/930X3G               | [73a88e2c94](https://linux-hardware.org/?probe=73a88e2c94) | Aug 23, 2019 |
| Dell          | XPS 15 9570                 | [85fc7259b6](https://linux-hardware.org/?probe=85fc7259b6) | Aug 15, 2019 |
| Fujitsu       | LIFEBOOK U772               | [0f7c7fe35a](https://linux-hardware.org/?probe=0f7c7fe35a) | Aug 15, 2019 |
| HP            | Pavilion x2 Detachable      | [923cbd5735](https://linux-hardware.org/?probe=923cbd5735) | Aug 06, 2019 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [0aaee3cc4f](https://linux-hardware.org/?probe=0aaee3cc4f) | Aug 02, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [61e8e08336](https://linux-hardware.org/?probe=61e8e08336) | Jul 31, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [41e069ab47](https://linux-hardware.org/?probe=41e069ab47) | Jul 31, 2019 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [3e47232411](https://linux-hardware.org/?probe=3e47232411) | Jul 26, 2019 |
| Dell          | Latitude E7470              | [90e9f8dfad](https://linux-hardware.org/?probe=90e9f8dfad) | Jul 26, 2019 |
| Lenovo        | ThinkPad S430 33642NG       | [7c0cd24986](https://linux-hardware.org/?probe=7c0cd24986) | Jul 25, 2019 |
| HP            | Pavilion dv9700             | [bfebe8555b](https://linux-hardware.org/?probe=bfebe8555b) | Jul 25, 2019 |
| HP            | Compaq CQ58                 | [0c02dfd17b](https://linux-hardware.org/?probe=0c02dfd17b) | Jul 21, 2019 |
| HP            | Compaq nx7400 (RU429ET#A... | [37b1d8aa7d](https://linux-hardware.org/?probe=37b1d8aa7d) | Jul 19, 2019 |
| Lenovo        | G580 2189                   | [f3d7e4e13d](https://linux-hardware.org/?probe=f3d7e4e13d) | Jul 19, 2019 |
| Lenovo        | G580 2189                   | [a75a2e9dae](https://linux-hardware.org/?probe=a75a2e9dae) | Jul 19, 2019 |
| HP            | Pavilion dv7                | [dda054b15d](https://linux-hardware.org/?probe=dda054b15d) | Jul 15, 2019 |
| ASUSTek       | 900                         | [db34e96f60](https://linux-hardware.org/?probe=db34e96f60) | Jul 06, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [5bc72880ea](https://linux-hardware.org/?probe=5bc72880ea) | Jun 15, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [25522cad27](https://linux-hardware.org/?probe=25522cad27) | Jun 13, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [4ed2a6de0d](https://linux-hardware.org/?probe=4ed2a6de0d) | Jun 08, 2019 |
| Acer          | Nitro AN515-42              | [5d176e185c](https://linux-hardware.org/?probe=5d176e185c) | Jun 06, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [945dd2aedf](https://linux-hardware.org/?probe=945dd2aedf) | Jun 04, 2019 |
| ASUSTek       | X55SV                       | [4137ac8f54](https://linux-hardware.org/?probe=4137ac8f54) | May 31, 2019 |
| HP            | EliteBook 8440p             | [e1a6c35a36](https://linux-hardware.org/?probe=e1a6c35a36) | May 27, 2019 |
| HP            | EliteBook 8440p             | [cfcb01f30c](https://linux-hardware.org/?probe=cfcb01f30c) | May 27, 2019 |
| HP            | EliteBook 8760w             | [13780fae80](https://linux-hardware.org/?probe=13780fae80) | May 25, 2019 |
| HP            | EliteBook 8760w             | [93d7fd3de9](https://linux-hardware.org/?probe=93d7fd3de9) | May 25, 2019 |
| ASUSTek       | UX331UA                     | [5b86d530bf](https://linux-hardware.org/?probe=5b86d530bf) | May 07, 2019 |
| MSI           | GV62 8RE                    | [4c00b9e457](https://linux-hardware.org/?probe=4c00b9e457) | May 05, 2019 |
| Lenovo        | Unknown                     | [fd7bf6fb44](https://linux-hardware.org/?probe=fd7bf6fb44) | May 04, 2019 |
| Lenovo        | Unknown                     | [abcb8328f0](https://linux-hardware.org/?probe=abcb8328f0) | May 03, 2019 |
| ASUSTek       | UX331UA                     | [4e74668f09](https://linux-hardware.org/?probe=4e74668f09) | Apr 30, 2019 |
| AMI           | Cherry Trail CR             | [c2adff61c1](https://linux-hardware.org/?probe=c2adff61c1) | Apr 16, 2019 |
| ASUSTek       | X550JX                      | [961517bceb](https://linux-hardware.org/?probe=961517bceb) | Apr 08, 2019 |
| Acer          | TravelMate 5720             | [3c724ba732](https://linux-hardware.org/?probe=3c724ba732) | Apr 03, 2019 |
| Acer          | TravelMate 5720             | [19a257005b](https://linux-hardware.org/?probe=19a257005b) | Apr 02, 2019 |
| Lenovo        | ThinkPad W500 406333G       | [16f12d3bc8](https://linux-hardware.org/?probe=16f12d3bc8) | Apr 01, 2019 |
| Lenovo        | ThinkPad W500 406333G       | [28142e5518](https://linux-hardware.org/?probe=28142e5518) | Apr 01, 2019 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [e8fd67417e](https://linux-hardware.org/?probe=e8fd67417e) | Mar 29, 2019 |
| ASUSTek       | S551LN                      | [2c007f8b6c](https://linux-hardware.org/?probe=2c007f8b6c) | Mar 23, 2019 |
| Lenovo        | ThinkPad X201 3680HC3       | [6f637899c4](https://linux-hardware.org/?probe=6f637899c4) | Mar 12, 2019 |
| HP            | Laptop 14-ck0xxx            | [620383c937](https://linux-hardware.org/?probe=620383c937) | Mar 07, 2019 |
| Acer          | Aspire 7220                 | [918907fa0a](https://linux-hardware.org/?probe=918907fa0a) | Mar 06, 2019 |
| ASUSTek       | N750JK                      | [29d535d30f](https://linux-hardware.org/?probe=29d535d30f) | Feb 15, 2019 |
| ASUSTek       | N750JK                      | [0a21e6bf0f](https://linux-hardware.org/?probe=0a21e6bf0f) | Feb 13, 2019 |
| Lenovo        | ThinkPad X201 3680HC3       | [f5cf28dd23](https://linux-hardware.org/?probe=f5cf28dd23) | Jan 25, 2019 |
| ASUSTek       | N750JK                      | [e706aadaf7](https://linux-hardware.org/?probe=e706aadaf7) | Jan 16, 2019 |
| ASUSTek       | N750JK                      | [8e8a651043](https://linux-hardware.org/?probe=8e8a651043) | Jan 12, 2019 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [d87952f0b8](https://linux-hardware.org/?probe=d87952f0b8) | Dec 20, 2018 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [7f746478de](https://linux-hardware.org/?probe=7f746478de) | Dec 20, 2018 |
| Lenovo        | ThinkPad T530 24295XG       | [65d4845db2](https://linux-hardware.org/?probe=65d4845db2) | Dec 10, 2018 |
| Lenovo        | ThinkPad T570 20H9001EGE    | [904c160172](https://linux-hardware.org/?probe=904c160172) | Nov 25, 2018 |
| Lenovo        | ThinkPad T570 20H9001EGE    | [e71b0059ee](https://linux-hardware.org/?probe=e71b0059ee) | Nov 25, 2018 |
| Lenovo        | ThinkPad T530 24292UG       | [dc38e86871](https://linux-hardware.org/?probe=dc38e86871) | Jun 29, 2018 |
| Lenovo        | ThinkPad T530 24292UG       | [f521f460e8](https://linux-hardware.org/?probe=f521f460e8) | Jun 29, 2018 |
| Acer          | Aspire ES1-111M             | [782a0a4926](https://linux-hardware.org/?probe=782a0a4926) | Mar 25, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 83        | 18.44%  |
| Ubuntu 18.04       | 46        | 10.22%  |
| Ubuntu 22.04       | 16        | 3.56%   |
| Ubuntu 21.10       | 15        | 3.33%   |
| OpenMandriva 4.2   | 12        | 2.67%   |
| Fedora 34          | 12        | 2.67%   |
| Arch               | 11        | 2.44%   |
| Ubuntu 19.04       | 8         | 1.78%   |
| Pop!_OS 20.04      | 8         | 1.78%   |
| Manjaro            | 8         | 1.78%   |
| Fedora 36          | 8         | 1.78%   |
| Zorin 15           | 7         | 1.56%   |
| Pop!_OS 21.04      | 7         | 1.56%   |
| Fedora 32          | 7         | 1.56%   |
| Debian 11          | 7         | 1.56%   |
| Debian 10          | 7         | 1.56%   |
| Ubuntu 20.10       | 6         | 1.33%   |
| Pop!_OS 22.04      | 6         | 1.33%   |
| Pop!_OS 21.10      | 6         | 1.33%   |
| Linux Mint 20.3    | 6         | 1.33%   |
| Linux Mint 20.2    | 6         | 1.33%   |
| Linux Mint 20.1    | 6         | 1.33%   |
| KDE neon 20.04     | 6         | 1.33%   |
| Fedora 33          | 6         | 1.33%   |
| Xubuntu 20.04      | 5         | 1.11%   |
| Ubuntu 19.10       | 5         | 1.11%   |
| Ubuntu 18.10       | 5         | 1.11%   |
| Linux Mint 20      | 5         | 1.11%   |
| Fedora 35          | 5         | 1.11%   |
| Arch Rolling       | 5         | 1.11%   |
| Ubuntu 21.04       | 4         | 0.89%   |
| Pop!_OS 20.10      | 4         | 0.89%   |
| OpenMandriva 4.3   | 4         | 0.89%   |
| Linux Mint 19.2    | 4         | 0.89%   |
| Kubuntu 20.04      | 4         | 0.89%   |
| Fedora 31          | 4         | 0.89%   |
| Void Linux Rolling | 3         | 0.67%   |
| Ubuntu Unity 18.04 | 3         | 0.67%   |
| Linux Mint 19.3    | 3         | 0.67%   |
| Elementary 6       | 3         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 174       | 41.33%  |
| Fedora       | 35        | 8.31%   |
| Linux Mint   | 33        | 7.84%   |
| Pop!_OS      | 30        | 7.13%   |
| OpenMandriva | 18        | 4.28%   |
| Manjaro      | 18        | 4.28%   |
| Debian       | 15        | 3.56%   |
| Arch         | 15        | 3.56%   |
| Zorin        | 10        | 2.38%   |
| Kubuntu      | 9         | 2.14%   |
| Xubuntu      | 8         | 1.9%    |
| KDE neon     | 6         | 1.43%   |
| Ubuntu Unity | 5         | 1.19%   |
| Void Linux   | 4         | 0.95%   |
| ROSA         | 4         | 0.95%   |
| Elementary   | 4         | 0.95%   |
| ArcoLinux    | 4         | 0.95%   |
| Ubuntu MATE  | 3         | 0.71%   |
| Parrot       | 3         | 0.71%   |
| EndeavourOS  | 3         | 0.71%   |
| Clear Linux  | 3         | 0.71%   |
| openSUSE     | 2         | 0.48%   |
| LMDE         | 2         | 0.48%   |
| Kali         | 2         | 0.48%   |
| Garuda Linux | 2         | 0.48%   |
| TUXEDO OS    | 1         | 0.24%   |
| SteamOS      | 1         | 0.24%   |
| Lubuntu      | 1         | 0.24%   |
| LinuxFX      | 1         | 0.24%   |
| Gentoo       | 1         | 0.24%   |
| GalliumOS    | 1         | 0.24%   |
| Endless      | 1         | 0.24%   |
| BlackPanther | 1         | 0.24%   |
| antiX        | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 14        | 2.82%   |
| 5.10.14-desktop-1omv4002 | 12        | 2.41%   |
| 5.4.0-52-generic         | 6         | 1.21%   |
| 5.4.0-48-generic         | 6         | 1.21%   |
| 5.4.0-26-generic         | 6         | 1.21%   |
| 5.4.0-7634-generic       | 5         | 1.01%   |
| 5.4.0-47-generic         | 5         | 1.01%   |
| 5.16.7-desktop-1omv4003  | 5         | 1.01%   |
| 5.4.0-58-generic         | 4         | 0.8%    |
| 5.4.0-40-generic         | 4         | 0.8%    |
| 5.3.0-40-generic         | 4         | 0.8%    |
| 5.19.0-76051900-generic  | 4         | 0.8%    |
| 5.11.0-41-generic        | 4         | 0.8%    |
| 5.11.0-40-generic        | 4         | 0.8%    |
| 5.11.0-27-generic        | 4         | 0.8%    |
| 5.0.0-23-generic         | 4         | 0.8%    |
| 4.15.0-55-generic        | 4         | 0.8%    |
| 5.8.15-301.fc33.x86_64   | 3         | 0.6%    |
| 5.8.0-59-generic         | 3         | 0.6%    |
| 5.8.0-50-generic         | 3         | 0.6%    |
| 5.8.0-45-generic         | 3         | 0.6%    |
| 5.8.0-29-generic         | 3         | 0.6%    |
| 5.4.0-96-generic         | 3         | 0.6%    |
| 5.4.0-91-generic         | 3         | 0.6%    |
| 5.4.0-81-generic         | 3         | 0.6%    |
| 5.4.0-77-generic         | 3         | 0.6%    |
| 5.4.0-62-generic         | 3         | 0.6%    |
| 5.4.0-54-generic         | 3         | 0.6%    |
| 5.4.0-29-generic         | 3         | 0.6%    |
| 5.3.0-28-generic         | 3         | 0.6%    |
| 5.15.0-46-generic        | 3         | 0.6%    |
| 5.15.0-43-generic        | 3         | 0.6%    |
| 5.15.0-40-generic        | 3         | 0.6%    |
| 5.15.0-27-generic        | 3         | 0.6%    |
| 5.13.12-200.fc34.x86_64  | 3         | 0.6%    |
| 5.11.0-7620-generic      | 3         | 0.6%    |
| 5.11.0-46-generic        | 3         | 0.6%    |
| 5.11.0-43-generic        | 3         | 0.6%    |
| 5.11.0-36-generic        | 3         | 0.6%    |
| 5.0.0-37-generic         | 3         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 91        | 19.57%  |
| 5.11.0  | 34        | 7.31%   |
| 4.15.0  | 34        | 7.31%   |
| 5.8.0   | 28        | 6.02%   |
| 5.13.0  | 23        | 4.95%   |
| 5.15.0  | 20        | 4.3%    |
| 5.3.0   | 18        | 3.87%   |
| 5.0.0   | 17        | 3.66%   |
| 4.18.0  | 13        | 2.8%    |
| 5.10.14 | 12        | 2.58%   |
| 5.10.0  | 8         | 1.72%   |
| 4.19.0  | 7         | 1.51%   |
| 5.19.0  | 5         | 1.08%   |
| 5.16.7  | 5         | 1.08%   |
| 5.7.15  | 4         | 0.86%   |
| 5.9.0   | 3         | 0.65%   |
| 5.8.15  | 3         | 0.65%   |
| 5.4.18  | 3         | 0.65%   |
| 5.19.13 | 3         | 0.65%   |
| 5.16.0  | 3         | 0.65%   |
| 5.14.0  | 3         | 0.65%   |
| 5.13.12 | 3         | 0.65%   |
| 5.9.16  | 2         | 0.43%   |
| 5.9.14  | 2         | 0.43%   |
| 5.8.16  | 2         | 0.43%   |
| 5.8.11  | 2         | 0.43%   |
| 5.6.7   | 2         | 0.43%   |
| 5.4.8   | 2         | 0.43%   |
| 5.18.11 | 2         | 0.43%   |
| 5.17.5  | 2         | 0.43%   |
| 5.16.18 | 2         | 0.43%   |
| 5.16.12 | 2         | 0.43%   |
| 5.16.11 | 2         | 0.43%   |
| 5.15.6  | 2         | 0.43%   |
| 5.15.46 | 2         | 0.43%   |
| 5.15.16 | 2         | 0.43%   |
| 5.15.15 | 2         | 0.43%   |
| 5.15.12 | 2         | 0.43%   |
| 5.14.7  | 2         | 0.43%   |
| 5.12.0  | 2         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 99        | 21.52%  |
| 5.8     | 39        | 8.48%   |
| 5.15    | 39        | 8.48%   |
| 5.11    | 38        | 8.26%   |
| 4.15    | 34        | 7.39%   |
| 5.13    | 28        | 6.09%   |
| 5.10    | 25        | 5.43%   |
| 5.3     | 18        | 3.91%   |
| 5.16    | 18        | 3.91%   |
| 5.0     | 18        | 3.91%   |
| 5.19    | 16        | 3.48%   |
| 4.18    | 14        | 3.04%   |
| 5.14    | 12        | 2.61%   |
| 5.9     | 9         | 1.96%   |
| 4.19    | 8         | 1.74%   |
| 5.18    | 7         | 1.52%   |
| 5.7     | 6         | 1.3%    |
| 5.6     | 6         | 1.3%    |
| 5.17    | 6         | 1.3%    |
| 5.12    | 5         | 1.09%   |
| 5.1     | 3         | 0.65%   |
| 4.9     | 2         | 0.43%   |
| 4.4     | 2         | 0.43%   |
| 4.14    | 2         | 0.43%   |
| 6.0     | 1         | 0.22%   |
| 5.2     | 1         | 0.22%   |
| 4.16    | 1         | 0.22%   |
| 4.13    | 1         | 0.22%   |
| 4.10    | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 387       | 95.56%  |
| i686   | 18        | 4.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 216       | 50.7%   |
| Unknown         | 67        | 15.73%  |
| KDE5            | 54        | 12.68%  |
| XFCE            | 25        | 5.87%   |
| X-Cinnamon      | 21        | 4.93%   |
| KDE             | 12        | 2.82%   |
| MATE            | 9         | 2.11%   |
| Unity           | 5         | 1.17%   |
| i3              | 4         | 0.94%   |
| Pantheon        | 3         | 0.7%    |
| LXQt            | 2         | 0.47%   |
| Cinnamon        | 2         | 0.47%   |
| sway            | 1         | 0.23%   |
| qtile-default   | 1         | 0.23%   |
| LeftWM          | 1         | 0.23%   |
| icewm           | 1         | 0.23%   |
| GNOME Flashback | 1         | 0.23%   |
| awesome         | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 316       | 74.7%   |
| Wayland | 70        | 16.55%  |
| Unknown | 32        | 7.57%   |
| Tty     | 5         | 1.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 246       | 58.99%  |
| GDM     | 62        | 14.87%  |
| SDDM    | 40        | 9.59%   |
| GDM3    | 40        | 9.59%   |
| LightDM | 15        | 3.6%    |
| TDM     | 12        | 2.88%   |
| Ly      | 1         | 0.24%   |
| GREETD  | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 140       | 33.25%  |
| da_DK   | 126       | 29.93%  |
| Unknown | 61        | 14.49%  |
| en_DK   | 51        | 12.11%  |
| en_GB   | 21        | 4.99%   |
| de_DE   | 8         | 1.9%    |
| C       | 5         | 1.19%   |
| pl_PL   | 2         | 0.48%   |
| en_AG   | 2         | 0.48%   |
| pt_BR   | 1         | 0.24%   |
| it_IT   | 1         | 0.24%   |
| is_IS   | 1         | 0.24%   |
| fr_FR   | 1         | 0.24%   |
| en_CA   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 207       | 50.24%  |
| EFI  | 205       | 49.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 325       | 78.69%  |
| Btrfs   | 41        | 9.93%   |
| Overlay | 20        | 4.84%   |
| Unknown | 20        | 4.84%   |
| Zfs     | 4         | 0.97%   |
| Ext2    | 3         | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 269       | 65.45%  |
| GPT     | 112       | 27.25%  |
| MBR     | 30        | 7.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 365       | 89.02%  |
| Yes       | 45        | 10.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 324       | 79.02%  |
| Yes       | 86        | 20.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 145       | 35.89%  |
| Hewlett-Packard     | 73        | 18.07%  |
| Dell                | 40        | 9.9%    |
| ASUSTek Computer    | 37        | 9.16%   |
| Acer                | 32        | 7.92%   |
| Apple               | 13        | 3.22%   |
| Toshiba             | 10        | 2.48%   |
| Notebook            | 8         | 1.98%   |
| MSI                 | 6         | 1.49%   |
| HUAWEI              | 4         | 0.99%   |
| Samsung Electronics | 3         | 0.74%   |
| Google              | 3         | 0.74%   |
| TUXEDO              | 2         | 0.5%    |
| Razer               | 2         | 0.5%    |
| Quanta              | 2         | 0.5%    |
| Packard Bell        | 2         | 0.5%    |
| Medion              | 2         | 0.5%    |
| Fujitsu             | 2         | 0.5%    |
| eMachines           | 2         | 0.5%    |
| AMI                 | 2         | 0.5%    |
| Unknown             | 2         | 0.5%    |
| Valve               | 1         | 0.25%   |
| Timi                | 1         | 0.25%   |
| SLIMBOOK            | 1         | 0.25%   |
| Purism              | 1         | 0.25%   |
| LG Electronics      | 1         | 0.25%   |
| LAMINA              | 1         | 0.25%   |
| IBM                 | 1         | 0.25%   |
| GPD                 | 1         | 0.25%   |
| Fujitsu Siemens     | 1         | 0.25%   |
| DukaPC              | 1         | 0.25%   |
| Dixonsxp            | 1         | 0.25%   |
| Alienware           | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 8         | 1.98%   |
| HP Pavilion dv7                       | 4         | 0.99%   |
| Dell XPS 15 9570                      | 4         | 0.99%   |
| HP EliteBook 820 G3                   | 3         | 0.74%   |
| Toshiba Satellite L40                 | 2         | 0.5%    |
| Quanta MW1/HW1                        | 2         | 0.5%    |
| Notebook W54_55SU1,SUW                | 2         | 0.5%    |
| Lenovo ThinkPad T530 24295L4          | 2         | 0.5%    |
| Lenovo IdeaPad S130-14IGM 81J2        | 2         | 0.5%    |
| Lenovo IdeaPad 310-15IKB 80TV         | 2         | 0.5%    |
| Lenovo E31-80 80MX                    | 2         | 0.5%    |
| HP ProBook 650 G1                     | 2         | 0.5%    |
| HP Pavilion Notebook                  | 2         | 0.5%    |
| HP Pavilion g7                        | 2         | 0.5%    |
| HP Laptop 15-bw0xx                    | 2         | 0.5%    |
| HP EliteBook 845 G7 Notebook PC       | 2         | 0.5%    |
| HP EliteBook 840 G1                   | 2         | 0.5%    |
| HP Compaq Presario CQ71               | 2         | 0.5%    |
| eMachines E725                        | 2         | 0.5%    |
| Dell XPS 15 9560                      | 2         | 0.5%    |
| Dell XPS 13 9370                      | 2         | 0.5%    |
| Dell Latitude E7440                   | 2         | 0.5%    |
| Dell Latitude 7480                    | 2         | 0.5%    |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK | 2         | 0.5%    |
| Apple MacBookPro9,2                   | 2         | 0.5%    |
| Apple MacBookPro7,1                   | 2         | 0.5%    |
| Apple MacBookPro5,5                   | 2         | 0.5%    |
| Apple MacBookPro14,1                  | 2         | 0.5%    |
| Valve Jupiter                         | 1         | 0.25%   |
| TUXEDO Pulse 15 Gen1                  | 1         | 0.25%   |
| Toshiba Satellite U300                | 1         | 0.25%   |
| Toshiba Satellite P850                | 1         | 0.25%   |
| Toshiba Satellite P55W-C              | 1         | 0.25%   |
| Toshiba Satellite P50-A-11J           | 1         | 0.25%   |
| Toshiba Satellite L755D               | 1         | 0.25%   |
| Toshiba Satellite L350D               | 1         | 0.25%   |
| Toshiba Satellite C670D-10C           | 1         | 0.25%   |
| Toshiba Satellite C660                | 1         | 0.25%   |
| Timi TM1703                           | 1         | 0.25%   |
| SLIMBOOK PROX14-10                    | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 102       | 25.25%  |
| Acer Aspire           | 22        | 5.45%   |
| HP Pavilion           | 18        | 4.46%   |
| HP EliteBook          | 18        | 4.46%   |
| Dell Latitude         | 18        | 4.46%   |
| Lenovo IdeaPad        | 14        | 3.47%   |
| Dell XPS              | 12        | 2.97%   |
| Toshiba Satellite     | 10        | 2.48%   |
| HP ProBook            | 10        | 2.48%   |
| ASUS ROG              | 8         | 1.98%   |
| Unknown               | 8         | 1.98%   |
| HP Laptop             | 7         | 1.73%   |
| HP Compaq             | 6         | 1.49%   |
| Dell Inspiron         | 5         | 1.24%   |
| ASUS ZenBook          | 5         | 1.24%   |
| Lenovo Yoga           | 3         | 0.74%   |
| Lenovo ThinkBook      | 3         | 0.74%   |
| HP ZBook              | 3         | 0.74%   |
| Dell Precision        | 3         | 0.74%   |
| ASUS VivoBook         | 3         | 0.74%   |
| Acer Swift            | 3         | 0.74%   |
| Razer Blade           | 2         | 0.5%    |
| Quanta MW1            | 2         | 0.5%    |
| Packard Bell EasyNote | 2         | 0.5%    |
| Notebook W54          | 2         | 0.5%    |
| Lenovo Legion         | 2         | 0.5%    |
| Lenovo E31-80         | 2         | 0.5%    |
| Lenovo 3000           | 2         | 0.5%    |
| HP OMEN               | 2         | 0.5%    |
| Fujitsu LIFEBOOK      | 2         | 0.5%    |
| eMachines E725        | 2         | 0.5%    |
| ASUS TUF              | 2         | 0.5%    |
| ASUS ASUS             | 2         | 0.5%    |
| Apple MacBookPro9     | 2         | 0.5%    |
| Apple MacBookPro7     | 2         | 0.5%    |
| Apple MacBookPro5     | 2         | 0.5%    |
| Apple MacBookPro14    | 2         | 0.5%    |
| Apple MacBookPro11    | 2         | 0.5%    |
| Acer TravelMate       | 2         | 0.5%    |
| Acer Nitro            | 2         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 40        | 9.9%    |
| 2019    | 37        | 9.16%   |
| 2013    | 32        | 7.92%   |
| 2017    | 31        | 7.67%   |
| 2016    | 30        | 7.43%   |
| 2012    | 30        | 7.43%   |
| 2020    | 29        | 7.18%   |
| 2021    | 27        | 6.68%   |
| 2011    | 27        | 6.68%   |
| 2015    | 26        | 6.44%   |
| 2009    | 20        | 4.95%   |
| 2014    | 19        | 4.7%    |
| 2010    | 17        | 4.21%   |
| 2008    | 13        | 3.22%   |
| 2007    | 13        | 3.22%   |
| 2022    | 7         | 1.73%   |
| 2006    | 4         | 0.99%   |
| 2003    | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 404       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 364       | 89.22%  |
| Enabled  | 44        | 10.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 400       | 99.01%  |
| Yes  | 4         | 0.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 122       | 29.47%  |
| 8.01-16.0   | 83        | 20.05%  |
| 16.01-24.0  | 72        | 17.39%  |
| 3.01-4.0    | 65        | 15.7%   |
| 32.01-64.0  | 31        | 7.49%   |
| 1.01-2.0    | 15        | 3.62%   |
| 2.01-3.0    | 9         | 2.17%   |
| 24.01-32.0  | 8         | 1.93%   |
| 64.01-256.0 | 7         | 1.69%   |
| 0.51-1.0    | 1         | 0.24%   |
| 0.01-0.5    | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 148       | 32.74%  |
| 2.01-3.0   | 122       | 26.99%  |
| 4.01-8.0   | 72        | 15.93%  |
| 3.01-4.0   | 67        | 14.82%  |
| 0.51-1.0   | 23        | 5.09%   |
| 8.01-16.0  | 13        | 2.88%   |
| 0.01-0.5   | 4         | 0.88%   |
| 16.01-24.0 | 2         | 0.44%   |
| 32.01-64.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 321       | 78.1%   |
| 2      | 79        | 19.22%  |
| 3      | 8         | 1.95%   |
| 0      | 3         | 0.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 271       | 66.26%  |
| Yes       | 138       | 33.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 346       | 85.01%  |
| No        | 61        | 14.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 399       | 98.76%  |
| No        | 5         | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 335       | 80.92%  |
| No        | 79        | 19.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Denmark | 404       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Copenhagen            | 95        | 22.2%   |
| Odense                | 32        | 7.48%   |
| Frederiksberg         | 29        | 6.78%   |
| Bronshoj              | 15        | 3.5%    |
| Aarhus                | 15        | 3.5%    |
| Silkeborg             | 11        | 2.57%   |
| Glostrup Municipality | 8         | 1.87%   |
| Aalborg               | 8         | 1.87%   |
| Holstebro             | 7         | 1.64%   |
| Valby                 | 6         | 1.4%    |
| Roskilde              | 6         | 1.4%    |
| Norresundby           | 6         | 1.4%    |
| Kongens Lyngby        | 6         | 1.4%    |
| Gentofte Municipality | 6         | 1.4%    |
| Aabenraa              | 6         | 1.4%    |
| Slagelse              | 5         | 1.17%   |
| Nyborg                | 5         | 1.17%   |
| Naestved              | 5         | 1.17%   |
| Hvidovre              | 5         | 1.17%   |
| Horsens               | 5         | 1.17%   |
| Vanlose               | 4         | 0.93%   |
| Thisted               | 4         | 0.93%   |
| Sindal                | 4         | 0.93%   |
| Risskov               | 4         | 0.93%   |
| Kastrup               | 4         | 0.93%   |
| Herlev                | 4         | 0.93%   |
| Esbjerg               | 4         | 0.93%   |
| Elsinore              | 4         | 0.93%   |
| Vaerlose              | 3         | 0.7%    |
| Taastrup              | 3         | 0.7%    |
| Skive                 | 3         | 0.7%    |
| Skanderborg           | 3         | 0.7%    |
| Rønne                | 3         | 0.7%    |
| Holte                 | 3         | 0.7%    |
| Hojbjerg              | 3         | 0.7%    |
| Hadsund               | 3         | 0.7%    |
| Viborg                | 2         | 0.47%   |
| Vejle                 | 2         | 0.47%   |
| Svendborg             | 2         | 0.47%   |
| Køge                 | 2         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 121       | 166    | 25.8%   |
| WDC                 | 52        | 67     | 11.09%  |
| Kingston            | 36        | 48     | 7.68%   |
| Seagate             | 35        | 41     | 7.46%   |
| Toshiba             | 34        | 48     | 7.25%   |
| SK hynix            | 32        | 46     | 6.82%   |
| Unknown             | 20        | 23     | 4.26%   |
| Hitachi             | 20        | 24     | 4.26%   |
| SanDisk             | 19        | 26     | 4.05%   |
| Intel               | 17        | 20     | 3.62%   |
| Micron Technology   | 13        | 16     | 2.77%   |
| LITEON              | 10        | 16     | 2.13%   |
| HGST                | 10        | 15     | 2.13%   |
| PNY                 | 8         | 8      | 1.71%   |
| Apple               | 6         | 8      | 1.28%   |
| LITEONIT            | 4         | 5      | 0.85%   |
| Intenso             | 4         | 6      | 0.85%   |
| OCZ                 | 3         | 3      | 0.64%   |
| Lenovo              | 3         | 4      | 0.64%   |
| A-DATA Technology   | 3         | 3      | 0.64%   |
| KIOXIA              | 2         | 3      | 0.43%   |
| Fujitsu             | 2         | 3      | 0.43%   |
| Crucial             | 2         | 2      | 0.43%   |
| China               | 2         | 2      | 0.43%   |
| XPG                 | 1         | 1      | 0.21%   |
| USB3.0              | 1         | 1      | 0.21%   |
| Transcend           | 1         | 1      | 0.21%   |
| Solid State Storage | 1         | 1      | 0.21%   |
| Silicon Motion      | 1         | 1      | 0.21%   |
| Phison              | 1         | 2      | 0.21%   |
| KingFast            | 1         | 1      | 0.21%   |
| Kingchuxing         | 1         | 1      | 0.21%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |
| ASUS-PHISON         | 1         | 1      | 0.21%   |
| Apricorn            | 1         | 2      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 10        | 2.03%   |
| Samsung SSD 850 EVO 500GB              | 9         | 1.83%   |
| Samsung SSD 850 EVO 250GB              | 8         | 1.62%   |
| Toshiba NVMe SSD Drive 512GB           | 6         | 1.22%   |
| Samsung NVMe SSD Drive 512GB           | 6         | 1.22%   |
| Kingston SA400S37480G 480GB SSD        | 6         | 1.22%   |
| Kingston SA400S37240G 240GB SSD        | 6         | 1.22%   |
| SK hynix NVMe SSD Drive 512GB          | 5         | 1.01%   |
| Samsung NVMe SSD Drive 1024GB          | 5         | 1.01%   |
| Unknown MMC Card  32GB                 | 4         | 0.81%   |
| Toshiba NVMe SSD Drive 256GB           | 4         | 0.81%   |
| Samsung SSD 860 EVO 500GB              | 4         | 0.81%   |
| Samsung MZVLB512HAJQ-000L7 512GB       | 4         | 0.81%   |
| PNY CS900 120GB SSD                    | 4         | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 3         | 0.61%   |
| WDC WD2500BEVT-60ZCT1 250GB            | 3         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB               | 3         | 0.61%   |
| Unknown MMC Card  64GB                 | 3         | 0.61%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 3         | 0.61%   |
| SK hynix NVMe SSD Drive 256GB          | 3         | 0.61%   |
| SK hynix HFS256G39TND-N210A 256GB SSD  | 3         | 0.61%   |
| Seagate ST2000LM015-2E8174 2TB         | 3         | 0.61%   |
| Samsung SSD 970 EVO Plus 1TB           | 3         | 0.61%   |
| Samsung SSD 860 EVO 1TB                | 3         | 0.61%   |
| Micron NVMe SSD Drive 512GB            | 3         | 0.61%   |
| Kingston SV300S37A120G 120GB SSD       | 3         | 0.61%   |
| Kingston SA400S37120G 120GB SSD        | 3         | 0.61%   |
| Intel NVMe SSD Drive 512GB             | 3         | 0.61%   |
| HGST HTS545050A7E380 500GB             | 3         | 0.61%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 2         | 0.41%   |
| WDC WDS100T2G0A-00JH30 1TB SSD         | 2         | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.41%   |
| WDC WD5000BEVT-22ZAT0 500GB            | 2         | 0.41%   |
| WDC WD2500BEVS-60UST0 250GB            | 2         | 0.41%   |
| WDC WD10SPCX-24HWST1 1TB               | 2         | 0.41%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 2         | 0.41%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB   | 2         | 0.41%   |
| Toshiba TR150 240GB SSD                | 2         | 0.41%   |
| Toshiba NVMe SSD Drive 2TB             | 2         | 0.41%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 34        | 40     | 30.09%  |
| WDC      | 31        | 41     | 27.43%  |
| Hitachi  | 20        | 24     | 17.7%   |
| Toshiba  | 13        | 14     | 11.5%   |
| HGST     | 10        | 15     | 8.85%   |
| Fujitsu  | 2         | 3      | 1.77%   |
| USB3.0   | 1         | 1      | 0.88%   |
| Apricorn | 1         | 2      | 0.88%   |
| Apple    | 1         | 2      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 67        | 87     | 36.41%  |
| Kingston            | 32        | 43     | 17.39%  |
| SanDisk             | 11        | 14     | 5.98%   |
| WDC                 | 10        | 13     | 5.43%   |
| LITEON              | 9         | 15     | 4.89%   |
| PNY                 | 8         | 8      | 4.35%   |
| Toshiba             | 7         | 9      | 3.8%    |
| SK hynix            | 7         | 9      | 3.8%    |
| Micron Technology   | 5         | 5      | 2.72%   |
| LITEONIT            | 4         | 5      | 2.17%   |
| Intenso             | 4         | 6      | 2.17%   |
| Apple               | 4         | 4      | 2.17%   |
| OCZ                 | 3         | 3      | 1.63%   |
| Intel               | 3         | 4      | 1.63%   |
| A-DATA Technology   | 3         | 3      | 1.63%   |
| Crucial             | 2         | 2      | 1.09%   |
| China               | 2         | 2      | 1.09%   |
| KingFast            | 1         | 1      | 0.54%   |
| Kingchuxing         | 1         | 1      | 0.54%   |
| ASUS-PHISON         | 1         | 1      | 0.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 175       | 235    | 38.89%  |
| NVMe    | 145       | 212    | 32.22%  |
| HDD     | 106       | 142    | 23.56%  |
| MMC     | 22        | 25     | 4.89%   |
| Unknown | 2         | 2      | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 262       | 368    | 59.68%  |
| NVMe | 145       | 212    | 33.03%  |
| MMC  | 22        | 25     | 5.01%   |
| SAS  | 10        | 11     | 2.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 206       | 288    | 72.79%  |
| 0.51-1.0   | 61        | 69     | 21.55%  |
| 1.01-2.0   | 13        | 17     | 4.59%   |
| 4.01-10.0  | 2         | 2      | 0.71%   |
| 3.01-4.0   | 1         | 1      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 134       | 31.09%  |
| 251-500        | 97        | 22.51%  |
| 501-1000       | 61        | 14.15%  |
| 1-20           | 33        | 7.66%   |
| 51-100         | 32        | 7.42%   |
| 1001-2000      | 23        | 5.34%   |
| Unknown        | 20        | 4.64%   |
| 21-50          | 16        | 3.71%   |
| More than 3000 | 8         | 1.86%   |
| 2001-3000      | 7         | 1.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 186       | 41.8%   |
| 21-50          | 73        | 16.4%   |
| 101-250        | 54        | 12.13%  |
| 51-100         | 53        | 11.91%  |
| 251-500        | 34        | 7.64%   |
| Unknown        | 20        | 4.49%   |
| 501-1000       | 17        | 3.82%   |
| 1001-2000      | 5         | 1.12%   |
| 2001-3000      | 2         | 0.45%   |
| More than 3000 | 1         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 15.38%  |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 7.69%   |
| WDC WD5000BPVT-80HXZT3 500GB          | 1         | 1      | 7.69%   |
| WDC WD5000BEVT-35ZAT0 500GB           | 1         | 1      | 7.69%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 7.69%   |
| Toshiba KSG60ZSE256G SATA 256GB SSD   | 1         | 1      | 7.69%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 7.69%   |
| Micron Technology 1100 SATA 512GB SSD | 1         | 1      | 7.69%   |
| Kingston SA400S37480G 480GB SSD       | 1         | 1      | 7.69%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 7.69%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 7.69%   |
| Apple HDD HTS547550A9E384 500GB       | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 3      | 23.08%  |
| Seagate           | 3         | 3      | 23.08%  |
| Toshiba           | 2         | 2      | 15.38%  |
| HGST              | 2         | 2      | 15.38%  |
| Micron Technology | 1         | 1      | 7.69%   |
| Kingston          | 1         | 1      | 7.69%   |
| Apple             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 33.33%  |
| WDC     | 2         | 2      | 22.22%  |
| HGST    | 2         | 2      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Apple   | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 69.23%  |
| SSD  | 4         | 4      | 30.77%  |

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
| Detected | 281       | 438    | 66.43%  |
| Works    | 129       | 165    | 30.5%   |
| Malfunc  | 13        | 13     | 3.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 261       | 57.87%  |
| Samsung Electronics              | 61        | 13.53%  |
| AMD                              | 39        | 8.65%   |
| SK hynix                         | 24        | 5.32%   |
| SanDisk                          | 17        | 3.77%   |
| Toshiba America Info Systems     | 15        | 3.33%   |
| Micron Technology                | 8         | 1.77%   |
| Nvidia                           | 7         | 1.55%   |
| Kingston Technology Company      | 4         | 0.89%   |
| Silicon Motion                   | 3         | 0.67%   |
| Lenovo                           | 3         | 0.67%   |
| Solid State Storage Technology   | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Phison Electronics               | 1         | 0.22%   |
| Lite-On Technology               | 1         | 0.22%   |
| KIOXIA                           | 1         | 0.22%   |
| JMicron Technology               | 1         | 0.22%   |
| ASMedia Technology               | 1         | 0.22%   |
| Apple                            | 1         | 0.22%   |
| ADATA Technology                 | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 37        | 7.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 36        | 7.39%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 31        | 6.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 28        | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 25        | 5.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 23        | 4.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 19        | 3.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 18        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 3.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 14        | 2.87%   |
| SK hynix Gold P31 SSD                                                            | 11        | 2.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 11        | 2.26%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 10        | 2.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 10        | 2.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 2.05%   |
| Micron Non-Volatile memory controller                                            | 8         | 1.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 7         | 1.44%   |
| SK hynix Non-Volatile memory controller                                          | 7         | 1.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.44%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 5         | 1.03%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.03%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 0.82%   |
| Intel SSD 660P Series                                                            | 4         | 0.82%   |
| Intel Non-Volatile memory controller                                             | 4         | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 4         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 0.82%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.62%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 0.62%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.62%   |
| Lenovo Non-Volatile memory controller                                            | 3         | 0.62%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 0.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.62%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 266       | 57.08%  |
| NVMe | 146       | 31.33%  |
| IDE  | 33        | 7.08%   |
| RAID | 21        | 4.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 332       | 82.18%  |
| AMD    | 72        | 17.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 12        | 2.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 9         | 2.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 7         | 1.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 7         | 1.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 6         | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 6         | 1.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 6         | 1.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 5         | 1.24%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 5         | 1.24%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 1.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 1.24%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 5         | 1.24%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 4         | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 4         | 0.99%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 4         | 0.99%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 4         | 0.99%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 4         | 0.99%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 4         | 0.99%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 0.99%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 4         | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 4         | 0.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 0.99%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 0.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 0.99%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 4         | 0.99%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 4         | 0.99%   |
| AMD Ryzen 9 5900HS with Radeon Graphics     | 4         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 0.74%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 3         | 0.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 3         | 0.74%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 0.74%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 3         | 0.74%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 3         | 0.74%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 3         | 0.74%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 3         | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 0.74%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 3         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 117       | 28.96%  |
| Intel Core i5                  | 116       | 28.71%  |
| Intel Core 2 Duo               | 21        | 5.2%    |
| Intel Core i3                  | 17        | 4.21%   |
| Intel Celeron                  | 15        | 3.71%   |
| AMD Ryzen 7                    | 14        | 3.47%   |
| Other                          | 13        | 3.22%   |
| AMD Ryzen 5                    | 11        | 2.72%   |
| AMD Ryzen 7 PRO                | 9         | 2.23%   |
| Intel Pentium Dual-Core        | 7         | 1.73%   |
| AMD Ryzen 9                    | 7         | 1.73%   |
| Intel Atom                     | 6         | 1.49%   |
| Intel Pentium                  | 5         | 1.24%   |
| Intel Core i9                  | 5         | 1.24%   |
| AMD A6                         | 4         | 0.99%   |
| Intel Pentium M                | 3         | 0.74%   |
| AMD A8                         | 3         | 0.74%   |
| Intel Pentium Silver           | 2         | 0.5%    |
| Intel Pentium Dual             | 2         | 0.5%    |
| Intel Core 2                   | 2         | 0.5%    |
| AMD Turion 64 X2 Mobile        | 2         | 0.5%    |
| AMD Ryzen 5 PRO                | 2         | 0.5%    |
| AMD E                          | 2         | 0.5%    |
| AMD Athlon                     | 2         | 0.5%    |
| AMD A4                         | 2         | 0.5%    |
| AMD A10                        | 2         | 0.5%    |
| Intel Genuine                  | 1         | 0.25%   |
| Intel Core m7                  | 1         | 0.25%   |
| Intel Celeron M                | 1         | 0.25%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.25%   |
| AMD Ryzen 3                    | 1         | 0.25%   |
| AMD FX                         | 1         | 0.25%   |
| AMD E2                         | 1         | 0.25%   |
| AMD E1                         | 1         | 0.25%   |
| AMD Athlon X2                  | 1         | 0.25%   |
| AMD Athlon Neo                 | 1         | 0.25%   |
| AMD Athlon II Neo              | 1         | 0.25%   |
| AMD Athlon II Dual-Core        | 1         | 0.25%   |
| AMD Athlon II                  | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 203       | 50.25%  |
| 4      | 128       | 31.68%  |
| 8      | 34        | 8.42%   |
| 6      | 24        | 5.94%   |
| 1      | 13        | 3.22%   |
| 14     | 1         | 0.25%   |
| 12     | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 404       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 308       | 76.24%  |
| 1      | 96        | 23.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 389       | 95.81%  |
| Unknown        | 13        | 3.2%    |
| 32-bit         | 4         | 0.99%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 21.15%  |
| 0x40651    | 24        | 5.77%   |
| 0x306a9    | 23        | 5.53%   |
| 0x206a7    | 22        | 5.29%   |
| 0x406e3    | 20        | 4.81%   |
| 0x1067a    | 18        | 4.33%   |
| 0x806ea    | 15        | 3.61%   |
| 0x806e9    | 15        | 3.61%   |
| 0x306c3    | 15        | 3.61%   |
| 0x806ec    | 14        | 3.37%   |
| 0x906ea    | 13        | 3.13%   |
| 0x20655    | 11        | 2.64%   |
| 0x906e9    | 8         | 1.92%   |
| 0x0a50000c | 8         | 1.92%   |
| 0x906ed    | 6         | 1.44%   |
| 0x806eb    | 6         | 1.44%   |
| 0x20652    | 6         | 1.44%   |
| 0x08600104 | 6         | 1.44%   |
| 0x08600106 | 5         | 1.2%    |
| 0x08108102 | 5         | 1.2%    |
| 0x806c1    | 4         | 0.96%   |
| 0x706e5    | 4         | 0.96%   |
| 0x6fd      | 4         | 0.96%   |
| 0x506e3    | 4         | 0.96%   |
| 0x406c3    | 4         | 0.96%   |
| 0x306d4    | 4         | 0.96%   |
| 0x30678    | 4         | 0.96%   |
| 0x10676    | 4         | 0.96%   |
| 0x6d8      | 3         | 0.72%   |
| 0x0810100b | 3         | 0.72%   |
| 0x07030105 | 3         | 0.72%   |
| 0xa0652    | 2         | 0.48%   |
| 0x706a1    | 2         | 0.48%   |
| 0x6fb      | 2         | 0.48%   |
| 0x6fa      | 2         | 0.48%   |
| 0x6f6      | 2         | 0.48%   |
| 0x506c9    | 2         | 0.48%   |
| 0x406c4    | 2         | 0.48%   |
| 0x40661    | 2         | 0.48%   |
| 0x10661    | 2         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 95        | 23.51%  |
| Haswell          | 44        | 10.89%  |
| Skylake          | 32        | 7.92%   |
| SandyBridge      | 30        | 7.43%   |
| IvyBridge        | 27        | 6.68%   |
| Penryn           | 25        | 6.19%   |
| Westmere         | 17        | 4.21%   |
| Zen 2            | 13        | 3.22%   |
| Zen 3            | 12        | 2.97%   |
| Silvermont       | 12        | 2.97%   |
| Core             | 12        | 2.97%   |
| Zen+             | 10        | 2.48%   |
| Unknown          | 10        | 2.48%   |
| TigerLake        | 7         | 1.73%   |
| Broadwell        | 7         | 1.73%   |
| Excavator        | 6         | 1.49%   |
| IceLake          | 5         | 1.24%   |
| CometLake        | 5         | 1.24%   |
| P6               | 4         | 0.99%   |
| Bobcat           | 4         | 0.99%   |
| Zen              | 3         | 0.74%   |
| Puma             | 3         | 0.74%   |
| K8 Hammer        | 3         | 0.74%   |
| K8 & K10 hybrid  | 3         | 0.74%   |
| K10              | 3         | 0.74%   |
| Goldmont plus    | 3         | 0.74%   |
| Steamroller      | 2         | 0.5%    |
| Goldmont         | 2         | 0.5%    |
| Bonnell          | 2         | 0.5%    |
| Piledriver       | 1         | 0.25%   |
| K10 Llano        | 1         | 0.25%   |
| Alderlake Hybrid | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 296       | 57.48%  |
| Nvidia                           | 125       | 24.27%  |
| AMD                              | 93        | 18.06%  |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 5.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 26        | 4.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 4.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 4.7%    |
| Intel UHD Graphics 620                                                                   | 23        | 4.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 20        | 3.76%   |
| Intel HD Graphics 620                                                                    | 15        | 2.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 2.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 2.63%   |
| AMD Renoir                                                                               | 13        | 2.44%   |
| AMD Cezanne                                                                              | 12        | 2.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.88%   |
| Intel HD Graphics 630                                                                    | 8         | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 1.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.32%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.13%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.75%   |
| Intel HD Graphics 530                                                                    | 4         | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.75%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.75%   |
| AMD Lucienne                                                                             | 4         | 0.75%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.56%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.56%   |
| Nvidia GF108M [NVS 5400M]                                                                | 3         | 0.56%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 3         | 0.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.56%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 0.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 195       | 48.27%  |
| Intel + Nvidia | 85        | 21.04%  |
| 1 x AMD        | 58        | 14.36%  |
| 1 x Nvidia     | 29        | 7.18%   |
| Intel + AMD    | 15        | 3.71%   |
| 2 x AMD        | 10        | 2.48%   |
| AMD + Nvidia   | 10        | 2.48%   |
| Other          | 1         | 0.25%   |
| 1 x SiS        | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 339       | 82.89%  |
| Proprietary | 60        | 14.67%  |
| Unknown     | 10        | 2.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 245       | 59.76%  |
| 0.01-0.5   | 57        | 13.9%   |
| 1.01-2.0   | 54        | 13.17%  |
| 3.01-4.0   | 23        | 5.61%   |
| 0.51-1.0   | 21        | 5.12%   |
| 5.01-6.0   | 7         | 1.71%   |
| 7.01-8.0   | 2         | 0.49%   |
| 2.01-3.0   | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 102       | 21.56%  |
| LG Display              | 68        | 14.38%  |
| Chimei Innolux          | 52        | 10.99%  |
| Samsung Electronics     | 46        | 9.73%   |
| BOE                     | 45        | 9.51%   |
| Lenovo                  | 27        | 5.71%   |
| Dell                    | 19        | 4.02%   |
| Sharp                   | 18        | 3.81%   |
| Apple                   | 13        | 2.75%   |
| Chi Mei Optoelectronics | 9         | 1.9%    |
| Philips                 | 8         | 1.69%   |
| PANDA                   | 7         | 1.48%   |
| Hewlett-Packard         | 7         | 1.48%   |
| Goldstar                | 5         | 1.06%   |
| AOC                     | 5         | 1.06%   |
| ASUSTek Computer        | 4         | 0.85%   |
| Sony                    | 3         | 0.63%   |
| LG Philips              | 3         | 0.63%   |
| InfoVision              | 3         | 0.63%   |
| BenQ                    | 3         | 0.63%   |
| Seiko/Epson             | 2         | 0.42%   |
| Panasonic               | 2         | 0.42%   |
| LGD                     | 2         | 0.42%   |
| CSO                     | 2         | 0.42%   |
| CPT                     | 2         | 0.42%   |
| ViewSonic               | 1         | 0.21%   |
| Vestel Elektronik       | 1         | 0.21%   |
| TMX                     | 1         | 0.21%   |
| Tianma XM               | 1         | 0.21%   |
| RTK                     | 1         | 0.21%   |
| PVT                     | 1         | 0.21%   |
| Packard Bell            | 1         | 0.21%   |
| MSI                     | 1         | 0.21%   |
| JDI                     | 1         | 0.21%   |
| HKC                     | 1         | 0.21%   |
| Haier                   | 1         | 0.21%   |
| Fujitsu Siemens         | 1         | 0.21%   |
| DENON                   | 1         | 0.21%   |
| ANX                     | 1         | 0.21%   |
| Ancor Communications    | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 6         | 1.24%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 5         | 1.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.03%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.82%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 4         | 0.82%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch     | 3         | 0.62%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 3         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch         | 3         | 0.62%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 3         | 0.62%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 3         | 0.62%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.41%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.41%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch     | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch     | 2         | 0.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.41%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 2         | 0.41%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.41%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch              | 2         | 0.41%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 2         | 0.41%   |
| LG Display LCD Monitor LGD0226 1600x900 382x215mm 17.3-inch              | 2         | 0.41%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 2         | 0.41%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 2         | 0.41%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 2         | 0.41%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.41%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch              | 2         | 0.41%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 2         | 0.41%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                        | 2         | 0.41%   |
| Dell 2208WFP DEL403C 1680x1050 473x296mm 22.0-inch                       | 2         | 0.41%   |
| CPT LCD Monitor CPT1006 1400x1050 304x228mm 15.0-inch                    | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 196       | 43.65%  |
| 1366x768 (WXGA)    | 89        | 19.82%  |
| 3840x2160 (4K)     | 35        | 7.8%    |
| 1600x900 (HD+)     | 32        | 7.13%   |
| 2560x1440 (QHD)    | 20        | 4.45%   |
| 1280x800 (WXGA)    | 17        | 3.79%   |
| 1920x1200 (WUXGA)  | 12        | 2.67%   |
| 1440x900 (WXGA+)   | 8         | 1.78%   |
| 1680x1050 (WSXGA+) | 7         | 1.56%   |
| 2880x1800          | 6         | 1.34%   |
| 2560x1600          | 4         | 0.89%   |
| 1400x1050          | 3         | 0.67%   |
| 3840x2400          | 2         | 0.45%   |
| 3440x1440          | 2         | 0.45%   |
| 3200x1800 (QHD+)   | 2         | 0.45%   |
| 3000x2000          | 2         | 0.45%   |
| 1280x1024 (SXGA)   | 2         | 0.45%   |
| 1024x600           | 2         | 0.45%   |
| 800x1280           | 1         | 0.22%   |
| 3840x1600          | 1         | 0.22%   |
| 3840x1100          | 1         | 0.22%   |
| 3840x1080          | 1         | 0.22%   |
| 2160x1440          | 1         | 0.22%   |
| 1920x540           | 1         | 0.22%   |
| 1360x768           | 1         | 0.22%   |
| Unknown            | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 177       | 37.18%  |
| 14      | 71        | 14.92%  |
| 13      | 69        | 14.5%   |
| 17      | 34        | 7.14%   |
| 27      | 23        | 4.83%   |
| 12      | 21        | 4.41%   |
| 24      | 19        | 3.99%   |
| Unknown | 10        | 2.1%    |
| 23      | 9         | 1.89%   |
| 31      | 8         | 1.68%   |
| 84      | 5         | 1.05%   |
| 22      | 4         | 0.84%   |
| 11      | 4         | 0.84%   |
| 21      | 3         | 0.63%   |
| 18      | 3         | 0.63%   |
| 10      | 3         | 0.63%   |
| 72      | 2         | 0.42%   |
| 34      | 2         | 0.42%   |
| 25      | 2         | 0.42%   |
| 19      | 2         | 0.42%   |
| 65      | 1         | 0.21%   |
| 46      | 1         | 0.21%   |
| 37      | 1         | 0.21%   |
| 29      | 1         | 0.21%   |
| 16      | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 275       | 58.64%  |
| 201-300     | 62        | 13.22%  |
| 501-600     | 44        | 9.38%   |
| 351-400     | 42        | 8.96%   |
| 601-700     | 14        | 2.99%   |
| 401-500     | 10        | 2.13%   |
| Unknown     | 10        | 2.13%   |
| 1501-2000   | 7         | 1.49%   |
| 701-800     | 2         | 0.43%   |
| 1001-1500   | 2         | 0.43%   |
| 801-900     | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 335       | 80.34%  |
| 16/10   | 59        | 14.15%  |
| Unknown | 7         | 1.68%   |
| 3/2     | 6         | 1.44%   |
| 4/3     | 3         | 0.72%   |
| 21/9    | 3         | 0.72%   |
| 5/4     | 2         | 0.48%   |
| 3.40    | 1         | 0.24%   |
| 0.62    | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 177       | 37.42%  |
| 81-90          | 112       | 23.68%  |
| 71-80          | 28        | 5.92%   |
| 121-130        | 25        | 5.29%   |
| 301-350        | 23        | 4.86%   |
| 201-250        | 23        | 4.86%   |
| 61-70          | 19        | 4.02%   |
| 251-300        | 12        | 2.54%   |
| 351-500        | 10        | 2.11%   |
| Unknown        | 10        | 2.11%   |
| More than 1000 | 8         | 1.69%   |
| 131-140        | 8         | 1.69%   |
| 51-60          | 5         | 1.06%   |
| 141-150        | 4         | 0.85%   |
| 41-50          | 3         | 0.63%   |
| 151-200        | 2         | 0.42%   |
| 501-1000       | 2         | 0.42%   |
| 91-100         | 2         | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 208       | 45.02%  |
| 101-120       | 116       | 25.11%  |
| 51-100        | 65        | 14.07%  |
| 161-240       | 35        | 7.58%   |
| More than 240 | 24        | 5.19%   |
| Unknown       | 10        | 2.16%   |
| 1-50          | 4         | 0.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 331       | 79.19%  |
| 2     | 67        | 16.03%  |
| 3     | 10        | 2.39%   |
| 0     | 8         | 1.91%   |
| 4     | 2         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 247       | 38.78%  |
| Realtek Semiconductor             | 177       | 27.79%  |
| Qualcomm Atheros                  | 79        | 12.4%   |
| Broadcom                          | 36        | 5.65%   |
| Lenovo                            | 12        | 1.88%   |
| Sierra Wireless                   | 11        | 1.73%   |
| MediaTek                          | 10        | 1.57%   |
| Broadcom Limited                  | 10        | 1.57%   |
| Ericsson Business Mobile Networks | 9         | 1.41%   |
| Ralink                            | 6         | 0.94%   |
| Nvidia                            | 5         | 0.78%   |
| Marvell Technology Group          | 5         | 0.78%   |
| Ralink Technology                 | 3         | 0.47%   |
| Qualcomm                          | 3         | 0.47%   |
| Dell                              | 3         | 0.47%   |
| Samsung Electronics               | 2         | 0.31%   |
| NetGear                           | 2         | 0.31%   |
| DisplayLink                       | 2         | 0.31%   |
| ASIX Electronics                  | 2         | 0.31%   |
| ZyXEL Communications              | 1         | 0.16%   |
| Xiaomi                            | 1         | 0.16%   |
| TP-Link                           | 1         | 0.16%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.16%   |
| Philips (or NXP)                  | 1         | 0.16%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.16%   |
| Linksys                           | 1         | 0.16%   |
| ICS Advent                        | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| Google                            | 1         | 0.16%   |
| FIBOCOM                           | 1         | 0.16%   |
| D-Link System                     | 1         | 0.16%   |
| ASUSTek Computer                  | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 116       | 14.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 30        | 3.72%   |
| Intel Wireless 8265 / 8275                                              | 27        | 3.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 27        | 3.35%   |
| Intel Wireless 7260                                                     | 26        | 3.22%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 2.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 23        | 2.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 2.11%   |
| Intel Wireless 8260                                                     | 16        | 1.98%   |
| Intel Wireless 7265                                                     | 14        | 1.73%   |
| Intel Ethernet Connection (4) I219-LM                                   | 14        | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 1.49%   |
| Intel Ethernet Connection I218-LM                                       | 12        | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.99%   |
| Intel Ethernet Connection I219-LM                                       | 8         | 0.99%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.87%   |
| Intel Ethernet Connection I219-V                                        | 7         | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                                | 7         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.74%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.74%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                    | 6         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 0.74%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 5         | 0.62%   |
| Sierra Wireless EM7345 4G LTE                                           | 5         | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.62%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                                   | 5         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 240       | 56.6%   |
| Qualcomm Atheros      | 66        | 15.57%  |
| Realtek Semiconductor | 44        | 10.38%  |
| Broadcom              | 25        | 5.9%    |
| Sierra Wireless       | 11        | 2.59%   |
| MediaTek              | 10        | 2.36%   |
| Broadcom Limited      | 7         | 1.65%   |
| Ralink                | 6         | 1.42%   |
| Ralink Technology     | 3         | 0.71%   |
| Qualcomm              | 2         | 0.47%   |
| NetGear               | 2         | 0.47%   |
| Dell                  | 2         | 0.47%   |
| ZyXEL Communications  | 1         | 0.24%   |
| TP-Link               | 1         | 0.24%   |
| Philips (or NXP)      | 1         | 0.24%   |
| FIBOCOM               | 1         | 0.24%   |
| D-Link System         | 1         | 0.24%   |
| ASUSTek Computer      | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 27        | 6.37%   |
| Intel Wireless 7260                                                     | 26        | 6.13%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 5.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 23        | 5.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 4.01%   |
| Intel Wireless 8260                                                     | 16        | 3.77%   |
| Intel Wireless 7265                                                     | 14        | 3.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 2.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 2.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.89%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.42%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 1.42%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 1.42%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 5         | 1.18%   |
| Sierra Wireless EM7345 4G LTE                                           | 5         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 1.18%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.18%   |
| Intel Wireless-AC 9260                                                  | 5         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.18%   |
| Intel Centrino Advanced-N 6200                                          | 5         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.18%   |
| Intel Wireless 3165                                                     | 4         | 0.94%   |
| Intel Wireless 3160                                                     | 4         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.94%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 163       | 44.29%  |
| Intel                            | 132       | 35.87%  |
| Qualcomm Atheros                 | 20        | 5.43%   |
| Broadcom                         | 16        | 4.35%   |
| Lenovo                           | 12        | 3.26%   |
| Nvidia                           | 5         | 1.36%   |
| Marvell Technology Group         | 5         | 1.36%   |
| Broadcom Limited                 | 3         | 0.82%   |
| Samsung Electronics              | 2         | 0.54%   |
| DisplayLink                      | 2         | 0.54%   |
| ASIX Electronics                 | 2         | 0.54%   |
| Xiaomi                           | 1         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Qualcomm                         | 1         | 0.27%   |
| Linksys                          | 1         | 0.27%   |
| ICS Advent                       | 1         | 0.27%   |
| Google                           | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 116       | 31.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 8.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 27        | 7.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 3.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.24%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 3.24%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 2.16%   |
| Intel Ethernet Connection I219-V                                  | 7         | 1.89%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.62%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 1.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.35%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 1.08%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 1.08%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.81%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 3         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.81%   |
| Intel Ethernet Connection (13) I219-V                             | 3         | 0.81%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.81%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.81%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.81%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.54%   |
| Realtek Realtek Ethernet controller                               | 2         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.54%   |
| Lenovo ThinkPad Lan                                               | 2         | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.54%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 399       | 52.64%  |
| Ethernet | 346       | 45.65%  |
| Modem    | 12        | 1.58%   |
| Unknown  | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 335       | 77.37%  |
| Ethernet | 98        | 22.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 320       | 79.01%  |
| 1     | 76        | 18.77%  |
| 3     | 5         | 1.23%   |
| 0     | 4         | 0.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 388       | 95.8%   |
| Yes  | 17        | 4.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 176       | 52.07%  |
| Broadcom                        | 35        | 10.36%  |
| Realtek Semiconductor           | 22        | 6.51%   |
| Qualcomm Atheros Communications | 21        | 6.21%   |
| Lite-On Technology              | 17        | 5.03%   |
| IMC Networks                    | 15        | 4.44%   |
| Foxconn / Hon Hai               | 12        | 3.55%   |
| Apple                           | 11        | 3.25%   |
| Hewlett-Packard                 | 9         | 2.66%   |
| Cambridge Silicon Radio         | 4         | 1.18%   |
| Dell                            | 3         | 0.89%   |
| Realtek                         | 2         | 0.59%   |
| Ralink Technology               | 2         | 0.59%   |
| ASUSTek Computer                | 2         | 0.59%   |
| USI                             | 1         | 0.3%    |
| Toshiba                         | 1         | 0.3%    |
| Taiyo Yuden                     | 1         | 0.3%    |
| Ralink                          | 1         | 0.3%    |
| MediaTek                        | 1         | 0.3%    |
| D-Link System                   | 1         | 0.3%    |
| Chicony Electronics             | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 95        | 28.11%  |
| Intel AX200 Bluetooth                               | 23        | 6.8%    |
| Intel AX201 Bluetooth                               | 19        | 5.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 5.03%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 4.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 2.96%   |
| Realtek Bluetooth Radio                             | 9         | 2.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 2.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 2.37%   |
| Apple Bluetooth Host Controller                     | 8         | 2.37%   |
| IMC Networks Wireless_Device                        | 7         | 2.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 2.07%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 1.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 1.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 1.48%   |
| IMC Networks Bluetooth Radio                        | 5         | 1.48%   |
| Lite-On Bluetooth Device                            | 4         | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.18%   |
| Intel AX210 Bluetooth                               | 4         | 1.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.18%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.89%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.89%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.89%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.89%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.89%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.89%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.59%   |
| Realtek Bluetooth Radio                             | 2         | 0.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.59%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.59%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.59%   |
| USI Bluetooth Device                                | 1         | 0.3%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.3%    |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.3%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.3%    |
| Ralink CSR BS8510                                   | 1         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 320       | 63.75%  |
| AMD                              | 76        | 15.14%  |
| Nvidia                           | 68        | 13.55%  |
| Lenovo                           | 10        | 1.99%   |
| GN Netcom                        | 6         | 1.2%    |
| Plantronics                      | 3         | 0.6%    |
| Hewlett-Packard                  | 3         | 0.6%    |
| Sennheiser Communications        | 2         | 0.4%    |
| Realtek Semiconductor            | 2         | 0.4%    |
| Razer USA                        | 2         | 0.4%    |
| VIA Technologies                 | 1         | 0.2%    |
| Texas Instruments                | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Samson Technologies              | 1         | 0.2%    |
| NAD Electronics                  | 1         | 0.2%    |
| Kingston Technology              | 1         | 0.2%    |
| Creative Technology              | 1         | 0.2%    |
| C-Media Electronics              | 1         | 0.2%    |
| Blue Microphones                 | 1         | 0.2%    |
| Afatech                          | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 68        | 11.04%  |
| AMD Family 17h/19h HD Audio Controller                                     | 45        | 7.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 4.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 28        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26        | 4.22%   |
| Intel Haswell-ULT HD Audio Controller                                      | 25        | 4.06%   |
| Intel 8 Series HD Audio Controller                                         | 25        | 4.06%   |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 20        | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19        | 3.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 17        | 2.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 1.95%   |
| Intel CM238 HD Audio Controller                                            | 10        | 1.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 9         | 1.46%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 4         | 0.65%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 4         | 0.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 0.65%   |
| AMD High Definition Audio Controller                                       | 4         | 0.65%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.49%   |
| Nvidia GT216 HDMI Audio Controller                                         | 3         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 67        | 30.88%  |
| SK hynix            | 56        | 25.81%  |
| Micron Technology   | 31        | 14.29%  |
| Kingston            | 22        | 10.14%  |
| Unknown             | 13        | 5.99%   |
| Crucial             | 6         | 2.76%   |
| Elpida              | 5         | 2.3%    |
| Nanya Technology    | 3         | 1.38%   |
| Corsair             | 3         | 1.38%   |
| A-DATA Technology   | 3         | 1.38%   |
| Ramaxel Technology  | 2         | 0.92%   |
| Transcend           | 1         | 0.46%   |
| G.Skill             | 1         | 0.46%   |
| fef5                | 1         | 0.46%   |
| Avant               | 1         | 0.46%   |
| Apacer              | 1         | 0.46%   |
| Unknown             | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 8         | 3.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 2.19%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 1.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 1.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 1.75%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 1.75%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 3         | 1.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 1.32%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 3         | 1.32%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 3         | 1.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 2         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 2         | 0.88%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                       | 2         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.88%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 0.88%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.88%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 0.88%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 0.88%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 2         | 0.88%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 2         | 0.88%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.88%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.88%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 0.88%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 2         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.88%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.88%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 2         | 0.88%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s               | 2         | 0.88%   |
| Micron RAM 4ATS1G64HZ-2G3A1 8GB SODIMM DDR4 2400MT/s                | 2         | 0.88%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.88%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s              | 2         | 0.88%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s              | 2         | 0.88%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 2         | 0.88%   |
| Unknown RAM Module 8GB SODIMM LPDDR3 1600MT/s                       | 1         | 0.44%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.44%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                    | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 89        | 48.11%  |
| DDR3    | 61        | 32.97%  |
| LPDDR3  | 14        | 7.57%   |
| DDR2    | 8         | 4.32%   |
| LPDDR4  | 7         | 3.78%   |
| Unknown | 2         | 1.08%   |
| SDRAM   | 1         | 0.54%   |
| LPDDR5  | 1         | 0.54%   |
| DRAM    | 1         | 0.54%   |
| DDR     | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 162       | 87.1%   |
| Row Of Chips | 16        | 8.6%    |
| Chip         | 4         | 2.15%   |
| Unknown      | 3         | 1.61%   |
| DIMM         | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 90        | 45.92%  |
| 4096  | 44        | 22.45%  |
| 16384 | 36        | 18.37%  |
| 2048  | 19        | 9.69%   |
| 32768 | 4         | 2.04%   |
| 1024  | 2         | 1.02%   |
| 512   | 1         | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 48        | 24.24%  |
| 2667    | 47        | 23.74%  |
| 3200    | 27        | 13.64%  |
| 2133    | 21        | 10.61%  |
| 2400    | 12        | 6.06%   |
| 1334    | 10        | 5.05%   |
| 1333    | 8         | 4.04%   |
| 667     | 7         | 3.54%   |
| 1867    | 5         | 2.53%   |
| 4266    | 3         | 1.52%   |
| Unknown | 3         | 1.52%   |
| 4267    | 2         | 1.01%   |
| 1067    | 2         | 1.01%   |
| 8400    | 1         | 0.51%   |
| 4199    | 1         | 0.51%   |
| 800     | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 2         | 50%     |
| Hewlett-Packard    | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP DeskJet 3700 series   | 1         | 25%     |
| Canon PIXMA MX370 Series | 1         | 25%     |
| Canon PIXMA MP280        | 1         | 25%     |
| Brother HL-1210W series  | 1         | 25%     |

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
| Chicony Electronics                    | 109       | 30.62%  |
| Acer                                   | 47        | 13.2%   |
| IMC Networks                           | 37        | 10.39%  |
| Realtek Semiconductor                  | 27        | 7.58%   |
| Microdia                               | 18        | 5.06%   |
| Suyin                                  | 15        | 4.21%   |
| Lite-On Technology                     | 15        | 4.21%   |
| Sunplus Innovation Technology          | 14        | 3.93%   |
| Quanta                                 | 14        | 3.93%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.09%   |
| Logitech                               | 9         | 2.53%   |
| Syntek                                 | 8         | 2.25%   |
| Apple                                  | 8         | 2.25%   |
| Silicon Motion                         | 4         | 1.12%   |
| Lenovo                                 | 4         | 1.12%   |
| Luxvisions Innotech Limited            | 3         | 0.84%   |
| Samsung Electronics                    | 2         | 0.56%   |
| Primax Electronics                     | 2         | 0.56%   |
| Alcor Micro                            | 2         | 0.56%   |
| Z-Star Microelectronics                | 1         | 0.28%   |
| Sonix Technology                       | 1         | 0.28%   |
| Ricoh                                  | 1         | 0.28%   |
| MacroSilicon                           | 1         | 0.28%   |
| Genesys Logic                          | 1         | 0.28%   |
| GEMBIRD                                | 1         | 0.28%   |
| ALi                                    | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 29        | 8.1%    |
| IMC Networks Integrated Camera           | 15        | 4.19%   |
| Chicony HD WebCam                        | 12        | 3.35%   |
| Realtek Integrated_Webcam_HD             | 11        | 3.07%   |
| Acer Integrated Camera                   | 10        | 2.79%   |
| Microdia Integrated_Webcam_HD            | 9         | 2.51%   |
| IMC Networks USB2.0 HD UVC WebCam        | 9         | 2.51%   |
| Lite-On Integrated Camera                | 8         | 2.23%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 1.96%   |
| Chicony HP HD Camera                     | 6         | 1.68%   |
| Acer Lenovo EasyCamera                   | 6         | 1.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 5         | 1.4%    |
| Apple Built-in iSight                    | 5         | 1.4%    |
| Acer SunplusIT Integrated Camera         | 5         | 1.4%    |
| Syntek Lenovo EasyCamera                 | 4         | 1.12%   |
| Chicony USB 2.0 Camera                   | 4         | 1.12%   |
| Chicony Integrated Camera (1280x720@30)  | 4         | 1.12%   |
| Acer ThinkPad Integrated Camera          | 4         | 1.12%   |
| Acer EasyCamera                          | 4         | 1.12%   |
| Sunplus Laptop Integrated WebCam HD      | 3         | 0.84%   |
| Sunplus Integrated_Webcam_HD             | 3         | 0.84%   |
| Quanta USB2.0 HD UVC WebCam              | 3         | 0.84%   |
| Quanta HP Webcam                         | 3         | 0.84%   |
| Quanta HD Webcam                         | 3         | 0.84%   |
| Microdia Integrated Webcam               | 3         | 0.84%   |
| Lite-On HP HD Webcam                     | 3         | 0.84%   |
| Lenovo Integrated Webcam                 | 3         | 0.84%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 3         | 0.84%   |
| IMC Networks USB Camera                  | 3         | 0.84%   |
| Chicony USB2.0 Camera                    | 3         | 0.84%   |
| Chicony Lenovo EasyCamera                | 3         | 0.84%   |
| Chicony Integrated Camera [ThinkPad]     | 3         | 0.84%   |
| Chicony HP Truevision HD                 | 3         | 0.84%   |
| Acer ThinkPad P50 Integrated Camera      | 3         | 0.84%   |
| Acer SunplusIT INC. Integrated Camera    | 3         | 0.84%   |
| Acer Lenovo Integrated Webcam            | 3         | 0.84%   |
| Acer HD Webcam                           | 3         | 0.84%   |
| Syntek Integrated Camera                 | 2         | 0.56%   |
| Suyin HP Webcam-101                      | 2         | 0.56%   |
| Suyin HP TrueVision HD Integrated Webcam | 2         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 44        | 39.64%  |
| Synaptics                  | 33        | 29.73%  |
| Upek                       | 11        | 9.91%   |
| AuthenTec                  | 9         | 8.11%   |
| Shenzhen Goodix Technology | 8         | 7.21%   |
| Elan Microelectronics      | 4         | 3.6%    |
| STMicroelectronics         | 1         | 0.9%    |
| LighTuning Technology      | 1         | 0.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 20.72%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 9.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 9.91%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 7.21%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 4.5%    |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 4.5%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.6%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.6%    |
| AuthenTec AES2810                                                          | 4         | 3.6%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 3.6%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.8%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.8%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.8%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.8%    |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.8%    |
| Elan ELAN:Fingerprint                                                      | 2         | 1.8%    |
| Elan ELAN:ARM-M4                                                           | 2         | 1.8%    |
| Unknown                                                                    | 2         | 1.8%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.9%    |
| Validity Sensors VFS491                                                    | 1         | 0.9%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.9%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.9%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.9%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.9%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.9%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.9%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 36        | 61.02%  |
| Broadcom    | 15        | 25.42%  |
| Upek        | 6         | 10.17%  |
| Lenovo      | 2         | 3.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 36        | 61.02%  |
| Broadcom 5880                                                                | 7         | 11.86%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 10.17%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 8.47%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.39%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.39%   |
| Broadcom 58200                                                               | 1         | 1.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 216       | 51.92%  |
| 1     | 145       | 34.86%  |
| 2     | 43        | 10.34%  |
| 3     | 8         | 1.92%   |
| 4     | 2         | 0.48%   |
| 10    | 1         | 0.24%   |
| 6     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 110       | 41.35%  |
| Chipcard                 | 56        | 21.05%  |
| Graphics card            | 38        | 14.29%  |
| Net/wireless             | 16        | 6.02%   |
| Multimedia controller    | 16        | 6.02%   |
| Card reader              | 9         | 3.38%   |
| Camera                   | 6         | 2.26%   |
| Storage                  | 4         | 1.5%    |
| Communication controller | 4         | 1.5%    |
| Sound                    | 2         | 0.75%   |
| Net/ethernet             | 2         | 0.75%   |
| Bluetooth                | 2         | 0.75%   |
| Modem                    | 1         | 0.38%   |

