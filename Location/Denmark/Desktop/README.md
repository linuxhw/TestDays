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

Total: 465

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| ASUSTek       | Z170-P                      | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| HP            | 339A                        | [1be48a395d](https://linux-hardware.org/?probe=1be48a395d) | Apr 21, 2023 |
| Acer          | Aspire XC-230               | [d31e8d7c7d](https://linux-hardware.org/?probe=d31e8d7c7d) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [ebdd0f2a6a](https://linux-hardware.org/?probe=ebdd0f2a6a) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | [878d249691](https://linux-hardware.org/?probe=878d249691) | Apr 18, 2023 |
| Pegatron      | 2AD5                        | [245db62c73](https://linux-hardware.org/?probe=245db62c73) | Apr 18, 2023 |
| Pegatron      | 2AD5                        | [ad23efbf03](https://linux-hardware.org/?probe=ad23efbf03) | Apr 14, 2023 |
| HP            | 339A                        | [57e1af32cd](https://linux-hardware.org/?probe=57e1af32cd) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [1bf207dfca](https://linux-hardware.org/?probe=1bf207dfca) | Apr 13, 2023 |
| Lenovo        | NO DPK                      | [4d84f3549a](https://linux-hardware.org/?probe=4d84f3549a) | Apr 13, 2023 |
| MSI           | 970 GAMING                  | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [32c138c982](https://linux-hardware.org/?probe=32c138c982) | Mar 31, 2023 |
| HP            | 3398                        | [ed9f84a231](https://linux-hardware.org/?probe=ed9f84a231) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d1e1b40549](https://linux-hardware.org/?probe=d1e1b40549) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bcd49e85cb](https://linux-hardware.org/?probe=bcd49e85cb) | Mar 27, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [c722a5f7b2](https://linux-hardware.org/?probe=c722a5f7b2) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [56854770ba](https://linux-hardware.org/?probe=56854770ba) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [62a95efc48](https://linux-hardware.org/?probe=62a95efc48) | Mar 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASUSTek       | PRIME X570-P                | [8681f176da](https://linux-hardware.org/?probe=8681f176da) | Mar 17, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [f3bb3c5ef1](https://linux-hardware.org/?probe=f3bb3c5ef1) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [fc7d8aee1f](https://linux-hardware.org/?probe=fc7d8aee1f) | Mar 16, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| Acer          | Aspire X1935                | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| ASRock        | X570M Pro4                  | [d3ac8dd45f](https://linux-hardware.org/?probe=d3ac8dd45f) | Mar 11, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [fd33b65218](https://linux-hardware.org/?probe=fd33b65218) | Mar 04, 2023 |
| ASUSTek       | SABERTOOTH P67              | [80720d46a2](https://linux-hardware.org/?probe=80720d46a2) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH P67              | [dd01af3afe](https://linux-hardware.org/?probe=dd01af3afe) | Mar 03, 2023 |
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


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 42       | 12.73%  |
| Ubuntu 18.04       | 30       | 9.09%   |
| Arch Rolling       | 16       | 4.85%   |
| Zorin 16           | 13       | 3.94%   |
| OpenMandriva 4.2   | 13       | 3.94%   |
| Ubuntu 22.04       | 11       | 3.33%   |
| Pop!_OS 22.04      | 9        | 2.73%   |
| Pop!_OS 21.04      | 7        | 2.12%   |
| OpenMandriva 4.3   | 7        | 2.12%   |
| Manjaro            | 7        | 2.12%   |
| Linux Mint 20.2    | 7        | 2.12%   |
| Debian 11          | 7        | 2.12%   |
| Linux Mint 21.1    | 6        | 1.82%   |
| Ubuntu 22.10       | 5        | 1.52%   |
| Ubuntu 20.10       | 5        | 1.52%   |
| Ubuntu 19.04       | 5        | 1.52%   |
| Pop!_OS 20.10      | 5        | 1.52%   |
| Linux Mint 20.3    | 5        | 1.52%   |
| Linux Mint 20.1    | 5        | 1.52%   |
| Zorin 15           | 4        | 1.21%   |
| Ubuntu 21.10       | 4        | 1.21%   |
| KDE neon 20.04     | 4        | 1.21%   |
| Ubuntu 19.10       | 3        | 0.91%   |
| Pop!_OS 21.10      | 3        | 0.91%   |
| OpenMandriva 23.03 | 3        | 0.91%   |
| Linux Mint 20      | 3        | 0.91%   |
| Fedora 36          | 3        | 0.91%   |
| Fedora 32          | 3        | 0.91%   |
| Debian 10          | 3        | 0.91%   |
| Ubuntu MATE 22.04  | 2        | 0.61%   |
| Ubuntu MATE 20.04  | 2        | 0.61%   |
| Ubuntu 16.04       | 2        | 0.61%   |
| Pop!_OS 20.04      | 2        | 0.61%   |
| Manjaro 21.2.0     | 2        | 0.61%   |
| Manjaro 20.0.3     | 2        | 0.61%   |
| Manjaro 20.0.1     | 2        | 0.61%   |
| Linux Mint 19.3    | 2        | 0.61%   |
| Linux Mint 19.2    | 2        | 0.61%   |
| Linux Mint 19.1    | 2        | 0.61%   |
| Kubuntu 20.04      | 2        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 106      | 33.76%  |
| Linux Mint   | 31       | 9.87%   |
| Pop!_OS      | 26       | 8.28%   |
| OpenMandriva | 24       | 7.64%   |
| Arch         | 18       | 5.73%   |
| Zorin        | 17       | 5.41%   |
| Manjaro      | 17       | 5.41%   |
| Fedora       | 16       | 5.1%    |
| Debian       | 14       | 4.46%   |
| Kubuntu      | 6        | 1.91%   |
| KDE neon     | 6        | 1.91%   |
| Ubuntu MATE  | 4        | 1.27%   |
| ArcoLinux    | 4        | 1.27%   |
| ROSA         | 3        | 0.96%   |
| Gentoo       | 3        | 0.96%   |
| EndeavourOS  | 3        | 0.96%   |
| MX           | 2        | 0.64%   |
| Garuda Linux | 2        | 0.64%   |
| Xubuntu      | 1        | 0.32%   |
| SteamOS      | 1        | 0.32%   |
| Solus        | 1        | 0.32%   |
| Parrot       | 1        | 0.32%   |
| openSUSE     | 1        | 0.32%   |
| Nobara       | 1        | 0.32%   |
| NixOS        | 1        | 0.32%   |
| Lubuntu      | 1        | 0.32%   |
| Endless      | 1        | 0.32%   |
| Elementary   | 1        | 0.32%   |
| BlackPanther | 1        | 0.32%   |
| Anarchy      | 1        | 0.32%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 11       | 3.09%   |
| 5.4.0-52-generic         | 6        | 1.69%   |
| 5.16.7-desktop-1omv4003  | 6        | 1.69%   |
| 5.15.0-58-generic        | 5        | 1.4%    |
| 5.15.0-56-generic        | 5        | 1.4%    |
| 5.8.0-43-generic         | 4        | 1.12%   |
| 5.4.0-42-generic         | 4        | 1.12%   |
| 5.11.12-desktop-1omv4002 | 4        | 1.12%   |
| 4.15.0-48-generic        | 4        | 1.12%   |
| 6.2.6-desktop-1omv2390   | 3        | 0.84%   |
| 5.8.5-arch1-1            | 3        | 0.84%   |
| 5.4.0-91-generic         | 3        | 0.84%   |
| 5.4.0-90-generic         | 3        | 0.84%   |
| 5.4.0-73-generic         | 3        | 0.84%   |
| 5.4.0-58-generic         | 3        | 0.84%   |
| 5.4.0-29-generic         | 3        | 0.84%   |
| 5.3.0-28-generic         | 3        | 0.84%   |
| 5.19.0-38-generic        | 3        | 0.84%   |
| 5.15.0-69-generic        | 3        | 0.84%   |
| 5.15.0-46-generic        | 3        | 0.84%   |
| 5.15.0-41-generic        | 3        | 0.84%   |
| 5.13.0-28-generic        | 3        | 0.84%   |
| 5.11.0-7620-generic      | 3        | 0.84%   |
| 5.11.0-37-generic        | 3        | 0.84%   |
| 5.11.0-27-generic        | 3        | 0.84%   |
| 5.10.0-20-amd64          | 3        | 0.84%   |
| 5.0.0-13-generic         | 3        | 0.84%   |
| 4.15.0-45-generic        | 3        | 0.84%   |
| 6.2.6-arch1-1            | 2        | 0.56%   |
| 6.2.6-76060206-generic   | 2        | 0.56%   |
| 6.2.0-76060200-generic   | 2        | 0.56%   |
| 6.1.9-arch1-1            | 2        | 0.56%   |
| 5.8.0-7642-generic       | 2        | 0.56%   |
| 5.8.0-63-generic         | 2        | 0.56%   |
| 5.8.0-41-generic         | 2        | 0.56%   |
| 5.6.15-1-MANJARO         | 2        | 0.56%   |
| 5.6.12-1-MANJARO         | 2        | 0.56%   |
| 5.4.18-1-MANJARO         | 2        | 0.56%   |
| 5.4.0-88-generic         | 2        | 0.56%   |
| 5.4.0-80-generic         | 2        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 51       | 14.96%  |
| 4.15.0  | 28       | 8.21%   |
| 5.15.0  | 24       | 7.04%   |
| 5.8.0   | 21       | 6.16%   |
| 5.13.0  | 19       | 5.57%   |
| 5.11.0  | 18       | 5.28%   |
| 5.19.0  | 13       | 3.81%   |
| 5.3.0   | 11       | 3.23%   |
| 5.10.14 | 11       | 3.23%   |
| 5.10.0  | 8        | 2.35%   |
| 5.0.0   | 8        | 2.35%   |
| 6.2.6   | 7        | 2.05%   |
| 5.16.7  | 6        | 1.76%   |
| 4.18.0  | 5        | 1.47%   |
| 5.11.12 | 4        | 1.17%   |
| 4.19.0  | 4        | 1.17%   |
| 5.8.5   | 3        | 0.88%   |
| 5.6.15  | 3        | 0.88%   |
| 6.2.8   | 2        | 0.59%   |
| 6.2.0   | 2        | 0.59%   |
| 6.1.9   | 2        | 0.59%   |
| 6.1.12  | 2        | 0.59%   |
| 6.1.1   | 2        | 0.59%   |
| 5.9.1   | 2        | 0.59%   |
| 5.8.18  | 2        | 0.59%   |
| 5.6.12  | 2        | 0.59%   |
| 5.4.18  | 2        | 0.59%   |
| 5.19.5  | 2        | 0.59%   |
| 5.16.0  | 2        | 0.59%   |
| 5.13.12 | 2        | 0.59%   |
| 5.11.11 | 2        | 0.59%   |
| 6.2.7   | 1        | 0.29%   |
| 6.1.8   | 1        | 0.29%   |
| 6.1.7   | 1        | 0.29%   |
| 6.1.4   | 1        | 0.29%   |
| 6.1.3   | 1        | 0.29%   |
| 6.1.14  | 1        | 0.29%   |
| 6.1.11  | 1        | 0.29%   |
| 6.1.0   | 1        | 0.29%   |
| 6.0.9   | 1        | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 16.42%  |
| 5.15    | 32       | 9.55%   |
| 5.8     | 30       | 8.96%   |
| 4.15    | 28       | 8.36%   |
| 5.11    | 26       | 7.76%   |
| 5.13    | 22       | 6.57%   |
| 5.10    | 21       | 6.27%   |
| 5.19    | 16       | 4.78%   |
| 5.16    | 13       | 3.88%   |
| 6.2     | 12       | 3.58%   |
| 6.1     | 12       | 3.58%   |
| 5.3     | 11       | 3.28%   |
| 5.0     | 8        | 2.39%   |
| 5.6     | 7        | 2.09%   |
| 6.0     | 6        | 1.79%   |
| 5.7     | 5        | 1.49%   |
| 4.19    | 5        | 1.49%   |
| 4.18    | 5        | 1.49%   |
| 5.17    | 4        | 1.19%   |
| 5.9     | 3        | 0.9%    |
| 5.14    | 3        | 0.9%    |
| 4.9     | 3        | 0.9%    |
| 5.18    | 2        | 0.6%    |
| 5.12    | 2        | 0.6%    |
| 5.1     | 2        | 0.6%    |
| 5.2     | 1        | 0.3%    |
| 4.17    | 1        | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 297      | 99%     |
| i686   | 3        | 1%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 135      | 42.72%  |
| Unknown       | 57       | 18.04%  |
| KDE5          | 54       | 17.09%  |
| X-Cinnamon    | 24       | 7.59%   |
| XFCE          | 18       | 5.7%    |
| MATE          | 7        | 2.22%   |
| KDE           | 7        | 2.22%   |
| Cinnamon      | 4        | 1.27%   |
| KDE4          | 2        | 0.63%   |
| Pantheon      | 1        | 0.32%   |
| openbox       | 1        | 0.32%   |
| LXQt          | 1        | 0.32%   |
| LXDE          | 1        | 0.32%   |
| i3            | 1        | 0.32%   |
| enlightenment | 1        | 0.32%   |
| Deepin        | 1        | 0.32%   |
| bspwm         | 1        | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 250      | 80.65%  |
| Wayland | 27       | 8.71%   |
| Unknown | 25       | 8.06%   |
| Tty     | 8        | 2.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 174      | 55.59%  |
| SDDM    | 49       | 15.65%  |
| GDM3    | 33       | 10.54%  |
| GDM     | 21       | 6.71%   |
| LightDM | 18       | 5.75%   |
| TDM     | 15       | 4.79%   |
| KDM     | 2        | 0.64%   |
| LXDM    | 1        | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 113      | 36.57%  |
| da_DK      | 89       | 28.8%   |
| Unknown    | 43       | 13.92%  |
| en_DK      | 38       | 12.3%   |
| en_GB      | 10       | 3.24%   |
| C          | 4        | 1.29%   |
| ru_RU      | 2        | 0.65%   |
| de_DE      | 2        | 0.65%   |
| pl_PL      | 1        | 0.32%   |
| it_IT      | 1        | 0.32%   |
| io_001     | 1        | 0.32%   |
| es_ES      | 1        | 0.32%   |
| en_US.UTF8 | 1        | 0.32%   |
| en_IE      | 1        | 0.32%   |
| de_CH      | 1        | 0.32%   |
| de_AT      | 1        | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 180      | 58.25%  |
| EFI  | 129      | 41.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 243      | 77.64%  |
| Overlay | 27       | 8.63%   |
| Btrfs   | 23       | 7.35%   |
| Unknown | 13       | 4.15%   |
| Zfs     | 4        | 1.28%   |
| Xfs     | 2        | 0.64%   |
| F2fs    | 1        | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 179      | 57.56%  |
| GPT     | 102      | 32.8%   |
| MBR     | 30       | 9.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 240      | 77.42%  |
| Yes       | 70       | 22.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 218      | 71.48%  |
| Yes       | 87       | 28.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 101      | 33.67%  |
| Gigabyte Technology | 45       | 15%     |
| ASRock              | 29       | 9.67%   |
| MSI                 | 27       | 9%      |
| Lenovo              | 27       | 9%      |
| Hewlett-Packard     | 19       | 6.33%   |
| Medion              | 11       | 3.67%   |
| Dell                | 11       | 3.67%   |
| Acer                | 8        | 2.67%   |
| Pegatron            | 4        | 1.33%   |
| Shuttle             | 3        | 1%      |
| Intel               | 2        | 0.67%   |
| T-bao               | 1        | 0.33%   |
| Packard Bell        | 1        | 0.33%   |
| NEXCOM              | 1        | 0.33%   |
| Inventec            | 1        | 0.33%   |
| Fujitsu Siemens     | 1        | 0.33%   |
| Fujitsu             | 1        | 0.33%   |
| eMachines           | 1        | 0.33%   |
| ECS                 | 1        | 0.33%   |
| BESSTAR Tech        | 1        | 0.33%   |
| AMI                 | 1        | 0.33%   |
| Alienware           | 1        | 0.33%   |
| ABIT                | 1        | 0.33%   |
| Unknown             | 1        | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS ROG STRIX B450-E GAMING | 5        | 1.67%   |
| ASUS All Series              | 5        | 1.67%   |
| ASUS Z170 PRO GAMING         | 4        | 1.33%   |
| MSI MS-7C37                  | 3        | 1%      |
| Gigabyte X570 AORUS MASTER   | 3        | 1%      |
| Dell OptiPlex 9020           | 3        | 1%      |
| ASUS ROG STRIX B550-F GAMING | 3        | 1%      |
| MSI MS-7C02                  | 2        | 0.67%   |
| MSI MS-7B79                  | 2        | 0.67%   |
| MSI MS-7693                  | 2        | 0.67%   |
| Medion MS-7797               | 2        | 0.67%   |
| Medion MS-7646               | 2        | 0.67%   |
| Lenovo H30-05 90BJ00CNMT     | 2        | 0.67%   |
| Gigabyte P85-D3              | 2        | 0.67%   |
| ASUS Z170-P                  | 2        | 0.67%   |
| ASUS TUF Gaming X570-PLUS    | 2        | 0.67%   |
| ASUS ROG STRIX X470-I GAMING | 2        | 0.67%   |
| ASUS PRIME Z390-A            | 2        | 0.67%   |
| ASUS PRIME Z370-P            | 2        | 0.67%   |
| ASUS PRIME Z370-A            | 2        | 0.67%   |
| ASUS PRIME B250M-A           | 2        | 0.67%   |
| ASUS PRIME A320M-K           | 2        | 0.67%   |
| ASUS M5A78L-M/USB3           | 2        | 0.67%   |
| ASUS M5A78L-M LX V2          | 2        | 0.67%   |
| ASUS CROSSHAIR VI HERO       | 2        | 0.67%   |
| ASRock B550M-ITX/ac          | 2        | 0.67%   |
| T-bao MINI PC                | 1        | 0.33%   |
| Shuttle X50V2PLUS            | 1        | 0.33%   |
| Shuttle SN68S                | 1        | 0.33%   |
| Shuttle SH67H3               | 1        | 0.33%   |
| Pegatron HPE-532sc           | 1        | 0.33%   |
| Pegatron h8-1350eo           | 1        | 0.33%   |
| Pegatron h8-1110sc           | 1        | 0.33%   |
| Pegatron 2AD5                | 1        | 0.33%   |
| Packard Bell IXTREME M5741   | 1        | 0.33%   |
| NEXCOM NDIS B322             | 1        | 0.33%   |
| MSI Vortex G65VR 6RE SLI     | 1        | 0.33%   |
| MSI MS-7C91                  | 1        | 0.33%   |
| MSI MS-7C83                  | 1        | 0.33%   |
| MSI MS-7C80                  | 1        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 25       | 8.33%   |
| ASUS ROG            | 23       | 7.67%   |
| Lenovo ThinkCentre  | 12       | 4%      |
| ASUS TUF            | 9        | 3%      |
| Gigabyte X570       | 8        | 2.67%   |
| HP Compaq           | 7        | 2.33%   |
| Lenovo ThinkStation | 5        | 1.67%   |
| Dell OptiPlex       | 5        | 1.67%   |
| ASUS All            | 5        | 1.67%   |
| Acer Aspire         | 5        | 1.67%   |
| ASUS Z170           | 4        | 1.33%   |
| ASUS SABERTOOTH     | 4        | 1.33%   |
| ASUS M5A78L-M       | 4        | 1.33%   |
| MSI MS-7C37         | 3        | 1%      |
| Lenovo IdeaCentre   | 3        | 1%      |
| HP ProLiant         | 3        | 1%      |
| Gigabyte B550       | 3        | 1%      |
| ASRock Z170         | 3        | 1%      |
| MSI MS-7C02         | 2        | 0.67%   |
| MSI MS-7B79         | 2        | 0.67%   |
| MSI MS-7693         | 2        | 0.67%   |
| Medion MS-7797      | 2        | 0.67%   |
| Medion MS-7646      | 2        | 0.67%   |
| Lenovo H30-05       | 2        | 0.67%   |
| HP EliteDesk        | 2        | 0.67%   |
| Gigabyte Z390       | 2        | 0.67%   |
| Gigabyte P85-D3     | 2        | 0.67%   |
| Gigabyte A320M-S2H  | 2        | 0.67%   |
| Dell Precision      | 2        | 0.67%   |
| ASUS Z170-P         | 2        | 0.67%   |
| ASUS CROSSHAIR      | 2        | 0.67%   |
| ASRock Z77          | 2        | 0.67%   |
| ASRock B550M-ITX    | 2        | 0.67%   |
| ASRock B450M        | 2        | 0.67%   |
| ASRock B450         | 2        | 0.67%   |
| T-bao MINI          | 1        | 0.33%   |
| Shuttle X50V2PLUS   | 1        | 0.33%   |
| Shuttle SN68S       | 1        | 0.33%   |
| Shuttle SH67H3      | 1        | 0.33%   |
| Pegatron HPE-532sc  | 1        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 33       | 11%     |
| 2019 | 31       | 10.33%  |
| 2020 | 30       | 10%     |
| 2012 | 29       | 9.67%   |
| 2021 | 21       | 7%      |
| 2013 | 21       | 7%      |
| 2017 | 20       | 6.67%   |
| 2016 | 18       | 6%      |
| 2015 | 18       | 6%      |
| 2011 | 17       | 5.67%   |
| 2010 | 14       | 4.67%   |
| 2014 | 13       | 4.33%   |
| 2008 | 11       | 3.67%   |
| 2009 | 10       | 3.33%   |
| 2022 | 7        | 2.33%   |
| 2007 | 5        | 1.67%   |
| 2006 | 2        | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 300      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 295      | 98.33%  |
| Enabled  | 5        | 1.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 300      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 98       | 31.72%  |
| 32.01-64.0      | 63       | 20.39%  |
| 8.01-16.0       | 53       | 17.15%  |
| 3.01-4.0        | 29       | 9.39%   |
| 4.01-8.0        | 27       | 8.74%   |
| 64.01-256.0     | 22       | 7.12%   |
| 24.01-32.0      | 10       | 3.24%   |
| 1.01-2.0        | 4        | 1.29%   |
| 2.01-3.0        | 2        | 0.65%   |
| More than 256.0 | 1        | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 113      | 33.33%  |
| 2.01-3.0   | 78       | 23.01%  |
| 4.01-8.0   | 60       | 17.7%   |
| 3.01-4.0   | 51       | 15.04%  |
| 8.01-16.0  | 17       | 5.01%   |
| 0.51-1.0   | 10       | 2.95%   |
| 0.01-0.5   | 4        | 1.18%   |
| 24.01-32.0 | 3        | 0.88%   |
| 32.01-64.0 | 2        | 0.59%   |
| 16.01-24.0 | 1        | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 113      | 36.22%  |
| 2      | 75       | 24.04%  |
| 3      | 64       | 20.51%  |
| 4      | 29       | 9.29%   |
| 5      | 17       | 5.45%   |
| 6      | 6        | 1.92%   |
| 8      | 3        | 0.96%   |
| 0      | 3        | 0.96%   |
| 9      | 1        | 0.32%   |
| 7      | 1        | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 170      | 56.29%  |
| Yes       | 132      | 43.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 298      | 99.33%  |
| No        | 2        | 0.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 52.29%  |
| Yes       | 146      | 47.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 201      | 66.34%  |
| Yes       | 102      | 33.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Denmark | 300      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Copenhagen               | 78       | 25.16%  |
| Frederiksberg            | 16       | 5.16%   |
| Odense                   | 15       | 4.84%   |
| Aarhus                   | 12       | 3.87%   |
| Slagelse                 | 7        | 2.26%   |
| Aabenraa                 | 7        | 2.26%   |
| Silkeborg                | 6        | 1.94%   |
| Horsens                  | 6        | 1.94%   |
| Bronshoj                 | 6        | 1.94%   |
| Esbjerg                  | 5        | 1.61%   |
| Vejle                    | 4        | 1.29%   |
| Roskilde                 | 4        | 1.29%   |
| Herlev                   | 4        | 1.29%   |
| Allinge                  | 4        | 1.29%   |
| Albertslund Municipality | 4        | 1.29%   |
| Aalborg                  | 4        | 1.29%   |
| Viby J                   | 3        | 0.97%   |
| Valby                    | 3        | 0.97%   |
| Trige                    | 3        | 0.97%   |
| Svendborg                | 3        | 0.97%   |
| Rødovre Municipality    | 3        | 0.97%   |
| Nyborg                   | 3        | 0.97%   |
| Hvidovre                 | 3        | 0.97%   |
| Hjørring                | 3        | 0.97%   |
| Fredericia               | 3        | 0.97%   |
| Aabybro                  | 3        | 0.97%   |
| Vordingborg              | 2        | 0.65%   |
| Taastrup                 | 2        | 0.65%   |
| Stovring                 | 2        | 0.65%   |
| Soborg                   | 2        | 0.65%   |
| Skanderborg              | 2        | 0.65%   |
| Risskov                  | 2        | 0.65%   |
| Olsted                   | 2        | 0.65%   |
| Odder                    | 2        | 0.65%   |
| Kongens Lyngby           | 2        | 0.65%   |
| Kolding                  | 2        | 0.65%   |
| Kastrup                  | 2        | 0.65%   |
| Hundested                | 2        | 0.65%   |
| Holstebro                | 2        | 0.65%   |
| Glostrup Municipality    | 2        | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 117      | 209    | 20.45%  |
| Seagate                   | 103      | 156    | 18.01%  |
| WDC                       | 89       | 150    | 15.56%  |
| Kingston                  | 52       | 77     | 9.09%   |
| Crucial                   | 25       | 35     | 4.37%   |
| SanDisk                   | 22       | 27     | 3.85%   |
| Toshiba                   | 21       | 27     | 3.67%   |
| Intel                     | 18       | 22     | 3.15%   |
| Hitachi                   | 11       | 17     | 1.92%   |
| Intenso                   | 8        | 11     | 1.4%    |
| Corsair                   | 8        | 11     | 1.4%    |
| Phison                    | 7        | 10     | 1.22%   |
| Unknown                   | 6        | 7      | 1.05%   |
| Phison Electronics        | 6        | 10     | 1.05%   |
| A-DATA Technology         | 6        | 6      | 1.05%   |
| SK hynix                  | 4        | 4      | 0.7%    |
| PNY                       | 4        | 4      | 0.7%    |
| OCZ                       | 4        | 4      | 0.7%    |
| HGST                      | 4        | 7      | 0.7%    |
| Verbatim                  | 3        | 6      | 0.52%   |
| Micron/Crucial Technology | 3        | 3      | 0.52%   |
| Micron Technology         | 3        | 4      | 0.52%   |
| LITEON                    | 3        | 3      | 0.52%   |
| JMicron Technology        | 3        | 3      | 0.52%   |
| XPG                       | 2        | 2      | 0.35%   |
| Transcend                 | 2        | 2      | 0.35%   |
| Patriot                   | 2        | 2      | 0.35%   |
| Maxtor                    | 2        | 2      | 0.35%   |
| Leven                     | 2        | 2      | 0.35%   |
| HUAWEI                    | 2        | 2      | 0.35%   |
| Fujitsu                   | 2        | 2      | 0.35%   |
| Apple                     | 2        | 5      | 0.35%   |
| AFOX                      | 2        | 2      | 0.35%   |
| Unknown                   | 2        | 4      | 0.35%   |
| USB                       | 1        | 1      | 0.17%   |
| Unknown (CF)              | 1        | 1      | 0.17%   |
| Team                      | 1        | 1      | 0.17%   |
| Supersonic                | 1        | 1      | 0.17%   |
| Silicon Motion            | 1        | 1      | 0.17%   |
| Shark                     | 1        | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung SSD 860 QVO 1TB                            | 8        | 1.18%   |
| Samsung NVMe SSD Drive 500GB                       | 8        | 1.18%   |
| Kingston SV300S37A120G 120GB SSD                   | 8        | 1.18%   |
| Kingston SA400S37240G 240GB SSD                    | 8        | 1.18%   |
| Seagate ST2000DM001-1ER164 2TB                     | 7        | 1.04%   |
| Samsung SSD 860 EVO 1TB                            | 7        | 1.04%   |
| Samsung NVMe SSD Drive 1TB                         | 7        | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB                     | 6        | 0.89%   |
| Samsung SSD 850 EVO 250GB                          | 6        | 0.89%   |
| Samsung SSD 840 EVO 250GB                          | 6        | 0.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 6        | 0.89%   |
| Seagate ST500DM002-1BD142 500GB                    | 5        | 0.74%   |
| Samsung SSD 860 EVO 500GB                          | 5        | 0.74%   |
| Samsung SSD 850 EVO 500GB                          | 5        | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 5        | 0.74%   |
| Phison E12 NVMe Controller 512GB                   | 5        | 0.74%   |
| Kingston SA400S37480G 480GB SSD                    | 5        | 0.74%   |
| Crucial CT1000MX500SSD1 1TB                        | 5        | 0.74%   |
| Unknown SD/MMC/MS PRO 249GB                        | 4        | 0.59%   |
| Seagate ST2000DM001-1CH164 2TB                     | 4        | 0.59%   |
| Seagate ST1000DM003-1SB10C 1TB                     | 4        | 0.59%   |
| Seagate ST1000DM003-1SB102 1TB                     | 4        | 0.59%   |
| Kingston SA400S37120G 120GB SSD                    | 4        | 0.59%   |
| WDC WD20EARX-00PASB0 2TB                           | 3        | 0.44%   |
| WDC WD1003FZEX-00K3CA0 1TB                         | 3        | 0.44%   |
| Seagate ST4000VN008-2DR166 4TB                     | 3        | 0.44%   |
| Seagate ST3250310AS 250GB                          | 3        | 0.44%   |
| Seagate ST3000DM008-2DM166 3TB                     | 3        | 0.44%   |
| Seagate ST3000DM001-1ER166 3TB                     | 3        | 0.44%   |
| Seagate ST2000DM001-9YN164 2TB                     | 3        | 0.44%   |
| SanDisk NVMe SSD Drive 1TB                         | 3        | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB                     | 3        | 0.44%   |
| Samsung SSD 970 EVO 1TB                            | 3        | 0.44%   |
| Samsung SSD 850 EVO 120GB                          | 3        | 0.44%   |
| Samsung SSD 840 EVO 500GB                          | 3        | 0.44%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB             | 3        | 0.44%   |
| Samsung NVMe SSD Drive 256GB                       | 3        | 0.44%   |
| Samsung HD103SJ 1TB                                | 3        | 0.44%   |
| PNY CS900 120GB SSD                                | 3        | 0.44%   |
| Kingston SV300S37A240G 240GB SSD                   | 3        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 99       | 149    | 41.42%  |
| WDC                 | 76       | 136    | 31.8%   |
| Toshiba             | 19       | 25     | 7.95%   |
| Samsung Electronics | 12       | 18     | 5.02%   |
| Hitachi             | 11       | 17     | 4.6%    |
| Unknown             | 4        | 5      | 1.67%   |
| HGST                | 4        | 7      | 1.67%   |
| JMicron Technology  | 3        | 3      | 1.26%   |
| Maxtor              | 2        | 2      | 0.84%   |
| Fujitsu             | 2        | 2      | 0.84%   |
| Apple               | 2        | 5      | 0.84%   |
| Unknown             | 2        | 4      | 0.84%   |
| Intenso             | 1        | 2      | 0.42%   |
| Hewlett-Packard     | 1        | 3      | 0.42%   |
| ASMT109x            | 1        | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 70       | 119    | 32.86%  |
| Kingston            | 44       | 61     | 20.66%  |
| Crucial             | 21       | 31     | 9.86%   |
| SanDisk             | 10       | 10     | 4.69%   |
| WDC                 | 7        | 7      | 3.29%   |
| Intel               | 7        | 9      | 3.29%   |
| Intenso             | 5        | 5      | 2.35%   |
| A-DATA Technology   | 5        | 5      | 2.35%   |
| PNY                 | 4        | 4      | 1.88%   |
| OCZ                 | 4        | 4      | 1.88%   |
| Corsair             | 4        | 5      | 1.88%   |
| Verbatim            | 3        | 6      | 1.41%   |
| Micron Technology   | 3        | 4      | 1.41%   |
| LITEON              | 3        | 3      | 1.41%   |
| Transcend           | 2        | 2      | 0.94%   |
| Patriot             | 2        | 2      | 0.94%   |
| Leven               | 2        | 2      | 0.94%   |
| AFOX                | 2        | 2      | 0.94%   |
| USB                 | 1        | 1      | 0.47%   |
| Unknown (CF)        | 1        | 1      | 0.47%   |
| Toshiba             | 1        | 1      | 0.47%   |
| Team                | 1        | 1      | 0.47%   |
| Supersonic          | 1        | 1      | 0.47%   |
| SK hynix            | 1        | 1      | 0.47%   |
| Shark               | 1        | 1      | 0.47%   |
| OCZ-VERTEX3         | 1        | 1      | 0.47%   |
| LITEONIT            | 1        | 1      | 0.47%   |
| KingDian            | 1        | 1      | 0.47%   |
| INDMEM              | 1        | 1      | 0.47%   |
| FORESEE             | 1        | 1      | 0.47%   |
| China               | 1        | 1      | 0.47%   |
| ADATA SU            | 1        | 1      | 0.47%   |
| 2-Power             | 1        | 2      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 182      | 379    | 38.48%  |
| SSD     | 170      | 297    | 35.94%  |
| NVMe    | 111      | 177    | 23.47%  |
| Unknown | 8        | 8      | 1.69%   |
| MMC     | 2        | 2      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 257      | 646    | 64.25%  |
| NVMe | 111      | 177    | 27.75%  |
| SAS  | 30       | 38     | 7.5%    |
| MMC  | 2        | 2      | 0.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 187      | 327    | 47.22%  |
| 0.51-1.0   | 105      | 158    | 26.52%  |
| 1.01-2.0   | 45       | 83     | 11.36%  |
| 2.01-3.0   | 20       | 32     | 5.05%   |
| 4.01-10.0  | 17       | 41     | 4.29%   |
| 3.01-4.0   | 14       | 21     | 3.54%   |
| 10.01-20.0 | 8        | 14     | 2.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 60       | 18.58%  |
| 251-500        | 53       | 16.41%  |
| 101-250        | 52       | 16.1%   |
| 1001-2000      | 43       | 13.31%  |
| More than 3000 | 36       | 11.15%  |
| 1-20           | 22       | 6.81%   |
| 2001-3000      | 21       | 6.5%    |
| Unknown        | 16       | 4.95%   |
| 21-50          | 12       | 3.72%   |
| 51-100         | 8        | 2.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 100      | 30.67%  |
| 21-50          | 45       | 13.8%   |
| 101-250        | 44       | 13.5%   |
| 501-1000       | 33       | 10.12%  |
| 51-100         | 28       | 8.59%   |
| 251-500        | 25       | 7.67%   |
| Unknown        | 16       | 4.91%   |
| More than 3000 | 15       | 4.6%    |
| 1001-2000      | 15       | 4.6%    |
| 2001-3000      | 5        | 1.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD  | 2        | 4      | 5.88%   |
| Kingston SHPM2280P2H 480G SSD     | 2        | 2      | 5.88%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1      | 2.94%   |
| WDC WD5000AADS-00S9B0 500GB       | 1        | 1      | 2.94%   |
| WDC WD10EZRX-00A8LB0 1TB          | 1        | 1      | 2.94%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 2.94%   |
| WDC WD10EURX-73FH1Y0 1TB          | 1        | 1      | 2.94%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 2.94%   |
| Toshiba DT01ACA050 500GB          | 1        | 1      | 2.94%   |
| Seagate ST380013AS 80GB           | 1        | 1      | 2.94%   |
| Seagate ST3400633AS 400GB         | 1        | 1      | 2.94%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 2.94%   |
| Seagate ST320LT020-9YG142 320GB   | 1        | 1      | 2.94%   |
| Seagate ST3200822AS 200GB         | 1        | 1      | 2.94%   |
| Seagate ST31500341AS 1TB          | 1        | 1      | 2.94%   |
| Seagate ST31000524AS 1TB          | 1        | 1      | 2.94%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 2.94%   |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 1      | 2.94%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 2.94%   |
| SanDisk SDSSDX240GG25 240GB       | 1        | 1      | 2.94%   |
| Samsung Electronics SP0812C 80GB  | 1        | 1      | 2.94%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 2.94%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 2.94%   |
| OCZ AGILITY3 240GB SSD            | 1        | 1      | 2.94%   |
| Leven JAJS300M480C 480GB SSD      | 1        | 1      | 2.94%   |
| Kingston SA400S37480G 480GB SSD   | 1        | 1      | 2.94%   |
| Kingston SA400S37240G 240GB SSD   | 1        | 1      | 2.94%   |
| Intel SSDSC2BW480H6 480GB         | 1        | 1      | 2.94%   |
| Intel SSDPEKKF256G7L 256GB        | 1        | 1      | 2.94%   |
| Hitachi HDT721025SLA380 250GB     | 1        | 1      | 2.94%   |
| Hitachi HDP725032GLA360 320GB     | 1        | 2      | 2.94%   |
| Unknown                           | 1        | 2      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 10     | 27.59%  |
| Kingston            | 6        | 8      | 20.69%  |
| WDC                 | 5        | 6      | 17.24%  |
| Samsung Electronics | 2        | 3      | 6.9%    |
| Intel               | 2        | 2      | 6.9%    |
| Toshiba             | 1        | 1      | 3.45%   |
| SanDisk             | 1        | 1      | 3.45%   |
| OCZ                 | 1        | 1      | 3.45%   |
| Leven               | 1        | 1      | 3.45%   |
| Hitachi             | 1        | 3      | 3.45%   |
| Unknown             | 1        | 2      | 3.45%   |

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
| HDD  | 14       | 25     | 58.33%  |
| SSD  | 9        | 12     | 37.5%   |
| NVMe | 1        | 1      | 4.17%   |

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
| Detected | 207      | 545    | 60%     |
| Works    | 114      | 280    | 33.04%  |
| Malfunc  | 24       | 38     | 6.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 184      | 38.98%  |
| AMD                          | 110      | 23.31%  |
| Samsung Electronics          | 51       | 10.81%  |
| ASMedia Technology           | 21       | 4.45%   |
| SanDisk                      | 16       | 3.39%   |
| Phison Electronics           | 16       | 3.39%   |
| Kingston Technology Company  | 15       | 3.18%   |
| JMicron Technology           | 12       | 2.54%   |
| Marvell Technology Group     | 10       | 2.12%   |
| Nvidia                       | 9        | 1.91%   |
| Micron/Crucial Technology    | 7        | 1.48%   |
| Seagate Technology           | 5        | 1.06%   |
| ADATA Technology             | 4        | 0.85%   |
| SK hynix                     | 3        | 0.64%   |
| VIA Technologies             | 2        | 0.42%   |
| Toshiba America Info Systems | 1        | 0.21%   |
| Silicon Motion               | 1        | 0.21%   |
| Realtek Semiconductor        | 1        | 0.21%   |
| KIOXIA                       | 1        | 0.21%   |
| HighPoint Technologies       | 1        | 0.21%   |
| Hewlett-Packard              | 1        | 0.21%   |
| Broadcom / LSI               | 1        | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 75       | 12.91%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 31       | 5.34%   |
| AMD 400 Series Chipset SATA Controller                                                  | 26       | 4.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 3.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 20       | 3.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 3.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 19       | 3.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 18       | 3.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15       | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 2.24%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12       | 2.07%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 1.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10       | 1.72%   |
| Phison E12 NVMe Controller                                                              | 10       | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8        | 1.38%   |
| Kingston Company A2000 NVMe SSD                                                         | 8        | 1.38%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 1.38%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.38%   |
| Intel SSD 660P Series                                                                   | 7        | 1.2%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 6        | 1.03%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.03%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6        | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.03%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.03%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 0.86%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.86%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 0.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4        | 0.69%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.69%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 0.69%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.69%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3        | 0.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 263      | 57.55%  |
| NVMe | 113      | 24.73%  |
| IDE  | 58       | 12.69%  |
| RAID | 22       | 4.81%   |
| SAS  | 1        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 184      | 61.33%  |
| AMD    | 116      | 38.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 11       | 3.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 8        | 2.65%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 7        | 2.32%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 6        | 1.99%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 6        | 1.99%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 6        | 1.99%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 5        | 1.66%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 4        | 1.32%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 4        | 1.32%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 4        | 1.32%   |
| Intel Core i5-3350P CPU @ 3.10GHz      | 4        | 1.32%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 4        | 1.32%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 4        | 1.32%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 4        | 1.32%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 0.99%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 3        | 0.99%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 3        | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 3        | 0.99%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 3        | 0.99%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 3        | 0.99%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 0.99%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 3        | 0.99%   |
| Intel 12th Gen Core i9-12900K          | 3        | 0.99%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 3        | 0.99%   |
| AMD Ryzen 3 1200 Quad-Core Processor   | 3        | 0.99%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 2        | 0.66%   |
| Intel Core i7-4770S CPU @ 3.10GHz      | 2        | 0.66%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 2        | 0.66%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 2        | 0.66%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 2        | 0.66%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 2        | 0.66%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 0.66%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 2        | 0.66%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 2        | 0.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 0.66%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 2        | 0.66%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 0.66%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 2        | 0.66%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 2        | 0.66%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz   | 2        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 55       | 18.27%  |
| Intel Core i5           | 54       | 17.94%  |
| AMD Ryzen 7             | 29       | 9.63%   |
| AMD Ryzen 5             | 26       | 8.64%   |
| AMD Ryzen 9             | 18       | 5.98%   |
| Intel Xeon              | 14       | 4.65%   |
| Intel Core i3           | 14       | 4.65%   |
| Other                   | 11       | 3.65%   |
| AMD FX                  | 10       | 3.32%   |
| Intel Core 2 Duo        | 9        | 2.99%   |
| Intel Core i9           | 5        | 1.66%   |
| Intel Core 2 Quad       | 5        | 1.66%   |
| Intel Celeron           | 5        | 1.66%   |
| AMD Ryzen 3             | 5        | 1.66%   |
| AMD Phenom II X4        | 4        | 1.33%   |
| AMD Athlon 64 X2        | 4        | 1.33%   |
| AMD A8                  | 4        | 1.33%   |
| Intel Pentium           | 3        | 1%      |
| Intel Atom              | 3        | 1%      |
| AMD Ryzen Threadripper  | 3        | 1%      |
| AMD Athlon II X4        | 3        | 1%      |
| AMD A6                  | 3        | 1%      |
| AMD A10                 | 3        | 1%      |
| Intel Pentium Dual-Core | 2        | 0.66%   |
| Intel Core 2            | 2        | 0.66%   |
| Intel Pentium Silver    | 1        | 0.33%   |
| Intel Pentium Dual      | 1        | 0.33%   |
| AMD Phenom II X2        | 1        | 0.33%   |
| AMD GX                  | 1        | 0.33%   |
| AMD E                   | 1        | 0.33%   |
| AMD Athlon II Neo       | 1        | 0.33%   |
| AMD A4                  | 1        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 121      | 40.07%  |
| 2      | 54       | 17.88%  |
| 6      | 53       | 17.55%  |
| 8      | 39       | 12.91%  |
| 12     | 16       | 5.3%    |
| 16     | 10       | 3.31%   |
| 10     | 3        | 0.99%   |
| 1      | 2        | 0.66%   |
| 64     | 1        | 0.33%   |
| 32     | 1        | 0.33%   |
| 24     | 1        | 0.33%   |
| 3      | 1        | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 298      | 99.33%  |
| 2      | 2        | 0.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 189      | 63%     |
| 1      | 111      | 37%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 296      | 97.69%  |
| Unknown        | 7        | 2.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 73       | 23.32%  |
| 0x306c3    | 22       | 7.03%   |
| 0x506e3    | 16       | 5.11%   |
| 0x306a9    | 16       | 5.11%   |
| 0x206a7    | 15       | 4.79%   |
| 0x08701021 | 10       | 3.19%   |
| 0x0800820d | 10       | 3.19%   |
| 0x906ea    | 9        | 2.88%   |
| 0x1067a    | 8        | 2.56%   |
| 0x906e9    | 7        | 2.24%   |
| 0x90672    | 7        | 2.24%   |
| 0x08701013 | 7        | 2.24%   |
| 0x08001138 | 7        | 2.24%   |
| 0x0a201009 | 6        | 1.92%   |
| 0x906ed    | 5        | 1.6%    |
| 0x06000852 | 5        | 1.6%    |
| 0x010000c8 | 5        | 1.6%    |
| 0xa0653    | 4        | 1.28%   |
| 0x906ec    | 4        | 1.28%   |
| 0x0a601203 | 4        | 1.28%   |
| 0xa0655    | 3        | 0.96%   |
| 0x6fd      | 3        | 0.96%   |
| 0x106e5    | 3        | 0.96%   |
| 0x0a201205 | 3        | 0.96%   |
| 0xa0671    | 2        | 0.64%   |
| 0x6f6      | 2        | 0.64%   |
| 0x206c2    | 2        | 0.64%   |
| 0x10676    | 2        | 0.64%   |
| 0x0a50000c | 2        | 0.64%   |
| 0x0a201016 | 2        | 0.64%   |
| 0x08600106 | 2        | 0.64%   |
| 0x08108109 | 2        | 0.64%   |
| 0x08001137 | 2        | 0.64%   |
| 0x08001129 | 2        | 0.64%   |
| 0x06003106 | 2        | 0.64%   |
| 0x06001119 | 2        | 0.64%   |
| 0x0600063e | 2        | 0.64%   |
| 0x010000db | 2        | 0.64%   |
| 0x906eb    | 1        | 0.32%   |
| 0x906c0    | 1        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 35       | 11.59%  |
| Zen 2            | 31       | 10.26%  |
| Haswell          | 31       | 10.26%  |
| IvyBridge        | 22       | 7.28%   |
| Skylake          | 21       | 6.95%   |
| Zen 3            | 19       | 6.29%   |
| SandyBridge      | 19       | 6.29%   |
| Zen+             | 14       | 4.64%   |
| Penryn           | 14       | 4.64%   |
| Zen              | 12       | 3.97%   |
| Piledriver       | 10       | 3.31%   |
| Unknown          | 10       | 3.31%   |
| K10              | 9        | 2.98%   |
| CometLake        | 7        | 2.32%   |
| Core             | 6        | 1.99%   |
| Alderlake Hybrid | 6        | 1.99%   |
| Nehalem          | 5        | 1.66%   |
| Westmere         | 4        | 1.32%   |
| K8 Hammer        | 4        | 1.32%   |
| Steamroller      | 3        | 0.99%   |
| Puma             | 3        | 0.99%   |
| Bulldozer        | 3        | 0.99%   |
| Broadwell        | 3        | 0.99%   |
| Jaguar           | 2        | 0.66%   |
| Icelake          | 2        | 0.66%   |
| Bonnell          | 2        | 0.66%   |
| Silvermont       | 1        | 0.33%   |
| Goldmont plus    | 1        | 0.33%   |
| Goldmont         | 1        | 0.33%   |
| Excavator        | 1        | 0.33%   |
| Bobcat           | 1        | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 165      | 50.3%   |
| AMD                        | 89       | 27.13%  |
| Intel                      | 72       | 21.95%  |
| Matrox Electronics Systems | 1        | 0.3%    |
| ASPEED Technology          | 1        | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 13       | 3.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 13       | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 3.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 2.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 8        | 2.39%   |
| Intel HD Graphics 530                                                       | 8        | 2.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.09%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.79%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 1.79%   |
| Intel HD Graphics 630                                                       | 6        | 1.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.79%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.49%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 1.49%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 1.49%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 1.19%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 1.19%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.19%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 4        | 1.19%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.19%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 1.19%   |
| AMD Raphael                                                                 | 4        | 1.19%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 1.19%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.19%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.9%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 0.9%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2080]                                             | 3        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2060]                                             | 3        | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.9%    |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.9%    |
| Nvidia GK104 [GeForce GTX 770]                                              | 3        | 0.9%    |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 0.9%    |
| Intel AlderLake-S GT1                                                       | 3        | 0.9%    |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 3        | 0.9%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 0.9%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 3        | 0.9%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 152      | 50.33%  |
| 1 x AMD         | 75       | 24.83%  |
| 1 x Intel       | 53       | 17.55%  |
| Intel + Nvidia  | 6        | 1.99%   |
| 2 x AMD         | 5        | 1.66%   |
| AMD + Nvidia    | 4        | 1.32%   |
| Intel + AMD     | 3        | 0.99%   |
| 2 x Nvidia      | 2        | 0.66%   |
| Nvidia + ASPEED | 1        | 0.33%   |
| 1 x Matrox      | 1        | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 196      | 63.23%  |
| Proprietary | 104      | 33.55%  |
| Unknown     | 10       | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 115      | 36.86%  |
| 1.01-2.0   | 60       | 19.23%  |
| 7.01-8.0   | 45       | 14.42%  |
| 3.01-4.0   | 21       | 6.73%   |
| 0.01-0.5   | 21       | 6.73%   |
| 5.01-6.0   | 20       | 6.41%   |
| 0.51-1.0   | 15       | 4.81%   |
| 8.01-16.0  | 11       | 3.53%   |
| 2.01-3.0   | 2        | 0.64%   |
| 4.01-5.0   | 1        | 0.32%   |
| 16.01-24.0 | 1        | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 72       | 21.3%   |
| Dell                    | 34       | 10.06%  |
| AOC                     | 23       | 6.8%    |
| Ancor Communications    | 22       | 6.51%   |
| Hewlett-Packard         | 21       | 6.21%   |
| Philips                 | 20       | 5.92%   |
| Acer                    | 19       | 5.62%   |
| BenQ                    | 18       | 5.33%   |
| ASUSTek Computer        | 15       | 4.44%   |
| Lenovo                  | 14       | 4.14%   |
| Goldstar                | 12       | 3.55%   |
| Sony                    | 9        | 2.66%   |
| Unknown                 | 6        | 1.78%   |
| Medion                  | 6        | 1.78%   |
| Lenovo Group Limited    | 5        | 1.48%   |
| LG Electronics          | 4        | 1.18%   |
| IBM                     | 3        | 0.89%   |
| Gigabyte Technology     | 3        | 0.89%   |
| ViewSonic               | 2        | 0.59%   |
| Vestel Elektronik       | 2        | 0.59%   |
| Tech Concepts           | 2        | 0.59%   |
| MSI                     | 2        | 0.59%   |
| Idek Iiyama             | 2        | 0.59%   |
| Fujitsu Siemens         | 2        | 0.59%   |
| AUS                     | 2        | 0.59%   |
| Unknown                 | 2        | 0.59%   |
| Wacom                   | 1        | 0.3%    |
| Vestel                  | 1        | 0.3%    |
| TopView                 | 1        | 0.3%    |
| Pixio                   | 1        | 0.3%    |
| Pioneer                 | 1        | 0.3%    |
| Panasonic               | 1        | 0.3%    |
| Packard Bell            | 1        | 0.3%    |
| OTC                     | 1        | 0.3%    |
| OEM                     | 1        | 0.3%    |
| Iiyama                  | 1        | 0.3%    |
| IFS                     | 1        | 0.3%    |
| Eizo                    | 1        | 0.3%    |
| Chi Mei Optoelectronics | 1        | 0.3%    |
| AU Optronics            | 1        | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch           | 6        | 1.56%   |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                      | 4        | 1.04%   |
| Sony TV SNYEE01 1920x1080                                              | 3        | 0.78%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3        | 0.78%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                      | 3        | 0.78%   |
| AOC U32U1WR6B AOC3201 3840x2160 697x392mm 31.5-inch                    | 3        | 0.78%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch       | 3        | 0.78%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 2        | 0.52%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                       | 2        | 0.52%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch   | 2        | 0.52%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 2        | 0.52%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 2        | 0.52%   |
| Samsung Electronics LCD Monitor LF27T35 1920x1080                      | 2        | 0.52%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch     | 2        | 0.52%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch               | 2        | 0.52%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2        | 0.52%   |
| Medion MD20444 MED3661 1920x1080 521x293mm 23.5-inch                   | 2        | 0.52%   |
| Lenovo LCD Monitor LEN1144 1920x1080 518x324mm 24.1-inch               | 2        | 0.52%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch             | 2        | 0.52%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 2        | 0.52%   |
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                 | 2        | 0.52%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch        | 2        | 0.52%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                      | 2        | 0.52%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                      | 2        | 0.52%   |
| Dell P1913 DELA089 1440x900 408x255mm 18.9-inch                        | 2        | 0.52%   |
| Dell 2407WFP DELA017 1920x1200 519x324mm 24.1-inch                     | 2        | 0.52%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch                | 2        | 0.52%   |
| BenQ G2420HDB BNQ7842 1920x1080 477x268mm 21.5-inch                    | 2        | 0.52%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 2        | 0.52%   |
| ASUSTek Computer VA249 AUS24C1 1920x1080 527x296mm 23.8-inch           | 2        | 0.52%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 2        | 0.52%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                       | 2        | 0.52%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 2        | 0.52%   |
| AOC 2460G4 AOC246A 1920x1080 531x299mm 24.0-inch                       | 2        | 0.52%   |
| AOC 2450W AOC2450 1920x1080 520x290mm 23.4-inch                        | 2        | 0.52%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch       | 2        | 0.52%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 2        | 0.52%   |
| Ancor Communications ASUS VP278 ACI27C8 1920x1080 598x336mm 27.0-inch  | 2        | 0.52%   |
| Unknown                                                                | 2        | 0.52%   |
| Wacom Cintiq 16 WAC1064 1920x1080 344x193mm 15.5-inch                  | 1        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 148      | 44.71%  |
| 2560x1440 (QHD)    | 39       | 11.78%  |
| 3840x2160 (4K)     | 36       | 10.88%  |
| 1680x1050 (WSXGA+) | 17       | 5.14%   |
| Unknown            | 17       | 5.14%   |
| 1280x1024 (SXGA)   | 14       | 4.23%   |
| 3440x1440          | 8        | 2.42%   |
| 1920x1200 (WUXGA)  | 8        | 2.42%   |
| 3840x1080          | 6        | 1.81%   |
| 1600x900 (HD+)     | 6        | 1.81%   |
| 1440x900 (WXGA+)   | 6        | 1.81%   |
| 1360x768           | 3        | 0.91%   |
| 3840x1200          | 2        | 0.6%    |
| 2560x1080          | 2        | 0.6%    |
| 1920x540           | 2        | 0.6%    |
| 9840x3840          | 1        | 0.3%    |
| 6400x2160          | 1        | 0.3%    |
| 5760x1440          | 1        | 0.3%    |
| 5760x1080          | 1        | 0.3%    |
| 5120x1440          | 1        | 0.3%    |
| 4608x1440          | 1        | 0.3%    |
| 4480x1440          | 1        | 0.3%    |
| 3840x1600          | 1        | 0.3%    |
| 3280x1080          | 1        | 0.3%    |
| 3200x1200          | 1        | 0.3%    |
| 3200x1080          | 1        | 0.3%    |
| 2560x1600          | 1        | 0.3%    |
| 2560x1024          | 1        | 0.3%    |
| 2048x1152          | 1        | 0.3%    |
| 1600x1200          | 1        | 0.3%    |
| 1366x768 (WXGA)    | 1        | 0.3%    |
| 1360x765           | 1        | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 63       | 18.92%  |
| 24      | 59       | 17.72%  |
| Unknown | 49       | 14.71%  |
| 23      | 37       | 11.11%  |
| 31      | 22       | 6.61%   |
| 21      | 19       | 5.71%   |
| 19      | 14       | 4.2%    |
| 22      | 12       | 3.6%    |
| 20      | 11       | 3.3%    |
| 34      | 8        | 2.4%    |
| 72      | 7        | 2.1%    |
| 84      | 5        | 1.5%    |
| 32      | 4        | 1.2%    |
| 17      | 3        | 0.9%    |
| 15      | 3        | 0.9%    |
| 38      | 2        | 0.6%    |
| 28      | 2        | 0.6%    |
| 25      | 2        | 0.6%    |
| 65      | 1        | 0.3%    |
| 60      | 1        | 0.3%    |
| 54      | 1        | 0.3%    |
| 48      | 1        | 0.3%    |
| 42      | 1        | 0.3%    |
| 39      | 1        | 0.3%    |
| 35      | 1        | 0.3%    |
| 33      | 1        | 0.3%    |
| 30      | 1        | 0.3%    |
| 29      | 1        | 0.3%    |
| 18      | 1        | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 136      | 43.04%  |
| Unknown     | 49       | 15.51%  |
| 401-500     | 48       | 15.19%  |
| 601-700     | 34       | 10.76%  |
| 701-800     | 13       | 4.11%   |
| 1501-2000   | 12       | 3.8%    |
| 351-400     | 9        | 2.85%   |
| 301-350     | 6        | 1.9%    |
| 801-900     | 4        | 1.27%   |
| 1001-1500   | 4        | 1.27%   |
| 901-1000    | 1        | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 190      | 63.12%  |
| Unknown | 44       | 14.62%  |
| 16/10   | 39       | 12.96%  |
| 5/4     | 12       | 3.99%   |
| 21/9    | 11       | 3.65%   |
| 4/3     | 2        | 0.66%   |
| 32/9    | 2        | 0.66%   |
| 3/2     | 1        | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 99       | 30.09%  |
| 301-350        | 63       | 19.15%  |
| Unknown        | 49       | 14.89%  |
| 351-500        | 39       | 11.85%  |
| 151-200        | 29       | 8.81%   |
| 251-300        | 24       | 7.29%   |
| More than 1000 | 15       | 4.56%   |
| 501-1000       | 5        | 1.52%   |
| 141-150        | 3        | 0.91%   |
| 101-110        | 2        | 0.61%   |
| 111-120        | 1        | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 181      | 59.15%  |
| 101-120 | 52       | 16.99%  |
| Unknown | 49       | 16.01%  |
| 121-160 | 12       | 3.92%   |
| 1-50    | 9        | 2.94%   |
| 161-240 | 3        | 0.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 211      | 68.95%  |
| 2     | 69       | 22.55%  |
| 0     | 16       | 5.23%   |
| 3     | 10       | 3.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 177      | 40.5%   |
| Intel                           | 143      | 32.72%  |
| Qualcomm Atheros                | 16       | 3.66%   |
| Broadcom                        | 16       | 3.66%   |
| Nvidia                          | 9        | 2.06%   |
| Ralink                          | 8        | 1.83%   |
| Ralink Technology               | 7        | 1.6%    |
| Aquantia                        | 6        | 1.37%   |
| TP-Link                         | 5        | 1.14%   |
| MediaTek                        | 5        | 1.14%   |
| ASUSTek Computer                | 5        | 1.14%   |
| Qualcomm Atheros Communications | 4        | 0.92%   |
| IMC Networks                    | 4        | 0.92%   |
| Huawei Technologies             | 4        | 0.92%   |
| OnePlus Technology (Shenzhen)   | 3        | 0.69%   |
| NetGear                         | 3        | 0.69%   |
| Edimax Technology               | 3        | 0.69%   |
| D-Link                          | 3        | 0.69%   |
| Samsung Electronics             | 2        | 0.46%   |
| Microsoft                       | 2        | 0.46%   |
| ASIX Electronics                | 2        | 0.46%   |
| Unknown                         | 1        | 0.23%   |
| Texas Instruments               | 1        | 0.23%   |
| Solarflare Communications       | 1        | 0.23%   |
| Linksys                         | 1        | 0.23%   |
| Lenovo                          | 1        | 0.23%   |
| JMicron Technology              | 1        | 0.23%   |
| InterBiometrics                 | 1        | 0.23%   |
| ICS Advent                      | 1        | 0.23%   |
| HMD Global                      | 1        | 0.23%   |
| D-Link System                   | 1        | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 139      | 27.69%  |
| Intel I211 Gigabit Network Connection                             | 27       | 5.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21       | 4.18%   |
| Intel Ethernet Connection (2) I219-V                              | 19       | 3.78%   |
| Intel Wi-Fi 6 AX200                                               | 17       | 3.39%   |
| Intel Ethernet Controller I225-V                                  | 10       | 1.99%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 1.99%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 1.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9        | 1.79%   |
| Intel Wireless-AC 9260                                            | 8        | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 8        | 1.59%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1%      |
| Realtek 802.11ac NIC                                              | 4        | 0.8%    |
| Ralink RT5370 Wireless Adapter                                    | 4        | 0.8%    |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 0.8%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.8%    |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]              | 4        | 0.8%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 3        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3        | 0.6%    |
| OnePlus (Shenzhen) OnePlus                                        | 3        | 0.6%    |
| Nvidia MCP73 Ethernet                                             | 3        | 0.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 3        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.6%    |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.6%    |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.4%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 52       | 34.21%  |
| Realtek Semiconductor           | 29       | 19.08%  |
| Broadcom                        | 12       | 7.89%   |
| Qualcomm Atheros                | 9        | 5.92%   |
| Ralink                          | 8        | 5.26%   |
| Ralink Technology               | 7        | 4.61%   |
| TP-Link                         | 5        | 3.29%   |
| ASUSTek Computer                | 5        | 3.29%   |
| Qualcomm Atheros Communications | 4        | 2.63%   |
| MediaTek                        | 4        | 2.63%   |
| IMC Networks                    | 4        | 2.63%   |
| NetGear                         | 3        | 1.97%   |
| Edimax Technology               | 3        | 1.97%   |
| D-Link                          | 3        | 1.97%   |
| Microsoft                       | 2        | 1.32%   |
| Linksys                         | 1        | 0.66%   |
| D-Link System                   | 1        | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 17       | 10.9%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 9        | 5.77%   |
| Intel Wireless-AC 9260                                                               | 8        | 5.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 8        | 5.13%   |
| Realtek 802.11ac NIC                                                                 | 4        | 2.56%   |
| Ralink RT5370 Wireless Adapter                                                       | 4        | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 2.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 4        | 2.56%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                 | 4        | 2.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 3        | 1.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 3        | 1.92%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 3        | 1.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 3        | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 3        | 1.92%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 2        | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.28%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 1.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 1.28%   |
| Ralink MT7601U Wireless Adapter                                                      | 2        | 1.28%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 2        | 1.28%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 1.28%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 1.28%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                          | 2        | 1.28%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 2        | 1.28%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 2        | 1.28%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 0.64%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 0.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1        | 0.64%   |
| TP-Link Archer T4U ver.3                                                             | 1        | 0.64%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1        | 0.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 1        | 0.64%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                          | 1        | 0.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.64%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                      | 1        | 0.64%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                           | 1        | 0.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 1        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 166      | 50.46%  |
| Intel                         | 121      | 36.78%  |
| Nvidia                        | 9        | 2.74%   |
| Qualcomm Atheros              | 8        | 2.43%   |
| Aquantia                      | 6        | 1.82%   |
| Broadcom                      | 4        | 1.22%   |
| OnePlus Technology (Shenzhen) | 3        | 0.91%   |
| Samsung Electronics           | 2        | 0.61%   |
| Huawei Technologies           | 2        | 0.61%   |
| ASIX Electronics              | 2        | 0.61%   |
| Solarflare Communications     | 1        | 0.3%    |
| MediaTek                      | 1        | 0.3%    |
| Lenovo                        | 1        | 0.3%    |
| JMicron Technology            | 1        | 0.3%    |
| ICS Advent                    | 1        | 0.3%    |
| HMD Global                    | 1        | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 139      | 40.76%  |
| Intel I211 Gigabit Network Connection                             | 27       | 7.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21       | 6.16%   |
| Intel Ethernet Connection (2) I219-V                              | 19       | 5.57%   |
| Intel Ethernet Controller I225-V                                  | 10       | 2.93%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 2.93%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 2.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 2.35%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.47%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.17%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.88%   |
| OnePlus (Shenzhen) OnePlus                                        | 3        | 0.88%   |
| Nvidia MCP73 Ethernet                                             | 3        | 0.88%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.88%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.59%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.59%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.59%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.59%   |
| Huawei ATU-L21                                                    | 2        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.59%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.29%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.29%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.29%   |
| Nvidia MCP79 Ethernet                                             | 1        | 0.29%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.29%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 298      | 66.37%  |
| WiFi     | 146      | 32.52%  |
| Modem    | 4        | 0.89%   |
| Unknown  | 1        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 243      | 77.14%  |
| WiFi     | 72       | 22.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 170      | 56.29%  |
| 2     | 110      | 36.42%  |
| 3     | 17       | 5.63%   |
| 0     | 3        | 0.99%   |
| 5     | 1        | 0.33%   |
| 4     | 1        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 289      | 96.01%  |
| Yes  | 12       | 3.99%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 50       | 46.3%   |
| Cambridge Silicon Radio         | 28       | 25.93%  |
| ASUSTek Computer                | 7        | 6.48%   |
| IMC Networks                    | 5        | 4.63%   |
| Qualcomm Atheros Communications | 4        | 3.7%    |
| Broadcom                        | 4        | 3.7%    |
| Realtek Semiconductor           | 3        | 2.78%   |
| MediaTek                        | 3        | 2.78%   |
| Belkin Components               | 2        | 1.85%   |
| HTC (High Tech Computer)        | 1        | 0.93%   |
| Edimax Technology               | 1        | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 28       | 25.93%  |
| Intel AX200 Bluetooth                                                | 14       | 12.96%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 9        | 8.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 8        | 7.41%   |
| Intel Bluetooth wireless interface                                   | 6        | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 5        | 4.63%   |
| IMC Networks Bluetooth Radio                                         | 4        | 3.7%    |
| MediaTek Wireless_Device                                             | 3        | 2.78%   |
| Intel AX210 Bluetooth                                                | 3        | 2.78%   |
| Intel AX201 Bluetooth                                                | 3        | 2.78%   |
| ASUS ASUS USB-BT500                                                  | 3        | 2.78%   |
| Realtek RTL8821A Bluetooth                                           | 2        | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2        | 1.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 1.85%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 2        | 1.85%   |
| ASUS Bluetooth Radio                                                 | 2        | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.93%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 0.93%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.93%   |
| Intel Bluetooth Device                                               | 1        | 0.93%   |
| IMC Networks Bluetooth Device                                        | 1        | 0.93%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.93%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 0.93%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 0.93%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 0.93%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.93%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 167      | 29.04%  |
| Nvidia                  | 162      | 28.17%  |
| AMD                     | 138      | 24%     |
| SteelSeries ApS         | 15       | 2.61%   |
| Kingston Technology     | 12       | 2.09%   |
| C-Media Electronics     | 12       | 2.09%   |
| Creative Technology     | 8        | 1.39%   |
| ASUSTek Computer        | 8        | 1.39%   |
| Logitech                | 7        | 1.22%   |
| Creative Labs           | 7        | 1.22%   |
| GN Netcom               | 5        | 0.87%   |
| Yamaha                  | 2        | 0.35%   |
| XMOS                    | 2        | 0.35%   |
| VIA Technologies        | 2        | 0.35%   |
| Texas Instruments       | 2        | 0.35%   |
| Realtek Semiconductor   | 2        | 0.35%   |
| Razer USA               | 2        | 0.35%   |
| Focusrite-Novation      | 2        | 0.35%   |
| Turtle Beach            | 1        | 0.17%   |
| Tenx Technology         | 1        | 0.17%   |
| Syntek                  | 1        | 0.17%   |
| Sony                    | 1        | 0.17%   |
| Shure                   | 1        | 0.17%   |
| RODE Microphones        | 1        | 0.17%   |
| ROCCAT                  | 1        | 0.17%   |
| Musical Fidelity        | 1        | 0.17%   |
| JMTek                   | 1        | 0.17%   |
| GYROCOM C&C             | 1        | 0.17%   |
| DSEA A/S                | 1        | 0.17%   |
| Corsair                 | 1        | 0.17%   |
| Clavia DMI AB           | 1        | 0.17%   |
| BR25                    | 1        | 0.17%   |
| BEHRINGER International | 1        | 0.17%   |
| B & W Group             | 1        | 0.17%   |
| Audio-Technica          | 1        | 0.17%   |
| Astro Gaming            | 1        | 0.17%   |
| ASRock                  | 1        | 0.17%   |
| Antlion Audio           | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 41       | 6.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22       | 3.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22       | 3.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21       | 3.22%   |
| Intel 200 Series PCH HD Audio                                              | 19       | 2.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19       | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17       | 2.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16       | 2.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 14       | 2.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14       | 2.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 14       | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 2.15%   |
| AMD Navi 10 HDMI Audio                                                     | 14       | 2.15%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14       | 2.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14       | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 12       | 1.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 10       | 1.53%   |
| Nvidia TU104 HD Audio Controller                                           | 10       | 1.53%   |
| Nvidia GK104 HDMI Audio Controller                                         | 10       | 1.53%   |
| AMD FCH Azalia Controller                                                  | 10       | 1.53%   |
| Kingston Technology HyperX 7.1 Audio                                       | 9        | 1.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.23%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8        | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 1.07%   |
| Nvidia GM204 High Definition Audio Controller                              | 7        | 1.07%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7        | 1.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 7        | 1.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7        | 1.07%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 0.92%   |
| ASUSTek Computer USB Audio                                                 | 6        | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 0.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 0.92%   |
| AMD Kabini HDMI/DP Audio                                                   | 6        | 0.92%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 5        | 0.77%   |
| Nvidia GP102 HDMI Audio Controller                                         | 5        | 0.77%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 41       | 23.98%  |
| Kingston            | 31       | 18.13%  |
| G.Skill             | 24       | 14.04%  |
| Samsung Electronics | 20       | 11.7%   |
| Unknown             | 18       | 10.53%  |
| Crucial             | 12       | 7.02%   |
| SK hynix            | 9        | 5.26%   |
| Micron Technology   | 8        | 4.68%   |
| Ramaxel Technology  | 3        | 1.75%   |
| Nanya Technology    | 2        | 1.17%   |
| Unifosa             | 1        | 0.58%   |
| Elpida              | 1        | 0.58%   |
| Unknown             | 1        | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 8        | 4.4%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 4        | 2.2%    |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s | 4        | 2.2%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 2        | 1.1%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                  | 2        | 1.1%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 2        | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 2        | 1.1%    |
| Samsung RAM M378B5773CH0-CK0 2048MB DIMM DDR3 1600MT/s   | 2        | 1.1%    |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s      | 2        | 1.1%    |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s      | 2        | 1.1%    |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 2        | 1.1%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 2        | 1.1%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 2        | 1.1%    |
| Kingston RAM KF556C36-16 16GB DIMM 6400MT/s              | 2        | 1.1%    |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s         | 2        | 1.1%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 2        | 1.1%    |
| Kingston RAM HP24D4U7S8MBP-8 8192MB DIMM DDR4 2400MT/s   | 2        | 1.1%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 2        | 1.1%    |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 2        | 1.1%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 2        | 1.1%    |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s   | 2        | 1.1%    |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 2        | 1.1%    |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM 1600MT/s           | 2        | 1.1%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 2        | 1.1%    |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 0.55%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s                 | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                     | 1        | 0.55%   |
| Unknown RAM Module 4096MB DIMM                           | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 1        | 0.55%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s               | 1        | 0.55%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s      | 1        | 0.55%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s       | 1        | 0.55%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s        | 1        | 0.55%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.55%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 83       | 53.55%  |
| DDR3    | 43       | 27.74%  |
| Unknown | 10       | 6.45%   |
| DDR5    | 9        | 5.81%   |
| SDRAM   | 8        | 5.16%   |
| DDR     | 2        | 1.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 142      | 93.42%  |
| SODIMM | 10       | 6.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 71       | 43.29%  |
| 16384 | 33       | 20.12%  |
| 4096  | 30       | 18.29%  |
| 2048  | 18       | 10.98%  |
| 32768 | 9        | 5.49%   |
| 1024  | 2        | 1.22%   |
| 512   | 1        | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 30       | 17.96%  |
| 3600    | 18       | 10.78%  |
| 3200    | 16       | 9.58%   |
| 1333    | 15       | 8.98%   |
| 2400    | 13       | 7.78%   |
| 3400    | 7        | 4.19%   |
| 2667    | 7        | 4.19%   |
| 3466    | 6        | 3.59%   |
| 2133    | 5        | 2.99%   |
| 5200    | 3        | 1.8%    |
| 4800    | 3        | 1.8%    |
| 3666    | 3        | 1.8%    |
| 3000    | 3        | 1.8%    |
| 2933    | 3        | 1.8%    |
| 667     | 3        | 1.8%    |
| 6400    | 2        | 1.2%    |
| 3500    | 2        | 1.2%    |
| 2048    | 2        | 1.2%    |
| 1867    | 2        | 1.2%    |
| 1639    | 2        | 1.2%    |
| Unknown | 2        | 1.2%    |
| 20306   | 1        | 0.6%    |
| 6000    | 1        | 0.6%    |
| 4400    | 1        | 0.6%    |
| 4000    | 1        | 0.6%    |
| 3800    | 1        | 0.6%    |
| 3733    | 1        | 0.6%    |
| 3534    | 1        | 0.6%    |
| 3533    | 1        | 0.6%    |
| 3333    | 1        | 0.6%    |
| 3266    | 1        | 0.6%    |
| 3100    | 1        | 0.6%    |
| 2800    | 1        | 0.6%    |
| 2733    | 1        | 0.6%    |
| 2666    | 1        | 0.6%    |
| 2000    | 1        | 0.6%    |
| 1866    | 1        | 0.6%    |
| 1800    | 1        | 0.6%    |
| 1334    | 1        | 0.6%    |
| 1066    | 1        | 0.6%    |

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
| Logitech                               | 23       | 56.1%   |
| Microsoft                              | 3        | 7.32%   |
| Trust                                  | 2        | 4.88%   |
| Sunplus Innovation Technology          | 2        | 4.88%   |
| Samsung Electronics                    | 2        | 4.88%   |
| Creative Technology                    | 2        | 4.88%   |
| Quanta                                 | 1        | 2.44%   |
| Oculus VR                              | 1        | 2.44%   |
| Intel                                  | 1        | 2.44%   |
| Hewlett-Packard                        | 1        | 2.44%   |
| Cubeternet                             | 1        | 2.44%   |
| Chicony Electronics                    | 1        | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech StreamCam                                                   | 4        | 9.76%   |
| Logitech HD Webcam C525                                              | 3        | 7.32%   |
| Logitech HD Pro Webcam C920                                          | 3        | 7.32%   |
| Trust USB Camera                                                     | 2        | 4.88%   |
| Samsung Galaxy series, misc. (MTP mode)                              | 2        | 4.88%   |
| Logitech Webcam C270                                                 | 2        | 4.88%   |
| Logitech C930c                                                       | 2        | 4.88%   |
| Logitech C922 Pro Stream Webcam                                      | 2        | 4.88%   |
| Sunplus SunplusIT PC Camera                                          | 1        | 2.44%   |
| Sunplus Sandberg USB Webcam Pro                                      | 1        | 2.44%   |
| Quanta FREETALK HD                                                   | 1        | 2.44%   |
| Oculus VR Quest 2                                                    | 1        | 2.44%   |
| Microsoft MicrosoftÂ LifeCam Studio                                 | 1        | 2.44%   |
| Microsoft LifeCam HD-3000                                            | 1        | 2.44%   |
| Microsoft LifeCam Cinema                                             | 1        | 2.44%   |
| Logitech Webcam Pro 9000                                             | 1        | 2.44%   |
| Logitech Webcam C930e                                                | 1        | 2.44%   |
| Logitech Webcam C925e                                                | 1        | 2.44%   |
| Logitech QuickCam Pro 5000                                           | 1        | 2.44%   |
| Logitech QuickCam E 3500                                             | 1        | 2.44%   |
| Logitech HD Webcam C510                                              | 1        | 2.44%   |
| Logitech C670i FHD Webcam                                            | 1        | 2.44%   |
| Intel RealSense SR300                                                | 1        | 2.44%   |
| HP HD-4110 Webcam                                                    | 1        | 2.44%   |
| Cubeternet USB2.0 Camera                                             | 1        | 2.44%   |
| Creative VF0610 Live! Cam Socialize HD                               | 1        | 2.44%   |
| Creative Live! Cam Sync 1080p                                        | 1        | 2.44%   |
| Chicony Gateway Webcam                                               | 1        | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 2.44%   |

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
| 0     | 253      | 82.95%  |
| 1     | 37       | 12.13%  |
| 2     | 10       | 3.28%   |
| 3     | 3        | 0.98%   |
| 6     | 1        | 0.33%   |
| 4     | 1        | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 18       | 27.27%  |
| Net/wireless             | 15       | 22.73%  |
| Sound                    | 7        | 10.61%  |
| Communication controller | 7        | 10.61%  |
| Multimedia controller    | 6        | 9.09%   |
| Unassigned class         | 5        | 7.58%   |
| Storage/raid             | 2        | 3.03%   |
| Card reader              | 2        | 3.03%   |
| Network                  | 1        | 1.52%   |
| Net/ethernet             | 1        | 1.52%   |
| Chipcard                 | 1        | 1.52%   |
| Camera                   | 1        | 1.52%   |

