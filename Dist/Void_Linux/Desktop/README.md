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

Total: 75

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Void Linux Rolling | 33       | 63.46%  |
| Void Linux         | 19       | 36.54%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Void Linux | 50       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Desktops | Percent |
|-----------|----------|---------|
| 6.3.12_1  | 3        | 5.17%   |
| 6.1.31_1  | 2        | 3.45%   |
| 6.0.13_1  | 2        | 3.45%   |
| 5.8.18_1  | 2        | 3.45%   |
| 5.18.9_1  | 2        | 3.45%   |
| 5.16.20_1 | 2        | 3.45%   |
| 5.13.19_1 | 2        | 3.45%   |
| 5.11.9_1  | 2        | 3.45%   |
| 5.10.14_1 | 2        | 3.45%   |
| 6.3.13_1  | 1        | 1.72%   |
| 6.1.4_1   | 1        | 1.72%   |
| 6.1.12_1  | 1        | 1.72%   |
| 5.9.14_1  | 1        | 1.72%   |
| 5.8.5_1   | 1        | 1.72%   |
| 5.8.16_1  | 1        | 1.72%   |
| 5.8.11_1  | 1        | 1.72%   |
| 5.8.10_1  | 1        | 1.72%   |
| 5.6.14_1  | 1        | 1.72%   |
| 5.4.15_1  | 1        | 1.72%   |
| 5.4.13_2  | 1        | 1.72%   |
| 5.3.16_1  | 1        | 1.72%   |
| 5.18.1_1  | 1        | 1.72%   |
| 5.18.16_1 | 1        | 1.72%   |
| 5.18.14_1 | 1        | 1.72%   |
| 5.15.50_1 | 1        | 1.72%   |
| 5.15.41_1 | 1        | 1.72%   |
| 5.15.34_1 | 1        | 1.72%   |
| 5.15.32_1 | 1        | 1.72%   |
| 5.15.30_1 | 1        | 1.72%   |
| 5.15.22_1 | 1        | 1.72%   |
| 5.15.19_1 | 1        | 1.72%   |
| 5.15.16_1 | 1        | 1.72%   |
| 5.15.11_1 | 1        | 1.72%   |
| 5.13.15_1 | 1        | 1.72%   |
| 5.13.13_1 | 1        | 1.72%   |
| 5.13.10_1 | 1        | 1.72%   |
| 5.12.14_1 | 1        | 1.72%   |
| 5.12.10_1 | 1        | 1.72%   |
| 5.11.18_1 | 1        | 1.72%   |
| 5.10.8_1  | 1        | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3.12  | 3        | 5.17%   |
| 6.1.31  | 2        | 3.45%   |
| 6.0.13  | 2        | 3.45%   |
| 5.8.18  | 2        | 3.45%   |
| 5.18.9  | 2        | 3.45%   |
| 5.16.20 | 2        | 3.45%   |
| 5.13.19 | 2        | 3.45%   |
| 5.11.9  | 2        | 3.45%   |
| 5.10.14 | 2        | 3.45%   |
| 6.3.13  | 1        | 1.72%   |
| 6.1.4   | 1        | 1.72%   |
| 6.1.12  | 1        | 1.72%   |
| 5.9.14  | 1        | 1.72%   |
| 5.8.5   | 1        | 1.72%   |
| 5.8.16  | 1        | 1.72%   |
| 5.8.11  | 1        | 1.72%   |
| 5.8.10  | 1        | 1.72%   |
| 5.6.14  | 1        | 1.72%   |
| 5.4.15  | 1        | 1.72%   |
| 5.4.13  | 1        | 1.72%   |
| 5.3.16  | 1        | 1.72%   |
| 5.18.16 | 1        | 1.72%   |
| 5.18.14 | 1        | 1.72%   |
| 5.18.1  | 1        | 1.72%   |
| 5.15.50 | 1        | 1.72%   |
| 5.15.41 | 1        | 1.72%   |
| 5.15.34 | 1        | 1.72%   |
| 5.15.32 | 1        | 1.72%   |
| 5.15.30 | 1        | 1.72%   |
| 5.15.22 | 1        | 1.72%   |
| 5.15.19 | 1        | 1.72%   |
| 5.15.16 | 1        | 1.72%   |
| 5.15.11 | 1        | 1.72%   |
| 5.13.15 | 1        | 1.72%   |
| 5.13.13 | 1        | 1.72%   |
| 5.13.10 | 1        | 1.72%   |
| 5.12.14 | 1        | 1.72%   |
| 5.12.10 | 1        | 1.72%   |
| 5.11.18 | 1        | 1.72%   |
| 5.10.8  | 1        | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 9        | 15.79%  |
| 5.10    | 7        | 12.28%  |
| 5.8     | 6        | 10.53%  |
| 5.18    | 5        | 8.77%   |
| 5.13    | 5        | 8.77%   |
| 6.3     | 4        | 7.02%   |
| 4.19    | 4        | 7.02%   |
| 6.1     | 3        | 5.26%   |
| 5.11    | 3        | 5.26%   |
| 6.0     | 2        | 3.51%   |
| 5.4     | 2        | 3.51%   |
| 5.16    | 2        | 3.51%   |
| 5.12    | 2        | 3.51%   |
| 5.9     | 1        | 1.75%   |
| 5.6     | 1        | 1.75%   |
| 5.3     | 1        | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 47       | 94%     |
| ppc64le | 1        | 2%      |
| ppc64   | 1        | 2%      |
| i686    | 1        | 2%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 47.17%  |
| XFCE       | 8        | 15.09%  |
| KDE5       | 4        | 7.55%   |
| GNOME      | 4        | 7.55%   |
| X-Cinnamon | 3        | 5.66%   |
| KDE        | 3        | 5.66%   |
| sway       | 2        | 3.77%   |
| openbox    | 1        | 1.89%   |
| Lumina     | 1        | 1.89%   |
| bspwm      | 1        | 1.89%   |
| awesome    | 1        | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 39       | 75%     |
| Wayland | 6        | 11.54%  |
| Unknown | 4        | 7.69%   |
| Tty     | 3        | 5.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 42       | 80.77%  |
| SDDM    | 3        | 5.77%   |
| LightDM | 3        | 5.77%   |
| LXDM    | 2        | 3.85%   |
| GDM     | 2        | 3.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 24       | 44.44%  |
| Unknown | 11       | 20.37%  |
| ru_RU   | 4        | 7.41%   |
| pl_PL   | 2        | 3.7%    |
| fr_FR   | 2        | 3.7%    |
| en_GB   | 2        | 3.7%    |
| cs_CZ   | 2        | 3.7%    |
| pt_BR   | 1        | 1.85%   |
| en_IE   | 1        | 1.85%   |
| en_DK   | 1        | 1.85%   |
| en_AU   | 1        | 1.85%   |
| el_GR   | 1        | 1.85%   |
| de_DE   | 1        | 1.85%   |
| bg_BG   | 1        | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 31       | 58.49%  |
| EFI  | 22       | 41.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 31       | 58.49%  |
| Btrfs   | 12       | 22.64%  |
| Zfs     | 5        | 9.43%   |
| Xfs     | 4        | 7.55%   |
| Unknown | 1        | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 27       | 51.92%  |
| Unknown | 17       | 32.69%  |
| MBR     | 8        | 15.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 82%     |
| Yes       | 9        | 18%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 75%     |
| Yes       | 13       | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 19       | 38%     |
| MSI                 | 8        | 16%     |
| ASRock              | 8        | 16%     |
| Gigabyte Technology | 6        | 12%     |
| Dell                | 4        | 8%      |
| Unknown             | 3        | 6%      |
| Hewlett-Packard     | 2        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 3        | 6%      |
| Dell OptiPlex 7010           | 2        | 4%      |
| ASUS PRIME Z390-P            | 2        | 4%      |
| MSI MS-7D14                  | 1        | 2%      |
| MSI MS-7C92                  | 1        | 2%      |
| MSI MS-7C52                  | 1        | 2%      |
| MSI MS-7C35                  | 1        | 2%      |
| MSI MS-7C02                  | 1        | 2%      |
| MSI MS-7A68                  | 1        | 2%      |
| MSI MS-7A39                  | 1        | 2%      |
| MSI MS-7816                  | 1        | 2%      |
| HP EliteDesk 800 G1 SFF      | 1        | 2%      |
| HP Compaq Elite 8300 SFF     | 1        | 2%      |
| Gigabyte Z370 AORUS Gaming 3 | 1        | 2%      |
| Gigabyte X570S UD            | 1        | 2%      |
| Gigabyte H310M M.2 2.0       | 1        | 2%      |
| Gigabyte GA-78LMT-S2         | 1        | 2%      |
| Gigabyte B550M AORUS PRO-P   | 1        | 2%      |
| Gigabyte B450M DS3H          | 1        | 2%      |
| Dell OptiPlex GX520          | 1        | 2%      |
| Dell OptiPlex 780            | 1        | 2%      |
| ASUS TUF B450M-PRO GAMING    | 1        | 2%      |
| ASUS ROG STRIX B450-F GAMING | 1        | 2%      |
| ASUS ROG CROSSHAIR VII HERO  | 1        | 2%      |
| ASUS PRIME Z690-P            | 1        | 2%      |
| ASUS PRIME Z270-AR           | 1        | 2%      |
| ASUS PRIME X470-PRO          | 1        | 2%      |
| ASUS PRIME H610M-E D4        | 1        | 2%      |
| ASUS PRIME A320M-K/BR        | 1        | 2%      |
| ASUS P8Z77-V LX2             | 1        | 2%      |
| ASUS P8H67-V                 | 1        | 2%      |
| ASUS Maximus VIII FORMULA    | 1        | 2%      |
| ASUS M5A97 EVO R2.0          | 1        | 2%      |
| ASUS M5A78L-M LX             | 1        | 2%      |
| ASUS M4A89GTD-PRO/USB3       | 1        | 2%      |
| ASUS H110M-PLUS              | 1        | 2%      |
| ASUS CUSTOM                  | 1        | 2%      |
| ASUS B150M PRO GAMING        | 1        | 2%      |
| ASRock X570 Pro4             | 1        | 2%      |
| ASRock TRX40 Taichi          | 1        | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 7        | 14%     |
| Dell OptiPlex        | 4        | 8%      |
| Unknown              | 3        | 6%      |
| ASUS ROG             | 2        | 4%      |
| MSI MS-7D14          | 1        | 2%      |
| MSI MS-7C92          | 1        | 2%      |
| MSI MS-7C52          | 1        | 2%      |
| MSI MS-7C35          | 1        | 2%      |
| MSI MS-7C02          | 1        | 2%      |
| MSI MS-7A68          | 1        | 2%      |
| MSI MS-7A39          | 1        | 2%      |
| MSI MS-7816          | 1        | 2%      |
| HP EliteDesk         | 1        | 2%      |
| HP Compaq            | 1        | 2%      |
| Gigabyte Z370        | 1        | 2%      |
| Gigabyte X570S       | 1        | 2%      |
| Gigabyte H310M       | 1        | 2%      |
| Gigabyte GA-78LMT-S2 | 1        | 2%      |
| Gigabyte B550M       | 1        | 2%      |
| Gigabyte B450M       | 1        | 2%      |
| ASUS TUF             | 1        | 2%      |
| ASUS P8Z77-V         | 1        | 2%      |
| ASUS P8H67-V         | 1        | 2%      |
| ASUS Maximus         | 1        | 2%      |
| ASUS M5A97           | 1        | 2%      |
| ASUS M5A78L-M        | 1        | 2%      |
| ASUS M4A89GTD-PRO    | 1        | 2%      |
| ASUS H110M-PLUS      | 1        | 2%      |
| ASUS CUSTOM          | 1        | 2%      |
| ASUS B150M           | 1        | 2%      |
| ASRock X570          | 1        | 2%      |
| ASRock TRX40         | 1        | 2%      |
| ASRock N68-S3        | 1        | 2%      |
| ASRock J4005B-ITX    | 1        | 2%      |
| ASRock H61M-VG4      | 1        | 2%      |
| ASRock B450          | 1        | 2%      |
| ASRock AB350M        | 1        | 2%      |
| ASRock 970           | 1        | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 11       | 22%     |
| 2020    | 5        | 10%     |
| 2017    | 5        | 10%     |
| 2013    | 5        | 10%     |
| 2012    | 5        | 10%     |
| 2019    | 4        | 8%      |
| 2021    | 3        | 6%      |
| 2010    | 3        | 6%      |
| 2016    | 2        | 4%      |
| 2011    | 2        | 4%      |
| Unknown | 2        | 4%      |
| 2023    | 1        | 2%      |
| 2022    | 1        | 2%      |
| 2005    | 1        | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 50       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 50       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 18       | 35.29%  |
| 8.01-16.0       | 11       | 21.57%  |
| 32.01-64.0      | 9        | 17.65%  |
| 4.01-8.0        | 6        | 11.76%  |
| 3.01-4.0        | 3        | 5.88%   |
| More than 256.0 | 1        | 1.96%   |
| 24.01-32.0      | 1        | 1.96%   |
| 2.01-3.0        | 1        | 1.96%   |
| 64.01-256.0     | 1        | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 14       | 25.45%  |
| 3.01-4.0    | 9        | 16.36%  |
| 1.01-2.0    | 8        | 14.55%  |
| 8.01-16.0   | 8        | 14.55%  |
| 0.51-1.0    | 7        | 12.73%  |
| 4.01-8.0    | 6        | 10.91%  |
| 64.01-256.0 | 1        | 1.82%   |
| 16.01-24.0  | 1        | 1.82%   |
| 0.01-0.5    | 1        | 1.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 16       | 30.77%  |
| 3      | 15       | 28.85%  |
| 1      | 14       | 26.92%  |
| 4      | 4        | 7.69%   |
| 5      | 2        | 3.85%   |
| 9      | 1        | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 82%     |
| Yes       | 9        | 18%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 68.63%  |
| Yes       | 16       | 31.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 74.51%  |
| Yes       | 13       | 25.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 13       | 26%     |
| Poland      | 5        | 10%     |
| Russia      | 4        | 8%      |
| Germany     | 3        | 6%      |
| Czechia     | 3        | 6%      |
| Brazil      | 3        | 6%      |
| UK          | 2        | 4%      |
| Netherlands | 2        | 4%      |
| Greece      | 2        | 4%      |
| France      | 2        | 4%      |
| Finland     | 2        | 4%      |
| Turkey      | 1        | 2%      |
| Sweden      | 1        | 2%      |
| Spain       | 1        | 2%      |
| India       | 1        | 2%      |
| Bulgaria    | 1        | 2%      |
| Belgium     | 1        | 2%      |
| Bangladesh  | 1        | 2%      |
| Australia   | 1        | 2%      |
| Argentina   | 1        | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Denver             | 3        | 5.66%   |
| Prague             | 2        | 3.77%   |
| Munich             | 2        | 3.77%   |
| Lublin             | 2        | 3.77%   |
| Amsterdam          | 2        | 3.77%   |
| Zagnansk           | 1        | 1.89%   |
| Yekaterinburg      | 1        | 1.89%   |
| Worthing           | 1        | 1.89%   |
| Warsaw             | 1        | 1.89%   |
| Varna              | 1        | 1.89%   |
| South Shields      | 1        | 1.89%   |
| Sofia              | 1        | 1.89%   |
| Savannah           | 1        | 1.89%   |
| Saint-Paul-les-Dax | 1        | 1.89%   |
| Saint Paul         | 1        | 1.89%   |
| Rosario            | 1        | 1.89%   |
| Rio de Janeiro     | 1        | 1.89%   |
| Richmond           | 1        | 1.89%   |
| Pyatigorsk         | 1        | 1.89%   |
| Pelabravo          | 1        | 1.89%   |
| Pardubice          | 1        | 1.89%   |
| Oulu               | 1        | 1.89%   |
| Orlando            | 1        | 1.89%   |
| Nizhniy Novgorod   | 1        | 1.89%   |
| New York           | 1        | 1.89%   |
| Muhos              | 1        | 1.89%   |
| Monaca             | 1        | 1.89%   |
| Miedziana Gora     | 1        | 1.89%   |
| Mer                | 1        | 1.89%   |
| Kolkata            | 1        | 1.89%   |
| Katerini           | 1        | 1.89%   |
| Iwkowa             | 1        | 1.89%   |
| Ioannina           | 1        | 1.89%   |
| Helsinki           | 1        | 1.89%   |
| Gothenburg         | 1        | 1.89%   |
| Glasgow            | 1        | 1.89%   |
| Epping             | 1        | 1.89%   |
| Elgin              | 1        | 1.89%   |
| Eden               | 1        | 1.89%   |
| Dhaka              | 1        | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 23       | 38     | 22.12%  |
| WDC                         | 21       | 29     | 20.19%  |
| Seagate                     | 17       | 24     | 16.35%  |
| Kingston                    | 11       | 12     | 10.58%  |
| Toshiba                     | 4        | 5      | 3.85%   |
| SanDisk                     | 4        | 5      | 3.85%   |
| Hitachi                     | 3        | 3      | 2.88%   |
| Crucial                     | 3        | 4      | 2.88%   |
| Intel                       | 2        | 3      | 1.92%   |
| HGST                        | 2        | 2      | 1.92%   |
| Corsair                     | 2        | 2      | 1.92%   |
| A-DATA Technology           | 2        | 3      | 1.92%   |
| XPG                         | 1        | 4      | 0.96%   |
| SPCC                        | 1        | 1      | 0.96%   |
| Phison                      | 1        | 1      | 0.96%   |
| Patriot                     | 1        | 1      | 0.96%   |
| OCZ                         | 1        | 1      | 0.96%   |
| Micron/Crucial Technology   | 1        | 1      | 0.96%   |
| Maxtor                      | 1        | 1      | 0.96%   |
| LITEONIT                    | 1        | 1      | 0.96%   |
| Kingston Technology Company | 1        | 2      | 0.96%   |
| Gigabyte Technology         | 1        | 2      | 0.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 5        | 4.13%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4        | 3.31%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 2.48%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 2.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2        | 1.65%   |
| Samsung SSD 980 PRO 500GB                           | 2        | 1.65%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2        | 1.65%   |
| Samsung SSD 870 QVO 1TB                             | 2        | 1.65%   |
| Samsung SSD 870 EVO 500GB                           | 2        | 1.65%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 1.65%   |
| Samsung NVMe SSD Drive 500GB                        | 2        | 1.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 1.65%   |
| Kingston SHFS37A120G 120GB SSD                      | 2        | 1.65%   |
| XPG NVMe SSD Drive 2TB                              | 1        | 0.83%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1        | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1        | 0.83%   |
| WDC WD7500AYYS-01RCA0 752GB                         | 1        | 0.83%   |
| WDC WD5000AADS-00S9B0 500GB                         | 1        | 0.83%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 0.83%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 1        | 0.83%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 1        | 0.83%   |
| WDC WD2003FZEX-00Z4SA0 2TB                          | 1        | 0.83%   |
| WDC WD1600AAJS-60PSA0 160GB                         | 1        | 0.83%   |
| WDC WD15EARS-00MVWB0 1TB                            | 1        | 0.83%   |
| WDC WD10JPVX-08JC3T6 1TB                            | 1        | 0.83%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1        | 0.83%   |
| WDC WD10EZRX-00L4HB0 1TB                            | 1        | 0.83%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 1        | 0.83%   |
| WDC WD10EFRX-68PJCN0 1TB                            | 1        | 0.83%   |
| WDC WD10EFRX-68FYTN0 1TB                            | 1        | 0.83%   |
| WDC WD10EARX-00PASB0 1TB                            | 1        | 0.83%   |
| WDC WD10EARS-00Y5B1 1TB                             | 1        | 0.83%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 1        | 0.83%   |
| WDC WD1001FALS-00K1B0 1TB                           | 1        | 0.83%   |
| Toshiba MQ04ABF100 1TB                              | 1        | 0.83%   |
| Toshiba HDWD110 1TB                                 | 1        | 0.83%   |
| Toshiba DT01ACA200 2TB                              | 1        | 0.83%   |
| Toshiba DT01ACA050 500GB                            | 1        | 0.83%   |
| SPCC Solid State Disk 128GB                         | 1        | 0.83%   |
| Seagate ST9500325AS 500GB                           | 1        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 25     | 36.73%  |
| Seagate             | 17       | 24     | 34.69%  |
| Toshiba             | 4        | 5      | 8.16%   |
| Samsung Electronics | 4        | 5      | 8.16%   |
| Hitachi             | 3        | 3      | 6.12%   |
| HGST                | 2        | 2      | 4.08%   |
| Maxtor              | 1        | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 15     | 32.43%  |
| Kingston            | 11       | 12     | 29.73%  |
| WDC                 | 4        | 4      | 10.81%  |
| SPCC                | 1        | 1      | 2.7%    |
| SanDisk             | 1        | 1      | 2.7%    |
| Patriot             | 1        | 1      | 2.7%    |
| OCZ                 | 1        | 1      | 2.7%    |
| LITEONIT            | 1        | 1      | 2.7%    |
| Intel               | 1        | 1      | 2.7%    |
| Gigabyte Technology | 1        | 2      | 2.7%    |
| Crucial             | 1        | 2      | 2.7%    |
| Corsair             | 1        | 1      | 2.7%    |
| A-DATA Technology   | 1        | 2      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 37       | 65     | 41.57%  |
| SSD  | 32       | 44     | 35.96%  |
| NVMe | 20       | 36     | 22.47%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 48       | 109    | 70.59%  |
| NVMe | 20       | 36     | 29.41%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 53     | 50.67%  |
| 0.51-1.0   | 23       | 34     | 30.67%  |
| 1.01-2.0   | 12       | 19     | 16%     |
| 3.01-4.0   | 1        | 2      | 1.33%   |
| 4.01-10.0  | 1        | 1      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 11       | 21.15%  |
| 101-250        | 9        | 17.31%  |
| More than 3000 | 7        | 13.46%  |
| 1001-2000      | 7        | 13.46%  |
| 501-1000       | 7        | 13.46%  |
| Unknown        | 5        | 9.62%   |
| 2001-3000      | 4        | 7.69%   |
| 1-20           | 2        | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 12       | 21.05%  |
| 101-250        | 10       | 17.54%  |
| 251-500        | 8        | 14.04%  |
| 1001-2000      | 6        | 10.53%  |
| 51-100         | 5        | 8.77%   |
| Unknown        | 5        | 8.77%   |
| 501-1000       | 4        | 7.02%   |
| More than 3000 | 3        | 5.26%   |
| 21-50          | 3        | 5.26%   |
| 2001-3000      | 1        | 1.75%   |

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
| Works    | 34       | 71     | 50%     |
| Detected | 20       | 55     | 29.41%  |
| Malfunc  | 14       | 19     | 20.59%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 25       | 32.89%  |
| AMD                         | 23       | 30.26%  |
| Samsung Electronics         | 11       | 14.47%  |
| SanDisk                     | 3        | 3.95%   |
| ASMedia Technology          | 3        | 3.95%   |
| Phison Electronics          | 2        | 2.63%   |
| Micron/Crucial Technology   | 2        | 2.63%   |
| ADATA Technology            | 2        | 2.63%   |
| Nvidia                      | 1        | 1.32%   |
| Marvell Technology Group    | 1        | 1.32%   |
| Kingston Technology Company | 1        | 1.32%   |
| JMicron Technology          | 1        | 1.32%   |
| Broadcom                    | 1        | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13       | 13.83%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8        | 8.51%   |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 8.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 4.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 3.19%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 3.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 3.19%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 3.19%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 2.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 2.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 2.13%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.13%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 2.13%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2        | 2.13%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 1        | 1.06%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 1.06%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.06%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.06%   |
| Phison E12 NVMe Controller                                                     | 1        | 1.06%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.06%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.06%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 1.06%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 1.06%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 1        | 1.06%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 1.06%   |
| JMicron JMB361 AHCI/IDE                                                        | 1        | 1.06%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1        | 1.06%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.06%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 1.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 46       | 59.74%  |
| NVMe | 20       | 25.97%  |
| IDE  | 8        | 10.39%  |
| RAID | 3        | 3.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 24       | 48%     |
| AMD                      | 24       | 48%     |
| PowerNV C1P9S01 REV 1.01 | 1        | 2%      |
| PowerMac11,2             | 1        | 2%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4        | 8%      |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2        | 4%      |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2        | 4%      |
| AMD Ryzen 5 2600 Six-Core Processor                | 2        | 4%      |
| AMD FX-4300 Quad-Core Processor                    | 2        | 4%      |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1        | 2%      |
| PowerMac11,2 PPC970MP, altivec supported           | 1        | 2%      |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1        | 2%      |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1        | 2%      |
| Intel Pentium 4 CPU 2.80GHz                        | 1        | 2%      |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1        | 2%      |
| Intel Core i7-6700K CPU @ 4.00GHz                  | 1        | 2%      |
| Intel Core i7-4790 CPU @ 3.60GHz                   | 1        | 2%      |
| Intel Core i5-8600K CPU @ 3.60GHz                  | 1        | 2%      |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1        | 2%      |
| Intel Core i5-4670 CPU @ 3.40GHz                   | 1        | 2%      |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1        | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz                   | 1        | 2%      |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1        | 2%      |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1        | 2%      |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1        | 2%      |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1        | 2%      |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1        | 2%      |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1        | 2%      |
| Intel 12th Gen Core i7-12700K                      | 1        | 2%      |
| Intel 12th Gen Core i3-12100F                      | 1        | 2%      |
| Intel 11th Gen Core i5-11600 @ 2.80GHz             | 1        | 2%      |
| AMD Ryzen Threadripper 3990X 64-Core Processor     | 1        | 2%      |
| AMD Ryzen 9 5900X 12-Core Processor                | 1        | 2%      |
| AMD Ryzen 7 5800X 8-Core Processor                 | 1        | 2%      |
| AMD Ryzen 7 3700X 8-Core Processor                 | 1        | 2%      |
| AMD Ryzen 7 2700X Eight-Core Processor             | 1        | 2%      |
| AMD Ryzen 7 1700X Eight-Core Processor             | 1        | 2%      |
| AMD Ryzen 7 1700 Eight-Core Processor              | 1        | 2%      |
| AMD Ryzen 5 5600G with Radeon Graphics             | 1        | 2%      |
| AMD Ryzen 5 3600X 6-Core Processor                 | 1        | 2%      |
| AMD Ryzen 5 3600 6-Core Processor                  | 1        | 2%      |
| AMD Ryzen 5 1600 Six-Core Processor                | 1        | 2%      |
| AMD Ryzen 3 3100 4-Core Processor                  | 1        | 2%      |
| AMD Phenom II X4 980 Processor                     | 1        | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 10       | 20%     |
| Intel Core i5          | 8        | 16%     |
| Other                  | 5        | 10%     |
| AMD Ryzen 7            | 5        | 10%     |
| Intel Core i7          | 4        | 8%      |
| Intel Core i3          | 3        | 6%      |
| AMD FX                 | 3        | 6%      |
| Intel Pentium Gold     | 1        | 2%      |
| Intel Pentium 4        | 1        | 2%      |
| Intel Pentium          | 1        | 2%      |
| Intel Core i9          | 1        | 2%      |
| Intel Core 2 Duo       | 1        | 2%      |
| Intel Celeron          | 1        | 2%      |
| AMD Ryzen Threadripper | 1        | 2%      |
| AMD Ryzen 9            | 1        | 2%      |
| AMD Ryzen 3            | 1        | 2%      |
| AMD Phenom II X4       | 1        | 2%      |
| AMD Athlon II X3       | 1        | 2%      |
| AMD Athlon II X2       | 1        | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 16       | 32%     |
| 6      | 12       | 24%     |
| 2      | 10       | 20%     |
| 8      | 7        | 14%     |
| 12     | 2        | 4%      |
| 64     | 1        | 2%      |
| 3      | 1        | 2%      |
| 1      | 1        | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 32       | 64%     |
| 1      | 17       | 34%     |
| 4      | 1        | 2%      |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 46       | 92%     |
| Unknown        | 3        | 6%      |
| 32-bit         | 1        | 2%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 36.54%  |
| 0x306a9    | 3        | 5.77%   |
| 0x906e9    | 2        | 3.85%   |
| 0x506e3    | 2        | 3.85%   |
| 0x0a201009 | 2        | 3.85%   |
| 0x08701021 | 2        | 3.85%   |
| 0x0800820d | 2        | 3.85%   |
| 0x06000852 | 2        | 3.85%   |
| 0x010000c8 | 2        | 3.85%   |
| 0xa0671    | 1        | 1.92%   |
| 0x906ed    | 1        | 1.92%   |
| 0x906ea    | 1        | 1.92%   |
| 0x90675    | 1        | 1.92%   |
| 0x90672    | 1        | 1.92%   |
| 0x706a1    | 1        | 1.92%   |
| 0x306c3    | 1        | 1.92%   |
| 0x1067a    | 1        | 1.92%   |
| 0x0a50000c | 1        | 1.92%   |
| 0x0a201205 | 1        | 1.92%   |
| 0x0a201204 | 1        | 1.92%   |
| 0x08701030 | 1        | 1.92%   |
| 0x08701013 | 1        | 1.92%   |
| 0x08001138 | 1        | 1.92%   |
| 0x08001136 | 1        | 1.92%   |
| 0x08001129 | 1        | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 7        | 14%     |
| KabyLake         | 7        | 14%     |
| IvyBridge        | 6        | 12%     |
| Zen 2            | 5        | 10%     |
| Zen+             | 3        | 6%      |
| Zen              | 3        | 6%      |
| Piledriver       | 3        | 6%      |
| K10              | 3        | 6%      |
| Haswell          | 3        | 6%      |
| Skylake          | 2        | 4%      |
| Alderlake Hybrid | 2        | 4%      |
| Unknown          | 2        | 4%      |
| Penryn           | 1        | 2%      |
| NetBurst         | 1        | 2%      |
| Icelake          | 1        | 2%      |
| Goldmont plus    | 1        | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 26       | 47.27%  |
| AMD               | 20       | 36.36%  |
| Intel             | 8        | 14.55%  |
| ASPEED Technology | 1        | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 8.62%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 3        | 5.17%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 3.45%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 3.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.45%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 3.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 3.45%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 3.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 3.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.45%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.72%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.72%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.72%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1.72%   |
| Nvidia NV43 [GeForce 6600]                                                  | 1        | 1.72%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.72%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.72%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.72%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 1.72%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1        | 1.72%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.72%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.72%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 1        | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.72%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.72%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.72%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.72%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.72%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.72%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 1.72%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 1.72%   |
| AMD RS880 [Radeon HD 4290]                                                  | 1        | 1.72%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.72%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 1.72%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 1.72%   |
| AMD Lexa XT [Radeon PRO WX 2100]                                            | 1        | 1.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 24       | 45.28%  |
| 1 x AMD      | 19       | 35.85%  |
| 1 x Intel    | 7        | 13.21%  |
| 2 x Nvidia   | 2        | 3.77%   |
| AMD + ASPEED | 1        | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 29       | 54.72%  |
| Proprietary | 24       | 45.28%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 31.48%  |
| 3.01-4.0   | 11       | 20.37%  |
| 1.01-2.0   | 9        | 16.67%  |
| 7.01-8.0   | 5        | 9.26%   |
| 5.01-6.0   | 3        | 5.56%   |
| 8.01-16.0  | 3        | 5.56%   |
| 2.01-3.0   | 2        | 3.7%    |
| 0.01-0.5   | 2        | 3.7%    |
| 16.01-24.0 | 1        | 1.85%   |
| 0.51-1.0   | 1        | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 14.29%  |
| Dell                 | 8        | 14.29%  |
| Hewlett-Packard      | 6        | 10.71%  |
| Acer                 | 5        | 8.93%   |
| Philips              | 3        | 5.36%   |
| Iiyama               | 3        | 5.36%   |
| Goldstar             | 3        | 5.36%   |
| BenQ                 | 3        | 5.36%   |
| ASUSTek Computer     | 3        | 5.36%   |
| Fujitsu Siemens      | 2        | 3.57%   |
| Ancor Communications | 2        | 3.57%   |
| Unknown              | 1        | 1.79%   |
| Sceptre Tech         | 1        | 1.79%   |
| Sceptre              | 1        | 1.79%   |
| ONN                  | 1        | 1.79%   |
| MSI                  | 1        | 1.79%   |
| Lenovo               | 1        | 1.79%   |
| Idek Iiyama          | 1        | 1.79%   |
| Gigabyte Technology  | 1        | 1.79%   |
| FUN                  | 1        | 1.79%   |
| AOC                  | 1        | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1        | 1.61%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch         | 1        | 1.61%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 530x300mm 24.0-inch  | 1        | 1.61%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1        | 1.61%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 1.61%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 1.61%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 1.61%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1        | 1.61%   |
| Samsung Electronics LCD Monitor LU28R55 3840x2160                     | 1        | 1.61%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1        | 1.61%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1        | 1.61%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1        | 1.61%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1        | 1.61%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1        | 1.61%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                   | 1        | 1.61%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 1        | 1.61%   |
| Lenovo LEN-510A-B LEN1201 1920x1080 509x286mm 23.0-inch               | 1        | 1.61%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 1        | 1.61%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1        | 1.61%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 1        | 1.61%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 1        | 1.61%   |
| Idek Iiyama LCD Monitor PL3266Q 2560x1440                             | 1        | 1.61%   |
| Hewlett-Packard Z24i G2 HPN3481 1920x1200 518x324mm 24.1-inch         | 1        | 1.61%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 1        | 1.61%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1        | 1.61%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1        | 1.61%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 480x270mm 21.7-inch           | 1        | 1.61%   |
| Hewlett-Packard 21kd HWP3329 1920x1080 458x258mm 20.7-inch            | 1        | 1.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 1.61%   |
| Goldstar 32 FHD GSM7701 1920x1080 600x340mm 27.2-inch                 | 1        | 1.61%   |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1        | 1.61%   |
| Gigabyte Technology AORUS CV27Q GBT2705 2560x1440 600x340mm 27.2-inch | 1        | 1.61%   |
| FUN HDMI Monitor FUN9D31 3840x2160 480x270mm 21.7-inch                | 1        | 1.61%   |
| Fujitsu Siemens SL27T-1 LED FUS07E4 1920x1080 598x336mm 27.0-inch     | 1        | 1.61%   |
| Fujitsu Siemens E19-06SA FUS0742 1280x1024 376x301mm 19.0-inch        | 1        | 1.61%   |
| Dell U3818DW DELA0F4 3840x1600 880x367mm 37.5-inch                    | 1        | 1.61%   |
| Dell U2913WM DEL4089 2560x1080 673x284mm 28.8-inch                    | 1        | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 26       | 48.15%  |
| 3840x2160 (4K)     | 5        | 9.26%   |
| 2560x1440 (QHD)    | 5        | 9.26%   |
| 1680x1050 (WSXGA+) | 4        | 7.41%   |
| 3440x1440          | 3        | 5.56%   |
| 1920x1200 (WUXGA)  | 2        | 3.7%    |
| 1366x768 (WXGA)    | 2        | 3.7%    |
| 1280x1024 (SXGA)   | 2        | 3.7%    |
| Unknown            | 2        | 3.7%    |
| 7680x1080          | 1        | 1.85%   |
| 3840x1600          | 1        | 1.85%   |
| 2560x1080          | 1        | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 13       | 22.81%  |
| Unknown | 11       | 19.3%   |
| 27      | 7        | 12.28%  |
| 21      | 6        | 10.53%  |
| 23      | 4        | 7.02%   |
| 22      | 4        | 7.02%   |
| 34      | 3        | 5.26%   |
| 28      | 2        | 3.51%   |
| 40      | 1        | 1.75%   |
| 37      | 1        | 1.75%   |
| 31      | 1        | 1.75%   |
| 25      | 1        | 1.75%   |
| 20      | 1        | 1.75%   |
| 19      | 1        | 1.75%   |
| 17      | 1        | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 23       | 41.07%  |
| 401-500     | 11       | 19.64%  |
| Unknown     | 11       | 19.64%  |
| 601-700     | 4        | 7.14%   |
| 701-800     | 3        | 5.36%   |
| 801-900     | 2        | 3.57%   |
| 351-400     | 1        | 1.79%   |
| 301-350     | 1        | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 55.56%  |
| Unknown | 11       | 20.37%  |
| 16/10   | 6        | 11.11%  |
| 21/9    | 5        | 9.26%   |
| 5/4     | 2        | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 35.71%  |
| Unknown        | 11       | 19.64%  |
| 251-300        | 8        | 14.29%  |
| 301-350        | 7        | 12.5%   |
| 351-500        | 5        | 8.93%   |
| 151-200        | 2        | 3.57%   |
| 501-1000       | 2        | 3.57%   |
| 141-150        | 1        | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 51.72%  |
| 101-120 | 14       | 24.14%  |
| Unknown | 11       | 18.97%  |
| 121-160 | 2        | 3.45%   |
| 161-240 | 1        | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 76.92%  |
| 2     | 12       | 23.08%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 33       | 42.31%  |
| Intel                           | 21       | 26.92%  |
| Qualcomm Atheros                | 4        | 5.13%   |
| Broadcom                        | 3        | 3.85%   |
| Xiaomi                          | 2        | 2.56%   |
| TP-Link                         | 2        | 2.56%   |
| Ralink Technology               | 2        | 2.56%   |
| Qualcomm Atheros Communications | 2        | 2.56%   |
| Tenda                           | 1        | 1.28%   |
| STMicroelectronics              | 1        | 1.28%   |
| OnePlus Technology (Shenzhen)   | 1        | 1.28%   |
| Nvidia                          | 1        | 1.28%   |
| MediaTek                        | 1        | 1.28%   |
| ASUSTek Computer                | 1        | 1.28%   |
| ASIX Electronics                | 1        | 1.28%   |
| Arduino SA                      | 1        | 1.28%   |
| Apple                           | 1        | 1.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 23       | 28.75%  |
| Realtek RTL8125 2.5GbE Controller                                       | 7        | 8.75%   |
| Intel I211 Gigabit Network Connection                                   | 5        | 6.25%   |
| Intel Wi-Fi 6 AX200                                                     | 4        | 5%      |
| Intel Ethernet Connection (2) I219-V                                    | 4        | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3        | 3.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2        | 2.5%    |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 2.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 1.25%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1        | 1.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1        | 1.25%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1        | 1.25%   |
| Tenda U12                                                               | 1        | 1.25%   |
| STMicroelectronics Virtual COM Port                                     | 1        | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 1.25%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 1.25%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 1.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.25%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:5A38C392                              | 1        | 1.25%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 1.25%   |
| MediaTek Titan pocket                                                   | 1        | 1.25%   |
| Intel Wireless 7265                                                     | 1        | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 1.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 1.25%   |
| Intel Ethernet Connection I218-V                                        | 1        | 1.25%   |
| Intel Ethernet Connection I217-LM                                       | 1        | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 1        | 1.25%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                             | 1        | 1.25%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                 | 1        | 1.25%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                        | 1        | 1.25%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1        | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                           | 1        | 1.25%   |
| Arduino SA Uno R3 (CDC ACM)                                             | 1        | 1.25%   |
| Apple iPad 4/Mini1                                                      | 1        | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 44.44%  |
| TP-Link                         | 2        | 11.11%  |
| Ralink Technology               | 2        | 11.11%  |
| Qualcomm Atheros Communications | 2        | 11.11%  |
| Qualcomm Atheros                | 2        | 11.11%  |
| Realtek Semiconductor           | 1        | 5.56%   |
| ASUSTek Computer                | 1        | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 4        | 22.22%  |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 11.11%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1        | 5.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1        | 5.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 5.56%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 5.56%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 5.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 5.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 5.56%   |
| Intel Wireless 7265                                                     | 1        | 5.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1        | 5.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 5.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 5.56%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1        | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 32       | 54.24%  |
| Intel                 | 15       | 25.42%  |
| Broadcom              | 3        | 5.08%   |
| Xiaomi                | 2        | 3.39%   |
| Qualcomm Atheros      | 2        | 3.39%   |
| Tenda                 | 1        | 1.69%   |
| Nvidia                | 1        | 1.69%   |
| MediaTek              | 1        | 1.69%   |
| ASIX Electronics      | 1        | 1.69%   |
| Apple                 | 1        | 1.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23       | 38.98%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 11.86%  |
| Intel I211 Gigabit Network Connection                             | 5        | 8.47%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 6.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 5.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 3.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 1.69%   |
| Tenda U12                                                         | 1        | 1.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.69%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.69%   |
| MediaTek Titan pocket                                             | 1        | 1.69%   |
| Intel Ethernet Connection I218-V                                  | 1        | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.69%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.69%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                       | 1        | 1.69%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.69%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 1.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.69%   |
| Apple iPad 4/Mini1                                                | 1        | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 72.46%  |
| WiFi     | 16       | 23.19%  |
| Modem    | 2        | 2.9%    |
| Unknown  | 1        | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 86.27%  |
| WiFi     | 7        | 13.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 80%     |
| 2     | 6        | 12%     |
| 3     | 4        | 8%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 84%     |
| Yes  | 8        | 16%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 46.67%  |
| Cambridge Silicon Radio | 4        | 26.67%  |
| Broadcom                | 2        | 13.33%  |
| ASUSTek Computer        | 1        | 6.67%   |
| Actions                 | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 4        | 26.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 26.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 6.67%   |
| Intel AX210 Bluetooth                               | 1        | 6.67%   |
| Intel AX201 Bluetooth                               | 1        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 6.67%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 6.67%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 6.67%   |
| Actions general adapter                             | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AMD                     | 27       | 26.73%  |
| Nvidia                  | 25       | 24.75%  |
| Intel                   | 23       | 22.77%  |
| C-Media Electronics     | 5        | 4.95%   |
| Logitech                | 4        | 3.96%   |
| JMTek                   | 4        | 3.96%   |
| VIA Technologies        | 1        | 0.99%   |
| SteelSeries ApS         | 1        | 0.99%   |
| SAVITECH                | 1        | 0.99%   |
| Fry's Electronics       | 1        | 0.99%   |
| Focusrite-Novation      | 1        | 0.99%   |
| Elgato Systems          | 1        | 0.99%   |
| EDFIER                  | 1        | 0.99%   |
| Creative Technology     | 1        | 0.99%   |
| Corsair                 | 1        | 0.99%   |
| Cambridge Audio         | 1        | 0.99%   |
| Blue Microphones        | 1        | 0.99%   |
| BEHRINGER International | 1        | 0.99%   |
| ASRock                  | 1        | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 9.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 4.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 4.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 4.13%   |
| JMTek USB PnP Audio Device                                                 | 4        | 3.31%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 3.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 3.31%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 2.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 2.48%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 2.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 1.65%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.65%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.65%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 2        | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.65%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.65%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.65%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.65%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 0.83%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.83%   |
| SAVITECH SA9023 audio controller                                           | 1        | 0.83%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.83%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.83%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.83%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.83%   |
| Nvidia Audio device                                                        | 1        | 0.83%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1        | 0.83%   |
| Logitech CONEXANT USB AUDIO                                                | 1        | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.83%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 8        | 23.53%  |
| Kingston            | 6        | 17.65%  |
| Corsair             | 6        | 17.65%  |
| Unknown             | 3        | 8.82%   |
| Samsung Electronics | 3        | 8.82%   |
| Crucial             | 3        | 8.82%   |
| A-DATA Technology   | 2        | 5.88%   |
| SK hynix            | 1        | 2.94%   |
| Patriot             | 1        | 2.94%   |
| Avant               | 1        | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 5%      |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 2.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 2.5%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 2.5%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2.5%    |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.5%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.5%    |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.5%    |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s      | 1        | 2.5%    |
| Patriot RAM PSD48G24002 8GB DIMM DDR4 2400MT/s           | 1        | 2.5%    |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s      | 1        | 2.5%    |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s        | 1        | 2.5%    |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s     | 1        | 2.5%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 1        | 2.5%    |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.5%    |
| Kingston RAM 99U5471-025.A00LF 4096MB DIMM DDR3 1333MT/s | 1        | 2.5%    |
| Kingston RAM 9905701-017.A00G 16GB DIMM DDR4 2667MT/s    | 1        | 2.5%    |
| G.Skill RAM F4-3600C16-8GVK 8GB DIMM DDR4 3600MT/s       | 1        | 2.5%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 1        | 2.5%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 1        | 2.5%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 1        | 2.5%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 1        | 2.5%    |
| G.Skill RAM F4-2800C17-8GIS 8192MB DIMM DDR4 2800MT/s    | 1        | 2.5%    |
| G.Skill RAM F4-2666C18-4GRS 4GB SODIMM DDR4 2400MT/s     | 1        | 2.5%    |
| G.Skill RAM F3-10666CL7-2GBRH 2048MB DIMM DDR3 1333MT/s  | 1        | 2.5%    |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s     | 1        | 2.5%    |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s     | 1        | 2.5%    |
| Crucial RAM CT16G4DFD824A.M16FJ 16GB DIMM DDR4 2400MT/s  | 1        | 2.5%    |
| Crucial RAM CT16G4DFD824A.M16FD 16GB DIMM DDR4 3200MT/s  | 1        | 2.5%    |
| Crucial RAM CT16G48C40U5.M8A1 16GB DIMM DDR5 4800MT/s    | 1        | 2.5%    |
| Crucial RAM BL25664TN1608.16FF 2048MB DIMM DDR3 1333MT/s | 1        | 2.5%    |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s      | 1        | 2.5%    |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s     | 1        | 2.5%    |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s     | 1        | 2.5%    |
| Corsair RAM CMK32GX4M4D3600C16 8GB DIMM DDR4 3600MT/s    | 1        | 2.5%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 1        | 2.5%    |
| Avant RAM W641GU42J7240NC 8GB DIMM DDR4 2400MT/s         | 1        | 2.5%    |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s              | 1        | 2.5%    |
| A-DATA RAM DDR4 2666 2OZ 16GB DIMM DDR4 3200MT/s         | 1        | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 22       | 64.71%  |
| DDR3    | 9        | 26.47%  |
| Unknown | 2        | 5.88%   |
| DDR5    | 1        | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 33       | 97.06%  |
| SODIMM | 1        | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 48.57%  |
| 4096  | 8        | 22.86%  |
| 16384 | 7        | 20%     |
| 2048  | 2        | 5.71%   |
| 1024  | 1        | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 6        | 15.38%  |
| 2400  | 6        | 15.38%  |
| 3200  | 5        | 12.82%  |
| 1600  | 5        | 12.82%  |
| 1333  | 5        | 12.82%  |
| 3866  | 2        | 5.13%   |
| 3000  | 2        | 5.13%   |
| 4800  | 1        | 2.56%   |
| 3534  | 1        | 2.56%   |
| 3333  | 1        | 2.56%   |
| 2933  | 1        | 2.56%   |
| 2800  | 1        | 2.56%   |
| 2667  | 1        | 2.56%   |
| 1867  | 1        | 2.56%   |
| 1067  | 1        | 2.56%   |

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
| Logitech                      | 6        | 40%     |
| Microdia                      | 2        | 13.33%  |
| MacroSilicon                  | 2        | 13.33%  |
| Sunplus Innovation Technology | 1        | 6.67%   |
| Realtek Semiconductor         | 1        | 6.67%   |
| Microsoft                     | 1        | 6.67%   |
| GEMBIRD                       | 1        | 6.67%   |
| Chicony Electronics           | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 20%     |
| Sunplus USB 2.0 Camera                            | 1        | 6.67%   |
| Realtek FULL HD 1080P Webcam                      | 1        | 6.67%   |
| Microsoft LifeCam HD-3000                         | 1        | 6.67%   |
| Microdia USB 2.0 Camera                           | 1        | 6.67%   |
| Microdia Camera                                   | 1        | 6.67%   |
| MacroSilicon USB Video                            | 1        | 6.67%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1        | 6.67%   |
| Logitech Webcam C930e                             | 1        | 6.67%   |
| Logitech HD Webcam C615                           | 1        | 6.67%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 6.67%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 6.67%   |
| Chicony HP 720p HD Monitor Webcam                 | 1        | 6.67%   |

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
| 0     | 45       | 90%     |
| 1     | 3        | 6%      |
| 2     | 2        | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Sound         | 2        | 28.57%  |
| Net/wireless  | 2        | 28.57%  |
| Graphics card | 2        | 28.57%  |
| Camera        | 1        | 14.29%  |

