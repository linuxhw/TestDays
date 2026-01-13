Linux in Lithuania - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Lithuania.

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

Total: 269

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | 990FX Extreme3              | [a4957b0fb6](https://linux-hardware.org/?probe=a4957b0fb6) | Dec 27, 2025 |
| ASRock        | B550M-ITX/ac                | [30d59dd72a](https://linux-hardware.org/?probe=30d59dd72a) | Dec 26, 2025 |
| MSI           | X570-A PRO                  | [da7609dc43](https://linux-hardware.org/?probe=da7609dc43) | Dec 19, 2025 |
| ASUSTek       | ProArt B650-CREATOR         | [907fe00a3c](https://linux-hardware.org/?probe=907fe00a3c) | Nov 09, 2025 |
| Lenovo        | 106F NOK                    | [65fde3e18c](https://linux-hardware.org/?probe=65fde3e18c) | Nov 08, 2025 |
| ASUSTek       | ROG STRIX B850-E GAMING ... | [1e0ef0fcdb](https://linux-hardware.org/?probe=1e0ef0fcdb) | Nov 05, 2025 |
| ASUSTek       | VM40B                       | [da7375d0b0](https://linux-hardware.org/?probe=da7375d0b0) | Oct 22, 2025 |
| Gigabyte      | X570 AORUS ULTRA            | [1967f6dbe5](https://linux-hardware.org/?probe=1967f6dbe5) | Sep 27, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [085ba70e19](https://linux-hardware.org/?probe=085ba70e19) | Aug 24, 2025 |
| ASUSTek       | ROG STRIX B850-E GAMING ... | [6305c41b67](https://linux-hardware.org/?probe=6305c41b67) | Aug 20, 2025 |
| MSI           | B450 TOMAHAWK MAX II        | [7754689bb6](https://linux-hardware.org/?probe=7754689bb6) | Aug 11, 2025 |
| MSI           | B550M PRO-VDH WIFI          | [f65a5e3862](https://linux-hardware.org/?probe=f65a5e3862) | Aug 09, 2025 |
| Gigabyte      | Z390 D                      | [66d9546dda](https://linux-hardware.org/?probe=66d9546dda) | Aug 06, 2025 |
| Gigabyte      | X570S UD                    | [d23166b510](https://linux-hardware.org/?probe=d23166b510) | Jul 19, 2025 |
| Unknown       | Unknown                     | [6d3e356f35](https://linux-hardware.org/?probe=6d3e356f35) | Jul 11, 2025 |
| ASRock        | B450M-HDV R4.0              | [430090f90d](https://linux-hardware.org/?probe=430090f90d) | Jun 17, 2025 |
| ASRock        | B450M-HDV R4.0              | [d373e1ac51](https://linux-hardware.org/?probe=d373e1ac51) | Jun 17, 2025 |
| ASUSTek       | ROG STRIX B850-E GAMING ... | [d2b1a57099](https://linux-hardware.org/?probe=d2b1a57099) | Jun 02, 2025 |
| Intel         | DQ965GF AAD41676-402        | [cbcd411d7c](https://linux-hardware.org/?probe=cbcd411d7c) | May 23, 2025 |
| MSI           | TRX40 PRO WIFI              | [4ad4538d68](https://linux-hardware.org/?probe=4ad4538d68) | May 22, 2025 |
| MSI           | Z170-A PRO                  | [25bc89f5f3](https://linux-hardware.org/?probe=25bc89f5f3) | May 14, 2025 |
| ASUSTek       | ROG STRIX B850-E GAMING ... | [5193bb5c7e](https://linux-hardware.org/?probe=5193bb5c7e) | May 05, 2025 |
| ASRock        | Z490 Pro4                   | [211f6b2a1d](https://linux-hardware.org/?probe=211f6b2a1d) | May 05, 2025 |
| ASRock        | B550M Pro4                  | [412b8c06ae](https://linux-hardware.org/?probe=412b8c06ae) | Apr 29, 2025 |
| ASUSTek       | P8Z77-V PRO                 | [cda6bb9bab](https://linux-hardware.org/?probe=cda6bb9bab) | Apr 19, 2025 |
| ASUSTek       | ROG STRIX B850-E GAMING ... | [5f2b949d51](https://linux-hardware.org/?probe=5f2b949d51) | Apr 08, 2025 |
| MSI           | MAG A520M VECTOR WIFI       | [2df2189531](https://linux-hardware.org/?probe=2df2189531) | Apr 07, 2025 |
| ASUSTek       | ROG STRIX B850-E GAMING ... | [0ae3014bc0](https://linux-hardware.org/?probe=0ae3014bc0) | Apr 06, 2025 |
| Gigabyte      | MZBSWMP-00                  | [4263c1ac68](https://linux-hardware.org/?probe=4263c1ac68) | Mar 22, 2025 |
| ASUSTek       | M5A97 R2.0                  | [1be56d43f4](https://linux-hardware.org/?probe=1be56d43f4) | Mar 11, 2025 |
| MSI           | PRO B650M-A WIFI            | [9156ad042b](https://linux-hardware.org/?probe=9156ad042b) | Mar 06, 2025 |
| MSI           | B450 TOMAHAWK MAX II        | [4f720212bf](https://linux-hardware.org/?probe=4f720212bf) | Feb 26, 2025 |
| ASUSTek       | ROG STRIX B850-E GAMING ... | [30bb29dbf1](https://linux-hardware.org/?probe=30bb29dbf1) | Feb 25, 2025 |
| ASUSTek       | ROG STRIX B850-E GAMING ... | [9d2e1d7d65](https://linux-hardware.org/?probe=9d2e1d7d65) | Feb 21, 2025 |
| Acer          | Veriton EN2580 V:1.2        | [ab858557f0](https://linux-hardware.org/?probe=ab858557f0) | Feb 13, 2025 |
| ASUSTek       | PRIME B760M-K               | [a3200946c9](https://linux-hardware.org/?probe=a3200946c9) | Feb 11, 2025 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | [5a020512a0](https://linux-hardware.org/?probe=5a020512a0) | Feb 05, 2025 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | [1b73bf6a4d](https://linux-hardware.org/?probe=1b73bf6a4d) | Feb 04, 2025 |
| Acer          | Veriton EN2580 V:1.2        | [41fae9111c](https://linux-hardware.org/?probe=41fae9111c) | Jan 24, 2025 |
| Dell          | 0TTDMJ A00                  | [be4d9b1402](https://linux-hardware.org/?probe=be4d9b1402) | Jan 24, 2025 |
| KMP           | B85M ECO IS85E              | [354defb6a6](https://linux-hardware.org/?probe=354defb6a6) | Jan 07, 2025 |
| MSI           | B450-A PRO                  | [fa8374d09c](https://linux-hardware.org/?probe=fa8374d09c) | Jan 01, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [9ba5e6b3c0](https://linux-hardware.org/?probe=9ba5e6b3c0) | Dec 30, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [bbae43def0](https://linux-hardware.org/?probe=bbae43def0) | Dec 24, 2024 |
| MSI           | H61M-P23                    | [4e730504db](https://linux-hardware.org/?probe=4e730504db) | Dec 06, 2024 |
| ASUSTek       | PRIME A520M-A II            | [954f4f20de](https://linux-hardware.org/?probe=954f4f20de) | Oct 28, 2024 |
| ASRock        | B550M Phantom Gaming 4      | [0bfa5ff580](https://linux-hardware.org/?probe=0bfa5ff580) | Oct 08, 2024 |
| HP            | 805D                        | [9b68e25a8d](https://linux-hardware.org/?probe=9b68e25a8d) | Oct 02, 2024 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [e9bef43957](https://linux-hardware.org/?probe=e9bef43957) | Oct 02, 2024 |
| ASUSTek       | PRIME B560M-K               | [8ead28af74](https://linux-hardware.org/?probe=8ead28af74) | Aug 07, 2024 |
| Gigabyte      | A320M-S2H-CF                | [6f98b9d085](https://linux-hardware.org/?probe=6f98b9d085) | Jun 08, 2024 |
| MSI           | B550-A PRO                  | [d9d57e90a2](https://linux-hardware.org/?probe=d9d57e90a2) | Jun 03, 2024 |
| MSI           | B550-A PRO                  | [803cb92786](https://linux-hardware.org/?probe=803cb92786) | May 29, 2024 |
| ASRock        | A320M-DVS R4.0              | [58a45e4ab3](https://linux-hardware.org/?probe=58a45e4ab3) | May 21, 2024 |
| ASRock        | A320M-DVS R4.0              | [e2d7993d49](https://linux-hardware.org/?probe=e2d7993d49) | May 20, 2024 |
| HP            | 0AECh D                     | [7173a4bf88](https://linux-hardware.org/?probe=7173a4bf88) | May 18, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [204a955e18](https://linux-hardware.org/?probe=204a955e18) | May 17, 2024 |
| MSI           | B550-A PRO                  | [077d8caca8](https://linux-hardware.org/?probe=077d8caca8) | Apr 22, 2024 |
| MSI           | B550-A PRO                  | [1e07f3fb8f](https://linux-hardware.org/?probe=1e07f3fb8f) | Apr 22, 2024 |
| MSI           | B550-A PRO                  | [909681165a](https://linux-hardware.org/?probe=909681165a) | Apr 22, 2024 |
| ASUSTek       | P9X79                       | [f5f0955b10](https://linux-hardware.org/?probe=f5f0955b10) | Apr 20, 2024 |
| ASRock        | B760M Pro RS                | [ba1fde2d8b](https://linux-hardware.org/?probe=ba1fde2d8b) | Apr 17, 2024 |
| ASRock        | B450M Pro4                  | [c6e809a3fa](https://linux-hardware.org/?probe=c6e809a3fa) | Apr 08, 2024 |
| ASUSTek       | PRIME B550M-A               | [98f3a35dbb](https://linux-hardware.org/?probe=98f3a35dbb) | Mar 24, 2024 |
| ASRock        | B450M Pro4                  | [bdd0b87420](https://linux-hardware.org/?probe=bdd0b87420) | Mar 19, 2024 |
| ASRock        | B550M Phantom Gaming 4      | [30345806ba](https://linux-hardware.org/?probe=30345806ba) | Mar 11, 2024 |
| HP            | 8950                        | [ee925d29a1](https://linux-hardware.org/?probe=ee925d29a1) | Mar 08, 2024 |
| HP            | 8950                        | [f2b8f96540](https://linux-hardware.org/?probe=f2b8f96540) | Mar 08, 2024 |
| ASRock        | B450M Pro4                  | [95f6ca3672](https://linux-hardware.org/?probe=95f6ca3672) | Mar 04, 2024 |
| Gigabyte      | B85M-DS3H-A                 | [99e8a768ca](https://linux-hardware.org/?probe=99e8a768ca) | Jan 30, 2024 |
| AMI           | Intel                       | [5085eba8b2](https://linux-hardware.org/?probe=5085eba8b2) | Jan 23, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [adb9343764](https://linux-hardware.org/?probe=adb9343764) | Jan 16, 2024 |
| ASRock        | B760M Pro RS                | [34ecc17795](https://linux-hardware.org/?probe=34ecc17795) | Jan 10, 2024 |
| ASRock        | B760M Pro RS                | [f648cda96d](https://linux-hardware.org/?probe=f648cda96d) | Dec 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [fbe4d2ec54](https://linux-hardware.org/?probe=fbe4d2ec54) | Dec 08, 2023 |
| ASRock        | B760M Pro RS                | [77b3b5fc4d](https://linux-hardware.org/?probe=77b3b5fc4d) | Dec 07, 2023 |
| Dell          | 0NV0M7 A01                  | [f5ced375d8](https://linux-hardware.org/?probe=f5ced375d8) | Nov 17, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [81fb4db1cc](https://linux-hardware.org/?probe=81fb4db1cc) | Nov 15, 2023 |
| ASRock        | X470 Taichi Ultimate        | [2b9b1f909c](https://linux-hardware.org/?probe=2b9b1f909c) | Nov 05, 2023 |
| ASUSTek       | M5A97 R2.0                  | [7f2d93dc09](https://linux-hardware.org/?probe=7f2d93dc09) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [40769bf0a3](https://linux-hardware.org/?probe=40769bf0a3) | Oct 27, 2023 |
| MSI           | H81M-P33                    | [f59a3c2021](https://linux-hardware.org/?probe=f59a3c2021) | Oct 25, 2023 |
| MSI           | H81M-P33                    | [04b9d686b6](https://linux-hardware.org/?probe=04b9d686b6) | Oct 21, 2023 |
| ASRock        | B450 Pro4                   | [02211f49db](https://linux-hardware.org/?probe=02211f49db) | Oct 08, 2023 |
| ASRock        | B450M Pro4                  | [87f5275af6](https://linux-hardware.org/?probe=87f5275af6) | Sep 18, 2023 |
| ASRock        | B450M Pro4                  | [b52a6f9b59](https://linux-hardware.org/?probe=b52a6f9b59) | Sep 10, 2023 |
| ASRock        | B450M Pro4                  | [cdabed6210](https://linux-hardware.org/?probe=cdabed6210) | Sep 05, 2023 |
| Intel         | D915GAV AAC64134-400        | [c7cad9e093](https://linux-hardware.org/?probe=c7cad9e093) | Aug 20, 2023 |
| ASRock        | B450M-HDV R4.0              | [6855901c02](https://linux-hardware.org/?probe=6855901c02) | Aug 12, 2023 |
| MSI           | B350 TOMAHAWK               | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| ASUSTek       | PRIME H410M-K               | [0dbf02ef16](https://linux-hardware.org/?probe=0dbf02ef16) | Jul 13, 2023 |
| ASUSTek       | Z87-A                       | [ca84827c75](https://linux-hardware.org/?probe=ca84827c75) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [a30c01fab8](https://linux-hardware.org/?probe=a30c01fab8) | Jun 21, 2023 |
| ASUSTek       | P5KPL-VM                    | [e2919326cd](https://linux-hardware.org/?probe=e2919326cd) | Jun 16, 2023 |
| HP            | 0B4Ch D                     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX2                 | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| ASRock        | QC5000M-ITX/PH              | [bdf4ee4d4f](https://linux-hardware.org/?probe=bdf4ee4d4f) | Jun 04, 2023 |
| MSI           | B450M MORTAR MAX            | [72ccbe10aa](https://linux-hardware.org/?probe=72ccbe10aa) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d2189d4a5f](https://linux-hardware.org/?probe=d2189d4a5f) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| HP            | 0B4Ch D                     | [0f593c947e](https://linux-hardware.org/?probe=0f593c947e) | May 27, 2023 |
| HP            | 0B4Ch D                     | [e7a8d68439](https://linux-hardware.org/?probe=e7a8d68439) | May 27, 2023 |
| Unknown       | Unknown                     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [db7e2a1d87](https://linux-hardware.org/?probe=db7e2a1d87) | Apr 29, 2023 |
| ASUSTek       | P8B75-V                     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| ASUSTek       | P8B75-V                     | [8957c4fdd0](https://linux-hardware.org/?probe=8957c4fdd0) | Apr 19, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e13bc4c0b8](https://linux-hardware.org/?probe=e13bc4c0b8) | Apr 04, 2023 |
| HP            | 1825                        | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| HP            | 1850                        | [1b56ff36d2](https://linux-hardware.org/?probe=1b56ff36d2) | Mar 10, 2023 |
| ASRock        | H67M-GE/HT                  | [3410887193](https://linux-hardware.org/?probe=3410887193) | Feb 25, 2023 |
| Gigabyte      | GB-BSi5-1135G7              | [93002e901f](https://linux-hardware.org/?probe=93002e901f) | Feb 10, 2023 |
| MSI           | H61M-P23                    | [86404b5b68](https://linux-hardware.org/?probe=86404b5b68) | Feb 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| Gigabyte      | B550M DS3H                  | [10ae4cbb25](https://linux-hardware.org/?probe=10ae4cbb25) | Jan 08, 2023 |
| Gigabyte      | H410M H V3                  | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| HP            | 3397                        | [27c0a5213d](https://linux-hardware.org/?probe=27c0a5213d) | Nov 11, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [4f1e0d9702](https://linux-hardware.org/?probe=4f1e0d9702) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [842320d7b3](https://linux-hardware.org/?probe=842320d7b3) | Nov 02, 2022 |
| Lenovo        | ThinkCentre M81 5048E2G     | [35840b3b8c](https://linux-hardware.org/?probe=35840b3b8c) | Oct 23, 2022 |
| HP            | 3047h                       | [1a0f4c46f9](https://linux-hardware.org/?probe=1a0f4c46f9) | Oct 20, 2022 |
| BESSTAR Te... | UM700                       | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| ASUSTek       | M5A97 R2.0                  | [96e0712ca0](https://linux-hardware.org/?probe=96e0712ca0) | Sep 19, 2022 |
| Gigabyte      | EX58-UD3R                   | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| MSI           | MAG B460M MORTAR            | [258d99cc9e](https://linux-hardware.org/?probe=258d99cc9e) | Sep 06, 2022 |
| Gigabyte      | GA-970A-D3                  | [5ee4e3aec0](https://linux-hardware.org/?probe=5ee4e3aec0) | Sep 02, 2022 |
| ASRock        | B550M Pro4                  | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASUSTek       | Maximus Formula             | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| Dell          | 07T4MC A11                  | [61d394116d](https://linux-hardware.org/?probe=61d394116d) | Jul 20, 2022 |
| ASUSTek       | Maximus Formula             | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | Maximus Formula             | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| MSI           | Z270-A PRO                  | [0d78267c59](https://linux-hardware.org/?probe=0d78267c59) | Jun 16, 2022 |
| Dell          | 02YYK5 A01                  | [bd3336efcb](https://linux-hardware.org/?probe=bd3336efcb) | Jun 14, 2022 |
| Dell          | 02YYK5 A01                  | [a068dc57c8](https://linux-hardware.org/?probe=a068dc57c8) | May 13, 2022 |
| Dell          | 02YYK5 A01                  | [96f6c5bf2a](https://linux-hardware.org/?probe=96f6c5bf2a) | May 10, 2022 |
| Dell          | 03NVJ6 A02                  | [9e90322621](https://linux-hardware.org/?probe=9e90322621) | May 06, 2022 |
| Dell          | 03NVJ6 A02                  | [08e665f8bf](https://linux-hardware.org/?probe=08e665f8bf) | May 04, 2022 |
| ASRock        | A320M-HDV R4.0              | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| Dell          | 02YYK5 A01                  | [a3bf1cf766](https://linux-hardware.org/?probe=a3bf1cf766) | Apr 19, 2022 |
| Dell          | 02YYK5 A01                  | [f2e4d7052d](https://linux-hardware.org/?probe=f2e4d7052d) | Apr 16, 2022 |
| MSI           | MEG X570 UNIFY              | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ba327aee7](https://linux-hardware.org/?probe=8ba327aee7) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| ASUSTek       | PRIME H510M-R               | [6736f1afa6](https://linux-hardware.org/?probe=6736f1afa6) | Apr 03, 2022 |
| Gigabyte      | B450M S2H                   | [aa02b40ff7](https://linux-hardware.org/?probe=aa02b40ff7) | Mar 27, 2022 |
| MSI           | B350 PC MATE                | [2e06b2fed8](https://linux-hardware.org/?probe=2e06b2fed8) | Feb 27, 2022 |
| ASRock        | QC5000M-ITX/PH              | [573ff5a0d0](https://linux-hardware.org/?probe=573ff5a0d0) | Feb 16, 2022 |
| MSI           | B450M MORTAR MAX            | [54f55cc209](https://linux-hardware.org/?probe=54f55cc209) | Feb 16, 2022 |
| ASUSTek       | Maximus Formula             | [130c778a64](https://linux-hardware.org/?probe=130c778a64) | Feb 11, 2022 |
| ASUSTek       | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [5616230c16](https://linux-hardware.org/?probe=5616230c16) | Feb 01, 2022 |
| ASUSTek       | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [d824937c84](https://linux-hardware.org/?probe=d824937c84) | Dec 22, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [1252e4adb0](https://linux-hardware.org/?probe=1252e4adb0) | Dec 18, 2021 |
| ASRock        | B450 Pro4                   | [cc0c8de988](https://linux-hardware.org/?probe=cc0c8de988) | Nov 27, 2021 |
| Dell          | 084J0R A00                  | [2f5b5e4c72](https://linux-hardware.org/?probe=2f5b5e4c72) | Nov 19, 2021 |
| Dell          | 084J0R A00                  | [1907e644a0](https://linux-hardware.org/?probe=1907e644a0) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b1edada81b](https://linux-hardware.org/?probe=b1edada81b) | Nov 13, 2021 |
| MSI           | MEG X570 UNIFY              | [7b9e7ec5f4](https://linux-hardware.org/?probe=7b9e7ec5f4) | Oct 23, 2021 |
| MSI           | B85M GAMING                 | [55468e657e](https://linux-hardware.org/?probe=55468e657e) | Oct 16, 2021 |
| ASUSTek       | X79-DELUXE                  | [c49552f889](https://linux-hardware.org/?probe=c49552f889) | Oct 14, 2021 |
| ASUSTek       | X79-DELUXE                  | [d606b23e02](https://linux-hardware.org/?probe=d606b23e02) | Oct 14, 2021 |
| ASUSTek       | Maximus Formula             | [34c7038f6f](https://linux-hardware.org/?probe=34c7038f6f) | Sep 12, 2021 |
| HP            | 09F8h                       | [60e1a81b56](https://linux-hardware.org/?probe=60e1a81b56) | Sep 05, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [057cfec49e](https://linux-hardware.org/?probe=057cfec49e) | Sep 01, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [523f5ca193](https://linux-hardware.org/?probe=523f5ca193) | Aug 23, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [90e24e0335](https://linux-hardware.org/?probe=90e24e0335) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | [1c59d4f975](https://linux-hardware.org/?probe=1c59d4f975) | Aug 19, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| MSI           | MAG B460M MORTAR            | [652f1a31e9](https://linux-hardware.org/?probe=652f1a31e9) | Aug 10, 2021 |
| MSI           | MAG B460M MORTAR            | [80648f256b](https://linux-hardware.org/?probe=80648f256b) | Aug 10, 2021 |
| ASRock        | G31M-VS2                    | [ffde05f551](https://linux-hardware.org/?probe=ffde05f551) | Aug 01, 2021 |
| ASRock        | Z87 Extreme4                | [ee3189a7be](https://linux-hardware.org/?probe=ee3189a7be) | Jul 11, 2021 |
| ASRock        | X570M Pro4                  | [714a2fb6ec](https://linux-hardware.org/?probe=714a2fb6ec) | Jul 02, 2021 |
| Gigabyte      | P41-ES3G                    | [653a634621](https://linux-hardware.org/?probe=653a634621) | Jun 29, 2021 |
| ASUSTek       | PRIME B450M-K               | [e78af672d3](https://linux-hardware.org/?probe=e78af672d3) | Jun 18, 2021 |
| MSI           | H81M-P33                    | [ab8a093d72](https://linux-hardware.org/?probe=ab8a093d72) | May 12, 2021 |
| Gigabyte      | M55S-S3                     | [7114f9857a](https://linux-hardware.org/?probe=7114f9857a) | Apr 29, 2021 |
| ASUSTek       | PRIME B450M-K               | [dc665ba00d](https://linux-hardware.org/?probe=dc665ba00d) | Apr 14, 2021 |
| Gigabyte      | B85M-HD3                    | [499ccddfc2](https://linux-hardware.org/?probe=499ccddfc2) | Apr 09, 2021 |
| MSI           | MAG B460M MORTAR            | [f7341fd5b2](https://linux-hardware.org/?probe=f7341fd5b2) | Apr 01, 2021 |
| Gigabyte      | H81M-D2V                    | [d62d3a2dad](https://linux-hardware.org/?probe=d62d3a2dad) | Mar 19, 2021 |
| HP            | 805A                        | [76ad927d3b](https://linux-hardware.org/?probe=76ad927d3b) | Mar 18, 2021 |
| Gigabyte      | B85M-HD3                    | [ad58858e33](https://linux-hardware.org/?probe=ad58858e33) | Mar 17, 2021 |
| Intel         | DH67BL AAG10189-208         | [391c72b961](https://linux-hardware.org/?probe=391c72b961) | Mar 17, 2021 |
| Intel         | DH55HC AAE70933-501         | [6a44f69309](https://linux-hardware.org/?probe=6a44f69309) | Mar 17, 2021 |
| Gigabyte      | H55M-UD2H                   | [e671743616](https://linux-hardware.org/?probe=e671743616) | Mar 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [d4e62a32a8](https://linux-hardware.org/?probe=d4e62a32a8) | Mar 04, 2021 |
| ASUSTek       | M5A97 R2.0                  | [7ab4c4e090](https://linux-hardware.org/?probe=7ab4c4e090) | Mar 03, 2021 |
| Gigabyte      | Z370M DS3H-CF               | [e4702a62a8](https://linux-hardware.org/?probe=e4702a62a8) | Feb 19, 2021 |
| Gigabyte      | A320M-H-CF                  | [ceffe7a79e](https://linux-hardware.org/?probe=ceffe7a79e) | Feb 16, 2021 |
| Intel         | DH61WW AAG23116-206         | [446351d845](https://linux-hardware.org/?probe=446351d845) | Feb 15, 2021 |
| ASUSTek       | Maximus Formula             | [b5e1004909](https://linux-hardware.org/?probe=b5e1004909) | Feb 12, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [504106eb2c](https://linux-hardware.org/?probe=504106eb2c) | Feb 12, 2021 |
| ASUSTek       | H87M-PLUS                   | [c951026b91](https://linux-hardware.org/?probe=c951026b91) | Feb 07, 2021 |
| ASUSTek       | Maximus Formula             | [80724d2ba1](https://linux-hardware.org/?probe=80724d2ba1) | Jan 31, 2021 |
| ASRock        | H61M/U3S3                   | [2d831a72bb](https://linux-hardware.org/?probe=2d831a72bb) | Jan 27, 2021 |
| Gigabyte      | B250M-D3H-CF                | [a38c700d1b](https://linux-hardware.org/?probe=a38c700d1b) | Jan 16, 2021 |
| ASUSTek       | H87M-PLUS                   | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| ASUSTek       | Leonite2                    | [9867e750d0](https://linux-hardware.org/?probe=9867e750d0) | Jan 01, 2021 |
| ASRock        | B450M Pro4                  | [649ea3d331](https://linux-hardware.org/?probe=649ea3d331) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | [5c89245f08](https://linux-hardware.org/?probe=5c89245f08) | Dec 02, 2020 |
| ASUSTek       | H87M-PLUS                   | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| Gigabyte      | H81M-D2V                    | [49bd67196b](https://linux-hardware.org/?probe=49bd67196b) | Nov 20, 2020 |
| ASRock        | 880GM-LE FX                 | [c16ef7ddf0](https://linux-hardware.org/?probe=c16ef7ddf0) | Nov 09, 2020 |
| Gigabyte      | H77M-D3H                    | [2788cb02ed](https://linux-hardware.org/?probe=2788cb02ed) | Nov 08, 2020 |
| HP            | 3048h                       | [96c9bd0ab6](https://linux-hardware.org/?probe=96c9bd0ab6) | Nov 05, 2020 |
| MSI           | Z87M-G43                    | [9de0cc7bbf](https://linux-hardware.org/?probe=9de0cc7bbf) | Nov 03, 2020 |
| HP            | 0A64h                       | [88899b775b](https://linux-hardware.org/?probe=88899b775b) | Oct 20, 2020 |
| ASUSTek       | H87M-PLUS                   | [a5e1c0e5f3](https://linux-hardware.org/?probe=a5e1c0e5f3) | Oct 03, 2020 |
| ASUSTek       | H87M-PLUS                   | [0362c406d8](https://linux-hardware.org/?probe=0362c406d8) | Oct 03, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [b765d71b82](https://linux-hardware.org/?probe=b765d71b82) | Sep 28, 2020 |
| Gigabyte      | H81M-D2V                    | [c46dd29f7a](https://linux-hardware.org/?probe=c46dd29f7a) | Sep 17, 2020 |
| ASUSTek       | PRIME B450M-A               | [d4d40f1808](https://linux-hardware.org/?probe=d4d40f1808) | Sep 04, 2020 |
| ASUSTek       | PRIME A320M-R               | [0097d71249](https://linux-hardware.org/?probe=0097d71249) | Sep 04, 2020 |
| ASUSTek       | PRIME Z390-A                | [4bd12a2bcc](https://linux-hardware.org/?probe=4bd12a2bcc) | Aug 25, 2020 |
| ASRock        | AB350M Pro4                 | [a5338ac2ec](https://linux-hardware.org/?probe=a5338ac2ec) | Aug 22, 2020 |
| Gigabyte      | M68MT-S2P                   | [f6a94becbf](https://linux-hardware.org/?probe=f6a94becbf) | Aug 13, 2020 |
| MSI           | H81M-P33                    | [5d7abb7a5b](https://linux-hardware.org/?probe=5d7abb7a5b) | Jul 31, 2020 |
| ASUSTek       | PRIME H310M-E               | [f31ba594be](https://linux-hardware.org/?probe=f31ba594be) | Jul 19, 2020 |
| ASUSTek       | PRIME H310M-E               | [90f3c751dc](https://linux-hardware.org/?probe=90f3c751dc) | Jul 19, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [ab2ec330ab](https://linux-hardware.org/?probe=ab2ec330ab) | Jun 24, 2020 |
| ASUSTek       | M5A97 R2.0                  | [feebe9e438](https://linux-hardware.org/?probe=feebe9e438) | Jun 03, 2020 |
| Intel         | DP55WB AAE64798-205         | [cbc58485b8](https://linux-hardware.org/?probe=cbc58485b8) | Apr 23, 2020 |
| MSI           | H61M-P20                    | [bd9fc44d34](https://linux-hardware.org/?probe=bd9fc44d34) | Mar 17, 2020 |
| MSI           | H61M-P20                    | [9111061475](https://linux-hardware.org/?probe=9111061475) | Mar 10, 2020 |
| MSI           | Z170A GAMING M5             | [f1eb3e7e12](https://linux-hardware.org/?probe=f1eb3e7e12) | Mar 01, 2020 |
| MSI           | Z170A GAMING M5             | [7058bdb7d6](https://linux-hardware.org/?probe=7058bdb7d6) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | [816d9c42da](https://linux-hardware.org/?probe=816d9c42da) | Feb 28, 2020 |
| HP            | 1589                        | [0c9be85544](https://linux-hardware.org/?probe=0c9be85544) | Feb 21, 2020 |
| ASUSTek       | P8Z68-V LX                  | [2d24c5a932](https://linux-hardware.org/?probe=2d24c5a932) | Feb 15, 2020 |
| ASUSTek       | PRIME B350M-A               | [c95a831b3c](https://linux-hardware.org/?probe=c95a831b3c) | Feb 11, 2020 |
| ASUSTek       | H87M-PLUS                   | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| MSI           | B450M PRO-VDH               | [5b95761a5d](https://linux-hardware.org/?probe=5b95761a5d) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH V2            | [660da3e630](https://linux-hardware.org/?probe=660da3e630) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH               | [f45d7203c0](https://linux-hardware.org/?probe=f45d7203c0) | Jan 03, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [b0c00423bd](https://linux-hardware.org/?probe=b0c00423bd) | Dec 31, 2019 |
| MSI           | B450M PRO-VDH               | [924e886e1f](https://linux-hardware.org/?probe=924e886e1f) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | [4a5d98c236](https://linux-hardware.org/?probe=4a5d98c236) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | [b919c0cb27](https://linux-hardware.org/?probe=b919c0cb27) | Dec 13, 2019 |
| ASRock        | H61M-VS                     | [6d7e3aa70a](https://linux-hardware.org/?probe=6d7e3aa70a) | Dec 11, 2019 |
| ASUSTek       | H110M-R                     | [3068ae6e29](https://linux-hardware.org/?probe=3068ae6e29) | Nov 05, 2019 |
| ASUSTek       | H110M-R                     | [dc23169db8](https://linux-hardware.org/?probe=dc23169db8) | Oct 10, 2019 |
| ASUSTek       | P5QPL-AM                    | [ec4b0c74d2](https://linux-hardware.org/?probe=ec4b0c74d2) | Sep 27, 2019 |
| HP            | 0A60h                       | [e587b4122a](https://linux-hardware.org/?probe=e587b4122a) | Sep 22, 2019 |
| Gigabyte      | B250M-DS3H-CF               | [fd394cc113](https://linux-hardware.org/?probe=fd394cc113) | Jun 05, 2019 |
| ASRock        | X370 Taichi                 | [283ce85ac6](https://linux-hardware.org/?probe=283ce85ac6) | Feb 20, 2019 |
| Dell          | 0XFWHV A00                  | [f9e47efc1f](https://linux-hardware.org/?probe=f9e47efc1f) | Jan 12, 2019 |
| MSI           | Z170A GAMING M5             | [68365011c2](https://linux-hardware.org/?probe=68365011c2) | Oct 26, 2018 |
| Intel         | DB65AL AAG12530-302         | [be0b280760](https://linux-hardware.org/?probe=be0b280760) | Oct 25, 2018 |
| HP            | 0A60h                       | [887d9e063a](https://linux-hardware.org/?probe=887d9e063a) | Sep 24, 2018 |
| HP            | 0A60h                       | [180ad06c55](https://linux-hardware.org/?probe=180ad06c55) | Aug 21, 2018 |
| HP            | 0A60h                       | [4ed0a42e5c](https://linux-hardware.org/?probe=4ed0a42e5c) | Jun 30, 2018 |
| ASUSTek       | M4A785T-M                   | [0f2664d3b1](https://linux-hardware.org/?probe=0f2664d3b1) | Mar 29, 2018 |
| ASUSTek       | M4A785T-M                   | [1a91c5f47f](https://linux-hardware.org/?probe=1a91c5f47f) | Mar 05, 2018 |
| Intel         | D102GGC2 AAD42789-201       | [d52ebc3540](https://linux-hardware.org/?probe=d52ebc3540) | Jan 09, 2018 |
| Intel         | D102GGC2 AAD42789-201       | [16d64740e8](https://linux-hardware.org/?probe=16d64740e8) | Jan 09, 2018 |
| ASRock        | ALiveDual-eSATA2            | [7330a7e461](https://linux-hardware.org/?probe=7330a7e461) | Sep 27, 2017 |
| ASRock        | 980DE3/U3S3 R2.0            | [ce9b629fa0](https://linux-hardware.org/?probe=ce9b629fa0) | Apr 21, 2017 |
| ASRock        | G41M-VS3                    | [8915ed904a](https://linux-hardware.org/?probe=8915ed904a) | Mar 14, 2017 |
| ASRock        | G41C-VS                     | [3688013a36](https://linux-hardware.org/?probe=3688013a36) | Dec 02, 2016 |
| ASRock        | G41C-VS                     | [9f9c0116cd](https://linux-hardware.org/?probe=9f9c0116cd) | Nov 30, 2016 |
| ASRock        | G41C-VS                     | [a1993f9fc4](https://linux-hardware.org/?probe=a1993f9fc4) | Nov 28, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Arch Rolling                 | 13       | 6.67%   |
| Ubuntu 22.04                 | 9        | 4.62%   |
| Ubuntu 20.04                 | 7        | 3.59%   |
| Ubuntu 18.04                 | 6        | 3.08%   |
| Pop!_OS 22.04                | 6        | 3.08%   |
| Arch                         | 6        | 3.08%   |
| Manjaro                      | 5        | 2.56%   |
| Ubuntu 24.04                 | 4        | 2.05%   |
| Ubuntu 21.10                 | 4        | 2.05%   |
| Ubuntu 19.10                 | 4        | 2.05%   |
| OpenMandriva 23.01           | 4        | 2.05%   |
| Debian 12                    | 4        | 2.05%   |
| Debian 11                    | 4        | 2.05%   |
| ROSA R8.1                    | 3        | 1.54%   |
| ROSA R11                     | 3        | 1.54%   |
| ROSA R10                     | 3        | 1.54%   |
| Pop!_OS 21.10                | 3        | 1.54%   |
| Pop!_OS 21.04                | 3        | 1.54%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.54%   |
| OpenMandriva 4.2             | 3        | 1.54%   |
| OpenMandriva 25.01           | 3        | 1.54%   |
| Manjaro 20.2.1               | 3        | 1.54%   |
| KDE neon 20.04               | 3        | 1.54%   |
| Fedora 41                    | 3        | 1.54%   |
| Fedora 33                    | 3        | 1.54%   |
| Bazzite 42                   | 3        | 1.54%   |
| Zorin 16                     | 2        | 1.03%   |
| Ubuntu 23.04                 | 2        | 1.03%   |
| Ubuntu 20.10                 | 2        | 1.03%   |
| ROSA 12.2                    | 2        | 1.03%   |
| OpenMandriva 25.90           | 2        | 1.03%   |
| OpenMandriva 23.08           | 2        | 1.03%   |
| OpenMandriva 23.03           | 2        | 1.03%   |
| Linux Mint 19.3              | 2        | 1.03%   |
| Kubuntu 20.04                | 2        | 1.03%   |
| Fedora 32                    | 2        | 1.03%   |
| Debian 10                    | 2        | 1.03%   |
| Artix Rolling                | 2        | 1.03%   |
| ArcoLinux Rolling            | 2        | 1.03%   |
| Zorin 17                     | 1        | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 38       | 20.65%  |
| OpenMandriva | 21       | 11.41%  |
| Arch         | 17       | 9.24%   |
| ROSA         | 13       | 7.07%   |
| Pop!_OS      | 13       | 7.07%   |
| Manjaro      | 12       | 6.52%   |
| Fedora       | 11       | 5.98%   |
| Linux Mint   | 10       | 5.43%   |
| Debian       | 9        | 4.89%   |
| KDE neon     | 5        | 2.72%   |
| Kubuntu      | 4        | 2.17%   |
| Zorin        | 3        | 1.63%   |
| openSUSE     | 3        | 1.63%   |
| Bazzite      | 3        | 1.63%   |
| Nobara       | 2        | 1.09%   |
| Artix        | 2        | 1.09%   |
| ArcoLinux    | 2        | 1.09%   |
| Xubuntu      | 1        | 0.54%   |
| Ubuntu Unity | 1        | 0.54%   |
| SteamOS      | 1        | 0.54%   |
| Sparky       | 1        | 0.54%   |
| RHEL         | 1        | 0.54%   |
| MX           | 1        | 0.54%   |
| Lubuntu      | 1        | 0.54%   |
| LMDE         | 1        | 0.54%   |
| Garuda Linux | 1        | 0.54%   |
| Endless      | 1        | 0.54%   |
| EndeavourOS  | 1        | 0.54%   |
| Elementary   | 1        | 0.54%   |
| Deepin       | 1        | 0.54%   |
| Clear Linux  | 1        | 0.54%   |
| CentOS       | 1        | 0.54%   |
| CachyOS      | 1        | 0.54%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.14.2-desktop-3omv2590       | 4        | 1.8%    |
| 6.1.1-desktop-1omv2290        | 4        | 1.8%    |
| 6.12.9-desktop-1omv2490       | 3        | 1.35%   |
| 5.3.0-23-generic              | 3        | 1.35%   |
| 5.10.14-desktop-1omv4002      | 3        | 1.35%   |
| 6.9.3-76060903-generic        | 2        | 0.9%    |
| 6.8.0-45-generic              | 2        | 0.9%    |
| 6.2.6-desktop-1omv2390        | 2        | 0.9%    |
| 6.2.0-20-generic              | 2        | 0.9%    |
| 6.11.0-25-generic             | 2        | 0.9%    |
| 6.1.31-1-lts                  | 2        | 0.9%    |
| 5.9.16-1-MANJARO              | 2        | 0.9%    |
| 5.4.0-70-generic              | 2        | 0.9%    |
| 5.4.0-66-generic              | 2        | 0.9%    |
| 5.4.0-48-generic              | 2        | 0.9%    |
| 5.4.0-26-generic              | 2        | 0.9%    |
| 5.3.0-40-generic              | 2        | 0.9%    |
| 5.3.0-28-generic              | 2        | 0.9%    |
| 5.3.0-24-generic              | 2        | 0.9%    |
| 5.19.0-41-generic             | 2        | 0.9%    |
| 5.15.23-2-lts                 | 2        | 0.9%    |
| 5.15.0-47-generic             | 2        | 0.9%    |
| 5.15.0-46-generic             | 2        | 0.9%    |
| 5.11.0-7620-generic           | 2        | 0.9%    |
| 4.9.60-nrj-desktop-1rosa-i586 | 2        | 0.9%    |
| 6.9.3-zen1-1-zen              | 1        | 0.45%   |
| 6.9.3-arch1-1                 | 1        | 0.45%   |
| 6.9.2-zen1-1-zen              | 1        | 0.45%   |
| 6.8.9-zen1-2-zen              | 1        | 0.45%   |
| 6.8.7-arch1-1                 | 1        | 0.45%   |
| 6.8.6-zen1-1-zen              | 1        | 0.45%   |
| 6.8.5-301.fc40.x86_64         | 1        | 0.45%   |
| 6.8.0-87-generic              | 1        | 0.45%   |
| 6.8.0-51-generic              | 1        | 0.45%   |
| 6.8.0-50-generic              | 1        | 0.45%   |
| 6.6.68-x64v3-xanmod1          | 1        | 0.45%   |
| 6.6.6-76060606-generic        | 1        | 0.45%   |
| 6.6.5-x64v2-xanmod1-1         | 1        | 0.45%   |
| 6.6.4-zen1-1-zen              | 1        | 0.45%   |
| 6.6.3-1-default               | 1        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 13       | 6.25%   |
| 5.15.0  | 13       | 6.25%   |
| 5.3.0   | 8        | 3.85%   |
| 5.13.0  | 8        | 3.85%   |
| 4.15.0  | 8        | 3.85%   |
| 5.8.0   | 6        | 2.88%   |
| 5.11.0  | 6        | 2.88%   |
| 6.8.0   | 5        | 2.4%    |
| 6.1.0   | 5        | 2.4%    |
| 6.9.3   | 4        | 1.92%   |
| 6.14.2  | 4        | 1.92%   |
| 6.1.1   | 4        | 1.92%   |
| 5.19.0  | 4        | 1.92%   |
| 6.2.6   | 3        | 1.44%   |
| 6.2.0   | 3        | 1.44%   |
| 6.12.9  | 3        | 1.44%   |
| 6.11.0  | 3        | 1.44%   |
| 5.10.14 | 3        | 1.44%   |
| 5.10.0  | 3        | 1.44%   |
| 6.5.0   | 2        | 0.96%   |
| 6.3.5   | 2        | 0.96%   |
| 6.14.0  | 2        | 0.96%   |
| 6.1.31  | 2        | 0.96%   |
| 5.9.16  | 2        | 0.96%   |
| 5.15.23 | 2        | 0.96%   |
| 4.9.60  | 2        | 0.96%   |
| 4.19.0  | 2        | 0.96%   |
| 6.9.2   | 1        | 0.48%   |
| 6.8.9   | 1        | 0.48%   |
| 6.8.7   | 1        | 0.48%   |
| 6.8.6   | 1        | 0.48%   |
| 6.8.5   | 1        | 0.48%   |
| 6.6.68  | 1        | 0.48%   |
| 6.6.6   | 1        | 0.48%   |
| 6.6.5   | 1        | 0.48%   |
| 6.6.4   | 1        | 0.48%   |
| 6.6.3   | 1        | 0.48%   |
| 6.6.2   | 1        | 0.48%   |
| 6.6.14  | 1        | 0.48%   |
| 6.6.10  | 1        | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 19       | 9.27%   |
| 5.4     | 15       | 7.32%   |
| 5.10    | 12       | 5.85%   |
| 6.1     | 11       | 5.37%   |
| 6.8     | 9        | 4.39%   |
| 5.8     | 9        | 4.39%   |
| 5.13    | 9        | 4.39%   |
| 6.6     | 8        | 3.9%    |
| 5.3     | 8        | 3.9%    |
| 4.15    | 8        | 3.9%    |
| 6.14    | 7        | 3.41%   |
| 5.11    | 7        | 3.41%   |
| 4.9     | 7        | 3.41%   |
| 6.2     | 6        | 2.93%   |
| 6.12    | 6        | 2.93%   |
| 5.19    | 6        | 2.93%   |
| 6.4     | 5        | 2.44%   |
| 5.16    | 5        | 2.44%   |
| 6.9     | 4        | 1.95%   |
| 6.3     | 3        | 1.46%   |
| 6.15    | 3        | 1.46%   |
| 6.11    | 3        | 1.46%   |
| 6.10    | 3        | 1.46%   |
| 6.0     | 3        | 1.46%   |
| 5.9     | 3        | 1.46%   |
| 5.7     | 3        | 1.46%   |
| 5.12    | 3        | 1.46%   |
| 4.19    | 3        | 1.46%   |
| 4.14    | 3        | 1.46%   |
| 6.5     | 2        | 0.98%   |
| 6.16    | 2        | 0.98%   |
| 6.13    | 2        | 0.98%   |
| 5.18    | 2        | 0.98%   |
| 4.1     | 2        | 0.98%   |
| 6.17    | 1        | 0.49%   |
| 5.6     | 1        | 0.49%   |
| 5.5     | 1        | 0.49%   |
| 4.18    | 1        | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 175      | 97.22%  |
| i686   | 5        | 2.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 66       | 34.74%  |
| KDE5          | 34       | 17.89%  |
| Unknown       | 17       | 8.95%   |
| XFCE          | 14       | 7.37%   |
| KDE6          | 13       | 6.84%   |
| KDE4          | 11       | 5.79%   |
| X-Cinnamon    | 10       | 5.26%   |
| KDE           | 8        | 4.21%   |
| MATE          | 3        | 1.58%   |
| LXQt          | 3        | 1.58%   |
| Cinnamon      | 3        | 1.58%   |
| Hyprland      | 2        | 1.05%   |
| Unity         | 1        | 0.53%   |
| qtile         | 1        | 0.53%   |
| Pantheon      | 1        | 0.53%   |
| i3            | 1        | 0.53%   |
| Enlightenment | 1        | 0.53%   |
| Deepin        | 1        | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 130      | 69.52%  |
| Wayland | 45       | 24.06%  |
| Unknown | 7        | 3.74%   |
| Tty     | 5        | 2.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 79       | 42.93%  |
| SDDM    | 39       | 21.2%   |
| LightDM | 18       | 9.78%   |
| GDM     | 17       | 9.24%   |
| GDM3    | 15       | 8.15%   |
| KDM     | 10       | 5.43%   |
| TDM     | 6        | 3.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 122      | 67.4%   |
| lt_LT   | 19       | 10.5%   |
| Unknown | 16       | 8.84%   |
| en_GB   | 14       | 7.73%   |
| ru_RU   | 7        | 3.87%   |
| C       | 2        | 1.1%    |
| uk_UA   | 1        | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 109      | 60.22%  |
| EFI  | 72       | 39.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 120      | 65.57%  |
| Btrfs   | 29       | 15.85%  |
| Overlay | 16       | 8.74%   |
| Unknown | 7        | 3.83%   |
| Tmpfs   | 5        | 2.73%   |
| Xfs     | 4        | 2.19%   |
| SAMSUNG | 1        | 0.55%   |
| F2fs    | 1        | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 76       | 41.53%  |
| GPT     | 75       | 40.98%  |
| MBR     | 32       | 17.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 81.67%  |
| Yes       | 33       | 18.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 69.23%  |
| Yes       | 56       | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 47       | 26.26%  |
| MSI                 | 31       | 17.32%  |
| ASRock              | 31       | 17.32%  |
| Gigabyte Technology | 29       | 16.2%   |
| Hewlett-Packard     | 14       | 7.82%   |
| Intel               | 8        | 4.47%   |
| Dell                | 7        | 3.91%   |
| Lenovo              | 3        | 1.68%   |
| Acer                | 2        | 1.12%   |
| Unknown             | 2        | 1.12%   |
| KMP                 | 1        | 0.56%   |
| Fujitsu Siemens     | 1        | 0.56%   |
| Fujitsu             | 1        | 0.56%   |
| BESSTAR Tech        | 1        | 0.56%   |
| AMI                 | 1        | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                          | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| MSI MS-7A38                                   | 3        | 1.68%   |
| MSI MS-7817                                   | 3        | 1.68%   |
| ASUS All Series                               | 3        | 1.68%   |
| MSI MS-7C91                                   | 2        | 1.12%   |
| MSI MS-7C82                                   | 2        | 1.12%   |
| MSI MS-7A34                                   | 2        | 1.12%   |
| MSI MS-7823                                   | 2        | 1.12%   |
| ASUS TUF Gaming X570-PLUS                     | 2        | 1.12%   |
| ASUS TUF Gaming B550-PLUS                     | 2        | 1.12%   |
| ASUS PRIME Z390-A                             | 2        | 1.12%   |
| ASUS PRIME B450M-K                            | 2        | 1.12%   |
| ASUS PRIME B450M-A                            | 2        | 1.12%   |
| ASRock B550M Pro4                             | 2        | 1.12%   |
| ASRock B450M-HDV R4.0                         | 2        | 1.12%   |
| ASRock B450 Pro4                              | 2        | 1.12%   |
| Acer Veriton EN2580                           | 2        | 1.12%   |
| Unknown                                       | 2        | 1.12%   |
| MSI MS-7D91                                   | 1        | 0.56%   |
| MSI MS-7D77                                   | 1        | 0.56%   |
| MSI MS-7D14                                   | 1        | 0.56%   |
| MSI MS-7C95                                   | 1        | 0.56%   |
| MSI MS-7C60                                   | 1        | 0.56%   |
| MSI MS-7C56                                   | 1        | 0.56%   |
| MSI MS-7C37                                   | 1        | 0.56%   |
| MSI MS-7C35                                   | 1        | 0.56%   |
| MSI MS-7C02                                   | 1        | 0.56%   |
| MSI MS-7B89                                   | 1        | 0.56%   |
| MSI MS-7B86                                   | 1        | 0.56%   |
| MSI MS-7B18                                   | 1        | 0.56%   |
| MSI MS-7A71                                   | 1        | 0.56%   |
| MSI MS-7977                                   | 1        | 0.56%   |
| MSI MS-7971                                   | 1        | 0.56%   |
| MSI MS-7788                                   | 1        | 0.56%   |
| MSI MS-7680                                   | 1        | 0.56%   |
| Lenovo ThinkStation P520 30BFS0XK0C           | 1        | 0.56%   |
| Lenovo ThinkStation P3 Tower Gen 2 30HSS57W00 | 1        | 0.56%   |
| Lenovo ThinkCentre M81 5048E2G                | 1        | 0.56%   |
| KMP IS85E                                     | 1        | 0.56%   |
| Intel DQ965GF AAD41676-402                    | 1        | 0.56%   |
| Intel DP55WB AAE64798-205                     | 1        | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 17       | 9.5%    |
| HP Compaq           | 7        | 3.91%   |
| ASUS TUF            | 6        | 3.35%   |
| Dell OptiPlex       | 4        | 2.23%   |
| ASUS ROG            | 4        | 2.23%   |
| MSI MS-7A38         | 3        | 1.68%   |
| MSI MS-7817         | 3        | 1.68%   |
| Gigabyte X570       | 3        | 1.68%   |
| ASUS All            | 3        | 1.68%   |
| ASRock B550M        | 3        | 1.68%   |
| ASRock B450         | 3        | 1.68%   |
| MSI MS-7C91         | 2        | 1.12%   |
| MSI MS-7C82         | 2        | 1.12%   |
| MSI MS-7A34         | 2        | 1.12%   |
| MSI MS-7823         | 2        | 1.12%   |
| Lenovo ThinkStation | 2        | 1.12%   |
| HP EliteDesk        | 2        | 1.12%   |
| Dell Vostro         | 2        | 1.12%   |
| ASRock B450M-HDV    | 2        | 1.12%   |
| Acer Veriton        | 2        | 1.12%   |
| Unknown             | 2        | 1.12%   |
| MSI MS-7D91         | 1        | 0.56%   |
| MSI MS-7D77         | 1        | 0.56%   |
| MSI MS-7D14         | 1        | 0.56%   |
| MSI MS-7C95         | 1        | 0.56%   |
| MSI MS-7C60         | 1        | 0.56%   |
| MSI MS-7C56         | 1        | 0.56%   |
| MSI MS-7C37         | 1        | 0.56%   |
| MSI MS-7C35         | 1        | 0.56%   |
| MSI MS-7C02         | 1        | 0.56%   |
| MSI MS-7B89         | 1        | 0.56%   |
| MSI MS-7B86         | 1        | 0.56%   |
| MSI MS-7B18         | 1        | 0.56%   |
| MSI MS-7A71         | 1        | 0.56%   |
| MSI MS-7977         | 1        | 0.56%   |
| MSI MS-7971         | 1        | 0.56%   |
| MSI MS-7788         | 1        | 0.56%   |
| MSI MS-7680         | 1        | 0.56%   |
| Lenovo ThinkCentre  | 1        | 0.56%   |
| KMP IS85E           | 1        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 28       | 15.64%  |
| 2020 | 17       | 9.5%    |
| 2021 | 15       | 8.38%   |
| 2015 | 12       | 6.7%    |
| 2013 | 12       | 6.7%    |
| 2012 | 12       | 6.7%    |
| 2009 | 12       | 6.7%    |
| 2011 | 10       | 5.59%   |
| 2019 | 9        | 5.03%   |
| 2016 | 9        | 5.03%   |
| 2017 | 8        | 4.47%   |
| 2010 | 6        | 3.35%   |
| 2007 | 5        | 2.79%   |
| 2023 | 4        | 2.23%   |
| 2022 | 4        | 2.23%   |
| 2014 | 4        | 2.23%   |
| 2006 | 4        | 2.23%   |
| 2025 | 2        | 1.12%   |
| 2024 | 2        | 1.12%   |
| 2008 | 2        | 1.12%   |
| 2005 | 1        | 0.56%   |
| 2004 | 1        | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 179      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 174      | 96.67%  |
| Enabled  | 6        | 3.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 179      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 50       | 27.47%  |
| 32.01-64.0  | 37       | 20.33%  |
| 8.01-16.0   | 27       | 14.84%  |
| 4.01-8.0    | 23       | 12.64%  |
| 3.01-4.0    | 22       | 12.09%  |
| 64.01-256.0 | 12       | 6.59%   |
| 24.01-32.0  | 4        | 2.2%    |
| 1.01-2.0    | 4        | 2.2%    |
| 2.01-3.0    | 2        | 1.1%    |
| 0.51-1.0    | 1        | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 51       | 24.76%  |
| 4.01-8.0   | 46       | 22.33%  |
| 2.01-3.0   | 39       | 18.93%  |
| 3.01-4.0   | 31       | 15.05%  |
| 8.01-16.0  | 16       | 7.77%   |
| 0.51-1.0   | 14       | 6.8%    |
| 16.01-24.0 | 4        | 1.94%   |
| 0.01-0.5   | 3        | 1.46%   |
| 24.01-32.0 | 2        | 0.97%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 68       | 36.17%  |
| 2      | 63       | 33.51%  |
| 3      | 32       | 17.02%  |
| 4      | 14       | 7.45%   |
| 5      | 7        | 3.72%   |
| 6      | 2        | 1.06%   |
| 7      | 1        | 0.53%   |
| 0      | 1        | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 128      | 69.95%  |
| Yes       | 55       | 30.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 178      | 99.44%  |
| No        | 1        | 0.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 67.76%  |
| Yes       | 59       | 32.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 128      | 71.51%  |
| Yes       | 51       | 28.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Lithuania | 179      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Vilnius      | 88       | 48.09%  |
| Kaunas       | 36       | 19.67%  |
| Klaipėda    | 12       | 6.56%   |
| Šiauliai    | 10       | 5.46%   |
| Mažeikiai   | 6        | 3.28%   |
| Panevezys    | 3        | 1.64%   |
| Alytus       | 3        | 1.64%   |
| Telšiai     | 2        | 1.09%   |
| Garliava     | 2        | 1.09%   |
| Elektrėnai  | 2        | 1.09%   |
| Zapyškis    | 1        | 0.55%   |
| Vainutas     | 1        | 0.55%   |
| Utena        | 1        | 0.55%   |
| Ukmerge      | 1        | 0.55%   |
| Trakai       | 1        | 0.55%   |
| Tauragė     | 1        | 0.55%   |
| Šilalė     | 1        | 0.55%   |
| Raseiniai    | 1        | 0.55%   |
| Pakruojis    | 1        | 0.55%   |
| Nemenčinė  | 1        | 0.55%   |
| Marijampolė | 1        | 0.55%   |
| Lentvaris    | 1        | 0.55%   |
| Kuliai       | 1        | 0.55%   |
| Kėdainiai   | 1        | 0.55%   |
| Gargždai    | 1        | 0.55%   |
| Druskininkai | 1        | 0.55%   |
| Anykščiai  | 1        | 0.55%   |
| Aleksandrija | 1        | 0.55%   |
| Agluonenai   | 1        | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 65       | 130    | 19.17%  |
| WDC                          | 51       | 71     | 15.04%  |
| Seagate                      | 38       | 51     | 11.21%  |
| A-DATA Technology            | 26       | 30     | 7.67%   |
| Kingston                     | 23       | 35     | 6.78%   |
| Toshiba                      | 21       | 29     | 6.19%   |
| Crucial                      | 17       | 23     | 5.01%   |
| Sandisk                      | 13       | 15     | 3.83%   |
| Patriot                      | 11       | 11     | 3.24%   |
| Hitachi                      | 7        | 7      | 2.06%   |
| ADATA Technology             | 5        | 6      | 1.47%   |
| Micron/Crucial Technology    | 4        | 7      | 1.18%   |
| MAXIO Technology (Hangzhou)  | 4        | 7      | 1.18%   |
| China                        | 4        | 4      | 1.18%   |
| Intel                        | 3        | 4      | 0.88%   |
| HGST                         | 3        | 4      | 0.88%   |
| GOODRAM                      | 3        | 3      | 0.88%   |
| Gigabyte Technology          | 3        | 3      | 0.88%   |
| Corsair                      | 3        | 5      | 0.88%   |
| XrayDisk                     | 2        | 2      | 0.59%   |
| XPG                          | 2        | 2      | 0.59%   |
| Unknown                      | 2        | 2      | 0.59%   |
| Transcend                    | 2        | 2      | 0.59%   |
| SPCC                         | 2        | 2      | 0.59%   |
| KIOXIA                       | 2        | 4      | 0.59%   |
| JMicron Technology           | 2        | 2      | 0.59%   |
| Intenso                      | 2        | 3      | 0.59%   |
| Apacer                       | 2        | 4      | 0.59%   |
| StoreJet                     | 1        | 1      | 0.29%   |
| Silicon Motion               | 1        | 1      | 0.29%   |
| Shenzhen Longsys Electronics | 1        | 3      | 0.29%   |
| Realtek Semiconductor        | 1        | 1      | 0.29%   |
| PNY                          | 1        | 1      | 0.29%   |
| Plextor                      | 1        | 1      | 0.29%   |
| Phison                       | 1        | 1      | 0.29%   |
| OCZ                          | 1        | 2      | 0.29%   |
| Netac                        | 1        | 1      | 0.29%   |
| MEMO                         | 1        | 1      | 0.29%   |
| Lite-On Technology           | 1        | 1      | 0.29%   |
| Leven                        | 1        | 3      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                    | 6        | 1.59%   |
| WDC WD20EFRX-68EUZN0 2TB                           | 5        | 1.32%   |
| Samsung SSD 860 EVO 250GB                          | 5        | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 5        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5        | 1.32%   |
| A-DATA SU650 120GB SSD                             | 5        | 1.32%   |
| Toshiba DT01ACA100 1TB                             | 4        | 1.06%   |
| Samsung SSD 860 EVO 500GB                          | 4        | 1.06%   |
| Samsung SSD 850 EVO 500GB                          | 4        | 1.06%   |
| Samsung SSD 850 EVO 250GB                          | 4        | 1.06%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                | 4        | 1.06%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB   | 4        | 1.06%   |
| Kingston SA400S37240G 240GB SSD                    | 4        | 1.06%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 3        | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB                     | 3        | 0.79%   |
| SanDisk NVMe SSD Drive 500GB                       | 3        | 0.79%   |
| Samsung SSD 860 EVO 1TB                            | 3        | 0.79%   |
| Samsung NVMe SSD Drive 1TB                         | 3        | 0.79%   |
| Samsung HD501LJ 500GB                              | 3        | 0.79%   |
| Patriot Burst 480GB SSD                            | 3        | 0.79%   |
| Patriot Burst 120GB SSD                            | 3        | 0.79%   |
| Kingston SV300S37A120G 120GB SSD                   | 3        | 0.79%   |
| Kingston SA400S37480G 480GB SSD                    | 3        | 0.79%   |
| Kingston SA400S37120G 120GB SSD                    | 3        | 0.79%   |
| Crucial CT1000MX500SSD1 1TB                        | 3        | 0.79%   |
| A-DATA SU650 240GB SSD                             | 3        | 0.79%   |
| A-DATA SP550 120GB SSD                             | 3        | 0.79%   |
| WDC WD800AAJS-60PSA0 80GB                          | 2        | 0.53%   |
| WDC WD5000AAKX-22ERMA0 500GB                       | 2        | 0.53%   |
| WDC WD5000AAKX-001CA0 500GB                        | 2        | 0.53%   |
| WDC WD10PURX-64E5EY0 1TB                           | 2        | 0.53%   |
| Toshiba MQ01ABD100 1TB                             | 2        | 0.53%   |
| Toshiba MK3261GSYN 320GB                           | 2        | 0.53%   |
| Toshiba HDWE140 4TB                                | 2        | 0.53%   |
| Toshiba HDWD120 2TB                                | 2        | 0.53%   |
| Toshiba HDWD110 1TB                                | 2        | 0.53%   |
| Seagate ST3500418AS 500GB                          | 2        | 0.53%   |
| Seagate ST2000VX000-1CU164 2TB                     | 2        | 0.53%   |
| Seagate ST2000DM006-2DM164 2TB                     | 2        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 46       | 66     | 36.51%  |
| Seagate             | 38       | 51     | 30.16%  |
| Toshiba             | 18       | 26     | 14.29%  |
| Samsung Electronics | 12       | 29     | 9.52%   |
| Hitachi             | 7        | 7      | 5.56%   |
| HGST                | 3        | 4      | 2.38%   |
| JMicron Technology  | 1        | 1      | 0.79%   |
| ExcelStor           | 1        | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 33       | 50     | 24.81%  |
| A-DATA Technology   | 21       | 25     | 15.79%  |
| Kingston            | 19       | 29     | 14.29%  |
| Crucial             | 14       | 20     | 10.53%  |
| Patriot             | 11       | 11     | 8.27%   |
| China               | 4        | 4      | 3.01%   |
| GOODRAM             | 3        | 3      | 2.26%   |
| XrayDisk            | 2        | 2      | 1.5%    |
| WDC                 | 2        | 2      | 1.5%    |
| Transcend           | 2        | 2      | 1.5%    |
| SPCC                | 2        | 2      | 1.5%    |
| Intenso             | 2        | 3      | 1.5%    |
| Intel               | 2        | 2      | 1.5%    |
| Gigabyte Technology | 2        | 2      | 1.5%    |
| Apacer              | 2        | 4      | 1.5%    |
| Unknown             | 1        | 1      | 0.75%   |
| Toshiba             | 1        | 1      | 0.75%   |
| StoreJet            | 1        | 1      | 0.75%   |
| PNY                 | 1        | 1      | 0.75%   |
| Plextor             | 1        | 1      | 0.75%   |
| OCZ                 | 1        | 2      | 0.75%   |
| Netac               | 1        | 1      | 0.75%   |
| Leven               | 1        | 3      | 0.75%   |
| Hewlett-Packard     | 1        | 1      | 0.75%   |
| Dahua               | 1        | 1      | 0.75%   |
| Corsair             | 1        | 1      | 0.75%   |
| Colorful            | 1        | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 111      | 176    | 38.95%  |
| HDD     | 101      | 185    | 35.44%  |
| NVMe    | 69       | 125    | 24.21%  |
| Unknown | 3        | 3      | 1.05%   |
| MMC     | 1        | 1      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 151      | 354    | 65.65%  |
| NVMe | 69       | 121    | 30%     |
| SAS  | 9        | 14     | 3.91%   |
| MMC  | 1        | 1      | 0.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 124      | 239    | 58.49%  |
| 0.51-1.0   | 55       | 74     | 25.94%  |
| 1.01-2.0   | 23       | 34     | 10.85%  |
| 3.01-4.0   | 4        | 7      | 1.89%   |
| 2.01-3.0   | 3        | 4      | 1.42%   |
| 4.01-10.0  | 2        | 2      | 0.94%   |
| 10.01-20.0 | 1        | 1      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 45       | 23.2%   |
| 251-500        | 31       | 15.98%  |
| 501-1000       | 30       | 15.46%  |
| 1001-2000      | 27       | 13.92%  |
| More than 3000 | 14       | 7.22%   |
| 2001-3000      | 13       | 6.7%    |
| 1-20           | 13       | 6.7%    |
| 51-100         | 9        | 4.64%   |
| Unknown        | 7        | 3.61%   |
| 21-50          | 5        | 2.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 61       | 29.61%  |
| 101-250        | 27       | 13.11%  |
| 21-50          | 23       | 11.17%  |
| 251-500        | 21       | 10.19%  |
| 51-100         | 19       | 9.22%   |
| 1001-2000      | 18       | 8.74%   |
| 501-1000       | 16       | 7.77%   |
| More than 3000 | 9        | 4.37%   |
| Unknown        | 7        | 3.4%    |
| 2001-3000      | 5        | 2.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Desktops | Drives | Percent |
|---------------------------------------------------------------|----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB                                      | 3        | 7      | 9.09%   |
| WDC WD800AAJS-60PSA0 80GB                                     | 2        | 2      | 6.06%   |
| Toshiba MK3261GSYN 320GB                                      | 2        | 2      | 6.06%   |
| WDC WD6400BPVT-80HXZT1 640GB                                  | 1        | 1      | 3.03%   |
| WDC WD5000AAKX-001CA0 500GB                                   | 1        | 1      | 3.03%   |
| WDC WD5000AAKS-00A7B2 500GB                                   | 1        | 1      | 3.03%   |
| WDC WD1600JS-60MHB5 160GB                                     | 1        | 1      | 3.03%   |
| WDC WD1003FBYX-01Y7B0 1TB                                     | 1        | 2      | 3.03%   |
| Toshiba MQ01ABD100 1TB                                        | 1        | 1      | 3.03%   |
| Seagate ST9500325AS 500GB                                     | 1        | 1      | 3.03%   |
| Seagate ST500LX012-SSHD-8GB                                   | 1        | 1      | 3.03%   |
| Seagate ST3500413AS 500GB                                     | 1        | 1      | 3.03%   |
| Seagate ST3250410AS 250GB                                     | 1        | 1      | 3.03%   |
| Seagate ST3250318AS 250GB                                     | 1        | 1      | 3.03%   |
| Seagate ST2000VX000-1CU164 2TB                                | 1        | 1      | 3.03%   |
| Samsung Electronics SSD 980 500GB                             | 1        | 1      | 3.03%   |
| Samsung Electronics NVMe SSD Controller 980 (DRAM-less) 256GB | 1        | 1      | 3.03%   |
| Samsung Electronics HD501LJ 500GB                             | 1        | 1      | 3.03%   |
| Samsung Electronics HD403LJ 400GB                             | 1        | 1      | 3.03%   |
| Samsung Electronics HD154UI 1TB                               | 1        | 1      | 3.03%   |
| Samsung Electronics HD103SJ 1TB                               | 1        | 1      | 3.03%   |
| Samsung Electronics HD080HJ/ 80GB                             | 1        | 4      | 3.03%   |
| Leven JAJS300M240C 240GB SSD                                  | 1        | 3      | 3.03%   |
| Kingston SV300S37A120G 120GB SSD                              | 1        | 1      | 3.03%   |
| Hitachi HTS547575A9E384 752GB                                 | 1        | 1      | 3.03%   |
| ExcelStor Technology J8160S 160GB                             | 1        | 1      | 3.03%   |
| Crucial CT525MX300SSD1 528GB                                  | 1        | 1      | 3.03%   |
| Colorful SL300 120GB                                          | 1        | 1      | 3.03%   |
| A-DATA Technology SX900 256GB SSD                             | 1        | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 15     | 32.26%  |
| Seagate             | 6        | 6      | 19.35%  |
| Samsung Electronics | 6        | 10     | 19.35%  |
| Toshiba             | 2        | 3      | 6.45%   |
| Leven               | 1        | 3      | 3.23%   |
| Kingston            | 1        | 1      | 3.23%   |
| Hitachi             | 1        | 1      | 3.23%   |
| ExcelStor           | 1        | 1      | 3.23%   |
| Crucial             | 1        | 1      | 3.23%   |
| Colorful            | 1        | 1      | 3.23%   |
| A-DATA Technology   | 1        | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 15     | 40%     |
| Seagate             | 6        | 6      | 24%     |
| Samsung Electronics | 5        | 8      | 20%     |
| Toshiba             | 2        | 3      | 8%      |
| Hitachi             | 1        | 1      | 4%      |
| ExcelStor           | 1        | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 34     | 76.92%  |
| SSD  | 5        | 7      | 19.23%  |
| NVMe | 1        | 2      | 3.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                         | Desktops | Drives | Percent |
|---------------------------------------------------------------|----------|--------|---------|
| Seagate ST3160812A 160GB                                      | 1        | 2      | 33.33%  |
| Samsung Electronics NVMe SSD Controller 980 (DRAM-less) 256GB | 1        | 1      | 33.33%  |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD              | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 66.67%  |
| Seagate             | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 92       | 260    | 45.1%   |
| Works    | 85       | 183    | 41.67%  |
| Malfunc  | 24       | 43     | 11.76%  |
| Failed   | 3        | 4      | 1.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 100      | 35.59%  |
| AMD                          | 76       | 27.05%  |
| Samsung Electronics          | 27       | 9.61%   |
| SanDisk                      | 15       | 5.34%   |
| ASMedia Technology           | 14       | 4.98%   |
| ADATA Technology             | 10       | 3.56%   |
| Micron/Crucial Technology    | 6        | 2.14%   |
| Kingston Technology Company  | 5        | 1.78%   |
| MAXIO Technology (Hangzhou)  | 4        | 1.42%   |
| Realtek Semiconductor        | 3        | 1.07%   |
| Phison Electronics           | 3        | 1.07%   |
| Nvidia                       | 3        | 1.07%   |
| Marvell Technology Group     | 3        | 1.07%   |
| JMicron Technology           | 3        | 1.07%   |
| KIOXIA                       | 2        | 0.71%   |
| Toshiba America Info Systems | 1        | 0.36%   |
| Silicon Motion               | 1        | 0.36%   |
| Shenzhen Longsys Electronics | 1        | 0.36%   |
| OCZ Technology Group         | 1        | 0.36%   |
| Micron Technology            | 1        | 0.36%   |
| LSI Logic / Symbios Logic    | 1        | 0.36%   |
| Lite-On Technology           | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 39       | 11.08%  |
| AMD 400 Series Chipset SATA Controller                                                  | 18       | 5.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 16       | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15       | 4.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 4.26%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 12       | 3.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 2.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 1.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 1.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 1.99%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6        | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 1.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.7%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 5        | 1.42%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 1.42%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.42%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.42%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.42%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 5        | 1.42%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.42%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 4        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.14%   |
| AMD 600 Series Chipset SATA Controller                                                  | 4        | 1.14%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                            | 3        | 0.85%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 3        | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.85%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 2        | 0.57%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.57%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 2        | 0.57%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.57%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2        | 0.57%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.57%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.57%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 148      | 55.85%  |
| NVMe | 69       | 26.04%  |
| IDE  | 36       | 13.58%  |
| RAID | 10       | 3.77%   |
| SAS  | 1        | 0.38%   |
| SCSI | 1        | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 101      | 56.42%  |
| AMD    | 78       | 43.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-10400F CPU @ 2.90GHz          | 5        | 2.79%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 2.79%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 2.23%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3        | 1.68%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 1.68%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.68%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 1.68%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 1.68%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 1.68%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 2        | 1.12%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.12%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.12%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.12%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.12%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 2        | 1.12%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.12%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.12%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.12%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 1.12%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.12%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.12%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.12%   |
| AMD Ryzen 5 5600 6-Core Processor           | 2        | 1.12%   |
| AMD Ryzen 5 5500                            | 2        | 1.12%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 1.12%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.12%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 1.12%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 2        | 1.12%   |
| AMD FX-8300 Eight-Core Processor            | 2        | 1.12%   |
| AMD Athlon II X2 260 Processor              | 2        | 1.12%   |
| Intel Xeon W-2145 CPU @ 3.70GHz             | 1        | 0.56%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 0.56%   |
| Intel Xeon CPU X5560 @ 2.80GHz              | 1        | 0.56%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.56%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 30       | 16.76%  |
| Intel Core i5           | 29       | 16.2%   |
| Intel Core i7           | 17       | 9.5%    |
| AMD Ryzen 7             | 15       | 8.38%   |
| Intel Core i3           | 13       | 7.26%   |
| Other                   | 10       | 5.59%   |
| AMD Ryzen 9             | 10       | 5.59%   |
| Intel Pentium Dual-Core | 6        | 3.35%   |
| AMD FX                  | 6        | 3.35%   |
| Intel Xeon              | 5        | 2.79%   |
| Intel Core 2 Duo        | 4        | 2.23%   |
| Intel Celeron           | 4        | 2.23%   |
| AMD Ryzen 3             | 4        | 2.23%   |
| Intel Pentium 4         | 3        | 1.68%   |
| Intel Pentium           | 3        | 1.68%   |
| AMD Athlon II X2        | 3        | 1.68%   |
| Intel Pentium D         | 2        | 1.12%   |
| Intel Core i9           | 2        | 1.12%   |
| AMD Phenom II X4        | 2        | 1.12%   |
| AMD Athlon 64 X2        | 2        | 1.12%   |
| Intel Core 2 Quad       | 1        | 0.56%   |
| Intel Core 2            | 1        | 0.56%   |
| Intel Core              | 1        | 0.56%   |
| AMD Ryzen Threadripper  | 1        | 0.56%   |
| AMD PRO A8              | 1        | 0.56%   |
| AMD EPYC                | 1        | 0.56%   |
| AMD Athlon II X4        | 1        | 0.56%   |
| AMD A8                  | 1        | 0.56%   |
| AMD A4                  | 1        | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 57       | 31.84%  |
| 6      | 40       | 22.35%  |
| 2      | 40       | 22.35%  |
| 8      | 23       | 12.85%  |
| 12     | 6        | 3.35%   |
| 16     | 5        | 2.79%   |
| 1      | 3        | 1.68%   |
| 14     | 2        | 1.12%   |
| 32     | 1        | 0.56%   |
| 24     | 1        | 0.56%   |
| 10     | 1        | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 178      | 98.89%  |
| 24     | 1        | 0.56%   |
| 2      | 1        | 0.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 112      | 62.22%  |
| 1      | 68       | 37.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 178      | 99.44%  |
| 32-bit         | 1        | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 86       | 46.74%  |
| 0x306c3    | 11       | 5.98%   |
| 0x206a7    | 7        | 3.8%    |
| 0x1067a    | 6        | 3.26%   |
| 0x08701021 | 6        | 3.26%   |
| 0x306a9    | 5        | 2.72%   |
| 0x906e9    | 4        | 2.17%   |
| 0x08001137 | 4        | 2.17%   |
| 0x010000c8 | 4        | 2.17%   |
| 0xa0653    | 3        | 1.63%   |
| 0x0800820d | 3        | 1.63%   |
| 0xf43      | 2        | 1.09%   |
| 0xb06e0    | 2        | 1.09%   |
| 0x506e3    | 2        | 1.09%   |
| 0x0a50000d | 2        | 1.09%   |
| 0x0a50000c | 2        | 1.09%   |
| 0x0a201016 | 2        | 1.09%   |
| 0x0a201009 | 2        | 1.09%   |
| 0x08108109 | 2        | 1.09%   |
| 0xf65      | 1        | 0.54%   |
| 0xf47      | 1        | 0.54%   |
| 0xf34      | 1        | 0.54%   |
| 0xa0671    | 1        | 0.54%   |
| 0x906ed    | 1        | 0.54%   |
| 0x906ec    | 1        | 0.54%   |
| 0x906eb    | 1        | 0.54%   |
| 0x806c1    | 1        | 0.54%   |
| 0x206c2    | 1        | 0.54%   |
| 0x20652    | 1        | 0.54%   |
| 0x106e5    | 1        | 0.54%   |
| 0x106a5    | 1        | 0.54%   |
| 0x0a50000b | 1        | 0.54%   |
| 0x0a201211 | 1        | 0.54%   |
| 0x0a20120a | 1        | 0.54%   |
| 0x0a201204 | 1        | 0.54%   |
| 0x0a201025 | 1        | 0.54%   |
| 0x0a201005 | 1        | 0.54%   |
| 0x08701013 | 1        | 0.54%   |
| 0x0810100b | 1        | 0.54%   |
| 0x0800820b | 1        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 26       | 14.53%  |
| Haswell          | 15       | 8.38%   |
| KabyLake         | 14       | 7.82%   |
| IvyBridge        | 13       | 7.26%   |
| Zen 2            | 12       | 6.7%    |
| Zen+             | 10       | 5.59%   |
| Penryn           | 10       | 5.59%   |
| Zen              | 9        | 5.03%   |
| SandyBridge      | 9        | 5.03%   |
| Unknown          | 9        | 5.03%   |
| Skylake          | 7        | 3.91%   |
| Piledriver       | 7        | 3.91%   |
| CometLake        | 7        | 3.91%   |
| K10              | 6        | 3.35%   |
| NetBurst         | 5        | 2.79%   |
| Westmere         | 3        | 1.68%   |
| TigerLake        | 3        | 1.68%   |
| Nehalem          | 3        | 1.68%   |
| K8 Hammer        | 2        | 1.12%   |
| Core             | 2        | 1.12%   |
| Alderlake Hybrid | 2        | 1.12%   |
| Steamroller      | 1        | 0.56%   |
| Silvermont       | 1        | 0.56%   |
| Jaguar           | 1        | 0.56%   |
| Icelake          | 1        | 0.56%   |
| Gracemont        | 1        | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 80       | 41.88%  |
| AMD    | 61       | 31.94%  |
| Intel  | 50       | 26.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 6%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 3.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 3%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 2.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 2.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 2.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 1.5%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.5%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.5%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.5%    |
| Nvidia AD107 [GeForce RTX 4060]                                             | 3        | 1.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3        | 1.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.5%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 1.5%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.5%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1%      |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 1%      |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1%      |
| Nvidia GT216 [GeForce GT 220]                                               | 2        | 1%      |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1%      |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 1%      |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1%      |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 1%      |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 1%      |
| Nvidia G92 [GeForce GTS 250]                                                | 2        | 1%      |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 1%      |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 2        | 1%      |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 2        | 1%      |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1%      |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 1%      |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1%      |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 1%      |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 1%      |
| AMD Granite Ridge [Radeon Graphics]                                         | 2        | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 73       | 40.11%  |
| 1 x AMD        | 52       | 28.57%  |
| 1 x Intel      | 44       | 24.18%  |
| 2 x AMD        | 4        | 2.2%    |
| AMD + Nvidia   | 4        | 2.2%    |
| 2 x Nvidia     | 2        | 1.1%    |
| Other          | 1        | 0.55%   |
| Intel + Nvidia | 1        | 0.55%   |
| Intel + AMD    | 1        | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 125      | 67.57%  |
| Proprietary | 49       | 26.49%  |
| Unknown     | 11       | 5.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 78       | 41.49%  |
| 1.01-2.0   | 21       | 11.17%  |
| 7.01-8.0   | 20       | 10.64%  |
| 0.51-1.0   | 18       | 9.57%   |
| 3.01-4.0   | 17       | 9.04%   |
| 0.01-0.5   | 15       | 7.98%   |
| 5.01-6.0   | 11       | 5.85%   |
| 8.01-16.0  | 7        | 3.72%   |
| 16.01-24.0 | 1        | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 42       | 21.76%  |
| Dell                 | 27       | 13.99%  |
| Goldstar             | 25       | 12.95%  |
| AOC                  | 22       | 11.4%   |
| Philips              | 20       | 10.36%  |
| BenQ                 | 11       | 5.7%    |
| Hewlett-Packard      | 10       | 5.18%   |
| Ancor Communications | 8        | 4.15%   |
| Lenovo               | 7        | 3.63%   |
| ASUSTek Computer     | 4        | 2.07%   |
| ViewSonic            | 2        | 1.04%   |
| LG Electronics       | 2        | 1.04%   |
| Unknown (XXX)        | 1        | 0.52%   |
| Unknown              | 1        | 0.52%   |
| Toshiba              | 1        | 0.52%   |
| Sony                 | 1        | 0.52%   |
| NEC Computers        | 1        | 0.52%   |
| Mi                   | 1        | 0.52%   |
| Medion               | 1        | 0.52%   |
| Iiyama               | 1        | 0.52%   |
| Hitachi              | 1        | 0.52%   |
| Eizo                 | 1        | 0.52%   |
| DENON                | 1        | 0.52%   |
| AGO                  | 1        | 0.52%   |
| Acer                 | 1        | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 3        | 1.36%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 3        | 1.36%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3        | 1.36%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch     | 2        | 0.91%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 2        | 0.91%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.91%   |
| Samsung Electronics LCD Monitor C32HG7x 2560x1440                     | 2        | 0.91%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 2        | 0.91%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2        | 0.91%   |
| Lenovo LEN L193pC LEN114F 1280x1024 376x301mm 19.0-inch               | 2        | 0.91%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch              | 2        | 0.91%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch              | 2        | 0.91%   |
| Dell U2419H DEL4148 1920x1080 527x296mm 23.8-inch                     | 2        | 0.91%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2        | 0.91%   |
| Dell U2212HM DELD048 1920x1080 475x267mm 21.5-inch                    | 2        | 0.91%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2        | 0.91%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                    | 2        | 0.91%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                        | 2        | 0.91%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 2        | 0.91%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1        | 0.45%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                 | 1        | 0.45%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.45%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 1        | 0.45%   |
| Toshiba 43UHD_LCD_TV TSB3700 3840x2160 940x540mm 42.7-inch            | 1        | 0.45%   |
| Sony TV SNY2C02 1920x1080 886x498mm 40.0-inch                         | 1        | 0.45%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.45%   |
| Samsung Electronics T19B300 SAM0926 1366x768 410x230mm 18.5-inch      | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0609 1920x1080 510x290mm 23.1-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                      | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM05E7 1920x1080 510x290mm 23.1-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0523 1920x1080 477x268mm 21.5-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM03E8 1920x1080                      | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch   | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM01E3 1280x1024 338x270mm 17.0-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0192 1280x1024 338x270mm 17.0-inch  | 1        | 0.45%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch    | 1        | 0.45%   |
| Samsung Electronics SMBX2231 SAM076C 1920x1080 477x268mm 21.5-inch    | 1        | 0.45%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch    | 1        | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 92       | 47.18%  |
| 2560x1440 (QHD)    | 30       | 15.38%  |
| 1280x1024 (SXGA)   | 20       | 10.26%  |
| 3840x2160 (4K)     | 18       | 9.23%   |
| 1366x768 (WXGA)    | 6        | 3.08%   |
| 3440x1440          | 4        | 2.05%   |
| 2560x1080          | 4        | 2.05%   |
| 1440x900 (WXGA+)   | 4        | 2.05%   |
| 1680x1050 (WSXGA+) | 3        | 1.54%   |
| Unknown            | 3        | 1.54%   |
| 3840x1600          | 2        | 1.03%   |
| 3840x1080          | 2        | 1.03%   |
| 1920x1200 (WUXGA)  | 2        | 1.03%   |
| 3200x1080          | 1        | 0.51%   |
| 2288x1287          | 1        | 0.51%   |
| 1600x900 (HD+)     | 1        | 0.51%   |
| 1360x768           | 1        | 0.51%   |
| 1280x720 (HD)      | 1        | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 37       | 18.23%  |
| 24      | 33       | 16.26%  |
| 23      | 29       | 14.29%  |
| 21      | 26       | 12.81%  |
| Unknown | 14       | 6.9%    |
| 19      | 11       | 5.42%   |
| 31      | 10       | 4.93%   |
| 17      | 9        | 4.43%   |
| 34      | 7        | 3.45%   |
| 18      | 7        | 3.45%   |
| 40      | 4        | 1.97%   |
| 84      | 3        | 1.48%   |
| 20      | 3        | 1.48%   |
| 22      | 2        | 0.99%   |
| 142     | 1        | 0.49%   |
| 63      | 1        | 0.49%   |
| 55      | 1        | 0.49%   |
| 50      | 1        | 0.49%   |
| 37      | 1        | 0.49%   |
| 33      | 1        | 0.49%   |
| 25      | 1        | 0.49%   |
| 12      | 1        | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 87       | 44.85%  |
| 401-500        | 39       | 20.1%   |
| 601-700        | 14       | 7.22%   |
| Unknown        | 14       | 7.22%   |
| 351-400        | 10       | 5.15%   |
| 301-350        | 9        | 4.64%   |
| 701-800        | 8        | 4.12%   |
| 801-900        | 5        | 2.58%   |
| 1501-2000      | 3        | 1.55%   |
| 1001-1500      | 3        | 1.55%   |
| More than 2000 | 1        | 0.52%   |
| 201-300        | 1        | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 129      | 70.49%  |
| 5/4     | 19       | 10.38%  |
| 16/10   | 11       | 6.01%   |
| Unknown | 11       | 6.01%   |
| 21/9    | 8        | 4.37%   |
| 3/2     | 3        | 1.64%   |
| 4/3     | 1        | 0.55%   |
| 1.00    | 1        | 0.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 73       | 36.5%   |
| 301-350        | 37       | 18.5%   |
| 151-200        | 21       | 10.5%   |
| 351-500        | 18       | 9%      |
| 141-150        | 15       | 7.5%    |
| Unknown        | 14       | 7%      |
| 251-300        | 9        | 4.5%    |
| More than 1000 | 7        | 3.5%    |
| 501-1000       | 5        | 2.5%    |
| 71-80          | 1        | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 120      | 63.16%  |
| 101-120 | 42       | 22.11%  |
| Unknown | 14       | 7.37%   |
| 121-160 | 8        | 4.21%   |
| 1-50    | 3        | 1.58%   |
| 161-240 | 3        | 1.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 131      | 72.38%  |
| 2     | 36       | 19.89%  |
| 0     | 10       | 5.52%   |
| 3     | 4        | 2.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 115      | 49.57%  |
| Intel                           | 60       | 25.86%  |
| Qualcomm Atheros                | 14       | 6.03%   |
| Broadcom                        | 7        | 3.02%   |
| TP-Link                         | 4        | 1.72%   |
| Microsoft                       | 4        | 1.72%   |
| MediaTek                        | 4        | 1.72%   |
| Broadcom Limited                | 4        | 1.72%   |
| Aquantia                        | 3        | 1.29%   |
| Samsung Electronics             | 2        | 0.86%   |
| Ralink                          | 2        | 0.86%   |
| Nvidia                          | 2        | 0.86%   |
| D-Link                          | 2        | 0.86%   |
| U-Blox                          | 1        | 0.43%   |
| Ralink Technology               | 1        | 0.43%   |
| Qualcomm Atheros Communications | 1        | 0.43%   |
| Marvell Technology Group        | 1        | 0.43%   |
| Huawei Technologies             | 1        | 0.43%   |
| Edimax Technology               | 1        | 0.43%   |
| D-Link System                   | 1        | 0.43%   |
| ASUSTek Computer                | 1        | 0.43%   |
| 3Com                            | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 93       | 35.63%  |
| Realtek RTL8125 2.5GbE Controller                                               | 13       | 4.98%   |
| Intel I211 Gigabit Network Connection                                           | 9        | 3.45%   |
| Intel Wi-Fi 6 AX200                                                             | 6        | 2.3%    |
| Intel 82579V Gigabit Network Connection                                         | 6        | 2.3%    |
| Intel Ethernet Controller I225-V                                                | 5        | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 5        | 1.92%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                          | 3        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 3        | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 3        | 1.15%   |
| Intel Wi-Fi 6 AX201                                                             | 3        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                                            | 3        | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                                           | 3        | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 3        | 1.15%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                        | 2        | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 2        | 0.77%   |
| Realtek RTL8126 5GbE Controller                                                 | 2        | 0.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 2        | 0.77%   |
| Ralink RT2561/RT61 rev B 802.11g                                                | 2        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                | 2        | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                      | 2        | 0.77%   |
| Microsoft Xbox Wireless Adapter for Windows                                     | 2        | 0.77%   |
| Microsoft Xbox 360 Wireless Adapter                                             | 2        | 0.77%   |
| MediaTek MT7927 802.11be 320MHz 2x2 PCIe Wireless Network Adapter [Filogic 380] | 2        | 0.77%   |
| Intel Wireless 7265                                                             | 2        | 0.77%   |
| Intel Ethernet Controller I226-V                                                | 2        | 0.77%   |
| Intel Ethernet Connection I217-LM                                               | 2        | 0.77%   |
| Intel Ethernet Connection (2) I219-V                                            | 2        | 0.77%   |
| Intel Ethernet Connection (14) I219-V                                           | 2        | 0.77%   |
| Intel 82578DC Gigabit Network Connection                                        | 2        | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                                      | 2        | 0.77%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                               | 2        | 0.77%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                 | 2        | 0.77%   |
| U-Blox [u-blox 7]                                                               | 1        | 0.38%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                             | 1        | 0.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                    | 1        | 0.38%   |
| TP-Link Archer T4U ver.3                                                        | 1        | 0.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                      | 1        | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                     | 1        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 22       | 36.07%  |
| Realtek Semiconductor           | 12       | 19.67%  |
| TP-Link                         | 4        | 6.56%   |
| Qualcomm Atheros                | 4        | 6.56%   |
| Microsoft                       | 4        | 6.56%   |
| MediaTek                        | 4        | 6.56%   |
| Ralink                          | 2        | 3.28%   |
| D-Link                          | 2        | 3.28%   |
| Broadcom                        | 2        | 3.28%   |
| Ralink Technology               | 1        | 1.64%   |
| Qualcomm Atheros Communications | 1        | 1.64%   |
| Edimax Technology               | 1        | 1.64%   |
| D-Link System                   | 1        | 1.64%   |
| ASUSTek Computer                | 1        | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                             | 6        | 9.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 5        | 8.2%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                          | 3        | 4.92%   |
| Intel Wi-Fi 6 AX201                                                             | 3        | 4.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                        | 2        | 3.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 2        | 3.28%   |
| Ralink RT2561/RT61 rev B 802.11g                                                | 2        | 3.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                | 2        | 3.28%   |
| Microsoft Xbox Wireless Adapter for Windows                                     | 2        | 3.28%   |
| Microsoft Xbox 360 Wireless Adapter                                             | 2        | 3.28%   |
| MediaTek MT7927 802.11be 320MHz 2x2 PCIe Wireless Network Adapter [Filogic 380] | 2        | 3.28%   |
| Intel Wireless 7265                                                             | 2        | 3.28%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                             | 1        | 1.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                    | 1        | 1.64%   |
| TP-Link Archer T4U ver.3                                                        | 1        | 1.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                      | 1        | 1.64%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 1        | 1.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                        | 1        | 1.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                 | 1        | 1.64%   |
| Realtek 802.11ax WLAN Adapter                                                   | 1        | 1.64%   |
| Realtek 802.11ac NIC                                                            | 1        | 1.64%   |
| Ralink RT5370 Wireless Adapter                                                  | 1        | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 1        | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                                                 | 1        | 1.64%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]   | 1        | 1.64%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 1        | 1.64%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 1        | 1.64%   |
| Intel Wireless 7260                                                             | 1        | 1.64%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                 | 1        | 1.64%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 1        | 1.64%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 1        | 1.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                                  | 1        | 1.64%   |
| Intel 700 Series Chipset CNVi WiFi                                              | 1        | 1.64%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]               | 1        | 1.64%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]            | 1        | 1.64%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                   | 1        | 1.64%   |
| D-Link 802.11 n WLAN                                                            | 1        | 1.64%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                    | 1        | 1.64%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                    | 1        | 1.64%   |
| ASUS 802.11n WLAN Adapter                                                       | 1        | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 111      | 58.12%  |
| Intel                    | 51       | 26.7%   |
| Qualcomm Atheros         | 10       | 5.24%   |
| Broadcom                 | 5        | 2.62%   |
| Broadcom Limited         | 4        | 2.09%   |
| Aquantia                 | 3        | 1.57%   |
| Samsung Electronics      | 2        | 1.05%   |
| Nvidia                   | 2        | 1.05%   |
| Marvell Technology Group | 1        | 0.52%   |
| Huawei Technologies      | 1        | 0.52%   |
| 3Com                     | 1        | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 93       | 46.73%  |
| Realtek RTL8125 2.5GbE Controller                                      | 13       | 6.53%   |
| Intel I211 Gigabit Network Connection                                  | 9        | 4.52%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 3.02%   |
| Intel Ethernet Controller I225-V                                       | 5        | 2.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 1.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3        | 1.51%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 1.51%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 1.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 1.51%   |
| Realtek RTL8126 5GbE Controller                                        | 2        | 1.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2        | 1.01%   |
| Intel Ethernet Controller I226-V                                       | 2        | 1.01%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 1.01%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 1.01%   |
| Intel 82578DC Gigabit Network Connection                               | 2        | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 1.01%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 1.01%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 2        | 1.01%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 0.5%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 0.5%    |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.5%    |
| Nvidia MCP55 Ethernet                                                  | 1        | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.5%    |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 0.5%    |
| Intel I210 Gigabit Network Connection                                  | 1        | 0.5%    |
| Intel Ethernet Connection I217-V                                       | 1        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 0.5%    |
| Intel Ethernet Connection (19) I219-LM                                 | 1        | 0.5%    |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 0.5%    |
| Intel Ethernet Connection (13) I219-V                                  | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 178      | 75.11%  |
| WiFi     | 58       | 24.47%  |
| Modem    | 1        | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 153      | 83.15%  |
| WiFi     | 31       | 16.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 130      | 71.43%  |
| 2     | 41       | 22.53%  |
| 3     | 10       | 5.49%   |
| 5     | 1        | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 178      | 99.44%  |
| Yes  | 1        | 0.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 21       | 41.18%  |
| Cambridge Silicon Radio         | 18       | 35.29%  |
| ASUSTek Computer                | 3        | 5.88%   |
| Foxconn / Hon Hai               | 2        | 3.92%   |
| Edimax Technology               | 2        | 3.92%   |
| Realtek Semiconductor           | 1        | 1.96%   |
| Qualcomm Atheros Communications | 1        | 1.96%   |
| MediaTek                        | 1        | 1.96%   |
| IMC Networks                    | 1        | 1.96%   |
| Broadcom                        | 1        | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18       | 35.29%  |
| Intel AX200 Bluetooth                               | 6        | 11.76%  |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 9.8%    |
| Intel AX201 Bluetooth                               | 4        | 7.84%   |
| Intel Bluetooth wireless interface                  | 2        | 3.92%   |
| Intel Bluetooth Device                              | 2        | 3.92%   |
| Foxconn / Hon Hai Wireless_Device                   | 2        | 3.92%   |
| Edimax Bluetooth Device                             | 2        | 3.92%   |
| Realtek Bluetooth Radio                             | 1        | 1.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.96%   |
| MediaTek Wireless_Device                            | 1        | 1.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.96%   |
| Intel AX210 Bluetooth                               | 1        | 1.96%   |
| IMC Networks Wireless_Device                        | 1        | 1.96%   |
| Broadcom Bluetooth Device                           | 1        | 1.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.96%   |
| ASUS Bluetooth Radio                                | 1        | 1.96%   |
| ASUS ASUS USB-BT500                                 | 1        | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 97       | 30.03%  |
| AMD                                             | 89       | 27.55%  |
| Nvidia                                          | 74       | 22.91%  |
| C-Media Electronics                             | 9        | 2.79%   |
| JMTek                                           | 7        | 2.17%   |
| Logitech                                        | 5        | 1.55%   |
| Kingston Technology                             | 3        | 0.93%   |
| ASUSTek Computer                                | 3        | 0.93%   |
| Yamaha                                          | 2        | 0.62%   |
| SteelSeries ApS                                 | 2        | 0.62%   |
| Razer USA                                       | 2        | 0.62%   |
| PreSonus Audio Electronics                      | 2        | 0.62%   |
| Micro Star International                        | 2        | 0.62%   |
| Focusrite-Novation                              | 2        | 0.62%   |
| Creative Labs                                   | 2        | 0.62%   |
| XMOS                                            | 1        | 0.31%   |
| Texas Instruments                               | 1        | 0.31%   |
| Sony                                            | 1        | 0.31%   |
| Sennheiser Communications                       | 1        | 0.31%   |
| Schiit Audio                                    | 1        | 0.31%   |
| Roland                                          | 1        | 0.31%   |
| Realtek Semiconductor                           | 1        | 0.31%   |
| Panasonic (Matsushita)                          | 1        | 0.31%   |
| Native Instruments                              | 1        | 0.31%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.31%   |
| KTMicro                                         | 1        | 0.31%   |
| Jieli Technology                                | 1        | 0.31%   |
| Hewlett-Packard                                 | 1        | 0.31%   |
| Harman                                          | 1        | 0.31%   |
| GN Netcom                                       | 1        | 0.31%   |
| Generalplus Technology                          | 1        | 0.31%   |
| Dell                                            | 1        | 0.31%   |
| Creative Technology                             | 1        | 0.31%   |
| Beijing Chushifengmang Technology Development   | 1        | 0.31%   |
| Audio-Technica                                  | 1        | 0.31%   |
| Audeze                                          | 1        | 0.31%   |
| Allen&Heath                                     | 1        | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 29       | 7.61%   |
| AMD Ryzen HD Audio Controller                                              | 15       | 3.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 3.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14       | 3.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 2.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 2.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 2.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 2.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 2.1%    |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 8        | 2.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 1.84%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 1.84%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7        | 1.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 1.57%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 1.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 1.57%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 1.57%   |
| JMTek USB PnP Audio Device                                                 | 6        | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 1.57%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 1.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.31%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 1.31%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.05%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 1.05%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.05%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.79%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.79%   |
| Nvidia AD107 High Definition Audio Controller                              | 3        | 0.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3        | 0.79%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 3        | 0.79%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3        | 0.79%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 0.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 32       | 24.06%  |
| G.Skill                      | 20       | 15.04%  |
| Unknown                      | 17       | 12.78%  |
| Crucial                      | 15       | 11.28%  |
| Samsung Electronics          | 9        | 6.77%   |
| Patriot                      | 9        | 6.77%   |
| SK hynix                     | 5        | 3.76%   |
| Corsair                      | 5        | 3.76%   |
| A-DATA Technology            | 4        | 3.01%   |
| Ramaxel Technology           | 3        | 2.26%   |
| GOODRAM                      | 3        | 2.26%   |
| Transcend                    | 2        | 1.5%    |
| Team                         | 2        | 1.5%    |
| Nanya Technology             | 2        | 1.5%    |
| Timetec                      | 1        | 0.75%   |
| Patriot Memory (PDP Systems) | 1        | 0.75%   |
| Micron Technology            | 1        | 0.75%   |
| Elpida                       | 1        | 0.75%   |
| Atermiter                    | 1        | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3600MT/s    | 4        | 2.72%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s    | 3        | 2.04%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s | 3        | 2.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 2        | 1.36%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s  | 2        | 1.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s | 2        | 1.36%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s       | 2        | 1.36%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s  | 2        | 1.36%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s | 2        | 1.36%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s   | 2        | 1.36%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s             | 1        | 0.68%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s          | 1        | 0.68%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s             | 1        | 0.68%   |
| Unknown RAM Module 512MB DIMM 800MT/s                 | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s             | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s          | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s               | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s              | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 400MT/s                   | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 1        | 0.68%   |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s          | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR2 400MT/s           | 1        | 0.68%   |
| Transcend RAM JM2400HLB-8G 8GB DIMM DDR4 2667MT/s     | 1        | 0.68%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s         | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s    | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s    | 1        | 0.68%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s            | 1        | 0.68%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s  | 1        | 0.68%   |
| SK hynix RAM HMT41GU6BFR8A-RD 8GB DIMM DDR3 1867MT/s  | 1        | 0.68%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s  | 1        | 0.68%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s  | 1        | 0.68%   |
| Samsung RAM Module 16GB DIMM 4800MT/s                 | 1        | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 57       | 48.72%  |
| DDR3    | 36       | 30.77%  |
| Unknown | 7        | 5.98%   |
| DDR5    | 6        | 5.13%   |
| SDRAM   | 5        | 4.27%   |
| DDR2    | 4        | 3.42%   |
| DDR     | 2        | 1.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 105      | 92.11%  |
| SODIMM | 9        | 7.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 47       | 38.52%  |
| 4096  | 26       | 21.31%  |
| 16384 | 22       | 18.03%  |
| 2048  | 12       | 9.84%   |
| 32768 | 8        | 6.56%   |
| 1024  | 4        | 3.28%   |
| 512   | 3        | 2.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 25       | 18.94%  |
| 1333    | 14       | 10.61%  |
| 3200    | 13       | 9.85%   |
| 3600    | 12       | 9.09%   |
| 2667    | 10       | 7.58%   |
| 2666    | 5        | 3.79%   |
| 2400    | 5        | 3.79%   |
| 3800    | 4        | 3.03%   |
| 2133    | 4        | 3.03%   |
| 1867    | 4        | 3.03%   |
| 800     | 4        | 3.03%   |
| 4800    | 3        | 2.27%   |
| 3866    | 3        | 2.27%   |
| 667     | 3        | 2.27%   |
| Unknown | 3        | 2.27%   |
| 6400    | 2        | 1.52%   |
| 3733    | 2        | 1.52%   |
| 2934    | 2        | 1.52%   |
| 2933    | 2        | 1.52%   |
| 2800    | 2        | 1.52%   |
| 400     | 2        | 1.52%   |
| 5600    | 1        | 0.76%   |
| 3400    | 1        | 0.76%   |
| 3066    | 1        | 0.76%   |
| 3000    | 1        | 0.76%   |
| 2734    | 1        | 0.76%   |
| 1066    | 1        | 0.76%   |
| 533     | 1        | 0.76%   |
| 333     | 1        | 0.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 50%     |
| Hewlett-Packard     | 2        | 33.33%  |
| Canon               | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung SCX-4200 series | 1        | 16.67%  |
| Samsung ML-1670 Series  | 1        | 16.67%  |
| Samsung M2070 Series    | 1        | 16.67%  |
| HP PSC-1315/PSC-1317    | 1        | 16.67%  |
| HP LaserJet 1020        | 1        | 16.67%  |
| Canon TS6000 series     | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 22       | 46.81%  |
| Microdia                      | 4        | 8.51%   |
| Samsung Electronics           | 2        | 4.26%   |
| Panasonic (Matsushita)        | 2        | 4.26%   |
| Generalplus Technology        | 2        | 4.26%   |
| Z-Star Microelectronics       | 1        | 2.13%   |
| Sunplus Innovation Technology | 1        | 2.13%   |
| Sonix Technology              | 1        | 2.13%   |
| Realtek Semiconductor         | 1        | 2.13%   |
| Razer USA                     | 1        | 2.13%   |
| Pixart Imaging                | 1        | 2.13%   |
| Lenovo                        | 1        | 2.13%   |
| Huawei Technologies           | 1        | 2.13%   |
| HRY                           | 1        | 2.13%   |
| GenesysLogic Technology       | 1        | 2.13%   |
| Genesys Logic                 | 1        | 2.13%   |
| Cubeternet                    | 1        | 2.13%   |
| Creative Technology           | 1        | 2.13%   |
| Chicony Electronics           | 1        | 2.13%   |
| Arkmicro Technologies         | 1        | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                | 7        | 14.89%  |
| Samsung Galaxy series, misc. (MTP mode)                             | 2        | 4.26%   |
| Panasonic (Matsushita) TY-CC20W                                     | 2        | 4.26%   |
| Microdia Webcam Vitade AF                                           | 2        | 4.26%   |
| Logitech HD Webcam C615                                             | 2        | 4.26%   |
| Logitech HD Pro Webcam C920                                         | 2        | 4.26%   |
| Logitech C922 Pro Stream Webcam                                     | 2        | 4.26%   |
| Generalplus 808 Camera #9 (web-cam mode)                            | 2        | 4.26%   |
| Z-Star Venus USB2.0 Camera                                          | 1        | 2.13%   |
| Sunplus AUSDOM FHD Camera                                           | 1        | 2.13%   |
| Sonix USB Camera                                                    | 1        | 2.13%   |
| Realtek USB Camera                                                  | 1        | 2.13%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 1        | 2.13%   |
| Pixart Imaging Webcam Genius iLook 300                              | 1        | 2.13%   |
| Microdia CyberTrack H7                                              | 1        | 2.13%   |
| Microdia Camera                                                     | 1        | 2.13%   |
| Logitech Webcam C930e                                               | 1        | 2.13%   |
| Logitech Webcam C170                                                | 1        | 2.13%   |
| Logitech Webcam B500                                                | 1        | 2.13%   |
| Logitech QuickCam Pro 9000                                          | 1        | 2.13%   |
| Logitech Logitech Webcam C925e                                      | 1        | 2.13%   |
| Logitech Logitech Webcam C160                                       | 1        | 2.13%   |
| Logitech HD Webcam C525                                             | 1        | 2.13%   |
| Logitech C920 PRO HD Webcam                                         | 1        | 2.13%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 2.13%   |
| Lenovo Lenovo FHD Webcam Audio                                      | 1        | 2.13%   |
| Huawei HiCamera                                                     | 1        | 2.13%   |
| HRY USB Camera                                                      | 1        | 2.13%   |
| GenesysLogic USB2.0 UVC PC Camera                                   | 1        | 2.13%   |
| Genesys Logic HD camera                                             | 1        | 2.13%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 2.13%   |
| Creative Live! Cam Sync 1080p                                       | 1        | 2.13%   |
| Chicony HP 720p HD Monitor Webcam                                   | 1        | 2.13%   |
| Arkmicro USB2.0 PC CAMERA                                           | 1        | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Yamila | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Yamila Yamila Fingerprint Device | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 1        | 50%     |
| Alcor Micro           | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |
| Alcor Micro AU9540 Smartcard Reader               | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 162      | 90%     |
| 1     | 16       | 8.89%   |
| 3     | 1        | 0.56%   |
| 2     | 1        | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 10       | 47.62%  |
| Net/wireless          | 4        | 19.05%  |
| Network               | 1        | 4.76%   |
| Net/ethernet          | 1        | 4.76%   |
| Multimedia controller | 1        | 4.76%   |
| Fingerprint reader    | 1        | 4.76%   |
| Chipcard              | 1        | 4.76%   |
| Camera                | 1        | 4.76%   |
| Bluetooth             | 1        | 4.76%   |

