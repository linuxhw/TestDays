Ubuntu MATE 20.04 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 333

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | A88X-GAMER                  | [8340e366fc](https://linux-hardware.org/?probe=8340e366fc) | Mar 28, 2022 |
| ASUSTek       | A55BM-E                     | [7bbbcc53c1](https://linux-hardware.org/?probe=7bbbcc53c1) | Mar 14, 2022 |
| Dell          | OptiPlex 980                | [14cf2b23f7](https://linux-hardware.org/?probe=14cf2b23f7) | Mar 14, 2022 |
| ASUSTek       | M4A79XTD EVO                | [d59f0b152c](https://linux-hardware.org/?probe=d59f0b152c) | Mar 10, 2022 |
| Gigabyte      | Z68XP-UD3                   | [6382c70064](https://linux-hardware.org/?probe=6382c70064) | Mar 07, 2022 |
| ASRock        | B450M Pro4                  | [b18f6804d6](https://linux-hardware.org/?probe=b18f6804d6) | Mar 02, 2022 |
| ECS           | A785GM-AD3                  | [43c3e7c4a0](https://linux-hardware.org/?probe=43c3e7c4a0) | Mar 02, 2022 |
| Pegatron      | Narra6                      | [ad9a06f14d](https://linux-hardware.org/?probe=ad9a06f14d) | Feb 25, 2022 |
| ECS           | G41T-M7                     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| ECS           | A785GM-AD3                  | [b6459dbb39](https://linux-hardware.org/?probe=b6459dbb39) | Feb 12, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [e58751112a](https://linux-hardware.org/?probe=e58751112a) | Feb 11, 2022 |
| Gigabyte      | F2A88XM-D3HP                | [c6783b6b8b](https://linux-hardware.org/?probe=c6783b6b8b) | Feb 07, 2022 |
| ASUSTek       | H61M-K                      | [0e2c677ddc](https://linux-hardware.org/?probe=0e2c677ddc) | Feb 03, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [fab2b2828e](https://linux-hardware.org/?probe=fab2b2828e) | Jan 26, 2022 |
| ASRock        | Z77 Pro4                    | [8062682731](https://linux-hardware.org/?probe=8062682731) | Jan 25, 2022 |
| Gigabyte      | H410M H V3                  | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| ASRock        | G41C-VS                     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| ASUSTek       | P5LD2                       | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Dell          | 0UG982                      | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Dell          | 0FH884                      | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| Dell          | 0UG982                      | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| Dell          | 0UG982                      | [597dfb85b7](https://linux-hardware.org/?probe=597dfb85b7) | Jan 19, 2022 |
| ASUSTek       | H81M-C                      | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [a96f2def6d](https://linux-hardware.org/?probe=a96f2def6d) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| ASUSTek       | H81M-C                      | [51d8172f5b](https://linux-hardware.org/?probe=51d8172f5b) | Jan 16, 2022 |
| ASUSTek       | H81M-C                      | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| ASUSTek       | H81M-K                      | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| Dell          | 032W55 A03                  | [f3838abaaf](https://linux-hardware.org/?probe=f3838abaaf) | Jan 04, 2022 |
| ASRock        | 970 Extreme4                | [1fbef2b76c](https://linux-hardware.org/?probe=1fbef2b76c) | Dec 23, 2021 |
| ASUSTek       | PRIME B360M-K               | [8df64a7f80](https://linux-hardware.org/?probe=8df64a7f80) | Dec 21, 2021 |
| MSI           | H61M-S20                    | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| ASUSTek       | H81M-A                      | [50acb69e6e](https://linux-hardware.org/?probe=50acb69e6e) | Dec 02, 2021 |
| HP            | 3646h                       | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | [9b13286f92](https://linux-hardware.org/?probe=9b13286f92) | Nov 28, 2021 |
| MSI           | H81M-P33                    | [3d2583b1f1](https://linux-hardware.org/?probe=3d2583b1f1) | Nov 26, 2021 |
| Dell          | 0T656F A01                  | [06f4633f1b](https://linux-hardware.org/?probe=06f4633f1b) | Nov 24, 2021 |
| ASUSTek       | AT3IONT-I                   | [b8f5329824](https://linux-hardware.org/?probe=b8f5329824) | Nov 22, 2021 |
| Dell          | 0M017G A00                  | [da444f9b8f](https://linux-hardware.org/?probe=da444f9b8f) | Nov 22, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [a13103a9ad](https://linux-hardware.org/?probe=a13103a9ad) | Nov 20, 2021 |
| ASRock        | B450M Pro4                  | [2cdd151d75](https://linux-hardware.org/?probe=2cdd151d75) | Nov 14, 2021 |
| Dell          | 03NVJ6 A00                  | [61bfe5dfa7](https://linux-hardware.org/?probe=61bfe5dfa7) | Nov 11, 2021 |
| ASUSTek       | M4A78-E                     | [dd8a96b615](https://linux-hardware.org/?probe=dd8a96b615) | Nov 09, 2021 |
| ASUSTek       | M4A78-E                     | [89aff3881c](https://linux-hardware.org/?probe=89aff3881c) | Nov 09, 2021 |
| ASUSTek       | A55BM-E                     | [fd25737c58](https://linux-hardware.org/?probe=fd25737c58) | Nov 09, 2021 |
| ASRock        | B450M Pro4                  | [4138b9cffa](https://linux-hardware.org/?probe=4138b9cffa) | Nov 08, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [e21897758d](https://linux-hardware.org/?probe=e21897758d) | Nov 07, 2021 |
| Gigabyte      | H97M-D3H                    | [05e3caa05c](https://linux-hardware.org/?probe=05e3caa05c) | Nov 02, 2021 |
| ASRock        | B450M Pro4                  | [60ffb9d428](https://linux-hardware.org/?probe=60ffb9d428) | Oct 31, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | [4946a6a02c](https://linux-hardware.org/?probe=4946a6a02c) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | [0ad429cea5](https://linux-hardware.org/?probe=0ad429cea5) | Oct 26, 2021 |
| ASUSTek       | M5A78L LE                   | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [27b0a66ceb](https://linux-hardware.org/?probe=27b0a66ceb) | Oct 20, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| Dell          | 08NPPY A00                  | [f0ff9a911e](https://linux-hardware.org/?probe=f0ff9a911e) | Oct 03, 2021 |
| Gigabyte      | Z97-HD3                     | [5f6c245dc5](https://linux-hardware.org/?probe=5f6c245dc5) | Sep 28, 2021 |
| MSI           | H61M-P23                    | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| Gigabyte      | Z97-HD3                     | [6a2e918e37](https://linux-hardware.org/?probe=6a2e918e37) | Sep 28, 2021 |
| Dell          | 03NVJ6 A00                  | [5422d3bf1d](https://linux-hardware.org/?probe=5422d3bf1d) | Sep 27, 2021 |
| Intel         | DG31PR AAD97573-206         | [060da3d3ab](https://linux-hardware.org/?probe=060da3d3ab) | Sep 26, 2021 |
| HP            | 8265                        | [f840aed42d](https://linux-hardware.org/?probe=f840aed42d) | Sep 21, 2021 |
| ASUSTek       | PRIME B450M-A               | [f93c2362ff](https://linux-hardware.org/?probe=f93c2362ff) | Sep 21, 2021 |
| HP            | 3397                        | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| ASRock        | H110M-STX                   | [6bb90d3b07](https://linux-hardware.org/?probe=6bb90d3b07) | Sep 16, 2021 |
| HP            | 3396                        | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
| ASRock        | H110M-STX                   | [a0b807eb42](https://linux-hardware.org/?probe=a0b807eb42) | Aug 30, 2021 |
| MSI           | Z370 PC PRO                 | [c594736488](https://linux-hardware.org/?probe=c594736488) | Aug 30, 2021 |
| ASRock        | B75M-DGS R2.0               | [16250b0c12](https://linux-hardware.org/?probe=16250b0c12) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [41e440c2e5](https://linux-hardware.org/?probe=41e440c2e5) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [e086d2eb61](https://linux-hardware.org/?probe=e086d2eb61) | Aug 29, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| ASRock        | M3A785GMH/128M              | [4ace1ea1ac](https://linux-hardware.org/?probe=4ace1ea1ac) | Aug 15, 2021 |
| MSI           | X79A-GD45                   | [c5b78e1a01](https://linux-hardware.org/?probe=c5b78e1a01) | Aug 13, 2021 |
| Dell          | 05GD68 A00                  | [bbfbd42562](https://linux-hardware.org/?probe=bbfbd42562) | Aug 07, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [c861e28d21](https://linux-hardware.org/?probe=c861e28d21) | Aug 05, 2021 |
| ASRock        | Q1900M                      | [700f4a0ca1](https://linux-hardware.org/?probe=700f4a0ca1) | Aug 02, 2021 |
| Dell          | 08NPPY A00                  | [fe0cf5b120](https://linux-hardware.org/?probe=fe0cf5b120) | Aug 01, 2021 |
| Dell          | 08NPPY A00                  | [e706b18dd8](https://linux-hardware.org/?probe=e706b18dd8) | Aug 01, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| ASUSTek       | M2N68-AM Plus               | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [6dcb19e468](https://linux-hardware.org/?probe=6dcb19e468) | Jul 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | [647fe69592](https://linux-hardware.org/?probe=647fe69592) | Jul 22, 2021 |
| MSI           | H61M-E33                    | [0d1a9284a9](https://linux-hardware.org/?probe=0d1a9284a9) | Jul 17, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [011a83c682](https://linux-hardware.org/?probe=011a83c682) | Jul 17, 2021 |
| Unknown       | TB-4000                     | [fb3e1984b0](https://linux-hardware.org/?probe=fb3e1984b0) | Jul 10, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [ae14beb6fd](https://linux-hardware.org/?probe=ae14beb6fd) | Jul 09, 2021 |
| Dell          | 05GD68 A00                  | [ebd157141b](https://linux-hardware.org/?probe=ebd157141b) | Jul 08, 2021 |
| Gigabyte      | H81M-S1                     | [4b2c3ea073](https://linux-hardware.org/?probe=4b2c3ea073) | Jul 07, 2021 |
| ASUSTek       | Z170-AR                     | [37343856a5](https://linux-hardware.org/?probe=37343856a5) | Jul 02, 2021 |
| Dell          | 05GD68 A00                  | [9bb3c8dbe9](https://linux-hardware.org/?probe=9bb3c8dbe9) | Jul 02, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [7fba4b1b78](https://linux-hardware.org/?probe=7fba4b1b78) | Jun 23, 2021 |
| HP            | 1495                        | [03ab704550](https://linux-hardware.org/?probe=03ab704550) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | [c71b41c7a8](https://linux-hardware.org/?probe=c71b41c7a8) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | [f39e5005bd](https://linux-hardware.org/?probe=f39e5005bd) | Jun 20, 2021 |
| eMachines     | EL1352                      | [f175ae71f2](https://linux-hardware.org/?probe=f175ae71f2) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [0616fdb086](https://linux-hardware.org/?probe=0616fdb086) | Jun 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [3d47d96665](https://linux-hardware.org/?probe=3d47d96665) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [c9bea47caa](https://linux-hardware.org/?probe=c9bea47caa) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [c9c757474a](https://linux-hardware.org/?probe=c9c757474a) | Jun 12, 2021 |
| ASRock        | ALiveXFire-eSATA2           | [17af721bae](https://linux-hardware.org/?probe=17af721bae) | Jun 10, 2021 |
| Gigabyte      | Z97-HD3                     | [1ab4ff25ab](https://linux-hardware.org/?probe=1ab4ff25ab) | Jun 10, 2021 |
| ASUSTek       | P8B75-M                     | [d732611ebb](https://linux-hardware.org/?probe=d732611ebb) | Jun 02, 2021 |
| Dell          | 0KRC95 A00                  | [913ea68973](https://linux-hardware.org/?probe=913ea68973) | May 31, 2021 |
| Inventec      | Z CLASS A02                 | [7fc4815cbd](https://linux-hardware.org/?probe=7fc4815cbd) | May 29, 2021 |
| Dell          | 02YYK5 A01                  | [6b9dbebe2f](https://linux-hardware.org/?probe=6b9dbebe2f) | May 18, 2021 |
| Acer          | Board                       | [7f9d35f468](https://linux-hardware.org/?probe=7f9d35f468) | May 18, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [f1592b156b](https://linux-hardware.org/?probe=f1592b156b) | May 16, 2021 |
| ASUSTek       | M2N68-AM Plus               | [7761ccf4be](https://linux-hardware.org/?probe=7761ccf4be) | May 07, 2021 |
| ASUSTek       | M2N68-AM Plus               | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [9ff1a95290](https://linux-hardware.org/?probe=9ff1a95290) | May 01, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [289a9d70d9](https://linux-hardware.org/?probe=289a9d70d9) | Apr 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [d5310b7f74](https://linux-hardware.org/?probe=d5310b7f74) | Apr 15, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [c2aed97877](https://linux-hardware.org/?probe=c2aed97877) | Apr 08, 2021 |
| MSI           | Z97 GAMING 5                | [946c22503a](https://linux-hardware.org/?probe=946c22503a) | Apr 07, 2021 |
| Dell          | 0F6X5P A00                  | [16218d28da](https://linux-hardware.org/?probe=16218d28da) | Apr 04, 2021 |
| HP            | 3397                        | [e5812883ce](https://linux-hardware.org/?probe=e5812883ce) | Mar 31, 2021 |
| ASRock        | H310M-STX                   | [419277b830](https://linux-hardware.org/?probe=419277b830) | Mar 26, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f3ac6366a6](https://linux-hardware.org/?probe=f3ac6366a6) | Mar 24, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4d7e0c9e41](https://linux-hardware.org/?probe=4d7e0c9e41) | Mar 23, 2021 |
| Lenovo        | SHARKBAY NOK                | [e9b0291347](https://linux-hardware.org/?probe=e9b0291347) | Mar 21, 2021 |
| HP            | 1497                        | [d35a7eef80](https://linux-hardware.org/?probe=d35a7eef80) | Mar 19, 2021 |
| Intel         | DH61WW AAG23116-203         | [e4faf817fd](https://linux-hardware.org/?probe=e4faf817fd) | Mar 19, 2021 |
| MSI           | MAG B550M MORTAR            | [9210657e45](https://linux-hardware.org/?probe=9210657e45) | Mar 17, 2021 |
| ASRock        | 960GM-S3 FX                 | [5784a74c50](https://linux-hardware.org/?probe=5784a74c50) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| Dell          | 03NVJ6 A00                  | [2b8f8e4cec](https://linux-hardware.org/?probe=2b8f8e4cec) | Mar 14, 2021 |
| MSI           | B85M-P33                    | [e7d2bb8e63](https://linux-hardware.org/?probe=e7d2bb8e63) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | [957f68f2b7](https://linux-hardware.org/?probe=957f68f2b7) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | [839bc4873c](https://linux-hardware.org/?probe=839bc4873c) | Mar 08, 2021 |
| MSI           | Z370-A PRO                  | [b5cf5849a1](https://linux-hardware.org/?probe=b5cf5849a1) | Mar 06, 2021 |
| HP            | 2B2C                        | [20c11c9bbc](https://linux-hardware.org/?probe=20c11c9bbc) | Mar 04, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [e4437002b3](https://linux-hardware.org/?probe=e4437002b3) | Mar 04, 2021 |
| Medion        | B460H6-EM                   | [2ab61e6080](https://linux-hardware.org/?probe=2ab61e6080) | Mar 03, 2021 |
| Dell          | 03NVJ6 A00                  | [f1349be70a](https://linux-hardware.org/?probe=f1349be70a) | Feb 19, 2021 |
| Unknown       | XH61X000.100                | [029de8905d](https://linux-hardware.org/?probe=029de8905d) | Feb 17, 2021 |
| JINGSHA       | Board                       | [01ab676e78](https://linux-hardware.org/?probe=01ab676e78) | Feb 15, 2021 |
| Dell          | 03NVJ6 A00                  | [87f43dfecd](https://linux-hardware.org/?probe=87f43dfecd) | Feb 12, 2021 |
| MSI           | B85M GAMING                 | [bd107eb4ae](https://linux-hardware.org/?probe=bd107eb4ae) | Feb 10, 2021 |
| Gigabyte      | MZBAYAB-00                  | [fa48450d71](https://linux-hardware.org/?probe=fa48450d71) | Feb 09, 2021 |
| ASUSTek       | P8P67 PRO                   | [bbff698cb8](https://linux-hardware.org/?probe=bbff698cb8) | Feb 09, 2021 |
| HP            | ProLiant MicroServer        | [394af8312b](https://linux-hardware.org/?probe=394af8312b) | Feb 07, 2021 |
| HP            | ProLiant MicroServer        | [0e61287ad7](https://linux-hardware.org/?probe=0e61287ad7) | Feb 07, 2021 |
| Gateway       | DX4885                      | [48628b0b95](https://linux-hardware.org/?probe=48628b0b95) | Feb 03, 2021 |
| Gigabyte      | H61M-D2H-USB3               | [e39393dcdb](https://linux-hardware.org/?probe=e39393dcdb) | Feb 02, 2021 |
| Intel         | H61M-S1                     | [38a03ee5be](https://linux-hardware.org/?probe=38a03ee5be) | Jan 31, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [20d082d72c](https://linux-hardware.org/?probe=20d082d72c) | Jan 26, 2021 |
| ASUSTek       | LITHIUM                     | [e2c8ad85fb](https://linux-hardware.org/?probe=e2c8ad85fb) | Jan 24, 2021 |
| ASUSTek       | LITHIUM                     | [3f3f25d596](https://linux-hardware.org/?probe=3f3f25d596) | Jan 24, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [4695d8c639](https://linux-hardware.org/?probe=4695d8c639) | Jan 24, 2021 |
| ASUSTek       | P5N-D                       | [cac7f8ae52](https://linux-hardware.org/?probe=cac7f8ae52) | Jan 23, 2021 |
| ASUSTek       | P5N-D                       | [b637c75d21](https://linux-hardware.org/?probe=b637c75d21) | Jan 23, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Dell          | 0200DY A03                  | [5e5ca98e54](https://linux-hardware.org/?probe=5e5ca98e54) | Jan 13, 2021 |
| ASUSTek       | P8Z68-V PRO                 | [86c7eb6c5b](https://linux-hardware.org/?probe=86c7eb6c5b) | Jan 11, 2021 |
| ASUSTek       | PRIME B250-PRO              | [474542bd76](https://linux-hardware.org/?probe=474542bd76) | Jan 10, 2021 |
| ASUSTek       | P7P55 LX                    | [d13d4667c3](https://linux-hardware.org/?probe=d13d4667c3) | Jan 09, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [fb8fa788e3](https://linux-hardware.org/?probe=fb8fa788e3) | Jan 07, 2021 |
| MSI           | H87-G43                     | [8b1363882c](https://linux-hardware.org/?probe=8b1363882c) | Jan 03, 2021 |
| Gigabyte      | Z97-HD3                     | [417a2cbe50](https://linux-hardware.org/?probe=417a2cbe50) | Dec 26, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [46e2c41ee6](https://linux-hardware.org/?probe=46e2c41ee6) | Dec 17, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [9ad04d0568](https://linux-hardware.org/?probe=9ad04d0568) | Dec 16, 2020 |
| ASUSTek       | M5A78L LE                   | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [e9fb6116b3](https://linux-hardware.org/?probe=e9fb6116b3) | Dec 14, 2020 |
| ASUSTek       | M5A78L LE                   | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| HP            | 82A2                        | [8b443d9da5](https://linux-hardware.org/?probe=8b443d9da5) | Dec 12, 2020 |
| HP            | 82A2                        | [58faddeba3](https://linux-hardware.org/?probe=58faddeba3) | Dec 12, 2020 |
| Gigabyte      | 945GCM-S2C                  | [e1d03e259e](https://linux-hardware.org/?probe=e1d03e259e) | Dec 09, 2020 |
| Gigabyte      | EP45T-EXTREME               | [9320edd724](https://linux-hardware.org/?probe=9320edd724) | Dec 07, 2020 |
| Gigabyte      | 945GCM-S2C                  | [eba95d11b5](https://linux-hardware.org/?probe=eba95d11b5) | Dec 04, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [94f75b4e92](https://linux-hardware.org/?probe=94f75b4e92) | Nov 22, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [49224bd7f8](https://linux-hardware.org/?probe=49224bd7f8) | Nov 21, 2020 |
| ASUSTek       | WS C246M PRO Series         | [502bd89093](https://linux-hardware.org/?probe=502bd89093) | Nov 18, 2020 |
| ASUSTek       | WS C246M PRO Series         | [dc20d9cf64](https://linux-hardware.org/?probe=dc20d9cf64) | Nov 17, 2020 |
| Medion        | B360H4-EM V1.0              | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| Dell          | 0WG864                      | [1c2384097b](https://linux-hardware.org/?probe=1c2384097b) | Nov 15, 2020 |
| HP            | 1790                        | [02138cec8b](https://linux-hardware.org/?probe=02138cec8b) | Nov 08, 2020 |
| HP            | 1905                        | [6f20f6aa7d](https://linux-hardware.org/?probe=6f20f6aa7d) | Nov 08, 2020 |
| Intel         | SLIMBOOK                    | [2250e4a10f](https://linux-hardware.org/?probe=2250e4a10f) | Nov 07, 2020 |
| HP            | 3397                        | [17188b10a3](https://linux-hardware.org/?probe=17188b10a3) | Nov 06, 2020 |
| Pegatron      | NARRA3                      | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| Lenovo        | Board                       | [69bc4fbb1b](https://linux-hardware.org/?probe=69bc4fbb1b) | Oct 30, 2020 |
| HP            | 1493                        | [34134cab7f](https://linux-hardware.org/?probe=34134cab7f) | Oct 30, 2020 |
| HP            | 1493                        | [dd1964d532](https://linux-hardware.org/?probe=dd1964d532) | Oct 30, 2020 |
| HP            | 1497                        | [1d068e5c77](https://linux-hardware.org/?probe=1d068e5c77) | Oct 28, 2020 |
| HP            | 3047h                       | [4f58775069](https://linux-hardware.org/?probe=4f58775069) | Oct 28, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [a13afb5c54](https://linux-hardware.org/?probe=a13afb5c54) | Oct 27, 2020 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [dd929b231e](https://linux-hardware.org/?probe=dd929b231e) | Oct 26, 2020 |
| ASRock        | G31M-GS                     | [0a9aa8dcd2](https://linux-hardware.org/?probe=0a9aa8dcd2) | Oct 26, 2020 |
| Biostar       | A320MH                      | [8c1edce824](https://linux-hardware.org/?probe=8c1edce824) | Oct 24, 2020 |
| Dell          | 0V6XGW A00                  | [1518ff90f9](https://linux-hardware.org/?probe=1518ff90f9) | Oct 24, 2020 |
| Gigabyte      | H110M-H DDR3-CF             | [ab60c752a9](https://linux-hardware.org/?probe=ab60c752a9) | Oct 23, 2020 |
| HP            | 3047h                       | [ecba048272](https://linux-hardware.org/?probe=ecba048272) | Oct 21, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [658b7105e1](https://linux-hardware.org/?probe=658b7105e1) | Oct 21, 2020 |
| HP            | 3047h                       | [4c9083177a](https://linux-hardware.org/?probe=4c9083177a) | Oct 21, 2020 |
| HP            | 3047h                       | [67e7807767](https://linux-hardware.org/?probe=67e7807767) | Oct 21, 2020 |
| HP            | 3047h                       | [4dd1cde645](https://linux-hardware.org/?probe=4dd1cde645) | Oct 20, 2020 |
| HP            | 3047h                       | [d84da1ea3e](https://linux-hardware.org/?probe=d84da1ea3e) | Oct 20, 2020 |
| HP            | 3047h                       | [134da552c2](https://linux-hardware.org/?probe=134da552c2) | Oct 20, 2020 |
| HP            | 304Ah                       | [3163a2892d](https://linux-hardware.org/?probe=3163a2892d) | Oct 19, 2020 |
| HP            | 3397                        | [8bdef2c49c](https://linux-hardware.org/?probe=8bdef2c49c) | Oct 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [e5aa6a33a6](https://linux-hardware.org/?probe=e5aa6a33a6) | Oct 18, 2020 |
| HP            | 3397                        | [5a6fac5a0f](https://linux-hardware.org/?probe=5a6fac5a0f) | Oct 16, 2020 |
| MSI           | B550M PRO-VDH WIFI          | [2c4fc7773a](https://linux-hardware.org/?probe=2c4fc7773a) | Oct 14, 2020 |
| Dell          | 042P49 A01                  | [44c14427a0](https://linux-hardware.org/?probe=44c14427a0) | Oct 13, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [097db248db](https://linux-hardware.org/?probe=097db248db) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [41141f049e](https://linux-hardware.org/?probe=41141f049e) | Oct 11, 2020 |
| Gigabyte      | A320M-H-CF                  | [2c0322f113](https://linux-hardware.org/?probe=2c0322f113) | Oct 10, 2020 |
| Dell          | 0FR6WH A01                  | [2776ae6a1a](https://linux-hardware.org/?probe=2776ae6a1a) | Oct 09, 2020 |
| Dell          | 0T656F A01                  | [f44db9c73a](https://linux-hardware.org/?probe=f44db9c73a) | Oct 09, 2020 |
| Pegatron      | 2A84h                       | [a8d97c37b7](https://linux-hardware.org/?probe=a8d97c37b7) | Oct 08, 2020 |
| Dell          | 0HN7XN A00                  | [885b19f22a](https://linux-hardware.org/?probe=885b19f22a) | Oct 08, 2020 |
| HP            | 3646h                       | [d5dd5824e3](https://linux-hardware.org/?probe=d5dd5824e3) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | [1f6fe3684d](https://linux-hardware.org/?probe=1f6fe3684d) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | [8872b79e71](https://linux-hardware.org/?probe=8872b79e71) | Oct 07, 2020 |
| Dell          | 0TVR1F A01                  | [3de8c4e65d](https://linux-hardware.org/?probe=3de8c4e65d) | Oct 06, 2020 |
| Dell          | 0TVR1F A01                  | [ae1a5155a6](https://linux-hardware.org/?probe=ae1a5155a6) | Oct 05, 2020 |
| Gigabyte      | B460M DS3H                  | [c607051cd6](https://linux-hardware.org/?probe=c607051cd6) | Oct 04, 2020 |
| Gigabyte      | B460M DS3H                  | [a96b9c0e32](https://linux-hardware.org/?probe=a96b9c0e32) | Oct 04, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [16d07f52d6](https://linux-hardware.org/?probe=16d07f52d6) | Sep 29, 2020 |
| HP            | 3047h                       | [8276b976a7](https://linux-hardware.org/?probe=8276b976a7) | Sep 28, 2020 |
| HP            | 1497                        | [3c6ed08ddd](https://linux-hardware.org/?probe=3c6ed08ddd) | Sep 25, 2020 |
| Gigabyte      | H81M-H                      | [21991336a9](https://linux-hardware.org/?probe=21991336a9) | Sep 25, 2020 |
| Dell          | 09M8Y8 A01                  | [7086c0ba36](https://linux-hardware.org/?probe=7086c0ba36) | Sep 25, 2020 |
| Intel         | DG43GT AAE62768-301         | [028847b86e](https://linux-hardware.org/?probe=028847b86e) | Sep 21, 2020 |
| Dell          | 0WX729                      | [f2cc61a6f1](https://linux-hardware.org/?probe=f2cc61a6f1) | Sep 17, 2020 |
| Dell          | 0WX729                      | [4fdbabe245](https://linux-hardware.org/?probe=4fdbabe245) | Sep 17, 2020 |
| Dell          | 0D441T A01                  | [a5c5a78a7c](https://linux-hardware.org/?probe=a5c5a78a7c) | Sep 16, 2020 |
| Dell          | 0TW904                      | [20994a3808](https://linux-hardware.org/?probe=20994a3808) | Sep 15, 2020 |
| Dell          | 0T656F A01                  | [a004d9a942](https://linux-hardware.org/?probe=a004d9a942) | Sep 14, 2020 |
| HP            | 18E7                        | [18852c6be3](https://linux-hardware.org/?probe=18852c6be3) | Sep 11, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [0bba6eaf71](https://linux-hardware.org/?probe=0bba6eaf71) | Sep 11, 2020 |
| Dell          | 0T656F A01                  | [6b43e65d15](https://linux-hardware.org/?probe=6b43e65d15) | Sep 10, 2020 |
| Dell          | 0TVR1F A01                  | [22aaefa03b](https://linux-hardware.org/?probe=22aaefa03b) | Sep 10, 2020 |
| Dell          | 042P49 A01                  | [282331caa5](https://linux-hardware.org/?probe=282331caa5) | Sep 10, 2020 |
| Dell          | 0M5DCD A00                  | [bfc77d64c6](https://linux-hardware.org/?probe=bfc77d64c6) | Sep 09, 2020 |
| Dell          | 0M5DCD A00                  | [d269751a9e](https://linux-hardware.org/?probe=d269751a9e) | Sep 09, 2020 |
| Dell          | 0N820C A02                  | [a43f37d51e](https://linux-hardware.org/?probe=a43f37d51e) | Sep 08, 2020 |
| Gigabyte      | H81M-H                      | [3ae339618d](https://linux-hardware.org/?probe=3ae339618d) | Sep 08, 2020 |
| Gigabyte      | H81M-H                      | [d2f477c7f5](https://linux-hardware.org/?probe=d2f477c7f5) | Sep 08, 2020 |
| Dell          | 0M5DCD A00                  | [c39d1b0af6](https://linux-hardware.org/?probe=c39d1b0af6) | Sep 05, 2020 |
| MSI           | Creator TRX40               | [48149893d7](https://linux-hardware.org/?probe=48149893d7) | Sep 04, 2020 |
| HP            | 3397                        | [e9da9cd17f](https://linux-hardware.org/?probe=e9da9cd17f) | Sep 03, 2020 |
| HP            | 339A                        | [5f29fd9231](https://linux-hardware.org/?probe=5f29fd9231) | Sep 03, 2020 |
| HP            | 3397                        | [a8ea68de6d](https://linux-hardware.org/?probe=a8ea68de6d) | Sep 03, 2020 |
| MSI           | MEG X570 UNIFY              | [7e2dae216d](https://linux-hardware.org/?probe=7e2dae216d) | Sep 03, 2020 |
| Dell          | 03K80F A00                  | [a3452cb614](https://linux-hardware.org/?probe=a3452cb614) | Sep 02, 2020 |
| Dell          | 0HY9JP A00                  | [e797b1bf14](https://linux-hardware.org/?probe=e797b1bf14) | Sep 02, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2b44d73e4b](https://linux-hardware.org/?probe=2b44d73e4b) | Sep 02, 2020 |
| HP            | 1497                        | [edf6c3ecfa](https://linux-hardware.org/?probe=edf6c3ecfa) | Sep 01, 2020 |
| Gigabyte      | H81M-H                      | [b5600f5c06](https://linux-hardware.org/?probe=b5600f5c06) | Aug 31, 2020 |
| Gigabyte      | H81M-H                      | [461e0244f4](https://linux-hardware.org/?probe=461e0244f4) | Aug 31, 2020 |
| Gigabyte      | X58A-UD3R                   | [b26cdf0225](https://linux-hardware.org/?probe=b26cdf0225) | Aug 29, 2020 |
| ASUSTek       | PRIME Z270-P                | [b39122c844](https://linux-hardware.org/?probe=b39122c844) | Aug 25, 2020 |
| ASUSTek       | PRIME X399-A                | [8d0d4f27be](https://linux-hardware.org/?probe=8d0d4f27be) | Aug 22, 2020 |
| Toshiba       | STI 010432                  | [7d6c45eed4](https://linux-hardware.org/?probe=7d6c45eed4) | Aug 20, 2020 |
| Toshiba       | STI 010432                  | [da8ae751c9](https://linux-hardware.org/?probe=da8ae751c9) | Aug 20, 2020 |
| ASUSTek       | PRIME Z270-P                | [b5c4317a43](https://linux-hardware.org/?probe=b5c4317a43) | Aug 20, 2020 |
| Intel         | Board                       | [0792f8e763](https://linux-hardware.org/?probe=0792f8e763) | Aug 20, 2020 |
| ASRock        | 990FX Extreme4              | [9d89158c0c](https://linux-hardware.org/?probe=9d89158c0c) | Aug 19, 2020 |
| ASUSTek       | PRIME Z270-P                | [f3ea863c21](https://linux-hardware.org/?probe=f3ea863c21) | Aug 19, 2020 |
| Toshiba       | STI 010432                  | [844d21cfba](https://linux-hardware.org/?probe=844d21cfba) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | [d568758fb5](https://linux-hardware.org/?probe=d568758fb5) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | [93e07b3103](https://linux-hardware.org/?probe=93e07b3103) | Aug 16, 2020 |
| ASRock        | B450M Pro4                  | [27573f027c](https://linux-hardware.org/?probe=27573f027c) | Aug 12, 2020 |
| Intel         | Board                       | [501444c3d4](https://linux-hardware.org/?probe=501444c3d4) | Aug 12, 2020 |
| Intel         | Board                       | [aca06096b6](https://linux-hardware.org/?probe=aca06096b6) | Aug 12, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1c6f36de59](https://linux-hardware.org/?probe=1c6f36de59) | Aug 10, 2020 |
| Gigabyte      | H97N-WIFI                   | [608ff52425](https://linux-hardware.org/?probe=608ff52425) | Aug 06, 2020 |
| Gigabyte      | Z77P-D3                     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| ASUSTek       | P9X79 DELUXE                | [bd1790913e](https://linux-hardware.org/?probe=bd1790913e) | Aug 03, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [8936a7017a](https://linux-hardware.org/?probe=8936a7017a) | Jul 28, 2020 |
| ASUSTek       | P9X79 DELUXE                | [3ee7d0dc49](https://linux-hardware.org/?probe=3ee7d0dc49) | Jul 28, 2020 |
| Gigabyte      | M68MT-S2P                   | [e9661e7816](https://linux-hardware.org/?probe=e9661e7816) | Jul 27, 2020 |
| Intel         | DH87RL AAG74240-402         | [dfb8a55f7f](https://linux-hardware.org/?probe=dfb8a55f7f) | Jul 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | [3ff385285a](https://linux-hardware.org/?probe=3ff385285a) | Jul 26, 2020 |
| Biostar       | G31-M7 TE                   | [6affb516f1](https://linux-hardware.org/?probe=6affb516f1) | Jul 24, 2020 |
| ASUSTek       | AM1M-A                      | [8a3873a0c3](https://linux-hardware.org/?probe=8a3873a0c3) | Jul 24, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [3e594f7ff4](https://linux-hardware.org/?probe=3e594f7ff4) | Jul 24, 2020 |
| Dell          | 0200DY A03                  | [9dbcace7db](https://linux-hardware.org/?probe=9dbcace7db) | Jul 21, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [292d396a46](https://linux-hardware.org/?probe=292d396a46) | Jul 21, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c3a79140eb](https://linux-hardware.org/?probe=c3a79140eb) | Jul 18, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [68e6b713ca](https://linux-hardware.org/?probe=68e6b713ca) | Jul 14, 2020 |
| ASUSTek       | P5QPL-AM                    | [bd28d2c132](https://linux-hardware.org/?probe=bd28d2c132) | Jul 13, 2020 |
| HP            | 8434 11                     | [377d6d5aa4](https://linux-hardware.org/?probe=377d6d5aa4) | Jul 10, 2020 |
| Lenovo        | Board                       | [30edd53934](https://linux-hardware.org/?probe=30edd53934) | Jul 09, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [994e71e658](https://linux-hardware.org/?probe=994e71e658) | Jul 03, 2020 |
| MSI           | A78M-E35                    | [baf6228acf](https://linux-hardware.org/?probe=baf6228acf) | Jul 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | [f7afeb0f26](https://linux-hardware.org/?probe=f7afeb0f26) | Jul 01, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c1d0ef500e](https://linux-hardware.org/?probe=c1d0ef500e) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6a9b477b88](https://linux-hardware.org/?probe=6a9b477b88) | Jun 29, 2020 |
| HP            | ProLiant MicroServer        | [1f2d306b05](https://linux-hardware.org/?probe=1f2d306b05) | Jun 20, 2020 |
| IBM           | Board                       | [28e9762210](https://linux-hardware.org/?probe=28e9762210) | Jun 16, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [02f2a001e1](https://linux-hardware.org/?probe=02f2a001e1) | Jun 11, 2020 |
| ASUSTek       | P5QPL-AM                    | [994e3df746](https://linux-hardware.org/?probe=994e3df746) | Jun 11, 2020 |
| ASRock        | H110M-STX                   | [3c35aef096](https://linux-hardware.org/?probe=3c35aef096) | Jun 10, 2020 |
| Dell          | 0478VN A00                  | [f02bda5144](https://linux-hardware.org/?probe=f02bda5144) | Jun 09, 2020 |
| Gigabyte      | B450M DS3H-CF               | [8dbad33afb](https://linux-hardware.org/?probe=8dbad33afb) | Jun 05, 2020 |
| ASRock        | A320M-HDV R4.0              | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASUSTek       | P5QPL-AM                    | [140b5cec40](https://linux-hardware.org/?probe=140b5cec40) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | [9c5c59ed91](https://linux-hardware.org/?probe=9c5c59ed91) | May 30, 2020 |
| IBM           | Board                       | [784c83d7d6](https://linux-hardware.org/?probe=784c83d7d6) | May 19, 2020 |
| ASUSTek       | PRIME B450M-K               | [8fd77159e9](https://linux-hardware.org/?probe=8fd77159e9) | May 19, 2020 |
| Dell          | 0WF810                      | [24f1a1287d](https://linux-hardware.org/?probe=24f1a1287d) | May 17, 2020 |
| Dell          | 0WF810                      | [6ae0e21069](https://linux-hardware.org/?probe=6ae0e21069) | May 17, 2020 |
| Dell          | 0WF810                      | [e6f27fd467](https://linux-hardware.org/?probe=e6f27fd467) | May 17, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4806bd297f](https://linux-hardware.org/?probe=4806bd297f) | May 16, 2020 |
| ASRock        | A320M-HDV R4.0              | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| Lenovo        | SDK0E50510 WIN 262507961... | [0400e155ee](https://linux-hardware.org/?probe=0400e155ee) | May 10, 2020 |
| Gigabyte      | GA-970A-UD3                 | [567162aae3](https://linux-hardware.org/?probe=567162aae3) | May 09, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9a72c58dee](https://linux-hardware.org/?probe=9a72c58dee) | May 04, 2020 |
| Gigabyte      | GA-A75-D3H                  | [88dd0cfbcb](https://linux-hardware.org/?probe=88dd0cfbcb) | May 02, 2020 |
| Gigabyte      | GA-A75-D3H                  | [530009d42a](https://linux-hardware.org/?probe=530009d42a) | May 02, 2020 |
| Intel         | D946GZIS AAD45436-306       | [483b574b1a](https://linux-hardware.org/?probe=483b574b1a) | Apr 25, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [ba2c3155d7](https://linux-hardware.org/?probe=ba2c3155d7) | Apr 22, 2020 |
| ASUSTek       | P9X79 WS                    | [513772febc](https://linux-hardware.org/?probe=513772febc) | Mar 01, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.4.0-48-generic           | 28       | 11.02%  |
| 5.4.0-52-generic           | 13       | 5.12%   |
| 5.4.0-47-generic           | 13       | 5.12%   |
| 5.4.0-42-generic           | 13       | 5.12%   |
| 5.4.0-94-generic           | 12       | 4.72%   |
| 5.4.0-45-generic           | 10       | 3.94%   |
| 5.4.0-65-generic           | 8        | 3.15%   |
| 5.4.0-40-generic           | 8        | 3.15%   |
| 5.4.0-66-generic           | 7        | 2.76%   |
| 5.4.0-67-generic           | 6        | 2.36%   |
| 5.11.0-40-generic          | 6        | 2.36%   |
| 5.4.0-80-generic           | 5        | 1.97%   |
| 5.4.0-29-generic           | 5        | 1.97%   |
| 5.8.0-55-generic           | 4        | 1.57%   |
| 5.4.0-89-generic           | 4        | 1.57%   |
| 5.4.0-74-generic           | 4        | 1.57%   |
| 5.4.0-56-generic           | 4        | 1.57%   |
| 5.4.0-33-generic           | 4        | 1.57%   |
| 5.8.0-59-generic           | 3        | 1.18%   |
| 5.4.0-90-generic           | 3        | 1.18%   |
| 5.4.0-88-generic           | 3        | 1.18%   |
| 5.4.0-81-generic           | 3        | 1.18%   |
| 5.4.0-77-generic           | 3        | 1.18%   |
| 5.4.0-72-generic           | 3        | 1.18%   |
| 5.4.0-62-generic           | 3        | 1.18%   |
| 5.4.0-59-generic           | 3        | 1.18%   |
| 5.4.0-58-generic           | 3        | 1.18%   |
| 5.4.0-26-generic           | 3        | 1.18%   |
| 5.13.0-35-generic          | 3        | 1.18%   |
| 5.13.0-27-generic          | 3        | 1.18%   |
| 5.8.0-53-generic           | 2        | 0.79%   |
| 5.4.0-73-generic           | 2        | 0.79%   |
| 5.4.0-70-generic           | 2        | 0.79%   |
| 5.4.0-60-generic           | 2        | 0.79%   |
| 5.4.0-51-generic           | 2        | 0.79%   |
| 5.4.0-37-generic           | 2        | 0.79%   |
| 5.4.0-34-generic           | 2        | 0.79%   |
| 5.4.0-100-generic          | 2        | 0.79%   |
| 5.11.0-43-generic          | 2        | 0.79%   |
| 5.11.0-34-generic          | 2        | 0.79%   |
| 5.11.0-25-generic          | 2        | 0.79%   |
| 5.8.0-57-generic           | 1        | 0.39%   |
| 5.8.0-54-generic           | 1        | 0.39%   |
| 5.8.0-50-generic           | 1        | 0.39%   |
| 5.8.0-48-generic           | 1        | 0.39%   |
| 5.8.0-45-generic           | 1        | 0.39%   |
| 5.8.0-43-generic           | 1        | 0.39%   |
| 5.8.0-41-generic           | 1        | 0.39%   |
| 5.8.0-40-generic           | 1        | 0.39%   |
| 5.7.6-050706-generic       | 1        | 0.39%   |
| 5.7.0-050700-generic       | 1        | 0.39%   |
| 5.4.0-99-generic           | 1        | 0.39%   |
| 5.4.0-97-generic           | 1        | 0.39%   |
| 5.4.0-91-generic           | 1        | 0.39%   |
| 5.4.0-86-generic           | 1        | 0.39%   |
| 5.4.0-702104061620-generic | 1        | 0.39%   |
| 5.4.0-64-generic           | 1        | 0.39%   |
| 5.4.0-53-lowlatency        | 1        | 0.39%   |
| 5.4.0-53-generic           | 1        | 0.39%   |
| 5.4.0-52-lowlatency        | 1        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 182      | 79.48%  |
| 5.11.0  | 18       | 7.86%   |
| 5.8.0   | 17       | 7.42%   |
| 5.13.0  | 6        | 2.62%   |
| 5.10.0  | 2        | 0.87%   |
| 5.7.6   | 1        | 0.44%   |
| 5.7.0   | 1        | 0.44%   |
| 5.16.0  | 1        | 0.44%   |
| 5.10.5  | 1        | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 182      | 79.48%  |
| 5.11    | 18       | 7.86%   |
| 5.8     | 17       | 7.42%   |
| 5.13    | 6        | 2.62%   |
| 5.10    | 3        | 1.31%   |
| 5.7     | 2        | 0.87%   |
| 5.16    | 1        | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 224      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 221      | 98.66%  |
| X-Cinnamon | 1        | 0.45%   |
| Trinity    | 1        | 0.45%   |
| GNOME      | 1        | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 217      | 96.44%  |
| Tty     | 7        | 3.11%   |
| Wayland | 1        | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 104      | 44.83%  |
| Unknown | 65       | 28.02%  |
| LightDM | 52       | 22.41%  |
| GDM     | 6        | 2.59%   |
| GDM3    | 3        | 1.29%   |
| SLiM    | 1        | 0.43%   |
| SDDM    | 1        | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| pt_BR | 55       | 24.44%  |
| en_US | 51       | 22.67%  |
| fr_FR | 16       | 7.11%   |
| el_GR | 16       | 7.11%   |
| de_DE | 16       | 7.11%   |
| en_GB | 11       | 4.89%   |
| en_CA | 10       | 4.44%   |
| ru_RU | 8        | 3.56%   |
| es_ES | 6        | 2.67%   |
| es_AR | 6        | 2.67%   |
| it_IT | 4        | 1.78%   |
| nl_NL | 3        | 1.33%   |
| en_AU | 3        | 1.33%   |
| pl_PL | 2        | 0.89%   |
| fi_FI | 2        | 0.89%   |
| de_CH | 2        | 0.89%   |
| cs_CZ | 2        | 0.89%   |
| sv_SE | 1        | 0.44%   |
| ja_JP | 1        | 0.44%   |
| hu_HU | 1        | 0.44%   |
| hr_HR | 1        | 0.44%   |
| eu_ES | 1        | 0.44%   |
| es_GT | 1        | 0.44%   |
| es_CL | 1        | 0.44%   |
| en_SG | 1        | 0.44%   |
| en_IN | 1        | 0.44%   |
| de_AT | 1        | 0.44%   |
| da_DK | 1        | 0.44%   |
| C     | 1        | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 146      | 64.32%  |
| EFI  | 81       | 35.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 207      | 92.41%  |
| Overlay | 12       | 5.36%   |
| Xfs     | 2        | 0.89%   |
| Zfs     | 1        | 0.45%   |
| ExX4    | 1        | 0.45%   |
| Btrfs   | 1        | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 79       | 34.8%   |
| Unknown | 76       | 33.48%  |
| GPT     | 72       | 31.72%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 196      | 87.11%  |
| Yes       | 29       | 12.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 152      | 66.96%  |
| Yes       | 75       | 33.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 51       | 22.77%  |
| Dell                | 42       | 18.75%  |
| Hewlett-Packard     | 35       | 15.63%  |
| Gigabyte Technology | 30       | 13.39%  |
| MSI                 | 18       | 8.04%   |
| ASRock              | 18       | 8.04%   |
| Intel               | 8        | 3.57%   |
| Lenovo              | 4        | 1.79%   |
| Pegatron            | 3        | 1.34%   |
| Medion              | 2        | 0.89%   |
| ECS                 | 2        | 0.89%   |
| Biostar             | 2        | 0.89%   |
| Unknown             | 2        | 0.89%   |
| Semp Toshiba        | 1        | 0.45%   |
| JINGSHA             | 1        | 0.45%   |
| IBM                 | 1        | 0.45%   |
| Gateway             | 1        | 0.45%   |
| Fujitsu Siemens     | 1        | 0.45%   |
| Albatron            | 1        | 0.45%   |
| Acer                | 1        | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| HP Compaq 6005 Pro SFF PC         | 8        | 3.57%   |
| HP Compaq Elite 8300 SFF          | 7        | 3.13%   |
| Dell OptiPlex 3010                | 5        | 2.23%   |
| ASUS All Series                   | 5        | 2.23%   |
| Dell OptiPlex GX520               | 4        | 1.79%   |
| Dell OptiPlex 390                 | 4        | 1.79%   |
| Dell OptiPlex 360                 | 4        | 1.79%   |
| HP Compaq 6200 Pro SFF PC         | 3        | 1.34%   |
| Dell OptiPlex 330                 | 3        | 1.34%   |
| ASUS M5A78L-M/USB3                | 3        | 1.34%   |
| ASRock B450M Pro4                 | 3        | 1.34%   |
| MSI MS-7680                       | 2        | 0.89%   |
| HP Compaq 8000 Elite SFF PC       | 2        | 0.89%   |
| HP Compaq 4000 Pro SFF PC         | 2        | 0.89%   |
| Gigabyte Z97-HD3                  | 2        | 0.89%   |
| Gigabyte B450M DS3H               | 2        | 0.89%   |
| Dell OptiPlex GX620               | 2        | 0.89%   |
| Dell OptiPlex 980                 | 2        | 0.89%   |
| Dell OptiPlex 780                 | 2        | 0.89%   |
| Dell OptiPlex 755                 | 2        | 0.89%   |
| Dell OptiPlex 380                 | 2        | 0.89%   |
| ASUS P8H61-M LX3 R2.0             | 2        | 0.89%   |
| ASUS M2N68-AM Plus                | 2        | 0.89%   |
| Unknown                           | 2        | 0.89%   |
| Semp Toshiba STI                  | 1        | 0.45%   |
| Pegatron VG271AA-ABF s5206fr      | 1        | 0.45%   |
| Pegatron FR484AA-UUW m9464sc      | 1        | 0.45%   |
| Pegatron Compaq dx7500 SFF        | 1        | 0.45%   |
| MSI MS-7C95                       | 1        | 0.45%   |
| MSI MS-7C94                       | 1        | 0.45%   |
| MSI MS-7C91                       | 1        | 0.45%   |
| MSI MS-7C84                       | 1        | 0.45%   |
| MSI MS-7C59                       | 1        | 0.45%   |
| MSI MS-7C35                       | 1        | 0.45%   |
| MSI MS-7B51                       | 1        | 0.45%   |
| MSI MS-7B49                       | 1        | 0.45%   |
| MSI MS-7B48                       | 1        | 0.45%   |
| MSI MS-7B18                       | 1        | 0.45%   |
| MSI MS-7B17                       | 1        | 0.45%   |
| MSI MS-7823                       | 1        | 0.45%   |
| MSI MS-7817                       | 1        | 0.45%   |
| MSI MS-7816                       | 1        | 0.45%   |
| MSI MS-7735                       | 1        | 0.45%   |
| MSI MS-7721                       | 1        | 0.45%   |
| Medion MD34440                    | 1        | 0.45%   |
| Medion MD34207/C746               | 1        | 0.45%   |
| Lenovo ThinkCentre M73 10B00013US | 1        | 0.45%   |
| Lenovo ThinkCentre M73 10AXS5W900 | 1        | 0.45%   |
| Lenovo ThinkCentre M58p 6234DJ1   | 1        | 0.45%   |
| Lenovo ThinkCentre A70 7844P8U    | 1        | 0.45%   |
| JINGSHA Board                     | 1        | 0.45%   |
| Intel SLIMBOOK                    | 1        | 0.45%   |
| Intel H61M-S1                     | 1        | 0.45%   |
| Intel DH87RL AAG74240-402         | 1        | 0.45%   |
| Intel DH61WW AAG23116-203         | 1        | 0.45%   |
| Intel DG43GT AAE62768-301         | 1        | 0.45%   |
| Intel DG31PR AAD97573-206         | 1        | 0.45%   |
| Intel D946GZIS AAD45436-306       | 1        | 0.45%   |
| Intel Board                       | 1        | 0.45%   |
| IBM 9210KGT                       | 1        | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 36       | 16.07%  |
| HP Compaq            | 27       | 12.05%  |
| ASUS PRIME           | 8        | 3.57%   |
| ASUS All             | 5        | 2.23%   |
| Lenovo ThinkCentre   | 4        | 1.79%   |
| ASUS M5A78L-M        | 4        | 1.79%   |
| ASUS M5A97           | 3        | 1.34%   |
| ASRock B450M         | 3        | 1.34%   |
| MSI MS-7680          | 2        | 0.89%   |
| HP ProDesk           | 2        | 0.89%   |
| Gigabyte Z97-HD3     | 2        | 0.89%   |
| Gigabyte X570        | 2        | 0.89%   |
| Gigabyte B450M       | 2        | 0.89%   |
| Gigabyte B450        | 2        | 0.89%   |
| Dell Precision       | 2        | 0.89%   |
| ASUS TUF             | 2        | 0.89%   |
| ASUS ROG             | 2        | 0.89%   |
| ASUS P9X79           | 2        | 0.89%   |
| ASUS P8H61-M         | 2        | 0.89%   |
| ASUS M2N68-AM        | 2        | 0.89%   |
| Unknown              | 2        | 0.89%   |
| Semp Toshiba STI     | 1        | 0.45%   |
| Pegatron VG271AA-ABF | 1        | 0.45%   |
| Pegatron FR484AA-UUW | 1        | 0.45%   |
| Pegatron Compaq      | 1        | 0.45%   |
| MSI MS-7C95          | 1        | 0.45%   |
| MSI MS-7C94          | 1        | 0.45%   |
| MSI MS-7C91          | 1        | 0.45%   |
| MSI MS-7C84          | 1        | 0.45%   |
| MSI MS-7C59          | 1        | 0.45%   |
| MSI MS-7C35          | 1        | 0.45%   |
| MSI MS-7B51          | 1        | 0.45%   |
| MSI MS-7B49          | 1        | 0.45%   |
| MSI MS-7B48          | 1        | 0.45%   |
| MSI MS-7B18          | 1        | 0.45%   |
| MSI MS-7B17          | 1        | 0.45%   |
| MSI MS-7823          | 1        | 0.45%   |
| MSI MS-7817          | 1        | 0.45%   |
| MSI MS-7816          | 1        | 0.45%   |
| MSI MS-7735          | 1        | 0.45%   |
| MSI MS-7721          | 1        | 0.45%   |
| Medion MD34440       | 1        | 0.45%   |
| Medion MD34207       | 1        | 0.45%   |
| JINGSHA Board        | 1        | 0.45%   |
| Intel SLIMBOOK       | 1        | 0.45%   |
| Intel H61M-S1        | 1        | 0.45%   |
| Intel DH87RL         | 1        | 0.45%   |
| Intel DH61WW         | 1        | 0.45%   |
| Intel DG43GT         | 1        | 0.45%   |
| Intel DG31PR         | 1        | 0.45%   |
| Intel D946GZIS       | 1        | 0.45%   |
| Intel Board          | 1        | 0.45%   |
| IBM 9210KGT          | 1        | 0.45%   |
| HP Z230              | 1        | 0.45%   |
| HP Z220              | 1        | 0.45%   |
| HP ProLiant          | 1        | 0.45%   |
| HP EliteDesk         | 1        | 0.45%   |
| HP Desktop           | 1        | 0.45%   |
| HP 550-142nf         | 1        | 0.45%   |
| Gigabyte Z77P-D3     | 1        | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 34       | 15.18%  |
| 2012 | 27       | 12.05%  |
| 2018 | 26       | 11.61%  |
| 2009 | 23       | 10.27%  |
| 2013 | 18       | 8.04%   |
| 2008 | 15       | 6.7%    |
| 2014 | 14       | 6.25%   |
| 2010 | 11       | 4.91%   |
| 2020 | 10       | 4.46%   |
| 2015 | 9        | 4.02%   |
| 2019 | 7        | 3.13%   |
| 2017 | 6        | 2.68%   |
| 2005 | 6        | 2.68%   |
| 2016 | 5        | 2.23%   |
| 2007 | 5        | 2.23%   |
| 2006 | 5        | 2.23%   |
| 2021 | 3        | 1.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 224      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 220      | 98.21%  |
| Enabled  | 4        | 1.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 224      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 73       | 32.44%  |
| 8.01-16.0       | 36       | 16%     |
| 16.01-24.0      | 33       | 14.67%  |
| 4.01-8.0        | 29       | 12.89%  |
| 32.01-64.0      | 23       | 10.22%  |
| 64.01-256.0     | 11       | 4.89%   |
| 1.01-2.0        | 9        | 4%      |
| 2.01-3.0        | 6        | 2.67%   |
| 24.01-32.0      | 4        | 1.78%   |
| More than 256.0 | 1        | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 79       | 32.92%  |
| 0.51-1.0   | 56       | 23.33%  |
| 2.01-3.0   | 42       | 17.5%   |
| 4.01-8.0   | 22       | 9.17%   |
| 3.01-4.0   | 22       | 9.17%   |
| 8.01-16.0  | 7        | 2.92%   |
| 0.01-0.5   | 7        | 2.92%   |
| 24.01-32.0 | 2        | 0.83%   |
| 16.01-24.0 | 2        | 0.83%   |
| 32.01-64.0 | 1        | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 121      | 52.61%  |
| 2      | 57       | 24.78%  |
| 3      | 25       | 10.87%  |
| 4      | 12       | 5.22%   |
| 5      | 4        | 1.74%   |
| 7      | 3        | 1.3%    |
| 10     | 2        | 0.87%   |
| 8      | 2        | 0.87%   |
| 6      | 2        | 0.87%   |
| 11     | 1        | 0.43%   |
| 0      | 1        | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 139      | 61.5%   |
| No        | 87       | 38.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 223      | 99.55%  |
| No        | 1        | 0.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 67.98%  |
| Yes       | 73       | 32.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 176      | 77.88%  |
| Yes       | 50       | 22.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Brazil      | 58       | 25.89%  |
| USA         | 26       | 11.61%  |
| Germany     | 19       | 8.48%   |
| Greece      | 17       | 7.59%   |
| France      | 15       | 6.7%    |
| UK          | 12       | 5.36%   |
| Spain       | 9        | 4.02%   |
| Canada      | 8        | 3.57%   |
| Argentina   | 8        | 3.57%   |
| Russia      | 7        | 3.13%   |
| Netherlands | 5        | 2.23%   |
| Czechia     | 5        | 2.23%   |
| Italy       | 4        | 1.79%   |
| Poland      | 3        | 1.34%   |
| Finland     | 3        | 1.34%   |
| Switzerland | 2        | 0.89%   |
| Japan       | 2        | 0.89%   |
| Bulgaria    | 2        | 0.89%   |
| Australia   | 2        | 0.89%   |
| Ukraine     | 1        | 0.45%   |
| Taiwan      | 1        | 0.45%   |
| Singapore   | 1        | 0.45%   |
| Romania     | 1        | 0.45%   |
| Mexico      | 1        | 0.45%   |
| India       | 1        | 0.45%   |
| Hungary     | 1        | 0.45%   |
| Hong Kong   | 1        | 0.45%   |
| Guatemala   | 1        | 0.45%   |
| Estonia     | 1        | 0.45%   |
| Denmark     | 1        | 0.45%   |
| Cyprus      | 1        | 0.45%   |
| Croatia     | 1        | 0.45%   |
| Chile       | 1        | 0.45%   |
| Belgium     | 1        | 0.45%   |
| Belarus     | 1        | 0.45%   |
| Austria     | 1        | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Sao Paulo                  | 24       | 10.39%  |
| JundiaГ­                 | 20       | 8.66%   |
| Old Faliron                | 11       | 4.76%   |
| Itatiba                    | 4        | 1.73%   |
| Thessaloniki               | 3        | 1.3%    |
| Manchester                 | 3        | 1.3%    |
| Yekaterinburg              | 2        | 0.87%   |
| WЕ‚ocЕ‚awek          | 2        | 0.87%   |
| Windsor                    | 2        | 0.87%   |
| Melbourne                  | 2        | 0.87%   |
| Kirchheim unter Teck       | 2        | 0.87%   |
| Karlsruhe                  | 2        | 0.87%   |
| Hamburg                    | 2        | 0.87%   |
| Florence                   | 2        | 0.87%   |
| Biysk                      | 2        | 0.87%   |
| Berlin                     | 2        | 0.87%   |
| Bagnoles-de-l'Orne         | 2        | 0.87%   |
| Zurich                     | 1        | 0.43%   |
| Zsaka                      | 1        | 0.43%   |
| Zagreb                     | 1        | 0.43%   |
| Worb                       | 1        | 0.43%   |
| Westbury                   | 1        | 0.43%   |
| Wejherowo                  | 1        | 0.43%   |
| Warren                     | 1        | 0.43%   |
| Village-Neuf               | 1        | 0.43%   |
| Vigo                       | 1        | 0.43%   |
| Vienna                     | 1        | 0.43%   |
| ViamГЈo                  | 1        | 0.43%   |
| Veliko Tarnovo             | 1        | 0.43%   |
| Varois-et-Chaignot         | 1        | 0.43%   |
| Valladolid                 | 1        | 0.43%   |
| Ushiku                     | 1        | 0.43%   |
| Urretxu                    | 1        | 0.43%   |
| Tremembe                   | 1        | 0.43%   |
| Torun                      | 1        | 0.43%   |
| Tilburg                    | 1        | 0.43%   |
| The Hague                  | 1        | 0.43%   |
| Thalfingen                 | 1        | 0.43%   |
| Terlizzi                   | 1        | 0.43%   |
| Tainan City                | 1        | 0.43%   |
| SГЈo JosГ© dos Pinhais | 1        | 0.43%   |
| Sunnyvale                  | 1        | 0.43%   |
| Sunderland                 | 1        | 0.43%   |
| Stezzano                   | 1        | 0.43%   |
| Spokane                    | 1        | 0.43%   |
| Sofia                      | 1        | 0.43%   |
| Smolensk                   | 1        | 0.43%   |
| Sehnde                     | 1        | 0.43%   |
| Secaucus                   | 1        | 0.43%   |
| Seattle                    | 1        | 0.43%   |
| Sao Goncalo                | 1        | 0.43%   |
| San Luis                   | 1        | 0.43%   |
| San Jose                   | 1        | 0.43%   |
| San Diego                  | 1        | 0.43%   |
| Saint-Laurent-sur-Gorre    | 1        | 0.43%   |
| Saint John                 | 1        | 0.43%   |
| Rotterdam                  | 1        | 0.43%   |
| Revda                      | 1        | 0.43%   |
| Reston                     | 1        | 0.43%   |
| Rakovnik                   | 1        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 91       | 131    | 26.38%  |
| Seagate                   | 81       | 129    | 23.48%  |
| Samsung Electronics       | 50       | 82     | 14.49%  |
| Kingston                  | 22       | 31     | 6.38%   |
| Toshiba                   | 12       | 24     | 3.48%   |
| SanDisk                   | 12       | 13     | 3.48%   |
| Hitachi                   | 12       | 15     | 3.48%   |
| Crucial                   | 8        | 12     | 2.32%   |
| Intel                     | 7        | 9      | 2.03%   |
| A-DATA Technology         | 6        | 6      | 1.74%   |
| Silicon Motion            | 4        | 5      | 1.16%   |
| PNY                       | 3        | 4      | 0.87%   |
| Patriot                   | 3        | 5      | 0.87%   |
| MAXTOR                    | 3        | 10     | 0.87%   |
| HGST                      | 3        | 5      | 0.87%   |
| Unknown                   | 2        | 2      | 0.58%   |
| Apacer                    | 2        | 2      | 0.58%   |
| USB3.0                    | 1        | 1      | 0.29%   |
| TO Exter                  | 1        | 1      | 0.29%   |
| SPCC                      | 1        | 1      | 0.29%   |
| SMI                       | 1        | 1      | 0.29%   |
| SK Hynix                  | 1        | 1      | 0.29%   |
| Phison                    | 1        | 1      | 0.29%   |
| Mushkin                   | 1        | 1      | 0.29%   |
| Micron/Crucial Technology | 1        | 2      | 0.29%   |
| Marlin                    | 1        | 1      | 0.29%   |
| Lexar                     | 1        | 1      | 0.29%   |
| Leven                     | 1        | 1      | 0.29%   |
| LDLC                      | 1        | 1      | 0.29%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.29%   |
| JMicron                   | 1        | 1      | 0.29%   |
| Intenso                   | 1        | 1      | 0.29%   |
| Inateck                   | 1        | 1      | 0.29%   |
| Hewlett-Packard           | 1        | 1      | 0.29%   |
| China                     | 1        | 1      | 0.29%   |
| ASMT109x                  | 1        | 2      | 0.29%   |
| ASMT                      | 1        | 2      | 0.29%   |
| AMD                       | 1        | 1      | 0.29%   |
| AGI                       | 1        | 2      | 0.29%   |
| addlink                   | 1        | 2      | 0.29%   |
| ADATA SP                  | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 13       | 3.27%   |
| WDC WD5000AAKX-083CA1 500GB          | 6        | 1.51%   |
| WDC WD5000AAKX-003CA0 500GB          | 6        | 1.51%   |
| Seagate ST3500418AS 500GB            | 6        | 1.51%   |
| Seagate ST1000DM010-2EP102 1TB       | 5        | 1.26%   |
| Samsung SSD 860 EVO 500GB            | 5        | 1.26%   |
| Samsung HD322HJ 320GB                | 5        | 1.26%   |
| Kingston SA400S37120G 120GB SSD      | 5        | 1.26%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4        | 1.01%   |
| Toshiba DT01ACA100 1TB               | 4        | 1.01%   |
| WDC WD2500AAKX-753CA1 250GB          | 3        | 0.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 3        | 0.75%   |
| WDC WD10EZEX-00BN5A0 1TB             | 3        | 0.75%   |
| Toshiba DT01ACA050 500GB             | 3        | 0.75%   |
| Seagate ST8000DM004-2CX188 8TB       | 3        | 0.75%   |
| Seagate ST3500630AS 500GB            | 3        | 0.75%   |
| Seagate ST3320620AS 320GB            | 3        | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB       | 3        | 0.75%   |
| Seagate ST2000DM001-9YN164 2TB       | 3        | 0.75%   |
| Seagate ST2000DM001-1ER164 2TB       | 3        | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB       | 3        | 0.75%   |
| Samsung SP2504C 250GB                | 3        | 0.75%   |
| Samsung NVMe SSD Drive 500GB         | 3        | 0.75%   |
| Samsung HD502HJ 500GB                | 3        | 0.75%   |
| Kingston SV300S37A120G 120GB SSD     | 3        | 0.75%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2        | 0.5%    |
| WDC WD5000AZLX-75K2TA0 500GB         | 2        | 0.5%    |
| WDC WD5000AAKX-08U6AA0 500GB         | 2        | 0.5%    |
| WDC WD3200AAKS-75L9A0 320GB          | 2        | 0.5%    |
| WDC WD20EARX-00PASB0 2TB             | 2        | 0.5%    |
| WDC WD10EZEX-08M2NA0 1TB             | 2        | 0.5%    |
| WDC WD10EARX-00N0YB0 1TB             | 2        | 0.5%    |
| Unknown SD/MMC/MS PRO 32GB           | 2        | 0.5%    |
| Seagate ST3500413AS 500GB            | 2        | 0.5%    |
| Seagate ST340212AS 40GB              | 2        | 0.5%    |
| Seagate ST31000528AS 1TB             | 2        | 0.5%    |
| Seagate Expansion 320GB              | 2        | 0.5%    |
| SanDisk SSD U100 16GB                | 2        | 0.5%    |
| SanDisk SSD PLUS 480GB               | 2        | 0.5%    |
| SanDisk SD8SB8U-256G-1006 256GB SSD  | 2        | 0.5%    |
| Samsung SSD 970 PRO 512GB            | 2        | 0.5%    |
| Samsung SSD 970 EVO Plus 250GB       | 2        | 0.5%    |
| Samsung SSD 970 EVO 500GB            | 2        | 0.5%    |
| Samsung SSD 870 EVO 1TB              | 2        | 0.5%    |
| Samsung SSD 860 EVO 2TB              | 2        | 0.5%    |
| Samsung MZ7LN128HCHP-000L1 128GB SSD | 2        | 0.5%    |
| Kingston SV300S37A240G 240GB SSD     | 2        | 0.5%    |
| Kingston SA400S37960G 960GB SSD      | 2        | 0.5%    |
| Kingston SA400S37240G 240GB SSD      | 2        | 0.5%    |
| Hitachi HDP725050GLA360 500GB        | 2        | 0.5%    |
| HGST HDN726040ALE614 4TB             | 2        | 0.5%    |
| Apacer AS350 128GB SSD               | 2        | 0.5%    |
| A-DATA SU650 120GB SSD               | 2        | 0.5%    |
| WDC WDS500G3X0C-00SJG0 500GB         | 1        | 0.25%   |
| WDC WDS500G2B0A 500GB SSD            | 1        | 0.25%   |
| WDC WDS500G1R0B-68A4Z0 500GB SSD     | 1        | 0.25%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1        | 0.25%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1        | 0.25%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.25%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1        | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 82       | 114    | 38.5%   |
| Seagate             | 80       | 128    | 37.56%  |
| Samsung Electronics | 19       | 20     | 8.92%   |
| Toshiba             | 12       | 24     | 5.63%   |
| Hitachi             | 12       | 15     | 5.63%   |
| HGST                | 3        | 5      | 1.41%   |
| Unknown             | 2        | 2      | 0.94%   |
| MAXTOR              | 2        | 7      | 0.94%   |
| ASMT109x            | 1        | 2      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 38     | 20.19%  |
| Kingston            | 19       | 23     | 18.27%  |
| SanDisk             | 12       | 13     | 11.54%  |
| WDC                 | 11       | 16     | 10.58%  |
| Crucial             | 8        | 12     | 7.69%   |
| A-DATA Technology   | 6        | 6      | 5.77%   |
| Intel               | 5        | 7      | 4.81%   |
| PNY                 | 3        | 4      | 2.88%   |
| Patriot             | 2        | 4      | 1.92%   |
| Apacer              | 2        | 2      | 1.92%   |
| USB3.0              | 1        | 1      | 0.96%   |
| TO Exter            | 1        | 1      | 0.96%   |
| SMI                 | 1        | 1      | 0.96%   |
| Seagate             | 1        | 1      | 0.96%   |
| Mushkin             | 1        | 1      | 0.96%   |
| MAXTOR              | 1        | 3      | 0.96%   |
| Lexar               | 1        | 1      | 0.96%   |
| Leven               | 1        | 1      | 0.96%   |
| LDLC                | 1        | 1      | 0.96%   |
| JMicron             | 1        | 1      | 0.96%   |
| Intenso             | 1        | 1      | 0.96%   |
| China               | 1        | 1      | 0.96%   |
| ASMT                | 1        | 2      | 0.96%   |
| AMD                 | 1        | 1      | 0.96%   |
| ADATA SP            | 1        | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 176      | 317    | 58.86%  |
| SSD     | 88       | 143    | 29.43%  |
| NVMe    | 32       | 50     | 10.7%   |
| Unknown | 3        | 4      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 213      | 447    | 82.56%  |
| NVMe | 32       | 50     | 12.4%   |
| SAS  | 13       | 17     | 5.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 171      | 264    | 58.76%  |
| 0.51-1.0   | 64       | 102    | 21.99%  |
| 1.01-2.0   | 31       | 43     | 10.65%  |
| 3.01-4.0   | 10       | 15     | 3.44%   |
| 4.01-10.0  | 9        | 24     | 3.09%   |
| 2.01-3.0   | 5        | 11     | 1.72%   |
| 10.01-20.0 | 1        | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 72       | 31.03%  |
| 101-250        | 40       | 17.24%  |
| 1001-2000      | 30       | 12.93%  |
| 501-1000       | 29       | 12.5%   |
| More than 3000 | 26       | 11.21%  |
| Unknown        | 10       | 4.31%   |
| 2001-3000      | 9        | 3.88%   |
| 1-20           | 7        | 3.02%   |
| 51-100         | 6        | 2.59%   |
| 21-50          | 3        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 78       | 32.91%  |
| 21-50          | 31       | 13.08%  |
| 101-250        | 31       | 13.08%  |
| 51-100         | 22       | 9.28%   |
| 251-500        | 20       | 8.44%   |
| 501-1000       | 15       | 6.33%   |
| 1001-2000      | 14       | 5.91%   |
| Unknown        | 10       | 4.22%   |
| 2001-3000      | 9        | 3.8%    |
| More than 3000 | 7        | 2.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 5        | 5      | 9.8%    |
| WDC WD5000AAKX-083CA1 500GB       | 4        | 4      | 7.84%   |
| WDC WD5000AAKX-003CA0 500GB       | 2        | 2      | 3.92%   |
| WDC WD2500AAKX-753CA1 250GB       | 2        | 2      | 3.92%   |
| Seagate ST3500418AS 500GB         | 2        | 2      | 3.92%   |
| Samsung Electronics HD502HJ 500GB | 2        | 2      | 3.92%   |
| WDC WD40EFAX-68JH4N0 4TB          | 1        | 1      | 1.96%   |
| WDC WD2500YS-01SHB1 256GB         | 1        | 1      | 1.96%   |
| WDC WD2500AAKX-75U6AA0 250GB      | 1        | 1      | 1.96%   |
| WDC WD2500AAJS-75M0A0 250GB       | 1        | 1      | 1.96%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 1        | 1      | 1.96%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 2      | 1.96%   |
| WDC WD15EADS-00P8B0 1TB           | 1        | 1      | 1.96%   |
| WDC WD1200JD-00HBB0 120GB         | 1        | 1      | 1.96%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 1      | 1.96%   |
| WDC WD10EFRX-68PJCN0 1TB          | 1        | 1      | 1.96%   |
| WDC WD10EARS-00MVWB0 1TB          | 1        | 1      | 1.96%   |
| Toshiba MK5055GSX 500GB           | 1        | 1      | 1.96%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 1.96%   |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 1      | 1.96%   |
| Seagate ST3750525AS 752GB         | 1        | 1      | 1.96%   |
| Seagate ST3500320AS 500GB         | 1        | 1      | 1.96%   |
| Seagate ST3402111AS 40GB          | 1        | 1      | 1.96%   |
| Seagate ST3360320AS 360GB         | 1        | 2      | 1.96%   |
| Seagate ST3320620AS 320GB         | 1        | 1      | 1.96%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 1.96%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 1.96%   |
| Seagate ST32000644NS 2TB          | 1        | 1      | 1.96%   |
| Seagate ST31000333AS 1TB          | 1        | 1      | 1.96%   |
| Seagate ST2000DM001-9YN164 2TB    | 1        | 2      | 1.96%   |
| Seagate ST1000DM003-1CH162 1TB    | 1        | 1      | 1.96%   |
| SanDisk SSD PLUS 480GB            | 1        | 1      | 1.96%   |
| Samsung Electronics SP2504C 250GB | 1        | 1      | 1.96%   |
| MAXTOR 6Y160M0 160GB              | 1        | 1      | 1.96%   |
| Kingston SHPM2280P2H 240G SSD     | 1        | 1      | 1.96%   |
| Intel SSDSA2M080G2GC 80GB         | 1        | 1      | 1.96%   |
| Hitachi HDT721050SLA360 500GB     | 1        | 1      | 1.96%   |
| HGST HDN726040ALE614 4TB          | 1        | 2      | 1.96%   |
| Crucial CT1050MX300SSD1 1050GB    | 1        | 1      | 1.96%   |
| ASMT USB 3.0 Destop H 1TB SSD     | 1        | 2      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 21     | 38%     |
| WDC                 | 18       | 20     | 36%     |
| Samsung Electronics | 3        | 3      | 6%      |
| Toshiba             | 2        | 2      | 4%      |
| SanDisk             | 1        | 1      | 2%      |
| MAXTOR              | 1        | 1      | 2%      |
| Kingston            | 1        | 1      | 2%      |
| Intel               | 1        | 1      | 2%      |
| Hitachi             | 1        | 1      | 2%      |
| HGST                | 1        | 2      | 2%      |
| Crucial             | 1        | 1      | 2%      |
| ASMT                | 1        | 2      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 21     | 42.22%  |
| WDC                 | 18       | 20     | 40%     |
| Samsung Electronics | 3        | 3      | 6.67%   |
| Toshiba             | 2        | 2      | 4.44%   |
| MAXTOR              | 1        | 1      | 2.22%   |
| Hitachi             | 1        | 1      | 2.22%   |
| HGST                | 1        | 2      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 42       | 50     | 91.3%   |
| SSD  | 4        | 6      | 8.7%    |

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
| Works    | 126      | 245    | 50.2%   |
| Detected | 81       | 213    | 32.27%  |
| Malfunc  | 44       | 56     | 17.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 152      | 54.09%  |
| AMD                           | 63       | 22.42%  |
| Samsung Electronics           | 13       | 4.63%   |
| Marvell Technology Group      | 11       | 3.91%   |
| ASMedia Technology            | 9        | 3.2%    |
| Nvidia                        | 8        | 2.85%   |
| Silicon Motion                | 6        | 2.14%   |
| Kingston Technology Company   | 5        | 1.78%   |
| Phison Electronics            | 3        | 1.07%   |
| JMicron Technology            | 3        | 1.07%   |
| VIA Technologies              | 1        | 0.36%   |
| SK Hynix                      | 1        | 0.36%   |
| Sandisk                       | 1        | 0.36%   |
| Micron/Crucial Technology     | 1        | 0.36%   |
| LSI Logic / Symbios Logic     | 1        | 0.36%   |
| KIOXIA                        | 1        | 0.36%   |
| Integrated Technology Express | 1        | 0.36%   |
| Hewlett-Packard               | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 7.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26       | 7.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 23       | 6.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20       | 5.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17       | 4.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 4.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14       | 3.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 3.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 13       | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 3.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 2.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 2.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 2.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 2.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 1.89%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 1.62%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 1.62%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.35%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 1.08%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.08%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 1.08%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.81%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.81%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.81%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.54%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.54%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.54%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 2        | 0.54%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2        | 0.54%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.54%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.54%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.54%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.54%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.54%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.54%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.54%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.54%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.54%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.27%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.27%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.27%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.27%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.27%   |
| Nvidia MCP79 AHCI Controller                                                            | 1        | 0.27%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                                 | 1        | 0.27%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.27%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.27%   |
| Nvidia MCP51 IDE                                                                        | 1        | 0.27%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 167      | 58.19%  |
| IDE  | 79       | 27.53%  |
| NVMe | 31       | 10.8%   |
| RAID | 7        | 2.44%   |
| SAS  | 3        | 1.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 155      | 69.2%   |
| AMD    | 69       | 30.8%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 9        | 4.02%   |
| AMD Phenom II X4 B97 Processor              | 7        | 3.13%   |
| Intel Pentium 4 CPU 3.00GHz                 | 5        | 2.23%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 5        | 2.23%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 5        | 2.23%   |
| Intel Pentium D CPU 2.80GHz                 | 4        | 1.79%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 4        | 1.79%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 4        | 1.79%   |
| AMD FX-8350 Eight-Core Processor            | 4        | 1.79%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 3        | 1.34%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 1.34%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 1.34%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.34%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1.34%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 3        | 1.34%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 1.34%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.34%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.34%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 3        | 1.34%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.34%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.34%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.34%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 2        | 0.89%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 0.89%   |
| Intel Core i7-4790S CPU @ 3.20GHz           | 2        | 0.89%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.89%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.89%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.89%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 0.89%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.89%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.89%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 0.89%   |
| Intel Celeron CPU E1400 @ 2.00GHz           | 2        | 0.89%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 2        | 0.89%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 0.89%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.89%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 0.89%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 0.89%   |
| AMD FX-6300 Six-Core Processor              | 2        | 0.89%   |
| AMD Athlon II X2 215 Processor              | 2        | 0.89%   |
| Intel Xeon E-2126G CPU @ 3.30GHz            | 1        | 0.45%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.45%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.45%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz         | 1        | 0.45%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 0.45%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.45%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.45%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.45%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.45%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.45%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.45%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 0.45%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 0.45%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.45%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.45%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.45%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.45%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.45%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 44       | 19.64%  |
| Intel Core i3           | 25       | 11.16%  |
| Intel Core i7           | 19       | 8.48%   |
| Intel Core 2 Duo        | 15       | 6.7%    |
| AMD FX                  | 12       | 5.36%   |
| AMD Phenom II X4        | 11       | 4.91%   |
| AMD Ryzen 5             | 10       | 4.46%   |
| Intel Core 2 Quad       | 9        | 4.02%   |
| AMD Ryzen 7             | 9        | 4.02%   |
| Intel Xeon              | 8        | 3.57%   |
| Intel Pentium           | 7        | 3.13%   |
| Intel Celeron           | 7        | 3.13%   |
| AMD Athlon II X2        | 7        | 3.13%   |
| Intel Pentium 4         | 5        | 2.23%   |
| Intel Pentium Dual-Core | 4        | 1.79%   |
| Intel Pentium D         | 4        | 1.79%   |
| AMD Ryzen 9             | 4        | 1.79%   |
| Other                   | 3        | 1.34%   |
| Intel Core 2            | 3        | 1.34%   |
| Intel Pentium Dual      | 2        | 0.89%   |
| AMD Ryzen Threadripper  | 2        | 0.89%   |
| AMD Ryzen 3             | 2        | 0.89%   |
| AMD Athlon              | 2        | 0.89%   |
| AMD A8                  | 2        | 0.89%   |
| Intel Core i9           | 1        | 0.45%   |
| Intel Atom              | 1        | 0.45%   |
| AMD Turion II Neo       | 1        | 0.45%   |
| AMD Ryzen 3 PRO         | 1        | 0.45%   |
| AMD Phenom II X6        | 1        | 0.45%   |
| AMD Athlon 64 X2        | 1        | 0.45%   |
| AMD A4                  | 1        | 0.45%   |
| AMD A10                 | 1        | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 93       | 41.52%  |
| 2      | 77       | 34.38%  |
| 6      | 24       | 10.71%  |
| 8      | 11       | 4.91%   |
| 1      | 7        | 3.13%   |
| 16     | 5        | 2.23%   |
| 3      | 3        | 1.34%   |
| 24     | 2        | 0.89%   |
| 12     | 2        | 0.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 221      | 98.66%  |
| 2      | 3        | 1.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 123      | 54.67%  |
| 2      | 102      | 45.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 224      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 24       | 10.62%  |
| 0x306c3    | 22       | 9.73%   |
| 0x206a7    | 19       | 8.41%   |
| Unknown    | 16       | 7.08%   |
| 0x1067a    | 15       | 6.64%   |
| 0x010000c8 | 13       | 5.75%   |
| 0x08701021 | 8        | 3.54%   |
| 0x6fb      | 7        | 3.1%    |
| 0x06000852 | 7        | 3.1%    |
| 0x906ea    | 6        | 2.65%   |
| 0x6fd      | 6        | 2.65%   |
| 0xf41      | 4        | 1.77%   |
| 0xa0653    | 4        | 1.77%   |
| 0x906e9    | 4        | 1.77%   |
| 0x206d7    | 4        | 1.77%   |
| 0x08701013 | 4        | 1.77%   |
| 0x0800820d | 4        | 1.77%   |
| 0xf47      | 3        | 1.33%   |
| 0x6f6      | 3        | 1.33%   |
| 0x506e3    | 3        | 1.33%   |
| 0x106e5    | 3        | 1.33%   |
| 0x0810100b | 3        | 1.33%   |
| 0x06001119 | 3        | 1.33%   |
| 0x010000db | 3        | 1.33%   |
| 0x906ed    | 2        | 0.88%   |
| 0x906eb    | 2        | 0.88%   |
| 0x30678    | 2        | 0.88%   |
| 0x20655    | 2        | 0.88%   |
| 0x10676    | 2        | 0.88%   |
| 0x0600063e | 2        | 0.88%   |
| 0xf62      | 1        | 0.44%   |
| 0xf43      | 1        | 0.44%   |
| 0xa0671    | 1        | 0.44%   |
| 0x906ec    | 1        | 0.44%   |
| 0x806ea    | 1        | 0.44%   |
| 0x306f2    | 1        | 0.44%   |
| 0x306e4    | 1        | 0.44%   |
| 0x206d6    | 1        | 0.44%   |
| 0x106c2    | 1        | 0.44%   |
| 0x106a5    | 1        | 0.44%   |
| 0x10677    | 1        | 0.44%   |
| 0x0a201016 | 1        | 0.44%   |
| 0x0a201009 | 1        | 0.44%   |
| 0x08600106 | 1        | 0.44%   |
| 0x08301039 | 1        | 0.44%   |
| 0x08108109 | 1        | 0.44%   |
| 0x08101102 | 1        | 0.44%   |
| 0x08101016 | 1        | 0.44%   |
| 0x08101013 | 1        | 0.44%   |
| 0x08001138 | 1        | 0.44%   |
| 0x08001137 | 1        | 0.44%   |
| 0x0600611a | 1        | 0.44%   |
| 0x06003106 | 1        | 0.44%   |
| 0x0600081f | 1        | 0.44%   |
| 0x010000dc | 1        | 0.44%   |
| 0x010000c7 | 1        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 26       | 11.61%  |
| IvyBridge   | 25       | 11.16%  |
| Haswell     | 24       | 10.71%  |
| K10         | 21       | 9.38%   |
| Penryn      | 20       | 8.93%   |
| KabyLake    | 17       | 7.59%   |
| Core        | 16       | 7.14%   |
| Zen 2       | 14       | 6.25%   |
| Piledriver  | 13       | 5.8%    |
| NetBurst    | 9        | 4.02%   |
| Zen         | 8        | 3.57%   |
| Zen+        | 5        | 2.23%   |
| Skylake     | 4        | 1.79%   |
| Nehalem     | 4        | 1.79%   |
| CometLake   | 4        | 1.79%   |
| Zen 3       | 2        | 0.89%   |
| Westmere    | 2        | 0.89%   |
| Silvermont  | 2        | 0.89%   |
| Bulldozer   | 2        | 0.89%   |
| Steamroller | 1        | 0.45%   |
| K8 Hammer   | 1        | 0.45%   |
| Jaguar      | 1        | 0.45%   |
| Icelake     | 1        | 0.45%   |
| Excavator   | 1        | 0.45%   |
| Bonnell     | 1        | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 96       | 40.51%  |
| Nvidia            | 70       | 29.54%  |
| AMD               | 70       | 29.54%  |
| ASPEED Technology | 1        | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 17       | 7.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15       | 6.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 13       | 5.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 4.58%   |
| AMD RS880 [Radeon HD 4200]                                                  | 10       | 4.17%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 8        | 3.33%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 8        | 3.33%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 2.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 2.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 2.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.67%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.67%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.25%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.25%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.25%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 3        | 1.25%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 1.25%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.83%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 0.83%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 0.83%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 2        | 0.83%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 0.83%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 0.83%   |
| Intel HD Graphics 630                                                       | 2        | 0.83%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 0.83%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 0.83%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 0.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 0.83%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 0.83%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 0.83%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 0.83%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2        | 0.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.42%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.42%   |
| Nvidia TU104GL [Quadro RTX 4000]                                            | 1        | 0.42%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.42%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.42%   |
| Nvidia NV44 [GeForce 6200 SE TurboCache]                                    | 1        | 0.42%   |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.42%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.42%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 0.42%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.42%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.42%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.42%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.42%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.42%   |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 0.42%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.42%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.42%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.42%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.42%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 86       | 38.22%  |
| 1 x AMD        | 67       | 29.78%  |
| 1 x Nvidia     | 63       | 28%     |
| Intel + Nvidia | 5        | 2.22%   |
| 2 x Nvidia     | 1        | 0.44%   |
| 2 x AMD        | 1        | 0.44%   |
| Intel + AMD    | 1        | 0.44%   |
| 1 x ASPEED     | 1        | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 173      | 76.21%  |
| Proprietary | 50       | 22.03%  |
| Unknown     | 4        | 1.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 100      | 43.86%  |
| 0.01-0.5   | 35       | 15.35%  |
| 1.01-2.0   | 30       | 13.16%  |
| 0.51-1.0   | 28       | 12.28%  |
| 7.01-8.0   | 15       | 6.58%   |
| 3.01-4.0   | 15       | 6.58%   |
| 5.01-6.0   | 4        | 1.75%   |
| 2.01-3.0   | 1        | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 61       | 25.63%  |
| Samsung Electronics  | 36       | 15.13%  |
| Goldstar             | 22       | 9.24%   |
| Philips              | 13       | 5.46%   |
| Hewlett-Packard      | 13       | 5.46%   |
| BenQ                 | 13       | 5.46%   |
| Ancor Communications | 10       | 4.2%    |
| Acer                 | 9        | 3.78%   |
| AOC                  | 8        | 3.36%   |
| ViewSonic            | 7        | 2.94%   |
| Unknown              | 7        | 2.94%   |
| Lenovo               | 3        | 1.26%   |
| HannStar             | 3        | 1.26%   |
| Vestel Elektronik    | 2        | 0.84%   |
| Toshiba              | 2        | 0.84%   |
| NEC Computers        | 2        | 0.84%   |
| LG Electronics       | 2        | 0.84%   |
| Iiyama               | 2        | 0.84%   |
| Gateway              | 2        | 0.84%   |
| Belinea              | 2        | 0.84%   |
| Vizio                | 1        | 0.42%   |
| VIZ                  | 1        | 0.42%   |
| Targa                | 1        | 0.42%   |
| Sony                 | 1        | 0.42%   |
| Seiki                | 1        | 0.42%   |
| Sceptre Tech         | 1        | 0.42%   |
| Sceptre              | 1        | 0.42%   |
| RTK                  | 1        | 0.42%   |
| ROW                  | 1        | 0.42%   |
| Packard Bell         | 1        | 0.42%   |
| Onkyo                | 1        | 0.42%   |
| Medion               | 1        | 0.42%   |
| Insignia             | 1        | 0.42%   |
| Hitachi              | 1        | 0.42%   |
| Fujitsu Siemens      | 1        | 0.42%   |
| Element              | 1        | 0.42%   |
| Eizo                 | 1        | 0.42%   |
| Daewoo               | 1        | 0.42%   |
| Compal               | 1        | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 31       | 12.11%  |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                    | 5        | 1.95%   |
| ViewSonic VA703-4Series VSC6A1E 1280x1024 341x274mm 17.2-inch        | 4        | 1.56%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                     | 3        | 1.17%   |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                    | 3        | 1.17%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                        | 2        | 0.78%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 2        | 0.78%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                    | 2        | 0.78%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 600x340mm 27.2-inch              | 2        | 0.78%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2        | 0.78%   |
| Goldstar W2253 GSM56DB 1920x1080 474x296mm 22.0-inch                 | 2        | 0.78%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2        | 0.78%   |
| Goldstar E2340 GSM57A6 1920x1080 510x290mm 23.1-inch                 | 2        | 0.78%   |
| Goldstar 23LC1R GSM5617 1360x768 930x523mm 42.0-inch                 | 2        | 0.78%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 0.78%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                     | 2        | 0.78%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 2        | 0.78%   |
| Vizio VO320E VIZ0035 1366x768 700x390mm 31.5-inch                    | 1        | 0.39%   |
| VIZ LCD Monitor E322VL 1920x1080                                     | 1        | 0.39%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch              | 1        | 0.39%   |
| ViewSonic VE902m VSC491B 1280x1024 376x301mm 19.0-inch               | 1        | 0.39%   |
| ViewSonic VE710s VSCF518 1280x1024 338x270mm 17.0-inch               | 1        | 0.39%   |
| Unknown LCD Monitor Sony SDM-X82 1280x1024                           | 1        | 0.39%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 1        | 0.39%   |
| Unknown LCD Monitor SAMSUNG 1360x768                                 | 1        | 0.39%   |
| Unknown LCD Monitor PHILIPS FTV 1360x768                             | 1        | 0.39%   |
| Unknown LCD Monitor FormacTFT2010 1600x1200                          | 1        | 0.39%   |
| Unknown LCD Monitor ELE E4SW5017RKU                                  | 1        | 0.39%   |
| Unknown LCD Monitor CHHWJT 1920x1080                                 | 1        | 0.39%   |
| Toshiba TV TSB2017 3840x2160                                         | 1        | 0.39%   |
| Toshiba 50UHD_LCD_TV TSB3700 1920x1080 1360x768mm 61.5-inch          | 1        | 0.39%   |
| Targa LCD Monitor LCDTV16                                            | 1        | 0.39%   |
| Sony TV SNYEE01 1920x1080                                            | 1        | 0.39%   |
| Seiki SE19HY10 SEK1920 1366x768 410x230mm 18.5-inch                  | 1        | 0.39%   |
| Sceptre Tech Sceptre X24WG SPT2401 1920x1200 518x324mm 24.1-inch     | 1        | 0.39%   |
| Sceptre Tech Sceptre C27 SPT0AD7 1920x1080 600x340mm 27.2-inch       | 1        | 0.39%   |
| Sceptre LCD Monitor X24WG 3840x1200                                  | 1        | 0.39%   |
| Sceptre LCD Monitor X24WG                                            | 1        | 0.39%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch    | 1        | 0.39%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1        | 0.39%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch    | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 338x270mm 17.0-inch | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch | 1        | 0.39%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch   | 1        | 0.39%   |
| Samsung Electronics SMB2270HD SAM070C 1920x1080 476x268mm 21.5-inch  | 1        | 0.39%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch   | 1        | 0.39%   |
| Samsung Electronics S27E330 SAM0D90 1920x1080 598x336mm 27.0-inch    | 1        | 0.39%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch    | 1        | 0.39%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1        | 0.39%   |
| Samsung Electronics S24D390 SAM0B64 1920x1080 521x293mm 23.5-inch    | 1        | 0.39%   |
| Samsung Electronics S24B350 SAM08D9 1920x1080 531x299mm 24.0-inch    | 1        | 0.39%   |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch    | 1        | 0.39%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch    | 1        | 0.39%   |
| Samsung Electronics S19F355 SAM0E79 1366x768 410x230mm 18.5-inch     | 1        | 0.39%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 1        | 0.39%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                 | 1        | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 76       | 32.07%  |
| 1280x1024 (SXGA)   | 58       | 24.47%  |
| 3840x2160 (4K)     | 18       | 7.59%   |
| 1366x768 (WXGA)    | 18       | 7.59%   |
| 1440x900 (WXGA+)   | 13       | 5.49%   |
| 1360x768           | 12       | 5.06%   |
| 1680x1050 (WSXGA+) | 9        | 3.8%    |
| Unknown            | 7        | 2.95%   |
| 2560x1440 (QHD)    | 6        | 2.53%   |
| 1920x1200 (WUXGA)  | 4        | 1.69%   |
| 1600x1200          | 3        | 1.27%   |
| 3440x1440          | 2        | 0.84%   |
| 1600x900 (HD+)     | 2        | 0.84%   |
| 6400x1080          | 1        | 0.42%   |
| 5040x1050          | 1        | 0.42%   |
| 4240x1440          | 1        | 0.42%   |
| 3840x1200          | 1        | 0.42%   |
| 3840x1080          | 1        | 0.42%   |
| 3000x1920          | 1        | 0.42%   |
| 2640x1024          | 1        | 0.42%   |
| 1152x864           | 1        | 0.42%   |
| 1024x768 (XGA)     | 1        | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 52       | 21.67%  |
| Unknown | 29       | 12.08%  |
| 24      | 22       | 9.17%   |
| 21      | 21       | 8.75%   |
| 23      | 19       | 7.92%   |
| 18      | 18       | 7.5%    |
| 27      | 15       | 6.25%   |
| 19      | 12       | 5%      |
| 15      | 11       | 4.58%   |
| 22      | 10       | 4.17%   |
| 84      | 6        | 2.5%    |
| 31      | 6        | 2.5%    |
| 72      | 4        | 1.67%   |
| 20      | 3        | 1.25%   |
| 42      | 2        | 0.83%   |
| 40      | 2        | 0.83%   |
| 33      | 2        | 0.83%   |
| 32      | 2        | 0.83%   |
| 52      | 1        | 0.42%   |
| 46      | 1        | 0.42%   |
| 36      | 1        | 0.42%   |
| 34      | 1        | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 301-350     | 60       | 25.64%  |
| 401-500     | 55       | 23.5%   |
| 501-600     | 51       | 21.79%  |
| Unknown     | 29       | 12.39%  |
| 1501-2000   | 10       | 4.27%   |
| 351-400     | 9        | 3.85%   |
| 601-700     | 8        | 3.42%   |
| 701-800     | 6        | 2.56%   |
| 801-900     | 2        | 0.85%   |
| 1001-1500   | 2        | 0.85%   |
| 901-1000    | 2        | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 108      | 48%     |
| 5/4     | 50       | 22.22%  |
| 16/10   | 28       | 12.44%  |
| Unknown | 26       | 11.56%  |
| 4/3     | 6        | 2.67%   |
| 6/5     | 4        | 1.78%   |
| 3/2     | 2        | 0.89%   |
| 21/9    | 1        | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 64       | 27.23%  |
| 201-250        | 53       | 22.55%  |
| Unknown        | 29       | 12.34%  |
| 151-200        | 25       | 10.64%  |
| 301-350        | 15       | 6.38%   |
| More than 1000 | 11       | 4.68%   |
| 351-500        | 10       | 4.26%   |
| 251-300        | 8        | 3.4%    |
| 101-110        | 8        | 3.4%    |
| 501-1000       | 6        | 2.55%   |
| 131-140        | 3        | 1.28%   |
| 111-120        | 3        | 1.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 149      | 65.64%  |
| 101-120 | 33       | 14.54%  |
| Unknown | 29       | 12.78%  |
| 1-50    | 9        | 3.96%   |
| 121-160 | 5        | 2.2%    |
| 161-240 | 2        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 187      | 82.74%  |
| 2     | 31       | 13.72%  |
| 0     | 5        | 2.21%   |
| 3     | 3        | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 119      | 40.61%  |
| Intel                           | 85       | 29.01%  |
| Broadcom                        | 25       | 8.53%   |
| Qualcomm Atheros                | 12       | 4.1%    |
| Ralink Technology               | 7        | 2.39%   |
| Nvidia                          | 7        | 2.39%   |
| TP-Link                         | 5        | 1.71%   |
| Ralink                          | 5        | 1.71%   |
| Edimax Technology               | 3        | 1.02%   |
| Broadcom Limited                | 3        | 1.02%   |
| ASUSTek Computer                | 3        | 1.02%   |
| Aquantia                        | 3        | 1.02%   |
| Xiaomi                          | 2        | 0.68%   |
| Qualcomm Atheros Communications | 2        | 0.68%   |
| Linksys                         | 2        | 0.68%   |
| D-Link System                   | 2        | 0.68%   |
| ASIX Electronics                | 2        | 0.68%   |
| ZyDAS                           | 1        | 0.34%   |
| Sitecom Europe                  | 1        | 0.34%   |
| Samsung Electronics             | 1        | 0.34%   |
| NetGear                         | 1        | 0.34%   |
| MediaTek                        | 1        | 0.34%   |
| Marvell Technology Group        | 1        | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 100      | 30.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 20       | 6.17%   |
| Intel I211 Gigabit Network Connection                              | 11       | 3.4%    |
| Intel Wi-Fi 6 AX200                                                | 8        | 2.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 8        | 2.47%   |
| Realtek RTL8125 2.5GbE Controller                                  | 7        | 2.16%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express            | 6        | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 5        | 1.54%   |
| Nvidia MCP61 Ethernet                                              | 5        | 1.54%   |
| Intel Ethernet Connection I217-V                                   | 5        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                               | 5        | 1.54%   |
| Intel 82579V Gigabit Network Connection                            | 5        | 1.54%   |
| Intel 82574L Gigabit Network Connection                            | 5        | 1.54%   |
| Intel 82567LM-3 Gigabit Network Connection                         | 5        | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 4        | 1.23%   |
| Intel Ethernet Connection (2) I219-V                               | 4        | 1.23%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                    | 4        | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 3        | 0.93%   |
| Ralink MT7601U Wireless Adapter                                    | 3        | 0.93%   |
| Intel Ethernet Connection I217-LM                                  | 3        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 3        | 0.93%   |
| Intel 82578DM Gigabit Network Connection                           | 3        | 0.93%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express      | 3        | 0.93%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]  | 3        | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 2        | 0.62%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 2        | 0.62%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 2        | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                    | 2        | 0.62%   |
| Ralink RT5370 Wireless Adapter                                     | 2        | 0.62%   |
| Ralink RT2561/RT61 rev B 802.11g                                   | 2        | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                    | 2        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 2        | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet     | 2        | 0.62%   |
| Intel Wireless-AC 9260                                             | 2        | 0.62%   |
| Intel Wireless 7260                                                | 2        | 0.62%   |
| Intel 82567V-4 Gigabit Network Connection                          | 2        | 0.62%   |
| Intel 82567V-2 Gigabit Network Connection                          | 2        | 0.62%   |
| Edimax 802.11n WLAN Adapter                                        | 2        | 0.62%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                    | 2        | 0.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                    | 2        | 0.62%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 2        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                      | 2        | 0.62%   |
| ZyDAS ZD1211B 802.11g                                              | 1        | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                     | 1        | 0.31%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                  | 1        | 0.31%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                              | 1        | 0.31%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                          | 1        | 0.31%   |
| TP-Link 802.11n NIC                                                | 1        | 0.31%   |
| Sitecom Europe 802.11n WLAN Adapter                                | 1        | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                      | 1        | 0.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1        | 0.31%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter           | 1        | 0.31%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                | 1        | 0.31%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 1        | 0.31%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 1        | 0.31%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1        | 0.31%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 1        | 0.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 1        | 0.31%   |
| Realtek RTL8187 Wireless Adapter                                   | 1        | 0.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 1        | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 21       | 27.27%  |
| Intel                           | 19       | 24.68%  |
| Ralink Technology               | 7        | 9.09%   |
| TP-Link                         | 5        | 6.49%   |
| Ralink                          | 5        | 6.49%   |
| Qualcomm Atheros                | 4        | 5.19%   |
| Edimax Technology               | 3        | 3.9%    |
| ASUSTek Computer                | 3        | 3.9%    |
| Qualcomm Atheros Communications | 2        | 2.6%    |
| Linksys                         | 2        | 2.6%    |
| ZyDAS                           | 1        | 1.3%    |
| Xiaomi                          | 1        | 1.3%    |
| Sitecom Europe                  | 1        | 1.3%    |
| NetGear                         | 1        | 1.3%    |
| MediaTek                        | 1        | 1.3%    |
| Broadcom                        | 1        | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 8        | 10.39%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 4        | 5.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 3        | 3.9%    |
| Ralink MT7601U Wireless Adapter                                           | 3        | 3.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 3        | 3.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 2        | 2.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 2        | 2.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                           | 2        | 2.6%    |
| Ralink RT5370 Wireless Adapter                                            | 2        | 2.6%    |
| Ralink RT2561/RT61 rev B 802.11g                                          | 2        | 2.6%    |
| Qualcomm Atheros AR9271 802.11n                                           | 2        | 2.6%    |
| Intel Wireless-AC 9260                                                    | 2        | 2.6%    |
| Intel Wireless 7260                                                       | 2        | 2.6%    |
| Edimax 802.11n WLAN Adapter                                               | 2        | 2.6%    |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]        | 2        | 2.6%    |
| ZyDAS ZD1211B 802.11g                                                     | 1        | 1.3%    |
| Xiaomi MediaTek MT7601U [MI WiFi]                                         | 1        | 1.3%    |
| TP-Link RTL8812AU Archer T4U 802.11ac                                     | 1        | 1.3%    |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                 | 1        | 1.3%    |
| TP-Link 802.11n NIC                                                       | 1        | 1.3%    |
| Sitecom Europe 802.11n WLAN Adapter                                       | 1        | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 1        | 1.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                  | 1        | 1.3%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1        | 1.3%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                           | 1        | 1.3%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.3%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                   | 1        | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1        | 1.3%    |
| Realtek RTL8187 Wireless Adapter                                          | 1        | 1.3%    |
| Realtek 802.11n                                                           | 1        | 1.3%    |
| Ralink RT5572 Wireless Adapter                                            | 1        | 1.3%    |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1        | 1.3%    |
| Ralink RT5360 Wireless 802.11n 1T/1R                                      | 1        | 1.3%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                      | 1        | 1.3%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 1        | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 1        | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1        | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1        | 1.3%    |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.3%    |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                        | 1        | 1.3%    |
| Linksys WUSB6400M                                                         | 1        | 1.3%    |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]             | 1        | 1.3%    |
| Intel Wireless 7265                                                       | 1        | 1.3%    |
| Intel Wireless 3165                                                       | 1        | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 1        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                           | 1        | 1.3%    |
| Edimax AC600 USB                                                          | 1        | 1.3%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                        | 1        | 1.3%    |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                 | 1        | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 112      | 47.06%  |
| Intel                    | 74       | 31.09%  |
| Broadcom                 | 24       | 10.08%  |
| Qualcomm Atheros         | 8        | 3.36%   |
| Nvidia                   | 7        | 2.94%   |
| Broadcom Limited         | 3        | 1.26%   |
| Aquantia                 | 3        | 1.26%   |
| D-Link System            | 2        | 0.84%   |
| ASIX Electronics         | 2        | 0.84%   |
| Xiaomi                   | 1        | 0.42%   |
| Samsung Electronics      | 1        | 0.42%   |
| Marvell Technology Group | 1        | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 100      | 40.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20       | 8.1%    |
| Intel I211 Gigabit Network Connection                             | 11       | 4.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8        | 3.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 2.83%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 6        | 2.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 2.02%   |
| Nvidia MCP61 Ethernet                                             | 5        | 2.02%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.02%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 2.02%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 2.02%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 2.02%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 2.02%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.62%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 4        | 1.62%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.21%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 1.21%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 3        | 1.21%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 1.21%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.81%   |
| Intel 82567V-4 Gigabit Network Connection                         | 2        | 0.81%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.81%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.81%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.4%    |
| Nvidia MCP73 Ethernet                                             | 1        | 0.4%    |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.4%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.4%    |
| Intel PRO/100 VE Network Connection                               | 1        | 0.4%    |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.4%    |
| Intel I210 Gigabit Network Connection                             | 1        | 0.4%    |
| Intel Ethernet Controller I225-V                                  | 1        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.4%    |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1        | 0.4%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                | 1        | 0.4%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.4%    |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.4%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.4%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.4%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.4%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 223      | 75.34%  |
| WiFi     | 73       | 24.66%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 197      | 77.87%  |
| WiFi     | 56       | 22.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 172      | 76.11%  |
| 2     | 46       | 20.35%  |
| 3     | 5        | 2.21%   |
| 4     | 2        | 0.88%   |
| 0     | 1        | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 208      | 91.63%  |
| Yes  | 19       | 8.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 32.69%  |
| Cambridge Silicon Radio         | 17       | 32.69%  |
| Broadcom                        | 7        | 13.46%  |
| Realtek Semiconductor           | 3        | 5.77%   |
| Qualcomm Atheros Communications | 2        | 3.85%   |
| IMC Networks                    | 2        | 3.85%   |
| ASUSTek Computer                | 2        | 3.85%   |
| Lite-On Technology              | 1        | 1.92%   |
| Belkin Components               | 1        | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 17       | 32.69%  |
| Intel AX200 Bluetooth                                  | 7        | 13.46%  |
| Intel Bluetooth wireless interface                     | 4        | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                      | 4        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                       | 3        | 5.77%   |
| Realtek Bluetooth Radio                                | 2        | 3.85%   |
| Qualcomm Atheros AR3011 Bluetooth                      | 2        | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1        | 1.92%   |
| Lite-On Bluetooth Device                               | 1        | 1.92%   |
| Intel Bluetooth Device                                 | 1        | 1.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 1        | 1.92%   |
| Intel AX210 Bluetooth                                  | 1        | 1.92%   |
| IMC Networks Bluetooth Radio                           | 1        | 1.92%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1        | 1.92%   |
| Broadcom Bluetooth 3.0 Device                          | 1        | 1.92%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter       | 1        | 1.92%   |
| Broadcom BCM2045 Bluetooth                             | 1        | 1.92%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter  | 1        | 1.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                     | 1        | 1.92%   |
| ASUS ASUS USB-BT500                                    | 1        | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 153      | 45.13%  |
| AMD                      | 84       | 24.78%  |
| Nvidia                   | 69       | 20.35%  |
| C-Media Electronics      | 9        | 2.65%   |
| Logitech                 | 3        | 0.88%   |
| Razer USA                | 2        | 0.59%   |
| Kingston Technology      | 2        | 0.59%   |
| JMTek                    | 2        | 0.59%   |
| Generalplus Technology   | 2        | 0.59%   |
| Creative Labs            | 2        | 0.59%   |
| Corsair                  | 2        | 0.59%   |
| XMOS                     | 1        | 0.29%   |
| Plantronics              | 1        | 0.29%   |
| Micro Star International | 1        | 0.29%   |
| Hewlett-Packard          | 1        | 0.29%   |
| Focusrite-Novation       | 1        | 0.29%   |
| Creative Technology      | 1        | 0.29%   |
| BEHRINGER International  | 1        | 0.29%   |
| ASUSTek Computer         | 1        | 0.29%   |
| Alesis                   | 1        | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 29       | 7.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 28       | 7.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 22       | 5.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 20       | 5.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 16       | 4.11%   |
| AMD Starship/Matisse HD Audio Controller                                          | 14       | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13       | 3.34%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 9        | 2.31%   |
| Intel Cannon Lake PCH cAVS                                                        | 8        | 2.06%   |
| Intel 200 Series PCH HD Audio                                                     | 8        | 2.06%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8        | 2.06%   |
| Nvidia High Definition Audio Controller                                           | 7        | 1.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 7        | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 1.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.8%    |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                                 | 6        | 1.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 1.54%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 1.54%   |
| Nvidia MCP61 High Definition Audio                                                | 5        | 1.29%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5        | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 1.29%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 5        | 1.29%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 5        | 1.29%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.29%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 1.03%   |
| Nvidia GK104 HDMI Audio Controller                                                | 4        | 1.03%   |
| Nvidia GF106 High Definition Audio Controller                                     | 4        | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.03%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 4        | 1.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.77%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 0.77%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.77%   |
| Intel Comet Lake PCH-V cAVS                                                       | 3        | 0.77%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 0.77%   |
| AMD Navi 10 HDMI Audio                                                            | 3        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 0.51%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.51%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.51%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 0.51%   |
| Kingston Technology HyperX 7.1 Audio                                              | 2        | 0.51%   |
| Intel USB PnP Sound Device                                                        | 2        | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 0.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.51%   |
| Generalplus Technology USB Audio Device                                           | 2        | 0.51%   |
| C-Media Electronics CM8888 [Oxygen Express]                                       | 2        | 0.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.51%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 0.51%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 0.51%   |
| XMOS xCORE USB Audio 2.0                                                          | 1        | 0.26%   |
| Razer USA Gaming Headset [Kraken USB]                                             | 1        | 0.26%   |
| Razer USA Electra V2 USB                                                          | 1        | 0.26%   |
| Plantronics Audio 655 DSP                                                         | 1        | 0.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 40       | 23.67%  |
| Kingston                   | 36       | 21.3%   |
| Corsair                    | 15       | 8.88%   |
| SK Hynix                   | 14       | 8.28%   |
| Samsung Electronics        | 12       | 7.1%    |
| G.Skill                    | 11       | 6.51%   |
| Crucial                    | 11       | 6.51%   |
| Smart                      | 4        | 2.37%   |
| Team                       | 3        | 1.78%   |
| Patriot                    | 3        | 1.78%   |
| Elpida                     | 3        | 1.78%   |
| Teikon                     | 2        | 1.18%   |
| Nanya Technology           | 2        | 1.18%   |
| HBS                        | 2        | 1.18%   |
| Unknown (00FFFFFFFFFFFFFF) | 1        | 0.59%   |
| Transcend                  | 1        | 0.59%   |
| Ramaxel Technology         | 1        | 0.59%   |
| Qimonda                    | 1        | 0.59%   |
| Micron Technology          | 1        | 0.59%   |
| Kreton                     | 1        | 0.59%   |
| Goldenmars                 | 1        | 0.59%   |
| GeIL                       | 1        | 0.59%   |
| atermiter                  | 1        | 0.59%   |
| A-DATA Technology          | 1        | 0.59%   |
| Unknown                    | 1        | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                             | 5        | 2.78%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                                | 4        | 2.22%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                   | 3        | 1.67%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                              | 3        | 1.67%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                       | 3        | 1.67%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s                     | 3        | 1.67%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                              | 2        | 1.11%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                      | 2        | 1.11%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s                              | 2        | 1.11%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                               | 2        | 1.11%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                               | 2        | 1.11%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                   | 2        | 1.11%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                      | 2        | 1.11%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s                                | 2        | 1.11%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s                        | 2        | 1.11%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s                     | 2        | 1.11%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s                  | 2        | 1.11%   |
| Elpida RAM EBJ41EF8BCFA-DJ-F 4096MB DIMM DDR3 1333MT/s                    | 2        | 1.11%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s                      | 2        | 1.11%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s                 | 2        | 1.11%   |
| Unknown RAM Module 8192MB DIMM SDRAM                                      | 1        | 0.56%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                              | 1        | 0.56%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                                    | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                      | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                               | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                              | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                                    | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                                    | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                                      | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                              | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 1067MT/s                              | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                                | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                               | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                    | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                                    | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s                               | 1        | 0.56%   |
| Unknown RAM CS4S2666D19321C 32GB SODIMM DDR4 2667MT/s                     | 1        | 0.56%   |
| Unknown RAM 3634543235363032304555322E3543322020 2048MB DIMM DDR2 800MT/s | 1        | 0.56%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                     | 1        | 0.56%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s                     | 1        | 0.56%   |
| Unknown (00FFFFFFFFFFFFFF) RAM 864AY-667D4 2048MB DIMM DDR2 667MT/s       | 1        | 0.56%   |
| Transcend RAM JM667QLU-2G 2048MB DIMM DDR2 667MT/s                        | 1        | 0.56%   |
| Teikon RAM TMT251U6CFR8C-PBH 4096MB DIMM DDR3 1333MT/s                    | 1        | 0.56%   |
| Teikon RAM TMT225U6FR8C-H9HC 2048MB DIMM DDR3 1066MT/s                    | 1        | 0.56%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s                     | 1        | 0.56%   |
| Smart RAM SH564568FH8N6PHSFR 2048MB DIMM DDR3 1067MT/s                    | 1        | 0.56%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s                       | 1        | 0.56%   |
| Smart RAM SH564568FH8N6PHSF 2048MB DIMM DDR3 1333MT/s                     | 1        | 0.56%   |
| Smart RAM SH564288FH8N6PHSF 1GB DIMM DDR3 1333MT/s                        | 1        | 0.56%   |
| SK Hynix RAM MPPU4GBPC1600 00 4096MB DIMM 533MT/s                         | 1        | 0.56%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2400MT/s                             | 1        | 0.56%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1600MT/s                             | 1        | 0.56%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1333MT/s                             | 1        | 0.56%   |
| SK Hynix RAM MMXIV 4096MB DIMM DDR3 1600MT/s                              | 1        | 0.56%   |
| SK Hynix RAM HYMP112U64CP8-S6 1024MB DIMM DDR2 800MT/s                    | 1        | 0.56%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4096MB DIMM DDR3 1600MT/s                   | 1        | 0.56%   |
| SK Hynix RAM HMT41GU7AFR8C-PB 8192MB DIMM DDR3 1333MT/s                   | 1        | 0.56%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s                 | 1        | 0.56%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s                   | 1        | 0.56%   |
| SK Hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s                      | 1        | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 67       | 44.97%  |
| DDR4    | 37       | 24.83%  |
| DDR2    | 17       | 11.41%  |
| Unknown | 11       | 7.38%   |
| DDR     | 9        | 6.04%   |
| SDRAM   | 7        | 4.7%    |
| DRAM    | 1        | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 140      | 97.22%  |
| SODIMM | 4        | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 45       | 28.3%   |
| 8192  | 41       | 25.79%  |
| 4096  | 41       | 25.79%  |
| 16384 | 16       | 10.06%  |
| 1024  | 9        | 5.66%   |
| 32768 | 6        | 3.77%   |
| 512   | 1        | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 33       | 21.29%  |
| 1600    | 30       | 19.35%  |
| 800     | 13       | 8.39%   |
| 3200    | 12       | 7.74%   |
| 667     | 11       | 7.1%    |
| 2400    | 10       | 6.45%   |
| 2667    | 7        | 4.52%   |
| 533     | 7        | 4.52%   |
| Unknown | 4        | 2.58%   |
| 1067    | 3        | 1.94%   |
| 49926   | 2        | 1.29%   |
| 3600    | 2        | 1.29%   |
| 3400    | 2        | 1.29%   |
| 2666    | 2        | 1.29%   |
| 1867    | 2        | 1.29%   |
| 400     | 2        | 1.29%   |
| 3866    | 1        | 0.65%   |
| 3733    | 1        | 0.65%   |
| 3500    | 1        | 0.65%   |
| 3466    | 1        | 0.65%   |
| 3100    | 1        | 0.65%   |
| 2933    | 1        | 0.65%   |
| 2800    | 1        | 0.65%   |
| 2473    | 1        | 0.65%   |
| 2133    | 1        | 0.65%   |
| 1866    | 1        | 0.65%   |
| 1400    | 1        | 0.65%   |
| 1066    | 1        | 0.65%   |
| 266     | 1        | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 9        | 40.91%  |
| Seiko Epson            | 3        | 13.64%  |
| Brother Industries     | 3        | 13.64%  |
| Canon                  | 2        | 9.09%   |
| Samsung Electronics    | 1        | 4.55%   |
| QinHeng Electronics    | 1        | 4.55%   |
| Panasonic (Matsushita) | 1        | 4.55%   |
| Lexmark International  | 1        | 4.55%   |
| Bixolon                | 1        | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| HP LaserJet Professional P 1102w           | 2        | 8.7%    |
| Brother Printer                            | 2        | 8.7%    |
| Seiko Epson WF-2010 Series                 | 1        | 4.35%   |
| Seiko Epson Printer                        | 1        | 4.35%   |
| Seiko Epson L310 Series                    | 1        | 4.35%   |
| Samsung M2020 Series                       | 1        | 4.35%   |
| QinHeng CH340S                             | 1        | 4.35%   |
| Panasonic (Matsushita) KX-MB2130RU         | 1        | 4.35%   |
| Lexmark International InkJet Color Printer | 1        | 4.35%   |
| HP OfficeJet 6950                          | 1        | 4.35%   |
| HP Officejet 4500 G510a-f                  | 1        | 4.35%   |
| HP LaserJet 1022                           | 1        | 4.35%   |
| HP LaserJet 1020                           | 1        | 4.35%   |
| HP Deskjet F4500 series                    | 1        | 4.35%   |
| HP Deskjet 3050 J610 series                | 1        | 4.35%   |
| HP DeskJet 2130 series                     | 1        | 4.35%   |
| Canon Pixma iP4500 Printer                 | 1        | 4.35%   |
| Canon LBP7010C/7018C                       | 1        | 4.35%   |
| Brother HL-3170CDW series                  | 1        | 4.35%   |
| Brother HL-1440 Laser Printer              | 1        | 4.35%   |
| Bixolon Printer                            | 1        | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 210 | 1        | 50%     |
| Canon CanoScan LiDE 110 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 11       | 42.31%  |
| Creative Technology           | 2        | 7.69%   |
| Apple                         | 2        | 7.69%   |
| Z-Star Microelectronics       | 1        | 3.85%   |
| Sweex                         | 1        | 3.85%   |
| Sunplus Innovation Technology | 1        | 3.85%   |
| Microsoft                     | 1        | 3.85%   |
| Microdia                      | 1        | 3.85%   |
| KYE Systems (Mouse Systems)   | 1        | 3.85%   |
| Jieli Technology              | 1        | 3.85%   |
| IMC Networks                  | 1        | 3.85%   |
| Chicony Electronics           | 1        | 3.85%   |
| Aveo Technology               | 1        | 3.85%   |
| ARC International             | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Logitech Webcam C270                         | 5        | 18.52%  |
| Apple iPhone 5/5C/5S/6/SE                    | 2        | 7.41%   |
| Z-Star Venus USB2.0 Camera                   | 1        | 3.7%    |
| Sweex WC060 Series HD Webcam                 | 1        | 3.7%    |
| Sunplus Integrated_Webcam_HD                 | 1        | 3.7%    |
| Microsoft LifeCam HD-3000                    | 1        | 3.7%    |
| Microdia Integrated_Webcam_FHD               | 1        | 3.7%    |
| Logitech Webcam C930e                        | 1        | 3.7%    |
| Logitech Webcam C170                         | 1        | 3.7%    |
| Logitech QuickCam Pro for Notebooks          | 1        | 3.7%    |
| Logitech QuickCam Pro 9000                   | 1        | 3.7%    |
| Logitech QuickCam Deluxe for Notebooks       | 1        | 3.7%    |
| Logitech HD Webcam C525                      | 1        | 3.7%    |
| Logitech HD Pro Webcam C920                  | 1        | 3.7%    |
| KYE Systems (Mouse Systems) Genius iSlim 330 | 1        | 3.7%    |
| Jieli USB PHY 2.0                            | 1        | 3.7%    |
| IMC Networks XHC Camera                      | 1        | 3.7%    |
| Creative Live! Cam Video IM Pro              | 1        | 3.7%    |
| Creative Live! Cam Chat HD [VF0700]          | 1        | 3.7%    |
| Chicony Gateway Webcam                       | 1        | 3.7%    |
| Aveo UVC camera (Bresser microscope)         | 1        | 3.7%    |
| ARC International Camera                     | 1        | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Chicony Electronics | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 211      | 93.36%  |
| 1     | 14       | 6.19%   |
| 2     | 1        | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 31.25%  |
| Net/wireless             | 3        | 18.75%  |
| Communication controller | 3        | 18.75%  |
| Unassigned class         | 1        | 6.25%   |
| Tv card                  | 1        | 6.25%   |
| Storage/ata              | 1        | 6.25%   |
| Network                  | 1        | 6.25%   |
| Multimedia controller    | 1        | 6.25%   |

