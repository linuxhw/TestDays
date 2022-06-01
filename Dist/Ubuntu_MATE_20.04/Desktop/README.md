Ubuntu MATE 20.04 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

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

Total: 324

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | 970A-DS3P                   | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| INP           | i1000BTS                    | [95da2ada33](https://linux-hardware.org/?probe=95da2ada33) | May 24, 2022 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | [4d68e6fd8d](https://linux-hardware.org/?probe=4d68e6fd8d) | May 12, 2022 |
| HP            | 3031h                       | [4a57ff5761](https://linux-hardware.org/?probe=4a57ff5761) | May 10, 2022 |
| ASUSTek       | A55BM-E                     | [b2b220b65d](https://linux-hardware.org/?probe=b2b220b65d) | Apr 25, 2022 |
| ASRock        | Z87M Extreme4               | [83ffe21604](https://linux-hardware.org/?probe=83ffe21604) | Apr 18, 2022 |
| ASUSTek       | Z97-K                       | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| MSI           | MAG B550M MORTAR            | [7a9f6e1de7](https://linux-hardware.org/?probe=7a9f6e1de7) | Apr 13, 2022 |
| Dell          | 03NVJ6 A00                  | [c640615939](https://linux-hardware.org/?probe=c640615939) | Apr 10, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| Gigabyte      | H470M DS3H                  | [bbfc43c637](https://linux-hardware.org/?probe=bbfc43c637) | Apr 05, 2022 |
| ASRock        | N68C-GS FX                  | [5f45322780](https://linux-hardware.org/?probe=5f45322780) | Apr 04, 2022 |
| Dell          | 06X1TJ A00                  | [42cf748563](https://linux-hardware.org/?probe=42cf748563) | Apr 03, 2022 |
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
| ASUSTek       | H81M-C                      | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
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
| Dell          | 03NVJ6 A00                  | [5422d3bf1d](https://linux-hardware.org/?probe=5422d3bf1d) | Sep 27, 2021 |
| Intel         | DG31PR AAD97573-206         | [060da3d3ab](https://linux-hardware.org/?probe=060da3d3ab) | Sep 26, 2021 |
| HP            | 8265                        | [f840aed42d](https://linux-hardware.org/?probe=f840aed42d) | Sep 21, 2021 |
| ASUSTek       | PRIME B450M-A               | [f93c2362ff](https://linux-hardware.org/?probe=f93c2362ff) | Sep 21, 2021 |
| HP            | 3397                        | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| ASRock        | H110M-STX                   | [6bb90d3b07](https://linux-hardware.org/?probe=6bb90d3b07) | Sep 16, 2021 |
| HP            | 3396                        | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
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
| Dell          | 08NPPY A00                  | [e706b18dd8](https://linux-hardware.org/?probe=e706b18dd8) | Aug 01, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| ASUSTek       | M2N68-AM Plus               | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [6dcb19e468](https://linux-hardware.org/?probe=6dcb19e468) | Jul 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | [647fe69592](https://linux-hardware.org/?probe=647fe69592) | Jul 22, 2021 |
| MSI           | H61M-E33                    | [0d1a9284a9](https://linux-hardware.org/?probe=0d1a9284a9) | Jul 17, 2021 |
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
| Acer          | C-AXC-605                   | [7f9d35f468](https://linux-hardware.org/?probe=7f9d35f468) | May 18, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [f1592b156b](https://linux-hardware.org/?probe=f1592b156b) | May 16, 2021 |
| ASUSTek       | M2N68-AM Plus               | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [9ff1a95290](https://linux-hardware.org/?probe=9ff1a95290) | May 01, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [289a9d70d9](https://linux-hardware.org/?probe=289a9d70d9) | Apr 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [d5310b7f74](https://linux-hardware.org/?probe=d5310b7f74) | Apr 15, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [c2aed97877](https://linux-hardware.org/?probe=c2aed97877) | Apr 08, 2021 |
| MSI           | Z97 GAMING 5                | [946c22503a](https://linux-hardware.org/?probe=946c22503a) | Apr 07, 2021 |
| Dell          | 0F6X5P A00                  | [16218d28da](https://linux-hardware.org/?probe=16218d28da) | Apr 04, 2021 |
| HP            | 3397                        | [e5812883ce](https://linux-hardware.org/?probe=e5812883ce) | Mar 31, 2021 |
| ASRock        | H310M-STX                   | [419277b830](https://linux-hardware.org/?probe=419277b830) | Mar 26, 2021 |
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
| Medion        | B460H6-EM                   | [2ab61e6080](https://linux-hardware.org/?probe=2ab61e6080) | Mar 03, 2021 |
| Unknown       | XH61X000.100                | [029de8905d](https://linux-hardware.org/?probe=029de8905d) | Feb 17, 2021 |
| JINGSHA       | Unknown                     | [01ab676e78](https://linux-hardware.org/?probe=01ab676e78) | Feb 15, 2021 |
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
| ASUSTek       | TUF Gaming B550M-PLUS       | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
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
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [49224bd7f8](https://linux-hardware.org/?probe=49224bd7f8) | Nov 21, 2020 |
| ASUSTek       | WS C246M PRO Series         | [502bd89093](https://linux-hardware.org/?probe=502bd89093) | Nov 18, 2020 |
| ASUSTek       | WS C246M PRO Series         | [dc20d9cf64](https://linux-hardware.org/?probe=dc20d9cf64) | Nov 17, 2020 |
| Dell          | 0WG864                      | [1c2384097b](https://linux-hardware.org/?probe=1c2384097b) | Nov 15, 2020 |
| HP            | 1790                        | [02138cec8b](https://linux-hardware.org/?probe=02138cec8b) | Nov 08, 2020 |
| HP            | 1905                        | [6f20f6aa7d](https://linux-hardware.org/?probe=6f20f6aa7d) | Nov 08, 2020 |
| Intel         | SLIMBOOK                    | [2250e4a10f](https://linux-hardware.org/?probe=2250e4a10f) | Nov 07, 2020 |
| HP            | 3397                        | [17188b10a3](https://linux-hardware.org/?probe=17188b10a3) | Nov 06, 2020 |
| Pegatron      | NARRA3                      | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| Lenovo        | ThinkCentre M58p 6234DJ1    | [69bc4fbb1b](https://linux-hardware.org/?probe=69bc4fbb1b) | Oct 30, 2020 |
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
| Gigabyte      | H81M-H                      | [461e0244f4](https://linux-hardware.org/?probe=461e0244f4) | Aug 31, 2020 |
| Gigabyte      | X58A-UD3R                   | [b26cdf0225](https://linux-hardware.org/?probe=b26cdf0225) | Aug 29, 2020 |
| ASUSTek       | PRIME Z270-P                | [b39122c844](https://linux-hardware.org/?probe=b39122c844) | Aug 25, 2020 |
| ASUSTek       | PRIME X399-A                | [8d0d4f27be](https://linux-hardware.org/?probe=8d0d4f27be) | Aug 22, 2020 |
| Toshiba       | STI 010432                  | [7d6c45eed4](https://linux-hardware.org/?probe=7d6c45eed4) | Aug 20, 2020 |
| Intel         | Unknown                     | [0792f8e763](https://linux-hardware.org/?probe=0792f8e763) | Aug 20, 2020 |
| ASRock        | 990FX Extreme4              | [9d89158c0c](https://linux-hardware.org/?probe=9d89158c0c) | Aug 19, 2020 |
| ASUSTek       | PRIME Z270-P                | [f3ea863c21](https://linux-hardware.org/?probe=f3ea863c21) | Aug 19, 2020 |
| Toshiba       | STI 010432                  | [844d21cfba](https://linux-hardware.org/?probe=844d21cfba) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | [d568758fb5](https://linux-hardware.org/?probe=d568758fb5) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | [93e07b3103](https://linux-hardware.org/?probe=93e07b3103) | Aug 16, 2020 |
| ASRock        | B450M Pro4                  | [27573f027c](https://linux-hardware.org/?probe=27573f027c) | Aug 12, 2020 |
| Intel         | Unknown                     | [aca06096b6](https://linux-hardware.org/?probe=aca06096b6) | Aug 12, 2020 |
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
| Lenovo        | ThinkCentre A70 7844P8U     | [30edd53934](https://linux-hardware.org/?probe=30edd53934) | Jul 09, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [994e71e658](https://linux-hardware.org/?probe=994e71e658) | Jul 03, 2020 |
| MSI           | A78M-E35                    | [baf6228acf](https://linux-hardware.org/?probe=baf6228acf) | Jul 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | [f7afeb0f26](https://linux-hardware.org/?probe=f7afeb0f26) | Jul 01, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c1d0ef500e](https://linux-hardware.org/?probe=c1d0ef500e) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6a9b477b88](https://linux-hardware.org/?probe=6a9b477b88) | Jun 29, 2020 |
| HP            | ProLiant MicroServer        | [1f2d306b05](https://linux-hardware.org/?probe=1f2d306b05) | Jun 20, 2020 |
| IBM           | 9210KGT                     | [28e9762210](https://linux-hardware.org/?probe=28e9762210) | Jun 16, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [02f2a001e1](https://linux-hardware.org/?probe=02f2a001e1) | Jun 11, 2020 |
| ASRock        | H110M-STX                   | [3c35aef096](https://linux-hardware.org/?probe=3c35aef096) | Jun 10, 2020 |
| Dell          | 0478VN A00                  | [f02bda5144](https://linux-hardware.org/?probe=f02bda5144) | Jun 09, 2020 |
| Gigabyte      | B450M DS3H-CF               | [8dbad33afb](https://linux-hardware.org/?probe=8dbad33afb) | Jun 05, 2020 |
| ASRock        | A320M-HDV R4.0              | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASUSTek       | P5QPL-AM                    | [140b5cec40](https://linux-hardware.org/?probe=140b5cec40) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | [9c5c59ed91](https://linux-hardware.org/?probe=9c5c59ed91) | May 30, 2020 |
| IBM           | 9210KGT                     | [784c83d7d6](https://linux-hardware.org/?probe=784c83d7d6) | May 19, 2020 |
| ASUSTek       | PRIME B450M-K               | [8fd77159e9](https://linux-hardware.org/?probe=8fd77159e9) | May 19, 2020 |
| Dell          | 0WF810                      | [24f1a1287d](https://linux-hardware.org/?probe=24f1a1287d) | May 17, 2020 |
| Dell          | 0WF810                      | [6ae0e21069](https://linux-hardware.org/?probe=6ae0e21069) | May 17, 2020 |
| Dell          | 0WF810                      | [e6f27fd467](https://linux-hardware.org/?probe=e6f27fd467) | May 17, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4806bd297f](https://linux-hardware.org/?probe=4806bd297f) | May 16, 2020 |
| ASRock        | A320M-HDV R4.0              | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| Lenovo        | SDK0E50510 WIN 262507961... | [0400e155ee](https://linux-hardware.org/?probe=0400e155ee) | May 10, 2020 |
| Gigabyte      | GA-970A-UD3                 | [567162aae3](https://linux-hardware.org/?probe=567162aae3) | May 09, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9a72c58dee](https://linux-hardware.org/?probe=9a72c58dee) | May 04, 2020 |
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
| 5.4.0-48-generic           | 29       | 11.11%  |
| 5.4.0-52-generic           | 13       | 4.98%   |
| 5.4.0-42-generic           | 13       | 4.98%   |
| 5.4.0-94-generic           | 12       | 4.6%    |
| 5.4.0-47-generic           | 12       | 4.6%    |
| 5.4.0-45-generic           | 10       | 3.83%   |
| 5.4.0-65-generic           | 8        | 3.07%   |
| 5.4.0-40-generic           | 8        | 3.07%   |
| 5.4.0-66-generic           | 6        | 2.3%    |
| 5.11.0-40-generic          | 6        | 2.3%    |
| 5.4.0-80-generic           | 5        | 1.92%   |
| 5.4.0-67-generic           | 5        | 1.92%   |
| 5.4.0-29-generic           | 5        | 1.92%   |
| 5.8.0-55-generic           | 4        | 1.53%   |
| 5.4.0-89-generic           | 4        | 1.53%   |
| 5.4.0-74-generic           | 4        | 1.53%   |
| 5.4.0-56-generic           | 4        | 1.53%   |
| 5.4.0-33-generic           | 4        | 1.53%   |
| 5.4.0-107-generic          | 4        | 1.53%   |
| 5.8.0-59-generic           | 3        | 1.15%   |
| 5.4.0-90-generic           | 3        | 1.15%   |
| 5.4.0-88-generic           | 3        | 1.15%   |
| 5.4.0-81-generic           | 3        | 1.15%   |
| 5.4.0-72-generic           | 3        | 1.15%   |
| 5.4.0-62-generic           | 3        | 1.15%   |
| 5.4.0-59-generic           | 3        | 1.15%   |
| 5.4.0-58-generic           | 3        | 1.15%   |
| 5.4.0-26-generic           | 3        | 1.15%   |
| 5.13.0-39-generic          | 3        | 1.15%   |
| 5.13.0-35-generic          | 3        | 1.15%   |
| 5.13.0-27-generic          | 3        | 1.15%   |
| 5.8.0-53-generic           | 2        | 0.77%   |
| 5.4.0-77-generic           | 2        | 0.77%   |
| 5.4.0-73-generic           | 2        | 0.77%   |
| 5.4.0-70-generic           | 2        | 0.77%   |
| 5.4.0-60-generic           | 2        | 0.77%   |
| 5.4.0-51-generic           | 2        | 0.77%   |
| 5.4.0-37-generic           | 2        | 0.77%   |
| 5.4.0-100-generic          | 2        | 0.77%   |
| 5.11.0-43-generic          | 2        | 0.77%   |
| 5.11.0-41-generic          | 2        | 0.77%   |
| 5.11.0-34-generic          | 2        | 0.77%   |
| 5.11.0-25-generic          | 2        | 0.77%   |
| 5.8.0-57-generic           | 1        | 0.38%   |
| 5.8.0-54-generic           | 1        | 0.38%   |
| 5.8.0-50-generic           | 1        | 0.38%   |
| 5.8.0-48-generic           | 1        | 0.38%   |
| 5.8.0-45-generic           | 1        | 0.38%   |
| 5.8.0-43-generic           | 1        | 0.38%   |
| 5.8.0-41-generic           | 1        | 0.38%   |
| 5.8.0-40-generic           | 1        | 0.38%   |
| 5.7.6-050706-generic       | 1        | 0.38%   |
| 5.7.0-050700-generic       | 1        | 0.38%   |
| 5.4.0-99-generic           | 1        | 0.38%   |
| 5.4.0-97-generic           | 1        | 0.38%   |
| 5.4.0-91-generic           | 1        | 0.38%   |
| 5.4.0-86-generic           | 1        | 0.38%   |
| 5.4.0-702104061620-generic | 1        | 0.38%   |
| 5.4.0-64-generic           | 1        | 0.38%   |
| 5.4.0-53-generic           | 1        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 185      | 78.39%  |
| 5.8.0   | 17       | 7.2%    |
| 5.11.0  | 17       | 7.2%    |
| 5.13.0  | 10       | 4.24%   |
| 5.10.0  | 2        | 0.85%   |
| 5.7.6   | 1        | 0.42%   |
| 5.7.0   | 1        | 0.42%   |
| 5.16.0  | 1        | 0.42%   |
| 5.14.0  | 1        | 0.42%   |
| 5.10.5  | 1        | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 185      | 78.39%  |
| 5.8     | 17       | 7.2%    |
| 5.11    | 17       | 7.2%    |
| 5.13    | 10       | 4.24%   |
| 5.10    | 3        | 1.27%   |
| 5.7     | 2        | 0.85%   |
| 5.16    | 1        | 0.42%   |
| 5.14    | 1        | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 232      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 227      | 97.84%  |
| X-Cinnamon | 2        | 0.86%   |
| Trinity    | 1        | 0.43%   |
| GNOME      | 1        | 0.43%   |
| Budgie     | 1        | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 224      | 96.14%  |
| Tty     | 8        | 3.43%   |
| Wayland | 1        | 0.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 104      | 43.15%  |
| Unknown | 65       | 26.97%  |
| LightDM | 61       | 25.31%  |
| GDM     | 6        | 2.49%   |
| GDM3    | 3        | 1.24%   |
| SLiM    | 1        | 0.41%   |
| SDDM    | 1        | 0.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 56       | 24.03%  |
| pt_BR | 55       | 23.61%  |
| el_GR | 17       | 7.3%    |
| de_DE | 17       | 7.3%    |
| fr_FR | 16       | 6.87%   |
| en_GB | 11       | 4.72%   |
| en_CA | 10       | 4.29%   |
| ru_RU | 8        | 3.43%   |
| es_ES | 6        | 2.58%   |
| es_AR | 6        | 2.58%   |
| it_IT | 4        | 1.72%   |
| en_AU | 3        | 1.29%   |
| pl_PL | 2        | 0.86%   |
| nl_NL | 2        | 0.86%   |
| hu_HU | 2        | 0.86%   |
| fi_FI | 2        | 0.86%   |
| en_IN | 2        | 0.86%   |
| de_CH | 2        | 0.86%   |
| cs_CZ | 2        | 0.86%   |
| sv_SE | 1        | 0.43%   |
| ja_JP | 1        | 0.43%   |
| hr_HR | 1        | 0.43%   |
| eu_ES | 1        | 0.43%   |
| es_GT | 1        | 0.43%   |
| es_CL | 1        | 0.43%   |
| en_SG | 1        | 0.43%   |
| de_AT | 1        | 0.43%   |
| da_DK | 1        | 0.43%   |
| C     | 1        | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 151      | 64.26%  |
| EFI  | 84       | 35.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 214      | 92.24%  |
| Overlay | 12       | 5.17%   |
| Zfs     | 2        | 0.86%   |
| Xfs     | 2        | 0.86%   |
| ExX4    | 1        | 0.43%   |
| Btrfs   | 1        | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 84       | 35.74%  |
| Unknown | 77       | 32.77%  |
| GPT     | 74       | 31.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 204      | 87.55%  |
| Yes       | 29       | 12.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 157      | 66.81%  |
| Yes       | 78       | 33.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 53       | 22.84%  |
| Dell                | 42       | 18.1%   |
| Hewlett-Packard     | 36       | 15.52%  |
| Gigabyte Technology | 32       | 13.79%  |
| ASRock              | 20       | 8.62%   |
| MSI                 | 19       | 8.19%   |
| Intel               | 8        | 3.45%   |
| Lenovo              | 4        | 1.72%   |
| Pegatron            | 3        | 1.29%   |
| ECS                 | 2        | 0.86%   |
| Biostar             | 2        | 0.86%   |
| Unknown             | 2        | 0.86%   |
| Semp Toshiba        | 1        | 0.43%   |
| Medion              | 1        | 0.43%   |
| JINGSHA             | 1        | 0.43%   |
| INP                 | 1        | 0.43%   |
| IBM                 | 1        | 0.43%   |
| Gateway             | 1        | 0.43%   |
| Fujitsu Siemens     | 1        | 0.43%   |
| Albatron            | 1        | 0.43%   |
| Acer                | 1        | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| HP Compaq 6005 Pro SFF PC         | 8        | 3.45%   |
| HP Compaq Elite 8300 SFF          | 7        | 3.02%   |
| ASUS All Series                   | 6        | 2.59%   |
| Dell OptiPlex 3010                | 5        | 2.16%   |
| Dell OptiPlex GX520               | 4        | 1.72%   |
| Dell OptiPlex 390                 | 4        | 1.72%   |
| Dell OptiPlex 360                 | 4        | 1.72%   |
| Unknown                           | 4        | 1.72%   |
| HP Compaq 6200 Pro SFF PC         | 3        | 1.29%   |
| Dell OptiPlex 330                 | 3        | 1.29%   |
| ASUS M5A78L-M/USB3                | 3        | 1.29%   |
| ASRock B450M Pro4                 | 3        | 1.29%   |
| MSI MS-7C94                       | 2        | 0.86%   |
| MSI MS-7680                       | 2        | 0.86%   |
| HP Compaq 8000 Elite SFF PC       | 2        | 0.86%   |
| HP Compaq 4000 Pro SFF PC         | 2        | 0.86%   |
| Gigabyte Z97-HD3                  | 2        | 0.86%   |
| Gigabyte B450M DS3H               | 2        | 0.86%   |
| Dell OptiPlex GX620               | 2        | 0.86%   |
| Dell OptiPlex 980                 | 2        | 0.86%   |
| Dell OptiPlex 780                 | 2        | 0.86%   |
| Dell OptiPlex 755                 | 2        | 0.86%   |
| Dell OptiPlex 380                 | 2        | 0.86%   |
| ASUS P8H61-M LX3 R2.0             | 2        | 0.86%   |
| ASUS M2N68-AM Plus                | 2        | 0.86%   |
| Semp Toshiba STI                  | 1        | 0.43%   |
| Pegatron VG271AA-ABF s5206fr      | 1        | 0.43%   |
| Pegatron FR484AA-UUW m9464sc      | 1        | 0.43%   |
| Pegatron Compaq dx7500 SFF        | 1        | 0.43%   |
| MSI MS-7C95                       | 1        | 0.43%   |
| MSI MS-7C91                       | 1        | 0.43%   |
| MSI MS-7C84                       | 1        | 0.43%   |
| MSI MS-7C59                       | 1        | 0.43%   |
| MSI MS-7C35                       | 1        | 0.43%   |
| MSI MS-7B51                       | 1        | 0.43%   |
| MSI MS-7B49                       | 1        | 0.43%   |
| MSI MS-7B48                       | 1        | 0.43%   |
| MSI MS-7B18                       | 1        | 0.43%   |
| MSI MS-7B17                       | 1        | 0.43%   |
| MSI MS-7823                       | 1        | 0.43%   |
| MSI MS-7817                       | 1        | 0.43%   |
| MSI MS-7816                       | 1        | 0.43%   |
| MSI MS-7735                       | 1        | 0.43%   |
| MSI MS-7721                       | 1        | 0.43%   |
| Medion MD34440                    | 1        | 0.43%   |
| Lenovo ThinkCentre M73 10B00013US | 1        | 0.43%   |
| Lenovo ThinkCentre M73 10AXS5W900 | 1        | 0.43%   |
| Lenovo ThinkCentre M58p 6234DJ1   | 1        | 0.43%   |
| Lenovo ThinkCentre A70 7844P8U    | 1        | 0.43%   |
| Intel SLIMBOOK                    | 1        | 0.43%   |
| Intel H61M-S1                     | 1        | 0.43%   |
| Intel DH87RL AAG74240-402         | 1        | 0.43%   |
| Intel DH61WW AAG23116-203         | 1        | 0.43%   |
| Intel DG43GT AAE62768-301         | 1        | 0.43%   |
| Intel DG31PR AAD97573-206         | 1        | 0.43%   |
| Intel D946GZIS AAD45436-306       | 1        | 0.43%   |
| INP i1000BTS                      | 1        | 0.43%   |
| IBM 9210KGT                       | 1        | 0.43%   |
| HP Z230 Tower Workstation         | 1        | 0.43%   |
| HP Z220 CMT Workstation           | 1        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 36       | 15.52%  |
| HP Compaq            | 28       | 12.07%  |
| ASUS PRIME           | 8        | 3.45%   |
| ASUS All             | 6        | 2.59%   |
| Lenovo ThinkCentre   | 4        | 1.72%   |
| ASUS M5A78L-M        | 4        | 1.72%   |
| Unknown              | 4        | 1.72%   |
| ASUS M5A97           | 3        | 1.29%   |
| ASRock B450M         | 3        | 1.29%   |
| MSI MS-7C94          | 2        | 0.86%   |
| MSI MS-7680          | 2        | 0.86%   |
| HP ProDesk           | 2        | 0.86%   |
| Gigabyte Z97-HD3     | 2        | 0.86%   |
| Gigabyte X570        | 2        | 0.86%   |
| Gigabyte B450M       | 2        | 0.86%   |
| Gigabyte B450        | 2        | 0.86%   |
| Dell Precision       | 2        | 0.86%   |
| ASUS TUF             | 2        | 0.86%   |
| ASUS ROG             | 2        | 0.86%   |
| ASUS P9X79           | 2        | 0.86%   |
| ASUS P8H61-M         | 2        | 0.86%   |
| ASUS M2N68-AM        | 2        | 0.86%   |
| Semp Toshiba STI     | 1        | 0.43%   |
| Pegatron VG271AA-ABF | 1        | 0.43%   |
| Pegatron FR484AA-UUW | 1        | 0.43%   |
| Pegatron Compaq      | 1        | 0.43%   |
| MSI MS-7C95          | 1        | 0.43%   |
| MSI MS-7C91          | 1        | 0.43%   |
| MSI MS-7C84          | 1        | 0.43%   |
| MSI MS-7C59          | 1        | 0.43%   |
| MSI MS-7C35          | 1        | 0.43%   |
| MSI MS-7B51          | 1        | 0.43%   |
| MSI MS-7B49          | 1        | 0.43%   |
| MSI MS-7B48          | 1        | 0.43%   |
| MSI MS-7B18          | 1        | 0.43%   |
| MSI MS-7B17          | 1        | 0.43%   |
| MSI MS-7823          | 1        | 0.43%   |
| MSI MS-7817          | 1        | 0.43%   |
| MSI MS-7816          | 1        | 0.43%   |
| MSI MS-7735          | 1        | 0.43%   |
| MSI MS-7721          | 1        | 0.43%   |
| Medion MD34440       | 1        | 0.43%   |
| Intel SLIMBOOK       | 1        | 0.43%   |
| Intel H61M-S1        | 1        | 0.43%   |
| Intel DH87RL         | 1        | 0.43%   |
| Intel DH61WW         | 1        | 0.43%   |
| Intel DG43GT         | 1        | 0.43%   |
| Intel DG31PR         | 1        | 0.43%   |
| Intel D946GZIS       | 1        | 0.43%   |
| INP i1000BTS         | 1        | 0.43%   |
| IBM 9210KGT          | 1        | 0.43%   |
| HP Z230              | 1        | 0.43%   |
| HP Z220              | 1        | 0.43%   |
| HP ProLiant          | 1        | 0.43%   |
| HP EliteDesk         | 1        | 0.43%   |
| HP Desktop           | 1        | 0.43%   |
| HP 550-142nf         | 1        | 0.43%   |
| Gigabyte Z77P-D3     | 1        | 0.43%   |
| Gigabyte Z68XP-UD3   | 1        | 0.43%   |
| Gigabyte Z390        | 1        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 33       | 14.22%  |
| 2012 | 28       | 12.07%  |
| 2018 | 25       | 10.78%  |
| 2009 | 24       | 10.34%  |
| 2013 | 21       | 9.05%   |
| 2008 | 17       | 7.33%   |
| 2014 | 14       | 6.03%   |
| 2020 | 13       | 5.6%    |
| 2010 | 10       | 4.31%   |
| 2015 | 9        | 3.88%   |
| 2019 | 7        | 3.02%   |
| 2017 | 6        | 2.59%   |
| 2005 | 6        | 2.59%   |
| 2016 | 5        | 2.16%   |
| 2007 | 5        | 2.16%   |
| 2006 | 5        | 2.16%   |
| 2021 | 4        | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 232      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 228      | 98.28%  |
| Enabled  | 4        | 1.72%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 232      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 74       | 31.62%  |
| 8.01-16.0       | 38       | 16.24%  |
| 16.01-24.0      | 34       | 14.53%  |
| 4.01-8.0        | 30       | 12.82%  |
| 32.01-64.0      | 26       | 11.11%  |
| 64.01-256.0     | 12       | 5.13%   |
| 1.01-2.0        | 9        | 3.85%   |
| 2.01-3.0        | 6        | 2.56%   |
| 24.01-32.0      | 4        | 1.71%   |
| More than 256.0 | 1        | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 82       | 33.06%  |
| 0.51-1.0   | 56       | 22.58%  |
| 2.01-3.0   | 42       | 16.94%  |
| 4.01-8.0   | 24       | 9.68%   |
| 3.01-4.0   | 24       | 9.68%   |
| 8.01-16.0  | 7        | 2.82%   |
| 0.01-0.5   | 7        | 2.82%   |
| 24.01-32.0 | 3        | 1.21%   |
| 16.01-24.0 | 2        | 0.81%   |
| 32.01-64.0 | 1        | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 125      | 52.52%  |
| 2      | 59       | 24.79%  |
| 3      | 26       | 10.92%  |
| 4      | 13       | 5.46%   |
| 5      | 4        | 1.68%   |
| 7      | 3        | 1.26%   |
| 10     | 2        | 0.84%   |
| 8      | 2        | 0.84%   |
| 6      | 2        | 0.84%   |
| 11     | 1        | 0.42%   |
| 0      | 1        | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 141      | 60.26%  |
| No        | 93       | 39.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 231      | 99.57%  |
| No        | 1        | 0.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 161      | 68.22%  |
| Yes       | 75       | 31.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 184      | 78.63%  |
| Yes       | 50       | 21.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Brazil      | 58       | 25%     |
| USA         | 29       | 12.5%   |
| Germany     | 21       | 9.05%   |
| Greece      | 18       | 7.76%   |
| France      | 15       | 6.47%   |
| UK          | 12       | 5.17%   |
| Spain       | 9        | 3.88%   |
| Canada      | 8        | 3.45%   |
| Argentina   | 8        | 3.45%   |
| Russia      | 7        | 3.02%   |
| Czechia     | 5        | 2.16%   |
| Netherlands | 4        | 1.72%   |
| Italy       | 4        | 1.72%   |
| Poland      | 3        | 1.29%   |
| Finland     | 3        | 1.29%   |
| Switzerland | 2        | 0.86%   |
| Japan       | 2        | 0.86%   |
| India       | 2        | 0.86%   |
| Hungary     | 2        | 0.86%   |
| Denmark     | 2        | 0.86%   |
| Bulgaria    | 2        | 0.86%   |
| Australia   | 2        | 0.86%   |
| Ukraine     | 1        | 0.43%   |
| Taiwan      | 1        | 0.43%   |
| Singapore   | 1        | 0.43%   |
| Romania     | 1        | 0.43%   |
| Mexico      | 1        | 0.43%   |
| Hong Kong   | 1        | 0.43%   |
| Guatemala   | 1        | 0.43%   |
| Estonia     | 1        | 0.43%   |
| Cyprus      | 1        | 0.43%   |
| Croatia     | 1        | 0.43%   |
| Chile       | 1        | 0.43%   |
| Belgium     | 1        | 0.43%   |
| Belarus     | 1        | 0.43%   |
| Austria     | 1        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sao Paulo              | 49       | 20.5%   |
| Athens                 | 12       | 5.02%   |
| Berlin                 | 4        | 1.67%   |
| Thessaloniki           | 3        | 1.26%   |
| Yekaterinburg          | 2        | 0.84%   |
| Windsor                | 2        | 0.84%   |
| Sneek                  | 2        | 0.84%   |
| Melbourne              | 2        | 0.84%   |
| Manchester             | 2        | 0.84%   |
| Kirchheim unter Teck   | 2        | 0.84%   |
| Karlsruhe              | 2        | 0.84%   |
| Helsinki               | 2        | 0.84%   |
| Hamburg                | 2        | 0.84%   |
| Florence               | 2        | 0.84%   |
| Biysk                  | 2        | 0.84%   |
| Bar-le-Duc             | 2        | 0.84%   |
| Zumarraga              | 1        | 0.42%   |
| Zsaka                  | 1        | 0.42%   |
| Zagreb                 | 1        | 0.42%   |
| Yankton                | 1        | 0.42%   |
| Włocławek            | 1        | 0.42%   |
| Woodland Hills         | 1        | 0.42%   |
| Westbury               | 1        | 0.42%   |
| Warren                 | 1        | 0.42%   |
| Vikyrovice             | 1        | 0.42%   |
| Vigo                   | 1        | 0.42%   |
| Vienna                 | 1        | 0.42%   |
| Viamao                 | 1        | 0.42%   |
| Veliko Tarnovo         | 1        | 0.42%   |
| Vannes                 | 1        | 0.42%   |
| Ushiku                 | 1        | 0.42%   |
| Tremembe               | 1        | 0.42%   |
| Torokszentmiklos       | 1        | 0.42%   |
| The Hague              | 1        | 0.42%   |
| Thalfingen             | 1        | 0.42%   |
| Tainan City            | 1        | 0.42%   |
| Sunnyvale              | 1        | 0.42%   |
| Sunderland             | 1        | 0.42%   |
| Spokane                | 1        | 0.42%   |
| South Shields          | 1        | 0.42%   |
| Sofia                  | 1        | 0.42%   |
| Skelmersdale           | 1        | 0.42%   |
| Secaucus               | 1        | 0.42%   |
| Seattle                | 1        | 0.42%   |
| Sao José dos Pinhais  | 1        | 0.42%   |
| Sao Goncalo            | 1        | 0.42%   |
| Santeramo in Colle     | 1        | 0.42%   |
| San Luis               | 1        | 0.42%   |
| San Jose               | 1        | 0.42%   |
| San Giovanni Valdarno  | 1        | 0.42%   |
| San Diego              | 1        | 0.42%   |
| Saint-Maur-des-Fossés | 1        | 0.42%   |
| Saint-Cloud            | 1        | 0.42%   |
| Saint John             | 1        | 0.42%   |
| Rio Bonito             | 1        | 0.42%   |
| Reston                 | 1        | 0.42%   |
| Ramos Mejia            | 1        | 0.42%   |
| Provins                | 1        | 0.42%   |
| Prague                 | 1        | 0.42%   |
| Portland               | 1        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 94       | 134    | 26.26%  |
| Seagate                   | 83       | 131    | 23.18%  |
| Samsung Electronics       | 54       | 87     | 15.08%  |
| Kingston                  | 24       | 33     | 6.7%    |
| Hitachi                   | 13       | 16     | 3.63%   |
| Toshiba                   | 12       | 25     | 3.35%   |
| SanDisk                   | 12       | 13     | 3.35%   |
| Crucial                   | 8        | 12     | 2.23%   |
| Intel                     | 7        | 9      | 1.96%   |
| A-DATA Technology         | 6        | 6      | 1.68%   |
| Silicon Motion            | 4        | 5      | 1.12%   |
| PNY                       | 3        | 4      | 0.84%   |
| Patriot                   | 3        | 5      | 0.84%   |
| MAXTOR                    | 3        | 7      | 0.84%   |
| HGST                      | 3        | 5      | 0.84%   |
| Unknown                   | 2        | 2      | 0.56%   |
| Apacer                    | 2        | 2      | 0.56%   |
| USB3.0                    | 1        | 1      | 0.28%   |
| TO Exter                  | 1        | 1      | 0.28%   |
| SPCC                      | 1        | 1      | 0.28%   |
| SMI                       | 1        | 1      | 0.28%   |
| SK Hynix                  | 1        | 1      | 0.28%   |
| Phison                    | 1        | 1      | 0.28%   |
| Mushkin                   | 1        | 1      | 0.28%   |
| Micron/Crucial Technology | 1        | 2      | 0.28%   |
| Marlin                    | 1        | 1      | 0.28%   |
| Lexar                     | 1        | 1      | 0.28%   |
| Leven                     | 1        | 1      | 0.28%   |
| LDLC                      | 1        | 1      | 0.28%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.28%   |
| JMicron                   | 1        | 1      | 0.28%   |
| Intenso                   | 1        | 1      | 0.28%   |
| Inateck                   | 1        | 1      | 0.28%   |
| Hewlett-Packard           | 1        | 1      | 0.28%   |
| China                     | 1        | 1      | 0.28%   |
| ASMT109x                  | 1        | 2      | 0.28%   |
| ASMT                      | 1        | 2      | 0.28%   |
| AMD                       | 1        | 1      | 0.28%   |
| AGI                       | 1        | 2      | 0.28%   |
| addlink                   | 1        | 2      | 0.28%   |
| ADATA SP                  | 1        | 1      | 0.28%   |
| Unknown                   | 1        | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 13       | 3.16%   |
| WDC WD5000AAKX-083CA1 500GB          | 6        | 1.46%   |
| WDC WD5000AAKX-003CA0 500GB          | 6        | 1.46%   |
| Seagate ST3500418AS 500GB            | 6        | 1.46%   |
| Seagate ST1000DM010-2EP102 1TB       | 5        | 1.21%   |
| Samsung SSD 860 EVO 500GB            | 5        | 1.21%   |
| Samsung HD322HJ 320GB                | 5        | 1.21%   |
| Kingston SA400S37120G 120GB SSD      | 5        | 1.21%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4        | 0.97%   |
| Toshiba DT01ACA100 1TB               | 4        | 0.97%   |
| WDC WD2500AAKX-753CA1 250GB          | 3        | 0.73%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 3        | 0.73%   |
| WDC WD10EZEX-00BN5A0 1TB             | 3        | 0.73%   |
| Toshiba DT01ACA050 500GB             | 3        | 0.73%   |
| Seagate ST8000DM004-2CX188 8TB       | 3        | 0.73%   |
| Seagate ST3500630AS 500GB            | 3        | 0.73%   |
| Seagate ST3320620AS 320GB            | 3        | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB       | 3        | 0.73%   |
| Seagate ST2000DM001-9YN164 2TB       | 3        | 0.73%   |
| Seagate ST2000DM001-1ER164 2TB       | 3        | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB       | 3        | 0.73%   |
| Samsung SP2504C 250GB                | 3        | 0.73%   |
| Samsung NVMe SSD Drive 500GB         | 3        | 0.73%   |
| Samsung HD502HJ 500GB                | 3        | 0.73%   |
| Kingston SV300S37A120G 120GB SSD     | 3        | 0.73%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2        | 0.49%   |
| WDC WD5000AZLX-75K2TA0 500GB         | 2        | 0.49%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 2        | 0.49%   |
| WDC WD3200AAKS-75L9A0 320GB          | 2        | 0.49%   |
| WDC WD20EARX-00PASB0 2TB             | 2        | 0.49%   |
| WDC WD10EZEX-08M2NA0 1TB             | 2        | 0.49%   |
| WDC WD10EARX-00N0YB0 1TB             | 2        | 0.49%   |
| Unknown SD/MMC/MS PRO 999GB          | 2        | 0.49%   |
| Seagate ST3500413AS 500GB            | 2        | 0.49%   |
| Seagate ST340212AS 40GB              | 2        | 0.49%   |
| Seagate ST3160815AS 160GB            | 2        | 0.49%   |
| Seagate ST31000528AS 1TB             | 2        | 0.49%   |
| Seagate Expansion 4TB                | 2        | 0.49%   |
| SanDisk SSD U100 16GB                | 2        | 0.49%   |
| SanDisk SSD PLUS 480GB               | 2        | 0.49%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD  | 2        | 0.49%   |
| Samsung SSD 970 PRO 512GB            | 2        | 0.49%   |
| Samsung SSD 970 EVO Plus 250GB       | 2        | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB         | 2        | 0.49%   |
| Samsung SSD 970 EVO 500GB            | 2        | 0.49%   |
| Samsung SSD 870 EVO 500GB            | 2        | 0.49%   |
| Samsung SSD 870 EVO 1TB              | 2        | 0.49%   |
| Samsung SSD 860 EVO 4TB              | 2        | 0.49%   |
| Samsung SSD 860 EVO 2TB              | 2        | 0.49%   |
| Samsung MZ7LN128HCHP-000L1 128GB SSD | 2        | 0.49%   |
| Kingston SV300S37A240G 240GB SSD     | 2        | 0.49%   |
| Kingston SA400S37960G 960GB SSD      | 2        | 0.49%   |
| Kingston SA400S37240G 240GB SSD      | 2        | 0.49%   |
| Intel SSDSA2M080G2GC 80GB            | 2        | 0.49%   |
| Hitachi HDS721010CLA332 1TB          | 2        | 0.49%   |
| Hitachi HDP725050GLA360 500GB        | 2        | 0.49%   |
| HGST HDN726040ALE614 4TB             | 2        | 0.49%   |
| Apacer AS350 128GB SSD               | 2        | 0.49%   |
| A-DATA SU650 120GB SSD               | 2        | 0.49%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1        | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 85       | 116    | 38.64%  |
| Seagate             | 82       | 130    | 37.27%  |
| Samsung Electronics | 20       | 22     | 9.09%   |
| Hitachi             | 13       | 16     | 5.91%   |
| Toshiba             | 12       | 25     | 5.45%   |
| HGST                | 3        | 5      | 1.36%   |
| Unknown             | 2        | 2      | 0.91%   |
| MAXTOR              | 2        | 5      | 0.91%   |
| ASMT109x            | 1        | 2      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 40     | 21.1%   |
| Kingston            | 21       | 25     | 19.27%  |
| SanDisk             | 12       | 13     | 11.01%  |
| WDC                 | 11       | 17     | 10.09%  |
| Crucial             | 8        | 12     | 7.34%   |
| Intel               | 6        | 8      | 5.5%    |
| A-DATA Technology   | 6        | 6      | 5.5%    |
| PNY                 | 3        | 4      | 2.75%   |
| Patriot             | 2        | 4      | 1.83%   |
| Apacer              | 2        | 2      | 1.83%   |
| USB3.0              | 1        | 1      | 0.92%   |
| TO Exter            | 1        | 1      | 0.92%   |
| SMI                 | 1        | 1      | 0.92%   |
| Seagate             | 1        | 1      | 0.92%   |
| Mushkin             | 1        | 1      | 0.92%   |
| MAXTOR              | 1        | 2      | 0.92%   |
| Lexar               | 1        | 1      | 0.92%   |
| Leven               | 1        | 1      | 0.92%   |
| LDLC                | 1        | 1      | 0.92%   |
| JMicron             | 1        | 1      | 0.92%   |
| Intenso             | 1        | 1      | 0.92%   |
| China               | 1        | 1      | 0.92%   |
| ASMT                | 1        | 2      | 0.92%   |
| AMD                 | 1        | 1      | 0.92%   |
| ADATA SP            | 1        | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 180      | 323    | 58.25%  |
| SSD     | 93       | 148    | 30.1%   |
| NVMe    | 32       | 50     | 10.36%  |
| Unknown | 3        | 4      | 0.97%   |
| MMC     | 1        | 1      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 220      | 457    | 82.4%   |
| NVMe | 32       | 50     | 11.99%  |
| SAS  | 14       | 18     | 5.24%   |
| MMC  | 1        | 1      | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 177      | 269    | 59%     |
| 0.51-1.0   | 65       | 104    | 21.67%  |
| 1.01-2.0   | 31       | 43     | 10.33%  |
| 3.01-4.0   | 11       | 18     | 3.67%   |
| 4.01-10.0  | 10       | 25     | 3.33%   |
| 2.01-3.0   | 5        | 11     | 1.67%   |
| 10.01-20.0 | 1        | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 75       | 31.25%  |
| 101-250        | 41       | 17.08%  |
| 1001-2000      | 31       | 12.92%  |
| 501-1000       | 29       | 12.08%  |
| More than 3000 | 26       | 10.83%  |
| 2001-3000      | 10       | 4.17%   |
| Unknown        | 10       | 4.17%   |
| 1-20           | 7        | 2.92%   |
| 51-100         | 6        | 2.5%    |
| 21-50          | 5        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 81       | 33.06%  |
| 101-250        | 34       | 13.88%  |
| 21-50          | 33       | 13.47%  |
| 251-500        | 21       | 8.57%   |
| 51-100         | 21       | 8.57%   |
| 1001-2000      | 15       | 6.12%   |
| 501-1000       | 14       | 5.71%   |
| Unknown        | 10       | 4.08%   |
| 2001-3000      | 9        | 3.67%   |
| More than 3000 | 7        | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 5        | 5      | 9.09%   |
| WDC WD5000AAKX-083CA1 500GB           | 4        | 4      | 7.27%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 3.64%   |
| WDC WD2500AAKX-753CA1 250GB           | 2        | 2      | 3.64%   |
| Seagate ST3500418AS 500GB             | 2        | 2      | 3.64%   |
| Samsung Electronics HD502HJ 500GB     | 2        | 2      | 3.64%   |
| WDC WD40EFAX-68JH4N0 4TB              | 1        | 1      | 1.82%   |
| WDC WD2500YS-01SHB1 256GB             | 1        | 1      | 1.82%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1        | 1      | 1.82%   |
| WDC WD2500AAJS-75M0A0 249GB           | 1        | 1      | 1.82%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 1.82%   |
| WDC WD1600AAJS-75M0A0 160GB           | 1        | 2      | 1.82%   |
| WDC WD15EADS-00P8B0 1TB               | 1        | 1      | 1.82%   |
| WDC WD1200JD-00HBB0 120GB             | 1        | 1      | 1.82%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 1.82%   |
| WDC WD10EFRX-68PJCN0 1TB              | 1        | 1      | 1.82%   |
| WDC WD10EARS-00MVWB0 1TB              | 1        | 1      | 1.82%   |
| Toshiba MK5055GSX 500GB               | 1        | 1      | 1.82%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 1.82%   |
| Seagate ST4000DM004-2CV104 4TB        | 1        | 1      | 1.82%   |
| Seagate ST3750525AS 752GB             | 1        | 1      | 1.82%   |
| Seagate ST3500320AS 500GB             | 1        | 1      | 1.82%   |
| Seagate ST3402111AS 40GB              | 1        | 1      | 1.82%   |
| Seagate ST3360320AS 360GB             | 1        | 2      | 1.82%   |
| Seagate ST3320620AS 320GB             | 1        | 1      | 1.82%   |
| Seagate ST3250318AS 250GB             | 1        | 1      | 1.82%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 1.82%   |
| Seagate ST32000644NS 2TB              | 1        | 1      | 1.82%   |
| Seagate ST3160815AS 160GB             | 1        | 1      | 1.82%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 1.82%   |
| Seagate ST2000DM001-9YN164 2TB        | 1        | 2      | 1.82%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 1.82%   |
| SanDisk SSD PLUS 480GB                | 1        | 1      | 1.82%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 1.82%   |
| Samsung Electronics SP2504C 250GB     | 1        | 1      | 1.82%   |
| Samsung Electronics M3 Portable 1TB   | 1        | 1      | 1.82%   |
| MAXTOR 6Y160M0 160GB                  | 1        | 1      | 1.82%   |
| Kingston SHPM2280P2H 240G SSD         | 1        | 1      | 1.82%   |
| Intel SSDSA2M080G2GC 80GB             | 1        | 1      | 1.82%   |
| Hitachi HDT721050SLA360 500GB         | 1        | 1      | 1.82%   |
| Hitachi HDS721010CLA332 1TB           | 1        | 1      | 1.82%   |
| HGST HDN726040ALE614 4TB              | 1        | 2      | 1.82%   |
| Crucial CT1050MX300SSD1 1050GB        | 1        | 1      | 1.82%   |
| ASMT USB 3.0 Destop H 1TB SSD         | 1        | 2      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 22     | 37.04%  |
| WDC                 | 18       | 20     | 33.33%  |
| Samsung Electronics | 5        | 5      | 9.26%   |
| Toshiba             | 2        | 2      | 3.7%    |
| Hitachi             | 2        | 2      | 3.7%    |
| SanDisk             | 1        | 1      | 1.85%   |
| MAXTOR              | 1        | 1      | 1.85%   |
| Kingston            | 1        | 1      | 1.85%   |
| Intel               | 1        | 1      | 1.85%   |
| HGST                | 1        | 2      | 1.85%   |
| Crucial             | 1        | 1      | 1.85%   |
| ASMT                | 1        | 2      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 22     | 41.67%  |
| WDC                 | 18       | 20     | 37.5%   |
| Samsung Electronics | 4        | 4      | 8.33%   |
| Toshiba             | 2        | 2      | 4.17%   |
| Hitachi             | 2        | 2      | 4.17%   |
| MAXTOR              | 1        | 1      | 2.08%   |
| HGST                | 1        | 2      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 45       | 53     | 90%     |
| SSD  | 5        | 7      | 10%     |

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
| Works    | 132      | 254    | 50.19%  |
| Detected | 83       | 212    | 31.56%  |
| Malfunc  | 48       | 60     | 18.25%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 157      | 54.14%  |
| AMD                           | 65       | 22.41%  |
| Samsung Electronics           | 14       | 4.83%   |
| Marvell Technology Group      | 11       | 3.79%   |
| Nvidia                        | 9        | 3.1%    |
| ASMedia Technology            | 9        | 3.1%    |
| Silicon Motion                | 6        | 2.07%   |
| Kingston Technology Company   | 5        | 1.72%   |
| Phison Electronics            | 3        | 1.03%   |
| JMicron Technology            | 3        | 1.03%   |
| VIA Technologies              | 1        | 0.34%   |
| SK Hynix                      | 1        | 0.34%   |
| Sandisk                       | 1        | 0.34%   |
| Micron/Crucial Technology     | 1        | 0.34%   |
| LSI Logic / Symbios Logic     | 1        | 0.34%   |
| KIOXIA                        | 1        | 0.34%   |
| Integrated Technology Express | 1        | 0.34%   |
| Hewlett-Packard               | 1        | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 7.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26       | 6.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 23       | 6.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17       | 4.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 3.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 3.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15       | 3.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 13       | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 2.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 2.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 2.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 1.83%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 1.57%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 1.57%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 1.57%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 1.57%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 1.31%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 1.04%   |
| Nvidia MCP61 IDE                                                                        | 4        | 1.04%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.78%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.78%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.52%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.52%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.52%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 2        | 0.52%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2        | 0.52%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.52%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.52%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.52%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.52%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.52%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.52%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.52%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.52%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.52%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.52%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.52%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.26%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.26%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.26%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.26%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.26%   |
| Nvidia MCP79 AHCI Controller                                                            | 1        | 0.26%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                                 | 1        | 0.26%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.26%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.26%   |
| Nvidia MCP51 IDE                                                                        | 1        | 0.26%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 173      | 58.45%  |
| IDE  | 82       | 27.7%   |
| NVMe | 31       | 10.47%  |
| RAID | 7        | 2.36%   |
| SAS  | 3        | 1.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 160      | 68.97%  |
| AMD    | 72       | 31.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 9        | 3.88%   |
| AMD Phenom II X4 B97 Processor              | 7        | 3.02%   |
| Intel Pentium 4 CPU 3.00GHz                 | 5        | 2.16%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 5        | 2.16%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 5        | 2.16%   |
| Intel Pentium D CPU 2.80GHz                 | 4        | 1.72%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 4        | 1.72%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 4        | 1.72%   |
| AMD FX-8350 Eight-Core Processor            | 4        | 1.72%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 3        | 1.29%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 1.29%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.29%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1.29%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 3        | 1.29%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 1.29%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.29%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.29%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 3        | 1.29%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 3        | 1.29%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.29%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.29%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.29%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 2        | 0.86%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 0.86%   |
| Intel Core i7-4790S CPU @ 3.20GHz           | 2        | 0.86%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.86%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.86%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.86%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.86%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.86%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 0.86%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.86%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.86%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 0.86%   |
| Intel Celeron CPU E1400 @ 2.00GHz           | 2        | 0.86%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 0.86%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.86%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 0.86%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 0.86%   |
| AMD FX-6300 Six-Core Processor              | 2        | 0.86%   |
| AMD Athlon II X2 215 Processor              | 2        | 0.86%   |
| Intel Xeon E-2126G CPU @ 3.30GHz            | 1        | 0.43%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.43%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.43%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz         | 1        | 0.43%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1        | 0.43%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.43%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.43%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.43%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.43%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.43%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.43%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 0.43%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 0.43%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.43%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.43%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.43%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.43%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.43%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 43       | 18.53%  |
| Intel Core i3           | 25       | 10.78%  |
| Intel Core i7           | 22       | 9.48%   |
| Intel Core 2 Duo        | 15       | 6.47%   |
| AMD FX                  | 13       | 5.6%    |
| AMD Phenom II X4        | 11       | 4.74%   |
| Intel Core 2 Quad       | 10       | 4.31%   |
| AMD Ryzen 5             | 10       | 4.31%   |
| AMD Ryzen 7             | 9        | 3.88%   |
| Intel Xeon              | 8        | 3.45%   |
| Intel Celeron           | 8        | 3.45%   |
| Intel Pentium           | 7        | 3.02%   |
| AMD Athlon II X2        | 7        | 3.02%   |
| Intel Pentium 4         | 5        | 2.16%   |
| AMD Ryzen 9             | 5        | 2.16%   |
| Other                   | 4        | 1.72%   |
| Intel Pentium Dual-Core | 4        | 1.72%   |
| Intel Pentium D         | 4        | 1.72%   |
| Intel Core 2            | 3        | 1.29%   |
| Intel Pentium Dual      | 2        | 0.86%   |
| AMD Ryzen Threadripper  | 2        | 0.86%   |
| AMD Ryzen 3             | 2        | 0.86%   |
| AMD Athlon              | 2        | 0.86%   |
| AMD A8                  | 2        | 0.86%   |
| Intel Core i9           | 1        | 0.43%   |
| Intel Atom              | 1        | 0.43%   |
| AMD Turion II Neo       | 1        | 0.43%   |
| AMD Ryzen 3 PRO         | 1        | 0.43%   |
| AMD Phenom II X6        | 1        | 0.43%   |
| AMD Athlon II X4        | 1        | 0.43%   |
| AMD Athlon 64 X2        | 1        | 0.43%   |
| AMD A4                  | 1        | 0.43%   |
| AMD A10                 | 1        | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 97       | 41.81%  |
| 2      | 79       | 34.05%  |
| 6      | 23       | 9.91%   |
| 8      | 13       | 5.6%    |
| 1      | 7        | 3.02%   |
| 16     | 6        | 2.59%   |
| 3      | 3        | 1.29%   |
| 24     | 2        | 0.86%   |
| 12     | 2        | 0.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 229      | 98.71%  |
| 2      | 3        | 1.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 125      | 53.65%  |
| 2      | 108      | 46.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 232      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 24       | 10.26%  |
| 0x306a9    | 24       | 10.26%  |
| 0x206a7    | 19       | 8.12%   |
| Unknown    | 16       | 6.84%   |
| 0x1067a    | 15       | 6.41%   |
| 0x010000c8 | 14       | 5.98%   |
| 0x08701021 | 9        | 3.85%   |
| 0x06000852 | 8        | 3.42%   |
| 0x6fb      | 7        | 2.99%   |
| 0x6fd      | 6        | 2.56%   |
| 0x906ea    | 5        | 2.14%   |
| 0xf41      | 4        | 1.71%   |
| 0xa0653    | 4        | 1.71%   |
| 0x906e9    | 4        | 1.71%   |
| 0x206d7    | 4        | 1.71%   |
| 0x08701013 | 4        | 1.71%   |
| 0x0800820d | 4        | 1.71%   |
| 0xf47      | 3        | 1.28%   |
| 0x6f6      | 3        | 1.28%   |
| 0x506e3    | 3        | 1.28%   |
| 0x106e5    | 3        | 1.28%   |
| 0x0810100b | 3        | 1.28%   |
| 0x06001119 | 3        | 1.28%   |
| 0x010000db | 3        | 1.28%   |
| 0xa0671    | 2        | 0.85%   |
| 0x906ed    | 2        | 0.85%   |
| 0x906eb    | 2        | 0.85%   |
| 0x30678    | 2        | 0.85%   |
| 0x20655    | 2        | 0.85%   |
| 0x10677    | 2        | 0.85%   |
| 0x10676    | 2        | 0.85%   |
| 0x0600063e | 2        | 0.85%   |
| 0xf62      | 1        | 0.43%   |
| 0xf43      | 1        | 0.43%   |
| 0xa0655    | 1        | 0.43%   |
| 0x906ec    | 1        | 0.43%   |
| 0x806ea    | 1        | 0.43%   |
| 0x506c9    | 1        | 0.43%   |
| 0x306f2    | 1        | 0.43%   |
| 0x306e4    | 1        | 0.43%   |
| 0x206d6    | 1        | 0.43%   |
| 0x106c2    | 1        | 0.43%   |
| 0x106a5    | 1        | 0.43%   |
| 0x0a201016 | 1        | 0.43%   |
| 0x0a201009 | 1        | 0.43%   |
| 0x08600106 | 1        | 0.43%   |
| 0x08301039 | 1        | 0.43%   |
| 0x08108109 | 1        | 0.43%   |
| 0x08101102 | 1        | 0.43%   |
| 0x08101016 | 1        | 0.43%   |
| 0x08101013 | 1        | 0.43%   |
| 0x08001138 | 1        | 0.43%   |
| 0x08001137 | 1        | 0.43%   |
| 0x0600611a | 1        | 0.43%   |
| 0x06003106 | 1        | 0.43%   |
| 0x0600081f | 1        | 0.43%   |
| 0x010000dc | 1        | 0.43%   |
| 0x010000c7 | 1        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 26       | 11.21%  |
| Haswell     | 26       | 11.21%  |
| IvyBridge   | 25       | 10.78%  |
| K10         | 22       | 9.48%   |
| Penryn      | 21       | 9.05%   |
| KabyLake    | 16       | 6.9%    |
| Core        | 16       | 6.9%    |
| Zen 2       | 15       | 6.47%   |
| Piledriver  | 14       | 6.03%   |
| NetBurst    | 9        | 3.88%   |
| Zen         | 8        | 3.45%   |
| Zen+        | 5        | 2.16%   |
| CometLake   | 5        | 2.16%   |
| Skylake     | 4        | 1.72%   |
| Nehalem     | 4        | 1.72%   |
| Zen 3       | 2        | 0.86%   |
| Westmere    | 2        | 0.86%   |
| Silvermont  | 2        | 0.86%   |
| Icelake     | 2        | 0.86%   |
| Bulldozer   | 2        | 0.86%   |
| Steamroller | 1        | 0.43%   |
| K8 Hammer   | 1        | 0.43%   |
| Jaguar      | 1        | 0.43%   |
| Goldmont    | 1        | 0.43%   |
| Excavator   | 1        | 0.43%   |
| Bonnell     | 1        | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 101      | 40.73%  |
| Nvidia            | 74       | 29.84%  |
| AMD               | 72       | 29.03%  |
| ASPEED Technology | 1        | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 17       | 6.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15       | 5.98%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 14       | 5.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 4.78%   |
| AMD RS880 [Radeon HD 4200]                                                  | 10       | 3.98%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 8        | 3.19%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 8        | 3.19%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 2.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 2.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.99%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.59%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.59%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.59%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.2%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.2%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.2%    |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 3        | 1.2%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 1.2%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.8%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 0.8%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.8%    |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 2        | 0.8%    |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 0.8%    |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 0.8%    |
| Intel HD Graphics 630                                                       | 2        | 0.8%    |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 0.8%    |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 0.8%    |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 0.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 0.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 0.8%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 0.8%    |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 0.8%    |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2        | 0.8%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.4%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.4%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.4%    |
| Nvidia TU104GL [Quadro RTX 4000]                                            | 1        | 0.4%    |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.4%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.4%    |
| Nvidia NV44 [GeForce 6200 SE TurboCache]                                    | 1        | 0.4%    |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 0.4%    |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.4%    |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 0.4%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.4%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.4%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.4%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.4%    |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 0.4%    |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.4%    |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.4%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.4%    |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.4%    |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 89       | 38.2%   |
| 1 x AMD                  | 68       | 29.18%  |
| 1 x Nvidia               | 66       | 28.33%  |
| Intel + Nvidia           | 5        | 2.15%   |
| 2 x Nvidia               | 1        | 0.43%   |
| 2 x AMD                  | 1        | 0.43%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.43%   |
| Intel + AMD              | 1        | 0.43%   |
| 1 x ASPEED               | 1        | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 180      | 76.92%  |
| Proprietary | 51       | 21.79%  |
| Unknown     | 3        | 1.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 103      | 43.64%  |
| 0.01-0.5   | 35       | 14.83%  |
| 1.01-2.0   | 31       | 13.14%  |
| 0.51-1.0   | 30       | 12.71%  |
| 7.01-8.0   | 17       | 7.2%    |
| 3.01-4.0   | 15       | 6.36%   |
| 5.01-6.0   | 4        | 1.69%   |
| 2.01-3.0   | 1        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 60       | 24.29%  |
| Samsung Electronics  | 39       | 15.79%  |
| Goldstar             | 23       | 9.31%   |
| Philips              | 14       | 5.67%   |
| Hewlett-Packard      | 14       | 5.67%   |
| BenQ                 | 13       | 5.26%   |
| Ancor Communications | 11       | 4.45%   |
| AOC                  | 10       | 4.05%   |
| Acer                 | 10       | 4.05%   |
| ViewSonic            | 7        | 2.83%   |
| Unknown              | 7        | 2.83%   |
| Lenovo               | 3        | 1.21%   |
| HannStar             | 3        | 1.21%   |
| Vestel Elektronik    | 2        | 0.81%   |
| Toshiba              | 2        | 0.81%   |
| NEC Computers        | 2        | 0.81%   |
| LG Electronics       | 2        | 0.81%   |
| Iiyama               | 2        | 0.81%   |
| Gateway              | 2        | 0.81%   |
| Belinea              | 2        | 0.81%   |
| Vizio                | 1        | 0.4%    |
| VIZ                  | 1        | 0.4%    |
| Targa                | 1        | 0.4%    |
| Sony                 | 1        | 0.4%    |
| Seiki                | 1        | 0.4%    |
| Sceptre Tech         | 1        | 0.4%    |
| Sceptre              | 1        | 0.4%    |
| RTK                  | 1        | 0.4%    |
| ROW                  | 1        | 0.4%    |
| Packard Bell         | 1        | 0.4%    |
| Medion               | 1        | 0.4%    |
| Insignia             | 1        | 0.4%    |
| Hitachi              | 1        | 0.4%    |
| Fujitsu Siemens      | 1        | 0.4%    |
| Element              | 1        | 0.4%    |
| Eizo                 | 1        | 0.4%    |
| DENON                | 1        | 0.4%    |
| Daewoo               | 1        | 0.4%    |
| Compal               | 1        | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 31       | 11.65%  |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                    | 5        | 1.88%   |
| ViewSonic VA703-4Series VSC6A1E 1280x1024 341x274mm 17.2-inch        | 4        | 1.5%    |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                     | 3        | 1.13%   |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                    | 3        | 1.13%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                        | 2        | 0.75%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 340x270mm 17.1-inch | 2        | 0.75%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                    | 2        | 0.75%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch    | 2        | 0.75%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 2        | 0.75%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2        | 0.75%   |
| Goldstar W2253 GSM56DB 1920x1080 474x296mm 22.0-inch                 | 2        | 0.75%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2        | 0.75%   |
| Goldstar E2340 GSM57A6 1920x1080 510x290mm 23.1-inch                 | 2        | 0.75%   |
| Goldstar 23LC1R GSM5617 1360x768 930x523mm 42.0-inch                 | 2        | 0.75%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 0.75%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                     | 2        | 0.75%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 2        | 0.75%   |
| Vizio VO320E VIZ0035 1366x768 700x390mm 31.5-inch                    | 1        | 0.38%   |
| VIZ LCD Monitor E322VL 1920x1080                                     | 1        | 0.38%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch              | 1        | 0.38%   |
| ViewSonic VE902m VSC491B 1280x1024 376x301mm 19.0-inch               | 1        | 0.38%   |
| ViewSonic VE710s VSCF518 1280x1024 338x270mm 17.0-inch               | 1        | 0.38%   |
| Unknown LCD Monitor Sony SDM-X82 1280x1024                           | 1        | 0.38%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 1        | 0.38%   |
| Unknown LCD Monitor SAMSUNG 1360x768                                 | 1        | 0.38%   |
| Unknown LCD Monitor PHILIPS FTV 1360x768                             | 1        | 0.38%   |
| Unknown LCD Monitor FormacTFT2010 1600x1200                          | 1        | 0.38%   |
| Unknown LCD Monitor ELE E4SW5017RKU                                  | 1        | 0.38%   |
| Unknown LCD Monitor CHHWJT 1920x1080                                 | 1        | 0.38%   |
| Toshiba TV TSB2017 3840x2160                                         | 1        | 0.38%   |
| Toshiba 49UHD_LCD_TV TSB3700 3840x2160 1872x1053mm 84.6-inch         | 1        | 0.38%   |
| Targa LCD Monitor LCDTV16                                            | 1        | 0.38%   |
| Sony TV SNYEE01 1920x1080                                            | 1        | 0.38%   |
| Seiki SE19HY10 SEK1920 1366x768 410x230mm 18.5-inch                  | 1        | 0.38%   |
| Sceptre Tech Sceptre X24WG SPT2401 1920x1200 518x324mm 24.1-inch     | 1        | 0.38%   |
| Sceptre Tech Sceptre T27 SPT0AD7 1920x1080 600x330mm 27.0-inch       | 1        | 0.38%   |
| Sceptre LCD Monitor X24WG 3840x1200                                  | 1        | 0.38%   |
| Sceptre LCD Monitor X24WG                                            | 1        | 0.38%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch    | 1        | 0.38%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch    | 1        | 0.38%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.38%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 608x345mm 27.5-inch    | 1        | 0.38%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch    | 1        | 0.38%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1        | 0.38%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.38%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch | 1        | 0.38%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 338x270mm 17.0-inch | 1        | 0.38%   |
| Samsung Electronics SyncMaster SAM02F3 1680x1050 474x296mm 22.0-inch | 1        | 0.38%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch | 1        | 0.38%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch   | 1        | 0.38%   |
| Samsung Electronics SMB2270HD SAM070C 1920x1080 476x268mm 21.5-inch  | 1        | 0.38%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch   | 1        | 0.38%   |
| Samsung Electronics S27E330 SAM0D90 1920x1080 598x336mm 27.0-inch    | 1        | 0.38%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch    | 1        | 0.38%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1        | 0.38%   |
| Samsung Electronics S24D390 SAM0B64 1920x1080 521x293mm 23.5-inch    | 1        | 0.38%   |
| Samsung Electronics S24B350 SAM08D9 1920x1080 531x299mm 24.0-inch    | 1        | 0.38%   |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch    | 1        | 0.38%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch    | 1        | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 80       | 32.65%  |
| 1280x1024 (SXGA)   | 58       | 23.67%  |
| 3840x2160 (4K)     | 19       | 7.76%   |
| 1366x768 (WXGA)    | 19       | 7.76%   |
| 1440x900 (WXGA+)   | 13       | 5.31%   |
| 1360x768           | 12       | 4.9%    |
| 1680x1050 (WSXGA+) | 10       | 4.08%   |
| 2560x1440 (QHD)    | 7        | 2.86%   |
| Unknown            | 7        | 2.86%   |
| 1920x1200 (WUXGA)  | 4        | 1.63%   |
| 1600x1200          | 3        | 1.22%   |
| 3440x1440          | 2        | 0.82%   |
| 1600x900 (HD+)     | 2        | 0.82%   |
| 6400x1080          | 1        | 0.41%   |
| 5040x1050          | 1        | 0.41%   |
| 4240x1440          | 1        | 0.41%   |
| 3840x1200          | 1        | 0.41%   |
| 3840x1080          | 1        | 0.41%   |
| 3000x1920          | 1        | 0.41%   |
| 2640x1024          | 1        | 0.41%   |
| 1152x864           | 1        | 0.41%   |
| 1024x768 (XGA)     | 1        | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 52       | 20.88%  |
| Unknown | 29       | 11.65%  |
| 24      | 22       | 8.84%   |
| 23      | 22       | 8.84%   |
| 21      | 22       | 8.84%   |
| 18      | 19       | 7.63%   |
| 27      | 17       | 6.83%   |
| 19      | 12       | 4.82%   |
| 22      | 11       | 4.42%   |
| 15      | 11       | 4.42%   |
| 31      | 7        | 2.81%   |
| 84      | 6        | 2.41%   |
| 72      | 5        | 2.01%   |
| 20      | 3        | 1.2%    |
| 42      | 2        | 0.8%    |
| 40      | 2        | 0.8%    |
| 33      | 2        | 0.8%    |
| 32      | 2        | 0.8%    |
| 46      | 1        | 0.4%    |
| 36      | 1        | 0.4%    |
| 34      | 1        | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 301-350     | 60       | 24.79%  |
| 401-500     | 58       | 23.97%  |
| 501-600     | 54       | 22.31%  |
| Unknown     | 29       | 11.98%  |
| 1501-2000   | 11       | 4.55%   |
| 601-700     | 10       | 4.13%   |
| 351-400     | 9        | 3.72%   |
| 701-800     | 6        | 2.48%   |
| 801-900     | 2        | 0.83%   |
| 901-1000    | 2        | 0.83%   |
| 1001-1500   | 1        | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 115      | 49.36%  |
| 5/4     | 50       | 21.46%  |
| 16/10   | 29       | 12.45%  |
| Unknown | 26       | 11.16%  |
| 4/3     | 6        | 2.58%   |
| 6/5     | 4        | 1.72%   |
| 3/2     | 2        | 0.86%   |
| 21/9    | 1        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 65       | 26.64%  |
| 201-250        | 59       | 24.18%  |
| Unknown        | 29       | 11.89%  |
| 151-200        | 24       | 9.84%   |
| 301-350        | 17       | 6.97%   |
| More than 1000 | 11       | 4.51%   |
| 351-500        | 11       | 4.51%   |
| 251-300        | 8        | 3.28%   |
| 101-110        | 8        | 3.28%   |
| 501-1000       | 6        | 2.46%   |
| 131-140        | 3        | 1.23%   |
| 111-120        | 3        | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 154      | 65.81%  |
| 101-120 | 34       | 14.53%  |
| Unknown | 29       | 12.39%  |
| 1-50    | 9        | 3.85%   |
| 121-160 | 6        | 2.56%   |
| 161-240 | 2        | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 194      | 82.91%  |
| 2     | 32       | 13.68%  |
| 0     | 5        | 2.14%   |
| 3     | 3        | 1.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 123      | 40.33%  |
| Intel                           | 88       | 28.85%  |
| Broadcom                        | 26       | 8.52%   |
| Qualcomm Atheros                | 13       | 4.26%   |
| Nvidia                          | 8        | 2.62%   |
| Ralink Technology               | 7        | 2.3%    |
| TP-Link                         | 5        | 1.64%   |
| Ralink                          | 5        | 1.64%   |
| Aquantia                        | 4        | 1.31%   |
| Edimax Technology               | 3        | 0.98%   |
| Broadcom Limited                | 3        | 0.98%   |
| ASUSTek Computer                | 3        | 0.98%   |
| Qualcomm Atheros Communications | 2        | 0.66%   |
| MediaTek                        | 2        | 0.66%   |
| Linksys                         | 2        | 0.66%   |
| D-Link System                   | 2        | 0.66%   |
| ASIX Electronics                | 2        | 0.66%   |
| ZyDAS                           | 1        | 0.33%   |
| Xiaomi                          | 1        | 0.33%   |
| Sitecom Europe                  | 1        | 0.33%   |
| Samsung Electronics             | 1        | 0.33%   |
| NetGear                         | 1        | 0.33%   |
| Marvell Technology Group        | 1        | 0.33%   |
| Huawei Technologies             | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 101      | 29.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 20       | 5.9%    |
| Intel I211 Gigabit Network Connection                              | 11       | 3.24%   |
| Realtek RTL8125 2.5GbE Controller                                  | 8        | 2.36%   |
| Intel Wi-Fi 6 AX200                                                | 8        | 2.36%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 8        | 2.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 6        | 1.77%   |
| Nvidia MCP61 Ethernet                                              | 6        | 1.77%   |
| Intel Ethernet Connection I217-V                                   | 6        | 1.77%   |
| Intel 82567LM-3 Gigabit Network Connection                         | 6        | 1.77%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express            | 6        | 1.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 5        | 1.47%   |
| Intel Ethernet Connection (7) I219-V                               | 5        | 1.47%   |
| Intel 82579V Gigabit Network Connection                            | 5        | 1.47%   |
| Intel 82574L Gigabit Network Connection                            | 5        | 1.47%   |
| Intel Ethernet Connection (2) I219-V                               | 4        | 1.18%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                    | 4        | 1.18%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]  | 4        | 1.18%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 3        | 0.88%   |
| Ralink MT7601U Wireless Adapter                                    | 3        | 0.88%   |
| Intel Ethernet Connection I217-LM                                  | 3        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 3        | 0.88%   |
| Intel 82578DM Gigabit Network Connection                           | 3        | 0.88%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express      | 3        | 0.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 2        | 0.59%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 2        | 0.59%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 2        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                    | 2        | 0.59%   |
| Ralink RT5370 Wireless Adapter                                     | 2        | 0.59%   |
| Ralink RT2561/RT61 rev B 802.11g                                   | 2        | 0.59%   |
| Qualcomm Atheros AR9271 802.11n                                    | 2        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 2        | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet     | 2        | 0.59%   |
| Intel Wireless-AC 9260                                             | 2        | 0.59%   |
| Intel Wireless 7260                                                | 2        | 0.59%   |
| Intel Ethernet Controller I225-V                                   | 2        | 0.59%   |
| Intel 82567V-4 Gigabit Network Connection                          | 2        | 0.59%   |
| Intel 82567V-2 Gigabit Network Connection                          | 2        | 0.59%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]  | 2        | 0.59%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                    | 2        | 0.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                    | 2        | 0.59%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 2        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                      | 2        | 0.59%   |
| ZyDAS ZD1211B 802.11g                                              | 1        | 0.29%   |
| Xiaomi Mi/Redmi series (RNDIS)                                     | 1        | 0.29%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                              | 1        | 0.29%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                          | 1        | 0.29%   |
| TP-Link 802.11n NIC                                                | 1        | 0.29%   |
| Sitecom Europe 802.11n WLAN Adapter                                | 1        | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                      | 1        | 0.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1        | 0.29%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter           | 1        | 0.29%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                | 1        | 0.29%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 1        | 0.29%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 1        | 0.29%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1        | 0.29%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1        | 0.29%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 1        | 0.29%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 1        | 0.29%   |
| Realtek RTL8187 Wireless Adapter                                   | 1        | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 22       | 27.85%  |
| Intel                           | 18       | 22.78%  |
| Ralink Technology               | 7        | 8.86%   |
| TP-Link                         | 5        | 6.33%   |
| Ralink                          | 5        | 6.33%   |
| Qualcomm Atheros                | 5        | 6.33%   |
| Edimax Technology               | 3        | 3.8%    |
| ASUSTek Computer                | 3        | 3.8%    |
| Qualcomm Atheros Communications | 2        | 2.53%   |
| MediaTek                        | 2        | 2.53%   |
| Linksys                         | 2        | 2.53%   |
| Broadcom                        | 2        | 2.53%   |
| ZyDAS                           | 1        | 1.27%   |
| Sitecom Europe                  | 1        | 1.27%   |
| NetGear                         | 1        | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 8        | 10.13%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 5        | 6.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 3        | 3.8%    |
| Ralink MT7601U Wireless Adapter                                           | 3        | 3.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 3        | 3.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 2        | 2.53%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 2        | 2.53%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                           | 2        | 2.53%   |
| Ralink RT5370 Wireless Adapter                                            | 2        | 2.53%   |
| Ralink RT2561/RT61 rev B 802.11g                                          | 2        | 2.53%   |
| Qualcomm Atheros AR9271 802.11n                                           | 2        | 2.53%   |
| Intel Wireless-AC 9260                                                    | 2        | 2.53%   |
| Intel Wireless 7260                                                       | 2        | 2.53%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]         | 2        | 2.53%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]        | 2        | 2.53%   |
| ZyDAS ZD1211B 802.11g                                                     | 1        | 1.27%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                     | 1        | 1.27%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                 | 1        | 1.27%   |
| TP-Link 802.11n NIC                                                       | 1        | 1.27%   |
| Sitecom Europe 802.11n WLAN Adapter                                       | 1        | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 1        | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                  | 1        | 1.27%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1        | 1.27%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                           | 1        | 1.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 1.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1        | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                   | 1        | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1        | 1.27%   |
| Realtek RTL8187 Wireless Adapter                                          | 1        | 1.27%   |
| Ralink RT5572 Wireless Adapter                                            | 1        | 1.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1        | 1.27%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                      | 1        | 1.27%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                      | 1        | 1.27%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 1        | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 1        | 1.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1        | 1.27%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                | 1        | 1.27%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.27%   |
| MediaTek Wireless                                                         | 1        | 1.27%   |
| MediaTek MI WLAN Adapter                                                  | 1        | 1.27%   |
| Linksys WUSB6400M                                                         | 1        | 1.27%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]             | 1        | 1.27%   |
| Intel Wireless 7265                                                       | 1        | 1.27%   |
| Intel Wireless 3165                                                       | 1        | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 1        | 1.27%   |
| Edimax AC600 USB                                                          | 1        | 1.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                        | 1        | 1.27%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                        | 1        | 1.27%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                 | 1        | 1.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 115      | 46.37%  |
| Intel                    | 78       | 31.45%  |
| Broadcom                 | 24       | 9.68%   |
| Qualcomm Atheros         | 8        | 3.23%   |
| Nvidia                   | 8        | 3.23%   |
| Aquantia                 | 4        | 1.61%   |
| Broadcom Limited         | 3        | 1.21%   |
| D-Link System            | 2        | 0.81%   |
| ASIX Electronics         | 2        | 0.81%   |
| Xiaomi                   | 1        | 0.4%    |
| Samsung Electronics      | 1        | 0.4%    |
| Marvell Technology Group | 1        | 0.4%    |
| Huawei Technologies      | 1        | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101      | 38.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20       | 7.69%   |
| Intel I211 Gigabit Network Connection                             | 11       | 4.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 3.08%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8        | 3.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 2.31%   |
| Nvidia MCP61 Ethernet                                             | 6        | 2.31%   |
| Intel Ethernet Connection I217-V                                  | 6        | 2.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 2.31%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 6        | 2.31%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 1.92%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.92%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.92%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.54%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 4        | 1.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.15%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 1.15%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 3        | 1.15%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.77%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.77%   |
| Intel 82567V-4 Gigabit Network Connection                         | 2        | 0.77%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.77%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.77%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.38%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.38%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.38%   |
| Intel PRO/100 VE Network Connection                               | 1        | 0.38%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.38%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.38%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.38%   |
| Intel Ethernet Converged Network Adapter X520-Q1                  | 1        | 0.38%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.38%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.38%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1        | 0.38%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                | 1        | 0.38%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.38%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 0.38%   |
| Huawei MAR-LX1A                                                   | 1        | 0.38%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.38%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.38%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.38%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 231      | 75.49%  |
| WiFi     | 75       | 24.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 189      | 79.08%  |
| WiFi     | 50       | 20.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 178      | 76.07%  |
| 2     | 47       | 20.09%  |
| 3     | 5        | 2.14%   |
| 4     | 2        | 0.85%   |
| 14    | 1        | 0.43%   |
| 0     | 1        | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 215      | 91.49%  |
| Yes  | 20       | 8.51%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 18       | 34.62%  |
| Intel                           | 16       | 30.77%  |
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
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 18       | 34.62%  |
| Intel AX200 Bluetooth                                  | 7        | 13.46%  |
| Intel Bluetooth wireless interface                     | 4        | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                      | 4        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                       | 3        | 5.77%   |
| Realtek Bluetooth Radio                                | 2        | 3.85%   |
| Qualcomm Atheros AR3011 Bluetooth                      | 2        | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1        | 1.92%   |
| Lite-On Bluetooth Device                               | 1        | 1.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 1        | 1.92%   |
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


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 158      | 44.89%  |
| AMD                                  | 87       | 24.72%  |
| Nvidia                               | 73       | 20.74%  |
| C-Media Electronics                  | 9        | 2.56%   |
| Logitech                             | 3        | 0.85%   |
| Razer USA                            | 2        | 0.57%   |
| Kingston Technology                  | 2        | 0.57%   |
| JMTek                                | 2        | 0.57%   |
| Generalplus Technology               | 2        | 0.57%   |
| Creative Labs                        | 2        | 0.57%   |
| Corsair                              | 2        | 0.57%   |
| XMOS                                 | 1        | 0.28%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.28%   |
| Plantronics                          | 1        | 0.28%   |
| Micro Star International             | 1        | 0.28%   |
| Hewlett-Packard                      | 1        | 0.28%   |
| Focusrite-Novation                   | 1        | 0.28%   |
| Creative Technology                  | 1        | 0.28%   |
| BEHRINGER International              | 1        | 0.28%   |
| ASUSTek Computer                     | 1        | 0.28%   |
| Alesis                               | 1        | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 29       | 7.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 29       | 7.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 22       | 5.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 21       | 5.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 16       | 3.95%   |
| AMD Starship/Matisse HD Audio Controller                                          | 15       | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 3.46%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 9        | 2.22%   |
| Nvidia High Definition Audio Controller                                           | 8        | 1.98%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 8        | 1.98%   |
| Intel 200 Series PCH HD Audio                                                     | 8        | 1.98%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8        | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                        | 7        | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 1.73%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.73%   |
| Nvidia MCP61 High Definition Audio                                                | 6        | 1.48%   |
| Nvidia GP104 High Definition Audio Controller                                     | 6        | 1.48%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 1.48%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                                 | 6        | 1.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 1.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 1.48%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 5        | 1.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 5        | 1.23%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.23%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 0.99%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 0.99%   |
| Nvidia GK104 HDMI Audio Controller                                                | 4        | 0.99%   |
| Nvidia GF106 High Definition Audio Controller                                     | 4        | 0.99%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 0.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 0.99%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 4        | 0.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.74%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.74%   |
| Intel Comet Lake PCH-V cAVS                                                       | 3        | 0.74%   |
| AMD Navi 10 HDMI Audio                                                            | 3        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 0.49%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 0.49%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.49%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.49%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 0.49%   |
| Kingston Technology HyperX 7.1 Audio                                              | 2        | 0.49%   |
| Intel USB PnP Sound Device                                                        | 2        | 0.49%   |
| Intel Audio device                                                                | 2        | 0.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 0.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.49%   |
| Generalplus Technology Usb Audio Device                                           | 2        | 0.49%   |
| C-Media Electronics CM8888 [Oxygen Express]                                       | 2        | 0.49%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.49%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 0.49%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 0.49%   |
| XMOS xCORE USB Audio 2.0                                                          | 1        | 0.25%   |
| Thesycon Systemsoftware & Consulting E30                                          | 1        | 0.25%   |
| Razer USA Razer Kraken USB                                                        | 1        | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 41       | 23.16%  |
| Kingston                   | 39       | 22.03%  |
| SK Hynix                   | 15       | 8.47%   |
| Corsair                    | 15       | 8.47%   |
| G.Skill                    | 12       | 6.78%   |
| Samsung Electronics        | 11       | 6.21%   |
| Crucial                    | 11       | 6.21%   |
| Smart                      | 4        | 2.26%   |
| Team                       | 3        | 1.69%   |
| Patriot                    | 3        | 1.69%   |
| Nanya Technology           | 3        | 1.69%   |
| Elpida                     | 3        | 1.69%   |
| Teikon                     | 2        | 1.13%   |
| HBS                        | 2        | 1.13%   |
| Unknown (ABCD)             | 1        | 0.56%   |
| Unknown (00FFFFFFFFFFFFFF) | 1        | 0.56%   |
| Transcend                  | 1        | 0.56%   |
| Ramaxel Technology         | 1        | 0.56%   |
| Qimonda                    | 1        | 0.56%   |
| Micron Technology          | 1        | 0.56%   |
| Kreton                     | 1        | 0.56%   |
| Goldenmars                 | 1        | 0.56%   |
| Golden Empire              | 1        | 0.56%   |
| GeIL                       | 1        | 0.56%   |
| atermiter                  | 1        | 0.56%   |
| A-DATA Technology          | 1        | 0.56%   |
| Unknown                    | 1        | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                             | 5        | 2.66%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                                | 4        | 2.13%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                   | 3        | 1.6%    |
| SK Hynix RAM HYMP125U64CP8-S6 2048MB DIMM DDR2 49926MT/s                  | 3        | 1.6%    |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                              | 3        | 1.6%    |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s                    | 3        | 1.6%    |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s                     | 3        | 1.6%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                              | 2        | 1.06%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                      | 2        | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s                              | 2        | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                               | 2        | 1.06%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                               | 2        | 1.06%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                   | 2        | 1.06%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                      | 2        | 1.06%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s                                | 2        | 1.06%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s                        | 2        | 1.06%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s                  | 2        | 1.06%   |
| Kingston RAM 2G-UDIMM 2048MB DIMM DDR2 800MT/s                            | 2        | 1.06%   |
| Elpida RAM EBJ41EF8BCFA-DJ-F 4096MB DIMM DDR3 1333MT/s                    | 2        | 1.06%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s                      | 2        | 1.06%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s                    | 2        | 1.06%   |
| Unknown RAM Module 8192MB DIMM SDRAM                                      | 1        | 0.53%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                              | 1        | 0.53%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                                    | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                      | 1        | 0.53%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                               | 1        | 0.53%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                              | 1        | 0.53%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                                    | 1        | 0.53%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                                    | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                                      | 1        | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                              | 1        | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR2 1067MT/s                              | 1        | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                                | 1        | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                               | 1        | 0.53%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                    | 1        | 0.53%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                                    | 1        | 0.53%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s                               | 1        | 0.53%   |
| Unknown RAM CS4S2666D19321C 32GB SODIMM DDR4 2667MT/s                     | 1        | 0.53%   |
| Unknown RAM 3634543235363032304555322E3543322020 2048MB DIMM DDR2 800MT/s | 1        | 0.53%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                     | 1        | 0.53%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s                        | 1        | 0.53%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s                     | 1        | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s            | 1        | 0.53%   |
| Unknown (00FFFFFFFFFFFFFF) RAM 864AY-667D4 2048MB DIMM DDR2 667MT/s       | 1        | 0.53%   |
| Transcend RAM JM667QLU-2G 2048MB DIMM DDR2 667MT/s                        | 1        | 0.53%   |
| Teikon RAM TMT251U6CFR8C-PBH 4096MB DIMM DDR3 1333MT/s                    | 1        | 0.53%   |
| Teikon RAM TMT225U6FR8C-H9HC 2048MB DIMM DDR3 1066MT/s                    | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                        | 1        | 0.53%   |
| Smart RAM SH564568FH8N6PHSFR 2048MB DIMM DDR3 1067MT/s                    | 1        | 0.53%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s                       | 1        | 0.53%   |
| Smart RAM SH564568FH8N6PHSF 2GB DIMM DDR3 1333MT/s                        | 1        | 0.53%   |
| Smart RAM SH564288FH8N6PHSF 1GB DIMM DDR3 1333MT/s                        | 1        | 0.53%   |
| SK Hynix RAM MPPU4GBPC1600 00 4096MB DIMM 533MT/s                         | 1        | 0.53%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2400MT/s                             | 1        | 0.53%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1600MT/s                             | 1        | 0.53%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1333MT/s                             | 1        | 0.53%   |
| SK Hynix RAM MMXIV 4096MB DIMM DDR3 1600MT/s                              | 1        | 0.53%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s                       | 1        | 0.53%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4096MB DIMM DDR3 1600MT/s                   | 1        | 0.53%   |
| SK Hynix RAM HMT41GU7AFR8C-PB 8192MB DIMM DDR3 1333MT/s                   | 1        | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 69       | 43.95%  |
| DDR4    | 39       | 24.84%  |
| DDR2    | 18       | 11.46%  |
| Unknown | 11       | 7.01%   |
| SDRAM   | 9        | 5.73%   |
| DDR     | 9        | 5.73%   |
| LPDDR4  | 1        | 0.64%   |
| DRAM    | 1        | 0.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 147      | 97.35%  |
| SODIMM | 4        | 2.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 46       | 27.71%  |
| 8192  | 42       | 25.3%   |
| 4096  | 42       | 25.3%   |
| 16384 | 20       | 12.05%  |
| 1024  | 9        | 5.42%   |
| 32768 | 6        | 3.61%   |
| 512   | 1        | 0.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 33       | 20.25%  |
| 1600    | 32       | 19.63%  |
| 800     | 14       | 8.59%   |
| 3200    | 12       | 7.36%   |
| 2400    | 12       | 7.36%   |
| 667     | 11       | 6.75%   |
| 533     | 7        | 4.29%   |
| 2667    | 6        | 3.68%   |
| Unknown | 4        | 2.45%   |
| 49926   | 3        | 1.84%   |
| 2666    | 3        | 1.84%   |
| 1067    | 3        | 1.84%   |
| 3733    | 2        | 1.23%   |
| 3600    | 2        | 1.23%   |
| 3466    | 2        | 1.23%   |
| 3400    | 2        | 1.23%   |
| 1867    | 2        | 1.23%   |
| 400     | 2        | 1.23%   |
| 3866    | 1        | 0.61%   |
| 3100    | 1        | 0.61%   |
| 2933    | 1        | 0.61%   |
| 2800    | 1        | 0.61%   |
| 2473    | 1        | 0.61%   |
| 2133    | 1        | 0.61%   |
| 2048    | 1        | 0.61%   |
| 1866    | 1        | 0.61%   |
| 1400    | 1        | 0.61%   |
| 1066    | 1        | 0.61%   |
| 266     | 1        | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 8        | 34.78%  |
| Brother Industries     | 4        | 17.39%  |
| Seiko Epson            | 3        | 13.04%  |
| Samsung Electronics    | 2        | 8.7%    |
| Canon                  | 2        | 8.7%    |
| QinHeng Electronics    | 1        | 4.35%   |
| Panasonic (Matsushita) | 1        | 4.35%   |
| Lexmark International  | 1        | 4.35%   |
| Bixolon                | 1        | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| HP LaserJet Professional P 1102w           | 2        | 8.33%   |
| Brother Printer                            | 2        | 8.33%   |
| Seiko Epson WF-2010 Series                 | 1        | 4.17%   |
| Seiko Epson Printer                        | 1        | 4.17%   |
| Seiko Epson L312 Series                    | 1        | 4.17%   |
| Samsung M2020 Series                       | 1        | 4.17%   |
| Samsung CLX-4190 Series                    | 1        | 4.17%   |
| QinHeng CH340S                             | 1        | 4.17%   |
| Panasonic (Matsushita) KX-MB2130RU         | 1        | 4.17%   |
| Lexmark International InkJet Color Printer | 1        | 4.17%   |
| HP Officejet 4500 G510a-f                  | 1        | 4.17%   |
| HP LaserJet 1022                           | 1        | 4.17%   |
| HP LaserJet 1020                           | 1        | 4.17%   |
| HP Deskjet F4500 series                    | 1        | 4.17%   |
| HP Deskjet 3050 J610 series                | 1        | 4.17%   |
| HP DeskJet 2130 series                     | 1        | 4.17%   |
| Canon Pixma iP4500 Printer                 | 1        | 4.17%   |
| Canon LBP7010C/7018C                       | 1        | 4.17%   |
| Brother HL-3170CDW series                  | 1        | 4.17%   |
| Brother HL-1440 Laser Printer              | 1        | 4.17%   |
| Brother DCP-L2540DW                        | 1        | 4.17%   |
| Bixolon Printer                            | 1        | 4.17%   |

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
| Microsoft                     | 2        | 7.69%   |
| Creative Technology           | 2        | 7.69%   |
| Apple                         | 2        | 7.69%   |
| Z-Star Microelectronics       | 1        | 3.85%   |
| Sunplus Innovation Technology | 1        | 3.85%   |
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
| Sunplus HK 1080P K20Pro                      | 1        | 3.7%    |
| Microsoft LifeCam VX-2000                    | 1        | 3.7%    |
| Microsoft LifeCam HD-3000                    | 1        | 3.7%    |
| Microdia Integrated Camera                   | 1        | 3.7%    |
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
| 0     | 216      | 92.7%   |
| 1     | 14       | 6.01%   |
| 2     | 3        | 1.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 27.78%  |
| Communication controller | 4        | 22.22%  |
| Net/wireless             | 3        | 16.67%  |
| Multimedia controller    | 2        | 11.11%  |
| Unassigned class         | 1        | 5.56%   |
| Tv card                  | 1        | 5.56%   |
| Storage/ata              | 1        | 5.56%   |
| Network                  | 1        | 5.56%   |

