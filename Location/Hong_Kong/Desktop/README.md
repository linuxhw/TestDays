Linux in Hong Kong - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

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

Total: 392

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | STRIX B250G GAMING          | [e71d05d160](https://linux-hardware.org/?probe=e71d05d160) | Dec 26, 2025 |
| MSI           | MAG Z390M MORTAR            | [da8cf0d3e6](https://linux-hardware.org/?probe=da8cf0d3e6) | Dec 24, 2025 |
| MSI           | MPG Z790I EDGE WIFI         | [47618fa09e](https://linux-hardware.org/?probe=47618fa09e) | Dec 21, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [1f85b9af5c](https://linux-hardware.org/?probe=1f85b9af5c) | Nov 16, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [6ecd41cb9d](https://linux-hardware.org/?probe=6ecd41cb9d) | Nov 02, 2025 |
| Gigabyte      | H97-D3H-CF                  | [ec6f023759](https://linux-hardware.org/?probe=ec6f023759) | Oct 30, 2025 |
| Gigabyte      | B85M-DS3H-A                 | [431d118223](https://linux-hardware.org/?probe=431d118223) | Oct 22, 2025 |
| Lenovo        | 1064 NOK                    | [58842d436e](https://linux-hardware.org/?probe=58842d436e) | Oct 07, 2025 |
| Lenovo        | 1064 NOK                    | [a1e96e6c35](https://linux-hardware.org/?probe=a1e96e6c35) | Oct 07, 2025 |
| Dell          | 0F5C5X A00                  | [9250e080d0](https://linux-hardware.org/?probe=9250e080d0) | Sep 23, 2025 |
| Gigabyte      | B550M DS3H AC R2            | [0cbf2e13e3](https://linux-hardware.org/?probe=0cbf2e13e3) | Sep 17, 2025 |
| Gigabyte      | Z77M-D3H                    | [ef08ddbe59](https://linux-hardware.org/?probe=ef08ddbe59) | Sep 16, 2025 |
| Gigabyte      | B85M-DS3H-A                 | [3a7a44f878](https://linux-hardware.org/?probe=3a7a44f878) | Sep 07, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [259b064dae](https://linux-hardware.org/?probe=259b064dae) | Aug 26, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [f78395372e](https://linux-hardware.org/?probe=f78395372e) | Aug 26, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [c3291a4f6a](https://linux-hardware.org/?probe=c3291a4f6a) | Aug 21, 2025 |
| Unknown       | Apple iPhone X (Global)     | [9a5c49b7b4](https://linux-hardware.org/?probe=9a5c49b7b4) | Aug 17, 2025 |
| GALAX         | B460M FANTAXY V2 G10a       | [491f93195f](https://linux-hardware.org/?probe=491f93195f) | Aug 15, 2025 |
| MSI           | MPG B650I EDGE WIFI         | [87a900bc69](https://linux-hardware.org/?probe=87a900bc69) | Aug 15, 2025 |
| MSI           | MPG B850 EDGE TI WIFI       | [42feb2ff5a](https://linux-hardware.org/?probe=42feb2ff5a) | Aug 13, 2025 |
| Gigabyte      | B550M AORUS PRO AX          | [82b6589226](https://linux-hardware.org/?probe=82b6589226) | Aug 03, 2025 |
| Dell          | 03J4J0 A00                  | [30594f4f32](https://linux-hardware.org/?probe=30594f4f32) | Jul 17, 2025 |
| Dell          | 03J4J0 A00                  | [368f602e55](https://linux-hardware.org/?probe=368f602e55) | Jul 17, 2025 |
| IBM           | 8141KB4                     | [b2d94fe26b](https://linux-hardware.org/?probe=b2d94fe26b) | Jul 14, 2025 |
| TSINGHUA T... | B460-N2 V1.1                | [4c93574a2e](https://linux-hardware.org/?probe=4c93574a2e) | Jun 23, 2025 |
| TSINGHUA T... | B460-N2 V1.1                | [e1d6625658](https://linux-hardware.org/?probe=e1d6625658) | Jun 23, 2025 |
| Dell          | 0FR2VJ A00                  | [b829ef1dcd](https://linux-hardware.org/?probe=b829ef1dcd) | Jun 21, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [503d340244](https://linux-hardware.org/?probe=503d340244) | Jun 19, 2025 |
| Huanan        | X99-F8D V2.7                | [004881e20f](https://linux-hardware.org/?probe=004881e20f) | Jun 18, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [f73c3a15b0](https://linux-hardware.org/?probe=f73c3a15b0) | Jun 15, 2025 |
| ASUSTek       | B850M AYW GAMING WIFI       | [26fa960531](https://linux-hardware.org/?probe=26fa960531) | Jun 08, 2025 |
| Colorful T... | BATTLE-AX Z790M-PLUS D5 ... | [e60cc022cc](https://linux-hardware.org/?probe=e60cc022cc) | Jun 08, 2025 |
| ASUSTek       | P8Z77-V                     | [5ea4567ec2](https://linux-hardware.org/?probe=5ea4567ec2) | May 30, 2025 |
| Unknown       | Unknown                     | [37860ce79c](https://linux-hardware.org/?probe=37860ce79c) | May 25, 2025 |
| Dell          | 0N5G27 A00                  | [a2d14618b1](https://linux-hardware.org/?probe=a2d14618b1) | May 17, 2025 |
| ASUSTek       | PRIME Z790-P WIFI           | [671f45a412](https://linux-hardware.org/?probe=671f45a412) | May 10, 2025 |
| Intel         | B75                         | [3ace3eb74f](https://linux-hardware.org/?probe=3ace3eb74f) | May 09, 2025 |
| Gigabyte      | B460M GAMING HD             | [262166817f](https://linux-hardware.org/?probe=262166817f) | May 02, 2025 |
| ASRock        | B660M-ITX/ac                | [44486b5250](https://linux-hardware.org/?probe=44486b5250) | May 01, 2025 |
| ASRock        | B660M-STX                   | [1fc9308b5e](https://linux-hardware.org/?probe=1fc9308b5e) | Apr 29, 2025 |
| Dell          | 0MRC1X A01                  | [5eab785222](https://linux-hardware.org/?probe=5eab785222) | Apr 23, 2025 |
| Huanan        | X99-F8D PLUS V1.32          | [10d261dfba](https://linux-hardware.org/?probe=10d261dfba) | Apr 13, 2025 |
| Huanan        | X79-4M V3.0                 | [8e0b9902b0](https://linux-hardware.org/?probe=8e0b9902b0) | Apr 13, 2025 |
| Gigabyte      | B550I AORUS PRO AX          | [229462ba35](https://linux-hardware.org/?probe=229462ba35) | Mar 26, 2025 |
| METAPHYUNI    | M11 Series-HPT              | [5bbe21ead2](https://linux-hardware.org/?probe=5bbe21ead2) | Mar 21, 2025 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [0b7ae7e487](https://linux-hardware.org/?probe=0b7ae7e487) | Mar 20, 2025 |
| ASUSTek       | PRIME B760M-A               | [971f31b2e4](https://linux-hardware.org/?probe=971f31b2e4) | Mar 09, 2025 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [5006bd2526](https://linux-hardware.org/?probe=5006bd2526) | Feb 24, 2025 |
| GMKtec        | NucBox K6                   | [c7404d3e8a](https://linux-hardware.org/?probe=c7404d3e8a) | Feb 22, 2025 |
| ASUSTek       | Z97-PRO GAMER               | [12c28affcf](https://linux-hardware.org/?probe=12c28affcf) | Feb 19, 2025 |
| Unknown       | Unknown                     | [9228e0c6e0](https://linux-hardware.org/?probe=9228e0c6e0) | Feb 08, 2025 |
| Unknown       | Unknown                     | [4ac723cdc5](https://linux-hardware.org/?probe=4ac723cdc5) | Feb 08, 2025 |
| Gigabyte      | A320M-S2H-CF                | [5ca9e49e7b](https://linux-hardware.org/?probe=5ca9e49e7b) | Feb 07, 2025 |
| Gigabyte      | Z370N WIFI-CF               | [dcd1731383](https://linux-hardware.org/?probe=dcd1731383) | Jan 22, 2025 |
| HP            | 158B                        | [01634803b8](https://linux-hardware.org/?probe=01634803b8) | Jan 19, 2025 |
| Dell          | 0G3HR7 A00                  | [969498db10](https://linux-hardware.org/?probe=969498db10) | Jan 16, 2025 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [30146b9eaa](https://linux-hardware.org/?probe=30146b9eaa) | Jan 14, 2025 |
| Dell          | 0HGFJM A00                  | [f849a74d2e](https://linux-hardware.org/?probe=f849a74d2e) | Dec 24, 2024 |
| MSI           | MPG Z790 EDGE MONSTER HU... | [9362ff5af5](https://linux-hardware.org/?probe=9362ff5af5) | Dec 18, 2024 |
| H3C           | 3005                        | [8d2a9b7b91](https://linux-hardware.org/?probe=8d2a9b7b91) | Dec 12, 2024 |
| MSI           | MPG Z790 EDGE MONSTER HU... | [dbee9a2410](https://linux-hardware.org/?probe=dbee9a2410) | Nov 19, 2024 |
| HP            | 8B3C A                      | [ca1220b4d7](https://linux-hardware.org/?probe=ca1220b4d7) | Oct 28, 2024 |
| MSI           | MAG B365M MORTAR            | [e7487dc9a5](https://linux-hardware.org/?probe=e7487dc9a5) | Oct 27, 2024 |
| MSI           | MPG Z790 EDGE MONSTER HU... | [623a3231f2](https://linux-hardware.org/?probe=623a3231f2) | Oct 23, 2024 |
| Lenovo        | NOK                         | [89c7a1344f](https://linux-hardware.org/?probe=89c7a1344f) | Oct 21, 2024 |
| ASRock        | X600M-STX                   | [aa6001a955](https://linux-hardware.org/?probe=aa6001a955) | Oct 13, 2024 |
| HP            | 8B3C A                      | [59ea5dfc93](https://linux-hardware.org/?probe=59ea5dfc93) | Oct 02, 2024 |
| ASUSTek       | PRIME B760M-A               | [6e40568312](https://linux-hardware.org/?probe=6e40568312) | Sep 30, 2024 |
| ASRock        | B560M-HDV R3.0              | [dbc73513c7](https://linux-hardware.org/?probe=dbc73513c7) | Sep 26, 2024 |
| ASRock        | 970 Extreme3 R2.0           | [d174717db9](https://linux-hardware.org/?probe=d174717db9) | Sep 24, 2024 |
| Dell          | 0HV8FN A01                  | [c38e664bd9](https://linux-hardware.org/?probe=c38e664bd9) | Sep 24, 2024 |
| Gigabyte      | B85M-DS3H-A                 | [bd491cf784](https://linux-hardware.org/?probe=bd491cf784) | Sep 17, 2024 |
| Tianbei       | GEM12                       | [54f3a3e92b](https://linux-hardware.org/?probe=54f3a3e92b) | Aug 26, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [a4c99bb5b1](https://linux-hardware.org/?probe=a4c99bb5b1) | Aug 25, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [7b3e825580](https://linux-hardware.org/?probe=7b3e825580) | Aug 25, 2024 |
| IBM           | 8141KB4                     | [237b1f38c6](https://linux-hardware.org/?probe=237b1f38c6) | Aug 22, 2024 |
| IBM           | 8141KB4                     | [374425afb5](https://linux-hardware.org/?probe=374425afb5) | Aug 22, 2024 |
| ASUSTek       | TUF Gaming Z790-PRO WIFI    | [643af9216f](https://linux-hardware.org/?probe=643af9216f) | Aug 13, 2024 |
| ASUSTek       | TUF Gaming Z790-PRO WIFI    | [48403b988f](https://linux-hardware.org/?probe=48403b988f) | Aug 13, 2024 |
| ASUSTek       | Z97-PRO GAMER               | [3015220143](https://linux-hardware.org/?probe=3015220143) | Jul 30, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | [3875e7577b](https://linux-hardware.org/?probe=3875e7577b) | Jul 20, 2024 |
| ASRock        | Z370 Extreme4               | [514a57e9b4](https://linux-hardware.org/?probe=514a57e9b4) | Jul 16, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1c7ebc3219](https://linux-hardware.org/?probe=1c7ebc3219) | Jul 10, 2024 |
| MSI           | H81M-P33                    | [c512e9b284](https://linux-hardware.org/?probe=c512e9b284) | Jul 06, 2024 |
| ASUSTek       | PRIME B350M-A               | [57743d100f](https://linux-hardware.org/?probe=57743d100f) | Jun 15, 2024 |
| ASUSTek       | H81M-K                      | [4606b35d59](https://linux-hardware.org/?probe=4606b35d59) | Jun 07, 2024 |
| ASRock        | B660M PG Riptide            | [0eb75d61c6](https://linux-hardware.org/?probe=0eb75d61c6) | May 22, 2024 |
| Dell          | 0G3HR7 A00                  | [8e85e2f4cb](https://linux-hardware.org/?probe=8e85e2f4cb) | May 20, 2024 |
| Gigabyte      | Z790M AORUS ELITE AX        | [b6b53361f3](https://linux-hardware.org/?probe=b6b53361f3) | May 19, 2024 |
| ASRock        | X299 Professional Gaming... | [50e9d2967d](https://linux-hardware.org/?probe=50e9d2967d) | May 16, 2024 |
| AZW           | GTR V11                     | [4f36eb5740](https://linux-hardware.org/?probe=4f36eb5740) | May 11, 2024 |
| Huanan        | X99-TF                      | [804eb7916a](https://linux-hardware.org/?probe=804eb7916a) | May 05, 2024 |
| HP            | 2B2C                        | [082d220d35](https://linux-hardware.org/?probe=082d220d35) | May 04, 2024 |
| HP            | 158B                        | [38acb31ca9](https://linux-hardware.org/?probe=38acb31ca9) | Apr 24, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [ba12ac8498](https://linux-hardware.org/?probe=ba12ac8498) | Apr 17, 2024 |
| HP            | 158B                        | [d7c58cf079](https://linux-hardware.org/?probe=d7c58cf079) | Apr 09, 2024 |
| TSINGHUA T... | B560M-J01 V0.2              | [85ca1b62a7](https://linux-hardware.org/?probe=85ca1b62a7) | Apr 09, 2024 |
| Dell          | 02J54D A01                  | [28dc6c5c06](https://linux-hardware.org/?probe=28dc6c5c06) | Apr 01, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b4b14726e3](https://linux-hardware.org/?probe=b4b14726e3) | Mar 23, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [2b17261b3a](https://linux-hardware.org/?probe=2b17261b3a) | Mar 23, 2024 |
| Gigabyte      | B360HD3                     | [a82720d3a4](https://linux-hardware.org/?probe=a82720d3a4) | Mar 18, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | [ec5e2c689a](https://linux-hardware.org/?probe=ec5e2c689a) | Mar 13, 2024 |
| Huanan        | X99-TF                      | [edb2ac80c9](https://linux-hardware.org/?probe=edb2ac80c9) | Mar 04, 2024 |
| MSI           | MEG Z790 ACE                | [0137944d6c](https://linux-hardware.org/?probe=0137944d6c) | Feb 22, 2024 |
| Unknown       | Unknown                     | [aa24b40efa](https://linux-hardware.org/?probe=aa24b40efa) | Feb 19, 2024 |
| Unknown       | Unknown                     | [e9ad690ec9](https://linux-hardware.org/?probe=e9ad690ec9) | Feb 19, 2024 |
| ASUSTek       | Rampage II Extreme          | [42f4db38c2](https://linux-hardware.org/?probe=42f4db38c2) | Feb 16, 2024 |
| Unknown       | Unknown                     | [255d81b8e9](https://linux-hardware.org/?probe=255d81b8e9) | Feb 15, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [140a2db49b](https://linux-hardware.org/?probe=140a2db49b) | Feb 03, 2024 |
| ASRock        | X300-ITX                    | [3390b15018](https://linux-hardware.org/?probe=3390b15018) | Feb 02, 2024 |
| HP            | 8B3C A                      | [12ec418267](https://linux-hardware.org/?probe=12ec418267) | Jan 31, 2024 |
| MSI           | MAG B550M BAZOOKA           | [c0d98503dd](https://linux-hardware.org/?probe=c0d98503dd) | Jan 29, 2024 |
| Unknown       | Unknown                     | [2bf1eac05d](https://linux-hardware.org/?probe=2bf1eac05d) | Jan 27, 2024 |
| ASRock        | B650M PG Riptide            | [1ebf8a3fea](https://linux-hardware.org/?probe=1ebf8a3fea) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [53b28fea12](https://linux-hardware.org/?probe=53b28fea12) | Jan 21, 2024 |
| Unknown       | Unknown                     | [413fbae0c9](https://linux-hardware.org/?probe=413fbae0c9) | Jan 17, 2024 |
| Unknown       | Unknown                     | [69d393fc55](https://linux-hardware.org/?probe=69d393fc55) | Jan 17, 2024 |
| Gigabyte      | G41M-Combo                  | [e34d332260](https://linux-hardware.org/?probe=e34d332260) | Jan 10, 2024 |
| Dell          | 0VNM11 A00                  | [060cdd6c04](https://linux-hardware.org/?probe=060cdd6c04) | Jan 04, 2024 |
| MSI           | B450M MORTAR MAX            | [0c20bdae04](https://linux-hardware.org/?probe=0c20bdae04) | Dec 31, 2023 |
| MSI           | B450M MORTAR MAX            | [d6622a2c0a](https://linux-hardware.org/?probe=d6622a2c0a) | Dec 31, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [0daa9bd3eb](https://linux-hardware.org/?probe=0daa9bd3eb) | Dec 29, 2023 |
| Dell          | 0PJDGF A02                  | [cfdd125cd5](https://linux-hardware.org/?probe=cfdd125cd5) | Dec 19, 2023 |
| Dell          | 0PJDGF A02                  | [edcd06b95f](https://linux-hardware.org/?probe=edcd06b95f) | Dec 19, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [c6fa46e494](https://linux-hardware.org/?probe=c6fa46e494) | Dec 17, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [ebfb65701f](https://linux-hardware.org/?probe=ebfb65701f) | Dec 14, 2023 |
| Huanan        | X99-TF                      | [2bf94ff272](https://linux-hardware.org/?probe=2bf94ff272) | Dec 13, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [c4de324273](https://linux-hardware.org/?probe=c4de324273) | Dec 12, 2023 |
| Huanan        | X99-TF                      | [c617461c74](https://linux-hardware.org/?probe=c617461c74) | Dec 03, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [940148ec06](https://linux-hardware.org/?probe=940148ec06) | Dec 01, 2023 |
| Intel         | SKYBAY                      | [f802b552c5](https://linux-hardware.org/?probe=f802b552c5) | Nov 29, 2023 |
| Intel         | SKYBAY                      | [914eab8268](https://linux-hardware.org/?probe=914eab8268) | Nov 28, 2023 |
| Intel         | SKYBAY                      | [3e3de1a647](https://linux-hardware.org/?probe=3e3de1a647) | Nov 27, 2023 |
| Intel         | SKYBAY                      | [9d55b4f75f](https://linux-hardware.org/?probe=9d55b4f75f) | Nov 27, 2023 |
| Unknown       | Unknown                     | [3ccba31903](https://linux-hardware.org/?probe=3ccba31903) | Nov 27, 2023 |
| Intel         | SKYBAY                      | [21f1b67acc](https://linux-hardware.org/?probe=21f1b67acc) | Nov 24, 2023 |
| Unknown       | Unknown                     | [47bf46db9d](https://linux-hardware.org/?probe=47bf46db9d) | Nov 24, 2023 |
| Unknown       | Unknown                     | [e62a5fc1bc](https://linux-hardware.org/?probe=e62a5fc1bc) | Nov 24, 2023 |
| Intel         | SKYBAY                      | [03d84cbd00](https://linux-hardware.org/?probe=03d84cbd00) | Nov 24, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [bdbde84396](https://linux-hardware.org/?probe=bdbde84396) | Nov 18, 2023 |
| HPE           | ProLiant MicroServer Gen... | [7461a3b207](https://linux-hardware.org/?probe=7461a3b207) | Nov 08, 2023 |
| Unknown       | Unknown                     | [5c2d84d61d](https://linux-hardware.org/?probe=5c2d84d61d) | Nov 06, 2023 |
| Unknown       | Unknown                     | [e84ce1e0d3](https://linux-hardware.org/?probe=e84ce1e0d3) | Nov 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [37aa104ebf](https://linux-hardware.org/?probe=37aa104ebf) | Nov 06, 2023 |
| Intel         | X79 V1.0                    | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [b2c5bb3ed9](https://linux-hardware.org/?probe=b2c5bb3ed9) | Nov 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [650d69cdce](https://linux-hardware.org/?probe=650d69cdce) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [6e87d140be](https://linux-hardware.org/?probe=6e87d140be) | Oct 25, 2023 |
| MSI           | PRO B760M-P DDR4            | [23f0d88b97](https://linux-hardware.org/?probe=23f0d88b97) | Oct 20, 2023 |
| Gigabyte      | B150M-HD3-CF                | [6f431b83bd](https://linux-hardware.org/?probe=6f431b83bd) | Oct 08, 2023 |
| Gigabyte      | B150M-HD3-CF                | [e524ccbf1b](https://linux-hardware.org/?probe=e524ccbf1b) | Oct 07, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [ca79f8ce4c](https://linux-hardware.org/?probe=ca79f8ce4c) | Oct 04, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [f4f3555c2b](https://linux-hardware.org/?probe=f4f3555c2b) | Oct 03, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [9b86a89bf4](https://linux-hardware.org/?probe=9b86a89bf4) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [08989d4bba](https://linux-hardware.org/?probe=08989d4bba) | Sep 21, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [6d0e6a863d](https://linux-hardware.org/?probe=6d0e6a863d) | Sep 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [07d34fd9b5](https://linux-hardware.org/?probe=07d34fd9b5) | Sep 18, 2023 |
| Gigabyte      | H55N-USB3                   | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| Shenzhen M... | HX90G                       | [fda84a9c7c](https://linux-hardware.org/?probe=fda84a9c7c) | Sep 10, 2023 |
| Dell          | 0VNM11 A00                  | [e448e177d3](https://linux-hardware.org/?probe=e448e177d3) | Aug 21, 2023 |
| ASRock        | Q1900-ITX                   | [2c60ec2f95](https://linux-hardware.org/?probe=2c60ec2f95) | Aug 17, 2023 |
| ASRock        | Q1900-ITX                   | [b4a64727f4](https://linux-hardware.org/?probe=b4a64727f4) | Aug 14, 2023 |
| Dell          | 0VNM11 A00                  | [71cd1ddbf5](https://linux-hardware.org/?probe=71cd1ddbf5) | Aug 13, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [cf233e5568](https://linux-hardware.org/?probe=cf233e5568) | Aug 13, 2023 |
| ASRock        | X300M-STX                   | [e43da17360](https://linux-hardware.org/?probe=e43da17360) | Jul 29, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [8c8e7f5edd](https://linux-hardware.org/?probe=8c8e7f5edd) | Jul 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c5475d0982](https://linux-hardware.org/?probe=c5475d0982) | Jul 18, 2023 |
| MSI           | B250M PRO-VDH               | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [8a5ddbbafc](https://linux-hardware.org/?probe=8a5ddbbafc) | Jul 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a57586f69b](https://linux-hardware.org/?probe=a57586f69b) | Jul 01, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| BESSTAR Te... | B550                        | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8a9a60ca4d](https://linux-hardware.org/?probe=8a9a60ca4d) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [eaca61c801](https://linux-hardware.org/?probe=eaca61c801) | Jun 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c536181b6a](https://linux-hardware.org/?probe=c536181b6a) | Jun 14, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| HP            | 83E2                        | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| HP            | 1632                        | [ed47689eec](https://linux-hardware.org/?probe=ed47689eec) | May 22, 2023 |
| Dell          | 0N0992 A01                  | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| Gigabyte      | X570S AERO G                | [30e0bd8317](https://linux-hardware.org/?probe=30e0bd8317) | Apr 02, 2023 |
| MSI           | B450 TOMAHAWK               | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [601836815c](https://linux-hardware.org/?probe=601836815c) | Feb 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [c1936488f5](https://linux-hardware.org/?probe=c1936488f5) | Feb 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [ee4e2b3cde](https://linux-hardware.org/?probe=ee4e2b3cde) | Feb 19, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [81c1e35182](https://linux-hardware.org/?probe=81c1e35182) | Jan 24, 2023 |
| Gigabyte      | H97N-WIFI                   | [a18f404d39](https://linux-hardware.org/?probe=a18f404d39) | Jan 17, 2023 |
| ASUSTek       | M4A78                       | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| Dell          | 042P49 A02                  | [dc81fac0f7](https://linux-hardware.org/?probe=dc81fac0f7) | Jan 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [895a345eb9](https://linux-hardware.org/?probe=895a345eb9) | Nov 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [9d9d3a4967](https://linux-hardware.org/?probe=9d9d3a4967) | Nov 02, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| ASRock        | H470M-STX                   | [02f3177542](https://linux-hardware.org/?probe=02f3177542) | Oct 26, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [ce7a9a3171](https://linux-hardware.org/?probe=ce7a9a3171) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| ASRock        | AB350M Pro4                 | [6207d55486](https://linux-hardware.org/?probe=6207d55486) | Oct 05, 2022 |
| MSI           | B75MA-E33                   | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| HP            | 18E7                        | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| ASUSTek       | PRIME B660M-K D4            | [e939330716](https://linux-hardware.org/?probe=e939330716) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | [822d20fcdb](https://linux-hardware.org/?probe=822d20fcdb) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | [92f244ac1c](https://linux-hardware.org/?probe=92f244ac1c) | Sep 25, 2022 |
| MSI           | H81M-P33                    | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| ASRock        | H97M Anniversary            | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| ASRock        | Z490 PG Velocita            | [eac045585b](https://linux-hardware.org/?probe=eac045585b) | Sep 23, 2022 |
| Huanan        | X99-TF                      | [657d78e891](https://linux-hardware.org/?probe=657d78e891) | Sep 21, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Dell          | 0427JK A00                  | [8f6a2c8d0b](https://linux-hardware.org/?probe=8f6a2c8d0b) | Aug 22, 2022 |
| Dell          | 0200DY A03                  | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [bd7c6f361d](https://linux-hardware.org/?probe=bd7c6f361d) | Aug 18, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [56ba58f5d0](https://linux-hardware.org/?probe=56ba58f5d0) | Aug 16, 2022 |
| ASRock        | B450M-HDV R4.0              | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| Huanan        | X99-TF                      | [55b43de5a6](https://linux-hardware.org/?probe=55b43de5a6) | Jul 17, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Huanan        | X99-TF                      | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Huanan        | X99-TF                      | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| Gigabyte      | HA65M-UD3H-B3               | [d368918a0b](https://linux-hardware.org/?probe=d368918a0b) | May 13, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| MSI           | H87I                        | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [0633ac7757](https://linux-hardware.org/?probe=0633ac7757) | Apr 26, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [56902c7998](https://linux-hardware.org/?probe=56902c7998) | Apr 26, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| ASUSTek       | VM62                        | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| ASRock        | H410M-ITX/ac                | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| MSI           | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Dell          | 0Y3R3K A03                  | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| ASUSTek       | PRIME Z590-A                | [7320ed668a](https://linux-hardware.org/?probe=7320ed668a) | Mar 12, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [99d3e16ede](https://linux-hardware.org/?probe=99d3e16ede) | Mar 12, 2022 |
| Unknown       | Intel X79                   | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [0b9a7acb84](https://linux-hardware.org/?probe=0b9a7acb84) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell          | 0Y5DDC A00                  | [3c7daed552](https://linux-hardware.org/?probe=3c7daed552) | Feb 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6e5689a733](https://linux-hardware.org/?probe=6e5689a733) | Jan 28, 2022 |
| ASRock        | Z270M-ITX/ac                | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| HP            | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [c5fa4a0cec](https://linux-hardware.org/?probe=c5fa4a0cec) | Dec 24, 2021 |
| ASRock        | H410M-ITX/ac                | [99c341562a](https://linux-hardware.org/?probe=99c341562a) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| MSI           | 870-G45                     | [e6317a2b91](https://linux-hardware.org/?probe=e6317a2b91) | Dec 19, 2021 |
| Unknown       | Intel X79                   | [985655e4b3](https://linux-hardware.org/?probe=985655e4b3) | Dec 11, 2021 |
| Unknown       | Intel X79                   | [6f32192557](https://linux-hardware.org/?probe=6f32192557) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| MSI           | Boston                      | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| Supermicro    | C2SBC-Q                     | [1099e48366](https://linux-hardware.org/?probe=1099e48366) | Nov 28, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Gigabyte      | H310M S2H x.x               | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [35b58ec233](https://linux-hardware.org/?probe=35b58ec233) | Nov 16, 2021 |
| Seco          | C40 C                       | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [9bcd3d5479](https://linux-hardware.org/?probe=9bcd3d5479) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [aedfc53de6](https://linux-hardware.org/?probe=aedfc53de6) | Oct 20, 2021 |
| MSI           | H61M-P23                    | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| MSI           | MEG X570 GODLIKE            | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| Gigabyte      | B365M GAMING HD             | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [5cd377c0e0](https://linux-hardware.org/?probe=5cd377c0e0) | Aug 13, 2021 |
| Gigabyte      | B75M-D2P                    | [5e54c2a102](https://linux-hardware.org/?probe=5e54c2a102) | Aug 12, 2021 |
| HP            | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | H410M-HDV                   | [58b70e282d](https://linux-hardware.org/?probe=58b70e282d) | Jul 14, 2021 |
| Gigabyte      | B365M GAMING HD             | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [71da4978c9](https://linux-hardware.org/?probe=71da4978c9) | Jun 29, 2021 |
| Gigabyte      | B365M GAMING HD             | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Gigabyte      | B365M GAMING HD             | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z390-P                | [54e520ac17](https://linux-hardware.org/?probe=54e520ac17) | Jun 17, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| ASRock        | H410M-HDV                   | [bcb80080a5](https://linux-hardware.org/?probe=bcb80080a5) | Jun 06, 2021 |
| HP            | 18E7                        | [9844f6635c](https://linux-hardware.org/?probe=9844f6635c) | May 30, 2021 |
| ASUSTek       | VM62                        | [486aeb5b89](https://linux-hardware.org/?probe=486aeb5b89) | May 25, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| Dell          | 0D02VH A01                  | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| ASUSTek       | PRIME X399-A                | [a201bdfc36](https://linux-hardware.org/?probe=a201bdfc36) | May 19, 2021 |
| ASUSTek       | M4A78-VM                    | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| ASUSTek       | Z8NA-D6                     | [1b777c6f08](https://linux-hardware.org/?probe=1b777c6f08) | May 02, 2021 |
| ASUSTek       | Z8NA-D6                     | [4c7956a34c](https://linux-hardware.org/?probe=4c7956a34c) | May 02, 2021 |
| MSI           | Boston                      | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| HP            | 1632                        | [adf9ebb679](https://linux-hardware.org/?probe=adf9ebb679) | Mar 25, 2021 |
| MSI           | B450I GAMING PLUS AC        | [6a4196e0aa](https://linux-hardware.org/?probe=6a4196e0aa) | Mar 23, 2021 |
| MSI           | B450M-A PRO MAX             | [dc64c81c35](https://linux-hardware.org/?probe=dc64c81c35) | Mar 23, 2021 |
| ASUSTek       | B85M-G R2.0                 | [71ef988016](https://linux-hardware.org/?probe=71ef988016) | Mar 21, 2021 |
| ASRock        | H410M-HDV                   | [e44a5ce779](https://linux-hardware.org/?probe=e44a5ce779) | Mar 14, 2021 |
| MSI           | Boston                      | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| ASUSTek       | P8H61-M LX PLUS             | [b94539c6dc](https://linux-hardware.org/?probe=b94539c6dc) | Mar 01, 2021 |
| ASUSTek       | B85M-G R2.0                 | [b2cb174b9a](https://linux-hardware.org/?probe=b2cb174b9a) | Mar 01, 2021 |
| Lenovo        | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| Dell          | 0D02VH A01                  | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| ASUSTek       | VM45                        | [03eeb85521](https://linux-hardware.org/?probe=03eeb85521) | Feb 21, 2021 |
| ASUSTek       | VM65-K                      | [6b97cf71eb](https://linux-hardware.org/?probe=6b97cf71eb) | Feb 18, 2021 |
| ASUSTek       | VM65-K                      | [4f0bcd1276](https://linux-hardware.org/?probe=4f0bcd1276) | Feb 17, 2021 |
| ASUSTek       | VM40B                       | [6c0bf22f39](https://linux-hardware.org/?probe=6c0bf22f39) | Feb 17, 2021 |
| Dell          | 0D02VH A01                  | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| Lenovo        | IdeaCentre K330             | [78ce34058b](https://linux-hardware.org/?probe=78ce34058b) | Feb 11, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [39bc70ca5d](https://linux-hardware.org/?probe=39bc70ca5d) | Jan 13, 2021 |
| ASRock        | H410M-HDV                   | [d2420f233b](https://linux-hardware.org/?probe=d2420f233b) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| Dell          | 0TP412                      | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [cf7386e848](https://linux-hardware.org/?probe=cf7386e848) | Dec 18, 2020 |
| ASUSTek       | H97M-PLUS                   | [1d6b7df7b4](https://linux-hardware.org/?probe=1d6b7df7b4) | Dec 08, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| Dell          | 0D02VH A01                  | [8309aa39cf](https://linux-hardware.org/?probe=8309aa39cf) | Nov 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | [37d5acae7d](https://linux-hardware.org/?probe=37d5acae7d) | Nov 27, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [97c485886b](https://linux-hardware.org/?probe=97c485886b) | Nov 25, 2020 |
| Dell          | 0D02VH A01                  | [8f55b945a1](https://linux-hardware.org/?probe=8f55b945a1) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [de597aa847](https://linux-hardware.org/?probe=de597aa847) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f5aa8c9150](https://linux-hardware.org/?probe=f5aa8c9150) | Nov 20, 2020 |
| ASUSTek       | H110I-PLUS                  | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| ASUSTek       | H97M-PLUS                   | [f90977870e](https://linux-hardware.org/?probe=f90977870e) | Nov 04, 2020 |
| Gigabyte      | Z370 HD3P-CF                | [1af7b2b551](https://linux-hardware.org/?probe=1af7b2b551) | Oct 13, 2020 |
| ASUSTek       | H110I-PLUS                  | [e292456297](https://linux-hardware.org/?probe=e292456297) | Sep 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e7b41f62a4](https://linux-hardware.org/?probe=e7b41f62a4) | Sep 14, 2020 |
| ASUSTek       | H110I-PLUS                  | [20bdbc68b7](https://linux-hardware.org/?probe=20bdbc68b7) | Sep 12, 2020 |
| ASUSTek       | H81M-E                      | [43b8c677bc](https://linux-hardware.org/?probe=43b8c677bc) | Sep 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Foxconn       | 2ADA                        | [24cad8bed5](https://linux-hardware.org/?probe=24cad8bed5) | Aug 28, 2020 |
| Foxconn       | 2ADA                        | [3d4c2a283d](https://linux-hardware.org/?probe=3d4c2a283d) | Aug 28, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [e27db6fb31](https://linux-hardware.org/?probe=e27db6fb31) | Aug 24, 2020 |
| HP            | 802E                        | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP            | 802E                        | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP            | 802E                        | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| Gigabyte      | B150M-D3H-CF                | [50dc692a9e](https://linux-hardware.org/?probe=50dc692a9e) | Jul 23, 2020 |
| Gigabyte      | Z170X-Gaming 5 Modified ... | [a62f520dc3](https://linux-hardware.org/?probe=a62f520dc3) | Jul 18, 2020 |
| MSI           | B450M MORTAR MAX            | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP            | 1998                        | [255863fefb](https://linux-hardware.org/?probe=255863fefb) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | [b159b440f2](https://linux-hardware.org/?probe=b159b440f2) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | [4181637bf3](https://linux-hardware.org/?probe=4181637bf3) | Jun 01, 2020 |
| Biostar       | H110MHC                     | [98d1029698](https://linux-hardware.org/?probe=98d1029698) | May 26, 2020 |
| ASUSTek       | B150M-C                     | [2229b866b3](https://linux-hardware.org/?probe=2229b866b3) | May 26, 2020 |
| ASUSTek       | H110I-PLUS                  | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| ASUSTek       | STRIX H270F GAMING          | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Dell          | 0C2KJT A00                  | [179a82277c](https://linux-hardware.org/?probe=179a82277c) | May 01, 2020 |
| MSI           | 2A9C                        | [23df26e5de](https://linux-hardware.org/?probe=23df26e5de) | Apr 25, 2020 |
| Acer          | Aspire XC-710 V:1.1         | [664ac5b85b](https://linux-hardware.org/?probe=664ac5b85b) | Apr 24, 2020 |
| MSI           | Boston                      | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| ASUSTek       | H110I-PLUS                  | [f504649d96](https://linux-hardware.org/?probe=f504649d96) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | [3916938374](https://linux-hardware.org/?probe=3916938374) | Apr 11, 2020 |
| Gigabyte      | Z87-HD3                     | [52a7dab5ac](https://linux-hardware.org/?probe=52a7dab5ac) | Apr 09, 2020 |
| ASUSTek       | H110I-PLUS                  | [9c72670aa1](https://linux-hardware.org/?probe=9c72670aa1) | Apr 05, 2020 |
| ASUSTek       | H110I-PLUS                  | [37fb7cae94](https://linux-hardware.org/?probe=37fb7cae94) | Mar 30, 2020 |
| MSI           | B360M FIRE                  | [8bb021d2a6](https://linux-hardware.org/?probe=8bb021d2a6) | Mar 27, 2020 |
| ASUSTek       | H110I-PLUS                  | [18b565a861](https://linux-hardware.org/?probe=18b565a861) | Mar 26, 2020 |
| ASUSTek       | H110I-PLUS                  | [abce376627](https://linux-hardware.org/?probe=abce376627) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | [e6860a26ae](https://linux-hardware.org/?probe=e6860a26ae) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | [5f2e14b65b](https://linux-hardware.org/?probe=5f2e14b65b) | Mar 16, 2020 |
| ASUSTek       | H110I-PLUS                  | [1bcf8a4701](https://linux-hardware.org/?probe=1bcf8a4701) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | [bd55777a4f](https://linux-hardware.org/?probe=bd55777a4f) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | [137262daa3](https://linux-hardware.org/?probe=137262daa3) | Mar 05, 2020 |
| ASUSTek       | H110I-PLUS                  | [047acafb1a](https://linux-hardware.org/?probe=047acafb1a) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | [e8315b1469](https://linux-hardware.org/?probe=e8315b1469) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | [04e5b85d84](https://linux-hardware.org/?probe=04e5b85d84) | Feb 28, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | [310ae04477](https://linux-hardware.org/?probe=310ae04477) | Feb 27, 2020 |
| ASUSTek       | H110I-PLUS                  | [046814376c](https://linux-hardware.org/?probe=046814376c) | Feb 20, 2020 |
| ASUSTek       | H110I-PLUS                  | [a417965167](https://linux-hardware.org/?probe=a417965167) | Feb 19, 2020 |
| Intel         | DH77DF AAG40293-301         | [ac00169b1c](https://linux-hardware.org/?probe=ac00169b1c) | Feb 14, 2020 |
| ASUSTek       | H110I-PLUS                  | [cef9a00862](https://linux-hardware.org/?probe=cef9a00862) | Feb 12, 2020 |
| ASUSTek       | H110I-PLUS                  | [dcc65f9ee3](https://linux-hardware.org/?probe=dcc65f9ee3) | Feb 11, 2020 |
| ASUSTek       | H110I-PLUS                  | [900a11f8b3](https://linux-hardware.org/?probe=900a11f8b3) | Feb 10, 2020 |
| Gigabyte      | GA-MA78GM-S2HP              | [20d5a3bd6a](https://linux-hardware.org/?probe=20d5a3bd6a) | Feb 01, 2020 |
| Gigabyte      | Z77N-WIFI                   | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Gigabyte      | P55A-UD3                    | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| ASUSTek       | Z8NA-D6                     | [b2d6dabaa7](https://linux-hardware.org/?probe=b2d6dabaa7) | Dec 23, 2019 |
| MSI           | X470 GAMING PRO CARBON      | [e3b6ce369a](https://linux-hardware.org/?probe=e3b6ce369a) | Dec 23, 2019 |
| Intel         | DZ68DB AAG27985-101         | [15f84fa3f2](https://linux-hardware.org/?probe=15f84fa3f2) | Oct 26, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | [3392a03f3c](https://linux-hardware.org/?probe=3392a03f3c) | Oct 03, 2019 |
| Gigabyte      | B150M-D3H-CF                | [4302e84025](https://linux-hardware.org/?probe=4302e84025) | Sep 24, 2019 |
| ASUSTek       | B150M-A                     | [e8ccb234ed](https://linux-hardware.org/?probe=e8ccb234ed) | Aug 30, 2019 |
| ASRock        | B75M R2.0                   | [1479826c17](https://linux-hardware.org/?probe=1479826c17) | Aug 28, 2019 |
| Hardkernel    | ODROID-H2                   | [26d6c60ad5](https://linux-hardware.org/?probe=26d6c60ad5) | Jul 06, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | [ea2ad2bc4d](https://linux-hardware.org/?probe=ea2ad2bc4d) | Jun 05, 2019 |
| Dell          | 0CRH6C A01                  | [23dcf2aff6](https://linux-hardware.org/?probe=23dcf2aff6) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | [61bb547684](https://linux-hardware.org/?probe=61bb547684) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | [8549b6dfd8](https://linux-hardware.org/?probe=8549b6dfd8) | Apr 08, 2019 |
| ASRock        | Z270 Killer SLI             | [a03ea38833](https://linux-hardware.org/?probe=a03ea38833) | Jul 06, 2018 |
| Gigabyte      | GA-M56S-S3                  | [17f0958960](https://linux-hardware.org/?probe=17f0958960) | Oct 06, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 22.04                 | 27       | 9.54%   |
| Ubuntu 20.04                 | 20       | 7.07%   |
| Arch Rolling                 | 20       | 7.07%   |
| Ubuntu 18.04                 | 13       | 4.59%   |
| Debian 11                    | 11       | 3.89%   |
| OpenMandriva 4.2             | 10       | 3.53%   |
| Debian 12                    | 10       | 3.53%   |
| Pop!_OS 22.04                | 8        | 2.83%   |
| Linux Mint 22.1              | 7        | 2.47%   |
| Ubuntu 24.04                 | 6        | 2.12%   |
| Ubuntu 16.04                 | 6        | 2.12%   |
| OpenMandriva 4.3             | 6        | 2.12%   |
| KDE neon 20.04               | 5        | 1.77%   |
| Ubuntu 19.10                 | 4        | 1.41%   |
| Fedora 35                    | 4        | 1.41%   |
| Ubuntu 23.10                 | 3        | 1.06%   |
| Ubuntu 23.04                 | 3        | 1.06%   |
| Ubuntu 20.10                 | 3        | 1.06%   |
| PostmarketOS Edge            | 3        | 1.06%   |
| ArcoLinux Rolling            | 3        | 1.06%   |
| Xubuntu 18.04                | 2        | 0.71%   |
| Ubuntu 25.04                 | 2        | 0.71%   |
| Ubuntu 21.10                 | 2        | 0.71%   |
| Ubuntu 19.04                 | 2        | 0.71%   |
| Slackware 15.0               | 2        | 0.71%   |
| Pop!_OS 20.10                | 2        | 0.71%   |
| Pika OS 4                    | 2        | 0.71%   |
| Parrot 4.9                   | 2        | 0.71%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.71%   |
| OpenMandriva 25.90           | 2        | 0.71%   |
| OpenMandriva 24.12           | 2        | 0.71%   |
| OpenMandriva 24.07           | 2        | 0.71%   |
| OpenMandriva 23.08           | 2        | 0.71%   |
| NixOS 25.05                  | 2        | 0.71%   |
| NixOS 24.05                  | 2        | 0.71%   |
| Manjaro 23.1.0               | 2        | 0.71%   |
| Linux Mint 22.2              | 2        | 0.71%   |
| Linux Mint 21.2              | 2        | 0.71%   |
| Gentoo 2.7                   | 2        | 0.71%   |
| Fedora 40                    | 2        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 87       | 32.46%  |
| OpenMandriva | 25       | 9.33%   |
| Debian       | 21       | 7.84%   |
| Arch         | 21       | 7.84%   |
| Fedora       | 17       | 6.34%   |
| Linux Mint   | 13       | 4.85%   |
| Pop!_OS      | 11       | 4.1%    |
| Manjaro      | 8        | 2.99%   |
| Kubuntu      | 5        | 1.87%   |
| KDE neon     | 5        | 1.87%   |
| NixOS        | 4        | 1.49%   |
| Slackware    | 3        | 1.12%   |
| PostmarketOS | 3        | 1.12%   |
| openSUSE     | 3        | 1.12%   |
| EndeavourOS  | 3        | 1.12%   |
| Elementary   | 3        | 1.12%   |
| CentOS       | 3        | 1.12%   |
| Bazzite      | 3        | 1.12%   |
| ArcoLinux    | 3        | 1.12%   |
| Zorin        | 2        | 0.75%   |
| Xubuntu      | 2        | 0.75%   |
| SteamOS      | 2        | 0.75%   |
| ROSA         | 2        | 0.75%   |
| Rocky Linux  | 2        | 0.75%   |
| Pikaos       | 2        | 0.75%   |
| Parrot       | 2        | 0.75%   |
| Kali         | 2        | 0.75%   |
| Gentoo       | 2        | 0.75%   |
| Deepin       | 2        | 0.75%   |
| Clear Linux  | 2        | 0.75%   |
| Ubuntu MATE  | 1        | 0.37%   |
| Lubuntu      | 1        | 0.37%   |
| Artix        | 1        | 0.37%   |
| Alpine       | 1        | 0.37%   |
| Aeon         | 1        | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.14-desktop-1omv4002    | 9        | 2.86%   |
| 5.16.7-desktop-1omv4003     | 6        | 1.9%    |
| 4.15.0-142-generic          | 6        | 1.9%    |
| 6.2.0-26-generic            | 4        | 1.27%   |
| 5.4.0-42-generic            | 3        | 0.95%   |
| 5.15.0-46-generic           | 3        | 0.95%   |
| 6.8.0-60-generic            | 2        | 0.63%   |
| 6.8.0-52-generic            | 2        | 0.63%   |
| 6.7.0-zen3-1.1-zen          | 2        | 0.63%   |
| 6.5.0-9-generic             | 2        | 0.63%   |
| 6.5.0-14-generic            | 2        | 0.63%   |
| 6.4.11-desktop-1omv2390     | 2        | 0.63%   |
| 6.2.0-39-generic            | 2        | 0.63%   |
| 6.2.0-33-generic            | 2        | 0.63%   |
| 6.2.0-20-generic            | 2        | 0.63%   |
| 6.14.2-desktop-3omv2590     | 2        | 0.63%   |
| 6.14.0-27-generic           | 2        | 0.63%   |
| 6.12.9-desktop-1omv2490     | 2        | 0.63%   |
| 6.1.1-arch1-1               | 2        | 0.63%   |
| 6.1.0-9-amd64               | 2        | 0.63%   |
| 5.5.0-1parrot1-amd64        | 2        | 0.63%   |
| 5.4.0-56-generic            | 2        | 0.63%   |
| 5.4.0-47-generic            | 2        | 0.63%   |
| 5.4.0-33-generic            | 2        | 0.63%   |
| 5.4.0-109-generic           | 2        | 0.63%   |
| 5.3.0-46-generic            | 2        | 0.63%   |
| 5.19.0-76051900-generic     | 2        | 0.63%   |
| 5.19.0-43-generic           | 2        | 0.63%   |
| 5.13.0-35-generic           | 2        | 0.63%   |
| 5.11.0-43-generic           | 2        | 0.63%   |
| 5.0.0-25-generic            | 2        | 0.63%   |
| 4.15.0-88-generic           | 2        | 0.63%   |
| 6.9.9-arch1-1               | 1        | 0.32%   |
| 6.9.7-desktop-1omv2490      | 1        | 0.32%   |
| 6.9.4-arch1-1               | 1        | 0.32%   |
| 6.9.0-2.ge4714c6-default    | 1        | 0.32%   |
| 6.8.9-A1-Bryan              | 1        | 0.32%   |
| 6.8.9-301.fsync.fc40.x86_64 | 1        | 0.32%   |
| 6.8.5-301.fc40.x86_64       | 1        | 0.32%   |
| 6.8.4-arch1-1               | 1        | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 20       | 6.67%   |
| 5.15.0  | 17       | 5.67%   |
| 4.15.0  | 13       | 4.33%   |
| 6.2.0   | 12       | 4%      |
| 6.1.0   | 12       | 4%      |
| 6.8.0   | 9        | 3%      |
| 5.8.0   | 9        | 3%      |
| 5.19.0  | 9        | 3%      |
| 5.10.14 | 9        | 3%      |
| 6.5.0   | 8        | 2.67%   |
| 5.3.0   | 7        | 2.33%   |
| 5.13.0  | 7        | 2.33%   |
| 5.11.0  | 7        | 2.33%   |
| 5.10.0  | 7        | 2.33%   |
| 5.16.7  | 6        | 2%      |
| 6.14.0  | 5        | 1.67%   |
| 6.12.9  | 5        | 1.67%   |
| 5.0.0   | 5        | 1.67%   |
| 6.11.0  | 4        | 1.33%   |
| 6.14.2  | 3        | 1%      |
| 6.1.1   | 3        | 1%      |
| 5.17.5  | 3        | 1%      |
| 4.18.0  | 3        | 1%      |
| 6.8.9   | 2        | 0.67%   |
| 6.7.0   | 2        | 0.67%   |
| 6.5.6   | 2        | 0.67%   |
| 6.4.11  | 2        | 0.67%   |
| 6.2.9   | 2        | 0.67%   |
| 6.16.0  | 2        | 0.67%   |
| 6.11.2  | 2        | 0.67%   |
| 6.0.0   | 2        | 0.67%   |
| 5.5.0   | 2        | 0.67%   |
| 5.14.14 | 2        | 0.67%   |
| 6.9.9   | 1        | 0.33%   |
| 6.9.7   | 1        | 0.33%   |
| 6.9.4   | 1        | 0.33%   |
| 6.9.0   | 1        | 0.33%   |
| 6.8.5   | 1        | 0.33%   |
| 6.8.4   | 1        | 0.33%   |
| 6.8.11  | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 26       | 8.81%   |
| 5.4     | 20       | 6.78%   |
| 5.10    | 20       | 6.78%   |
| 6.1     | 18       | 6.1%    |
| 6.2     | 16       | 5.42%   |
| 6.8     | 14       | 4.75%   |
| 4.15    | 13       | 4.41%   |
| 6.5     | 12       | 4.07%   |
| 6.12    | 11       | 3.73%   |
| 5.8     | 11       | 3.73%   |
| 5.19    | 11       | 3.73%   |
| 6.14    | 10       | 3.39%   |
| 5.16    | 9        | 3.05%   |
| 5.13    | 9        | 3.05%   |
| 5.11    | 8        | 2.71%   |
| 5.3     | 7        | 2.37%   |
| 6.6     | 6        | 2.03%   |
| 6.11    | 6        | 2.03%   |
| 5.0     | 5        | 1.69%   |
| 6.9     | 4        | 1.36%   |
| 6.4     | 4        | 1.36%   |
| 6.10    | 4        | 1.36%   |
| 6.0     | 4        | 1.36%   |
| 5.17    | 4        | 1.36%   |
| 5.14    | 4        | 1.36%   |
| 6.7     | 3        | 1.02%   |
| 6.16    | 3        | 1.02%   |
| 6.13    | 3        | 1.02%   |
| 5.9     | 3        | 1.02%   |
| 5.5     | 3        | 1.02%   |
| 5.18    | 3        | 1.02%   |
| 4.18    | 3        | 1.02%   |
| 6.3     | 2        | 0.68%   |
| 6.17    | 2        | 0.68%   |
| 6.15    | 2        | 0.68%   |
| 5.7     | 2        | 0.68%   |
| 5.6     | 2        | 0.68%   |
| 5.12    | 2        | 0.68%   |
| 6.18    | 1        | 0.34%   |
| 4.9     | 1        | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 250      | 96.9%   |
| i686    | 3        | 1.16%   |
| aarch64 | 3        | 1.16%   |
| riscv64 | 2        | 0.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 106      | 38.55%  |
| KDE5          | 48       | 17.45%  |
| Unknown       | 44       | 16%     |
| KDE6          | 22       | 8%      |
| X-Cinnamon    | 12       | 4.36%   |
| XFCE          | 11       | 4%      |
| KDE           | 6        | 2.18%   |
| MATE          | 4        | 1.45%   |
| Pantheon      | 3        | 1.09%   |
| sway          | 2        | 0.73%   |
| LXQt          | 2        | 0.73%   |
| i3            | 2        | 0.73%   |
| GNOME Classic | 2        | 0.73%   |
| DDE           | 2        | 0.73%   |
| openbox       | 1        | 0.36%   |
| none+bspwm    | 1        | 0.36%   |
| LXDE          | 1        | 0.36%   |
| KDE4          | 1        | 0.36%   |
| ICEWM         | 1        | 0.36%   |
| Hyprland      | 1        | 0.36%   |
| Deepin        | 1        | 0.36%   |
| Cinnamon      | 1        | 0.36%   |
| awesome       | 1        | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 173      | 63.6%   |
| Wayland | 68       | 25%     |
| Tty     | 19       | 6.99%   |
| Unknown | 12       | 4.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 110      | 41.04%  |
| SDDM    | 55       | 20.52%  |
| GDM3    | 49       | 18.28%  |
| LightDM | 27       | 10.07%  |
| GDM     | 20       | 7.46%   |
| TDM     | 2        | 0.75%   |
| Ly      | 2        | 0.75%   |
| XDM     | 1        | 0.37%   |
| KDM     | 1        | 0.37%   |
| GREETD  | 1        | 0.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 109      | 40.67%  |
| en_HK   | 73       | 27.24%  |
| zh_CN   | 32       | 11.94%  |
| zh_TW   | 15       | 5.6%    |
| Unknown | 14       | 5.22%   |
| C       | 9        | 3.36%   |
| en_GB   | 7        | 2.61%   |
| zh_HK   | 6        | 2.24%   |
| en_AU   | 2        | 0.75%   |
| zh_SG   | 1        | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 156      | 59.09%  |
| BIOS | 108      | 40.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 166      | 62.17%  |
| Btrfs   | 43       | 16.1%   |
| Tmpfs   | 23       | 8.61%   |
| Overlay | 18       | 6.74%   |
| Xfs     | 9        | 3.37%   |
| Zfs     | 3        | 1.12%   |
| Unknown | 2        | 0.75%   |
| F2fs    | 1        | 0.37%   |
| Ext3    | 1        | 0.37%   |
| Ext2    | 1        | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 151      | 57.41%  |
| Unknown | 94       | 35.74%  |
| MBR     | 18       | 6.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 220      | 81.48%  |
| Yes       | 50       | 18.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 179      | 67.55%  |
| Yes       | 86       | 32.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 62       | 24.03%  |
| Gigabyte Technology                  | 41       | 15.89%  |
| MSI                                  | 38       | 14.73%  |
| ASRock                               | 26       | 10.08%  |
| Dell                                 | 21       | 8.14%   |
| Unknown                              | 13       | 5.04%   |
| Lenovo                               | 11       | 4.26%   |
| Hewlett-Packard                      | 11       | 4.26%   |
| Intel                                | 8        | 3.1%    |
| Huanan                               | 4        | 1.55%   |
| TSINGHUA TONGFANG COMPUTER           | 2        | 0.78%   |
| Supermicro                           | 2        | 0.78%   |
| Acer                                 | 2        | 0.78%   |
| Tianbei                              | 1        | 0.39%   |
| Soyo                                 | 1        | 0.39%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.39%   |
| Seco                                 | 1        | 0.39%   |
| METAPHYUNI                           | 1        | 0.39%   |
| IBM                                  | 1        | 0.39%   |
| HPE                                  | 1        | 0.39%   |
| Hardkernel                           | 1        | 0.39%   |
| H3C                                  | 1        | 0.39%   |
| GMKtec                               | 1        | 0.39%   |
| GALAX                                | 1        | 0.39%   |
| Foxconn                              | 1        | 0.39%   |
| Colorful Technology                  | 1        | 0.39%   |
| Biostar                              | 1        | 0.39%   |
| BESSTAR Tech                         | 1        | 0.39%   |
| AZW                                  | 1        | 0.39%   |
| Apple                                | 1        | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 13       | 5.04%   |
| ASUS All Series                            | 6        | 2.33%   |
| Intel SKYBAY                               | 4        | 1.55%   |
| ASUS TUF Gaming B650M-E WIFI               | 3        | 1.16%   |
| ASUS H110I-PLUS                            | 3        | 1.16%   |
| TSINGHUA TONGFANG COMPUTER E500            | 2        | 0.78%   |
| MSI MS-7D42                                | 2        | 0.78%   |
| MSI MS-7C94                                | 2        | 0.78%   |
| MSI MS-7C02                                | 2        | 0.78%   |
| MSI MS-7B93                                | 2        | 0.78%   |
| MSI MS-7B89                                | 2        | 0.78%   |
| HP ProDesk 600 G1 SFF                      | 2        | 0.78%   |
| Gigabyte X570 AORUS ELITE                  | 2        | 0.78%   |
| ASUS Z8NA-D6                               | 2        | 0.78%   |
| ASUS VM65                                  | 2        | 0.78%   |
| ASUS VM62                                  | 2        | 0.78%   |
| ASRock H410M-ITX/ac                        | 2        | 0.78%   |
| ASRock H410M-HDV                           | 2        | 0.78%   |
| Tianbei GEM12                              | 1        | 0.39%   |
| Supermicro PIO-617R-TLN4F+-ST031           | 1        | 0.39%   |
| Supermicro C2SBC-Q                         | 1        | 0.39%   |
| Soyo SY-A68M FS V2.0                       | 1        | 0.39%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.39%   |
| Seco C40                                   | 1        | 0.39%   |
| MSI Pro 3130 Small Form Factor PC          | 1        | 0.39%   |
| MSI MS-7E62                                | 1        | 0.39%   |
| MSI MS-7E25                                | 1        | 0.39%   |
| MSI MS-7E03                                | 1        | 0.39%   |
| MSI MS-7E02                                | 1        | 0.39%   |
| MSI MS-7D86                                | 1        | 0.39%   |
| MSI MS-7D75                                | 1        | 0.39%   |
| MSI MS-7D73                                | 1        | 0.39%   |
| MSI MS-7D32                                | 1        | 0.39%   |
| MSI MS-7D31                                | 1        | 0.39%   |
| MSI MS-7C95                                | 1        | 0.39%   |
| MSI MS-7C67                                | 1        | 0.39%   |
| MSI MS-7C52                                | 1        | 0.39%   |
| MSI MS-7C34                                | 1        | 0.39%   |
| MSI MS-7C00                                | 1        | 0.39%   |
| MSI MS-7B78                                | 1        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 13       | 5.04%   |
| ASUS TUF                                   | 12       | 4.65%   |
| ASUS PRIME                                 | 12       | 4.65%   |
| Dell OptiPlex                              | 11       | 4.26%   |
| ASUS ROG                                   | 8        | 3.1%    |
| Lenovo ThinkCentre                         | 6        | 2.33%   |
| ASUS All                                   | 6        | 2.33%   |
| Intel SKYBAY                               | 4        | 1.55%   |
| HP ProDesk                                 | 3        | 1.16%   |
| Gigabyte X570                              | 3        | 1.16%   |
| Dell Precision                             | 3        | 1.16%   |
| ASUS H110I-PLUS                            | 3        | 1.16%   |
| TSINGHUA TONGFANG COMPUTER E500            | 2        | 0.78%   |
| MSI MS-7D42                                | 2        | 0.78%   |
| MSI MS-7C94                                | 2        | 0.78%   |
| MSI MS-7C02                                | 2        | 0.78%   |
| MSI MS-7B93                                | 2        | 0.78%   |
| MSI MS-7B89                                | 2        | 0.78%   |
| Huanan X99-F8D                             | 2        | 0.78%   |
| HP EliteDesk                               | 2        | 0.78%   |
| Gigabyte B550M                             | 2        | 0.78%   |
| Gigabyte B450                              | 2        | 0.78%   |
| Dell Vostro                                | 2        | 0.78%   |
| Dell Inspiron                              | 2        | 0.78%   |
| ASUS Z8NA-D6                               | 2        | 0.78%   |
| ASUS VM65                                  | 2        | 0.78%   |
| ASUS VM62                                  | 2        | 0.78%   |
| ASUS STRIX                                 | 2        | 0.78%   |
| ASRock H410M-ITX                           | 2        | 0.78%   |
| ASRock H410M-HDV                           | 2        | 0.78%   |
| Tianbei GEM12                              | 1        | 0.39%   |
| Supermicro PIO-617R-TLN4F+-ST031           | 1        | 0.39%   |
| Supermicro C2SBC-Q                         | 1        | 0.39%   |
| Soyo SY-A68M                               | 1        | 0.39%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.39%   |
| Seco C40                                   | 1        | 0.39%   |
| MSI Pro                                    | 1        | 0.39%   |
| MSI MS-7E62                                | 1        | 0.39%   |
| MSI MS-7E25                                | 1        | 0.39%   |
| MSI MS-7E03                                | 1        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 24       | 9.3%    |
| 2022    | 23       | 8.91%   |
| 2021    | 22       | 8.53%   |
| 2023    | 20       | 7.75%   |
| 2019    | 20       | 7.75%   |
| 2020    | 19       | 7.36%   |
| 2014    | 19       | 7.36%   |
| 2017    | 16       | 6.2%    |
| 2013    | 14       | 5.43%   |
| 2010    | 14       | 5.43%   |
| 2024    | 11       | 4.26%   |
| 2016    | 11       | 4.26%   |
| 2015    | 11       | 4.26%   |
| 2012    | 9        | 3.49%   |
| 2011    | 7        | 2.71%   |
| 2008    | 5        | 1.94%   |
| 2009    | 4        | 1.55%   |
| Unknown | 4        | 1.55%   |
| 2025    | 3        | 1.16%   |
| 2007    | 1        | 0.39%   |
| 2005    | 1        | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 258      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 239      | 92.64%  |
| Enabled  | 19       | 7.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 258      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 68       | 25.66%  |
| 16.01-24.0      | 55       | 20.75%  |
| 8.01-16.0       | 37       | 13.96%  |
| 64.01-256.0     | 35       | 13.21%  |
| 4.01-8.0        | 25       | 9.43%   |
| 3.01-4.0        | 22       | 8.3%    |
| 24.01-32.0      | 15       | 5.66%   |
| 1.01-2.0        | 3        | 1.13%   |
| 2.01-3.0        | 2        | 0.75%   |
| 0.51-1.0        | 2        | 0.75%   |
| More than 256.0 | 1        | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 65       | 22.49%  |
| 2.01-3.0   | 62       | 21.45%  |
| 1.01-2.0   | 62       | 21.45%  |
| 3.01-4.0   | 39       | 13.49%  |
| 8.01-16.0  | 23       | 7.96%   |
| 0.51-1.0   | 16       | 5.54%   |
| 16.01-24.0 | 10       | 3.46%   |
| 0.01-0.5   | 6        | 2.08%   |
| 32.01-64.0 | 4        | 1.38%   |
| 24.01-32.0 | 1        | 0.35%   |
| Unknown    | 1        | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 107      | 39.34%  |
| 2      | 76       | 27.94%  |
| 3      | 49       | 18.01%  |
| 4      | 14       | 5.15%   |
| 5      | 12       | 4.41%   |
| 6      | 4        | 1.47%   |
| 7      | 3        | 1.1%    |
| 0      | 3        | 1.1%    |
| 9      | 2        | 0.74%   |
| 11     | 1        | 0.37%   |
| 8      | 1        | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 202      | 77.1%   |
| Yes       | 60       | 22.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 252      | 97.67%  |
| No        | 6        | 2.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 142      | 53.99%  |
| No        | 121      | 46.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 134      | 50.76%  |
| Yes       | 130      | 49.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Hong Kong | 258      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Central           | 150      | 53.76%  |
| Kowloon           | 15       | 5.38%   |
| Hong Kong         | 14       | 5.02%   |
| Tuen Mun          | 10       | 3.58%   |
| Wanchai           | 9        | 3.23%   |
| Tseung Kwan O     | 6        | 2.15%   |
| Yuen Long         | 4        | 1.43%   |
| Shatin            | 4        | 1.43%   |
| Sham Shui Po      | 4        | 1.43%   |
| Ngau Wu Tok       | 4        | 1.43%   |
| To Kwa Wan        | 3        | 1.08%   |
| Tai Po            | 3        | 1.08%   |
| Ma On Shan Tsuen  | 3        | 1.08%   |
| Kwai Chung        | 3        | 1.08%   |
| Hung Hom          | 3        | 1.08%   |
| Tsuen Wan         | 2        | 0.72%   |
| Tsimshatsui       | 2        | 0.72%   |
| Quarry Bay        | 2        | 0.72%   |
| Kwun Tong         | 2        | 0.72%   |
| Kwun Hang         | 2        | 0.72%   |
| Kwu Tung          | 2        | 0.72%   |
| Ho Man Tin        | 2        | 0.72%   |
| Fo Tan            | 2        | 0.72%   |
| Cheung Sha Lan    | 2        | 0.72%   |
| Chai Wan          | 2        | 0.72%   |
| Yuen Long San Hui | 1        | 0.36%   |
| Wong Tai Sin      | 1        | 0.36%   |
| Tung Chung        | 1        | 0.36%   |
| Tin Shui Wai      | 1        | 0.36%   |
| Tai Wan To        | 1        | 0.36%   |
| Tai Wan           | 1        | 0.36%   |
| Tai Kok Tsui      | 1        | 0.36%   |
| Sheung Wan        | 1        | 0.36%   |
| Sheung Shui       | 1        | 0.36%   |
| Sha Tin Wai       | 1        | 0.36%   |
| Sai Kung          | 1        | 0.36%   |
| North Point       | 1        | 0.36%   |
| Mong Kok          | 1        | 0.36%   |
| Ma Wan            | 1        | 0.36%   |
| Ma On Shan        | 1        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 70       | 111    | 14.17%  |
| WDC                          | 65       | 101    | 13.16%  |
| Samsung Electronics          | 48       | 72     | 9.72%   |
| Toshiba                      | 33       | 52     | 6.68%   |
| SanDisk                      | 26       | 30     | 5.26%   |
| Kingston                     | 25       | 37     | 5.06%   |
| Crucial                      | 19       | 29     | 3.85%   |
| A-DATA Technology            | 16       | 23     | 3.24%   |
| Silicon Motion               | 12       | 18     | 2.43%   |
| Hitachi                      | 10       | 23     | 2.02%   |
| KIOXIA                       | 9        | 12     | 1.82%   |
| HGST                         | 9        | 11     | 1.82%   |
| SK hynix                     | 8        | 14     | 1.62%   |
| Unknown                      | 7        | 7      | 1.42%   |
| Unknown                      | 7        | 7      | 1.42%   |
| Plextor                      | 6        | 6      | 1.21%   |
| Transcend                    | 5        | 6      | 1.01%   |
| Phison                       | 5        | 8      | 1.01%   |
| Micron/Crucial Technology    | 5        | 5      | 1.01%   |
| Intel                        | 5        | 16     | 1.01%   |
| ZHITAI                       | 4        | 7      | 0.81%   |
| Phison Electronics           | 4        | 4      | 0.81%   |
| Netac                        | 4        | 4      | 0.81%   |
| Micron Technology            | 4        | 4      | 0.81%   |
| MAXIO Technology (Hangzhou)  | 4        | 5      | 0.81%   |
| LITEON                       | 4        | 4      | 0.81%   |
| Gigabyte Technology          | 4        | 8      | 0.81%   |
| Fujitsu                      | 4        | 9      | 0.81%   |
| SPCC                         | 3        | 3      | 0.61%   |
| JMicron Technology           | 3        | 6      | 0.61%   |
| Hikvision                    | 3        | 3      | 0.61%   |
| DOGGO                        | 3        | 3      | 0.61%   |
| China                        | 3        | 4      | 0.61%   |
| ADATA Technology             | 3        | 7      | 0.61%   |
| Team                         | 2        | 2      | 0.4%    |
| Shenzhen Longsys Electronics | 2        | 2      | 0.4%    |
| Realtek Semiconductor        | 2        | 3      | 0.4%    |
| Realtek                      | 2        | 2      | 0.4%    |
| Maxtor                       | 2        | 4      | 0.4%    |
| Lite-On Technology           | 2        | 3      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 7        | 1.3%    |
| Unknown                                               | 7        | 1.3%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 6        | 1.11%   |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 1.11%   |
| KIOXIA NVMe SSD 1TB                                   | 6        | 1.11%   |
| Kingston SA400S37480G 480GB SSD                       | 6        | 1.11%   |
| Toshiba DT01ACA050 500GB                              | 5        | 0.93%   |
| Samsung SSD 860 EVO 1TB                               | 5        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 5        | 0.93%   |
| A-DATA SP550 240GB SSD                                | 5        | 0.93%   |
| WDC WD20EZBX-00AYRA0 2TB                              | 4        | 0.74%   |
| Toshiba DT01ACA300 3TB                                | 4        | 0.74%   |
| Toshiba DT01ACA200 2TB                                | 4        | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB                        | 4        | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB                        | 4        | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 4        | 0.74%   |
| Kingston SA400S37960G 960GB SSD                       | 4        | 0.74%   |
| Crucial CT500MX500SSD1 500GB                          | 4        | 0.74%   |
| WDC WD30EZRX-00D8PB0 3TB                              | 3        | 0.56%   |
| WDC WD10EZEX-75WN4A1 1TB                              | 3        | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 3        | 0.56%   |
| Seagate ST3500418AS 500GB                             | 3        | 0.56%   |
| Seagate ST3500413AS 500GB                             | 3        | 0.56%   |
| Seagate ST3250318AS 250GB                             | 3        | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 0.56%   |
| Seagate ST1000DM003-1SB102 1TB                        | 3        | 0.56%   |
| Seagate ST1000DM003-1ER162 1TB                        | 3        | 0.56%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                 | 3        | 0.56%   |
| SanDisk NVMe SSD Drive 1TB                            | 3        | 0.56%   |
| Samsung SSD 980 1TB                                   | 3        | 0.56%   |
| Samsung SSD 860 EVO 500GB                             | 3        | 0.56%   |
| Kingston SA400S37240G 240GB SSD                       | 3        | 0.56%   |
| JMicron Generic 320GB                                 | 3        | 0.56%   |
| Fujitsu F300 480GB                                    | 3        | 0.56%   |
| DOGGO DQ-60G SSD                                      | 3        | 0.56%   |
| WDC WDS200T2B0A 2TB SSD                               | 2        | 0.37%   |
| WDC WD40EZAX-00C8UB0 4TB                              | 2        | 0.37%   |
| WDC WD30EZAZ-22SF3B0 3TB                              | 2        | 0.37%   |
| Toshiba MG10ACA20TE 20TB                              | 2        | 0.37%   |
| Toshiba MG05ACA800E 8TB                               | 2        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| Seagate            | 68       | 108    | 37.99%  |
| WDC                | 50       | 81     | 27.93%  |
| Toshiba            | 32       | 51     | 17.88%  |
| Hitachi            | 10       | 23     | 5.59%   |
| HGST               | 9        | 11     | 5.03%   |
| JMicron Technology | 3        | 6      | 1.68%   |
| Maxtor             | 2        | 4      | 1.12%   |
| Unknown            | 1        | 1      | 0.56%   |
| HGST HTS           | 1        | 1      | 0.56%   |
| Fujitsu            | 1        | 1      | 0.56%   |
| External           | 1        | 1      | 0.56%   |
| Apple              | 1        | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 35     | 17.14%  |
| Kingston            | 17       | 27     | 12.14%  |
| A-DATA Technology   | 13       | 20     | 9.29%   |
| Crucial             | 11       | 21     | 7.86%   |
| WDC                 | 10       | 11     | 7.14%   |
| SanDisk             | 6        | 6      | 4.29%   |
| Transcend           | 5        | 6      | 3.57%   |
| Plextor             | 5        | 5      | 3.57%   |
| Netac               | 4        | 4      | 2.86%   |
| SPCC                | 3        | 3      | 2.14%   |
| SK hynix            | 3        | 8      | 2.14%   |
| LITEON              | 3        | 3      | 2.14%   |
| Fujitsu             | 3        | 8      | 2.14%   |
| DOGGO               | 3        | 3      | 2.14%   |
| Team                | 2        | 2      | 1.43%   |
| China               | 2        | 3      | 1.43%   |
| ZOTAC               | 1        | 1      | 0.71%   |
| ZHITAI              | 1        | 1      | 0.71%   |
| WDC WDS2            | 1        | 1      | 0.71%   |
| Toshiba             | 1        | 1      | 0.71%   |
| tigo                | 1        | 1      | 0.71%   |
| Soyo                | 1        | 1      | 0.71%   |
| ShiJi               | 1        | 1      | 0.71%   |
| PNY                 | 1        | 1      | 0.71%   |
| Philips             | 1        | 1      | 0.71%   |
| Patriot             | 1        | 2      | 0.71%   |
| OCZ                 | 1        | 1      | 0.71%   |
| Micron Technology   | 1        | 1      | 0.71%   |
| MAXSUN              | 1        | 1      | 0.71%   |
| Lexar               | 1        | 1      | 0.71%   |
| Intel               | 1        | 3      | 0.71%   |
| Hikvision           | 1        | 1      | 0.71%   |
| GALAX               | 1        | 1      | 0.71%   |
| G537N               | 1        | 1      | 0.71%   |
| Dogfish             | 1        | 1      | 0.71%   |
| Corsair             | 1        | 1      | 0.71%   |
| Colorful            | 1        | 1      | 0.71%   |
| Asgard              | 1        | 1      | 0.71%   |
| Apacer              | 1        | 3      | 0.71%   |
| Aoluska             | 1        | 1      | 0.71%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 149      | 289    | 35.82%  |
| NVMe    | 131      | 230    | 31.49%  |
| SSD     | 120      | 196    | 28.85%  |
| Unknown | 13       | 14     | 3.13%   |
| MMC     | 3        | 3      | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 199      | 466    | 55.74%  |
| NVMe | 131      | 227    | 36.69%  |
| SAS  | 24       | 36     | 6.72%   |
| MMC  | 3        | 3      | 0.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 120      | 215    | 42.86%  |
| 0.51-1.0   | 77       | 115    | 27.5%   |
| 1.01-2.0   | 34       | 49     | 12.14%  |
| 3.01-4.0   | 17       | 41     | 6.07%   |
| 2.01-3.0   | 16       | 28     | 5.71%   |
| 4.01-10.0  | 12       | 30     | 4.29%   |
| 10.01-20.0 | 4        | 7      | 1.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 49       | 17.69%  |
| 101-250        | 48       | 17.33%  |
| 251-500        | 36       | 13%     |
| 501-1000       | 34       | 12.27%  |
| 1001-2000      | 31       | 11.19%  |
| 51-100         | 22       | 7.94%   |
| 2001-3000      | 18       | 6.5%    |
| 1-20           | 17       | 6.14%   |
| Unknown        | 14       | 5.05%   |
| 21-50          | 8        | 2.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 93       | 31.53%  |
| 101-250        | 38       | 12.88%  |
| 21-50          | 29       | 9.83%   |
| 501-1000       | 28       | 9.49%   |
| 251-500        | 25       | 8.47%   |
| 51-100         | 23       | 7.8%    |
| 1001-2000      | 19       | 6.44%   |
| Unknown        | 14       | 4.75%   |
| More than 3000 | 13       | 4.41%   |
| 2001-3000      | 13       | 4.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Desktops | Drives | Percent |
|-----------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB               | 3        | 4      | 9.68%   |
| Seagate ST3500418AS 500GB                     | 2        | 3      | 6.45%   |
| ZHITAI TiPlus5000 512GB                       | 1        | 1      | 3.23%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD              | 1        | 1      | 3.23%   |
| WDC WD5003ABYX-18WERA0 500GB                  | 1        | 1      | 3.23%   |
| WDC WD30EZRX-00D8PB0 3TB                      | 1        | 1      | 3.23%   |
| WDC WD10EZEX-60WN4A1 1TB                      | 1        | 1      | 3.23%   |
| WDC WD10EZEX-00RKKA0 1TB                      | 1        | 1      | 3.23%   |
| WDC WD10EALS-00Z8A0 1TB                       | 1        | 2      | 3.23%   |
| Toshiba MK1655GSX 160GB                       | 1        | 1      | 3.23%   |
| Toshiba MK1252GSX 120GB                       | 1        | 1      | 3.23%   |
| Toshiba DT01ACA100 1TB                        | 1        | 2      | 3.23%   |
| Seagate ST3640323AS 640GB                     | 1        | 1      | 3.23%   |
| Seagate ST3250318AS 250GB                     | 1        | 1      | 3.23%   |
| Seagate ST3250310AS 250GB                     | 1        | 1      | 3.23%   |
| Seagate ST3160815AS 160GB                     | 1        | 1      | 3.23%   |
| Seagate ST2000VX002-1AH166 2TB                | 1        | 1      | 3.23%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB           | 1        | 1      | 3.23%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB  | 1        | 1      | 3.23%   |
| Realtek Semiconductor ADATA SWORDFISH 250GB   | 1        | 2      | 3.23%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD     | 1        | 1      | 3.23%   |
| Lite-On Technology M8Pe Series NVMe SSD 256GB | 1        | 1      | 3.23%   |
| Kingston SA400S37480G 480GB SSD               | 1        | 1      | 3.23%   |
| Intel SSDPEKKW128G7 128GB                     | 1        | 1      | 3.23%   |
| Intel SSD 600P Series 1024GB                  | 1        | 4      | 3.23%   |
| Hitachi HTS542512K9SA00 120GB                 | 1        | 1      | 3.23%   |
| HGST HTS 541010A9E680 1TB                     | 1        | 1      | 3.23%   |
| Crucial CT500MX500SSD1 500GB                  | 1        | 2      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 11       | 13     | 36.67%  |
| WDC                   | 5        | 7      | 16.67%  |
| Toshiba               | 3        | 4      | 10%     |
| Intel                 | 2        | 5      | 6.67%   |
| ZHITAI                | 1        | 1      | 3.33%   |
| Samsung Electronics   | 1        | 1      | 3.33%   |
| Realtek Semiconductor | 1        | 2      | 3.33%   |
| LITEON                | 1        | 1      | 3.33%   |
| Lite-On Technology    | 1        | 1      | 3.33%   |
| Kingston              | 1        | 1      | 3.33%   |
| Hitachi               | 1        | 1      | 3.33%   |
| HGST HTS              | 1        | 1      | 3.33%   |
| Crucial               | 1        | 2      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 11       | 13     | 55%     |
| WDC      | 4        | 6      | 20%     |
| Toshiba  | 3        | 4      | 15%     |
| Hitachi  | 1        | 1      | 5%      |
| HGST HTS | 1        | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 25     | 65.52%  |
| NVMe | 6        | 10     | 20.69%  |
| SSD  | 4        | 5      | 13.79%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 139      | 355    | 46.64%  |
| Works    | 130      | 337    | 43.62%  |
| Malfunc  | 29       | 40     | 9.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel                                   | 178      | 40.92%  |
| AMD                                     | 66       | 15.17%  |
| Samsung Electronics                     | 30       | 6.9%    |
| SanDisk                                 | 25       | 5.75%   |
| ASMedia Technology                      | 21       | 4.83%   |
| Silicon Motion                          | 14       | 3.22%   |
| Phison Electronics                      | 14       | 3.22%   |
| Micron/Crucial Technology               | 12       | 2.76%   |
| KIOXIA                                  | 10       | 2.3%    |
| Kingston Technology Company             | 10       | 2.3%    |
| MAXIO Technology (Hangzhou)             | 6        | 1.38%   |
| ADATA Technology                        | 6        | 1.38%   |
| Yangtze Memory Technologies             | 5        | 1.15%   |
| SK hynix                                | 5        | 1.15%   |
| Micron Technology                       | 4        | 0.92%   |
| Marvell Technology Group                | 4        | 0.92%   |
| Lite-On Technology                      | 3        | 0.69%   |
| JMicron Technology                      | 3        | 0.69%   |
| Solidigm                                | 2        | 0.46%   |
| Shenzhen Longsys Electronics            | 2        | 0.46%   |
| Seagate Technology                      | 2        | 0.46%   |
| Realtek Semiconductor                   | 2        | 0.46%   |
| LSI Logic / Symbios Logic               | 2        | 0.46%   |
| Integrated Technology Express           | 2        | 0.46%   |
| INNOGRIT                                | 2        | 0.46%   |
| VIA Technologies                        | 1        | 0.23%   |
| Shenzhen Unionmemory Information System | 1        | 0.23%   |
| Shenzhen Shichuangyi Electronics        | 1        | 0.23%   |
| Nvidia                                  | 1        | 0.23%   |
| Broadcom / LSI                          | 1        | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 27       | 5.5%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 23       | 4.68%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 19       | 3.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 18       | 3.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 17       | 3.46%   |
| AMD 600 Series Chipset SATA Controller                                         | 15       | 3.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 15       | 3.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 14       | 2.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13       | 2.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 12       | 2.44%   |
| AMD 500 Series Chipset SATA Controller                                         | 11       | 2.24%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 10       | 2.04%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 9        | 1.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9        | 1.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9        | 1.83%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 8        | 1.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8        | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8        | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7        | 1.43%   |
| KIOXIA NVMe SSD                                                                | 7        | 1.43%   |
| Phison E16 PCIe4 NVMe Controller                                               | 6        | 1.22%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6        | 1.22%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 6        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 1.22%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 5        | 1.02%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 5        | 1.02%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 5        | 1.02%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 5        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5        | 1.02%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5        | 1.02%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 4        | 0.81%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 4        | 0.81%   |
| Intel SATA Controller [RAID Mode]                                              | 4        | 0.81%   |
| Intel RST Volume Management Device Controller                                  | 4        | 0.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 0.81%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3        | 0.61%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3        | 0.61%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 3        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 230      | 56.51%  |
| NVMe | 130      | 31.94%  |
| RAID | 22       | 5.41%   |
| IDE  | 22       | 5.41%   |
| SAS  | 3        | 0.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Intel      | 179      | 69.38%  |
| AMD        | 73       | 28.29%  |
| Unknown    | 3        | 1.16%   |
| thead,c906 | 2        | 0.78%   |
| iSH        | 1        | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Pentium CPU G4560 @ 3.50GHz      | 5        | 1.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 5        | 1.92%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 5        | 1.92%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 5        | 1.92%   |
| AMD Ryzen 5 3600 6-Core Processor      | 5        | 1.92%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 4        | 1.54%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 4        | 1.54%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 4        | 1.54%   |
| Intel Xeon CPU X5675 @ 3.07GHz         | 3        | 1.15%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz    | 3        | 1.15%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 1.15%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 3        | 1.15%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 3        | 1.15%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 3        | 1.15%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 3        | 1.15%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 1.15%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 3        | 1.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 1.15%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 3        | 1.15%   |
| Intel 12th Gen Core i7-12700           | 3        | 1.15%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 3        | 1.15%   |
| AMD Ryzen 7 9700X 8-Core Processor     | 3        | 1.15%   |
| AMD Ryzen 7 7700X 8-Core Processor     | 3        | 1.15%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 3        | 1.15%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 3        | 1.15%   |
|                                        | 3        | 1.15%   |
| thead,c906 rv64imafdc                  | 2        | 0.77%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 2        | 0.77%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 0.77%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 0.77%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 0.77%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 2        | 0.77%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 2        | 0.77%   |
| Intel 13th Gen Core i7-13700K          | 2        | 0.77%   |
| Intel 13th Gen Core i7-13700           | 2        | 0.77%   |
| Intel 13th Gen Core i5-13600K          | 2        | 0.77%   |
| Intel 13th Gen Core i5-13500           | 2        | 0.77%   |
| Intel 12th Gen Core i9-12900K          | 2        | 0.77%   |
| Intel 12th Gen Core i7-12700K          | 2        | 0.77%   |
| Intel 12th Gen Core i5-12600K          | 2        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Other                   | 43       | 16.54%  |
| Intel Core i7           | 38       | 14.62%  |
| Intel Core i5           | 37       | 14.23%  |
| AMD Ryzen 7             | 28       | 10.77%  |
| Intel Core i3           | 22       | 8.46%   |
| AMD Ryzen 5             | 20       | 7.69%   |
| Intel Xeon              | 16       | 6.15%   |
| AMD Ryzen 9             | 11       | 4.23%   |
| Intel Pentium           | 10       | 3.85%   |
| Intel Celeron           | 7        | 2.69%   |
| Intel Core i9           | 4        | 1.54%   |
| AMD Phenom II X4        | 3        | 1.15%   |
| AMD Phenom II X6        | 2        | 0.77%   |
| AMD FX                  | 2        | 0.77%   |
| Intel Pentium Silver    | 1        | 0.38%   |
| Intel Pentium Gold      | 1        | 0.38%   |
| Intel Pentium Dual-Core | 1        | 0.38%   |
| Intel Pentium Dual      | 1        | 0.38%   |
| Intel Pentium 4         | 1        | 0.38%   |
| Intel Core 2 Quad       | 1        | 0.38%   |
| Intel Core 2 Extreme    | 1        | 0.38%   |
| Intel Core 2 Duo        | 1        | 0.38%   |
| Intel Core 2            | 1        | 0.38%   |
| AMD Ryzen Threadripper  | 1        | 0.38%   |
| AMD Ryzen Embedded      | 1        | 0.38%   |
| AMD Ryzen 7 PRO         | 1        | 0.38%   |
| AMD Opteron             | 1        | 0.38%   |
| AMD Athlon II X4        | 1        | 0.38%   |
| AMD Athlon 64 X2        | 1        | 0.38%   |
| AMD A8                  | 1        | 0.38%   |
| AMD A10                 | 1        | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 76       | 29.34%  |
| 8       | 47       | 18.15%  |
| 6       | 45       | 17.37%  |
| 2       | 39       | 15.06%  |
| 12      | 15       | 5.79%   |
| 16      | 13       | 5.02%   |
| 10      | 5        | 1.93%   |
| Unknown | 5        | 1.93%   |
| 14      | 4        | 1.54%   |
| 24      | 3        | 1.16%   |
| 3       | 2        | 0.77%   |
| 40      | 1        | 0.39%   |
| 28      | 1        | 0.39%   |
| 20      | 1        | 0.39%   |
| 18      | 1        | 0.39%   |
| 1       | 1        | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 246      | 95.35%  |
| 2       | 7        | 2.71%   |
| Unknown | 5        | 1.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 175      | 67.31%  |
| 1       | 80       | 30.77%  |
| Unknown | 5        | 1.92%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 253      | 98.06%  |
| Unknown        | 3        | 1.16%   |
| 64-bit         | 1        | 0.39%   |
| 32-bit         | 1        | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 119      | 44.74%  |
| 0x306c3    | 13       | 4.89%   |
| 0x90672    | 11       | 4.14%   |
| 0x906e9    | 10       | 3.76%   |
| 0x306a9    | 7        | 2.63%   |
| 0x206a7    | 7        | 2.63%   |
| 0x906ea    | 6        | 2.26%   |
| 0x506e3    | 6        | 2.26%   |
| 0x906ed    | 5        | 1.88%   |
| 0x0a50000d | 5        | 1.88%   |
| 0x0800820d | 4        | 1.5%    |
| 0xb0671    | 3        | 1.13%   |
| 0xa0671    | 3        | 1.13%   |
| 0xa0653    | 3        | 1.13%   |
| 0x806e9    | 3        | 1.13%   |
| 0x40651    | 3        | 1.13%   |
| 0x306e4    | 3        | 1.13%   |
| 0x206c2    | 3        | 1.13%   |
| 0x20652    | 3        | 1.13%   |
| 0x0a50000c | 3        | 1.13%   |
| 0x0a201009 | 3        | 1.13%   |
| 0x08701021 | 3        | 1.13%   |
| 0x08701013 | 3        | 1.13%   |
| 0x90675    | 2        | 0.75%   |
| 0x1067a    | 2        | 0.75%   |
| 0x0a601206 | 2        | 0.75%   |
| 0x0a601203 | 2        | 0.75%   |
| 0x0a201016 | 2        | 0.75%   |
| 0x06003106 | 2        | 0.75%   |
| 0x010000c8 | 2        | 0.75%   |
| 0xf41      | 1        | 0.38%   |
| 0xb06e0    | 1        | 0.38%   |
| 0xa0655    | 1        | 0.38%   |
| 0xa0654    | 1        | 0.38%   |
| 0x906eb    | 1        | 0.38%   |
| 0x706a1    | 1        | 0.38%   |
| 0x6fd      | 1        | 0.38%   |
| 0x30678    | 1        | 0.38%   |
| 0x20655    | 1        | 0.38%   |
| 0x106e5    | 1        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 41       | 15.71%  |
| KabyLake         | 37       | 14.18%  |
| Haswell          | 28       | 10.73%  |
| Alderlake Hybrid | 23       | 8.81%   |
| Zen 3            | 19       | 7.28%   |
| IvyBridge        | 14       | 5.36%   |
| CometLake        | 14       | 5.36%   |
| Skylake          | 13       | 4.98%   |
| Zen 2            | 12       | 4.6%    |
| SandyBridge      | 10       | 3.83%   |
| Westmere         | 9        | 3.45%   |
| Zen+             | 8        | 3.07%   |
| K10              | 6        | 2.3%    |
| Zen              | 3        | 1.15%   |
| Penryn           | 3        | 1.15%   |
| Icelake          | 3        | 1.15%   |
| Core             | 3        | 1.15%   |
| Steamroller      | 2        | 0.77%   |
| Piledriver       | 2        | 0.77%   |
| Nehalem          | 2        | 0.77%   |
| Broadwell        | 2        | 0.77%   |
| Tremont          | 1        | 0.38%   |
| Silvermont       | 1        | 0.38%   |
| NetBurst         | 1        | 0.38%   |
| K8 Hammer        | 1        | 0.38%   |
| Gracemont        | 1        | 0.38%   |
| Goldmont plus    | 1        | 0.38%   |
| Excavator        | 1        | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 110      | 37.67%  |
| Nvidia            | 109      | 37.33%  |
| AMD               | 72       | 24.66%  |
| ASPEED Technology | 1        | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 16       | 5.21%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 12       | 3.91%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 10       | 3.26%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 2.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 2.93%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 8        | 2.61%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 7        | 2.28%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 7        | 2.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 1.95%   |
| Intel Kaby Lake-S GT1 [HD Graphics 610]                                     | 6        | 1.95%   |
| AMD Raphael                                                                 | 6        | 1.95%   |
| AMD Phoenix1                                                                | 6        | 1.95%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 1.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.63%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 1.63%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 4        | 1.3%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.3%    |
| Nvidia GM107 [GeForce GTX 750]                                              | 4        | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.3%    |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 4        | 1.3%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.3%    |
| AMD Granite Ridge [Radeon Graphics]                                         | 4        | 1.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.3%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.98%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.98%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 3        | 0.98%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 0.98%   |
| Nvidia AD106 [GeForce RTX 4060 Ti]                                          | 3        | 0.98%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 3        | 0.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 0.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 0.98%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 3        | 0.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 0.98%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 3        | 0.98%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 0.98%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 3        | 0.98%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.65%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 87       | 33.08%  |
| 1 x Intel      | 82       | 31.18%  |
| 1 x AMD        | 55       | 20.91%  |
| Intel + Nvidia | 14       | 5.32%   |
| AMD + Nvidia   | 8        | 3.04%   |
| 2 x AMD        | 7        | 2.66%   |
| Other          | 6        | 2.28%   |
| 4 x Nvidia     | 1        | 0.38%   |
| 3 x AMD        | 1        | 0.38%   |
| 2 x Intel      | 1        | 0.38%   |
| 1 x ASPEED     | 1        | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 184      | 69.43%  |
| Proprietary | 65       | 24.53%  |
| Unknown     | 16       | 6.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 141      | 52.61%  |
| 7.01-8.0   | 27       | 10.07%  |
| 3.01-4.0   | 21       | 7.84%   |
| 1.01-2.0   | 20       | 7.46%   |
| 0.51-1.0   | 19       | 7.09%   |
| 8.01-16.0  | 16       | 5.97%   |
| 0.01-0.5   | 12       | 4.48%   |
| 5.01-6.0   | 7        | 2.61%   |
| 2.01-3.0   | 2        | 0.75%   |
| 4.01-5.0   | 1        | 0.37%   |
| 24.01-32.0 | 1        | 0.37%   |
| 16.01-24.0 | 1        | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 31       | 11.52%  |
| Goldstar             | 26       | 9.67%   |
| Samsung Electronics  | 24       | 8.92%   |
| AOC                  | 21       | 7.81%   |
| Philips              | 16       | 5.95%   |
| ASUSTek Computer     | 11       | 4.09%   |
| Acer                 | 11       | 4.09%   |
| Ancor Communications | 10       | 3.72%   |
| BenQ                 | 9        | 3.35%   |
| ViewSonic            | 8        | 2.97%   |
| Unknown              | 7        | 2.6%    |
| JRY                  | 7        | 2.6%    |
| IPS                  | 6        | 2.23%   |
| AMO                  | 6        | 2.23%   |
| Lenovo               | 5        | 1.86%   |
| Hewlett-Packard      | 5        | 1.86%   |
| Mi                   | 4        | 1.49%   |
| SOY                  | 3        | 1.12%   |
| MSI                  | 3        | 1.12%   |
| Toshiba              | 2        | 0.74%   |
| Skyworth             | 2        | 0.74%   |
| SKY                  | 2        | 0.74%   |
| RTK                  | 2        | 0.74%   |
| INNOCN               | 2        | 0.74%   |
| HSO                  | 2        | 0.74%   |
| Eizo                 | 2        | 0.74%   |
| Denver               | 2        | 0.74%   |
| CHR                  | 2        | 0.74%   |
| AUS                  | 2        | 0.74%   |
| Unknown              | 2        | 0.74%   |
| YSN                  | 1        | 0.37%   |
| Xiaomi               | 1        | 0.37%   |
| Xiangye              | 1        | 0.37%   |
| Unknown (BBC)        | 1        | 0.37%   |
| Unknown (AAA)        | 1        | 0.37%   |
| TFC                  | 1        | 0.37%   |
| TCT                  | 1        | 0.37%   |
| TCL                  | 1        | 0.37%   |
| Sony                 | 1        | 0.37%   |
| SKG                  | 1        | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| JRY HDMI JRY1330 1920x1080 293x165mm 13.2-inch                        | 6        | 2.15%   |
| IPS T270LG IPS2700 3840x2160 602x339mm 27.2-inch                      | 5        | 1.79%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 5        | 1.79%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 4        | 1.43%   |
| AMO HS241P AMO2800 3840x2160 620x350mm 28.0-inch                      | 4        | 1.43%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3        | 1.08%   |
| Toshiba TV TSB2634 1920x1080                                          | 2        | 0.72%   |
| SOY M5 MONITOR SOY0240 1920x1080 520x320mm 24.0-inch                  | 2        | 0.72%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 0.72%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 2        | 0.72%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 2        | 0.72%   |
| MSI MP243X MSI40B5 1920x1080 530x290mm 23.8-inch                      | 2        | 0.72%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 530x300mm 24.0-inch              | 2        | 0.72%   |
| INNOCN 49C1R IOCFFFF 1920x1080 1197x337mm 49.0-inch                   | 2        | 0.72%   |
| HSO B2431M HSO2431 3840x2160 520x290mm 23.4-inch                      | 2        | 0.72%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 0.72%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2        | 0.72%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 2        | 0.72%   |
| Denver MO-HHS-32C LHCFFFF 1920x1080 699x393mm 31.6-inch               | 2        | 0.72%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                     | 2        | 0.72%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 2        | 0.72%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                    | 2        | 0.72%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 2        | 0.72%   |
| Acer V196HQL ACR033D 1366x768 410x230mm 18.5-inch                     | 2        | 0.72%   |
| Unknown                                                               | 2        | 0.72%   |
| YSN YSNO YSN2290 2560x1080 670x308mm 29.0-inch                        | 1        | 0.36%   |
| Xiaomi Mi TV XMD004A 3840x2160 708x398mm 32.0-inch                    | 1        | 0.36%   |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                  | 1        | 0.36%   |
| ViewSonic VX2462 series VSC7A3F 1920x1080 530x300mm 24.0-inch         | 1        | 0.36%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch              | 1        | 0.36%   |
| ViewSonic VX2239 SERIES VSC5225 1920x1080 480x270mm 21.7-inch         | 1        | 0.36%   |
| ViewSonic VG921m VSC301E 1280x1024 380x300mm 19.1-inch                | 1        | 0.36%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1        | 0.36%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch            | 1        | 0.36%   |
| ViewSonic VA2231 Series VSCBB25 1920x1080 477x268mm 21.5-inch         | 1        | 0.36%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch          | 1        | 0.36%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.36%   |
| Unknown LCD Monitor hp f1523 1024x768                                 | 1        | 0.36%   |
| Unknown LCD Monitor GBT G32QC A 2560x1440                             | 1        | 0.36%   |
| Unknown LCD Monitor FST V22T-1R LED 1920x1080                         | 1        | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 113      | 45.02%  |
| 3840x2160 (4K)     | 55       | 21.91%  |
| 2560x1440 (QHD)    | 29       | 11.55%  |
| 1366x768 (WXGA)    | 9        | 3.59%   |
| 1680x1050 (WSXGA+) | 7        | 2.79%   |
| 1440x900 (WXGA+)   | 7        | 2.79%   |
| 1280x1024 (SXGA)   | 5        | 1.99%   |
| 1360x768           | 4        | 1.59%   |
| Unknown            | 4        | 1.59%   |
| 3840x1080          | 3        | 1.2%    |
| 2560x1080          | 3        | 1.2%    |
| 1024x768 (XGA)     | 3        | 1.2%    |
| 3440x1440          | 2        | 0.8%    |
| 1920x1200 (WUXGA)  | 2        | 0.8%    |
| 5120x1440          | 1        | 0.4%    |
| 3200x1080          | 1        | 0.4%    |
| 2560x2880          | 1        | 0.4%    |
| 2560x1600          | 1        | 0.4%    |
| 1400x1050          | 1        | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 45       | 17.05%  |
| 27      | 43       | 16.29%  |
| 23      | 38       | 14.39%  |
| 21      | 28       | 10.61%  |
| Unknown | 22       | 8.33%   |
| 18      | 12       | 4.55%   |
| 31      | 11       | 4.17%   |
| 40      | 6        | 2.27%   |
| 28      | 6        | 2.27%   |
| 13      | 6        | 2.27%   |
| 84      | 5        | 1.89%   |
| 19      | 5        | 1.89%   |
| 49      | 4        | 1.52%   |
| 22      | 4        | 1.52%   |
| 15      | 4        | 1.52%   |
| 34      | 3        | 1.14%   |
| 26      | 3        | 1.14%   |
| 72      | 2        | 0.76%   |
| 64      | 2        | 0.76%   |
| 20      | 2        | 0.76%   |
| 17      | 2        | 0.76%   |
| 65      | 1        | 0.38%   |
| 58      | 1        | 0.38%   |
| 57      | 1        | 0.38%   |
| 54      | 1        | 0.38%   |
| 50      | 1        | 0.38%   |
| 48      | 1        | 0.38%   |
| 37      | 1        | 0.38%   |
| 32      | 1        | 0.38%   |
| 29      | 1        | 0.38%   |
| 25      | 1        | 0.38%   |
| 16      | 1        | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 118      | 46.46%  |
| 401-500     | 48       | 18.9%   |
| Unknown     | 22       | 8.66%   |
| 601-700     | 21       | 8.27%   |
| 1001-1500   | 11       | 4.33%   |
| 801-900     | 7        | 2.76%   |
| 301-350     | 7        | 2.76%   |
| 1501-2000   | 7        | 2.76%   |
| 201-300     | 6        | 2.36%   |
| 701-800     | 5        | 1.97%   |
| 351-400     | 2        | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 180      | 73.47%  |
| 16/10   | 26       | 10.61%  |
| Unknown | 21       | 8.57%   |
| 32/9    | 5        | 2.04%   |
| 5/4     | 3        | 1.22%   |
| 21/9    | 3        | 1.22%   |
| 6/5     | 2        | 0.82%   |
| 4/3     | 2        | 0.82%   |
| 2.18    | 1        | 0.41%   |
| 0.89    | 1        | 0.41%   |
| 0.56    | 1        | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 91       | 34.87%  |
| 301-350        | 51       | 19.54%  |
| Unknown        | 22       | 8.43%   |
| 351-500        | 17       | 6.51%   |
| 151-200        | 17       | 6.51%   |
| 251-300        | 16       | 6.13%   |
| More than 1000 | 14       | 5.36%   |
| 501-1000       | 12       | 4.6%    |
| 141-150        | 10       | 3.83%   |
| 71-80          | 6        | 2.3%    |
| 101-110        | 4        | 1.53%   |
| 131-140        | 1        | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 134      | 51.94%  |
| 101-120       | 54       | 20.93%  |
| 161-240       | 24       | 9.3%    |
| Unknown       | 22       | 8.53%   |
| 121-160       | 13       | 5.04%   |
| 1-50          | 10       | 3.88%   |
| More than 240 | 1        | 0.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 206      | 79.54%  |
| 2     | 31       | 11.97%  |
| 0     | 21       | 8.11%   |
| 3     | 1        | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 155      | 40.47%  |
| Intel                                  | 141      | 36.81%  |
| MediaTek                               | 17       | 4.44%   |
| TP-Link                                | 12       | 3.13%   |
| Broadcom                               | 11       | 2.87%   |
| Qualcomm Atheros                       | 9        | 2.35%   |
| Ralink Technology                      | 7        | 1.83%   |
| Microsoft                              | 4        | 1.04%   |
| Qualcomm Technologies                  | 2        | 0.52%   |
| ASUSTek Computer                       | 2        | 0.52%   |
| Aquantia                               | 2        | 0.52%   |
| Xiaomi                                 | 1        | 0.26%   |
| Winbond Electronics                    | 1        | 0.26%   |
| vivo                                   | 1        | 0.26%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.26%   |
| SEGGER                                 | 1        | 0.26%   |
| Sega                                   | 1        | 0.26%   |
| Samsung Electronics                    | 1        | 0.26%   |
| Qualcomm                               | 1        | 0.26%   |
| PEAK-System Technik                    | 1        | 0.26%   |
| Nvidia                                 | 1        | 0.26%   |
| NetGear                                | 1        | 0.26%   |
| National Semiconductor                 | 1        | 0.26%   |
| Marvell Technology Group               | 1        | 0.26%   |
| Kinesis                                | 1        | 0.26%   |
| Google                                 | 1        | 0.26%   |
| D-Link System                          | 1        | 0.26%   |
| D-Link                                 | 1        | 0.26%   |
| BUFFALO                                | 1        | 0.26%   |
| Belkin Components                      | 1        | 0.26%   |
| ASIX Electronics                       | 1        | 0.26%   |
| Arduino SA                             | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 105      | 22.93%  |
| Realtek RTL8125 2.5GbE Controller                                      | 33       | 7.21%   |
| Intel Wi-Fi 6 AX200                                                    | 21       | 4.59%   |
| Intel Ethernet Controller I225-V                                       | 16       | 3.49%   |
| Intel Ethernet Connection (2) I219-V                                   | 15       | 3.28%   |
| Intel I211 Gigabit Network Connection                                  | 14       | 3.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 12       | 2.62%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 10       | 2.18%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7        | 1.53%   |
| Intel Ethernet Connection I217-LM                                      | 7        | 1.53%   |
| Realtek 802.11ac NIC                                                   | 6        | 1.31%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6        | 1.31%   |
| Intel 82574L Gigabit Network Connection                                | 6        | 1.31%   |
| Intel 700 Series Chipset CNVi WiFi                                     | 6        | 1.31%   |
| Intel Ethernet Connection (17) I219-LM                                 | 5        | 1.09%   |
| Ralink RT5370 Wireless Adapter                                         | 4        | 0.87%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]   | 4        | 0.87%   |
| Intel Wireless 7265                                                    | 4        | 0.87%   |
| Intel Ethernet Controller I226-V                                       | 4        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 0.87%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 3        | 0.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 0.66%   |
| Ralink MT7601U Wireless Adapter                                        | 3        | 0.66%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 3        | 0.66%   |
| Intel Wireless 8265 / 8275                                             | 3        | 0.66%   |
| Intel Wireless 7260                                                    | 3        | 0.66%   |
| Intel Wireless 3160                                                    | 3        | 0.66%   |
| Intel Ethernet Connection I217-V                                       | 3        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 0.66%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.66%   |
| Intel Ethernet Connection (11) I219-V                                  | 3        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3        | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 0.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2        | 0.44%   |
| Realtek USB 10/100/1G/2.5 LAN                                          | 2        | 0.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 82       | 52.23%  |
| Realtek Semiconductor | 21       | 13.38%  |
| MediaTek              | 17       | 10.83%  |
| TP-Link               | 12       | 7.64%   |
| Ralink Technology     | 7        | 4.46%   |
| Broadcom              | 5        | 3.18%   |
| Microsoft             | 4        | 2.55%   |
| Qualcomm Atheros      | 3        | 1.91%   |
| ASUSTek Computer      | 2        | 1.27%   |
| NetGear               | 1        | 0.64%   |
| D-Link System         | 1        | 0.64%   |
| BUFFALO               | 1        | 0.64%   |
| Belkin Components     | 1        | 0.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 21       | 13.38%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 12       | 7.64%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 8        | 5.1%    |
| Realtek 802.11ac NIC                                                 | 6        | 3.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 6        | 3.82%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 6        | 3.82%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 6        | 3.82%   |
| Ralink RT5370 Wireless Adapter                                       | 4        | 2.55%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 4        | 2.55%   |
| Intel Wireless 7265                                                  | 4        | 2.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 3        | 1.91%   |
| Ralink MT7601U Wireless Adapter                                      | 3        | 1.91%   |
| Microsoft Xbox Wireless Adapter for Windows                          | 3        | 1.91%   |
| Intel Wireless 8265 / 8275                                           | 3        | 1.91%   |
| Intel Wireless 7260                                                  | 3        | 1.91%   |
| Intel Wireless 3160                                                  | 3        | 1.91%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3        | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3        | 1.91%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 1.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2        | 1.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2        | 1.27%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 2        | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2        | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 2        | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2        | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 2        | 1.27%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                   | 2        | 1.27%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2      | 2        | 1.27%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2        | 1.27%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 2        | 1.27%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 2        | 1.27%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                | 1        | 0.64%   |
| TP-Link Archer T4U ver.3                                             | 1        | 0.64%   |
| TP-Link 802.11n NIC                                                  | 1        | 0.64%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1        | 0.64%   |
| TP-Link 802.11ac NIC                                                 | 1        | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1        | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 152      | 53.9%   |
| Intel                                  | 103      | 36.52%  |
| Qualcomm Atheros                       | 6        | 2.13%   |
| Broadcom                               | 6        | 2.13%   |
| Qualcomm Technologies                  | 2        | 0.71%   |
| Aquantia                               | 2        | 0.71%   |
| Xiaomi                                 | 1        | 0.35%   |
| vivo                                   | 1        | 0.35%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.35%   |
| Samsung Electronics                    | 1        | 0.35%   |
| Qualcomm                               | 1        | 0.35%   |
| Nvidia                                 | 1        | 0.35%   |
| National Semiconductor                 | 1        | 0.35%   |
| Marvell Technology Group               | 1        | 0.35%   |
| Google                                 | 1        | 0.35%   |
| D-Link                                 | 1        | 0.35%   |
| ASIX Electronics                       | 1        | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 105      | 35.59%  |
| Realtek RTL8125 2.5GbE Controller                                              | 33       | 11.19%  |
| Intel Ethernet Controller I225-V                                               | 16       | 5.42%   |
| Intel Ethernet Connection (2) I219-V                                           | 15       | 5.08%   |
| Intel I211 Gigabit Network Connection                                          | 14       | 4.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7        | 2.37%   |
| Intel Ethernet Connection I217-LM                                              | 7        | 2.37%   |
| Intel 82574L Gigabit Network Connection                                        | 6        | 2.03%   |
| Intel Ethernet Connection (17) I219-LM                                         | 5        | 1.69%   |
| Intel Ethernet Controller I226-V                                               | 4        | 1.36%   |
| Intel Ethernet Connection (7) I219-V                                           | 4        | 1.36%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 4        | 1.36%   |
| Intel 82579V Gigabit Network Connection                                        | 4        | 1.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 1.02%   |
| Intel Ethernet Connection I217-V                                               | 3        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3        | 1.02%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 1.02%   |
| Intel Ethernet Connection (11) I219-V                                          | 3        | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 1.02%   |
| Realtek USB 10/100/1G/2.5 LAN                                                  | 2        | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2        | 0.68%   |
| Realtek Killer E2600 GbE Controller                                            | 2        | 0.68%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]               | 2        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 0.68%   |
| Intel Ethernet Connection (17) I219-V                                          | 2        | 0.68%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 0.68%   |
| Intel Ethernet Connection (12) I219-V                                          | 2        | 0.68%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2        | 0.68%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.34%   |
| vivo V2029                                                                     | 1        | 0.34%   |
| Sony Ericsson Mobile AB XQ-CC72                                                | 1        | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.34%   |
| Realtek RTL8126 5GbE Controller                                                | 1        | 0.34%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.34%   |
| Qualcomm Nokia X30 5G                                                          | 1        | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.34%   |
| Nvidia MCP65 Ethernet                                                          | 1        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 253      | 62.94%  |
| WiFi     | 143      | 35.57%  |
| Modem    | 4        | 1%      |
| Unknown  | 2        | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 203      | 73.29%  |
| WiFi     | 74       | 26.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 122      | 46.56%  |
| 2     | 114      | 43.51%  |
| 3     | 13       | 4.96%   |
| 0     | 8        | 3.05%   |
| 4     | 3        | 1.15%   |
| 8     | 1        | 0.38%   |
| 7     | 1        | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 245      | 94.59%  |
| Yes  | 14       | 5.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 78       | 58.21%  |
| Cambridge Silicon Radio         | 19       | 14.18%  |
| Realtek Semiconductor           | 6        | 4.48%   |
| MediaTek                        | 6        | 4.48%   |
| IMC Networks                    | 5        | 3.73%   |
| Foxconn / Hon Hai               | 4        | 2.99%   |
| Broadcom                        | 4        | 2.99%   |
| TP-Link                         | 2        | 1.49%   |
| Qualcomm Atheros Communications | 2        | 1.49%   |
| ASUSTek Computer                | 2        | 1.49%   |
| Apple                           | 2        | 1.49%   |
| SINO WEALTH                     | 1        | 0.75%   |
| Micro Star International        | 1        | 0.75%   |
| Lite-On Technology              | 1        | 0.75%   |
| Unknown                         | 1        | 0.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 19       | 14.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 19       | 14.18%  |
| Intel Bluetooth wireless interface                  | 13       | 9.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 11       | 8.21%   |
| Intel AX201 Bluetooth                               | 11       | 8.21%   |
| Intel Bluetooth Device                              | 10       | 7.46%   |
| Intel AX210 Bluetooth                               | 8        | 5.97%   |
| Realtek Bluetooth Radio                             | 6        | 4.48%   |
| MediaTek Wireless_Device                            | 6        | 4.48%   |
| IMC Networks Wireless_Device                        | 4        | 2.99%   |
| TP-Link TP-T@- UB500 Adapter                        | 2        | 1.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 1.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 1.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 2        | 1.49%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2        | 1.49%   |
| ASUS Bluetooth Radio                                | 2        | 1.49%   |
| SINO WEALTH Bluetooth Keyboard                      | 1        | 0.75%   |
| Micro Star International Bluetooth Dongle           | 1        | 0.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 0.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 0.75%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1        | 0.75%   |
| IMC Networks Bluetooth Radio                        | 1        | 0.75%   |
| Broadcom Bluetooth Controller                       | 1        | 0.75%   |
| Broadcom Bluetooth 2.0+eDR dongle                   | 1        | 0.75%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle  | 1        | 0.75%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 0.75%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 0.75%   |
| Apple Bluetooth Host Controller                     | 1        | 0.75%   |
| Unknown                                             | 1        | 0.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 176      | 40.55%  |
| Nvidia                                       | 106      | 24.42%  |
| AMD                                          | 93       | 21.43%  |
| C-Media Electronics                          | 11       | 2.53%   |
| Micro Star International                     | 8        | 1.84%   |
| ASUSTek Computer                             | 4        | 0.92%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.69%   |
| SteelSeries ApS                              | 3        | 0.69%   |
| Focusrite-Novation                           | 3        | 0.69%   |
| Walmart                                      | 2        | 0.46%   |
| Logitech                                     | 2        | 0.46%   |
| KTMicro                                      | 2        | 0.46%   |
| FiiO Electronics Technology                  | 2        | 0.46%   |
| Creative Labs                                | 2        | 0.46%   |
| XMOS                                         | 1        | 0.23%   |
| TT AUDIO                                     | 1        | 0.23%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.23%   |
| Texas Instruments                            | 1        | 0.23%   |
| Sony                                         | 1        | 0.23%   |
| Schiit Audio                                 | 1        | 0.23%   |
| SAVITECH                                     | 1        | 0.23%   |
| Roland                                       | 1        | 0.23%   |
| Nordic Semiconductor ASA                     | 1        | 0.23%   |
| Meizu                                        | 1        | 0.23%   |
| Lynx                                         | 1        | 0.23%   |
| JMTek                                        | 1        | 0.23%   |
| Jieli Technology                             | 1        | 0.23%   |
| Hewlett-Packard                              | 1        | 0.23%   |
| Harman International                         | 1        | 0.23%   |
| AudioQuest                                   | 1        | 0.23%   |
| Arturia                                      | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                              | 27       | 5.24%   |
| Intel Alder Lake-S HD Audio Controller                                     | 23       | 4.47%   |
| AMD Starship/Matisse HD Audio Controller                                   | 23       | 4.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18       | 3.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 18       | 3.5%    |
| AMD Radeon High Definition Audio Controller                                | 17       | 3.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16       | 3.11%   |
| Intel 200 Series PCH HD Audio                                              | 16       | 3.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14       | 2.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 10       | 1.94%   |
| Intel Raptor Lake High Definition Audio Controller                         | 10       | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 1.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 1.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.75%   |
| Intel Comet Lake PCH-V cAVS                                                | 9        | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 1.75%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 9        | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.55%   |
| Micro Star International USB Audio                                         | 8        | 1.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 1.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 7        | 1.36%   |
| Nvidia GA106 High Definition Audio Controller                              | 7        | 1.36%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 1.36%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7        | 1.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 0.97%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 0.97%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.78%   |
| Nvidia AD106M High Definition Audio Controller                             | 4        | 0.78%   |
| Nvidia AD102 High Definition Audio Controller                              | 4        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 0.78%   |
| ASUSTek Computer USB Audio                                                 | 4        | 0.78%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 4        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston                        | 45       | 26.63%  |
| Corsair                         | 19       | 11.24%  |
| Samsung Electronics             | 18       | 10.65%  |
| A-DATA Technology               | 16       | 9.47%   |
| SK hynix                        | 13       | 7.69%   |
| Unknown                         | 8        | 4.73%   |
| G.Skill                         | 8        | 4.73%   |
| Crucial                         | 7        | 4.14%   |
| Team                            | 5        | 2.96%   |
| Micron Technology               | 4        | 2.37%   |
| Unknown                         | 4        | 2.37%   |
| Ramaxel Technology              | 3        | 1.78%   |
| Juhor                           | 2        | 1.18%   |
| GLOWAY                          | 2        | 1.18%   |
| Unknown (0x0AFD)                | 1        | 0.59%   |
| Unknown (0x0080)                | 1        | 0.59%   |
| Unknown (049E)                  | 1        | 0.59%   |
| Transcend                       | 1        | 0.59%   |
| Shenzhen SKIHOTAR Semiconductor | 1        | 0.59%   |
| Nanya Technology                | 1        | 0.59%   |
| KingSpec                        | 1        | 0.59%   |
| Kingmax                         | 1        | 0.59%   |
| KINGBANK                        | 1        | 0.59%   |
| Kimtigo                         | 1        | 0.59%   |
| Essencore Limited               | 1        | 0.59%   |
| CUSO                            | 1        | 0.59%   |
| Colorful                        | 1        | 0.59%   |
| Asgard                          | 1        | 0.59%   |
| Apacer                          | 1        | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Unknown                                                          | 4        | 2.16%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3466MT/s            | 3        | 1.62%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2        | 1.08%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                   | 2        | 1.08%   |
| Kingston RAM KHX2666C16/8G 8GiB DIMM DDR4 3466MT/s               | 2        | 1.08%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2        | 1.08%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s            | 2        | 1.08%   |
| Juhor RAM JHD2666U1916JG 16GB DIMM DDR4 2667MT/s                 | 2        | 1.08%   |
| Corsair RAM CMZ16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s             | 2        | 1.08%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 2        | 1.08%   |
| Corsair RAM CM4X16GC3600C18K2D 16GB DIMM DDR4 3600MT/s           | 2        | 1.08%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                         | 2        | 1.08%   |
| A-DATA RAM DDR4 3600 16GB DIMM DDR4 3800MT/s                     | 2        | 1.08%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1        | 0.54%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM 800MT/s                              | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s                      | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1        | 0.54%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 1        | 0.54%   |
| Unknown (0x0AFD) RAM SED2666U1932 32GB DIMM DDR4 2667MT/s        | 1        | 0.54%   |
| Unknown (0x0080) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s | 1        | 0.54%   |
| Unknown (049E) RAM PF-LEN-31369 8GB DIMM DDR3 1333MT/s           | 1        | 0.54%   |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s                | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s               | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s               | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1866MT/s               | 1        | 0.54%   |
| Team RAM Elite-1333 8GB DIMM DDR3 1333MT/s                       | 1        | 0.54%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                       | 1        | 0.54%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                       | 1        | 0.54%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                       | 1        | 0.54%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s            | 1        | 0.54%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.54%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1        | 0.54%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1        | 0.54%   |
| SK hynix RAM HMCG78AGBUA081N 16GB DIMM DDR5 5600MT/s             | 1        | 0.54%   |
| SK hynix RAM HMCG66MEBUA084N 8GB DIMM DDR5 4800MT/s              | 1        | 0.54%   |
| SK hynix RAM HMCG66AGBUA084N 8GB DIMM DDR5 5600MT/s              | 1        | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 89       | 56.69%  |
| DDR3    | 29       | 18.47%  |
| DDR5    | 27       | 17.2%   |
| Unknown | 6        | 3.82%   |
| SDRAM   | 3        | 1.91%   |
| DDR2    | 2        | 1.27%   |
| LPDDR4  | 1        | 0.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 131      | 84.52%  |
| SODIMM       | 22       | 14.19%  |
| Row Of Chips | 2        | 1.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 54       | 32.53%  |
| 8192  | 45       | 27.11%  |
| 32768 | 26       | 15.66%  |
| 4096  | 24       | 14.46%  |
| 2048  | 11       | 6.63%   |
| 24576 | 3        | 1.81%   |
| 49152 | 1        | 0.6%    |
| 3072  | 1        | 0.6%    |
| 1024  | 1        | 0.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 23       | 13.86%  |
| 1600    | 19       | 11.45%  |
| 2667    | 17       | 10.24%  |
| 5600    | 11       | 6.63%   |
| 3600    | 11       | 6.63%   |
| 2400    | 11       | 6.63%   |
| 1333    | 11       | 6.63%   |
| 6000    | 7        | 4.22%   |
| 2133    | 7        | 4.22%   |
| 2666    | 6        | 3.61%   |
| 4800    | 5        | 3.01%   |
| 3466    | 5        | 3.01%   |
| 3000    | 4        | 2.41%   |
| 4000    | 3        | 1.81%   |
| 1866    | 3        | 1.81%   |
| 800     | 3        | 1.81%   |
| 3933    | 2        | 1.2%    |
| 3800    | 2        | 1.2%    |
| 8400    | 1        | 0.6%    |
| 7000    | 1        | 0.6%    |
| 6400    | 1        | 0.6%    |
| 6200    | 1        | 0.6%    |
| 5400    | 1        | 0.6%    |
| 5000    | 1        | 0.6%    |
| 4199    | 1        | 0.6%    |
| 3866    | 1        | 0.6%    |
| 3733    | 1        | 0.6%    |
| 3400    | 1        | 0.6%    |
| 3266    | 1        | 0.6%    |
| 3007    | 1        | 0.6%    |
| 2933    | 1        | 0.6%    |
| 2733    | 1        | 0.6%    |
| 667     | 1        | 0.6%    |
| Unknown | 1        | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 40%     |
| Fuji Xerox         | 1        | 20%     |
| Canon              | 1        | 20%     |
| Brother Industries | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP LaserJet Pro M329        | 1        | 20%     |
| HP LaserJet P2035           | 1        | 20%     |
| Fuji Xerox DocuPrint P158 b | 1        | 20%     |
| Canon MP160                 | 1        | 20%     |
| Brother HL-L2320D series    | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 2        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 12       | 38.71%  |
| Microdia                      | 3        | 9.68%   |
| eMPIA Technology              | 2        | 6.45%   |
| Z-Star Microelectronics       | 1        | 3.23%   |
| Sunplus Innovation Technology | 1        | 3.23%   |
| SN0002                        | 1        | 3.23%   |
| Samsung Electronics           | 1        | 3.23%   |
| Nokia Mobile Phones           | 1        | 3.23%   |
| HYGD-221208-J                 | 1        | 3.23%   |
| Google                        | 1        | 3.23%   |
| Essential Products            | 1        | 3.23%   |
| Cubeternet                    | 1        | 3.23%   |
| Aveo Technology               | 1        | 3.23%   |
| ARC International             | 1        | 3.23%   |
| Afatech                       | 1        | 3.23%   |
| Actions Microelectronics      | 1        | 3.23%   |
| A4Tech                        | 1        | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 5        | 15.63%  |
| Logitech BRIO Ultra HD Webcam           | 2        | 6.25%   |
| Logitech B525 HD Webcam                 | 2        | 6.25%   |
| eMPIA M035 Compact Web Cam              | 2        | 6.25%   |
| Z-Star Sirius USB2.0 Camera             | 1        | 3.13%   |
| Sunplus SPCA2650 PC Camera              | 1        | 3.13%   |
| SN0002 2K USB Camera                    | 1        | 3.13%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 3.13%   |
| Nokia Mobile Phones Lumia 640 Phone     | 1        | 3.13%   |
| Microdia USB 2.0 Camera                 | 1        | 3.13%   |
| Microdia Rapoo Camera                   | 1        | 3.13%   |
| Microdia HP Integrated Webcam           | 1        | 3.13%   |
| Logitech Webcam C930e                   | 1        | 3.13%   |
| Logitech C922 Pro Stream Webcam         | 1        | 3.13%   |
| Logitech C920 PRO HD Webcam             | 1        | 3.13%   |
| HYGD-221208-J BKX-Usb2.0 2MP Camera     | 1        | 3.13%   |
| Google Nexus/Pixel Device (PTP + debug) | 1        | 3.13%   |
| Google Nexus/Pixel Device (MTP + debug) | 1        | 3.13%   |
| Essential Products PH-1                 | 1        | 3.13%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 3.13%   |
| Aveo USB2.0 Camera                      | 1        | 3.13%   |
| ARC International Camera                | 1        | 3.13%   |
| Afatech NarviCapture U3 HD60 4K Device  | 1        | 3.13%   |
| Actions UGREEN 25854                    | 1        | 3.13%   |
| A4Tech FHD 1080P PC Camera              | 1        | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 2        | 50%     |
| Yubico.com            | 1        | 25%     |
| Clay Logic            | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Advanced Card Systems ACR1281 1S Dual Reader | 2        | 50%     |
| Yubico.com Yubikey 4/5 U2F+CCID              | 1        | 25%     |
| Clay Logic Nitrokey HSM                      | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 216      | 81.2%   |
| 1     | 39       | 14.66%  |
| 2     | 7        | 2.63%   |
| 4     | 2        | 0.75%   |
| 3     | 2        | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 24       | 38.71%  |
| Graphics card            | 15       | 24.19%  |
| Communication controller | 9        | 14.52%  |
| Unassigned class         | 5        | 8.06%   |
| Chipcard                 | 3        | 4.84%   |
| Storage/ata              | 1        | 1.61%   |
| Sound                    | 1        | 1.61%   |
| Net/ethernet             | 1        | 1.61%   |
| Fingerprint reader       | 1        | 1.61%   |
| Camera                   | 1        | 1.61%   |
| Bluetooth                | 1        | 1.61%   |

