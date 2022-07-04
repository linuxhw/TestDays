Linux in Bulgaria - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

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

Total: 403

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | N68-S                       | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
| ASRock        | 890GM Pro3 R2.0             | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| HP            | ProLiant ML350 G5           | [57a6a7a493](https://linux-hardware.org/?probe=57a6a7a493) | Jun 20, 2022 |
| ASUSTek       | P5KC                        | [489dd3049e](https://linux-hardware.org/?probe=489dd3049e) | Jun 13, 2022 |
| ASUSTek       | P5K Premium                 | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| Pegatron      | 2AC3                        | [a93743e1a0](https://linux-hardware.org/?probe=a93743e1a0) | Jun 11, 2022 |
| HP            | 872D                        | [c27f333c46](https://linux-hardware.org/?probe=c27f333c46) | Jun 08, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a434348da9](https://linux-hardware.org/?probe=a434348da9) | May 26, 2022 |
| Gigabyte      | X99-UD4-CF                  | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| Pegatron      | 2A99h                       | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| Acer          | Predator G3-605             | [fb7a7e74d1](https://linux-hardware.org/?probe=fb7a7e74d1) | May 11, 2022 |
| Gigabyte      | H97N                        | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| Pegatron      | 2AC3                        | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| Intel         | DG35EC AAE29266-205         | [ff7adfb82a](https://linux-hardware.org/?probe=ff7adfb82a) | May 05, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASRock        | B450M Steel Legend          | [c40273d0bc](https://linux-hardware.org/?probe=c40273d0bc) | Apr 29, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ab21675303](https://linux-hardware.org/?probe=ab21675303) | Apr 29, 2022 |
| MSI           | PRO B660-A DDR4             | [ec79dfd8b1](https://linux-hardware.org/?probe=ec79dfd8b1) | Apr 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | [86aeb14193](https://linux-hardware.org/?probe=86aeb14193) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| Gigabyte      | X99-UD4-CF                  | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| ASRock        | H110M-DGS                   | [33d09ef3fd](https://linux-hardware.org/?probe=33d09ef3fd) | Apr 15, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| Gigabyte      | X99-UD4-CF                  | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| ASRock        | B450M Steel Legend          | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [5215972642](https://linux-hardware.org/?probe=5215972642) | Mar 31, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [4153c10d0b](https://linux-hardware.org/?probe=4153c10d0b) | Mar 31, 2022 |
| Gigabyte      | X99-UD4-CF                  | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| Gigabyte      | X99-UD4-CF                  | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [38c8508bc0](https://linux-hardware.org/?probe=38c8508bc0) | Mar 10, 2022 |
| ASRock        | B450M Steel Legend          | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| ASRock        | B450M-HDV R4.0              | [5914978461](https://linux-hardware.org/?probe=5914978461) | Mar 04, 2022 |
| ASRock        | A320M Pro4                  | [43f47c3d8e](https://linux-hardware.org/?probe=43f47c3d8e) | Feb 28, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [fb6d74d159](https://linux-hardware.org/?probe=fb6d74d159) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [dc3262a408](https://linux-hardware.org/?probe=dc3262a408) | Feb 20, 2022 |
| ASUSTek       | P5KC                        | [d12f767e54](https://linux-hardware.org/?probe=d12f767e54) | Feb 19, 2022 |
| Lenovo        | ThinkCentre M58p 6234A1G    | [1cbf260df6](https://linux-hardware.org/?probe=1cbf260df6) | Feb 18, 2022 |
| ASUSTek       | P5KC                        | [61c7fe5dfd](https://linux-hardware.org/?probe=61c7fe5dfd) | Feb 18, 2022 |
| ASUSTek       | A68HM-K                     | [2024310fec](https://linux-hardware.org/?probe=2024310fec) | Feb 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [afe18260fc](https://linux-hardware.org/?probe=afe18260fc) | Feb 17, 2022 |
| ASRock        | 960GM-GS3 FX                | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V                    | [d00c78fd08](https://linux-hardware.org/?probe=d00c78fd08) | Feb 08, 2022 |
| ASUSTek       | P8H77-V                     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| ASRock        | FM2A58M-DG3+                | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Intel         | X99                         | [f4a0c1aaaa](https://linux-hardware.org/?probe=f4a0c1aaaa) | Jan 20, 2022 |
| ASUSTek       | PRIME Z270-P                | [821f3261c2](https://linux-hardware.org/?probe=821f3261c2) | Jan 18, 2022 |
| ASRock        | H110M-DGS                   | [d027268e2b](https://linux-hardware.org/?probe=d027268e2b) | Jan 14, 2022 |
| ASUSTek       | PRIME Z270-P                | [a9ed1157c0](https://linux-hardware.org/?probe=a9ed1157c0) | Jan 13, 2022 |
| ASUSTek       | PRIME Z270-P                | [f23503b603](https://linux-hardware.org/?probe=f23503b603) | Jan 10, 2022 |
| Gigabyte      | G41M-ES2L                   | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| Gigabyte      | X570 GAMING X               | [7add8fadfa](https://linux-hardware.org/?probe=7add8fadfa) | Jan 04, 2022 |
| Gigabyte      | X570 GAMING X               | [e8cfb51ca5](https://linux-hardware.org/?probe=e8cfb51ca5) | Jan 04, 2022 |
| HP            | 3397                        | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| Gigabyte      | X570 GAMING X               | [50045a522a](https://linux-hardware.org/?probe=50045a522a) | Dec 30, 2021 |
| ASUSTek       | P5E                         | [1d3ece3005](https://linux-hardware.org/?probe=1d3ece3005) | Dec 29, 2021 |
| Gigabyte      | X570 GAMING X               | [19959c7845](https://linux-hardware.org/?probe=19959c7845) | Dec 26, 2021 |
| ASRock        | B450M Steel Legend          | [b8ff289917](https://linux-hardware.org/?probe=b8ff289917) | Dec 22, 2021 |
| Dell          | 0427JK A00                  | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [65ec484cf7](https://linux-hardware.org/?probe=65ec484cf7) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [ab70f6516f](https://linux-hardware.org/?probe=ab70f6516f) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| Dell          | 0427JK A00                  | [785650303f](https://linux-hardware.org/?probe=785650303f) | Dec 13, 2021 |
| Gigabyte      | Z490 AORUS PRO AX           | [03ba9fdf17](https://linux-hardware.org/?probe=03ba9fdf17) | Dec 11, 2021 |
| ASRock        | B450M Steel Legend          | [a5c3366e73](https://linux-hardware.org/?probe=a5c3366e73) | Dec 10, 2021 |
| ASRock        | B450M Steel Legend          | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [7530a42730](https://linux-hardware.org/?probe=7530a42730) | Dec 03, 2021 |
| ASUSTek       | PRIME Z590-P                | [f0c1e81fb5](https://linux-hardware.org/?probe=f0c1e81fb5) | Nov 25, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [bd12b5a969](https://linux-hardware.org/?probe=bd12b5a969) | Nov 21, 2021 |
| ASUSTek       | M51BC                       | [dfc2c68c8d](https://linux-hardware.org/?probe=dfc2c68c8d) | Nov 19, 2021 |
| Acer          | Predator G3-605             | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| ASRock        | B450M Steel Legend          | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| ASUSTek       | PRIME X570-P                | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| ASRock        | B450M Steel Legend          | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8cae94b7f8](https://linux-hardware.org/?probe=8cae94b7f8) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| ASUSTek       | PRIME B350M-A               | [3ab004eed4](https://linux-hardware.org/?probe=3ab004eed4) | Oct 17, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| ASRock        | H81M-HDS                    | [300c7e725d](https://linux-hardware.org/?probe=300c7e725d) | Oct 10, 2021 |
| Gigabyte      | H310M S2P                   | [637dbbacba](https://linux-hardware.org/?probe=637dbbacba) | Oct 08, 2021 |
| ASUSTek       | PRIME X370-PRO              | [1121eb673b](https://linux-hardware.org/?probe=1121eb673b) | Sep 27, 2021 |
| ASRock        | FM2A58M-HD+                 | [3be61fa185](https://linux-hardware.org/?probe=3be61fa185) | Sep 11, 2021 |
| Lenovo        | ThinkStation D20 4158E93    | [fde770f309](https://linux-hardware.org/?probe=fde770f309) | Sep 11, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [a95e304baf](https://linux-hardware.org/?probe=a95e304baf) | Sep 07, 2021 |
| Unknown       | Unknown                     | [a37b749b27](https://linux-hardware.org/?probe=a37b749b27) | Sep 06, 2021 |
| Unknown       | Unknown                     | [92e21fb915](https://linux-hardware.org/?probe=92e21fb915) | Sep 06, 2021 |
| ASRock        | X570 Pro4                   | [7c76ac10d8](https://linux-hardware.org/?probe=7c76ac10d8) | Sep 04, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [7d634f76ad](https://linux-hardware.org/?probe=7d634f76ad) | Aug 31, 2021 |
| ASRock        | FM2A58M-HD+                 | [9eb666fd13](https://linux-hardware.org/?probe=9eb666fd13) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | [8a976ca31c](https://linux-hardware.org/?probe=8a976ca31c) | Aug 29, 2021 |
| HP            | 18E4                        | [81c51891c9](https://linux-hardware.org/?probe=81c51891c9) | Aug 27, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [257e2c9dd4](https://linux-hardware.org/?probe=257e2c9dd4) | Aug 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [59f5bb4379](https://linux-hardware.org/?probe=59f5bb4379) | Aug 18, 2021 |
| ASRock        | FM2A68M-DG3+                | [3bfb2e6910](https://linux-hardware.org/?probe=3bfb2e6910) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Gigabyte      | GA-870A-USB3                | [f7de5020c6](https://linux-hardware.org/?probe=f7de5020c6) | Aug 16, 2021 |
| MSI           | A68HM-P33 V2                | [4c3bedddac](https://linux-hardware.org/?probe=4c3bedddac) | Aug 14, 2021 |
| Gigabyte      | GA-870A-USB3                | [bb46750dfa](https://linux-hardware.org/?probe=bb46750dfa) | Aug 12, 2021 |
| ASUSTek       | P5KC                        | [4fce5e2d88](https://linux-hardware.org/?probe=4fce5e2d88) | Aug 09, 2021 |
| ASUSTek       | M4A78 PRO                   | [ef7f570d01](https://linux-hardware.org/?probe=ef7f570d01) | Aug 04, 2021 |
| ASRock        | H110 Pro BTC+               | [0c191944fc](https://linux-hardware.org/?probe=0c191944fc) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | [a08f9bd38d](https://linux-hardware.org/?probe=a08f9bd38d) | Aug 02, 2021 |
| MSI           | MEG X570 UNIFY              | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| ASUSTek       | PRIME Z370-A                | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| Gigabyte      | GA-870A-USB3                | [b39264f1fa](https://linux-hardware.org/?probe=b39264f1fa) | Jul 22, 2021 |
| ASRock        | AB350 Pro4                  | [5d62f330ba](https://linux-hardware.org/?probe=5d62f330ba) | Jul 18, 2021 |
| ASUSTek       | TUF X299 MARK 2             | [d3f2c6d8d8](https://linux-hardware.org/?probe=d3f2c6d8d8) | Jul 13, 2021 |
| ASUSTek       | P5QD TURBO                  | [5ce964530d](https://linux-hardware.org/?probe=5ce964530d) | Jul 13, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [13af782a58](https://linux-hardware.org/?probe=13af782a58) | Jun 29, 2021 |
| Gigabyte      | GA-870A-USB3                | [d791d77acc](https://linux-hardware.org/?probe=d791d77acc) | Jun 28, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [e56a7ee3c9](https://linux-hardware.org/?probe=e56a7ee3c9) | Jun 27, 2021 |
| HP            | 1493                        | [cd54c7db25](https://linux-hardware.org/?probe=cd54c7db25) | Jun 26, 2021 |
| HP            | 1493                        | [5b7dd91534](https://linux-hardware.org/?probe=5b7dd91534) | Jun 26, 2021 |
| Gigabyte      | GA-M56S-S3                  | [e7e3e4138d](https://linux-hardware.org/?probe=e7e3e4138d) | Jun 20, 2021 |
| Gigabyte      | GA-M56S-S3                  | [c4f55611e4](https://linux-hardware.org/?probe=c4f55611e4) | Jun 20, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [f200ec0bda](https://linux-hardware.org/?probe=f200ec0bda) | Jun 08, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [9a2b696908](https://linux-hardware.org/?probe=9a2b696908) | Jun 05, 2021 |
| Gigabyte      | Z490 AORUS ELITE AC         | [6bc1b9dcc9](https://linux-hardware.org/?probe=6bc1b9dcc9) | May 31, 2021 |
| Dell          | 0K240Y A02                  | [c050f79e2b](https://linux-hardware.org/?probe=c050f79e2b) | May 29, 2021 |
| Dell          | 0K240Y A02                  | [7f510d13fb](https://linux-hardware.org/?probe=7f510d13fb) | May 28, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [60450a65b2](https://linux-hardware.org/?probe=60450a65b2) | May 20, 2021 |
| ASRock        | Z97 Anniversary             | [493f6f8057](https://linux-hardware.org/?probe=493f6f8057) | May 18, 2021 |
| ASUSTek       | P5P43TD PRO                 | [4d5f23e6ba](https://linux-hardware.org/?probe=4d5f23e6ba) | May 17, 2021 |
| ASRock        | Z97 Anniversary             | [14ea7483bc](https://linux-hardware.org/?probe=14ea7483bc) | May 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [22657f3929](https://linux-hardware.org/?probe=22657f3929) | May 15, 2021 |
| HP            | 3396                        | [ed3fa57f54](https://linux-hardware.org/?probe=ed3fa57f54) | May 15, 2021 |
| ASUSTek       | B150M-A                     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [cf41b106cb](https://linux-hardware.org/?probe=cf41b106cb) | May 11, 2021 |
| Gigabyte      | A320MA-M.2-CF               | [511e08ef09](https://linux-hardware.org/?probe=511e08ef09) | May 09, 2021 |
| Unknown       | Unknown                     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| ASUSTek       | P5KC                        | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASRock        | X570 Pro4                   | [3ad2c89a0a](https://linux-hardware.org/?probe=3ad2c89a0a) | May 03, 2021 |
| ASUSTek       | P5KC                        | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| ASRock        | X79 Extreme4                | [d3383d57ef](https://linux-hardware.org/?probe=d3383d57ef) | May 01, 2021 |
| ASUSTek       | Amberine M                  | [9eeaeb53fc](https://linux-hardware.org/?probe=9eeaeb53fc) | Apr 26, 2021 |
| ASRock        | B360M Pro4                  | [b1f9a4880e](https://linux-hardware.org/?probe=b1f9a4880e) | Apr 22, 2021 |
| ASUSTek       | P8P67 DELUXE                | [8c83051b44](https://linux-hardware.org/?probe=8c83051b44) | Apr 12, 2021 |
| ASRock        | Z68 Extreme7 Gen3           | [d8e2ac9e9b](https://linux-hardware.org/?probe=d8e2ac9e9b) | Apr 11, 2021 |
| ASUSTek       | PRIME X370-PRO              | [891b52b28e](https://linux-hardware.org/?probe=891b52b28e) | Apr 08, 2021 |
| ASUSTek       | P5KC                        | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| ASRock        | A320M-HDV R4.0              | [658ec2843e](https://linux-hardware.org/?probe=658ec2843e) | Apr 03, 2021 |
| HP            | 1850                        | [517c6137a3](https://linux-hardware.org/?probe=517c6137a3) | Apr 01, 2021 |
| ASRock        | B550M Pro4                  | [333c645cc4](https://linux-hardware.org/?probe=333c645cc4) | Apr 01, 2021 |
| ASRock        | AB350M Pro4                 | [bd779f8e4e](https://linux-hardware.org/?probe=bd779f8e4e) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | [072483c895](https://linux-hardware.org/?probe=072483c895) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | [11e59c84c6](https://linux-hardware.org/?probe=11e59c84c6) | Mar 26, 2021 |
| Seco          | C40 C                       | [70a92f2d8a](https://linux-hardware.org/?probe=70a92f2d8a) | Mar 19, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [e5f799a9f1](https://linux-hardware.org/?probe=e5f799a9f1) | Mar 19, 2021 |
| ASRock        | B450M-HDV R4.0              | [d2d43a5a92](https://linux-hardware.org/?probe=d2d43a5a92) | Mar 17, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [ef2bfba994](https://linux-hardware.org/?probe=ef2bfba994) | Mar 17, 2021 |
| ECS           | MCP61M-M3                   | [39fb7fbfdd](https://linux-hardware.org/?probe=39fb7fbfdd) | Mar 17, 2021 |
| ASRock        | B450M-HDV R4.0              | [30047ff89f](https://linux-hardware.org/?probe=30047ff89f) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| ASUSTek       | PRIME X570-P                | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| Dell          | 0T10XW A02                  | [3fc42af6ee](https://linux-hardware.org/?probe=3fc42af6ee) | Mar 13, 2021 |
| Dell          | 0T10XW A02                  | [3403829400](https://linux-hardware.org/?probe=3403829400) | Mar 13, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [e2bd9d6df8](https://linux-hardware.org/?probe=e2bd9d6df8) | Mar 11, 2021 |
| Lenovo        | MAHOBAY NOK                 | [5ff3194762](https://linux-hardware.org/?probe=5ff3194762) | Mar 10, 2021 |
| ASRock        | AB350 Pro4                  | [a76ade188b](https://linux-hardware.org/?probe=a76ade188b) | Mar 07, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [b3a1ae5051](https://linux-hardware.org/?probe=b3a1ae5051) | Mar 06, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [f14a8d2de0](https://linux-hardware.org/?probe=f14a8d2de0) | Mar 05, 2021 |
| ASUSTek       | M2N68-AM Plus               | [18268633d9](https://linux-hardware.org/?probe=18268633d9) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | [c4e5bc819d](https://linux-hardware.org/?probe=c4e5bc819d) | Mar 02, 2021 |
| Intel         | X99 V102                    | [e4884fdd22](https://linux-hardware.org/?probe=e4884fdd22) | Feb 25, 2021 |
| HP            | 3396                        | [dd8601c672](https://linux-hardware.org/?probe=dd8601c672) | Feb 24, 2021 |
| HP            | 3396                        | [5c5fde40cd](https://linux-hardware.org/?probe=5c5fde40cd) | Feb 24, 2021 |
| ASUSTek       | PRIME X570-P                | [53d26490a1](https://linux-hardware.org/?probe=53d26490a1) | Feb 23, 2021 |
| HP            | 1494                        | [c369d28059](https://linux-hardware.org/?probe=c369d28059) | Feb 23, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [5ad971da58](https://linux-hardware.org/?probe=5ad971da58) | Feb 23, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | [698bd7ab9c](https://linux-hardware.org/?probe=698bd7ab9c) | Feb 22, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | [e5ae830bbf](https://linux-hardware.org/?probe=e5ae830bbf) | Feb 21, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [b9b1df7b2d](https://linux-hardware.org/?probe=b9b1df7b2d) | Feb 21, 2021 |
| Dell          | 0DFRFW A01                  | [71a10bba93](https://linux-hardware.org/?probe=71a10bba93) | Feb 16, 2021 |
| MSI           | MS-7250                     | [e1f266f412](https://linux-hardware.org/?probe=e1f266f412) | Feb 15, 2021 |
| MSI           | H61M-P31                    | [256f5dc934](https://linux-hardware.org/?probe=256f5dc934) | Feb 14, 2021 |
| ASUSTek       | A8N-E                       | [a35eff4bb9](https://linux-hardware.org/?probe=a35eff4bb9) | Feb 14, 2021 |
| iEi           | B202 V1.0                   | [3dce687709](https://linux-hardware.org/?probe=3dce687709) | Feb 14, 2021 |
| Gigabyte      | H81M-HD3                    | [b6b357f26c](https://linux-hardware.org/?probe=b6b357f26c) | Feb 14, 2021 |
| ASRock        | 890GX Extreme3              | [1168daa7de](https://linux-hardware.org/?probe=1168daa7de) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | [dc1822ee72](https://linux-hardware.org/?probe=dc1822ee72) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | [8fedc4a9c1](https://linux-hardware.org/?probe=8fedc4a9c1) | Feb 12, 2021 |
| Lenovo        | MAHOBAY NOK                 | [2d6363ed19](https://linux-hardware.org/?probe=2d6363ed19) | Feb 10, 2021 |
| ASRock        | X570 Taichi                 | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| ASRock        | FM2A85X Extreme4            | [2f1725cb23](https://linux-hardware.org/?probe=2f1725cb23) | Jan 30, 2021 |
| ASUSTek       | PRIME X570-P                | [d566b4292e](https://linux-hardware.org/?probe=d566b4292e) | Jan 30, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [5e824ae0f4](https://linux-hardware.org/?probe=5e824ae0f4) | Jan 29, 2021 |
| ASRock        | H87M Pro4                   | [88e1834599](https://linux-hardware.org/?probe=88e1834599) | Jan 24, 2021 |
| ASUSTek       | M5A78L-M LX                 | [194dbb8e46](https://linux-hardware.org/?probe=194dbb8e46) | Jan 24, 2021 |
| Gigabyte      | M68M-S2P                    | [bdee5c1907](https://linux-hardware.org/?probe=bdee5c1907) | Jan 23, 2021 |
| ASRock        | H110M-HDV                   | [6eecfdfd4b](https://linux-hardware.org/?probe=6eecfdfd4b) | Jan 21, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [e10b7bc8cf](https://linux-hardware.org/?probe=e10b7bc8cf) | Jan 21, 2021 |
| MiTAC         | E220 6A7                    | [0d75e5ba34](https://linux-hardware.org/?probe=0d75e5ba34) | Jan 14, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [20416ee115](https://linux-hardware.org/?probe=20416ee115) | Jan 10, 2021 |
| Dell          | 0K240Y A02                  | [1c948eea28](https://linux-hardware.org/?probe=1c948eea28) | Jan 05, 2021 |
| ASRock        | 960GM-GS3 FX                | [13e7f80b8f](https://linux-hardware.org/?probe=13e7f80b8f) | Jan 03, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [5232dd577c](https://linux-hardware.org/?probe=5232dd577c) | Jan 03, 2021 |
| ASUSTek       | P8H77-V                     | [50edfe4e5e](https://linux-hardware.org/?probe=50edfe4e5e) | Jan 01, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [05fcb61de6](https://linux-hardware.org/?probe=05fcb61de6) | Dec 29, 2020 |
| ASUSTek       | P5G41T-M LX                 | [06f63c2119](https://linux-hardware.org/?probe=06f63c2119) | Dec 24, 2020 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [fed52f343a](https://linux-hardware.org/?probe=fed52f343a) | Dec 24, 2020 |
| MiTAC         | E220 6A7                    | [e051bc126d](https://linux-hardware.org/?probe=e051bc126d) | Dec 23, 2020 |
| Dell          | 0K240Y A02                  | [d522c503da](https://linux-hardware.org/?probe=d522c503da) | Dec 21, 2020 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [ad3ac7bcee](https://linux-hardware.org/?probe=ad3ac7bcee) | Dec 19, 2020 |
| Unknown       | GSUO H61                    | [3c4c6c8bd0](https://linux-hardware.org/?probe=3c4c6c8bd0) | Dec 14, 2020 |
| Gigabyte      | EP45-DS3L                   | [d0388f0066](https://linux-hardware.org/?probe=d0388f0066) | Dec 12, 2020 |
| Gigabyte      | EQ45M-S2                    | [2c39a254ee](https://linux-hardware.org/?probe=2c39a254ee) | Dec 11, 2020 |
| ASUSTek       | PRIME X570-PRO              | [6502e1050d](https://linux-hardware.org/?probe=6502e1050d) | Dec 05, 2020 |
| ASRock        | 960GM-GS3 FX                | [b7e98a5926](https://linux-hardware.org/?probe=b7e98a5926) | Dec 04, 2020 |
| ASRock        | FM2A75 Pro4+                | [d12dc95e76](https://linux-hardware.org/?probe=d12dc95e76) | Dec 03, 2020 |
| ASRock        | FM2A75 Pro4+                | [02c7320eaf](https://linux-hardware.org/?probe=02c7320eaf) | Dec 03, 2020 |
| ASRock        | G41M-S3                     | [1f91a14ff2](https://linux-hardware.org/?probe=1f91a14ff2) | Dec 03, 2020 |
| ASRock        | X370 Gaming K4              | [7b8b964ce4](https://linux-hardware.org/?probe=7b8b964ce4) | Nov 29, 2020 |
| Dell          | 0K240Y A02                  | [6f8d2322b6](https://linux-hardware.org/?probe=6f8d2322b6) | Nov 25, 2020 |
| ASUSTek       | H110M-PLUS                  | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| Lenovo        | MAHOBAY                     | [7698cbedd0](https://linux-hardware.org/?probe=7698cbedd0) | Nov 12, 2020 |
| Gigabyte      | B450 AORUS M                | [c1df930d7e](https://linux-hardware.org/?probe=c1df930d7e) | Nov 10, 2020 |
| iEi           | B202 V1.0                   | [ad705b0098](https://linux-hardware.org/?probe=ad705b0098) | Oct 29, 2020 |
| Packard Be... | IMEDIA S2185                | [5fd02031d2](https://linux-hardware.org/?probe=5fd02031d2) | Oct 21, 2020 |
| Dell          | 0XHGV1 A00                  | [d1f3fe93be](https://linux-hardware.org/?probe=d1f3fe93be) | Oct 16, 2020 |
| ASUSTek       | P5GC-MX/1333                | [bfe71baced](https://linux-hardware.org/?probe=bfe71baced) | Oct 14, 2020 |
| Gigabyte      | PH67A-D3-B3                 | [61b3d8f426](https://linux-hardware.org/?probe=61b3d8f426) | Oct 09, 2020 |
| ASRock        | AB350M Pro4                 | [b178beac46](https://linux-hardware.org/?probe=b178beac46) | Oct 07, 2020 |
| ASUSTek       | P10S-V Series               | [ab381f976a](https://linux-hardware.org/?probe=ab381f976a) | Oct 04, 2020 |
| Gigabyte      | P35-S3G                     | [c55cb88668](https://linux-hardware.org/?probe=c55cb88668) | Sep 30, 2020 |
| Acer          | EG43M                       | [f70bf9f37f](https://linux-hardware.org/?probe=f70bf9f37f) | Sep 26, 2020 |
| Acer          | EG43M                       | [93fe9368c0](https://linux-hardware.org/?probe=93fe9368c0) | Sep 26, 2020 |
| ASUSTek       | Berkeley                    | [db3c1d0348](https://linux-hardware.org/?probe=db3c1d0348) | Sep 13, 2020 |
| ASUSTek       | TUF Z370-PRO GAMING         | [fd2b790572](https://linux-hardware.org/?probe=fd2b790572) | Sep 09, 2020 |
| Shuttle       | FH81                        | [f7d3c868f1](https://linux-hardware.org/?probe=f7d3c868f1) | Sep 07, 2020 |
| Gigabyte      | H97-Gaming 3                | [bc5ee009b9](https://linux-hardware.org/?probe=bc5ee009b9) | Aug 29, 2020 |
| HP            | 0AA4h                       | [e1d187b146](https://linux-hardware.org/?probe=e1d187b146) | Aug 24, 2020 |
| Gigabyte      | H97-Gaming 3                | [b636cd4fc2](https://linux-hardware.org/?probe=b636cd4fc2) | Aug 10, 2020 |
| Lenovo        | ThinkCentre M90p 5864BQ9    | [2f13897020](https://linux-hardware.org/?probe=2f13897020) | Aug 06, 2020 |
| HP            | 1632                        | [051549bbcd](https://linux-hardware.org/?probe=051549bbcd) | Aug 03, 2020 |
| HP            | 1496                        | [814a9396ee](https://linux-hardware.org/?probe=814a9396ee) | Aug 01, 2020 |
| ASUSTek       | A8N-VM CSM                  | [d6af935ba5](https://linux-hardware.org/?probe=d6af935ba5) | Jul 30, 2020 |
| ASUSTek       | X99-PRO                     | [ec4e8d2f6b](https://linux-hardware.org/?probe=ec4e8d2f6b) | Jul 30, 2020 |
| ASRock        | ConRoe945PL-GLAN            | [006d3a68b4](https://linux-hardware.org/?probe=006d3a68b4) | Jul 30, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| Gigabyte      | 990XA-UD3                   | [974c9ebd9c](https://linux-hardware.org/?probe=974c9ebd9c) | Jul 26, 2020 |
| Foxconn       | 2A8C                        | [511636781f](https://linux-hardware.org/?probe=511636781f) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | [2afa9387d5](https://linux-hardware.org/?probe=2afa9387d5) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | [8ced06cd1f](https://linux-hardware.org/?probe=8ced06cd1f) | Jul 25, 2020 |
| ASUSTek       | P5B-Deluxe                  | [7b8022aa05](https://linux-hardware.org/?probe=7b8022aa05) | Jul 23, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | [f25b0e7108](https://linux-hardware.org/?probe=f25b0e7108) | Jul 19, 2020 |
| Foxconn       | 2A8C                        | [1de3848a94](https://linux-hardware.org/?probe=1de3848a94) | Jul 19, 2020 |
| Gigabyte      | H97-Gaming 3                | [2298274454](https://linux-hardware.org/?probe=2298274454) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | [2f5df8729a](https://linux-hardware.org/?probe=2f5df8729a) | Jul 17, 2020 |
| MSI           | B350 TOMAHAWK               | [7387ae682a](https://linux-hardware.org/?probe=7387ae682a) | Jul 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | [46702d58d5](https://linux-hardware.org/?probe=46702d58d5) | Jul 04, 2020 |
| MSI           | B150 GAMING M3              | [4e837b8686](https://linux-hardware.org/?probe=4e837b8686) | Jul 01, 2020 |
| Intel         | DX58SO2 AAG10925-205        | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| ASUSTek       | P8H61-I LX R2.0/RM/SI       | [a5f5e5572b](https://linux-hardware.org/?probe=a5f5e5572b) | Jun 30, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [078efbe676](https://linux-hardware.org/?probe=078efbe676) | Jun 29, 2020 |
| ASRock        | 960GM-GS3 FX                | [a79843ff43](https://linux-hardware.org/?probe=a79843ff43) | Jun 27, 2020 |
| Gigabyte      | B450 AORUS M                | [5d93931a70](https://linux-hardware.org/?probe=5d93931a70) | Jun 21, 2020 |
| Gigabyte      | B450 AORUS M                | [6d318a0db0](https://linux-hardware.org/?probe=6d318a0db0) | Jun 21, 2020 |
| Gigabyte      | X99-UD4-CF                  | [f2f35bedba](https://linux-hardware.org/?probe=f2f35bedba) | Jun 20, 2020 |
| Gigabyte      | X99-UD4-CF                  | [22ca9e31e5](https://linux-hardware.org/?probe=22ca9e31e5) | Jun 15, 2020 |
| ASRock        | H110M-HDV                   | [9a04c60269](https://linux-hardware.org/?probe=9a04c60269) | Jun 15, 2020 |
| ASUSTek       | X99-PRO                     | [1b58de62cc](https://linux-hardware.org/?probe=1b58de62cc) | Jun 14, 2020 |
| ASUSTek       | X99-PRO                     | [5a279c96a5](https://linux-hardware.org/?probe=5a279c96a5) | Jun 13, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1e9b7bd7d0](https://linux-hardware.org/?probe=1e9b7bd7d0) | Jun 09, 2020 |
| ASRock        | 970M Pro3                   | [f40c51e426](https://linux-hardware.org/?probe=f40c51e426) | Jun 03, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [efa59eef1c](https://linux-hardware.org/?probe=efa59eef1c) | Jun 01, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | [9c341d7259](https://linux-hardware.org/?probe=9c341d7259) | May 25, 2020 |
| Intel         | DG35EC AAE29266-205         | [5bd26cbc33](https://linux-hardware.org/?probe=5bd26cbc33) | May 24, 2020 |
| ASUSTek       | M2N-MX SE Plus              | [34d65fc5b5](https://linux-hardware.org/?probe=34d65fc5b5) | May 22, 2020 |
| HP            | 1496                        | [64b345823f](https://linux-hardware.org/?probe=64b345823f) | May 18, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | [5d67f4aace](https://linux-hardware.org/?probe=5d67f4aace) | May 16, 2020 |
| Gigabyte      | H97-Gaming 3                | [d4a5246eaa](https://linux-hardware.org/?probe=d4a5246eaa) | May 12, 2020 |
| MSI           | MS-7368                     | [090e6cd15c](https://linux-hardware.org/?probe=090e6cd15c) | May 01, 2020 |
| MSI           | MS-7368                     | [308c2e01f6](https://linux-hardware.org/?probe=308c2e01f6) | Apr 30, 2020 |
| ASUSTek       | M2N68-CM                    | [6f787e35a1](https://linux-hardware.org/?probe=6f787e35a1) | Apr 27, 2020 |
| ASUSTek       | P5KPL-AM                    | [7dceeca2dd](https://linux-hardware.org/?probe=7dceeca2dd) | Apr 24, 2020 |
| Gigabyte      | P85-D3                      | [5972095107](https://linux-hardware.org/?probe=5972095107) | Apr 21, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | [00cedd86e4](https://linux-hardware.org/?probe=00cedd86e4) | Apr 19, 2020 |
| Dell          | 08NPPY A00                  | [895a4ce7cb](https://linux-hardware.org/?probe=895a4ce7cb) | Apr 15, 2020 |
| Shuttle       | FH81                        | [61209bcee3](https://linux-hardware.org/?probe=61209bcee3) | Apr 11, 2020 |
| ASRock        | 890GX Extreme3              | [2f70e1ae2c](https://linux-hardware.org/?probe=2f70e1ae2c) | Apr 10, 2020 |
| ASRock        | 970 Extreme3                | [679cdbade2](https://linux-hardware.org/?probe=679cdbade2) | Apr 05, 2020 |
| HP            | 0A64h                       | [79aa6d6301](https://linux-hardware.org/?probe=79aa6d6301) | Apr 05, 2020 |
| ASUSTek       | P5K                         | [60860911b6](https://linux-hardware.org/?probe=60860911b6) | Apr 03, 2020 |
| ASRock        | X470 Taichi Ultimate        | [a7f7938a12](https://linux-hardware.org/?probe=a7f7938a12) | Apr 02, 2020 |
| ASUSTek       | P5KPL-AM                    | [4db785101b](https://linux-hardware.org/?probe=4db785101b) | Apr 01, 2020 |
| Dell          | 0DR845                      | [c1582b3202](https://linux-hardware.org/?probe=c1582b3202) | Apr 01, 2020 |
| ASUSTek       | P5K SE                      | [8492263fc0](https://linux-hardware.org/?probe=8492263fc0) | Mar 29, 2020 |
| ASUSTek       | P5K SE                      | [fd766dda01](https://linux-hardware.org/?probe=fd766dda01) | Mar 26, 2020 |
| ASRock        | G41M-S3                     | [19c0625a28](https://linux-hardware.org/?probe=19c0625a28) | Mar 24, 2020 |
| ASUSTek       | M4A3000E                    | [76ec7cf71b](https://linux-hardware.org/?probe=76ec7cf71b) | Mar 23, 2020 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [0d2e81fb9b](https://linux-hardware.org/?probe=0d2e81fb9b) | Mar 20, 2020 |
| ASUSTek       | P5K                         | [64c435a307](https://linux-hardware.org/?probe=64c435a307) | Mar 17, 2020 |
| ASUSTek       | P5K                         | [d532983f25](https://linux-hardware.org/?probe=d532983f25) | Mar 17, 2020 |
| ASRock        | X470 Taichi Ultimate        | [53d0f3f5fc](https://linux-hardware.org/?probe=53d0f3f5fc) | Mar 13, 2020 |
| Unknown       | K8NF6G-VSTA                 | [b4f0d62c45](https://linux-hardware.org/?probe=b4f0d62c45) | Mar 08, 2020 |
| Unknown       | K8NF6G-VSTA                 | [08691dfde3](https://linux-hardware.org/?probe=08691dfde3) | Mar 08, 2020 |
| ASRock        | 890FX Deluxe4               | [391c431de9](https://linux-hardware.org/?probe=391c431de9) | Mar 05, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | [5b7e72604e](https://linux-hardware.org/?probe=5b7e72604e) | Mar 04, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | [4c1a03683b](https://linux-hardware.org/?probe=4c1a03683b) | Mar 01, 2020 |
| Intel         | DQ57TM AAE92694-402         | [e82b578dad](https://linux-hardware.org/?probe=e82b578dad) | Feb 28, 2020 |
| ASRock        | H81M-ITX/WiFi               | [a513552c14](https://linux-hardware.org/?probe=a513552c14) | Feb 27, 2020 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | [455dbd81e1](https://linux-hardware.org/?probe=455dbd81e1) | Feb 22, 2020 |
| ASUSTek       | P8H61-M LX                  | [b09f7bb137](https://linux-hardware.org/?probe=b09f7bb137) | Feb 22, 2020 |
| ASUSTek       | H81M-PLUS                   | [8231b2fe22](https://linux-hardware.org/?probe=8231b2fe22) | Feb 18, 2020 |
| ASUSTek       | A88XM-E                     | [ea21444fa7](https://linux-hardware.org/?probe=ea21444fa7) | Feb 11, 2020 |
| ASUSTek       | A88XM-E                     | [984a9c83fd](https://linux-hardware.org/?probe=984a9c83fd) | Feb 10, 2020 |
| HP            | 0A64h                       | [23d32db8b9](https://linux-hardware.org/?probe=23d32db8b9) | Feb 10, 2020 |
| HP            | 0A64h                       | [eed7c64698](https://linux-hardware.org/?probe=eed7c64698) | Feb 06, 2020 |
| ASUSTek       | M2N68-CM                    | [201ca7dd72](https://linux-hardware.org/?probe=201ca7dd72) | Jan 28, 2020 |
| ASRock        | AB350M Pro4 R2.0            | [11e945005f](https://linux-hardware.org/?probe=11e945005f) | Jan 08, 2020 |
| ASUSTek       | H81M-PLUS                   | [6056ef2c40](https://linux-hardware.org/?probe=6056ef2c40) | Jan 07, 2020 |
| ASUSTek       | H110M-PLUS                  | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| ASUSTek       | V-P8H67E                    | [274eea3275](https://linux-hardware.org/?probe=274eea3275) | Dec 20, 2019 |
| Foxconn       | A55MX                       | [05c6b7995d](https://linux-hardware.org/?probe=05c6b7995d) | Dec 19, 2019 |
| Lenovo        | ThinkCentre M91p 7033W9N    | [3eb7eb388c](https://linux-hardware.org/?probe=3eb7eb388c) | Dec 17, 2019 |
| Lenovo        | ThinkCentre M91p 7033W9N    | [aaa8d34fff](https://linux-hardware.org/?probe=aaa8d34fff) | Dec 17, 2019 |
| ASUSTek       | H81M-PLUS                   | [6e09a0e0aa](https://linux-hardware.org/?probe=6e09a0e0aa) | Dec 16, 2019 |
| ASUSTek       | V-P8H67E                    | [030c06dbf0](https://linux-hardware.org/?probe=030c06dbf0) | Dec 15, 2019 |
| ASUSTek       | V-P8H67E                    | [893a9b3000](https://linux-hardware.org/?probe=893a9b3000) | Dec 14, 2019 |
| Intel         | DG35EC AAE29266-205         | [0a74735da6](https://linux-hardware.org/?probe=0a74735da6) | Dec 12, 2019 |
| HP            | 1850                        | [898f2b7197](https://linux-hardware.org/?probe=898f2b7197) | Dec 01, 2019 |
| ASRock        | B85M Pro4                   | [c6b09d560f](https://linux-hardware.org/?probe=c6b09d560f) | Nov 30, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [ade7b4eb87](https://linux-hardware.org/?probe=ade7b4eb87) | Nov 29, 2019 |
| ASUSTek       | H97-PLUS                    | [5b9bb1aedb](https://linux-hardware.org/?probe=5b9bb1aedb) | Nov 28, 2019 |
| ASUSTek       | H97-PLUS                    | [115ab4a8a7](https://linux-hardware.org/?probe=115ab4a8a7) | Nov 28, 2019 |
| ASRock        | H61M-GS                     | [b0cff72d0c](https://linux-hardware.org/?probe=b0cff72d0c) | Nov 24, 2019 |
| iEi           | B202 V1.0                   | [16699afe19](https://linux-hardware.org/?probe=16699afe19) | Nov 13, 2019 |
| ASRock        | H61M-VG3                    | [6bc9ab22bf](https://linux-hardware.org/?probe=6bc9ab22bf) | Nov 11, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [a2fe589062](https://linux-hardware.org/?probe=a2fe589062) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [2e5a5d8827](https://linux-hardware.org/?probe=2e5a5d8827) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [616c5e7edb](https://linux-hardware.org/?probe=616c5e7edb) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [a5359e7def](https://linux-hardware.org/?probe=a5359e7def) | Oct 29, 2019 |
| Foxconn       | A6VMX 0A                    | [74249dc009](https://linux-hardware.org/?probe=74249dc009) | Oct 29, 2019 |
| iEi           | B202 V1.0                   | [bffdad4a05](https://linux-hardware.org/?probe=bffdad4a05) | Oct 26, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASRock        | H61M-VG3                    | [260918f990](https://linux-hardware.org/?probe=260918f990) | Oct 22, 2019 |
| Foxconn       | A6VMX 0A                    | [7991685c3a](https://linux-hardware.org/?probe=7991685c3a) | Oct 14, 2019 |
| Gigabyte      | X99-UD4-CF                  | [54db2b52da](https://linux-hardware.org/?probe=54db2b52da) | Oct 02, 2019 |
| Gigabyte      | H61M-DS2                    | [28b8e9271b](https://linux-hardware.org/?probe=28b8e9271b) | Sep 27, 2019 |
| Gigabyte      | H61M-DS2                    | [3cf419c507](https://linux-hardware.org/?probe=3cf419c507) | Sep 27, 2019 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [fbd6f89151](https://linux-hardware.org/?probe=fbd6f89151) | Sep 19, 2019 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [ff27a61c6c](https://linux-hardware.org/?probe=ff27a61c6c) | Sep 16, 2019 |
| ASUSTek       | V-P8H67E                    | [612c5f53a4](https://linux-hardware.org/?probe=612c5f53a4) | Sep 07, 2019 |
| ASUSTek       | V-P8H67E                    | [9f517e5081](https://linux-hardware.org/?probe=9f517e5081) | Aug 31, 2019 |
| ASRock        | A75M-HVS                    | [c5d625831f](https://linux-hardware.org/?probe=c5d625831f) | Aug 23, 2019 |
| Dell          | 0XCR8D A02                  | [ed9cabe6d7](https://linux-hardware.org/?probe=ed9cabe6d7) | Aug 16, 2019 |
| ASUSTek       | M2N-MX                      | [97e0e3e7ce](https://linux-hardware.org/?probe=97e0e3e7ce) | Aug 04, 2019 |
| ASUSTek       | M2N-MX                      | [662d4876ce](https://linux-hardware.org/?probe=662d4876ce) | Aug 04, 2019 |
| Dell          | 0CRH6C A01                  | [1e288a14af](https://linux-hardware.org/?probe=1e288a14af) | Aug 03, 2019 |
| Fujitsu Si... | D2344-A3 S26361-D2344-A3    | [82e5d349d1](https://linux-hardware.org/?probe=82e5d349d1) | Jul 28, 2019 |
| HP            | 09F8h                       | [c52ee1274d](https://linux-hardware.org/?probe=c52ee1274d) | Jul 27, 2019 |
| Gigabyte      | C1037UN-EU                  | [6790768959](https://linux-hardware.org/?probe=6790768959) | Jul 20, 2019 |
| ASUSTek       | M4A78T-E                    | [607db49638](https://linux-hardware.org/?probe=607db49638) | Jun 22, 2019 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [d8c3110cba](https://linux-hardware.org/?probe=d8c3110cba) | Jun 22, 2019 |
| Gigabyte      | X99-UD4-CF                  | [dfc4a93cdf](https://linux-hardware.org/?probe=dfc4a93cdf) | Jun 21, 2019 |
| Foxconn       | 945 7MD Series              | [1acc3bbabb](https://linux-hardware.org/?probe=1acc3bbabb) | Jun 04, 2019 |
| Dell          | 0C27VV A03                  | [d78c1d6096](https://linux-hardware.org/?probe=d78c1d6096) | May 27, 2019 |
| Dell          | 0C27VV A03                  | [c8bb3e23f9](https://linux-hardware.org/?probe=c8bb3e23f9) | May 27, 2019 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [9ed71fdbcf](https://linux-hardware.org/?probe=9ed71fdbcf) | May 20, 2019 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [b18be16b85](https://linux-hardware.org/?probe=b18be16b85) | May 17, 2019 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [673c1426f0](https://linux-hardware.org/?probe=673c1426f0) | May 12, 2019 |
| ASUSTek       | M2N-X                       | [aa1ba4b47d](https://linux-hardware.org/?probe=aa1ba4b47d) | May 07, 2019 |
| HP            | 1906                        | [7ea8acd893](https://linux-hardware.org/?probe=7ea8acd893) | May 01, 2019 |
| Fujitsu       | D3004-A1 S26361-D3004-A1    | [17448d5b73](https://linux-hardware.org/?probe=17448d5b73) | Apr 29, 2019 |
| ASRock        | B150M Pro4                  | [8227df5ae7](https://linux-hardware.org/?probe=8227df5ae7) | Apr 13, 2019 |
| Dell          | 0K240Y A02                  | [e206f8f36e](https://linux-hardware.org/?probe=e206f8f36e) | Mar 25, 2019 |
| Wibtek        | H61-M HDMI2                 | [6f082a4f2d](https://linux-hardware.org/?probe=6f082a4f2d) | Feb 12, 2019 |
| Wibtek        | H61-M HDMI2                 | [3a44341e10](https://linux-hardware.org/?probe=3a44341e10) | Feb 12, 2019 |
| ASUSTek       | P5P43TD                     | [8d55cb4dca](https://linux-hardware.org/?probe=8d55cb4dca) | Feb 10, 2019 |
| ASRock        | Z97 Anniversary             | [672985bb0e](https://linux-hardware.org/?probe=672985bb0e) | Jan 26, 2019 |
| ASUSTek       | P5Q-PRO                     | [e74d60bf4b](https://linux-hardware.org/?probe=e74d60bf4b) | Jan 08, 2019 |
| ASUSTek       | P5Q-PRO                     | [f5081cb119](https://linux-hardware.org/?probe=f5081cb119) | Jan 08, 2019 |
| Acer          | Extensa X2610G              | [92c3e82d58](https://linux-hardware.org/?probe=92c3e82d58) | Jan 02, 2019 |
| ASRock        | B85M Pro3                   | [70f28e74b9](https://linux-hardware.org/?probe=70f28e74b9) | Dec 10, 2018 |
| ASRock        | Z370 Pro4                   | [7594332b68](https://linux-hardware.org/?probe=7594332b68) | Dec 02, 2018 |
| ASRock        | Z370 Pro4                   | [900f783b11](https://linux-hardware.org/?probe=900f783b11) | Dec 02, 2018 |
| ASRock        | B360M-HDV                   | [fb017cece0](https://linux-hardware.org/?probe=fb017cece0) | Nov 16, 2018 |
| ASRock        | Z77 Extreme3                | [a85b28c3f9](https://linux-hardware.org/?probe=a85b28c3f9) | Nov 15, 2018 |
| Gigabyte      | H81M-S2V                    | [801b3fb729](https://linux-hardware.org/?probe=801b3fb729) | Jun 27, 2018 |
| Gigabyte      | 970A-DS3P                   | [ee5ac544fa](https://linux-hardware.org/?probe=ee5ac544fa) | Feb 24, 2018 |
| Intel         | DH67GD AAG10206-208         | [fbd1d0b016](https://linux-hardware.org/?probe=fbd1d0b016) | Feb 23, 2018 |
| Acer          | Aspire XC-605               | [cbd8d79578](https://linux-hardware.org/?probe=cbd8d79578) | Jan 19, 2018 |
| Foxconn       | A6VMX 0A                    | [8ba0c7f4c3](https://linux-hardware.org/?probe=8ba0c7f4c3) | Dec 21, 2017 |
| Intel         | DH67GD AAG10206-208         | [9722b2d773](https://linux-hardware.org/?probe=9722b2d773) | Oct 31, 2017 |
| Intel         | DH67GD AAG10206-208         | [728c8e49b2](https://linux-hardware.org/?probe=728c8e49b2) | Oct 27, 2017 |
| ASUSTek       | Maximus IX HERO             | [8db3dd798e](https://linux-hardware.org/?probe=8db3dd798e) | Sep 05, 2017 |
| ASUSTek       | Maximus IX HERO             | [9f96da724a](https://linux-hardware.org/?probe=9f96da724a) | Sep 05, 2017 |
| Dell          | 0NKW6Y A00                  | [212f6d0514](https://linux-hardware.org/?probe=212f6d0514) | Sep 03, 2017 |
| Intel         | DH67GD AAG10206-208         | [0c3b83b208](https://linux-hardware.org/?probe=0c3b83b208) | Jun 06, 2017 |
| ASUSTek       | M4A78LT-M                   | [0a1b2311b5](https://linux-hardware.org/?probe=0a1b2311b5) | May 28, 2017 |
| Supermicro    | C2SBC-Q                     | [671517f196](https://linux-hardware.org/?probe=671517f196) | Apr 15, 2017 |
| ASRock        | H61M-GS                     | [5625f5be6e](https://linux-hardware.org/?probe=5625f5be6e) | Jan 30, 2017 |
| ASRock        | H61M-GS                     | [f309dd0e46](https://linux-hardware.org/?probe=f309dd0e46) | Jan 24, 2017 |
| ASRock        | H61M-GS                     | [eb755563bf](https://linux-hardware.org/?probe=eb755563bf) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 40       | 13.75%  |
| Ubuntu 18.04                 | 30       | 10.31%  |
| OpenMandriva 4.2             | 15       | 5.15%   |
| ROSA R11                     | 8        | 2.75%   |
| ROSA R10                     | 8        | 2.75%   |
| Manjaro                      | 8        | 2.75%   |
| Debian 11                    | 8        | 2.75%   |
| ArcoLinux Rolling            | 7        | 2.41%   |
| Xubuntu 18.04                | 6        | 2.06%   |
| Ubuntu 20.10                 | 6        | 2.06%   |
| Linux Mint 20.1              | 6        | 2.06%   |
| Arch                         | 6        | 2.06%   |
| Zorin 15                     | 5        | 1.72%   |
| Ubuntu 19.10                 | 5        | 1.72%   |
| Ubuntu 16.04                 | 5        | 1.72%   |
| KDE neon 20.04               | 5        | 1.72%   |
| Ubuntu 19.04                 | 4        | 1.37%   |
| Pop!_OS 21.10                | 4        | 1.37%   |
| Pop!_OS 20.10                | 4        | 1.37%   |
| Pop!_OS 20.04                | 4        | 1.37%   |
| Linux Mint 19.3              | 4        | 1.37%   |
| Ubuntu 21.04                 | 3        | 1.03%   |
| ROSA R8.1                    | 3        | 1.03%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.03%   |
| OpenMandriva 4.3             | 3        | 1.03%   |
| LMDE 4                       | 3        | 1.03%   |
| Linux Mint 20                | 3        | 1.03%   |
| Kubuntu 20.04                | 3        | 1.03%   |
| Xubuntu 20.04                | 2        | 0.69%   |
| Ubuntu MATE 20.04            | 2        | 0.69%   |
| Ubuntu 22.04                 | 2        | 0.69%   |
| ROSA R11.1                   | 2        | 0.69%   |
| Pop!_OS 21.04                | 2        | 0.69%   |
| OpenMandriva 4.50            | 2        | 0.69%   |
| Manjaro 21.2.0               | 2        | 0.69%   |
| Linux Mint 20.2              | 2        | 0.69%   |
| KDE neon 18.04               | 2        | 0.69%   |
| Gentoo 2.6                   | 2        | 0.69%   |
| Fedora 36                    | 2        | 0.69%   |
| Fedora 35                    | 2        | 0.69%   |
| Fedora 33                    | 2        | 0.69%   |
| Elementary 0.4.1             | 2        | 0.69%   |
| Debian 9                     | 2        | 0.69%   |
| CentOS 7                     | 2        | 0.69%   |
| Arch Rolling                 | 2        | 0.69%   |
| Zorin 16                     | 1        | 0.34%   |
| Xubuntu 21.10                | 1        | 0.34%   |
| Xubuntu 20.10                | 1        | 0.34%   |
| Void Linux Rolling           | 1        | 0.34%   |
| Ubuntu Budgie 20.04          | 1        | 0.34%   |
| Ubuntu 21.10                 | 1        | 0.34%   |
| Ubuntu 18.10                 | 1        | 0.34%   |
| Slackware 14.2               | 1        | 0.34%   |
| ROSA R9                      | 1        | 0.34%   |
| ROSA R8                      | 1        | 0.34%   |
| ROSA 12.2                    | 1        | 0.34%   |
| Novos 2020.05                | 1        | 0.34%   |
| Manjaro 21.2rc               | 1        | 0.34%   |
| Manjaro 21.2.5               | 1        | 0.34%   |
| Manjaro 21.1.0               | 1        | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 93       | 33.82%  |
| ROSA          | 20       | 7.27%   |
| OpenMandriva  | 20       | 7.27%   |
| Linux Mint    | 18       | 6.55%   |
| Manjaro       | 16       | 5.82%   |
| Pop!_OS       | 14       | 5.09%   |
| Debian        | 12       | 4.36%   |
| Xubuntu       | 10       | 3.64%   |
| Arch          | 8        | 2.91%   |
| KDE neon      | 7        | 2.55%   |
| Fedora        | 7        | 2.55%   |
| ArcoLinux     | 7        | 2.55%   |
| Zorin         | 6        | 2.18%   |
| Kubuntu       | 5        | 1.82%   |
| openSUSE      | 3        | 1.09%   |
| Lubuntu       | 3        | 1.09%   |
| LMDE          | 3        | 1.09%   |
| Elementary    | 3        | 1.09%   |
| CentOS        | 3        | 1.09%   |
| Ubuntu MATE   | 2        | 0.73%   |
| Gentoo        | 2        | 0.73%   |
| Endless       | 2        | 0.73%   |
| Clear Linux   | 2        | 0.73%   |
| Artix         | 2        | 0.73%   |
| Void Linux    | 1        | 0.36%   |
| Ubuntu Budgie | 1        | 0.36%   |
| Slackware     | 1        | 0.36%   |
| Novos         | 1        | 0.36%   |
| Kali          | 1        | 0.36%   |
| EndeavourOS   | 1        | 0.36%   |
| BlackPanther  | 1        | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002         | 15       | 4.66%   |
| 5.4.0-42-generic                 | 7        | 2.17%   |
| 5.3.0-40-generic                 | 7        | 2.17%   |
| 4.15.0-desktop-45.1rosa-x86_64   | 6        | 1.86%   |
| 5.4.0-58-generic                 | 5        | 1.55%   |
| 5.9.16-1-MANJARO                 | 4        | 1.24%   |
| 5.8.0-43-generic                 | 4        | 1.24%   |
| 5.11.0-27-generic                | 4        | 1.24%   |
| 5.10.0-8-amd64                   | 4        | 1.24%   |
| 5.8.0-7642-generic               | 3        | 0.93%   |
| 5.8.0-40-generic                 | 3        | 0.93%   |
| 5.4.0-56-generic                 | 3        | 0.93%   |
| 5.4.0-37-generic                 | 3        | 0.93%   |
| 5.3.0-46-generic                 | 3        | 0.93%   |
| 5.3.0-45-generic                 | 3        | 0.93%   |
| 5.3.0-42-generic                 | 3        | 0.93%   |
| 5.16.7-desktop-1omv4003          | 3        | 0.93%   |
| 5.15.0-27-generic                | 3        | 0.93%   |
| 5.0.0-37-generic                 | 3        | 0.93%   |
| 5.0.0-23-generic                 | 3        | 0.93%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 3        | 0.93%   |
| 4.15.0-29-generic                | 3        | 0.93%   |
| 5.8.11-1-MANJARO                 | 2        | 0.62%   |
| 5.8.0-44-generic                 | 2        | 0.62%   |
| 5.4.0-7634-generic               | 2        | 0.62%   |
| 5.4.0-67-generic                 | 2        | 0.62%   |
| 5.4.0-66-generic                 | 2        | 0.62%   |
| 5.4.0-65-generic                 | 2        | 0.62%   |
| 5.4.0-59-generic                 | 2        | 0.62%   |
| 5.4.0-49-generic                 | 2        | 0.62%   |
| 5.4.0-48-generic                 | 2        | 0.62%   |
| 5.4.0-40-generic                 | 2        | 0.62%   |
| 5.4.0-29-generic                 | 2        | 0.62%   |
| 5.4.0-26-generic                 | 2        | 0.62%   |
| 5.13.0-30-generic                | 2        | 0.62%   |
| 5.13.0-22-generic                | 2        | 0.62%   |
| 5.12.4-desktop-1omv4050          | 2        | 0.62%   |
| 5.11.0-7614-generic              | 2        | 0.62%   |
| 5.11.0-37-generic                | 2        | 0.62%   |
| 5.10.0-13-amd64                  | 2        | 0.62%   |
| 5.0.0-36-generic                 | 2        | 0.62%   |
| 5.0.0-32-generic                 | 2        | 0.62%   |
| 5.0.0-15-generic                 | 2        | 0.62%   |
| 4.9.76-nrj-desktop-1rosa-x86_64  | 2        | 0.62%   |
| 4.9.20-nrj-desktop-1rosa-x86_64  | 2        | 0.62%   |
| 4.9.124-nrj-desktop-1rosa-x86_64 | 2        | 0.62%   |
| 4.19.0-16-amd64                  | 2        | 0.62%   |
| 4.18.0-25-generic                | 2        | 0.62%   |
| 4.18.0-18-generic                | 2        | 0.62%   |
| 4.15.0-desktop-60.7rosa-x86_64   | 2        | 0.62%   |
| 4.15.0-45-generic                | 2        | 0.62%   |
| 4.1.38-nrj-desktop-2rosa-x86_64  | 2        | 0.62%   |
| 5.9.11-3-MANJARO                 | 1        | 0.31%   |
| 5.8.9-986.native                 | 1        | 0.31%   |
| 5.8.18_1                         | 1        | 0.31%   |
| 5.8.18-050818-generic            | 1        | 0.31%   |
| 5.8.14-arch1-1                   | 1        | 0.31%   |
| 5.8.0-7630-generic               | 1        | 0.31%   |
| 5.8.0-59-generic                 | 1        | 0.31%   |
| 5.8.0-55-generic                 | 1        | 0.31%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 47       | 15.51%  |
| 4.15.0  | 32       | 10.56%  |
| 5.8.0   | 20       | 6.6%    |
| 5.3.0   | 18       | 5.94%   |
| 5.10.14 | 15       | 4.95%   |
| 5.11.0  | 14       | 4.62%   |
| 5.0.0   | 14       | 4.62%   |
| 5.10.0  | 8        | 2.64%   |
| 4.18.0  | 7        | 2.31%   |
| 5.13.0  | 6        | 1.98%   |
| 5.9.16  | 4        | 1.32%   |
| 5.15.0  | 4        | 1.32%   |
| 4.19.0  | 4        | 1.32%   |
| 5.16.7  | 3        | 0.99%   |
| 4.9.60  | 3        | 0.99%   |
| 4.9.20  | 3        | 0.99%   |
| 5.8.18  | 2        | 0.66%   |
| 5.8.11  | 2        | 0.66%   |
| 5.7.7   | 2        | 0.66%   |
| 5.7.6   | 2        | 0.66%   |
| 5.6.0   | 2        | 0.66%   |
| 5.3.16  | 2        | 0.66%   |
| 5.3.14  | 2        | 0.66%   |
| 5.17.6  | 2        | 0.66%   |
| 5.17.5  | 2        | 0.66%   |
| 5.17.11 | 2        | 0.66%   |
| 5.16.15 | 2        | 0.66%   |
| 5.16.11 | 2        | 0.66%   |
| 5.15.6  | 2        | 0.66%   |
| 5.12.4  | 2        | 0.66%   |
| 5.11.11 | 2        | 0.66%   |
| 5.10.79 | 2        | 0.66%   |
| 5.10.16 | 2        | 0.66%   |
| 4.9.76  | 2        | 0.66%   |
| 4.9.124 | 2        | 0.66%   |
| 4.4.0   | 2        | 0.66%   |
| 4.1.38  | 2        | 0.66%   |
| 3.10.0  | 2        | 0.66%   |
| 5.9.11  | 1        | 0.33%   |
| 5.8.9   | 1        | 0.33%   |
| 5.8.14  | 1        | 0.33%   |
| 5.7.17  | 1        | 0.33%   |
| 5.7.11  | 1        | 0.33%   |
| 5.6.3   | 1        | 0.33%   |
| 5.6.17  | 1        | 0.33%   |
| 5.6.16  | 1        | 0.33%   |
| 5.5.7   | 1        | 0.33%   |
| 5.4.83  | 1        | 0.33%   |
| 5.4.80  | 1        | 0.33%   |
| 5.4.18  | 1        | 0.33%   |
| 5.3.8   | 1        | 0.33%   |
| 5.3.5   | 1        | 0.33%   |
| 5.2.9   | 1        | 0.33%   |
| 5.2.8   | 1        | 0.33%   |
| 5.2.15  | 1        | 0.33%   |
| 5.2.0   | 1        | 0.33%   |
| 5.17.9  | 1        | 0.33%   |
| 5.17.4  | 1        | 0.33%   |
| 5.17.2  | 1        | 0.33%   |
| 5.16.4  | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 50       | 16.89%  |
| 5.10    | 34       | 11.49%  |
| 4.15    | 32       | 10.81%  |
| 5.8     | 26       | 8.78%   |
| 5.3     | 22       | 7.43%   |
| 5.11    | 19       | 6.42%   |
| 5.0     | 14       | 4.73%   |
| 5.15    | 12       | 4.05%   |
| 5.16    | 11       | 3.72%   |
| 4.9     | 10       | 3.38%   |
| 5.17    | 8        | 2.7%    |
| 5.13    | 7        | 2.36%   |
| 4.18    | 7        | 2.36%   |
| 5.7     | 6        | 2.03%   |
| 5.9     | 5        | 1.69%   |
| 5.6     | 5        | 1.69%   |
| 5.2     | 4        | 1.35%   |
| 5.14    | 4        | 1.35%   |
| 5.12    | 4        | 1.35%   |
| 4.19    | 4        | 1.35%   |
| 4.1     | 3        | 1.01%   |
| 4.4     | 2        | 0.68%   |
| 3.10    | 2        | 0.68%   |
| 5.5     | 1        | 0.34%   |
| 4.7     | 1        | 0.34%   |
| 4.20    | 1        | 0.34%   |
| 4.10    | 1        | 0.34%   |
| Unknown | 1        | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 254      | 98.07%  |
| i686   | 5        | 1.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 91       | 32.16%  |
| KDE5            | 49       | 17.31%  |
| Unknown         | 48       | 16.96%  |
| XFCE            | 23       | 8.13%   |
| KDE4            | 15       | 5.3%    |
| X-Cinnamon      | 14       | 4.95%   |
| KDE             | 11       | 3.89%   |
| MATE            | 9        | 3.18%   |
| Unity           | 5        | 1.77%   |
| Pantheon        | 3        | 1.06%   |
| LXQt            | 3        | 1.06%   |
| GNOME Flashback | 2        | 0.71%   |
| Budgie          | 2        | 0.71%   |
| bspwm           | 2        | 0.71%   |
| xmonad          | 1        | 0.35%   |
| qtile           | 1        | 0.35%   |
| i3              | 1        | 0.35%   |
| DWM             | 1        | 0.35%   |
| Cinnamon        | 1        | 0.35%   |
| awesome         | 1        | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 230      | 86.14%  |
| Unknown | 17       | 6.37%   |
| Wayland | 15       | 5.62%   |
| Tty     | 5        | 1.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 157      | 57.93%  |
| SDDM    | 50       | 18.45%  |
| GDM     | 16       | 5.9%    |
| KDM     | 15       | 5.54%   |
| LightDM | 14       | 5.17%   |
| TDM     | 13       | 4.8%    |
| GDM3    | 6        | 2.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 140      | 51.85%  |
| Unknown | 56       | 20.74%  |
| bg_BG   | 53       | 19.63%  |
| C       | 7        | 2.59%   |
| en_GB   | 5        | 1.85%   |
| de_DE   | 5        | 1.85%   |
| ru_RU   | 1        | 0.37%   |
| POSIX   | 1        | 0.37%   |
| it_IT   | 1        | 0.37%   |
| C.UTF8  | 1        | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 181      | 67.79%  |
| EFI  | 86       | 32.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 203      | 74.36%  |
| Overlay | 24       | 8.79%   |
| Unknown | 22       | 8.06%   |
| Btrfs   | 14       | 5.13%   |
| Xfs     | 4        | 1.47%   |
| Zfs     | 3        | 1.1%    |
| Tmpfs   | 1        | 0.37%   |
| Jfs     | 1        | 0.37%   |
| Ext3    | 1        | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 159      | 59.55%  |
| GPT     | 64       | 23.97%  |
| MBR     | 44       | 16.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 217      | 80.07%  |
| Yes       | 54       | 19.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 175      | 66.29%  |
| Yes       | 89       | 33.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 68       | 26.25%  |
| ASRock              | 54       | 20.85%  |
| Gigabyte Technology | 41       | 15.83%  |
| Lenovo              | 15       | 5.79%   |
| Hewlett-Packard     | 15       | 5.79%   |
| MSI                 | 14       | 5.41%   |
| Dell                | 12       | 4.63%   |
| Fujitsu             | 9        | 3.47%   |
| Intel               | 6        | 2.32%   |
| Foxconn             | 4        | 1.54%   |
| Acer                | 4        | 1.54%   |
| Unknown             | 4        | 1.54%   |
| Wibtek              | 2        | 0.77%   |
| Pegatron            | 2        | 0.77%   |
| Fujitsu Siemens     | 2        | 0.77%   |
| Supermicro          | 1        | 0.39%   |
| Shuttle             | 1        | 0.39%   |
| Seco                | 1        | 0.39%   |
| Packard Bell        | 1        | 0.39%   |
| MiTAC               | 1        | 0.39%   |
| iEi                 | 1        | 0.39%   |
| ECS                 | 1        | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 5        | 1.93%   |
| Lenovo H520S 2561                  | 4        | 1.54%   |
| Unknown                            | 4        | 1.54%   |
| ASRock Z97 Anniversary             | 3        | 1.16%   |
| Wibtek H61-M HDMI2                 | 2        | 0.77%   |
| Lenovo H520e 10159                 | 2        | 0.77%   |
| Gigabyte X99-UD4-CF                | 2        | 0.77%   |
| Gigabyte H370AORUSGAMING3WIFI      | 2        | 0.77%   |
| Gigabyte B450 AORUS M              | 2        | 0.77%   |
| Fujitsu ESPRIMO P710               | 2        | 0.77%   |
| Dell Precision Tower 5810          | 2        | 0.77%   |
| Dell OptiPlex 780                  | 2        | 0.77%   |
| ASUS PRIME X570-P                  | 2        | 0.77%   |
| ASUS P5Q-PRO                       | 2        | 0.77%   |
| ASUS P5KC                          | 2        | 0.77%   |
| ASRock H110M-HDV                   | 2        | 0.77%   |
| ASRock H110M-DGS                   | 2        | 0.77%   |
| ASRock G41M-S3                     | 2        | 0.77%   |
| ASRock B450M-HDV R4.0              | 2        | 0.77%   |
| ASRock B450M Steel Legend          | 2        | 0.77%   |
| ASRock 890GX Extreme3              | 2        | 0.77%   |
| Supermicro C2SBC-Q                 | 1        | 0.39%   |
| Shuttle XH81V                      | 1        | 0.39%   |
| Seco C40                           | 1        | 0.39%   |
| Pegatron Compaq 505B Microtower PC | 1        | 0.39%   |
| Pegatron 520-1030uk                | 1        | 0.39%   |
| Packard Bell IMEDIA S2185          | 1        | 0.39%   |
| MSI Pentino G-Series MT            | 1        | 0.39%   |
| MSI MS-7D59                        | 1        | 0.39%   |
| MSI MS-7C84                        | 1        | 0.39%   |
| MSI MS-7C56                        | 1        | 0.39%   |
| MSI MS-7C35                        | 1        | 0.39%   |
| MSI MS-7C09                        | 1        | 0.39%   |
| MSI MS-7B86                        | 1        | 0.39%   |
| MSI MS-7B17                        | 1        | 0.39%   |
| MSI MS-7A63                        | 1        | 0.39%   |
| MSI MS-7A34                        | 1        | 0.39%   |
| MSI MS-7978                        | 1        | 0.39%   |
| MSI MS-7895                        | 1        | 0.39%   |
| MSI MS-7368                        | 1        | 0.39%   |
| MSI MS-7250                        | 1        | 0.39%   |
| MiTAC E220 6A7                     | 1        | 0.39%   |
| Lenovo ThinkStation S30 0606CW2    | 1        | 0.39%   |
| Lenovo ThinkStation D20 4158E93    | 1        | 0.39%   |
| Lenovo ThinkCentre M91p 7033W9N    | 1        | 0.39%   |
| Lenovo ThinkCentre M90p 5864BQ9    | 1        | 0.39%   |
| Lenovo ThinkCentre M83 10AGS17E00  | 1        | 0.39%   |
| Lenovo ThinkCentre M82 3395W1K     | 1        | 0.39%   |
| Lenovo ThinkCentre M82 26972W5     | 1        | 0.39%   |
| Lenovo ThinkCentre M58p 6234A1G    | 1        | 0.39%   |
| Lenovo H50-50 90B600BFBG           | 1        | 0.39%   |
| Intel X99 V102                     | 1        | 0.39%   |
| Intel X99                          | 1        | 0.39%   |
| Intel DX58SO2 AAG10925-205         | 1        | 0.39%   |
| Intel DH67GD AAG10206-208          | 1        | 0.39%   |
| Intel DG35EC AAE29266-205          | 1        | 0.39%   |
| Intel DESKTOP 300                  | 1        | 0.39%   |
| iEi B202                           | 1        | 0.39%   |
| HP Z230 SFF Workstation            | 1        | 0.39%   |
| HP rp5800                          | 1        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| HP Compaq                     | 10       | 3.86%   |
| ASUS PRIME                    | 9        | 3.47%   |
| Fujitsu ESPRIMO               | 8        | 3.09%   |
| Dell OptiPlex                 | 8        | 3.09%   |
| Lenovo ThinkCentre            | 6        | 2.32%   |
| ASUS ROG                      | 5        | 1.93%   |
| ASUS All                      | 5        | 1.93%   |
| Lenovo H520S                  | 4        | 1.54%   |
| ASUS P5K                      | 4        | 1.54%   |
| Unknown                       | 4        | 1.54%   |
| Gigabyte X570                 | 3        | 1.16%   |
| Dell Precision                | 3        | 1.16%   |
| ASUS TUF                      | 3        | 1.16%   |
| ASRock Z97                    | 3        | 1.16%   |
| ASRock X570                   | 3        | 1.16%   |
| Wibtek H61-M                  | 2        | 0.77%   |
| Lenovo ThinkStation           | 2        | 0.77%   |
| Lenovo H520e                  | 2        | 0.77%   |
| Intel X99                     | 2        | 0.77%   |
| Gigabyte Z490                 | 2        | 0.77%   |
| Gigabyte X99-UD4-CF           | 2        | 0.77%   |
| Gigabyte H370AORUSGAMING3WIFI | 2        | 0.77%   |
| Gigabyte B450                 | 2        | 0.77%   |
| ASUS P5Q-PRO                  | 2        | 0.77%   |
| ASUS P5P43TD                  | 2        | 0.77%   |
| ASUS P5KPL-AM                 | 2        | 0.77%   |
| ASUS P5KC                     | 2        | 0.77%   |
| ASUS M2N-MX                   | 2        | 0.77%   |
| ASRock H110M-HDV              | 2        | 0.77%   |
| ASRock H110M-DGS              | 2        | 0.77%   |
| ASRock G41M-S3                | 2        | 0.77%   |
| ASRock B85M                   | 2        | 0.77%   |
| ASRock B450M-HDV              | 2        | 0.77%   |
| ASRock B450M                  | 2        | 0.77%   |
| ASRock AB350M                 | 2        | 0.77%   |
| ASRock 890GX                  | 2        | 0.77%   |
| Acer Aspire                   | 2        | 0.77%   |
| Supermicro C2SBC-Q            | 1        | 0.39%   |
| Shuttle XH81V                 | 1        | 0.39%   |
| Seco C40                      | 1        | 0.39%   |
| Pegatron Compaq               | 1        | 0.39%   |
| Pegatron 520-1030uk           | 1        | 0.39%   |
| Packard Bell IMEDIA           | 1        | 0.39%   |
| MSI Pentino                   | 1        | 0.39%   |
| MSI MS-7D59                   | 1        | 0.39%   |
| MSI MS-7C84                   | 1        | 0.39%   |
| MSI MS-7C56                   | 1        | 0.39%   |
| MSI MS-7C35                   | 1        | 0.39%   |
| MSI MS-7C09                   | 1        | 0.39%   |
| MSI MS-7B86                   | 1        | 0.39%   |
| MSI MS-7B17                   | 1        | 0.39%   |
| MSI MS-7A63                   | 1        | 0.39%   |
| MSI MS-7A34                   | 1        | 0.39%   |
| MSI MS-7978                   | 1        | 0.39%   |
| MSI MS-7895                   | 1        | 0.39%   |
| MSI MS-7368                   | 1        | 0.39%   |
| MSI MS-7250                   | 1        | 0.39%   |
| MiTAC E220                    | 1        | 0.39%   |
| Lenovo H50-50                 | 1        | 0.39%   |
| Intel DX58SO2                 | 1        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 26       | 10.04%  |
| 2011 | 25       | 9.65%   |
| 2012 | 24       | 9.27%   |
| 2014 | 20       | 7.72%   |
| 2018 | 19       | 7.34%   |
| 2017 | 18       | 6.95%   |
| 2007 | 18       | 6.95%   |
| 2019 | 17       | 6.56%   |
| 2009 | 16       | 6.18%   |
| 2010 | 14       | 5.41%   |
| 2015 | 13       | 5.02%   |
| 2008 | 13       | 5.02%   |
| 2020 | 10       | 3.86%   |
| 2006 | 8        | 3.09%   |
| 2021 | 7        | 2.7%    |
| 2016 | 7        | 2.7%    |
| 2005 | 3        | 1.16%   |
| 2022 | 1        | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 259      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 255      | 98.08%  |
| Enabled  | 5        | 1.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 259      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 55       | 20.45%  |
| 16.01-24.0  | 51       | 18.96%  |
| 4.01-8.0    | 50       | 18.59%  |
| 8.01-16.0   | 49       | 18.22%  |
| 32.01-64.0  | 28       | 10.41%  |
| 1.01-2.0    | 11       | 4.09%   |
| 24.01-32.0  | 9        | 3.35%   |
| 2.01-3.0    | 9        | 3.35%   |
| 64.01-256.0 | 6        | 2.23%   |
| 0.51-1.0    | 1        | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 105      | 35.23%  |
| 2.01-3.0   | 74       | 24.83%  |
| 4.01-8.0   | 40       | 13.42%  |
| 3.01-4.0   | 34       | 11.41%  |
| 0.51-1.0   | 34       | 11.41%  |
| 8.01-16.0  | 8        | 2.68%   |
| 24.01-32.0 | 1        | 0.34%   |
| 16.01-24.0 | 1        | 0.34%   |
| 0.01-0.5   | 1        | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 110      | 40.15%  |
| 2      | 90       | 32.85%  |
| 3      | 36       | 13.14%  |
| 4      | 14       | 5.11%   |
| 5      | 12       | 4.38%   |
| 6      | 5        | 1.82%   |
| 7      | 2        | 0.73%   |
| 0      | 2        | 0.73%   |
| 11     | 1        | 0.36%   |
| 9      | 1        | 0.36%   |
| 8      | 1        | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 138      | 51.49%  |
| No        | 130      | 48.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 258      | 99.61%  |
| No        | 1        | 0.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 199      | 76.25%  |
| Yes       | 62       | 23.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 213      | 80.68%  |
| Yes       | 51       | 19.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Bulgaria | 259      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Sofia             | 118      | 43.7%   |
| Varna             | 22       | 8.15%   |
| Plovdiv           | 19       | 7.04%   |
| Burgas            | 9        | 3.33%   |
| Stara Zagora      | 8        | 2.96%   |
| Rousse            | 8        | 2.96%   |
| Sliven            | 6        | 2.22%   |
| Pernik            | 6        | 2.22%   |
| Veliko Tarnovo    | 4        | 1.48%   |
| Shumen            | 4        | 1.48%   |
| Razgrad           | 3        | 1.11%   |
| Kazanlak          | 3        | 1.11%   |
| Haskovo           | 3        | 1.11%   |
| Dobrich           | 3        | 1.11%   |
| Asenovgrad        | 3        | 1.11%   |
| Vidin             | 2        | 0.74%   |
| Targovishte       | 2        | 0.74%   |
| Sistov            | 2        | 0.74%   |
| Pleven            | 2        | 0.74%   |
| Novi Pazar        | 2        | 0.74%   |
| Novi Iskar        | 2        | 0.74%   |
| Kyustendil        | 2        | 0.74%   |
| Gabrovo           | 2        | 0.74%   |
| Cherven           | 2        | 0.74%   |
| Zlatitsa          | 1        | 0.37%   |
| Vratsa            | 1        | 0.37%   |
| Velingrad         | 1        | 0.37%   |
| Tvarditsa         | 1        | 0.37%   |
| Toros             | 1        | 0.37%   |
| Svoge             | 1        | 0.37%   |
| Smolyan           | 1        | 0.37%   |
| Slatina           | 1        | 0.37%   |
| Slashten          | 1        | 0.37%   |
| Silistra          | 1        | 0.37%   |
| Septemvri         | 1        | 0.37%   |
| Rakovski          | 1        | 0.37%   |
| Popovo            | 1        | 0.37%   |
| Petrich           | 1        | 0.37%   |
| Peshtera          | 1        | 0.37%   |
| Pazardzhik        | 1        | 0.37%   |
| Orlyak            | 1        | 0.37%   |
| Omurtag           | 1        | 0.37%   |
| Nane              | 1        | 0.37%   |
| Montana           | 1        | 0.37%   |
| Mezdra            | 1        | 0.37%   |
| Malashevtsi       | 1        | 0.37%   |
| Maglizh           | 1        | 0.37%   |
| Krumovgrad        | 1        | 0.37%   |
| Knezha            | 1        | 0.37%   |
| Karlovo           | 1        | 0.37%   |
| Gorna Oryahovitsa | 1        | 0.37%   |
| Dolni Dabnik      | 1        | 0.37%   |
| Dimitrovgrad      | 1        | 0.37%   |
| Cherven Bryag     | 1        | 0.37%   |
| Byala             | 1        | 0.37%   |
| Bozhurishte       | 1        | 0.37%   |
| Blagoevgrad       | 1        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| Seagate                 | 91       | 142    | 19.91%  |
| WDC                     | 84       | 140    | 18.38%  |
| Samsung Electronics     | 62       | 92     | 13.57%  |
| Hitachi                 | 40       | 61     | 8.75%   |
| Kingston                | 28       | 40     | 6.13%   |
| Toshiba                 | 27       | 39     | 5.91%   |
| A-DATA Technology       | 19       | 26     | 4.16%   |
| Team                    | 10       | 11     | 2.19%   |
| Intel                   | 10       | 13     | 2.19%   |
| SanDisk                 | 8        | 9      | 1.75%   |
| Phison                  | 7        | 7      | 1.53%   |
| Crucial                 | 7        | 13     | 1.53%   |
| China                   | 7        | 7      | 1.53%   |
| SPCC                    | 5        | 6      | 1.09%   |
| Patriot                 | 5        | 6      | 1.09%   |
| Maxtor                  | 5        | 8      | 1.09%   |
| Realtek Semiconductor   | 4        | 5      | 0.88%   |
| HGST                    | 4        | 8      | 0.88%   |
| XPG                     | 3        | 5      | 0.66%   |
| Unknown                 | 3        | 6      | 0.66%   |
| Silicon Motion          | 3        | 6      | 0.66%   |
| OCZ                     | 2        | 2      | 0.44%   |
| KIOXIA                  | 2        | 2      | 0.44%   |
| KingSpec                | 2        | 2      | 0.44%   |
| JMicron Technology      | 2        | 3      | 0.44%   |
| ExcelStor               | 2        | 6      | 0.44%   |
| Union Memory (Shenzhen) | 1        | 4      | 0.22%   |
| Transcend               | 1        | 2      | 0.22%   |
| TO Exter                | 1        | 1      | 0.22%   |
| OCZ-VERTEX3             | 1        | 1      | 0.22%   |
| Micron Technology       | 1        | 1      | 0.22%   |
| LITEON                  | 1        | 1      | 0.22%   |
| Intenso                 | 1        | 1      | 0.22%   |
| Innodisk                | 1        | 1      | 0.22%   |
| HGST HTS                | 1        | 1      | 0.22%   |
| Hewlett-Packard         | 1        | 1      | 0.22%   |
| Gigabyte Technology     | 1        | 6      | 0.22%   |
| Corsair                 | 1        | 1      | 0.22%   |
| ATP                     | 1        | 2      | 0.22%   |
| ASMedia                 | 1        | 1      | 0.22%   |
| AMD                     | 1        | 2      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB        | 14       | 2.66%   |
| Kingston SA400S37120G 120GB SSD        | 8        | 1.52%   |
| Toshiba DT01ACA100 1TB                 | 7        | 1.33%   |
| Seagate ST1000DM010-2EP102 1TB         | 7        | 1.33%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 7        | 1.33%   |
| Seagate ST1000DM003-1ER162 1TB         | 6        | 1.14%   |
| Kingston SV300S37A120G 120GB SSD       | 6        | 1.14%   |
| Kingston SA400S37480G 480GB SSD        | 6        | 1.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 5        | 0.95%   |
| Toshiba DT01ACA050 500GB               | 5        | 0.95%   |
| Seagate ST2000DM008-2FR102 2TB         | 5        | 0.95%   |
| Samsung SSD 860 EVO 250GB              | 5        | 0.95%   |
| Samsung SSD 860 EVO 1TB                | 5        | 0.95%   |
| Samsung SSD 850 PRO 256GB              | 5        | 0.95%   |
| Samsung SSD 850 EVO 250GB              | 5        | 0.95%   |
| Hitachi HDP725050GLA360 500GB          | 5        | 0.95%   |
| Toshiba DT01ACA200 2TB                 | 4        | 0.76%   |
| Samsung SSD 970 EVO 250GB              | 4        | 0.76%   |
| Samsung NVMe SSD Drive 250GB           | 4        | 0.76%   |
| Hitachi HDS721616PLA380 160GB          | 4        | 0.76%   |
| Hitachi HDS721050CLA362 500GB          | 4        | 0.76%   |
| A-DATA SU650 240GB SSD                 | 4        | 0.76%   |
| XPG NVMe SSD Drive 512GB               | 3        | 0.57%   |
| WDC WD2003FZEX-00SRLA0 2TB             | 3        | 0.57%   |
| WDC WD2002FAEX-007BA0 2TB              | 3        | 0.57%   |
| WDC WD10EZEX-22BN5A0 1TB               | 3        | 0.57%   |
| WDC WD10EZEX-00WN4A0 1TB               | 3        | 0.57%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 3        | 0.57%   |
| Toshiba HDWD110 1TB                    | 3        | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB         | 3        | 0.57%   |
| Seagate ST3500413AS 500GB              | 3        | 0.57%   |
| Seagate ST3250312AS 250GB              | 3        | 0.57%   |
| Seagate ST31000524AS 1TB               | 3        | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB         | 3        | 0.57%   |
| Samsung SSD 850 EVO 500GB              | 3        | 0.57%   |
| Kingston SA400S37240G 240GB SSD        | 3        | 0.57%   |
| Hitachi HDS721010CLA332 1TB            | 3        | 0.57%   |
| A-DATA SU650 120GB SSD                 | 3        | 0.57%   |
| WDC WD6000HLHX-01JJPV0 600GB           | 2        | 0.38%   |
| WDC WD5000AAKX-603CA0 500GB            | 2        | 0.38%   |
| WDC WD5000AAKX-08U6AA0 500GB           | 2        | 0.38%   |
| WDC WD5000AADS-00S9B0 500GB            | 2        | 0.38%   |
| WDC WD30PURX-64P6ZY0 3TB               | 2        | 0.38%   |
| WDC WD30EFRX-68EUZN0 3TB               | 2        | 0.38%   |
| WDC WD10EZEX-75M2NA0 1TB               | 2        | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB               | 2        | 0.38%   |
| WDC WD1003FZEX-00MK2A0 1TB             | 2        | 0.38%   |
| WDC WD1002FAEX-00Y9A0 1TB              | 2        | 0.38%   |
| Toshiba DT01ACA300 3TB                 | 2        | 0.38%   |
| Team T253X2256G 256GB SSD              | 2        | 0.38%   |
| Team T2535T240G 240GB SSD              | 2        | 0.38%   |
| SPCC Solid State Disk 128GB            | 2        | 0.38%   |
| Seagate ST500LT012-1DG142 500GB        | 2        | 0.38%   |
| Seagate ST4000VN008-2DR166 4TB         | 2        | 0.38%   |
| Seagate ST380815AS 80GB                | 2        | 0.38%   |
| Seagate ST3500320AS 500GB              | 2        | 0.38%   |
| Seagate ST3500312CS 500GB              | 2        | 0.38%   |
| Seagate ST3320620AS 320GB              | 2        | 0.38%   |
| Seagate ST3160815AS 160GB              | 2        | 0.38%   |
| Seagate ST2000VN004-2E4164 2TB         | 2        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 91       | 142    | 35.69%  |
| WDC                 | 78       | 129    | 30.59%  |
| Hitachi             | 40       | 61     | 15.69%  |
| Toshiba             | 25       | 37     | 9.8%    |
| Samsung Electronics | 6        | 8      | 2.35%   |
| Maxtor              | 5        | 8      | 1.96%   |
| HGST                | 4        | 8      | 1.57%   |
| ExcelStor           | 2        | 6      | 0.78%   |
| JMicron Technology  | 1        | 1      | 0.39%   |
| HGST HTS            | 1        | 1      | 0.39%   |
| Hewlett-Packard     | 1        | 1      | 0.39%   |
| ASMedia             | 1        | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 36       | 47     | 23.84%  |
| Kingston            | 28       | 40     | 18.54%  |
| A-DATA Technology   | 18       | 23     | 11.92%  |
| Team                | 10       | 11     | 6.62%   |
| Intel               | 8        | 11     | 5.3%    |
| Crucial             | 7        | 13     | 4.64%   |
| China               | 7        | 7      | 4.64%   |
| WDC                 | 6        | 9      | 3.97%   |
| SanDisk             | 6        | 7      | 3.97%   |
| SPCC                | 5        | 6      | 3.31%   |
| Patriot             | 5        | 6      | 3.31%   |
| OCZ                 | 2        | 2      | 1.32%   |
| KingSpec            | 2        | 2      | 1.32%   |
| Transcend           | 1        | 2      | 0.66%   |
| Toshiba             | 1        | 1      | 0.66%   |
| TO Exter            | 1        | 1      | 0.66%   |
| OCZ-VERTEX3         | 1        | 1      | 0.66%   |
| LITEON              | 1        | 1      | 0.66%   |
| JMicron Technology  | 1        | 2      | 0.66%   |
| Intenso             | 1        | 1      | 0.66%   |
| Gigabyte Technology | 1        | 6      | 0.66%   |
| Corsair             | 1        | 1      | 0.66%   |
| ATP                 | 1        | 2      | 0.66%   |
| AMD                 | 1        | 2      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 204      | 403    | 53.26%  |
| SSD     | 126      | 204    | 32.9%   |
| NVMe    | 50       | 79     | 13.05%  |
| Unknown | 2        | 4      | 0.52%   |
| MMC     | 1        | 1      | 0.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 247      | 599    | 80.72%  |
| NVMe | 50       | 79     | 16.34%  |
| SAS  | 8        | 12     | 2.61%   |
| MMC  | 1        | 1      | 0.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 201      | 358    | 58.43%  |
| 0.51-1.0   | 87       | 154    | 25.29%  |
| 1.01-2.0   | 28       | 42     | 8.14%   |
| 3.01-4.0   | 11       | 27     | 3.2%    |
| 2.01-3.0   | 10       | 17     | 2.91%   |
| 4.01-10.0  | 4        | 6      | 1.16%   |
| 10.01-20.0 | 3        | 3      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 66       | 23.57%  |
| 251-500        | 49       | 17.5%   |
| 501-1000       | 39       | 13.93%  |
| 1001-2000      | 31       | 11.07%  |
| 1-20           | 28       | 10%     |
| 51-100         | 22       | 7.86%   |
| More than 3000 | 18       | 6.43%   |
| Unknown        | 11       | 3.93%   |
| 2001-3000      | 9        | 3.21%   |
| 21-50          | 7        | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 119      | 40.48%  |
| 21-50          | 39       | 13.27%  |
| 101-250        | 32       | 10.88%  |
| 51-100         | 29       | 9.86%   |
| 501-1000       | 21       | 7.14%   |
| 251-500        | 16       | 5.44%   |
| 1001-2000      | 15       | 5.1%    |
| Unknown        | 11       | 3.74%   |
| More than 3000 | 7        | 2.38%   |
| 2001-3000      | 5        | 1.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD6000HLHX-01JJPV0 600GB          | 2        | 3      | 4.44%   |
| WDC WD5000AAKX-603CA0 500GB           | 2        | 6      | 4.44%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 4.44%   |
| Seagate ST2000DM001-1CH164 2TB        | 2        | 2      | 4.44%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 2      | 2.22%   |
| WDC WD5000AACS-00G8B1 500GB           | 1        | 1      | 2.22%   |
| WDC WD3200AAJS-07M0A0 320GB           | 1        | 2      | 2.22%   |
| WDC WD2500JS-00MHB0 250GB             | 1        | 1      | 2.22%   |
| WDC WD15EARS-00S8B1 1TB               | 1        | 1      | 2.22%   |
| WDC WD10EARS-00MVWB0 1TB              | 1        | 1      | 2.22%   |
| Toshiba DT01ACA300 3TB                | 1        | 1      | 2.22%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 2.22%   |
| Seagate ST380215A 80GB                | 1        | 1      | 2.22%   |
| Seagate ST3500830AS 500GB             | 1        | 1      | 2.22%   |
| Seagate ST3320311CS 320GB             | 1        | 1      | 2.22%   |
| Seagate ST31000333AS 1TB              | 1        | 1      | 2.22%   |
| Seagate ST2000DM001-9YN164 2TB        | 1        | 1      | 2.22%   |
| SanDisk SDSSDX480GG25 480GB           | 1        | 1      | 2.22%   |
| Samsung Electronics SSD 970 EVO 250GB | 1        | 1      | 2.22%   |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 2      | 2.22%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1        | 1      | 2.22%   |
| Patriot P200 512GB SSD                | 1        | 1      | 2.22%   |
| Maxtor 6Y160M0 160GB                  | 1        | 1      | 2.22%   |
| Maxtor 6L080P0 81GB                   | 1        | 1      | 2.22%   |
| Maxtor 2F040L0 41GB                   | 1        | 1      | 2.22%   |
| Kingston SV300S37A60G 64GB SSD        | 1        | 1      | 2.22%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 2.22%   |
| Kingston SUV500240G 240GB SSD         | 1        | 1      | 2.22%   |
| Kingston SA400S37480G 480GB SSD       | 1        | 1      | 2.22%   |
| Intel SSDSC2BW480A4 480GB             | 1        | 2      | 2.22%   |
| Intel SSDSC2BW120A3F 120GB            | 1        | 1      | 2.22%   |
| Hitachi HDT722525DLA380 250GB         | 1        | 1      | 2.22%   |
| Hitachi HDT721010SLA360 1TB           | 1        | 1      | 2.22%   |
| Hitachi HDS721010CLA330 1TB           | 1        | 1      | 2.22%   |
| Hitachi HDP725050GLA360 500GB         | 1        | 1      | 2.22%   |
| ExcelStor Technology J9250S 250GB     | 1        | 2      | 2.22%   |
| ExcelStor Technology J680 82GB        | 1        | 1      | 2.22%   |
| China SSD 120GB                       | 1        | 1      | 2.22%   |
| A-DATA Technology SX900 256GB SSD     | 1        | 1      | 2.22%   |
| A-DATA Technology SU800 512GB SSD     | 1        | 1      | 2.22%   |
| A-DATA Technology SU700 120GB SSD     | 1        | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 17     | 22.22%  |
| Seagate             | 9        | 9      | 20%     |
| Kingston            | 4        | 4      | 8.89%   |
| Hitachi             | 4        | 4      | 8.89%   |
| Samsung Electronics | 3        | 4      | 6.67%   |
| Maxtor              | 3        | 3      | 6.67%   |
| A-DATA Technology   | 3        | 3      | 6.67%   |
| Toshiba             | 2        | 2      | 4.44%   |
| Intel               | 2        | 3      | 4.44%   |
| ExcelStor           | 2        | 3      | 4.44%   |
| SanDisk             | 1        | 1      | 2.22%   |
| Patriot             | 1        | 1      | 2.22%   |
| China               | 1        | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Desktops | Drives | Percent |
|-----------|----------|--------|---------|
| WDC       | 10       | 17     | 33.33%  |
| Seagate   | 9        | 9      | 30%     |
| Hitachi   | 4        | 4      | 13.33%  |
| Maxtor    | 3        | 3      | 10%     |
| Toshiba   | 2        | 2      | 6.67%   |
| ExcelStor | 2        | 3      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 38     | 66.67%  |
| SSD  | 12       | 14     | 28.57%  |
| NVMe | 2        | 3      | 4.76%   |

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
| Detected | 165      | 426    | 55%     |
| Works    | 97       | 210    | 32.33%  |
| Malfunc  | 38       | 55     | 12.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 169      | 48.42%  |
| AMD                           | 75       | 21.49%  |
| Samsung Electronics           | 30       | 8.6%    |
| JMicron Technology            | 17       | 4.87%   |
| Nvidia                        | 15       | 4.3%    |
| Phison Electronics            | 7        | 2.01%   |
| Marvell Technology Group      | 7        | 2.01%   |
| ASMedia Technology            | 6        | 1.72%   |
| ADATA Technology              | 6        | 1.72%   |
| Realtek Semiconductor         | 4        | 1.15%   |
| Silicon Motion                | 3        | 0.86%   |
| SanDisk                       | 3        | 0.86%   |
| KIOXIA                        | 2        | 0.57%   |
| Union Memory (Shenzhen)       | 1        | 0.29%   |
| Toshiba America Info Systems  | 1        | 0.29%   |
| Micron Technology             | 1        | 0.29%   |
| Integrated Technology Express | 1        | 0.29%   |
| Hewlett-Packard               | 1        | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 41       | 8.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 21       | 4.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20       | 4.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 3.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 2.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 2.56%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 2.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 2.35%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 11       | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 2.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10       | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 2.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 2.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9        | 1.92%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 1.71%   |
| Nvidia MCP61 IDE                                                                        | 7        | 1.49%   |
| JMicron JMB368 IDE controller                                                           | 7        | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.49%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 1.49%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 1.28%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 1.28%   |
| AMD FCH IDE Controller                                                                  | 6        | 1.28%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.28%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.07%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 1.07%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.07%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.85%   |
| Realtek Realtek Non-Volatile memory controller                                          | 4        | 0.85%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 0.85%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 0.85%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.85%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 4        | 0.85%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 4        | 0.85%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 4        | 0.85%   |
| AMD SB600 IDE                                                                           | 4        | 0.85%   |
| Phison E12 NVMe Controller                                                              | 3        | 0.64%   |
| JMicron JMB361 AHCI/IDE                                                                 | 3        | 0.64%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 0.64%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 0.64%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 0.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.64%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 0.64%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.43%   |
| Phison E7 NVMe Controller                                                               | 2        | 0.43%   |
| Nvidia MCP65 SATA Controller                                                            | 2        | 0.43%   |
| Nvidia MCP65 IDE                                                                        | 2        | 0.43%   |
| Nvidia MCP55 SATA Controller                                                            | 2        | 0.43%   |
| Nvidia MCP55 IDE                                                                        | 2        | 0.43%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.43%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.43%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.43%   |
| Intel SSD 660P Series                                                                   | 2        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 187      | 53.58%  |
| IDE  | 98       | 28.08%  |
| NVMe | 51       | 14.61%  |
| RAID | 12       | 3.44%   |
| SAS  | 1        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 168      | 64.86%  |
| AMD    | 91       | 35.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 1.92%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 4        | 1.53%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 1.53%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 1.53%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 1.53%   |
| AMD FX-6300 Six-Core Processor              | 4        | 1.53%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 3        | 1.15%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 1.15%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.15%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 1.15%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.15%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.15%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 3        | 1.15%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.15%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.15%   |
| AMD Athlon II X2 250 Processor              | 3        | 1.15%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 2        | 0.77%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 0.77%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.77%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 0.77%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 0.77%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.77%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.77%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 0.77%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.77%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.77%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 0.77%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.77%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 0.77%   |
| Intel Core i5-10600K CPU @ 4.10GHz          | 2        | 0.77%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 0.77%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 0.77%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2        | 0.77%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 0.77%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.77%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.77%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.77%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.77%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 0.77%   |
| Intel Core 2 Duo CPU E8200 @ 2.66GHz        | 2        | 0.77%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz        | 2        | 0.77%   |
| Intel Celeron CPU G1620T @ 2.40GHz          | 2        | 0.77%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 0.77%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 2        | 0.77%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 0.77%   |
| AMD Athlon 64 X2 Dual Core Processor 6000+  | 2        | 0.77%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2        | 0.77%   |
| AMD Athlon 64 Processor 3500+               | 2        | 0.77%   |
| AMD Athlon 64 Processor 3200+               | 2        | 0.77%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.38%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 0.38%   |
| Intel Xeon CPU X5460 @ 3.16GHz              | 1        | 0.38%   |
| Intel Xeon CPU E5420 @ 2.50GHz              | 1        | 0.38%   |
| Intel Xeon CPU E5405 @ 2.00GHz              | 1        | 0.38%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.38%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1        | 0.38%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.38%   |
| Intel Xeon CPU E31220 @ 3.10GHz             | 1        | 0.38%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 47       | 18.01%  |
| Intel Core i3           | 19       | 7.28%   |
| Intel Core i7           | 18       | 6.9%    |
| AMD Ryzen 5             | 17       | 6.51%   |
| Intel Xeon              | 14       | 5.36%   |
| Intel Core 2 Duo        | 14       | 5.36%   |
| Intel Pentium           | 12       | 4.6%    |
| Intel Core 2 Quad       | 12       | 4.6%    |
| Intel Celeron           | 12       | 4.6%    |
| AMD Ryzen 7             | 9        | 3.45%   |
| AMD Athlon 64 X2        | 8        | 3.07%   |
| AMD FX                  | 7        | 2.68%   |
| Intel Pentium Dual-Core | 5        | 1.92%   |
| AMD Ryzen 9             | 5        | 1.92%   |
| AMD Athlon 64           | 5        | 1.92%   |
| AMD A8                  | 5        | 1.92%   |
| Other                   | 4        | 1.53%   |
| Intel Pentium Dual      | 4        | 1.53%   |
| AMD Phenom II X4        | 4        | 1.53%   |
| AMD Athlon II X2        | 4        | 1.53%   |
| Intel Core i9           | 3        | 1.15%   |
| AMD Ryzen 3             | 3        | 1.15%   |
| AMD Athlon II X4        | 3        | 1.15%   |
| Intel Pentium Gold      | 2        | 0.77%   |
| Intel Core 2            | 2        | 0.77%   |
| AMD Sempron             | 2        | 0.77%   |
| AMD Ryzen 7 PRO         | 2        | 0.77%   |
| AMD Ryzen 5 PRO         | 2        | 0.77%   |
| AMD Phenom II X6        | 2        | 0.77%   |
| AMD Phenom II X2        | 2        | 0.77%   |
| AMD Phenom              | 2        | 0.77%   |
| AMD Athlon X4           | 2        | 0.77%   |
| Intel Pentium D         | 1        | 0.38%   |
| AMD Ryzen Embedded      | 1        | 0.38%   |
| AMD Phenom II X3        | 1        | 0.38%   |
| AMD GX                  | 1        | 0.38%   |
| AMD E1                  | 1        | 0.38%   |
| AMD Athlon II X3        | 1        | 0.38%   |
| AMD A6                  | 1        | 0.38%   |
| AMD A4                  | 1        | 0.38%   |
| AMD A10                 | 1        | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 93       | 35.63%  |
| 4       | 90       | 34.48%  |
| 6       | 32       | 12.26%  |
| 8       | 19       | 7.28%   |
| 1       | 9        | 3.45%   |
| 3       | 8        | 3.07%   |
| 12      | 7        | 2.68%   |
| 16      | 1        | 0.38%   |
| 14      | 1        | 0.38%   |
| Unknown | 1        | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 257      | 99.23%  |
| 2      | 2        | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 155      | 59.16%  |
| 2       | 106      | 40.46%  |
| Unknown | 1        | 0.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 254      | 97.32%  |
| Unknown        | 7        | 2.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 72       | 26.28%  |
| 0x306c3    | 24       | 8.76%   |
| 0x206a7    | 19       | 6.93%   |
| 0x306a9    | 15       | 5.47%   |
| 0x1067a    | 14       | 5.11%   |
| 0x506e3    | 11       | 4.01%   |
| 0x010000c8 | 10       | 3.65%   |
| 0x906ea    | 7        | 2.55%   |
| 0x906e9    | 7        | 2.55%   |
| 0x6fb      | 7        | 2.55%   |
| 0x6fd      | 6        | 2.19%   |
| 0x306f2    | 6        | 2.19%   |
| 0x10676    | 4        | 1.46%   |
| 0x0a201009 | 4        | 1.46%   |
| 0x0800820d | 4        | 1.46%   |
| 0x06000852 | 4        | 1.46%   |
| 0xa0671    | 3        | 1.09%   |
| 0xa0655    | 3        | 1.09%   |
| 0x08701013 | 3        | 1.09%   |
| 0x06003106 | 3        | 1.09%   |
| 0x06001119 | 3        | 1.09%   |
| 0x6f6      | 2        | 0.73%   |
| 0x206c2    | 2        | 0.73%   |
| 0x20655    | 2        | 0.73%   |
| 0x0a201204 | 2        | 0.73%   |
| 0x08600103 | 2        | 0.73%   |
| 0x08108109 | 2        | 0.73%   |
| 0x08001138 | 2        | 0.73%   |
| 0x03000027 | 2        | 0.73%   |
| 0x010000db | 2        | 0.73%   |
| 0xf64      | 1        | 0.36%   |
| 0x906eb    | 1        | 0.36%   |
| 0x90672    | 1        | 0.36%   |
| 0x6f2      | 1        | 0.36%   |
| 0x406c4    | 1        | 0.36%   |
| 0x306e4    | 1        | 0.36%   |
| 0x30678    | 1        | 0.36%   |
| 0x206d7    | 1        | 0.36%   |
| 0x106e5    | 1        | 0.36%   |
| 0x10677    | 1        | 0.36%   |
| 0x0a50000c | 1        | 0.36%   |
| 0x0a201205 | 1        | 0.36%   |
| 0x0a201016 | 1        | 0.36%   |
| 0x08701021 | 1        | 0.36%   |
| 0x08600104 | 1        | 0.36%   |
| 0x0810100b | 1        | 0.36%   |
| 0x08001137 | 1        | 0.36%   |
| 0x08001129 | 1        | 0.36%   |
| 0x0800111c | 1        | 0.36%   |
| 0x07030105 | 1        | 0.36%   |
| 0x0700010f | 1        | 0.36%   |
| 0x0600084f | 1        | 0.36%   |
| 0x0600063e | 1        | 0.36%   |
| 0x010000dc | 1        | 0.36%   |
| 0x010000bf | 1        | 0.36%   |
| 0x01000095 | 1        | 0.36%   |
| 0x01000083 | 1        | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 34       | 13.08%  |
| SandyBridge      | 25       | 9.62%   |
| Penryn           | 24       | 9.23%   |
| IvyBridge        | 20       | 7.69%   |
| KabyLake         | 19       | 7.31%   |
| K10              | 19       | 7.31%   |
| Core             | 16       | 6.15%   |
| K8 Hammer        | 14       | 5.38%   |
| Skylake          | 13       | 5%      |
| Zen 3            | 11       | 4.23%   |
| Zen 2            | 11       | 4.23%   |
| Piledriver       | 11       | 4.23%   |
| Zen+             | 9        | 3.46%   |
| Zen              | 8        | 3.08%   |
| Westmere         | 5        | 1.92%   |
| CometLake        | 4        | 1.54%   |
| Steamroller      | 3        | 1.15%   |
| Silvermont       | 2        | 0.77%   |
| K10 Llano        | 2        | 0.77%   |
| Unknown          | 2        | 0.77%   |
| Puma             | 1        | 0.38%   |
| NetBurst         | 1        | 0.38%   |
| Nehalem          | 1        | 0.38%   |
| Jaguar           | 1        | 0.38%   |
| Icelake          | 1        | 0.38%   |
| Excavator        | 1        | 0.38%   |
| Bulldozer        | 1        | 0.38%   |
| Alderlake Hybrid | 1        | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 108      | 38.43%  |
| AMD    | 94       | 33.45%  |
| Intel  | 79       | 28.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 16       | 5.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 4.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 13       | 4.53%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 3.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 7        | 2.44%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 2.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 2.09%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 1.74%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 1.74%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.74%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.39%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.39%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.39%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 4        | 1.39%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 4        | 1.39%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.39%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 4        | 1.39%   |
| AMD Renoir                                                                  | 4        | 1.39%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.39%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 1.05%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.05%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.05%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 1.05%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3        | 1.05%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 3        | 1.05%   |
| Intel HD Graphics 530                                                       | 3        | 1.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.05%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 1.05%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 1.05%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 1.05%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.05%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 0.7%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.7%    |
| Nvidia GF119 [GeForce GT 520]                                               | 2        | 0.7%    |
| Intel HD Graphics 630                                                       | 2        | 0.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.7%    |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 0.7%    |
| AMD RV770 CE [Radeon HD 4710]                                               | 2        | 0.7%    |
| AMD RV710 [Radeon HD 4550]                                                  | 2        | 0.7%    |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 2        | 0.7%    |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                   | 2        | 0.7%    |
| AMD RS480 [Radeon Xpress 1150] (Secondary)                                  | 2        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 0.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 0.7%    |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 2        | 0.7%    |
| AMD Cezanne                                                                 | 2        | 0.7%    |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 2        | 0.7%    |
| AMD Barts XT [Radeon HD 6870]                                               | 2        | 0.7%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.35%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.35%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.35%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.35%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.35%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.35%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 100      | 37.59%  |
| 1 x AMD        | 87       | 32.71%  |
| 1 x Intel      | 63       | 23.68%  |
| 2 x AMD        | 5        | 1.88%   |
| Intel + Nvidia | 5        | 1.88%   |
| Intel + AMD    | 3        | 1.13%   |
| AMD + Nvidia   | 3        | 1.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 186      | 70.72%  |
| Proprietary | 67       | 25.48%  |
| Unknown     | 10       | 3.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 92       | 33.58%  |
| 1.01-2.0   | 46       | 16.79%  |
| 0.01-0.5   | 35       | 12.77%  |
| 3.01-4.0   | 32       | 11.68%  |
| 0.51-1.0   | 32       | 11.68%  |
| 7.01-8.0   | 25       | 9.12%   |
| 5.01-6.0   | 5        | 1.82%   |
| 2.01-3.0   | 3        | 1.09%   |
| 8.01-16.0  | 3        | 1.09%   |
| 16.01-24.0 | 1        | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 37       | 13.7%   |
| Dell                 | 31       | 11.48%  |
| Goldstar             | 28       | 10.37%  |
| Philips              | 26       | 9.63%   |
| Acer                 | 20       | 7.41%   |
| Ancor Communications | 18       | 6.67%   |
| Hewlett-Packard      | 12       | 4.44%   |
| AOC                  | 12       | 4.44%   |
| BenQ                 | 10       | 3.7%    |
| LG Electronics       | 7        | 2.59%   |
| Fujitsu Siemens      | 7        | 2.59%   |
| Panasonic            | 5        | 1.85%   |
| Lenovo               | 4        | 1.48%   |
| HannStar             | 4        | 1.48%   |
| Unknown              | 3        | 1.11%   |
| Sony                 | 3        | 1.11%   |
| NEC Computers        | 3        | 1.11%   |
| Eizo                 | 3        | 1.11%   |
| ViewSonic            | 2        | 0.74%   |
| Vestel Elektronik    | 2        | 0.74%   |
| Vestel               | 2        | 0.74%   |
| Lenovo Group Limited | 2        | 0.74%   |
| Gigabyte Technology  | 2        | 0.74%   |
| ASUSTek Computer     | 2        | 0.74%   |
| ___                  | 1        | 0.37%   |
| WST                  | 1        | 0.37%   |
| WIN                  | 1        | 0.37%   |
| TAR                  | 1        | 0.37%   |
| SUNNY                | 1        | 0.37%   |
| Sharp                | 1        | 0.37%   |
| PRISM+               | 1        | 0.37%   |
| PEGA                 | 1        | 0.37%   |
| Packard Bell         | 1        | 0.37%   |
| Optoma               | 1        | 0.37%   |
| NUG                  | 1        | 0.37%   |
| NCS                  | 1        | 0.37%   |
| MSI                  | 1        | 0.37%   |
| KTC                  | 1        | 0.37%   |
| Iiyama               | 1        | 0.37%   |
| HPN                  | 1        | 0.37%   |
| HKC                  | 1        | 0.37%   |
| HJW                  | 1        | 0.37%   |
| Hitachi              | 1        | 0.37%   |
| eMachines            | 1        | 0.37%   |
| Elo Touch            | 1        | 0.37%   |
| Denver               | 1        | 0.37%   |
| Belinea              | 1        | 0.37%   |
| AUS                  | 1        | 0.37%   |
| Unknown              | 1        | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch              | 3        | 1.03%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                           | 2        | 0.68%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch   | 2        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 2        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch   | 2        | 0.68%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch             | 2        | 0.68%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                    | 2        | 0.68%   |
| Goldstar E2211 GSM5838 1920x1080 477x268mm 21.5-inch                    | 2        | 0.68%   |
| Goldstar 24EN43 GSM59DF 1920x1080 510x290mm 23.1-inch                   | 2        | 0.68%   |
| BenQ FP202WA BNQ76C2 1680x1050 376x301mm 19.0-inch                      | 2        | 0.68%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                         | 2        | 0.68%   |
| Ancor Communications VW202 ACI20A2 1680x1050 433x271mm 20.1-inch        | 2        | 0.68%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                       | 2        | 0.68%   |
| Acer G257HL ACR0415 1920x1080 553x309mm 24.9-inch                       | 2        | 0.68%   |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                       | 2        | 0.68%   |
| ___ LCD TV ___0101 1360x768                                             | 1        | 0.34%   |
| WST L9VB4 WST0388 1440x900 410x256mm 19.0-inch                          | 1        | 0.34%   |
| WIN 19W MONITOR WIN0010 1440x900 420x320mm 20.8-inch                    | 1        | 0.34%   |
| ViewSonic VG2021m-2 VSCE11D 1400x1050 410x310mm 20.2-inch               | 1        | 0.34%   |
| ViewSonic LCD Monitor VG2236 SERIES 1920x1080                           | 1        | 0.34%   |
| Vestel LCD Monitor 48UHD_LCD_TV                                         | 1        | 0.34%   |
| Vestel LCD Monitor 22W_LCD_TV 1920x1080                                 | 1        | 0.34%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                      | 1        | 0.34%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.34%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.34%   |
| TAR LCD Monitor LCD17-6 3200x1080                                       | 1        | 0.34%   |
| SUNNY SUNNY SNN0002 1920x1080 708x398mm 32.0-inch                       | 1        | 0.34%   |
| Sony TV *00 SNYF303 1920x1080 1439x809mm 65.0-inch                      | 1        | 0.34%   |
| Sony LCD Monitor TV 1920x1080                                           | 1        | 0.34%   |
| Sony LCD Monitor TV 1820x1023                                           | 1        | 0.34%   |
| Sharp HDMI SHP102F 1400x1050 820x460mm 37.0-inch                        | 1        | 0.34%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch       | 1        | 0.34%   |
| Samsung Electronics T24D391 SAM0B73 1920x1080 520x290mm 23.4-inch       | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 474x296mm 22.0-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM036D 1920x1080                        | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM0218 1280x1024 376x301mm 19.0-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM0216 1280x1024 338x270mm 17.0-inch    | 1        | 0.34%   |
| Samsung Electronics SyncMaster SAM00D2 1280x1024 338x270mm 17.0-inch    | 1        | 0.34%   |
| Samsung Electronics SMXL2370HD SAM072B 1920x1080 510x287mm 23.0-inch    | 1        | 0.34%   |
| Samsung Electronics SMS19A450 SAM0848 1280x1024 376x301mm 19.0-inch     | 1        | 0.34%   |
| Samsung Electronics SMBX2235 SAM0700 1920x1080 477x268mm 21.5-inch      | 1        | 0.34%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch      | 1        | 0.34%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch   | 1        | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.34%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.34%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch       | 1        | 0.34%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch       | 1        | 0.34%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch       | 1        | 0.34%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch       | 1        | 0.34%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                    | 1        | 0.34%   |
| Samsung Electronics LCD Monitor SyncMaster 3600x1200                    | 1        | 0.34%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch   | 1        | 0.34%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch | 1        | 0.34%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 0.34%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch    | 1        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 115      | 41.97%  |
| 1280x1024 (SXGA)   | 28       | 10.22%  |
| 1680x1050 (WSXGA+) | 23       | 8.39%   |
| 2560x1440 (QHD)    | 20       | 7.3%    |
| 3840x2160 (4K)     | 18       | 6.57%   |
| 1440x900 (WXGA+)   | 12       | 4.38%   |
| Unknown            | 11       | 4.01%   |
| 1920x1200 (WUXGA)  | 6        | 2.19%   |
| 1366x768 (WXGA)    | 6        | 2.19%   |
| 1600x900 (HD+)     | 5        | 1.82%   |
| 3840x1200          | 3        | 1.09%   |
| 3840x1080          | 3        | 1.09%   |
| 3440x1440          | 3        | 1.09%   |
| 1360x768           | 3        | 1.09%   |
| 1024x768 (XGA)     | 3        | 1.09%   |
| 1600x1200          | 2        | 0.73%   |
| 1400x1050          | 2        | 0.73%   |
| 6784x2160          | 1        | 0.36%   |
| 6400x1080          | 1        | 0.36%   |
| 5120x1080          | 1        | 0.36%   |
| 4240x1440          | 1        | 0.36%   |
| 3600x1200          | 1        | 0.36%   |
| 3200x1080          | 1        | 0.36%   |
| 2560x1080          | 1        | 0.36%   |
| 1921x1080          | 1        | 0.36%   |
| 1920x540           | 1        | 0.36%   |
| 1820x1023          | 1        | 0.36%   |
| 1280x720 (HD)      | 1        | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 39       | 14.39%  |
| 21      | 37       | 13.65%  |
| 24      | 30       | 11.07%  |
| 23      | 28       | 10.33%  |
| 27      | 24       | 8.86%   |
| 19      | 19       | 7.01%   |
| 22      | 16       | 5.9%    |
| 17      | 15       | 5.54%   |
| 20      | 12       | 4.43%   |
| 84      | 9        | 3.32%   |
| 31      | 9        | 3.32%   |
| 18      | 6        | 2.21%   |
| 34      | 4        | 1.48%   |
| 25      | 4        | 1.48%   |
| 72      | 2        | 0.74%   |
| 54      | 2        | 0.74%   |
| 40      | 2        | 0.74%   |
| 15      | 2        | 0.74%   |
| 12      | 2        | 0.74%   |
| 75      | 1        | 0.37%   |
| 65      | 1        | 0.37%   |
| 52      | 1        | 0.37%   |
| 46      | 1        | 0.37%   |
| 37      | 1        | 0.37%   |
| 33      | 1        | 0.37%   |
| 32      | 1        | 0.37%   |
| 28      | 1        | 0.37%   |
| 26      | 1        | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 80       | 29.74%  |
| 401-500     | 80       | 29.74%  |
| Unknown     | 39       | 14.5%   |
| 301-350     | 16       | 5.95%   |
| 601-700     | 15       | 5.58%   |
| 1501-2000   | 12       | 4.46%   |
| 351-400     | 11       | 4.09%   |
| 701-800     | 6        | 2.23%   |
| 1001-1500   | 5        | 1.86%   |
| 801-900     | 3        | 1.12%   |
| 201-300     | 2        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 138      | 54.76%  |
| 16/10   | 39       | 15.48%  |
| Unknown | 35       | 13.89%  |
| 5/4     | 24       | 9.52%   |
| 4/3     | 9        | 3.57%   |
| 21/9    | 4        | 1.59%   |
| 6/5     | 1        | 0.4%    |
| 32/9    | 1        | 0.4%    |
| 3/2     | 1        | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 87       | 32.95%  |
| 151-200        | 41       | 15.53%  |
| Unknown        | 39       | 14.77%  |
| 301-350        | 25       | 9.47%   |
| 141-150        | 18       | 6.82%   |
| More than 1000 | 16       | 6.06%   |
| 351-500        | 16       | 6.06%   |
| 251-300        | 14       | 5.3%    |
| 501-1000       | 4        | 1.52%   |
| 71-80          | 2        | 0.76%   |
| 101-110        | 2        | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 148      | 58.04%  |
| 101-120 | 47       | 18.43%  |
| Unknown | 39       | 15.29%  |
| 1-50    | 11       | 4.31%   |
| 121-160 | 7        | 2.75%   |
| 161-240 | 3        | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 214      | 80.15%  |
| 2     | 36       | 13.48%  |
| 0     | 14       | 5.24%   |
| 3     | 2        | 0.75%   |
| 4     | 1        | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 145      | 43.28%  |
| Intel                                 | 94       | 28.06%  |
| Qualcomm Atheros                      | 25       | 7.46%   |
| Nvidia                                | 15       | 4.48%   |
| Qualcomm Atheros Communications       | 9        | 2.69%   |
| Ralink Technology                     | 8        | 2.39%   |
| Broadcom                              | 7        | 2.09%   |
| TP-Link                               | 6        | 1.79%   |
| Broadcom Limited                      | 6        | 1.79%   |
| Marvell Technology Group              | 4        | 1.19%   |
| Sundance Technology Inc / IC Plus     | 3        | 0.9%    |
| Xiaomi                                | 2        | 0.6%    |
| Microsoft                             | 2        | 0.6%    |
| MediaTek                              | 2        | 0.6%    |
| Ralink                                | 1        | 0.3%    |
| Huawei Technologies                   | 1        | 0.3%    |
| Gemtek                                | 1        | 0.3%    |
| D-Link                                | 1        | 0.3%    |
| Chelsio Communications                | 1        | 0.3%    |
| Aquantia                              | 1        | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 106      | 29.36%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 16       | 4.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 13       | 3.6%    |
| Intel I211 Gigabit Network Connection                                                | 11       | 3.05%   |
| Intel Ethernet Connection (2) I219-V                                                 | 11       | 3.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 10       | 2.77%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 8        | 2.22%   |
| Nvidia MCP61 Ethernet                                                                | 8        | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 7        | 1.94%   |
| Intel Wi-Fi 6 AX200                                                                  | 7        | 1.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 6        | 1.66%   |
| Intel Ethernet Connection I217-LM                                                    | 6        | 1.66%   |
| Intel Ethernet Connection (7) I219-V                                                 | 6        | 1.66%   |
| Intel Ethernet Connection (2) I218-V                                                 | 6        | 1.66%   |
| Intel Ethernet Controller I225-V                                                     | 5        | 1.39%   |
| Intel 82579V Gigabit Network Connection                                              | 5        | 1.39%   |
| Intel Ethernet Connection I217-V                                                     | 4        | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 1.11%   |
| Intel 82567LM-3 Gigabit Network Connection                                           | 4        | 1.11%   |
| Intel 82566DM-2 Gigabit Network Connection                                           | 4        | 1.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 3        | 0.83%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY           | 3        | 0.83%   |
| Realtek RTL8187 Wireless Adapter                                                     | 3        | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 3        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                                      | 3        | 0.83%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                        | 3        | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 3        | 0.83%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                              | 3        | 0.83%   |
| Intel 82578DM Gigabit Network Connection                                             | 3        | 0.83%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                      | 3        | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                       | 2        | 0.55%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 2        | 0.55%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                      | 2        | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                      | 2        | 0.55%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                           | 2        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                            | 2        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                            | 2        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                             | 2        | 0.55%   |
| Nvidia MCP65 Ethernet                                                                | 2        | 0.55%   |
| Nvidia MCP55 Ethernet                                                                | 2        | 0.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 0.55%   |
| Intel 82574L Gigabit Network Connection                                              | 2        | 0.55%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                      | 2        | 0.55%   |
| TP-Link Archer T4U ver.3                                                             | 1        | 0.28%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1        | 0.28%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 1        | 0.28%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 0.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 0.28%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 1        | 0.28%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                                     | 1        | 0.28%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                | 1        | 0.28%   |
| Ralink RT2070 Wireless Adapter                                                       | 1        | 0.28%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 0.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                            | 1        | 0.28%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 0.28%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                           | 1        | 0.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 0.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 1        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 17       | 25.76%  |
| Realtek Semiconductor                 | 11       | 16.67%  |
| Qualcomm Atheros Communications       | 9        | 13.64%  |
| Ralink Technology                     | 8        | 12.12%  |
| TP-Link                               | 6        | 9.09%   |
| Qualcomm Atheros                      | 5        | 7.58%   |
| Broadcom                              | 3        | 4.55%   |
| Microsoft                             | 2        | 3.03%   |
| Ralink                                | 1        | 1.52%   |
| MediaTek                              | 1        | 1.52%   |
| Gemtek                                | 1        | 1.52%   |
| D-Link                                | 1        | 1.52%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                                        | 8        | 12.12%  |
| Intel Wi-Fi 6 AX200                                                                                    | 7        | 10.61%  |
| Intel Comet Lake PCH CNVi WiFi                                                                         | 4        | 6.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                           | 3        | 4.55%   |
| Realtek RTL8187 Wireless Adapter                                                                       | 3        | 4.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 3        | 4.55%   |
| Ralink MT7601U Wireless Adapter                                                                        | 3        | 4.55%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                                  | 2        | 3.03%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                                        | 2        | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                        | 2        | 3.03%   |
| TP-Link Archer T4U ver.3                                                                               | 1        | 1.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                        | 1        | 1.52%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                             | 1        | 1.52%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                                        | 1        | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 1        | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1        | 1.52%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                                  | 1        | 1.52%   |
| Ralink RT2070 Wireless Adapter                                                                         | 1        | 1.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 1.52%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287]                   | 1        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                       | 1        | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 1        | 1.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                         | 1        | 1.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                                       | 1        | 1.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                                | 1        | 1.52%   |
| Microsoft XBOX ACC                                                                                     | 1        | 1.52%   |
| Microsoft Wireless XBox Controller Dongle                                                              | 1        | 1.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                | 1        | 1.52%   |
| Intel Wireless-AC 9260                                                                                 | 1        | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                 | 1        | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                         | 1        | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 1        | 1.52%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                                      | 1        | 1.52%   |
| D-Link GO-USB-N150 N Adapter                                                                           | 1        | 1.52%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                                     | 1        | 1.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                                                        | 1        | 1.52%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                                                     | 1        | 1.52%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 1        | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 139      | 49.12%  |
| Intel                             | 87       | 30.74%  |
| Qualcomm Atheros                  | 20       | 7.07%   |
| Nvidia                            | 15       | 5.3%    |
| Broadcom Limited                  | 6        | 2.12%   |
| Marvell Technology Group          | 4        | 1.41%   |
| Broadcom                          | 4        | 1.41%   |
| Sundance Technology Inc / IC Plus | 3        | 1.06%   |
| Xiaomi                            | 2        | 0.71%   |
| Huawei Technologies               | 1        | 0.35%   |
| Chelsio Communications            | 1        | 0.35%   |
| Aquantia                          | 1        | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 106      | 36.05%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 16       | 5.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 13       | 4.42%   |
| Intel I211 Gigabit Network Connection                                      | 11       | 3.74%   |
| Intel Ethernet Connection (2) I219-V                                       | 11       | 3.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 10       | 3.4%    |
| Nvidia MCP61 Ethernet                                                      | 8        | 2.72%   |
| Realtek RTL8125 2.5GbE Controller                                          | 7        | 2.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 6        | 2.04%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 2.04%   |
| Intel Ethernet Connection (7) I219-V                                       | 6        | 2.04%   |
| Intel Ethernet Connection (2) I218-V                                       | 6        | 2.04%   |
| Intel Ethernet Controller I225-V                                           | 5        | 1.7%    |
| Intel 82579V Gigabit Network Connection                                    | 5        | 1.7%    |
| Intel Ethernet Connection I217-V                                           | 4        | 1.36%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 1.36%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 1.36%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 3        | 1.02%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 3        | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 1.02%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 3        | 1.02%   |
| Intel 82578DM Gigabit Network Connection                                   | 3        | 1.02%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express            | 3        | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.68%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 2        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 2        | 0.68%   |
| Nvidia MCP65 Ethernet                                                      | 2        | 0.68%   |
| Nvidia MCP55 Ethernet                                                      | 2        | 0.68%   |
| Intel 82574L Gigabit Network Connection                                    | 2        | 0.68%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.34%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.34%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1        | 0.34%   |
| Nvidia MCP67 Ethernet                                                      | 1        | 0.34%   |
| Nvidia MCP51 Ethernet Controller                                           | 1        | 0.34%   |
| Nvidia CK804 Ethernet Controller                                           | 1        | 0.34%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 1        | 0.34%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                          | 1        | 0.34%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.34%   |
| Intel Ethernet Connection (5) I219-LM                                      | 1        | 0.34%   |
| Intel 82573L Gigabit Ethernet Controller                                   | 1        | 0.34%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                         | 1        | 0.34%   |
| Intel 82567V-4 Gigabit Network Connection                                  | 1        | 0.34%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 1        | 0.34%   |
| Intel 82567LF-3 Gigabit Network Connection                                 | 1        | 0.34%   |
| Intel 82567LF-2 Gigabit Network Connection                                 | 1        | 0.34%   |
| Intel 82566DC-2 Gigabit Network Connection                                 | 1        | 0.34%   |
| Intel 82566DC Gigabit Network Connection                                   | 1        | 0.34%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1        | 0.34%   |
| Huawei COL-L29                                                             | 1        | 0.34%   |
| Chelsio T320 10GbE Dual Port Adapter                                       | 1        | 0.34%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 1        | 0.34%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1        | 0.34%   |
| Broadcom Limited NetXtreme II BCM5708 Gigabit Ethernet                     | 1        | 0.34%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 1        | 0.34%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express            | 1        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 258      | 80.37%  |
| WiFi     | 62       | 19.31%  |
| Modem    | 1        | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 228      | 88.37%  |
| WiFi     | 30       | 11.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 196      | 74.81%  |
| 2     | 56       | 21.37%  |
| 3     | 7        | 2.67%   |
| 5     | 1        | 0.38%   |
| 4     | 1        | 0.38%   |
| 0     | 1        | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 257      | 99.23%  |
| Yes  | 2        | 0.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 20       | 37.74%  |
| Intel                      | 17       | 32.08%  |
| Integrated System Solution | 5        | 9.43%   |
| Broadcom                   | 3        | 5.66%   |
| ASUSTek Computer           | 3        | 5.66%   |
| Realtek Semiconductor      | 2        | 3.77%   |
| MediaTek                   | 1        | 1.89%   |
| Lite-On Technology         | 1        | 1.89%   |
| IMC Networks               | 1        | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 20       | 37.74%  |
| Intel AX200 Bluetooth                                 | 7        | 13.21%  |
| Intel Bluetooth Device                                | 4        | 7.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 5.66%   |
| Integrated System Solution Bluetooth Device           | 3        | 5.66%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 2        | 3.77%   |
| Broadcom BCM2045 Bluetooth                            | 2        | 3.77%   |
| Realtek RTL8723B Bluetooth                            | 1        | 1.89%   |
| Realtek Bluetooth Radio                               | 1        | 1.89%   |
| MediaTek Wireless_Device                              | 1        | 1.89%   |
| Lite-On Bluetooth Device                              | 1        | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 1.89%   |
| Intel AX210 Bluetooth                                 | 1        | 1.89%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.89%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 1.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 1.89%   |
| ASUS Bluetooth Adapter                                | 1        | 1.89%   |
| ASUS BCM20702A0                                       | 1        | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 158      | 36.57%  |
| AMD                                  | 114      | 26.39%  |
| Nvidia                               | 101      | 23.38%  |
| C-Media Electronics                  | 14       | 3.24%   |
| Creative Labs                        | 9        | 2.08%   |
| GN Netcom                            | 4        | 0.93%   |
| Texas Instruments                    | 3        | 0.69%   |
| Plantronics                          | 3        | 0.69%   |
| Creative Technology                  | 3        | 0.69%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.46%   |
| Tenx Technology                      | 2        | 0.46%   |
| Logitech                             | 2        | 0.46%   |
| Generalplus Technology               | 2        | 0.46%   |
| BEHRINGER International              | 2        | 0.46%   |
| ASUSTek Computer                     | 2        | 0.46%   |
| VIA Technologies                     | 1        | 0.23%   |
| SteelSeries ApS                      | 1        | 0.23%   |
| Sennheiser Communications            | 1        | 0.23%   |
| Samson Technologies                  | 1        | 0.23%   |
| Razer USA                            | 1        | 0.23%   |
| NAD Electronics                      | 1        | 0.23%   |
| M-Audio                              | 1        | 0.23%   |
| FiiO Electronics Technology          | 1        | 0.23%   |
| Evolution Electronics                | 1        | 0.23%   |
| ESS Technology                       | 1        | 0.23%   |
| Corsair                              | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 29       | 5.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 21       | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20       | 3.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16       | 3.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 16       | 3.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16       | 3.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13       | 2.58%   |
| Intel 200 Series PCH HD Audio                                              | 13       | 2.58%   |
| AMD FCH Azalia Controller                                                  | 13       | 2.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 2.39%   |
| Nvidia GF119 HDMI Audio Controller                                         | 11       | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11       | 2.19%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 2.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 10       | 1.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 1.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 1.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 1.79%   |
| Nvidia MCP61 High Definition Audio                                         | 8        | 1.59%   |
| Nvidia High Definition Audio Controller                                    | 7        | 1.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.39%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.39%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 1.39%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 7        | 1.39%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 6        | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 0.99%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5        | 0.99%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 0.99%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 0.99%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.8%    |
| AMD Trinity HDMI Audio Controller                                          | 4        | 0.8%    |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 4        | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.6%    |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.6%    |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3        | 0.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.6%    |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 3        | 0.6%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 3        | 0.6%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 0.6%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 3        | 0.6%    |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 3        | 0.6%    |
| Thesycon Systemsoftware & Consulting E30                                   | 2        | 0.4%    |
| Tenx Technology USB AUDIO                                                  | 2        | 0.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.4%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.4%    |
| Nvidia MCP65 High Definition Audio                                         | 2        | 0.4%    |
| Nvidia MCP55 High Definition Audio                                         | 2        | 0.4%    |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.4%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.4%    |
| Intel Comet Lake PCH cAVS                                                  | 2        | 0.4%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.4%    |
| Intel Audio device                                                         | 2        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 34       | 22.37%  |
| Unknown             | 28       | 18.42%  |
| Corsair             | 17       | 11.18%  |
| Samsung Electronics | 12       | 7.89%   |
| A-DATA Technology   | 10       | 6.58%   |
| SK hynix            | 9        | 5.92%   |
| Micron Technology   | 9        | 5.92%   |
| Team                | 5        | 3.29%   |
| G.Skill             | 5        | 3.29%   |
| Crucial             | 5        | 3.29%   |
| Nanya Technology    | 4        | 2.63%   |
| Ramaxel Technology  | 2        | 1.32%   |
| pqi                 | 2        | 1.32%   |
| Goodram             | 2        | 1.32%   |
| Atermiter           | 2        | 1.32%   |
| Transcend           | 1        | 0.66%   |
| Thermaltake         | 1        | 0.66%   |
| Silicon Power       | 1        | 0.66%   |
| HBS                 | 1        | 0.66%   |
| Elpida              | 1        | 0.66%   |
| CSX                 | 1        | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 3        | 1.79%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 3        | 1.79%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2        | 1.19%   |
| Unknown RAM Module 4096MB DIMM SDRAM                         | 2        | 1.19%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 2        | 1.19%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 2        | 1.19%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s         | 2        | 1.19%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s       | 2        | 1.19%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s      | 2        | 1.19%   |
| Kingston RAM KHX3000C15/16GX 16384MB DIMM DDR4 3333MT/s      | 2        | 1.19%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 2        | 1.19%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s          | 2        | 1.19%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 2        | 1.19%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 2        | 1.19%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                     | 2        | 1.19%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1        | 0.6%    |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                    | 1        | 0.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1        | 0.6%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 1        | 0.6%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                 | 1        | 0.6%    |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s                  | 1        | 0.6%    |
| Unknown RAM Module 4096MB DIMM DDR2                          | 1        | 0.6%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                      | 1        | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1        | 0.6%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 0.6%    |
| Unknown RAM Module 256MB DIMM DDR 333MT/s                    | 1        | 0.6%    |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                  | 1        | 0.6%    |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                  | 1        | 0.6%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 1        | 0.6%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 1        | 0.6%    |
| Unknown RAM Module 1GB FB-DIMM DDR2 667MT/s                  | 1        | 0.6%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                     | 1        | 0.6%    |
| Unknown RAM Module 1GB DIMM 400MT/s                          | 1        | 0.6%    |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 1        | 0.6%    |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 1        | 0.6%    |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                  | 1        | 0.6%    |
| Unknown RAM Module 1024MB DIMM DDR2 57535MT/s                | 1        | 0.6%    |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                   | 1        | 0.6%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                       | 1        | 0.6%    |
| Unknown RAM CS4S2666D19161C 16GB SODIMM DDR4 2667MT/s        | 1        | 0.6%    |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s           | 1        | 0.6%    |
| Transcend RAM JM1333KLN-2G 2048MB DIMM DDR3 1333MT/s         | 1        | 0.6%    |
| Thermaltake RAM R009R432GX2-3600C18A 32GB DIMM DDR4 3600MT/s | 1        | 0.6%    |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s          | 1        | 0.6%    |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s          | 1        | 0.6%    |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s          | 1        | 0.6%    |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s           | 1        | 0.6%    |
| Team RAM Module 8GB DIMM DDR4 3200MT/s                       | 1        | 0.6%    |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                   | 1        | 0.6%    |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                   | 1        | 0.6%    |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                | 1        | 0.6%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 0.6%    |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.6%    |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM 2133MT/s              | 1        | 0.6%    |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB DIMM DDR4 2133MT/s        | 1        | 0.6%    |
| Silicon Power RAM DBLT4GN568S 4GB DIMM 1333MT/s              | 1        | 0.6%    |
| Samsung RAM Module 2048MB DIMM DDR3 1067MT/s                 | 1        | 0.6%    |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s         | 1        | 0.6%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 1        | 0.6%    |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 49       | 37.12%  |
| DDR3    | 48       | 36.36%  |
| DDR2    | 14       | 10.61%  |
| SDRAM   | 10       | 7.58%   |
| Unknown | 10       | 7.58%   |
| DDR     | 1        | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 123      | 96.09%  |
| SODIMM  | 3        | 2.34%   |
| RIMM    | 1        | 0.78%   |
| FB-DIMM | 1        | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 47       | 32.87%  |
| 8192  | 35       | 24.48%  |
| 2048  | 29       | 20.28%  |
| 16384 | 17       | 11.89%  |
| 1024  | 9        | 6.29%   |
| 32768 | 3        | 2.1%    |
| 512   | 2        | 1.4%    |
| 256   | 1        | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 27       | 18.88%  |
| 1333    | 20       | 13.99%  |
| 800     | 13       | 9.09%   |
| 3200    | 8        | 5.59%   |
| 2133    | 8        | 5.59%   |
| 3600    | 7        | 4.9%    |
| 2400    | 6        | 4.2%    |
| 2667    | 5        | 3.5%    |
| 1867    | 5        | 3.5%    |
| 3000    | 4        | 2.8%    |
| Unknown | 4        | 2.8%    |
| 3466    | 3        | 2.1%    |
| 2933    | 3        | 2.1%    |
| 667     | 3        | 2.1%    |
| 333     | 3        | 2.1%    |
| 3800    | 2        | 1.4%    |
| 3533    | 2        | 1.4%    |
| 3333    | 2        | 1.4%    |
| 2800    | 2        | 1.4%    |
| 1866    | 2        | 1.4%    |
| 1800    | 2        | 1.4%    |
| 57535   | 1        | 0.7%    |
| 3733    | 1        | 0.7%    |
| 3467    | 1        | 0.7%    |
| 3266    | 1        | 0.7%    |
| 3066    | 1        | 0.7%    |
| 2666    | 1        | 0.7%    |
| 2481    | 1        | 0.7%    |
| 2000    | 1        | 0.7%    |
| 1639    | 1        | 0.7%    |
| 1067    | 1        | 0.7%    |
| 533     | 1        | 0.7%    |
| 400     | 1        | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 46.15%  |
| Brother Industries  | 3        | 23.08%  |
| Xerox               | 1        | 7.69%   |
| Samsung Electronics | 1        | 7.69%   |
| Kyocera             | 1        | 7.69%   |
| ATEN International  | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| HP LaserJet 1020                         | 2        | 15.38%  |
| Xerox Phaser 3020                        | 1        | 7.69%   |
| Samsung ML-2010P Mono Laser Printer      | 1        | 7.69%   |
| Kyocera ECOSYS P2040dn                   | 1        | 7.69%   |
| HP LaserJet Professional P1566           | 1        | 7.69%   |
| HP LaserJet P1102                        | 1        | 7.69%   |
| HP LaserJet 4350                         | 1        | 7.69%   |
| HP DeskJet 4530 series                   | 1        | 7.69%   |
| Brother Printer                          | 1        | 7.69%   |
| Brother MFC-B7715DW series               | 1        | 7.69%   |
| Brother DCP-T300                         | 1        | 7.69%   |
| ATEN International UC-1284B Printer Port | 1        | 7.69%   |

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


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 50%     |
| Canon CanoScan LiDE 110            | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 6        | 15%     |
| Microdia                | 6        | 15%     |
| Logitech                | 6        | 15%     |
| Microsoft               | 5        | 12.5%   |
| Creative Technology     | 2        | 5%      |
| Unknown                 | 1        | 2.5%    |
| Suyin                   | 1        | 2.5%    |
| Silicon Motion          | 1        | 2.5%    |
| Samsung Electronics     | 1        | 2.5%    |
| Razer USA               | 1        | 2.5%    |
| Pixart Imaging          | 1        | 2.5%    |
| Hewlett-Packard         | 1        | 2.5%    |
| Google                  | 1        | 2.5%    |
| Genesys Logic           | 1        | 2.5%    |
| Generalplus Technology  | 1        | 2.5%    |
| GEMBIRD                 | 1        | 2.5%    |
| Divio                   | 1        | 2.5%    |
| Chicony Electronics     | 1        | 2.5%    |
| Apple                   | 1        | 2.5%    |
| Alcor Micro             | 1        | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Z-Star A4 TECH HD PC Camera                 | 3        | 7.5%    |
| Microdia Camera                             | 3        | 7.5%    |
| Z-Star Venus USB2.0 Camera                  | 2        | 5%      |
| Microsoft LifeCam HD-3000                   | 2        | 5%      |
| Logitech Webcam C170                        | 2        | 5%      |
| Z-Star Vega USB 2.0 Camera                  | 1        | 2.5%    |
| Unknown HD camera                           | 1        | 2.5%    |
| Suyin Acer/HP Integrated Webcam [CN0314]    | 1        | 2.5%    |
| Silicon Motion Silicon Motion Camera        | 1        | 2.5%    |
| Samsung Galaxy series, misc. (MTP mode)     | 1        | 2.5%    |
| Razer USA Gaming Webcam [Kiyo]              | 1        | 2.5%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro        | 1        | 2.5%    |
| Microsoft MicrosoftÃ‚ LifeCam HD-5001    | 1        | 2.5%    |
| Microsoft LifeCam VX-500 [1357]             | 1        | 2.5%    |
| Microsoft LifeCam Studio                    | 1        | 2.5%    |
| Microdia USB 2.0 Camera                     | 1        | 2.5%    |
| Microdia Sonix USB 2.0 Camera               | 1        | 2.5%    |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 2.5%    |
| Logitech Webcam Pro 9000                    | 1        | 2.5%    |
| Logitech Webcam C300                        | 1        | 2.5%    |
| Logitech Webcam C270                        | 1        | 2.5%    |
| Logitech HD Webcam C615                     | 1        | 2.5%    |
| HP Webcam 1300                              | 1        | 2.5%    |
| Google Nexus/Pixel Device (MTP + debug)     | 1        | 2.5%    |
| Genesys Logic Camera                        | 1        | 2.5%    |
| Generalplus 808 Camera                      | 1        | 2.5%    |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 2.5%    |
| Divio ProLink DS3303u Webcam                | 1        | 2.5%    |
| Creative Live! Cam Sync HD [VF0770]         | 1        | 2.5%    |
| Creative Live! Cam Chat HD [VF0700]         | 1        | 2.5%    |
| Chicony HP 720p HD Monitor Webcam           | 1        | 2.5%    |
| Apple iPhone 5/5C/5S/6/SE                   | 1        | 2.5%    |
| Alcor Micro USB 2.0 PC Camera               | 1        | 2.5%    |

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
| OmniKey               | 2        | 66.67%  |
| Advanced Card Systems | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121                  | 2        | 66.67%  |
| Advanced Card Systems ACR38 SmartCard Reader | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 225      | 86.21%  |
| 1     | 33       | 12.64%  |
| 2     | 2        | 0.77%   |
| 3     | 1        | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 34.21%  |
| Unassigned class         | 8        | 21.05%  |
| Net/wireless             | 3        | 7.89%   |
| Communication controller | 3        | 7.89%   |
| Camera                   | 3        | 7.89%   |
| Net/ethernet             | 2        | 5.26%   |
| Card reader              | 2        | 5.26%   |
| Storage/ata              | 1        | 2.63%   |
| Sound                    | 1        | 2.63%   |
| Multimedia controller    | 1        | 2.63%   |
| Chipcard                 | 1        | 2.63%   |

