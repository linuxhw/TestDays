Linux in Croatia - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

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

Total: 345

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME Z890-P                | [c534bd7c2a](https://linux-hardware.org/?probe=c534bd7c2a) | Dec 27, 2025 |
| MSI           | B450-A PRO MAX              | [4e0a622a8d](https://linux-hardware.org/?probe=4e0a622a8d) | Dec 20, 2025 |
| RUNING        | X79 VB1.0                   | [3ec9d4080d](https://linux-hardware.org/?probe=3ec9d4080d) | Dec 12, 2025 |
| Gigabyte      | B450M DS3H-CF               | [679d7bdb80](https://linux-hardware.org/?probe=679d7bdb80) | Dec 08, 2025 |
| ASRock        | B650M-HDV/M.2               | [240a18463d](https://linux-hardware.org/?probe=240a18463d) | Dec 05, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [76bcf66e25](https://linux-hardware.org/?probe=76bcf66e25) | Dec 05, 2025 |
| ASRock        | H610M-HDV/M.2               | [61c2456b61](https://linux-hardware.org/?probe=61c2456b61) | Nov 28, 2025 |
| HP            | 18E7                        | [7fa8cd3ff6](https://linux-hardware.org/?probe=7fa8cd3ff6) | Nov 24, 2025 |
| HP            | 18E7                        | [6380da5baa](https://linux-hardware.org/?probe=6380da5baa) | Nov 24, 2025 |
| Gigabyte      | 970A-UD3P                   | [59759f1ca8](https://linux-hardware.org/?probe=59759f1ca8) | Nov 16, 2025 |
| Gigabyte      | H77M-D3H                    | [5835eaf267](https://linux-hardware.org/?probe=5835eaf267) | Nov 14, 2025 |
| Gigabyte      | H77M-D3H                    | [79fa61f75c](https://linux-hardware.org/?probe=79fa61f75c) | Nov 14, 2025 |
| Gigabyte      | AB350M-Gaming 3-CF          | [da42036c62](https://linux-hardware.org/?probe=da42036c62) | Nov 11, 2025 |
| Shenzhen M... | AHBNB OEM                   | [6b8c6e82a4](https://linux-hardware.org/?probe=6b8c6e82a4) | Nov 02, 2025 |
| GEEKOM        | A8                          | [1c879653f0](https://linux-hardware.org/?probe=1c879653f0) | Nov 01, 2025 |
| Gigabyte      | 970A-UD3P                   | [86ea95eba1](https://linux-hardware.org/?probe=86ea95eba1) | Oct 12, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [486fbc4bb6](https://linux-hardware.org/?probe=486fbc4bb6) | Oct 01, 2025 |
| GARAGE        | 775i65G                     | [5ff35e7037](https://linux-hardware.org/?probe=5ff35e7037) | Sep 17, 2025 |
| Lenovo        | 3141 SDK0J40697 WIN 3305... | [cf1ccb412f](https://linux-hardware.org/?probe=cf1ccb412f) | Sep 12, 2025 |
| ASRock        | B450M Pro4                  | [b524e7fcfe](https://linux-hardware.org/?probe=b524e7fcfe) | Aug 25, 2025 |
| MSI           | H61M-P20                    | [f77e708e7b](https://linux-hardware.org/?probe=f77e708e7b) | Jul 29, 2025 |
| ASRock        | 970 Pro3 R2.0               | [8c401a9e1b](https://linux-hardware.org/?probe=8c401a9e1b) | Jul 20, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f6c7ce8af4](https://linux-hardware.org/?probe=f6c7ce8af4) | Jul 02, 2025 |
| ASUSTek       | PRIME B840M-A WIFI          | [f6514e8750](https://linux-hardware.org/?probe=f6514e8750) | Jun 19, 2025 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [1be7f7ed63](https://linux-hardware.org/?probe=1be7f7ed63) | Jun 17, 2025 |
| ASUSTek       | Z170-A                      | [ab7acfc669](https://linux-hardware.org/?probe=ab7acfc669) | Jun 06, 2025 |
| ASUSTek       | PRIME B550M-A               | [5a0112d369](https://linux-hardware.org/?probe=5a0112d369) | Jun 01, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | [f64017876b](https://linux-hardware.org/?probe=f64017876b) | May 30, 2025 |
| MSI           | X79A-GD45 Plus              | [cf9f503e11](https://linux-hardware.org/?probe=cf9f503e11) | May 29, 2025 |
| ASUSTek       | PRIME B840M-A WIFI          | [a79556481f](https://linux-hardware.org/?probe=a79556481f) | May 27, 2025 |
| Gigabyte      | B450 GAMING X               | [b2d0d0f17a](https://linux-hardware.org/?probe=b2d0d0f17a) | May 15, 2025 |
| Gigabyte      | Z390 GAMING X-CF            | [47eed7059c](https://linux-hardware.org/?probe=47eed7059c) | May 10, 2025 |
| Gigabyte      | Z390 GAMING X-CF            | [277381e0f4](https://linux-hardware.org/?probe=277381e0f4) | May 09, 2025 |
| ASRock        | B650M Pro RS                | [929c1e925a](https://linux-hardware.org/?probe=929c1e925a) | May 02, 2025 |
| MSI           | PRO B650-A WIFI             | [905fc52a67](https://linux-hardware.org/?probe=905fc52a67) | Apr 23, 2025 |
| Gigabyte      | B650M D3HP                  | [c4215927cd](https://linux-hardware.org/?probe=c4215927cd) | Apr 23, 2025 |
| Gigabyte      | AB350M-Gaming 3-CF          | [c91410327a](https://linux-hardware.org/?probe=c91410327a) | Apr 18, 2025 |
| ASUSTek       | B75M-A                      | [c517058f1f](https://linux-hardware.org/?probe=c517058f1f) | Apr 14, 2025 |
| ASRock        | B450M-HDV R4.0              | [c34096a43d](https://linux-hardware.org/?probe=c34096a43d) | Apr 10, 2025 |
| Gigabyte      | B550M DS3H                  | [714b80920c](https://linux-hardware.org/?probe=714b80920c) | Apr 05, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [23a7e30d1b](https://linux-hardware.org/?probe=23a7e30d1b) | Mar 30, 2025 |
| ASRock        | B650M-HDV/M.2               | [a55911ac71](https://linux-hardware.org/?probe=a55911ac71) | Mar 26, 2025 |
| ASRock        | B560 Steel Legend           | [23fb9edc5a](https://linux-hardware.org/?probe=23fb9edc5a) | Mar 21, 2025 |
| ASUSTek       | P5KC                        | [d576625cd4](https://linux-hardware.org/?probe=d576625cd4) | Mar 16, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a768ed4646](https://linux-hardware.org/?probe=a768ed4646) | Mar 15, 2025 |
| ASRock        | H110M-HDV R3.0              | [a970826785](https://linux-hardware.org/?probe=a970826785) | Mar 15, 2025 |
| Gigabyte      | B550M DS3H                  | [b99f2487da](https://linux-hardware.org/?probe=b99f2487da) | Mar 02, 2025 |
| GARAGE        | 775i65G                     | [0d16cd7346](https://linux-hardware.org/?probe=0d16cd7346) | Mar 02, 2025 |
| HP            | 8055                        | [7ef369214e](https://linux-hardware.org/?probe=7ef369214e) | Feb 14, 2025 |
| ASRock        | 880G Extreme3               | [533616e811](https://linux-hardware.org/?probe=533616e811) | Jan 29, 2025 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [70479fdb19](https://linux-hardware.org/?probe=70479fdb19) | Jan 29, 2025 |
| ASRock        | 880G Extreme3               | [d37def4689](https://linux-hardware.org/?probe=d37def4689) | Jan 27, 2025 |
| ASUSTek       | Z97M-PLUS                   | [dfd173b83d](https://linux-hardware.org/?probe=dfd173b83d) | Jan 21, 2025 |
| Gigabyte      | MFLP7IP-00                  | [744d15cd68](https://linux-hardware.org/?probe=744d15cd68) | Jan 19, 2025 |
| BESSTAR Te... | UM350                       | [4a64dc33c3](https://linux-hardware.org/?probe=4a64dc33c3) | Jan 18, 2025 |
| ASUSTek       | PRIME B550M-A               | [975a1199f7](https://linux-hardware.org/?probe=975a1199f7) | Jan 17, 2025 |
| ASRock        | A320M-HDV                   | [01c2e4a226](https://linux-hardware.org/?probe=01c2e4a226) | Jan 12, 2025 |
| Gigabyte      | Z370 AORUS Gaming 7         | [47ce7960b6](https://linux-hardware.org/?probe=47ce7960b6) | Jan 09, 2025 |
| ASRock        | H510M-HDV/M.2 SE            | [cd15dad76b](https://linux-hardware.org/?probe=cd15dad76b) | Jan 02, 2025 |
| HP            | 1495                        | [f9588cf3eb](https://linux-hardware.org/?probe=f9588cf3eb) | Dec 30, 2024 |
| Gigabyte      | B550M DS3H                  | [01c866bd0e](https://linux-hardware.org/?probe=01c866bd0e) | Dec 21, 2024 |
| ASRock        | B650M PG Lightning          | [93343b543c](https://linux-hardware.org/?probe=93343b543c) | Dec 16, 2024 |
| Gigabyte      | H97M-HD3                    | [0e0965bc17](https://linux-hardware.org/?probe=0e0965bc17) | Dec 15, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | [c43094abf1](https://linux-hardware.org/?probe=c43094abf1) | Dec 14, 2024 |
| ASRock        | B250M-HDV                   | [feade65edb](https://linux-hardware.org/?probe=feade65edb) | Dec 13, 2024 |
| ASRock        | B650M PG Lightning          | [4370a5ccdf](https://linux-hardware.org/?probe=4370a5ccdf) | Dec 11, 2024 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [c2162b5ffe](https://linux-hardware.org/?probe=c2162b5ffe) | Nov 30, 2024 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [1997f45737](https://linux-hardware.org/?probe=1997f45737) | Nov 28, 2024 |
| HP            | 81C5 MVB                    | [18206773c5](https://linux-hardware.org/?probe=18206773c5) | Nov 24, 2024 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [efffc4e893](https://linux-hardware.org/?probe=efffc4e893) | Nov 05, 2024 |
| HP            | 3048h                       | [8984b9b0ff](https://linux-hardware.org/?probe=8984b9b0ff) | Oct 31, 2024 |
| HP            | 1495                        | [2fd3ea9199](https://linux-hardware.org/?probe=2fd3ea9199) | Oct 25, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | [632d66a3f3](https://linux-hardware.org/?probe=632d66a3f3) | Oct 23, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [abab79db3c](https://linux-hardware.org/?probe=abab79db3c) | Oct 19, 2024 |
| ASRock        | A620M-HDV/M.2               | [2f77fd05f6](https://linux-hardware.org/?probe=2f77fd05f6) | Oct 15, 2024 |
| EMC           | 110-335-541B-04 FFF         | [a45ce6a612](https://linux-hardware.org/?probe=a45ce6a612) | Oct 01, 2024 |
| Gigabyte      | A620M S2H                   | [125f5a8d74](https://linux-hardware.org/?probe=125f5a8d74) | Sep 10, 2024 |
| ASUSTek       | M5A97 R2.0                  | [1e5012faa8](https://linux-hardware.org/?probe=1e5012faa8) | Sep 05, 2024 |
| ASUSTek       | M5A97 R2.0                  | [03c509b9db](https://linux-hardware.org/?probe=03c509b9db) | Sep 02, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [18c81a5d40](https://linux-hardware.org/?probe=18c81a5d40) | Aug 24, 2024 |
| Gigabyte      | B450 AORUS M                | [6ef48298ce](https://linux-hardware.org/?probe=6ef48298ce) | Aug 13, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | [b2182890a9](https://linux-hardware.org/?probe=b2182890a9) | Aug 09, 2024 |
| ASRock        | H97 Anniversary             | [ec56437f32](https://linux-hardware.org/?probe=ec56437f32) | Jul 31, 2024 |
| ASRock        | B560 Steel Legend           | [d3002dc7c2](https://linux-hardware.org/?probe=d3002dc7c2) | Jul 29, 2024 |
| MAXSUN        | MS-TZZ B560M                | [cca7e1333d](https://linux-hardware.org/?probe=cca7e1333d) | Jul 23, 2024 |
| HP            | 18E4                        | [bcfb2d82b4](https://linux-hardware.org/?probe=bcfb2d82b4) | Jul 20, 2024 |
| ASRock        | B650 PG Lightning           | [69f46fe2a1](https://linux-hardware.org/?probe=69f46fe2a1) | Jul 04, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | [8211ffc9b9](https://linux-hardware.org/?probe=8211ffc9b9) | Jun 07, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [15dd095045](https://linux-hardware.org/?probe=15dd095045) | Jun 01, 2024 |
| ASUSTek       | M5A78L LE                   | [5afe282618](https://linux-hardware.org/?probe=5afe282618) | May 27, 2024 |
| Gigabyte      | B760 GAMING X DDR4          | [740702872c](https://linux-hardware.org/?probe=740702872c) | May 27, 2024 |
| Gigabyte      | B550M DS3H                  | [34390c3261](https://linux-hardware.org/?probe=34390c3261) | May 12, 2024 |
| Gigabyte      | B550M DS3H                  | [3d5dfb554e](https://linux-hardware.org/?probe=3d5dfb554e) | May 12, 2024 |
| HP            | 1496                        | [64f726b9c5](https://linux-hardware.org/?probe=64f726b9c5) | Apr 30, 2024 |
| ASUSTek       | PRIME B560M-A               | [886328abc3](https://linux-hardware.org/?probe=886328abc3) | Apr 25, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [0b8cd1192f](https://linux-hardware.org/?probe=0b8cd1192f) | Apr 24, 2024 |
| HP            | 8876 11                     | [b15b96ee62](https://linux-hardware.org/?probe=b15b96ee62) | Apr 23, 2024 |
| MSI           | PRO Z790-P WIFI             | [3ac4d133b8](https://linux-hardware.org/?probe=3ac4d133b8) | Apr 23, 2024 |
| Dell          | 06JWJY A01                  | [824cb2807f](https://linux-hardware.org/?probe=824cb2807f) | Apr 11, 2024 |
| HP            | 1495                        | [7bb71cc6c8](https://linux-hardware.org/?probe=7bb71cc6c8) | Apr 03, 2024 |
| HP            | 1495                        | [369904b953](https://linux-hardware.org/?probe=369904b953) | Apr 03, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | [74e95f0015](https://linux-hardware.org/?probe=74e95f0015) | Mar 24, 2024 |
| HP            | 83EF                        | [34c1c23a84](https://linux-hardware.org/?probe=34c1c23a84) | Mar 23, 2024 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [fac66be915](https://linux-hardware.org/?probe=fac66be915) | Mar 19, 2024 |
| Gigabyte      | B650M DS3H                  | [91f2211c0c](https://linux-hardware.org/?probe=91f2211c0c) | Feb 14, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [bf2ce0efeb](https://linux-hardware.org/?probe=bf2ce0efeb) | Jan 15, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [80799f979c](https://linux-hardware.org/?probe=80799f979c) | Jan 10, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ff9686f03c](https://linux-hardware.org/?probe=ff9686f03c) | Jan 06, 2024 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [7a9ff71d9b](https://linux-hardware.org/?probe=7a9ff71d9b) | Dec 28, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [58bbd67a73](https://linux-hardware.org/?probe=58bbd67a73) | Dec 23, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [155e0f1c37](https://linux-hardware.org/?probe=155e0f1c37) | Dec 22, 2023 |
| Dell          | 0R790T A00                  | [8a72b2a4ce](https://linux-hardware.org/?probe=8a72b2a4ce) | Dec 13, 2023 |
| eMachines     | ET1850                      | [b433ca3cfa](https://linux-hardware.org/?probe=b433ca3cfa) | Dec 02, 2023 |
| MSI           | PRO B650M-A WIFI            | [2a9ba6fc77](https://linux-hardware.org/?probe=2a9ba6fc77) | Nov 17, 2023 |
| HP            | 18E4                        | [fb73ea4228](https://linux-hardware.org/?probe=fb73ea4228) | Nov 12, 2023 |
| ASRock        | B450M-HDV R4.0              | [c019f410aa](https://linux-hardware.org/?probe=c019f410aa) | Nov 08, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [24304767eb](https://linux-hardware.org/?probe=24304767eb) | Oct 21, 2023 |
| Intel         | DG965RY AAD41691-301        | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [e0158c541c](https://linux-hardware.org/?probe=e0158c541c) | Sep 29, 2023 |
| Gigabyte      | X570S UD                    | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [5a6ff779bd](https://linux-hardware.org/?probe=5a6ff779bd) | Sep 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [bd389fb2a0](https://linux-hardware.org/?probe=bd389fb2a0) | Sep 15, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Intel         | DH61CR AAG14064-204         | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| ASRock        | B560 Steel Legend           | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| HP            | 2B47                        | [06373794be](https://linux-hardware.org/?probe=06373794be) | Aug 01, 2023 |
| ASRock        | B450M-HDV R4.0              | [289d9fe165](https://linux-hardware.org/?probe=289d9fe165) | Jun 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| MSI           | PRO Z690-A DDR4             | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| HPE           | ProLiant ML30 Gen10 Plus    | [3a75fa5c03](https://linux-hardware.org/?probe=3a75fa5c03) | May 07, 2023 |
| ASUSTek       | GRYPHON Z87                 | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| ASUSTek       | PRIME B560M-A               | [171e39cdb6](https://linux-hardware.org/?probe=171e39cdb6) | Apr 05, 2023 |
| MSI           | B450M PRO-M2 MAX            | [bdfe7a3498](https://linux-hardware.org/?probe=bdfe7a3498) | Mar 21, 2023 |
| ASUSTek       | H110M-R                     | [2409dc15b4](https://linux-hardware.org/?probe=2409dc15b4) | Mar 10, 2023 |
| ASRock        | H97 Pro4                    | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| MSI           | 0A90                        | [9210981559](https://linux-hardware.org/?probe=9210981559) | Feb 06, 2023 |
| MSI           | 0A90                        | [aedd414dbf](https://linux-hardware.org/?probe=aedd414dbf) | Feb 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| ASUSTek       | PRIME B560M-A               | [2b04043ef0](https://linux-hardware.org/?probe=2b04043ef0) | Jan 10, 2023 |
| ASRock        | B550M Steel Legend          | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [15d7102174](https://linux-hardware.org/?probe=15d7102174) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [52525a1058](https://linux-hardware.org/?probe=52525a1058) | Dec 08, 2022 |
| ASRock        | K10N78D                     | [b5e2e7a024](https://linux-hardware.org/?probe=b5e2e7a024) | Dec 02, 2022 |
| ASRock        | B550M-ITX/ac                | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| HP            | 1998                        | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| ASUSTek       | PRIME H410M-A               | [b3cac9f8b8](https://linux-hardware.org/?probe=b3cac9f8b8) | Nov 02, 2022 |
| ASUSTek       | PRIME B560M-A               | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| ASUSTek       | M5A78L LE                   | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Lenovo        | 0x30F617AA NOK              | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [0dca3e500c](https://linux-hardware.org/?probe=0dca3e500c) | Sep 22, 2022 |
| ASUSTek       | Z97-PRO                     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5ddb15f201](https://linux-hardware.org/?probe=5ddb15f201) | Aug 07, 2022 |
| HP            | 1825                        | [4a21a02ae4](https://linux-hardware.org/?probe=4a21a02ae4) | Jul 29, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [3c665fb25f](https://linux-hardware.org/?probe=3c665fb25f) | Jul 28, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| ASRock        | K10N78D                     | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| WinFast       | NF-MCP55 FAB1.0             | [bb066cc2da](https://linux-hardware.org/?probe=bb066cc2da) | Jul 03, 2022 |
| MSI           | Z87-G41 PC Mate             | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [0d4266a0f3](https://linux-hardware.org/?probe=0d4266a0f3) | Jun 15, 2022 |
| ASUSTek       | B250 MINING EXPERT          | [987ef7b2e7](https://linux-hardware.org/?probe=987ef7b2e7) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Gigabyte      | X48T-DQ6                    | [2953148fae](https://linux-hardware.org/?probe=2953148fae) | May 16, 2022 |
| Dell          | 0J37VM A01                  | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A               | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |
| ASRock        | Z87 Extreme4                | [db3a8bef92](https://linux-hardware.org/?probe=db3a8bef92) | May 09, 2022 |
| ASRock        | H470M-HDV                   | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| MSI           | B450 TOMAHAWK               | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| Gigabyte      | P31-ES3G                    | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| Intel         | H61M-S2PV                   | [caa602b556](https://linux-hardware.org/?probe=caa602b556) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| ASRock        | H61M-DGS                    | [c8019d43f7](https://linux-hardware.org/?probe=c8019d43f7) | Apr 25, 2022 |
| ASRock        | H97 Pro4                    | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Pegatron      | 2AC3                        | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| ASRock        | A320M-HDV R4.0              | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| Gigabyte      | X48T-DQ6                    | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [561a945c5a](https://linux-hardware.org/?probe=561a945c5a) | Mar 13, 2022 |
| ASRock        | B360 Gaming K4              | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| ASUSTek       | Z170-P                      | [fac84edcf2](https://linux-hardware.org/?probe=fac84edcf2) | Mar 08, 2022 |
| ASRock        | H97 Pro4                    | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | X48T-DQ6                    | [593cb60512](https://linux-hardware.org/?probe=593cb60512) | Mar 06, 2022 |
| Foxconn       | 2A8Ch                       | [49093d0be0](https://linux-hardware.org/?probe=49093d0be0) | Mar 05, 2022 |
| Gigabyte      | H410M H V3                  | [d0ee45a4b1](https://linux-hardware.org/?probe=d0ee45a4b1) | Feb 26, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [731457f46c](https://linux-hardware.org/?probe=731457f46c) | Feb 13, 2022 |
| ECS           | A75F2-M2                    | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| Gigabyte      | B85M-DS3H                   | [98d6451ac1](https://linux-hardware.org/?probe=98d6451ac1) | Feb 07, 2022 |
| ASRock        | Z97M Pro4                   | [a496090845](https://linux-hardware.org/?probe=a496090845) | Feb 01, 2022 |
| Foxconn       | 2A8Ch                       | [276caa5169](https://linux-hardware.org/?probe=276caa5169) | Jan 23, 2022 |
| ASRock        | Z590 Pro4                   | [a89877d9de](https://linux-hardware.org/?probe=a89877d9de) | Jan 16, 2022 |
| ASRock        | Z590 Pro4                   | [7a2453280a](https://linux-hardware.org/?probe=7a2453280a) | Jan 14, 2022 |
| ECS           | H61H2-M2                    | [21704ab656](https://linux-hardware.org/?probe=21704ab656) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | [47b4da86e2](https://linux-hardware.org/?probe=47b4da86e2) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | [f1f247b586](https://linux-hardware.org/?probe=f1f247b586) | Jan 09, 2022 |
| MSI           | H81M-P33                    | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| Gigabyte      | 965P-DS3                    | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| ECS           | H61H2-M2                    | [6f3d8856df](https://linux-hardware.org/?probe=6f3d8856df) | Dec 29, 2021 |
| ASRock        | 870 Extreme3                | [d202f241ee](https://linux-hardware.org/?probe=d202f241ee) | Dec 23, 2021 |
| Intel         | DH61CR AAG14064-204         | [13c79f41a6](https://linux-hardware.org/?probe=13c79f41a6) | Dec 18, 2021 |
| Intel         | DH61CR AAG14064-204         | [dbc555c5ad](https://linux-hardware.org/?probe=dbc555c5ad) | Dec 16, 2021 |
| ASRock        | B450M-HDV R4.0              | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | PRIME A320M-K               | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| Dell          | 0GDG8Y A00                  | [d0cf0cc443](https://linux-hardware.org/?probe=d0cf0cc443) | Dec 01, 2021 |
| Foxconn       | 2A8Ch                       | [1eff06a331](https://linux-hardware.org/?probe=1eff06a331) | Nov 30, 2021 |
| Foxconn       | 2A8Ch                       | [1f650ebd72](https://linux-hardware.org/?probe=1f650ebd72) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [c77e499435](https://linux-hardware.org/?probe=c77e499435) | Nov 13, 2021 |
| ASUSTek       | M4A78T-E                    | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| MSI           | P55-CD53                    | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| MSI           | P55-CD53                    | [12bf811a5c](https://linux-hardware.org/?probe=12bf811a5c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | M5A78L LE                   | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Pegatron      | 2A73h                       | [dc24d5d19f](https://linux-hardware.org/?probe=dc24d5d19f) | Oct 16, 2021 |
| ASUSTek       | PRIME H410M-R               | [d891006b52](https://linux-hardware.org/?probe=d891006b52) | Oct 14, 2021 |
| ASUSTek       | B85M-E                      | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| ASUSTek       | A58M-K                      | [2ca6ce79db](https://linux-hardware.org/?probe=2ca6ce79db) | Oct 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e5508ac7ab](https://linux-hardware.org/?probe=e5508ac7ab) | Sep 27, 2021 |
| ASUSTek       | M4A78T-E                    | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| MSI           | A320M PRO-VH PLUS           | [149504315f](https://linux-hardware.org/?probe=149504315f) | Aug 10, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| ASRock        | B450M-HDV R4.0              | [f15116c26a](https://linux-hardware.org/?probe=f15116c26a) | Jul 30, 2021 |
| ASRock        | Z370 Pro4                   | [9a9f7c5e69](https://linux-hardware.org/?probe=9a9f7c5e69) | Jul 20, 2021 |
| Gigabyte      | GA-990XA-UD3                | [af31bae015](https://linux-hardware.org/?probe=af31bae015) | Jun 10, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [83b3cc659a](https://linux-hardware.org/?probe=83b3cc659a) | Jun 07, 2021 |
| Dell          | 06CV2N A01                  | [35a0afd617](https://linux-hardware.org/?probe=35a0afd617) | May 25, 2021 |
| MSI           | B450 TOMAHAWK               | [eb4e8e4cc2](https://linux-hardware.org/?probe=eb4e8e4cc2) | May 25, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASRock        | P45DE                       | [2f6b602e36](https://linux-hardware.org/?probe=2f6b602e36) | Apr 18, 2021 |
| ASRock        | Z370 Pro4                   | [7ad77d82ba](https://linux-hardware.org/?probe=7ad77d82ba) | Apr 03, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [b776bc7947](https://linux-hardware.org/?probe=b776bc7947) | Mar 31, 2021 |
| MSI           | B450M PRO-M2 MAX            | [6e5e0c9ef4](https://linux-hardware.org/?probe=6e5e0c9ef4) | Mar 19, 2021 |
| MSI           | Z390-A PRO                  | [12566ee726](https://linux-hardware.org/?probe=12566ee726) | Mar 10, 2021 |
| Gigabyte      | G1.Sniper Z87               | [c9a3501b03](https://linux-hardware.org/?probe=c9a3501b03) | Mar 02, 2021 |
| ASRock        | FM2A75M-DGS                 | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME A320M-K               | [24a672b8ac](https://linux-hardware.org/?probe=24a672b8ac) | Feb 25, 2021 |
| ASRock        | Z87 Extreme4                | [081e14044d](https://linux-hardware.org/?probe=081e14044d) | Feb 13, 2021 |
| Dell          | 0NNGP2 A00                  | [9be58392b6](https://linux-hardware.org/?probe=9be58392b6) | Feb 08, 2021 |
| Dell          | 0J37VM A01                  | [3062914f46](https://linux-hardware.org/?probe=3062914f46) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | [34e1267a80](https://linux-hardware.org/?probe=34e1267a80) | Feb 07, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [eee7c1f592](https://linux-hardware.org/?probe=eee7c1f592) | Feb 03, 2021 |
| ASRock        | ConRoe1333-D667             | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | [28cb4726bb](https://linux-hardware.org/?probe=28cb4726bb) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | [0b4b751863](https://linux-hardware.org/?probe=0b4b751863) | Jan 31, 2021 |
| ASRock        | X570M Pro4                  | [9cd91004ab](https://linux-hardware.org/?probe=9cd91004ab) | Jan 24, 2021 |
| Gigabyte      | F2A78M-DS2                  | [9afb5c207a](https://linux-hardware.org/?probe=9afb5c207a) | Jan 23, 2021 |
| Dell          | 0DFRFW A01                  | [482bc5334f](https://linux-hardware.org/?probe=482bc5334f) | Jan 22, 2021 |
| MSI           | B450 TOMAHAWK               | [943284255a](https://linux-hardware.org/?probe=943284255a) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | [df34a7d718](https://linux-hardware.org/?probe=df34a7d718) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | [0d8e905a30](https://linux-hardware.org/?probe=0d8e905a30) | Jan 16, 2021 |
| ASUSTek       | Maximus VII HERO            | [9b72f3a82b](https://linux-hardware.org/?probe=9b72f3a82b) | Jan 11, 2021 |
| ASUSTek       | M4A78T-E                    | [e2fa1223c4](https://linux-hardware.org/?probe=e2fa1223c4) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                    | [db7dfe41a5](https://linux-hardware.org/?probe=db7dfe41a5) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | [2ca3b4e129](https://linux-hardware.org/?probe=2ca3b4e129) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | [638a245f5f](https://linux-hardware.org/?probe=638a245f5f) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H            | [15160d8a87](https://linux-hardware.org/?probe=15160d8a87) | Jan 02, 2021 |
| HP            | 18EA                        | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Gigabyte      | GA-MA770-UD3                | [120e788567](https://linux-hardware.org/?probe=120e788567) | Dec 24, 2020 |
| ASUSTek       | H81M-K                      | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| ASRock        | Z370 Pro4                   | [e6df8b78b5](https://linux-hardware.org/?probe=e6df8b78b5) | Dec 21, 2020 |
| ASUSTek       | M5A78L LE                   | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L LE                   | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| ASRock        | N68-S3 UCC                  | [b75cfae4a3](https://linux-hardware.org/?probe=b75cfae4a3) | Nov 01, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [36db0ea3d4](https://linux-hardware.org/?probe=36db0ea3d4) | Oct 21, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [ff7ecd0641](https://linux-hardware.org/?probe=ff7ecd0641) | Oct 15, 2020 |
| Pegatron      | 2A94h                       | [668c4bbb8b](https://linux-hardware.org/?probe=668c4bbb8b) | Oct 06, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | [b098cfc85e](https://linux-hardware.org/?probe=b098cfc85e) | Sep 30, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | [df11954c4f](https://linux-hardware.org/?probe=df11954c4f) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | [8220732bda](https://linux-hardware.org/?probe=8220732bda) | Sep 28, 2020 |
| ASUSTek       | M5A78L LE                   | [7f4940b41c](https://linux-hardware.org/?probe=7f4940b41c) | Sep 28, 2020 |
| ASRock        | N68-S3 UCC                  | [42ed26b195](https://linux-hardware.org/?probe=42ed26b195) | Sep 19, 2020 |
| ASUSTek       | M4A77                       | [d076f8fe03](https://linux-hardware.org/?probe=d076f8fe03) | Sep 08, 2020 |
| ASRock        | Z87E-ITX                    | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASRock        | N68-S3 UCC                  | [a2d99d11fc](https://linux-hardware.org/?probe=a2d99d11fc) | Aug 30, 2020 |
| ASUSTek       | P8H77-V LE                  | [1c2eaa2346](https://linux-hardware.org/?probe=1c2eaa2346) | Aug 23, 2020 |
| HP            | 2129                        | [d1eda00971](https://linux-hardware.org/?probe=d1eda00971) | Aug 20, 2020 |
| MSI           | Z87-G41 PC Mate             | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| Gigabyte      | G41M-Combo                  | [2f3657530f](https://linux-hardware.org/?probe=2f3657530f) | Jun 29, 2020 |
| ASUSTek       | B85M-E                      | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| ASRock        | H97M Pro4                   | [31f3732dc9](https://linux-hardware.org/?probe=31f3732dc9) | Jun 19, 2020 |
| Gigabyte      | G31MX-S2                    | [7da6752573](https://linux-hardware.org/?probe=7da6752573) | May 31, 2020 |
| Gigabyte      | G31MX-S2                    | [5472c53dca](https://linux-hardware.org/?probe=5472c53dca) | May 31, 2020 |
| ASRock        | H81M-DGS R2.0               | [26a9c7f62c](https://linux-hardware.org/?probe=26a9c7f62c) | May 30, 2020 |
| Gigabyte      | 990FXA-UD3                  | [e3042f4583](https://linux-hardware.org/?probe=e3042f4583) | May 24, 2020 |
| ASUSTek       | P8H77-V LE                  | [e6f20d976d](https://linux-hardware.org/?probe=e6f20d976d) | May 17, 2020 |
| Gigabyte      | 965P-DS3                    | [abfb95a938](https://linux-hardware.org/?probe=abfb95a938) | May 11, 2020 |
| Gigabyte      | 965P-DS3                    | [e59e1593d5](https://linux-hardware.org/?probe=e59e1593d5) | May 11, 2020 |
| MSI           | MS-7360                     | [ab94189bcf](https://linux-hardware.org/?probe=ab94189bcf) | May 07, 2020 |
| MSI           | Z87-G41 PC Mate             | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| HP            | 3031h                       | [b4638888cb](https://linux-hardware.org/?probe=b4638888cb) | Apr 14, 2020 |
| ASUSTek       | M5A78L LE                   | [1562c544a6](https://linux-hardware.org/?probe=1562c544a6) | Apr 14, 2020 |
| ASRock        | H61M-DGS                    | [0a090881ae](https://linux-hardware.org/?probe=0a090881ae) | Apr 12, 2020 |
| ASUSTek       | A8V-MQ                      | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| ASRock        | H61M-VS                     | [799e1670fd](https://linux-hardware.org/?probe=799e1670fd) | Mar 18, 2020 |
| HP            | 212B                        | [6058dd53b1](https://linux-hardware.org/?probe=6058dd53b1) | Mar 16, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [26545c7add](https://linux-hardware.org/?probe=26545c7add) | Feb 24, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [1693523c61](https://linux-hardware.org/?probe=1693523c61) | Feb 21, 2020 |
| Intel         | DH67BL AAG10189-213         | [b0e9895bef](https://linux-hardware.org/?probe=b0e9895bef) | Feb 16, 2020 |
| ASRock        | B150M-HDV                   | [c08c6d0574](https://linux-hardware.org/?probe=c08c6d0574) | Feb 08, 2020 |
| HP            | 18E7                        | [de846e5f4f](https://linux-hardware.org/?probe=de846e5f4f) | Jan 22, 2020 |
| Intel         | DH67BL AAG10189-213         | [9ed2076b0d](https://linux-hardware.org/?probe=9ed2076b0d) | Jan 18, 2020 |
| Intel         | DH67BL AAG10189-213         | [dc121e5512](https://linux-hardware.org/?probe=dc121e5512) | Jan 18, 2020 |
| Acer          | Veriton S680G               | [277889b2ff](https://linux-hardware.org/?probe=277889b2ff) | Jan 15, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [e097415087](https://linux-hardware.org/?probe=e097415087) | Dec 26, 2019 |
| ASRock        | N68-S3 UCC                  | [9cbd6c2e0e](https://linux-hardware.org/?probe=9cbd6c2e0e) | Dec 25, 2019 |
| ASRock        | 990FX Extreme3              | [107280e5a9](https://linux-hardware.org/?probe=107280e5a9) | Dec 23, 2019 |
| ASRock        | 990FX Extreme3              | [66a084d547](https://linux-hardware.org/?probe=66a084d547) | Dec 11, 2019 |
| ASRock        | H97 Killer                  | [8538b88e3d](https://linux-hardware.org/?probe=8538b88e3d) | Nov 27, 2019 |
| ASRock        | 970 Pro3 R2.0               | [73c6829ffb](https://linux-hardware.org/?probe=73c6829ffb) | Nov 27, 2019 |
| HP            | 18EA                        | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| ASRock        | A320M-HDV R3.0              | [d3d79c2a8d](https://linux-hardware.org/?probe=d3d79c2a8d) | Sep 16, 2019 |
| Gigabyte      | A320M-H-CF                  | [a35aea421b](https://linux-hardware.org/?probe=a35aea421b) | Sep 09, 2019 |
| Intel         | DX58SO AAE29331-501         | [349ef8982a](https://linux-hardware.org/?probe=349ef8982a) | Sep 09, 2019 |
| Gigabyte      | A320M-H-CF                  | [59782a89ea](https://linux-hardware.org/?probe=59782a89ea) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF                  | [b4ef0f5499](https://linux-hardware.org/?probe=b4ef0f5499) | Sep 05, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | [be3a07802c](https://linux-hardware.org/?probe=be3a07802c) | Aug 13, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | [9cdd546881](https://linux-hardware.org/?probe=9cdd546881) | Jul 29, 2019 |
| ASRock        | A300M-STX                   | [edf300f175](https://linux-hardware.org/?probe=edf300f175) | Jul 29, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | [aad0551e27](https://linux-hardware.org/?probe=aad0551e27) | Jul 25, 2019 |
| ASUSTek       | E35M1-M                     | [1b78cc518f](https://linux-hardware.org/?probe=1b78cc518f) | Jul 08, 2019 |
| ASUSTek       | E35M1-M                     | [1f5e6b026b](https://linux-hardware.org/?probe=1f5e6b026b) | Jun 23, 2019 |
| ASUSTek       | PRIME A320M-K               | [f8c4365b6c](https://linux-hardware.org/?probe=f8c4365b6c) | Jun 07, 2019 |
| ASUSTek       | PRIME A320M-K               | [3968b06d9c](https://linux-hardware.org/?probe=3968b06d9c) | Jun 07, 2019 |
| HP            | 83ED                        | [532b72754e](https://linux-hardware.org/?probe=532b72754e) | May 06, 2019 |
| Gigabyte      | Z77P-D3                     | [e7259783d1](https://linux-hardware.org/?probe=e7259783d1) | Apr 13, 2019 |
| Pegatron      | 2A99                        | [196712630c](https://linux-hardware.org/?probe=196712630c) | Feb 26, 2019 |
| ASUSTek       | B150M-C                     | [88898f6797](https://linux-hardware.org/?probe=88898f6797) | Feb 10, 2019 |
| ECS           | A770M-A                     | [feacfccf11](https://linux-hardware.org/?probe=feacfccf11) | Feb 05, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | [bf1298d356](https://linux-hardware.org/?probe=bf1298d356) | Jan 29, 2019 |
| ABIT          | IP35-E                      | [87b22d6a66](https://linux-hardware.org/?probe=87b22d6a66) | Jan 26, 2019 |
| Gigabyte      | AX370-Gaming K7             | [bc26ed35a0](https://linux-hardware.org/?probe=bc26ed35a0) | Dec 08, 2018 |
| Unknown       | Grantsdale                  | [65da6a461b](https://linux-hardware.org/?probe=65da6a461b) | Nov 21, 2018 |
| Pegatron      | 2AB6                        | [00a8407210](https://linux-hardware.org/?probe=00a8407210) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 20       | 7.49%   |
| Ubuntu 18.04                 | 14       | 5.24%   |
| Ubuntu 22.04                 | 9        | 3.37%   |
| OpenMandriva 24.12           | 7        | 2.62%   |
| Manjaro                      | 7        | 2.62%   |
| Debian 11                    | 7        | 2.62%   |
| OpenMandriva 4.3             | 6        | 2.25%   |
| Linux Mint 20.3              | 6        | 2.25%   |
| Linux Mint 20.2              | 6        | 2.25%   |
| ArcoLinux Rolling            | 6        | 2.25%   |
| Ubuntu 18.10                 | 5        | 1.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 5        | 1.87%   |
| Debian 12                    | 5        | 1.87%   |
| Zorin 16                     | 4        | 1.5%    |
| Ubuntu 24.10                 | 4        | 1.5%    |
| Ubuntu 24.04                 | 4        | 1.5%    |
| OpenMandriva 5.0             | 4        | 1.5%    |
| OpenMandriva 25.03           | 4        | 1.5%    |
| OpenMandriva 23.08           | 4        | 1.5%    |
| Fedora 38                    | 4        | 1.5%    |
| Debian 10                    | 4        | 1.5%    |
| Ubuntu MATE 22.04            | 3        | 1.12%   |
| Ubuntu 19.10                 | 3        | 1.12%   |
| Pop!_OS 21.10                | 3        | 1.12%   |
| OpenMandriva 6.0             | 3        | 1.12%   |
| OpenMandriva 4.2             | 3        | 1.12%   |
| OpenMandriva 25.90           | 3        | 1.12%   |
| LMDE 6                       | 3        | 1.12%   |
| Fedora 39                    | 3        | 1.12%   |
| Fedora 31                    | 3        | 1.12%   |
| EndeavourOS Rolling          | 3        | 1.12%   |
| Arch Rolling                 | 3        | 1.12%   |
| Ubuntu 21.04                 | 2        | 0.75%   |
| Pop!_OS 20.10                | 2        | 0.75%   |
| openSUSE Leap-15.2           | 2        | 0.75%   |
| OpenMandriva 4.50            | 2        | 0.75%   |
| OpenMandriva 24.07           | 2        | 0.75%   |
| OpenMandriva 23.11           | 2        | 0.75%   |
| OpenMandriva 23.03           | 2        | 0.75%   |
| Linux Mint 22.2              | 2        | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 64       | 25.7%   |
| OpenMandriva  | 39       | 15.66%  |
| Linux Mint    | 26       | 10.44%  |
| Debian        | 17       | 6.83%   |
| Fedora        | 16       | 6.43%   |
| Manjaro       | 12       | 4.82%   |
| Pop!_OS       | 9        | 3.61%   |
| openSUSE      | 8        | 3.21%   |
| Zorin         | 6        | 2.41%   |
| ArcoLinux     | 6        | 2.41%   |
| Ubuntu MATE   | 4        | 1.61%   |
| LMDE          | 4        | 1.61%   |
| Arch          | 4        | 1.61%   |
| Xubuntu       | 3        | 1.2%    |
| Ubuntu Budgie | 3        | 1.2%    |
| Kubuntu       | 3        | 1.2%    |
| KDE neon      | 3        | 1.2%    |
| EndeavourOS   | 3        | 1.2%    |
| Bazzite       | 3        | 1.2%    |
| Nobara        | 2        | 0.8%    |
| Gentoo        | 2        | 0.8%    |
| Ubuntu Unity  | 1        | 0.4%    |
| ROSA          | 1        | 0.4%    |
| Rocky Linux   | 1        | 0.4%    |
| MX            | 1        | 0.4%    |
| Lubuntu       | 1        | 0.4%    |
| LinuxFX       | 1        | 0.4%    |
| Kali          | 1        | 0.4%    |
| Garuda Linux  | 1        | 0.4%    |
| Endless       | 1        | 0.4%    |
| Elementary    | 1        | 0.4%    |
| Dts-distro    | 1        | 0.4%    |
| Clear Linux   | 1        | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 6.14.2-desktop-3omv2590  | 6        | 2.05%   |
| 5.16.7-desktop-1omv4003  | 6        | 2.05%   |
| 6.6.2-desktop-1omv2390   | 5        | 1.71%   |
| 6.4.11-desktop-1omv2390  | 4        | 1.37%   |
| 6.12.1-desktop-1omv2490  | 4        | 1.37%   |
| 5.4.0-58-generic         | 4        | 1.37%   |
| 6.2.9-300.fc38.x86_64    | 3        | 1.02%   |
| 6.13.9-desktop-3omv2590  | 3        | 1.02%   |
| 5.4.0-91-generic         | 3        | 1.02%   |
| 5.3.0-26-generic         | 3        | 1.02%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.02%   |
| 5.0.0-27-generic         | 3        | 1.02%   |
| 6.8.0-51-generic         | 2        | 0.68%   |
| 6.2.6-desktop-1omv2390   | 2        | 0.68%   |
| 6.17.7-ba19.fc43.x86_64  | 2        | 0.68%   |
| 6.12.6-desktop-1omv2490  | 2        | 0.68%   |
| 6.11.0-13-generic        | 2        | 0.68%   |
| 5.8.0-48-generic         | 2        | 0.68%   |
| 5.4.0-48-generic         | 2        | 0.68%   |
| 5.4.0-42-generic         | 2        | 0.68%   |
| 5.4.0-26-generic         | 2        | 0.68%   |
| 5.4.0-100-generic        | 2        | 0.68%   |
| 5.3.0-42-generic         | 2        | 0.68%   |
| 5.3.0-28-generic         | 2        | 0.68%   |
| 5.15.0-52-generic        | 2        | 0.68%   |
| 5.15.0-48-generic        | 2        | 0.68%   |
| 5.15.0-105-generic       | 2        | 0.68%   |
| 5.13.0-40-generic        | 2        | 0.68%   |
| 5.12.4-desktop-1omv4050  | 2        | 0.68%   |
| 5.11.0-41-generic        | 2        | 0.68%   |
| 5.11.0-38-generic        | 2        | 0.68%   |
| 5.11.0-37-generic        | 2        | 0.68%   |
| 5.10.0-13-amd64          | 2        | 0.68%   |
| 4.19.0-14-amd64          | 2        | 0.68%   |
| 4.18.0-10-generic        | 2        | 0.68%   |
| 4.15.0-45-generic        | 2        | 0.68%   |
| 4.15.0-20-generic        | 2        | 0.68%   |
| 6.8.8-1-default          | 1        | 0.34%   |
| 6.8.7-zen1-1-zen         | 1        | 0.34%   |
| 6.8.12-4-pve             | 1        | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 33       | 12%     |
| 5.15.0  | 13       | 4.73%   |
| 5.11.0  | 12       | 4.36%   |
| 5.3.0   | 11       | 4%      |
| 4.15.0  | 10       | 3.64%   |
| 6.8.0   | 8        | 2.91%   |
| 5.10.0  | 8        | 2.91%   |
| 4.18.0  | 8        | 2.91%   |
| 6.14.2  | 6        | 2.18%   |
| 5.16.7  | 6        | 2.18%   |
| 5.13.0  | 6        | 2.18%   |
| 6.6.2   | 5        | 1.82%   |
| 6.11.0  | 5        | 1.82%   |
| 6.1.0   | 5        | 1.82%   |
| 5.8.0   | 5        | 1.82%   |
| 6.4.11  | 4        | 1.45%   |
| 6.14.0  | 4        | 1.45%   |
| 6.12.1  | 4        | 1.45%   |
| 5.0.0   | 4        | 1.45%   |
| 6.5.0   | 3        | 1.09%   |
| 6.2.9   | 3        | 1.09%   |
| 6.17.7  | 3        | 1.09%   |
| 6.13.9  | 3        | 1.09%   |
| 6.12.6  | 3        | 1.09%   |
| 5.12.4  | 3        | 1.09%   |
| 5.10.14 | 3        | 1.09%   |
| 4.19.0  | 3        | 1.09%   |
| 6.5.4   | 2        | 0.73%   |
| 6.2.6   | 2        | 0.73%   |
| 6.17.8  | 2        | 0.73%   |
| 6.11.10 | 2        | 0.73%   |
| 5.3.18  | 2        | 0.73%   |
| 5.19.0  | 2        | 0.73%   |
| 5.16.11 | 2        | 0.73%   |
| 6.8.8   | 1        | 0.36%   |
| 6.8.7   | 1        | 0.36%   |
| 6.8.12  | 1        | 0.36%   |
| 6.8.11  | 1        | 0.36%   |
| 6.8.1   | 1        | 0.36%   |
| 6.7.4   | 1        | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 13.55%  |
| 5.15    | 18       | 6.59%   |
| 5.10    | 15       | 5.49%   |
| 6.14    | 14       | 5.13%   |
| 5.3     | 14       | 5.13%   |
| 6.8     | 13       | 4.76%   |
| 6.12    | 13       | 4.76%   |
| 5.11    | 13       | 4.76%   |
| 6.6     | 10       | 3.66%   |
| 4.15    | 10       | 3.66%   |
| 6.11    | 8        | 2.93%   |
| 5.16    | 8        | 2.93%   |
| 4.18    | 8        | 2.93%   |
| 6.5     | 7        | 2.56%   |
| 6.2     | 7        | 2.56%   |
| 6.1     | 7        | 2.56%   |
| 6.4     | 6        | 2.2%    |
| 6.17    | 6        | 2.2%    |
| 5.13    | 6        | 2.2%    |
| 6.10    | 5        | 1.83%   |
| 5.8     | 5        | 1.83%   |
| 5.19    | 5        | 1.83%   |
| 6.13    | 4        | 1.47%   |
| 5.0     | 4        | 1.47%   |
| 6.7     | 3        | 1.1%    |
| 6.0     | 3        | 1.1%    |
| 5.18    | 3        | 1.1%    |
| 5.12    | 3        | 1.1%    |
| 4.19    | 3        | 1.1%    |
| 6.3     | 2        | 0.73%   |
| 6.16    | 2        | 0.73%   |
| 5.7     | 2        | 0.73%   |
| 5.17    | 2        | 0.73%   |
| 5.14    | 2        | 0.73%   |
| 6.15    | 1        | 0.37%   |
| 5.9     | 1        | 0.37%   |
| 5.6     | 1        | 0.37%   |
| 4.14    | 1        | 0.37%   |
| 4.13    | 1        | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 240      | 99.17%  |
| i686   | 2        | 0.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 82       | 32.54%  |
| KDE5       | 50       | 19.84%  |
| Unknown    | 30       | 11.9%   |
| KDE6       | 24       | 9.52%   |
| X-Cinnamon | 23       | 9.13%   |
| XFCE       | 11       | 4.37%   |
| MATE       | 7        | 2.78%   |
| KDE        | 6        | 2.38%   |
| Cinnamon   | 5        | 1.98%   |
| LXQt       | 3        | 1.19%   |
| Budgie     | 3        | 1.19%   |
| Unity      | 1        | 0.4%    |
| ubuntu     | 1        | 0.4%    |
| Pantheon   | 1        | 0.4%    |
| openbox    | 1        | 0.4%    |
| LXDE       | 1        | 0.4%    |
| i3         | 1        | 0.4%    |
| DWM        | 1        | 0.4%    |
| dk         | 1        | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 177      | 70.52%  |
| Wayland | 54       | 21.51%  |
| Unknown | 12       | 4.78%   |
| Tty     | 8        | 3.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 114      | 45.42%  |
| SDDM    | 63       | 25.1%   |
| LightDM | 29       | 11.55%  |
| GDM3    | 25       | 9.96%   |
| GDM     | 16       | 6.37%   |
| TDM     | 4        | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 146      | 58.63%  |
| hr_HR   | 51       | 20.48%  |
| Unknown | 26       | 10.44%  |
| en_GB   | 18       | 7.23%   |
| C       | 5        | 2.01%   |
| nb_NO   | 1        | 0.4%    |
| it_IT   | 1        | 0.4%    |
| de_DE   | 1        | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 124      | 50.82%  |
| BIOS | 120      | 49.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 168      | 66.93%  |
| Btrfs   | 38       | 15.14%  |
| Overlay | 28       | 11.16%  |
| Tmpfs   | 7        | 2.79%   |
| Zfs     | 4        | 1.59%   |
| Unknown | 4        | 1.59%   |
| Xfs     | 2        | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 114      | 46.34%  |
| GPT     | 109      | 44.31%  |
| MBR     | 23       | 9.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 194      | 77.29%  |
| Yes       | 57       | 22.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 152      | 61.29%  |
| Yes       | 96       | 38.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASRock                               | 56       | 23.14%  |
| ASUSTek Computer                     | 55       | 22.73%  |
| Gigabyte Technology                  | 50       | 20.66%  |
| MSI                                  | 21       | 8.68%   |
| Hewlett-Packard                      | 19       | 7.85%   |
| Intel                                | 6        | 2.48%   |
| Dell                                 | 6        | 2.48%   |
| Pegatron                             | 5        | 2.07%   |
| Lenovo                               | 5        | 2.07%   |
| ECS                                  | 3        | 1.24%   |
| WinFast                              | 1        | 0.41%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.41%   |
| RUNING                               | 1        | 0.41%   |
| MAXSUN                               | 1        | 0.41%   |
| HPE                                  | 1        | 0.41%   |
| GEEKOM                               | 1        | 0.41%   |
| GARAGE                               | 1        | 0.41%   |
| Fujitsu Siemens                      | 1        | 0.41%   |
| Fujitsu                              | 1        | 0.41%   |
| Foxconn                              | 1        | 0.41%   |
| EMC                                  | 1        | 0.41%   |
| eMachines                            | 1        | 0.41%   |
| BESSTAR Tech                         | 1        | 0.41%   |
| Acer                                 | 1        | 0.41%   |
| ABIT                                 | 1        | 0.41%   |
| Unknown                              | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| ASUS All Series                                   | 6        | 2.48%   |
| ASRock B450M-HDV R4.0                             | 5        | 2.07%   |
| Gigabyte B550M DS3H                               | 3        | 1.24%   |
| ASUS PRIME A320M-K                                | 3        | 1.24%   |
| MSI MS-7C02                                       | 2        | 0.83%   |
| MSI MS-7850                                       | 2        | 0.83%   |
| Intel DH61CR AAG14064-204                         | 2        | 0.83%   |
| HP ProDesk 600 G1 SFF                             | 2        | 0.83%   |
| HP Compaq 8200 Elite SFF PC                       | 2        | 0.83%   |
| Gigabyte B450 GAMING X                            | 2        | 0.83%   |
| Gigabyte B450 AORUS ELITE                         | 2        | 0.83%   |
| Gigabyte A320M-S2H                                | 2        | 0.83%   |
| ASUS TUF Gaming X570-PLUS                         | 2        | 0.83%   |
| ASUS ROG STRIX B450-F GAMING                      | 2        | 0.83%   |
| ASUS PRIME B550M-A                                | 2        | 0.83%   |
| ASUS P8H77-V LE                                   | 2        | 0.83%   |
| ASUS M5A78L LE                                    | 2        | 0.83%   |
| ASRock H61M-DGS                                   | 2        | 0.83%   |
| ASRock B560 Steel Legend                          | 2        | 0.83%   |
| ASRock 970 Pro3 R2.0                              | 2        | 0.83%   |
| WinFast N570SM2AA                                 | 1        | 0.41%   |
| Shenzhen Meigao Electronic Equipment Venus series | 1        | 0.41%   |
| RUNING X79 VB1.0                                  | 1        | 0.41%   |
| Pegatron Pro 3010 Small Form Factor PC            | 1        | 0.41%   |
| Pegatron HPE-520ad                                | 1        | 0.41%   |
| Pegatron G5261de                                  | 1        | 0.41%   |
| Pegatron Compaq dx2400 Microtower PC              | 1        | 0.41%   |
| Pegatron 27-1001eu                                | 1        | 0.41%   |
| MSI MS-7E06                                       | 1        | 0.41%   |
| MSI MS-7D77                                       | 1        | 0.41%   |
| MSI MS-7D75                                       | 1        | 0.41%   |
| MSI MS-7D40                                       | 1        | 0.41%   |
| MSI MS-7D25                                       | 1        | 0.41%   |
| MSI MS-7C84                                       | 1        | 0.41%   |
| MSI MS-7B98                                       | 1        | 0.41%   |
| MSI MS-7B86                                       | 1        | 0.41%   |
| MSI MS-7B84                                       | 1        | 0.41%   |
| MSI MS-7B07                                       | 1        | 0.41%   |
| MSI MS-7817                                       | 1        | 0.41%   |
| MSI MS-7788                                       | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 14       | 5.79%   |
| ASUS TUF                                   | 8        | 3.31%   |
| ASUS All                                   | 6        | 2.48%   |
| HP Compaq                                  | 5        | 2.07%   |
| Gigabyte B450                              | 5        | 2.07%   |
| ASUS ROG                                   | 5        | 2.07%   |
| ASRock B450M-HDV                           | 5        | 2.07%   |
| HP ProDesk                                 | 4        | 1.65%   |
| Lenovo ThinkCentre                         | 3        | 1.24%   |
| HP EliteDesk                               | 3        | 1.24%   |
| Gigabyte Z390                              | 3        | 1.24%   |
| Gigabyte B550M                             | 3        | 1.24%   |
| Dell Vostro                                | 3        | 1.24%   |
| ASRock H97                                 | 3        | 1.24%   |
| ASRock A320M-HDV                           | 3        | 1.24%   |
| MSI MS-7C02                                | 2        | 0.83%   |
| MSI MS-7850                                | 2        | 0.83%   |
| Intel DH61CR                               | 2        | 0.83%   |
| Gigabyte Z790                              | 2        | 0.83%   |
| Gigabyte Z370                              | 2        | 0.83%   |
| Gigabyte B650M                             | 2        | 0.83%   |
| Gigabyte A320M-S2H                         | 2        | 0.83%   |
| Dell OptiPlex                              | 2        | 0.83%   |
| ASUS P8H77-V                               | 2        | 0.83%   |
| ASUS M5A78L                                | 2        | 0.83%   |
| ASRock H61M-DGS                            | 2        | 0.83%   |
| ASRock B650M                               | 2        | 0.83%   |
| ASRock B560                                | 2        | 0.83%   |
| ASRock B550M                               | 2        | 0.83%   |
| ASRock 970                                 | 2        | 0.83%   |
| WinFast N570SM2AA                          | 1        | 0.41%   |
| Shenzhen Meigao Electronic Equipment Venus | 1        | 0.41%   |
| RUNING X79                                 | 1        | 0.41%   |
| Pegatron Pro                               | 1        | 0.41%   |
| Pegatron HPE-520ad                         | 1        | 0.41%   |
| Pegatron G5261de                           | 1        | 0.41%   |
| Pegatron Compaq                            | 1        | 0.41%   |
| Pegatron 27-1001eu                         | 1        | 0.41%   |
| MSI MS-7E06                                | 1        | 0.41%   |
| MSI MS-7D77                                | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 25       | 10.33%  |
| 2020 | 23       | 9.5%    |
| 2013 | 21       | 8.68%   |
| 2017 | 20       | 8.26%   |
| 2012 | 19       | 7.85%   |
| 2011 | 16       | 6.61%   |
| 2021 | 14       | 5.79%   |
| 2019 | 13       | 5.37%   |
| 2014 | 12       | 4.96%   |
| 2022 | 11       | 4.55%   |
| 2009 | 11       | 4.55%   |
| 2023 | 10       | 4.13%   |
| 2015 | 8        | 3.31%   |
| 2010 | 8        | 3.31%   |
| 2008 | 8        | 3.31%   |
| 2007 | 7        | 2.89%   |
| 2024 | 5        | 2.07%   |
| 2016 | 5        | 2.07%   |
| 2005 | 3        | 1.24%   |
| 2006 | 2        | 0.83%   |
| 2025 | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 242      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 234      | 96.3%   |
| Enabled  | 9        | 3.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 242      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 60       | 24.29%  |
| 8.01-16.0   | 51       | 20.65%  |
| 32.01-64.0  | 45       | 18.22%  |
| 4.01-8.0    | 32       | 12.96%  |
| 3.01-4.0    | 22       | 8.91%   |
| 64.01-256.0 | 15       | 6.07%   |
| 24.01-32.0  | 12       | 4.86%   |
| 1.01-2.0    | 9        | 3.64%   |
| 2.01-3.0    | 1        | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 85       | 31.72%  |
| 2.01-3.0   | 69       | 25.75%  |
| 4.01-8.0   | 51       | 19.03%  |
| 3.01-4.0   | 30       | 11.19%  |
| 8.01-16.0  | 15       | 5.6%    |
| 0.51-1.0   | 10       | 3.73%   |
| 16.01-24.0 | 5        | 1.87%   |
| 0.01-0.5   | 2        | 0.75%   |
| 24.01-32.0 | 1        | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 85       | 33.6%   |
| 2      | 72       | 28.46%  |
| 3      | 42       | 16.6%   |
| 4      | 26       | 10.28%  |
| 5      | 14       | 5.53%   |
| 6      | 5        | 1.98%   |
| 0      | 3        | 1.19%   |
| 10     | 2        | 0.79%   |
| 8      | 2        | 0.79%   |
| 7      | 2        | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 143      | 58.61%  |
| Yes       | 101      | 41.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 239      | 98.76%  |
| No        | 3        | 1.24%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 64.78%  |
| Yes       | 87       | 35.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 181      | 73.88%  |
| Yes       | 64       | 26.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Croatia | 242      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Zagreb               | 129      | 48.13%  |
| Split                | 18       | 6.72%   |
| Rijeka               | 17       | 6.34%   |
| Osijek               | 11       | 4.1%    |
| Varaždin            | 5        | 1.87%   |
| Velika Gorica        | 4        | 1.49%   |
| Samobor              | 4        | 1.49%   |
| Pula                 | 4        | 1.49%   |
| Zaprešić           | 3        | 1.12%   |
| Virovitica           | 3        | 1.12%   |
| Koprivnica           | 3        | 1.12%   |
| Bjelovar             | 3        | 1.12%   |
| Zadar                | 2        | 0.75%   |
| Vodice               | 2        | 0.75%   |
| Slavonski Brod       | 2        | 0.75%   |
| Slatina              | 2        | 0.75%   |
| Sisak                | 2        | 0.75%   |
| Pitomaca             | 2        | 0.75%   |
| Ivanja Reka          | 2        | 0.75%   |
| GJurgevac            | 2        | 0.75%   |
| Červar-Porat        | 2        | 0.75%   |
| Čakovec             | 2        | 0.75%   |
| Visnjevac            | 1        | 0.37%   |
| Valpovo              | 1        | 0.37%   |
| Sveti Petar Orehovec | 1        | 0.37%   |
| Supetar              | 1        | 0.37%   |
| Stari Perkovci       | 1        | 0.37%   |
| Smrika               | 1        | 0.37%   |
| Skrad                | 1        | 0.37%   |
| Sesvete              | 1        | 0.37%   |
| Rogotin              | 1        | 0.37%   |
| Raslina              | 1        | 0.37%   |
| Rab                  | 1        | 0.37%   |
| Prelog               | 1        | 0.37%   |
| Postira              | 1        | 0.37%   |
| Novi Marof           | 1        | 0.37%   |
| Nerezine             | 1        | 0.37%   |
| Matulji              | 1        | 0.37%   |
| Malinska             | 1        | 0.37%   |
| Mali Lošinj         | 1        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 99       | 164    | 20.37%  |
| Samsung Electronics         | 62       | 100    | 12.76%  |
| Seagate                     | 48       | 78     | 9.88%   |
| Kingston                    | 48       | 77     | 9.88%   |
| Toshiba                     | 43       | 67     | 8.85%   |
| Crucial                     | 36       | 52     | 7.41%   |
| SanDisk                     | 15       | 19     | 3.09%   |
| A-DATA Technology           | 15       | 19     | 3.09%   |
| Kingston Technology Company | 13       | 17     | 2.67%   |
| Intel                       | 12       | 14     | 2.47%   |
| Patriot                     | 9        | 12     | 1.85%   |
| Hitachi                     | 7        | 10     | 1.44%   |
| Micron Technology           | 6        | 6      | 1.23%   |
| Transcend                   | 5        | 9      | 1.03%   |
| Micron/Crucial Technology   | 5        | 5      | 1.03%   |
| Unknown                     | 4        | 10     | 0.82%   |
| SPCC                        | 4        | 4      | 0.82%   |
| Silicon Motion              | 4        | 5      | 0.82%   |
| Phison                      | 3        | 3      | 0.62%   |
| China                       | 3        | 4      | 0.62%   |
| ADATA Technology            | 3        | 3      | 0.62%   |
| Phison Electronics          | 2        | 3      | 0.41%   |
| OCZ                         | 2        | 3      | 0.41%   |
| Mushkin                     | 2        | 3      | 0.41%   |
| Maxtor                      | 2        | 2      | 0.41%   |
| KingSpec                    | 2        | 2      | 0.41%   |
| HPE                         | 2        | 4      | 0.41%   |
| Gigabyte Technology         | 2        | 2      | 0.41%   |
| External                    | 2        | 2      | 0.41%   |
| Corsair                     | 2        | 2      | 0.41%   |
| XPG                         | 1        | 3      | 0.21%   |
| Viper                       | 1        | 1      | 0.21%   |
| Vi550                       | 1        | 1      | 0.21%   |
| Verbatim                    | 1        | 1      | 0.21%   |
| TO Exter                    | 1        | 1      | 0.21%   |
| Seagate Technology          | 1        | 1      | 0.21%   |
| Realtek Semiconductor       | 1        | 1      | 0.21%   |
| Ramaxel Technology          | 1        | 1      | 0.21%   |
| PNY                         | 1        | 1      | 0.21%   |
| Netac                       | 1        | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Toshiba HDWD130 3TB                               | 7        | 1.24%   |
| Toshiba HDWD110 1TB                               | 7        | 1.24%   |
| Toshiba DT01ACA100 1TB                            | 7        | 1.24%   |
| Kingston SA400S37480G 480GB SSD                   | 7        | 1.24%   |
| Kingston SA400S37240G 240GB SSD                   | 7        | 1.24%   |
| Kingston SA400S37120G 120GB SSD                   | 7        | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB                    | 6        | 1.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 6        | 1.07%   |
| Kingston SV300S37A120G 120GB SSD                  | 5        | 0.89%   |
| Crucial CT1000BX500SSD1 1TB                       | 5        | 0.89%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 4        | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 4        | 0.71%   |
| Toshiba MQ01ABD100 1TB                            | 4        | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB                    | 4        | 0.71%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB             | 4        | 0.71%   |
| Samsung SSD 850 EVO 250GB                         | 4        | 0.71%   |
| Patriot Burst 240GB SSD                           | 4        | 0.71%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB               | 4        | 0.71%   |
| Kingston Company SNV2S1000G 1TB                   | 4        | 0.71%   |
| Intel SSDSC2BW120A4 120GB                         | 4        | 0.71%   |
| Crucial CT2000P3PSSD8 2TB                         | 4        | 0.71%   |
| Crucial CT120BX500SSD1 120GB                      | 4        | 0.71%   |
| WDC WD5000AAKX-001CA0 500GB                       | 3        | 0.53%   |
| WDC WD30EZRX-00AZ6B0 3TB                          | 3        | 0.53%   |
| WDC WD30EFRX-68EUZN0 3TB                          | 3        | 0.53%   |
| WDC WD10EZEX-08M2NA0 1TB                          | 3        | 0.53%   |
| Toshiba MG08ACA16TE 16TB                          | 3        | 0.53%   |
| Toshiba HDWD240 4TB                               | 3        | 0.53%   |
| Toshiba HDWD120 2TB                               | 3        | 0.53%   |
| Toshiba DT01ACA300 3TB                            | 3        | 0.53%   |
| Seagate ST3250410AS 250GB                         | 3        | 0.53%   |
| Seagate ST31500341AS 1TB                          | 3        | 0.53%   |
| Seagate ST31000528AS 1TB                          | 3        | 0.53%   |
| SanDisk SDSSDA240G 240GB                          | 3        | 0.53%   |
| Samsung SSD 990 PRO 2TB                           | 3        | 0.53%   |
| Samsung SSD 980 500GB                             | 3        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB                      | 3        | 0.53%   |
| Samsung SSD 860 EVO 500GB                         | 3        | 0.53%   |
| Samsung SSD 860 EVO 250GB                         | 3        | 0.53%   |
| Samsung HD103SI 1TB                               | 3        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 93       | 150    | 44.93%  |
| Seagate             | 45       | 74     | 21.74%  |
| Toshiba             | 42       | 66     | 20.29%  |
| Samsung Electronics | 8        | 10     | 3.86%   |
| Hitachi             | 7        | 10     | 3.38%   |
| Unknown             | 2        | 2      | 0.97%   |
| Maxtor              | 2        | 2      | 0.97%   |
| External            | 2        | 2      | 0.97%   |
| TO Exter            | 1        | 1      | 0.48%   |
| Min Yi U            | 1        | 1      | 0.48%   |
| HPE                 | 1        | 2      | 0.48%   |
| HGST HTS            | 1        | 1      | 0.48%   |
| HGST                | 1        | 1      | 0.48%   |
| ASMedia             | 1        | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 39       | 55     | 22.94%  |
| Samsung Electronics | 27       | 41     | 15.88%  |
| Crucial             | 27       | 37     | 15.88%  |
| A-DATA Technology   | 13       | 16     | 7.65%   |
| Intel               | 10       | 12     | 5.88%   |
| Patriot             | 8        | 11     | 4.71%   |
| WDC                 | 7        | 7      | 4.12%   |
| SanDisk             | 5        | 8      | 2.94%   |
| SPCC                | 4        | 4      | 2.35%   |
| Transcend           | 3        | 3      | 1.76%   |
| China               | 3        | 4      | 1.76%   |
| Seagate             | 2        | 3      | 1.18%   |
| OCZ                 | 2        | 3      | 1.18%   |
| Mushkin             | 2        | 3      | 1.18%   |
| Micron Technology   | 2        | 2      | 1.18%   |
| KingSpec            | 2        | 2      | 1.18%   |
| Gigabyte Technology | 2        | 2      | 1.18%   |
| Vi550               | 1        | 1      | 0.59%   |
| Verbatim            | 1        | 1      | 0.59%   |
| Ramaxel Technology  | 1        | 1      | 0.59%   |
| PNY                 | 1        | 1      | 0.59%   |
| Netac               | 1        | 1      | 0.59%   |
| Kingmax             | 1        | 1      | 0.59%   |
| KingDian            | 1        | 1      | 0.59%   |
| Intenso             | 1        | 1      | 0.59%   |
| INNOVATION IT       | 1        | 1      | 0.59%   |
| GOODRAM             | 1        | 1      | 0.59%   |
| Corsair             | 1        | 1      | 0.59%   |
| AMD                 | 1        | 2      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 158      | 323    | 40.31%  |
| SSD     | 136      | 226    | 34.69%  |
| NVMe    | 95       | 169    | 24.23%  |
| Unknown | 3        | 10     | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 208      | 537    | 65.82%  |
| NVMe | 95       | 169    | 30.06%  |
| SAS  | 13       | 22     | 4.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 152      | 282    | 48.1%   |
| 0.51-1.0   | 84       | 135    | 26.58%  |
| 1.01-2.0   | 35       | 56     | 11.08%  |
| 2.01-3.0   | 19       | 36     | 6.01%   |
| 3.01-4.0   | 18       | 27     | 5.7%    |
| 10.01-20.0 | 5        | 9      | 1.58%   |
| 4.01-10.0  | 3        | 4      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 50       | 19.08%  |
| 1001-2000      | 43       | 16.41%  |
| 251-500        | 42       | 16.03%  |
| 501-1000       | 36       | 13.74%  |
| More than 3000 | 35       | 13.36%  |
| 1-20           | 19       | 7.25%   |
| 2001-3000      | 12       | 4.58%   |
| Unknown        | 12       | 4.58%   |
| 51-100         | 11       | 4.2%    |
| 21-50          | 2        | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 96       | 35.56%  |
| 21-50          | 33       | 12.22%  |
| 251-500        | 26       | 9.63%   |
| 501-1000       | 25       | 9.26%   |
| 1001-2000      | 21       | 7.78%   |
| 101-250        | 19       | 7.04%   |
| 51-100         | 14       | 5.19%   |
| More than 3000 | 13       | 4.81%   |
| Unknown        | 12       | 4.44%   |
| 2001-3000      | 10       | 3.7%    |
| 0              | 1        | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                    | Desktops | Drives | Percent |
|----------------------------------------------------------|----------|--------|---------|
| Seagate ST31500341AS 1TB                                 | 2        | 3      | 5.13%   |
| Crucial CT120BX500SSD1 120GB                             | 2        | 4      | 5.13%   |
| WDC WD6400AAKS-07A7B0 640GB                              | 1        | 1      | 2.56%   |
| WDC WD5003ABYX-88 LEN 500GB                              | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-221CA1 500GB                              | 1        | 1      | 2.56%   |
| WDC WD5000AAKS-00UU3A0 500GB                             | 1        | 1      | 2.56%   |
| WDC WD3200BEKT-08PVMT1 320GB                             | 1        | 1      | 2.56%   |
| WDC WD3200AAKS-00L9A0 320GB                              | 1        | 1      | 2.56%   |
| WDC WD2500AAKX-75U6AA0 250GB                             | 1        | 1      | 2.56%   |
| WDC WD20PURX-64P6ZY0 2TB                                 | 1        | 1      | 2.56%   |
| WDC WD2003FYYS-05T9B0 2TB                                | 1        | 1      | 2.56%   |
| WDC WD15EARS-00S8B1 1TB                                  | 1        | 1      | 2.56%   |
| WDC WD10EZRZ-00HTKB0 1TB                                 | 1        | 1      | 2.56%   |
| WDC WD10EZEX-00MFCA0 1TB                                 | 1        | 1      | 2.56%   |
| WDC WD1001FALS-00J7B0 1TB                                | 1        | 1      | 2.56%   |
| WDC WD Green 2.5 240GB                                   | 1        | 1      | 2.56%   |
| Transcend TS480GSSD220S 480GB                            | 1        | 1      | 2.56%   |
| Toshiba DT01ACA100 1TB                                   | 1        | 1      | 2.56%   |
| SPCC Solid State Disk 128GB                              | 1        | 1      | 2.56%   |
| Seagate ST9500420AS 500GB                                | 1        | 1      | 2.56%   |
| Seagate ST3250410AS 250GB                                | 1        | 2      | 2.56%   |
| Seagate ST31000528AS 1TB                                 | 1        | 1      | 2.56%   |
| Seagate ST2000DM008-2FR102 2TB                           | 1        | 1      | 2.56%   |
| Seagate ST2000DM001-1ER164 2TB                           | 1        | 1      | 2.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                       | 1        | 3      | 2.56%   |
| Seagate ST1000DX002-2DV162 1TB                           | 1        | 1      | 2.56%   |
| SanDisk SDSSDA240G 240GB                                 | 1        | 1      | 2.56%   |
| Samsung Electronics SSD 970 EVO Plus 1TB S6P7NG3R755349M | 1        | 1      | 2.56%   |
| Samsung Electronics SSD 850 PRO 256GB                    | 1        | 1      | 2.56%   |
| Kingston SKC2500M8500G 500GB                             | 1        | 1      | 2.56%   |
| Kingston SHFS37A120G 120GB SSD                           | 1        | 1      | 2.56%   |
| Intel SSDSC2BW180A4 180GB                                | 1        | 1      | 2.56%   |
| Intel SSDSC2BW120A4 120GB                                | 1        | 1      | 2.56%   |
| Hitachi HDS723020BLA642 2TB                              | 1        | 1      | 2.56%   |
| Crucial CT525MX300SSD1 528GB                             | 1        | 1      | 2.56%   |
| China SSD 500GB                                          | 1        | 1      | 2.56%   |
| A-DATA Technology SP900 64GB SSD                         | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 14     | 36.84%  |
| Seagate             | 8        | 13     | 21.05%  |
| Crucial             | 3        | 5      | 7.89%   |
| Samsung Electronics | 2        | 2      | 5.26%   |
| Kingston            | 2        | 2      | 5.26%   |
| Intel               | 2        | 2      | 5.26%   |
| Transcend           | 1        | 1      | 2.63%   |
| Toshiba             | 1        | 1      | 2.63%   |
| SPCC                | 1        | 1      | 2.63%   |
| SanDisk             | 1        | 1      | 2.63%   |
| Hitachi             | 1        | 1      | 2.63%   |
| China               | 1        | 1      | 2.63%   |
| A-DATA Technology   | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 13       | 13     | 56.52%  |
| Seagate | 8        | 13     | 34.78%  |
| Toshiba | 1        | 1      | 4.35%   |
| Hitachi | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 28     | 58.33%  |
| SSD  | 13       | 15     | 36.11%  |
| NVMe | 2        | 2      | 5.56%   |

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
| Detected | 130      | 377    | 47.62%  |
| Works    | 111      | 306    | 40.66%  |
| Malfunc  | 32       | 45     | 11.72%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 140      | 36.94%  |
| AMD                          | 94       | 24.8%   |
| Samsung Electronics          | 34       | 8.97%   |
| Kingston Technology Company  | 27       | 7.12%   |
| Micron/Crucial Technology    | 14       | 3.69%   |
| Sandisk                      | 11       | 2.9%    |
| Phison Electronics           | 8        | 2.11%   |
| ASMedia Technology           | 8        | 2.11%   |
| JMicron Technology           | 6        | 1.58%   |
| ADATA Technology             | 6        | 1.58%   |
| Marvell Technology Group     | 5        | 1.32%   |
| Silicon Motion               | 4        | 1.06%   |
| Nvidia                       | 4        | 1.06%   |
| Micron Technology            | 4        | 1.06%   |
| Transcend                    | 2        | 0.53%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.53%   |
| Adaptec                      | 2        | 0.53%   |
| VIA Technologies             | 1        | 0.26%   |
| Toshiba America Info Systems | 1        | 0.26%   |
| Silicon Image                | 1        | 0.26%   |
| Seagate Technology           | 1        | 0.26%   |
| Realtek Semiconductor        | 1        | 0.26%   |
| KIOXIA                       | 1        | 0.26%   |
| Broadcom / LSI               | 1        | 0.26%   |
| Biwin Storage Technology     | 1        | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 37       | 7.84%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 4.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 3.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 15       | 3.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 2.75%   |
| AMD 600 Series Chipset SATA Controller                                                  | 13       | 2.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 2.33%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 11       | 2.33%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 10       | 2.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 2.12%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9        | 1.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 1.69%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 7        | 1.48%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.48%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 1.48%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 1.48%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 6        | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 6        | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 1.27%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 5        | 1.06%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 5        | 1.06%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 5        | 1.06%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.06%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 5        | 1.06%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.06%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 4        | 0.85%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.85%   |
| AMD FCH IDE Controller                                                                  | 4        | 0.85%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 0.64%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 3        | 0.64%   |
| Kingston Company KC2000/KC2500 NVMe SSD [SM2262EN]                                      | 3        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 197      | 53.68%  |
| NVMe | 96       | 26.16%  |
| IDE  | 57       | 15.53%  |
| RAID | 16       | 4.36%   |
| SAS  | 1        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 141      | 58.26%  |
| AMD    | 101      | 41.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 2.45%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 6        | 2.45%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.63%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.63%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 1.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 1.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 1.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.22%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 1.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.22%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 1.22%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.22%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 1.22%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.22%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 3        | 1.22%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.22%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.22%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 1.22%   |
| AMD Ryzen 7 7700 8-Core Processor           | 3        | 1.22%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 1.22%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.82%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 0.82%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 0.82%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.82%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 2        | 0.82%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.82%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 0.82%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 2        | 0.82%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 0.82%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 0.82%   |
| Intel Core 2 CPU 6320 @ 1.86GHz             | 2        | 0.82%   |
| Intel 13th Gen Core i5-13600K               | 2        | 0.82%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2        | 0.82%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 0.82%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 2        | 0.82%   |
| AMD Ryzen 7 9800X3D 8-Core Processor        | 2        | 0.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 0.82%   |
| AMD Ryzen 5 7600X 6-Core Processor          | 2        | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 44       | 17.96%  |
| AMD Ryzen 5             | 27       | 11.02%  |
| Intel Core i7           | 23       | 9.39%   |
| AMD Ryzen 7             | 21       | 8.57%   |
| Intel Core i3           | 19       | 7.76%   |
| Other                   | 16       | 6.53%   |
| AMD Ryzen 9             | 13       | 5.31%   |
| Intel Xeon              | 9        | 3.67%   |
| Intel Core 2 Duo        | 9        | 3.67%   |
| AMD FX                  | 8        | 3.27%   |
| AMD Ryzen 3             | 6        | 2.45%   |
| Intel Pentium           | 5        | 2.04%   |
| AMD Phenom II X4        | 4        | 1.63%   |
| AMD Athlon II X4        | 4        | 1.63%   |
| Intel Pentium Dual-Core | 3        | 1.22%   |
| Intel Pentium 4         | 3        | 1.22%   |
| Intel Core 2 Quad       | 3        | 1.22%   |
| Intel Core 2            | 3        | 1.22%   |
| AMD Athlon X4           | 3        | 1.22%   |
| AMD Athlon 64 X2        | 3        | 1.22%   |
| Intel Pentium Dual      | 2        | 0.82%   |
| Intel Core i9           | 2        | 0.82%   |
| AMD A8                  | 2        | 0.82%   |
| Intel Core              | 1        | 0.41%   |
| Intel Celeron           | 1        | 0.41%   |
| AMD Ryzen Threadripper  | 1        | 0.41%   |
| AMD Ryzen 7 PRO         | 1        | 0.41%   |
| AMD Ryzen 5 PRO         | 1        | 0.41%   |
| AMD Ryzen 3 PRO         | 1        | 0.41%   |
| AMD Phenom II X6        | 1        | 0.41%   |
| AMD Phenom II X2        | 1        | 0.41%   |
| AMD Phenom              | 1        | 0.41%   |
| AMD E                   | 1        | 0.41%   |
| AMD Athlon 64           | 1        | 0.41%   |
| AMD Athlon              | 1        | 0.41%   |
| AMD A6                  | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 89       | 36.33%  |
| 2      | 46       | 18.78%  |
| 6      | 43       | 17.55%  |
| 8      | 33       | 13.47%  |
| 12     | 9        | 3.67%   |
| 1      | 6        | 2.45%   |
| 16     | 5        | 2.04%   |
| 24     | 3        | 1.22%   |
| 14     | 3        | 1.22%   |
| 3      | 3        | 1.22%   |
| 20     | 2        | 0.82%   |
| 10     | 2        | 0.82%   |
| 18     | 1        | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 241      | 99.59%  |
| 2      | 1        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 143      | 58.85%  |
| 1      | 100      | 41.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 240      | 99.17%  |
| Unknown        | 2        | 0.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 111      | 44.4%   |
| 0x306c3    | 21       | 8.4%    |
| 0x206a7    | 12       | 4.8%    |
| 0x1067a    | 7        | 2.8%    |
| 0x0800820d | 7        | 2.8%    |
| 0xa0653    | 5        | 2%      |
| 0x906ea    | 5        | 2%      |
| 0x906e9    | 5        | 2%      |
| 0x506e3    | 4        | 1.6%    |
| 0x010000db | 4        | 1.6%    |
| 0x010000c8 | 4        | 1.6%    |
| 0xa0671    | 3        | 1.2%    |
| 0x6fd      | 3        | 1.2%    |
| 0x306a9    | 3        | 1.2%    |
| 0x0a601203 | 3        | 1.2%    |
| 0x08701021 | 3        | 1.2%    |
| 0x06001119 | 3        | 1.2%    |
| 0xf43      | 2        | 0.8%    |
| 0xb0671    | 2        | 0.8%    |
| 0xa0655    | 2        | 0.8%    |
| 0x906ed    | 2        | 0.8%    |
| 0x906eb    | 2        | 0.8%    |
| 0x6fb      | 2        | 0.8%    |
| 0x306f2    | 2        | 0.8%    |
| 0x0a601206 | 2        | 0.8%    |
| 0x08701013 | 2        | 0.8%    |
| 0x08600106 | 2        | 0.8%    |
| 0x0810100b | 2        | 0.8%    |
| 0x08001137 | 2        | 0.8%    |
| 0x06000852 | 2        | 0.8%    |
| 0x0600063e | 2        | 0.8%    |
| 0x90672    | 1        | 0.4%    |
| 0x6f6      | 1        | 0.4%    |
| 0x20655    | 1        | 0.4%    |
| 0x106a4    | 1        | 0.4%    |
| 0x0a50000d | 1        | 0.4%    |
| 0x0a50000c | 1        | 0.4%    |
| 0x0a20120e | 1        | 0.4%    |
| 0x0a201009 | 1        | 0.4%    |
| 0x0a201005 | 1        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 32       | 13.11%  |
| Unknown          | 22       | 9.02%   |
| KabyLake         | 20       | 8.2%    |
| Zen 3            | 17       | 6.97%   |
| SandyBridge      | 17       | 6.97%   |
| Zen 2            | 15       | 6.15%   |
| Zen+             | 13       | 5.33%   |
| Zen              | 12       | 4.92%   |
| Skylake          | 11       | 4.51%   |
| Piledriver       | 11       | 4.51%   |
| Penryn           | 11       | 4.51%   |
| K10              | 10       | 4.1%    |
| Core             | 9        | 3.69%   |
| IvyBridge        | 8        | 3.28%   |
| CometLake        | 8        | 3.28%   |
| Alderlake Hybrid | 7        | 2.87%   |
| Icelake          | 6        | 2.46%   |
| K8 Hammer        | 4        | 1.64%   |
| NetBurst         | 3        | 1.23%   |
| Westmere         | 2        | 0.82%   |
| Bulldozer        | 2        | 0.82%   |
| Nehalem          | 1        | 0.41%   |
| Lunarlake Hybrid | 1        | 0.41%   |
| Excavator        | 1        | 0.41%   |
| Bobcat           | 1        | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 107      | 39.48%  |
| Nvidia                     | 97       | 35.79%  |
| Intel                      | 64       | 23.62%  |
| Matrox Electronics Systems | 2        | 0.74%   |
| ATI Technologies           | 1        | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 5.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 5.04%   |
| AMD Raphael                                                                 | 10       | 3.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 3.24%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 6        | 2.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.16%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 6        | 2.16%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 2.16%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.8%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 1.44%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 1.44%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.44%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 1.44%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.44%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 4        | 1.44%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 4        | 1.44%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 4        | 1.44%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.08%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 3        | 1.08%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.08%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.08%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 3        | 1.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.08%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.08%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 1.08%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 1.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.08%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 2        | 0.72%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.72%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                         | 2        | 0.72%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 0.72%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 91       | 36.4%   |
| 1 x Nvidia     | 85       | 34%     |
| 1 x Intel      | 50       | 20%     |
| Intel + Nvidia | 6        | 2.4%    |
| AMD + Nvidia   | 6        | 2.4%    |
| 2 x AMD        | 5        | 2%      |
| Intel + AMD    | 5        | 2%      |
| 1 x Matrox     | 2        | 0.8%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 177      | 70.52%  |
| Proprietary | 65       | 25.9%   |
| Unknown     | 9        | 3.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 102      | 40.64%  |
| 1.01-2.0   | 33       | 13.15%  |
| 0.51-1.0   | 32       | 12.75%  |
| 7.01-8.0   | 30       | 11.95%  |
| 0.01-0.5   | 16       | 6.37%   |
| 3.01-4.0   | 14       | 5.58%   |
| 8.01-16.0  | 13       | 5.18%   |
| 5.01-6.0   | 7        | 2.79%   |
| 2.01-3.0   | 4        | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 52       | 18.84%  |
| Dell                 | 41       | 14.86%  |
| AOC                  | 35       | 12.68%  |
| Acer                 | 26       | 9.42%   |
| Goldstar             | 25       | 9.06%   |
| Philips              | 22       | 7.97%   |
| Ancor Communications | 12       | 4.35%   |
| ASUSTek Computer     | 8        | 2.9%    |
| Hewlett-Packard      | 7        | 2.54%   |
| BenQ                 | 5        | 1.81%   |
| Unknown              | 3        | 1.09%   |
| Sony                 | 3        | 1.09%   |
| LG Electronics       | 3        | 1.09%   |
| Denver               | 3        | 1.09%   |
| Unknown (XXX)        | 2        | 0.72%   |
| Huion                | 2        | 0.72%   |
| Hitachi              | 2        | 0.72%   |
| Grundig              | 2        | 0.72%   |
| Gigabyte Technology  | 2        | 0.72%   |
| Fujitsu Siemens      | 2        | 0.72%   |
| ViewSonic            | 1        | 0.36%   |
| Vestel Elektronik    | 1        | 0.36%   |
| RTK                  | 1        | 0.36%   |
| Panasonic            | 1        | 0.36%   |
| NOA VISION           | 1        | 0.36%   |
| NEC Computers        | 1        | 0.36%   |
| Mi                   | 1        | 0.36%   |
| LG Display           | 1        | 0.36%   |
| Lenovo               | 1        | 0.36%   |
| KTC                  | 1        | 0.36%   |
| Jean                 | 1        | 0.36%   |
| InnoLux Display      | 1        | 0.36%   |
| Iiyama               | 1        | 0.36%   |
| HKC                  | 1        | 0.36%   |
| FME                  | 1        | 0.36%   |
| CHO                  | 1        | 0.36%   |
| Beko                 | 1        | 0.36%   |
| AU Optronics         | 1        | 0.36%   |
| Arnos Instruments    | 1        | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5        | 1.69%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 4        | 1.35%   |
| Denver PGM340 LHC3400 3440x1440 790x330mm 33.7-inch                   | 3        | 1.01%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                    | 3        | 1.01%   |
| Unknown (XXX) Beyo TV XXX9615 3840x2160 1210x680mm 54.6-inch          | 2        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                     | 2        | 0.68%   |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                    | 2        | 0.68%   |
| Huion Kamvas 22plus HAT2150 1920x1080 476x267mm 21.5-inch             | 2        | 0.68%   |
| Grundig WUXGA GRU4448 1360x768                                        | 2        | 0.68%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2        | 0.68%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 2        | 0.68%   |
| Goldstar HDR 4K GSM7780 3840x2160 697x392mm 31.5-inch                 | 2        | 0.68%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 2        | 0.68%   |
| Dell U2212HM DELD047 1920x1080 475x267mm 21.5-inch                    | 2        | 0.68%   |
| Dell S2721DGF DEL41DB 2560x1440 597x336mm 27.0-inch                   | 2        | 0.68%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 2        | 0.68%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                     | 2        | 0.68%   |
| Dell LCD Monitor SE2416H 5760x1080                                    | 2        | 0.68%   |
| Dell LCD Monitor SE2416H                                              | 2        | 0.68%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                     | 2        | 0.68%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 2        | 0.68%   |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                     | 2        | 0.68%   |
| AOC AG352UCG AOC3525 3440x1440 819x346mm 35.0-inch                    | 2        | 0.68%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                       | 2        | 0.68%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2        | 0.68%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                        | 2        | 0.68%   |
| AOC 22B15HN AOC2201 1920x1080 478x260mm 21.4-inch                     | 2        | 0.68%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 2        | 0.68%   |
| Acer VG270 ACR0694 1920x1080 600x340mm 27.2-inch                      | 2        | 0.68%   |
| Acer V223HQ ACR0070 1920x1080 477x268mm 21.5-inch                     | 2        | 0.68%   |
| Acer K272HL ACR03DC 1920x1080 598x336mm 27.0-inch                     | 2        | 0.68%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 1        | 0.34%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch  | 1        | 0.34%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.34%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.34%   |
| Unknown LCD Monitor CVT STD LCDTV 3840x1080                           | 1        | 0.34%   |
| Sony TV SNY1A02 1920x1080                                             | 1        | 0.34%   |
| Sony TV *00 SNYA003 1920x1080 1218x685mm 55.0-inch                    | 1        | 0.34%   |
| Sony TV *00 SNY2B05 3840x2160                                         | 1        | 0.34%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 118      | 43.87%  |
| 3840x2160 (4K)     | 30       | 11.15%  |
| 2560x1440 (QHD)    | 30       | 11.15%  |
| 1280x1024 (SXGA)   | 15       | 5.58%   |
| 1680x1050 (WSXGA+) | 13       | 4.83%   |
| 1920x1200 (WUXGA)  | 11       | 4.09%   |
| 3440x1440          | 10       | 3.72%   |
| Unknown            | 8        | 2.97%   |
| 1440x900 (WXGA+)   | 6        | 2.23%   |
| 3840x1080          | 5        | 1.86%   |
| 2560x1080          | 5        | 1.86%   |
| 1600x900 (HD+)     | 5        | 1.86%   |
| 1360x768           | 4        | 1.49%   |
| 1366x768 (WXGA)    | 3        | 1.12%   |
| 5760x1080          | 2        | 0.74%   |
| 2048x1152          | 2        | 0.74%   |
| 4480x1440          | 1        | 0.37%   |
| 2560x1600          | 1        | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 46       | 16.67%  |
| 24      | 38       | 13.77%  |
| 23      | 38       | 13.77%  |
| 21      | 33       | 11.96%  |
| Unknown | 21       | 7.61%   |
| 31      | 12       | 4.35%   |
| 34      | 11       | 3.99%   |
| 19      | 11       | 3.99%   |
| 22      | 10       | 3.62%   |
| 17      | 10       | 3.62%   |
| 20      | 7        | 2.54%   |
| 54      | 5        | 1.81%   |
| 84      | 4        | 1.45%   |
| 33      | 4        | 1.45%   |
| 18      | 4        | 1.45%   |
| 72      | 2        | 0.72%   |
| 65      | 2        | 0.72%   |
| 35      | 2        | 0.72%   |
| 25      | 2        | 0.72%   |
| 15      | 2        | 0.72%   |
| 64      | 1        | 0.36%   |
| 63      | 1        | 0.36%   |
| 60      | 1        | 0.36%   |
| 58      | 1        | 0.36%   |
| 55      | 1        | 0.36%   |
| 49      | 1        | 0.36%   |
| 46      | 1        | 0.36%   |
| 43      | 1        | 0.36%   |
| 39      | 1        | 0.36%   |
| 32      | 1        | 0.36%   |
| 26      | 1        | 0.36%   |
| 14      | 1        | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 110      | 41.51%  |
| 401-500     | 57       | 21.51%  |
| Unknown     | 21       | 7.92%   |
| 601-700     | 18       | 6.79%   |
| 701-800     | 16       | 6.04%   |
| 1001-1500   | 14       | 5.28%   |
| 301-350     | 10       | 3.77%   |
| 351-400     | 8        | 3.02%   |
| 1501-2000   | 6        | 2.26%   |
| 801-900     | 2        | 0.75%   |
| 901-1000    | 2        | 0.75%   |
| 201-300     | 1        | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 169      | 67.33%  |
| 16/10   | 33       | 13.15%  |
| Unknown | 18       | 7.17%   |
| 5/4     | 14       | 5.58%   |
| 21/9    | 14       | 5.58%   |
| 4/3     | 1        | 0.4%    |
| 32/9    | 1        | 0.4%    |
| 3/2     | 1        | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 84       | 31.11%  |
| 301-350        | 47       | 17.41%  |
| 351-500        | 30       | 11.11%  |
| 151-200        | 27       | 10%     |
| 251-300        | 23       | 8.52%   |
| Unknown        | 21       | 7.78%   |
| More than 1000 | 18       | 6.67%   |
| 141-150        | 11       | 4.07%   |
| 501-1000       | 4        | 1.48%   |
| 101-110        | 3        | 1.11%   |
| 121-130        | 2        | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 143      | 56.08%  |
| 101-120 | 64       | 25.1%   |
| Unknown | 21       | 8.24%   |
| 121-160 | 14       | 5.49%   |
| 1-50    | 11       | 4.31%   |
| 161-240 | 2        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 177      | 71.08%  |
| 2     | 54       | 21.69%  |
| 0     | 11       | 4.42%   |
| 3     | 6        | 2.41%   |
| 4     | 1        | 0.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 159      | 45.82%  |
| Intel                             | 83       | 23.92%  |
| Qualcomm Atheros                  | 14       | 4.03%   |
| TP-Link                           | 13       | 3.75%   |
| MediaTek                          | 12       | 3.46%   |
| Broadcom                          | 10       | 2.88%   |
| Ralink Technology                 | 6        | 1.73%   |
| Ralink                            | 5        | 1.44%   |
| Qualcomm Atheros Communications   | 5        | 1.44%   |
| D-Link                            | 5        | 1.44%   |
| Nvidia                            | 4        | 1.15%   |
| ASIX Electronics                  | 4        | 1.15%   |
| Samsung Electronics               | 3        | 0.86%   |
| Marvell Technology Group          | 3        | 0.86%   |
| Xiaomi                            | 2        | 0.58%   |
| Sundance Technology Inc / IC Plus | 2        | 0.58%   |
| NetGear                           | 2        | 0.58%   |
| Microsoft                         | 2        | 0.58%   |
| Linksys                           | 2        | 0.58%   |
| VIA Technologies                  | 1        | 0.29%   |
| T & A Mobile Phones               | 1        | 0.29%   |
| Smart Link                        | 1        | 0.29%   |
| Nokia Mobile Phones               | 1        | 0.29%   |
| ICS Advent                        | 1        | 0.29%   |
| Huawei Technologies               | 1        | 0.29%   |
| Edimax Technology                 | 1        | 0.29%   |
| D-Link System                     | 1        | 0.29%   |
| Broadcom Limited                  | 1        | 0.29%   |
| ASUSTek Computer                  | 1        | 0.29%   |
| Aquantia                          | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 116      | 31.18%  |
| Realtek RTL8125 2.5GbE Controller                                      | 26       | 6.99%   |
| Intel Wi-Fi 6 AX200                                                    | 9        | 2.42%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 2.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7        | 1.88%   |
| Intel Ethernet Controller I225-V                                       | 6        | 1.61%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 1.61%   |
| Intel Ethernet Connection (2) I218-V                                   | 6        | 1.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 5        | 1.34%   |
| Qualcomm Atheros AR9271 802.11n                                        | 5        | 1.34%   |
| Intel Ethernet Connection I217-LM                                      | 5        | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 1.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 1.08%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 1.08%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 1.08%   |
| Intel Ethernet Connection I217-V                                       | 4        | 1.08%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 1.08%   |
| Ralink MT7601U Wireless Adapter                                        | 3        | 0.81%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 3        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3        | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 0.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 0.81%   |
| Intel 700 Series Chipset CNVi WiFi                                     | 3        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3        | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 0.54%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 2        | 0.54%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 2        | 0.54%   |
| TP-Link 802.11ac NIC                                                   | 2        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.54%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 0.54%   |
| Realtek 802.11ac NIC                                                   | 2        | 0.54%   |
| Ralink RT2070 Wireless Adapter                                         | 2        | 0.54%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 2        | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 0.54%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter             | 2        | 0.54%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 0.54%   |
| NetGear A6210                                                          | 2        | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 21       | 22.11%  |
| Realtek Semiconductor           | 14       | 14.74%  |
| TP-Link                         | 12       | 12.63%  |
| MediaTek                        | 7        | 7.37%   |
| Broadcom                        | 7        | 7.37%   |
| Ralink Technology               | 6        | 6.32%   |
| Ralink                          | 5        | 5.26%   |
| Qualcomm Atheros Communications | 5        | 5.26%   |
| Qualcomm Atheros                | 5        | 5.26%   |
| D-Link                          | 5        | 5.26%   |
| NetGear                         | 2        | 2.11%   |
| Microsoft                       | 2        | 2.11%   |
| Linksys                         | 2        | 2.11%   |
| Edimax Technology               | 1        | 1.05%   |
| ASUSTek Computer                | 1        | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 9        | 9.28%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 5        | 5.15%   |
| Qualcomm Atheros AR9271 802.11n                                      | 5        | 5.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4        | 4.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 4        | 4.12%   |
| Ralink MT7601U Wireless Adapter                                      | 3        | 3.09%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 3        | 3.09%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 3        | 3.09%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 2        | 2.06%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 2        | 2.06%   |
| TP-Link 802.11ac NIC                                                 | 2        | 2.06%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 2        | 2.06%   |
| Realtek 802.11ac NIC                                                 | 2        | 2.06%   |
| Ralink RT2070 Wireless Adapter                                       | 2        | 2.06%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 2.06%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter           | 2        | 2.06%   |
| NetGear A6210                                                        | 2        | 2.06%   |
| Intel Wireless 3165                                                  | 2        | 2.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 2.06%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 2        | 2.06%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 2        | 2.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2        | 2.06%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.03%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.03%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1        | 1.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 1.03%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 1.03%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 1.03%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 1        | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1        | 1.03%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 1.03%   |
| Microsoft Wireless XBox Controller Dongle                            | 1        | 1.03%   |
| MediaTek WiFi                                                        | 1        | 1.03%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1        | 1.03%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 1        | 1.03%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                  | 1        | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 152      | 57.58%  |
| Intel                             | 70       | 26.52%  |
| Qualcomm Atheros                  | 9        | 3.41%   |
| Nvidia                            | 4        | 1.52%   |
| MediaTek                          | 4        | 1.52%   |
| ASIX Electronics                  | 4        | 1.52%   |
| Samsung Electronics               | 3        | 1.14%   |
| Marvell Technology Group          | 3        | 1.14%   |
| Broadcom                          | 3        | 1.14%   |
| Xiaomi                            | 2        | 0.76%   |
| Sundance Technology Inc / IC Plus | 2        | 0.76%   |
| VIA Technologies                  | 1        | 0.38%   |
| TP-Link                           | 1        | 0.38%   |
| T & A Mobile Phones               | 1        | 0.38%   |
| ICS Advent                        | 1        | 0.38%   |
| Huawei Technologies               | 1        | 0.38%   |
| D-Link System                     | 1        | 0.38%   |
| Broadcom Limited                  | 1        | 0.38%   |
| Aquantia                          | 1        | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 116      | 42.65%  |
| Realtek RTL8125 2.5GbE Controller                                          | 26       | 9.56%   |
| Intel Ethernet Connection (2) I219-V                                       | 8        | 2.94%   |
| Intel Ethernet Controller I225-V                                           | 6        | 2.21%   |
| Intel Ethernet Connection (7) I219-V                                       | 6        | 2.21%   |
| Intel Ethernet Connection (2) I218-V                                       | 6        | 2.21%   |
| Intel Ethernet Connection I217-LM                                          | 5        | 1.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 4        | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 4        | 1.47%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 1.47%   |
| Intel I210 Gigabit Network Connection                                      | 4        | 1.47%   |
| Intel Ethernet Connection I217-V                                           | 4        | 1.47%   |
| Intel 82579V Gigabit Network Connection                                    | 4        | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 1.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter              | 3        | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                                      | 3        | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 3        | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                              | 3        | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 2        | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 2        | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.74%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 0.74%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 0.74%   |
| Intel Ethernet Connection (17) I219-V                                      | 2        | 0.74%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.37%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]            | 1        | 0.37%   |
| T & A Mobile Phones 9008A                                                  | 1        | 0.37%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1        | 0.37%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.37%   |
| Realtek RTL8126 5GbE Controller                                            | 1        | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 239      | 72.64%  |
| WiFi     | 87       | 26.44%  |
| Modem    | 2        | 0.61%   |
| Unknown  | 1        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 187      | 76.64%  |
| WiFi     | 57       | 23.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 171      | 70.08%  |
| 2     | 64       | 26.23%  |
| 0     | 5        | 2.05%   |
| 3     | 2        | 0.82%   |
| 13    | 1        | 0.41%   |
| 4     | 1        | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 224      | 92.18%  |
| Yes  | 19       | 7.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 21       | 32.31%  |
| Cambridge Silicon Radio         | 12       | 18.46%  |
| Realtek Semiconductor           | 6        | 9.23%   |
| MediaTek                        | 4        | 6.15%   |
| IMC Networks                    | 4        | 6.15%   |
| Foxconn / Hon Hai               | 4        | 6.15%   |
| Broadcom                        | 4        | 6.15%   |
| TP-Link                         | 3        | 4.62%   |
| Integrated System Solution      | 2        | 3.08%   |
| ASUSTek Computer                | 2        | 3.08%   |
| Apple                           | 2        | 3.08%   |
| Qualcomm Atheros Communications | 1        | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 12       | 18.46%  |
| Intel AX200 Bluetooth                                 | 9        | 13.85%  |
| Realtek Bluetooth Radio                               | 5        | 7.69%   |
| MediaTek Wireless_Device                              | 4        | 6.15%   |
| Intel Bluetooth wireless interface                    | 4        | 6.15%   |
| Intel Bluetooth Device                                | 4        | 6.15%   |
| TP-Link TP-T@- UB500 Adapter                          | 3        | 4.62%   |
| IMC Networks Wireless_Device                          | 3        | 4.62%   |
| Foxconn / Hon Hai Wireless_Device                     | 3        | 4.62%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 3.08%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 3.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 3.08%   |
| Realtek Bluetooth 5.3 Radio                           | 1        | 1.54%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 1.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.54%   |
| Intel AX201 Bluetooth                                 | 1        | 1.54%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.54%   |
| Integrated System Solution Bluetooth Device           | 1        | 1.54%   |
| IMC Networks BCM20702A0                               | 1        | 1.54%   |
| Foxconn / Hon Hai BT                                  | 1        | 1.54%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 1.54%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 1.54%   |
| Apple Bluetooth USB Host Controller                   | 1        | 1.54%   |
| Apple Bluetooth Host Controller                       | 1        | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 140      | 32.11%  |
| Intel                                | 137      | 31.42%  |
| Nvidia                               | 93       | 21.33%  |
| C-Media Electronics                  | 13       | 2.98%   |
| Logitech                             | 9        | 2.06%   |
| Creative Labs                        | 3        | 0.69%   |
| Yamaha                               | 2        | 0.46%   |
| VIA Technologies                     | 2        | 0.46%   |
| Tenx Technology                      | 2        | 0.46%   |
| Microsoft                            | 2        | 0.46%   |
| Generalplus Technology               | 2        | 0.46%   |
| Creative Technology                  | 2        | 0.46%   |
| ASUSTek Computer                     | 2        | 0.46%   |
| Unknown                              | 2        | 0.46%   |
| XMOS                                 | 1        | 0.23%   |
| Xilinx                               | 1        | 0.23%   |
| Walmart                              | 1        | 0.23%   |
| Trust                                | 1        | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.23%   |
| Sony                                 | 1        | 0.23%   |
| SAVITECH                             | 1        | 0.23%   |
| Razer USA                            | 1        | 0.23%   |
| PreSonus Audio Electronics           | 1        | 0.23%   |
| Nordic Semiconductor ASA             | 1        | 0.23%   |
| Native Instruments                   | 1        | 0.23%   |
| MV-SILICON                           | 1        | 0.23%   |
| Micro Star International             | 1        | 0.23%   |
| MCS                                  | 1        | 0.23%   |
| KTMicro                              | 1        | 0.23%   |
| Kingston Technology                  | 1        | 0.23%   |
| JMTek                                | 1        | 0.23%   |
| Hewlett-Packard                      | 1        | 0.23%   |
| GYROCOM C&C                          | 1        | 0.23%   |
| Focusrite-Novation                   | 1        | 0.23%   |
| Ensoniq                              | 1        | 0.23%   |
| Corsair                              | 1        | 0.23%   |
| Cirrus Logic                         | 1        | 0.23%   |
| ATI Technologies                     | 1        | 0.23%   |
| Astro Gaming                         | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                              | 29       | 5.61%   |
| AMD Starship/Matisse HD Audio Controller                                   | 26       | 5.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18       | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17       | 3.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16       | 3.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15       | 2.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 2.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 14       | 2.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14       | 2.71%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 13       | 2.51%   |
| Intel 200 Series PCH HD Audio                                              | 11       | 2.13%   |
| AMD Radeon High Definition Audio Controller                                | 11       | 2.13%   |
| Nvidia TU116 High Definition Audio Controller                              | 10       | 1.93%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 10       | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 1.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 1.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 1.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9        | 1.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 1.55%   |
| Nvidia GM206 High Definition Audio Controller                              | 7        | 1.35%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 7        | 1.35%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 7        | 1.35%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 1.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 1.16%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 6        | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 1.16%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 6        | 1.16%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 0.97%   |
| Intel Raptor Lake High Definition Audio Controller                         | 5        | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 0.97%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 5        | 0.97%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 0.97%   |
| AMD FCH Azalia Controller                                                  | 5        | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.77%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 0.77%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 48       | 31.17%  |
| Corsair             | 24       | 15.58%  |
| G.Skill             | 22       | 14.29%  |
| Unknown             | 13       | 8.44%   |
| SK hynix            | 10       | 6.49%   |
| Samsung Electronics | 9        | 5.84%   |
| Crucial             | 8        | 5.19%   |
| Transcend           | 3        | 1.95%   |
| Patriot             | 2        | 1.3%    |
| Micron Technology   | 2        | 1.3%    |
| Kingmax             | 2        | 1.3%    |
| Elpida              | 2        | 1.3%    |
| A-DATA Technology   | 2        | 1.3%    |
| Unknown (0x0B45)    | 1        | 0.65%   |
| Team                | 1        | 0.65%   |
| Silicon Power       | 1        | 0.65%   |
| Ramaxel Technology  | 1        | 0.65%   |
| Mushkin             | 1        | 0.65%   |
| Apacer              | 1        | 0.65%   |
| Unknown             | 1        | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4        | 2.47%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 3        | 1.85%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s              | 3        | 1.85%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s             | 3        | 1.85%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s            | 3        | 1.85%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s           | 3        | 1.85%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 2        | 1.23%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s              | 2        | 1.23%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s              | 2        | 1.23%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s              | 2        | 1.23%   |
| Kingston RAM KF560C40-16 16GB DIMM 6000MT/s                      | 2        | 1.23%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s             | 2        | 1.23%   |
| G.Skill RAM F5-6000J3040F16G 16GB DIMM DDR5 6000MT/s             | 2        | 1.23%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s              | 2        | 1.23%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3600MT/s               | 2        | 1.23%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s             | 2        | 1.23%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3200MT/s            | 2        | 1.23%   |
| Corsair RAM CML4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s              | 2        | 1.23%   |
| Unknown RAM Module 512MB DIMM DDR2 533MT/s                       | 1        | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1        | 0.62%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                        | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 1333MT/s                        | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                             | 1        | 0.62%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1        | 0.62%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                          | 1        | 0.62%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1        | 0.62%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                       | 1        | 0.62%   |
| Unknown RAM 4000 C19 Series 8192MB DIMM DDR4 4000MT/s            | 1        | 0.62%   |
| Unknown (0x0B45) RAM WPBH32D416SWA-16G 16GB SODIMM DDR4 3200MT/s | 1        | 0.62%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s             | 1        | 0.62%   |
| Transcend RAM JM1600KLN-2G 2GB DIMM DDR3 1333MT/s                | 1        | 0.62%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s                | 1        | 0.62%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1866MT/s               | 1        | 0.62%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1        | 0.62%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 72       | 53.33%  |
| DDR3    | 35       | 25.93%  |
| DDR5    | 14       | 10.37%  |
| SDRAM   | 5        | 3.7%    |
| DDR2    | 4        | 2.96%   |
| Unknown | 4        | 2.96%   |
| DDR     | 1        | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 127      | 94.78%  |
| SODIMM | 7        | 5.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 52       | 36.36%  |
| 16384 | 40       | 27.97%  |
| 4096  | 24       | 16.78%  |
| 2048  | 16       | 11.19%  |
| 32768 | 6        | 4.2%    |
| 1024  | 3        | 2.1%    |
| 49152 | 1        | 0.7%    |
| 512   | 1        | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 19       | 13.48%  |
| 3600  | 14       | 9.93%   |
| 3200  | 12       | 8.51%   |
| 2400  | 11       | 7.8%    |
| 1333  | 11       | 7.8%    |
| 3733  | 8        | 5.67%   |
| 2667  | 8        | 5.67%   |
| 6000  | 7        | 4.96%   |
| 2133  | 7        | 4.96%   |
| 3400  | 6        | 4.26%   |
| 4000  | 3        | 2.13%   |
| 3800  | 3        | 2.13%   |
| 1866  | 3        | 2.13%   |
| 1800  | 3        | 2.13%   |
| 800   | 3        | 2.13%   |
| 5600  | 2        | 1.42%   |
| 667   | 2        | 1.42%   |
| 6600  | 1        | 0.71%   |
| 6400  | 1        | 0.71%   |
| 6200  | 1        | 0.71%   |
| 5200  | 1        | 0.71%   |
| 5000  | 1        | 0.71%   |
| 3933  | 1        | 0.71%   |
| 3466  | 1        | 0.71%   |
| 3334  | 1        | 0.71%   |
| 3333  | 1        | 0.71%   |
| 3000  | 1        | 0.71%   |
| 2933  | 1        | 0.71%   |
| 2866  | 1        | 0.71%   |
| 2800  | 1        | 0.71%   |
| 2666  | 1        | 0.71%   |
| 1867  | 1        | 0.71%   |
| 1067  | 1        | 0.71%   |
| 1066  | 1        | 0.71%   |
| 533   | 1        | 0.71%   |
| 400   | 1        | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Hewlett-Packard              | 9        | 45%     |
| Canon                        | 3        | 15%     |
| Brother Industries           | 3        | 15%     |
| Prolific Technology          | 2        | 10%     |
| Wincor Nixdorf International | 1        | 5%      |
| QinHeng Electronics          | 1        | 5%      |
| Pantum                       | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                   | 2        | 10%     |
| HP LaserJet M14-M17                             | 2        | 10%     |
| HP DeskJet 3630 series                          | 2        | 10%     |
| Brother HL-1110 series                          | 2        | 10%     |
| Wincor Nixdorf International POS Printer, TH230 | 1        | 5%      |
| QinHeng CH340S                                  | 1        | 5%      |
| Pantum P2000                                    | 1        | 5%      |
| HP LaserJet P1102                               | 1        | 5%      |
| HP Ink Tank Wireless 410 series                 | 1        | 5%      |
| HP HP LaserJet M101-M106                        | 1        | 5%      |
| HP DeskJet 2700 series                          | 1        | 5%      |
| HP DeskJet 2130 series                          | 1        | 5%      |
| Canon PIXMA MG2500 Series                       | 1        | 5%      |
| Canon PIXMA iP1800 Printer                      | 1        | 5%      |
| Canon LiDE 400                                  | 1        | 5%      |
| Brother HL-52x0 series                          | 1        | 5%      |

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


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1        | 50%     |
| Canon CanoScan LiDE 220       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 15       | 42.86%  |
| Sunplus Innovation Technology | 4        | 11.43%  |
| Microdia                      | 4        | 11.43%  |
| Realtek Semiconductor         | 3        | 8.57%   |
| Chicony Electronics           | 2        | 5.71%   |
| USB CAMERA                    | 1        | 2.86%   |
| Trust                         | 1        | 2.86%   |
| GenesysLogic Technology       | 1        | 2.86%   |
| Genesys Logic                 | 1        | 2.86%   |
| Creative Technology           | 1        | 2.86%   |
| Anker                         | 1        | 2.86%   |
| Alcor Micro                   | 1        | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Sunplus Full HD webcam                 | 4        | 11.43%  |
| Logitech Webcam C270                   | 4        | 11.43%  |
| Microdia Camera                        | 2        | 5.71%   |
| Logitech Webcam C170                   | 2        | 5.71%   |
| USB CAMERA USB CAMERA                  | 1        | 2.86%   |
| Trust Full HD Webcam                   | 1        | 2.86%   |
| Realtek USB Camera                     | 1        | 2.86%   |
| Realtek FULL HD 1080P Webcam           | 1        | 2.86%   |
| Realtek Asus laptop camera             | 1        | 2.86%   |
| Microdia Sonix USB 2.0 Camera          | 1        | 2.86%   |
| Microdia CyberTrack H7                 | 1        | 2.86%   |
| Logitech Webcam C310                   | 1        | 2.86%   |
| Logitech Webcam C250                   | 1        | 2.86%   |
| Logitech Webcam C210                   | 1        | 2.86%   |
| Logitech Webcam C110                   | 1        | 2.86%   |
| Logitech QuickCam Communicate MP/S5500 | 1        | 2.86%   |
| Logitech Logitech Webcam C925e         | 1        | 2.86%   |
| Logitech HD Pro Webcam C920            | 1        | 2.86%   |
| Logitech C922 Pro Stream Webcam        | 1        | 2.86%   |
| Logitech Brio 500                      | 1        | 2.86%   |
| GenesysLogic USB2.0 UVC PC Camera      | 1        | 2.86%   |
| Genesys Logic USB2.0 UVC PC Camera     | 1        | 2.86%   |
| Creative Live! Cam Sync 1080p V2       | 1        | 2.86%   |
| Chicony HP High Definition Webcam      | 1        | 2.86%   |
| Chicony HP High Definition 1MP Webcam  | 1        | 2.86%   |
| Anker PowerConf C300                   | 1        | 2.86%   |
| Alcor Micro USB 2.0 Camera             | 1        | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Gemalto (was Gemplus)      | 3        | 42.86%  |
| Aladdin Knowledge Systems  | 2        | 28.57%  |
| MagTek                     | 1        | 14.29%  |
| Athena Smartcard Solutions | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Key SmartCard Reader  | 2        | 28.57%  |
| Aladdin Knowledge Systems Token JC                | 2        | 28.57%  |
| MagTek ZCS100                                     | 1        | 14.29%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 14.29%  |
| Athena Smartcard Solutions ASEDrive V3C           | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 209      | 84.96%  |
| 1     | 28       | 11.38%  |
| 2     | 8        | 3.25%   |
| 3     | 1        | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 12       | 27.91%  |
| Graphics card            | 12       | 27.91%  |
| Chipcard                 | 4        | 9.3%    |
| Bluetooth                | 4        | 9.3%    |
| Unassigned class         | 3        | 6.98%   |
| Communication controller | 3        | 6.98%   |
| Storage/raid             | 1        | 2.33%   |
| Sound                    | 1        | 2.33%   |
| Network                  | 1        | 2.33%   |
| Modem                    | 1        | 2.33%   |
| Fingerprint reader       | 1        | 2.33%   |

