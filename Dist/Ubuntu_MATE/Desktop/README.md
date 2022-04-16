Ubuntu MATE - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 647

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | X99P-SLI-CF                 | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| ASUSTek       | Z97-K                       | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| Unknown       | Unknown                     | [d7811dbd43](https://linux-hardware.org/?probe=d7811dbd43) | Apr 14, 2022 |
| MSI           | MAG B550M MORTAR            | [7a9f6e1de7](https://linux-hardware.org/?probe=7a9f6e1de7) | Apr 13, 2022 |
| Dell          | 03NVJ6 A00                  | [c640615939](https://linux-hardware.org/?probe=c640615939) | Apr 10, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| Gigabyte      | H470M DS3H                  | [bbfc43c637](https://linux-hardware.org/?probe=bbfc43c637) | Apr 05, 2022 |
| ASRock        | N68C-GS FX                  | [5f45322780](https://linux-hardware.org/?probe=5f45322780) | Apr 04, 2022 |
| Dell          | 06X1TJ A00                  | [42cf748563](https://linux-hardware.org/?probe=42cf748563) | Apr 03, 2022 |
| ASUSTek       | A88X-GAMER                  | [8340e366fc](https://linux-hardware.org/?probe=8340e366fc) | Mar 28, 2022 |
| HP            | 802E                        | [b15f756d65](https://linux-hardware.org/?probe=b15f756d65) | Mar 21, 2022 |
| HP            | 3397                        | [fe1ae429b1](https://linux-hardware.org/?probe=fe1ae429b1) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [220c4f69b0](https://linux-hardware.org/?probe=220c4f69b0) | Mar 15, 2022 |
| ASUSTek       | A55BM-E                     | [7bbbcc53c1](https://linux-hardware.org/?probe=7bbbcc53c1) | Mar 14, 2022 |
| Dell          | OptiPlex 980                | [14cf2b23f7](https://linux-hardware.org/?probe=14cf2b23f7) | Mar 14, 2022 |
| ASUSTek       | M4A79XTD EVO                | [d59f0b152c](https://linux-hardware.org/?probe=d59f0b152c) | Mar 10, 2022 |
| Gigabyte      | Z68XP-UD3                   | [6382c70064](https://linux-hardware.org/?probe=6382c70064) | Mar 07, 2022 |
| Medion        | MS-7797                     | [88982d8ccb](https://linux-hardware.org/?probe=88982d8ccb) | Mar 05, 2022 |
| ASRock        | B450M Pro4                  | [b18f6804d6](https://linux-hardware.org/?probe=b18f6804d6) | Mar 02, 2022 |
| ECS           | A785GM-AD3                  | [43c3e7c4a0](https://linux-hardware.org/?probe=43c3e7c4a0) | Mar 02, 2022 |
| Intel         | H55                         | [2f52a73f85](https://linux-hardware.org/?probe=2f52a73f85) | Feb 27, 2022 |
| Pegatron      | Narra6                      | [ad9a06f14d](https://linux-hardware.org/?probe=ad9a06f14d) | Feb 25, 2022 |
| ASUSTek       | PRIME B450M-A II            | [09aca1c435](https://linux-hardware.org/?probe=09aca1c435) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | [35c00d5889](https://linux-hardware.org/?probe=35c00d5889) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | [265235f4f4](https://linux-hardware.org/?probe=265235f4f4) | Feb 21, 2022 |
| ECS           | G41T-M7                     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| ECS           | A785GM-AD3                  | [b6459dbb39](https://linux-hardware.org/?probe=b6459dbb39) | Feb 12, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [e58751112a](https://linux-hardware.org/?probe=e58751112a) | Feb 11, 2022 |
| ASUSTek       | PRIME B250M-K               | [6f66651cd1](https://linux-hardware.org/?probe=6f66651cd1) | Feb 10, 2022 |
| ASUSTek       | P5W DH Deluxe               | [7c3fa0c43b](https://linux-hardware.org/?probe=7c3fa0c43b) | Feb 08, 2022 |
| Gigabyte      | GA-990XA-UD3                | [6bb9884c12](https://linux-hardware.org/?probe=6bb9884c12) | Feb 08, 2022 |
| Gigabyte      | F2A88XM-D3HP                | [c6783b6b8b](https://linux-hardware.org/?probe=c6783b6b8b) | Feb 07, 2022 |
| Gigabyte      | GA-990XA-UD3                | [74ebb0645d](https://linux-hardware.org/?probe=74ebb0645d) | Feb 06, 2022 |
| ASUSTek       | H61M-K                      | [0e2c677ddc](https://linux-hardware.org/?probe=0e2c677ddc) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | [4dc312f4f3](https://linux-hardware.org/?probe=4dc312f4f3) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | [d70247596b](https://linux-hardware.org/?probe=d70247596b) | Feb 02, 2022 |
| Lenovo        | SDK0E50510 WIN              | [f317005b0a](https://linux-hardware.org/?probe=f317005b0a) | Feb 02, 2022 |
| Lenovo        | NOK                         | [8905840b45](https://linux-hardware.org/?probe=8905840b45) | Feb 02, 2022 |
| HP            | 8434 11                     | [76a7851e7f](https://linux-hardware.org/?probe=76a7851e7f) | Jan 28, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [fab2b2828e](https://linux-hardware.org/?probe=fab2b2828e) | Jan 26, 2022 |
| ASRock        | Z77 Pro4                    | [8062682731](https://linux-hardware.org/?probe=8062682731) | Jan 25, 2022 |
| Gigabyte      | H410M H V3                  | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [868c5fe3a4](https://linux-hardware.org/?probe=868c5fe3a4) | Jan 24, 2022 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [a4b48a8427](https://linux-hardware.org/?probe=a4b48a8427) | Jan 23, 2022 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [622bf721f3](https://linux-hardware.org/?probe=622bf721f3) | Jan 23, 2022 |
| ASRock        | G41C-VS                     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| HP            | 8434 11                     | [6bb20c8d64](https://linux-hardware.org/?probe=6bb20c8d64) | Jan 20, 2022 |
| HP            | 8455                        | [fbf272366c](https://linux-hardware.org/?probe=fbf272366c) | Jan 20, 2022 |
| ASUSTek       | P5LD2                       | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Lenovo        | NOK                         | [111a1caac8](https://linux-hardware.org/?probe=111a1caac8) | Jan 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | [597677191c](https://linux-hardware.org/?probe=597677191c) | Jan 19, 2022 |
| Dell          | 0UG982                      | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | [ebef716d33](https://linux-hardware.org/?probe=ebef716d33) | Jan 19, 2022 |
| Dell          | 0FH884                      | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| HP            | 18E7                        | [b68364ed90](https://linux-hardware.org/?probe=b68364ed90) | Jan 19, 2022 |
| Dell          | 0HY9JP A02                  | [8314cd9ba6](https://linux-hardware.org/?probe=8314cd9ba6) | Jan 19, 2022 |
| Dell          | 0UG982                      | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| Dell          | 0UG982                      | [597dfb85b7](https://linux-hardware.org/?probe=597dfb85b7) | Jan 19, 2022 |
| HP            | 18E7                        | [9fedcb7ff7](https://linux-hardware.org/?probe=9fedcb7ff7) | Jan 18, 2022 |
| HP            | 18E7                        | [48871270a2](https://linux-hardware.org/?probe=48871270a2) | Jan 18, 2022 |
| HP            | 18E7                        | [ca38c856e1](https://linux-hardware.org/?probe=ca38c856e1) | Jan 18, 2022 |
| HP            | 18E7                        | [a4df88b38f](https://linux-hardware.org/?probe=a4df88b38f) | Jan 18, 2022 |
| HP            | 18E7                        | [a745b9add0](https://linux-hardware.org/?probe=a745b9add0) | Jan 18, 2022 |
| HP            | 18E7                        | [b69abe6fd4](https://linux-hardware.org/?probe=b69abe6fd4) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | [9753f9164a](https://linux-hardware.org/?probe=9753f9164a) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | [2d7a6e6cb6](https://linux-hardware.org/?probe=2d7a6e6cb6) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | [51484889f9](https://linux-hardware.org/?probe=51484889f9) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | [4ca462c89a](https://linux-hardware.org/?probe=4ca462c89a) | Jan 18, 2022 |
| Dell          | 0HY9JP A02                  | [c4c9f4b0a9](https://linux-hardware.org/?probe=c4c9f4b0a9) | Jan 18, 2022 |
| HP            | 8434 11                     | [4a128d2bb2](https://linux-hardware.org/?probe=4a128d2bb2) | Jan 18, 2022 |
| HP            | 18E7                        | [97d4bc7367](https://linux-hardware.org/?probe=97d4bc7367) | Jan 18, 2022 |
| Lenovo        | NOK                         | [7ae2819a6f](https://linux-hardware.org/?probe=7ae2819a6f) | Jan 18, 2022 |
| HP            | 18E7                        | [e86d0cc284](https://linux-hardware.org/?probe=e86d0cc284) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | [022f56a960](https://linux-hardware.org/?probe=022f56a960) | Jan 18, 2022 |
| HP            | 18E7                        | [0d2a09f683](https://linux-hardware.org/?probe=0d2a09f683) | Jan 18, 2022 |
| HP            | 8455                        | [639182896b](https://linux-hardware.org/?probe=639182896b) | Jan 18, 2022 |
| ASRock        | B450M Pro4                  | [556d0fb884](https://linux-hardware.org/?probe=556d0fb884) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [a96f2def6d](https://linux-hardware.org/?probe=a96f2def6d) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| ASUSTek       | H81M-C                      | [51d8172f5b](https://linux-hardware.org/?probe=51d8172f5b) | Jan 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6438d5a5af](https://linux-hardware.org/?probe=6438d5a5af) | Jan 15, 2022 |
| ASUSTek       | H81M-C                      | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| ZOTAC         | NM10                        | [d758728651](https://linux-hardware.org/?probe=d758728651) | Jan 14, 2022 |
| ASUSTek       | H81M-K                      | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| HP            | 3397                        | [38a4d731fe](https://linux-hardware.org/?probe=38a4d731fe) | Jan 08, 2022 |
| Gigabyte      | B450M S2H                   | [858d718984](https://linux-hardware.org/?probe=858d718984) | Jan 07, 2022 |
| Dell          | 032W55 A03                  | [f3838abaaf](https://linux-hardware.org/?probe=f3838abaaf) | Jan 04, 2022 |
| ASRock        | 870iCafe R2.0               | [f67cc91b2e](https://linux-hardware.org/?probe=f67cc91b2e) | Dec 31, 2021 |
| MSI           | H81M-P33                    | [e637f730e7](https://linux-hardware.org/?probe=e637f730e7) | Dec 31, 2021 |
| MSI           | H81M-P33                    | [4c225dc457](https://linux-hardware.org/?probe=4c225dc457) | Dec 30, 2021 |
| Gigabyte      | H67MA-UD2H-B3               | [e32af6a3de](https://linux-hardware.org/?probe=e32af6a3de) | Dec 26, 2021 |
| MSI           | 760GM-P23                   | [62abb9d0ef](https://linux-hardware.org/?probe=62abb9d0ef) | Dec 25, 2021 |
| ASRock        | 970 Extreme4                | [1fbef2b76c](https://linux-hardware.org/?probe=1fbef2b76c) | Dec 23, 2021 |
| ASUSTek       | PRIME B360M-K               | [8df64a7f80](https://linux-hardware.org/?probe=8df64a7f80) | Dec 21, 2021 |
| ASUSTek       | H61M-K                      | [8f53f4e97c](https://linux-hardware.org/?probe=8f53f4e97c) | Dec 19, 2021 |
| MSI           | H61M-S20                    | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| ASUSTek       | H81M-A                      | [50acb69e6e](https://linux-hardware.org/?probe=50acb69e6e) | Dec 02, 2021 |
| HP            | 3646h                       | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | PRIME X570-P                | [6b7ec76b64](https://linux-hardware.org/?probe=6b7ec76b64) | Nov 28, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | [9b13286f92](https://linux-hardware.org/?probe=9b13286f92) | Nov 28, 2021 |
| MSI           | H81M-P33                    | [3d2583b1f1](https://linux-hardware.org/?probe=3d2583b1f1) | Nov 26, 2021 |
| Dell          | 0T656F A01                  | [06f4633f1b](https://linux-hardware.org/?probe=06f4633f1b) | Nov 24, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| ASUSTek       | AT3IONT-I                   | [b8f5329824](https://linux-hardware.org/?probe=b8f5329824) | Nov 22, 2021 |
| Dell          | 0M017G A00                  | [da444f9b8f](https://linux-hardware.org/?probe=da444f9b8f) | Nov 22, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [a13103a9ad](https://linux-hardware.org/?probe=a13103a9ad) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |
| Dell          | 0G261D A00                  | [1bb376a60b](https://linux-hardware.org/?probe=1bb376a60b) | Nov 17, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [8a6de2970d](https://linux-hardware.org/?probe=8a6de2970d) | Nov 15, 2021 |
| ASRock        | B450M Pro4                  | [2cdd151d75](https://linux-hardware.org/?probe=2cdd151d75) | Nov 14, 2021 |
| Dell          | 03NVJ6 A00                  | [61bfe5dfa7](https://linux-hardware.org/?probe=61bfe5dfa7) | Nov 11, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [1971073b86](https://linux-hardware.org/?probe=1971073b86) | Nov 10, 2021 |
| ASUSTek       | M4A78-E                     | [dd8a96b615](https://linux-hardware.org/?probe=dd8a96b615) | Nov 09, 2021 |
| ASUSTek       | M4A78-E                     | [89aff3881c](https://linux-hardware.org/?probe=89aff3881c) | Nov 09, 2021 |
| ASUSTek       | A55BM-E                     | [fd25737c58](https://linux-hardware.org/?probe=fd25737c58) | Nov 09, 2021 |
| ASRock        | B450M Pro4                  | [4138b9cffa](https://linux-hardware.org/?probe=4138b9cffa) | Nov 08, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [e21897758d](https://linux-hardware.org/?probe=e21897758d) | Nov 07, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [914d585adc](https://linux-hardware.org/?probe=914d585adc) | Nov 07, 2021 |
| Gigabyte      | H97M-D3H                    | [05e3caa05c](https://linux-hardware.org/?probe=05e3caa05c) | Nov 02, 2021 |
| ASRock        | B450M Pro4                  | [60ffb9d428](https://linux-hardware.org/?probe=60ffb9d428) | Oct 31, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | [4946a6a02c](https://linux-hardware.org/?probe=4946a6a02c) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | [0ad429cea5](https://linux-hardware.org/?probe=0ad429cea5) | Oct 26, 2021 |
| ASUSTek       | M5A78L LE                   | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [27b0a66ceb](https://linux-hardware.org/?probe=27b0a66ceb) | Oct 20, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| Gigabyte      | B450M S2H                   | [fe1c549ed6](https://linux-hardware.org/?probe=fe1c549ed6) | Oct 05, 2021 |
| Dell          | 08NPPY A00                  | [f0ff9a911e](https://linux-hardware.org/?probe=f0ff9a911e) | Oct 03, 2021 |
| Gigabyte      | Z97-HD3                     | [5f6c245dc5](https://linux-hardware.org/?probe=5f6c245dc5) | Sep 28, 2021 |
| MSI           | H61M-P23                    | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| Gigabyte      | Z97-HD3                     | [6a2e918e37](https://linux-hardware.org/?probe=6a2e918e37) | Sep 28, 2021 |
| Dell          | 03NVJ6 A00                  | [5422d3bf1d](https://linux-hardware.org/?probe=5422d3bf1d) | Sep 27, 2021 |
| Intel         | DG31PR AAD97573-206         | [060da3d3ab](https://linux-hardware.org/?probe=060da3d3ab) | Sep 26, 2021 |
| HP            | 8265                        | [f840aed42d](https://linux-hardware.org/?probe=f840aed42d) | Sep 21, 2021 |
| ASUSTek       | PRIME B450M-A               | [f93c2362ff](https://linux-hardware.org/?probe=f93c2362ff) | Sep 21, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [a5211dc1bb](https://linux-hardware.org/?probe=a5211dc1bb) | Sep 21, 2021 |
| Gigabyte      | B450M S2H                   | [13298e0f6b](https://linux-hardware.org/?probe=13298e0f6b) | Sep 19, 2021 |
| HP            | 3397                        | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| HP            | 1497                        | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| Gigabyte      | B450M S2H                   | [022e2ca406](https://linux-hardware.org/?probe=022e2ca406) | Sep 16, 2021 |
| ASRock        | H110M-STX                   | [6bb90d3b07](https://linux-hardware.org/?probe=6bb90d3b07) | Sep 16, 2021 |
| Medion        | MS-7797                     | [f2f5579dc5](https://linux-hardware.org/?probe=f2f5579dc5) | Sep 15, 2021 |
| Medion        | MS-7797                     | [6ca6bee736](https://linux-hardware.org/?probe=6ca6bee736) | Sep 15, 2021 |
| Intel         | DH67CL AAG10212-204         | [e9d68ab5e4](https://linux-hardware.org/?probe=e9d68ab5e4) | Sep 09, 2021 |
| HP            | 3396                        | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
| ASRock        | H110M-STX                   | [a0b807eb42](https://linux-hardware.org/?probe=a0b807eb42) | Aug 30, 2021 |
| MSI           | Z370 PC PRO                 | [c594736488](https://linux-hardware.org/?probe=c594736488) | Aug 30, 2021 |
| ASRock        | B75M-DGS R2.0               | [16250b0c12](https://linux-hardware.org/?probe=16250b0c12) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [41e440c2e5](https://linux-hardware.org/?probe=41e440c2e5) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [e086d2eb61](https://linux-hardware.org/?probe=e086d2eb61) | Aug 29, 2021 |
| MSI           | 2A9C                        | [57601d98f3](https://linux-hardware.org/?probe=57601d98f3) | Aug 28, 2021 |
| MSI           | 2A9C                        | [2fb08ccc03](https://linux-hardware.org/?probe=2fb08ccc03) | Aug 28, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| MSI           | B450M PRO-M2 MAX            | [b28b036f78](https://linux-hardware.org/?probe=b28b036f78) | Aug 22, 2021 |
| ASRock        | M3A785GMH/128M              | [4ace1ea1ac](https://linux-hardware.org/?probe=4ace1ea1ac) | Aug 15, 2021 |
| MSI           | X79A-GD45                   | [c5b78e1a01](https://linux-hardware.org/?probe=c5b78e1a01) | Aug 13, 2021 |
| Gigabyte      | B550M DS3H                  | [6776a424d5](https://linux-hardware.org/?probe=6776a424d5) | Aug 11, 2021 |
| Dell          | 05GD68 A00                  | [bbfbd42562](https://linux-hardware.org/?probe=bbfbd42562) | Aug 07, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [c861e28d21](https://linux-hardware.org/?probe=c861e28d21) | Aug 05, 2021 |
| ASRock        | Q1900M                      | [700f4a0ca1](https://linux-hardware.org/?probe=700f4a0ca1) | Aug 02, 2021 |
| Dell          | 08NPPY A00                  | [fe0cf5b120](https://linux-hardware.org/?probe=fe0cf5b120) | Aug 01, 2021 |
| Dell          | 08NPPY A00                  | [e706b18dd8](https://linux-hardware.org/?probe=e706b18dd8) | Aug 01, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| ASUSTek       | M2N68-AM Plus               | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [e8e43c77ca](https://linux-hardware.org/?probe=e8e43c77ca) | Jul 23, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [6dcb19e468](https://linux-hardware.org/?probe=6dcb19e468) | Jul 23, 2021 |
| ASUSTek       | P8H67-M LE                  | [db7104ee10](https://linux-hardware.org/?probe=db7104ee10) | Jul 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | [647fe69592](https://linux-hardware.org/?probe=647fe69592) | Jul 22, 2021 |
| MSI           | H61M-E33                    | [0d1a9284a9](https://linux-hardware.org/?probe=0d1a9284a9) | Jul 17, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [011a83c682](https://linux-hardware.org/?probe=011a83c682) | Jul 17, 2021 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [6001052e23](https://linux-hardware.org/?probe=6001052e23) | Jul 15, 2021 |
| Lenovo        | Tilapia CRB                 | [da1f0d65ec](https://linux-hardware.org/?probe=da1f0d65ec) | Jul 12, 2021 |
| Unknown       | TB-4000                     | [fb3e1984b0](https://linux-hardware.org/?probe=fb3e1984b0) | Jul 10, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [ae14beb6fd](https://linux-hardware.org/?probe=ae14beb6fd) | Jul 09, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [7adcf7dc7c](https://linux-hardware.org/?probe=7adcf7dc7c) | Jul 09, 2021 |
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
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8bb06ce851](https://linux-hardware.org/?probe=8bb06ce851) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [0616fdb086](https://linux-hardware.org/?probe=0616fdb086) | Jun 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [3d47d96665](https://linux-hardware.org/?probe=3d47d96665) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [c9bea47caa](https://linux-hardware.org/?probe=c9bea47caa) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [c9c757474a](https://linux-hardware.org/?probe=c9c757474a) | Jun 12, 2021 |
| ASRock        | ALiveXFire-eSATA2           | [17af721bae](https://linux-hardware.org/?probe=17af721bae) | Jun 10, 2021 |
| Gigabyte      | Z97-HD3                     | [1ab4ff25ab](https://linux-hardware.org/?probe=1ab4ff25ab) | Jun 10, 2021 |
| ASUSTek       | P8B75-M                     | [d732611ebb](https://linux-hardware.org/?probe=d732611ebb) | Jun 02, 2021 |
| Gigabyte      | GA-870A-UD3                 | [3f2f789273](https://linux-hardware.org/?probe=3f2f789273) | Jun 01, 2021 |
| Lenovo        | 3102 NOK                    | [3d1a8cffc3](https://linux-hardware.org/?probe=3d1a8cffc3) | May 31, 2021 |
| Dell          | 0KRC95 A00                  | [913ea68973](https://linux-hardware.org/?probe=913ea68973) | May 31, 2021 |
| Dell          | 0PC5F7 A02                  | [86611a5efe](https://linux-hardware.org/?probe=86611a5efe) | May 31, 2021 |
| Inventec      | Z CLASS A02                 | [7fc4815cbd](https://linux-hardware.org/?probe=7fc4815cbd) | May 29, 2021 |
| ASUSTek       | GL12CX                      | [d95dd524bc](https://linux-hardware.org/?probe=d95dd524bc) | May 28, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [cf31dd498a](https://linux-hardware.org/?probe=cf31dd498a) | May 26, 2021 |
| Gigabyte      | B450 AORUS M                | [a9539e0359](https://linux-hardware.org/?probe=a9539e0359) | May 24, 2021 |
| Wistron       | ProLiant ML110 G6           | [d328ce9f69](https://linux-hardware.org/?probe=d328ce9f69) | May 18, 2021 |
| Dell          | 02YYK5 A01                  | [6b9dbebe2f](https://linux-hardware.org/?probe=6b9dbebe2f) | May 18, 2021 |
| Acer          | Board                       | [7f9d35f468](https://linux-hardware.org/?probe=7f9d35f468) | May 18, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [f1592b156b](https://linux-hardware.org/?probe=f1592b156b) | May 16, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [dec38c20c6](https://linux-hardware.org/?probe=dec38c20c6) | May 15, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [bbefe7273f](https://linux-hardware.org/?probe=bbefe7273f) | May 13, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [33a95ff348](https://linux-hardware.org/?probe=33a95ff348) | May 10, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [40a8a145e6](https://linux-hardware.org/?probe=40a8a145e6) | May 10, 2021 |
| ASUSTek       | M2N68-AM Plus               | [7761ccf4be](https://linux-hardware.org/?probe=7761ccf4be) | May 07, 2021 |
| ASUSTek       | UN45H                       | [714a70d40a](https://linux-hardware.org/?probe=714a70d40a) | May 07, 2021 |
| Dell          | 06D7TR A00                  | [9db6c930c1](https://linux-hardware.org/?probe=9db6c930c1) | May 06, 2021 |
| ASUSTek       | UN45H                       | [efc8ac4c79](https://linux-hardware.org/?probe=efc8ac4c79) | May 06, 2021 |
| ASUSTek       | M2N68-AM Plus               | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [9ff1a95290](https://linux-hardware.org/?probe=9ff1a95290) | May 01, 2021 |
| Gigabyte      | B150-HD3-CF                 | [e91c8823fa](https://linux-hardware.org/?probe=e91c8823fa) | Apr 28, 2021 |
| Pegatron      | Benicia                     | [517b7af416](https://linux-hardware.org/?probe=517b7af416) | Apr 22, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [289a9d70d9](https://linux-hardware.org/?probe=289a9d70d9) | Apr 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [d5310b7f74](https://linux-hardware.org/?probe=d5310b7f74) | Apr 15, 2021 |
| MSI           | Z97 GAMING 5                | [21501b34c2](https://linux-hardware.org/?probe=21501b34c2) | Apr 15, 2021 |
| Unknown       | NF-MCP61                    | [265d75e8f5](https://linux-hardware.org/?probe=265d75e8f5) | Apr 12, 2021 |
| Pegatron      | Benicia                     | [eee4525e5f](https://linux-hardware.org/?probe=eee4525e5f) | Apr 10, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [c2aed97877](https://linux-hardware.org/?probe=c2aed97877) | Apr 08, 2021 |
| MSI           | Z97 GAMING 5                | [946c22503a](https://linux-hardware.org/?probe=946c22503a) | Apr 07, 2021 |
| Gigabyte      | B450M H                     | [d1a51a8680](https://linux-hardware.org/?probe=d1a51a8680) | Apr 04, 2021 |
| Dell          | 0F6X5P A00                  | [16218d28da](https://linux-hardware.org/?probe=16218d28da) | Apr 04, 2021 |
| Gigabyte      | P31-S3G                     | [8600b9ee23](https://linux-hardware.org/?probe=8600b9ee23) | Apr 02, 2021 |
| ASUSTek       | M5A78L/USB3                 | [9afaeda84f](https://linux-hardware.org/?probe=9afaeda84f) | Apr 01, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [db1ca65bed](https://linux-hardware.org/?probe=db1ca65bed) | Apr 01, 2021 |
| Pegatron      | Benicia                     | [9b259bef44](https://linux-hardware.org/?probe=9b259bef44) | Apr 01, 2021 |
| Pegatron      | Benicia                     | [4e2a1c50d1](https://linux-hardware.org/?probe=4e2a1c50d1) | Apr 01, 2021 |
| HP            | 1632                        | [c6df0e432e](https://linux-hardware.org/?probe=c6df0e432e) | Mar 31, 2021 |
| HP            | 3397                        | [e5812883ce](https://linux-hardware.org/?probe=e5812883ce) | Mar 31, 2021 |
| ASUSTek       | M5A97 R2.0                  | [1509fc7671](https://linux-hardware.org/?probe=1509fc7671) | Mar 31, 2021 |
| HP            | 1632                        | [50fc7fcff6](https://linux-hardware.org/?probe=50fc7fcff6) | Mar 30, 2021 |
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
| H61M          | 5123660003                  | [4aec213a10](https://linux-hardware.org/?probe=4aec213a10) | Mar 09, 2021 |
| Gigabyte      | Z77-D3H                     | [2af8335e88](https://linux-hardware.org/?probe=2af8335e88) | Mar 09, 2021 |
| H61M          | 5123660003                  | [7a6ac13ee4](https://linux-hardware.org/?probe=7a6ac13ee4) | Mar 09, 2021 |
| MSI           | B85M-P33                    | [e7d2bb8e63](https://linux-hardware.org/?probe=e7d2bb8e63) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | [957f68f2b7](https://linux-hardware.org/?probe=957f68f2b7) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | [839bc4873c](https://linux-hardware.org/?probe=839bc4873c) | Mar 08, 2021 |
| MSI           | G41M-S01                    | [e375637dd3](https://linux-hardware.org/?probe=e375637dd3) | Mar 07, 2021 |
| MSI           | Z370-A PRO                  | [b5cf5849a1](https://linux-hardware.org/?probe=b5cf5849a1) | Mar 06, 2021 |
| Acer          | Aspire GX-785               | [f9bff3e5ad](https://linux-hardware.org/?probe=f9bff3e5ad) | Mar 06, 2021 |
| HP            | 2B2C                        | [20c11c9bbc](https://linux-hardware.org/?probe=20c11c9bbc) | Mar 04, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [e4437002b3](https://linux-hardware.org/?probe=e4437002b3) | Mar 04, 2021 |
| Medion        | B460H6-EM                   | [2ab61e6080](https://linux-hardware.org/?probe=2ab61e6080) | Mar 03, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [7c1ac98fc7](https://linux-hardware.org/?probe=7c1ac98fc7) | Mar 02, 2021 |
| Dell          | 0MWYPT A01                  | [f418cb6b18](https://linux-hardware.org/?probe=f418cb6b18) | Mar 01, 2021 |
| Lenovo        | Board                       | [47fadb4fa4](https://linux-hardware.org/?probe=47fadb4fa4) | Feb 27, 2021 |
| Lenovo        | Board                       | [0a73258a20](https://linux-hardware.org/?probe=0a73258a20) | Feb 26, 2021 |
| HP            | ProLiant MicroServer        | [eb757aee01](https://linux-hardware.org/?probe=eb757aee01) | Feb 26, 2021 |
| Intel         | DG31PR AAD97573-306         | [e6e8f6870c](https://linux-hardware.org/?probe=e6e8f6870c) | Feb 22, 2021 |
| Dell          | 03NVJ6 A00                  | [f1349be70a](https://linux-hardware.org/?probe=f1349be70a) | Feb 19, 2021 |
| Unknown       | XH61X000.100                | [029de8905d](https://linux-hardware.org/?probe=029de8905d) | Feb 17, 2021 |
| JINGSHA       | Board                       | [01ab676e78](https://linux-hardware.org/?probe=01ab676e78) | Feb 15, 2021 |
| Dell          | 08WKV3 A00                  | [5f126b3966](https://linux-hardware.org/?probe=5f126b3966) | Feb 15, 2021 |
| Dell          | 03NVJ6 A00                  | [87f43dfecd](https://linux-hardware.org/?probe=87f43dfecd) | Feb 12, 2021 |
| MSI           | B85M GAMING                 | [bd107eb4ae](https://linux-hardware.org/?probe=bd107eb4ae) | Feb 10, 2021 |
| Gigabyte      | MZBAYAB-00                  | [fa48450d71](https://linux-hardware.org/?probe=fa48450d71) | Feb 09, 2021 |
| ASUSTek       | P8P67 PRO                   | [bbff698cb8](https://linux-hardware.org/?probe=bbff698cb8) | Feb 09, 2021 |
| HP            | ProLiant MicroServer        | [394af8312b](https://linux-hardware.org/?probe=394af8312b) | Feb 07, 2021 |
| HP            | ProLiant MicroServer        | [0e61287ad7](https://linux-hardware.org/?probe=0e61287ad7) | Feb 07, 2021 |
| Gigabyte      | Z97X-Gaming 5               | [b99d5ec5ca](https://linux-hardware.org/?probe=b99d5ec5ca) | Feb 04, 2021 |
| Gateway       | DX4885                      | [48628b0b95](https://linux-hardware.org/?probe=48628b0b95) | Feb 03, 2021 |
| Gigabyte      | H61M-D2H-USB3               | [e39393dcdb](https://linux-hardware.org/?probe=e39393dcdb) | Feb 02, 2021 |
| Intel         | H61M-S1                     | [38a03ee5be](https://linux-hardware.org/?probe=38a03ee5be) | Jan 31, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [bbab610ec1](https://linux-hardware.org/?probe=bbab610ec1) | Jan 31, 2021 |
| ASUSTek       | H97M-PLUS                   | [5d87cbd136](https://linux-hardware.org/?probe=5d87cbd136) | Jan 28, 2021 |
| Foxconn       | CALI                        | [6ced30e397](https://linux-hardware.org/?probe=6ced30e397) | Jan 27, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [20d082d72c](https://linux-hardware.org/?probe=20d082d72c) | Jan 26, 2021 |
| ASUSTek       | LITHIUM                     | [e2c8ad85fb](https://linux-hardware.org/?probe=e2c8ad85fb) | Jan 24, 2021 |
| ASUSTek       | LITHIUM                     | [3f3f25d596](https://linux-hardware.org/?probe=3f3f25d596) | Jan 24, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [4695d8c639](https://linux-hardware.org/?probe=4695d8c639) | Jan 24, 2021 |
| ASUSTek       | P5N-D                       | [cac7f8ae52](https://linux-hardware.org/?probe=cac7f8ae52) | Jan 23, 2021 |
| ASUSTek       | P5N-D                       | [b637c75d21](https://linux-hardware.org/?probe=b637c75d21) | Jan 23, 2021 |
| Intel         | DG41RQ AAE54511-203         | [fc928f4e01](https://linux-hardware.org/?probe=fc928f4e01) | Jan 20, 2021 |
| IBM           | 813311S                     | [c65634928d](https://linux-hardware.org/?probe=c65634928d) | Jan 20, 2021 |
| IBM           | 813311S                     | [9dc5e1fd39](https://linux-hardware.org/?probe=9dc5e1fd39) | Jan 19, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Dell          | 0200DY A03                  | [5e5ca98e54](https://linux-hardware.org/?probe=5e5ca98e54) | Jan 13, 2021 |
| ASUSTek       | P8Z68-V PRO                 | [86c7eb6c5b](https://linux-hardware.org/?probe=86c7eb6c5b) | Jan 11, 2021 |
| ASUSTek       | PRIME B250-PRO              | [474542bd76](https://linux-hardware.org/?probe=474542bd76) | Jan 10, 2021 |
| ASUSTek       | P7P55 LX                    | [d13d4667c3](https://linux-hardware.org/?probe=d13d4667c3) | Jan 09, 2021 |
| ASRock        | B75 Pro3-M                  | [e514f058fe](https://linux-hardware.org/?probe=e514f058fe) | Jan 08, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [fb8fa788e3](https://linux-hardware.org/?probe=fb8fa788e3) | Jan 07, 2021 |
| Dell          | Board                       | [28f7852e30](https://linux-hardware.org/?probe=28f7852e30) | Jan 06, 2021 |
| Dell          | Board                       | [2441565de2](https://linux-hardware.org/?probe=2441565de2) | Jan 04, 2021 |
| MSI           | H87-G43                     | [8b1363882c](https://linux-hardware.org/?probe=8b1363882c) | Jan 03, 2021 |
| ASUSTek       | M5A99X EVO                  | [236270122d](https://linux-hardware.org/?probe=236270122d) | Jan 03, 2021 |
| ASUSTek       | NARRA2                      | [8668a91426](https://linux-hardware.org/?probe=8668a91426) | Jan 01, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [581e2dc97d](https://linux-hardware.org/?probe=581e2dc97d) | Jan 01, 2021 |
| ASUSTek       | Z170-A                      | [3c77355a19](https://linux-hardware.org/?probe=3c77355a19) | Dec 31, 2020 |
| HP            | 158A                        | [6709abbada](https://linux-hardware.org/?probe=6709abbada) | Dec 29, 2020 |
| Gigabyte      | Z97-HD3                     | [417a2cbe50](https://linux-hardware.org/?probe=417a2cbe50) | Dec 26, 2020 |
| MSI           | 2AE0                        | [57d0f5bc7e](https://linux-hardware.org/?probe=57d0f5bc7e) | Dec 25, 2020 |
| MSI           | 2A9C                        | [63d54bffba](https://linux-hardware.org/?probe=63d54bffba) | Dec 20, 2020 |
| MSI           | 2A9C                        | [e1816a5176](https://linux-hardware.org/?probe=e1816a5176) | Dec 20, 2020 |
| Dell          | Board                       | [db31d45e0e](https://linux-hardware.org/?probe=db31d45e0e) | Dec 18, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [46e2c41ee6](https://linux-hardware.org/?probe=46e2c41ee6) | Dec 17, 2020 |
| Intel         | DG31PR AAD97573-206         | [b58cd271b0](https://linux-hardware.org/?probe=b58cd271b0) | Dec 16, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [9ad04d0568](https://linux-hardware.org/?probe=9ad04d0568) | Dec 16, 2020 |
| ASUSTek       | M5A78L LE                   | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [e9fb6116b3](https://linux-hardware.org/?probe=e9fb6116b3) | Dec 14, 2020 |
| ASUSTek       | M5A78L LE                   | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| HP            | 82A2                        | [8b443d9da5](https://linux-hardware.org/?probe=8b443d9da5) | Dec 12, 2020 |
| HP            | 82A2                        | [58faddeba3](https://linux-hardware.org/?probe=58faddeba3) | Dec 12, 2020 |
| Gigabyte      | 945GCM-S2C                  | [e1d03e259e](https://linux-hardware.org/?probe=e1d03e259e) | Dec 09, 2020 |
| Dell          | 0F1262                      | [90378abac3](https://linux-hardware.org/?probe=90378abac3) | Dec 08, 2020 |
| Dell          | 0F1262                      | [63e64577e4](https://linux-hardware.org/?probe=63e64577e4) | Dec 08, 2020 |
| Gigabyte      | EP45T-EXTREME               | [9320edd724](https://linux-hardware.org/?probe=9320edd724) | Dec 07, 2020 |
| Gigabyte      | 945GCM-S2C                  | [eba95d11b5](https://linux-hardware.org/?probe=eba95d11b5) | Dec 04, 2020 |
| Foxconn       | 2A8C                        | [f0c3c358a0](https://linux-hardware.org/?probe=f0c3c358a0) | Dec 03, 2020 |
| Dell          | 0GM819                      | [2555a4411a](https://linux-hardware.org/?probe=2555a4411a) | Nov 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [283f77cd86](https://linux-hardware.org/?probe=283f77cd86) | Nov 25, 2020 |
| Gigabyte      | B450M S2H                   | [2fca776404](https://linux-hardware.org/?probe=2fca776404) | Nov 24, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [94f75b4e92](https://linux-hardware.org/?probe=94f75b4e92) | Nov 22, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [49224bd7f8](https://linux-hardware.org/?probe=49224bd7f8) | Nov 21, 2020 |
| EAGLE EYE ... | BayTrail-D Rev.00           | [4976c9dd08](https://linux-hardware.org/?probe=4976c9dd08) | Nov 21, 2020 |
| ASUSTek       | WS C246M PRO Series         | [502bd89093](https://linux-hardware.org/?probe=502bd89093) | Nov 18, 2020 |
| Supermicro    | H8DM8-2                     | [51d5cdb6e0](https://linux-hardware.org/?probe=51d5cdb6e0) | Nov 18, 2020 |
| TYAN Compu... | S8230                       | [c761d2a512](https://linux-hardware.org/?probe=c761d2a512) | Nov 18, 2020 |
| Supermicro    | H8DI3+                      | [cdbfbfdd91](https://linux-hardware.org/?probe=cdbfbfdd91) | Nov 18, 2020 |
| Supermicro    | H8DI3+                      | [c163123358](https://linux-hardware.org/?probe=c163123358) | Nov 17, 2020 |
| ASUSTek       | WS C246M PRO Series         | [dc20d9cf64](https://linux-hardware.org/?probe=dc20d9cf64) | Nov 17, 2020 |
| ASUSTek       | Benicia                     | [a7eba86b12](https://linux-hardware.org/?probe=a7eba86b12) | Nov 17, 2020 |
| Medion        | B360H4-EM V1.0              | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| Dell          | 0WG864                      | [1c2384097b](https://linux-hardware.org/?probe=1c2384097b) | Nov 15, 2020 |
| ASUSTek       | Benicia                     | [38670b2463](https://linux-hardware.org/?probe=38670b2463) | Nov 11, 2020 |
| HP            | 1790                        | [02138cec8b](https://linux-hardware.org/?probe=02138cec8b) | Nov 08, 2020 |
| HP            | 1905                        | [6f20f6aa7d](https://linux-hardware.org/?probe=6f20f6aa7d) | Nov 08, 2020 |
| Intel         | SLIMBOOK                    | [2250e4a10f](https://linux-hardware.org/?probe=2250e4a10f) | Nov 07, 2020 |
| HP            | 3397                        | [17188b10a3](https://linux-hardware.org/?probe=17188b10a3) | Nov 06, 2020 |
| Lenovo        | Board                       | [e57019aa03](https://linux-hardware.org/?probe=e57019aa03) | Nov 06, 2020 |
| ASUSTek       | Z170M-PLUS                  | [436e8c5ead](https://linux-hardware.org/?probe=436e8c5ead) | Nov 05, 2020 |
| ASUSTek       | Z170M-PLUS                  | [4a14036d89](https://linux-hardware.org/?probe=4a14036d89) | Nov 05, 2020 |
| Unknown       | Unknown                     | [49351fb74d](https://linux-hardware.org/?probe=49351fb74d) | Nov 03, 2020 |
| ASUSTek       | PRIME X570-P                | [7cc067fb03](https://linux-hardware.org/?probe=7cc067fb03) | Nov 03, 2020 |
| ASUSTek       | PRIME X570-P                | [2a45f74eda](https://linux-hardware.org/?probe=2a45f74eda) | Nov 02, 2020 |
| Pegatron      | NARRA3                      | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| Lenovo        | Board                       | [69bc4fbb1b](https://linux-hardware.org/?probe=69bc4fbb1b) | Oct 30, 2020 |
| HP            | 1493                        | [34134cab7f](https://linux-hardware.org/?probe=34134cab7f) | Oct 30, 2020 |
| HP            | 1493                        | [dd1964d532](https://linux-hardware.org/?probe=dd1964d532) | Oct 30, 2020 |
| HP            | 1497                        | [1d068e5c77](https://linux-hardware.org/?probe=1d068e5c77) | Oct 28, 2020 |
| HP            | 3047h                       | [4f58775069](https://linux-hardware.org/?probe=4f58775069) | Oct 28, 2020 |
| ASUSTek       | P5K                         | [db5fa55daa](https://linux-hardware.org/?probe=db5fa55daa) | Oct 27, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [a13afb5c54](https://linux-hardware.org/?probe=a13afb5c54) | Oct 27, 2020 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [dd929b231e](https://linux-hardware.org/?probe=dd929b231e) | Oct 26, 2020 |
| ASRock        | G31M-GS                     | [0a9aa8dcd2](https://linux-hardware.org/?probe=0a9aa8dcd2) | Oct 26, 2020 |
| Gigabyte      | F2A78M-HD2                  | [3919d06624](https://linux-hardware.org/?probe=3919d06624) | Oct 25, 2020 |
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
| ASUSTek       | P5V800-MX                   | [a88e3e04a8](https://linux-hardware.org/?probe=a88e3e04a8) | Oct 17, 2020 |
| Dell          | 08NPPY A00                  | [1e62d6029b](https://linux-hardware.org/?probe=1e62d6029b) | Oct 17, 2020 |
| ASUSTek       | P5V800-MX                   | [1820121750](https://linux-hardware.org/?probe=1820121750) | Oct 17, 2020 |
| HP            | 3397                        | [5a6fac5a0f](https://linux-hardware.org/?probe=5a6fac5a0f) | Oct 16, 2020 |
| MSI           | B550M PRO-VDH WIFI          | [2c4fc7773a](https://linux-hardware.org/?probe=2c4fc7773a) | Oct 14, 2020 |
| Dell          | 042P49 A01                  | [44c14427a0](https://linux-hardware.org/?probe=44c14427a0) | Oct 13, 2020 |
| MSI           | A320M-A PRO                 | [88c1fe1b25](https://linux-hardware.org/?probe=88c1fe1b25) | Oct 13, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [097db248db](https://linux-hardware.org/?probe=097db248db) | Oct 12, 2020 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | [8de90e5004](https://linux-hardware.org/?probe=8de90e5004) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [41141f049e](https://linux-hardware.org/?probe=41141f049e) | Oct 11, 2020 |
| Gigabyte      | A320M-H-CF                  | [2c0322f113](https://linux-hardware.org/?probe=2c0322f113) | Oct 10, 2020 |
| Dell          | 0FR6WH A01                  | [2776ae6a1a](https://linux-hardware.org/?probe=2776ae6a1a) | Oct 09, 2020 |
| Dell          | 0T656F A01                  | [f44db9c73a](https://linux-hardware.org/?probe=f44db9c73a) | Oct 09, 2020 |
| Pegatron      | 2A84h                       | [a8d97c37b7](https://linux-hardware.org/?probe=a8d97c37b7) | Oct 08, 2020 |
| Dell          | 0HN7XN A00                  | [885b19f22a](https://linux-hardware.org/?probe=885b19f22a) | Oct 08, 2020 |
| HP            | 3646h                       | [d5dd5824e3](https://linux-hardware.org/?probe=d5dd5824e3) | Oct 07, 2020 |
| Intel         | DH77DF AAG40293-300         | [3757081542](https://linux-hardware.org/?probe=3757081542) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | [1f6fe3684d](https://linux-hardware.org/?probe=1f6fe3684d) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | [8872b79e71](https://linux-hardware.org/?probe=8872b79e71) | Oct 07, 2020 |
| Dell          | 0TVR1F A01                  | [3de8c4e65d](https://linux-hardware.org/?probe=3de8c4e65d) | Oct 06, 2020 |
| Dell          | 0TVR1F A01                  | [ae1a5155a6](https://linux-hardware.org/?probe=ae1a5155a6) | Oct 05, 2020 |
| Gigabyte      | B460M DS3H                  | [c607051cd6](https://linux-hardware.org/?probe=c607051cd6) | Oct 04, 2020 |
| Gigabyte      | B460M DS3H                  | [a96b9c0e32](https://linux-hardware.org/?probe=a96b9c0e32) | Oct 04, 2020 |
| Acer          | Predator G5910              | [1366ed3c65](https://linux-hardware.org/?probe=1366ed3c65) | Oct 03, 2020 |
| ASRock        | 970 Pro3 R2.0               | [98400991aa](https://linux-hardware.org/?probe=98400991aa) | Oct 02, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [16d07f52d6](https://linux-hardware.org/?probe=16d07f52d6) | Sep 29, 2020 |
| HP            | 3047h                       | [8276b976a7](https://linux-hardware.org/?probe=8276b976a7) | Sep 28, 2020 |
| TEKNOSERVI... | TTL-TEKNOSLIM               | [e2bab86cc6](https://linux-hardware.org/?probe=e2bab86cc6) | Sep 28, 2020 |
| HP            | 1497                        | [3c6ed08ddd](https://linux-hardware.org/?probe=3c6ed08ddd) | Sep 25, 2020 |
| Gigabyte      | H81M-H                      | [21991336a9](https://linux-hardware.org/?probe=21991336a9) | Sep 25, 2020 |
| Dell          | 09M8Y8 A01                  | [7086c0ba36](https://linux-hardware.org/?probe=7086c0ba36) | Sep 25, 2020 |
| Intel         | DQ965GF AAD41676-601        | [67488208ca](https://linux-hardware.org/?probe=67488208ca) | Sep 23, 2020 |
| Intel         | DQ965GF AAD41676-601        | [d76b69027e](https://linux-hardware.org/?probe=d76b69027e) | Sep 23, 2020 |
| Intel         | DG43GT AAE62768-301         | [028847b86e](https://linux-hardware.org/?probe=028847b86e) | Sep 21, 2020 |
| Dell          | 0WX729                      | [f2cc61a6f1](https://linux-hardware.org/?probe=f2cc61a6f1) | Sep 17, 2020 |
| Dell          | 0WX729                      | [4fdbabe245](https://linux-hardware.org/?probe=4fdbabe245) | Sep 17, 2020 |
| Intel         | B75                         | [0bbd4974f9](https://linux-hardware.org/?probe=0bbd4974f9) | Sep 17, 2020 |
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
| ASUSTek       | P5K                         | [d65fdfd514](https://linux-hardware.org/?probe=d65fdfd514) | Sep 07, 2020 |
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
| ASUSTek       | P5K                         | [f61b9d7c51](https://linux-hardware.org/?probe=f61b9d7c51) | Aug 20, 2020 |
| Intel         | Board                       | [0792f8e763](https://linux-hardware.org/?probe=0792f8e763) | Aug 20, 2020 |
| HP            | 0A64h                       | [09736ec014](https://linux-hardware.org/?probe=09736ec014) | Aug 20, 2020 |
| ASRock        | 990FX Extreme4              | [9d89158c0c](https://linux-hardware.org/?probe=9d89158c0c) | Aug 19, 2020 |
| ASUSTek       | PRIME Z270-P                | [f3ea863c21](https://linux-hardware.org/?probe=f3ea863c21) | Aug 19, 2020 |
| Toshiba       | STI 010432                  | [844d21cfba](https://linux-hardware.org/?probe=844d21cfba) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | [d568758fb5](https://linux-hardware.org/?probe=d568758fb5) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | [93e07b3103](https://linux-hardware.org/?probe=93e07b3103) | Aug 16, 2020 |
| ASRock        | B450M Pro4                  | [27573f027c](https://linux-hardware.org/?probe=27573f027c) | Aug 12, 2020 |
| Intel         | Board                       | [501444c3d4](https://linux-hardware.org/?probe=501444c3d4) | Aug 12, 2020 |
| Intel         | Board                       | [aca06096b6](https://linux-hardware.org/?probe=aca06096b6) | Aug 12, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1c6f36de59](https://linux-hardware.org/?probe=1c6f36de59) | Aug 10, 2020 |
| ASUSTek       | M4N68T-M LE                 | [0142ff156e](https://linux-hardware.org/?probe=0142ff156e) | Aug 07, 2020 |
| Gigabyte      | H97N-WIFI                   | [608ff52425](https://linux-hardware.org/?probe=608ff52425) | Aug 06, 2020 |
| Gigabyte      | Z77P-D3                     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| ASUSTek       | P9X79 DELUXE                | [bd1790913e](https://linux-hardware.org/?probe=bd1790913e) | Aug 03, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [716ca191bf](https://linux-hardware.org/?probe=716ca191bf) | Jul 29, 2020 |
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
| Unknown       | Unknown                     | [d8653c0683](https://linux-hardware.org/?probe=d8653c0683) | Jul 19, 2020 |
| Unknown       | Unknown                     | [8244df34e4](https://linux-hardware.org/?probe=8244df34e4) | Jul 19, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c3a79140eb](https://linux-hardware.org/?probe=c3a79140eb) | Jul 18, 2020 |
| HP            | 1905                        | [213860b4ef](https://linux-hardware.org/?probe=213860b4ef) | Jul 17, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [68e6b713ca](https://linux-hardware.org/?probe=68e6b713ca) | Jul 14, 2020 |
| ASUSTek       | P5QPL-AM                    | [bd28d2c132](https://linux-hardware.org/?probe=bd28d2c132) | Jul 13, 2020 |
| HP            | 8434 11                     | [377d6d5aa4](https://linux-hardware.org/?probe=377d6d5aa4) | Jul 10, 2020 |
| Lenovo        | Board                       | [30edd53934](https://linux-hardware.org/?probe=30edd53934) | Jul 09, 2020 |
| HP            | 1905                        | [c53b0206e5](https://linux-hardware.org/?probe=c53b0206e5) | Jul 08, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [994e71e658](https://linux-hardware.org/?probe=994e71e658) | Jul 03, 2020 |
| MSI           | A78M-E35                    | [baf6228acf](https://linux-hardware.org/?probe=baf6228acf) | Jul 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | [f7afeb0f26](https://linux-hardware.org/?probe=f7afeb0f26) | Jul 01, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c1d0ef500e](https://linux-hardware.org/?probe=c1d0ef500e) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6a9b477b88](https://linux-hardware.org/?probe=6a9b477b88) | Jun 29, 2020 |
| HP            | 09E8h                       | [d9b1f1bf60](https://linux-hardware.org/?probe=d9b1f1bf60) | Jun 28, 2020 |
| HP            | 09E8h                       | [14e6514858](https://linux-hardware.org/?probe=14e6514858) | Jun 20, 2020 |
| HP            | ProLiant MicroServer        | [1f2d306b05](https://linux-hardware.org/?probe=1f2d306b05) | Jun 20, 2020 |
| ASRock        | B85M Pro4                   | [d427080ed1](https://linux-hardware.org/?probe=d427080ed1) | Jun 17, 2020 |
| IBM           | Board                       | [28e9762210](https://linux-hardware.org/?probe=28e9762210) | Jun 16, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [02f2a001e1](https://linux-hardware.org/?probe=02f2a001e1) | Jun 11, 2020 |
| ASUSTek       | P5QPL-AM                    | [994e3df746](https://linux-hardware.org/?probe=994e3df746) | Jun 11, 2020 |
| ASRock        | H110M-STX                   | [3c35aef096](https://linux-hardware.org/?probe=3c35aef096) | Jun 10, 2020 |
| Dell          | 0478VN A00                  | [f02bda5144](https://linux-hardware.org/?probe=f02bda5144) | Jun 09, 2020 |
| Gigabyte      | B450M DS3H-CF               | [8dbad33afb](https://linux-hardware.org/?probe=8dbad33afb) | Jun 05, 2020 |
| ASRock        | A320M-HDV R4.0              | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASUSTek       | P5QPL-AM                    | [140b5cec40](https://linux-hardware.org/?probe=140b5cec40) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | [9c5c59ed91](https://linux-hardware.org/?probe=9c5c59ed91) | May 30, 2020 |
| MSI           | B450 TOMAHAWK               | [a1efaa98b1](https://linux-hardware.org/?probe=a1efaa98b1) | May 29, 2020 |
| MSI           | B450 TOMAHAWK               | [34dd0b6941](https://linux-hardware.org/?probe=34dd0b6941) | May 29, 2020 |
| Gigabyte      | F2A78M-HD2                  | [6bdc484d30](https://linux-hardware.org/?probe=6bdc484d30) | May 25, 2020 |
| HP            | 1905                        | [2cfc73cc46](https://linux-hardware.org/?probe=2cfc73cc46) | May 20, 2020 |
| IBM           | Board                       | [784c83d7d6](https://linux-hardware.org/?probe=784c83d7d6) | May 19, 2020 |
| ASUSTek       | PRIME B450M-K               | [8fd77159e9](https://linux-hardware.org/?probe=8fd77159e9) | May 19, 2020 |
| Dell          | 0WF810                      | [24f1a1287d](https://linux-hardware.org/?probe=24f1a1287d) | May 17, 2020 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [c568b3270d](https://linux-hardware.org/?probe=c568b3270d) | May 17, 2020 |
| Dell          | 0WF810                      | [6ae0e21069](https://linux-hardware.org/?probe=6ae0e21069) | May 17, 2020 |
| Dell          | 0WF810                      | [e6f27fd467](https://linux-hardware.org/?probe=e6f27fd467) | May 17, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4806bd297f](https://linux-hardware.org/?probe=4806bd297f) | May 16, 2020 |
| eMachines     | EMCP61M                     | [df9fb640bc](https://linux-hardware.org/?probe=df9fb640bc) | May 16, 2020 |
| ASRock        | A320M-HDV R4.0              | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [f69adb8baa](https://linux-hardware.org/?probe=f69adb8baa) | May 12, 2020 |
| Lenovo        | SDK0E50510 WIN 262507961... | [0400e155ee](https://linux-hardware.org/?probe=0400e155ee) | May 10, 2020 |
| Fujitsu Si... | MS-7293VP                   | [a812ea5b0e](https://linux-hardware.org/?probe=a812ea5b0e) | May 10, 2020 |
| Gigabyte      | GA-970A-UD3                 | [567162aae3](https://linux-hardware.org/?probe=567162aae3) | May 09, 2020 |
| ASUSTek       | PRIME B360M-A               | [a60475afb0](https://linux-hardware.org/?probe=a60475afb0) | May 07, 2020 |
| Gigabyte      | G41M-ES2L                   | [6d0c0ba23f](https://linux-hardware.org/?probe=6d0c0ba23f) | May 06, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9a72c58dee](https://linux-hardware.org/?probe=9a72c58dee) | May 04, 2020 |
| Gigabyte      | GA-A75-D3H                  | [88dd0cfbcb](https://linux-hardware.org/?probe=88dd0cfbcb) | May 02, 2020 |
| Gigabyte      | GA-A75-D3H                  | [530009d42a](https://linux-hardware.org/?probe=530009d42a) | May 02, 2020 |
| ASUSTek       | PRIME B360M-A               | [8266071d4d](https://linux-hardware.org/?probe=8266071d4d) | May 01, 2020 |
| ASUSTek       | PRIME B360M-A               | [125f63ea26](https://linux-hardware.org/?probe=125f63ea26) | May 01, 2020 |
| Biostar       | TA770E3                     | [18e745a21f](https://linux-hardware.org/?probe=18e745a21f) | Apr 28, 2020 |
| Fujitsu       | D3348-B1 S26361-D3348-B1    | [d92e25593d](https://linux-hardware.org/?probe=d92e25593d) | Apr 28, 2020 |
| Intel         | D946GZIS AAD45436-306       | [483b574b1a](https://linux-hardware.org/?probe=483b574b1a) | Apr 25, 2020 |
| MSI           | H81I                        | [1a376610c9](https://linux-hardware.org/?probe=1a376610c9) | Apr 23, 2020 |
| Dell          | 06D7TR A00                  | [aa971cfd4b](https://linux-hardware.org/?probe=aa971cfd4b) | Apr 22, 2020 |
| Dell          | 06D7TR A00                  | [f983529eec](https://linux-hardware.org/?probe=f983529eec) | Apr 22, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [ba2c3155d7](https://linux-hardware.org/?probe=ba2c3155d7) | Apr 22, 2020 |
| ASUSTek       | M5A78L LE                   | [1562c544a6](https://linux-hardware.org/?probe=1562c544a6) | Apr 14, 2020 |
| MSI           | AMETHYST-M                  | [d42d07bebb](https://linux-hardware.org/?probe=d42d07bebb) | Apr 13, 2020 |
| HP            | 18E7                        | [706a61d51a](https://linux-hardware.org/?probe=706a61d51a) | Apr 13, 2020 |
| MSI           | AMETHYST-M                  | [7c3997226d](https://linux-hardware.org/?probe=7c3997226d) | Apr 12, 2020 |
| Acer          | FRS690L                     | [36566fc3d6](https://linux-hardware.org/?probe=36566fc3d6) | Apr 11, 2020 |
| Dell          | 0RF945                      | [33dfbd4c46](https://linux-hardware.org/?probe=33dfbd4c46) | Apr 10, 2020 |
| Medion        | MS-7621                     | [52ea662142](https://linux-hardware.org/?probe=52ea662142) | Apr 10, 2020 |
| Unknown       | SKYBAY                      | [377dc747eb](https://linux-hardware.org/?probe=377dc747eb) | Apr 10, 2020 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [f3e1f82f8a](https://linux-hardware.org/?probe=f3e1f82f8a) | Apr 10, 2020 |
| Packard Be... | imedia S1300                | [4176927e40](https://linux-hardware.org/?probe=4176927e40) | Apr 08, 2020 |
| Dell          | 0RF945                      | [a6656c777c](https://linux-hardware.org/?probe=a6656c777c) | Apr 05, 2020 |
| ASRock        | N68C-S UCC                  | [d9fcbbba59](https://linux-hardware.org/?probe=d9fcbbba59) | Apr 05, 2020 |
| ASRock        | N68C-S UCC                  | [eca43c4678](https://linux-hardware.org/?probe=eca43c4678) | Apr 05, 2020 |
| ASRock        | N68C-S UCC                  | [6f107accce](https://linux-hardware.org/?probe=6f107accce) | Apr 05, 2020 |
| ASRock        | N68C-S UCC                  | [a570845e0e](https://linux-hardware.org/?probe=a570845e0e) | Apr 05, 2020 |
| ASRock        | N68C-S UCC                  | [6d06e1fb7d](https://linux-hardware.org/?probe=6d06e1fb7d) | Apr 05, 2020 |
| Unknown       | Unknown                     | [1dbf41b4db](https://linux-hardware.org/?probe=1dbf41b4db) | Apr 04, 2020 |
| ASUSTek       | K30BF_M32BF                 | [8bf252d3c7](https://linux-hardware.org/?probe=8bf252d3c7) | Mar 26, 2020 |
| Acer          | Aspire MC605 v1.0           | [1b4feb99d6](https://linux-hardware.org/?probe=1b4feb99d6) | Mar 24, 2020 |
| ASUSTek       | H81M-A                      | [4007d120f4](https://linux-hardware.org/?probe=4007d120f4) | Mar 23, 2020 |
| HP            | 09E8h                       | [57904c47e1](https://linux-hardware.org/?probe=57904c47e1) | Mar 21, 2020 |
| HP            | 09E8h                       | [4c44586ba9](https://linux-hardware.org/?probe=4c44586ba9) | Mar 21, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [b4d14a98ef](https://linux-hardware.org/?probe=b4d14a98ef) | Mar 20, 2020 |
| Pegatron      | Benicia                     | [548ea6b794](https://linux-hardware.org/?probe=548ea6b794) | Mar 17, 2020 |
| Pegatron      | Benicia                     | [88b4ab2118](https://linux-hardware.org/?probe=88b4ab2118) | Mar 17, 2020 |
| ASUSTek       | M5A97 R2.0                  | [4cf01c5deb](https://linux-hardware.org/?probe=4cf01c5deb) | Mar 17, 2020 |
| MSI           | X370 GAMING PLUS            | [745dce9c6b](https://linux-hardware.org/?probe=745dce9c6b) | Mar 16, 2020 |
| Dell          | 0XPDFK A01                  | [9434f7214c](https://linux-hardware.org/?probe=9434f7214c) | Mar 16, 2020 |
| MSI           | X370 GAMING PLUS            | [e14efa2501](https://linux-hardware.org/?probe=e14efa2501) | Mar 10, 2020 |
| MSI           | X370 GAMING PLUS            | [78c1606697](https://linux-hardware.org/?probe=78c1606697) | Mar 09, 2020 |
| ASUSTek       | Z87-EXPERT                  | [bf50ba13d5](https://linux-hardware.org/?probe=bf50ba13d5) | Mar 09, 2020 |
| MSI           | Z97-G43                     | [15f3bc409b](https://linux-hardware.org/?probe=15f3bc409b) | Mar 03, 2020 |
| ASUSTek       | P9X79 WS                    | [513772febc](https://linux-hardware.org/?probe=513772febc) | Mar 01, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [9238d52f18](https://linux-hardware.org/?probe=9238d52f18) | Feb 29, 2020 |
| ASUSTek       | M5A97 R2.0                  | [bbd59f253f](https://linux-hardware.org/?probe=bbd59f253f) | Feb 28, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [df58761358](https://linux-hardware.org/?probe=df58761358) | Feb 26, 2020 |
| Gigabyte      | M68MT-S2                    | [dd8e2753eb](https://linux-hardware.org/?probe=dd8e2753eb) | Feb 22, 2020 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [107b2c10b1](https://linux-hardware.org/?probe=107b2c10b1) | Feb 21, 2020 |
| Intel         | DQ67SW AAG12527-306         | [67fddf0810](https://linux-hardware.org/?probe=67fddf0810) | Feb 19, 2020 |
| Intel         | CM8V5CB8N K53774-201        | [4ba8cd9ca2](https://linux-hardware.org/?probe=4ba8cd9ca2) | Feb 16, 2020 |
| Intel         | CM8V5CB8N K53774-201        | [19086b2ac2](https://linux-hardware.org/?probe=19086b2ac2) | Feb 16, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [2d0a423903](https://linux-hardware.org/?probe=2d0a423903) | Feb 11, 2020 |
| Dell          | 0FH884                      | [688c76e3c5](https://linux-hardware.org/?probe=688c76e3c5) | Feb 10, 2020 |
| Dell          | 0FH884                      | [04f5c96f13](https://linux-hardware.org/?probe=04f5c96f13) | Feb 10, 2020 |
| ASRock        | N68C-S UCC                  | [04206a5e8b](https://linux-hardware.org/?probe=04206a5e8b) | Feb 10, 2020 |
| ASRock        | N68C-S UCC                  | [40300eadfc](https://linux-hardware.org/?probe=40300eadfc) | Feb 10, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [644e6d88e4](https://linux-hardware.org/?probe=644e6d88e4) | Feb 09, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [b7799e0013](https://linux-hardware.org/?probe=b7799e0013) | Feb 07, 2020 |
| MSI           | Z97-G43                     | [fa6f308dc8](https://linux-hardware.org/?probe=fa6f308dc8) | Feb 06, 2020 |
| Lenovo        | ThinkServer TS140           | [33fc6022df](https://linux-hardware.org/?probe=33fc6022df) | Feb 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [a84be71f79](https://linux-hardware.org/?probe=a84be71f79) | Feb 05, 2020 |
| ECS           | A55F2-M3                    | [b9b38e5c20](https://linux-hardware.org/?probe=b9b38e5c20) | Feb 05, 2020 |
| ASUSTek       | P5QL PRO                    | [08fe8386b9](https://linux-hardware.org/?probe=08fe8386b9) | Feb 01, 2020 |
| ASUSTek       | P8Z68-V                     | [c75136db54](https://linux-hardware.org/?probe=c75136db54) | Jan 25, 2020 |
| HP            | 304Bh                       | [21e955c9a9](https://linux-hardware.org/?probe=21e955c9a9) | Jan 22, 2020 |
| HP            | 304Bh                       | [46e2695de3](https://linux-hardware.org/?probe=46e2695de3) | Jan 22, 2020 |
| HP            | 304Bh                       | [6ecb0e897f](https://linux-hardware.org/?probe=6ecb0e897f) | Jan 22, 2020 |
| Medion        | MS-7707                     | [3feacd8f08](https://linux-hardware.org/?probe=3feacd8f08) | Jan 19, 2020 |
| Medion        | MS-7707                     | [5d5096c9a8](https://linux-hardware.org/?probe=5d5096c9a8) | Jan 18, 2020 |
| MSI           | Z97-G43                     | [bcfef709a8](https://linux-hardware.org/?probe=bcfef709a8) | Jan 18, 2020 |
| Dell          | 06FW8P A02                  | [c537ea693f](https://linux-hardware.org/?probe=c537ea693f) | Dec 31, 2019 |
| ASRock        | G41C-GS                     | [401c11ccd1](https://linux-hardware.org/?probe=401c11ccd1) | Dec 24, 2019 |
| HP            | 3047h                       | [70e4f247fc](https://linux-hardware.org/?probe=70e4f247fc) | Dec 22, 2019 |
| Unknown       | SKYBAY                      | [c96c722a74](https://linux-hardware.org/?probe=c96c722a74) | Dec 22, 2019 |
| ASUSTek       | M2N-MX SE Plus              | [f3b22a675a](https://linux-hardware.org/?probe=f3b22a675a) | Dec 20, 2019 |
| Dell          | 0D6H9T A00                  | [2bc1b7d26e](https://linux-hardware.org/?probe=2bc1b7d26e) | Dec 19, 2019 |
| Gigabyte      | Z77P-D3                     | [3de82df337](https://linux-hardware.org/?probe=3de82df337) | Dec 17, 2019 |
| ASUSTek       | P8B75-M                     | [c3fe050e13](https://linux-hardware.org/?probe=c3fe050e13) | Dec 17, 2019 |
| ASUSTek       | LEUCITE3                    | [a95d4ac608](https://linux-hardware.org/?probe=a95d4ac608) | Dec 12, 2019 |
| ASUSTek       | LEUCITE3                    | [47e91009e5](https://linux-hardware.org/?probe=47e91009e5) | Dec 12, 2019 |
| ASUSTek       | LEUCITE3                    | [fe314e9b90](https://linux-hardware.org/?probe=fe314e9b90) | Dec 12, 2019 |
| ASUSTek       | LEUCITE3                    | [6eae565cae](https://linux-hardware.org/?probe=6eae565cae) | Dec 12, 2019 |
| ASUSTek       | LEUCITE3                    | [fdc2e78512](https://linux-hardware.org/?probe=fdc2e78512) | Dec 12, 2019 |
| MSI           | Z370 PC PRO                 | [b711749144](https://linux-hardware.org/?probe=b711749144) | Dec 07, 2019 |
| Gigabyte      | EG41MF-US2H                 | [ef2092e08e](https://linux-hardware.org/?probe=ef2092e08e) | Dec 06, 2019 |
| Dell          | 0RY206                      | [84263bb67f](https://linux-hardware.org/?probe=84263bb67f) | Dec 04, 2019 |
| HP            | 3047h                       | [41f1677a48](https://linux-hardware.org/?probe=41f1677a48) | Dec 03, 2019 |
| ASUSTek       | PRIME B250M-C               | [30009478a9](https://linux-hardware.org/?probe=30009478a9) | Dec 03, 2019 |
| Gigabyte      | H61MA-D3V                   | [e017e03ada](https://linux-hardware.org/?probe=e017e03ada) | Dec 02, 2019 |
| ASUSTek       | P5B-Deluxe                  | [c6c301411f](https://linux-hardware.org/?probe=c6c301411f) | Nov 14, 2019 |
| Gigabyte      | AB350M-Gaming 3-CF          | [c34d42ef7d](https://linux-hardware.org/?probe=c34d42ef7d) | Apr 26, 2019 |
| ASUSTek       | B75M-A                      | [8716e14da6](https://linux-hardware.org/?probe=8716e14da6) | Apr 26, 2019 |
| ASUSTek       | B75M-A                      | [2d5421e731](https://linux-hardware.org/?probe=2d5421e731) | Apr 26, 2019 |
| ASUSTek       | B75M-A                      | [1315e96719](https://linux-hardware.org/?probe=1315e96719) | Apr 26, 2019 |
| ASUSTek       | B75M-A                      | [e119ccfc52](https://linux-hardware.org/?probe=e119ccfc52) | Apr 26, 2019 |
| ASUSTek       | B75M-A                      | [52b1ac6f0d](https://linux-hardware.org/?probe=52b1ac6f0d) | Apr 26, 2019 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4dc79e706c](https://linux-hardware.org/?probe=4dc79e706c) | Mar 01, 2019 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3f3fa0acda](https://linux-hardware.org/?probe=3f3fa0acda) | Mar 01, 2019 |
| Gigabyte      | AB350M-Gaming 3-CF          | [2c0ab2c3d4](https://linux-hardware.org/?probe=2c0ab2c3d4) | Feb 28, 2019 |
| Gigabyte      | AB350M-Gaming 3-CF          | [423419be03](https://linux-hardware.org/?probe=423419be03) | Feb 28, 2019 |
| Gigabyte      | AB350M-Gaming 3-CF          | [566f39f59b](https://linux-hardware.org/?probe=566f39f59b) | Feb 22, 2019 |
| Gigabyte      | AB350M-Gaming 3-CF          | [14febb13aa](https://linux-hardware.org/?probe=14febb13aa) | Feb 20, 2019 |
| Gigabyte      | EX58-UD5                    | [004b195269](https://linux-hardware.org/?probe=004b195269) | Dec 05, 2018 |
| ASUSTek       | P5QL PRO                    | [4efe3892fd](https://linux-hardware.org/?probe=4efe3892fd) | Nov 28, 2018 |
| ASUSTek       | H110M-K                     | [411849da99](https://linux-hardware.org/?probe=411849da99) | Nov 07, 2018 |
| Gigabyte      | B75-D3V                     | [6fd3268a04](https://linux-hardware.org/?probe=6fd3268a04) | Oct 21, 2018 |
| Gigabyte      | B75-D3V                     | [67dd897a65](https://linux-hardware.org/?probe=67dd897a65) | Oct 21, 2018 |
| ASUSTek       | B150M-A/M.2                 | [b3176380ec](https://linux-hardware.org/?probe=b3176380ec) | Oct 01, 2018 |
| HP            | 2AF8                        | [cf7972f23a](https://linux-hardware.org/?probe=cf7972f23a) | Sep 29, 2018 |
| Medion        | H110H4-EM                   | [d10fed4b9f](https://linux-hardware.org/?probe=d10fed4b9f) | Jun 23, 2018 |
| Gigabyte      | GA-MA770-UD3                | [27fe9dbbfb](https://linux-hardware.org/?probe=27fe9dbbfb) | Sep 09, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu MATE 20.04 | 228      | 54.42%  |
| Ubuntu MATE 18.04 | 106      | 25.3%   |
| Ubuntu MATE 21.04 | 18       | 4.3%    |
| Ubuntu MATE 20.10 | 17       | 4.06%   |
| Ubuntu MATE 19.10 | 17       | 4.06%   |
| Ubuntu MATE 21.10 | 16       | 3.82%   |
| Ubuntu MATE 16.04 | 7        | 1.67%   |
| Ubuntu MATE 22.04 | 4        | 0.95%   |
| Ubuntu MATE 18.10 | 2        | 0.48%   |
| Ubuntu MATE 19.04 | 1        | 0.24%   |
| Ubuntu MATE 17.04 | 1        | 0.24%   |
| Ubuntu MATE 15.04 | 1        | 0.24%   |
| Ubuntu MATE       | 1        | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Ubuntu MATE | 405      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.4.0-48-generic   | 29       | 6.22%   |
| 5.4.0-52-generic   | 16       | 3.43%   |
| 5.4.0-42-generic   | 16       | 3.43%   |
| 4.15.0-163-generic | 15       | 3.22%   |
| 5.4.0-47-generic   | 14       | 3%      |
| 5.4.0-94-generic   | 12       | 2.58%   |
| 5.4.0-65-generic   | 11       | 2.36%   |
| 5.4.0-45-generic   | 10       | 2.15%   |
| 5.3.0-46-generic   | 9        | 1.93%   |
| 5.4.0-66-generic   | 8        | 1.72%   |
| 5.4.0-40-generic   | 8        | 1.72%   |
| 5.4.0-67-generic   | 7        | 1.5%    |
| 5.4.0-80-generic   | 6        | 1.29%   |
| 5.3.0-40-generic   | 6        | 1.29%   |
| 5.11.0-40-generic  | 6        | 1.29%   |
| 5.8.0-48-generic   | 5        | 1.07%   |
| 5.4.0-58-generic   | 5        | 1.07%   |
| 5.4.0-56-generic   | 5        | 1.07%   |
| 5.4.0-29-generic   | 5        | 1.07%   |
| 5.8.0-55-generic   | 4        | 0.86%   |
| 5.4.0-89-generic   | 4        | 0.86%   |
| 5.4.0-81-generic   | 4        | 0.86%   |
| 5.4.0-74-generic   | 4        | 0.86%   |
| 5.4.0-70-generic   | 4        | 0.86%   |
| 5.4.0-62-generic   | 4        | 0.86%   |
| 5.4.0-33-generic   | 4        | 0.86%   |
| 5.4.0-107-generic  | 4        | 0.86%   |
| 5.13.0-30-generic  | 4        | 0.86%   |
| 5.11.0-25-generic  | 4        | 0.86%   |
| 4.15.0-88-generic  | 4        | 0.86%   |
| 4.15.0-76-generic  | 4        | 0.86%   |
| 5.8.0-59-generic   | 3        | 0.64%   |
| 5.8.0-50-generic   | 3        | 0.64%   |
| 5.4.0-90-generic   | 3        | 0.64%   |
| 5.4.0-88-generic   | 3        | 0.64%   |
| 5.4.0-77-generic   | 3        | 0.64%   |
| 5.4.0-72-generic   | 3        | 0.64%   |
| 5.4.0-59-generic   | 3        | 0.64%   |
| 5.4.0-51-generic   | 3        | 0.64%   |
| 5.4.0-26-generic   | 3        | 0.64%   |
| 5.3.0-51-generic   | 3        | 0.64%   |
| 5.3.0-45-generic   | 3        | 0.64%   |
| 5.3.0-42-generic   | 3        | 0.64%   |
| 5.3.0-29-generic   | 3        | 0.64%   |
| 5.3.0-26-generic   | 3        | 0.64%   |
| 5.3.0-24-generic   | 3        | 0.64%   |
| 5.13.0-35-generic  | 3        | 0.64%   |
| 5.13.0-28-generic  | 3        | 0.64%   |
| 5.13.0-27-generic  | 3        | 0.64%   |
| 5.13.0-25-generic  | 3        | 0.64%   |
| 5.11.0-34-generic  | 3        | 0.64%   |
| 5.11.0-18-generic  | 3        | 0.64%   |
| 5.11.0-16-generic  | 3        | 0.64%   |
| 4.15.0-96-generic  | 3        | 0.64%   |
| 4.15.0-91-generic  | 3        | 0.64%   |
| 4.15.0-72-generic  | 3        | 0.64%   |
| 4.15.0-70-generic  | 3        | 0.64%   |
| 5.8.0-53-generic   | 2        | 0.43%   |
| 5.8.0-43-generic   | 2        | 0.43%   |
| 5.8.0-41-generic   | 2        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 209      | 49.18%  |
| 4.15.0  | 59       | 13.88%  |
| 5.3.0   | 39       | 9.18%   |
| 5.11.0  | 37       | 8.71%   |
| 5.8.0   | 34       | 8%      |
| 5.13.0  | 23       | 5.41%   |
| 5.0.0   | 5        | 1.18%   |
| 5.15.0  | 3        | 0.71%   |
| 5.10.0  | 2        | 0.47%   |
| 4.18.0  | 2        | 0.47%   |
| 5.9.1   | 1        | 0.24%   |
| 5.7.6   | 1        | 0.24%   |
| 5.7.0   | 1        | 0.24%   |
| 5.5.5   | 1        | 0.24%   |
| 5.4.2   | 1        | 0.24%   |
| 5.16.0  | 1        | 0.24%   |
| 5.10.5  | 1        | 0.24%   |
| 5.10.4  | 1        | 0.24%   |
| 5.10.1  | 1        | 0.24%   |
| 4.4.0   | 1        | 0.24%   |
| 4.10.0  | 1        | 0.24%   |
| 3.19.0  | 1        | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 210      | 49.53%  |
| 4.15    | 59       | 13.92%  |
| 5.3     | 39       | 9.2%    |
| 5.11    | 37       | 8.73%   |
| 5.8     | 34       | 8.02%   |
| 5.13    | 23       | 5.42%   |
| 5.0     | 5        | 1.18%   |
| 5.10    | 4        | 0.94%   |
| 5.15    | 3        | 0.71%   |
| 5.7     | 2        | 0.47%   |
| 4.18    | 2        | 0.47%   |
| 5.9     | 1        | 0.24%   |
| 5.5     | 1        | 0.24%   |
| 5.16    | 1        | 0.24%   |
| 4.4     | 1        | 0.24%   |
| 4.10    | 1        | 0.24%   |
| 3.19    | 1        | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 381      | 94.07%  |
| i686   | 24       | 5.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 398      | 98.27%  |
| X-Cinnamon | 2        | 0.49%   |
| Trinity    | 2        | 0.49%   |
| GNOME      | 2        | 0.49%   |
| Cinnamon   | 1        | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 391      | 96.31%  |
| Tty     | 11       | 2.71%   |
| Wayland | 4        | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 163      | 38.44%  |
| TDM     | 139      | 32.78%  |
| LightDM | 101      | 23.82%  |
| GDM     | 14       | 3.3%    |
| GDM3    | 4        | 0.94%   |
| SLiM    | 2        | 0.47%   |
| SDDM    | 1        | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 110      | 26.89%  |
| pt_BR   | 63       | 15.4%   |
| fr_FR   | 30       | 7.33%   |
| el_GR   | 30       | 7.33%   |
| de_DE   | 27       | 6.6%    |
| en_GB   | 20       | 4.89%   |
| es_ES   | 14       | 3.42%   |
| en_CA   | 13       | 3.18%   |
| Unknown | 13       | 3.18%   |
| ru_RU   | 12       | 2.93%   |
| it_IT   | 12       | 2.93%   |
| es_AR   | 9        | 2.2%    |
| en_AU   | 7        | 1.71%   |
| nl_NL   | 6        | 1.47%   |
| pl_PL   | 5        | 1.22%   |
| hu_HU   | 5        | 1.22%   |
| es_PE   | 4        | 0.98%   |
| sv_SE   | 2        | 0.49%   |
| fi_FI   | 2        | 0.49%   |
| es_CL   | 2        | 0.49%   |
| de_CH   | 2        | 0.49%   |
| de_AT   | 2        | 0.49%   |
| cs_CZ   | 2        | 0.49%   |
| C       | 2        | 0.49%   |
| zh_TW   | 1        | 0.24%   |
| pt_PT   | 1        | 0.24%   |
| nl_BE   | 1        | 0.24%   |
| ja_JP   | 1        | 0.24%   |
| hr_HR   | 1        | 0.24%   |
| eu_ES   | 1        | 0.24%   |
| es_VE   | 1        | 0.24%   |
| es_MX   | 1        | 0.24%   |
| es_GT   | 1        | 0.24%   |
| en_ZA   | 1        | 0.24%   |
| en_SG   | 1        | 0.24%   |
| en_PH   | 1        | 0.24%   |
| en_IN   | 1        | 0.24%   |
| en_IL   | 1        | 0.24%   |
| da_DK   | 1        | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 283      | 68.86%  |
| EFI  | 128      | 31.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 365      | 90.12%  |
| Overlay | 25       | 6.17%   |
| Zfs     | 4        | 0.99%   |
| Xfs     | 3        | 0.74%   |
| Btrfs   | 3        | 0.74%   |
| Unknown | 2        | 0.49%   |
| ExX4    | 1        | 0.25%   |
| Ext2    | 1        | 0.25%   |
| Aufs    | 1        | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 199      | 48.07%  |
| GPT     | 115      | 27.78%  |
| MBR     | 100      | 24.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 339      | 83.09%  |
| Yes       | 69       | 16.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 261      | 63.5%   |
| Yes       | 150      | 36.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 102      | 25.19%  |
| Dell                | 57       | 14.07%  |
| Hewlett-Packard     | 53       | 13.09%  |
| Gigabyte Technology | 53       | 13.09%  |
| MSI                 | 35       | 8.64%   |
| ASRock              | 26       | 6.42%   |
| Intel               | 16       | 3.95%   |
| Lenovo              | 14       | 3.46%   |
| Medion              | 6        | 1.48%   |
| Unknown             | 6        | 1.48%   |
| Pegatron            | 5        | 1.23%   |
| Acer                | 4        | 0.99%   |
| Fujitsu Siemens     | 3        | 0.74%   |
| ECS                 | 3        | 0.74%   |
| Biostar             | 3        | 0.74%   |
| Supermicro          | 2        | 0.49%   |
| IBM                 | 2        | 0.49%   |
| Fujitsu             | 2        | 0.49%   |
| Foxconn             | 2        | 0.49%   |
| ZOTAC               | 1        | 0.25%   |
| TYAN Computer       | 1        | 0.25%   |
| TEKNOSERVICE        | 1        | 0.25%   |
| Semp Toshiba        | 1        | 0.25%   |
| Packard Bell        | 1        | 0.25%   |
| JINGSHA             | 1        | 0.25%   |
| H61M                | 1        | 0.25%   |
| Gateway             | 1        | 0.25%   |
| eMachines           | 1        | 0.25%   |
| EAGLE EYE NETWORKS  | 1        | 0.25%   |
| Albatron            | 1        | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 9        | 2.22%   |
| HP ProDesk 600 G1 SFF             | 8        | 1.98%   |
| HP Compaq Elite 8300 SFF          | 8        | 1.98%   |
| HP Compaq 6005 Pro SFF PC         | 8        | 1.98%   |
| Unknown                           | 6        | 1.48%   |
| Dell OptiPlex 3010                | 5        | 1.23%   |
| HP Compaq 6200 Pro SFF PC         | 4        | 0.99%   |
| Dell OptiPlex GX520               | 4        | 0.99%   |
| Dell OptiPlex 390                 | 4        | 0.99%   |
| Dell OptiPlex 360                 | 4        | 0.99%   |
| Dell OptiPlex GX620               | 3        | 0.74%   |
| Dell OptiPlex 755                 | 3        | 0.74%   |
| Dell OptiPlex 330                 | 3        | 0.74%   |
| ASUS M5A97 R2.0                   | 3        | 0.74%   |
| ASUS M5A78L-M/USB3                | 3        | 0.74%   |
| ASRock B450M Pro4                 | 3        | 0.74%   |
| MSI MS-7C94                       | 2        | 0.49%   |
| MSI MS-7B49                       | 2        | 0.49%   |
| MSI MS-7817                       | 2        | 0.49%   |
| MSI MS-7816                       | 2        | 0.49%   |
| MSI MS-7680                       | 2        | 0.49%   |
| Lenovo ThinkCentre E73 10AW008MMX | 2        | 0.49%   |
| HP ProLiant MicroServer           | 2        | 0.49%   |
| HP Compaq 8000 Elite SFF PC       | 2        | 0.49%   |
| HP Compaq 4000 Pro SFF PC         | 2        | 0.49%   |
| Gigabyte Z97-HD3                  | 2        | 0.49%   |
| Gigabyte B450M DS3H               | 2        | 0.49%   |
| Dell OptiPlex 980                 | 2        | 0.49%   |
| Dell OptiPlex 790                 | 2        | 0.49%   |
| Dell OptiPlex 780                 | 2        | 0.49%   |
| Dell OptiPlex 7020                | 2        | 0.49%   |
| Dell OptiPlex 380                 | 2        | 0.49%   |
| Dell OptiPlex 3050                | 2        | 0.49%   |
| ASUS ROG Maximus XIII HERO        | 2        | 0.49%   |
| ASUS PRIME X570-P                 | 2        | 0.49%   |
| ASUS P8H61-M LX3 R2.0             | 2        | 0.49%   |
| ASUS P8B75-M                      | 2        | 0.49%   |
| ASUS M5A78L-M PLUS/USB3           | 2        | 0.49%   |
| ASUS M2N68-AM Plus                | 2        | 0.49%   |
| ASUS H61M-K                       | 2        | 0.49%   |
| ASRock N68C-S UCC                 | 2        | 0.49%   |
| ZOTAC NM10                        | 1        | 0.25%   |
| TYAN S8230                        | 1        | 0.25%   |
| TEKNOSERVICE TTL-TEKNOSLIM        | 1        | 0.25%   |
| Supermicro H8DM8-2                | 1        | 0.25%   |
| Supermicro H8DI3+                 | 1        | 0.25%   |
| Semp Toshiba STI                  | 1        | 0.25%   |
| Pegatron VG271AA-ABF s5206fr      | 1        | 0.25%   |
| Pegatron KT373AA-ABA a6519fh      | 1        | 0.25%   |
| Pegatron KQ467AA-ABE m9265.es     | 1        | 0.25%   |
| Pegatron FR484AA-UUW m9464sc      | 1        | 0.25%   |
| Pegatron Compaq dx7500 SFF        | 1        | 0.25%   |
| Packard Bell imedia S1300         | 1        | 0.25%   |
| MSI MS-7C95                       | 1        | 0.25%   |
| MSI MS-7C91                       | 1        | 0.25%   |
| MSI MS-7C84                       | 1        | 0.25%   |
| MSI MS-7C59                       | 1        | 0.25%   |
| MSI MS-7C51                       | 1        | 0.25%   |
| MSI MS-7C35                       | 1        | 0.25%   |
| MSI MS-7C08                       | 1        | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell OptiPlex              | 46       | 11.36%  |
| HP Compaq                  | 32       | 7.9%    |
| ASUS PRIME                 | 18       | 4.44%   |
| Lenovo ThinkCentre         | 12       | 2.96%   |
| HP ProDesk                 | 9        | 2.22%   |
| ASUS ROG                   | 9        | 2.22%   |
| ASUS All                   | 9        | 2.22%   |
| Dell Precision             | 6        | 1.48%   |
| Unknown                    | 6        | 1.48%   |
| ASUS M5A97                 | 5        | 1.23%   |
| ASUS M5A78L-M              | 5        | 1.23%   |
| Gigabyte B450M             | 3        | 0.74%   |
| Gigabyte B450              | 3        | 0.74%   |
| ASRock B450M               | 3        | 0.74%   |
| Acer Aspire                | 3        | 0.74%   |
| MSI MS-7C94                | 2        | 0.49%   |
| MSI MS-7B49                | 2        | 0.49%   |
| MSI MS-7817                | 2        | 0.49%   |
| MSI MS-7816                | 2        | 0.49%   |
| MSI MS-7680                | 2        | 0.49%   |
| Intel DG31PR               | 2        | 0.49%   |
| HP ProLiant                | 2        | 0.49%   |
| Gigabyte Z97-HD3           | 2        | 0.49%   |
| Gigabyte X570              | 2        | 0.49%   |
| Fujitsu Siemens ESPRIMO    | 2        | 0.49%   |
| Dell Inspiron              | 2        | 0.49%   |
| ASUS TUF                   | 2        | 0.49%   |
| ASUS P9X79                 | 2        | 0.49%   |
| ASUS P8Z68-V               | 2        | 0.49%   |
| ASUS P8H61-M               | 2        | 0.49%   |
| ASUS P8B75-M               | 2        | 0.49%   |
| ASUS P5KPL-AM              | 2        | 0.49%   |
| ASUS M5A99X                | 2        | 0.49%   |
| ASUS M5A78L                | 2        | 0.49%   |
| ASUS M2N68-AM              | 2        | 0.49%   |
| ASUS H61M-K                | 2        | 0.49%   |
| ASRock N68C-S              | 2        | 0.49%   |
| ASRock 970                 | 2        | 0.49%   |
| ZOTAC NM10                 | 1        | 0.25%   |
| TYAN S8230                 | 1        | 0.25%   |
| TEKNOSERVICE TTL-TEKNOSLIM | 1        | 0.25%   |
| Supermicro H8DM8-2         | 1        | 0.25%   |
| Supermicro H8DI3+          | 1        | 0.25%   |
| Semp Toshiba STI           | 1        | 0.25%   |
| Pegatron VG271AA-ABF       | 1        | 0.25%   |
| Pegatron KT373AA-ABA       | 1        | 0.25%   |
| Pegatron KQ467AA-ABE       | 1        | 0.25%   |
| Pegatron FR484AA-UUW       | 1        | 0.25%   |
| Pegatron Compaq            | 1        | 0.25%   |
| Packard Bell imedia        | 1        | 0.25%   |
| MSI MS-7C95                | 1        | 0.25%   |
| MSI MS-7C91                | 1        | 0.25%   |
| MSI MS-7C84                | 1        | 0.25%   |
| MSI MS-7C59                | 1        | 0.25%   |
| MSI MS-7C51                | 1        | 0.25%   |
| MSI MS-7C35                | 1        | 0.25%   |
| MSI MS-7C08                | 1        | 0.25%   |
| MSI MS-7C02                | 1        | 0.25%   |
| MSI MS-7B89                | 1        | 0.25%   |
| MSI MS-7B84                | 1        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 50       | 12.35%  |
| 2012 | 42       | 10.37%  |
| 2018 | 39       | 9.63%   |
| 2009 | 39       | 9.63%   |
| 2013 | 37       | 9.14%   |
| 2014 | 29       | 7.16%   |
| 2008 | 23       | 5.68%   |
| 2010 | 22       | 5.43%   |
| 2020 | 20       | 4.94%   |
| 2017 | 18       | 4.44%   |
| 2015 | 17       | 4.2%    |
| 2019 | 16       | 3.95%   |
| 2007 | 15       | 3.7%    |
| 2006 | 12       | 2.96%   |
| 2016 | 10       | 2.47%   |
| 2005 | 10       | 2.47%   |
| 2021 | 5        | 1.23%   |
| 2004 | 1        | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 405      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 397      | 98.02%  |
| Enabled  | 8        | 1.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 405      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 117      | 28.61%  |
| 8.01-16.0       | 76       | 18.58%  |
| 16.01-24.0      | 70       | 17.11%  |
| 4.01-8.0        | 52       | 12.71%  |
| 32.01-64.0      | 33       | 8.07%   |
| 64.01-256.0     | 23       | 5.62%   |
| 1.01-2.0        | 16       | 3.91%   |
| 2.01-3.0        | 15       | 3.67%   |
| 24.01-32.0      | 5        | 1.22%   |
| More than 256.0 | 1        | 0.24%   |
| 0.51-1.0        | 1        | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 150      | 34.17%  |
| 0.51-1.0   | 95       | 21.64%  |
| 2.01-3.0   | 82       | 18.68%  |
| 3.01-4.0   | 43       | 9.79%   |
| 4.01-8.0   | 40       | 9.11%   |
| 8.01-16.0  | 13       | 2.96%   |
| 0.01-0.5   | 8        | 1.82%   |
| 24.01-32.0 | 3        | 0.68%   |
| 16.01-24.0 | 3        | 0.68%   |
| 32.01-64.0 | 2        | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 198      | 47.83%  |
| 2      | 112      | 27.05%  |
| 3      | 52       | 12.56%  |
| 4      | 25       | 6.04%   |
| 5      | 7        | 1.69%   |
| 6      | 6        | 1.45%   |
| 7      | 4        | 0.97%   |
| 10     | 3        | 0.72%   |
| 11     | 2        | 0.48%   |
| 8      | 2        | 0.48%   |
| 0      | 2        | 0.48%   |
| 12     | 1        | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 258      | 62.62%  |
| No        | 154      | 37.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 403      | 99.51%  |
| No        | 2        | 0.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 278      | 67.64%  |
| Yes       | 133      | 32.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 329      | 80.64%  |
| Yes       | 79       | 19.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Brazil       | 66       | 16.3%   |
| USA          | 51       | 12.59%  |
| Germany      | 35       | 8.64%   |
| France       | 32       | 7.9%    |
| Greece       | 31       | 7.65%   |
| Russia       | 24       | 5.93%   |
| UK           | 19       | 4.69%   |
| Spain        | 18       | 4.44%   |
| Italy        | 15       | 3.7%    |
| Argentina    | 12       | 2.96%   |
| Canada       | 11       | 2.72%   |
| Australia    | 8        | 1.98%   |
| Poland       | 7        | 1.73%   |
| Netherlands  | 7        | 1.73%   |
| Hungary      | 6        | 1.48%   |
| Czechia      | 5        | 1.23%   |
| Ukraine      | 4        | 0.99%   |
| Peru         | 4        | 0.99%   |
| Finland      | 4        | 0.99%   |
| Belgium      | 4        | 0.99%   |
| Mexico       | 3        | 0.74%   |
| Austria      | 3        | 0.74%   |
| Taiwan       | 2        | 0.49%   |
| Switzerland  | 2        | 0.49%   |
| Sweden       | 2        | 0.49%   |
| Romania      | 2        | 0.49%   |
| Japan        | 2        | 0.49%   |
| Cyprus       | 2        | 0.49%   |
| Croatia      | 2        | 0.49%   |
| Chile        | 2        | 0.49%   |
| Bulgaria     | 2        | 0.49%   |
| Venezuela    | 1        | 0.25%   |
| Thailand     | 1        | 0.25%   |
| South Africa | 1        | 0.25%   |
| Slovenia     | 1        | 0.25%   |
| Singapore    | 1        | 0.25%   |
| Portugal     | 1        | 0.25%   |
| Philippines  | 1        | 0.25%   |
| Pakistan     | 1        | 0.25%   |
| Norway       | 1        | 0.25%   |
| Israel       | 1        | 0.25%   |
| India        | 1        | 0.25%   |
| Hong Kong    | 1        | 0.25%   |
| Guatemala    | 1        | 0.25%   |
| Estonia      | 1        | 0.25%   |
| Denmark      | 1        | 0.25%   |
| Belarus      | 1        | 0.25%   |
| Bangladesh   | 1        | 0.25%   |
| Albania      | 1        | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Sao Paulo            | 25       | 5.98%   |
| JundiaГ­           | 20       | 4.78%   |
| Thessaloniki         | 17       | 4.07%   |
| Old Faliron          | 11       | 2.63%   |
| Paris                | 6        | 1.44%   |
| Berlin               | 6        | 1.44%   |
| Moscow               | 5        | 1.2%    |
| St Petersburg        | 4        | 0.96%   |
| Rome                 | 4        | 0.96%   |
| Manchester           | 4        | 0.96%   |
| Madrid               | 4        | 0.96%   |
| Itatiba              | 4        | 0.96%   |
| Vienna               | 3        | 0.72%   |
| Oktyabr'skiy         | 3        | 0.72%   |
| Florence             | 3        | 0.72%   |
| Yekaterinburg        | 2        | 0.48%   |
| WЕ‚ocЕ‚awek    | 2        | 0.48%   |
| Windsor              | 2        | 0.48%   |
| Toronto              | 2        | 0.48%   |
| Stuttgart            | 2        | 0.48%   |
| Portet-sur-Garonne   | 2        | 0.48%   |
| Perth                | 2        | 0.48%   |
| Milan                | 2        | 0.48%   |
| Melbourne            | 2        | 0.48%   |
| Limassol             | 2        | 0.48%   |
| Lima                 | 2        | 0.48%   |
| Le Kremlin-Bicetre   | 2        | 0.48%   |
| Kirchheim unter Teck | 2        | 0.48%   |
| Karlsruhe            | 2        | 0.48%   |
| Kansas City          | 2        | 0.48%   |
| Hamburg              | 2        | 0.48%   |
| Foz do IguaГ§u     | 2        | 0.48%   |
| Enger                | 2        | 0.48%   |
| Cleveland            | 2        | 0.48%   |
| Budapest             | 2        | 0.48%   |
| Biysk                | 2        | 0.48%   |
| Bilbao               | 2        | 0.48%   |
| Barcelona            | 2        | 0.48%   |
| Bagnoles-de-l'Orne   | 2        | 0.48%   |
| Adelaide             | 2        | 0.48%   |
| Zurich               | 1        | 0.24%   |
| Zsaka                | 1        | 0.24%   |
| Zagreb               | 1        | 0.24%   |
| XГ tiva            | 1        | 0.24%   |
| Wroclaw              | 1        | 0.24%   |
| Worb                 | 1        | 0.24%   |
| Westbury             | 1        | 0.24%   |
| Wertheim am Main     | 1        | 0.24%   |
| Wejherowo            | 1        | 0.24%   |
| Warsaw               | 1        | 0.24%   |
| Warrnambool          | 1        | 0.24%   |
| Warren Township      | 1        | 0.24%   |
| Warren               | 1        | 0.24%   |
| Wallasey             | 1        | 0.24%   |
| Volta Redonda        | 1        | 0.24%   |
| Vladikavkaz          | 1        | 0.24%   |
| Village-Neuf         | 1        | 0.24%   |
| Vigo                 | 1        | 0.24%   |
| ViamГЈo            | 1        | 0.24%   |
| Venice               | 1        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 154      | 237    | 23.44%  |
| Seagate                   | 143      | 240    | 21.77%  |
| Samsung Electronics       | 94       | 149    | 14.31%  |
| Toshiba                   | 38       | 58     | 5.78%   |
| Kingston                  | 38       | 50     | 5.78%   |
| Hitachi                   | 26       | 31     | 3.96%   |
| SanDisk                   | 24       | 26     | 3.65%   |
| Crucial                   | 20       | 27     | 3.04%   |
| Intel                     | 18       | 22     | 2.74%   |
| Unknown                   | 10       | 16     | 1.52%   |
| A-DATA Technology         | 9        | 9      | 1.37%   |
| MAXTOR                    | 6        | 14     | 0.91%   |
| PNY                       | 5        | 6      | 0.76%   |
| Phison                    | 5        | 5      | 0.76%   |
| Patriot                   | 5        | 7      | 0.76%   |
| HGST                      | 5        | 7      | 0.76%   |
| China                     | 5        | 8      | 0.76%   |
| Silicon Motion            | 4        | 5      | 0.61%   |
| JMicron                   | 3        | 3      | 0.46%   |
| SK Hynix                  | 2        | 2      | 0.3%    |
| OCZ                       | 2        | 2      | 0.3%    |
| Micron/Crucial Technology | 2        | 5      | 0.3%    |
| LITEONIT                  | 2        | 2      | 0.3%    |
| LDLC                      | 2        | 2      | 0.3%    |
| Intenso                   | 2        | 4      | 0.3%    |
| Hewlett-Packard           | 2        | 2      | 0.3%    |
| Fujitsu                   | 2        | 2      | 0.3%    |
| Corsair                   | 2        | 2      | 0.3%    |
| Apacer                    | 2        | 2      | 0.3%    |
| USB3.0                    | 1        | 1      | 0.15%   |
| TO Exter                  | 1        | 1      | 0.15%   |
| Team                      | 1        | 1      | 0.15%   |
| TCSUNBOW                  | 1        | 1      | 0.15%   |
| STM                       | 1        | 1      | 0.15%   |
| SPCC                      | 1        | 1      | 0.15%   |
| SMI                       | 1        | 1      | 0.15%   |
| SABRENT                   | 1        | 1      | 0.15%   |
| PLEXTOR                   | 1        | 1      | 0.15%   |
| Mushkin                   | 1        | 1      | 0.15%   |
| Micron Technology         | 1        | 1      | 0.15%   |
| MEDIATEK                  | 1        | 1      | 0.15%   |
| Marlin                    | 1        | 1      | 0.15%   |
| Lexar                     | 1        | 1      | 0.15%   |
| Leven                     | 1        | 1      | 0.15%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.15%   |
| KESU                      | 1        | 2      | 0.15%   |
| Inateck                   | 1        | 1      | 0.15%   |
| BAITITON                  | 1        | 1      | 0.15%   |
| ASMT109x                  | 1        | 2      | 0.15%   |
| ASMT                      | 1        | 2      | 0.15%   |
| AMD                       | 1        | 1      | 0.15%   |
| AGI                       | 1        | 2      | 0.15%   |
| addlink                   | 1        | 2      | 0.15%   |
| ADATA SP                  | 1        | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 19       | 2.5%    |
| WDC WD10EZEX-08WN4A0 1TB         | 11       | 1.45%   |
| Toshiba DT01ACA100 1TB           | 9        | 1.19%   |
| Seagate ST3500418AS 500GB        | 9        | 1.19%   |
| Kingston SA400S37120G 120GB SSD  | 9        | 1.19%   |
| Toshiba DT01ACA050 500GB         | 8        | 1.05%   |
| Seagate ST2000DM001-1ER164 2TB   | 8        | 1.05%   |
| WDC WD5000AAKX-003CA0 500GB      | 7        | 0.92%   |
| Seagate ST1000DM010-2EP102 1TB   | 7        | 0.92%   |
| Samsung SSD 860 EVO 500GB        | 7        | 0.92%   |
| WDC WD5000AAKX-083CA1 500GB      | 6        | 0.79%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 6        | 0.79%   |
| WDC WD10EZEX-00BN5A0 1TB         | 6        | 0.79%   |
| Seagate ST1000DM003-1CH162 1TB   | 6        | 0.79%   |
| Toshiba DT01ACA200 2TB           | 5        | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 0.66%   |
| Seagate Expansion 1TB            | 5        | 0.66%   |
| Samsung NVMe SSD Drive 500GB     | 5        | 0.66%   |
| Samsung HD322HJ 320GB            | 5        | 0.66%   |
| Kingston SV300S37A120G 120GB SSD | 5        | 0.66%   |
| Intel SSDSA2BW120G3H 120GB       | 5        | 0.66%   |
| WDC WD2500AAKX-753CA1 250GB      | 4        | 0.53%   |
| WDC WD20EARX-00PASB0 2TB         | 4        | 0.53%   |
| WDC WD10EZEX-00WN4A0 1TB         | 4        | 0.53%   |
| Unknown SD/MMC/MS PRO 394GB      | 4        | 0.53%   |
| Seagate ST3500630AS 500GB        | 4        | 0.53%   |
| Seagate ST2000DM001-9YN164 2TB   | 4        | 0.53%   |
| SanDisk SDSSDA240G 240GB         | 4        | 0.53%   |
| Samsung SSD 850 EVO 250GB        | 4        | 0.53%   |
| Samsung HD103SJ 1TB              | 4        | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 3        | 0.4%    |
| WDC WD30EFRX-68EUZN0 3TB         | 3        | 0.4%    |
| WDC WD10EZEX-08M2NA0 1TB         | 3        | 0.4%    |
| Toshiba HDWD130 3TB              | 3        | 0.4%    |
| Seagate ST8000DM004-2CX188 8TB   | 3        | 0.4%    |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 0.4%    |
| Seagate ST3500413AS 500GB        | 3        | 0.4%    |
| Seagate ST3320620AS 320GB        | 3        | 0.4%    |
| Seagate ST31000528AS 1TB         | 3        | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB   | 3        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB   | 3        | 0.4%    |
| SanDisk SSD PLUS 480GB           | 3        | 0.4%    |
| SanDisk SDSSDA120G 120GB         | 3        | 0.4%    |
| Samsung SSD 980 PRO 1TB          | 3        | 0.4%    |
| Samsung SSD 970 EVO 500GB        | 3        | 0.4%    |
| Samsung SSD 840 Series 250GB     | 3        | 0.4%    |
| Samsung SSD 840 EVO 250GB        | 3        | 0.4%    |
| Samsung SP2504C 250GB            | 3        | 0.4%    |
| Samsung HD502HJ 500GB            | 3        | 0.4%    |
| Kingston SV300S37A240G 240GB SSD | 3        | 0.4%    |
| Hitachi HDP725050GLA360 500GB    | 3        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB      | 3        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2        | 0.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 0.26%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.26%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 2        | 0.26%   |
| WDC WD5000AZLX-08K2TA0 500GB     | 2        | 0.26%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 2        | 0.26%   |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 0.26%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 142      | 238    | 35.68%  |
| WDC                 | 140      | 209    | 35.18%  |
| Toshiba             | 36       | 56     | 9.05%   |
| Samsung Electronics | 32       | 37     | 8.04%   |
| Hitachi             | 26       | 31     | 6.53%   |
| Unknown             | 6        | 9      | 1.51%   |
| MAXTOR              | 5        | 11     | 1.26%   |
| HGST                | 5        | 7      | 1.26%   |
| Fujitsu             | 2        | 2      | 0.5%    |
| SABRENT             | 1        | 1      | 0.25%   |
| KESU                | 1        | 2      | 0.25%   |
| JMicron             | 1        | 1      | 0.25%   |
| ASMT109x            | 1        | 2      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 47       | 75     | 23.04%  |
| Kingston            | 32       | 39     | 15.69%  |
| SanDisk             | 24       | 26     | 11.76%  |
| Crucial             | 19       | 26     | 9.31%   |
| WDC                 | 18       | 26     | 8.82%   |
| Intel               | 15       | 19     | 7.35%   |
| A-DATA Technology   | 9        | 9      | 4.41%   |
| PNY                 | 5        | 6      | 2.45%   |
| China               | 5        | 8      | 2.45%   |
| Patriot             | 4        | 6      | 1.96%   |
| OCZ                 | 2        | 2      | 0.98%   |
| LITEONIT            | 2        | 2      | 0.98%   |
| Apacer              | 2        | 2      | 0.98%   |
| USB3.0              | 1        | 1      | 0.49%   |
| Unknown             | 1        | 2      | 0.49%   |
| Toshiba             | 1        | 1      | 0.49%   |
| TO Exter            | 1        | 1      | 0.49%   |
| Team                | 1        | 1      | 0.49%   |
| SMI                 | 1        | 1      | 0.49%   |
| Seagate             | 1        | 1      | 0.49%   |
| PLEXTOR             | 1        | 1      | 0.49%   |
| Mushkin             | 1        | 1      | 0.49%   |
| Micron Technology   | 1        | 1      | 0.49%   |
| MAXTOR              | 1        | 3      | 0.49%   |
| Lexar               | 1        | 1      | 0.49%   |
| Leven               | 1        | 1      | 0.49%   |
| LDLC                | 1        | 1      | 0.49%   |
| JMicron             | 1        | 1      | 0.49%   |
| Intenso             | 1        | 3      | 0.49%   |
| BAITITON            | 1        | 1      | 0.49%   |
| ASMT                | 1        | 2      | 0.49%   |
| AMD                 | 1        | 1      | 0.49%   |
| ADATA SP            | 1        | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 318      | 606    | 56.58%  |
| SSD     | 176      | 272    | 31.32%  |
| NVMe    | 56       | 83     | 9.96%   |
| Unknown | 12       | 14     | 2.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 386      | 849    | 81.61%  |
| NVMe | 56       | 83     | 11.84%  |
| SAS  | 31       | 43     | 6.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 300      | 478    | 55.87%  |
| 0.51-1.0   | 140      | 231    | 26.07%  |
| 1.01-2.0   | 52       | 87     | 9.68%   |
| 4.01-10.0  | 17       | 38     | 3.17%   |
| 3.01-4.0   | 16       | 23     | 2.98%   |
| 2.01-3.0   | 11       | 20     | 2.05%   |
| 10.01-20.0 | 1        | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 104      | 24.82%  |
| 101-250        | 82       | 19.57%  |
| 501-1000       | 66       | 15.75%  |
| 1001-2000      | 50       | 11.93%  |
| More than 3000 | 37       | 8.83%   |
| Unknown        | 26       | 6.21%   |
| 2001-3000      | 21       | 5.01%   |
| 51-100         | 14       | 3.34%   |
| 21-50          | 10       | 2.39%   |
| 1-20           | 9        | 2.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 123      | 28.41%  |
| 21-50          | 60       | 13.86%  |
| 101-250        | 50       | 11.55%  |
| 251-500        | 48       | 11.09%  |
| 51-100         | 42       | 9.7%    |
| 501-1000       | 30       | 6.93%   |
| 1001-2000      | 28       | 6.47%   |
| Unknown        | 26       | 6%      |
| More than 3000 | 13       | 3%      |
| 2001-3000      | 13       | 3%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 6        | 6      | 8.22%   |
| WDC WD5000AAKX-083CA1 500GB           | 4        | 4      | 5.48%   |
| Seagate ST3500418AS 500GB             | 4        | 4      | 5.48%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 2.74%   |
| WDC WD2500AAKX-753CA1 250GB           | 2        | 2      | 2.74%   |
| Unknown MM0500EANCR 500GB             | 2        | 5      | 2.74%   |
| Seagate ST2000DM001-9YN164 2TB        | 2        | 3      | 2.74%   |
| Seagate ST1000DM003-1CH162 1TB        | 2        | 2      | 2.74%   |
| Samsung Electronics HD502HJ 500GB     | 2        | 2      | 2.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1        | 1      | 1.37%   |
| WDC WD40EFAX-68JH4N0 4TB              | 1        | 1      | 1.37%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1        | 1      | 1.37%   |
| WDC WD2500YS-01SHB1 256GB             | 1        | 1      | 1.37%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1        | 1      | 1.37%   |
| WDC WD2500AAJS-75M0A0 250GB           | 1        | 1      | 1.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 1.37%   |
| WDC WD1600AAJS-75M0A0 160GB           | 1        | 2      | 1.37%   |
| WDC WD15EARS-00Z5B1 1TB               | 1        | 1      | 1.37%   |
| WDC WD15EADS-00P8B0 1TB               | 1        | 1      | 1.37%   |
| WDC WD1200JD-00HBB0 120GB             | 1        | 1      | 1.37%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 1.37%   |
| WDC WD10EFRX-68PJCN0 1TB              | 1        | 1      | 1.37%   |
| WDC WD10EARS-00MVWB0 1TB              | 1        | 1      | 1.37%   |
| WDC WD10EADS-00L5B1 1TB               | 1        | 2      | 1.37%   |
| Toshiba MK5055GSX 500GB               | 1        | 1      | 1.37%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 1.37%   |
| Seagate ST9500530NS 500GB             | 1        | 1      | 1.37%   |
| Seagate ST9320325AS 320GB             | 1        | 1      | 1.37%   |
| Seagate ST4000DM004-2CV104 4TB        | 1        | 1      | 1.37%   |
| Seagate ST3750525AS 752GB             | 1        | 1      | 1.37%   |
| Seagate ST3500320AS 500GB             | 1        | 1      | 1.37%   |
| Seagate ST3402111AS 40GB              | 1        | 1      | 1.37%   |
| Seagate ST3360320AS 360GB             | 1        | 2      | 1.37%   |
| Seagate ST3320620AS 320GB             | 1        | 1      | 1.37%   |
| Seagate ST3320418AS 320GB             | 1        | 1      | 1.37%   |
| Seagate ST3250318AS 250GB             | 1        | 1      | 1.37%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 1.37%   |
| Seagate ST32000644NS 2TB              | 1        | 1      | 1.37%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 1.37%   |
| SanDisk SSD PLUS 480GB                | 1        | 1      | 1.37%   |
| Samsung Electronics SSD 960 PRO 1TB   | 1        | 1      | 1.37%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 1.37%   |
| Samsung Electronics SP2504C 250GB     | 1        | 1      | 1.37%   |
| Samsung Electronics M3 Portable 500GB | 1        | 1      | 1.37%   |
| Samsung Electronics HD501LJ 500GB     | 1        | 1      | 1.37%   |
| MAXTOR STM3320613AS 320GB             | 1        | 1      | 1.37%   |
| MAXTOR 6Y160M0 160GB                  | 1        | 1      | 1.37%   |
| Kingston SHPM2280P2H 240G SSD         | 1        | 1      | 1.37%   |
| Intel SSDSA2M080G2GC 80GB             | 1        | 1      | 1.37%   |
| Hitachi HDT721050SLA360 500GB         | 1        | 1      | 1.37%   |
| Hitachi HDS721010CLA332 1TB           | 1        | 1      | 1.37%   |
| HGST HDN726040ALE614 4TB              | 1        | 2      | 1.37%   |
| Crucial CT525MX300SSD1 528GB          | 1        | 1      | 1.37%   |
| Crucial CT1050MX300SSD1 1TB           | 1        | 1      | 1.37%   |
| ASMT USB 3.0 Destop H 1TB SSD         | 1        | 2      | 1.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 30     | 38.03%  |
| WDC                 | 22       | 25     | 30.99%  |
| Samsung Electronics | 7        | 7      | 9.86%   |
| Unknown             | 2        | 5      | 2.82%   |
| Toshiba             | 2        | 2      | 2.82%   |
| MAXTOR              | 2        | 2      | 2.82%   |
| Hitachi             | 2        | 2      | 2.82%   |
| Crucial             | 2        | 2      | 2.82%   |
| SanDisk             | 1        | 1      | 1.41%   |
| Kingston            | 1        | 1      | 1.41%   |
| Intel               | 1        | 1      | 1.41%   |
| HGST                | 1        | 2      | 1.41%   |
| ASMT                | 1        | 2      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 30     | 43.55%  |
| WDC                 | 21       | 24     | 33.87%  |
| Samsung Electronics | 5        | 5      | 8.06%   |
| Unknown             | 2        | 5      | 3.23%   |
| Toshiba             | 2        | 2      | 3.23%   |
| MAXTOR              | 2        | 2      | 3.23%   |
| Hitachi             | 2        | 2      | 3.23%   |
| HGST                | 1        | 2      | 1.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 58       | 72     | 87.88%  |
| SSD  | 7        | 9      | 10.61%  |
| NVMe | 1        | 1      | 1.52%   |

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
| Detected | 206      | 518    | 44.98%  |
| Works    | 189      | 375    | 41.27%  |
| Malfunc  | 63       | 82     | 13.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 268      | 52.96%  |
| AMD                           | 110      | 21.74%  |
| Samsung Electronics           | 23       | 4.55%   |
| Nvidia                        | 21       | 4.15%   |
| Marvell Technology Group      | 16       | 3.16%   |
| ASMedia Technology            | 14       | 2.77%   |
| Phison Electronics            | 9        | 1.78%   |
| JMicron Technology            | 9        | 1.78%   |
| Kingston Technology Company   | 8        | 1.58%   |
| Silicon Motion                | 7        | 1.38%   |
| VIA Technologies              | 3        | 0.59%   |
| Micron/Crucial Technology     | 3        | 0.59%   |
| SK Hynix                      | 2        | 0.4%    |
| Sandisk                       | 2        | 0.4%    |
| LSI Logic / Symbios Logic     | 2        | 0.4%    |
| Toshiba America Info Systems  | 1        | 0.2%    |
| Silicon Image                 | 1        | 0.2%    |
| Lite-On IT Corp. / Plextor    | 1        | 0.2%    |
| KIOXIA                        | 1        | 0.2%    |
| Integrated Technology Express | 1        | 0.2%    |
| Hewlett-Packard               | 1        | 0.2%    |
| Broadcom / LSI                | 1        | 0.2%    |
| ADATA Technology              | 1        | 0.2%    |
| Adaptec                       | 1        | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 49       | 7.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 41       | 6.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 37       | 5.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 34       | 5.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 28       | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 26       | 3.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 24       | 3.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 21       | 3.12%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 2.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 17       | 2.52%   |
| Nvidia MCP61 SATA Controller                                                            | 15       | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15       | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15       | 2.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 14       | 2.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13       | 1.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 12       | 1.78%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 1.63%   |
| Nvidia MCP61 IDE                                                                        | 9        | 1.34%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 1.34%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 7        | 1.04%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 6        | 0.89%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 0.89%   |
| Phison E12 NVMe Controller                                                              | 5        | 0.74%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.74%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 5        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 0.59%   |
| JMicron JMB362 SATA Controller                                                          | 4        | 0.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4        | 0.59%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.59%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.59%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 0.59%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 0.59%   |
| AMD FCH SATA Controller D                                                               | 4        | 0.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.45%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 3        | 0.45%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.45%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 0.45%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.45%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.45%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.45%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 3        | 0.45%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.45%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.45%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 3        | 0.45%   |
| AMD SB600 IDE                                                                           | 3        | 0.45%   |
| AMD FCH IDE Controller                                                                  | 3        | 0.45%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.3%    |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 2        | 0.3%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.3%    |
| Nvidia MCP79 AHCI Controller                                                            | 2        | 0.3%    |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 2        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 288      | 55.81%  |
| IDE  | 146      | 28.29%  |
| NVMe | 56       | 10.85%  |
| RAID | 20       | 3.88%   |
| SAS  | 4        | 0.78%   |
| SCSI | 2        | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 278      | 68.64%  |
| AMD    | 127      | 31.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 9        | 2.22%   |
| AMD Phenom II X4 B97 Processor              | 7        | 1.73%   |
| Intel Pentium 4 CPU 3.00GHz                 | 6        | 1.48%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 6        | 1.48%   |
| Intel Celeron CPU G1840 @ 2.80GHz           | 6        | 1.48%   |
| Intel Pentium D CPU 2.80GHz                 | 5        | 1.23%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 5        | 1.23%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 5        | 1.23%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 5        | 1.23%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 5        | 1.23%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 1.23%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 1.23%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 1.23%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 4        | 0.99%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 0.99%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 4        | 0.99%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 4        | 0.99%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 0.99%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 4        | 0.99%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 4        | 0.99%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 4        | 0.99%   |
| AMD FX-6300 Six-Core Processor              | 4        | 0.99%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 3        | 0.74%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 3        | 0.74%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.74%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.74%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.74%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.74%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.74%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 3        | 0.74%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 0.74%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 3        | 0.74%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.74%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 0.74%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3        | 0.74%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 0.74%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.74%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.74%   |
| AMD FX-6100 Six-Core Processor              | 3        | 0.74%   |
| AMD Athlon II X2 250 Processor              | 3        | 0.74%   |
| AMD Athlon II X2 245 Processor              | 3        | 0.74%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 0.49%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 0.49%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 0.49%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 0.49%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 0.49%   |
| Intel Pentium 4 CPU 3.40GHz                 | 2        | 0.49%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 0.49%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.49%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.49%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.49%   |
| Intel Core i7-4790S CPU @ 3.20GHz           | 2        | 0.49%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.49%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.49%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.49%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.49%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 2        | 0.49%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 0.49%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 77       | 19.01%  |
| Intel Core i3           | 38       | 9.38%   |
| Intel Core i7           | 32       | 7.9%    |
| Intel Core 2 Duo        | 22       | 5.43%   |
| AMD Ryzen 5             | 21       | 5.19%   |
| Intel Xeon              | 18       | 4.44%   |
| AMD FX                  | 18       | 4.44%   |
| Intel Celeron           | 17       | 4.2%    |
| Intel Core 2 Quad       | 16       | 3.95%   |
| Intel Pentium           | 15       | 3.7%    |
| AMD Athlon II X2        | 15       | 3.7%    |
| AMD Phenom II X4        | 13       | 3.21%   |
| AMD Ryzen 7             | 11       | 2.72%   |
| Intel Pentium Dual-Core | 10       | 2.47%   |
| Intel Pentium 4         | 9        | 2.22%   |
| AMD Ryzen 3             | 7        | 1.73%   |
| Intel Pentium D         | 6        | 1.48%   |
| AMD Ryzen 9             | 6        | 1.48%   |
| Other                   | 5        | 1.23%   |
| AMD Athlon 64 X2        | 5        | 1.23%   |
| Intel Core 2            | 4        | 0.99%   |
| Intel Atom              | 4        | 0.99%   |
| AMD A8                  | 4        | 0.99%   |
| Intel Pentium Dual      | 3        | 0.74%   |
| Intel Core i9           | 3        | 0.74%   |
| AMD Ryzen Threadripper  | 3        | 0.74%   |
| AMD Athlon              | 3        | 0.74%   |
| AMD Turion II Neo       | 2        | 0.49%   |
| AMD Six-Core Opteron    | 2        | 0.49%   |
| AMD Phenom II X6        | 2        | 0.49%   |
| AMD Athlon II X4        | 2        | 0.49%   |
| AMD A6                  | 2        | 0.49%   |
| AMD A4                  | 2        | 0.49%   |
| Intel Pentium Gold      | 1        | 0.25%   |
| AMD Ryzen 3 PRO         | 1        | 0.25%   |
| AMD Phenom II X2        | 1        | 0.25%   |
| AMD Phenom              | 1        | 0.25%   |
| AMD Opteron             | 1        | 0.25%   |
| AMD Athlon Dual Core    | 1        | 0.25%   |
| AMD Athlon 64           | 1        | 0.25%   |
| AMD A10                 | 1        | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 160      | 39.51%  |
| 2       | 142      | 35.06%  |
| 6       | 38       | 9.38%   |
| 1       | 19       | 4.69%   |
| 8       | 18       | 4.44%   |
| 16      | 9        | 2.22%   |
| 3       | 7        | 1.73%   |
| 12      | 5        | 1.23%   |
| 10      | 3        | 0.74%   |
| 24      | 2        | 0.49%   |
| 32      | 1        | 0.25%   |
| Unknown | 1        | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 396      | 97.78%  |
| 2      | 9        | 2.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 238      | 58.62%  |
| 2       | 167      | 41.13%  |
| Unknown | 1        | 0.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 402      | 99.26%  |
| 32-bit         | 3        | 0.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 62       | 14.94%  |
| 0x306c3    | 46       | 11.08%  |
| 0x306a9    | 30       | 7.23%   |
| 0x206a7    | 28       | 6.75%   |
| 0x1067a    | 24       | 5.78%   |
| 0x010000c8 | 20       | 4.82%   |
| 0x506e3    | 10       | 2.41%   |
| 0x08701021 | 10       | 2.41%   |
| 0x06000852 | 10       | 2.41%   |
| 0x906ea    | 9        | 2.17%   |
| 0x906e9    | 9        | 2.17%   |
| 0x6fd      | 9        | 2.17%   |
| 0x6fb      | 8        | 1.93%   |
| 0xf41      | 7        | 1.69%   |
| 0x10676    | 7        | 1.69%   |
| 0x06001119 | 7        | 1.69%   |
| 0xa0653    | 5        | 1.2%    |
| 0x08701013 | 5        | 1.2%    |
| 0x0800820d | 5        | 1.2%    |
| 0x010000db | 5        | 1.2%    |
| 0xf47      | 4        | 0.96%   |
| 0x906eb    | 4        | 0.96%   |
| 0x6f6      | 4        | 0.96%   |
| 0x30678    | 4        | 0.96%   |
| 0x206d7    | 4        | 0.96%   |
| 0x0810100b | 4        | 0.96%   |
| 0xa0671    | 3        | 0.72%   |
| 0x906ed    | 3        | 0.72%   |
| 0x306f2    | 3        | 0.72%   |
| 0x20655    | 3        | 0.72%   |
| 0x106e5    | 3        | 0.72%   |
| 0x106c2    | 3        | 0.72%   |
| 0x106a5    | 3        | 0.72%   |
| 0x08101016 | 3        | 0.72%   |
| 0x08001138 | 3        | 0.72%   |
| 0xf64      | 2        | 0.48%   |
| 0x6f7      | 2        | 0.48%   |
| 0x10677    | 2        | 0.48%   |
| 0x0a201016 | 2        | 0.48%   |
| 0x08108109 | 2        | 0.48%   |
| 0x0800820b | 2        | 0.48%   |
| 0x06003106 | 2        | 0.48%   |
| 0x0600063e | 2        | 0.48%   |
| 0x010000c7 | 2        | 0.48%   |
| 0xf62      | 1        | 0.24%   |
| 0xf49      | 1        | 0.24%   |
| 0xf43      | 1        | 0.24%   |
| 0xf29      | 1        | 0.24%   |
| 0xa0655    | 1        | 0.24%   |
| 0x906ec    | 1        | 0.24%   |
| 0x806ec    | 1        | 0.24%   |
| 0x806ea    | 1        | 0.24%   |
| 0x806e9    | 1        | 0.24%   |
| 0x406c3    | 1        | 0.24%   |
| 0x306e4    | 1        | 0.24%   |
| 0x206d6    | 1        | 0.24%   |
| 0x206c2    | 1        | 0.24%   |
| 0x0a50000c | 1        | 0.24%   |
| 0x0a50000b | 1        | 0.24%   |
| 0x0a201009 | 1        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 51       | 12.59%  |
| SandyBridge | 40       | 9.88%   |
| K10         | 40       | 9.88%   |
| Penryn      | 38       | 9.38%   |
| KabyLake    | 34       | 8.4%    |
| IvyBridge   | 32       | 7.9%    |
| Core        | 23       | 5.68%   |
| Piledriver  | 21       | 5.19%   |
| Zen 2       | 20       | 4.94%   |
| NetBurst    | 17       | 4.2%    |
| Zen         | 15       | 3.7%    |
| Skylake     | 12       | 2.96%   |
| Zen+        | 10       | 2.47%   |
| K8 Hammer   | 8        | 1.98%   |
| Nehalem     | 7        | 1.73%   |
| CometLake   | 7        | 1.73%   |
| Zen 3       | 5        | 1.23%   |
| Westmere    | 5        | 1.23%   |
| Silvermont  | 5        | 1.23%   |
| Bulldozer   | 4        | 0.99%   |
| Bonnell     | 4        | 0.99%   |
| Steamroller | 2        | 0.49%   |
| Icelake     | 2        | 0.49%   |
| Jaguar      | 1        | 0.25%   |
| Excavator   | 1        | 0.25%   |
| Unknown     | 1        | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 160      | 37.12%  |
| Nvidia                     | 148      | 34.34%  |
| AMD                        | 119      | 27.61%  |
| ASPEED Technology          | 2        | 0.46%   |
| VIA Technologies           | 1        | 0.23%   |
| Matrox Electronics Systems | 1        | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 31       | 7%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 20       | 4.51%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 19       | 4.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 19       | 4.29%   |
| Nvidia GT218 [GeForce 210]                                                  | 14       | 3.16%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 11       | 2.48%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 11       | 2.48%   |
| AMD RS880 [Radeon HD 4200]                                                  | 11       | 2.48%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 10       | 2.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 2.26%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 2.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8        | 1.81%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 1.58%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.35%   |
| AMD RS780L [Radeon 3000]                                                    | 6        | 1.35%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 6        | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.13%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 5        | 1.13%   |
| Intel HD Graphics 530                                                       | 5        | 1.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.13%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.13%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 0.9%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 0.9%    |
| Intel HD Graphics 630                                                       | 4        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 4        | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.68%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.68%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 0.68%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 3        | 0.68%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.68%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 3        | 0.68%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 0.68%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                        | 3        | 0.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 0.68%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 3        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.45%   |
| Nvidia GT218 [GeForce 310]                                                  | 2        | 0.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.45%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.45%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.45%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.45%   |
| Nvidia GK107GL [Quadro K600]                                                | 2        | 0.45%   |
| Nvidia GK107GL [Quadro K2000]                                               | 2        | 0.45%   |
| Nvidia GK107 [NVS 510]                                                      | 2        | 0.45%   |
| Nvidia GK107 [GeForce GT 740]                                               | 2        | 0.45%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.45%   |
| Nvidia GF119 [GeForce GT 520]                                               | 2        | 0.45%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 2        | 0.45%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 2        | 0.45%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 0.45%   |
| Nvidia GF106GL [Quadro 2000]                                                | 2        | 0.45%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 0.45%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 0.45%   |
| Nvidia C79 [ION]                                                            | 2        | 0.45%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 0.45%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 0.45%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2        | 0.45%   |
| AMD Trinity [Radeon HD 7560D]                                               | 2        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 142      | 34.8%   |
| 1 x Nvidia               | 135      | 33.09%  |
| 1 x AMD                  | 110      | 26.96%  |
| Intel + Nvidia           | 8        | 1.96%   |
| 2 x AMD                  | 5        | 1.23%   |
| 2 x Nvidia               | 2        | 0.49%   |
| 1 x ASPEED               | 2        | 0.49%   |
| 1 x VIA                  | 1        | 0.25%   |
| Nvidia + Matrox          | 1        | 0.25%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.25%   |
| Intel + AMD              | 1        | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 302      | 73.48%  |
| Proprietary | 95       | 23.11%  |
| Unknown     | 14       | 3.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 157      | 38.01%  |
| 1.01-2.0   | 76       | 18.4%   |
| 0.01-0.5   | 65       | 15.74%  |
| 0.51-1.0   | 52       | 12.59%  |
| 3.01-4.0   | 32       | 7.75%   |
| 7.01-8.0   | 21       | 5.08%   |
| 5.01-6.0   | 5        | 1.21%   |
| 2.01-3.0   | 3        | 0.73%   |
| 4.01-5.0   | 1        | 0.24%   |
| 8.01-16.0  | 1        | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 80       | 18.82%  |
| Samsung Electronics  | 69       | 16.24%  |
| Goldstar             | 45       | 10.59%  |
| Hewlett-Packard      | 35       | 8.24%   |
| Acer                 | 29       | 6.82%   |
| Philips              | 21       | 4.94%   |
| BenQ                 | 17       | 4%      |
| Ancor Communications | 16       | 3.76%   |
| AOC                  | 15       | 3.53%   |
| Unknown              | 10       | 2.35%   |
| ViewSonic            | 8        | 1.88%   |
| LG Electronics       | 7        | 1.65%   |
| Iiyama               | 5        | 1.18%   |
| NEC Computers        | 4        | 0.94%   |
| Lenovo               | 4        | 0.94%   |
| Eizo                 | 4        | 0.94%   |
| ASUSTek Computer     | 4        | 0.94%   |
| Toshiba              | 3        | 0.71%   |
| Sony                 | 3        | 0.71%   |
| HannStar             | 3        | 0.71%   |
| Gateway              | 3        | 0.71%   |
| Fujitsu Siemens      | 3        | 0.71%   |
| Belinea              | 3        | 0.71%   |
| Vizio                | 2        | 0.47%   |
| Vestel Elektronik    | 2        | 0.47%   |
| RTK                  | 2        | 0.47%   |
| Packard Bell         | 2        | 0.47%   |
| ONKYO                | 2        | 0.47%   |
| Hitachi              | 2        | 0.47%   |
| FUS                  | 2        | 0.47%   |
| Element              | 2        | 0.47%   |
| Daewoo               | 2        | 0.47%   |
| VIZ                  | 1        | 0.24%   |
| Targa                | 1        | 0.24%   |
| SII                  | 1        | 0.24%   |
| Seiki                | 1        | 0.24%   |
| Sceptre Tech         | 1        | 0.24%   |
| Sceptre              | 1        | 0.24%   |
| ROW                  | 1        | 0.24%   |
| Microstep            | 1        | 0.24%   |
| Medion               | 1        | 0.24%   |
| Insignia             | 1        | 0.24%   |
| IND                  | 1        | 0.24%   |
| Idek Iiyama          | 1        | 0.24%   |
| FSR                  | 1        | 0.24%   |
| Compal               | 1        | 0.24%   |
| AU Optronics         | 1        | 0.24%   |
| Arnos Instruments    | 1        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 31       | 6.83%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                    | 5        | 1.1%    |
| ViewSonic VA703-4Series VSC6A1E 1280x1024 341x274mm 17.2-inch        | 4        | 0.88%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch          | 3        | 0.66%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                     | 3        | 0.66%   |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                    | 3        | 0.66%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch   | 2        | 0.44%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 2        | 0.44%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 340x270mm 17.1-inch | 2        | 0.44%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 2        | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 2        | 0.44%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                    | 2        | 0.44%   |
| Samsung Electronics LCD Monitor C32F391 1920x1080                    | 2        | 0.44%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch    | 2        | 0.44%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch               | 2        | 0.44%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 600x340mm 27.2-inch              | 2        | 0.44%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch           | 2        | 0.44%   |
| Hewlett-Packard L2035 HWP2612 1600x1200 408x306mm 20.1-inch          | 2        | 0.44%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2        | 0.44%   |
| Goldstar W2253 GSM56DB 1920x1080 474x296mm 22.0-inch                 | 2        | 0.44%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2        | 0.44%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 2        | 0.44%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch           | 2        | 0.44%   |
| Goldstar L1953T GSM4B45 1280x1024 338x270mm 17.0-inch                | 2        | 0.44%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 2        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 0.44%   |
| Goldstar E2340 GSM57A6 1920x1080 510x290mm 23.1-inch                 | 2        | 0.44%   |
| Goldstar 23LC1R GSM5617 1360x768 930x523mm 42.0-inch                 | 2        | 0.44%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                    | 2        | 0.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 0.44%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                     | 2        | 0.44%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                   | 2        | 0.44%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 2        | 0.44%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch     | 2        | 0.44%   |
| Acer R221Q ACR0503 1920x1080 476x268mm 21.5-inch                     | 2        | 0.44%   |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                  | 2        | 0.44%   |
| Acer AL1714 ACRAD18 1280x1024 338x270mm 17.0-inch                    | 2        | 0.44%   |
| Vizio VO320E VIZ0035 1366x768 700x390mm 31.5-inch                    | 1        | 0.22%   |
| Vizio M550NV VIZ0063 1920x1080 1210x680mm 54.6-inch                  | 1        | 0.22%   |
| VIZ LCD Monitor E322VL 1920x1080                                     | 1        | 0.22%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch              | 1        | 0.22%   |
| ViewSonic VE902m VSC491B 1280x1024 376x301mm 19.0-inch               | 1        | 0.22%   |
| ViewSonic VE710s VSCF518 1280x1024 338x270mm 17.0-inch               | 1        | 0.22%   |
| ViewSonic VA2223wm VSC0523 1920x1080 480x270mm 21.7-inch             | 1        | 0.22%   |
| Unknown LCD Monitor Sony SDM-X82 1280x1024                           | 1        | 0.22%   |
| Unknown LCD Monitor SAMSUNG 1360x768                                 | 1        | 0.22%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 0.22%   |
| Unknown LCD Monitor PHILIPS FTV 1360x768                             | 1        | 0.22%   |
| Unknown LCD Monitor OOO MA2224W 1920x1080                            | 1        | 0.22%   |
| Unknown LCD Monitor FormacTFT2010 1600x1200                          | 1        | 0.22%   |
| Unknown LCD Monitor ELE E4SW5017RKU                                  | 1        | 0.22%   |
| Unknown LCD Monitor CHHWJT 1920x1080                                 | 1        | 0.22%   |
| Toshiba TV TSB2017 3840x2160                                         | 1        | 0.22%   |
| Toshiba IDTI_HDMI LCD2482 1920x1080 477x268mm 21.5-inch              | 1        | 0.22%   |
| Toshiba 50UHD_LCD_TV TSB3700 1920x1080 1360x768mm 61.5-inch          | 1        | 0.22%   |
| Targa LCD Monitor LCDTV16                                            | 1        | 0.22%   |
| Sony TV SNYEE01 1920x1080                                            | 1        | 0.22%   |
| Sony TV SNY0801 1360x768                                             | 1        | 0.22%   |
| Sony SDM-HX73 SNY2970 1280x1024 338x270mm 17.0-inch                  | 1        | 0.22%   |
| SII SII SPRT RPT SII9575 3840x2160 1270x720mm 57.5-inch              | 1        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 143      | 34.13%  |
| 1280x1024 (SXGA)   | 98       | 23.39%  |
| 3840x2160 (4K)     | 27       | 6.44%   |
| 1366x768 (WXGA)    | 26       | 6.21%   |
| 1680x1050 (WSXGA+) | 19       | 4.53%   |
| 1440x900 (WXGA+)   | 18       | 4.3%    |
| 1360x768           | 15       | 3.58%   |
| Unknown            | 14       | 3.34%   |
| 2560x1440 (QHD)    | 12       | 2.86%   |
| 1920x1200 (WUXGA)  | 9        | 2.15%   |
| 1600x900 (HD+)     | 9        | 2.15%   |
| 1600x1200          | 7        | 1.67%   |
| 3840x1080          | 5        | 1.19%   |
| 1024x768 (XGA)     | 3        | 0.72%   |
| 3440x1440          | 2        | 0.48%   |
| 6400x1080          | 1        | 0.24%   |
| 5840x1440          | 1        | 0.24%   |
| 5760x2160          | 1        | 0.24%   |
| 5040x1050          | 1        | 0.24%   |
| 4240x1440          | 1        | 0.24%   |
| 3840x1200          | 1        | 0.24%   |
| 3200x1080          | 1        | 0.24%   |
| 3000x1920          | 1        | 0.24%   |
| 2880x900           | 1        | 0.24%   |
| 2640x1024          | 1        | 0.24%   |
| 2560x1080          | 1        | 0.24%   |
| 1152x864           | 1        | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 68       | 16.15%  |
| Unknown | 51       | 12.11%  |
| 21      | 43       | 10.21%  |
| 23      | 41       | 9.74%   |
| 19      | 36       | 8.55%   |
| 24      | 34       | 8.08%   |
| 27      | 29       | 6.89%   |
| 18      | 23       | 5.46%   |
| 22      | 16       | 3.8%    |
| 31      | 14       | 3.33%   |
| 20      | 13       | 3.09%   |
| 15      | 13       | 3.09%   |
| 84      | 7        | 1.66%   |
| 72      | 5        | 1.19%   |
| 32      | 5        | 1.19%   |
| 42      | 3        | 0.71%   |
| 40      | 3        | 0.71%   |
| 46      | 2        | 0.48%   |
| 34      | 2        | 0.48%   |
| 33      | 2        | 0.48%   |
| 14      | 2        | 0.48%   |
| 57      | 1        | 0.24%   |
| 54      | 1        | 0.24%   |
| 52      | 1        | 0.24%   |
| 47      | 1        | 0.24%   |
| 41      | 1        | 0.24%   |
| 36      | 1        | 0.24%   |
| 26      | 1        | 0.24%   |
| 25      | 1        | 0.24%   |
| 16      | 1        | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 103      | 25%     |
| 501-600     | 96       | 23.3%   |
| 301-350     | 78       | 18.93%  |
| Unknown     | 51       | 12.38%  |
| 351-400     | 31       | 7.52%   |
| 601-700     | 17       | 4.13%   |
| 1501-2000   | 12       | 2.91%   |
| 701-800     | 10       | 2.43%   |
| 1001-1500   | 6        | 1.46%   |
| 901-1000    | 4        | 0.97%   |
| 801-900     | 3        | 0.73%   |
| 201-300     | 1        | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 197      | 49.5%   |
| 5/4     | 85       | 21.36%  |
| Unknown | 48       | 12.06%  |
| 16/10   | 47       | 11.81%  |
| 4/3     | 12       | 3.02%   |
| 6/5     | 4        | 1.01%   |
| 3/2     | 3        | 0.75%   |
| 21/9    | 2        | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 105      | 25.42%  |
| 141-150        | 84       | 20.34%  |
| 151-200        | 62       | 15.01%  |
| Unknown        | 51       | 12.35%  |
| 301-350        | 29       | 7.02%   |
| 351-500        | 22       | 5.33%   |
| More than 1000 | 15       | 3.63%   |
| 251-300        | 15       | 3.63%   |
| 101-110        | 11       | 2.66%   |
| 501-1000       | 11       | 2.66%   |
| 131-140        | 3        | 0.73%   |
| 111-120        | 3        | 0.73%   |
| 81-90          | 1        | 0.24%   |
| 121-130        | 1        | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 265      | 66.25%  |
| 101-120 | 57       | 14.25%  |
| Unknown | 51       | 12.75%  |
| 1-50    | 17       | 4.25%   |
| 121-160 | 7        | 1.75%   |
| 161-240 | 3        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 331      | 81.33%  |
| 2     | 53       | 13.02%  |
| 0     | 17       | 4.18%   |
| 3     | 6        | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 213      | 39.74%  |
| Intel                           | 149      | 27.8%   |
| Qualcomm Atheros                | 34       | 6.34%   |
| Broadcom                        | 33       | 6.16%   |
| Nvidia                          | 18       | 3.36%   |
| Ralink Technology               | 14       | 2.61%   |
| Ralink                          | 9        | 1.68%   |
| TP-Link                         | 7        | 1.31%   |
| Broadcom Limited                | 7        | 1.31%   |
| Qualcomm Atheros Communications | 5        | 0.93%   |
| Marvell Technology Group        | 5        | 0.93%   |
| D-Link                          | 4        | 0.75%   |
| ASUSTek Computer                | 4        | 0.75%   |
| NetGear                         | 3        | 0.56%   |
| Huawei Technologies             | 3        | 0.56%   |
| Edimax Technology               | 3        | 0.56%   |
| D-Link System                   | 3        | 0.56%   |
| ASIX Electronics                | 3        | 0.56%   |
| Aquantia                        | 3        | 0.56%   |
| Xiaomi                          | 2        | 0.37%   |
| VIA Technologies                | 2        | 0.37%   |
| Linksys                         | 2        | 0.37%   |
| ZyDAS                           | 1        | 0.19%   |
| Sitecom Europe                  | 1        | 0.19%   |
| Samsung Electronics             | 1        | 0.19%   |
| QLogic                          | 1        | 0.19%   |
| Microsoft                       | 1        | 0.19%   |
| Mellanox Technologies           | 1        | 0.19%   |
| MediaTek                        | 1        | 0.19%   |
| IMC Networks                    | 1        | 0.19%   |
| Gemtek                          | 1        | 0.19%   |
| Arduino SA                      | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 178      | 30.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25       | 4.24%   |
| Intel I211 Gigabit Network Connection                             | 15       | 2.54%   |
| Nvidia MCP61 Ethernet                                             | 14       | 2.37%   |
| Intel Ethernet Connection I217-LM                                 | 14       | 2.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 1.86%   |
| Intel Ethernet Connection (2) I219-V                              | 11       | 1.86%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11       | 1.86%   |
| Intel Wi-Fi 6 AX200                                               | 10       | 1.69%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 1.53%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 1.36%   |
| Intel Ethernet Connection I217-V                                  | 8        | 1.36%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 1.36%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 1.19%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 7        | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 0.85%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 4        | 0.68%   |
| Intel 82578DM Gigabit Network Connection                          | 4        | 0.68%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 4        | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.51%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.51%   |
| Realtek 802.11ac NIC                                              | 3        | 0.51%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3        | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 0.51%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 3        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.34%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.34%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.34%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.34%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2        | 0.34%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.34%   |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.34%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 2        | 0.34%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 2        | 0.34%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.34%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2        | 0.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2        | 0.34%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 2        | 0.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.34%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2        | 0.34%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2        | 0.34%   |
| Intel Wireless-AC 9260                                            | 2        | 0.34%   |
| Intel Wireless 7265                                               | 2        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 34       | 24.46%  |
| Intel                           | 27       | 19.42%  |
| Qualcomm Atheros                | 18       | 12.95%  |
| Ralink Technology               | 14       | 10.07%  |
| Ralink                          | 9        | 6.47%   |
| TP-Link                         | 7        | 5.04%   |
| Qualcomm Atheros Communications | 5        | 3.6%    |
| ASUSTek Computer                | 4        | 2.88%   |
| NetGear                         | 3        | 2.16%   |
| Edimax Technology               | 3        | 2.16%   |
| D-Link                          | 3        | 2.16%   |
| Broadcom                        | 3        | 2.16%   |
| Linksys                         | 2        | 1.44%   |
| ZyDAS                           | 1        | 0.72%   |
| Xiaomi                          | 1        | 0.72%   |
| Sitecom Europe                  | 1        | 0.72%   |
| Microsoft                       | 1        | 0.72%   |
| MediaTek                        | 1        | 0.72%   |
| IMC Networks                    | 1        | 0.72%   |
| Gemtek                          | 1        | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 10       | 7.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 6        | 4.29%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 5        | 3.57%   |
| Ralink MT7601U Wireless Adapter                                                       | 4        | 2.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 3        | 2.14%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 3        | 2.14%   |
| Realtek 802.11ac NIC                                                                  | 3        | 2.14%   |
| Ralink RT5370 Wireless Adapter                                                        | 3        | 2.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                 | 3        | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3        | 2.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3        | 2.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 3        | 2.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 2        | 1.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2        | 1.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 2        | 1.43%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2        | 1.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 2        | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 2        | 1.43%   |
| Realtek RTL8187 Wireless Adapter                                                      | 2        | 1.43%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 2        | 1.43%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                  | 2        | 1.43%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 2        | 1.43%   |
| Ralink RT2561/RT61 rev B 802.11g                                                      | 2        | 1.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2        | 1.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2        | 1.43%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 2        | 1.43%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                            | 2        | 1.43%   |
| Intel Wireless-AC 9260                                                                | 2        | 1.43%   |
| Intel Wireless 7265                                                                   | 2        | 1.43%   |
| Intel Wireless 7260                                                                   | 2        | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 2        | 1.43%   |
| Edimax 802.11n WLAN Adapter                                                           | 2        | 1.43%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]                    | 2        | 1.43%   |
| ZyDAS ZD1211B 802.11g                                                                 | 1        | 0.71%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                                     | 1        | 0.71%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                 | 1        | 0.71%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                 | 1        | 0.71%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                 | 1        | 0.71%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                             | 1        | 0.71%   |
| TP-Link 802.11n NIC                                                                   | 1        | 0.71%   |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.71%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                   | 1        | 0.71%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1        | 0.71%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1        | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1        | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 0.71%   |
| Realtek 802.11n NIC                                                                   | 1        | 0.71%   |
| Ralink RT5572 Wireless Adapter                                                        | 1        | 0.71%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                     | 1        | 0.71%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                  | 1        | 0.71%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1        | 0.71%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                  | 1        | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1        | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1        | 0.71%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 0.71%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]        | 1        | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 199      | 46.39%  |
| Intel                    | 135      | 31.47%  |
| Broadcom                 | 30       | 6.99%   |
| Nvidia                   | 18       | 4.2%    |
| Qualcomm Atheros         | 17       | 3.96%   |
| Broadcom Limited         | 7        | 1.63%   |
| Marvell Technology Group | 5        | 1.17%   |
| D-Link System            | 3        | 0.7%    |
| ASIX Electronics         | 3        | 0.7%    |
| Aquantia                 | 3        | 0.7%    |
| VIA Technologies         | 2        | 0.47%   |
| Huawei Technologies      | 2        | 0.47%   |
| Xiaomi                   | 1        | 0.23%   |
| Samsung Electronics      | 1        | 0.23%   |
| QLogic                   | 1        | 0.23%   |
| Mellanox Technologies    | 1        | 0.23%   |
| D-Link                   | 1        | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 178      | 39.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25       | 5.61%   |
| Intel I211 Gigabit Network Connection                             | 15       | 3.36%   |
| Nvidia MCP61 Ethernet                                             | 14       | 3.14%   |
| Intel Ethernet Connection I217-LM                                 | 14       | 3.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 2.47%   |
| Intel Ethernet Connection (2) I219-V                              | 11       | 2.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11       | 2.47%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 2.02%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 1.79%   |
| Intel Ethernet Connection I217-V                                  | 8        | 1.79%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 1.79%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 1.57%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 7        | 1.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.9%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 4        | 0.9%    |
| Intel 82578DM Gigabit Network Connection                          | 4        | 0.9%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 4        | 0.9%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.67%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.67%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 3        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.67%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.67%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.45%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2        | 0.45%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 0.45%   |
| Intel I350 Gigabit Network Connection                             | 2        | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.45%   |
| Intel 82567V-4 Gigabit Network Connection                         | 2        | 0.45%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.45%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.45%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 2        | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.22%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.22%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.22%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.22%   |
| QLogic ISP4022-based Ethernet NIC                                 | 1        | 0.22%   |
| Nvidia MCP79 Ethernet                                             | 1        | 0.22%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.22%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.22%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.22%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1        | 0.22%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.22%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.22%   |
| Marvell Group 88E8052 PCI-E ASF Gigabit Ethernet Controller       | 1        | 0.22%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.22%   |
| Intel PRO/100 VE Network Connection                               | 1        | 0.22%   |
| Intel Ethernet Connection (6) I219-LM                             | 1        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 402      | 74.72%  |
| WiFi     | 132      | 24.54%  |
| Modem    | 2        | 0.37%   |
| Unknown  | 2        | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 348      | 78.03%  |
| WiFi     | 98       | 21.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 303      | 73.9%   |
| 2     | 89       | 21.71%  |
| 3     | 10       | 2.44%   |
| 4     | 3        | 0.73%   |
| 0     | 3        | 0.73%   |
| 6     | 1        | 0.24%   |
| 5     | 1        | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 377      | 92.18%  |
| Yes  | 32       | 7.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 29       | 35.37%  |
| Intel                           | 25       | 30.49%  |
| Broadcom                        | 11       | 13.41%  |
| ASUSTek Computer                | 5        | 6.1%    |
| Realtek Semiconductor           | 3        | 3.66%   |
| Qualcomm Atheros Communications | 3        | 3.66%   |
| IMC Networks                    | 2        | 2.44%   |
| TRENDnet                        | 1        | 1.22%   |
| Lite-On Technology              | 1        | 1.22%   |
| Integrated System Solution      | 1        | 1.22%   |
| Belkin Components               | 1        | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 29       | 35.37%  |
| Intel AX200 Bluetooth                                  | 10       | 12.2%   |
| Broadcom BCM20702A0 Bluetooth 4.0                      | 6        | 7.32%   |
| Intel Bluetooth wireless interface                     | 5        | 6.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 4        | 4.88%   |
| Intel Wireless-AC 3168 Bluetooth                       | 3        | 3.66%   |
| Realtek Bluetooth Radio                                | 2        | 2.44%   |
| Qualcomm Atheros AR3011 Bluetooth                      | 2        | 2.44%   |
| Broadcom Bluetooth 3.0 Device                          | 2        | 2.44%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter       | 2        | 2.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                     | 2        | 2.44%   |
| TRENDnet TBW-108UB USB Adapter                         | 1        | 1.22%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1        | 1.22%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)        | 1        | 1.22%   |
| Lite-On Bluetooth Device                               | 1        | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 1        | 1.22%   |
| Intel Bluetooth Device                                 | 1        | 1.22%   |
| Intel AX210 Bluetooth                                  | 1        | 1.22%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter  | 1        | 1.22%   |
| IMC Networks Bluetooth Radio                           | 1        | 1.22%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1        | 1.22%   |
| Broadcom BCM2045 Bluetooth                             | 1        | 1.22%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter  | 1        | 1.22%   |
| ASUS Bluetooth Radio                                   | 1        | 1.22%   |
| ASUS Bluetooth Device                                  | 1        | 1.22%   |
| ASUS ASUS USB-BT500                                    | 1        | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 269      | 42.83%  |
| Nvidia                               | 145      | 23.09%  |
| AMD                                  | 145      | 23.09%  |
| C-Media Electronics                  | 15       | 2.39%   |
| Creative Labs                        | 9        | 1.43%   |
| Logitech                             | 4        | 0.64%   |
| JMTek                                | 4        | 0.64%   |
| Razer USA                            | 3        | 0.48%   |
| Corsair                              | 3        | 0.48%   |
| ASUSTek Computer                     | 3        | 0.48%   |
| VIA Technologies                     | 2        | 0.32%   |
| Tenx Technology                      | 2        | 0.32%   |
| Plantronics                          | 2        | 0.32%   |
| Kingston Technology                  | 2        | 0.32%   |
| Hewlett-Packard                      | 2        | 0.32%   |
| GN Netcom                            | 2        | 0.32%   |
| Generalplus Technology               | 2        | 0.32%   |
| Creative Technology                  | 2        | 0.32%   |
| XMOS                                 | 1        | 0.16%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.16%   |
| Sony                                 | 1        | 0.16%   |
| Micro Star International             | 1        | 0.16%   |
| Giga-Byte Technology                 | 1        | 0.16%   |
| Focusrite-Novation                   | 1        | 0.16%   |
| Ensoniq                              | 1        | 0.16%   |
| Dell                                 | 1        | 0.16%   |
| D&M Holdings (Denon/Marantz)         | 1        | 0.16%   |
| Blue Microphones                     | 1        | 0.16%   |
| BEHRINGER International              | 1        | 0.16%   |
| Alesis                               | 1        | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 45       | 6.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 41       | 5.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 38       | 5.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 36       | 4.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 33       | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 24       | 3.31%   |
| AMD Starship/Matisse HD Audio Controller                                          | 22       | 3.03%   |
| Nvidia High Definition Audio Controller                                           | 16       | 2.2%    |
| AMD Family 17h/19h HD Audio Controller                                            | 16       | 2.2%    |
| Nvidia MCP61 High Definition Audio                                                | 15       | 2.07%   |
| Intel 200 Series PCH HD Audio                                                     | 15       | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                        | 14       | 1.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 14       | 1.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 13       | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 12       | 1.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 12       | 1.65%   |
| Nvidia GP108 High Definition Audio Controller                                     | 11       | 1.52%   |
| Nvidia GK107 HDMI Audio Controller                                                | 11       | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 11       | 1.52%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 10       | 1.38%   |
| AMD FCH Azalia Controller                                                         | 10       | 1.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 1.38%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 10       | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9        | 1.24%   |
| Nvidia GP104 High Definition Audio Controller                                     | 9        | 1.24%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 9        | 1.24%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 1.24%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 8        | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 1.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 8        | 1.1%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 8        | 1.1%    |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                                 | 7        | 0.96%   |
| Nvidia GK104 HDMI Audio Controller                                                | 6        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6        | 0.83%   |
| Nvidia GF106 High Definition Audio Controller                                     | 6        | 0.83%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 6        | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5        | 0.69%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 5        | 0.69%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 0.55%   |
| Nvidia TU104 HD Audio Controller                                                  | 4        | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 0.55%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4        | 0.55%   |
| Intel Comet Lake PCH-V cAVS                                                       | 4        | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 4        | 0.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4        | 0.55%   |
| Nvidia MCP79 High Definition Audio                                                | 3        | 0.41%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.41%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 0.41%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3        | 0.41%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 0.41%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 0.41%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                  | 3        | 0.41%   |
| C-Media Electronics CM8888 [Oxygen Express]                                       | 3        | 0.41%   |
| AMD Trinity HDMI Audio Controller                                                 | 3        | 0.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 0.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 0.41%   |
| AMD Navi 10 HDMI Audio                                                            | 3        | 0.41%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 3        | 0.41%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 2        | 0.28%   |
| Tenx Technology USB AUDIO                                                         | 2        | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 59       | 22.69%  |
| Kingston                   | 51       | 19.62%  |
| Corsair                    | 26       | 10%     |
| Samsung Electronics        | 23       | 8.85%   |
| SK Hynix                   | 20       | 7.69%   |
| Crucial                    | 19       | 7.31%   |
| G.Skill                    | 18       | 6.92%   |
| Team                       | 5        | 1.92%   |
| Micron Technology          | 5        | 1.92%   |
| Smart                      | 4        | 1.54%   |
| Nanya Technology           | 4        | 1.54%   |
| Elpida                     | 4        | 1.54%   |
| Patriot                    | 3        | 1.15%   |
| Teikon                     | 2        | 0.77%   |
| Silicon Power              | 2        | 0.77%   |
| Qimonda                    | 2        | 0.77%   |
| HBS                        | 2        | 0.77%   |
| A-DATA Technology          | 2        | 0.77%   |
| Unknown (00FFFFFFFFFFFFFF) | 1        | 0.38%   |
| Transcend                  | 1        | 0.38%   |
| Ramaxel Technology         | 1        | 0.38%   |
| Kreton                     | 1        | 0.38%   |
| Goldenmars                 | 1        | 0.38%   |
| Golden Empire              | 1        | 0.38%   |
| GeIL                       | 1        | 0.38%   |
| atermiter                  | 1        | 0.38%   |
| Unknown                    | 1        | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1333MT/s                                   | 5        | 1.81%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                             | 5        | 1.81%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                               | 4        | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                                | 4        | 1.45%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                              | 4        | 1.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                              | 3        | 1.09%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                      | 3        | 1.09%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s                       | 3        | 1.09%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s                    | 3        | 1.09%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s                     | 3        | 1.09%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                                    | 2        | 0.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                      | 2        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s                              | 2        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                               | 2        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                                | 2        | 0.72%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                                    | 2        | 0.72%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                   | 2        | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s                                | 2        | 0.72%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s                     | 2        | 0.72%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4096MB DIMM DDR3 1600MT/s                   | 2        | 0.72%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                       | 2        | 0.72%   |
| Qimonda RAM 64T128020EU2.5B2 1GB DIMM DDR2 800MT/s                        | 2        | 0.72%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                         | 2        | 0.72%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s                  | 2        | 0.72%   |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s                  | 2        | 0.72%   |
| Elpida RAM EBJ41EF8BCFA-DJ-F 4096MB DIMM DDR3 1333MT/s                    | 2        | 0.72%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s                      | 2        | 0.72%   |
| Corsair RAM CMK32GX4M2E3200C16 16384MB DIMM DDR4 3200MT/s                 | 2        | 0.72%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s                    | 2        | 0.72%   |
| Unknown RAM Module 8192MB DIMM SDRAM                                      | 1        | 0.36%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                              | 1        | 0.36%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                                    | 1        | 0.36%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                                   | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                      | 1        | 0.36%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                      | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1066MT/s                             | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM SDRAM                                      | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                               | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                              | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR2 266MT/s                               | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                                    | 1        | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                   | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                  | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                                      | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                              | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                               | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 1067MT/s                              | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                               | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                    | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                    | 1        | 0.36%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                                   | 1        | 0.36%   |
| Unknown RAM Module 1GB DIMM SDRAM                                         | 1        | 0.36%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s                               | 1        | 0.36%   |
| Unknown RAM CS4S2666D19321C 32GB SODIMM DDR4 2667MT/s                     | 1        | 0.36%   |
| Unknown RAM CL5-5-5 DDR2-800 2048MB DIMM SDRAM 2048MT/s                   | 1        | 0.36%   |
| Unknown RAM 3634543235363032304555322E3543322020 2048MB DIMM DDR2 800MT/s | 1        | 0.36%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                     | 1        | 0.36%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s                     | 1        | 0.36%   |
| Unknown (00FFFFFFFFFFFFFF) RAM 864AY-667D4 2048MB DIMM DDR2 667MT/s       | 1        | 0.36%   |
| Transcend RAM JM667QLU-2G 2048MB DIMM DDR2 667MT/s                        | 1        | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 91       | 39.22%  |
| DDR4    | 70       | 30.17%  |
| DDR2    | 26       | 11.21%  |
| Unknown | 18       | 7.76%   |
| SDRAM   | 15       | 6.47%   |
| DDR     | 10       | 4.31%   |
| LPDDR3  | 1        | 0.43%   |
| DRAM    | 1        | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 220      | 97.35%  |
| SODIMM       | 5        | 2.21%   |
| Row Of Chips | 1        | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 69       | 28.28%  |
| 8192  | 64       | 26.23%  |
| 2048  | 57       | 23.36%  |
| 16384 | 29       | 11.89%  |
| 1024  | 13       | 5.33%   |
| 32768 | 10       | 4.1%    |
| 512   | 1        | 0.41%   |
| 32    | 1        | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 47       | 19.26%  |
| 1600    | 43       | 17.62%  |
| 3200    | 22       | 9.02%   |
| 800     | 19       | 7.79%   |
| 2400    | 18       | 7.38%   |
| 667     | 14       | 5.74%   |
| 2667    | 10       | 4.1%    |
| 533     | 7        | 2.87%   |
| Unknown | 7        | 2.87%   |
| 2133    | 5        | 2.05%   |
| 1867    | 5        | 2.05%   |
| 3600    | 4        | 1.64%   |
| 2933    | 4        | 1.64%   |
| 2666    | 4        | 1.64%   |
| 3400    | 3        | 1.23%   |
| 1067    | 3        | 1.23%   |
| 400     | 3        | 1.23%   |
| 266     | 3        | 1.23%   |
| 49926   | 2        | 0.82%   |
| 3733    | 2        | 0.82%   |
| 3500    | 2        | 0.82%   |
| 2048    | 2        | 0.82%   |
| 1400    | 2        | 0.82%   |
| 1066    | 2        | 0.82%   |
| 3866    | 1        | 0.41%   |
| 3466    | 1        | 0.41%   |
| 3333    | 1        | 0.41%   |
| 3100    | 1        | 0.41%   |
| 3000    | 1        | 0.41%   |
| 2800    | 1        | 0.41%   |
| 2473    | 1        | 0.41%   |
| 2187    | 1        | 0.41%   |
| 1866    | 1        | 0.41%   |
| 1648    | 1        | 0.41%   |
| 333     | 1        | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 12       | 35.29%  |
| Seiko Epson            | 4        | 11.76%  |
| Samsung Electronics    | 4        | 11.76%  |
| Canon                  | 4        | 11.76%  |
| Brother Industries     | 4        | 11.76%  |
| QinHeng Electronics    | 1        | 2.94%   |
| Prolific Technology    | 1        | 2.94%   |
| Panasonic (Matsushita) | 1        | 2.94%   |
| Lexmark International  | 1        | 2.94%   |
| Dymo-CoStar            | 1        | 2.94%   |
| Bixolon                | 1        | 2.94%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Seiko Epson Printer                        | 2        | 5.71%   |
| Samsung SCX-4200 series                    | 2        | 5.71%   |
| Samsung M2020 Series                       | 2        | 5.71%   |
| HP LaserJet Professional P 1102w           | 2        | 5.71%   |
| Brother Printer                            | 2        | 5.71%   |
| Seiko Epson WF-2010 Series                 | 1        | 2.86%   |
| Seiko Epson L312 Series                    | 1        | 2.86%   |
| QinHeng CH340S                             | 1        | 2.86%   |
| Prolific PL2305 Parallel Port              | 1        | 2.86%   |
| Panasonic (Matsushita) KX-MB2130RU         | 1        | 2.86%   |
| Lexmark International InkJet Color Printer | 1        | 2.86%   |
| HP OfficeJet 6950                          | 1        | 2.86%   |
| HP Officejet 4500 G510a-f                  | 1        | 2.86%   |
| HP LaserJet 1022                           | 1        | 2.86%   |
| HP LaserJet 1020                           | 1        | 2.86%   |
| HP Deskjet F4500 series                    | 1        | 2.86%   |
| HP DeskJet F300 series                     | 1        | 2.86%   |
| HP Deskjet 3050 J610 series                | 1        | 2.86%   |
| HP DeskJet 2700 series                     | 1        | 2.86%   |
| HP DeskJet 2130 series                     | 1        | 2.86%   |
| HP color LaserJet 4650                     | 1        | 2.86%   |
| Dymo-CoStar DYMO LabelWriter 320           | 1        | 2.86%   |
| Canon Pixma iP4500 Printer                 | 1        | 2.86%   |
| Canon LiDE 400                             | 1        | 2.86%   |
| Canon LBP7010C/7018C                       | 1        | 2.86%   |
| Canon LaserShot LBP-1120 Printer           | 1        | 2.86%   |
| Brother HL-3170CDW series                  | 1        | 2.86%   |
| Brother HL-1440 Laser Printer              | 1        | 2.86%   |
| Brother DCP-L2540DW                        | 1        | 2.86%   |
| Bixolon Printer                            | 1        | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 4        | 66.67%  |
| Hewlett-Packard             | 1        | 16.67%  |
| Acer Peripherals (now BenQ) | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| HP ScanJet 4370                             | 1        | 16.67%  |
| Canon CanoScan N1240U/LiDE 30               | 1        | 16.67%  |
| Canon CanoScan LIDE 25                      | 1        | 16.67%  |
| Canon CanoScan LiDE 210                     | 1        | 16.67%  |
| Canon CanoScan LiDE 110                     | 1        | 16.67%  |
| Acer Peripherals (now BenQ) S2W 3300U/4300U | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 23       | 38.98%  |
| Microdia                      | 6        | 10.17%  |
| Creative Technology           | 3        | 5.08%   |
| Z-Star Microelectronics       | 2        | 3.39%   |
| Samsung Electronics           | 2        | 3.39%   |
| Microsoft                     | 2        | 3.39%   |
| KYE Systems (Mouse Systems)   | 2        | 3.39%   |
| IMC Networks                  | 2        | 3.39%   |
| Chicony Electronics           | 2        | 3.39%   |
| ARC International             | 2        | 3.39%   |
| Apple                         | 2        | 3.39%   |
| Unknown                       | 1        | 1.69%   |
| Sweex                         | 1        | 1.69%   |
| Sunplus Innovation Technology | 1        | 1.69%   |
| Novatel Wireless              | 1        | 1.69%   |
| Jieli Technology              | 1        | 1.69%   |
| Generalplus Technology        | 1        | 1.69%   |
| GEMBIRD                       | 1        | 1.69%   |
| eMPIA Technology              | 1        | 1.69%   |
| Cubeternet                    | 1        | 1.69%   |
| Canon                         | 1        | 1.69%   |
| Aveo Technology               | 1        | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 7        | 11.48%  |
| Logitech HD Pro Webcam C920                       | 3        | 4.92%   |
| Samsung Galaxy A5 (MTP)                           | 2        | 3.28%   |
| Logitech Webcam C925e                             | 2        | 3.28%   |
| Logitech Webcam C170                              | 2        | 3.28%   |
| ARC International Camera                          | 2        | 3.28%   |
| Apple iPhone 5/5C/5S/6/SE                         | 2        | 3.28%   |
| Z-Star Venus USB2.0 Camera                        | 1        | 1.64%   |
| Z-Star Sirius USB2.0 Camera                       | 1        | 1.64%   |
| Sweex WC060 Series HD Webcam                      | 1        | 1.64%   |
| Sunplus FHD Camera Microphone                     | 1        | 1.64%   |
| Novatel Wireless Merlin U740 (non-Vodafone)       | 1        | 1.64%   |
| Microsoft LifeCam VX-2000                         | 1        | 1.64%   |
| Microsoft LifeCam HD-3000                         | 1        | 1.64%   |
| Microdia Webcam Vitade AF                         | 1        | 1.64%   |
| Microdia JOYACCESS JA-Webcam                      | 1        | 1.64%   |
| Microdia Integrated Camera                        | 1        | 1.64%   |
| Microdia Defender G-Lens 2577 HD720p Camera       | 1        | 1.64%   |
| Microdia Camera                                   | 1        | 1.64%   |
| Microdia AUKEY PC-W1                              | 1        | 1.64%   |
| Logitech Webcam C930e                             | 1        | 1.64%   |
| Logitech Webcam C250                              | 1        | 1.64%   |
| Logitech QuickCam Pro for Notebooks               | 1        | 1.64%   |
| Logitech QuickCam Pro 9000                        | 1        | 1.64%   |
| Logitech QuickCam E 3500                          | 1        | 1.64%   |
| Logitech QuickCam Deluxe for Notebooks            | 1        | 1.64%   |
| Logitech HD Webcam C525                           | 1        | 1.64%   |
| Logitech HD Webcam C510                           | 1        | 1.64%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 1.64%   |
| Logitech BRIO                                     | 1        | 1.64%   |
| KYE Systems (Mouse Systems) iLook 320             | 1        | 1.64%   |
| KYE Systems (Mouse Systems) Genius iSlim 330      | 1        | 1.64%   |
| KYE Systems (Mouse Systems) FaceCam 311           | 1        | 1.64%   |
| Jieli USB PHY 2.0                                 | 1        | 1.64%   |
| IMC Networks XHC Camera                           | 1        | 1.64%   |
| IMC Networks USB 2.0 Camera                       | 1        | 1.64%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 1        | 1.64%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 1.64%   |
| eMPIA M035 Compact Web Cam                        | 1        | 1.64%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 1        | 1.64%   |
| Creative Webcam Live! Effects                     | 1        | 1.64%   |
| Creative Live! Cam Video IM Pro                   | 1        | 1.64%   |
| Creative Live! Cam Chat HD [VF0700]               | 1        | 1.64%   |
| Chicony HP High Definition 1MP Webcam             | 1        | 1.64%   |
| Chicony Gateway Webcam                            | 1        | 1.64%   |
| Canon Powershot ELPH 135 / IXUS 145               | 1        | 1.64%   |
| Aveo UVC camera (Bresser microscope)              | 1        | 1.64%   |
| Unknown                                           | 1        | 1.64%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 16.67%  |
| Kobil Systems         | 1        | 16.67%  |
| Gemalto (was Gemplus) | 1        | 16.67%  |
| Chicony Electronics   | 1        | 16.67%  |
| Alcor Micro           | 1        | 16.67%  |
| Advanced Card Systems | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface    | 1        | 16.67%  |
| Kobil Systems Smart Token                            | 1        | 16.67%  |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader     | 1        | 16.67%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                  | 1        | 16.67%  |
| Advanced Card Systems ACR122U                        | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 361      | 88.05%  |
| 1     | 42       | 10.24%  |
| 2     | 6        | 1.46%   |
| 5     | 1        | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 19       | 35.85%  |
| Net/wireless             | 7        | 13.21%  |
| Communication controller | 6        | 11.32%  |
| Multimedia controller    | 4        | 7.55%   |
| Chipcard                 | 4        | 7.55%   |
| Unassigned class         | 3        | 5.66%   |
| Sound                    | 3        | 5.66%   |
| Tv card                  | 1        | 1.89%   |
| Storage/ata              | 1        | 1.89%   |
| Network                  | 1        | 1.89%   |
| Modem                    | 1        | 1.89%   |
| Card reader              | 1        | 1.89%   |
| Camera                   | 1        | 1.89%   |
| Bluetooth                | 1        | 1.89%   |

