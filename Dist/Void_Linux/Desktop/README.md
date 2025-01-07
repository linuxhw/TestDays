Void Linux - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Void Linux.

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

Total: 115

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | P41T-C31                    | [c6bfdbb4ac](https://linux-hardware.org/?probe=c6bfdbb4ac) | Jan 03, 2025 |
| Gigabyte | Z690I A ULTRA LITE D4       | [f153085b7c](https://linux-hardware.org/?probe=f153085b7c) | Nov 21, 2024 |
| Dell     | 0HN7XN A01                  | [cb494ef824](https://linux-hardware.org/?probe=cb494ef824) | Nov 13, 2024 |
| ASRock   | B450M/ac                    | [7d8108e45d](https://linux-hardware.org/?probe=7d8108e45d) | Oct 16, 2024 |
| Dell     | 0RY007 A01                  | [5d0dff2bab](https://linux-hardware.org/?probe=5d0dff2bab) | Oct 13, 2024 |
| ASRock   | B450 Pro4                   | [e388b60674](https://linux-hardware.org/?probe=e388b60674) | Oct 05, 2024 |
| Gigabyte | H310M S2H                   | [a61d3c9e57](https://linux-hardware.org/?probe=a61d3c9e57) | Jul 05, 2024 |
| Gigabyte | MFLP5IP-00                  | [d1bb865d34](https://linux-hardware.org/?probe=d1bb865d34) | Jul 02, 2024 |
| HP       | 0AE4h                       | [3eedb438d5](https://linux-hardware.org/?probe=3eedb438d5) | Jun 19, 2024 |
| AMI      | Unknown                     | [287abc46ae](https://linux-hardware.org/?probe=287abc46ae) | Jun 11, 2024 |
| HP       | 8594                        | [f06ecd2e7b](https://linux-hardware.org/?probe=f06ecd2e7b) | Jun 08, 2024 |
| MSI      | B550-A PRO                  | [c06c68d9b3](https://linux-hardware.org/?probe=c06c68d9b3) | May 29, 2024 |
| Shuttle  | FH170                       | [7d64c3247b](https://linux-hardware.org/?probe=7d64c3247b) | May 29, 2024 |
| HP       | 8594                        | [441198408b](https://linux-hardware.org/?probe=441198408b) | May 22, 2024 |
| ASUSTek  | PRIME Z370-P II             | [09665b9825](https://linux-hardware.org/?probe=09665b9825) | Mar 21, 2024 |
| Gigabyte | Z97X-UD7 TH-CF              | [3f20fe5386](https://linux-hardware.org/?probe=3f20fe5386) | Mar 13, 2024 |
| ASUSTek  | ROG Maximus Z790 APEX EN... | [b0c33ebfd2](https://linux-hardware.org/?probe=b0c33ebfd2) | Mar 07, 2024 |
| ASUSTek  | ROG Maximus Z790 APEX EN... | [15c45d681f](https://linux-hardware.org/?probe=15c45d681f) | Mar 06, 2024 |
| Gigabyte | B550 AORUS ELITE V2         | [7fe3789b7f](https://linux-hardware.org/?probe=7fe3789b7f) | Feb 23, 2024 |
| Gigabyte | X570 AORUS MASTER           | [bda104dc07](https://linux-hardware.org/?probe=bda104dc07) | Feb 04, 2024 |
| Gigabyte | Z790 AORUS MASTER X         | [c35fdb0865](https://linux-hardware.org/?probe=c35fdb0865) | Feb 04, 2024 |
| HP       | 2ADE                        | [c98c83ddde](https://linux-hardware.org/?probe=c98c83ddde) | Jan 29, 2024 |
| Gigabyte | Z790 AORUS MASTER X         | [89387d46ef](https://linux-hardware.org/?probe=89387d46ef) | Jan 18, 2024 |
| Gigabyte | Z790 AORUS MASTER X         | [c1e2f276ba](https://linux-hardware.org/?probe=c1e2f276ba) | Jan 18, 2024 |
| Dell     | 0G919G A00                  | [265aa7e914](https://linux-hardware.org/?probe=265aa7e914) | Jan 04, 2024 |
| ASRock   | B550M Pro4                  | [9eb47b934a](https://linux-hardware.org/?probe=9eb47b934a) | Jan 02, 2024 |
| ASUSTek  | PRIME B660M-A WIFI D4       | [7caa5da564](https://linux-hardware.org/?probe=7caa5da564) | Dec 31, 2023 |
| MSI      | PRO B550M-P GEN3            | [9662ee22d6](https://linux-hardware.org/?probe=9662ee22d6) | Dec 26, 2023 |
| ASUSTek  | TUF Gaming B550M-PLUS WI... | [980caec27f](https://linux-hardware.org/?probe=980caec27f) | Dec 03, 2023 |
| ASUSTek  | TUF Gaming X570-PLUS        | [f6d20427d3](https://linux-hardware.org/?probe=f6d20427d3) | Nov 26, 2023 |
| ASUSTek  | TUF Gaming X570-PLUS        | [7ed36f1817](https://linux-hardware.org/?probe=7ed36f1817) | Nov 18, 2023 |
| ASUSTek  | TUF Gaming X570-PLUS        | [f2070cd827](https://linux-hardware.org/?probe=f2070cd827) | Nov 18, 2023 |
| Unknown  | T100                        | [298b8f8764](https://linux-hardware.org/?probe=298b8f8764) | Nov 16, 2023 |
| ASUSTek  | PRIME B550-PLUS AC-HES      | [6a8536f5df](https://linux-hardware.org/?probe=6a8536f5df) | Nov 04, 2023 |
| Dell     | 0C27VV A03                  | [3e65f94217](https://linux-hardware.org/?probe=3e65f94217) | Oct 28, 2023 |
| EVGA     | Z790 DARK KINGPIN.0         | [9faa5f07eb](https://linux-hardware.org/?probe=9faa5f07eb) | Oct 20, 2023 |
| EVGA     | Z790 DARK KINGPIN.0         | [4bec650d3e](https://linux-hardware.org/?probe=4bec650d3e) | Oct 20, 2023 |
| Gigabyte | Z68XP-UD3                   | [d96bdeca74](https://linux-hardware.org/?probe=d96bdeca74) | Oct 10, 2023 |
| MSI      | B450 TOMAHAWK MAX           | [c074bb832e](https://linux-hardware.org/?probe=c074bb832e) | Oct 06, 2023 |
| MSI      | B450-A PRO MAX              | [1e60d905c5](https://linux-hardware.org/?probe=1e60d905c5) | Sep 10, 2023 |
| MSI      | MEG X570 UNIFY              | [179381f376](https://linux-hardware.org/?probe=179381f376) | Aug 12, 2023 |
| Gigabyte | X570S UD                    | [dd0cfabd4b](https://linux-hardware.org/?probe=dd0cfabd4b) | Jul 29, 2023 |
| Gigabyte | Z370 AORUS Gaming 3         | [08d9fe81da](https://linux-hardware.org/?probe=08d9fe81da) | Jul 10, 2023 |
| HP       | 1998                        | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| ASUSTek  | Maximus VIII FORMULA        | [00a862ae7c](https://linux-hardware.org/?probe=00a862ae7c) | Jun 14, 2023 |
| ASUSTek  | PRIME H610M-E D4            | [827f6ecac2](https://linux-hardware.org/?probe=827f6ecac2) | Jun 07, 2023 |
| ASUSTek  | M5A97 EVO R2.0              | [d94b8cf0e0](https://linux-hardware.org/?probe=d94b8cf0e0) | Feb 18, 2023 |
| ASUSTek  | M5A97 EVO R2.0              | [a551d228f4](https://linux-hardware.org/?probe=a551d228f4) | Jan 14, 2023 |
| MSI      | B550M PRO                   | [61b36bfa2e](https://linux-hardware.org/?probe=61b36bfa2e) | Dec 29, 2022 |
| MSI      | B550M PRO                   | [57f4a4985a](https://linux-hardware.org/?probe=57f4a4985a) | Dec 23, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| Unknown  | Unknown                     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| Dell     | 0WR7PY A03                  | [2f9e03051e](https://linux-hardware.org/?probe=2f9e03051e) | Aug 13, 2022 |
| ASUSTek  | TUF B450M-PRO GAMING        | [53fd2c87d2](https://linux-hardware.org/?probe=53fd2c87d2) | Jul 16, 2022 |
| HP       | 3397                        | [7d3b738672](https://linux-hardware.org/?probe=7d3b738672) | Jul 14, 2022 |
| ASUSTek  | TUF Gaming B560-PLUS WIF... | [fa17eccd81](https://linux-hardware.org/?probe=fa17eccd81) | Jul 04, 2022 |
| ASUSTek  | PRIME Z690-P                | [6302e38583](https://linux-hardware.org/?probe=6302e38583) | Jun 22, 2022 |
| ASUSTek  | PRIME Z690-P                | [ce610351c3](https://linux-hardware.org/?probe=ce610351c3) | Jun 03, 2022 |
| ASUSTek  | PRIME Z690-P                | [1e0c1bed2a](https://linux-hardware.org/?probe=1e0c1bed2a) | Jun 02, 2022 |
| MSI      | B450M-A PRO MAX             | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| Dell     | 0WR7PY A01                  | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| MSI      | Z87-G43                     | [d5612db7ca](https://linux-hardware.org/?probe=d5612db7ca) | May 02, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| ASRock   | X570 Pro4                   | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| ASRock   | TRX40 Taichi                | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| MSI      | B550M PRO                   | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
| Gigabyte | B450M DS3H-CF               | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Gigabyte | B550M AORUS PRO-P           | [61374a4048](https://linux-hardware.org/?probe=61374a4048) | Jan 25, 2022 |
| ASUSTek  | PRIME X470-PRO              | [24fedcca0a](https://linux-hardware.org/?probe=24fedcca0a) | Jan 18, 2022 |
| MSI      | B450M-A PRO MAX             | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI      | B450M-A PRO MAX             | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| Gigabyte | B450M DS3H-CF               | [093a7d451a](https://linux-hardware.org/?probe=093a7d451a) | Oct 16, 2021 |
| Gigabyte | B450M DS3H-CF               | [7917f7d57f](https://linux-hardware.org/?probe=7917f7d57f) | Oct 12, 2021 |
| Gigabyte | H310M M.2 x.x               | [6ad302377d](https://linux-hardware.org/?probe=6ad302377d) | Sep 30, 2021 |
| MSI      | B450 TOMAHAWK MAX II        | [a0d3015e21](https://linux-hardware.org/?probe=a0d3015e21) | Sep 15, 2021 |
| ASUSTek  | M4A89GTD-PRO/USB3           | [d3c1b5c10c](https://linux-hardware.org/?probe=d3c1b5c10c) | Sep 11, 2021 |
| ASUSTek  | ROG CROSSHAIR VII HERO      | [bc2b986f06](https://linux-hardware.org/?probe=bc2b986f06) | Aug 19, 2021 |
| ASUSTek  | ROG CROSSHAIR VII HERO      | [85d1c86c68](https://linux-hardware.org/?probe=85d1c86c68) | Aug 19, 2021 |
| Dell     | 03NVJ6 A02                  | [5dec53ee3f](https://linux-hardware.org/?probe=5dec53ee3f) | Jul 26, 2021 |
| ASRock   | J4005B-ITX                  | [053a28a1b7](https://linux-hardware.org/?probe=053a28a1b7) | Jun 13, 2021 |
| ASRock   | H61M-VG4                    | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| ASRock   | H61M-VG4                    | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| ASUSTek  | M5A78L-M LX                 | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek  | M5A78L-M LX                 | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| ASRock   | B450 Pro4                   | [42d648695d](https://linux-hardware.org/?probe=42d648695d) | Mar 26, 2021 |
| Unknown  | Unknown                     | [35af7cfd3d](https://linux-hardware.org/?probe=35af7cfd3d) | Feb 22, 2021 |
| ASRock   | B450 Pro4                   | [09b0e87eec](https://linux-hardware.org/?probe=09b0e87eec) | Feb 12, 2021 |
| ASUSTek  | PRIME Z390-P                | [5d02f20d1d](https://linux-hardware.org/?probe=5d02f20d1d) | Feb 10, 2021 |
| MSI      | MPG B550I GAMING EDGE WI... | [624f71f228](https://linux-hardware.org/?probe=624f71f228) | Jan 21, 2021 |
| ASUSTek  | PRIME Z390-P                | [73c3fdc605](https://linux-hardware.org/?probe=73c3fdc605) | Jan 16, 2021 |
| ASUSTek  | PRIME Z270-AR               | [35d08fe710](https://linux-hardware.org/?probe=35d08fe710) | Dec 30, 2020 |
| MSI      | MPG B550I GAMING EDGE WI... | [1f66d0eb72](https://linux-hardware.org/?probe=1f66d0eb72) | Dec 22, 2020 |
| MSI      | MPG B550I GAMING EDGE WI... | [61887011a6](https://linux-hardware.org/?probe=61887011a6) | Dec 22, 2020 |
| ASUSTek  | B150M PRO GAMING            | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| ASUSTek  | B150M PRO GAMING            | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| ASUSTek  | H110M-PLUS                  | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| ASUSTek  | PRIME B360M-A               | [438477ec85](https://linux-hardware.org/?probe=438477ec85) | Nov 14, 2020 |
| ASUSTek  | PRIME B360M-A               | [ac5adde915](https://linux-hardware.org/?probe=ac5adde915) | Nov 13, 2020 |
| ASRock   | 970 Pro3 R2.0               | [d889341667](https://linux-hardware.org/?probe=d889341667) | Oct 28, 2020 |
| MSI      | Z270 TOMAHAWK               | [66f15fef73](https://linux-hardware.org/?probe=66f15fef73) | Sep 28, 2020 |
| ASUSTek  | P8Z77-V LX2                 | [ee56035e75](https://linux-hardware.org/?probe=ee56035e75) | Sep 24, 2020 |
| ASUSTek  | P8H67-V                     | [9bc61b31d4](https://linux-hardware.org/?probe=9bc61b31d4) | Sep 02, 2020 |
| Gigabyte | GA-78LMT-S2                 | [efac4b3e2b](https://linux-hardware.org/?probe=efac4b3e2b) | May 25, 2020 |
| Dell     | 0H8052                      | [18169ce984](https://linux-hardware.org/?probe=18169ce984) | Jan 29, 2020 |
| Unknown  | Unknown                     | [b9eb4a5652](https://linux-hardware.org/?probe=b9eb4a5652) | Jan 24, 2020 |
| Unknown  | Unknown                     | [ac87dc43f3](https://linux-hardware.org/?probe=ac87dc43f3) | Jan 24, 2020 |
| ASUSTek  | H110M-PLUS                  | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| ASRock   | AB350M                      | [1ec4015426](https://linux-hardware.org/?probe=1ec4015426) | Sep 01, 2019 |
| ASRock   | N68-S3 FX                   | [69e86c050b](https://linux-hardware.org/?probe=69e86c050b) | Aug 18, 2019 |
| ASRock   | N68-S3 FX                   | [ef4f02af88](https://linux-hardware.org/?probe=ef4f02af88) | Aug 16, 2019 |
| ASUSTek  | Z97-A                       | [c2458d18f6](https://linux-hardware.org/?probe=c2458d18f6) | Aug 03, 2019 |
| MSI      | B350M GAMING PRO            | [20e1f5d7a1](https://linux-hardware.org/?probe=20e1f5d7a1) | Apr 17, 2019 |
| ASUSTek  | PRIME A320M-K/BR            | [1b0a4407c7](https://linux-hardware.org/?probe=1b0a4407c7) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Void Linux Rolling | 65       | 77.38%  |
| Void Linux         | 19       | 22.62%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Void Linux | 82       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Desktops | Percent |
|-----------------|----------|---------|
| 6.6.8_1         | 3        | 3.3%    |
| 6.6.31_1        | 3        | 3.3%    |
| 6.6.11_1        | 3        | 3.3%    |
| 6.3.12_1        | 3        | 3.3%    |
| 6.6.35_1        | 2        | 2.2%    |
| 6.6.21_1        | 2        | 2.2%    |
| 6.5.9_1         | 2        | 2.2%    |
| 6.3.13_1        | 2        | 2.2%    |
| 6.1.31_1        | 2        | 2.2%    |
| 6.0.13_1        | 2        | 2.2%    |
| 5.8.18_1        | 2        | 2.2%    |
| 5.18.9_1        | 2        | 2.2%    |
| 5.16.20_1       | 2        | 2.2%    |
| 5.13.19_1       | 2        | 2.2%    |
| 5.11.9_1        | 2        | 2.2%    |
| 5.10.14_1       | 2        | 2.2%    |
| 6.8.1_1         | 1        | 1.1%    |
| 6.7.9_1         | 1        | 1.1%    |
| 6.7.0-xanmod1_1 | 1        | 1.1%    |
| 6.6.59_1        | 1        | 1.1%    |
| 6.6.52_1        | 1        | 1.1%    |
| 6.6.48_1        | 1        | 1.1%    |
| 6.6.32_1        | 1        | 1.1%    |
| 6.6.20_1        | 1        | 1.1%    |
| 6.6.1_1         | 1        | 1.1%    |
| 6.6.17_1        | 1        | 1.1%    |
| 6.5.7_1         | 1        | 1.1%    |
| 6.5.6_1         | 1        | 1.1%    |
| 6.5.5_2         | 1        | 1.1%    |
| 6.5.13_1        | 1        | 1.1%    |
| 6.5.11_1        | 1        | 1.1%    |
| 6.11.9_1        | 1        | 1.1%    |
| 6.1.4_1         | 1        | 1.1%    |
| 6.1.12_1        | 1        | 1.1%    |
| 6.1.114_2       | 1        | 1.1%    |
| 5.9.14_1        | 1        | 1.1%    |
| 5.8.5_1         | 1        | 1.1%    |
| 5.8.16_1        | 1        | 1.1%    |
| 5.8.11_1        | 1        | 1.1%    |
| 5.8.10_1        | 1        | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6.8   | 3        | 3.3%    |
| 6.6.31  | 3        | 3.3%    |
| 6.6.11  | 3        | 3.3%    |
| 6.3.12  | 3        | 3.3%    |
| 6.6.35  | 2        | 2.2%    |
| 6.6.21  | 2        | 2.2%    |
| 6.5.9   | 2        | 2.2%    |
| 6.3.13  | 2        | 2.2%    |
| 6.1.31  | 2        | 2.2%    |
| 6.0.13  | 2        | 2.2%    |
| 5.8.18  | 2        | 2.2%    |
| 5.18.9  | 2        | 2.2%    |
| 5.16.20 | 2        | 2.2%    |
| 5.13.19 | 2        | 2.2%    |
| 5.11.9  | 2        | 2.2%    |
| 5.10.14 | 2        | 2.2%    |
| 6.8.1   | 1        | 1.1%    |
| 6.7.9   | 1        | 1.1%    |
| 6.7.0   | 1        | 1.1%    |
| 6.6.59  | 1        | 1.1%    |
| 6.6.52  | 1        | 1.1%    |
| 6.6.48  | 1        | 1.1%    |
| 6.6.32  | 1        | 1.1%    |
| 6.6.20  | 1        | 1.1%    |
| 6.6.17  | 1        | 1.1%    |
| 6.6.1   | 1        | 1.1%    |
| 6.5.7   | 1        | 1.1%    |
| 6.5.6   | 1        | 1.1%    |
| 6.5.5   | 1        | 1.1%    |
| 6.5.13  | 1        | 1.1%    |
| 6.5.11  | 1        | 1.1%    |
| 6.11.9  | 1        | 1.1%    |
| 6.1.4   | 1        | 1.1%    |
| 6.1.12  | 1        | 1.1%    |
| 6.1.114 | 1        | 1.1%    |
| 5.9.14  | 1        | 1.1%    |
| 5.8.5   | 1        | 1.1%    |
| 5.8.16  | 1        | 1.1%    |
| 5.8.11  | 1        | 1.1%    |
| 5.8.10  | 1        | 1.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6     | 19       | 21.35%  |
| 5.15    | 9        | 10.11%  |
| 6.5     | 7        | 7.87%   |
| 5.10    | 7        | 7.87%   |
| 5.8     | 6        | 6.74%   |
| 6.3     | 5        | 5.62%   |
| 5.18    | 5        | 5.62%   |
| 5.13    | 5        | 5.62%   |
| 6.1     | 4        | 4.49%   |
| 4.19    | 4        | 4.49%   |
| 5.11    | 3        | 3.37%   |
| 6.7     | 2        | 2.25%   |
| 6.0     | 2        | 2.25%   |
| 5.4     | 2        | 2.25%   |
| 5.16    | 2        | 2.25%   |
| 5.12    | 2        | 2.25%   |
| 6.8     | 1        | 1.12%   |
| 6.11    | 1        | 1.12%   |
| 5.9     | 1        | 1.12%   |
| 5.6     | 1        | 1.12%   |
| 5.3     | 1        | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 79       | 96.34%  |
| ppc64le | 1        | 1.22%   |
| ppc64   | 1        | 1.22%   |
| i686    | 1        | 1.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 35       | 40.7%   |
| XFCE         | 18       | 20.93%  |
| KDE5         | 8        | 9.3%    |
| sway         | 6        | 6.98%   |
| GNOME        | 6        | 6.98%   |
| KDE          | 3        | 3.49%   |
| X-Cinnamon   | 2        | 2.33%   |
| X-Generic    | 1        | 1.16%   |
| river        | 1        | 1.16%   |
| openbox      | 1        | 1.16%   |
| Lumina       | 1        | 1.16%   |
| i3-with-dbus | 1        | 1.16%   |
| Hyprland     | 1        | 1.16%   |
| bspwm        | 1        | 1.16%   |
| awesome      | 1        | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 57       | 66.28%  |
| Wayland | 15       | 17.44%  |
| Tty     | 8        | 9.3%    |
| Unknown | 6        | 6.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 65       | 76.47%  |
| LightDM | 7        | 8.24%   |
| SDDM    | 6        | 7.06%   |
| GDM     | 5        | 5.88%   |
| LXDM    | 2        | 2.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 40       | 45.98%  |
| Unknown     | 14       | 16.09%  |
| ru_RU       | 5        | 5.75%   |
| fr_FR       | 4        | 4.6%    |
| en_GB       | 4        | 4.6%    |
| pl_PL       | 3        | 3.45%   |
| en_CA       | 3        | 3.45%   |
| pt_BR       | 2        | 2.3%    |
| de_DE       | 2        | 2.3%    |
| cs_CZ       | 2        | 2.3%    |
| hu_HU       | 1        | 1.15%   |
| es_CL       | 1        | 1.15%   |
| en_US.utf-8 | 1        | 1.15%   |
| en_IE       | 1        | 1.15%   |
| en_DK       | 1        | 1.15%   |
| en_AU       | 1        | 1.15%   |
| el_GR       | 1        | 1.15%   |
| bg_BG       | 1        | 1.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 50       | 58.82%  |
| EFI  | 35       | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 48       | 55.81%  |
| Btrfs   | 21       | 24.42%  |
| Xfs     | 7        | 8.14%   |
| Zfs     | 6        | 6.98%   |
| Unknown | 2        | 2.33%   |
| Overlay | 1        | 1.16%   |
| F2fs    | 1        | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 41       | 48.81%  |
| Unknown | 30       | 35.71%  |
| MBR     | 13       | 15.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 85.54%  |
| Yes       | 12       | 14.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 73.81%  |
| Yes       | 22       | 26.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 25       | 30.49%  |
| Gigabyte Technology | 14       | 17.07%  |
| MSI                 | 13       | 15.85%  |
| ASRock              | 11       | 13.41%  |
| Dell                | 7        | 8.54%   |
| Hewlett-Packard     | 5        | 6.1%    |
| Unknown             | 4        | 4.88%   |
| Shuttle             | 1        | 1.22%   |
| EVGA                | 1        | 1.22%   |
| AMI                 | 1        | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 5        | 6.1%    |
| MSI MS-7C02                      | 2        | 2.44%   |
| Dell OptiPlex 780                | 2        | 2.44%   |
| Dell OptiPlex 7010               | 2        | 2.44%   |
| ASUS PRIME Z390-P                | 2        | 2.44%   |
| ASRock B450 Pro4                 | 2        | 2.44%   |
| Shuttle DH170                    | 1        | 1.22%   |
| MSI MS-7D95                      | 1        | 1.22%   |
| MSI MS-7D14                      | 1        | 1.22%   |
| MSI MS-7C92                      | 1        | 1.22%   |
| MSI MS-7C56                      | 1        | 1.22%   |
| MSI MS-7C52                      | 1        | 1.22%   |
| MSI MS-7C35                      | 1        | 1.22%   |
| MSI MS-7B86                      | 1        | 1.22%   |
| MSI MS-7A68                      | 1        | 1.22%   |
| MSI MS-7A39                      | 1        | 1.22%   |
| MSI MS-7816                      | 1        | 1.22%   |
| MSI MS-7610                      | 1        | 1.22%   |
| HP Z400 Workstation              | 1        | 1.22%   |
| HP EliteDesk 800 G5 Desktop Mini | 1        | 1.22%   |
| HP EliteDesk 800 G1 SFF          | 1        | 1.22%   |
| HP Compaq Pro 4300 SFF PC        | 1        | 1.22%   |
| HP Compaq Elite 8300 SFF         | 1        | 1.22%   |
| Gigabyte Z97X-UD7 TH             | 1        | 1.22%   |
| Gigabyte Z790 AORUS MASTER X     | 1        | 1.22%   |
| Gigabyte Z690I A ULTRA LITE D4   | 1        | 1.22%   |
| Gigabyte Z68XP-UD3               | 1        | 1.22%   |
| Gigabyte Z370 AORUS Gaming 3     | 1        | 1.22%   |
| Gigabyte X570S UD                | 1        | 1.22%   |
| Gigabyte X570 AORUS MASTER       | 1        | 1.22%   |
| Gigabyte H310M S2H 2.0           | 1        | 1.22%   |
| Gigabyte H310M M.2 2.0           | 1        | 1.22%   |
| Gigabyte GB-BRi5(H)-8250         | 1        | 1.22%   |
| Gigabyte GA-78LMT-S2             | 1        | 1.22%   |
| Gigabyte B550M AORUS PRO-P       | 1        | 1.22%   |
| Gigabyte B550 AORUS ELITE V2     | 1        | 1.22%   |
| Gigabyte B450M DS3H              | 1        | 1.22%   |
| EVGA Z790 DARK KINGPIN           | 1        | 1.22%   |
| Dell OptiPlex GX520              | 1        | 1.22%   |
| Dell OptiPlex 380                | 1        | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME               | 10       | 12.2%   |
| Dell OptiPlex            | 6        | 7.32%   |
| Unknown                  | 5        | 6.1%    |
| ASUS ROG                 | 3        | 3.66%   |
| MSI MS-7C02              | 2        | 2.44%   |
| HP EliteDesk             | 2        | 2.44%   |
| HP Compaq                | 2        | 2.44%   |
| Gigabyte H310M           | 2        | 2.44%   |
| ASUS TUF                 | 2        | 2.44%   |
| ASRock B450              | 2        | 2.44%   |
| Shuttle DH170            | 1        | 1.22%   |
| MSI MS-7D95              | 1        | 1.22%   |
| MSI MS-7D14              | 1        | 1.22%   |
| MSI MS-7C92              | 1        | 1.22%   |
| MSI MS-7C56              | 1        | 1.22%   |
| MSI MS-7C52              | 1        | 1.22%   |
| MSI MS-7C35              | 1        | 1.22%   |
| MSI MS-7B86              | 1        | 1.22%   |
| MSI MS-7A68              | 1        | 1.22%   |
| MSI MS-7A39              | 1        | 1.22%   |
| MSI MS-7816              | 1        | 1.22%   |
| MSI MS-7610              | 1        | 1.22%   |
| HP Z400                  | 1        | 1.22%   |
| Gigabyte Z97X-UD7        | 1        | 1.22%   |
| Gigabyte Z790            | 1        | 1.22%   |
| Gigabyte Z690I           | 1        | 1.22%   |
| Gigabyte Z68XP-UD3       | 1        | 1.22%   |
| Gigabyte Z370            | 1        | 1.22%   |
| Gigabyte X570S           | 1        | 1.22%   |
| Gigabyte X570            | 1        | 1.22%   |
| Gigabyte GB-BRi5(H)-8250 | 1        | 1.22%   |
| Gigabyte GA-78LMT-S2     | 1        | 1.22%   |
| Gigabyte B550M           | 1        | 1.22%   |
| Gigabyte B550            | 1        | 1.22%   |
| Gigabyte B450M           | 1        | 1.22%   |
| EVGA Z790                | 1        | 1.22%   |
| Dell Inspiron            | 1        | 1.22%   |
| ASUS P8Z77-V             | 1        | 1.22%   |
| ASUS P8H67-V             | 1        | 1.22%   |
| ASUS Maximus             | 1        | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 14       | 17.07%  |
| 2019    | 10       | 12.2%   |
| 2021    | 9        | 10.98%  |
| 2020    | 8        | 9.76%   |
| 2017    | 7        | 8.54%   |
| 2012    | 6        | 7.32%   |
| 2013    | 5        | 6.1%    |
| 2011    | 4        | 4.88%   |
| 2010    | 4        | 4.88%   |
| 2023    | 3        | 3.66%   |
| 2022    | 2        | 2.44%   |
| 2009    | 2        | 2.44%   |
| Unknown | 2        | 2.44%   |
| 2024    | 1        | 1.22%   |
| 2016    | 1        | 1.22%   |
| 2015    | 1        | 1.22%   |
| 2014    | 1        | 1.22%   |
| 2008    | 1        | 1.22%   |
| 2005    | 1        | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 82       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 81       | 98.78%  |
| Enabled  | 1        | 1.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 82       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 26       | 31.33%  |
| 32.01-64.0      | 19       | 22.89%  |
| 8.01-16.0       | 15       | 18.07%  |
| 4.01-8.0        | 9        | 10.84%  |
| 64.01-256.0     | 5        | 6.02%   |
| 3.01-4.0        | 4        | 4.82%   |
| 2.01-3.0        | 2        | 2.41%   |
| More than 256.0 | 1        | 1.2%    |
| 24.01-32.0      | 1        | 1.2%    |
| 1.01-2.0        | 1        | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 20       | 22.47%  |
| 4.01-8.0    | 16       | 17.98%  |
| 3.01-4.0    | 16       | 17.98%  |
| 1.01-2.0    | 14       | 15.73%  |
| 8.01-16.0   | 11       | 12.36%  |
| 0.51-1.0    | 7        | 7.87%   |
| 64.01-256.0 | 2        | 2.25%   |
| 0.01-0.5    | 2        | 2.25%   |
| 16.01-24.0  | 1        | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 32.14%  |
| 3      | 23       | 27.38%  |
| 1      | 22       | 26.19%  |
| 4      | 8        | 9.52%   |
| 5      | 2        | 2.38%   |
| 9      | 1        | 1.19%   |
| 7      | 1        | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 81.71%  |
| Yes       | 15       | 18.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 81       | 98.78%  |
| No        | 1        | 1.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 59.04%  |
| Yes       | 34       | 40.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 66.27%  |
| Yes       | 28       | 33.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 22       | 26.83%  |
| Germany     | 7        | 8.54%   |
| Poland      | 6        | 7.32%   |
| UK          | 5        | 6.1%    |
| Russia      | 5        | 6.1%    |
| Brazil      | 5        | 6.1%    |
| France      | 4        | 4.88%   |
| Czechia     | 4        | 4.88%   |
| Netherlands | 3        | 3.66%   |
| Greece      | 3        | 3.66%   |
| Canada      | 3        | 3.66%   |
| Finland     | 2        | 2.44%   |
| Turkey      | 1        | 1.22%   |
| Sweden      | 1        | 1.22%   |
| Spain       | 1        | 1.22%   |
| Pakistan    | 1        | 1.22%   |
| Italy       | 1        | 1.22%   |
| India       | 1        | 1.22%   |
| Hungary     | 1        | 1.22%   |
| Chile       | 1        | 1.22%   |
| Bulgaria    | 1        | 1.22%   |
| Belgium     | 1        | 1.22%   |
| Bangladesh  | 1        | 1.22%   |
| Australia   | 1        | 1.22%   |
| Argentina   | 1        | 1.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Prague               | 3        | 3.53%   |
| Denver               | 3        | 3.53%   |
| Vancouver            | 2        | 2.35%   |
| Munich               | 2        | 2.35%   |
| Lublin               | 2        | 2.35%   |
| Kenmore              | 2        | 2.35%   |
| Amsterdam            | 2        | 2.35%   |
| Zagnansk             | 1        | 1.18%   |
| Yekaterinburg        | 1        | 1.18%   |
| Worthing             | 1        | 1.18%   |
| Winnipeg             | 1        | 1.18%   |
| Warsaw               | 1        | 1.18%   |
| Varna                | 1        | 1.18%   |
| Toulouse             | 1        | 1.18%   |
| Taranto              | 1        | 1.18%   |
| Steinbach-Hallenberg | 1        | 1.18%   |
| South Shields        | 1        | 1.18%   |
| Sofia                | 1        | 1.18%   |
| Savannah             | 1        | 1.18%   |
| San Antonio          | 1        | 1.18%   |
| Saint-Paul-les-Dax   | 1        | 1.18%   |
| Saint Paul           | 1        | 1.18%   |
| Saarbrücken         | 1        | 1.18%   |
| Rotherham            | 1        | 1.18%   |
| Rosario              | 1        | 1.18%   |
| Rio de Janeiro       | 1        | 1.18%   |
| Richmond             | 1        | 1.18%   |
| Pyatigorsk           | 1        | 1.18%   |
| Pelabravo            | 1        | 1.18%   |
| Pardubice            | 1        | 1.18%   |
| Oulu                 | 1        | 1.18%   |
| Orlando              | 1        | 1.18%   |
| Odessa               | 1        | 1.18%   |
| Nizhniy Novgorod     | 1        | 1.18%   |
| Newmarket            | 1        | 1.18%   |
| New York             | 1        | 1.18%   |
| New Bedford          | 1        | 1.18%   |
| Muhos                | 1        | 1.18%   |
| Moscow               | 1        | 1.18%   |
| Monaca               | 1        | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 33       | 56     | 20.25%  |
| WDC                         | 27       | 40     | 16.56%  |
| Seagate                     | 24       | 35     | 14.72%  |
| Kingston                    | 13       | 14     | 7.98%   |
| Sandisk                     | 11       | 14     | 6.75%   |
| Crucial                     | 6        | 7      | 3.68%   |
| Toshiba                     | 5        | 6      | 3.07%   |
| Hitachi                     | 5        | 5      | 3.07%   |
| SK hynix                    | 3        | 6      | 1.84%   |
| Phison Electronics          | 3        | 3      | 1.84%   |
| Intel                       | 3        | 4      | 1.84%   |
| A-DATA Technology           | 3        | 5      | 1.84%   |
| SPCC                        | 2        | 2      | 1.23%   |
| Realtek Semiconductor       | 2        | 2      | 1.23%   |
| Micron/Crucial Technology   | 2        | 2      | 1.23%   |
| HGST                        | 2        | 2      | 1.23%   |
| Corsair                     | 2        | 2      | 1.23%   |
| XPG                         | 1        | 4      | 0.61%   |
| Unknown                     | 1        | 1      | 0.61%   |
| Phison                      | 1        | 1      | 0.61%   |
| Patriot                     | 1        | 1      | 0.61%   |
| OCZ                         | 1        | 1      | 0.61%   |
| NGFF                        | 1        | 1      | 0.61%   |
| Maxtor                      | 1        | 1      | 0.61%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.61%   |
| LITEONIT                    | 1        | 1      | 0.61%   |
| Kingston Technology Company | 1        | 2      | 0.61%   |
| JMicron Technology          | 1        | 1      | 0.61%   |
| Intenso                     | 1        | 1      | 0.61%   |
| HS-SSD-E100                 | 1        | 1      | 0.61%   |
| Gigabyte Technology         | 1        | 2      | 0.61%   |
| BIWIN                       | 1        | 1      | 0.61%   |
| AMD                         | 1        | 1      | 0.61%   |
| AGI                         | 1        | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 8        | 4.23%   |
| Kingston SA400S37240G 240GB SSD                      | 6        | 3.17%   |
| Seagate ST2000DM008-2FR102 2TB                       | 5        | 2.65%   |
| Seagate ST1000DM010-2EP102 1TB                       | 5        | 2.65%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 3        | 1.59%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 3        | 1.59%   |
| Samsung SSD 870 QVO 1TB                              | 3        | 1.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 2        | 1.06%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 2        | 1.06%   |
| Toshiba DT01ACA050 500GB                             | 2        | 1.06%   |
| SK hynix SHPP41-2000GM 2TB                           | 2        | 1.06%   |
| Seagate ST1000DM003-1CH162 1TB                       | 2        | 1.06%   |
| Samsung SSD 980 PRO 500GB                            | 2        | 1.06%   |
| Samsung SSD 970 EVO Plus 1TB                         | 2        | 1.06%   |
| Samsung SSD 870 EVO 500GB                            | 2        | 1.06%   |
| Samsung SSD 870 EVO 1TB                              | 2        | 1.06%   |
| Samsung SSD 860 EVO 500GB                            | 2        | 1.06%   |
| Samsung NVMe SSD Drive 500GB                         | 2        | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 2        | 1.06%   |
| Phison E12 NVMe Controller 480GB                     | 2        | 1.06%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 2        | 1.06%   |
| Kingston SV300S37A120G 120GB SSD                     | 2        | 1.06%   |
| Kingston SHFS37A120G 120GB SSD                       | 2        | 1.06%   |
| Intel SSDSC2BW240H6 240GB                            | 2        | 1.06%   |
| XPG NVMe SSD Drive 2TB                               | 1        | 0.53%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                     | 1        | 0.53%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 1        | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 1        | 0.53%   |
| WDC WD7500AYYS-01RCA0 752GB                          | 1        | 0.53%   |
| WDC WD60EZAZ-00SF3B0 6TB                             | 1        | 0.53%   |
| WDC WD5003ABYZ-011FA0 500GB                          | 1        | 0.53%   |
| WDC WD5000AAKX-60U6AA0 500GB                         | 1        | 0.53%   |
| WDC WD5000AADS-00S9B0 500GB                          | 1        | 0.53%   |
| WDC WD2500AAKX-603CA0 250GB                          | 1        | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 1        | 0.53%   |
| WDC WD20EZBX-00AYRA0 2TB                             | 1        | 0.53%   |
| WDC WD20EFRX-68EUZN0 2TB                             | 1        | 0.53%   |
| WDC WD2003FZEX-00Z4SA0 2TB                           | 1        | 0.53%   |
| WDC WD1600AAJS-60PSA0 160GB                          | 1        | 0.53%   |
| WDC WD15EARS-00MVWB0 1TB                             | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 35     | 35.82%  |
| WDC                 | 23       | 33     | 34.33%  |
| Samsung Electronics | 6        | 7      | 8.96%   |
| Toshiba             | 5        | 6      | 7.46%   |
| Hitachi             | 5        | 5      | 7.46%   |
| HGST                | 2        | 2      | 2.99%   |
| Maxtor              | 1        | 1      | 1.49%   |
| JMicron Technology  | 1        | 1      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 18     | 25.42%  |
| Kingston            | 13       | 14     | 22.03%  |
| WDC                 | 6        | 7      | 10.17%  |
| SanDisk             | 4        | 5      | 6.78%   |
| Crucial             | 4        | 5      | 6.78%   |
| SPCC                | 2        | 2      | 3.39%   |
| Intel               | 2        | 2      | 3.39%   |
| A-DATA Technology   | 2        | 4      | 3.39%   |
| Patriot             | 1        | 1      | 1.69%   |
| OCZ                 | 1        | 1      | 1.69%   |
| NGFF                | 1        | 1      | 1.69%   |
| LITEONIT            | 1        | 1      | 1.69%   |
| Intenso             | 1        | 1      | 1.69%   |
| HS-SSD-E100         | 1        | 1      | 1.69%   |
| Gigabyte Technology | 1        | 2      | 1.69%   |
| Corsair             | 1        | 1      | 1.69%   |
| BIWIN               | 1        | 1      | 1.69%   |
| AMD                 | 1        | 1      | 1.69%   |
| AGI                 | 1        | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 53       | 90     | 37.86%  |
| SSD  | 49       | 69     | 35%     |
| NVMe | 37       | 67     | 26.43%  |
| MMC  | 1        | 1      | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 72       | 156    | 64.29%  |
| NVMe | 37       | 67     | 33.04%  |
| SAS  | 2        | 3      | 1.79%   |
| MMC  | 1        | 1      | 0.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 55       | 79     | 50.46%  |
| 0.51-1.0   | 33       | 47     | 30.28%  |
| 1.01-2.0   | 16       | 23     | 14.68%  |
| 3.01-4.0   | 3        | 8      | 2.75%   |
| 4.01-10.0  | 2        | 2      | 1.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 18       | 20.93%  |
| 101-250        | 16       | 18.6%   |
| 501-1000       | 13       | 15.12%  |
| 251-500        | 12       | 13.95%  |
| More than 3000 | 10       | 11.63%  |
| 2001-3000      | 6        | 6.98%   |
| Unknown        | 6        | 6.98%   |
| 1-20           | 4        | 4.65%   |
| 51-100         | 1        | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 20       | 21.98%  |
| 251-500        | 13       | 14.29%  |
| 101-250        | 11       | 12.09%  |
| 1001-2000      | 11       | 12.09%  |
| 501-1000       | 10       | 10.99%  |
| 21-50          | 8        | 8.79%   |
| 51-100         | 8        | 8.79%   |
| Unknown        | 6        | 6.59%   |
| More than 3000 | 3        | 3.3%    |
| 2001-3000      | 1        | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Desktops | Drives | Percent |
|-----------------------------------------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB                               | 1        | 2      | 4.35%   |
| WDC WD2003FZEX-00Z4SA0 2TB                                | 1        | 1      | 4.35%   |
| WDC WD10EZEX-08WN4A0 1TB                                  | 1        | 1      | 4.35%   |
| Toshiba MQ04ABF100 1TB                                    | 1        | 2      | 4.35%   |
| Seagate ST9500325AS 500GB                                 | 1        | 1      | 4.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB                       | 1        | 1      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB                           | 1        | 1      | 4.35%   |
| Seagate ST4000VN008-2DR166 4TB                            | 1        | 1      | 4.35%   |
| Seagate ST4000VN000-1H4168 4TB                            | 1        | 2      | 4.35%   |
| Seagate ST3750330AS 752GB                                 | 1        | 1      | 4.35%   |
| Seagate ST3250410AS 250GB                                 | 1        | 1      | 4.35%   |
| Seagate ST2000VX000-1CU164 2TB                            | 1        | 2      | 4.35%   |
| Seagate ST2000DM001-1CH164 2TB                            | 1        | 1      | 4.35%   |
| SanDisk SSD U100 256GB                                    | 1        | 1      | 4.35%   |
| SanDisk SSD PLUS 240GB                                    | 1        | 1      | 4.35%   |
| Samsung Electronics HM160HI 160GB                         | 1        | 1      | 4.35%   |
| Samsung Electronics HD502HJ 500GB                         | 1        | 1      | 4.35%   |
| Samsung Electronics HD322HJ 320GB                         | 1        | 1      | 4.35%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB | 1        | 1      | 4.35%   |
| Hitachi HUA722010CLA330 1TB                               | 1        | 1      | 4.35%   |
| Hitachi HTS545050B9A300 500GB                             | 1        | 1      | 4.35%   |
| Crucial CT525MX300SSD1 528GB                              | 1        | 1      | 4.35%   |
| A-DATA Technology SU700 120GB SSD                         | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 8        | 11     | 36.36%  |
| WDC                   | 3        | 4      | 13.64%  |
| Samsung Electronics   | 3        | 3      | 13.64%  |
| SanDisk               | 2        | 2      | 9.09%   |
| Hitachi               | 2        | 2      | 9.09%   |
| Toshiba               | 1        | 2      | 4.55%   |
| Realtek Semiconductor | 1        | 1      | 4.55%   |
| Crucial               | 1        | 1      | 4.55%   |
| A-DATA Technology     | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 11     | 47.06%  |
| WDC                 | 3        | 4      | 17.65%  |
| Samsung Electronics | 3        | 3      | 17.65%  |
| Hitachi             | 2        | 2      | 11.76%  |
| Toshiba             | 1        | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 22     | 76.19%  |
| SSD  | 4        | 4      | 19.05%  |
| NVMe | 1        | 1      | 4.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Intel SSDSC2BW240H6 240GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| Intel  | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 47       | 100    | 45.19%  |
| Detected | 38       | 99     | 36.54%  |
| Malfunc  | 18       | 27     | 17.31%  |
| Failed   | 1        | 1      | 0.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 44       | 33.33%  |
| AMD                         | 35       | 26.52%  |
| Samsung Electronics         | 18       | 13.64%  |
| SanDisk                     | 7        | 5.3%    |
| Phison Electronics          | 5        | 3.79%   |
| ASMedia Technology          | 5        | 3.79%   |
| SK hynix                    | 3        | 2.27%   |
| Micron/Crucial Technology   | 3        | 2.27%   |
| Marvell Technology Group    | 3        | 2.27%   |
| Realtek Semiconductor       | 2        | 1.52%   |
| ADATA Technology            | 2        | 1.52%   |
| Nvidia                      | 1        | 0.76%   |
| MAXIO Technology (Hangzhou) | 1        | 0.76%   |
| Kingston Technology Company | 1        | 0.76%   |
| JMicron Technology          | 1        | 0.76%   |
| Broadcom                    | 1        | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18       | 11.04%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14       | 8.59%   |
| AMD 400 Series Chipset SATA Controller                                         | 12       | 7.36%   |
| AMD 500 Series Chipset SATA Controller                                         | 9        | 5.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6        | 3.68%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 5        | 3.07%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 4        | 2.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 2.45%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4        | 2.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 2.45%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.84%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3        | 1.84%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3        | 1.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 1.84%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 1.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 1.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 1.84%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2        | 1.23%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2        | 1.23%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.23%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2        | 1.23%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 1.23%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.23%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2        | 1.23%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1        | 0.61%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1        | 0.61%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.61%   |
| SanDisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                      | 1        | 0.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1        | 0.61%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.61%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 1        | 0.61%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.61%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.61%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 0.61%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 71       | 55.91%  |
| NVMe | 37       | 29.13%  |
| IDE  | 12       | 9.45%   |
| RAID | 7        | 5.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 44       | 53.66%  |
| AMD                      | 36       | 43.9%   |
| PowerNV C1P9S01 REV 1.01 | 1        | 1.22%   |
| PowerMac11,2             | 1        | 1.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 6        | 7.32%   |
| Intel Core i9-14900K                               | 3        | 3.66%   |
| AMD Ryzen 7 5800X 8-Core Processor                 | 3        | 3.66%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 3        | 3.66%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2        | 2.44%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2        | 2.44%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 2        | 2.44%   |
| AMD Ryzen 7 5700G with Radeon Graphics             | 2        | 2.44%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 2        | 2.44%   |
| AMD Ryzen 5 3600X 6-Core Processor                 | 2        | 2.44%   |
| AMD FX-4300 Quad-Core Processor                    | 2        | 2.44%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1        | 1.22%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1        | 1.22%   |
| Intel Xeon CPU W3520 @ 2.67GHz                     | 1        | 1.22%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz                | 1        | 1.22%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1        | 1.22%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1        | 1.22%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1        | 1.22%   |
| Intel N100                                         | 1        | 1.22%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1        | 1.22%   |
| Intel Core i7-9700 CPU @ 3.00GHz                   | 1        | 1.22%   |
| Intel Core i7-8700 CPU @ 3.20GHz                   | 1        | 1.22%   |
| Intel Core i7-8086K CPU @ 4.00GHz                  | 1        | 1.22%   |
| Intel Core i7-7700 CPU @ 3.60GHz                   | 1        | 1.22%   |
| Intel Core i7-6700K CPU @ 4.00GHz                  | 1        | 1.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz                   | 1        | 1.22%   |
| Intel Core i5-8600K CPU @ 3.60GHz                  | 1        | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz                  | 1        | 1.22%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1        | 1.22%   |
| Intel Core i5-4670 CPU @ 3.40GHz                   | 1        | 1.22%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1        | 1.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz                   | 1        | 1.22%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1        | 1.22%   |
| Intel Core i5-2500 CPU @ 3.30GHz                   | 1        | 1.22%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1        | 1.22%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1        | 1.22%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1        | 1.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz                   | 1        | 1.22%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz              | 1        | 1.22%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz              | 1        | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 14       | 17.07%  |
| AMD Ryzen 7            | 12       | 14.63%  |
| Intel Core i5          | 10       | 12.2%   |
| Other                  | 8        | 9.76%   |
| Intel Core i7          | 8        | 9.76%   |
| Intel Core i9          | 4        | 4.88%   |
| Intel Core i3          | 4        | 4.88%   |
| AMD FX                 | 3        | 3.66%   |
| Intel Xeon             | 2        | 2.44%   |
| Intel Core 2 Quad      | 2        | 2.44%   |
| Intel Core 2 Duo       | 2        | 2.44%   |
| Intel Celeron          | 2        | 2.44%   |
| AMD Ryzen 9            | 2        | 2.44%   |
| Intel Pentium Gold     | 1        | 1.22%   |
| Intel Pentium 4        | 1        | 1.22%   |
| Intel Pentium          | 1        | 1.22%   |
| Intel Atom             | 1        | 1.22%   |
| AMD Ryzen Threadripper | 1        | 1.22%   |
| AMD Ryzen 3            | 1        | 1.22%   |
| AMD Phenom II X4       | 1        | 1.22%   |
| AMD Athlon II X3       | 1        | 1.22%   |
| AMD Athlon II X2       | 1        | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 25       | 30.49%  |
| 6      | 19       | 23.17%  |
| 8      | 15       | 18.29%  |
| 2      | 12       | 14.63%  |
| 24     | 3        | 3.66%   |
| 12     | 3        | 3.66%   |
| 1      | 2        | 2.44%   |
| 64     | 1        | 1.22%   |
| 16     | 1        | 1.22%   |
| 3      | 1        | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 55       | 67.07%  |
| 1      | 26       | 31.71%  |
| 4      | 1        | 1.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 78       | 95.12%  |
| Unknown        | 3        | 3.66%   |
| 32-bit         | 1        | 1.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 55.95%  |
| 0x306a9    | 3        | 3.57%   |
| 0x906e9    | 2        | 2.38%   |
| 0x506e3    | 2        | 2.38%   |
| 0x0a201009 | 2        | 2.38%   |
| 0x08701030 | 2        | 2.38%   |
| 0x08701021 | 2        | 2.38%   |
| 0x0800820d | 2        | 2.38%   |
| 0x06000852 | 2        | 2.38%   |
| 0x010000c8 | 2        | 2.38%   |
| 0xa0671    | 1        | 1.19%   |
| 0x906ed    | 1        | 1.19%   |
| 0x906ea    | 1        | 1.19%   |
| 0x90675    | 1        | 1.19%   |
| 0x90672    | 1        | 1.19%   |
| 0x706a1    | 1        | 1.19%   |
| 0x306c3    | 1        | 1.19%   |
| 0x1067a    | 1        | 1.19%   |
| 0x10677    | 1        | 1.19%   |
| 0x0a50000f | 1        | 1.19%   |
| 0x0a50000d | 1        | 1.19%   |
| 0x0a50000c | 1        | 1.19%   |
| 0x0a201205 | 1        | 1.19%   |
| 0x0a201204 | 1        | 1.19%   |
| 0x08701013 | 1        | 1.19%   |
| 0x08001138 | 1        | 1.19%   |
| 0x08001136 | 1        | 1.19%   |
| 0x08001129 | 1        | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 15       | 18.29%  |
| KabyLake         | 12       | 14.63%  |
| Zen 2            | 7        | 8.54%   |
| IvyBridge        | 7        | 8.54%   |
| Alderlake Hybrid | 6        | 7.32%   |
| Zen+             | 5        | 6.1%    |
| Penryn           | 4        | 4.88%   |
| Haswell          | 4        | 4.88%   |
| Zen              | 3        | 3.66%   |
| Piledriver       | 3        | 3.66%   |
| K10              | 3        | 3.66%   |
| Unknown          | 3        | 3.66%   |
| Skylake          | 2        | 2.44%   |
| Silvermont       | 1        | 1.22%   |
| SandyBridge      | 1        | 1.22%   |
| NetBurst         | 1        | 1.22%   |
| Nehalem          | 1        | 1.22%   |
| Icelake          | 1        | 1.22%   |
| Gracemont        | 1        | 1.22%   |
| Goldmont plus    | 1        | 1.22%   |
| Core             | 1        | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 38       | 42.22%  |
| AMD               | 33       | 36.67%  |
| Intel             | 18       | 20%     |
| ASPEED Technology | 1        | 1.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 6.38%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 4.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 4.26%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 3.19%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 3.19%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 3.19%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 3        | 3.19%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 2.13%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.13%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 2        | 2.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.13%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 2.13%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.13%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.06%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.06%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.06%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1.06%   |
| Nvidia NV43 [GeForce 6600]                                                  | 1        | 1.06%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.06%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.06%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.06%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.06%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.06%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.06%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.06%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.06%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 1.06%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.06%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 1.06%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.06%   |
| Nvidia AD106 [GeForce RTX 4060 Ti 16GB]                                     | 1        | 1.06%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 1        | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.06%   |
| Intel UHD Graphics 620                                                      | 1        | 1.06%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 35       | 40.7%   |
| 1 x AMD        | 29       | 33.72%  |
| 1 x Intel      | 14       | 16.28%  |
| 2 x Nvidia     | 2        | 2.33%   |
| Other          | 1        | 1.16%   |
| 2 x AMD        | 1        | 1.16%   |
| Intel + Nvidia | 1        | 1.16%   |
| Intel + AMD    | 1        | 1.16%   |
| AMD + Nvidia   | 1        | 1.16%   |
| AMD + ASPEED   | 1        | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 50       | 58.82%  |
| Proprietary | 34       | 40%     |
| Unknown     | 1        | 1.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 35.63%  |
| 7.01-8.0   | 14       | 16.09%  |
| 3.01-4.0   | 13       | 14.94%  |
| 1.01-2.0   | 9        | 10.34%  |
| 8.01-16.0  | 5        | 5.75%   |
| 5.01-6.0   | 4        | 4.6%    |
| 16.01-24.0 | 3        | 3.45%   |
| 0.51-1.0   | 3        | 3.45%   |
| 0.01-0.5   | 3        | 3.45%   |
| 2.01-3.0   | 2        | 2.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 15       | 16.13%  |
| Dell                 | 11       | 11.83%  |
| Goldstar             | 8        | 8.6%    |
| Hewlett-Packard      | 7        | 7.53%   |
| Acer                 | 6        | 6.45%   |
| Philips              | 4        | 4.3%    |
| AOC                  | 4        | 4.3%    |
| Ancor Communications | 4        | 4.3%    |
| Iiyama               | 3        | 3.23%   |
| BenQ                 | 3        | 3.23%   |
| ASUSTek Computer     | 3        | 3.23%   |
| MSI                  | 2        | 2.15%   |
| Lenovo               | 2        | 2.15%   |
| Fujitsu Siemens      | 2        | 2.15%   |
| Unknown              | 2        | 2.15%   |
| Vizio                | 1        | 1.08%   |
| ViewSonic            | 1        | 1.08%   |
| Unknown (XXX)        | 1        | 1.08%   |
| Unknown              | 1        | 1.08%   |
| Sceptre Tech         | 1        | 1.08%   |
| Sceptre              | 1        | 1.08%   |
| ONN                  | 1        | 1.08%   |
| NEC Computers        | 1        | 1.08%   |
| LG Electronics       | 1        | 1.08%   |
| KK@                  | 1        | 1.08%   |
| Idek Iiyama          | 1        | 1.08%   |
| Huion                | 1        | 1.08%   |
| Gigabyte Technology  | 1        | 1.08%   |
| FUN                  | 1        | 1.08%   |
| eMachines            | 1        | 1.08%   |
| Corsair              | 1        | 1.08%   |
| AXM                  | 1        | 1.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 1.96%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 1.96%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 2        | 1.96%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 1.96%   |
| Unknown                                                               | 2        | 1.96%   |
| Vizio E320-B2 VIZ0095 1360x768 477x268mm 21.5-inch                    | 1        | 0.98%   |
| ViewSonic LCD Monitor VX2457 1920x1080                                | 1        | 0.98%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1        | 0.98%   |
| Unknown (XXX) Beyond TV XXX9615 3840x2160 1210x680mm 54.6-inch        | 1        | 0.98%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch         | 1        | 0.98%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1        | 0.98%   |
| Samsung Electronics SMS22A350H SAM07D2 1920x1080 477x268mm 21.5-inch  | 1        | 0.98%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 0.98%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1        | 0.98%   |
| Samsung Electronics LCD Monitor LU28R55 3840x2160                     | 1        | 0.98%   |
| Samsung Electronics LCD Monitor LC49G95T 7040x1440                    | 1        | 0.98%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1        | 0.98%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1        | 0.98%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 1        | 0.98%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 532x304mm 24.1-inch    | 1        | 0.98%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 0.98%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1        | 0.98%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch               | 1        | 0.98%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1        | 0.98%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1        | 0.98%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1        | 0.98%   |
| NEC Computers E171M NEC6914 1280x1024 338x270mm 17.0-inch             | 1        | 0.98%   |
| LG Electronics LCD Monitor 27GL850                                    | 1        | 0.98%   |
| Lenovo LEN L220xwC LEN1151 1920x1200 474x296mm 22.0-inch              | 1        | 0.98%   |
| Lenovo LCD Monitor LEN1201 1920x1080 476x268mm 21.5-inch              | 1        | 0.98%   |
| KK@ LCM17BT35H KK@4B4B 1600x1200 611x398mm 28.7-inch                  | 1        | 0.98%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 1        | 0.98%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1        | 0.98%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 1        | 0.98%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 1        | 0.98%   |
| Idek Iiyama LCD Monitor PL3266Q 2560x1440                             | 1        | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 39       | 43.33%  |
| 3840x2160 (4K)     | 10       | 11.11%  |
| 2560x1440 (QHD)    | 9        | 10%     |
| 3440x1440          | 4        | 4.44%   |
| 1680x1050 (WSXGA+) | 4        | 4.44%   |
| 1366x768 (WXGA)    | 4        | 4.44%   |
| Unknown            | 4        | 4.44%   |
| 2560x1080          | 3        | 3.33%   |
| 1920x1200 (WUXGA)  | 3        | 3.33%   |
| 1280x1024 (SXGA)   | 3        | 3.33%   |
| 1600x900 (HD+)     | 2        | 2.22%   |
| 7680x1080          | 1        | 1.11%   |
| 7040x1440          | 1        | 1.11%   |
| 3840x1600          | 1        | 1.11%   |
| 3840x1080          | 1        | 1.11%   |
| 1600x1200          | 1        | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 18       | 19.35%  |
| Unknown | 16       | 17.2%   |
| 27      | 11       | 11.83%  |
| 21      | 9        | 9.68%   |
| 23      | 7        | 7.53%   |
| 34      | 5        | 5.38%   |
| 22      | 5        | 5.38%   |
| 31      | 4        | 4.3%    |
| 28      | 3        | 3.23%   |
| 25      | 2        | 2.15%   |
| 20      | 2        | 2.15%   |
| 19      | 2        | 2.15%   |
| 17      | 2        | 2.15%   |
| 54      | 1        | 1.08%   |
| 48      | 1        | 1.08%   |
| 40      | 1        | 1.08%   |
| 37      | 1        | 1.08%   |
| 32      | 1        | 1.08%   |
| 26      | 1        | 1.08%   |
| 15      | 1        | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 34       | 38.2%   |
| 401-500     | 16       | 17.98%  |
| Unknown     | 16       | 17.98%  |
| 601-700     | 9        | 10.11%  |
| 701-800     | 6        | 6.74%   |
| 301-350     | 3        | 3.37%   |
| 801-900     | 2        | 2.25%   |
| 1001-1500   | 2        | 2.25%   |
| 351-400     | 1        | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 49       | 56.98%  |
| Unknown | 16       | 18.6%   |
| 21/9    | 8        | 9.3%    |
| 16/10   | 8        | 9.3%    |
| 5/4     | 3        | 3.49%   |
| 32/9    | 1        | 1.16%   |
| 3/2     | 1        | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 31       | 34.07%  |
| Unknown        | 16       | 17.58%  |
| 351-500        | 12       | 13.19%  |
| 301-350        | 12       | 13.19%  |
| 251-300        | 9        | 9.89%   |
| 151-200        | 4        | 4.4%    |
| 501-1000       | 3        | 3.3%    |
| 141-150        | 2        | 2.2%    |
| More than 1000 | 1        | 1.1%    |
| 101-110        | 1        | 1.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 45       | 48.91%  |
| 101-120 | 24       | 26.09%  |
| Unknown | 16       | 17.39%  |
| 121-160 | 4        | 4.35%   |
| 161-240 | 2        | 2.17%   |
| 1-50    | 1        | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 61       | 71.76%  |
| 2     | 21       | 24.71%  |
| 0     | 2        | 2.35%   |
| 3     | 1        | 1.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 52       | 41.94%  |
| Intel                           | 35       | 28.23%  |
| Broadcom                        | 6        | 4.84%   |
| Qualcomm Atheros                | 4        | 3.23%   |
| TP-Link                         | 3        | 2.42%   |
| Aquantia                        | 3        | 2.42%   |
| Xiaomi                          | 2        | 1.61%   |
| Ralink Technology               | 2        | 1.61%   |
| Qualcomm Atheros Communications | 2        | 1.61%   |
| MediaTek                        | 2        | 1.61%   |
| Tenda                           | 1        | 0.81%   |
| STMicroelectronics              | 1        | 0.81%   |
| Qualcomm Technologies           | 1        | 0.81%   |
| Qualcomm                        | 1        | 0.81%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.81%   |
| Nvidia                          | 1        | 0.81%   |
| Microsoft                       | 1        | 0.81%   |
| Mellanox Technologies           | 1        | 0.81%   |
| Broadcom Limited                | 1        | 0.81%   |
| ASUSTek Computer                | 1        | 0.81%   |
| ASIX Electronics                | 1        | 0.81%   |
| Arduino SA                      | 1        | 0.81%   |
| Apple                           | 1        | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 37       | 27.21%  |
| Realtek RTL8125 2.5GbE Controller                                       | 10       | 7.35%   |
| Intel Wi-Fi 6 AX200                                                     | 7        | 5.15%   |
| Intel I211 Gigabit Network Connection                                   | 7        | 5.15%   |
| Intel Ethernet Connection (2) I219-V                                    | 4        | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3        | 2.21%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 2        | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2        | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2        | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 1.47%   |
| Intel Wireless 7265                                                     | 2        | 1.47%   |
| Intel Ethernet Controller I226-V                                        | 2        | 1.47%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2        | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 2        | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1        | 0.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1        | 0.74%   |
| Tenda U12                                                               | 1        | 0.74%   |
| STMicroelectronics Virtual COM Port                                     | 1        | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1        | 0.74%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 0.74%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 0.74%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]        | 1        | 0.74%   |
| Qualcomm POCO F3                                                        | 1        | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 0.74%   |
| OnePlus (Shenzhen) BE2029                                               | 1        | 0.74%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 0.74%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 0.74%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                 | 1        | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 0.74%   |
| MediaTek Infinix SMART 5                                                | 1        | 0.74%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2         | 1        | 0.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1        | 0.74%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1        | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 16       | 44.44%  |
| Realtek Semiconductor           | 5        | 13.89%  |
| TP-Link                         | 3        | 8.33%   |
| Ralink Technology               | 2        | 5.56%   |
| Qualcomm Atheros Communications | 2        | 5.56%   |
| Qualcomm Atheros                | 2        | 5.56%   |
| Tenda                           | 1        | 2.78%   |
| Qualcomm Technologies           | 1        | 2.78%   |
| Microsoft                       | 1        | 2.78%   |
| MediaTek                        | 1        | 2.78%   |
| Broadcom                        | 1        | 2.78%   |
| ASUSTek Computer                | 1        | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7        | 18.92%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 2        | 5.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2        | 5.41%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 5.41%   |
| Intel Wireless 7265                                                     | 2        | 5.41%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2        | 5.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1        | 2.7%    |
| Tenda U12                                                               | 1        | 2.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 2.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 2.7%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 1        | 2.7%    |
| Ralink RT5572 Wireless Adapter                                          | 1        | 2.7%    |
| Ralink MT7601U Wireless Adapter                                         | 1        | 2.7%    |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]        | 1        | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 2.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 2.7%    |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 2.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 2.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1        | 2.7%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1        | 2.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 2.7%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 1        | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 2.7%    |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                      | 1        | 2.7%    |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1        | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 49       | 52.13%  |
| Intel                 | 26       | 27.66%  |
| Broadcom              | 5        | 5.32%   |
| Aquantia              | 3        | 3.19%   |
| Xiaomi                | 2        | 2.13%   |
| Qualcomm Atheros      | 2        | 2.13%   |
| Qualcomm              | 1        | 1.06%   |
| Nvidia                | 1        | 1.06%   |
| Mellanox Technologies | 1        | 1.06%   |
| MediaTek              | 1        | 1.06%   |
| Broadcom Limited      | 1        | 1.06%   |
| ASIX Electronics      | 1        | 1.06%   |
| Apple                 | 1        | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 37       | 38.54%  |
| Realtek RTL8125 2.5GbE Controller                                                 | 10       | 10.42%  |
| Intel I211 Gigabit Network Connection                                             | 7        | 7.29%   |
| Intel Ethernet Connection (2) I219-V                                              | 4        | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 3        | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 2        | 2.08%   |
| Intel Ethernet Controller I226-V                                                  | 2        | 2.08%   |
| Intel 82567LM-3 Gigabit Network Connection                                        | 2        | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                    | 1        | 1.04%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                              | 1        | 1.04%   |
| Qualcomm POCO F3                                                                  | 1        | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                         | 1        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                     | 1        | 1.04%   |
| Nvidia MCP61 Ethernet                                                             | 1        | 1.04%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                           | 1        | 1.04%   |
| MediaTek Infinix SMART 5                                                          | 1        | 1.04%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                   | 1        | 1.04%   |
| Intel Ethernet Controller I225-V                                                  | 1        | 1.04%   |
| Intel Ethernet Connection I219-V                                                  | 1        | 1.04%   |
| Intel Ethernet Connection I218-V                                                  | 1        | 1.04%   |
| Intel Ethernet Connection I217-V                                                  | 1        | 1.04%   |
| Intel Ethernet Connection I217-LM                                                 | 1        | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                                             | 1        | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                             | 1        | 1.04%   |
| Intel Ethernet Connection (17) I219-V                                             | 1        | 1.04%   |
| Intel 82562V-2 10/100 Network Connection                                          | 1        | 1.04%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                                       | 1        | 1.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                 | 1        | 1.04%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                           | 1        | 1.04%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                                  | 1        | 1.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                   | 1        | 1.04%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                           | 1        | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                                     | 1        | 1.04%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]   | 1        | 1.04%   |
| Aquantia AQtion AQC100 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]    | 1        | 1.04%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 1        | 1.04%   |
| Apple iPad 4/Mini1                                                                | 1        | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 81       | 68.64%  |
| WiFi     | 34       | 28.81%  |
| Modem    | 2        | 1.69%   |
| Unknown  | 1        | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 81.93%  |
| WiFi     | 15       | 18.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 68.29%  |
| 2     | 17       | 20.73%  |
| 3     | 8        | 9.76%   |
| 4     | 1        | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 78.05%  |
| Yes  | 18       | 21.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 16       | 53.33%  |
| Cambridge Silicon Radio | 6        | 20%     |
| IMC Networks            | 2        | 6.67%   |
| Broadcom                | 2        | 6.67%   |
| Realtek Semiconductor   | 1        | 3.33%   |
| Foxconn / Hon Hai       | 1        | 3.33%   |
| ASUSTek Computer        | 1        | 3.33%   |
| Actions                 | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 7        | 22.58%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 19.35%  |
| Intel AX201 Bluetooth                               | 3        | 9.68%   |
| IMC Networks Bluetooth Radio                        | 2        | 6.45%   |
| Realtek Bluetooth Radio                             | 1        | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.23%   |
| Intel Bluetooth wireless interface                  | 1        | 3.23%   |
| Intel Bluetooth Device                              | 1        | 3.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.23%   |
| Intel AX211 Bluetooth                               | 1        | 3.23%   |
| Intel AX210 Bluetooth                               | 1        | 3.23%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 3.23%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.23%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 3.23%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 3.23%   |
| Actions general adapter                             | 1        | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 47       | 28.48%  |
| Intel                                | 40       | 24.24%  |
| Nvidia                               | 37       | 22.42%  |
| C-Media Electronics                  | 6        | 3.64%   |
| Logitech                             | 4        | 2.42%   |
| JMTek                                | 4        | 2.42%   |
| Focusrite-Novation                   | 2        | 1.21%   |
| Corsair                              | 2        | 1.21%   |
| Astro Gaming                         | 2        | 1.21%   |
| VIA Technologies                     | 1        | 0.61%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.61%   |
| SteelSeries ApS                      | 1        | 0.61%   |
| SAVITECH                             | 1        | 0.61%   |
| Razer USA                            | 1        | 0.61%   |
| Mark of the Unicorn                  | 1        | 0.61%   |
| KTMicro                              | 1        | 0.61%   |
| Kingston Technology                  | 1        | 0.61%   |
| Giga-Byte Technology                 | 1        | 0.61%   |
| Fry's Electronics                    | 1        | 0.61%   |
| FiiO Electronics Technology          | 1        | 0.61%   |
| Elgato Systems                       | 1        | 0.61%   |
| EDFIER                               | 1        | 0.61%   |
| Creative Technology                  | 1        | 0.61%   |
| Creative Labs                        | 1        | 0.61%   |
| Cambridge Silicon Radio              | 1        | 0.61%   |
| Cambridge Audio                      | 1        | 0.61%   |
| Blue Microphones                     | 1        | 0.61%   |
| BEHRINGER International              | 1        | 0.61%   |
| ASUSTek Computer                     | 1        | 0.61%   |
| ASRock                               | 1        | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 19       | 9.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 4.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 3.65%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 3.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 3.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 2.6%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 2.6%    |
| JMTek USB PnP Audio Device                                                 | 4        | 2.08%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.08%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 2.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 2.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 1.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.56%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 3        | 1.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.56%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia AD102 High Definition Audio Controller                              | 2        | 1.04%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 2        | 1.04%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.04%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 1.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.04%   |
| Astro Gaming Astro A50                                                     | 2        | 1.04%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2        | 1.04%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 0.52%   |
| Thesycon Systemsoftware & Consulting E70                                   | 1        | 0.52%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.52%   |
| SAVITECH SA9023 audio controller                                           | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 12       | 22.22%  |
| Corsair             | 9        | 16.67%  |
| Kingston            | 7        | 12.96%  |
| Unknown             | 6        | 11.11%  |
| Crucial             | 5        | 9.26%   |
| SK hynix            | 4        | 7.41%   |
| Samsung Electronics | 3        | 5.56%   |
| A-DATA Technology   | 3        | 5.56%   |
| Transcend           | 1        | 1.85%   |
| Team                | 1        | 1.85%   |
| Patriot             | 1        | 1.85%   |
| Micron Technology   | 1        | 1.85%   |
| Avant               | 1        | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 3.28%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 2        | 3.28%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s  | 2        | 3.28%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 3.28%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s               | 1        | 1.64%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 1.64%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 1.64%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 1.64%   |
| Transcend RAM JM367Q643A-6 512MB DIMM DDR2 667MT/s      | 1        | 1.64%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s      | 1        | 1.64%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 1.64%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s     | 1        | 1.64%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.64%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s    | 1        | 1.64%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.64%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s  | 1        | 1.64%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.64%   |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s     | 1        | 1.64%   |
| Patriot RAM PSD48G24002 8GB DIMM DDR4 2400MT/s          | 1        | 1.64%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s      | 1        | 1.64%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s     | 1        | 1.64%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s       | 1        | 1.64%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s     | 1        | 1.64%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s    | 1        | 1.64%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 1.64%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 1.64%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 1.64%   |
| Kingston RAM 9905701-017.A00G 16GB DIMM DDR4 2667MT/s   | 1        | 1.64%   |
| G.Skill RAM F5-8200J4052F24G 24GB DIMM DDR5 8200MT/s    | 1        | 1.64%   |
| G.Skill RAM F5-6800J3445G32G 32GB DIMM DDR5 4800MT/s    | 1        | 1.64%   |
| G.Skill RAM F4-3600C16-8GVK 8GB DIMM DDR4 3600MT/s      | 1        | 1.64%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s     | 1        | 1.64%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 1        | 1.64%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 1        | 1.64%   |
| G.Skill RAM F4-2800C17-8GIS 8GB DIMM DDR4 2800MT/s      | 1        | 1.64%   |
| G.Skill RAM F4-2666C18-4GRS 4GB SODIMM DDR4 2400MT/s    | 1        | 1.64%   |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s    | 1        | 1.64%   |
| G.Skill RAM F3-10666CL7-2GBRH 2048MB DIMM DDR3 1333MT/s | 1        | 1.64%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s    | 1        | 1.64%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s    | 1        | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 56.86%  |
| DDR3    | 13       | 25.49%  |
| DDR5    | 3        | 5.88%   |
| Unknown | 3        | 5.88%   |
| SDRAM   | 1        | 1.96%   |
| LPDDR5  | 1        | 1.96%   |
| DDR2    | 1        | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 47       | 92.16%  |
| SODIMM       | 3        | 5.88%   |
| Row Of Chips | 1        | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 38.89%  |
| 4096  | 11       | 20.37%  |
| 16384 | 10       | 18.52%  |
| 32768 | 4        | 7.41%   |
| 2048  | 4        | 7.41%   |
| 1024  | 2        | 3.7%    |
| 24576 | 1        | 1.85%   |
| 512   | 1        | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 8        | 13.33%  |
| 1600    | 7        | 11.67%  |
| 1333    | 7        | 11.67%  |
| 3200    | 6        | 10%     |
| 2400    | 6        | 10%     |
| 4800    | 2        | 3.33%   |
| 3866    | 2        | 3.33%   |
| 3534    | 2        | 3.33%   |
| 8200    | 1        | 1.67%   |
| 6400    | 1        | 1.67%   |
| 4000    | 1        | 1.67%   |
| 3800    | 1        | 1.67%   |
| 3733    | 1        | 1.67%   |
| 3466    | 1        | 1.67%   |
| 3333    | 1        | 1.67%   |
| 3000    | 1        | 1.67%   |
| 2933    | 1        | 1.67%   |
| 2800    | 1        | 1.67%   |
| 2667    | 1        | 1.67%   |
| 2666    | 1        | 1.67%   |
| 1867    | 1        | 1.67%   |
| 1866    | 1        | 1.67%   |
| 1800    | 1        | 1.67%   |
| 1067    | 1        | 1.67%   |
| 1066    | 1        | 1.67%   |
| 800     | 1        | 1.67%   |
| 667     | 1        | 1.67%   |
| Unknown | 1        | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 7        | 29.17%  |
| Microdia                      | 4        | 16.67%  |
| MacroSilicon                  | 2        | 8.33%   |
| WaveRider Communications      | 1        | 4.17%   |
| Sunplus Innovation Technology | 1        | 4.17%   |
| Sonix Technology              | 1        | 4.17%   |
| Samsung Electronics           | 1        | 4.17%   |
| Realtek Semiconductor         | 1        | 4.17%   |
| Microsoft                     | 1        | 4.17%   |
| GEMBIRD                       | 1        | 4.17%   |
| Chicony Electronics           | 1        | 4.17%   |
| Asuscom Network               | 1        | 4.17%   |
| Alcorlink                     | 1        | 4.17%   |
| Unknown                       | 1        | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 12.5%   |
| Microdia USB 2.0 Camera                           | 2        | 8.33%   |
| WaveRider USB Live camera                         | 1        | 4.17%   |
| Sunplus USB 2.0 Camera                            | 1        | 4.17%   |
| Sonix NexiGo HD Webcam                            | 1        | 4.17%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1        | 4.17%   |
| Realtek FULL HD 1080P Webcam                      | 1        | 4.17%   |
| Microsoft LifeCam HD-3000                         | 1        | 4.17%   |
| Microdia Webcam Vitade AF                         | 1        | 4.17%   |
| Microdia Camera                                   | 1        | 4.17%   |
| MacroSilicon USB Video                            | 1        | 4.17%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1        | 4.17%   |
| Logitech Webcam C930e                             | 1        | 4.17%   |
| Logitech HD Webcam C615                           | 1        | 4.17%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 4.17%   |
| Logitech BRIO 4K Stream Edition                   | 1        | 4.17%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 4.17%   |
| Chicony HP 720p HD Monitor Webcam                 | 1        | 4.17%   |
| Asuscom Network w300                              | 1        | 4.17%   |
| Alcorlink USB 2.0 Camera                          | 1        | 4.17%   |
| Unknown                                           | 1        | 4.17%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 71       | 86.59%  |
| 1     | 8        | 9.76%   |
| 2     | 3        | 3.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 50%     |
| Net/wireless             | 3        | 21.43%  |
| Sound                    | 2        | 14.29%  |
| Communication controller | 1        | 7.14%   |
| Camera                   | 1        | 7.14%   |

