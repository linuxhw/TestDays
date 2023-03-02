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

Total: 53

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0J1C3P A00                  | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
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
| Dell          | 0J1C3P A00                  | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Dell          | 0J1C3P A00                  | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.12.0               | 6        | 15.79%  |
| Alpine 3.17_alpha20220809   | 4        | 10.53%  |
| Alpine 3.16.0               | 3        | 7.89%   |
| Alpine 3.13.0_alpha20200626 | 3        | 7.89%   |
| Alpine 3.17.1               | 2        | 5.26%   |
| Alpine 3.16.1               | 2        | 5.26%   |
| Alpine 3.15.4               | 2        | 5.26%   |
| Alpine 3.11.2               | 2        | 5.26%   |
| Alpine 3.8.4                | 1        | 2.63%   |
| Alpine 3.17.0               | 1        | 2.63%   |
| Alpine 3.16.3               | 1        | 2.63%   |
| Alpine 3.16.2               | 1        | 2.63%   |
| Alpine 3.16.0_alpha20220328 | 1        | 2.63%   |
| Alpine 3.15.6               | 1        | 2.63%   |
| Alpine 3.15.0               | 1        | 2.63%   |
| Alpine 3.14.2               | 1        | 2.63%   |
| Alpine 3.14.0               | 1        | 2.63%   |
| Alpine 3.13.6               | 1        | 2.63%   |
| Alpine 3.13.2               | 1        | 2.63%   |
| Alpine 3.13.1               | 1        | 2.63%   |
| Alpine 3.13.0_alpha20201218 | 1        | 2.63%   |
| Alpine 3.12.3               | 1        | 2.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 35       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.43-1-lts      | 5        | 13.16%  |
| 5.15.60-0-lts     | 2        | 5.26%   |
| 6.0.10-0-edge     | 1        | 2.63%   |
| 5.8.0             | 1        | 2.63%   |
| 5.7.4             | 1        | 2.63%   |
| 5.4.84-0-lts      | 1        | 2.63%   |
| 5.4.6-0-lts       | 1        | 2.63%   |
| 5.4.58-0-lts      | 1        | 2.63%   |
| 5.4.57-0-lts      | 1        | 2.63%   |
| 5.4.0-77-generic  | 1        | 2.63%   |
| 5.18.0-0-asahi    | 1        | 2.63%   |
| 5.17.9-0-edge     | 1        | 2.63%   |
| 5.17.3-0-edge     | 1        | 2.63%   |
| 5.15.87-0-lts     | 1        | 2.63%   |
| 5.15.86-0-lts     | 1        | 2.63%   |
| 5.15.83-0-lts     | 1        | 2.63%   |
| 5.15.80           | 1        | 2.63%   |
| 5.15.74-0-lts     | 1        | 2.63%   |
| 5.15.70-0-lts     | 1        | 2.63%   |
| 5.15.57-0-lts     | 1        | 2.63%   |
| 5.15.46-1-lts     | 1        | 2.63%   |
| 5.15.40-0-lts     | 1        | 2.63%   |
| 5.15.38-0-lts     | 1        | 2.63%   |
| 5.15.32-0-lts     | 1        | 2.63%   |
| 5.15.17-0-lts     | 1        | 2.63%   |
| 5.14.0-1054-oem   | 1        | 2.63%   |
| 5.10.81           | 1        | 2.63%   |
| 5.10.61-0-lts     | 1        | 2.63%   |
| 5.10.16-0-lts     | 1        | 2.63%   |
| 5.10.12-0-lts     | 1        | 2.63%   |
| 5.10.1-0-lts      | 1        | 2.63%   |
| 4.14.89-0-vanilla | 1        | 2.63%   |
| 3.10.105          | 1        | 2.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.43   | 5        | 13.16%  |
| 5.15.60  | 2        | 5.26%   |
| 6.0.10   | 1        | 2.63%   |
| 5.8.0    | 1        | 2.63%   |
| 5.7.4    | 1        | 2.63%   |
| 5.4.84   | 1        | 2.63%   |
| 5.4.6    | 1        | 2.63%   |
| 5.4.58   | 1        | 2.63%   |
| 5.4.57   | 1        | 2.63%   |
| 5.4.0    | 1        | 2.63%   |
| 5.18.0   | 1        | 2.63%   |
| 5.17.9   | 1        | 2.63%   |
| 5.17.3   | 1        | 2.63%   |
| 5.15.87  | 1        | 2.63%   |
| 5.15.86  | 1        | 2.63%   |
| 5.15.83  | 1        | 2.63%   |
| 5.15.80  | 1        | 2.63%   |
| 5.15.74  | 1        | 2.63%   |
| 5.15.70  | 1        | 2.63%   |
| 5.15.57  | 1        | 2.63%   |
| 5.15.46  | 1        | 2.63%   |
| 5.15.40  | 1        | 2.63%   |
| 5.15.38  | 1        | 2.63%   |
| 5.15.32  | 1        | 2.63%   |
| 5.15.17  | 1        | 2.63%   |
| 5.14.0   | 1        | 2.63%   |
| 5.10.81  | 1        | 2.63%   |
| 5.10.61  | 1        | 2.63%   |
| 5.10.16  | 1        | 2.63%   |
| 5.10.12  | 1        | 2.63%   |
| 5.10.1   | 1        | 2.63%   |
| 4.14.89  | 1        | 2.63%   |
| 3.10.105 | 1        | 2.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 13       | 35.14%  |
| 5.4     | 10       | 27.03%  |
| 5.10    | 5        | 13.51%  |
| 5.17    | 2        | 5.41%   |
| 6.0     | 1        | 2.7%    |
| 5.8     | 1        | 2.7%    |
| 5.7     | 1        | 2.7%    |
| 5.18    | 1        | 2.7%    |
| 5.14    | 1        | 2.7%    |
| 4.14    | 1        | 2.7%    |
| 3.10    | 1        | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 31       | 88.57%  |
| i686    | 3        | 8.57%   |
| aarch64 | 1        | 2.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 31       | 88.57%  |
| XFCE    | 2        | 5.71%   |
| sway    | 1        | 2.86%   |
| i3      | 1        | 2.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 77.14%  |
| X11     | 7        | 20%     |
| Wayland | 1        | 2.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 33       | 94.29%  |
| LightDM | 2        | 5.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 22       | 61.11%  |
| Unknown | 13       | 36.11%  |
| en_US   | 1        | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 23       | 65.71%  |
| EFI  | 12       | 34.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 28       | 77.78%  |
| Overlay | 3        | 8.33%   |
| Btrfs   | 2        | 5.56%   |
| Zfs     | 1        | 2.78%   |
| Tmpfs   | 1        | 2.78%   |
| Unknown | 1        | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 58.33%  |
| GPT     | 10       | 27.78%  |
| MBR     | 5        | 13.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 82.86%  |
| Yes       | 6        | 17.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 91.43%  |
| Yes       | 3        | 8.57%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 7        | 20%     |
| ASUSTek Computer    | 5        | 14.29%  |
| Gigabyte Technology | 4        | 11.43%  |
| ASRock              | 4        | 11.43%  |
| Lenovo              | 2        | 5.71%   |
| Intel               | 2        | 5.71%   |
| Hewlett-Packard     | 2        | 5.71%   |
| Fujitsu             | 2        | 5.71%   |
| Unknown             | 2        | 5.71%   |
| VIA Technologies    | 1        | 2.86%   |
| Shuttle             | 1        | 2.86%   |
| MSI                 | 1        | 2.86%   |
| Gateway             | 1        | 2.86%   |
| eMachines           | 1        | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte Z490I AORUS ULTRA         | 2        | 5.71%   |
| Dell Precision 3660                | 2        | 5.71%   |
| ASUS All Series                    | 2        | 5.71%   |
| Unknown                            | 2        | 5.71%   |
| VIA KM266APro-835                  | 1        | 2.86%   |
| Shuttle DS81D                      | 1        | 2.86%   |
| MSI MS-7877                        | 1        | 2.86%   |
| Lenovo ThinkCentre M93p 10AB0016US | 1        | 2.86%   |
| Lenovo H535 10117                  | 1        | 2.86%   |
| Intel DQ67SW                       | 1        | 2.86%   |
| Intel DH61BF AAG81311-101          | 1        | 2.86%   |
| HP ProLiant MicroServer Gen8       | 1        | 2.86%   |
| HP Compaq 4000 Pro SFF PC          | 1        | 2.86%   |
| Gigabyte X570S AERO G              | 1        | 2.86%   |
| Gigabyte B550 AORUS ELITE V2       | 1        | 2.86%   |
| Gateway SX2185                     | 1        | 2.86%   |
| Fujitsu PRIMERGY TX100 S2          | 1        | 2.86%   |
| Fujitsu FujitsuTP7000              | 1        | 2.86%   |
| eMachines EL1352G                  | 1        | 2.86%   |
| Dell OptiPlex 755                  | 1        | 2.86%   |
| Dell OptiPlex 5000                 | 1        | 2.86%   |
| Dell OptiPlex 3020M                | 1        | 2.86%   |
| Dell OptiPlex 3010                 | 1        | 2.86%   |
| Dell Inspiron 3647                 | 1        | 2.86%   |
| ASUS TS10                          | 1        | 2.86%   |
| ASUS PRIME H370M-PLUS              | 1        | 2.86%   |
| ASUS P8H67-V                       | 1        | 2.86%   |
| ASRock X470 Master SLI/ac          | 1        | 2.86%   |
| ASRock J3455M                      | 1        | 2.86%   |
| ASRock H81M                        | 1        | 2.86%   |
| ASRock D1800B-ITX                  | 1        | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 4        | 11.43%  |
| Gigabyte Z490I        | 2        | 5.71%   |
| Dell Precision        | 2        | 5.71%   |
| ASUS All              | 2        | 5.71%   |
| Unknown               | 2        | 5.71%   |
| VIA KM266APro-835     | 1        | 2.86%   |
| Shuttle DS81D         | 1        | 2.86%   |
| MSI MS-7877           | 1        | 2.86%   |
| Lenovo ThinkCentre    | 1        | 2.86%   |
| Lenovo H535           | 1        | 2.86%   |
| Intel DQ67SW          | 1        | 2.86%   |
| Intel DH61BF          | 1        | 2.86%   |
| HP ProLiant           | 1        | 2.86%   |
| HP Compaq             | 1        | 2.86%   |
| Gigabyte X570S        | 1        | 2.86%   |
| Gigabyte B550         | 1        | 2.86%   |
| Gateway SX2185        | 1        | 2.86%   |
| Fujitsu PRIMERGY      | 1        | 2.86%   |
| Fujitsu FujitsuTP7000 | 1        | 2.86%   |
| eMachines EL1352G     | 1        | 2.86%   |
| Dell Inspiron         | 1        | 2.86%   |
| ASUS TS10             | 1        | 2.86%   |
| ASUS PRIME            | 1        | 2.86%   |
| ASUS P8H67-V          | 1        | 2.86%   |
| ASRock X470           | 1        | 2.86%   |
| ASRock J3455M         | 1        | 2.86%   |
| ASRock H81M           | 1        | 2.86%   |
| ASRock D1800B-ITX     | 1        | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 8        | 22.86%  |
| 2012    | 5        | 14.29%  |
| 2013    | 4        | 11.43%  |
| 2020    | 3        | 8.57%   |
| 2018    | 3        | 8.57%   |
| 2010    | 3        | 8.57%   |
| 2022    | 1        | 2.86%   |
| 2021    | 1        | 2.86%   |
| 2017    | 1        | 2.86%   |
| 2016    | 1        | 2.86%   |
| 2011    | 1        | 2.86%   |
| 2009    | 1        | 2.86%   |
| 2007    | 1        | 2.86%   |
| 2004    | 1        | 2.86%   |
| Unknown | 1        | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 35       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 35       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 35       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 8        | 21.05%  |
| 16.01-24.0      | 7        | 18.42%  |
| 8.01-16.0       | 6        | 15.79%  |
| 4.01-8.0        | 5        | 13.16%  |
| 32.01-64.0      | 5        | 13.16%  |
| 1.01-2.0        | 2        | 5.26%   |
| 0.51-1.0        | 2        | 5.26%   |
| More than 256.0 | 1        | 2.63%   |
| 2.01-3.0        | 1        | 2.63%   |
| 0.01-0.5        | 1        | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 11       | 30.56%  |
| 1.01-2.0  | 8        | 22.22%  |
| 0.51-1.0  | 6        | 16.67%  |
| 3.01-4.0  | 4        | 11.11%  |
| 4.01-8.0  | 2        | 5.56%   |
| 2.01-3.0  | 2        | 5.56%   |
| 8.01-16.0 | 2        | 5.56%   |
| Unknown   | 1        | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 44.44%  |
| 3      | 8        | 22.22%  |
| 2      | 8        | 22.22%  |
| 4      | 3        | 8.33%   |
| 12     | 1        | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 82.86%  |
| Yes       | 6        | 17.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 97.14%  |
| No        | 1        | 2.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 71.43%  |
| Yes       | 10       | 28.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 77.14%  |
| Yes       | 8        | 22.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 10       | 27.78%  |
| Russia      | 4        | 11.11%  |
| Germany     | 3        | 8.33%   |
| UK          | 2        | 5.56%   |
| Sweden      | 2        | 5.56%   |
| Norway      | 2        | 5.56%   |
| Ukraine     | 1        | 2.78%   |
| Switzerland | 1        | 2.78%   |
| Spain       | 1        | 2.78%   |
| South Korea | 1        | 2.78%   |
| Portugal    | 1        | 2.78%   |
| Poland      | 1        | 2.78%   |
| Pakistan    | 1        | 2.78%   |
| Indonesia   | 1        | 2.78%   |
| Guatemala   | 1        | 2.78%   |
| Greece      | 1        | 2.78%   |
| Canada      | 1        | 2.78%   |
| Austria     | 1        | 2.78%   |
| Argentina   | 1        | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Springfield         | 4        | 11.11%  |
| St Petersburg       | 3        | 8.33%   |
| Manitowoc           | 3        | 8.33%   |
| As                  | 2        | 5.56%   |
| Zurich              | 1        | 2.78%   |
| Stockholm           | 1        | 2.78%   |
| Salzburg            | 1        | 2.78%   |
| Redwood City        | 1        | 2.78%   |
| Penza               | 1        | 2.78%   |
| Oberhausen          | 1        | 2.78%   |
| Lisbon              | 1        | 2.78%   |
| Lahore              | 1        | 2.78%   |
| Kharkiv             | 1        | 2.78%   |
| Jember              | 1        | 2.78%   |
| Heraklion           | 1        | 2.78%   |
| Hamburg             | 1        | 2.78%   |
| Guatemala City      | 1        | 2.78%   |
| Goyang-si           | 1        | 2.78%   |
| Gothenburg          | 1        | 2.78%   |
| Glasgow             | 1        | 2.78%   |
| General San Martin  | 1        | 2.78%   |
| Frankfurt am Main   | 1        | 2.78%   |
| Durham              | 1        | 2.78%   |
| Czarna Białostocka | 1        | 2.78%   |
| Chicago             | 1        | 2.78%   |
| Bradford            | 1        | 2.78%   |
| Barrow in Furness   | 1        | 2.78%   |
| Barcelona           | 1        | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 17     | 17.54%  |
| Seagate             | 9        | 19     | 15.79%  |
| WDC                 | 8        | 13     | 14.04%  |
| Toshiba             | 4        | 4      | 7.02%   |
| HGST                | 4        | 4      | 7.02%   |
| Hitachi             | 3        | 3      | 5.26%   |
| A-DATA Technology   | 3        | 3      | 5.26%   |
| Kingston            | 2        | 2      | 3.51%   |
| Intel               | 2        | 3      | 3.51%   |
| Crucial             | 2        | 5      | 3.51%   |
| Unknown             | 1        | 1      | 1.75%   |
| Transcend           | 1        | 1      | 1.75%   |
| SK hynix            | 1        | 1      | 1.75%   |
| SanDisk             | 1        | 1      | 1.75%   |
| Phison Electronics  | 1        | 1      | 1.75%   |
| LITEON              | 1        | 1      | 1.75%   |
| Lexar               | 1        | 1      | 1.75%   |
| KIOXIA              | 1        | 1      | 1.75%   |
| Kingmax             | 1        | 1      | 1.75%   |
| Apple               | 1        | 3      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 960 EVO 500GB             | 2        | 2.94%   |
| WDC WDS250G2B0B-00YS70 250GB SSD      | 1        | 1.47%   |
| WDC WDS250G2B0B 250GB SSD             | 1        | 1.47%   |
| WDC WDS250G2B0A 250GB SSD             | 1        | 1.47%   |
| WDC WD800AAJS-00 80GB                 | 1        | 1.47%   |
| WDC WD3200AAKX-0 320GB                | 1        | 1.47%   |
| WDC WD20EZRZ-00Z 2TB                  | 1        | 1.47%   |
| WDC WD1600BEVT-2 160GB                | 1        | 1.47%   |
| WDC WD140EDGZ-11B2DA2 14TB            | 1        | 1.47%   |
| WDC WD120EFBX-68B0EN0 12TB            | 1        | 1.47%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1        | 1.47%   |
| WDC WD10EZEX-21M2NA0 1TB              | 1        | 1.47%   |
| Unknown MMC Card  32GB                | 1        | 1.47%   |
| Transcend SSD 1GB                     | 1        | 1.47%   |
| Toshiba MQ04ABF100 1TB                | 1        | 1.47%   |
| Toshiba MQ01ABF050 500GB              | 1        | 1.47%   |
| Toshiba MK3252GS 320GB                | 1        | 1.47%   |
| Toshiba HDWD130 3TB                   | 1        | 1.47%   |
| SK hynix SC300 M.2 2280 256 256GB SSD | 1        | 1.47%   |
| Seagate ST980310AS 80GB               | 1        | 1.47%   |
| Seagate ST5000LM000-2AN170 5TB        | 1        | 1.47%   |
| Seagate ST4000VN008-2DR1 4TB          | 1        | 1.47%   |
| Seagate ST4000NC000-1FR1 4TB          | 1        | 1.47%   |
| Seagate ST380815AS 80GB               | 1        | 1.47%   |
| Seagate ST3500418AS 500GB             | 1        | 1.47%   |
| Seagate ST3000DM001-1ER166 3TB        | 1        | 1.47%   |
| Seagate ST2000DL001-9VT1 2TB          | 1        | 1.47%   |
| Seagate ST14000VN0008-2KU103 14TB     | 1        | 1.47%   |
| Seagate ST1000LM048-2E71 1TB          | 1        | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 1.47%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1.47%   |
| SanDisk SDSA6MM 16GB SSD              | 1        | 1.47%   |
| Samsung SSD 980 PRO 1TB               | 1        | 1.47%   |
| Samsung SSD 980 500GB                 | 1        | 1.47%   |
| Samsung SSD 970 EVO Plus 1TB          | 1        | 1.47%   |
| Samsung SSD 970 EVO 250GB             | 1        | 1.47%   |
| Samsung SSD 870 QVO 1TB               | 1        | 1.47%   |
| Samsung SSD 870 EVO 1TB               | 1        | 1.47%   |
| Samsung SSD 850 EVO 500GB             | 1        | 1.47%   |
| Samsung SSD 750 EVO 250GB             | 1        | 1.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 19     | 33.33%  |
| WDC                 | 6        | 10     | 22.22%  |
| Toshiba             | 4        | 4      | 14.81%  |
| HGST                | 4        | 4      | 14.81%  |
| Hitachi             | 3        | 3      | 11.11%  |
| Samsung Electronics | 1        | 2      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 6      | 19.05%  |
| A-DATA Technology   | 3        | 3      | 14.29%  |
| WDC                 | 2        | 3      | 9.52%   |
| Kingston            | 2        | 2      | 9.52%   |
| Intel               | 2        | 3      | 9.52%   |
| Crucial             | 2        | 5      | 9.52%   |
| Transcend           | 1        | 1      | 4.76%   |
| SK hynix            | 1        | 1      | 4.76%   |
| SanDisk             | 1        | 1      | 4.76%   |
| LITEON              | 1        | 1      | 4.76%   |
| Lexar               | 1        | 1      | 4.76%   |
| Kingmax             | 1        | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 42     | 42%     |
| SSD  | 18       | 28     | 36%     |
| NVMe | 10       | 14     | 20%     |
| MMC  | 1        | 1      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 68     | 71.43%  |
| NVMe | 10       | 14     | 23.81%  |
| SAS  | 1        | 2      | 2.38%   |
| MMC  | 1        | 1      | 2.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 26       | 39     | 63.41%  |
| 0.51-1.0   | 7        | 12     | 17.07%  |
| 3.01-4.0   | 2        | 6      | 4.88%   |
| 2.01-3.0   | 2        | 2      | 4.88%   |
| 4.01-10.0  | 2        | 2      | 4.88%   |
| 10.01-20.0 | 1        | 6      | 2.44%   |
| 1.01-2.0   | 1        | 3      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 10       | 27.78%  |
| 101-250        | 7        | 19.44%  |
| 21-50          | 4        | 11.11%  |
| 2001-3000      | 4        | 11.11%  |
| 1-20           | 4        | 11.11%  |
| More than 3000 | 3        | 8.33%   |
| 251-500        | 2        | 5.56%   |
| 1001-2000      | 1        | 2.78%   |
| 51-100         | 1        | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 15       | 41.67%  |
| Unknown        | 10       | 27.78%  |
| 21-50          | 4        | 11.11%  |
| 251-500        | 3        | 8.33%   |
| More than 3000 | 1        | 2.78%   |
| 2001-3000      | 1        | 2.78%   |
| 1001-2000      | 1        | 2.78%   |
| 51-100         | 1        | 2.78%   |

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
| Works    | 27       | 58     | 67.5%   |
| Detected | 7        | 20     | 17.5%   |
| Malfunc  | 6        | 7      | 15%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 26       | 52%     |
| Samsung Electronics       | 7        | 14%     |
| AMD                       | 6        | 12%     |
| LSI Logic / Symbios Logic | 2        | 4%      |
| Adaptec                   | 2        | 4%      |
| VIA Technologies          | 1        | 2%      |
| Promise Technology        | 1        | 2%      |
| Phison Electronics        | 1        | 2%      |
| Nvidia                    | 1        | 2%      |
| KIOXIA                    | 1        | 2%      |
| Broadcom / LSI            | 1        | 2%      |
| ASMedia Technology        | 1        | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 8.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 6.78%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4        | 6.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 5.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 3.39%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2        | 3.39%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 3.39%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 3.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 3.39%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 3.39%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2        | 3.39%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 2        | 3.39%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 1.69%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.69%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.69%   |
| Promise PDC42819 [FastTrak TX2650/TX4650]                                      | 1        | 1.69%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 1.69%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.69%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.69%   |
| KIOXIA Non-Volatile memory controller                                          | 1        | 1.69%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.69%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1        | 1.69%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1        | 1.69%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 1.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.69%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 1.69%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1        | 1.69%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                        | 1        | 1.69%   |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                        | 1        | 1.69%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 1        | 1.69%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 1.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 27       | 51.92%  |
| RAID | 9        | 17.31%  |
| NVMe | 8        | 15.38%  |
| IDE  | 6        | 11.54%  |
| SAS  | 2        | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 27       | 75%     |
| AMD     | 8        | 22.22%  |
| Unknown | 1        | 2.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz       | 2        | 5.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2        | 5.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 5.56%   |
| Intel Core i3-4150 CPU @ 3.50GHz        | 2        | 5.56%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz      | 1        | 2.78%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1        | 2.78%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz  | 1        | 2.78%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 1        | 2.78%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 1        | 2.78%   |
| Intel Core i5-4570T CPU @ 2.90GHz       | 1        | 2.78%   |
| Intel Core i5-3450 CPU @ 3.10GHz        | 1        | 2.78%   |
| Intel Core i3-3240 CPU @ 3.40GHz        | 1        | 2.78%   |
| Intel Core i3-3220T CPU @ 2.80GHz       | 1        | 2.78%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 1        | 2.78%   |
| Intel Celeron M processor 1.00GHz       | 1        | 2.78%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 1        | 2.78%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 1        | 2.78%   |
| Intel Celeron CPU J1800 @ 2.41GHz       | 1        | 2.78%   |
| Intel Celeron CPU G1850 @ 2.90GHz       | 1        | 2.78%   |
| Intel Celeron CPU E3400 @ 2.60GHz       | 1        | 2.78%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 1        | 2.78%   |
| Intel 12th Gen Core i9-12900K           | 1        | 2.78%   |
| Intel 12th Gen Core i7-12700T           | 1        | 2.78%   |
| AMD Sempron 145 Processor               | 1        | 2.78%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 1        | 2.78%   |
| AMD Ryzen 7 5700X 8-Core Processor      | 1        | 2.78%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 1        | 2.78%   |
| AMD Mobile Duron processor              | 1        | 2.78%   |
| AMD FX-8350 Eight-Core Processor        | 1        | 2.78%   |
| AMD E1-2500 APU with Radeon HD Graphics | 1        | 2.78%   |
| AMD A8-5500 APU with Radeon HD Graphics | 1        | 2.78%   |
|                                         | 1        | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 6        | 16.67%  |
| Intel Core i3      | 5        | 13.89%  |
| Intel Celeron      | 5        | 13.89%  |
| Other              | 4        | 11.11%  |
| Intel Core i9      | 2        | 5.56%   |
| Intel Core i7      | 2        | 5.56%   |
| AMD Ryzen 7        | 2        | 5.56%   |
| Intel Xeon Gold    | 1        | 2.78%   |
| Intel Xeon         | 1        | 2.78%   |
| Intel Pentium Dual | 1        | 2.78%   |
| Intel Celeron M    | 1        | 2.78%   |
| Intel Atom         | 1        | 2.78%   |
| AMD Sempron        | 1        | 2.78%   |
| AMD Ryzen 9        | 1        | 2.78%   |
| AMD FX             | 1        | 2.78%   |
| AMD E1             | 1        | 2.78%   |
| AMD A8             | 1        | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 36.11%  |
| 2      | 11       | 30.56%  |
| 1      | 3        | 8.33%   |
| 12     | 2        | 5.56%   |
| 10     | 2        | 5.56%   |
| 8      | 2        | 5.56%   |
| 32     | 1        | 2.78%   |
| 16     | 1        | 2.78%   |
| 6      | 1        | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 97.22%  |
| 2      | 1        | 2.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 57.14%  |
| 2      | 15       | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 18       | 51.43%  |
| 32-bit, 64-bit | 14       | 40%     |
| 32-bit         | 2        | 5.71%   |
| 64-bit         | 1        | 2.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 52.78%  |
| 0x306c3    | 4        | 11.11%  |
| 0x306a9    | 2        | 5.56%   |
| 0xa0655    | 1        | 2.78%   |
| 0x906ea    | 1        | 2.78%   |
| 0x90672    | 1        | 2.78%   |
| 0x6fd      | 1        | 2.78%   |
| 0x6d8      | 1        | 2.78%   |
| 0x506c9    | 1        | 2.78%   |
| 0x406c4    | 1        | 2.78%   |
| 0x106e5    | 1        | 2.78%   |
| 0x08701021 | 1        | 2.78%   |
| 0x0800820d | 1        | 2.78%   |
| 0x010000b6 | 1        | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 7        | 19.44%  |
| Silvermont       | 3        | 8.33%   |
| SandyBridge      | 3        | 8.33%   |
| IvyBridge        | 3        | 8.33%   |
| Piledriver       | 2        | 5.56%   |
| CometLake        | 2        | 5.56%   |
| Unknown          | 2        | 5.56%   |
| Zen+             | 1        | 2.78%   |
| Zen 3            | 1        | 2.78%   |
| Zen 2            | 1        | 2.78%   |
| Skylake          | 1        | 2.78%   |
| Penryn           | 1        | 2.78%   |
| P6               | 1        | 2.78%   |
| Nehalem          | 1        | 2.78%   |
| KabyLake         | 1        | 2.78%   |
| K6               | 1        | 2.78%   |
| K10              | 1        | 2.78%   |
| Jaguar           | 1        | 2.78%   |
| Goldmont         | 1        | 2.78%   |
| Core             | 1        | 2.78%   |
| Alderlake Hybrid | 1        | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 24       | 63.16%  |
| AMD                        | 6        | 15.79%  |
| Nvidia                     | 5        | 13.16%  |
| Matrox Electronics Systems | 2        | 5.26%   |
| VIA Technologies           | 1        | 2.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 10.53%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 7.89%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 7.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 5.26%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 5.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 5.26%   |
| Intel AlderLake-S GT1                                                                    | 2        | 5.26%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 5.26%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 2.63%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 2.63%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1        | 2.63%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 2.63%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1        | 2.63%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 2.63%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 2.63%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1        | 2.63%   |
| Intel HD Graphics 500                                                                    | 1        | 2.63%   |
| Intel DG2 [Arc A750]                                                                     | 1        | 2.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.63%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 2.63%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 2.63%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 2.63%   |
| AMD Trinity [Radeon HD 7560D]                                                            | 1        | 2.63%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                                   | 1        | 2.63%   |
| AMD ES1000                                                                               | 1        | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 22       | 61.11%  |
| 1 x AMD         | 6        | 16.67%  |
| 1 x Nvidia      | 3        | 8.33%   |
| Other           | 1        | 2.78%   |
| 2 x Intel       | 1        | 2.78%   |
| 1 x VIA         | 1        | 2.78%   |
| Nvidia + Matrox | 1        | 2.78%   |
| 1 x Matrox      | 1        | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 29       | 80.56%  |
| Unknown     | 6        | 16.67%  |
| Proprietary | 1        | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 80%     |
| 7.01-8.0   | 2        | 5.71%   |
| 0.01-0.5   | 2        | 5.71%   |
| 3.01-4.0   | 1        | 2.86%   |
| 1.01-2.0   | 1        | 2.86%   |
| 8.01-16.0  | 1        | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 7        | 26.92%  |
| Samsung Electronics | 4        | 15.38%  |
| BenQ                | 3        | 11.54%  |
| AOC                 | 3        | 11.54%  |
| Goldstar            | 2        | 7.69%   |
| Acer                | 2        | 7.69%   |
| ViewSonic           | 1        | 3.85%   |
| Mi                  | 1        | 3.85%   |
| KVM                 | 1        | 3.85%   |
| Elo Touch           | 1        | 3.85%   |
| CTC                 | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell 2009W DEL4041 1680x1050 433x271mm 20.1-inch                      | 3        | 11.11%  |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 2        | 7.41%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1        | 3.7%    |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                      | 1        | 3.7%    |
| KVM LCD Monitor17 KVM4308 1280x1024 338x270mm 17.0-inch               | 1        | 3.7%    |
| Goldstar Ultra HD GSM5B08 3780x2160 600x340mm 27.2-inch               | 1        | 3.7%    |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                 | 1        | 3.7%    |
| Elo Touch ET1717L ELO1717 1280x1024 338x270mm 17.0-inch               | 1        | 3.7%    |
| Dell U2518D DEL413A 2560x1440 550x310mm 24.9-inch                     | 1        | 3.7%    |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 1        | 3.7%    |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                     | 1        | 3.7%    |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                     | 1        | 3.7%    |
| CTC KD02909-8770A CTC0770 1024x768 304x228mm 15.0-inch                | 1        | 3.7%    |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 1        | 3.7%    |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                     | 1        | 3.7%    |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                     | 1        | 3.7%    |
| AOC 718Swag-1 AOCC750 1440x900 367x230mm 17.1-inch                    | 1        | 3.7%    |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                      | 1        | 3.7%    |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                      | 1        | 3.7%    |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                     | 1        | 3.7%    |
| Acer S236HL ACR0387 1920x1080 510x286mm 23.0-inch                     | 1        | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 8        | 30.77%  |
| 1680x1050 (WSXGA+) | 4        | 15.38%  |
| 1280x1024 (SXGA)   | 4        | 15.38%  |
| 2560x1440 (QHD)    | 3        | 11.54%  |
| 3840x2160 (4K)     | 2        | 7.69%   |
| 3440x1440          | 2        | 7.69%   |
| 1440x900 (WXGA+)   | 1        | 3.85%   |
| 1366x768 (WXGA)    | 1        | 3.85%   |
| 1024x768 (XGA)     | 1        | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 4        | 14.81%  |
| 20     | 4        | 14.81%  |
| 23     | 3        | 11.11%  |
| 21     | 3        | 11.11%  |
| 17     | 3        | 11.11%  |
| 34     | 2        | 7.41%   |
| 24     | 2        | 7.41%   |
| 19     | 2        | 7.41%   |
| 54     | 1        | 3.7%    |
| 31     | 1        | 3.7%    |
| 25     | 1        | 3.7%    |
| 15     | 1        | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 33.33%  |
| 401-500     | 7        | 25.93%  |
| 351-400     | 3        | 11.11%  |
| 301-350     | 3        | 11.11%  |
| 701-800     | 2        | 7.41%   |
| 601-700     | 2        | 7.41%   |
| 1001-1500   | 1        | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 12       | 52.17%  |
| 5/4   | 4        | 17.39%  |
| 16/10 | 4        | 17.39%  |
| 21/9  | 2        | 8.7%    |
| 4/3   | 1        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 25.93%  |
| 151-200        | 7        | 25.93%  |
| 301-350        | 4        | 14.81%  |
| 351-500        | 3        | 11.11%  |
| 141-150        | 2        | 7.41%   |
| More than 1000 | 1        | 3.7%    |
| 251-300        | 1        | 3.7%    |
| 131-140        | 1        | 3.7%    |
| 101-110        | 1        | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 58.33%  |
| 101-120 | 5        | 20.83%  |
| 1-50    | 3        | 12.5%   |
| 161-240 | 1        | 4.17%   |
| 121-160 | 1        | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 55.56%  |
| 0     | 13       | 36.11%  |
| 2     | 2        | 5.56%   |
| 4     | 1        | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 18       | 37.5%   |
| Intel                           | 13       | 27.08%  |
| Broadcom                        | 5        | 10.42%  |
| Qualcomm Atheros                | 3        | 6.25%   |
| Xiaomi                          | 2        | 4.17%   |
| VIA Technologies                | 1        | 2.08%   |
| T & A Mobile Phones             | 1        | 2.08%   |
| Qualcomm Atheros Communications | 1        | 2.08%   |
| Qualcomm                        | 1        | 2.08%   |
| Nvidia                          | 1        | 2.08%   |
| MediaTek                        | 1        | 2.08%   |
| D-Link System                   | 1        | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 14       | 25%     |
| Intel Ethernet Controller I225-V                                      | 4        | 7.14%   |
| Intel Ethernet Connection (17) I219-LM                                | 2        | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                                        | 2        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2        | 3.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1        | 1.79%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                  | 1        | 1.79%   |
| VIA VT6102/VT6103 [Rhine-II]                                          | 1        | 1.79%   |
| T & A Mobile Phones Alcatel JOY TAB 2                                 | 1        | 1.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                    | 1        | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                   | 1        | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                            | 1        | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 1        | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                     | 1        | 1.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1        | 1.79%   |
| Qualcomm Redmi 9T                                                     | 1        | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter            | 1        | 1.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 1        | 1.79%   |
| Qualcomm Atheros AR9271 802.11n                                       | 1        | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1        | 1.79%   |
| Nvidia MCP61 Ethernet                                                 | 1        | 1.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                               | 1        | 1.79%   |
| Intel I211 Gigabit Network Connection                                 | 1        | 1.79%   |
| Intel Ethernet Connection I217-LM                                     | 1        | 1.79%   |
| Intel Ethernet Connection (7) I219-V                                  | 1        | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                      | 1        | 1.79%   |
| Intel Centrino Wireless-N 105                                         | 1        | 1.79%   |
| Intel 82578DM Gigabit Network Connection                              | 1        | 1.79%   |
| Intel 82567V-4 Gigabit Network Connection                             | 1        | 1.79%   |
| Intel 82566DM-2 Gigabit Network Connection                            | 1        | 1.79%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                       | 1        | 1.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1        | 1.79%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1        | 1.79%   |
| Broadcom BRCM4378 Wireless Network Adapter                            | 1        | 1.79%   |
| Broadcom BRCM4378 Bluetooth Controller                                | 1        | 1.79%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1        | 1.79%   |
| Broadcom BCM43227 802.11b/g/n                                         | 1        | 1.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 33.33%  |
| Realtek Semiconductor           | 3        | 25%     |
| Broadcom                        | 2        | 16.67%  |
| Qualcomm Atheros Communications | 1        | 8.33%   |
| Qualcomm Atheros                | 1        | 8.33%   |
| MediaTek                        | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Comet Lake PCH CNVi WiFi                             | 2        | 16.67%  |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 8.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 8.33%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 8.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 8.33%   |
| Qualcomm Atheros AR9271 802.11n                            | 1        | 8.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 1        | 8.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 8.33%   |
| Intel Centrino Wireless-N 105                              | 1        | 8.33%   |
| Broadcom BRCM4378 Wireless Network Adapter                 | 1        | 8.33%   |
| Broadcom BCM43227 802.11b/g/n                              | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 41.46%  |
| Intel                 | 13       | 31.71%  |
| Broadcom              | 3        | 7.32%   |
| Xiaomi                | 2        | 4.88%   |
| Qualcomm Atheros      | 2        | 4.88%   |
| VIA Technologies      | 1        | 2.44%   |
| Qualcomm              | 1        | 2.44%   |
| Nvidia                | 1        | 2.44%   |
| D-Link System         | 1        | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 14       | 33.33%  |
| Intel Ethernet Controller I225-V                                      | 4        | 9.52%   |
| Intel Ethernet Connection (17) I219-LM                                | 2        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2        | 4.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1        | 2.38%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                  | 1        | 2.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                          | 1        | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 1        | 2.38%   |
| Realtek RTL8125 2.5GbE Controller                                     | 1        | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1        | 2.38%   |
| Qualcomm Redmi 9T                                                     | 1        | 2.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 1        | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1        | 2.38%   |
| Nvidia MCP61 Ethernet                                                 | 1        | 2.38%   |
| Intel I211 Gigabit Network Connection                                 | 1        | 2.38%   |
| Intel Ethernet Connection I217-LM                                     | 1        | 2.38%   |
| Intel Ethernet Connection (7) I219-V                                  | 1        | 2.38%   |
| Intel 82578DM Gigabit Network Connection                              | 1        | 2.38%   |
| Intel 82567V-4 Gigabit Network Connection                             | 1        | 2.38%   |
| Intel 82566DM-2 Gigabit Network Connection                            | 1        | 2.38%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                       | 1        | 2.38%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1        | 2.38%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1        | 2.38%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1        | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 34       | 73.91%  |
| WiFi     | 10       | 21.74%  |
| Unknown  | 2        | 4.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 90.63%  |
| WiFi     | 3        | 9.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 56.76%  |
| 2     | 12       | 32.43%  |
| 3     | 2        | 5.41%   |
| 5     | 1        | 2.7%    |
| 4     | 1        | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 91.43%  |
| Yes  | 3        | 8.57%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 37.5%   |
| Cambridge Silicon Radio | 3        | 37.5%   |
| MediaTek                | 1        | 12.5%   |
| IMC Networks            | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 37.5%   |
| Intel AX201 Bluetooth                               | 2        | 25%     |
| MediaTek Wireless_Device                            | 1        | 12.5%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 12.5%   |
| IMC Networks Bluetooth Device                       | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 23       | 57.5%   |
| AMD                                  | 8        | 20%     |
| Nvidia                               | 4        | 10%     |
| VIA Technologies                     | 1        | 2.5%    |
| Thesycon Systemsoftware & Consulting | 1        | 2.5%    |
| Texas Instruments                    | 1        | 2.5%    |
| RODE Microphones                     | 1        | 2.5%    |
| Native Instruments                   | 1        | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 10.42%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 8.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 6.25%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 4.17%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 4.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 4.17%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 4.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 4.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 4.17%   |
| AMD FCH Azalia Controller                                                  | 2        | 4.17%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 2.08%   |
| Thesycon Systemsoftware & Consulting D10 Balanced                          | 1        | 2.08%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 2.08%   |
| RODE Microphones RODE NT-USB Mini                                          | 1        | 2.08%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 2.08%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 2.08%   |
| Native Instruments Komplete Audio 2                                        | 1        | 2.08%   |
| Intel USB PnP Sound Device                                                 | 1        | 2.08%   |
| Intel DG2 Audio Controller                                                 | 1        | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 2.08%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 2.08%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 6        | 14.63%  |
| Crucial             | 6        | 14.63%  |
| Unknown             | 5        | 12.2%   |
| Kingston            | 5        | 12.2%   |
| Samsung Electronics | 4        | 9.76%   |
| Elpida              | 4        | 9.76%   |
| Micron Technology   | 3        | 7.32%   |
| Corsair             | 2        | 4.88%   |
| Team                | 1        | 2.44%   |
| Qimonda             | 1        | 2.44%   |
| Patriot             | 1        | 2.44%   |
| Hewlett-Packard     | 1        | 2.44%   |
| Cors                | 1        | 2.44%   |
| A-DATA Technology   | 1        | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s      | 2        | 4.44%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s | 2        | 4.44%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 2.22%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 2.22%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s             | 1        | 2.22%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 2.22%   |
| Unknown RAM Module 128MB DIMM                            | 1        | 2.22%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 2.22%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s       | 1        | 2.22%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s  | 1        | 2.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2.22%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 2.22%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 2.22%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 2.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2.22%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 2.22%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 2.22%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s      | 1        | 2.22%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.22%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.22%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s         | 1        | 2.22%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 2.22%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s      | 1        | 2.22%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 2.22%   |
| Micron RAM 16ATF4G64HZ-3G2F1 32GB SODIMM DDR4 3200MT/s   | 1        | 2.22%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s      | 1        | 2.22%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 1        | 2.22%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 2.22%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 2.22%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s    | 1        | 2.22%   |
| Kingston RAM 9905595-005.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 2.22%   |
| Kingston RAM 9905474-019.A00LF 2048MB DIMM DDR3 1333MT/s | 1        | 2.22%   |
| HP RAM Module 4GB DIMM DDR3 1600MT/s                     | 1        | 2.22%   |
| Elpida RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 2.22%   |
| Elpida RAM EBE10UE8ACWA-6E-E 1GB DIMM DDR2 667MT/s       | 1        | 2.22%   |
| Crucial RAM CT51264BF160B.C16F 4GB DIMM DDR3 1600MT/s    | 1        | 2.22%   |
| Crucial RAM CT25664BA160B.C16F 2GB DIMM DDR3 1600MT/s    | 1        | 2.22%   |
| Crucial RAM CT102464BA160B.M16 8GB DIMM DDR3 1600MT/s    | 1        | 2.22%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s   | 1        | 2.22%   |
| Corsair RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 21       | 65.63%  |
| DDR4    | 7        | 21.88%  |
| SDRAM   | 2        | 6.25%   |
| DDR2    | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 28       | 90.32%  |
| SODIMM | 3        | 9.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 11       | 30.56%  |
| 4096  | 10       | 27.78%  |
| 2048  | 7        | 19.44%  |
| 32768 | 2        | 5.56%   |
| 16384 | 2        | 5.56%   |
| 1024  | 2        | 5.56%   |
| 512   | 1        | 2.78%   |
| 128   | 1        | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 47.22%  |
| 1333    | 4        | 11.11%  |
| 3600    | 3        | 8.33%   |
| 2400    | 2        | 5.56%   |
| 1866    | 2        | 5.56%   |
| Unknown | 2        | 5.56%   |
| 3800    | 1        | 2.78%   |
| 3200    | 1        | 2.78%   |
| 2200    | 1        | 2.78%   |
| 2133    | 1        | 2.78%   |
| 1800    | 1        | 2.78%   |
| 667     | 1        | 2.78%   |

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
| 0     | 26       | 72.22%  |
| 1     | 5        | 13.89%  |
| 3     | 2        | 5.56%   |
| 2     | 2        | 5.56%   |
| 5     | 1        | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 35.29%  |
| Net/wireless             | 4        | 23.53%  |
| Communication controller | 3        | 17.65%  |
| Unassigned class         | 1        | 5.88%   |
| Sound                    | 1        | 5.88%   |
| Network                  | 1        | 5.88%   |
| Net/ethernet             | 1        | 5.88%   |

