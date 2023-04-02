Fedora 37 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 821

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b4a624599e](https://linux-hardware.org/?probe=b4a624599e) | Apr 01, 2023 |
| Intel         | DH77EB AAG39073-304         | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [c512f4cdd9](https://linux-hardware.org/?probe=c512f4cdd9) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [79d44a9e66](https://linux-hardware.org/?probe=79d44a9e66) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [e615755655](https://linux-hardware.org/?probe=e615755655) | Apr 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a9aebc7f0](https://linux-hardware.org/?probe=4a9aebc7f0) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [acfff71638](https://linux-hardware.org/?probe=acfff71638) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | [4693b65922](https://linux-hardware.org/?probe=4693b65922) | Mar 31, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [8d4ef602e5](https://linux-hardware.org/?probe=8d4ef602e5) | Mar 31, 2023 |
| Dell          | 0PP150 A00                  | [fdc879a486](https://linux-hardware.org/?probe=fdc879a486) | Mar 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1417777bbc](https://linux-hardware.org/?probe=1417777bbc) | Mar 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [70efcb81e9](https://linux-hardware.org/?probe=70efcb81e9) | Mar 30, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2ac52b4538](https://linux-hardware.org/?probe=2ac52b4538) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bc798d371a](https://linux-hardware.org/?probe=bc798d371a) | Mar 30, 2023 |
| System76      | Thelio Mira thelio-mira-... | [4915a172bd](https://linux-hardware.org/?probe=4915a172bd) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| Acer          | Veriton N4630G              | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | [7c56c30e23](https://linux-hardware.org/?probe=7c56c30e23) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | [010ed7a818](https://linux-hardware.org/?probe=010ed7a818) | Mar 29, 2023 |
| MSI           | B450M MORTAR                | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [151a527b35](https://linux-hardware.org/?probe=151a527b35) | Mar 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [4b0ae8033f](https://linux-hardware.org/?probe=4b0ae8033f) | Mar 28, 2023 |
| MSI           | B550-A PRO                  | [999219f420](https://linux-hardware.org/?probe=999219f420) | Mar 28, 2023 |
| Lenovo        | ThinkServer TS130           | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| Dell          | 08HPGT A01                  | [451ccd93f2](https://linux-hardware.org/?probe=451ccd93f2) | Mar 27, 2023 |
| Dell          | 08HPGT A01                  | [e38a63e793](https://linux-hardware.org/?probe=e38a63e793) | Mar 27, 2023 |
| Huanan        | X99-F8D V2.6                | [65f96586ec](https://linux-hardware.org/?probe=65f96586ec) | Mar 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [14380327b0](https://linux-hardware.org/?probe=14380327b0) | Mar 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [79dc82b50b](https://linux-hardware.org/?probe=79dc82b50b) | Mar 27, 2023 |
| ASUSTek       | Maximus VIII HERO           | [23ee1856bc](https://linux-hardware.org/?probe=23ee1856bc) | Mar 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6b00de6bed](https://linux-hardware.org/?probe=6b00de6bed) | Mar 27, 2023 |
| Dell          | 07PR60 A01                  | [f312d049e0](https://linux-hardware.org/?probe=f312d049e0) | Mar 27, 2023 |
| ASRock        | B450M-HDV R4.0              | [e069fb2622](https://linux-hardware.org/?probe=e069fb2622) | Mar 26, 2023 |
| Acer          | Veriton M2631 V:1.0         | [4a4f12631a](https://linux-hardware.org/?probe=4a4f12631a) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a607ac616d](https://linux-hardware.org/?probe=a607ac616d) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3711318620](https://linux-hardware.org/?probe=3711318620) | Mar 26, 2023 |
| BESSTAR Te... | F6BFC                       | [881c531ee5](https://linux-hardware.org/?probe=881c531ee5) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-K               | [95b0768bfc](https://linux-hardware.org/?probe=95b0768bfc) | Mar 25, 2023 |
| MSI           | 2AE0                        | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Lenovo        | SHARKBAY No DPK             | [2941abc936](https://linux-hardware.org/?probe=2941abc936) | Mar 25, 2023 |
| ASRock        | AD525PV3                    | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| MSI           | A320M-A PRO MAX             | [505777b9b6](https://linux-hardware.org/?probe=505777b9b6) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [518cef7fe4](https://linux-hardware.org/?probe=518cef7fe4) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [cce19de050](https://linux-hardware.org/?probe=cce19de050) | Mar 24, 2023 |
| Gigabyte      | H77N-WIFI                   | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| Itautec       | ST 4265                     | [4671d7c30e](https://linux-hardware.org/?probe=4671d7c30e) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| ASUSTek       | P8P67 PRO                   | [7ed577df49](https://linux-hardware.org/?probe=7ed577df49) | Mar 23, 2023 |
| Gigabyte      | A520M S2H                   | [50931f533e](https://linux-hardware.org/?probe=50931f533e) | Mar 23, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | [0027308e3d](https://linux-hardware.org/?probe=0027308e3d) | Mar 23, 2023 |
| ASRock        | X79 Extreme6                | [1287699f09](https://linux-hardware.org/?probe=1287699f09) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| MSI           | PRO B650M-A WIFI            | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| Lenovo        | SDK0F82993 WIN              | [fbff3ec47c](https://linux-hardware.org/?probe=fbff3ec47c) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [299072c37e](https://linux-hardware.org/?probe=299072c37e) | Mar 22, 2023 |
| ASUSTek       | B85M-G                      | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| ASUSTek       | PRIME B550M-A               | [aede16096d](https://linux-hardware.org/?probe=aede16096d) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| NZXT          | N7 B550                     | [8ca9bc3db9](https://linux-hardware.org/?probe=8ca9bc3db9) | Mar 21, 2023 |
| MSI           | X570-A PRO                  | [a9c58c1f47](https://linux-hardware.org/?probe=a9c58c1f47) | Mar 21, 2023 |
| Shuttle       | SH570                       | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [3298f3c951](https://linux-hardware.org/?probe=3298f3c951) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [cb21d30b9e](https://linux-hardware.org/?probe=cb21d30b9e) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4483bfa54d](https://linux-hardware.org/?probe=4483bfa54d) | Mar 20, 2023 |
| Win elemen... | M600                        | [eb40c2a7fc](https://linux-hardware.org/?probe=eb40c2a7fc) | Mar 20, 2023 |
| ASRock        | H81M-HG4 R4.0               | [ef87ac1a64](https://linux-hardware.org/?probe=ef87ac1a64) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Dell          | 0YXT71 A00                  | [7a4669a603](https://linux-hardware.org/?probe=7a4669a603) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | [93ff9f0891](https://linux-hardware.org/?probe=93ff9f0891) | Mar 19, 2023 |
| ASRock        | B450M-HDV R4.0              | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P                | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| ASUSTek       | PRIME B550M-A               | [b63ad62fc2](https://linux-hardware.org/?probe=b63ad62fc2) | Mar 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [783a968012](https://linux-hardware.org/?probe=783a968012) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [501c72715a](https://linux-hardware.org/?probe=501c72715a) | Mar 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [280e67175b](https://linux-hardware.org/?probe=280e67175b) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [35505ab2bf](https://linux-hardware.org/?probe=35505ab2bf) | Mar 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [261bcbfc32](https://linux-hardware.org/?probe=261bcbfc32) | Mar 17, 2023 |
| ASUSTek       | M2N-E SLI                   | [bf5b0c4406](https://linux-hardware.org/?probe=bf5b0c4406) | Mar 17, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [4d82c078c8](https://linux-hardware.org/?probe=4d82c078c8) | Mar 16, 2023 |
| Medion        | B550A4-EM                   | [458aea611f](https://linux-hardware.org/?probe=458aea611f) | Mar 16, 2023 |
| Gigabyte      | G41MT-D3                    | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Gigabyte      | H410M H V3                  | [6023b7ce1d](https://linux-hardware.org/?probe=6023b7ce1d) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | [69cb363858](https://linux-hardware.org/?probe=69cb363858) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | [c9e4cb7c2e](https://linux-hardware.org/?probe=c9e4cb7c2e) | Mar 16, 2023 |
| ASUSTek       | PRIME B550M-A               | [f48398a1e2](https://linux-hardware.org/?probe=f48398a1e2) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS PRO              | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [897879b2c7](https://linux-hardware.org/?probe=897879b2c7) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [bf303c0c16](https://linux-hardware.org/?probe=bf303c0c16) | Mar 16, 2023 |
| MSI           | H81M-P33                    | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| MSI           | B450M MORTAR                | [14a4314e39](https://linux-hardware.org/?probe=14a4314e39) | Mar 15, 2023 |
| Dell          | 0NC2VH A01                  | [e6fd051ae8](https://linux-hardware.org/?probe=e6fd051ae8) | Mar 14, 2023 |
| Huanan        | X99-QD4 V1.0                | [800c597040](https://linux-hardware.org/?probe=800c597040) | Mar 14, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| ASRock        | H170M Pro4                  | [c34ef2441a](https://linux-hardware.org/?probe=c34ef2441a) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| ASUSTek       | Rampage V EXTREME           | [e186537a7e](https://linux-hardware.org/?probe=e186537a7e) | Mar 14, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [532c5768ad](https://linux-hardware.org/?probe=532c5768ad) | Mar 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c59a00db09](https://linux-hardware.org/?probe=c59a00db09) | Mar 13, 2023 |
| MSI           | PRO B550M-VC WIFI           | [c3a62d14b3](https://linux-hardware.org/?probe=c3a62d14b3) | Mar 13, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [e245557641](https://linux-hardware.org/?probe=e245557641) | Mar 13, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [532bf1dca2](https://linux-hardware.org/?probe=532bf1dca2) | Mar 13, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5434188010](https://linux-hardware.org/?probe=5434188010) | Mar 12, 2023 |
| MSI           | A320M-A PRO MAX             | [07ebf171d6](https://linux-hardware.org/?probe=07ebf171d6) | Mar 12, 2023 |
| ASUSTek       | PRIME A520M-E               | [d2b4cffe84](https://linux-hardware.org/?probe=d2b4cffe84) | Mar 11, 2023 |
| ASUSTek       | H170-PRO                    | [c3e0b5bc1d](https://linux-hardware.org/?probe=c3e0b5bc1d) | Mar 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [b7a4968bcd](https://linux-hardware.org/?probe=b7a4968bcd) | Mar 11, 2023 |
| Gigabyte      | Z170X-UD3 Ultra-CF          | [fa2be7de30](https://linux-hardware.org/?probe=fa2be7de30) | Mar 11, 2023 |
| Unknown       | Unknown                     | [7e7927f2dd](https://linux-hardware.org/?probe=7e7927f2dd) | Mar 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1d552cfca2](https://linux-hardware.org/?probe=1d552cfca2) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [0f9de03c50](https://linux-hardware.org/?probe=0f9de03c50) | Mar 11, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [e9af5c4cb2](https://linux-hardware.org/?probe=e9af5c4cb2) | Mar 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [ca937e17a7](https://linux-hardware.org/?probe=ca937e17a7) | Mar 10, 2023 |
| Gigabyte      | G41MT-D3                    | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [9cd2cf85c7](https://linux-hardware.org/?probe=9cd2cf85c7) | Mar 09, 2023 |
| ASRock        | Z370M Pro4                  | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| MSI           | MAG B460M MORTAR            | [233700c52d](https://linux-hardware.org/?probe=233700c52d) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [62800640af](https://linux-hardware.org/?probe=62800640af) | Mar 07, 2023 |
| AZW           | GTR V02                     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bac7bd817d](https://linux-hardware.org/?probe=bac7bd817d) | Mar 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [5750b514a0](https://linux-hardware.org/?probe=5750b514a0) | Mar 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [6735fc94ae](https://linux-hardware.org/?probe=6735fc94ae) | Mar 06, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| MSI           | MAG B460M MORTAR            | [de44275a2c](https://linux-hardware.org/?probe=de44275a2c) | Mar 06, 2023 |
| Dell          | 0RY007                      | [1aff8f499e](https://linux-hardware.org/?probe=1aff8f499e) | Mar 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d725cc57f0](https://linux-hardware.org/?probe=d725cc57f0) | Mar 06, 2023 |
| ASUSTek       | PRIME X570-P                | [14eb2d295d](https://linux-hardware.org/?probe=14eb2d295d) | Mar 06, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [e6421e9301](https://linux-hardware.org/?probe=e6421e9301) | Mar 06, 2023 |
| Huanan        | X99-TF                      | [99a3729e53](https://linux-hardware.org/?probe=99a3729e53) | Mar 05, 2023 |
| MSI           | B550M PRO                   | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| HP            | 2B05                        | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| HP            | 2B05                        | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [f0b9f4e39f](https://linux-hardware.org/?probe=f0b9f4e39f) | Mar 05, 2023 |
| ASRock        | B560M-ITX/ac                | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| ASUSTek       | P7H55-M LX                  | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| ASRock        | X470 Taichi                 | [59392dfa37](https://linux-hardware.org/?probe=59392dfa37) | Mar 04, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [06063736c6](https://linux-hardware.org/?probe=06063736c6) | Mar 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b4110d0e0b](https://linux-hardware.org/?probe=b4110d0e0b) | Mar 04, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [4b9b04ef26](https://linux-hardware.org/?probe=4b9b04ef26) | Mar 03, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [b6535fad6b](https://linux-hardware.org/?probe=b6535fad6b) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [7efed287ee](https://linux-hardware.org/?probe=7efed287ee) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | [191bd6ec28](https://linux-hardware.org/?probe=191bd6ec28) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | [391c255a97](https://linux-hardware.org/?probe=391c255a97) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [277d16fb2a](https://linux-hardware.org/?probe=277d16fb2a) | Mar 02, 2023 |
| ASUSTek       | Maximus VII RANGER          | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | [e699d6bb6e](https://linux-hardware.org/?probe=e699d6bb6e) | Mar 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| AZW           | SEi                         | [eb876ab2f4](https://linux-hardware.org/?probe=eb876ab2f4) | Mar 02, 2023 |
| AZW           | SEi                         | [7184a124c7](https://linux-hardware.org/?probe=7184a124c7) | Mar 02, 2023 |
| Dell          | 0KRC95 A02                  | [3bb7b686ec](https://linux-hardware.org/?probe=3bb7b686ec) | Mar 02, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [420e6e6325](https://linux-hardware.org/?probe=420e6e6325) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [1b3d15d8f6](https://linux-hardware.org/?probe=1b3d15d8f6) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [0485a3d508](https://linux-hardware.org/?probe=0485a3d508) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [9d6539b8f6](https://linux-hardware.org/?probe=9d6539b8f6) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-K               | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| HP            | 834F                        | [96631603b3](https://linux-hardware.org/?probe=96631603b3) | Mar 01, 2023 |
| MSI           | A320M GRENADE               | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [713781f44e](https://linux-hardware.org/?probe=713781f44e) | Mar 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [833b6835b6](https://linux-hardware.org/?probe=833b6835b6) | Mar 01, 2023 |
| Dell          | 0KRC95 A02                  | [5cf1539621](https://linux-hardware.org/?probe=5cf1539621) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [48c5c743c9](https://linux-hardware.org/?probe=48c5c743c9) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| HP            | 158A                        | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| ASUSTek       | PRIME Q270M-C               | [3a9683fbb7](https://linux-hardware.org/?probe=3a9683fbb7) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| Gigabyte      | Z170MX-Gaming 5             | [1f0e9197f9](https://linux-hardware.org/?probe=1f0e9197f9) | Feb 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [a121d0545a](https://linux-hardware.org/?probe=a121d0545a) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c56cf68cef](https://linux-hardware.org/?probe=c56cf68cef) | Feb 26, 2023 |
| Gigabyte      | EX58-UD5                    | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| Gigabyte      | H510M S2                    | [24ea8468ca](https://linux-hardware.org/?probe=24ea8468ca) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [c204192a4b](https://linux-hardware.org/?probe=c204192a4b) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-A II            | [420520e3ab](https://linux-hardware.org/?probe=420520e3ab) | Feb 25, 2023 |
| Dell          | 0W2F8G A01                  | [1d0d54843b](https://linux-hardware.org/?probe=1d0d54843b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | [27fa5a62b6](https://linux-hardware.org/?probe=27fa5a62b6) | Feb 24, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| MSI           | B350M PRO-VDH               | [748d109cb3](https://linux-hardware.org/?probe=748d109cb3) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [5d901ddc4e](https://linux-hardware.org/?probe=5d901ddc4e) | Feb 24, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [2312252934](https://linux-hardware.org/?probe=2312252934) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| MSI           | Z170A PC MATE               | [5ee58b9271](https://linux-hardware.org/?probe=5ee58b9271) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A               | [acdea94715](https://linux-hardware.org/?probe=acdea94715) | Feb 23, 2023 |
| Gateway       | SX2185                      | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| ASRock        | B450M Pro4                  | [193a97dfb1](https://linux-hardware.org/?probe=193a97dfb1) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [eade3920d9](https://linux-hardware.org/?probe=eade3920d9) | Feb 23, 2023 |
| ASUSTek       | P5L-MX                      | [cc19e49d3c](https://linux-hardware.org/?probe=cc19e49d3c) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| ASUSTek       | P5L-MX                      | [9eb9ca3cfb](https://linux-hardware.org/?probe=9eb9ca3cfb) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| ASRock        | AB350 Pro4                  | [aaad317fe4](https://linux-hardware.org/?probe=aaad317fe4) | Feb 22, 2023 |
| ASRockRack    | X470D4U                     | [162a5279bc](https://linux-hardware.org/?probe=162a5279bc) | Feb 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [8fd85f724b](https://linux-hardware.org/?probe=8fd85f724b) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH X99              | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| ASRock        | X670E Pro RS                | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [42099690a6](https://linux-hardware.org/?probe=42099690a6) | Feb 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6eda9f2592](https://linux-hardware.org/?probe=6eda9f2592) | Feb 19, 2023 |
| ASUSTek       | P5Q SE2                     | [37b0d0609f](https://linux-hardware.org/?probe=37b0d0609f) | Feb 18, 2023 |
| ASRock        | H110 Pro BTC+               | [bce117c4dc](https://linux-hardware.org/?probe=bce117c4dc) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| MSI           | H410M PRO-VH                | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [5fe0f2c1fe](https://linux-hardware.org/?probe=5fe0f2c1fe) | Feb 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [f9fb638882](https://linux-hardware.org/?probe=f9fb638882) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [750c0f6337](https://linux-hardware.org/?probe=750c0f6337) | Feb 17, 2023 |
| ASRock        | X470 Taichi                 | [71685845fe](https://linux-hardware.org/?probe=71685845fe) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [8e3bad7795](https://linux-hardware.org/?probe=8e3bad7795) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [add68ac711](https://linux-hardware.org/?probe=add68ac711) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | [a19a7a2edd](https://linux-hardware.org/?probe=a19a7a2edd) | Feb 16, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f4e8b0e952](https://linux-hardware.org/?probe=f4e8b0e952) | Feb 16, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [ca54397755](https://linux-hardware.org/?probe=ca54397755) | Feb 15, 2023 |
| MSI           | FM2-A75MA-E35               | [a7f2ca398d](https://linux-hardware.org/?probe=a7f2ca398d) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7d8c3e7e48](https://linux-hardware.org/?probe=7d8c3e7e48) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| HP            | 8714                        | [19a66b5101](https://linux-hardware.org/?probe=19a66b5101) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [43dff5bee7](https://linux-hardware.org/?probe=43dff5bee7) | Feb 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | [10c8101c9b](https://linux-hardware.org/?probe=10c8101c9b) | Feb 14, 2023 |
| MSI           | X99A SLI PLUS               | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | 0R6PCT A01                  | [4126ed8507](https://linux-hardware.org/?probe=4126ed8507) | Feb 13, 2023 |
| Pegatron      | 2AB6                        | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a5469c55ac](https://linux-hardware.org/?probe=a5469c55ac) | Feb 12, 2023 |
| ASUSTek       | PRIME B550M-A               | [2d63c8d887](https://linux-hardware.org/?probe=2d63c8d887) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| ASUSTek       | Z97-P                       | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| ASRock        | Z790 Pro RS WiFi            | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6474c43d80](https://linux-hardware.org/?probe=6474c43d80) | Feb 11, 2023 |
| ASRock        | A300M-STX                   | [79266ec6c7](https://linux-hardware.org/?probe=79266ec6c7) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9a2b8045de](https://linux-hardware.org/?probe=9a2b8045de) | Feb 10, 2023 |
| HP            | 8714                        | [3938395f75](https://linux-hardware.org/?probe=3938395f75) | Feb 10, 2023 |
| ASUSTek       | PRIME H410M-K               | [c3a837a320](https://linux-hardware.org/?probe=c3a837a320) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [70b81f3738](https://linux-hardware.org/?probe=70b81f3738) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| MSI           | H110M PRO-VD PLUS           | [c296dedf74](https://linux-hardware.org/?probe=c296dedf74) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [69c30e6f7b](https://linux-hardware.org/?probe=69c30e6f7b) | Feb 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [a12cca2eeb](https://linux-hardware.org/?probe=a12cca2eeb) | Feb 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [b02b8779fc](https://linux-hardware.org/?probe=b02b8779fc) | Feb 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5c5d5d4304](https://linux-hardware.org/?probe=5c5d5d4304) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH X79              | [21910f6687](https://linux-hardware.org/?probe=21910f6687) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Lenovo        | ThinkServer TS140           | [1bac17097f](https://linux-hardware.org/?probe=1bac17097f) | Feb 07, 2023 |
| ASUSTek       | SABERTOOTH X79              | [ace0ce95b9](https://linux-hardware.org/?probe=ace0ce95b9) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [47153e938c](https://linux-hardware.org/?probe=47153e938c) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e82192ba4c](https://linux-hardware.org/?probe=e82192ba4c) | Feb 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d91fe3e151](https://linux-hardware.org/?probe=d91fe3e151) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31a56f80dd](https://linux-hardware.org/?probe=31a56f80dd) | Feb 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [ff01db5c9a](https://linux-hardware.org/?probe=ff01db5c9a) | Feb 06, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f1e58aba53](https://linux-hardware.org/?probe=f1e58aba53) | Feb 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [10cf328828](https://linux-hardware.org/?probe=10cf328828) | Feb 06, 2023 |
| Gigabyte      | B450M DS3H V2               | [781dc9da09](https://linux-hardware.org/?probe=781dc9da09) | Feb 06, 2023 |
| Compal        | DIP00                       | [632d4c313a](https://linux-hardware.org/?probe=632d4c313a) | Feb 06, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [99d0ce5421](https://linux-hardware.org/?probe=99d0ce5421) | Feb 05, 2023 |
| HP            | 1589                        | [1872d63c2b](https://linux-hardware.org/?probe=1872d63c2b) | Feb 05, 2023 |
| HP            | 1589                        | [69c0ab962c](https://linux-hardware.org/?probe=69c0ab962c) | Feb 05, 2023 |
| Intel         | X99                         | [e8790caf8d](https://linux-hardware.org/?probe=e8790caf8d) | Feb 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [944149e350](https://linux-hardware.org/?probe=944149e350) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [1c6725b5eb](https://linux-hardware.org/?probe=1c6725b5eb) | Feb 04, 2023 |
| Gigabyte      | Z77MX-D3H                   | [a17959ea9b](https://linux-hardware.org/?probe=a17959ea9b) | Feb 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | [3633683d62](https://linux-hardware.org/?probe=3633683d62) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [f2578f11e1](https://linux-hardware.org/?probe=f2578f11e1) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5e9c75d478](https://linux-hardware.org/?probe=5e9c75d478) | Feb 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [e680a7484e](https://linux-hardware.org/?probe=e680a7484e) | Feb 03, 2023 |
| HP            | 8714                        | [b8abceccbc](https://linux-hardware.org/?probe=b8abceccbc) | Feb 03, 2023 |
| Pegatron      | IPXSB-H61                   | [a694854d87](https://linux-hardware.org/?probe=a694854d87) | Feb 02, 2023 |
| Acer          | Veriton M2631 V:1.0         | [28e1975b51](https://linux-hardware.org/?probe=28e1975b51) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [9b8d82dfcd](https://linux-hardware.org/?probe=9b8d82dfcd) | Feb 02, 2023 |
| Gigabyte      | J1900M-D2P                  | [c7b6222f08](https://linux-hardware.org/?probe=c7b6222f08) | Feb 02, 2023 |
| ASRock        | Z77 Extreme4                | [6598bc47dd](https://linux-hardware.org/?probe=6598bc47dd) | Feb 02, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [15c523ee98](https://linux-hardware.org/?probe=15c523ee98) | Feb 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f2919f7135](https://linux-hardware.org/?probe=f2919f7135) | Feb 01, 2023 |
| ASRock        | B450M Pro4 R2.0             | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| ASUSTek       | H81M-A/BR                   | [7d271a8235](https://linux-hardware.org/?probe=7d271a8235) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [d35cf58f46](https://linux-hardware.org/?probe=d35cf58f46) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| MSI           | Z170A PC MATE               | [ff305089b2](https://linux-hardware.org/?probe=ff305089b2) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [779b723b67](https://linux-hardware.org/?probe=779b723b67) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [5f2948351d](https://linux-hardware.org/?probe=5f2948351d) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| AZW           | U59                         | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| AZW           | U59                         | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Gigabyte      | H97M-D3H                    | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [318b0a5ecb](https://linux-hardware.org/?probe=318b0a5ecb) | Jan 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [6a4a26884d](https://linux-hardware.org/?probe=6a4a26884d) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [8e4f1d2ed2](https://linux-hardware.org/?probe=8e4f1d2ed2) | Jan 30, 2023 |
| ASUSTek       | PRIME B550M-A               | [585c3c8f85](https://linux-hardware.org/?probe=585c3c8f85) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASRock        | N68-S UCC                   | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| ASUSTek       | GA15DH                      | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [ef43edeee5](https://linux-hardware.org/?probe=ef43edeee5) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| ASRock        | X570M Pro4                  | [e72f7f2fb1](https://linux-hardware.org/?probe=e72f7f2fb1) | Jan 29, 2023 |
| Acer          | FMP55                       | [d091fbc8d3](https://linux-hardware.org/?probe=d091fbc8d3) | Jan 29, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [d9f9d4bc89](https://linux-hardware.org/?probe=d9f9d4bc89) | Jan 27, 2023 |
| ASRock        | 970 Pro3 R2.0               | [676f900958](https://linux-hardware.org/?probe=676f900958) | Jan 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [e619db262a](https://linux-hardware.org/?probe=e619db262a) | Jan 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [c0ea09ef3c](https://linux-hardware.org/?probe=c0ea09ef3c) | Jan 27, 2023 |
| ASRock        | AD2700-ITX                  | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [decfe6ab97](https://linux-hardware.org/?probe=decfe6ab97) | Jan 25, 2023 |
| Dell          | 0XFWHV A00                  | [52ee3df163](https://linux-hardware.org/?probe=52ee3df163) | Jan 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Dell          | 0X30MX A00                  | [c323a1a215](https://linux-hardware.org/?probe=c323a1a215) | Jan 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [2f215e1ce7](https://linux-hardware.org/?probe=2f215e1ce7) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| Dell          | 0Y56T3 A00                  | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| MSI           | H510M PRO                   | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| MSI           | B450-A PRO                  | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| AZW           | GTR V02                     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [7a067fe264](https://linux-hardware.org/?probe=7a067fe264) | Jan 21, 2023 |
| ASRock        | FM2A88X Extreme6+           | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [5bbd614c0f](https://linux-hardware.org/?probe=5bbd614c0f) | Jan 20, 2023 |
| HP            | 0AECh D                     | [b2ea95f507](https://linux-hardware.org/?probe=b2ea95f507) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| Dell          | 0GY6Y8 A02                  | [33b364ed89](https://linux-hardware.org/?probe=33b364ed89) | Jan 19, 2023 |
| ASRock        | X300M-STX                   | [8303a9c2a0](https://linux-hardware.org/?probe=8303a9c2a0) | Jan 18, 2023 |
| Dell          | 0XFRWW A00                  | [2b96d4b6f6](https://linux-hardware.org/?probe=2b96d4b6f6) | Jan 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [011b9a41cd](https://linux-hardware.org/?probe=011b9a41cd) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | 0KRC95 A02                  | [01cf6039d0](https://linux-hardware.org/?probe=01cf6039d0) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| ASUSTek       | Z97-K                       | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [8753bd8277](https://linux-hardware.org/?probe=8753bd8277) | Jan 17, 2023 |
| Gigabyte      | G41MT-D3                    | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d5843b83af](https://linux-hardware.org/?probe=d5843b83af) | Jan 16, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [dd16b56d30](https://linux-hardware.org/?probe=dd16b56d30) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Dell          | 0M863N A01                  | [1dff7cb016](https://linux-hardware.org/?probe=1dff7cb016) | Jan 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b68ce1375d](https://linux-hardware.org/?probe=b68ce1375d) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK               | [978682daa6](https://linux-hardware.org/?probe=978682daa6) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| AZW           | GTR V02                     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| Dell          | 0W2F8G A01                  | [999fcca032](https://linux-hardware.org/?probe=999fcca032) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| ASUSTek       | H170 PRO GAMING             | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| HP            | 3047h                       | [5eb46c9039](https://linux-hardware.org/?probe=5eb46c9039) | Jan 12, 2023 |
| HP            | 3047h                       | [0c035c1a04](https://linux-hardware.org/?probe=0c035c1a04) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| Unknown       | X79                         | [62bf02da9d](https://linux-hardware.org/?probe=62bf02da9d) | Jan 12, 2023 |
| Unknown       | X79                         | [aed457b56c](https://linux-hardware.org/?probe=aed457b56c) | Jan 12, 2023 |
| MSI           | B550-A PRO                  | [28d13d17ba](https://linux-hardware.org/?probe=28d13d17ba) | Jan 12, 2023 |
| Pegatron      | 2AC3                        | [3cfb7d9e7c](https://linux-hardware.org/?probe=3cfb7d9e7c) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [760cc2eaed](https://linux-hardware.org/?probe=760cc2eaed) | Jan 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a5f45ca97](https://linux-hardware.org/?probe=0a5f45ca97) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [7c7c8175c0](https://linux-hardware.org/?probe=7c7c8175c0) | Jan 09, 2023 |
| Gigabyte      | H77N-WIFI                   | [95cfb68187](https://linux-hardware.org/?probe=95cfb68187) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| AZW           | GTR V02                     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| MSI           | MEG X570 ACE                | [853f3c06ce](https://linux-hardware.org/?probe=853f3c06ce) | Jan 08, 2023 |
| MSI           | X570-A PRO                  | [d3e35671cd](https://linux-hardware.org/?probe=d3e35671cd) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Acer          | FMCP7A-ION-LE               | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e417e45252](https://linux-hardware.org/?probe=e417e45252) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e7b27ba60c](https://linux-hardware.org/?probe=e7b27ba60c) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| Positivo      | POS-PIQ57BQA                | [4453ef0d86](https://linux-hardware.org/?probe=4453ef0d86) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| Gigabyte      | B450M S2H                   | [6d6e710ac3](https://linux-hardware.org/?probe=6d6e710ac3) | Jan 04, 2023 |
| Gigabyte      | Z690 UD DDR4                | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| Gigabyte      | J1900M-D2P                  | [ad776cdf84](https://linux-hardware.org/?probe=ad776cdf84) | Jan 04, 2023 |
| Dell          | 0KRC95 A02                  | [8e30a9a43e](https://linux-hardware.org/?probe=8e30a9a43e) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | [e03b53cc0e](https://linux-hardware.org/?probe=e03b53cc0e) | Jan 04, 2023 |
| Gigabyte      | H410M H V3                  | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| Positivo      | POS-EIB85CZ                 | [639f5a2bf7](https://linux-hardware.org/?probe=639f5a2bf7) | Jan 03, 2023 |
| ASUSTek       | PRIME X570-P                | [f1962e0076](https://linux-hardware.org/?probe=f1962e0076) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| Dell          | 0KRC95 A02                  | [d7c57c2bae](https://linux-hardware.org/?probe=d7c57c2bae) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [7c98c0b00d](https://linux-hardware.org/?probe=7c98c0b00d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [4e900247e4](https://linux-hardware.org/?probe=4e900247e4) | Jan 02, 2023 |
| ASRock        | Z77 Professional            | [bf09b21dc7](https://linux-hardware.org/?probe=bf09b21dc7) | Jan 02, 2023 |
| ASRock        | FM2A88M-HD+ R2.0            | [8e9080dc74](https://linux-hardware.org/?probe=8e9080dc74) | Jan 01, 2023 |
| ASUSTek       | H81M-PLUS                   | [752fe53b7c](https://linux-hardware.org/?probe=752fe53b7c) | Jan 01, 2023 |
| Intel         | DG41TY AAE47335-300         | [11f3804cb6](https://linux-hardware.org/?probe=11f3804cb6) | Jan 01, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3b6d1593c8](https://linux-hardware.org/?probe=3b6d1593c8) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f16b55ea54](https://linux-hardware.org/?probe=f16b55ea54) | Dec 31, 2022 |
| Shuttle       | SH570                       | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| ASRock        | A320M-DVS R4.0              | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| Shuttle       | SH570                       | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | X79 Extreme6                | [5ea31811b4](https://linux-hardware.org/?probe=5ea31811b4) | Dec 30, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| ASUSTek       | Z87-PRO                     | [eafab9edba](https://linux-hardware.org/?probe=eafab9edba) | Dec 30, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bdc5158ffb](https://linux-hardware.org/?probe=bdc5158ffb) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [4cf9d40c0d](https://linux-hardware.org/?probe=4cf9d40c0d) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [7e53808767](https://linux-hardware.org/?probe=7e53808767) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Gigabyte      | B365M DS3H                  | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| Dell          | 0N4YC8 A00                  | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [7bb247e453](https://linux-hardware.org/?probe=7bb247e453) | Dec 28, 2022 |
| Gigabyte      | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| Gigabyte      | B650I AORUS ULTRA           | [3c25f43c23](https://linux-hardware.org/?probe=3c25f43c23) | Dec 28, 2022 |
| Itautec       | ST 4265                     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| MSI           | Z390-A PRO                  | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Itautec       | ST 4265                     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [4c97c87b61](https://linux-hardware.org/?probe=4c97c87b61) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [46705eb79f](https://linux-hardware.org/?probe=46705eb79f) | Dec 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [e853f645cf](https://linux-hardware.org/?probe=e853f645cf) | Dec 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| MSI           | Z270M MORTAR                | [70564a2846](https://linux-hardware.org/?probe=70564a2846) | Dec 24, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bf8f02ac85](https://linux-hardware.org/?probe=bf8f02ac85) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [926850a516](https://linux-hardware.org/?probe=926850a516) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| ASUSTek       | B85-PLUS                    | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| ASUSTek       | B85-PLUS                    | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [8428e68855](https://linux-hardware.org/?probe=8428e68855) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Dell          | 02YRK5 A02                  | [f5f6093483](https://linux-hardware.org/?probe=f5f6093483) | Dec 21, 2022 |
| Intel         | H81                         | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| ASRock        | Z790 Pro RS WiFi            | [d54c198ec8](https://linux-hardware.org/?probe=d54c198ec8) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [60dbf09ee4](https://linux-hardware.org/?probe=60dbf09ee4) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [6a964b9d6b](https://linux-hardware.org/?probe=6a964b9d6b) | Dec 19, 2022 |
| Gigabyte      | A520M DS3H                  | [4251c08b5d](https://linux-hardware.org/?probe=4251c08b5d) | Dec 18, 2022 |
| Dell          | 0KRC95 A02                  | [e7bb083869](https://linux-hardware.org/?probe=e7bb083869) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | [53c582a7f6](https://linux-hardware.org/?probe=53c582a7f6) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| Gigabyte      | J1900M-D2P                  | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [54132f7285](https://linux-hardware.org/?probe=54132f7285) | Dec 17, 2022 |
| HP            | 82F2 A01                    | [859d719a2a](https://linux-hardware.org/?probe=859d719a2a) | Dec 16, 2022 |
| Gigabyte      | Z77MX-D3H                   | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-K               | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| Lenovo        | 31900003 STD                | [81dea8d96e](https://linux-hardware.org/?probe=81dea8d96e) | Dec 15, 2022 |
| ASRock        | X670E Steel Legend          | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| MSI           | B550-A PRO B02              | [3a1ebe10f8](https://linux-hardware.org/?probe=3a1ebe10f8) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [572f0231a5](https://linux-hardware.org/?probe=572f0231a5) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a0d17e1d50](https://linux-hardware.org/?probe=a0d17e1d50) | Dec 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| Intel         | DQ67SW AAG12527-309         | [3b826b42e0](https://linux-hardware.org/?probe=3b826b42e0) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [fa4afa166d](https://linux-hardware.org/?probe=fa4afa166d) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [5cde0cdcc4](https://linux-hardware.org/?probe=5cde0cdcc4) | Dec 14, 2022 |
| HP            | 18E4                        | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [1ccd39b328](https://linux-hardware.org/?probe=1ccd39b328) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| Dell          | 0YJMC0 A01                  | [59de758672](https://linux-hardware.org/?probe=59de758672) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1800fc9efb](https://linux-hardware.org/?probe=1800fc9efb) | Dec 14, 2022 |
| Gigabyte      | B550M DS3H                  | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| MSI           | PRO B650M-A WIFI            | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [469dfe26a6](https://linux-hardware.org/?probe=469dfe26a6) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| ASRock        | X79 Extreme6                | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| Gigabyte      | H370M DS3H-CF               | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | [6bf96cf0fc](https://linux-hardware.org/?probe=6bf96cf0fc) | Dec 11, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Lenovo        | ThinkStation S30 056851U    | [8c7b6cfca0](https://linux-hardware.org/?probe=8c7b6cfca0) | Dec 10, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| MSI           | H97M-G43                    | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| ASRock        | X670E Steel Legend          | [11df680f78](https://linux-hardware.org/?probe=11df680f78) | Dec 09, 2022 |
| Gigabyte      | G31_ICH7                    | [d433eed3f1](https://linux-hardware.org/?probe=d433eed3f1) | Dec 09, 2022 |
| Dell          | 0GU083 A00                  | [1f3f73a41c](https://linux-hardware.org/?probe=1f3f73a41c) | Dec 09, 2022 |
| Gigabyte      | Z77MX-D3H                   | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [a875eabf3d](https://linux-hardware.org/?probe=a875eabf3d) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [6ab58fe686](https://linux-hardware.org/?probe=6ab58fe686) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [07e4a8072a](https://linux-hardware.org/?probe=07e4a8072a) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5544994d11](https://linux-hardware.org/?probe=5544994d11) | Dec 08, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| Shenzhen M... | HX90G                       | [83a892b661](https://linux-hardware.org/?probe=83a892b661) | Dec 08, 2022 |
| Gigabyte      | A520I AC                    | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| MSI           | H97M-G43                    | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [551e0142a8](https://linux-hardware.org/?probe=551e0142a8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| MSI           | B550-A PRO                  | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| Gigabyte      | X570 GAMING X               | [811b0e1a71](https://linux-hardware.org/?probe=811b0e1a71) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5be32d156a](https://linux-hardware.org/?probe=5be32d156a) | Dec 06, 2022 |
| HP            | 8767 A                      | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| Acer          | FMP55                       | [78aabc71bf](https://linux-hardware.org/?probe=78aabc71bf) | Dec 05, 2022 |
| Unknown       | HX90                        | [9f3f9dec0b](https://linux-hardware.org/?probe=9f3f9dec0b) | Dec 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| HP            | 8860 A                      | [23fde1381a](https://linux-hardware.org/?probe=23fde1381a) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | 0M017G A00                  | [d6b5487094](https://linux-hardware.org/?probe=d6b5487094) | Dec 05, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cff58a3529](https://linux-hardware.org/?probe=cff58a3529) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| HP            | 158B                        | [5652b24e0d](https://linux-hardware.org/?probe=5652b24e0d) | Dec 04, 2022 |
| HP            | 158B                        | [015085e084](https://linux-hardware.org/?probe=015085e084) | Dec 04, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [0a626fffe5](https://linux-hardware.org/?probe=0a626fffe5) | Dec 04, 2022 |
| Gigabyte      | GA-970A-DS3                 | [8c06e98cf8](https://linux-hardware.org/?probe=8c06e98cf8) | Dec 03, 2022 |
| Dell          | 0N826N A02                  | [e9f0634dd6](https://linux-hardware.org/?probe=e9f0634dd6) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [80bba2043d](https://linux-hardware.org/?probe=80bba2043d) | Dec 03, 2022 |
| Unknown       | HX90                        | [40847bd89b](https://linux-hardware.org/?probe=40847bd89b) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [07a15db1a6](https://linux-hardware.org/?probe=07a15db1a6) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [6c18ee8479](https://linux-hardware.org/?probe=6c18ee8479) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [d31a6b4c0f](https://linux-hardware.org/?probe=d31a6b4c0f) | Dec 01, 2022 |
| Positivo      | POS-PIQ57BQA                | [8403658c27](https://linux-hardware.org/?probe=8403658c27) | Dec 01, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [9cd70143b5](https://linux-hardware.org/?probe=9cd70143b5) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | PRIME X370-PRO              | [aa87dfdc13](https://linux-hardware.org/?probe=aa87dfdc13) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Gigabyte      | X570 GAMING X               | [7ea2de1a3b](https://linux-hardware.org/?probe=7ea2de1a3b) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6d835027fa](https://linux-hardware.org/?probe=6d835027fa) | Nov 29, 2022 |
| MSI           | X570-A PRO                  | [92ddd925db](https://linux-hardware.org/?probe=92ddd925db) | Nov 28, 2022 |
| ASUSTek       | GA15DH                      | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [207d763813](https://linux-hardware.org/?probe=207d763813) | Nov 28, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [81a61c4765](https://linux-hardware.org/?probe=81a61c4765) | Nov 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Gigabyte      | B550 GAMING X               | [b9264b2557](https://linux-hardware.org/?probe=b9264b2557) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [33f5823764](https://linux-hardware.org/?probe=33f5823764) | Nov 25, 2022 |
| ASUSTek       | PRIME B360M-D               | [67a7943b8d](https://linux-hardware.org/?probe=67a7943b8d) | Nov 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [6f867d822a](https://linux-hardware.org/?probe=6f867d822a) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bf1722d4d6](https://linux-hardware.org/?probe=bf1722d4d6) | Nov 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [7f0ba24aad](https://linux-hardware.org/?probe=7f0ba24aad) | Nov 24, 2022 |
| ASUSTek       | GA15DH                      | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee5b760222](https://linux-hardware.org/?probe=ee5b760222) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [8de6a24029](https://linux-hardware.org/?probe=8de6a24029) | Nov 24, 2022 |
| Dell          | 0J3C2F A02                  | [0cfd78c6bb](https://linux-hardware.org/?probe=0cfd78c6bb) | Nov 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b0e5869f2d](https://linux-hardware.org/?probe=b0e5869f2d) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [1deb081598](https://linux-hardware.org/?probe=1deb081598) | Nov 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [e89ecf8da4](https://linux-hardware.org/?probe=e89ecf8da4) | Nov 23, 2022 |
| MSI           | 2A9C                        | [ee8683a595](https://linux-hardware.org/?probe=ee8683a595) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | 2A9C                        | [77dd7e3fbc](https://linux-hardware.org/?probe=77dd7e3fbc) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| ASUSTek       | Maximus IX HERO             | [587aa317bd](https://linux-hardware.org/?probe=587aa317bd) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE V2               | [d126214b62](https://linux-hardware.org/?probe=d126214b62) | Nov 22, 2022 |
| HP            | 3647h                       | [8f77a73e9b](https://linux-hardware.org/?probe=8f77a73e9b) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| ASUSTek       | PRIME Z270-A                | [540d321764](https://linux-hardware.org/?probe=540d321764) | Nov 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [34f72bd414](https://linux-hardware.org/?probe=34f72bd414) | Nov 20, 2022 |
| Gigabyte      | H310M S2H x.x               | [97ea29ed26](https://linux-hardware.org/?probe=97ea29ed26) | Nov 20, 2022 |
| Dell          | 0HY9JP A02                  | [fa0e9792f0](https://linux-hardware.org/?probe=fa0e9792f0) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK               | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| ASRock        | B450 Pro4                   | [cd0f63540b](https://linux-hardware.org/?probe=cd0f63540b) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [ecceccb3b7](https://linux-hardware.org/?probe=ecceccb3b7) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d304f26226](https://linux-hardware.org/?probe=d304f26226) | Nov 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [050e6cfd68](https://linux-hardware.org/?probe=050e6cfd68) | Nov 19, 2022 |
| ASUSTek       | Z97-P                       | [75748e49d9](https://linux-hardware.org/?probe=75748e49d9) | Nov 19, 2022 |
| Gigabyte      | M720-US3                    | [299b2cd745](https://linux-hardware.org/?probe=299b2cd745) | Nov 18, 2022 |
| Acer          | FMP55                       | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| ASRock        | X300-ITX                    | [54f7198f58](https://linux-hardware.org/?probe=54f7198f58) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | H81M-R                      | [cd129bebe1](https://linux-hardware.org/?probe=cd129bebe1) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9f45de6ee3](https://linux-hardware.org/?probe=9f45de6ee3) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| Intel         | DX79SR AAG57199-200         | [b12b9ec8d5](https://linux-hardware.org/?probe=b12b9ec8d5) | Nov 16, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [7bf6427590](https://linux-hardware.org/?probe=7bf6427590) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | PRIME A320M-E               | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| MSI           | Z390-A PRO                  | [e851ddd11a](https://linux-hardware.org/?probe=e851ddd11a) | Nov 10, 2022 |
| ASRock        | H310M-STX                   | [cb421b22a5](https://linux-hardware.org/?probe=cb421b22a5) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| Gigabyte      | B85M-D3V-A                  | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Dell          | 09WH54 A00                  | [c7723a2b2f](https://linux-hardware.org/?probe=c7723a2b2f) | Nov 07, 2022 |
| Gigabyte      | X670 GAMING X AX            | [1a96ebec7a](https://linux-hardware.org/?probe=1a96ebec7a) | Nov 07, 2022 |
| Gigabyte      | A320M-H-CF                  | [fa33ccff27](https://linux-hardware.org/?probe=fa33ccff27) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [02104ae91b](https://linux-hardware.org/?probe=02104ae91b) | Nov 05, 2022 |
| ASRock        | X570 Taichi                 | [d9902c03cb](https://linux-hardware.org/?probe=d9902c03cb) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [108df7bc6d](https://linux-hardware.org/?probe=108df7bc6d) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a2c8fe2afa](https://linux-hardware.org/?probe=a2c8fe2afa) | Nov 05, 2022 |
| MSI           | Z390-A PRO                  | [5cfd4967b0](https://linux-hardware.org/?probe=5cfd4967b0) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| HP            | 8459                        | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| ASUSTek       | B150 PRO GAMING             | [b2229c56c4](https://linux-hardware.org/?probe=b2229c56c4) | Nov 01, 2022 |
| Gigabyte      | B85M-D3V-A                  | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [8e2ab3d61b](https://linux-hardware.org/?probe=8e2ab3d61b) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | [ba5da6b270](https://linux-hardware.org/?probe=ba5da6b270) | Oct 29, 2022 |
| MSI           | B450M MORTAR                | [44e8a164d1](https://linux-hardware.org/?probe=44e8a164d1) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [db4db1b508](https://linux-hardware.org/?probe=db4db1b508) | Oct 25, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| HP            | 2B05                        | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7f855c9b05](https://linux-hardware.org/?probe=7f855c9b05) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [77b57dbe12](https://linux-hardware.org/?probe=77b57dbe12) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [13f4800fa8](https://linux-hardware.org/?probe=13f4800fa8) | Oct 20, 2022 |
| Gigabyte      | 970A-DS3P FX                | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| Dell          | 0WR7PY A02                  | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| Gigabyte      | H610M H DDR4                | [985b192440](https://linux-hardware.org/?probe=985b192440) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [05fa96288f](https://linux-hardware.org/?probe=05fa96288f) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| MSI           | B550M PRO-VDH               | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| Dell          | 0RY007                      | [745f69ec3d](https://linux-hardware.org/?probe=745f69ec3d) | Oct 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| Gigabyte      | B550M DS3H                  | [2f8557640c](https://linux-hardware.org/?probe=2f8557640c) | Oct 02, 2022 |
| ASUSTek       | PRIME Z270-A                | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| Intel         | DP35DP AAD81073-208         | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| Acer          | Aspire X1900                | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| ASUSTek       | Z170-A                      | [aad09d3281](https://linux-hardware.org/?probe=aad09d3281) | Sep 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| HP            | 2B05                        | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| HP            | 3397                        | [637a5570cf](https://linux-hardware.org/?probe=637a5570cf) | Sep 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| Gigabyte      | B85M-D3V-A                  | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| HP            | 1998                        | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| MSI           | Z370 TOMAHAWK               | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| Dell          | 08NPPY A00                  | [93eb00c3c5](https://linux-hardware.org/?probe=93eb00c3c5) | Jun 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [2cd65296c2](https://linux-hardware.org/?probe=2cd65296c2) | May 08, 2022 |
| HP            | 0B54h D                     | [7153ec172b](https://linux-hardware.org/?probe=7153ec172b) | Mar 21, 2022 |
| HP            | 0B54h D                     | [399cc50503](https://linux-hardware.org/?probe=399cc50503) | Mar 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.0.15-300.fc37.x86_64        | 45       | 7.59%   |
| 6.0.12-300.fc37.x86_64        | 44       | 7.42%   |
| 6.1.18-200.fc37.x86_64        | 32       | 5.4%    |
| 6.0.7-301.fc37.x86_64         | 31       | 5.23%   |
| 6.0.11-300.fc37.x86_64        | 31       | 5.23%   |
| 6.0.8-300.fc37.x86_64         | 27       | 4.55%   |
| 6.0.9-300.fc37.x86_64         | 26       | 4.38%   |
| 6.1.14-200.fc37.x86_64        | 25       | 4.22%   |
| 6.1.8-200.fc37.x86_64         | 22       | 3.71%   |
| 6.1.11-200.fc37.x86_64        | 22       | 3.71%   |
| 6.2.7-200.fc37.x86_64         | 21       | 3.54%   |
| 6.0.10-300.fc37.x86_64        | 21       | 3.54%   |
| 6.1.9-200.fc37.x86_64         | 20       | 3.37%   |
| 6.1.6-200.fc37.x86_64         | 19       | 3.2%    |
| 6.1.7-200.fc37.x86_64         | 17       | 2.87%   |
| 6.1.15-200.fc37.x86_64        | 16       | 2.7%    |
| 6.1.13-200.fc37.x86_64        | 16       | 2.7%    |
| 6.1.10-200.fc37.x86_64        | 13       | 2.19%   |
| 5.19.16-301.fc37.x86_64       | 12       | 2.02%   |
| 6.2.8-200.fc37.x86_64         | 10       | 1.69%   |
| 6.1.5-200.fc37.x86_64         | 10       | 1.69%   |
| 6.1.12-200.fc37.x86_64        | 10       | 1.69%   |
| 6.0.17-300.fc37.x86_64        | 9        | 1.52%   |
| 6.0.16-300.fc37.x86_64        | 8        | 1.35%   |
| 6.0.14-300.fc37.x86_64        | 8        | 1.35%   |
| 5.19.9-300.fc37.x86_64        | 8        | 1.35%   |
| 5.19.13-300.fc37.x86_64       | 8        | 1.35%   |
| 6.0.18-300.fc37.x86_64        | 7        | 1.18%   |
| 6.0.13-300.fc37.x86_64        | 5        | 0.84%   |
| 5.19.7-300.fc37.x86_64        | 4        | 0.67%   |
| 6.0.5-300.fc37.x86_64         | 3        | 0.51%   |
| 5.19.8-300.fc37.x86_64        | 3        | 0.51%   |
| 6.2.6-200.fc37.x86_64         | 2        | 0.34%   |
| 6.1.14-603.inttf.fc37.x86_64  | 2        | 0.34%   |
| 6.0.6-300.fc37.x86_64         | 2        | 0.34%   |
| 5.19.16-300.fc37.x86_64       | 2        | 0.34%   |
| 5.19.12-300.fc37.x86_64       | 2        | 0.34%   |
| 6.2.7_tkg_pds                 | 1        | 0.17%   |
| 6.2.7-250.vanilla.fc37.x86_64 | 1        | 0.17%   |
| 6.2.2-300.fc37.x86_64         | 1        | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.15  | 45       | 7.59%   |
| 6.0.12  | 44       | 7.42%   |
| 6.1.18  | 34       | 5.73%   |
| 6.0.11  | 32       | 5.4%    |
| 6.0.7   | 31       | 5.23%   |
| 6.1.14  | 27       | 4.55%   |
| 6.0.8   | 27       | 4.55%   |
| 6.0.9   | 26       | 4.38%   |
| 6.2.7   | 23       | 3.88%   |
| 6.1.8   | 23       | 3.88%   |
| 6.1.11  | 23       | 3.88%   |
| 6.0.10  | 23       | 3.88%   |
| 6.1.9   | 20       | 3.37%   |
| 6.1.6   | 19       | 3.2%    |
| 6.1.7   | 17       | 2.87%   |
| 6.1.15  | 16       | 2.7%    |
| 6.1.13  | 16       | 2.7%    |
| 5.19.16 | 15       | 2.53%   |
| 6.1.10  | 13       | 2.19%   |
| 6.1.5   | 11       | 1.85%   |
| 6.2.8   | 10       | 1.69%   |
| 6.1.12  | 10       | 1.69%   |
| 6.0.17  | 9        | 1.52%   |
| 6.0.16  | 8        | 1.35%   |
| 6.0.14  | 8        | 1.35%   |
| 5.19.9  | 8        | 1.35%   |
| 5.19.13 | 8        | 1.35%   |
| 6.0.18  | 7        | 1.18%   |
| 6.0.13  | 6        | 1.01%   |
| 5.19.8  | 4        | 0.67%   |
| 5.19.7  | 4        | 0.67%   |
| 6.0.5   | 3        | 0.51%   |
| 6.2.6   | 2        | 0.34%   |
| 6.0.6   | 2        | 0.34%   |
| 5.19.14 | 2        | 0.34%   |
| 5.19.12 | 2        | 0.34%   |
| 5.19.10 | 2        | 0.34%   |
| 5.19.0  | 2        | 0.34%   |
| 6.2.2   | 1        | 0.17%   |
| 6.2.1   | 1        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0     | 260      | 46.1%   |
| 6.1     | 219      | 38.83%  |
| 5.19    | 45       | 7.98%   |
| 6.2     | 37       | 6.56%   |
| 5.8     | 1        | 0.18%   |
| 5.18    | 1        | 0.18%   |
| 5.17    | 1        | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 526      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 372      | 70.59%  |
| KDE5                         | 102      | 19.35%  |
| Unknown                      | 13       | 2.47%   |
| XFCE                         | 11       | 2.09%   |
| X-Cinnamon                   | 7        | 1.33%   |
| Cinnamon                     | 7        | 1.33%   |
| MATE                         | 4        | 0.76%   |
| GNOME Classic                | 3        | 0.57%   |
| bspwm                        | 2        | 0.38%   |
| sway                         | 1        | 0.19%   |
| qtile                        | 1        | 0.19%   |
| LXQt                         | 1        | 0.19%   |
| LXDE                         | 1        | 0.19%   |
| i3                           | 1        | 0.19%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 334      | 62.78%  |
| X11     | 173      | 32.52%  |
| Tty     | 16       | 3.01%   |
| Unknown | 9        | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 313      | 58.95%  |
| GDM     | 138      | 25.99%  |
| SDDM    | 46       | 8.66%   |
| LightDM | 33       | 6.21%   |
| LXDM    | 1        | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 269      | 51.04%  |
| en_GB   | 38       | 7.21%   |
| ru_RU   | 36       | 6.83%   |
| pt_BR   | 32       | 6.07%   |
| de_DE   | 22       | 4.17%   |
| en_AU   | 18       | 3.42%   |
| en_CA   | 15       | 2.85%   |
| pl_PL   | 13       | 2.47%   |
| fr_FR   | 12       | 2.28%   |
| it_IT   | 11       | 2.09%   |
| es_ES   | 11       | 2.09%   |
| en_NZ   | 4        | 0.76%   |
| cs_CZ   | 4        | 0.76%   |
| hu_HU   | 3        | 0.57%   |
| fi_FI   | 3        | 0.57%   |
| Unknown | 3        | 0.57%   |
| vi_VN   | 2        | 0.38%   |
| sv_SE   | 2        | 0.38%   |
| nl_NL   | 2        | 0.38%   |
| ko_KR   | 2        | 0.38%   |
| en_IL   | 2        | 0.38%   |
| de_AT   | 2        | 0.38%   |
| C       | 2        | 0.38%   |
| tr_TR   | 1        | 0.19%   |
| th_TH   | 1        | 0.19%   |
| sr_RS   | 1        | 0.19%   |
| ru_UA   | 1        | 0.19%   |
| pt_PT   | 1        | 0.19%   |
| nb_NO   | 1        | 0.19%   |
| es_UY   | 1        | 0.19%   |
| es_US   | 1        | 0.19%   |
| es_SV   | 1        | 0.19%   |
| es_PE   | 1        | 0.19%   |
| es_MX   | 1        | 0.19%   |
| es_CO   | 1        | 0.19%   |
| es_CL   | 1        | 0.19%   |
| es_AR   | 1        | 0.19%   |
| en_IN   | 1        | 0.19%   |
| en_IE   | 1        | 0.19%   |
| de_CH   | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 384      | 72.32%  |
| BIOS | 147      | 27.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 409      | 77.76%  |
| Ext4  | 97       | 18.44%  |
| Xfs   | 18       | 3.42%   |
| F2fs  | 2        | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 301      | 56.47%  |
| GPT     | 201      | 37.71%  |
| MBR     | 31       | 5.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 459      | 86.44%  |
| Yes       | 72       | 13.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 430      | 81.13%  |
| Yes       | 100      | 18.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 171      | 32.51%  |
| MSI                                  | 95       | 18.06%  |
| Gigabyte Technology                  | 88       | 16.73%  |
| ASRock                               | 53       | 10.08%  |
| Dell                                 | 34       | 6.46%   |
| Hewlett-Packard                      | 19       | 3.61%   |
| Lenovo                               | 15       | 2.85%   |
| Intel                                | 9        | 1.71%   |
| Acer                                 | 7        | 1.33%   |
| Huanan                               | 4        | 0.76%   |
| Positivo                             | 3        | 0.57%   |
| Pegatron                             | 3        | 0.57%   |
| AZW                                  | 3        | 0.57%   |
| Unknown                              | 3        | 0.57%   |
| Itautec                              | 2        | 0.38%   |
| Fujitsu                              | 2        | 0.38%   |
| BESSTAR Tech                         | 2        | 0.38%   |
| Win element                          | 1        | 0.19%   |
| System76                             | 1        | 0.19%   |
| Shuttle                              | 1        | 0.19%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.19%   |
| NZXT                                 | 1        | 0.19%   |
| Medion                               | 1        | 0.19%   |
| MACHINIST                            | 1        | 0.19%   |
| Gateway                              | 1        | 0.19%   |
| GALAX                                | 1        | 0.19%   |
| ECS                                  | 1        | 0.19%   |
| Compal                               | 1        | 0.19%   |
| ASRockRack                           | 1        | 0.19%   |
| Apple                                | 1        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 16       | 3.04%   |
| Dell OptiPlex 7010                 | 7        | 1.33%   |
| ASUS TUF Gaming X570-PLUS          | 6        | 1.14%   |
| MSI MS-7C37                        | 5        | 0.95%   |
| ASUS TUF Gaming B550M-PLUS         | 5        | 0.95%   |
| MSI MS-7C84                        | 4        | 0.76%   |
| MSI MS-7C56                        | 4        | 0.76%   |
| MSI MS-7C02                        | 4        | 0.76%   |
| MSI MS-7A38                        | 4        | 0.76%   |
| ASUS ROG STRIX B450-F GAMING       | 4        | 0.76%   |
| ASUS ProArt Z690-CREATOR WIFI      | 4        | 0.76%   |
| ASUS ProArt X670E-CREATOR WIFI     | 4        | 0.76%   |
| ASUS PRIME B450M-A II              | 4        | 0.76%   |
| MSI MS-7C94                        | 3        | 0.57%   |
| MSI MS-7C91                        | 3        | 0.57%   |
| MSI MS-7C52                        | 3        | 0.57%   |
| MSI MS-7B89                        | 3        | 0.57%   |
| Gigabyte Z370 AORUS Ultra Gaming   | 3        | 0.57%   |
| Gigabyte B550M DS3H                | 3        | 0.57%   |
| ASUS Z170 PRO GAMING               | 3        | 0.57%   |
| ASUS ROG STRIX X670E-F GAMING WIFI | 3        | 0.57%   |
| ASUS ROG STRIX X570-E GAMING       | 3        | 0.57%   |
| ASUS ROG STRIX B550-F GAMING       | 3        | 0.57%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI    | 3        | 0.57%   |
| ASUS PRIME X370-PRO                | 3        | 0.57%   |
| ASUS PRIME B550M-A                 | 3        | 0.57%   |
| ASUS PRIME B550-PLUS               | 3        | 0.57%   |
| Unknown                            | 3        | 0.57%   |
| Positivo POS-PIQ57BQ               | 2        | 0.38%   |
| MSI MS-7D25                        | 2        | 0.38%   |
| MSI MS-7D22                        | 2        | 0.38%   |
| MSI MS-7C95                        | 2        | 0.38%   |
| MSI MS-7C82                        | 2        | 0.38%   |
| MSI MS-7B98                        | 2        | 0.38%   |
| MSI MS-7B93                        | 2        | 0.38%   |
| MSI MS-7B86                        | 2        | 0.38%   |
| MSI MS-7B78                        | 2        | 0.38%   |
| MSI MS-7A34                        | 2        | 0.38%   |
| MSI MS-7971                        | 2        | 0.38%   |
| MSI MS-7721                        | 2        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 44       | 8.37%   |
| ASUS ROG             | 38       | 7.22%   |
| ASUS TUF             | 28       | 5.32%   |
| Dell OptiPlex        | 19       | 3.61%   |
| ASUS All             | 16       | 3.04%   |
| ASUS ProArt          | 8        | 1.52%   |
| Lenovo ThinkCentre   | 7        | 1.33%   |
| Gigabyte X570        | 7        | 1.33%   |
| Gigabyte B550        | 6        | 1.14%   |
| Dell Precision       | 6        | 1.14%   |
| Dell Inspiron        | 6        | 1.14%   |
| MSI MS-7C37          | 5        | 0.95%   |
| Gigabyte B550M       | 5        | 0.95%   |
| MSI MS-7C84          | 4        | 0.76%   |
| MSI MS-7C56          | 4        | 0.76%   |
| MSI MS-7C02          | 4        | 0.76%   |
| MSI MS-7A38          | 4        | 0.76%   |
| HP Compaq            | 4        | 0.76%   |
| Gigabyte B450M       | 4        | 0.76%   |
| ASRock X670E         | 4        | 0.76%   |
| ASRock X570          | 4        | 0.76%   |
| ASRock B450M         | 4        | 0.76%   |
| Acer Aspire          | 4        | 0.76%   |
| MSI MS-7C94          | 3        | 0.57%   |
| MSI MS-7C91          | 3        | 0.57%   |
| MSI MS-7C52          | 3        | 0.57%   |
| MSI MS-7B89          | 3        | 0.57%   |
| HP Pavilion          | 3        | 0.57%   |
| Gigabyte Z370        | 3        | 0.57%   |
| Gigabyte B365M       | 3        | 0.57%   |
| Dell XPS             | 3        | 0.57%   |
| ASUS Z170            | 3        | 0.57%   |
| ASUS SABERTOOTH      | 3        | 0.57%   |
| ASUS Pro             | 3        | 0.57%   |
| ASUS P8Z77-V         | 3        | 0.57%   |
| Acer Veriton         | 3        | 0.57%   |
| Unknown              | 3        | 0.57%   |
| Positivo POS-PIQ57BQ | 2        | 0.38%   |
| MSI MS-7D25          | 2        | 0.38%   |
| MSI MS-7D22          | 2        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 79       | 15.02%  |
| 2019    | 70       | 13.31%  |
| 2018    | 59       | 11.22%  |
| 2022    | 54       | 10.27%  |
| 2021    | 43       | 8.17%   |
| 2017    | 41       | 7.79%   |
| 2012    | 35       | 6.65%   |
| 2013    | 34       | 6.46%   |
| 2014    | 24       | 4.56%   |
| 2015    | 20       | 3.8%    |
| 2010    | 16       | 3.04%   |
| 2011    | 14       | 2.66%   |
| 2009    | 12       | 2.28%   |
| 2016    | 8        | 1.52%   |
| 2008    | 8        | 1.52%   |
| 2006    | 4        | 0.76%   |
| 2023    | 3        | 0.57%   |
| 2007    | 1        | 0.19%   |
| Unknown | 1        | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 526      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 474      | 89.77%  |
| Enabled  | 54       | 10.23%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 526      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 164      | 30.94%  |
| 32.01-64.0      | 141      | 26.6%   |
| 8.01-16.0       | 71       | 13.4%   |
| 64.01-256.0     | 52       | 9.81%   |
| 4.01-8.0        | 37       | 6.98%   |
| 24.01-32.0      | 35       | 6.6%    |
| 3.01-4.0        | 25       | 4.72%   |
| More than 256.0 | 2        | 0.38%   |
| 1.01-2.0        | 2        | 0.38%   |
| 2.01-3.0        | 1        | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 196      | 34.88%  |
| 3.01-4.0   | 123      | 21.89%  |
| 2.01-3.0   | 110      | 19.57%  |
| 8.01-16.0  | 59       | 10.5%   |
| 1.01-2.0   | 50       | 8.9%    |
| 0.51-1.0   | 12       | 2.14%   |
| 16.01-24.0 | 6        | 1.07%   |
| 32.01-64.0 | 2        | 0.36%   |
| 24.01-32.0 | 2        | 0.36%   |
| 0.01-0.5   | 2        | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 171      | 31.9%   |
| 1      | 140      | 26.12%  |
| 3      | 110      | 20.52%  |
| 4      | 60       | 11.19%  |
| 5      | 29       | 5.41%   |
| 6      | 11       | 2.05%   |
| 7      | 5        | 0.93%   |
| 8      | 3        | 0.56%   |
| 9      | 2        | 0.37%   |
| 18     | 1        | 0.19%   |
| 15     | 1        | 0.19%   |
| 12     | 1        | 0.19%   |
| 10     | 1        | 0.19%   |
| 0      | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 381      | 72.3%   |
| Yes       | 146      | 27.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 524      | 99.43%  |
| No        | 3        | 0.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 270      | 51.04%  |
| Yes       | 259      | 48.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 270      | 50.66%  |
| Yes       | 263      | 49.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 123      | 23.25%  |
| Brazil       | 42       | 7.94%   |
| Russia       | 38       | 7.18%   |
| Germany      | 37       | 6.99%   |
| UK           | 20       | 3.78%   |
| Poland       | 20       | 3.78%   |
| Italy        | 19       | 3.59%   |
| Australia    | 19       | 3.59%   |
| Spain        | 16       | 3.02%   |
| France       | 16       | 3.02%   |
| Canada       | 16       | 3.02%   |
| Netherlands  | 14       | 2.65%   |
| Sweden       | 10       | 1.89%   |
| Austria      | 9        | 1.7%    |
| Czechia      | 7        | 1.32%   |
| Vietnam      | 5        | 0.95%   |
| Turkey       | 5        | 0.95%   |
| Romania      | 5        | 0.95%   |
| Norway       | 5        | 0.95%   |
| New Zealand  | 5        | 0.95%   |
| Hungary      | 5        | 0.95%   |
| Finland      | 5        | 0.95%   |
| Colombia     | 5        | 0.95%   |
| Thailand     | 4        | 0.76%   |
| Switzerland  | 4        | 0.76%   |
| Portugal     | 4        | 0.76%   |
| Belgium      | 4        | 0.76%   |
| South Korea  | 3        | 0.57%   |
| Malaysia     | 3        | 0.57%   |
| Latvia       | 3        | 0.57%   |
| Israel       | 3        | 0.57%   |
| Indonesia    | 3        | 0.57%   |
| India        | 3        | 0.57%   |
| Greece       | 3        | 0.57%   |
| Belarus      | 3        | 0.57%   |
| South Africa | 2        | 0.38%   |
| Slovenia     | 2        | 0.38%   |
| Singapore    | 2        | 0.38%   |
| Serbia       | 2        | 0.38%   |
| Saudi Arabia | 2        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Sydney           | 13       | 2.4%    |
| Moscow           | 11       | 2.03%   |
| Warsaw           | 6        | 1.11%   |
| Berlin           | 6        | 1.11%   |
| Vienna           | 5        | 0.92%   |
| Sao Paulo        | 5        | 0.92%   |
| Palmas           | 5        | 0.92%   |
| London           | 5        | 0.92%   |
| Yekaterinburg    | 4        | 0.74%   |
| Budapest         | 4        | 0.74%   |
| Stockholm        | 3        | 0.55%   |
| Seattle          | 3        | 0.55%   |
| Riga             | 3        | 0.55%   |
| Porto Alegre     | 3        | 0.55%   |
| Ho Chi Minh City | 3        | 0.55%   |
| Helsinki         | 3        | 0.55%   |
| Hamburg          | 3        | 0.55%   |
| Belo Horizonte   | 3        | 0.55%   |
| Auckland         | 3        | 0.55%   |
| Atlanta          | 3        | 0.55%   |
| Volgograd        | 2        | 0.37%   |
| Vancouver        | 2        | 0.37%   |
| St Petersburg    | 2        | 0.37%   |
| Singapore        | 2        | 0.37%   |
| Saratov          | 2        | 0.37%   |
| Santa Clara      | 2        | 0.37%   |
| Rome             | 2        | 0.37%   |
| Rochester        | 2        | 0.37%   |
| Rio de Janeiro   | 2        | 0.37%   |
| Regina           | 2        | 0.37%   |
| Prague           | 2        | 0.37%   |
| Nal'chik         | 2        | 0.37%   |
| Munich           | 2        | 0.37%   |
| Minsk            | 2        | 0.37%   |
| Milan            | 2        | 0.37%   |
| Melbourne        | 2        | 0.37%   |
| Liberec          | 2        | 0.37%   |
| Leeds            | 2        | 0.37%   |
| Krasnodar        | 2        | 0.37%   |
| Kingston         | 2        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 216      | 361    | 20.04%  |
| WDC                         | 172      | 298    | 15.96%  |
| Seagate                     | 161      | 224    | 14.94%  |
| Kingston                    | 78       | 100    | 7.24%   |
| SanDisk                     | 73       | 98     | 6.77%   |
| Crucial                     | 61       | 79     | 5.66%   |
| Toshiba                     | 55       | 72     | 5.1%    |
| Phison Electronics          | 28       | 34     | 2.6%    |
| Intel                       | 18       | 25     | 1.67%   |
| Hitachi                     | 15       | 20     | 1.39%   |
| A-DATA Technology           | 14       | 14     | 1.3%    |
| Micron/Crucial Technology   | 13       | 16     | 1.21%   |
| China                       | 13       | 19     | 1.21%   |
| HGST                        | 10       | 22     | 0.93%   |
| Unknown                     | 8        | 12     | 0.74%   |
| Corsair                     | 8        | 12     | 0.74%   |
| Apacer                      | 8        | 12     | 0.74%   |
| SPCC                        | 7        | 10     | 0.65%   |
| SK hynix                    | 7        | 7      | 0.65%   |
| Realtek Semiconductor       | 7        | 7      | 0.65%   |
| Silicon Motion              | 6        | 7      | 0.56%   |
| PNY                         | 5        | 6      | 0.46%   |
| Kingston Technology Company | 5        | 5      | 0.46%   |
| ADATA Technology            | 5        | 5      | 0.46%   |
| Micron Technology           | 4        | 5      | 0.37%   |
| ASMT                        | 4        | 5      | 0.37%   |
| Plextor                     | 3        | 3      | 0.28%   |
| Netac                       | 3        | 3      | 0.28%   |
| JMicron Technology          | 3        | 3      | 0.28%   |
| Intenso                     | 3        | 3      | 0.28%   |
| HS-SSD-C100                 | 3        | 3      | 0.28%   |
| Transcend                   | 2        | 2      | 0.19%   |
| Team                        | 2        | 2      | 0.19%   |
| SABRENT                     | 2        | 2      | 0.19%   |
| Patriot                     | 2        | 2      | 0.19%   |
| Maxtor                      | 2        | 2      | 0.19%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.19%   |
| LT                          | 2        | 2      | 0.19%   |
| LITEON                      | 2        | 2      | 0.19%   |
| Lite-On Technology          | 2        | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 42       | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 23       | 1.83%   |
| Seagate ST2000DM008-2FR102 2TB                      | 22       | 1.75%   |
| Kingston SA400S37240G 240GB SSD                     | 19       | 1.51%   |
| Samsung SSD 850 EVO 250GB                           | 17       | 1.35%   |
| Phison E12 NVMe Controller 256GB                    | 14       | 1.11%   |
| Kingston SA400S37120G 120GB SSD                     | 14       | 1.11%   |
| Seagate ST1000DM010-2EP102 1TB                      | 13       | 1.03%   |
| Crucial CT1000MX500SSD1 1TB                         | 13       | 1.03%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 11       | 0.87%   |
| Seagate ST500DM002-1BD142 500GB                     | 11       | 0.87%   |
| Samsung SSD 870 EVO 500GB                           | 11       | 0.87%   |
| Samsung SSD 860 EVO 500GB                           | 11       | 0.87%   |
| Samsung SSD 850 EVO 500GB                           | 11       | 0.87%   |
| Kingston SA400S37480G 480GB SSD                     | 11       | 0.87%   |
| Toshiba DT01ACA200 2TB                              | 9        | 0.71%   |
| Samsung SSD 870 EVO 1TB                             | 9        | 0.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 8        | 0.63%   |
| Samsung SSD 870 QVO 2TB                             | 8        | 0.63%   |
| Samsung SSD 860 EVO 250GB                           | 8        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 8        | 0.63%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 8        | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB                      | 7        | 0.56%   |
| Samsung SSD 860 EVO 1TB                             | 7        | 0.56%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 7        | 0.56%   |
| Crucial CT500MX500SSD1 500GB                        | 7        | 0.56%   |
| Toshiba HDWD110 1TB                                 | 6        | 0.48%   |
| Toshiba DT01ACA100 1TB                              | 6        | 0.48%   |
| Seagate ST2000DM008-2UB102 2TB                      | 6        | 0.48%   |
| Seagate ST2000DM006-2DM164 2TB                      | 6        | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB                      | 6        | 0.48%   |
| Samsung SSD 980 PRO 1TB                             | 6        | 0.48%   |
| Samsung SSD 970 EVO Plus 2TB                        | 6        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6        | 0.48%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 5        | 0.4%    |
| WDC WD30EFRX-68EUZN0 3TB                            | 5        | 0.4%    |
| WDC WD10EZEX-60WN4A0 1TB                            | 5        | 0.4%    |
| Seagate ST4000DM004-2CV104 4TB                      | 5        | 0.4%    |
| Seagate ST31000528AS 1TB                            | 5        | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 5        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 159      | 220    | 40.36%  |
| WDC                 | 142      | 244    | 36.04%  |
| Toshiba             | 44       | 56     | 11.17%  |
| Hitachi             | 15       | 20     | 3.81%   |
| Samsung Electronics | 12       | 15     | 3.05%   |
| HGST                | 10       | 22     | 2.54%   |
| ASMT                | 3        | 4      | 0.76%   |
| Unknown             | 2        | 2      | 0.51%   |
| SABRENT             | 2        | 2      | 0.51%   |
| Maxtor              | 2        | 2      | 0.51%   |
| USB3.0              | 1        | 1      | 0.25%   |
| Intenso             | 1        | 1      | 0.25%   |
| IET                 | 1        | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 107      | 162    | 27.44%  |
| Kingston            | 59       | 72     | 15.13%  |
| Crucial             | 58       | 74     | 14.87%  |
| SanDisk             | 32       | 36     | 8.21%   |
| WDC                 | 27       | 34     | 6.92%   |
| China               | 13       | 19     | 3.33%   |
| A-DATA Technology   | 10       | 10     | 2.56%   |
| Intel               | 9        | 12     | 2.31%   |
| Toshiba             | 7        | 8      | 1.79%   |
| Apacer              | 6        | 9      | 1.54%   |
| PNY                 | 5        | 6      | 1.28%   |
| Corsair             | 5        | 7      | 1.28%   |
| SPCC                | 4        | 6      | 1.03%   |
| Plextor             | 3        | 3      | 0.77%   |
| Unknown             | 2        | 2      | 0.51%   |
| Transcend           | 2        | 2      | 0.51%   |
| SK hynix            | 2        | 2      | 0.51%   |
| Patriot             | 2        | 2      | 0.51%   |
| LT                  | 2        | 2      | 0.51%   |
| LITEON              | 2        | 2      | 0.51%   |
| Lexar               | 2        | 3      | 0.51%   |
| KingSpec            | 2        | 2      | 0.51%   |
| KingDian            | 2        | 2      | 0.51%   |
| GOODRAM             | 2        | 3      | 0.51%   |
| XSTAR               | 1        | 1      | 0.26%   |
| VSP                 | 1        | 1      | 0.26%   |
| Vaseky              | 1        | 1      | 0.26%   |
| Team                | 1        | 1      | 0.26%   |
| Super Talent        | 1        | 1      | 0.26%   |
| Seagate             | 1        | 1      | 0.26%   |
| OWC                 | 1        | 1      | 0.26%   |
| OCZ                 | 1        | 1      | 0.26%   |
| Netac               | 1        | 1      | 0.26%   |
| Mushkin             | 1        | 1      | 0.26%   |
| Micron Technology   | 1        | 2      | 0.26%   |
| Mercury             | 1        | 1      | 0.26%   |
| LITEONIT            | 1        | 1      | 0.26%   |
| Lenovo              | 1        | 1      | 0.26%   |
| KUIJIA              | 1        | 1      | 0.26%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 322      | 508    | 34.51%  |
| HDD     | 306      | 590    | 32.8%   |
| NVMe    | 287      | 436    | 30.76%  |
| Unknown | 18       | 23     | 1.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 435      | 1063   | 56.86%  |
| NVMe | 287      | 435    | 37.52%  |
| SAS  | 43       | 59     | 5.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 292      | 470    | 42.26%  |
| 0.51-1.0   | 206      | 316    | 29.81%  |
| 1.01-2.0   | 102      | 137    | 14.76%  |
| 3.01-4.0   | 35       | 59     | 5.07%   |
| 4.01-10.0  | 28       | 46     | 4.05%   |
| 2.01-3.0   | 24       | 47     | 3.47%   |
| 10.01-20.0 | 4        | 23     | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 101      | 18.84%  |
| 501-1000       | 98       | 18.28%  |
| More than 3000 | 94       | 17.54%  |
| 251-500        | 64       | 11.94%  |
| 2001-3000      | 56       | 10.45%  |
| 101-250        | 50       | 9.33%   |
| Unknown        | 30       | 5.6%    |
| 1-20           | 25       | 4.66%   |
| 51-100         | 13       | 2.43%   |
| 21-50          | 5        | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 93       | 16.82%  |
| 501-1000       | 86       | 15.55%  |
| 101-250        | 66       | 11.93%  |
| 21-50          | 64       | 11.57%  |
| 251-500        | 60       | 10.85%  |
| 1001-2000      | 59       | 10.67%  |
| 51-100         | 47       | 8.5%    |
| Unknown        | 30       | 5.42%   |
| More than 3000 | 27       | 4.88%   |
| 2001-3000      | 21       | 3.8%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB   | 4        | 4      | 5.13%   |
| WDC WD5000AAKX-603CA0 500GB           | 2        | 2      | 2.56%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2        | 2      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 2.56%   |
| Intel SSDSC2CT120A3 120GB             | 2        | 5      | 2.56%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 1.28%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1        | 1      | 1.28%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 1      | 1.28%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 1.28%   |
| WDC WD40PURZ-85AKKY0 4TB              | 1        | 1      | 1.28%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1        | 1      | 1.28%   |
| WDC WD3200BPVT-80JJ5T0 320GB          | 1        | 1      | 1.28%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1        | 1      | 1.28%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1        | 1      | 1.28%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 1      | 1.28%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1        | 1      | 1.28%   |
| WDC WD20EZRX-22D8PB0 2TB              | 1        | 1      | 1.28%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 1      | 1.28%   |
| WDC WD15EARS-00MVWB0 1TB              | 1        | 1      | 1.28%   |
| WDC WD140EDFZ-11A0VA0 14TB            | 1        | 2      | 1.28%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1        | 2      | 1.28%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.28%   |
| WDC WD10EZEX-00WN4A0 1TB              | 1        | 1      | 1.28%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 1      | 1.28%   |
| WDC WD10EADS-00L5B1 1TB               | 1        | 1      | 1.28%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1        | 1      | 1.28%   |
| Toshiba MQ01ABD050 500GB              | 1        | 1      | 1.28%   |
| Toshiba MK7559GSXP 752GB              | 1        | 1      | 1.28%   |
| Toshiba MK3263GSX 320GB               | 1        | 1      | 1.28%   |
| SPCC SPCCSolidStateDisk 128GB SSD     | 1        | 1      | 1.28%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1        | 1      | 1.28%   |
| Seagate ST8000NE001-2M7101 8TB        | 1        | 1      | 1.28%   |
| Seagate ST6000DM003-2CY186 6TB        | 1        | 1      | 1.28%   |
| Seagate ST500LM021-1KJ152 500GB       | 1        | 2      | 1.28%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 1.28%   |
| Seagate ST3500320AS 500GB             | 1        | 1      | 1.28%   |
| Seagate ST3320620AS 320GB             | 1        | 2      | 1.28%   |
| Seagate ST32000641AS 2TB              | 1        | 1      | 1.28%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 1.28%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 1.28%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 27     | 31.94%  |
| Seagate             | 19       | 29     | 26.39%  |
| Samsung Electronics | 9        | 13     | 12.5%   |
| Crucial             | 4        | 4      | 5.56%   |
| Toshiba             | 3        | 3      | 4.17%   |
| Intel               | 3        | 6      | 4.17%   |
| Hitachi             | 2        | 2      | 2.78%   |
| Corsair             | 2        | 2      | 2.78%   |
| SPCC                | 1        | 1      | 1.39%   |
| SK hynix            | 1        | 1      | 1.39%   |
| SanDisk             | 1        | 1      | 1.39%   |
| Maxtor              | 1        | 1      | 1.39%   |
| Kingston            | 1        | 1      | 1.39%   |
| AMD                 | 1        | 2      | 1.39%   |
| A-DATA Technology   | 1        | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 26     | 42.31%  |
| Seagate             | 19       | 29     | 36.54%  |
| Samsung Electronics | 5        | 8      | 9.62%   |
| Toshiba             | 3        | 3      | 5.77%   |
| Hitachi             | 2        | 2      | 3.85%   |
| Maxtor              | 1        | 1      | 1.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 46       | 69     | 69.7%   |
| SSD  | 20       | 25     | 30.3%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| SPCC M.2 PCIe SSD 2TB    | 1        | 1      | 50%     |
| Seagate ST31000528AS 1TB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SPCC    | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 335      | 915    | 55.19%  |
| Works    | 209      | 546    | 34.43%  |
| Malfunc  | 61       | 94     | 10.05%  |
| Failed   | 2        | 2      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 281      | 30.95%  |
| AMD                            | 236      | 25.99%  |
| Samsung Electronics            | 128      | 14.1%   |
| SanDisk                        | 57       | 6.28%   |
| ASMedia Technology             | 37       | 4.07%   |
| Phison Electronics             | 36       | 3.96%   |
| Kingston Technology Company    | 29       | 3.19%   |
| Micron/Crucial Technology      | 16       | 1.76%   |
| Marvell Technology Group       | 16       | 1.76%   |
| Silicon Motion                 | 9        | 0.99%   |
| ADATA Technology               | 9        | 0.99%   |
| Realtek Semiconductor          | 8        | 0.88%   |
| SK hynix                       | 5        | 0.55%   |
| Nvidia                         | 5        | 0.55%   |
| JMicron Technology             | 5        | 0.55%   |
| Toshiba America Info Systems   | 4        | 0.44%   |
| MAXIO Technology (Hangzhou)    | 4        | 0.44%   |
| Broadcom / LSI                 | 4        | 0.44%   |
| Micron Technology              | 3        | 0.33%   |
| VIA Technologies               | 2        | 0.22%   |
| LSI Logic / Symbios Logic      | 2        | 0.22%   |
| Lite-On Technology             | 2        | 0.22%   |
| ULi Electronics                | 1        | 0.11%   |
| Solidigm                       | 1        | 0.11%   |
| Solid State Storage Technology | 1        | 0.11%   |
| Silicon Image                  | 1        | 0.11%   |
| Shenzhen Longsys Electronics   | 1        | 0.11%   |
| Seagate Technology             | 1        | 0.11%   |
| Netac Technology               | 1        | 0.11%   |
| KIOXIA                         | 1        | 0.11%   |
| Biwin Storage Technology       | 1        | 0.11%   |
| Adaptec                        | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 138      | 13.12%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 71       | 6.75%   |
| AMD 400 Series Chipset SATA Controller                                         | 54       | 5.13%   |
| AMD 500 Series Chipset SATA Controller                                         | 50       | 4.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 40       | 3.8%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 35       | 3.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 29       | 2.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 27       | 2.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 26       | 2.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 24       | 2.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 23       | 2.19%   |
| Phison E12 NVMe Controller                                                     | 19       | 1.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 19       | 1.81%   |
| Intel SATA Controller [RAID mode]                                              | 17       | 1.62%   |
| Intel Volume Management Device NVMe RAID Controller                            | 15       | 1.43%   |
| Kingston Company Company Non-Volatile memory controller                        | 14       | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 13       | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12       | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12       | 1.14%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 11       | 1.05%   |
| AMD 300 Series Chipset SATA Controller                                         | 11       | 1.05%   |
| Samsung NVMe SSD Controller 980                                                | 10       | 0.95%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 10       | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10       | 0.95%   |
| AMD FCH SATA Controller D                                                      | 10       | 0.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9        | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9        | 0.86%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 9        | 0.86%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 9        | 0.86%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 8        | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                               | 8        | 0.76%   |
| Kingston Company A2000 NVMe SSD                                                | 8        | 0.76%   |
| AMD X370 Series Chipset SATA Controller                                        | 8        | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 7        | 0.67%   |
| SanDisk Non-Volatile memory controller                                         | 7        | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7        | 0.67%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 7        | 0.67%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 6        | 0.57%   |
| Phison PS5013 E13 NVMe Controller                                              | 6        | 0.57%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 6        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 469      | 54.41%  |
| NVMe | 286      | 33.18%  |
| IDE  | 54       | 6.26%   |
| RAID | 43       | 4.99%   |
| SAS  | 9        | 1.04%   |
| SCSI | 1        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 279      | 53.04%  |
| AMD    | 247      | 46.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 23       | 4.37%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 18       | 3.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 14       | 2.66%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 13       | 2.47%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 13       | 2.47%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 11       | 2.09%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 11       | 2.09%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 10       | 1.9%    |
| AMD Ryzen 7 5800X 8-Core Processor     | 9        | 1.71%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 8        | 1.52%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 8        | 1.52%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 8        | 1.52%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 7        | 1.33%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 6        | 1.14%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 6        | 1.14%   |
| AMD Ryzen 7 5800X3D 8-Core Processor   | 6        | 1.14%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 5        | 0.95%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 5        | 0.95%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 5        | 0.95%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 5        | 0.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 5        | 0.95%   |
| Intel 12th Gen Core i9-12900K          | 5        | 0.95%   |
| Intel 12th Gen Core i7-12700           | 5        | 0.95%   |
| AMD Ryzen 7 3800X 8-Core Processor     | 5        | 0.95%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 5        | 0.95%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 5        | 0.95%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 4        | 0.76%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 4        | 0.76%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 4        | 0.76%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 4        | 0.76%   |
| Intel Core i5-10400 CPU @ 2.90GHz      | 4        | 0.76%   |
| Intel 12th Gen Core i7-12700K          | 4        | 0.76%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 4        | 0.76%   |
| AMD Ryzen 5 3500X 6-Core Processor     | 4        | 0.76%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz    | 3        | 0.57%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 0.57%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 3        | 0.57%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 3        | 0.57%   |
| Intel Core i5-8600K CPU @ 3.60GHz      | 3        | 0.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 97       | 18.44%  |
| Intel Core i7           | 87       | 16.54%  |
| Intel Core i5           | 67       | 12.74%  |
| AMD Ryzen 7             | 60       | 11.41%  |
| AMD Ryzen 9             | 42       | 7.98%   |
| Other                   | 40       | 7.6%    |
| Intel Xeon              | 25       | 4.75%   |
| Intel Core i3           | 23       | 4.37%   |
| AMD FX                  | 11       | 2.09%   |
| Intel Core 2 Quad       | 7        | 1.33%   |
| Intel Core i9           | 6        | 1.14%   |
| Intel Pentium           | 5        | 0.95%   |
| AMD Ryzen 3             | 5        | 0.95%   |
| Intel Pentium Dual-Core | 4        | 0.76%   |
| Intel Core 2 Duo        | 4        | 0.76%   |
| Intel Celeron           | 4        | 0.76%   |
| AMD Ryzen Threadripper  | 4        | 0.76%   |
| AMD A6                  | 4        | 0.76%   |
| Intel Atom              | 3        | 0.57%   |
| AMD Phenom II X6        | 3        | 0.57%   |
| AMD A8                  | 3        | 0.57%   |
| AMD A4                  | 3        | 0.57%   |
| AMD A10                 | 3        | 0.57%   |
| Intel Pentium Gold      | 2        | 0.38%   |
| AMD Ryzen 5 PRO         | 2        | 0.38%   |
| AMD Phenom II X4        | 2        | 0.38%   |
| AMD Athlon 64 X2        | 2        | 0.38%   |
| Intel Pentium Dual      | 1        | 0.19%   |
| Intel Genuine           | 1        | 0.19%   |
| AMD Ryzen 3 PRO         | 1        | 0.19%   |
| AMD PRO A10             | 1        | 0.19%   |
| AMD Phenom II X2        | 1        | 0.19%   |
| AMD Athlon II X4        | 1        | 0.19%   |
| AMD Athlon II X2        | 1        | 0.19%   |
| AMD Athlon              | 1        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 154      | 29.28%  |
| 6      | 139      | 26.43%  |
| 8      | 91       | 17.3%   |
| 2      | 54       | 10.27%  |
| 16     | 32       | 6.08%   |
| 12     | 32       | 6.08%   |
| 10     | 9        | 1.71%   |
| 24     | 5        | 0.95%   |
| 3      | 4        | 0.76%   |
| 1      | 3        | 0.57%   |
| 14     | 2        | 0.38%   |
| 32     | 1        | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 519      | 98.67%  |
| 2      | 7        | 1.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 399      | 75.86%  |
| 1      | 127      | 24.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 526      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 49       | 9.14%   |
| Unknown    | 41       | 7.65%   |
| 0x306c3    | 33       | 6.16%   |
| 0x306a9    | 29       | 5.41%   |
| 0x506e3    | 23       | 4.29%   |
| 0x906ea    | 22       | 4.1%    |
| 0x0a601203 | 19       | 3.54%   |
| 0x0a50000d | 19       | 3.54%   |
| 0x90672    | 18       | 3.36%   |
| 0x0a201016 | 18       | 3.36%   |
| 0x206a7    | 14       | 2.61%   |
| 0x0a20120a | 14       | 2.61%   |
| 0x0a50000c | 12       | 2.24%   |
| 0x906ed    | 11       | 2.05%   |
| 0x906e9    | 11       | 2.05%   |
| 0x206d7    | 11       | 2.05%   |
| 0x08701013 | 10       | 1.87%   |
| 0x0800820d | 10       | 1.87%   |
| 0xa0655    | 9        | 1.68%   |
| 0xa0653    | 9        | 1.68%   |
| 0x1067a    | 9        | 1.68%   |
| 0x306f2    | 7        | 1.31%   |
| 0x08001138 | 7        | 1.31%   |
| 0x90675    | 6        | 1.12%   |
| 0x0a201205 | 6        | 1.12%   |
| 0x0a201009 | 6        | 1.12%   |
| 0x06000822 | 6        | 1.12%   |
| 0xb0671    | 5        | 0.93%   |
| 0xa0671    | 5        | 0.93%   |
| 0x0a50000b | 5        | 0.93%   |
| 0x0a601201 | 4        | 0.75%   |
| 0x08108109 | 4        | 0.75%   |
| 0x08101016 | 4        | 0.75%   |
| 0x06001119 | 4        | 0.75%   |
| 0x906ec    | 3        | 0.56%   |
| 0x6fd      | 3        | 0.56%   |
| 0x6fb      | 3        | 0.56%   |
| 0x106e5    | 3        | 0.56%   |
| 0x08001137 | 3        | 0.56%   |
| 0x906eb    | 2        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 84       | 15.97%  |
| Zen 2            | 66       | 12.55%  |
| KabyLake         | 55       | 10.46%  |
| Haswell          | 43       | 8.17%   |
| IvyBridge        | 33       | 6.27%   |
| Alderlake Hybrid | 33       | 6.27%   |
| Unknown          | 28       | 5.32%   |
| Skylake          | 26       | 4.94%   |
| SandyBridge      | 26       | 4.94%   |
| Zen              | 18       | 3.42%   |
| CometLake        | 18       | 3.42%   |
| Zen+             | 17       | 3.23%   |
| Piledriver       | 14       | 2.66%   |
| Penryn           | 12       | 2.28%   |
| K10              | 7        | 1.33%   |
| Icelake          | 6        | 1.14%   |
| Core             | 6        | 1.14%   |
| Westmere         | 5        | 0.95%   |
| Nehalem          | 5        | 0.95%   |
| Excavator        | 4        | 0.76%   |
| Bonnell          | 4        | 0.76%   |
| Steamroller      | 2        | 0.38%   |
| Silvermont       | 2        | 0.38%   |
| K8 Hammer        | 2        | 0.38%   |
| Jaguar           | 2        | 0.38%   |
| Bulldozer        | 2        | 0.38%   |
| Broadwell        | 2        | 0.38%   |
| Tremont          | 1        | 0.19%   |
| Puma             | 1        | 0.19%   |
| K10 Llano        | 1        | 0.19%   |
| Goldmont plus    | 1        | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| AMD               | 236      | 41.4%   |
| Nvidia            | 230      | 40.35%  |
| Intel             | 101      | 17.72%  |
| ASPEED Technology | 3        | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 45       | 7.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 25       | 4.19%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 24       | 4.03%   |
| AMD Raphael                                                                 | 23       | 3.86%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 22       | 3.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 2.01%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 12       | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 10       | 1.68%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 10       | 1.68%   |
| Intel AlderLake-S GT1                                                       | 9        | 1.51%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9        | 1.51%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 8        | 1.34%   |
| Intel HD Graphics 530                                                       | 8        | 1.34%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 7        | 1.17%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.17%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 7        | 1.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 1.17%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 1.01%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 1.01%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 1.01%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 1.01%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.01%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.01%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 6        | 1.01%   |
| Intel HD Graphics 630                                                       | 6        | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 1.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.01%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 0.84%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 0.84%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 5        | 0.84%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 5        | 0.84%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 4        | 0.67%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 4        | 0.67%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 4        | 0.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 0.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 199      | 37.69%  |
| 1 x AMD                  | 199      | 37.69%  |
| 1 x Intel                | 74       | 14.02%  |
| 2 x AMD                  | 18       | 3.41%   |
| AMD + Nvidia             | 14       | 2.65%   |
| Intel + Nvidia           | 12       | 2.27%   |
| 2 x Intel                | 3        | 0.57%   |
| 2 x Nvidia               | 2        | 0.38%   |
| Intel + AMD              | 2        | 0.38%   |
| 3 x AMD                  | 1        | 0.19%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.19%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.19%   |
| 1 x ASPEED               | 1        | 0.19%   |
| AMD + ASPEED             | 1        | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 381      | 71.75%  |
| Proprietary | 132      | 24.86%  |
| Unknown     | 18       | 3.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 151      | 28.07%  |
| 7.01-8.0   | 115      | 21.38%  |
| 1.01-2.0   | 55       | 10.22%  |
| 3.01-4.0   | 54       | 10.04%  |
| 8.01-16.0  | 49       | 9.11%   |
| 0.51-1.0   | 41       | 7.62%   |
| 0.01-0.5   | 36       | 6.69%   |
| 5.01-6.0   | 24       | 4.46%   |
| 16.01-24.0 | 7        | 1.3%    |
| 2.01-3.0   | 6        | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 93       | 15.2%   |
| Dell                 | 86       | 14.05%  |
| Goldstar             | 75       | 12.25%  |
| Hewlett-Packard      | 47       | 7.68%   |
| AOC                  | 40       | 6.54%   |
| Acer                 | 36       | 5.88%   |
| BenQ                 | 30       | 4.9%    |
| Ancor Communications | 23       | 3.76%   |
| ASUSTek Computer     | 22       | 3.59%   |
| Philips              | 21       | 3.43%   |
| Lenovo               | 19       | 3.1%    |
| ViewSonic            | 10       | 1.63%   |
| Gigabyte Technology  | 10       | 1.63%   |
| Sceptre Tech         | 9        | 1.47%   |
| Iiyama               | 9        | 1.47%   |
| MSI                  | 8        | 1.31%   |
| Unknown              | 5        | 0.82%   |
| Sony                 | 5        | 0.82%   |
| Eizo                 | 5        | 0.82%   |
| NEC Computers        | 4        | 0.65%   |
| Mi                   | 4        | 0.65%   |
| Vizio                | 3        | 0.49%   |
| Pixio                | 3        | 0.49%   |
| HannStar             | 3        | 0.49%   |
| ONN                  | 2        | 0.33%   |
| Hitachi              | 2        | 0.33%   |
| FPT                  | 2        | 0.33%   |
| Belinea              | 2        | 0.33%   |
| Unknown              | 2        | 0.33%   |
| Westinghouse         | 1        | 0.16%   |
| USR                  | 1        | 0.16%   |
| Unknown (XXX)        | 1        | 0.16%   |
| RTK                  | 1        | 0.16%   |
| Positivo             | 1        | 0.16%   |
| Panasonic            | 1        | 0.16%   |
| NCS                  | 1        | 0.16%   |
| MStar                | 1        | 0.16%   |
| Microstep            | 1        | 0.16%   |
| Medion Akoya         | 1        | 0.16%   |
| Medion               | 1        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                       | 8        | 1.22%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 5        | 0.76%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 5        | 0.76%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5        | 0.76%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 4        | 0.61%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 4        | 0.61%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 4        | 0.61%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3        | 0.46%   |
| Samsung Electronics C34H89x SAM0E25 3440x1440 797x333mm 34.0-inch      | 3        | 0.46%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 0.46%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 3        | 0.46%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                   | 3        | 0.46%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch               | 3        | 0.46%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch             | 3        | 0.46%   |
| Goldstar ULTRAGEAR GSM774B 3440x1440 800x335mm 34.1-inch               | 3        | 0.46%   |
| Goldstar ULTRAGEAR GSM5B71 1920x1080 597x336mm 27.0-inch               | 3        | 0.46%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                  | 3        | 0.46%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                  | 3        | 0.46%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                      | 3        | 0.46%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 3        | 0.46%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 3        | 0.46%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 597x336mm 27.0-inch         | 2        | 0.3%    |
| Sceptre Tech E24 SPT099D 1920x1080 409x230mm 18.5-inch                 | 2        | 0.3%    |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch      | 2        | 0.3%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 2        | 0.3%    |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 597x336mm 27.0-inch | 2        | 0.3%    |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 2        | 0.3%    |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch     | 2        | 0.3%    |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 2        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2        | 0.3%    |
| Philips PHL 328E9Q PHLC180 1920x1080 698x393mm 31.5-inch               | 2        | 0.3%    |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2        | 0.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2        | 0.3%    |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch               | 2        | 0.3%    |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 2        | 0.3%    |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                   | 2        | 0.3%    |
| Iiyama PL2760Q IVM663D 2560x1440 597x336mm 27.0-inch                   | 2        | 0.3%    |
| Hewlett-Packard ZR2440w HWP2956 1920x1080 518x324mm 24.1-inch          | 2        | 0.3%    |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch           | 2        | 0.3%    |
| Hewlett-Packard LA2006 HWP2944 1600x900 443x249mm 20.0-inch            | 2        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 241      | 41.48%  |
| 3840x2160 (4K)     | 90       | 15.49%  |
| 2560x1440 (QHD)    | 88       | 15.15%  |
| 3440x1440          | 36       | 6.2%    |
| 1280x1024 (SXGA)   | 18       | 3.1%    |
| 1680x1050 (WSXGA+) | 16       | 2.75%   |
| 1366x768 (WXGA)    | 14       | 2.41%   |
| 2560x1080          | 13       | 2.24%   |
| 1600x900 (HD+)     | 13       | 2.24%   |
| 1920x1200 (WUXGA)  | 11       | 1.89%   |
| 1440x900 (WXGA+)   | 10       | 1.72%   |
| 3840x1080          | 5        | 0.86%   |
| 2288x1287          | 5        | 0.86%   |
| 1360x768           | 4        | 0.69%   |
| Unknown            | 4        | 0.69%   |
| 2560x1600          | 3        | 0.52%   |
| 1600x1200          | 3        | 0.52%   |
| 4160x1440          | 1        | 0.17%   |
| 3840x1600          | 1        | 0.17%   |
| 3200x1080          | 1        | 0.17%   |
| 3120x1600          | 1        | 0.17%   |
| 2560x2880          | 1        | 0.17%   |
| 2160x1200          | 1        | 0.17%   |
| 1920x540           | 1        | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 134      | 21.65%  |
| 24      | 104      | 16.8%   |
| 23      | 76       | 12.28%  |
| 31      | 50       | 8.08%   |
| 21      | 48       | 7.75%   |
| 34      | 40       | 6.46%   |
| 19      | 20       | 3.23%   |
| Unknown | 15       | 2.42%   |
| 20      | 14       | 2.26%   |
| 22      | 13       | 2.1%    |
| 18      | 13       | 2.1%    |
| 25      | 11       | 1.78%   |
| 32      | 8        | 1.29%   |
| 84      | 7        | 1.13%   |
| 48      | 7        | 1.13%   |
| 26      | 6        | 0.97%   |
| 142     | 5        | 0.81%   |
| 29      | 5        | 0.81%   |
| 40      | 4        | 0.65%   |
| 17      | 4        | 0.65%   |
| 72      | 3        | 0.48%   |
| 54      | 3        | 0.48%   |
| 42      | 3        | 0.48%   |
| 39      | 3        | 0.48%   |
| 36      | 3        | 0.48%   |
| 35      | 3        | 0.48%   |
| 28      | 3        | 0.48%   |
| 65      | 2        | 0.32%   |
| 52      | 2        | 0.32%   |
| 43      | 2        | 0.32%   |
| 15      | 2        | 0.32%   |
| 69      | 1        | 0.16%   |
| 44      | 1        | 0.16%   |
| 38      | 1        | 0.16%   |
| 37      | 1        | 0.16%   |
| 33      | 1        | 0.16%   |
| 12      | 1        | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 285      | 48.8%   |
| 401-500        | 95       | 16.27%  |
| 601-700        | 70       | 11.99%  |
| 701-800        | 51       | 8.73%   |
| Unknown        | 15       | 2.57%   |
| 1001-1500      | 14       | 2.4%    |
| 351-400        | 12       | 2.05%   |
| 801-900        | 11       | 1.88%   |
| 1501-2000      | 11       | 1.88%   |
| 901-1000       | 8        | 1.37%   |
| 301-350        | 6        | 1.03%   |
| More than 2000 | 5        | 0.86%   |
| 201-300        | 1        | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 393      | 73.87%  |
| 21/9    | 48       | 9.02%   |
| 16/10   | 48       | 9.02%   |
| 5/4     | 16       | 3.01%   |
| Unknown | 11       | 2.07%   |
| 4/3     | 5        | 0.94%   |
| 1.00    | 5        | 0.94%   |
| 32/9    | 4        | 0.75%   |
| 1.96    | 1        | 0.19%   |
| 0.89    | 1        | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 185      | 30.48%  |
| 301-350        | 137      | 22.57%  |
| 351-500        | 105      | 17.3%   |
| 151-200        | 52       | 8.57%   |
| 251-300        | 48       | 7.91%   |
| More than 1000 | 25       | 4.12%   |
| 501-1000       | 23       | 3.79%   |
| Unknown        | 15       | 2.47%   |
| 141-150        | 14       | 2.31%   |
| 101-110        | 2        | 0.33%   |
| 71-80          | 1        | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 306      | 55.04%  |
| 101-120 | 145      | 26.08%  |
| 121-160 | 45       | 8.09%   |
| 1-50    | 23       | 4.14%   |
| 161-240 | 22       | 3.96%   |
| Unknown | 15       | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 354      | 66.54%  |
| 2     | 136      | 25.56%  |
| 0     | 23       | 4.32%   |
| 3     | 17       | 3.2%    |
| 4     | 2        | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 314      | 40.05%  |
| Intel                           | 286      | 36.48%  |
| MediaTek                        | 33       | 4.21%   |
| Qualcomm Atheros                | 30       | 3.83%   |
| Broadcom                        | 23       | 2.93%   |
| TP-Link                         | 19       | 2.42%   |
| Aquantia                        | 11       | 1.4%    |
| Ralink Technology               | 9        | 1.15%   |
| Ralink                          | 7        | 0.89%   |
| Microsoft                       | 6        | 0.77%   |
| D-Link                          | 5        | 0.64%   |
| Nvidia                          | 4        | 0.51%   |
| Google                          | 4        | 0.51%   |
| Xiaomi                          | 3        | 0.38%   |
| Samsung Electronics             | 2        | 0.26%   |
| Qualcomm Atheros Communications | 2        | 0.26%   |
| NetGear                         | 2        | 0.26%   |
| Mellanox Technologies           | 2        | 0.26%   |
| Marvell Technology Group        | 2        | 0.26%   |
| InterBiometrics                 | 2        | 0.26%   |
| Huawei Technologies             | 2        | 0.26%   |
| Zoom Telephonics                | 1        | 0.13%   |
| Qualcomm                        | 1        | 0.13%   |
| QinHeng Electronics             | 1        | 0.13%   |
| OPPO Electronics                | 1        | 0.13%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.13%   |
| Motorola PCS                    | 1        | 0.13%   |
| Microchip Technology            | 1        | 0.13%   |
| ICS Advent                      | 1        | 0.13%   |
| Conexant Systems                | 1        | 0.13%   |
| Broadcom Limited                | 1        | 0.13%   |
| Bose                            | 1        | 0.13%   |
| ASIX Electronics                | 1        | 0.13%   |
| Arduino SA                      | 1        | 0.13%   |
| American Megatrends             | 1        | 0.13%   |
| Adafruit                        | 1        | 0.13%   |
| AboCom Systems                  | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 227      | 25.36%  |
| Realtek RTL8125 2.5GbE Controller                                   | 65       | 7.26%   |
| Intel Wi-Fi 6 AX200                                                 | 54       | 6.03%   |
| Intel I211 Gigabit Network Connection                               | 46       | 5.14%   |
| Intel Ethernet Controller I225-V                                    | 39       | 4.36%   |
| Intel Ethernet Connection (2) I219-V                                | 32       | 3.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 21       | 2.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 18       | 2.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 18       | 2.01%   |
| Intel Wireless-AC 9260                                              | 13       | 1.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 12       | 1.34%   |
| Intel Ethernet Connection (7) I219-V                                | 12       | 1.34%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 12       | 1.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 9        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 8        | 0.89%   |
| Intel Ethernet Connection (2) I218-V                                | 8        | 0.89%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 8        | 0.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7        | 0.78%   |
| Intel 82579V Gigabit Network Connection                             | 7        | 0.78%   |
| Intel 82574L Gigabit Network Connection                             | 7        | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 6        | 0.67%   |
| Intel Ethernet Connection I217-LM                                   | 6        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                               | 5        | 0.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 4        | 0.45%   |
| Realtek 802.11ac NIC                                                | 4        | 0.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 4        | 0.45%   |
| Intel Wireless 7265                                                 | 4        | 0.45%   |
| Intel Ethernet Connection I217-V                                    | 4        | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 0.45%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 4        | 0.45%   |
| Intel 700 Series Chipset Family Wi-Fi                               | 4        | 0.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 4        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 3        | 0.34%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 3        | 0.34%   |
| TP-Link 802.11ac NIC                                                | 3        | 0.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 3        | 0.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 3        | 0.34%   |
| Ralink MT7601U Wireless Adapter                                     | 3        | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 0.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 127      | 46.35%  |
| Realtek Semiconductor           | 36       | 13.14%  |
| MediaTek                        | 33       | 12.04%  |
| TP-Link                         | 18       | 6.57%   |
| Qualcomm Atheros                | 18       | 6.57%   |
| Broadcom                        | 11       | 4.01%   |
| Ralink Technology               | 9        | 3.28%   |
| Ralink                          | 7        | 2.55%   |
| Microsoft                       | 6        | 2.19%   |
| D-Link                          | 3        | 1.09%   |
| Qualcomm Atheros Communications | 2        | 0.73%   |
| NetGear                         | 2        | 0.73%   |
| Broadcom Limited                | 1        | 0.36%   |
| AboCom Systems                  | 1        | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 54       | 19.57%  |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 18       | 6.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 18       | 6.52%   |
| Intel Wireless-AC 9260                                        | 13       | 4.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 12       | 4.35%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 12       | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 9        | 3.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 6        | 2.17%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 4        | 1.45%   |
| Realtek 802.11ac NIC                                          | 4        | 1.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 4        | 1.45%   |
| Intel Wireless 7265                                           | 4        | 1.45%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 4        | 1.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 4        | 1.45%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 3        | 1.09%   |
| TP-Link 802.11ac NIC                                          | 3        | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3        | 1.09%   |
| Ralink MT7601U Wireless Adapter                               | 3        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 3        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3        | 1.09%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2        | 0.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 2        | 0.72%   |
| TP-Link Archer T4U ver.3                                      | 2        | 0.72%   |
| TP-Link 802.11ac WLAN Adapter                                 | 2        | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 0.72%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 2        | 0.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 2        | 0.72%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 2        | 0.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2        | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2        | 0.72%   |
| Ralink RT5370 Wireless Adapter                                | 2        | 0.72%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 2        | 0.72%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                     | 2        | 0.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 2        | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2        | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                               | 2        | 0.72%   |
| Microsoft XBOX ACC                                            | 2        | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                           | 2        | 0.72%   |
| Microsoft Wireless XBox Controller Dongle                     | 2        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 299      | 51.37%  |
| Intel                         | 219      | 37.63%  |
| Qualcomm Atheros              | 13       | 2.23%   |
| Broadcom                      | 12       | 2.06%   |
| Aquantia                      | 11       | 1.89%   |
| Nvidia                        | 4        | 0.69%   |
| Google                        | 4        | 0.69%   |
| Xiaomi                        | 3        | 0.52%   |
| Samsung Electronics           | 2        | 0.34%   |
| Mellanox Technologies         | 2        | 0.34%   |
| Marvell Technology Group      | 2        | 0.34%   |
| D-Link                        | 2        | 0.34%   |
| TP-Link                       | 1        | 0.17%   |
| Qualcomm                      | 1        | 0.17%   |
| OPPO Electronics              | 1        | 0.17%   |
| OnePlus Technology (Shenzhen) | 1        | 0.17%   |
| Motorola PCS                  | 1        | 0.17%   |
| ICS Advent                    | 1        | 0.17%   |
| Huawei Technologies           | 1        | 0.17%   |
| ASIX Electronics              | 1        | 0.17%   |
| American Megatrends           | 1        | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 227      | 37.27%  |
| Realtek RTL8125 2.5GbE Controller                                   | 65       | 10.67%  |
| Intel I211 Gigabit Network Connection                               | 46       | 7.55%   |
| Intel Ethernet Controller I225-V                                    | 39       | 6.4%    |
| Intel Ethernet Connection (2) I219-V                                | 32       | 5.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 21       | 3.45%   |
| Intel Ethernet Connection (7) I219-V                                | 12       | 1.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 8        | 1.31%   |
| Intel Ethernet Connection (2) I218-V                                | 8        | 1.31%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 8        | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7        | 1.15%   |
| Intel 82579V Gigabit Network Connection                             | 7        | 1.15%   |
| Intel 82574L Gigabit Network Connection                             | 7        | 1.15%   |
| Intel Ethernet Connection I217-LM                                   | 6        | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                               | 5        | 0.82%   |
| Intel Ethernet Connection I217-V                                    | 4        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 4        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 3        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 3        | 0.49%   |
| Intel I210 Gigabit Network Connection                               | 3        | 0.49%   |
| Intel Ethernet Controller X550                                      | 3        | 0.49%   |
| Intel Ethernet Connection (14) I219-V                               | 3        | 0.49%   |
| Intel Ethernet Connection (11) I219-V                               | 3        | 0.49%   |
| Intel Ethernet Connection (10) I219-V                               | 3        | 0.49%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                     | 3        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 2        | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.33%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 2        | 0.33%   |
| Intel I350 Gigabit Network Connection                               | 2        | 0.33%   |
| Intel Ethernet Connection (17) I219-V                               | 2        | 0.33%   |
| Intel 82578DM Gigabit Network Connection                            | 2        | 0.33%   |
| Intel 82575EB Gigabit Network Connection                            | 2        | 0.33%   |
| Google Pixel 6 Pro                                                  | 2        | 0.33%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                            | 2        | 0.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 2        | 0.33%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 2        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 524      | 66.16%  |
| WiFi     | 258      | 32.58%  |
| Modem    | 9        | 1.14%   |
| Unknown  | 1        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 420      | 75.13%  |
| WiFi     | 139      | 24.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 279      | 52.64%  |
| 2     | 204      | 38.49%  |
| 3     | 37       | 6.98%   |
| 4     | 6        | 1.13%   |
| 5     | 2        | 0.38%   |
| 9     | 1        | 0.19%   |
| 0     | 1        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 368      | 69.57%  |
| Yes  | 161      | 30.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 118      | 43.38%  |
| Cambridge Silicon Radio         | 53       | 19.49%  |
| MediaTek                        | 19       | 6.99%   |
| Realtek Semiconductor           | 18       | 6.62%   |
| TP-Link                         | 15       | 5.51%   |
| Broadcom                        | 11       | 4.04%   |
| ASUSTek Computer                | 9        | 3.31%   |
| Foxconn / Hon Hai               | 7        | 2.57%   |
| IMC Networks                    | 6        | 2.21%   |
| Qualcomm Atheros Communications | 4        | 1.47%   |
| Edimax Technology               | 2        | 0.74%   |
| Belkin Components               | 2        | 0.74%   |
| Apple                           | 2        | 0.74%   |
| Toshiba                         | 1        | 0.37%   |
| SINO WEALTH                     | 1        | 0.37%   |
| Lite-On Technology              | 1        | 0.37%   |
| Integrated System Solution      | 1        | 0.37%   |
| HTC (High Tech Computer)        | 1        | 0.37%   |
| Dynex                           | 1        | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 53       | 19.34%  |
| Intel AX200 Bluetooth                                                | 50       | 18.25%  |
| MediaTek Wireless_Device                                             | 19       | 6.93%   |
| Intel AX210 Bluetooth                                                | 17       | 6.2%    |
| TP-Link UB500 Adapter                                                | 15       | 5.47%   |
| Realtek Bluetooth Radio                                              | 15       | 5.47%   |
| Intel AX201 Bluetooth                                                | 14       | 5.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 12       | 4.38%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 9        | 3.28%   |
| Intel Bluetooth wireless interface                                   | 9        | 3.28%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 8        | 2.92%   |
| Foxconn / Hon Hai Wireless_Device                                    | 7        | 2.55%   |
| Intel Bluetooth Device                                               | 5        | 1.82%   |
| ASUS ASUS USB-BT500                                                  | 4        | 1.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3        | 1.09%   |
| IMC Networks Wireless_Device                                         | 3        | 1.09%   |
| IMC Networks Bluetooth Radio                                         | 3        | 1.09%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 0.73%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 0.73%   |
| Edimax Bluetooth Adapter                                             | 2        | 0.73%   |
| ASUS Bluetooth Adapter                                               | 2        | 0.73%   |
| Apple Bluetooth Host Controller                                      | 2        | 0.73%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 1        | 0.36%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 1        | 0.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 1        | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 0.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.36%   |
| Lite-On Bluetooth Device                                             | 1        | 0.36%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.36%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.36%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.36%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.36%   |
| Broadcom HP Portable Valentine                                       | 1        | 0.36%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.36%   |
| Broadcom BCM20702A0 Bluetooth                                        | 1        | 0.36%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.36%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.36%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.36%   |
| ASUS Bluetooth Radio                                                 | 1        | 0.36%   |
| ASUS Bluetooth Device                                                | 1        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 306      | 29.54%  |
| Intel                                           | 268      | 25.87%  |
| Nvidia                                          | 223      | 21.53%  |
| C-Media Electronics                             | 31       | 2.99%   |
| Logitech                                        | 15       | 1.45%   |
| JMTek                                           | 12       | 1.16%   |
| Creative Labs                                   | 12       | 1.16%   |
| ASUSTek Computer                                | 12       | 1.16%   |
| Razer USA                                       | 11       | 1.06%   |
| Kingston Technology                             | 10       | 0.97%   |
| Texas Instruments                               | 8        | 0.77%   |
| Focusrite-Novation                              | 8        | 0.77%   |
| SteelSeries ApS                                 | 7        | 0.68%   |
| Generalplus Technology                          | 7        | 0.68%   |
| Samson Technologies                             | 5        | 0.48%   |
| GN Netcom                                       | 5        | 0.48%   |
| Corsair                                         | 5        | 0.48%   |
| Sony                                            | 4        | 0.39%   |
| Realtek Semiconductor                           | 4        | 0.39%   |
| Plantronics                                     | 4        | 0.39%   |
| XMOS                                            | 3        | 0.29%   |
| VIA Technologies                                | 3        | 0.29%   |
| RODE Microphones                                | 3        | 0.29%   |
| Micro Star International                        | 3        | 0.29%   |
| Giga-Byte Technology                            | 3        | 0.29%   |
| Dell                                            | 3        | 0.29%   |
| Creative Technology                             | 3        | 0.29%   |
| Trust                                           | 2        | 0.19%   |
| Thesycon Systemsoftware & Consulting            | 2        | 0.19%   |
| Schiit Audio                                    | 2        | 0.19%   |
| Medeli Electronics                              | 2        | 0.19%   |
| M-Audio                                         | 2        | 0.19%   |
| Licensed by Sony Computer Entertainment America | 2        | 0.19%   |
| LG Electronics                                  | 2        | 0.19%   |
| KTMicro                                         | 2        | 0.19%   |
| GYROCOM C&C                                     | 2        | 0.19%   |
| FiiO Electronics Technology                     | 2        | 0.19%   |
| FDUCE PRO AUDIO MADE                            | 2        | 0.19%   |
| Cambridge Silicon Radio                         | 2        | 0.19%   |
| Blue Microphones                                | 2        | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 113      | 9.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 69       | 5.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 68       | 5.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 47       | 3.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 38       | 3.06%   |
| Intel 200 Series PCH HD Audio                                              | 31       | 2.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 28       | 2.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 2.17%   |
| Intel Alder Lake-S HD Audio Controller                                     | 26       | 2.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 25       | 2.01%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 25       | 2.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 25       | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 21       | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19       | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 16       | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                              | 16       | 1.29%   |
| Nvidia GA104 High Definition Audio Controller                              | 16       | 1.29%   |
| AMD Navi 10 HDMI Audio                                                     | 16       | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 15       | 1.21%   |
| Nvidia GP104 High Definition Audio Controller                              | 14       | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14       | 1.13%   |
| Nvidia TU104 HD Audio Controller                                           | 13       | 1.05%   |
| Nvidia GM206 High Definition Audio Controller                              | 13       | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13       | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                              | 12       | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                              | 12       | 0.97%   |
| Nvidia GA102 High Definition Audio Controller                              | 12       | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 11       | 0.88%   |
| JMTek USB PnP Audio Device                                                 | 11       | 0.88%   |
| AMD FCH Azalia Controller                                                  | 11       | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 11       | 0.88%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 10       | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 9        | 0.72%   |
| C-Media Electronics USB Audio Device                                       | 9        | 0.72%   |
| ASUSTek Computer USB Audio                                                 | 9        | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                         | 8        | 0.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 0.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 0.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 0.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 54       | 21.18%  |
| G.Skill             | 40       | 15.69%  |
| Corsair             | 40       | 15.69%  |
| Crucial             | 18       | 7.06%   |
| Unknown             | 17       | 6.67%   |
| Samsung Electronics | 17       | 6.67%   |
| SK hynix            | 10       | 3.92%   |
| A-DATA Technology   | 7        | 2.75%   |
| Micron Technology   | 6        | 2.35%   |
| Patriot             | 5        | 1.96%   |
| Team                | 4        | 1.57%   |
| AMD                 | 4        | 1.57%   |
| Smart               | 3        | 1.18%   |
| Ramaxel Technology  | 3        | 1.18%   |
| Nanya Technology    | 3        | 1.18%   |
| Apacer              | 3        | 1.18%   |
| Unknown             | 3        | 1.18%   |
| Unifosa             | 2        | 0.78%   |
| Gold Key            | 2        | 0.78%   |
| GeIL                | 2        | 0.78%   |
| Unknown (ABCD)      | 1        | 0.39%   |
| Unknown (0x0C97)    | 1        | 0.39%   |
| Transcend           | 1        | 0.39%   |
| Silicon Power       | 1        | 0.39%   |
| Qimonda             | 1        | 0.39%   |
| PNY                 | 1        | 0.39%   |
| Innodisk            | 1        | 0.39%   |
| GOODRAM             | 1        | 0.39%   |
| Golden Empire       | 1        | 0.39%   |
| EVGA                | 1        | 0.39%   |
| Elpida              | 1        | 0.39%   |
| Avant               | 1        | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 5        | 1.84%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 5        | 1.84%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s  | 5        | 1.84%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 4        | 1.47%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 1.1%    |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s   | 3        | 1.1%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 3        | 1.1%    |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s | 3        | 1.1%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 3        | 1.1%    |
| Unknown                                                | 3        | 1.1%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 0.74%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 2        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 2        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2        | 0.74%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s     | 2        | 0.74%   |
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s    | 2        | 0.74%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s    | 2        | 0.74%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 2        | 0.74%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 2        | 0.74%   |
| Kingston RAM KF560C40-16 16GB DIMM DDR5 6000MT/s       | 2        | 0.74%   |
| Kingston RAM KF552C40-8 8GB DIMM DDR5 4800MT/s         | 2        | 0.74%   |
| Kingston RAM KF552C40-32 32GB DIMM DDR5 5200MT/s       | 2        | 0.74%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s       | 2        | 0.74%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s  | 2        | 0.74%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s  | 2        | 0.74%   |
| G.Skill RAM F5-5600J3036D16G 16GB DIMM DDR5 4800MT/s   | 2        | 0.74%   |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s    | 2        | 0.74%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s  | 2        | 0.74%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s  | 2        | 0.74%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s  | 2        | 0.74%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s  | 2        | 0.74%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s            | 2        | 0.74%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR2 533MT/s               | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM 800MT/s                    | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM 667MT/s                    | 1        | 0.37%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s             | 1        | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s             | 1        | 0.37%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s               | 1        | 0.37%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 129      | 57.33%  |
| DDR3    | 52       | 23.11%  |
| DDR5    | 24       | 10.67%  |
| DDR2    | 10       | 4.44%   |
| Unknown | 6        | 2.67%   |
| SDRAM   | 2        | 0.89%   |
| LPDDR4  | 1        | 0.44%   |
| DDR     | 1        | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 216      | 96.86%  |
| SODIMM  | 5        | 2.24%   |
| FB-DIMM | 2        | 0.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 93       | 39.57%  |
| 16384 | 57       | 24.26%  |
| 4096  | 43       | 18.3%   |
| 32768 | 20       | 8.51%   |
| 2048  | 18       | 7.66%   |
| 1024  | 4        | 1.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 32       | 12.85%  |
| 1600  | 31       | 12.45%  |
| 3600  | 27       | 10.84%  |
| 2400  | 15       | 6.02%   |
| 1333  | 15       | 6.02%   |
| 4800  | 13       | 5.22%   |
| 3466  | 11       | 4.42%   |
| 2133  | 9        | 3.61%   |
| 3866  | 7        | 2.81%   |
| 2667  | 7        | 2.81%   |
| 800   | 7        | 2.81%   |
| 5200  | 5        | 2.01%   |
| 3400  | 5        | 2.01%   |
| 2666  | 5        | 2.01%   |
| 667   | 5        | 2.01%   |
| 3800  | 4        | 1.61%   |
| 3000  | 4        | 1.61%   |
| 1866  | 4        | 1.61%   |
| 1800  | 4        | 1.61%   |
| 6000  | 3        | 1.2%    |
| 3733  | 3        | 1.2%    |
| 3666  | 3        | 1.2%    |
| 3333  | 2        | 0.8%    |
| 3266  | 2        | 0.8%    |
| 2933  | 2        | 0.8%    |
| 2800  | 2        | 0.8%    |
| 533   | 2        | 0.8%    |
| 400   | 2        | 0.8%    |
| 333   | 2        | 0.8%    |
| 6400  | 1        | 0.4%    |
| 5808  | 1        | 0.4%    |
| 5600  | 1        | 0.4%    |
| 4600  | 1        | 0.4%    |
| 4133  | 1        | 0.4%    |
| 3334  | 1        | 0.4%    |
| 3151  | 1        | 0.4%    |
| 3100  | 1        | 0.4%    |
| 3066  | 1        | 0.4%    |
| 2934  | 1        | 0.4%    |
| 2200  | 1        | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Brother Industries    | 6        | 26.09%  |
| Hewlett-Packard       | 5        | 21.74%  |
| Seiko Epson           | 4        | 17.39%  |
| Samsung Electronics   | 4        | 17.39%  |
| Canon                 | 2        | 8.7%    |
| Prolific Technology   | 1        | 4.35%   |
| Lexmark International | 1        | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson WP-4020 Series    | 1        | 4.35%   |
| Seiko Epson WF-2860 Series    | 1        | 4.35%   |
| Seiko Epson Printer           | 1        | 4.35%   |
| Seiko Epson L300 Series       | 1        | 4.35%   |
| Samsung SCX-4623 Series       | 1        | 4.35%   |
| Samsung SCX-4300 Series       | 1        | 4.35%   |
| Samsung ML-2855 Series        | 1        | 4.35%   |
| Samsung M2070 Series          | 1        | 4.35%   |
| Prolific PL2305 Parallel Port | 1        | 4.35%   |
| Lexmark International B2236dw | 1        | 4.35%   |
| HP LaserJet 1010              | 1        | 4.35%   |
| HP ENVY Photo 7800 series     | 1        | 4.35%   |
| HP DeskJet F300 series        | 1        | 4.35%   |
| HP DeskJet 5650c              | 1        | 4.35%   |
| HP DeskJet 3630 series        | 1        | 4.35%   |
| Canon TS5100 series           | 1        | 4.35%   |
| Canon LiDE 400                | 1        | 4.35%   |
| Brother MFC-7460DN            | 1        | 4.35%   |
| Brother HL-L2350DW series     | 1        | 4.35%   |
| Brother HL-L2320D series      | 1        | 4.35%   |
| Brother HL-L2300D series      | 1        | 4.35%   |
| Brother HL-2030 Laser Printer | 1        | 4.35%   |
| Brother DCP-L2510D series     | 1        | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 5        | 71.43%  |
| Canon       | 2        | 28.57%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                    | 2        | 28.57%  |
| Seiko Epson GT-6600U [Perfection 610]                    | 2        | 28.57%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 14.29%  |
| Canon CanoScan LiDE 210                                  | 1        | 14.29%  |
| Canon CanoScan LiDE 100                                  | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 72       | 48%     |
| Microdia                               | 13       | 8.67%   |
| Samsung Electronics                    | 7        | 4.67%   |
| Microsoft                              | 7        | 4.67%   |
| Apple                                  | 7        | 4.67%   |
| Sunplus Innovation Technology          | 4        | 2.67%   |
| KYE Systems (Mouse Systems)            | 4        | 2.67%   |
| LG Electronics                         | 3        | 2%      |
| Chicony Electronics                    | 3        | 2%      |
| webcam                                 | 2        | 1.33%   |
| WaveRider Communications               | 2        | 1.33%   |
| Trust                                  | 2        | 1.33%   |
| SunplusIT                              | 2        | 1.33%   |
| Cubeternet                             | 2        | 1.33%   |
| AVerMedia Technologies                 | 2        | 1.33%   |
| Z-Star Microelectronics                | 1        | 0.67%   |
| WCM_USB                                | 1        | 0.67%   |
| Unknown                                | 1        | 0.67%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.67%   |
| Sonix Technology                       | 1        | 0.67%   |
| SN0002                                 | 1        | 0.67%   |
| Smartronix                             | 1        | 0.67%   |
| Realtek Semiconductor                  | 1        | 0.67%   |
| Nikon                                  | 1        | 0.67%   |
| MacroSilicon                           | 1        | 0.67%   |
| Integrated Technology Express          | 1        | 0.67%   |
| Hewlett-Packard                        | 1        | 0.67%   |
| DigitalPersona                         | 1        | 0.67%   |
| ASUSTek Computer                       | 1        | 0.67%   |
| Arkmicro Technologies                  | 1        | 0.67%   |
| ARC International                      | 1        | 0.67%   |
| Anker PowerConf C200                   | 1        | 0.67%   |
| A4Tech                                 | 1        | 0.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920          | 14       | 9.27%   |
| Logitech Webcam C270                 | 12       | 7.95%   |
| Logitech HD Webcam C525              | 9        | 5.96%   |
| Samsung Galaxy A5 (MTP)              | 7        | 4.64%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X      | 7        | 4.64%   |
| Logitech C922 Pro Stream Webcam      | 6        | 3.97%   |
| Microdia Webcam Vitade AF            | 5        | 3.31%   |
| Logitech C920 PRO HD Webcam          | 4        | 2.65%   |
| Logitech Webcam C930e                | 3        | 1.99%   |
| Logitech HD Webcam C615              | 3        | 1.99%   |
| Logitech BRIO Ultra HD Webcam        | 3        | 1.99%   |
| webcam webcam                        | 2        | 1.32%   |
| WaveRider USB 2.0 Camera             | 2        | 1.32%   |
| Microsoft MicrosoftÂ LifeCam Cinema | 2        | 1.32%   |
| Microdia USB 2.0 Camera              | 2        | 1.32%   |
| Microdia Camera                      | 2        | 1.32%   |
| Logitech Webcam C925e                | 2        | 1.32%   |
| Logitech Webcam C310                 | 2        | 1.32%   |
| Logitech Webcam C250                 | 2        | 1.32%   |
| Logitech Webcam C170                 | 2        | 1.32%   |
| Logitech Logi Webcam C920e           | 2        | 1.32%   |
| LG LG UltraFine Display Camera       | 2        | 1.32%   |
| AVerMedia Live Streamer CAM 313      | 2        | 1.32%   |
| Z-Star Venus USB2.0 Camera           | 1        | 0.66%   |
| WCM_USB WEB CAM                      | 1        | 0.66%   |
| Unknown HD camera                    | 1        | 0.66%   |
| Trust WB-6250X Webcam                | 1        | 0.66%   |
| Trust FHD Webcam                     | 1        | 0.66%   |
| SunplusIT USB camera                 | 1        | 0.66%   |
| SunplusIT USB 2.0 Camera             | 1        | 0.66%   |
| Sunplus WEMISS CM-A1                 | 1        | 0.66%   |
| Sunplus NexiGo N930AF FHD Webcam     | 1        | 0.66%   |
| Sunplus HD 720P webcam               | 1        | 0.66%   |
| Sunplus Aukey-PC-LM1E Camera         | 1        | 0.66%   |
| Sony Ericsson Mobile AB XQ-CC54      | 1        | 0.66%   |
| Sonix USB Camera                     | 1        | 0.66%   |
| SN0002 1080P Web Camera              | 1        | 0.66%   |
| Smartronix webcam                    | 1        | 0.66%   |
| Realtek NexiGo N960E FHD Webcam      | 1        | 0.66%   |
| Nikon DSC D3200                      | 1        | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Microsoft             | 1        | 20%     |
| LighTuning Technology | 1        | 20%     |
| Elan Microelectronics | 1        | 20%     |
| DigitalPersona        | 1        | 20%     |
| AuthenTec             | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Microsoft Fingerprint Reader                | 1        | 20%     |
| LighTuning Fingerprint Sensor               | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 20%     |
| DigitalPersona Fingerprint Reader           | 1        | 20%     |
| AuthenTec AES1600                           | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Reiner SCT Kartensysteme | 1        | 50%     |
| Aktiv                    | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 50%     |
| Aktiv Rutoken lite                                                         | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 450      | 84.59%  |
| 1     | 66       | 12.41%  |
| 2     | 6        | 1.13%   |
| 4     | 4        | 0.75%   |
| 3     | 4        | 0.75%   |
| 8     | 1        | 0.19%   |
| 5     | 1        | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 30       | 29.7%   |
| Net/wireless             | 20       | 19.8%   |
| Sound                    | 11       | 10.89%  |
| Multimedia controller    | 8        | 7.92%   |
| Unassigned class         | 7        | 6.93%   |
| Camera                   | 6        | 5.94%   |
| Fingerprint reader       | 4        | 3.96%   |
| Communication controller | 4        | 3.96%   |
| Storage/raid             | 3        | 2.97%   |
| Network                  | 3        | 2.97%   |
| Net/ethernet             | 3        | 2.97%   |
| Modem                    | 1        | 0.99%   |
| Bluetooth                | 1        | 0.99%   |

