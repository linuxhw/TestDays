Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 7618

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | DH61BR G32662-203           | [06cb46d18c](https://linux-hardware.org/?probe=06cb46d18c) | Feb 02, 2024 |
| Unknown       | DH61BR G32662-203           | [7496b90e09](https://linux-hardware.org/?probe=7496b90e09) | Feb 02, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | [4bcae97baa](https://linux-hardware.org/?probe=4bcae97baa) | Feb 02, 2024 |
| Apple         | Mac-F221BEC8                | [7e71a3a029](https://linux-hardware.org/?probe=7e71a3a029) | Feb 02, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [97d6952c52](https://linux-hardware.org/?probe=97d6952c52) | Feb 02, 2024 |
| HP            | 859C                        | [bc1cc805c6](https://linux-hardware.org/?probe=bc1cc805c6) | Feb 02, 2024 |
| ASRock        | X300-ITX                    | [3390b15018](https://linux-hardware.org/?probe=3390b15018) | Feb 02, 2024 |
| Dell          | 05XGC8 A01                  | [29ae38936a](https://linux-hardware.org/?probe=29ae38936a) | Feb 02, 2024 |
| Fujitsu       | D3523-Ax S26361-D3523-Ax    | [fefabce2b4](https://linux-hardware.org/?probe=fefabce2b4) | Feb 02, 2024 |
| HP            | 158A                        | [1ec6b139ac](https://linux-hardware.org/?probe=1ec6b139ac) | Feb 02, 2024 |
| Dell          | 0T568R A00                  | [4ce5e16aa2](https://linux-hardware.org/?probe=4ce5e16aa2) | Feb 01, 2024 |
| Dell          | 0TDG4V A01                  | [d921cc13e3](https://linux-hardware.org/?probe=d921cc13e3) | Feb 01, 2024 |
| EBN           | MA1N                        | [302ea43954](https://linux-hardware.org/?probe=302ea43954) | Feb 01, 2024 |
| Dell          | 09KPNV A01                  | [b6ba043767](https://linux-hardware.org/?probe=b6ba043767) | Feb 01, 2024 |
| Gigabyte      | B760M GAMING X DDR4         | [855d31073a](https://linux-hardware.org/?probe=855d31073a) | Feb 01, 2024 |
| MSI           | B550-A PRO                  | [c211b49a95](https://linux-hardware.org/?probe=c211b49a95) | Feb 01, 2024 |
| HP            | 8598                        | [cc6faa2bfa](https://linux-hardware.org/?probe=cc6faa2bfa) | Feb 01, 2024 |
| MSI           | Z370-A PRO                  | [d012afeb56](https://linux-hardware.org/?probe=d012afeb56) | Feb 01, 2024 |
| HC Technol... | HCAR5000-MI                 | [f6051e0b06](https://linux-hardware.org/?probe=f6051e0b06) | Feb 01, 2024 |
| ASUSTek       | PRIME B760-PLUS D4          | [d9355c6146](https://linux-hardware.org/?probe=d9355c6146) | Feb 01, 2024 |
| Foxconn       | 9657MA                      | [6b2e0b2ae9](https://linux-hardware.org/?probe=6b2e0b2ae9) | Jan 31, 2024 |
| Supermicro    | X10DRU-i+A                  | [f2881b94b0](https://linux-hardware.org/?probe=f2881b94b0) | Jan 31, 2024 |
| Gigabyte      | B560M DS3H AC               | [81a39a795c](https://linux-hardware.org/?probe=81a39a795c) | Jan 31, 2024 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [2360c2cf38](https://linux-hardware.org/?probe=2360c2cf38) | Jan 31, 2024 |
| Intel         | DG41AN AAE92991-401         | [5e520c92ca](https://linux-hardware.org/?probe=5e520c92ca) | Jan 31, 2024 |
| MSI           | B550-A PRO                  | [85c2cd9371](https://linux-hardware.org/?probe=85c2cd9371) | Jan 31, 2024 |
| ASUSTek       | PRO H410M-C                 | [ab001c7490](https://linux-hardware.org/?probe=ab001c7490) | Jan 31, 2024 |
| Dell          | 02K9CR A01                  | [72df486f35](https://linux-hardware.org/?probe=72df486f35) | Jan 31, 2024 |
| Dell          | 0T568R A00                  | [56936b64ba](https://linux-hardware.org/?probe=56936b64ba) | Jan 30, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [c737ef78e9](https://linux-hardware.org/?probe=c737ef78e9) | Jan 30, 2024 |
| Unknown       | Unknown                     | [6928c8eb05](https://linux-hardware.org/?probe=6928c8eb05) | Jan 30, 2024 |
| MSI           | X99A SLI PLUS               | [216026fc45](https://linux-hardware.org/?probe=216026fc45) | Jan 30, 2024 |
| Gigabyte      | H55M-S2HP                   | [a1a4140c7e](https://linux-hardware.org/?probe=a1a4140c7e) | Jan 30, 2024 |
| Unknown       | Unknown                     | [a4eb1c6dda](https://linux-hardware.org/?probe=a4eb1c6dda) | Jan 30, 2024 |
| Unknown       | Unknown                     | [f8b5f64c1e](https://linux-hardware.org/?probe=f8b5f64c1e) | Jan 30, 2024 |
| HP            | 894D                        | [851e68057d](https://linux-hardware.org/?probe=851e68057d) | Jan 30, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [c2ff3b6e2f](https://linux-hardware.org/?probe=c2ff3b6e2f) | Jan 30, 2024 |
| Dell          | 0TDG4V A01                  | [240d51778b](https://linux-hardware.org/?probe=240d51778b) | Jan 30, 2024 |
| Intel         | X99 V1.0                    | [202a9720c4](https://linux-hardware.org/?probe=202a9720c4) | Jan 30, 2024 |
| Medion        | B250H4-EM                   | [418b44d0a2](https://linux-hardware.org/?probe=418b44d0a2) | Jan 29, 2024 |
| Pegatron      | Benicia                     | [b127dc2bc0](https://linux-hardware.org/?probe=b127dc2bc0) | Jan 29, 2024 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [21628b2a5b](https://linux-hardware.org/?probe=21628b2a5b) | Jan 29, 2024 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [26ae99cfe2](https://linux-hardware.org/?probe=26ae99cfe2) | Jan 29, 2024 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [856669283d](https://linux-hardware.org/?probe=856669283d) | Jan 29, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [009120e99a](https://linux-hardware.org/?probe=009120e99a) | Jan 29, 2024 |
| Gigabyte      | Z77X-D3H                    | [aa69326408](https://linux-hardware.org/?probe=aa69326408) | Jan 29, 2024 |
| ASUSTek       | G10DK                       | [f5632504cc](https://linux-hardware.org/?probe=f5632504cc) | Jan 29, 2024 |
| ASUSTek       | G10DK                       | [5ef0067e13](https://linux-hardware.org/?probe=5ef0067e13) | Jan 29, 2024 |
| Unknown       | HX90                        | [2d0982fbb6](https://linux-hardware.org/?probe=2d0982fbb6) | Jan 29, 2024 |
| Dell          | 0C2KJT A00                  | [bc76ac497b](https://linux-hardware.org/?probe=bc76ac497b) | Jan 29, 2024 |
| Dell          | 0C2KJT A00                  | [b56c82b709](https://linux-hardware.org/?probe=b56c82b709) | Jan 29, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [29fcd258c7](https://linux-hardware.org/?probe=29fcd258c7) | Jan 28, 2024 |
| Biostar       | B550MH                      | [18a98ffa2c](https://linux-hardware.org/?probe=18a98ffa2c) | Jan 28, 2024 |
| Biostar       | B550MH                      | [7e52e1855c](https://linux-hardware.org/?probe=7e52e1855c) | Jan 28, 2024 |
| Unknown       | Unknown                     | [e80d32ade5](https://linux-hardware.org/?probe=e80d32ade5) | Jan 28, 2024 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [0aa2140ac2](https://linux-hardware.org/?probe=0aa2140ac2) | Jan 28, 2024 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [752e2156f6](https://linux-hardware.org/?probe=752e2156f6) | Jan 28, 2024 |
| HP            | 82F2 A01                    | [017f111720](https://linux-hardware.org/?probe=017f111720) | Jan 28, 2024 |
| ASUSTek       | PRIME H510M-E               | [f8f08ce899](https://linux-hardware.org/?probe=f8f08ce899) | Jan 28, 2024 |
| ASRock        | FM2A75M Pro4+               | [d3d40bf0b4](https://linux-hardware.org/?probe=d3d40bf0b4) | Jan 28, 2024 |
| ASUSTek       | P5Q SE2                     | [5aa0059c3f](https://linux-hardware.org/?probe=5aa0059c3f) | Jan 28, 2024 |
| Dell          | 0D24M8 A01                  | [db11402dbf](https://linux-hardware.org/?probe=db11402dbf) | Jan 28, 2024 |
| Medion        | D3F3-EM                     | [b49f3c529a](https://linux-hardware.org/?probe=b49f3c529a) | Jan 28, 2024 |
| ASUSTek       | PRIME A320M-K               | [3d0d9dce8a](https://linux-hardware.org/?probe=3d0d9dce8a) | Jan 28, 2024 |
| ASUSTek       | P8B75-M                     | [ad1a5f6757](https://linux-hardware.org/?probe=ad1a5f6757) | Jan 28, 2024 |
| Dell          | 0VHWTR A02                  | [a40f7ff2de](https://linux-hardware.org/?probe=a40f7ff2de) | Jan 27, 2024 |
| ABIT          | AB9/AB9RPO                  | [01c28bcaa5](https://linux-hardware.org/?probe=01c28bcaa5) | Jan 27, 2024 |
| Apple         | Mac-F221BEC8                | [9fb7827c5f](https://linux-hardware.org/?probe=9fb7827c5f) | Jan 27, 2024 |
| Gigabyte      | B450 AORUS M                | [03351f8523](https://linux-hardware.org/?probe=03351f8523) | Jan 27, 2024 |
| MSI           | A320M GRENADE               | [0a605bfdee](https://linux-hardware.org/?probe=0a605bfdee) | Jan 27, 2024 |
| Gigabyte      | B450M DS3H-CF               | [a6b046b2b7](https://linux-hardware.org/?probe=a6b046b2b7) | Jan 27, 2024 |
| ASUSTek       | PRIME B450M-K II            | [46b23b4469](https://linux-hardware.org/?probe=46b23b4469) | Jan 27, 2024 |
| ASUSTek       | NODUSM3                     | [b7a885758d](https://linux-hardware.org/?probe=b7a885758d) | Jan 27, 2024 |
| JGINYUE       | H97M-VH V2.1                | [f4baebb6b0](https://linux-hardware.org/?probe=f4baebb6b0) | Jan 27, 2024 |
| JGINYUE       | H97M-VH V2.1                | [7983ca3c2d](https://linux-hardware.org/?probe=7983ca3c2d) | Jan 27, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [9eeddc4566](https://linux-hardware.org/?probe=9eeddc4566) | Jan 27, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [fe40514847](https://linux-hardware.org/?probe=fe40514847) | Jan 27, 2024 |
| Gigabyte      | B450M DS3H-CF               | [95541e0847](https://linux-hardware.org/?probe=95541e0847) | Jan 27, 2024 |
| ECS           | APLD-MINI                   | [51b4a0993d](https://linux-hardware.org/?probe=51b4a0993d) | Jan 26, 2024 |
| Gigabyte      | B450M S2H                   | [b010be0d2f](https://linux-hardware.org/?probe=b010be0d2f) | Jan 26, 2024 |
| MSI           | B250M BAZOOKA               | [0bd7085870](https://linux-hardware.org/?probe=0bd7085870) | Jan 26, 2024 |
| HP            | 1998                        | [b1431c9048](https://linux-hardware.org/?probe=b1431c9048) | Jan 26, 2024 |
| HP            | 8719                        | [42bc597317](https://linux-hardware.org/?probe=42bc597317) | Jan 26, 2024 |
| Supermicro    | X10DDW-i                    | [6a9650896a](https://linux-hardware.org/?probe=6a9650896a) | Jan 26, 2024 |
| Lenovo        | Annapurna CRB NOK           | [5b803efc86](https://linux-hardware.org/?probe=5b803efc86) | Jan 26, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [903d800136](https://linux-hardware.org/?probe=903d800136) | Jan 26, 2024 |
| Dell          | 0C2XKD A01                  | [f32c18bab1](https://linux-hardware.org/?probe=f32c18bab1) | Jan 25, 2024 |
| Foxconn       | Cinema Series FAB           | [de1e89f80f](https://linux-hardware.org/?probe=de1e89f80f) | Jan 25, 2024 |
| ASRock        | Z77 Extreme4                | [4685f2b1e9](https://linux-hardware.org/?probe=4685f2b1e9) | Jan 25, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7b16c2c1bc](https://linux-hardware.org/?probe=7b16c2c1bc) | Jan 25, 2024 |
| Dell          | 0HHV7N A00                  | [fda3733e63](https://linux-hardware.org/?probe=fda3733e63) | Jan 25, 2024 |
| Dell          | 0PTTT9 A01                  | [310d107f7d](https://linux-hardware.org/?probe=310d107f7d) | Jan 25, 2024 |
| HP            | 2129                        | [9617c50324](https://linux-hardware.org/?probe=9617c50324) | Jan 25, 2024 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | [bbc8707e00](https://linux-hardware.org/?probe=bbc8707e00) | Jan 25, 2024 |
| ASRock        | A520M-HDV                   | [db1260e2b7](https://linux-hardware.org/?probe=db1260e2b7) | Jan 25, 2024 |
| ASRock        | B450M Pro4                  | [e44bf066a4](https://linux-hardware.org/?probe=e44bf066a4) | Jan 25, 2024 |
| MSI           | B450M MORTAR MAX            | [969d0f1bef](https://linux-hardware.org/?probe=969d0f1bef) | Jan 25, 2024 |
| GEEKOM        | Mini IT13                   | [db1f38bd8c](https://linux-hardware.org/?probe=db1f38bd8c) | Jan 25, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | [2851a608c0](https://linux-hardware.org/?probe=2851a608c0) | Jan 25, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [6c409399d4](https://linux-hardware.org/?probe=6c409399d4) | Jan 25, 2024 |
| ASRock        | H370M-HDV                   | [86e43e96f0](https://linux-hardware.org/?probe=86e43e96f0) | Jan 25, 2024 |
| Dell          | 0N4YC8 A00                  | [03750ea62c](https://linux-hardware.org/?probe=03750ea62c) | Jan 25, 2024 |
| MSI           | MEG X399 CREATION           | [b598a0fd29](https://linux-hardware.org/?probe=b598a0fd29) | Jan 25, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [f904e3ce10](https://linux-hardware.org/?probe=f904e3ce10) | Jan 24, 2024 |
| ASUSTek       | P5G41T-M LX2/GB             | [642c49982c](https://linux-hardware.org/?probe=642c49982c) | Jan 24, 2024 |
| HP            | 821D                        | [c56ee90d6b](https://linux-hardware.org/?probe=c56ee90d6b) | Jan 24, 2024 |
| ASUSTek       | M4A77T                      | [082bd06cdc](https://linux-hardware.org/?probe=082bd06cdc) | Jan 24, 2024 |
| HP            | 8053                        | [ecca7b4395](https://linux-hardware.org/?probe=ecca7b4395) | Jan 24, 2024 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | [db6de09144](https://linux-hardware.org/?probe=db6de09144) | Jan 24, 2024 |
| Dell          | 0XKH0D A02                  | [7ed5013174](https://linux-hardware.org/?probe=7ed5013174) | Jan 24, 2024 |
| MSI           | H110M PRO-VD                | [208d27435c](https://linux-hardware.org/?probe=208d27435c) | Jan 24, 2024 |
| ASUSTek       | Z97-A-USB31                 | [1fe92d4fbe](https://linux-hardware.org/?probe=1fe92d4fbe) | Jan 24, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [0d4e165d3f](https://linux-hardware.org/?probe=0d4e165d3f) | Jan 23, 2024 |
| ASUSTek       | D500SA                      | [91815478a7](https://linux-hardware.org/?probe=91815478a7) | Jan 23, 2024 |
| Dell          | 02YYK5 A01                  | [092dabd325](https://linux-hardware.org/?probe=092dabd325) | Jan 23, 2024 |
| Dell          | 06X1TJ A00                  | [5eb76b0285](https://linux-hardware.org/?probe=5eb76b0285) | Jan 23, 2024 |
| ASRock        | B450 Pro4 R2.0              | [a606bceea5](https://linux-hardware.org/?probe=a606bceea5) | Jan 23, 2024 |
| ASUSTek       | PRIME A320M-K               | [920e34bee4](https://linux-hardware.org/?probe=920e34bee4) | Jan 23, 2024 |
| ASUSTek       | Berkeley                    | [c7d349a7f0](https://linux-hardware.org/?probe=c7d349a7f0) | Jan 23, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c8dc8a63fb](https://linux-hardware.org/?probe=c8dc8a63fb) | Jan 23, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b126f7be3d](https://linux-hardware.org/?probe=b126f7be3d) | Jan 23, 2024 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [988f12d3d7](https://linux-hardware.org/?probe=988f12d3d7) | Jan 23, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [a15d748e41](https://linux-hardware.org/?probe=a15d748e41) | Jan 23, 2024 |
| AMI           | Intel                       | [5085eba8b2](https://linux-hardware.org/?probe=5085eba8b2) | Jan 23, 2024 |
| Gigabyte      | Z790 UD AX                  | [a84ee0f485](https://linux-hardware.org/?probe=a84ee0f485) | Jan 23, 2024 |
| Gigabyte      | GA-78LMT-S2P                | [615b7dc324](https://linux-hardware.org/?probe=615b7dc324) | Jan 22, 2024 |
| Foxconn       | 2AAF                        | [aa481d37c8](https://linux-hardware.org/?probe=aa481d37c8) | Jan 22, 2024 |
| ASUSTek       | PRIME B550M-A               | [ed85e4518e](https://linux-hardware.org/?probe=ed85e4518e) | Jan 22, 2024 |
| Gigabyte      | B360M DS3H                  | [d809dd5290](https://linux-hardware.org/?probe=d809dd5290) | Jan 22, 2024 |
| ASRock        | A520M-HDV                   | [34e4549f27](https://linux-hardware.org/?probe=34e4549f27) | Jan 22, 2024 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [bb111f75bd](https://linux-hardware.org/?probe=bb111f75bd) | Jan 22, 2024 |
| Gigabyte      | H310M H x.x                 | [7164188034](https://linux-hardware.org/?probe=7164188034) | Jan 22, 2024 |
| ASRock        | B450M Pro4                  | [3566eaf43c](https://linux-hardware.org/?probe=3566eaf43c) | Jan 22, 2024 |
| Gigabyte      | B550 GAMING X V2            | [0b0db0e2ef](https://linux-hardware.org/?probe=0b0db0e2ef) | Jan 22, 2024 |
| ASUSTek       | PRIME B450M-A II            | [50bd62bd8e](https://linux-hardware.org/?probe=50bd62bd8e) | Jan 21, 2024 |
| ASRock        | H570 Steel Legend           | [7c0fb43f23](https://linux-hardware.org/?probe=7c0fb43f23) | Jan 21, 2024 |
| ASRock        | X470 Taichi Ultimate        | [161b90d80c](https://linux-hardware.org/?probe=161b90d80c) | Jan 21, 2024 |
| Gigabyte      | H81M-D2W                    | [03ec02fab4](https://linux-hardware.org/?probe=03ec02fab4) | Jan 21, 2024 |
| MSI           | Z170A GAMING M5             | [742588d66a](https://linux-hardware.org/?probe=742588d66a) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [97588f48fc](https://linux-hardware.org/?probe=97588f48fc) | Jan 21, 2024 |
| MSI           | MPG Z790 CARBON WIFI        | [3224331d5e](https://linux-hardware.org/?probe=3224331d5e) | Jan 21, 2024 |
| ASRock        | FM2A88X Pro+                | [cf5b1adab5](https://linux-hardware.org/?probe=cf5b1adab5) | Jan 21, 2024 |
| AZW           | GTR V21                     | [dbc8e08754](https://linux-hardware.org/?probe=dbc8e08754) | Jan 21, 2024 |
| Foxconn       | 2A8C                        | [591fafe62b](https://linux-hardware.org/?probe=591fafe62b) | Jan 21, 2024 |
| Dell          | 051FJ8 A00                  | [186f951a85](https://linux-hardware.org/?probe=186f951a85) | Jan 21, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | [426fe50b95](https://linux-hardware.org/?probe=426fe50b95) | Jan 21, 2024 |
| MSI           | PRO Z790-P WIFI             | [55b2a770eb](https://linux-hardware.org/?probe=55b2a770eb) | Jan 21, 2024 |
| ASUSTek       | STRIX H270F GAMING          | [9c9338dcfd](https://linux-hardware.org/?probe=9c9338dcfd) | Jan 21, 2024 |
| ASUSTek       | PRIME X470-PRO              | [09c4a32231](https://linux-hardware.org/?probe=09c4a32231) | Jan 21, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | [9712c9e135](https://linux-hardware.org/?probe=9712c9e135) | Jan 21, 2024 |
| MSI           | Z370-A PRO                  | [0a97ecaa3f](https://linux-hardware.org/?probe=0a97ecaa3f) | Jan 21, 2024 |
| Dell          | 06X1TJ A00                  | [bcd509c9d9](https://linux-hardware.org/?probe=bcd509c9d9) | Jan 20, 2024 |
| ASUSTek       | M5A97 R2.0                  | [5a96118b34](https://linux-hardware.org/?probe=5a96118b34) | Jan 20, 2024 |
| Foxconn       | H61MXE                      | [0a7a342b95](https://linux-hardware.org/?probe=0a7a342b95) | Jan 20, 2024 |
| Gigabyte      | P55-USB3                    | [2ae180284e](https://linux-hardware.org/?probe=2ae180284e) | Jan 20, 2024 |
| Unknown       | HX90                        | [ced9f53d73](https://linux-hardware.org/?probe=ced9f53d73) | Jan 20, 2024 |
| Dell          | 0K068D A00                  | [b268579e9b](https://linux-hardware.org/?probe=b268579e9b) | Jan 20, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [341a928c78](https://linux-hardware.org/?probe=341a928c78) | Jan 20, 2024 |
| HP            | ProLiant ML110 Gen9         | [f5eb92f644](https://linux-hardware.org/?probe=f5eb92f644) | Jan 20, 2024 |
| ASRock        | FM2A68M-HD+                 | [63e6c0358d](https://linux-hardware.org/?probe=63e6c0358d) | Jan 20, 2024 |
| Unknown       | Unknown                     | [bcded7aa47](https://linux-hardware.org/?probe=bcded7aa47) | Jan 20, 2024 |
| Dell          | 08K0X7 A00                  | [454c4af5bc](https://linux-hardware.org/?probe=454c4af5bc) | Jan 19, 2024 |
| Dell          | 073MMW A02                  | [2e19e7434e](https://linux-hardware.org/?probe=2e19e7434e) | Jan 19, 2024 |
| ASUSTek       | PRIME H510M-A               | [6aa12bd4c7](https://linux-hardware.org/?probe=6aa12bd4c7) | Jan 19, 2024 |
| Dell          | 0M9KCM A01                  | [dd9dc75a4d](https://linux-hardware.org/?probe=dd9dc75a4d) | Jan 19, 2024 |
| Dell          | 0YGWFV A01                  | [b8474b7f54](https://linux-hardware.org/?probe=b8474b7f54) | Jan 19, 2024 |
| Dell          | 0YGWFV A01                  | [8e54683492](https://linux-hardware.org/?probe=8e54683492) | Jan 19, 2024 |
| Dell          | 02YYK5 A00                  | [0ee138a094](https://linux-hardware.org/?probe=0ee138a094) | Jan 19, 2024 |
| ASRock        | B450M Pro4                  | [440bc94322](https://linux-hardware.org/?probe=440bc94322) | Jan 19, 2024 |
| Biostar       | B450MHP                     | [16584e3717](https://linux-hardware.org/?probe=16584e3717) | Jan 19, 2024 |
| Biostar       | B450MHP                     | [24682bdb1f](https://linux-hardware.org/?probe=24682bdb1f) | Jan 19, 2024 |
| ASUSTek       | P6T DELUXE V2               | [4c2aa275e2](https://linux-hardware.org/?probe=4c2aa275e2) | Jan 19, 2024 |
| Biostar       | A320MH                      | [9213e79212](https://linux-hardware.org/?probe=9213e79212) | Jan 19, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [986bc58cd9](https://linux-hardware.org/?probe=986bc58cd9) | Jan 19, 2024 |
| Dell          | 05CNYF A01                  | [913528cc80](https://linux-hardware.org/?probe=913528cc80) | Jan 19, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | [7d86aa45c2](https://linux-hardware.org/?probe=7d86aa45c2) | Jan 19, 2024 |
| ASUSTek       | PRIME B360M-A               | [cf9f573e23](https://linux-hardware.org/?probe=cf9f573e23) | Jan 19, 2024 |
| BESSTAR Te... | HM90                        | [69c4bfff2b](https://linux-hardware.org/?probe=69c4bfff2b) | Jan 19, 2024 |
| HP            | 1998                        | [b54abe0bef](https://linux-hardware.org/?probe=b54abe0bef) | Jan 18, 2024 |
| Intel         | HM570                       | [3f05344c2c](https://linux-hardware.org/?probe=3f05344c2c) | Jan 18, 2024 |
| ASUSTek       | G16CH                       | [a482e4cc60](https://linux-hardware.org/?probe=a482e4cc60) | Jan 18, 2024 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [977382abab](https://linux-hardware.org/?probe=977382abab) | Jan 18, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [f0b1918981](https://linux-hardware.org/?probe=f0b1918981) | Jan 18, 2024 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | [370e1682cf](https://linux-hardware.org/?probe=370e1682cf) | Jan 18, 2024 |
| ASUSTek       | P6T SE                      | [6b60732b39](https://linux-hardware.org/?probe=6b60732b39) | Jan 18, 2024 |
| Dell          | 0DR845                      | [f591ac32d9](https://linux-hardware.org/?probe=f591ac32d9) | Jan 18, 2024 |
| Gigabyte      | B460 HD3                    | [4e6f6c248f](https://linux-hardware.org/?probe=4e6f6c248f) | Jan 18, 2024 |
| ASUSTek       | SABERTOOTH 990FX R3.0       | [207dc59ee3](https://linux-hardware.org/?probe=207dc59ee3) | Jan 18, 2024 |
| Apple         | Mac-F42C88C8 Proto1         | [8f87c80e99](https://linux-hardware.org/?probe=8f87c80e99) | Jan 17, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9353e2bbef](https://linux-hardware.org/?probe=9353e2bbef) | Jan 17, 2024 |
| Unknown       | HP ProLiant m400 Server ... | [adf4650d81](https://linux-hardware.org/?probe=adf4650d81) | Jan 17, 2024 |
| ASUSTek       | P6X58D-E                    | [09a124fcf0](https://linux-hardware.org/?probe=09a124fcf0) | Jan 17, 2024 |
| SZMZ          | X99 DUAL Z8                 | [623c2e3113](https://linux-hardware.org/?probe=623c2e3113) | Jan 17, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [dfa4d23039](https://linux-hardware.org/?probe=dfa4d23039) | Jan 17, 2024 |
| MSI           | Z490-A PRO                  | [57eaf7e4ff](https://linux-hardware.org/?probe=57eaf7e4ff) | Jan 17, 2024 |
| HP            | 822A                        | [9fa299bc2a](https://linux-hardware.org/?probe=9fa299bc2a) | Jan 17, 2024 |
| HP            | 822A                        | [400eeb3bba](https://linux-hardware.org/?probe=400eeb3bba) | Jan 17, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [a15715468f](https://linux-hardware.org/?probe=a15715468f) | Jan 17, 2024 |
| MSI           | PRO B650M-P                 | [13bd535c3f](https://linux-hardware.org/?probe=13bd535c3f) | Jan 17, 2024 |
| ASUSTek       | G11CD-K                     | [004aa1092f](https://linux-hardware.org/?probe=004aa1092f) | Jan 16, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [fe24385194](https://linux-hardware.org/?probe=fe24385194) | Jan 16, 2024 |
| ASUSTek       | PRIME X470-PRO              | [cb1fa259a7](https://linux-hardware.org/?probe=cb1fa259a7) | Jan 16, 2024 |
| ASUSTek       | M5A99X EVO                  | [fd42a66717](https://linux-hardware.org/?probe=fd42a66717) | Jan 16, 2024 |
| ASUSTek       | H110M-R                     | [3daca725a3](https://linux-hardware.org/?probe=3daca725a3) | Jan 16, 2024 |
| ASUSTek       | H110M-R                     | [cb598cde50](https://linux-hardware.org/?probe=cb598cde50) | Jan 16, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [3a49e03d57](https://linux-hardware.org/?probe=3a49e03d57) | Jan 16, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [fae72561ad](https://linux-hardware.org/?probe=fae72561ad) | Jan 16, 2024 |
| ASUSTek       | M5A97 R2.0                  | [ccbf148cb3](https://linux-hardware.org/?probe=ccbf148cb3) | Jan 16, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [4d53425b9f](https://linux-hardware.org/?probe=4d53425b9f) | Jan 15, 2024 |
| ASRock        | B650 PG Lightning           | [ff371f0408](https://linux-hardware.org/?probe=ff371f0408) | Jan 15, 2024 |
| PCWare        | IPMH510E                    | [a52f228033](https://linux-hardware.org/?probe=a52f228033) | Jan 15, 2024 |
| Dell          | 0X8DXD A01                  | [d374bcb1f1](https://linux-hardware.org/?probe=d374bcb1f1) | Jan 15, 2024 |
| HP            | 81B4 01                     | [2a8624aed6](https://linux-hardware.org/?probe=2a8624aed6) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4532c646e7](https://linux-hardware.org/?probe=4532c646e7) | Jan 15, 2024 |
| Gigabyte      | P55-USB3                    | [34cc055d6b](https://linux-hardware.org/?probe=34cc055d6b) | Jan 15, 2024 |
| Supermicro    | H12DST-BA                   | [d64a1ee900](https://linux-hardware.org/?probe=d64a1ee900) | Jan 15, 2024 |
| Supermicro    | H12DST-BA                   | [3f83ec793d](https://linux-hardware.org/?probe=3f83ec793d) | Jan 15, 2024 |
| Supermicro    | H12DST-BA                   | [623de08cce](https://linux-hardware.org/?probe=623de08cce) | Jan 15, 2024 |
| Supermicro    | H12DST-BA                   | [e925fa2676](https://linux-hardware.org/?probe=e925fa2676) | Jan 15, 2024 |
| Dell          | 0XJ5V0 A01                  | [09e55a9304](https://linux-hardware.org/?probe=09e55a9304) | Jan 15, 2024 |
| HP            | 18E5                        | [4fb3a76631](https://linux-hardware.org/?probe=4fb3a76631) | Jan 15, 2024 |
| ASUSTek       | STRIX X99 GAMING            | [a77f0d6a70](https://linux-hardware.org/?probe=a77f0d6a70) | Jan 15, 2024 |
| Medion        | MS-7800                     | [f0e70a4db4](https://linux-hardware.org/?probe=f0e70a4db4) | Jan 15, 2024 |
| Lenovo        | ThinkCentre M81 5048E2G     | [d4de0eb368](https://linux-hardware.org/?probe=d4de0eb368) | Jan 14, 2024 |
| Lenovo        | ThinkCentre M81 5048E2G     | [b4aecb91bf](https://linux-hardware.org/?probe=b4aecb91bf) | Jan 14, 2024 |
| Dell          | OptiPlex 7050               | [c0f181142d](https://linux-hardware.org/?probe=c0f181142d) | Jan 14, 2024 |
| MSI           | B150M BAZOOKA               | [44444075fd](https://linux-hardware.org/?probe=44444075fd) | Jan 14, 2024 |
| Gigabyte      | 990FXA-UD3                  | [cd7b830381](https://linux-hardware.org/?probe=cd7b830381) | Jan 14, 2024 |
| Gigabyte      | 990FXA-UD3                  | [84ecce6ca6](https://linux-hardware.org/?probe=84ecce6ca6) | Jan 14, 2024 |
| Dell          | 0XCR8D A01                  | [761cd45b4a](https://linux-hardware.org/?probe=761cd45b4a) | Jan 14, 2024 |
| Dell          | 0TDG4V A01                  | [41ac0edbe0](https://linux-hardware.org/?probe=41ac0edbe0) | Jan 14, 2024 |
| Dell          | 0K068D A00                  | [ef25812c9b](https://linux-hardware.org/?probe=ef25812c9b) | Jan 14, 2024 |
| Gigabyte      | B450M DS3H-CF               | [546e67bcf4](https://linux-hardware.org/?probe=546e67bcf4) | Jan 14, 2024 |
| Dell          | 0GWHMW A00                  | [42cd6629f0](https://linux-hardware.org/?probe=42cd6629f0) | Jan 14, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [74cdfb120c](https://linux-hardware.org/?probe=74cdfb120c) | Jan 14, 2024 |
| Biostar       | B350GT3                     | [d210ea56f8](https://linux-hardware.org/?probe=d210ea56f8) | Jan 14, 2024 |
| Gigabyte      | B550M DS3H                  | [0ab04d0727](https://linux-hardware.org/?probe=0ab04d0727) | Jan 14, 2024 |
| MSI           | H110M PRO-VD                | [c8b3437429](https://linux-hardware.org/?probe=c8b3437429) | Jan 13, 2024 |
| HP            | 3048h                       | [352c2d797c](https://linux-hardware.org/?probe=352c2d797c) | Jan 13, 2024 |
| Gigabyte      | GA-MA78GM-US2H              | [2dbb9562af](https://linux-hardware.org/?probe=2dbb9562af) | Jan 13, 2024 |
| ASRock        | B660 Pro RS                 | [e7dc825ebd](https://linux-hardware.org/?probe=e7dc825ebd) | Jan 13, 2024 |
| HP            | 3048h                       | [f4972d54fd](https://linux-hardware.org/?probe=f4972d54fd) | Jan 13, 2024 |
| ASRock        | 970 Extreme4                | [7c02fff797](https://linux-hardware.org/?probe=7c02fff797) | Jan 13, 2024 |
| ASRock        | 970 Extreme4                | [9956a82d50](https://linux-hardware.org/?probe=9956a82d50) | Jan 13, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [e2a832747d](https://linux-hardware.org/?probe=e2a832747d) | Jan 13, 2024 |
| ASUSTek       | A88XM-E/USB                 | [3ae14ee6a8](https://linux-hardware.org/?probe=3ae14ee6a8) | Jan 13, 2024 |
| BESSTAR Te... | UM700                       | [07e4f86238](https://linux-hardware.org/?probe=07e4f86238) | Jan 13, 2024 |
| ASUSTek       | A58M-K                      | [574d526af4](https://linux-hardware.org/?probe=574d526af4) | Jan 13, 2024 |
| Intel         | X79-SERVER V1.1             | [ec275f8de3](https://linux-hardware.org/?probe=ec275f8de3) | Jan 13, 2024 |
| Intel         | DH55TC AAG26116-302         | [593bf4f394](https://linux-hardware.org/?probe=593bf4f394) | Jan 13, 2024 |
| Intel         | DH55TC AAG26116-302         | [8d503de9a9](https://linux-hardware.org/?probe=8d503de9a9) | Jan 13, 2024 |
| Intel         | X79-SERVER V1.1             | [a15d2182be](https://linux-hardware.org/?probe=a15d2182be) | Jan 13, 2024 |
| Intel         | X99                         | [6fff9c3661](https://linux-hardware.org/?probe=6fff9c3661) | Jan 13, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | [b2862b579f](https://linux-hardware.org/?probe=b2862b579f) | Jan 13, 2024 |
| ASRock        | N68-GS                      | [d8f071018b](https://linux-hardware.org/?probe=d8f071018b) | Jan 13, 2024 |
| Dell          | 0YXT71 A03                  | [3aa9c455f5](https://linux-hardware.org/?probe=3aa9c455f5) | Jan 13, 2024 |
| Acer          | Veriton X2631G V:1.0        | [56b1b4f807](https://linux-hardware.org/?probe=56b1b4f807) | Jan 13, 2024 |
| ASUSTek       | SABERTOOTH X58              | [097d095e0b](https://linux-hardware.org/?probe=097d095e0b) | Jan 13, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | [1e616f7505](https://linux-hardware.org/?probe=1e616f7505) | Jan 13, 2024 |
| MSI           | H81M-P33 V2                 | [5cb55d28df](https://linux-hardware.org/?probe=5cb55d28df) | Jan 12, 2024 |
| ASRock        | B360M Pro4                  | [054186ab28](https://linux-hardware.org/?probe=054186ab28) | Jan 12, 2024 |
| Alienware     | 0FPV4P A00                  | [ae50bc7ef0](https://linux-hardware.org/?probe=ae50bc7ef0) | Jan 12, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [c496e279e2](https://linux-hardware.org/?probe=c496e279e2) | Jan 12, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [bc31bf9978](https://linux-hardware.org/?probe=bc31bf9978) | Jan 12, 2024 |
| MSI           | H97 PC Mate                 | [b9df3e4a61](https://linux-hardware.org/?probe=b9df3e4a61) | Jan 12, 2024 |
| Inventec      | VXC Class A02               | [6d6e888c50](https://linux-hardware.org/?probe=6d6e888c50) | Jan 12, 2024 |
| ASUSTek       | PRIME Z690-P                | [b37b59525e](https://linux-hardware.org/?probe=b37b59525e) | Jan 12, 2024 |
| Google        | Kench                       | [09cb7c7c8c](https://linux-hardware.org/?probe=09cb7c7c8c) | Jan 12, 2024 |
| ASUSTek       | PRIME B560M-A               | [ee518e7cc7](https://linux-hardware.org/?probe=ee518e7cc7) | Jan 12, 2024 |
| Dell          | 0DR845                      | [5185c062d7](https://linux-hardware.org/?probe=5185c062d7) | Jan 12, 2024 |
| ASRock        | A320M/ac                    | [fc6b575161](https://linux-hardware.org/?probe=fc6b575161) | Jan 12, 2024 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | [7049dd3f9a](https://linux-hardware.org/?probe=7049dd3f9a) | Jan 12, 2024 |
| Medion        | MS-7713                     | [6264963f7f](https://linux-hardware.org/?probe=6264963f7f) | Jan 11, 2024 |
| Gigabyte      | Z590 VISION G               | [e7b280f139](https://linux-hardware.org/?probe=e7b280f139) | Jan 11, 2024 |
| Gigabyte      | GA-990FXA-UD3               | [8a634f1a99](https://linux-hardware.org/?probe=8a634f1a99) | Jan 11, 2024 |
| HP            | 1494                        | [2d0efc2df1](https://linux-hardware.org/?probe=2d0efc2df1) | Jan 11, 2024 |
| Dell          | 0D24M8 A00                  | [a482ed79df](https://linux-hardware.org/?probe=a482ed79df) | Jan 11, 2024 |
| Dell          | 0773VG A02                  | [f06d515c8d](https://linux-hardware.org/?probe=f06d515c8d) | Jan 11, 2024 |
| Gigabyte      | B150M-D3H-CF                | [0f1bb4710b](https://linux-hardware.org/?probe=0f1bb4710b) | Jan 11, 2024 |
| Supermicro    | X10DDW-i                    | [ce09e674db](https://linux-hardware.org/?probe=ce09e674db) | Jan 11, 2024 |
| Dell          | 07T4MC A00                  | [11b0c38685](https://linux-hardware.org/?probe=11b0c38685) | Jan 11, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3a45f1d548](https://linux-hardware.org/?probe=3a45f1d548) | Jan 11, 2024 |
| SPESTECH      | IB.IELK.CW01                | [3a97c43bcc](https://linux-hardware.org/?probe=3a97c43bcc) | Jan 11, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [36143515d5](https://linux-hardware.org/?probe=36143515d5) | Jan 11, 2024 |
| Unknown       | Unknown                     | [6baa4ca11a](https://linux-hardware.org/?probe=6baa4ca11a) | Jan 11, 2024 |
| HP            | 1589                        | [57f5f20e09](https://linux-hardware.org/?probe=57f5f20e09) | Jan 10, 2024 |
| Dell          | 0K240Y A01                  | [bcd5fdf52a](https://linux-hardware.org/?probe=bcd5fdf52a) | Jan 10, 2024 |
| HP            | 8054                        | [a9ef74e12b](https://linux-hardware.org/?probe=a9ef74e12b) | Jan 10, 2024 |
| ASRock        | B550 Pro4                   | [96741b129f](https://linux-hardware.org/?probe=96741b129f) | Jan 10, 2024 |
| Gigabyte      | P35-DS3R                    | [8012464652](https://linux-hardware.org/?probe=8012464652) | Jan 10, 2024 |
| Lenovo        | NO DPK                      | [739397b2fd](https://linux-hardware.org/?probe=739397b2fd) | Jan 10, 2024 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | [5f33f48cbe](https://linux-hardware.org/?probe=5f33f48cbe) | Jan 10, 2024 |
| HP            | ProLiant ML150 G6           | [15df93ab9c](https://linux-hardware.org/?probe=15df93ab9c) | Jan 10, 2024 |
| Dell          | 0J9VVP A00                  | [855cc5cb5c](https://linux-hardware.org/?probe=855cc5cb5c) | Jan 10, 2024 |
| Dell          | 0RW199                      | [a80b1a7541](https://linux-hardware.org/?probe=a80b1a7541) | Jan 10, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [9e8a81f355](https://linux-hardware.org/?probe=9e8a81f355) | Jan 10, 2024 |
| HP            | 802E                        | [e07fedf95d](https://linux-hardware.org/?probe=e07fedf95d) | Jan 09, 2024 |
| Supermicro    | X10DRU-i+A                  | [99d2afabde](https://linux-hardware.org/?probe=99d2afabde) | Jan 09, 2024 |
| Supermicro    | X10DDW-i                    | [04153850d2](https://linux-hardware.org/?probe=04153850d2) | Jan 09, 2024 |
| Supermicro    | X10DDW-i                    | [13fdb351eb](https://linux-hardware.org/?probe=13fdb351eb) | Jan 09, 2024 |
| Supermicro    | X10DDW-i                    | [3e1d916552](https://linux-hardware.org/?probe=3e1d916552) | Jan 09, 2024 |
| Supermicro    | X10DRL-i                    | [59f7acf7d1](https://linux-hardware.org/?probe=59f7acf7d1) | Jan 09, 2024 |
| Supermicro    | X10DDW-i                    | [f97c7d0615](https://linux-hardware.org/?probe=f97c7d0615) | Jan 09, 2024 |
| Supermicro    | X10DRL-i                    | [97ae6ae9d6](https://linux-hardware.org/?probe=97ae6ae9d6) | Jan 09, 2024 |
| Shenzhen M... | F7BSC                       | [80d405caee](https://linux-hardware.org/?probe=80d405caee) | Jan 09, 2024 |
| HP            | 802E                        | [98da041426](https://linux-hardware.org/?probe=98da041426) | Jan 09, 2024 |
| Dell          | 0FDY5C A00                  | [75d43bcfb1](https://linux-hardware.org/?probe=75d43bcfb1) | Jan 08, 2024 |
| ASUSTek       | G11CD-K                     | [52f6b591f0](https://linux-hardware.org/?probe=52f6b591f0) | Jan 08, 2024 |
| Dell          | 0FDY5C A00                  | [ad79e14384](https://linux-hardware.org/?probe=ad79e14384) | Jan 08, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [c5b2a8a90a](https://linux-hardware.org/?probe=c5b2a8a90a) | Jan 08, 2024 |
| ASRock        | A320M/ac                    | [61c1bebfec](https://linux-hardware.org/?probe=61c1bebfec) | Jan 08, 2024 |
| Pegatron      | IPMH61P1                    | [4a65448cb8](https://linux-hardware.org/?probe=4a65448cb8) | Jan 08, 2024 |
| OEM           | B7D                         | [be419ae1dd](https://linux-hardware.org/?probe=be419ae1dd) | Jan 08, 2024 |
| Gigabyte      | H510M S2H V2                | [48ba042e53](https://linux-hardware.org/?probe=48ba042e53) | Jan 08, 2024 |
| ASUSTek       | P5KPL-CM                    | [999db6bbcb](https://linux-hardware.org/?probe=999db6bbcb) | Jan 08, 2024 |
| MSI           | B550-A PRO                  | [363ad22f1d](https://linux-hardware.org/?probe=363ad22f1d) | Jan 08, 2024 |
| Shenzhen M... | F7BRC                       | [720a2d2f2e](https://linux-hardware.org/?probe=720a2d2f2e) | Jan 08, 2024 |
| MSI           | Z370-A PRO                  | [8cee53e85f](https://linux-hardware.org/?probe=8cee53e85f) | Jan 08, 2024 |
| Gigabyte      | B760 GAMING X AX DDR4       | [807f4aa507](https://linux-hardware.org/?probe=807f4aa507) | Jan 07, 2024 |
| Gigabyte      | B85M-HD3                    | [5229c0698f](https://linux-hardware.org/?probe=5229c0698f) | Jan 07, 2024 |
| HP            | 1850                        | [0a05038be5](https://linux-hardware.org/?probe=0a05038be5) | Jan 07, 2024 |
| ASUSTek       | H81M-C                      | [9c1bde7d6d](https://linux-hardware.org/?probe=9c1bde7d6d) | Jan 07, 2024 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [ec227e187d](https://linux-hardware.org/?probe=ec227e187d) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [015e318a3b](https://linux-hardware.org/?probe=015e318a3b) | Jan 07, 2024 |
| Dell          | 018D1Y A00                  | [4564a7ced9](https://linux-hardware.org/?probe=4564a7ced9) | Jan 07, 2024 |
| HP            | 1850                        | [48072766c5](https://linux-hardware.org/?probe=48072766c5) | Jan 07, 2024 |
| Cisco Syst... | UCSC-C220-M3S 74-10442-0... | [2bc5f49245](https://linux-hardware.org/?probe=2bc5f49245) | Jan 07, 2024 |
| ASUSTek       | P9X79                       | [a2b3231c7a](https://linux-hardware.org/?probe=a2b3231c7a) | Jan 07, 2024 |
| MSI           | 2AE0                        | [71a31212bb](https://linux-hardware.org/?probe=71a31212bb) | Jan 07, 2024 |
| AMD           | A88                         | [f614fcb81f](https://linux-hardware.org/?probe=f614fcb81f) | Jan 06, 2024 |
| eMachines     | EL1350                      | [1f46a9e4b2](https://linux-hardware.org/?probe=1f46a9e4b2) | Jan 06, 2024 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | [3b1d3575ed](https://linux-hardware.org/?probe=3b1d3575ed) | Jan 06, 2024 |
| Gigabyte      | B150M-DS3H-CF               | [428c97e8d0](https://linux-hardware.org/?probe=428c97e8d0) | Jan 06, 2024 |
| AMD           | A88                         | [04e378da84](https://linux-hardware.org/?probe=04e378da84) | Jan 06, 2024 |
| Gigabyte      | B150M-DS3H-CF               | [05bbb14c15](https://linux-hardware.org/?probe=05bbb14c15) | Jan 06, 2024 |
| MSI           | B450M MORTAR MAX            | [34f9702909](https://linux-hardware.org/?probe=34f9702909) | Jan 06, 2024 |
| Gigabyte      | GB-BEI5-1240                | [c79e4d2996](https://linux-hardware.org/?probe=c79e4d2996) | Jan 06, 2024 |
| Gigabyte      | GB-BEI5-1240                | [818200d0a2](https://linux-hardware.org/?probe=818200d0a2) | Jan 06, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [0a9a88c59f](https://linux-hardware.org/?probe=0a9a88c59f) | Jan 06, 2024 |
| EVGA          | 132-YW-E179-FTW 1           | [8da03704e8](https://linux-hardware.org/?probe=8da03704e8) | Jan 06, 2024 |
| Supermicro    | X9SCI/X9SCA                 | [f26fd37750](https://linux-hardware.org/?probe=f26fd37750) | Jan 06, 2024 |
| Gigabyte      | Z97X-UD5H-BK                | [ad5cae0bab](https://linux-hardware.org/?probe=ad5cae0bab) | Jan 06, 2024 |
| HP            | 2B35                        | [440fa90f6f](https://linux-hardware.org/?probe=440fa90f6f) | Jan 05, 2024 |
| MSI           | B460M-A PRO                 | [4e7806e597](https://linux-hardware.org/?probe=4e7806e597) | Jan 05, 2024 |
| HP            | 2B35                        | [e6337403f7](https://linux-hardware.org/?probe=e6337403f7) | Jan 05, 2024 |
| Intel         | H61/B75                     | [e44ccc1a76](https://linux-hardware.org/?probe=e44ccc1a76) | Jan 05, 2024 |
| ASUSTek       | B760M-AYW WIFI              | [6a471fb5e8](https://linux-hardware.org/?probe=6a471fb5e8) | Jan 05, 2024 |
| Pegatron      | 2A84h                       | [d9de7d8df1](https://linux-hardware.org/?probe=d9de7d8df1) | Jan 05, 2024 |
| Gigabyte      | B560M H                     | [d7952bcc19](https://linux-hardware.org/?probe=d7952bcc19) | Jan 05, 2024 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [f1b2c46af1](https://linux-hardware.org/?probe=f1b2c46af1) | Jan 05, 2024 |
| Intel         | JSL MRD                     | [806de7a9fc](https://linux-hardware.org/?probe=806de7a9fc) | Jan 05, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [98cc0a2e6d](https://linux-hardware.org/?probe=98cc0a2e6d) | Jan 05, 2024 |
| Intel         | JSL MRD                     | [5650f4ed95](https://linux-hardware.org/?probe=5650f4ed95) | Jan 05, 2024 |
| Unknown       | Unknown                     | [dd6b7a2d69](https://linux-hardware.org/?probe=dd6b7a2d69) | Jan 05, 2024 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [f5b3cddf2f](https://linux-hardware.org/?probe=f5b3cddf2f) | Jan 05, 2024 |
| ASUSTek       | Rampage V EDITION 10        | [e666d40d0e](https://linux-hardware.org/?probe=e666d40d0e) | Jan 04, 2024 |
| Gigabyte      | B560 AORUS PRO AX           | [9fdb7c6d17](https://linux-hardware.org/?probe=9fdb7c6d17) | Jan 04, 2024 |
| Dell          | 0773VG A00                  | [5337319e57](https://linux-hardware.org/?probe=5337319e57) | Jan 04, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [26dd967e32](https://linux-hardware.org/?probe=26dd967e32) | Jan 04, 2024 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [fb96d69697](https://linux-hardware.org/?probe=fb96d69697) | Jan 04, 2024 |
| HP            | ProLiant ML110 Gen9         | [2cefb2c1d5](https://linux-hardware.org/?probe=2cefb2c1d5) | Jan 04, 2024 |
| ASUSTek       | TUF B360M-E GAMING          | [453e5e7b1a](https://linux-hardware.org/?probe=453e5e7b1a) | Jan 04, 2024 |
| Dell          | 06FW8P A01                  | [64eb36d553](https://linux-hardware.org/?probe=64eb36d553) | Jan 04, 2024 |
| Dell          | 06FW8P A01                  | [4a93269eb2](https://linux-hardware.org/?probe=4a93269eb2) | Jan 04, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [436f8ebcc9](https://linux-hardware.org/?probe=436f8ebcc9) | Jan 04, 2024 |
| Dell          | 0VNM11 A00                  | [060cdd6c04](https://linux-hardware.org/?probe=060cdd6c04) | Jan 04, 2024 |
| MSI           | Z97 GAMING 3                | [7dbbaf8f8a](https://linux-hardware.org/?probe=7dbbaf8f8a) | Jan 04, 2024 |
| Gigabyte      | H510M S2H                   | [dde30793cf](https://linux-hardware.org/?probe=dde30793cf) | Jan 04, 2024 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [790e68a3c7](https://linux-hardware.org/?probe=790e68a3c7) | Jan 04, 2024 |
| Gigabyte      | A320M-S2H-CF                | [31b1e0e2ed](https://linux-hardware.org/?probe=31b1e0e2ed) | Jan 04, 2024 |
| ASUSTek       | P7P55D PRO                  | [ad03a876d3](https://linux-hardware.org/?probe=ad03a876d3) | Jan 04, 2024 |
| ASRock        | H61M/U3S3                   | [e6f1a43f8e](https://linux-hardware.org/?probe=e6f1a43f8e) | Jan 03, 2024 |
| Gigabyte      | G31M-S2L                    | [14ef56bddf](https://linux-hardware.org/?probe=14ef56bddf) | Jan 03, 2024 |
| Lenovo        | ThinkCentre M58 7244A37     | [055046db1b](https://linux-hardware.org/?probe=055046db1b) | Jan 03, 2024 |
| Foxconn       | 2AAF                        | [57599bfe8d](https://linux-hardware.org/?probe=57599bfe8d) | Jan 03, 2024 |
| Gigabyte      | MH610AT-SI                  | [1b75d28eb3](https://linux-hardware.org/?probe=1b75d28eb3) | Jan 03, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [1272096f12](https://linux-hardware.org/?probe=1272096f12) | Jan 03, 2024 |
| ASRock        | Z77 Performance             | [7f44640341](https://linux-hardware.org/?probe=7f44640341) | Jan 03, 2024 |
| ASUSTek       | H610A-IM-A                  | [9ca65cc91e](https://linux-hardware.org/?probe=9ca65cc91e) | Jan 03, 2024 |
| ASUSTek       | H610A-IM-A                  | [a3d7b469e5](https://linux-hardware.org/?probe=a3d7b469e5) | Jan 03, 2024 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | [a7f5e10167](https://linux-hardware.org/?probe=a7f5e10167) | Jan 03, 2024 |
| ASUSTek       | H81M-C                      | [254c995de7](https://linux-hardware.org/?probe=254c995de7) | Jan 02, 2024 |
| ASRock        | A520M-ITX/ac                | [7bd61f9bd1](https://linux-hardware.org/?probe=7bd61f9bd1) | Jan 02, 2024 |
| Gigabyte      | H310M H x.x                 | [31c94a2bae](https://linux-hardware.org/?probe=31c94a2bae) | Jan 02, 2024 |
| ASUSTek       | PRIME X370-PRO              | [52935ac75e](https://linux-hardware.org/?probe=52935ac75e) | Jan 02, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [8401b0bb88](https://linux-hardware.org/?probe=8401b0bb88) | Jan 02, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [ee1c1bbe4a](https://linux-hardware.org/?probe=ee1c1bbe4a) | Jan 02, 2024 |
| Lenovo        | ThinkStation S20 4157E87    | [0d92b00ebc](https://linux-hardware.org/?probe=0d92b00ebc) | Jan 02, 2024 |
| Gigabyte      | GA-78LMT-S2P                | [2fee56835f](https://linux-hardware.org/?probe=2fee56835f) | Jan 02, 2024 |
| ASRock        | J5005-ITX                   | [5373e7f16c](https://linux-hardware.org/?probe=5373e7f16c) | Jan 02, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3a67df5dcf](https://linux-hardware.org/?probe=3a67df5dcf) | Jan 02, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [b163926938](https://linux-hardware.org/?probe=b163926938) | Jan 02, 2024 |
| ASUSTek       | H81M-C                      | [221ebe85fb](https://linux-hardware.org/?probe=221ebe85fb) | Jan 02, 2024 |
| Dell          | 0XJ8C4 A00                  | [e902f5396d](https://linux-hardware.org/?probe=e902f5396d) | Jan 02, 2024 |
| MSI           | Z77A-G43                    | [b33c14ee42](https://linux-hardware.org/?probe=b33c14ee42) | Jan 02, 2024 |
| MSI           | X79A-GD65                   | [ecb9a57738](https://linux-hardware.org/?probe=ecb9a57738) | Jan 01, 2024 |
| ASRock        | B450M Gaming                | [81242d3eca](https://linux-hardware.org/?probe=81242d3eca) | Jan 01, 2024 |
| ASUSTek       | P8H67-M LE                  | [82877fbf5e](https://linux-hardware.org/?probe=82877fbf5e) | Jan 01, 2024 |
| HP            | 82A2                        | [7cc3d17916](https://linux-hardware.org/?probe=7cc3d17916) | Jan 01, 2024 |
| Gigabyte      | H270N-WIFI-CF               | [d47bc3897f](https://linux-hardware.org/?probe=d47bc3897f) | Jan 01, 2024 |
| Medion        | H110H4-EM                   | [da3367c80e](https://linux-hardware.org/?probe=da3367c80e) | Jan 01, 2024 |
| Dell          | 0D24M8 A01                  | [f363c3e115](https://linux-hardware.org/?probe=f363c3e115) | Jan 01, 2024 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | [fc9ced99d5](https://linux-hardware.org/?probe=fc9ced99d5) | Jan 01, 2024 |
| Dell          | 09KPNV A01                  | [d6c27424e2](https://linux-hardware.org/?probe=d6c27424e2) | Jan 01, 2024 |
| Centerm       | C92                         | [5ede09f987](https://linux-hardware.org/?probe=5ede09f987) | Jan 01, 2024 |
| Centerm       | C92                         | [0201370bf4](https://linux-hardware.org/?probe=0201370bf4) | Jan 01, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [6dbc709464](https://linux-hardware.org/?probe=6dbc709464) | Jan 01, 2024 |
| ASRock        | X399 Professional Gaming    | [2d812c76d3](https://linux-hardware.org/?probe=2d812c76d3) | Jan 01, 2024 |
| ASRock        | B450M Pro4                  | [126f6b0c9c](https://linux-hardware.org/?probe=126f6b0c9c) | Dec 31, 2023 |
| ASRock        | B450M Pro4                  | [8625e5d1fa](https://linux-hardware.org/?probe=8625e5d1fa) | Dec 31, 2023 |
| MSI           | B550-A PRO                  | [3b6183bbb5](https://linux-hardware.org/?probe=3b6183bbb5) | Dec 31, 2023 |
| Foxconn       | 2ADA                        | [ae6e6ab09f](https://linux-hardware.org/?probe=ae6e6ab09f) | Dec 31, 2023 |
| HP            | 18E9                        | [298cd92eb1](https://linux-hardware.org/?probe=298cd92eb1) | Dec 31, 2023 |
| ZOTAC         | NM10                        | [c0f4135bd0](https://linux-hardware.org/?probe=c0f4135bd0) | Dec 31, 2023 |
| MACHINIST     | X99-D8-MAX V1.0             | [ef584ae5a8](https://linux-hardware.org/?probe=ef584ae5a8) | Dec 31, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fda4d32a86](https://linux-hardware.org/?probe=fda4d32a86) | Dec 31, 2023 |
| Dell          | 0C2XKD A01                  | [5e36d4fb43](https://linux-hardware.org/?probe=5e36d4fb43) | Dec 31, 2023 |
| ASUSTek       | P8H67-M PRO                 | [63d62dd94e](https://linux-hardware.org/?probe=63d62dd94e) | Dec 31, 2023 |
| HP            | ProLiant ML110 Gen9         | [0181b68b4a](https://linux-hardware.org/?probe=0181b68b4a) | Dec 31, 2023 |
| ASUSTek       | P8H67-M PRO                 | [6a45d6cf9e](https://linux-hardware.org/?probe=6a45d6cf9e) | Dec 30, 2023 |
| Gigabyte      | A620I AX                    | [7f73790fbf](https://linux-hardware.org/?probe=7f73790fbf) | Dec 30, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [af479728a3](https://linux-hardware.org/?probe=af479728a3) | Dec 30, 2023 |
| ASUSTek       | PRIME X470-PRO              | [495efd257e](https://linux-hardware.org/?probe=495efd257e) | Dec 30, 2023 |
| Unknown       | Unknown                     | [e6e8bd6545](https://linux-hardware.org/?probe=e6e8bd6545) | Dec 30, 2023 |
| MSI           | B350 KRAIT GAMING           | [a4582db0da](https://linux-hardware.org/?probe=a4582db0da) | Dec 30, 2023 |
| DFI           | LP DK 790FXB-M2RS           | [8d0c82bedc](https://linux-hardware.org/?probe=8d0c82bedc) | Dec 30, 2023 |
| HP            | ProLiant ML110 Gen9         | [4cb0683071](https://linux-hardware.org/?probe=4cb0683071) | Dec 30, 2023 |
| Lenovo        | 30BD NOK                    | [033b3c8abd](https://linux-hardware.org/?probe=033b3c8abd) | Dec 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e14a6e4044](https://linux-hardware.org/?probe=e14a6e4044) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | [88a9972a33](https://linux-hardware.org/?probe=88a9972a33) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | [91be04698f](https://linux-hardware.org/?probe=91be04698f) | Dec 30, 2023 |
| Dell          | 09KPNV A01                  | [115ec4e7a9](https://linux-hardware.org/?probe=115ec4e7a9) | Dec 29, 2023 |
| HP            | 304Ah                       | [0a84d8bd4a](https://linux-hardware.org/?probe=0a84d8bd4a) | Dec 29, 2023 |
| Gigabyte      | 990FXA-UD3                  | [9104adc237](https://linux-hardware.org/?probe=9104adc237) | Dec 29, 2023 |
| Shenzhen M... | AHBNB OEM                   | [9883edd543](https://linux-hardware.org/?probe=9883edd543) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [36b4cb3de7](https://linux-hardware.org/?probe=36b4cb3de7) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [7accaaedbb](https://linux-hardware.org/?probe=7accaaedbb) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [5d7ab2ff4b](https://linux-hardware.org/?probe=5d7ab2ff4b) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [be9b9577fd](https://linux-hardware.org/?probe=be9b9577fd) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [4f7ea59b94](https://linux-hardware.org/?probe=4f7ea59b94) | Dec 29, 2023 |
| ASUSTek       | X99-DELUXE                  | [2433b4bc75](https://linux-hardware.org/?probe=2433b4bc75) | Dec 29, 2023 |
| Dell          | 00V62H A01                  | [0032f131d1](https://linux-hardware.org/?probe=0032f131d1) | Dec 29, 2023 |
| MSI           | H110M PRO-VD                | [318343d58b](https://linux-hardware.org/?probe=318343d58b) | Dec 29, 2023 |
| ASUSTek       | PRIME A520M-E               | [3133f699e1](https://linux-hardware.org/?probe=3133f699e1) | Dec 29, 2023 |
| Dell          | 096JG8 A01                  | [915a028a6a](https://linux-hardware.org/?probe=915a028a6a) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [51ab2c0529](https://linux-hardware.org/?probe=51ab2c0529) | Dec 29, 2023 |
| Inventec      | VXC Class A02               | [0575404de8](https://linux-hardware.org/?probe=0575404de8) | Dec 29, 2023 |
| ASUSTek       | PRIME B365M-A               | [2109440c5e](https://linux-hardware.org/?probe=2109440c5e) | Dec 29, 2023 |
| ASUSTek       | PRIME B365M-A               | [69ed200761](https://linux-hardware.org/?probe=69ed200761) | Dec 29, 2023 |
| MSI           | H110M PRO-VD                | [1c6ef1eeb0](https://linux-hardware.org/?probe=1c6ef1eeb0) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [4f4c0766c2](https://linux-hardware.org/?probe=4f4c0766c2) | Dec 28, 2023 |
| ASRock        | B250M-HDV                   | [c6c27e51ca](https://linux-hardware.org/?probe=c6c27e51ca) | Dec 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2d53ff60cb](https://linux-hardware.org/?probe=2d53ff60cb) | Dec 28, 2023 |
| Dell          | 04Y8V0 A02                  | [ba96083a55](https://linux-hardware.org/?probe=ba96083a55) | Dec 28, 2023 |
| HP            | 830C                        | [2f602f34b2](https://linux-hardware.org/?probe=2f602f34b2) | Dec 28, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | [0d4c53d42f](https://linux-hardware.org/?probe=0d4c53d42f) | Dec 28, 2023 |
| ASUSTek       | PRIME H510M-A               | [e65000c3c2](https://linux-hardware.org/?probe=e65000c3c2) | Dec 28, 2023 |
| HP            | 830C                        | [2256355ca5](https://linux-hardware.org/?probe=2256355ca5) | Dec 28, 2023 |
| ASRock        | AMCP7A-ION                  | [8358bb2fb8](https://linux-hardware.org/?probe=8358bb2fb8) | Dec 28, 2023 |
| Dell          | 0YXT71 A03                  | [7a857447b4](https://linux-hardware.org/?probe=7a857447b4) | Dec 28, 2023 |
| JHZD          | BQM6                        | [fa041569a6](https://linux-hardware.org/?probe=fa041569a6) | Dec 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [8df141917e](https://linux-hardware.org/?probe=8df141917e) | Dec 28, 2023 |
| Acer          | H410H6-M17 P21-A1           | [6c4e2313d7](https://linux-hardware.org/?probe=6c4e2313d7) | Dec 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [020ea108b0](https://linux-hardware.org/?probe=020ea108b0) | Dec 28, 2023 |
| Gigabyte      | B660 DS3H DDR4              | [3b68c7809f](https://linux-hardware.org/?probe=3b68c7809f) | Dec 27, 2023 |
| HP            | 1589                        | [c52940817e](https://linux-hardware.org/?probe=c52940817e) | Dec 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | [e0b1c57cc6](https://linux-hardware.org/?probe=e0b1c57cc6) | Dec 27, 2023 |
| MSI           | X79A-GD65                   | [298e0aeef7](https://linux-hardware.org/?probe=298e0aeef7) | Dec 27, 2023 |
| MSI           | X79A-GD65                   | [0272fb469a](https://linux-hardware.org/?probe=0272fb469a) | Dec 27, 2023 |
| Dell          | 02VCFF A00                  | [902c7a4466](https://linux-hardware.org/?probe=902c7a4466) | Dec 27, 2023 |
| ASRock        | B650M PG Riptide            | [9a27ea61df](https://linux-hardware.org/?probe=9a27ea61df) | Dec 27, 2023 |
| HP            | 86E9 A                      | [e373d2be5d](https://linux-hardware.org/?probe=e373d2be5d) | Dec 27, 2023 |
| MSI           | B150M MORTAR                | [c179cdb6dc](https://linux-hardware.org/?probe=c179cdb6dc) | Dec 27, 2023 |
| Acer          | H410H6-M17 P21-A1           | [106af034ae](https://linux-hardware.org/?probe=106af034ae) | Dec 27, 2023 |
| Dell          | 0KWVT8 A03                  | [fae868ef79](https://linux-hardware.org/?probe=fae868ef79) | Dec 26, 2023 |
| ASUSTek       | PRIME X570-PRO              | [4e5179b4d1](https://linux-hardware.org/?probe=4e5179b4d1) | Dec 26, 2023 |
| Supermicro    | X8SIL                       | [16a2d27e0a](https://linux-hardware.org/?probe=16a2d27e0a) | Dec 26, 2023 |
| MSI           | MAG B560M BAZOOKA           | [64d1814f82](https://linux-hardware.org/?probe=64d1814f82) | Dec 26, 2023 |
| MSI           | B150M MORTAR                | [23577ab5f1](https://linux-hardware.org/?probe=23577ab5f1) | Dec 26, 2023 |
| Dell          | 042P49 A02                  | [67c9288ec5](https://linux-hardware.org/?probe=67c9288ec5) | Dec 26, 2023 |
| HP            | 86E9 A                      | [c13adc0c5e](https://linux-hardware.org/?probe=c13adc0c5e) | Dec 26, 2023 |
| Dell          | 0D6H9T A00                  | [280147184f](https://linux-hardware.org/?probe=280147184f) | Dec 26, 2023 |
| HP            | 81C5 MVB                    | [15a3980b4a](https://linux-hardware.org/?probe=15a3980b4a) | Dec 25, 2023 |
| MSI           | B85-G43                     | [fd632d7a1f](https://linux-hardware.org/?probe=fd632d7a1f) | Dec 25, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [39eb82bb24](https://linux-hardware.org/?probe=39eb82bb24) | Dec 25, 2023 |
| MSI           | A68HM-P33 V2                | [4f11205fd5](https://linux-hardware.org/?probe=4f11205fd5) | Dec 25, 2023 |
| ASRock        | H61M-VG3                    | [1ef527f93a](https://linux-hardware.org/?probe=1ef527f93a) | Dec 24, 2023 |
| ASRock        | H61DEL                      | [932b2c50eb](https://linux-hardware.org/?probe=932b2c50eb) | Dec 24, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [915a47dab1](https://linux-hardware.org/?probe=915a47dab1) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | [d330d1d9f9](https://linux-hardware.org/?probe=d330d1d9f9) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | [d8ae24af2b](https://linux-hardware.org/?probe=d8ae24af2b) | Dec 24, 2023 |
| Acer          | Veriton X2631G V:1.0        | [c9555a34f2](https://linux-hardware.org/?probe=c9555a34f2) | Dec 23, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [b1c3408d24](https://linux-hardware.org/?probe=b1c3408d24) | Dec 23, 2023 |
| ASRock        | H310CM-HDV/M.2              | [76d95ab75c](https://linux-hardware.org/?probe=76d95ab75c) | Dec 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [6f36390142](https://linux-hardware.org/?probe=6f36390142) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | [fb0acc2d50](https://linux-hardware.org/?probe=fb0acc2d50) | Dec 23, 2023 |
| HP            | 1497                        | [9d5244b557](https://linux-hardware.org/?probe=9d5244b557) | Dec 23, 2023 |
| Lenovo        | ThinkCentre M58 7373AJ5     | [201981bc3f](https://linux-hardware.org/?probe=201981bc3f) | Dec 23, 2023 |
| Foxconn       | 2ADA                        | [f30aec24c2](https://linux-hardware.org/?probe=f30aec24c2) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | [7d19dec574](https://linux-hardware.org/?probe=7d19dec574) | Dec 23, 2023 |
| MSI           | PRO Z790-A WIFI             | [9b8ad6a3f1](https://linux-hardware.org/?probe=9b8ad6a3f1) | Dec 23, 2023 |
| eMachines     | EL1360                      | [af31609559](https://linux-hardware.org/?probe=af31609559) | Dec 23, 2023 |
| ASUSTek       | P6T                         | [d90adb3a12](https://linux-hardware.org/?probe=d90adb3a12) | Dec 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [da051b693c](https://linux-hardware.org/?probe=da051b693c) | Dec 23, 2023 |
| Dell          | 0FDY5C A00                  | [a3fc39604c](https://linux-hardware.org/?probe=a3fc39604c) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | [bbdb2204d8](https://linux-hardware.org/?probe=bbdb2204d8) | Dec 22, 2023 |
| Dell          | 0D6H9T A00                  | [84275b737e](https://linux-hardware.org/?probe=84275b737e) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c9bee45423](https://linux-hardware.org/?probe=c9bee45423) | Dec 22, 2023 |
| Intel         | H61                         | [72c7724ef0](https://linux-hardware.org/?probe=72c7724ef0) | Dec 22, 2023 |
| MSI           | X570-A PRO                  | [27a132c185](https://linux-hardware.org/?probe=27a132c185) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | [03ddd69e34](https://linux-hardware.org/?probe=03ddd69e34) | Dec 22, 2023 |
| MSI           | PRO Z790-A WIFI             | [8e38fb94ba](https://linux-hardware.org/?probe=8e38fb94ba) | Dec 22, 2023 |
| Dell          | 0WR7PY A03                  | [9ff527cfd0](https://linux-hardware.org/?probe=9ff527cfd0) | Dec 22, 2023 |
| HP            | 8626                        | [b04d9fcad9](https://linux-hardware.org/?probe=b04d9fcad9) | Dec 22, 2023 |
| Dell          | 0HY9JP A02                  | [6f47019169](https://linux-hardware.org/?probe=6f47019169) | Dec 22, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [8a2d46dced](https://linux-hardware.org/?probe=8a2d46dced) | Dec 22, 2023 |
| LattePanda    | Sigma                       | [09cb864933](https://linux-hardware.org/?probe=09cb864933) | Dec 22, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [2af66f541d](https://linux-hardware.org/?probe=2af66f541d) | Dec 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [3ff2f289b9](https://linux-hardware.org/?probe=3ff2f289b9) | Dec 22, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [dbc2e93666](https://linux-hardware.org/?probe=dbc2e93666) | Dec 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [628ca02992](https://linux-hardware.org/?probe=628ca02992) | Dec 21, 2023 |
| Gigabyte      | Z87-HD3                     | [49e514e9c4](https://linux-hardware.org/?probe=49e514e9c4) | Dec 21, 2023 |
| Acer          | Aspire XC-1760              | [ac3910a453](https://linux-hardware.org/?probe=ac3910a453) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | [1ba9d3bc0c](https://linux-hardware.org/?probe=1ba9d3bc0c) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | [066ebdde5b](https://linux-hardware.org/?probe=066ebdde5b) | Dec 21, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [191d4913cd](https://linux-hardware.org/?probe=191d4913cd) | Dec 21, 2023 |
| Foxconn       | 2ADA                        | [735572694e](https://linux-hardware.org/?probe=735572694e) | Dec 21, 2023 |
| HP            | 18E7                        | [ad6cf02d18](https://linux-hardware.org/?probe=ad6cf02d18) | Dec 21, 2023 |
| HP            | 18E7                        | [fdb8b2d229](https://linux-hardware.org/?probe=fdb8b2d229) | Dec 21, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [8eca3c15e7](https://linux-hardware.org/?probe=8eca3c15e7) | Dec 21, 2023 |
| ASUSTek       | Z10PG-D16 Series            | [6b3c6c4099](https://linux-hardware.org/?probe=6b3c6c4099) | Dec 21, 2023 |
| MSI           | NF725M-P43                  | [43756d6fad](https://linux-hardware.org/?probe=43756d6fad) | Dec 21, 2023 |
| ASUSTek       | M5A97 R2.0                  | [93a7029d22](https://linux-hardware.org/?probe=93a7029d22) | Dec 21, 2023 |
| Acer          | Veriton X2631G V:1.0        | [7597019eca](https://linux-hardware.org/?probe=7597019eca) | Dec 21, 2023 |
| ASUSTek       | VM40B                       | [8deb79e86e](https://linux-hardware.org/?probe=8deb79e86e) | Dec 20, 2023 |
| Gigabyte      | B560M H                     | [6e7f8b2300](https://linux-hardware.org/?probe=6e7f8b2300) | Dec 20, 2023 |
| Gigabyte      | H81M-DS2                    | [1da522781e](https://linux-hardware.org/?probe=1da522781e) | Dec 20, 2023 |
| Gigabyte      | B550M DS3H                  | [35547b20b3](https://linux-hardware.org/?probe=35547b20b3) | Dec 20, 2023 |
| MSI           | B450-A PRO MAX              | [f46e034f2c](https://linux-hardware.org/?probe=f46e034f2c) | Dec 20, 2023 |
| Dell          | 09KPNV A00                  | [e696fd9ae0](https://linux-hardware.org/?probe=e696fd9ae0) | Dec 20, 2023 |
| Dell          | 0C522T A03                  | [7cd9f2379e](https://linux-hardware.org/?probe=7cd9f2379e) | Dec 20, 2023 |
| ASUSTek       | P8Z77-M PRO                 | [58517da295](https://linux-hardware.org/?probe=58517da295) | Dec 20, 2023 |
| ASRock        | FM2A58M-HD+                 | [09ab03cdcd](https://linux-hardware.org/?probe=09ab03cdcd) | Dec 19, 2023 |
| ANGXUN        | X79-VG2 V1.3                | [532c5b5ddc](https://linux-hardware.org/?probe=532c5b5ddc) | Dec 19, 2023 |
| MSI           | B85-G43                     | [2c855d2376](https://linux-hardware.org/?probe=2c855d2376) | Dec 19, 2023 |
| Dell          | 042P49 A02                  | [11f6da5848](https://linux-hardware.org/?probe=11f6da5848) | Dec 19, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [843515c201](https://linux-hardware.org/?probe=843515c201) | Dec 19, 2023 |
| Dell          | 0C522T A03                  | [35b8611349](https://linux-hardware.org/?probe=35b8611349) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | [359af07cb2](https://linux-hardware.org/?probe=359af07cb2) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | [b4b91802b5](https://linux-hardware.org/?probe=b4b91802b5) | Dec 19, 2023 |
| MSI           | X570-A PRO                  | [3cf8d970f8](https://linux-hardware.org/?probe=3cf8d970f8) | Dec 19, 2023 |
| MSI           | A520M-A PRO                 | [5781ca34c8](https://linux-hardware.org/?probe=5781ca34c8) | Dec 19, 2023 |
| Dell          | 0Y7WYT A00                  | [705321d0b6](https://linux-hardware.org/?probe=705321d0b6) | Dec 19, 2023 |
| HP            | 3647h                       | [0e741d6d7c](https://linux-hardware.org/?probe=0e741d6d7c) | Dec 18, 2023 |
| Supermicro    | X7DWA                       | [2ea00dfda4](https://linux-hardware.org/?probe=2ea00dfda4) | Dec 18, 2023 |
| Supermicro    | X7DWA                       | [6357637f80](https://linux-hardware.org/?probe=6357637f80) | Dec 18, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [f93e198dd4](https://linux-hardware.org/?probe=f93e198dd4) | Dec 18, 2023 |
| Gigabyte      | H410M S2H V3                | [498141a78c](https://linux-hardware.org/?probe=498141a78c) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | [0cf5577833](https://linux-hardware.org/?probe=0cf5577833) | Dec 18, 2023 |
| Dell          | 06FW8P A02                  | [7b66e504eb](https://linux-hardware.org/?probe=7b66e504eb) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | [2bee7533b2](https://linux-hardware.org/?probe=2bee7533b2) | Dec 18, 2023 |
| Gigabyte      | B550 GAMING X               | [6ecd3ce2c3](https://linux-hardware.org/?probe=6ecd3ce2c3) | Dec 18, 2023 |
| ASRock        | Z370M-ITX/ac                | [0f7c6a7383](https://linux-hardware.org/?probe=0f7c6a7383) | Dec 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | [8425b10899](https://linux-hardware.org/?probe=8425b10899) | Dec 17, 2023 |
| Dell          | 07N90W A02                  | [0c471e8b44](https://linux-hardware.org/?probe=0c471e8b44) | Dec 17, 2023 |
| ASRock        | Z77 Extreme4                | [ead1dfb3ae](https://linux-hardware.org/?probe=ead1dfb3ae) | Dec 17, 2023 |
| ASRock        | H61M-VG4                    | [a845742a42](https://linux-hardware.org/?probe=a845742a42) | Dec 17, 2023 |
| MSI           | 2A9C                        | [342d099a7f](https://linux-hardware.org/?probe=342d099a7f) | Dec 17, 2023 |
| ASUSTek       | PRIME A320M-K               | [1f0e0f04f8](https://linux-hardware.org/?probe=1f0e0f04f8) | Dec 17, 2023 |
| HP            | 1790                        | [2d8c859110](https://linux-hardware.org/?probe=2d8c859110) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [8adfc82dc5](https://linux-hardware.org/?probe=8adfc82dc5) | Dec 17, 2023 |
| Dell          | 0KWVT8 A03                  | [d5632292b6](https://linux-hardware.org/?probe=d5632292b6) | Dec 17, 2023 |
| Dell          | 0KWVT8 A03                  | [6745d8d399](https://linux-hardware.org/?probe=6745d8d399) | Dec 17, 2023 |
| Gigabyte      | H77M-D3H                    | [de9dcb40ba](https://linux-hardware.org/?probe=de9dcb40ba) | Dec 17, 2023 |
| Dell          | 0PC5F7 A03                  | [b280c267db](https://linux-hardware.org/?probe=b280c267db) | Dec 17, 2023 |
| Shenzhen M... | TH80                        | [1ad9ee524d](https://linux-hardware.org/?probe=1ad9ee524d) | Dec 16, 2023 |
| Inventec      | DQ Class A02                | [73df6dfb3b](https://linux-hardware.org/?probe=73df6dfb3b) | Dec 16, 2023 |
| Gigabyte      | B85-HD3-A                   | [e3d139cdb3](https://linux-hardware.org/?probe=e3d139cdb3) | Dec 16, 2023 |
| ASUSTek       | PRIME B760-PLUS             | [a7dd86011c](https://linux-hardware.org/?probe=a7dd86011c) | Dec 16, 2023 |
| Intel         | SHARKBAY                    | [efe58ba5df](https://linux-hardware.org/?probe=efe58ba5df) | Dec 16, 2023 |
| Gigabyte      | 970A-DS3P                   | [e6019b847e](https://linux-hardware.org/?probe=e6019b847e) | Dec 16, 2023 |
| HP            | 2B05                        | [81e68a1fb8](https://linux-hardware.org/?probe=81e68a1fb8) | Dec 16, 2023 |
| HP            | 2B05                        | [2063743d90](https://linux-hardware.org/?probe=2063743d90) | Dec 16, 2023 |
| Acer          | EG43M                       | [62c8e8acf8](https://linux-hardware.org/?probe=62c8e8acf8) | Dec 16, 2023 |
| HP            | 1790                        | [9bb2d6fcb4](https://linux-hardware.org/?probe=9bb2d6fcb4) | Dec 16, 2023 |
| ASUSTek       | PRIME A320M-A               | [862ce85408](https://linux-hardware.org/?probe=862ce85408) | Dec 16, 2023 |
| Dell          | 0RT6HT A01                  | [3509be8560](https://linux-hardware.org/?probe=3509be8560) | Dec 16, 2023 |
| ASRock        | X570 Taichi                 | [6458d64d28](https://linux-hardware.org/?probe=6458d64d28) | Dec 16, 2023 |
| Gigabyte      | B85-HD3-A                   | [b60d191f59](https://linux-hardware.org/?probe=b60d191f59) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | [1fae1d3423](https://linux-hardware.org/?probe=1fae1d3423) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | [1a70a13ff4](https://linux-hardware.org/?probe=1a70a13ff4) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | [8be30808ec](https://linux-hardware.org/?probe=8be30808ec) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | [1e0ba866f7](https://linux-hardware.org/?probe=1e0ba866f7) | Dec 15, 2023 |
| Google        | Guado                       | [e981ac3399](https://linux-hardware.org/?probe=e981ac3399) | Dec 15, 2023 |
| XDO.AI        | Pantera Pico PC             | [6358b586ac](https://linux-hardware.org/?probe=6358b586ac) | Dec 15, 2023 |
| Gigabyte      | Z790 AORUS MASTER           | [6af7c135e1](https://linux-hardware.org/?probe=6af7c135e1) | Dec 15, 2023 |
| Dell          | 0NW6H5 A00                  | [eb487bbab2](https://linux-hardware.org/?probe=eb487bbab2) | Dec 14, 2023 |
| Unknown       | Unknown                     | [9fb745d9fe](https://linux-hardware.org/?probe=9fb745d9fe) | Dec 14, 2023 |
| Lenovo        | SDK0J40700 WIN              | [48c963a11d](https://linux-hardware.org/?probe=48c963a11d) | Dec 14, 2023 |
| Google        | Guado                       | [50ceaa2515](https://linux-hardware.org/?probe=50ceaa2515) | Dec 14, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [742681b576](https://linux-hardware.org/?probe=742681b576) | Dec 14, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [72cd581273](https://linux-hardware.org/?probe=72cd581273) | Dec 14, 2023 |
| XDO.AI        | Pantera Pico PC             | [fabfe15230](https://linux-hardware.org/?probe=fabfe15230) | Dec 14, 2023 |
| HC Technol... | HCAR5000-MI                 | [d4d42016ea](https://linux-hardware.org/?probe=d4d42016ea) | Dec 14, 2023 |
| Gigabyte      | H410M S2H V3                | [101f8237e0](https://linux-hardware.org/?probe=101f8237e0) | Dec 14, 2023 |
| Dell          | 0TDG4V A01                  | [6da01d5871](https://linux-hardware.org/?probe=6da01d5871) | Dec 14, 2023 |
| ASRock        | B550M Pro4                  | [9d0aff4b01](https://linux-hardware.org/?probe=9d0aff4b01) | Dec 13, 2023 |
| HP            | 83EF                        | [e2a7a03e4c](https://linux-hardware.org/?probe=e2a7a03e4c) | Dec 13, 2023 |
| HP            | 83EF                        | [d5d568c47c](https://linux-hardware.org/?probe=d5d568c47c) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [ab0ac93be6](https://linux-hardware.org/?probe=ab0ac93be6) | Dec 13, 2023 |
| HP            | 18E9                        | [ab47a5d40b](https://linux-hardware.org/?probe=ab47a5d40b) | Dec 13, 2023 |
| ASRock        | B550M Pro4                  | [e196db2480](https://linux-hardware.org/?probe=e196db2480) | Dec 13, 2023 |
| Gigabyte      | H410M S2H V3                | [e198c73fa2](https://linux-hardware.org/?probe=e198c73fa2) | Dec 13, 2023 |
| Dell          | 0K240Y A01                  | [227af40d05](https://linux-hardware.org/?probe=227af40d05) | Dec 13, 2023 |
| ASUSTek       | Basswood3G                  | [f686ec5ba9](https://linux-hardware.org/?probe=f686ec5ba9) | Dec 13, 2023 |
| Unknown       | Unknown                     | [fd405f79f2](https://linux-hardware.org/?probe=fd405f79f2) | Dec 13, 2023 |
| ASRock        | 970 Extreme4                | [ce858f7f7c](https://linux-hardware.org/?probe=ce858f7f7c) | Dec 13, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [01f7be08ae](https://linux-hardware.org/?probe=01f7be08ae) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4f1419b521](https://linux-hardware.org/?probe=4f1419b521) | Dec 12, 2023 |
| HP            | 3048h                       | [bb95017425](https://linux-hardware.org/?probe=bb95017425) | Dec 12, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | [eadc049e56](https://linux-hardware.org/?probe=eadc049e56) | Dec 12, 2023 |
| Gigabyte      | H310M H x.x                 | [bcf9fba46f](https://linux-hardware.org/?probe=bcf9fba46f) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | [2f96568c78](https://linux-hardware.org/?probe=2f96568c78) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | [68fe94d3be](https://linux-hardware.org/?probe=68fe94d3be) | Dec 12, 2023 |
| Dell          | 0M5DCD A00                  | [98f2d76ef0](https://linux-hardware.org/?probe=98f2d76ef0) | Dec 12, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [c4de324273](https://linux-hardware.org/?probe=c4de324273) | Dec 12, 2023 |
| MSI           | A320M PRO-VD/S              | [c2a6947086](https://linux-hardware.org/?probe=c2a6947086) | Dec 12, 2023 |
| HC Technol... | HCAR5000-MI                 | [d5cb60727d](https://linux-hardware.org/?probe=d5cb60727d) | Dec 12, 2023 |
| MSI           | B450 TOMAHAWK               | [8e66dfbc28](https://linux-hardware.org/?probe=8e66dfbc28) | Dec 12, 2023 |
| HP            | 0AECh D                     | [b1856b493c](https://linux-hardware.org/?probe=b1856b493c) | Dec 12, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | [06f64404ec](https://linux-hardware.org/?probe=06f64404ec) | Dec 12, 2023 |
| Gigabyte      | A520M H                     | [e72a787933](https://linux-hardware.org/?probe=e72a787933) | Dec 12, 2023 |
| ASRock        | B450M-HDV R4.0              | [ee39e0724c](https://linux-hardware.org/?probe=ee39e0724c) | Dec 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | [0d3866e04a](https://linux-hardware.org/?probe=0d3866e04a) | Dec 11, 2023 |
| Dell          | 0Y2YM6 A01                  | [c3fee04c74](https://linux-hardware.org/?probe=c3fee04c74) | Dec 11, 2023 |
| Dell          | 07VWPG A01                  | [a9ad39cd38](https://linux-hardware.org/?probe=a9ad39cd38) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [e3afd2e002](https://linux-hardware.org/?probe=e3afd2e002) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [656bfe20f4](https://linux-hardware.org/?probe=656bfe20f4) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [b1c994920c](https://linux-hardware.org/?probe=b1c994920c) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [cc7c14dd72](https://linux-hardware.org/?probe=cc7c14dd72) | Dec 11, 2023 |
| MSI           | Z490-A PRO                  | [bd1772e0a0](https://linux-hardware.org/?probe=bd1772e0a0) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [b7c06bf365](https://linux-hardware.org/?probe=b7c06bf365) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [8badd81a74](https://linux-hardware.org/?probe=8badd81a74) | Dec 11, 2023 |
| ASRock        | B85M Pro4                   | [8a11fe8107](https://linux-hardware.org/?probe=8a11fe8107) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [448dc8ed72](https://linux-hardware.org/?probe=448dc8ed72) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [472c013f53](https://linux-hardware.org/?probe=472c013f53) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [8cb24408c9](https://linux-hardware.org/?probe=8cb24408c9) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [df2e9cf858](https://linux-hardware.org/?probe=df2e9cf858) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [c8d223020d](https://linux-hardware.org/?probe=c8d223020d) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [70364f28ab](https://linux-hardware.org/?probe=70364f28ab) | Dec 11, 2023 |
| Gigabyte      | D-700                       | [18e3ee84cc](https://linux-hardware.org/?probe=18e3ee84cc) | Dec 11, 2023 |
| Intel         | H61                         | [611b51b6c1](https://linux-hardware.org/?probe=611b51b6c1) | Dec 11, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [32d436e221](https://linux-hardware.org/?probe=32d436e221) | Dec 11, 2023 |
| Gigabyte      | EP41-UD3L                   | [9b40e5889d](https://linux-hardware.org/?probe=9b40e5889d) | Dec 10, 2023 |
| Dell          | 0C522T A03                  | [11f857231b](https://linux-hardware.org/?probe=11f857231b) | Dec 10, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [237db70b40](https://linux-hardware.org/?probe=237db70b40) | Dec 10, 2023 |
| ASRock        | A520M-HVS                   | [5d07d03602](https://linux-hardware.org/?probe=5d07d03602) | Dec 10, 2023 |
| Pegatron      | IPMH61P1                    | [0d0474a798](https://linux-hardware.org/?probe=0d0474a798) | Dec 10, 2023 |
| ASUSTek       | PRIME B250M-A               | [1eaf3dd454](https://linux-hardware.org/?probe=1eaf3dd454) | Dec 10, 2023 |
| Dell          | 0TP406                      | [1b81a10a36](https://linux-hardware.org/?probe=1b81a10a36) | Dec 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [aa1aa7d695](https://linux-hardware.org/?probe=aa1aa7d695) | Dec 10, 2023 |
| Pegatron      | 2AC3                        | [3831586b47](https://linux-hardware.org/?probe=3831586b47) | Dec 10, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [e87dcf9ee2](https://linux-hardware.org/?probe=e87dcf9ee2) | Dec 10, 2023 |
| ASRock        | H61M-DGS                    | [d49b26fe0c](https://linux-hardware.org/?probe=d49b26fe0c) | Dec 10, 2023 |
| Inventec      | DQ Class A02                | [8e1c466924](https://linux-hardware.org/?probe=8e1c466924) | Dec 09, 2023 |
| ASRock        | H61M-DGS                    | [f8bd255155](https://linux-hardware.org/?probe=f8bd255155) | Dec 09, 2023 |
| Acer          | Veriton X2631G V:1.0        | [1465cf0eac](https://linux-hardware.org/?probe=1465cf0eac) | Dec 09, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [af3f6d16ac](https://linux-hardware.org/?probe=af3f6d16ac) | Dec 09, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [5121b6a20c](https://linux-hardware.org/?probe=5121b6a20c) | Dec 09, 2023 |
| MSI           | B150M PRO-VDH               | [e35af0e70a](https://linux-hardware.org/?probe=e35af0e70a) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [237110c8c0](https://linux-hardware.org/?probe=237110c8c0) | Dec 09, 2023 |
| Biostar       | A10N-8800E                  | [283ae39c42](https://linux-hardware.org/?probe=283ae39c42) | Dec 09, 2023 |
| Gigabyte      | B550M K                     | [bbf66f105d](https://linux-hardware.org/?probe=bbf66f105d) | Dec 09, 2023 |
| Gigabyte      | B550M K                     | [e44ea6cf67](https://linux-hardware.org/?probe=e44ea6cf67) | Dec 09, 2023 |
| Gigabyte      | Z87-HD3                     | [9f3fb37b64](https://linux-hardware.org/?probe=9f3fb37b64) | Dec 09, 2023 |
| Lenovo        | ThinkCentre M58p 6234AE5    | [4cf3efef96](https://linux-hardware.org/?probe=4cf3efef96) | Dec 09, 2023 |
| Gigabyte      | Z87-HD3                     | [26c99ed573](https://linux-hardware.org/?probe=26c99ed573) | Dec 09, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [22d34b64f2](https://linux-hardware.org/?probe=22d34b64f2) | Dec 09, 2023 |
| MSI           | B150M PRO-VDH               | [634d1d56b8](https://linux-hardware.org/?probe=634d1d56b8) | Dec 09, 2023 |
| Dell          | 0C522T A03                  | [3c06d9b7a8](https://linux-hardware.org/?probe=3c06d9b7a8) | Dec 09, 2023 |
| Intel         | DH67CL AAG10212-206         | [957289310d](https://linux-hardware.org/?probe=957289310d) | Dec 08, 2023 |
| ASRock        | H510M-ITX/ac                | [4850c05764](https://linux-hardware.org/?probe=4850c05764) | Dec 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [69df0251d9](https://linux-hardware.org/?probe=69df0251d9) | Dec 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [56eae53402](https://linux-hardware.org/?probe=56eae53402) | Dec 08, 2023 |
| MSI           | B450 TOMAHAWK               | [254b936002](https://linux-hardware.org/?probe=254b936002) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [8198e47786](https://linux-hardware.org/?probe=8198e47786) | Dec 08, 2023 |
| Gigabyte      | B85M-HD3                    | [b4da4c1d8a](https://linux-hardware.org/?probe=b4da4c1d8a) | Dec 07, 2023 |
| Biostar       | A10N-8800E                  | [b56d3e163b](https://linux-hardware.org/?probe=b56d3e163b) | Dec 07, 2023 |
| HP            | 8184 X4                     | [bad08bc9a0](https://linux-hardware.org/?probe=bad08bc9a0) | Dec 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [16b14ad0a7](https://linux-hardware.org/?probe=16b14ad0a7) | Dec 07, 2023 |
| HP            | 18E9                        | [80f4acdcfd](https://linux-hardware.org/?probe=80f4acdcfd) | Dec 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [04dd7cde77](https://linux-hardware.org/?probe=04dd7cde77) | Dec 07, 2023 |
| Dell          | 0NK5PH A00                  | [d96cb11edc](https://linux-hardware.org/?probe=d96cb11edc) | Dec 07, 2023 |
| Pegatron      | IPMH61P1                    | [264229998e](https://linux-hardware.org/?probe=264229998e) | Dec 07, 2023 |
| Gigabyte      | GA-MA770-DS3                | [66917779ad](https://linux-hardware.org/?probe=66917779ad) | Dec 07, 2023 |
| HP            | 09F8h                       | [c988ff1e96](https://linux-hardware.org/?probe=c988ff1e96) | Dec 07, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [5f96473345](https://linux-hardware.org/?probe=5f96473345) | Dec 07, 2023 |
| Dell          | 0GWHMW A00                  | [7843d89bd3](https://linux-hardware.org/?probe=7843d89bd3) | Dec 07, 2023 |
| ASUSTek       | PRIME B650M-A AX II         | [68ae754b57](https://linux-hardware.org/?probe=68ae754b57) | Dec 07, 2023 |
| Gigabyte      | G1.Sniper M3                | [d81e8e0452](https://linux-hardware.org/?probe=d81e8e0452) | Dec 07, 2023 |
| Gigabyte      | G1.Sniper M3                | [ac25bf99a5](https://linux-hardware.org/?probe=ac25bf99a5) | Dec 07, 2023 |
| Dell          | 0DFRFW A01                  | [766521b0e1](https://linux-hardware.org/?probe=766521b0e1) | Dec 06, 2023 |
| HP            | 0AECh D                     | [d58cc2f609](https://linux-hardware.org/?probe=d58cc2f609) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [2d3f4ca82c](https://linux-hardware.org/?probe=2d3f4ca82c) | Dec 06, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1337f45be](https://linux-hardware.org/?probe=d1337f45be) | Dec 06, 2023 |
| Gigabyte      | B450M DS3H V2               | [f2a72d7b29](https://linux-hardware.org/?probe=f2a72d7b29) | Dec 06, 2023 |
| ALDO          | C2016-BSWI-D2               | [4dec414c2e](https://linux-hardware.org/?probe=4dec414c2e) | Dec 06, 2023 |
| Dell          | 0RY007                      | [2c93573995](https://linux-hardware.org/?probe=2c93573995) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | [30c6080de4](https://linux-hardware.org/?probe=30c6080de4) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | [0226f5545c](https://linux-hardware.org/?probe=0226f5545c) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | [cf63284103](https://linux-hardware.org/?probe=cf63284103) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | [6d0a010766](https://linux-hardware.org/?probe=6d0a010766) | Dec 06, 2023 |
| Supermicro    | X9DRW                       | [485f869e9b](https://linux-hardware.org/?probe=485f869e9b) | Dec 06, 2023 |
| HP            | 82F1                        | [3a292e8aaa](https://linux-hardware.org/?probe=3a292e8aaa) | Dec 06, 2023 |
| Dell          | 0P42M6 A01                  | [2deb37f773](https://linux-hardware.org/?probe=2deb37f773) | Dec 06, 2023 |
| Supermicro    | X10DRL-i                    | [f30d1a0a40](https://linux-hardware.org/?probe=f30d1a0a40) | Dec 06, 2023 |
| Supermicro    | X10DRL-i                    | [7f6c70bab0](https://linux-hardware.org/?probe=7f6c70bab0) | Dec 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [c7a3277bfa](https://linux-hardware.org/?probe=c7a3277bfa) | Dec 06, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [1b3a42caac](https://linux-hardware.org/?probe=1b3a42caac) | Dec 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [9b6cdd96f4](https://linux-hardware.org/?probe=9b6cdd96f4) | Dec 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [3176cf1b45](https://linux-hardware.org/?probe=3176cf1b45) | Dec 06, 2023 |
| HP            | 2AF7                        | [4d98ac755f](https://linux-hardware.org/?probe=4d98ac755f) | Dec 06, 2023 |
| Unknown       | G-GLK01                     | [5c5efbafff](https://linux-hardware.org/?probe=5c5efbafff) | Dec 06, 2023 |
| Dell          | 0Y7WYT A00                  | [a59c9d08c1](https://linux-hardware.org/?probe=a59c9d08c1) | Dec 06, 2023 |
| NEC Infron... | MS-9888 10h                 | [8a1a2b9976](https://linux-hardware.org/?probe=8a1a2b9976) | Dec 05, 2023 |
| HC Technol... | HCAR5000-MI                 | [3f2a30851e](https://linux-hardware.org/?probe=3f2a30851e) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [5e59f15fed](https://linux-hardware.org/?probe=5e59f15fed) | Dec 05, 2023 |
| HP            | 3646h                       | [df62144cda](https://linux-hardware.org/?probe=df62144cda) | Dec 05, 2023 |
| HP            | 339A                        | [53b6aa6808](https://linux-hardware.org/?probe=53b6aa6808) | Dec 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6d790b9d8c](https://linux-hardware.org/?probe=6d790b9d8c) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [fa61806ea8](https://linux-hardware.org/?probe=fa61806ea8) | Dec 05, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [ee36539c94](https://linux-hardware.org/?probe=ee36539c94) | Dec 05, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [599d20e4ef](https://linux-hardware.org/?probe=599d20e4ef) | Dec 04, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [bab7262ca5](https://linux-hardware.org/?probe=bab7262ca5) | Dec 04, 2023 |
| Supermicro    | X10DRG-Q                    | [5844ee0f43](https://linux-hardware.org/?probe=5844ee0f43) | Dec 04, 2023 |
| ASUSTek       | M4A78LT-M                   | [9edd2d878e](https://linux-hardware.org/?probe=9edd2d878e) | Dec 04, 2023 |
| Supermicro    | X10DRG-Q                    | [175bbb55cb](https://linux-hardware.org/?probe=175bbb55cb) | Dec 04, 2023 |
| Foxconn       | 2AB1                        | [93bbf17266](https://linux-hardware.org/?probe=93bbf17266) | Dec 04, 2023 |
| MSI           | Z97 GAMING 7                | [887cbb52f3](https://linux-hardware.org/?probe=887cbb52f3) | Dec 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | [cea029e467](https://linux-hardware.org/?probe=cea029e467) | Dec 04, 2023 |
| ZOTAC         | NM10                        | [a567bbf0a7](https://linux-hardware.org/?probe=a567bbf0a7) | Dec 04, 2023 |
| ASRock        | H97 Performance             | [dc36b5ee77](https://linux-hardware.org/?probe=dc36b5ee77) | Dec 04, 2023 |
| Unknown       | Unknown                     | [18e4bdaa86](https://linux-hardware.org/?probe=18e4bdaa86) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6c24e26ef9](https://linux-hardware.org/?probe=6c24e26ef9) | Dec 03, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [6e9e9a487a](https://linux-hardware.org/?probe=6e9e9a487a) | Dec 03, 2023 |
| MSI           | A75MA-G55                   | [02a8179117](https://linux-hardware.org/?probe=02a8179117) | Dec 03, 2023 |
| HP            | 2B46                        | [5bfce44b96](https://linux-hardware.org/?probe=5bfce44b96) | Dec 03, 2023 |
| Google        | Wukong                      | [e665343907](https://linux-hardware.org/?probe=e665343907) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | [4cb46d807d](https://linux-hardware.org/?probe=4cb46d807d) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | [0c74d4b343](https://linux-hardware.org/?probe=0c74d4b343) | Dec 03, 2023 |
| HP            | ProLiant ML110 Gen9         | [c5f6a282c6](https://linux-hardware.org/?probe=c5f6a282c6) | Dec 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [1d3323974f](https://linux-hardware.org/?probe=1d3323974f) | Dec 03, 2023 |
| Shuttle       | DS10U                       | [4e3fa0f845](https://linux-hardware.org/?probe=4e3fa0f845) | Dec 02, 2023 |
| ASUSTek       | P9X79                       | [9cdf3ecc77](https://linux-hardware.org/?probe=9cdf3ecc77) | Dec 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | [5923988290](https://linux-hardware.org/?probe=5923988290) | Dec 02, 2023 |
| ASRock        | AB350 Pro4                  | [61e9871a33](https://linux-hardware.org/?probe=61e9871a33) | Dec 02, 2023 |
| HP            | 3398                        | [26c9b1fa25](https://linux-hardware.org/?probe=26c9b1fa25) | Dec 01, 2023 |
| ASRock        | 970 Extreme4                | [4cbc340e7c](https://linux-hardware.org/?probe=4cbc340e7c) | Dec 01, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [50332d509a](https://linux-hardware.org/?probe=50332d509a) | Dec 01, 2023 |
| Gigabyte      | B550M DS3H AC               | [bc4ff37548](https://linux-hardware.org/?probe=bc4ff37548) | Dec 01, 2023 |
| Dell          | 09KPNV A01                  | [e7cb2d834a](https://linux-hardware.org/?probe=e7cb2d834a) | Dec 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [89ec59d64e](https://linux-hardware.org/?probe=89ec59d64e) | Dec 01, 2023 |
| HP            | 2B0B 100                    | [48cb125554](https://linux-hardware.org/?probe=48cb125554) | Dec 01, 2023 |
| ASRock        | B450M-HDV                   | [d59279f095](https://linux-hardware.org/?probe=d59279f095) | Dec 01, 2023 |
| ASUSTek       | M5A78L-M LX3                | [41ae74c0ef](https://linux-hardware.org/?probe=41ae74c0ef) | Dec 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [dd82ddf299](https://linux-hardware.org/?probe=dd82ddf299) | Dec 01, 2023 |
| Dell          | 0C522T A03                  | [988e96f53c](https://linux-hardware.org/?probe=988e96f53c) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [96a30d5a91](https://linux-hardware.org/?probe=96a30d5a91) | Nov 30, 2023 |
| Kllisre       | X79 V2.72S                  | [cd66ba8786](https://linux-hardware.org/?probe=cd66ba8786) | Nov 30, 2023 |
| ASUSTek       | CG5275                      | [13c8d80b5d](https://linux-hardware.org/?probe=13c8d80b5d) | Nov 29, 2023 |
| MSI           | B550-A PRO                  | [3bbd848840](https://linux-hardware.org/?probe=3bbd848840) | Nov 29, 2023 |
| Shenzhen M... | F6BFC                       | [1074904ba9](https://linux-hardware.org/?probe=1074904ba9) | Nov 29, 2023 |
| Foxconn       | nT-330i                     | [e20a015b3a](https://linux-hardware.org/?probe=e20a015b3a) | Nov 29, 2023 |
| HP            | 1905                        | [8d1dfc94c1](https://linux-hardware.org/?probe=8d1dfc94c1) | Nov 29, 2023 |
| Gigabyte      | F2A88X-D3H                  | [15c78cff63](https://linux-hardware.org/?probe=15c78cff63) | Nov 29, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [e6c589b9b0](https://linux-hardware.org/?probe=e6c589b9b0) | Nov 29, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [62cb0079ed](https://linux-hardware.org/?probe=62cb0079ed) | Nov 29, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [da395dd09e](https://linux-hardware.org/?probe=da395dd09e) | Nov 28, 2023 |
| Pegatron      | EVANS                       | [0d15cfcfb2](https://linux-hardware.org/?probe=0d15cfcfb2) | Nov 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [ee5fe89209](https://linux-hardware.org/?probe=ee5fe89209) | Nov 28, 2023 |
| HP            | 18E5                        | [a078eaa1d4](https://linux-hardware.org/?probe=a078eaa1d4) | Nov 28, 2023 |
| ASRock        | H310CM-HDV/M.2              | [72f7a18db5](https://linux-hardware.org/?probe=72f7a18db5) | Nov 28, 2023 |
| HP            | 8055                        | [a35b553ba1](https://linux-hardware.org/?probe=a35b553ba1) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [33388f794b](https://linux-hardware.org/?probe=33388f794b) | Nov 28, 2023 |
| Unknown       | Unknown                     | [34cbcf6478](https://linux-hardware.org/?probe=34cbcf6478) | Nov 28, 2023 |
| Dell          | 06X1TJ A00                  | [4819314a84](https://linux-hardware.org/?probe=4819314a84) | Nov 27, 2023 |
| Intel         | JSL MRD                     | [6c635f4665](https://linux-hardware.org/?probe=6c635f4665) | Nov 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [330921f980](https://linux-hardware.org/?probe=330921f980) | Nov 27, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [85217c44b9](https://linux-hardware.org/?probe=85217c44b9) | Nov 27, 2023 |
| Intel         | HM570                       | [69eb6aa616](https://linux-hardware.org/?probe=69eb6aa616) | Nov 27, 2023 |
| Supermicro    | X10DRL-i                    | [5ef70291dd](https://linux-hardware.org/?probe=5ef70291dd) | Nov 27, 2023 |
| Supermicro    | X10DRU-i+A                  | [1dc89f1473](https://linux-hardware.org/?probe=1dc89f1473) | Nov 27, 2023 |
| Supermicro    | X9DRW                       | [86356d229c](https://linux-hardware.org/?probe=86356d229c) | Nov 27, 2023 |
| Supermicro    | X10DRL-i                    | [258e338541](https://linux-hardware.org/?probe=258e338541) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | [dd750184ff](https://linux-hardware.org/?probe=dd750184ff) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | [275dfaabe4](https://linux-hardware.org/?probe=275dfaabe4) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | [7a9789da62](https://linux-hardware.org/?probe=7a9789da62) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | [792780c033](https://linux-hardware.org/?probe=792780c033) | Nov 27, 2023 |
| Supermicro    | X9DRW                       | [c764c8a98e](https://linux-hardware.org/?probe=c764c8a98e) | Nov 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [7d36a1431f](https://linux-hardware.org/?probe=7d36a1431f) | Nov 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [c594f5ae7a](https://linux-hardware.org/?probe=c594f5ae7a) | Nov 27, 2023 |
| Gigabyte      | Z490 UD                     | [38d2e85b40](https://linux-hardware.org/?probe=38d2e85b40) | Nov 27, 2023 |
| ASUSTek       | P6T SE                      | [caddbf7d43](https://linux-hardware.org/?probe=caddbf7d43) | Nov 27, 2023 |
| Dell          | 0VNM11 A01                  | [63c8ac9339](https://linux-hardware.org/?probe=63c8ac9339) | Nov 27, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [59d1928371](https://linux-hardware.org/?probe=59d1928371) | Nov 27, 2023 |
| Gigabyte      | Z370N WIFI-CF               | [9704afc74e](https://linux-hardware.org/?probe=9704afc74e) | Nov 27, 2023 |
| ASRock        | A320M-HD                    | [1138c4c71b](https://linux-hardware.org/?probe=1138c4c71b) | Nov 27, 2023 |
| Intel         | HM570                       | [1cb9f8c891](https://linux-hardware.org/?probe=1cb9f8c891) | Nov 27, 2023 |
| Intel         | H61                         | [5146767aa6](https://linux-hardware.org/?probe=5146767aa6) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [c090300c01](https://linux-hardware.org/?probe=c090300c01) | Nov 26, 2023 |
| Gigabyte      | GA-970A-UD3                 | [203375fd6b](https://linux-hardware.org/?probe=203375fd6b) | Nov 26, 2023 |
| Intel         | B75                         | [fab278b6c3](https://linux-hardware.org/?probe=fab278b6c3) | Nov 26, 2023 |
| ASUSTek       | PRIME X470-PRO              | [47ec694370](https://linux-hardware.org/?probe=47ec694370) | Nov 26, 2023 |
| Dell          | 0NK5PH A00                  | [ed6b4827c0](https://linux-hardware.org/?probe=ed6b4827c0) | Nov 26, 2023 |
| BCM           | RX67Q                       | [59c8825b99](https://linux-hardware.org/?probe=59c8825b99) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [d3e69f25a6](https://linux-hardware.org/?probe=d3e69f25a6) | Nov 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [06a2e5b5a8](https://linux-hardware.org/?probe=06a2e5b5a8) | Nov 26, 2023 |
| Dell          | 0K240Y A01                  | [ac50bb87af](https://linux-hardware.org/?probe=ac50bb87af) | Nov 26, 2023 |
| Dell          | 0GYT9V A00                  | [a0fe7b3987](https://linux-hardware.org/?probe=a0fe7b3987) | Nov 26, 2023 |
| AZW           | MINI S 10                   | [32c65d600d](https://linux-hardware.org/?probe=32c65d600d) | Nov 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [a41a3d9679](https://linux-hardware.org/?probe=a41a3d9679) | Nov 26, 2023 |
| Gigabyte      | GA-970A-UD3                 | [6505e0c278](https://linux-hardware.org/?probe=6505e0c278) | Nov 26, 2023 |
| Gigabyte      | Z170X-Gaming 5              | [555e8e34b6](https://linux-hardware.org/?probe=555e8e34b6) | Nov 26, 2023 |
| Gigabyte      | Z170X-Gaming 5              | [b153aa9661](https://linux-hardware.org/?probe=b153aa9661) | Nov 26, 2023 |
| Foxconn       | H61MXT1/F2/-S/-V            | [0529750c82](https://linux-hardware.org/?probe=0529750c82) | Nov 25, 2023 |
| ASUSTek       | PRIME A320M-K               | [3ff2b07867](https://linux-hardware.org/?probe=3ff2b07867) | Nov 25, 2023 |
| Dell          | 0RT6HT A01                  | [aedd0fa212](https://linux-hardware.org/?probe=aedd0fa212) | Nov 25, 2023 |
| MSI           | Z87-G41 PC Mate             | [cff699d67d](https://linux-hardware.org/?probe=cff699d67d) | Nov 25, 2023 |
| Dell          | 0TDG4V A01                  | [f8200e619a](https://linux-hardware.org/?probe=f8200e619a) | Nov 25, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e7d72eaf1d](https://linux-hardware.org/?probe=e7d72eaf1d) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a727d2b744](https://linux-hardware.org/?probe=a727d2b744) | Nov 25, 2023 |
| ASRock        | AB350 Pro4                  | [0a3b2f3f70](https://linux-hardware.org/?probe=0a3b2f3f70) | Nov 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [436499a8a7](https://linux-hardware.org/?probe=436499a8a7) | Nov 25, 2023 |
| ASRock        | Z370 Killer SLI/ac          | [c2d9f4aefb](https://linux-hardware.org/?probe=c2d9f4aefb) | Nov 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | [fb9766adc5](https://linux-hardware.org/?probe=fb9766adc5) | Nov 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [dcc7dca975](https://linux-hardware.org/?probe=dcc7dca975) | Nov 24, 2023 |
| ASUSTek       | P8Z77-V LX                  | [f4a77c64b0](https://linux-hardware.org/?probe=f4a77c64b0) | Nov 24, 2023 |
| HP            | 2B0B 100                    | [908fb46664](https://linux-hardware.org/?probe=908fb46664) | Nov 24, 2023 |
| HP            | 339A                        | [3168ba2168](https://linux-hardware.org/?probe=3168ba2168) | Nov 24, 2023 |
| Dell          | 0TP406                      | [cc0c592ca4](https://linux-hardware.org/?probe=cc0c592ca4) | Nov 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [5417165a43](https://linux-hardware.org/?probe=5417165a43) | Nov 24, 2023 |
| Supermicro    | X10DAI                      | [00b8c3c935](https://linux-hardware.org/?probe=00b8c3c935) | Nov 23, 2023 |
| AZW           | SEi V1.0                    | [d18296a25c](https://linux-hardware.org/?probe=d18296a25c) | Nov 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [b98f204f02](https://linux-hardware.org/?probe=b98f204f02) | Nov 23, 2023 |
| MSI           | Z87-G41 PC Mate             | [ae2a4ee822](https://linux-hardware.org/?probe=ae2a4ee822) | Nov 23, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d4a222fa3e](https://linux-hardware.org/?probe=d4a222fa3e) | Nov 23, 2023 |
| ASUSTek       | P6T SE                      | [60e24166f1](https://linux-hardware.org/?probe=60e24166f1) | Nov 23, 2023 |
| Gigabyte      | H310M H x.x                 | [b1d5cf3254](https://linux-hardware.org/?probe=b1d5cf3254) | Nov 23, 2023 |
| Gigabyte      | X99-UD4-CF                  | [d71110004d](https://linux-hardware.org/?probe=d71110004d) | Nov 23, 2023 |
| AZW           | Green G4 10                 | [e41477f9c4](https://linux-hardware.org/?probe=e41477f9c4) | Nov 23, 2023 |
| ASUSTek       | Q87T                        | [9f4fa65adc](https://linux-hardware.org/?probe=9f4fa65adc) | Nov 23, 2023 |
| ASUSTek       | Q87T                        | [2b57cf5c8e](https://linux-hardware.org/?probe=2b57cf5c8e) | Nov 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [70c262ab30](https://linux-hardware.org/?probe=70c262ab30) | Nov 23, 2023 |
| Gigabyte      | Z68AP-D3                    | [38521acb5a](https://linux-hardware.org/?probe=38521acb5a) | Nov 23, 2023 |
| ASRock        | Z690M-ITX/ax                | [94ad5ba24d](https://linux-hardware.org/?probe=94ad5ba24d) | Nov 23, 2023 |
| ASRock        | B450M Pro4                  | [e9faa52e9c](https://linux-hardware.org/?probe=e9faa52e9c) | Nov 23, 2023 |
| MSI           | H81M-E33                    | [590f44bb87](https://linux-hardware.org/?probe=590f44bb87) | Nov 22, 2023 |
| ASRock        | J4105-ITX                   | [d5a155c906](https://linux-hardware.org/?probe=d5a155c906) | Nov 22, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [67293d8013](https://linux-hardware.org/?probe=67293d8013) | Nov 22, 2023 |
| Gigabyte      | 970A-DS3P                   | [5546fbf0d2](https://linux-hardware.org/?probe=5546fbf0d2) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [60b99664ff](https://linux-hardware.org/?probe=60b99664ff) | Nov 22, 2023 |
| ASRock        | FM2A58M-VG3+                | [df8c7b0bdb](https://linux-hardware.org/?probe=df8c7b0bdb) | Nov 22, 2023 |
| Biostar       | H81MHV3 5.0                 | [3643a6597c](https://linux-hardware.org/?probe=3643a6597c) | Nov 22, 2023 |
| ASRock        | A320M-HDV R4.0              | [794cc91e17](https://linux-hardware.org/?probe=794cc91e17) | Nov 22, 2023 |
| HP            | 1998                        | [260f73efb3](https://linux-hardware.org/?probe=260f73efb3) | Nov 22, 2023 |
| Gigabyte      | GB-BRR3H-4300               | [5850b8f7b8](https://linux-hardware.org/?probe=5850b8f7b8) | Nov 22, 2023 |
| MSI           | PRO Z790-A WIFI             | [4949a4bc03](https://linux-hardware.org/?probe=4949a4bc03) | Nov 22, 2023 |
| MSI           | PRO Z790-A WIFI             | [e5b0fd761f](https://linux-hardware.org/?probe=e5b0fd761f) | Nov 22, 2023 |
| HP            | 1998                        | [cc59ee230b](https://linux-hardware.org/?probe=cc59ee230b) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [205b0b2438](https://linux-hardware.org/?probe=205b0b2438) | Nov 22, 2023 |
| AZW           | Green G5                    | [ad48753316](https://linux-hardware.org/?probe=ad48753316) | Nov 22, 2023 |
| Supermicro    | X10DRU-i+A                  | [bcefaeb3bc](https://linux-hardware.org/?probe=bcefaeb3bc) | Nov 21, 2023 |
| Foxconn       | 2ABF                        | [c05c0dccd3](https://linux-hardware.org/?probe=c05c0dccd3) | Nov 21, 2023 |
| Foxconn       | 2ABF                        | [043a7040bc](https://linux-hardware.org/?probe=043a7040bc) | Nov 21, 2023 |
| Gigabyte      | B550M DS3H                  | [c1f0bdaf54](https://linux-hardware.org/?probe=c1f0bdaf54) | Nov 21, 2023 |
| Dell          | 062TCH A00                  | [6df960f264](https://linux-hardware.org/?probe=6df960f264) | Nov 21, 2023 |
| ASUSTek       | B150M-ET M2 SERIES          | [a999563329](https://linux-hardware.org/?probe=a999563329) | Nov 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [b29d72095f](https://linux-hardware.org/?probe=b29d72095f) | Nov 20, 2023 |
| HP            | 1905                        | [7f22b93c4b](https://linux-hardware.org/?probe=7f22b93c4b) | Nov 20, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.309     | [5372788890](https://linux-hardware.org/?probe=5372788890) | Nov 20, 2023 |
| Dell          | 062TCH A00                  | [895c93e639](https://linux-hardware.org/?probe=895c93e639) | Nov 20, 2023 |
| Biostar       | Z790 VALKYRIE               | [b052717bb5](https://linux-hardware.org/?probe=b052717bb5) | Nov 20, 2023 |
| ASRock        | H81M-ITX/WiFi               | [e4b1bf4519](https://linux-hardware.org/?probe=e4b1bf4519) | Nov 20, 2023 |
| MSI           | PRO B550M-VC WIFI           | [6d0e282cad](https://linux-hardware.org/?probe=6d0e282cad) | Nov 20, 2023 |
| MSI           | PRO B550M-VC WIFI           | [5df0fefadc](https://linux-hardware.org/?probe=5df0fefadc) | Nov 20, 2023 |
| Gigabyte      | H81M-HD2                    | [a89f5cdc65](https://linux-hardware.org/?probe=a89f5cdc65) | Nov 20, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [d5a1fce5c0](https://linux-hardware.org/?probe=d5a1fce5c0) | Nov 19, 2023 |
| Gigabyte      | GA-790XTA-UD4               | [142c93b927](https://linux-hardware.org/?probe=142c93b927) | Nov 19, 2023 |
| HP            | 0AECh D                     | [208a7b27ab](https://linux-hardware.org/?probe=208a7b27ab) | Nov 19, 2023 |
| ASUSTek       | M4A87TD/USB3                | [1c63aea539](https://linux-hardware.org/?probe=1c63aea539) | Nov 19, 2023 |
| Lenovo        | 30C7 SDK0K13468 WIN 3273... | [27b54b9945](https://linux-hardware.org/?probe=27b54b9945) | Nov 19, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [8f389f95a6](https://linux-hardware.org/?probe=8f389f95a6) | Nov 19, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [8f99d241f8](https://linux-hardware.org/?probe=8f99d241f8) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [e5d2cc7fcd](https://linux-hardware.org/?probe=e5d2cc7fcd) | Nov 19, 2023 |
| Dell          | 0TDG4V A01                  | [737ddab002](https://linux-hardware.org/?probe=737ddab002) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [ab7e55f5b9](https://linux-hardware.org/?probe=ab7e55f5b9) | Nov 19, 2023 |
| HP            | 1905                        | [19cc0187db](https://linux-hardware.org/?probe=19cc0187db) | Nov 19, 2023 |
| ASUSTek       | P7H55                       | [cd5e7b0924](https://linux-hardware.org/?probe=cd5e7b0924) | Nov 18, 2023 |
| Gigabyte      | B360HD3                     | [281c4b4ac5](https://linux-hardware.org/?probe=281c4b4ac5) | Nov 18, 2023 |
| ASUSTek       | A88X-PRO                    | [3fb9313a57](https://linux-hardware.org/?probe=3fb9313a57) | Nov 18, 2023 |
| AZW           | EQ                          | [19fa22ee5a](https://linux-hardware.org/?probe=19fa22ee5a) | Nov 18, 2023 |
| Inventec      | D CLASS A02                 | [ac41b7769d](https://linux-hardware.org/?probe=ac41b7769d) | Nov 18, 2023 |
| ASUSTek       | M2N68 Plus                  | [881ae0051a](https://linux-hardware.org/?probe=881ae0051a) | Nov 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [37139a6fd4](https://linux-hardware.org/?probe=37139a6fd4) | Nov 18, 2023 |
| ASRock        | AB350 Gaming K4             | [281925660d](https://linux-hardware.org/?probe=281925660d) | Nov 18, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [bfbed17470](https://linux-hardware.org/?probe=bfbed17470) | Nov 18, 2023 |
| Dell          | 0VRWRC A00                  | [b43ea86bfc](https://linux-hardware.org/?probe=b43ea86bfc) | Nov 18, 2023 |
| MSI           | B75MA-E33                   | [87132187f5](https://linux-hardware.org/?probe=87132187f5) | Nov 18, 2023 |
| MSI           | B75MA-E33                   | [ed47d2c01d](https://linux-hardware.org/?probe=ed47d2c01d) | Nov 18, 2023 |
| AZW           | EQ                          | [a5a8046409](https://linux-hardware.org/?probe=a5a8046409) | Nov 18, 2023 |
| HP            | 83E1                        | [8c2a7b3183](https://linux-hardware.org/?probe=8c2a7b3183) | Nov 18, 2023 |
| HP            | 83E1                        | [8b8d3394a8](https://linux-hardware.org/?probe=8b8d3394a8) | Nov 18, 2023 |
| ASRock        | B360M IB-R1                 | [fce9bc6ebe](https://linux-hardware.org/?probe=fce9bc6ebe) | Nov 18, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [0ebd3e6dd0](https://linux-hardware.org/?probe=0ebd3e6dd0) | Nov 17, 2023 |
| MSI           | A320M PRO-VD/S              | [2b5bf0b25f](https://linux-hardware.org/?probe=2b5bf0b25f) | Nov 17, 2023 |
| Gigabyte      | H61M-D2-B3                  | [358c0e28e9](https://linux-hardware.org/?probe=358c0e28e9) | Nov 17, 2023 |
| Dell          | 0NV0M7 A01                  | [f5ced375d8](https://linux-hardware.org/?probe=f5ced375d8) | Nov 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [57d850fe75](https://linux-hardware.org/?probe=57d850fe75) | Nov 17, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [6b4903cbb7](https://linux-hardware.org/?probe=6b4903cbb7) | Nov 17, 2023 |
| Medion        | H110H4-EM                   | [e6ca6d6e19](https://linux-hardware.org/?probe=e6ca6d6e19) | Nov 17, 2023 |
| HP            | 83E2                        | [89267eedbb](https://linux-hardware.org/?probe=89267eedbb) | Nov 17, 2023 |
| ASUSTek       | PRIME A320M-K               | [7adb8abf2c](https://linux-hardware.org/?probe=7adb8abf2c) | Nov 17, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [a1a2303573](https://linux-hardware.org/?probe=a1a2303573) | Nov 17, 2023 |
| Huanan        | X99-8M-F V1.3               | [58b38ab609](https://linux-hardware.org/?probe=58b38ab609) | Nov 17, 2023 |
| Huanan        | X99-8M-F V1.3               | [db7291c1da](https://linux-hardware.org/?probe=db7291c1da) | Nov 17, 2023 |
| ASUSTek       | P8H67-M                     | [5a6066ab8c](https://linux-hardware.org/?probe=5a6066ab8c) | Nov 17, 2023 |
| Dell          | 0F428D A00                  | [7111aa0bdb](https://linux-hardware.org/?probe=7111aa0bdb) | Nov 17, 2023 |
| AMI           | Intel                       | [36c0765b5c](https://linux-hardware.org/?probe=36c0765b5c) | Nov 17, 2023 |
| Dell          | 0GXM1W A00                  | [da8f5fa2e5](https://linux-hardware.org/?probe=da8f5fa2e5) | Nov 17, 2023 |
| ASUSTek       | Z170-K                      | [8d6d23926d](https://linux-hardware.org/?probe=8d6d23926d) | Nov 17, 2023 |
| Dell          | 0HHV7N A00                  | [9bb04e6b68](https://linux-hardware.org/?probe=9bb04e6b68) | Nov 17, 2023 |
| ASUSTek       | P8H67-M                     | [663c18d823](https://linux-hardware.org/?probe=663c18d823) | Nov 16, 2023 |
| Gigabyte      | P85-D3                      | [a6742c43a4](https://linux-hardware.org/?probe=a6742c43a4) | Nov 16, 2023 |
| Unknown       | Unknown                     | [f5e4b8400a](https://linux-hardware.org/?probe=f5e4b8400a) | Nov 16, 2023 |
| Supermicro    | X10DRU-i+A                  | [507da23117](https://linux-hardware.org/?probe=507da23117) | Nov 16, 2023 |
| Gigabyte      | H310M H x.x                 | [a95e23a38b](https://linux-hardware.org/?probe=a95e23a38b) | Nov 16, 2023 |
| Lenovo        | NOK                         | [1126fee720](https://linux-hardware.org/?probe=1126fee720) | Nov 16, 2023 |
| Gigabyte      | Z68AP-D3                    | [e1f0981231](https://linux-hardware.org/?probe=e1f0981231) | Nov 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [389f2adb17](https://linux-hardware.org/?probe=389f2adb17) | Nov 16, 2023 |
| HP            | 895C                        | [cbc2a3c2ae](https://linux-hardware.org/?probe=cbc2a3c2ae) | Nov 16, 2023 |
| Dell          | 062TCH A00                  | [5e674f81ca](https://linux-hardware.org/?probe=5e674f81ca) | Nov 15, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [fe31319dba](https://linux-hardware.org/?probe=fe31319dba) | Nov 15, 2023 |
| Gigabyte      | B550M K                     | [7415f68bac](https://linux-hardware.org/?probe=7415f68bac) | Nov 15, 2023 |
| MACHINIST     | E5-RS9 V1.11                | [13df1b5b7e](https://linux-hardware.org/?probe=13df1b5b7e) | Nov 15, 2023 |
| HP            | 3031h                       | [41814a3ce4](https://linux-hardware.org/?probe=41814a3ce4) | Nov 15, 2023 |
| ASUSTek       | H81-GAMER                   | [c5a2208642](https://linux-hardware.org/?probe=c5a2208642) | Nov 15, 2023 |
| ASUSTek       | H81-GAMER                   | [8891aedb5d](https://linux-hardware.org/?probe=8891aedb5d) | Nov 15, 2023 |
| Dell          | 0DFRFW A01                  | [dc42526823](https://linux-hardware.org/?probe=dc42526823) | Nov 15, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [27fcb76b4a](https://linux-hardware.org/?probe=27fcb76b4a) | Nov 15, 2023 |
| Dell          | 0D6H9T A02                  | [943ffbe22c](https://linux-hardware.org/?probe=943ffbe22c) | Nov 15, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [193b97cc55](https://linux-hardware.org/?probe=193b97cc55) | Nov 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1200e8253b](https://linux-hardware.org/?probe=1200e8253b) | Nov 14, 2023 |
| HP            | 0A64h                       | [db072ebaed](https://linux-hardware.org/?probe=db072ebaed) | Nov 14, 2023 |
| Dell          | 0YNVJG A02                  | [7c23854d23](https://linux-hardware.org/?probe=7c23854d23) | Nov 14, 2023 |
| Dell          | 0PGKWF A02                  | [3025cd2250](https://linux-hardware.org/?probe=3025cd2250) | Nov 14, 2023 |
| Dell          | 0YNVJG A02                  | [a641eb99bf](https://linux-hardware.org/?probe=a641eb99bf) | Nov 14, 2023 |
| Dell          | 05WXFV A03                  | [ecab18e943](https://linux-hardware.org/?probe=ecab18e943) | Nov 14, 2023 |
| Gigabyte      | B85M-HD3                    | [6cd89560fd](https://linux-hardware.org/?probe=6cd89560fd) | Nov 14, 2023 |
| ASUSTek       | Crosshair V Formula         | [81264f0e4e](https://linux-hardware.org/?probe=81264f0e4e) | Nov 14, 2023 |
| Intel         | AlderLake-S ADP-S DDR5 U... | [b3e7f8ab5c](https://linux-hardware.org/?probe=b3e7f8ab5c) | Nov 14, 2023 |
| ASUSTek       | P8B75-M LE                  | [d4baa90ad5](https://linux-hardware.org/?probe=d4baa90ad5) | Nov 14, 2023 |
| ASUSTek       | H110M-A                     | [d2b8ae9725](https://linux-hardware.org/?probe=d2b8ae9725) | Nov 13, 2023 |
| ASUSTek       | P8B75-M LE                  | [5dd5ed8025](https://linux-hardware.org/?probe=5dd5ed8025) | Nov 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | [05e0b7749a](https://linux-hardware.org/?probe=05e0b7749a) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6f0d8ee5da](https://linux-hardware.org/?probe=6f0d8ee5da) | Nov 13, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [3c2d452ee0](https://linux-hardware.org/?probe=3c2d452ee0) | Nov 13, 2023 |
| HP            | 2215                        | [452b632947](https://linux-hardware.org/?probe=452b632947) | Nov 13, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [15f3bc5d7e](https://linux-hardware.org/?probe=15f3bc5d7e) | Nov 13, 2023 |
| HP            | 0AA0h                       | [6d11e8b4d5](https://linux-hardware.org/?probe=6d11e8b4d5) | Nov 13, 2023 |
| ASUSTek       | H81M-C                      | [b3c22e6ea8](https://linux-hardware.org/?probe=b3c22e6ea8) | Nov 13, 2023 |
| Dell          | 0TDG4V A01                  | [f886eb50fa](https://linux-hardware.org/?probe=f886eb50fa) | Nov 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0020161387](https://linux-hardware.org/?probe=0020161387) | Nov 13, 2023 |
| ASUSTek       | PRIME Z390-A                | [597d1856ab](https://linux-hardware.org/?probe=597d1856ab) | Nov 12, 2023 |
| Medion        | MS-7707                     | [a6971454a0](https://linux-hardware.org/?probe=a6971454a0) | Nov 12, 2023 |
| OEM           | B75 Ver:1.41                | [a706806180](https://linux-hardware.org/?probe=a706806180) | Nov 12, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [cd6a15e082](https://linux-hardware.org/?probe=cd6a15e082) | Nov 12, 2023 |
| Acer          | Aspire X3950                | [b5f08e00c9](https://linux-hardware.org/?probe=b5f08e00c9) | Nov 12, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [82ac0e505a](https://linux-hardware.org/?probe=82ac0e505a) | Nov 12, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [8f08acd434](https://linux-hardware.org/?probe=8f08acd434) | Nov 12, 2023 |
| HP            | 845A                        | [95fbc211ec](https://linux-hardware.org/?probe=95fbc211ec) | Nov 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [bedc6fd7f0](https://linux-hardware.org/?probe=bedc6fd7f0) | Nov 11, 2023 |
| HP            | 339A                        | [b72bafad26](https://linux-hardware.org/?probe=b72bafad26) | Nov 11, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [c0932e879f](https://linux-hardware.org/?probe=c0932e879f) | Nov 11, 2023 |
| MSI           | MS-B0A21                    | [c9d19c0810](https://linux-hardware.org/?probe=c9d19c0810) | Nov 11, 2023 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [e82ee1d840](https://linux-hardware.org/?probe=e82ee1d840) | Nov 11, 2023 |
| ASUSTek       | Z170-A                      | [332413e83b](https://linux-hardware.org/?probe=332413e83b) | Nov 11, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [f709168fa7](https://linux-hardware.org/?probe=f709168fa7) | Nov 11, 2023 |
| HP            | 8054                        | [66fa2fd8c5](https://linux-hardware.org/?probe=66fa2fd8c5) | Nov 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [145330a105](https://linux-hardware.org/?probe=145330a105) | Nov 11, 2023 |
| HP            | 8054                        | [91d4d659b4](https://linux-hardware.org/?probe=91d4d659b4) | Nov 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [cf0d635016](https://linux-hardware.org/?probe=cf0d635016) | Nov 11, 2023 |
| ASUSTek       | P8H67-I DELUXE              | [2e8ed5d14f](https://linux-hardware.org/?probe=2e8ed5d14f) | Nov 11, 2023 |
| HP            | 339A                        | [a89c7d0d5f](https://linux-hardware.org/?probe=a89c7d0d5f) | Nov 10, 2023 |
| HP            | 1998                        | [3843c1d8d9](https://linux-hardware.org/?probe=3843c1d8d9) | Nov 10, 2023 |
| ASUSTek       | H110M-D                     | [6e0b13392e](https://linux-hardware.org/?probe=6e0b13392e) | Nov 10, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [947bd85c63](https://linux-hardware.org/?probe=947bd85c63) | Nov 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | [f63e590b7d](https://linux-hardware.org/?probe=f63e590b7d) | Nov 10, 2023 |
| ASUSTek       | P7H55-M                     | [cee33b1be4](https://linux-hardware.org/?probe=cee33b1be4) | Nov 10, 2023 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | [8d9e3d8367](https://linux-hardware.org/?probe=8d9e3d8367) | Nov 10, 2023 |
| Unknown       | Unknown                     | [2a03c8f49d](https://linux-hardware.org/?probe=2a03c8f49d) | Nov 10, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [8db3107f3f](https://linux-hardware.org/?probe=8db3107f3f) | Nov 10, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 291      | 5.03%   |
| 5.15.0-52-generic | 250      | 4.32%   |
| 5.15.0-58-generic | 246      | 4.25%   |
| 5.19.0-35-generic | 212      | 3.66%   |
| 6.2.0-26-generic  | 207      | 3.58%   |
| 5.15.0-48-generic | 202      | 3.49%   |
| 5.15.0-43-generic | 201      | 3.47%   |
| 5.19.0-32-generic | 196      | 3.39%   |
| 5.15.0-47-generic | 196      | 3.39%   |
| 5.19.0-38-generic | 178      | 3.07%   |
| 6.2.0-39-generic  | 168      | 2.9%    |
| 5.19.0-41-generic | 166      | 2.87%   |
| 6.2.0-36-generic  | 159      | 2.75%   |
| 5.19.0-46-generic | 156      | 2.69%   |
| 5.15.0-53-generic | 151      | 2.61%   |
| 5.15.0-46-generic | 137      | 2.37%   |
| 6.2.0-37-generic  | 134      | 2.31%   |
| 5.15.0-25-generic | 118      | 2.04%   |
| 6.5.0-14-generic  | 112      | 1.93%   |
| 5.19.0-43-generic | 107      | 1.85%   |
| 6.2.0-34-generic  | 106      | 1.83%   |
| 5.15.0-27-generic | 102      | 1.76%   |
| 5.15.0-60-generic | 98       | 1.69%   |
| 5.15.0-41-generic | 94       | 1.62%   |
| 5.15.0-40-generic | 92       | 1.59%   |
| 6.2.0-32-generic  | 91       | 1.57%   |
| 6.2.0-33-generic  | 90       | 1.55%   |
| 6.2.0-35-generic  | 86       | 1.49%   |
| 5.15.0-57-generic | 83       | 1.43%   |
| 5.15.0-50-generic | 80       | 1.38%   |
| 5.19.0-45-generic | 74       | 1.28%   |
| 5.19.0-40-generic | 71       | 1.23%   |
| 5.15.0-91-generic | 65       | 1.12%   |
| 5.15.0-67-generic | 63       | 1.09%   |
| 5.15.0-33-generic | 60       | 1.04%   |
| 5.19.0-50-generic | 54       | 0.93%   |
| 5.15.0-30-generic | 53       | 0.92%   |
| 5.15.0-69-generic | 49       | 0.85%   |
| 5.19.0-42-generic | 48       | 0.83%   |
| 6.5.0-15-generic  | 46       | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 2785     | 52.97%  |
| 5.19.0  | 1158     | 22.02%  |
| 6.2.0   | 1011     | 19.23%  |
| 6.5.0   | 162      | 3.08%   |
| 5.17.0  | 19       | 0.36%   |
| 5.13.0  | 15       | 0.29%   |
| 6.1.0   | 10       | 0.19%   |
| 6.0.0   | 6        | 0.11%   |
| 5.18.0  | 5        | 0.1%    |
| 6.0.1   | 3        | 0.06%   |
| 5.19.5  | 3        | 0.06%   |
| 5.18.10 | 3        | 0.06%   |
| 5.17.7  | 3        | 0.06%   |
| 5.10.60 | 3        | 0.06%   |
| 6.6.8   | 2        | 0.04%   |
| 6.4.3   | 2        | 0.04%   |
| 6.4.12  | 2        | 0.04%   |
| 6.4.0   | 2        | 0.04%   |
| 6.2.16  | 2        | 0.04%   |
| 6.2.11  | 2        | 0.04%   |
| 6.1.11  | 2        | 0.04%   |
| 6.0.9   | 2        | 0.04%   |
| 5.8.0   | 2        | 0.04%   |
| 5.19.17 | 2        | 0.04%   |
| 5.17.9  | 2        | 0.04%   |
| 5.17.15 | 2        | 0.04%   |
| 5.15.13 | 2        | 0.04%   |
| 5.14.0  | 2        | 0.04%   |
| 6.7.0   | 1        | 0.02%   |
| 6.6.9   | 1        | 0.02%   |
| 6.6.5   | 1        | 0.02%   |
| 6.6.2   | 1        | 0.02%   |
| 6.5.1   | 1        | 0.02%   |
| 6.4.9   | 1        | 0.02%   |
| 6.4.14  | 1        | 0.02%   |
| 6.4.11  | 1        | 0.02%   |
| 6.3.9   | 1        | 0.02%   |
| 6.3.7   | 1        | 0.02%   |
| 6.3.4   | 1        | 0.02%   |
| 6.3.2   | 1        | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 2788     | 53.04%  |
| 5.19    | 1164     | 22.15%  |
| 6.2     | 1021     | 19.43%  |
| 6.5     | 163      | 3.1%    |
| 5.17    | 30       | 0.57%   |
| 6.1     | 18       | 0.34%   |
| 5.13    | 15       | 0.29%   |
| 6.0     | 13       | 0.25%   |
| 5.18    | 13       | 0.25%   |
| 6.4     | 9        | 0.17%   |
| 6.6     | 5        | 0.1%    |
| 6.3     | 5        | 0.1%    |
| 5.10    | 3        | 0.06%   |
| 5.8     | 2        | 0.04%   |
| 5.14    | 2        | 0.04%   |
| 5.11    | 2        | 0.04%   |
| 6.7     | 1        | 0.02%   |
| 5.4     | 1        | 0.02%   |
| 5.16    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 4984     | 99.98%  |
| aarch64 | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 4518     | 90.47%  |
| Unknown         | 310      | 6.21%   |
| GNUstep         | 67       | 1.34%   |
| X-Cinnamon      | 51       | 1.02%   |
| GNOME Flashback | 20       | 0.4%    |
| GNOME Classic   | 11       | 0.22%   |
| i3              | 6        | 0.12%   |
| Enlightenment   | 5        | 0.1%    |
| ubuntu=GNOME    | 1        | 0.02%   |
| ubuntu          | 1        | 0.02%   |
| INPT            | 1        | 0.02%   |
| i3-with-shmlog  | 1        | 0.02%   |
| Cinnamon        | 1        | 0.02%   |
| awesome         | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 2693     | 52.85%  |
| X11     | 1949     | 38.25%  |
| Tty     | 290      | 5.69%   |
| Unknown | 163      | 3.2%    |
| Web     | 1        | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 4321     | 86.32%  |
| Unknown | 492      | 9.83%   |
| LightDM | 149      | 2.98%   |
| SDDM    | 18       | 0.36%   |
| GDM     | 17       | 0.34%   |
| SLiM    | 7        | 0.14%   |
| XDM     | 1        | 0.02%   |
| LXDM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2195     | 43.88%  |
| de_DE   | 478      | 9.56%   |
| fr_FR   | 349      | 6.98%   |
| en_GB   | 241      | 4.82%   |
| pt_BR   | 188      | 3.76%   |
| it_IT   | 158      | 3.16%   |
| en_CA   | 143      | 2.86%   |
| ru_RU   | 114      | 2.28%   |
| es_ES   | 104      | 2.08%   |
| C       | 95       | 1.9%    |
| en_AU   | 91       | 1.82%   |
| en_IN   | 73       | 1.46%   |
| pl_PL   | 68       | 1.36%   |
| Unknown | 60       | 1.2%    |
| nl_NL   | 49       | 0.98%   |
| ja_JP   | 42       | 0.84%   |
| cs_CZ   | 36       | 0.72%   |
| es_MX   | 35       | 0.7%    |
| zh_CN   | 34       | 0.68%   |
| de_AT   | 34       | 0.68%   |
| es_AR   | 32       | 0.64%   |
| sv_SE   | 24       | 0.48%   |
| hu_HU   | 23       | 0.46%   |
| en_ZA   | 22       | 0.44%   |
| fi_FI   | 18       | 0.36%   |
| pt_PT   | 17       | 0.34%   |
| en_NZ   | 16       | 0.32%   |
| tr_TR   | 15       | 0.3%    |
| fr_BE   | 14       | 0.28%   |
| de_CH   | 14       | 0.28%   |
| fr_CA   | 13       | 0.26%   |
| el_GR   | 13       | 0.26%   |
| en_PH   | 12       | 0.24%   |
| zh_TW   | 11       | 0.22%   |
| ko_KR   | 11       | 0.22%   |
| es_CO   | 11       | 0.22%   |
| sk_SK   | 10       | 0.2%    |
| nl_BE   | 10       | 0.2%    |
| es_CL   | 8        | 0.16%   |
| en_HK   | 7        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3469     | 68.76%  |
| EFI  | 1576     | 31.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Ext4          | 3573     | 69.42%  |
| Tmpfs         | 1242     | 24.13%  |
| Overlay       | 153      | 2.97%   |
| Zfs           | 94       | 1.83%   |
| Btrfs         | 42       | 0.82%   |
| Xfs           | 24       | 0.47%   |
| Ext2          | 9        | 0.17%   |
| Unknown       | 4        | 0.08%   |
| Ext3          | 3        | 0.06%   |
| XXXX          | 1        | 0.02%   |
| Jfs           | 1        | 0.02%   |
| Fuse.snapfuse | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 3591     | 69.88%  |
| Unknown | 1006     | 19.58%  |
| MBR     | 542      | 10.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4178     | 82.46%  |
| Yes       | 889      | 17.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2932     | 58.12%  |
| Yes       | 2113     | 41.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1213     | 24.33%  |
| Gigabyte Technology                  | 718      | 14.4%   |
| MSI                                  | 552      | 11.07%  |
| Dell                                 | 530      | 10.63%  |
| Hewlett-Packard                      | 398      | 7.98%   |
| ASRock                               | 393      | 7.88%   |
| Lenovo                               | 205      | 4.11%   |
| Intel                                | 146      | 2.93%   |
| Acer                                 | 92       | 1.85%   |
| Fujitsu                              | 83       | 1.66%   |
| Unknown                              | 76       | 1.52%   |
| Supermicro                           | 53       | 1.06%   |
| Pegatron                             | 44       | 0.88%   |
| Foxconn                              | 44       | 0.88%   |
| Medion                               | 40       | 0.8%    |
| Biostar                              | 36       | 0.72%   |
| AZW                                  | 28       | 0.56%   |
| Apple                                | 26       | 0.52%   |
| ECS                                  | 23       | 0.46%   |
| Shuttle                              | 19       | 0.38%   |
| Alienware                            | 19       | 0.38%   |
| Huanan                               | 15       | 0.3%    |
| Gateway                              | 13       | 0.26%   |
| BESSTAR Tech                         | 12       | 0.24%   |
| Shenzhen Meigao Electronic Equipment | 10       | 0.2%    |
| Positivo                             | 9        | 0.18%   |
| Packard Bell                         | 9        | 0.18%   |
| OEM                                  | 7        | 0.14%   |
| Inventec                             | 7        | 0.14%   |
| AMI                                  | 7        | 0.14%   |
| Google                               | 6        | 0.12%   |
| eMachines                            | 6        | 0.12%   |
| ASRockRack                           | 6        | 0.12%   |
| MACHINIST                            | 5        | 0.1%    |
| HC Technology.                       | 5        | 0.1%    |
| ZOTAC                                | 4        | 0.08%   |
| Wistron                              | 4        | 0.08%   |
| PCWare                               | 4        | 0.08%   |
| Fujitsu Siemens                      | 4        | 0.08%   |
| YANYU                                | 3        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 115      | 2.31%   |
| Unknown                         | 82       | 1.64%   |
| Dell OptiPlex 7010              | 39       | 0.78%   |
| Dell OptiPlex 9020              | 35       | 0.7%    |
| ASUS PRIME A320M-K              | 29       | 0.58%   |
| ASUS TUF Gaming X570-PLUS       | 23       | 0.46%   |
| Dell OptiPlex 3020              | 22       | 0.44%   |
| MSI MS-7C91                     | 21       | 0.42%   |
| MSI MS-7C37                     | 21       | 0.42%   |
| Dell OptiPlex 790               | 20       | 0.4%    |
| MSI MS-7721                     | 19       | 0.38%   |
| Dell OptiPlex 7050              | 18       | 0.36%   |
| ASUS ROG STRIX B550-F GAMING    | 18       | 0.36%   |
| ASUS PRIME Z590-P               | 18       | 0.36%   |
| Dell OptiPlex 3050              | 17       | 0.34%   |
| Intel H61                       | 16       | 0.32%   |
| ASUS PRIME B550M-A              | 16       | 0.32%   |
| ASRock B450M Pro4               | 16       | 0.32%   |
| Gigabyte B450M DS3H             | 15       | 0.3%    |
| Dell OptiPlex 990               | 15       | 0.3%    |
| Dell OptiPlex 7040              | 15       | 0.3%    |
| ASUS PRIME X570-PRO             | 15       | 0.3%    |
| MSI MS-7C52                     | 14       | 0.28%   |
| HP Compaq 8200 Elite SFF PC     | 14       | 0.28%   |
| Dell OptiPlex 780               | 14       | 0.28%   |
| MSI MS-7C56                     | 13       | 0.26%   |
| HP EliteDesk 800 G1 SFF         | 13       | 0.26%   |
| ASUS M5A78L-M/USB3              | 13       | 0.26%   |
| MSI MS-7C02                     | 12       | 0.24%   |
| MSI MS-7817                     | 12       | 0.24%   |
| Gigabyte A320M-S2H              | 12       | 0.24%   |
| ASUS H110M-A                    | 12       | 0.24%   |
| Supermicro SYS-6018R-TDW        | 11       | 0.22%   |
| MSI MS-7B86                     | 11       | 0.22%   |
| HP ProDesk 600 G1 SFF           | 11       | 0.22%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI | 11       | 0.22%   |
| ASUS M5A97 R2.0                 | 11       | 0.22%   |
| ASRock A320M-HDV R4.0           | 11       | 0.22%   |
| MSI MS-7B79                     | 10       | 0.2%    |
| MSI MS-7693                     | 10       | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 334      | 6.7%    |
| ASUS PRIME          | 268      | 5.38%   |
| ASUS ROG            | 172      | 3.45%   |
| Lenovo ThinkCentre  | 120      | 2.41%   |
| HP Compaq           | 118      | 2.37%   |
| ASUS TUF            | 115      | 2.31%   |
| ASUS All            | 115      | 2.31%   |
| Unknown             | 82       | 1.64%   |
| Dell Precision      | 80       | 1.6%    |
| HP EliteDesk        | 64       | 1.28%   |
| Acer Aspire         | 56       | 1.12%   |
| Fujitsu ESPRIMO     | 55       | 1.1%    |
| Dell Inspiron       | 53       | 1.06%   |
| HP ProDesk          | 49       | 0.98%   |
| Gigabyte B450M      | 32       | 0.64%   |
| Lenovo ThinkStation | 29       | 0.58%   |
| ASUS M5A78L-M       | 28       | 0.56%   |
| Gigabyte B550M      | 27       | 0.54%   |
| Gigabyte X570       | 25       | 0.5%    |
| ASRock B450M        | 24       | 0.48%   |
| Lenovo IdeaCentre   | 23       | 0.46%   |
| Gigabyte Z390       | 23       | 0.46%   |
| Dell XPS            | 23       | 0.46%   |
| ASUS M5A97          | 23       | 0.46%   |
| MSI MS-7C91         | 21       | 0.42%   |
| MSI MS-7C37         | 21       | 0.42%   |
| ASUS Pro            | 21       | 0.42%   |
| Fujitsu CELSIUS     | 20       | 0.4%    |
| MSI MS-7721         | 19       | 0.38%   |
| Gigabyte B550       | 19       | 0.38%   |
| Gigabyte B450       | 18       | 0.36%   |
| Dell Vostro         | 18       | 0.36%   |
| ASUS P8H61-M        | 18       | 0.36%   |
| Acer Veriton        | 18       | 0.36%   |
| Intel H61           | 17       | 0.34%   |
| HP Pavilion         | 17       | 0.34%   |
| ASRock X570         | 16       | 0.32%   |
| ASUS CROSSHAIR      | 15       | 0.3%    |
| MSI MS-7C52         | 14       | 0.28%   |
| HP ProLiant         | 14       | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 449      | 9.01%   |
| 2013    | 431      | 8.65%   |
| 2012    | 422      | 8.47%   |
| 2020    | 394      | 7.9%    |
| 2021    | 366      | 7.34%   |
| 2019    | 334      | 6.7%    |
| 2014    | 334      | 6.7%    |
| 2011    | 328      | 6.58%   |
| 2017    | 316      | 6.34%   |
| 2022    | 289      | 5.8%    |
| 2015    | 280      | 5.62%   |
| 2010    | 243      | 4.87%   |
| 2016    | 203      | 4.07%   |
| 2009    | 200      | 4.01%   |
| 2008    | 145      | 2.91%   |
| 2023    | 122      | 2.45%   |
| 2007    | 90       | 1.81%   |
| 2006    | 25       | 0.5%    |
| 2005    | 7        | 0.14%   |
| Unknown | 6        | 0.12%   |
| 2004    | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4985     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4809     | 96.28%  |
| Enabled  | 186      | 3.72%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4976     | 99.82%  |
| Yes  | 9        | 0.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1312     | 25.95%  |
| 32.01-64.0      | 848      | 16.78%  |
| 4.01-8.0        | 834      | 16.5%   |
| 8.01-16.0       | 813      | 16.08%  |
| 3.01-4.0        | 555      | 10.98%  |
| 64.01-256.0     | 403      | 7.97%   |
| 24.01-32.0      | 172      | 3.4%    |
| 1.01-2.0        | 55       | 1.09%   |
| More than 256.0 | 33       | 0.65%   |
| 2.01-3.0        | 27       | 0.53%   |
| 0.51-1.0        | 2        | 0.04%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1651     | 30.62%  |
| 2.01-3.0    | 1600     | 29.67%  |
| 4.01-8.0    | 838      | 15.54%  |
| 3.01-4.0    | 801      | 14.86%  |
| 8.01-16.0   | 279      | 5.17%   |
| 0.51-1.0    | 103      | 1.91%   |
| 16.01-24.0  | 50       | 0.93%   |
| 0.01-0.5    | 24       | 0.45%   |
| 24.01-32.0  | 23       | 0.43%   |
| 32.01-64.0  | 14       | 0.26%   |
| 64.01-256.0 | 9        | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 2118     | 41.13%  |
| 2      | 1479     | 28.72%  |
| 3      | 749      | 14.55%  |
| 4      | 362      | 7.03%   |
| 5      | 180      | 3.5%    |
| 6      | 83       | 1.61%   |
| 0      | 61       | 1.18%   |
| 7      | 49       | 0.95%   |
| 8      | 20       | 0.39%   |
| 9      | 18       | 0.35%   |
| 10     | 9        | 0.17%   |
| 11     | 8        | 0.16%   |
| 13     | 3        | 0.06%   |
| 12     | 3        | 0.06%   |
| 25     | 2        | 0.04%   |
| 14     | 2        | 0.04%   |
| 38     | 1        | 0.02%   |
| 20     | 1        | 0.02%   |
| 17     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2862     | 56.97%  |
| Yes       | 2162     | 43.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4944     | 99.16%  |
| No        | 42       | 0.84%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2729     | 54.3%   |
| Yes       | 2297     | 45.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3356     | 66.67%  |
| Yes       | 1678     | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1113     | 22.27%  |
| Germany      | 566      | 11.33%  |
| France       | 368      | 7.36%   |
| Brazil       | 266      | 5.32%   |
| UK           | 235      | 4.7%    |
| Russia       | 208      | 4.16%   |
| Italy        | 190      | 3.8%    |
| Canada       | 188      | 3.76%   |
| Switzerland  | 151      | 3.02%   |
| Spain        | 126      | 2.52%   |
| Australia    | 101      | 2.02%   |
| Poland       | 91       | 1.82%   |
| Netherlands  | 91       | 1.82%   |
| India        | 83       | 1.66%   |
| Austria      | 64       | 1.28%   |
| Mexico       | 60       | 1.2%    |
| Sweden       | 56       | 1.12%   |
| Japan        | 55       | 1.1%    |
| Argentina    | 52       | 1.04%   |
| Belgium      | 49       | 0.98%   |
| Czechia      | 46       | 0.92%   |
| Finland      | 44       | 0.88%   |
| Hungary      | 39       | 0.78%   |
| China        | 39       | 0.78%   |
| Turkey       | 38       | 0.76%   |
| Greece       | 34       | 0.68%   |
| Romania      | 31       | 0.62%   |
| South Africa | 26       | 0.52%   |
| Slovakia     | 26       | 0.52%   |
| Bulgaria     | 26       | 0.52%   |
| Portugal     | 24       | 0.48%   |
| South Korea  | 22       | 0.44%   |
| Hong Kong    | 19       | 0.38%   |
| Thailand     | 18       | 0.36%   |
| Norway       | 18       | 0.36%   |
| New Zealand  | 18       | 0.36%   |
| Taiwan       | 17       | 0.34%   |
| Serbia       | 17       | 0.34%   |
| Denmark      | 17       | 0.34%   |
| Colombia     | 17       | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zurich            | 85       | 1.63%   |
| Moscow            | 62       | 1.19%   |
| Berlin            | 47       | 0.9%    |
| Paris             | 39       | 0.75%   |
| Vienna            | 38       | 0.73%   |
| Sydney            | 35       | 0.67%   |
| Sao Paulo         | 29       | 0.56%   |
| Milan             | 28       | 0.54%   |
| Madrid            | 28       | 0.54%   |
| St Petersburg     | 27       | 0.52%   |
| Hamburg           | 26       | 0.5%    |
| Cheboksary        | 24       | 0.46%   |
| Rio de Janeiro    | 23       | 0.44%   |
| New York          | 23       | 0.44%   |
| Rome              | 21       | 0.4%    |
| Munich            | 21       | 0.4%    |
| Helsinki          | 21       | 0.4%    |
| Warsaw            | 20       | 0.38%   |
| Toronto           | 20       | 0.38%   |
| Prague            | 19       | 0.36%   |
| Athens            | 19       | 0.36%   |
| Seattle           | 18       | 0.35%   |
| San José         | 18       | 0.35%   |
| Lucerne           | 18       | 0.35%   |
| Los Angeles       | 18       | 0.35%   |
| Istanbul          | 18       | 0.35%   |
| London            | 17       | 0.33%   |
| Budapest          | 17       | 0.33%   |
| Barcelona         | 17       | 0.33%   |
| Roubaix           | 16       | 0.31%   |
| Melbourne         | 16       | 0.31%   |
| Stockholm         | 14       | 0.27%   |
| Singapore         | 14       | 0.27%   |
| Manchester        | 14       | 0.27%   |
| Dallas            | 14       | 0.27%   |
| Brisbane          | 14       | 0.27%   |
| Amsterdam         | 14       | 0.27%   |
| Vancouver         | 13       | 0.25%   |
| Sofia             | 13       | 0.25%   |
| Frankfurt am Main | 13       | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1568     | 2543   | 17.99%  |
| WDC                         | 1519     | 2522   | 17.43%  |
| Samsung Electronics         | 1312     | 2074   | 15.05%  |
| Kingston                    | 526      | 657    | 6.03%   |
| Sandisk                     | 434      | 608    | 4.98%   |
| Toshiba                     | 431      | 565    | 4.94%   |
| Crucial                     | 385      | 573    | 4.42%   |
| Hitachi                     | 254      | 334    | 2.91%   |
| Intel                       | 133      | 215    | 1.53%   |
| A-DATA Technology           | 132      | 165    | 1.51%   |
| China                       | 116      | 137    | 1.33%   |
| Unknown                     | 115      | 214    | 1.32%   |
| HGST                        | 92       | 158    | 1.06%   |
| Phison Electronics          | 91       | 119    | 1.04%   |
| SK hynix                    | 86       | 110    | 0.99%   |
| Micron/Crucial Technology   | 84       | 111    | 0.96%   |
| PNY                         | 68       | 82     | 0.78%   |
| Intenso                     | 68       | 89     | 0.78%   |
| Kingston Technology Company | 66       | 80     | 0.76%   |
| Silicon Motion              | 65       | 85     | 0.75%   |
| SPCC                        | 55       | 91     | 0.63%   |
| Micron Technology           | 50       | 65     | 0.57%   |
| Phison                      | 44       | 59     | 0.5%    |
| OCZ                         | 41       | 59     | 0.47%   |
| Patriot                     | 35       | 45     | 0.4%    |
| Maxtor                      | 35       | 47     | 0.4%    |
| Lexar                       | 35       | 40     | 0.4%    |
| Corsair                     | 33       | 38     | 0.38%   |
| Gigabyte Technology         | 31       | 40     | 0.36%   |
| Unknown                     | 31       | 34     | 0.36%   |
| Team                        | 29       | 44     | 0.33%   |
| ADATA Technology            | 29       | 38     | 0.33%   |
| Transcend                   | 28       | 28     | 0.32%   |
| Hewlett-Packard             | 28       | 69     | 0.32%   |
| Fujitsu                     | 22       | 30     | 0.25%   |
| ASMT                        | 21       | 34     | 0.24%   |
| MAXIO Technology (Hangzhou) | 20       | 24     | 0.23%   |
| JMicron Technology          | 20       | 21     | 0.23%   |
| Realtek Semiconductor       | 19       | 23     | 0.22%   |
| KingSpec                    | 19       | 21     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 131      | 1.3%    |
| Seagate ST500DM002-1BD142 500GB                       | 119      | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB                        | 119      | 1.18%   |
| Kingston SA400S37240G 240GB SSD                       | 111      | 1.1%    |
| Seagate ST2000DM008-2FR102 2TB                        | 108      | 1.07%   |
| Kingston SA400S37480G 480GB SSD                       | 90       | 0.89%   |
| Samsung SSD 850 EVO 250GB                             | 79       | 0.78%   |
| Toshiba DT01ACA100 1TB                                | 73       | 0.72%   |
| Samsung SSD 850 EVO 500GB                             | 73       | 0.72%   |
| Samsung SSD 860 EVO 500GB                             | 70       | 0.69%   |
| Samsung SSD 980 PRO 1TB                               | 69       | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 64       | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB                        | 63       | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB                        | 62       | 0.62%   |
| Crucial CT500MX500SSD1 500GB                          | 56       | 0.56%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 54       | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 53       | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                           | 53       | 0.53%   |
| Kingston SA400S37120G 120GB SSD                       | 50       | 0.5%    |
| Toshiba DT01ACA050 500GB                              | 49       | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB                        | 49       | 0.49%   |
| Unknown SD/MMC/MS PRO 256GB                           | 46       | 0.46%   |
| Crucial CT240BX500SSD1 240GB                          | 45       | 0.45%   |
| Seagate ST1000DM003-1SB102 1TB                        | 43       | 0.43%   |
| SanDisk NVMe SSD Drive 1TB                            | 42       | 0.42%   |
| Toshiba HDWD110 1TB                                   | 41       | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 39       | 0.39%   |
| Samsung SSD 980 1TB                                   | 39       | 0.39%   |
| Samsung SSD 870 EVO 500GB                             | 39       | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB                        | 35       | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB                        | 35       | 0.35%   |
| Seagate ST2000DM001-1CH164 2TB                        | 35       | 0.35%   |
| Samsung SSD 860 EVO 1TB                               | 35       | 0.35%   |
| Toshiba DT01ACA200 2TB                                | 34       | 0.34%   |
| Seagate ST3500418AS 500GB                             | 34       | 0.34%   |
| Crucial CT480BX500SSD1 480GB                          | 33       | 0.33%   |
| Seagate ST31000528AS 1TB                              | 31       | 0.31%   |
| Samsung SSD 870 EVO 1TB                               | 31       | 0.31%   |
| Samsung SSD 860 EVO 250GB                             | 31       | 0.31%   |
| Samsung NVMe SSD Drive 1TB                            | 31       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1536     | 2479   | 38.45%  |
| WDC                 | 1347     | 2215   | 33.72%  |
| Toshiba             | 369      | 480    | 9.24%   |
| Hitachi             | 252      | 332    | 6.31%   |
| Samsung Electronics | 196      | 287    | 4.91%   |
| HGST                | 92       | 154    | 2.3%    |
| Unknown             | 52       | 67     | 1.3%    |
| Maxtor              | 33       | 42     | 0.83%   |
| Fujitsu             | 22       | 30     | 0.55%   |
| JMicron Technology  | 17       | 18     | 0.43%   |
| Intenso             | 17       | 19     | 0.43%   |
| ASMT                | 9        | 11     | 0.23%   |
| Apple               | 8        | 9      | 0.2%    |
| Hewlett-Packard     | 7        | 24     | 0.18%   |
| WD MediaMax         | 5        | 6      | 0.13%   |
| SABRENT             | 4        | 6      | 0.1%    |
| External            | 4        | 4      | 0.1%    |
| ExcelStor           | 4        | 4      | 0.1%    |
| HPE                 | 3        | 5      | 0.08%   |
| TDAS                | 2        | 11     | 0.05%   |
| LaCie               | 2        | 3      | 0.05%   |
| Inateck             | 2        | 2      | 0.05%   |
| ASMedia             | 2        | 2      | 0.05%   |
| USB3.0              | 1        | 2      | 0.03%   |
| StoreJet            | 1        | 1      | 0.03%   |
| SSK                 | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| QUANTUM             | 1        | 1      | 0.03%   |
| Min Yi U            | 1        | 2      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| HGST HTS            | 1        | 1      | 0.03%   |
| DAS                 | 1        | 3      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 669      | 911    | 22.17%  |
| Kingston            | 437      | 548    | 14.48%  |
| Crucial             | 340      | 509    | 11.27%  |
| SanDisk             | 224      | 313    | 7.42%   |
| WDC                 | 179      | 227    | 5.93%   |
| China               | 115      | 135    | 3.81%   |
| A-DATA Technology   | 111      | 143    | 3.68%   |
| Intel               | 79       | 148    | 2.62%   |
| PNY                 | 62       | 76     | 2.05%   |
| Toshiba             | 60       | 68     | 1.99%   |
| SPCC                | 51       | 86     | 1.69%   |
| OCZ                 | 39       | 45     | 1.29%   |
| Intenso             | 38       | 55     | 1.26%   |
| Patriot             | 34       | 44     | 1.13%   |
| Micron Technology   | 34       | 48     | 1.13%   |
| SK hynix            | 28       | 38     | 0.93%   |
| Team                | 27       | 41     | 0.89%   |
| Transcend           | 26       | 26     | 0.86%   |
| Lexar               | 24       | 28     | 0.8%    |
| Gigabyte Technology | 22       | 31     | 0.73%   |
| Corsair             | 20       | 24     | 0.66%   |
| KingSpec            | 19       | 21     | 0.63%   |
| GOODRAM             | 19       | 28     | 0.63%   |
| Hewlett-Packard     | 17       | 17     | 0.56%   |
| Apacer              | 15       | 15     | 0.5%    |
| Unknown             | 15       | 16     | 0.5%    |
| LITEON              | 14       | 20     | 0.46%   |
| SABRENT             | 12       | 15     | 0.4%    |
| ASMT                | 12       | 22     | 0.4%    |
| Fanxiang            | 11       | 15     | 0.36%   |
| LITEONIT            | 9        | 10     | 0.3%    |
| Emtec               | 9        | 9      | 0.3%    |
| Dogfish             | 9        | 13     | 0.3%    |
| Seagate             | 8        | 10     | 0.27%   |
| FORESEE             | 8        | 8      | 0.27%   |
| Netac               | 7        | 9      | 0.23%   |
| Mushkin             | 6        | 6      | 0.2%    |
| Leven               | 6        | 19     | 0.2%    |
| LDLC                | 6        | 7      | 0.2%    |
| KIOXIA-EXCERIA      | 6        | 14     | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3113     | 6224   | 42.03%  |
| SSD     | 2547     | 4036   | 34.39%  |
| NVMe    | 1539     | 2373   | 20.78%  |
| Unknown | 181      | 312    | 2.44%   |
| MMC     | 27       | 37     | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4270     | 9850   | 68.39%  |
| NVMe | 1538     | 2368   | 24.63%  |
| SAS  | 409      | 727    | 6.55%   |
| MMC  | 27       | 37     | 0.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2932     | 4921   | 47.47%  |
| 0.51-1.0   | 1809     | 2848   | 29.29%  |
| 1.01-2.0   | 742      | 1179   | 12.01%  |
| 3.01-4.0   | 290      | 471    | 4.7%    |
| 4.01-10.0  | 188      | 443    | 3.04%   |
| 2.01-3.0   | 156      | 239    | 2.53%   |
| 10.01-20.0 | 57       | 156    | 0.92%   |
| 20.01-50.0 | 1        | 2      | 0.02%   |
| 0          | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1224     | 23.53%  |
| 251-500        | 984      | 18.92%  |
| 501-1000       | 961      | 18.48%  |
| 1001-2000      | 588      | 11.31%  |
| More than 3000 | 507      | 9.75%   |
| 2001-3000      | 257      | 4.94%   |
| 51-100         | 242      | 4.65%   |
| 1-20           | 210      | 4.04%   |
| Unknown        | 131      | 2.52%   |
| 21-50          | 97       | 1.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1637     | 30.57%  |
| 21-50          | 988      | 18.45%  |
| 101-250        | 653      | 12.19%  |
| 51-100         | 639      | 11.93%  |
| 251-500        | 424      | 7.92%   |
| 501-1000       | 355      | 6.63%   |
| 1001-2000      | 228      | 4.26%   |
| More than 3000 | 204      | 3.81%   |
| Unknown        | 131      | 2.45%   |
| 2001-3000      | 95       | 1.77%   |
| 0              | 1        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 9        | 9      | 2.07%   |
| WDC WD40EFRX-68WT0N0 4TB              | 8        | 10     | 1.84%   |
| Seagate ST3500418AS 500GB             | 5        | 7      | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB        | 5        | 5      | 1.15%   |
| WDC WD10EARS-00Y5B1 1TB               | 4        | 5      | 0.92%   |
| Seagate ST31000528AS 1TB              | 4        | 4      | 0.92%   |
| Seagate ST2000DM008-2FR102 2TB        | 4        | 5      | 0.92%   |
| Seagate ST2000DM001-1CH164 2TB        | 4        | 4      | 0.92%   |
| Seagate ST1000DM003-1CH162 1TB        | 4        | 5      | 0.92%   |
| SanDisk SSD PLUS 480GB                | 4        | 4      | 0.92%   |
| Kingston SA400S37240G 240GB SSD       | 4        | 4      | 0.92%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3        | 3      | 0.69%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 3        | 3      | 0.69%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 3        | 3      | 0.69%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 3        | 4      | 0.69%   |
| WDC WD10EZEX-21WN4A0 1TB              | 3        | 3      | 0.69%   |
| WDC WD10EZEX-21M2NA0 1TB              | 3        | 3      | 0.69%   |
| Toshiba DT01ACA050 500GB              | 3        | 3      | 0.69%   |
| Seagate ST500LM021-1KJ152 500GB       | 3        | 5      | 0.69%   |
| Seagate ST3250310AS 250GB             | 3        | 3      | 0.69%   |
| Samsung Electronics SSD 870 EVO 500GB | 3        | 3      | 0.69%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3        | 3      | 0.69%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.69%   |
| Intel SSDSC2CW120A3 120GB             | 3        | 3      | 0.69%   |
| Intel SSDSC2BB800G7 800GB             | 3        | 9      | 0.69%   |
| A-DATA Technology SX8100NP 512GB      | 3        | 3      | 0.69%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 2        | 2      | 0.46%   |
| WDC WD5000AADS-00S9B0 500GB           | 2        | 2      | 0.46%   |
| WDC WD40EZRX-00SPEB0 4TB              | 2        | 2      | 0.46%   |
| WDC WD4003FZEX-00Z4SA0 4TB            | 2        | 4      | 0.46%   |
| WDC WD30EZRX-00MMMB0 3TB              | 2        | 6      | 0.46%   |
| WDC WD2002FAEX-007BA0 2TB             | 2        | 2      | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2        | 2      | 0.46%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 2        | 4      | 0.46%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 2        | 2      | 0.46%   |
| WDC WD10EZEX-22MFCA0 1TB              | 2        | 2      | 0.46%   |
| WDC WD10EADS-65L5B1 1TB               | 2        | 2      | 0.46%   |
| WDC WD10EADS-00M2B0 1TB               | 2        | 2      | 0.46%   |
| Toshiba DT01ACA100 1TB                | 2        | 2      | 0.46%   |
| Seagate ST500LM000-SSHD-8GB           | 2        | 3      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 125      | 155    | 29.41%  |
| Seagate             | 111      | 149    | 26.12%  |
| Samsung Electronics | 49       | 54     | 11.53%  |
| Hitachi             | 24       | 30     | 5.65%   |
| Intel               | 17       | 31     | 4%      |
| Toshiba             | 16       | 17     | 3.76%   |
| Kingston            | 13       | 13     | 3.06%   |
| Crucial             | 9        | 11     | 2.12%   |
| SanDisk             | 7        | 9      | 1.65%   |
| A-DATA Technology   | 7        | 7      | 1.65%   |
| Maxtor              | 6        | 7      | 1.41%   |
| HGST                | 5        | 6      | 1.18%   |
| China               | 4        | 4      | 0.94%   |
| SK hynix            | 3        | 3      | 0.71%   |
| Micron Technology   | 3        | 9      | 0.71%   |
| LITEONIT            | 3        | 3      | 0.71%   |
| LDLC                | 3        | 4      | 0.71%   |
| OCZ                 | 2        | 2      | 0.47%   |
| Intenso             | 2        | 2      | 0.47%   |
| YS                  | 1        | 1      | 0.24%   |
| XPG                 | 1        | 1      | 0.24%   |
| WD MediaMax         | 1        | 1      | 0.24%   |
| walram              | 1        | 1      | 0.24%   |
| USB3.0              | 1        | 1      | 0.24%   |
| Unknown             | 1        | 1      | 0.24%   |
| Silicon Motion      | 1        | 2      | 0.24%   |
| PNY                 | 1        | 1      | 0.24%   |
| Patriot             | 1        | 1      | 0.24%   |
| Netac               | 1        | 2      | 0.24%   |
| Mushkin             | 1        | 1      | 0.24%   |
| KingSpec            | 1        | 1      | 0.24%   |
| Gigabyte Technology | 1        | 1      | 0.24%   |
| Corsair             | 1        | 1      | 0.24%   |
| ASMedia             | 1        | 1      | 0.24%   |
| Unknown             | 1        | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 118      | 148    | 39.07%  |
| Seagate             | 111      | 149    | 36.75%  |
| Hitachi             | 24       | 30     | 7.95%   |
| Samsung Electronics | 22       | 24     | 7.28%   |
| Toshiba             | 14       | 15     | 4.64%   |
| Maxtor              | 6        | 7      | 1.99%   |
| HGST                | 5        | 6      | 1.66%   |
| WD MediaMax         | 1        | 1      | 0.33%   |
| Unknown             | 1        | 1      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 282      | 381    | 69.63%  |
| SSD  | 101      | 128    | 24.94%  |
| NVMe | 22       | 25     | 5.43%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 500GB     | 2        | 2      | 20%     |
| WDC WD800BB-00FJA0 80GB               | 1        | 1      | 10%     |
| WDC WD3200AAJS-22VWA0 320GB           | 1        | 1      | 10%     |
| WDC WD1500HLFS-01G6U0 150GB           | 1        | 1      | 10%     |
| Seagate ST3500630AS 500GB             | 1        | 1      | 10%     |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 1      | 10%     |
| Intel SSDSC2BB480G7 480GB             | 1        | 4      | 10%     |
| Intel SSDPEKKW256G7 256GB             | 1        | 1      | 10%     |
| Hewlett-Packard EF0450FARMV 450GB     | 1        | 4      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 30%     |
| Samsung Electronics | 3        | 3      | 30%     |
| Intel               | 2        | 5      | 20%     |
| Seagate             | 1        | 1      | 10%     |
| Hewlett-Packard     | 1        | 4      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3357     | 8848   | 61.99%  |
| Works    | 1669     | 3584   | 30.82%  |
| Malfunc  | 379      | 534    | 7%      |
| Failed   | 10       | 16     | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 3356     | 45.91%  |
| AMD                            | 1476     | 20.19%  |
| Samsung Electronics            | 585      | 8%      |
| SanDisk                        | 282      | 3.86%   |
| ASMedia Technology             | 267      | 3.65%   |
| Kingston Technology Company    | 159      | 2.18%   |
| Phison Electronics             | 154      | 2.11%   |
| Marvell Technology Group       | 149      | 2.04%   |
| Micron/Crucial Technology      | 132      | 1.81%   |
| JMicron Technology             | 128      | 1.75%   |
| Nvidia                         | 102      | 1.4%    |
| Silicon Motion                 | 83       | 1.14%   |
| SK hynix                       | 60       | 0.82%   |
| ADATA Technology               | 50       | 0.68%   |
| MAXIO Technology (Hangzhou)    | 35       | 0.48%   |
| Broadcom / LSI                 | 32       | 0.44%   |
| Realtek Semiconductor          | 31       | 0.42%   |
| LSI Logic / Symbios Logic      | 29       | 0.4%    |
| VIA Technologies               | 22       | 0.3%    |
| Silicon Image                  | 21       | 0.29%   |
| KIOXIA                         | 21       | 0.29%   |
| Adaptec                        | 19       | 0.26%   |
| Seagate Technology             | 18       | 0.25%   |
| Micron Technology              | 17       | 0.23%   |
| Toshiba America Info Systems   | 14       | 0.19%   |
| Shenzhen Longsys Electronics   | 13       | 0.18%   |
| INNOGRIT                       | 6        | 0.08%   |
| Hewlett-Packard                | 5        | 0.07%   |
| Union Memory (Shenzhen)        | 4        | 0.05%   |
| Solidigm                       | 4        | 0.05%   |
| Lite-On Technology             | 4        | 0.05%   |
| Apple                          | 4        | 0.05%   |
| Transcend                      | 2        | 0.03%   |
| Solid State Storage Technology | 2        | 0.03%   |
| OCZ Technology Group           | 2        | 0.03%   |
| Netac Technology               | 2        | 0.03%   |
| Integrated Technology Express  | 2        | 0.03%   |
| Chelsio Communications         | 2        | 0.03%   |
| Biwin Storage Technology       | 2        | 0.03%   |
| 3ware                          | 2        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 744      | 8.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 417      | 4.73%   |
| Intel SATA Controller [RAID mode]                                                       | 292      | 3.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 271      | 3.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 268      | 3.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 255      | 2.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 250      | 2.84%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 243      | 2.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 240      | 2.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 221      | 2.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 211      | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 186      | 2.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 180      | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 165      | 1.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 157      | 1.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 141      | 1.6%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 136      | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 125      | 1.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 111      | 1.26%   |
| AMD FCH SATA Controller D                                                               | 99       | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 97       | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 96       | 1.09%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 89       | 1.01%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 88       | 1%      |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 85       | 0.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 84       | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 79       | 0.9%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 78       | 0.89%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 73       | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 70       | 0.79%   |
| AMD 600 Series Chipset SATA Controller                                                  | 67       | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 64       | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 64       | 0.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 58       | 0.66%   |
| AMD 300 Series Chipset SATA Controller                                                  | 54       | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 52       | 0.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 52       | 0.59%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 51       | 0.58%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 51       | 0.58%   |
| Nvidia MCP61 SATA Controller                                                            | 50       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4118     | 57.85%  |
| NVMe | 1542     | 21.66%  |
| IDE  | 901      | 12.66%  |
| RAID | 471      | 6.62%   |
| SAS  | 62       | 0.87%   |
| SCSI | 24       | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 3412     | 68.45%  |
| AMD     | 1572     | 31.53%  |
| Unknown | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 74       | 1.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 70       | 1.4%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 60       | 1.2%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 60       | 1.2%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 60       | 1.2%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 60       | 1.2%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 54       | 1.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 53       | 1.06%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 52       | 1.04%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 50       | 1%      |
| Intel Core i5-4590 CPU @ 3.30GHz            | 48       | 0.96%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 47       | 0.94%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 47       | 0.94%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 45       | 0.9%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 44       | 0.88%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 44       | 0.88%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 43       | 0.86%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 41       | 0.82%   |
| AMD FX-8350 Eight-Core Processor            | 41       | 0.82%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 39       | 0.78%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 37       | 0.74%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 36       | 0.72%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 34       | 0.68%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 33       | 0.66%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 32       | 0.64%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 32       | 0.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 30       | 0.6%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 30       | 0.6%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 30       | 0.6%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 30       | 0.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 28       | 0.56%   |
| AMD FX-6300 Six-Core Processor              | 28       | 0.56%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 26       | 0.52%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 26       | 0.52%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 26       | 0.52%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 26       | 0.52%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 25       | 0.5%    |
| Intel Core i5 CPU 650 @ 3.20GHz             | 25       | 0.5%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 25       | 0.5%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 24       | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 948      | 18.98%  |
| Intel Core i7           | 744      | 14.9%   |
| Intel Core i3           | 396      | 7.93%   |
| AMD Ryzen 5             | 395      | 7.91%   |
| Intel Xeon              | 352      | 7.05%   |
| Other                   | 340      | 6.81%   |
| AMD Ryzen 7             | 259      | 5.19%   |
| AMD Ryzen 9             | 185      | 3.7%    |
| AMD FX                  | 156      | 3.12%   |
| Intel Celeron           | 150      | 3%      |
| Intel Core 2 Duo        | 111      | 2.22%   |
| Intel Core 2 Quad       | 103      | 2.06%   |
| Intel Pentium           | 102      | 2.04%   |
| AMD Ryzen 3             | 77       | 1.54%   |
| AMD A10                 | 57       | 1.14%   |
| Intel Core i9           | 49       | 0.98%   |
| Intel Pentium Dual-Core | 48       | 0.96%   |
| AMD Phenom II X4        | 48       | 0.96%   |
| AMD A8                  | 40       | 0.8%    |
| AMD Ryzen Threadripper  | 39       | 0.78%   |
| AMD Athlon II X2        | 39       | 0.78%   |
| AMD A6                  | 30       | 0.6%    |
| AMD A4                  | 25       | 0.5%    |
| AMD Athlon 64 X2        | 22       | 0.44%   |
| Intel Atom              | 21       | 0.42%   |
| AMD Athlon II X4        | 21       | 0.42%   |
| Intel Core 2            | 20       | 0.4%    |
| AMD Phenom II X6        | 19       | 0.38%   |
| AMD Athlon              | 18       | 0.36%   |
| AMD Phenom II X2        | 15       | 0.3%    |
| AMD Ryzen 5 PRO         | 13       | 0.26%   |
| Intel Pentium Gold      | 12       | 0.24%   |
| Intel Pentium Dual      | 12       | 0.24%   |
| AMD Athlon II X3        | 11       | 0.22%   |
| AMD Athlon X4           | 10       | 0.2%    |
| Intel Pentium 4         | 8        | 0.16%   |
| AMD Sempron             | 8        | 0.16%   |
| AMD EPYC                | 8        | 0.16%   |
| AMD GX                  | 7        | 0.14%   |
| Intel Genuine           | 6        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2004     | 40.09%  |
| 2       | 1049     | 20.98%  |
| 6       | 755      | 15.1%   |
| 8       | 534      | 10.68%  |
| 12      | 202      | 4.04%   |
| 16      | 156      | 3.12%   |
| 1       | 69       | 1.38%   |
| 3       | 63       | 1.26%   |
| 10      | 50       | 1%      |
| 24      | 43       | 0.86%   |
| 14      | 17       | 0.34%   |
| 32      | 13       | 0.26%   |
| 28      | 13       | 0.26%   |
| 20      | 10       | 0.2%    |
| 64      | 7        | 0.14%   |
| 18      | 5        | 0.1%    |
| 36      | 4        | 0.08%   |
| 128     | 1        | 0.02%   |
| 44      | 1        | 0.02%   |
| 40      | 1        | 0.02%   |
| 22      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 4848     | 97.25%  |
| 2       | 136      | 2.73%   |
| Unknown | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 2959     | 59.26%  |
| 1       | 2031     | 40.68%  |
| 6       | 1        | 0.02%   |
| 4       | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4983     | 99.94%  |
| Unknown        | 3        | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3296     | 64.55%  |
| 0x306c3    | 175      | 3.43%   |
| 0x306a9    | 110      | 2.15%   |
| 0x506e3    | 96       | 1.88%   |
| 0x206a7    | 90       | 1.76%   |
| 0x08701021 | 74       | 1.45%   |
| 0x906ea    | 64       | 1.25%   |
| 0x906e9    | 59       | 1.16%   |
| 0x0a20120a | 46       | 0.9%    |
| 0x306f2    | 45       | 0.88%   |
| 0x90672    | 44       | 0.86%   |
| 0x0800820d | 44       | 0.86%   |
| 0x06000852 | 44       | 0.86%   |
| 0x0a201016 | 41       | 0.8%    |
| 0x0a601203 | 37       | 0.72%   |
| 0xa0671    | 36       | 0.71%   |
| 0xa0653    | 35       | 0.69%   |
| 0x1067a    | 34       | 0.67%   |
| 0x08108109 | 34       | 0.67%   |
| 0x010000c8 | 32       | 0.63%   |
| 0xa0655    | 29       | 0.57%   |
| 0x906ed    | 29       | 0.57%   |
| 0xb0671    | 25       | 0.49%   |
| 0x08701013 | 25       | 0.49%   |
| 0x406f1    | 23       | 0.45%   |
| 0x0a50000d | 22       | 0.43%   |
| 0x0a50000c | 17       | 0.33%   |
| 0x06003106 | 17       | 0.33%   |
| 0x06001119 | 16       | 0.31%   |
| 0x106e5    | 15       | 0.29%   |
| 0x906ec    | 14       | 0.27%   |
| 0x906eb    | 13       | 0.25%   |
| 0x0a201205 | 13       | 0.25%   |
| 0x0a201009 | 13       | 0.25%   |
| 0x08001138 | 13       | 0.25%   |
| 0x106a5    | 12       | 0.24%   |
| 0x20655    | 11       | 0.22%   |
| 0x0810100b | 11       | 0.22%   |
| 0x010000db | 11       | 0.22%   |
| 0x90675    | 10       | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 655      | 13.12%  |
| KabyLake         | 463      | 9.27%   |
| IvyBridge        | 379      | 7.59%   |
| SandyBridge      | 341      | 6.83%   |
| Zen 3            | 339      | 6.79%   |
| Skylake          | 322      | 6.45%   |
| Zen 2            | 268      | 5.37%   |
| Unknown          | 261      | 5.23%   |
| Penryn           | 227      | 4.55%   |
| Piledriver       | 203      | 4.06%   |
| Zen+             | 180      | 3.6%    |
| K10              | 176      | 3.52%   |
| CometLake        | 160      | 3.2%    |
| Westmere         | 133      | 2.66%   |
| Zen              | 121      | 2.42%   |
| Core             | 111      | 2.22%   |
| Alderlake Hybrid | 107      | 2.14%   |
| Nehalem          | 89       | 1.78%   |
| Broadwell        | 58       | 1.16%   |
| Icelake          | 53       | 1.06%   |
| Steamroller      | 49       | 0.98%   |
| Silvermont       | 48       | 0.96%   |
| K8 Hammer        | 34       | 0.68%   |
| Excavator        | 33       | 0.66%   |
| Goldmont plus    | 31       | 0.62%   |
| Bulldozer        | 30       | 0.6%    |
| Goldmont         | 19       | 0.38%   |
| TigerLake        | 16       | 0.32%   |
| Jaguar           | 15       | 0.3%    |
| NetBurst         | 13       | 0.26%   |
| K10 Llano        | 13       | 0.26%   |
| Tremont          | 12       | 0.24%   |
| Bonnell          | 11       | 0.22%   |
| Bobcat           | 11       | 0.22%   |
| Puma             | 8        | 0.16%   |
| Gracemont        | 5        | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 2133     | 39.41%  |
| Intel                                        | 1794     | 33.15%  |
| AMD                                          | 1405     | 25.96%  |
| ASPEED Technology                            | 48       | 0.89%   |
| Matrox Electronics Systems                   | 28       | 0.52%   |
| ATI Technologies                             | 2        | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.02%   |
| VIA Technologies                             | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 305      | 5.51%   |
| Intel HD Graphics 530                                                       | 180      | 3.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 163      | 2.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 146      | 2.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 145      | 2.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 145      | 2.62%   |
| Nvidia GK208B [GeForce GT 710]                                              | 106      | 1.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 86       | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 82       | 1.48%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 78       | 1.41%   |
| Intel HD Graphics 630                                                       | 78       | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 75       | 1.36%   |
| Nvidia GT218 [GeForce 210]                                                  | 73       | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 63       | 1.14%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 63       | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 62       | 1.12%   |
| AMD Raphael                                                                 | 61       | 1.1%    |
| Nvidia GK208B [GeForce GT 730]                                              | 59       | 1.07%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 55       | 0.99%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 54       | 0.98%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 54       | 0.98%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 54       | 0.98%   |
| Intel AlderLake-S GT1                                                       | 50       | 0.9%    |
| ASPEED Technology ASPEED Graphics Family                                    | 48       | 0.87%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 44       | 0.8%    |
| Nvidia GF119 [GeForce GT 610]                                               | 42       | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 40       | 0.72%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 39       | 0.7%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 39       | 0.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 38       | 0.69%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 38       | 0.69%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 38       | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 37       | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 36       | 0.65%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 36       | 0.65%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 36       | 0.65%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 34       | 0.61%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 34       | 0.61%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 34       | 0.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 33       | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1908     | 37.88%  |
| 1 x Intel                | 1517     | 30.12%  |
| 1 x AMD                  | 1232     | 24.46%  |
| Intel + Nvidia           | 93       | 1.85%   |
| AMD + Nvidia             | 82       | 1.63%   |
| 2 x AMD                  | 48       | 0.95%   |
| 1 x ASPEED               | 36       | 0.71%   |
| Intel + AMD              | 35       | 0.69%   |
| 2 x Nvidia               | 28       | 0.56%   |
| 1 x Matrox               | 21       | 0.42%   |
| Nvidia + ASPEED          | 9        | 0.18%   |
| Other                    | 5        | 0.1%    |
| Nvidia + Matrox          | 4        | 0.08%   |
| AMD + Matrox             | 3        | 0.06%   |
| 1 x Intel + 3 x Nvidia   | 2        | 0.04%   |
| Intel + AMD + 1 x Nvidia | 2        | 0.04%   |
| AMD + 2 x Nvidia         | 2        | 0.04%   |
| AMD + ASPEED             | 2        | 0.04%   |
| 3 x Nvidia + 1 x ASPEED  | 1        | 0.02%   |
| 3 x AMD                  | 1        | 0.02%   |
| 2 x Intel                | 1        | 0.02%   |
| 1 x XGI                  | 1        | 0.02%   |
| 1 x VIA                  | 1        | 0.02%   |
| Intel + 2 x Nvidia       | 1        | 0.02%   |
| Intel + 2 x AMD          | 1        | 0.02%   |
| Intel + AMD + 3 x Nvidia | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3469     | 68.48%  |
| Proprietary | 1318     | 26.02%  |
| Unknown     | 279      | 5.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3683     | 72.69%  |
| 1.01-2.0   | 302      | 5.96%   |
| 7.01-8.0   | 226      | 4.46%   |
| 0.51-1.0   | 222      | 4.38%   |
| 3.01-4.0   | 192      | 3.79%   |
| 0.01-0.5   | 176      | 3.47%   |
| 8.01-16.0  | 118      | 2.33%   |
| 5.01-6.0   | 75       | 1.48%   |
| 16.01-24.0 | 35       | 0.69%   |
| 2.01-3.0   | 30       | 0.59%   |
| 4.01-5.0   | 7        | 0.14%   |
| 32.01-64.0 | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 839      | 16.68%  |
| Dell                 | 614      | 12.2%   |
| Goldstar             | 487      | 9.68%   |
| Hewlett-Packard      | 356      | 7.08%   |
| Acer                 | 335      | 6.66%   |
| AOC                  | 237      | 4.71%   |
| Philips              | 228      | 4.53%   |
| BenQ                 | 222      | 4.41%   |
| Ancor Communications | 199      | 3.96%   |
| Iiyama               | 123      | 2.44%   |
| Lenovo               | 107      | 2.13%   |
| ViewSonic            | 99       | 1.97%   |
| ASUSTek Computer     | 93       | 1.85%   |
| Sony                 | 67       | 1.33%   |
| Vizio                | 44       | 0.87%   |
| Panasonic            | 40       | 0.8%    |
| Fujitsu Siemens      | 40       | 0.8%    |
| LG Electronics       | 39       | 0.78%   |
| MSI                  | 37       | 0.74%   |
| Sceptre Tech         | 35       | 0.7%    |
| Eizo                 | 35       | 0.7%    |
| Unknown              | 32       | 0.64%   |
| NEC Computers        | 32       | 0.64%   |
| HannStar             | 25       | 0.5%    |
| Unknown              | 22       | 0.44%   |
| Medion               | 21       | 0.42%   |
| Toshiba              | 20       | 0.4%    |
| Gigabyte Technology  | 20       | 0.4%    |
| HKC                  | 17       | 0.34%   |
| Apple                | 17       | 0.34%   |
| Sharp                | 16       | 0.32%   |
| RTK                  | 15       | 0.3%    |
| Unknown (XXX)        | 13       | 0.26%   |
| Vestel Elektronik    | 12       | 0.24%   |
| HUAWEI               | 11       | 0.22%   |
| Hitachi              | 11       | 0.22%   |
| Gericom              | 11       | 0.22%   |
| Belinea              | 11       | 0.22%   |
| Plain Tree Systems   | 10       | 0.2%    |
| MStar                | 10       | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 27       | 0.51%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                       | 23       | 0.43%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 22       | 0.41%   |
| Unknown                                                                 | 22       | 0.41%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 20       | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 19       | 0.36%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                      | 19       | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 17       | 0.32%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 17       | 0.32%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 16       | 0.3%    |
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                     | 15       | 0.28%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                        | 15       | 0.28%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 14       | 0.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 13       | 0.24%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch    | 12       | 0.22%   |
| Sony TV SNY3102 1920x1080 708x398mm 32.0-inch                           | 12       | 0.22%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                      | 12       | 0.22%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                      | 12       | 0.22%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                        | 12       | 0.22%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 12       | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 11       | 0.21%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                | 11       | 0.21%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 11       | 0.21%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                 | 11       | 0.21%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                       | 11       | 0.21%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                      | 11       | 0.21%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 10       | 0.19%   |
| Gericom Q26 QMX2426 1920x1080 550x344mm 25.5-inch                       | 10       | 0.19%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch   | 10       | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 9        | 0.17%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 9        | 0.17%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                     | 9        | 0.17%   |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                         | 9        | 0.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 8        | 0.15%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 8        | 0.15%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 8        | 0.15%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                   | 8        | 0.15%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                  | 8        | 0.15%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                      | 8        | 0.15%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch        | 8        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2336     | 47.52%  |
| 3840x2160 (4K)     | 561      | 11.41%  |
| 2560x1440 (QHD)    | 339      | 6.9%    |
| 1280x1024 (SXGA)   | 268      | 5.45%   |
| 1680x1050 (WSXGA+) | 241      | 4.9%    |
| 1366x768 (WXGA)    | 181      | 3.68%   |
| 1920x1200 (WUXGA)  | 158      | 3.21%   |
| 1440x900 (WXGA+)   | 147      | 2.99%   |
| 1600x900 (HD+)     | 143      | 2.91%   |
| 3440x1440          | 78       | 1.59%   |
| 2560x1080          | 67       | 1.36%   |
| Unknown            | 61       | 1.24%   |
| 1360x768           | 60       | 1.22%   |
| 1920x540           | 45       | 0.92%   |
| 3840x1080          | 35       | 0.71%   |
| 1024x768 (XGA)     | 35       | 0.71%   |
| 1280x720 (HD)      | 24       | 0.49%   |
| 1600x1200          | 20       | 0.41%   |
| 2560x1600          | 15       | 0.31%   |
| 2288x1287          | 13       | 0.26%   |
| 3840x1600          | 12       | 0.24%   |
| 1400x1050          | 10       | 0.2%    |
| 2048x1152          | 7        | 0.14%   |
| 1280x960           | 7        | 0.14%   |
| 3840x1200          | 5        | 0.1%    |
| 4480x1440          | 4        | 0.08%   |
| 5120x1440          | 3        | 0.06%   |
| 3600x1080          | 3        | 0.06%   |
| 3360x1080          | 3        | 0.06%   |
| 3200x1080          | 3        | 0.06%   |
| 5760x1080          | 2        | 0.04%   |
| 3520x1080          | 2        | 0.04%   |
| 1280x768           | 2        | 0.04%   |
| 7680x2160          | 1        | 0.02%   |
| 720x480            | 1        | 0.02%   |
| 6400x2160          | 1        | 0.02%   |
| 5760x2160          | 1        | 0.02%   |
| 5520x1080          | 1        | 0.02%   |
| 5120x1080          | 1        | 0.02%   |
| 4480x1080          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 734      | 14.56%  |
| 27      | 727      | 14.42%  |
| 23      | 637      | 12.64%  |
| 21      | 546      | 10.83%  |
| Unknown | 333      | 6.61%   |
| 19      | 307      | 6.09%   |
| 31      | 267      | 5.3%    |
| 18      | 167      | 3.31%   |
| 22      | 162      | 3.21%   |
| 20      | 158      | 3.13%   |
| 17      | 135      | 2.68%   |
| 34      | 119      | 2.36%   |
| 84      | 91       | 1.81%   |
| 32      | 68       | 1.35%   |
| 15      | 65       | 1.29%   |
| 72      | 55       | 1.09%   |
| 54      | 54       | 1.07%   |
| 40      | 53       | 1.05%   |
| 25      | 40       | 0.79%   |
| 28      | 24       | 0.48%   |
| 26      | 22       | 0.44%   |
| 46      | 21       | 0.42%   |
| 42      | 19       | 0.38%   |
| 37      | 19       | 0.38%   |
| 43      | 18       | 0.36%   |
| 52      | 17       | 0.34%   |
| 65      | 15       | 0.3%    |
| 49      | 15       | 0.3%    |
| 29      | 15       | 0.3%    |
| 36      | 14       | 0.28%   |
| 48      | 12       | 0.24%   |
| 14      | 9        | 0.18%   |
| 142     | 7        | 0.14%   |
| 35      | 7        | 0.14%   |
| 12      | 7        | 0.14%   |
| 74      | 6        | 0.12%   |
| 64      | 6        | 0.12%   |
| 60      | 6        | 0.12%   |
| 33      | 6        | 0.12%   |
| 16      | 6        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1952     | 39.91%  |
| 401-500        | 1173     | 23.98%  |
| 601-700        | 389      | 7.95%   |
| Unknown        | 333      | 6.81%   |
| 701-800        | 207      | 4.23%   |
| 301-350        | 193      | 3.95%   |
| 1001-1500      | 166      | 3.39%   |
| 351-400        | 165      | 3.37%   |
| 1501-2000      | 162      | 3.31%   |
| 801-900        | 87       | 1.78%   |
| 901-1000       | 39       | 0.8%    |
| 201-300        | 17       | 0.35%   |
| More than 2000 | 8        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3233     | 69.24%  |
| 16/10   | 597      | 12.79%  |
| 5/4     | 266      | 5.7%    |
| Unknown | 264      | 5.65%   |
| 21/9    | 152      | 3.26%   |
| 4/3     | 72       | 1.54%   |
| 32/9    | 30       | 0.64%   |
| 3/2     | 20       | 0.43%   |
| 6/5     | 13       | 0.28%   |
| 1.00    | 10       | 0.21%   |
| 2.00    | 3        | 0.06%   |
| 0.56    | 3        | 0.06%   |
| 2.12    | 2        | 0.04%   |
| 1.96    | 2        | 0.04%   |
| 3.20    | 1        | 0.02%   |
| 0.89    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1621     | 32.83%  |
| 301-350        | 741      | 15.01%  |
| 151-200        | 628      | 12.72%  |
| 351-500        | 488      | 9.88%   |
| Unknown        | 333      | 6.74%   |
| More than 1000 | 293      | 5.93%   |
| 251-300        | 293      | 5.93%   |
| 141-150        | 263      | 5.33%   |
| 501-1000       | 180      | 3.65%   |
| 101-110        | 58       | 1.17%   |
| 71-80          | 10       | 0.2%    |
| 111-120        | 10       | 0.2%    |
| 131-140        | 9        | 0.18%   |
| 81-90          | 5        | 0.1%    |
| 91-100         | 3        | 0.06%   |
| 121-130        | 2        | 0.04%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2983     | 62.96%  |
| 101-120       | 833      | 17.58%  |
| Unknown       | 333      | 7.03%   |
| 1-50          | 242      | 5.11%   |
| 121-160       | 241      | 5.09%   |
| 161-240       | 105      | 2.22%   |
| More than 240 | 1        | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3728     | 73.31%  |
| 2     | 804      | 15.81%  |
| 0     | 455      | 8.95%   |
| 3     | 85       | 1.67%   |
| 4     | 11       | 0.22%   |
| 6     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2957     | 41.74%  |
| Intel                           | 2344     | 33.09%  |
| Qualcomm Atheros                | 348      | 4.91%   |
| Broadcom                        | 210      | 2.96%   |
| TP-Link                         | 151      | 2.13%   |
| Ralink Technology               | 127      | 1.79%   |
| MediaTek                        | 109      | 1.54%   |
| Nvidia                          | 85       | 1.2%    |
| Ralink                          | 69       | 0.97%   |
| Aquantia                        | 50       | 0.71%   |
| NetGear                         | 48       | 0.68%   |
| Broadcom Limited                | 46       | 0.65%   |
| Marvell Technology Group        | 37       | 0.52%   |
| Qualcomm Atheros Communications | 34       | 0.48%   |
| Microsoft                       | 34       | 0.48%   |
| ASIX Electronics                | 34       | 0.48%   |
| Samsung Electronics             | 31       | 0.44%   |
| D-Link System                   | 29       | 0.41%   |
| D-Link                          | 24       | 0.34%   |
| Xiaomi                          | 22       | 0.31%   |
| ASUSTek Computer                | 22       | 0.31%   |
| Edimax Technology               | 20       | 0.28%   |
| Linksys                         | 17       | 0.24%   |
| IMC Networks                    | 15       | 0.21%   |
| DisplayLink                     | 13       | 0.18%   |
| Mellanox Technologies           | 11       | 0.16%   |
| Qualcomm                        | 9        | 0.13%   |
| AVM                             | 9        | 0.13%   |
| Sitecom Europe                  | 7        | 0.1%    |
| Mercucys                        | 7        | 0.1%    |
| Huawei Technologies             | 6        | 0.08%   |
| Google                          | 6        | 0.08%   |
| BUFFALO                         | 6        | 0.08%   |
| Belkin Components               | 6        | 0.08%   |
| Arduino SA                      | 6        | 0.08%   |
| ZyDAS                           | 5        | 0.07%   |
| ZTE WCDMA Technologies MSM      | 5        | 0.07%   |
| VIA Technologies                | 5        | 0.07%   |
| OPPO Electronics                | 5        | 0.07%   |
| ICS Advent                      | 5        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2272     | 27.85%  |
| Realtek RTL8125 2.5GbE Controller                                      | 333      | 4.08%   |
| Intel I211 Gigabit Network Connection                                  | 235      | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 226      | 2.77%   |
| Intel Wi-Fi 6 AX200                                                    | 202      | 2.48%   |
| Intel Ethernet Controller I225-V                                       | 186      | 2.28%   |
| Intel Ethernet Connection I217-LM                                      | 169      | 2.07%   |
| Intel Ethernet Connection (2) I219-V                                   | 169      | 2.07%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 110      | 1.35%   |
| Intel Ethernet Connection (7) I219-V                                   | 97       | 1.19%   |
| Intel 82579V Gigabit Network Connection                                | 94       | 1.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 88       | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 85       | 1.04%   |
| Realtek 802.11ac NIC                                                   | 84       | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 81       | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                                  | 81       | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 73       | 0.89%   |
| Intel Ethernet Connection I217-V                                       | 65       | 0.8%    |
| Intel Ethernet Connection (2) I218-V                                   | 62       | 0.76%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 54       | 0.66%   |
| Intel 82574L Gigabit Network Connection                                | 53       | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 51       | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 50       | 0.61%   |
| Ralink MT7601U Wireless Adapter                                        | 50       | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 47       | 0.58%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 46       | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 46       | 0.56%   |
| Nvidia MCP61 Ethernet                                                  | 45       | 0.55%   |
| Intel Wireless 7265                                                    | 45       | 0.55%   |
| Intel I210 Gigabit Network Connection                                  | 45       | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 42       | 0.51%   |
| Intel Wireless 7260                                                    | 42       | 0.51%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 42       | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                                  | 40       | 0.49%   |
| Intel I350 Gigabit Network Connection                                  | 35       | 0.43%   |
| Intel Ethernet Controller I226-V                                       | 35       | 0.43%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 35       | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 33       | 0.4%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 33       | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                                  | 33       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 841      | 34.13%  |
| Realtek Semiconductor                 | 587      | 23.82%  |
| Qualcomm Atheros                      | 198      | 8.04%   |
| TP-Link                               | 148      | 6.01%   |
| Ralink Technology                     | 127      | 5.15%   |
| MediaTek                              | 102      | 4.14%   |
| Broadcom                              | 80       | 3.25%   |
| Ralink                                | 69       | 2.8%    |
| NetGear                               | 48       | 1.95%   |
| Qualcomm Atheros Communications       | 34       | 1.38%   |
| Microsoft                             | 34       | 1.38%   |
| D-Link                                | 23       | 0.93%   |
| D-Link System                         | 21       | 0.85%   |
| Broadcom Limited                      | 21       | 0.85%   |
| ASUSTek Computer                      | 21       | 0.85%   |
| Edimax Technology                     | 20       | 0.81%   |
| IMC Networks                          | 15       | 0.61%   |
| Linksys                               | 14       | 0.57%   |
| AVM                                   | 9        | 0.37%   |
| Sitecom Europe                        | 7        | 0.28%   |
| Mercucys                              | 7        | 0.28%   |
| BUFFALO                               | 6        | 0.24%   |
| Belkin Components                     | 6        | 0.24%   |
| ZyDAS                                 | 5        | 0.2%    |
| Wilocity                              | 4        | 0.16%   |
| Micro Star International              | 3        | 0.12%   |
| Gemtek                                | 2        | 0.08%   |
| Encore Electronics                    | 2        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.08%   |
| ZyXEL Communications                  | 1        | 0.04%   |
| TRENDnet                              | 1        | 0.04%   |
| Sierra Wireless                       | 1        | 0.04%   |
| Sagem                                 | 1        | 0.04%   |
| Philips (or NXP)                      | 1        | 0.04%   |
| LSI                                   | 1        | 0.04%   |
| Guillemot                             | 1        | 0.04%   |
| Dell                                  | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 202      | 8.07%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 110      | 4.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 85       | 3.39%   |
| Realtek 802.11ac NIC                                          | 84       | 3.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 81       | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 73       | 2.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 54       | 2.16%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 51       | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 50       | 2%      |
| Ralink MT7601U Wireless Adapter                               | 50       | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 46       | 1.84%   |
| Intel Wireless 7265                                           | 45       | 1.8%    |
| Intel Wireless 7260                                           | 42       | 1.68%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 42       | 1.68%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 35       | 1.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 33       | 1.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 33       | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 31       | 1.24%   |
| Intel Wireless 3165                                           | 30       | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                | 30       | 1.2%    |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 29       | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                               | 28       | 1.12%   |
| Ralink RT5370 Wireless Adapter                                | 27       | 1.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 26       | 1.04%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 26       | 1.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 25       | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 25       | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 24       | 0.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 23       | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 23       | 0.92%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 23       | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 23       | 0.92%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 22       | 0.88%   |
| Intel Wireless 8260                                           | 22       | 0.88%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 20       | 0.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 19       | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 19       | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 18       | 0.72%   |
| TP-Link 802.11ac NIC                                          | 17       | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 17       | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2754     | 51.19%  |
| Intel                                  | 1921     | 35.71%  |
| Qualcomm Atheros                       | 169      | 3.14%   |
| Broadcom                               | 133      | 2.47%   |
| Nvidia                                 | 85       | 1.58%   |
| Aquantia                               | 50       | 0.93%   |
| Marvell Technology Group               | 37       | 0.69%   |
| ASIX Electronics                       | 34       | 0.63%   |
| Samsung Electronics                    | 31       | 0.58%   |
| Broadcom Limited                       | 25       | 0.46%   |
| Xiaomi                                 | 22       | 0.41%   |
| DisplayLink                            | 13       | 0.24%   |
| Qualcomm                               | 9        | 0.17%   |
| D-Link System                          | 8        | 0.15%   |
| MediaTek                               | 6        | 0.11%   |
| Google                                 | 6        | 0.11%   |
| ZTE WCDMA Technologies MSM             | 5        | 0.09%   |
| VIA Technologies                       | 5        | 0.09%   |
| OPPO Electronics                       | 5        | 0.09%   |
| Mellanox Technologies                  | 5        | 0.09%   |
| ICS Advent                             | 5        | 0.09%   |
| Huawei Technologies                    | 5        | 0.09%   |
| TP-Link                                | 4        | 0.07%   |
| JMicron Technology                     | 4        | 0.07%   |
| Chelsio Communications                 | 4        | 0.07%   |
| Linksys                                | 3        | 0.06%   |
| American Megatrends                    | 3        | 0.06%   |
| 3Com                                   | 3        | 0.06%   |
| Tehuti Networks                        | 2        | 0.04%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.04%   |
| Apple                                  | 2        | 0.04%   |
| Vimtron Electronics                    | 1        | 0.02%   |
| Spreadtrum Communications              | 1        | 0.02%   |
| QNAP System                            | 1        | 0.02%   |
| QLogic                                 | 1        | 0.02%   |
| QinHeng Electronics                    | 1        | 0.02%   |
| Prolific Technology                    | 1        | 0.02%   |
| Novatel Wireless                       | 1        | 0.02%   |
| Netchip Technology                     | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 2272     | 40.65%  |
| Realtek RTL8125 2.5GbE Controller                                              | 333      | 5.96%   |
| Intel I211 Gigabit Network Connection                                          | 235      | 4.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 226      | 4.04%   |
| Intel Ethernet Controller I225-V                                               | 186      | 3.33%   |
| Intel Ethernet Connection I217-LM                                              | 169      | 3.02%   |
| Intel Ethernet Connection (2) I219-V                                           | 169      | 3.02%   |
| Intel Ethernet Connection (7) I219-V                                           | 97       | 1.74%   |
| Intel 82579V Gigabit Network Connection                                        | 94       | 1.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 88       | 1.57%   |
| Intel Ethernet Connection (2) I219-LM                                          | 81       | 1.45%   |
| Intel Ethernet Connection I217-V                                               | 65       | 1.16%   |
| Intel Ethernet Connection (2) I218-V                                           | 62       | 1.11%   |
| Intel 82574L Gigabit Network Connection                                        | 53       | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 47       | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 46       | 0.82%   |
| Nvidia MCP61 Ethernet                                                          | 45       | 0.81%   |
| Intel I210 Gigabit Network Connection                                          | 45       | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 42       | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                          | 40       | 0.72%   |
| Intel I350 Gigabit Network Connection                                          | 35       | 0.63%   |
| Intel Ethernet Controller I226-V                                               | 35       | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                                          | 33       | 0.59%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 32       | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 30       | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 27       | 0.48%   |
| Intel Ethernet Connection (14) I219-V                                          | 26       | 0.47%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 25       | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 23       | 0.41%   |
| Intel Ethernet Connection (17) I219-V                                          | 23       | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 22       | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 22       | 0.39%   |
| Intel 82578DC Gigabit Network Connection                                       | 22       | 0.39%   |
| Intel Ethernet Connection (2) I218-LM                                          | 21       | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 20       | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 20       | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 20       | 0.36%   |
| Intel Ethernet Controller X550                                                 | 20       | 0.36%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 19       | 0.34%   |
| Intel 82578DM Gigabit Network Connection                                       | 18       | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4944     | 67.61%  |
| WiFi     | 2303     | 31.5%   |
| Modem    | 53       | 0.72%   |
| Unknown  | 12       | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3928     | 75.32%  |
| WiFi     | 1287     | 24.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3039     | 60.66%  |
| 2     | 1628     | 32.5%   |
| 3     | 240      | 4.79%   |
| 4     | 47       | 0.94%   |
| 0     | 30       | 0.6%    |
| 5     | 17       | 0.34%   |
| 7     | 4        | 0.08%   |
| 8     | 2        | 0.04%   |
| 17    | 1        | 0.02%   |
| 9     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3348     | 66.64%  |
| Yes  | 1676     | 33.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 776      | 44.8%   |
| Cambridge Silicon Radio         | 319      | 18.42%  |
| Realtek Semiconductor           | 131      | 7.56%   |
| ASUSTek Computer                | 103      | 5.95%   |
| Broadcom                        | 71       | 4.1%    |
| Qualcomm Atheros Communications | 68       | 3.93%   |
| MediaTek                        | 59       | 3.41%   |
| IMC Networks                    | 44       | 2.54%   |
| TP-Link                         | 34       | 1.96%   |
| Apple                           | 27       | 1.56%   |
| Lite-On Technology              | 20       | 1.15%   |
| Foxconn / Hon Hai               | 14       | 0.81%   |
| Belkin Components               | 8        | 0.46%   |
| Realtek                         | 6        | 0.35%   |
| Integrated System Solution      | 6        | 0.35%   |
| Edimax Technology               | 6        | 0.35%   |
| Dell                            | 5        | 0.29%   |
| Micro Star International        | 4        | 0.23%   |
| Logitech                        | 4        | 0.23%   |
| Dynex                           | 4        | 0.23%   |
| Unknown                         | 4        | 0.23%   |
| Actions                         | 3        | 0.17%   |
| Toshiba                         | 2        | 0.12%   |
| Ralink                          | 2        | 0.12%   |
| HTC (High Tech Computer)        | 2        | 0.12%   |
| Hewlett-Packard                 | 2        | 0.12%   |
| D-Link System                   | 2        | 0.12%   |
| Conwise Technology              | 2        | 0.12%   |
| TRENDnet                        | 1        | 0.06%   |
| Primax Electronics              | 1        | 0.06%   |
| Mobile Action Technology        | 1        | 0.06%   |
| D-Link                          | 1        | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 319      | 18.4%   |
| Intel AX200 Bluetooth                                 | 173      | 9.98%   |
| Intel Bluetooth wireless interface                    | 149      | 8.59%   |
| Intel AX210 Bluetooth                                 | 109      | 6.29%   |
| Realtek Bluetooth Radio                               | 107      | 6.17%   |
| Intel AX201 Bluetooth                                 | 97       | 5.59%   |
| Intel Wireless-AC 3168 Bluetooth                      | 83       | 4.79%   |
| MediaTek Wireless_Device                              | 59       | 3.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 59       | 3.4%    |
| Intel Bluetooth Device                                | 52       | 3%      |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 42       | 2.42%   |
| TP-Link UB500 Adapter                                 | 34       | 1.96%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 34       | 1.96%   |
| ASUS ASUS USB-BT500                                   | 30       | 1.73%   |
| Qualcomm Atheros  Bluetooth Device                    | 28       | 1.61%   |
| IMC Networks Bluetooth Radio                          | 25       | 1.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 25       | 1.44%   |
| Realtek  Bluetooth 4.2 Adapter                        | 21       | 1.21%   |
| ASUS Bluetooth Radio                                  | 18       | 1.04%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 17       | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 14       | 0.81%   |
| IMC Networks Wireless_Device                          | 13       | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                     | 12       | 0.69%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 10       | 0.58%   |
| Lite-On Bluetooth Device                              | 9        | 0.52%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 9        | 0.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 9        | 0.52%   |
| Apple Bluetooth Host Controller                       | 9        | 0.52%   |
| ASUS Qualcomm Bluetooth 4.1                           | 8        | 0.46%   |
| Broadcom BCM2045 Bluetooth                            | 7        | 0.4%    |
| Realtek Bluetooth Radio                               | 6        | 0.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 6        | 0.35%   |
| ASUS BCM20702A0                                       | 6        | 0.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 5        | 0.29%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 5        | 0.29%   |
| Integrated System Solution Bluetooth Device           | 5        | 0.29%   |
| Edimax Bluetooth Adapter                              | 5        | 0.29%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 5        | 0.29%   |
| ASUS Bluetooth Device                                 | 5        | 0.29%   |
| Apple Bluetooth HCI                                   | 5        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 3248     | 39.58%  |
| Nvidia                                       | 2022     | 24.64%  |
| AMD                                          | 1937     | 23.6%   |
| C-Media Electronics                          | 161      | 1.96%   |
| Logitech                                     | 90       | 1.1%    |
| Creative Labs                                | 74       | 0.9%    |
| ASUSTek Computer                             | 65       | 0.79%   |
| Micro Star International                     | 39       | 0.48%   |
| GN Netcom                                    | 39       | 0.48%   |
| Texas Instruments                            | 34       | 0.41%   |
| Kingston Technology                          | 30       | 0.37%   |
| JMTek                                        | 27       | 0.33%   |
| Razer USA                                    | 23       | 0.28%   |
| Generalplus Technology                       | 22       | 0.27%   |
| Corsair                                      | 22       | 0.27%   |
| SteelSeries ApS                              | 21       | 0.26%   |
| Focusrite-Novation                           | 21       | 0.26%   |
| Creative Technology                          | 21       | 0.26%   |
| Plantronics                                  | 15       | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 14       | 0.17%   |
| KTMicro                                      | 10       | 0.12%   |
| Hewlett-Packard                              | 10       | 0.12%   |
| Giga-Byte Technology                         | 10       | 0.12%   |
| Tenx Technology                              | 9        | 0.11%   |
| Dell                                         | 9        | 0.11%   |
| VIA Technologies                             | 8        | 0.1%    |
| Realtek Semiconductor                        | 8        | 0.1%    |
| Blue Microphones                             | 8        | 0.1%    |
| Sennheiser Communications                    | 7        | 0.09%   |
| M-Audio                                      | 7        | 0.09%   |
| Astro Gaming                                 | 7        | 0.09%   |
| Apple                                        | 7        | 0.09%   |
| Sony                                         | 6        | 0.07%   |
| BR23                                         | 6        | 0.07%   |
| Samson Technologies                          | 5        | 0.06%   |
| Yamaha                                       | 4        | 0.05%   |
| Syntek                                       | 4        | 0.05%   |
| Microsoft                                    | 4        | 0.05%   |
| DSEA A/S                                     | 4        | 0.05%   |
| Bose                                         | 4        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 470      | 4.94%   |
| AMD Starship/Matisse HD Audio Controller                                   | 464      | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 359      | 3.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 336      | 3.53%   |
| AMD Family 17h/19h HD Audio Controller                                     | 313      | 3.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 291      | 3.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 289      | 3.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 273      | 2.87%   |
| Intel 200 Series PCH HD Audio                                              | 261      | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 192      | 2.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 179      | 1.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 172      | 1.81%   |
| AMD FCH Azalia Controller                                                  | 164      | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 162      | 1.7%    |
| Intel Alder Lake-S HD Audio Controller                                     | 136      | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 136      | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 134      | 1.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 131      | 1.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 128      | 1.35%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 125      | 1.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 116      | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                              | 111      | 1.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 111      | 1.17%   |
| Nvidia High Definition Audio Controller                                    | 110      | 1.16%   |
| Nvidia GA102 High Definition Audio Controller                              | 103      | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 102      | 1.07%   |
| Nvidia GP104 High Definition Audio Controller                              | 101      | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 99       | 1.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 99       | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                              | 91       | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 86       | 0.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 86       | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 82       | 0.86%   |
| Nvidia GA106 High Definition Audio Controller                              | 80       | 0.84%   |
| Nvidia GF119 HDMI Audio Controller                                         | 77       | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 75       | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 74       | 0.78%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 71       | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 68       | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                              | 67       | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 465      | 17.64%  |
| Corsair                      | 382      | 14.49%  |
| Samsung Electronics          | 313      | 11.87%  |
| SK hynix                     | 258      | 9.79%   |
| Crucial                      | 209      | 7.93%   |
| G.Skill                      | 208      | 7.89%   |
| Unknown                      | 205      | 7.78%   |
| Micron Technology            | 152      | 5.77%   |
| A-DATA Technology            | 71       | 2.69%   |
| Unknown                      | 50       | 1.9%    |
| Team                         | 47       | 1.78%   |
| Patriot                      | 26       | 0.99%   |
| Ramaxel Technology           | 23       | 0.87%   |
| Nanya Technology             | 20       | 0.76%   |
| Unknown (ABCD)               | 14       | 0.53%   |
| Transcend                    | 11       | 0.42%   |
| Elpida                       | 11       | 0.42%   |
| Smart                        | 10       | 0.38%   |
| Apacer                       | 8        | 0.3%    |
| AMD                          | 8        | 0.3%    |
| PNY                          | 7        | 0.27%   |
| Hewlett-Packard              | 6        | 0.23%   |
| GOODRAM                      | 6        | 0.23%   |
| ASint Technology             | 6        | 0.23%   |
| Unknown (0x1636)             | 5        | 0.19%   |
| Timetec                      | 5        | 0.19%   |
| Silicon Power                | 5        | 0.19%   |
| Patriot Memory (PDP Systems) | 5        | 0.19%   |
| Lexar                        | 5        | 0.19%   |
| Avant                        | 5        | 0.19%   |
| Asgard                       | 5        | 0.19%   |
| KETECH                       | 4        | 0.15%   |
| Innodisk                     | 4        | 0.15%   |
| GeIL                         | 4        | 0.15%   |
| Atermiter                    | 4        | 0.15%   |
| Unifosa                      | 3        | 0.11%   |
| Neo Forza                    | 3        | 0.11%   |
| KLEVV                        | 3        | 0.11%   |
| Kingmax                      | 3        | 0.11%   |
| Hikvision                    | 3        | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 50       | 1.76%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 27       | 0.95%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 23       | 0.81%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 18       | 0.63%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 18       | 0.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 17       | 0.6%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 17       | 0.6%    |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 17       | 0.6%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 15       | 0.53%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 15       | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 14       | 0.49%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s            | 14       | 0.49%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 14       | 0.49%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 14       | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 13       | 0.46%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 13       | 0.46%   |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s          | 12       | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 11       | 0.39%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s            | 11       | 0.39%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 11       | 0.39%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 11       | 0.39%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 10       | 0.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 10       | 0.35%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 10       | 0.35%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 9        | 0.32%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 9        | 0.32%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s           | 9        | 0.32%   |
| Kingston RAM KF556C40-32 32GB DIMM 5808MT/s                    | 9        | 0.32%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 9        | 0.32%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 9        | 0.32%   |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s          | 9        | 0.32%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s         | 9        | 0.32%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s          | 9        | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 8        | 0.28%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 8        | 0.28%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 8        | 0.28%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 8        | 0.28%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s            | 8        | 0.28%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 8        | 0.28%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 8        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1240     | 52.72%  |
| DDR3         | 717      | 30.48%  |
| DDR5         | 123      | 5.23%   |
| Unknown      | 91       | 3.87%   |
| SDRAM        | 62       | 2.64%   |
| DDR2         | 61       | 2.59%   |
| LPDDR4       | 25       | 1.06%   |
| DDR          | 15       | 0.64%   |
| DRAM         | 11       | 0.47%   |
| LPDDR3       | 4        | 0.17%   |
| LPDDR5       | 2        | 0.09%   |
| DDR2 FB-DIMM | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2074     | 89.59%  |
| SODIMM       | 211      | 9.11%   |
| Row Of Chips | 11       | 0.48%   |
| RIMM         | 11       | 0.48%   |
| FB-DIMM      | 6        | 0.26%   |
| Chip         | 1        | 0.04%   |
| Unknown      | 1        | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 888      | 35.53%  |
| 16384  | 565      | 22.61%  |
| 4096   | 541      | 21.65%  |
| 32768  | 228      | 9.12%   |
| 2048   | 226      | 9.04%   |
| 1024   | 39       | 1.56%   |
| 65536  | 5        | 0.2%    |
| 49152  | 3        | 0.12%   |
| 512    | 3        | 0.12%   |
| 131072 | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 438      | 16.97%  |
| 3200    | 340      | 13.17%  |
| 1333    | 228      | 8.83%   |
| 2400    | 193      | 7.48%   |
| 2667    | 171      | 6.63%   |
| 3600    | 169      | 6.55%   |
| 2133    | 117      | 4.53%   |
| 1867    | 61       | 2.36%   |
| 800     | 55       | 2.13%   |
| 3000    | 50       | 1.94%   |
| 2666    | 48       | 1.86%   |
| 4800    | 46       | 1.78%   |
| 3800    | 40       | 1.55%   |
| 3733    | 39       | 1.51%   |
| 2933    | 35       | 1.36%   |
| 1800    | 35       | 1.36%   |
| 667     | 32       | 1.24%   |
| 3533    | 28       | 1.08%   |
| 3400    | 27       | 1.05%   |
| 1066    | 27       | 1.05%   |
| 1866    | 26       | 1.01%   |
| 5600    | 22       | 0.85%   |
| Unknown | 18       | 0.7%    |
| 6000    | 17       | 0.66%   |
| 3534    | 17       | 0.66%   |
| 3066    | 17       | 0.66%   |
| 3466    | 16       | 0.62%   |
| 1067    | 14       | 0.54%   |
| 5200    | 13       | 0.5%    |
| 3266    | 13       | 0.5%    |
| 3666    | 12       | 0.46%   |
| 3866    | 11       | 0.43%   |
| 6400    | 10       | 0.39%   |
| 3500    | 10       | 0.39%   |
| 2000    | 10       | 0.39%   |
| 1334    | 10       | 0.39%   |
| 5808    | 9        | 0.35%   |
| 3933    | 9        | 0.35%   |
| 2465    | 9        | 0.35%   |
| 1648    | 9        | 0.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 82       | 34.89%  |
| Brother Industries     | 52       | 22.13%  |
| Canon                  | 30       | 12.77%  |
| Seiko Epson            | 23       | 9.79%   |
| Samsung Electronics    | 21       | 8.94%   |
| Dymo-CoStar            | 6        | 2.55%   |
| Lexmark International  | 4        | 1.7%    |
| Prolific Technology    | 3        | 1.28%   |
| STMicroelectronics     | 2        | 0.85%   |
| QinHeng Electronics    | 2        | 0.85%   |
| Kyocera                | 2        | 0.85%   |
| Zebra                  | 1        | 0.43%   |
| Xerox                  | 1        | 0.43%   |
| SAT                    | 1        | 0.43%   |
| Pantum                 | 1        | 0.43%   |
| Oki Data               | 1        | 0.43%   |
| Fuji Xerox             | 1        | 0.43%   |
| Custom Engineering SPA | 1        | 0.43%   |
| Apple                  | 1        | 0.43%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP DeskJet 2130 series                                    | 5        | 2.08%   |
| Dymo-CoStar LabelWriter 400                               | 5        | 2.08%   |
| Seiko Epson L360 Series                                   | 3        | 1.25%   |
| Seiko Epson L3150 Series                                  | 3        | 1.25%   |
| Seiko Epson ET-2720 Series                                | 3        | 1.25%   |
| Samsung Composite Device                                  | 3        | 1.25%   |
| Prolific PL2305 Parallel Port                             | 3        | 1.25%   |
| HP OfficeJet Pro 8020 series                              | 3        | 1.25%   |
| HP OfficeJet 3830 series                                  | 3        | 1.25%   |
| HP LaserJet P1005                                         | 3        | 1.25%   |
| HP DeskJet 3700 series                                    | 3        | 1.25%   |
| Canon TS3100 series                                       | 3        | 1.25%   |
| Brother Printer                                           | 3        | 1.25%   |
| Brother MFC-L2700DW                                       | 3        | 1.25%   |
| Brother HL-L2350DW series                                 | 3        | 1.25%   |
| Brother HL-1440 Laser Printer                             | 3        | 1.25%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2        | 0.83%   |
| Seiko Epson XP-2100 Series                                | 2        | 0.83%   |
| Seiko Epson L3250 Series                                  | 2        | 0.83%   |
| Seiko Epson ET-4800 Series                                | 2        | 0.83%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 0.83%   |
| Samsung M2070 Series                                      | 2        | 0.83%   |
| Samsung C460 Series                                       | 2        | 0.83%   |
| QinHeng CH340S                                            | 2        | 0.83%   |
| HP OfficeJet 5600 (USBHUB)                                | 2        | 0.83%   |
| HP Officejet 4500 G510n-z                                 | 2        | 0.83%   |
| HP LaserJet M203-M206                                     | 2        | 0.83%   |
| HP LaserJet 4250                                          | 2        | 0.83%   |
| HP LaserJet 3015                                          | 2        | 0.83%   |
| HP HP LaserJet M14-M17                                    | 2        | 0.83%   |
| HP ENVY 5540 series                                       | 2        | 0.83%   |
| HP ENVY 4520 series                                       | 2        | 0.83%   |
| HP ENVY 4500 series                                       | 2        | 0.83%   |
| HP DeskJet 4100 series                                    | 2        | 0.83%   |
| HP DeskJet 3630 series                                    | 2        | 0.83%   |
| HP Deskjet 3050A                                          | 2        | 0.83%   |
| HP DeskJet 2600 series                                    | 2        | 0.83%   |
| HP Deskjet 2510 series                                    | 2        | 0.83%   |
| HP DeskJet 2300 series                                    | 2        | 0.83%   |
| HP DeskJet 1110 series                                    | 2        | 0.83%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 24       | 57.14%  |
| Seiko Epson                 | 9        | 21.43%  |
| Hewlett-Packard             | 6        | 14.29%  |
| UMAX                        | 1        | 2.38%   |
| Ultima Electronics          | 1        | 2.38%   |
| Acer Peripherals (now BenQ) | 1        | 2.38%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 120                                                               | 6        | 14.29%  |
| Canon CanoScan LiDE 220                                                               | 4        | 9.52%   |
| Canon CanoScan LiDE 100                                                               | 3        | 7.14%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 2        | 4.76%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 2        | 4.76%   |
| Canon CanoScan LiDE 110                                                               | 2        | 4.76%   |
| UMAX Astra 2200/2200SU                                                                | 1        | 2.38%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 2.38%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 2.38%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1        | 2.38%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 2.38%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 2.38%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1        | 2.38%   |
| HP Scanjet N6010                                                                      | 1        | 2.38%   |
| HP ScanJet G4010                                                                      | 1        | 2.38%   |
| HP Scanjet G2710                                                                      | 1        | 2.38%   |
| HP ScanJet 4850C/4890C                                                                | 1        | 2.38%   |
| HP ScanJet 3970c                                                                      | 1        | 2.38%   |
| HP ScanJet 3400cse                                                                    | 1        | 2.38%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1        | 2.38%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 1        | 2.38%   |
| Canon CanoScan LiDE 70                                                                | 1        | 2.38%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1        | 2.38%   |
| Canon CanoScan LIDE 25                                                                | 1        | 2.38%   |
| Canon CanoScan LiDE 210                                                               | 1        | 2.38%   |
| Canon CanoScan LiDE 200                                                               | 1        | 2.38%   |
| Canon CanoScan 9000F Mark II                                                          | 1        | 2.38%   |
| Canon CanoScan 4200F                                                                  | 1        | 2.38%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 1        | 2.38%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 319      | 35.41%  |
| Microdia                               | 80       | 8.88%   |
| Microsoft                              | 56       | 6.22%   |
| Sunplus Innovation Technology          | 43       | 4.77%   |
| Apple                                  | 32       | 3.55%   |
| Samsung Electronics                    | 30       | 3.33%   |
| Generalplus Technology                 | 28       | 3.11%   |
| ARC International                      | 23       | 2.55%   |
| Z-Star Microelectronics                | 21       | 2.33%   |
| Chicony Electronics                    | 20       | 2.22%   |
| Realtek Semiconductor                  | 19       | 2.11%   |
| webcamvendor                           | 15       | 1.66%   |
| Trust                                  | 10       | 1.11%   |
| Creative Technology                    | 10       | 1.11%   |
| KYE Systems (Mouse Systems)            | 9        | 1%      |
| Jieli Technology                       | 8        | 0.89%   |
| Hewlett-Packard                        | 8        | 0.89%   |
| Cubeternet                             | 8        | 0.89%   |
| Sonix Technology                       | 7        | 0.78%   |
| MacroSilicon                           | 7        | 0.78%   |
| GEMBIRD                                | 7        | 0.78%   |
| Razer USA                              | 6        | 0.67%   |
| WaveRider Communications               | 5        | 0.55%   |
| AVerMedia Technologies                 | 5        | 0.55%   |
| Aveo Technology                        | 5        | 0.55%   |
| Philips (or NXP)                       | 4        | 0.44%   |
| Linux Foundation                       | 4        | 0.44%   |
| Genesys Logic                          | 4        | 0.44%   |
| Asuscom Network                        | 4        | 0.44%   |
| YGTek                                  | 3        | 0.33%   |
| OPPO Electronics                       | 3        | 0.33%   |
| IMC Networks                           | 3        | 0.33%   |
| Huawei Technologies                    | 3        | 0.33%   |
| Guillemot                              | 3        | 0.33%   |
| GenesysLogic Technology                | 3        | 0.33%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.33%   |
| Bison Electronics                      | 3        | 0.33%   |
| Arkmicro Technologies                  | 3        | 0.33%   |
| Alcor Micro                            | 3        | 0.33%   |
| YT-221117-J                            | 2        | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 76       | 8.4%    |
| Logitech HD Pro Webcam C920                       | 46       | 5.08%   |
| Logitech C922 Pro Stream Webcam                   | 32       | 3.54%   |
| Samsung Galaxy series, misc. (MTP mode)           | 29       | 3.2%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                | 29       | 3.2%    |
| ARC International Camera                          | 23       | 2.54%   |
| Microdia Webcam Vitade AF                         | 21       | 2.32%   |
| Generalplus GENERAL WEBCAM                        | 21       | 2.32%   |
| Microdia USB 2.0 Camera                           | 18       | 1.99%   |
| Logitech C920 PRO HD Webcam                       | 18       | 1.99%   |
| Microsoft LifeCam HD-3000                         | 17       | 1.88%   |
| Logitech Webcam C170                              | 15       | 1.66%   |
| Logitech HD Webcam C615                           | 15       | 1.66%   |
| Sunplus FHD Camera Microphone                     | 14       | 1.55%   |
| Logitech BRIO Ultra HD Webcam                     | 13       | 1.44%   |
| webcamvendor webcamproduct                        | 12       | 1.33%   |
| Microdia Sonix USB 2.0 Camera                     | 11       | 1.22%   |
| Microdia Camera                                   | 11       | 1.22%   |
| Sunplus Full HD webcam                            | 10       | 1.1%    |
| Microsoft LifeCam Cinema                          | 10       | 1.1%    |
| Logitech HD Webcam C525                           | 10       | 1.1%    |
| Logitech Webcam C310                              | 9        | 0.99%   |
| Z-Star Venus USB2.0 Camera                        | 8        | 0.88%   |
| Microdia Integrated Camera                        | 8        | 0.88%   |
| Jieli USB PHY 2.0                                 | 8        | 0.88%   |
| Logitech Webcam C930e                             | 7        | 0.77%   |
| Logitech StreamCam                                | 7        | 0.77%   |
| Logitech HD Webcam C910                           | 7        | 0.77%   |
| Generalplus 808 Camera                            | 7        | 0.77%   |
| Chicony HP High Definition 1MP Webcam             | 7        | 0.77%   |
| MacroSilicon USB3. 0 capture                      | 6        | 0.66%   |
| Sunplus HD 720P webcam                            | 5        | 0.55%   |
| Realtek USB Camera                                | 5        | 0.55%   |
| Realtek Full HD webcam                            | 5        | 0.55%   |
| Logitech Webcam C925e                             | 5        | 0.55%   |
| Logitech QuickCam Pro 9000                        | 5        | 0.55%   |
| Logitech QuickCam Communicate MP/S5500            | 5        | 0.55%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 5        | 0.55%   |
| Chicony Integrated Camera                         | 5        | 0.55%   |
| Trust Full HD Webcam                              | 4        | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 2        | 28.57%  |
| Dell                  | 2        | 28.57%  |
| Microsoft             | 1        | 14.29%  |
| Elan Microelectronics | 1        | 14.29%  |
| DigitalPersona        | 1        | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor                  | 2        | 28.57%  |
| Dell MS819 Wired Mouse With Fingerprint Reader | 2        | 28.57%  |
| Microsoft Fingerprint Reader                   | 1        | 14.29%  |
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 14.29%  |
| DigitalPersona Fingerprint Reader              | 1        | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 9        | 23.08%  |
| Realtek Semiconductor     | 5        | 12.82%  |
| Gemalto (was Gemplus)     | 5        | 12.82%  |
| Alcor Micro               | 5        | 12.82%  |
| SCM Microsystems          | 3        | 7.69%   |
| Chicony Electronics       | 3        | 7.69%   |
| Cherry                    | 2        | 5.13%   |
| Bit4id                    | 2        | 5.13%   |
| Reiner SCT Kartensysteme  | 1        | 2.56%   |
| Lenovo                    | 1        | 2.56%   |
| Giesecke & Devrient       | 1        | 2.56%   |
| Fujitsu Siemens Computers | 1        | 2.56%   |
| Aladdin Knowledge Systems | 1        | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 5        | 12.82%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 5        | 12.82%  |
| Advanced Card Systems ACR38 SmartCard Reader                               | 5        | 12.82%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 10.26%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 7.69%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 3        | 7.69%   |
| Advanced Card Systems ACR122U                                              | 2        | 5.13%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.56%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 2.56%   |
| Giesecke & Devrient StarSign CUT S                                         | 1        | 2.56%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.56%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 2.56%   |
| Cherry KC 1000 SC Z                                                        | 1        | 2.56%   |
| Bit4id miniLector-s                                                        | 1        | 2.56%   |
| Bit4id miniLector EVO                                                      | 1        | 2.56%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 2.56%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 2.56%   |
| Advanced Card Systems ACR39U                                               | 1        | 2.56%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 4184     | 82.49%  |
| 1     | 714      | 14.08%  |
| 2     | 90       | 1.77%   |
| 4     | 33       | 0.65%   |
| 3     | 31       | 0.61%   |
| 5     | 11       | 0.22%   |
| 6     | 5        | 0.1%    |
| 8     | 2        | 0.04%   |
| 10    | 1        | 0.02%   |
| 7     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 398      | 35.95%  |
| Net/wireless             | 222      | 20.05%  |
| Unassigned class         | 137      | 12.38%  |
| Communication controller | 101      | 9.12%   |
| Sound                    | 66       | 5.96%   |
| Chipcard                 | 26       | 2.35%   |
| Camera                   | 25       | 2.26%   |
| Multimedia controller    | 24       | 2.17%   |
| Bluetooth                | 22       | 1.99%   |
| Net/ethernet             | 21       | 1.9%    |
| Storage/raid             | 20       | 1.81%   |
| Network                  | 13       | 1.17%   |
| Card reader              | 7        | 0.63%   |
| Fingerprint reader       | 5        | 0.45%   |
| Dvb card                 | 5        | 0.45%   |
| Storage/nvme             | 3        | 0.27%   |
| Storage/ata              | 3        | 0.27%   |
| Modem                    | 3        | 0.27%   |
| Tv card                  | 2        | 0.18%   |
| Firewire controller      | 2        | 0.18%   |
| Wireless                 | 1        | 0.09%   |
| Storage/ide              | 1        | 0.09%   |

