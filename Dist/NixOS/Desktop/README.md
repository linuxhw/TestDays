NixOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

Total: 43

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | H97I-PLUS                   | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| MSI        | MEG X570 UNIFY              | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek    | ROG STRIX Z390-F GAMING     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| MSI        | MEG X570 UNIFY              | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI        | MEG X570 UNIFY              | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| ASUSTek    | PRIME A520M-K               | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte   | B550I AORUS PRO AX          | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
| ASUSTek    | PRIME X570-P                | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| Acer       | Nitro N50-610               | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| ASUSTek    | P8Q77-M                     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| Gigabyte   | X470 AORUS ULTRA GAMING-... | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| MSI        | B450M MORTAR MAX            | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| ASUSTek    | P8Z77-V LK                  | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek    | P8Z77-V LK                  | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA       | X299 FTW K                  | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell       | 0KJCC5 A00                  | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI        | X399 SLI PLUS               | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
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
| Hardkernel | ODROID-H2                   | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| ASUSTek    | TUF Gaming X570-PLUS        | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
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
| NixOS 22.05                      | 9        | 26.47%  |
| NixOS 21.11                      | 7        | 20.59%  |
| NixOS                            | 3        | 8.82%   |
| NixOS 21.05pre-git               | 2        | 5.88%   |
| NixOS 21.11.20210528.540dccb     | 1        | 2.94%   |
| NixOS 21.05.993.93963c27b93      | 1        | 2.94%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1        | 2.94%   |
| NixOS 21.05.20210929.ee90403     | 1        | 2.94%   |
| NixOS 21.05.20210430.c8dff32     | 1        | 2.94%   |
| NixOS 21.05.20210224.f6b5bfd     | 1        | 2.94%   |
| NixOS 21.05.1471.a7512bb64b1     | 1        | 2.94%   |
| NixOS 21.03pre246062.420f89ceb26 | 1        | 2.94%   |
| NixOS 21.03.git.b4349c13a6d      | 1        | 2.94%   |
| NixOS 21.03.20201007.420f89c     | 1        | 2.94%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1        | 2.94%   |
| NixOS 20.09pre-git               | 1        | 2.94%   |
| NixOS 20.09.git.4a361b06a93      | 1        | 2.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| NixOS | 33       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.8.1-zen1             | 2        | 5.88%   |
| 5.15.47                | 2        | 5.88%   |
| 5.10.102               | 2        | 5.88%   |
| 5.8.10                 | 1        | 2.94%   |
| 5.7.19                 | 1        | 2.94%   |
| 5.4.94                 | 1        | 2.94%   |
| 5.4.72                 | 1        | 2.94%   |
| 5.4.69                 | 1        | 2.94%   |
| 5.4.50                 | 1        | 2.94%   |
| 5.4.47                 | 1        | 2.94%   |
| 5.17.1                 | 1        | 2.94%   |
| 5.16.8-zen1            | 1        | 2.94%   |
| 5.15.7                 | 1        | 2.94%   |
| 5.15.43                | 1        | 2.94%   |
| 5.15.39                | 1        | 2.94%   |
| 5.15.34                | 1        | 2.94%   |
| 5.15.26                | 1        | 2.94%   |
| 5.15.25                | 1        | 2.94%   |
| 5.15.18                | 1        | 2.94%   |
| 5.14.16-lqx1           | 1        | 2.94%   |
| 5.13.2                 | 1        | 2.94%   |
| 5.12.15                | 1        | 2.94%   |
| 5.11.16-zen1           | 1        | 2.94%   |
| 5.11.16-xanmod1-cacule | 1        | 2.94%   |
| 5.10.99                | 1        | 2.94%   |
| 5.10.96                | 1        | 2.94%   |
| 5.10.62                | 1        | 2.94%   |
| 5.10.52                | 1        | 2.94%   |
| 5.10.43                | 1        | 2.94%   |
| 5.10.35                | 1        | 2.94%   |
| 5.10.17                | 1        | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.8.1    | 2        | 5.88%   |
| 5.15.47  | 2        | 5.88%   |
| 5.11.16  | 2        | 5.88%   |
| 5.10.102 | 2        | 5.88%   |
| 5.8.10   | 1        | 2.94%   |
| 5.7.19   | 1        | 2.94%   |
| 5.4.94   | 1        | 2.94%   |
| 5.4.72   | 1        | 2.94%   |
| 5.4.69   | 1        | 2.94%   |
| 5.4.50   | 1        | 2.94%   |
| 5.4.47   | 1        | 2.94%   |
| 5.17.1   | 1        | 2.94%   |
| 5.16.8   | 1        | 2.94%   |
| 5.15.7   | 1        | 2.94%   |
| 5.15.43  | 1        | 2.94%   |
| 5.15.39  | 1        | 2.94%   |
| 5.15.34  | 1        | 2.94%   |
| 5.15.26  | 1        | 2.94%   |
| 5.15.25  | 1        | 2.94%   |
| 5.15.18  | 1        | 2.94%   |
| 5.14.16  | 1        | 2.94%   |
| 5.13.2   | 1        | 2.94%   |
| 5.12.15  | 1        | 2.94%   |
| 5.10.99  | 1        | 2.94%   |
| 5.10.96  | 1        | 2.94%   |
| 5.10.62  | 1        | 2.94%   |
| 5.10.52  | 1        | 2.94%   |
| 5.10.43  | 1        | 2.94%   |
| 5.10.35  | 1        | 2.94%   |
| 5.10.17  | 1        | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 9        | 26.47%  |
| 5.10    | 9        | 26.47%  |
| 5.4     | 5        | 14.71%  |
| 5.8     | 3        | 8.82%   |
| 5.11    | 2        | 5.88%   |
| 5.7     | 1        | 2.94%   |
| 5.17    | 1        | 2.94%   |
| 5.16    | 1        | 2.94%   |
| 5.14    | 1        | 2.94%   |
| 5.13    | 1        | 2.94%   |
| 5.12    | 1        | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 33       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 24       | 72.73%  |
| KDE          | 3        | 9.09%   |
| XFCE         | 2        | 6.06%   |
| sway         | 2        | 6.06%   |
| none+awesome | 1        | 3.03%   |
| GNOME        | 1        | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 66.67%  |
| X11     | 7        | 21.21%  |
| Wayland | 3        | 9.09%   |
| Tty     | 1        | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 78.79%  |
| LightDM | 4        | 12.12%  |
| SDDM    | 2        | 6.06%   |
| GDM     | 1        | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 51.52%  |
| en_US   | 11       | 33.33%  |
| en_GB   | 2        | 6.06%   |
| pt_BR   | 1        | 3.03%   |
| en_DK   | 1        | 3.03%   |
| de_CH   | 1        | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 27       | 79.41%  |
| BIOS | 7        | 20.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 15       | 45.45%  |
| Tmpfs   | 5        | 15.15%  |
| Zfs     | 3        | 9.09%   |
| Xfs     | 3        | 9.09%   |
| Btrfs   | 3        | 9.09%   |
| Unknown | 3        | 9.09%   |
| Ext2    | 1        | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 31       | 93.94%  |
| Unknown | 2        | 6.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 75.76%  |
| Yes       | 8        | 24.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 57.58%  |
| No        | 14       | 42.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 14       | 42.42%  |
| MSI                 | 7        | 21.21%  |
| Gigabyte Technology | 4        | 12.12%  |
| ASRock              | 3        | 9.09%   |
| Hewlett-Packard     | 1        | 3.03%   |
| Hardkernel          | 1        | 3.03%   |
| EVGA                | 1        | 3.03%   |
| Dell                | 1        | 3.03%   |
| Acer                | 1        | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7C37                      | 2        | 6.06%   |
| MSI MS-7C95                      | 1        | 3.03%   |
| MSI MS-7C84                      | 1        | 3.03%   |
| MSI MS-7C35                      | 1        | 3.03%   |
| MSI MS-7B89                      | 1        | 3.03%   |
| MSI MS-7B09                      | 1        | 3.03%   |
| HP EliteDesk 800 G2 DM 35W       | 1        | 3.03%   |
| Hardkernel ODROID-H2             | 1        | 3.03%   |
| Gigabyte X570 AORUS ELITE        | 1        | 3.03%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 3.03%   |
| Gigabyte H97M-D3H                | 1        | 3.03%   |
| Gigabyte B550I AORUS PRO AX      | 1        | 3.03%   |
| EVGA X299 FTW K                  | 1        | 3.03%   |
| Dell Precision Tower 7810        | 1        | 3.03%   |
| ASUS Z170-P                      | 1        | 3.03%   |
| ASUS TUF Gaming X570-PLUS        | 1        | 3.03%   |
| ASUS ROG STRIX Z390-F GAMING     | 1        | 3.03%   |
| ASUS ROG STRIX B550-I GAMING     | 1        | 3.03%   |
| ASUS ROG STRIX B550-F GAMING     | 1        | 3.03%   |
| ASUS PRO602617                   | 1        | 3.03%   |
| ASUS PRO-Q77 IU                  | 1        | 3.03%   |
| ASUS Pro WS W480-ACE             | 1        | 3.03%   |
| ASUS PRIME Z390-A                | 1        | 3.03%   |
| ASUS PRIME Z270-K                | 1        | 3.03%   |
| ASUS PRIME X570-P                | 1        | 3.03%   |
| ASUS PRIME A520M-K               | 1        | 3.03%   |
| ASUS P8Z77-V LK                  | 1        | 3.03%   |
| ASUS All Series                  | 1        | 3.03%   |
| ASRock X570 Taichi               | 1        | 3.03%   |
| ASRock TRX40 Creator             | 1        | 3.03%   |
| ASRock B450 Gaming-ITX/ac        | 1        | 3.03%   |
| Acer Nitro N50-610               | 1        | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 4        | 12.12%  |
| ASUS ROG             | 3        | 9.09%   |
| MSI MS-7C37          | 2        | 6.06%   |
| MSI MS-7C95          | 1        | 3.03%   |
| MSI MS-7C84          | 1        | 3.03%   |
| MSI MS-7C35          | 1        | 3.03%   |
| MSI MS-7B89          | 1        | 3.03%   |
| MSI MS-7B09          | 1        | 3.03%   |
| HP EliteDesk         | 1        | 3.03%   |
| Hardkernel ODROID-H2 | 1        | 3.03%   |
| Gigabyte X570        | 1        | 3.03%   |
| Gigabyte X470        | 1        | 3.03%   |
| Gigabyte H97M-D3H    | 1        | 3.03%   |
| Gigabyte B550I       | 1        | 3.03%   |
| EVGA X299            | 1        | 3.03%   |
| Dell Precision       | 1        | 3.03%   |
| ASUS Z170-P          | 1        | 3.03%   |
| ASUS TUF             | 1        | 3.03%   |
| ASUS PRO602617       | 1        | 3.03%   |
| ASUS PRO-Q77         | 1        | 3.03%   |
| ASUS Pro             | 1        | 3.03%   |
| ASUS P8Z77-V         | 1        | 3.03%   |
| ASUS All             | 1        | 3.03%   |
| ASRock X570          | 1        | 3.03%   |
| ASRock TRX40         | 1        | 3.03%   |
| ASRock B450          | 1        | 3.03%   |
| Acer Nitro           | 1        | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 11       | 33.33%  |
| 2020 | 8        | 24.24%  |
| 2018 | 5        | 15.15%  |
| 2016 | 3        | 9.09%   |
| 2015 | 2        | 6.06%   |
| 2014 | 2        | 6.06%   |
| 2017 | 1        | 3.03%   |
| 2012 | 1        | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 33       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 33       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 33       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 12       | 36.36%  |
| 32.01-64.0  | 10       | 30.3%   |
| 16.01-24.0  | 6        | 18.18%  |
| 4.01-8.0    | 2        | 6.06%   |
| 24.01-32.0  | 2        | 6.06%   |
| 8.01-16.0   | 1        | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 10       | 30.3%   |
| 4.01-8.0   | 8        | 24.24%  |
| 32.01-64.0 | 4        | 12.12%  |
| 3.01-4.0   | 4        | 12.12%  |
| 16.01-24.0 | 3        | 9.09%   |
| 1.01-2.0   | 2        | 6.06%   |
| 24.01-32.0 | 1        | 3.03%   |
| 2.01-3.0   | 1        | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 11       | 32.35%  |
| 3      | 9        | 26.47%  |
| 1      | 6        | 17.65%  |
| 6      | 3        | 8.82%   |
| 5      | 2        | 5.88%   |
| 8      | 1        | 2.94%   |
| 4      | 1        | 2.94%   |
| 0      | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 81.82%  |
| Yes       | 6        | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 66.67%  |
| Yes       | 11       | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 57.58%  |
| Yes       | 14       | 42.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 8        | 24.24%  |
| Germany     | 6        | 18.18%  |
| UK          | 3        | 9.09%   |
| Poland      | 3        | 9.09%   |
| Russia      | 2        | 6.06%   |
| Canada      | 2        | 6.06%   |
| Austria     | 2        | 6.06%   |
| Ukraine     | 1        | 3.03%   |
| Switzerland | 1        | 3.03%   |
| Serbia      | 1        | 3.03%   |
| New Zealand | 1        | 3.03%   |
| Hungary     | 1        | 3.03%   |
| Denmark     | 1        | 3.03%   |
| Brazil      | 1        | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 2        | 6.06%   |
| Schaafheim        | 2        | 6.06%   |
| Plymouth          | 2        | 6.06%   |
| Marki             | 2        | 6.06%   |
| Darmstadt         | 2        | 6.06%   |
| Wellington        | 1        | 3.03%   |
| Székesfehérvár | 1        | 3.03%   |
| Southampton       | 1        | 3.03%   |
| South Deerfield   | 1        | 3.03%   |
| Sindelfingen      | 1        | 3.03%   |
| San Gabriel       | 1        | 3.03%   |
| Richardson        | 1        | 3.03%   |
| Redwood City      | 1        | 3.03%   |
| Ramenskoye        | 1        | 3.03%   |
| Osasco            | 1        | 3.03%   |
| Oakville          | 1        | 3.03%   |
| Montreal          | 1        | 3.03%   |
| Melrose           | 1        | 3.03%   |
| Kuybyshev         | 1        | 3.03%   |
| Kharkiv           | 1        | 3.03%   |
| Karlsruhe         | 1        | 3.03%   |
| Gdansk            | 1        | 3.03%   |
| Esbjerg           | 1        | 3.03%   |
| Dietikon          | 1        | 3.03%   |
| Didcot            | 1        | 3.03%   |
| Belgrade          | 1        | 3.03%   |
| Austin            | 1        | 3.03%   |
| Andover           | 1        | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 34     | 28.13%  |
| Seagate             | 8        | 10     | 12.5%   |
| WDC                 | 6        | 13     | 9.38%   |
| Crucial             | 6        | 7      | 9.38%   |
| Toshiba             | 5        | 8      | 7.81%   |
| SanDisk             | 5        | 9      | 7.81%   |
| Kingston            | 5        | 5      | 7.81%   |
| Intel               | 4        | 6      | 6.25%   |
| Plextor             | 1        | 1      | 1.56%   |
| Phison Electronics  | 1        | 2      | 1.56%   |
| Phison              | 1        | 1      | 1.56%   |
| Lexar               | 1        | 1      | 1.56%   |
| HGST                | 1        | 3      | 1.56%   |
| China               | 1        | 1      | 1.56%   |
| ASMT                | 1        | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung SSD 970 EVO Plus 2TB           | 3        | 3.7%    |
| Samsung SSD 860 EVO 1TB                | 3        | 3.7%    |
| Seagate ST3000DM001-1ER166 3TB         | 2        | 2.47%   |
| SanDisk SSD PLUS 240GB                 | 2        | 2.47%   |
| Samsung SSD 980 PRO 1TB                | 2        | 2.47%   |
| Samsung SSD 970 EVO Plus 1TB           | 2        | 2.47%   |
| Samsung SSD 970 EVO 500GB              | 2        | 2.47%   |
| Samsung SSD 970 EVO 1TB                | 2        | 2.47%   |
| Samsung SSD 860 QVO 1TB                | 2        | 2.47%   |
| Samsung SSD 860 EVO 500GB              | 2        | 2.47%   |
| Samsung SSD 860 EVO 2TB                | 2        | 2.47%   |
| Samsung NVMe SSD Drive 1TB             | 2        | 2.47%   |
| Crucial CT1000MX500SSD1 1TB            | 2        | 2.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 1        | 1.23%   |
| WDC WD80EDAZ-11TA3A0 8TB               | 1        | 1.23%   |
| WDC WD40EFRX-68N32N0 4TB               | 1        | 1.23%   |
| WDC WD3200BPVT-22JJ5T0 320GB           | 1        | 1.23%   |
| WDC WD10EZEX-21WN4A0 1TB               | 1        | 1.23%   |
| WDC WD10EZEX-00RKKA0 1TB               | 1        | 1.23%   |
| WDC WD10EZEX-00KUWA0 1TB               | 1        | 1.23%   |
| Toshiba TR150 960GB SSD                | 1        | 1.23%   |
| Toshiba HDWL120 2TB                    | 1        | 1.23%   |
| Toshiba HDWE160 6TB                    | 1        | 1.23%   |
| Toshiba HDWD130 3TB                    | 1        | 1.23%   |
| Toshiba HDWD120 2TB                    | 1        | 1.23%   |
| Seagate ST4000DM004-2CV104 4TB         | 1        | 1.23%   |
| Seagate ST3000VX010-2H916L 3TB         | 1        | 1.23%   |
| Seagate ST3000DM001-1CH166 3TB         | 1        | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1        | 1.23%   |
| Seagate ST1000DM003-1CH162 1TB         | 1        | 1.23%   |
| Seagate Backup+ Hub BK 8TB             | 1        | 1.23%   |
| SanDisk Ultra II 960GB SSD             | 1        | 1.23%   |
| SanDisk SSD PLUS 240 GB                | 1        | 1.23%   |
| SanDisk SSD PLUS 120 GB                | 1        | 1.23%   |
| SanDisk SDSSDHII240G 240GB             | 1        | 1.23%   |
| SanDisk SDSSDA240G 240GB               | 1        | 1.23%   |
| SanDisk NVMe SSD Drive 1TB             | 1        | 1.23%   |
| Samsung SSD 970 PRO 512GB              | 1        | 1.23%   |
| Samsung SSD 970 EVO Plus 500GB         | 1        | 1.23%   |
| Samsung SSD 960 EVO 1TB                | 1        | 1.23%   |
| Samsung SSD 850 EVO 250GB              | 1        | 1.23%   |
| Samsung SSD 850 EVO 120GB              | 1        | 1.23%   |
| Samsung SSD 840 EVO 250GB              | 1        | 1.23%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 1        | 1.23%   |
| Samsung MZVLB256HBHQ-000L7 256GB       | 1        | 1.23%   |
| Plextor PX-512M9PeY 512GB              | 1        | 1.23%   |
| Phison Sabrent 1TB                     | 1        | 1.23%   |
| Phison PCIe SSD 2TB                    | 1        | 1.23%   |
| Lexar 1TB SSD                          | 1        | 1.23%   |
| Kingston SVP200S37A60G 64GB SSD        | 1        | 1.23%   |
| Kingston SUV400S37480G 480GB SSD       | 1        | 1.23%   |
| Kingston SUV300S37A240G 240GB SSD      | 1        | 1.23%   |
| Kingston SA400S37960G 960GB SSD        | 1        | 1.23%   |
| Kingston SA2000M8500G 500GB            | 1        | 1.23%   |
| Intel SSDSC2CT180A3 180GB              | 1        | 1.23%   |
| Intel SSDSC2BW240A4 240GB              | 1        | 1.23%   |
| Intel SSDSC2BW120A4 120GB              | 1        | 1.23%   |
| Intel SSDSA2BW160G3H 160GB             | 1        | 1.23%   |
| HGST HTS721010A9E630 1TB               | 1        | 1.23%   |
| Crucial M4-CT128M4SSD2 128GB           | 1        | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 8        | 10     | 40%     |
| WDC     | 6        | 11     | 30%     |
| Toshiba | 4        | 7      | 20%     |
| HGST    | 1        | 3      | 5%      |
| ASMT    | 1        | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 14     | 30%     |
| Crucial             | 6        | 7      | 20%     |
| SanDisk             | 4        | 7      | 13.33%  |
| Kingston            | 4        | 4      | 13.33%  |
| Intel               | 4        | 6      | 13.33%  |
| WDC                 | 1        | 2      | 3.33%   |
| Toshiba             | 1        | 1      | 3.33%   |
| China               | 1        | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 25       | 42     | 42.37%  |
| NVMe | 19       | 28     | 32.2%   |
| HDD  | 15       | 32     | 25.42%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 72     | 58.82%  |
| NVMe | 19       | 28     | 37.25%  |
| SAS  | 2        | 2      | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 28     | 38.3%   |
| 0.51-1.0   | 14       | 21     | 29.79%  |
| 2.01-3.0   | 5        | 6      | 10.64%  |
| 1.01-2.0   | 5        | 8      | 10.64%  |
| 4.01-10.0  | 3        | 7      | 6.38%   |
| 3.01-4.0   | 2        | 4      | 4.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 19       | 57.58%  |
| 1-20           | 5        | 15.15%  |
| 501-1000       | 3        | 9.09%   |
| 2001-3000      | 2        | 6.06%   |
| 101-250        | 2        | 6.06%   |
| More than 3000 | 1        | 3.03%   |
| 1001-2000      | 1        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 19       | 57.58%  |
| 1-20           | 7        | 21.21%  |
| 101-250        | 2        | 6.06%   |
| 1001-2000      | 2        | 6.06%   |
| More than 3000 | 1        | 3.03%   |
| 251-500        | 1        | 3.03%   |
| 501-1000       | 1        | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 970 EVO 1TB | 1        | 1      | 33.33%  |
| Intel SSDSC2BW240A4 240GB           | 1        | 1      | 33.33%  |
| ASMT 2115 128GB                     | 1        | 1      | 33.33%  |

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
| Works    | 31       | 90     | 83.78%  |
| Detected | 4        | 9      | 10.81%  |
| Malfunc  | 2        | 3      | 5.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 18       | 32.14%  |
| Intel                        | 15       | 26.79%  |
| Samsung Electronics          | 13       | 23.21%  |
| Phison Electronics           | 2        | 3.57%   |
| Kingston Technology Company  | 2        | 3.57%   |
| ASMedia Technology           | 2        | 3.57%   |
| Shenzhen Longsys Electronics | 1        | 1.79%   |
| SanDisk                      | 1        | 1.79%   |
| LSI Logic / Symbios Logic    | 1        | 1.79%   |
| Lite-On Technology           | 1        | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 12       | 19.35%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 11       | 17.74%  |
| AMD 500 Series Chipset SATA Controller                                        | 5        | 8.06%   |
| AMD 400 Series Chipset SATA Controller                                        | 3        | 4.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2        | 3.23%   |
| Phison E12 NVMe Controller                                                    | 2        | 3.23%   |
| Kingston Company A2000 NVMe SSD                                               | 2        | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 3.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 3.23%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 2        | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2        | 3.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2        | 3.23%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 2        | 3.23%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                   | 1        | 1.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1        | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 1.61%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]       | 1        | 1.61%   |
| Lite-On Non-Volatile memory controller                                        | 1        | 1.61%   |
| Intel SATA Controller [RAID mode]                                             | 1        | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1        | 1.61%   |
| Intel Comet Lake PCH-H RAID                                                   | 1        | 1.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1        | 1.61%   |
| Intel C610/X99 series chipset IDE-r Controller                                | 1        | 1.61%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1        | 1.61%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 1.61%   |
| AMD X399 Series Chipset SATA Controller                                       | 1        | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 31       | 56.36%  |
| NVMe | 20       | 36.36%  |
| RAID | 2        | 3.64%   |
| SAS  | 1        | 1.82%   |
| IDE  | 1        | 1.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 18       | 54.55%  |
| Intel  | 15       | 45.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 4        | 12.12%  |
| AMD Ryzen 7 3800X 8-Core Processor             | 3        | 9.09%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 6.06%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 6.06%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 6.06%   |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1        | 3.03%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1        | 3.03%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1        | 3.03%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1        | 3.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 3.03%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 3.03%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 3.03%   |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1        | 3.03%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 3.03%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1        | 3.03%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 3.03%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 3.03%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1        | 3.03%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 3.03%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 3.03%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 3.03%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 3.03%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 3.03%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 3.03%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 7        | 21.21%  |
| Intel Core i5          | 6        | 18.18%  |
| AMD Ryzen 7            | 5        | 15.15%  |
| Intel Core i7          | 4        | 12.12%  |
| AMD Ryzen 9            | 4        | 12.12%  |
| Intel Xeon             | 2        | 6.06%   |
| AMD Ryzen Threadripper | 2        | 6.06%   |
| Intel Core i9          | 1        | 3.03%   |
| Intel Core i3          | 1        | 3.03%   |
| Intel Celeron          | 1        | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 11       | 33.33%  |
| 4      | 6        | 18.18%  |
| 8      | 5        | 15.15%  |
| 12     | 3        | 9.09%   |
| 16     | 2        | 6.06%   |
| 10     | 2        | 6.06%   |
| 2      | 2        | 6.06%   |
| 32     | 1        | 3.03%   |
| 24     | 1        | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 96.97%  |
| 2      | 1        | 3.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 28       | 84.85%  |
| 1      | 5        | 15.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 33       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 6        | 17.65%  |
| Unknown    | 5        | 14.71%  |
| 0x08701013 | 4        | 11.76%  |
| 0x906ea    | 2        | 5.88%   |
| 0x506e3    | 2        | 5.88%   |
| 0x306c3    | 2        | 5.88%   |
| 0x306a9    | 2        | 5.88%   |
| 0x0a201204 | 2        | 5.88%   |
| 0x0a201009 | 2        | 5.88%   |
| 0xa0653    | 1        | 2.94%   |
| 0x906e9    | 1        | 2.94%   |
| 0x406f1    | 1        | 2.94%   |
| 0x306f2    | 1        | 2.94%   |
| 0x08301025 | 1        | 2.94%   |
| 0x0800820d | 1        | 2.94%   |
| 0x08001137 | 1        | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 12       | 36.36%  |
| Zen 3         | 4        | 12.12%  |
| Skylake       | 3        | 9.09%   |
| KabyLake      | 3        | 9.09%   |
| Haswell       | 3        | 9.09%   |
| IvyBridge     | 2        | 6.06%   |
| CometLake     | 2        | 6.06%   |
| Zen+          | 1        | 3.03%   |
| Zen           | 1        | 3.03%   |
| Goldmont plus | 1        | 3.03%   |
| Broadwell     | 1        | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 19       | 50%     |
| AMD    | 12       | 31.58%  |
| Intel  | 7        | 18.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 5        | 13.16%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 5        | 13.16%  |
| Nvidia TU106 [GeForce RTX 2070]                                  | 2        | 5.26%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 2        | 5.26%   |
| Nvidia GK104 [GeForce GTX 760]                                   | 2        | 5.26%   |
| Intel HD Graphics 530                                            | 2        | 5.26%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 2        | 5.26%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                               | 1        | 2.63%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                            | 1        | 2.63%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                            | 1        | 2.63%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                            | 1        | 2.63%   |
| Nvidia GP104 [GeForce GTX 1080]                                  | 1        | 2.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                  | 1        | 2.63%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                               | 1        | 2.63%   |
| Nvidia GM206 [GeForce GTX 960]                                   | 1        | 2.63%   |
| Nvidia GM204 [GeForce GTX 970]                                   | 1        | 2.63%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                | 1        | 2.63%   |
| Nvidia GK107 [NVS 510]                                           | 1        | 2.63%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                | 1        | 2.63%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                   | 1        | 2.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 2.63%   |
| Intel UHD P630 Graphics                                          | 1        | 2.63%   |
| Intel HD Graphics 630                                            | 1        | 2.63%   |
| Intel GeminiLake [UHD Graphics 600]                              | 1        | 2.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                        | 1        | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 15       | 45.45%  |
| 1 x AMD        | 9        | 27.27%  |
| 1 x Intel      | 5        | 15.15%  |
| AMD + Nvidia   | 3        | 9.09%   |
| Intel + Nvidia | 1        | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 57.58%  |
| Proprietary | 13       | 39.39%  |
| Unknown     | 1        | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 67.65%  |
| 7.01-8.0   | 9        | 26.47%  |
| 1.01-2.0   | 1        | 2.94%   |
| 8.01-16.0  | 1        | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 9        | 29.03%  |
| Goldstar             | 8        | 25.81%  |
| Acer                 | 3        | 9.68%   |
| Ancor Communications | 2        | 6.45%   |
| Vizio                | 1        | 3.23%   |
| Unknown (AAA)        | 1        | 3.23%   |
| Samsung Electronics  | 1        | 3.23%   |
| MPI                  | 1        | 3.23%   |
| Iiyama               | 1        | 3.23%   |
| HVR                  | 1        | 3.23%   |
| Hewlett-Packard      | 1        | 3.23%   |
| BenQ                 | 1        | 3.23%   |
| AOC                  | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2        | 6.06%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2        | 6.06%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2        | 6.06%   |
| Vizio E400i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                  | 1        | 3.03%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1        | 3.03%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.03%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                      | 1        | 3.03%   |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch               | 1        | 3.03%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 1        | 3.03%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 1        | 3.03%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch              | 1        | 3.03%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 1        | 3.03%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 3.03%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1        | 3.03%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1        | 3.03%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 1        | 3.03%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 1        | 3.03%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                     | 1        | 3.03%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 1        | 3.03%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                     | 1        | 3.03%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1        | 3.03%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                      | 1        | 3.03%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 1        | 3.03%   |
| Dell P2415Q DELA0BE 3840x2160 530x300mm 24.0-inch                     | 1        | 3.03%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                     | 1        | 3.03%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 3.03%   |
| AOC 2280W AOC2280 1920x1080 477x268mm 21.5-inch                       | 1        | 3.03%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 1        | 3.03%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 1        | 3.03%   |
| Acer AL1717 ACRAD60 1280x1024 338x270mm 17.0-inch                     | 1        | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 10       | 34.48%  |
| 3840x2160 (4K)    | 7        | 24.14%  |
| 2560x1440 (QHD)   | 4        | 13.79%  |
| 2560x1080         | 4        | 13.79%  |
| 2160x1200         | 1        | 3.45%   |
| 1920x1200 (WUXGA) | 1        | 3.45%   |
| 1280x720 (HD)     | 1        | 3.45%   |
| 1280x1024 (SXGA)  | 1        | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 23.33%  |
| 23      | 6        | 20%     |
| 34      | 4        | 13.33%  |
| 24      | 4        | 13.33%  |
| 25      | 2        | 6.67%   |
| 21      | 2        | 6.67%   |
| 49      | 1        | 3.33%   |
| 31      | 1        | 3.33%   |
| 17      | 1        | 3.33%   |
| 8       | 1        | 3.33%   |
| Unknown | 1        | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 60.71%  |
| 701-800     | 4        | 14.29%  |
| 401-500     | 2        | 7.14%   |
| 601-700     | 1        | 3.57%   |
| 301-350     | 1        | 3.57%   |
| 101-200     | 1        | 3.57%   |
| 1001-1500   | 1        | 3.57%   |
| Unknown     | 1        | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 17       | 65.38%  |
| 21/9  | 4        | 15.38%  |
| 16/10 | 3        | 11.54%  |
| 5/4   | 1        | 3.85%   |
| 4/3   | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 29.03%  |
| 301-350        | 7        | 22.58%  |
| 351-500        | 5        | 16.13%  |
| 251-300        | 4        | 12.9%   |
| 151-200        | 2        | 6.45%   |
| More than 1000 | 1        | 3.23%   |
| 1-40           | 1        | 3.23%   |
| 141-150        | 1        | 3.23%   |
| Unknown        | 1        | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 51.72%  |
| 161-240 | 6        | 20.69%  |
| 101-120 | 5        | 17.24%  |
| 1-50    | 1        | 3.45%   |
| 121-160 | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 57.58%  |
| 0     | 7        | 21.21%  |
| 2     | 5        | 15.15%  |
| 3     | 2        | 6.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 22       | 43.14%  |
| Realtek Semiconductor | 21       | 41.18%  |
| Aquantia              | 2        | 3.92%   |
| TP-Link               | 1        | 1.96%   |
| Texas Instruments     | 1        | 1.96%   |
| Qualcomm Atheros      | 1        | 1.96%   |
| Oculus VR             | 1        | 1.96%   |
| Microsoft             | 1        | 1.96%   |
| MediaTek              | 1        | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15       | 27.78%  |
| Intel Wi-Fi 6 AX200                                               | 6        | 11.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 9.26%   |
| Intel I211 Gigabit Network Connection                             | 5        | 9.26%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 3.7%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.7%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 3.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.85%   |
| Texas Instruments CC2538 USB CDC                                  | 1        | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.85%   |
| Oculus VR Rift S                                                  | 1        | 1.85%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.85%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.85%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.85%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.85%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Intel     | 8        | 72.73%  |
| TP-Link   | 1        | 9.09%   |
| Microsoft | 1        | 9.09%   |
| MediaTek  | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 6        | 54.55%  |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1        | 9.09%   |
| Microsoft Xbox 360 Wireless Adapter                        | 1        | 9.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 9.09%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 51.22%  |
| Intel                 | 17       | 41.46%  |
| Aquantia              | 2        | 4.88%   |
| Qualcomm Atheros      | 1        | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15       | 36.59%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 12.2%   |
| Intel I211 Gigabit Network Connection                             | 5        | 12.2%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 4.88%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 4.88%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 4.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 2.44%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.44%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 2.44%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.44%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.44%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 71.74%  |
| WiFi     | 11       | 23.91%  |
| Modem    | 2        | 4.35%   |

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
| 1     | 18       | 54.55%  |
| 2     | 12       | 36.36%  |
| 3     | 2        | 6.06%   |
| 0     | 1        | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 69.7%   |
| Yes  | 10       | 30.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 6        | 40%     |
| ASUSTek Computer         | 3        | 20%     |
| Cambridge Silicon Radio  | 2        | 13.33%  |
| Realtek Semiconductor    | 1        | 6.67%   |
| MediaTek                 | 1        | 6.67%   |
| HTC (High Tech Computer) | 1        | 6.67%   |
| Broadcom                 | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 4        | 26.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 13.33%  |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 13.33%  |
| Realtek Bluetooth Radio                                              | 1        | 6.67%   |
| MediaTek Wireless_Device                                             | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 6.67%   |
| Intel Bluetooth Device                                               | 1        | 6.67%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 6.67%   |
| ASUS ASUS USB-BT500                                                  | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 20       | 27.78%  |
| Nvidia                               | 19       | 26.39%  |
| Intel                                | 15       | 20.83%  |
| C-Media Electronics                  | 3        | 4.17%   |
| Texas Instruments                    | 2        | 2.78%   |
| Sennheiser Communications            | 2        | 2.78%   |
| Unknown                              | 1        | 1.39%   |
| Thomann                              | 1        | 1.39%   |
| Thesycon Systemsoftware & Consulting | 1        | 1.39%   |
| Sony                                 | 1        | 1.39%   |
| Schiit Audio                         | 1        | 1.39%   |
| PreSonus Audio Electronics           | 1        | 1.39%   |
| Kingston Technology                  | 1        | 1.39%   |
| GYROCOM C&C                          | 1        | 1.39%   |
| Creative Technology                  | 1        | 1.39%   |
| Creative Labs                        | 1        | 1.39%   |
| Antlion Audio                        | 1        | 1.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 16       | 19.51%  |
| AMD Navi 10 HDMI Audio                                              | 5        | 6.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 5        | 6.1%    |
| Nvidia TU106 High Definition Audio Controller                       | 3        | 3.66%   |
| Nvidia GK104 HDMI Audio Controller                                  | 3        | 3.66%   |
| Texas Instruments PCM2902 Audio Codec                               | 2        | 2.44%   |
| Nvidia TU116 High Definition Audio Controller                       | 2        | 2.44%   |
| Nvidia GP106 High Definition Audio Controller                       | 2        | 2.44%   |
| Nvidia GP104 High Definition Audio Controller                       | 2        | 2.44%   |
| Intel Comet Lake PCH cAVS                                           | 2        | 2.44%   |
| Intel Cannon Lake PCH cAVS                                          | 2        | 2.44%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2        | 2.44%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2        | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2        | 2.44%   |
| Intel 200 Series PCH HD Audio                                       | 2        | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2        | 2.44%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2        | 2.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 2        | 2.44%   |
| Unknown USB Audio                                                   | 1        | 1.22%   |
| Thomann SC450USB                                                    | 1        | 1.22%   |
| Thesycon Systemsoftware & Consulting E30                            | 1        | 1.22%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1        | 1.22%   |
| Sennheiser Communications Sennheiser SC630 for Lync                 | 1        | 1.22%   |
| Sennheiser Communications Headset [PC 8]                            | 1        | 1.22%   |
| Schiit Audio Schiit Modi 3+                                         | 1        | 1.22%   |
| PreSonus Audio Electronics AudioBox                                 | 1        | 1.22%   |
| Nvidia TU104 HD Audio Controller                                    | 1        | 1.22%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1        | 1.22%   |
| Nvidia GM206 High Definition Audio Controller                       | 1        | 1.22%   |
| Nvidia GM204 High Definition Audio Controller                       | 1        | 1.22%   |
| Nvidia GM200 High Definition Audio                                  | 1        | 1.22%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1        | 1.22%   |
| Nvidia Audio device                                                 | 1        | 1.22%   |
| Kingston Technology HyperX 7.1 Audio                                | 1        | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1        | 1.22%   |
| GYROCOM C&C Fiio E10                                                | 1        | 1.22%   |
| Creative Technology Sound BlasterX G1                               | 1        | 1.22%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]          | 1        | 1.22%   |
| C-Media Electronics USB Advanced Audio Device                       | 1        | 1.22%   |
| C-Media Electronics CM108 Audio Controller                          | 1        | 1.22%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 1        | 1.22%   |
| Antlion Audio Antlion USB Microphone                                | 1        | 1.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 12       | 31.58%  |
| Kingston            | 8        | 21.05%  |
| G.Skill             | 6        | 15.79%  |
| Micron Technology   | 3        | 7.89%   |
| Crucial             | 3        | 7.89%   |
| Samsung Electronics | 2        | 5.26%   |
| Unknown (ABCD)      | 1        | 2.63%   |
| Unknown             | 1        | 2.63%   |
| Strontium           | 1        | 2.63%   |
| Goodram             | 1        | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s         | 3        | 7.14%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 2        | 4.76%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 2        | 4.76%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s            | 2        | 4.76%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 2        | 4.76%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s         | 2        | 4.76%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                  | 1        | 2.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 2.38%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s             | 1        | 2.38%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1        | 2.38%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s           | 1        | 2.38%   |
| Micron RAM 4ATF1G64AZ-3G2E1 8GB DIMM DDR4 3200MT/s             | 1        | 2.38%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s           | 1        | 2.38%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s           | 1        | 2.38%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s        | 1        | 2.38%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1        | 2.38%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s            | 1        | 2.38%   |
| Kingston RAM 9965745-021.A00G 32GB DIMM DDR4 2933MT/s          | 1        | 2.38%   |
| Kingston RAM 9965684-028.A00G 8GB DIMM DDR4 3200MT/s           | 1        | 2.38%   |
| Goodram RAM GR1600D364L9/4G 4096MB DIMM DDR3 1333MT/s          | 1        | 2.38%   |
| Goodram RAM GR1600D364L11/4G 4GB DIMM DDR3 1600MT/s            | 1        | 2.38%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 1        | 2.38%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 1        | 2.38%   |
| G.Skill RAM F3-2133C10-8GXM 8192MB DIMM DDR3 2132MT/s          | 1        | 2.38%   |
| G.Skill RAM F3-1600C9-8GSR 8GB DIMM DDR3 1333MT/s              | 1        | 2.38%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s          | 1        | 2.38%   |
| Crucial RAM BLS16G4D32AESE.M16FE 16GB DIMM DDR4 3733MT/s       | 1        | 2.38%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s       | 1        | 2.38%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 1        | 2.38%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s          | 1        | 2.38%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s         | 1        | 2.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 1        | 2.38%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s         | 1        | 2.38%   |
| Corsair RAM CMK16GX4M2D3600C18 8192MB DIMM DDR4 3600MT/s       | 1        | 2.38%   |
| Corsair RAM CMD64GX4M4A2666C15 16384MB DIMM DDR4 2133MT/s      | 1        | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 27       | 84.38%  |
| DDR3   | 4        | 12.5%   |
| LPDDR4 | 1        | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 30       | 93.75%  |
| SODIMM | 1        | 3.13%   |
| RIMM   | 1        | 3.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 15       | 41.67%  |
| 8192  | 12       | 33.33%  |
| 32768 | 7        | 19.44%  |
| 4096  | 2        | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 12       | 30.77%  |
| 3600  | 5        | 12.82%  |
| 2133  | 4        | 10.26%  |
| 3000  | 3        | 7.69%   |
| 1600  | 3        | 7.69%   |
| 3334  | 2        | 5.13%   |
| 2400  | 2        | 5.13%   |
| 3733  | 1        | 2.56%   |
| 3533  | 1        | 2.56%   |
| 3466  | 1        | 2.56%   |
| 3400  | 1        | 2.56%   |
| 3266  | 1        | 2.56%   |
| 2933  | 1        | 2.56%   |
| 2132  | 1        | 2.56%   |
| 1333  | 1        | 2.56%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Logitech     | 5        | 55.56%  |
| MacroSilicon | 2        | 22.22%  |
| Microdia     | 1        | 11.11%  |
| Apple        | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| MacroSilicon MiraBox Capture | 2        | 22.22%  |
| Microdia Camera              | 1        | 11.11%  |
| Logitech Webcam C930e        | 1        | 11.11%  |
| Logitech Webcam C270         | 1        | 11.11%  |
| Logitech StreamCam           | 1        | 11.11%  |
| Logitech HD Pro Webcam C920  | 1        | 11.11%  |
| Logitech C930c               | 1        | 11.11%  |
| Apple iPhone 5/5C/5S/6/SE    | 1        | 11.11%  |

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
| 0     | 25       | 75.76%  |
| 1     | 7        | 21.21%  |
| 2     | 1        | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 37.5%   |
| Net/wireless     | 2        | 25%     |
| Graphics card    | 1        | 12.5%   |
| Camera           | 1        | 12.5%   |
| Bluetooth        | 1        | 12.5%   |

