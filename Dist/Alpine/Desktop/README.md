Alpine - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Alpine.

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

Total: 62

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 83E2                        | [0db8dcbc23](https://linux-hardware.org/?probe=0db8dcbc23) | May 28, 2023 |
| MSI           | MAG B460M MORTAR            | [da74cacf64](https://linux-hardware.org/?probe=da74cacf64) | May 18, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [429dc207a6](https://linux-hardware.org/?probe=429dc207a6) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [f887e6f037](https://linux-hardware.org/?probe=f887e6f037) | May 15, 2023 |
| UGREEN        | DX4600                      | [cbe70de89c](https://linux-hardware.org/?probe=cbe70de89c) | Apr 19, 2023 |
| ASUSTek       | PRIME B360M-C               | [8cf7b9cc76](https://linux-hardware.org/?probe=8cf7b9cc76) | Mar 23, 2023 |
| Intel         | D525MW AAE93082-401         | [590309a32b](https://linux-hardware.org/?probe=590309a32b) | Mar 18, 2023 |
| Intel         | D525MW AAE93082-401         | [bc847b4586](https://linux-hardware.org/?probe=bc847b4586) | Mar 09, 2023 |
| Intel         | D525MW AAE93082-401         | [d02959f9ad](https://linux-hardware.org/?probe=d02959f9ad) | Mar 02, 2023 |
| Unknown       | Unknown                     | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| ASRock        | X470 Master SLI/ac          | [d8f1121a19](https://linux-hardware.org/?probe=d8f1121a19) | Jan 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASRock        | X470 Master SLI/ac          | [6b6a4929de](https://linux-hardware.org/?probe=6b6a4929de) | Jan 16, 2023 |
| ASRock        | X470 Master SLI/ac          | [8775308115](https://linux-hardware.org/?probe=8775308115) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | [473b4d0e6e](https://linux-hardware.org/?probe=473b4d0e6e) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Gigabyte      | X570S AERO G                | [053b8697ce](https://linux-hardware.org/?probe=053b8697ce) | Jan 06, 2023 |
| Dell          | 0J1C3P A00                  | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
| Dell          | 03V7GF A01                  | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [bbf4464c41](https://linux-hardware.org/?probe=bbf4464c41) | Nov 27, 2022 |
| Fujitsu       | FujitsuTP7000 -1            | [89198d262f](https://linux-hardware.org/?probe=89198d262f) | Nov 17, 2022 |
| Lenovo        | 31900058 STD                | [d7cc344b2f](https://linux-hardware.org/?probe=d7cc344b2f) | Oct 31, 2022 |
| Lenovo        | 31900058 STD                | [9f7158b883](https://linux-hardware.org/?probe=9f7158b883) | Oct 16, 2022 |
| HP            | 1493                        | [60ebd1d8dd](https://linux-hardware.org/?probe=60ebd1d8dd) | Sep 29, 2022 |
| Gateway       | SX2185                      | [8372be8fe3](https://linux-hardware.org/?probe=8372be8fe3) | Sep 29, 2022 |
| ASRock        | H81M                        | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| Intel         | DH61BF AAG81311-101         | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| Intel         | DQ67SW AAG12527-310         | [9a4907d88c](https://linux-hardware.org/?probe=9a4907d88c) | Jul 17, 2022 |
| Unknown       | Unknown                     | [d857b93614](https://linux-hardware.org/?probe=d857b93614) | Jul 13, 2022 |
| Lenovo        | 31900058 STD                | [2f6356a177](https://linux-hardware.org/?probe=2f6356a177) | Jun 17, 2022 |
| Lenovo        | 31900058 STD                | [582fd88dbe](https://linux-hardware.org/?probe=582fd88dbe) | Jun 14, 2022 |
| MSI           | Z170A GAMING PRO            | [73b3e29101](https://linux-hardware.org/?probe=73b3e29101) | Jun 14, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [e692b2a091](https://linux-hardware.org/?probe=e692b2a091) | May 26, 2022 |
| ASUSTek       | H97-PLUS                    | [cab2025064](https://linux-hardware.org/?probe=cab2025064) | May 24, 2022 |
| MSI           | J1900I                      | [86f37a71f5](https://linux-hardware.org/?probe=86f37a71f5) | May 15, 2022 |
| MSI           | J1900I                      | [5a48d83596](https://linux-hardware.org/?probe=5a48d83596) | May 15, 2022 |
| ASUSTek       | Z97-K                       | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Dell          | 02YRK5 A02                  | [58c2ed388b](https://linux-hardware.org/?probe=58c2ed388b) | Dec 02, 2021 |
| HP            | 21B4 A01                    | [98accc83e4](https://linux-hardware.org/?probe=98accc83e4) | Nov 11, 2021 |
| Dell          | 0T10XW A00                  | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| Shuttle       | FS81                        | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Unknown       | Unknown                     | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| Dell          | 0VRWRC A00                  | [37a6ad6e02](https://linux-hardware.org/?probe=37a6ad6e02) | Apr 09, 2021 |
| ASUSTek       | P8H67-V                     | [89edd8b343](https://linux-hardware.org/?probe=89edd8b343) | Mar 17, 2021 |
| HP            | ProLiant MicroServer Gen... | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| VIA Techno... | KM266APro-835               | [1334ad3f74](https://linux-hardware.org/?probe=1334ad3f74) | Dec 22, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | 0PU052                      | [9a31999f07](https://linux-hardware.org/?probe=9a31999f07) | Aug 31, 2020 |
| ASUSTek       | TS10                        | [71d7f6e110](https://linux-hardware.org/?probe=71d7f6e110) | Aug 20, 2020 |
| VIA Techno... | KM266APro-835               | [25ec3d44ff](https://linux-hardware.org/?probe=25ec3d44ff) | Aug 16, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | [0c50242cc5](https://linux-hardware.org/?probe=0c50242cc5) | Aug 09, 2020 |
| Unknown       | Unknown                     | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
| ASRock        | J3455M                      | [05f9d5c3b4](https://linux-hardware.org/?probe=05f9d5c3b4) | Aug 06, 2020 |
| eMachines     | EL1352G                     | [4513d2931f](https://linux-hardware.org/?probe=4513d2931f) | Jul 03, 2020 |
| eMachines     | EL1352G                     | [4b26717c89](https://linux-hardware.org/?probe=4b26717c89) | Jul 03, 2020 |
| ASRock        | J3455M                      | [3719f96b60](https://linux-hardware.org/?probe=3719f96b60) | Jul 03, 2020 |
| Unknown       | i855GM/E-ITE8712            | [7b9cbd816b](https://linux-hardware.org/?probe=7b9cbd816b) | Dec 27, 2019 |
| ASRock        | D1800B-ITX                  | [f962d4bbf9](https://linux-hardware.org/?probe=f962d4bbf9) | Dec 22, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Alpine 3.12.0               | 6        | 13.64%  |
| Alpine 3.17_alpha20220809   | 4        | 9.09%   |
| Alpine 3.18.0               | 3        | 6.82%   |
| Alpine 3.16.0               | 3        | 6.82%   |
| Alpine 3.15.4               | 3        | 6.82%   |
| Alpine 3.13.0_alpha20200626 | 3        | 6.82%   |
| Alpine 3.17.2               | 2        | 4.55%   |
| Alpine 3.17.1               | 2        | 4.55%   |
| Alpine 3.16.1               | 2        | 4.55%   |
| Alpine 3.11.2               | 2        | 4.55%   |
| Alpine 3.8.4                | 1        | 2.27%   |
| Alpine 3.17.0               | 1        | 2.27%   |
| Alpine 3.16.3               | 1        | 2.27%   |
| Alpine 3.16.2               | 1        | 2.27%   |
| Alpine 3.16.0_alpha20220328 | 1        | 2.27%   |
| Alpine 3.15.6               | 1        | 2.27%   |
| Alpine 3.15.0               | 1        | 2.27%   |
| Alpine 3.14.2               | 1        | 2.27%   |
| Alpine 3.14.0               | 1        | 2.27%   |
| Alpine 3.13.6               | 1        | 2.27%   |
| Alpine 3.13.2               | 1        | 2.27%   |
| Alpine 3.13.1               | 1        | 2.27%   |
| Alpine 3.13.0_alpha20201218 | 1        | 2.27%   |
| Alpine 3.12.3               | 1        | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 41       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.43-1-lts      | 5        | 11.36%  |
| 5.15.60-0-lts     | 2        | 4.55%   |
| 6.3.3-0-edge      | 1        | 2.27%   |
| 6.1.30-0-lts      | 1        | 2.27%   |
| 6.1.28-2-lts      | 1        | 2.27%   |
| 6.0.10-0-edge     | 1        | 2.27%   |
| 5.8.0             | 1        | 2.27%   |
| 5.7.4             | 1        | 2.27%   |
| 5.4.84-0-lts      | 1        | 2.27%   |
| 5.4.6-0-lts       | 1        | 2.27%   |
| 5.4.58-0-lts      | 1        | 2.27%   |
| 5.4.57-0-lts      | 1        | 2.27%   |
| 5.4.0-77-generic  | 1        | 2.27%   |
| 5.18.0-0-asahi    | 1        | 2.27%   |
| 5.17.9-0-edge     | 1        | 2.27%   |
| 5.17.3-0-edge     | 1        | 2.27%   |
| 5.15.98-0-lts     | 1        | 2.27%   |
| 5.15.87-0-lts     | 1        | 2.27%   |
| 5.15.86-0-lts     | 1        | 2.27%   |
| 5.15.83-0-lts     | 1        | 2.27%   |
| 5.15.80           | 1        | 2.27%   |
| 5.15.74-0-lts     | 1        | 2.27%   |
| 5.15.70-0-lts     | 1        | 2.27%   |
| 5.15.64-1-pve     | 1        | 2.27%   |
| 5.15.57-0-lts     | 1        | 2.27%   |
| 5.15.46-1-lts     | 1        | 2.27%   |
| 5.15.40-0-lts     | 1        | 2.27%   |
| 5.15.38-0-lts     | 1        | 2.27%   |
| 5.15.32-0-lts     | 1        | 2.27%   |
| 5.15.17-0-lts     | 1        | 2.27%   |
| 5.14.0-1054-oem   | 1        | 2.27%   |
| 5.10.81           | 1        | 2.27%   |
| 5.10.61-0-lts     | 1        | 2.27%   |
| 5.10.16-0-lts     | 1        | 2.27%   |
| 5.10.12-0-lts     | 1        | 2.27%   |
| 5.10.1-0-lts      | 1        | 2.27%   |
| 4.4.180+          | 1        | 2.27%   |
| 4.14.89-0-vanilla | 1        | 2.27%   |
| 3.10.105          | 1        | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.43   | 5        | 11.36%  |
| 5.15.60  | 2        | 4.55%   |
| 6.3.3    | 1        | 2.27%   |
| 6.1.30   | 1        | 2.27%   |
| 6.1.28   | 1        | 2.27%   |
| 6.0.10   | 1        | 2.27%   |
| 5.8.0    | 1        | 2.27%   |
| 5.7.4    | 1        | 2.27%   |
| 5.4.84   | 1        | 2.27%   |
| 5.4.6    | 1        | 2.27%   |
| 5.4.58   | 1        | 2.27%   |
| 5.4.57   | 1        | 2.27%   |
| 5.4.0    | 1        | 2.27%   |
| 5.18.0   | 1        | 2.27%   |
| 5.17.9   | 1        | 2.27%   |
| 5.17.3   | 1        | 2.27%   |
| 5.15.98  | 1        | 2.27%   |
| 5.15.87  | 1        | 2.27%   |
| 5.15.86  | 1        | 2.27%   |
| 5.15.83  | 1        | 2.27%   |
| 5.15.80  | 1        | 2.27%   |
| 5.15.74  | 1        | 2.27%   |
| 5.15.70  | 1        | 2.27%   |
| 5.15.64  | 1        | 2.27%   |
| 5.15.57  | 1        | 2.27%   |
| 5.15.46  | 1        | 2.27%   |
| 5.15.40  | 1        | 2.27%   |
| 5.15.38  | 1        | 2.27%   |
| 5.15.32  | 1        | 2.27%   |
| 5.15.17  | 1        | 2.27%   |
| 5.14.0   | 1        | 2.27%   |
| 5.10.81  | 1        | 2.27%   |
| 5.10.61  | 1        | 2.27%   |
| 5.10.16  | 1        | 2.27%   |
| 5.10.12  | 1        | 2.27%   |
| 5.10.1   | 1        | 2.27%   |
| 4.4.180  | 1        | 2.27%   |
| 4.14.89  | 1        | 2.27%   |
| 3.10.105 | 1        | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 15       | 34.88%  |
| 5.4     | 10       | 23.26%  |
| 5.10    | 5        | 11.63%  |
| 6.1     | 2        | 4.65%   |
| 5.17    | 2        | 4.65%   |
| 6.3     | 1        | 2.33%   |
| 6.0     | 1        | 2.33%   |
| 5.8     | 1        | 2.33%   |
| 5.7     | 1        | 2.33%   |
| 5.18    | 1        | 2.33%   |
| 5.14    | 1        | 2.33%   |
| 4.4     | 1        | 2.33%   |
| 4.14    | 1        | 2.33%   |
| 3.10    | 1        | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 37       | 90.24%  |
| i686    | 3        | 7.32%   |
| aarch64 | 1        | 2.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 85.37%  |
| XFCE    | 2        | 4.88%   |
| sway    | 1        | 2.44%   |
| KDE5    | 1        | 2.44%   |
| i3      | 1        | 2.44%   |
| GNOME   | 1        | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 31       | 75.61%  |
| X11     | 8        | 19.51%  |
| Wayland | 2        | 4.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 92.68%  |
| LightDM | 2        | 4.88%   |
| SDDM    | 1        | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 25       | 59.52%  |
| Unknown | 15       | 35.71%  |
| pt_BR   | 1        | 2.38%   |
| en_US   | 1        | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 26       | 63.41%  |
| EFI  | 15       | 36.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 33       | 78.57%  |
| Overlay | 3        | 7.14%   |
| Btrfs   | 3        | 7.14%   |
| Zfs     | 1        | 2.38%   |
| Tmpfs   | 1        | 2.38%   |
| Unknown | 1        | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 59.52%  |
| GPT     | 12       | 28.57%  |
| MBR     | 5        | 11.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 80.49%  |
| Yes       | 8        | 19.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 92.68%  |
| Yes       | 3        | 7.32%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 6        | 14.63%  |
| ASUSTek Computer    | 6        | 14.63%  |
| Gigabyte Technology | 5        | 12.2%   |
| ASRock              | 4        | 9.76%   |
| Intel               | 3        | 7.32%   |
| Hewlett-Packard     | 3        | 7.32%   |
| Unknown             | 3        | 7.32%   |
| MSI                 | 2        | 4.88%   |
| Lenovo              | 2        | 4.88%   |
| Fujitsu             | 2        | 4.88%   |
| VIA Technologies    | 1        | 2.44%   |
| UGREEN              | 1        | 2.44%   |
| Shuttle             | 1        | 2.44%   |
| Gateway             | 1        | 2.44%   |
| eMachines           | 1        | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 3        | 7.32%   |
| Gigabyte Z490I AORUS ULTRA         | 2        | 4.88%   |
| ASUS All Series                    | 2        | 4.88%   |
| VIA KM266APro-835                  | 1        | 2.44%   |
| UGREEN DX4600                      | 1        | 2.44%   |
| Shuttle DS81D                      | 1        | 2.44%   |
| MSI MS-7C82                        | 1        | 2.44%   |
| MSI MS-7877                        | 1        | 2.44%   |
| Lenovo ThinkCentre M93p 10AB0016US | 1        | 2.44%   |
| Lenovo H535 10117                  | 1        | 2.44%   |
| Intel DQ67SW                       | 1        | 2.44%   |
| Intel DH61BF AAG81311-101          | 1        | 2.44%   |
| Intel D525MW AAE93082-401          | 1        | 2.44%   |
| HP ProLiant MicroServer Gen8       | 1        | 2.44%   |
| HP EliteDesk 800 G4 DM 35W         | 1        | 2.44%   |
| HP Compaq 4000 Pro SFF PC          | 1        | 2.44%   |
| Gigabyte Z170X-UD5                 | 1        | 2.44%   |
| Gigabyte X570S AERO G              | 1        | 2.44%   |
| Gigabyte B550 AORUS ELITE V2       | 1        | 2.44%   |
| Gateway SX2185                     | 1        | 2.44%   |
| Fujitsu PRIMERGY TX100 S2          | 1        | 2.44%   |
| Fujitsu FujitsuTP7000              | 1        | 2.44%   |
| eMachines EL1352G                  | 1        | 2.44%   |
| Dell Precision 3660                | 1        | 2.44%   |
| Dell OptiPlex 755                  | 1        | 2.44%   |
| Dell OptiPlex 5000                 | 1        | 2.44%   |
| Dell OptiPlex 3020M                | 1        | 2.44%   |
| Dell OptiPlex 3010                 | 1        | 2.44%   |
| Dell Inspiron 3647                 | 1        | 2.44%   |
| ASUS TS10                          | 1        | 2.44%   |
| ASUS PRIME H370M-PLUS              | 1        | 2.44%   |
| ASUS PRIME B360M-C                 | 1        | 2.44%   |
| ASUS P8H67-V                       | 1        | 2.44%   |
| ASRock X470 Master SLI/ac          | 1        | 2.44%   |
| ASRock J3455M                      | 1        | 2.44%   |
| ASRock H81M                        | 1        | 2.44%   |
| ASRock D1800B-ITX                  | 1        | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 4        | 9.76%   |
| Unknown               | 3        | 7.32%   |
| Gigabyte Z490I        | 2        | 4.88%   |
| ASUS PRIME            | 2        | 4.88%   |
| ASUS All              | 2        | 4.88%   |
| VIA KM266APro-835     | 1        | 2.44%   |
| UGREEN DX4600         | 1        | 2.44%   |
| Shuttle DS81D         | 1        | 2.44%   |
| MSI MS-7C82           | 1        | 2.44%   |
| MSI MS-7877           | 1        | 2.44%   |
| Lenovo ThinkCentre    | 1        | 2.44%   |
| Lenovo H535           | 1        | 2.44%   |
| Intel DQ67SW          | 1        | 2.44%   |
| Intel DH61BF          | 1        | 2.44%   |
| Intel D525MW          | 1        | 2.44%   |
| HP ProLiant           | 1        | 2.44%   |
| HP EliteDesk          | 1        | 2.44%   |
| HP Compaq             | 1        | 2.44%   |
| Gigabyte Z170X-UD5    | 1        | 2.44%   |
| Gigabyte X570S        | 1        | 2.44%   |
| Gigabyte B550         | 1        | 2.44%   |
| Gateway SX2185        | 1        | 2.44%   |
| Fujitsu PRIMERGY      | 1        | 2.44%   |
| Fujitsu FujitsuTP7000 | 1        | 2.44%   |
| eMachines EL1352G     | 1        | 2.44%   |
| Dell Precision        | 1        | 2.44%   |
| Dell Inspiron         | 1        | 2.44%   |
| ASUS TS10             | 1        | 2.44%   |
| ASUS P8H67-V          | 1        | 2.44%   |
| ASRock X470           | 1        | 2.44%   |
| ASRock J3455M         | 1        | 2.44%   |
| ASRock H81M           | 1        | 2.44%   |
| ASRock D1800B-ITX     | 1        | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 8        | 19.51%  |
| 2020    | 5        | 12.2%   |
| 2018    | 5        | 12.2%   |
| 2012    | 5        | 12.2%   |
| 2013    | 4        | 9.76%   |
| 2010    | 3        | 7.32%   |
| 2022    | 2        | 4.88%   |
| 2011    | 2        | 4.88%   |
| 2017    | 1        | 2.44%   |
| 2016    | 1        | 2.44%   |
| 2015    | 1        | 2.44%   |
| 2009    | 1        | 2.44%   |
| 2007    | 1        | 2.44%   |
| 2004    | 1        | 2.44%   |
| Unknown | 1        | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 41       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 41       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 8        | 18.18%  |
| 16.01-24.0      | 8        | 18.18%  |
| 4.01-8.0        | 6        | 13.64%  |
| 32.01-64.0      | 6        | 13.64%  |
| 8.01-16.0       | 6        | 13.64%  |
| 2.01-3.0        | 2        | 4.55%   |
| 1.01-2.0        | 2        | 4.55%   |
| 0.51-1.0        | 2        | 4.55%   |
| 0.01-0.5        | 2        | 4.55%   |
| More than 256.0 | 1        | 2.27%   |
| 64.01-256.0     | 1        | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 11       | 26.19%  |
| 1.01-2.0  | 9        | 21.43%  |
| 0.51-1.0  | 7        | 16.67%  |
| 3.01-4.0  | 5        | 11.9%   |
| 2.01-3.0  | 4        | 9.52%   |
| 4.01-8.0  | 2        | 4.76%   |
| 8.01-16.0 | 2        | 4.76%   |
| 0         | 1        | 2.38%   |
| Unknown   | 1        | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 45.24%  |
| 2      | 9        | 21.43%  |
| 3      | 8        | 19.05%  |
| 4      | 4        | 9.52%   |
| 12     | 1        | 2.38%   |
| 5      | 1        | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 85.37%  |
| Yes       | 6        | 14.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 97.56%  |
| No        | 1        | 2.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 73.17%  |
| Yes       | 11       | 26.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 78.05%  |
| Yes       | 9        | 21.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 10       | 23.81%  |
| Russia      | 4        | 9.52%   |
| Germany     | 4        | 9.52%   |
| UK          | 2        | 4.76%   |
| Sweden      | 2        | 4.76%   |
| Norway      | 2        | 4.76%   |
| Brazil      | 2        | 4.76%   |
| Ukraine     | 1        | 2.38%   |
| Switzerland | 1        | 2.38%   |
| Spain       | 1        | 2.38%   |
| South Korea | 1        | 2.38%   |
| Portugal    | 1        | 2.38%   |
| Poland      | 1        | 2.38%   |
| Pakistan    | 1        | 2.38%   |
| Indonesia   | 1        | 2.38%   |
| Guatemala   | 1        | 2.38%   |
| Greece      | 1        | 2.38%   |
| Finland     | 1        | 2.38%   |
| China       | 1        | 2.38%   |
| Canada      | 1        | 2.38%   |
| Austria     | 1        | 2.38%   |
| Australia   | 1        | 2.38%   |
| Argentina   | 1        | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Springfield          | 4        | 9.52%   |
| St Petersburg        | 3        | 7.14%   |
| Manitowoc            | 3        | 7.14%   |
| Frankfurt am Main    | 2        | 4.76%   |
| As                   | 2        | 4.76%   |
| Zurich               | 1        | 2.38%   |
| Tuusula              | 1        | 2.38%   |
| Stockholm            | 1        | 2.38%   |
| Salzburg             | 1        | 2.38%   |
| Redwood City         | 1        | 2.38%   |
| Penza                | 1        | 2.38%   |
| Oberhausen           | 1        | 2.38%   |
| Lisbon               | 1        | 2.38%   |
| Lahore               | 1        | 2.38%   |
| Kharkiv              | 1        | 2.38%   |
| Jember               | 1        | 2.38%   |
| Heraklion            | 1        | 2.38%   |
| Hangzhou             | 1        | 2.38%   |
| Hamburg              | 1        | 2.38%   |
| Gwacheon             | 1        | 2.38%   |
| Guatemala City       | 1        | 2.38%   |
| Gothenburg           | 1        | 2.38%   |
| Glasgow              | 1        | 2.38%   |
| General San Martin   | 1        | 2.38%   |
| Durham               | 1        | 2.38%   |
| Czarna Białostocka  | 1        | 2.38%   |
| Chicago              | 1        | 2.38%   |
| Bradford             | 1        | 2.38%   |
| Betim                | 1        | 2.38%   |
| Barrow in Furness    | 1        | 2.38%   |
| Barcelona            | 1        | 2.38%   |
| Balneário Camboriú | 1        | 2.38%   |
| Adelaide             | 1        | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 20     | 19.12%  |
| WDC                 | 10       | 15     | 14.71%  |
| Seagate             | 10       | 22     | 14.71%  |
| Toshiba             | 4        | 4      | 5.88%   |
| HGST                | 4        | 4      | 5.88%   |
| A-DATA Technology   | 4        | 5      | 5.88%   |
| Sandisk             | 3        | 5      | 4.41%   |
| Hitachi             | 3        | 3      | 4.41%   |
| Crucial             | 3        | 6      | 4.41%   |
| SK hynix            | 2        | 2      | 2.94%   |
| Kingston            | 2        | 2      | 2.94%   |
| Intel               | 2        | 3      | 2.94%   |
| Unknown             | 1        | 1      | 1.47%   |
| Transcend           | 1        | 1      | 1.47%   |
| Phison Electronics  | 1        | 1      | 1.47%   |
| LITEON              | 1        | 1      | 1.47%   |
| Lexar               | 1        | 1      | 1.47%   |
| KIOXIA              | 1        | 1      | 1.47%   |
| Kingmax             | 1        | 1      | 1.47%   |
| Apple               | 1        | 3      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 960 EVO 500GB                           | 2        | 2.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2        | 2.47%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1        | 1.23%   |
| WDC WDS250G2B0B 250GB SSD                           | 1        | 1.23%   |
| WDC WDS250G2B0A 250GB SSD                           | 1        | 1.23%   |
| WDC WD800AAJS-00 80GB                               | 1        | 1.23%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1        | 1.23%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1        | 1.23%   |
| WDC WD3200AAKX-0 320GB                              | 1        | 1.23%   |
| WDC WD20EZRZ-00Z 2TB                                | 1        | 1.23%   |
| WDC WD1600BEVT-2 160GB                              | 1        | 1.23%   |
| WDC WD140EDGZ-11B2DA2 14TB                          | 1        | 1.23%   |
| WDC WD120EFBX-68B0EN0 12TB                          | 1        | 1.23%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1        | 1.23%   |
| WDC WD10EZEX-21M2NA0 1TB                            | 1        | 1.23%   |
| Unknown MMC Card  32GB                              | 1        | 1.23%   |
| Transcend SSD 1GB                                   | 1        | 1.23%   |
| Toshiba MQ04ABF100 1TB                              | 1        | 1.23%   |
| Toshiba MQ01ABF050 500GB                            | 1        | 1.23%   |
| Toshiba MK3252GS 320GB                              | 1        | 1.23%   |
| Toshiba HDWD130 3TB                                 | 1        | 1.23%   |
| SK hynix SC300 M.2 2280 256 256GB SSD               | 1        | 1.23%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1        | 1.23%   |
| Seagate ST980310AS 80GB                             | 1        | 1.23%   |
| Seagate ST5000LM000-2AN170 5TB                      | 1        | 1.23%   |
| Seagate ST4000VN008-2DR1 4TB                        | 1        | 1.23%   |
| Seagate ST4000NC000-1FR1 4TB                        | 1        | 1.23%   |
| Seagate ST380815AS 80GB                             | 1        | 1.23%   |
| Seagate ST3500418AS 500GB                           | 1        | 1.23%   |
| Seagate ST3000DM001-1ER166 3TB                      | 1        | 1.23%   |
| Seagate ST2000DL001-9VT1 2TB                        | 1        | 1.23%   |
| Seagate ST18000NM000J-2TV103 18TB                   | 1        | 1.23%   |
| Seagate ST14000VN0008-2KU103 14TB                   | 1        | 1.23%   |
| Seagate ST1000LM048-2E71 1TB                        | 1        | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 1.23%   |
| Seagate ST1000DM003-1ER162 1TB                      | 1        | 1.23%   |
| Sandisk WDC WDS500G2B0C-00PXH0 500GB                | 1        | 1.23%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 1        | 1.23%   |
| SanDisk SSD PLUS 240GB                              | 1        | 1.23%   |
| SanDisk SSD PLUS 1TB                                | 1        | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 22     | 32.26%  |
| WDC                 | 8        | 12     | 25.81%  |
| Toshiba             | 4        | 4      | 12.9%   |
| HGST                | 4        | 4      | 12.9%   |
| Hitachi             | 3        | 3      | 9.68%   |
| Samsung Electronics | 2        | 3      | 6.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 7      | 20.83%  |
| Crucial             | 3        | 6      | 12.5%   |
| A-DATA Technology   | 3        | 3      | 12.5%   |
| WDC                 | 2        | 3      | 8.33%   |
| SanDisk             | 2        | 3      | 8.33%   |
| Kingston            | 2        | 2      | 8.33%   |
| Intel               | 2        | 3      | 8.33%   |
| Transcend           | 1        | 1      | 4.17%   |
| SK hynix            | 1        | 1      | 4.17%   |
| LITEON              | 1        | 1      | 4.17%   |
| Lexar               | 1        | 1      | 4.17%   |
| Kingmax             | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 48     | 40%     |
| SSD  | 21       | 32     | 35%     |
| NVMe | 14       | 20     | 23.33%  |
| MMC  | 1        | 1      | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 34       | 78     | 68%     |
| NVMe | 14       | 20     | 28%     |
| SAS  | 1        | 2      | 2%      |
| MMC  | 1        | 1      | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 29       | 44     | 61.7%   |
| 0.51-1.0   | 8        | 13     | 17.02%  |
| 3.01-4.0   | 3        | 7      | 6.38%   |
| 2.01-3.0   | 2        | 2      | 4.26%   |
| 10.01-20.0 | 2        | 9      | 4.26%   |
| 4.01-10.0  | 2        | 2      | 4.26%   |
| 1.01-2.0   | 1        | 3      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 12       | 28.57%  |
| 101-250        | 8        | 19.05%  |
| More than 3000 | 4        | 9.52%   |
| 21-50          | 4        | 9.52%   |
| 2001-3000      | 4        | 9.52%   |
| 1-20           | 4        | 9.52%   |
| 251-500        | 2        | 4.76%   |
| 1001-2000      | 2        | 4.76%   |
| 501-1000       | 1        | 2.38%   |
| 51-100         | 1        | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 16       | 38.1%   |
| Unknown        | 12       | 28.57%  |
| 251-500        | 5        | 11.9%   |
| 21-50          | 4        | 9.52%   |
| 1001-2000      | 2        | 4.76%   |
| More than 3000 | 1        | 2.38%   |
| 2001-3000      | 1        | 2.38%   |
| 51-100         | 1        | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD3200AAKX-0 320GB           | 1        | 1      | 16.67%  |
| Toshiba MK3252GS 320GB           | 1        | 1      | 16.67%  |
| SanDisk SDSA6MM 16GB SSD         | 1        | 1      | 16.67%  |
| Samsung Electronics SP0411N 40GB | 1        | 2      | 16.67%  |
| Kingmax SSD 120G                 | 1        | 1      | 16.67%  |
| Hitachi HTS722080K9A300 80GB     | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 16.67%  |
| Toshiba             | 1        | 1      | 16.67%  |
| SanDisk             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 2      | 16.67%  |
| Kingmax             | 1        | 1      | 16.67%  |
| Hitachi             | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 25%     |
| Toshiba             | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 2      | 25%     |
| Hitachi             | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 5      | 66.67%  |
| SSD  | 2        | 2      | 33.33%  |

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
| Works    | 31       | 70     | 67.39%  |
| Detected | 9        | 24     | 19.57%  |
| Malfunc  | 6        | 7      | 13.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 32       | 50.79%  |
| Samsung Electronics       | 8        | 12.7%   |
| AMD                       | 6        | 9.52%   |
| Marvell Technology Group  | 2        | 3.17%   |
| LSI Logic / Symbios Logic | 2        | 3.17%   |
| ASMedia Technology        | 2        | 3.17%   |
| Adaptec                   | 2        | 3.17%   |
| VIA Technologies          | 1        | 1.59%   |
| SK hynix                  | 1        | 1.59%   |
| SanDisk                   | 1        | 1.59%   |
| Promise Technology        | 1        | 1.59%   |
| Phison Electronics        | 1        | 1.59%   |
| Nvidia                    | 1        | 1.59%   |
| KIOXIA                    | 1        | 1.59%   |
| Broadcom / LSI            | 1        | 1.59%   |
| ADATA Technology          | 1        | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 6.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 5.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4        | 5.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 4.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 2.7%    |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 2        | 2.7%    |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2        | 2.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 2.7%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 2.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 2.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 2.7%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2        | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 2.7%    |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2        | 2.7%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 1.35%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 1.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.35%   |
| SanDisk Non-Volatile memory controller                                         | 1        | 1.35%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 1.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.35%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.35%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                      | 1        | 1.35%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 1.35%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.35%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.35%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 1.35%   |
| KIOXIA Non-Volatile memory controller                                          | 1        | 1.35%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.35%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 1.35%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1        | 1.35%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1        | 1.35%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 1.35%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.35%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 1.35%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1        | 1.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 32       | 51.61%  |
| NVMe | 12       | 19.35%  |
| RAID | 9        | 14.52%  |
| IDE  | 7        | 11.29%  |
| SAS  | 2        | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 33       | 78.57%  |
| AMD     | 8        | 19.05%  |
| Unknown | 1        | 2.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz       | 2        | 4.76%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2        | 4.76%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 4.76%   |
| Intel Core i3-4150 CPU @ 3.50GHz        | 2        | 4.76%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz      | 1        | 2.38%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1        | 2.38%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz  | 1        | 2.38%   |
| Intel Core i7-8700T CPU @ 2.40GHz       | 1        | 2.38%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1        | 2.38%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 1        | 2.38%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1        | 2.38%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 1        | 2.38%   |
| Intel Core i5-4570T CPU @ 2.90GHz       | 1        | 2.38%   |
| Intel Core i5-3450 CPU @ 3.10GHz        | 1        | 2.38%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1        | 2.38%   |
| Intel Core i3-3240 CPU @ 3.40GHz        | 1        | 2.38%   |
| Intel Core i3-3220T CPU @ 2.80GHz       | 1        | 2.38%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 1        | 2.38%   |
| Intel Celeron N5105 @ 2.00GHz           | 1        | 2.38%   |
| Intel Celeron M processor 1.00GHz       | 1        | 2.38%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 1        | 2.38%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 1        | 2.38%   |
| Intel Celeron CPU J1800 @ 2.41GHz       | 1        | 2.38%   |
| Intel Celeron CPU G1850 @ 2.90GHz       | 1        | 2.38%   |
| Intel Celeron CPU E3400 @ 2.60GHz       | 1        | 2.38%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 1        | 2.38%   |
| Intel Atom CPU D525 @ 1.80GHz           | 1        | 2.38%   |
| Intel 12th Gen Core i9-12900K           | 1        | 2.38%   |
| Intel 12th Gen Core i7-12700T           | 1        | 2.38%   |
| AMD Sempron 145 Processor               | 1        | 2.38%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 1        | 2.38%   |
| AMD Ryzen 7 5700X 8-Core Processor      | 1        | 2.38%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 1        | 2.38%   |
| AMD Mobile Duron processor              | 1        | 2.38%   |
| AMD FX-8350 Eight-Core Processor        | 1        | 2.38%   |
| AMD E1-2500 APU with Radeon HD Graphics | 1        | 2.38%   |
| AMD A8-5500 APU with Radeon HD Graphics | 1        | 2.38%   |
|                                         | 1        | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 8        | 19.05%  |
| Intel Celeron      | 6        | 14.29%  |
| Intel Core i3      | 5        | 11.9%   |
| Other              | 4        | 9.52%   |
| Intel Core i7      | 4        | 9.52%   |
| Intel Core i9      | 2        | 4.76%   |
| Intel Atom         | 2        | 4.76%   |
| AMD Ryzen 7        | 2        | 4.76%   |
| Intel Xeon Gold    | 1        | 2.38%   |
| Intel Xeon         | 1        | 2.38%   |
| Intel Pentium Dual | 1        | 2.38%   |
| Intel Celeron M    | 1        | 2.38%   |
| AMD Sempron        | 1        | 2.38%   |
| AMD Ryzen 9        | 1        | 2.38%   |
| AMD FX             | 1        | 2.38%   |
| AMD E1             | 1        | 2.38%   |
| AMD A8             | 1        | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 15       | 35.71%  |
| 2      | 12       | 28.57%  |
| 1      | 4        | 9.52%   |
| 6      | 3        | 7.14%   |
| 12     | 2        | 4.76%   |
| 10     | 2        | 4.76%   |
| 8      | 2        | 4.76%   |
| 32     | 1        | 2.38%   |
| 16     | 1        | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 40       | 95.24%  |
| 2      | 1        | 2.38%   |
| 0      | 1        | 2.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 53.66%  |
| 2      | 19       | 46.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 21       | 51.22%  |
| 32-bit, 64-bit | 17       | 41.46%  |
| 32-bit         | 2        | 4.88%   |
| 64-bit         | 1        | 2.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 57.14%  |
| 0x306c3    | 4        | 9.52%   |
| 0x906ea    | 2        | 4.76%   |
| 0x306a9    | 2        | 4.76%   |
| 0xa0655    | 1        | 2.38%   |
| 0x90672    | 1        | 2.38%   |
| 0x6fd      | 1        | 2.38%   |
| 0x6d8      | 1        | 2.38%   |
| 0x506c9    | 1        | 2.38%   |
| 0x406c4    | 1        | 2.38%   |
| 0x106e5    | 1        | 2.38%   |
| 0x08701021 | 1        | 2.38%   |
| 0x0800820d | 1        | 2.38%   |
| 0x010000b6 | 1        | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 7        | 16.67%  |
| Silvermont       | 3        | 7.14%   |
| SandyBridge      | 3        | 7.14%   |
| KabyLake         | 3        | 7.14%   |
| IvyBridge        | 3        | 7.14%   |
| CometLake        | 3        | 7.14%   |
| Unknown          | 3        | 7.14%   |
| Skylake          | 2        | 4.76%   |
| Piledriver       | 2        | 4.76%   |
| Zen+             | 1        | 2.38%   |
| Zen 3            | 1        | 2.38%   |
| Zen 2            | 1        | 2.38%   |
| Penryn           | 1        | 2.38%   |
| P6               | 1        | 2.38%   |
| Nehalem          | 1        | 2.38%   |
| K6               | 1        | 2.38%   |
| K10              | 1        | 2.38%   |
| Jaguar           | 1        | 2.38%   |
| Goldmont         | 1        | 2.38%   |
| Core             | 1        | 2.38%   |
| Bonnell          | 1        | 2.38%   |
| Alderlake Hybrid | 1        | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 28       | 63.64%  |
| AMD                        | 8        | 18.18%  |
| Nvidia                     | 5        | 11.36%  |
| Matrox Electronics Systems | 2        | 4.55%   |
| VIA Technologies           | 1        | 2.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 9.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 6.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 6.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 6.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 4.55%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 4.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 4.55%   |
| Intel AlderLake-S GT1                                                                    | 2        | 4.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 4.55%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 4.55%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 2.27%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 2.27%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1        | 2.27%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 2.27%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1        | 2.27%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 2.27%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 2.27%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1        | 2.27%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 2.27%   |
| Intel HD Graphics 500                                                                    | 1        | 2.27%   |
| Intel DG2 [Arc A750]                                                                     | 1        | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.27%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 2.27%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 2.27%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 2.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 2.27%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 1        | 2.27%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 1        | 2.27%   |
| AMD ES1000                                                                               | 1        | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 26       | 61.9%   |
| 1 x AMD         | 8        | 19.05%  |
| 1 x Nvidia      | 3        | 7.14%   |
| Other           | 1        | 2.38%   |
| 2 x Intel       | 1        | 2.38%   |
| 1 x VIA         | 1        | 2.38%   |
| Nvidia + Matrox | 1        | 2.38%   |
| 1 x Matrox      | 1        | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 33       | 78.57%  |
| Unknown     | 8        | 19.05%  |
| Proprietary | 1        | 2.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 80.49%  |
| 7.01-8.0   | 3        | 7.32%   |
| 0.01-0.5   | 2        | 4.88%   |
| 3.01-4.0   | 1        | 2.44%   |
| 1.01-2.0   | 1        | 2.44%   |
| 8.01-16.0  | 1        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 26.67%  |
| Samsung Electronics | 4        | 13.33%  |
| AOC                 | 4        | 13.33%  |
| Goldstar            | 3        | 10%     |
| BenQ                | 3        | 10%     |
| Acer                | 2        | 6.67%   |
| ViewSonic           | 1        | 3.33%   |
| Philips             | 1        | 3.33%   |
| Mi                  | 1        | 3.33%   |
| KVM                 | 1        | 3.33%   |
| Elo Touch           | 1        | 3.33%   |
| CTC                 | 1        | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                     | 3        | 10%     |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch     | 2        | 6.67%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch             | 1        | 3.33%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 3.33%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch | 1        | 3.33%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch              | 1        | 3.33%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                     | 1        | 3.33%   |
| KVM LCD Monitor17 KVM4308 1280x1024 338x270mm 17.0-inch              | 1        | 3.33%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch             | 1        | 3.33%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 1        | 3.33%   |
| Goldstar LG HDR 4K GSM774F 3840x2160 700x400mm 31.7-inch             | 1        | 3.33%   |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch              | 1        | 3.33%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                    | 1        | 3.33%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                   | 1        | 3.33%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                    | 1        | 3.33%   |
| Dell E1911 DELF037 1440x900 408x255mm 18.9-inch                      | 1        | 3.33%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                    | 1        | 3.33%   |
| CTC KD02909-8770A CTC0770 1024x768 304x228mm 15.0-inch               | 1        | 3.33%   |
| BenQ XL2411Z BNQ7F31 1920x1080 530x300mm 24.0-inch                   | 1        | 3.33%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                    | 1        | 3.33%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 3.33%   |
| AOC 912Vwa AOC1912 1440x900 408x255mm 18.9-inch                      | 1        | 3.33%   |
| AOC 718Swag-1 AOCC750 1440x900 367x230mm 17.1-inch                   | 1        | 3.33%   |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                     | 1        | 3.33%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                     | 1        | 3.33%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                    | 1        | 3.33%   |
| Acer S236HL ACR0387 1920x1080 510x286mm 23.0-inch                    | 1        | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 9        | 31.03%  |
| 2560x1440 (QHD)    | 4        | 13.79%  |
| 1680x1050 (WSXGA+) | 4        | 13.79%  |
| 1280x1024 (SXGA)   | 4        | 13.79%  |
| 3840x2160 (4K)     | 2        | 6.9%    |
| 3440x1440          | 2        | 6.9%    |
| 1440x900 (WXGA+)   | 2        | 6.9%    |
| 1366x768 (WXGA)    | 1        | 3.45%   |
| 1024x768 (XGA)     | 1        | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 5        | 17.24%  |
| 20     | 4        | 13.79%  |
| 23     | 3        | 10.34%  |
| 21     | 3        | 10.34%  |
| 19     | 3        | 10.34%  |
| 17     | 3        | 10.34%  |
| 34     | 2        | 6.9%    |
| 24     | 2        | 6.9%    |
| 31     | 1        | 3.45%   |
| 25     | 1        | 3.45%   |
| 18     | 1        | 3.45%   |
| 15     | 1        | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 34.48%  |
| 401-500     | 9        | 31.03%  |
| 351-400     | 3        | 10.34%  |
| 301-350     | 3        | 10.34%  |
| 701-800     | 2        | 6.9%    |
| 601-700     | 2        | 6.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 13       | 50%     |
| 16/10 | 6        | 23.08%  |
| 5/4   | 4        | 15.38%  |
| 21/9  | 2        | 7.69%   |
| 4/3   | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 9        | 31.03%  |
| 201-250        | 7        | 24.14%  |
| 301-350        | 5        | 17.24%  |
| 351-500        | 3        | 10.34%  |
| 141-150        | 2        | 6.9%    |
| 251-300        | 1        | 3.45%   |
| 131-140        | 1        | 3.45%   |
| 101-110        | 1        | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 57.69%  |
| 101-120 | 7        | 26.92%  |
| 1-50    | 2        | 7.69%   |
| 161-240 | 1        | 3.85%   |
| 121-160 | 1        | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 23       | 54.76%  |
| 0     | 15       | 35.71%  |
| 2     | 3        | 7.14%   |
| 4     | 1        | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 20       | 35.71%  |
| Intel                           | 18       | 32.14%  |
| Broadcom                        | 5        | 8.93%   |
| Qualcomm Atheros                | 4        | 7.14%   |
| Xiaomi                          | 2        | 3.57%   |
| VIA Technologies                | 1        | 1.79%   |
| T & A Mobile Phones             | 1        | 1.79%   |
| Qualcomm Atheros Communications | 1        | 1.79%   |
| Qualcomm                        | 1        | 1.79%   |
| Nvidia                          | 1        | 1.79%   |
| MediaTek                        | 1        | 1.79%   |
| D-Link System                   | 1        | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 15       | 23.08%  |
| Intel Ethernet Controller I225-V                                        | 5        | 7.69%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2        | 3.08%   |
| Intel I211 Gigabit Network Connection                                   | 2        | 3.08%   |
| Intel Ethernet Connection (7) I219-V                                    | 2        | 3.08%   |
| Intel Ethernet Connection (17) I219-LM                                  | 2        | 3.08%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2        | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2        | 3.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 1.54%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1        | 1.54%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1        | 1.54%   |
| T & A Mobile Phones 5007Z                                               | 1        | 1.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1        | 1.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1        | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1        | 1.54%   |
| Qualcomm Fairphone 4 5G                                                 | 1        | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 1.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1        | 1.54%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 1.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.54%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 1.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 1.54%   |
| Intel I210 Gigabit Network Connection                                   | 1        | 1.54%   |
| Intel Ethernet Connection I217-LM                                       | 1        | 1.54%   |
| Intel Ethernet Connection (7) I219-LM                                   | 1        | 1.54%   |
| Intel Ethernet Connection (2) I219-V                                    | 1        | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 1.54%   |
| Intel Centrino Wireless-N 105                                           | 1        | 1.54%   |
| Intel 82578DM Gigabit Network Connection                                | 1        | 1.54%   |
| Intel 82567V-4 Gigabit Network Connection                               | 1        | 1.54%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 1        | 1.54%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                         | 1        | 1.54%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                        | 1        | 1.54%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                        | 1        | 1.54%   |
| Broadcom BRCM4378 Wireless Network Adapter                              | 1        | 1.54%   |
| Broadcom BRCM4378 Bluetooth Controller                                  | 1        | 1.54%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller   | 1        | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 30.77%  |
| Realtek Semiconductor           | 3        | 23.08%  |
| Qualcomm Atheros                | 2        | 15.38%  |
| Broadcom                        | 2        | 15.38%  |
| Qualcomm Atheros Communications | 1        | 7.69%   |
| MediaTek                        | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Comet Lake PCH CNVi WiFi                                          | 2        | 15.38%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 7.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1        | 7.69%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 7.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 7.69%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 7.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 7.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 7.69%   |
| Intel Centrino Wireless-N 105                                           | 1        | 7.69%   |
| Broadcom BRCM4378 Wireless Network Adapter                              | 1        | 7.69%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 39.58%  |
| Intel                 | 18       | 37.5%   |
| Broadcom              | 3        | 6.25%   |
| Xiaomi                | 2        | 4.17%   |
| Qualcomm Atheros      | 2        | 4.17%   |
| VIA Technologies      | 1        | 2.08%   |
| Qualcomm              | 1        | 2.08%   |
| Nvidia                | 1        | 2.08%   |
| D-Link System         | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 15       | 30%     |
| Intel Ethernet Controller I225-V                                      | 5        | 10%     |
| Realtek RTL8125 2.5GbE Controller                                     | 2        | 4%      |
| Intel I211 Gigabit Network Connection                                 | 2        | 4%      |
| Intel Ethernet Connection (7) I219-V                                  | 2        | 4%      |
| Intel Ethernet Connection (17) I219-LM                                | 2        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2        | 4%      |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1        | 2%      |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                  | 1        | 2%      |
| VIA VT6102/VT6103 [Rhine-II]                                          | 1        | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 1        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1        | 2%      |
| Qualcomm Fairphone 4 5G                                               | 1        | 2%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 1        | 2%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1        | 2%      |
| Nvidia MCP61 Ethernet                                                 | 1        | 2%      |
| Intel I210 Gigabit Network Connection                                 | 1        | 2%      |
| Intel Ethernet Connection I217-LM                                     | 1        | 2%      |
| Intel Ethernet Connection (7) I219-LM                                 | 1        | 2%      |
| Intel Ethernet Connection (2) I219-V                                  | 1        | 2%      |
| Intel 82578DM Gigabit Network Connection                              | 1        | 2%      |
| Intel 82567V-4 Gigabit Network Connection                             | 1        | 2%      |
| Intel 82566DM-2 Gigabit Network Connection                            | 1        | 2%      |
| D-Link System DGE-528T Gigabit Ethernet Adapter                       | 1        | 2%      |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1        | 2%      |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1        | 2%      |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1        | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 40       | 75.47%  |
| WiFi     | 11       | 20.75%  |
| Unknown  | 2        | 3.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 35       | 89.74%  |
| WiFi     | 4        | 10.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 55.81%  |
| 2     | 15       | 34.88%  |
| 3     | 2        | 4.65%   |
| 5     | 1        | 2.33%   |
| 4     | 1        | 2.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 34       | 82.93%  |
| Yes  | 7        | 17.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 4        | 40%     |
| Intel                   | 3        | 30%     |
| MediaTek                | 1        | 10%     |
| IMC Networks            | 1        | 10%     |
| Actions                 | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 40%     |
| Intel AX201 Bluetooth                               | 2        | 20%     |
| MediaTek Wireless_Device                            | 1        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 10%     |
| IMC Networks Bluetooth Device                       | 1        | 10%     |
| Actions general adapter                             | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 26       | 55.32%  |
| AMD                                  | 10       | 21.28%  |
| Nvidia                               | 4        | 8.51%   |
| VIA Technologies                     | 1        | 2.13%   |
| Thesycon Systemsoftware & Consulting | 1        | 2.13%   |
| Texas Instruments                    | 1        | 2.13%   |
| RODE Microphones                     | 1        | 2.13%   |
| Native Instruments                   | 1        | 2.13%   |
| Generalplus Technology               | 1        | 2.13%   |
| C-Media Electronics                  | 1        | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 9.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 7.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 7.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 5.45%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 3.64%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 3.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 3.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 3.64%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 3.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 3.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 3.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 3.64%   |
| AMD FCH Azalia Controller                                                  | 2        | 3.64%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 1.82%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                              | 1        | 1.82%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.82%   |
| RODE Microphones RODE NT-USB Mini                                          | 1        | 1.82%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.82%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.82%   |
| Native Instruments Komplete Audio 2                                        | 1        | 1.82%   |
| Intel USB PnP Sound Device                                                 | 1        | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.82%   |
| Intel DG2 Audio Controller                                                 | 1        | 1.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 1.82%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.82%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.82%   |
| Generalplus Technology USB Audio Device                                    | 1        | 1.82%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.82%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 1.82%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 1.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 7        | 15.22%  |
| Unknown             | 6        | 13.04%  |
| SK hynix            | 6        | 13.04%  |
| Kingston            | 6        | 13.04%  |
| Samsung Electronics | 5        | 10.87%  |
| Elpida              | 4        | 8.7%    |
| Micron Technology   | 3        | 6.52%   |
| Corsair             | 2        | 4.35%   |
| Team                | 1        | 2.17%   |
| Qimonda             | 1        | 2.17%   |
| Patriot             | 1        | 2.17%   |
| Hewlett-Packard     | 1        | 2.17%   |
| Cors                | 1        | 2.17%   |
| A-DATA Technology   | 1        | 2.17%   |
| Unknown             | 1        | 2.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s      | 2        | 4%      |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s | 2        | 4%      |
| Unknown RAM Module 512MB DIMM                            | 1        | 2%      |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 2%      |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 1        | 2%      |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s             | 1        | 2%      |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 2%      |
| Unknown RAM Module 128MB DIMM                            | 1        | 2%      |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 2%      |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s      | 1        | 2%      |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 2%      |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 2%      |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 2%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s              | 1        | 2%      |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 2%      |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM 2200MT/s           | 1        | 2%      |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Samsung RAM M378B5173EB0-YK0 4096MB DIMM DDR3 1600MT/s   | 1        | 2%      |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s         | 1        | 2%      |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 2%      |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s      | 1        | 2%      |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Micron RAM 16ATF4G64HZ-3G2F1 32GB SODIMM DDR4 3200MT/s   | 1        | 2%      |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s      | 1        | 2%      |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 1        | 2%      |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 2%      |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 2%      |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 2%      |
| Kingston RAM 9905744-064.A00G 32GB SODIMM DDR4 3200MT/s  | 1        | 2%      |
| Kingston RAM 9905595-005.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 2%      |
| Kingston RAM 9905474-019.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 2%      |
| HP RAM Module 4GB DIMM DDR3 1600MT/s                     | 1        | 2%      |
| Elpida RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 2%      |
| Elpida RAM EBE10UE8ACWA-6E-E 1024MB DIMM DDR2 667MT/s    | 1        | 2%      |
| Crucial RAM CT51264BF160B.C16F 4GB DIMM DDR3 1600MT/s    | 1        | 2%      |
| Crucial RAM CT25664BA160B.C16F 2GB DIMM DDR3 1600MT/s    | 1        | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 22       | 61.11%  |
| DDR4    | 10       | 27.78%  |
| SDRAM   | 2        | 5.56%   |
| DDR2    | 1        | 2.78%   |
| Unknown | 1        | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 30       | 85.71%  |
| SODIMM | 5        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 13       | 31.71%  |
| 4096  | 10       | 24.39%  |
| 2048  | 8        | 19.51%  |
| 32768 | 3        | 7.32%   |
| 1024  | 3        | 7.32%   |
| 16384 | 2        | 4.88%   |
| 512   | 1        | 2.44%   |
| 128   | 1        | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 42.5%   |
| 3600    | 4        | 10%     |
| 1333    | 4        | 10%     |
| 3200    | 2        | 5%      |
| 2400    | 2        | 5%      |
| 1866    | 2        | 5%      |
| Unknown | 2        | 5%      |
| 3800    | 1        | 2.5%    |
| 2667    | 1        | 2.5%    |
| 2200    | 1        | 2.5%    |
| 2133    | 1        | 2.5%    |
| 1800    | 1        | 2.5%    |
| 800     | 1        | 2.5%    |
| 667     | 1        | 2.5%    |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 2        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star Vimicro USB2.0 Camera      | 1        | 50%     |
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 50%     |

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
| 0     | 30       | 71.43%  |
| 1     | 5        | 11.9%   |
| 2     | 3        | 7.14%   |
| 3     | 2        | 4.76%   |
| 7     | 1        | 2.38%   |
| 4     | 1        | 2.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 8        | 33.33%  |
| Communication controller | 5        | 20.83%  |
| Net/wireless             | 4        | 16.67%  |
| Storage/ata              | 2        | 8.33%   |
| Net/ethernet             | 2        | 8.33%   |
| Unassigned class         | 1        | 4.17%   |
| Sound                    | 1        | 4.17%   |
| Network                  | 1        | 4.17%   |

