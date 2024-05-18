NixOS - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for NixOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NixOS/Desktop/README.md) and [notebooks](/Dist/NixOS/Notebook/README.md).

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

Total: 582

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [161509c62b](https://linux-hardware.org/?probe=161509c62b) | May 09, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [73060b4642](https://linux-hardware.org/?probe=73060b4642) | May 07, 2024 |
| Acer          | TravelMate Spin P414RN-5... | Convertible | [5d3f93b635](https://linux-hardware.org/?probe=5d3f93b635) | May 07, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [44f44fe800](https://linux-hardware.org/?probe=44f44fe800) | May 06, 2024 |
| HP            | 2B2C                        | Desktop     | [082d220d35](https://linux-hardware.org/?probe=082d220d35) | May 04, 2024 |
| Apple         | MacBookPro16,2              | Notebook    | [fe05b165fb](https://linux-hardware.org/?probe=fe05b165fb) | May 04, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [1902c0eeab](https://linux-hardware.org/?probe=1902c0eeab) | May 02, 2024 |
| Acer          | Predator PH315-51           | Notebook    | [6cadb88b1d](https://linux-hardware.org/?probe=6cadb88b1d) | May 01, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [3146b9914d](https://linux-hardware.org/?probe=3146b9914d) | May 01, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [32d8346d26](https://linux-hardware.org/?probe=32d8346d26) | May 01, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [90807317fb](https://linux-hardware.org/?probe=90807317fb) | May 01, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [5cd273406c](https://linux-hardware.org/?probe=5cd273406c) | Apr 30, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [836078acb2](https://linux-hardware.org/?probe=836078acb2) | Apr 29, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [45bc744085](https://linux-hardware.org/?probe=45bc744085) | Apr 28, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [7c970a2e6f](https://linux-hardware.org/?probe=7c970a2e6f) | Apr 27, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [33f2b78f07](https://linux-hardware.org/?probe=33f2b78f07) | Apr 27, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [55a3147182](https://linux-hardware.org/?probe=55a3147182) | Apr 26, 2024 |
| Unknown       | X79A                        | Desktop     | [c0456a0238](https://linux-hardware.org/?probe=c0456a0238) | Apr 26, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [86305e383e](https://linux-hardware.org/?probe=86305e383e) | Apr 25, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [113c93d444](https://linux-hardware.org/?probe=113c93d444) | Apr 25, 2024 |
| Jetway        | 1.0                         | Desktop     | [5410155063](https://linux-hardware.org/?probe=5410155063) | Apr 25, 2024 |
| Dell          | Latitude 7330 Rugged Ext... | Notebook    | [787276b922](https://linux-hardware.org/?probe=787276b922) | Apr 25, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [e1d4486b51](https://linux-hardware.org/?probe=e1d4486b51) | Apr 24, 2024 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [26f465d651](https://linux-hardware.org/?probe=26f465d651) | Apr 24, 2024 |
| HP            | ProBook 440 G2              | Notebook    | [e5a4a84406](https://linux-hardware.org/?probe=e5a4a84406) | Apr 23, 2024 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [bf31c1e8e2](https://linux-hardware.org/?probe=bf31c1e8e2) | Apr 22, 2024 |
| Razer         | Blade 14 - RZ09-0508        | Notebook    | [cc1f5421e7](https://linux-hardware.org/?probe=cc1f5421e7) | Apr 21, 2024 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [95968f8653](https://linux-hardware.org/?probe=95968f8653) | Apr 19, 2024 |
| Gigabyte      | Z790 UD                     | Desktop     | [098435751f](https://linux-hardware.org/?probe=098435751f) | Apr 18, 2024 |
| Gigabyte      | Z790 UD                     | Desktop     | [ab7e23fe7d](https://linux-hardware.org/?probe=ab7e23fe7d) | Apr 18, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d9119d4702](https://linux-hardware.org/?probe=d9119d4702) | Apr 18, 2024 |
| MSI           | GE60 2PE                    | Notebook    | [38cce299c6](https://linux-hardware.org/?probe=38cce299c6) | Apr 18, 2024 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [25827e36e6](https://linux-hardware.org/?probe=25827e36e6) | Apr 18, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ba533ecb3a](https://linux-hardware.org/?probe=ba533ecb3a) | Apr 18, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [a805996b80](https://linux-hardware.org/?probe=a805996b80) | Apr 16, 2024 |
| Lenovo        | ThinkPad P50 20EN0007MH     | Notebook    | [d56c554eed](https://linux-hardware.org/?probe=d56c554eed) | Apr 16, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [6a7d29fe24](https://linux-hardware.org/?probe=6a7d29fe24) | Apr 15, 2024 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [edae497a7d](https://linux-hardware.org/?probe=edae497a7d) | Apr 14, 2024 |
| Razer         | Blade                       | Notebook    | [8ff543883a](https://linux-hardware.org/?probe=8ff543883a) | Apr 14, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [159bfe4be5](https://linux-hardware.org/?probe=159bfe4be5) | Apr 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [90946053e1](https://linux-hardware.org/?probe=90946053e1) | Apr 11, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [d48fd50ca7](https://linux-hardware.org/?probe=d48fd50ca7) | Apr 11, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [c468075794](https://linux-hardware.org/?probe=c468075794) | Apr 11, 2024 |
| MSI           | GL65 9SC                    | Notebook    | [7bc8965c5e](https://linux-hardware.org/?probe=7bc8965c5e) | Apr 10, 2024 |
| Google        | Redrix                      | Notebook    | [6dd8afed85](https://linux-hardware.org/?probe=6dd8afed85) | Apr 10, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [12d5a6c723](https://linux-hardware.org/?probe=12d5a6c723) | Apr 08, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [50c4a83180](https://linux-hardware.org/?probe=50c4a83180) | Apr 07, 2024 |
| System76      | Oryx Pro                    | Notebook    | [4592d774b4](https://linux-hardware.org/?probe=4592d774b4) | Apr 06, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | Notebook    | [81925bcc23](https://linux-hardware.org/?probe=81925bcc23) | Apr 05, 2024 |
| Microsoft     | Surface Pro 7               | Tablet      | [9314afa830](https://linux-hardware.org/?probe=9314afa830) | Apr 02, 2024 |
| Gigabyte      | GA-H61TN-SI                 | Desktop     | [3f6b496eb7](https://linux-hardware.org/?probe=3f6b496eb7) | Apr 02, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [32e0d11ee9](https://linux-hardware.org/?probe=32e0d11ee9) | Apr 02, 2024 |
| ASUSTek       | ROG Flow X16 GV601RE_GV6... | Convertible | [50f1f6c6db](https://linux-hardware.org/?probe=50f1f6c6db) | Mar 29, 2024 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [a675b83c7d](https://linux-hardware.org/?probe=a675b83c7d) | Mar 29, 2024 |
| Acer          | Swift SF514-54GT            | Notebook    | [c0a1536935](https://linux-hardware.org/?probe=c0a1536935) | Mar 28, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [75613012d4](https://linux-hardware.org/?probe=75613012d4) | Mar 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [57aabe3115](https://linux-hardware.org/?probe=57aabe3115) | Mar 26, 2024 |
| Dell          | Latitude 7420               | Notebook    | [511721b690](https://linux-hardware.org/?probe=511721b690) | Mar 23, 2024 |
| MSI           | B450-A PRO MAX              | Desktop     | [5448e71afb](https://linux-hardware.org/?probe=5448e71afb) | Mar 23, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [9fce956c50](https://linux-hardware.org/?probe=9fce956c50) | Mar 23, 2024 |
| Gigabyte      | Z790 AORUS ELITE X WIFI7    | Desktop     | [9a507bf688](https://linux-hardware.org/?probe=9a507bf688) | Mar 23, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [4445879c66](https://linux-hardware.org/?probe=4445879c66) | Mar 21, 2024 |
| Xunlong       | Orange Pi 3B                | Soc         | [09e82980da](https://linux-hardware.org/?probe=09e82980da) | Mar 21, 2024 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [164d9ccd8d](https://linux-hardware.org/?probe=164d9ccd8d) | Mar 21, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [01284be05a](https://linux-hardware.org/?probe=01284be05a) | Mar 20, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [027fecc047](https://linux-hardware.org/?probe=027fecc047) | Mar 18, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [b835c572e5](https://linux-hardware.org/?probe=b835c572e5) | Mar 18, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | Notebook    | [def7c584ff](https://linux-hardware.org/?probe=def7c584ff) | Mar 17, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | Notebook    | [3906b06830](https://linux-hardware.org/?probe=3906b06830) | Mar 17, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [1ceb0c75ea](https://linux-hardware.org/?probe=1ceb0c75ea) | Mar 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [5bad97c6ec](https://linux-hardware.org/?probe=5bad97c6ec) | Mar 15, 2024 |
| MSI           | B450-A PRO                  | Desktop     | [fcf37e125a](https://linux-hardware.org/?probe=fcf37e125a) | Mar 14, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [45cb718f8b](https://linux-hardware.org/?probe=45cb718f8b) | Mar 14, 2024 |
| Gigabyte      | GA-MA790GP-DS4H             | Desktop     | [9ffb06c47b](https://linux-hardware.org/?probe=9ffb06c47b) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [0772d17a95](https://linux-hardware.org/?probe=0772d17a95) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [644c52ac31](https://linux-hardware.org/?probe=644c52ac31) | Mar 13, 2024 |
| MSI           | B85M-E45                    | Desktop     | [6623f1bc66](https://linux-hardware.org/?probe=6623f1bc66) | Mar 12, 2024 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [06ecea6114](https://linux-hardware.org/?probe=06ecea6114) | Mar 12, 2024 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [260fb753fe](https://linux-hardware.org/?probe=260fb753fe) | Mar 11, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | Desktop     | [1bf5956e3f](https://linux-hardware.org/?probe=1bf5956e3f) | Mar 10, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [34bed62abf](https://linux-hardware.org/?probe=34bed62abf) | Mar 10, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [dc8badd739](https://linux-hardware.org/?probe=dc8badd739) | Mar 08, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [36f42c8be7](https://linux-hardware.org/?probe=36f42c8be7) | Mar 08, 2024 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [10e971349c](https://linux-hardware.org/?probe=10e971349c) | Mar 08, 2024 |
| MSI           | B450-A PRO                  | Desktop     | [ec32ffdea7](https://linux-hardware.org/?probe=ec32ffdea7) | Mar 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [25074d4407](https://linux-hardware.org/?probe=25074d4407) | Mar 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c2b5dc013f](https://linux-hardware.org/?probe=c2b5dc013f) | Mar 03, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [8a0a1f3b4a](https://linux-hardware.org/?probe=8a0a1f3b4a) | Mar 01, 2024 |
| Lenovo        | ThinkPad T480s 20L7S3750... | Notebook    | [ce625cdb1a](https://linux-hardware.org/?probe=ce625cdb1a) | Feb 29, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [43919c6c44](https://linux-hardware.org/?probe=43919c6c44) | Feb 29, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [2fae47ca0a](https://linux-hardware.org/?probe=2fae47ca0a) | Feb 29, 2024 |
| Gigabyte      | GA-MA790GP-DS4H             | Desktop     | [0bdc619992](https://linux-hardware.org/?probe=0bdc619992) | Feb 28, 2024 |
| Lenovo        | ThinkPad T480s 20L7S3750... | Notebook    | [7b3b02bc41](https://linux-hardware.org/?probe=7b3b02bc41) | Feb 28, 2024 |
| MSI           | GL65 9SC                    | Notebook    | [6981398659](https://linux-hardware.org/?probe=6981398659) | Feb 28, 2024 |
| Lenovo        | ThinkPad T480s 20L7S3750... | Notebook    | [8bdc7efaf7](https://linux-hardware.org/?probe=8bdc7efaf7) | Feb 28, 2024 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [b1de481d25](https://linux-hardware.org/?probe=b1de481d25) | Feb 28, 2024 |
| Dell          | Latitude 7420               | Notebook    | [fd13235e39](https://linux-hardware.org/?probe=fd13235e39) | Feb 27, 2024 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [6185ab568b](https://linux-hardware.org/?probe=6185ab568b) | Feb 27, 2024 |
| Microsoft     | Surface Laptop SE           | Tablet      | [fb82ad13c6](https://linux-hardware.org/?probe=fb82ad13c6) | Feb 27, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [f6c8d11592](https://linux-hardware.org/?probe=f6c8d11592) | Feb 26, 2024 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [848c852446](https://linux-hardware.org/?probe=848c852446) | Feb 25, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7a1e61aea2](https://linux-hardware.org/?probe=7a1e61aea2) | Feb 24, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [f4e1c02b92](https://linux-hardware.org/?probe=f4e1c02b92) | Feb 21, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [bccce50111](https://linux-hardware.org/?probe=bccce50111) | Feb 21, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [d8f261643b](https://linux-hardware.org/?probe=d8f261643b) | Feb 21, 2024 |
| Lenovo        | Y720-15IKB 81CQ             | Notebook    | [c62e8797a8](https://linux-hardware.org/?probe=c62e8797a8) | Feb 19, 2024 |
| Win elemen... | M600                        | Desktop     | [706d9a6da6](https://linux-hardware.org/?probe=706d9a6da6) | Feb 15, 2024 |
| Biostar       | TZ590-BTC DUO               | Desktop     | [43894bcb57](https://linux-hardware.org/?probe=43894bcb57) | Feb 15, 2024 |
| Lenovo        | ThinkPad Edge E531 68859... | Notebook    | [45a495ee7d](https://linux-hardware.org/?probe=45a495ee7d) | Feb 14, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7efa507cb3](https://linux-hardware.org/?probe=7efa507cb3) | Feb 12, 2024 |
| Acer          | AOD270                      | Notebook    | [a0b7e5e68a](https://linux-hardware.org/?probe=a0b7e5e68a) | Feb 11, 2024 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [fefa1b06db](https://linux-hardware.org/?probe=fefa1b06db) | Feb 08, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9db247a049](https://linux-hardware.org/?probe=9db247a049) | Feb 08, 2024 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | Notebook    | [66c0cc51e3](https://linux-hardware.org/?probe=66c0cc51e3) | Feb 06, 2024 |
| ASUSTek       | ROG Strix G513QE_G513QE     | Notebook    | [ea8930c46e](https://linux-hardware.org/?probe=ea8930c46e) | Feb 06, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [696b85242c](https://linux-hardware.org/?probe=696b85242c) | Feb 03, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fe7dfd8247](https://linux-hardware.org/?probe=fe7dfd8247) | Feb 02, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [55197489b0](https://linux-hardware.org/?probe=55197489b0) | Feb 02, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [1579230b7f](https://linux-hardware.org/?probe=1579230b7f) | Feb 02, 2024 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [ae13945074](https://linux-hardware.org/?probe=ae13945074) | Feb 01, 2024 |
| Corsair       | Voyager a1600               | Notebook    | [86aec463cc](https://linux-hardware.org/?probe=86aec463cc) | Jan 30, 2024 |
| Corsair       | Voyager a1600               | Notebook    | [00605bf92c](https://linux-hardware.org/?probe=00605bf92c) | Jan 28, 2024 |
| Biostar       | TZ590-BTC DUO               | Desktop     | [86684436da](https://linux-hardware.org/?probe=86684436da) | Jan 27, 2024 |
| Biostar       | TZ590-BTC DUO               | Desktop     | [68df04d154](https://linux-hardware.org/?probe=68df04d154) | Jan 27, 2024 |
| Sony          | VGN-CS11S_Q                 | Notebook    | [df687ca726](https://linux-hardware.org/?probe=df687ca726) | Jan 26, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [d7308911e4](https://linux-hardware.org/?probe=d7308911e4) | Jan 26, 2024 |
| Framework     | Laptop                      | Notebook    | [64d0e147fe](https://linux-hardware.org/?probe=64d0e147fe) | Jan 25, 2024 |
| MSI           | MS-B1831                    | Desktop     | [45dd2bc3a1](https://linux-hardware.org/?probe=45dd2bc3a1) | Jan 25, 2024 |
| Sony          | VGN-CS11S_Q                 | Notebook    | [4c9e427a30](https://linux-hardware.org/?probe=4c9e427a30) | Jan 25, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [4a41cdcc67](https://linux-hardware.org/?probe=4a41cdcc67) | Jan 25, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c2be9790ea](https://linux-hardware.org/?probe=c2be9790ea) | Jan 25, 2024 |
| ASUSTek       | UX370UAF                    | Convertible | [170f79245c](https://linux-hardware.org/?probe=170f79245c) | Jan 20, 2024 |
| Lenovo        | ThinkPad T495 20NJ0016MX    | Notebook    | [31aa08c915](https://linux-hardware.org/?probe=31aa08c915) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [553986db8b](https://linux-hardware.org/?probe=553986db8b) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f73bc25ab5](https://linux-hardware.org/?probe=f73bc25ab5) | Jan 17, 2024 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [ca16a763c8](https://linux-hardware.org/?probe=ca16a763c8) | Jan 17, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [6cfbe412a8](https://linux-hardware.org/?probe=6cfbe412a8) | Jan 16, 2024 |
| System76      | Oryx Pro                    | Notebook    | [db771e1a08](https://linux-hardware.org/?probe=db771e1a08) | Jan 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8578d3d843](https://linux-hardware.org/?probe=8578d3d843) | Jan 15, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [128765ce37](https://linux-hardware.org/?probe=128765ce37) | Jan 15, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [3af1df104e](https://linux-hardware.org/?probe=3af1df104e) | Jan 15, 2024 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [655122ef53](https://linux-hardware.org/?probe=655122ef53) | Jan 14, 2024 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [268e37f04e](https://linux-hardware.org/?probe=268e37f04e) | Jan 14, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [0d1de0324b](https://linux-hardware.org/?probe=0d1de0324b) | Jan 14, 2024 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [929c108f73](https://linux-hardware.org/?probe=929c108f73) | Jan 13, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c5eb936632](https://linux-hardware.org/?probe=c5eb936632) | Jan 13, 2024 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ec63c6084b](https://linux-hardware.org/?probe=ec63c6084b) | Jan 12, 2024 |
| Apple         | MacBookPro3,1               | Notebook    | [87d8854210](https://linux-hardware.org/?probe=87d8854210) | Jan 12, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [9297ef72df](https://linux-hardware.org/?probe=9297ef72df) | Jan 12, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [17fa0ca044](https://linux-hardware.org/?probe=17fa0ca044) | Jan 12, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [bdc05e8e4e](https://linux-hardware.org/?probe=bdc05e8e4e) | Jan 11, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [579cc62424](https://linux-hardware.org/?probe=579cc62424) | Jan 11, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [508859d8fd](https://linux-hardware.org/?probe=508859d8fd) | Jan 11, 2024 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [ee3988fb25](https://linux-hardware.org/?probe=ee3988fb25) | Jan 09, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [40a1d7ca08](https://linux-hardware.org/?probe=40a1d7ca08) | Jan 08, 2024 |
| HUAWEI        | WRT-WX9                     | Notebook    | [5b9a494436](https://linux-hardware.org/?probe=5b9a494436) | Jan 08, 2024 |
| Dell          | XPS 9315                    | Notebook    | [af18bb67fd](https://linux-hardware.org/?probe=af18bb67fd) | Jan 08, 2024 |
| MSI           | Z170A SLI                   | Desktop     | [e58029e4a2](https://linux-hardware.org/?probe=e58029e4a2) | Jan 08, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [00c7d53339](https://linux-hardware.org/?probe=00c7d53339) | Jan 08, 2024 |
| Fujitsu       | LIFEBOOK U7412              | Notebook    | [e7b60f15e8](https://linux-hardware.org/?probe=e7b60f15e8) | Jan 08, 2024 |
| Dell          | 0FXD80 A00                  | Desktop     | [628772fa2d](https://linux-hardware.org/?probe=628772fa2d) | Jan 07, 2024 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [3e11f092ef](https://linux-hardware.org/?probe=3e11f092ef) | Jan 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | Notebook    | [739eae84a2](https://linux-hardware.org/?probe=739eae84a2) | Jan 07, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [fb05620dfd](https://linux-hardware.org/?probe=fb05620dfd) | Jan 05, 2024 |
| Dell          | Inspiron 5767               | Notebook    | [460e0f5fa4](https://linux-hardware.org/?probe=460e0f5fa4) | Jan 05, 2024 |
| Dell          | Inspiron 7506 2n1           | Convertible | [ae203f3797](https://linux-hardware.org/?probe=ae203f3797) | Jan 05, 2024 |
| ASUSTek       | Pro WS TRX50-SAGE WIFI      | Desktop     | [cfba81369c](https://linux-hardware.org/?probe=cfba81369c) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [527cc7c1d4](https://linux-hardware.org/?probe=527cc7c1d4) | Jan 05, 2024 |
| HP            | 1790                        | Desktop     | [e554a0f029](https://linux-hardware.org/?probe=e554a0f029) | Jan 04, 2024 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [8d22dafe25](https://linux-hardware.org/?probe=8d22dafe25) | Jan 03, 2024 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [91b39eb7b5](https://linux-hardware.org/?probe=91b39eb7b5) | Jan 03, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [733b1e64b3](https://linux-hardware.org/?probe=733b1e64b3) | Jan 03, 2024 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [9c965e61f4](https://linux-hardware.org/?probe=9c965e61f4) | Jan 02, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [5ea7f924df](https://linux-hardware.org/?probe=5ea7f924df) | Jan 02, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [f96513dd00](https://linux-hardware.org/?probe=f96513dd00) | Jan 02, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [c6c9c3c74e](https://linux-hardware.org/?probe=c6c9c3c74e) | Jan 01, 2024 |
| Lenovo        | ThinkPad Twist 33476LU      | Notebook    | [bb88a71510](https://linux-hardware.org/?probe=bb88a71510) | Jan 01, 2024 |
| System76      | Serval WS                   | Notebook    | [3dd4d45859](https://linux-hardware.org/?probe=3dd4d45859) | Dec 30, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [35e2f8c10c](https://linux-hardware.org/?probe=35e2f8c10c) | Dec 29, 2023 |
| AZW           | EQ                          | Desktop     | [f27e8ec7a4](https://linux-hardware.org/?probe=f27e8ec7a4) | Dec 27, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f8483f02ab](https://linux-hardware.org/?probe=f8483f02ab) | Dec 26, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [541f2d959f](https://linux-hardware.org/?probe=541f2d959f) | Dec 26, 2023 |
| Fujitsu       | LIFEBOOK U7412              | Notebook    | [a2797ec36b](https://linux-hardware.org/?probe=a2797ec36b) | Dec 26, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [ad6c489ffc](https://linux-hardware.org/?probe=ad6c489ffc) | Dec 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [ef18e09b69](https://linux-hardware.org/?probe=ef18e09b69) | Dec 23, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [f67367aa62](https://linux-hardware.org/?probe=f67367aa62) | Dec 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a953876b2c](https://linux-hardware.org/?probe=a953876b2c) | Dec 23, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [ac1d637679](https://linux-hardware.org/?probe=ac1d637679) | Dec 21, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [1d8538aeef](https://linux-hardware.org/?probe=1d8538aeef) | Dec 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [fb187c2fa4](https://linux-hardware.org/?probe=fb187c2fa4) | Dec 20, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [b6aa52f693](https://linux-hardware.org/?probe=b6aa52f693) | Dec 17, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [73693b1a91](https://linux-hardware.org/?probe=73693b1a91) | Dec 17, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [71c27a1bf6](https://linux-hardware.org/?probe=71c27a1bf6) | Dec 17, 2023 |
| Medion        | M14L-256                    | Notebook    | [6cd85934b3](https://linux-hardware.org/?probe=6cd85934b3) | Dec 15, 2023 |
| AZW           | EQ                          | Desktop     | [b6aa615ccf](https://linux-hardware.org/?probe=b6aa615ccf) | Dec 14, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [2982c2a2c6](https://linux-hardware.org/?probe=2982c2a2c6) | Dec 14, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [8617acecda](https://linux-hardware.org/?probe=8617acecda) | Dec 11, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [87be870a89](https://linux-hardware.org/?probe=87be870a89) | Dec 09, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [85d6d037cc](https://linux-hardware.org/?probe=85d6d037cc) | Dec 09, 2023 |
| Dell          | G5 5590                     | Notebook    | [6970987854](https://linux-hardware.org/?probe=6970987854) | Dec 08, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [62c4dde3a6](https://linux-hardware.org/?probe=62c4dde3a6) | Dec 07, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [2ba0c7198a](https://linux-hardware.org/?probe=2ba0c7198a) | Dec 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [5b8e1b7878](https://linux-hardware.org/?probe=5b8e1b7878) | Dec 05, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [aae20908c5](https://linux-hardware.org/?probe=aae20908c5) | Dec 05, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [525166f0d5](https://linux-hardware.org/?probe=525166f0d5) | Dec 04, 2023 |
| AZW           | EQ                          | Desktop     | [c2dedbf2f3](https://linux-hardware.org/?probe=c2dedbf2f3) | Dec 04, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [7273cc93a9](https://linux-hardware.org/?probe=7273cc93a9) | Dec 02, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1784c4c5b0](https://linux-hardware.org/?probe=1784c4c5b0) | Dec 01, 2023 |
| Dell          | 0J91V2 A05                  | Server      | [28e8abbbdf](https://linux-hardware.org/?probe=28e8abbbdf) | Dec 01, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [9f7f83e1ee](https://linux-hardware.org/?probe=9f7f83e1ee) | Nov 28, 2023 |
| retsamarre... | 000-F4423-FBA004-2000-N     | Tablet      | [5f97496a76](https://linux-hardware.org/?probe=5f97496a76) | Nov 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [07e6828b2e](https://linux-hardware.org/?probe=07e6828b2e) | Nov 23, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [05c1dddd8d](https://linux-hardware.org/?probe=05c1dddd8d) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450s 20BX001MU... | Notebook    | [80d4678e90](https://linux-hardware.org/?probe=80d4678e90) | Nov 23, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [602aeb4101](https://linux-hardware.org/?probe=602aeb4101) | Nov 22, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | Notebook    | [4065934176](https://linux-hardware.org/?probe=4065934176) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | Notebook    | [fbde674650](https://linux-hardware.org/?probe=fbde674650) | Nov 22, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [34b2b48e8c](https://linux-hardware.org/?probe=34b2b48e8c) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [494b2a6d2f](https://linux-hardware.org/?probe=494b2a6d2f) | Nov 19, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [576d311bde](https://linux-hardware.org/?probe=576d311bde) | Nov 18, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0820ebd908](https://linux-hardware.org/?probe=0820ebd908) | Nov 16, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [f21a42a965](https://linux-hardware.org/?probe=f21a42a965) | Nov 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ac7deed0de](https://linux-hardware.org/?probe=ac7deed0de) | Nov 16, 2023 |
| ASUSTek       | ROG Strix G513QE_G513QE     | Notebook    | [455efd5541](https://linux-hardware.org/?probe=455efd5541) | Nov 15, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [ce6a10d6a3](https://linux-hardware.org/?probe=ce6a10d6a3) | Nov 15, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [a263ed1c12](https://linux-hardware.org/?probe=a263ed1c12) | Nov 13, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [789eee99a6](https://linux-hardware.org/?probe=789eee99a6) | Nov 12, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [c55053fa25](https://linux-hardware.org/?probe=c55053fa25) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [67938dee90](https://linux-hardware.org/?probe=67938dee90) | Nov 12, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [503d3690b0](https://linux-hardware.org/?probe=503d3690b0) | Nov 11, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [dfbaeb29c5](https://linux-hardware.org/?probe=dfbaeb29c5) | Nov 11, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [e0883e3bd0](https://linux-hardware.org/?probe=e0883e3bd0) | Nov 11, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [35b2509d27](https://linux-hardware.org/?probe=35b2509d27) | Nov 10, 2023 |
| Nvidia        | snc302eeh                   | Desktop     | [2b0a14caec](https://linux-hardware.org/?probe=2b0a14caec) | Nov 10, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d9cad8ffde](https://linux-hardware.org/?probe=d9cad8ffde) | Nov 09, 2023 |
| Unknown       | Unknown                     | Soc         | [97dadee998](https://linux-hardware.org/?probe=97dadee998) | Nov 08, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [79e23fd44a](https://linux-hardware.org/?probe=79e23fd44a) | Nov 07, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2f6078ab72](https://linux-hardware.org/?probe=2f6078ab72) | Nov 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [49b3b70e38](https://linux-hardware.org/?probe=49b3b70e38) | Nov 07, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [1786e4735e](https://linux-hardware.org/?probe=1786e4735e) | Nov 07, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [0ecfad9d87](https://linux-hardware.org/?probe=0ecfad9d87) | Nov 07, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [30416c0355](https://linux-hardware.org/?probe=30416c0355) | Nov 04, 2023 |
| HP            | 83E1                        | Desktop     | [c82d34ebac](https://linux-hardware.org/?probe=c82d34ebac) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [0e5f976d6b](https://linux-hardware.org/?probe=0e5f976d6b) | Nov 02, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6f3e496918](https://linux-hardware.org/?probe=6f3e496918) | Oct 29, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b075cf8841](https://linux-hardware.org/?probe=b075cf8841) | Oct 28, 2023 |
| LattePanda    | Sigma                       | Desktop     | [d287cf2d8a](https://linux-hardware.org/?probe=d287cf2d8a) | Oct 26, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [387c91f530](https://linux-hardware.org/?probe=387c91f530) | Oct 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| ECS           | A55F-M3                     | Desktop     | [6da483b400](https://linux-hardware.org/?probe=6da483b400) | Oct 25, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [a80fcc753e](https://linux-hardware.org/?probe=a80fcc753e) | Oct 25, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [c0bcd133c9](https://linux-hardware.org/?probe=c0bcd133c9) | Oct 22, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Framework     | Laptop                      | Notebook    | [e765d5da63](https://linux-hardware.org/?probe=e765d5da63) | Oct 18, 2023 |
| Unknown       | Apple Mac mini (M1, 2020... | Mini pc     | [e6566d9c7c](https://linux-hardware.org/?probe=e6566d9c7c) | Oct 18, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [da6815d760](https://linux-hardware.org/?probe=da6815d760) | Oct 18, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [11155b7b3a](https://linux-hardware.org/?probe=11155b7b3a) | Oct 13, 2023 |
| Unknown       | HX90                        | Desktop     | [f247716ab0](https://linux-hardware.org/?probe=f247716ab0) | Oct 13, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [ba690b36a3](https://linux-hardware.org/?probe=ba690b36a3) | Oct 12, 2023 |
| MSI           | Prestige 16Studio A13VE     | Notebook    | [0209063983](https://linux-hardware.org/?probe=0209063983) | Oct 12, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [7ff5fe9fdd](https://linux-hardware.org/?probe=7ff5fe9fdd) | Oct 11, 2023 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | Notebook    | [a4d6af03fe](https://linux-hardware.org/?probe=a4d6af03fe) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [801a2a4abf](https://linux-hardware.org/?probe=801a2a4abf) | Oct 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [fc3ea4bb32](https://linux-hardware.org/?probe=fc3ea4bb32) | Oct 08, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [89472bd2f3](https://linux-hardware.org/?probe=89472bd2f3) | Oct 07, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [90f777d9cc](https://linux-hardware.org/?probe=90f777d9cc) | Oct 07, 2023 |
| Dell          | 08DM12 A01                  | Server      | [9faef398d0](https://linux-hardware.org/?probe=9faef398d0) | Oct 07, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [642a2f5a9b](https://linux-hardware.org/?probe=642a2f5a9b) | Oct 04, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a4fbd5793d](https://linux-hardware.org/?probe=a4fbd5793d) | Oct 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [c67f66f5e3](https://linux-hardware.org/?probe=c67f66f5e3) | Oct 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [007bb33fbf](https://linux-hardware.org/?probe=007bb33fbf) | Oct 01, 2023 |
| Dell          | Latitude E6540              | Notebook    | [8fdc000f7e](https://linux-hardware.org/?probe=8fdc000f7e) | Oct 01, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a5de8b78e7](https://linux-hardware.org/?probe=a5de8b78e7) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [1135ddac8e](https://linux-hardware.org/?probe=1135ddac8e) | Sep 30, 2023 |
| MSI           | Z68A-GD65                   | Desktop     | [c0f968740b](https://linux-hardware.org/?probe=c0f968740b) | Sep 29, 2023 |
| Dell          | Latitude 5430               | Notebook    | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | Notebook    | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [1478e1265d](https://linux-hardware.org/?probe=1478e1265d) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [0177e96165](https://linux-hardware.org/?probe=0177e96165) | Sep 28, 2023 |
| HP            | 3397                        | Desktop     | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Dell          | Latitude E6540              | Notebook    | [7d9885cd7c](https://linux-hardware.org/?probe=7d9885cd7c) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf71bcd90e](https://linux-hardware.org/?probe=bf71bcd90e) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4d2c8f9f07](https://linux-hardware.org/?probe=4d2c8f9f07) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| HP            | 1998                        | Desktop     | [4af6b915c2](https://linux-hardware.org/?probe=4af6b915c2) | Sep 17, 2023 |
| Dell          | Latitude E6540              | Notebook    | [ff29b23e60](https://linux-hardware.org/?probe=ff29b23e60) | Sep 13, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S4RV00    | Notebook    | [8ae7288bf3](https://linux-hardware.org/?probe=8ae7288bf3) | Sep 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | Notebook    | [5778731f85](https://linux-hardware.org/?probe=5778731f85) | Sep 10, 2023 |
| HP            | 8767 A                      | Desktop     | [ce91ccf3a9](https://linux-hardware.org/?probe=ce91ccf3a9) | Sep 09, 2023 |
| Dell          | Precision 5680              | Notebook    | [fdcb7ce5d4](https://linux-hardware.org/?probe=fdcb7ce5d4) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 20HES2RC00    | Notebook    | [390104a086](https://linux-hardware.org/?probe=390104a086) | Aug 28, 2023 |
| Dell          | Wyse 5470                   | Notebook    | [6d45205020](https://linux-hardware.org/?probe=6d45205020) | Aug 27, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [a9a56ae120](https://linux-hardware.org/?probe=a9a56ae120) | Aug 22, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [aed7eacff0](https://linux-hardware.org/?probe=aed7eacff0) | Aug 20, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9e03b48bf3](https://linux-hardware.org/?probe=9e03b48bf3) | Aug 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| AZW           | EQ                          | Desktop     | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | Notebook    | [c384115725](https://linux-hardware.org/?probe=c384115725) | Aug 05, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [13c8b276bb](https://linux-hardware.org/?probe=13c8b276bb) | Aug 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1abcf2ad6f](https://linux-hardware.org/?probe=1abcf2ad6f) | Aug 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| Teclast       | F5                          | Convertible | [76fcc31a43](https://linux-hardware.org/?probe=76fcc31a43) | Aug 01, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e452f85fb8](https://linux-hardware.org/?probe=e452f85fb8) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| System76      | Pangolin                    | Notebook    | [3b37a9bedb](https://linux-hardware.org/?probe=3b37a9bedb) | Jul 29, 2023 |
| Alienware     | 17                          | Notebook    | [25f67e59b8](https://linux-hardware.org/?probe=25f67e59b8) | Jul 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| HP            | 1998                        | Desktop     | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | Desktop     | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| AZW           | EQ                          | Desktop     | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8d48a50003](https://linux-hardware.org/?probe=8d48a50003) | Jul 22, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c29abaca55](https://linux-hardware.org/?probe=c29abaca55) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [59a0d6a7bb](https://linux-hardware.org/?probe=59a0d6a7bb) | Jul 19, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [1e8eeb8513](https://linux-hardware.org/?probe=1e8eeb8513) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [8efa3cf99d](https://linux-hardware.org/?probe=8efa3cf99d) | Jul 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [9bb1b8fbca](https://linux-hardware.org/?probe=9bb1b8fbca) | Jul 12, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d7afc91d12](https://linux-hardware.org/?probe=d7afc91d12) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4d377fc8b8](https://linux-hardware.org/?probe=4d377fc8b8) | Jul 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [fd56f44c38](https://linux-hardware.org/?probe=fd56f44c38) | Jun 29, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [4c4d870bdb](https://linux-hardware.org/?probe=4c4d870bdb) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [cf6a7757d5](https://linux-hardware.org/?probe=cf6a7757d5) | Jun 26, 2023 |
| Microtech     | CoreBook Lite               | Notebook    | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2812cf43d0](https://linux-hardware.org/?probe=2812cf43d0) | Jun 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| MECHREVO      | WUJIE 14                    | Notebook    | [a55e31b287](https://linux-hardware.org/?probe=a55e31b287) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | Notebook    | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85902981fd](https://linux-hardware.org/?probe=85902981fd) | Jun 11, 2023 |
| MACHENIKE     | F117-7P                     | Notebook    | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4396db2f33](https://linux-hardware.org/?probe=4396db2f33) | May 22, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [aefc60eaea](https://linux-hardware.org/?probe=aefc60eaea) | May 11, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [c40c2cb964](https://linux-hardware.org/?probe=c40c2cb964) | May 10, 2023 |
| Acer          | Spin SP514-51N              | Convertible | [6b23655b4b](https://linux-hardware.org/?probe=6b23655b4b) | May 10, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [6ee65c19d2](https://linux-hardware.org/?probe=6ee65c19d2) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [493bc0b894](https://linux-hardware.org/?probe=493bc0b894) | Apr 29, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| Dell          | 0KFKMF A00                  | All in one  | [cbae954ecc](https://linux-hardware.org/?probe=cbae954ecc) | Apr 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [7fd17e2245](https://linux-hardware.org/?probe=7fd17e2245) | Apr 22, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | Notebook    | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [6ce8b7fb26](https://linux-hardware.org/?probe=6ce8b7fb26) | Apr 11, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [f53ad14ea5](https://linux-hardware.org/?probe=f53ad14ea5) | Mar 13, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [3326423f04](https://linux-hardware.org/?probe=3326423f04) | Mar 06, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [8bf9dd7b83](https://linux-hardware.org/?probe=8bf9dd7b83) | Mar 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c4f08a9fc3](https://linux-hardware.org/?probe=c4f08a9fc3) | Mar 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c4d51ca1b8](https://linux-hardware.org/?probe=c4d51ca1b8) | Mar 04, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4f3c01941d](https://linux-hardware.org/?probe=4f3c01941d) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [616e689b13](https://linux-hardware.org/?probe=616e689b13) | Feb 19, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [5f59be48e1](https://linux-hardware.org/?probe=5f59be48e1) | Feb 16, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [68effccd60](https://linux-hardware.org/?probe=68effccd60) | Feb 16, 2023 |
| Teclast       | F5                          | Convertible | [e62bdaaa3b](https://linux-hardware.org/?probe=e62bdaaa3b) | Feb 13, 2023 |
| Teclast       | F5                          | Convertible | [30e30a5c3e](https://linux-hardware.org/?probe=30e30a5c3e) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8ac9c4b4ef](https://linux-hardware.org/?probe=8ac9c4b4ef) | Feb 09, 2023 |
| Acer          | Switch SW713-51GNP          | Tablet      | [46ecb88f1d](https://linux-hardware.org/?probe=46ecb88f1d) | Feb 08, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [75a3416ebc](https://linux-hardware.org/?probe=75a3416ebc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | Notebook    | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| Blackview     | AceBook 1                   | Notebook    | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [0e4ba05b0f](https://linux-hardware.org/?probe=0e4ba05b0f) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [226b8e5ff8](https://linux-hardware.org/?probe=226b8e5ff8) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b99e4815bc](https://linux-hardware.org/?probe=b99e4815bc) | Jan 10, 2023 |
| Dell          | Latitude 7420               | Notebook    | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | Notebook    | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b721a47fa4](https://linux-hardware.org/?probe=b721a47fa4) | Jan 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d5df950832](https://linux-hardware.org/?probe=d5df950832) | Jan 03, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6a53c626dd](https://linux-hardware.org/?probe=6a53c626dd) | Jan 02, 2023 |
| Dell          | Precision M4800             | Notebook    | [505f1b47dc](https://linux-hardware.org/?probe=505f1b47dc) | Dec 30, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| Dell          | Inspiron 7586               | Convertible | [d670af270f](https://linux-hardware.org/?probe=d670af270f) | Dec 28, 2022 |
| GPD           | WIN2                        | Notebook    | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf62b1c520](https://linux-hardware.org/?probe=cf62b1c520) | Dec 20, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ee5f96d645](https://linux-hardware.org/?probe=ee5f96d645) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3c18fca709](https://linux-hardware.org/?probe=3c18fca709) | Dec 09, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [3dfa1ba4b1](https://linux-hardware.org/?probe=3dfa1ba4b1) | Dec 09, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [110e3eab7f](https://linux-hardware.org/?probe=110e3eab7f) | Dec 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f698b715e4](https://linux-hardware.org/?probe=f698b715e4) | Nov 30, 2022 |
| Dell          | Inspiron 7586               | Convertible | [91dcb3265a](https://linux-hardware.org/?probe=91dcb3265a) | Nov 24, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [b79f103dd5](https://linux-hardware.org/?probe=b79f103dd5) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [44a3785f1f](https://linux-hardware.org/?probe=44a3785f1f) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | Notebook    | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [fce691523b](https://linux-hardware.org/?probe=fce691523b) | Oct 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | Notebook    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d79322ca4a](https://linux-hardware.org/?probe=d79322ca4a) | Oct 19, 2022 |
| Dell          | Precision 5760              | Notebook    | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa5ea0c17c](https://linux-hardware.org/?probe=aa5ea0c17c) | Oct 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ae775f1f89](https://linux-hardware.org/?probe=ae775f1f89) | Oct 13, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3a409e83a0](https://linux-hardware.org/?probe=3a409e83a0) | Oct 07, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [5eb1758869](https://linux-hardware.org/?probe=5eb1758869) | Oct 07, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8e301a5e4e](https://linux-hardware.org/?probe=8e301a5e4e) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3f823868fd](https://linux-hardware.org/?probe=3f823868fd) | Sep 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ad69daf392](https://linux-hardware.org/?probe=ad69daf392) | Sep 11, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [a02c8258ba](https://linux-hardware.org/?probe=a02c8258ba) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7986ddc1d9](https://linux-hardware.org/?probe=7986ddc1d9) | Sep 11, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | Notebook    | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | Notebook    | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | Notebook    | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | Notebook    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| Supermicro    | X8DT6                       | Server      | [0fd3b261c7](https://linux-hardware.org/?probe=0fd3b261c7) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| ASUSTek       | P8Q77-M                     | Desktop     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| GPD           | MicroPC                     | Notebook    | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | Notebook    | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | Notebook    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | Notebook    | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| Dell          | Latitude 7420               | Notebook    | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [e5dc04e6a5](https://linux-hardware.org/?probe=e5dc04e6a5) | Dec 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| Teclast       | F5                          | Convertible | [0854310843](https://linux-hardware.org/?probe=0854310843) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | Notebook    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [66d71367c1](https://linux-hardware.org/?probe=66d71367c1) | Aug 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bd919b4bd6](https://linux-hardware.org/?probe=bd919b4bd6) | Aug 22, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Inspiron 7391 2n1           | Convertible | [f632a64d73](https://linux-hardware.org/?probe=f632a64d73) | Jul 22, 2021 |
| Dell          | Latitude 7420               | Notebook    | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| ASUSTek       | Pro WS W480-ACE             | Desktop     | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| Lenovo        | ThinkPad T580 20L90024PB    | Notebook    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP            | 8055                        | Desktop     | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP            | 8055                        | Desktop     | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |
| Acer          | Aspire E5-576G              | Notebook    | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | Notebook    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/NixOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| NixOS 23.11                      | 115       | 25.05%  |
| NixOS 23.05                      | 107       | 23.31%  |
| NixOS 24.05                      | 92        | 20.04%  |
| NixOS 22.11                      | 55        | 11.98%  |
| NixOS 22.05                      | 37        | 8.06%   |
| NixOS 21.11                      | 18        | 3.92%   |
| NixOS                            | 5         | 1.09%   |
| NixOS 21.05pre-git               | 2         | 0.44%   |
| NixOS 20.09pre-git               | 2         | 0.44%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.22%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.22%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.22%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.22%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.22%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.22%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.22%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.22%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.22%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.22%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.22%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.22%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.22%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.22%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.22%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.22%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.22%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.22%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.22%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.22%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.22%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.22%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.22%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.22%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.22%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 419       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 6.1.69    | 13        | 2.62%   |
| 6.1.55    | 11        | 2.22%   |
| 6.6.8     | 9         | 1.81%   |
| 6.6.28    | 8         | 1.61%   |
| 6.1.61    | 7         | 1.41%   |
| 6.8.1     | 6         | 1.21%   |
| 6.7.6     | 6         | 1.21%   |
| 6.6.0     | 6         | 1.21%   |
| 6.1.82    | 6         | 1.21%   |
| 6.1.72    | 6         | 1.21%   |
| 6.1.68    | 6         | 1.21%   |
| 6.1.64    | 6         | 1.21%   |
| 6.5.5     | 5         | 1.01%   |
| 6.1.60    | 5         | 1.01%   |
| 6.1.51    | 5         | 1.01%   |
| 6.1.31    | 5         | 1.01%   |
| 5.15.74   | 5         | 1.01%   |
| 6.7.0     | 4         | 0.81%   |
| 6.6.3     | 4         | 0.81%   |
| 6.6.26    | 4         | 0.81%   |
| 6.6.22    | 4         | 0.81%   |
| 6.4.0     | 4         | 0.81%   |
| 6.3.8     | 4         | 0.81%   |
| 6.3.3     | 4         | 0.81%   |
| 6.1.53    | 4         | 0.81%   |
| 6.1.38    | 4         | 0.81%   |
| 5.15.86   | 4         | 0.81%   |
| 5.15.43   | 4         | 0.81%   |
| 6.8.6     | 3         | 0.6%    |
| 6.7.9     | 3         | 0.6%    |
| 6.7.7     | 3         | 0.6%    |
| 6.6.23    | 3         | 0.6%    |
| 6.6.18    | 3         | 0.6%    |
| 6.5.7     | 3         | 0.6%    |
| 6.3.1     | 3         | 0.6%    |
| 6.2.0-rc6 | 3         | 0.6%    |
| 6.1.79    | 3         | 0.6%    |
| 6.1.74    | 3         | 0.6%    |
| 6.1.71    | 3         | 0.6%    |
| 6.1.67    | 3         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.69  | 13        | 2.62%   |
| 6.1.55  | 12        | 2.42%   |
| 6.6.8   | 10        | 2.02%   |
| 6.7.6   | 8         | 1.61%   |
| 6.6.28  | 8         | 1.61%   |
| 6.8.1   | 7         | 1.41%   |
| 6.7.0   | 7         | 1.41%   |
| 6.1.61  | 7         | 1.41%   |
| 6.6.0   | 6         | 1.21%   |
| 6.4.0   | 6         | 1.21%   |
| 6.1.82  | 6         | 1.21%   |
| 6.1.72  | 6         | 1.21%   |
| 6.1.68  | 6         | 1.21%   |
| 6.1.64  | 6         | 1.21%   |
| 6.1.31  | 6         | 1.21%   |
| 6.8.6   | 5         | 1.01%   |
| 6.5.7   | 5         | 1.01%   |
| 6.5.5   | 5         | 1.01%   |
| 6.1.60  | 5         | 1.01%   |
| 6.1.51  | 5         | 1.01%   |
| 5.15.74 | 5         | 1.01%   |
| 6.8.0   | 4         | 0.81%   |
| 6.7.7   | 4         | 0.81%   |
| 6.6.3   | 4         | 0.81%   |
| 6.6.26  | 4         | 0.81%   |
| 6.6.22  | 4         | 0.81%   |
| 6.5.11  | 4         | 0.81%   |
| 6.3.8   | 4         | 0.81%   |
| 6.3.3   | 4         | 0.81%   |
| 6.2.0   | 4         | 0.81%   |
| 6.1.53  | 4         | 0.81%   |
| 6.1.38  | 4         | 0.81%   |
| 6.1.0   | 4         | 0.81%   |
| 6.0.10  | 4         | 0.81%   |
| 5.15.86 | 4         | 0.81%   |
| 5.15.43 | 4         | 0.81%   |
| 6.7.9   | 3         | 0.6%    |
| 6.7.5   | 3         | 0.6%    |
| 6.6.23  | 3         | 0.6%    |
| 6.6.18  | 3         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 146       | 31.33%  |
| 5.15    | 63        | 13.52%  |
| 6.6     | 61        | 13.09%  |
| 6.7     | 32        | 6.87%   |
| 6.5     | 22        | 4.72%   |
| 6.8     | 19        | 4.08%   |
| 6.4     | 17        | 3.65%   |
| 5.10    | 14        | 3%      |
| 6.3     | 13        | 2.79%   |
| 6.2     | 13        | 2.79%   |
| 6.0     | 13        | 2.79%   |
| 5.16    | 8         | 1.72%   |
| 5.4     | 7         | 1.5%    |
| 5.19    | 7         | 1.5%    |
| 5.8     | 6         | 1.29%   |
| 5.18    | 5         | 1.07%   |
| 5.13    | 4         | 0.86%   |
| 5.7     | 3         | 0.64%   |
| 5.17    | 3         | 0.64%   |
| 5.12    | 3         | 0.64%   |
| 5.14    | 2         | 0.43%   |
| 5.11    | 2         | 0.43%   |
| 4.19    | 2         | 0.43%   |
| Unknown | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 409       | 97.61%  |
| aarch64 | 9         | 2.15%   |
| i686    | 1         | 0.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 129       | 29.45%  |
| GNOME         | 78        | 17.81%  |
| KDE5          | 58        | 13.24%  |
| Hyprland      | 45        | 10.27%  |
| sway          | 41        | 9.36%   |
| KDE           | 20        | 4.57%   |
| none+i3       | 15        | 3.42%   |
| XFCE          | 13        | 2.97%   |
| KDE6          | 11        | 2.51%   |
| none+awesome  | 4         | 0.91%   |
| X-Generic     | 3         | 0.68%   |
| X-Cinnamon    | 3         | 0.68%   |
| none+xmonad   | 3         | 0.68%   |
| MATE          | 3         | 0.68%   |
| xsession      | 2         | 0.46%   |
| Pantheon      | 2         | 0.46%   |
| Budgie        | 2         | 0.46%   |
| plasmawayland | 1         | 0.23%   |
| plasma        | 1         | 0.23%   |
| none+dwm      | 1         | 0.23%   |
| none+bspwm    | 1         | 0.23%   |
| LXQt          | 1         | 0.23%   |
| HM-awesome    | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 169       | 38.5%   |
| Unknown | 142       | 32.35%  |
| X11     | 93        | 21.18%  |
| Tty     | 35        | 7.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 171       | 40.05%  |
| SDDM    | 99        | 23.19%  |
| GDM     | 91        | 21.31%  |
| LightDM | 62        | 14.52%  |
| GREETD  | 4         | 0.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 269       | 63.29%  |
| Unknown    | 65        | 15.29%  |
| en_GB      | 27        | 6.35%   |
| en_AU      | 11        | 2.59%   |
| de_DE      | 9         | 2.12%   |
| ru_RU      | 7         | 1.65%   |
| en_DK      | 5         | 1.18%   |
| en_CA      | 5         | 1.18%   |
| fr_FR      | 4         | 0.94%   |
| pt_PT      | 3         | 0.71%   |
| pt_BR      | 3         | 0.71%   |
| it_IT      | 2         | 0.47%   |
| de_CH      | 2         | 0.47%   |
| C          | 2         | 0.47%   |
| sv_SE      | 1         | 0.24%   |
| ro_RO      | 1         | 0.24%   |
| pl_PL      | 1         | 0.24%   |
| lv_LV      | 1         | 0.24%   |
| lt_LT      | 1         | 0.24%   |
| es_MX      | 1         | 0.24%   |
| en_SG      | 1         | 0.24%   |
| en_NZ      | 1         | 0.24%   |
| en_IN      | 1         | 0.24%   |
| en_IE.UTF8 | 1         | 0.24%   |
| en_IE      | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 378       | 89.79%  |
| BIOS | 43        | 10.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 237       | 55.5%   |
| Btrfs    | 87        | 20.37%  |
| Zfs      | 37        | 8.67%   |
| Tmpfs    | 33        | 7.73%   |
| Xfs      | 20        | 4.68%   |
| Unknown  | 6         | 1.41%   |
| F2fs     | 3         | 0.7%    |
| Bcachefs | 3         | 0.7%    |
| Ext2     | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 397       | 94.08%  |
| MBR     | 17        | 4.03%   |
| Unknown | 8         | 1.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 343       | 80.33%  |
| Yes       | 84        | 19.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 305       | 72.1%   |
| Yes       | 118       | 27.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 86        | 20.53%  |
| ASUSTek Computer                     | 86        | 20.53%  |
| Dell                                 | 41        | 9.79%   |
| Hewlett-Packard                      | 34        | 8.11%   |
| MSI                                  | 31        | 7.4%    |
| Gigabyte Technology                  | 27        | 6.44%   |
| Apple                                | 21        | 5.01%   |
| Acer                                 | 13        | 3.1%    |
| ASRock                               | 12        | 2.86%   |
| Framework                            | 7         | 1.67%   |
| Intel                                | 4         | 0.95%   |
| Unknown                              | 4         | 0.95%   |
| Timi                                 | 3         | 0.72%   |
| System76                             | 3         | 0.72%   |
| Raspberry Pi Foundation              | 3         | 0.72%   |
| Pine Microsystems                    | 3         | 0.72%   |
| GPD                                  | 3         | 0.72%   |
| Supermicro                           | 2         | 0.48%   |
| Razer                                | 2         | 0.48%   |
| Microsoft                            | 2         | 0.48%   |
| MECHREVO                             | 2         | 0.48%   |
| HUAWEI                               | 2         | 0.48%   |
| Xunlong                              | 1         | 0.24%   |
| Win element                          | 1         | 0.24%   |
| Toshiba                              | 1         | 0.24%   |
| Teclast                              | 1         | 0.24%   |
| Sony                                 | 1         | 0.24%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.24%   |
| Samsung Electronics                  | 1         | 0.24%   |
| retsamarret                          | 1         | 0.24%   |
| OBSIDIAN-PC                          | 1         | 0.24%   |
| Nvidia                               | 1         | 0.24%   |
| Microtech                            | 1         | 0.24%   |
| Medion                               | 1         | 0.24%   |
| MACHENIKE                            | 1         | 0.24%   |
| LattePanda                           | 1         | 0.24%   |
| Jetway                               | 1         | 0.24%   |
| HONOR                                | 1         | 0.24%   |
| Hardkernel                           | 1         | 0.24%   |
| Google                               | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Apple MacBookPro11,5                                 | 5         | 1.19%   |
| Apple MacBookPro11,3                                 | 4         | 0.95%   |
| Unknown                                              | 4         | 0.95%   |
| Pine Microsystems Pine64 PinePhone (1.2)             | 3         | 0.72%   |
| MSI MS-7C37                                          | 3         | 0.72%   |
| MSI MS-7B86                                          | 3         | 0.72%   |
| Lenovo 13w Yoga 82S1                                 | 3         | 0.72%   |
| Framework Laptop (12th Gen Intel Core)               | 3         | 0.72%   |
| Framework Laptop                                     | 3         | 0.72%   |
| ASUS TUF Gaming X570-PLUS                            | 3         | 0.72%   |
| ASUS All Series                                      | 3         | 0.72%   |
| Apple iMac17,1                                       | 3         | 0.72%   |
| MSI MS-7C56                                          | 2         | 0.48%   |
| Lenovo ThinkPad T480 20L5CTO1WW                      | 2         | 0.48%   |
| Lenovo Legion R9000P ARX8 82WM                       | 2         | 0.48%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS                    | 2         | 0.48%   |
| HP ZBook Firefly 14 inch G10 A Mobile Workstation PC | 2         | 0.48%   |
| HP EliteBook 8470p                                   | 2         | 0.48%   |
| Gigabyte B550I AORUS PRO AX                          | 2         | 0.48%   |
| Gigabyte B450M DS3H                                  | 2         | 0.48%   |
| Dell XPS 15 9530                                     | 2         | 0.48%   |
| Dell Latitude 7420                                   | 2         | 0.48%   |
| Dell Inspiron 7506 2n1                               | 2         | 0.48%   |
| ASUS Zenbook UX3402ZA_UX3402ZA                       | 2         | 0.48%   |
| ASUS Zenbook UN5401RA UN5401RA_UN5401RA              | 2         | 0.48%   |
| ASUS Vivobook Go E1404FA_E1404FA                     | 2         | 0.48%   |
| ASUS SABERTOOTH 990FX R2.0                           | 2         | 0.48%   |
| ASUS ROG STRIX B550-I GAMING                         | 2         | 0.48%   |
| ASUS ROG STRIX B550-F GAMING                         | 2         | 0.48%   |
| ASUS PRIME X370-PRO                                  | 2         | 0.48%   |
| ASRock Z87 Extreme4                                  | 2         | 0.48%   |
| Xunlong Orange Pi 3B                                 | 1         | 0.24%   |
| Win element M600                                     | 1         | 0.24%   |
| Toshiba Satellite L50-B                              | 1         | 0.24%   |
| Timi Xiaomi Book Pro 16 2022                         | 1         | 0.24%   |
| Timi Redmi Book Pro 15 2022                          | 1         | 0.24%   |
| Timi Redmi Book Pro 14 2022                          | 1         | 0.24%   |
| Teclast F5                                           | 1         | 0.24%   |
| System76 Serval WS                                   | 1         | 0.24%   |
| System76 Pangolin                                    | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 48        | 11.46%  |
| ASUS ROG                 | 26        | 6.21%   |
| Dell XPS                 | 13        | 3.1%    |
| ASUS PRIME               | 12        | 2.86%   |
| Apple MacBookPro11       | 11        | 2.63%   |
| Lenovo Legion            | 10        | 2.39%   |
| HP EliteBook             | 9         | 2.15%   |
| Dell Latitude            | 9         | 2.15%   |
| Dell Inspiron            | 9         | 2.15%   |
| ASUS ZenBook             | 9         | 2.15%   |
| ASUS TUF                 | 9         | 2.15%   |
| Lenovo IdeaPad           | 7         | 1.67%   |
| Framework Laptop         | 7         | 1.67%   |
| Lenovo Yoga              | 6         | 1.43%   |
| ASUS VivoBook            | 6         | 1.43%   |
| Acer Aspire              | 6         | 1.43%   |
| HP ProBook               | 5         | 1.19%   |
| HP Pavilion              | 5         | 1.19%   |
| Lenovo ThinkBook         | 4         | 0.95%   |
| HP ZBook                 | 4         | 0.95%   |
| Gigabyte X570            | 4         | 0.95%   |
| Dell Precision           | 4         | 0.95%   |
| Unknown                  | 4         | 0.95%   |
| RPi Raspberry            | 3         | 0.72%   |
| Pine Microsystems Pine64 | 3         | 0.72%   |
| MSI MS-7C37              | 3         | 0.72%   |
| MSI MS-7B86              | 3         | 0.72%   |
| Lenovo IdeaPadFlex       | 3         | 0.72%   |
| Lenovo 13w               | 3         | 0.72%   |
| HP EliteDesk             | 3         | 0.72%   |
| Gigabyte Z790            | 3         | 0.72%   |
| Gigabyte Z390            | 3         | 0.72%   |
| Gigabyte B450M           | 3         | 0.72%   |
| Dell PowerEdge           | 3         | 0.72%   |
| ASUS ProArt              | 3         | 0.72%   |
| ASUS Pro                 | 3         | 0.72%   |
| ASUS All                 | 3         | 0.72%   |
| Apple iMac17             | 3         | 0.72%   |
| Timi Redmi               | 2         | 0.48%   |
| Razer Blade              | 2         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 55        | 13.13%  |
| 2022    | 52        | 12.41%  |
| 2023    | 48        | 11.46%  |
| 2019    | 46        | 10.98%  |
| 2021    | 43        | 10.26%  |
| 2018    | 43        | 10.26%  |
| 2016    | 20        | 4.77%   |
| 2017    | 19        | 4.53%   |
| 2014    | 18        | 4.3%    |
| 2013    | 17        | 4.06%   |
| 2012    | 17        | 4.06%   |
| 2015    | 14        | 3.34%   |
| Unknown | 9         | 2.15%   |
| 2011    | 7         | 1.67%   |
| 2008    | 6         | 1.43%   |
| 2010    | 2         | 0.48%   |
| 2009    | 1         | 0.24%   |
| 2007    | 1         | 0.24%   |
| 2000    | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 221       | 52.74%  |
| Desktop        | 140       | 33.41%  |
| Convertible    | 31        | 7.4%    |
| System on chip | 5         | 1.19%   |
| Tablet         | 5         | 1.19%   |
| All in one     | 5         | 1.19%   |
| Server         | 5         | 1.19%   |
| Mini pc        | 4         | 0.95%   |
| Phone          | 3         | 0.72%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 409       | 96.69%  |
| Enabled  | 14        | 3.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 415       | 99.05%  |
| Yes  | 4         | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 104       | 24.53%  |
| 32.01-64.0      | 97        | 22.88%  |
| 8.01-16.0       | 72        | 16.98%  |
| 64.01-256.0     | 55        | 12.97%  |
| 4.01-8.0        | 51        | 12.03%  |
| 24.01-32.0      | 23        | 5.42%   |
| 3.01-4.0        | 16        | 3.77%   |
| More than 256.0 | 2         | 0.47%   |
| 0.51-1.0        | 2         | 0.47%   |
| 2.01-3.0        | 1         | 0.24%   |
| 1.01-2.0        | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 123       | 26.57%  |
| 2.01-3.0    | 85        | 18.36%  |
| 3.01-4.0    | 72        | 15.55%  |
| 8.01-16.0   | 68        | 14.69%  |
| 1.01-2.0    | 51        | 11.02%  |
| 16.01-24.0  | 22        | 4.75%   |
| 0.51-1.0    | 13        | 2.81%   |
| 32.01-64.0  | 12        | 2.59%   |
| 24.01-32.0  | 9         | 1.94%   |
| 0.01-0.5    | 6         | 1.3%    |
| 64.01-256.0 | 2         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 252       | 58.6%   |
| 2      | 105       | 24.42%  |
| 3      | 36        | 8.37%   |
| 5      | 11        | 2.56%   |
| 4      | 11        | 2.56%   |
| 6      | 5         | 1.16%   |
| 8      | 3         | 0.7%    |
| 7      | 2         | 0.47%   |
| 23     | 1         | 0.23%   |
| 17     | 1         | 0.23%   |
| 11     | 1         | 0.23%   |
| 9      | 1         | 0.23%   |
| 0      | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 375       | 89.29%  |
| Yes       | 45        | 10.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 311       | 73.7%   |
| No        | 111       | 26.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 336       | 79.43%  |
| No        | 87        | 20.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 328       | 77.54%  |
| No        | 95        | 22.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 97        | 23.15%  |
| Germany         | 44        | 10.5%   |
| Russia          | 27        | 6.44%   |
| UK              | 23        | 5.49%   |
| Italy           | 20        | 4.77%   |
| France          | 15        | 3.58%   |
| Canada          | 14        | 3.34%   |
| Poland          | 13        | 3.1%    |
| Netherlands     | 13        | 3.1%    |
| Australia       | 11        | 2.63%   |
| Brazil          | 10        | 2.39%   |
| Czechia         | 9         | 2.15%   |
| Sweden          | 8         | 1.91%   |
| Austria         | 8         | 1.91%   |
| Ukraine         | 7         | 1.67%   |
| Portugal        | 7         | 1.67%   |
| Switzerland     | 6         | 1.43%   |
| Romania         | 5         | 1.19%   |
| Japan           | 5         | 1.19%   |
| Belgium         | 5         | 1.19%   |
| Norway          | 4         | 0.95%   |
| India           | 4         | 0.95%   |
| China           | 4         | 0.95%   |
| Taiwan          | 3         | 0.72%   |
| Singapore       | 3         | 0.72%   |
| Mexico          | 3         | 0.72%   |
| Denmark         | 3         | 0.72%   |
| The Netherlands | 2         | 0.48%   |
| Thailand        | 2         | 0.48%   |
| Spain           | 2         | 0.48%   |
| South Africa    | 2         | 0.48%   |
| Slovenia        | 2         | 0.48%   |
| Serbia          | 2         | 0.48%   |
| Qatar           | 2         | 0.48%   |
| New Zealand     | 2         | 0.48%   |
| Iraq            | 2         | 0.48%   |
| Hungary         | 2         | 0.48%   |
| Hong Kong       | 2         | 0.48%   |
| Finland         | 2         | 0.48%   |
| Bulgaria        | 2         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Amsterdam         | 9         | 2.05%   |
| Vienna            | 7         | 1.59%   |
| Hamburg           | 6         | 1.36%   |
| Prague            | 5         | 1.14%   |
| Perth             | 5         | 1.14%   |
| Milwaukee         | 5         | 1.14%   |
| Kharkiv           | 5         | 1.14%   |
| Rochester         | 4         | 0.91%   |
| Moscow            | 4         | 0.91%   |
| Marki             | 4         | 0.91%   |
| Los Angeles       | 4         | 0.91%   |
| Frankfurt am Main | 4         | 0.91%   |
| Craigsville       | 4         | 0.91%   |
| Chelyabinsk       | 4         | 0.91%   |
| Warsaw            | 3         | 0.68%   |
| St Petersburg     | 3         | 0.68%   |
| Singapore         | 3         | 0.68%   |
| Salt Lake City    | 3         | 0.68%   |
| Richmond          | 3         | 0.68%   |
| Porto             | 3         | 0.68%   |
| Plymouth          | 3         | 0.68%   |
| Oslo              | 3         | 0.68%   |
| Melbourne         | 3         | 0.68%   |
| Lyon              | 3         | 0.68%   |
| London            | 3         | 0.68%   |
| Chicago           | 3         | 0.68%   |
| Cerami            | 3         | 0.68%   |
| Austin            | 3         | 0.68%   |
| Athens            | 3         | 0.68%   |
| Yoshkar-Ola       | 2         | 0.45%   |
| Wenden            | 2         | 0.45%   |
| Taipei            | 2         | 0.45%   |
| Sydney            | 2         | 0.45%   |
| Stockholm         | 2         | 0.45%   |
| Southampton       | 2         | 0.45%   |
| South Deerfield   | 2         | 0.45%   |
| Sorocaba          | 2         | 0.45%   |
| Sofia             | 2         | 0.45%   |
| Sibiu             | 2         | 0.45%   |
| Schaafheim        | 2         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 157       | 259    | 25.28%  |
| Sandisk                     | 56        | 69     | 9.02%   |
| WDC                         | 51        | 89     | 8.21%   |
| Seagate                     | 49        | 99     | 7.89%   |
| Toshiba                     | 28        | 45     | 4.51%   |
| Crucial                     | 25        | 32     | 4.03%   |
| SK hynix                    | 23        | 29     | 3.7%    |
| Intel                       | 23        | 30     | 3.7%    |
| Micron Technology           | 22        | 23     | 3.54%   |
| Unknown                     | 21        | 26     | 3.38%   |
| Kingston                    | 21        | 28     | 3.38%   |
| Apple                       | 17        | 24     | 2.74%   |
| KIOXIA                      | 11        | 13     | 1.77%   |
| Phison Electronics          | 10        | 15     | 1.61%   |
| HGST                        | 10        | 22     | 1.61%   |
| Micron/Crucial Technology   | 8         | 8      | 1.29%   |
| Kingston Technology Company | 8         | 12     | 1.29%   |
| MAXIO Technology (Hangzhou) | 6         | 8      | 0.97%   |
| Realtek Semiconductor       | 5         | 15     | 0.81%   |
| A-DATA Technology           | 5         | 6      | 0.81%   |
| Yangtze Memory Technologies | 3         | 4      | 0.48%   |
| Union Memory (Shenzhen)     | 3         | 4      | 0.48%   |
| Silicon Motion              | 3         | 3      | 0.48%   |
| PNY                         | 3         | 5      | 0.48%   |
| Hitachi                     | 3         | 6      | 0.48%   |
| Corsair                     | 3         | 3      | 0.48%   |
| Unknown                     | 3         | 3      | 0.48%   |
| Transcend                   | 2         | 2      | 0.32%   |
| SPCC                        | 2         | 2      | 0.32%   |
| Realtek                     | 2         | 2      | 0.32%   |
| Plextor                     | 2         | 2      | 0.32%   |
| Patriot                     | 2         | 3      | 0.32%   |
| OCZ                         | 2         | 2      | 0.32%   |
| LITEONIT                    | 2         | 2      | 0.32%   |
| Lite-On Technology          | 2         | 3      | 0.32%   |
| Lexar                       | 2         | 2      | 0.32%   |
| Intenso                     | 2         | 2      | 0.32%   |
| China                       | 2         | 2      | 0.32%   |
| BIWIN                       | 2         | 2      | 0.32%   |
| ADATA Technology            | 2         | 4      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 33        | 4.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 26        | 3.7%    |
| Samsung SSD 860 EVO 500GB                           | 8         | 1.14%   |
| Samsung SSD 860 EVO 1TB                             | 8         | 1.14%   |
| Unknown MMC Card  32GB                              | 7         | 1%      |
| Toshiba XG6 NVMe SSD Controller 1024GB              | 5         | 0.71%   |
| Sandisk WD_BLACK SN770 1TB                          | 5         | 0.71%   |
| Samsung SSD 990 PRO 1TB                             | 5         | 0.71%   |
| Samsung SSD 860 QVO 1TB                             | 5         | 0.71%   |
| Samsung SSD 850 EVO 500GB                           | 5         | 0.71%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 5         | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB  | 5         | 0.71%   |
| Intel SSDPEKNU512GZ 512GB                           | 5         | 0.71%   |
| Intel SSDPEKNU010TZ 1024GB                          | 5         | 0.71%   |
| Unknown MMC Card  64GB                              | 4         | 0.57%   |
| Unknown MMC Card  128GB                             | 4         | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB                      | 4         | 0.57%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                  | 4         | 0.57%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 4         | 0.57%   |
| SanDisk SSD PLUS 240GB                              | 4         | 0.57%   |
| Samsung SSD 990 PRO 2TB                             | 4         | 0.57%   |
| Samsung SSD 850 EVO 250GB                           | 4         | 0.57%   |
| KIOXIA KBG50ZNV512G 512GB                           | 4         | 0.57%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 0.57%   |
| Crucial CT1000MX500SSD1 1TB                         | 4         | 0.57%   |
| Apple SSD SM0512G 500GB                             | 4         | 0.57%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3         | 0.43%   |
| Seagate ST3000DM001-1CH166 3TB                      | 3         | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.43%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 3         | 0.43%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 1TB | 3         | 0.43%   |
| Samsung SSD 980 1TB                                 | 3         | 0.43%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.43%   |
| Samsung SSD 970 EVO 500GB                           | 3         | 0.43%   |
| Samsung SSD 870 EVO 500GB                           | 3         | 0.43%   |
| Samsung SSD 870 EVO 2TB                             | 3         | 0.43%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.43%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 3         | 0.43%   |
| Micron MTFDKCD512TFK 512GB                          | 3         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 99     | 39.2%   |
| WDC                 | 42        | 76     | 33.6%   |
| Toshiba             | 16        | 30     | 12.8%   |
| HGST                | 10        | 22     | 8%      |
| Hitachi             | 3         | 6      | 2.4%    |
| Apple               | 3         | 3      | 2.4%    |
| Samsung Electronics | 2         | 2      | 1.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 105    | 32.28%  |
| Crucial             | 24        | 31     | 12.7%   |
| SanDisk             | 15        | 20     | 7.94%   |
| Kingston            | 15        | 18     | 7.94%   |
| Apple               | 14        | 17     | 7.41%   |
| Intel               | 6         | 8      | 3.17%   |
| WDC                 | 5         | 7      | 2.65%   |
| SK hynix            | 4         | 4      | 2.12%   |
| PNY                 | 3         | 5      | 1.59%   |
| Micron Technology   | 3         | 3      | 1.59%   |
| Corsair             | 3         | 3      | 1.59%   |
| Transcend           | 2         | 2      | 1.06%   |
| Toshiba             | 2         | 2      | 1.06%   |
| SPCC                | 2         | 2      | 1.06%   |
| Patriot             | 2         | 3      | 1.06%   |
| OCZ                 | 2         | 2      | 1.06%   |
| LITEONIT            | 2         | 2      | 1.06%   |
| Intenso             | 2         | 2      | 1.06%   |
| China               | 2         | 2      | 1.06%   |
| BIWIN               | 2         | 2      | 1.06%   |
| A-DATA Technology   | 2         | 2      | 1.06%   |
| Unknown             | 2         | 2      | 1.06%   |
| ZHITAI              | 1         | 1      | 0.53%   |
| Teclast             | 1         | 3      | 0.53%   |
| Team                | 1         | 1      | 0.53%   |
| S3+                 | 1         | 1      | 0.53%   |
| Plextor             | 1         | 1      | 0.53%   |
| Netac               | 1         | 1      | 0.53%   |
| Neo Forza           | 1         | 1      | 0.53%   |
| LITEON              | 1         | 1      | 0.53%   |
| Lexar               | 1         | 1      | 0.53%   |
| KingFast            | 1         | 1      | 0.53%   |
| INNOVATION IT       | 1         | 1      | 0.53%   |
| Dogfish             | 1         | 1      | 0.53%   |
| ASMT                | 1         | 1      | 0.53%   |
| ASMedia             | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 284       | 406    | 50.18%  |
| SSD     | 164       | 260    | 28.98%  |
| HDD     | 97        | 238    | 17.14%  |
| MMC     | 20        | 26     | 3.53%   |
| Unknown | 1         | 1      | 0.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 284       | 404    | 54.83%  |
| SATA | 198       | 480    | 38.22%  |
| MMC  | 20        | 26     | 3.86%   |
| SAS  | 16        | 21     | 3.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 133       | 203    | 45.86%  |
| 0.51-1.0   | 89        | 130    | 30.69%  |
| 1.01-2.0   | 25        | 35     | 8.62%   |
| 4.01-10.0  | 16        | 61     | 5.52%   |
| 2.01-3.0   | 12        | 22     | 4.14%   |
| 3.01-4.0   | 9         | 25     | 3.1%    |
| 10.01-20.0 | 6         | 22     | 2.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 98        | 22.69%  |
| Unknown        | 75        | 17.36%  |
| 251-500        | 63        | 14.58%  |
| 501-1000       | 52        | 12.04%  |
| 1001-2000      | 44        | 10.19%  |
| 101-250        | 42        | 9.72%   |
| More than 3000 | 36        | 8.33%   |
| 2001-3000      | 17        | 3.94%   |
| 51-100         | 3         | 0.69%   |
| 21-50          | 2         | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 134       | 30.18%  |
| Unknown        | 75        | 16.89%  |
| 101-250        | 56        | 12.61%  |
| 21-50          | 44        | 9.91%   |
| 51-100         | 32        | 7.21%   |
| 251-500        | 30        | 6.76%   |
| 501-1000       | 29        | 6.53%   |
| 1001-2000      | 19        | 4.28%   |
| More than 3000 | 16        | 3.6%    |
| 2001-3000      | 9         | 2.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Computers | Drives | Percent |
|----------------------------------------------------------------|-----------|--------|---------|
| SanDisk SSD PLUS 240GB                                         | 2         | 4      | 4.26%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 2      | 4.26%   |
| WDC WD5000AAKS-00V1A0 500GB                                    | 1         | 1      | 2.13%   |
| WDC WD30EZRX-00SPEB0 3TB                                       | 1         | 1      | 2.13%   |
| WDC WD30EFRX-68AX9N0 3TB                                       | 1         | 5      | 2.13%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                       | 1         | 1      | 2.13%   |
| WDC WD20EARX-008FB0 2TB                                        | 1         | 1      | 2.13%   |
| WDC WD20EARS-22MVWB0 2TB                                       | 1         | 1      | 2.13%   |
| WDC WD1600JS-00NCB1 160GB                                      | 1         | 1      | 2.13%   |
| WDC WD10JPVX-08JC3T5 1TB                                       | 1         | 1      | 2.13%   |
| WDC WD10EZEX-60ZF5A0 1TB                                       | 1         | 1      | 2.13%   |
| WDC WD1001FALS-403AA0 1TB                                      | 1         | 2      | 2.13%   |
| WDC WD10 JPLX-00MBPT0 1TB                                      | 1         | 1      | 2.13%   |
| Union Memory UMIS RPITJ512PED2OWX 512GB                        | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD100 1TB                                         | 1         | 1      | 2.13%   |
| Toshiba MK2565GSXV 250GB                                       | 1         | 1      | 2.13%   |
| Toshiba HDWQ140 4TB                                            | 1         | 1      | 2.13%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                           | 1         | 1      | 2.13%   |
| SK hynix HFS250G32TND-N1A2A 250GB SSD                          | 1         | 1      | 2.13%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                          | 1         | 1      | 2.13%   |
| Seagate ST8000VN004-2M2101 8TB                                 | 1         | 3      | 2.13%   |
| Seagate ST8000VN0022-2EL112 8TB                                | 1         | 1      | 2.13%   |
| Seagate ST500LX005-1CW162 500GB                                | 1         | 1      | 2.13%   |
| Seagate ST500LT012-9WS142 500GB                                | 1         | 1      | 2.13%   |
| Seagate ST3500418AS 500GB                                      | 1         | 1      | 2.13%   |
| Seagate ST2000LM015-2E8174 2TB                                 | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 970 EVO 1TB                            | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 870 EVO 2TB                            | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 870 EVO 1TB                            | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 850 EVO 1TB                            | 1         | 1      | 2.13%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1         | 1      | 2.13%   |
| Micron Technology C400 RealSSD 2.5 7mm 512GB                   | 1         | 1      | 2.13%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD                 | 1         | 1      | 2.13%   |
| Intenso SSD 250GB                                              | 1         | 1      | 2.13%   |
| Intel SSDSC2BW240A4 240GB                                      | 1         | 1      | 2.13%   |
| Intel SSDSA2M080G2GC 80GB                                      | 1         | 1      | 2.13%   |
| Hitachi HDS722020ALA330 2TB                                    | 1         | 1      | 2.13%   |
| HGST HUS728T8TALE6L4 8TB                                       | 1         | 1      | 2.13%   |
| HGST HTS545050A7E680 500GB                                     | 1         | 1      | 2.13%   |
| Crucial CT240M500SSD1 240GB                                    | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 16     | 23.4%   |
| Samsung Electronics | 7         | 7      | 14.89%  |
| Seagate             | 6         | 8      | 12.77%  |
| Toshiba             | 3         | 3      | 6.38%   |
| SK hynix            | 3         | 3      | 6.38%   |
| SanDisk             | 2         | 4      | 4.26%   |
| Micron Technology   | 2         | 2      | 4.26%   |
| Intel               | 2         | 2      | 4.26%   |
| HGST                | 2         | 2      | 4.26%   |
| Crucial             | 2         | 2      | 4.26%   |
| Corsair             | 2         | 2      | 4.26%   |
| Union Memory        | 1         | 1      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| Hitachi             | 1         | 1      | 2.13%   |
| ASMT                | 1         | 1      | 2.13%   |
| A-DATA Technology   | 1         | 2      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 16     | 47.83%  |
| Seagate | 6         | 8      | 26.09%  |
| Toshiba | 3         | 3      | 13.04%  |
| HGST    | 2         | 2      | 8.7%    |
| Hitachi | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 30     | 47.83%  |
| SSD  | 17        | 19     | 36.96%  |
| NVMe | 7         | 8      | 15.22%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MG03ACA300 3TB                           | 1         | 1      | 25%     |
| Toshiba HDWG180 8TB                              | 1         | 4      | 25%     |
| SK hynix BC501 NVMe Solid State Drive 512GB      | 1         | 1      | 25%     |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 5      | 50%     |
| SK hynix            | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 392       | 801    | 82.01%  |
| Detected | 42        | 66     | 8.79%   |
| Malfunc  | 40        | 57     | 8.37%   |
| Failed   | 4         | 7      | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 191       | 31.57%  |
| Samsung Electronics                     | 121       | 20%     |
| AMD                                     | 87        | 14.38%  |
| SanDisk                                 | 47        | 7.77%   |
| SK hynix                                | 19        | 3.14%   |
| Micron Technology                       | 19        | 3.14%   |
| ASMedia Technology                      | 17        | 2.81%   |
| Kingston Technology Company             | 15        | 2.48%   |
| Toshiba America Info Systems            | 11        | 1.82%   |
| Phison Electronics                      | 11        | 1.82%   |
| KIOXIA                                  | 11        | 1.82%   |
| Micron/Crucial Technology               | 9         | 1.49%   |
| MAXIO Technology (Hangzhou)             | 6         | 0.99%   |
| Realtek Semiconductor                   | 5         | 0.83%   |
| ADATA Technology                        | 5         | 0.83%   |
| LSI Logic / Symbios Logic               | 4         | 0.66%   |
| Broadcom / LSI                          | 4         | 0.66%   |
| Yangtze Memory Technologies             | 3         | 0.5%    |
| Union Memory (Shenzhen)                 | 3         | 0.5%    |
| Silicon Motion                          | 3         | 0.5%    |
| Marvell Technology Group                | 3         | 0.5%    |
| Lite-On Technology                      | 3         | 0.5%    |
| Shenzhen Longsys Electronics            | 2         | 0.33%   |
| Solid State Storage Technology          | 1         | 0.17%   |
| Shenzhen Unionmemory Information System | 1         | 0.17%   |
| Nvidia                                  | 1         | 0.17%   |
| INNOGRIT                                | 1         | 0.17%   |
| Biwin Storage Technology                | 1         | 0.17%   |
| Apple                                   | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 52        | 8.07%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 49        | 7.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 29        | 4.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 2.48%   |
| AMD 500 Series Chipset SATA Controller                                         | 16        | 2.48%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 15        | 2.33%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 15        | 2.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 14        | 2.17%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 12        | 1.86%   |
| AMD 600 Series Chipset SATA Controller                                         | 12        | 1.86%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 11        | 1.71%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 11        | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 1.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 1.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 1.4%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 9         | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 1.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 1.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 1.4%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 8         | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 1.24%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 7         | 1.09%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 7         | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 1.09%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 6         | 0.93%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 0.93%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 6         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 0.93%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 5         | 0.78%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 5         | 0.78%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 0.78%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 5         | 0.78%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 5         | 0.78%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 5         | 0.78%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 0.78%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 4         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 282       | 48.79%  |
| SATA | 246       | 42.56%  |
| RAID | 33        | 5.71%   |
| IDE  | 10        | 1.73%   |
| SAS  | 7         | 1.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 262       | 62.53%  |
| AMD     | 148       | 35.32%  |
| ARM     | 8         | 1.91%   |
| Unknown | 1         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 9         | 2.15%   |
| ARM Processor                                  | 8         | 1.91%   |
| Intel 12th Gen Core i7-1260P                   | 7         | 1.67%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 7         | 1.67%   |
| Intel 12th Gen Core i5-1240P                   | 6         | 1.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 6         | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 5         | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 5         | 1.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 5         | 1.19%   |
| Intel Core i5-8350U CPU @ 1.70GHz              | 5         | 1.19%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 5         | 1.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 5         | 1.19%   |
| AMD Ryzen 9 7950X 16-Core Processor            | 5         | 1.19%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 5         | 1.19%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics     | 5         | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 4         | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 4         | 0.95%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz             | 4         | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 4         | 0.95%   |
| AMD Ryzen 9 6900HS with Radeon Graphics        | 4         | 0.95%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 4         | 0.95%   |
| AMD Ryzen 7 6800H with Radeon Graphics         | 4         | 0.95%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 4         | 0.95%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 4         | 0.95%   |
| AMD Ryzen 5 5625U with Radeon Graphics         | 4         | 0.95%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz             | 3         | 0.72%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz             | 3         | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 3         | 0.72%   |
| Intel Core i7-10710U CPU @ 1.10GHz             | 3         | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 3         | 0.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 3         | 0.72%   |
| Intel Core i5-9300H CPU @ 2.40GHz              | 3         | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 3         | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 3         | 0.72%   |
| Intel Celeron N4100 CPU @ 1.10GHz              | 3         | 0.72%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 3         | 0.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 3         | 0.72%   |
| AMD Ryzen 7 PRO 7840HS w/ Radeon 780M Graphics | 3         | 0.72%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics     | 3         | 0.72%   |
| AMD Ryzen 7 6800HS with Radeon Graphics        | 3         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 97        | 23.15%  |
| Other                  | 82        | 19.57%  |
| Intel Core i5          | 53        | 12.65%  |
| AMD Ryzen 7            | 46        | 10.98%  |
| AMD Ryzen 9            | 38        | 9.07%   |
| AMD Ryzen 5            | 35        | 8.35%   |
| AMD Ryzen 7 PRO        | 16        | 3.82%   |
| Intel Celeron          | 11        | 2.63%   |
| Intel Xeon             | 10        | 2.39%   |
| Intel Core i3          | 6         | 1.43%   |
| Intel Core i9          | 5         | 1.19%   |
| AMD Ryzen Threadripper | 5         | 1.19%   |
| AMD FX                 | 3         | 0.72%   |
| Intel Core 2 Duo       | 2         | 0.48%   |
| Intel Atom             | 2         | 0.48%   |
| Intel Pentium Gold     | 1         | 0.24%   |
| Intel Pentium D        | 1         | 0.24%   |
| Intel Core m3          | 1         | 0.24%   |
| AMD Ryzen 5 PRO        | 1         | 0.24%   |
| AMD Ryzen 3            | 1         | 0.24%   |
| AMD EPYC               | 1         | 0.24%   |
| AMD Athlon II X4       | 1         | 0.24%   |
| AMD Athlon 64 X2       | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 131       | 31.26%  |
| 8       | 90        | 21.48%  |
| 2       | 55        | 13.13%  |
| 6       | 54        | 12.89%  |
| 12      | 29        | 6.92%   |
| 16      | 18        | 4.3%    |
| 14      | 12        | 2.86%   |
| 10      | 12        | 2.86%   |
| 24      | 8         | 1.91%   |
| Unknown | 7         | 1.67%   |
| 64      | 1         | 0.24%   |
| 32      | 1         | 0.24%   |
| 1       | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 409       | 97.61%  |
| Unknown | 7         | 1.67%   |
| 2       | 3         | 0.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 372       | 88.78%  |
| 1       | 40        | 9.55%   |
| Unknown | 7         | 1.67%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 417       | 99.29%  |
| 64-bit         | 1         | 0.24%   |
| 32-bit         | 1         | 0.24%   |
| Unknown        | 1         | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 32.79%  |
| 0x0a50000c | 19        | 4.42%   |
| 0x306c3    | 13        | 3.02%   |
| 0x306a9    | 13        | 3.02%   |
| 0x906ea    | 12        | 2.79%   |
| 0x806c1    | 11        | 2.56%   |
| 0x806ea    | 10        | 2.33%   |
| 0x0a50000d | 10        | 2.33%   |
| 0x0a404102 | 10        | 2.33%   |
| 0x08701021 | 10        | 2.33%   |
| 0x506e3    | 8         | 1.86%   |
| 0x40661    | 8         | 1.86%   |
| 0x08600106 | 8         | 1.86%   |
| 0x906a3    | 7         | 1.63%   |
| 0x806ec    | 6         | 1.4%    |
| 0x806e9    | 6         | 1.4%    |
| 0x306d4    | 6         | 1.4%    |
| 0x0a601203 | 6         | 1.4%    |
| 0x906e9    | 5         | 1.16%   |
| 0x806eb    | 5         | 1.16%   |
| 0x0a704103 | 5         | 1.16%   |
| 0x08701013 | 5         | 1.16%   |
| 0xb0671    | 4         | 0.93%   |
| 0x406e3    | 4         | 0.93%   |
| 0x40651    | 4         | 0.93%   |
| 0x08108109 | 4         | 0.93%   |
| 0xb06a2    | 3         | 0.7%    |
| 0x906a4    | 3         | 0.7%    |
| 0x706a8    | 3         | 0.7%    |
| 0x706a1    | 3         | 0.7%    |
| 0x0a201016 | 3         | 0.7%    |
| 0x0800820d | 3         | 0.7%    |
| 0x08001138 | 3         | 0.7%    |
| 0xb06a3    | 2         | 0.47%   |
| 0xa0660    | 2         | 0.47%   |
| 0xa0653    | 2         | 0.47%   |
| 0xa0652    | 2         | 0.47%   |
| 0x906ed    | 2         | 0.47%   |
| 0x706e5    | 2         | 0.47%   |
| 0x306e4    | 2         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 66        | 15.71%  |
| Unknown          | 62        | 14.76%  |
| Zen 3            | 50        | 11.9%   |
| Alderlake Hybrid | 44        | 10.48%  |
| Haswell          | 33        | 7.86%   |
| Zen 2            | 30        | 7.14%   |
| TigerLake        | 22        | 5.24%   |
| IvyBridge        | 21        | 5%      |
| Skylake          | 19        | 4.52%   |
| CometLake        | 11        | 2.62%   |
| Zen+             | 10        | 2.38%   |
| IceLake          | 9         | 2.14%   |
| Broadwell        | 9         | 2.14%   |
| Goldmont plus    | 8         | 1.9%    |
| Zen              | 7         | 1.67%   |
| SandyBridge      | 3         | 0.71%   |
| Piledriver       | 3         | 0.71%   |
| Westmere         | 2         | 0.48%   |
| Bonnell          | 2         | 0.48%   |
| Tremont          | 1         | 0.24%   |
| Silvermont       | 1         | 0.24%   |
| Penryn           | 1         | 0.24%   |
| NetBurst         | 1         | 0.24%   |
| Nehalem          | 1         | 0.24%   |
| K8 Hammer        | 1         | 0.24%   |
| K10 Llano        | 1         | 0.24%   |
| Gracemont        | 1         | 0.24%   |
| Core             | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 207       | 40.43%  |
| AMD                        | 158       | 30.86%  |
| Nvidia                     | 142       | 27.73%  |
| Matrox Electronics Systems | 4         | 0.78%   |
| ASPEED Technology          | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 23        | 4.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 18        | 3.42%   |
| AMD Rembrandt [Radeon 680M]                                          | 17        | 3.23%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                            | 15        | 2.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]              | 13        | 2.47%   |
| Intel UHD Graphics 620                                               | 12        | 2.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 12        | 2.28%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                               | 10        | 1.9%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]        | 10        | 1.9%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]              | 10        | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 9         | 1.71%   |
| Intel HD Graphics 620                                                | 9         | 1.71%   |
| AMD Raphael                                                          | 9         | 1.71%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]        | 9         | 1.71%   |
| Intel GeminiLake [UHD Graphics 600]                                  | 8         | 1.52%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 8         | 1.52%   |
| AMD Phoenix1                                                         | 8         | 1.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                  | 7         | 1.33%   |
| Intel HD Graphics 630                                                | 6         | 1.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 6         | 1.14%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                           | 6         | 1.14%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                       | 6         | 1.14%   |
| AMD Barcelo                                                          | 6         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 5         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 5         | 0.95%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                           | 5         | 0.95%   |
| Intel HD Graphics 5500                                               | 5         | 0.95%   |
| Intel HD Graphics 530                                                | 5         | 0.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 5         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 5         | 0.95%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                      | 5         | 0.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 5         | 0.95%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 4         | 0.76%   |
| Nvidia GP108M [GeForce MX250]                                        | 4         | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                        | 4         | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                       | 4         | 0.76%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                          | 4         | 0.76%   |
| Nvidia GK104 [GeForce GTX 760]                                       | 4         | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                              | 4         | 0.76%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                      | 4         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 125       | 29.62%  |
| 1 x AMD         | 114       | 27.01%  |
| Intel + Nvidia  | 67        | 15.88%  |
| 1 x Nvidia      | 53        | 12.56%  |
| AMD + Nvidia    | 22        | 5.21%   |
| 2 x AMD         | 11        | 2.61%   |
| Intel + AMD     | 11        | 2.61%   |
| Other           | 10        | 2.37%   |
| 1 x Matrox      | 4         | 0.95%   |
| 2 x Intel       | 2         | 0.47%   |
| Intel + 2 x AMD | 1         | 0.24%   |
| 1 x ASPEED      | 1         | 0.24%   |
| AMD + ASPEED    | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 304       | 72.04%  |
| Proprietary | 99        | 23.46%  |
| Unknown     | 19        | 4.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 250       | 58.69%  |
| 0.01-0.5   | 51        | 11.97%  |
| 1.01-2.0   | 35        | 8.22%   |
| 7.01-8.0   | 28        | 6.57%   |
| 8.01-16.0  | 21        | 4.93%   |
| 3.01-4.0   | 20        | 4.69%   |
| 0.51-1.0   | 14        | 3.29%   |
| 16.01-24.0 | 5         | 1.17%   |
| 5.01-6.0   | 1         | 0.23%   |
| 2.01-3.0   | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 54        | 11.32%  |
| BOE                  | 53        | 11.11%  |
| Dell                 | 47        | 9.85%   |
| Samsung Electronics  | 46        | 9.64%   |
| Goldstar             | 37        | 7.76%   |
| Chimei Innolux       | 34        | 7.13%   |
| LG Display           | 30        | 6.29%   |
| Apple                | 20        | 4.19%   |
| Acer                 | 16        | 3.35%   |
| Sharp                | 14        | 2.94%   |
| Ancor Communications | 13        | 2.73%   |
| Hewlett-Packard      | 11        | 2.31%   |
| ASUSTek Computer     | 9         | 1.89%   |
| CSO                  | 8         | 1.68%   |
| PANDA                | 7         | 1.47%   |
| Lenovo               | 7         | 1.47%   |
| Iiyama               | 7         | 1.47%   |
| BenQ                 | 6         | 1.26%   |
| AOC                  | 6         | 1.26%   |
| Philips              | 5         | 1.05%   |
| Gigabyte Technology  | 5         | 1.05%   |
| ViewSonic            | 4         | 0.84%   |
| TMX                  | 4         | 0.84%   |
| Eizo                 | 4         | 0.84%   |
| InfoVision           | 3         | 0.63%   |
| Vizio                | 2         | 0.42%   |
| Toshiba              | 2         | 0.42%   |
| Panasonic            | 2         | 0.42%   |
| MSI                  | 2         | 0.42%   |
| Hitachi              | 2         | 0.42%   |
| HannStar             | 2         | 0.42%   |
| WST                  | 1         | 0.21%   |
| Valve                | 1         | 0.21%   |
| Unknown (AAA)        | 1         | 0.21%   |
| Sceptre Tech         | 1         | 0.21%   |
| RTK                  | 1         | 0.21%   |
| Nreal Air            | 1         | 0.21%   |
| NEC Computers        | 1         | 0.21%   |
| MPI                  | 1         | 0.21%   |
| KDB                  | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 6         | 1.23%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.82%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 4         | 0.82%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.61%   |
| Goldstar HDR WQHD GSM772E 3440x1440 800x335mm 34.1-inch               | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch        | 3         | 0.61%   |
| Apple iMac APPAE05 3840x2160 597x336mm 27.0-inch                      | 3         | 0.61%   |
| Apple Color LCD APPA02F 2880x1800 331x207mm 15.4-inch                 | 3         | 0.61%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 3         | 0.61%   |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                 | 3         | 0.61%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 3         | 0.61%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                 | 2         | 0.41%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                 | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 2         | 0.41%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch          | 2         | 0.41%   |
| LG Display LCD Monitor LGD40A9 1920x1080 309x174mm 14.0-inch          | 2         | 0.41%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.41%   |
| Goldstar ULTRAGEAR+ GSM5C34 2560x1440 590x333mm 26.7-inch             | 2         | 0.41%   |
| Goldstar ULTRAFINE GSM5BC2 3840x2160 697x392mm 31.5-inch              | 2         | 0.41%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.41%   |
| Goldstar FULL HD GSM5BDF 1920x1080 480x270mm 21.7-inch                | 2         | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.41%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 0.41%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2         | 0.41%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 0.41%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                   | 2         | 0.41%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 2         | 0.41%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN139D 1920x1080 293x165mm 13.2-inch      | 2         | 0.41%   |
| BOE LCD Monitor BOE0B56 1920x1080 309x174mm 14.0-inch                 | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO6DA8 2560x1600 301x188mm 14.0-inch        | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 180       | 39.82%  |
| 3840x2160 (4K)     | 63        | 13.94%  |
| 2560x1440 (QHD)    | 43        | 9.51%   |
| 2880x1800          | 24        | 5.31%   |
| 1920x1200 (WUXGA)  | 24        | 5.31%   |
| 2560x1600          | 21        | 4.65%   |
| 1366x768 (WXGA)    | 20        | 4.42%   |
| 3440x1440          | 13        | 2.88%   |
| 1280x1024 (SXGA)   | 10        | 2.21%   |
| 2256x1504          | 9         | 1.99%   |
| 3840x2400          | 5         | 1.11%   |
| 2560x1080          | 5         | 1.11%   |
| 1600x900 (HD+)     | 5         | 1.11%   |
| 1680x1050 (WSXGA+) | 4         | 0.88%   |
| 3840x1080          | 2         | 0.44%   |
| 3200x2000          | 2         | 0.44%   |
| 2240x1400          | 2         | 0.44%   |
| 1920x1280          | 2         | 0.44%   |
| 1024x600           | 2         | 0.44%   |
| 3840x2560          | 1         | 0.22%   |
| 3840x1200          | 1         | 0.22%   |
| 3456x2160          | 1         | 0.22%   |
| 3200x1800 (QHD+)   | 1         | 0.22%   |
| 3000x2000          | 1         | 0.22%   |
| 2736x1824          | 1         | 0.22%   |
| 2560x2880          | 1         | 0.22%   |
| 2160x1440          | 1         | 0.22%   |
| 2160x1200          | 1         | 0.22%   |
| 1920x2160          | 1         | 0.22%   |
| 1600x1200          | 1         | 0.22%   |
| 1440x900 (WXGA+)   | 1         | 0.22%   |
| 1360x768           | 1         | 0.22%   |
| 1280x800 (WXGA)    | 1         | 0.22%   |
| 1280x720 (HD)      | 1         | 0.22%   |
| Unknown            | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 85        | 18.16%  |
| 14      | 63        | 13.46%  |
| 13      | 60        | 12.82%  |
| 27      | 58        | 12.39%  |
| 24      | 37        | 7.91%   |
| 23      | 21        | 4.49%   |
| 34      | 20        | 4.27%   |
| 16      | 19        | 4.06%   |
| 31      | 18        | 3.85%   |
| 21      | 14        | 2.99%   |
| 17      | 14        | 2.99%   |
| 12      | 10        | 2.14%   |
| 19      | 6         | 1.28%   |
| 25      | 5         | 1.07%   |
| 84      | 4         | 0.85%   |
| 20      | 4         | 0.85%   |
| Unknown | 4         | 0.85%   |
| 22      | 3         | 0.64%   |
| 86      | 2         | 0.43%   |
| 54      | 2         | 0.43%   |
| 48      | 2         | 0.43%   |
| 28      | 2         | 0.43%   |
| 26      | 2         | 0.43%   |
| 11      | 2         | 0.43%   |
| 10      | 2         | 0.43%   |
| 46      | 1         | 0.21%   |
| 43      | 1         | 0.21%   |
| 40      | 1         | 0.21%   |
| 39      | 1         | 0.21%   |
| 38      | 1         | 0.21%   |
| 36      | 1         | 0.21%   |
| 35      | 1         | 0.21%   |
| 32      | 1         | 0.21%   |
| 18      | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 184       | 40.26%  |
| 501-600     | 107       | 23.41%  |
| 201-300     | 58        | 12.69%  |
| 601-700     | 26        | 5.69%   |
| 401-500     | 22        | 4.81%   |
| 701-800     | 21        | 4.6%    |
| 351-400     | 18        | 3.94%   |
| 1001-1500   | 7         | 1.53%   |
| 801-900     | 5         | 1.09%   |
| 1501-2000   | 5         | 1.09%   |
| Unknown     | 4         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 271       | 65.3%   |
| 16/10   | 89        | 21.45%  |
| 21/9    | 21        | 5.06%   |
| 3/2     | 15        | 3.61%   |
| 5/4     | 9         | 2.17%   |
| 32/9    | 2         | 0.48%   |
| 0.89    | 2         | 0.48%   |
| 6/5     | 1         | 0.24%   |
| 4/3     | 1         | 0.24%   |
| 3.20    | 1         | 0.24%   |
| 1.00    | 1         | 0.24%   |
| 0.56    | 1         | 0.24%   |
| Unknown | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 95        | 20.43%  |
| 101-110        | 86        | 18.49%  |
| 301-350        | 59        | 12.69%  |
| 201-250        | 55        | 11.83%  |
| 351-500        | 42        | 9.03%   |
| 71-80          | 28        | 6.02%   |
| 111-120        | 18        | 3.87%   |
| 151-200        | 17        | 3.66%   |
| 251-300        | 16        | 3.44%   |
| 61-70          | 9         | 1.94%   |
| 121-130        | 9         | 1.94%   |
| More than 1000 | 8         | 1.72%   |
| 501-1000       | 8         | 1.72%   |
| 141-150        | 5         | 1.08%   |
| Unknown        | 4         | 0.86%   |
| 51-60          | 2         | 0.43%   |
| 41-50          | 2         | 0.43%   |
| 131-140        | 2         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 127       | 28.48%  |
| 51-100        | 102       | 22.87%  |
| 161-240       | 101       | 22.65%  |
| 101-120       | 75        | 16.82%  |
| More than 240 | 32        | 7.17%   |
| 1-50          | 5         | 1.12%   |
| Unknown       | 4         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 294       | 68.06%  |
| 2     | 84        | 19.44%  |
| 0     | 39        | 9.03%   |
| 3     | 14        | 3.24%   |
| 4     | 1         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 253       | 41.27%  |
| Realtek Semiconductor             | 197       | 32.14%  |
| MediaTek                          | 42        | 6.85%   |
| Broadcom                          | 26        | 4.24%   |
| Qualcomm Atheros                  | 25        | 4.08%   |
| Qualcomm                          | 9         | 1.47%   |
| Aquantia                          | 9         | 1.47%   |
| TP-Link                           | 6         | 0.98%   |
| Lenovo                            | 4         | 0.65%   |
| Xiaomi                            | 3         | 0.49%   |
| Ralink Technology                 | 3         | 0.49%   |
| Microsoft                         | 3         | 0.49%   |
| Ralink                            | 2         | 0.33%   |
| Qualcomm Technologies             | 2         | 0.33%   |
| Marvell Technology Group          | 2         | 0.33%   |
| ICS Advent                        | 2         | 0.33%   |
| D-Link System                     | 2         | 0.33%   |
| Broadcom Limited                  | 2         | 0.33%   |
| ASIX Electronics                  | 2         | 0.33%   |
| Apple                             | 2         | 0.33%   |
| Texas Instruments                 | 1         | 0.16%   |
| STMicroelectronics                | 1         | 0.16%   |
| Standard Microsystems             | 1         | 0.16%   |
| Samsung Electronics               | 1         | 0.16%   |
| Qualcomm Atheros Communications   | 1         | 0.16%   |
| QinHeng Electronics               | 1         | 0.16%   |
| Pulse-Eight                       | 1         | 0.16%   |
| Oculus VR                         | 1         | 0.16%   |
| Nvidia                            | 1         | 0.16%   |
| Google                            | 1         | 0.16%   |
| FIBOCOM                           | 1         | 0.16%   |
| Espressif                         | 1         | 0.16%   |
| Ericsson Business Mobile Networks | 1         | 0.16%   |
| Edimax Technology                 | 1         | 0.16%   |
| DisplayLink                       | 1         | 0.16%   |
| D-Link                            | 1         | 0.16%   |
| ASUSTek Computer                  | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 118       | 16.34%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 39        | 5.4%    |
| Intel Wi-Fi 6 AX200                                                    | 31        | 4.29%   |
| Realtek RTL8125 2.5GbE Controller                                      | 25        | 3.46%   |
| Intel Ethernet Controller I225-V                                       | 21        | 2.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 20        | 2.77%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 19        | 2.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 19        | 2.63%   |
| Intel I211 Gigabit Network Connection                                  | 18        | 2.49%   |
| Intel Wi-Fi 6 AX201                                                    | 15        | 2.08%   |
| Intel Wireless 8265 / 8275                                             | 13        | 1.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 11        | 1.52%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 11        | 1.52%   |
| Intel Wireless 8260                                                    | 10        | 1.39%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 9         | 1.25%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 9         | 1.25%   |
| Intel Wireless 7265                                                    | 8         | 1.11%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 8         | 1.11%   |
| Intel Ethernet Connection (7) I219-V                                   | 8         | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 1.11%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 7         | 0.97%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 7         | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 7         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 0.83%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 0.69%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 5         | 0.69%   |
| Intel Wireless 7260                                                    | 5         | 0.69%   |
| Intel Wireless 3160                                                    | 5         | 0.69%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 5         | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 5         | 0.69%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 5         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 206       | 59.37%  |
| MediaTek                        | 41        | 11.82%  |
| Realtek Semiconductor           | 27        | 7.78%   |
| Broadcom                        | 21        | 6.05%   |
| Qualcomm Atheros                | 20        | 5.76%   |
| Qualcomm                        | 8         | 2.31%   |
| TP-Link                         | 6         | 1.73%   |
| Ralink Technology               | 3         | 0.86%   |
| Microsoft                       | 3         | 0.86%   |
| Ralink                          | 2         | 0.58%   |
| Qualcomm Technologies           | 2         | 0.58%   |
| Broadcom Limited                | 2         | 0.58%   |
| Qualcomm Atheros Communications | 1         | 0.29%   |
| FIBOCOM                         | 1         | 0.29%   |
| Edimax Technology               | 1         | 0.29%   |
| D-Link System                   | 1         | 0.29%   |
| D-Link                          | 1         | 0.29%   |
| ASUSTek Computer                | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                              | 31        | 8.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter    | 20        | 5.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]        | 19        | 5.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                 | 19        | 5.48%   |
| Intel Wi-Fi 6 AX201                                              | 15        | 4.32%   |
| Intel Wireless 8265 / 8275                                       | 13        | 3.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 11        | 3.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 11        | 3.17%   |
| Intel Wireless 8260                                              | 10        | 2.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 9         | 2.59%   |
| Intel Raptor Lake PCH CNVi WiFi                                  | 9         | 2.59%   |
| Intel Wireless 7265                                              | 8         | 2.31%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]          | 8         | 2.31%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 7         | 2.02%   |
| Qualcomm QCNFA765 Wireless Network Adapter                       | 7         | 2.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter    | 7         | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                | 7         | 2.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                         | 7         | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 6         | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 6         | 1.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter         | 5         | 1.44%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                | 5         | 1.44%   |
| Intel Wireless 7260                                              | 5         | 1.44%   |
| Intel Wireless 3160                                              | 5         | 1.44%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                | 5         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 5         | 1.44%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter     | 5         | 1.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 4         | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                   | 4         | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 4         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 4         | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 4         | 1.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                      | 3         | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 3         | 0.86%   |
| Intel Wireless 3165                                              | 3         | 0.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 3         | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 2         | 0.58%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800] | 2         | 0.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 2         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                 | 2         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 179       | 51.29%  |
| Intel                    | 120       | 34.38%  |
| Broadcom                 | 13        | 3.72%   |
| Aquantia                 | 9         | 2.58%   |
| Qualcomm Atheros         | 6         | 1.72%   |
| Lenovo                   | 4         | 1.15%   |
| Xiaomi                   | 3         | 0.86%   |
| Marvell Technology Group | 2         | 0.57%   |
| ICS Advent               | 2         | 0.57%   |
| ASIX Electronics         | 2         | 0.57%   |
| Apple                    | 2         | 0.57%   |
| Standard Microsystems    | 1         | 0.29%   |
| Samsung Electronics      | 1         | 0.29%   |
| Qualcomm                 | 1         | 0.29%   |
| Nvidia                   | 1         | 0.29%   |
| Google                   | 1         | 0.29%   |
| DisplayLink              | 1         | 0.29%   |
| D-Link System            | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 118       | 32.24%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 39        | 10.66%  |
| Realtek RTL8125 2.5GbE Controller                                              | 25        | 6.83%   |
| Intel Ethernet Controller I225-V                                               | 21        | 5.74%   |
| Intel I211 Gigabit Network Connection                                          | 18        | 4.92%   |
| Intel Ethernet Connection (7) I219-V                                           | 8         | 2.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 2.19%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 1.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 1.37%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 1.37%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.37%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.09%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 4         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.82%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.82%   |
| Intel Ethernet Connection (16) I219-V                                          | 3         | 0.82%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 3         | 0.82%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3         | 0.82%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2         | 0.55%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 2         | 0.55%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 0.55%   |
| Intel Ethernet Connection (16) I219-LM                                         | 2         | 0.55%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 0.55%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.55%   |
| ICS Advent 10/100M LAN                                                         | 2         | 0.55%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 2         | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.55%   |
| Standard Microsystems Ethernet controller                                      | 1         | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.27%   |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.27%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.27%   |
| Qualcomm Nokia G42 5G                                                          | 1         | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 333       | 50.92%  |
| Ethernet | 312       | 47.71%  |
| Modem    | 7         | 1.07%   |
| Unknown  | 2         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 274       | 62.56%  |
| Ethernet | 164       | 37.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 198       | 46.7%   |
| 1     | 192       | 45.28%  |
| 3     | 21        | 4.95%   |
| 0     | 10        | 2.36%   |
| 4     | 2         | 0.47%   |
| 5     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 307       | 71.73%  |
| Yes  | 121       | 28.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 191       | 57.53%  |
| Foxconn / Hon Hai               | 22        | 6.63%   |
| Realtek Semiconductor           | 20        | 6.02%   |
| Apple                           | 20        | 6.02%   |
| IMC Networks                    | 15        | 4.52%   |
| Cambridge Silicon Radio         | 15        | 4.52%   |
| MediaTek                        | 11        | 3.31%   |
| Qualcomm Atheros Communications | 8         | 2.41%   |
| Broadcom                        | 8         | 2.41%   |
| ASUSTek Computer                | 7         | 2.11%   |
| USI                             | 4         | 1.2%    |
| Lite-On Technology              | 4         | 1.2%    |
| Opticis                         | 2         | 0.6%    |
| Realtek                         | 1         | 0.3%    |
| Integrated System Solution      | 1         | 0.3%    |
| HTC (High Tech Computer)        | 1         | 0.3%    |
| Belkin Components               | 1         | 0.3%    |
| Alps Electric                   | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX211 Bluetooth                               | 32        | 9.64%   |
| Intel AX201 Bluetooth                               | 30        | 9.04%   |
| Intel AX200 Bluetooth                               | 29        | 8.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 8.43%   |
| Intel Bluetooth Device                              | 21        | 6.33%   |
| Intel Bluetooth wireless interface                  | 19        | 5.72%   |
| Intel AX210 Bluetooth                               | 18        | 5.42%   |
| Realtek Bluetooth Radio                             | 16        | 4.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 4.52%   |
| Foxconn / Hon Hai Wireless_Device                   | 14        | 4.22%   |
| Apple Bluetooth Host Controller                     | 14        | 4.22%   |
| IMC Networks Wireless_Device                        | 12        | 3.61%   |
| MediaTek Wireless_Device                            | 11        | 3.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 2.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.51%   |
| Apple Bluetooth USB Host Controller                 | 5         | 1.51%   |
| USI Bluetooth Device                                | 4         | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.2%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.9%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 0.9%    |
| ASUS ASUS USB-BT500                                 | 3         | 0.9%    |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.6%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 0.6%    |
| Opticis Bluetooth Radio                             | 2         | 0.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.6%    |
| Broadcom HP Portable SoftSailing                    | 2         | 0.6%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.3%    |
| Realtek Bluetooth Radio                             | 1         | 0.3%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.3%    |
| Lite-On Wireless_Device                             | 1         | 0.3%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.3%    |
| Integrated System Solution Bluetooth Device         | 1         | 0.3%    |
| IMC Networks Bluetooth Radio                        | 1         | 0.3%    |
| IMC Networks Bluetooth Device                       | 1         | 0.3%    |
| IMC Networks BCM20702A0                             | 1         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 257       | 38.7%   |
| AMD                                  | 170       | 25.6%   |
| Nvidia                               | 108       | 16.27%  |
| C-Media Electronics                  | 12        | 1.81%   |
| Logitech                             | 7         | 1.05%   |
| Focusrite-Novation                   | 7         | 1.05%   |
| RODE Microphones                     | 6         | 0.9%    |
| Razer USA                            | 6         | 0.9%    |
| Lenovo                               | 6         | 0.9%    |
| Texas Instruments                    | 5         | 0.75%   |
| Kingston Technology                  | 5         | 0.75%   |
| Realtek Semiconductor                | 4         | 0.6%    |
| Creative Technology                  | 4         | 0.6%    |
| Blue Microphones                     | 4         | 0.6%    |
| ASUSTek Computer                     | 4         | 0.6%    |
| Shure                                | 3         | 0.45%   |
| Schiit Audio                         | 3         | 0.45%   |
| AudioQuest                           | 3         | 0.45%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.3%    |
| Synaptics                            | 2         | 0.3%    |
| Sony                                 | 2         | 0.3%    |
| Micro Star International             | 2         | 0.3%    |
| JMTek                                | 2         | 0.3%    |
| Huawei Technologies                  | 2         | 0.3%    |
| Hewlett-Packard                      | 2         | 0.3%    |
| GN Netcom                            | 2         | 0.3%    |
| DSEA A/S                             | 2         | 0.3%    |
| Creative Labs                        | 2         | 0.3%    |
| Corsair                              | 2         | 0.3%    |
| Yamaha                               | 1         | 0.15%   |
| Valve Software                       | 1         | 0.15%   |
| Trust                                | 1         | 0.15%   |
| Thomann                              | 1         | 0.15%   |
| TC Electronic                        | 1         | 0.15%   |
| SteelSeries ApS                      | 1         | 0.15%   |
| Sennheiser Communications            | 1         | 0.15%   |
| Satechi                              | 1         | 0.15%   |
| Samson Technologies                  | 1         | 0.15%   |
| Roland                               | 1         | 0.15%   |
| PreSonus Audio Electronics           | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 89        | 10.84%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 42        | 5.12%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 37        | 4.51%   |
| AMD Starship/Matisse HD Audio Controller                                   | 36        | 4.38%   |
| Intel Sunrise Point-LP HD Audio                                            | 29        | 3.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 23        | 2.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 23        | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23        | 2.8%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 23        | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 22        | 2.68%   |
| Nvidia Audio device                                                        | 17        | 2.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 1.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13        | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 1.34%   |
| AMD Navi 10 HDMI Audio                                                     | 11        | 1.34%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 10        | 1.22%   |
| Intel Raptor Lake High Definition Audio Controller                         | 10        | 1.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10        | 1.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 0.97%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 0.97%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 8         | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 0.61%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.61%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5         | 0.61%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 87        | 18.63%  |
| SK hynix                     | 83        | 17.77%  |
| Micron Technology            | 58        | 12.42%  |
| Kingston                     | 57        | 12.21%  |
| Corsair                      | 44        | 9.42%   |
| Crucial                      | 34        | 7.28%   |
| G.Skill                      | 28        | 6%      |
| Unknown                      | 18        | 3.85%   |
| A-DATA Technology            | 10        | 2.14%   |
| Unknown                      | 9         | 1.93%   |
| Team                         | 8         | 1.71%   |
| Unknown (ABCD)               | 5         | 1.07%   |
| Ramaxel Technology           | 5         | 1.07%   |
| Patriot                      | 4         | 0.86%   |
| GOODRAM                      | 3         | 0.64%   |
| Transcend                    | 2         | 0.43%   |
| Lexar                        | 2         | 0.43%   |
| Avant                        | 2         | 0.43%   |
| AMD                          | 2         | 0.43%   |
| Unknown (0x59B)              | 1         | 0.21%   |
| Strontium                    | 1         | 0.21%   |
| Smart Brazil                 | 1         | 0.21%   |
| Patriot Memory (PDP Systems) | 1         | 0.21%   |
| GLOWAY                       | 1         | 0.21%   |
| Apacer                       | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 10        | 2.01%   |
| Unknown                                                          | 9         | 1.81%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 6         | 1.21%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s           | 5         | 1.01%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.8%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.8%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.8%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 4         | 0.8%    |
| Team RAM TEAMGROUP-SD4-3200 16384MB SODIMM DDR4 3200MT/s         | 3         | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.6%    |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 3         | 0.6%    |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.6%    |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 3         | 0.6%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.6%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 3         | 0.6%    |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 3         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.6%    |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s          | 3         | 0.6%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 3         | 0.6%    |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s           | 3         | 0.6%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.4%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.4%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 2         | 0.4%    |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.4%    |
| SK hynix RAM HMCG78AEBSA095N 16GB SODIMM 4800MT/s                | 2         | 0.4%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.4%    |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 2         | 0.4%    |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 2         | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.4%    |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 0.4%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.4%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 0.4%    |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 214       | 52.71%  |
| DDR3    | 72        | 17.73%  |
| DDR5    | 43        | 10.59%  |
| LPDDR5  | 32        | 7.88%   |
| LPDDR4  | 26        | 6.4%    |
| LPDDR3  | 11        | 2.71%   |
| Unknown | 3         | 0.74%   |
| DDR2    | 2         | 0.49%   |
| SDRAM   | 1         | 0.25%   |
| DRAM    | 1         | 0.25%   |
| DDR     | 1         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 213       | 51.45%  |
| DIMM         | 134       | 32.37%  |
| Row Of Chips | 62        | 14.98%  |
| Chip         | 3         | 0.72%   |
| RIMM         | 1         | 0.24%   |
| Unknown      | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 188       | 42.06%  |
| 16384 | 118       | 26.4%   |
| 4096  | 71        | 15.88%  |
| 32768 | 57        | 12.75%  |
| 2048  | 10        | 2.24%   |
| 65536 | 2         | 0.45%   |
| 1024  | 1         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 90        | 20.32%  |
| 1600    | 55        | 12.42%  |
| 2667    | 53        | 11.96%  |
| 6400    | 29        | 6.55%   |
| 2400    | 27        | 6.09%   |
| 2133    | 27        | 6.09%   |
| 3600    | 25        | 5.64%   |
| 4800    | 20        | 4.51%   |
| 4267    | 14        | 3.16%   |
| 5600    | 11        | 2.48%   |
| 1867    | 10        | 2.26%   |
| 1333    | 8         | 1.81%   |
| 3733    | 7         | 1.58%   |
| 3000    | 7         | 1.58%   |
| 6000    | 6         | 1.35%   |
| 5200    | 6         | 1.35%   |
| 4266    | 4         | 0.9%    |
| 3800    | 4         | 0.9%    |
| 3266    | 4         | 0.9%    |
| Unknown | 3         | 0.68%   |
| 7500    | 2         | 0.45%   |
| 5500    | 2         | 0.45%   |
| 4000    | 2         | 0.45%   |
| 3866    | 2         | 0.45%   |
| 3666    | 2         | 0.45%   |
| 3534    | 2         | 0.45%   |
| 3334    | 2         | 0.45%   |
| 2933    | 2         | 0.45%   |
| 1866    | 2         | 0.45%   |
| 1066    | 2         | 0.45%   |
| 667     | 2         | 0.45%   |
| 7467    | 1         | 0.23%   |
| 3933    | 1         | 0.23%   |
| 3400    | 1         | 0.23%   |
| 3100    | 1         | 0.23%   |
| 2800    | 1         | 0.23%   |
| 2666    | 1         | 0.23%   |
| 2134    | 1         | 0.23%   |
| 2132    | 1         | 0.23%   |
| 1800    | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Xerox              | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Xerox Phaser 6125N      | 1         | 33.33%  |
| Canon TR8500 series     | 1         | 33.33%  |
| Brother HL-2240D series | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 50        | 18.38%  |
| Logitech                               | 34        | 12.5%   |
| IMC Networks                           | 33        | 12.13%  |
| Microdia                               | 22        | 8.09%   |
| Bison Electronics                      | 21        | 7.72%   |
| Realtek Semiconductor                  | 18        | 6.62%   |
| Sunplus Innovation Technology          | 12        | 4.41%   |
| Quanta                                 | 11        | 4.04%   |
| Apple                                  | 9         | 3.31%   |
| Acer                                   | 9         | 3.31%   |
| Luxvisions Innotech Limited            | 7         | 2.57%   |
| Syntek                                 | 6         | 2.21%   |
| Shinetech                              | 5         | 1.84%   |
| MacroSilicon                           | 4         | 1.47%   |
| Lite-On Technology                     | 4         | 1.47%   |
| Sonix Technology                       | 3         | 1.1%    |
| SunplusIT                              | 2         | 0.74%   |
| Samsung Electronics                    | 2         | 0.74%   |
| Razer USA                              | 2         | 0.74%   |
| Primax Electronics                     | 2         | 0.74%   |
| Microsoft                              | 2         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 0.74%   |
| Alcor Micro                            | 2         | 0.74%   |
| 2M UVC CAMERA                          | 2         | 0.74%   |
| Z-Star Microelectronics                | 1         | 0.37%   |
| Valve Software                         | 1         | 0.37%   |
| Silicon Motion                         | 1         | 0.37%   |
| Ricoh                                  | 1         | 0.37%   |
| OPPO Electronics                       | 1         | 0.37%   |
| OmniVision Technologies                | 1         | 0.37%   |
| globaloptics                           | 1         | 0.37%   |
| AVerMedia Technologies                 | 1         | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 25        | 9.06%   |
| Microdia Integrated_Webcam_HD                 | 13        | 4.71%   |
| IMC Networks Integrated Camera                | 13        | 4.71%   |
| IMC Networks USB2.0 HD UVC WebCam             | 12        | 4.35%   |
| Bison Integrated Camera                       | 11        | 3.99%   |
| Chicony HP HD Camera                          | 9         | 3.26%   |
| Logitech HD Pro Webcam C920                   | 8         | 2.9%    |
| Realtek Integrated_Webcam_HD                  | 7         | 2.54%   |
| Syntek Integrated Camera                      | 6         | 2.17%   |
| Apple FaceTime HD Camera (Built-in)           | 6         | 2.17%   |
| Luxvisions Innotech Limited Integrated Camera | 5         | 1.81%   |
| Sunplus Integrated_Webcam_FHD                 | 4         | 1.45%   |
| ShineTech USB2.0 HD UVC WebCam                | 4         | 1.45%   |
| Realtek Laptop Camera                         | 4         | 1.45%   |
| Quanta USB2.0 HD UVC WebCam                   | 4         | 1.45%   |
| MacroSilicon MiraBox Capture                  | 4         | 1.45%   |
| Logitech Webcam C270                          | 4         | 1.45%   |
| Logitech StreamCam                            | 4         | 1.45%   |
| Logitech C922 Pro Stream Webcam               | 4         | 1.45%   |
| Acer Integrated Camera                        | 4         | 1.45%   |
| Lite-On Integrated Camera                     | 3         | 1.09%   |
| Bison HD Webcam                               | 3         | 1.09%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 0.72%   |
| Sonix USB2.0 HD UVC WebCam                    | 2         | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)       | 2         | 0.72%   |
| Quanta VGA WebCam                             | 2         | 0.72%   |
| Primax HP HD Webcam [Fixed]                   | 2         | 0.72%   |
| Microdia Webcam Vitade AF                     | 2         | 0.72%   |
| Microdia Integrated Webcam                    | 2         | 0.72%   |
| Logitech Webcam C930e                         | 2         | 0.72%   |
| Logitech C920 PRO HD Webcam                   | 2         | 0.72%   |
| Logitech BRIO Ultra HD Webcam                 | 2         | 0.72%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 0.72%   |
| Chicony USB2.0 Camera                         | 2         | 0.72%   |
| Chicony HP 5MP Camera                         | 2         | 0.72%   |
| Bison SunplusIT Integrated Camera             | 2         | 0.72%   |
| Bison BisonCam,NB Pro                         | 2         | 0.72%   |
| Acer Integrated IR Camera                     | 2         | 0.72%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam           | 2         | 0.72%   |
| Z-Star Venus USB2.0 Camera                    | 1         | 0.36%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 26        | 41.94%  |
| Validity Sensors           | 18        | 29.03%  |
| Shenzhen Goodix Technology | 14        | 22.58%  |
| LighTuning Technology      | 1         | 1.61%   |
| Gingytech                  | 1         | 1.61%   |
| Focal-systems.Corp         | 1         | 1.61%   |
| Elan Microelectronics      | 1         | 1.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 16.13%  |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 14.52%  |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 8.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 6.45%   |
| Synaptics UWP WBDI Device                                                  | 4         | 6.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 6.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.84%   |
| Synaptics UWP WBDI                                                         | 3         | 4.84%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 3.23%   |
| Validity Sensors VFS491                                                    | 2         | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.23%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 1.61%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.61%   |
| Synaptics WBDI                                                             | 1         | 1.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.61%   |
| Gingytech Fingerprint sensor                                               | 1         | 1.61%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.61%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 1.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 26        | 61.9%   |
| Broadcom         | 7         | 16.67%  |
| Yubico.com       | 5         | 11.9%   |
| Upek             | 1         | 2.38%   |
| SCM Microsystems | 1         | 2.38%   |
| OmniKey          | 1         | 2.38%   |
| Clay Logic       | 1         | 2.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 26        | 61.9%   |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 4         | 9.52%   |
| Broadcom 58200                                             | 3         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 4.76%   |
| Broadcom 5880                                              | 2         | 4.76%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 2.38%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 2.38%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1         | 2.38%   |
| OmniKey CardMan Smart@Link                                 | 1         | 2.38%   |
| Clay Logic Nitrokey HSM                                    | 1         | 2.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 261       | 60.42%  |
| 1     | 120       | 27.78%  |
| 2     | 44        | 10.19%  |
| 3     | 5         | 1.16%   |
| 4     | 2         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 60        | 27.4%   |
| Multimedia controller    | 43        | 19.63%  |
| Graphics card            | 35        | 15.98%  |
| Chipcard                 | 34        | 15.53%  |
| Net/wireless             | 16        | 7.31%   |
| Camera                   | 9         | 4.11%   |
| Bluetooth                | 5         | 2.28%   |
| Unassigned class         | 3         | 1.37%   |
| Network                  | 2         | 0.91%   |
| Net/ethernet             | 2         | 0.91%   |
| Modem                    | 2         | 0.91%   |
| Firewire controller      | 2         | 0.91%   |
| Communication controller | 2         | 0.91%   |
| Card reader              | 2         | 0.91%   |
| Storage/ata              | 1         | 0.46%   |
| Dvb card                 | 1         | 0.46%   |

