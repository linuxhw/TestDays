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

Total: 431

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 3032h                       | [007bbeffa0](https://linux-hardware.org/?probe=007bbeffa0) | Feb 26, 2023 |
| Dell          | 01TN68 A02                  | [ce7bdb1ddf](https://linux-hardware.org/?probe=ce7bdb1ddf) | Feb 21, 2023 |
| Dell          | 01TN68 A02                  | [0dd1f15a92](https://linux-hardware.org/?probe=0dd1f15a92) | Feb 21, 2023 |
| HP            | 1497                        | [47ffeac7cf](https://linux-hardware.org/?probe=47ffeac7cf) | Feb 20, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [9f6834d4a9](https://linux-hardware.org/?probe=9f6834d4a9) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [131f8f99a2](https://linux-hardware.org/?probe=131f8f99a2) | Feb 17, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [01355a0714](https://linux-hardware.org/?probe=01355a0714) | Feb 17, 2023 |
| ASRock        | H81M-HDS                    | [b744809cc2](https://linux-hardware.org/?probe=b744809cc2) | Feb 14, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [4d007a868e](https://linux-hardware.org/?probe=4d007a868e) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [29dc75351d](https://linux-hardware.org/?probe=29dc75351d) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [54d35f2b7f](https://linux-hardware.org/?probe=54d35f2b7f) | Feb 03, 2023 |
| HP            | 1905                        | [9ddf75323e](https://linux-hardware.org/?probe=9ddf75323e) | Feb 03, 2023 |
| ASRock        | X300M-STX                   | [5ce1aa97c6](https://linux-hardware.org/?probe=5ce1aa97c6) | Feb 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ef9c1299e6](https://linux-hardware.org/?probe=ef9c1299e6) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [78b817b650](https://linux-hardware.org/?probe=78b817b650) | Jan 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| ASRock        | B550M-ITX/ac                | [a7ac9067b0](https://linux-hardware.org/?probe=a7ac9067b0) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fd99b07929](https://linux-hardware.org/?probe=fd99b07929) | Jan 18, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [286de51ef8](https://linux-hardware.org/?probe=286de51ef8) | Jan 13, 2023 |
| HP            | ProLiant MicroServer Gen... | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [fcda893618](https://linux-hardware.org/?probe=fcda893618) | Jan 13, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| ASRock        | B450M-HDV R4.0              | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | P85-D3                      | [8d017ea6af](https://linux-hardware.org/?probe=8d017ea6af) | Jan 01, 2023 |
| Gigabyte      | P85-D3                      | [aebeaf8b5e](https://linux-hardware.org/?probe=aebeaf8b5e) | Jan 01, 2023 |
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


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Ubuntu 20.04         | 41       | 13.44%  |
| Ubuntu 18.04         | 30       | 9.84%   |
| Arch Rolling         | 14       | 4.59%   |
| Zorin 16             | 13       | 4.26%   |
| OpenMandriva 4.2     | 13       | 4.26%   |
| Ubuntu 22.04         | 8        | 2.62%   |
| Pop!_OS 21.04        | 7        | 2.3%    |
| OpenMandriva 4.3     | 7        | 2.3%    |
| Manjaro              | 7        | 2.3%    |
| Linux Mint 20.2      | 7        | 2.3%    |
| Debian 11            | 7        | 2.3%    |
| Ubuntu 20.10         | 5        | 1.64%   |
| Ubuntu 19.04         | 5        | 1.64%   |
| Pop!_OS 20.10        | 5        | 1.64%   |
| Linux Mint 20.3      | 5        | 1.64%   |
| Linux Mint 20.1      | 5        | 1.64%   |
| Zorin 15             | 4        | 1.31%   |
| Ubuntu 22.10         | 4        | 1.31%   |
| Ubuntu 21.10         | 4        | 1.31%   |
| Pop!_OS 22.04        | 4        | 1.31%   |
| Linux Mint 21.1      | 4        | 1.31%   |
| KDE neon 20.04       | 4        | 1.31%   |
| Ubuntu 19.10         | 3        | 0.98%   |
| Pop!_OS 21.10        | 3        | 0.98%   |
| Linux Mint 20        | 3        | 0.98%   |
| Fedora 32            | 3        | 0.98%   |
| Debian 10            | 3        | 0.98%   |
| Ubuntu MATE 20.04    | 2        | 0.66%   |
| Ubuntu 16.04         | 2        | 0.66%   |
| Pop!_OS 20.04        | 2        | 0.66%   |
| Manjaro 21.2.0       | 2        | 0.66%   |
| Manjaro 20.0.3       | 2        | 0.66%   |
| Manjaro 20.0.1       | 2        | 0.66%   |
| Linux Mint 19.3      | 2        | 0.66%   |
| Linux Mint 19.2      | 2        | 0.66%   |
| Linux Mint 19.1      | 2        | 0.66%   |
| Kubuntu 20.04        | 2        | 0.66%   |
| Garuda Linux Soaring | 2        | 0.66%   |
| Fedora 37            | 2        | 0.66%   |
| Fedora 35            | 2        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 101      | 34.71%  |
| Linux Mint   | 30       | 10.31%  |
| OpenMandriva | 22       | 7.56%   |
| Pop!_OS      | 21       | 7.22%   |
| Zorin        | 17       | 5.84%   |
| Manjaro      | 16       | 5.5%    |
| Arch         | 16       | 5.5%    |
| Fedora       | 14       | 4.81%   |
| Debian       | 13       | 4.47%   |
| Kubuntu      | 6        | 2.06%   |
| KDE neon     | 5        | 1.72%   |
| Ubuntu MATE  | 3        | 1.03%   |
| ROSA         | 3        | 1.03%   |
| Gentoo       | 3        | 1.03%   |
| EndeavourOS  | 3        | 1.03%   |
| ArcoLinux    | 3        | 1.03%   |
| MX           | 2        | 0.69%   |
| Garuda Linux | 2        | 0.69%   |
| Xubuntu      | 1        | 0.34%   |
| SteamOS      | 1        | 0.34%   |
| Solus        | 1        | 0.34%   |
| Parrot       | 1        | 0.34%   |
| openSUSE     | 1        | 0.34%   |
| NixOS        | 1        | 0.34%   |
| Lubuntu      | 1        | 0.34%   |
| Endless      | 1        | 0.34%   |
| Elementary   | 1        | 0.34%   |
| BlackPanther | 1        | 0.34%   |
| Anarchy      | 1        | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 11       | 3.34%   |
| 5.4.0-52-generic         | 6        | 1.82%   |
| 5.16.7-desktop-1omv4003  | 6        | 1.82%   |
| 5.15.0-58-generic        | 5        | 1.52%   |
| 5.15.0-56-generic        | 5        | 1.52%   |
| 5.8.0-43-generic         | 4        | 1.22%   |
| 5.4.0-42-generic         | 4        | 1.22%   |
| 5.11.12-desktop-1omv4002 | 4        | 1.22%   |
| 4.15.0-48-generic        | 4        | 1.22%   |
| 5.8.5-arch1-1            | 3        | 0.91%   |
| 5.4.0-91-generic         | 3        | 0.91%   |
| 5.4.0-90-generic         | 3        | 0.91%   |
| 5.4.0-73-generic         | 3        | 0.91%   |
| 5.4.0-58-generic         | 3        | 0.91%   |
| 5.4.0-29-generic         | 3        | 0.91%   |
| 5.3.0-28-generic         | 3        | 0.91%   |
| 5.15.0-46-generic        | 3        | 0.91%   |
| 5.15.0-41-generic        | 3        | 0.91%   |
| 5.13.0-28-generic        | 3        | 0.91%   |
| 5.11.0-7620-generic      | 3        | 0.91%   |
| 5.11.0-37-generic        | 3        | 0.91%   |
| 5.11.0-27-generic        | 3        | 0.91%   |
| 5.10.0-20-amd64          | 3        | 0.91%   |
| 5.0.0-13-generic         | 3        | 0.91%   |
| 4.15.0-45-generic        | 3        | 0.91%   |
| 6.1.9-arch1-1            | 2        | 0.61%   |
| 5.8.0-7642-generic       | 2        | 0.61%   |
| 5.8.0-63-generic         | 2        | 0.61%   |
| 5.8.0-41-generic         | 2        | 0.61%   |
| 5.6.15-1-MANJARO         | 2        | 0.61%   |
| 5.6.12-1-MANJARO         | 2        | 0.61%   |
| 5.4.18-1-MANJARO         | 2        | 0.61%   |
| 5.4.0-88-generic         | 2        | 0.61%   |
| 5.4.0-80-generic         | 2        | 0.61%   |
| 5.4.0-70-generic         | 2        | 0.61%   |
| 5.4.0-53-generic         | 2        | 0.61%   |
| 5.4.0-48-generic         | 2        | 0.61%   |
| 5.4.0-26-generic         | 2        | 0.61%   |
| 5.3.0-46-generic         | 2        | 0.61%   |
| 5.3.0-26-generic         | 2        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 51       | 16.24%  |
| 4.15.0  | 28       | 8.92%   |
| 5.8.0   | 21       | 6.69%   |
| 5.15.0  | 20       | 6.37%   |
| 5.13.0  | 19       | 6.05%   |
| 5.11.0  | 18       | 5.73%   |
| 5.3.0   | 11       | 3.5%    |
| 5.10.14 | 11       | 3.5%    |
| 5.19.0  | 8        | 2.55%   |
| 5.10.0  | 8        | 2.55%   |
| 5.0.0   | 8        | 2.55%   |
| 5.16.7  | 6        | 1.91%   |
| 4.18.0  | 5        | 1.59%   |
| 5.11.12 | 4        | 1.27%   |
| 4.19.0  | 4        | 1.27%   |
| 5.8.5   | 3        | 0.96%   |
| 5.6.15  | 3        | 0.96%   |
| 6.1.9   | 2        | 0.64%   |
| 5.9.1   | 2        | 0.64%   |
| 5.8.18  | 2        | 0.64%   |
| 5.6.12  | 2        | 0.64%   |
| 5.4.18  | 2        | 0.64%   |
| 5.19.5  | 2        | 0.64%   |
| 5.16.0  | 2        | 0.64%   |
| 5.13.12 | 2        | 0.64%   |
| 5.11.11 | 2        | 0.64%   |
| 6.1.8   | 1        | 0.32%   |
| 6.1.7   | 1        | 0.32%   |
| 6.1.4   | 1        | 0.32%   |
| 6.1.3   | 1        | 0.32%   |
| 6.1.12  | 1        | 0.32%   |
| 6.1.1   | 1        | 0.32%   |
| 6.0.9   | 1        | 0.32%   |
| 6.0.7   | 1        | 0.32%   |
| 6.0.6   | 1        | 0.32%   |
| 6.0.15  | 1        | 0.32%   |
| 6.0.12  | 1        | 0.32%   |
| 6.0.11  | 1        | 0.32%   |
| 5.9.0   | 1        | 0.32%   |
| 5.8.6   | 1        | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 17.86%  |
| 5.8     | 30       | 9.74%   |
| 5.15    | 28       | 9.09%   |
| 4.15    | 28       | 9.09%   |
| 5.11    | 26       | 8.44%   |
| 5.13    | 22       | 7.14%   |
| 5.10    | 21       | 6.82%   |
| 5.16    | 13       | 4.22%   |
| 5.3     | 11       | 3.57%   |
| 5.19    | 11       | 3.57%   |
| 5.0     | 8        | 2.6%    |
| 6.1     | 7        | 2.27%   |
| 5.6     | 7        | 2.27%   |
| 6.0     | 6        | 1.95%   |
| 5.7     | 5        | 1.62%   |
| 4.19    | 5        | 1.62%   |
| 4.18    | 5        | 1.62%   |
| 5.17    | 4        | 1.3%    |
| 5.9     | 3        | 0.97%   |
| 5.14    | 3        | 0.97%   |
| 4.9     | 3        | 0.97%   |
| 5.12    | 2        | 0.65%   |
| 5.1     | 2        | 0.65%   |
| 5.2     | 1        | 0.32%   |
| 5.18    | 1        | 0.32%   |
| 4.17    | 1        | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 276      | 98.92%  |
| i686   | 3        | 1.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 123      | 41.84%  |
| Unknown       | 55       | 18.71%  |
| KDE5          | 50       | 17.01%  |
| X-Cinnamon    | 24       | 8.16%   |
| XFCE          | 16       | 5.44%   |
| KDE           | 7        | 2.38%   |
| MATE          | 6        | 2.04%   |
| Cinnamon      | 4        | 1.36%   |
| KDE4          | 2        | 0.68%   |
| Pantheon      | 1        | 0.34%   |
| openbox       | 1        | 0.34%   |
| LXDE          | 1        | 0.34%   |
| i3            | 1        | 0.34%   |
| enlightenment | 1        | 0.34%   |
| Deepin        | 1        | 0.34%   |
| bspwm         | 1        | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 235      | 82.17%  |
| Unknown | 25       | 8.74%   |
| Wayland | 19       | 6.64%   |
| Tty     | 7        | 2.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 163      | 56.01%  |
| SDDM    | 45       | 15.46%  |
| GDM3    | 29       | 9.97%   |
| GDM     | 20       | 6.87%   |
| LightDM | 16       | 5.5%    |
| TDM     | 15       | 5.15%   |
| KDM     | 2        | 0.69%   |
| LXDM    | 1        | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 102      | 35.54%  |
| da_DK      | 85       | 29.62%  |
| Unknown    | 42       | 14.63%  |
| en_DK      | 36       | 12.54%  |
| en_GB      | 8        | 2.79%   |
| C          | 3        | 1.05%   |
| ru_RU      | 2        | 0.7%    |
| de_DE      | 2        | 0.7%    |
| pl_PL      | 1        | 0.35%   |
| it_IT      | 1        | 0.35%   |
| io_001     | 1        | 0.35%   |
| es_ES      | 1        | 0.35%   |
| en_US.UTF8 | 1        | 0.35%   |
| en_IE      | 1        | 0.35%   |
| de_AT      | 1        | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 165      | 57.89%  |
| EFI  | 120      | 42.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 228      | 78.62%  |
| Overlay | 25       | 8.62%   |
| Btrfs   | 18       | 6.21%   |
| Unknown | 13       | 4.48%   |
| Zfs     | 3        | 1.03%   |
| Xfs     | 2        | 0.69%   |
| F2fs    | 1        | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 171      | 58.97%  |
| GPT     | 90       | 31.03%  |
| MBR     | 29       | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 224      | 77.51%  |
| Yes       | 65       | 22.49%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 203      | 71.48%  |
| Yes       | 81       | 28.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 92       | 32.97%  |
| Gigabyte Technology | 44       | 15.77%  |
| ASRock              | 27       | 9.68%   |
| MSI                 | 26       | 9.32%   |
| Lenovo              | 24       | 8.6%    |
| Hewlett-Packard     | 18       | 6.45%   |
| Medion              | 11       | 3.94%   |
| Dell                | 11       | 3.94%   |
| Acer                | 6        | 2.15%   |
| Shuttle             | 3        | 1.08%   |
| Pegatron            | 3        | 1.08%   |
| Intel               | 2        | 0.72%   |
| T-bao               | 1        | 0.36%   |
| Packard Bell        | 1        | 0.36%   |
| NEXCOM              | 1        | 0.36%   |
| Inventec            | 1        | 0.36%   |
| Fujitsu             | 1        | 0.36%   |
| eMachines           | 1        | 0.36%   |
| ECS                 | 1        | 0.36%   |
| BESSTAR Tech        | 1        | 0.36%   |
| AMI                 | 1        | 0.36%   |
| Alienware           | 1        | 0.36%   |
| ABIT                | 1        | 0.36%   |
| Unknown             | 1        | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS ROG STRIX B450-E GAMING | 5        | 1.79%   |
| ASUS All Series              | 5        | 1.79%   |
| ASUS Z170 PRO GAMING         | 4        | 1.43%   |
| MSI MS-7C37                  | 3        | 1.08%   |
| Dell OptiPlex 9020           | 3        | 1.08%   |
| ASUS ROG STRIX B550-F GAMING | 3        | 1.08%   |
| MSI MS-7C02                  | 2        | 0.72%   |
| MSI MS-7B79                  | 2        | 0.72%   |
| Medion MS-7797               | 2        | 0.72%   |
| Medion MS-7646               | 2        | 0.72%   |
| Lenovo H30-05 90BJ00CNMT     | 2        | 0.72%   |
| Gigabyte X570 AORUS MASTER   | 2        | 0.72%   |
| Gigabyte P85-D3              | 2        | 0.72%   |
| ASUS TUF Gaming X570-PLUS    | 2        | 0.72%   |
| ASUS ROG STRIX X470-I GAMING | 2        | 0.72%   |
| ASUS PRIME Z390-A            | 2        | 0.72%   |
| ASUS PRIME Z370-P            | 2        | 0.72%   |
| ASUS PRIME Z370-A            | 2        | 0.72%   |
| ASUS PRIME B250M-A           | 2        | 0.72%   |
| ASUS M5A78L-M/USB3           | 2        | 0.72%   |
| ASUS CROSSHAIR VI HERO       | 2        | 0.72%   |
| ASRock B550M-ITX/ac          | 2        | 0.72%   |
| T-bao MINI PC                | 1        | 0.36%   |
| Shuttle X50V2PLUS            | 1        | 0.36%   |
| Shuttle SN68S                | 1        | 0.36%   |
| Shuttle SH67H3               | 1        | 0.36%   |
| Pegatron HPE-532sc           | 1        | 0.36%   |
| Pegatron h8-1110sc           | 1        | 0.36%   |
| Pegatron 2AD5                | 1        | 0.36%   |
| Packard Bell IXTREME M5741   | 1        | 0.36%   |
| NEXCOM NDIS B322             | 1        | 0.36%   |
| MSI Vortex G65VR 6RE SLI     | 1        | 0.36%   |
| MSI MS-7C91                  | 1        | 0.36%   |
| MSI MS-7C83                  | 1        | 0.36%   |
| MSI MS-7C80                  | 1        | 0.36%   |
| MSI MS-7C75                  | 1        | 0.36%   |
| MSI MS-7C56                  | 1        | 0.36%   |
| MSI MS-7B86                  | 1        | 0.36%   |
| MSI MS-7B50                  | 1        | 0.36%   |
| MSI MS-7A40                  | 1        | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS ROG            | 22       | 7.89%   |
| ASUS PRIME          | 22       | 7.89%   |
| Lenovo ThinkCentre  | 11       | 3.94%   |
| ASUS TUF            | 9        | 3.23%   |
| Gigabyte X570       | 7        | 2.51%   |
| HP Compaq           | 6        | 2.15%   |
| Dell OptiPlex       | 5        | 1.79%   |
| ASUS All            | 5        | 1.79%   |
| Lenovo ThinkStation | 4        | 1.43%   |
| ASUS Z170           | 4        | 1.43%   |
| MSI MS-7C37         | 3        | 1.08%   |
| HP ProLiant         | 3        | 1.08%   |
| Gigabyte B550       | 3        | 1.08%   |
| ASUS SABERTOOTH     | 3        | 1.08%   |
| ASUS M5A78L-M       | 3        | 1.08%   |
| ASRock Z170         | 3        | 1.08%   |
| Acer Aspire         | 3        | 1.08%   |
| MSI MS-7C02         | 2        | 0.72%   |
| MSI MS-7B79         | 2        | 0.72%   |
| Medion MS-7797      | 2        | 0.72%   |
| Medion MS-7646      | 2        | 0.72%   |
| Lenovo IdeaCentre   | 2        | 0.72%   |
| Lenovo H30-05       | 2        | 0.72%   |
| HP EliteDesk        | 2        | 0.72%   |
| Gigabyte Z390       | 2        | 0.72%   |
| Gigabyte P85-D3     | 2        | 0.72%   |
| Gigabyte A320M-S2H  | 2        | 0.72%   |
| Dell Precision      | 2        | 0.72%   |
| ASUS CROSSHAIR      | 2        | 0.72%   |
| ASRock Z77          | 2        | 0.72%   |
| ASRock B550M-ITX    | 2        | 0.72%   |
| ASRock B450M        | 2        | 0.72%   |
| ASRock B450         | 2        | 0.72%   |
| T-bao MINI          | 1        | 0.36%   |
| Shuttle X50V2PLUS   | 1        | 0.36%   |
| Shuttle SN68S       | 1        | 0.36%   |
| Shuttle SH67H3      | 1        | 0.36%   |
| Pegatron HPE-532sc  | 1        | 0.36%   |
| Pegatron h8-1110sc  | 1        | 0.36%   |
| Pegatron 2AD5       | 1        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 31       | 11.11%  |
| 2020 | 29       | 10.39%  |
| 2019 | 27       | 9.68%   |
| 2012 | 27       | 9.68%   |
| 2021 | 21       | 7.53%   |
| 2013 | 21       | 7.53%   |
| 2017 | 18       | 6.45%   |
| 2016 | 17       | 6.09%   |
| 2015 | 15       | 5.38%   |
| 2011 | 15       | 5.38%   |
| 2010 | 14       | 5.02%   |
| 2014 | 11       | 3.94%   |
| 2009 | 10       | 3.58%   |
| 2008 | 10       | 3.58%   |
| 2022 | 6        | 2.15%   |
| 2007 | 5        | 1.79%   |
| 2006 | 2        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 279      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 275      | 98.57%  |
| Enabled  | 4        | 1.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 279      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 91       | 31.71%  |
| 32.01-64.0      | 60       | 20.91%  |
| 8.01-16.0       | 51       | 17.77%  |
| 3.01-4.0        | 27       | 9.41%   |
| 4.01-8.0        | 25       | 8.71%   |
| 64.01-256.0     | 17       | 5.92%   |
| 24.01-32.0      | 9        | 3.14%   |
| 1.01-2.0        | 4        | 1.39%   |
| 2.01-3.0        | 2        | 0.7%    |
| More than 256.0 | 1        | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 106      | 33.65%  |
| 2.01-3.0   | 76       | 24.13%  |
| 4.01-8.0   | 52       | 16.51%  |
| 3.01-4.0   | 48       | 15.24%  |
| 8.01-16.0  | 15       | 4.76%   |
| 0.51-1.0   | 10       | 3.17%   |
| 0.01-0.5   | 4        | 1.27%   |
| 24.01-32.0 | 2        | 0.63%   |
| 32.01-64.0 | 1        | 0.32%   |
| 16.01-24.0 | 1        | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 106      | 36.81%  |
| 2      | 67       | 23.26%  |
| 3      | 58       | 20.14%  |
| 4      | 29       | 10.07%  |
| 5      | 16       | 5.56%   |
| 6      | 5        | 1.74%   |
| 0      | 3        | 1.04%   |
| 8      | 2        | 0.69%   |
| 9      | 1        | 0.35%   |
| 7      | 1        | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 156      | 55.71%  |
| Yes       | 124      | 44.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 277      | 99.28%  |
| No        | 2        | 0.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 151      | 53.17%  |
| Yes       | 133      | 46.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 186      | 66.19%  |
| Yes       | 95       | 33.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Denmark | 279      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Copenhagen               | 73       | 25.35%  |
| Frederiksberg            | 15       | 5.21%   |
| Odense                   | 14       | 4.86%   |
| Aarhus                   | 11       | 3.82%   |
| Aabenraa                 | 7        | 2.43%   |
| Slagelse                 | 6        | 2.08%   |
| Silkeborg                | 6        | 2.08%   |
| Bronshoj                 | 6        | 2.08%   |
| Vejle                    | 4        | 1.39%   |
| Roskilde                 | 4        | 1.39%   |
| Horsens                  | 4        | 1.39%   |
| Herlev                   | 4        | 1.39%   |
| Esbjerg                  | 4        | 1.39%   |
| Allinge                  | 4        | 1.39%   |
| Albertslund Municipality | 4        | 1.39%   |
| Aalborg                  | 4        | 1.39%   |
| Valby                    | 3        | 1.04%   |
| Svendborg                | 3        | 1.04%   |
| Rødovre Municipality    | 3        | 1.04%   |
| Nyborg                   | 3        | 1.04%   |
| Hvidovre                 | 3        | 1.04%   |
| Hjørring                | 3        | 1.04%   |
| Aabybro                  | 3        | 1.04%   |
| Viby J                   | 2        | 0.69%   |
| Trige                    | 2        | 0.69%   |
| Taastrup                 | 2        | 0.69%   |
| Stovring                 | 2        | 0.69%   |
| Soborg                   | 2        | 0.69%   |
| Skanderborg              | 2        | 0.69%   |
| Risskov                  | 2        | 0.69%   |
| Odder                    | 2        | 0.69%   |
| Kongens Lyngby           | 2        | 0.69%   |
| Kolding                  | 2        | 0.69%   |
| Kastrup                  | 2        | 0.69%   |
| Hundested                | 2        | 0.69%   |
| Holstebro                | 2        | 0.69%   |
| Glostrup Municipality    | 2        | 0.69%   |
| Gentofte Municipality    | 2        | 0.69%   |
| Fredericia               | 2        | 0.69%   |
| Charlottenlund           | 2        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 104      | 184    | 19.51%  |
| Seagate                   | 95       | 142    | 17.82%  |
| WDC                       | 86       | 146    | 16.14%  |
| Kingston                  | 50       | 74     | 9.38%   |
| Crucial                   | 25       | 34     | 4.69%   |
| Toshiba                   | 21       | 27     | 3.94%   |
| SanDisk                   | 21       | 26     | 3.94%   |
| Intel                     | 15       | 17     | 2.81%   |
| Hitachi                   | 11       | 17     | 2.06%   |
| Intenso                   | 8        | 11     | 1.5%    |
| Corsair                   | 8        | 11     | 1.5%    |
| Phison                    | 7        | 10     | 1.31%   |
| Unknown                   | 6        | 7      | 1.13%   |
| A-DATA Technology         | 6        | 6      | 1.13%   |
| SK hynix                  | 4        | 4      | 0.75%   |
| PNY                       | 4        | 4      | 0.75%   |
| OCZ                       | 4        | 4      | 0.75%   |
| Phison Electronics        | 3        | 5      | 0.56%   |
| Micron Technology         | 3        | 4      | 0.56%   |
| JMicron Technology        | 3        | 3      | 0.56%   |
| HGST                      | 3        | 6      | 0.56%   |
| XPG                       | 2        | 2      | 0.38%   |
| Verbatim                  | 2        | 5      | 0.38%   |
| Transcend                 | 2        | 2      | 0.38%   |
| Micron/Crucial Technology | 2        | 2      | 0.38%   |
| Maxtor                    | 2        | 2      | 0.38%   |
| LITEON                    | 2        | 2      | 0.38%   |
| Leven                     | 2        | 2      | 0.38%   |
| HUAWEI                    | 2        | 2      | 0.38%   |
| Fujitsu                   | 2        | 2      | 0.38%   |
| Apple                     | 2        | 5      | 0.38%   |
| AFOX                      | 2        | 2      | 0.38%   |
| Unknown                   | 2        | 4      | 0.38%   |
| USB                       | 1        | 1      | 0.19%   |
| Unknown (CF)              | 1        | 1      | 0.19%   |
| Team                      | 1        | 1      | 0.19%   |
| Supersonic                | 1        | 1      | 0.19%   |
| Silicon Motion            | 1        | 1      | 0.19%   |
| Shark                     | 1        | 1      | 0.19%   |
| Seagate Technology        | 1        | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB                         | 8        | 1.27%   |
| Kingston SV300S37A120G 120GB SSD                     | 8        | 1.27%   |
| Samsung NVMe SSD Drive 1TB                           | 7        | 1.11%   |
| Kingston SA400S37240G 240GB SSD                      | 7        | 1.11%   |
| Seagate ST2000DM001-1ER164 2TB                       | 6        | 0.95%   |
| Seagate ST1000DM010-2EP102 1TB                       | 6        | 0.95%   |
| Samsung SSD 860 QVO 1TB                              | 6        | 0.95%   |
| Samsung SSD 860 EVO 1TB                              | 6        | 0.95%   |
| Samsung SSD 850 EVO 250GB                            | 6        | 0.95%   |
| Samsung SSD 840 EVO 250GB                            | 6        | 0.95%   |
| Samsung SSD 860 EVO 500GB                            | 5        | 0.79%   |
| Kingston SA400S37480G 480GB SSD                      | 5        | 0.79%   |
| Crucial CT1000MX500SSD1 1TB                          | 5        | 0.79%   |
| Unknown SD/MMC/MS PRO 16GB                           | 4        | 0.64%   |
| Seagate ST2000DM001-1CH164 2TB                       | 4        | 0.64%   |
| Seagate ST1000DM003-1SB10C 1TB                       | 4        | 0.64%   |
| Seagate ST1000DM003-1SB102 1TB                       | 4        | 0.64%   |
| Samsung SSD 850 EVO 500GB                            | 4        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 4        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                      | 4        | 0.64%   |
| WDC WD20EARX-00PASB0 2TB                             | 3        | 0.48%   |
| WDC WD1003FZEX-00K3CA0 1TB                           | 3        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                      | 3        | 0.48%   |
| Seagate ST4000VN008-2DR166 4TB                       | 3        | 0.48%   |
| Seagate ST3250310AS 250GB                            | 3        | 0.48%   |
| Seagate ST3000DM008-2DM166 3TB                       | 3        | 0.48%   |
| Seagate ST3000DM001-1ER166 3TB                       | 3        | 0.48%   |
| SanDisk NVMe SSD Drive 1TB                           | 3        | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB                       | 3        | 0.48%   |
| Samsung SSD 970 EVO 1TB                              | 3        | 0.48%   |
| Samsung SSD 840 EVO 500GB                            | 3        | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 3        | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB               | 3        | 0.48%   |
| Samsung HD103SJ 1TB                                  | 3        | 0.48%   |
| PNY CS900 120GB SSD                                  | 3        | 0.48%   |
| Kingston SV300S37A240G 240GB SSD                     | 3        | 0.48%   |
| Kingston SUV400S37240G 240GB SSD                     | 3        | 0.48%   |
| Kingston SUV400S37120G 120GB SSD                     | 3        | 0.48%   |
| Kingston SA2000M81000G 1TB                           | 3        | 0.48%   |
| JMicron Generic 200GB                                | 3        | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 91       | 137    | 40.27%  |
| WDC                 | 73       | 132    | 32.3%   |
| Toshiba             | 19       | 25     | 8.41%   |
| Hitachi             | 11       | 17     | 4.87%   |
| Samsung Electronics | 10       | 16     | 4.42%   |
| Unknown             | 4        | 5      | 1.77%   |
| JMicron Technology  | 3        | 3      | 1.33%   |
| HGST                | 3        | 6      | 1.33%   |
| Maxtor              | 2        | 2      | 0.88%   |
| Fujitsu             | 2        | 2      | 0.88%   |
| Apple               | 2        | 5      | 0.88%   |
| Unknown             | 2        | 4      | 0.88%   |
| USB                 | 1        | 1      | 0.44%   |
| Intenso             | 1        | 2      | 0.44%   |
| Hewlett-Packard     | 1        | 3      | 0.44%   |
| ASMT109x            | 1        | 1      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 63       | 107    | 31.82%  |
| Kingston            | 42       | 59     | 21.21%  |
| Crucial             | 21       | 30     | 10.61%  |
| SanDisk             | 10       | 10     | 5.05%   |
| WDC                 | 7        | 7      | 3.54%   |
| Intenso             | 5        | 5      | 2.53%   |
| Intel               | 5        | 6      | 2.53%   |
| A-DATA Technology   | 5        | 5      | 2.53%   |
| PNY                 | 4        | 4      | 2.02%   |
| OCZ                 | 4        | 4      | 2.02%   |
| Corsair             | 4        | 5      | 2.02%   |
| Micron Technology   | 3        | 4      | 1.52%   |
| Verbatim            | 2        | 5      | 1.01%   |
| Transcend           | 2        | 2      | 1.01%   |
| LITEON              | 2        | 2      | 1.01%   |
| Leven               | 2        | 2      | 1.01%   |
| AFOX                | 2        | 2      | 1.01%   |
| Unknown (CF)        | 1        | 1      | 0.51%   |
| Toshiba             | 1        | 1      | 0.51%   |
| Team                | 1        | 1      | 0.51%   |
| Supersonic          | 1        | 1      | 0.51%   |
| SK hynix            | 1        | 1      | 0.51%   |
| Shark               | 1        | 1      | 0.51%   |
| Patriot             | 1        | 1      | 0.51%   |
| OCZ-VERTEX3         | 1        | 1      | 0.51%   |
| LITEONIT            | 1        | 1      | 0.51%   |
| KingDian            | 1        | 1      | 0.51%   |
| INDMEM              | 1        | 1      | 0.51%   |
| FORESEE             | 1        | 1      | 0.51%   |
| China               | 1        | 1      | 0.51%   |
| ADATA SU            | 1        | 1      | 0.51%   |
| 2-Power             | 1        | 2      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 171      | 361    | 38.69%  |
| SSD     | 160      | 275    | 36.2%   |
| NVMe    | 101      | 153    | 22.85%  |
| Unknown | 8        | 8      | 1.81%   |
| MMC     | 2        | 2      | 0.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 241      | 609    | 64.61%  |
| NVMe | 101      | 153    | 27.08%  |
| SAS  | 29       | 35     | 7.77%   |
| MMC  | 2        | 2      | 0.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 177      | 312    | 47.58%  |
| 0.51-1.0   | 95       | 140    | 25.54%  |
| 1.01-2.0   | 42       | 78     | 11.29%  |
| 2.01-3.0   | 20       | 32     | 5.38%   |
| 4.01-10.0  | 17       | 39     | 4.57%   |
| 3.01-4.0   | 15       | 23     | 4.03%   |
| 10.01-20.0 | 6        | 12     | 1.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 54       | 18%     |
| 101-250        | 50       | 16.67%  |
| 251-500        | 48       | 16%     |
| 1001-2000      | 41       | 13.67%  |
| More than 3000 | 34       | 11.33%  |
| 2001-3000      | 21       | 7%      |
| 1-20           | 19       | 6.33%   |
| Unknown        | 13       | 4.33%   |
| 21-50          | 12       | 4%      |
| 51-100         | 8        | 2.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 93       | 30.69%  |
| 21-50          | 42       | 13.86%  |
| 101-250        | 41       | 13.53%  |
| 501-1000       | 31       | 10.23%  |
| 51-100         | 25       | 8.25%   |
| 251-500        | 23       | 7.59%   |
| More than 3000 | 15       | 4.95%   |
| 1001-2000      | 15       | 4.95%   |
| Unknown        | 13       | 4.29%   |
| 2001-3000      | 5        | 1.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD  | 2        | 4      | 6.25%   |
| Kingston SHPM2280P2H 480G SSD     | 2        | 2      | 6.25%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1      | 3.13%   |
| WDC WD5000AADS-00S9B0 500GB       | 1        | 1      | 3.13%   |
| WDC WD10EZRX-00A8LB0 1TB          | 1        | 1      | 3.13%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 3.13%   |
| WDC WD10EURX-73FH1Y0 1TB          | 1        | 1      | 3.13%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 3.13%   |
| Toshiba DT01ACA050 500GB          | 1        | 1      | 3.13%   |
| Seagate ST380013AS 80GB           | 1        | 1      | 3.13%   |
| Seagate ST3400633AS 400GB         | 1        | 1      | 3.13%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 3.13%   |
| Seagate ST320LT020-9YG142 320GB   | 1        | 1      | 3.13%   |
| Seagate ST3200822AS 200GB         | 1        | 1      | 3.13%   |
| Seagate ST31500341AS 1TB          | 1        | 1      | 3.13%   |
| Seagate ST31000524AS 1TB          | 1        | 1      | 3.13%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 3.13%   |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 1      | 3.13%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 3.13%   |
| SanDisk SDSSDX240GG25 240GB       | 1        | 1      | 3.13%   |
| Samsung Electronics SP0812C 80GB  | 1        | 1      | 3.13%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 3.13%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 3.13%   |
| OCZ AGILITY3 240GB SSD            | 1        | 1      | 3.13%   |
| Leven JAJS300M480C 480GB SSD      | 1        | 1      | 3.13%   |
| Kingston SA400S37480G 480GB SSD   | 1        | 1      | 3.13%   |
| Intel SSDSC2BW480H6 480GB         | 1        | 1      | 3.13%   |
| Hitachi HDT721025SLA380 250GB     | 1        | 1      | 3.13%   |
| Hitachi HDP725032GLA360 320GB     | 1        | 2      | 3.13%   |
| Unknown                           | 1        | 2      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 10     | 29.63%  |
| WDC                 | 5        | 6      | 18.52%  |
| Kingston            | 5        | 7      | 18.52%  |
| Samsung Electronics | 2        | 3      | 7.41%   |
| Toshiba             | 1        | 1      | 3.7%    |
| SanDisk             | 1        | 1      | 3.7%    |
| OCZ                 | 1        | 1      | 3.7%    |
| Leven               | 1        | 1      | 3.7%    |
| Intel               | 1        | 1      | 3.7%    |
| Hitachi             | 1        | 3      | 3.7%    |
| Unknown             | 1        | 2      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 10     | 44.44%  |
| WDC                 | 5        | 6      | 27.78%  |
| Samsung Electronics | 2        | 3      | 11.11%  |
| Toshiba             | 1        | 1      | 5.56%   |
| Hitachi             | 1        | 3      | 5.56%   |
| Unknown             | 1        | 2      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 25     | 63.64%  |
| SSD  | 8        | 11     | 36.36%  |

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
| Detected | 195      | 515    | 60.75%  |
| Works    | 104      | 248    | 32.4%   |
| Malfunc  | 22       | 36     | 6.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 175      | 40.23%  |
| AMD                          | 99       | 22.76%  |
| Samsung Electronics          | 45       | 10.34%  |
| ASMedia Technology           | 21       | 4.83%   |
| SanDisk                      | 15       | 3.45%   |
| Kingston Technology Company  | 15       | 3.45%   |
| Phison Electronics           | 14       | 3.22%   |
| JMicron Technology           | 10       | 2.3%    |
| Nvidia                       | 8        | 1.84%   |
| Marvell Technology Group     | 8        | 1.84%   |
| Micron/Crucial Technology    | 6        | 1.38%   |
| Seagate Technology           | 4        | 0.92%   |
| ADATA Technology             | 4        | 0.92%   |
| SK hynix                     | 3        | 0.69%   |
| VIA Technologies             | 2        | 0.46%   |
| Toshiba America Info Systems | 1        | 0.23%   |
| Silicon Motion               | 1        | 0.23%   |
| Realtek Semiconductor        | 1        | 0.23%   |
| HighPoint Technologies       | 1        | 0.23%   |
| Hewlett-Packard              | 1        | 0.23%   |
| Broadcom / LSI               | 1        | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 63       | 11.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 27       | 5.02%   |
| AMD 400 Series Chipset SATA Controller                                                  | 25       | 4.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 3.9%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 19       | 3.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18       | 3.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 18       | 3.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 2.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12       | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 2.23%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8        | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8        | 1.49%   |
| Phison E12 NVMe Controller                                                              | 8        | 1.49%   |
| Kingston Company A2000 NVMe SSD                                                         | 8        | 1.49%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 1.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.49%   |
| Intel SSD 660P Series                                                                   | 7        | 1.3%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 6        | 1.12%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6        | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.12%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.12%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4        | 0.74%   |
| Kingston Company Company Non-Volatile memory controller                                 | 4        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.74%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.74%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 0.74%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.74%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 0.74%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3        | 0.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 242      | 57.08%  |
| NVMe | 103      | 24.29%  |
| IDE  | 56       | 13.21%  |
| RAID | 22       | 5.19%   |
| SAS  | 1        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 174      | 62.37%  |
| AMD    | 105      | 37.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 10       | 3.57%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 8        | 2.86%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 6        | 2.14%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 6        | 2.14%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 6        | 2.14%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 6        | 2.14%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 5        | 1.79%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 4        | 1.43%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 4        | 1.43%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 4        | 1.43%   |
| Intel Core i5-3350P CPU @ 3.10GHz      | 4        | 1.43%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 4        | 1.43%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 4        | 1.43%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 1.07%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 3        | 1.07%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 3        | 1.07%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 1.07%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 3        | 1.07%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 3        | 1.07%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 3        | 1.07%   |
| AMD Ryzen 3 1200 Quad-Core Processor   | 3        | 1.07%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 0.71%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 2        | 0.71%   |
| Intel Core i7-4770S CPU @ 3.10GHz      | 2        | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 2        | 0.71%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 0.71%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 0.71%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 2        | 0.71%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 2        | 0.71%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 2        | 0.71%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 0.71%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 2        | 0.71%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 2        | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 0.71%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 2        | 0.71%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 0.71%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 2        | 0.71%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz   | 2        | 0.71%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz   | 2        | 0.71%   |
| Intel 12th Gen Core i9-12900K          | 2        | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 53       | 18.93%  |
| Intel Core i7           | 52       | 18.57%  |
| AMD Ryzen 7             | 27       | 9.64%   |
| AMD Ryzen 5             | 23       | 8.21%   |
| AMD Ryzen 9             | 15       | 5.36%   |
| Intel Xeon              | 13       | 4.64%   |
| Intel Core i3           | 12       | 4.29%   |
| Other                   | 11       | 3.93%   |
| Intel Core 2 Duo        | 9        | 3.21%   |
| AMD FX                  | 8        | 2.86%   |
| AMD Ryzen 3             | 5        | 1.79%   |
| Intel Core i9           | 4        | 1.43%   |
| Intel Core 2 Quad       | 4        | 1.43%   |
| Intel Celeron           | 4        | 1.43%   |
| AMD Phenom II X4        | 4        | 1.43%   |
| AMD Athlon 64 X2        | 4        | 1.43%   |
| Intel Pentium           | 3        | 1.07%   |
| Intel Atom              | 3        | 1.07%   |
| AMD Ryzen Threadripper  | 3        | 1.07%   |
| AMD Athlon II X4        | 3        | 1.07%   |
| AMD A8                  | 3        | 1.07%   |
| AMD A6                  | 3        | 1.07%   |
| AMD A10                 | 3        | 1.07%   |
| Intel Pentium Dual-Core | 2        | 0.71%   |
| Intel Core 2            | 2        | 0.71%   |
| Intel Pentium Silver    | 1        | 0.36%   |
| Intel Pentium Dual      | 1        | 0.36%   |
| AMD Phenom II X2        | 1        | 0.36%   |
| AMD GX                  | 1        | 0.36%   |
| AMD E                   | 1        | 0.36%   |
| AMD Athlon II Neo       | 1        | 0.36%   |
| AMD A4                  | 1        | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 114      | 40.71%  |
| 2      | 51       | 18.21%  |
| 6      | 49       | 17.5%   |
| 8      | 37       | 13.21%  |
| 12     | 13       | 4.64%   |
| 16     | 8        | 2.86%   |
| 10     | 3        | 1.07%   |
| 1      | 2        | 0.71%   |
| 64     | 1        | 0.36%   |
| 32     | 1        | 0.36%   |
| 24     | 1        | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 277      | 99.28%  |
| 2      | 2        | 0.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 172      | 61.65%  |
| 1      | 107      | 38.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 275      | 97.52%  |
| Unknown        | 7        | 2.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 62       | 21.38%  |
| 0x306c3    | 22       | 7.59%   |
| 0x506e3    | 15       | 5.17%   |
| 0x206a7    | 15       | 5.17%   |
| 0x306a9    | 14       | 4.83%   |
| 0x0800820d | 10       | 3.45%   |
| 0x906ea    | 9        | 3.1%    |
| 0x08701021 | 9        | 3.1%    |
| 0x1067a    | 8        | 2.76%   |
| 0x08701013 | 7        | 2.41%   |
| 0x08001138 | 7        | 2.41%   |
| 0x906e9    | 6        | 2.07%   |
| 0x90672    | 6        | 2.07%   |
| 0x0a201009 | 6        | 2.07%   |
| 0x906ed    | 5        | 1.72%   |
| 0x06000852 | 5        | 1.72%   |
| 0x010000c8 | 5        | 1.72%   |
| 0xa0653    | 4        | 1.38%   |
| 0x906ec    | 4        | 1.38%   |
| 0xa0655    | 3        | 1.03%   |
| 0x6fd      | 3        | 1.03%   |
| 0x106e5    | 3        | 1.03%   |
| 0x0a201205 | 3        | 1.03%   |
| 0xa0671    | 2        | 0.69%   |
| 0x6f6      | 2        | 0.69%   |
| 0x206c2    | 2        | 0.69%   |
| 0x10676    | 2        | 0.69%   |
| 0x0a601203 | 2        | 0.69%   |
| 0x0a50000c | 2        | 0.69%   |
| 0x08600106 | 2        | 0.69%   |
| 0x08108109 | 2        | 0.69%   |
| 0x08001137 | 2        | 0.69%   |
| 0x08001129 | 2        | 0.69%   |
| 0x06003106 | 2        | 0.69%   |
| 0x06001119 | 2        | 0.69%   |
| 0x0600063e | 2        | 0.69%   |
| 0x010000db | 2        | 0.69%   |
| 0x906eb    | 1        | 0.34%   |
| 0x906c0    | 1        | 0.34%   |
| 0x806ea    | 1        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 34       | 12.14%  |
| Zen 2            | 30       | 10.71%  |
| Haswell          | 30       | 10.71%  |
| IvyBridge        | 20       | 7.14%   |
| Skylake          | 19       | 6.79%   |
| SandyBridge      | 17       | 6.07%   |
| Zen 3            | 15       | 5.36%   |
| Zen+             | 13       | 4.64%   |
| Penryn           | 13       | 4.64%   |
| Zen              | 12       | 4.29%   |
| Piledriver       | 9        | 3.21%   |
| K10              | 9        | 3.21%   |
| Unknown          | 8        | 2.86%   |
| CometLake        | 7        | 2.5%    |
| Core             | 6        | 2.14%   |
| Nehalem          | 5        | 1.79%   |
| Alderlake Hybrid | 5        | 1.79%   |
| Westmere         | 4        | 1.43%   |
| K8 Hammer        | 4        | 1.43%   |
| Steamroller      | 3        | 1.07%   |
| Puma             | 2        | 0.71%   |
| Jaguar           | 2        | 0.71%   |
| Icelake          | 2        | 0.71%   |
| Bulldozer        | 2        | 0.71%   |
| Broadwell        | 2        | 0.71%   |
| Bonnell          | 2        | 0.71%   |
| Silvermont       | 1        | 0.36%   |
| Goldmont plus    | 1        | 0.36%   |
| Goldmont         | 1        | 0.36%   |
| Excavator        | 1        | 0.36%   |
| Bobcat           | 1        | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 158      | 51.8%   |
| AMD                        | 78       | 25.57%  |
| Intel                      | 67       | 21.97%  |
| Matrox Electronics Systems | 1        | 0.33%   |
| ASPEED Technology          | 1        | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 3.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 12       | 3.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 3.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 2.88%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 8        | 2.56%   |
| Intel HD Graphics 530                                                       | 7        | 2.24%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.92%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 1.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 1.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.92%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.6%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 1.6%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.6%    |
| Intel HD Graphics 630                                                       | 5        | 1.6%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 1.6%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 1.28%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 4        | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.28%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 1.28%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.28%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.96%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 0.96%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 3        | 0.96%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 3        | 0.96%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.96%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.96%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.96%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 0.96%   |
| Intel AlderLake-S GT1                                                       | 3        | 0.96%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 3        | 0.96%   |
| AMD Raphael                                                                 | 3        | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 0.96%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.64%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.64%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 146      | 51.96%  |
| 1 x AMD         | 66       | 23.49%  |
| 1 x Intel       | 48       | 17.08%  |
| Intel + Nvidia  | 6        | 2.14%   |
| 2 x AMD         | 5        | 1.78%   |
| Intel + AMD     | 3        | 1.07%   |
| AMD + Nvidia    | 3        | 1.07%   |
| 2 x Nvidia      | 2        | 0.71%   |
| Nvidia + ASPEED | 1        | 0.36%   |
| 1 x Matrox      | 1        | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 179      | 61.94%  |
| Proprietary | 101      | 34.95%  |
| Unknown     | 9        | 3.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 99       | 34.38%  |
| 1.01-2.0   | 59       | 20.49%  |
| 7.01-8.0   | 41       | 14.24%  |
| 3.01-4.0   | 21       | 7.29%   |
| 5.01-6.0   | 20       | 6.94%   |
| 0.01-0.5   | 19       | 6.6%    |
| 0.51-1.0   | 15       | 5.21%   |
| 8.01-16.0  | 10       | 3.47%   |
| 2.01-3.0   | 2        | 0.69%   |
| 4.01-5.0   | 1        | 0.35%   |
| 16.01-24.0 | 1        | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 67       | 21.07%  |
| Dell                    | 31       | 9.75%   |
| AOC                     | 22       | 6.92%   |
| Ancor Communications    | 22       | 6.92%   |
| Philips                 | 19       | 5.97%   |
| Hewlett-Packard         | 19       | 5.97%   |
| Acer                    | 19       | 5.97%   |
| BenQ                    | 17       | 5.35%   |
| ASUSTek Computer        | 14       | 4.4%    |
| Goldstar                | 13       | 4.09%   |
| Lenovo                  | 10       | 3.14%   |
| Sony                    | 8        | 2.52%   |
| Unknown                 | 6        | 1.89%   |
| Medion                  | 5        | 1.57%   |
| Lenovo Group Limited    | 5        | 1.57%   |
| LG Electronics          | 4        | 1.26%   |
| IBM                     | 3        | 0.94%   |
| ViewSonic               | 2        | 0.63%   |
| Vestel Elektronik       | 2        | 0.63%   |
| Tech Concepts           | 2        | 0.63%   |
| MSI                     | 2        | 0.63%   |
| Idek Iiyama             | 2        | 0.63%   |
| Gigabyte Technology     | 2        | 0.63%   |
| Fujitsu Siemens         | 2        | 0.63%   |
| AUS                     | 2        | 0.63%   |
| Unknown                 | 2        | 0.63%   |
| Wacom                   | 1        | 0.31%   |
| Vestel                  | 1        | 0.31%   |
| TopView                 | 1        | 0.31%   |
| Pixio                   | 1        | 0.31%   |
| Pioneer                 | 1        | 0.31%   |
| Panasonic               | 1        | 0.31%   |
| Packard Bell            | 1        | 0.31%   |
| OTC                     | 1        | 0.31%   |
| OEM                     | 1        | 0.31%   |
| Iiyama                  | 1        | 0.31%   |
| IFS                     | 1        | 0.31%   |
| Eizo                    | 1        | 0.31%   |
| Chi Mei Optoelectronics | 1        | 0.31%   |
| AU Optronics            | 1        | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6        | 1.67%   |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                     | 4        | 1.11%   |
| Sony TV SNYEE01 1920x1080                                             | 3        | 0.83%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3        | 0.83%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                     | 3        | 0.83%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3        | 0.83%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 3        | 0.83%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 2        | 0.56%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                      | 2        | 0.56%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch  | 2        | 0.56%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 2        | 0.56%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2        | 0.56%   |
| Samsung Electronics LCD Monitor LF27T35 1920x1080                     | 2        | 0.56%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 2        | 0.56%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2        | 0.56%   |
| Medion MD20444 MED3661 1920x1080 521x293mm 23.5-inch                  | 2        | 0.56%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 2        | 0.56%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch              | 2        | 0.56%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 2        | 0.56%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch       | 2        | 0.56%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 2        | 0.56%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                     | 2        | 0.56%   |
| Dell P1913 DELA089 1440x900 408x255mm 18.9-inch                       | 2        | 0.56%   |
| Dell 2407WFP DELA017 1920x1200 519x324mm 24.1-inch                    | 2        | 0.56%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 2        | 0.56%   |
| BenQ G2420HDB BNQ7842 1920x1080 477x268mm 21.5-inch                   | 2        | 0.56%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 2        | 0.56%   |
| ASUSTek Computer VA249 AUS24C1 1920x1080 527x296mm 23.8-inch          | 2        | 0.56%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 0.56%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                     | 2        | 0.56%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                      | 2        | 0.56%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 2        | 0.56%   |
| AOC 2450W AOC2450 1920x1080 520x290mm 23.4-inch                       | 2        | 0.56%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 2        | 0.56%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2        | 0.56%   |
| Ancor Communications ASUS VP278 ACI27C8 1920x1080 598x336mm 27.0-inch | 2        | 0.56%   |
| Unknown                                                               | 2        | 0.56%   |
| Wacom Cintiq 16 WAC1064 1920x1080 344x193mm 15.5-inch                 | 1        | 0.28%   |
| ViewSonic VX2880ML VSCCE2F 3840x2160 621x341mm 27.9-inch              | 1        | 0.28%   |
| ViewSonic VG2236 SERIES VSCE726 1920x1080 477x268mm 21.5-inch         | 1        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 144      | 46.01%  |
| 2560x1440 (QHD)    | 37       | 11.82%  |
| 3840x2160 (4K)     | 34       | 10.86%  |
| Unknown            | 16       | 5.11%   |
| 1680x1050 (WSXGA+) | 15       | 4.79%   |
| 1280x1024 (SXGA)   | 13       | 4.15%   |
| 3440x1440          | 8        | 2.56%   |
| 3840x1080          | 6        | 1.92%   |
| 1440x900 (WXGA+)   | 6        | 1.92%   |
| 1920x1200 (WUXGA)  | 5        | 1.6%    |
| 1600x900 (HD+)     | 5        | 1.6%    |
| 1360x768           | 3        | 0.96%   |
| 3840x1200          | 2        | 0.64%   |
| 1920x540           | 2        | 0.64%   |
| 9840x3840          | 1        | 0.32%   |
| 6400x2160          | 1        | 0.32%   |
| 5760x1440          | 1        | 0.32%   |
| 5760x1080          | 1        | 0.32%   |
| 5120x1440          | 1        | 0.32%   |
| 4608x1440          | 1        | 0.32%   |
| 4480x1440          | 1        | 0.32%   |
| 3840x1600          | 1        | 0.32%   |
| 3200x1200          | 1        | 0.32%   |
| 3200x1080          | 1        | 0.32%   |
| 2560x1600          | 1        | 0.32%   |
| 2560x1080          | 1        | 0.32%   |
| 2560x1024          | 1        | 0.32%   |
| 2048x1152          | 1        | 0.32%   |
| 1600x1200          | 1        | 0.32%   |
| 1366x768 (WXGA)    | 1        | 0.32%   |
| 1360x765           | 1        | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 59       | 18.73%  |
| 24      | 55       | 17.46%  |
| Unknown | 48       | 15.24%  |
| 23      | 37       | 11.75%  |
| 31      | 22       | 6.98%   |
| 21      | 18       | 5.71%   |
| 19      | 14       | 4.44%   |
| 22      | 11       | 3.49%   |
| 20      | 9        | 2.86%   |
| 72      | 7        | 2.22%   |
| 34      | 7        | 2.22%   |
| 84      | 4        | 1.27%   |
| 32      | 4        | 1.27%   |
| 15      | 3        | 0.95%   |
| 28      | 2        | 0.63%   |
| 17      | 2        | 0.63%   |
| 65      | 1        | 0.32%   |
| 60      | 1        | 0.32%   |
| 54      | 1        | 0.32%   |
| 48      | 1        | 0.32%   |
| 42      | 1        | 0.32%   |
| 39      | 1        | 0.32%   |
| 38      | 1        | 0.32%   |
| 35      | 1        | 0.32%   |
| 33      | 1        | 0.32%   |
| 30      | 1        | 0.32%   |
| 29      | 1        | 0.32%   |
| 25      | 1        | 0.32%   |
| 18      | 1        | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 128      | 42.81%  |
| Unknown     | 48       | 16.05%  |
| 401-500     | 44       | 14.72%  |
| 601-700     | 34       | 11.37%  |
| 701-800     | 12       | 4.01%   |
| 1501-2000   | 11       | 3.68%   |
| 351-400     | 9        | 3.01%   |
| 301-350     | 5        | 1.67%   |
| 1001-1500   | 4        | 1.34%   |
| 801-900     | 3        | 1%      |
| 901-1000    | 1        | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 181      | 63.96%  |
| Unknown | 43       | 15.19%  |
| 16/10   | 33       | 11.66%  |
| 5/4     | 11       | 3.89%   |
| 21/9    | 10       | 3.53%   |
| 4/3     | 2        | 0.71%   |
| 32/9    | 2        | 0.71%   |
| 3/2     | 1        | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 96       | 30.87%  |
| 301-350        | 59       | 18.97%  |
| Unknown        | 48       | 15.43%  |
| 351-500        | 38       | 12.22%  |
| 151-200        | 27       | 8.68%   |
| 251-300        | 20       | 6.43%   |
| More than 1000 | 14       | 4.5%    |
| 501-1000       | 4        | 1.29%   |
| 141-150        | 2        | 0.64%   |
| 101-110        | 2        | 0.64%   |
| 111-120        | 1        | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 170      | 58.62%  |
| 101-120 | 48       | 16.55%  |
| Unknown | 48       | 16.55%  |
| 121-160 | 12       | 4.14%   |
| 1-50    | 9        | 3.1%    |
| 161-240 | 3        | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 195      | 68.9%   |
| 2     | 64       | 22.61%  |
| 0     | 15       | 5.3%    |
| 3     | 9        | 3.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 168      | 41.58%  |
| Intel                           | 131      | 32.43%  |
| Broadcom                        | 15       | 3.71%   |
| Qualcomm Atheros                | 14       | 3.47%   |
| Nvidia                          | 8        | 1.98%   |
| Ralink Technology               | 6        | 1.49%   |
| Ralink                          | 6        | 1.49%   |
| TP-Link                         | 5        | 1.24%   |
| ASUSTek Computer                | 5        | 1.24%   |
| Qualcomm Atheros Communications | 4        | 0.99%   |
| MediaTek                        | 4        | 0.99%   |
| IMC Networks                    | 4        | 0.99%   |
| Huawei Technologies             | 4        | 0.99%   |
| Aquantia                        | 4        | 0.99%   |
| OnePlus Technology (Shenzhen)   | 3        | 0.74%   |
| Edimax Technology               | 3        | 0.74%   |
| D-Link                          | 3        | 0.74%   |
| Samsung Electronics             | 2        | 0.5%    |
| NetGear                         | 2        | 0.5%    |
| Microsoft                       | 2        | 0.5%    |
| Unknown                         | 1        | 0.25%   |
| Texas Instruments               | 1        | 0.25%   |
| Solarflare Communications       | 1        | 0.25%   |
| Linksys                         | 1        | 0.25%   |
| Lenovo                          | 1        | 0.25%   |
| JMicron Technology              | 1        | 0.25%   |
| InterBiometrics                 | 1        | 0.25%   |
| ICS Advent                      | 1        | 0.25%   |
| HMD Global                      | 1        | 0.25%   |
| D-Link System                   | 1        | 0.25%   |
| ASIX Electronics                | 1        | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133      | 28.73%  |
| Intel I211 Gigabit Network Connection                             | 24       | 5.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19       | 4.1%    |
| Intel Ethernet Connection (2) I219-V                              | 18       | 3.89%   |
| Intel Wi-Fi 6 AX200                                               | 14       | 3.02%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 2.16%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 2.16%   |
| Intel Ethernet Controller I225-V                                  | 9        | 1.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9        | 1.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 8        | 1.73%   |
| Intel Wireless-AC 9260                                            | 7        | 1.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 1.51%   |
| Realtek 802.11ac NIC                                              | 4        | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 0.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.86%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]              | 4        | 0.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3        | 0.65%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 3        | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.65%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3        | 0.65%   |
| OnePlus (Shenzhen) Android                                        | 3        | 0.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 0.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.65%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.65%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.65%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 47       | 33.81%  |
| Realtek Semiconductor           | 27       | 19.42%  |
| Broadcom                        | 11       | 7.91%   |
| Qualcomm Atheros                | 9        | 6.47%   |
| Ralink Technology               | 6        | 4.32%   |
| Ralink                          | 6        | 4.32%   |
| TP-Link                         | 5        | 3.6%    |
| ASUSTek Computer                | 5        | 3.6%    |
| Qualcomm Atheros Communications | 4        | 2.88%   |
| IMC Networks                    | 4        | 2.88%   |
| MediaTek                        | 3        | 2.16%   |
| Edimax Technology               | 3        | 2.16%   |
| D-Link                          | 3        | 2.16%   |
| NetGear                         | 2        | 1.44%   |
| Microsoft                       | 2        | 1.44%   |
| Linksys                         | 1        | 0.72%   |
| D-Link System                   | 1        | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 14       | 9.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 9        | 6.29%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 8        | 5.59%   |
| Intel Wireless-AC 9260                                                               | 7        | 4.9%    |
| Realtek 802.11ac NIC                                                                 | 4        | 2.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 2.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 4        | 2.8%    |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                 | 4        | 2.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 3        | 2.1%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 2.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 2.1%    |
| Ralink RT5370 Wireless Adapter                                                       | 3        | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 3        | 2.1%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 3        | 2.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 3        | 2.1%    |
| TP-Link 802.11ac WLAN Adapter                                                        | 2        | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.4%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 1.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 1.4%    |
| Ralink MT7601U Wireless Adapter                                                      | 2        | 1.4%    |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 1.4%    |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 1.4%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 2        | 1.4%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 2        | 1.4%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 0.7%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 0.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1        | 0.7%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1        | 0.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 1        | 0.7%    |
| TP-Link 802.11ac NIC                                                                 | 1        | 0.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.7%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                      | 1        | 0.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                           | 1        | 0.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 1        | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.7%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 1        | 0.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 1        | 0.7%    |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 0.7%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 157      | 51.64%  |
| Intel                         | 111      | 36.51%  |
| Nvidia                        | 8        | 2.63%   |
| Qualcomm Atheros              | 6        | 1.97%   |
| Broadcom                      | 4        | 1.32%   |
| Aquantia                      | 4        | 1.32%   |
| OnePlus Technology (Shenzhen) | 3        | 0.99%   |
| Samsung Electronics           | 2        | 0.66%   |
| Huawei Technologies           | 2        | 0.66%   |
| Solarflare Communications     | 1        | 0.33%   |
| MediaTek                      | 1        | 0.33%   |
| Lenovo                        | 1        | 0.33%   |
| JMicron Technology            | 1        | 0.33%   |
| ICS Advent                    | 1        | 0.33%   |
| HMD Global                    | 1        | 0.33%   |
| ASIX Electronics              | 1        | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133      | 42.22%  |
| Intel I211 Gigabit Network Connection                             | 24       | 7.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19       | 6.03%   |
| Intel Ethernet Connection (2) I219-V                              | 18       | 5.71%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 3.17%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 3.17%   |
| Intel Ethernet Controller I225-V                                  | 9        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 2.22%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.27%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.95%   |
| OnePlus (Shenzhen) Android                                        | 3        | 0.95%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.95%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.95%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.63%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.63%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.63%   |
| Huawei MLA-L11                                                    | 2        | 0.63%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.32%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.32%   |
| Nvidia MCP79 Ethernet                                             | 1        | 0.32%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.32%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.32%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.32%   |
| MediaTek moto e(6) plus                                           | 1        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 277      | 66.75%  |
| WiFi     | 133      | 32.05%  |
| Modem    | 4        | 0.96%   |
| Unknown  | 1        | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 227      | 77.21%  |
| WiFi     | 67       | 22.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 162      | 57.86%  |
| 2     | 99       | 35.36%  |
| 3     | 15       | 5.36%   |
| 0     | 3        | 1.07%   |
| 4     | 1        | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 269      | 96.07%  |
| Yes  | 11       | 3.93%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 46       | 46%     |
| Cambridge Silicon Radio         | 26       | 26%     |
| ASUSTek Computer                | 7        | 7%      |
| Qualcomm Atheros Communications | 4        | 4%      |
| IMC Networks                    | 4        | 4%      |
| Broadcom                        | 4        | 4%      |
| MediaTek                        | 3        | 3%      |
| Realtek Semiconductor           | 2        | 2%      |
| Belkin Components               | 2        | 2%      |
| HTC (High Tech Computer)        | 1        | 1%      |
| Edimax Technology               | 1        | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 26       | 26%     |
| Intel AX200 Bluetooth                                                | 12       | 12%     |
| Intel Wireless-AC 3168 Bluetooth                                     | 9        | 9%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 7        | 7%      |
| Intel Bluetooth wireless interface                                   | 5        | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 5        | 5%      |
| MediaTek Wireless_Device                                             | 3        | 3%      |
| Intel AX210 Bluetooth                                                | 3        | 3%      |
| Intel AX201 Bluetooth                                                | 3        | 3%      |
| IMC Networks Bluetooth Radio                                         | 3        | 3%      |
| ASUS ASUS USB-BT500                                                  | 3        | 3%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2        | 2%      |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 2%      |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 2        | 2%      |
| ASUS Bluetooth Radio                                                 | 2        | 2%      |
| Realtek RTL8821A Bluetooth                                           | 1        | 1%      |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 1%      |
| Intel Bluetooth Device                                               | 1        | 1%      |
| IMC Networks Bluetooth Device                                        | 1        | 1%      |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1%      |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 1%      |
| Broadcom HP Portable Bumble Bee                                      | 1        | 1%      |
| Broadcom BCM2045 Bluetooth                                           | 1        | 1%      |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 1%      |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 158      | 29.42%  |
| Nvidia                  | 155      | 28.86%  |
| AMD                     | 125      | 23.28%  |
| SteelSeries ApS         | 14       | 2.61%   |
| Kingston Technology     | 11       | 2.05%   |
| C-Media Electronics     | 10       | 1.86%   |
| Logitech                | 7        | 1.3%    |
| Creative Technology     | 7        | 1.3%    |
| ASUSTek Computer        | 7        | 1.3%    |
| Creative Labs           | 6        | 1.12%   |
| GN Netcom               | 5        | 0.93%   |
| Yamaha                  | 2        | 0.37%   |
| VIA Technologies        | 2        | 0.37%   |
| Texas Instruments       | 2        | 0.37%   |
| Realtek Semiconductor   | 2        | 0.37%   |
| Razer USA               | 2        | 0.37%   |
| Focusrite-Novation      | 2        | 0.37%   |
| XMOS                    | 1        | 0.19%   |
| Unknown                 | 1        | 0.19%   |
| Turtle Beach            | 1        | 0.19%   |
| Tenx Technology         | 1        | 0.19%   |
| Syntek                  | 1        | 0.19%   |
| Sony                    | 1        | 0.19%   |
| Shure                   | 1        | 0.19%   |
| RODE Microphones        | 1        | 0.19%   |
| ROCCAT                  | 1        | 0.19%   |
| Musical Fidelity        | 1        | 0.19%   |
| JMTek                   | 1        | 0.19%   |
| Jieli Technology        | 1        | 0.19%   |
| GYROCOM C&C             | 1        | 0.19%   |
| Corsair                 | 1        | 0.19%   |
| Clavia DMI AB           | 1        | 0.19%   |
| BEHRINGER International | 1        | 0.19%   |
| B & W Group             | 1        | 0.19%   |
| Audio-Technica          | 1        | 0.19%   |
| Astro Gaming            | 1        | 0.19%   |
| Antlion Audio           | 1        | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 38       | 6.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22       | 3.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 21       | 3.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18       | 2.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 18       | 2.98%   |
| Intel 200 Series PCH HD Audio                                              | 17       | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16       | 2.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 14       | 2.31%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14       | 2.31%   |
| Nvidia GP104 High Definition Audio Controller                              | 14       | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 2.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14       | 2.31%   |
| AMD Navi 10 HDMI Audio                                                     | 13       | 2.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13       | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 12       | 1.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 1.82%   |
| Nvidia TU104 HD Audio Controller                                           | 10       | 1.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 9        | 1.49%   |
| AMD FCH Azalia Controller                                                  | 9        | 1.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.32%   |
| Nvidia GK104 HDMI Audio Controller                                         | 8        | 1.32%   |
| Kingston Technology HyperX 7.1 Audio                                       | 8        | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8        | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 1.16%   |
| Nvidia GM204 High Definition Audio Controller                              | 7        | 1.16%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7        | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                              | 7        | 1.16%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 0.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 0.99%   |
| ASUSTek Computer USB Audio                                                 | 6        | 0.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 0.99%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 5        | 0.83%   |
| Nvidia GP102 HDMI Audio Controller                                         | 5        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                   | 5        | 0.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 5        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 37       | 23.27%  |
| Kingston            | 29       | 18.24%  |
| G.Skill             | 22       | 13.84%  |
| Unknown             | 17       | 10.69%  |
| Samsung Electronics | 17       | 10.69%  |
| Crucial             | 12       | 7.55%   |
| SK hynix            | 8        | 5.03%   |
| Micron Technology   | 8        | 5.03%   |
| Ramaxel Technology  | 3        | 1.89%   |
| Nanya Technology    | 2        | 1.26%   |
| Unknown             | 2        | 1.26%   |
| Unifosa             | 1        | 0.63%   |
| Elpida              | 1        | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 7        | 4.14%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 4        | 2.37%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 4        | 2.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 2        | 1.18%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                  | 2        | 1.18%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 2        | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s | 2        | 1.18%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s      | 2        | 1.18%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 2        | 1.18%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 2        | 1.18%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 2        | 1.18%   |
| Kingston RAM KF556C36-16 16GB DIMM 6400MT/s              | 2        | 1.18%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s         | 2        | 1.18%   |
| Kingston RAM HP24D4U7S8MBP-8 8192MB DIMM DDR4 2400MT/s   | 2        | 1.18%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 2        | 1.18%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 2        | 1.18%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 2        | 1.18%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 2        | 1.18%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 2        | 1.18%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s      | 2        | 1.18%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 2        | 1.18%   |
| Unknown                                                  | 2        | 1.18%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 0.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s                 | 1        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                     | 1        | 0.59%   |
| Unknown RAM Module 4096MB DIMM                           | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 1        | 0.59%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s               | 1        | 0.59%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s       | 1        | 0.59%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s        | 1        | 0.59%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.59%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.59%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 0.59%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR 667MT/s     | 1        | 0.59%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 77       | 53.85%  |
| DDR3    | 41       | 28.67%  |
| Unknown | 10       | 6.99%   |
| DDR5    | 7        | 4.9%    |
| SDRAM   | 6        | 4.2%    |
| DDR     | 2        | 1.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 131      | 92.91%  |
| SODIMM | 10       | 7.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 67       | 44.37%  |
| 16384 | 30       | 19.87%  |
| 4096  | 29       | 19.21%  |
| 2048  | 16       | 10.6%   |
| 32768 | 6        | 3.97%   |
| 1024  | 2        | 1.32%   |
| 512   | 1        | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 29       | 18.71%  |
| 3600    | 15       | 9.68%   |
| 3200    | 15       | 9.68%   |
| 1333    | 15       | 9.68%   |
| 2400    | 11       | 7.1%    |
| 3400    | 7        | 4.52%   |
| 2667    | 7        | 4.52%   |
| 3466    | 6        | 3.87%   |
| 2133    | 5        | 3.23%   |
| 5200    | 3        | 1.94%   |
| 3666    | 3        | 1.94%   |
| 3000    | 3        | 1.94%   |
| 2933    | 3        | 1.94%   |
| 667     | 3        | 1.94%   |
| 6400    | 2        | 1.29%   |
| 4800    | 2        | 1.29%   |
| 3500    | 2        | 1.29%   |
| 2048    | 2        | 1.29%   |
| 1867    | 2        | 1.29%   |
| Unknown | 2        | 1.29%   |
| 20306   | 1        | 0.65%   |
| 4400    | 1        | 0.65%   |
| 4000    | 1        | 0.65%   |
| 3800    | 1        | 0.65%   |
| 3733    | 1        | 0.65%   |
| 3534    | 1        | 0.65%   |
| 3533    | 1        | 0.65%   |
| 3333    | 1        | 0.65%   |
| 3266    | 1        | 0.65%   |
| 3100    | 1        | 0.65%   |
| 2733    | 1        | 0.65%   |
| 2666    | 1        | 0.65%   |
| 1866    | 1        | 0.65%   |
| 1800    | 1        | 0.65%   |
| 1639    | 1        | 0.65%   |
| 1334    | 1        | 0.65%   |
| 1066    | 1        | 0.65%   |
| 533     | 1        | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 50%     |
| Brother Industries  | 5        | 35.71%  |
| Prolific Technology | 1        | 7.14%   |
| Canon               | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Brother DCP-J140W                  | 2        | 14.29%  |
| Prolific PL2305 Parallel Port      | 1        | 7.14%   |
| HP LaserJet 1020                   | 1        | 7.14%   |
| HP ENVY Photo 6200 series          | 1        | 7.14%   |
| HP ENVY 4520 series                | 1        | 7.14%   |
| HP Deskjet D4300 series            | 1        | 7.14%   |
| HP DeskJet 5940                    | 1        | 7.14%   |
| HP DeskJet 5550                    | 1        | 7.14%   |
| HP DeskJet 2620 All-in-One Printer | 1        | 7.14%   |
| Canon iP7200 series                | 1        | 7.14%   |
| Brother HL-5250DN Printer          | 1        | 7.14%   |
| Brother HL-2240D series            | 1        | 7.14%   |
| Brother HL-2030 Laser Printer      | 1        | 7.14%   |

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
| 0     | 235      | 82.75%  |
| 1     | 36       | 12.68%  |
| 2     | 8        | 2.82%   |
| 3     | 3        | 1.06%   |
| 6     | 1        | 0.35%   |
| 4     | 1        | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 14       | 23.33%  |
| Graphics card            | 14       | 23.33%  |
| Sound                    | 7        | 11.67%  |
| Communication controller | 7        | 11.67%  |
| Multimedia controller    | 6        | 10%     |
| Unassigned class         | 4        | 6.67%   |
| Storage/raid             | 2        | 3.33%   |
| Card reader              | 2        | 3.33%   |
| Network                  | 1        | 1.67%   |
| Net/ethernet             | 1        | 1.67%   |
| Chipcard                 | 1        | 1.67%   |
| Camera                   | 1        | 1.67%   |

