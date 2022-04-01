NixOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for NixOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 35

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | P8Q77-M                     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| Gigabyte   | X470 AORUS ULTRA GAMING-... | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| MSI        | B450M MORTAR MAX            | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| ASUSTek    | P8Z77-V LK                  | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek    | P8Z77-V LK                  | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA       | X299 FTW K                  | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell       | 0KJCC5 A00                  | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI        | X399 SLI PLUS               | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [051ac4ce21](https://linux-hardware.org/?probe=051ac4ce21) | Jan 13, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| ASUSTek    | Z170-P                      | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Gigabyte   | X570 AORUS ELITE            | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek    | PRIME Z390-A                | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Gigabyte   | H97M-D3H                    | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| MSI        | X399 SLI PLUS               | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASRock     | X570 Taichi                 | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock     | X570 Taichi                 | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek    | SABERTOOTH X99              | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI        | X570-A PRO                  | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock     | B450 Gaming-ITX/ac          | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock     | B450 Gaming-ITX/ac          | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock     | B450 Gaming-ITX/ac          | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| ASUSTek    | Pro WS W480-ACE             | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI        | MPG X570 GAMING PLUS        | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| HARDKERNEL | ODROID-H2                   | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| ASUSTek    | TUF GAMING X570-PLUS        | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| MSI        | MAG B550M BAZOOKA           | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek    | PRIME Z270-K                | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP         | 8055                        | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP         | 8055                        | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| ASRock     | TRX40 Creator               | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| NixOS 21.11                      | 6        | 22.22%  |
| NixOS 22.05                      | 3        | 11.11%  |
| NixOS                            | 3        | 11.11%  |
| NixOS 21.05pre-git               | 2        | 7.41%   |
| NixOS 21.11.20210528.540dccb     | 1        | 3.7%    |
| NixOS 21.05.993.93963c27b93      | 1        | 3.7%    |
| NixOS 21.05.2075.ff1ea3a36c1     | 1        | 3.7%    |
| NixOS 21.05.20210929.ee90403     | 1        | 3.7%    |
| NixOS 21.05.20210430.c8dff32     | 1        | 3.7%    |
| NixOS 21.05.20210224.f6b5bfd     | 1        | 3.7%    |
| NixOS 21.05.1471.a7512bb64b1     | 1        | 3.7%    |
| NixOS 21.03pre246062.420f89ceb26 | 1        | 3.7%    |
| NixOS 21.03.git.b4349c13a6d      | 1        | 3.7%    |
| NixOS 21.03.20201007.420f89c     | 1        | 3.7%    |
| NixOS 20.09pre231796.22a81aa5fc1 | 1        | 3.7%    |
| NixOS 20.09pre-git               | 1        | 3.7%    |
| NixOS 20.09.git.4a361b06a93      | 1        | 3.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| NixOS | 26       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.8.1-zen1             | 2        | 7.41%   |
| 5.10.102               | 2        | 7.41%   |
| 5.8.10                 | 1        | 3.7%    |
| 5.7.19                 | 1        | 3.7%    |
| 5.4.94                 | 1        | 3.7%    |
| 5.4.72                 | 1        | 3.7%    |
| 5.4.69                 | 1        | 3.7%    |
| 5.4.50                 | 1        | 3.7%    |
| 5.4.47                 | 1        | 3.7%    |
| 5.16.8-zen1            | 1        | 3.7%    |
| 5.15.7                 | 1        | 3.7%    |
| 5.15.26                | 1        | 3.7%    |
| 5.15.25                | 1        | 3.7%    |
| 5.15.18                | 1        | 3.7%    |
| 5.14.16-lqx1           | 1        | 3.7%    |
| 5.13.2                 | 1        | 3.7%    |
| 5.12.15                | 1        | 3.7%    |
| 5.11.16-zen1           | 1        | 3.7%    |
| 5.11.16-xanmod1-cacule | 1        | 3.7%    |
| 5.10.99                | 1        | 3.7%    |
| 5.10.62                | 1        | 3.7%    |
| 5.10.52                | 1        | 3.7%    |
| 5.10.43                | 1        | 3.7%    |
| 5.10.35                | 1        | 3.7%    |
| 5.10.17                | 1        | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.8.1    | 2        | 7.41%   |
| 5.11.16  | 2        | 7.41%   |
| 5.10.102 | 2        | 7.41%   |
| 5.8.10   | 1        | 3.7%    |
| 5.7.19   | 1        | 3.7%    |
| 5.4.94   | 1        | 3.7%    |
| 5.4.72   | 1        | 3.7%    |
| 5.4.69   | 1        | 3.7%    |
| 5.4.50   | 1        | 3.7%    |
| 5.4.47   | 1        | 3.7%    |
| 5.16.8   | 1        | 3.7%    |
| 5.15.7   | 1        | 3.7%    |
| 5.15.26  | 1        | 3.7%    |
| 5.15.25  | 1        | 3.7%    |
| 5.15.18  | 1        | 3.7%    |
| 5.14.16  | 1        | 3.7%    |
| 5.13.2   | 1        | 3.7%    |
| 5.12.15  | 1        | 3.7%    |
| 5.10.99  | 1        | 3.7%    |
| 5.10.62  | 1        | 3.7%    |
| 5.10.52  | 1        | 3.7%    |
| 5.10.43  | 1        | 3.7%    |
| 5.10.35  | 1        | 3.7%    |
| 5.10.17  | 1        | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 8        | 29.63%  |
| 5.4     | 5        | 18.52%  |
| 5.15    | 4        | 14.81%  |
| 5.8     | 3        | 11.11%  |
| 5.11    | 2        | 7.41%   |
| 5.7     | 1        | 3.7%    |
| 5.16    | 1        | 3.7%    |
| 5.14    | 1        | 3.7%    |
| 5.13    | 1        | 3.7%    |
| 5.12    | 1        | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 26       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 76.92%  |
| KDE     | 3        | 11.54%  |
| sway    | 2        | 7.69%   |
| GNOME   | 1        | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 73.08%  |
| X11     | 4        | 15.38%  |
| Wayland | 2        | 7.69%   |
| Tty     | 1        | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 92.31%  |
| SDDM    | 2        | 7.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 57.69%  |
| en_US   | 7        | 26.92%  |
| en_GB   | 2        | 7.69%   |
| pt_BR   | 1        | 3.85%   |
| en_DK   | 1        | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 21       | 77.78%  |
| BIOS | 6        | 22.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 11       | 42.31%  |
| Tmpfs   | 5        | 19.23%  |
| Xfs     | 3        | 11.54%  |
| Btrfs   | 3        | 11.54%  |
| Unknown | 2        | 7.69%   |
| Zfs     | 1        | 3.85%   |
| Ext2    | 1        | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 25       | 96.15%  |
| Unknown | 1        | 3.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 69.23%  |
| Yes       | 8        | 30.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 57.69%  |
| No        | 11       | 42.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 38.46%  |
| MSI                 | 6        | 23.08%  |
| Gigabyte Technology | 3        | 11.54%  |
| ASRock              | 3        | 11.54%  |
| Hewlett-Packard     | 1        | 3.85%   |
| HARDKERNEL          | 1        | 3.85%   |
| EVGA                | 1        | 3.85%   |
| Dell                | 1        | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7C37                      | 2        | 7.69%   |
| MSI MS-7C95                      | 1        | 3.85%   |
| MSI MS-7C84                      | 1        | 3.85%   |
| MSI MS-7B89                      | 1        | 3.85%   |
| MSI MS-7B09                      | 1        | 3.85%   |
| HP EliteDesk 800 G2 DM 35W       | 1        | 3.85%   |
| HARDKERNEL ODROID-H2             | 1        | 3.85%   |
| Gigabyte X570 AORUS ELITE        | 1        | 3.85%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 3.85%   |
| Gigabyte H97M-D3H                | 1        | 3.85%   |
| EVGA X299 FTW K                  | 1        | 3.85%   |
| Dell Precision Tower 7810        | 1        | 3.85%   |
| ASUS Z170-P                      | 1        | 3.85%   |
| ASUS TUF GAMING X570-PLUS        | 1        | 3.85%   |
| ASUS ROG STRIX B550-I GAMING     | 1        | 3.85%   |
| ASUS ROG STRIX B550-F GAMING     | 1        | 3.85%   |
| ASUS PRO-Q77 IU                  | 1        | 3.85%   |
| ASUS Pro WS W480-ACE             | 1        | 3.85%   |
| ASUS PRIME Z390-A                | 1        | 3.85%   |
| ASUS PRIME Z270-K                | 1        | 3.85%   |
| ASUS P8Z77-V LK                  | 1        | 3.85%   |
| ASUS All Series                  | 1        | 3.85%   |
| ASRock X570 Taichi               | 1        | 3.85%   |
| ASRock TRX40 Creator             | 1        | 3.85%   |
| ASRock B450 Gaming-ITX/ac        | 1        | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| MSI MS-7C37          | 2        | 7.69%   |
| ASUS ROG             | 2        | 7.69%   |
| ASUS PRIME           | 2        | 7.69%   |
| MSI MS-7C95          | 1        | 3.85%   |
| MSI MS-7C84          | 1        | 3.85%   |
| MSI MS-7B89          | 1        | 3.85%   |
| MSI MS-7B09          | 1        | 3.85%   |
| HP EliteDesk         | 1        | 3.85%   |
| HARDKERNEL ODROID-H2 | 1        | 3.85%   |
| Gigabyte X570        | 1        | 3.85%   |
| Gigabyte X470        | 1        | 3.85%   |
| Gigabyte H97M-D3H    | 1        | 3.85%   |
| EVGA X299            | 1        | 3.85%   |
| Dell Precision       | 1        | 3.85%   |
| ASUS Z170-P          | 1        | 3.85%   |
| ASUS TUF             | 1        | 3.85%   |
| ASUS PRO-Q77         | 1        | 3.85%   |
| ASUS Pro             | 1        | 3.85%   |
| ASUS P8Z77-V         | 1        | 3.85%   |
| ASUS All             | 1        | 3.85%   |
| ASRock X570          | 1        | 3.85%   |
| ASRock TRX40         | 1        | 3.85%   |
| ASRock B450          | 1        | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 8        | 30.77%  |
| 2020 | 5        | 19.23%  |
| 2018 | 4        | 15.38%  |
| 2016 | 2        | 7.69%   |
| 2015 | 2        | 7.69%   |
| 2014 | 2        | 7.69%   |
| 2021 | 1        | 3.85%   |
| 2017 | 1        | 3.85%   |
| 2012 | 1        | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 26       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 26       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 10       | 38.46%  |
| 32.01-64.0  | 7        | 26.92%  |
| 16.01-24.0  | 5        | 19.23%  |
| 4.01-8.0    | 2        | 7.69%   |
| 24.01-32.0  | 1        | 3.85%   |
| 8.01-16.0   | 1        | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 9        | 34.62%  |
| 4.01-8.0   | 5        | 19.23%  |
| 32.01-64.0 | 4        | 15.38%  |
| 3.01-4.0   | 3        | 11.54%  |
| 16.01-24.0 | 2        | 7.69%   |
| 1.01-2.0   | 2        | 7.69%   |
| 24.01-32.0 | 1        | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 33.33%  |
| 3      | 6        | 22.22%  |
| 1      | 4        | 14.81%  |
| 6      | 3        | 11.11%  |
| 5      | 2        | 7.41%   |
| 8      | 1        | 3.7%    |
| 4      | 1        | 3.7%    |
| 0      | 1        | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 80.77%  |
| Yes       | 5        | 19.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 69.23%  |
| Yes       | 8        | 30.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 65.38%  |
| Yes       | 9        | 34.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 6        | 23.08%  |
| USA         | 3        | 11.54%  |
| Poland      | 3        | 11.54%  |
| UK          | 2        | 7.69%   |
| Russia      | 2        | 7.69%   |
| Austria     | 2        | 7.69%   |
| Ukraine     | 1        | 3.85%   |
| Serbia      | 1        | 3.85%   |
| New Zealand | 1        | 3.85%   |
| Netherlands | 1        | 3.85%   |
| Hungary     | 1        | 3.85%   |
| Denmark     | 1        | 3.85%   |
| Canada      | 1        | 3.85%   |
| Brazil      | 1        | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 2        | 7.14%   |
| Marki             | 2        | 7.14%   |
| Bensheim          | 2        | 7.14%   |
| Wellington        | 1        | 3.57%   |
| Srednyaya Akhtuba | 1        | 3.57%   |
| Southampton       | 1        | 3.57%   |
| Sindelfingen      | 1        | 3.57%   |
| Schaafheim        | 1        | 3.57%   |
| San Gabriel       | 1        | 3.57%   |
| Redwood City      | 1        | 3.57%   |
| Ramenskoye        | 1        | 3.57%   |
| Osasco            | 1        | 3.57%   |
| Numansdorp        | 1        | 3.57%   |
| Montreal          | 1        | 3.57%   |
| Melrose           | 1        | 3.57%   |
| Kuybyshev         | 1        | 3.57%   |
| Kharkiv           | 1        | 3.57%   |
| Karlsruhe         | 1        | 3.57%   |
| Gdansk            | 1        | 3.57%   |
| Frankfurt am Main | 1        | 3.57%   |
| Esbjerg           | 1        | 3.57%   |
| Elsenfeld         | 1        | 3.57%   |
| Budapest          | 1        | 3.57%   |
| Belgrade          | 1        | 3.57%   |
| Andover           | 1        | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 27     | 25%     |
| Seagate             | 6        | 7      | 11.54%  |
| Crucial             | 6        | 7      | 11.54%  |
| WDC                 | 5        | 12     | 9.62%   |
| Kingston            | 5        | 5      | 9.62%   |
| Toshiba             | 4        | 7      | 7.69%   |
| SanDisk             | 4        | 8      | 7.69%   |
| Intel               | 4        | 6      | 7.69%   |
| PLEXTOR             | 1        | 1      | 1.92%   |
| Phison              | 1        | 1      | 1.92%   |
| Lexar               | 1        | 1      | 1.92%   |
| HGST                | 1        | 3      | 1.92%   |
| ASMT                | 1        | 1      | 1.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST3000DM001-1ER166 3TB     | 2        | 2.99%   |
| Samsung SSD 970 EVO Plus 2TB       | 2        | 2.99%   |
| Samsung SSD 970 EVO Plus 1TB       | 2        | 2.99%   |
| Samsung SSD 970 EVO 500GB          | 2        | 2.99%   |
| Samsung SSD 860 QVO 1TB            | 2        | 2.99%   |
| Samsung SSD 860 EVO 2TB            | 2        | 2.99%   |
| Samsung SSD 860 EVO 1TB            | 2        | 2.99%   |
| Crucial CT1000MX500SSD1 1TB        | 2        | 2.99%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1        | 1.49%   |
| WDC WD80EDAZ-11TA3A0 8TB           | 1        | 1.49%   |
| WDC WD40EFRX-68N32N0 4TB           | 1        | 1.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1        | 1.49%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 1.49%   |
| WDC WD10EZEX-00KUWA0 1TB           | 1        | 1.49%   |
| Toshiba TR150 960GB SSD            | 1        | 1.49%   |
| Toshiba HDWL120 2TB                | 1        | 1.49%   |
| Toshiba HDWE160 6TB                | 1        | 1.49%   |
| Toshiba HDWD120 2TB                | 1        | 1.49%   |
| Seagate ST3000VX010-2H916L 3TB     | 1        | 1.49%   |
| Seagate ST3000DM001-1CH166 3TB     | 1        | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1.49%   |
| Seagate ST1000DM003-1CH162 1TB     | 1        | 1.49%   |
| SanDisk Ultra II 960GB SSD         | 1        | 1.49%   |
| SanDisk SSD PLUS 240GB             | 1        | 1.49%   |
| SanDisk SSD PLUS 240 GB            | 1        | 1.49%   |
| SanDisk SSD PLUS 120 GB            | 1        | 1.49%   |
| SanDisk SDSSDHII240G 240GB         | 1        | 1.49%   |
| SanDisk SDSSDA240G 240GB           | 1        | 1.49%   |
| Sandisk NVMe SSD Drive 1TB         | 1        | 1.49%   |
| Samsung SSD 980 PRO 1TB            | 1        | 1.49%   |
| Samsung SSD 970 PRO 512GB          | 1        | 1.49%   |
| Samsung SSD 970 EVO 1TB            | 1        | 1.49%   |
| Samsung SSD 960 EVO 1TB            | 1        | 1.49%   |
| Samsung SSD 860 EVO 500GB          | 1        | 1.49%   |
| Samsung SSD 850 EVO 250GB          | 1        | 1.49%   |
| Samsung SSD 850 EVO 120GB          | 1        | 1.49%   |
| Samsung SSD 840 EVO 250GB          | 1        | 1.49%   |
| Samsung NVMe SSD Drive 500GB       | 1        | 1.49%   |
| Samsung NVMe SSD Drive 1TB         | 1        | 1.49%   |
| Samsung MZVLB256HBHQ-000L7 256GB   | 1        | 1.49%   |
| PLEXTOR PX-512M9PeY 512GB          | 1        | 1.49%   |
| Phison Sabrent 1TB                 | 1        | 1.49%   |
| Lexar 1TB SSD                      | 1        | 1.49%   |
| Kingston SVP200S37A60G 64GB SSD    | 1        | 1.49%   |
| Kingston SUV400S37480G 480GB SSD   | 1        | 1.49%   |
| Kingston SUV300S37A240G 240GB SSD  | 1        | 1.49%   |
| Kingston SA400S37960G 960GB SSD    | 1        | 1.49%   |
| Kingston SA2000M8500G 500GB        | 1        | 1.49%   |
| Intel SSDSC2CT180A3 180GB          | 1        | 1.49%   |
| Intel SSDSC2BW240A4 240GB          | 1        | 1.49%   |
| Intel SSDSC2BW120A4 120GB          | 1        | 1.49%   |
| Intel SSDSA2BW160G3H 160GB         | 1        | 1.49%   |
| HGST HTS721010A9E630 1TB           | 1        | 1.49%   |
| Crucial M4-CT128M4SSD2 128GB       | 1        | 1.49%   |
| Crucial M4-CT064M4SSD1 64GB        | 1        | 1.49%   |
| Crucial CT525MX300SSD1 528GB       | 1        | 1.49%   |
| Crucial CT250BX100SSD1 250GB       | 1        | 1.49%   |
| Crucial CT2000BX500SSD1 2TB        | 1        | 1.49%   |
| ASMT 2115 1TB                      | 1        | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 6        | 7      | 37.5%   |
| WDC     | 5        | 10     | 31.25%  |
| Toshiba | 3        | 6      | 18.75%  |
| HGST    | 1        | 3      | 6.25%   |
| ASMT    | 1        | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 12     | 26.92%  |
| Crucial             | 6        | 7      | 23.08%  |
| Kingston            | 4        | 4      | 15.38%  |
| Intel               | 4        | 6      | 15.38%  |
| SanDisk             | 3        | 6      | 11.54%  |
| WDC                 | 1        | 2      | 3.85%   |
| Toshiba             | 1        | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 21       | 38     | 44.68%  |
| NVMe | 14       | 21     | 29.79%  |
| HDD  | 12       | 27     | 25.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 64     | 61.54%  |
| NVMe | 14       | 21     | 35.9%   |
| SAS  | 1        | 1      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 24     | 38.46%  |
| 0.51-1.0   | 12       | 20     | 30.77%  |
| 1.01-2.0   | 5        | 8      | 12.82%  |
| 2.01-3.0   | 4        | 5      | 10.26%  |
| 4.01-10.0  | 2        | 6      | 5.13%   |
| 3.01-4.0   | 1        | 2      | 2.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 65.38%  |
| 1-20       | 3        | 11.54%  |
| 501-1000   | 3        | 11.54%  |
| 2001-3000  | 1        | 3.85%   |
| 101-250    | 1        | 3.85%   |
| 1001-2000  | 1        | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| Unknown   | 17       | 65.38%  |
| 1-20      | 5        | 19.23%  |
| 251-500   | 1        | 3.85%   |
| 101-250   | 1        | 3.85%   |
| 1001-2000 | 1        | 3.85%   |
| 501-1000  | 1        | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 970 EVO 1TB | 1        | 1      | 33.33%  |
| Intel SSDSC2BW240A4 240GB           | 1        | 1      | 33.33%  |
| ASMT 2115 1TB                       | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 33.33%  |
| Intel               | 1        | 1      | 33.33%  |
| ASMT                | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| ASMT   | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 1        | 1      | 33.33%  |
| SSD  | 1        | 1      | 33.33%  |
| HDD  | 1        | 1      | 33.33%  |

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
| Works    | 24       | 78     | 85.71%  |
| Detected | 2        | 5      | 7.14%   |
| Malfunc  | 2        | 3      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 14       | 31.82%  |
| Intel                        | 12       | 27.27%  |
| Samsung Electronics          | 9        | 20.45%  |
| Kingston Technology Company  | 2        | 4.55%   |
| ASMedia Technology           | 2        | 4.55%   |
| Shenzhen Longsys Electronics | 1        | 2.27%   |
| Sandisk                      | 1        | 2.27%   |
| Phison Electronics           | 1        | 2.27%   |
| LSI Logic / Symbios Logic    | 1        | 2.27%   |
| Lite-On Technology           | 1        | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 10       | 20%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 8        | 16%     |
| AMD 500 Series Chipset SATA Controller                                        | 3        | 6%      |
| AMD 400 Series Chipset SATA Controller                                        | 3        | 6%      |
| Kingston Company A2000 NVMe SSD                                               | 2        | 4%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 4%      |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 2        | 4%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2        | 4%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2        | 4%      |
| ASMedia ASM1062 Serial ATA Controller                                         | 2        | 4%      |
| Shenzhen Longsys Electronics Non-Volatile memory controller                   | 1        | 2%      |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1        | 2%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 2%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 2%      |
| Phison E12 NVMe Controller                                                    | 1        | 2%      |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]       | 1        | 2%      |
| Lite-On Non-Volatile memory controller                                        | 1        | 2%      |
| Intel Comet Lake SATA AHCI Controller                                         | 1        | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1        | 2%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 1        | 2%      |
| Intel C610/X99 series chipset IDE-r Controller                                | 1        | 2%      |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1        | 2%      |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 2%      |
| AMD X399 Series Chipset SATA Controller                                       | 1        | 2%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 60.47%  |
| NVMe | 15       | 34.88%  |
| SAS  | 1        | 2.33%   |
| IDE  | 1        | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 14       | 53.85%  |
| Intel  | 12       | 46.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 3        | 11.54%  |
| AMD Ryzen 7 3800X 8-Core Processor             | 2        | 7.69%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 7.69%   |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1        | 3.85%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1        | 3.85%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1        | 3.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 3.85%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1        | 3.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 3.85%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 3.85%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 3.85%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 3.85%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1        | 3.85%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 3.85%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1        | 3.85%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 3.85%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 3.85%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 3.85%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 3.85%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 3.85%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 3.85%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 6        | 23.08%  |
| Intel Core i5          | 4        | 15.38%  |
| AMD Ryzen 7            | 4        | 15.38%  |
| Intel Core i7          | 3        | 11.54%  |
| Intel Xeon             | 2        | 7.69%   |
| AMD Ryzen Threadripper | 2        | 7.69%   |
| AMD Ryzen 9            | 2        | 7.69%   |
| Intel Core i9          | 1        | 3.85%   |
| Intel Core i3          | 1        | 3.85%   |
| Intel Celeron          | 1        | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 8        | 30.77%  |
| 4      | 5        | 19.23%  |
| 8      | 4        | 15.38%  |
| 12     | 2        | 7.69%   |
| 10     | 2        | 7.69%   |
| 2      | 2        | 7.69%   |
| 32     | 1        | 3.85%   |
| 24     | 1        | 3.85%   |
| 16     | 1        | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 96.15%  |
| 2      | 1        | 3.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 84.62%  |
| 1      | 4        | 15.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 26       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 5        | 18.52%  |
| Unknown    | 5        | 18.52%  |
| 0x08701013 | 3        | 11.11%  |
| 0x506e3    | 2        | 7.41%   |
| 0x306a9    | 2        | 7.41%   |
| 0x906ea    | 1        | 3.7%    |
| 0x906e9    | 1        | 3.7%    |
| 0x406f1    | 1        | 3.7%    |
| 0x306f2    | 1        | 3.7%    |
| 0x306c3    | 1        | 3.7%    |
| 0x0a201204 | 1        | 3.7%    |
| 0x0a201009 | 1        | 3.7%    |
| 0x08301025 | 1        | 3.7%    |
| 0x0800820d | 1        | 3.7%    |
| 0x08001137 | 1        | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 10       | 38.46%  |
| Skylake       | 3        | 11.54%  |
| Zen 3         | 2        | 7.69%   |
| KabyLake      | 2        | 7.69%   |
| IvyBridge     | 2        | 7.69%   |
| Haswell       | 2        | 7.69%   |
| Zen+          | 1        | 3.85%   |
| Zen           | 1        | 3.85%   |
| Goldmont plus | 1        | 3.85%   |
| CometLake     | 1        | 3.85%   |
| Broadwell     | 1        | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 15       | 48.39%  |
| AMD    | 9        | 29.03%  |
| Intel  | 7        | 22.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 5        | 16.13%  |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 2        | 6.45%   |
| Nvidia GK104 [GeForce GTX 760]                                   | 2        | 6.45%   |
| Intel HD Graphics 530                                            | 2        | 6.45%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 2        | 6.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 2        | 6.45%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                               | 1        | 3.23%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                            | 1        | 3.23%   |
| Nvidia TU106 [GeForce RTX 2070]                                  | 1        | 3.23%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                            | 1        | 3.23%   |
| Nvidia GP104 [GeForce GTX 1080]                                  | 1        | 3.23%   |
| Nvidia GP104 [GeForce GTX 1070]                                  | 1        | 3.23%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                               | 1        | 3.23%   |
| Nvidia GM206 [GeForce GTX 960]                                   | 1        | 3.23%   |
| Nvidia GM204 [GeForce GTX 970]                                   | 1        | 3.23%   |
| Nvidia GK107 [NVS 510]                                           | 1        | 3.23%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                | 1        | 3.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 3.23%   |
| Intel UHD P630 Graphics                                          | 1        | 3.23%   |
| Intel HD Graphics 630                                            | 1        | 3.23%   |
| Intel GeminiLake [UHD Graphics 600]                              | 1        | 3.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                        | 1        | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 11       | 42.31%  |
| 1 x AMD        | 6        | 23.08%  |
| 1 x Intel      | 5        | 19.23%  |
| AMD + Nvidia   | 3        | 11.54%  |
| Intel + Nvidia | 1        | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 15       | 57.69%  |
| Proprietary | 10       | 38.46%  |
| Unknown     | 1        | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 70.37%  |
| 7.01-8.0   | 7        | 25.93%  |
| 1.01-2.0   | 1        | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 8        | 29.63%  |
| Dell                 | 8        | 29.63%  |
| Acer                 | 3        | 11.11%  |
| Ancor Communications | 2        | 7.41%   |
| Unknown (AAA)        | 1        | 3.7%    |
| MPI                  | 1        | 3.7%    |
| Iiyama               | 1        | 3.7%    |
| HVR                  | 1        | 3.7%    |
| BenQ                 | 1        | 3.7%    |
| AOC                  | 1        | 3.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 2        | 6.9%    |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2        | 6.9%    |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2        | 6.9%    |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1        | 3.45%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                      | 1        | 3.45%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch               | 1        | 3.45%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 1        | 3.45%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch              | 1        | 3.45%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 1        | 3.45%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 3.45%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1        | 3.45%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 1        | 3.45%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 1        | 3.45%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 1        | 3.45%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                     | 1        | 3.45%   |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                     | 1        | 3.45%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1        | 3.45%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                      | 1        | 3.45%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 1        | 3.45%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                     | 1        | 3.45%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                     | 1        | 3.45%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 3.45%   |
| AOC 2280W AOC2280 1920x1080 477x268mm 21.5-inch                       | 1        | 3.45%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 1        | 3.45%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 1        | 3.45%   |
| Acer AL1717 ACRAD60 1280x1024 338x270mm 17.0-inch                     | 1        | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 8        | 32%     |
| 3840x2160 (4K)   | 7        | 28%     |
| 2560x1080        | 4        | 16%     |
| 2560x1440 (QHD)  | 3        | 12%     |
| 2160x1200        | 1        | 4%      |
| 1280x720 (HD)    | 1        | 4%      |
| 1280x1024 (SXGA) | 1        | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 26.92%  |
| 23      | 5        | 19.23%  |
| 34      | 4        | 15.38%  |
| 24      | 3        | 11.54%  |
| 21      | 2        | 7.69%   |
| 31      | 1        | 3.85%   |
| 25      | 1        | 3.85%   |
| 17      | 1        | 3.85%   |
| 8       | 1        | 3.85%   |
| Unknown | 1        | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 58.33%  |
| 701-800     | 4        | 16.67%  |
| 401-500     | 2        | 8.33%   |
| 601-700     | 1        | 4.17%   |
| 301-350     | 1        | 4.17%   |
| 101-200     | 1        | 4.17%   |
| Unknown     | 1        | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 14       | 63.64%  |
| 21/9  | 4        | 18.18%  |
| 16/10 | 2        | 9.09%   |
| 5/4   | 1        | 4.55%   |
| 4/3   | 1        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 29.63%  |
| 301-350        | 7        | 25.93%  |
| 351-500        | 5        | 18.52%  |
| 251-300        | 2        | 7.41%   |
| 151-200        | 2        | 7.41%   |
| 1-40           | 1        | 3.7%    |
| 141-150        | 1        | 3.7%    |
| Unknown        | 1        | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 52%     |
| 161-240 | 6        | 24%     |
| 101-120 | 4        | 16%     |
| 121-160 | 1        | 4%      |
| Unknown | 1        | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 50%     |
| 0     | 6        | 23.08%  |
| 2     | 5        | 19.23%  |
| 3     | 2        | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 17       | 42.5%   |
| Realtek Semiconductor | 16       | 40%     |
| Aquantia              | 2        | 5%      |
| TP-Link               | 1        | 2.5%    |
| Texas Instruments     | 1        | 2.5%    |
| Qualcomm Atheros      | 1        | 2.5%    |
| Oculus VR             | 1        | 2.5%    |
| Microsoft             | 1        | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 27.91%  |
| Intel Wi-Fi 6 AX200                                               | 5        | 11.63%  |
| Intel I211 Gigabit Network Connection                             | 5        | 11.63%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 6.98%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 4.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 2.33%   |
| Texas Instruments CC2538 USB CDC                                  | 1        | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 2.33%   |
| Oculus VR Rift S                                                  | 1        | 2.33%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2.33%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.33%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.33%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.33%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.33%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.33%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Intel     | 6        | 75%     |
| TP-Link   | 1        | 12.5%   |
| Microsoft | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 5        | 62.5%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1        | 12.5%   |
| Microsoft Xbox 360 Wireless Adapter                        | 1        | 12.5%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 48.48%  |
| Intel                 | 14       | 42.42%  |
| Aquantia              | 2        | 6.06%   |
| Qualcomm Atheros      | 1        | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 36.36%  |
| Intel I211 Gigabit Network Connection                             | 5        | 15.15%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 9.09%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 6.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 3.03%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.03%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.03%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 3.03%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.03%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.03%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 72.22%  |
| WiFi     | 8        | 22.22%  |
| Modem    | 2        | 5.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 85.19%  |
| WiFi     | 4        | 14.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 57.69%  |
| 2     | 9        | 34.62%  |
| 3     | 1        | 3.85%   |
| 0     | 1        | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 73.08%  |
| Yes  | 7        | 26.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 4        | 40%     |
| ASUSTek Computer         | 3        | 30%     |
| Cambridge Silicon Radio  | 2        | 20%     |
| HTC (High Tech Computer) | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 3        | 30%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 20%     |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 20%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 10%     |
| HTC (High Tech Computer) BCM920703 Bluetooth 4.1    | 1        | 10%     |
| ASUS ASUS USB-BT500                                 | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Nvidia                               | 15       | 28.3%   |
| AMD                                  | 15       | 28.3%   |
| Intel                                | 12       | 22.64%  |
| Unknown                              | 1        | 1.89%   |
| Thomann                              | 1        | 1.89%   |
| Thesycon Systemsoftware & Consulting | 1        | 1.89%   |
| Texas Instruments                    | 1        | 1.89%   |
| Sony                                 | 1        | 1.89%   |
| Sennheiser Communications            | 1        | 1.89%   |
| PreSonus Audio Electronics           | 1        | 1.89%   |
| GYROCOM C&C                          | 1        | 1.89%   |
| Creative Technology                  | 1        | 1.89%   |
| Creative Labs                        | 1        | 1.89%   |
| C-Media Electronics                  | 1        | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 12       | 19.67%  |
| AMD Navi 10 HDMI Audio                                              | 5        | 8.2%    |
| Nvidia GK104 HDMI Audio Controller                                  | 3        | 4.92%   |
| Nvidia TU116 High Definition Audio Controller                       | 2        | 3.28%   |
| Nvidia TU106 High Definition Audio Controller                       | 2        | 3.28%   |
| Nvidia GP106 High Definition Audio Controller                       | 2        | 3.28%   |
| Nvidia GP104 High Definition Audio Controller                       | 2        | 3.28%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2        | 3.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2        | 3.28%   |
| Intel 200 Series PCH HD Audio                                       | 2        | 3.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2        | 3.28%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2        | 3.28%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 2        | 3.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 2        | 3.28%   |
| Unknown USB Audio                                                   | 1        | 1.64%   |
| Thomann SC450USB                                                    | 1        | 1.64%   |
| Thesycon Systemsoftware & Consulting D30 Pro                        | 1        | 1.64%   |
| Texas Instruments PCM2902 Audio Codec                               | 1        | 1.64%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1        | 1.64%   |
| Sennheiser Communications Headset [PC 8]                            | 1        | 1.64%   |
| PreSonus Audio Electronics AudioBox                                 | 1        | 1.64%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1        | 1.64%   |
| Nvidia GM206 High Definition Audio Controller                       | 1        | 1.64%   |
| Nvidia GM204 High Definition Audio Controller                       | 1        | 1.64%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1        | 1.64%   |
| Intel Comet Lake PCH cAVS                                           | 1        | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1        | 1.64%   |
| Intel Cannon Lake PCH cAVS                                          | 1        | 1.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1        | 1.64%   |
| GYROCOM C&C Fiio E10                                                | 1        | 1.64%   |
| Creative Technology Sound BlasterX G1                               | 1        | 1.64%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]          | 1        | 1.64%   |
| C-Media Electronics USB Advanced Audio Device                       | 1        | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 7        | 24.14%  |
| Corsair             | 7        | 24.14%  |
| G.Skill             | 4        | 13.79%  |
| Crucial             | 3        | 10.34%  |
| Samsung Electronics | 2        | 6.9%    |
| Micron Technology   | 2        | 6.9%    |
| Unknown (ABCD)      | 1        | 3.45%   |
| Unknown             | 1        | 3.45%   |
| Strontium           | 1        | 3.45%   |
| GOODRAM             | 1        | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s      | 2        | 6.06%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 2        | 6.06%   |
| Kingston RAM KHX2400C15/16G 16384MB DIMM DDR4 3334MT/s         | 2        | 6.06%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 2        | 6.06%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s         | 2        | 6.06%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                  | 1        | 3.03%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 3.03%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s             | 1        | 3.03%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1        | 3.03%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s           | 1        | 3.03%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s           | 1        | 3.03%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s           | 1        | 3.03%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s           | 1        | 3.03%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1        | 3.03%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s            | 1        | 3.03%   |
| Kingston RAM 9965745-021.A00G 32GB DIMM DDR4 2933MT/s          | 1        | 3.03%   |
| GOODRAM RAM GR1600D364L9/4G 4096MB DIMM DDR3 1333MT/s          | 1        | 3.03%   |
| GOODRAM RAM GR1600D364L11/4G 4GB DIMM DDR3 1600MT/s            | 1        | 3.03%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 1        | 3.03%   |
| G.Skill RAM F3-1600C9-8GSR 8GB DIMM DDR3 1333MT/s              | 1        | 3.03%   |
| Crucial RAM BLS4G3D1609DS1S00. 4096MB DIMM DDR3 1600MT/s       | 1        | 3.03%   |
| Crucial RAM BLS16G4D32AESE.M16FE 16GB DIMM DDR4 3733MT/s       | 1        | 3.03%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16384MB DIMM DDR4 3200MT/s    | 1        | 3.03%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 1        | 3.03%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s          | 1        | 3.03%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s      | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2D3600C18 8192MB DIMM DDR4 3600MT/s       | 1        | 3.03%   |
| Corsair RAM CMD64GX4M4A2666C15 16384MB DIMM DDR4 2133MT/s      | 1        | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 21       | 84%     |
| DDR3   | 3        | 12%     |
| LPDDR4 | 1        | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 23       | 92%     |
| SODIMM | 1        | 4%      |
| RIMM   | 1        | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 11       | 40.74%  |
| 8192  | 9        | 33.33%  |
| 32768 | 5        | 18.52%  |
| 4096  | 2        | 7.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 9        | 30%     |
| 2133  | 4        | 13.33%  |
| 3600  | 3        | 10%     |
| 1600  | 3        | 10%     |
| 3334  | 2        | 6.67%   |
| 2400  | 2        | 6.67%   |
| 3733  | 1        | 3.33%   |
| 3533  | 1        | 3.33%   |
| 3466  | 1        | 3.33%   |
| 3400  | 1        | 3.33%   |
| 3266  | 1        | 3.33%   |
| 2933  | 1        | 3.33%   |
| 1333  | 1        | 3.33%   |

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


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Logitech     | 4        | 50%     |
| MacroSilicon | 2        | 25%     |
| Microdia     | 1        | 12.5%   |
| Apple        | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| MacroSilicon MiraBox Capture | 2        | 25%     |
| Microdia Camera              | 1        | 12.5%   |
| Logitech Webcam C930e        | 1        | 12.5%   |
| Logitech Webcam C270         | 1        | 12.5%   |
| Logitech HD Pro Webcam C920  | 1        | 12.5%   |
| Logitech C930c               | 1        | 12.5%   |
| Apple iPhone 5/5C/5S/6/SE    | 1        | 12.5%   |

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
| 0     | 20       | 76.92%  |
| 1     | 5        | 19.23%  |
| 2     | 1        | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 50%     |
| Net/wireless     | 1        | 16.67%  |
| Graphics card    | 1        | 16.67%  |
| Camera           | 1        | 16.67%  |

