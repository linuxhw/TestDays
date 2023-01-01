Linux in Denmark - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

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

Total: 399

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME Z390-A                | [da48bed048](https://linux-hardware.org/?probe=da48bed048) | Dec 24, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [e964534175](https://linux-hardware.org/?probe=e964534175) | Dec 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d367461182](https://linux-hardware.org/?probe=d367461182) | Dec 19, 2022 |
| ASUSTek       | PRIME Z270-A                | [ea3dbee733](https://linux-hardware.org/?probe=ea3dbee733) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [441dc6d8a0](https://linux-hardware.org/?probe=441dc6d8a0) | Dec 13, 2022 |
| Gigabyte      | B650 GAMING X AX            | [2473215632](https://linux-hardware.org/?probe=2473215632) | Dec 10, 2022 |
| ASUSTek       | M80CJ-O                     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| Lenovo        | SHARKBAY NOK                | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [6b2389329d](https://linux-hardware.org/?probe=6b2389329d) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9282404406](https://linux-hardware.org/?probe=9282404406) | Nov 30, 2022 |
| ASUSTek       | PRIME TRX40-PRO             | [ecafbb7acb](https://linux-hardware.org/?probe=ecafbb7acb) | Nov 20, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [9b0f3f926d](https://linux-hardware.org/?probe=9b0f3f926d) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [1cc37489d5](https://linux-hardware.org/?probe=1cc37489d5) | Nov 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [ea05374336](https://linux-hardware.org/?probe=ea05374336) | Nov 19, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [de3eac26e1](https://linux-hardware.org/?probe=de3eac26e1) | Nov 18, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [07b8a83017](https://linux-hardware.org/?probe=07b8a83017) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [75ffcfaf88](https://linux-hardware.org/?probe=75ffcfaf88) | Nov 11, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [9a7d0e6d37](https://linux-hardware.org/?probe=9a7d0e6d37) | Nov 03, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [81a04d40a3](https://linux-hardware.org/?probe=81a04d40a3) | Nov 03, 2022 |
| Inventec      | DQ Class A02                | [f64d3223c5](https://linux-hardware.org/?probe=f64d3223c5) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | [c4fddde4b6](https://linux-hardware.org/?probe=c4fddde4b6) | Oct 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| Gigabyte      | 990FXA-UD5                  | [7c8d5609e0](https://linux-hardware.org/?probe=7c8d5609e0) | Sep 22, 2022 |
| Gigabyte      | EX58-UD4P                   | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [e55484acd4](https://linux-hardware.org/?probe=e55484acd4) | Sep 17, 2022 |
| Lenovo        | SDK0J40700 WIN              | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| MSI           | X570-A PRO                  | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte      | 990FXA-UD5                  | [e5364d8761](https://linux-hardware.org/?probe=e5364d8761) | Sep 01, 2022 |
| Unknown       | TB-4000                     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| ASUSTek       | SABERTOOTH X58              | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| Gigabyte      | P85-D3                      | [06b934d14f](https://linux-hardware.org/?probe=06b934d14f) | Aug 26, 2022 |
| Unknown       | TB-4000                     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Gigabyte      | B460M DS3H V2               | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| Unknown       | TB-4000                     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [0009de2dbb](https://linux-hardware.org/?probe=0009de2dbb) | Aug 11, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Lenovo        | SDK0J40700 WIN              | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| Lenovo        | SDK0J40700 WIN              | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| Gigabyte      | MJPLNAB-00                  | [d414e51a0c](https://linux-hardware.org/?probe=d414e51a0c) | Jul 23, 2022 |
| Gigabyte      | MJPLNAB-00                  | [9dcb499f3e](https://linux-hardware.org/?probe=9dcb499f3e) | Jul 23, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [a74834b383](https://linux-hardware.org/?probe=a74834b383) | Jul 04, 2022 |
| HP            | 805D                        | [3610332b9c](https://linux-hardware.org/?probe=3610332b9c) | Jul 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [c12aa3088a](https://linux-hardware.org/?probe=c12aa3088a) | Jun 30, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [b0c272ff93](https://linux-hardware.org/?probe=b0c272ff93) | Jun 26, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| ASUSTek       | H110I-PLUS                  | [36389b33b6](https://linux-hardware.org/?probe=36389b33b6) | Jun 12, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [d3fdbc7413](https://linux-hardware.org/?probe=d3fdbc7413) | Jun 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a307c95089](https://linux-hardware.org/?probe=a307c95089) | Jun 08, 2022 |
| Unknown       | TB-4000                     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| BESSTAR Te... | HM90                        | [5272429aa9](https://linux-hardware.org/?probe=5272429aa9) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| MSI           | 970A-G43                    | [92dd93dd78](https://linux-hardware.org/?probe=92dd93dd78) | May 24, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [bc9270aeff](https://linux-hardware.org/?probe=bc9270aeff) | May 13, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [f0e5f896a4](https://linux-hardware.org/?probe=f0e5f896a4) | May 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Gigabyte      | G41M-Combo                  | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Unknown       | TB-4000                     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| MSI           | MS-1T11                     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [91aa85fff9](https://linux-hardware.org/?probe=91aa85fff9) | Apr 21, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [ddc3550f6b](https://linux-hardware.org/?probe=ddc3550f6b) | Apr 04, 2022 |
| ASRock        | X99 Extreme4                | [e29b4c30f1](https://linux-hardware.org/?probe=e29b4c30f1) | Apr 04, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| ASUSTek       | PRIME Z370-P                | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [4ce05dd1e2](https://linux-hardware.org/?probe=4ce05dd1e2) | Mar 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f3b52d9201](https://linux-hardware.org/?probe=f3b52d9201) | Mar 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5c40bf9192](https://linux-hardware.org/?probe=5c40bf9192) | Mar 21, 2022 |
| ASUSTek       | PRIME B250M-A               | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Gigabyte      | MFLP7IP-00                  | [304c5939e7](https://linux-hardware.org/?probe=304c5939e7) | Mar 18, 2022 |
| Shuttle       | X50V2PLUS V1.00             | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| ASUSTek       | PRIME A320M-K               | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [04e8e7704e](https://linux-hardware.org/?probe=04e8e7704e) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c1929d8540](https://linux-hardware.org/?probe=c1929d8540) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [bdc86d995a](https://linux-hardware.org/?probe=bdc86d995a) | Feb 21, 2022 |
| Dell          | 0KC9NP A01                  | [f9a0fa24f8](https://linux-hardware.org/?probe=f9a0fa24f8) | Feb 18, 2022 |
| ASRock        | FM2A55M-DGS                 | [efe38992bd](https://linux-hardware.org/?probe=efe38992bd) | Feb 15, 2022 |
| Dell          | 0GTK4K A02                  | [466029e620](https://linux-hardware.org/?probe=466029e620) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e63f72d407](https://linux-hardware.org/?probe=e63f72d407) | Feb 07, 2022 |
| Medion        | MS-7800                     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [40ed6ce0c5](https://linux-hardware.org/?probe=40ed6ce0c5) | Feb 04, 2022 |
| Unknown       | TB-4000                     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [b8f4a15736](https://linux-hardware.org/?probe=b8f4a15736) | Jan 25, 2022 |
| ASUSTek       | P8H67-M                     | [a69dd56657](https://linux-hardware.org/?probe=a69dd56657) | Jan 21, 2022 |
| Gigabyte      | B460M AORUS PRO             | [1e301a4129](https://linux-hardware.org/?probe=1e301a4129) | Jan 19, 2022 |
| Acer          | Predator G6-710             | [29bdcc72c9](https://linux-hardware.org/?probe=29bdcc72c9) | Jan 18, 2022 |
| ASUSTek       | P8H67-M                     | [1568252a07](https://linux-hardware.org/?probe=1568252a07) | Jan 17, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | [46932917d4](https://linux-hardware.org/?probe=46932917d4) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| MSI           | A68HM GRENADE               | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| MSI           | X470 GAMING PRO             | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [1e14543dfd](https://linux-hardware.org/?probe=1e14543dfd) | Dec 18, 2021 |
| HP            | 3031h                       | [8a8888c824](https://linux-hardware.org/?probe=8a8888c824) | Dec 17, 2021 |
| ABIT          | I-G31                       | [048b7bcf6a](https://linux-hardware.org/?probe=048b7bcf6a) | Dec 13, 2021 |
| Dell          | 0YXT71 A01                  | [fbe4f7fdb9](https://linux-hardware.org/?probe=fbe4f7fdb9) | Dec 12, 2021 |
| ASUSTek       | Z170-P                      | [6e857bc210](https://linux-hardware.org/?probe=6e857bc210) | Dec 09, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [ac173fd5ba](https://linux-hardware.org/?probe=ac173fd5ba) | Dec 09, 2021 |
| ASUSTek       | PRIME Z390-A                | [e884cd44db](https://linux-hardware.org/?probe=e884cd44db) | Dec 08, 2021 |
| HP            | 3031h                       | [68cf960e7f](https://linux-hardware.org/?probe=68cf960e7f) | Dec 02, 2021 |
| HP            | 3031h                       | [1c49cd6404](https://linux-hardware.org/?probe=1c49cd6404) | Dec 02, 2021 |
| HP            | 8299                        | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| HP            | 8299                        | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6071fde7dd](https://linux-hardware.org/?probe=6071fde7dd) | Nov 28, 2021 |
| Acer          | Aspire X3995                | [cde003006d](https://linux-hardware.org/?probe=cde003006d) | Nov 22, 2021 |
| Acer          | Aspire X3995                | [2e97d6ef1c](https://linux-hardware.org/?probe=2e97d6ef1c) | Nov 22, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [ea4842466c](https://linux-hardware.org/?probe=ea4842466c) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [faf9e68f7a](https://linux-hardware.org/?probe=faf9e68f7a) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [2b2ea53377](https://linux-hardware.org/?probe=2b2ea53377) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [b4512f4b54](https://linux-hardware.org/?probe=b4512f4b54) | Nov 18, 2021 |
| ASRock        | Z170 Gaming K4              | [53281d6c95](https://linux-hardware.org/?probe=53281d6c95) | Nov 17, 2021 |
| Dell          | 0YXT71 A01                  | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| T-bao         | MINI PC V1.0                | [72ce248d0c](https://linux-hardware.org/?probe=72ce248d0c) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [be8c7e44de](https://linux-hardware.org/?probe=be8c7e44de) | Oct 23, 2021 |
| MSI           | Z77A-G45                    | [7a31ca9e22](https://linux-hardware.org/?probe=7a31ca9e22) | Oct 23, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [e1ddc26c5e](https://linux-hardware.org/?probe=e1ddc26c5e) | Oct 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [c0c2de7d52](https://linux-hardware.org/?probe=c0c2de7d52) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [56f27fef6e](https://linux-hardware.org/?probe=56f27fef6e) | Oct 16, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [a36474b9ff](https://linux-hardware.org/?probe=a36474b9ff) | Oct 04, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASRock        | H470M-ITX/ac                | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [201176552b](https://linux-hardware.org/?probe=201176552b) | Sep 21, 2021 |
| Medion        | B360H4-EM V1.0              | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Dell          | 0XCR8D A02                  | [9cb5ea4f4a](https://linux-hardware.org/?probe=9cb5ea4f4a) | Sep 11, 2021 |
| ASRock        | P55M Pro                    | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASRock        | 980DE3/U3S3                 | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| Medion        | MS-7616                     | [cbd20c24d8](https://linux-hardware.org/?probe=cbd20c24d8) | Aug 20, 2021 |
| HP            | 212B                        | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| ASUSTek       | P8B75-M                     | [4d29ffa0f7](https://linux-hardware.org/?probe=4d29ffa0f7) | Aug 03, 2021 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [4135f29492](https://linux-hardware.org/?probe=4135f29492) | Aug 02, 2021 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [59cd9e3edd](https://linux-hardware.org/?probe=59cd9e3edd) | Aug 01, 2021 |
| Pegatron      | 2AB6                        | [79dffb5346](https://linux-hardware.org/?probe=79dffb5346) | Jul 31, 2021 |
| Gigabyte      | P85-D3                      | [51f83ebd4a](https://linux-hardware.org/?probe=51f83ebd4a) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Lenovo        | ThinkCentre Edge71 1577G... | [cf7f13e31c](https://linux-hardware.org/?probe=cf7f13e31c) | Jul 29, 2021 |
| ASRock        | H310CM-DVS                  | [5ae2994458](https://linux-hardware.org/?probe=5ae2994458) | Jul 28, 2021 |
| Medion        | Z370H4-EM                   | [f19570a630](https://linux-hardware.org/?probe=f19570a630) | Jul 24, 2021 |
| Shuttle       | FH67                        | [611a7c28dc](https://linux-hardware.org/?probe=611a7c28dc) | Jul 22, 2021 |
| Shuttle       | FH67                        | [3d3fb6c381](https://linux-hardware.org/?probe=3d3fb6c381) | Jul 22, 2021 |
| ASRock        | 980DE3/U3S3                 | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5fcfefa75a](https://linux-hardware.org/?probe=5fcfefa75a) | Jul 19, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [0c0d9cc784](https://linux-hardware.org/?probe=0c0d9cc784) | Jul 15, 2021 |
| ASUSTek       | PRIME Z370-A                | [208a9ee715](https://linux-hardware.org/?probe=208a9ee715) | Jun 23, 2021 |
| ASUSTek       | PRIME Z370-A                | [86fce52939](https://linux-hardware.org/?probe=86fce52939) | Jun 23, 2021 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [ca43a33e1d](https://linux-hardware.org/?probe=ca43a33e1d) | Jun 18, 2021 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [4a0a83693b](https://linux-hardware.org/?probe=4a0a83693b) | Jun 14, 2021 |
| ASRock        | P55M Pro                    | [cac3198045](https://linux-hardware.org/?probe=cac3198045) | Jun 14, 2021 |
| HP            | 212B                        | [b72ab2aea5](https://linux-hardware.org/?probe=b72ab2aea5) | Jun 09, 2021 |
| ASRock        | P55M Pro                    | [b994c1917a](https://linux-hardware.org/?probe=b994c1917a) | Jun 03, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| MSI           | Z87 MPOWER                  | [848def4822](https://linux-hardware.org/?probe=848def4822) | May 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [e0217f85a6](https://linux-hardware.org/?probe=e0217f85a6) | May 28, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [f9358acedf](https://linux-hardware.org/?probe=f9358acedf) | May 27, 2021 |
| ASUSTek       | PRIME B450M-A               | [787c1b3a8c](https://linux-hardware.org/?probe=787c1b3a8c) | May 26, 2021 |
| ASUSTek       | B85M-G                      | [92f19ca1e6](https://linux-hardware.org/?probe=92f19ca1e6) | May 25, 2021 |
| ASUSTek       | NARRA2                      | [0b2cf24d70](https://linux-hardware.org/?probe=0b2cf24d70) | May 25, 2021 |
| Medion        | MS-7646                     | [799be90f9c](https://linux-hardware.org/?probe=799be90f9c) | May 11, 2021 |
| ASRock        | J4105-ITX                   | [2cb8135a58](https://linux-hardware.org/?probe=2cb8135a58) | May 08, 2021 |
| ASUSTek       | PRIME B450M-K               | [a8271c73ee](https://linux-hardware.org/?probe=a8271c73ee) | May 02, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [9e0202e76a](https://linux-hardware.org/?probe=9e0202e76a) | Apr 27, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [31cb6e83ed](https://linux-hardware.org/?probe=31cb6e83ed) | Apr 19, 2021 |
| Acer          | Veriton M275                | [246a662951](https://linux-hardware.org/?probe=246a662951) | Apr 17, 2021 |
| Gigabyte      | B75M-D3H                    | [cd772af567](https://linux-hardware.org/?probe=cd772af567) | Apr 14, 2021 |
| Gigabyte      | EP35-DS4                    | [e37cf6fc8d](https://linux-hardware.org/?probe=e37cf6fc8d) | Apr 12, 2021 |
| MSI           | Z87 MPOWER                  | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09cf1ed052](https://linux-hardware.org/?probe=09cf1ed052) | Apr 08, 2021 |
| ASRock        | Z270 Pro4                   | [b90dd1b4d2](https://linux-hardware.org/?probe=b90dd1b4d2) | Apr 02, 2021 |
| Medion        | MS-7797                     | [947bc894eb](https://linux-hardware.org/?probe=947bc894eb) | Apr 01, 2021 |
| ASUSTek       | PRIME Z370-A                | [757d1d0707](https://linux-hardware.org/?probe=757d1d0707) | Mar 31, 2021 |
| ASUSTek       | PRIME Z370-A                | [eb1782ad49](https://linux-hardware.org/?probe=eb1782ad49) | Mar 31, 2021 |
| Dell          | 0CU409                      | [53a8c28aed](https://linux-hardware.org/?probe=53a8c28aed) | Mar 24, 2021 |
| Acer          | Aspire XC-605               | [f8ad366bd9](https://linux-hardware.org/?probe=f8ad366bd9) | Mar 19, 2021 |
| ASUSTek       | PRIME X470-PRO              | [54288c23c9](https://linux-hardware.org/?probe=54288c23c9) | Mar 18, 2021 |
| ECS           | Nettle3                     | [f7ec16d7e7](https://linux-hardware.org/?probe=f7ec16d7e7) | Mar 16, 2021 |
| HP            | 3032h                       | [79b0bf2416](https://linux-hardware.org/?probe=79b0bf2416) | Mar 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [9ebf280981](https://linux-hardware.org/?probe=9ebf280981) | Mar 05, 2021 |
| Gigabyte      | A320M-S2H-CF                | [efa91095ab](https://linux-hardware.org/?probe=efa91095ab) | Mar 05, 2021 |
| ASUSTek       | M4N75TD                     | [9daf1b6529](https://linux-hardware.org/?probe=9daf1b6529) | Feb 28, 2021 |
| ASUSTek       | P5P43TD                     | [3a2604a18a](https://linux-hardware.org/?probe=3a2604a18a) | Feb 27, 2021 |
| HP            | 1998                        | [43bd925171](https://linux-hardware.org/?probe=43bd925171) | Feb 27, 2021 |
| ASUSTek       | PRIME Z270-A                | [66ce820cff](https://linux-hardware.org/?probe=66ce820cff) | Feb 25, 2021 |
| ASRock        | QC5000-ITX/WiFi             | [d321b1eb90](https://linux-hardware.org/?probe=d321b1eb90) | Feb 21, 2021 |
| ASRock        | Z270 Pro4                   | [7114de29ed](https://linux-hardware.org/?probe=7114de29ed) | Feb 20, 2021 |
| Medion        | MS-7797                     | [3c4d9332e4](https://linux-hardware.org/?probe=3c4d9332e4) | Feb 19, 2021 |
| MSI           | B150M PRO-VH                | [255e61b850](https://linux-hardware.org/?probe=255e61b850) | Feb 13, 2021 |
| Medion        | MS-7797                     | [7e6811c842](https://linux-hardware.org/?probe=7e6811c842) | Feb 10, 2021 |
| Medion        | MS-7797                     | [394c3c87f4](https://linux-hardware.org/?probe=394c3c87f4) | Feb 10, 2021 |
| ASRock        | B550M-ITX/ac                | [909d040ae4](https://linux-hardware.org/?probe=909d040ae4) | Feb 07, 2021 |
| Medion        | MS-7708                     | [53ba901c28](https://linux-hardware.org/?probe=53ba901c28) | Feb 01, 2021 |
| Medion        | MS-7708                     | [8ef1638192](https://linux-hardware.org/?probe=8ef1638192) | Feb 01, 2021 |
| Lenovo        | ThinkServer TS140           | [8f911a91ca](https://linux-hardware.org/?probe=8f911a91ca) | Jan 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [34257c05a5](https://linux-hardware.org/?probe=34257c05a5) | Jan 27, 2021 |
| Gigabyte      | GA-780T-D3L                 | [2f2ede94cb](https://linux-hardware.org/?probe=2f2ede94cb) | Jan 17, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [fc3f785613](https://linux-hardware.org/?probe=fc3f785613) | Jan 15, 2021 |
| NEXCOM        | NDIS B322                   | [c2789ca746](https://linux-hardware.org/?probe=c2789ca746) | Jan 06, 2021 |
| Gigabyte      | B550M DS3H                  | [16d30d3356](https://linux-hardware.org/?probe=16d30d3356) | Dec 30, 2020 |
| Gigabyte      | B550M DS3H                  | [944fc761f4](https://linux-hardware.org/?probe=944fc761f4) | Dec 30, 2020 |
| ASUSTek       | Z97-K                       | [3eacdc5965](https://linux-hardware.org/?probe=3eacdc5965) | Dec 28, 2020 |
| MSI           | B150M PRO-VH                | [f225de5ed7](https://linux-hardware.org/?probe=f225de5ed7) | Dec 25, 2020 |
| MSI           | B150M PRO-VH                | [6971a673ec](https://linux-hardware.org/?probe=6971a673ec) | Dec 25, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [13d6a7172d](https://linux-hardware.org/?probe=13d6a7172d) | Dec 15, 2020 |
| Gigabyte      | J3455N-D3H                  | [a9a1ba9727](https://linux-hardware.org/?probe=a9a1ba9727) | Dec 13, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [968983910f](https://linux-hardware.org/?probe=968983910f) | Dec 08, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [b3c78e0e70](https://linux-hardware.org/?probe=b3c78e0e70) | Dec 07, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [1a5eee726d](https://linux-hardware.org/?probe=1a5eee726d) | Dec 05, 2020 |
| MSI           | MPG Z490 GAMING PLUS        | [95b94bfe02](https://linux-hardware.org/?probe=95b94bfe02) | Dec 04, 2020 |
| MSI           | X570-A PRO                  | [0c57860179](https://linux-hardware.org/?probe=0c57860179) | Dec 02, 2020 |
| Medion        | B360H4-EM V1.0              | [718acb9fc0](https://linux-hardware.org/?probe=718acb9fc0) | Dec 02, 2020 |
| MSI           | B150M PRO-VH                | [ed280391f2](https://linux-hardware.org/?probe=ed280391f2) | Nov 30, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [f49b6c5048](https://linux-hardware.org/?probe=f49b6c5048) | Nov 27, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [ce4048d43f](https://linux-hardware.org/?probe=ce4048d43f) | Nov 24, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [9845e5eb1e](https://linux-hardware.org/?probe=9845e5eb1e) | Nov 15, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [91207c72e3](https://linux-hardware.org/?probe=91207c72e3) | Nov 15, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [d2afbbe9f9](https://linux-hardware.org/?probe=d2afbbe9f9) | Nov 10, 2020 |
| Lenovo        | ThinkCentre Edge72 3484F... | [8864ed7825](https://linux-hardware.org/?probe=8864ed7825) | Nov 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [54f14d0d27](https://linux-hardware.org/?probe=54f14d0d27) | Nov 02, 2020 |
| ASRock        | Z170 OC Formula             | [067d0719a1](https://linux-hardware.org/?probe=067d0719a1) | Oct 30, 2020 |
| ASRock        | TRX40 Creator               | [3b1961ec14](https://linux-hardware.org/?probe=3b1961ec14) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2e111f0b77](https://linux-hardware.org/?probe=2e111f0b77) | Oct 29, 2020 |
| Dell          | 0CT017                      | [4f36a920b3](https://linux-hardware.org/?probe=4f36a920b3) | Oct 26, 2020 |
| ASRock        | B450M Pro4                  | [375a230939](https://linux-hardware.org/?probe=375a230939) | Oct 26, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [97ae9ff8fd](https://linux-hardware.org/?probe=97ae9ff8fd) | Oct 16, 2020 |
| ASUSTek       | PRIME B250M-A               | [afee01c14d](https://linux-hardware.org/?probe=afee01c14d) | Oct 11, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [734e996f73](https://linux-hardware.org/?probe=734e996f73) | Oct 07, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ce1874a3be](https://linux-hardware.org/?probe=ce1874a3be) | Oct 07, 2020 |
| ASRock        | Z170 Extreme4               | [39a631ad3c](https://linux-hardware.org/?probe=39a631ad3c) | Oct 06, 2020 |
| Pegatron      | 2AD5                        | [4d341edca9](https://linux-hardware.org/?probe=4d341edca9) | Oct 05, 2020 |
| MSI           | Z87 MPOWER                  | [c361400ba5](https://linux-hardware.org/?probe=c361400ba5) | Oct 02, 2020 |
| HP            | 3398                        | [95d758781c](https://linux-hardware.org/?probe=95d758781c) | Oct 01, 2020 |
| ASUSTek       | Z170-DELUXE                 | [619ac1f764](https://linux-hardware.org/?probe=619ac1f764) | Sep 30, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09b275ac93](https://linux-hardware.org/?probe=09b275ac93) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS PRO              | [1fd3e30c8e](https://linux-hardware.org/?probe=1fd3e30c8e) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5032W3M     | [b6dc69bcc6](https://linux-hardware.org/?probe=b6dc69bcc6) | Sep 23, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [4298ad10c2](https://linux-hardware.org/?probe=4298ad10c2) | Sep 05, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [d98e57a21a](https://linux-hardware.org/?probe=d98e57a21a) | Sep 05, 2020 |
| Gigabyte      | X570 GAMING X               | [9cd1bda591](https://linux-hardware.org/?probe=9cd1bda591) | Sep 04, 2020 |
| Medion        | MS-7366                     | [ff7271711d](https://linux-hardware.org/?probe=ff7271711d) | Aug 25, 2020 |
| HP            | 2AFA                        | [b60453f85a](https://linux-hardware.org/?probe=b60453f85a) | Aug 23, 2020 |
| HP            | 2AFA                        | [4c206cac6d](https://linux-hardware.org/?probe=4c206cac6d) | Aug 22, 2020 |
| ASUSTek       | Z170-PRO                    | [7a14a06010](https://linux-hardware.org/?probe=7a14a06010) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [9ac43f513b](https://linux-hardware.org/?probe=9ac43f513b) | Aug 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [5c7a68d981](https://linux-hardware.org/?probe=5c7a68d981) | Aug 07, 2020 |
| Gigabyte      | Z77P-D3                     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| MSI           | B450 TOMAHAWK               | [c44d7421b8](https://linux-hardware.org/?probe=c44d7421b8) | Jul 24, 2020 |
| MSI           | X470 GAMING PRO             | [c12505e247](https://linux-hardware.org/?probe=c12505e247) | Jul 21, 2020 |
| MSI           | X470 GAMING PRO             | [ca1dac6b45](https://linux-hardware.org/?probe=ca1dac6b45) | Jul 21, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [861ca18aab](https://linux-hardware.org/?probe=861ca18aab) | Jul 16, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [ce07e0a768](https://linux-hardware.org/?probe=ce07e0a768) | Jul 14, 2020 |
| Lenovo        | ThinkCentre M58 7359WQR     | [73e0df5013](https://linux-hardware.org/?probe=73e0df5013) | Jul 09, 2020 |
| Gigabyte      | X570 UD                     | [ab1e04310e](https://linux-hardware.org/?probe=ab1e04310e) | Jul 07, 2020 |
| Gigabyte      | X570 UD                     | [319bbe63a2](https://linux-hardware.org/?probe=319bbe63a2) | Jul 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [1fa9af511a](https://linux-hardware.org/?probe=1fa9af511a) | Jul 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [57643353ce](https://linux-hardware.org/?probe=57643353ce) | Jun 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [9546ca8c2a](https://linux-hardware.org/?probe=9546ca8c2a) | Jun 29, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [b92d2bdb9d](https://linux-hardware.org/?probe=b92d2bdb9d) | Jun 28, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | [8f5fc60880](https://linux-hardware.org/?probe=8f5fc60880) | Jun 20, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [fdabb9483a](https://linux-hardware.org/?probe=fdabb9483a) | Jun 19, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | [bef7a799cc](https://linux-hardware.org/?probe=bef7a799cc) | Jun 18, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [415c3a4a20](https://linux-hardware.org/?probe=415c3a4a20) | Jun 18, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [1bd41519c5](https://linux-hardware.org/?probe=1bd41519c5) | Jun 13, 2020 |
| ASUSTek       | Maximus VIII HERO           | [3e632a857d](https://linux-hardware.org/?probe=3e632a857d) | Jun 06, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [c83816398c](https://linux-hardware.org/?probe=c83816398c) | Jun 05, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [82591ffa30](https://linux-hardware.org/?probe=82591ffa30) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [637d3d6ccc](https://linux-hardware.org/?probe=637d3d6ccc) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [bde3e045ca](https://linux-hardware.org/?probe=bde3e045ca) | May 31, 2020 |
| ASUSTek       | E45M1-I DELUXE              | [58f57667ee](https://linux-hardware.org/?probe=58f57667ee) | May 25, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [8ab04c0e95](https://linux-hardware.org/?probe=8ab04c0e95) | May 22, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a1a244d013](https://linux-hardware.org/?probe=a1a244d013) | May 21, 2020 |
| AMI           | Cherry Trail FFD            | [2646be2c9b](https://linux-hardware.org/?probe=2646be2c9b) | May 17, 2020 |
| AMI           | Cherry Trail FFD            | [1abe48ca91](https://linux-hardware.org/?probe=1abe48ca91) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | [aa8b123cdd](https://linux-hardware.org/?probe=aa8b123cdd) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | [c6f0fde0d2](https://linux-hardware.org/?probe=c6f0fde0d2) | May 16, 2020 |
| Gigabyte      | GA-870A-UD3                 | [9d150cc443](https://linux-hardware.org/?probe=9d150cc443) | May 16, 2020 |
| ASUSTek       | B85M-G                      | [f575cb11cb](https://linux-hardware.org/?probe=f575cb11cb) | May 08, 2020 |
| ASRock        | B450 Gaming K4              | [d82dc4eb4f](https://linux-hardware.org/?probe=d82dc4eb4f) | May 01, 2020 |
| ASRock        | B450 Gaming K4              | [c08ec23742](https://linux-hardware.org/?probe=c08ec23742) | May 01, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [3d3bc60c59](https://linux-hardware.org/?probe=3d3bc60c59) | Apr 28, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [ed1abce019](https://linux-hardware.org/?probe=ed1abce019) | Apr 23, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [0cbe6fdb9b](https://linux-hardware.org/?probe=0cbe6fdb9b) | Apr 21, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [61d4286e96](https://linux-hardware.org/?probe=61d4286e96) | Apr 06, 2020 |
| ECS           | Nettle3                     | [51538f1902](https://linux-hardware.org/?probe=51538f1902) | Apr 02, 2020 |
| ECS           | Nettle3                     | [5a8f6b27a0](https://linux-hardware.org/?probe=5a8f6b27a0) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [fee80882b4](https://linux-hardware.org/?probe=fee80882b4) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [309423fc5a](https://linux-hardware.org/?probe=309423fc5a) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [cc7be1cc44](https://linux-hardware.org/?probe=cc7be1cc44) | Apr 02, 2020 |
| Dell          | 0F373D A00                  | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [fbc59a267b](https://linux-hardware.org/?probe=fbc59a267b) | Mar 23, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [548b742928](https://linux-hardware.org/?probe=548b742928) | Mar 22, 2020 |
| HP            | ProLiant MicroServer        | [b8fc545d86](https://linux-hardware.org/?probe=b8fc545d86) | Mar 19, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [73276b8f74](https://linux-hardware.org/?probe=73276b8f74) | Mar 09, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [da8bd96ca5](https://linux-hardware.org/?probe=da8bd96ca5) | Mar 07, 2020 |
| ASUSTek       | Z97-A-USB31                 | [63b94ee87e](https://linux-hardware.org/?probe=63b94ee87e) | Mar 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | [da2608360d](https://linux-hardware.org/?probe=da2608360d) | Feb 23, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | [078b188645](https://linux-hardware.org/?probe=078b188645) | Feb 16, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | [700eabb523](https://linux-hardware.org/?probe=700eabb523) | Feb 15, 2020 |
| HP            | 86D3                        | [83613548dc](https://linux-hardware.org/?probe=83613548dc) | Feb 13, 2020 |
| Alienware     | 06G6JW A00                  | [f3eab06bb2](https://linux-hardware.org/?probe=f3eab06bb2) | Feb 10, 2020 |
| MSI           | Z97-G43                     | [01c2993ade](https://linux-hardware.org/?probe=01c2993ade) | Jan 25, 2020 |
| HP            | ProLiant ML350 G6           | [3472820868](https://linux-hardware.org/?probe=3472820868) | Jan 17, 2020 |
| HP            | ProLiant ML350 G6           | [86fb31ed72](https://linux-hardware.org/?probe=86fb31ed72) | Jan 16, 2020 |
| ASUSTek       | M4A88T-M                    | [643a92956a](https://linux-hardware.org/?probe=643a92956a) | Jan 13, 2020 |
| Gigabyte      | EG41M-US2H                  | [697f2f05e2](https://linux-hardware.org/?probe=697f2f05e2) | Jan 12, 2020 |
| eMachines     | ET1850                      | [7c1a93e022](https://linux-hardware.org/?probe=7c1a93e022) | Dec 23, 2019 |
| Gigabyte      | Z77P-D3                     | [3de82df337](https://linux-hardware.org/?probe=3de82df337) | Dec 17, 2019 |
| Gigabyte      | H61N-USB3                   | [ee74c9e54c](https://linux-hardware.org/?probe=ee74c9e54c) | Dec 12, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | [44e3d900f5](https://linux-hardware.org/?probe=44e3d900f5) | Dec 02, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ed930b473b](https://linux-hardware.org/?probe=ed930b473b) | Nov 24, 2019 |
| Gigabyte      | Z77P-D3                     | [e2bc0cfec5](https://linux-hardware.org/?probe=e2bc0cfec5) | Nov 24, 2019 |
| Gigabyte      | Z77P-D3                     | [53e0ab44e0](https://linux-hardware.org/?probe=53e0ab44e0) | Nov 23, 2019 |
| Gigabyte      | Z77P-D3                     | [9a1e3d5db9](https://linux-hardware.org/?probe=9a1e3d5db9) | Nov 23, 2019 |
| Packard Be... | IMEDIA L4880                | [a9a53bf7f4](https://linux-hardware.org/?probe=a9a53bf7f4) | Nov 18, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [0029decba2](https://linux-hardware.org/?probe=0029decba2) | Nov 08, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [6b013738c6](https://linux-hardware.org/?probe=6b013738c6) | Oct 24, 2019 |
| HP            | 3397                        | [27d2857bca](https://linux-hardware.org/?probe=27d2857bca) | Sep 30, 2019 |
| Gigabyte      | EG41M-US2H                  | [9717827455](https://linux-hardware.org/?probe=9717827455) | Sep 27, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [6298b19758](https://linux-hardware.org/?probe=6298b19758) | Sep 25, 2019 |
| ASUSTek       | PRIME Z370-A                | [6d7e7fdc51](https://linux-hardware.org/?probe=6d7e7fdc51) | Sep 23, 2019 |
| ASUSTek       | Z10PA-D8 Series             | [7436c74dcb](https://linux-hardware.org/?probe=7436c74dcb) | Sep 11, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [340c34926f](https://linux-hardware.org/?probe=340c34926f) | Aug 22, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [d1e5249043](https://linux-hardware.org/?probe=d1e5249043) | Aug 19, 2019 |
| ASRock        | HM65-MXM                    | [0d687e29cb](https://linux-hardware.org/?probe=0d687e29cb) | Aug 12, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [fbdbd66417](https://linux-hardware.org/?probe=fbdbd66417) | Aug 11, 2019 |
| Dell          | 06X1TJ A01                  | [faf781dda9](https://linux-hardware.org/?probe=faf781dda9) | Aug 05, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [2ed5b5afc5](https://linux-hardware.org/?probe=2ed5b5afc5) | Jul 21, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [aa7226b798](https://linux-hardware.org/?probe=aa7226b798) | Jul 21, 2019 |
| Lenovo        | ThinkCentre M81 5032W3M     | [cb4983baf6](https://linux-hardware.org/?probe=cb4983baf6) | Jul 18, 2019 |
| ASRock        | FM2A78M-HD+                 | [4c45eb1803](https://linux-hardware.org/?probe=4c45eb1803) | Jul 10, 2019 |
| Intel         | DH77EB AAG39073-304         | [08b86f6f4c](https://linux-hardware.org/?probe=08b86f6f4c) | Jul 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [706e1e0baf](https://linux-hardware.org/?probe=706e1e0baf) | Jun 30, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [11a091fb81](https://linux-hardware.org/?probe=11a091fb81) | Jun 22, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [8fc47ce184](https://linux-hardware.org/?probe=8fc47ce184) | Jun 15, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [7ba347026e](https://linux-hardware.org/?probe=7ba347026e) | Jun 13, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [3f7e0702b6](https://linux-hardware.org/?probe=3f7e0702b6) | Jun 12, 2019 |
| Dell          | 088DT1 A01                  | [5ea359299f](https://linux-hardware.org/?probe=5ea359299f) | Jun 11, 2019 |
| ASUSTek       | X99-A/USB                   | [d1e49be03d](https://linux-hardware.org/?probe=d1e49be03d) | Jun 11, 2019 |
| Gigabyte      | P85-D3                      | [16a7890585](https://linux-hardware.org/?probe=16a7890585) | Jun 09, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [9f8322e22a](https://linux-hardware.org/?probe=9f8322e22a) | Jun 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [0c0c2eca20](https://linux-hardware.org/?probe=0c0c2eca20) | Jun 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [3608798d1a](https://linux-hardware.org/?probe=3608798d1a) | May 24, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [e50d4d260b](https://linux-hardware.org/?probe=e50d4d260b) | May 23, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [1cbc7d5be7](https://linux-hardware.org/?probe=1cbc7d5be7) | May 16, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [cb3502a316](https://linux-hardware.org/?probe=cb3502a316) | May 09, 2019 |
| MSI           | B350 TOMAHAWK               | [3db9496e05](https://linux-hardware.org/?probe=3db9496e05) | May 08, 2019 |
| MSI           | B450 TOMAHAWK               | [0f966d6a2d](https://linux-hardware.org/?probe=0f966d6a2d) | May 08, 2019 |
| ASUSTek       | CROSSHAIR VI HERO           | [7653740066](https://linux-hardware.org/?probe=7653740066) | May 04, 2019 |
| HP            | 0A58h                       | [ec6b93d879](https://linux-hardware.org/?probe=ec6b93d879) | May 02, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [ca0ce2b4fc](https://linux-hardware.org/?probe=ca0ce2b4fc) | Apr 26, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [e08bb193b2](https://linux-hardware.org/?probe=e08bb193b2) | Apr 24, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [79831da7d2](https://linux-hardware.org/?probe=79831da7d2) | Apr 15, 2019 |
| Dell          | 04JGCK A02                  | [fd0e8a37d1](https://linux-hardware.org/?probe=fd0e8a37d1) | Apr 09, 2019 |
| ASRock        | 4Core1600Twins-P35          | [a5f4c15c85](https://linux-hardware.org/?probe=a5f4c15c85) | Apr 07, 2019 |
| ASUSTek       | P7P55D                      | [b25ec7e75a](https://linux-hardware.org/?probe=b25ec7e75a) | Mar 18, 2019 |
| Shuttle       | FN68S V10                   | [10121de278](https://linux-hardware.org/?probe=10121de278) | Mar 04, 2019 |
| Shuttle       | FN68S V10                   | [d15d7c5f21](https://linux-hardware.org/?probe=d15d7c5f21) | Mar 04, 2019 |
| ASRock        | 4Core1600Twins-P35          | [98b19f2fc7](https://linux-hardware.org/?probe=98b19f2fc7) | Feb 25, 2019 |
| ASRock        | Z77 Pro4                    | [08a0af469d](https://linux-hardware.org/?probe=08a0af469d) | Feb 20, 2019 |
| ASRock        | 4Core1600Twins-P35          | [e94ef5e02e](https://linux-hardware.org/?probe=e94ef5e02e) | Feb 16, 2019 |
| ASRock        | Z77 Pro4                    | [ba845b8712](https://linux-hardware.org/?probe=ba845b8712) | Feb 15, 2019 |
| ASRock        | Z77 Pro4                    | [e104fbc941](https://linux-hardware.org/?probe=e104fbc941) | Feb 14, 2019 |
| Acer          | FMCP7A-ION                  | [22a3849e3a](https://linux-hardware.org/?probe=22a3849e3a) | Dec 05, 2018 |
| Medion        | MS-7646                     | [cb720a4df0](https://linux-hardware.org/?probe=cb720a4df0) | Nov 25, 2018 |
| Medion        | MS-7713                     | [94a415c6c3](https://linux-hardware.org/?probe=94a415c6c3) | Nov 23, 2018 |
| Medion        | MS-7646                     | [7ff447b20e](https://linux-hardware.org/?probe=7ff447b20e) | Nov 22, 2018 |
| Lenovo        | 5025a26                     | [75a078fe71](https://linux-hardware.org/?probe=75a078fe71) | Nov 15, 2018 |
| ASUSTek       | PRIME Z370-P                | [89bfd874c0](https://linux-hardware.org/?probe=89bfd874c0) | Nov 03, 2018 |
| MSI           | B75MA-E31                   | [b1600ef31c](https://linux-hardware.org/?probe=b1600ef31c) | Nov 02, 2018 |
| ASUSTek       | H81M-P PLUS                 | [67c13bd391](https://linux-hardware.org/?probe=67c13bd391) | Oct 25, 2018 |
| Pegatron      | 2AB5                        | [85d0b75160](https://linux-hardware.org/?probe=85d0b75160) | Oct 24, 2018 |
| Pegatron      | 2AB5                        | [25cf879f80](https://linux-hardware.org/?probe=25cf879f80) | Oct 24, 2018 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f67b4afee6](https://linux-hardware.org/?probe=f67b4afee6) | Aug 11, 2018 |
| HP            | 82FE 11                     | [bd284d1c9d](https://linux-hardware.org/?probe=bd284d1c9d) | Dec 11, 2017 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [0f0a556912](https://linux-hardware.org/?probe=0f0a556912) | Jul 03, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 41       | 14.54%  |
| Ubuntu 18.04      | 30       | 10.64%  |
| OpenMandriva 4.2  | 13       | 4.61%   |
| Zorin 16          | 12       | 4.26%   |
| Arch Rolling      | 11       | 3.9%    |
| Pop!_OS 21.04     | 7        | 2.48%   |
| Manjaro           | 7        | 2.48%   |
| Linux Mint 20.2   | 7        | 2.48%   |
| Ubuntu 20.10      | 5        | 1.77%   |
| Ubuntu 19.04      | 5        | 1.77%   |
| Pop!_OS 20.10     | 5        | 1.77%   |
| OpenMandriva 4.3  | 5        | 1.77%   |
| Linux Mint 20.3   | 5        | 1.77%   |
| Linux Mint 20.1   | 5        | 1.77%   |
| Debian 11         | 5        | 1.77%   |
| Zorin 15          | 4        | 1.42%   |
| Ubuntu 22.04      | 4        | 1.42%   |
| Ubuntu 21.10      | 4        | 1.42%   |
| Pop!_OS 22.04     | 4        | 1.42%   |
| KDE neon 20.04    | 4        | 1.42%   |
| Ubuntu 22.10      | 3        | 1.06%   |
| Ubuntu 19.10      | 3        | 1.06%   |
| Pop!_OS 21.10     | 3        | 1.06%   |
| Linux Mint 20     | 3        | 1.06%   |
| Fedora 32         | 3        | 1.06%   |
| Debian 10         | 3        | 1.06%   |
| Ubuntu MATE 20.04 | 2        | 0.71%   |
| Ubuntu 16.04      | 2        | 0.71%   |
| Pop!_OS 20.04     | 2        | 0.71%   |
| Manjaro 21.2.0    | 2        | 0.71%   |
| Manjaro 20.0.3    | 2        | 0.71%   |
| Manjaro 20.0.1    | 2        | 0.71%   |
| Linux Mint 19.3   | 2        | 0.71%   |
| Linux Mint 19.2   | 2        | 0.71%   |
| Linux Mint 19.1   | 2        | 0.71%   |
| Kubuntu 20.04     | 2        | 0.71%   |
| Fedora 35         | 2        | 0.71%   |
| Fedora 34         | 2        | 0.71%   |
| Fedora 30         | 2        | 0.71%   |
| EndeavourOS       | 2        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 96       | 35.69%  |
| Linux Mint   | 27       | 10.04%  |
| Pop!_OS      | 21       | 7.81%   |
| OpenMandriva | 19       | 7.06%   |
| Zorin        | 16       | 5.95%   |
| Manjaro      | 16       | 5.95%   |
| Arch         | 13       | 4.83%   |
| Fedora       | 12       | 4.46%   |
| Debian       | 11       | 4.09%   |
| Kubuntu      | 5        | 1.86%   |
| KDE neon     | 5        | 1.86%   |
| ROSA         | 3        | 1.12%   |
| Gentoo       | 3        | 1.12%   |
| EndeavourOS  | 3        | 1.12%   |
| ArcoLinux    | 3        | 1.12%   |
| Ubuntu MATE  | 2        | 0.74%   |
| MX           | 2        | 0.74%   |
| Xubuntu      | 1        | 0.37%   |
| SteamOS      | 1        | 0.37%   |
| Solus        | 1        | 0.37%   |
| Parrot       | 1        | 0.37%   |
| openSUSE     | 1        | 0.37%   |
| NixOS        | 1        | 0.37%   |
| Lubuntu      | 1        | 0.37%   |
| Garuda Linux | 1        | 0.37%   |
| Endless      | 1        | 0.37%   |
| Elementary   | 1        | 0.37%   |
| BlackPanther | 1        | 0.37%   |
| Anarchy      | 1        | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 11       | 3.63%   |
| 5.4.0-52-generic         | 6        | 1.98%   |
| 5.16.7-desktop-1omv4003  | 5        | 1.65%   |
| 5.8.0-43-generic         | 4        | 1.32%   |
| 5.4.0-42-generic         | 4        | 1.32%   |
| 5.15.0-56-generic        | 4        | 1.32%   |
| 4.15.0-48-generic        | 4        | 1.32%   |
| 5.8.5-arch1-1            | 3        | 0.99%   |
| 5.4.0-91-generic         | 3        | 0.99%   |
| 5.4.0-90-generic         | 3        | 0.99%   |
| 5.4.0-73-generic         | 3        | 0.99%   |
| 5.4.0-58-generic         | 3        | 0.99%   |
| 5.4.0-29-generic         | 3        | 0.99%   |
| 5.3.0-28-generic         | 3        | 0.99%   |
| 5.15.0-46-generic        | 3        | 0.99%   |
| 5.15.0-41-generic        | 3        | 0.99%   |
| 5.13.0-28-generic        | 3        | 0.99%   |
| 5.11.12-desktop-1omv4002 | 3        | 0.99%   |
| 5.11.0-7620-generic      | 3        | 0.99%   |
| 5.11.0-37-generic        | 3        | 0.99%   |
| 5.11.0-27-generic        | 3        | 0.99%   |
| 5.0.0-13-generic         | 3        | 0.99%   |
| 4.15.0-45-generic        | 3        | 0.99%   |
| 5.8.0-7642-generic       | 2        | 0.66%   |
| 5.8.0-63-generic         | 2        | 0.66%   |
| 5.8.0-41-generic         | 2        | 0.66%   |
| 5.6.15-1-MANJARO         | 2        | 0.66%   |
| 5.6.12-1-MANJARO         | 2        | 0.66%   |
| 5.4.18-1-MANJARO         | 2        | 0.66%   |
| 5.4.0-88-generic         | 2        | 0.66%   |
| 5.4.0-80-generic         | 2        | 0.66%   |
| 5.4.0-70-generic         | 2        | 0.66%   |
| 5.4.0-53-generic         | 2        | 0.66%   |
| 5.4.0-48-generic         | 2        | 0.66%   |
| 5.4.0-26-generic         | 2        | 0.66%   |
| 5.3.0-46-generic         | 2        | 0.66%   |
| 5.3.0-26-generic         | 2        | 0.66%   |
| 5.19.0-76051900-generic  | 2        | 0.66%   |
| 5.13.12-200.fc34.x86_64  | 2        | 0.66%   |
| 5.13.0-7620-generic      | 2        | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 51       | 17.65%  |
| 4.15.0  | 28       | 9.69%   |
| 5.8.0   | 21       | 7.27%   |
| 5.13.0  | 19       | 6.57%   |
| 5.11.0  | 18       | 6.23%   |
| 5.15.0  | 13       | 4.5%    |
| 5.3.0   | 11       | 3.81%   |
| 5.10.14 | 11       | 3.81%   |
| 5.0.0   | 8        | 2.77%   |
| 5.10.0  | 6        | 2.08%   |
| 5.19.0  | 5        | 1.73%   |
| 5.16.7  | 5        | 1.73%   |
| 4.18.0  | 5        | 1.73%   |
| 4.19.0  | 4        | 1.38%   |
| 5.8.5   | 3        | 1.04%   |
| 5.6.15  | 3        | 1.04%   |
| 5.11.12 | 3        | 1.04%   |
| 5.9.1   | 2        | 0.69%   |
| 5.8.18  | 2        | 0.69%   |
| 5.6.12  | 2        | 0.69%   |
| 5.4.18  | 2        | 0.69%   |
| 5.19.5  | 2        | 0.69%   |
| 5.16.0  | 2        | 0.69%   |
| 5.13.12 | 2        | 0.69%   |
| 5.11.11 | 2        | 0.69%   |
| 6.0.9   | 1        | 0.35%   |
| 6.0.7   | 1        | 0.35%   |
| 6.0.6   | 1        | 0.35%   |
| 6.0.12  | 1        | 0.35%   |
| 5.9.0   | 1        | 0.35%   |
| 5.8.6   | 1        | 0.35%   |
| 5.8.4   | 1        | 0.35%   |
| 5.8.2   | 1        | 0.35%   |
| 5.8.12  | 1        | 0.35%   |
| 5.7.9   | 1        | 0.35%   |
| 5.7.8   | 1        | 0.35%   |
| 5.7.7   | 1        | 0.35%   |
| 5.7.6   | 1        | 0.35%   |
| 5.7.2   | 1        | 0.35%   |
| 5.7.0   | 1        | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 19.37%  |
| 5.8     | 30       | 10.56%  |
| 4.15    | 28       | 9.86%   |
| 5.11    | 25       | 8.8%    |
| 5.13    | 22       | 7.75%   |
| 5.15    | 21       | 7.39%   |
| 5.10    | 19       | 6.69%   |
| 5.3     | 11       | 3.87%   |
| 5.16    | 11       | 3.87%   |
| 5.19    | 8        | 2.82%   |
| 5.0     | 8        | 2.82%   |
| 5.6     | 7        | 2.46%   |
| 5.7     | 5        | 1.76%   |
| 4.19    | 5        | 1.76%   |
| 4.18    | 5        | 1.76%   |
| 6.0     | 4        | 1.41%   |
| 5.17    | 4        | 1.41%   |
| 5.9     | 3        | 1.06%   |
| 5.14    | 3        | 1.06%   |
| 4.9     | 3        | 1.06%   |
| 5.12    | 2        | 0.7%    |
| 5.1     | 2        | 0.7%    |
| 5.2     | 1        | 0.35%   |
| 5.18    | 1        | 0.35%   |
| 4.17    | 1        | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 255      | 98.84%  |
| i686   | 3        | 1.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 113      | 41.39%  |
| Unknown       | 54       | 19.78%  |
| KDE5          | 45       | 16.48%  |
| X-Cinnamon    | 22       | 8.06%   |
| XFCE          | 16       | 5.86%   |
| KDE           | 7        | 2.56%   |
| Cinnamon      | 4        | 1.47%   |
| MATE          | 3        | 1.1%    |
| KDE4          | 2        | 0.73%   |
| Pantheon      | 1        | 0.37%   |
| openbox       | 1        | 0.37%   |
| LXDE          | 1        | 0.37%   |
| i3            | 1        | 0.37%   |
| enlightenment | 1        | 0.37%   |
| Deepin        | 1        | 0.37%   |
| bspwm         | 1        | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 222      | 83.77%  |
| Unknown | 24       | 9.06%   |
| Wayland | 14       | 5.28%   |
| Tty     | 5        | 1.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 159      | 58.89%  |
| SDDM    | 40       | 14.81%  |
| GDM3    | 24       | 8.89%   |
| GDM     | 17       | 6.3%    |
| TDM     | 15       | 5.56%   |
| LightDM | 12       | 4.44%   |
| KDM     | 2        | 0.74%   |
| LXDM    | 1        | 0.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 93       | 34.96%  |
| da_DK      | 79       | 29.7%   |
| Unknown    | 42       | 15.79%  |
| en_DK      | 34       | 12.78%  |
| en_GB      | 5        | 1.88%   |
| ru_RU      | 2        | 0.75%   |
| de_DE      | 2        | 0.75%   |
| C          | 2        | 0.75%   |
| pl_PL      | 1        | 0.38%   |
| it_IT      | 1        | 0.38%   |
| io_001     | 1        | 0.38%   |
| es_ES      | 1        | 0.38%   |
| en_US.UTF8 | 1        | 0.38%   |
| en_IE      | 1        | 0.38%   |
| de_AT      | 1        | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 157      | 59.7%   |
| EFI  | 106      | 40.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 211      | 79.03%  |
| Overlay | 23       | 8.61%   |
| Btrfs   | 14       | 5.24%   |
| Unknown | 13       | 4.87%   |
| Zfs     | 3        | 1.12%   |
| Xfs     | 2        | 0.75%   |
| F2fs    | 1        | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 168      | 62.69%  |
| GPT     | 75       | 27.99%  |
| MBR     | 25       | 9.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 210      | 78.65%  |
| Yes       | 57       | 21.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 188      | 71.48%  |
| Yes       | 75       | 28.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 86       | 33.33%  |
| Gigabyte Technology | 42       | 16.28%  |
| MSI                 | 26       | 10.08%  |
| ASRock              | 22       | 8.53%   |
| Lenovo              | 20       | 7.75%   |
| Hewlett-Packard     | 15       | 5.81%   |
| Medion              | 11       | 4.26%   |
| Dell                | 10       | 3.88%   |
| Acer                | 6        | 2.33%   |
| Shuttle             | 3        | 1.16%   |
| Pegatron            | 3        | 1.16%   |
| Intel               | 2        | 0.78%   |
| T-bao               | 1        | 0.39%   |
| Packard Bell        | 1        | 0.39%   |
| NEXCOM              | 1        | 0.39%   |
| Inventec            | 1        | 0.39%   |
| Fujitsu             | 1        | 0.39%   |
| eMachines           | 1        | 0.39%   |
| ECS                 | 1        | 0.39%   |
| BESSTAR Tech        | 1        | 0.39%   |
| AMI                 | 1        | 0.39%   |
| Alienware           | 1        | 0.39%   |
| ABIT                | 1        | 0.39%   |
| Unknown             | 1        | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS ROG STRIX B450-E GAMING | 5        | 1.94%   |
| ASUS All Series              | 5        | 1.94%   |
| ASUS Z170 PRO GAMING         | 4        | 1.55%   |
| MSI MS-7C37                  | 3        | 1.16%   |
| Dell OptiPlex 9020           | 3        | 1.16%   |
| ASUS ROG STRIX B550-F GAMING | 3        | 1.16%   |
| MSI MS-7C02                  | 2        | 0.78%   |
| MSI MS-7B79                  | 2        | 0.78%   |
| Medion MS-7797               | 2        | 0.78%   |
| Medion MS-7646               | 2        | 0.78%   |
| Lenovo H30-05 90BJ00CNMT     | 2        | 0.78%   |
| Gigabyte X570 AORUS MASTER   | 2        | 0.78%   |
| Gigabyte P85-D3              | 2        | 0.78%   |
| ASUS TUF Gaming X570-PLUS    | 2        | 0.78%   |
| ASUS ROG STRIX X470-I GAMING | 2        | 0.78%   |
| ASUS PRIME Z390-A            | 2        | 0.78%   |
| ASUS PRIME Z370-P            | 2        | 0.78%   |
| ASUS PRIME Z370-A            | 2        | 0.78%   |
| ASUS PRIME B250M-A           | 2        | 0.78%   |
| ASUS M5A78L-M/USB3           | 2        | 0.78%   |
| ASUS CROSSHAIR VI HERO       | 2        | 0.78%   |
| T-bao MINI PC                | 1        | 0.39%   |
| Shuttle X50V2PLUS            | 1        | 0.39%   |
| Shuttle SN68S                | 1        | 0.39%   |
| Shuttle SH67H3               | 1        | 0.39%   |
| Pegatron HPE-532sc           | 1        | 0.39%   |
| Pegatron h8-1110sc           | 1        | 0.39%   |
| Pegatron 2AD5                | 1        | 0.39%   |
| Packard Bell IXTREME M5741   | 1        | 0.39%   |
| NEXCOM NDIS B322             | 1        | 0.39%   |
| MSI Vortex G65VR 6RE SLI     | 1        | 0.39%   |
| MSI MS-7C91                  | 1        | 0.39%   |
| MSI MS-7C83                  | 1        | 0.39%   |
| MSI MS-7C80                  | 1        | 0.39%   |
| MSI MS-7C75                  | 1        | 0.39%   |
| MSI MS-7C56                  | 1        | 0.39%   |
| MSI MS-7B86                  | 1        | 0.39%   |
| MSI MS-7B50                  | 1        | 0.39%   |
| MSI MS-7A40                  | 1        | 0.39%   |
| MSI MS-7A37                  | 1        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 21       | 8.14%   |
| ASUS PRIME           | 20       | 7.75%   |
| Lenovo ThinkCentre   | 10       | 3.88%   |
| Gigabyte X570        | 7        | 2.71%   |
| ASUS TUF             | 7        | 2.71%   |
| HP Compaq            | 5        | 1.94%   |
| Dell OptiPlex        | 5        | 1.94%   |
| ASUS All             | 5        | 1.94%   |
| ASUS Z170            | 4        | 1.55%   |
| MSI MS-7C37          | 3        | 1.16%   |
| Lenovo ThinkStation  | 3        | 1.16%   |
| ASUS SABERTOOTH      | 3        | 1.16%   |
| ASUS M5A78L-M        | 3        | 1.16%   |
| ASRock Z170          | 3        | 1.16%   |
| Acer Aspire          | 3        | 1.16%   |
| MSI MS-7C02          | 2        | 0.78%   |
| MSI MS-7B79          | 2        | 0.78%   |
| Medion MS-7797       | 2        | 0.78%   |
| Medion MS-7646       | 2        | 0.78%   |
| Lenovo H30-05        | 2        | 0.78%   |
| HP ProLiant          | 2        | 0.78%   |
| HP EliteDesk         | 2        | 0.78%   |
| Gigabyte Z390        | 2        | 0.78%   |
| Gigabyte P85-D3      | 2        | 0.78%   |
| Gigabyte B550        | 2        | 0.78%   |
| Gigabyte A320M-S2H   | 2        | 0.78%   |
| ASUS CROSSHAIR       | 2        | 0.78%   |
| ASRock Z77           | 2        | 0.78%   |
| ASRock B450          | 2        | 0.78%   |
| T-bao MINI           | 1        | 0.39%   |
| Shuttle X50V2PLUS    | 1        | 0.39%   |
| Shuttle SN68S        | 1        | 0.39%   |
| Shuttle SH67H3       | 1        | 0.39%   |
| Pegatron HPE-532sc   | 1        | 0.39%   |
| Pegatron h8-1110sc   | 1        | 0.39%   |
| Pegatron 2AD5        | 1        | 0.39%   |
| Packard Bell IXTREME | 1        | 0.39%   |
| NEXCOM NDIS          | 1        | 0.39%   |
| MSI Vortex           | 1        | 0.39%   |
| MSI MS-7C91          | 1        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 30       | 11.63%  |
| 2019 | 27       | 10.47%  |
| 2012 | 27       | 10.47%  |
| 2020 | 23       | 8.91%   |
| 2017 | 19       | 7.36%   |
| 2013 | 18       | 6.98%   |
| 2021 | 16       | 6.2%    |
| 2016 | 15       | 5.81%   |
| 2015 | 15       | 5.81%   |
| 2011 | 15       | 5.81%   |
| 2010 | 13       | 5.04%   |
| 2014 | 11       | 4.26%   |
| 2009 | 10       | 3.88%   |
| 2008 | 10       | 3.88%   |
| 2007 | 5        | 1.94%   |
| 2022 | 2        | 0.78%   |
| 2006 | 2        | 0.78%   |

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
| Disabled | 257      | 99.61%  |
| Enabled  | 1        | 0.39%   |

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
| 16.01-24.0      | 83       | 31.2%   |
| 32.01-64.0      | 54       | 20.3%   |
| 8.01-16.0       | 49       | 18.42%  |
| 3.01-4.0        | 27       | 10.15%  |
| 4.01-8.0        | 24       | 9.02%   |
| 64.01-256.0     | 14       | 5.26%   |
| 24.01-32.0      | 8        | 3.01%   |
| 1.01-2.0        | 4        | 1.5%    |
| 2.01-3.0        | 2        | 0.75%   |
| More than 256.0 | 1        | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 100      | 34.48%  |
| 2.01-3.0   | 70       | 24.14%  |
| 4.01-8.0   | 46       | 15.86%  |
| 3.01-4.0   | 44       | 15.17%  |
| 8.01-16.0  | 13       | 4.48%   |
| 0.51-1.0   | 10       | 3.45%   |
| 0.01-0.5   | 3        | 1.03%   |
| 24.01-32.0 | 2        | 0.69%   |
| 32.01-64.0 | 1        | 0.34%   |
| 16.01-24.0 | 1        | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 99       | 37.08%  |
| 2      | 61       | 22.85%  |
| 3      | 54       | 20.22%  |
| 4      | 26       | 9.74%   |
| 5      | 16       | 5.99%   |
| 6      | 5        | 1.87%   |
| 0      | 3        | 1.12%   |
| 9      | 1        | 0.37%   |
| 8      | 1        | 0.37%   |
| 7      | 1        | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 141      | 54.44%  |
| Yes       | 118      | 45.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 256      | 99.22%  |
| No        | 2        | 0.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 139      | 53.05%  |
| Yes       | 123      | 46.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 174      | 67.18%  |
| Yes       | 85       | 32.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Denmark | 258      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Copenhagen               | 63       | 23.77%  |
| Frederiksberg            | 15       | 5.66%   |
| Odense                   | 14       | 5.28%   |
| Aarhus                   | 10       | 3.77%   |
| Slagelse                 | 6        | 2.26%   |
| Silkeborg                | 6        | 2.26%   |
| Bronshoj                 | 6        | 2.26%   |
| Aabenraa                 | 6        | 2.26%   |
| Aalborg                  | 5        | 1.89%   |
| Vejle                    | 4        | 1.51%   |
| Roskilde                 | 4        | 1.51%   |
| Herlev                   | 4        | 1.51%   |
| Esbjerg                  | 4        | 1.51%   |
| Albertslund Municipality | 4        | 1.51%   |
| Svendborg                | 3        | 1.13%   |
| Rødovre Municipality    | 3        | 1.13%   |
| Nyborg                   | 3        | 1.13%   |
| Hvidovre                 | 3        | 1.13%   |
| Horsens                  | 3        | 1.13%   |
| Hjørring                | 3        | 1.13%   |
| Allinge                  | 3        | 1.13%   |
| Aabybro                  | 3        | 1.13%   |
| Viby J                   | 2        | 0.75%   |
| Valby                    | 2        | 0.75%   |
| Trige                    | 2        | 0.75%   |
| Taastrup                 | 2        | 0.75%   |
| Stovring                 | 2        | 0.75%   |
| Soborg                   | 2        | 0.75%   |
| Skanderborg              | 2        | 0.75%   |
| Risskov                  | 2        | 0.75%   |
| Kolding                  | 2        | 0.75%   |
| Kastrup                  | 2        | 0.75%   |
| Hundested                | 2        | 0.75%   |
| Glostrup Municipality    | 2        | 0.75%   |
| Gentofte Municipality    | 2        | 0.75%   |
| Fredericia               | 2        | 0.75%   |
| Charlottenlund           | 2        | 0.75%   |
| Aars                     | 2        | 0.75%   |
| Vordingborg              | 1        | 0.38%   |
| Virum                    | 1        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 94       | 170    | 19.22%  |
| Seagate                   | 88       | 127    | 18%     |
| WDC                       | 80       | 136    | 16.36%  |
| Kingston                  | 47       | 66     | 9.61%   |
| Crucial                   | 23       | 32     | 4.7%    |
| Toshiba                   | 20       | 26     | 4.09%   |
| SanDisk                   | 20       | 25     | 4.09%   |
| Intel                     | 13       | 15     | 2.66%   |
| Hitachi                   | 10       | 14     | 2.04%   |
| Corsair                   | 8        | 11     | 1.64%   |
| Phison                    | 7        | 10     | 1.43%   |
| Unknown                   | 6        | 7      | 1.23%   |
| Intenso                   | 6        | 9      | 1.23%   |
| A-DATA Technology         | 5        | 5      | 1.02%   |
| SK hynix                  | 4        | 4      | 0.82%   |
| PNY                       | 4        | 4      | 0.82%   |
| OCZ                       | 4        | 4      | 0.82%   |
| Phison Electronics        | 3        | 5      | 0.61%   |
| Micron Technology         | 3        | 4      | 0.61%   |
| JMicron Technology        | 3        | 3      | 0.61%   |
| HGST                      | 3        | 6      | 0.61%   |
| Unknown                   | 3        | 5      | 0.61%   |
| Verbatim                  | 2        | 5      | 0.41%   |
| Transcend                 | 2        | 2      | 0.41%   |
| Micron/Crucial Technology | 2        | 2      | 0.41%   |
| Maxtor                    | 2        | 2      | 0.41%   |
| LITEON                    | 2        | 2      | 0.41%   |
| HUAWEI                    | 2        | 2      | 0.41%   |
| Fujitsu                   | 2        | 2      | 0.41%   |
| Apple                     | 2        | 5      | 0.41%   |
| XPG                       | 1        | 1      | 0.2%    |
| Unknown (CF)              | 1        | 1      | 0.2%    |
| Team                      | 1        | 1      | 0.2%    |
| Silicon Motion            | 1        | 1      | 0.2%    |
| Shark                     | 1        | 1      | 0.2%    |
| Seagate Technology        | 1        | 1      | 0.2%    |
| Realtek Semiconductor     | 1        | 2      | 0.2%    |
| Patriot                   | 1        | 1      | 0.2%    |
| OCZ-VERTEX3               | 1        | 1      | 0.2%    |
| LITEONIT                  | 1        | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB           | 8        | 1.39%   |
| Samsung NVMe SSD Drive 1TB             | 7        | 1.22%   |
| Kingston SV300S37A120G 120GB SSD       | 7        | 1.22%   |
| Kingston SA400S37240G 240GB SSD        | 7        | 1.22%   |
| Seagate ST2000DM001-1ER164 2TB         | 6        | 1.04%   |
| Samsung SSD 860 QVO 1TB                | 6        | 1.04%   |
| Samsung SSD 860 EVO 1TB                | 6        | 1.04%   |
| Samsung SSD 850 EVO 250GB              | 6        | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB         | 5        | 0.87%   |
| Samsung SSD 840 EVO 250GB              | 5        | 0.87%   |
| Crucial CT1000MX500SSD1 1TB            | 5        | 0.87%   |
| Unknown SD/MMC/MS PRO 64GB             | 4        | 0.7%    |
| Seagate ST2000DM001-1CH164 2TB         | 4        | 0.7%    |
| Seagate ST1000DM003-1SB102 1TB         | 4        | 0.7%    |
| Samsung SSD 860 EVO 500GB              | 4        | 0.7%    |
| Samsung SSD 850 EVO 500GB              | 4        | 0.7%    |
| Kingston SA400S37480G 480GB SSD        | 4        | 0.7%    |
| Kingston SA400S37120G 120GB SSD        | 4        | 0.7%    |
| WDC WD20EARX-00PASB0 2TB               | 3        | 0.52%   |
| WDC WD1003FZEX-00K3CA0 1TB             | 3        | 0.52%   |
| Seagate ST500DM002-1BD142 500GB        | 3        | 0.52%   |
| Seagate ST4000VN008-2DR166 4TB         | 3        | 0.52%   |
| Seagate ST3250310AS 250GB              | 3        | 0.52%   |
| Seagate ST3000DM008-2DM166 3TB         | 3        | 0.52%   |
| Seagate ST3000DM001-1ER166 3TB         | 3        | 0.52%   |
| Seagate ST1000DM003-1SB10C 1TB         | 3        | 0.52%   |
| SanDisk NVMe SSD Drive 1TB             | 3        | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB         | 3        | 0.52%   |
| Samsung SSD 970 EVO 1TB                | 3        | 0.52%   |
| Samsung SSD 840 EVO 500GB              | 3        | 0.52%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3        | 0.52%   |
| Samsung NVMe SSD Drive 250GB           | 3        | 0.52%   |
| Samsung HD103SJ 1TB                    | 3        | 0.52%   |
| PNY CS900 120GB SSD                    | 3        | 0.52%   |
| Kingston SV300S37A240G 240GB SSD       | 3        | 0.52%   |
| Kingston SUV400S37240G 240GB SSD       | 3        | 0.52%   |
| Kingston SUV400S37120G 120GB SSD       | 3        | 0.52%   |
| Kingston SA2000M81000G 1TB             | 3        | 0.52%   |
| JMicron Generic 240GB SSD              | 3        | 0.52%   |
| Intenso SCSI 1TB                       | 3        | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 85       | 123    | 40.48%  |
| WDC                 | 69       | 124    | 32.86%  |
| Toshiba             | 18       | 24     | 8.57%   |
| Samsung Electronics | 10       | 16     | 4.76%   |
| Hitachi             | 10       | 14     | 4.76%   |
| Unknown             | 4        | 5      | 1.9%    |
| HGST                | 3        | 6      | 1.43%   |
| Maxtor              | 2        | 2      | 0.95%   |
| Fujitsu             | 2        | 2      | 0.95%   |
| Apple               | 2        | 5      | 0.95%   |
| Unknown             | 2        | 4      | 0.95%   |
| Intenso             | 1        | 2      | 0.48%   |
| Hewlett-Packard     | 1        | 2      | 0.48%   |
| ASMT109x            | 1        | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 55       | 98     | 30.39%  |
| Kingston            | 39       | 52     | 21.55%  |
| Crucial             | 20       | 29     | 11.05%  |
| SanDisk             | 10       | 10     | 5.52%   |
| WDC                 | 6        | 6      | 3.31%   |
| Intel               | 5        | 6      | 2.76%   |
| PNY                 | 4        | 4      | 2.21%   |
| OCZ                 | 4        | 4      | 2.21%   |
| Corsair             | 4        | 5      | 2.21%   |
| A-DATA Technology   | 4        | 4      | 2.21%   |
| Micron Technology   | 3        | 4      | 1.66%   |
| JMicron Technology  | 3        | 3      | 1.66%   |
| Intenso             | 3        | 3      | 1.66%   |
| Verbatim            | 2        | 5      | 1.1%    |
| Transcend           | 2        | 2      | 1.1%    |
| LITEON              | 2        | 2      | 1.1%    |
| Unknown (CF)        | 1        | 1      | 0.55%   |
| Toshiba             | 1        | 1      | 0.55%   |
| Team                | 1        | 1      | 0.55%   |
| SK hynix            | 1        | 1      | 0.55%   |
| Shark               | 1        | 1      | 0.55%   |
| Patriot             | 1        | 1      | 0.55%   |
| OCZ-VERTEX3         | 1        | 1      | 0.55%   |
| LITEONIT            | 1        | 1      | 0.55%   |
| Leven               | 1        | 1      | 0.55%   |
| INDMEM              | 1        | 1      | 0.55%   |
| FORESEE             | 1        | 1      | 0.55%   |
| AFOX                | 1        | 1      | 0.55%   |
| ADATA SU            | 1        | 1      | 0.55%   |
| 2-Power             | 1        | 2      | 0.55%   |
| Unknown             | 1        | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 158      | 330    | 39.4%   |
| SSD     | 145      | 253    | 36.16%  |
| NVMe    | 89       | 139    | 22.19%  |
| Unknown | 7        | 8      | 1.75%   |
| MMC     | 2        | 2      | 0.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 225      | 559    | 65.98%  |
| NVMe | 89       | 139    | 26.1%   |
| SAS  | 25       | 32     | 7.33%   |
| MMC  | 2        | 2      | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 163      | 280    | 47.52%  |
| 0.51-1.0   | 90       | 135    | 26.24%  |
| 1.01-2.0   | 40       | 74     | 11.66%  |
| 2.01-3.0   | 17       | 29     | 4.96%   |
| 4.01-10.0  | 15       | 35     | 4.37%   |
| 3.01-4.0   | 13       | 19     | 3.79%   |
| 10.01-20.0 | 5        | 11     | 1.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 50       | 18.05%  |
| 251-500        | 46       | 16.61%  |
| 101-250        | 46       | 16.61%  |
| 1001-2000      | 37       | 13.36%  |
| More than 3000 | 30       | 10.83%  |
| 2001-3000      | 21       | 7.58%   |
| 1-20           | 17       | 6.14%   |
| Unknown        | 13       | 4.69%   |
| 21-50          | 10       | 3.61%   |
| 51-100         | 7        | 2.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 86       | 30.71%  |
| 21-50          | 40       | 14.29%  |
| 101-250        | 35       | 12.5%   |
| 501-1000       | 26       | 9.29%   |
| 51-100         | 24       | 8.57%   |
| 251-500        | 22       | 7.86%   |
| More than 3000 | 15       | 5.36%   |
| 1001-2000      | 15       | 5.36%   |
| Unknown        | 13       | 4.64%   |
| 2001-3000      | 4        | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Kingston SHPM2280P2H 480G SSD     | 2        | 2      | 7.14%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1      | 3.57%   |
| WDC WD5000AADS-00S9B0 500GB       | 1        | 1      | 3.57%   |
| WDC WD10EZRX-00A8LB0 1TB          | 1        | 1      | 3.57%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 3.57%   |
| WDC WD10EURX-73FH1Y0 1TB          | 1        | 1      | 3.57%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 3.57%   |
| Seagate ST380013AS 80GB           | 1        | 1      | 3.57%   |
| Seagate ST3400633AS 400GB         | 1        | 1      | 3.57%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 3.57%   |
| Seagate ST320LT020-9YG142 320GB   | 1        | 1      | 3.57%   |
| Seagate ST3200822AS 200GB         | 1        | 1      | 3.57%   |
| Seagate ST31000524AS 1TB          | 1        | 1      | 3.57%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 3.57%   |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 1      | 3.57%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 3.57%   |
| SanDisk SDSSDX240GG25 240GB       | 1        | 1      | 3.57%   |
| Samsung Electronics SP0812C 80GB  | 1        | 1      | 3.57%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 3.57%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 3.57%   |
| OCZ AGILITY3 240GB SSD            | 1        | 1      | 3.57%   |
| Leven JAJS300M480C 480GB SSD      | 1        | 1      | 3.57%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 3      | 3.57%   |
| Kingston SA400S37480G 480GB SSD   | 1        | 1      | 3.57%   |
| Intel SSDSC2BW480H6 480GB         | 1        | 1      | 3.57%   |
| Hitachi HDP725032GLA360 320GB     | 1        | 2      | 3.57%   |
| Unknown                           | 1        | 2      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 9      | 32%     |
| WDC                 | 5        | 6      | 20%     |
| Kingston            | 4        | 6      | 16%     |
| Samsung Electronics | 2        | 3      | 8%      |
| SanDisk             | 1        | 1      | 4%      |
| OCZ                 | 1        | 1      | 4%      |
| Leven               | 1        | 1      | 4%      |
| Intel               | 1        | 1      | 4%      |
| Hitachi             | 1        | 2      | 4%      |
| Unknown             | 1        | 2      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 9      | 47.06%  |
| WDC                 | 5        | 6      | 29.41%  |
| Samsung Electronics | 2        | 3      | 11.76%  |
| Hitachi             | 1        | 2      | 5.88%   |
| Unknown             | 1        | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 22     | 65%     |
| SSD  | 7        | 10     | 35%     |

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
| Detected | 186      | 483    | 63.05%  |
| Works    | 89       | 217    | 30.17%  |
| Malfunc  | 20       | 32     | 6.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 162      | 40.1%   |
| AMD                          | 92       | 22.77%  |
| Samsung Electronics          | 42       | 10.4%   |
| ASMedia Technology           | 20       | 4.95%   |
| Phison Electronics           | 14       | 3.47%   |
| Kingston Technology Company  | 14       | 3.47%   |
| SanDisk                      | 13       | 3.22%   |
| JMicron Technology           | 10       | 2.48%   |
| Nvidia                       | 8        | 1.98%   |
| Marvell Technology Group     | 8        | 1.98%   |
| Micron/Crucial Technology    | 5        | 1.24%   |
| SK hynix                     | 3        | 0.74%   |
| Seagate Technology           | 3        | 0.74%   |
| VIA Technologies             | 2        | 0.5%    |
| ADATA Technology             | 2        | 0.5%    |
| Toshiba America Info Systems | 1        | 0.25%   |
| Silicon Motion               | 1        | 0.25%   |
| Realtek Semiconductor        | 1        | 0.25%   |
| HighPoint Technologies       | 1        | 0.25%   |
| Hewlett-Packard              | 1        | 0.25%   |
| Broadcom / LSI               | 1        | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 61       | 12.2%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 27       | 5.4%    |
| AMD 400 Series Chipset SATA Controller                                         | 23       | 4.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 20       | 4%      |
| ASMedia ASM1062 Serial ATA Controller                                          | 19       | 3.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 18       | 3.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 17       | 3.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15       | 3%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 14       | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11       | 2.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9        | 1.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 9        | 1.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8        | 1.6%    |
| Phison E12 NVMe Controller                                                     | 8        | 1.6%    |
| Kingston Company A2000 NVMe SSD                                                | 8        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 8        | 1.6%    |
| Phison E16 PCIe4 NVMe Controller                                               | 6        | 1.2%    |
| JMicron JMB363 SATA/IDE Controller                                             | 6        | 1.2%    |
| Intel SSD 660P Series                                                          | 6        | 1.2%    |
| Intel SATA Controller [RAID mode]                                              | 6        | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6        | 1.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 6        | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5        | 1%      |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 5        | 1%      |
| AMD 300 Series Chipset SATA Controller                                         | 5        | 1%      |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4        | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                            | 4        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 0.8%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 4        | 0.8%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4        | 0.8%    |
| Intel 4 Series Chipset PT IDER Controller                                      | 4        | 0.8%    |
| AMD X370 Series Chipset SATA Controller                                        | 4        | 0.8%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3        | 0.6%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 3        | 0.6%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 0.6%    |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 0.6%    |
| JMicron JMB368 IDE controller                                                  | 3        | 0.6%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 0.6%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 223      | 57.47%  |
| NVMe | 91       | 23.45%  |
| IDE  | 55       | 14.18%  |
| RAID | 18       | 4.64%   |
| SAS  | 1        | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 161      | 62.4%   |
| AMD    | 97       | 37.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 9        | 3.47%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 8        | 3.09%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 6        | 2.32%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 6        | 2.32%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 6        | 2.32%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 5        | 1.93%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 5        | 1.93%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 4        | 1.54%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 4        | 1.54%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 4        | 1.54%   |
| Intel Core i5-3350P CPU @ 3.10GHz      | 4        | 1.54%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 4        | 1.54%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 4        | 1.54%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 3        | 1.16%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 3        | 1.16%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 3        | 1.16%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 3        | 1.16%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 3        | 1.16%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 0.77%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 2        | 0.77%   |
| Intel Core i7-4770S CPU @ 3.10GHz      | 2        | 0.77%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 2        | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 0.77%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 0.77%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 2        | 0.77%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 2        | 0.77%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 2        | 0.77%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 0.77%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 2        | 0.77%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 2        | 0.77%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 2        | 0.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 0.77%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 2        | 0.77%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 2        | 0.77%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz   | 2        | 0.77%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz   | 2        | 0.77%   |
| Intel 12th Gen Core i9-12900K          | 2        | 0.77%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 2        | 0.77%   |
| AMD Ryzen 9 3950X 16-Core Processor    | 2        | 0.77%   |
| AMD Ryzen 7 1800X Eight-Core Processor | 2        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 50       | 19.31%  |
| Intel Core i7           | 48       | 18.53%  |
| AMD Ryzen 7             | 25       | 9.65%   |
| AMD Ryzen 5             | 21       | 8.11%   |
| AMD Ryzen 9             | 13       | 5.02%   |
| Intel Core i3           | 12       | 4.63%   |
| Intel Xeon              | 11       | 4.25%   |
| Intel Core 2 Duo        | 9        | 3.47%   |
| AMD FX                  | 8        | 3.09%   |
| Other                   | 7        | 2.7%    |
| Intel Core i9           | 4        | 1.54%   |
| Intel Core 2 Quad       | 4        | 1.54%   |
| Intel Celeron           | 4        | 1.54%   |
| AMD Ryzen 3             | 4        | 1.54%   |
| AMD Phenom II X4        | 4        | 1.54%   |
| AMD Athlon 64 X2        | 4        | 1.54%   |
| Intel Pentium           | 3        | 1.16%   |
| Intel Atom              | 3        | 1.16%   |
| AMD Ryzen Threadripper  | 3        | 1.16%   |
| AMD Athlon II X4        | 3        | 1.16%   |
| AMD A8                  | 3        | 1.16%   |
| AMD A6                  | 3        | 1.16%   |
| Intel Pentium Dual-Core | 2        | 0.77%   |
| Intel Core 2            | 2        | 0.77%   |
| AMD A10                 | 2        | 0.77%   |
| Intel Pentium Silver    | 1        | 0.39%   |
| Intel Pentium Dual      | 1        | 0.39%   |
| AMD Phenom II X2        | 1        | 0.39%   |
| AMD GX                  | 1        | 0.39%   |
| AMD E                   | 1        | 0.39%   |
| AMD Athlon II Neo       | 1        | 0.39%   |
| AMD A4                  | 1        | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 108      | 41.7%   |
| 2      | 50       | 19.31%  |
| 6      | 45       | 17.37%  |
| 8      | 33       | 12.74%  |
| 12     | 10       | 3.86%   |
| 16     | 7        | 2.7%    |
| 1      | 2        | 0.77%   |
| 64     | 1        | 0.39%   |
| 32     | 1        | 0.39%   |
| 24     | 1        | 0.39%   |
| 10     | 1        | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 256      | 99.22%  |
| 2      | 2        | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 158      | 61.24%  |
| 1      | 100      | 38.76%  |

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
| Unknown    | 57       | 21.27%  |
| 0x306c3    | 20       | 7.46%   |
| 0x506e3    | 14       | 5.22%   |
| 0x306a9    | 14       | 5.22%   |
| 0x206a7    | 14       | 5.22%   |
| 0x0800820d | 10       | 3.73%   |
| 0x906ea    | 8        | 2.99%   |
| 0x1067a    | 8        | 2.99%   |
| 0x08701021 | 8        | 2.99%   |
| 0x08701013 | 7        | 2.61%   |
| 0x906e9    | 6        | 2.24%   |
| 0x0a201009 | 6        | 2.24%   |
| 0x08001138 | 6        | 2.24%   |
| 0x06000852 | 5        | 1.87%   |
| 0x010000c8 | 5        | 1.87%   |
| 0xa0653    | 4        | 1.49%   |
| 0x906ec    | 4        | 1.49%   |
| 0x906ed    | 3        | 1.12%   |
| 0x90672    | 3        | 1.12%   |
| 0x6fd      | 3        | 1.12%   |
| 0x106e5    | 3        | 1.12%   |
| 0xa0671    | 2        | 0.75%   |
| 0xa0655    | 2        | 0.75%   |
| 0x6f6      | 2        | 0.75%   |
| 0x206c2    | 2        | 0.75%   |
| 0x10676    | 2        | 0.75%   |
| 0x0a201205 | 2        | 0.75%   |
| 0x08600106 | 2        | 0.75%   |
| 0x08108109 | 2        | 0.75%   |
| 0x08001137 | 2        | 0.75%   |
| 0x08001129 | 2        | 0.75%   |
| 0x06001119 | 2        | 0.75%   |
| 0x0600063e | 2        | 0.75%   |
| 0x010000db | 2        | 0.75%   |
| 0x906eb    | 1        | 0.37%   |
| 0x906c0    | 1        | 0.37%   |
| 0x806ea    | 1        | 0.37%   |
| 0x706a1    | 1        | 0.37%   |
| 0x6fb      | 1        | 0.37%   |
| 0x506c9    | 1        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 31       | 11.97%  |
| Zen 2            | 28       | 10.81%  |
| Haswell          | 28       | 10.81%  |
| IvyBridge        | 19       | 7.34%   |
| Skylake          | 18       | 6.95%   |
| SandyBridge      | 16       | 6.18%   |
| Zen+             | 13       | 5.02%   |
| Penryn           | 13       | 5.02%   |
| Zen 3            | 12       | 4.63%   |
| Zen              | 11       | 4.25%   |
| Piledriver       | 9        | 3.47%   |
| K10              | 9        | 3.47%   |
| Core             | 6        | 2.32%   |
| CometLake        | 6        | 2.32%   |
| Nehalem          | 5        | 1.93%   |
| Unknown          | 5        | 1.93%   |
| Westmere         | 4        | 1.54%   |
| K8 Hammer        | 4        | 1.54%   |
| Alderlake Hybrid | 3        | 1.16%   |
| Steamroller      | 2        | 0.77%   |
| Puma             | 2        | 0.77%   |
| Jaguar           | 2        | 0.77%   |
| Icelake          | 2        | 0.77%   |
| Bulldozer        | 2        | 0.77%   |
| Broadwell        | 2        | 0.77%   |
| Bonnell          | 2        | 0.77%   |
| Silvermont       | 1        | 0.39%   |
| Goldmont plus    | 1        | 0.39%   |
| Goldmont         | 1        | 0.39%   |
| Excavator        | 1        | 0.39%   |
| Bobcat           | 1        | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 152      | 53.52%  |
| AMD               | 71       | 25%     |
| Intel             | 60       | 21.13%  |
| ASPEED Technology | 1        | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 3.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11       | 3.79%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 8        | 2.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 2.41%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 2.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 2.07%   |
| Intel HD Graphics 530                                                       | 6        | 2.07%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 1.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 1.72%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.72%   |
| Intel HD Graphics 630                                                       | 5        | 1.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 1.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.72%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 1.38%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 1.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.38%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 1.38%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.03%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 1.03%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 3        | 1.03%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 3        | 1.03%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.03%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 1.03%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.03%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.03%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 1.03%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 3        | 1.03%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.03%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.69%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.69%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.69%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.69%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 0.69%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 2        | 0.69%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 140      | 53.85%  |
| 1 x AMD         | 60       | 23.08%  |
| 1 x Intel       | 41       | 15.77%  |
| Intel + Nvidia  | 6        | 2.31%   |
| 2 x AMD         | 4        | 1.54%   |
| Intel + AMD     | 3        | 1.15%   |
| AMD + Nvidia    | 3        | 1.15%   |
| 2 x Nvidia      | 2        | 0.77%   |
| Nvidia + ASPEED | 1        | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 163      | 61.05%  |
| Proprietary | 97       | 36.33%  |
| Unknown     | 7        | 2.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 86       | 32.33%  |
| 1.01-2.0   | 55       | 20.68%  |
| 7.01-8.0   | 38       | 14.29%  |
| 5.01-6.0   | 20       | 7.52%   |
| 3.01-4.0   | 20       | 7.52%   |
| 0.01-0.5   | 19       | 7.14%   |
| 0.51-1.0   | 15       | 5.64%   |
| 8.01-16.0  | 10       | 3.76%   |
| 2.01-3.0   | 2        | 0.75%   |
| 4.01-5.0   | 1        | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 60       | 20%     |
| Dell                    | 29       | 9.67%   |
| Ancor Communications    | 22       | 7.33%   |
| Hewlett-Packard         | 19       | 6.33%   |
| AOC                     | 19       | 6.33%   |
| Philips                 | 17       | 5.67%   |
| BenQ                    | 17       | 5.67%   |
| Acer                    | 17       | 5.67%   |
| Goldstar                | 13       | 4.33%   |
| ASUSTek Computer        | 12       | 4%      |
| Lenovo                  | 10       | 3.33%   |
| Sony                    | 8        | 2.67%   |
| Unknown                 | 6        | 2%      |
| Medion                  | 5        | 1.67%   |
| Lenovo Group Limited    | 5        | 1.67%   |
| LG Electronics          | 4        | 1.33%   |
| IBM                     | 3        | 1%      |
| ViewSonic               | 2        | 0.67%   |
| Vestel Elektronik       | 2        | 0.67%   |
| Tech Concepts           | 2        | 0.67%   |
| MSI                     | 2        | 0.67%   |
| Idek Iiyama             | 2        | 0.67%   |
| Gigabyte Technology     | 2        | 0.67%   |
| Fujitsu Siemens         | 2        | 0.67%   |
| AUS                     | 2        | 0.67%   |
| Unknown                 | 2        | 0.67%   |
| Wacom                   | 1        | 0.33%   |
| Vestel                  | 1        | 0.33%   |
| TopView                 | 1        | 0.33%   |
| Pixio                   | 1        | 0.33%   |
| Pioneer                 | 1        | 0.33%   |
| Panasonic               | 1        | 0.33%   |
| Packard Bell            | 1        | 0.33%   |
| OTC                     | 1        | 0.33%   |
| OEM                     | 1        | 0.33%   |
| Iiyama                  | 1        | 0.33%   |
| IFS                     | 1        | 0.33%   |
| Eizo                    | 1        | 0.33%   |
| Chi Mei Optoelectronics | 1        | 0.33%   |
| AU Optronics            | 1        | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6        | 1.78%   |
| Sony TV SNYEE01 1920x1080                                             | 3        | 0.89%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 3        | 0.89%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                     | 3        | 0.89%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3        | 0.89%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 3        | 0.89%   |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                     | 3        | 0.89%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 2        | 0.59%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                      | 2        | 0.59%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch  | 2        | 0.59%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 2        | 0.59%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2        | 0.59%   |
| Medion MD20444 MED3661 1920x1080 521x293mm 23.5-inch                  | 2        | 0.59%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 410x260mm 19.1-inch            | 2        | 0.59%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch              | 2        | 0.59%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 2        | 0.59%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch       | 2        | 0.59%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 2        | 0.59%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                     | 2        | 0.59%   |
| Dell P1913 DELA089 1440x900 408x255mm 18.9-inch                       | 2        | 0.59%   |
| Dell 2407WFP DELA017 1920x1200 520x330mm 24.2-inch                    | 2        | 0.59%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 2        | 0.59%   |
| BenQ G2420HDB BNQ7842 1920x1080 477x268mm 21.5-inch                   | 2        | 0.59%   |
| BenQ G2420HD BNQ7840 1920x1080 530x300mm 24.0-inch                    | 2        | 0.59%   |
| ASUSTek Computer VA249 AUS24C1 1920x1080 527x296mm 23.8-inch          | 2        | 0.59%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 2        | 0.59%   |
| AOC 2450W AOC2450 1920x1080 520x290mm 23.4-inch                       | 2        | 0.59%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 2        | 0.59%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2        | 0.59%   |
| Ancor Communications ASUS VP278 ACI27C8 1920x1080 598x336mm 27.0-inch | 2        | 0.59%   |
| Unknown                                                               | 2        | 0.59%   |
| Wacom Cintiq 16 WAC1064 1920x1080 344x193mm 15.5-inch                 | 1        | 0.3%    |
| ViewSonic VX2880ML VSCCE2F 3840x2160 621x341mm 27.9-inch              | 1        | 0.3%    |
| ViewSonic VG2236 SERIES VSCE726 1920x1080 477x268mm 21.5-inch         | 1        | 0.3%    |
| Vestel LCD Monitor 49UHD_LCD_TV 3840x2160                             | 1        | 0.3%    |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.3%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.3%    |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.3%    |
| Unknown LCD Monitor Nexgen MIRAI DML-517 1280x1024                    | 1        | 0.3%    |
| Unknown LCD Monitor Dell S2716DG 2560x1440                            | 1        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 136      | 46.26%  |
| 2560x1440 (QHD)    | 34       | 11.56%  |
| 3840x2160 (4K)     | 30       | 10.2%   |
| Unknown            | 16       | 5.44%   |
| 1680x1050 (WSXGA+) | 14       | 4.76%   |
| 1280x1024 (SXGA)   | 12       | 4.08%   |
| 3440x1440          | 7        | 2.38%   |
| 3840x1080          | 6        | 2.04%   |
| 1440x900 (WXGA+)   | 6        | 2.04%   |
| 1600x900 (HD+)     | 5        | 1.7%    |
| 1920x1200 (WUXGA)  | 4        | 1.36%   |
| 1360x768           | 3        | 1.02%   |
| 3840x1200          | 2        | 0.68%   |
| 1920x540           | 2        | 0.68%   |
| 9840x3840          | 1        | 0.34%   |
| 6400x2160          | 1        | 0.34%   |
| 5760x1440          | 1        | 0.34%   |
| 5760x1080          | 1        | 0.34%   |
| 5120x1440          | 1        | 0.34%   |
| 4608x1440          | 1        | 0.34%   |
| 4480x1440          | 1        | 0.34%   |
| 3840x1600          | 1        | 0.34%   |
| 3200x1200          | 1        | 0.34%   |
| 3200x1080          | 1        | 0.34%   |
| 2560x1600          | 1        | 0.34%   |
| 2560x1080          | 1        | 0.34%   |
| 2560x1024          | 1        | 0.34%   |
| 2048x1152          | 1        | 0.34%   |
| 1600x1200          | 1        | 0.34%   |
| 1366x768 (WXGA)    | 1        | 0.34%   |
| 1360x765           | 1        | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 57       | 19.26%  |
| 24      | 49       | 16.55%  |
| Unknown | 47       | 15.88%  |
| 23      | 34       | 11.49%  |
| 31      | 19       | 6.42%   |
| 21      | 18       | 6.08%   |
| 19      | 13       | 4.39%   |
| 22      | 10       | 3.38%   |
| 20      | 9        | 3.04%   |
| 72      | 7        | 2.36%   |
| 34      | 6        | 2.03%   |
| 84      | 4        | 1.35%   |
| 32      | 3        | 1.01%   |
| 15      | 3        | 1.01%   |
| 28      | 2        | 0.68%   |
| 17      | 2        | 0.68%   |
| 65      | 1        | 0.34%   |
| 60      | 1        | 0.34%   |
| 54      | 1        | 0.34%   |
| 48      | 1        | 0.34%   |
| 42      | 1        | 0.34%   |
| 39      | 1        | 0.34%   |
| 38      | 1        | 0.34%   |
| 35      | 1        | 0.34%   |
| 33      | 1        | 0.34%   |
| 30      | 1        | 0.34%   |
| 29      | 1        | 0.34%   |
| 25      | 1        | 0.34%   |
| 18      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 117      | 41.79%  |
| Unknown     | 47       | 16.79%  |
| 401-500     | 43       | 15.36%  |
| 601-700     | 31       | 11.07%  |
| 1501-2000   | 11       | 3.93%   |
| 701-800     | 10       | 3.57%   |
| 351-400     | 8        | 2.86%   |
| 301-350     | 5        | 1.79%   |
| 1001-1500   | 4        | 1.43%   |
| 801-900     | 3        | 1.07%   |
| 901-1000    | 1        | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 168      | 63.64%  |
| Unknown | 42       | 15.91%  |
| 16/10   | 30       | 11.36%  |
| 5/4     | 10       | 3.79%   |
| 21/9    | 9        | 3.41%   |
| 4/3     | 2        | 0.76%   |
| 32/9    | 2        | 0.76%   |
| 3/2     | 1        | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 88       | 30.24%  |
| 301-350        | 57       | 19.59%  |
| Unknown        | 47       | 16.15%  |
| 351-500        | 33       | 11.34%  |
| 151-200        | 26       | 8.93%   |
| 251-300        | 17       | 5.84%   |
| More than 1000 | 14       | 4.81%   |
| 501-1000       | 4        | 1.37%   |
| 141-150        | 2        | 0.69%   |
| 101-110        | 2        | 0.69%   |
| 111-120        | 1        | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 156      | 57.56%  |
| 101-120 | 47       | 17.34%  |
| Unknown | 47       | 17.34%  |
| 121-160 | 10       | 3.69%   |
| 1-50    | 9        | 3.32%   |
| 161-240 | 2        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 180      | 68.7%   |
| 2     | 60       | 22.9%   |
| 0     | 13       | 4.96%   |
| 3     | 9        | 3.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 156      | 41.49%  |
| Intel                           | 119      | 31.65%  |
| Qualcomm Atheros                | 14       | 3.72%   |
| Broadcom                        | 14       | 3.72%   |
| Nvidia                          | 8        | 2.13%   |
| Ralink                          | 6        | 1.6%    |
| TP-Link                         | 5        | 1.33%   |
| Ralink Technology               | 5        | 1.33%   |
| ASUSTek Computer                | 5        | 1.33%   |
| Qualcomm Atheros Communications | 4        | 1.06%   |
| MediaTek                        | 4        | 1.06%   |
| IMC Networks                    | 4        | 1.06%   |
| Huawei Technologies             | 4        | 1.06%   |
| Aquantia                        | 4        | 1.06%   |
| OnePlus Technology (Shenzhen)   | 3        | 0.8%    |
| Edimax Technology               | 3        | 0.8%    |
| Samsung Electronics             | 2        | 0.53%   |
| NetGear                         | 2        | 0.53%   |
| Microsoft                       | 2        | 0.53%   |
| D-Link                          | 2        | 0.53%   |
| Unknown                         | 1        | 0.27%   |
| Texas Instruments               | 1        | 0.27%   |
| Solarflare Communications       | 1        | 0.27%   |
| Linksys                         | 1        | 0.27%   |
| JMicron Technology              | 1        | 0.27%   |
| InterBiometrics                 | 1        | 0.27%   |
| ICS Advent                      | 1        | 0.27%   |
| HMD Global                      | 1        | 0.27%   |
| D-Link System                   | 1        | 0.27%   |
| ASIX Electronics                | 1        | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 124      | 28.84%  |
| Intel I211 Gigabit Network Connection                                                | 24       | 5.58%   |
| Intel Ethernet Connection (2) I219-V                                                 | 17       | 3.95%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 16       | 3.72%   |
| Intel Wi-Fi 6 AX200                                                                  | 12       | 2.79%   |
| Intel Ethernet Connection I217-LM                                                    | 9        | 2.09%   |
| Intel Ethernet Controller I225-V                                                     | 8        | 1.86%   |
| Intel Ethernet Connection (7) I219-V                                                 | 8        | 1.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 8        | 1.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 8        | 1.86%   |
| Intel Wireless-AC 9260                                                               | 7        | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 6        | 1.4%    |
| Intel Ethernet Connection (2) I218-V                                                 | 4        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                                           | 4        | 0.93%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                 | 4        | 0.93%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                    | 4        | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 3        | 0.7%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 0.7%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                      | 3        | 0.7%    |
| Realtek 802.11ac NIC                                                                 | 3        | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 3        | 0.7%    |
| OnePlus (Shenzhen) OnePlus                                                           | 3        | 0.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 3        | 0.7%    |
| Intel 82579V Gigabit Network Connection                                              | 3        | 0.7%    |
| Intel 82574L Gigabit Network Connection                                              | 3        | 0.7%    |
| TP-Link 802.11ac WLAN Adapter                                                        | 2        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                                        | 2        | 0.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 0.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 2        | 0.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 2        | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 2        | 0.47%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 0.47%   |
| Ralink MT7601U Wireless Adapter                                                      | 2        | 0.47%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 0.47%   |
| Nvidia MCP73 Ethernet                                                                | 2        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 40       | 31.01%  |
| Realtek Semiconductor           | 26       | 20.16%  |
| Broadcom                        | 11       | 8.53%   |
| Qualcomm Atheros                | 9        | 6.98%   |
| Ralink                          | 6        | 4.65%   |
| TP-Link                         | 5        | 3.88%   |
| Ralink Technology               | 5        | 3.88%   |
| ASUSTek Computer                | 5        | 3.88%   |
| Qualcomm Atheros Communications | 4        | 3.1%    |
| IMC Networks                    | 4        | 3.1%    |
| MediaTek                        | 3        | 2.33%   |
| Edimax Technology               | 3        | 2.33%   |
| NetGear                         | 2        | 1.55%   |
| Microsoft                       | 2        | 1.55%   |
| D-Link                          | 2        | 1.55%   |
| Linksys                         | 1        | 0.78%   |
| D-Link System                   | 1        | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 12       | 9.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 8        | 6.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 8        | 6.02%   |
| Intel Wireless-AC 9260                                                               | 7        | 5.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 3.01%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                 | 4        | 3.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 3        | 2.26%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 2.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 2.26%   |
| Realtek 802.11ac NIC                                                                 | 3        | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 3        | 2.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 3        | 2.26%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 2        | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 1.5%    |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 1.5%    |
| Ralink MT7601U Wireless Adapter                                                      | 2        | 1.5%    |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 1.5%    |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 1.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 2        | 1.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 2        | 1.5%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 2        | 1.5%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 2        | 1.5%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 0.75%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 0.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1        | 0.75%   |
| TP-Link Archer T4U ver.3                                                             | 1        | 0.75%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1        | 0.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 1        | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.75%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                      | 1        | 0.75%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 1        | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.75%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 1        | 0.75%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 0.75%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                                               | 1        | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 1        | 0.75%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 145      | 51.42%  |
| Intel                         | 103      | 36.52%  |
| Nvidia                        | 8        | 2.84%   |
| Qualcomm Atheros              | 6        | 2.13%   |
| Aquantia                      | 4        | 1.42%   |
| OnePlus Technology (Shenzhen) | 3        | 1.06%   |
| Broadcom                      | 3        | 1.06%   |
| Samsung Electronics           | 2        | 0.71%   |
| Huawei Technologies           | 2        | 0.71%   |
| Solarflare Communications     | 1        | 0.35%   |
| MediaTek                      | 1        | 0.35%   |
| JMicron Technology            | 1        | 0.35%   |
| ICS Advent                    | 1        | 0.35%   |
| HMD Global                    | 1        | 0.35%   |
| ASIX Electronics              | 1        | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 124      | 42.47%  |
| Intel I211 Gigabit Network Connection                             | 24       | 8.22%   |
| Intel Ethernet Connection (2) I219-V                              | 17       | 5.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 5.48%   |
| Intel Ethernet Connection I217-LM                                 | 9        | 3.08%   |
| Intel Ethernet Controller I225-V                                  | 8        | 2.74%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 2.05%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.37%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.03%   |
| OnePlus (Shenzhen) OnePlus                                        | 3        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.03%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.03%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.68%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.68%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.68%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.68%   |
| Huawei STK-L21                                                    | 2        | 0.68%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.34%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.34%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.34%   |
| Nvidia MCP79 Ethernet                                             | 1        | 0.34%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.34%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.34%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.34%   |
| MediaTek Infinix NOTE 11                                          | 1        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 256      | 66.67%  |
| WiFi     | 123      | 32.03%  |
| Modem    | 4        | 1.04%   |
| Unknown  | 1        | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 208      | 76.75%  |
| WiFi     | 63       | 23.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 150      | 58.14%  |
| 2     | 89       | 34.5%   |
| 3     | 15       | 5.81%   |
| 0     | 3        | 1.16%   |
| 4     | 1        | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 248      | 95.75%  |
| Yes  | 11       | 4.25%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 40       | 44.44%  |
| Cambridge Silicon Radio         | 24       | 26.67%  |
| ASUSTek Computer                | 6        | 6.67%   |
| Qualcomm Atheros Communications | 4        | 4.44%   |
| IMC Networks                    | 4        | 4.44%   |
| Broadcom                        | 4        | 4.44%   |
| MediaTek                        | 3        | 3.33%   |
| Belkin Components               | 2        | 2.22%   |
| Realtek Semiconductor           | 1        | 1.11%   |
| HTC (High Tech Computer)        | 1        | 1.11%   |
| Edimax Technology               | 1        | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 24       | 26.67%  |
| Intel AX200 Bluetooth                                                | 11       | 12.22%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 8        | 8.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 7        | 7.78%   |
| Intel Bluetooth wireless interface                                   | 4        | 4.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4        | 4.44%   |
| MediaTek Wireless_Device                                             | 3        | 3.33%   |
| IMC Networks Bluetooth Radio                                         | 3        | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2        | 2.22%   |
| Intel AX210 Bluetooth                                                | 2        | 2.22%   |
| Intel AX201 Bluetooth                                                | 2        | 2.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 2.22%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 2        | 2.22%   |
| ASUS Bluetooth Radio                                                 | 2        | 2.22%   |
| ASUS Bluetooth Device                                                | 2        | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 1.11%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 1.11%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 1.11%   |
| Intel Bluetooth Device                                               | 1        | 1.11%   |
| IMC Networks Bluetooth Device                                        | 1        | 1.11%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.11%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 1.11%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 1.11%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 1.11%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 1.11%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Nvidia                  | 149      | 29.74%  |
| Intel                   | 146      | 29.14%  |
| AMD                     | 116      | 23.15%  |
| SteelSeries ApS         | 14       | 2.79%   |
| Kingston Technology     | 10       | 2%      |
| C-Media Electronics     | 10       | 2%      |
| Creative Labs           | 6        | 1.2%    |
| ASUSTek Computer        | 6        | 1.2%    |
| Logitech                | 5        | 1%      |
| Creative Technology     | 5        | 1%      |
| GN Netcom               | 4        | 0.8%    |
| Yamaha                  | 2        | 0.4%    |
| VIA Technologies        | 2        | 0.4%    |
| Texas Instruments       | 2        | 0.4%    |
| Realtek Semiconductor   | 2        | 0.4%    |
| Razer USA               | 2        | 0.4%    |
| Focusrite-Novation      | 2        | 0.4%    |
| XMOS                    | 1        | 0.2%    |
| Unknown                 | 1        | 0.2%    |
| Turtle Beach            | 1        | 0.2%    |
| Tenx Technology         | 1        | 0.2%    |
| Syntek                  | 1        | 0.2%    |
| Sony                    | 1        | 0.2%    |
| Shure                   | 1        | 0.2%    |
| RODE Microphones        | 1        | 0.2%    |
| ROCCAT                  | 1        | 0.2%    |
| JMTek                   | 1        | 0.2%    |
| GYROCOM C&C             | 1        | 0.2%    |
| Corsair                 | 1        | 0.2%    |
| Clavia DMI AB           | 1        | 0.2%    |
| BR25                    | 1        | 0.2%    |
| BEHRINGER International | 1        | 0.2%    |
| B & W Group             | 1        | 0.2%    |
| Audio-Technica          | 1        | 0.2%    |
| Astro Gaming            | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 35       | 6.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20       | 3.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 20       | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18       | 3.21%   |
| Intel 200 Series PCH HD Audio                                              | 17       | 3.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 2.67%   |
| Nvidia TU116 High Definition Audio Controller                              | 14       | 2.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 14       | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 14       | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13       | 2.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13       | 2.32%   |
| Nvidia GP104 High Definition Audio Controller                              | 12       | 2.14%   |
| AMD Navi 10 HDMI Audio                                                     | 12       | 2.14%   |
| Nvidia TU104 HD Audio Controller                                           | 10       | 1.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 9        | 1.6%    |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 1.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 1.6%    |
| Nvidia GK104 HDMI Audio Controller                                         | 8        | 1.43%   |
| Kingston Technology HyperX 7.1 Audio                                       | 8        | 1.43%   |
| AMD FCH Azalia Controller                                                  | 8        | 1.43%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 1.25%   |
| Nvidia GM204 High Definition Audio Controller                              | 7        | 1.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.25%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 1.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 1.07%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 1.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 1.07%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 5        | 0.89%   |
| Nvidia GP102 HDMI Audio Controller                                         | 5        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 0.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 0.89%   |
| ASUSTek Computer USB Audio                                                 | 5        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                   | 5        | 0.89%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 4        | 0.71%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 0.71%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 36       | 25.53%  |
| Kingston            | 26       | 18.44%  |
| G.Skill             | 20       | 14.18%  |
| Samsung Electronics | 16       | 11.35%  |
| Unknown             | 14       | 9.93%   |
| Crucial             | 10       | 7.09%   |
| Micron Technology   | 7        | 4.96%   |
| SK hynix            | 5        | 3.55%   |
| Ramaxel Technology  | 2        | 1.42%   |
| Nanya Technology    | 2        | 1.42%   |
| Unifosa             | 1        | 0.71%   |
| Elpida              | 1        | 0.71%   |
| Unknown             | 1        | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 7        | 4.64%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 4        | 2.65%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 4        | 2.65%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                  | 2        | 1.32%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 2        | 1.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 2        | 1.32%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s      | 2        | 1.32%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 2        | 1.32%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s     | 2        | 1.32%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 2        | 1.32%   |
| Kingston RAM KF556C36-16 16GB DIMM DDR5 5600MT/s         | 2        | 1.32%   |
| Kingston RAM HP24D4U7S8MBP-8 8192MB DIMM DDR4 2400MT/s   | 2        | 1.32%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 2        | 1.32%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 2        | 1.32%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 2        | 1.32%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 2        | 1.32%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s      | 2        | 1.32%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 2        | 1.32%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s                 | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 4096MB DIMM                           | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 0.66%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s               | 1        | 0.66%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s       | 1        | 0.66%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM DDR3 1333MT/s     | 1        | 0.66%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.66%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.66%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s    | 1        | 0.66%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s  | 1        | 0.66%   |
| SK hynix RAM HMT325U6CFR8C-H9 2048MB DIMM DDR3 1333MT/s  | 1        | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 1        | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s | 1        | 0.66%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 69       | 53.91%  |
| DDR3    | 37       | 28.91%  |
| Unknown | 10       | 7.81%   |
| SDRAM   | 6        | 4.69%   |
| DDR5    | 4        | 3.13%   |
| DDR     | 2        | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 119      | 94.44%  |
| SODIMM | 7        | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 61       | 45.52%  |
| 4096  | 27       | 20.15%  |
| 16384 | 24       | 17.91%  |
| 2048  | 15       | 11.19%  |
| 32768 | 4        | 2.99%   |
| 1024  | 2        | 1.49%   |
| 512   | 1        | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 18.71%  |
| 3600    | 15       | 10.79%  |
| 3200    | 14       | 10.07%  |
| 1333    | 14       | 10.07%  |
| 2400    | 9        | 6.47%   |
| 3400    | 7        | 5.04%   |
| 3466    | 6        | 4.32%   |
| 2667    | 6        | 4.32%   |
| 2133    | 5        | 3.6%    |
| 2933    | 3        | 2.16%   |
| 667     | 3        | 2.16%   |
| 5600    | 2        | 1.44%   |
| 5200    | 2        | 1.44%   |
| 3666    | 2        | 1.44%   |
| 3500    | 2        | 1.44%   |
| 3000    | 2        | 1.44%   |
| 2048    | 2        | 1.44%   |
| 1867    | 2        | 1.44%   |
| Unknown | 2        | 1.44%   |
| 20306   | 1        | 0.72%   |
| 4400    | 1        | 0.72%   |
| 4000    | 1        | 0.72%   |
| 3800    | 1        | 0.72%   |
| 3733    | 1        | 0.72%   |
| 3533    | 1        | 0.72%   |
| 3333    | 1        | 0.72%   |
| 3100    | 1        | 0.72%   |
| 2733    | 1        | 0.72%   |
| 1866    | 1        | 0.72%   |
| 1800    | 1        | 0.72%   |
| 1639    | 1        | 0.72%   |
| 1334    | 1        | 0.72%   |
| 1066    | 1        | 0.72%   |
| 533     | 1        | 0.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 53.85%  |
| Brother Industries  | 4        | 30.77%  |
| Prolific Technology | 1        | 7.69%   |
| Canon               | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port      | 1        | 7.69%   |
| HP LaserJet 1020                   | 1        | 7.69%   |
| HP ENVY Photo 6200 series          | 1        | 7.69%   |
| HP ENVY 4520 series                | 1        | 7.69%   |
| HP Deskjet D4300 series            | 1        | 7.69%   |
| HP DeskJet 5940                    | 1        | 7.69%   |
| HP DeskJet 5550                    | 1        | 7.69%   |
| HP DeskJet 2620 All-in-One Printer | 1        | 7.69%   |
| Canon iP7200 series                | 1        | 7.69%   |
| Brother HL-5250DN Printer          | 1        | 7.69%   |
| Brother HL-2240D series            | 1        | 7.69%   |
| Brother HL-2030 Laser Printer      | 1        | 7.69%   |
| Brother DCP-J140W                  | 1        | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP ScanJet 5470c/5490c | 1        | 50%     |
| HP PSC 1200            | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 23       | 57.5%   |
| Microsoft                              | 3        | 7.5%    |
| Trust                                  | 2        | 5%      |
| Sunplus Innovation Technology          | 2        | 5%      |
| Samsung Electronics                    | 2        | 5%      |
| Quanta                                 | 1        | 2.5%    |
| Oculus VR                              | 1        | 2.5%    |
| Intel                                  | 1        | 2.5%    |
| Hewlett-Packard                        | 1        | 2.5%    |
| Cubeternet                             | 1        | 2.5%    |
| Creative Technology                    | 1        | 2.5%    |
| Chicony Electronics                    | 1        | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) | 1        | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech StreamCam                                                   | 4        | 10%     |
| Logitech HD Webcam C525                                              | 3        | 7.5%    |
| Logitech HD Pro Webcam C920                                          | 3        | 7.5%    |
| Trust USB Camera                                                     | 2        | 5%      |
| Samsung Galaxy A5 (MTP)                                              | 2        | 5%      |
| Logitech Webcam C270                                                 | 2        | 5%      |
| Logitech C930c                                                       | 2        | 5%      |
| Logitech C922 Pro Stream Webcam                                      | 2        | 5%      |
| Sunplus SunplusIT PC Camera                                          | 1        | 2.5%    |
| Sunplus Sandberg USB Webcam Pro                                      | 1        | 2.5%    |
| Quanta FREETALK HD                                                   | 1        | 2.5%    |
| Oculus VR Quest 2                                                    | 1        | 2.5%    |
| Microsoft MicrosoftÂ LifeCam Studio                                 | 1        | 2.5%    |
| Microsoft LifeCam HD-3000                                            | 1        | 2.5%    |
| Microsoft LifeCam Cinema                                             | 1        | 2.5%    |
| Logitech Webcam Pro 9000                                             | 1        | 2.5%    |
| Logitech Webcam C930e                                                | 1        | 2.5%    |
| Logitech Webcam C925e                                                | 1        | 2.5%    |
| Logitech QuickCam Pro 5000                                           | 1        | 2.5%    |
| Logitech QuickCam E 3500                                             | 1        | 2.5%    |
| Logitech HD Webcam C510                                              | 1        | 2.5%    |
| Logitech C670i FHD Webcam                                            | 1        | 2.5%    |
| Intel RealSense Camera SR300                                         | 1        | 2.5%    |
| HP HD-4110 Webcam                                                    | 1        | 2.5%    |
| Cubeternet USB2.0 Camera                                             | 1        | 2.5%    |
| Creative Live! Cam Sync 1080p                                        | 1        | 2.5%    |
| Chicony Gateway Webcam                                               | 1        | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 2.5%    |

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
| Advanced Card Systems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Advanced Card Systems ACR1252 Dual Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 220      | 83.65%  |
| 1     | 31       | 11.79%  |
| 2     | 8        | 3.04%   |
| 3     | 2        | 0.76%   |
| 6     | 1        | 0.38%   |
| 4     | 1        | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 14       | 25.93%  |
| Graphics card            | 12       | 22.22%  |
| Multimedia controller    | 6        | 11.11%  |
| Communication controller | 6        | 11.11%  |
| Sound                    | 5        | 9.26%   |
| Unassigned class         | 4        | 7.41%   |
| Storage/raid             | 2        | 3.7%    |
| Network                  | 1        | 1.85%   |
| Net/ethernet             | 1        | 1.85%   |
| Chipcard                 | 1        | 1.85%   |
| Card reader              | 1        | 1.85%   |
| Camera                   | 1        | 1.85%   |

