Linux in Finland - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Finland.

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

Total: 1021

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | Alder Lake-H PCH E1.1G      | [fa7a5b2aa3](https://linux-hardware.org/?probe=fa7a5b2aa3) | Jan 31, 2024 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [a8411850db](https://linux-hardware.org/?probe=a8411850db) | Jan 30, 2024 |
| MSI           | MS-6702E                    | [9624bc0fe2](https://linux-hardware.org/?probe=9624bc0fe2) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [4e6d22c388](https://linux-hardware.org/?probe=4e6d22c388) | Jan 28, 2024 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [85fd42ad4d](https://linux-hardware.org/?probe=85fd42ad4d) | Jan 27, 2024 |
| Dell          | 0TTDMJ A00                  | [e5d9f41477](https://linux-hardware.org/?probe=e5d9f41477) | Jan 19, 2024 |
| ASRock        | H61M                        | [653436b855](https://linux-hardware.org/?probe=653436b855) | Jan 18, 2024 |
| Dell          | 0MGK50 A02                  | [8ce2d2a81a](https://linux-hardware.org/?probe=8ce2d2a81a) | Jan 17, 2024 |
| SZMZ          | X99 DUAL Z8                 | [623c2e3113](https://linux-hardware.org/?probe=623c2e3113) | Jan 17, 2024 |
| ASRock        | X570 Pro4                   | [1cd88b68af](https://linux-hardware.org/?probe=1cd88b68af) | Jan 17, 2024 |
| ASUSTek       | M2N68-AM Plus               | [3a65e9553a](https://linux-hardware.org/?probe=3a65e9553a) | Jan 17, 2024 |
| ASUSTek       | M2N68-AM Plus               | [07dab6070f](https://linux-hardware.org/?probe=07dab6070f) | Jan 17, 2024 |
| Gigabyte      | F2A85X-D3H                  | [908d3d7353](https://linux-hardware.org/?probe=908d3d7353) | Jan 14, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [08074470dd](https://linux-hardware.org/?probe=08074470dd) | Jan 13, 2024 |
| ASUSTek       | PRIME Z270-P                | [bf8ac62321](https://linux-hardware.org/?probe=bf8ac62321) | Jan 11, 2024 |
| Gigabyte      | F2A85X-D3H                  | [dca0f1d3ab](https://linux-hardware.org/?probe=dca0f1d3ab) | Jan 07, 2024 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | [afda94711c](https://linux-hardware.org/?probe=afda94711c) | Jan 04, 2024 |
| ASUSTek       | P8H67-M                     | [06843ca788](https://linux-hardware.org/?probe=06843ca788) | Jan 04, 2024 |
| ASUSTek       | M2A-MX                      | [9be60381fc](https://linux-hardware.org/?probe=9be60381fc) | Dec 31, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [b7be314f8d](https://linux-hardware.org/?probe=b7be314f8d) | Dec 30, 2023 |
| HP            | 802E                        | [a519d89c9e](https://linux-hardware.org/?probe=a519d89c9e) | Dec 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | [5ec001ca66](https://linux-hardware.org/?probe=5ec001ca66) | Dec 28, 2023 |
| MSI           | B150 GAMING M3              | [2b312f609c](https://linux-hardware.org/?probe=2b312f609c) | Dec 27, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [7eb85caf57](https://linux-hardware.org/?probe=7eb85caf57) | Dec 21, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [4ea2f3364d](https://linux-hardware.org/?probe=4ea2f3364d) | Dec 19, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [df369cf5be](https://linux-hardware.org/?probe=df369cf5be) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bd0bcd2eba](https://linux-hardware.org/?probe=bd0bcd2eba) | Dec 18, 2023 |
| Acer          | Aspire M3920                | [ccca1b4884](https://linux-hardware.org/?probe=ccca1b4884) | Dec 17, 2023 |
| HP            | 81C5 MVB                    | [77e3f530d5](https://linux-hardware.org/?probe=77e3f530d5) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [646c709529](https://linux-hardware.org/?probe=646c709529) | Dec 15, 2023 |
| Dell          | 0TTDMJ A00                  | [66477630d7](https://linux-hardware.org/?probe=66477630d7) | Dec 14, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [af3f6d16ac](https://linux-hardware.org/?probe=af3f6d16ac) | Dec 09, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [74440ebfad](https://linux-hardware.org/?probe=74440ebfad) | Dec 07, 2023 |
| ASRock        | X570 Taichi                 | [0b316f9f1b](https://linux-hardware.org/?probe=0b316f9f1b) | Nov 28, 2023 |
| HP            | 81C5 MVB                    | [90d11dd2b3](https://linux-hardware.org/?probe=90d11dd2b3) | Nov 25, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | [e02ad6b382](https://linux-hardware.org/?probe=e02ad6b382) | Nov 24, 2023 |
| Gigabyte      | B85M-D3V Plus-SI            | [7771038ba5](https://linux-hardware.org/?probe=7771038ba5) | Nov 19, 2023 |
| Gigabyte      | B85M-D3V Plus-SI            | [0e5665d3c6](https://linux-hardware.org/?probe=0e5665d3c6) | Nov 18, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1909f3fbff](https://linux-hardware.org/?probe=1909f3fbff) | Nov 15, 2023 |
| HP            | 0A64h                       | [db072ebaed](https://linux-hardware.org/?probe=db072ebaed) | Nov 14, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [3c2d452ee0](https://linux-hardware.org/?probe=3c2d452ee0) | Nov 13, 2023 |
| HP            | 2B34                        | [24ed29acbc](https://linux-hardware.org/?probe=24ed29acbc) | Nov 13, 2023 |
| ASUSTek       | Z87-A                       | [08f1651d1f](https://linux-hardware.org/?probe=08f1651d1f) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [67938dee90](https://linux-hardware.org/?probe=67938dee90) | Nov 12, 2023 |
| Gigabyte      | EP45-UD3P                   | [20f689bbac](https://linux-hardware.org/?probe=20f689bbac) | Nov 11, 2023 |
| ASUSTek       | PRIME X399-A                | [e0883e3bd0](https://linux-hardware.org/?probe=e0883e3bd0) | Nov 11, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [715a6e7831](https://linux-hardware.org/?probe=715a6e7831) | Nov 10, 2023 |
| HP            | 0A64h                       | [ad021b1397](https://linux-hardware.org/?probe=ad021b1397) | Nov 06, 2023 |
| Lenovo        | T530-28ICB                  | [ba883f99a0](https://linux-hardware.org/?probe=ba883f99a0) | Nov 06, 2023 |
| ASUSTek       | PRIME Z370-A                | [ae66cf41f9](https://linux-hardware.org/?probe=ae66cf41f9) | Nov 03, 2023 |
| ASUSTek       | PRIME Z370-A                | [92b484d86d](https://linux-hardware.org/?probe=92b484d86d) | Nov 03, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [ea285340e0](https://linux-hardware.org/?probe=ea285340e0) | Nov 01, 2023 |
| Gigabyte      | H170N-WIFI-CF               | [af90b19d11](https://linux-hardware.org/?probe=af90b19d11) | Oct 30, 2023 |
| ASUSTek       | P5B                         | [aa136c9e44](https://linux-hardware.org/?probe=aa136c9e44) | Oct 29, 2023 |
| Foxconn       | 2ADA                        | [ce19056aa6](https://linux-hardware.org/?probe=ce19056aa6) | Oct 29, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [c2dc388cd3](https://linux-hardware.org/?probe=c2dc388cd3) | Oct 25, 2023 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [48de72a7a6](https://linux-hardware.org/?probe=48de72a7a6) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [fb66b6579d](https://linux-hardware.org/?probe=fb66b6579d) | Oct 22, 2023 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [8a9d0ba0e6](https://linux-hardware.org/?probe=8a9d0ba0e6) | Oct 22, 2023 |
| Fujitsu Si... | D2828-A1 S26361-D2828-A1    | [c04e21ae93](https://linux-hardware.org/?probe=c04e21ae93) | Oct 19, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [8ff07b1c79](https://linux-hardware.org/?probe=8ff07b1c79) | Oct 19, 2023 |
| ASRock        | H510M-HVS                   | [0766c5afbd](https://linux-hardware.org/?probe=0766c5afbd) | Oct 19, 2023 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [070de2c38f](https://linux-hardware.org/?probe=070de2c38f) | Oct 18, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [d652b15856](https://linux-hardware.org/?probe=d652b15856) | Oct 17, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [5a1df4c4df](https://linux-hardware.org/?probe=5a1df4c4df) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| ASRock        | H97M Anniversary            | [7df48c5c5d](https://linux-hardware.org/?probe=7df48c5c5d) | Oct 14, 2023 |
| ASRock        | 990FX Extreme3              | [662b1d3228](https://linux-hardware.org/?probe=662b1d3228) | Oct 13, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [93499e6693](https://linux-hardware.org/?probe=93499e6693) | Oct 12, 2023 |
| ASUSTek       | P5KR                        | [641c856c71](https://linux-hardware.org/?probe=641c856c71) | Oct 08, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [b838717a3d](https://linux-hardware.org/?probe=b838717a3d) | Oct 07, 2023 |
| ASUSTek       | PRIME B450M-A               | [bf8761b854](https://linux-hardware.org/?probe=bf8761b854) | Oct 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1220b29312](https://linux-hardware.org/?probe=1220b29312) | Oct 05, 2023 |
| HP            | 8433 11                     | [7540fc930b](https://linux-hardware.org/?probe=7540fc930b) | Oct 05, 2023 |
| ASUSTek       | M4A78T-E                    | [0d82fee8df](https://linux-hardware.org/?probe=0d82fee8df) | Oct 02, 2023 |
| HP            | 8433 11                     | [0fcfc69a01](https://linux-hardware.org/?probe=0fcfc69a01) | Oct 02, 2023 |
| Shenzhen M... | F7BAA                       | [30268d41d2](https://linux-hardware.org/?probe=30268d41d2) | Sep 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [85c6c01e63](https://linux-hardware.org/?probe=85c6c01e63) | Sep 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [ed68f904fe](https://linux-hardware.org/?probe=ed68f904fe) | Sep 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [e24beff974](https://linux-hardware.org/?probe=e24beff974) | Sep 26, 2023 |
| ASUSTek       | M4A79T Deluxe               | [ac151127e1](https://linux-hardware.org/?probe=ac151127e1) | Sep 25, 2023 |
| Dell          | 0NW6H5 A00                  | [c3221c93ca](https://linux-hardware.org/?probe=c3221c93ca) | Sep 23, 2023 |
| HP            | 2B34                        | [101780dee0](https://linux-hardware.org/?probe=101780dee0) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | [5783da9442](https://linux-hardware.org/?probe=5783da9442) | Sep 23, 2023 |
| ASRock        | AB350 Pro4                  | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [a0ba042279](https://linux-hardware.org/?probe=a0ba042279) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [e6db76aa66](https://linux-hardware.org/?probe=e6db76aa66) | Sep 17, 2023 |
| HP            | 18E7                        | [e5b07fa901](https://linux-hardware.org/?probe=e5b07fa901) | Sep 15, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [33b3749fc5](https://linux-hardware.org/?probe=33b3749fc5) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f1888930f8](https://linux-hardware.org/?probe=f1888930f8) | Sep 04, 2023 |
| HP            | 3397                        | [181c80a502](https://linux-hardware.org/?probe=181c80a502) | Sep 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [06860111ba](https://linux-hardware.org/?probe=06860111ba) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [5222737445](https://linux-hardware.org/?probe=5222737445) | Aug 29, 2023 |
| ASUSTek       | PRIME Z370-P II             | [56692679f3](https://linux-hardware.org/?probe=56692679f3) | Aug 28, 2023 |
| ASUSTek       | Pro WS 565-ACE              | [ae73127da5](https://linux-hardware.org/?probe=ae73127da5) | Aug 28, 2023 |
| HP            | 3397                        | [59d80acf6f](https://linux-hardware.org/?probe=59d80acf6f) | Aug 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c859974eed](https://linux-hardware.org/?probe=c859974eed) | Aug 26, 2023 |
| Fujitsu Si... | MS-7275-VB                  | [2b7a6dab27](https://linux-hardware.org/?probe=2b7a6dab27) | Aug 26, 2023 |
| Fujitsu Si... | MS-7275-VB                  | [2a67da7ab4](https://linux-hardware.org/?probe=2a67da7ab4) | Aug 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [ff1bdfd1e3](https://linux-hardware.org/?probe=ff1bdfd1e3) | Aug 24, 2023 |
| ASRock        | B550M-ITX/ac                | [6b9175d89e](https://linux-hardware.org/?probe=6b9175d89e) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [b52dbe962f](https://linux-hardware.org/?probe=b52dbe962f) | Aug 19, 2023 |
| Gigabyte      | Z77M-D3H                    | [154e2db6b7](https://linux-hardware.org/?probe=154e2db6b7) | Aug 18, 2023 |
| ASUSTek       | PRIME Z270-A                | [c6918bacbd](https://linux-hardware.org/?probe=c6918bacbd) | Aug 18, 2023 |
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
| ASUSTek       | ROG STRIX B650E-I GAMING... | [5d52bf85ca](https://linux-hardware.org/?probe=5d52bf85ca) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [f972a8359d](https://linux-hardware.org/?probe=f972a8359d) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [ab0235d27c](https://linux-hardware.org/?probe=ab0235d27c) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [3446b719ab](https://linux-hardware.org/?probe=3446b719ab) | Aug 15, 2023 |
| ASUSTek       | A88XM-E/USB                 | [e4b403ad5a](https://linux-hardware.org/?probe=e4b403ad5a) | Aug 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [231f8f9b37](https://linux-hardware.org/?probe=231f8f9b37) | Aug 13, 2023 |
| MSI           | MEG X570 UNIFY              | [179381f376](https://linux-hardware.org/?probe=179381f376) | Aug 12, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [873825c261](https://linux-hardware.org/?probe=873825c261) | Aug 07, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [28ee020bed](https://linux-hardware.org/?probe=28ee020bed) | Aug 06, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | [13f47a5399](https://linux-hardware.org/?probe=13f47a5399) | Aug 06, 2023 |
| Medion        | B550A4-EM                   | [f1bf2b93c1](https://linux-hardware.org/?probe=f1bf2b93c1) | Aug 05, 2023 |
| HP            | 8653 A                      | [09f876ab04](https://linux-hardware.org/?probe=09f876ab04) | Aug 02, 2023 |
| HP            | 0AA8h                       | [76dbb0d0a3](https://linux-hardware.org/?probe=76dbb0d0a3) | Jul 31, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [36c7268653](https://linux-hardware.org/?probe=36c7268653) | Jul 31, 2023 |
| ASUSTek       | H97M-PLUS                   | [940e14c90d](https://linux-hardware.org/?probe=940e14c90d) | Jul 31, 2023 |
| ASUSTek       | M2N68-AM Plus               | [c980146db6](https://linux-hardware.org/?probe=c980146db6) | Jul 29, 2023 |
| ASUSTek       | M2N68-AM Plus               | [a9a2ac74bc](https://linux-hardware.org/?probe=a9a2ac74bc) | Jul 29, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [f591b4a83a](https://linux-hardware.org/?probe=f591b4a83a) | Jul 28, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [4f809512a6](https://linux-hardware.org/?probe=4f809512a6) | Jul 26, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [99352602c2](https://linux-hardware.org/?probe=99352602c2) | Jul 24, 2023 |
| ASUSTek       | PRIME X399-A                | [3dac76b45f](https://linux-hardware.org/?probe=3dac76b45f) | Jul 23, 2023 |
| ASUSTek       | PRIME Z270-K                | [97aa2f7158](https://linux-hardware.org/?probe=97aa2f7158) | Jul 22, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [cc9f1fdcd8](https://linux-hardware.org/?probe=cc9f1fdcd8) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [fc0fcad674](https://linux-hardware.org/?probe=fc0fcad674) | Jul 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | [4884c4b183](https://linux-hardware.org/?probe=4884c4b183) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [81d6c4c3bd](https://linux-hardware.org/?probe=81d6c4c3bd) | Jul 15, 2023 |
| MSI           | Z87-G45 GAMING              | [110a53c220](https://linux-hardware.org/?probe=110a53c220) | Jul 13, 2023 |
| ASUSTek       | PRIME Z390-A                | [2551062f30](https://linux-hardware.org/?probe=2551062f30) | Jul 13, 2023 |
| ASUSTek       | P10S-I Series               | [109d52a9be](https://linux-hardware.org/?probe=109d52a9be) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| ASRock        | X570 Taichi                 | [ea2102a05b](https://linux-hardware.org/?probe=ea2102a05b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | [655b6ba155](https://linux-hardware.org/?probe=655b6ba155) | Jul 09, 2023 |
| HP            | 158B                        | [aad7455bc5](https://linux-hardware.org/?probe=aad7455bc5) | Jul 08, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [d122a1cedc](https://linux-hardware.org/?probe=d122a1cedc) | Jul 07, 2023 |
| MSI           | B350 GAMING PLUS            | [8115e08748](https://linux-hardware.org/?probe=8115e08748) | Jul 05, 2023 |
| MSI           | Z170A GAMING M3             | [ebd5d13804](https://linux-hardware.org/?probe=ebd5d13804) | Jul 04, 2023 |
| ASRock        | Z87 Extreme6                | [d69ea1a2cb](https://linux-hardware.org/?probe=d69ea1a2cb) | Jul 02, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [42624c8bb1](https://linux-hardware.org/?probe=42624c8bb1) | Jun 29, 2023 |
| Cisco         | WAVE-694-K9 A0              | [26b9c3adb7](https://linux-hardware.org/?probe=26b9c3adb7) | Jun 27, 2023 |
| ASUSTek       | P5Q-E                       | [55179e2249](https://linux-hardware.org/?probe=55179e2249) | Jun 25, 2023 |
| ASUSTek       | P8P67 PRO                   | [7b33fc2cb8](https://linux-hardware.org/?probe=7b33fc2cb8) | Jun 23, 2023 |
| HP            | 1495                        | [9bdf95d92b](https://linux-hardware.org/?probe=9bdf95d92b) | Jun 21, 2023 |
| ASUSTek       | PRIME B360M-C               | [4dca77df51](https://linux-hardware.org/?probe=4dca77df51) | Jun 21, 2023 |
| ASUSTek       | P8P67 PRO                   | [ba4e83abed](https://linux-hardware.org/?probe=ba4e83abed) | Jun 20, 2023 |
| ASUSTek       | P7P55D LE                   | [285303d1a0](https://linux-hardware.org/?probe=285303d1a0) | Jun 13, 2023 |
| HP            | 3398                        | [7523eb041f](https://linux-hardware.org/?probe=7523eb041f) | Jun 11, 2023 |
| Gigabyte      | B650M GAMING X AX           | [5affc12294](https://linux-hardware.org/?probe=5affc12294) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Foxconn       | 2ABF                        | [8472aba19b](https://linux-hardware.org/?probe=8472aba19b) | May 25, 2023 |
| ASRock        | 890GX Extreme3              | [016f2a8ada](https://linux-hardware.org/?probe=016f2a8ada) | May 24, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [a2a31dbbee](https://linux-hardware.org/?probe=a2a31dbbee) | May 24, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| MSI           | 2AE0                        | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| ASRock        | 890FX Deluxe4               | [c00eb20149](https://linux-hardware.org/?probe=c00eb20149) | May 18, 2023 |
| HP            | 1495                        | [6332ac9d68](https://linux-hardware.org/?probe=6332ac9d68) | May 14, 2023 |
| ASRock        | X299 Taichi                 | [59e43db209](https://linux-hardware.org/?probe=59e43db209) | May 14, 2023 |
| Acer          | Predator G3-605             | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Acer          | Predator G3-605             | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [713564ccd4](https://linux-hardware.org/?probe=713564ccd4) | May 12, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [33f3e64e8f](https://linux-hardware.org/?probe=33f3e64e8f) | May 11, 2023 |
| ASRock        | X670E Pro RS                | [a17449f761](https://linux-hardware.org/?probe=a17449f761) | May 02, 2023 |
| ASRock        | 890FX Deluxe4               | [327a1a2b37](https://linux-hardware.org/?probe=327a1a2b37) | Apr 29, 2023 |
| ASRock        | B550M-ITX/ac                | [0295ab04a7](https://linux-hardware.org/?probe=0295ab04a7) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| HP            | 3029h                       | [35be4d25c4](https://linux-hardware.org/?probe=35be4d25c4) | Apr 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | [962bffed9f](https://linux-hardware.org/?probe=962bffed9f) | Apr 25, 2023 |
| MSI           | B450M MORTAR MAX            | [7560923404](https://linux-hardware.org/?probe=7560923404) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| ASRock        | B550M-ITX/ac                | [4fad4d4a09](https://linux-hardware.org/?probe=4fad4d4a09) | Apr 21, 2023 |
| Dell          | 0T656F A02                  | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [e8b30a69f9](https://linux-hardware.org/?probe=e8b30a69f9) | Apr 16, 2023 |
| ASRock        | H87 Pro4                    | [e85b3e34b0](https://linux-hardware.org/?probe=e85b3e34b0) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [87acc1eb9d](https://linux-hardware.org/?probe=87acc1eb9d) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c3eb775c80](https://linux-hardware.org/?probe=c3eb775c80) | Apr 13, 2023 |
| HP            | 1791                        | [c87bf6d0e1](https://linux-hardware.org/?probe=c87bf6d0e1) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [654728e9fe](https://linux-hardware.org/?probe=654728e9fe) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| Foxconn       | 2ABF                        | [408e2e47c1](https://linux-hardware.org/?probe=408e2e47c1) | Apr 12, 2023 |
| MSI           | B350 GAMING PLUS            | [df2f924a6e](https://linux-hardware.org/?probe=df2f924a6e) | Apr 11, 2023 |
| ASRock        | 970 Pro3 R2.0               | [375bb1794b](https://linux-hardware.org/?probe=375bb1794b) | Apr 08, 2023 |
| ASUSTek       | P5B                         | [a2a4936e2c](https://linux-hardware.org/?probe=a2a4936e2c) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3569575b7c](https://linux-hardware.org/?probe=3569575b7c) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5881a47fd0](https://linux-hardware.org/?probe=5881a47fd0) | Apr 05, 2023 |
| HP            | 18E5                        | [71c68a2c6a](https://linux-hardware.org/?probe=71c68a2c6a) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0662f665d7](https://linux-hardware.org/?probe=0662f665d7) | Apr 03, 2023 |
| HP            | 2AF3                        | [fe33aa7257](https://linux-hardware.org/?probe=fe33aa7257) | Apr 02, 2023 |
| HP            | 0A64h                       | [f4fd3904f0](https://linux-hardware.org/?probe=f4fd3904f0) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [a025953f4c](https://linux-hardware.org/?probe=a025953f4c) | Mar 31, 2023 |
| HP            | 0A64h                       | [9f50595e87](https://linux-hardware.org/?probe=9f50595e87) | Mar 30, 2023 |
| HP            | 18E7                        | [6b64a1639b](https://linux-hardware.org/?probe=6b64a1639b) | Mar 30, 2023 |
| ASRock        | B85M Pro4                   | [d237bcc0a2](https://linux-hardware.org/?probe=d237bcc0a2) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a1d2ac5e6e](https://linux-hardware.org/?probe=a1d2ac5e6e) | Mar 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | [7483952d78](https://linux-hardware.org/?probe=7483952d78) | Mar 29, 2023 |
| ASUSTek       | P8H67                       | [3b9e638ecb](https://linux-hardware.org/?probe=3b9e638ecb) | Mar 26, 2023 |
| ASUSTek       | PRIME B450M-K               | [95b0768bfc](https://linux-hardware.org/?probe=95b0768bfc) | Mar 25, 2023 |
| HP            | 8433 11                     | [1f76e1dc62](https://linux-hardware.org/?probe=1f76e1dc62) | Mar 25, 2023 |
| HP            | 0A64h                       | [c53db667a1](https://linux-hardware.org/?probe=c53db667a1) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0c824a1f88](https://linux-hardware.org/?probe=0c824a1f88) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6a57dfd8fc](https://linux-hardware.org/?probe=6a57dfd8fc) | Mar 23, 2023 |
| ASUSTek       | PRIME B360M-C               | [8cf7b9cc76](https://linux-hardware.org/?probe=8cf7b9cc76) | Mar 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | [3fe3c818f7](https://linux-hardware.org/?probe=3fe3c818f7) | Mar 20, 2023 |
| Intel         | DP55WB AAE64798-205         | [a76d46bf92](https://linux-hardware.org/?probe=a76d46bf92) | Mar 18, 2023 |
| HP            | 805A                        | [fd97efb317](https://linux-hardware.org/?probe=fd97efb317) | Mar 16, 2023 |
| HP            | 8299                        | [59417ae66d](https://linux-hardware.org/?probe=59417ae66d) | Mar 16, 2023 |
| Lenovo        | Annapurna CRB 0B98401 WI... | [c4603a155e](https://linux-hardware.org/?probe=c4603a155e) | Mar 14, 2023 |
| ASUSTek       | P5KR                        | [613bbd6934](https://linux-hardware.org/?probe=613bbd6934) | Mar 14, 2023 |
| MSI           | MPG Z490 GAMING CARBON W... | [a6c5296f86](https://linux-hardware.org/?probe=a6c5296f86) | Mar 12, 2023 |
| HP            | 8433 11                     | [51a4dbf83e](https://linux-hardware.org/?probe=51a4dbf83e) | Mar 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [c5950249eb](https://linux-hardware.org/?probe=c5950249eb) | Mar 11, 2023 |
| ASUSTek       | P6T WS PRO                  | [7d5df3a3d7](https://linux-hardware.org/?probe=7d5df3a3d7) | Mar 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [ca937e17a7](https://linux-hardware.org/?probe=ca937e17a7) | Mar 10, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [fcb5d30135](https://linux-hardware.org/?probe=fcb5d30135) | Mar 09, 2023 |
| Inventec      | Z CLASS A02                 | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| Gigabyte      | B450M GAMING                | [168b8db115](https://linux-hardware.org/?probe=168b8db115) | Mar 06, 2023 |
| MSI           | MS-6702E                    | [e17662e6c0](https://linux-hardware.org/?probe=e17662e6c0) | Mar 05, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [65aa79b0a3](https://linux-hardware.org/?probe=65aa79b0a3) | Mar 05, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [ab7448d0bf](https://linux-hardware.org/?probe=ab7448d0bf) | Mar 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b531e1a7a8](https://linux-hardware.org/?probe=b531e1a7a8) | Mar 04, 2023 |
| ASUSTek       | P7P55D                      | [1c2701a81c](https://linux-hardware.org/?probe=1c2701a81c) | Mar 04, 2023 |
| MSI           | B350 GAMING PLUS            | [c3d6a142c0](https://linux-hardware.org/?probe=c3d6a142c0) | Mar 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [a04a4550d5](https://linux-hardware.org/?probe=a04a4550d5) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [62c37af17b](https://linux-hardware.org/?probe=62c37af17b) | Mar 03, 2023 |
| HP            | 8053                        | [c48153fe6d](https://linux-hardware.org/?probe=c48153fe6d) | Mar 02, 2023 |
| ASUSTek       | PRIME B250-PRO              | [cd58d8a863](https://linux-hardware.org/?probe=cd58d8a863) | Feb 28, 2023 |
| HP            | 18E7                        | [a4fb4affcf](https://linux-hardware.org/?probe=a4fb4affcf) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4018e453c4](https://linux-hardware.org/?probe=4018e453c4) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [48725cdc4d](https://linux-hardware.org/?probe=48725cdc4d) | Feb 28, 2023 |
| ASUSTek       | B150M-C                     | [e675a40455](https://linux-hardware.org/?probe=e675a40455) | Feb 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [a758475e11](https://linux-hardware.org/?probe=a758475e11) | Feb 26, 2023 |
| HP            | 8433 11                     | [881b062090](https://linux-hardware.org/?probe=881b062090) | Feb 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c34909b191](https://linux-hardware.org/?probe=c34909b191) | Feb 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [ec6ab709e5](https://linux-hardware.org/?probe=ec6ab709e5) | Feb 22, 2023 |
| ASUSTek       | P5Q-E                       | [1fd091bff9](https://linux-hardware.org/?probe=1fd091bff9) | Feb 21, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [50261acb6b](https://linux-hardware.org/?probe=50261acb6b) | Feb 21, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [32ed66a6f9](https://linux-hardware.org/?probe=32ed66a6f9) | Feb 20, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [06c110e6f1](https://linux-hardware.org/?probe=06c110e6f1) | Feb 19, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [d94b8cf0e0](https://linux-hardware.org/?probe=d94b8cf0e0) | Feb 18, 2023 |
| ASUSTek       | M5A97 R2.0                  | [8fb0aec13d](https://linux-hardware.org/?probe=8fb0aec13d) | Feb 18, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [c67a2ae3c5](https://linux-hardware.org/?probe=c67a2ae3c5) | Feb 18, 2023 |
| AOpen         | iBDWMt-WBOP R1.00H 55WB3... | [c524d923e6](https://linux-hardware.org/?probe=c524d923e6) | Feb 17, 2023 |
| Pegatron      | 2AD5                        | [5065063fa1](https://linux-hardware.org/?probe=5065063fa1) | Feb 16, 2023 |
| HP            | 8433 11                     | [3f4ea738b6](https://linux-hardware.org/?probe=3f4ea738b6) | Feb 15, 2023 |
| MSI           | Z370 PC PRO                 | [b5744eb259](https://linux-hardware.org/?probe=b5744eb259) | Feb 13, 2023 |
| ASRock        | B550M-ITX/ac                | [79204339d0](https://linux-hardware.org/?probe=79204339d0) | Feb 11, 2023 |
| HP            | 212B                        | [d3ac338cb9](https://linux-hardware.org/?probe=d3ac338cb9) | Feb 11, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [04929299d7](https://linux-hardware.org/?probe=04929299d7) | Feb 10, 2023 |
| HP            | 212B                        | [cc32aa2d27](https://linux-hardware.org/?probe=cc32aa2d27) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3af865ffdf](https://linux-hardware.org/?probe=3af865ffdf) | Feb 07, 2023 |
| Acer          | F690GVM                     | [8110fd6f99](https://linux-hardware.org/?probe=8110fd6f99) | Feb 07, 2023 |
| Gigabyte      | Z77X-UD3H                   | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [c66fb39891](https://linux-hardware.org/?probe=c66fb39891) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| Gigabyte      | EP45-UD3P                   | [da7b0aca1f](https://linux-hardware.org/?probe=da7b0aca1f) | Feb 03, 2023 |
| MSI           | D2415 S26361-D2415-A21      | [3acfaaf14c](https://linux-hardware.org/?probe=3acfaaf14c) | Feb 01, 2023 |
| Intel         | D34010WYK H14771-303        | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| HP            | 805A                        | [b33510966e](https://linux-hardware.org/?probe=b33510966e) | Jan 27, 2023 |
| BESSTAR Te... | TH50                        | [da185120e5](https://linux-hardware.org/?probe=da185120e5) | Jan 25, 2023 |
| Dell          | 0KRC95 A01                  | [9580da1eb5](https://linux-hardware.org/?probe=9580da1eb5) | Jan 25, 2023 |
| ASUSTek       | PRIME H510M-A               | [287c632c93](https://linux-hardware.org/?probe=287c632c93) | Jan 21, 2023 |
| ASUSTek       | PRIME H510M-A               | [83529ed276](https://linux-hardware.org/?probe=83529ed276) | Jan 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [a551d228f4](https://linux-hardware.org/?probe=a551d228f4) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| ASUSTek       | Z97-P                       | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| HP            | 87D6 SMVB                   | [cf2b65f039](https://linux-hardware.org/?probe=cf2b65f039) | Jan 12, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [cc5b67471e](https://linux-hardware.org/?probe=cc5b67471e) | Jan 12, 2023 |
| HP            | 3397                        | [0057e1b40e](https://linux-hardware.org/?probe=0057e1b40e) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| ASUSTek       | M5A97 R2.0                  | [333595c9de](https://linux-hardware.org/?probe=333595c9de) | Jan 10, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [19658b1d4e](https://linux-hardware.org/?probe=19658b1d4e) | Jan 10, 2023 |
| HP            | 3646h                       | [9baf70c121](https://linux-hardware.org/?probe=9baf70c121) | Jan 08, 2023 |
| Foxconn       | ETON                        | [f30a00babb](https://linux-hardware.org/?probe=f30a00babb) | Jan 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [79551dad5b](https://linux-hardware.org/?probe=79551dad5b) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7142941d7c](https://linux-hardware.org/?probe=7142941d7c) | Jan 07, 2023 |
| Gigabyte      | EP45-UD3P                   | [fa5bdcfc4c](https://linux-hardware.org/?probe=fa5bdcfc4c) | Jan 06, 2023 |
| ASUSTek       | M5A97                       | [06ff3bed63](https://linux-hardware.org/?probe=06ff3bed63) | Jan 06, 2023 |
| Dell          | 0D881F A06                  | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | EP45-UD3P                   | [d89c5688d2](https://linux-hardware.org/?probe=d89c5688d2) | Jan 03, 2023 |
| Intel         | X79-SERVER V1.1             | [322b016537](https://linux-hardware.org/?probe=322b016537) | Jan 01, 2023 |
| HP            | 339A                        | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME X570-P                | [33fd3ed258](https://linux-hardware.org/?probe=33fd3ed258) | Dec 29, 2022 |
| ASRock        | Z790M-ITX WiFi              | [c1c0ab5824](https://linux-hardware.org/?probe=c1c0ab5824) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Foxconn       | 2ADA                        | [7a7d8227ee](https://linux-hardware.org/?probe=7a7d8227ee) | Dec 25, 2022 |
| ASUSTek       | PRIME Z270-P                | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| MSI           | B550-A PRO                  | [3d63d2fe51](https://linux-hardware.org/?probe=3d63d2fe51) | Dec 22, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Gigabyte      | X570S AERO G                | [262a879a99](https://linux-hardware.org/?probe=262a879a99) | Dec 19, 2022 |
| Gigabyte      | Z590I VISION D              | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| ASUSTek       | H170-PRO                    | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| ASUSTek       | PRIME B550M-K               | [fa85be7b33](https://linux-hardware.org/?probe=fa85be7b33) | Dec 12, 2022 |
| ASUSTek       | PRIME B550M-K               | [c8890a2f74](https://linux-hardware.org/?probe=c8890a2f74) | Dec 09, 2022 |
| ASRock        | Z77 Pro3                    | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| ASUSTek       | P5Q-E                       | [fb93b5bdfa](https://linux-hardware.org/?probe=fb93b5bdfa) | Dec 06, 2022 |
| MSI           | B450-A PRO MAX              | [8de79673ea](https://linux-hardware.org/?probe=8de79673ea) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| MSI           | B450-A PRO MAX              | [e2f97abdea](https://linux-hardware.org/?probe=e2f97abdea) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| MSI           | B350 GAMING PLUS            | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2813bdf250](https://linux-hardware.org/?probe=2813bdf250) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| ASRock        | AB350M-HDV                  | [9484c00cb6](https://linux-hardware.org/?probe=9484c00cb6) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Intel         | D53427RKE G87971-406        | [e3bc504c6e](https://linux-hardware.org/?probe=e3bc504c6e) | Nov 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [00db55919b](https://linux-hardware.org/?probe=00db55919b) | Nov 14, 2022 |
| HP            | 1998                        | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| Gigabyte      | A320M-H-CF                  | [2a6473f450](https://linux-hardware.org/?probe=2a6473f450) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| Dell          | 0HY9JP A00                  | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| HP            | 8054                        | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| HP            | 8054                        | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| ASUSTek       | H97M-PLUS                   | [dc9837cefc](https://linux-hardware.org/?probe=dc9837cefc) | Nov 09, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [9746d693c3](https://linux-hardware.org/?probe=9746d693c3) | Nov 08, 2022 |
| HP            | 0B4Ch D                     | [6921f657bf](https://linux-hardware.org/?probe=6921f657bf) | Nov 07, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [4b9071c932](https://linux-hardware.org/?probe=4b9071c932) | Nov 01, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| Acer          | Predator PO3-620            | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| HP            | 805A                        | [dbe3ff75e8](https://linux-hardware.org/?probe=dbe3ff75e8) | Oct 24, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [59f7d0820f](https://linux-hardware.org/?probe=59f7d0820f) | Oct 20, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [48d48d4c8e](https://linux-hardware.org/?probe=48d48d4c8e) | Oct 19, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| ASUSTek       | PRIME X370-PRO              | [2495f40df9](https://linux-hardware.org/?probe=2495f40df9) | Oct 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ba8acdb280](https://linux-hardware.org/?probe=ba8acdb280) | Oct 15, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [14891d8a26](https://linux-hardware.org/?probe=14891d8a26) | Oct 13, 2022 |
| Lenovo        | T530-28ICB                  | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | P8P67 LE                    | [08a298f14e](https://linux-hardware.org/?probe=08a298f14e) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | [33cb2c0dce](https://linux-hardware.org/?probe=33cb2c0dce) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | [12486e4114](https://linux-hardware.org/?probe=12486e4114) | Oct 03, 2022 |
| ASUSTek       | Z170-P                      | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0f4b7501b3](https://linux-hardware.org/?probe=0f4b7501b3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [d603e07087](https://linux-hardware.org/?probe=d603e07087) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [a2ebf20cd0](https://linux-hardware.org/?probe=a2ebf20cd0) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| HP            | 0AA0h                       | [5757039d29](https://linux-hardware.org/?probe=5757039d29) | Sep 23, 2022 |
| ASUSTek       | PRIME Z270-P                | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [e620df9580](https://linux-hardware.org/?probe=e620df9580) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASRock        | H97M Anniversary            | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6168b7089f](https://linux-hardware.org/?probe=6168b7089f) | Sep 11, 2022 |
| ASUSTek       | PRIME Z270-P                | [4a00a1ca0b](https://linux-hardware.org/?probe=4a00a1ca0b) | Sep 10, 2022 |
| Dell          | 0TTDMJ A00                  | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| ASUSTek       | M4A78T-E                    | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| MSI           | B350M PRO-VDH               | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| Gigabyte      | Z590I VISION D              | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| HP            | 805A                        | [477936d851](https://linux-hardware.org/?probe=477936d851) | Aug 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2fd4ef02b3](https://linux-hardware.org/?probe=2fd4ef02b3) | Aug 30, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [4b37519faf](https://linux-hardware.org/?probe=4b37519faf) | Aug 29, 2022 |
| HP            | 339A                        | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | B450M-HDV R4.0              | [a180ab604a](https://linux-hardware.org/?probe=a180ab604a) | Aug 26, 2022 |
| ASUSTek       | H97M-PLUS                   | [6bcc6b550f](https://linux-hardware.org/?probe=6bcc6b550f) | Aug 24, 2022 |
| Acer          | Predator G3620              | [b79ed7b47b](https://linux-hardware.org/?probe=b79ed7b47b) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1d0c242f30](https://linux-hardware.org/?probe=1d0c242f30) | Aug 23, 2022 |
| ASRock        | Z75 Pro3                    | [4fbe3d2710](https://linux-hardware.org/?probe=4fbe3d2710) | Aug 22, 2022 |
| Acer          | Predator PO5-600s V:1.0     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| Foxconn       | 2ABF                        | [eaea01215e](https://linux-hardware.org/?probe=eaea01215e) | Aug 17, 2022 |
| Dell          | 0C27VV A01                  | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| ASUSTek       | PRIME B550M-A               | [bd608fb7bc](https://linux-hardware.org/?probe=bd608fb7bc) | Aug 13, 2022 |
| HP            | 805A                        | [c7671a704a](https://linux-hardware.org/?probe=c7671a704a) | Aug 11, 2022 |
| ASUSTek       | M5A97 R2.0                  | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| ASUSTek       | Z87-PRO                     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| Gigabyte      | H55M-UD2H                   | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| Gigabyte      | Z77X-UD3H                   | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| HP            | 1497                        | [2fe6cb5b2c](https://linux-hardware.org/?probe=2fe6cb5b2c) | Aug 07, 2022 |
| HP            | 1497                        | [24959f2c80](https://linux-hardware.org/?probe=24959f2c80) | Aug 07, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| ASUSTek       | PRIME B450M-A               | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Gigabyte      | B85-HD3                     | [ca37936b6f](https://linux-hardware.org/?probe=ca37936b6f) | Jul 28, 2022 |
| ASRock        | X399 Taichi                 | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | PRIME Z270-A                | [70ddacf43f](https://linux-hardware.org/?probe=70ddacf43f) | Jul 25, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [b35dabeb45](https://linux-hardware.org/?probe=b35dabeb45) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [2625b243eb](https://linux-hardware.org/?probe=2625b243eb) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [25728e964b](https://linux-hardware.org/?probe=25728e964b) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [9558ff01e9](https://linux-hardware.org/?probe=9558ff01e9) | Jul 20, 2022 |
| Dell          | 0GM819                      | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| HP            | 3647h                       | [f59774eab5](https://linux-hardware.org/?probe=f59774eab5) | Jun 30, 2022 |
| Gigabyte      | B150-HD3P-CF                | [c62062eac9](https://linux-hardware.org/?probe=c62062eac9) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [36bf4dc378](https://linux-hardware.org/?probe=36bf4dc378) | Jun 13, 2022 |
| Dell          | 0RW203                      | [d53558bc85](https://linux-hardware.org/?probe=d53558bc85) | Jun 12, 2022 |
| Supermicro    | X10SBA-LA                   | [4b46c69e08](https://linux-hardware.org/?probe=4b46c69e08) | Jun 03, 2022 |
| ASUSTek       | P8H67                       | [dff99aa7e6](https://linux-hardware.org/?probe=dff99aa7e6) | May 30, 2022 |
| HP            | 1998                        | [48be2e4a99](https://linux-hardware.org/?probe=48be2e4a99) | May 30, 2022 |
| HP            | 1998                        | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| ASRock        | X99 Taichi                  | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| ASUSTek       | H97M-PLUS                   | [d2e3603431](https://linux-hardware.org/?probe=d2e3603431) | May 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [244be4f232](https://linux-hardware.org/?probe=244be4f232) | May 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [587c1deb4c](https://linux-hardware.org/?probe=587c1deb4c) | May 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| ASUSTek       | P8H67                       | [d94b81d9d3](https://linux-hardware.org/?probe=d94b81d9d3) | May 12, 2022 |
| HP            | 805F                        | [466bb8cc36](https://linux-hardware.org/?probe=466bb8cc36) | May 10, 2022 |
| ASUSTek       | P8B75-V                     | [b4ecefaba5](https://linux-hardware.org/?probe=b4ecefaba5) | May 09, 2022 |
| Acer          | RS780HVF                    | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| MSI           | Z87M GAMING                 | [7e95657ad7](https://linux-hardware.org/?probe=7e95657ad7) | May 08, 2022 |
| ASUSTek       | Z170-A                      | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| ASUSTek       | AM1M-A                      | [537def711a](https://linux-hardware.org/?probe=537def711a) | May 08, 2022 |
| Acer          | RS780HVF                    | [1f30630929](https://linux-hardware.org/?probe=1f30630929) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| Supermicro    | X8ST3                       | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Acer          | H57M01                      | [180132b3e1](https://linux-hardware.org/?probe=180132b3e1) | May 03, 2022 |
| Acer          | FX58M                       | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| HP            | 1589                        | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| ASUSTek       | P5B                         | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| MSI           | B550-A PRO                  | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| Gigabyte      | B450M S2H                   | [2e84d98937](https://linux-hardware.org/?probe=2e84d98937) | Apr 29, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [1612f46137](https://linux-hardware.org/?probe=1612f46137) | Apr 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| ASRock        | Z87 Extreme6                | [d7e24821ee](https://linux-hardware.org/?probe=d7e24821ee) | Apr 18, 2022 |
| Dell          | 0HY9JP A00                  | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| MSI           | Indio                       | [ca3a24d84d](https://linux-hardware.org/?probe=ca3a24d84d) | Apr 13, 2022 |
| MSI           | Z370 PC PRO                 | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | [1a910e93c5](https://linux-hardware.org/?probe=1a910e93c5) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | [2d350f40d2](https://linux-hardware.org/?probe=2d350f40d2) | Apr 09, 2022 |
| Acer          | Batman A01                  | [a102f85d9d](https://linux-hardware.org/?probe=a102f85d9d) | Apr 08, 2022 |
| Gigabyte      | H410M H V3                  | [1a1c86083e](https://linux-hardware.org/?probe=1a1c86083e) | Apr 07, 2022 |
| HP            | 18E7                        | [35dbcc5737](https://linux-hardware.org/?probe=35dbcc5737) | Apr 07, 2022 |
| ASUSTek       | B150M-K                     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire TC-120               | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASRock        | B85M-ITX                    | [1a2849588f](https://linux-hardware.org/?probe=1a2849588f) | Apr 01, 2022 |
| HP            | 3047h                       | [356fac6a3a](https://linux-hardware.org/?probe=356fac6a3a) | Apr 01, 2022 |
| HP            | 3047h                       | [d4c9852b3c](https://linux-hardware.org/?probe=d4c9852b3c) | Apr 01, 2022 |
| MSI           | 990FXA-GD65                 | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [79c9d66395](https://linux-hardware.org/?probe=79c9d66395) | Mar 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [7b835e9a57](https://linux-hardware.org/?probe=7b835e9a57) | Mar 23, 2022 |
| ASRock        | AB350M-HDV                  | [069ce018ad](https://linux-hardware.org/?probe=069ce018ad) | Mar 22, 2022 |
| Gigabyte      | H61M-S2PV                   | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| Acer          | FX58M                       | [7404e9534e](https://linux-hardware.org/?probe=7404e9534e) | Mar 09, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [2142681934](https://linux-hardware.org/?probe=2142681934) | Mar 06, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| ASUSTek       | Maximus VIII IMPACT         | [2e19b36624](https://linux-hardware.org/?probe=2e19b36624) | Mar 03, 2022 |
| Acer          | Aspire XC-105               | [0dd55e5b26](https://linux-hardware.org/?probe=0dd55e5b26) | Feb 26, 2022 |
| ABIT          | IP35                        | [278dd592cc](https://linux-hardware.org/?probe=278dd592cc) | Feb 26, 2022 |
| ASUSTek       | Z170-K                      | [cfdffcf6ab](https://linux-hardware.org/?probe=cfdffcf6ab) | Feb 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [f12d1e47df](https://linux-hardware.org/?probe=f12d1e47df) | Feb 24, 2022 |
| ASRock        | AB350M-HDV                  | [5fe85bba2e](https://linux-hardware.org/?probe=5fe85bba2e) | Feb 22, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [8b588bf90b](https://linux-hardware.org/?probe=8b588bf90b) | Feb 15, 2022 |
| ASRock        | 890FX Deluxe4               | [33a47b3c4b](https://linux-hardware.org/?probe=33a47b3c4b) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [040550cdaa](https://linux-hardware.org/?probe=040550cdaa) | Feb 11, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [ba2262bba5](https://linux-hardware.org/?probe=ba2262bba5) | Feb 10, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [3d76f83751](https://linux-hardware.org/?probe=3d76f83751) | Feb 10, 2022 |
| ASUSTek       | H97M-PLUS                   | [75b31509a3](https://linux-hardware.org/?probe=75b31509a3) | Feb 09, 2022 |
| ASUSTek       | H97M-PLUS                   | [88fdd17fc6](https://linux-hardware.org/?probe=88fdd17fc6) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [22be2d64a2](https://linux-hardware.org/?probe=22be2d64a2) | Feb 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [035ccaeec8](https://linux-hardware.org/?probe=035ccaeec8) | Feb 04, 2022 |
| Dell          | 051FJ8 A00                  | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| MSI           | Z170A PC MATE               | [e83deb15fd](https://linux-hardware.org/?probe=e83deb15fd) | Jan 31, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [5f6a8cf57f](https://linux-hardware.org/?probe=5f6a8cf57f) | Jan 29, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [9ff78b6d13](https://linux-hardware.org/?probe=9ff78b6d13) | Jan 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| ASRock        | H510M-HVS                   | [ef779f5d49](https://linux-hardware.org/?probe=ef779f5d49) | Jan 26, 2022 |
| ASRock        | AB350M-HDV                  | [cf5823e07b](https://linux-hardware.org/?probe=cf5823e07b) | Jan 26, 2022 |
| Packard Be... | IMEDIA S3840                | [eff4bf09ec](https://linux-hardware.org/?probe=eff4bf09ec) | Jan 26, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [88049a6cee](https://linux-hardware.org/?probe=88049a6cee) | Jan 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | [8f7c57b03f](https://linux-hardware.org/?probe=8f7c57b03f) | Jan 18, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [5f904131f5](https://linux-hardware.org/?probe=5f904131f5) | Jan 18, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [06c4be96aa](https://linux-hardware.org/?probe=06c4be96aa) | Jan 17, 2022 |
| HP            | 18E5                        | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| HP            | 1495                        | [ea7df45832](https://linux-hardware.org/?probe=ea7df45832) | Jan 14, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [e82feb71d2](https://linux-hardware.org/?probe=e82feb71d2) | Jan 12, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0529614510](https://linux-hardware.org/?probe=0529614510) | Jan 12, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | [1da9aea182](https://linux-hardware.org/?probe=1da9aea182) | Jan 10, 2022 |
| HP            | 3646h                       | [85edd0c1bf](https://linux-hardware.org/?probe=85edd0c1bf) | Jan 08, 2022 |
| HP            | 3646h                       | [616a0acd31](https://linux-hardware.org/?probe=616a0acd31) | Jan 08, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [72fa18d5dd](https://linux-hardware.org/?probe=72fa18d5dd) | Jan 08, 2022 |
| MSI           | H110M ECO                   | [c056a2eafa](https://linux-hardware.org/?probe=c056a2eafa) | Jan 07, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | [6f8a6d74e4](https://linux-hardware.org/?probe=6f8a6d74e4) | Jan 07, 2022 |
| Acer          | WMCP78M                     | [250fa57c5d](https://linux-hardware.org/?probe=250fa57c5d) | Jan 05, 2022 |
| Gigabyte      | 970A-UD3P                   | [c28c0f7f40](https://linux-hardware.org/?probe=c28c0f7f40) | Jan 04, 2022 |
| HP            | 3397                        | [188bb8c669](https://linux-hardware.org/?probe=188bb8c669) | Dec 28, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| ASUSTek       | A_F_K20CE                   | [4365a457d8](https://linux-hardware.org/?probe=4365a457d8) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | [a1c07a7e6a](https://linux-hardware.org/?probe=a1c07a7e6a) | Dec 15, 2021 |
| ASRock        | AB350 Pro4                  | [002a05b1c7](https://linux-hardware.org/?probe=002a05b1c7) | Dec 14, 2021 |
| ASUSTek       | Z97-C                       | [3284718afd](https://linux-hardware.org/?probe=3284718afd) | Dec 01, 2021 |
| HP            | 3646h                       | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | SABERTOOTH Z87              | [71d6a80bd1](https://linux-hardware.org/?probe=71d6a80bd1) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6591fce926](https://linux-hardware.org/?probe=6591fce926) | Nov 27, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [3355d6fd50](https://linux-hardware.org/?probe=3355d6fd50) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f62619c698](https://linux-hardware.org/?probe=f62619c698) | Nov 24, 2021 |
| Acer          | WMCP78M                     | [5930f530bb](https://linux-hardware.org/?probe=5930f530bb) | Nov 24, 2021 |
| HP            | 3647h                       | [e3d0601f0b](https://linux-hardware.org/?probe=e3d0601f0b) | Nov 23, 2021 |
| Gigabyte      | Z270X-Gaming K5             | [613686da3f](https://linux-hardware.org/?probe=613686da3f) | Nov 22, 2021 |
| HP            | 8433 11                     | [e88c3d4a94](https://linux-hardware.org/?probe=e88c3d4a94) | Nov 22, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| Lenovo        | ThinkStation S20 4157FY2    | [b05be2384d](https://linux-hardware.org/?probe=b05be2384d) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0581432da](https://linux-hardware.org/?probe=d0581432da) | Nov 20, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [646919d578](https://linux-hardware.org/?probe=646919d578) | Nov 20, 2021 |
| Dell          | 00F82W A01                  | [972f96ba1d](https://linux-hardware.org/?probe=972f96ba1d) | Nov 17, 2021 |
| ASRock        | B450M-HDV                   | [d004277425](https://linux-hardware.org/?probe=d004277425) | Nov 14, 2021 |
| MSI           | X570-A PRO                  | [1d72b572ac](https://linux-hardware.org/?probe=1d72b572ac) | Nov 14, 2021 |
| HP            | 1495                        | [d66a2a8cf5](https://linux-hardware.org/?probe=d66a2a8cf5) | Nov 10, 2021 |
| Lenovo        | Kabini CRB 31900003 STD     | [4d94fd8ba6](https://linux-hardware.org/?probe=4d94fd8ba6) | Nov 10, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [b98565dc8e](https://linux-hardware.org/?probe=b98565dc8e) | Nov 09, 2021 |
| HP            | 1495                        | [22bbd228cb](https://linux-hardware.org/?probe=22bbd228cb) | Nov 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8cf09365a4](https://linux-hardware.org/?probe=8cf09365a4) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [10faa36c81](https://linux-hardware.org/?probe=10faa36c81) | Nov 06, 2021 |
| ASUSTek       | A_F_K20CE                   | [a40335233e](https://linux-hardware.org/?probe=a40335233e) | Nov 04, 2021 |
| ASRock        | Z87 Extreme6                | [32b0b7b787](https://linux-hardware.org/?probe=32b0b7b787) | Nov 04, 2021 |
| ABIT          | AI7                         | [75f77dabe1](https://linux-hardware.org/?probe=75f77dabe1) | Nov 03, 2021 |
| ASUSTek       | M2N-E                       | [dfa80f4b9f](https://linux-hardware.org/?probe=dfa80f4b9f) | Oct 31, 2021 |
| ASRock        | 970 Extreme4                | [e10152abc8](https://linux-hardware.org/?probe=e10152abc8) | Oct 25, 2021 |
| ASRock        | 970 Extreme4                | [0f6daccd63](https://linux-hardware.org/?probe=0f6daccd63) | Oct 25, 2021 |
| ASUSTek       | PRIME Z270-P                | [5b429fd560](https://linux-hardware.org/?probe=5b429fd560) | Oct 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [477512ba5c](https://linux-hardware.org/?probe=477512ba5c) | Oct 23, 2021 |
| Gigabyte      | Z170-HD3P-CF                | [c487ba6138](https://linux-hardware.org/?probe=c487ba6138) | Oct 22, 2021 |
| HP            | 158B                        | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [8961245abb](https://linux-hardware.org/?probe=8961245abb) | Oct 15, 2021 |
| ASUSTek       | P8Z68-V                     | [e8ad89cb87](https://linux-hardware.org/?probe=e8ad89cb87) | Oct 12, 2021 |
| HP            | 21D0                        | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [818fe93a6d](https://linux-hardware.org/?probe=818fe93a6d) | Oct 10, 2021 |
| Gigabyte      | Z170-HD3P-CF                | [319f2002de](https://linux-hardware.org/?probe=319f2002de) | Oct 09, 2021 |
| Dell          | 0YC523                      | [cf8d063deb](https://linux-hardware.org/?probe=cf8d063deb) | Oct 09, 2021 |
| MSI           | Z370-A PRO                  | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | [0c5e4a2345](https://linux-hardware.org/?probe=0c5e4a2345) | Oct 02, 2021 |
| HP            | 0AACh                       | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| Medion        | B460H6-EM                   | [b461764429](https://linux-hardware.org/?probe=b461764429) | Sep 27, 2021 |
| MSI           | MS-7211                     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | [7ded59f42f](https://linux-hardware.org/?probe=7ded59f42f) | Sep 21, 2021 |
| ASRock        | B450M-HDV R4.0              | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [22390a295d](https://linux-hardware.org/?probe=22390a295d) | Sep 04, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [7467c9452c](https://linux-hardware.org/?probe=7467c9452c) | Sep 01, 2021 |
| Gigabyte      | H97N-WIFI                   | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [fa40b359a1](https://linux-hardware.org/?probe=fa40b359a1) | Aug 27, 2021 |
| Acer          | RS780HVF                    | [f051228785](https://linux-hardware.org/?probe=f051228785) | Aug 21, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| Acer          | RS780HVF                    | [32c3b00b51](https://linux-hardware.org/?probe=32c3b00b51) | Aug 14, 2021 |
| Acer          | RS780HVF                    | [858844ae39](https://linux-hardware.org/?probe=858844ae39) | Aug 14, 2021 |
| Acer          | Predator G3-710             | [bc8ec0cacc](https://linux-hardware.org/?probe=bc8ec0cacc) | Aug 14, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| ASUSTek       | PRIME X470-PRO              | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| Gigabyte      | B360HD3PLM-CF               | [ab5514ae70](https://linux-hardware.org/?probe=ab5514ae70) | Aug 06, 2021 |
| ASRock        | Z87 Extreme6                | [ec6b248ebe](https://linux-hardware.org/?probe=ec6b248ebe) | Aug 03, 2021 |
| ASRock        | 939A785GMH/128M             | [fe09c8fdc1](https://linux-hardware.org/?probe=fe09c8fdc1) | Aug 03, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [d6735c5f18](https://linux-hardware.org/?probe=d6735c5f18) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [734237b1dc](https://linux-hardware.org/?probe=734237b1dc) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [9ce0842819](https://linux-hardware.org/?probe=9ce0842819) | Aug 02, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0451bc276f](https://linux-hardware.org/?probe=0451bc276f) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| ASUSTek       | P5K-VM                      | [1b2a02afbe](https://linux-hardware.org/?probe=1b2a02afbe) | Jul 31, 2021 |
| HP            | 8437                        | [06f61b9a3f](https://linux-hardware.org/?probe=06f61b9a3f) | Jul 27, 2021 |
| HP            | 8437                        | [3e06775292](https://linux-hardware.org/?probe=3e06775292) | Jul 27, 2021 |
| MSI           | Z370 SLI PLUS               | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Intel         | DP55WG AAE57269-407         | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| HP            | 8437                        | [0764df2f0a](https://linux-hardware.org/?probe=0764df2f0a) | Jul 24, 2021 |
| ASUSTek       | M2N68-AM Plus               | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| ASRock        | 939A785GMH/128M             | [f363c1063a](https://linux-hardware.org/?probe=f363c1063a) | Jul 22, 2021 |
| Gigabyte      | Z270X-Gaming K5             | [384c090a20](https://linux-hardware.org/?probe=384c090a20) | Jul 22, 2021 |
| Dell          | 0C27VV A01                  | [99b906c497](https://linux-hardware.org/?probe=99b906c497) | Jul 21, 2021 |
| Dell          | 0GH911                      | [2aa93c89cd](https://linux-hardware.org/?probe=2aa93c89cd) | Jul 21, 2021 |
| Dell          | 0VHWTR A01                  | [5116710fe0](https://linux-hardware.org/?probe=5116710fe0) | Jul 20, 2021 |
| HP            | 802F                        | [469561ff27](https://linux-hardware.org/?probe=469561ff27) | Jul 20, 2021 |
| ASUSTek       | A88XM-PLUS                  | [4f9f3cbb83](https://linux-hardware.org/?probe=4f9f3cbb83) | Jul 18, 2021 |
| ASUSTek       | NARRA2                      | [e7e7f905c7](https://linux-hardware.org/?probe=e7e7f905c7) | Jul 17, 2021 |
| ASUSTek       | NARRA2                      | [40f65831a3](https://linux-hardware.org/?probe=40f65831a3) | Jul 17, 2021 |
| MSI           | MEG X570 GODLIKE            | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| Pegatron      | 2AB6                        | [d5eb8c32fb](https://linux-hardware.org/?probe=d5eb8c32fb) | Jul 06, 2021 |
| MSI           | Z370-A PRO                  | [557af42b3d](https://linux-hardware.org/?probe=557af42b3d) | Jul 03, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [2043830384](https://linux-hardware.org/?probe=2043830384) | Jun 26, 2021 |
| ASRock        | Z370 Professional Gaming... | [fa3749c0c0](https://linux-hardware.org/?probe=fa3749c0c0) | Jun 22, 2021 |
| ASUSTek       | PRIME Z370-P                | [8ec235f1f1](https://linux-hardware.org/?probe=8ec235f1f1) | Jun 13, 2021 |
| Dell          | 0GH911                      | [3d8aec55af](https://linux-hardware.org/?probe=3d8aec55af) | Jun 10, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [e0db4d0875](https://linux-hardware.org/?probe=e0db4d0875) | Jun 08, 2021 |
| ASRockRack    | B450D4U-V1L                 | [49a0eec9f5](https://linux-hardware.org/?probe=49a0eec9f5) | Jun 05, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [a750453ba5](https://linux-hardware.org/?probe=a750453ba5) | Jun 04, 2021 |
| Gigabyte      | B360HD3PLM-CF               | [a434845c16](https://linux-hardware.org/?probe=a434845c16) | Jun 03, 2021 |
| ASUSTek       | M4A78LT-M                   | [ef97789a6a](https://linux-hardware.org/?probe=ef97789a6a) | May 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [a266b8dd81](https://linux-hardware.org/?probe=a266b8dd81) | May 27, 2021 |
| MSI           | Z370 PC PRO                 | [ddfe32e6ab](https://linux-hardware.org/?probe=ddfe32e6ab) | May 25, 2021 |
| ASUSTek       | P7P55D EVO                  | [66c62dc8f8](https://linux-hardware.org/?probe=66c62dc8f8) | May 22, 2021 |
| HP            | 8433 11                     | [8670420e76](https://linux-hardware.org/?probe=8670420e76) | May 21, 2021 |
| ASRock        | X99M Extreme4               | [fba004a752](https://linux-hardware.org/?probe=fba004a752) | May 20, 2021 |
| ASUSTek       | P8H67                       | [fa879ee1d2](https://linux-hardware.org/?probe=fa879ee1d2) | May 19, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [249ab0aa24](https://linux-hardware.org/?probe=249ab0aa24) | May 19, 2021 |
| ASRock        | Z77 Pro3                    | [a981f9a0c5](https://linux-hardware.org/?probe=a981f9a0c5) | May 12, 2021 |
| ASUSTek       | UN45H                       | [714a70d40a](https://linux-hardware.org/?probe=714a70d40a) | May 07, 2021 |
| ASUSTek       | A88XM-PLUS                  | [4482a1fb69](https://linux-hardware.org/?probe=4482a1fb69) | May 06, 2021 |
| ASUSTek       | UN45H                       | [efc8ac4c79](https://linux-hardware.org/?probe=efc8ac4c79) | May 06, 2021 |
| ASRock        | Z77 Pro3                    | [3ea8d93c76](https://linux-hardware.org/?probe=3ea8d93c76) | May 05, 2021 |
| HP            | 3647h                       | [bd39210291](https://linux-hardware.org/?probe=bd39210291) | May 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | [9482db99b9](https://linux-hardware.org/?probe=9482db99b9) | May 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| ASRock        | X570M Pro4                  | [ef52974aaf](https://linux-hardware.org/?probe=ef52974aaf) | May 03, 2021 |
| ASRock        | X570M Pro4                  | [1c94c5b005](https://linux-hardware.org/?probe=1c94c5b005) | May 03, 2021 |
| MSI           | 2A9C                        | [fbb37a1ceb](https://linux-hardware.org/?probe=fbb37a1ceb) | May 02, 2021 |
| MSI           | 2A9C                        | [1b4573b9c5](https://linux-hardware.org/?probe=1b4573b9c5) | May 02, 2021 |
| Dell          | 0T10XW A01                  | [4ab0e6b099](https://linux-hardware.org/?probe=4ab0e6b099) | May 01, 2021 |
| MSI           | Z370-A PRO                  | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| HP            | 1998                        | [9bb6ae0565](https://linux-hardware.org/?probe=9bb6ae0565) | Apr 18, 2021 |
| ASRock        | Z87 Extreme6                | [6ac1485bc6](https://linux-hardware.org/?probe=6ac1485bc6) | Apr 17, 2021 |
| Pegatron      | APX85-GS                    | [3a6accac1f](https://linux-hardware.org/?probe=3a6accac1f) | Apr 12, 2021 |
| ASUSTek       | P5E                         | [8689ac73b3](https://linux-hardware.org/?probe=8689ac73b3) | Apr 11, 2021 |
| Pegatron      | 2A99                        | [07a84a3b4d](https://linux-hardware.org/?probe=07a84a3b4d) | Apr 11, 2021 |
| HP            | 0A00h                       | [144a5f7819](https://linux-hardware.org/?probe=144a5f7819) | Apr 09, 2021 |
| ASUSTek       | PRIME Z390-P                | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| Pegatron      | 2A72h                       | [e1fff3ade4](https://linux-hardware.org/?probe=e1fff3ade4) | Apr 07, 2021 |
| MSI           | B450I GAMING PLUS AC        | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| Gigabyte      | B550 AORUS PRO              | [e88c887878](https://linux-hardware.org/?probe=e88c887878) | Apr 01, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | [2838e1ca6c](https://linux-hardware.org/?probe=2838e1ca6c) | Mar 30, 2021 |
| ASRock        | ALiveNF6G-GLAN              | [1f409f9bf1](https://linux-hardware.org/?probe=1f409f9bf1) | Mar 28, 2021 |
| HP            | 1589                        | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | [04469024ca](https://linux-hardware.org/?probe=04469024ca) | Mar 27, 2021 |
| HP            | 8054                        | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| ASUSTek       | Z87-K                       | [c412261d89](https://linux-hardware.org/?probe=c412261d89) | Mar 26, 2021 |
| HP            | 802F                        | [ae40d5cbc9](https://linux-hardware.org/?probe=ae40d5cbc9) | Mar 24, 2021 |
| ASUSTek       | P7H55D-M EVO                | [ccb057337e](https://linux-hardware.org/?probe=ccb057337e) | Mar 23, 2021 |
| Shuttle       | FZ77                        | [ca3dfc266d](https://linux-hardware.org/?probe=ca3dfc266d) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| Gigabyte      | M61PME-S2P                  | [72fc5ffa15](https://linux-hardware.org/?probe=72fc5ffa15) | Mar 18, 2021 |
| HP            | 1495                        | [23947d4a1e](https://linux-hardware.org/?probe=23947d4a1e) | Mar 17, 2021 |
| ASUSTek       | Acacia                      | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Dell          | 0C27VV A01                  | [48f8273cdb](https://linux-hardware.org/?probe=48f8273cdb) | Mar 16, 2021 |
| Unknown       | Unknown                     | [e9c99960d1](https://linux-hardware.org/?probe=e9c99960d1) | Mar 16, 2021 |
| ASUSTek       | P5N32-E SLI                 | [11caeb50ac](https://linux-hardware.org/?probe=11caeb50ac) | Mar 16, 2021 |
| MSI           | B450I GAMING PLUS AC        | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| ASUSTek       | Z87-K                       | [2cbefa6c90](https://linux-hardware.org/?probe=2cbefa6c90) | Mar 15, 2021 |
| MSI           | H81M-P33                    | [9487818af0](https://linux-hardware.org/?probe=9487818af0) | Mar 13, 2021 |
| HP            | 859C                        | [6434de9da7](https://linux-hardware.org/?probe=6434de9da7) | Mar 13, 2021 |
| ASRock        | X570 Phantom Gaming X       | [feedeb2b69](https://linux-hardware.org/?probe=feedeb2b69) | Mar 12, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | [e83e8ffa64](https://linux-hardware.org/?probe=e83e8ffa64) | Mar 08, 2021 |
| ASRock        | 990FX Extreme3              | [ee5505ce8e](https://linux-hardware.org/?probe=ee5505ce8e) | Mar 05, 2021 |
| ASUSTek       | P5E                         | [adac4a8f70](https://linux-hardware.org/?probe=adac4a8f70) | Mar 04, 2021 |
| Intel         | DH77KC AAG39641-401         | [1af2ede26c](https://linux-hardware.org/?probe=1af2ede26c) | Mar 03, 2021 |
| ASRock        | 990FX Extreme6              | [8b50e7792e](https://linux-hardware.org/?probe=8b50e7792e) | Mar 02, 2021 |
| Gigabyte      | Z490 VISION D               | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| ASRock        | P67 Extreme4                | [1f91d9a631](https://linux-hardware.org/?probe=1f91d9a631) | Feb 27, 2021 |
| ASRock        | P67 Extreme4                | [ad443f47c2](https://linux-hardware.org/?probe=ad443f47c2) | Feb 27, 2021 |
| HP            | 805A                        | [26d9d2a996](https://linux-hardware.org/?probe=26d9d2a996) | Feb 25, 2021 |
| ASRock        | A320M-HDV                   | [cd111b2c04](https://linux-hardware.org/?probe=cd111b2c04) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | [762e158923](https://linux-hardware.org/?probe=762e158923) | Feb 25, 2021 |
| ASUSTek       | H97M-PLUS                   | [bcbcbdf158](https://linux-hardware.org/?probe=bcbcbdf158) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | [90fa6e7434](https://linux-hardware.org/?probe=90fa6e7434) | Feb 24, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | [601807d0e7](https://linux-hardware.org/?probe=601807d0e7) | Feb 24, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [84ddb6cbec](https://linux-hardware.org/?probe=84ddb6cbec) | Feb 24, 2021 |
| Dell          | 0C27VV A01                  | [d47c258b89](https://linux-hardware.org/?probe=d47c258b89) | Feb 22, 2021 |
| Gigabyte      | G31M-ES2L                   | [ccd37902d0](https://linux-hardware.org/?probe=ccd37902d0) | Feb 22, 2021 |
| Dell          | 0YC523                      | [d805d39715](https://linux-hardware.org/?probe=d805d39715) | Feb 22, 2021 |
| ASUSTek       | P5KPL-CM                    | [c116602ad6](https://linux-hardware.org/?probe=c116602ad6) | Feb 18, 2021 |
| ASUSTek       | H97M-PLUS                   | [b1e9a3d14d](https://linux-hardware.org/?probe=b1e9a3d14d) | Feb 18, 2021 |
| ASUSTek       | Z87M-PLUS                   | [d90fd08234](https://linux-hardware.org/?probe=d90fd08234) | Feb 17, 2021 |
| ECS           | Nettle3                     | [fb2a315c43](https://linux-hardware.org/?probe=fb2a315c43) | Feb 16, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [ce117380dd](https://linux-hardware.org/?probe=ce117380dd) | Feb 14, 2021 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [9862174836](https://linux-hardware.org/?probe=9862174836) | Feb 13, 2021 |
| ASUSTek       | P8H77-V LE                  | [99f3171b76](https://linux-hardware.org/?probe=99f3171b76) | Feb 10, 2021 |
| ASUSTek       | P8H77-V LE                  | [e052a51f58](https://linux-hardware.org/?probe=e052a51f58) | Feb 10, 2021 |
| ASRock        | 970 Extreme4                | [dee973015c](https://linux-hardware.org/?probe=dee973015c) | Feb 09, 2021 |
| ASRock        | X570 Phantom Gaming X       | [c0ada2d30c](https://linux-hardware.org/?probe=c0ada2d30c) | Feb 08, 2021 |
| Gigabyte      | GA-970A-UD3                 | [71a56734c1](https://linux-hardware.org/?probe=71a56734c1) | Feb 07, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [826729feac](https://linux-hardware.org/?probe=826729feac) | Feb 07, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [389456d6b7](https://linux-hardware.org/?probe=389456d6b7) | Feb 06, 2021 |
| ASUSTek       | P7P55D PRO                  | [3e78bc9f2c](https://linux-hardware.org/?probe=3e78bc9f2c) | Feb 06, 2021 |
| ASUSTek       | M3A78-EM                    | [95af098c68](https://linux-hardware.org/?probe=95af098c68) | Feb 05, 2021 |
| HP            | 0A64h                       | [6b5e34333d](https://linux-hardware.org/?probe=6b5e34333d) | Feb 04, 2021 |
| ASRock        | 990FX Extreme3              | [e5ac3cd7e2](https://linux-hardware.org/?probe=e5ac3cd7e2) | Feb 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [47d61a08a0](https://linux-hardware.org/?probe=47d61a08a0) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | [e546964d97](https://linux-hardware.org/?probe=e546964d97) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | [80124b02cf](https://linux-hardware.org/?probe=80124b02cf) | Jan 31, 2021 |
| ASUSTek       | P5G41T-M LX PLUS            | [ef58793cd1](https://linux-hardware.org/?probe=ef58793cd1) | Jan 29, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [897d7d00d7](https://linux-hardware.org/?probe=897d7d00d7) | Jan 27, 2021 |
| AOpen         | D1007 0BB4                  | [8e09b52f79](https://linux-hardware.org/?probe=8e09b52f79) | Jan 24, 2021 |
| AOpen         | D1007 0BB4                  | [73d0723981](https://linux-hardware.org/?probe=73d0723981) | Jan 21, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [d4d4c84bc5](https://linux-hardware.org/?probe=d4d4c84bc5) | Jan 19, 2021 |
| HP            | 844C                        | [f9e65434d6](https://linux-hardware.org/?probe=f9e65434d6) | Jan 16, 2021 |
| ASUSTek       | M5A97 R2.0                  | [0e5edf7f67](https://linux-hardware.org/?probe=0e5edf7f67) | Jan 14, 2021 |
| ASUSTek       | M5A97 R2.0                  | [4d2826d61b](https://linux-hardware.org/?probe=4d2826d61b) | Jan 13, 2021 |
| Dell          | 0Y958C A00                  | [6a52898067](https://linux-hardware.org/?probe=6a52898067) | Jan 12, 2021 |
| MSI           | AMETHYST-M                  | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Dell          | 0YC523                      | [ef04db7b3d](https://linux-hardware.org/?probe=ef04db7b3d) | Jan 04, 2021 |
| MSI           | Z170A GAMING M5             | [fde14ce5dd](https://linux-hardware.org/?probe=fde14ce5dd) | Jan 04, 2021 |
| MSI           | Z170A GAMING M5             | [f120a3b7a1](https://linux-hardware.org/?probe=f120a3b7a1) | Jan 04, 2021 |
| ASUSTek       | Z87-K                       | [aa039f37b7](https://linux-hardware.org/?probe=aa039f37b7) | Dec 30, 2020 |
| Packard Be... | RS740                       | [5ce58f1cfb](https://linux-hardware.org/?probe=5ce58f1cfb) | Dec 30, 2020 |
| MSI           | B360M MORTAR                | [96a4f4f86f](https://linux-hardware.org/?probe=96a4f4f86f) | Dec 29, 2020 |
| MSI           | B360M MORTAR                | [770704b41d](https://linux-hardware.org/?probe=770704b41d) | Dec 29, 2020 |
| ASUSTek       | Z170I PRO GAMING            | [a4ad398189](https://linux-hardware.org/?probe=a4ad398189) | Dec 28, 2020 |
| ASUSTek       | Z87-PRO                     | [38bf55661f](https://linux-hardware.org/?probe=38bf55661f) | Dec 28, 2020 |
| ASUSTek       | Z87-PRO                     | [9c1f8e8a57](https://linux-hardware.org/?probe=9c1f8e8a57) | Dec 28, 2020 |
| Foxconn       | 2AA9                        | [ad51692f6a](https://linux-hardware.org/?probe=ad51692f6a) | Dec 26, 2020 |
| Intel         | D34010WYK H14771-303        | [3a3ce906e2](https://linux-hardware.org/?probe=3a3ce906e2) | Dec 25, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [4b40fc00f6](https://linux-hardware.org/?probe=4b40fc00f6) | Dec 20, 2020 |
| HP            | 1850                        | [a92e22af3c](https://linux-hardware.org/?probe=a92e22af3c) | Dec 19, 2020 |
| ASRock        | G41C-GS                     | [822e9847fc](https://linux-hardware.org/?probe=822e9847fc) | Dec 19, 2020 |
| ASRockRack    | B450D4U-V1L                 | [53bda46668](https://linux-hardware.org/?probe=53bda46668) | Dec 17, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [4e7ff831eb](https://linux-hardware.org/?probe=4e7ff831eb) | Dec 14, 2020 |
| MSI           | MS-7211                     | [d5848092f3](https://linux-hardware.org/?probe=d5848092f3) | Dec 14, 2020 |
| Foxconn       | 2ADA                        | [0b3c20a9d9](https://linux-hardware.org/?probe=0b3c20a9d9) | Dec 12, 2020 |
| ASUSTek       | H110M-C                     | [cde1c20a36](https://linux-hardware.org/?probe=cde1c20a36) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | [1aedfd747c](https://linux-hardware.org/?probe=1aedfd747c) | Dec 12, 2020 |
| Gigabyte      | H370 HD3-CF                 | [16778aa65b](https://linux-hardware.org/?probe=16778aa65b) | Dec 11, 2020 |
| Lenovo        | SDK0E50510 WIN              | [79400c58bc](https://linux-hardware.org/?probe=79400c58bc) | Dec 11, 2020 |
| Gigabyte      | H370 HD3-CF                 | [3167aca45c](https://linux-hardware.org/?probe=3167aca45c) | Dec 10, 2020 |
| HP            | 2AF3                        | [66cb088231](https://linux-hardware.org/?probe=66cb088231) | Dec 10, 2020 |
| HP            | 2AF3                        | [839c9749a0](https://linux-hardware.org/?probe=839c9749a0) | Dec 10, 2020 |
| ASUSTek       | M4A785T-M                   | [44e7dff3d3](https://linux-hardware.org/?probe=44e7dff3d3) | Dec 10, 2020 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [b9e091029f](https://linux-hardware.org/?probe=b9e091029f) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | [84feb3d2f6](https://linux-hardware.org/?probe=84feb3d2f6) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | [92ad61acb2](https://linux-hardware.org/?probe=92ad61acb2) | Dec 10, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e4dc25a528](https://linux-hardware.org/?probe=e4dc25a528) | Dec 09, 2020 |
| Gigabyte      | B360M D3H-CF                | [27f9412b8a](https://linux-hardware.org/?probe=27f9412b8a) | Dec 08, 2020 |
| Acer          | Aspire XC600 v1.0           | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| ASUSTek       | PRIME B550-PLUS             | [0d011c1658](https://linux-hardware.org/?probe=0d011c1658) | Nov 30, 2020 |
| ASUSTek       | PRIME X370-PRO              | [45e6832bd6](https://linux-hardware.org/?probe=45e6832bd6) | Nov 26, 2020 |
| Acer          | Aspire TC-603               | [79605fa1a1](https://linux-hardware.org/?probe=79605fa1a1) | Nov 24, 2020 |
| ASRockRack    | B450D4U-V1L                 | [19c11c3ffd](https://linux-hardware.org/?probe=19c11c3ffd) | Nov 24, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cd25862710](https://linux-hardware.org/?probe=cd25862710) | Nov 20, 2020 |
| HP            | 198E                        | [1c885683dc](https://linux-hardware.org/?probe=1c885683dc) | Nov 19, 2020 |
| ASUSTek       | P5G41T-M LE                 | [e7fe53d106](https://linux-hardware.org/?probe=e7fe53d106) | Nov 18, 2020 |
| HP            | 1998                        | [1346951067](https://linux-hardware.org/?probe=1346951067) | Nov 12, 2020 |
| HP            | 1998                        | [dece9d28a6](https://linux-hardware.org/?probe=dece9d28a6) | Nov 12, 2020 |
| HP            | 1998                        | [00c2c438c0](https://linux-hardware.org/?probe=00c2c438c0) | Nov 11, 2020 |
| HP            | 1998                        | [3772df1169](https://linux-hardware.org/?probe=3772df1169) | Nov 11, 2020 |
| HP            | 1998                        | [7c1b7a3a8f](https://linux-hardware.org/?probe=7c1b7a3a8f) | Nov 11, 2020 |
| MSI           | G41M-P28                    | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Dell          | 0T656F A02                  | [cae149b8a1](https://linux-hardware.org/?probe=cae149b8a1) | Nov 11, 2020 |
| HP            | 1998                        | [e3874c5181](https://linux-hardware.org/?probe=e3874c5181) | Nov 11, 2020 |
| MSI           | G41M-P28                    | [afee9b144d](https://linux-hardware.org/?probe=afee9b144d) | Nov 11, 2020 |
| ASUSTek       | P8H67                       | [58e6f9543d](https://linux-hardware.org/?probe=58e6f9543d) | Nov 10, 2020 |
| ASUSTek       | P8H67                       | [4ac5a781a1](https://linux-hardware.org/?probe=4ac5a781a1) | Nov 10, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [5234189221](https://linux-hardware.org/?probe=5234189221) | Nov 08, 2020 |
| HP            | 1495                        | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| HP            | 1495                        | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| MSI           | Z97M-G43                    | [58cf86104b](https://linux-hardware.org/?probe=58cf86104b) | Nov 03, 2020 |
| MSI           | B450-A PRO MAX              | [b348fef370](https://linux-hardware.org/?probe=b348fef370) | Nov 02, 2020 |
| ASUSTek       | P5KPL-CM                    | [0352b345cb](https://linux-hardware.org/?probe=0352b345cb) | Nov 02, 2020 |
| Pegatron      | NARRA3                      | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [0745eca4eb](https://linux-hardware.org/?probe=0745eca4eb) | Oct 31, 2020 |
| Foxconn       | 2ABF                        | [a4caa7de36](https://linux-hardware.org/?probe=a4caa7de36) | Oct 30, 2020 |
| ASUSTek       | M5A97 R2.0                  | [80424d0c76](https://linux-hardware.org/?probe=80424d0c76) | Oct 30, 2020 |
| ASRock        | B150M-DVS R2.0              | [fe0d972e21](https://linux-hardware.org/?probe=fe0d972e21) | Oct 29, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [1bad9ab1dd](https://linux-hardware.org/?probe=1bad9ab1dd) | Oct 29, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [3f18f3f21e](https://linux-hardware.org/?probe=3f18f3f21e) | Oct 28, 2020 |
| ASUSTek       | P6T                         | [3ac523398e](https://linux-hardware.org/?probe=3ac523398e) | Oct 28, 2020 |
| ASUSTek       | H97M-PLUS                   | [0441a81235](https://linux-hardware.org/?probe=0441a81235) | Oct 27, 2020 |
| Supermicro    | X9SCI/X9SCA                 | [311e5dfe10](https://linux-hardware.org/?probe=311e5dfe10) | Oct 25, 2020 |
| Dell          | 0T656F A02                  | [92ccdd2770](https://linux-hardware.org/?probe=92ccdd2770) | Oct 24, 2020 |
| Gigabyte      | Z170-Gaming K3-CF           | [002d0884a9](https://linux-hardware.org/?probe=002d0884a9) | Oct 22, 2020 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [9d3c97dea2](https://linux-hardware.org/?probe=9d3c97dea2) | Oct 21, 2020 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [4609337b52](https://linux-hardware.org/?probe=4609337b52) | Oct 20, 2020 |
| ASUSTek       | PRIME Z370-P                | [aaeb2157bb](https://linux-hardware.org/?probe=aaeb2157bb) | Oct 19, 2020 |
| Gigabyte      | B550 AORUS PRO              | [2779444bba](https://linux-hardware.org/?probe=2779444bba) | Oct 19, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8892c91b74](https://linux-hardware.org/?probe=8892c91b74) | Oct 19, 2020 |
| ASRock        | J3710-ITX                   | [3f1b610426](https://linux-hardware.org/?probe=3f1b610426) | Oct 18, 2020 |
| Acer          | Aspire XC-605               | [77bfaa4cf4](https://linux-hardware.org/?probe=77bfaa4cf4) | Oct 17, 2020 |
| ASRockRack    | B450D4U-V1L                 | [423121e43d](https://linux-hardware.org/?probe=423121e43d) | Oct 12, 2020 |
| Acer          | WMCP78M                     | [85191c5734](https://linux-hardware.org/?probe=85191c5734) | Oct 07, 2020 |
| ASUSTek       | PRIME Z370-P                | [db2d04c102](https://linux-hardware.org/?probe=db2d04c102) | Oct 07, 2020 |
| ASUSTek       | Maximus VI EXTREME          | [a6995dcd50](https://linux-hardware.org/?probe=a6995dcd50) | Oct 07, 2020 |
| ASUSTek       | Z170M-PLUS                  | [0de2f730e6](https://linux-hardware.org/?probe=0de2f730e6) | Oct 07, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | [fba1eca372](https://linux-hardware.org/?probe=fba1eca372) | Oct 05, 2020 |
| ASUSTek       | P5E                         | [6cb501be5f](https://linux-hardware.org/?probe=6cb501be5f) | Oct 05, 2020 |
| MSI           | 990FXA-GD65                 | [fe2c088ea6](https://linux-hardware.org/?probe=fe2c088ea6) | Oct 03, 2020 |
| Lenovo        | 3098 0B98401 PRO            | [2221632b84](https://linux-hardware.org/?probe=2221632b84) | Oct 03, 2020 |
| MSI           | 990FXA-GD65                 | [e4175eb759](https://linux-hardware.org/?probe=e4175eb759) | Oct 03, 2020 |
| HP            | 3397                        | [3d20bbed7a](https://linux-hardware.org/?probe=3d20bbed7a) | Oct 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [3c907dd84e](https://linux-hardware.org/?probe=3c907dd84e) | Oct 03, 2020 |
| ASUSTek       | H81I-PLUS                   | [3770254bcd](https://linux-hardware.org/?probe=3770254bcd) | Oct 02, 2020 |
| ASRock        | FM2A75 Pro4                 | [a57ba9c332](https://linux-hardware.org/?probe=a57ba9c332) | Sep 29, 2020 |
| ASUSTek       | P8Z68-V GEN3                | [ac4a6958b0](https://linux-hardware.org/?probe=ac4a6958b0) | Sep 29, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [0bd951036d](https://linux-hardware.org/?probe=0bd951036d) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [bfb9828008](https://linux-hardware.org/?probe=bfb9828008) | Sep 28, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | [37b2dd7af9](https://linux-hardware.org/?probe=37b2dd7af9) | Sep 28, 2020 |
| ASUSTek       | PRIME Z390M-PLUS            | [495415d7ad](https://linux-hardware.org/?probe=495415d7ad) | Sep 28, 2020 |
| ASUSTek       | PRIME Z390-A                | [63e778d2be](https://linux-hardware.org/?probe=63e778d2be) | Sep 28, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [9edecf1b35](https://linux-hardware.org/?probe=9edecf1b35) | Sep 28, 2020 |
| Intel         | D946GZIS AAD66165-301       | [f8df50faeb](https://linux-hardware.org/?probe=f8df50faeb) | Sep 27, 2020 |
| MSI           | Z77A-G45                    | [28a219f7b8](https://linux-hardware.org/?probe=28a219f7b8) | Sep 23, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | [333f34e356](https://linux-hardware.org/?probe=333f34e356) | Sep 20, 2020 |
| ASUSTek       | M4A78T-E                    | [6fe22c6007](https://linux-hardware.org/?probe=6fe22c6007) | Sep 20, 2020 |
| ASUSTek       | KRPA-U16 Series             | [588c3eb0ba](https://linux-hardware.org/?probe=588c3eb0ba) | Sep 18, 2020 |
| ASUSTek       | Z10PA-U8 Series             | [f60b4c96e0](https://linux-hardware.org/?probe=f60b4c96e0) | Sep 18, 2020 |
| ASUSTek       | Z10PA-U8 Series             | [bfc568f6d8](https://linux-hardware.org/?probe=bfc568f6d8) | Sep 18, 2020 |
| MSI           | B350M PRO-VDH               | [16827d150f](https://linux-hardware.org/?probe=16827d150f) | Sep 18, 2020 |
| MSI           | B350M PRO-VDH               | [10a678dfa9](https://linux-hardware.org/?probe=10a678dfa9) | Sep 18, 2020 |
| MSI           | B350M PRO-VDH               | [b1cc6e2b49](https://linux-hardware.org/?probe=b1cc6e2b49) | Sep 18, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0cf8ee1ae8](https://linux-hardware.org/?probe=0cf8ee1ae8) | Sep 16, 2020 |
| ASRock        | B450M Pro4                  | [9df4d6c8b1](https://linux-hardware.org/?probe=9df4d6c8b1) | Sep 15, 2020 |
| ASUSTek       | Z170-A                      | [81cb15062d](https://linux-hardware.org/?probe=81cb15062d) | Sep 14, 2020 |
| ASRock        | Z87 Extreme6                | [8e26b54de5](https://linux-hardware.org/?probe=8e26b54de5) | Sep 12, 2020 |
| Gigabyte      | X570 AORUS PRO              | [086d35ff5c](https://linux-hardware.org/?probe=086d35ff5c) | Sep 12, 2020 |
| Intel         | D946GZIS AAD66165-301       | [517c09218d](https://linux-hardware.org/?probe=517c09218d) | Sep 10, 2020 |
| Foxconn       | 2ADA                        | [5a32535dcd](https://linux-hardware.org/?probe=5a32535dcd) | Sep 10, 2020 |
| ASUSTek       | X99-PRO/USB                 | [231f0afb76](https://linux-hardware.org/?probe=231f0afb76) | Sep 09, 2020 |
| MSI           | B450I GAMING PLUS AC        | [0b87386e6a](https://linux-hardware.org/?probe=0b87386e6a) | Sep 09, 2020 |
| ASRock        | B450M-HDV R4.0              | [cf465b6ceb](https://linux-hardware.org/?probe=cf465b6ceb) | Sep 05, 2020 |
| Gigabyte      | F2A88XN-WIFI                | [342b54e7a0](https://linux-hardware.org/?probe=342b54e7a0) | Sep 04, 2020 |
| MSI           | B450I GAMING PLUS AC        | [d3510ce4e2](https://linux-hardware.org/?probe=d3510ce4e2) | Sep 04, 2020 |
| ASRock        | B450M-HDV R4.0              | [34b84c17b7](https://linux-hardware.org/?probe=34b84c17b7) | Sep 04, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [900f200c57](https://linux-hardware.org/?probe=900f200c57) | Sep 03, 2020 |
| ASUSTek       | M5A97 R2.0                  | [b511e8b52a](https://linux-hardware.org/?probe=b511e8b52a) | Aug 31, 2020 |
| Intel         | D946GZIS AAD66165-301       | [10e5c82714](https://linux-hardware.org/?probe=10e5c82714) | Aug 31, 2020 |
| MSI           | B450M MORTAR MAX            | [d24e39c945](https://linux-hardware.org/?probe=d24e39c945) | Aug 29, 2020 |
| MSI           | B450M MORTAR MAX            | [2a246d5ea8](https://linux-hardware.org/?probe=2a246d5ea8) | Aug 29, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [7640a283c8](https://linux-hardware.org/?probe=7640a283c8) | Aug 28, 2020 |
| HP            | 2AF3                        | [61d714ef58](https://linux-hardware.org/?probe=61d714ef58) | Aug 27, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [7152566435](https://linux-hardware.org/?probe=7152566435) | Aug 23, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [422ee2d231](https://linux-hardware.org/?probe=422ee2d231) | Aug 21, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0230526040](https://linux-hardware.org/?probe=0230526040) | Aug 20, 2020 |
| HP            | 0A64h                       | [223ff53d77](https://linux-hardware.org/?probe=223ff53d77) | Aug 18, 2020 |
| ASUSTek       | PRIME X570-PRO              | [36e63c4f0b](https://linux-hardware.org/?probe=36e63c4f0b) | Aug 18, 2020 |
| ASUSTek       | M4A78T-E                    | [8345dd66f0](https://linux-hardware.org/?probe=8345dd66f0) | Aug 17, 2020 |
| ASUSTek       | Z170M-PLUS                  | [7831468225](https://linux-hardware.org/?probe=7831468225) | Aug 14, 2020 |
| ASUSTek       | Z170M-PLUS                  | [302127e58b](https://linux-hardware.org/?probe=302127e58b) | Aug 14, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [01515127a6](https://linux-hardware.org/?probe=01515127a6) | Aug 11, 2020 |
| MSI           | B450I GAMING PLUS AC        | [d6a59a4350](https://linux-hardware.org/?probe=d6a59a4350) | Aug 10, 2020 |
| ASRock        | Z87 Extreme6                | [9ab8243174](https://linux-hardware.org/?probe=9ab8243174) | Aug 07, 2020 |
| ASUSTek       | H81I-PLUS                   | [7259e07174](https://linux-hardware.org/?probe=7259e07174) | Aug 07, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [ddda943f96](https://linux-hardware.org/?probe=ddda943f96) | Aug 07, 2020 |
| HP            | 198E                        | [321cdddb29](https://linux-hardware.org/?probe=321cdddb29) | Aug 05, 2020 |
| Intel         | D946GZIS AAD66165-301       | [0f40a312c4](https://linux-hardware.org/?probe=0f40a312c4) | Aug 03, 2020 |
| ASRock        | Z87 Extreme6                | [0ab11e1615](https://linux-hardware.org/?probe=0ab11e1615) | Jul 30, 2020 |
| ASUSTek       | Z170M-PLUS                  | [74d141c870](https://linux-hardware.org/?probe=74d141c870) | Jul 30, 2020 |
| ASRock        | B450M Pro4                  | [a05ebd9a3d](https://linux-hardware.org/?probe=a05ebd9a3d) | Jul 29, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [9f29db1cee](https://linux-hardware.org/?probe=9f29db1cee) | Jul 28, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [a68b2400b4](https://linux-hardware.org/?probe=a68b2400b4) | Jul 27, 2020 |
| ASUSTek       | M4A785D-M PRO               | [dcf2273c01](https://linux-hardware.org/?probe=dcf2273c01) | Jul 26, 2020 |
| ASRock        | B450M Pro4                  | [022e082270](https://linux-hardware.org/?probe=022e082270) | Jul 25, 2020 |
| ASRock        | B450M Pro4                  | [6595773d87](https://linux-hardware.org/?probe=6595773d87) | Jul 23, 2020 |
| MSI           | MS-7388                     | [95f9f16df0](https://linux-hardware.org/?probe=95f9f16df0) | Jul 23, 2020 |
| ASUSTek       | P5E                         | [bcea9f0625](https://linux-hardware.org/?probe=bcea9f0625) | Jul 14, 2020 |
| MSI           | B450M MORTAR MAX            | [8b21c297c5](https://linux-hardware.org/?probe=8b21c297c5) | Jul 03, 2020 |
| Pegatron      | 2A99                        | [a2db447eb2](https://linux-hardware.org/?probe=a2db447eb2) | Jul 01, 2020 |
| ASUSTek       | Maximus VII GENE            | [6209226e93](https://linux-hardware.org/?probe=6209226e93) | Jun 23, 2020 |
| Pegatron      | NARRA3                      | [5ba05ac282](https://linux-hardware.org/?probe=5ba05ac282) | Jun 23, 2020 |
| Pegatron      | NARRA3                      | [458687c748](https://linux-hardware.org/?probe=458687c748) | Jun 23, 2020 |
| MSI           | X570-A PRO                  | [8ea0db2339](https://linux-hardware.org/?probe=8ea0db2339) | Jun 15, 2020 |
| MSI           | MS-7211                     | [76c18a99c5](https://linux-hardware.org/?probe=76c18a99c5) | Jun 14, 2020 |
| MSI           | MS-7211                     | [3bad7f0625](https://linux-hardware.org/?probe=3bad7f0625) | Jun 14, 2020 |
| Acer          | RS780HVF                    | [83b78f2956](https://linux-hardware.org/?probe=83b78f2956) | Jun 12, 2020 |
| HP            | 1850                        | [2cc6a94d41](https://linux-hardware.org/?probe=2cc6a94d41) | Jun 11, 2020 |
| HP            | 844C                        | [9ca2de8699](https://linux-hardware.org/?probe=9ca2de8699) | Jun 04, 2020 |
| HP            | 8596                        | [8a317cad1f](https://linux-hardware.org/?probe=8a317cad1f) | Jun 04, 2020 |
| ASRock        | X399 Taichi                 | [9c9844febe](https://linux-hardware.org/?probe=9c9844febe) | Jun 03, 2020 |
| ASUSTek       | VM42                        | [0c45d392cd](https://linux-hardware.org/?probe=0c45d392cd) | Jun 01, 2020 |
| ASUSTek       | P8P67 DELUXE                | [e66cc02c0f](https://linux-hardware.org/?probe=e66cc02c0f) | May 26, 2020 |
| ASRock        | X570 Taichi                 | [0a9aa77797](https://linux-hardware.org/?probe=0a9aa77797) | May 25, 2020 |
| ASRock        | 970 Pro3 R2.0               | [6ac29193c7](https://linux-hardware.org/?probe=6ac29193c7) | May 22, 2020 |
| ASUSTek       | PRIME X570-PRO              | [dac4e0e6ee](https://linux-hardware.org/?probe=dac4e0e6ee) | May 09, 2020 |
| ASUSTek       | Z97-E                       | [64ac218015](https://linux-hardware.org/?probe=64ac218015) | May 04, 2020 |
| ASUSTek       | Z97-E                       | [110eb7afe6](https://linux-hardware.org/?probe=110eb7afe6) | May 04, 2020 |
| HP            | 2AFB                        | [ad8b92b3c2](https://linux-hardware.org/?probe=ad8b92b3c2) | Apr 29, 2020 |
| Pegatron      | 2A72h                       | [e91fa26092](https://linux-hardware.org/?probe=e91fa26092) | Apr 29, 2020 |
| Pegatron      | 2A72h                       | [ba42a81415](https://linux-hardware.org/?probe=ba42a81415) | Apr 28, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [3cef1ebb25](https://linux-hardware.org/?probe=3cef1ebb25) | Apr 23, 2020 |
| ASRock        | X570M Pro4                  | [84162d8ef3](https://linux-hardware.org/?probe=84162d8ef3) | Apr 21, 2020 |
| Gigabyte      | X570 GAMING X               | [b6ddb425af](https://linux-hardware.org/?probe=b6ddb425af) | Apr 12, 2020 |
| ASUSTek       | Z97-P                       | [1e40acf175](https://linux-hardware.org/?probe=1e40acf175) | Apr 09, 2020 |
| ASUSTek       | P8Z77-V LX                  | [893f6857b2](https://linux-hardware.org/?probe=893f6857b2) | Apr 04, 2020 |
| ASUSTek       | H87I-PLUS                   | [0f8a987ceb](https://linux-hardware.org/?probe=0f8a987ceb) | Apr 03, 2020 |
| ASUSTek       | P8Z77-V LX                  | [ec1375a9f8](https://linux-hardware.org/?probe=ec1375a9f8) | Apr 02, 2020 |
| ASUSTek       | CM1855                      | [3b029acc71](https://linux-hardware.org/?probe=3b029acc71) | Apr 02, 2020 |
| Gigabyte      | MFHM17P-00                  | [456a21854c](https://linux-hardware.org/?probe=456a21854c) | Mar 29, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [d925844b9e](https://linux-hardware.org/?probe=d925844b9e) | Mar 25, 2020 |
| ASUSTek       | Rampage IV FORMULA          | [4303c3c3a0](https://linux-hardware.org/?probe=4303c3c3a0) | Mar 24, 2020 |
| ASUSTek       | Rampage IV FORMULA          | [572afffcf7](https://linux-hardware.org/?probe=572afffcf7) | Mar 24, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [165309707f](https://linux-hardware.org/?probe=165309707f) | Mar 24, 2020 |
| ASUSTek       | PRIME B450M-A               | [e973706460](https://linux-hardware.org/?probe=e973706460) | Mar 24, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cdc5018f7b](https://linux-hardware.org/?probe=cdc5018f7b) | Mar 20, 2020 |
| HP            | 0A64h                       | [e525355c31](https://linux-hardware.org/?probe=e525355c31) | Mar 15, 2020 |
| ASUSTek       | PRIME Z370-P                | [5b782ed08d](https://linux-hardware.org/?probe=5b782ed08d) | Mar 15, 2020 |
| ASUSTek       | Maximus VII GENE            | [222a13e152](https://linux-hardware.org/?probe=222a13e152) | Mar 12, 2020 |
| ASUSTek       | Maximus VII GENE            | [f4da492647](https://linux-hardware.org/?probe=f4da492647) | Mar 11, 2020 |
| Gigabyte      | B360M D3H-CF                | [ec4c81e7d9](https://linux-hardware.org/?probe=ec4c81e7d9) | Mar 06, 2020 |
| ASUSTek       | M4A88TD-M EVO               | [1276eb9896](https://linux-hardware.org/?probe=1276eb9896) | Feb 29, 2020 |
| ASUSTek       | Z170-P D3                   | [0dc81f0e45](https://linux-hardware.org/?probe=0dc81f0e45) | Feb 26, 2020 |
| ASUSTek       | G21CN                       | [45598f0644](https://linux-hardware.org/?probe=45598f0644) | Feb 24, 2020 |
| ASUSTek       | PRIME Z370-P                | [5a72aef554](https://linux-hardware.org/?probe=5a72aef554) | Feb 22, 2020 |
| ASRock        | Z97 Extreme4                | [60038b2000](https://linux-hardware.org/?probe=60038b2000) | Feb 21, 2020 |
| ASUSTek       | M5A78L LE                   | [ba36629619](https://linux-hardware.org/?probe=ba36629619) | Feb 15, 2020 |
| ASRock        | Z77 Pro3                    | [698b8aaaed](https://linux-hardware.org/?probe=698b8aaaed) | Feb 09, 2020 |
| ASUSTek       | P9X79 DELUXE                | [c37f970528](https://linux-hardware.org/?probe=c37f970528) | Feb 01, 2020 |
| Gigabyte      | Z97P-D3                     | [f151961dd1](https://linux-hardware.org/?probe=f151961dd1) | Feb 01, 2020 |
| ASUSTek       | M4A78T-E                    | [6059173c99](https://linux-hardware.org/?probe=6059173c99) | Jan 28, 2020 |
| MSI           | B450M PRO-M2                | [04b3edf01b](https://linux-hardware.org/?probe=04b3edf01b) | Jan 25, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4e9e3904fb](https://linux-hardware.org/?probe=4e9e3904fb) | Jan 25, 2020 |
| ASUSTek       | PRIME B350M-A               | [efe2412a0a](https://linux-hardware.org/?probe=efe2412a0a) | Jan 25, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [6eaa1a038c](https://linux-hardware.org/?probe=6eaa1a038c) | Jan 24, 2020 |
| Gigabyte      | X170-WS ECC-CF              | [c284714094](https://linux-hardware.org/?probe=c284714094) | Jan 24, 2020 |
| ASUSTek       | PRIME Z270-A                | [cda0e88379](https://linux-hardware.org/?probe=cda0e88379) | Jan 15, 2020 |
| Intel         | DP55WG AAE57269-408         | [b1606ddfdf](https://linux-hardware.org/?probe=b1606ddfdf) | Jan 14, 2020 |
| ASRock        | X399 Taichi                 | [5ab003017d](https://linux-hardware.org/?probe=5ab003017d) | Jan 09, 2020 |
| ASUSTek       | PRIME Z270-A                | [80297eeeb4](https://linux-hardware.org/?probe=80297eeeb4) | Jan 04, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [ad44824354](https://linux-hardware.org/?probe=ad44824354) | Jan 02, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [a853544a4d](https://linux-hardware.org/?probe=a853544a4d) | Jan 02, 2020 |
| ASUSTek       | M5A78L LE                   | [6c0bf83741](https://linux-hardware.org/?probe=6c0bf83741) | Jan 01, 2020 |
| ASRock        | G31M-GS                     | [857343b33e](https://linux-hardware.org/?probe=857343b33e) | Dec 30, 2019 |
| ASUSTek       | Z170-A                      | [562af84691](https://linux-hardware.org/?probe=562af84691) | Dec 16, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [3973a7cef2](https://linux-hardware.org/?probe=3973a7cef2) | Dec 12, 2019 |
| Lenovo        | ThinkCentre M90p 3652A3G    | [3877a5d3bb](https://linux-hardware.org/?probe=3877a5d3bb) | Dec 09, 2019 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [8e2b5b679e](https://linux-hardware.org/?probe=8e2b5b679e) | Dec 05, 2019 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [b9ff361521](https://linux-hardware.org/?probe=b9ff361521) | Dec 03, 2019 |
| ASUSTek       | P8Z68-V                     | [1f44759168](https://linux-hardware.org/?probe=1f44759168) | Dec 02, 2019 |
| HP            | 1998                        | [ee17d70239](https://linux-hardware.org/?probe=ee17d70239) | Nov 28, 2019 |
| ASUSTek       | P8Z77-V LX                  | [8f2d04de46](https://linux-hardware.org/?probe=8f2d04de46) | Nov 28, 2019 |
| HP            | 1998                        | [78481ffcd4](https://linux-hardware.org/?probe=78481ffcd4) | Nov 17, 2019 |
| Foxconn       | A76ML-K 30                  | [cd69cd71e1](https://linux-hardware.org/?probe=cd69cd71e1) | Nov 12, 2019 |
| Gigabyte      | 970A-DS3P                   | [870d0fe48e](https://linux-hardware.org/?probe=870d0fe48e) | Oct 28, 2019 |
| ASUSTek       | H97M-E                      | [9d2304c49f](https://linux-hardware.org/?probe=9d2304c49f) | Oct 27, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [4dc787cc15](https://linux-hardware.org/?probe=4dc787cc15) | Oct 27, 2019 |
| Gigabyte      | B450 AORUS M                | [b05e61e4d9](https://linux-hardware.org/?probe=b05e61e4d9) | Oct 25, 2019 |
| ASRock        | B450 Pro4                   | [dcfc0b3327](https://linux-hardware.org/?probe=dcfc0b3327) | Oct 23, 2019 |
| ASRock        | B450 Pro4                   | [a29a11899f](https://linux-hardware.org/?probe=a29a11899f) | Oct 23, 2019 |
| ASRock        | B450 Pro4                   | [1740915405](https://linux-hardware.org/?probe=1740915405) | Oct 23, 2019 |
| ASRock        | B450 Pro4                   | [ba98645988](https://linux-hardware.org/?probe=ba98645988) | Oct 23, 2019 |
| ASUSTek       | Z87-K                       | [a2c50a6a82](https://linux-hardware.org/?probe=a2c50a6a82) | Oct 22, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | [afd255688a](https://linux-hardware.org/?probe=afd255688a) | Oct 20, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | [b194fb82fe](https://linux-hardware.org/?probe=b194fb82fe) | Oct 20, 2019 |
| ASUSTek       | PRIME H270-PLUS             | [0656361c4f](https://linux-hardware.org/?probe=0656361c4f) | Oct 19, 2019 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [3f141d1c9d](https://linux-hardware.org/?probe=3f141d1c9d) | Oct 05, 2019 |
| HP            | 0A64h                       | [b3aec62eb9](https://linux-hardware.org/?probe=b3aec62eb9) | Oct 01, 2019 |
| MSI           | Z370 SLI PLUS               | [d6f9a54a5e](https://linux-hardware.org/?probe=d6f9a54a5e) | Sep 04, 2019 |
| Packard Be... | MCP73T-AD                   | [897bde5f15](https://linux-hardware.org/?probe=897bde5f15) | Aug 22, 2019 |
| ASUSTek       | P8H77-I                     | [9a5e6f850c](https://linux-hardware.org/?probe=9a5e6f850c) | Aug 16, 2019 |
| MSI           | Z370 SLI PLUS               | [9d169b5017](https://linux-hardware.org/?probe=9d169b5017) | Aug 14, 2019 |
| ASUSTek       | P8H77-I                     | [3ecc7afdb6](https://linux-hardware.org/?probe=3ecc7afdb6) | Aug 03, 2019 |
| ASUSTek       | TUF B450-PLUS GAMING        | [537d11b224](https://linux-hardware.org/?probe=537d11b224) | Jul 26, 2019 |
| Gigabyte      | P35-DS3                     | [b79ee752b4](https://linux-hardware.org/?probe=b79ee752b4) | Jul 15, 2019 |
| MSI           | IONA                        | [a585eaef35](https://linux-hardware.org/?probe=a585eaef35) | Jul 13, 2019 |
| ASUSTek       | M5A97 R2.0                  | [e2e30d9fb0](https://linux-hardware.org/?probe=e2e30d9fb0) | Jul 09, 2019 |
| ASUSTek       | M5A97 R2.0                  | [a6b185ca6f](https://linux-hardware.org/?probe=a6b185ca6f) | Jul 09, 2019 |
| ASUSTek       | M5A97 R2.0                  | [4ee3c4c06c](https://linux-hardware.org/?probe=4ee3c4c06c) | Jul 09, 2019 |
| HP            | 1497                        | [5ce732df30](https://linux-hardware.org/?probe=5ce732df30) | Jun 21, 2019 |
| ASUSTek       | M4A78                       | [f95aec52e4](https://linux-hardware.org/?probe=f95aec52e4) | Jun 15, 2019 |
| ASUSTek       | PRIME H270-PLUS             | [347d0dbf57](https://linux-hardware.org/?probe=347d0dbf57) | May 29, 2019 |
| ASUSTek       | M4A87TD/USB3                | [a55280bb16](https://linux-hardware.org/?probe=a55280bb16) | May 25, 2019 |
| ASUSTek       | M5A78L LE                   | [8d3a77af71](https://linux-hardware.org/?probe=8d3a77af71) | May 24, 2019 |
| MSI           | 760GM-E51                   | [b23ed61a74](https://linux-hardware.org/?probe=b23ed61a74) | May 13, 2019 |
| Foxconn       | 2ABF                        | [80e41dc351](https://linux-hardware.org/?probe=80e41dc351) | May 10, 2019 |
| MSI           | 760GM-E51                   | [c77558abf8](https://linux-hardware.org/?probe=c77558abf8) | May 01, 2019 |
| Gigabyte      | G1.Sniper Z87               | [8ce5db772c](https://linux-hardware.org/?probe=8ce5db772c) | Apr 17, 2019 |
| Intel         | DG33TL AAD89517-700         | [90ba96cb73](https://linux-hardware.org/?probe=90ba96cb73) | Apr 16, 2019 |
| Intel         | DG33TL AAD89517-700         | [b151450467](https://linux-hardware.org/?probe=b151450467) | Apr 15, 2019 |
| ASRock        | X470 Gaming-ITX/ac          | [1c1b87dea4](https://linux-hardware.org/?probe=1c1b87dea4) | Apr 13, 2019 |
| ASUSTek       | P6T                         | [4db2f20573](https://linux-hardware.org/?probe=4db2f20573) | Apr 07, 2019 |
| ASRock        | AB350M Pro4                 | [855fdd6eac](https://linux-hardware.org/?probe=855fdd6eac) | Mar 19, 2019 |
| ASRock        | Z87 Extreme6                | [96aaa39135](https://linux-hardware.org/?probe=96aaa39135) | Mar 18, 2019 |
| HP            | 1497                        | [357589623a](https://linux-hardware.org/?probe=357589623a) | Feb 23, 2019 |
| ASUSTek       | P6T                         | [5040f012a9](https://linux-hardware.org/?probe=5040f012a9) | Feb 10, 2019 |
| ASUSTek       | P6T                         | [79dfc022fd](https://linux-hardware.org/?probe=79dfc022fd) | Feb 09, 2019 |
| ASRock        | ALiveNF6G-GLAN              | [a89f20ae20](https://linux-hardware.org/?probe=a89f20ae20) | Feb 08, 2019 |
| AOpen         | nMCP7ALPx-DE R1.04 Oct.0... | [b778a6096a](https://linux-hardware.org/?probe=b778a6096a) | Jan 30, 2019 |
| ASRock        | ALiveNF6G-GLAN              | [5ab2a6ed4a](https://linux-hardware.org/?probe=5ab2a6ed4a) | Jan 25, 2019 |
| ASUSTek       | P5LD2EB-DHS                 | [ece39839eb](https://linux-hardware.org/?probe=ece39839eb) | Jan 05, 2019 |
| Intel         | DH61DL AAG14066-202         | [8e77a793e3](https://linux-hardware.org/?probe=8e77a793e3) | Dec 19, 2018 |
| ASUSTek       | M5A78L-M/USB3               | [82325163f4](https://linux-hardware.org/?probe=82325163f4) | Dec 12, 2018 |
| ASUSTek       | M5A78L-M/USB3               | [b699ce4e30](https://linux-hardware.org/?probe=b699ce4e30) | Dec 12, 2018 |
| ASUSTek       | P7H55-M PRO                 | [79918271ca](https://linux-hardware.org/?probe=79918271ca) | Dec 12, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Finland/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 77       | 10.07%  |
| Ubuntu 22.04       | 44       | 5.75%   |
| Ubuntu 18.04       | 40       | 5.23%   |
| Arch Rolling       | 33       | 4.31%   |
| OpenMandriva 23.01 | 30       | 3.92%   |
| Pop!_OS 22.04      | 22       | 2.88%   |
| OpenMandriva 4.2   | 18       | 2.35%   |
| Arch               | 15       | 1.96%   |
| OpenMandriva 23.03 | 14       | 1.83%   |
| Linux Mint 20.1    | 14       | 1.83%   |
| Debian 11          | 14       | 1.83%   |
| Gentoo 2.7         | 12       | 1.57%   |
| Manjaro            | 11       | 1.44%   |
| Linux Mint 21.2    | 11       | 1.44%   |
| OpenMandriva 4.3   | 10       | 1.31%   |
| Linux Mint 20      | 10       | 1.31%   |
| Fedora 36          | 10       | 1.31%   |
| ArcoLinux Rolling  | 10       | 1.31%   |
| Zorin 16           | 9        | 1.18%   |
| Ubuntu 20.10       | 9        | 1.18%   |
| Linux Mint 20.3    | 9        | 1.18%   |
| Xubuntu 18.04      | 8        | 1.05%   |
| Pop!_OS 21.04      | 8        | 1.05%   |
| Debian 12          | 8        | 1.05%   |
| Xubuntu 20.04      | 7        | 0.92%   |
| Ubuntu 23.04       | 7        | 0.92%   |
| Pop!_OS 20.04      | 7        | 0.92%   |
| Linux Mint 19.3    | 7        | 0.92%   |
| Kubuntu 22.04      | 7        | 0.92%   |
| Debian Testing     | 7        | 0.92%   |
| Debian 10          | 7        | 0.92%   |
| Ubuntu 21.10       | 6        | 0.78%   |
| Ubuntu 21.04       | 6        | 0.78%   |
| Ubuntu 19.10       | 6        | 0.78%   |
| Linux Mint 21.1    | 6        | 0.78%   |
| KDE neon 20.04     | 6        | 0.78%   |
| Fedora 32          | 6        | 0.78%   |
| Ubuntu 19.04       | 5        | 0.65%   |
| ROSA R10           | 5        | 0.65%   |
| Pop!_OS 20.10      | 5        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 195      | 27.58%  |
| OpenMandriva  | 81       | 11.46%  |
| Linux Mint    | 56       | 7.92%   |
| Arch          | 48       | 6.79%   |
| Pop!_OS       | 43       | 6.08%   |
| Fedora        | 39       | 5.52%   |
| Debian        | 38       | 5.37%   |
| Manjaro       | 33       | 4.67%   |
| Gentoo        | 20       | 2.83%   |
| Xubuntu       | 18       | 2.55%   |
| Kubuntu       | 14       | 1.98%   |
| openSUSE      | 11       | 1.56%   |
| ArcoLinux     | 11       | 1.56%   |
| Zorin         | 10       | 1.41%   |
| ROSA          | 10       | 1.41%   |
| Lubuntu       | 10       | 1.41%   |
| KDE neon      | 10       | 1.41%   |
| Ubuntu MATE   | 6        | 0.85%   |
| CentOS        | 6        | 0.85%   |
| MX            | 5        | 0.71%   |
| EndeavourOS   | 4        | 0.57%   |
| Elementary    | 4        | 0.57%   |
| Ubuntu Unity  | 3        | 0.42%   |
| Peppermint    | 3        | 0.42%   |
| Nobara        | 3        | 0.42%   |
| BlackPanther  | 3        | 0.42%   |
| Void Linux    | 2        | 0.28%   |
| UbuntuDDE     | 2        | 0.28%   |
| NixOS         | 2        | 0.28%   |
| LMDE          | 2        | 0.28%   |
| Clear Linux   | 2        | 0.28%   |
| Artix         | 2        | 0.28%   |
| Alpine        | 2        | 0.28%   |
| Solus         | 1        | 0.14%   |
| Rocky Linux   | 1        | 0.14%   |
| RHEL          | 1        | 0.14%   |
| Parabola      | 1        | 0.14%   |
| Oracle Linux  | 1        | 0.14%   |
| Garuda Linux  | 1        | 0.14%   |
| Crystal Linux | 1        | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 6.1.1-desktop-1omv2290          | 29       | 3.48%   |
| 5.10.14-desktop-1omv4002        | 18       | 2.16%   |
| 5.4.0-42-generic                | 13       | 1.56%   |
| 6.2.6-desktop-1omv2390          | 12       | 1.44%   |
| 5.4.0-47-generic                | 9        | 1.08%   |
| 5.16.7-desktop-1omv4003         | 9        | 1.08%   |
| 5.8.0-44-generic                | 6        | 0.72%   |
| 5.4.0-65-generic                | 6        | 0.72%   |
| 5.4.0-52-generic                | 6        | 0.72%   |
| 5.4.0-48-generic                | 6        | 0.72%   |
| 6.2.0-26-generic                | 5        | 0.6%    |
| 5.8.0-41-generic                | 5        | 0.6%    |
| 5.4.0-56-generic                | 5        | 0.6%    |
| 5.4.0-53-generic                | 5        | 0.6%    |
| 5.15.0-60-generic               | 5        | 0.6%    |
| 5.15.0-58-generic               | 5        | 0.6%    |
| 5.15.0-46-generic               | 5        | 0.6%    |
| 5.15.0-27-generic               | 5        | 0.6%    |
| 5.13.0-7620-generic             | 5        | 0.6%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5        | 0.6%    |
| 6.6.6-76060606-generic          | 4        | 0.48%   |
| 6.0.12-76060006-generic         | 4        | 0.48%   |
| 5.8.0-7630-generic              | 4        | 0.48%   |
| 5.4.0-66-generic                | 4        | 0.48%   |
| 5.4.0-58-generic                | 4        | 0.48%   |
| 5.4.0-54-generic                | 4        | 0.48%   |
| 5.4.0-45-generic                | 4        | 0.48%   |
| 5.19.0-76051900-generic         | 4        | 0.48%   |
| 5.15.28-1-MANJARO               | 4        | 0.48%   |
| 5.15.0-91-generic               | 4        | 0.48%   |
| 5.15.0-52-generic               | 4        | 0.48%   |
| 5.15.0-48-generic               | 4        | 0.48%   |
| 5.13.0-30-generic               | 4        | 0.48%   |
| 4.15.0-29-generic               | 4        | 0.48%   |
| 6.6.2-desktop-1omv2390          | 3        | 0.36%   |
| 6.3.5-desktop-3omv2390          | 3        | 0.36%   |
| 6.2.6-76060206-generic          | 3        | 0.36%   |
| 6.2.0-36-generic                | 3        | 0.36%   |
| 6.1.0-9-amd64                   | 3        | 0.36%   |
| 5.8.0-49-generic                | 3        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 111      | 13.96%  |
| 5.15.0  | 71       | 8.93%   |
| 5.8.0   | 38       | 4.78%   |
| 4.15.0  | 35       | 4.4%    |
| 6.1.1   | 29       | 3.65%   |
| 5.13.0  | 22       | 2.77%   |
| 5.11.0  | 22       | 2.77%   |
| 6.2.0   | 21       | 2.64%   |
| 5.19.0  | 19       | 2.39%   |
| 5.10.14 | 19       | 2.39%   |
| 6.2.6   | 15       | 1.89%   |
| 5.3.0   | 13       | 1.64%   |
| 5.10.0  | 12       | 1.51%   |
| 5.0.0   | 12       | 1.51%   |
| 4.19.0  | 10       | 1.26%   |
| 5.16.7  | 9        | 1.13%   |
| 4.18.0  | 9        | 1.13%   |
| 6.0.12  | 7        | 0.88%   |
| 6.1.0   | 6        | 0.75%   |
| 6.6.2   | 5        | 0.63%   |
| 4.9.60  | 5        | 0.63%   |
| 6.6.7   | 4        | 0.5%    |
| 6.6.6   | 4        | 0.5%    |
| 5.17.5  | 4        | 0.5%    |
| 5.15.28 | 4        | 0.5%    |
| 5.14.14 | 4        | 0.5%    |
| 5.14.0  | 4        | 0.5%    |
| 5.11.2  | 4        | 0.5%    |
| 6.5.5   | 3        | 0.38%   |
| 6.5.4   | 3        | 0.38%   |
| 6.5.0   | 3        | 0.38%   |
| 6.4.8   | 3        | 0.38%   |
| 6.3.5   | 3        | 0.38%   |
| 6.1.4   | 3        | 0.38%   |
| 6.0.7   | 3        | 0.38%   |
| 6.0.5   | 3        | 0.38%   |
| 6.0.11  | 3        | 0.38%   |
| 5.3.18  | 3        | 0.38%   |
| 5.17.3  | 3        | 0.38%   |
| 5.12.4  | 3        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 122      | 15.62%  |
| 5.15    | 98       | 12.55%  |
| 5.8     | 50       | 6.4%    |
| 6.1     | 49       | 6.27%   |
| 6.2     | 48       | 6.15%   |
| 5.10    | 48       | 6.15%   |
| 4.15    | 36       | 4.61%   |
| 5.11    | 32       | 4.1%    |
| 5.13    | 29       | 3.71%   |
| 5.19    | 26       | 3.33%   |
| 6.0     | 24       | 3.07%   |
| 5.3     | 19       | 2.43%   |
| 5.16    | 18       | 2.3%    |
| 6.6     | 16       | 2.05%   |
| 5.17    | 16       | 2.05%   |
| 6.4     | 14       | 1.79%   |
| 5.0     | 13       | 1.66%   |
| 4.19    | 13       | 1.66%   |
| 4.18    | 13       | 1.66%   |
| 6.5     | 12       | 1.54%   |
| 5.14    | 11       | 1.41%   |
| 6.3     | 10       | 1.28%   |
| 5.9     | 9        | 1.15%   |
| 5.7     | 9        | 1.15%   |
| 5.18    | 9        | 1.15%   |
| 5.12    | 8        | 1.02%   |
| 5.6     | 6        | 0.77%   |
| 4.9     | 6        | 0.77%   |
| 5.5     | 5        | 0.64%   |
| 3.10    | 3        | 0.38%   |
| 4.1     | 2        | 0.26%   |
| 6.7     | 1        | 0.13%   |
| 5.2     | 1        | 0.13%   |
| 5.1     | 1        | 0.13%   |
| 4.4     | 1        | 0.13%   |
| 4.20    | 1        | 0.13%   |
| 4.13    | 1        | 0.13%   |
| 4.12    | 1        | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 672      | 98.68%  |
| i686   | 9        | 1.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 260      | 36.52%  |
| KDE5             | 169      | 23.74%  |
| Unknown          | 98       | 13.76%  |
| XFCE             | 45       | 6.32%   |
| X-Cinnamon       | 44       | 6.18%   |
| MATE             | 26       | 3.65%   |
| KDE              | 17       | 2.39%   |
| LXQt             | 11       | 1.54%   |
| KDE4             | 4        | 0.56%   |
| GNOME Flashback  | 4        | 0.56%   |
| Cinnamon         | 4        | 0.56%   |
| Unity            | 3        | 0.42%   |
| Pantheon         | 3        | 0.42%   |
| LXDE             | 3        | 0.42%   |
| lightdm-xsession | 3        | 0.42%   |
| i3               | 3        | 0.42%   |
| Budgie           | 3        | 0.42%   |
| sway             | 2        | 0.28%   |
| dwm              | 2        | 0.28%   |
| Deepin           | 2        | 0.28%   |
| bspwm            | 2        | 0.28%   |
| sway:Unity       | 1        | 0.14%   |
| onyx:GNOME       | 1        | 0.14%   |
| Hyprland         | 1        | 0.14%   |
| GNOME Classic    | 1        | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 521      | 73.8%   |
| Wayland | 108      | 15.3%   |
| Tty     | 43       | 6.09%   |
| Unknown | 33       | 4.67%   |
| Web     | 1        | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 321      | 44.58%  |
| SDDM    | 156      | 21.67%  |
| GDM3    | 75       | 10.42%  |
| GDM     | 72       | 10%     |
| LightDM | 63       | 8.75%   |
| TDM     | 27       | 3.75%   |
| KDM     | 5        | 0.69%   |
| SLiM    | 1        | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Desktops | Percent |
|-----------------|----------|---------|
| en_US           | 317      | 45.09%  |
| fi_FI           | 224      | 31.86%  |
| Unknown         | 68       | 9.67%   |
| en_GB           | 38       | 5.41%   |
| C               | 13       | 1.85%   |
| ru_RU           | 8        | 1.14%   |
| en_FI           | 7        | 1%      |
| sv_FI           | 4        | 0.57%   |
| sv_SE           | 3        | 0.43%   |
| fr_FR           | 3        | 0.43%   |
| en_DK           | 3        | 0.43%   |
| en_SE           | 2        | 0.28%   |
| en_IE           | 2        | 0.28%   |
| C.UTF8          | 2        | 0.28%   |
| POSIX           | 1        | 0.14%   |
| pl_PL           | 1        | 0.14%   |
| it_IT           | 1        | 0.14%   |
| ia_FR           | 1        | 0.14%   |
| fr_CA           | 1        | 0.14%   |
| fi_FI@euro.UTF- | 1        | 0.14%   |
| en_us.utf-8     | 1        | 0.14%   |
| en_CA           | 1        | 0.14%   |
| af_ZA           | 1        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 391      | 55.7%   |
| EFI  | 311      | 44.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 491      | 69.45%  |
| Btrfs   | 79       | 11.17%  |
| Overlay | 66       | 9.34%   |
| Tmpfs   | 23       | 3.25%   |
| Unknown | 21       | 2.97%   |
| Xfs     | 16       | 2.26%   |
| Zfs     | 7        | 0.99%   |
| F2fs    | 2        | 0.28%   |
| Ext3    | 1        | 0.14%   |
| Ext2    | 1        | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 319      | 45.12%  |
| Unknown | 299      | 42.29%  |
| MBR     | 89       | 12.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 531      | 76.29%  |
| Yes       | 165      | 23.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 455      | 65.37%  |
| Yes       | 241      | 34.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 259      | 38.09%  |
| Hewlett-Packard                      | 80       | 11.76%  |
| MSI                                  | 68       | 10%     |
| Gigabyte Technology                  | 67       | 9.85%   |
| ASRock                               | 60       | 8.82%   |
| Lenovo                               | 23       | 3.38%   |
| Dell                                 | 21       | 3.09%   |
| Acer                                 | 21       | 3.09%   |
| Fujitsu                              | 20       | 2.94%   |
| Intel                                | 12       | 1.76%   |
| Foxconn                              | 10       | 1.47%   |
| Pegatron                             | 9        | 1.32%   |
| Fujitsu Siemens                      | 4        | 0.59%   |
| Supermicro                           | 3        | 0.44%   |
| Packard Bell                         | 3        | 0.44%   |
| AOpen                                | 3        | 0.44%   |
| Medion                               | 2        | 0.29%   |
| ASRockRack                           | 2        | 0.29%   |
| ABIT                                 | 2        | 0.29%   |
| WeiBu                                | 1        | 0.15%   |
| SZMZ                                 | 1        | 0.15%   |
| Shuttle                              | 1        | 0.15%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.15%   |
| Inventec                             | 1        | 0.15%   |
| IceWhale Technology                  | 1        | 0.15%   |
| ECS                                  | 1        | 0.15%   |
| Cisco                                | 1        | 0.15%   |
| BESSTAR Tech                         | 1        | 0.15%   |
| Apple                                | 1        | 0.15%   |
| Unknown                              | 1        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 26       | 3.82%   |
| HP EliteDesk 800 G1 SFF          | 9        | 1.32%   |
| ASUS TUF Gaming X570-PLUS        | 7        | 1.03%   |
| ASUS ROG STRIX B550-F GAMING     | 7        | 1.03%   |
| MSI MS-7C37                      | 6        | 0.88%   |
| MSI MS-7A38                      | 5        | 0.74%   |
| ASUS Pro WS 565-ACE              | 5        | 0.74%   |
| ASUS PRIME X370-PRO              | 5        | 0.74%   |
| ASUS M5A97 R2.0                  | 5        | 0.74%   |
| HP Compaq 8200 Elite SFF PC      | 4        | 0.59%   |
| Gigabyte X570 AORUS ELITE        | 4        | 0.59%   |
| ASUS TUF B450-PLUS GAMING        | 4        | 0.59%   |
| ASUS PRIME B450-PLUS             | 4        | 0.59%   |
| ASUS PRIME B350-PLUS             | 4        | 0.59%   |
| MSI MS-7B89                      | 3        | 0.44%   |
| MSI MS-7B49                      | 3        | 0.44%   |
| MSI MS-7B48                      | 3        | 0.44%   |
| Fujitsu ESPRIMO E910             | 3        | 0.44%   |
| Fujitsu D3401-H2 S26361-D3401-H2 | 3        | 0.44%   |
| Dell OptiPlex 780                | 3        | 0.44%   |
| ASUS TUF Gaming B550-PLUS        | 3        | 0.44%   |
| ASUS ROG STRIX Z370-F GAMING     | 3        | 0.44%   |
| ASUS ROG STRIX B550-I GAMING     | 3        | 0.44%   |
| ASUS ROG STRIX B450-F GAMING     | 3        | 0.44%   |
| ASUS PRIME Z270-P                | 3        | 0.44%   |
| ASUS PRIME Z270-A                | 3        | 0.44%   |
| ASUS PRIME X470-PRO              | 3        | 0.44%   |
| ASUS PRIME B450M-A               | 3        | 0.44%   |
| ASUS M5A97 LE R2.0               | 3        | 0.44%   |
| ASUS M5A97 EVO R2.0              | 3        | 0.44%   |
| ASUS M5A78L-M/USB3               | 3        | 0.44%   |
| ASUS M4A78T-E                    | 3        | 0.44%   |
| ASRock X570 Taichi               | 3        | 0.44%   |
| ASRock B450M-HDV R4.0            | 3        | 0.44%   |
| Acer Aspire X3300                | 3        | 0.44%   |
| MSI MS-7C95                      | 2        | 0.29%   |
| MSI MS-7C91                      | 2        | 0.29%   |
| MSI MS-7C84                      | 2        | 0.29%   |
| MSI MS-7C56                      | 2        | 0.29%   |
| MSI MS-7B86                      | 2        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 56       | 8.24%   |
| ASUS ROG                | 36       | 5.29%   |
| HP Compaq               | 27       | 3.97%   |
| ASUS All                | 26       | 3.82%   |
| ASUS TUF                | 20       | 2.94%   |
| Dell OptiPlex           | 17       | 2.5%    |
| HP EliteDesk            | 16       | 2.35%   |
| Lenovo ThinkCentre      | 15       | 2.21%   |
| Acer Aspire             | 14       | 2.06%   |
| Fujitsu ESPRIMO         | 12       | 1.76%   |
| ASUS M5A97              | 12       | 1.76%   |
| HP ProDesk              | 8        | 1.18%   |
| Gigabyte X570           | 8        | 1.18%   |
| MSI MS-7C37             | 6        | 0.88%   |
| HP Pavilion             | 6        | 0.88%   |
| ASUS Pro                | 6        | 0.88%   |
| MSI MS-7A38             | 5        | 0.74%   |
| ASRock X570             | 5        | 0.74%   |
| Acer Predator           | 5        | 0.74%   |
| Gigabyte B550           | 4        | 0.59%   |
| ASUS P7P55D             | 4        | 0.59%   |
| ASRock B450M-HDV        | 4        | 0.59%   |
| ASRock 970              | 4        | 0.59%   |
| MSI MS-7B89             | 3        | 0.44%   |
| MSI MS-7B49             | 3        | 0.44%   |
| MSI MS-7B48             | 3        | 0.44%   |
| Lenovo IdeaCentre       | 3        | 0.44%   |
| HP Z240                 | 3        | 0.44%   |
| Fujitsu Siemens ESPRIMO | 3        | 0.44%   |
| Fujitsu D3401-H2        | 3        | 0.44%   |
| Dell Precision          | 3        | 0.44%   |
| ASUS P8Z77-V            | 3        | 0.44%   |
| ASUS P8Z68-V            | 3        | 0.44%   |
| ASUS P8P67              | 3        | 0.44%   |
| ASUS P6T                | 3        | 0.44%   |
| ASUS M5A78L-M           | 3        | 0.44%   |
| ASUS M4A78T-E           | 3        | 0.44%   |
| ASRock B450             | 3        | 0.44%   |
| Packard Bell IMEDIA     | 2        | 0.29%   |
| MSI MS-7C95             | 2        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 76       | 11.18%  |
| 2018 | 71       | 10.44%  |
| 2017 | 60       | 8.82%   |
| 2013 | 59       | 8.68%   |
| 2019 | 54       | 7.94%   |
| 2020 | 53       | 7.79%   |
| 2009 | 46       | 6.76%   |
| 2011 | 40       | 5.88%   |
| 2015 | 35       | 5.15%   |
| 2010 | 32       | 4.71%   |
| 2014 | 31       | 4.56%   |
| 2016 | 28       | 4.12%   |
| 2008 | 28       | 4.12%   |
| 2021 | 17       | 2.5%    |
| 2007 | 17       | 2.5%    |
| 2022 | 16       | 2.35%   |
| 2006 | 8        | 1.18%   |
| 2023 | 4        | 0.59%   |
| 2005 | 3        | 0.44%   |
| 2004 | 2        | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 680      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 667      | 97.51%  |
| Enabled  | 17       | 2.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 680      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 195      | 27.98%  |
| 32.01-64.0      | 120      | 17.22%  |
| 8.01-16.0       | 116      | 16.64%  |
| 3.01-4.0        | 90       | 12.91%  |
| 4.01-8.0        | 88       | 12.63%  |
| 64.01-256.0     | 42       | 6.03%   |
| 24.01-32.0      | 23       | 3.3%    |
| 1.01-2.0        | 14       | 2.01%   |
| 2.01-3.0        | 6        | 0.86%   |
| More than 256.0 | 1        | 0.14%   |
| 0.51-1.0        | 1        | 0.14%   |
| 0.01-0.5        | 1        | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 249      | 32.81%  |
| 2.01-3.0    | 157      | 20.69%  |
| 4.01-8.0    | 126      | 16.6%   |
| 3.01-4.0    | 94       | 12.38%  |
| 0.51-1.0    | 53       | 6.98%   |
| 8.01-16.0   | 49       | 6.46%   |
| 16.01-24.0  | 10       | 1.32%   |
| 0.01-0.5    | 8        | 1.05%   |
| 32.01-64.0  | 5        | 0.66%   |
| 24.01-32.0  | 5        | 0.66%   |
| 0           | 2        | 0.26%   |
| 64.01-256.0 | 1        | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 231      | 32.22%  |
| 2      | 190      | 26.5%   |
| 3      | 133      | 18.55%  |
| 4      | 61       | 8.51%   |
| 5      | 43       | 6%      |
| 6      | 19       | 2.65%   |
| 7      | 11       | 1.53%   |
| 0      | 10       | 1.39%   |
| 9      | 7        | 0.98%   |
| 8      | 6        | 0.84%   |
| 10     | 4        | 0.56%   |
| 23     | 1        | 0.14%   |
| 11     | 1        | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 364      | 52.53%  |
| Yes       | 329      | 47.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 676      | 99.41%  |
| No        | 4        | 0.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 411      | 59.83%  |
| Yes       | 276      | 40.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 474      | 68.8%   |
| Yes       | 215      | 31.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Finland | 680      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Helsinki     | 279      | 37.75%  |
| Tampere      | 69       | 9.34%   |
| Turku        | 49       | 6.63%   |
| Oulu         | 44       | 5.95%   |
| Espoo        | 44       | 5.95%   |
| Vantaa       | 28       | 3.79%   |
| Kuopio       | 20       | 2.71%   |
| Jyväskylä  | 17       | 2.3%    |
| Lahti        | 15       | 2.03%   |
| Tuusula      | 11       | 1.49%   |
| Vaasa        | 10       | 1.35%   |
| Joensuu      | 10       | 1.35%   |
| Raisio       | 9        | 1.22%   |
| Hyvinkaeae   | 8        | 1.08%   |
| Raahe        | 6        | 0.81%   |
| Salo         | 5        | 0.68%   |
| Pori         | 5        | 0.68%   |
| Seinäjoki   | 4        | 0.54%   |
| Kotka        | 4        | 0.54%   |
| Hämeenlinna | 4        | 0.54%   |
| Uusikaupunki | 3        | 0.41%   |
| Lempäälä  | 3        | 0.41%   |
| Lappeenranta | 3        | 0.41%   |
| Kouvola      | 3        | 0.41%   |
| Kerava       | 3        | 0.41%   |
| Järvenpää | 3        | 0.41%   |
| Hanko        | 3        | 0.41%   |
| Tupos        | 2        | 0.27%   |
| Tenala       | 2        | 0.27%   |
| Tarvasjoki   | 2        | 0.27%   |
| Solv         | 2        | 0.27%   |
| Rovaniemi    | 2        | 0.27%   |
| Rauma        | 2        | 0.27%   |
| Porlammi     | 2        | 0.27%   |
| Nokia        | 2        | 0.27%   |
| Maenttae     | 2        | 0.27%   |
| Lohja        | 2        | 0.27%   |
| Lieto        | 2        | 0.27%   |
| Klaukkala    | 2        | 0.27%   |
| Karis        | 2        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 276      | 492    | 21.13%  |
| WDC                         | 248      | 466    | 18.99%  |
| Seagate                     | 206      | 364    | 15.77%  |
| Kingston                    | 182      | 279    | 13.94%  |
| Toshiba                     | 52       | 106    | 3.98%   |
| Crucial                     | 41       | 51     | 3.14%   |
| Intel                       | 38       | 56     | 2.91%   |
| Hitachi                     | 35       | 47     | 2.68%   |
| SanDisk                     | 33       | 40     | 2.53%   |
| A-DATA Technology           | 20       | 27     | 1.53%   |
| Maxtor                      | 13       | 20     | 1%      |
| Verbatim                    | 11       | 20     | 0.84%   |
| PNY                         | 11       | 13     | 0.84%   |
| Micron Technology           | 11       | 18     | 0.84%   |
| Phison                      | 10       | 10     | 0.77%   |
| Corsair                     | 10       | 12     | 0.77%   |
| Unknown                     | 9        | 21     | 0.69%   |
| OCZ                         | 9        | 11     | 0.69%   |
| HGST                        | 9        | 20     | 0.69%   |
| Transcend                   | 8        | 11     | 0.61%   |
| SK hynix                    | 8        | 9      | 0.61%   |
| Phison Electronics          | 5        | 6      | 0.38%   |
| Kingston Technology Company | 5        | 6      | 0.38%   |
| Intenso                     | 5        | 8      | 0.38%   |
| XPG                         | 3        | 5      | 0.23%   |
| SPCC                        | 3        | 3      | 0.23%   |
| Micron/Crucial Technology   | 3        | 4      | 0.23%   |
| LITEONIT                    | 3        | 3      | 0.23%   |
| Fujitsu                     | 3        | 3      | 0.23%   |
| ADATA Technology            | 3        | 4      | 0.23%   |
| USB3.0                      | 2        | 2      | 0.15%   |
| Plextor                     | 2        | 2      | 0.15%   |
| Patriot                     | 2        | 5      | 0.15%   |
| OCZ-VERTEX3                 | 2        | 2      | 0.15%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.15%   |
| LITEON                      | 2        | 2      | 0.15%   |
| Lexar                       | 2        | 2      | 0.15%   |
| HUAWEI                      | 2        | 2      | 0.15%   |
| Hewlett-Packard             | 2        | 3      | 0.15%   |
| XrayDisk                    | 1        | 1      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 32       | 2.02%   |
| Samsung SSD 850 EVO 250GB                          | 30       | 1.89%   |
| Kingston SA400S37480G 480GB SSD                    | 24       | 1.51%   |
| Kingston SA400S37120G 120GB SSD                    | 21       | 1.32%   |
| Samsung SSD 850 EVO 500GB                          | 20       | 1.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 17       | 1.07%   |
| Seagate ST500DM002-1BD142 500GB                    | 14       | 0.88%   |
| Samsung SSD 860 EVO 500GB                          | 14       | 0.88%   |
| Samsung NVMe SSD Drive 500GB                       | 14       | 0.88%   |
| Kingston SV300S37A120G 120GB SSD                   | 14       | 0.88%   |
| Kingston SHFS37A120G 120GB SSD                     | 13       | 0.82%   |
| Toshiba DT01ACA300 3TB                             | 12       | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB                     | 12       | 0.76%   |
| Samsung HD103SJ 1TB                                | 12       | 0.76%   |
| Seagate ST2000DM008-2FR102 2TB                     | 11       | 0.69%   |
| Samsung SSD 860 EVO 1TB                            | 11       | 0.69%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 10       | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB                     | 10       | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 10       | 0.63%   |
| Kingston SV300S37A240G 240GB SSD                   | 10       | 0.63%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 9        | 0.57%   |
| WDC WD40EFRX-68WT0N0 4TB                           | 8        | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB                           | 8        | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB                     | 8        | 0.5%    |
| Samsung SSD 960 EVO 500GB                          | 8        | 0.5%    |
| Samsung HD501LJ 500GB                              | 8        | 0.5%    |
| Kingston SA400S37960G 960GB SSD                    | 8        | 0.5%    |
| Toshiba DT01ACA100 1TB                             | 7        | 0.44%   |
| Seagate ST31000528AS 1TB                           | 7        | 0.44%   |
| Samsung SSD 850 PRO 256GB                          | 7        | 0.44%   |
| Samsung SSD 840 EVO 120GB                          | 7        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                        | 7        | 0.44%   |
| Verbatim Vi550 S3 SSD 512GB                        | 6        | 0.38%   |
| Seagate ST31000524AS 1TB                           | 6        | 0.38%   |
| Seagate ST2000DM001-1ER164 2TB                     | 6        | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 6        | 0.38%   |
| Samsung SSD 980 1TB                                | 6        | 0.38%   |
| Samsung SSD 860 EVO 250GB                          | 6        | 0.38%   |
| Samsung NVMe SSD Drive 1TB                         | 6        | 0.38%   |
| PNY CS900 120GB SSD                                | 6        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 220      | 403    | 38.33%  |
| Seagate             | 198      | 351    | 34.49%  |
| Samsung Electronics | 48       | 74     | 8.36%   |
| Toshiba             | 43       | 81     | 7.49%   |
| Hitachi             | 35       | 47     | 6.1%    |
| Maxtor              | 13       | 20     | 2.26%   |
| HGST                | 9        | 20     | 1.57%   |
| Fujitsu             | 3        | 3      | 0.52%   |
| Unknown             | 2        | 2      | 0.35%   |
| StoreJet            | 1        | 1      | 0.17%   |
| Hewlett-Packard     | 1        | 1      | 0.17%   |
| External            | 1        | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 164      | 243    | 31.6%   |
| Kingston            | 160      | 244    | 30.83%  |
| Crucial             | 39       | 48     | 7.51%   |
| WDC                 | 35       | 50     | 6.74%   |
| Intel               | 12       | 26     | 2.31%   |
| Verbatim            | 11       | 20     | 2.12%   |
| SanDisk             | 11       | 11     | 2.12%   |
| Micron Technology   | 11       | 18     | 2.12%   |
| A-DATA Technology   | 11       | 15     | 2.12%   |
| PNY                 | 9        | 11     | 1.73%   |
| OCZ                 | 9        | 11     | 1.73%   |
| Transcend           | 8        | 11     | 1.54%   |
| Corsair             | 6        | 7      | 1.16%   |
| Toshiba             | 4        | 11     | 0.77%   |
| Intenso             | 4        | 7      | 0.77%   |
| SPCC                | 3        | 3      | 0.58%   |
| LITEONIT            | 3        | 3      | 0.58%   |
| USB3.0              | 2        | 2      | 0.39%   |
| Plextor             | 2        | 2      | 0.39%   |
| Patriot             | 2        | 5      | 0.39%   |
| OCZ-VERTEX3         | 2        | 2      | 0.39%   |
| LITEON              | 2        | 2      | 0.39%   |
| Unknown             | 1        | 1      | 0.19%   |
| TSA                 | 1        | 1      | 0.19%   |
| sobetter            | 1        | 1      | 0.19%   |
| Seagate             | 1        | 1      | 0.19%   |
| OCZ-VERTEX          | 1        | 1      | 0.19%   |
| Netac               | 1        | 1      | 0.19%   |
| Hewlett-Packard     | 1        | 2      | 0.19%   |
| China               | 1        | 1      | 0.19%   |
| Unknown             | 1        | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 427      | 1004   | 39.61%  |
| SSD     | 402      | 762    | 37.29%  |
| NVMe    | 228      | 373    | 21.15%  |
| Unknown | 19       | 33     | 1.76%   |
| MMC     | 2        | 2      | 0.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 603      | 1717   | 68.6%   |
| NVMe | 228      | 373    | 25.94%  |
| SAS  | 46       | 82     | 5.23%   |
| MMC  | 2        | 2      | 0.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 464      | 927    | 49.05%  |
| 0.51-1.0   | 261      | 397    | 27.59%  |
| 1.01-2.0   | 95       | 159    | 10.04%  |
| 3.01-4.0   | 48       | 117    | 5.07%   |
| 2.01-3.0   | 38       | 82     | 4.02%   |
| 4.01-10.0  | 35       | 78     | 3.7%    |
| 10.01-20.0 | 5        | 6      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 163      | 22.45%  |
| 501-1000       | 105      | 14.46%  |
| 251-500        | 102      | 14.05%  |
| More than 3000 | 91       | 12.53%  |
| 1001-2000      | 71       | 9.78%   |
| 1-20           | 58       | 7.99%   |
| 2001-3000      | 49       | 6.75%   |
| Unknown        | 41       | 5.65%   |
| 51-100         | 33       | 4.55%   |
| 21-50          | 13       | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 245      | 33.02%  |
| 21-50          | 84       | 11.32%  |
| 101-250        | 69       | 9.3%    |
| 501-1000       | 69       | 9.3%    |
| 51-100         | 67       | 9.03%   |
| 251-500        | 59       | 7.95%   |
| 1001-2000      | 43       | 5.8%    |
| Unknown        | 41       | 5.53%   |
| More than 3000 | 38       | 5.12%   |
| 2001-3000      | 27       | 3.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB                       | 4        | 6      | 3.7%    |
| Samsung Electronics HD103SJ 1TB                | 3        | 4      | 2.78%   |
| Micron Technology MTFDDAK512MAM-1K1 512GB SSD  | 3        | 5      | 2.78%   |
| Kingston SHFS37A120G 120GB SSD                 | 3        | 4      | 2.78%   |
| WDC WD10EARS-22Y5B1 1TB                        | 2        | 3      | 1.85%   |
| USB3.0 Super Speed 500GB SSD                   | 2        | 2      | 1.85%   |
| Toshiba DT01ACA100 1TB                         | 2        | 3      | 1.85%   |
| Seagate ST3250318AS 250GB                      | 2        | 2      | 1.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2        | 3      | 1.85%   |
| Samsung Electronics SSD 980 1TB                | 2        | 2      | 1.85%   |
| Samsung Electronics SSD 850 EVO 1TB            | 2        | 2      | 1.85%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD | 2        | 4      | 1.85%   |
| Maxtor 7Y250M0 256GB                           | 2        | 2      | 1.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1        | 1      | 0.93%   |
| WDC WDS120G2G0A-00JH30 120GB SSD               | 1        | 1      | 0.93%   |
| WDC WD6400AAKS-07A7B0 640GB                    | 1        | 1      | 0.93%   |
| WDC WD50EZRZ-32RWYB1 5TB                       | 1        | 1      | 0.93%   |
| WDC WD5000ABPS-01ZZB0 500GB                    | 1        | 1      | 0.93%   |
| WDC WD5000AAKX-60U6AA0 500GB                   | 1        | 1      | 0.93%   |
| WDC WD5000AAKX-00ERMA0 500GB                   | 1        | 1      | 0.93%   |
| WDC WD5000AAKS-22A7B0 500GB                    | 1        | 1      | 0.93%   |
| WDC WD3200YS-01PGB0 320GB                      | 1        | 1      | 0.93%   |
| WDC WD3200BEVT-22ZCT0 320GB                    | 1        | 1      | 0.93%   |
| WDC WD3200AAKS-00L9A0 320GB                    | 1        | 1      | 0.93%   |
| WDC WD3200AAJS-60Z0A0 320GB                    | 1        | 1      | 0.93%   |
| WDC WD3200AAJS-00RYA0 320GB                    | 1        | 1      | 0.93%   |
| WDC WD30EFRX-68EUZN0 3TB                       | 1        | 1      | 0.93%   |
| WDC WD2500AAJS-00V4A0 250GB                    | 1        | 1      | 0.93%   |
| WDC WD20EARS-00MVWB0 2TB                       | 1        | 1      | 0.93%   |
| WDC WD2002FAEX-007BA0 2TB                      | 1        | 1      | 0.93%   |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1        | 1      | 0.93%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1        | 1      | 0.93%   |
| WDC WD10EADX-22TDHB0 1TB                       | 1        | 1      | 0.93%   |
| WDC WD10EADS-22M2B0 1TB                        | 1        | 1      | 0.93%   |
| WDC WD1001FALS-41Y6A1 1TB                      | 1        | 1      | 0.93%   |
| Toshiba MQ04ABF100 1TB                         | 1        | 1      | 0.93%   |
| Toshiba HDWQ140 4TB                            | 1        | 1      | 0.93%   |
| Toshiba HDWA120 2TB                            | 1        | 1      | 0.93%   |
| SPCC Solid State Disk 240GB                    | 1        | 1      | 0.93%   |
| Seagate ST8000DM004-2CX188 8TB                 | 1        | 1      | 0.93%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 31     | 25.71%  |
| Seagate             | 23       | 25     | 21.9%   |
| Samsung Electronics | 14       | 16     | 13.33%  |
| Kingston            | 11       | 12     | 10.48%  |
| Toshiba             | 5        | 6      | 4.76%   |
| Micron Technology   | 5        | 9      | 4.76%   |
| Hitachi             | 5        | 6      | 4.76%   |
| Maxtor              | 4        | 4      | 3.81%   |
| USB3.0              | 2        | 2      | 1.9%    |
| Intel               | 2        | 2      | 1.9%    |
| Corsair             | 2        | 2      | 1.9%    |
| SPCC                | 1        | 1      | 0.95%   |
| PNY                 | 1        | 1      | 0.95%   |
| LITEONIT            | 1        | 1      | 0.95%   |
| HGST                | 1        | 1      | 0.95%   |
| A-DATA Technology   | 1        | 1      | 0.95%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 25       | 29     | 36.76%  |
| Seagate             | 23       | 25     | 33.82%  |
| Toshiba             | 5        | 6      | 7.35%   |
| Samsung Electronics | 5        | 6      | 7.35%   |
| Hitachi             | 5        | 6      | 7.35%   |
| Maxtor              | 4        | 4      | 5.88%   |
| HGST                | 1        | 1      | 1.47%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 66       | 77     | 63.46%  |
| SSD  | 31       | 36     | 29.81%  |
| NVMe | 7        | 7      | 6.73%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3250318AS 250GB         | 1        | 1      | 50%     |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 356      | 1106   | 45.52%  |
| Works    | 323      | 946    | 41.3%   |
| Malfunc  | 101      | 120    | 12.92%  |
| Failed   | 2        | 2      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 402      | 38.95%  |
| AMD                          | 260      | 25.19%  |
| Samsung Electronics          | 114      | 11.05%  |
| ASMedia Technology           | 40       | 3.88%   |
| SanDisk                      | 33       | 3.2%    |
| Kingston Technology Company  | 30       | 2.91%   |
| JMicron Technology           | 30       | 2.91%   |
| Phison Electronics           | 21       | 2.03%   |
| Nvidia                       | 21       | 2.03%   |
| Marvell Technology Group     | 17       | 1.65%   |
| ADATA Technology             | 15       | 1.45%   |
| VIA Technologies             | 8        | 0.78%   |
| Toshiba America Info Systems | 7        | 0.68%   |
| SK hynix                     | 7        | 0.68%   |
| Micron/Crucial Technology    | 6        | 0.58%   |
| LSI Logic / Symbios Logic    | 5        | 0.48%   |
| Seagate Technology           | 4        | 0.39%   |
| Realtek Semiconductor        | 3        | 0.29%   |
| Broadcom / LSI               | 3        | 0.29%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.19%   |
| Silicon Motion               | 1        | 0.1%    |
| Promise Technology           | 1        | 0.1%    |
| Hosin Global Electronics     | 1        | 0.1%    |
| Adaptec                      | 1        | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 135      | 10.53%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 58       | 4.52%   |
| AMD 400 Series Chipset SATA Controller                                         | 53       | 4.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 49       | 3.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 47       | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 40       | 3.12%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 38       | 2.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 37       | 2.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 36       | 2.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 36       | 2.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 34       | 2.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 32       | 2.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 28       | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 25       | 1.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 22       | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 22       | 1.72%   |
| AMD 300 Series Chipset SATA Controller                                         | 22       | 1.72%   |
| Intel SATA Controller [RAID mode]                                              | 20       | 1.56%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 18       | 1.4%    |
| JMicron JMB363 SATA/IDE Controller                                             | 15       | 1.17%   |
| Intel SSD 660P Series                                                          | 14       | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 14       | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 14       | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 14       | 1.09%   |
| Nvidia MCP61 SATA Controller                                                   | 13       | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 13       | 1.01%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 13       | 1.01%   |
| Phison E12 NVMe Controller                                                     | 12       | 0.94%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 10       | 0.78%   |
| Nvidia MCP61 IDE                                                               | 9        | 0.7%    |
| AMD 600 Series Chipset SATA Controller                                         | 9        | 0.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8        | 0.62%   |
| JMicron JMB368 IDE controller                                                  | 8        | 0.62%   |
| AMD X370 Series Chipset SATA Controller                                        | 8        | 0.62%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7        | 0.55%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 7        | 0.55%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 6        | 0.47%   |
| JMicron JMB362 SATA Controller                                                 | 6        | 0.47%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 6        | 0.47%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 6        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 586      | 58.25%  |
| NVMe | 232      | 23.06%  |
| IDE  | 148      | 14.71%  |
| RAID | 31       | 3.08%   |
| SAS  | 7        | 0.7%    |
| SCSI | 2        | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 398      | 58.53%  |
| AMD    | 282      | 41.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 21       | 3.07%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 16       | 2.34%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 12       | 1.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 11       | 1.61%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 10       | 1.46%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 9        | 1.32%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 9        | 1.32%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 9        | 1.32%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 9        | 1.32%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 8        | 1.17%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 8        | 1.17%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 8        | 1.17%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 8        | 1.17%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 8        | 1.17%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 1.17%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 7        | 1.02%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 7        | 1.02%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 7        | 1.02%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 6        | 0.88%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 6        | 0.88%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 0.88%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 6        | 0.88%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 6        | 0.88%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 0.88%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 6        | 0.88%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 6        | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 0.73%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 5        | 0.73%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 5        | 0.73%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 5        | 0.73%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 5        | 0.73%   |
| AMD Phenom II X4 965 Processor              | 5        | 0.73%   |
| AMD FX-6300 Six-Core Processor              | 5        | 0.73%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 0.58%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 0.58%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 4        | 0.58%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 4        | 0.58%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 4        | 0.58%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 4        | 0.58%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 4        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 130      | 19.06%  |
| Intel Core i7           | 99       | 14.52%  |
| AMD Ryzen 5             | 71       | 10.41%  |
| AMD Ryzen 7             | 60       | 8.8%    |
| Intel Core i3           | 41       | 6.01%   |
| AMD Ryzen 9             | 34       | 4.99%   |
| Intel Xeon              | 30       | 4.4%    |
| AMD FX                  | 27       | 3.96%   |
| Intel Core 2 Duo        | 19       | 2.79%   |
| Intel Pentium           | 17       | 2.49%   |
| Intel Celeron           | 17       | 2.49%   |
| AMD Athlon II X2        | 13       | 1.91%   |
| Other                   | 12       | 1.76%   |
| AMD Phenom II X4        | 12       | 1.76%   |
| Intel Core 2 Quad       | 11       | 1.61%   |
| AMD Athlon 64 X2        | 11       | 1.61%   |
| Intel Pentium Dual-Core | 8        | 1.17%   |
| AMD Ryzen 3             | 7        | 1.03%   |
| Intel Core i9           | 5        | 0.73%   |
| AMD Phenom              | 5        | 0.73%   |
| Intel Pentium 4         | 4        | 0.59%   |
| Intel Core 2            | 4        | 0.59%   |
| AMD Ryzen Threadripper  | 4        | 0.59%   |
| AMD Phenom II X6        | 4        | 0.59%   |
| AMD Ryzen 7 PRO         | 3        | 0.44%   |
| AMD Athlon II X4        | 3        | 0.44%   |
| AMD Athlon              | 3        | 0.44%   |
| AMD A10                 | 3        | 0.44%   |
| Intel Atom              | 2        | 0.29%   |
| AMD Sempron             | 2        | 0.29%   |
| AMD G                   | 2        | 0.29%   |
| AMD E1                  | 2        | 0.29%   |
| AMD Athlon Dual Core    | 2        | 0.29%   |
| AMD A6                  | 2        | 0.29%   |
| AMD A4                  | 2        | 0.29%   |
| Intel Pentium Dual      | 1        | 0.15%   |
| Intel Genuine           | 1        | 0.15%   |
| AMD Turion II Neo       | 1        | 0.15%   |
| AMD PRO A10             | 1        | 0.15%   |
| AMD Phenom II X3        | 1        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 270      | 39.65%  |
| 2      | 143      | 21%     |
| 6      | 101      | 14.83%  |
| 8      | 82       | 12.04%  |
| 12     | 25       | 3.67%   |
| 1      | 17       | 2.5%    |
| 16     | 16       | 2.35%   |
| 3      | 14       | 2.06%   |
| 14     | 5        | 0.73%   |
| 10     | 4        | 0.59%   |
| 36     | 1        | 0.15%   |
| 32     | 1        | 0.15%   |
| 20     | 1        | 0.15%   |
| 18     | 1        | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 673      | 98.97%  |
| 2      | 6        | 0.88%   |
| 0      | 1        | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 391      | 57.33%  |
| 1      | 291      | 42.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 671      | 98.39%  |
| Unknown        | 9        | 1.32%   |
| 32-bit         | 2        | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 212      | 29.82%  |
| 0x306c3    | 43       | 6.05%   |
| 0x306a9    | 39       | 5.49%   |
| 0x506e3    | 34       | 4.78%   |
| 0x1067a    | 28       | 3.94%   |
| 0x206a7    | 27       | 3.8%    |
| 0x08701021 | 26       | 3.66%   |
| 0x0800820d | 20       | 2.81%   |
| 0x906ea    | 15       | 2.11%   |
| 0x0a201016 | 15       | 2.11%   |
| 0x08701013 | 15       | 2.11%   |
| 0x06000852 | 14       | 1.97%   |
| 0x010000c8 | 14       | 1.97%   |
| 0x906e9    | 12       | 1.69%   |
| 0x906eb    | 8        | 1.13%   |
| 0x08001137 | 8        | 1.13%   |
| 0x0a601203 | 7        | 0.98%   |
| 0x0a201009 | 7        | 0.98%   |
| 0x906ec    | 6        | 0.84%   |
| 0x20655    | 6        | 0.84%   |
| 0x20652    | 6        | 0.84%   |
| 0x106e5    | 6        | 0.84%   |
| 0x08001138 | 6        | 0.84%   |
| 0x106a5    | 5        | 0.7%    |
| 0x08701030 | 5        | 0.7%    |
| 0x010000db | 5        | 0.7%    |
| 0xf41      | 4        | 0.56%   |
| 0x6fd      | 4        | 0.56%   |
| 0x6fb      | 4        | 0.56%   |
| 0x40651    | 4        | 0.56%   |
| 0x0a50000d | 4        | 0.56%   |
| 0x08108109 | 4        | 0.56%   |
| 0xa0653    | 3        | 0.42%   |
| 0x906ed    | 3        | 0.42%   |
| 0x6f6      | 3        | 0.42%   |
| 0x50654    | 3        | 0.42%   |
| 0x206d7    | 3        | 0.42%   |
| 0x10676    | 3        | 0.42%   |
| 0x0a20120a | 3        | 0.42%   |
| 0x08101016 | 3        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 78       | 11.42%  |
| KabyLake         | 65       | 9.52%   |
| Zen 2            | 64       | 9.37%   |
| IvyBridge        | 50       | 7.32%   |
| Skylake          | 49       | 7.17%   |
| Zen 3            | 45       | 6.59%   |
| SandyBridge      | 41       | 6%      |
| K10              | 40       | 5.86%   |
| Zen              | 34       | 4.98%   |
| Penryn           | 33       | 4.83%   |
| Zen+             | 31       | 4.54%   |
| Piledriver       | 29       | 4.25%   |
| K8 Hammer        | 16       | 2.34%   |
| Core             | 16       | 2.34%   |
| Nehalem          | 15       | 2.2%    |
| Unknown          | 15       | 2.2%    |
| Westmere         | 14       | 2.05%   |
| CometLake        | 9        | 1.32%   |
| NetBurst         | 6        | 0.88%   |
| Silvermont       | 5        | 0.73%   |
| Steamroller      | 4        | 0.59%   |
| Jaguar           | 4        | 0.59%   |
| Bulldozer        | 4        | 0.59%   |
| Alderlake Hybrid | 4        | 0.59%   |
| Goldmont plus    | 2        | 0.29%   |
| Broadwell        | 2        | 0.29%   |
| Bonnell          | 2        | 0.29%   |
| Bobcat           | 2        | 0.29%   |
| TigerLake        | 1        | 0.15%   |
| Icelake          | 1        | 0.15%   |
| Goldmont         | 1        | 0.15%   |
| Excavator        | 1        | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 320      | 43.42%  |
| AMD                                          | 225      | 30.53%  |
| Intel                                        | 175      | 23.74%  |
| ASPEED Technology                            | 11       | 1.49%   |
| Silicon Motion                               | 3        | 0.41%   |
| Matrox Electronics Systems                   | 2        | 0.27%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 36       | 4.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 36       | 4.72%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 21       | 2.75%   |
| Intel HD Graphics 530                                                       | 21       | 2.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 19       | 2.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 18       | 2.36%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 14       | 1.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 14       | 1.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13       | 1.7%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 13       | 1.7%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 13       | 1.7%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 12       | 1.57%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 11       | 1.44%   |
| Nvidia GT218 [GeForce 210]                                                  | 11       | 1.44%   |
| ASPEED Technology ASPEED Graphics Family                                    | 11       | 1.44%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 1.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 1.31%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 9        | 1.18%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 9        | 1.18%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 8        | 1.05%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 8        | 1.05%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 8        | 1.05%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 8        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 7        | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 0.92%   |
| AMD Raphael                                                                 | 7        | 0.92%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 7        | 0.92%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 6        | 0.79%   |
| Intel HD Graphics 630                                                       | 6        | 0.79%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 6        | 0.79%   |
| AMD RS880 [Radeon HD 4200]                                                  | 6        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.66%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 5        | 0.66%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 5        | 0.66%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 0.66%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 0.66%   |
| Intel Core Processor Integrated Graphics Controller                         | 5        | 0.66%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 5        | 0.66%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 5        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 293      | 42.16%  |
| 1 x AMD            | 197      | 28.35%  |
| 1 x Intel          | 147      | 21.15%  |
| 2 x AMD            | 12       | 1.73%   |
| 1 x ASPEED         | 11       | 1.58%   |
| AMD + Nvidia       | 11       | 1.58%   |
| Intel + Nvidia     | 8        | 1.15%   |
| 2 x Nvidia         | 6        | 0.86%   |
| 1 x Silicon Motion | 3        | 0.43%   |
| Intel + AMD        | 2        | 0.29%   |
| Other              | 1        | 0.14%   |
| 2 x Intel          | 1        | 0.14%   |
| 1 x XGI            | 1        | 0.14%   |
| Nvidia + Matrox    | 1        | 0.14%   |
| 1 x Matrox         | 1        | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 470      | 67.05%  |
| Proprietary | 194      | 27.67%  |
| Unknown     | 37       | 5.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 262      | 36.54%  |
| 1.01-2.0   | 94       | 13.11%  |
| 7.01-8.0   | 91       | 12.69%  |
| 0.01-0.5   | 73       | 10.18%  |
| 3.01-4.0   | 67       | 9.34%   |
| 0.51-1.0   | 60       | 8.37%   |
| 5.01-6.0   | 31       | 4.32%   |
| 8.01-16.0  | 23       | 3.21%   |
| 2.01-3.0   | 10       | 1.39%   |
| 16.01-24.0 | 6        | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 149      | 19.28%  |
| BenQ                 | 70       | 9.06%   |
| Ancor Communications | 64       | 8.28%   |
| Hewlett-Packard      | 63       | 8.15%   |
| Acer                 | 62       | 8.02%   |
| Dell                 | 58       | 7.5%    |
| Goldstar             | 49       | 6.34%   |
| Lenovo               | 31       | 4.01%   |
| ASUSTek Computer     | 26       | 3.36%   |
| Fujitsu Siemens      | 23       | 2.98%   |
| AOC                  | 23       | 2.98%   |
| Sony                 | 22       | 2.85%   |
| Philips              | 22       | 2.85%   |
| ViewSonic            | 14       | 1.81%   |
| Eizo                 | 13       | 1.68%   |
| LG Electronics       | 7        | 0.91%   |
| Unknown              | 6        | 0.78%   |
| Panasonic            | 5        | 0.65%   |
| MSI                  | 5        | 0.65%   |
| Vestel Elektronik    | 4        | 0.52%   |
| FUS                  | 4        | 0.52%   |
| Toshiba              | 3        | 0.39%   |
| Packard Bell         | 3        | 0.39%   |
| Onkyo                | 3        | 0.39%   |
| NEC Computers        | 3        | 0.39%   |
| Iiyama               | 3        | 0.39%   |
| Wacom                | 2        | 0.26%   |
| Tech Concepts        | 2        | 0.26%   |
| Lenovo Group Limited | 2        | 0.26%   |
| Hitachi              | 2        | 0.26%   |
| DENON                | 2        | 0.26%   |
| AUS                  | 2        | 0.26%   |
| Unknown              | 2        | 0.26%   |
| Xiaomi               | 1        | 0.13%   |
| Valve                | 1        | 0.13%   |
| UGD                  | 1        | 0.13%   |
| TVT                  | 1        | 0.13%   |
| SFX                  | 1        | 0.13%   |
| PKB                  | 1        | 0.13%   |
| Optoma               | 1        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6        | 0.73%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 6        | 0.73%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 5        | 0.61%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 5        | 0.61%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 5        | 0.61%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 4        | 0.49%   |
| Hewlett-Packard Z23i HWP3090 1920x1080 509x286mm 23.0-inch            | 4        | 0.49%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 4        | 0.49%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 4        | 0.49%   |
| BenQ G2400W BNQ780A 1920x1200 519x324mm 24.1-inch                     | 4        | 0.49%   |
| Ancor Communications VG248 ACI24A4 1920x1080 530x300mm 24.0-inch      | 4        | 0.49%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 4        | 0.49%   |
| Sony TV SNY0801 1360x768                                              | 3        | 0.37%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 3        | 0.37%   |
| Samsung Electronics T24D390 SAM0B6C 1920x1080 521x293mm 23.5-inch     | 3        | 0.37%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 3        | 0.37%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 3        | 0.37%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 3        | 0.37%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                     | 3        | 0.37%   |
| Samsung Electronics CF791 SAM0DC4 3440x1440 797x333mm 34.0-inch       | 3        | 0.37%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 3        | 0.37%   |
| LG Electronics LCD Monitor LG TV                                      | 3        | 0.37%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 3        | 0.37%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 3        | 0.37%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 3        | 0.37%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                  | 3        | 0.37%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 3        | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3        | 0.37%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 3        | 0.37%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch               | 3        | 0.37%   |
| BenQ ZOWIE XL LCD BNQ7F32 1920x1080 531x298mm 24.0-inch               | 3        | 0.37%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 3        | 0.37%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 3        | 0.37%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 3        | 0.37%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 3        | 0.37%   |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 621x341mm 27.9-inch | 3        | 0.37%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch | 3        | 0.37%   |
| Acer X34 ACR0450 3440x1440 798x335mm 34.1-inch                        | 3        | 0.37%   |
| Acer S191HQL ACR021C 1366x768 410x230mm 18.5-inch                     | 3        | 0.37%   |
| Acer KG241 P ACR069A 1920x1080 531x299mm 24.0-inch                    | 3        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 301      | 39.71%  |
| 2560x1440 (QHD)    | 77       | 10.16%  |
| 3840x2160 (4K)     | 75       | 9.89%   |
| 1680x1050 (WSXGA+) | 55       | 7.26%   |
| 1920x1200 (WUXGA)  | 49       | 6.46%   |
| 1280x1024 (SXGA)   | 43       | 5.67%   |
| Unknown            | 32       | 4.22%   |
| 3440x1440          | 23       | 3.03%   |
| 1440x900 (WXGA+)   | 16       | 2.11%   |
| 1360x768           | 16       | 2.11%   |
| 3840x1080          | 12       | 1.58%   |
| 1366x768 (WXGA)    | 7        | 0.92%   |
| 1920x540           | 6        | 0.79%   |
| 1600x900 (HD+)     | 5        | 0.66%   |
| 1280x720 (HD)      | 5        | 0.66%   |
| 4480x1440          | 4        | 0.53%   |
| 1600x1200          | 4        | 0.53%   |
| 2560x1080          | 3        | 0.4%    |
| 5760x2160          | 2        | 0.26%   |
| 5120x1440          | 2        | 0.26%   |
| 3840x1200          | 2        | 0.26%   |
| 3360x1050          | 2        | 0.26%   |
| 2560x1600          | 2        | 0.26%   |
| 7680x2160          | 1        | 0.13%   |
| 5760x1440          | 1        | 0.13%   |
| 5280x1080          | 1        | 0.13%   |
| 4480x1600          | 1        | 0.13%   |
| 3840x1600          | 1        | 0.13%   |
| 3520x1200          | 1        | 0.13%   |
| 3360x1080          | 1        | 0.13%   |
| 2560x2880          | 1        | 0.13%   |
| 2288x1287          | 1        | 0.13%   |
| 2160x1200          | 1        | 0.13%   |
| 1834x1031          | 1        | 0.13%   |
| 1826x1027          | 1        | 0.13%   |
| 1400x1050          | 1        | 0.13%   |
| 1360x765           | 1        | 0.13%   |
| 1024x768 (XGA)     | 1        | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 146      | 19.41%  |
| 27      | 105      | 13.96%  |
| 23      | 98       | 13.03%  |
| Unknown | 95       | 12.63%  |
| 22      | 46       | 6.12%   |
| 19      | 41       | 5.45%   |
| 31      | 30       | 3.99%   |
| 21      | 29       | 3.86%   |
| 34      | 20       | 2.66%   |
| 84      | 17       | 2.26%   |
| 18      | 14       | 1.86%   |
| 20      | 13       | 1.73%   |
| 32      | 12       | 1.6%    |
| 25      | 12       | 1.6%    |
| 17      | 11       | 1.46%   |
| 72      | 10       | 1.33%   |
| 40      | 9        | 1.2%    |
| 55      | 4        | 0.53%   |
| 28      | 4        | 0.53%   |
| 26      | 4        | 0.53%   |
| 65      | 3        | 0.4%    |
| 54      | 3        | 0.4%    |
| 36      | 3        | 0.4%    |
| 29      | 3        | 0.4%    |
| 49      | 2        | 0.27%   |
| 48      | 2        | 0.27%   |
| 46      | 2        | 0.27%   |
| 39      | 2        | 0.27%   |
| 33      | 2        | 0.27%   |
| 15      | 2        | 0.27%   |
| 13      | 2        | 0.27%   |
| 142     | 1        | 0.13%   |
| 85      | 1        | 0.13%   |
| 75      | 1        | 0.13%   |
| 37      | 1        | 0.13%   |
| 35      | 1        | 0.13%   |
| 14      | 1        | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 315      | 44.37%  |
| 401-500        | 109      | 15.35%  |
| Unknown        | 95       | 13.38%  |
| 601-700        | 47       | 6.62%   |
| 701-800        | 37       | 5.21%   |
| 351-400        | 33       | 4.65%   |
| 1501-2000      | 29       | 4.08%   |
| 1001-1500      | 15       | 2.11%   |
| 801-900        | 13       | 1.83%   |
| 301-350        | 13       | 1.83%   |
| 201-300        | 3        | 0.42%   |
| More than 2000 | 1        | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 394      | 57.27%  |
| 16/10   | 130      | 18.9%   |
| Unknown | 79       | 11.48%  |
| 5/4     | 41       | 5.96%   |
| 21/9    | 24       | 3.49%   |
| 32/9    | 7        | 1.02%   |
| 4/3     | 5        | 0.73%   |
| 6/5     | 3        | 0.44%   |
| 3/2     | 3        | 0.44%   |
| 1.00    | 1        | 0.15%   |
| 0.89    | 1        | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 240      | 32.7%   |
| 301-350        | 109      | 14.85%  |
| Unknown        | 95       | 12.94%  |
| 251-300        | 71       | 9.67%   |
| 351-500        | 70       | 9.54%   |
| 151-200        | 67       | 9.13%   |
| More than 1000 | 39       | 5.31%   |
| 501-1000       | 21       | 2.86%   |
| 141-150        | 17       | 2.32%   |
| 101-110        | 3        | 0.41%   |
| 71-80          | 2        | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 426      | 61.83%  |
| 101-120 | 95       | 13.79%  |
| Unknown | 95       | 13.79%  |
| 121-160 | 34       | 4.93%   |
| 1-50    | 27       | 3.92%   |
| 161-240 | 12       | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 510      | 73.17%  |
| 2     | 127      | 18.22%  |
| 0     | 41       | 5.88%   |
| 3     | 16       | 2.3%    |
| 4     | 3        | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 364      | 37.37%  |
| Intel                                  | 327      | 33.57%  |
| Qualcomm Atheros                       | 40       | 4.11%   |
| Broadcom                               | 28       | 2.87%   |
| Ralink                                 | 18       | 1.85%   |
| Nvidia                                 | 17       | 1.75%   |
| TP-Link                                | 16       | 1.64%   |
| ASUSTek Computer                       | 15       | 1.54%   |
| Huawei Technologies                    | 14       | 1.44%   |
| Ralink Technology                      | 13       | 1.33%   |
| Samsung Electronics                    | 12       | 1.23%   |
| MediaTek                               | 9        | 0.92%   |
| Marvell Technology Group               | 9        | 0.92%   |
| Xiaomi                                 | 8        | 0.82%   |
| Microsoft                              | 7        | 0.72%   |
| Broadcom Limited                       | 7        | 0.72%   |
| ZyXEL Communications                   | 5        | 0.51%   |
| D-Link System                          | 5        | 0.51%   |
| Motorola PCS                           | 4        | 0.41%   |
| NetGear                                | 3        | 0.31%   |
| Microchip Technology                   | 3        | 0.31%   |
| HMD Global                             | 3        | 0.31%   |
| Gemtek                                 | 3        | 0.31%   |
| D-Link                                 | 3        | 0.31%   |
| BUFFALO                                | 3        | 0.31%   |
| ASIX Electronics                       | 3        | 0.31%   |
| Aquantia                               | 3        | 0.31%   |
| 3Com                                   | 3        | 0.31%   |
| ZyDAS                                  | 2        | 0.21%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.21%   |
| Qualcomm                               | 2        | 0.21%   |
| Linksys                                | 2        | 0.21%   |
| Edimax Technology                      | 2        | 0.21%   |
| VIA Technologies                       | 1        | 0.1%    |
| U-Blox                                 | 1        | 0.1%    |
| Seeed Technology                       | 1        | 0.1%    |
| Qualcomm Atheros Communications        | 1        | 0.1%    |
| OPPO Electronics                       | 1        | 0.1%    |
| OnePlus Technology (Shenzhen)          | 1        | 0.1%    |
| Oculus VR                              | 1        | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 288      | 26.02%  |
| Intel I211 Gigabit Network Connection                                  | 57       | 5.15%   |
| Intel Ethernet Connection (2) I219-V                                   | 35       | 3.16%   |
| Realtek RTL8125 2.5GbE Controller                                      | 34       | 3.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 33       | 2.98%   |
| Intel Wi-Fi 6 AX200                                                    | 28       | 2.53%   |
| Intel Ethernet Controller I225-V                                       | 20       | 1.81%   |
| Intel 82579V Gigabit Network Connection                                | 16       | 1.45%   |
| Intel I210 Gigabit Network Connection                                  | 15       | 1.36%   |
| Intel Ethernet Connection I217-LM                                      | 15       | 1.36%   |
| Intel Ethernet Connection (7) I219-V                                   | 15       | 1.36%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15       | 1.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 13       | 1.17%   |
| Intel Ethernet Connection I217-V                                       | 13       | 1.17%   |
| Nvidia MCP61 Ethernet                                                  | 12       | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 12       | 1.08%   |
| Intel Ethernet Connection (2) I218-V                                   | 11       | 0.99%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 11       | 0.99%   |
| Intel 82574L Gigabit Network Connection                                | 9        | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8        | 0.72%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 8        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 7        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7        | 0.63%   |
| Huawei STG-LX1                                                         | 7        | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6        | 0.54%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller              | 6        | 0.54%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 6        | 0.54%   |
| Intel Wireless 7260                                                    | 6        | 0.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6        | 0.54%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 6        | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6        | 0.54%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]              | 6        | 0.54%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 5        | 0.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 0.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 5        | 0.45%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 5        | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 5        | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 5        | 0.45%   |
| Intel Wireless 8260                                                    | 5        | 0.45%   |
| Intel I350 Gigabit Network Connection                                  | 5        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 89       | 30.58%  |
| Realtek Semiconductor           | 67       | 23.02%  |
| Ralink                          | 18       | 6.19%   |
| Broadcom                        | 16       | 5.5%    |
| TP-Link                         | 15       | 5.15%   |
| ASUSTek Computer                | 15       | 5.15%   |
| Qualcomm Atheros                | 14       | 4.81%   |
| Ralink Technology               | 13       | 4.47%   |
| MediaTek                        | 9        | 3.09%   |
| Microsoft                       | 7        | 2.41%   |
| ZyXEL Communications            | 5        | 1.72%   |
| D-Link System                   | 4        | 1.37%   |
| NetGear                         | 3        | 1.03%   |
| Gemtek                          | 3        | 1.03%   |
| BUFFALO                         | 3        | 1.03%   |
| ZyDAS                           | 2        | 0.69%   |
| Edimax Technology               | 2        | 0.69%   |
| D-Link                          | 2        | 0.69%   |
| Qualcomm Atheros Communications | 1        | 0.34%   |
| Linksys                         | 1        | 0.34%   |
| LG Electronics                  | 1        | 0.34%   |
| Broadcom Limited                | 1        | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 28       | 9.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 13       | 4.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12       | 4.08%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 8        | 2.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7        | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6        | 2.04%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 6        | 2.04%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 6        | 2.04%   |
| Intel Wireless 7260                                            | 6        | 2.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 6        | 2.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 6        | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6        | 2.04%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]      | 6        | 2.04%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 5        | 1.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 5        | 1.7%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 5        | 1.7%    |
| Intel Wireless 8260                                            | 5        | 1.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 4        | 1.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4        | 1.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4        | 1.36%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 4        | 1.36%   |
| Realtek 802.11ac NIC                                           | 4        | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4        | 1.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4        | 1.36%   |
| Microsoft Xbox 360 Wireless Adapter                            | 4        | 1.36%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4        | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4        | 1.36%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 4        | 1.36%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3        | 1.02%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 3        | 1.02%   |
| Ralink RT5370 Wireless Adapter                                 | 3        | 1.02%   |
| Ralink MT7601U Wireless Adapter                                | 3        | 1.02%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 3        | 1.02%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 3        | 1.02%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 3        | 1.02%   |
| Gemtek WUBR-177G [Ralink RT2571W]                              | 3        | 1.02%   |
| ASUS USB-N53 802.11abgn Network Adapter [Ralink RT3572]        | 3        | 1.02%   |
| ZyXEL ZyXEL Dual-Band Wireless AC USB Adapter                  | 2        | 0.68%   |
| ZyDAS ZD1211B 802.11g                                          | 2        | 0.68%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 338      | 44.42%  |
| Intel                                  | 288      | 37.84%  |
| Qualcomm Atheros                       | 28       | 3.68%   |
| Nvidia                                 | 17       | 2.23%   |
| Samsung Electronics                    | 12       | 1.58%   |
| Broadcom                               | 12       | 1.58%   |
| Huawei Technologies                    | 11       | 1.45%   |
| Marvell Technology Group               | 9        | 1.18%   |
| Xiaomi                                 | 8        | 1.05%   |
| Broadcom Limited                       | 6        | 0.79%   |
| Motorola PCS                           | 3        | 0.39%   |
| HMD Global                             | 3        | 0.39%   |
| ASIX Electronics                       | 3        | 0.39%   |
| Aquantia                               | 3        | 0.39%   |
| 3Com                                   | 3        | 0.39%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.26%   |
| Qualcomm                               | 2        | 0.26%   |
| VIA Technologies                       | 1        | 0.13%   |
| TP-Link                                | 1        | 0.13%   |
| OPPO Electronics                       | 1        | 0.13%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.13%   |
| Linksys                                | 1        | 0.13%   |
| Lenovo                                 | 1        | 0.13%   |
| Google                                 | 1        | 0.13%   |
| DisplayLink                            | 1        | 0.13%   |
| D-Link System                          | 1        | 0.13%   |
| D-Link                                 | 1        | 0.13%   |
| American Megatrends                    | 1        | 0.13%   |
| AMD                                    | 1        | 0.13%   |
| ADMtek                                 | 1        | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 288      | 36.09%  |
| Intel I211 Gigabit Network Connection                                  | 57       | 7.14%   |
| Intel Ethernet Connection (2) I219-V                                   | 35       | 4.39%   |
| Realtek RTL8125 2.5GbE Controller                                      | 34       | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 33       | 4.14%   |
| Intel Ethernet Controller I225-V                                       | 20       | 2.51%   |
| Intel 82579V Gigabit Network Connection                                | 16       | 2.01%   |
| Intel I210 Gigabit Network Connection                                  | 15       | 1.88%   |
| Intel Ethernet Connection I217-LM                                      | 15       | 1.88%   |
| Intel Ethernet Connection (7) I219-V                                   | 15       | 1.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15       | 1.88%   |
| Intel Ethernet Connection I217-V                                       | 13       | 1.63%   |
| Nvidia MCP61 Ethernet                                                  | 12       | 1.5%    |
| Intel Ethernet Connection (2) I218-V                                   | 11       | 1.38%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 11       | 1.38%   |
| Intel 82574L Gigabit Network Connection                                | 9        | 1.13%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8        | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7        | 0.88%   |
| Huawei STG-LX1                                                         | 7        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 5        | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 5        | 0.63%   |
| Intel I350 Gigabit Network Connection                                  | 5        | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4        | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 4        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 4        | 0.5%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 4        | 0.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 4        | 0.5%    |
| Intel 82578DM Gigabit Network Connection                               | 4        | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 4        | 0.5%    |
| Huawei E353/E3131                                                      | 4        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 3        | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3        | 0.38%   |
| Motorola PCS moto g52                                                  | 3        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 0.38%   |
| Intel 82578DC Gigabit Network Connection                               | 3        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 676      | 70.05%  |
| WiFi     | 275      | 28.5%   |
| Modem    | 12       | 1.24%   |
| Unknown  | 2        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 549      | 80.62%  |
| WiFi     | 131      | 19.24%  |
| Unknown  | 1        | 0.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 433      | 63.21%  |
| 2     | 205      | 29.93%  |
| 3     | 31       | 4.53%   |
| 0     | 8        | 1.17%   |
| 5     | 5        | 0.73%   |
| 4     | 3        | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 565      | 80.95%  |
| Yes  | 133      | 19.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 87       | 39.55%  |
| Cambridge Silicon Radio         | 55       | 25%     |
| ASUSTek Computer                | 36       | 16.36%  |
| Realtek Semiconductor           | 11       | 5%      |
| IMC Networks                    | 6        | 2.73%   |
| MediaTek                        | 5        | 2.27%   |
| Qualcomm Atheros Communications | 4        | 1.82%   |
| HTC (High Tech Computer)        | 4        | 1.82%   |
| Apple                           | 4        | 1.82%   |
| Broadcom                        | 3        | 1.36%   |
| Edimax Technology               | 2        | 0.91%   |
| Lite-On Technology              | 1        | 0.45%   |
| Foxconn / Hon Hai               | 1        | 0.45%   |
| Belkin Components               | 1        | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 55       | 24.77%  |
| Intel AX200 Bluetooth                                                | 32       | 14.41%  |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 20       | 9.01%   |
| Intel Bluetooth wireless interface                                   | 19       | 8.56%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 10       | 4.5%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 9        | 4.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 7        | 3.15%   |
| IMC Networks Bluetooth Radio                                         | 6        | 2.7%    |
| ASUS ASUS USB-BT500                                                  | 6        | 2.7%    |
| MediaTek Wireless_Device                                             | 5        | 2.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 5        | 2.25%   |
| Intel AX210 Bluetooth                                                | 4        | 1.8%    |
| Intel AX201 Bluetooth                                                | 4        | 1.8%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 1.8%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 1.35%   |
| Intel Bluetooth Device                                               | 3        | 1.35%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 3        | 1.35%   |
| ASUS Bluetooth Radio                                                 | 3        | 1.35%   |
| ASUS BCM20702A0                                                      | 3        | 1.35%   |
| Realtek Bluetooth Radio                                              | 2        | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                                    | 2        | 0.9%    |
| Edimax Bluetooth Adapter                                             | 2        | 0.9%    |
| ASUS Bluetooth Adapter                                               | 2        | 0.9%    |
| Apple Bluetooth Host Controller                                      | 2        | 0.9%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 0.45%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)                      | 1        | 0.45%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 1        | 0.45%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1        | 0.45%   |
| Broadcom Bluetooth 3.0+HS USB Adapter                                | 1        | 0.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 0.45%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 1        | 0.45%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.45%   |
| ASUS Bluetooth Device                                                | 1        | 0.45%   |
| Apple Bluetooth USB Host Controller                                  | 1        | 0.45%   |
| Apple Bluetooth HCI                                                  | 1        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 362      | 30.09%  |
| Nvidia                               | 314      | 26.1%   |
| AMD                                  | 312      | 25.94%  |
| C-Media Electronics                  | 28       | 2.33%   |
| Logitech                             | 19       | 1.58%   |
| Creative Labs                        | 16       | 1.33%   |
| Kingston Technology                  | 12       | 1%      |
| ASUSTek Computer                     | 12       | 1%      |
| Texas Instruments                    | 8        | 0.67%   |
| SteelSeries ApS                      | 8        | 0.67%   |
| Creative Technology                  | 8        | 0.67%   |
| Razer USA                            | 7        | 0.58%   |
| Focusrite-Novation                   | 7        | 0.58%   |
| Corsair                              | 6        | 0.5%    |
| VIA Technologies                     | 5        | 0.42%   |
| RODE Microphones                     | 4        | 0.33%   |
| M-Audio                              | 4        | 0.33%   |
| Blue Microphones                     | 4        | 0.33%   |
| Thesycon Systemsoftware & Consulting | 3        | 0.25%   |
| Plantronics                          | 3        | 0.25%   |
| GN Netcom                            | 3        | 0.25%   |
| Generalplus Technology               | 3        | 0.25%   |
| DSEA A/S                             | 3        | 0.25%   |
| BEHRINGER International              | 3        | 0.25%   |
| AudioQuest                           | 3        | 0.25%   |
| SAVITECH                             | 2        | 0.17%   |
| Realtek Semiconductor                | 2        | 0.17%   |
| Microsoft                            | 2        | 0.17%   |
| Lenovo                               | 2        | 0.17%   |
| JBL                                  | 2        | 0.17%   |
| GYROCOM C&C                          | 2        | 0.17%   |
| FiiO Electronics Technology          | 2        | 0.17%   |
| Cambridge Audio                      | 2        | 0.17%   |
| Zeroplus                             | 1        | 0.08%   |
| Yamaha                               | 1        | 0.08%   |
| XMOS                                 | 1        | 0.08%   |
| Valve Software                       | 1        | 0.08%   |
| Turtle Beach                         | 1        | 0.08%   |
| Trust                                | 1        | 0.08%   |
| Thomann                              | 1        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 87       | 6.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 64       | 4.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 51       | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 45       | 3.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 44       | 3.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 42       | 3%      |
| Nvidia GP104 High Definition Audio Controller                              | 36       | 2.57%   |
| Intel 200 Series PCH HD Audio                                              | 36       | 2.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 35       | 2.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 35       | 2.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 34       | 2.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 31       | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 24       | 1.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 21       | 1.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 21       | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 20       | 1.43%   |
| Nvidia High Definition Audio Controller                                    | 18       | 1.28%   |
| AMD Navi 10 HDMI Audio                                                     | 18       | 1.28%   |
| Nvidia TU116 High Definition Audio Controller                              | 17       | 1.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 17       | 1.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 17       | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                              | 16       | 1.14%   |
| Nvidia GM206 High Definition Audio Controller                              | 15       | 1.07%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 15       | 1.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 14       | 1%      |
| Nvidia MCP61 High Definition Audio                                         | 13       | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 13       | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                         | 13       | 0.93%   |
| Nvidia GK104 HDMI Audio Controller                                         | 13       | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 13       | 0.93%   |
| AMD FCH Azalia Controller                                                  | 13       | 0.93%   |
| Nvidia TU104 HD Audio Controller                                           | 12       | 0.86%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 12       | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11       | 0.79%   |
| Nvidia GM204 High Definition Audio Controller                              | 11       | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 11       | 0.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11       | 0.79%   |
| Nvidia GP102 HDMI Audio Controller                                         | 10       | 0.71%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 10       | 0.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 151      | 33.11%  |
| Samsung Electronics | 53       | 11.62%  |
| Unknown             | 43       | 9.43%   |
| G.Skill             | 43       | 9.43%   |
| Corsair             | 42       | 9.21%   |
| SK hynix            | 34       | 7.46%   |
| Crucial             | 29       | 6.36%   |
| Micron Technology   | 24       | 5.26%   |
| Ramaxel Technology  | 7        | 1.54%   |
| Nanya Technology    | 5        | 1.1%    |
| Elpida              | 5        | 1.1%    |
| Team                | 3        | 0.66%   |
| A-DATA Technology   | 3        | 0.66%   |
| Unknown (ABCD)      | 2        | 0.44%   |
| ASint Technology    | 2        | 0.44%   |
| Apacer              | 2        | 0.44%   |
| Unknown (AB)        | 1        | 0.22%   |
| Unigen              | 1        | 0.22%   |
| Qimonda             | 1        | 0.22%   |
| Patriot             | 1        | 0.22%   |
| Hitachi             | 1        | 0.22%   |
| GOODRAM             | 1        | 0.22%   |
| GIGA-BYTE           | 1        | 0.22%   |
| Unknown             | 1        | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 17       | 3.36%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 11       | 2.17%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 8        | 1.58%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 7        | 1.38%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 6        | 1.19%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1600MT/s         | 6        | 1.19%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 6        | 1.19%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 6        | 1.19%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 5        | 0.99%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 5        | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 4        | 0.79%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s            | 4        | 0.79%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s            | 4        | 0.79%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 4        | 0.79%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s            | 4        | 0.79%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s            | 4        | 0.79%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s           | 4        | 0.79%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s          | 4        | 0.79%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 4        | 0.79%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 3        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 3        | 0.59%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 3        | 0.59%   |
| Samsung RAM M391A4G43AB1-CWE 32GB DIMM DDR4 3200MT/s           | 3        | 0.59%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s            | 3        | 0.59%   |
| Ramaxel RAM RMR1870EC58E9F1333 4GB DIMM DDR3 1333MT/s          | 3        | 0.59%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 3        | 0.59%   |
| Kingston RAM 99U5471-002.A01LF 2GB DIMM DDR3 1334MT/s          | 3        | 0.59%   |
| G.Skill RAM F4-3200C16-16GTZ 16GB DIMM DDR4 3200MT/s           | 3        | 0.59%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 3        | 0.59%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s           | 3        | 0.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 2        | 0.4%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 2        | 0.4%    |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 2        | 0.4%    |
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 2        | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 0.4%    |
| SK hynix RAM Module 8GB DIMM DDR3 1333MT/s                     | 2        | 0.4%    |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s            | 2        | 0.4%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 0.4%    |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                      | 2        | 0.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 203      | 48.8%   |
| DDR3    | 138      | 33.17%  |
| DDR2    | 28       | 6.73%   |
| Unknown | 16       | 3.85%   |
| SDRAM   | 12       | 2.88%   |
| DDR5    | 9        | 2.16%   |
| DDR     | 6        | 1.44%   |
| LPDDR4  | 3        | 0.72%   |
| DRAM    | 1        | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 387      | 94.62%  |
| SODIMM       | 18       | 4.4%    |
| RIMM         | 2        | 0.49%   |
| Row Of Chips | 1        | 0.24%   |
| FB-DIMM      | 1        | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 172      | 38.74%  |
| 4096  | 95       | 21.4%   |
| 16384 | 65       | 14.64%  |
| 2048  | 59       | 13.29%  |
| 32768 | 27       | 6.08%   |
| 1024  | 21       | 4.73%   |
| 512   | 5        | 1.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 62       | 13.39%  |
| 1333    | 49       | 10.58%  |
| 3200    | 34       | 7.34%   |
| 3600    | 29       | 6.26%   |
| 2133    | 29       | 6.26%   |
| 3733    | 25       | 5.4%    |
| 2400    | 22       | 4.75%   |
| 800     | 21       | 4.54%   |
| 2667    | 18       | 3.89%   |
| 667     | 16       | 3.46%   |
| 1867    | 15       | 3.24%   |
| 3466    | 14       | 3.02%   |
| 3800    | 13       | 2.81%   |
| 1866    | 8        | 1.73%   |
| 1066    | 8        | 1.73%   |
| 3533    | 7        | 1.51%   |
| 3000    | 7        | 1.51%   |
| 2933    | 7        | 1.51%   |
| 3866    | 6        | 1.3%    |
| 4800    | 5        | 1.08%   |
| 1800    | 5        | 1.08%   |
| 3400    | 4        | 0.86%   |
| 3266    | 4        | 0.86%   |
| 2800    | 4        | 0.86%   |
| 2666    | 4        | 0.86%   |
| 2200    | 4        | 0.86%   |
| 1334    | 4        | 0.86%   |
| 3333    | 3        | 0.65%   |
| 1067    | 3        | 0.65%   |
| 533     | 3        | 0.65%   |
| 49926   | 2        | 0.43%   |
| 5600    | 2        | 0.43%   |
| 3151    | 2        | 0.43%   |
| 3100    | 2        | 0.43%   |
| 2733    | 2        | 0.43%   |
| Unknown | 2        | 0.43%   |
| 8192    | 1        | 0.22%   |
| 6400    | 1        | 0.22%   |
| 5200    | 1        | 0.22%   |
| 4133    | 1        | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 11       | 42.31%  |
| Seiko Epson         | 4        | 15.38%  |
| Samsung Electronics | 3        | 11.54%  |
| Brother Industries  | 3        | 11.54%  |
| Xerox               | 2        | 7.69%   |
| Canon               | 2        | 7.69%   |
| Prolific Technology | 1        | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung ML-1660 Series              | 2        | 7.69%   |
| HP DeskJet 6940 series              | 2        | 7.69%   |
| Xerox WorkCentre 3325               | 1        | 3.85%   |
| Xerox Phaser 6500N                  | 1        | 3.85%   |
| Seiko Epson WF-3520 Series          | 1        | 3.85%   |
| Seiko Epson Printer                 | 1        | 3.85%   |
| Seiko Epson L555 Series             | 1        | 3.85%   |
| Seiko Epson L3150 Series            | 1        | 3.85%   |
| Samsung CLP-325 Color Laser Printer | 1        | 3.85%   |
| Prolific PL2305 Parallel Port       | 1        | 3.85%   |
| HP PSC 1100 series                  | 1        | 3.85%   |
| HP OfficeJet 5200 series            | 1        | 3.85%   |
| HP LaserJet Professional P 1102w    | 1        | 3.85%   |
| HP LaserJet Pro M148-M149           | 1        | 3.85%   |
| HP LaserJet P2055 series            | 1        | 3.85%   |
| HP LaserJet P2015 series            | 1        | 3.85%   |
| HP LaserJet 1200                    | 1        | 3.85%   |
| HP DeskJet F300 series              | 1        | 3.85%   |
| HP DeskJet 960c                     | 1        | 3.85%   |
| Canon TS3300 series                 | 1        | 3.85%   |
| Canon TS3100 series                 | 1        | 3.85%   |
| Brother MFC-7460DN                  | 1        | 3.85%   |
| Brother DCP-L2530DW series          | 1        | 3.85%   |
| Brother DCP-7055W                   | 1        | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 4        | 80%     |
| Seiko Epson | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Canon CanoScan N650U/N656U            | 2        | 40%     |
| Seiko Epson GT-X770 [Perfection V500] | 1        | 20%     |
| Canon CanoScan LiDE 200               | 1        | 20%     |
| Canon CanoScan LiDE 110               | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 46       | 48.94%  |
| Microsoft                     | 11       | 11.7%   |
| Microdia                      | 10       | 10.64%  |
| Trust                         | 3        | 3.19%   |
| Samsung Electronics           | 3        | 3.19%   |
| Realtek Semiconductor         | 3        | 3.19%   |
| Sunplus Innovation Technology | 2        | 2.13%   |
| Creative Technology           | 2        | 2.13%   |
| Chicony Electronics           | 2        | 2.13%   |
| Apple                         | 2        | 2.13%   |
| Valve Software                | 1        | 1.06%   |
| Tobii Technology AB           | 1        | 1.06%   |
| Sonix Technology              | 1        | 1.06%   |
| Silicon Motion                | 1        | 1.06%   |
| Razer USA                     | 1        | 1.06%   |
| OnePlus                       | 1        | 1.06%   |
| MacroSilicon                  | 1        | 1.06%   |
| Lenovo                        | 1        | 1.06%   |
| Google                        | 1        | 1.06%   |
| Generalplus Technology        | 1        | 1.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Logitech Webcam C270                                | 9        | 9.57%   |
| Microsoft LifeCam HD-3000                           | 8        | 8.51%   |
| Logitech HD Pro Webcam C920                         | 8        | 8.51%   |
| Logitech StreamCam                                  | 5        | 5.32%   |
| Logitech HD Webcam C525                             | 5        | 5.32%   |
| Logitech HD Webcam C510                             | 5        | 5.32%   |
| Microdia Camera                                     | 4        | 4.26%   |
| Samsung Galaxy series, misc. (MTP mode)             | 3        | 3.19%   |
| Logitech C922 Pro Stream Webcam                     | 3        | 3.19%   |
| Trust Full HD Webcam                                | 2        | 2.13%   |
| Sunplus Full HD webcam                              | 2        | 2.13%   |
| Microdia USB 2.0 Camera                             | 2        | 2.13%   |
| Logitech Webcam C930e                               | 2        | 2.13%   |
| Logitech Webcam C925e                               | 2        | 2.13%   |
| Logitech Webcam B500                                | 2        | 2.13%   |
| Valve Software 3D Camera                            | 1        | 1.06%   |
| Trust USB Camera                                    | 1        | 1.06%   |
| Tobii AB EyeChip                                    | 1        | 1.06%   |
| Sonix FHD Webcam                                    | 1        | 1.06%   |
| Silicon Motion Endoscope camera                     | 1        | 1.06%   |
| Realtek NexiGo N660P FHD Webcam                     | 1        | 1.06%   |
| Realtek Full HD webcam                              | 1        | 1.06%   |
| Realtek FULL HD 1080P Webcam                        | 1        | 1.06%   |
| Razer USA Razer Kiyo Pro                            | 1        | 1.06%   |
| OnePlus GM1913                                      | 1        | 1.06%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 1.06%   |
| Microsoft LifeCam Studio                            | 1        | 1.06%   |
| Microsoft LifeCam HD-5000                           | 1        | 1.06%   |
| Microdia Sonix USB 2.0 Camera                       | 1        | 1.06%   |
| Microdia Defender G-Lens 2577 HD720p Camera         | 1        | 1.06%   |
| Microdia AUKEY-W1                                   | 1        | 1.06%   |
| Microdia ACR010 USB Webcam                          | 1        | 1.06%   |
| MacroSilicon USB3. 0 capture                        | 1        | 1.06%   |
| Logitech Webcam C210                                | 1        | 1.06%   |
| Logitech Webcam C110                                | 1        | 1.06%   |
| Logitech QuickCam Communicate MP/S5500              | 1        | 1.06%   |
| Logitech HD Webcam C615                             | 1        | 1.06%   |
| Logitech BRIO Ultra HD Webcam                       | 1        | 1.06%   |
| Lenovo FHD Webcam Audio                             | 1        | 1.06%   |
| Google Nexus/Pixel Device (MTP + debug)             | 1        | 1.06%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microsoft Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| SCM Microsystems          | 4        | 33.33%  |
| Fujitsu Siemens Computers | 3        | 25%     |
| OmniKey                   | 2        | 16.67%  |
| Advanced Card Systems     | 2        | 16.67%  |
| Alcor Micro               | 1        | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Fujitsu Siemens Computers SmartCard Reader 2A              | 3        | 25%     |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader | 2        | 16.67%  |
| OmniKey CardMan 1021                                       | 2        | 16.67%  |
| Advanced Card Systems ACR38 SmartCard Reader               | 2        | 16.67%  |
| SCM Microsystems SCR333 SmartCard Reader                   | 1        | 8.33%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1        | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                        | 1        | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 571      | 82.51%  |
| 1     | 98       | 14.16%  |
| 2     | 17       | 2.46%   |
| 3     | 3        | 0.43%   |
| 4     | 2        | 0.29%   |
| 6     | 1        | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 46       | 32.62%  |
| Net/wireless             | 32       | 22.7%   |
| Communication controller | 14       | 9.93%   |
| Unassigned class         | 10       | 7.09%   |
| Sound                    | 7        | 4.96%   |
| Chipcard                 | 6        | 4.26%   |
| Multimedia controller    | 5        | 3.55%   |
| Bluetooth                | 4        | 2.84%   |
| Storage/raid             | 3        | 2.13%   |
| Card reader              | 3        | 2.13%   |
| Camera                   | 3        | 2.13%   |
| Storage/nvme             | 2        | 1.42%   |
| Storage/ide              | 2        | 1.42%   |
| Net/ethernet             | 2        | 1.42%   |
| Network                  | 1        | 0.71%   |
| Firewire controller      | 1        | 0.71%   |

