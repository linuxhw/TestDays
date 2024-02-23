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

Total: 94

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Void Linux Rolling | 47       | 71.21%  |
| Void Linux         | 19       | 28.79%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Void Linux | 64       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Desktops | Percent |
|-----------|----------|---------|
| 6.6.8_1   | 3        | 4.17%   |
| 6.3.12_1  | 3        | 4.17%   |
| 6.6.11_1  | 2        | 2.78%   |
| 6.5.9_1   | 2        | 2.78%   |
| 6.3.13_1  | 2        | 2.78%   |
| 6.1.31_1  | 2        | 2.78%   |
| 6.0.13_1  | 2        | 2.78%   |
| 5.8.18_1  | 2        | 2.78%   |
| 5.18.9_1  | 2        | 2.78%   |
| 5.16.20_1 | 2        | 2.78%   |
| 5.13.19_1 | 2        | 2.78%   |
| 5.11.9_1  | 2        | 2.78%   |
| 5.10.14_1 | 2        | 2.78%   |
| 6.6.1_1   | 1        | 1.39%   |
| 6.5.7_1   | 1        | 1.39%   |
| 6.5.6_1   | 1        | 1.39%   |
| 6.5.5_2   | 1        | 1.39%   |
| 6.5.13_1  | 1        | 1.39%   |
| 6.5.11_1  | 1        | 1.39%   |
| 6.1.4_1   | 1        | 1.39%   |
| 6.1.12_1  | 1        | 1.39%   |
| 5.9.14_1  | 1        | 1.39%   |
| 5.8.5_1   | 1        | 1.39%   |
| 5.8.16_1  | 1        | 1.39%   |
| 5.8.11_1  | 1        | 1.39%   |
| 5.8.10_1  | 1        | 1.39%   |
| 5.6.14_1  | 1        | 1.39%   |
| 5.4.15_1  | 1        | 1.39%   |
| 5.4.13_2  | 1        | 1.39%   |
| 5.3.16_1  | 1        | 1.39%   |
| 5.18.1_1  | 1        | 1.39%   |
| 5.18.16_1 | 1        | 1.39%   |
| 5.18.14_1 | 1        | 1.39%   |
| 5.15.50_1 | 1        | 1.39%   |
| 5.15.41_1 | 1        | 1.39%   |
| 5.15.34_1 | 1        | 1.39%   |
| 5.15.32_1 | 1        | 1.39%   |
| 5.15.30_1 | 1        | 1.39%   |
| 5.15.22_1 | 1        | 1.39%   |
| 5.15.19_1 | 1        | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6.8   | 3        | 4.17%   |
| 6.3.12  | 3        | 4.17%   |
| 6.6.11  | 2        | 2.78%   |
| 6.5.9   | 2        | 2.78%   |
| 6.3.13  | 2        | 2.78%   |
| 6.1.31  | 2        | 2.78%   |
| 6.0.13  | 2        | 2.78%   |
| 5.8.18  | 2        | 2.78%   |
| 5.18.9  | 2        | 2.78%   |
| 5.16.20 | 2        | 2.78%   |
| 5.13.19 | 2        | 2.78%   |
| 5.11.9  | 2        | 2.78%   |
| 5.10.14 | 2        | 2.78%   |
| 6.6.1   | 1        | 1.39%   |
| 6.5.7   | 1        | 1.39%   |
| 6.5.6   | 1        | 1.39%   |
| 6.5.5   | 1        | 1.39%   |
| 6.5.13  | 1        | 1.39%   |
| 6.5.11  | 1        | 1.39%   |
| 6.1.4   | 1        | 1.39%   |
| 6.1.12  | 1        | 1.39%   |
| 5.9.14  | 1        | 1.39%   |
| 5.8.5   | 1        | 1.39%   |
| 5.8.16  | 1        | 1.39%   |
| 5.8.11  | 1        | 1.39%   |
| 5.8.10  | 1        | 1.39%   |
| 5.6.14  | 1        | 1.39%   |
| 5.4.15  | 1        | 1.39%   |
| 5.4.13  | 1        | 1.39%   |
| 5.3.16  | 1        | 1.39%   |
| 5.18.16 | 1        | 1.39%   |
| 5.18.14 | 1        | 1.39%   |
| 5.18.1  | 1        | 1.39%   |
| 5.15.50 | 1        | 1.39%   |
| 5.15.41 | 1        | 1.39%   |
| 5.15.34 | 1        | 1.39%   |
| 5.15.32 | 1        | 1.39%   |
| 5.15.30 | 1        | 1.39%   |
| 5.15.22 | 1        | 1.39%   |
| 5.15.19 | 1        | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 9        | 12.68%  |
| 6.5     | 7        | 9.86%   |
| 5.10    | 7        | 9.86%   |
| 6.6     | 6        | 8.45%   |
| 5.8     | 6        | 8.45%   |
| 6.3     | 5        | 7.04%   |
| 5.18    | 5        | 7.04%   |
| 5.13    | 5        | 7.04%   |
| 4.19    | 4        | 5.63%   |
| 6.1     | 3        | 4.23%   |
| 5.11    | 3        | 4.23%   |
| 6.0     | 2        | 2.82%   |
| 5.4     | 2        | 2.82%   |
| 5.16    | 2        | 2.82%   |
| 5.12    | 2        | 2.82%   |
| 5.9     | 1        | 1.41%   |
| 5.6     | 1        | 1.41%   |
| 5.3     | 1        | 1.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 61       | 95.31%  |
| ppc64le | 1        | 1.56%   |
| ppc64   | 1        | 1.56%   |
| i686    | 1        | 1.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 40.3%   |
| XFCE       | 13       | 19.4%   |
| KDE5       | 8        | 11.94%  |
| GNOME      | 5        | 7.46%   |
| sway       | 4        | 5.97%   |
| X-Cinnamon | 3        | 4.48%   |
| KDE        | 3        | 4.48%   |
| openbox    | 1        | 1.49%   |
| Lumina     | 1        | 1.49%   |
| bspwm      | 1        | 1.49%   |
| awesome    | 1        | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 47       | 71.21%  |
| Wayland | 10       | 15.15%  |
| Tty     | 5        | 7.58%   |
| Unknown | 4        | 6.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 78.79%  |
| SDDM    | 5        | 7.58%   |
| GDM     | 4        | 6.06%   |
| LightDM | 3        | 4.55%   |
| LXDM    | 2        | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 34       | 50%     |
| Unknown | 11       | 16.18%  |
| ru_RU   | 4        | 5.88%   |
| fr_FR   | 3        | 4.41%   |
| pl_PL   | 2        | 2.94%   |
| en_GB   | 2        | 2.94%   |
| cs_CZ   | 2        | 2.94%   |
| pt_BR   | 1        | 1.47%   |
| hu_HU   | 1        | 1.47%   |
| es_CL   | 1        | 1.47%   |
| en_IE   | 1        | 1.47%   |
| en_DK   | 1        | 1.47%   |
| en_CA   | 1        | 1.47%   |
| en_AU   | 1        | 1.47%   |
| el_GR   | 1        | 1.47%   |
| de_DE   | 1        | 1.47%   |
| bg_BG   | 1        | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 41       | 61.19%  |
| EFI  | 26       | 38.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 38       | 56.72%  |
| Btrfs   | 16       | 23.88%  |
| Zfs     | 6        | 8.96%   |
| Xfs     | 5        | 7.46%   |
| F2fs    | 1        | 1.49%   |
| Unknown | 1        | 1.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 31       | 46.97%  |
| Unknown | 25       | 37.88%  |
| MBR     | 10       | 15.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 84.38%  |
| Yes       | 10       | 15.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 75.76%  |
| Yes       | 16       | 24.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 23       | 35.94%  |
| MSI                 | 11       | 17.19%  |
| ASRock              | 9        | 14.06%  |
| Gigabyte Technology | 8        | 12.5%   |
| Dell                | 5        | 7.81%   |
| Unknown             | 4        | 6.25%   |
| Hewlett-Packard     | 3        | 4.69%   |
| EVGA                | 1        | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 4        | 6.25%   |
| MSI MS-7C02                        | 2        | 3.13%   |
| Dell OptiPlex 780                  | 2        | 3.13%   |
| Dell OptiPlex 7010                 | 2        | 3.13%   |
| ASUS PRIME Z390-P                  | 2        | 3.13%   |
| MSI MS-7D95                        | 1        | 1.56%   |
| MSI MS-7D14                        | 1        | 1.56%   |
| MSI MS-7C92                        | 1        | 1.56%   |
| MSI MS-7C52                        | 1        | 1.56%   |
| MSI MS-7C35                        | 1        | 1.56%   |
| MSI MS-7B86                        | 1        | 1.56%   |
| MSI MS-7A68                        | 1        | 1.56%   |
| MSI MS-7A39                        | 1        | 1.56%   |
| MSI MS-7816                        | 1        | 1.56%   |
| HP EliteDesk 800 G1 SFF            | 1        | 1.56%   |
| HP Compaq Pro 4300 SFF PC          | 1        | 1.56%   |
| HP Compaq Elite 8300 SFF           | 1        | 1.56%   |
| Gigabyte Z790 AORUS MASTER X       | 1        | 1.56%   |
| Gigabyte Z68XP-UD3                 | 1        | 1.56%   |
| Gigabyte Z370 AORUS Gaming 3       | 1        | 1.56%   |
| Gigabyte X570S UD                  | 1        | 1.56%   |
| Gigabyte H310M M.2 2.0             | 1        | 1.56%   |
| Gigabyte GA-78LMT-S2               | 1        | 1.56%   |
| Gigabyte B550M AORUS PRO-P         | 1        | 1.56%   |
| Gigabyte B450M DS3H                | 1        | 1.56%   |
| EVGA Z790 DARK KINGPIN             | 1        | 1.56%   |
| Dell OptiPlex GX520                | 1        | 1.56%   |
| ASUS TUF Gaming B550M-PLUS WIFI II | 1        | 1.56%   |
| ASUS TUF B450M-PRO GAMING          | 1        | 1.56%   |
| ASUS ROG STRIX B450-F GAMING       | 1        | 1.56%   |
| ASUS ROG CROSSHAIR VII HERO        | 1        | 1.56%   |
| ASUS PRIME Z690-P                  | 1        | 1.56%   |
| ASUS PRIME Z270-AR                 | 1        | 1.56%   |
| ASUS PRIME X470-PRO                | 1        | 1.56%   |
| ASUS PRIME H610M-E D4              | 1        | 1.56%   |
| ASUS PRIME B660M-A WIFI D4         | 1        | 1.56%   |
| ASUS PRIME B550-PLUS AC-HES        | 1        | 1.56%   |
| ASUS PRIME A320M-K/BR              | 1        | 1.56%   |
| ASUS P8Z77-V LX2                   | 1        | 1.56%   |
| ASUS P8H67-V                       | 1        | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 9        | 14.06%  |
| Dell OptiPlex        | 5        | 7.81%   |
| Unknown              | 4        | 6.25%   |
| MSI MS-7C02          | 2        | 3.13%   |
| HP Compaq            | 2        | 3.13%   |
| ASUS TUF             | 2        | 3.13%   |
| ASUS ROG             | 2        | 3.13%   |
| MSI MS-7D95          | 1        | 1.56%   |
| MSI MS-7D14          | 1        | 1.56%   |
| MSI MS-7C92          | 1        | 1.56%   |
| MSI MS-7C52          | 1        | 1.56%   |
| MSI MS-7C35          | 1        | 1.56%   |
| MSI MS-7B86          | 1        | 1.56%   |
| MSI MS-7A68          | 1        | 1.56%   |
| MSI MS-7A39          | 1        | 1.56%   |
| MSI MS-7816          | 1        | 1.56%   |
| HP EliteDesk         | 1        | 1.56%   |
| Gigabyte Z790        | 1        | 1.56%   |
| Gigabyte Z68XP-UD3   | 1        | 1.56%   |
| Gigabyte Z370        | 1        | 1.56%   |
| Gigabyte X570S       | 1        | 1.56%   |
| Gigabyte H310M       | 1        | 1.56%   |
| Gigabyte GA-78LMT-S2 | 1        | 1.56%   |
| Gigabyte B550M       | 1        | 1.56%   |
| Gigabyte B450M       | 1        | 1.56%   |
| EVGA Z790            | 1        | 1.56%   |
| ASUS P8Z77-V         | 1        | 1.56%   |
| ASUS P8H67-V         | 1        | 1.56%   |
| ASUS Maximus         | 1        | 1.56%   |
| ASUS M5A97           | 1        | 1.56%   |
| ASUS M5A78L-M        | 1        | 1.56%   |
| ASUS M4A89GTD-PRO    | 1        | 1.56%   |
| ASUS H110M-PLUS      | 1        | 1.56%   |
| ASUS CUSTOM          | 1        | 1.56%   |
| ASUS B150M           | 1        | 1.56%   |
| ASUS Amd             | 1        | 1.56%   |
| ASRock X570          | 1        | 1.56%   |
| ASRock TRX40         | 1        | 1.56%   |
| ASRock N68-S3        | 1        | 1.56%   |
| ASRock J4005B-ITX    | 1        | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 11       | 17.19%  |
| 2021    | 8        | 12.5%   |
| 2019    | 7        | 10.94%  |
| 2020    | 6        | 9.38%   |
| 2012    | 6        | 9.38%   |
| 2017    | 5        | 7.81%   |
| 2013    | 5        | 7.81%   |
| 2011    | 4        | 6.25%   |
| 2023    | 3        | 4.69%   |
| 2010    | 3        | 4.69%   |
| 2016    | 2        | 3.13%   |
| Unknown | 2        | 3.13%   |
| 2022    | 1        | 1.56%   |
| 2005    | 1        | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 64       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 64       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 20       | 30.77%  |
| 32.01-64.0      | 15       | 23.08%  |
| 8.01-16.0       | 14       | 21.54%  |
| 4.01-8.0        | 8        | 12.31%  |
| 3.01-4.0        | 3        | 4.62%   |
| 64.01-256.0     | 2        | 3.08%   |
| More than 256.0 | 1        | 1.54%   |
| 24.01-32.0      | 1        | 1.54%   |
| 2.01-3.0        | 1        | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 15       | 21.74%  |
| 3.01-4.0    | 14       | 20.29%  |
| 4.01-8.0    | 10       | 14.49%  |
| 1.01-2.0    | 10       | 14.49%  |
| 8.01-16.0   | 10       | 14.49%  |
| 0.51-1.0    | 7        | 10.14%  |
| 64.01-256.0 | 1        | 1.45%   |
| 16.01-24.0  | 1        | 1.45%   |
| 0.01-0.5    | 1        | 1.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 33.33%  |
| 3      | 19       | 28.79%  |
| 1      | 17       | 25.76%  |
| 4      | 5        | 7.58%   |
| 5      | 2        | 3.03%   |
| 9      | 1        | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 79.69%  |
| Yes       | 13       | 20.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 64       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 61.54%  |
| Yes       | 25       | 38.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 67.69%  |
| Yes       | 21       | 32.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 17       | 26.56%  |
| Poland      | 5        | 7.81%   |
| Russia      | 4        | 6.25%   |
| Germany     | 4        | 6.25%   |
| UK          | 3        | 4.69%   |
| Netherlands | 3        | 4.69%   |
| Greece      | 3        | 4.69%   |
| France      | 3        | 4.69%   |
| Czechia     | 3        | 4.69%   |
| Brazil      | 3        | 4.69%   |
| Finland     | 2        | 3.13%   |
| Canada      | 2        | 3.13%   |
| Turkey      | 1        | 1.56%   |
| Sweden      | 1        | 1.56%   |
| Spain       | 1        | 1.56%   |
| Italy       | 1        | 1.56%   |
| India       | 1        | 1.56%   |
| Hungary     | 1        | 1.56%   |
| Chile       | 1        | 1.56%   |
| Bulgaria    | 1        | 1.56%   |
| Belgium     | 1        | 1.56%   |
| Bangladesh  | 1        | 1.56%   |
| Australia   | 1        | 1.56%   |
| Argentina   | 1        | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Denver             | 3        | 4.48%   |
| Prague             | 2        | 2.99%   |
| Munich             | 2        | 2.99%   |
| Lublin             | 2        | 2.99%   |
| Amsterdam          | 2        | 2.99%   |
| Zagnansk           | 1        | 1.49%   |
| Yekaterinburg      | 1        | 1.49%   |
| Worthing           | 1        | 1.49%   |
| Winnipeg           | 1        | 1.49%   |
| Warsaw             | 1        | 1.49%   |
| Varna              | 1        | 1.49%   |
| Vancouver          | 1        | 1.49%   |
| Toulouse           | 1        | 1.49%   |
| Taranto            | 1        | 1.49%   |
| South Shields      | 1        | 1.49%   |
| Sofia              | 1        | 1.49%   |
| Savannah           | 1        | 1.49%   |
| Saint-Paul-les-Dax | 1        | 1.49%   |
| Saint Paul         | 1        | 1.49%   |
| Rosario            | 1        | 1.49%   |
| Rio de Janeiro     | 1        | 1.49%   |
| Richmond           | 1        | 1.49%   |
| Pyatigorsk         | 1        | 1.49%   |
| Pelabravo          | 1        | 1.49%   |
| Pardubice          | 1        | 1.49%   |
| Oulu               | 1        | 1.49%   |
| Orlando            | 1        | 1.49%   |
| Odessa             | 1        | 1.49%   |
| Nizhniy Novgorod   | 1        | 1.49%   |
| Newmarket          | 1        | 1.49%   |
| New York           | 1        | 1.49%   |
| Muhos              | 1        | 1.49%   |
| Monaca             | 1        | 1.49%   |
| Miedziana Gora     | 1        | 1.49%   |
| Mer                | 1        | 1.49%   |
| Madisonville       | 1        | 1.49%   |
| Kolkata            | 1        | 1.49%   |
| Kenmore            | 1        | 1.49%   |
| Katerini           | 1        | 1.49%   |
| Kalloni            | 1        | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 28       | 46     | 21.71%  |
| WDC                         | 24       | 34     | 18.6%   |
| Seagate                     | 20       | 27     | 15.5%   |
| Kingston                    | 12       | 13     | 9.3%    |
| Sandisk                     | 6        | 7      | 4.65%   |
| Toshiba                     | 5        | 6      | 3.88%   |
| Hitachi                     | 5        | 5      | 3.88%   |
| Crucial                     | 4        | 5      | 3.1%    |
| Micron/Crucial Technology   | 2        | 2      | 1.55%   |
| Intel                       | 2        | 3      | 1.55%   |
| HGST                        | 2        | 2      | 1.55%   |
| Corsair                     | 2        | 2      | 1.55%   |
| A-DATA Technology           | 2        | 3      | 1.55%   |
| XPG                         | 1        | 4      | 0.78%   |
| SPCC                        | 1        | 1      | 0.78%   |
| SK hynix                    | 1        | 2      | 0.78%   |
| Phison                      | 1        | 1      | 0.78%   |
| Patriot                     | 1        | 1      | 0.78%   |
| OCZ                         | 1        | 1      | 0.78%   |
| Maxtor                      | 1        | 1      | 0.78%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.78%   |
| LITEONIT                    | 1        | 1      | 0.78%   |
| Kingston Technology Company | 1        | 2      | 0.78%   |
| JMicron Technology          | 1        | 1      | 0.78%   |
| Intenso                     | 1        | 1      | 0.78%   |
| Gigabyte Technology         | 1        | 2      | 0.78%   |
| BIWIN                       | 1        | 1      | 0.78%   |
| AGI                         | 1        | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 6        | 4.03%   |
| Kingston SA400S37240G 240GB SSD                   | 6        | 4.03%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5        | 3.36%   |
| Seagate ST1000DM010-2EP102 1TB                    | 4        | 2.68%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 3        | 2.01%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 2        | 1.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2        | 1.34%   |
| Toshiba DT01ACA050 500GB                          | 2        | 1.34%   |
| Seagate ST1000DM003-1CH162 1TB                    | 2        | 1.34%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB              | 2        | 1.34%   |
| Samsung SSD 980 PRO 500GB                         | 2        | 1.34%   |
| Samsung SSD 970 EVO Plus 1TB                      | 2        | 1.34%   |
| Samsung SSD 870 QVO 1TB                           | 2        | 1.34%   |
| Samsung SSD 870 EVO 500GB                         | 2        | 1.34%   |
| Samsung SSD 870 EVO 1TB                           | 2        | 1.34%   |
| Samsung SSD 860 EVO 500GB                         | 2        | 1.34%   |
| Samsung NVMe SSD Drive 500GB                      | 2        | 1.34%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB               | 2        | 1.34%   |
| Kingston SHFS37A120G 120GB SSD                    | 2        | 1.34%   |
| XPG NVMe SSD Drive 2TB                            | 1        | 0.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                  | 1        | 0.67%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 1        | 0.67%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 1        | 0.67%   |
| WDC WD7500AYYS-01RCA0 752GB                       | 1        | 0.67%   |
| WDC WD5000AAKX-60U6AA0 500GB                      | 1        | 0.67%   |
| WDC WD5000AADS-00S9B0 500GB                       | 1        | 0.67%   |
| WDC WD2500AAKX-603CA0 250GB                       | 1        | 0.67%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 1        | 0.67%   |
| WDC WD20EZBX-00AYRA0 2TB                          | 1        | 0.67%   |
| WDC WD20EFRX-68EUZN0 2TB                          | 1        | 0.67%   |
| WDC WD2003FZEX-00Z4SA0 2TB                        | 1        | 0.67%   |
| WDC WD1600AAJS-60PSA0 160GB                       | 1        | 0.67%   |
| WDC WD15EARS-00MVWB0 1TB                          | 1        | 0.67%   |
| WDC WD10JPVX-08JC3T6 1TB                          | 1        | 0.67%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1        | 0.67%   |
| WDC WD10EZRX-00L4HB0 1TB                          | 1        | 0.67%   |
| WDC WD10EZEX-00BBHA0 1TB                          | 1        | 0.67%   |
| WDC WD10EFRX-68PJCN0 1TB                          | 1        | 0.67%   |
| WDC WD10EFRX-68FYTN0 1TB                          | 1        | 0.67%   |
| WDC WD10EARX-00PASB0 1TB                          | 1        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 27     | 34.48%  |
| Seagate             | 20       | 27     | 34.48%  |
| Toshiba             | 5        | 6      | 8.62%   |
| Hitachi             | 5        | 5      | 8.62%   |
| Samsung Electronics | 4        | 5      | 6.9%    |
| HGST                | 2        | 2      | 3.45%   |
| Maxtor              | 1        | 1      | 1.72%   |
| JMicron Technology  | 1        | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 16     | 28.89%  |
| Kingston            | 12       | 13     | 26.67%  |
| WDC                 | 6        | 7      | 13.33%  |
| Crucial             | 2        | 3      | 4.44%   |
| SPCC                | 1        | 1      | 2.22%   |
| SanDisk             | 1        | 1      | 2.22%   |
| Patriot             | 1        | 1      | 2.22%   |
| OCZ                 | 1        | 1      | 2.22%   |
| LITEONIT            | 1        | 1      | 2.22%   |
| Intenso             | 1        | 1      | 2.22%   |
| Intel               | 1        | 1      | 2.22%   |
| Gigabyte Technology | 1        | 2      | 2.22%   |
| Corsair             | 1        | 1      | 2.22%   |
| BIWIN               | 1        | 1      | 2.22%   |
| AGI                 | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 2      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 44       | 74     | 40.37%  |
| SSD  | 38       | 53     | 34.86%  |
| NVMe | 27       | 49     | 24.77%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 58       | 126    | 67.44%  |
| NVMe | 27       | 49     | 31.4%   |
| SAS  | 1        | 1      | 1.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 45       | 63     | 50%     |
| 0.51-1.0   | 28       | 39     | 31.11%  |
| 1.01-2.0   | 15       | 22     | 16.67%  |
| 3.01-4.0   | 1        | 2      | 1.11%   |
| 4.01-10.0  | 1        | 1      | 1.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 13       | 19.7%   |
| 101-250        | 12       | 18.18%  |
| 251-500        | 11       | 16.67%  |
| 501-1000       | 9        | 13.64%  |
| More than 3000 | 8        | 12.12%  |
| Unknown        | 5        | 7.58%   |
| 2001-3000      | 4        | 6.06%   |
| 1-20           | 3        | 4.55%   |
| 51-100         | 1        | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 16       | 22.54%  |
| 251-500        | 10       | 14.08%  |
| 101-250        | 10       | 14.08%  |
| 1001-2000      | 8        | 11.27%  |
| 501-1000       | 7        | 9.86%   |
| 21-50          | 6        | 8.45%   |
| 51-100         | 5        | 7.04%   |
| Unknown        | 5        | 7.04%   |
| More than 3000 | 3        | 4.23%   |
| 2001-3000      | 1        | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB         | 1        | 2      | 6.25%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 1      | 6.25%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1      | 6.25%   |
| Toshiba MQ04ABF100 1TB              | 1        | 2      | 6.25%   |
| Seagate ST9500325AS 500GB           | 1        | 1      | 6.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 6.25%   |
| Seagate ST3750330AS 752GB           | 1        | 1      | 6.25%   |
| Seagate ST2000VX000-1CU164 2TB      | 1        | 2      | 6.25%   |
| Seagate ST2000DM001-1CH164 2TB      | 1        | 1      | 6.25%   |
| Samsung Electronics HM160HI 160GB   | 1        | 1      | 6.25%   |
| Samsung Electronics HD502HJ 500GB   | 1        | 1      | 6.25%   |
| Samsung Electronics HD322HJ 320GB   | 1        | 1      | 6.25%   |
| Hitachi HUA722010CLA330 1TB         | 1        | 1      | 6.25%   |
| Hitachi HTS545050B9A300 500GB       | 1        | 1      | 6.25%   |
| A-DATA Technology SU700 120GB SSD   | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 37.5%   |
| WDC                 | 3        | 4      | 18.75%  |
| Samsung Electronics | 3        | 3      | 18.75%  |
| Hitachi             | 2        | 2      | 12.5%   |
| Toshiba             | 1        | 2      | 6.25%   |
| A-DATA Technology   | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 40%     |
| WDC                 | 3        | 4      | 20%     |
| Samsung Electronics | 3        | 3      | 20%     |
| Hitachi             | 2        | 2      | 13.33%  |
| Toshiba             | 1        | 2      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 18     | 93.33%  |
| SSD  | 1        | 1      | 6.67%   |

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
| Works    | 38       | 78     | 46.34%  |
| Detected | 30       | 79     | 36.59%  |
| Malfunc  | 14       | 19     | 17.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 32       | 31.37%  |
| AMD                         | 30       | 29.41%  |
| Samsung Electronics         | 16       | 15.69%  |
| SanDisk                     | 5        | 4.9%    |
| ASMedia Technology          | 4        | 3.92%   |
| Micron/Crucial Technology   | 3        | 2.94%   |
| Phison Electronics          | 2        | 1.96%   |
| Marvell Technology Group    | 2        | 1.96%   |
| ADATA Technology            | 2        | 1.96%   |
| SK hynix                    | 1        | 0.98%   |
| Nvidia                      | 1        | 0.98%   |
| MAXIO Technology (Hangzhou) | 1        | 0.98%   |
| Kingston Technology Company | 1        | 0.98%   |
| JMicron Technology          | 1        | 0.98%   |
| Broadcom                    | 1        | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15       | 12.1%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12       | 9.68%   |
| AMD 400 Series Chipset SATA Controller                                         | 10       | 8.06%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 5.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 3.23%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4        | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 3.23%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3        | 2.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 2.42%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3        | 2.42%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 2.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 2.42%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2        | 1.61%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 1.61%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.61%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2        | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 1.61%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.61%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2        | 1.61%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1        | 0.81%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1        | 0.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1        | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.81%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.81%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.81%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.81%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 0.81%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1        | 0.81%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 1        | 0.81%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1        | 0.81%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1        | 0.81%   |
| JMicron JMB361 AHCI/IDE                                                        | 1        | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1        | 0.81%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1        | 0.81%   |
| Intel SATA controller                                                          | 1        | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 58       | 58.59%  |
| NVMe | 27       | 27.27%  |
| IDE  | 8        | 8.08%   |
| RAID | 6        | 6.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 31       | 48.44%  |
| AMD                      | 31       | 48.44%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 1.56%   |
| PowerMac11,2             | 1        | 1.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 6        | 9.38%   |
| Intel Core i9-14900K                               | 2        | 3.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2        | 3.13%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2        | 3.13%   |
| AMD Ryzen 7 5800X 8-Core Processor                 | 2        | 3.13%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 2        | 3.13%   |
| AMD Ryzen 5 3600X 6-Core Processor                 | 2        | 3.13%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2        | 3.13%   |
| AMD FX-4300 Quad-Core Processor                    | 2        | 3.13%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1        | 1.56%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1        | 1.56%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1        | 1.56%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1        | 1.56%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1        | 1.56%   |
| Intel N100                                         | 1        | 1.56%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1        | 1.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz                  | 1        | 1.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz                   | 1        | 1.56%   |
| Intel Core i5-8600K CPU @ 3.60GHz                  | 1        | 1.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1        | 1.56%   |
| Intel Core i5-4670 CPU @ 3.40GHz                   | 1        | 1.56%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1        | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz                   | 1        | 1.56%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1        | 1.56%   |
| Intel Core i5-2500 CPU @ 3.30GHz                   | 1        | 1.56%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1        | 1.56%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1        | 1.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1        | 1.56%   |
| Intel Core i3-3220 CPU @ 3.30GHz                   | 1        | 1.56%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz              | 1        | 1.56%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1        | 1.56%   |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1        | 1.56%   |
| Intel 12th Gen Core i7-12700K                      | 1        | 1.56%   |
| Intel 12th Gen Core i7-12700                       | 1        | 1.56%   |
| Intel 12th Gen Core i3-12100F                      | 1        | 1.56%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz             | 1        | 1.56%   |
| AMD Ryzen Threadripper 3990X 64-Core Processor     | 1        | 1.56%   |
| AMD Ryzen 9 5900X 12-Core Processor                | 1        | 1.56%   |
| AMD Ryzen 7 5700X 8-Core Processor                 | 1        | 1.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics             | 1        | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 13       | 20.31%  |
| Intel Core i5          | 9        | 14.06%  |
| AMD Ryzen 7            | 9        | 14.06%  |
| Other                  | 7        | 10.94%  |
| Intel Core i7          | 4        | 6.25%   |
| Intel Core i3          | 4        | 6.25%   |
| Intel Core i9          | 3        | 4.69%   |
| AMD FX                 | 3        | 4.69%   |
| Intel Pentium Gold     | 1        | 1.56%   |
| Intel Pentium 4        | 1        | 1.56%   |
| Intel Pentium          | 1        | 1.56%   |
| Intel Core 2 Quad      | 1        | 1.56%   |
| Intel Core 2 Duo       | 1        | 1.56%   |
| Intel Celeron          | 1        | 1.56%   |
| AMD Ryzen Threadripper | 1        | 1.56%   |
| AMD Ryzen 9            | 1        | 1.56%   |
| AMD Ryzen 3            | 1        | 1.56%   |
| AMD Phenom II X4       | 1        | 1.56%   |
| AMD Athlon II X3       | 1        | 1.56%   |
| AMD Athlon II X2       | 1        | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 19       | 29.69%  |
| 6      | 15       | 23.44%  |
| 8      | 11       | 17.19%  |
| 2      | 11       | 17.19%  |
| 12     | 3        | 4.69%   |
| 24     | 2        | 3.13%   |
| 64     | 1        | 1.56%   |
| 3      | 1        | 1.56%   |
| 1      | 1        | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 43       | 67.19%  |
| 1      | 20       | 31.25%  |
| 4      | 1        | 1.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 60       | 93.75%  |
| Unknown        | 3        | 4.69%   |
| 32-bit         | 1        | 1.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 48.48%  |
| 0x306a9    | 3        | 4.55%   |
| 0x906e9    | 2        | 3.03%   |
| 0x506e3    | 2        | 3.03%   |
| 0x0a201009 | 2        | 3.03%   |
| 0x08701021 | 2        | 3.03%   |
| 0x0800820d | 2        | 3.03%   |
| 0x06000852 | 2        | 3.03%   |
| 0x010000c8 | 2        | 3.03%   |
| 0xa0671    | 1        | 1.52%   |
| 0x906ed    | 1        | 1.52%   |
| 0x906ea    | 1        | 1.52%   |
| 0x90675    | 1        | 1.52%   |
| 0x90672    | 1        | 1.52%   |
| 0x706a1    | 1        | 1.52%   |
| 0x306c3    | 1        | 1.52%   |
| 0x1067a    | 1        | 1.52%   |
| 0x0a50000d | 1        | 1.52%   |
| 0x0a50000c | 1        | 1.52%   |
| 0x0a201205 | 1        | 1.52%   |
| 0x0a201204 | 1        | 1.52%   |
| 0x08701030 | 1        | 1.52%   |
| 0x08701013 | 1        | 1.52%   |
| 0x08001138 | 1        | 1.52%   |
| 0x08001136 | 1        | 1.52%   |
| 0x08001129 | 1        | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 12       | 18.75%  |
| KabyLake         | 7        | 10.94%  |
| IvyBridge        | 7        | 10.94%  |
| Zen 2            | 6        | 9.38%   |
| Zen+             | 4        | 6.25%   |
| Alderlake Hybrid | 4        | 6.25%   |
| Zen              | 3        | 4.69%   |
| Piledriver       | 3        | 4.69%   |
| K10              | 3        | 4.69%   |
| Haswell          | 3        | 4.69%   |
| Unknown          | 3        | 4.69%   |
| Skylake          | 2        | 3.13%   |
| Penryn           | 2        | 3.13%   |
| SandyBridge      | 1        | 1.56%   |
| NetBurst         | 1        | 1.56%   |
| Icelake          | 1        | 1.56%   |
| Gracemont        | 1        | 1.56%   |
| Goldmont plus    | 1        | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 34       | 47.89%  |
| AMD               | 25       | 35.21%  |
| Intel             | 11       | 15.49%  |
| ASPEED Technology | 1        | 1.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 8.11%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 4.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 4.05%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 4.05%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 3        | 4.05%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 2.7%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 2.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 2.7%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 2.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.7%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.35%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.35%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.35%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1.35%   |
| Nvidia NV43 [GeForce 6600]                                                  | 1        | 1.35%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.35%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.35%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.35%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.35%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.35%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.35%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 1.35%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.35%   |
| Nvidia AD106 [GeForce RTX 4060 Ti 16GB]                                     | 1        | 1.35%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 1        | 1.35%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.35%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.35%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 1        | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.35%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.35%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 1        | 1.35%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.35%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 31       | 46.27%  |
| 1 x AMD        | 24       | 35.82%  |
| 1 x Intel      | 8        | 11.94%  |
| 2 x Nvidia     | 2        | 2.99%   |
| Intel + Nvidia | 1        | 1.49%   |
| AMD + ASPEED   | 1        | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 37       | 55.22%  |
| Proprietary | 30       | 44.78%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 30.88%  |
| 3.01-4.0   | 13       | 19.12%  |
| 1.01-2.0   | 9        | 13.24%  |
| 7.01-8.0   | 8        | 11.76%  |
| 8.01-16.0  | 5        | 7.35%   |
| 5.01-6.0   | 4        | 5.88%   |
| 2.01-3.0   | 2        | 2.94%   |
| 16.01-24.0 | 2        | 2.94%   |
| 0.51-1.0   | 2        | 2.94%   |
| 0.01-0.5   | 2        | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 14.67%  |
| Dell                 | 10       | 13.33%  |
| Hewlett-Packard      | 7        | 9.33%   |
| Goldstar             | 6        | 8%      |
| Acer                 | 6        | 8%      |
| Philips              | 3        | 4%      |
| Iiyama               | 3        | 4%      |
| BenQ                 | 3        | 4%      |
| ASUSTek Computer     | 3        | 4%      |
| Ancor Communications | 3        | 4%      |
| Fujitsu Siemens      | 2        | 2.67%   |
| AOC                  | 2        | 2.67%   |
| Unknown              | 2        | 2.67%   |
| Vizio                | 1        | 1.33%   |
| ViewSonic            | 1        | 1.33%   |
| Unknown              | 1        | 1.33%   |
| Sceptre Tech         | 1        | 1.33%   |
| Sceptre              | 1        | 1.33%   |
| ONN                  | 1        | 1.33%   |
| MSI                  | 1        | 1.33%   |
| Lenovo               | 1        | 1.33%   |
| KK@                  | 1        | 1.33%   |
| Idek Iiyama          | 1        | 1.33%   |
| Huion                | 1        | 1.33%   |
| Gigabyte Technology  | 1        | 1.33%   |
| FUN                  | 1        | 1.33%   |
| eMachines            | 1        | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 2.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 2.47%   |
| Unknown                                                               | 2        | 2.47%   |
| Vizio E320-A0 VIZ0095 1366x768 697x392mm 31.5-inch                    | 1        | 1.23%   |
| ViewSonic LCD Monitor VX2457 1920x1080                                | 1        | 1.23%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1        | 1.23%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 1        | 1.23%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1        | 1.23%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1        | 1.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 1.23%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 1.23%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1        | 1.23%   |
| Samsung Electronics LCD Monitor LU28R55 3840x2160                     | 1        | 1.23%   |
| Samsung Electronics LCD Monitor LC49G95T 7040x1440                    | 1        | 1.23%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1        | 1.23%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1        | 1.23%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 530x300mm 24.0-inch    | 1        | 1.23%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1        | 1.23%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1        | 1.23%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1        | 1.23%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1        | 1.23%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 1        | 1.23%   |
| Lenovo LEN-V5S5/S4-B LEN1201 1920x1080 527x296mm 23.8-inch            | 1        | 1.23%   |
| KK@ LCM17BT35H KK@4B4B 1600x1200 611x398mm 28.7-inch                  | 1        | 1.23%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x330mm 34.1-inch                 | 1        | 1.23%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1        | 1.23%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 1        | 1.23%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 1        | 1.23%   |
| Idek Iiyama LCD Monitor PL3266Q 2560x1440                             | 1        | 1.23%   |
| Huion Kamvas Pro 20 HAT1953 1920x1080 432x243mm 19.5-inch             | 1        | 1.23%   |
| Hewlett-Packard Z24i G2 HPN3481 1920x1200 518x324mm 24.1-inch         | 1        | 1.23%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 1        | 1.23%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1        | 1.23%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1        | 1.23%   |
| Hewlett-Packard 22w HPN342E 1920x1080 476x268mm 21.5-inch             | 1        | 1.23%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1        | 1.23%   |
| Hewlett-Packard 21kd HWP3329 1920x1080 458x258mm 20.7-inch            | 1        | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 47.22%  |
| 3840x2160 (4K)     | 6        | 8.33%   |
| 2560x1440 (QHD)    | 6        | 8.33%   |
| 1680x1050 (WSXGA+) | 4        | 5.56%   |
| 3440x1440          | 3        | 4.17%   |
| 2560x1080          | 3        | 4.17%   |
| 1366x768 (WXGA)    | 3        | 4.17%   |
| Unknown            | 3        | 4.17%   |
| 1920x1200 (WUXGA)  | 2        | 2.78%   |
| 1600x900 (HD+)     | 2        | 2.78%   |
| 1280x1024 (SXGA)   | 2        | 2.78%   |
| 7680x1080          | 1        | 1.39%   |
| 7040x1440          | 1        | 1.39%   |
| 3840x1600          | 1        | 1.39%   |
| 1600x1200          | 1        | 1.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 15       | 20%     |
| Unknown | 15       | 20%     |
| 21      | 10       | 13.33%  |
| 27      | 8        | 10.67%  |
| 23      | 5        | 6.67%   |
| 34      | 4        | 5.33%   |
| 22      | 4        | 5.33%   |
| 28      | 3        | 4%      |
| 31      | 2        | 2.67%   |
| 25      | 2        | 2.67%   |
| 20      | 2        | 2.67%   |
| 19      | 2        | 2.67%   |
| 40      | 1        | 1.33%   |
| 37      | 1        | 1.33%   |
| 17      | 1        | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 27       | 36.99%  |
| 401-500     | 16       | 21.92%  |
| Unknown     | 15       | 20.55%  |
| 601-700     | 7        | 9.59%   |
| 701-800     | 4        | 5.48%   |
| 801-900     | 2        | 2.74%   |
| 351-400     | 1        | 1.37%   |
| 301-350     | 1        | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 55.71%  |
| Unknown | 15       | 21.43%  |
| 21/9    | 7        | 10%     |
| 16/10   | 6        | 8.57%   |
| 5/4     | 2        | 2.86%   |
| 3/2     | 1        | 1.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 26       | 35.62%  |
| Unknown        | 15       | 20.55%  |
| 251-300        | 9        | 12.33%  |
| 351-500        | 8        | 10.96%  |
| 301-350        | 8        | 10.96%  |
| 151-200        | 4        | 5.48%   |
| 501-1000       | 2        | 2.74%   |
| 141-150        | 1        | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 36       | 48%     |
| 101-120 | 20       | 26.67%  |
| Unknown | 15       | 20%     |
| 121-160 | 2        | 2.67%   |
| 1-50    | 1        | 1.33%   |
| 161-240 | 1        | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 75.76%  |
| 2     | 16       | 24.24%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 42       | 42.86%  |
| Intel                           | 26       | 26.53%  |
| Qualcomm Atheros                | 4        | 4.08%   |
| TP-Link                         | 3        | 3.06%   |
| Broadcom                        | 3        | 3.06%   |
| Xiaomi                          | 2        | 2.04%   |
| Ralink Technology               | 2        | 2.04%   |
| Qualcomm Atheros Communications | 2        | 2.04%   |
| MediaTek                        | 2        | 2.04%   |
| Aquantia                        | 2        | 2.04%   |
| Tenda                           | 1        | 1.02%   |
| STMicroelectronics              | 1        | 1.02%   |
| Qualcomm Technologies           | 1        | 1.02%   |
| OnePlus Technology (Shenzhen)   | 1        | 1.02%   |
| Nvidia                          | 1        | 1.02%   |
| Broadcom Limited                | 1        | 1.02%   |
| ASUSTek Computer                | 1        | 1.02%   |
| ASIX Electronics                | 1        | 1.02%   |
| Arduino SA                      | 1        | 1.02%   |
| Apple                           | 1        | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 31       | 29.52%  |
| Realtek RTL8125 2.5GbE Controller                                       | 8        | 7.62%   |
| Intel Wi-Fi 6 AX200                                                     | 5        | 4.76%   |
| Intel I211 Gigabit Network Connection                                   | 5        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                                    | 4        | 3.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3        | 2.86%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 2        | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2        | 1.9%    |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 1.9%    |
| Intel Wireless 7265                                                     | 2        | 1.9%    |
| Intel 82567LM-3 Gigabit Network Connection                              | 2        | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1        | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1        | 0.95%   |
| Tenda U12                                                               | 1        | 0.95%   |
| STMicroelectronics Virtual COM Port                                     | 1        | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1        | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1        | 0.95%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 0.95%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 0.95%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]        | 1        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 0.95%   |
| OnePlus (Shenzhen) KB2000                                               | 1        | 0.95%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 0.95%   |
| MediaTek File-CD Gadget                                                 | 1        | 0.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1        | 0.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1        | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 0.95%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 1        | 0.95%   |
| Intel Ethernet Controller I226-V                                        | 1        | 0.95%   |
| Intel Ethernet Connection I218-V                                        | 1        | 0.95%   |
| Intel Ethernet Connection I217-LM                                       | 1        | 0.95%   |
| Intel Ethernet Connection (17) I219-V                                   | 1        | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 0.95%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1        | 0.95%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 44.44%  |
| TP-Link                         | 3        | 11.11%  |
| Realtek Semiconductor           | 3        | 11.11%  |
| Ralink Technology               | 2        | 7.41%   |
| Qualcomm Atheros Communications | 2        | 7.41%   |
| Qualcomm Atheros                | 2        | 7.41%   |
| Tenda                           | 1        | 3.7%    |
| MediaTek                        | 1        | 3.7%    |
| ASUSTek Computer                | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 5        | 17.86%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 2        | 7.14%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 7.14%   |
| Intel Wireless 7265                                                     | 2        | 7.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1        | 3.57%   |
| Tenda U12                                                               | 1        | 3.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1        | 3.57%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1        | 3.57%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 3.57%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 3.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 3.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 3.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 3.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1        | 3.57%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1        | 3.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 3.57%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 1        | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 3.57%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1        | 3.57%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1        | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 41       | 56.16%  |
| Intel                 | 18       | 24.66%  |
| Broadcom              | 3        | 4.11%   |
| Xiaomi                | 2        | 2.74%   |
| Qualcomm Atheros      | 2        | 2.74%   |
| Aquantia              | 2        | 2.74%   |
| Nvidia                | 1        | 1.37%   |
| MediaTek              | 1        | 1.37%   |
| Broadcom Limited      | 1        | 1.37%   |
| ASIX Electronics      | 1        | 1.37%   |
| Apple                 | 1        | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 31       | 42.47%  |
| Realtek RTL8125 2.5GbE Controller                                                 | 8        | 10.96%  |
| Intel I211 Gigabit Network Connection                                             | 5        | 6.85%   |
| Intel Ethernet Connection (2) I219-V                                              | 4        | 5.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 3        | 4.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 2        | 2.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                        | 2        | 2.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                    | 1        | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                              | 1        | 1.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                         | 1        | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                     | 1        | 1.37%   |
| Nvidia MCP61 Ethernet                                                             | 1        | 1.37%   |
| MediaTek File-CD Gadget                                                           | 1        | 1.37%   |
| Intel Ethernet Controller I226-V                                                  | 1        | 1.37%   |
| Intel Ethernet Connection I218-V                                                  | 1        | 1.37%   |
| Intel Ethernet Connection I217-LM                                                 | 1        | 1.37%   |
| Intel Ethernet Connection (17) I219-V                                             | 1        | 1.37%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                                       | 1        | 1.37%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                           | 1        | 1.37%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                                  | 1        | 1.37%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                           | 1        | 1.37%   |
| ASIX AX88179 Gigabit Ethernet                                                     | 1        | 1.37%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]   | 1        | 1.37%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 1        | 1.37%   |
| Apple iPad 4/Mini1                                                                | 1        | 1.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 64       | 68.82%  |
| WiFi     | 25       | 26.88%  |
| Modem    | 2        | 2.15%   |
| Unknown  | 2        | 2.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 80%     |
| WiFi     | 13       | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 71.88%  |
| 2     | 11       | 17.19%  |
| 3     | 7        | 10.94%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 51       | 79.69%  |
| Yes  | 13       | 20.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 47.83%  |
| Cambridge Silicon Radio | 5        | 21.74%  |
| Broadcom                | 2        | 8.7%    |
| Realtek Semiconductor   | 1        | 4.35%   |
| IMC Networks            | 1        | 4.35%   |
| Foxconn / Hon Hai       | 1        | 4.35%   |
| ASUSTek Computer        | 1        | 4.35%   |
| Actions                 | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 5        | 20.83%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 20.83%  |
| Intel AX201 Bluetooth                               | 2        | 8.33%   |
| Realtek Bluetooth Radio                             | 1        | 4.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.17%   |
| Intel Bluetooth wireless interface                  | 1        | 4.17%   |
| Intel Bluetooth Device                              | 1        | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.17%   |
| Intel AX210 Bluetooth                               | 1        | 4.17%   |
| IMC Networks Bluetooth Radio                        | 1        | 4.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.17%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 4.17%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 4.17%   |
| Actions general adapter                             | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 36       | 27.48%  |
| Nvidia                               | 33       | 25.19%  |
| Intel                                | 30       | 22.9%   |
| C-Media Electronics                  | 6        | 4.58%   |
| Logitech                             | 4        | 3.05%   |
| JMTek                                | 4        | 3.05%   |
| VIA Technologies                     | 1        | 0.76%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.76%   |
| SteelSeries ApS                      | 1        | 0.76%   |
| SAVITECH                             | 1        | 0.76%   |
| Razer USA                            | 1        | 0.76%   |
| KTMicro                              | 1        | 0.76%   |
| Fry's Electronics                    | 1        | 0.76%   |
| Focusrite-Novation                   | 1        | 0.76%   |
| Elgato Systems                       | 1        | 0.76%   |
| EDFIER                               | 1        | 0.76%   |
| Creative Technology                  | 1        | 0.76%   |
| Corsair                              | 1        | 0.76%   |
| Cambridge Silicon Radio              | 1        | 0.76%   |
| Cambridge Audio                      | 1        | 0.76%   |
| Blue Microphones                     | 1        | 0.76%   |
| BEHRINGER International              | 1        | 0.76%   |
| Astro Gaming                         | 1        | 0.76%   |
| ASRock                               | 1        | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 16       | 10.32%  |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 4.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 4.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 3.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 3.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 3.23%   |
| JMTek USB PnP Audio Device                                                 | 4        | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.58%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 1.94%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.94%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.94%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.94%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.29%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.29%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.29%   |
| Nvidia Audio device                                                        | 2        | 1.29%   |
| Logitech PRO X                                                             | 2        | 1.29%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 1.29%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.29%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 1.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.29%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.29%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.29%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 0.65%   |
| Thesycon Systemsoftware & Consulting D50s                                  | 1        | 0.65%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.65%   |
| SAVITECH SA9023 audio controller                                           | 1        | 0.65%   |
| Razer USA Razer USB Sound Card                                             | 1        | 0.65%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 9        | 22.5%   |
| Corsair             | 7        | 17.5%   |
| Kingston            | 6        | 15%     |
| Unknown             | 4        | 10%     |
| Crucial             | 4        | 10%     |
| Samsung Electronics | 3        | 7.5%    |
| SK hynix            | 2        | 5%      |
| A-DATA Technology   | 2        | 5%      |
| Patriot             | 1        | 2.5%    |
| Micron Technology   | 1        | 2.5%    |
| Avant               | 1        | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 4.35%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 2        | 4.35%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 4.35%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 2.17%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 2.17%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s     | 1        | 2.17%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.17%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.17%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.17%   |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s      | 1        | 2.17%   |
| Patriot RAM PSD48G24002 8GB DIMM DDR4 2400MT/s           | 1        | 2.17%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s       | 1        | 2.17%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s      | 1        | 2.17%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s        | 1        | 2.17%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 1        | 2.17%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.17%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.17%   |
| Kingston RAM 9905701-017.A00G 16GB DIMM DDR4 2667MT/s    | 1        | 2.17%   |
| G.Skill RAM F5-6800J3445G32G 32GB DIMM DDR5 4800MT/s     | 1        | 2.17%   |
| G.Skill RAM F4-3600C16-8GVK 8GB DIMM DDR4 3600MT/s       | 1        | 2.17%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 1        | 2.17%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 1        | 2.17%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 1        | 2.17%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s   | 1        | 2.17%   |
| G.Skill RAM F4-2800C17-8GIS 8192MB DIMM DDR4 2800MT/s    | 1        | 2.17%   |
| G.Skill RAM F4-2666C18-4GRS 4GB SODIMM DDR4 2400MT/s     | 1        | 2.17%   |
| G.Skill RAM F3-10666CL7-2GBRH 2048MB DIMM DDR3 1333MT/s  | 1        | 2.17%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s     | 1        | 2.17%   |
| Crucial RAM CT8G4DFS824A.C8FE 8192MB DIMM DDR4 3000MT/s  | 1        | 2.17%   |
| Crucial RAM CT16G4DFD824A.M16FJ 16GB DIMM DDR4 2400MT/s  | 1        | 2.17%   |
| Crucial RAM CT16G4DFD824A.M16FD 16GB DIMM DDR4 3200MT/s  | 1        | 2.17%   |
| Crucial RAM CT16G48C40U5.M8A1 16GB DIMM DDR5 4800MT/s    | 1        | 2.17%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s    | 1        | 2.17%   |
| Crucial RAM BL25664TN1608.16FF 2048MB DIMM DDR3 1333MT/s | 1        | 2.17%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s      | 1        | 2.17%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s     | 1        | 2.17%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3066MT/s     | 1        | 2.17%   |
| Corsair RAM CMK32GX4M4D3600C16 8GB DIMM DDR4 3600MT/s    | 1        | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 23       | 58.97%  |
| DDR3    | 10       | 25.64%  |
| Unknown | 3        | 7.69%   |
| DDR5    | 2        | 5.13%   |
| LPDDR5  | 1        | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 37       | 94.87%  |
| SODIMM       | 1        | 2.56%   |
| Row Of Chips | 1        | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 42.5%   |
| 4096  | 10       | 25%     |
| 16384 | 8        | 20%     |
| 2048  | 3        | 7.5%    |
| 32768 | 1        | 2.5%    |
| 1024  | 1        | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 7        | 15.56%  |
| 3600  | 6        | 13.33%  |
| 1600  | 6        | 13.33%  |
| 3200  | 5        | 11.11%  |
| 2400  | 5        | 11.11%  |
| 4800  | 2        | 4.44%   |
| 3866  | 2        | 4.44%   |
| 3534  | 2        | 4.44%   |
| 6400  | 1        | 2.22%   |
| 3333  | 1        | 2.22%   |
| 3066  | 1        | 2.22%   |
| 3000  | 1        | 2.22%   |
| 2933  | 1        | 2.22%   |
| 2800  | 1        | 2.22%   |
| 2667  | 1        | 2.22%   |
| 2666  | 1        | 2.22%   |
| 1867  | 1        | 2.22%   |
| 1067  | 1        | 2.22%   |

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
| Logitech                      | 6        | 28.57%  |
| Microdia                      | 4        | 19.05%  |
| MacroSilicon                  | 2        | 9.52%   |
| WaveRider Communications      | 1        | 4.76%   |
| Sunplus Innovation Technology | 1        | 4.76%   |
| Sonix Technology              | 1        | 4.76%   |
| Samsung Electronics           | 1        | 4.76%   |
| Realtek Semiconductor         | 1        | 4.76%   |
| Microsoft                     | 1        | 4.76%   |
| GEMBIRD                       | 1        | 4.76%   |
| Chicony Electronics           | 1        | 4.76%   |
| Asuscom Network               | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 14.29%  |
| Microdia USB 2.0 Camera                           | 2        | 9.52%   |
| WaveRider USB Live camera                         | 1        | 4.76%   |
| Sunplus USB 2.0 Camera                            | 1        | 4.76%   |
| Sonix NexiGo HD Webcam                            | 1        | 4.76%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1        | 4.76%   |
| Realtek FULL HD 1080P Webcam                      | 1        | 4.76%   |
| Microsoft LifeCam HD-3000                         | 1        | 4.76%   |
| Microdia Webcam Vitade AF                         | 1        | 4.76%   |
| Microdia Camera                                   | 1        | 4.76%   |
| MacroSilicon USB3. 0 capture                      | 1        | 4.76%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1        | 4.76%   |
| Logitech Webcam C930e                             | 1        | 4.76%   |
| Logitech HD Webcam C615                           | 1        | 4.76%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 4.76%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 4.76%   |
| Chicony HP 720p HD Monitor Webcam                 | 1        | 4.76%   |
| Asuscom Network w300                              | 1        | 4.76%   |

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
| 0     | 56       | 87.5%   |
| 1     | 5        | 7.81%   |
| 2     | 3        | 4.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 45.45%  |
| Sound         | 2        | 18.18%  |
| Net/wireless  | 2        | 18.18%  |
| Network       | 1        | 9.09%   |
| Camera        | 1        | 9.09%   |

