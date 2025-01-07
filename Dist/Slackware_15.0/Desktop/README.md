Slackware 15.0 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 71

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550-PLUS         | [7ab225644f](https://linux-hardware.org/?probe=7ab225644f) | Dec 29, 2024 |
| HP            | 8643 SMVB               | [3e1d8b1c0f](https://linux-hardware.org/?probe=3e1d8b1c0f) | Dec 29, 2024 |
| HP            | 8906 SMVB               | [f52f996dd7](https://linux-hardware.org/?probe=f52f996dd7) | Dec 29, 2024 |
| HP            | 1495                    | [0accce2a1a](https://linux-hardware.org/?probe=0accce2a1a) | Dec 29, 2024 |
| Dell          | 0X4N41 A01              | [3aca8429ec](https://linux-hardware.org/?probe=3aca8429ec) | Dec 28, 2024 |
| HP            | 1495                    | [309b63cf7b](https://linux-hardware.org/?probe=309b63cf7b) | Dec 28, 2024 |
| ASUSTek       | H170M-PLUS              | [302ff2daa0](https://linux-hardware.org/?probe=302ff2daa0) | Sep 11, 2024 |
| ASUSTek       | PRIME B760M-A D4        | [23f34741b6](https://linux-hardware.org/?probe=23f34741b6) | Jun 17, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0   | [66de5464ad](https://linux-hardware.org/?probe=66de5464ad) | Jun 07, 2024 |
| ASRock        | B550M-HDV               | [eb41f5c32d](https://linux-hardware.org/?probe=eb41f5c32d) | May 15, 2024 |
| Dell          | 0X9M3X A04              | [4b6904a00b](https://linux-hardware.org/?probe=4b6904a00b) | May 13, 2024 |
| ASUSTek       | ProArt B550-CREATOR     | [37bd870888](https://linux-hardware.org/?probe=37bd870888) | Apr 19, 2024 |
| Gigabyte      | X570 AORUS ELITE        | [7204492392](https://linux-hardware.org/?probe=7204492392) | Mar 05, 2024 |
| MSI           | PRO X670-P WIFI         | [0ef39f433d](https://linux-hardware.org/?probe=0ef39f433d) | Feb 27, 2024 |
| MSI           | MAG B650M MORTAR WIFI   | [2ed279c40d](https://linux-hardware.org/?probe=2ed279c40d) | Feb 16, 2024 |
| ASRock        | B550M-ITX/ac            | [27015117d0](https://linux-hardware.org/?probe=27015117d0) | Feb 13, 2024 |
| MSI           | MAG B650M MORTAR WIFI   | [f536b283c6](https://linux-hardware.org/?probe=f536b283c6) | Jan 27, 2024 |
| MSI           | MAG B650M MORTAR WIFI   | [5dcf737641](https://linux-hardware.org/?probe=5dcf737641) | Jan 15, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2  | [a2ec3f504c](https://linux-hardware.org/?probe=a2ec3f504c) | Jan 14, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2  | [167fddc449](https://linux-hardware.org/?probe=167fddc449) | Jan 14, 2024 |
| MSI           | MAG B650M MORTAR WIFI   | [7e506254e0](https://linux-hardware.org/?probe=7e506254e0) | Dec 22, 2023 |
| Gigabyte      | Z97M-DS3H               | [4fd5ba2289](https://linux-hardware.org/?probe=4fd5ba2289) | Dec 04, 2023 |
| MSI           | X470 GAMING PLUS MAX    | [24ebfe35c8](https://linux-hardware.org/?probe=24ebfe35c8) | Nov 22, 2023 |
| ASUSTek       | P7P55D-E                | [f16aeca403](https://linux-hardware.org/?probe=f16aeca403) | Nov 03, 2023 |
| ASUSTek       | PRIME A320M-K           | [3f7bed61a8](https://linux-hardware.org/?probe=3f7bed61a8) | Jul 26, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2  | [6087b16809](https://linux-hardware.org/?probe=6087b16809) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2  | [dd63c138ad](https://linux-hardware.org/?probe=dd63c138ad) | Jul 15, 2023 |
| Fujitsu       | FujitsuTP7000 -1        | [231d7f8182](https://linux-hardware.org/?probe=231d7f8182) | Jun 18, 2023 |
| MSI           | X99A GAMING 7           | [ec94d173a7](https://linux-hardware.org/?probe=ec94d173a7) | May 23, 2023 |
| ASRock        | N68-S3 FX               | [0ed94fe810](https://linux-hardware.org/?probe=0ed94fe810) | May 10, 2023 |
| HEDYCOMPUT... | IH81MF-Q3               | [3444236ed4](https://linux-hardware.org/?probe=3444236ed4) | Apr 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF       | [7f052050d9](https://linux-hardware.org/?probe=7f052050d9) | Apr 10, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Dell          | 0MY171 A00              | [47fd974afd](https://linux-hardware.org/?probe=47fd974afd) | Mar 20, 2023 |
| ASUSTek       | PRIME B450M-A           | [053498458e](https://linux-hardware.org/?probe=053498458e) | Mar 03, 2023 |
| Dell          | 0MY171 A00              | [795f707b1a](https://linux-hardware.org/?probe=795f707b1a) | Feb 25, 2023 |
| Dell          | 04YP6J A03              | [696cc9b57a](https://linux-hardware.org/?probe=696cc9b57a) | Feb 19, 2023 |
| ASRock        | 990FX Extreme4          | [7ce91f2b1e](https://linux-hardware.org/?probe=7ce91f2b1e) | Feb 16, 2023 |
| ASRock        | N68-S UCC               | [cb4c89a390](https://linux-hardware.org/?probe=cb4c89a390) | Jan 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING | [1c9dc6792e](https://linux-hardware.org/?probe=1c9dc6792e) | Jan 13, 2023 |
| ASRock        | B550 Taichi             | [469f9d71e2](https://linux-hardware.org/?probe=469f9d71e2) | Dec 29, 2022 |
| Dell          | 0MY171 A00              | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| ASUSTek       | SABERTOOTH X99          | [c0bf1336d5](https://linux-hardware.org/?probe=c0bf1336d5) | Dec 12, 2022 |
| HP            | 8906 SMVB               | [d000e4e926](https://linux-hardware.org/?probe=d000e4e926) | Dec 02, 2022 |
| Lenovo        | 31900058 STD            | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| HP            | 3031h                   | [b6849a29a2](https://linux-hardware.org/?probe=b6849a29a2) | Sep 24, 2022 |
| HP            | 3031h                   | [40160588bb](https://linux-hardware.org/?probe=40160588bb) | Sep 20, 2022 |
| MSI           | H110M PRO-VD            | [2299dc1786](https://linux-hardware.org/?probe=2299dc1786) | Sep 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO | [a954ba4e86](https://linux-hardware.org/?probe=a954ba4e86) | Aug 26, 2022 |
| Dell          | 0200DY A03              | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| Gigabyte      | N3160TN                 | [e2f44a8274](https://linux-hardware.org/?probe=e2f44a8274) | May 31, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING    | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| MSI           | 970 GAMING              | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| ASRock        | N68-S3 FX               | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| MSI           | MS-7365                 | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown       | X79-P3                  | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| HP            | 0A08h                   | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| ASRock        | H410M-ITX/ac            | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASUSTek       | PRIME Z390-A            | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Acer          | FMCP7A-ION-LE           | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| ASRock        | H270 Pro4               | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| Lenovo        | 31900058 STD            | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| Biostar       | X470GTA                 | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| MSI           | G31TM-P21               | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP            | 212B                    | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI           | B450 TOMAHAWK MAX       | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| MSI           | G31TM-P21               | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI           | H61M-P31                | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| MSI           | B450M-A PRO MAX         | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek       | SABERTOOTH X99          | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI           | B450M-A PRO MAX         | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Desktops | Percent |
|-----------------|----------|---------|
| 5.15.63         | 6        | 9.38%   |
| 5.15.19         | 6        | 9.38%   |
| 5.19.17-Unraid  | 4        | 6.25%   |
| 5.19.17         | 4        | 6.25%   |
| 5.15.94         | 3        | 4.69%   |
| 6.12.7          | 2        | 3.13%   |
| 6.1.79-Unraid   | 2        | 3.13%   |
| 5.15.30-Unraid  | 2        | 3.13%   |
| 5.15.27         | 2        | 3.13%   |
| 5.15.145        | 2        | 3.13%   |
| 6.7.4-cometdust | 1        | 1.56%   |
| 6.6.7           | 1        | 1.56%   |
| 6.6.22          | 1        | 1.56%   |
| 6.6.18          | 1        | 1.56%   |
| 6.6.11          | 1        | 1.56%   |
| 6.12.1          | 1        | 1.56%   |
| 6.10.7          | 1        | 1.56%   |
| 6.10.5          | 1        | 1.56%   |
| 6.10.0-rc2-rt3  | 1        | 1.56%   |
| 6.1.64-Unraid   | 1        | 1.56%   |
| 6.1.61          | 1        | 1.56%   |
| 6.1.38          | 1        | 1.56%   |
| 6.1.20          | 1        | 1.56%   |
| 6.1.13          | 1        | 1.56%   |
| 5.19.16         | 1        | 1.56%   |
| 5.17.2          | 1        | 1.56%   |
| 5.17.0-custom   | 1        | 1.56%   |
| 5.16.18         | 1        | 1.56%   |
| 5.16.13         | 1        | 1.56%   |
| 5.16.11         | 1        | 1.56%   |
| 5.15.6          | 1        | 1.56%   |
| 5.15.38         | 1        | 1.56%   |
| 5.15.14         | 1        | 1.56%   |
| 5.15.13         | 1        | 1.56%   |
| 5.15.118        | 1        | 1.56%   |
| 5.15.103        | 1        | 1.56%   |
| 5.14.15-Unraid  | 1        | 1.56%   |
| 5.14.15         | 1        | 1.56%   |
| 5.14.12         | 1        | 1.56%   |
| 5.14.11         | 1        | 1.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.19.17  | 8        | 12.5%   |
| 5.15.63  | 6        | 9.38%   |
| 5.15.19  | 6        | 9.38%   |
| 5.15.94  | 3        | 4.69%   |
| 6.12.7   | 2        | 3.13%   |
| 6.1.79   | 2        | 3.13%   |
| 5.15.30  | 2        | 3.13%   |
| 5.15.27  | 2        | 3.13%   |
| 5.15.145 | 2        | 3.13%   |
| 5.14.15  | 2        | 3.13%   |
| 6.7.4    | 1        | 1.56%   |
| 6.6.7    | 1        | 1.56%   |
| 6.6.22   | 1        | 1.56%   |
| 6.6.18   | 1        | 1.56%   |
| 6.6.11   | 1        | 1.56%   |
| 6.12.1   | 1        | 1.56%   |
| 6.10.7   | 1        | 1.56%   |
| 6.10.5   | 1        | 1.56%   |
| 6.10.0   | 1        | 1.56%   |
| 6.1.64   | 1        | 1.56%   |
| 6.1.61   | 1        | 1.56%   |
| 6.1.38   | 1        | 1.56%   |
| 6.1.20   | 1        | 1.56%   |
| 6.1.13   | 1        | 1.56%   |
| 5.19.16  | 1        | 1.56%   |
| 5.17.2   | 1        | 1.56%   |
| 5.17.0   | 1        | 1.56%   |
| 5.16.18  | 1        | 1.56%   |
| 5.16.13  | 1        | 1.56%   |
| 5.16.11  | 1        | 1.56%   |
| 5.15.6   | 1        | 1.56%   |
| 5.15.38  | 1        | 1.56%   |
| 5.15.14  | 1        | 1.56%   |
| 5.15.13  | 1        | 1.56%   |
| 5.15.118 | 1        | 1.56%   |
| 5.15.103 | 1        | 1.56%   |
| 5.14.12  | 1        | 1.56%   |
| 5.14.11  | 1        | 1.56%   |
| 5.13.12  | 1        | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 27       | 43.55%  |
| 5.19    | 9        | 14.52%  |
| 6.1     | 5        | 8.06%   |
| 6.6     | 4        | 6.45%   |
| 5.14    | 4        | 6.45%   |
| 6.12    | 3        | 4.84%   |
| 6.10    | 3        | 4.84%   |
| 5.16    | 3        | 4.84%   |
| 5.17    | 2        | 3.23%   |
| 6.7     | 1        | 1.61%   |
| 5.13    | 1        | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 57       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 20       | 33.9%   |
| XFCE       | 16       | 27.12%  |
| Unknown    | 16       | 27.12%  |
| X-Generic  | 1        | 1.69%   |
| X-Cinnamon | 1        | 1.69%   |
| MATE       | 1        | 1.69%   |
| GNOME      | 1        | 1.69%   |
| FVWM       | 1        | 1.69%   |
| DWM        | 1        | 1.69%   |
| Cinnamon   | 1        | 1.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 30       | 49.18%  |
| Tty     | 17       | 27.87%  |
| Unknown | 9        | 14.75%  |
| Wayland | 5        | 8.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 21       | 35.59%  |
| Unknown | 21       | 35.59%  |
| XDM     | 9        | 15.25%  |
| LightDM | 5        | 8.47%   |
| TDM     | 1        | 1.69%   |
| SLiM    | 1        | 1.69%   |
| GDM     | 1        | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 32       | 55.17%  |
| Unknown     | 12       | 20.69%  |
| en_GB       | 3        | 5.17%   |
| ru_RU       | 2        | 3.45%   |
| it_IT       | 2        | 3.45%   |
| us          | 1        | 1.72%   |
| pt_PT       | 1        | 1.72%   |
| pt_BR       | 1        | 1.72%   |
| ja_JP       | 1        | 1.72%   |
| es_ES.UTF8  | 1        | 1.72%   |
| es_ES       | 1        | 1.72%   |
| en_US.ASCII | 1        | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 30       | 52.63%  |
| BIOS | 27       | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 35       | 61.4%   |
| Btrfs    | 9        | 15.79%  |
| Xfs      | 4        | 7.02%   |
| Tmpfs    | 2        | 3.51%   |
| Rootfs   | 2        | 3.51%   |
| Overlay  | 2        | 3.51%   |
| Reiserfs | 1        | 1.75%   |
| F2fs     | 1        | 1.75%   |
| Ext2     | 1        | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 40       | 68.97%  |
| MBR     | 11       | 18.97%  |
| Unknown | 7        | 12.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 62.07%  |
| Yes       | 22       | 37.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 73.68%  |
| Yes       | 15       | 26.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 14       | 24.56%  |
| MSI                 | 12       | 21.05%  |
| ASRock              | 9        | 15.79%  |
| Hewlett-Packard     | 6        | 10.53%  |
| Gigabyte Technology | 5        | 8.77%   |
| Dell                | 5        | 8.77%   |
| Lenovo              | 1        | 1.75%   |
| HEDYCOMPUTER        | 1        | 1.75%   |
| Fujitsu             | 1        | 1.75%   |
| Biostar             | 1        | 1.75%   |
| Acer                | 1        | 1.75%   |
| Unknown             | 1        | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| MSI MS-7D76                          | 2        | 3.51%   |
| ASRock N68-S3 FX                     | 2        | 3.51%   |
| MSI MS-7D67                          | 1        | 1.75%   |
| MSI MS-7C52                          | 1        | 1.75%   |
| MSI MS-7C02                          | 1        | 1.75%   |
| MSI MS-7B79                          | 1        | 1.75%   |
| MSI MS-7996                          | 1        | 1.75%   |
| MSI MS-7885                          | 1        | 1.75%   |
| MSI MS-7788                          | 1        | 1.75%   |
| MSI MS-7693                          | 1        | 1.75%   |
| MSI MS-7529                          | 1        | 1.75%   |
| MSI MS-7365                          | 1        | 1.75%   |
| Lenovo H50-05 90BH001WIX             | 1        | 1.75%   |
| HP Z440 Workstation                  | 1        | 1.75%   |
| HP xw8400 Workstation                | 1        | 1.75%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 1.75%   |
| HP Desktop M01-F0xxx                 | 1        | 1.75%   |
| HP Compaq dc7900 Small Form Factor   | 1        | 1.75%   |
| HP Compaq 8200 Elite SFF PC          | 1        | 1.75%   |
| HEDYCOMPUTER IH81MF-Q3               | 1        | 1.75%   |
| Gigabyte Z97M-DS3H                   | 1        | 1.75%   |
| Gigabyte X570 AORUS ELITE            | 1        | 1.75%   |
| Gigabyte N3160TN                     | 1        | 1.75%   |
| Gigabyte B550 AORUS ELITE AX V2      | 1        | 1.75%   |
| Gigabyte AB350-Gaming 3              | 1        | 1.75%   |
| Fujitsu FujitsuTP7000                | 1        | 1.75%   |
| Dell Precision WorkStation 690       | 1        | 1.75%   |
| Dell Precision T1650                 | 1        | 1.75%   |
| Dell Precision 3440                  | 1        | 1.75%   |
| Dell OptiPlex 780                    | 1        | 1.75%   |
| Dell OptiPlex 3020                   | 1        | 1.75%   |
| Biostar X470GTA                      | 1        | 1.75%   |
| ASUS TUF Gaming B450-PLUS II         | 1        | 1.75%   |
| ASUS TUF B450-PLUS GAMING            | 1        | 1.75%   |
| ASUS SABERTOOTH 990FX R2.0           | 1        | 1.75%   |
| ASUS ROG STRIX B550-I GAMING         | 1        | 1.75%   |
| ASUS ROG CROSSHAIR VIII HERO         | 1        | 1.75%   |
| ASUS ProArt B550-CREATOR             | 1        | 1.75%   |
| ASUS PRIME Z390-A                    | 1        | 1.75%   |
| ASUS PRIME B760M-A D4                | 1        | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 5        | 8.77%   |
| Dell Precision         | 3        | 5.26%   |
| MSI MS-7D76            | 2        | 3.51%   |
| HP Compaq              | 2        | 3.51%   |
| Dell OptiPlex          | 2        | 3.51%   |
| ASUS TUF               | 2        | 3.51%   |
| ASUS ROG               | 2        | 3.51%   |
| ASRock N68-S3          | 2        | 3.51%   |
| MSI MS-7D67            | 1        | 1.75%   |
| MSI MS-7C52            | 1        | 1.75%   |
| MSI MS-7C02            | 1        | 1.75%   |
| MSI MS-7B79            | 1        | 1.75%   |
| MSI MS-7996            | 1        | 1.75%   |
| MSI MS-7885            | 1        | 1.75%   |
| MSI MS-7788            | 1        | 1.75%   |
| MSI MS-7693            | 1        | 1.75%   |
| MSI MS-7529            | 1        | 1.75%   |
| MSI MS-7365            | 1        | 1.75%   |
| Lenovo H50-05          | 1        | 1.75%   |
| HP Z440                | 1        | 1.75%   |
| HP xw8400              | 1        | 1.75%   |
| HP Pavilion            | 1        | 1.75%   |
| HP Desktop             | 1        | 1.75%   |
| HEDYCOMPUTER IH81MF-Q3 | 1        | 1.75%   |
| Gigabyte Z97M-DS3H     | 1        | 1.75%   |
| Gigabyte X570          | 1        | 1.75%   |
| Gigabyte N3160TN       | 1        | 1.75%   |
| Gigabyte B550          | 1        | 1.75%   |
| Gigabyte AB350-Gaming  | 1        | 1.75%   |
| Fujitsu FujitsuTP7000  | 1        | 1.75%   |
| Biostar X470GTA        | 1        | 1.75%   |
| ASUS SABERTOOTH        | 1        | 1.75%   |
| ASUS ProArt            | 1        | 1.75%   |
| ASUS P7P55D-E          | 1        | 1.75%   |
| ASUS H170M-PLUS        | 1        | 1.75%   |
| ASUS All               | 1        | 1.75%   |
| ASRock N68-S           | 1        | 1.75%   |
| ASRock H410M-ITX       | 1        | 1.75%   |
| ASRock H270            | 1        | 1.75%   |
| ASRock B550M-ITX       | 1        | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 8        | 14.04%  |
| 2019 | 7        | 12.28%  |
| 2022 | 6        | 10.53%  |
| 2011 | 6        | 10.53%  |
| 2015 | 5        | 8.77%   |
| 2017 | 4        | 7.02%   |
| 2014 | 4        | 7.02%   |
| 2018 | 3        | 5.26%   |
| 2012 | 3        | 5.26%   |
| 2008 | 3        | 5.26%   |
| 2021 | 2        | 3.51%   |
| 2010 | 2        | 3.51%   |
| 2009 | 2        | 3.51%   |
| 2016 | 1        | 1.75%   |
| 2007 | 1        | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 57       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 57       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 57       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 16       | 27.12%  |
| 16.01-24.0  | 12       | 20.34%  |
| 8.01-16.0   | 8        | 13.56%  |
| 64.01-256.0 | 6        | 10.17%  |
| 4.01-8.0    | 5        | 8.47%   |
| 3.01-4.0    | 5        | 8.47%   |
| 24.01-32.0  | 4        | 6.78%   |
| 1.01-2.0    | 3        | 5.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 15       | 24.59%  |
| 2.01-3.0   | 14       | 22.95%  |
| 1.01-2.0   | 13       | 21.31%  |
| 0.51-1.0   | 6        | 9.84%   |
| 8.01-16.0  | 5        | 8.2%    |
| 3.01-4.0   | 4        | 6.56%   |
| 16.01-24.0 | 2        | 3.28%   |
| 32.01-64.0 | 1        | 1.64%   |
| 0.01-0.5   | 1        | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 25%     |
| 1      | 13       | 21.67%  |
| 3      | 11       | 18.33%  |
| 4      | 6        | 10%     |
| 6      | 4        | 6.67%   |
| 0      | 4        | 6.67%   |
| 10     | 2        | 3.33%   |
| 9      | 2        | 3.33%   |
| 14     | 1        | 1.67%   |
| 11     | 1        | 1.67%   |
| 5      | 1        | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 63.79%  |
| Yes       | 21       | 36.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 56       | 98.25%  |
| No        | 1        | 1.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 52.63%  |
| Yes       | 27       | 47.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 63.79%  |
| Yes       | 21       | 36.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 16       | 28.07%  |
| UK           | 7        | 12.28%  |
| Italy        | 5        | 8.77%   |
| Brazil       | 4        | 7.02%   |
| Russia       | 3        | 5.26%   |
| Kazakhstan   | 3        | 5.26%   |
| Japan        | 3        | 5.26%   |
| Germany      | 3        | 5.26%   |
| Spain        | 2        | 3.51%   |
| Hong Kong    | 2        | 3.51%   |
| Canada       | 2        | 3.51%   |
| South Africa | 1        | 1.75%   |
| Portugal     | 1        | 1.75%   |
| Poland       | 1        | 1.75%   |
| Malaysia     | 1        | 1.75%   |
| China        | 1        | 1.75%   |
| Australia    | 1        | 1.75%   |
| Argentina    | 1        | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Ust-Kamenogorsk     | 2        | 3.45%   |
| Tokyo               | 2        | 3.45%   |
| San Elizario        | 2        | 3.45%   |
| Rome                | 2        | 3.45%   |
| Milan               | 2        | 3.45%   |
| Gainesville         | 2        | 3.45%   |
| Winter Springs      | 1        | 1.72%   |
| Warsaw              | 1        | 1.72%   |
| Tsukuba             | 1        | 1.72%   |
| Toronto             | 1        | 1.72%   |
| Tatuí              | 1        | 1.72%   |
| St Petersburg       | 1        | 1.72%   |
| Springfield         | 1        | 1.72%   |
| Sham Shui Po        | 1        | 1.72%   |
| Seville             | 1        | 1.72%   |
| Senhora da Hora     | 1        | 1.72%   |
| Seattle             | 1        | 1.72%   |
| Santa Cruz do Sul   | 1        | 1.72%   |
| Saint Paul          | 1        | 1.72%   |
| Rock                | 1        | 1.72%   |
| Rheine              | 1        | 1.72%   |
| Porto Alegre        | 1        | 1.72%   |
| Perm                | 1        | 1.72%   |
| Penrith             | 1        | 1.72%   |
| Newcastle upon Tyne | 1        | 1.72%   |
| Nanping             | 1        | 1.72%   |
| Moscow              | 1        | 1.72%   |
| Milwaukee           | 1        | 1.72%   |
| Mead                | 1        | 1.72%   |
| McKinney            | 1        | 1.72%   |
| Luton               | 1        | 1.72%   |
| London              | 1        | 1.72%   |
| Liverpool           | 1        | 1.72%   |
| Lisbon              | 1        | 1.72%   |
| Leipzig             | 1        | 1.72%   |
| Laval               | 1        | 1.72%   |
| Kuantan             | 1        | 1.72%   |
| Karaganda           | 1        | 1.72%   |
| Harrow              | 1        | 1.72%   |
| Hamburg             | 1        | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 28       | 43     | 22.05%  |
| WDC                   | 22       | 58     | 17.32%  |
| Samsung Electronics   | 21       | 27     | 16.54%  |
| Toshiba               | 9        | 20     | 7.09%   |
| Kingston              | 6        | 8      | 4.72%   |
| Crucial               | 6        | 7      | 4.72%   |
| Hitachi               | 5        | 8      | 3.94%   |
| Transcend             | 3        | 3      | 2.36%   |
| SK hynix              | 2        | 2      | 1.57%   |
| SanDisk               | 2        | 2      | 1.57%   |
| Patriot               | 2        | 2      | 1.57%   |
| A-DATA Technology     | 2        | 2      | 1.57%   |
| ZHITAI                | 1        | 2      | 0.79%   |
| Unknown               | 1        | 2      | 0.79%   |
| Team                  | 1        | 1      | 0.79%   |
| Silicon Motion        | 1        | 2      | 0.79%   |
| Realtek Semiconductor | 1        | 1      | 0.79%   |
| PNY                   | 1        | 2      | 0.79%   |
| Pioneer               | 1        | 1      | 0.79%   |
| Phison Electronics    | 1        | 1      | 0.79%   |
| Maxtor                | 1        | 1      | 0.79%   |
| Lexar                 | 1        | 1      | 0.79%   |
| KIOXIA                | 1        | 2      | 0.79%   |
| Intenso               | 1        | 1      | 0.79%   |
| Intel                 | 1        | 2      | 0.79%   |
| HGST                  | 1        | 1      | 0.79%   |
| Hewlett-Packard       | 1        | 1      | 0.79%   |
| Gigabyte Technology   | 1        | 1      | 0.79%   |
| DUEX                  | 1        | 1      | 0.79%   |
| China                 | 1        | 1      | 0.79%   |
| Unknown               | 1        | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 6        | 3.85%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 3        | 1.92%   |
| Seagate ST4000VN006-3CW104 4TB                      | 3        | 1.92%   |
| Seagate ST4000DM004-2CV104 4TB                      | 3        | 1.92%   |
| Crucial CT500MX500SSD1 500GB                        | 3        | 1.92%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 2        | 1.28%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 1.28%   |
| Seagate ST2000DX001-1NS164 2TB                      | 2        | 1.28%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 1.28%   |
| Seagate ST2000DL003-9VT166 2TB                      | 2        | 1.28%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2        | 1.28%   |
| Seagate Expansion Desk 5TB                          | 2        | 1.28%   |
| Samsung SSD 970 EVO 250GB                           | 2        | 1.28%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 1.28%   |
| ZHITAI SC001 Active 1TB SSD                         | 1        | 0.64%   |
| ZHITAI PC005 Active 512GB                           | 1        | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.64%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1        | 0.64%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.64%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1        | 0.64%   |
| WDC WD80EFZZ-68BTXN0 8TB                            | 1        | 0.64%   |
| WDC WD80EFZX-68UW8N0 8TB                            | 1        | 0.64%   |
| WDC WD80EFBX-68AZZN0 8TB                            | 1        | 0.64%   |
| WDC WD80EFAX-68LHPN0 8TB                            | 1        | 0.64%   |
| WDC WD80EFAX-68KNBN0 8TB                            | 1        | 0.64%   |
| WDC WD8003FFBX-68B9AN0 8TB                          | 1        | 0.64%   |
| WDC WD6003FRYZ-01F0DB0 6TB                          | 1        | 0.64%   |
| WDC WD5000AAKX-22ERMA0 500GB                        | 1        | 0.64%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1        | 0.64%   |
| WDC WD5000AAKS-007AA0 500GB                         | 1        | 0.64%   |
| WDC WD5000AADS-00S9B0 500GB                         | 1        | 0.64%   |
| WDC WD40EJRX-89T1XY0 4TB                            | 1        | 0.64%   |
| WDC WD40EFAX-68JH4N1 4TB                            | 1        | 0.64%   |
| WDC WD400BD-60LTA0 40GB                             | 1        | 0.64%   |
| WDC WD3200AAJS-65B4A0 320GB                         | 1        | 0.64%   |
| WDC WD30EZRX-00SPEB0 3TB                            | 1        | 0.64%   |
| WDC WD30EZRX-00MMMB0 3TB                            | 1        | 0.64%   |
| WDC WD30EZRX-00DC0B0 3TB                            | 1        | 0.64%   |
| WDC WD30EZRX-00D8PB0 3TB                            | 1        | 0.64%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 28       | 43     | 41.79%  |
| WDC                 | 21       | 54     | 31.34%  |
| Toshiba             | 8        | 15     | 11.94%  |
| Hitachi             | 5        | 8      | 7.46%   |
| Samsung Electronics | 2        | 2      | 2.99%   |
| Maxtor              | 1        | 1      | 1.49%   |
| HGST                | 1        | 1      | 1.49%   |
| Unknown             | 1        | 1      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 10     | 20%     |
| Kingston            | 5        | 7      | 14.29%  |
| Crucial             | 4        | 5      | 11.43%  |
| Transcend           | 3        | 3      | 8.57%   |
| WDC                 | 2        | 3      | 5.71%   |
| ZHITAI              | 1        | 1      | 2.86%   |
| Toshiba             | 1        | 3      | 2.86%   |
| Team                | 1        | 1      | 2.86%   |
| SK hynix            | 1        | 1      | 2.86%   |
| SanDisk             | 1        | 1      | 2.86%   |
| PNY                 | 1        | 2      | 2.86%   |
| Pioneer             | 1        | 1      | 2.86%   |
| Patriot             | 1        | 1      | 2.86%   |
| Lexar               | 1        | 1      | 2.86%   |
| Intenso             | 1        | 1      | 2.86%   |
| Intel               | 1        | 2      | 2.86%   |
| Hewlett-Packard     | 1        | 1      | 2.86%   |
| DUEX                | 1        | 1      | 2.86%   |
| China               | 1        | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 125    | 43.62%  |
| SSD  | 30       | 46     | 31.91%  |
| NVMe | 23       | 36     | 24.47%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 48       | 168    | 64.86%  |
| NVMe | 23       | 36     | 31.08%  |
| SAS  | 3        | 3      | 4.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 33       | 47     | 35.48%  |
| 0.51-1.0   | 18       | 38     | 19.35%  |
| 3.01-4.0   | 14       | 26     | 15.05%  |
| 1.01-2.0   | 13       | 16     | 13.98%  |
| 4.01-10.0  | 9        | 29     | 9.68%   |
| 2.01-3.0   | 5        | 13     | 5.38%   |
| 10.01-20.0 | 1        | 2      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 16.67%  |
| Unknown        | 10       | 16.67%  |
| 1001-2000      | 9        | 15%     |
| 501-1000       | 8        | 13.33%  |
| 251-500        | 6        | 10%     |
| 2001-3000      | 6        | 10%     |
| More than 3000 | 5        | 8.33%   |
| 1-20           | 4        | 6.67%   |
| 51-100         | 2        | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 18.33%  |
| Unknown        | 10       | 16.67%  |
| 251-500        | 8        | 13.33%  |
| 1-20           | 8        | 13.33%  |
| 501-1000       | 8        | 13.33%  |
| 1001-2000      | 5        | 8.33%   |
| 21-50          | 3        | 5%      |
| 51-100         | 3        | 5%      |
| More than 3000 | 2        | 3.33%   |
| 2001-3000      | 2        | 3.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB              | 2        | 3      | 10.53%  |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 5.26%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1        | 1      | 5.26%   |
| WDC WD40EFAX-68JH4N1 4TB              | 1        | 4      | 5.26%   |
| WDC WD3200AAJS-65B4A0 320GB           | 1        | 1      | 5.26%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1        | 1      | 5.26%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1        | 1      | 5.26%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 5.26%   |
| Seagate ST380011A 80GB                | 1        | 1      | 5.26%   |
| Seagate ST3000VX006-1HH166 3TB        | 1        | 1      | 5.26%   |
| Seagate ST2000DL003-9VT166 2TB        | 1        | 1      | 5.26%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1        | 1      | 5.26%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 2      | 5.26%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 5.26%   |
| Hitachi HUA723030ALA640 3TB           | 1        | 1      | 5.26%   |
| Hitachi HDS721016CLA382 160GB         | 1        | 1      | 5.26%   |
| DUEX DX300256A5xnEMLC 256GB SSD       | 1        | 1      | 5.26%   |
| Unknown                               | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 13     | 47.06%  |
| Seagate             | 4        | 6      | 23.53%  |
| Hitachi             | 2        | 2      | 11.76%  |
| Samsung Electronics | 1        | 1      | 5.88%   |
| DUEX                | 1        | 1      | 5.88%   |
| Unknown             | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 12     | 50%     |
| Seagate | 4        | 6      | 28.57%  |
| Hitachi | 2        | 2      | 14.29%  |
| Unknown | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 21     | 80%     |
| SSD  | 2        | 2      | 13.33%  |
| NVMe | 1        | 1      | 6.67%   |

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
| Works    | 43       | 146    | 59.72%  |
| Malfunc  | 15       | 24     | 20.83%  |
| Detected | 14       | 37     | 19.44%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 27       | 25.96%  |
| Intel                        | 25       | 24.04%  |
| Samsung Electronics          | 13       | 12.5%   |
| ASMedia Technology           | 8        | 7.69%   |
| Marvell Technology Group     | 5        | 4.81%   |
| Nvidia                       | 4        | 3.85%   |
| Realtek Semiconductor        | 3        | 2.88%   |
| JMicron Technology           | 3        | 2.88%   |
| SanDisk                      | 2        | 1.92%   |
| Micron/Crucial Technology    | 2        | 1.92%   |
| Yangtze Memory Technologies  | 1        | 0.96%   |
| Toshiba America Info Systems | 1        | 0.96%   |
| SK hynix                     | 1        | 0.96%   |
| Silicon Motion               | 1        | 0.96%   |
| Phison Electronics           | 1        | 0.96%   |
| Nextorage                    | 1        | 0.96%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.96%   |
| LSI Logic / Symbios Logic    | 1        | 0.96%   |
| Lite-On Technology           | 1        | 0.96%   |
| KIOXIA                       | 1        | 0.96%   |
| Kingston Technology Company  | 1        | 0.96%   |
| Adaptec                      | 1        | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                   | 11       | 8.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                         | 10       | 7.63%   |
| AMD 400 Series Chipset SATA Controller                                | 9        | 6.87%   |
| AMD 500 Series Chipset SATA Controller                                | 6        | 4.58%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                         | 5        | 3.82%   |
| Nvidia MCP61 SATA Controller                                          | 3        | 2.29%   |
| Nvidia MCP61 IDE                                                      | 3        | 2.29%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller      | 3        | 2.29%   |
| Intel SATA Controller [RAID mode]                                     | 3        | 2.29%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]            | 3        | 2.29%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]      | 3        | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                     | 3        | 2.29%   |
| AMD 600 Series Chipset SATA Controller                                | 3        | 2.29%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)  | 2        | 1.53%   |
| JMicron JMB58x AHCI SATA controller                                   | 2        | 1.53%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                  | 2        | 1.53%   |
| Intel 631xESB/632xESB IDE Controller                                  | 2        | 1.53%   |
| Intel 4 Series Chipset PT IDER Controller                             | 2        | 1.53%   |
| Yangtze Memory ZHITAI PC005 NVMe SSD                                  | 1        | 0.76%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                  | 1        | 0.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                  | 1        | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers     | 1        | 0.76%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                            | 1        | 0.76%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                 | 1        | 0.76%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)            | 1        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                        | 1        | 0.76%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                           | 1        | 0.76%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                     | 1        | 0.76%   |
| Realtek RTS5763DL x2 NVMe SSD Controller                              | 1        | 0.76%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                     | 1        | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                      | 1        | 0.76%   |
| Nvidia MCP79 AHCI Controller                                          | 1        | 0.76%   |
| Nextorage NE1N NVMe SSD                                               | 1        | 0.76%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)              | 1        | 0.76%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B       | 1        | 0.76%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]               | 1        | 0.76%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                 | 1        | 0.76%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI | 1        | 0.76%   |
| Lite-On CAZ-82512 NVMe SSD                                            | 1        | 0.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                            | 1        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 43       | 47.25%  |
| NVMe | 24       | 26.37%  |
| IDE  | 15       | 16.48%  |
| RAID | 7        | 7.69%   |
| SCSI | 2        | 2.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 30       | 52.63%  |
| Intel  | 27       | 47.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 5.17%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 3.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 3.45%   |
| AMD Ryzen 9 7900 12-Core Processor          | 2        | 3.45%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 3.45%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 3.45%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 3.45%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 3.45%   |
| AMD Athlon II X2 250 Processor              | 2        | 3.45%   |
| Intel Xeon CPU X5355 @ 2.66GHz              | 1        | 1.72%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz         | 1        | 1.72%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 1.72%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 1.72%   |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 1.72%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 1.72%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 1.72%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 1.72%   |
| Intel Core i9-10900 CPU @ 2.80GHz           | 1        | 1.72%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 1.72%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.72%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 1.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.72%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.72%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 1.72%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 1.72%   |
| Intel Celeron CPU N3160 @ 1.60GHz           | 1        | 1.72%   |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 1.72%   |
| Intel 12th Gen Core i5-12400                | 1        | 1.72%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 1        | 1.72%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 1.72%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics  | 1        | 1.72%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 1        | 1.72%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 1.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 1        | 1.72%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 1        | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i7      | 7        | 12.07%  |
| AMD Ryzen 9        | 7        | 12.07%  |
| AMD Ryzen 5        | 7        | 12.07%  |
| AMD Ryzen 7        | 6        | 10.34%  |
| Intel Xeon         | 5        | 8.62%   |
| Intel Core i5      | 5        | 8.62%   |
| AMD FX             | 4        | 6.9%    |
| Intel Core 2 Duo   | 3        | 5.17%   |
| Intel Pentium      | 2        | 3.45%   |
| AMD Ryzen 3        | 2        | 3.45%   |
| AMD Athlon II X2   | 2        | 3.45%   |
| Other              | 1        | 1.72%   |
| Intel Pentium Dual | 1        | 1.72%   |
| Intel Core i9      | 1        | 1.72%   |
| Intel Core i3      | 1        | 1.72%   |
| Intel Celeron      | 1        | 1.72%   |
| Intel Atom         | 1        | 1.72%   |
| AMD Ryzen 7 PRO    | 1        | 1.72%   |
| AMD A8             | 1        | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 20       | 34.48%  |
| 2      | 10       | 17.24%  |
| 8      | 9        | 15.52%  |
| 6      | 8        | 13.79%  |
| 16     | 4        | 6.9%    |
| 12     | 3        | 5.17%   |
| 10     | 2        | 3.45%   |
| 14     | 1        | 1.72%   |
| 3      | 1        | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 55       | 96.49%  |
| 2      | 2        | 3.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 38       | 66.67%  |
| 1      | 19       | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 57       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 32.76%  |
| 0x08701021 | 6        | 10.34%  |
| 0x306f2    | 3        | 5.17%   |
| 0x306c3    | 2        | 3.45%   |
| 0x306a9    | 2        | 3.45%   |
| 0x1067a    | 2        | 3.45%   |
| 0x0a50000c | 2        | 3.45%   |
| 0x0a201016 | 2        | 3.45%   |
| 0xa0653    | 1        | 1.72%   |
| 0x906ea    | 1        | 1.72%   |
| 0x906e9    | 1        | 1.72%   |
| 0x6fd      | 1        | 1.72%   |
| 0x6fb      | 1        | 1.72%   |
| 0x506e3    | 1        | 1.72%   |
| 0x406c4    | 1        | 1.72%   |
| 0x306e4    | 1        | 1.72%   |
| 0x20655    | 1        | 1.72%   |
| 0x106c2    | 1        | 1.72%   |
| 0x0a20120a | 1        | 1.72%   |
| 0x0a20102b | 1        | 1.72%   |
| 0x08108109 | 1        | 1.72%   |
| 0x0810100b | 1        | 1.72%   |
| 0x0800820d | 1        | 1.72%   |
| 0x08001126 | 1        | 1.72%   |
| 0x07030105 | 1        | 1.72%   |
| 0x06000822 | 1        | 1.72%   |
| 0x010000b6 | 1        | 1.72%   |
| 0x00000000 | 1        | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 7        | 12.28%  |
| Zen 2       | 7        | 12.28%  |
| Haswell     | 6        | 10.53%  |
| Zen+        | 4        | 7.02%   |
| Unknown     | 4        | 7.02%   |
| Penryn      | 3        | 5.26%   |
| KabyLake    | 3        | 5.26%   |
| IvyBridge   | 3        | 5.26%   |
| Core        | 3        | 5.26%   |
| Zen         | 2        | 3.51%   |
| SandyBridge | 2        | 3.51%   |
| Piledriver  | 2        | 3.51%   |
| K10         | 2        | 3.51%   |
| CometLake   | 2        | 3.51%   |
| Bulldozer   | 2        | 3.51%   |
| Westmere    | 1        | 1.75%   |
| Skylake     | 1        | 1.75%   |
| Silvermont  | 1        | 1.75%   |
| Puma        | 1        | 1.75%   |
| Bonnell     | 1        | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 23       | 38.98%  |
| Nvidia | 22       | 37.29%  |
| Intel  | 14       | 23.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4        | 6.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 4.76%   |
| AMD Raphael                                                                              | 3        | 4.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 4.76%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3        | 4.76%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 3.17%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 3.17%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 3.17%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 2        | 3.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 3.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.17%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                                | 2        | 3.17%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 3.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 3.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.59%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                                        | 1        | 1.59%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 1.59%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1        | 1.59%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1        | 1.59%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1        | 1.59%   |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 1.59%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 1.59%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1        | 1.59%   |
| Nvidia C79 [ION]                                                                         | 1        | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.59%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.59%   |
| Intel HD Graphics 610                                                                    | 1        | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.59%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 1        | 1.59%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.59%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.59%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 1.59%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]                    | 1        | 1.59%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                                  | 1        | 1.59%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                                         | 1        | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 21       | 36.84%  |
| 1 x AMD        | 18       | 31.58%  |
| 1 x Intel      | 11       | 19.3%   |
| 2 x AMD        | 4        | 7.02%   |
| Other          | 1        | 1.75%   |
| Intel + Nvidia | 1        | 1.75%   |
| Intel + AMD    | 1        | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 43       | 75.44%  |
| Proprietary | 9        | 15.79%  |
| Unknown     | 5        | 8.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 40.35%  |
| 7.01-8.0   | 6        | 10.53%  |
| 1.01-2.0   | 6        | 10.53%  |
| 0.51-1.0   | 6        | 10.53%  |
| 0.01-0.5   | 6        | 10.53%  |
| 8.01-16.0  | 4        | 7.02%   |
| 3.01-4.0   | 3        | 5.26%   |
| 5.01-6.0   | 1        | 1.75%   |
| 2.01-3.0   | 1        | 1.75%   |
| 16.01-24.0 | 1        | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 8        | 15.38%  |
| Dell                    | 8        | 15.38%  |
| Hewlett-Packard         | 5        | 9.62%   |
| Goldstar                | 5        | 9.62%   |
| BenQ                    | 5        | 9.62%   |
| Ancor Communications    | 3        | 5.77%   |
| Acer                    | 3        | 5.77%   |
| AOC                     | 2        | 3.85%   |
| Wacom                   | 1        | 1.92%   |
| ViewSonic               | 1        | 1.92%   |
| Toshiba                 | 1        | 1.92%   |
| TopView                 | 1        | 1.92%   |
| RTK                     | 1        | 1.92%   |
| MSI                     | 1        | 1.92%   |
| Lenovo                  | 1        | 1.92%   |
| IOD                     | 1        | 1.92%   |
| GDH                     | 1        | 1.92%   |
| CTC                     | 1        | 1.92%   |
| Chi Mei Optoelectronics | 1        | 1.92%   |
| ASUSTek Computer        | 1        | 1.92%   |
| Unknown                 | 1        | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch               | 2        | 3.77%   |
| Goldstar LG HDR WQHD GSM7756 3440x1440 820x340mm 34.9-inch              | 2        | 3.77%   |
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch                | 1        | 1.89%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch              | 1        | 1.89%   |
| Toshiba TV TSB0108 1920x540                                             | 1        | 1.89%   |
| TopView HDMI TOP0814 1600x900 430x270mm 20.0-inch                       | 1        | 1.89%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                        | 1        | 1.89%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 433x271mm 20.1-inch    | 1        | 1.89%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch    | 1        | 1.89%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch    | 1        | 1.89%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch      | 1        | 1.89%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch       | 1        | 1.89%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch       | 1        | 1.89%   |
| Samsung Electronics LCD Monitor U28D590 3840x2160                       | 1        | 1.89%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 1        | 1.89%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                  | 1        | 1.89%   |
| MSI MAG342CQPV MSI4DB6 3440x1440 797x333mm 34.0-inch                    | 1        | 1.89%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch                  | 1        | 1.89%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                    | 1        | 1.89%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch              | 1        | 1.89%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch            | 1        | 1.89%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch            | 1        | 1.89%   |
| Goldstar W1952 GSM4B77 1440x900 410x260mm 19.1-inch                     | 1        | 1.89%   |
| Goldstar E2260 GSM57DF 1920x1080 477x268mm 21.5-inch                    | 1        | 1.89%   |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                     | 1        | 1.89%   |
| GDH TV PHILCO GDH0030 1920x1080 1150x650mm 52.0-inch                    | 1        | 1.89%   |
| Dell U2722D DEL422D 2560x1440 597x336mm 27.0-inch                       | 1        | 1.89%   |
| Dell SP2208WFP DEL4038 1680x1050 473x296mm 22.0-inch                    | 1        | 1.89%   |
| Dell SE2219H DELF10F 1920x1080 476x268mm 21.5-inch                      | 1        | 1.89%   |
| Dell LCD Monitor P190S 3200x1080                                        | 1        | 1.89%   |
| Dell G2723HN DEL4281 1920x1080 597x336mm 27.0-inch                      | 1        | 1.89%   |
| Dell E1913 DELD051 1440x900 408x255mm 18.9-inch                         | 1        | 1.89%   |
| Dell DELL2407WFPHC DELA026 1920x1200 519x324mm 24.1-inch                | 1        | 1.89%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                       | 1        | 1.89%   |
| CTC KD02909-8770A CTC0770 1024x768 304x228mm 15.0-inch                  | 1        | 1.89%   |
| Chi Mei Optoelectronics CMC 22 W CMO2228 1680x1050 473x296mm 22.0-inch  | 1        | 1.89%   |
| BenQ VZ2770H BNQ7B3C 1920x1080 598x336mm 27.0-inch                      | 1        | 1.89%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                       | 1        | 1.89%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                       | 1        | 1.89%   |
| BenQ G610HDAL BNQ785B 1366x768 344x194mm 15.5-inch                      | 1        | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 22       | 42.31%  |
| 3840x2160 (4K)     | 4        | 7.69%   |
| 3440x1440          | 4        | 7.69%   |
| 1366x768 (WXGA)    | 4        | 7.69%   |
| 1280x1024 (SXGA)   | 4        | 7.69%   |
| 1680x1050 (WSXGA+) | 3        | 5.77%   |
| 2560x1440 (QHD)    | 2        | 3.85%   |
| 1920x1200 (WUXGA)  | 2        | 3.85%   |
| 1440x900 (WXGA+)   | 2        | 3.85%   |
| 3200x1080          | 1        | 1.92%   |
| 1920x540           | 1        | 1.92%   |
| 1600x1200          | 1        | 1.92%   |
| 1024x768 (XGA)     | 1        | 1.92%   |
| Unknown            | 1        | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 9        | 17.31%  |
| 24      | 7        | 13.46%  |
| 21      | 6        | 11.54%  |
| 22      | 3        | 5.77%   |
| 20      | 3        | 5.77%   |
| 19      | 3        | 5.77%   |
| 15      | 3        | 5.77%   |
| Unknown | 3        | 5.77%   |
| 35      | 2        | 3.85%   |
| 34      | 2        | 3.85%   |
| 23      | 2        | 3.85%   |
| 18      | 2        | 3.85%   |
| 17      | 2        | 3.85%   |
| 84      | 1        | 1.92%   |
| 72      | 1        | 1.92%   |
| 52      | 1        | 1.92%   |
| 46      | 1        | 1.92%   |
| 31      | 1        | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 33.33%  |
| 401-500     | 14       | 27.45%  |
| 301-350     | 5        | 9.8%    |
| Unknown     | 3        | 5.88%   |
| 801-900     | 2        | 3.92%   |
| 701-800     | 2        | 3.92%   |
| 601-700     | 2        | 3.92%   |
| 351-400     | 2        | 3.92%   |
| 1501-2000   | 2        | 3.92%   |
| 1001-1500   | 2        | 3.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 59.18%  |
| 16/10   | 8        | 16.33%  |
| 5/4     | 4        | 8.16%   |
| 21/9    | 4        | 8.16%   |
| 4/3     | 2        | 4.08%   |
| Unknown | 2        | 4.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 27.45%  |
| 301-350        | 9        | 17.65%  |
| 151-200        | 8        | 15.69%  |
| 351-500        | 5        | 9.8%    |
| More than 1000 | 3        | 5.88%   |
| 141-150        | 3        | 5.88%   |
| 101-110        | 3        | 5.88%   |
| Unknown        | 3        | 5.88%   |
| 251-300        | 2        | 3.92%   |
| 501-1000       | 1        | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 58.82%  |
| 101-120 | 14       | 27.45%  |
| 1-50    | 3        | 5.88%   |
| Unknown | 3        | 5.88%   |
| 121-160 | 1        | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 80.7%   |
| 0     | 7        | 12.28%  |
| 2     | 3        | 5.26%   |
| 3     | 1        | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 35       | 42.68%  |
| Intel                           | 22       | 26.83%  |
| Ralink Technology               | 4        | 4.88%   |
| Qualcomm Atheros                | 4        | 4.88%   |
| MediaTek                        | 4        | 4.88%   |
| Nvidia                          | 3        | 3.66%   |
| Broadcom                        | 3        | 3.66%   |
| TP-Link                         | 2        | 2.44%   |
| Ralink                          | 1        | 1.22%   |
| Qualcomm Atheros Communications | 1        | 1.22%   |
| Qualcomm                        | 1        | 1.22%   |
| Dell                            | 1        | 1.22%   |
| Broadcom Limited                | 1        | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 23       | 25.27%  |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 5.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 4.4%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 3        | 3.3%    |
| Intel Wi-Fi 6 AX200                                                           | 3        | 3.3%    |
| Intel Ethernet Controller I225-V                                              | 3        | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 3.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 2.2%    |
| Ralink MT7601U Wireless Adapter                                               | 2        | 2.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 2.2%    |
| Nvidia MCP61 Ethernet                                                         | 2        | 2.2%    |
| Intel I211 Gigabit Network Connection                                         | 2        | 2.2%    |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 2.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 2.2%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 2.2%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 2        | 2.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.1%    |
| TP-Link 802.11ac NIC                                                          | 1        | 1.1%    |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 1.1%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.1%    |
| Ralink RT5372 Wireless Adapter                                                | 1        | 1.1%    |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 1.1%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 1.1%    |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 1.1%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 1.1%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 1.1%    |
| Qualcomm Airtel 4G                                                            | 1        | 1.1%    |
| Nvidia MCP79 Ethernet                                                         | 1        | 1.1%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1        | 1.1%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 1.1%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1        | 1.1%    |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 1.1%    |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 1.1%    |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 1.1%    |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.1%    |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 1.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 28.57%  |
| Realtek Semiconductor           | 4        | 14.29%  |
| Ralink Technology               | 4        | 14.29%  |
| MediaTek                        | 4        | 14.29%  |
| Qualcomm Atheros                | 3        | 10.71%  |
| TP-Link                         | 2        | 7.14%   |
| Ralink                          | 1        | 3.57%   |
| Qualcomm Atheros Communications | 1        | 3.57%   |
| Dell                            | 1        | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 3        | 10.71%  |
| Intel Wi-Fi 6 AX200                                                           | 3        | 10.71%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 7.14%   |
| Ralink MT7601U Wireless Adapter                                               | 2        | 7.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 7.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 3.57%   |
| TP-Link 802.11ac NIC                                                          | 1        | 3.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 3.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 3.57%   |
| Ralink RT5372 Wireless Adapter                                                | 1        | 3.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 3.57%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 3.57%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 3.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 3.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 3.57%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 3.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1        | 3.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 3.57%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1        | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1        | 3.57%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]         | 1        | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 34       | 53.97%  |
| Intel                 | 19       | 30.16%  |
| Nvidia                | 3        | 4.76%   |
| Broadcom              | 3        | 4.76%   |
| Qualcomm Atheros      | 2        | 3.17%   |
| Qualcomm              | 1        | 1.59%   |
| Broadcom Limited      | 1        | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23       | 36.51%  |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 7.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 6.35%   |
| Intel Ethernet Controller I225-V                                       | 3        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 4.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 3.17%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 3.17%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 3.17%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 3.17%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 3.17%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2        | 3.17%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1        | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.59%   |
| Qualcomm Airtel 4G                                                     | 1        | 1.59%   |
| Nvidia MCP79 Ethernet                                                  | 1        | 1.59%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 1.59%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.59%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 1.59%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 1.59%   |
| Intel Ethernet Connection (12) I219-V                                  | 1        | 1.59%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1        | 1.59%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 1        | 1.59%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 1        | 1.59%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 1        | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 67.47%  |
| WiFi     | 27       | 32.53%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 43       | 75.44%  |
| WiFi     | 14       | 24.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 60.34%  |
| 2     | 17       | 29.31%  |
| 3     | 2        | 3.45%   |
| 0     | 2        | 3.45%   |
| 5     | 1        | 1.72%   |
| 4     | 1        | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 84.48%  |
| Yes  | 9        | 15.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 6        | 27.27%  |
| Cambridge Silicon Radio  | 6        | 27.27%  |
| MediaTek                 | 5        | 22.73%  |
| Realtek Semiconductor    | 2        | 9.09%   |
| TP-Link                  | 1        | 4.55%   |
| Micro Star International | 1        | 4.55%   |
| Broadcom                 | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 27.27%  |
| MediaTek Wireless_Device                            | 5        | 22.73%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 9.09%   |
| Intel AX200 Bluetooth                               | 2        | 9.09%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1        | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.55%   |
| Realtek Bluetooth Radio                             | 1        | 4.55%   |
| Micro Star International Bluetooth Dongle           | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.55%   |
| Intel AX210 Bluetooth                               | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 30       | 34.88%  |
| Intel                    | 21       | 24.42%  |
| Nvidia                   | 18       | 20.93%  |
| Creative Labs            | 6        | 6.98%   |
| Micro Star International | 3        | 3.49%   |
| Kingston Technology      | 2        | 2.33%   |
| Texas Instruments        | 1        | 1.16%   |
| RME                      | 1        | 1.16%   |
| Holtek Semiconductor     | 1        | 1.16%   |
| DSEA A/S                 | 1        | 1.16%   |
| C-Media Electronics      | 1        | 1.16%   |
| ASUSTek Computer         | 1        | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 12       | 10.71%  |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 8        | 7.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 3.57%   |
| AMD Navi 31 HDMI/DP Audio                                                                         | 4        | 3.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4        | 3.57%   |
| Nvidia MCP61 High Definition Audio                                                                | 3        | 2.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3        | 2.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 2.68%   |
| Micro Star International USB Audio                                                                | 3        | 2.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3        | 2.68%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 3        | 2.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3        | 2.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3        | 2.68%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2        | 1.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 1.79%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2        | 1.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2        | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2        | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.79%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 1.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 1.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 1.79%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1        | 0.89%   |
| RME ADI-2 DAC (58830487)                                                                          | 1        | 0.89%   |
| Nvidia MCP79 High Definition Audio                                                                | 1        | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 0.89%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 0.89%   |
| Kingston Technology HyperX Amp                                                                    | 1        | 0.89%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1        | 0.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 0.89%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 0.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 0.89%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 0.89%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 10       | 16.67%  |
| Corsair             | 10       | 16.67%  |
| Samsung Electronics | 6        | 10%     |
| G.Skill             | 6        | 10%     |
| Unknown             | 5        | 8.33%   |
| Crucial             | 4        | 6.67%   |
| SK hynix            | 3        | 5%      |
| Team                | 2        | 3.33%   |
| AMD                 | 2        | 3.33%   |
| A-DATA Technology   | 2        | 3.33%   |
| Unknown             | 2        | 3.33%   |
| Transcend           | 1        | 1.67%   |
| Strontium           | 1        | 1.67%   |
| Smart               | 1        | 1.67%   |
| Silicon Power       | 1        | 1.67%   |
| Patriot             | 1        | 1.67%   |
| Micron Technology   | 1        | 1.67%   |
| GOODRAM             | 1        | 1.67%   |
| GLOWAY              | 1        | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 2        | 2.99%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 2        | 2.99%   |
| Unknown                                                   | 2        | 2.99%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                  | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                  | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 1.49%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s     | 1        | 1.49%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s        | 1        | 1.49%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 1        | 1.49%   |
| Strontium RAM SRT4G86U1-P9H 4GB DIMM DDR3 1333MT/s        | 1        | 1.49%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1GB FB-DIMM DDR2 667MT/s  | 1        | 1.49%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s | 1        | 1.49%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s | 1        | 1.49%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s      | 1        | 1.49%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s       | 1        | 1.49%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s       | 1        | 1.49%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s    | 1        | 1.49%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s       | 1        | 1.49%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 2733MT/s       | 1        | 1.49%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s           | 1        | 1.49%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s        | 1        | 1.49%   |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s           | 1        | 1.49%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s      | 1        | 1.49%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s      | 1        | 1.49%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Kingston RAM HP32D4U2S8MR-8 8GB DIMM DDR4 3200MT/s        | 1        | 1.49%   |
| Kingston RAM ACR128X64D2S800C6 1GB SODIMM DDR 975MT/s     | 1        | 1.49%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3600MT/s     | 1        | 1.49%   |
| Kingston RAM 9905743-151.A00G 8GB DIMM DDR4 3200MT/s      | 1        | 1.49%   |
| Kingston RAM 9905678-023.A00G 8GB DIMM DDR4 2400MT/s      | 1        | 1.49%   |
| GOODRAM RAM GR2666D464L19S/8G 8GB DIMM DDR4 2667MT/s      | 1        | 1.49%   |
| GLOWAY RAM TYA4U2666D19161C 16384MB DIMM DDR4 2667MT/s    | 1        | 1.49%   |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s     | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 29       | 58%     |
| DDR3  | 14       | 28%     |
| DDR2  | 3        | 6%      |
| SDRAM | 2        | 4%      |
| DDR5  | 1        | 2%      |
| DDR   | 1        | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 48       | 94.12%  |
| SODIMM  | 1        | 1.96%   |
| RIMM    | 1        | 1.96%   |
| FB-DIMM | 1        | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 20       | 35.71%  |
| 16384 | 13       | 23.21%  |
| 4096  | 12       | 21.43%  |
| 2048  | 5        | 8.93%   |
| 32768 | 4        | 7.14%   |
| 1024  | 2        | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 8        | 13.56%  |
| 3200    | 7        | 11.86%  |
| 3600    | 5        | 8.47%   |
| 2400    | 5        | 8.47%   |
| 1333    | 4        | 6.78%   |
| 3800    | 3        | 5.08%   |
| 2667    | 3        | 5.08%   |
| 2133    | 3        | 5.08%   |
| 3733    | 2        | 3.39%   |
| Unknown | 2        | 3.39%   |
| 65535   | 1        | 1.69%   |
| 4800    | 1        | 1.69%   |
| 4000    | 1        | 1.69%   |
| 3666    | 1        | 1.69%   |
| 3400    | 1        | 1.69%   |
| 3000    | 1        | 1.69%   |
| 2933    | 1        | 1.69%   |
| 2800    | 1        | 1.69%   |
| 2733    | 1        | 1.69%   |
| 2666    | 1        | 1.69%   |
| 2200    | 1        | 1.69%   |
| 2000    | 1        | 1.69%   |
| 1867    | 1        | 1.69%   |
| 1866    | 1        | 1.69%   |
| 975     | 1        | 1.69%   |
| 667     | 1        | 1.69%   |
| 533     | 1        | 1.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| QinHeng Electronics | 1        | 16.67%  |
| Prolific Technology | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |
| Dell                | 1        | 16.67%  |
| Canon               | 1        | 16.67%  |
| Brother Industries  | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| QinHeng CH340S                | 1        | 16.67%  |
| Prolific PL2305 Parallel Port | 1        | 16.67%  |
| HP OfficeJet Pro 9010 series  | 1        | 16.67%  |
| Dell 2330d Laser Printer      | 1        | 16.67%  |
| Canon CanoScan LiDE 300       | 1        | 16.67%  |
| Brother HL-L5102DW            | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 2        | 66.67%  |
| Seiko Epson | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20            | 1        | 33.33%  |
| Canon CanoScan LIDE 25                        | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 7        | 53.85%  |
| Sunplus Innovation Technology | 2        | 15.38%  |
| Z-Star Microelectronics       | 1        | 7.69%   |
| Samsung Electronics           | 1        | 7.69%   |
| Microsoft                     | 1        | 7.69%   |
| Microdia                      | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 3        | 23.08%  |
| Z-Star Vimicro USB2.0 Camera            | 1        | 7.69%   |
| Sunplus Full HD webcam                  | 1        | 7.69%   |
| Sunplus DICOTA 4K                       | 1        | 7.69%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 7.69%   |
| Microsoft LifeCam HD-3000               | 1        | 7.69%   |
| Microdia Camera                         | 1        | 7.69%   |
| Logitech QuickCam Pro 9000              | 1        | 7.69%   |
| Logitech Logitech Webcam C160           | 1        | 7.69%   |
| Logitech HD Webcam C910                 | 1        | 7.69%   |
| Logitech C922 Pro Stream Webcam         | 1        | 7.69%   |

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


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 36       | 61.02%  |
| 1     | 14       | 23.73%  |
| 2     | 5        | 8.47%   |
| 4     | 2        | 3.39%   |
| 5     | 1        | 1.69%   |
| 3     | 1        | 1.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 11       | 30.56%  |
| Graphics card            | 7        | 19.44%  |
| Net/wireless             | 5        | 13.89%  |
| Unassigned class         | 3        | 8.33%   |
| Communication controller | 3        | 8.33%   |
| Camera                   | 2        | 5.56%   |
| Storage/raid             | 1        | 2.78%   |
| Storage/ide              | 1        | 2.78%   |
| Net/ethernet             | 1        | 2.78%   |
| Chipcard                 | 1        | 2.78%   |
| Bluetooth                | 1        | 2.78%   |

