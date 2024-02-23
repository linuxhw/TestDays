Fedora - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 8090

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | X670E Pro RS                | [fd02477c14](https://linux-hardware.org/?probe=fd02477c14) | Feb 02, 2024 |
| HP            | 83E9                        | [a140a989be](https://linux-hardware.org/?probe=a140a989be) | Feb 02, 2024 |
| ASUSTek       | SABERTOOTH Z77              | [75c314c9bb](https://linux-hardware.org/?probe=75c314c9bb) | Feb 02, 2024 |
| ASUSTek       | H110M-R                     | [2902d23de2](https://linux-hardware.org/?probe=2902d23de2) | Feb 02, 2024 |
| Pegatron      | IPM41-D3                    | [5884d40085](https://linux-hardware.org/?probe=5884d40085) | Feb 02, 2024 |
| MSI           | X99A RAIDER                 | [158530e4dc](https://linux-hardware.org/?probe=158530e4dc) | Feb 02, 2024 |
| ASRock        | A320M-ITX                   | [7c3ebbb23c](https://linux-hardware.org/?probe=7c3ebbb23c) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [654e691a5d](https://linux-hardware.org/?probe=654e691a5d) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [279e68de12](https://linux-hardware.org/?probe=279e68de12) | Feb 02, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [e8554aab57](https://linux-hardware.org/?probe=e8554aab57) | Feb 02, 2024 |
| ASRock        | B560M-ITX/ac                | [9ed6c67efe](https://linux-hardware.org/?probe=9ed6c67efe) | Feb 02, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [73e32179ef](https://linux-hardware.org/?probe=73e32179ef) | Feb 02, 2024 |
| ASUSTek       | PRIME B560M-K               | [007e574396](https://linux-hardware.org/?probe=007e574396) | Feb 01, 2024 |
| ASUSTek       | PRIME B560M-K               | [9d4315d3e3](https://linux-hardware.org/?probe=9d4315d3e3) | Feb 01, 2024 |
| Pegatron      | IPM41-D3                    | [7969244295](https://linux-hardware.org/?probe=7969244295) | Feb 01, 2024 |
| HP            | 870C                        | [14801c4f80](https://linux-hardware.org/?probe=14801c4f80) | Feb 01, 2024 |
| Gigabyte      | G41MT-D3                    | [88c563b03e](https://linux-hardware.org/?probe=88c563b03e) | Feb 01, 2024 |
| MSI           | X99A RAIDER                 | [3953592045](https://linux-hardware.org/?probe=3953592045) | Feb 01, 2024 |
| Unknown       | Unknown                     | [66102cc055](https://linux-hardware.org/?probe=66102cc055) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [0b234564e9](https://linux-hardware.org/?probe=0b234564e9) | Jan 31, 2024 |
| MSI           | X99A RAIDER                 | [ffaf5dab37](https://linux-hardware.org/?probe=ffaf5dab37) | Jan 31, 2024 |
| ASUSTek       | M4N68T-M LE                 | [31e2d90ef4](https://linux-hardware.org/?probe=31e2d90ef4) | Jan 31, 2024 |
| Dell          | 00V62H A01                  | [4a42c319b4](https://linux-hardware.org/?probe=4a42c319b4) | Jan 30, 2024 |
| MSI           | AMETHYST-M                  | [865d868008](https://linux-hardware.org/?probe=865d868008) | Jan 30, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [fac7cfcfce](https://linux-hardware.org/?probe=fac7cfcfce) | Jan 30, 2024 |
| MSI           | AMETHYST-M                  | [da16f0848e](https://linux-hardware.org/?probe=da16f0848e) | Jan 30, 2024 |
| ASRock        | B550 Phantom Gaming 4       | [9d98a77586](https://linux-hardware.org/?probe=9d98a77586) | Jan 30, 2024 |
| ASUSTek       | X99-DELUXE                  | [482b1946f4](https://linux-hardware.org/?probe=482b1946f4) | Jan 30, 2024 |
| ASRock        | B550 Pro4                   | [9617266ebe](https://linux-hardware.org/?probe=9617266ebe) | Jan 30, 2024 |
| ASUSTek       | PRIME B450M-A II            | [abdcd1a804](https://linux-hardware.org/?probe=abdcd1a804) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0a68bb3157](https://linux-hardware.org/?probe=0a68bb3157) | Jan 30, 2024 |
| Dell          | 0U880P A01                  | [d3d4142e1e](https://linux-hardware.org/?probe=d3d4142e1e) | Jan 30, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | [193e9e6c74](https://linux-hardware.org/?probe=193e9e6c74) | Jan 30, 2024 |
| ASRock        | B450M Pro4                  | [c0f87d75df](https://linux-hardware.org/?probe=c0f87d75df) | Jan 29, 2024 |
| MSI           | Z490M-S01                   | [ed7f213619](https://linux-hardware.org/?probe=ed7f213619) | Jan 29, 2024 |
| ASRock        | B650M Pro RS WiFi           | [b2a4068ec1](https://linux-hardware.org/?probe=b2a4068ec1) | Jan 29, 2024 |
| ASRock        | A320M-HD                    | [5c0864b392](https://linux-hardware.org/?probe=5c0864b392) | Jan 29, 2024 |
| MSI           | MAG B550M BAZOOKA           | [c0d98503dd](https://linux-hardware.org/?probe=c0d98503dd) | Jan 29, 2024 |
| Gigabyte      | B550 GAMING X V2            | [99e90d2b89](https://linux-hardware.org/?probe=99e90d2b89) | Jan 29, 2024 |
| Intel         | DB75EN AAG39650-302         | [dcc6332a8e](https://linux-hardware.org/?probe=dcc6332a8e) | Jan 29, 2024 |
| MSI           | Z790 GAMING PRO WIFI        | [3e946efe3c](https://linux-hardware.org/?probe=3e946efe3c) | Jan 29, 2024 |
| Huanan        | X99-QD4 V1.0                | [2194293ede](https://linux-hardware.org/?probe=2194293ede) | Jan 28, 2024 |
| MSI           | 880GMS-E35                  | [0216fb4b4f](https://linux-hardware.org/?probe=0216fb4b4f) | Jan 28, 2024 |
| Gigabyte      | AX370-Gaming 5              | [c3f740ce88](https://linux-hardware.org/?probe=c3f740ce88) | Jan 28, 2024 |
| MSI           | H81M-E34                    | [9aec3e7a36](https://linux-hardware.org/?probe=9aec3e7a36) | Jan 28, 2024 |
| ASUSTek       | PRIME B550M-A AC            | [35b6b0dd05](https://linux-hardware.org/?probe=35b6b0dd05) | Jan 28, 2024 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [cfc0d0a745](https://linux-hardware.org/?probe=cfc0d0a745) | Jan 28, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [59ce08f802](https://linux-hardware.org/?probe=59ce08f802) | Jan 28, 2024 |
| MSI           | X470 GAMING PLUS            | [a896c739ca](https://linux-hardware.org/?probe=a896c739ca) | Jan 28, 2024 |
| Gigabyte      | B650 GAMING X AX            | [f728617f20](https://linux-hardware.org/?probe=f728617f20) | Jan 28, 2024 |
| ASUSTek       | PRIME B450M-A II            | [1d4239bc71](https://linux-hardware.org/?probe=1d4239bc71) | Jan 27, 2024 |
| ASUSTek       | PRIME X370-A                | [e3c045bb8c](https://linux-hardware.org/?probe=e3c045bb8c) | Jan 27, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [26c552f089](https://linux-hardware.org/?probe=26c552f089) | Jan 27, 2024 |
| Gigabyte      | Z77MX-D3H                   | [618155f762](https://linux-hardware.org/?probe=618155f762) | Jan 27, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [9d4827b4a5](https://linux-hardware.org/?probe=9d4827b4a5) | Jan 27, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [57f2a52748](https://linux-hardware.org/?probe=57f2a52748) | Jan 27, 2024 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [85fd42ad4d](https://linux-hardware.org/?probe=85fd42ad4d) | Jan 27, 2024 |
| Gigabyte      | TRX40 AORUS XTREME          | [cdf9d5dadb](https://linux-hardware.org/?probe=cdf9d5dadb) | Jan 27, 2024 |
| Gigabyte      | G41MT-D3                    | [327217e107](https://linux-hardware.org/?probe=327217e107) | Jan 27, 2024 |
| MSI           | MEG Z690I UNIFY             | [42f4602ff3](https://linux-hardware.org/?probe=42f4602ff3) | Jan 27, 2024 |
| ASUSTek       | PRIME X670-P                | [1d4943457c](https://linux-hardware.org/?probe=1d4943457c) | Jan 26, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [8ac63955c7](https://linux-hardware.org/?probe=8ac63955c7) | Jan 26, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [9b55015259](https://linux-hardware.org/?probe=9b55015259) | Jan 26, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [3cecdef02f](https://linux-hardware.org/?probe=3cecdef02f) | Jan 26, 2024 |
| HP            | 843B                        | [9a021639c5](https://linux-hardware.org/?probe=9a021639c5) | Jan 26, 2024 |
| ASUSTek       | PRIME X670-P                | [75379edae7](https://linux-hardware.org/?probe=75379edae7) | Jan 26, 2024 |
| ASUSTek       | A8R32-MVP Deluxe            | [f59710809d](https://linux-hardware.org/?probe=f59710809d) | Jan 26, 2024 |
| MSI           | H81M-E34                    | [c53fb2b81b](https://linux-hardware.org/?probe=c53fb2b81b) | Jan 25, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [813ed73797](https://linux-hardware.org/?probe=813ed73797) | Jan 25, 2024 |
| ASUSTek       | Z97-P                       | [0803e06982](https://linux-hardware.org/?probe=0803e06982) | Jan 25, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [ac31169eb1](https://linux-hardware.org/?probe=ac31169eb1) | Jan 25, 2024 |
| ASUSTek       | H110M-D                     | [7f2b907eb8](https://linux-hardware.org/?probe=7f2b907eb8) | Jan 25, 2024 |
| MSI           | B450M BAZOOKA V2            | [3f0ed24a76](https://linux-hardware.org/?probe=3f0ed24a76) | Jan 25, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [869af9b5c0](https://linux-hardware.org/?probe=869af9b5c0) | Jan 25, 2024 |
| ASUSTek       | G20AJ                       | [4dd87f5aeb](https://linux-hardware.org/?probe=4dd87f5aeb) | Jan 24, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | [0786b58816](https://linux-hardware.org/?probe=0786b58816) | Jan 24, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [f38d7bb62a](https://linux-hardware.org/?probe=f38d7bb62a) | Jan 24, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [9bf161df69](https://linux-hardware.org/?probe=9bf161df69) | Jan 24, 2024 |
| MSI           | FM2-A75MA-E35               | [78cddbe37f](https://linux-hardware.org/?probe=78cddbe37f) | Jan 24, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8d6b0dcab0](https://linux-hardware.org/?probe=8d6b0dcab0) | Jan 24, 2024 |
| ASRock        | Z690-C/D5                   | [534911d3a7](https://linux-hardware.org/?probe=534911d3a7) | Jan 24, 2024 |
| ASRock        | B660-ITX                    | [c82f95d7de](https://linux-hardware.org/?probe=c82f95d7de) | Jan 24, 2024 |
| MSI           | MPG B650I EDGE WIFI         | [9e5edb123e](https://linux-hardware.org/?probe=9e5edb123e) | Jan 24, 2024 |
| Gigabyte      | H61M-S2V-B3                 | [74874054dd](https://linux-hardware.org/?probe=74874054dd) | Jan 24, 2024 |
| Gigabyte      | H110M-S2H-CF                | [81f34fc65a](https://linux-hardware.org/?probe=81f34fc65a) | Jan 23, 2024 |
| Dell          | 0KN5W4 A03                  | [4665315883](https://linux-hardware.org/?probe=4665315883) | Jan 23, 2024 |
| ASUSTek       | SABERTOOTH Z77              | [013bd103c2](https://linux-hardware.org/?probe=013bd103c2) | Jan 23, 2024 |
| ASUSTek       | SABERTOOTH Z77              | [ff02cafda6](https://linux-hardware.org/?probe=ff02cafda6) | Jan 23, 2024 |
| ASUSTek       | P5Q SE2                     | [06fae6b7bf](https://linux-hardware.org/?probe=06fae6b7bf) | Jan 23, 2024 |
| Dell          | 0HHV7N A00                  | [38b1e0aa62](https://linux-hardware.org/?probe=38b1e0aa62) | Jan 23, 2024 |
| MSI           | PRO B660M-E DDR4            | [7357312922](https://linux-hardware.org/?probe=7357312922) | Jan 23, 2024 |
| Lenovo        | MAHOBAY NO DPK              | [1eeda8c8f1](https://linux-hardware.org/?probe=1eeda8c8f1) | Jan 23, 2024 |
| Lenovo        | ThinkCentre M90p 5536AN5    | [8305fcdce9](https://linux-hardware.org/?probe=8305fcdce9) | Jan 23, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | [9f48506578](https://linux-hardware.org/?probe=9f48506578) | Jan 23, 2024 |
| ASUSTek       | P5Q PRO TURBO               | [93762ed6a5](https://linux-hardware.org/?probe=93762ed6a5) | Jan 22, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6dbdc40268](https://linux-hardware.org/?probe=6dbdc40268) | Jan 22, 2024 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [2c38517137](https://linux-hardware.org/?probe=2c38517137) | Jan 22, 2024 |
| Biostar       | A68MHE                      | [bd1cb81b9d](https://linux-hardware.org/?probe=bd1cb81b9d) | Jan 22, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [bc06fb13b6](https://linux-hardware.org/?probe=bc06fb13b6) | Jan 22, 2024 |
| ASUSTek       | P7P55D                      | [8d8fab9b27](https://linux-hardware.org/?probe=8d8fab9b27) | Jan 21, 2024 |
| MSI           | X370 SLI PLUS               | [c4729b1c7c](https://linux-hardware.org/?probe=c4729b1c7c) | Jan 21, 2024 |
| ASUSTek       | M5A97 R2.0                  | [de6fb94ac8](https://linux-hardware.org/?probe=de6fb94ac8) | Jan 21, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | [d67daf2078](https://linux-hardware.org/?probe=d67daf2078) | Jan 21, 2024 |
| HP            | 8618                        | [d1bd70f41d](https://linux-hardware.org/?probe=d1bd70f41d) | Jan 21, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [f313b1c112](https://linux-hardware.org/?probe=f313b1c112) | Jan 21, 2024 |
| Dell          | 0HHV7N A00                  | [d6aeeb6ece](https://linux-hardware.org/?probe=d6aeeb6ece) | Jan 21, 2024 |
| Pegatron      | 2AB6                        | [57a1fef3f7](https://linux-hardware.org/?probe=57a1fef3f7) | Jan 21, 2024 |
| ASUSTek       | PRIME B550M-A               | [7069f9af65](https://linux-hardware.org/?probe=7069f9af65) | Jan 21, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [fbc836a9ff](https://linux-hardware.org/?probe=fbc836a9ff) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5c9deadb93](https://linux-hardware.org/?probe=5c9deadb93) | Jan 20, 2024 |
| MSI           | Z790 GAMING PRO WIFI        | [bdcd287661](https://linux-hardware.org/?probe=bdcd287661) | Jan 20, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [a535d51ede](https://linux-hardware.org/?probe=a535d51ede) | Jan 20, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [1db270091f](https://linux-hardware.org/?probe=1db270091f) | Jan 20, 2024 |
| MSI           | MS-7388                     | [e151be731a](https://linux-hardware.org/?probe=e151be731a) | Jan 20, 2024 |
| Dell          | 04Y8V0 A02                  | [c7ac75fb19](https://linux-hardware.org/?probe=c7ac75fb19) | Jan 20, 2024 |
| HP            | 8A96 11                     | [8b913e22cd](https://linux-hardware.org/?probe=8b913e22cd) | Jan 20, 2024 |
| HP            | 8A96 11                     | [3fa20439d9](https://linux-hardware.org/?probe=3fa20439d9) | Jan 20, 2024 |
| Gigabyte      | GA-870A-UD3                 | [7c13b83bff](https://linux-hardware.org/?probe=7c13b83bff) | Jan 20, 2024 |
| ASRock        | B760M PG SONIC WiFi         | [987717796a](https://linux-hardware.org/?probe=987717796a) | Jan 20, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [a27ea5cca3](https://linux-hardware.org/?probe=a27ea5cca3) | Jan 20, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | [5ab5b74cfa](https://linux-hardware.org/?probe=5ab5b74cfa) | Jan 20, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d166663637](https://linux-hardware.org/?probe=d166663637) | Jan 19, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [97f56eac35](https://linux-hardware.org/?probe=97f56eac35) | Jan 19, 2024 |
| MSI           | MPG X670E CARBON WIFI       | [0eb94b3491](https://linux-hardware.org/?probe=0eb94b3491) | Jan 19, 2024 |
| MSI           | MPG X670E CARBON WIFI       | [b6dfff4b78](https://linux-hardware.org/?probe=b6dfff4b78) | Jan 19, 2024 |
| Foxconn       | 2ABF                        | [9a5efc4dd3](https://linux-hardware.org/?probe=9a5efc4dd3) | Jan 19, 2024 |
| MSI           | MPG B650I EDGE WIFI         | [ba941d7a4e](https://linux-hardware.org/?probe=ba941d7a4e) | Jan 19, 2024 |
| Gigabyte      | EP45-DS3L                   | [c3a9225062](https://linux-hardware.org/?probe=c3a9225062) | Jan 19, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [008c387c2b](https://linux-hardware.org/?probe=008c387c2b) | Jan 19, 2024 |
| Gigabyte      | GA-MA780G-UD3H              | [9e1182e93f](https://linux-hardware.org/?probe=9e1182e93f) | Jan 19, 2024 |
| ASUSTek       | CG8480                      | [4610686acc](https://linux-hardware.org/?probe=4610686acc) | Jan 19, 2024 |
| Pegatron      | 2AB6                        | [9a9b3ef258](https://linux-hardware.org/?probe=9a9b3ef258) | Jan 19, 2024 |
| MSI           | MS-B9181                    | [503f0edf6a](https://linux-hardware.org/?probe=503f0edf6a) | Jan 19, 2024 |
| ASRock        | X370 Pro4                   | [9dfd5fe2cb](https://linux-hardware.org/?probe=9dfd5fe2cb) | Jan 19, 2024 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [89d65b315c](https://linux-hardware.org/?probe=89d65b315c) | Jan 19, 2024 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [27b2376cad](https://linux-hardware.org/?probe=27b2376cad) | Jan 18, 2024 |
| MSI           | MEG X570 UNIFY              | [01d5509c12](https://linux-hardware.org/?probe=01d5509c12) | Jan 18, 2024 |
| ASRock        | H310M-STX                   | [8e7c70643c](https://linux-hardware.org/?probe=8e7c70643c) | Jan 18, 2024 |
| Dell          | 0KN5W4 A03                  | [64f7b3272e](https://linux-hardware.org/?probe=64f7b3272e) | Jan 18, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | [16f764cb39](https://linux-hardware.org/?probe=16f764cb39) | Jan 18, 2024 |
| ASUSTek       | PRIME B360-PLUS             | [7f55ddb513](https://linux-hardware.org/?probe=7f55ddb513) | Jan 18, 2024 |
| Gigabyte      | B85-HD3                     | [66b0dbb818](https://linux-hardware.org/?probe=66b0dbb818) | Jan 18, 2024 |
| HP            | 3048h                       | [e24f1cffa1](https://linux-hardware.org/?probe=e24f1cffa1) | Jan 18, 2024 |
| HP            | 2B0F                        | [ce5907f486](https://linux-hardware.org/?probe=ce5907f486) | Jan 18, 2024 |
| ASRock        | AD2700-ITX                  | [93eee675be](https://linux-hardware.org/?probe=93eee675be) | Jan 18, 2024 |
| Gigabyte      | J1900M-D2P                  | [3c5d80f1e7](https://linux-hardware.org/?probe=3c5d80f1e7) | Jan 18, 2024 |
| ASUSTek       | P8Z77-V                     | [cc154717f4](https://linux-hardware.org/?probe=cc154717f4) | Jan 18, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [04707ec04e](https://linux-hardware.org/?probe=04707ec04e) | Jan 17, 2024 |
| Lenovo        | ThinkServer TS140           | [8ccec416bf](https://linux-hardware.org/?probe=8ccec416bf) | Jan 17, 2024 |
| Gigabyte      | F2A55M-DS2                  | [972e4192b6](https://linux-hardware.org/?probe=972e4192b6) | Jan 17, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [842faed623](https://linux-hardware.org/?probe=842faed623) | Jan 17, 2024 |
| Lenovo        | ThinkCentre M58p 7220A72    | [9d8436f707](https://linux-hardware.org/?probe=9d8436f707) | Jan 17, 2024 |
| ASRock        | X670E Pro RS                | [08a25334a9](https://linux-hardware.org/?probe=08a25334a9) | Jan 16, 2024 |
| ASUSTek       | Leonite2                    | [70605195c6](https://linux-hardware.org/?probe=70605195c6) | Jan 16, 2024 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [6b8df5e5f8](https://linux-hardware.org/?probe=6b8df5e5f8) | Jan 16, 2024 |
| HP            | 802F                        | [891f0c3076](https://linux-hardware.org/?probe=891f0c3076) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [ad209d60d3](https://linux-hardware.org/?probe=ad209d60d3) | Jan 15, 2024 |
| ECS           | H61H2-MV                    | [09c20c7740](https://linux-hardware.org/?probe=09c20c7740) | Jan 15, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3d6f9a4f65](https://linux-hardware.org/?probe=3d6f9a4f65) | Jan 15, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [b81d575e86](https://linux-hardware.org/?probe=b81d575e86) | Jan 15, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [2be91db1f9](https://linux-hardware.org/?probe=2be91db1f9) | Jan 15, 2024 |
| MSI           | PRO H610M-G DDR4            | [9dc779fa6c](https://linux-hardware.org/?probe=9dc779fa6c) | Jan 15, 2024 |
| ASUSTek       | Z97M-PLUS                   | [6565fd5500](https://linux-hardware.org/?probe=6565fd5500) | Jan 15, 2024 |
| MSI           | Z370-OC PRO                 | [4ffb04a6df](https://linux-hardware.org/?probe=4ffb04a6df) | Jan 15, 2024 |
| Dell          | 00V62H A01                  | [77fa76ca79](https://linux-hardware.org/?probe=77fa76ca79) | Jan 15, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [29d93a66fe](https://linux-hardware.org/?probe=29d93a66fe) | Jan 15, 2024 |
| ASUSTek       | Leonite2                    | [a4f9390786](https://linux-hardware.org/?probe=a4f9390786) | Jan 15, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5ba2479207](https://linux-hardware.org/?probe=5ba2479207) | Jan 15, 2024 |
| Dell          | 0GM819                      | [b55d9b9a52](https://linux-hardware.org/?probe=b55d9b9a52) | Jan 14, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c4edc08fb7](https://linux-hardware.org/?probe=c4edc08fb7) | Jan 14, 2024 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [721d114c58](https://linux-hardware.org/?probe=721d114c58) | Jan 14, 2024 |
| ASRock        | B560M-ITX/ac                | [0ab95fc3f5](https://linux-hardware.org/?probe=0ab95fc3f5) | Jan 14, 2024 |
| MSI           | A320M-A PRO                 | [0c48e7148e](https://linux-hardware.org/?probe=0c48e7148e) | Jan 14, 2024 |
| MSI           | B450M BAZOOKA V2            | [016db84158](https://linux-hardware.org/?probe=016db84158) | Jan 14, 2024 |
| AMI           | Intel                       | [8cea24270b](https://linux-hardware.org/?probe=8cea24270b) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [90337c194c](https://linux-hardware.org/?probe=90337c194c) | Jan 14, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [6443f8b7e5](https://linux-hardware.org/?probe=6443f8b7e5) | Jan 13, 2024 |
| ASUSTek       | P8Z77-V LX                  | [6be6b20963](https://linux-hardware.org/?probe=6be6b20963) | Jan 13, 2024 |
| ASUSTek       | P8Z77-V LX                  | [dba611325e](https://linux-hardware.org/?probe=dba611325e) | Jan 13, 2024 |
| ASUSTek       | PRIME B660M-A D4            | [cd57f74a31](https://linux-hardware.org/?probe=cd57f74a31) | Jan 13, 2024 |
| MSI           | H310M PRO-VH PLUS           | [7b76b0de4f](https://linux-hardware.org/?probe=7b76b0de4f) | Jan 13, 2024 |
| Gigabyte      | Z590 UD AC                  | [17dc5fdc19](https://linux-hardware.org/?probe=17dc5fdc19) | Jan 13, 2024 |
| MSI           | GF615M-P33                  | [7d32db9104](https://linux-hardware.org/?probe=7d32db9104) | Jan 12, 2024 |
| MSI           | H77MA-G43                   | [51882b379d](https://linux-hardware.org/?probe=51882b379d) | Jan 12, 2024 |
| Apple         | Mac-F221BEC8                | [79039b79e4](https://linux-hardware.org/?probe=79039b79e4) | Jan 12, 2024 |
| ASRock        | X670E Pro RS                | [2f899514f8](https://linux-hardware.org/?probe=2f899514f8) | Jan 12, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [b47717df63](https://linux-hardware.org/?probe=b47717df63) | Jan 12, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [c8b80fe147](https://linux-hardware.org/?probe=c8b80fe147) | Jan 12, 2024 |
| ASRock        | Z370 IB-R                   | [60d0873a83](https://linux-hardware.org/?probe=60d0873a83) | Jan 11, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6f2ff7e922](https://linux-hardware.org/?probe=6f2ff7e922) | Jan 11, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [537c95bdae](https://linux-hardware.org/?probe=537c95bdae) | Jan 11, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [2e480c8e36](https://linux-hardware.org/?probe=2e480c8e36) | Jan 11, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [0b4b01f1aa](https://linux-hardware.org/?probe=0b4b01f1aa) | Jan 11, 2024 |
| ASUSTek       | PRIME B450M-A               | [4bfba10e3f](https://linux-hardware.org/?probe=4bfba10e3f) | Jan 11, 2024 |
| ASUSTek       | H81M-A/BR                   | [9d4a2ac12b](https://linux-hardware.org/?probe=9d4a2ac12b) | Jan 11, 2024 |
| HP            | 8459                        | [1d15c6aed7](https://linux-hardware.org/?probe=1d15c6aed7) | Jan 10, 2024 |
| ASRock        | B550 PG Riptide             | [5221601add](https://linux-hardware.org/?probe=5221601add) | Jan 10, 2024 |
| HP            | 8618                        | [0abc5ffc81](https://linux-hardware.org/?probe=0abc5ffc81) | Jan 10, 2024 |
| MSI           | H310M PRO-VH PLUS           | [8431e0e3d7](https://linux-hardware.org/?probe=8431e0e3d7) | Jan 10, 2024 |
| ASUSTek       | PRIME X570-P                | [4b2d921c9b](https://linux-hardware.org/?probe=4b2d921c9b) | Jan 10, 2024 |
| Dell          | OptiPlex 5050               | [ad6a14b4dc](https://linux-hardware.org/?probe=ad6a14b4dc) | Jan 10, 2024 |
| Gigabyte      | J1900M-D2P                  | [b48b4a8698](https://linux-hardware.org/?probe=b48b4a8698) | Jan 10, 2024 |
| Dell          | 0XC7MM A01                  | [d2cc3e306e](https://linux-hardware.org/?probe=d2cc3e306e) | Jan 10, 2024 |
| MSI           | PRO B650M-A WIFI            | [245ccd0eb9](https://linux-hardware.org/?probe=245ccd0eb9) | Jan 09, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [8a25bf8215](https://linux-hardware.org/?probe=8a25bf8215) | Jan 09, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | [ad3bd18e36](https://linux-hardware.org/?probe=ad3bd18e36) | Jan 09, 2024 |
| Shenzhen M... | F7BRC                       | [f40f768b40](https://linux-hardware.org/?probe=f40f768b40) | Jan 09, 2024 |
| Intel         | B75                         | [cc1767546e](https://linux-hardware.org/?probe=cc1767546e) | Jan 09, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [c832a7e8f5](https://linux-hardware.org/?probe=c832a7e8f5) | Jan 08, 2024 |
| Gigabyte      | A320M-S2H-CF                | [88c9ecb793](https://linux-hardware.org/?probe=88c9ecb793) | Jan 08, 2024 |
| ASUSTek       | PRIME B550M-A               | [9f2c754db2](https://linux-hardware.org/?probe=9f2c754db2) | Jan 08, 2024 |
| ASUSTek       | H81M-E                      | [4fc71cdf2e](https://linux-hardware.org/?probe=4fc71cdf2e) | Jan 08, 2024 |
| HP            | 8906 SMVB                   | [fd4b6e8840](https://linux-hardware.org/?probe=fd4b6e8840) | Jan 08, 2024 |
| ASUSTek       | X99-DELUXE II               | [8362692262](https://linux-hardware.org/?probe=8362692262) | Jan 08, 2024 |
| GEEKOM        | A5                          | [a46bf9499e](https://linux-hardware.org/?probe=a46bf9499e) | Jan 07, 2024 |
| Biostar       | A68MHE                      | [ed7007dc1f](https://linux-hardware.org/?probe=ed7007dc1f) | Jan 07, 2024 |
| Gigabyte      | B650 GAMING X               | [33c147e1f3](https://linux-hardware.org/?probe=33c147e1f3) | Jan 07, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [46a12dff06](https://linux-hardware.org/?probe=46a12dff06) | Jan 07, 2024 |
| MSI           | A320M PRO-VH PLUS           | [3ff7f414fe](https://linux-hardware.org/?probe=3ff7f414fe) | Jan 07, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [96907e78c1](https://linux-hardware.org/?probe=96907e78c1) | Jan 07, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [d7bd0a9659](https://linux-hardware.org/?probe=d7bd0a9659) | Jan 07, 2024 |
| MSI           | H81M-E33                    | [cced2d2e95](https://linux-hardware.org/?probe=cced2d2e95) | Jan 07, 2024 |
| MSI           | B460M PRO-VDH WIFI          | [a642b9a382](https://linux-hardware.org/?probe=a642b9a382) | Jan 07, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [c1203b6f85](https://linux-hardware.org/?probe=c1203b6f85) | Jan 06, 2024 |
| ASUSTek       | H81M-PLUS                   | [1dd10b5144](https://linux-hardware.org/?probe=1dd10b5144) | Jan 06, 2024 |
| AMD           | A520                        | [844129c6ba](https://linux-hardware.org/?probe=844129c6ba) | Jan 06, 2024 |
| Intel         | B75                         | [b2190f0cff](https://linux-hardware.org/?probe=b2190f0cff) | Jan 06, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [41582699c7](https://linux-hardware.org/?probe=41582699c7) | Jan 06, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | [dda07da31a](https://linux-hardware.org/?probe=dda07da31a) | Jan 06, 2024 |
| ASRock        | B550M PG Riptide            | [681b82b48a](https://linux-hardware.org/?probe=681b82b48a) | Jan 06, 2024 |
| ASRock        | B550M PG Riptide            | [bbbedbf6f4](https://linux-hardware.org/?probe=bbbedbf6f4) | Jan 06, 2024 |
| Gigabyte      | GA-870A-UD3                 | [d273ae013f](https://linux-hardware.org/?probe=d273ae013f) | Jan 06, 2024 |
| AMD           | A520                        | [ab02db5a08](https://linux-hardware.org/?probe=ab02db5a08) | Jan 06, 2024 |
| Gigabyte      | G41MT-D3                    | [a78a3d75b9](https://linux-hardware.org/?probe=a78a3d75b9) | Jan 06, 2024 |
| Foxconn       | 2ABF                        | [d7443c3161](https://linux-hardware.org/?probe=d7443c3161) | Jan 05, 2024 |
| Foxconn       | 2ABF                        | [83a9bffcf5](https://linux-hardware.org/?probe=83a9bffcf5) | Jan 05, 2024 |
| HP            | 1589                        | [662d0bf8cd](https://linux-hardware.org/?probe=662d0bf8cd) | Jan 05, 2024 |
| ASUSTek       | M3A79-T DELUXE              | [fae924a6fc](https://linux-hardware.org/?probe=fae924a6fc) | Jan 05, 2024 |
| HP            | 8055                        | [ee3ece9007](https://linux-hardware.org/?probe=ee3ece9007) | Jan 05, 2024 |
| MSI           | MS-7142                     | [f2d4db6983](https://linux-hardware.org/?probe=f2d4db6983) | Jan 05, 2024 |
| Dell          | 00V62H A01                  | [22aa170ce4](https://linux-hardware.org/?probe=22aa170ce4) | Jan 05, 2024 |
| HP            | 89B4 A                      | [44908d808d](https://linux-hardware.org/?probe=44908d808d) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [bda6010293](https://linux-hardware.org/?probe=bda6010293) | Jan 04, 2024 |
| MSI           | MS-7142                     | [679ea97c9a](https://linux-hardware.org/?probe=679ea97c9a) | Jan 04, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | [d8329e0062](https://linux-hardware.org/?probe=d8329e0062) | Jan 04, 2024 |
| HP            | 83C1                        | [0f9107b4c6](https://linux-hardware.org/?probe=0f9107b4c6) | Jan 04, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [0113813f07](https://linux-hardware.org/?probe=0113813f07) | Jan 04, 2024 |
| MSI           | B150 GAMING M3              | [217eb67035](https://linux-hardware.org/?probe=217eb67035) | Jan 03, 2024 |
| ASUSTek       | X99-DELUXE II               | [73c3f784f9](https://linux-hardware.org/?probe=73c3f784f9) | Jan 03, 2024 |
| ASUSTek       | PRIME B450M-K II            | [3055333756](https://linux-hardware.org/?probe=3055333756) | Jan 03, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | [f4db017a3f](https://linux-hardware.org/?probe=f4db017a3f) | Jan 03, 2024 |
| MSI           | X99A GAMING 7               | [1d4efc3026](https://linux-hardware.org/?probe=1d4efc3026) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2f31bf4a09](https://linux-hardware.org/?probe=2f31bf4a09) | Jan 03, 2024 |
| ASUSTek       | PRIME H310M-E               | [6fe5c13887](https://linux-hardware.org/?probe=6fe5c13887) | Jan 03, 2024 |
| MSI           | X99A RAIDER                 | [353e6f7966](https://linux-hardware.org/?probe=353e6f7966) | Jan 03, 2024 |
| ASUSTek       | A8R32-MVP Deluxe            | [0f0e24cce5](https://linux-hardware.org/?probe=0f0e24cce5) | Jan 03, 2024 |
| ASRock        | X370 Pro4                   | [f2bd8e4b5d](https://linux-hardware.org/?probe=f2bd8e4b5d) | Jan 03, 2024 |
| Gigabyte      | X670 GAMING X AX V2         | [e4a3d2463f](https://linux-hardware.org/?probe=e4a3d2463f) | Jan 03, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | [bd15a62f1a](https://linux-hardware.org/?probe=bd15a62f1a) | Jan 02, 2024 |
| ASUSTek       | Crosshair V Formula         | [2db319c529](https://linux-hardware.org/?probe=2db319c529) | Jan 02, 2024 |
| ASUSTek       | P8H77-M                     | [518d80f081](https://linux-hardware.org/?probe=518d80f081) | Jan 02, 2024 |
| MSI           | X99A RAIDER                 | [0c40685bac](https://linux-hardware.org/?probe=0c40685bac) | Jan 02, 2024 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [9711c69823](https://linux-hardware.org/?probe=9711c69823) | Jan 02, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | [9868062aa3](https://linux-hardware.org/?probe=9868062aa3) | Jan 02, 2024 |
| Dell          | 0NDYHG A01                  | [68cde01489](https://linux-hardware.org/?probe=68cde01489) | Jan 02, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [ccaa0646d7](https://linux-hardware.org/?probe=ccaa0646d7) | Jan 01, 2024 |
| ASUSTek       | H81M-A/BR                   | [6f2227d209](https://linux-hardware.org/?probe=6f2227d209) | Jan 01, 2024 |
| ASUSTek       | PRIME B550M-A               | [a4cf1bb1ea](https://linux-hardware.org/?probe=a4cf1bb1ea) | Jan 01, 2024 |
| ASUSTek       | H97-PLUS                    | [e208caf8f1](https://linux-hardware.org/?probe=e208caf8f1) | Jan 01, 2024 |
| MSI           | X99A RAIDER                 | [bb37fe4632](https://linux-hardware.org/?probe=bb37fe4632) | Jan 01, 2024 |
| MSI           | 880GM-E41                   | [caf8e2f533](https://linux-hardware.org/?probe=caf8e2f533) | Dec 31, 2023 |
| ASUSTek       | H81M-A/BR                   | [61946a6719](https://linux-hardware.org/?probe=61946a6719) | Dec 31, 2023 |
| OEM           | G41 775 ICH7 8712           | [bfb91f354b](https://linux-hardware.org/?probe=bfb91f354b) | Dec 31, 2023 |
| AMI           | Intel                       | [532ef0e65e](https://linux-hardware.org/?probe=532ef0e65e) | Dec 31, 2023 |
| ASUSTek       | H81M-K                      | [8262129320](https://linux-hardware.org/?probe=8262129320) | Dec 31, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [4faca6dad4](https://linux-hardware.org/?probe=4faca6dad4) | Dec 31, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [83ef33bf03](https://linux-hardware.org/?probe=83ef33bf03) | Dec 31, 2023 |
| MSI           | X99A RAIDER                 | [a9aee13c48](https://linux-hardware.org/?probe=a9aee13c48) | Dec 31, 2023 |
| Apple         | Mac-F221BEC8                | [57b09cabf5](https://linux-hardware.org/?probe=57b09cabf5) | Dec 31, 2023 |
| MSI           | H110M PRO-VD                | [d508dc8f38](https://linux-hardware.org/?probe=d508dc8f38) | Dec 31, 2023 |
| MSI           | 970 GAMING                  | [7f7f8f09ae](https://linux-hardware.org/?probe=7f7f8f09ae) | Dec 31, 2023 |
| ASUSTek       | M5A97 R2.0                  | [674f54c42c](https://linux-hardware.org/?probe=674f54c42c) | Dec 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | [fa7e23a6ee](https://linux-hardware.org/?probe=fa7e23a6ee) | Dec 30, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [b7be314f8d](https://linux-hardware.org/?probe=b7be314f8d) | Dec 30, 2023 |
| Dell          | 0R6PCT A01                  | [8409c4a0d6](https://linux-hardware.org/?probe=8409c4a0d6) | Dec 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | [090ed6d6f3](https://linux-hardware.org/?probe=090ed6d6f3) | Dec 30, 2023 |
| Gigabyte      | G41MT-D3                    | [442c87e7d9](https://linux-hardware.org/?probe=442c87e7d9) | Dec 30, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [403210cab1](https://linux-hardware.org/?probe=403210cab1) | Dec 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [50eef7421d](https://linux-hardware.org/?probe=50eef7421d) | Dec 29, 2023 |
| Gigabyte      | X670 GAMING X AX V2         | [fb8e3461de](https://linux-hardware.org/?probe=fb8e3461de) | Dec 29, 2023 |
| ASRock        | AD2700-ITX                  | [3296b05cf8](https://linux-hardware.org/?probe=3296b05cf8) | Dec 29, 2023 |
| Gigabyte      | B450M DS3H V2               | [c8430d442b](https://linux-hardware.org/?probe=c8430d442b) | Dec 29, 2023 |
| ASRock        | B85M Pro3                   | [f61d357d7f](https://linux-hardware.org/?probe=f61d357d7f) | Dec 29, 2023 |
| HP            | 8719                        | [91c89a31b5](https://linux-hardware.org/?probe=91c89a31b5) | Dec 29, 2023 |
| Pegatron      | IPMIP-GS                    | [d8ace6bbb7](https://linux-hardware.org/?probe=d8ace6bbb7) | Dec 29, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [e49bfae343](https://linux-hardware.org/?probe=e49bfae343) | Dec 28, 2023 |
| Pegatron      | 2AB6                        | [faf90bb1a2](https://linux-hardware.org/?probe=faf90bb1a2) | Dec 28, 2023 |
| Gigabyte      | B450 AORUS M                | [e01ab0c412](https://linux-hardware.org/?probe=e01ab0c412) | Dec 28, 2023 |
| MSI           | MS-7390                     | [ca9f0bde00](https://linux-hardware.org/?probe=ca9f0bde00) | Dec 28, 2023 |
| Pegatron      | 2AB6                        | [6eb51d9bd9](https://linux-hardware.org/?probe=6eb51d9bd9) | Dec 28, 2023 |
| Dell          | 0R230R A00                  | [50111db215](https://linux-hardware.org/?probe=50111db215) | Dec 28, 2023 |
| Gigabyte      | Z77MX-D3H                   | [3357d873d5](https://linux-hardware.org/?probe=3357d873d5) | Dec 28, 2023 |
| ASRock        | X570 Steel Legend           | [a2a45575d5](https://linux-hardware.org/?probe=a2a45575d5) | Dec 28, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [7a9ff71d9b](https://linux-hardware.org/?probe=7a9ff71d9b) | Dec 28, 2023 |
| ASRock        | X570 Steel Legend           | [836a55f0b6](https://linux-hardware.org/?probe=836a55f0b6) | Dec 28, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0b3af4418c](https://linux-hardware.org/?probe=0b3af4418c) | Dec 27, 2023 |
| MSI           | Z97 GAMING 5                | [3b0901d1a4](https://linux-hardware.org/?probe=3b0901d1a4) | Dec 27, 2023 |
| ASRock        | X399 Phantom Gaming 6       | [3d57263239](https://linux-hardware.org/?probe=3d57263239) | Dec 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d661150c95](https://linux-hardware.org/?probe=d661150c95) | Dec 27, 2023 |
| ASUSTek       | H81M-A/BR                   | [87cae62baf](https://linux-hardware.org/?probe=87cae62baf) | Dec 27, 2023 |
| Gigabyte      | D525TUD                     | [8625448d34](https://linux-hardware.org/?probe=8625448d34) | Dec 27, 2023 |
| Unknown       | Unknown                     | [d9355d1b8b](https://linux-hardware.org/?probe=d9355d1b8b) | Dec 27, 2023 |
| ASUSTek       | PRIME X570-PRO              | [104529fd86](https://linux-hardware.org/?probe=104529fd86) | Dec 26, 2023 |
| MSI           | B450 TOMAHAWK               | [40a7073595](https://linux-hardware.org/?probe=40a7073595) | Dec 26, 2023 |
| Gigabyte      | Z170-HD3-CF                 | [99e618d817](https://linux-hardware.org/?probe=99e618d817) | Dec 26, 2023 |
| ASRock        | B365M Pro4                  | [3c41d3773a](https://linux-hardware.org/?probe=3c41d3773a) | Dec 26, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [267c545497](https://linux-hardware.org/?probe=267c545497) | Dec 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [96c4736340](https://linux-hardware.org/?probe=96c4736340) | Dec 26, 2023 |
| ASRock        | 990FX Killer                | [1003211f6d](https://linux-hardware.org/?probe=1003211f6d) | Dec 26, 2023 |
| ASRock        | 990FX Killer                | [034adc4ac8](https://linux-hardware.org/?probe=034adc4ac8) | Dec 26, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a68e5c51b4](https://linux-hardware.org/?probe=a68e5c51b4) | Dec 25, 2023 |
| MSI           | B350M MORTAR ARCTIC         | [68c1102e98](https://linux-hardware.org/?probe=68c1102e98) | Dec 25, 2023 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | [a5a641b111](https://linux-hardware.org/?probe=a5a641b111) | Dec 25, 2023 |
| MSI           | B350M MORTAR ARCTIC         | [f22547b26f](https://linux-hardware.org/?probe=f22547b26f) | Dec 25, 2023 |
| Gigabyte      | H77N-WIFI                   | [22bbfabce0](https://linux-hardware.org/?probe=22bbfabce0) | Dec 25, 2023 |
| ASUSTek       | PRIME X570-PRO              | [d6f1c37a34](https://linux-hardware.org/?probe=d6f1c37a34) | Dec 25, 2023 |
| Gigabyte      | D525TUD                     | [357709050e](https://linux-hardware.org/?probe=357709050e) | Dec 25, 2023 |
| MSI           | X99A RAIDER                 | [bd10b63ca1](https://linux-hardware.org/?probe=bd10b63ca1) | Dec 25, 2023 |
| MSI           | A320M PRO-VH PLUS           | [53fae0e708](https://linux-hardware.org/?probe=53fae0e708) | Dec 25, 2023 |
| ASUSTek       | G10DK                       | [b1132c5478](https://linux-hardware.org/?probe=b1132c5478) | Dec 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5dea927ca9](https://linux-hardware.org/?probe=5dea927ca9) | Dec 24, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [5c7f2ef98c](https://linux-hardware.org/?probe=5c7f2ef98c) | Dec 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | [0a5b67d3f4](https://linux-hardware.org/?probe=0a5b67d3f4) | Dec 24, 2023 |
| MSI           | MS-7388                     | [efab378a60](https://linux-hardware.org/?probe=efab378a60) | Dec 24, 2023 |
| Dell          | 0WMJ54 A01                  | [31f29a3843](https://linux-hardware.org/?probe=31f29a3843) | Dec 24, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [587884179e](https://linux-hardware.org/?probe=587884179e) | Dec 24, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [bdb39d60de](https://linux-hardware.org/?probe=bdb39d60de) | Dec 24, 2023 |
| MAXSUN        | MS-Terminator B550M         | [57ce047c4c](https://linux-hardware.org/?probe=57ce047c4c) | Dec 24, 2023 |
| MSI           | X99A RAIDER                 | [b150280df5](https://linux-hardware.org/?probe=b150280df5) | Dec 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | [6484f4217b](https://linux-hardware.org/?probe=6484f4217b) | Dec 24, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [dd658b1151](https://linux-hardware.org/?probe=dd658b1151) | Dec 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [c8bab56547](https://linux-hardware.org/?probe=c8bab56547) | Dec 23, 2023 |
| HP            | 2ADC                        | [2c9d8d03d2](https://linux-hardware.org/?probe=2c9d8d03d2) | Dec 23, 2023 |
| ASRock        | X370 Taichi                 | [689d51f57e](https://linux-hardware.org/?probe=689d51f57e) | Dec 23, 2023 |
| Gigabyte      | B85-HD3                     | [79fbb89592](https://linux-hardware.org/?probe=79fbb89592) | Dec 23, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [4cd7d986cd](https://linux-hardware.org/?probe=4cd7d986cd) | Dec 23, 2023 |
| Dell          | 04Y8V0 A02                  | [1c3e40ac13](https://linux-hardware.org/?probe=1c3e40ac13) | Dec 23, 2023 |
| MSI           | MS-7388                     | [5027d4b8ed](https://linux-hardware.org/?probe=5027d4b8ed) | Dec 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [aaf6ab3d26](https://linux-hardware.org/?probe=aaf6ab3d26) | Dec 23, 2023 |
| Gigabyte      | D525TUD                     | [dd2248530b](https://linux-hardware.org/?probe=dd2248530b) | Dec 23, 2023 |
| Gigabyte      | G41MT-D3                    | [d7f5fd2175](https://linux-hardware.org/?probe=d7f5fd2175) | Dec 23, 2023 |
| ASRock        | Z370 Professional Gaming... | [d46814af3c](https://linux-hardware.org/?probe=d46814af3c) | Dec 23, 2023 |
| Dell          | 0K3CM7 A00                  | [019b46745e](https://linux-hardware.org/?probe=019b46745e) | Dec 22, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [3fa9465c1a](https://linux-hardware.org/?probe=3fa9465c1a) | Dec 22, 2023 |
| ASUSTek       | P8H61 EVO                   | [a123efbb84](https://linux-hardware.org/?probe=a123efbb84) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | [1049cbc16b](https://linux-hardware.org/?probe=1049cbc16b) | Dec 22, 2023 |
| Colorful T... | A320M-M.2 PRO V15           | [821494cfbf](https://linux-hardware.org/?probe=821494cfbf) | Dec 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [c83a6a5f5d](https://linux-hardware.org/?probe=c83a6a5f5d) | Dec 22, 2023 |
| PCWare        | IPMH61R3                    | [891c2058a8](https://linux-hardware.org/?probe=891c2058a8) | Dec 22, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [f3f83a4f0a](https://linux-hardware.org/?probe=f3f83a4f0a) | Dec 22, 2023 |
| ASRock        | J3160DC-ITX                 | [c84aa85d4e](https://linux-hardware.org/?probe=c84aa85d4e) | Dec 22, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [7eb85caf57](https://linux-hardware.org/?probe=7eb85caf57) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [0dc09851b1](https://linux-hardware.org/?probe=0dc09851b1) | Dec 21, 2023 |
| Dell          | 0WMJ54 A01                  | [6cacd38012](https://linux-hardware.org/?probe=6cacd38012) | Dec 21, 2023 |
| ASUSTek       | X99-DELUXE II               | [dca266a251](https://linux-hardware.org/?probe=dca266a251) | Dec 21, 2023 |
| ASUSTek       | X99-DELUXE II               | [b9409f01d5](https://linux-hardware.org/?probe=b9409f01d5) | Dec 21, 2023 |
| ASRock        | B550M Pro4                  | [bb26992a0a](https://linux-hardware.org/?probe=bb26992a0a) | Dec 21, 2023 |
| HP            | 2B4B                        | [19a3edb061](https://linux-hardware.org/?probe=19a3edb061) | Dec 21, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [761fb59fa5](https://linux-hardware.org/?probe=761fb59fa5) | Dec 20, 2023 |
| Dell          | 042P49 A01                  | [fb968ffb8b](https://linux-hardware.org/?probe=fb968ffb8b) | Dec 20, 2023 |
| MSI           | PRO Z690-A WIFI             | [d6a5b20ac6](https://linux-hardware.org/?probe=d6a5b20ac6) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [088b57605f](https://linux-hardware.org/?probe=088b57605f) | Dec 20, 2023 |
| AZW           | MINI S                      | [78169fe4be](https://linux-hardware.org/?probe=78169fe4be) | Dec 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [8703894e1c](https://linux-hardware.org/?probe=8703894e1c) | Dec 20, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [85087e0568](https://linux-hardware.org/?probe=85087e0568) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [ec86cf0c12](https://linux-hardware.org/?probe=ec86cf0c12) | Dec 19, 2023 |
| ASUSTek       | P5B                         | [a700c11a65](https://linux-hardware.org/?probe=a700c11a65) | Dec 19, 2023 |
| ASRock        | B450M-HDV R4.0              | [02d834a147](https://linux-hardware.org/?probe=02d834a147) | Dec 19, 2023 |
| HP            | 3033h                       | [e57ef2fb67](https://linux-hardware.org/?probe=e57ef2fb67) | Dec 19, 2023 |
| ASRock        | B650M Pro RS                | [df96c996dd](https://linux-hardware.org/?probe=df96c996dd) | Dec 18, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [7bd446ee65](https://linux-hardware.org/?probe=7bd446ee65) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [2501635862](https://linux-hardware.org/?probe=2501635862) | Dec 18, 2023 |
| ASRock        | B450M-HDV R4.0              | [da0af8ac25](https://linux-hardware.org/?probe=da0af8ac25) | Dec 18, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [c66e6657fe](https://linux-hardware.org/?probe=c66e6657fe) | Dec 18, 2023 |
| HP            | 8643 SMVB                   | [70ece5f797](https://linux-hardware.org/?probe=70ece5f797) | Dec 18, 2023 |
| MSI           | X99A RAIDER                 | [84c183a024](https://linux-hardware.org/?probe=84c183a024) | Dec 18, 2023 |
| HP            | 8643 SMVB                   | [5082c6046e](https://linux-hardware.org/?probe=5082c6046e) | Dec 18, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [c0b618e2ab](https://linux-hardware.org/?probe=c0b618e2ab) | Dec 18, 2023 |
| HP            | 802E                        | [191904a770](https://linux-hardware.org/?probe=191904a770) | Dec 17, 2023 |
| ASRock        | H310M-STX                   | [df11c23d7c](https://linux-hardware.org/?probe=df11c23d7c) | Dec 17, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | [0f2293e8d1](https://linux-hardware.org/?probe=0f2293e8d1) | Dec 17, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [47747d42ef](https://linux-hardware.org/?probe=47747d42ef) | Dec 17, 2023 |
| MSI           | X99A RAIDER                 | [047995ad80](https://linux-hardware.org/?probe=047995ad80) | Dec 17, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [9f0d5821e3](https://linux-hardware.org/?probe=9f0d5821e3) | Dec 16, 2023 |
| Dell          | 0HY9JP A00                  | [5af488fb21](https://linux-hardware.org/?probe=5af488fb21) | Dec 16, 2023 |
| HP            | 8265                        | [58cc9fa090](https://linux-hardware.org/?probe=58cc9fa090) | Dec 16, 2023 |
| Gigabyte      | G41MT-D3                    | [39e7517ac6](https://linux-hardware.org/?probe=39e7517ac6) | Dec 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [68a9708e6a](https://linux-hardware.org/?probe=68a9708e6a) | Dec 16, 2023 |
| ASRock        | B450M-HDV R4.0              | [e93c46f2e9](https://linux-hardware.org/?probe=e93c46f2e9) | Dec 16, 2023 |
| ASRock        | B450M-HDV R4.0              | [25eb2af58f](https://linux-hardware.org/?probe=25eb2af58f) | Dec 16, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [7ad9484605](https://linux-hardware.org/?probe=7ad9484605) | Dec 16, 2023 |
| Gigabyte      | D525TUD                     | [34a66d3cef](https://linux-hardware.org/?probe=34a66d3cef) | Dec 15, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [dd6121c135](https://linux-hardware.org/?probe=dd6121c135) | Dec 15, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [9268266cec](https://linux-hardware.org/?probe=9268266cec) | Dec 15, 2023 |
| PCWare        | IPMH61R3                    | [ecac398c88](https://linux-hardware.org/?probe=ecac398c88) | Dec 15, 2023 |
| Dell          | 0HY9JP A00                  | [3a2a8878eb](https://linux-hardware.org/?probe=3a2a8878eb) | Dec 15, 2023 |
| MSI           | FM2-A75MA-E35               | [f589fd16ee](https://linux-hardware.org/?probe=f589fd16ee) | Dec 15, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [059715d1bf](https://linux-hardware.org/?probe=059715d1bf) | Dec 15, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [8a3e0ce72f](https://linux-hardware.org/?probe=8a3e0ce72f) | Dec 15, 2023 |
| Gigabyte      | B550M DS3H AC               | [95a15638a4](https://linux-hardware.org/?probe=95a15638a4) | Dec 15, 2023 |
| Gigabyte      | B550M DS3H AC               | [7482b66564](https://linux-hardware.org/?probe=7482b66564) | Dec 15, 2023 |
| ASUSTek       | PRIME B550M-A               | [fe2ebbb9af](https://linux-hardware.org/?probe=fe2ebbb9af) | Dec 14, 2023 |
| MSI           | MEG Z390 GODLIKE            | [e384ee26a6](https://linux-hardware.org/?probe=e384ee26a6) | Dec 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c8d2a05aea](https://linux-hardware.org/?probe=c8d2a05aea) | Dec 14, 2023 |
| MSI           | PRO B650M-P                 | [acee62fb75](https://linux-hardware.org/?probe=acee62fb75) | Dec 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [ba53faacb0](https://linux-hardware.org/?probe=ba53faacb0) | Dec 13, 2023 |
| ASUSTek       | H61M-K                      | [15f1f8f029](https://linux-hardware.org/?probe=15f1f8f029) | Dec 13, 2023 |
| Gigabyte      | H77N-WIFI                   | [017252c955](https://linux-hardware.org/?probe=017252c955) | Dec 13, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [5435277f12](https://linux-hardware.org/?probe=5435277f12) | Dec 13, 2023 |
| HP            | 8061                        | [9700867e8c](https://linux-hardware.org/?probe=9700867e8c) | Dec 13, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [978ed7ec9c](https://linux-hardware.org/?probe=978ed7ec9c) | Dec 13, 2023 |
| ASUSTek       | H61M-K                      | [d7a660dbef](https://linux-hardware.org/?probe=d7a660dbef) | Dec 13, 2023 |
| Gigabyte      | D525TUD                     | [12c2204715](https://linux-hardware.org/?probe=12c2204715) | Dec 12, 2023 |
| Gigabyte      | P35-DS3                     | [b8b172a5f2](https://linux-hardware.org/?probe=b8b172a5f2) | Dec 12, 2023 |
| Gigabyte      | P35-DS3                     | [d386a28d7e](https://linux-hardware.org/?probe=d386a28d7e) | Dec 12, 2023 |
| Gigabyte      | Z77MX-D3H                   | [45cc0c507d](https://linux-hardware.org/?probe=45cc0c507d) | Dec 12, 2023 |
| HP            | 1495                        | [9fb4cb4ac8](https://linux-hardware.org/?probe=9fb4cb4ac8) | Dec 12, 2023 |
| Gigabyte      | GA-890FXA-UD7               | [92c2bcd902](https://linux-hardware.org/?probe=92c2bcd902) | Dec 12, 2023 |
| ASUSTek       | Pro B550M-C                 | [9887ecb3b0](https://linux-hardware.org/?probe=9887ecb3b0) | Dec 12, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [0720cbce6b](https://linux-hardware.org/?probe=0720cbce6b) | Dec 12, 2023 |
| Gigabyte      | EP45-UD3L                   | [e71c3884d8](https://linux-hardware.org/?probe=e71c3884d8) | Dec 11, 2023 |
| HP            | 802E                        | [606309324b](https://linux-hardware.org/?probe=606309324b) | Dec 11, 2023 |
| Gigabyte      | J1900M-D2P                  | [f706bd9261](https://linux-hardware.org/?probe=f706bd9261) | Dec 11, 2023 |
| Intel         | HM570                       | [a0f2eecda0](https://linux-hardware.org/?probe=a0f2eecda0) | Dec 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [83d630d21f](https://linux-hardware.org/?probe=83d630d21f) | Dec 11, 2023 |
| Dell          | 055H3G A00                  | [501e07bc4d](https://linux-hardware.org/?probe=501e07bc4d) | Dec 10, 2023 |
| MSI           | B450M-A PRO MAX             | [fa533e33bb](https://linux-hardware.org/?probe=fa533e33bb) | Dec 10, 2023 |
| Gigabyte      | Z490 VISION G               | [184c82a359](https://linux-hardware.org/?probe=184c82a359) | Dec 10, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [069b020cd5](https://linux-hardware.org/?probe=069b020cd5) | Dec 10, 2023 |
| Foxconn       | 2A8C                        | [a467dabfb7](https://linux-hardware.org/?probe=a467dabfb7) | Dec 10, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [505f85e4d4](https://linux-hardware.org/?probe=505f85e4d4) | Dec 10, 2023 |
| HP            | 18E7                        | [dad5884f78](https://linux-hardware.org/?probe=dad5884f78) | Dec 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [14c50f3617](https://linux-hardware.org/?probe=14c50f3617) | Dec 10, 2023 |
| ASUSTek       | PRIME A320M-C R2.0          | [a8685fb67b](https://linux-hardware.org/?probe=a8685fb67b) | Dec 10, 2023 |
| MSI           | A88XM-E35                   | [c0bf97d7e0](https://linux-hardware.org/?probe=c0bf97d7e0) | Dec 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [31821d09d8](https://linux-hardware.org/?probe=31821d09d8) | Dec 09, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [e468ba51f6](https://linux-hardware.org/?probe=e468ba51f6) | Dec 09, 2023 |
| ASUSTek       | A88XM-A                     | [2b60976ef6](https://linux-hardware.org/?probe=2b60976ef6) | Dec 09, 2023 |
| ASUSTek       | H170-PRO                    | [5e8d3ff468](https://linux-hardware.org/?probe=5e8d3ff468) | Dec 09, 2023 |
| Foxconn       | 2A8C                        | [78cb902abe](https://linux-hardware.org/?probe=78cb902abe) | Dec 09, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [210d482f6d](https://linux-hardware.org/?probe=210d482f6d) | Dec 09, 2023 |
| MSI           | A88XM-E35                   | [b90d791132](https://linux-hardware.org/?probe=b90d791132) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [7267af3f34](https://linux-hardware.org/?probe=7267af3f34) | Dec 08, 2023 |
| ASRock        | B450 Pro4                   | [25627a5644](https://linux-hardware.org/?probe=25627a5644) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [8d7f7aebab](https://linux-hardware.org/?probe=8d7f7aebab) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [70f37dae85](https://linux-hardware.org/?probe=70f37dae85) | Dec 08, 2023 |
| ANGXUN        | X99 V1.0                    | [88919a1403](https://linux-hardware.org/?probe=88919a1403) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [2b349d78ce](https://linux-hardware.org/?probe=2b349d78ce) | Dec 07, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [3c37d1bb9f](https://linux-hardware.org/?probe=3c37d1bb9f) | Dec 07, 2023 |
| ASUSTek       | PRIME B350M-A               | [665a5984d2](https://linux-hardware.org/?probe=665a5984d2) | Dec 07, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [dc05a32f3d](https://linux-hardware.org/?probe=dc05a32f3d) | Dec 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [38c8286c83](https://linux-hardware.org/?probe=38c8286c83) | Dec 06, 2023 |
| MSI           | B460M PRO                   | [107b14c2d9](https://linux-hardware.org/?probe=107b14c2d9) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [38945d6d2e](https://linux-hardware.org/?probe=38945d6d2e) | Dec 05, 2023 |
| EVGA          | 132-YW-E178-FTW 1           | [3898078db1](https://linux-hardware.org/?probe=3898078db1) | Dec 05, 2023 |
| Unknown       | NISB 3500                   | [454871dab4](https://linux-hardware.org/?probe=454871dab4) | Dec 05, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [53dbcd2c87](https://linux-hardware.org/?probe=53dbcd2c87) | Dec 05, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5ec26a4bca](https://linux-hardware.org/?probe=5ec26a4bca) | Dec 05, 2023 |
| Lenovo        | ThinkServer TS140           | [c53a3bf5e8](https://linux-hardware.org/?probe=c53a3bf5e8) | Dec 05, 2023 |
| ASRock        | AD2700-ITX                  | [3681f281ac](https://linux-hardware.org/?probe=3681f281ac) | Dec 05, 2023 |
| MSI           | PRO B550M-VC WIFI           | [6e9785a58a](https://linux-hardware.org/?probe=6e9785a58a) | Dec 05, 2023 |
| ASUSTek       | Z170-A                      | [8a8bfb131c](https://linux-hardware.org/?probe=8a8bfb131c) | Dec 04, 2023 |
| MSI           | B450 TOMAHAWK               | [56afeffd34](https://linux-hardware.org/?probe=56afeffd34) | Dec 04, 2023 |
| Intel         | B75                         | [4290424c1d](https://linux-hardware.org/?probe=4290424c1d) | Dec 04, 2023 |
| Gigabyte      | GA-880GM-USB3               | [f4078eb310](https://linux-hardware.org/?probe=f4078eb310) | Dec 04, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [bb0ded92ef](https://linux-hardware.org/?probe=bb0ded92ef) | Dec 03, 2023 |
| BESSTAR Te... | UM350                       | [28b627c64a](https://linux-hardware.org/?probe=28b627c64a) | Dec 03, 2023 |
| Gigabyte      | 970A-DS3P                   | [6fce5f3dec](https://linux-hardware.org/?probe=6fce5f3dec) | Dec 03, 2023 |
| Dell          | 0WR7PY A01                  | [67b1cc2f69](https://linux-hardware.org/?probe=67b1cc2f69) | Dec 03, 2023 |
| MSI           | B360-A PRO                  | [7df9fbb107](https://linux-hardware.org/?probe=7df9fbb107) | Dec 03, 2023 |
| MSI           | PRO B650-VC WIFI            | [9e15f48c96](https://linux-hardware.org/?probe=9e15f48c96) | Dec 03, 2023 |
| Intel         | H61                         | [71c32c973c](https://linux-hardware.org/?probe=71c32c973c) | Dec 03, 2023 |
| Intel         | X99                         | [b1ae912db2](https://linux-hardware.org/?probe=b1ae912db2) | Dec 03, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [52374a1dea](https://linux-hardware.org/?probe=52374a1dea) | Dec 03, 2023 |
| MSI           | B360-A PRO                  | [f9da2a7d45](https://linux-hardware.org/?probe=f9da2a7d45) | Dec 03, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | [e3950352ba](https://linux-hardware.org/?probe=e3950352ba) | Dec 03, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [fb15da06c7](https://linux-hardware.org/?probe=fb15da06c7) | Dec 03, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [d869b4e21b](https://linux-hardware.org/?probe=d869b4e21b) | Dec 03, 2023 |
| Huanan        | X99-TF                      | [c617461c74](https://linux-hardware.org/?probe=c617461c74) | Dec 03, 2023 |
| HP            | 2215                        | [f29d88c563](https://linux-hardware.org/?probe=f29d88c563) | Dec 03, 2023 |
| Positivo      | POS-SIGL40BX POSITIVO       | [d6bdfaf7b5](https://linux-hardware.org/?probe=d6bdfaf7b5) | Dec 03, 2023 |
| ASUSTek       | PRIME X670-P                | [f7bf7a5dcc](https://linux-hardware.org/?probe=f7bf7a5dcc) | Dec 02, 2023 |
| Biostar       | B450MH                      | [e490dfb129](https://linux-hardware.org/?probe=e490dfb129) | Dec 02, 2023 |
| Dell          | 0GDG8Y A00                  | [97b3234a72](https://linux-hardware.org/?probe=97b3234a72) | Dec 02, 2023 |
| Gigabyte      | B650M DS3H                  | [0cd9d3d156](https://linux-hardware.org/?probe=0cd9d3d156) | Dec 02, 2023 |
| Dell          | 02YRK5 A03                  | [ae544eff63](https://linux-hardware.org/?probe=ae544eff63) | Dec 02, 2023 |
| MSI           | PRO B660M-A WIFI            | [d3a2fc2cb0](https://linux-hardware.org/?probe=d3a2fc2cb0) | Dec 02, 2023 |
| Gigabyte      | B550M DS3H                  | [a7ab6a0555](https://linux-hardware.org/?probe=a7ab6a0555) | Dec 02, 2023 |
| ASRock        | B650E PG-ITX WiFi           | [94317ffd1f](https://linux-hardware.org/?probe=94317ffd1f) | Dec 02, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [d029e3819c](https://linux-hardware.org/?probe=d029e3819c) | Dec 02, 2023 |
| Gigabyte      | GA-870A-UD3                 | [a827e0cc16](https://linux-hardware.org/?probe=a827e0cc16) | Dec 02, 2023 |
| Gigabyte      | J1900M-D2P                  | [0d2ac061a9](https://linux-hardware.org/?probe=0d2ac061a9) | Dec 02, 2023 |
| ASUSTek       | Z87-PRO                     | [7946f9a622](https://linux-hardware.org/?probe=7946f9a622) | Dec 01, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [80be39f0d4](https://linux-hardware.org/?probe=80be39f0d4) | Dec 01, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | [320fdec41d](https://linux-hardware.org/?probe=320fdec41d) | Dec 01, 2023 |
| HP            | 8061                        | [8f86201dfb](https://linux-hardware.org/?probe=8f86201dfb) | Dec 01, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [0ed139ee9c](https://linux-hardware.org/?probe=0ed139ee9c) | Dec 01, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [14b776bc4a](https://linux-hardware.org/?probe=14b776bc4a) | Dec 01, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | [59610f075c](https://linux-hardware.org/?probe=59610f075c) | Nov 30, 2023 |
| Gigabyte      | A520M AORUS ELITE           | [ae6274f798](https://linux-hardware.org/?probe=ae6274f798) | Nov 30, 2023 |
| ASRock        | AD2700-ITX                  | [215e772a98](https://linux-hardware.org/?probe=215e772a98) | Nov 30, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | [1959f30d83](https://linux-hardware.org/?probe=1959f30d83) | Nov 30, 2023 |
| Pegatron      | IPMIP-GS                    | [ebe5fd5255](https://linux-hardware.org/?probe=ebe5fd5255) | Nov 30, 2023 |
| Pegatron      | IPMIP-GS                    | [7b6f94666e](https://linux-hardware.org/?probe=7b6f94666e) | Nov 30, 2023 |
| MSI           | B450M-A PRO MAX             | [a6ae767fad](https://linux-hardware.org/?probe=a6ae767fad) | Nov 30, 2023 |
| ASRock        | 970 Extreme4                | [5dd27edbe4](https://linux-hardware.org/?probe=5dd27edbe4) | Nov 29, 2023 |
| Dell          | 08HPGT A01                  | [b9576cf1a9](https://linux-hardware.org/?probe=b9576cf1a9) | Nov 29, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [a418438d62](https://linux-hardware.org/?probe=a418438d62) | Nov 29, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [c6673a5a66](https://linux-hardware.org/?probe=c6673a5a66) | Nov 29, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [a5a00f200f](https://linux-hardware.org/?probe=a5a00f200f) | Nov 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [816bb46c28](https://linux-hardware.org/?probe=816bb46c28) | Nov 29, 2023 |
| ASRock        | X570 Taichi                 | [0b316f9f1b](https://linux-hardware.org/?probe=0b316f9f1b) | Nov 28, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [82528116e5](https://linux-hardware.org/?probe=82528116e5) | Nov 28, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [348a2974d6](https://linux-hardware.org/?probe=348a2974d6) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [dcfc4409e2](https://linux-hardware.org/?probe=dcfc4409e2) | Nov 28, 2023 |
| HP            | 1495                        | [17732cf790](https://linux-hardware.org/?probe=17732cf790) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [bb86b33f71](https://linux-hardware.org/?probe=bb86b33f71) | Nov 28, 2023 |
| ASRock        | H97M Pro4                   | [88bee4d4f2](https://linux-hardware.org/?probe=88bee4d4f2) | Nov 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [130735940f](https://linux-hardware.org/?probe=130735940f) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3397e49e8a](https://linux-hardware.org/?probe=3397e49e8a) | Nov 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [fccb07c19e](https://linux-hardware.org/?probe=fccb07c19e) | Nov 27, 2023 |
| ASRock        | X570 Pro4                   | [b1375e1720](https://linux-hardware.org/?probe=b1375e1720) | Nov 27, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [e1e2845536](https://linux-hardware.org/?probe=e1e2845536) | Nov 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | [af4437b421](https://linux-hardware.org/?probe=af4437b421) | Nov 27, 2023 |
| ASUSTek       | X99-DELUXE II               | [2bb0010426](https://linux-hardware.org/?probe=2bb0010426) | Nov 27, 2023 |
| Gigabyte      | H77N-WIFI                   | [b71948f3b9](https://linux-hardware.org/?probe=b71948f3b9) | Nov 27, 2023 |
| Dell          | 02YRK5 A03                  | [3b55d8f733](https://linux-hardware.org/?probe=3b55d8f733) | Nov 27, 2023 |
| MSI           | H61M-P31/W8                 | [b74cd41faf](https://linux-hardware.org/?probe=b74cd41faf) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [648a453b3f](https://linux-hardware.org/?probe=648a453b3f) | Nov 26, 2023 |
| Gigabyte      | GA-MA790X-DS4               | [5435d9e2ba](https://linux-hardware.org/?probe=5435d9e2ba) | Nov 26, 2023 |
| ASUSTek       | P7P55D PRO                  | [69ca3b417c](https://linux-hardware.org/?probe=69ca3b417c) | Nov 26, 2023 |
| Gigabyte      | B550M S2H                   | [284f7d2451](https://linux-hardware.org/?probe=284f7d2451) | Nov 26, 2023 |
| Gigabyte      | B650M GAMING X AX           | [dc0fce7e4a](https://linux-hardware.org/?probe=dc0fce7e4a) | Nov 26, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [5693d24a8d](https://linux-hardware.org/?probe=5693d24a8d) | Nov 26, 2023 |
| MSI           | B450M MORTAR MAX            | [7667f4a2a0](https://linux-hardware.org/?probe=7667f4a2a0) | Nov 26, 2023 |
| MSI           | X570-A PRO                  | [17cd5f34c3](https://linux-hardware.org/?probe=17cd5f34c3) | Nov 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [976fa4dff9](https://linux-hardware.org/?probe=976fa4dff9) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [84b3b5a3a1](https://linux-hardware.org/?probe=84b3b5a3a1) | Nov 25, 2023 |
| Gigabyte      | G41MT-D3                    | [39af83330a](https://linux-hardware.org/?probe=39af83330a) | Nov 25, 2023 |
| Dell          | 06D7TR A00                  | [d979c6298f](https://linux-hardware.org/?probe=d979c6298f) | Nov 24, 2023 |
| Gigabyte      | B650 GAMING X AX            | [c79d47b7b4](https://linux-hardware.org/?probe=c79d47b7b4) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [5e32800db0](https://linux-hardware.org/?probe=5e32800db0) | Nov 24, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [b7ae8810af](https://linux-hardware.org/?probe=b7ae8810af) | Nov 24, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [7aa3c32e86](https://linux-hardware.org/?probe=7aa3c32e86) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [8bb53007a4](https://linux-hardware.org/?probe=8bb53007a4) | Nov 24, 2023 |
| Apple         | Mac-F221BEC8                | [4d9238845b](https://linux-hardware.org/?probe=4d9238845b) | Nov 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [4cfc87a4cd](https://linux-hardware.org/?probe=4cfc87a4cd) | Nov 24, 2023 |
| ASRock        | B760M PG SONIC WiFi         | [48b39eec4f](https://linux-hardware.org/?probe=48b39eec4f) | Nov 23, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ecad990a24](https://linux-hardware.org/?probe=ecad990a24) | Nov 23, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [206b5d76fb](https://linux-hardware.org/?probe=206b5d76fb) | Nov 23, 2023 |
| ASUSTek       | PRIME X370-A                | [27f6e938d0](https://linux-hardware.org/?probe=27f6e938d0) | Nov 23, 2023 |
| MSI           | 760GMA-P34                  | [ebab9eb8e2](https://linux-hardware.org/?probe=ebab9eb8e2) | Nov 23, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [a4af0718ed](https://linux-hardware.org/?probe=a4af0718ed) | Nov 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [8414b3b3f1](https://linux-hardware.org/?probe=8414b3b3f1) | Nov 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [32822f68c4](https://linux-hardware.org/?probe=32822f68c4) | Nov 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [b64c66f4a2](https://linux-hardware.org/?probe=b64c66f4a2) | Nov 23, 2023 |
| ASUSTek       | M4A88T-M                    | [65c6061eb3](https://linux-hardware.org/?probe=65c6061eb3) | Nov 23, 2023 |
| HP            | 8906 SMVB                   | [c2e4fe7e50](https://linux-hardware.org/?probe=c2e4fe7e50) | Nov 23, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [eeae51d065](https://linux-hardware.org/?probe=eeae51d065) | Nov 23, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [3e89253fa2](https://linux-hardware.org/?probe=3e89253fa2) | Nov 22, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [bc7df67b84](https://linux-hardware.org/?probe=bc7df67b84) | Nov 22, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [667c79209d](https://linux-hardware.org/?probe=667c79209d) | Nov 21, 2023 |
| MSI           | IONA                        | [ccadf6afaf](https://linux-hardware.org/?probe=ccadf6afaf) | Nov 21, 2023 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | [7930532d04](https://linux-hardware.org/?probe=7930532d04) | Nov 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [49770e98c5](https://linux-hardware.org/?probe=49770e98c5) | Nov 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [9bffc312f2](https://linux-hardware.org/?probe=9bffc312f2) | Nov 21, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [84df454a40](https://linux-hardware.org/?probe=84df454a40) | Nov 21, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [8ea017cbfe](https://linux-hardware.org/?probe=8ea017cbfe) | Nov 21, 2023 |
| ASRock        | B450 Pro4                   | [5ca9f6c5df](https://linux-hardware.org/?probe=5ca9f6c5df) | Nov 21, 2023 |
| MSI           | X99A RAIDER                 | [3844682c90](https://linux-hardware.org/?probe=3844682c90) | Nov 21, 2023 |
| MSI           | A320M-A PRO MAX             | [9f22b27f2f](https://linux-hardware.org/?probe=9f22b27f2f) | Nov 21, 2023 |
| Apple         | Mac-F221BEC8                | [7a09806e41](https://linux-hardware.org/?probe=7a09806e41) | Nov 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [928f91a2f4](https://linux-hardware.org/?probe=928f91a2f4) | Nov 20, 2023 |
| Pegatron      | SM 3322                     | [aed1cc686d](https://linux-hardware.org/?probe=aed1cc686d) | Nov 20, 2023 |
| Pegatron      | SM 3322                     | [4f37480be5](https://linux-hardware.org/?probe=4f37480be5) | Nov 20, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [6eb6350799](https://linux-hardware.org/?probe=6eb6350799) | Nov 20, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | [6c52c4606d](https://linux-hardware.org/?probe=6c52c4606d) | Nov 20, 2023 |
| MSI           | X99A RAIDER                 | [fd4876bdbc](https://linux-hardware.org/?probe=fd4876bdbc) | Nov 20, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f8778aa9e9](https://linux-hardware.org/?probe=f8778aa9e9) | Nov 20, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [3c3adef14e](https://linux-hardware.org/?probe=3c3adef14e) | Nov 20, 2023 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [a4523c2cf4](https://linux-hardware.org/?probe=a4523c2cf4) | Nov 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [cc1d17df2e](https://linux-hardware.org/?probe=cc1d17df2e) | Nov 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6d6dcd50b3](https://linux-hardware.org/?probe=6d6dcd50b3) | Nov 19, 2023 |
| ASRock        | Z790-C                      | [81515ad1b7](https://linux-hardware.org/?probe=81515ad1b7) | Nov 19, 2023 |
| MSI           | Z270I GAMING PRO CARBON ... | [855aed38cb](https://linux-hardware.org/?probe=855aed38cb) | Nov 19, 2023 |
| MSI           | A88XM-E35                   | [daa37d291c](https://linux-hardware.org/?probe=daa37d291c) | Nov 19, 2023 |
| ASRock        | B450 Pro4                   | [98f95c1aee](https://linux-hardware.org/?probe=98f95c1aee) | Nov 19, 2023 |
| Dell          | 0H4VK7 A01                  | [4b95cfdbc2](https://linux-hardware.org/?probe=4b95cfdbc2) | Nov 19, 2023 |
| Gigabyte      | G41MT-D3                    | [2ccdec1495](https://linux-hardware.org/?probe=2ccdec1495) | Nov 19, 2023 |
| Intel         | HM570                       | [d266b38bab](https://linux-hardware.org/?probe=d266b38bab) | Nov 19, 2023 |
| ASUSTek       | G10DK                       | [253859ae2a](https://linux-hardware.org/?probe=253859ae2a) | Nov 19, 2023 |
| ASUSTek       | PRIME B550M-A               | [09070d5842](https://linux-hardware.org/?probe=09070d5842) | Nov 18, 2023 |
| ASUSTek       | PRIME X570-P                | [88e978f447](https://linux-hardware.org/?probe=88e978f447) | Nov 18, 2023 |
| ASUSTek       | PRIME X570-P                | [4230260e34](https://linux-hardware.org/?probe=4230260e34) | Nov 18, 2023 |
| Gigabyte      | GA-870A-UD3                 | [aebca817af](https://linux-hardware.org/?probe=aebca817af) | Nov 18, 2023 |
| HP            | 8906 SMVB                   | [c54f0b7e59](https://linux-hardware.org/?probe=c54f0b7e59) | Nov 18, 2023 |
| Acer          | H57M01                      | [3f362e7745](https://linux-hardware.org/?probe=3f362e7745) | Nov 18, 2023 |
| ASRock        | X99X Killer                 | [954fe7c236](https://linux-hardware.org/?probe=954fe7c236) | Nov 17, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [4cb5f6eae9](https://linux-hardware.org/?probe=4cb5f6eae9) | Nov 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [756a8e0f19](https://linux-hardware.org/?probe=756a8e0f19) | Nov 17, 2023 |
| Gigabyte      | J1900M-D2P                  | [d7673aaf5a](https://linux-hardware.org/?probe=d7673aaf5a) | Nov 17, 2023 |
| MSI           | Z97 GAMING 7                | [739c27fcff](https://linux-hardware.org/?probe=739c27fcff) | Nov 17, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [f072eeb8d6](https://linux-hardware.org/?probe=f072eeb8d6) | Nov 17, 2023 |
| ASUSTek       | H170 PRO GAMING             | [8274f1048a](https://linux-hardware.org/?probe=8274f1048a) | Nov 16, 2023 |
| MSI           | PRO B650-P WIFI             | [19753f50b2](https://linux-hardware.org/?probe=19753f50b2) | Nov 16, 2023 |
| AZW           | SEi                         | [03993012e9](https://linux-hardware.org/?probe=03993012e9) | Nov 16, 2023 |
| Dell          | 0478VN A00                  | [d2b8c293ea](https://linux-hardware.org/?probe=d2b8c293ea) | Nov 16, 2023 |
| ASUSTek       | A88XM-PLUS                  | [c951dffd5f](https://linux-hardware.org/?probe=c951dffd5f) | Nov 15, 2023 |
| ASUSTek       | A88XM-PLUS                  | [cc83fead4c](https://linux-hardware.org/?probe=cc83fead4c) | Nov 15, 2023 |
| ASUSTek       | M4A88T-M                    | [0c9c1b8513](https://linux-hardware.org/?probe=0c9c1b8513) | Nov 15, 2023 |
| ASUSTek       | P5G41T-M                    | [5ee5424fe6](https://linux-hardware.org/?probe=5ee5424fe6) | Nov 15, 2023 |
| ASUSTek       | AM1M-A                      | [4029b9094e](https://linux-hardware.org/?probe=4029b9094e) | Nov 15, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | [173b320fd8](https://linux-hardware.org/?probe=173b320fd8) | Nov 14, 2023 |
| Alienware     | 0P0JWX A00                  | [06fd25c3b5](https://linux-hardware.org/?probe=06fd25c3b5) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [9503e14877](https://linux-hardware.org/?probe=9503e14877) | Nov 14, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [1c989dab38](https://linux-hardware.org/?probe=1c989dab38) | Nov 14, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [c15516679b](https://linux-hardware.org/?probe=c15516679b) | Nov 14, 2023 |
| ASUSTek       | W580/SYS                    | [31a696a5bc](https://linux-hardware.org/?probe=31a696a5bc) | Nov 14, 2023 |
| Gigabyte      | H77N-WIFI                   | [c33072abbc](https://linux-hardware.org/?probe=c33072abbc) | Nov 14, 2023 |
| Gigabyte      | Z77MX-D3H                   | [121f68381f](https://linux-hardware.org/?probe=121f68381f) | Nov 14, 2023 |
| Gigabyte      | J1900M-D2P                  | [95eda79d27](https://linux-hardware.org/?probe=95eda79d27) | Nov 14, 2023 |
| eMachines     | EMCP73VT-PM                 | [cd7b8b7a84](https://linux-hardware.org/?probe=cd7b8b7a84) | Nov 14, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [2ed7720fa6](https://linux-hardware.org/?probe=2ed7720fa6) | Nov 13, 2023 |
| Gigabyte      | B650M K                     | [8abd967216](https://linux-hardware.org/?probe=8abd967216) | Nov 13, 2023 |
| HP            | 339B                        | [a3b2a52a12](https://linux-hardware.org/?probe=a3b2a52a12) | Nov 13, 2023 |
| MSI           | B350 GAMING PLUS            | [ffb3d9547e](https://linux-hardware.org/?probe=ffb3d9547e) | Nov 13, 2023 |
| MSI           | B350 GAMING PLUS            | [fb5cb725d6](https://linux-hardware.org/?probe=fb5cb725d6) | Nov 13, 2023 |
| ASUSTek       | P7P55D PRO                  | [9d6ebd2770](https://linux-hardware.org/?probe=9d6ebd2770) | Nov 13, 2023 |
| Unknown       | T3 MRD                      | [ae1a1c1e9b](https://linux-hardware.org/?probe=ae1a1c1e9b) | Nov 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6dac6c11a3](https://linux-hardware.org/?probe=6dac6c11a3) | Nov 13, 2023 |
| ASRock        | 890GM Pro3                  | [a88696f0e2](https://linux-hardware.org/?probe=a88696f0e2) | Nov 13, 2023 |
| Gigabyte      | H610M S2H DDR4              | [ec1ca3afc1](https://linux-hardware.org/?probe=ec1ca3afc1) | Nov 12, 2023 |
| MSI           | 880GMA-E35                  | [a03280c10b](https://linux-hardware.org/?probe=a03280c10b) | Nov 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [018fda89b5](https://linux-hardware.org/?probe=018fda89b5) | Nov 12, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [79accb8ead](https://linux-hardware.org/?probe=79accb8ead) | Nov 12, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [edf208cfd3](https://linux-hardware.org/?probe=edf208cfd3) | Nov 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [4779217105](https://linux-hardware.org/?probe=4779217105) | Nov 11, 2023 |
| eMachines     | EL1360G                     | [9929beb9eb](https://linux-hardware.org/?probe=9929beb9eb) | Nov 11, 2023 |
| ASUSTek       | P8Z77-V                     | [5fcc1a42c3](https://linux-hardware.org/?probe=5fcc1a42c3) | Nov 11, 2023 |
| HP            | 8459                        | [af904894a6](https://linux-hardware.org/?probe=af904894a6) | Nov 11, 2023 |
| ASUSTek       | P8Z77-V LX                  | [dd321d1fb2](https://linux-hardware.org/?probe=dd321d1fb2) | Nov 11, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [687a21becc](https://linux-hardware.org/?probe=687a21becc) | Nov 11, 2023 |
| Gigabyte      | AB350M-D3H-CF               | [a52b5d73c3](https://linux-hardware.org/?probe=a52b5d73c3) | Nov 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [4859d7ce93](https://linux-hardware.org/?probe=4859d7ce93) | Nov 10, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [5cc12c788a](https://linux-hardware.org/?probe=5cc12c788a) | Nov 10, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [9fcef5c1ff](https://linux-hardware.org/?probe=9fcef5c1ff) | Nov 10, 2023 |
| Loongson      | LS3A6000-7A2000-1w-V0.1-... | [ea4b644bef](https://linux-hardware.org/?probe=ea4b644bef) | Nov 10, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [c34342b820](https://linux-hardware.org/?probe=c34342b820) | Nov 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [ca677ba9c3](https://linux-hardware.org/?probe=ca677ba9c3) | Nov 10, 2023 |
| ASUSTek       | PHOENIX                     | [6d2ed74abd](https://linux-hardware.org/?probe=6d2ed74abd) | Nov 10, 2023 |
| MSI           | Z97 GAMING 7                | [0e9b33eef5](https://linux-hardware.org/?probe=0e9b33eef5) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [f1d0c200c0](https://linux-hardware.org/?probe=f1d0c200c0) | Nov 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d1f66b6c6](https://linux-hardware.org/?probe=9d1f66b6c6) | Nov 09, 2023 |
| ASUSTek       | PRIME X570-PRO              | [107047edc5](https://linux-hardware.org/?probe=107047edc5) | Nov 09, 2023 |
| Gigabyte      | A520I AC                    | [5a4538afb3](https://linux-hardware.org/?probe=5a4538afb3) | Nov 09, 2023 |
| Gigabyte      | A520M DS3H                  | [431101ce2f](https://linux-hardware.org/?probe=431101ce2f) | Nov 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [5c243dae6b](https://linux-hardware.org/?probe=5c243dae6b) | Nov 09, 2023 |
| MSI           | B450M MORTAR                | [838e2f455b](https://linux-hardware.org/?probe=838e2f455b) | Nov 09, 2023 |
| Gigabyte      | J1900M-D2P                  | [b1610ff76c](https://linux-hardware.org/?probe=b1610ff76c) | Nov 09, 2023 |
| HP            | 83E9                        | [77c04a83a4](https://linux-hardware.org/?probe=77c04a83a4) | Nov 09, 2023 |
| Dell          | 0101XX A00                  | [da57698f7d](https://linux-hardware.org/?probe=da57698f7d) | Nov 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [27e7e9866d](https://linux-hardware.org/?probe=27e7e9866d) | Nov 09, 2023 |
| Dell          | 02YYK5 A01                  | [e475e8c7d9](https://linux-hardware.org/?probe=e475e8c7d9) | Nov 08, 2023 |
| Gigabyte      | H610M S2H DDR4              | [3f45bd8f8d](https://linux-hardware.org/?probe=3f45bd8f8d) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [978f54c17b](https://linux-hardware.org/?probe=978f54c17b) | Nov 08, 2023 |
| Dell          | 0YJMC0 A02                  | [7a1de78213](https://linux-hardware.org/?probe=7a1de78213) | Nov 08, 2023 |
| Dell          | 0YJMC0 A02                  | [57fb2a4f18](https://linux-hardware.org/?probe=57fb2a4f18) | Nov 08, 2023 |
| ASUSTek       | Z170-K                      | [e83f07f0c3](https://linux-hardware.org/?probe=e83f07f0c3) | Nov 08, 2023 |
| MSI           | H110M ECO                   | [850e3ac421](https://linux-hardware.org/?probe=850e3ac421) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [17d6ddf22a](https://linux-hardware.org/?probe=17d6ddf22a) | Nov 08, 2023 |
| ASRock        | Z68 Pro3                    | [dbe90ad5d6](https://linux-hardware.org/?probe=dbe90ad5d6) | Nov 08, 2023 |
| ASRock        | X670E Taichi Carrara        | [3436cc704a](https://linux-hardware.org/?probe=3436cc704a) | Nov 08, 2023 |
| ASRock        | 890GM Pro3                  | [e00099e8c5](https://linux-hardware.org/?probe=e00099e8c5) | Nov 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [9e3d070f39](https://linux-hardware.org/?probe=9e3d070f39) | Nov 08, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [eb9b1302fd](https://linux-hardware.org/?probe=eb9b1302fd) | Nov 08, 2023 |
| ASRock        | B550M-C                     | [7d79d732ed](https://linux-hardware.org/?probe=7d79d732ed) | Nov 08, 2023 |
| EVGA          | X299 DARK                   | [1fe3dbc8cc](https://linux-hardware.org/?probe=1fe3dbc8cc) | Nov 08, 2023 |
| MSI           | Z370-A PRO                  | [e79bc70a0d](https://linux-hardware.org/?probe=e79bc70a0d) | Nov 07, 2023 |
| ASUSTek       | Z170-K                      | [4f31a7817f](https://linux-hardware.org/?probe=4f31a7817f) | Nov 07, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [655da69777](https://linux-hardware.org/?probe=655da69777) | Nov 07, 2023 |
| MSI           | X99A RAIDER                 | [722c36be7f](https://linux-hardware.org/?probe=722c36be7f) | Nov 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [d63435f6d0](https://linux-hardware.org/?probe=d63435f6d0) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [980eb7c13d](https://linux-hardware.org/?probe=980eb7c13d) | Nov 06, 2023 |
| Lenovo        | 3750 SDK0T76461 WIN 3422... | [995234c08b](https://linux-hardware.org/?probe=995234c08b) | Nov 06, 2023 |
| MSI           | H55M-E33                    | [09ba697574](https://linux-hardware.org/?probe=09ba697574) | Nov 06, 2023 |
| MSI           | A88XM-E35                   | [c7d6ab1d5a](https://linux-hardware.org/?probe=c7d6ab1d5a) | Nov 06, 2023 |
| Dell          | 05GD68 A00                  | [222146ef15](https://linux-hardware.org/?probe=222146ef15) | Nov 06, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [d57d789e77](https://linux-hardware.org/?probe=d57d789e77) | Nov 06, 2023 |
| MSI           | X99A RAIDER                 | [3a2a72df26](https://linux-hardware.org/?probe=3a2a72df26) | Nov 06, 2023 |
| ASRock        | X670E Taichi                | [6f05d717db](https://linux-hardware.org/?probe=6f05d717db) | Nov 05, 2023 |
| ASRock        | X670E Taichi                | [a366b27921](https://linux-hardware.org/?probe=a366b27921) | Nov 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [05a8c22a35](https://linux-hardware.org/?probe=05a8c22a35) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e1d50d8743](https://linux-hardware.org/?probe=e1d50d8743) | Nov 05, 2023 |
| Dell          | 0VNP2H A00                  | [98439489ad](https://linux-hardware.org/?probe=98439489ad) | Nov 05, 2023 |
| HP            | 1494                        | [93e0e0302f](https://linux-hardware.org/?probe=93e0e0302f) | Nov 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [4998a82a6b](https://linux-hardware.org/?probe=4998a82a6b) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-A II            | [539d8551fc](https://linux-hardware.org/?probe=539d8551fc) | Nov 05, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [a9ad2b542a](https://linux-hardware.org/?probe=a9ad2b542a) | Nov 05, 2023 |
| Pegatron      | 2AD5                        | [f8860a91a3](https://linux-hardware.org/?probe=f8860a91a3) | Nov 05, 2023 |
| Gigabyte      | B550M S2H                   | [7fb9150b16](https://linux-hardware.org/?probe=7fb9150b16) | Nov 04, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | [8edaffcccb](https://linux-hardware.org/?probe=8edaffcccb) | Nov 04, 2023 |
| Unknown       | Unknown                     | [50949c6e51](https://linux-hardware.org/?probe=50949c6e51) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | [2ab63a2fb6](https://linux-hardware.org/?probe=2ab63a2fb6) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [a3eb4c9d76](https://linux-hardware.org/?probe=a3eb4c9d76) | Nov 04, 2023 |
| ASUSTek       | H81M-C                      | [cfb51ce306](https://linux-hardware.org/?probe=cfb51ce306) | Nov 03, 2023 |
| HP            | 859C                        | [7928158950](https://linux-hardware.org/?probe=7928158950) | Nov 03, 2023 |
| Gigabyte      | G41MT-D3                    | [3a4be91563](https://linux-hardware.org/?probe=3a4be91563) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | [3618f2a4b5](https://linux-hardware.org/?probe=3618f2a4b5) | Nov 03, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [b58b97e74a](https://linux-hardware.org/?probe=b58b97e74a) | Nov 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bbe345cd5d](https://linux-hardware.org/?probe=bbe345cd5d) | Nov 02, 2023 |
| ASRock        | B760M PG SONIC WiFi         | [71e1e69f30](https://linux-hardware.org/?probe=71e1e69f30) | Nov 02, 2023 |
| MSI           | IONA                        | [579757d1cf](https://linux-hardware.org/?probe=579757d1cf) | Nov 02, 2023 |
| MSI           | B450M MORTAR MAX            | [960c1dbbd2](https://linux-hardware.org/?probe=960c1dbbd2) | Nov 01, 2023 |
| ASUSTek       | M52AD_M12AD                 | [a75715ee4a](https://linux-hardware.org/?probe=a75715ee4a) | Nov 01, 2023 |
| ASRock        | H97M Anniversary            | [6c66e3862d](https://linux-hardware.org/?probe=6c66e3862d) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [bb9a00e5b5](https://linux-hardware.org/?probe=bb9a00e5b5) | Nov 01, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [168597b33e](https://linux-hardware.org/?probe=168597b33e) | Nov 01, 2023 |
| HP            | 8767 A                      | [618323a058](https://linux-hardware.org/?probe=618323a058) | Nov 01, 2023 |
| ABIT          | F-I90HD                     | [2d6d01983c](https://linux-hardware.org/?probe=2d6d01983c) | Nov 01, 2023 |
| Gigabyte      | P67A-D3-B3                  | [0c51ffc039](https://linux-hardware.org/?probe=0c51ffc039) | Nov 01, 2023 |
| MSI           | B450M PRO-M2 V2             | [7296b22122](https://linux-hardware.org/?probe=7296b22122) | Oct 31, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [3b79851103](https://linux-hardware.org/?probe=3b79851103) | Oct 31, 2023 |
| Gigabyte      | F2A55M-DS2                  | [069872b404](https://linux-hardware.org/?probe=069872b404) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [3179102373](https://linux-hardware.org/?probe=3179102373) | Oct 31, 2023 |
| MSI           | X570-A PRO                  | [a198e0f9c2](https://linux-hardware.org/?probe=a198e0f9c2) | Oct 30, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [53e53337bb](https://linux-hardware.org/?probe=53e53337bb) | Oct 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [e4d622b76b](https://linux-hardware.org/?probe=e4d622b76b) | Oct 30, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [624a99186e](https://linux-hardware.org/?probe=624a99186e) | Oct 30, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [949a1ab2bb](https://linux-hardware.org/?probe=949a1ab2bb) | Oct 30, 2023 |
| Gigabyte      | B85M-D3V-A                  | [c35ab1031d](https://linux-hardware.org/?probe=c35ab1031d) | Oct 30, 2023 |
| ASRock        | 890GM Pro3                  | [cfeea44315](https://linux-hardware.org/?probe=cfeea44315) | Oct 30, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [e41780f56a](https://linux-hardware.org/?probe=e41780f56a) | Oct 29, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [7d0eb8f922](https://linux-hardware.org/?probe=7d0eb8f922) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | [ff941d75c9](https://linux-hardware.org/?probe=ff941d75c9) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | [307134fa91](https://linux-hardware.org/?probe=307134fa91) | Oct 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [deef4da5dc](https://linux-hardware.org/?probe=deef4da5dc) | Oct 29, 2023 |
| MSI           | PRO B650M-P                 | [521367f574](https://linux-hardware.org/?probe=521367f574) | Oct 29, 2023 |
| ASRock        | X399 Taichi                 | [78ab56301b](https://linux-hardware.org/?probe=78ab56301b) | Oct 29, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [dee4ef8a3b](https://linux-hardware.org/?probe=dee4ef8a3b) | Oct 29, 2023 |
| ASRock        | Z370 Professional Gaming... | [f589e0c914](https://linux-hardware.org/?probe=f589e0c914) | Oct 28, 2023 |
| HP            | 8053                        | [352cc1bad8](https://linux-hardware.org/?probe=352cc1bad8) | Oct 28, 2023 |
| HP            | 8053                        | [25f2c6e830](https://linux-hardware.org/?probe=25f2c6e830) | Oct 28, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | [4562f80268](https://linux-hardware.org/?probe=4562f80268) | Oct 28, 2023 |
| Gigabyte      | Z77-D3H                     | [77541125c0](https://linux-hardware.org/?probe=77541125c0) | Oct 28, 2023 |
| Gigabyte      | D525TUD                     | [944bb2ecb2](https://linux-hardware.org/?probe=944bb2ecb2) | Oct 28, 2023 |
| Gigabyte      | B550 VISION D-P             | [d78b4f6222](https://linux-hardware.org/?probe=d78b4f6222) | Oct 28, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [b18bbae606](https://linux-hardware.org/?probe=b18bbae606) | Oct 27, 2023 |
| HP            | 843F                        | [c39418a5fe](https://linux-hardware.org/?probe=c39418a5fe) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [4eacfc5dd8](https://linux-hardware.org/?probe=4eacfc5dd8) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1cb73bada5](https://linux-hardware.org/?probe=1cb73bada5) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS       | [a576bfd0b1](https://linux-hardware.org/?probe=a576bfd0b1) | Oct 26, 2023 |
| Gigabyte      | B450M DS3H V2               | [3279dc82a1](https://linux-hardware.org/?probe=3279dc82a1) | Oct 26, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [fff464540a](https://linux-hardware.org/?probe=fff464540a) | Oct 26, 2023 |
| Dell          | 0KJCC5 A00                  | [f4f5605117](https://linux-hardware.org/?probe=f4f5605117) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ca40b148a0](https://linux-hardware.org/?probe=ca40b148a0) | Oct 26, 2023 |
| ASRock        | 890GM Pro3                  | [ca2fb95579](https://linux-hardware.org/?probe=ca2fb95579) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [d5afb1c9da](https://linux-hardware.org/?probe=d5afb1c9da) | Oct 25, 2023 |
| Gigabyte      | EP45-DS3L                   | [a3a2c0b74b](https://linux-hardware.org/?probe=a3a2c0b74b) | Oct 25, 2023 |
| HP            | 8433 11                     | [902343e220](https://linux-hardware.org/?probe=902343e220) | Oct 25, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [9207de9b44](https://linux-hardware.org/?probe=9207de9b44) | Oct 25, 2023 |
| Dell          | 0C27VV A02                  | [7a88945a88](https://linux-hardware.org/?probe=7a88945a88) | Oct 25, 2023 |
| Supermicro    | X8SAX                       | [5d90e1af8c](https://linux-hardware.org/?probe=5d90e1af8c) | Oct 25, 2023 |
| ASRock        | FM2A88X+ Killer             | [c9b5ffd5b8](https://linux-hardware.org/?probe=c9b5ffd5b8) | Oct 24, 2023 |
| ASRock        | B450 Pro4                   | [d4a28890a5](https://linux-hardware.org/?probe=d4a28890a5) | Oct 24, 2023 |
| MSI           | B550-A PRO                  | [ed696b1c52](https://linux-hardware.org/?probe=ed696b1c52) | Oct 24, 2023 |
| Gigabyte      | A320M-H-CF                  | [3d211c5277](https://linux-hardware.org/?probe=3d211c5277) | Oct 24, 2023 |
| ASUSTek       | P5Q3                        | [660547e520](https://linux-hardware.org/?probe=660547e520) | Oct 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | [92dbf8615b](https://linux-hardware.org/?probe=92dbf8615b) | Oct 24, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [4e13c711c7](https://linux-hardware.org/?probe=4e13c711c7) | Oct 24, 2023 |
| Acer          | Aspire X1900                | [6454f71562](https://linux-hardware.org/?probe=6454f71562) | Oct 23, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [4440cac740](https://linux-hardware.org/?probe=4440cac740) | Oct 23, 2023 |
| MSI           | X370 SLI PLUS               | [2ac0a2ecc8](https://linux-hardware.org/?probe=2ac0a2ecc8) | Oct 23, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [7c86d9f1e5](https://linux-hardware.org/?probe=7c86d9f1e5) | Oct 23, 2023 |
| ASRock        | D1800M                      | [d31fadd4a5](https://linux-hardware.org/?probe=d31fadd4a5) | Oct 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | [eb9bba4f5c](https://linux-hardware.org/?probe=eb9bba4f5c) | Oct 23, 2023 |
| Gigabyte      | Z77MX-D3H                   | [1f16388df7](https://linux-hardware.org/?probe=1f16388df7) | Oct 23, 2023 |
| MSI           | IONA                        | [e444708510](https://linux-hardware.org/?probe=e444708510) | Oct 22, 2023 |
| AZW           | SER V1                      | [4262bad6c4](https://linux-hardware.org/?probe=4262bad6c4) | Oct 22, 2023 |
| Gigabyte      | G41MT-S2PT                  | [0b67401f8c](https://linux-hardware.org/?probe=0b67401f8c) | Oct 22, 2023 |
| Gigabyte      | G41MT-S2PT                  | [5a2f8368e1](https://linux-hardware.org/?probe=5a2f8368e1) | Oct 22, 2023 |
| MSI           | X99A RAIDER                 | [3ba4cde45a](https://linux-hardware.org/?probe=3ba4cde45a) | Oct 22, 2023 |
| HP            | 83E9                        | [c324d1ee0a](https://linux-hardware.org/?probe=c324d1ee0a) | Oct 22, 2023 |
| HP            | 83E9                        | [8102d00cdc](https://linux-hardware.org/?probe=8102d00cdc) | Oct 22, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [7c383004b6](https://linux-hardware.org/?probe=7c383004b6) | Oct 21, 2023 |
| Gigabyte      | F2A55M-DS2                  | [422e70640a](https://linux-hardware.org/?probe=422e70640a) | Oct 21, 2023 |
| Shenzhen M... | F6BFC                       | [64148c88c0](https://linux-hardware.org/?probe=64148c88c0) | Oct 21, 2023 |
| MSI           | B450M MORTAR MAX            | [c1ad18b5c9](https://linux-hardware.org/?probe=c1ad18b5c9) | Oct 21, 2023 |
| Gigabyte      | B85-HD3                     | [36f840931d](https://linux-hardware.org/?probe=36f840931d) | Oct 21, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [1190f127a2](https://linux-hardware.org/?probe=1190f127a2) | Oct 21, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | [74df5e1893](https://linux-hardware.org/?probe=74df5e1893) | Oct 21, 2023 |
| MSI           | X99A RAIDER                 | [edefe667a4](https://linux-hardware.org/?probe=edefe667a4) | Oct 21, 2023 |
| Packard Be... | IMEDIA S3840                | [3cc1398528](https://linux-hardware.org/?probe=3cc1398528) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [8290e4c160](https://linux-hardware.org/?probe=8290e4c160) | Oct 20, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [2d07542448](https://linux-hardware.org/?probe=2d07542448) | Oct 20, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [984eba244a](https://linux-hardware.org/?probe=984eba244a) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [6bb9b08c6e](https://linux-hardware.org/?probe=6bb9b08c6e) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | [17b8a78644](https://linux-hardware.org/?probe=17b8a78644) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3b1da376dc](https://linux-hardware.org/?probe=3b1da376dc) | Oct 19, 2023 |
| Gigabyte      | B75M-D3V                    | [b02f1b04e3](https://linux-hardware.org/?probe=b02f1b04e3) | Oct 19, 2023 |
| MACHINIST     | X99 G7 V1.0                 | [caca14cc52](https://linux-hardware.org/?probe=caca14cc52) | Oct 19, 2023 |
| MSI           | B550-A PRO                  | [77cf0c3af6](https://linux-hardware.org/?probe=77cf0c3af6) | Oct 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [064dc574bb](https://linux-hardware.org/?probe=064dc574bb) | Oct 18, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [305b104f83](https://linux-hardware.org/?probe=305b104f83) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [0566ab2287](https://linux-hardware.org/?probe=0566ab2287) | Oct 18, 2023 |
| HP            | 2B52                        | [b14a00a196](https://linux-hardware.org/?probe=b14a00a196) | Oct 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [d7ddb794ec](https://linux-hardware.org/?probe=d7ddb794ec) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [bb941b90f8](https://linux-hardware.org/?probe=bb941b90f8) | Oct 18, 2023 |
| Gigabyte      | H77N-WIFI                   | [0c16d31374](https://linux-hardware.org/?probe=0c16d31374) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d531813a7a](https://linux-hardware.org/?probe=d531813a7a) | Oct 18, 2023 |
| Gigabyte      | G41MT-S2PT                  | [e437f5edcb](https://linux-hardware.org/?probe=e437f5edcb) | Oct 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [2530967a90](https://linux-hardware.org/?probe=2530967a90) | Oct 17, 2023 |
| HP            | 1589                        | [9fca3eb994](https://linux-hardware.org/?probe=9fca3eb994) | Oct 17, 2023 |
| AZW           | SER V1                      | [fa5f054ba7](https://linux-hardware.org/?probe=fa5f054ba7) | Oct 17, 2023 |
| AZW           | SER V1                      | [e5c570b755](https://linux-hardware.org/?probe=e5c570b755) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [8422037a50](https://linux-hardware.org/?probe=8422037a50) | Oct 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | [b552badf93](https://linux-hardware.org/?probe=b552badf93) | Oct 17, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [6f8e6d4251](https://linux-hardware.org/?probe=6f8e6d4251) | Oct 17, 2023 |
| MSI           | MS-1T31                     | [2ca507b92f](https://linux-hardware.org/?probe=2ca507b92f) | Oct 17, 2023 |
| ASUSTek       | PRIME H510M-E               | [375e62bbf4](https://linux-hardware.org/?probe=375e62bbf4) | Oct 17, 2023 |
| ASRock        | B365M Pro4                  | [c84d539a84](https://linux-hardware.org/?probe=c84d539a84) | Oct 17, 2023 |
| HP            | 8AB6 SMVB                   | [e88f9153df](https://linux-hardware.org/?probe=e88f9153df) | Oct 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [3f87e6216a](https://linux-hardware.org/?probe=3f87e6216a) | Oct 16, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [01bccdaf20](https://linux-hardware.org/?probe=01bccdaf20) | Oct 16, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [bc4d536f22](https://linux-hardware.org/?probe=bc4d536f22) | Oct 16, 2023 |
| MSI           | PRO B650-P WIFI             | [55d07d6ee2](https://linux-hardware.org/?probe=55d07d6ee2) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | [66c28b84cf](https://linux-hardware.org/?probe=66c28b84cf) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | [982543f4bc](https://linux-hardware.org/?probe=982543f4bc) | Oct 16, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [70c2d315e0](https://linux-hardware.org/?probe=70c2d315e0) | Oct 16, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [453546268b](https://linux-hardware.org/?probe=453546268b) | Oct 16, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [d294330c51](https://linux-hardware.org/?probe=d294330c51) | Oct 16, 2023 |
| ASRock        | A320M-HDV R4.0              | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [37983381b0](https://linux-hardware.org/?probe=37983381b0) | Oct 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [6082a5c0de](https://linux-hardware.org/?probe=6082a5c0de) | Oct 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5330b349cb](https://linux-hardware.org/?probe=5330b349cb) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [8bbdd141fe](https://linux-hardware.org/?probe=8bbdd141fe) | Oct 15, 2023 |
| HP            | 1589                        | [88e5bbcc5a](https://linux-hardware.org/?probe=88e5bbcc5a) | Oct 15, 2023 |
| MSI           | PRO B660M-P DDR4            | [364fd8849a](https://linux-hardware.org/?probe=364fd8849a) | Oct 15, 2023 |
| Gigabyte      | J1900M-D2P                  | [27881eaaac](https://linux-hardware.org/?probe=27881eaaac) | Oct 15, 2023 |
| Dell          | 0TY915                      | [8ebe2fefc1](https://linux-hardware.org/?probe=8ebe2fefc1) | Oct 15, 2023 |
| Dell          | 0TY915                      | [736f520474](https://linux-hardware.org/?probe=736f520474) | Oct 15, 2023 |
| ASRock        | A320M-DGS                   | [a9599537b8](https://linux-hardware.org/?probe=a9599537b8) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | [7e4e4b6a5d](https://linux-hardware.org/?probe=7e4e4b6a5d) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | [b5d7147862](https://linux-hardware.org/?probe=b5d7147862) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | [642ecadbd2](https://linux-hardware.org/?probe=642ecadbd2) | Oct 15, 2023 |
| Dell          | 0Y2K8N A01                  | [32a0d75e98](https://linux-hardware.org/?probe=32a0d75e98) | Oct 14, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [70b85fc17d](https://linux-hardware.org/?probe=70b85fc17d) | Oct 14, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a86fd4e1d](https://linux-hardware.org/?probe=0a86fd4e1d) | Oct 14, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [039e898b5d](https://linux-hardware.org/?probe=039e898b5d) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [2edd75be93](https://linux-hardware.org/?probe=2edd75be93) | Oct 13, 2023 |
| ASRock        | B450M Pro4                  | [01e717042e](https://linux-hardware.org/?probe=01e717042e) | Oct 13, 2023 |
| ASRock        | H87 Performance             | [5d1713de03](https://linux-hardware.org/?probe=5d1713de03) | Oct 13, 2023 |
| AMI           | Intel                       | [888a4e1a0f](https://linux-hardware.org/?probe=888a4e1a0f) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f24ebc31a5](https://linux-hardware.org/?probe=f24ebc31a5) | Oct 13, 2023 |
| Dell          | 0WR7PY A03                  | [f59286c03f](https://linux-hardware.org/?probe=f59286c03f) | Oct 13, 2023 |
| HP            | 802F                        | [ed3a09f912](https://linux-hardware.org/?probe=ed3a09f912) | Oct 12, 2023 |
| HP            | 802F                        | [c2b0f9720e](https://linux-hardware.org/?probe=c2b0f9720e) | Oct 12, 2023 |
| MSI           | A68HM-E33                   | [71c8888ea4](https://linux-hardware.org/?probe=71c8888ea4) | Oct 12, 2023 |
| Gigabyte      | X570S UD                    | [c7b68dbfe1](https://linux-hardware.org/?probe=c7b68dbfe1) | Oct 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [b71efdb817](https://linux-hardware.org/?probe=b71efdb817) | Oct 11, 2023 |
| HP            | 843B                        | [652027900b](https://linux-hardware.org/?probe=652027900b) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [2e77fb6729](https://linux-hardware.org/?probe=2e77fb6729) | Oct 11, 2023 |
| ASRock        | B550 Steel Legend           | [c699787ab8](https://linux-hardware.org/?probe=c699787ab8) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [fa0785421a](https://linux-hardware.org/?probe=fa0785421a) | Oct 11, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [3ceccfff97](https://linux-hardware.org/?probe=3ceccfff97) | Oct 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [9b5d4b21a7](https://linux-hardware.org/?probe=9b5d4b21a7) | Oct 11, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a8028e0998](https://linux-hardware.org/?probe=a8028e0998) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5566e985cf](https://linux-hardware.org/?probe=5566e985cf) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [69f9b41478](https://linux-hardware.org/?probe=69f9b41478) | Oct 11, 2023 |
| MSI           | B450I GAMING PLUS AC        | [b1ff58e369](https://linux-hardware.org/?probe=b1ff58e369) | Oct 10, 2023 |
| Gigabyte      | J1900M-D2P                  | [8091bb0ceb](https://linux-hardware.org/?probe=8091bb0ceb) | Oct 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [19f6294d43](https://linux-hardware.org/?probe=19f6294d43) | Oct 10, 2023 |
| HP            | 89B5 A                      | [746fef0fc7](https://linux-hardware.org/?probe=746fef0fc7) | Oct 10, 2023 |
| ASRock        | B365M IB-R                  | [c1ac8c374a](https://linux-hardware.org/?probe=c1ac8c374a) | Oct 10, 2023 |
| Techvision    | TVI7309X B0                 | [5954b70bb9](https://linux-hardware.org/?probe=5954b70bb9) | Oct 10, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | [107d1f4d14](https://linux-hardware.org/?probe=107d1f4d14) | Oct 09, 2023 |
| MSI           | A320M-A PRO                 | [4a1888b421](https://linux-hardware.org/?probe=4a1888b421) | Oct 09, 2023 |
| Dell          | 0478VN A00                  | [8881cc216c](https://linux-hardware.org/?probe=8881cc216c) | Oct 09, 2023 |
| Dell          | 0DF42J A00                  | [830730801b](https://linux-hardware.org/?probe=830730801b) | Oct 09, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [7aa0b01da6](https://linux-hardware.org/?probe=7aa0b01da6) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [b249985c20](https://linux-hardware.org/?probe=b249985c20) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [90b88ff378](https://linux-hardware.org/?probe=90b88ff378) | Oct 09, 2023 |
| Gigabyte      | B550M DS3H                  | [7070641150](https://linux-hardware.org/?probe=7070641150) | Oct 08, 2023 |
| Gigabyte      | F2A55M-DS2                  | [dd44b0dc9e](https://linux-hardware.org/?probe=dd44b0dc9e) | Oct 08, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [26708ac497](https://linux-hardware.org/?probe=26708ac497) | Oct 08, 2023 |
| Gigabyte      | H310M S2H x.x               | [fd3c1d1196](https://linux-hardware.org/?probe=fd3c1d1196) | Oct 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [b04266e656](https://linux-hardware.org/?probe=b04266e656) | Oct 08, 2023 |
| Gigabyte      | B550 VISION D-P             | [b0a2980430](https://linux-hardware.org/?probe=b0a2980430) | Oct 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [d43dc626c0](https://linux-hardware.org/?probe=d43dc626c0) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [998f01f73b](https://linux-hardware.org/?probe=998f01f73b) | Oct 08, 2023 |
| HP            | 158A                        | [a1c0d51b9d](https://linux-hardware.org/?probe=a1c0d51b9d) | Oct 08, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [86f56798dc](https://linux-hardware.org/?probe=86f56798dc) | Oct 07, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [0d980c4a61](https://linux-hardware.org/?probe=0d980c4a61) | Oct 07, 2023 |
| Acer          | Aspire X1900                | [38b7e52e6b](https://linux-hardware.org/?probe=38b7e52e6b) | Oct 06, 2023 |
| Gigabyte      | B85M-D3V-A                  | [1a20748a43](https://linux-hardware.org/?probe=1a20748a43) | Oct 06, 2023 |
| Gigabyte      | H81M-D2V                    | [a41f086304](https://linux-hardware.org/?probe=a41f086304) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [6bf5869cab](https://linux-hardware.org/?probe=6bf5869cab) | Oct 06, 2023 |
| Dell          | 0N4YC8 A00                  | [76c6fdfad6](https://linux-hardware.org/?probe=76c6fdfad6) | Oct 06, 2023 |
| MSI           | B450M MORTAR MAX            | [a2fb75cc3e](https://linux-hardware.org/?probe=a2fb75cc3e) | Oct 06, 2023 |
| Medion        | MS-7707                     | [42bc6357f7](https://linux-hardware.org/?probe=42bc6357f7) | Oct 05, 2023 |
| HP            | 8906 SMVB                   | [010c54ccaf](https://linux-hardware.org/?probe=010c54ccaf) | Oct 05, 2023 |
| Dell          | 0478VN A00                  | [511df57852](https://linux-hardware.org/?probe=511df57852) | Oct 05, 2023 |
| ASUSTek       | P8H67                       | [68e28eea76](https://linux-hardware.org/?probe=68e28eea76) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9948b7ed73](https://linux-hardware.org/?probe=9948b7ed73) | Oct 05, 2023 |
| Dell          | 0N4YC8 A00                  | [fd4fb61bac](https://linux-hardware.org/?probe=fd4fb61bac) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | [d8f9e7b32a](https://linux-hardware.org/?probe=d8f9e7b32a) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | [ae798c007e](https://linux-hardware.org/?probe=ae798c007e) | Oct 05, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [0aa9a5ddc3](https://linux-hardware.org/?probe=0aa9a5ddc3) | Oct 05, 2023 |
| ASRock        | AD2700-ITX                  | [3aea9e7d2f](https://linux-hardware.org/?probe=3aea9e7d2f) | Oct 05, 2023 |
| Shenzhen M... | HX90G                       | [135859015c](https://linux-hardware.org/?probe=135859015c) | Oct 04, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [ca79f8ce4c](https://linux-hardware.org/?probe=ca79f8ce4c) | Oct 04, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [08f5cef7f3](https://linux-hardware.org/?probe=08f5cef7f3) | Oct 04, 2023 |
| ASRock        | B365 Pro4                   | [8e9fff1e35](https://linux-hardware.org/?probe=8e9fff1e35) | Oct 04, 2023 |
| Dell          | 0DF42J A00                  | [a98397577c](https://linux-hardware.org/?probe=a98397577c) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [400e01b1bf](https://linux-hardware.org/?probe=400e01b1bf) | Oct 03, 2023 |
| HP            | 802E                        | [2d84b83c17](https://linux-hardware.org/?probe=2d84b83c17) | Oct 03, 2023 |
| HP            | 802E                        | [10fcb68621](https://linux-hardware.org/?probe=10fcb68621) | Oct 03, 2023 |
| Supermicro    | H8DM8-2                     | [5386350e20](https://linux-hardware.org/?probe=5386350e20) | Oct 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | [b225569c1d](https://linux-hardware.org/?probe=b225569c1d) | Oct 02, 2023 |
| Dell          | 0YJPT1 A00                  | [59f53b1488](https://linux-hardware.org/?probe=59f53b1488) | Oct 02, 2023 |
| Dell          | 07PR60 A01                  | [020c2fbbf8](https://linux-hardware.org/?probe=020c2fbbf8) | Oct 02, 2023 |
| Unknown       | Unknown                     | [1f2e2a6b13](https://linux-hardware.org/?probe=1f2e2a6b13) | Oct 02, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [76c5466daa](https://linux-hardware.org/?probe=76c5466daa) | Oct 02, 2023 |
| Intel         | H110                        | [eaf6f0f81c](https://linux-hardware.org/?probe=eaf6f0f81c) | Oct 02, 2023 |
| Acer          | Aspire X1900                | [5d958ae7d1](https://linux-hardware.org/?probe=5d958ae7d1) | Oct 02, 2023 |
| ASRock        | H370M-ITX/ac                | [cf9e8e26c2](https://linux-hardware.org/?probe=cf9e8e26c2) | Oct 02, 2023 |
| MSI           | X99A RAIDER                 | [5442de3655](https://linux-hardware.org/?probe=5442de3655) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [b27cfa6ad6](https://linux-hardware.org/?probe=b27cfa6ad6) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [45b94d86b5](https://linux-hardware.org/?probe=45b94d86b5) | Oct 02, 2023 |
| ASRock        | B650E PG-ITX WiFi           | [10e1561364](https://linux-hardware.org/?probe=10e1561364) | Oct 01, 2023 |
| MSI           | X470 GAMING PLUS            | [113ab4dbc3](https://linux-hardware.org/?probe=113ab4dbc3) | Oct 01, 2023 |
| ASUSTek       | PRIME B450M-A               | [1e825c5574](https://linux-hardware.org/?probe=1e825c5574) | Oct 01, 2023 |
| MSI           | X99A RAIDER                 | [3e13770075](https://linux-hardware.org/?probe=3e13770075) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | [913e98318d](https://linux-hardware.org/?probe=913e98318d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | [f48a538837](https://linux-hardware.org/?probe=f48a538837) | Oct 01, 2023 |
| ASUSTek       | Z170-DELUXE                 | [9e04efc2d9](https://linux-hardware.org/?probe=9e04efc2d9) | Oct 01, 2023 |
| ASRock        | X570 Taichi                 | [7a670fe0ef](https://linux-hardware.org/?probe=7a670fe0ef) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [f3d279f91b](https://linux-hardware.org/?probe=f3d279f91b) | Sep 30, 2023 |
| ASUSTek       | Z170-A                      | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| MSI           | PRO B660M-A DDR4            | [a7683dc02d](https://linux-hardware.org/?probe=a7683dc02d) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [02af70281a](https://linux-hardware.org/?probe=02af70281a) | Sep 30, 2023 |
| Dell          | 0V8WGR A02                  | [9c9ded765b](https://linux-hardware.org/?probe=9c9ded765b) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [3d40d7878a](https://linux-hardware.org/?probe=3d40d7878a) | Sep 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | [5a507ec4da](https://linux-hardware.org/?probe=5a507ec4da) | Sep 30, 2023 |
| MSI           | X99A RAIDER                 | [a36938e994](https://linux-hardware.org/?probe=a36938e994) | Sep 30, 2023 |
| HP            | 8055                        | [3ddf31c78e](https://linux-hardware.org/?probe=3ddf31c78e) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [74bed86ee5](https://linux-hardware.org/?probe=74bed86ee5) | Sep 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| Intel         | H61                         | [f6a417439c](https://linux-hardware.org/?probe=f6a417439c) | Sep 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| Intel         | H61                         | [e7dac2f9ed](https://linux-hardware.org/?probe=e7dac2f9ed) | Sep 29, 2023 |
| MSI           | PRO B660M-A DDR4            | [4b5a46a1e2](https://linux-hardware.org/?probe=4b5a46a1e2) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60c04875f1](https://linux-hardware.org/?probe=60c04875f1) | Sep 29, 2023 |
| ASUSTek       | PRIME X570-PRO              | [74ec125e88](https://linux-hardware.org/?probe=74ec125e88) | Sep 29, 2023 |
| ASUSTek       | PRIME X570-PRO              | [cc8c6efba3](https://linux-hardware.org/?probe=cc8c6efba3) | Sep 28, 2023 |
| Dell          | 0YJPT1 A00                  | [a0a41d401e](https://linux-hardware.org/?probe=a0a41d401e) | Sep 28, 2023 |
| MSI           | H310M PRO-VD                | [67e14c1b2d](https://linux-hardware.org/?probe=67e14c1b2d) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| Dell          | 0XC7MM A01                  | [9fdfc5a13f](https://linux-hardware.org/?probe=9fdfc5a13f) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [5dbe8e1541](https://linux-hardware.org/?probe=5dbe8e1541) | Sep 28, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [2e3d19e919](https://linux-hardware.org/?probe=2e3d19e919) | Sep 28, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [23150c5bd3](https://linux-hardware.org/?probe=23150c5bd3) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [546df5b57f](https://linux-hardware.org/?probe=546df5b57f) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [503570ad7a](https://linux-hardware.org/?probe=503570ad7a) | Sep 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [4f0651ccc2](https://linux-hardware.org/?probe=4f0651ccc2) | Sep 27, 2023 |
| Gigabyte      | B650M K                     | [73da1b7ade](https://linux-hardware.org/?probe=73da1b7ade) | Sep 27, 2023 |
| ASRock        | B450M Steel Legend          | [b4de4fe266](https://linux-hardware.org/?probe=b4de4fe266) | Sep 27, 2023 |
| Dell          | 0773VG A00                  | [a68caa37d8](https://linux-hardware.org/?probe=a68caa37d8) | Sep 26, 2023 |
| Dell          | 0773VG A00                  | [5e34f7d424](https://linux-hardware.org/?probe=5e34f7d424) | Sep 26, 2023 |
| Gigabyte      | B550M S2H                   | [f61801ddb3](https://linux-hardware.org/?probe=f61801ddb3) | Sep 26, 2023 |
| Gigabyte      | B550M DS3H                  | [3bb1109d44](https://linux-hardware.org/?probe=3bb1109d44) | Sep 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [85c6c01e63](https://linux-hardware.org/?probe=85c6c01e63) | Sep 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [8da87a8c78](https://linux-hardware.org/?probe=8da87a8c78) | Sep 26, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [4b0aff27e8](https://linux-hardware.org/?probe=4b0aff27e8) | Sep 26, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [b49d28bbd4](https://linux-hardware.org/?probe=b49d28bbd4) | Sep 26, 2023 |
| ASRock        | B450M Steel Legend          | [ccb7f736f6](https://linux-hardware.org/?probe=ccb7f736f6) | Sep 26, 2023 |
| Huanan        | X99-8M-F V1.2               | [4ddba514a1](https://linux-hardware.org/?probe=4ddba514a1) | Sep 26, 2023 |
| MSI           | X99A RAIDER                 | [b69e9b97ec](https://linux-hardware.org/?probe=b69e9b97ec) | Sep 26, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [4375a551e1](https://linux-hardware.org/?probe=4375a551e1) | Sep 25, 2023 |
| ASUSTek       | P9D WS                      | [fd2133400d](https://linux-hardware.org/?probe=fd2133400d) | Sep 25, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [a6ef2b5028](https://linux-hardware.org/?probe=a6ef2b5028) | Sep 25, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [b7dae6ef48](https://linux-hardware.org/?probe=b7dae6ef48) | Sep 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [f4d45948eb](https://linux-hardware.org/?probe=f4d45948eb) | Sep 25, 2023 |
| MSI           | X99A RAIDER                 | [c6dc860de5](https://linux-hardware.org/?probe=c6dc860de5) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | [1b8b856469](https://linux-hardware.org/?probe=1b8b856469) | Sep 25, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [23d9e87224](https://linux-hardware.org/?probe=23d9e87224) | Sep 24, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Fedora 38 | 917      | 16.93%  |
| Fedora 36 | 690      | 12.74%  |
| Fedora 37 | 613      | 11.32%  |
| Fedora 33 | 568      | 10.49%  |
| Fedora 35 | 536      | 9.9%    |
| Fedora 34 | 519      | 9.58%   |
| Fedora 32 | 518      | 9.57%   |
| Fedora 39 | 463      | 8.55%   |
| Fedora 31 | 343      | 6.33%   |
| Fedora 30 | 133      | 2.46%   |
| Fedora 29 | 75       | 1.39%   |
| Fedora 28 | 14       | 0.26%   |
| Fedora 40 | 9        | 0.17%   |
| Fedora 27 | 9        | 0.17%   |
| Fedora 25 | 2        | 0.04%   |
| Fedora 24 | 2        | 0.04%   |
| Fedora 4  | 1        | 0.02%   |
| Fedora 21 | 1        | 0.02%   |
| Fedora 17 | 1        | 0.02%   |
| Fedora 14 | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Fedora | 4660     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.2.9-300.fc38.x86_64   | 100      | 1.61%   |
| 6.4.15-200.fc38.x86_64  | 74       | 1.19%   |
| 6.2.15-300.fc38.x86_64  | 72       | 1.16%   |
| 6.3.8-200.fc38.x86_64   | 71       | 1.14%   |
| 6.6.9-200.fc39.x86_64   | 63       | 1.01%   |
| 6.5.5-200.fc38.x86_64   | 60       | 0.96%   |
| 5.9.16-200.fc33.x86_64  | 58       | 0.93%   |
| 5.16.18-200.fc35.x86_64 | 57       | 0.92%   |
| 5.17.5-300.fc36.x86_64  | 52       | 0.84%   |
| 6.5.6-300.fc39.x86_64   | 48       | 0.77%   |
| 6.2.14-300.fc38.x86_64  | 48       | 0.77%   |
| 6.5.11-300.fc39.x86_64  | 47       | 0.76%   |
| 6.6.8-200.fc39.x86_64   | 46       | 0.74%   |
| 6.0.15-300.fc37.x86_64  | 45       | 0.72%   |
| 6.0.12-300.fc37.x86_64  | 44       | 0.71%   |
| 5.18.13-200.fc36.x86_64 | 42       | 0.67%   |
| 6.5.6-200.fc38.x86_64   | 40       | 0.64%   |
| 6.3.12-200.fc38.x86_64  | 40       | 0.64%   |
| 5.19.16-200.fc36.x86_64 | 40       | 0.64%   |
| 5.13.12-200.fc34.x86_64 | 39       | 0.63%   |
| 6.5.7-200.fc38.x86_64   | 38       | 0.61%   |
| 6.0.7-301.fc37.x86_64   | 38       | 0.61%   |
| 6.4.11-200.fc38.x86_64  | 37       | 0.59%   |
| 5.14.10-300.fc35.x86_64 | 37       | 0.59%   |
| 6.5.12-300.fc39.x86_64  | 35       | 0.56%   |
| 6.0.5-200.fc36.x86_64   | 35       | 0.56%   |
| 5.11.12-300.fc34.x86_64 | 35       | 0.56%   |
| 6.6.2-201.fc39.x86_64   | 34       | 0.55%   |
| 5.8.15-301.fc33.x86_64  | 34       | 0.55%   |
| 6.6.11-200.fc39.x86_64  | 33       | 0.53%   |
| 6.2.11-300.fc38.x86_64  | 33       | 0.53%   |
| 6.1.18-200.fc37.x86_64  | 33       | 0.53%   |
| 5.8.4-200.fc32.x86_64   | 33       | 0.53%   |
| 6.6.7-200.fc39.x86_64   | 32       | 0.51%   |
| 6.3.11-200.fc38.x86_64  | 32       | 0.51%   |
| 5.18.16-200.fc36.x86_64 | 32       | 0.51%   |
| 6.5.8-200.fc38.x86_64   | 31       | 0.5%    |
| 6.0.11-300.fc37.x86_64  | 31       | 0.5%    |
| 5.19.9-200.fc36.x86_64  | 31       | 0.5%    |
| 5.18.11-200.fc36.x86_64 | 31       | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.9   | 113      | 1.82%   |
| 6.2.15  | 91       | 1.46%   |
| 6.5.6   | 88       | 1.42%   |
| 6.4.15  | 77       | 1.24%   |
| 6.3.8   | 76       | 1.22%   |
| 6.5.5   | 69       | 1.11%   |
| 6.6.9   | 68       | 1.09%   |
| 5.17.5  | 68       | 1.09%   |
| 5.9.16  | 67       | 1.08%   |
| 5.16.18 | 65       | 1.05%   |
| 6.2.14  | 59       | 0.95%   |
| 5.19.16 | 59       | 0.95%   |
| 6.0.12  | 54       | 0.87%   |
| 5.8.15  | 54       | 0.87%   |
| 6.0.7   | 51       | 0.82%   |
| 6.0.15  | 51       | 0.82%   |
| 6.6.8   | 49       | 0.79%   |
| 6.5.11  | 47       | 0.76%   |
| 5.8.18  | 47       | 0.76%   |
| 5.18.13 | 43       | 0.69%   |
| 6.3.12  | 42       | 0.68%   |
| 6.5.12  | 41       | 0.66%   |
| 6.5.7   | 40       | 0.64%   |
| 5.8.16  | 40       | 0.64%   |
| 5.13.12 | 40       | 0.64%   |
| 6.0.8   | 39       | 0.63%   |
| 5.19.9  | 39       | 0.63%   |
| 5.14.10 | 39       | 0.63%   |
| 6.4.11  | 38       | 0.61%   |
| 6.2.11  | 38       | 0.61%   |
| 6.0.5   | 38       | 0.61%   |
| 6.0.9   | 37       | 0.6%    |
| 5.11.12 | 37       | 0.6%    |
| 5.11.11 | 37       | 0.6%    |
| 6.6.2   | 36       | 0.58%   |
| 6.6.11  | 36       | 0.58%   |
| 6.1.18  | 36       | 0.58%   |
| 5.18.5  | 35       | 0.56%   |
| 6.6.7   | 34       | 0.55%   |
| 6.0.11  | 34       | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 410      | 6.96%   |
| 6.5     | 359      | 6.1%    |
| 6.0     | 359      | 6.1%    |
| 6.6     | 325      | 5.52%   |
| 5.8     | 308      | 5.23%   |
| 6.4     | 296      | 5.03%   |
| 5.11    | 257      | 4.36%   |
| 5.19    | 256      | 4.35%   |
| 5.18    | 252      | 4.28%   |
| 5.17    | 251      | 4.26%   |
| 6.1     | 243      | 4.13%   |
| 6.3     | 227      | 3.86%   |
| 5.16    | 224      | 3.8%    |
| 5.9     | 209      | 3.55%   |
| 5.10    | 206      | 3.5%    |
| 5.14    | 205      | 3.48%   |
| 5.6     | 196      | 3.33%   |
| 5.13    | 191      | 3.24%   |
| 5.15    | 180      | 3.06%   |
| 5.12    | 176      | 2.99%   |
| 5.7     | 171      | 2.9%    |
| 5.4     | 135      | 2.29%   |
| 5.5     | 121      | 2.06%   |
| 5.3     | 116      | 1.97%   |
| 5.2     | 55       | 0.93%   |
| 5.0     | 48       | 0.82%   |
| 5.1     | 25       | 0.42%   |
| 4.19    | 22       | 0.37%   |
| 4.18    | 19       | 0.32%   |
| 4.20    | 18       | 0.31%   |
| 6.7     | 6        | 0.1%    |
| 4.16    | 5        | 0.08%   |
| 4.15    | 3        | 0.05%   |
| 6.8     | 2        | 0.03%   |
| 4.17    | 2        | 0.03%   |
| 4.13    | 2        | 0.03%   |
| 4.11    | 2        | 0.03%   |
| 4.14    | 1        | 0.02%   |
| 4.1     | 1        | 0.02%   |
| 3.9     | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 4654     | 99.85%  |
| i686        | 4        | 0.09%   |
| ppc64le     | 1        | 0.02%   |
| loongarch64 | 1        | 0.02%   |
| Unknown     | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 3245     | 67.66%  |
| KDE5                         | 685      | 14.28%  |
| Unknown                      | 286      | 5.96%   |
| KDE                          | 117      | 2.44%   |
| XFCE                         | 105      | 2.19%   |
| X-Cinnamon                   | 89       | 1.86%   |
| Cinnamon                     | 71       | 1.48%   |
| MATE                         | 66       | 1.38%   |
| GNOME Classic                | 37       | 0.77%   |
| LXQt                         | 13       | 0.27%   |
| LXDE                         | 11       | 0.23%   |
| Deepin                       | 11       | 0.23%   |
| Budgie                       | 11       | 0.23%   |
| i3                           | 10       | 0.21%   |
| sway                         | 7        | 0.15%   |
| KDE4                         | 6        | 0.13%   |
| Hyprland                     | 4        | 0.08%   |
| Xpra                         | 3        | 0.06%   |
| openbox                      | 3        | 0.06%   |
| awesome                      | 3        | 0.06%   |
| qtile                        | 2        | 0.04%   |
| DWM                          | 2        | 0.04%   |
| bspwm                        | 2        | 0.04%   |
| WindowMaker                  | 1        | 0.02%   |
| Pantheon                     | 1        | 0.02%   |
| NsCDE                        | 1        | 0.02%   |
| GNUstep                      | 1        | 0.02%   |
| GNOME Flashback              | 1        | 0.02%   |
| e16-session                  | 1        | 0.02%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 2733     | 55.97%  |
| X11     | 1839     | 37.66%  |
| Tty     | 159      | 3.26%   |
| Unknown | 147      | 3.01%   |
| Web     | 5        | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2784     | 58.04%  |
| GDM     | 1312     | 27.35%  |
| SDDM    | 385      | 8.03%   |
| LightDM | 225      | 4.69%   |
| TDM     | 73       | 1.52%   |
| XDM     | 7        | 0.15%   |
| KDM     | 7        | 0.15%   |
| LXDM    | 3        | 0.06%   |
| SLiM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2224     | 46.91%  |
| en_GB   | 326      | 6.88%   |
| Unknown | 253      | 5.34%   |
| ru_RU   | 238      | 5.02%   |
| pt_BR   | 233      | 4.91%   |
| de_DE   | 223      | 4.7%    |
| en_CA   | 144      | 3.04%   |
| fr_FR   | 143      | 3.02%   |
| en_AU   | 138      | 2.91%   |
| it_IT   | 100      | 2.11%   |
| es_ES   | 79       | 1.67%   |
| pl_PL   | 72       | 1.52%   |
| es_MX   | 34       | 0.72%   |
| cs_CZ   | 33       | 0.7%    |
| en_IN   | 31       | 0.65%   |
| en_NZ   | 25       | 0.53%   |
| es_AR   | 24       | 0.51%   |
| de_AT   | 20       | 0.42%   |
| tr_TR   | 18       | 0.38%   |
| ja_JP   | 18       | 0.38%   |
| es_CO   | 18       | 0.38%   |
| zh_CN   | 17       | 0.36%   |
| nl_NL   | 17       | 0.36%   |
| hu_HU   | 17       | 0.36%   |
| nl_BE   | 16       | 0.34%   |
| fi_FI   | 15       | 0.32%   |
| en_IE   | 15       | 0.32%   |
| sv_SE   | 14       | 0.3%    |
| pt_PT   | 13       | 0.27%   |
| es_CL   | 12       | 0.25%   |
| en_DK   | 12       | 0.25%   |
| C       | 11       | 0.23%   |
| uk_UA   | 10       | 0.21%   |
| fr_BE   | 9        | 0.19%   |
| ru_UA   | 8        | 0.17%   |
| ko_KR   | 8        | 0.17%   |
| fr_CH   | 8        | 0.17%   |
| fr_CA   | 8        | 0.17%   |
| zh_TW   | 6        | 0.13%   |
| sk_SK   | 6        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 3083     | 65.07%  |
| BIOS | 1655     | 34.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 2846     | 59.59%  |
| Ext4                | 1571     | 32.89%  |
| Xfs                 | 205      | 4.29%   |
| Unknown             | 132      | 2.76%   |
| Overlay             | 8        | 0.17%   |
| Zfs                 | 5        | 0.1%    |
| Ext3                | 5        | 0.1%    |
| F2fs                | 2        | 0.04%   |
| Tmpfs               | 1        | 0.02%   |
| Fuse.fuse-overlayfs | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2712     | 56.49%  |
| GPT     | 1694     | 35.28%  |
| MBR     | 395      | 8.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4080     | 85.48%  |
| Yes       | 693      | 14.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3773     | 79.6%   |
| Yes       | 967      | 20.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1342     | 28.8%   |
| Gigabyte Technology                  | 882      | 18.93%  |
| MSI                                  | 737      | 15.82%  |
| ASRock                               | 471      | 10.11%  |
| Dell                                 | 320      | 6.87%   |
| Hewlett-Packard                      | 262      | 5.62%   |
| Lenovo                               | 136      | 2.92%   |
| Intel                                | 76       | 1.63%   |
| Unknown                              | 55       | 1.18%   |
| Acer                                 | 45       | 0.97%   |
| Pegatron                             | 30       | 0.64%   |
| Fujitsu                              | 21       | 0.45%   |
| Huanan                               | 20       | 0.43%   |
| Biostar                              | 20       | 0.43%   |
| ECS                                  | 17       | 0.36%   |
| BESSTAR Tech                         | 16       | 0.34%   |
| Foxconn                              | 15       | 0.32%   |
| Apple                                | 14       | 0.3%    |
| Supermicro                           | 13       | 0.28%   |
| AZW                                  | 12       | 0.26%   |
| Alienware                            | 10       | 0.21%   |
| Positivo                             | 9        | 0.19%   |
| Shuttle                              | 8        | 0.17%   |
| Itautec                              | 8        | 0.17%   |
| Medion                               | 7        | 0.15%   |
| Shenzhen Meigao Electronic Equipment | 6        | 0.13%   |
| PCWare                               | 6        | 0.13%   |
| Packard Bell                         | 6        | 0.13%   |
| EVGA                                 | 6        | 0.13%   |
| AMI                                  | 6        | 0.13%   |
| MACHINIST                            | 5        | 0.11%   |
| eMachines                            | 5        | 0.11%   |
| System76                             | 4        | 0.09%   |
| ABIT                                 | 4        | 0.09%   |
| ZOTAC                                | 3        | 0.06%   |
| OEM                                  | 3        | 0.06%   |
| NZXT                                 | 3        | 0.06%   |
| Colorful Technology                  | 3        | 0.06%   |
| AMD                                  | 3        | 0.06%   |
| XFX                                  | 2        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 129      | 2.77%   |
| Unknown                        | 58       | 1.24%   |
| MSI MS-7C37                    | 49       | 1.05%   |
| ASUS TUF Gaming X570-PLUS      | 36       | 0.77%   |
| Dell OptiPlex 7010             | 30       | 0.64%   |
| MSI MS-7C02                    | 27       | 0.58%   |
| Gigabyte B450M DS3H            | 27       | 0.58%   |
| MSI MS-7A38                    | 26       | 0.56%   |
| MSI MS-7C91                    | 24       | 0.52%   |
| MSI MS-7C56                    | 24       | 0.52%   |
| MSI MS-7B86                    | 21       | 0.45%   |
| Dell OptiPlex 9020             | 21       | 0.45%   |
| ASUS ROG STRIX B550-F GAMING   | 21       | 0.45%   |
| MSI MS-7B89                    | 20       | 0.43%   |
| MSI MS-7B79                    | 20       | 0.43%   |
| MSI MS-7C95                    | 17       | 0.36%   |
| Gigabyte 970A-DS3P             | 17       | 0.36%   |
| ASUS ROG STRIX X570-F GAMING   | 17       | 0.36%   |
| ASRock B450M Pro4              | 17       | 0.36%   |
| Gigabyte B450 AORUS ELITE      | 16       | 0.34%   |
| ASUS ROG STRIX B550-I GAMING   | 16       | 0.34%   |
| MSI MS-7C52                    | 15       | 0.32%   |
| Gigabyte X570 I AORUS PRO WIFI | 15       | 0.32%   |
| ASUS ROG STRIX B450-F GAMING   | 15       | 0.32%   |
| ASUS PRIME X370-PRO            | 15       | 0.32%   |
| ASUS PRIME A320M-K             | 15       | 0.32%   |
| MSI MS-7C84                    | 14       | 0.3%    |
| Gigabyte A320M-S2H             | 14       | 0.3%    |
| Dell OptiPlex 3020             | 14       | 0.3%    |
| ASUS TUF Gaming B550M-PLUS     | 14       | 0.3%    |
| ASUS TUF Gaming B550-PLUS      | 14       | 0.3%    |
| ASUS ROG STRIX X570-E GAMING   | 14       | 0.3%    |
| ASUS PRIME X470-PRO            | 14       | 0.3%    |
| MSI MS-7A34                    | 13       | 0.28%   |
| Gigabyte B550M DS3H            | 13       | 0.28%   |
| Gigabyte B550I AORUS PRO AX    | 13       | 0.28%   |
| ASRock B450 Pro4               | 13       | 0.28%   |
| Gigabyte X570 AORUS ELITE      | 12       | 0.26%   |
| Gigabyte B450 AORUS M          | 12       | 0.26%   |
| ASUS ROG CROSSHAIR VII HERO    | 12       | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 283      | 6.07%   |
| ASUS ROG               | 277      | 5.94%   |
| Dell OptiPlex          | 179      | 3.84%   |
| ASUS TUF               | 171      | 3.67%   |
| ASUS All               | 129      | 2.77%   |
| Lenovo ThinkCentre     | 74       | 1.59%   |
| Gigabyte X570          | 73       | 1.57%   |
| HP Compaq              | 62       | 1.33%   |
| Unknown                | 58       | 1.24%   |
| Dell Precision         | 54       | 1.16%   |
| Gigabyte B450          | 52       | 1.12%   |
| MSI MS-7C37            | 49       | 1.05%   |
| HP EliteDesk           | 48       | 1.03%   |
| Gigabyte B450M         | 47       | 1.01%   |
| Gigabyte B550          | 40       | 0.86%   |
| Dell Inspiron          | 36       | 0.77%   |
| ASRock B450M           | 36       | 0.77%   |
| ASRock X570            | 32       | 0.69%   |
| Acer Aspire            | 30       | 0.64%   |
| HP ProDesk             | 29       | 0.62%   |
| Gigabyte B550M         | 29       | 0.62%   |
| Dell XPS               | 29       | 0.62%   |
| MSI MS-7C02            | 27       | 0.58%   |
| MSI MS-7A38            | 26       | 0.56%   |
| ASRock B450            | 26       | 0.56%   |
| MSI MS-7C91            | 24       | 0.52%   |
| MSI MS-7C56            | 24       | 0.52%   |
| ASUS P8Z77-V           | 22       | 0.47%   |
| MSI MS-7B86            | 21       | 0.45%   |
| MSI MS-7B89            | 20       | 0.43%   |
| MSI MS-7B79            | 20       | 0.43%   |
| Lenovo ThinkStation    | 19       | 0.41%   |
| Gigabyte 970A-DS3P     | 18       | 0.39%   |
| ASUS Maximus           | 18       | 0.39%   |
| MSI MS-7C95            | 17       | 0.36%   |
| Gigabyte A320M-S2H     | 17       | 0.36%   |
| ASUS SABERTOOTH        | 17       | 0.36%   |
| Gigabyte Z390          | 16       | 0.34%   |
| Gigabyte GA-78LMT-USB3 | 16       | 0.34%   |
| ASUS ProArt            | 16       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 623      | 13.37%  |
| 2019    | 519      | 11.14%  |
| 2020    | 508      | 10.9%   |
| 2017    | 364      | 7.81%   |
| 2012    | 345      | 7.4%    |
| 2021    | 320      | 6.87%   |
| 2013    | 310      | 6.65%   |
| 2014    | 284      | 6.09%   |
| 2022    | 219      | 4.7%    |
| 2011    | 217      | 4.66%   |
| 2015    | 206      | 4.42%   |
| 2016    | 200      | 4.29%   |
| 2010    | 149      | 3.2%    |
| 2009    | 146      | 3.13%   |
| 2008    | 101      | 2.17%   |
| 2023    | 68       | 1.46%   |
| 2007    | 50       | 1.07%   |
| 2006    | 22       | 0.47%   |
| 2005    | 5        | 0.11%   |
| Unknown | 4        | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4660     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4314     | 91.61%  |
| Enabled  | 395      | 8.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4658     | 99.96%  |
| Yes  | 2        | 0.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1437     | 30.01%  |
| 32.01-64.0      | 1118     | 23.35%  |
| 8.01-16.0       | 767      | 16.02%  |
| 4.01-8.0        | 520      | 10.86%  |
| 64.01-256.0     | 419      | 8.75%   |
| 3.01-4.0        | 276      | 5.76%   |
| 24.01-32.0      | 198      | 4.14%   |
| 1.01-2.0        | 24       | 0.5%    |
| 2.01-3.0        | 21       | 0.44%   |
| Unknown         | 4        | 0.08%   |
| More than 256.0 | 3        | 0.06%   |
| 0.51-1.0        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1570     | 29.1%   |
| 2.01-3.0    | 1330     | 24.65%  |
| 3.01-4.0    | 1106     | 20.5%   |
| 1.01-2.0    | 652      | 12.09%  |
| 8.01-16.0   | 499      | 9.25%   |
| 16.01-24.0  | 93       | 1.72%   |
| 0.51-1.0    | 70       | 1.3%    |
| 24.01-32.0  | 34       | 0.63%   |
| 32.01-64.0  | 19       | 0.35%   |
| 0.01-0.5    | 13       | 0.24%   |
| Unknown     | 6        | 0.11%   |
| 64.01-256.0 | 3        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 1534     | 30.95%  |
| 1      | 1388     | 28%     |
| 3      | 984      | 19.85%  |
| 4      | 510      | 10.29%  |
| 5      | 266      | 5.37%   |
| 6      | 128      | 2.58%   |
| 7      | 61       | 1.23%   |
| 8      | 33       | 0.67%   |
| 9      | 14       | 0.28%   |
| 0      | 12       | 0.24%   |
| 10     | 8        | 0.16%   |
| 11     | 6        | 0.12%   |
| 12     | 4        | 0.08%   |
| 15     | 2        | 0.04%   |
| 14     | 2        | 0.04%   |
| 410    | 1        | 0.02%   |
| 27     | 1        | 0.02%   |
| 24     | 1        | 0.02%   |
| 18     | 1        | 0.02%   |
| 13     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3119     | 66.04%  |
| Yes       | 1604     | 33.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4623     | 99.18%  |
| No        | 38       | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2377     | 50.18%  |
| Yes       | 2360     | 49.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2690     | 56.61%  |
| Yes       | 2062     | 43.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 1102     | 23.5%   |
| Germany     | 366      | 7.81%   |
| Brazil      | 345      | 7.36%   |
| Russia      | 299      | 6.38%   |
| Canada      | 195      | 4.16%   |
| UK          | 180      | 3.84%   |
| France      | 169      | 3.6%    |
| Italy       | 164      | 3.5%    |
| Australia   | 153      | 3.26%   |
| Poland      | 127      | 2.71%   |
| Spain       | 125      | 2.67%   |
| Netherlands | 83       | 1.77%   |
| Sweden      | 76       | 1.62%   |
| India       | 67       | 1.43%   |
| Czechia     | 63       | 1.34%   |
| Mexico      | 58       | 1.24%   |
| Switzerland | 56       | 1.19%   |
| Belgium     | 56       | 1.19%   |
| Austria     | 50       | 1.07%   |
| Argentina   | 49       | 1.04%   |
| Ukraine     | 43       | 0.92%   |
| Turkey      | 40       | 0.85%   |
| Finland     | 39       | 0.83%   |
| Norway      | 38       | 0.81%   |
| Romania     | 36       | 0.77%   |
| Portugal    | 35       | 0.75%   |
| Hungary     | 33       | 0.7%    |
| Colombia    | 31       | 0.66%   |
| New Zealand | 29       | 0.62%   |
| Japan       | 29       | 0.62%   |
| Greece      | 27       | 0.58%   |
| Denmark     | 23       | 0.49%   |
| Indonesia   | 22       | 0.47%   |
| Chile       | 22       | 0.47%   |
| Belarus     | 20       | 0.43%   |
| Thailand    | 18       | 0.38%   |
| Taiwan      | 18       | 0.38%   |
| China       | 18       | 0.38%   |
| Philippines | 17       | 0.36%   |
| Bulgaria    | 16       | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 74       | 1.48%   |
| Sydney         | 60       | 1.2%    |
| Berlin         | 39       | 0.78%   |
| St Petersburg  | 34       | 0.68%   |
| Sao Paulo      | 34       | 0.68%   |
| Warsaw         | 32       | 0.64%   |
| Vienna         | 30       | 0.6%    |
| Brisbane       | 25       | 0.5%    |
| Melbourne      | 24       | 0.48%   |
| Toronto        | 23       | 0.46%   |
| Paris          | 22       | 0.44%   |
| Rio de Janeiro | 21       | 0.42%   |
| Madrid         | 21       | 0.42%   |
| Hamburg        | 21       | 0.42%   |
| Seattle        | 20       | 0.4%    |
| Rome           | 20       | 0.4%    |
| Auckland       | 20       | 0.4%    |
| Prague         | 19       | 0.38%   |
| Porto Alegre   | 19       | 0.38%   |
| Athens         | 19       | 0.38%   |
| Zurich         | 18       | 0.36%   |
| Palmas         | 18       | 0.36%   |
| Milan          | 17       | 0.34%   |
| Yekaterinburg  | 16       | 0.32%   |
| Wroclaw        | 16       | 0.32%   |
| Munich         | 16       | 0.32%   |
| Los Angeles    | 16       | 0.32%   |
| London         | 16       | 0.32%   |
| Buenos Aires   | 16       | 0.32%   |
| Amsterdam      | 16       | 0.32%   |
| Montreal       | 15       | 0.3%    |
| Minsk          | 15       | 0.3%    |
| Mexico City    | 15       | 0.3%    |
| Istanbul       | 15       | 0.3%    |
| Helsinki       | 15       | 0.3%    |
| Budapest       | 15       | 0.3%    |
| Brussels       | 14       | 0.28%   |
| Belo Horizonte | 14       | 0.28%   |
| Cologne        | 13       | 0.26%   |
| Vancouver      | 12       | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 1713     | 3447   | 18.1%   |
| WDC                         | 1598     | 3155   | 16.89%  |
| Seagate                     | 1487     | 2718   | 15.71%  |
| Kingston                    | 623      | 926    | 6.58%   |
| Sandisk                     | 522      | 753    | 5.52%   |
| Crucial                     | 488      | 765    | 5.16%   |
| Toshiba                     | 473      | 725    | 5%      |
| Hitachi                     | 232      | 389    | 2.45%   |
| Intel                       | 213      | 379    | 2.25%   |
| A-DATA Technology           | 158      | 211    | 1.67%   |
| Phison                      | 109      | 152    | 1.15%   |
| Micron/Crucial Technology   | 107      | 152    | 1.13%   |
| Phison Electronics          | 99       | 150    | 1.05%   |
| HGST                        | 89       | 174    | 0.94%   |
| Unknown                     | 75       | 134    | 0.79%   |
| China                       | 72       | 95     | 0.76%   |
| SK hynix                    | 70       | 84     | 0.74%   |
| Silicon Motion              | 70       | 93     | 0.74%   |
| SPCC                        | 66       | 101    | 0.7%    |
| Corsair                     | 59       | 92     | 0.62%   |
| PNY                         | 55       | 78     | 0.58%   |
| Micron Technology           | 55       | 72     | 0.58%   |
| Patriot                     | 50       | 76     | 0.53%   |
| OCZ                         | 44       | 60     | 0.46%   |
| Kingston Technology Company | 38       | 47     | 0.4%    |
| ADATA Technology            | 38       | 48     | 0.4%    |
| MAXIO Technology (Hangzhou) | 33       | 38     | 0.35%   |
| Intenso                     | 32       | 41     | 0.34%   |
| Realtek Semiconductor       | 31       | 40     | 0.33%   |
| Team                        | 30       | 43     | 0.32%   |
| Maxtor                      | 30       | 37     | 0.32%   |
| Transcend                   | 29       | 37     | 0.31%   |
| ASMT                        | 26       | 33     | 0.27%   |
| Apacer                      | 26       | 40     | 0.27%   |
| XPG                         | 25       | 35     | 0.26%   |
| Hewlett-Packard             | 24       | 29     | 0.25%   |
| Gigabyte Technology         | 22       | 39     | 0.23%   |
| Plextor                     | 21       | 29     | 0.22%   |
| GOODRAM                     | 21       | 34     | 0.22%   |
| JMicron Technology          | 20       | 27     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 175      | 1.54%   |
| Samsung SSD 850 EVO 250GB                          | 147      | 1.29%   |
| Kingston SA400S37240G 240GB SSD                    | 123      | 1.08%   |
| Samsung SSD 860 EVO 500GB                          | 121      | 1.06%   |
| Seagate ST2000DM008-2FR102 2TB                     | 119      | 1.05%   |
| Seagate ST1000DM010-2EP102 1TB                     | 114      | 1%      |
| Samsung SSD 860 EVO 1TB                            | 110      | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 103      | 0.91%   |
| Samsung SSD 850 EVO 500GB                          | 101      | 0.89%   |
| Seagate ST500DM002-1BD142 500GB                    | 97       | 0.85%   |
| Samsung NVMe SSD Drive 500GB                       | 91       | 0.8%    |
| Kingston SA400S37480G 480GB SSD                    | 89       | 0.78%   |
| Toshiba DT01ACA100 1TB                             | 87       | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 82       | 0.72%   |
| Crucial CT500MX500SSD1 500GB                       | 81       | 0.71%   |
| Kingston SA400S37120G 120GB SSD                    | 80       | 0.7%    |
| Crucial CT1000MX500SSD1 1TB                        | 70       | 0.62%   |
| Samsung NVMe SSD Drive 1TB                         | 69       | 0.61%   |
| Seagate ST2000DM001-1ER164 2TB                     | 54       | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB                     | 53       | 0.47%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 53       | 0.47%   |
| Seagate ST1000DM003-1ER162 1TB                     | 52       | 0.46%   |
| Samsung SSD 860 EVO 250GB                          | 52       | 0.46%   |
| Toshiba HDWD110 1TB                                | 51       | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                   | 51       | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB                     | 46       | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB                     | 46       | 0.4%    |
| Crucial CT240BX500SSD1 240GB                       | 45       | 0.4%    |
| Toshiba DT01ACA200 2TB                             | 44       | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                         | 43       | 0.38%   |
| Phison E12 NVMe Controller 1TB                     | 43       | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 42       | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                     | 42       | 0.37%   |
| Samsung SSD 870 EVO 1TB                            | 42       | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 41       | 0.36%   |
| Seagate ST1000DM003-1SB102 1TB                     | 41       | 0.36%   |
| SanDisk NVMe SSD Drive 500GB                       | 41       | 0.36%   |
| Samsung SSD 840 EVO 250GB                          | 41       | 0.36%   |
| Seagate ST3500418AS 500GB                          | 40       | 0.35%   |
| Samsung SSD 980 1TB                                | 40       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1443     | 2628   | 37.36%  |
| WDC                 | 1370     | 2661   | 35.47%  |
| Toshiba             | 410      | 605    | 10.62%  |
| Hitachi             | 232      | 389    | 6.01%   |
| Samsung Electronics | 171      | 277    | 4.43%   |
| HGST                | 89       | 174    | 2.3%    |
| Maxtor              | 29       | 34     | 0.75%   |
| Unknown             | 26       | 33     | 0.67%   |
| JMicron Technology  | 14       | 21     | 0.36%   |
| ASMT                | 10       | 16     | 0.26%   |
| Fujitsu             | 9        | 11     | 0.23%   |
| Intenso             | 6        | 9      | 0.16%   |
| Apple               | 6        | 6      | 0.16%   |
| Hewlett-Packard     | 5        | 6      | 0.13%   |
| SSK                 | 3        | 3      | 0.08%   |
| MaxDigital          | 3        | 3      | 0.08%   |
| Inateck             | 3        | 8      | 0.08%   |
| USB                 | 2        | 2      | 0.05%   |
| TO Exter            | 2        | 2      | 0.05%   |
| Synology            | 2        | 3      | 0.05%   |
| SAGE                | 2        | 2      | 0.05%   |
| QNAP                | 2        | 2      | 0.05%   |
| LaCie               | 2        | 4      | 0.05%   |
| H/W                 | 2        | 4      | 0.05%   |
| External            | 2        | 3      | 0.05%   |
| ASMT109x            | 2        | 2      | 0.05%   |
| USB3.0              | 1        | 1      | 0.03%   |
| USB 3.0             | 1        | 3      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| Mercury             | 1        | 1      | 0.03%   |
| Maxone              | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| KINGWIN             | 1        | 1      | 0.03%   |
| KESU                | 1        | 1      | 0.03%   |
| IET                 | 1        | 1      | 0.03%   |
| IB-377U3            | 1        | 1      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |
| ASMT106x            | 1        | 2      | 0.03%   |
| ASMedia             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 986      | 1796   | 27.34%  |
| Kingston            | 503      | 749    | 13.95%  |
| Crucial             | 451      | 711    | 12.5%   |
| SanDisk             | 271      | 351    | 7.51%   |
| WDC                 | 246      | 379    | 6.82%   |
| A-DATA Technology   | 138      | 183    | 3.83%   |
| Intel               | 102      | 198    | 2.83%   |
| China               | 72       | 95     | 2%      |
| SPCC                | 55       | 81     | 1.52%   |
| PNY                 | 55       | 77     | 1.52%   |
| Patriot             | 47       | 72     | 1.3%    |
| OCZ                 | 44       | 60     | 1.22%   |
| Toshiba             | 41       | 62     | 1.14%   |
| Micron Technology   | 36       | 49     | 1%      |
| Corsair             | 33       | 53     | 0.91%   |
| Transcend           | 29       | 37     | 0.8%    |
| SK hynix            | 28       | 31     | 0.78%   |
| Team                | 27       | 40     | 0.75%   |
| Apacer              | 24       | 37     | 0.67%   |
| Intenso             | 21       | 26     | 0.58%   |
| GOODRAM             | 21       | 34     | 0.58%   |
| KingSpec            | 19       | 31     | 0.53%   |
| SABRENT             | 18       | 22     | 0.5%    |
| Plextor             | 18       | 25     | 0.5%    |
| Seagate             | 15       | 18     | 0.42%   |
| Gigabyte Technology | 15       | 25     | 0.42%   |
| LITEON              | 14       | 18     | 0.39%   |
| LITEONIT            | 13       | 16     | 0.36%   |
| Hewlett-Packard     | 13       | 15     | 0.36%   |
| Mushkin             | 12       | 17     | 0.33%   |
| ASMT                | 12       | 13     | 0.33%   |
| KingDian            | 11       | 12     | 0.3%    |
| Lexar               | 10       | 16     | 0.28%   |
| Verbatim            | 9        | 12     | 0.25%   |
| Unknown             | 9        | 9      | 0.25%   |
| Netac               | 9        | 10     | 0.25%   |
| Leven               | 7        | 8      | 0.19%   |
| AMD                 | 7        | 10     | 0.19%   |
| Smartbuy            | 6        | 6      | 0.17%   |
| OWC                 | 5        | 7      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2959     | 6926   | 37.25%  |
| SSD     | 2872     | 6017   | 36.15%  |
| NVMe    | 1960     | 3443   | 24.67%  |
| Unknown | 142      | 216    | 1.79%   |
| MMC     | 11       | 15     | 0.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4051     | 12548  | 63.27%  |
| NVMe | 1956     | 3429   | 30.55%  |
| SAS  | 385      | 625    | 6.01%   |
| MMC  | 11       | 15     | 0.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2917     | 6410   | 44.88%  |
| 0.51-1.0   | 1970     | 3512   | 30.31%  |
| 1.01-2.0   | 826      | 1372   | 12.71%  |
| 3.01-4.0   | 345      | 658    | 5.31%   |
| 4.01-10.0  | 203      | 502    | 3.12%   |
| 2.01-3.0   | 202      | 403    | 3.11%   |
| 10.01-20.0 | 37       | 86     | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 949      | 18.88%  |
| 1001-2000      | 929      | 18.48%  |
| More than 3000 | 783      | 15.58%  |
| 251-500        | 740      | 14.72%  |
| 101-250        | 618      | 12.29%  |
| 2001-3000      | 403      | 8.02%   |
| 1-20           | 229      | 4.56%   |
| Unknown        | 204      | 4.06%   |
| 51-100         | 121      | 2.41%   |
| 21-50          | 50       | 0.99%   |
| 0              | 1        | 0.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 981      | 18.63%  |
| 101-250        | 711      | 13.5%   |
| 21-50          | 696      | 13.22%  |
| 251-500        | 627      | 11.91%  |
| 501-1000       | 607      | 11.53%  |
| 51-100         | 564      | 10.71%  |
| 1001-2000      | 451      | 8.57%   |
| More than 3000 | 239      | 4.54%   |
| Unknown        | 204      | 3.87%   |
| 2001-3000      | 183      | 3.48%   |
| 0              | 2        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 20       | 46     | 3.22%   |
| Seagate ST31000528AS 1TB              | 8        | 10     | 1.29%   |
| Seagate ST31000524AS 1TB              | 8        | 8      | 1.29%   |
| WDC WD10EZEX-00BN5A0 1TB              | 7        | 7      | 1.13%   |
| Seagate ST3500418AS 500GB             | 7        | 16     | 1.13%   |
| Samsung Electronics SSD 870 EVO 1TB   | 7        | 9      | 1.13%   |
| Intel SSDSC2CT120A3 120GB             | 6        | 41     | 0.96%   |
| WDC WD10EZEX-08WN4A0 1TB              | 5        | 6      | 0.8%    |
| Toshiba MQ01ABD050 500GB              | 5        | 8      | 0.8%    |
| Seagate ST31500341AS 1TB              | 5        | 5      | 0.8%    |
| Seagate ST2000DM001-1CH164 2TB        | 5        | 5      | 0.8%    |
| Seagate ST1000DM010-2EP102 1TB        | 5        | 5      | 0.8%    |
| Samsung Electronics HD501LJ 500GB     | 5        | 37     | 0.8%    |
| Samsung Electronics HD322HJ 320GB     | 5        | 7      | 0.8%    |
| Crucial CT128MX100SSD1 128GB          | 5        | 7      | 0.8%    |
| WDC WD5000AAKX-00ERMA0 500GB          | 4        | 6      | 0.64%   |
| WDC WD40EFRX-68N32N0 4TB              | 4        | 4      | 0.64%   |
| WDC WD20EZRX-00D8PB0 2TB              | 4        | 6      | 0.64%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 4        | 4      | 0.64%   |
| Toshiba DT01ACA100 1TB                | 4        | 4      | 0.64%   |
| Hitachi HDS721010CLA332 1TB           | 4        | 4      | 0.64%   |
| Crucial CT275MX300SSD1 275GB          | 4        | 6      | 0.64%   |
| Crucial CT240M500SSD1 240GB           | 4        | 4      | 0.64%   |
| WDC WD5000AAKX-603CA0 500GB           | 3        | 3      | 0.48%   |
| WDC WD5000AAKS-00UU3A0 500GB          | 3        | 3      | 0.48%   |
| WDC WD40EFRX-68WT0N0 4TB              | 3        | 3      | 0.48%   |
| WDC WD10EZEX-00WN4A0 1TB              | 3        | 3      | 0.48%   |
| WDC WD10EARS-22Y5B1 1TB               | 3        | 3      | 0.48%   |
| Toshiba MQ01ABD100 1TB                | 3        | 3      | 0.48%   |
| Toshiba DT01ACA200 2TB                | 3        | 6      | 0.48%   |
| Seagate ST500LT012-1DG142 500GB       | 3        | 3      | 0.48%   |
| Seagate ST3000DM008-2DM166 3TB        | 3        | 4      | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB        | 3        | 3      | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB        | 3        | 3      | 0.48%   |
| Seagate ST2000DL003-9VT166 2TB        | 3        | 3      | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB        | 3        | 3      | 0.48%   |
| SanDisk SSD PLUS 480GB                | 3        | 3      | 0.48%   |
| SanDisk SSD PLUS 240GB                | 3        | 3      | 0.48%   |
| Samsung Electronics SSD 870 EVO 500GB | 3        | 4      | 0.48%   |
| Samsung Electronics SSD 870 EVO 2TB   | 3        | 3      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 150      | 226    | 25.68%  |
| Seagate                     | 149      | 241    | 25.51%  |
| Samsung Electronics         | 57       | 109    | 9.76%   |
| Hitachi                     | 43       | 56     | 7.36%   |
| Toshiba                     | 35       | 43     | 5.99%   |
| Intel                       | 23       | 60     | 3.94%   |
| Crucial                     | 23       | 36     | 3.94%   |
| SanDisk                     | 19       | 19     | 3.25%   |
| Kingston                    | 14       | 16     | 2.4%    |
| A-DATA Technology           | 11       | 11     | 1.88%   |
| Maxtor                      | 9        | 10     | 1.54%   |
| Corsair                     | 6        | 9      | 1.03%   |
| SK hynix                    | 4        | 4      | 0.68%   |
| OCZ                         | 4        | 5      | 0.68%   |
| HGST                        | 4        | 6      | 0.68%   |
| SPCC                        | 3        | 4      | 0.51%   |
| Micron Technology           | 3        | 3      | 0.51%   |
| LITEON                      | 3        | 3      | 0.51%   |
| OCZ-VERTEX3                 | 2        | 2      | 0.34%   |
| Intenso                     | 2        | 2      | 0.34%   |
| Fujitsu                     | 2        | 2      | 0.34%   |
| Verbatim                    | 1        | 1      | 0.17%   |
| Unknown                     | 1        | 1      | 0.17%   |
| Team                        | 1        | 4      | 0.17%   |
| PNY                         | 1        | 1      | 0.17%   |
| ORICO                       | 1        | 1      | 0.17%   |
| Micron/Crucial Technology   | 1        | 1      | 0.17%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.17%   |
| LITEONIT                    | 1        | 1      | 0.17%   |
| KingSpec                    | 1        | 1      | 0.17%   |
| KingDian                    | 1        | 1      | 0.17%   |
| HPE                         | 1        | 1      | 0.17%   |
| Hewlett-Packard             | 1        | 1      | 0.17%   |
| China                       | 1        | 1      | 0.17%   |
| BIWIN                       | 1        | 1      | 0.17%   |
| ASMT                        | 1        | 1      | 0.17%   |
| ASMedia                     | 1        | 1      | 0.17%   |
| Apacer                      | 1        | 1      | 0.17%   |
| AMD                         | 1        | 2      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 149      | 241    | 35.39%  |
| WDC                 | 147      | 221    | 34.92%  |
| Hitachi             | 43       | 56     | 10.21%  |
| Toshiba             | 35       | 43     | 8.31%   |
| Samsung Electronics | 30       | 76     | 7.13%   |
| Maxtor              | 9        | 10     | 2.14%   |
| HGST                | 4        | 6      | 0.95%   |
| Fujitsu             | 2        | 2      | 0.48%   |
| Hewlett-Packard     | 1        | 1      | 0.24%   |
| ASMT                | 1        | 1      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 381      | 657    | 70.3%   |
| SSD  | 145      | 216    | 26.75%  |
| NVMe | 16       | 16     | 2.95%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BEVT-00ZAT0 500GB       | 1        | 2      | 10%     |
| WDC WD30 EZRS-00J99B0 3TB         | 1        | 1      | 10%     |
| Toshiba HDWD130 3TB               | 1        | 1      | 10%     |
| SPCC M.2 PCIe SSD 2TB             | 1        | 1      | 10%     |
| Seagate ST3320613AS 320GB         | 1        | 1      | 10%     |
| Seagate ST31000528AS 1TB          | 1        | 2      | 10%     |
| Samsung Electronics SSD 980 500GB | 1        | 2      | 10%     |
| Samsung Electronics SSD 980 1TB   | 1        | 2      | 10%     |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 10%     |
| Hitachi HDS721010DLE630 1TB       | 1        | 10     | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 6      | 30%     |
| WDC                 | 2        | 3      | 20%     |
| Seagate             | 2        | 3      | 20%     |
| Toshiba             | 1        | 1      | 10%     |
| SPCC                | 1        | 1      | 10%     |
| Hitachi             | 1        | 10     | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2873     | 9351   | 53.51%  |
| Works    | 1968     | 6353   | 36.65%  |
| Malfunc  | 519      | 889    | 9.67%   |
| Failed   | 9        | 24     | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 2580     | 34.59%  |
| AMD                            | 2028     | 27.19%  |
| Samsung Electronics            | 840      | 11.26%  |
| SanDisk                        | 335      | 4.49%   |
| ASMedia Technology             | 317      | 4.25%   |
| Phison Electronics             | 235      | 3.15%   |
| Kingston Technology Company    | 176      | 2.36%   |
| Micron/Crucial Technology      | 142      | 1.9%    |
| Marvell Technology Group       | 137      | 1.84%   |
| JMicron Technology             | 104      | 1.39%   |
| Silicon Motion                 | 81       | 1.09%   |
| ADATA Technology               | 71       | 0.95%   |
| Nvidia                         | 60       | 0.8%    |
| SK hynix                       | 41       | 0.55%   |
| Realtek Semiconductor          | 40       | 0.54%   |
| MAXIO Technology (Hangzhou)    | 35       | 0.47%   |
| Toshiba America Info Systems   | 30       | 0.4%    |
| LSI Logic / Symbios Logic      | 25       | 0.34%   |
| Seagate Technology             | 23       | 0.31%   |
| Broadcom / LSI                 | 23       | 0.31%   |
| Micron Technology              | 21       | 0.28%   |
| KIOXIA                         | 15       | 0.2%    |
| VIA Technologies               | 13       | 0.17%   |
| Silicon Image                  | 13       | 0.17%   |
| Lite-On Technology             | 10       | 0.13%   |
| Shenzhen Longsys Electronics   | 8        | 0.11%   |
| Adaptec                        | 8        | 0.11%   |
| Netac Technology               | 7        | 0.09%   |
| INNOGRIT                       | 6        | 0.08%   |
| Solidigm                       | 4        | 0.05%   |
| Solid State Storage Technology | 4        | 0.05%   |
| Integrated Technology Express  | 4        | 0.05%   |
| Hewlett-Packard                | 3        | 0.04%   |
| 3ware                          | 3        | 0.04%   |
| Yangtze Memory Technologies    | 2        | 0.03%   |
| Union Memory (Shenzhen)        | 2        | 0.03%   |
| ULi Electronics                | 2        | 0.03%   |
| Lite-On IT Corp. / Plextor     | 2        | 0.03%   |
| HighPoint Technologies         | 2        | 0.03%   |
| Biwin Storage Technology       | 2        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1160     | 12.87%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 476      | 5.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 474      | 5.26%   |
| AMD 500 Series Chipset SATA Controller                                                  | 350      | 3.88%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 296      | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 293      | 3.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 265      | 2.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 242      | 2.68%   |
| Intel SATA Controller [RAID mode]                                                       | 209      | 2.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 195      | 2.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 179      | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 178      | 1.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 174      | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 162      | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 155      | 1.72%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 131      | 1.45%   |
| Phison E12 NVMe Controller                                                              | 123      | 1.36%   |
| AMD 300 Series Chipset SATA Controller                                                  | 121      | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 113      | 1.25%   |
| AMD 600 Series Chipset SATA Controller                                                  | 112      | 1.24%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 102      | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 98       | 1.09%   |
| AMD FCH SATA Controller D                                                               | 87       | 0.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 86       | 0.95%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 76       | 0.84%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 73       | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 72       | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 72       | 0.8%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 71       | 0.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 69       | 0.77%   |
| AMD X370 Series Chipset SATA Controller                                                 | 63       | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 59       | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 57       | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 57       | 0.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 52       | 0.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 52       | 0.58%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 51       | 0.57%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 51       | 0.57%   |
| Intel SSD 660P Series                                                                   | 51       | 0.57%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 48       | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4099     | 57.54%  |
| NVMe | 1957     | 27.47%  |
| IDE  | 650      | 9.12%   |
| RAID | 353      | 4.96%   |
| SAS  | 48       | 0.67%   |
| SCSI | 17       | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 2565     | 55.04%  |
| AMD                      | 2093     | 44.91%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.02%   |
| Loongson                 | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 158      | 3.37%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 117      | 2.49%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 88       | 1.88%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 82       | 1.75%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 73       | 1.56%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 73       | 1.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 68       | 1.45%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 67       | 1.43%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 63       | 1.34%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 62       | 1.32%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 60       | 1.28%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 52       | 1.11%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 49       | 1.04%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 46       | 0.98%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 45       | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 45       | 0.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 45       | 0.96%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 44       | 0.94%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 44       | 0.94%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 43       | 0.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 41       | 0.87%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 40       | 0.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 40       | 0.85%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 38       | 0.81%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 38       | 0.81%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 36       | 0.77%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 35       | 0.75%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 35       | 0.75%   |
| AMD FX-6300 Six-Core Processor              | 35       | 0.75%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 34       | 0.72%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 32       | 0.68%   |
| AMD FX-8350 Eight-Core Processor            | 31       | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 30       | 0.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 30       | 0.64%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 29       | 0.62%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 29       | 0.62%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 27       | 0.58%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 27       | 0.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 27       | 0.58%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 27       | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 778      | 16.62%  |
| Intel Core i7           | 700      | 14.96%  |
| AMD Ryzen 5             | 680      | 14.53%  |
| AMD Ryzen 7             | 508      | 10.85%  |
| AMD Ryzen 9             | 302      | 6.45%   |
| Intel Xeon              | 241      | 5.15%   |
| Intel Core i3           | 239      | 5.11%   |
| Other                   | 214      | 4.57%   |
| AMD FX                  | 153      | 3.27%   |
| Intel Core 2 Duo        | 81       | 1.73%   |
| AMD Ryzen 3             | 73       | 1.56%   |
| Intel Core 2 Quad       | 66       | 1.41%   |
| Intel Core i9           | 62       | 1.32%   |
| Intel Celeron           | 61       | 1.3%    |
| Intel Pentium           | 52       | 1.11%   |
| AMD Ryzen Threadripper  | 52       | 1.11%   |
| AMD Phenom II X4        | 47       | 1%      |
| AMD A10                 | 37       | 0.79%   |
| AMD A8                  | 29       | 0.62%   |
| Intel Pentium Dual-Core | 28       | 0.6%    |
| AMD A6                  | 22       | 0.47%   |
| AMD Phenom II X6        | 21       | 0.45%   |
| AMD Athlon              | 21       | 0.45%   |
| AMD Athlon II X2        | 20       | 0.43%   |
| Intel Core 2            | 16       | 0.34%   |
| AMD Ryzen 5 PRO         | 15       | 0.32%   |
| AMD Athlon 64 X2        | 15       | 0.32%   |
| AMD Ryzen 7 PRO         | 14       | 0.3%    |
| AMD A4                  | 14       | 0.3%    |
| Intel Atom              | 13       | 0.28%   |
| AMD Phenom              | 13       | 0.28%   |
| Intel Pentium Gold      | 9        | 0.19%   |
| AMD Phenom II X2        | 9        | 0.19%   |
| AMD Athlon II X4        | 9        | 0.19%   |
| AMD Athlon X4           | 8        | 0.17%   |
| Intel Pentium Dual      | 6        | 0.13%   |
| Intel Genuine           | 5        | 0.11%   |
| AMD Athlon II X3        | 4        | 0.09%   |
| AMD Athlon Dual Core    | 4        | 0.09%   |
| Intel Pentium D         | 3        | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1677     | 35.83%  |
| 6      | 1009     | 21.56%  |
| 8      | 710      | 15.17%  |
| 2      | 638      | 13.63%  |
| 12     | 262      | 5.6%    |
| 16     | 176      | 3.76%   |
| 10     | 58       | 1.24%   |
| 3      | 57       | 1.22%   |
| 1      | 37       | 0.79%   |
| 24     | 21       | 0.45%   |
| 14     | 16       | 0.34%   |
| 32     | 13       | 0.28%   |
| 28     | 2        | 0.04%   |
| 18     | 2        | 0.04%   |
| 36     | 1        | 0.02%   |
| 20     | 1        | 0.02%   |
| 5      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4601     | 98.73%  |
| 2      | 59       | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 3245     | 69.47%  |
| 1      | 1425     | 30.51%  |
| 4      | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4570     | 97.71%  |
| Unknown        | 107      | 2.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 978      | 20.11%  |
| 0x306c3    | 320      | 6.58%   |
| 0x08701021 | 316      | 6.5%    |
| 0x306a9    | 186      | 3.82%   |
| 0x0800820d | 182      | 3.74%   |
| 0x506e3    | 176      | 3.62%   |
| 0x206a7    | 137      | 2.82%   |
| 0x906ea    | 135      | 2.78%   |
| 0x08701013 | 128      | 2.63%   |
| 0x906e9    | 119      | 2.45%   |
| 0x0a201016 | 103      | 2.12%   |
| 0x1067a    | 88       | 1.81%   |
| 0x06000852 | 83       | 1.71%   |
| 0x0a20120a | 80       | 1.64%   |
| 0x0a601203 | 78       | 1.6%    |
| 0x0a201009 | 71       | 1.46%   |
| 0x08108109 | 70       | 1.44%   |
| 0x08001138 | 69       | 1.42%   |
| 0x0a50000d | 65       | 1.34%   |
| 0x0a50000c | 59       | 1.21%   |
| 0x906ed    | 57       | 1.17%   |
| 0x010000c8 | 56       | 1.15%   |
| 0x08001137 | 54       | 1.11%   |
| 0x90672    | 48       | 0.99%   |
| 0x08101016 | 46       | 0.95%   |
| 0x306f2    | 45       | 0.93%   |
| 0xa0655    | 44       | 0.9%    |
| 0xa0653    | 41       | 0.84%   |
| 0x08701030 | 39       | 0.8%    |
| 0x06001119 | 38       | 0.78%   |
| 0x206d7    | 33       | 0.68%   |
| 0x20655    | 28       | 0.58%   |
| 0xa0671    | 27       | 0.56%   |
| 0x106a5    | 27       | 0.56%   |
| 0x10676    | 27       | 0.56%   |
| 0x6fb      | 26       | 0.53%   |
| 0x106e5    | 26       | 0.53%   |
| 0x06003106 | 26       | 0.53%   |
| 0x06000822 | 26       | 0.53%   |
| 0x906eb    | 25       | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 539      | 11.51%  |
| KabyLake         | 507      | 10.82%  |
| Haswell          | 482      | 10.29%  |
| Zen 3            | 471      | 10.06%  |
| Zen+             | 307      | 6.55%   |
| IvyBridge        | 296      | 6.32%   |
| Skylake          | 267      | 5.7%    |
| SandyBridge      | 233      | 4.97%   |
| Zen              | 231      | 4.93%   |
| Piledriver       | 168      | 3.59%   |
| Penryn           | 159      | 3.39%   |
| Alderlake Hybrid | 149      | 3.18%   |
| Unknown          | 137      | 2.92%   |
| K10              | 128      | 2.73%   |
| CometLake        | 126      | 2.69%   |
| Westmere         | 74       | 1.58%   |
| Nehalem          | 68       | 1.45%   |
| Core             | 65       | 1.39%   |
| Icelake          | 52       | 1.11%   |
| Steamroller      | 37       | 0.79%   |
| Excavator        | 28       | 0.6%    |
| Bulldozer        | 27       | 0.58%   |
| K8 Hammer        | 24       | 0.51%   |
| Broadwell        | 22       | 0.47%   |
| Silvermont       | 18       | 0.38%   |
| Bonnell          | 10       | 0.21%   |
| Goldmont plus    | 9        | 0.19%   |
| Tremont          | 8        | 0.17%   |
| K10 Llano        | 8        | 0.17%   |
| NetBurst         | 7        | 0.15%   |
| Jaguar           | 7        | 0.15%   |
| Bobcat           | 6        | 0.13%   |
| Goldmont         | 5        | 0.11%   |
| Puma             | 4        | 0.09%   |
| Gracemont        | 3        | 0.06%   |
| TigerLake        | 2        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 2005     | 39.38%  |
| AMD                              | 1926     | 37.82%  |
| Intel                            | 1138     | 22.35%  |
| ASPEED Technology                | 10       | 0.2%    |
| Matrox Electronics Systems       | 9        | 0.18%   |
| VIA Technologies                 | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| S3 Graphics                      | 1        | 0.02%   |
| Loongson Technology              | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 354      | 6.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 182      | 3.44%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 143      | 2.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 129      | 2.44%   |
| Intel HD Graphics 530                                                       | 125      | 2.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 121      | 2.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 107      | 2.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 103      | 1.94%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 98       | 1.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 95       | 1.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 90       | 1.7%    |
| AMD Raphael                                                                 | 90       | 1.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 81       | 1.53%   |
| Intel HD Graphics 630                                                       | 80       | 1.51%   |
| Nvidia GK208B [GeForce GT 710]                                              | 76       | 1.43%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 73       | 1.38%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 70       | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 69       | 1.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 67       | 1.26%   |
| Nvidia GT218 [GeForce 210]                                                  | 56       | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 55       | 1.04%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 54       | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 52       | 0.98%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 51       | 0.96%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 50       | 0.94%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 50       | 0.94%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 49       | 0.93%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 48       | 0.91%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 47       | 0.89%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 47       | 0.89%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 46       | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 44       | 0.83%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 43       | 0.81%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 40       | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 38       | 0.72%   |
| Intel AlderLake-S GT1                                                       | 38       | 0.72%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 37       | 0.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 36       | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 36       | 0.68%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 36       | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1795     | 37.88%  |
| 1 x AMD                  | 1713     | 36.15%  |
| 1 x Intel                | 844      | 17.81%  |
| Intel + Nvidia           | 109      | 2.3%    |
| 2 x AMD                  | 103      | 2.17%   |
| AMD + Nvidia             | 67       | 1.41%   |
| Intel + AMD              | 42       | 0.89%   |
| 2 x Nvidia               | 26       | 0.55%   |
| 2 x Intel                | 8        | 0.17%   |
| 1 x ASPEED               | 6        | 0.13%   |
| 1 x Matrox               | 5        | 0.11%   |
| Nvidia + Matrox          | 3        | 0.06%   |
| Other                    | 2        | 0.04%   |
| Nvidia + ASPEED          | 2        | 0.04%   |
| Intel + 2 x AMD          | 2        | 0.04%   |
| Intel + AMD + 1 x Nvidia | 2        | 0.04%   |
| 3 x AMD                  | 1        | 0.02%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.02%   |
| 1 x VIA                  | 1        | 0.02%   |
| 1 x SiS                  | 1        | 0.02%   |
| 1 x S3 Graphics          | 1        | 0.02%   |
| 1 x Loongson Technology  | 1        | 0.02%   |
| Intel + 2 x Nvidia       | 1        | 0.02%   |
| AMD + 2 x Nvidia         | 1        | 0.02%   |
| AMD + Matrox             | 1        | 0.02%   |
| AMD + ASPEED             | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3510     | 73.82%  |
| Proprietary | 1096     | 23.05%  |
| Unknown     | 149      | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1617     | 33.21%  |
| 7.01-8.0   | 760      | 15.61%  |
| 1.01-2.0   | 603      | 12.38%  |
| 3.01-4.0   | 518      | 10.64%  |
| 0.51-1.0   | 434      | 8.91%   |
| 0.01-0.5   | 335      | 6.88%   |
| 8.01-16.0  | 291      | 5.98%   |
| 5.01-6.0   | 204      | 4.19%   |
| 2.01-3.0   | 63       | 1.29%   |
| 16.01-24.0 | 43       | 0.88%   |
| 4.01-5.0   | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 837      | 15.28%  |
| Dell                 | 717      | 13.09%  |
| Goldstar             | 714      | 13.04%  |
| Acer                 | 379      | 6.92%   |
| Hewlett-Packard      | 335      | 6.12%   |
| AOC                  | 309      | 5.64%   |
| BenQ                 | 274      | 5%      |
| Ancor Communications | 257      | 4.69%   |
| Philips              | 222      | 4.05%   |
| ViewSonic            | 133      | 2.43%   |
| Lenovo               | 129      | 2.36%   |
| ASUSTek Computer     | 121      | 2.21%   |
| Iiyama               | 111      | 2.03%   |
| MSI                  | 65       | 1.19%   |
| Sony                 | 54       | 0.99%   |
| Sceptre Tech         | 52       | 0.95%   |
| Unknown              | 46       | 0.84%   |
| Gigabyte Technology  | 45       | 0.82%   |
| Eizo                 | 43       | 0.79%   |
| HannStar             | 32       | 0.58%   |
| NEC Computers        | 30       | 0.55%   |
| Vizio                | 27       | 0.49%   |
| Mi                   | 22       | 0.4%    |
| Insignia             | 20       | 0.37%   |
| Panasonic            | 19       | 0.35%   |
| Fujitsu Siemens      | 17       | 0.31%   |
| LG Electronics       | 16       | 0.29%   |
| ___                  | 12       | 0.22%   |
| Pixio                | 12       | 0.22%   |
| HUAWEI               | 11       | 0.2%    |
| Vestel Elektronik    | 10       | 0.18%   |
| Toshiba              | 10       | 0.18%   |
| RTK                  | 10       | 0.18%   |
| Gateway              | 10       | 0.18%   |
| Medion               | 9        | 0.16%   |
| Hitachi              | 9        | 0.16%   |
| Unknown (XXX)        | 8        | 0.15%   |
| ONN                  | 7        | 0.13%   |
| Belinea              | 7        | 0.13%   |
| Apple                | 7        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 41       | 0.69%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 38       | 0.64%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 32       | 0.54%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 32       | 0.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 29       | 0.49%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 25       | 0.42%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 22       | 0.37%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 22       | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 21       | 0.35%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 21       | 0.35%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 19       | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 18       | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 17       | 0.29%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 16       | 0.27%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 16       | 0.27%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 15       | 0.25%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 14       | 0.24%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 13       | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 13       | 0.22%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 13       | 0.22%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 12       | 0.2%    |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 12       | 0.2%    |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 12       | 0.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 12       | 0.2%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 12       | 0.2%    |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 12       | 0.2%    |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 11       | 0.19%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 11       | 0.19%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 11       | 0.19%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 11       | 0.19%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 11       | 0.19%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 11       | 0.19%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 11       | 0.19%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                     | 11       | 0.19%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 10       | 0.17%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 10       | 0.17%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 10       | 0.17%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch              | 10       | 0.17%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 10       | 0.17%   |
| Goldstar LG ULTRAWIDE GSM76E4 3440x1440 800x340mm 34.2-inch           | 10       | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2358     | 44.79%  |
| 2560x1440 (QHD)    | 677      | 12.86%  |
| 3840x2160 (4K)     | 657      | 12.48%  |
| 1280x1024 (SXGA)   | 205      | 3.89%   |
| 1680x1050 (WSXGA+) | 194      | 3.68%   |
| 3440x1440          | 173      | 3.29%   |
| 1920x1200 (WUXGA)  | 162      | 3.08%   |
| 1366x768 (WXGA)    | 144      | 2.74%   |
| 1440x900 (WXGA+)   | 120      | 2.28%   |
| 1600x900 (HD+)     | 118      | 2.24%   |
| 2560x1080          | 116      | 2.2%    |
| 1360x768           | 59       | 1.12%   |
| 3840x1080          | 49       | 0.93%   |
| Unknown            | 44       | 0.84%   |
| 2288x1287          | 27       | 0.51%   |
| 1600x1200          | 27       | 0.51%   |
| 1920x540           | 22       | 0.42%   |
| 1024x768 (XGA)     | 18       | 0.34%   |
| 2560x1600          | 16       | 0.3%    |
| 1280x720 (HD)      | 10       | 0.19%   |
| 2048x1152          | 9        | 0.17%   |
| 3840x1600          | 8        | 0.15%   |
| 1280x960           | 6        | 0.11%   |
| 2160x1200          | 4        | 0.08%   |
| 5760x1080          | 3        | 0.06%   |
| 1280x768           | 3        | 0.06%   |
| 5760x2160          | 2        | 0.04%   |
| 3840x2560          | 2        | 0.04%   |
| 3840x1200          | 2        | 0.04%   |
| 1920x1440          | 2        | 0.04%   |
| 7680x2160          | 1        | 0.02%   |
| 7680x1440          | 1        | 0.02%   |
| 7120x1080          | 1        | 0.02%   |
| 6784x2160          | 1        | 0.02%   |
| 6400x2160          | 1        | 0.02%   |
| 6400x1080          | 1        | 0.02%   |
| 5760x1200          | 1        | 0.02%   |
| 5120x1440          | 1        | 0.02%   |
| 4864x2160          | 1        | 0.02%   |
| 4480x1200          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 1049     | 18.98%  |
| 24      | 916      | 16.57%  |
| 23      | 681      | 12.32%  |
| 21      | 617      | 11.16%  |
| 31      | 332      | 6.01%   |
| 34      | 255      | 4.61%   |
| 19      | 237      | 4.29%   |
| 18      | 163      | 2.95%   |
| 22      | 161      | 2.91%   |
| Unknown | 153      | 2.77%   |
| 20      | 149      | 2.7%    |
| 17      | 77       | 1.39%   |
| 32      | 71       | 1.28%   |
| 84      | 70       | 1.27%   |
| 72      | 68       | 1.23%   |
| 25      | 53       | 0.96%   |
| 15      | 47       | 0.85%   |
| 40      | 46       | 0.83%   |
| 54      | 39       | 0.71%   |
| 48      | 39       | 0.71%   |
| 26      | 30       | 0.54%   |
| 42      | 26       | 0.47%   |
| 142     | 25       | 0.45%   |
| 28      | 24       | 0.43%   |
| 49      | 15       | 0.27%   |
| 29      | 15       | 0.27%   |
| 52      | 13       | 0.24%   |
| 16      | 13       | 0.24%   |
| 46      | 12       | 0.22%   |
| 36      | 12       | 0.22%   |
| 35      | 12       | 0.22%   |
| 37      | 11       | 0.2%    |
| 65      | 10       | 0.18%   |
| 13      | 10       | 0.18%   |
| 33      | 8        | 0.14%   |
| 69      | 7        | 0.13%   |
| 39      | 7        | 0.13%   |
| 43      | 6        | 0.11%   |
| 30      | 6        | 0.11%   |
| 50      | 4        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2370     | 45.19%  |
| 401-500        | 1140     | 21.73%  |
| 601-700        | 491      | 9.36%   |
| 701-800        | 345      | 6.58%   |
| 351-400        | 173      | 3.3%    |
| Unknown        | 153      | 2.92%   |
| 1501-2000      | 148      | 2.82%   |
| 1001-1500      | 144      | 2.75%   |
| 301-350        | 121      | 2.31%   |
| 801-900        | 79       | 1.51%   |
| 901-1000       | 40       | 0.76%   |
| More than 2000 | 27       | 0.51%   |
| 201-300        | 14       | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3519     | 72.66%  |
| 16/10   | 561      | 11.58%  |
| 21/9    | 282      | 5.82%   |
| 5/4     | 199      | 4.11%   |
| Unknown | 99       | 2.04%   |
| 4/3     | 68       | 1.4%    |
| 32/9    | 44       | 0.91%   |
| 1.00    | 26       | 0.54%   |
| 6/5     | 20       | 0.41%   |
| 3/2     | 12       | 0.25%   |
| 1.96    | 6        | 0.12%   |
| 0.56    | 3        | 0.06%   |
| 3.20    | 1        | 0.02%   |
| 2.12    | 1        | 0.02%   |
| 0.89    | 1        | 0.02%   |
| 0.80    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1805     | 33.76%  |
| 301-350        | 1068     | 19.98%  |
| 351-500        | 689      | 12.89%  |
| 151-200        | 576      | 10.77%  |
| 251-300        | 342      | 6.4%    |
| More than 1000 | 257      | 4.81%   |
| 141-150        | 189      | 3.54%   |
| 501-1000       | 179      | 3.35%   |
| Unknown        | 153      | 2.86%   |
| 101-110        | 44       | 0.82%   |
| 131-140        | 12       | 0.22%   |
| 71-80          | 7        | 0.13%   |
| 121-130        | 7        | 0.13%   |
| 91-100         | 7        | 0.13%   |
| 111-120        | 6        | 0.11%   |
| 81-90          | 5        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2978     | 59.1%   |
| 101-120       | 1244     | 24.69%  |
| 121-160       | 319      | 6.33%   |
| 1-50          | 214      | 4.25%   |
| Unknown       | 153      | 3.04%   |
| 161-240       | 129      | 2.56%   |
| More than 240 | 2        | 0.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3356     | 69.51%  |
| 2     | 1124     | 23.28%  |
| 0     | 172      | 3.56%   |
| 3     | 148      | 3.07%   |
| 4     | 21       | 0.43%   |
| 5     | 5        | 0.1%    |
| 6     | 2        | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2794     | 40.87%  |
| Intel                           | 2321     | 33.95%  |
| Qualcomm Atheros                | 359      | 5.25%   |
| Broadcom                        | 191      | 2.79%   |
| TP-Link                         | 148      | 2.17%   |
| MediaTek                        | 140      | 2.05%   |
| Ralink Technology               | 117      | 1.71%   |
| Microsoft                       | 70       | 1.02%   |
| Ralink                          | 67       | 0.98%   |
| Aquantia                        | 63       | 0.92%   |
| Nvidia                          | 47       | 0.69%   |
| Qualcomm Atheros Communications | 41       | 0.6%    |
| ASUSTek Computer                | 33       | 0.48%   |
| NetGear                         | 31       | 0.45%   |
| D-Link                          | 27       | 0.39%   |
| Xiaomi                          | 25       | 0.37%   |
| Samsung Electronics             | 25       | 0.37%   |
| Marvell Technology Group        | 25       | 0.37%   |
| Google                          | 18       | 0.26%   |
| ASIX Electronics                | 18       | 0.26%   |
| Edimax Technology               | 16       | 0.23%   |
| Mellanox Technologies           | 15       | 0.22%   |
| DisplayLink                     | 14       | 0.2%    |
| Motorola PCS                    | 13       | 0.19%   |
| Huawei Technologies             | 13       | 0.19%   |
| Broadcom Limited                | 13       | 0.19%   |
| D-Link System                   | 12       | 0.18%   |
| Linksys                         | 11       | 0.16%   |
| Qualcomm                        | 8        | 0.12%   |
| Arduino SA                      | 8        | 0.12%   |
| ICS Advent                      | 7        | 0.1%    |
| Belkin Components               | 7        | 0.1%    |
| AVM                             | 7        | 0.1%    |
| Apple                           | 7        | 0.1%    |
| Wilocity                        | 6        | 0.09%   |
| OPPO Electronics                | 6        | 0.09%   |
| Microchip Technology            | 5        | 0.07%   |
| InterBiometrics                 | 5        | 0.07%   |
| HMD Global                      | 5        | 0.07%   |
| 3Com                            | 5        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 2141     | 27.01%  |
| Intel I211 Gigabit Network Connection                                          | 443      | 5.59%   |
| Intel Wi-Fi 6 AX200                                                            | 430      | 5.42%   |
| Realtek RTL8125 2.5GbE Controller                                              | 377      | 4.76%   |
| Intel Ethernet Connection (2) I219-V                                           | 239      | 3.02%   |
| Intel Ethernet Controller I225-V                                               | 233      | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 150      | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 131      | 1.65%   |
| Intel Ethernet Connection (7) I219-V                                           | 108      | 1.36%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 107      | 1.35%   |
| Intel Ethernet Connection I217-LM                                              | 93       | 1.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 82       | 1.03%   |
| Intel Ethernet Connection (2) I218-V                                           | 77       | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                                          | 66       | 0.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 64       | 0.81%   |
| Intel 82579V Gigabit Network Connection                                        | 64       | 0.81%   |
| Intel 82574L Gigabit Network Connection                                        | 63       | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 59       | 0.74%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 59       | 0.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 52       | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 52       | 0.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 52       | 0.66%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 52       | 0.66%   |
| Intel Ethernet Connection I217-V                                               | 49       | 0.62%   |
| Ralink MT7601U Wireless Adapter                                                | 48       | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 47       | 0.59%   |
| Microsoft Xbox Wireless Adapter for Windows                                    | 45       | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 44       | 0.56%   |
| Intel Wireless 7260                                                            | 40       | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 37       | 0.47%   |
| Intel Wireless 8260                                                            | 36       | 0.45%   |
| Realtek 802.11ac NIC                                                           | 33       | 0.42%   |
| Intel Wireless 7265                                                            | 33       | 0.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 33       | 0.42%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 33       | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 31       | 0.39%   |
| Intel I210 Gigabit Network Connection                                          | 31       | 0.39%   |
| Qualcomm Atheros AR9271 802.11n                                                | 30       | 0.38%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 30       | 0.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 28       | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 1085     | 42.82%  |
| Realtek Semiconductor                 | 405      | 15.98%  |
| Qualcomm Atheros                      | 195      | 7.7%    |
| TP-Link                               | 146      | 5.76%   |
| MediaTek                              | 139      | 5.49%   |
| Ralink Technology                     | 117      | 4.62%   |
| Broadcom                              | 103      | 4.06%   |
| Microsoft                             | 68       | 2.68%   |
| Ralink                                | 67       | 2.64%   |
| Qualcomm Atheros Communications       | 41       | 1.62%   |
| ASUSTek Computer                      | 31       | 1.22%   |
| NetGear                               | 30       | 1.18%   |
| D-Link                                | 23       | 0.91%   |
| Edimax Technology                     | 16       | 0.63%   |
| Linksys                               | 11       | 0.43%   |
| D-Link System                         | 7        | 0.28%   |
| Belkin Components                     | 7        | 0.28%   |
| AVM                                   | 7        | 0.28%   |
| Wilocity                              | 6        | 0.24%   |
| IMC Networks                          | 4        | 0.16%   |
| Broadcom Limited                      | 4        | 0.16%   |
| Mercucys                              | 3        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.12%   |
| Xiaomi                                | 2        | 0.08%   |
| BUFFALO                               | 2        | 0.08%   |
| AboCom Systems                        | 2        | 0.08%   |
| ZyDAS                                 | 1        | 0.04%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.04%   |
| Wacom                                 | 1        | 0.04%   |
| Toshiba                               | 1        | 0.04%   |
| Sitecom Europe                        | 1        | 0.04%   |
| Sierra Wireless                       | 1        | 0.04%   |
| Samsung Electronics                   | 1        | 0.04%   |
| PLANEX                                | 1        | 0.04%   |
| NEC Computers                         | 1        | 0.04%   |
| Gemtek                                | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 430      | 16.81%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 131      | 5.12%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 107      | 4.18%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 82       | 3.21%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 64       | 2.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 59       | 2.31%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 52       | 2.03%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 52       | 2.03%   |
| Ralink MT7601U Wireless Adapter                                | 48       | 1.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 47       | 1.84%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 45       | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 44       | 1.72%   |
| Intel Wireless 7260                                            | 40       | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 37       | 1.45%   |
| Intel Wireless 8260                                            | 36       | 1.41%   |
| Realtek 802.11ac NIC                                           | 33       | 1.29%   |
| Intel Wireless 7265                                            | 33       | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 33       | 1.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 31       | 1.21%   |
| Qualcomm Atheros AR9271 802.11n                                | 30       | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 28       | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 27       | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 27       | 1.06%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 26       | 1.02%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 26       | 1.02%   |
| Intel Wireless 8265 / 8275                                     | 25       | 0.98%   |
| Intel Wireless 3165                                            | 25       | 0.98%   |
| Ralink RT5370 Wireless Adapter                                 | 23       | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 23       | 0.9%    |
| Microsoft Xbox 360 Wireless Adapter                            | 22       | 0.86%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 21       | 0.82%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 20       | 0.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 20       | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 20       | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18       | 0.7%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 17       | 0.66%   |
| TP-Link 802.11ac NIC                                           | 17       | 0.66%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 17       | 0.66%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 17       | 0.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 17       | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2631     | 51.75%  |
| Intel                                  | 1819     | 35.78%  |
| Qualcomm Atheros                       | 183      | 3.6%    |
| Broadcom                               | 89       | 1.75%   |
| Aquantia                               | 63       | 1.24%   |
| Nvidia                                 | 47       | 0.92%   |
| Marvell Technology Group               | 25       | 0.49%   |
| Samsung Electronics                    | 24       | 0.47%   |
| Xiaomi                                 | 23       | 0.45%   |
| Google                                 | 18       | 0.35%   |
| ASIX Electronics                       | 18       | 0.35%   |
| DisplayLink                            | 14       | 0.28%   |
| Mellanox Technologies                  | 13       | 0.26%   |
| Motorola PCS                           | 11       | 0.22%   |
| Broadcom Limited                       | 9        | 0.18%   |
| Qualcomm                               | 8        | 0.16%   |
| ICS Advent                             | 7        | 0.14%   |
| Huawei Technologies                    | 7        | 0.14%   |
| Apple                                  | 7        | 0.14%   |
| OPPO Electronics                       | 6        | 0.12%   |
| HMD Global                             | 5        | 0.1%    |
| D-Link System                          | 5        | 0.1%    |
| 3Com                                   | 5        | 0.1%    |
| VIA Technologies                       | 4        | 0.08%   |
| D-Link                                 | 4        | 0.08%   |
| Lenovo                                 | 3        | 0.06%   |
| ADMtek                                 | 3        | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.04%   |
| TP-Link                                | 2        | 0.04%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.04%   |
| National Semiconductor                 | 2        | 0.04%   |
| Davicom Semiconductor                  | 2        | 0.04%   |
| ASUSTek Computer                       | 2        | 0.04%   |
| Accton Technology                      | 2        | 0.04%   |
| Xilinx                                 | 1        | 0.02%   |
| vivo                                   | 1        | 0.02%   |
| Tehuti Networks                        | 1        | 0.02%   |
| Sharp                                  | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 2141     | 40.37%  |
| Intel I211 Gigabit Network Connection                                           | 443      | 8.35%   |
| Realtek RTL8125 2.5GbE Controller                                               | 377      | 7.11%   |
| Intel Ethernet Connection (2) I219-V                                            | 239      | 4.51%   |
| Intel Ethernet Controller I225-V                                                | 233      | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 150      | 2.83%   |
| Intel Ethernet Connection (7) I219-V                                            | 108      | 2.04%   |
| Intel Ethernet Connection I217-LM                                               | 93       | 1.75%   |
| Intel Ethernet Connection (2) I218-V                                            | 77       | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                                           | 66       | 1.24%   |
| Intel 82579V Gigabit Network Connection                                         | 64       | 1.21%   |
| Intel 82574L Gigabit Network Connection                                         | 63       | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 59       | 1.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 52       | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 52       | 0.98%   |
| Intel Ethernet Connection I217-V                                                | 49       | 0.92%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 33       | 0.62%   |
| Intel I210 Gigabit Network Connection                                           | 31       | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                      | 30       | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 28       | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                        | 24       | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                                           | 24       | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 22       | 0.41%   |
| Nvidia MCP61 Ethernet                                                           | 21       | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 20       | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                 | 19       | 0.36%   |
| Intel Ethernet Connection (17) I219-V                                           | 19       | 0.36%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                | 19       | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 18       | 0.34%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 18       | 0.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                         | 17       | 0.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 15       | 0.28%   |
| Realtek Killer E3000 2.5GbE Controller                                          | 15       | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 15       | 0.28%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 15       | 0.28%   |
| Intel Ethernet Connection (14) I219-V                                           | 14       | 0.26%   |
| Intel 82566DM-2 Gigabit Network Connection                                      | 14       | 0.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                               | 14       | 0.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                  | 13       | 0.25%   |
| Intel 82578DM Gigabit Network Connection                                        | 13       | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4621     | 65.58%  |
| WiFi     | 2360     | 33.49%  |
| Modem    | 55       | 0.78%   |
| Unknown  | 10       | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3674     | 73.94%  |
| WiFi     | 1295     | 26.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2609     | 55.16%  |
| 2     | 1750     | 37%     |
| 3     | 274      | 5.79%   |
| 4     | 39       | 0.82%   |
| 0     | 31       | 0.66%   |
| 5     | 16       | 0.34%   |
| 6     | 7        | 0.15%   |
| 9     | 2        | 0.04%   |
| 11    | 1        | 0.02%   |
| 8     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 3748     | 78.26%  |
| Yes     | 1038     | 21.67%  |
| Unknown | 3        | 0.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 1015     | 47.45%  |
| Cambridge Silicon Radio         | 406      | 18.98%  |
| Realtek Semiconductor           | 146      | 6.83%   |
| ASUSTek Computer                | 144      | 6.73%   |
| Broadcom                        | 91       | 4.25%   |
| MediaTek                        | 90       | 4.21%   |
| Qualcomm Atheros Communications | 47       | 2.2%    |
| IMC Networks                    | 43       | 2.01%   |
| TP-Link                         | 39       | 1.82%   |
| Apple                           | 24       | 1.12%   |
| Foxconn / Hon Hai               | 23       | 1.08%   |
| Belkin Components               | 9        | 0.42%   |
| Edimax Technology               | 8        | 0.37%   |
| Lite-On Technology              | 7        | 0.33%   |
| Integrated System Solution      | 7        | 0.33%   |
| HTC (High Tech Computer)        | 7        | 0.33%   |
| Dynex                           | 5        | 0.23%   |
| Realtek                         | 4        | 0.19%   |
| Toshiba                         | 3        | 0.14%   |
| Hewlett-Packard                 | 3        | 0.14%   |
| Dell                            | 3        | 0.14%   |
| Actions                         | 3        | 0.14%   |
| SINO WEALTH                     | 2        | 0.09%   |
| Unknown                         | 2        | 0.09%   |
| Ralink                          | 1        | 0.05%   |
| Mobile Action Technology        | 1        | 0.05%   |
| Kensington                      | 1        | 0.05%   |
| Foxconn International           | 1        | 0.05%   |
| D-Link System                   | 1        | 0.05%   |
| D-Link                          | 1        | 0.05%   |
| Creative Technology             | 1        | 0.05%   |
| BUFFALO                         | 1        | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 406      | 18.94%  |
| Intel AX200 Bluetooth                                                | 403      | 18.8%   |
| Intel Bluetooth wireless interface                                   | 158      | 7.37%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 129      | 6.02%   |
| Realtek Bluetooth Radio                                              | 118      | 5.5%    |
| Intel AX210 Bluetooth                                                | 101      | 4.71%   |
| MediaTek Wireless_Device                                             | 90       | 4.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 78       | 3.64%   |
| Intel AX201 Bluetooth                                                | 74       | 3.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 63       | 2.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 45       | 2.1%    |
| TP-Link UB500 Adapter                                                | 39       | 1.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 39       | 1.82%   |
| Intel Bluetooth Device                                               | 31       | 1.45%   |
| ASUS ASUS USB-BT500                                                  | 25       | 1.17%   |
| ASUS Bluetooth Radio                                                 | 24       | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 22       | 1.03%   |
| Foxconn / Hon Hai Wireless_Device                                    | 21       | 0.98%   |
| IMC Networks Bluetooth Radio                                         | 17       | 0.79%   |
| Qualcomm Atheros  Bluetooth Device                                   | 16       | 0.75%   |
| IMC Networks Wireless_Device                                         | 16       | 0.75%   |
| ASUS Bluetooth Adapter                                               | 15       | 0.7%    |
| Apple Bluetooth Host Controller                                      | 14       | 0.65%   |
| ASUS BCM20702A0                                                      | 12       | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 10       | 0.47%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 9        | 0.42%   |
| ASUS Bluetooth Device                                                | 9        | 0.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 7        | 0.33%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 7        | 0.33%   |
| IMC Networks Bluetooth Device                                        | 7        | 0.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 7        | 0.33%   |
| Edimax Bluetooth Adapter                                             | 7        | 0.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 7        | 0.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 6        | 0.28%   |
| Integrated System Solution Bluetooth Device                          | 6        | 0.28%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 6        | 0.28%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 5        | 0.23%   |
| Broadcom BCM2045 Bluetooth                                           | 5        | 0.23%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 5        | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 2575     | 29.25%  |
| Intel                                | 2469     | 28.05%  |
| Nvidia                               | 1934     | 21.97%  |
| C-Media Electronics                  | 299      | 3.4%    |
| Logitech                             | 144      | 1.64%   |
| Creative Labs                        | 92       | 1.05%   |
| Kingston Technology                  | 67       | 0.76%   |
| JMTek                                | 67       | 0.76%   |
| SteelSeries ApS                      | 66       | 0.75%   |
| ASUSTek Computer                     | 59       | 0.67%   |
| Razer USA                            | 56       | 0.64%   |
| Focusrite-Novation                   | 56       | 0.64%   |
| Texas Instruments                    | 52       | 0.59%   |
| Corsair                              | 49       | 0.56%   |
| Generalplus Technology               | 44       | 0.5%    |
| Creative Technology                  | 43       | 0.49%   |
| Micro Star International             | 36       | 0.41%   |
| GN Netcom                            | 36       | 0.41%   |
| Plantronics                          | 32       | 0.36%   |
| Blue Microphones                     | 26       | 0.3%    |
| Realtek Semiconductor                | 25       | 0.28%   |
| Sony                                 | 23       | 0.26%   |
| Samson Technologies                  | 21       | 0.24%   |
| RODE Microphones                     | 20       | 0.23%   |
| GYROCOM C&C                          | 20       | 0.23%   |
| XMOS                                 | 15       | 0.17%   |
| Dell                                 | 15       | 0.17%   |
| Tenx Technology                      | 14       | 0.16%   |
| Giga-Byte Technology                 | 13       | 0.15%   |
| Thesycon Systemsoftware & Consulting | 12       | 0.14%   |
| M-Audio                              | 12       | 0.14%   |
| DSEA A/S                             | 12       | 0.14%   |
| Cambridge Silicon Radio              | 12       | 0.14%   |
| VIA Technologies                     | 11       | 0.12%   |
| Schiit Audio                         | 11       | 0.12%   |
| Hewlett-Packard                      | 11       | 0.12%   |
| Yamaha                               | 10       | 0.11%   |
| SAVITECH                             | 10       | 0.11%   |
| KTMicro                              | 10       | 0.11%   |
| FiiO Electronics Technology          | 10       | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 799      | 7.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 411      | 3.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 379      | 3.6%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 368      | 3.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 308      | 2.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 301      | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 275      | 2.61%   |
| Intel 200 Series PCH HD Audio                                              | 270      | 2.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 243      | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 241      | 2.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 223      | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 203      | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 194      | 1.84%   |
| Nvidia GP107GL High Definition Audio Controller                            | 186      | 1.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 179      | 1.7%    |
| AMD Navi 10 HDMI Audio                                                     | 177      | 1.68%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 163      | 1.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 155      | 1.47%   |
| Nvidia GP104 High Definition Audio Controller                              | 137      | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                              | 135      | 1.28%   |
| Intel Alder Lake-S HD Audio Controller                                     | 127      | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 123      | 1.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 123      | 1.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 111      | 1.05%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 108      | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                              | 104      | 0.99%   |
| AMD FCH Azalia Controller                                                  | 100      | 0.95%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 97       | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 92       | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 91       | 0.86%   |
| Nvidia TU104 HD Audio Controller                                           | 77       | 0.73%   |
| Nvidia High Definition Audio Controller                                    | 77       | 0.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 75       | 0.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 74       | 0.7%    |
| Nvidia GP108 High Definition Audio Controller                              | 69       | 0.66%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 67       | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                              | 66       | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 66       | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                              | 63       | 0.6%    |
| Nvidia GA106 High Definition Audio Controller                              | 62       | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 436      | 18.37%  |
| Corsair             | 414      | 17.44%  |
| G.Skill             | 311      | 13.1%   |
| Unknown             | 227      | 9.56%   |
| Crucial             | 184      | 7.75%   |
| Samsung Electronics | 173      | 7.29%   |
| SK hynix            | 158      | 6.66%   |
| Micron Technology   | 97       | 4.09%   |
| A-DATA Technology   | 60       | 2.53%   |
| Team                | 46       | 1.94%   |
| Patriot             | 40       | 1.68%   |
| Unknown             | 26       | 1.1%    |
| Ramaxel Technology  | 17       | 0.72%   |
| Smart               | 15       | 0.63%   |
| Nanya Technology    | 15       | 0.63%   |
| Elpida              | 10       | 0.42%   |
| GeIL                | 9        | 0.38%   |
| AMD                 | 9        | 0.38%   |
| Transcend           | 8        | 0.34%   |
| Silicon Power       | 8        | 0.34%   |
| GOODRAM             | 8        | 0.34%   |
| PNY                 | 7        | 0.29%   |
| Apacer              | 6        | 0.25%   |
| Unknown (ABCD)      | 4        | 0.17%   |
| Qumo                | 4        | 0.17%   |
| Qimonda             | 4        | 0.17%   |
| Patriot Memory      | 4        | 0.17%   |
| Avant               | 4        | 0.17%   |
| Unifosa             | 3        | 0.13%   |
| CSX                 | 3        | 0.13%   |
| Atermiter           | 3        | 0.13%   |
| V-GeN               | 2        | 0.08%   |
| Timetec             | 2        | 0.08%   |
| TakeMS              | 2        | 0.08%   |
| Sesame              | 2        | 0.08%   |
| OCZ                 | 2        | 0.08%   |
| Mushkin             | 2        | 0.08%   |
| MINPO               | 2        | 0.08%   |
| Kllisre             | 2        | 0.08%   |
| Goldkey             | 2        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 43       | 1.67%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s  | 27       | 1.05%   |
| Unknown                                                | 26       | 1.01%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 25       | 0.97%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 25       | 0.97%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 19       | 0.74%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 18       | 0.7%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 18       | 0.7%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s | 18       | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 15       | 0.58%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 15       | 0.58%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 14       | 0.54%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 14       | 0.54%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 14       | 0.54%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 13       | 0.5%    |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s    | 12       | 0.47%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 12       | 0.47%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s | 12       | 0.47%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s    | 11       | 0.43%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s  | 11       | 0.43%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s | 11       | 0.43%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 11       | 0.43%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 10       | 0.39%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 10       | 0.39%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 10       | 0.39%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s  | 10       | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 9        | 0.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 9        | 0.35%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 9        | 0.35%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 9        | 0.35%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s    | 9        | 0.35%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s     | 9        | 0.35%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s  | 9        | 0.35%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s  | 9        | 0.35%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 8        | 0.31%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s      | 8        | 0.31%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 8        | 0.31%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s | 8        | 0.31%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s | 8        | 0.31%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 7        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 1239     | 58.17%  |
| DDR3    | 558      | 26.2%   |
| Unknown | 98       | 4.6%    |
| DDR5    | 87       | 4.08%   |
| DDR2    | 75       | 3.52%   |
| SDRAM   | 50       | 2.35%   |
| DDR     | 12       | 0.56%   |
| LPDDR4  | 5        | 0.23%   |
| LPDDR3  | 3        | 0.14%   |
| DRAM    | 3        | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1984     | 94.39%  |
| SODIMM       | 101      | 4.8%    |
| RIMM         | 11       | 0.52%   |
| Row Of Chips | 3        | 0.14%   |
| FB-DIMM      | 3        | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 929      | 40.67%  |
| 16384 | 512      | 22.42%  |
| 4096  | 421      | 18.43%  |
| 2048  | 198      | 8.67%   |
| 32768 | 174      | 7.62%   |
| 1024  | 43       | 1.88%   |
| 512   | 4        | 0.18%   |
| 49152 | 2        | 0.09%   |
| 256   | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 320      | 13.72%  |
| 3200    | 300      | 12.86%  |
| 3600    | 224      | 9.61%   |
| 1333    | 185      | 7.93%   |
| 2400    | 139      | 5.96%   |
| 2133    | 113      | 4.85%   |
| 2667    | 97       | 4.16%   |
| 3733    | 67       | 2.87%   |
| 800     | 67       | 2.87%   |
| 3800    | 58       | 2.49%   |
| 3000    | 56       | 2.4%    |
| 3400    | 54       | 2.32%   |
| 667     | 46       | 1.97%   |
| 1867    | 44       | 1.89%   |
| 2666    | 41       | 1.76%   |
| 4800    | 33       | 1.42%   |
| 2933    | 31       | 1.33%   |
| 1800    | 31       | 1.33%   |
| 3866    | 30       | 1.29%   |
| 1866    | 30       | 1.29%   |
| 3533    | 29       | 1.24%   |
| Unknown | 28       | 1.2%    |
| 3466    | 25       | 1.07%   |
| 3666    | 19       | 0.81%   |
| 1066    | 19       | 0.81%   |
| 2800    | 18       | 0.77%   |
| 6000    | 13       | 0.56%   |
| 5600    | 12       | 0.51%   |
| 3534    | 12       | 0.51%   |
| 3066    | 12       | 0.51%   |
| 1067    | 12       | 0.51%   |
| 5200    | 11       | 0.47%   |
| 6400    | 9        | 0.39%   |
| 3100    | 9        | 0.39%   |
| 4000    | 8        | 0.34%   |
| 2733    | 8        | 0.34%   |
| 1334    | 8        | 0.34%   |
| 3334    | 7        | 0.3%    |
| 533     | 7        | 0.3%    |
| 3333    | 6        | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 79       | 39.11%  |
| Brother Industries    | 49       | 24.26%  |
| Canon                 | 22       | 10.89%  |
| Seiko Epson           | 14       | 6.93%   |
| Samsung Electronics   | 13       | 6.44%   |
| Prolific Technology   | 5        | 2.48%   |
| Dymo-CoStar           | 5        | 2.48%   |
| Lexmark International | 4        | 1.98%   |
| Xerox                 | 2        | 0.99%   |
| Kyocera               | 2        | 0.99%   |
| Star Micronics        | 1        | 0.5%    |
| SAT                   | 1        | 0.5%    |
| QinHeng Electronics   | 1        | 0.5%    |
| Pantum                | 1        | 0.5%    |
| Graphtec America      | 1        | 0.5%    |
| Dell                  | 1        | 0.5%    |
| Boca Systems          | 1        | 0.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Samsung M2070 Series                         | 5        | 2.46%   |
| Prolific PL2305 Parallel Port                | 5        | 2.46%   |
| HP ENVY 5000 series                          | 5        | 2.46%   |
| HP LaserJet Professional P 1102w             | 4        | 1.97%   |
| Brother HL-L2340D series                     | 4        | 1.97%   |
| HP ENVY 4520 series                          | 3        | 1.48%   |
| HP DeskJet F300 series                       | 3        | 1.48%   |
| HP DeskJet 3700 series                       | 3        | 1.48%   |
| HP DeskJet 2700 series                       | 3        | 1.48%   |
| Brother Printer                              | 3        | 1.48%   |
| Brother HL-1110 series                       | 3        | 1.48%   |
| Seiko Epson WF-2860 Series                   | 2        | 0.99%   |
| Seiko Epson Printer                          | 2        | 0.99%   |
| Samsung ML-216x Series Laser Printer         | 2        | 0.99%   |
| HP OfficeJet 6950                            | 2        | 0.99%   |
| HP LaserJet Professional P1102w              | 2        | 0.99%   |
| HP LaserJet P1102                            | 2        | 0.99%   |
| HP LaserJet 1020                             | 2        | 0.99%   |
| HP LaserJet 1010                             | 2        | 0.99%   |
| HP DeskJet 3630 series                       | 2        | 0.99%   |
| HP DeskJet 2600 series                       | 2        | 0.99%   |
| HP DeskJet 2130 series                       | 2        | 0.99%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 2        | 0.99%   |
| Canon TS3300 series                          | 2        | 0.99%   |
| Canon TS3100 series                          | 2        | 0.99%   |
| Canon TR4500 series                          | 2        | 0.99%   |
| Canon CanoScan LiDE 300                      | 2        | 0.99%   |
| Brother MFC-L2710DW series                   | 2        | 0.99%   |
| Brother MFC-9330CDW                          | 2        | 0.99%   |
| Brother HL-2230 series                       | 2        | 0.99%   |
| Brother HL-2030 Laser Printer                | 2        | 0.99%   |
| Brother HL-1440 Laser Printer                | 2        | 0.99%   |
| Xerox Phaser 6500N                           | 1        | 0.49%   |
| Xerox Phaser 3010                            | 1        | 0.49%   |
| Star Micronics TUP592 (STR_T-001)            | 1        | 0.49%   |
| Seiko Epson XP-100 Series                    | 1        | 0.49%   |
| Seiko Epson WP-4020 Series                   | 1        | 0.49%   |
| Seiko Epson WF-2510 Series                   | 1        | 0.49%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.49%   |
| Seiko Epson L360 Series                      | 1        | 0.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 32       | 59.26%  |
| Seiko Epson        | 15       | 27.78%  |
| Hewlett-Packard    | 4        | 7.41%   |
| UMAX               | 1        | 1.85%   |
| Ultima Electronics | 1        | 1.85%   |
| Mustek Systems     | 1        | 1.85%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 7        | 12.96%  |
| Seiko Epson GT-X770 [Perfection V500]                    | 5        | 9.26%   |
| Canon CanoScan LiDE 220                                  | 5        | 9.26%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 4        | 7.41%   |
| Canon CanoScan LIDE 25                                   | 3        | 5.56%   |
| Canon CanoScan LiDE 110                                  | 3        | 5.56%   |
| Canon CanoScan LiDE 100                                  | 3        | 5.56%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 2        | 3.7%    |
| Seiko Epson GT-6600U [Perfection 610]                    | 2        | 3.7%    |
| Canon CanoScan 4400F                                     | 2        | 3.7%    |
| UMAX Astra 2200/2200SU                                   | 1        | 1.85%   |
| Ultima Artec E+ Pro                                      | 1        | 1.85%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1        | 1.85%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]  | 1        | 1.85%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]              | 1        | 1.85%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 1.85%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1        | 1.85%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]            | 1        | 1.85%   |
| Mustek Systems BearPaw 2448 TA Plus                      | 1        | 1.85%   |
| HP ScanJet G4050                                         | 1        | 1.85%   |
| HP ScanJet 5590                                          | 1        | 1.85%   |
| HP ScanJet 3400cse                                       | 1        | 1.85%   |
| HP ScanJet 2400c                                         | 1        | 1.85%   |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 1.85%   |
| Canon CanoScan LiDE 700F                                 | 1        | 1.85%   |
| Canon CanoScan LiDE 70                                   | 1        | 1.85%   |
| Canon CanoScan LiDE 200                                  | 1        | 1.85%   |
| Canon CanoScan LiDE 120                                  | 1        | 1.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 533      | 44.53%  |
| Microsoft                              | 91       | 7.6%    |
| Microdia                               | 74       | 6.18%   |
| Apple                                  | 41       | 3.43%   |
| Samsung Electronics                    | 37       | 3.09%   |
| Sunplus Innovation Technology          | 36       | 3.01%   |
| Realtek Semiconductor                  | 27       | 2.26%   |
| Chicony Electronics                    | 22       | 1.84%   |
| KYE Systems (Mouse Systems)            | 21       | 1.75%   |
| Generalplus Technology                 | 20       | 1.67%   |
| ARC International                      | 19       | 1.59%   |
| Creative Technology                    | 16       | 1.34%   |
| Razer USA                              | 15       | 1.25%   |
| Z-Star Microelectronics                | 14       | 1.17%   |
| webcamvendor                           | 14       | 1.17%   |
| Cubeternet                             | 14       | 1.17%   |
| Jieli Technology                       | 12       | 1%      |
| Trust                                  | 11       | 0.92%   |
| AVerMedia Technologies                 | 11       | 0.92%   |
| MacroSilicon                           | 9        | 0.75%   |
| GEMBIRD                                | 9        | 0.75%   |
| Hewlett-Packard                        | 8        | 0.67%   |
| Lenovo                                 | 7        | 0.58%   |
| Aveo Technology                        | 6        | 0.5%    |
| LG Electronics                         | 5        | 0.42%   |
| Arkmicro Technologies                  | 5        | 0.42%   |
| Valve Software                         | 4        | 0.33%   |
| Google                                 | 4        | 0.33%   |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.33%   |
| Asuscom Network                        | 4        | 0.33%   |
| Alcor Micro                            | 4        | 0.33%   |
| A4Tech                                 | 4        | 0.33%   |
| Unknown                                | 4        | 0.33%   |
| YGTek                                  | 3        | 0.25%   |
| WaveRider Communications               | 3        | 0.25%   |
| Unknown                                | 3        | 0.25%   |
| Tobii Technology AB                    | 3        | 0.25%   |
| Sunplus IT                             | 3        | 0.25%   |
| Sonix Technology                       | 3        | 0.25%   |
| OmniVision Technologies                | 3        | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920               | 111      | 9.15%   |
| Logitech Webcam C270                      | 108      | 8.9%    |
| Samsung Galaxy series, misc. (MTP mode)   | 36       | 2.97%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR        | 36       | 2.97%   |
| Logitech HD Webcam C525                   | 33       | 2.72%   |
| Logitech C922 Pro Stream Webcam           | 32       | 2.64%   |
| Microsoft LifeCam HD-3000                 | 31       | 2.56%   |
| Microdia Webcam Vitade AF                 | 26       | 2.14%   |
| Logitech Webcam C310                      | 24       | 1.98%   |
| Logitech HD Webcam C615                   | 23       | 1.9%    |
| Logitech Webcam C170                      | 22       | 1.81%   |
| Logitech C920 PRO HD Webcam               | 22       | 1.81%   |
| Microdia USB 2.0 Camera                   | 21       | 1.73%   |
| Logitech BRIO Ultra HD Webcam             | 19       | 1.57%   |
| ARC International Camera                  | 19       | 1.57%   |
| Microsoft LifeCam Cinema                  | 18       | 1.48%   |
| Logitech Webcam Pro 9000                  | 16       | 1.32%   |
| webcamvendor webcamproduct                | 14       | 1.15%   |
| Generalplus GENERAL WEBCAM                | 14       | 1.15%   |
| Logitech Webcam C925e                     | 13       | 1.07%   |
| Logitech Webcam C930e                     | 12       | 0.99%   |
| Jieli USB PHY 2.0                         | 12       | 0.99%   |
| Logitech StreamCam                        | 11       | 0.91%   |
| Sunplus HD 720P webcam                    | 10       | 0.82%   |
| Logitech QuickCam Pro 9000                | 10       | 0.82%   |
| Realtek Full HD webcam                    | 9        | 0.74%   |
| Microdia Camera                           | 9        | 0.74%   |
| Logitech BRIO 4K Stream Edition           | 8        | 0.66%   |
| Trust USB Camera                          | 7        | 0.58%   |
| Razer USA Gaming Webcam [Kiyo]            | 7        | 0.58%   |
| Microsoft LifeCam Studio                  | 7        | 0.58%   |
| Microdia Integrated Camera                | 7        | 0.58%   |
| MacroSilicon USB3. 0 capture              | 7        | 0.58%   |
| Logitech HD Webcam C910                   | 7        | 0.58%   |
| KYE Systems (Mouse Systems) Genius Webcam | 7        | 0.58%   |
| AVerMedia Live Streamer CAM 313           | 7        | 0.58%   |
| Sunplus Full HD webcam                    | 6        | 0.49%   |
| Razer USA Razer Kiyo Pro                  | 6        | 0.49%   |
| Microsoft MicrosoftÂ LifeCam Cinema      | 6        | 0.49%   |
| Microsoft LifeCam VX-5000                 | 6        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 3        | 16.67%  |
| Elan Microelectronics | 3        | 16.67%  |
| DigitalPersona        | 3        | 16.67%  |
| AuthenTec             | 3        | 16.67%  |
| Synaptics             | 2        | 11.11%  |
| Dell                  | 2        | 11.11%  |
| Upek                  | 1        | 5.56%   |
| Microsoft             | 1        | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 3        | 16.67%  |
| DigitalPersona Fingerprint Reader              | 3        | 16.67%  |
| Synaptics  WBDI Fingerprint Reader - USB 052   | 2        | 11.11%  |
| LighTuning Fingerprint Sensor                  | 2        | 11.11%  |
| Dell MS819 Wired Mouse With Fingerprint Reader | 2        | 11.11%  |
| AuthenTec Fingerprint Sensor                   | 2        | 11.11%  |
| Upek TCS1C EIM/STM32 Fingerprint sensor        | 1        | 5.56%   |
| Microsoft Fingerprint Reader                   | 1        | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor    | 1        | 5.56%   |
| AuthenTec AES1600                              | 1        | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Yubico.com                        | 6        | 13.33%  |
| Realtek Semiconductor             | 6        | 13.33%  |
| Alcor Micro                       | 5        | 11.11%  |
| VASCO Data Security International | 4        | 8.89%   |
| SCM Microsystems                  | 4        | 8.89%   |
| OmniKey                           | 3        | 6.67%   |
| Gemalto (was Gemplus)             | 3        | 6.67%   |
| Cherry                            | 2        | 4.44%   |
| Aladdin Knowledge Systems         | 2        | 4.44%   |
| Aktiv                             | 2        | 4.44%   |
| Advanced Card Systems             | 2        | 4.44%   |
| Reiner SCT Kartensysteme          | 1        | 2.22%   |
| Fujitsu Siemens Computers         | 1        | 2.22%   |
| Feitian Technologies              | 1        | 2.22%   |
| Clay Logic                        | 1        | 2.22%   |
| Chicony Electronics               | 1        | 2.22%   |
| Bit4id                            | 1        | 2.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 6        | 13.33%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 4        | 8.89%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 3        | 6.67%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 6.67%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 6.67%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 6.67%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 4.44%   |
| Aladdin Knowledge Systems Token JC                                         | 2        | 4.44%   |
| Aktiv Rutoken lite                                                         | 2        | 4.44%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                        | 1        | 2.22%   |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 2.22%   |
| VASCO Data Security International DIGIPASS 870                             | 1        | 2.22%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                 | 1        | 2.22%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.22%   |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 2.22%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.22%   |
| OmniKey CardMan 1021                                                       | 1        | 2.22%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.22%   |
| Feitian Technologies FT SCR310                                             | 1        | 2.22%   |
| Clay Logic Nitrokey Pro                                                    | 1        | 2.22%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 2.22%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 2.22%   |
| Cherry Smart Terminal XX44                                                 | 1        | 2.22%   |
| Bit4id miniLector EVO                                                      | 1        | 2.22%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 2.22%   |
| Advanced Card Systems ACR122U                                              | 1        | 2.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 4055     | 85.14%  |
| 1     | 606      | 12.72%  |
| 2     | 67       | 1.41%   |
| 3     | 18       | 0.38%   |
| 4     | 10       | 0.21%   |
| 5     | 4        | 0.08%   |
| 6     | 2        | 0.04%   |
| 8     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 243      | 30.34%  |
| Net/wireless             | 229      | 28.59%  |
| Unassigned class         | 74       | 9.24%   |
| Sound                    | 47       | 5.87%   |
| Multimedia controller    | 41       | 5.12%   |
| Camera                   | 37       | 4.62%   |
| Communication controller | 35       | 4.37%   |
| Fingerprint reader       | 16       | 2%      |
| Bluetooth                | 15       | 1.87%   |
| Storage/raid             | 13       | 1.62%   |
| Network                  | 11       | 1.37%   |
| Net/ethernet             | 11       | 1.37%   |
| Card reader              | 7        | 0.87%   |
| Chipcard                 | 6        | 0.75%   |
| Modem                    | 5        | 0.62%   |
| Firewire controller      | 4        | 0.5%    |
| Dvb card                 | 2        | 0.25%   |
| Wireless                 | 1        | 0.12%   |
| Tv card                  | 1        | 0.12%   |
| Storage/nvme             | 1        | 0.12%   |
| Storage/ata              | 1        | 0.12%   |
| Storage                  | 1        | 0.12%   |

