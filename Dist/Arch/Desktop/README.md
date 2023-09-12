Arch - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for Arch.

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

Total: 3764

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Z390-A PRO                  | [32c21f0b73](https://linux-hardware.org/?probe=32c21f0b73) | Sep 07, 2023 |
| ASUSTek       | Maximus VII HERO            | [d9509a0fa0](https://linux-hardware.org/?probe=d9509a0fa0) | Sep 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [c22fad9c67](https://linux-hardware.org/?probe=c22fad9c67) | Sep 06, 2023 |
| ASUSTek       | PRIME B650M-A II            | [307ca05754](https://linux-hardware.org/?probe=307ca05754) | Sep 06, 2023 |
| Gigabyte      | X99-UD4-CF                  | [ee70bf217a](https://linux-hardware.org/?probe=ee70bf217a) | Sep 06, 2023 |
| Pegatron      | 2AD3                        | [07cfb5b967](https://linux-hardware.org/?probe=07cfb5b967) | Sep 05, 2023 |
| Gigabyte      | F2A85X-UP4                  | [9c7d201848](https://linux-hardware.org/?probe=9c7d201848) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [a64157168e](https://linux-hardware.org/?probe=a64157168e) | Sep 05, 2023 |
| Dell          | 00V62H A01                  | [51b40f3137](https://linux-hardware.org/?probe=51b40f3137) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | [0576ca20ab](https://linux-hardware.org/?probe=0576ca20ab) | Sep 05, 2023 |
| Acer          | Veriton M480                | [0c97015cce](https://linux-hardware.org/?probe=0c97015cce) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | [710c22af52](https://linux-hardware.org/?probe=710c22af52) | Sep 05, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [4a93cea12b](https://linux-hardware.org/?probe=4a93cea12b) | Sep 04, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [81f816e956](https://linux-hardware.org/?probe=81f816e956) | Sep 03, 2023 |
| ASUSTek       | Maximus VIII HERO           | [d208a16a1b](https://linux-hardware.org/?probe=d208a16a1b) | Sep 03, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [2eed39fb24](https://linux-hardware.org/?probe=2eed39fb24) | Sep 03, 2023 |
| ASRock        | B365 Pro4                   | [d6be71642e](https://linux-hardware.org/?probe=d6be71642e) | Sep 03, 2023 |
| ASUSTek       | A88X-PRO                    | [79ca2081a1](https://linux-hardware.org/?probe=79ca2081a1) | Sep 03, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [99b1fcf2e9](https://linux-hardware.org/?probe=99b1fcf2e9) | Sep 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | [56520c8e8d](https://linux-hardware.org/?probe=56520c8e8d) | Sep 03, 2023 |
| ASUSTek       | Z97M-PLUS                   | [5dac4ae656](https://linux-hardware.org/?probe=5dac4ae656) | Sep 03, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [ad65335e8d](https://linux-hardware.org/?probe=ad65335e8d) | Sep 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [9ab3e57ab7](https://linux-hardware.org/?probe=9ab3e57ab7) | Sep 02, 2023 |
| Dell          | 030VXY A02                  | [ff787e57bc](https://linux-hardware.org/?probe=ff787e57bc) | Sep 01, 2023 |
| ASUSTek       | PRIME H510M-K               | [f39e23df01](https://linux-hardware.org/?probe=f39e23df01) | Sep 01, 2023 |
| ASRock        | B365 Pro4                   | [6d0b6e95ba](https://linux-hardware.org/?probe=6d0b6e95ba) | Aug 30, 2023 |
| ASUSTek       | A88X-PRO                    | [9327ae4f97](https://linux-hardware.org/?probe=9327ae4f97) | Aug 30, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [0b44043b10](https://linux-hardware.org/?probe=0b44043b10) | Aug 29, 2023 |
| ASUSTek       | H97M-PLUS                   | [c5fb822b1c](https://linux-hardware.org/?probe=c5fb822b1c) | Aug 29, 2023 |
| Huanan        | H610M-PLUS V1.2             | [083aaaf1eb](https://linux-hardware.org/?probe=083aaaf1eb) | Aug 29, 2023 |
| Gigabyte      | H61M-DS2                    | [0817c6178e](https://linux-hardware.org/?probe=0817c6178e) | Aug 29, 2023 |
| Gigabyte      | H61M-DS2                    | [0a2adee694](https://linux-hardware.org/?probe=0a2adee694) | Aug 29, 2023 |
| ASUSTek       | PRIME Z370-P II             | [56692679f3](https://linux-hardware.org/?probe=56692679f3) | Aug 28, 2023 |
| ECS           | G31T-M7                     | [f095887170](https://linux-hardware.org/?probe=f095887170) | Aug 28, 2023 |
| Gigabyte      | 970A-D3P                    | [e178a50d54](https://linux-hardware.org/?probe=e178a50d54) | Aug 27, 2023 |
| ASUSTek       | Pro B550M-C                 | [3c68838457](https://linux-hardware.org/?probe=3c68838457) | Aug 27, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [4e7e2a9946](https://linux-hardware.org/?probe=4e7e2a9946) | Aug 27, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [b7020427e0](https://linux-hardware.org/?probe=b7020427e0) | Aug 27, 2023 |
| MSI           | H310M PRO-VD PLUS           | [2a25ad0be2](https://linux-hardware.org/?probe=2a25ad0be2) | Aug 27, 2023 |
| MSI           | Z390-A PRO                  | [7425d71f52](https://linux-hardware.org/?probe=7425d71f52) | Aug 26, 2023 |
| MSI           | Z390-A PRO                  | [fc86b0463f](https://linux-hardware.org/?probe=fc86b0463f) | Aug 26, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [e3c32f6873](https://linux-hardware.org/?probe=e3c32f6873) | Aug 25, 2023 |
| ASUSTek       | PRIME X570-P                | [555c7d17f0](https://linux-hardware.org/?probe=555c7d17f0) | Aug 25, 2023 |
| ASUSTek       | PRIME X570-P                | [2668db7570](https://linux-hardware.org/?probe=2668db7570) | Aug 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3a86d43941](https://linux-hardware.org/?probe=3a86d43941) | Aug 25, 2023 |
| HP            | 1497                        | [32a8075d02](https://linux-hardware.org/?probe=32a8075d02) | Aug 25, 2023 |
| Gigabyte      | B450M S2H                   | [9d09e14624](https://linux-hardware.org/?probe=9d09e14624) | Aug 24, 2023 |
| Gigabyte      | B450M DS3H V2               | [7486221845](https://linux-hardware.org/?probe=7486221845) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [60588f77af](https://linux-hardware.org/?probe=60588f77af) | Aug 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [368f9f947b](https://linux-hardware.org/?probe=368f9f947b) | Aug 23, 2023 |
| Gigabyte      | B365M DS3H                  | [74ff13d301](https://linux-hardware.org/?probe=74ff13d301) | Aug 23, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [6c9f647d44](https://linux-hardware.org/?probe=6c9f647d44) | Aug 23, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [6e915a1913](https://linux-hardware.org/?probe=6e915a1913) | Aug 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [9762e16c0e](https://linux-hardware.org/?probe=9762e16c0e) | Aug 21, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [4bc2673b83](https://linux-hardware.org/?probe=4bc2673b83) | Aug 21, 2023 |
| Dell          | 0D883F A04                  | [f76b91821d](https://linux-hardware.org/?probe=f76b91821d) | Aug 21, 2023 |
| Gigabyte      | M68M-S2P                    | [41ba06b203](https://linux-hardware.org/?probe=41ba06b203) | Aug 21, 2023 |
| AZW           | GTR V11                     | [9aefbc3e69](https://linux-hardware.org/?probe=9aefbc3e69) | Aug 20, 2023 |
| Intel         | X99                         | [c1ad35e185](https://linux-hardware.org/?probe=c1ad35e185) | Aug 20, 2023 |
| HP            | 2B29                        | [62f37a51ca](https://linux-hardware.org/?probe=62f37a51ca) | Aug 20, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [28a27adc22](https://linux-hardware.org/?probe=28a27adc22) | Aug 20, 2023 |
| Gigabyte      | AX370-Gaming 3-CF           | [13bcbc11d7](https://linux-hardware.org/?probe=13bcbc11d7) | Aug 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [778ea97c77](https://linux-hardware.org/?probe=778ea97c77) | Aug 20, 2023 |
| TYAN Compu... | S8010                       | [a381c313e3](https://linux-hardware.org/?probe=a381c313e3) | Aug 20, 2023 |
| Dell          | 0VNP2H A01                  | [5724c221b8](https://linux-hardware.org/?probe=5724c221b8) | Aug 19, 2023 |
| ASUSTek       | P8H61-MX                    | [767b42eeca](https://linux-hardware.org/?probe=767b42eeca) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3c0bf7ce7b](https://linux-hardware.org/?probe=3c0bf7ce7b) | Aug 18, 2023 |
| Gigabyte      | B560M D3H                   | [7a9ae970e6](https://linux-hardware.org/?probe=7a9ae970e6) | Aug 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [84cbd742a1](https://linux-hardware.org/?probe=84cbd742a1) | Aug 17, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [caae17275e](https://linux-hardware.org/?probe=caae17275e) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | [1aeba3a6ec](https://linux-hardware.org/?probe=1aeba3a6ec) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | [b44417fa3d](https://linux-hardware.org/?probe=b44417fa3d) | Aug 17, 2023 |
| Shenzhen M... | F7BSC                       | [94b9b057b4](https://linux-hardware.org/?probe=94b9b057b4) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [eb44f4dfc1](https://linux-hardware.org/?probe=eb44f4dfc1) | Aug 17, 2023 |
| CWWK          | N3050 P1                    | [dd3dfb0c02](https://linux-hardware.org/?probe=dd3dfb0c02) | Aug 17, 2023 |
| Shenzhen M... | F7BSC                       | [bfe3223b92](https://linux-hardware.org/?probe=bfe3223b92) | Aug 17, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [1d389611a3](https://linux-hardware.org/?probe=1d389611a3) | Aug 16, 2023 |
| ASUSTek       | PRIME Z390-P                | [c8ed9b0cb2](https://linux-hardware.org/?probe=c8ed9b0cb2) | Aug 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [24a5a21c43](https://linux-hardware.org/?probe=24a5a21c43) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [accdc886c7](https://linux-hardware.org/?probe=accdc886c7) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [96d94e5f6c](https://linux-hardware.org/?probe=96d94e5f6c) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [5652688ceb](https://linux-hardware.org/?probe=5652688ceb) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7463d795e8](https://linux-hardware.org/?probe=7463d795e8) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [38e95ded09](https://linux-hardware.org/?probe=38e95ded09) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [651eae5b59](https://linux-hardware.org/?probe=651eae5b59) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [d32a9fb8a4](https://linux-hardware.org/?probe=d32a9fb8a4) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [5929bf1039](https://linux-hardware.org/?probe=5929bf1039) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [ac0320b2ee](https://linux-hardware.org/?probe=ac0320b2ee) | Aug 15, 2023 |
| MSI           | B450 TOMAHAWK               | [78e30cb8ef](https://linux-hardware.org/?probe=78e30cb8ef) | Aug 15, 2023 |
| Gigabyte      | B550M DS3H                  | [e2a4a35103](https://linux-hardware.org/?probe=e2a4a35103) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [5d52bf85ca](https://linux-hardware.org/?probe=5d52bf85ca) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [f972a8359d](https://linux-hardware.org/?probe=f972a8359d) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [ab0235d27c](https://linux-hardware.org/?probe=ab0235d27c) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [3446b719ab](https://linux-hardware.org/?probe=3446b719ab) | Aug 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [e53e56fcbc](https://linux-hardware.org/?probe=e53e56fcbc) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [c27b841a97](https://linux-hardware.org/?probe=c27b841a97) | Aug 15, 2023 |
| ECS           | G31T-M7                     | [2d35b5e140](https://linux-hardware.org/?probe=2d35b5e140) | Aug 14, 2023 |
| Gigabyte      | B365M DS3H                  | [857539aaba](https://linux-hardware.org/?probe=857539aaba) | Aug 14, 2023 |
| Intel         | X79M-S                      | [043e072c46](https://linux-hardware.org/?probe=043e072c46) | Aug 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [e6fe434dfa](https://linux-hardware.org/?probe=e6fe434dfa) | Aug 13, 2023 |
| NZXT          | N7 B550                     | [6cf14ccbe3](https://linux-hardware.org/?probe=6cf14ccbe3) | Aug 13, 2023 |
| ASUSTek       | PRIME B550M-A               | [74a73b0208](https://linux-hardware.org/?probe=74a73b0208) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [e03e2f8abc](https://linux-hardware.org/?probe=e03e2f8abc) | Aug 13, 2023 |
| Gigabyte      | 970A-D3P                    | [8ef51956a9](https://linux-hardware.org/?probe=8ef51956a9) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [f7ab4aa00a](https://linux-hardware.org/?probe=f7ab4aa00a) | Aug 12, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [504746e40c](https://linux-hardware.org/?probe=504746e40c) | Aug 12, 2023 |
| Gigabyte      | H61M-DS2                    | [3181a592ac](https://linux-hardware.org/?probe=3181a592ac) | Aug 12, 2023 |
| Gigabyte      | B365 HD3                    | [e2ebf1941c](https://linux-hardware.org/?probe=e2ebf1941c) | Aug 11, 2023 |
| ASRock        | H310CM-HG4                  | [773b111412](https://linux-hardware.org/?probe=773b111412) | Aug 10, 2023 |
| ASRock        | H310CM-HG4                  | [70c4f2863b](https://linux-hardware.org/?probe=70c4f2863b) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d38ef662d4](https://linux-hardware.org/?probe=d38ef662d4) | Aug 10, 2023 |
| ASRock        | B365 Pro4                   | [45da50b5c8](https://linux-hardware.org/?probe=45da50b5c8) | Aug 10, 2023 |
| ASRock        | B365 Pro4                   | [03cb2690f7](https://linux-hardware.org/?probe=03cb2690f7) | Aug 10, 2023 |
| Gigabyte      | H61M-DS2                    | [939205ed85](https://linux-hardware.org/?probe=939205ed85) | Aug 09, 2023 |
| ASUSTek       | PRIME X470-PRO              | [afef0bb361](https://linux-hardware.org/?probe=afef0bb361) | Aug 09, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [3ecd6d3f74](https://linux-hardware.org/?probe=3ecd6d3f74) | Aug 09, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [608c3967b2](https://linux-hardware.org/?probe=608c3967b2) | Aug 07, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [e6955ee04c](https://linux-hardware.org/?probe=e6955ee04c) | Aug 07, 2023 |
| MSI           | B450M MORTAR MAX            | [f772c670ff](https://linux-hardware.org/?probe=f772c670ff) | Aug 07, 2023 |
| MSI           | B450M MORTAR MAX            | [fc8b72dd99](https://linux-hardware.org/?probe=fc8b72dd99) | Aug 07, 2023 |
| MSI           | H370M BAZOOKA               | [760051e27b](https://linux-hardware.org/?probe=760051e27b) | Aug 07, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | [6baabbdd21](https://linux-hardware.org/?probe=6baabbdd21) | Aug 06, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [01b9adfb02](https://linux-hardware.org/?probe=01b9adfb02) | Aug 05, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [9365c3de56](https://linux-hardware.org/?probe=9365c3de56) | Aug 05, 2023 |
| ASRock        | P67 Pro3                    | [da235e8c08](https://linux-hardware.org/?probe=da235e8c08) | Aug 05, 2023 |
| ASRock        | B550 PG Velocita            | [71ca443602](https://linux-hardware.org/?probe=71ca443602) | Aug 05, 2023 |
| HP            | 83E8                        | [0d285189b9](https://linux-hardware.org/?probe=0d285189b9) | Aug 04, 2023 |
| Gigabyte      | Z490M GAMING X              | [ad51d2548b](https://linux-hardware.org/?probe=ad51d2548b) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [986cf08dc9](https://linux-hardware.org/?probe=986cf08dc9) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [da8d764a97](https://linux-hardware.org/?probe=da8d764a97) | Aug 03, 2023 |
| ASRock        | B650M PG Riptide            | [bdccf9a3db](https://linux-hardware.org/?probe=bdccf9a3db) | Aug 01, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [28f1074e0a](https://linux-hardware.org/?probe=28f1074e0a) | Aug 01, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [e16ea772e1](https://linux-hardware.org/?probe=e16ea772e1) | Jul 30, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [3bbfa332c0](https://linux-hardware.org/?probe=3bbfa332c0) | Jul 30, 2023 |
| HP            | 843B                        | [c570a7c5f2](https://linux-hardware.org/?probe=c570a7c5f2) | Jul 29, 2023 |
| ASRock        | X300M-STX                   | [e43da17360](https://linux-hardware.org/?probe=e43da17360) | Jul 29, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [aaa06048d5](https://linux-hardware.org/?probe=aaa06048d5) | Jul 28, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [e79fd50f34](https://linux-hardware.org/?probe=e79fd50f34) | Jul 26, 2023 |
| MECHREVO      | F7BFD V1.0                  | [f9be0fc5a7](https://linux-hardware.org/?probe=f9be0fc5a7) | Jul 26, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [8c8e7f5edd](https://linux-hardware.org/?probe=8c8e7f5edd) | Jul 26, 2023 |
| ASRock        | B450M-HDV R4.0              | [864fcc639d](https://linux-hardware.org/?probe=864fcc639d) | Jul 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [5399a2e19e](https://linux-hardware.org/?probe=5399a2e19e) | Jul 24, 2023 |
| Gigabyte      | H110M-H-CF                  | [6dbfb1d71e](https://linux-hardware.org/?probe=6dbfb1d71e) | Jul 24, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [b571da19fb](https://linux-hardware.org/?probe=b571da19fb) | Jul 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2ff464874e](https://linux-hardware.org/?probe=2ff464874e) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | [2a23928116](https://linux-hardware.org/?probe=2a23928116) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | [247870abec](https://linux-hardware.org/?probe=247870abec) | Jul 24, 2023 |
| ASUSTek       | PRIME X399-A                | [3dac76b45f](https://linux-hardware.org/?probe=3dac76b45f) | Jul 23, 2023 |
| ECS           | A780LM-M2                   | [b8b1304632](https://linux-hardware.org/?probe=b8b1304632) | Jul 22, 2023 |
| ASUSTek       | P9X79                       | [2f8efec736](https://linux-hardware.org/?probe=2f8efec736) | Jul 22, 2023 |
| Biostar       | A320MH                      | [b4ad5e7452](https://linux-hardware.org/?probe=b4ad5e7452) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [625e829a7e](https://linux-hardware.org/?probe=625e829a7e) | Jul 22, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [d47c43e734](https://linux-hardware.org/?probe=d47c43e734) | Jul 22, 2023 |
| MSI           | Z490-A PRO                  | [a55a67fa01](https://linux-hardware.org/?probe=a55a67fa01) | Jul 22, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [478fb56a7d](https://linux-hardware.org/?probe=478fb56a7d) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [cc9f1fdcd8](https://linux-hardware.org/?probe=cc9f1fdcd8) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [fc0fcad674](https://linux-hardware.org/?probe=fc0fcad674) | Jul 21, 2023 |
| ASUSTek       | VC66                        | [369cd2ba96](https://linux-hardware.org/?probe=369cd2ba96) | Jul 20, 2023 |
| MSI           | A88XM-E35 V2                | [7ab6252e08](https://linux-hardware.org/?probe=7ab6252e08) | Jul 19, 2023 |
| ASRock        | X570 Taichi                 | [db2a22c2eb](https://linux-hardware.org/?probe=db2a22c2eb) | Jul 19, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [b12aa2eb63](https://linux-hardware.org/?probe=b12aa2eb63) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [ab65cec6fe](https://linux-hardware.org/?probe=ab65cec6fe) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [8a9fabbdc0](https://linux-hardware.org/?probe=8a9fabbdc0) | Jul 19, 2023 |
| AZW           | U59                         | [1c919967a8](https://linux-hardware.org/?probe=1c919967a8) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c5475d0982](https://linux-hardware.org/?probe=c5475d0982) | Jul 18, 2023 |
| ONDA          | A320SD4-ITX Ver:2.00        | [ffe435deca](https://linux-hardware.org/?probe=ffe435deca) | Jul 18, 2023 |
| ASRock        | X470 Gaming K4              | [7217058966](https://linux-hardware.org/?probe=7217058966) | Jul 18, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [02f8df2129](https://linux-hardware.org/?probe=02f8df2129) | Jul 18, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [e7e056881b](https://linux-hardware.org/?probe=e7e056881b) | Jul 18, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [4e4d74fab5](https://linux-hardware.org/?probe=4e4d74fab5) | Jul 17, 2023 |
| Dell          | 0TY565                      | [1d6edab344](https://linux-hardware.org/?probe=1d6edab344) | Jul 17, 2023 |
| MSI           | H110M PRO-VD PLUS           | [98acac35e7](https://linux-hardware.org/?probe=98acac35e7) | Jul 17, 2023 |
| MSI           | H110M PRO-VD PLUS           | [de9a7deb3b](https://linux-hardware.org/?probe=de9a7deb3b) | Jul 17, 2023 |
| Gigabyte      | B450M H                     | [c659d8d6b5](https://linux-hardware.org/?probe=c659d8d6b5) | Jul 17, 2023 |
| Gigabyte      | Z77X-D3H                    | [8464b9ef50](https://linux-hardware.org/?probe=8464b9ef50) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [15d7862757](https://linux-hardware.org/?probe=15d7862757) | Jul 16, 2023 |
| Apple         | Mac-F221BEC8                | [5202874aa5](https://linux-hardware.org/?probe=5202874aa5) | Jul 16, 2023 |
| MSI           | G41M-P33 Combo              | [3f15239dd2](https://linux-hardware.org/?probe=3f15239dd2) | Jul 16, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [cbab6d2236](https://linux-hardware.org/?probe=cbab6d2236) | Jul 16, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [01ed316904](https://linux-hardware.org/?probe=01ed316904) | Jul 16, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [a4bd524029](https://linux-hardware.org/?probe=a4bd524029) | Jul 15, 2023 |
| Gigabyte      | B360M DS3H                  | [08dede9db3](https://linux-hardware.org/?probe=08dede9db3) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [4dc6731c7a](https://linux-hardware.org/?probe=4dc6731c7a) | Jul 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [e32b594990](https://linux-hardware.org/?probe=e32b594990) | Jul 14, 2023 |
| Pegatron      | 2ACB                        | [1f05cae239](https://linux-hardware.org/?probe=1f05cae239) | Jul 14, 2023 |
| ASUSTek       | STRIX Z270G GAMING          | [1857fae531](https://linux-hardware.org/?probe=1857fae531) | Jul 13, 2023 |
| ASUSTek       | PRIME H370-PLUS             | [8a2aeb02b0](https://linux-hardware.org/?probe=8a2aeb02b0) | Jul 13, 2023 |
| ASRock        | B450M Pro4                  | [30403bcd32](https://linux-hardware.org/?probe=30403bcd32) | Jul 12, 2023 |
| Dell          | 051FJ8 A02                  | [d8310de68b](https://linux-hardware.org/?probe=d8310de68b) | Jul 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [7573efcc6c](https://linux-hardware.org/?probe=7573efcc6c) | Jul 12, 2023 |
| ASUSTek       | Maximus VI EXTREME          | [ea9603099a](https://linux-hardware.org/?probe=ea9603099a) | Jul 12, 2023 |
| MSI           | Z170A PC MATE               | [39b5c3bb23](https://linux-hardware.org/?probe=39b5c3bb23) | Jul 11, 2023 |
| ASUSTek       | B85M-G R2.0                 | [477ec4d403](https://linux-hardware.org/?probe=477ec4d403) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [eb024b5188](https://linux-hardware.org/?probe=eb024b5188) | Jul 10, 2023 |
| ASRock        | A75 Extreme6                | [1c0eb1b3ea](https://linux-hardware.org/?probe=1c0eb1b3ea) | Jul 10, 2023 |
| HP            | 1998                        | [03da98871c](https://linux-hardware.org/?probe=03da98871c) | Jul 10, 2023 |
| ASRock        | B650 PG Lightning           | [86c4d26a95](https://linux-hardware.org/?probe=86c4d26a95) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [aa2805e577](https://linux-hardware.org/?probe=aa2805e577) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [a1b896bd04](https://linux-hardware.org/?probe=a1b896bd04) | Jul 09, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [3540170054](https://linux-hardware.org/?probe=3540170054) | Jul 08, 2023 |
| MSI           | B450M MORTAR MAX            | [6b4669ec61](https://linux-hardware.org/?probe=6b4669ec61) | Jul 08, 2023 |
| Positivo      | POS-PIG43BC SIM             | [42727a7888](https://linux-hardware.org/?probe=42727a7888) | Jul 08, 2023 |
| ASRockRack    | E3C236D4U                   | [83ed95f0d3](https://linux-hardware.org/?probe=83ed95f0d3) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [c199c7040b](https://linux-hardware.org/?probe=c199c7040b) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [49c59b6c86](https://linux-hardware.org/?probe=49c59b6c86) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [df2a737853](https://linux-hardware.org/?probe=df2a737853) | Jul 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [40d2eef376](https://linux-hardware.org/?probe=40d2eef376) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [25ea01643a](https://linux-hardware.org/?probe=25ea01643a) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [e5539c7298](https://linux-hardware.org/?probe=e5539c7298) | Jul 06, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [79bd04036c](https://linux-hardware.org/?probe=79bd04036c) | Jul 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a4b93f17c2](https://linux-hardware.org/?probe=a4b93f17c2) | Jul 05, 2023 |
| ASRock        | B450M Pro4                  | [3cf621f13b](https://linux-hardware.org/?probe=3cf621f13b) | Jul 05, 2023 |
| ASRock        | B450M Pro4                  | [eb325b1c2a](https://linux-hardware.org/?probe=eb325b1c2a) | Jul 04, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [5699e37170](https://linux-hardware.org/?probe=5699e37170) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [4b2cf13c22](https://linux-hardware.org/?probe=4b2cf13c22) | Jul 03, 2023 |
| HP            | 3047h                       | [7dfd0078f7](https://linux-hardware.org/?probe=7dfd0078f7) | Jul 03, 2023 |
| Huanan        | H610M-PLUS V1.2             | [0bc6a5e828](https://linux-hardware.org/?probe=0bc6a5e828) | Jul 03, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [5af51ee197](https://linux-hardware.org/?probe=5af51ee197) | Jul 03, 2023 |
| MSI           | Z590 PRO WIFI               | [4fb1a41361](https://linux-hardware.org/?probe=4fb1a41361) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [364082f281](https://linux-hardware.org/?probe=364082f281) | Jul 03, 2023 |
| Pegatron      | 2AD3                        | [fd445e9894](https://linux-hardware.org/?probe=fd445e9894) | Jul 02, 2023 |
| ASRock        | B550M PG Riptide            | [e578144ebb](https://linux-hardware.org/?probe=e578144ebb) | Jul 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [47654b63c6](https://linux-hardware.org/?probe=47654b63c6) | Jul 02, 2023 |
| ASRock        | B550M PG Riptide            | [83fd2dc626](https://linux-hardware.org/?probe=83fd2dc626) | Jul 02, 2023 |
| ASUSTek       | P8H77-M PRO                 | [5c3eb7ce7c](https://linux-hardware.org/?probe=5c3eb7ce7c) | Jul 02, 2023 |
| Unknown       | Unknown                     | [556867d0f2](https://linux-hardware.org/?probe=556867d0f2) | Jul 02, 2023 |
| Unknown       | Unknown                     | [b36612c9e4](https://linux-hardware.org/?probe=b36612c9e4) | Jul 02, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [b4e7dadba8](https://linux-hardware.org/?probe=b4e7dadba8) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9e65cd9bd1](https://linux-hardware.org/?probe=9e65cd9bd1) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a57586f69b](https://linux-hardware.org/?probe=a57586f69b) | Jul 01, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [f50a86955f](https://linux-hardware.org/?probe=f50a86955f) | Jul 01, 2023 |
| Dell          | 08NPPY A00                  | [9f1aec7e08](https://linux-hardware.org/?probe=9f1aec7e08) | Jul 01, 2023 |
| Gigabyte      | X79-UD3                     | [36fed79d81](https://linux-hardware.org/?probe=36fed79d81) | Jul 01, 2023 |
| Pegatron      | 2ACB                        | [ceb2b4c1c5](https://linux-hardware.org/?probe=ceb2b4c1c5) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ef49f25cf8](https://linux-hardware.org/?probe=ef49f25cf8) | Jun 30, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [45d5903c62](https://linux-hardware.org/?probe=45d5903c62) | Jun 30, 2023 |
| Gigabyte      | X79-UD3                     | [5a88d6945d](https://linux-hardware.org/?probe=5a88d6945d) | Jun 29, 2023 |
| Acer          | Aspire XC-830               | [eccf186dfd](https://linux-hardware.org/?probe=eccf186dfd) | Jun 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [56e2b61337](https://linux-hardware.org/?probe=56e2b61337) | Jun 29, 2023 |
| MSI           | B450 TOMAHAWK               | [86866241cd](https://linux-hardware.org/?probe=86866241cd) | Jun 29, 2023 |
| MSI           | B550-A PRO                  | [722b0302f4](https://linux-hardware.org/?probe=722b0302f4) | Jun 29, 2023 |
| Dell          | 0PC5F7 A01                  | [133ed5cc64](https://linux-hardware.org/?probe=133ed5cc64) | Jun 28, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [238e77122e](https://linux-hardware.org/?probe=238e77122e) | Jun 28, 2023 |
| Acer          | Veriton M490G               | [1f3da6e87f](https://linux-hardware.org/?probe=1f3da6e87f) | Jun 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [cd0c241308](https://linux-hardware.org/?probe=cd0c241308) | Jun 28, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [48b0ff43fa](https://linux-hardware.org/?probe=48b0ff43fa) | Jun 27, 2023 |
| HP            | 18E7                        | [1ae4c92b7f](https://linux-hardware.org/?probe=1ae4c92b7f) | Jun 26, 2023 |
| ASRock        | H55M                        | [cb9e89e20e](https://linux-hardware.org/?probe=cb9e89e20e) | Jun 24, 2023 |
| Gigabyte      | G1.Sniper Z87               | [8df9a683cb](https://linux-hardware.org/?probe=8df9a683cb) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | [4d419c5b63](https://linux-hardware.org/?probe=4d419c5b63) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [56208916c9](https://linux-hardware.org/?probe=56208916c9) | Jun 23, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [4cfd97f850](https://linux-hardware.org/?probe=4cfd97f850) | Jun 23, 2023 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | [7bf78e33d4](https://linux-hardware.org/?probe=7bf78e33d4) | Jun 22, 2023 |
| MSI           | B250M PRO-VDH               | [e8391a9f3d](https://linux-hardware.org/?probe=e8391a9f3d) | Jun 22, 2023 |
| HP            | 21EF                        | [6022eb31ff](https://linux-hardware.org/?probe=6022eb31ff) | Jun 21, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [ae2beb307a](https://linux-hardware.org/?probe=ae2beb307a) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [c2c2365360](https://linux-hardware.org/?probe=c2c2365360) | Jun 20, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [092370b958](https://linux-hardware.org/?probe=092370b958) | Jun 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | [9e30c629f3](https://linux-hardware.org/?probe=9e30c629f3) | Jun 19, 2023 |
| ASRock        | B550M-ITX/ac                | [e9865c622f](https://linux-hardware.org/?probe=e9865c622f) | Jun 19, 2023 |
| ASRock        | Z87 Extreme4                | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| MSI           | Z97-G45 GAMING              | [cb20c2c912](https://linux-hardware.org/?probe=cb20c2c912) | Jun 18, 2023 |
| Acer          | Veriton M490G               | [f9405b8bd2](https://linux-hardware.org/?probe=f9405b8bd2) | Jun 18, 2023 |
| Gigabyte      | H410M S2H V3                | [26e276dc29](https://linux-hardware.org/?probe=26e276dc29) | Jun 18, 2023 |
| Gigabyte      | H410M S2H V3                | [978e506718](https://linux-hardware.org/?probe=978e506718) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [94999d2965](https://linux-hardware.org/?probe=94999d2965) | Jun 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [9b5c44b13a](https://linux-hardware.org/?probe=9b5c44b13a) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [6294c25695](https://linux-hardware.org/?probe=6294c25695) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c338e10965](https://linux-hardware.org/?probe=c338e10965) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [176973d157](https://linux-hardware.org/?probe=176973d157) | Jun 16, 2023 |
| ASUSTek       | Maximus VI HERO             | [ae9d05ff3a](https://linux-hardware.org/?probe=ae9d05ff3a) | Jun 15, 2023 |
| Acer          | Aspire XC-830               | [ca0cba861a](https://linux-hardware.org/?probe=ca0cba861a) | Jun 15, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [c05a02e77b](https://linux-hardware.org/?probe=c05a02e77b) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [b548786e27](https://linux-hardware.org/?probe=b548786e27) | Jun 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [928063a305](https://linux-hardware.org/?probe=928063a305) | Jun 13, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [f0f0a1b2ac](https://linux-hardware.org/?probe=f0f0a1b2ac) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [74b5d0e60a](https://linux-hardware.org/?probe=74b5d0e60a) | Jun 13, 2023 |
| ASUSTek       | PRIME B450M-K II            | [0fe4687002](https://linux-hardware.org/?probe=0fe4687002) | Jun 12, 2023 |
| MSI           | Z590-A PRO                  | [bac6eb2f16](https://linux-hardware.org/?probe=bac6eb2f16) | Jun 12, 2023 |
| Acer          | Veriton M490G               | [78ff85b0a4](https://linux-hardware.org/?probe=78ff85b0a4) | Jun 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [e7d498373d](https://linux-hardware.org/?probe=e7d498373d) | Jun 11, 2023 |
| Unknown       | Unknown                     | [0d80451f80](https://linux-hardware.org/?probe=0d80451f80) | Jun 11, 2023 |
| Unknown       | Unknown                     | [b25c3a4ecb](https://linux-hardware.org/?probe=b25c3a4ecb) | Jun 11, 2023 |
| Gigabyte      | B460M DS3H                  | [63c9d6c822](https://linux-hardware.org/?probe=63c9d6c822) | Jun 09, 2023 |
| Gigabyte      | B550 AORUS PRO              | [61a0a2ea5f](https://linux-hardware.org/?probe=61a0a2ea5f) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | [8b8c6949b6](https://linux-hardware.org/?probe=8b8c6949b6) | Jun 09, 2023 |
| Gigabyte      | H81M-S2H                    | [fc60082dfe](https://linux-hardware.org/?probe=fc60082dfe) | Jun 08, 2023 |
| ASUSTek       | Maximus VI HERO             | [5861bc7cef](https://linux-hardware.org/?probe=5861bc7cef) | Jun 08, 2023 |
| ASUSTek       | PRIME B350M-A               | [ba4bfc1fe1](https://linux-hardware.org/?probe=ba4bfc1fe1) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | [5533070ec1](https://linux-hardware.org/?probe=5533070ec1) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Gigabyte      | H610M H DDR4                | [e7cdd7e89b](https://linux-hardware.org/?probe=e7cdd7e89b) | Jun 07, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [45cc99775f](https://linux-hardware.org/?probe=45cc99775f) | Jun 07, 2023 |
| HP            | 3396                        | [ca540b449f](https://linux-hardware.org/?probe=ca540b449f) | Jun 07, 2023 |
| Gigabyte      | X670 GAMING X AX            | [05d49007a4](https://linux-hardware.org/?probe=05d49007a4) | Jun 07, 2023 |
| ASUSTek       | X99-DELUXE II               | [aab84214f1](https://linux-hardware.org/?probe=aab84214f1) | Jun 06, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6cd3cfcacf](https://linux-hardware.org/?probe=6cd3cfcacf) | Jun 06, 2023 |
| MSI           | B450M MORTAR                | [6d2c05fd11](https://linux-hardware.org/?probe=6d2c05fd11) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [54e2e07ac6](https://linux-hardware.org/?probe=54e2e07ac6) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [292e41c0e9](https://linux-hardware.org/?probe=292e41c0e9) | Jun 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [8c6a275a93](https://linux-hardware.org/?probe=8c6a275a93) | Jun 05, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [8cbfe4cdf0](https://linux-hardware.org/?probe=8cbfe4cdf0) | Jun 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| ASRock        | QC5000M-ITX/PH              | [bdf4ee4d4f](https://linux-hardware.org/?probe=bdf4ee4d4f) | Jun 04, 2023 |
| MSI           | B450M MORTAR MAX            | [72ccbe10aa](https://linux-hardware.org/?probe=72ccbe10aa) | Jun 04, 2023 |
| Unknown       | Intel X79                   | [0e2e65a79e](https://linux-hardware.org/?probe=0e2e65a79e) | Jun 04, 2023 |
| MSI           | PRO Z790-P WIFI             | [fb0c1a4922](https://linux-hardware.org/?probe=fb0c1a4922) | Jun 04, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a90856c944](https://linux-hardware.org/?probe=a90856c944) | Jun 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [0523005c68](https://linux-hardware.org/?probe=0523005c68) | Jun 03, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [1908e7e6f5](https://linux-hardware.org/?probe=1908e7e6f5) | Jun 03, 2023 |
| ASUSTek       | Z170-A                      | [4f512af4c2](https://linux-hardware.org/?probe=4f512af4c2) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d2189d4a5f](https://linux-hardware.org/?probe=d2189d4a5f) | Jun 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [d61bd0903e](https://linux-hardware.org/?probe=d61bd0903e) | Jun 02, 2023 |
| ASRock        | X370 Pro4                   | [aaeac4c226](https://linux-hardware.org/?probe=aaeac4c226) | Jun 01, 2023 |
| MSI           | MAG B460 TOMAHAWK           | [8389c76bd3](https://linux-hardware.org/?probe=8389c76bd3) | May 31, 2023 |
| Dell          | 0N4YC8 A00                  | [4a3e8c4d6f](https://linux-hardware.org/?probe=4a3e8c4d6f) | May 31, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [4dfacbbeb1](https://linux-hardware.org/?probe=4dfacbbeb1) | May 31, 2023 |
| ASRock        | B550M Steel Legend          | [ab97cb7f09](https://linux-hardware.org/?probe=ab97cb7f09) | May 30, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [b00cd1c84e](https://linux-hardware.org/?probe=b00cd1c84e) | May 30, 2023 |
| Cincoze       | 1.0.01.001                  | [1552e93368](https://linux-hardware.org/?probe=1552e93368) | May 30, 2023 |
| Dell          | 02N3WF A01                  | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| ASRock        | B450M Pro4                  | [c98400b6eb](https://linux-hardware.org/?probe=c98400b6eb) | May 30, 2023 |
| Dell          | 0XPDFK A01                  | [10e4fd14b5](https://linux-hardware.org/?probe=10e4fd14b5) | May 29, 2023 |
| ASRock        | Z370 Professional Gaming... | [f7d00f30cb](https://linux-hardware.org/?probe=f7d00f30cb) | May 28, 2023 |
| ASUSTek       | PRIME Z590-A                | [b5e36f87e6](https://linux-hardware.org/?probe=b5e36f87e6) | May 28, 2023 |
| ASRock        | H510M-HVS R2.0              | [c4ee84b38e](https://linux-hardware.org/?probe=c4ee84b38e) | May 28, 2023 |
| Gigabyte      | B660 DS3H DDR4              | [807dd44df4](https://linux-hardware.org/?probe=807dd44df4) | May 28, 2023 |
| HP            | 2AF7                        | [b459ce46cb](https://linux-hardware.org/?probe=b459ce46cb) | May 27, 2023 |
| ASRock        | H81M-VG4                    | [4e7b273239](https://linux-hardware.org/?probe=4e7b273239) | May 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [acee298918](https://linux-hardware.org/?probe=acee298918) | May 26, 2023 |
| Acer          | WG43M                       | [9afcfc4a44](https://linux-hardware.org/?probe=9afcfc4a44) | May 26, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [f757bc2c6e](https://linux-hardware.org/?probe=f757bc2c6e) | May 25, 2023 |
| HP            | 8643 SMVB                   | [961a04643c](https://linux-hardware.org/?probe=961a04643c) | May 25, 2023 |
| MSI           | X99A GAMING PRO CARBON      | [4c9595e6ea](https://linux-hardware.org/?probe=4c9595e6ea) | May 24, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e4c9c425f8](https://linux-hardware.org/?probe=e4c9c425f8) | May 23, 2023 |
| ASUSTek       | PRIME X399-A                | [a5a990a94c](https://linux-hardware.org/?probe=a5a990a94c) | May 23, 2023 |
| MSI           | X99A GAMING PRO CARBON      | [d0312b1a56](https://linux-hardware.org/?probe=d0312b1a56) | May 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | [aa33ddd283](https://linux-hardware.org/?probe=aa33ddd283) | May 23, 2023 |
| MSI           | B550-A PRO[CEC]             | [66b4de8c55](https://linux-hardware.org/?probe=66b4de8c55) | May 22, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [a8e6f277e2](https://linux-hardware.org/?probe=a8e6f277e2) | May 22, 2023 |
| MSI           | MPG Z790 EDGE WIFI          | [30e9eb3dd1](https://linux-hardware.org/?probe=30e9eb3dd1) | May 21, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [1e231f6e75](https://linux-hardware.org/?probe=1e231f6e75) | May 21, 2023 |
| HP            | 339A                        | [d4a8f3dbb1](https://linux-hardware.org/?probe=d4a8f3dbb1) | May 21, 2023 |
| ASRock        | Z790M-ITX WiFi              | [2229714a14](https://linux-hardware.org/?probe=2229714a14) | May 21, 2023 |
| ASRock        | 970A-G                      | [fd39b2185b](https://linux-hardware.org/?probe=fd39b2185b) | May 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6bcf177a20](https://linux-hardware.org/?probe=6bcf177a20) | May 20, 2023 |
| HP            | 8437                        | [d41a0c8439](https://linux-hardware.org/?probe=d41a0c8439) | May 20, 2023 |
| ASRock        | 970A-G                      | [fac3e3c961](https://linux-hardware.org/?probe=fac3e3c961) | May 20, 2023 |
| HP            | 8437                        | [ceacc79bf6](https://linux-hardware.org/?probe=ceacc79bf6) | May 19, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [515e752ecb](https://linux-hardware.org/?probe=515e752ecb) | May 19, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | [693c7b6d9b](https://linux-hardware.org/?probe=693c7b6d9b) | May 18, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | [e0ebac1371](https://linux-hardware.org/?probe=e0ebac1371) | May 18, 2023 |
| ASUSTek       | PRIME X570-PRO              | [09e723be6f](https://linux-hardware.org/?probe=09e723be6f) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | [dc1bf86813](https://linux-hardware.org/?probe=dc1bf86813) | May 17, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [377fe6aa67](https://linux-hardware.org/?probe=377fe6aa67) | May 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [16308738b3](https://linux-hardware.org/?probe=16308738b3) | May 15, 2023 |
| Gigabyte      | X570S AERO G                | [0f70383aab](https://linux-hardware.org/?probe=0f70383aab) | May 14, 2023 |
| Gigabyte      | Z170X-UD5 TH-CF             | [6a84af6428](https://linux-hardware.org/?probe=6a84af6428) | May 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6bfe747b4d](https://linux-hardware.org/?probe=6bfe747b4d) | May 13, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [7a38cda53d](https://linux-hardware.org/?probe=7a38cda53d) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [2c03c64f49](https://linux-hardware.org/?probe=2c03c64f49) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [e5dbe4c6f4](https://linux-hardware.org/?probe=e5dbe4c6f4) | May 13, 2023 |
| ASUSTek       | P8Z77-V LE                  | [0a23198016](https://linux-hardware.org/?probe=0a23198016) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1146828988](https://linux-hardware.org/?probe=1146828988) | May 13, 2023 |
| ASRock        | A320M/ac                    | [c244810475](https://linux-hardware.org/?probe=c244810475) | May 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [713564ccd4](https://linux-hardware.org/?probe=713564ccd4) | May 12, 2023 |
| Gigabyte      | X570S AERO G                | [ff26b44641](https://linux-hardware.org/?probe=ff26b44641) | May 12, 2023 |
| Gigabyte      | X570S AERO G                | [00abecb77e](https://linux-hardware.org/?probe=00abecb77e) | May 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [cfa81980a9](https://linux-hardware.org/?probe=cfa81980a9) | May 12, 2023 |
| Huanan        | X99-F8 Gaming 2021          | [fb4cf864f2](https://linux-hardware.org/?probe=fb4cf864f2) | May 11, 2023 |
| ASRock        | B450 Pro4                   | [928216a0a5](https://linux-hardware.org/?probe=928216a0a5) | May 10, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [bd5c79fbaf](https://linux-hardware.org/?probe=bd5c79fbaf) | May 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [47fea42b65](https://linux-hardware.org/?probe=47fea42b65) | May 09, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [2cbff804d8](https://linux-hardware.org/?probe=2cbff804d8) | May 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | [9e3f14cf8d](https://linux-hardware.org/?probe=9e3f14cf8d) | May 08, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [ecfcb0cab6](https://linux-hardware.org/?probe=ecfcb0cab6) | May 07, 2023 |
| ASRock        | 4X4-4000 Series             | [df056ec6f1](https://linux-hardware.org/?probe=df056ec6f1) | May 07, 2023 |
| MSI           | 970A-G46                    | [37f3da239a](https://linux-hardware.org/?probe=37f3da239a) | May 07, 2023 |
| ASUSTek       | M4N72-E                     | [30deed8e5a](https://linux-hardware.org/?probe=30deed8e5a) | May 07, 2023 |
| ASRock        | B450M Steel Legend          | [dc317ab270](https://linux-hardware.org/?probe=dc317ab270) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | [2e02937097](https://linux-hardware.org/?probe=2e02937097) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | [051da44921](https://linux-hardware.org/?probe=051da44921) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [3c8f9ed664](https://linux-hardware.org/?probe=3c8f9ed664) | May 06, 2023 |
| ASUSTek       | Z170-P                      | [756e372a11](https://linux-hardware.org/?probe=756e372a11) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [f2d8df2880](https://linux-hardware.org/?probe=f2d8df2880) | May 05, 2023 |
| Gigabyte      | Z590 UD AC                  | [b8f920797f](https://linux-hardware.org/?probe=b8f920797f) | May 05, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [9b013ebf89](https://linux-hardware.org/?probe=9b013ebf89) | May 05, 2023 |
| ASRock        | A320M-DVS R4.0              | [2b273ee426](https://linux-hardware.org/?probe=2b273ee426) | May 05, 2023 |
| MSI           | Z390-A PRO                  | [0501f3a43b](https://linux-hardware.org/?probe=0501f3a43b) | May 04, 2023 |
| MSI           | Z270-A PRO                  | [ec8586e070](https://linux-hardware.org/?probe=ec8586e070) | May 04, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [e42327b375](https://linux-hardware.org/?probe=e42327b375) | May 04, 2023 |
| MSI           | PRO B550M-VC WIFI           | [f677ec7e51](https://linux-hardware.org/?probe=f677ec7e51) | May 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | [df62d15ecc](https://linux-hardware.org/?probe=df62d15ecc) | May 03, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aac11fced2](https://linux-hardware.org/?probe=aac11fced2) | May 03, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [50f922927f](https://linux-hardware.org/?probe=50f922927f) | May 03, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [c8b7ffa6dc](https://linux-hardware.org/?probe=c8b7ffa6dc) | May 02, 2023 |
| Gigabyte      | X99-UD4-CF                  | [c2dcdb892d](https://linux-hardware.org/?probe=c2dcdb892d) | May 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | [8fb29cf081](https://linux-hardware.org/?probe=8fb29cf081) | May 01, 2023 |
| HP            | 8906 SMVB                   | [3fc2c4e9d9](https://linux-hardware.org/?probe=3fc2c4e9d9) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [dd0a47b6fc](https://linux-hardware.org/?probe=dd0a47b6fc) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [7087295cd7](https://linux-hardware.org/?probe=7087295cd7) | May 01, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [0aa17c06c5](https://linux-hardware.org/?probe=0aa17c06c5) | Apr 30, 2023 |
| MSI           | B360M MORTAR                | [352a47b8a0](https://linux-hardware.org/?probe=352a47b8a0) | Apr 30, 2023 |
| ASRock        | B550 Pro4                   | [5d0819f25c](https://linux-hardware.org/?probe=5d0819f25c) | Apr 28, 2023 |
| HP            | 82F2 A01                    | [ea8f7364db](https://linux-hardware.org/?probe=ea8f7364db) | Apr 27, 2023 |
| ASRock        | A330GC                      | [d1a2e8dd13](https://linux-hardware.org/?probe=d1a2e8dd13) | Apr 27, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [62996d1f05](https://linux-hardware.org/?probe=62996d1f05) | Apr 26, 2023 |
| ASUSTek       | PRIME B450M-A II            | [1ce9a878f3](https://linux-hardware.org/?probe=1ce9a878f3) | Apr 26, 2023 |
| ASRock        | B450 Pro4                   | [bd406c08f8](https://linux-hardware.org/?probe=bd406c08f8) | Apr 25, 2023 |
| Gigabyte      | H87-D3H-CF                  | [b3a3115f0c](https://linux-hardware.org/?probe=b3a3115f0c) | Apr 25, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [7595e7d8f9](https://linux-hardware.org/?probe=7595e7d8f9) | Apr 25, 2023 |
| eMachines     | EMCP73VT-PM                 | [d1a5ad5a38](https://linux-hardware.org/?probe=d1a5ad5a38) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b4b468d0db](https://linux-hardware.org/?probe=b4b468d0db) | Apr 24, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [34278ef67e](https://linux-hardware.org/?probe=34278ef67e) | Apr 24, 2023 |
| Intel         | HM570                       | [1220357b3d](https://linux-hardware.org/?probe=1220357b3d) | Apr 24, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [c11ea1fc19](https://linux-hardware.org/?probe=c11ea1fc19) | Apr 23, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [1a316c62a1](https://linux-hardware.org/?probe=1a316c62a1) | Apr 23, 2023 |
| ASRock        | A520M-ITX/ac                | [ef59f5ff9b](https://linux-hardware.org/?probe=ef59f5ff9b) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [dfb9f87dad](https://linux-hardware.org/?probe=dfb9f87dad) | Apr 22, 2023 |
| ASRock        | H61M/U3S3                   | [8fd7aea5ea](https://linux-hardware.org/?probe=8fd7aea5ea) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0de425d51e](https://linux-hardware.org/?probe=0de425d51e) | Apr 21, 2023 |
| ASRock        | H510M-HVS R2.0              | [1de5b776a3](https://linux-hardware.org/?probe=1de5b776a3) | Apr 21, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [a7b05c2528](https://linux-hardware.org/?probe=a7b05c2528) | Apr 20, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [68e853f4c1](https://linux-hardware.org/?probe=68e853f4c1) | Apr 20, 2023 |
| Intel         | X79-SERVER V1.1             | [384c50e703](https://linux-hardware.org/?probe=384c50e703) | Apr 20, 2023 |
| MSI           | H110M PRO-VD                | [509d9126e1](https://linux-hardware.org/?probe=509d9126e1) | Apr 19, 2023 |
| ASRock        | B250M Pro4                  | [5d27011671](https://linux-hardware.org/?probe=5d27011671) | Apr 19, 2023 |
| ASRock        | B550 Steel Legend           | [35534cbfba](https://linux-hardware.org/?probe=35534cbfba) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [c00d85072e](https://linux-hardware.org/?probe=c00d85072e) | Apr 18, 2023 |
| ASRock        | A320M-DVS R4.0              | [b715989fc4](https://linux-hardware.org/?probe=b715989fc4) | Apr 16, 2023 |
| ASRock        | A320M-DVS R4.0              | [213ac87204](https://linux-hardware.org/?probe=213ac87204) | Apr 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [7820a9b7bc](https://linux-hardware.org/?probe=7820a9b7bc) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4375bd0fb6](https://linux-hardware.org/?probe=4375bd0fb6) | Apr 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [0f678c5ded](https://linux-hardware.org/?probe=0f678c5ded) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [ee48e89e45](https://linux-hardware.org/?probe=ee48e89e45) | Apr 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | [57cc389eff](https://linux-hardware.org/?probe=57cc389eff) | Apr 14, 2023 |
| Biostar       | G31D-M7                     | [bb518a8623](https://linux-hardware.org/?probe=bb518a8623) | Apr 14, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [71d89005dd](https://linux-hardware.org/?probe=71d89005dd) | Apr 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [9f723bfac9](https://linux-hardware.org/?probe=9f723bfac9) | Apr 14, 2023 |
| ASRock        | B450M Pro4                  | [62dd8e069f](https://linux-hardware.org/?probe=62dd8e069f) | Apr 13, 2023 |
| HP            | 8906 SMVB                   | [c639e22b34](https://linux-hardware.org/?probe=c639e22b34) | Apr 13, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [796f3afe73](https://linux-hardware.org/?probe=796f3afe73) | Apr 12, 2023 |
| Acer          | WG43M                       | [e22afb229d](https://linux-hardware.org/?probe=e22afb229d) | Apr 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [2a108e9eed](https://linux-hardware.org/?probe=2a108e9eed) | Apr 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [c31f7b3b5c](https://linux-hardware.org/?probe=c31f7b3b5c) | Apr 10, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [fff8cbca92](https://linux-hardware.org/?probe=fff8cbca92) | Apr 10, 2023 |
| ASUSTek       | P7H55-M PRO                 | [69ee985017](https://linux-hardware.org/?probe=69ee985017) | Apr 09, 2023 |
| MSI           | A320M PRO-VD PLUS           | [709cc4af2c](https://linux-hardware.org/?probe=709cc4af2c) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [cc25df15df](https://linux-hardware.org/?probe=cc25df15df) | Apr 08, 2023 |
| HP            | 8906 SMVB                   | [44351926f8](https://linux-hardware.org/?probe=44351926f8) | Apr 08, 2023 |
| MSI           | B250M PRO-VDH               | [123883b7dd](https://linux-hardware.org/?probe=123883b7dd) | Apr 06, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [712e78de35](https://linux-hardware.org/?probe=712e78de35) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK               | [0b4faaa32e](https://linux-hardware.org/?probe=0b4faaa32e) | Apr 05, 2023 |
| Gigabyte      | B360M D2V                   | [d2850d3f77](https://linux-hardware.org/?probe=d2850d3f77) | Apr 03, 2023 |
| MSI           | B450 TOMAHAWK               | [416152a691](https://linux-hardware.org/?probe=416152a691) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8f8d89fe9a](https://linux-hardware.org/?probe=8f8d89fe9a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a5d404ca3d](https://linux-hardware.org/?probe=a5d404ca3d) | Apr 02, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [b4207e264f](https://linux-hardware.org/?probe=b4207e264f) | Apr 02, 2023 |
| ASRock        | B450M Pro4                  | [7bfb9086ab](https://linux-hardware.org/?probe=7bfb9086ab) | Apr 02, 2023 |
| ASUSTek       | P8H67-V                     | [3a488490ce](https://linux-hardware.org/?probe=3a488490ce) | Apr 02, 2023 |
| Gigabyte      | X570S AERO G                | [015b741441](https://linux-hardware.org/?probe=015b741441) | Apr 01, 2023 |
| AZW           | MINI S 10                   | [19d66110ff](https://linux-hardware.org/?probe=19d66110ff) | Apr 01, 2023 |
| Dell          | 0MGK50 A02                  | [3a042b5160](https://linux-hardware.org/?probe=3a042b5160) | Apr 01, 2023 |
| MSI           | P43T-C51                    | [d16b44b442](https://linux-hardware.org/?probe=d16b44b442) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [59c335754f](https://linux-hardware.org/?probe=59c335754f) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [8326806aa6](https://linux-hardware.org/?probe=8326806aa6) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| ASRock        | B550M-C                     | [c0fcfbc0ed](https://linux-hardware.org/?probe=c0fcfbc0ed) | Mar 31, 2023 |
| ASRock        | H67DE3                      | [b055ccc048](https://linux-hardware.org/?probe=b055ccc048) | Mar 31, 2023 |
| ASRock        | H67DE3                      | [c82ba90d70](https://linux-hardware.org/?probe=c82ba90d70) | Mar 31, 2023 |
| Gigabyte      | Z390 M-CF                   | [6bce2b9bc3](https://linux-hardware.org/?probe=6bce2b9bc3) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [ebd6135034](https://linux-hardware.org/?probe=ebd6135034) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [88864f0e2d](https://linux-hardware.org/?probe=88864f0e2d) | Mar 31, 2023 |
| Acer          | WG43M                       | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| MSI           | A320M PRO-VD PLUS           | [9e43a17d1a](https://linux-hardware.org/?probe=9e43a17d1a) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| IP3 Tech      | IB8                         | [c12033f9e7](https://linux-hardware.org/?probe=c12033f9e7) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d1e1b40549](https://linux-hardware.org/?probe=d1e1b40549) | Mar 28, 2023 |
| ASUSTek       | PRIME H370-PLUS             | [4a7e7763c1](https://linux-hardware.org/?probe=4a7e7763c1) | Mar 28, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [29ec74ac8b](https://linux-hardware.org/?probe=29ec74ac8b) | Mar 27, 2023 |
| Acer          | WG43M                       | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cba16003d7](https://linux-hardware.org/?probe=cba16003d7) | Mar 26, 2023 |
| Dell          | 0MGK50 A02                  | [93b35b776a](https://linux-hardware.org/?probe=93b35b776a) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [c722a5f7b2](https://linux-hardware.org/?probe=c722a5f7b2) | Mar 26, 2023 |
| ASUSTek       | PRIME Z390-A                | [b9095b98c4](https://linux-hardware.org/?probe=b9095b98c4) | Mar 25, 2023 |
| MSI           | X470 GAMING PRO             | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [99da9866a9](https://linux-hardware.org/?probe=99da9866a9) | Mar 25, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [2f5c339d88](https://linux-hardware.org/?probe=2f5c339d88) | Mar 25, 2023 |
| MSI           | B450M BAZOOKA V2            | [3677f24e87](https://linux-hardware.org/?probe=3677f24e87) | Mar 25, 2023 |
| ASRock        | B550AM Gaming               | [be6e8f17cc](https://linux-hardware.org/?probe=be6e8f17cc) | Mar 25, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [4eb8132fd2](https://linux-hardware.org/?probe=4eb8132fd2) | Mar 24, 2023 |
| MSI           | B450 TOMAHAWK               | [29fce46770](https://linux-hardware.org/?probe=29fce46770) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [56854770ba](https://linux-hardware.org/?probe=56854770ba) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [62a95efc48](https://linux-hardware.org/?probe=62a95efc48) | Mar 23, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [a36464850a](https://linux-hardware.org/?probe=a36464850a) | Mar 23, 2023 |
| ASRock        | B450M Steel Legend          | [9795961bca](https://linux-hardware.org/?probe=9795961bca) | Mar 22, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [1e299101d8](https://linux-hardware.org/?probe=1e299101d8) | Mar 22, 2023 |
| ASRock        | AB350 Pro4                  | [7336ce9057](https://linux-hardware.org/?probe=7336ce9057) | Mar 21, 2023 |
| ASRock        | AB350 Pro4                  | [01e06fb483](https://linux-hardware.org/?probe=01e06fb483) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [7d1cd9aded](https://linux-hardware.org/?probe=7d1cd9aded) | Mar 20, 2023 |
| Gigabyte      | P31-DS3L                    | [7fb5a2f07e](https://linux-hardware.org/?probe=7fb5a2f07e) | Mar 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f9c84aa26c](https://linux-hardware.org/?probe=f9c84aa26c) | Mar 20, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | [19a060d86d](https://linux-hardware.org/?probe=19a060d86d) | Mar 20, 2023 |
| Gigabyte      | B450M H                     | [ad5218c0bf](https://linux-hardware.org/?probe=ad5218c0bf) | Mar 19, 2023 |
| MSI           | B450 TOMAHAWK               | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| ASUSTek       | M4A87TD/USB3                | [ed76176dfa](https://linux-hardware.org/?probe=ed76176dfa) | Mar 18, 2023 |
| Gigabyte      | 945GCM-S2L                  | [4b484ab326](https://linux-hardware.org/?probe=4b484ab326) | Mar 18, 2023 |
| BESSTAR Te... | HM90                        | [c20318c7c0](https://linux-hardware.org/?probe=c20318c7c0) | Mar 18, 2023 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [be6db6cc62](https://linux-hardware.org/?probe=be6db6cc62) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [2215bc867b](https://linux-hardware.org/?probe=2215bc867b) | Mar 17, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [fff0c55980](https://linux-hardware.org/?probe=fff0c55980) | Mar 17, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [538477684f](https://linux-hardware.org/?probe=538477684f) | Mar 17, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [f3bb3c5ef1](https://linux-hardware.org/?probe=f3bb3c5ef1) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [fc7d8aee1f](https://linux-hardware.org/?probe=fc7d8aee1f) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [062ba6c2b9](https://linux-hardware.org/?probe=062ba6c2b9) | Mar 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8a802fa8fe](https://linux-hardware.org/?probe=8a802fa8fe) | Mar 16, 2023 |
| ASRock        | B450M Steel Legend          | [ae258d05b1](https://linux-hardware.org/?probe=ae258d05b1) | Mar 16, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [9765f2823e](https://linux-hardware.org/?probe=9765f2823e) | Mar 16, 2023 |
| Dell          | 0773VG A00                  | [53c02c1bb8](https://linux-hardware.org/?probe=53c02c1bb8) | Mar 16, 2023 |
| ASRock        | Z390M-ITX/ac                | [623a5ed92b](https://linux-hardware.org/?probe=623a5ed92b) | Mar 15, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [7649d9be35](https://linux-hardware.org/?probe=7649d9be35) | Mar 14, 2023 |
| Dell          | 0773VG A00                  | [42baaa40b9](https://linux-hardware.org/?probe=42baaa40b9) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2662a08251](https://linux-hardware.org/?probe=2662a08251) | Mar 14, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [d507b4619f](https://linux-hardware.org/?probe=d507b4619f) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [0b0840b785](https://linux-hardware.org/?probe=0b0840b785) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [25c6ceb9e8](https://linux-hardware.org/?probe=25c6ceb9e8) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1e2dd83baa](https://linux-hardware.org/?probe=1e2dd83baa) | Mar 13, 2023 |
| ASUSTek       | PRIME B560M-A               | [a7e24ac4b6](https://linux-hardware.org/?probe=a7e24ac4b6) | Mar 13, 2023 |
| Gigabyte      | X570S AERO G                | [7c00691824](https://linux-hardware.org/?probe=7c00691824) | Mar 12, 2023 |
| ASRock        | Z97M Pro4                   | [7ce318cc22](https://linux-hardware.org/?probe=7ce318cc22) | Mar 12, 2023 |
| ASUSTek       | PRIME Z590-A                | [751bedd6a9](https://linux-hardware.org/?probe=751bedd6a9) | Mar 12, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [7a20b4f81a](https://linux-hardware.org/?probe=7a20b4f81a) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [053e36ef52](https://linux-hardware.org/?probe=053e36ef52) | Mar 12, 2023 |
| Intel         | JSL MRD                     | [28832d0a36](https://linux-hardware.org/?probe=28832d0a36) | Mar 11, 2023 |
| Gigabyte      | A520I AC                    | [f1e983c2dc](https://linux-hardware.org/?probe=f1e983c2dc) | Mar 10, 2023 |
| Dell          | 0DFRFW A01                  | [9552c8c0ab](https://linux-hardware.org/?probe=9552c8c0ab) | Mar 10, 2023 |
| ASUSTek       | PRIME B450M-A               | [ceb2734b56](https://linux-hardware.org/?probe=ceb2734b56) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [447f2ec783](https://linux-hardware.org/?probe=447f2ec783) | Mar 09, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [9c59079b1f](https://linux-hardware.org/?probe=9c59079b1f) | Mar 09, 2023 |
| Acer          | Veriton M480                | [8cd45e8525](https://linux-hardware.org/?probe=8cd45e8525) | Mar 09, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [69564be379](https://linux-hardware.org/?probe=69564be379) | Mar 08, 2023 |
| Intel         | B75 V124                    | [8a643c9a04](https://linux-hardware.org/?probe=8a643c9a04) | Mar 08, 2023 |
| Intel         | B75 V124                    | [777cb32ba1](https://linux-hardware.org/?probe=777cb32ba1) | Mar 08, 2023 |
| ASUSTek       | H81T                        | [c17251dbd9](https://linux-hardware.org/?probe=c17251dbd9) | Mar 08, 2023 |
| MSI           | B450M MORTAR MAX            | [f8eea076e5](https://linux-hardware.org/?probe=f8eea076e5) | Mar 05, 2023 |
| MSI           | 970A-G46                    | [6f3850aa74](https://linux-hardware.org/?probe=6f3850aa74) | Mar 05, 2023 |
| ASUSTek       | M5A97 PLUS                  | [24d58ff4fc](https://linux-hardware.org/?probe=24d58ff4fc) | Mar 05, 2023 |
| HP            | 3397                        | [5250af801f](https://linux-hardware.org/?probe=5250af801f) | Mar 04, 2023 |
| MSI           | 970A-G46                    | [804b0fa4da](https://linux-hardware.org/?probe=804b0fa4da) | Mar 04, 2023 |
| Gigabyte      | B450M S2H                   | [1ccfddfbc0](https://linux-hardware.org/?probe=1ccfddfbc0) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c19189c929](https://linux-hardware.org/?probe=c19189c929) | Mar 04, 2023 |
| ASRock        | B550M Pro4                  | [5823762138](https://linux-hardware.org/?probe=5823762138) | Mar 03, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [860f53436b](https://linux-hardware.org/?probe=860f53436b) | Mar 03, 2023 |
| HP            | 82F2 A01                    | [305779159c](https://linux-hardware.org/?probe=305779159c) | Mar 02, 2023 |
| MSI           | MEG X670E ACE               | [ee356bc253](https://linux-hardware.org/?probe=ee356bc253) | Mar 02, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [8ac11055c8](https://linux-hardware.org/?probe=8ac11055c8) | Mar 02, 2023 |
| HP            | 8906 SMVB                   | [72b59f777e](https://linux-hardware.org/?probe=72b59f777e) | Mar 01, 2023 |
| ASRock        | B660M-STX                   | [5a32d2e162](https://linux-hardware.org/?probe=5a32d2e162) | Feb 28, 2023 |
| MSI           | 760GMA-P34                  | [9707436005](https://linux-hardware.org/?probe=9707436005) | Feb 28, 2023 |
| ASRock        | B365M-HDV                   | [def987e32c](https://linux-hardware.org/?probe=def987e32c) | Feb 28, 2023 |
| ASUSTek       | CM6870                      | [e338b721af](https://linux-hardware.org/?probe=e338b721af) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [62a7d7ef5c](https://linux-hardware.org/?probe=62a7d7ef5c) | Feb 28, 2023 |
| MSI           | B550-A PRO[CEC]             | [2465135444](https://linux-hardware.org/?probe=2465135444) | Feb 28, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [05542207ee](https://linux-hardware.org/?probe=05542207ee) | Feb 28, 2023 |
| Gigabyte      | AX370-Gaming K7             | [d4bcf9b7a2](https://linux-hardware.org/?probe=d4bcf9b7a2) | Feb 28, 2023 |
| MSI           | Z390-A PRO                  | [979b4559fe](https://linux-hardware.org/?probe=979b4559fe) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3ac3b5424a](https://linux-hardware.org/?probe=3ac3b5424a) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | [d6f5b00609](https://linux-hardware.org/?probe=d6f5b00609) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | [89cd5d5c44](https://linux-hardware.org/?probe=89cd5d5c44) | Feb 26, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [83c075f5c5](https://linux-hardware.org/?probe=83c075f5c5) | Feb 26, 2023 |
| MSI           | B550-A PRO[CEC]             | [9c1dad9bdc](https://linux-hardware.org/?probe=9c1dad9bdc) | Feb 25, 2023 |
| ASRock        | B450 Pro4                   | [926fcff980](https://linux-hardware.org/?probe=926fcff980) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH P67              | [efdc981614](https://linux-hardware.org/?probe=efdc981614) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [bea010d25e](https://linux-hardware.org/?probe=bea010d25e) | Feb 24, 2023 |
| ASRock        | B450M Steel Legend          | [69475d0fa7](https://linux-hardware.org/?probe=69475d0fa7) | Feb 23, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [beb6e53cb7](https://linux-hardware.org/?probe=beb6e53cb7) | Feb 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [640957cabe](https://linux-hardware.org/?probe=640957cabe) | Feb 23, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [601836815c](https://linux-hardware.org/?probe=601836815c) | Feb 22, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [aa39c9a471](https://linux-hardware.org/?probe=aa39c9a471) | Feb 22, 2023 |
| MSI           | B450 TOMAHAWK               | [53e8b0db7d](https://linux-hardware.org/?probe=53e8b0db7d) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-K               | [cfcf2ff473](https://linux-hardware.org/?probe=cfcf2ff473) | Feb 21, 2023 |
| ASUSTek       | G11CD                       | [4fc47f45be](https://linux-hardware.org/?probe=4fc47f45be) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ecc97fee86](https://linux-hardware.org/?probe=ecc97fee86) | Feb 21, 2023 |
| AZW           | GK55                        | [e8376dbc54](https://linux-hardware.org/?probe=e8376dbc54) | Feb 19, 2023 |
| ASRock        | AB350 Pro4                  | [0f1365d8d8](https://linux-hardware.org/?probe=0f1365d8d8) | Feb 19, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | [5b452754c0](https://linux-hardware.org/?probe=5b452754c0) | Feb 19, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [82fd276e35](https://linux-hardware.org/?probe=82fd276e35) | Feb 19, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [f8f6e2baea](https://linux-hardware.org/?probe=f8f6e2baea) | Feb 19, 2023 |
| MSI           | A320M-A PRO MAX             | [c1e5226b6e](https://linux-hardware.org/?probe=c1e5226b6e) | Feb 18, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [be751c4a5b](https://linux-hardware.org/?probe=be751c4a5b) | Feb 18, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [d0bb58e003](https://linux-hardware.org/?probe=d0bb58e003) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [322588bc4e](https://linux-hardware.org/?probe=322588bc4e) | Feb 18, 2023 |
| Gateway       | SX2803                      | [a1b20489b4](https://linux-hardware.org/?probe=a1b20489b4) | Feb 17, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [4948ea8836](https://linux-hardware.org/?probe=4948ea8836) | Feb 17, 2023 |
| HP            | 18E7                        | [821ea2c921](https://linux-hardware.org/?probe=821ea2c921) | Feb 17, 2023 |
| MSI           | A520M-A PRO                 | [fd678baa9f](https://linux-hardware.org/?probe=fd678baa9f) | Feb 16, 2023 |
| ASRock        | Z390M Pro4                  | [cf96b55907](https://linux-hardware.org/?probe=cf96b55907) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4e3ff30332](https://linux-hardware.org/?probe=4e3ff30332) | Feb 15, 2023 |
| MSI           | A320M-A PRO MAX             | [dd2017324e](https://linux-hardware.org/?probe=dd2017324e) | Feb 14, 2023 |
| ASUSTek       | PRIME Z590-A                | [926e34c5a9](https://linux-hardware.org/?probe=926e34c5a9) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d1171fb67b](https://linux-hardware.org/?probe=d1171fb67b) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [cd29998b19](https://linux-hardware.org/?probe=cd29998b19) | Feb 13, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [89f1272cd8](https://linux-hardware.org/?probe=89f1272cd8) | Feb 13, 2023 |
| ASUSTek       | PRIME Z390-P                | [8ac5b193cb](https://linux-hardware.org/?probe=8ac5b193cb) | Feb 13, 2023 |
| ASUSTek       | PRIME Z390-P                | [156fae6b82](https://linux-hardware.org/?probe=156fae6b82) | Feb 13, 2023 |
| HP            | 3397                        | [83dc4a9ea0](https://linux-hardware.org/?probe=83dc4a9ea0) | Feb 13, 2023 |
| HP            | 3397                        | [cc7019baaa](https://linux-hardware.org/?probe=cc7019baaa) | Feb 13, 2023 |
| MSI           | A320M-A PRO MAX             | [f5ef3d92cb](https://linux-hardware.org/?probe=f5ef3d92cb) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | [219157717b](https://linux-hardware.org/?probe=219157717b) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | [cdc63fb05e](https://linux-hardware.org/?probe=cdc63fb05e) | Feb 12, 2023 |
| Gigabyte      | B450M DS3H V2               | [a326374047](https://linux-hardware.org/?probe=a326374047) | Feb 12, 2023 |
| Dell          | 0M017G A00                  | [f2deee99d1](https://linux-hardware.org/?probe=f2deee99d1) | Feb 11, 2023 |
| ASRock        | Z790M-ITX WiFi              | [ca7e69040a](https://linux-hardware.org/?probe=ca7e69040a) | Feb 11, 2023 |
| Dell          | 0M017G A00                  | [30965e948d](https://linux-hardware.org/?probe=30965e948d) | Feb 10, 2023 |
| Dell          | 04YJ19 A00                  | [972fb9a299](https://linux-hardware.org/?probe=972fb9a299) | Feb 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [04929299d7](https://linux-hardware.org/?probe=04929299d7) | Feb 10, 2023 |
| MSI           | X470 GAMING PRO             | [a53ab3e915](https://linux-hardware.org/?probe=a53ab3e915) | Feb 10, 2023 |
| ASRock        | B450M Pro4-F                | [35bd9cf04c](https://linux-hardware.org/?probe=35bd9cf04c) | Feb 09, 2023 |
| ASUSTek       | PRIME B450M-A               | [f669c49cf5](https://linux-hardware.org/?probe=f669c49cf5) | Feb 09, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [fa2a1dba2d](https://linux-hardware.org/?probe=fa2a1dba2d) | Feb 09, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [cdfbd3e72a](https://linux-hardware.org/?probe=cdfbd3e72a) | Feb 09, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [58346a45de](https://linux-hardware.org/?probe=58346a45de) | Feb 08, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [e533f4d15f](https://linux-hardware.org/?probe=e533f4d15f) | Feb 08, 2023 |
| MSI           | H510M PRO-E                 | [577d1f97d8](https://linux-hardware.org/?probe=577d1f97d8) | Feb 08, 2023 |
| MSI           | H510M PRO-E                 | [2b7b643f2e](https://linux-hardware.org/?probe=2b7b643f2e) | Feb 08, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [01872da4ea](https://linux-hardware.org/?probe=01872da4ea) | Feb 07, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [c73a4ad56a](https://linux-hardware.org/?probe=c73a4ad56a) | Feb 06, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [f91035a72a](https://linux-hardware.org/?probe=f91035a72a) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [bdd3224e6c](https://linux-hardware.org/?probe=bdd3224e6c) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [79548473df](https://linux-hardware.org/?probe=79548473df) | Feb 05, 2023 |
| Unknown       | X79A                        | [eedea973ca](https://linux-hardware.org/?probe=eedea973ca) | Feb 05, 2023 |
| Dell          | 0GDG8Y A00                  | [b9b0a6cccb](https://linux-hardware.org/?probe=b9b0a6cccb) | Feb 04, 2023 |
| MSI           | Z490-A PRO                  | [d82820c304](https://linux-hardware.org/?probe=d82820c304) | Feb 04, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [2594dddd54](https://linux-hardware.org/?probe=2594dddd54) | Feb 04, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [4d007a868e](https://linux-hardware.org/?probe=4d007a868e) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [29dc75351d](https://linux-hardware.org/?probe=29dc75351d) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [54d35f2b7f](https://linux-hardware.org/?probe=54d35f2b7f) | Feb 03, 2023 |
| Gigabyte      | G31M-S2C                    | [3e5a2f20cc](https://linux-hardware.org/?probe=3e5a2f20cc) | Feb 03, 2023 |
| ASRock        | X300M-STX                   | [5ce1aa97c6](https://linux-hardware.org/?probe=5ce1aa97c6) | Feb 02, 2023 |
| HP            | 8906 SMVB                   | [82845bb849](https://linux-hardware.org/?probe=82845bb849) | Feb 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [1ca0a608f9](https://linux-hardware.org/?probe=1ca0a608f9) | Feb 02, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [1fddf279a5](https://linux-hardware.org/?probe=1fddf279a5) | Feb 02, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [09430385c6](https://linux-hardware.org/?probe=09430385c6) | Feb 02, 2023 |
| Dell          | 0T10XW A02                  | [10e5f7904a](https://linux-hardware.org/?probe=10e5f7904a) | Feb 02, 2023 |
| Gigabyte      | B650M DS3H                  | [981bcc29a7](https://linux-hardware.org/?probe=981bcc29a7) | Feb 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | [adb2f19fcd](https://linux-hardware.org/?probe=adb2f19fcd) | Feb 01, 2023 |
| MSI           | D2415 S26361-D2415-A21      | [3acfaaf14c](https://linux-hardware.org/?probe=3acfaaf14c) | Feb 01, 2023 |
| MSI           | B250M PRO-VDH               | [1dbacce612](https://linux-hardware.org/?probe=1dbacce612) | Feb 01, 2023 |
| Gigabyte      | B450M H                     | [2d4aa2e1a0](https://linux-hardware.org/?probe=2d4aa2e1a0) | Feb 01, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [caa1c9e23a](https://linux-hardware.org/?probe=caa1c9e23a) | Jan 31, 2023 |
| ASUSTek       | Z87M-PLUS                   | [8512c1d0cc](https://linux-hardware.org/?probe=8512c1d0cc) | Jan 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eb4687961f](https://linux-hardware.org/?probe=eb4687961f) | Jan 31, 2023 |
| MACHINIST     | X99Z V102 IENGINEER         | [d2cfaf56df](https://linux-hardware.org/?probe=d2cfaf56df) | Jan 31, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [7893a67a4b](https://linux-hardware.org/?probe=7893a67a4b) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [97aa61aba5](https://linux-hardware.org/?probe=97aa61aba5) | Jan 29, 2023 |
| ASUSTek       | Z170M-E D3                  | [2b466d1b19](https://linux-hardware.org/?probe=2b466d1b19) | Jan 29, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [b9a38b7494](https://linux-hardware.org/?probe=b9a38b7494) | Jan 29, 2023 |
| Toshiba       | STI 010433                  | [fead488cf1](https://linux-hardware.org/?probe=fead488cf1) | Jan 29, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [cba2528a29](https://linux-hardware.org/?probe=cba2528a29) | Jan 28, 2023 |
| ASRock        | X570 Pro4                   | [bf09bd7413](https://linux-hardware.org/?probe=bf09bd7413) | Jan 28, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [41ff395299](https://linux-hardware.org/?probe=41ff395299) | Jan 28, 2023 |
| MSI           | 970A-G46                    | [ece518ec34](https://linux-hardware.org/?probe=ece518ec34) | Jan 28, 2023 |
| Gigabyte      | J3455N-D3H                  | [3eb9131ab1](https://linux-hardware.org/?probe=3eb9131ab1) | Jan 27, 2023 |
| HP            | 8054                        | [864f5f225e](https://linux-hardware.org/?probe=864f5f225e) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [4ad0b3594f](https://linux-hardware.org/?probe=4ad0b3594f) | Jan 26, 2023 |
| ASUSTek       | PRIME H310M-K               | [ec43ef5c17](https://linux-hardware.org/?probe=ec43ef5c17) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [78b817b650](https://linux-hardware.org/?probe=78b817b650) | Jan 24, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [81c1e35182](https://linux-hardware.org/?probe=81c1e35182) | Jan 24, 2023 |
| HP            | 2B2C                        | [01cb4bc77f](https://linux-hardware.org/?probe=01cb4bc77f) | Jan 23, 2023 |
| T-bao         | MINI PC V1.0                | [6d1c897198](https://linux-hardware.org/?probe=6d1c897198) | Jan 23, 2023 |
| MSI           | B150 PC MATE                | [741901eb8f](https://linux-hardware.org/?probe=741901eb8f) | Jan 23, 2023 |
| ASRock        | B450 Pro4                   | [9beaa4240c](https://linux-hardware.org/?probe=9beaa4240c) | Jan 22, 2023 |
| Gigabyte      | A320M-H-CF                  | [14a5fa99db](https://linux-hardware.org/?probe=14a5fa99db) | Jan 22, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [77a744c052](https://linux-hardware.org/?probe=77a744c052) | Jan 22, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b4591be73d](https://linux-hardware.org/?probe=b4591be73d) | Jan 21, 2023 |
| Gigabyte      | GB-BRR7H-4800               | [0f0f1ed390](https://linux-hardware.org/?probe=0f0f1ed390) | Jan 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [b6b4b01344](https://linux-hardware.org/?probe=b6b4b01344) | Jan 20, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [9b4b20b28d](https://linux-hardware.org/?probe=9b4b20b28d) | Jan 20, 2023 |
| ASUSTek       | H110M-R                     | [f872a64ba1](https://linux-hardware.org/?probe=f872a64ba1) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [02089f3393](https://linux-hardware.org/?probe=02089f3393) | Jan 20, 2023 |
| MSI           | PRO B650M-A WIFI            | [3eb4809e32](https://linux-hardware.org/?probe=3eb4809e32) | Jan 19, 2023 |
| ASUSTek       | H110M-C/BR                  | [58bed7db63](https://linux-hardware.org/?probe=58bed7db63) | Jan 19, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [0c77a64f45](https://linux-hardware.org/?probe=0c77a64f45) | Jan 18, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [457c3d4d50](https://linux-hardware.org/?probe=457c3d4d50) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR            | [bcae5d5664](https://linux-hardware.org/?probe=bcae5d5664) | Jan 18, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [273e93cce5](https://linux-hardware.org/?probe=273e93cce5) | Jan 18, 2023 |
| ASUSTek       | Z97M-PLUS                   | [ea58101334](https://linux-hardware.org/?probe=ea58101334) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0e57f4ecbe](https://linux-hardware.org/?probe=0e57f4ecbe) | Jan 15, 2023 |
| Foxconn       | nT-i2000 Series PCB         | [a879fdd461](https://linux-hardware.org/?probe=a879fdd461) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [482cc76bce](https://linux-hardware.org/?probe=482cc76bce) | Jan 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [662223c5f6](https://linux-hardware.org/?probe=662223c5f6) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | [77adbc7487](https://linux-hardware.org/?probe=77adbc7487) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | [e430030b47](https://linux-hardware.org/?probe=e430030b47) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [8fbf586d24](https://linux-hardware.org/?probe=8fbf586d24) | Jan 14, 2023 |
| ASUSTek       | PRIME B550M-A               | [3365f7d56f](https://linux-hardware.org/?probe=3365f7d56f) | Jan 14, 2023 |
| Gigabyte      | B550M DS3H                  | [5de8333ea3](https://linux-hardware.org/?probe=5de8333ea3) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [fcda893618](https://linux-hardware.org/?probe=fcda893618) | Jan 13, 2023 |
| MSI           | 970A-G46                    | [32479ec724](https://linux-hardware.org/?probe=32479ec724) | Jan 13, 2023 |
| ASUSTek       | PRIME B550M-A               | [25a1763f73](https://linux-hardware.org/?probe=25a1763f73) | Jan 13, 2023 |
| ASUSTek       | B85M-E                      | [5ee23ee475](https://linux-hardware.org/?probe=5ee23ee475) | Jan 12, 2023 |
| Nvidia        | AN-M2                       | [8a7aad3266](https://linux-hardware.org/?probe=8a7aad3266) | Jan 12, 2023 |
| Dell          | 0DXJD9 A01                  | [78549912fa](https://linux-hardware.org/?probe=78549912fa) | Jan 12, 2023 |
| MSI           | Z490-A PRO                  | [bbcffca1e1](https://linux-hardware.org/?probe=bbcffca1e1) | Jan 11, 2023 |
| ASUSTek       | PRIME A320M-K               | [54711252e5](https://linux-hardware.org/?probe=54711252e5) | Jan 11, 2023 |
| Dell          | 0K3CM7 A00                  | [2c317eaef8](https://linux-hardware.org/?probe=2c317eaef8) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a1e541c1b3](https://linux-hardware.org/?probe=a1e541c1b3) | Jan 11, 2023 |
| HP            | 8767 A                      | [7b2c61c215](https://linux-hardware.org/?probe=7b2c61c215) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a57b3e3df6](https://linux-hardware.org/?probe=a57b3e3df6) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [694c5c31f9](https://linux-hardware.org/?probe=694c5c31f9) | Jan 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [47ac5c5ee1](https://linux-hardware.org/?probe=47ac5c5ee1) | Jan 10, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [8e857e93de](https://linux-hardware.org/?probe=8e857e93de) | Jan 10, 2023 |
| Gigabyte      | H410M S2H V3                | [1ec26d7d15](https://linux-hardware.org/?probe=1ec26d7d15) | Jan 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [7193f85a8c](https://linux-hardware.org/?probe=7193f85a8c) | Jan 09, 2023 |
| Gigabyte      | B550M DS3H                  | [3e39bca3ed](https://linux-hardware.org/?probe=3e39bca3ed) | Jan 09, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [9bf425bc2d](https://linux-hardware.org/?probe=9bf425bc2d) | Jan 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [153884836e](https://linux-hardware.org/?probe=153884836e) | Jan 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [06f9209282](https://linux-hardware.org/?probe=06f9209282) | Jan 08, 2023 |
| Gigabyte      | B550M DS3H                  | [faf4eff378](https://linux-hardware.org/?probe=faf4eff378) | Jan 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [a885b118ab](https://linux-hardware.org/?probe=a885b118ab) | Jan 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [27c42e99db](https://linux-hardware.org/?probe=27c42e99db) | Jan 08, 2023 |
| MSI           | Z270 PC MATE                | [4d780d6bf9](https://linux-hardware.org/?probe=4d780d6bf9) | Jan 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [ddae48cdbb](https://linux-hardware.org/?probe=ddae48cdbb) | Jan 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [8b38f9336f](https://linux-hardware.org/?probe=8b38f9336f) | Jan 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [7a2744ca03](https://linux-hardware.org/?probe=7a2744ca03) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | [aa21c2b75f](https://linux-hardware.org/?probe=aa21c2b75f) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6cd2288696](https://linux-hardware.org/?probe=6cd2288696) | Jan 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [ed168f4e29](https://linux-hardware.org/?probe=ed168f4e29) | Jan 05, 2023 |
| Dell          | 0HY9JP A01                  | [0532ee0c1e](https://linux-hardware.org/?probe=0532ee0c1e) | Jan 05, 2023 |
| ASRock        | H310M-HDV/M.2               | [cf98b88234](https://linux-hardware.org/?probe=cf98b88234) | Jan 05, 2023 |
| ASRock        | X570 Steel Legend           | [584234b202](https://linux-hardware.org/?probe=584234b202) | Jan 05, 2023 |
| Gigabyte      | H87-D3H-CF                  | [5b13eb0dad](https://linux-hardware.org/?probe=5b13eb0dad) | Jan 04, 2023 |
| MSI           | H110M PRO-VD                | [5b2857e18b](https://linux-hardware.org/?probe=5b2857e18b) | Jan 04, 2023 |
| Gigabyte      | Z490M GAMING X              | [9012a42d6e](https://linux-hardware.org/?probe=9012a42d6e) | Jan 03, 2023 |
| ASUSTek       | Maximus IX CODE             | [25d993017e](https://linux-hardware.org/?probe=25d993017e) | Jan 02, 2023 |
| Gigabyte      | B550M AORUS PRO             | [bc36d65732](https://linux-hardware.org/?probe=bc36d65732) | Jan 02, 2023 |
| PCWare        | IPMH110G                    | [a795f33f7a](https://linux-hardware.org/?probe=a795f33f7a) | Jan 02, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [30abdaa93b](https://linux-hardware.org/?probe=30abdaa93b) | Jan 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [a6540a8761](https://linux-hardware.org/?probe=a6540a8761) | Jan 01, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [0db2db0d47](https://linux-hardware.org/?probe=0db2db0d47) | Jan 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [162ad451eb](https://linux-hardware.org/?probe=162ad451eb) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ea3b140a7f](https://linux-hardware.org/?probe=ea3b140a7f) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek       | PRIME B250M-K               | [9db6f0fda7](https://linux-hardware.org/?probe=9db6f0fda7) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [fc2f55c02e](https://linux-hardware.org/?probe=fc2f55c02e) | Dec 31, 2022 |
| ASUSTek       | PRIME B550M-A               | [83810bf0a9](https://linux-hardware.org/?probe=83810bf0a9) | Dec 30, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| ASUSTek       | PRIME B550M-A               | [da9b785d2a](https://linux-hardware.org/?probe=da9b785d2a) | Dec 30, 2022 |
| ASRock        | B650M PG Riptide            | [614e6307eb](https://linux-hardware.org/?probe=614e6307eb) | Dec 29, 2022 |
| ASUSTek       | PRIME B550M-A               | [e6ac6cac6c](https://linux-hardware.org/?probe=e6ac6cac6c) | Dec 29, 2022 |
| ASUSTek       | PRIME B550M-A               | [1219225d5d](https://linux-hardware.org/?probe=1219225d5d) | Dec 28, 2022 |
| ASRock        | X570M Pro4                  | [71d2c76079](https://linux-hardware.org/?probe=71d2c76079) | Dec 28, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [79427500b5](https://linux-hardware.org/?probe=79427500b5) | Dec 28, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | [b9fd8381a4](https://linux-hardware.org/?probe=b9fd8381a4) | Dec 27, 2022 |
| ASRock        | H61M-HG4                    | [8658fa0fa3](https://linux-hardware.org/?probe=8658fa0fa3) | Dec 27, 2022 |
| HP            | 2B29                        | [b83d4fafa0](https://linux-hardware.org/?probe=b83d4fafa0) | Dec 26, 2022 |
| ASUSTek       | B85M-GAMER                  | [ded2e7e4e6](https://linux-hardware.org/?probe=ded2e7e4e6) | Dec 26, 2022 |
| ASUSTek       | PRIME B550M-A               | [8ca73d6b87](https://linux-hardware.org/?probe=8ca73d6b87) | Dec 26, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5d95c28ac6](https://linux-hardware.org/?probe=5d95c28ac6) | Dec 25, 2022 |
| Biostar       | AM1MHP                      | [a4c61d5381](https://linux-hardware.org/?probe=a4c61d5381) | Dec 25, 2022 |
| ASUSTek       | M5A97 PLUS                  | [8a1cb3f5e7](https://linux-hardware.org/?probe=8a1cb3f5e7) | Dec 25, 2022 |
| MSI           | 970A-G46                    | [4b2435b250](https://linux-hardware.org/?probe=4b2435b250) | Dec 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [8bfc8d2560](https://linux-hardware.org/?probe=8bfc8d2560) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [a98ca87f6a](https://linux-hardware.org/?probe=a98ca87f6a) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [00af244895](https://linux-hardware.org/?probe=00af244895) | Dec 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [457612540c](https://linux-hardware.org/?probe=457612540c) | Dec 24, 2022 |
| Gigabyte      | AX370-Gaming-CF             | [4770daed30](https://linux-hardware.org/?probe=4770daed30) | Dec 24, 2022 |
| ASUSTek       | PRIME B550M-A               | [52edc0816c](https://linux-hardware.org/?probe=52edc0816c) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-K II            | [9a6b000b23](https://linux-hardware.org/?probe=9a6b000b23) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fe5df748b0](https://linux-hardware.org/?probe=fe5df748b0) | Dec 23, 2022 |
| ASUSTek       | PRIME B550M-A               | [83436ff428](https://linux-hardware.org/?probe=83436ff428) | Dec 22, 2022 |
| ASUSTek       | PRIME B550M-A               | [90f9fb28f8](https://linux-hardware.org/?probe=90f9fb28f8) | Dec 22, 2022 |
| Gigabyte      | B450 AORUS M                | [74f0c818d6](https://linux-hardware.org/?probe=74f0c818d6) | Dec 21, 2022 |
| ASUSTek       | PRIME H510M-K               | [768834619c](https://linux-hardware.org/?probe=768834619c) | Dec 21, 2022 |
| ASUSTek       | PRIME X399-A                | [243fccb6fa](https://linux-hardware.org/?probe=243fccb6fa) | Dec 21, 2022 |
| ASUSTek       | PRIME B550M-A               | [3f3d7ab961](https://linux-hardware.org/?probe=3f3d7ab961) | Dec 21, 2022 |
| ASUSTek       | PRIME B550M-A               | [487d7751d8](https://linux-hardware.org/?probe=487d7751d8) | Dec 20, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [70b20b876e](https://linux-hardware.org/?probe=70b20b876e) | Dec 19, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [afcae667f0](https://linux-hardware.org/?probe=afcae667f0) | Dec 19, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [17618a8281](https://linux-hardware.org/?probe=17618a8281) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [8d21cb0063](https://linux-hardware.org/?probe=8d21cb0063) | Dec 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2d046f9339](https://linux-hardware.org/?probe=2d046f9339) | Dec 18, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [4760b50d21](https://linux-hardware.org/?probe=4760b50d21) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7964862f29](https://linux-hardware.org/?probe=7964862f29) | Dec 18, 2022 |
| Intel         | H55                         | [a5033f178f](https://linux-hardware.org/?probe=a5033f178f) | Dec 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [43d229d12e](https://linux-hardware.org/?probe=43d229d12e) | Dec 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a8936bc5e3](https://linux-hardware.org/?probe=a8936bc5e3) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [f9f06d0bcb](https://linux-hardware.org/?probe=f9f06d0bcb) | Dec 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [5f8287cae9](https://linux-hardware.org/?probe=5f8287cae9) | Dec 17, 2022 |
| HP            | 83EE                        | [a008cde5ae](https://linux-hardware.org/?probe=a008cde5ae) | Dec 17, 2022 |
| Intel         | DH55PJ AAE93812-303         | [bf511c3913](https://linux-hardware.org/?probe=bf511c3913) | Dec 16, 2022 |
| Gigabyte      | B150-HD3P-CF                | [18b9f94390](https://linux-hardware.org/?probe=18b9f94390) | Dec 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [62395615bf](https://linux-hardware.org/?probe=62395615bf) | Dec 15, 2022 |
| ASUSTek       | PRIME B550M-A               | [2495c6742d](https://linux-hardware.org/?probe=2495c6742d) | Dec 15, 2022 |
| Dell          | 0HY9JP A00                  | [82d5ee3bbe](https://linux-hardware.org/?probe=82d5ee3bbe) | Dec 15, 2022 |
| ASUSTek       | PRIME B550M-A               | [eace53ab64](https://linux-hardware.org/?probe=eace53ab64) | Dec 15, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [d087536cbf](https://linux-hardware.org/?probe=d087536cbf) | Dec 14, 2022 |
| ASUSTek       | PRIME B550M-A               | [a2fc1288f1](https://linux-hardware.org/?probe=a2fc1288f1) | Dec 14, 2022 |
| PCWare        | IPMH110G                    | [baa0f26af0](https://linux-hardware.org/?probe=baa0f26af0) | Dec 13, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [3d835ed57d](https://linux-hardware.org/?probe=3d835ed57d) | Dec 12, 2022 |
| ASUSTek       | PRIME B550M-K               | [fa85be7b33](https://linux-hardware.org/?probe=fa85be7b33) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [2c52e941ea](https://linux-hardware.org/?probe=2c52e941ea) | Dec 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [5073afb493](https://linux-hardware.org/?probe=5073afb493) | Dec 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ad6dc99c8a](https://linux-hardware.org/?probe=ad6dc99c8a) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-K               | [c8890a2f74](https://linux-hardware.org/?probe=c8890a2f74) | Dec 09, 2022 |
| ASRock        | X300M-STX                   | [a6f72ec4e3](https://linux-hardware.org/?probe=a6f72ec4e3) | Dec 09, 2022 |
| MSI           | B450 TOMAHAWK               | [b822420d6d](https://linux-hardware.org/?probe=b822420d6d) | Dec 09, 2022 |
| ASUSTek       | P8P67 DELUXE                | [82fdec2637](https://linux-hardware.org/?probe=82fdec2637) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | [5e58e0fc36](https://linux-hardware.org/?probe=5e58e0fc36) | Dec 08, 2022 |
| Gigabyte      | B550 GAMING X V2            | [7ac17baea3](https://linux-hardware.org/?probe=7ac17baea3) | Dec 07, 2022 |
| ASUSTek       | PRIME B550M-A               | [5b4cf72d01](https://linux-hardware.org/?probe=5b4cf72d01) | Dec 07, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [def749869a](https://linux-hardware.org/?probe=def749869a) | Dec 07, 2022 |
| ASUSTek       | P5Q DELUXE                  | [1519fb3a87](https://linux-hardware.org/?probe=1519fb3a87) | Dec 06, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [2ddb168532](https://linux-hardware.org/?probe=2ddb168532) | Dec 05, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [76ce7610ea](https://linux-hardware.org/?probe=76ce7610ea) | Dec 05, 2022 |
| PCWare        | IPMH110G                    | [0574aeace9](https://linux-hardware.org/?probe=0574aeace9) | Dec 05, 2022 |
| Dell          | 0NNFGG A00                  | [b955357ccc](https://linux-hardware.org/?probe=b955357ccc) | Dec 05, 2022 |
| ASUSTek       | PRIME B550M-A               | [d081f85083](https://linux-hardware.org/?probe=d081f85083) | Dec 05, 2022 |
| ASRock        | J4205-ITX                   | [f5eb647cc9](https://linux-hardware.org/?probe=f5eb647cc9) | Dec 04, 2022 |
| Gigabyte      | Z370M DS3H-CF               | [580b716020](https://linux-hardware.org/?probe=580b716020) | Dec 03, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [f477b8f059](https://linux-hardware.org/?probe=f477b8f059) | Dec 03, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [7a778f7987](https://linux-hardware.org/?probe=7a778f7987) | Dec 02, 2022 |
| ASUSTek       | SABERTOOTH X79              | [85f6854ce5](https://linux-hardware.org/?probe=85f6854ce5) | Dec 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [919c5d80c8](https://linux-hardware.org/?probe=919c5d80c8) | Dec 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0949d0916c](https://linux-hardware.org/?probe=0949d0916c) | Dec 02, 2022 |
| Shuttle       | FS81                        | [6352050887](https://linux-hardware.org/?probe=6352050887) | Dec 02, 2022 |
| Gigabyte      | B360M D3H-CF                | [e902390c9c](https://linux-hardware.org/?probe=e902390c9c) | Dec 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [f9ff6b9e31](https://linux-hardware.org/?probe=f9ff6b9e31) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [3c05de2bb5](https://linux-hardware.org/?probe=3c05de2bb5) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [17e6d4dbb5](https://linux-hardware.org/?probe=17e6d4dbb5) | Dec 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [7ff54a3b05](https://linux-hardware.org/?probe=7ff54a3b05) | Dec 01, 2022 |
| ASUSTek       | PRIME B550M-A               | [5b86ca0927](https://linux-hardware.org/?probe=5b86ca0927) | Dec 01, 2022 |
| MSI           | B450-A PRO MAX              | [8de79673ea](https://linux-hardware.org/?probe=8de79673ea) | Dec 01, 2022 |
| MSI           | B450-A PRO MAX              | [e2f97abdea](https://linux-hardware.org/?probe=e2f97abdea) | Nov 30, 2022 |
| ASUSTek       | P8P67 DELUXE                | [c117ba54ea](https://linux-hardware.org/?probe=c117ba54ea) | Nov 30, 2022 |
| Dell          | 0WWJRX A00                  | [83ef480c7d](https://linux-hardware.org/?probe=83ef480c7d) | Nov 30, 2022 |
| MSI           | MAG B550M MORTAR            | [b4c010a2b2](https://linux-hardware.org/?probe=b4c010a2b2) | Nov 30, 2022 |
| ASUSTek       | P8P67 DELUXE                | [47131749a5](https://linux-hardware.org/?probe=47131749a5) | Nov 30, 2022 |
| IBM           | MSI-9151 Boards             | [720ff829b9](https://linux-hardware.org/?probe=720ff829b9) | Nov 29, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ff119f84e6](https://linux-hardware.org/?probe=ff119f84e6) | Nov 29, 2022 |
| ASUSTek       | H110M-K                     | [becbfa5cc7](https://linux-hardware.org/?probe=becbfa5cc7) | Nov 28, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b0078eda9b](https://linux-hardware.org/?probe=b0078eda9b) | Nov 27, 2022 |
| ASUSTek       | P7H55-M                     | [e5ac492508](https://linux-hardware.org/?probe=e5ac492508) | Nov 27, 2022 |
| MSI           | X570-A PRO                  | [c2c27cf47f](https://linux-hardware.org/?probe=c2c27cf47f) | Nov 27, 2022 |
| ASUSTek       | PRIME B550M-A               | [7bdb03388b](https://linux-hardware.org/?probe=7bdb03388b) | Nov 27, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [098116b1d6](https://linux-hardware.org/?probe=098116b1d6) | Nov 26, 2022 |
| ASRock        | B460M-HDV                   | [00c07e7aa9](https://linux-hardware.org/?probe=00c07e7aa9) | Nov 25, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [d2d484b35b](https://linux-hardware.org/?probe=d2d484b35b) | Nov 24, 2022 |
| Gateway       | SX2803                      | [68a008f332](https://linux-hardware.org/?probe=68a008f332) | Nov 24, 2022 |
| ASUSTek       | PRIME B550M-A               | [ed9d641fda](https://linux-hardware.org/?probe=ed9d641fda) | Nov 23, 2022 |
| PCWare        | IPMH110G                    | [7d952c2b0d](https://linux-hardware.org/?probe=7d952c2b0d) | Nov 22, 2022 |
| Gigabyte      | H110M-H-CF                  | [fdafa2db2a](https://linux-hardware.org/?probe=fdafa2db2a) | Nov 22, 2022 |
| ASUSTek       | P5E3 Deluxe                 | [c14020107c](https://linux-hardware.org/?probe=c14020107c) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8de96e0012](https://linux-hardware.org/?probe=8de96e0012) | Nov 20, 2022 |
| ASUSTek       | PRIME TRX40-PRO             | [ecafbb7acb](https://linux-hardware.org/?probe=ecafbb7acb) | Nov 20, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [9b0f3f926d](https://linux-hardware.org/?probe=9b0f3f926d) | Nov 20, 2022 |
| ASUSTek       | PRIME Z590-A                | [ba2c2a39ed](https://linux-hardware.org/?probe=ba2c2a39ed) | Nov 20, 2022 |
| ASUSTek       | PRIME Z590-A                | [07985535f4](https://linux-hardware.org/?probe=07985535f4) | Nov 20, 2022 |
| ASRock        | AB350M-HDV                  | [9484c00cb6](https://linux-hardware.org/?probe=9484c00cb6) | Nov 20, 2022 |
| HP            | 8055                        | [65b0ad04f1](https://linux-hardware.org/?probe=65b0ad04f1) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [08372f6535](https://linux-hardware.org/?probe=08372f6535) | Nov 20, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [9d276a36d8](https://linux-hardware.org/?probe=9d276a36d8) | Nov 19, 2022 |
| Gigabyte      | B660M DS3H DDR4             | [4956957df8](https://linux-hardware.org/?probe=4956957df8) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [362cf69f1f](https://linux-hardware.org/?probe=362cf69f1f) | Nov 19, 2022 |
| ASUSTek       | PRIME B550M-A               | [9b19115bc7](https://linux-hardware.org/?probe=9b19115bc7) | Nov 18, 2022 |
| ASRock        | X470 Taichi Ultimate        | [7c8a72cae4](https://linux-hardware.org/?probe=7c8a72cae4) | Nov 18, 2022 |
| MSI           | H110M PRO-VH PLUS           | [54f40f8c4b](https://linux-hardware.org/?probe=54f40f8c4b) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | [469ead98f8](https://linux-hardware.org/?probe=469ead98f8) | Nov 17, 2022 |
| Foxconn       | 2ABF                        | [018a2825bf](https://linux-hardware.org/?probe=018a2825bf) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bb2db87e9a](https://linux-hardware.org/?probe=bb2db87e9a) | Nov 17, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8a9570e828](https://linux-hardware.org/?probe=8a9570e828) | Nov 17, 2022 |
| MSI           | Z590 PRO WIFI               | [c53f301391](https://linux-hardware.org/?probe=c53f301391) | Nov 16, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [b0c0ad46de](https://linux-hardware.org/?probe=b0c0ad46de) | Nov 16, 2022 |
| ASUSTek       | PRIME B550M-A               | [5ce6a414cd](https://linux-hardware.org/?probe=5ce6a414cd) | Nov 16, 2022 |
| HP            | 83EE                        | [182682b17c](https://linux-hardware.org/?probe=182682b17c) | Nov 16, 2022 |
| HP            | 83EE                        | [65d7bade6e](https://linux-hardware.org/?probe=65d7bade6e) | Nov 16, 2022 |
| Unknown       | Unknown                     | [ca24381492](https://linux-hardware.org/?probe=ca24381492) | Nov 15, 2022 |
| ASUSTek       | A58M-A/USB3                 | [f6342a3d18](https://linux-hardware.org/?probe=f6342a3d18) | Nov 15, 2022 |
| Gigabyte      | B450M DS3H V2               | [dc808c4131](https://linux-hardware.org/?probe=dc808c4131) | Nov 14, 2022 |
| Dell          | 03KWTV A02                  | [2853121816](https://linux-hardware.org/?probe=2853121816) | Nov 14, 2022 |
| Gigabyte      | B550M DS3H                  | [c16c0f7d8f](https://linux-hardware.org/?probe=c16c0f7d8f) | Nov 13, 2022 |
| HP            | 88BE                        | [1c03e5957d](https://linux-hardware.org/?probe=1c03e5957d) | Nov 13, 2022 |
| EVGA          | Z690 CLASSIFIED.0           | [aabaab5ceb](https://linux-hardware.org/?probe=aabaab5ceb) | Nov 13, 2022 |
| ASUSTek       | PRIME B550M-A               | [0bc3c759d6](https://linux-hardware.org/?probe=0bc3c759d6) | Nov 13, 2022 |
| ASUSTek       | P8P67 EVO                   | [c033c311f3](https://linux-hardware.org/?probe=c033c311f3) | Nov 12, 2022 |
| ASUSTek       | PRIME X470-PRO              | [2d2cdbb40b](https://linux-hardware.org/?probe=2d2cdbb40b) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d134c6d6bf](https://linux-hardware.org/?probe=d134c6d6bf) | Nov 12, 2022 |
| ASUSTek       | A68HM-K                     | [842f768168](https://linux-hardware.org/?probe=842f768168) | Nov 12, 2022 |
| ASRock        | X570 Taichi                 | [8bbd88e580](https://linux-hardware.org/?probe=8bbd88e580) | Nov 11, 2022 |
| MSI           | D2415 S26361-D2415-A10      | [924e18bdcc](https://linux-hardware.org/?probe=924e18bdcc) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [f20eddfba9](https://linux-hardware.org/?probe=f20eddfba9) | Nov 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [34e25768ae](https://linux-hardware.org/?probe=34e25768ae) | Nov 10, 2022 |
| ASUSTek       | Rampage IV EXTREME          | [39b6ceb06c](https://linux-hardware.org/?probe=39b6ceb06c) | Nov 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9c6a00b034](https://linux-hardware.org/?probe=9c6a00b034) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [3e90cd2d25](https://linux-hardware.org/?probe=3e90cd2d25) | Nov 09, 2022 |
| OKI Brasil    | ST 4280 Padrao              | [f2841b0f4d](https://linux-hardware.org/?probe=f2841b0f4d) | Nov 08, 2022 |
| OKI Brasil    | ST 4280 Padrao              | [58cb07d7e1](https://linux-hardware.org/?probe=58cb07d7e1) | Nov 08, 2022 |
| ASRock        | X370 Gaming K4              | [f0634d863e](https://linux-hardware.org/?probe=f0634d863e) | Nov 08, 2022 |
| HP            | 8906 SMVB                   | [2670a536f0](https://linux-hardware.org/?probe=2670a536f0) | Nov 08, 2022 |
| Gigabyte      | B360M D3H-CF                | [ee895bde1f](https://linux-hardware.org/?probe=ee895bde1f) | Nov 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0e2747c7ab](https://linux-hardware.org/?probe=0e2747c7ab) | Nov 08, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [b49062def4](https://linux-hardware.org/?probe=b49062def4) | Nov 07, 2022 |
| ASRock        | X570 Taichi                 | [79475d514b](https://linux-hardware.org/?probe=79475d514b) | Nov 07, 2022 |
| ASRock        | X570 Taichi                 | [442c68f23d](https://linux-hardware.org/?probe=442c68f23d) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b414369067](https://linux-hardware.org/?probe=b414369067) | Nov 07, 2022 |
| ASUSTek       | P5Q DELUXE                  | [82bf0e80f0](https://linux-hardware.org/?probe=82bf0e80f0) | Nov 06, 2022 |
| ASUSTek       | P5Q DELUXE                  | [28af0c9803](https://linux-hardware.org/?probe=28af0c9803) | Nov 06, 2022 |
| Dell          | 0GDG8Y A02                  | [e61ccb96d0](https://linux-hardware.org/?probe=e61ccb96d0) | Nov 06, 2022 |
| PCWare        | IPMH110G                    | [3409bf9968](https://linux-hardware.org/?probe=3409bf9968) | Nov 06, 2022 |
| ASRock        | B550M-ITX/ac                | [e351ee8496](https://linux-hardware.org/?probe=e351ee8496) | Nov 06, 2022 |
| MSI           | 880GMS-E41                  | [2f53fa13ed](https://linux-hardware.org/?probe=2f53fa13ed) | Nov 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [690e470acf](https://linux-hardware.org/?probe=690e470acf) | Nov 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [5db0a08b25](https://linux-hardware.org/?probe=5db0a08b25) | Nov 06, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c7a85b52dc](https://linux-hardware.org/?probe=c7a85b52dc) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [958f0c8551](https://linux-hardware.org/?probe=958f0c8551) | Nov 05, 2022 |
| ASRock        | X670E Taichi                | [c5227abc14](https://linux-hardware.org/?probe=c5227abc14) | Nov 05, 2022 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | [f59d3d75ed](https://linux-hardware.org/?probe=f59d3d75ed) | Nov 05, 2022 |
| Gigabyte      | H61M-S2PV                   | [1c2a17391f](https://linux-hardware.org/?probe=1c2a17391f) | Nov 05, 2022 |
| HP            | 83E9                        | [837b4320c1](https://linux-hardware.org/?probe=837b4320c1) | Nov 05, 2022 |
| Gigabyte      | B560M D3H                   | [e8364f4018](https://linux-hardware.org/?probe=e8364f4018) | Nov 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [27bc8e172c](https://linux-hardware.org/?probe=27bc8e172c) | Nov 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [97d8c001ef](https://linux-hardware.org/?probe=97d8c001ef) | Nov 03, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [2c9714bc6b](https://linux-hardware.org/?probe=2c9714bc6b) | Nov 02, 2022 |
| ASUSTek       | H81T                        | [7598a634e6](https://linux-hardware.org/?probe=7598a634e6) | Nov 02, 2022 |
| ASUSTek       | PRIME B550M-A               | [454939df34](https://linux-hardware.org/?probe=454939df34) | Nov 02, 2022 |
| ASUSTek       | PRIME B550M-A               | [321eae8d23](https://linux-hardware.org/?probe=321eae8d23) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | [689b5a4022](https://linux-hardware.org/?probe=689b5a4022) | Nov 01, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [a5d58af861](https://linux-hardware.org/?probe=a5d58af861) | Oct 31, 2022 |
| ASRock        | X670E Pro RS                | [5ebdf73c67](https://linux-hardware.org/?probe=5ebdf73c67) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690-A                | [b1027d78bc](https://linux-hardware.org/?probe=b1027d78bc) | Oct 31, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [472a3f2707](https://linux-hardware.org/?probe=472a3f2707) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [71de876615](https://linux-hardware.org/?probe=71de876615) | Oct 30, 2022 |
| MSI           | B550-A PRO                  | [0d67856d8a](https://linux-hardware.org/?probe=0d67856d8a) | Oct 30, 2022 |
| MSI           | B550-A PRO                  | [9845791d39](https://linux-hardware.org/?probe=9845791d39) | Oct 30, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [c128f85cdc](https://linux-hardware.org/?probe=c128f85cdc) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [93d25dfb1f](https://linux-hardware.org/?probe=93d25dfb1f) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [8384c9e137](https://linux-hardware.org/?probe=8384c9e137) | Oct 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [1f7df5159e](https://linux-hardware.org/?probe=1f7df5159e) | Oct 30, 2022 |
| ASUSTek       | P6TD DELUXE                 | [faa61ea635](https://linux-hardware.org/?probe=faa61ea635) | Oct 30, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [957fc9af86](https://linux-hardware.org/?probe=957fc9af86) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | [4234f1fe02](https://linux-hardware.org/?probe=4234f1fe02) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | [6ab822b64c](https://linux-hardware.org/?probe=6ab822b64c) | Oct 29, 2022 |
| Gigabyte      | EX58-UD3R                   | [0d76cc7e31](https://linux-hardware.org/?probe=0d76cc7e31) | Oct 29, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [060c8aadd1](https://linux-hardware.org/?probe=060c8aadd1) | Oct 28, 2022 |
| ASUSTek       | PRIME B550M-A               | [6650af69ad](https://linux-hardware.org/?probe=6650af69ad) | Oct 27, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [82fcc1ecc7](https://linux-hardware.org/?probe=82fcc1ecc7) | Oct 26, 2022 |
| Intel         | H55                         | [f634aefb9a](https://linux-hardware.org/?probe=f634aefb9a) | Oct 26, 2022 |
| MSI           | ZH77A-G43                   | [ff43c876e9](https://linux-hardware.org/?probe=ff43c876e9) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8a718e0ade](https://linux-hardware.org/?probe=8a718e0ade) | Oct 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [040714e135](https://linux-hardware.org/?probe=040714e135) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [a55a6ef774](https://linux-hardware.org/?probe=a55a6ef774) | Oct 25, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [52a4b91a1e](https://linux-hardware.org/?probe=52a4b91a1e) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e98085fc5](https://linux-hardware.org/?probe=6e98085fc5) | Oct 25, 2022 |
| MSI           | Z170A GAMING M7             | [3326f67ecf](https://linux-hardware.org/?probe=3326f67ecf) | Oct 25, 2022 |
| ASRock        | H110M-ITX                   | [6818d9b7e2](https://linux-hardware.org/?probe=6818d9b7e2) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b4f3e516e3](https://linux-hardware.org/?probe=b4f3e516e3) | Oct 24, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [581fb21345](https://linux-hardware.org/?probe=581fb21345) | Oct 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [c76c6f0a0e](https://linux-hardware.org/?probe=c76c6f0a0e) | Oct 24, 2022 |
| ASUSTek       | PRIME B550M-A               | [baf284f131](https://linux-hardware.org/?probe=baf284f131) | Oct 24, 2022 |
| ASUSTek       | PRIME B360M-A               | [19ccd70ee8](https://linux-hardware.org/?probe=19ccd70ee8) | Oct 24, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [01c09a61ae](https://linux-hardware.org/?probe=01c09a61ae) | Oct 24, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [a8ab16a5c5](https://linux-hardware.org/?probe=a8ab16a5c5) | Oct 24, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [37a0403fc9](https://linux-hardware.org/?probe=37a0403fc9) | Oct 24, 2022 |
| ASUSTek       | PRIME B550M-A               | [c9b4dc7a70](https://linux-hardware.org/?probe=c9b4dc7a70) | Oct 24, 2022 |
| ASUSTek       | PRIME B550M-A               | [b237965d1c](https://linux-hardware.org/?probe=b237965d1c) | Oct 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [25db15ea87](https://linux-hardware.org/?probe=25db15ea87) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [ce7a9a3171](https://linux-hardware.org/?probe=ce7a9a3171) | Oct 23, 2022 |
| Gigabyte      | B550 AORUS PRO              | [76c1dffd95](https://linux-hardware.org/?probe=76c1dffd95) | Oct 23, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [e2d21dcb54](https://linux-hardware.org/?probe=e2d21dcb54) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [edf45abefe](https://linux-hardware.org/?probe=edf45abefe) | Oct 21, 2022 |
| Acer          | Predator PO3-630            | [aae61f30c7](https://linux-hardware.org/?probe=aae61f30c7) | Oct 20, 2022 |
| ASUSTek       | PRIME B550M-A               | [68b839f16e](https://linux-hardware.org/?probe=68b839f16e) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [6be0c6ee5f](https://linux-hardware.org/?probe=6be0c6ee5f) | Oct 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [8b459ac79b](https://linux-hardware.org/?probe=8b459ac79b) | Oct 20, 2022 |
| HP            | 8056                        | [37ed8a6b64](https://linux-hardware.org/?probe=37ed8a6b64) | Oct 18, 2022 |
| Gigabyte      | X99-UD7 WIFI-CF             | [9c484b6d22](https://linux-hardware.org/?probe=9c484b6d22) | Oct 18, 2022 |
| ASRock        | X300M-STX                   | [549fe857a6](https://linux-hardware.org/?probe=549fe857a6) | Oct 18, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7891f1e18c](https://linux-hardware.org/?probe=7891f1e18c) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [36c0e4dd87](https://linux-hardware.org/?probe=36c0e4dd87) | Oct 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [8d774a5771](https://linux-hardware.org/?probe=8d774a5771) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d727afe327](https://linux-hardware.org/?probe=d727afe327) | Oct 17, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [9d4d455bb2](https://linux-hardware.org/?probe=9d4d455bb2) | Oct 17, 2022 |
| Dell          | 0HHV7N A00                  | [fec2e273f7](https://linux-hardware.org/?probe=fec2e273f7) | Oct 17, 2022 |
| Gigabyte      | B460M DS3H V2               | [4fe1c6d3e8](https://linux-hardware.org/?probe=4fe1c6d3e8) | Oct 17, 2022 |
| PCWare        | IPMH110G                    | [cde154a026](https://linux-hardware.org/?probe=cde154a026) | Oct 16, 2022 |
| Intel         | D955XBK AAC96732-501        | [57a5e6cd9a](https://linux-hardware.org/?probe=57a5e6cd9a) | Oct 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [24c63dcc9e](https://linux-hardware.org/?probe=24c63dcc9e) | Oct 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [e71107e8cd](https://linux-hardware.org/?probe=e71107e8cd) | Oct 16, 2022 |
| ASUSTek       | PRIME B550M-A               | [4aa372d298](https://linux-hardware.org/?probe=4aa372d298) | Oct 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [2495f40df9](https://linux-hardware.org/?probe=2495f40df9) | Oct 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ba8acdb280](https://linux-hardware.org/?probe=ba8acdb280) | Oct 15, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | [89060aa147](https://linux-hardware.org/?probe=89060aa147) | Oct 13, 2022 |
| ASUSTek       | P6T SE                      | [4ba4bc909d](https://linux-hardware.org/?probe=4ba4bc909d) | Oct 12, 2022 |
| Intel         | DH87RL AAG74240-400         | [82d2063927](https://linux-hardware.org/?probe=82d2063927) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [ec470df515](https://linux-hardware.org/?probe=ec470df515) | Oct 11, 2022 |
| Dell          | 0WR7PY A02                  | [e464adc2d9](https://linux-hardware.org/?probe=e464adc2d9) | Oct 11, 2022 |
| PCWare        | IPMH110G                    | [2bcf719742](https://linux-hardware.org/?probe=2bcf719742) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2f346a2afb](https://linux-hardware.org/?probe=2f346a2afb) | Oct 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Arch Rolling     | 1626     | 60.67%  |
| Arch             | 1042     | 38.88%  |
| Arch V20.4.11    | 2        | 0.07%   |
| Arch V19.11.3    | 2        | 0.07%   |
| Arch Workstation | 1        | 0.04%   |
| Arch V20.3.4     | 1        | 0.04%   |
| Arch V19.09.1    | 1        | 0.04%   |
| Arch V19.07.11   | 1        | 0.04%   |
| Arch V19.05.2    | 1        | 0.04%   |
| Arch Breaking    | 1        | 0.04%   |
| Arch 2020.09.05  | 1        | 0.04%   |
| Arch 20.08.3     | 1        | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Arch | 2616     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Desktops | Percent |
|-----------------|----------|---------|
| 5.8.5-arch1-1   | 36       | 1.15%   |
| 5.9.14-arch1-1  | 28       | 0.9%    |
| 5.9.1-arch1-1   | 28       | 0.9%    |
| 5.17.1-arch1-1  | 28       | 0.9%    |
| 5.8.12-arch1-1  | 27       | 0.87%   |
| 5.17.9-arch1-1  | 25       | 0.8%    |
| 6.4.12-arch1-1  | 22       | 0.71%   |
| 5.8.14-arch1-1  | 21       | 0.67%   |
| 5.17.5-arch1-1  | 21       | 0.67%   |
| 6.3.9-arch1-1   | 20       | 0.64%   |
| 5.8.10-arch1-1  | 20       | 0.64%   |
| 5.13.13-arch1-1 | 20       | 0.64%   |
| 5.11.6-arch1-1  | 20       | 0.64%   |
| 6.1.12-arch1-1  | 19       | 0.61%   |
| 5.7.12-arch1-1  | 19       | 0.61%   |
| 6.1.1-arch1-1   | 17       | 0.55%   |
| 6.0.2-arch1-1   | 17       | 0.55%   |
| 6.2.8-arch1-1   | 16       | 0.51%   |
| 5.8.1-arch1-1   | 16       | 0.51%   |
| 5.11.16-arch1-1 | 16       | 0.51%   |
| 5.8.7-arch1-1   | 15       | 0.48%   |
| 5.15.7-arch1-1  | 15       | 0.48%   |
| 5.10.16-arch1-1 | 15       | 0.48%   |
| 6.2.12-arch1-1  | 14       | 0.45%   |
| 5.6.15-arch1-1  | 14       | 0.45%   |
| 5.12.15-arch1-1 | 14       | 0.45%   |
| 6.1.8-arch1-1   | 13       | 0.42%   |
| 6.0.9-arch1-1   | 13       | 0.42%   |
| 6.0.8-arch1-1   | 13       | 0.42%   |
| 6.0.12-arch1-1  | 13       | 0.42%   |
| 5.14.6-arch1-1  | 13       | 0.42%   |
| 5.14.14-arch1-1 | 13       | 0.42%   |
| 5.12.14-arch1-1 | 13       | 0.42%   |
| 5.11.15-arch1-2 | 13       | 0.42%   |
| 6.4.8-arch1-1   | 12       | 0.38%   |
| 6.4.10-arch1-1  | 12       | 0.38%   |
| 6.3.2-arch1-1   | 12       | 0.38%   |
| 6.3.1-arch1-1   | 12       | 0.38%   |
| 6.2.1-arch1-1   | 12       | 0.38%   |
| 6.1.9-arch1-1   | 12       | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.5   | 48       | 1.54%   |
| 5.8.12  | 45       | 1.44%   |
| 5.9.1   | 36       | 1.16%   |
| 5.17.1  | 35       | 1.12%   |
| 5.11.6  | 34       | 1.09%   |
| 5.9.14  | 32       | 1.03%   |
| 5.8.10  | 31       | 0.99%   |
| 5.8.14  | 29       | 0.93%   |
| 5.17.9  | 28       | 0.9%    |
| 6.3.9   | 27       | 0.87%   |
| 5.17.5  | 27       | 0.87%   |
| 6.4.3   | 26       | 0.83%   |
| 6.1.12  | 25       | 0.8%    |
| 6.0.2   | 25       | 0.8%    |
| 6.4.12  | 24       | 0.77%   |
| 6.2.2   | 24       | 0.77%   |
| 5.8.1   | 23       | 0.74%   |
| 6.1.1   | 22       | 0.71%   |
| 5.8.11  | 22       | 0.71%   |
| 5.7.12  | 22       | 0.71%   |
| 5.13.13 | 22       | 0.71%   |
| 6.3.1   | 20       | 0.64%   |
| 5.11.16 | 20       | 0.64%   |
| 6.2.8   | 19       | 0.61%   |
| 6.1.8   | 19       | 0.61%   |
| 5.15.7  | 19       | 0.61%   |
| 5.12.9  | 19       | 0.61%   |
| 5.12.14 | 19       | 0.61%   |
| 6.4.10  | 18       | 0.58%   |
| 6.1.9   | 18       | 0.58%   |
| 5.19.7  | 18       | 0.58%   |
| 5.14.6  | 18       | 0.58%   |
| 5.12.15 | 18       | 0.58%   |
| 6.3.2   | 17       | 0.55%   |
| 6.2.12  | 17       | 0.55%   |
| 6.0.8   | 17       | 0.55%   |
| 6.0.12  | 17       | 0.55%   |
| 5.8.7   | 17       | 0.55%   |
| 5.19.9  | 17       | 0.55%   |
| 5.11.11 | 17       | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8     | 270      | 8.99%   |
| 5.15    | 182      | 6.06%   |
| 6.1     | 181      | 6.03%   |
| 5.11    | 158      | 5.26%   |
| 6.4     | 153      | 5.09%   |
| 5.9     | 152      | 5.06%   |
| 5.10    | 150      | 5%      |
| 5.12    | 144      | 4.8%    |
| 6.0     | 141      | 4.7%    |
| 5.4     | 138      | 4.6%    |
| 5.19    | 133      | 4.43%   |
| 6.2     | 131      | 4.36%   |
| 5.17    | 127      | 4.23%   |
| 6.3     | 121      | 4.03%   |
| 5.18    | 121      | 4.03%   |
| 5.7     | 106      | 3.53%   |
| 5.6     | 106      | 3.53%   |
| 5.14    | 94       | 3.13%   |
| 5.16    | 93       | 3.1%    |
| 5.13    | 78       | 2.6%    |
| 5.5     | 46       | 1.53%   |
| 5.3     | 42       | 1.4%    |
| 4.19    | 26       | 0.87%   |
| 5.0     | 19       | 0.63%   |
| 4.18    | 18       | 0.6%    |
| 5.2     | 15       | 0.5%    |
| 5.1     | 13       | 0.43%   |
| 4.20    | 12       | 0.4%    |
| 4.17    | 7        | 0.23%   |
| 4.15    | 7        | 0.23%   |
| 6.5     | 4        | 0.13%   |
| 4.16    | 4        | 0.13%   |
| 4.11    | 2        | 0.07%   |
| 4.10    | 2        | 0.07%   |
| 6.3.0   | 1        | 0.03%   |
| 4.9     | 1        | 0.03%   |
| 4.8     | 1        | 0.03%   |
| 4.6     | 1        | 0.03%   |
| 4.14    | 1        | 0.03%   |
| 4.13    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2615     | 99.96%  |
| i686   | 1        | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 782      | 28.71%  |
| KDE5                     | 754      | 27.68%  |
| Unknown                  | 337      | 12.37%  |
| XFCE                     | 221      | 8.11%   |
| KDE                      | 132      | 4.85%   |
| i3                       | 126      | 4.63%   |
| X-Cinnamon               | 44       | 1.62%   |
| MATE                     | 40       | 1.47%   |
| Budgie                   | 39       | 1.43%   |
| Deepin                   | 36       | 1.32%   |
| Cinnamon                 | 34       | 1.25%   |
| sway                     | 25       | 0.92%   |
| Hyprland                 | 22       | 0.81%   |
| LXDE                     | 20       | 0.73%   |
| LXQt                     | 17       | 0.62%   |
| bspwm                    | 16       | 0.59%   |
| Openbox                  | 14       | 0.51%   |
| qtile                    | 10       | 0.37%   |
| awesome                  | 9        | 0.33%   |
| dwm                      | 6        | 0.22%   |
| xmonad                   | 5        | 0.18%   |
| GNOME Flashback          | 5        | 0.18%   |
| leftwm                   | 4        | 0.15%   |
| GNOME Classic            | 4        | 0.15%   |
| Unity                    | 3        | 0.11%   |
| i3-with-shmlog           | 3        | 0.11%   |
| chadwm                   | 3        | 0.11%   |
| GNUstep                  | 2        | 0.07%   |
| Yaru:ubuntu:GNOME        | 1        | 0.04%   |
| xinitrc                  | 1        | 0.04%   |
| Wayfire                  | 1        | 0.04%   |
| sway:Unity               | 1        | 0.04%   |
| river                    | 1        | 0.04%   |
| jwm                      | 1        | 0.04%   |
| ICEWM                    | 1        | 0.04%   |
| GNOME-Classic            | 1        | 0.04%   |
| dusk                     | 1        | 0.04%   |
| default                  | 1        | 0.04%   |
| /usr/bin/openbox-session | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1750     | 64.41%  |
| Wayland | 506      | 18.62%  |
| Tty     | 280      | 10.31%  |
| Unknown | 180      | 6.62%   |
| Web     | 1        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1147     | 42.48%  |
| SDDM    | 648      | 24%     |
| GDM     | 321      | 11.89%  |
| LightDM | 280      | 10.37%  |
| TDM     | 195      | 7.22%   |
| Ly      | 32       | 1.19%   |
| LXDM    | 26       | 0.96%   |
| XDM     | 24       | 0.89%   |
| SLiM    | 11       | 0.41%   |
| GREETD  | 8        | 0.3%    |
| LY-DM   | 3        | 0.11%   |
| NODM    | 2        | 0.07%   |
| XINIT   | 1        | 0.04%   |
| KDM     | 1        | 0.04%   |
| EMPTTY  | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 1307     | 48.82%  |
| Unknown     | 239      | 8.93%   |
| en_GB       | 161      | 6.01%   |
| C           | 136      | 5.08%   |
| de_DE       | 126      | 4.71%   |
| ru_RU       | 105      | 3.92%   |
| pt_BR       | 77       | 2.88%   |
| it_IT       | 67       | 2.5%    |
| fr_FR       | 54       | 2.02%   |
| pl_PL       | 40       | 1.49%   |
| es_ES       | 33       | 1.23%   |
| en_CA       | 29       | 1.08%   |
| en_AU       | 28       | 1.05%   |
| en_IE       | 22       | 0.82%   |
| en_IN       | 19       | 0.71%   |
| zh_CN       | 18       | 0.67%   |
| en_DK       | 14       | 0.52%   |
| hu_HU       | 12       | 0.45%   |
| sv_SE       | 8        | 0.3%    |
| en_NZ       | 8        | 0.3%    |
| en_DE       | 8        | 0.3%    |
| de_AT       | 8        | 0.3%    |
| pt_PT       | 7        | 0.26%   |
| nl_NL       | 7        | 0.26%   |
| ja_JP       | 7        | 0.26%   |
| fi_FI       | 7        | 0.26%   |
| tr_TR       | 6        | 0.22%   |
| ru_UA       | 6        | 0.22%   |
| es_MX       | 6        | 0.22%   |
| es_CL       | 6        | 0.22%   |
| en_US.UTF8  | 6        | 0.22%   |
| es_CO       | 5        | 0.19%   |
| es_AR       | 5        | 0.19%   |
| de_CH       | 5        | 0.19%   |
| uk_UA       | 4        | 0.15%   |
| cs_CZ       | 4        | 0.15%   |
| es_GT       | 3        | 0.11%   |
| en_ZA       | 3        | 0.11%   |
| en_US.utf-8 | 3        | 0.11%   |
| en_SG       | 3        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 1593     | 59.69%  |
| BIOS | 1076     | 40.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1863     | 70.09%  |
| Btrfs    | 588      | 22.12%  |
| Xfs      | 72       | 2.71%   |
| Unknown  | 62       | 2.33%   |
| F2fs     | 35       | 1.32%   |
| Zfs      | 15       | 0.56%   |
| Overlay  | 15       | 0.56%   |
| XXXXX    | 2        | 0.08%   |
| Ext2     | 2        | 0.08%   |
| Tmpfs    | 1        | 0.04%   |
| Reiserfs | 1        | 0.04%   |
| Jfs      | 1        | 0.04%   |
| Ext3     | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1671     | 62.77%  |
| Unknown | 760      | 28.55%  |
| MBR     | 231      | 8.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2127     | 79.69%  |
| Yes       | 542      | 20.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1680     | 62.87%  |
| Yes       | 992      | 37.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 847      | 32.38%  |
| Gigabyte Technology                  | 537      | 20.53%  |
| MSI                                  | 444      | 16.97%  |
| ASRock                               | 337      | 12.88%  |
| Hewlett-Packard                      | 95       | 3.63%   |
| Dell                                 | 88       | 3.36%   |
| Lenovo                               | 46       | 1.76%   |
| Intel                                | 45       | 1.72%   |
| Acer                                 | 24       | 0.92%   |
| Unknown                              | 20       | 0.76%   |
| Biostar                              | 16       | 0.61%   |
| ECS                                  | 12       | 0.46%   |
| Pegatron                             | 11       | 0.42%   |
| Huanan                               | 8        | 0.31%   |
| Fujitsu                              | 6        | 0.23%   |
| Foxconn                              | 5        | 0.19%   |
| Apple                                | 5        | 0.19%   |
| Positivo                             | 4        | 0.15%   |
| Medion                               | 4        | 0.15%   |
| AZW                                  | 4        | 0.15%   |
| Shuttle                              | 3        | 0.11%   |
| PCWare                               | 3        | 0.11%   |
| Gateway                              | 3        | 0.11%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.08%   |
| Semp Toshiba                         | 2        | 0.08%   |
| ONDA                                 | 2        | 0.08%   |
| OEM                                  | 2        | 0.08%   |
| MACHINIST                            | 2        | 0.08%   |
| EVGA                                 | 2        | 0.08%   |
| BESSTAR Tech                         | 2        | 0.08%   |
| ASRockRack                           | 2        | 0.08%   |
| XFX                                  | 1        | 0.04%   |
| TYAN Computer                        | 1        | 0.04%   |
| T-bao                                | 1        | 0.04%   |
| Supermicro                           | 1        | 0.04%   |
| Samsung Electronics                  | 1        | 0.04%   |
| QIYIDA                               | 1        | 0.04%   |
| Protectli                            | 1        | 0.04%   |
| PC Engines                           | 1        | 0.04%   |
| Packard Bell                         | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 65       | 2.48%   |
| MSI MS-7C37                      | 31       | 1.19%   |
| MSI MS-7C02                      | 31       | 1.19%   |
| ASUS TUF Gaming X570-PLUS        | 31       | 1.19%   |
| MSI MS-7B86                      | 23       | 0.88%   |
| Gigabyte B450M DS3H              | 22       | 0.84%   |
| Unknown                          | 22       | 0.84%   |
| ASUS ROG STRIX B550-F GAMING     | 19       | 0.73%   |
| ASUS PRIME X470-PRO              | 18       | 0.69%   |
| MSI MS-7B89                      | 17       | 0.65%   |
| MSI MS-7A34                      | 17       | 0.65%   |
| Gigabyte X570 AORUS ELITE        | 17       | 0.65%   |
| ASUS ROG STRIX B450-F GAMING     | 17       | 0.65%   |
| MSI MS-7C91                      | 16       | 0.61%   |
| MSI MS-7B79                      | 16       | 0.61%   |
| ASUS PRIME X370-PRO              | 16       | 0.61%   |
| ASUS PRIME B450M-A               | 16       | 0.61%   |
| MSI MS-7A38                      | 15       | 0.57%   |
| MSI MS-7C56                      | 14       | 0.54%   |
| Gigabyte X470 AORUS ULTRA GAMING | 14       | 0.54%   |
| ASUS TUF Gaming B550-PLUS        | 13       | 0.5%    |
| ASUS ROG STRIX X570-E GAMING     | 13       | 0.5%    |
| ASRock X570 Taichi               | 12       | 0.46%   |
| ASRock B450M Pro4                | 12       | 0.46%   |
| Gigabyte B450 AORUS ELITE        | 11       | 0.42%   |
| Gigabyte 970A-DS3P               | 11       | 0.42%   |
| ASUS ROG STRIX X470-F GAMING     | 11       | 0.42%   |
| ASUS PRIME A320M-K               | 11       | 0.42%   |
| MSI MS-7B98                      | 10       | 0.38%   |
| Gigabyte X570 I AORUS PRO WIFI   | 10       | 0.38%   |
| ASUS ROG STRIX B550-I GAMING     | 10       | 0.38%   |
| Gigabyte X570 AORUS MASTER       | 9        | 0.34%   |
| Gigabyte B450 AORUS M            | 9        | 0.34%   |
| ASUS ROG CROSSHAIR VII HERO      | 9        | 0.34%   |
| ASUS PRIME X570-P                | 9        | 0.34%   |
| ASRock X570M Pro4                | 9        | 0.34%   |
| MSI MS-7C95                      | 8        | 0.31%   |
| MSI MS-7C35                      | 8        | 0.31%   |
| MSI MS-7693                      | 8        | 0.31%   |
| Gigabyte B550I AORUS PRO AX      | 8        | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 218      | 8.33%   |
| ASUS ROG              | 184      | 7.03%   |
| ASUS TUF              | 120      | 4.59%   |
| ASUS All              | 65       | 2.48%   |
| Gigabyte X570         | 59       | 2.26%   |
| Dell OptiPlex         | 59       | 2.26%   |
| Gigabyte B450M        | 37       | 1.41%   |
| MSI MS-7C37           | 31       | 1.19%   |
| MSI MS-7C02           | 31       | 1.19%   |
| ASRock X570           | 31       | 1.19%   |
| Gigabyte B450         | 30       | 1.15%   |
| MSI MS-7B86           | 23       | 0.88%   |
| Lenovo ThinkCentre    | 23       | 0.88%   |
| ASRock B450M          | 23       | 0.88%   |
| Unknown               | 22       | 0.84%   |
| ASRock B450           | 21       | 0.8%    |
| HP Compaq             | 19       | 0.73%   |
| Gigabyte X470         | 19       | 0.73%   |
| Gigabyte B550         | 19       | 0.73%   |
| MSI MS-7B89           | 17       | 0.65%   |
| MSI MS-7A34           | 17       | 0.65%   |
| Gigabyte Z390         | 17       | 0.65%   |
| ASUS P8Z77-V          | 17       | 0.65%   |
| MSI MS-7C91           | 16       | 0.61%   |
| MSI MS-7B79           | 16       | 0.61%   |
| Gigabyte AX370-Gaming | 16       | 0.61%   |
| ASRock X470           | 16       | 0.61%   |
| MSI MS-7A38           | 15       | 0.57%   |
| ASRock X370           | 15       | 0.57%   |
| Acer Aspire           | 15       | 0.57%   |
| MSI MS-7C56           | 14       | 0.54%   |
| ASUS STRIX            | 13       | 0.5%    |
| ASUS Maximus          | 13       | 0.5%    |
| Gigabyte B550M        | 12       | 0.46%   |
| ASRock AB350          | 12       | 0.46%   |
| HP Pavilion           | 11       | 0.42%   |
| HP EliteDesk          | 11       | 0.42%   |
| Gigabyte 970A-DS3P    | 11       | 0.42%   |
| MSI MS-7B98           | 10       | 0.38%   |
| Dell Precision        | 10       | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 485      | 18.54%  |
| 2019    | 383      | 14.64%  |
| 2020    | 317      | 12.12%  |
| 2017    | 240      | 9.17%   |
| 2012    | 160      | 6.12%   |
| 2014    | 146      | 5.58%   |
| 2013    | 146      | 5.58%   |
| 2016    | 143      | 5.47%   |
| 2021    | 117      | 4.47%   |
| 2015    | 108      | 4.13%   |
| 2011    | 108      | 4.13%   |
| 2022    | 79       | 3.02%   |
| 2010    | 63       | 2.41%   |
| 2009    | 43       | 1.64%   |
| 2008    | 32       | 1.22%   |
| 2007    | 21       | 0.8%    |
| 2023    | 14       | 0.54%   |
| 2006    | 6        | 0.23%   |
| 2005    | 2        | 0.08%   |
| Unknown | 2        | 0.08%   |
| 2002    | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2616     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2600     | 99.2%   |
| Enabled  | 21       | 0.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2614     | 99.92%  |
| Yes  | 2        | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 951      | 35.67%  |
| 32.01-64.0      | 699      | 26.22%  |
| 8.01-16.0       | 375      | 14.07%  |
| 4.01-8.0        | 196      | 7.35%   |
| 64.01-256.0     | 191      | 7.16%   |
| 3.01-4.0        | 115      | 4.31%   |
| 24.01-32.0      | 102      | 3.83%   |
| 1.01-2.0        | 16       | 0.6%    |
| 2.01-3.0        | 9        | 0.34%   |
| More than 256.0 | 5        | 0.19%   |
| 0.51-1.0        | 5        | 0.19%   |
| Unknown         | 2        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 793      | 27.48%  |
| 2.01-3.0    | 595      | 20.62%  |
| 1.01-2.0    | 493      | 17.08%  |
| 3.01-4.0    | 440      | 15.25%  |
| 8.01-16.0   | 349      | 12.09%  |
| 0.51-1.0    | 82       | 2.84%   |
| 16.01-24.0  | 71       | 2.46%   |
| 0.01-0.5    | 24       | 0.83%   |
| 24.01-32.0  | 20       | 0.69%   |
| 32.01-64.0  | 16       | 0.55%   |
| Unknown     | 2        | 0.07%   |
| 64.01-256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 797      | 29.05%  |
| 3      | 617      | 22.49%  |
| 1      | 575      | 20.95%  |
| 4      | 350      | 12.76%  |
| 5      | 203      | 7.4%    |
| 6      | 90       | 3.28%   |
| 7      | 53       | 1.93%   |
| 8      | 19       | 0.69%   |
| 9      | 17       | 0.62%   |
| 0      | 5        | 0.18%   |
| 12     | 4        | 0.15%   |
| 11     | 4        | 0.15%   |
| 10     | 4        | 0.15%   |
| 13     | 2        | 0.07%   |
| 22     | 1        | 0.04%   |
| 17     | 1        | 0.04%   |
| 15     | 1        | 0.04%   |
| 14     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1974     | 74.74%  |
| Yes       | 667      | 25.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2594     | 99.12%  |
| No        | 23       | 0.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1431     | 53.94%  |
| Yes       | 1222     | 46.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1475     | 55.45%  |
| Yes       | 1185     | 44.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 547      | 20.78%  |
| Germany     | 275      | 10.45%  |
| Russia      | 197      | 7.48%   |
| Brazil      | 144      | 5.47%   |
| UK          | 115      | 4.37%   |
| Italy       | 106      | 4.03%   |
| France      | 102      | 3.88%   |
| Poland      | 91       | 3.46%   |
| Canada      | 77       | 2.93%   |
| Spain       | 64       | 2.43%   |
| Netherlands | 53       | 2.01%   |
| Sweden      | 52       | 1.98%   |
| Ukraine     | 48       | 1.82%   |
| Finland     | 46       | 1.75%   |
| Australia   | 46       | 1.75%   |
| Austria     | 43       | 1.63%   |
| India       | 38       | 1.44%   |
| China       | 34       | 1.29%   |
| Hungary     | 27       | 1.03%   |
| Turkey      | 26       | 0.99%   |
| Switzerland | 26       | 0.99%   |
| Greece      | 23       | 0.87%   |
| Norway      | 22       | 0.84%   |
| Denmark     | 20       | 0.76%   |
| Argentina   | 20       | 0.76%   |
| Czechia     | 19       | 0.72%   |
| Romania     | 18       | 0.68%   |
| Mexico      | 18       | 0.68%   |
| Japan       | 17       | 0.65%   |
| Chile       | 16       | 0.61%   |
| Belgium     | 13       | 0.49%   |
| Serbia      | 12       | 0.46%   |
| New Zealand | 12       | 0.46%   |
| Bulgaria    | 12       | 0.46%   |
| Ireland     | 11       | 0.42%   |
| Hong Kong   | 11       | 0.42%   |
| Vietnam     | 10       | 0.38%   |
| Portugal    | 10       | 0.38%   |
| Singapore   | 9        | 0.34%   |
| Lithuania   | 9        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 56       | 2.01%   |
| Paris             | 29       | 1.04%   |
| Vienna            | 25       | 0.9%    |
| St Petersburg     | 25       | 0.9%    |
| Warsaw            | 24       | 0.86%   |
| Helsinki          | 24       | 0.86%   |
| Berlin            | 24       | 0.86%   |
| Sao Paulo         | 19       | 0.68%   |
| Frankfurt am Main | 17       | 0.61%   |
| Melbourne         | 15       | 0.54%   |
| London            | 15       | 0.54%   |
| Munich            | 14       | 0.5%    |
| Athens            | 13       | 0.47%   |
| Hamburg           | 12       | 0.43%   |
| Amsterdam         | 12       | 0.43%   |
| Sydney            | 11       | 0.4%    |
| Seattle           | 11       | 0.4%    |
| New York          | 11       | 0.4%    |
| Krakow            | 11       | 0.4%    |
| Chicago           | 11       | 0.4%    |
| Barcelona         | 11       | 0.4%    |
| Los Angeles       | 10       | 0.36%   |
| Dublin            | 10       | 0.36%   |
| Zurich            | 9        | 0.32%   |
| Tallinn           | 9        | 0.32%   |
| Singapore         | 9        | 0.32%   |
| Rome              | 9        | 0.32%   |
| Milan             | 9        | 0.32%   |
| Kyiv              | 9        | 0.32%   |
| Istanbul          | 9        | 0.32%   |
| Dallas            | 9        | 0.32%   |
| Stockholm         | 8        | 0.29%   |
| Shanghai          | 8        | 0.29%   |
| Rostov-on-Don     | 8        | 0.29%   |
| Rio de Janeiro    | 8        | 0.29%   |
| Recife            | 8        | 0.29%   |
| Madrid            | 8        | 0.29%   |
| Budapest          | 8        | 0.29%   |
| Belgrade          | 8        | 0.29%   |
| Yekaterinburg     | 7        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 1104     | 2037   | 19.11%  |
| WDC                         | 1029     | 1748   | 17.82%  |
| Seagate                     | 894      | 1445   | 15.48%  |
| Kingston                    | 342      | 473    | 5.92%   |
| SanDisk                     | 335      | 503    | 5.8%    |
| Crucial                     | 333      | 476    | 5.77%   |
| Toshiba                     | 322      | 483    | 5.57%   |
| Intel                       | 112      | 141    | 1.94%   |
| Hitachi                     | 105      | 147    | 1.82%   |
| A-DATA Technology           | 97       | 134    | 1.68%   |
| Phison                      | 81       | 110    | 1.4%    |
| Micron/Crucial Technology   | 62       | 75     | 1.07%   |
| HGST                        | 60       | 97     | 1.04%   |
| Silicon Motion              | 50       | 62     | 0.87%   |
| China                       | 50       | 65     | 0.87%   |
| Phison Electronics          | 45       | 56     | 0.78%   |
| OCZ                         | 44       | 62     | 0.76%   |
| Corsair                     | 42       | 54     | 0.73%   |
| SK hynix                    | 38       | 50     | 0.66%   |
| SPCC                        | 35       | 38     | 0.61%   |
| Unknown                     | 34       | 44     | 0.59%   |
| PNY                         | 32       | 39     | 0.55%   |
| Patriot                     | 32       | 42     | 0.55%   |
| ADATA Technology            | 30       | 38     | 0.52%   |
| Kingston Technology Company | 22       | 26     | 0.38%   |
| XPG                         | 21       | 28     | 0.36%   |
| Realtek Semiconductor       | 20       | 26     | 0.35%   |
| Micron Technology           | 20       | 23     | 0.35%   |
| GOODRAM                     | 20       | 28     | 0.35%   |
| Transcend                   | 15       | 27     | 0.26%   |
| Team                        | 15       | 24     | 0.26%   |
| Plextor                     | 15       | 24     | 0.26%   |
| Hewlett-Packard             | 15       | 16     | 0.26%   |
| Gigabyte Technology         | 13       | 16     | 0.23%   |
| SABRENT                     | 11       | 12     | 0.19%   |
| Lexar                       | 11       | 11     | 0.19%   |
| Intenso                     | 11       | 11     | 0.19%   |
| Maxtor                      | 9        | 9      | 0.16%   |
| LITEON                      | 9        | 9      | 0.16%   |
| JMicron Technology          | 9        | 17     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB             | 104      | 1.48%   |
| Samsung SSD 850 EVO 500GB                                       | 89       | 1.27%   |
| Samsung SSD 860 EVO 500GB                                       | 84       | 1.2%    |
| Seagate ST2000DM008-2FR102 2TB                                  | 83       | 1.18%   |
| Samsung SSD 860 EVO 1TB                                         | 71       | 1.01%   |
| Samsung SSD 850 EVO 250GB                                       | 70       | 1%      |
| Kingston SA400S37240G 240GB SSD                                 | 69       | 0.98%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 66       | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB           | 65       | 0.93%   |
| Crucial CT1000MX500SSD1 1TB                                     | 56       | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB                                        | 55       | 0.78%   |
| Samsung SSD 970 EVO Plus 1TB                                    | 53       | 0.76%   |
| Crucial CT500MX500SSD1 500GB                                    | 52       | 0.74%   |
| Toshiba DT01ACA100 1TB                                          | 50       | 0.71%   |
| Seagate ST500DM002-1BD142 500GB                                 | 49       | 0.7%    |
| Seagate ST4000DM004-2CV104 4TB                                  | 46       | 0.66%   |
| Samsung NVMe SSD Drive 1TB                                      | 46       | 0.66%   |
| Samsung NVMe SSD Drive 500GB                                    | 45       | 0.64%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 44       | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB                                  | 42       | 0.6%    |
| Kingston SA400S37120G 120GB SSD                                 | 42       | 0.6%    |
| Samsung SSD 860 QVO 1TB                                         | 41       | 0.58%   |
| Toshiba HDWD110 1TB                                             | 40       | 0.57%   |
| Samsung SSD 860 EVO 250GB                                       | 38       | 0.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 36       | 0.51%   |
| Samsung SSD 840 EVO 250GB                                       | 36       | 0.51%   |
| Kingston SA400S37480G 480GB SSD                                 | 36       | 0.51%   |
| WDC WD10EZEX-00BN5A0 1TB                                        | 33       | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                                | 33       | 0.47%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 31       | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 31       | 0.44%   |
| Samsung SSD 970 EVO 500GB                                       | 31       | 0.44%   |
| Toshiba DT01ACA200 2TB                                          | 29       | 0.41%   |
| Crucial CT480BX500SSD1 480GB                                    | 29       | 0.41%   |
| Samsung SSD 850 EVO 1TB                                         | 27       | 0.38%   |
| SanDisk NVMe SSD Drive 1TB                                      | 26       | 0.37%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 2TB | 26       | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB                                  | 25       | 0.36%   |
| Samsung SSD 970 EVO 1TB                                         | 25       | 0.36%   |
| Samsung SSD 960 EVO 250GB                                       | 25       | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 906      | 1482   | 37.52%  |
| Seagate             | 874      | 1409   | 36.19%  |
| Toshiba             | 293      | 414    | 12.13%  |
| Samsung Electronics | 105      | 143    | 4.35%   |
| Hitachi             | 105      | 147    | 4.35%   |
| HGST                | 58       | 95     | 2.4%    |
| Unknown             | 15       | 20     | 0.62%   |
| SABRENT             | 11       | 12     | 0.46%   |
| Maxtor              | 9        | 9      | 0.37%   |
| Fujitsu             | 6        | 6      | 0.25%   |
| Apple               | 5        | 5      | 0.21%   |
| ASMT                | 3        | 3      | 0.12%   |
| USB3.0              | 2        | 3      | 0.08%   |
| LaCie               | 2        | 2      | 0.08%   |
| Hewlett-Packard     | 2        | 2      | 0.08%   |
| ASMedia             | 2        | 2      | 0.08%   |
| USB                 | 1        | 1      | 0.04%   |
| Synology            | 1        | 1      | 0.04%   |
| StoreJet            | 1        | 1      | 0.04%   |
| SSK                 | 1        | 1      | 0.04%   |
| RSH-319             | 1        | 1      | 0.04%   |
| QNAP                | 1        | 11     | 0.04%   |
| MaxDigital          | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 1      | 0.04%   |
| LIO-ORG             | 1        | 2      | 0.04%   |
| JMicron Technology  | 1        | 8      | 0.04%   |
| Intenso             | 1        | 1      | 0.04%   |
| HGST HTS            | 1        | 1      | 0.04%   |
| H/W                 | 1        | 1      | 0.04%   |
| External            | 1        | 2      | 0.04%   |
| Config              | 1        | 1      | 0.04%   |
| ASUSTOR             | 1        | 1      | 0.04%   |
| Unknown             | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 641      | 994    | 29.43%  |
| Crucial             | 309      | 445    | 14.19%  |
| Kingston            | 290      | 385    | 13.31%  |
| SanDisk             | 191      | 301    | 8.77%   |
| WDC                 | 152      | 199    | 6.98%   |
| A-DATA Technology   | 66       | 92     | 3.03%   |
| China               | 50       | 65     | 2.3%    |
| Intel               | 49       | 61     | 2.25%   |
| OCZ                 | 44       | 62     | 2.02%   |
| Patriot             | 32       | 42     | 1.47%   |
| SPCC                | 30       | 32     | 1.38%   |
| PNY                 | 28       | 35     | 1.29%   |
| Corsair             | 21       | 25     | 0.96%   |
| GOODRAM             | 19       | 27     | 0.87%   |
| Toshiba             | 18       | 49     | 0.83%   |
| Transcend           | 13       | 25     | 0.6%    |
| Plextor             | 12       | 13     | 0.55%   |
| Team                | 11       | 13     | 0.51%   |
| Micron Technology   | 11       | 13     | 0.51%   |
| Lexar               | 11       | 11     | 0.51%   |
| SK hynix            | 10       | 11     | 0.46%   |
| Intenso             | 10       | 10     | 0.46%   |
| LITEON              | 8        | 8      | 0.37%   |
| JMicron Technology  | 7        | 8      | 0.32%   |
| Mushkin             | 6        | 11     | 0.28%   |
| Hewlett-Packard     | 6        | 6      | 0.28%   |
| TO Exter            | 5        | 6      | 0.23%   |
| Seagate             | 5        | 5      | 0.23%   |
| LITEONIT            | 5        | 5      | 0.23%   |
| Gigabyte Technology | 5        | 6      | 0.23%   |
| AMD                 | 5        | 6      | 0.23%   |
| Unknown             | 5        | 6      | 0.23%   |
| XrayDisk            | 4        | 5      | 0.18%   |
| Netac               | 4        | 4      | 0.18%   |
| KingSpec            | 4        | 4      | 0.18%   |
| KingDian            | 4        | 4      | 0.18%   |
| USB30               | 3        | 14     | 0.14%   |
| LIO-ORG             | 3        | 7      | 0.14%   |
| Drevo               | 3        | 4      | 0.14%   |
| ASMT                | 3        | 3      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1818     | 3790   | 37.97%  |
| SSD     | 1686     | 3113   | 35.21%  |
| NVMe    | 1227     | 2051   | 25.63%  |
| Unknown | 50       | 61     | 1.04%   |
| MMC     | 7        | 7      | 0.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2318     | 6727   | 62.35%  |
| NVMe | 1227     | 2048   | 33%     |
| SAS  | 166      | 240    | 4.46%   |
| MMC  | 7        | 7      | 0.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1665     | 3090   | 41.86%  |
| 0.51-1.0   | 1184     | 1941   | 29.76%  |
| 1.01-2.0   | 587      | 913    | 14.76%  |
| 3.01-4.0   | 216      | 376    | 5.43%   |
| 4.01-10.0  | 156      | 298    | 3.92%   |
| 2.01-3.0   | 141      | 218    | 3.54%   |
| 10.01-20.0 | 28       | 66     | 0.7%    |
| 20.01-50.0 | 1        | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 575      | 20.87%  |
| 501-1000       | 497      | 18.04%  |
| 1001-2000      | 488      | 17.71%  |
| 251-500        | 389      | 14.12%  |
| 101-250        | 358      | 12.99%  |
| 2001-3000      | 258      | 9.36%   |
| Unknown        | 71       | 2.58%   |
| 51-100         | 64       | 2.32%   |
| 21-50          | 28       | 1.02%   |
| 1-20           | 27       | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 411      | 14.43%  |
| 501-1000       | 398      | 13.97%  |
| 1-20           | 379      | 13.3%   |
| 251-500        | 352      | 12.36%  |
| 1001-2000      | 345      | 12.11%  |
| 21-50          | 269      | 9.44%   |
| 51-100         | 247      | 8.67%   |
| More than 3000 | 232      | 8.14%   |
| 2001-3000      | 145      | 5.09%   |
| Unknown        | 71       | 2.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 15       | 17     | 2.8%    |
| Seagate ST2000DM008-2FR102 2TB        | 7        | 10     | 1.31%   |
| Kingston SV300S37A120G 120GB SSD      | 7        | 7      | 1.31%   |
| WDC WD5000AAKX-001CA0 500GB           | 6        | 7      | 1.12%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 6        | 6      | 1.12%   |
| WDC WD20EARS-00MVWB0 2TB              | 6        | 8      | 1.12%   |
| Seagate ST2000DM006-2DM164 2TB        | 6        | 7      | 1.12%   |
| Seagate ST1000DM010-2EP102 1TB        | 6        | 7      | 1.12%   |
| Seagate ST31000528AS 1TB              | 5        | 5      | 0.93%   |
| Seagate ST1000DM003-9YN162 1TB        | 5        | 5      | 0.93%   |
| Samsung Electronics SSD 960 EVO 250GB | 5        | 11     | 0.93%   |
| OCZ VERTEX4 256GB SSD                 | 5        | 8      | 0.93%   |
| WDC WD20EARX-00PASB0 2TB              | 4        | 4      | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB              | 4        | 4      | 0.75%   |
| WDC WD10EZEX-00WN4A0 1TB              | 4        | 4      | 0.75%   |
| WDC WD10EARS-00Y5B1 1TB               | 4        | 6      | 0.75%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 4        | 5      | 0.75%   |
| Toshiba MQ01ABD100 1TB                | 4        | 7      | 0.75%   |
| Seagate ST3500418AS 500GB             | 4        | 5      | 0.75%   |
| Seagate ST3320620AS 320GB             | 4        | 4      | 0.75%   |
| Seagate ST31000524AS 1TB              | 4        | 4      | 0.75%   |
| Seagate ST2000DM001-1ER164 2TB        | 4        | 4      | 0.75%   |
| Seagate ST2000DM001-1CH164 2TB        | 4        | 4      | 0.75%   |
| Seagate ST1000DM003-1ER162 1TB        | 4        | 4      | 0.75%   |
| Samsung Electronics SSD 980 1TB       | 4        | 4      | 0.75%   |
| Samsung Electronics HD103SJ 1TB       | 4        | 6      | 0.75%   |
| Crucial CT525MX300SSD1 528GB          | 4        | 6      | 0.75%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 3        | 4      | 0.56%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 3        | 3      | 0.56%   |
| WDC WD40EFRX-68WT0N0 4TB              | 3        | 9      | 0.56%   |
| WDC WD40EFRX-68N32N0 4TB              | 3        | 3      | 0.56%   |
| WDC WD30EFRX-68EUZN0 3TB              | 3        | 3      | 0.56%   |
| WDC WD20EFRX-68EUZN0 2TB              | 3        | 7      | 0.56%   |
| WDC WD10EZEX-08M2NA0 1TB              | 3        | 3      | 0.56%   |
| Toshiba MK3261GSYN 320GB              | 3        | 3      | 0.56%   |
| Toshiba DT01ACA100 1TB                | 3        | 3      | 0.56%   |
| Seagate ST500LT012-1DG142 500GB       | 3        | 3      | 0.56%   |
| Seagate ST4000DM004-2CV104 4TB        | 3        | 3      | 0.56%   |
| Seagate ST3500312CS 500GB             | 3        | 4      | 0.56%   |
| Seagate ST2000DM001-9YN164 2TB        | 3        | 3      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 141      | 198    | 28.03%  |
| Seagate               | 141      | 177    | 28.03%  |
| Samsung Electronics   | 53       | 71     | 10.54%  |
| Toshiba               | 28       | 37     | 5.57%   |
| Hitachi               | 23       | 25     | 4.57%   |
| Kingston              | 18       | 24     | 3.58%   |
| Crucial               | 15       | 19     | 2.98%   |
| Intel                 | 12       | 14     | 2.39%   |
| SanDisk               | 11       | 12     | 2.19%   |
| OCZ                   | 10       | 17     | 1.99%   |
| A-DATA Technology     | 7        | 8      | 1.39%   |
| HGST                  | 6        | 6      | 1.19%   |
| Corsair               | 4        | 4      | 0.8%    |
| Hewlett-Packard       | 3        | 3      | 0.6%    |
| Drevo                 | 3        | 4      | 0.6%    |
| XrayDisk              | 2        | 3      | 0.4%    |
| SPCC                  | 2        | 3      | 0.4%    |
| Realtek Semiconductor | 2        | 3      | 0.4%    |
| PNY                   | 2        | 3      | 0.4%    |
| Plextor               | 2        | 9      | 0.4%    |
| Patriot               | 2        | 2      | 0.4%    |
| Maxtor                | 2        | 2      | 0.4%    |
| Transcend             | 1        | 7      | 0.2%    |
| TO Exter              | 1        | 1      | 0.2%    |
| SSSTC                 | 1        | 1      | 0.2%    |
| Silicon Motion        | 1        | 1      | 0.2%    |
| Micron Technology     | 1        | 1      | 0.2%    |
| LITEON                | 1        | 1      | 0.2%    |
| Kingrich              | 1        | 1      | 0.2%    |
| JMicron Technology    | 1        | 1      | 0.2%    |
| INNOVATION IT         | 1        | 1      | 0.2%    |
| GLOWAY                | 1        | 1      | 0.2%    |
| Gigabyte Technology   | 1        | 1      | 0.2%    |
| Fujitsu               | 1        | 1      | 0.2%    |
| BAITITON              | 1        | 4      | 0.2%    |
| Apple                 | 1        | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 141      | 177    | 39.06%  |
| WDC                 | 136      | 191    | 37.67%  |
| Toshiba             | 27       | 36     | 7.48%   |
| Samsung Electronics | 23       | 28     | 6.37%   |
| Hitachi             | 23       | 25     | 6.37%   |
| HGST                | 6        | 6      | 1.66%   |
| Maxtor              | 2        | 2      | 0.55%   |
| Hewlett-Packard     | 1        | 1      | 0.28%   |
| Fujitsu             | 1        | 1      | 0.28%   |
| Apple               | 1        | 1      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 320      | 468    | 70.18%  |
| SSD  | 108      | 150    | 23.68%  |
| NVMe | 28       | 49     | 6.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1        | 1      | 12.5%   |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1        | 1      | 12.5%   |
| Transcend TS128GMTE850 128GB                     | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB                  | 1        | 1      | 12.5%   |
| Seagate ST32000644NS 2TB                         | 1        | 1      | 12.5%   |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1        | 1      | 12.5%   |
| Samsung Electronics HM251JI 250GB                | 1        | 1      | 12.5%   |
| Kingston SV300S37A120G 120GB SSD                 | 1        | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 25%     |
| Seagate             | 2        | 2      | 25%     |
| Samsung Electronics | 2        | 2      | 25%     |
| Transcend           | 1        | 1      | 12.5%   |
| Kingston            | 1        | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1487     | 4694   | 47.1%   |
| Detected | 1233     | 3652   | 39.06%  |
| Malfunc  | 428      | 667    | 13.56%  |
| Failed   | 8        | 8      | 0.25%   |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 1328     | 30.5%   |
| Intel                            | 1286     | 29.54%  |
| Samsung Electronics              | 591      | 13.57%  |
| SanDisk                          | 191      | 4.39%   |
| ASMedia Technology               | 188      | 4.32%   |
| Phison Electronics               | 163      | 3.74%   |
| Micron/Crucial Technology        | 82       | 1.88%   |
| Kingston Technology Company      | 82       | 1.88%   |
| ADATA Technology                 | 74       | 1.7%    |
| Marvell Technology Group         | 70       | 1.61%   |
| Silicon Motion                   | 63       | 1.45%   |
| JMicron Technology               | 41       | 0.94%   |
| SK hynix                         | 29       | 0.67%   |
| Realtek Semiconductor            | 26       | 0.6%    |
| Seagate Technology               | 15       | 0.34%   |
| Micron Technology                | 13       | 0.3%    |
| Toshiba America Info Systems     | 12       | 0.28%   |
| Nvidia                           | 12       | 0.28%   |
| Broadcom / LSI                   | 10       | 0.23%   |
| Adaptec                          | 9        | 0.21%   |
| MAXIO Technology (Hangzhou)      | 8        | 0.18%   |
| LSI Logic / Symbios Logic        | 8        | 0.18%   |
| VIA Technologies                 | 7        | 0.16%   |
| Silicon Image                    | 7        | 0.16%   |
| Lite-On Technology               | 7        | 0.16%   |
| KIOXIA                           | 7        | 0.16%   |
| Yangtze Memory Technologies      | 4        | 0.09%   |
| Shenzhen Longsys Electronics     | 4        | 0.09%   |
| OCZ Technology Group             | 4        | 0.09%   |
| Hewlett-Packard                  | 4        | 0.09%   |
| Netac Technology                 | 2        | 0.05%   |
| Integrated Technology Express    | 2        | 0.05%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
| Lenovo                           | 1        | 0.02%   |
| INNOGRIT                         | 1        | 0.02%   |
| ATTO Technology                  | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 911      | 17.24%  |
| AMD 400 Series Chipset SATA Controller                                                  | 412      | 7.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 372      | 7.04%   |
| AMD 500 Series Chipset SATA Controller                                                  | 196      | 3.71%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 179      | 3.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 161      | 3.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 146      | 2.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 132      | 2.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 107      | 2.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 99       | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 94       | 1.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 91       | 1.72%   |
| Phison E12 NVMe Controller                                                              | 82       | 1.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 81       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 76       | 1.44%   |
| AMD 300 Series Chipset SATA Controller                                                  | 75       | 1.42%   |
| Intel SATA Controller [RAID mode]                                                       | 74       | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 72       | 1.36%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 67       | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 65       | 1.23%   |
| AMD X370 Series Chipset SATA Controller                                                 | 62       | 1.17%   |
| AMD FCH SATA Controller D                                                               | 51       | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 50       | 0.95%   |
| Samsung NVMe SSD Controller 980                                                         | 46       | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 42       | 0.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 40       | 0.76%   |
| Kingston Company A2000 NVMe SSD                                                         | 38       | 0.72%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 38       | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 38       | 0.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 37       | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 37       | 0.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 37       | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 36       | 0.68%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                               | 34       | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 34       | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 34       | 0.64%   |
| Intel SSD 660P Series                                                                   | 33       | 0.62%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 32       | 0.61%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 28       | 0.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 28       | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2382     | 58.86%  |
| NVMe | 1235     | 30.52%  |
| IDE  | 275      | 6.8%    |
| RAID | 134      | 3.31%   |
| SAS  | 14       | 0.35%   |
| SCSI | 7        | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 1352     | 51.68%  |
| Intel  | 1264     | 48.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 116      | 4.4%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 109      | 4.14%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 68       | 2.58%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 64       | 2.43%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 56       | 2.13%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 55       | 2.09%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 49       | 1.86%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 49       | 1.86%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 40       | 1.52%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 39       | 1.48%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 38       | 1.44%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 38       | 1.44%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 37       | 1.4%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 34       | 1.29%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 26       | 0.99%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 25       | 0.95%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 25       | 0.95%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 25       | 0.95%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 25       | 0.95%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 24       | 0.91%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 23       | 0.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 23       | 0.87%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 23       | 0.87%   |
| AMD FX-6300 Six-Core Processor              | 23       | 0.87%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 22       | 0.84%   |
| AMD FX-8350 Eight-Core Processor            | 22       | 0.84%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 21       | 0.8%    |
| AMD Ryzen 7 1700 Eight-Core Processor       | 21       | 0.8%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 20       | 0.76%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 20       | 0.76%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 20       | 0.76%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 20       | 0.76%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 20       | 0.76%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 19       | 0.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 19       | 0.72%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 18       | 0.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 18       | 0.68%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 17       | 0.65%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 17       | 0.65%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 16       | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 439      | 16.74%  |
| Intel Core i5           | 405      | 15.44%  |
| Intel Core i7           | 392      | 14.94%  |
| AMD Ryzen 7             | 391      | 14.91%  |
| AMD Ryzen 9             | 203      | 7.74%   |
| Intel Xeon              | 96       | 3.66%   |
| Intel Core i3           | 95       | 3.62%   |
| AMD FX                  | 88       | 3.35%   |
| Other                   | 76       | 2.9%    |
| AMD Ryzen 3             | 61       | 2.33%   |
| Intel Core i9           | 42       | 1.6%    |
| Intel Pentium           | 36       | 1.37%   |
| Intel Celeron           | 35       | 1.33%   |
| AMD Ryzen Threadripper  | 33       | 1.26%   |
| Intel Core 2 Quad       | 28       | 1.07%   |
| AMD A8                  | 24       | 0.91%   |
| Intel Core 2 Duo        | 22       | 0.84%   |
| AMD Athlon              | 16       | 0.61%   |
| Intel Pentium Dual-Core | 14       | 0.53%   |
| AMD Phenom II X4        | 14       | 0.53%   |
| AMD A10                 | 14       | 0.53%   |
| AMD A6                  | 10       | 0.38%   |
| Intel Atom              | 9        | 0.34%   |
| AMD Athlon II X4        | 9        | 0.34%   |
| AMD Athlon II X2        | 9        | 0.34%   |
| AMD Phenom II X6        | 7        | 0.27%   |
| AMD Ryzen 5 PRO         | 6        | 0.23%   |
| AMD Athlon 64 X2        | 6        | 0.23%   |
| Intel Pentium Dual      | 4        | 0.15%   |
| Intel Genuine           | 4        | 0.15%   |
| AMD Athlon X4           | 4        | 0.15%   |
| AMD A4                  | 4        | 0.15%   |
| Intel Pentium 4         | 3        | 0.11%   |
| Intel Core 2            | 3        | 0.11%   |
| AMD Phenom              | 3        | 0.11%   |
| AMD GX                  | 3        | 0.11%   |
| Intel Pentium Gold      | 2        | 0.08%   |
| AMD Ryzen 3 PRO         | 2        | 0.08%   |
| AMD Opteron             | 2        | 0.08%   |
| AMD E                   | 2        | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 873      | 33.23%  |
| 6       | 622      | 23.68%  |
| 8       | 505      | 19.22%  |
| 2       | 274      | 10.43%  |
| 12      | 151      | 5.75%   |
| 16      | 106      | 4.04%   |
| 3       | 28       | 1.07%   |
| 10      | 21       | 0.8%    |
| 1       | 14       | 0.53%   |
| 24      | 10       | 0.38%   |
| 32      | 6        | 0.23%   |
| 14      | 5        | 0.19%   |
| 64      | 4        | 0.15%   |
| 18      | 2        | 0.08%   |
| Unknown | 2        | 0.08%   |
| 40      | 1        | 0.04%   |
| 28      | 1        | 0.04%   |
| 22      | 1        | 0.04%   |
| 20      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2594     | 99.16%  |
| 2      | 22       | 0.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1892     | 72.24%  |
| 1       | 725      | 27.68%  |
| Unknown | 2        | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2572     | 98.09%  |
| Unknown        | 49       | 1.87%   |
| 32-bit         | 1        | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 892      | 32.66%  |
| 0x08701021 | 211      | 7.73%   |
| 0x0800820d | 148      | 5.42%   |
| 0x306c3    | 131      | 4.8%    |
| 0x08701013 | 95       | 3.48%   |
| 0x906e9    | 79       | 2.89%   |
| 0x306a9    | 79       | 2.89%   |
| 0x506e3    | 73       | 2.67%   |
| 0x206a7    | 68       | 2.49%   |
| 0x08001138 | 63       | 2.31%   |
| 0x906ea    | 61       | 2.23%   |
| 0x0a201016 | 56       | 2.05%   |
| 0x0a201009 | 50       | 1.83%   |
| 0x1067a    | 34       | 1.24%   |
| 0x0a601203 | 34       | 1.24%   |
| 0x08001137 | 29       | 1.06%   |
| 0x06000852 | 28       | 1.03%   |
| 0x08108109 | 27       | 0.99%   |
| 0x0a20120a | 22       | 0.81%   |
| 0x08101016 | 22       | 0.81%   |
| 0x906ec    | 21       | 0.77%   |
| 0x0a50000d | 21       | 0.77%   |
| 0xa0655    | 19       | 0.7%    |
| 0x306f2    | 19       | 0.7%    |
| 0x06000822 | 19       | 0.7%    |
| 0x906ed    | 18       | 0.66%   |
| 0xa0671    | 14       | 0.51%   |
| 0xa0653    | 14       | 0.51%   |
| 0x08001129 | 14       | 0.51%   |
| 0x010000c8 | 13       | 0.48%   |
| 0x0a50000c | 12       | 0.44%   |
| 0x06001119 | 12       | 0.44%   |
| 0x106e5    | 11       | 0.4%    |
| 0x08701030 | 11       | 0.4%    |
| 0x906eb    | 10       | 0.37%   |
| 0x90672    | 10       | 0.37%   |
| 0x206d7    | 10       | 0.37%   |
| 0x106a5    | 10       | 0.37%   |
| 0x0800820b | 10       | 0.37%   |
| 0x06003106 | 10       | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 428      | 16.26%  |
| KabyLake         | 329      | 12.5%   |
| Zen 3            | 255      | 9.68%   |
| Zen+             | 252      | 9.57%   |
| Haswell          | 238      | 9.04%   |
| Zen              | 171      | 6.49%   |
| Skylake          | 127      | 4.82%   |
| SandyBridge      | 122      | 4.63%   |
| IvyBridge        | 122      | 4.63%   |
| Piledriver       | 100      | 3.8%    |
| Unknown          | 84       | 3.19%   |
| CometLake        | 63       | 2.39%   |
| Penryn           | 61       | 2.32%   |
| K10              | 46       | 1.75%   |
| Nehalem          | 33       | 1.25%   |
| Alderlake Hybrid | 27       | 1.03%   |
| Westmere         | 24       | 0.91%   |
| Core             | 20       | 0.76%   |
| Icelake          | 18       | 0.68%   |
| Steamroller      | 16       | 0.61%   |
| Broadwell        | 16       | 0.61%   |
| Silvermont       | 14       | 0.53%   |
| K10 Llano        | 13       | 0.49%   |
| Excavator        | 8        | 0.3%    |
| K8 Hammer        | 7        | 0.27%   |
| Bulldozer        | 7        | 0.27%   |
| NetBurst         | 5        | 0.19%   |
| Jaguar           | 5        | 0.19%   |
| Goldmont plus    | 5        | 0.19%   |
| Bonnell          | 5        | 0.19%   |
| Puma             | 4        | 0.15%   |
| Goldmont         | 3        | 0.11%   |
| Tremont          | 2        | 0.08%   |
| Bobcat           | 2        | 0.08%   |
| Gracemont        | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 1253     | 44.01%  |
| AMD                              | 1103     | 38.74%  |
| Intel                            | 480      | 16.86%  |
| ASPEED Technology                | 5        | 0.18%   |
| Matrox Electronics Systems       | 2        | 0.07%   |
| ATI Technologies                 | 2        | 0.07%   |
| VIA Technologies                 | 1        | 0.04%   |
| Silicon Integrated Systems [SiS] | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 291      | 9.83%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 132      | 4.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 95       | 3.21%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 85       | 2.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 85       | 2.87%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 72       | 2.43%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 63       | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 58       | 1.96%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 57       | 1.93%   |
| Intel HD Graphics 630                                                       | 51       | 1.72%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 48       | 1.62%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 45       | 1.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 44       | 1.49%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 43       | 1.45%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 41       | 1.39%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 41       | 1.39%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 40       | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                              | 38       | 1.28%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 37       | 1.25%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 37       | 1.25%   |
| Intel HD Graphics 530                                                       | 36       | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 35       | 1.18%   |
| AMD Raphael                                                                 | 35       | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 33       | 1.11%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 29       | 0.98%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 29       | 0.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 29       | 0.98%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 28       | 0.95%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 28       | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 27       | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 24       | 0.81%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 24       | 0.81%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 23       | 0.78%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 23       | 0.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 22       | 0.74%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 21       | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 21       | 0.71%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 21       | 0.71%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 20       | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 20       | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1107     | 41.57%  |
| 1 x AMD              | 975      | 36.61%  |
| 1 x Intel            | 339      | 12.73%  |
| AMD + Nvidia         | 61       | 2.29%   |
| Intel + Nvidia       | 53       | 1.99%   |
| 2 x AMD              | 48       | 1.8%    |
| 2 x Nvidia           | 33       | 1.24%   |
| Intel + AMD          | 26       | 0.98%   |
| 2 x Intel            | 5        | 0.19%   |
| Other                | 4        | 0.15%   |
| 1 x ASPEED           | 3        | 0.11%   |
| 2 x AMD + 1 x Nvidia | 2        | 0.08%   |
| AMD + ASPEED         | 2        | 0.08%   |
| 3 x Nvidia           | 1        | 0.04%   |
| 1 x VIA              | 1        | 0.04%   |
| 1 x SiS              | 1        | 0.04%   |
| 1 x Matrox           | 1        | 0.04%   |
| AMD + Matrox         | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1587     | 59.77%  |
| Proprietary | 1016     | 38.27%  |
| Unknown     | 52       | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 862      | 31.62%  |
| 7.01-8.0   | 594      | 21.79%  |
| 3.01-4.0   | 324      | 11.89%  |
| 1.01-2.0   | 274      | 10.05%  |
| 8.01-16.0  | 198      | 7.26%   |
| 5.01-6.0   | 193      | 7.08%   |
| 0.51-1.0   | 125      | 4.59%   |
| 0.01-0.5   | 92       | 3.37%   |
| 2.01-3.0   | 43       | 1.58%   |
| 16.01-24.0 | 18       | 0.66%   |
| 4.01-5.0   | 3        | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 475      | 14.56%  |
| Dell                 | 383      | 11.74%  |
| Goldstar             | 375      | 11.49%  |
| Acer                 | 259      | 7.94%   |
| AOC                  | 212      | 6.5%    |
| BenQ                 | 197      | 6.04%   |
| Ancor Communications | 175      | 5.36%   |
| Hewlett-Packard      | 156      | 4.78%   |
| Philips              | 116      | 3.56%   |
| ViewSonic            | 84       | 2.57%   |
| ASUSTek Computer     | 77       | 2.36%   |
| Iiyama               | 68       | 2.08%   |
| LG Electronics       | 58       | 1.78%   |
| Lenovo               | 44       | 1.35%   |
| MSI                  | 39       | 1.2%    |
| Unknown              | 37       | 1.13%   |
| Gigabyte Technology  | 33       | 1.01%   |
| NEC Computers        | 28       | 0.86%   |
| Sony                 | 27       | 0.83%   |
| Eizo                 | 23       | 0.7%    |
| Sceptre Tech         | 19       | 0.58%   |
| Unknown              | 18       | 0.55%   |
| Fujitsu Siemens      | 17       | 0.52%   |
| Vizio                | 11       | 0.34%   |
| Valve                | 11       | 0.34%   |
| HUAWEI               | 10       | 0.31%   |
| HannStar             | 10       | 0.31%   |
| Denver               | 10       | 0.31%   |
| Toshiba              | 9        | 0.28%   |
| Pixio                | 9        | 0.28%   |
| Medion               | 9        | 0.28%   |
| Hitachi              | 9        | 0.28%   |
| HPN                  | 8        | 0.25%   |
| AUS                  | 8        | 0.25%   |
| Vestel Elektronik    | 7        | 0.21%   |
| Panasonic            | 7        | 0.21%   |
| Lenovo Group Limited | 7        | 0.21%   |
| Idek Iiyama          | 7        | 0.21%   |
| ___                  | 6        | 0.18%   |
| Packard Bell         | 6        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 26       | 0.73%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 26       | 0.73%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 23       | 0.64%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 21       | 0.59%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 20       | 0.56%   |
| Unknown                                                               | 18       | 0.5%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 17       | 0.48%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 17       | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 15       | 0.42%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 14       | 0.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 14       | 0.39%   |
| Valve Index HMD VLV91A8                                               | 11       | 0.31%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 11       | 0.31%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 10       | 0.28%   |
| AOC 27G2WG3 AOC2702 1920x1080 598x336mm 27.0-inch                     | 10       | 0.28%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 10       | 0.28%   |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch   | 9        | 0.25%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                | 9        | 0.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 9        | 0.25%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 9        | 0.25%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 9        | 0.25%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 9        | 0.25%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 9        | 0.25%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 9        | 0.25%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 8        | 0.22%   |
| AOC U34G2G1 AOC3402 3440x1440 797x334mm 34.0-inch                     | 8        | 0.22%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 8        | 0.22%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                         | 7        | 0.2%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 7        | 0.2%    |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                  | 7        | 0.2%    |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 7        | 0.2%    |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch               | 7        | 0.2%    |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 7        | 0.2%    |
| AOC 2460X AOC2460 1920x1200 518x324mm 24.1-inch                       | 7        | 0.2%    |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                     | 7        | 0.2%    |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 7        | 0.2%    |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 7        | 0.2%    |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch         | 6        | 0.17%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 6        | 0.17%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 6        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1341     | 42.88%  |
| 2560x1440 (QHD)    | 412      | 13.18%  |
| 3840x2160 (4K)     | 339      | 10.84%  |
| Unknown            | 119      | 3.81%   |
| 1680x1050 (WSXGA+) | 111      | 3.55%   |
| 3440x1440          | 108      | 3.45%   |
| 1280x1024 (SXGA)   | 104      | 3.33%   |
| 1920x1200 (WUXGA)  | 95       | 3.04%   |
| 1366x768 (WXGA)    | 78       | 2.49%   |
| 2560x1080          | 64       | 2.05%   |
| 1440x900 (WXGA+)   | 60       | 1.92%   |
| 1600x900 (HD+)     | 59       | 1.89%   |
| 3840x1080          | 52       | 1.66%   |
| 1360x768           | 34       | 1.09%   |
| 1920x540           | 13       | 0.42%   |
| 3840x1600          | 12       | 0.38%   |
| 7680x2160          | 10       | 0.32%   |
| 5760x1080          | 9        | 0.29%   |
| 2560x1600          | 9        | 0.29%   |
| 4480x1440          | 8        | 0.26%   |
| 5120x1440          | 7        | 0.22%   |
| 1600x1200          | 6        | 0.19%   |
| 1024x768 (XGA)     | 6        | 0.19%   |
| 6400x2160          | 5        | 0.16%   |
| 6400x1440          | 4        | 0.13%   |
| 3840x1200          | 4        | 0.13%   |
| 2160x1200          | 4        | 0.13%   |
| 5760x2160          | 3        | 0.1%    |
| 4480x1080          | 3        | 0.1%    |
| 2288x1287          | 3        | 0.1%    |
| 5760x1200          | 2        | 0.06%   |
| 5360x1440          | 2        | 0.06%   |
| 4240x1440          | 2        | 0.06%   |
| 3286x1080          | 2        | 0.06%   |
| 1280x720 (HD)      | 2        | 0.06%   |
| 8320x1440          | 1        | 0.03%   |
| 7920x1440          | 1        | 0.03%   |
| 7680x4320          | 1        | 0.03%   |
| 7680x3996          | 1        | 0.03%   |
| 7680x1440          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 574      | 17.84%  |
| 24      | 542      | 16.84%  |
| 23      | 380      | 11.81%  |
| Unknown | 348      | 10.81%  |
| 21      | 345      | 10.72%  |
| 31      | 141      | 4.38%   |
| 34      | 139      | 4.32%   |
| 19      | 127      | 3.95%   |
| 22      | 87       | 2.7%    |
| 18      | 74       | 2.3%    |
| 20      | 57       | 1.77%   |
| 17      | 50       | 1.55%   |
| 25      | 33       | 1.03%   |
| 72      | 32       | 0.99%   |
| 84      | 31       | 0.96%   |
| 15      | 27       | 0.84%   |
| 48      | 21       | 0.65%   |
| 32      | 21       | 0.65%   |
| 54      | 20       | 0.62%   |
| 40      | 20       | 0.62%   |
| 26      | 17       | 0.53%   |
| 28      | 13       | 0.4%    |
| 29      | 12       | 0.37%   |
| 46      | 11       | 0.34%   |
| 37      | 10       | 0.31%   |
| 35      | 9        | 0.28%   |
| 33      | 9        | 0.28%   |
| 65      | 6        | 0.19%   |
| 39      | 6        | 0.19%   |
| 49      | 5        | 0.16%   |
| 43      | 5        | 0.16%   |
| 42      | 5        | 0.16%   |
| 13      | 5        | 0.16%   |
| 142     | 3        | 0.09%   |
| 74      | 3        | 0.09%   |
| 57      | 3        | 0.09%   |
| 38      | 3        | 0.09%   |
| 36      | 3        | 0.09%   |
| 30      | 3        | 0.09%   |
| 12      | 3        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1313     | 43.62%  |
| 401-500        | 602      | 20%     |
| Unknown        | 348      | 11.56%  |
| 601-700        | 221      | 7.34%   |
| 701-800        | 171      | 5.68%   |
| 1001-1500      | 73       | 2.43%   |
| 301-350        | 72       | 2.39%   |
| 351-400        | 70       | 2.33%   |
| 1501-2000      | 67       | 2.23%   |
| 801-900        | 48       | 1.59%   |
| 901-1000       | 11       | 0.37%   |
| 201-300        | 10       | 0.33%   |
| More than 2000 | 4        | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1838     | 65.57%  |
| 16/10   | 322      | 11.49%  |
| Unknown | 309      | 11.02%  |
| 21/9    | 169      | 6.03%   |
| 5/4     | 104      | 3.71%   |
| 4/3     | 22       | 0.78%   |
| 32/9    | 22       | 0.78%   |
| 3/2     | 7        | 0.25%   |
| 2.00    | 3        | 0.11%   |
| 1.00    | 3        | 0.11%   |
| 1.96    | 2        | 0.07%   |
| 0.89    | 1        | 0.04%   |
| 0.57    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1040     | 33.42%  |
| 301-350        | 589      | 18.93%  |
| Unknown        | 348      | 11.18%  |
| 351-500        | 333      | 10.7%   |
| 151-200        | 256      | 8.23%   |
| 251-300        | 203      | 6.52%   |
| More than 1000 | 109      | 3.5%    |
| 141-150        | 106      | 3.41%   |
| 501-1000       | 84       | 2.7%    |
| 101-110        | 22       | 0.71%   |
| 71-80          | 8        | 0.26%   |
| 131-140        | 4        | 0.13%   |
| 111-120        | 4        | 0.13%   |
| 91-100         | 4        | 0.13%   |
| 81-90          | 1        | 0.03%   |
| 121-130        | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1552     | 53.26%  |
| 101-120       | 703      | 24.12%  |
| Unknown       | 348      | 11.94%  |
| 121-160       | 148      | 5.08%   |
| 1-50          | 83       | 2.85%   |
| 161-240       | 79       | 2.71%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1712     | 63.79%  |
| 2     | 717      | 26.71%  |
| 3     | 147      | 5.48%   |
| 0     | 92       | 3.43%   |
| 4     | 13       | 0.48%   |
| 5     | 2        | 0.07%   |
| 6     | 1        | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1560     | 42.15%  |
| Intel                                  | 1304     | 35.23%  |
| Qualcomm Atheros                       | 207      | 5.59%   |
| Broadcom                               | 91       | 2.46%   |
| TP-Link                                | 63       | 1.7%    |
| Ralink Technology                      | 63       | 1.7%    |
| Microsoft                              | 60       | 1.62%   |
| MediaTek                               | 44       | 1.19%   |
| Ralink                                 | 28       | 0.76%   |
| Aquantia                               | 25       | 0.68%   |
| Samsung Electronics                    | 16       | 0.43%   |
| Marvell Technology Group               | 16       | 0.43%   |
| NetGear                                | 15       | 0.41%   |
| Qualcomm Atheros Communications        | 13       | 0.35%   |
| Xiaomi                                 | 12       | 0.32%   |
| D-Link                                 | 12       | 0.32%   |
| Nvidia                                 | 11       | 0.3%    |
| Mellanox Technologies                  | 11       | 0.3%    |
| Microchip Technology                   | 10       | 0.27%   |
| D-Link System                          | 8        | 0.22%   |
| ASIX Electronics                       | 8        | 0.22%   |
| Oculus VR                              | 7        | 0.19%   |
| Broadcom Limited                       | 7        | 0.19%   |
| Huawei Technologies                    | 6        | 0.16%   |
| ASUSTek Computer                       | 6        | 0.16%   |
| Google                                 | 5        | 0.14%   |
| Edimax Technology                      | 5        | 0.14%   |
| DisplayLink                            | 4        | 0.11%   |
| AVM                                    | 4        | 0.11%   |
| Wilocity                               | 3        | 0.08%   |
| Motorola PCS                           | 3        | 0.08%   |
| Mercucys                               | 3        | 0.08%   |
| Belkin Components                      | 3        | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.05%   |
| Tenda                                  | 2        | 0.05%   |
| STMicroelectronics                     | 2        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.05%   |
| Qualcomm                               | 2        | 0.05%   |
| QLogic                                 | 2        | 0.05%   |
| QinHeng Electronics                    | 2        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1221     | 28.51%  |
| Intel I211 Gigabit Network Connection                             | 393      | 9.18%   |
| Intel Wi-Fi 6 AX200                                               | 236      | 5.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 210      | 4.9%    |
| Intel Ethernet Connection (2) I219-V                              | 161      | 3.76%   |
| Intel Ethernet Controller I225-V                                  | 92       | 2.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 90       | 2.1%    |
| Intel Ethernet Connection (7) I219-V                              | 79       | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53       | 1.24%   |
| Intel Ethernet Connection (2) I218-V                              | 52       | 1.21%   |
| Intel Wireless-AC 9260                                            | 49       | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 40       | 0.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38       | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 35       | 0.82%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 35       | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33       | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 33       | 0.77%   |
| Microsoft Xbox 360 Wireless Adapter                               | 31       | 0.72%   |
| Intel Wireless 8260                                               | 29       | 0.68%   |
| Ralink MT7601U Wireless Adapter                                   | 26       | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 24       | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 24       | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22       | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 21       | 0.49%   |
| Realtek 802.11ac NIC                                              | 21       | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 21       | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21       | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 21       | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20       | 0.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 20       | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 20       | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 20       | 0.47%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 19       | 0.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 19       | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 18       | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18       | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 17       | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.37%   |
| Intel Ethernet Connection (14) I219-V                             | 16       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 585      | 44.9%   |
| Realtek Semiconductor                 | 209      | 16.04%  |
| Qualcomm Atheros                      | 112      | 8.6%    |
| Ralink Technology                     | 63       | 4.83%   |
| Microsoft                             | 60       | 4.6%    |
| TP-Link                               | 59       | 4.53%   |
| Broadcom                              | 59       | 4.53%   |
| MediaTek                              | 43       | 3.3%    |
| Ralink                                | 28       | 2.15%   |
| NetGear                               | 14       | 1.07%   |
| Qualcomm Atheros Communications       | 13       | 1%      |
| D-Link                                | 12       | 0.92%   |
| ASUSTek Computer                      | 6        | 0.46%   |
| Edimax Technology                     | 5        | 0.38%   |
| D-Link System                         | 4        | 0.31%   |
| Broadcom Limited                      | 4        | 0.31%   |
| AVM                                   | 4        | 0.31%   |
| Wilocity                              | 3        | 0.23%   |
| Mercucys                              | 3        | 0.23%   |
| Belkin Components                     | 3        | 0.23%   |
| Tenda                                 | 2        | 0.15%   |
| Micro Star International              | 2        | 0.15%   |
| Linksys                               | 2        | 0.15%   |
| IMC Networks                          | 2        | 0.15%   |
| ZyXEL Communications                  | 1        | 0.08%   |
| Yoctopuce Sarl                        | 1        | 0.08%   |
| Sagem                                 | 1        | 0.08%   |
| BUFFALO                               | 1        | 0.08%   |
| AboCom Systems                        | 1        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 236      | 17.95%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 90       | 6.84%   |
| Intel Wireless-AC 9260                                         | 49       | 3.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 40       | 3.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 35       | 2.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 35       | 2.66%   |
| Microsoft Xbox 360 Wireless Adapter                            | 31       | 2.36%   |
| Intel Wireless 8260                                            | 29       | 2.21%   |
| Ralink MT7601U Wireless Adapter                                | 26       | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 24       | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 22       | 1.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 21       | 1.6%    |
| Realtek 802.11ac NIC                                           | 21       | 1.6%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 21       | 1.6%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 20       | 1.52%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 19       | 1.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 19       | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18       | 1.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 17       | 1.29%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 15       | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15       | 1.14%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 15       | 1.14%   |
| Intel Wireless 7265                                            | 15       | 1.14%   |
| Intel Wireless 8265 / 8275                                     | 14       | 1.06%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 13       | 0.99%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 13       | 0.99%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 12       | 0.91%   |
| Intel Wireless 7260                                            | 12       | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 11       | 0.84%   |
| Microsoft Wireless XBox Controller Dongle                      | 11       | 0.84%   |
| Intel Wireless 3165                                            | 11       | 0.84%   |
| Ralink RT5370 Wireless Adapter                                 | 10       | 0.76%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 10       | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 9        | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                | 9        | 0.68%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 8        | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 8        | 0.61%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 8        | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 7        | 0.53%   |
| TP-Link 802.11ac NIC                                           | 7        | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                        | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Realtek Semiconductor                         | 1487     | 52.6%   |
| Intel                                         | 1054     | 37.28%  |
| Qualcomm Atheros                              | 105      | 3.71%   |
| Broadcom                                      | 33       | 1.17%   |
| Aquantia                                      | 25       | 0.88%   |
| Samsung Electronics                           | 16       | 0.57%   |
| Marvell Technology Group                      | 16       | 0.57%   |
| Xiaomi                                        | 12       | 0.42%   |
| Nvidia                                        | 11       | 0.39%   |
| Mellanox Technologies                         | 9        | 0.32%   |
| ASIX Electronics                              | 8        | 0.28%   |
| TP-Link                                       | 4        | 0.14%   |
| Google                                        | 4        | 0.14%   |
| DisplayLink                                   | 4        | 0.14%   |
| D-Link System                                 | 4        | 0.14%   |
| Huawei Technologies                           | 3        | 0.11%   |
| Broadcom Limited                              | 3        | 0.11%   |
| ZTE WCDMA Technologies MSM                    | 2        | 0.07%   |
| Sony Ericsson Mobile Communications AB        | 2        | 0.07%   |
| Qualcomm                                      | 2        | 0.07%   |
| QLogic                                        | 2        | 0.07%   |
| OPPO Electronics                              | 2        | 0.07%   |
| Motorola PCS                                  | 2        | 0.07%   |
| Apple                                         | 2        | 0.07%   |
| Xilinx                                        | 1        | 0.04%   |
| VIA Technologies                              | 1        | 0.04%   |
| Standard Microsystems [SMC]                   | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]              | 1        | 0.04%   |
| NetGear                                       | 1        | 0.04%   |
| Netchip Technology                            | 1        | 0.04%   |
| MediaTek                                      | 1        | 0.04%   |
| Linux 2.6.35.3-571-gcca29a0 with fsl-usb2-udc | 1        | 0.04%   |
| JMicron Technology                            | 1        | 0.04%   |
| ICS Advent                                    | 1        | 0.04%   |
| HMD Global                                    | 1        | 0.04%   |
| Hisense                                       | 1        | 0.04%   |
| Foxconn / Hon Hai                             | 1        | 0.04%   |
| ADMtek                                        | 1        | 0.04%   |
| 3Com                                          | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1221     | 41.89%  |
| Intel I211 Gigabit Network Connection                                         | 393      | 13.48%  |
| Realtek RTL8125 2.5GbE Controller                                             | 210      | 7.2%    |
| Intel Ethernet Connection (2) I219-V                                          | 161      | 5.52%   |
| Intel Ethernet Controller I225-V                                              | 92       | 3.16%   |
| Intel Ethernet Connection (7) I219-V                                          | 79       | 2.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 53       | 1.82%   |
| Intel Ethernet Connection (2) I218-V                                          | 52       | 1.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 38       | 1.3%    |
| Intel Ethernet Connection I217-LM                                             | 35       | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 33       | 1.13%   |
| Intel 82579V Gigabit Network Connection                                       | 33       | 1.13%   |
| Intel Ethernet Connection I217-V                                              | 24       | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 21       | 0.72%   |
| Intel 82574L Gigabit Network Connection                                       | 21       | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 20       | 0.69%   |
| Intel I210 Gigabit Network Connection                                         | 20       | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                         | 20       | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 18       | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 16       | 0.55%   |
| Intel Ethernet Connection (14) I219-V                                         | 16       | 0.55%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 14       | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 11       | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 11       | 0.38%   |
| Intel Ethernet Connection (11) I219-V                                         | 11       | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 10       | 0.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 10       | 0.34%   |
| Intel Ethernet Connection (7) I219-LM                                         | 10       | 0.34%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 9        | 0.31%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 7        | 0.24%   |
| Intel 82578DC Gigabit Network Connection                                      | 7        | 0.24%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 7        | 0.24%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 6        | 0.21%   |
| Nvidia MCP61 Ethernet                                                         | 6        | 0.21%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 0.21%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 6        | 0.21%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 6        | 0.21%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 5        | 0.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 5        | 0.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 5        | 0.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2594     | 67.15%  |
| WiFi     | 1218     | 31.53%  |
| Modem    | 42       | 1.09%   |
| Unknown  | 9        | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2142     | 78.84%  |
| WiFi     | 574      | 21.13%  |
| Modem    | 1        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1555     | 58.88%  |
| 2     | 903      | 34.19%  |
| 3     | 146      | 5.53%   |
| 0     | 15       | 0.57%   |
| 4     | 14       | 0.53%   |
| 5     | 5        | 0.19%   |
| 6     | 2        | 0.08%   |
| 9     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2213     | 83.48%  |
| Yes  | 438      | 16.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 566      | 46.09%  |
| Cambridge Silicon Radio         | 295      | 24.02%  |
| ASUSTek Computer                | 105      | 8.55%   |
| Realtek Semiconductor           | 69       | 5.62%   |
| Broadcom                        | 42       | 3.42%   |
| MediaTek                        | 34       | 2.77%   |
| TP-Link                         | 19       | 1.55%   |
| Apple                           | 15       | 1.22%   |
| IMC Networks                    | 14       | 1.14%   |
| HTC (High Tech Computer)        | 14       | 1.14%   |
| Qualcomm Atheros Communications | 10       | 0.81%   |
| Foxconn / Hon Hai               | 9        | 0.73%   |
| Edimax Technology               | 7        | 0.57%   |
| Lite-On Technology              | 5        | 0.41%   |
| Integrated System Solution      | 4        | 0.33%   |
| Dynex                           | 4        | 0.33%   |
| Realtek                         | 3        | 0.24%   |
| Micro Star International        | 2        | 0.16%   |
| ISSC                            | 2        | 0.16%   |
| Actions                         | 2        | 0.16%   |
| Roper                           | 1        | 0.08%   |
| Hewlett-Packard                 | 1        | 0.08%   |
| Fujitsu                         | 1        | 0.08%   |
| Cypress Semiconductor           | 1        | 0.08%   |
| Corsair                         | 1        | 0.08%   |
| Belkin Components               | 1        | 0.08%   |
| Unknown                         | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 295      | 23.96%  |
| Intel AX200 Bluetooth                                                | 231      | 18.77%  |
| Intel Bluetooth Device                                               | 103      | 8.37%   |
| Intel Bluetooth wireless interface                                   | 82       | 6.66%   |
| Realtek Bluetooth Radio                                              | 54       | 4.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 49       | 3.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 40       | 3.25%   |
| Intel AX210 Bluetooth                                                | 39       | 3.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 37       | 3.01%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 35       | 2.84%   |
| MediaTek Wireless_Device                                             | 34       | 2.76%   |
| Intel AX201 Bluetooth                                                | 23       | 1.87%   |
| TP-Link UB5A Adapter                                                 | 19       | 1.54%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 18       | 1.46%   |
| ASUS Bluetooth Radio                                                 | 15       | 1.22%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 14       | 1.14%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 12       | 0.97%   |
| ASUS ASUS USB-BT500                                                  | 11       | 0.89%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 10       | 0.81%   |
| IMC Networks Bluetooth Radio                                         | 8        | 0.65%   |
| Foxconn / Hon Hai Wireless_Device                                    | 7        | 0.57%   |
| Apple Bluetooth Host Controller                                      | 7        | 0.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 5        | 0.41%   |
| ASUS Bluetooth Device                                                | 5        | 0.41%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 4        | 0.32%   |
| IMC Networks Wireless_Device                                         | 4        | 0.32%   |
| Edimax Bluetooth Adapter                                             | 4        | 0.32%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 4        | 0.32%   |
| ASUS BCM20702A0                                                      | 4        | 0.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 4        | 0.32%   |
| Realtek RTL8821A Bluetooth                                           | 3        | 0.24%   |
| Realtek Bluetooth Radio                                              | 3        | 0.24%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3        | 0.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 3        | 0.24%   |
| Lite-On Bluetooth Device                                             | 3        | 0.24%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 3        | 0.24%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.16%   |
| Micro Star International Bluetooth Device                            | 2        | 0.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 2        | 0.16%   |
| ISSC Bluetooth Device                                                | 2        | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 1594     | 30.02%  |
| Nvidia                               | 1228     | 23.13%  |
| Intel                                | 1203     | 22.66%  |
| C-Media Electronics                  | 189      | 3.56%   |
| Logitech                             | 96       | 1.81%   |
| Kingston Technology                  | 74       | 1.39%   |
| Focusrite-Novation                   | 57       | 1.07%   |
| SteelSeries ApS                      | 50       | 0.94%   |
| Texas Instruments                    | 48       | 0.9%    |
| Razer USA                            | 48       | 0.9%    |
| Creative Labs                        | 45       | 0.85%   |
| JMTek                                | 44       | 0.83%   |
| Corsair                              | 38       | 0.72%   |
| Creative Technology                  | 34       | 0.64%   |
| Blue Microphones                     | 34       | 0.64%   |
| ASUSTek Computer                     | 27       | 0.51%   |
| Samson Technologies                  | 22       | 0.41%   |
| Valve Software                       | 20       | 0.38%   |
| Yamaha                               | 19       | 0.36%   |
| Sony                                 | 18       | 0.34%   |
| GYROCOM C&C                          | 18       | 0.34%   |
| Generalplus Technology               | 18       | 0.34%   |
| BEHRINGER International              | 18       | 0.34%   |
| RODE Microphones                     | 14       | 0.26%   |
| Micro Star International             | 14       | 0.26%   |
| Audio-Technica                       | 13       | 0.24%   |
| XMOS                                 | 12       | 0.23%   |
| M-Audio                              | 12       | 0.23%   |
| FiiO Electronics Technology          | 12       | 0.23%   |
| SAVITECH                             | 11       | 0.21%   |
| Realtek Semiconductor                | 11       | 0.21%   |
| GN Netcom                            | 11       | 0.21%   |
| Dell                                 | 9        | 0.17%   |
| Cambridge Silicon Radio              | 9        | 0.17%   |
| Giga-Byte Technology                 | 8        | 0.15%   |
| DSEA A/S                             | 8        | 0.15%   |
| Thesycon Systemsoftware & Consulting | 7        | 0.13%   |
| Astro Gaming                         | 7        | 0.13%   |
| Antlion Audio                        | 7        | 0.13%   |
| VIA Technologies                     | 6        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 585      | 9.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 326      | 5.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 292      | 4.64%   |
| Intel 200 Series PCH HD Audio                                              | 178      | 2.83%   |
| AMD Family 17h/19h HD Audio Controller                                     | 170      | 2.7%    |
| AMD Navi 10 HDMI Audio                                                     | 156      | 2.48%   |
| Nvidia GP104 High Definition Audio Controller                              | 154      | 2.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 153      | 2.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 144      | 2.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 134      | 2.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 123      | 1.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 114      | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 114      | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 114      | 1.81%   |
| Nvidia GP106 High Definition Audio Controller                              | 113      | 1.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 93       | 1.48%   |
| Nvidia TU116 High Definition Audio Controller                              | 90       | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 90       | 1.43%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 87       | 1.38%   |
| Nvidia TU104 HD Audio Controller                                           | 78       | 1.24%   |
| Nvidia TU106 High Definition Audio Controller                              | 73       | 1.16%   |
| Nvidia GM204 High Definition Audio Controller                              | 69       | 1.1%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 63       | 1%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 63       | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 60       | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 59       | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 59       | 0.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 55       | 0.87%   |
| C-Media Electronics Blue Snowball                                          | 54       | 0.86%   |
| AMD FCH Azalia Controller                                                  | 53       | 0.84%   |
| Nvidia GA102 High Definition Audio Controller                              | 52       | 0.83%   |
| Nvidia GP102 HDMI Audio Controller                                         | 46       | 0.73%   |
| Nvidia GM206 High Definition Audio Controller                              | 45       | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 45       | 0.72%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 45       | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 43       | 0.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 41       | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 38       | 0.6%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 38       | 0.6%    |
| JMTek USB PnP Audio Device                                                 | 37       | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 492      | 23.16%  |
| Kingston            | 380      | 17.89%  |
| G.Skill             | 331      | 15.58%  |
| Crucial             | 234      | 11.02%  |
| Unknown             | 164      | 7.72%   |
| Samsung Electronics | 112      | 5.27%   |
| SK hynix            | 82       | 3.86%   |
| Micron Technology   | 61       | 2.87%   |
| A-DATA Technology   | 44       | 2.07%   |
| Team                | 35       | 1.65%   |
| Patriot             | 33       | 1.55%   |
| GOODRAM             | 19       | 0.89%   |
| Unknown             | 15       | 0.71%   |
| PNY                 | 10       | 0.47%   |
| AMD                 | 9        | 0.42%   |
| Nanya Technology    | 8        | 0.38%   |
| Golden Empire       | 6        | 0.28%   |
| Elpida              | 6        | 0.28%   |
| Ramaxel Technology  | 5        | 0.24%   |
| GeIL                | 5        | 0.24%   |
| Wilk Elektronik     | 4        | 0.19%   |
| Transcend           | 4        | 0.19%   |
| Smart               | 4        | 0.19%   |
| Kingmax             | 4        | 0.19%   |
| Goldkey             | 4        | 0.19%   |
| Apacer              | 4        | 0.19%   |
| Silicon Power       | 3        | 0.14%   |
| A Force             | 3        | 0.14%   |
| Unknown (ABCD)      | 2        | 0.09%   |
| Unifosa             | 2        | 0.09%   |
| Thermaltake         | 2        | 0.09%   |
| Neo Forza           | 2        | 0.09%   |
| Kllisre             | 2        | 0.09%   |
| KLEVV               | 2        | 0.09%   |
| Hewlett-Packard     | 2        | 0.09%   |
| CSX                 | 2        | 0.09%   |
| Axiom               | 2        | 0.09%   |
| Wilk                | 1        | 0.05%   |
| Veineda             | 1        | 0.05%   |
| V-Color             | 1        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 60       | 2.59%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s    | 54       | 2.33%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s  | 32       | 1.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 25       | 1.08%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s  | 24       | 1.03%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 20       | 0.86%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3866MT/s   | 20       | 0.86%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s      | 19       | 0.82%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 18       | 0.78%   |
| Unknown                                                  | 15       | 0.65%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s    | 14       | 0.6%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 13       | 0.56%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 13       | 0.56%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s       | 13       | 0.56%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s       | 12       | 0.52%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 12       | 0.52%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s              | 12       | 0.52%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 11       | 0.47%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s    | 11       | 0.47%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s   | 11       | 0.47%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 10       | 0.43%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s       | 9        | 0.39%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s      | 9        | 0.39%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 9        | 0.39%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s   | 9        | 0.39%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1800MT/s   | 9        | 0.39%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s    | 9        | 0.39%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 8        | 0.34%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s      | 8        | 0.34%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s    | 8        | 0.34%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 8        | 0.34%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 8        | 0.34%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s     | 8        | 0.34%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 8        | 0.34%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s     | 7        | 0.3%    |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s      | 7        | 0.3%    |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3600MT/s | 7        | 0.3%    |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s    | 7        | 0.3%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 7        | 0.3%    |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s   | 7        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 1294     | 67.78%  |
| DDR3    | 435      | 22.79%  |
| Unknown | 63       | 3.3%    |
| DDR5    | 48       | 2.51%   |
| SDRAM   | 32       | 1.68%   |
| DDR2    | 21       | 1.1%    |
| DDR     | 12       | 0.63%   |
| LPDDR4  | 2        | 0.1%    |
| LPDDR3  | 1        | 0.05%   |
| DRAM    | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1836     | 96.84%  |
| SODIMM  | 57       | 3.01%   |
| RIMM    | 2        | 0.11%   |
| FB-DIMM | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 982      | 47.95%  |
| 16384 | 442      | 21.58%  |
| 4096  | 344      | 16.8%   |
| 32768 | 141      | 6.88%   |
| 2048  | 113      | 5.52%   |
| 1024  | 21       | 1.03%   |
| 512   | 5        | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 287      | 13.41%  |
| 3200    | 260      | 12.15%  |
| 1600    | 240      | 11.21%  |
| 2400    | 143      | 6.68%   |
| 1333    | 135      | 6.31%   |
| 2667    | 90       | 4.21%   |
| 2133    | 87       | 4.07%   |
| 3400    | 74       | 3.46%   |
| 3000    | 60       | 2.8%    |
| 3533    | 57       | 2.66%   |
| 3733    | 53       | 2.48%   |
| 3800    | 51       | 2.38%   |
| 1867    | 51       | 2.38%   |
| 2933    | 46       | 2.15%   |
| 1866    | 38       | 1.78%   |
| 2800    | 32       | 1.5%    |
| 3866    | 31       | 1.45%   |
| 2666    | 30       | 1.4%    |
| 3666    | 29       | 1.36%   |
| 3466    | 27       | 1.26%   |
| 1800    | 25       | 1.17%   |
| 800     | 20       | 0.93%   |
| 667     | 20       | 0.93%   |
| Unknown | 20       | 0.93%   |
| 3266    | 17       | 0.79%   |
| 1066    | 17       | 0.79%   |
| 4800    | 16       | 0.75%   |
| 3333    | 16       | 0.75%   |
| 4000    | 11       | 0.51%   |
| 6400    | 10       | 0.47%   |
| 3066    | 9        | 0.42%   |
| 2733    | 9        | 0.42%   |
| 6000    | 8        | 0.37%   |
| 3151    | 8        | 0.37%   |
| 3100    | 8        | 0.37%   |
| 400     | 8        | 0.37%   |
| 5200    | 7        | 0.33%   |
| 5600    | 5        | 0.23%   |
| 4133    | 5        | 0.23%   |
| 3534    | 5        | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 26       | 33.33%  |
| Brother Industries       | 16       | 20.51%  |
| Samsung Electronics      | 11       | 14.1%   |
| Canon                    | 11       | 14.1%   |
| Seiko Epson              | 2        | 2.56%   |
| Prolific Technology      | 2        | 2.56%   |
| Dymo-CoStar              | 2        | 2.56%   |
| Zebra                    | 1        | 1.28%   |
| STMicroelectronics       | 1        | 1.28%   |
| Ricoh                    | 1        | 1.28%   |
| QinHeng Electronics      | 1        | 1.28%   |
| Philips (or NXP)         | 1        | 1.28%   |
| Magic Control Technology | 1        | 1.28%   |
| Fuji Xerox               | 1        | 1.28%   |
| Dell                     | 1        | 1.28%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Samsung M2070 Series                                      | 3        | 3.85%   |
| Samsung SCX-4100 Scanner                                  | 2        | 2.56%   |
| Prolific PL2305 Parallel Port                             | 2        | 2.56%   |
| HP Officejet Pro 8100                                     | 2        | 2.56%   |
| HP LaserJet P2015 series                                  | 2        | 2.56%   |
| HP LaserJet 1018                                          | 2        | 2.56%   |
| HP LaserJet 1012                                          | 2        | 2.56%   |
| HP DeskJet F4200 series                                   | 2        | 2.56%   |
| HP Deskjet 3050 J610 series                               | 2        | 2.56%   |
| Dymo-CoStar LabelWriter 450                               | 2        | 2.56%   |
| Brother Printer                                           | 2        | 2.56%   |
| Brother HL-L2320D series                                  | 2        | 2.56%   |
| Brother HL-5370DW series                                  | 2        | 2.56%   |
| Brother DCP-1510                                          | 2        | 2.56%   |
| Zebra LP2844 Printer                                      | 1        | 1.28%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1.28%   |
| Seiko Epson XP-7100 Series                                | 1        | 1.28%   |
| Seiko Epson L3110 Series                                  | 1        | 1.28%   |
| Samsung SCX-4200 series                                   | 1        | 1.28%   |
| Samsung ML-216x Series Laser Printer                      | 1        | 1.28%   |
| Samsung ML-1610 Mono Laser Printer                        | 1        | 1.28%   |
| Samsung M267x 287x Series                                 | 1        | 1.28%   |
| Samsung CLP-325 Color Laser Printer                       | 1        | 1.28%   |
| Samsung C1860 Series                                      | 1        | 1.28%   |
| Ricoh SP 150SU                                            | 1        | 1.28%   |
| QinHeng CH340S                                            | 1        | 1.28%   |
| Philips (or NXP) USB Printer                              | 1        | 1.28%   |
| Magic Control BAY-3U1S1P Parallel Port                    | 1        | 1.28%   |
| HP PSC-1315/PSC-1317                                      | 1        | 1.28%   |
| HP Officejet 4500 G510g-m                                 | 1        | 1.28%   |
| HP LaserJet P1005                                         | 1        | 1.28%   |
| HP LaserJet M14-M17                                       | 1        | 1.28%   |
| HP LaserJet 2420                                          | 1        | 1.28%   |
| HP LaserJet 1200                                          | 1        | 1.28%   |
| HP LaserJet 1020                                          | 1        | 1.28%   |
| HP Ink Tank 310 series                                    | 1        | 1.28%   |
| HP ENVY Photo 6200 series                                 | 1        | 1.28%   |
| HP ENVY 5540 series                                       | 1        | 1.28%   |
| HP DeskJet 840c                                           | 1        | 1.28%   |
| HP DeskJet 2600 series                                    | 1        | 1.28%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 9        | 52.94%  |
| Seiko Epson    | 6        | 35.29%  |
| Mustek Systems | 2        | 11.76%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 2        | 11.76%  |
| Canon CanoScan N650U/N656U                                  | 2        | 11.76%  |
| Canon CanoScan LiDE 200                                     | 2        | 11.76%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1        | 5.88%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 1        | 5.88%   |
| Seiko Epson GT-F700 [Perfection V350]                       | 1        | 5.88%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1        | 5.88%   |
| Mustek Systems ScanExpress 1200 UB                          | 1        | 5.88%   |
| Mustek Systems BearPaw 1200 CU Plus                         | 1        | 5.88%   |
| Canon CanoScan LiDE 60                                      | 1        | 5.88%   |
| Canon CanoScan LiDE 220                                     | 1        | 5.88%   |
| Canon CanoScan LiDE 210                                     | 1        | 5.88%   |
| Canon CanoScan LiDE 120                                     | 1        | 5.88%   |
| Canon CanoScan LiDE 110                                     | 1        | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 311      | 47.63%  |
| Microsoft                     | 43       | 6.58%   |
| Microdia                      | 43       | 6.58%   |
| Samsung Electronics           | 25       | 3.83%   |
| Sunplus Innovation Technology | 18       | 2.76%   |
| Valve Software                | 16       | 2.45%   |
| Z-Star Microelectronics       | 15       | 2.3%    |
| MacroSilicon                  | 14       | 2.14%   |
| Razer USA                     | 11       | 1.68%   |
| KYE Systems (Mouse Systems)   | 10       | 1.53%   |
| ARC International             | 10       | 1.53%   |
| Apple                         | 10       | 1.53%   |
| Creative Technology           | 9        | 1.38%   |
| Realtek Semiconductor         | 8        | 1.23%   |
| Generalplus Technology        | 8        | 1.23%   |
| Lenovo                        | 7        | 1.07%   |
| Jieli Technology              | 7        | 1.07%   |
| Chicony Electronics           | 6        | 0.92%   |
| Huawei Technologies           | 5        | 0.77%   |
| Cubeternet                    | 5        | 0.77%   |
| Alcor Micro                   | 5        | 0.77%   |
| LG Electronics                | 4        | 0.61%   |
| Hewlett-Packard               | 4        | 0.61%   |
| Unknown                       | 3        | 0.46%   |
| Trust                         | 3        | 0.46%   |
| Sonix Technology              | 3        | 0.46%   |
| Aveo Technology               | 3        | 0.46%   |
| 2M UVC CAMERA                 | 3        | 0.46%   |
| WaveRider Communications      | 2        | 0.31%   |
| SunplusIT                     | 2        | 0.31%   |
| Sunplus IT                    | 2        | 0.31%   |
| SHENZHEN EMEET TECHNOLOGY     | 2        | 0.31%   |
| Quanta                        | 2        | 0.31%   |
| Pixart Imaging                | 2        | 0.31%   |
| Oculus VR                     | 2        | 0.31%   |
| Magic Control Technology      | 2        | 0.31%   |
| HTC (High Tech Computer)      | 2        | 0.31%   |
| Google                        | 2        | 0.31%   |
| Fifine K420                   | 2        | 0.31%   |
| AVerMedia Technologies        | 2        | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920               | 80       | 12.2%   |
| Logitech Webcam C270                      | 51       | 7.77%   |
| Samsung Galaxy series, misc. (MTP mode)   | 25       | 3.81%   |
| Logitech C922 Pro Stream Webcam           | 24       | 3.66%   |
| Logitech Webcam C310                      | 17       | 2.59%   |
| Logitech BRIO Ultra HD Webcam             | 17       | 2.59%   |
| Valve Software 3D Camera                  | 16       | 2.44%   |
| Logitech Webcam C930e                     | 15       | 2.29%   |
| Microsoft LifeCam HD-3000                 | 14       | 2.13%   |
| Logitech StreamCam                        | 14       | 2.13%   |
| Logitech HD Webcam C615                   | 14       | 2.13%   |
| Logitech HD Webcam C525                   | 14       | 2.13%   |
| MacroSilicon USB Video                    | 12       | 1.83%   |
| Microdia Webcam Vitade AF                 | 11       | 1.68%   |
| Logitech Webcam C170                      | 11       | 1.68%   |
| Microsoft LifeCam Cinema                  | 10       | 1.52%   |
| ARC International Camera                  | 10       | 1.52%   |
| Razer USA Gaming Webcam [Kiyo]            | 8        | 1.22%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 8        | 1.22%   |
| Logitech Webcam C925e                     | 7        | 1.07%   |
| Logitech HD Webcam C910                   | 7        | 1.07%   |
| KYE Systems (Mouse Systems) Genius Webcam | 7        | 1.07%   |
| Jieli USB PHY 2.0                         | 7        | 1.07%   |
| Z-Star Venus USB2.0 Camera                | 6        | 0.91%   |
| Microsoft Xbox NUI Camera                 | 6        | 0.91%   |
| Lenovo 500 RGB Camera                     | 6        | 0.91%   |
| Z-Star Full HD 1080P PC Camera            | 5        | 0.76%   |
| Sunplus papalook AF 925                   | 5        | 0.76%   |
| Sunplus HD 720P webcam                    | 5        | 0.76%   |
| Microdia USB 2.0 Camera                   | 5        | 0.76%   |
| Microdia Integrated Camera                | 5        | 0.76%   |
| Microdia GC02M2                           | 5        | 0.76%   |
| Microdia Camera                           | 5        | 0.76%   |
| Huawei HiCamera                           | 5        | 0.76%   |
| Generalplus CAMERA - UVC                  | 5        | 0.76%   |
| Realtek FULL HD 1080P Webcam              | 4        | 0.61%   |
| Logitech QuickCam Pro 9000                | 4        | 0.61%   |
| Logitech Logi Webcam C920e                | 4        | 0.61%   |
| Logitech B525 HD Webcam                   | 4        | 0.61%   |
| Creative Live! Cam Sync HD [VF0770]       | 4        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Microsoft                  | 4        | 30.77%  |
| Synaptics                  | 2        | 15.38%  |
| Shenzhen Goodix Technology | 2        | 15.38%  |
| Elan Microelectronics      | 2        | 15.38%  |
| STMicroelectronics         | 1        | 7.69%   |
| LighTuning Technology      | 1        | 7.69%   |
| AuthenTec                  | 1        | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Microsoft Fingerprint Reader                 | 4        | 30.77%  |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 2        | 15.38%  |
| Shenzhen Goodix  Fingerprint Device          | 2        | 15.38%  |
| Elan fingerprint sensor [FeinTech FPS00200]  | 2        | 15.38%  |
| STMicroelectronics Fingerprint Reader        | 1        | 7.69%   |
| LighTuning Fingerprint Sensor                | 1        | 7.69%   |
| AuthenTec Fingerprint Sensor                 | 1        | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Advanced Card Systems             | 6        | 17.65%  |
| Clay Logic                        | 5        | 14.71%  |
| Reiner SCT Kartensysteme          | 4        | 11.76%  |
| Gemalto (was Gemplus)             | 4        | 11.76%  |
| Yubico.com                        | 3        | 8.82%   |
| OmniKey                           | 2        | 5.88%   |
| Alcor Micro                       | 2        | 5.88%   |
| Aladdin Knowledge Systems         | 2        | 5.88%   |
| VASCO Data Security International | 1        | 2.94%   |
| SCM Microsystems                  | 1        | 2.94%   |
| Fujitsu Siemens Computers         | 1        | 2.94%   |
| C3PO                              | 1        | 2.94%   |
| Aladdin R.D.                      | 1        | 2.94%   |
| Aktiv                             | 1        | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 3        | 8.82%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 8.82%   |
| Clay Logic Nitrokey Pro                                                    | 3        | 8.82%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 3        | 8.82%   |
| Reiner SCT Kartensysteme cyberJack one                                     | 2        | 5.88%   |
| Aladdin Knowledge Systems Token JC                                         | 2        | 5.88%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 1        | 2.94%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 1        | 2.94%   |
| Reiner SCT Kartensysteme tanJack USB                                       | 1        | 2.94%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.94%   |
| OmniKey Smart Card Reader USB                                              | 1        | 2.94%   |
| OmniKey 5022 Smart Card Reader                                             | 1        | 2.94%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 2.94%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                          | 1        | 2.94%   |
| Clay Logic Nitrokey Start                                                  | 1        | 2.94%   |
| Clay Logic Nitrokey HSM                                                    | 1        | 2.94%   |
| C3PO LTC31v2                                                               | 1        | 2.94%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 2.94%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 2.94%   |
| Aladdin R.D. JaCarta                                                       | 1        | 2.94%   |
| Aktiv Rutoken lite                                                         | 1        | 2.94%   |
| Advanced Card Systems ACR39U                                               | 1        | 2.94%   |
| Advanced Card Systems ACR1252 Dual Reader                                  | 1        | 2.94%   |
| Advanced Card Systems ACR122U                                              | 1        | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2307     | 86.5%   |
| 1     | 311      | 11.66%  |
| 2     | 38       | 1.42%   |
| 3     | 7        | 0.26%   |
| 6     | 2        | 0.07%   |
| 4     | 2        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 102      | 25.69%  |
| Net/wireless             | 95       | 23.93%  |
| Unassigned class         | 50       | 12.59%  |
| Camera                   | 22       | 5.54%   |
| Sound                    | 21       | 5.29%   |
| Communication controller | 19       | 4.79%   |
| Chipcard                 | 18       | 4.53%   |
| Bluetooth                | 16       | 4.03%   |
| Multimedia controller    | 13       | 3.27%   |
| Fingerprint reader       | 11       | 2.77%   |
| Network                  | 8        | 2.02%   |
| Net/ethernet             | 7        | 1.76%   |
| Modem                    | 4        | 1.01%   |
| Dvb card                 | 4        | 1.01%   |
| Storage/raid             | 2        | 0.5%    |
| Storage/ide              | 2        | 0.5%    |
| Tv card                  | 1        | 0.25%   |
| Storage/nvme             | 1        | 0.25%   |
| Storage                  | 1        | 0.25%   |

