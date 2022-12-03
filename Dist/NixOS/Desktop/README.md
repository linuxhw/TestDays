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

Total: 48

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | SABERTOOTH 990FX R2.0       | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| ASUSTek    | PRIME B550M-A               | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Gigabyte   | X570 AORUS ELITE            | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| ASUSTek    | PRIME B550M-A               | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| ASRock     | AB350 Pro4                  | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
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
| NixOS 22.05                      | 13       | 34.21%  |
| NixOS 21.11                      | 7        | 18.42%  |
| NixOS                            | 3        | 7.89%   |
| NixOS 21.05pre-git               | 2        | 5.26%   |
| NixOS 21.11.20210528.540dccb     | 1        | 2.63%   |
| NixOS 21.05.993.93963c27b93      | 1        | 2.63%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1        | 2.63%   |
| NixOS 21.05.20210929.ee90403     | 1        | 2.63%   |
| NixOS 21.05.20210430.c8dff32     | 1        | 2.63%   |
| NixOS 21.05.20210224.f6b5bfd     | 1        | 2.63%   |
| NixOS 21.05.1471.a7512bb64b1     | 1        | 2.63%   |
| NixOS 21.03pre246062.420f89ceb26 | 1        | 2.63%   |
| NixOS 21.03.git.b4349c13a6d      | 1        | 2.63%   |
| NixOS 21.03.20201007.420f89c     | 1        | 2.63%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1        | 2.63%   |
| NixOS 20.09pre-git               | 1        | 2.63%   |
| NixOS 20.09.git.4a361b06a93      | 1        | 2.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| NixOS | 36       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.8.1-zen1             | 2        | 5.13%   |
| 5.15.47                | 2        | 5.13%   |
| 5.10.102               | 2        | 5.13%   |
| 5.8.10                 | 1        | 2.56%   |
| 5.7.19                 | 1        | 2.56%   |
| 5.4.94                 | 1        | 2.56%   |
| 5.4.72                 | 1        | 2.56%   |
| 5.4.69                 | 1        | 2.56%   |
| 5.4.50                 | 1        | 2.56%   |
| 5.4.47                 | 1        | 2.56%   |
| 5.19.14                | 1        | 2.56%   |
| 5.18.19                | 1        | 2.56%   |
| 5.18.14-lqx2           | 1        | 2.56%   |
| 5.17.1                 | 1        | 2.56%   |
| 5.16.8-zen1            | 1        | 2.56%   |
| 5.15.74                | 1        | 2.56%   |
| 5.15.7                 | 1        | 2.56%   |
| 5.15.50                | 1        | 2.56%   |
| 5.15.43                | 1        | 2.56%   |
| 5.15.39                | 1        | 2.56%   |
| 5.15.34                | 1        | 2.56%   |
| 5.15.26                | 1        | 2.56%   |
| 5.15.25                | 1        | 2.56%   |
| 5.15.18                | 1        | 2.56%   |
| 5.14.16-lqx1           | 1        | 2.56%   |
| 5.13.2                 | 1        | 2.56%   |
| 5.12.15                | 1        | 2.56%   |
| 5.11.16-zen1           | 1        | 2.56%   |
| 5.11.16-xanmod1-cacule | 1        | 2.56%   |
| 5.10.99                | 1        | 2.56%   |
| 5.10.96                | 1        | 2.56%   |
| 5.10.62                | 1        | 2.56%   |
| 5.10.52                | 1        | 2.56%   |
| 5.10.43                | 1        | 2.56%   |
| 5.10.35                | 1        | 2.56%   |
| 5.10.17                | 1        | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.8.1    | 2        | 5.13%   |
| 5.15.47  | 2        | 5.13%   |
| 5.11.16  | 2        | 5.13%   |
| 5.10.102 | 2        | 5.13%   |
| 5.8.10   | 1        | 2.56%   |
| 5.7.19   | 1        | 2.56%   |
| 5.4.94   | 1        | 2.56%   |
| 5.4.72   | 1        | 2.56%   |
| 5.4.69   | 1        | 2.56%   |
| 5.4.50   | 1        | 2.56%   |
| 5.4.47   | 1        | 2.56%   |
| 5.19.14  | 1        | 2.56%   |
| 5.18.19  | 1        | 2.56%   |
| 5.18.14  | 1        | 2.56%   |
| 5.17.1   | 1        | 2.56%   |
| 5.16.8   | 1        | 2.56%   |
| 5.15.74  | 1        | 2.56%   |
| 5.15.7   | 1        | 2.56%   |
| 5.15.50  | 1        | 2.56%   |
| 5.15.43  | 1        | 2.56%   |
| 5.15.39  | 1        | 2.56%   |
| 5.15.34  | 1        | 2.56%   |
| 5.15.26  | 1        | 2.56%   |
| 5.15.25  | 1        | 2.56%   |
| 5.15.18  | 1        | 2.56%   |
| 5.14.16  | 1        | 2.56%   |
| 5.13.2   | 1        | 2.56%   |
| 5.12.15  | 1        | 2.56%   |
| 5.10.99  | 1        | 2.56%   |
| 5.10.96  | 1        | 2.56%   |
| 5.10.62  | 1        | 2.56%   |
| 5.10.52  | 1        | 2.56%   |
| 5.10.43  | 1        | 2.56%   |
| 5.10.35  | 1        | 2.56%   |
| 5.10.17  | 1        | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 11       | 28.21%  |
| 5.10    | 9        | 23.08%  |
| 5.4     | 5        | 12.82%  |
| 5.8     | 3        | 7.69%   |
| 5.18    | 2        | 5.13%   |
| 5.11    | 2        | 5.13%   |
| 5.7     | 1        | 2.56%   |
| 5.19    | 1        | 2.56%   |
| 5.17    | 1        | 2.56%   |
| 5.16    | 1        | 2.56%   |
| 5.14    | 1        | 2.56%   |
| 5.13    | 1        | 2.56%   |
| 5.12    | 1        | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 36       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 26       | 72.22%  |
| KDE          | 3        | 8.33%   |
| XFCE         | 2        | 5.56%   |
| sway         | 2        | 5.56%   |
| GNOME        | 2        | 5.56%   |
| none+awesome | 1        | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 64.86%  |
| X11     | 8        | 21.62%  |
| Wayland | 3        | 8.11%   |
| Tty     | 2        | 5.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 77.78%  |
| LightDM | 4        | 11.11%  |
| SDDM    | 2        | 5.56%   |
| GDM     | 2        | 5.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 50%     |
| en_US   | 12       | 33.33%  |
| en_GB   | 2        | 5.56%   |
| pt_BR   | 1        | 2.78%   |
| it_IT   | 1        | 2.78%   |
| en_DK   | 1        | 2.78%   |
| de_CH   | 1        | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 29       | 78.38%  |
| BIOS | 8        | 21.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 15       | 41.67%  |
| Tmpfs   | 5        | 13.89%  |
| Zfs     | 4        | 11.11%  |
| Xfs     | 4        | 11.11%  |
| Btrfs   | 4        | 11.11%  |
| Unknown | 3        | 8.33%   |
| Ext2    | 1        | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 34       | 94.44%  |
| Unknown | 2        | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 75%     |
| Yes       | 9        | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 52.78%  |
| No        | 17       | 47.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 44.44%  |
| MSI                 | 7        | 19.44%  |
| Gigabyte Technology | 4        | 11.11%  |
| ASRock              | 4        | 11.11%  |
| Hewlett-Packard     | 1        | 2.78%   |
| Hardkernel          | 1        | 2.78%   |
| EVGA                | 1        | 2.78%   |
| Dell                | 1        | 2.78%   |
| Acer                | 1        | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7C37                      | 2        | 5.56%   |
| MSI MS-7C95                      | 1        | 2.78%   |
| MSI MS-7C84                      | 1        | 2.78%   |
| MSI MS-7C35                      | 1        | 2.78%   |
| MSI MS-7B89                      | 1        | 2.78%   |
| MSI MS-7B09                      | 1        | 2.78%   |
| HP EliteDesk 800 G2 DM 35W       | 1        | 2.78%   |
| Hardkernel ODROID-H2             | 1        | 2.78%   |
| Gigabyte X570 AORUS ELITE        | 1        | 2.78%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 2.78%   |
| Gigabyte H97M-D3H                | 1        | 2.78%   |
| Gigabyte B550I AORUS PRO AX      | 1        | 2.78%   |
| EVGA X299 FTW K                  | 1        | 2.78%   |
| Dell Precision Tower 7810        | 1        | 2.78%   |
| ASUS Z170-P                      | 1        | 2.78%   |
| ASUS TUF Gaming X570-PLUS        | 1        | 2.78%   |
| ASUS SABERTOOTH 990FX R2.0       | 1        | 2.78%   |
| ASUS ROG STRIX Z390-F GAMING     | 1        | 2.78%   |
| ASUS ROG STRIX B550-I GAMING     | 1        | 2.78%   |
| ASUS ROG STRIX B550-F GAMING     | 1        | 2.78%   |
| ASUS PRO602617                   | 1        | 2.78%   |
| ASUS PRO-Q77 IU                  | 1        | 2.78%   |
| ASUS Pro WS W480-ACE             | 1        | 2.78%   |
| ASUS PRIME Z390-A                | 1        | 2.78%   |
| ASUS PRIME Z270-K                | 1        | 2.78%   |
| ASUS PRIME X570-P                | 1        | 2.78%   |
| ASUS PRIME B550M-A               | 1        | 2.78%   |
| ASUS PRIME A520M-K               | 1        | 2.78%   |
| ASUS P8Z77-V LK                  | 1        | 2.78%   |
| ASUS All Series                  | 1        | 2.78%   |
| ASRock X570 Taichi               | 1        | 2.78%   |
| ASRock TRX40 Creator             | 1        | 2.78%   |
| ASRock B450 Gaming-ITX/ac        | 1        | 2.78%   |
| ASRock AB350 Pro4                | 1        | 2.78%   |
| Acer Nitro N50-610               | 1        | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 5        | 13.89%  |
| ASUS ROG             | 3        | 8.33%   |
| MSI MS-7C37          | 2        | 5.56%   |
| MSI MS-7C95          | 1        | 2.78%   |
| MSI MS-7C84          | 1        | 2.78%   |
| MSI MS-7C35          | 1        | 2.78%   |
| MSI MS-7B89          | 1        | 2.78%   |
| MSI MS-7B09          | 1        | 2.78%   |
| HP EliteDesk         | 1        | 2.78%   |
| Hardkernel ODROID-H2 | 1        | 2.78%   |
| Gigabyte X570        | 1        | 2.78%   |
| Gigabyte X470        | 1        | 2.78%   |
| Gigabyte H97M-D3H    | 1        | 2.78%   |
| Gigabyte B550I       | 1        | 2.78%   |
| EVGA X299            | 1        | 2.78%   |
| Dell Precision       | 1        | 2.78%   |
| ASUS Z170-P          | 1        | 2.78%   |
| ASUS TUF             | 1        | 2.78%   |
| ASUS SABERTOOTH      | 1        | 2.78%   |
| ASUS PRO602617       | 1        | 2.78%   |
| ASUS PRO-Q77         | 1        | 2.78%   |
| ASUS Pro             | 1        | 2.78%   |
| ASUS P8Z77-V         | 1        | 2.78%   |
| ASUS All             | 1        | 2.78%   |
| ASRock X570          | 1        | 2.78%   |
| ASRock TRX40         | 1        | 2.78%   |
| ASRock B450          | 1        | 2.78%   |
| ASRock AB350         | 1        | 2.78%   |
| Acer Nitro           | 1        | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 10       | 27.78%  |
| 2020 | 9        | 25%     |
| 2018 | 5        | 13.89%  |
| 2016 | 4        | 11.11%  |
| 2017 | 2        | 5.56%   |
| 2015 | 2        | 5.56%   |
| 2014 | 2        | 5.56%   |
| 2012 | 2        | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 36       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 36       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 36       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 13       | 36.11%  |
| 32.01-64.0  | 10       | 27.78%  |
| 16.01-24.0  | 7        | 19.44%  |
| 4.01-8.0    | 2        | 5.56%   |
| 24.01-32.0  | 2        | 5.56%   |
| 8.01-16.0   | 2        | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 10       | 27.03%  |
| 4.01-8.0   | 9        | 24.32%  |
| 32.01-64.0 | 5        | 13.51%  |
| 3.01-4.0   | 5        | 13.51%  |
| 16.01-24.0 | 4        | 10.81%  |
| 1.01-2.0   | 2        | 5.41%   |
| 24.01-32.0 | 1        | 2.7%    |
| 2.01-3.0   | 1        | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 34.21%  |
| 3      | 9        | 23.68%  |
| 1      | 6        | 15.79%  |
| 6      | 4        | 10.53%  |
| 5      | 3        | 7.89%   |
| 8      | 1        | 2.63%   |
| 4      | 1        | 2.63%   |
| 0      | 1        | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 80.56%  |
| Yes       | 7        | 19.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 36       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 69.44%  |
| Yes       | 11       | 30.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 55.56%  |
| Yes       | 16       | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 9        | 25%     |
| Germany     | 7        | 19.44%  |
| UK          | 3        | 8.33%   |
| Poland      | 3        | 8.33%   |
| Russia      | 2        | 5.56%   |
| Canada      | 2        | 5.56%   |
| Austria     | 2        | 5.56%   |
| Ukraine     | 1        | 2.78%   |
| Switzerland | 1        | 2.78%   |
| Serbia      | 1        | 2.78%   |
| New Zealand | 1        | 2.78%   |
| Italy       | 1        | 2.78%   |
| Hungary     | 1        | 2.78%   |
| Denmark     | 1        | 2.78%   |
| Brazil      | 1        | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 2        | 5.56%   |
| Schaafheim        | 2        | 5.56%   |
| Plymouth          | 2        | 5.56%   |
| Marki             | 2        | 5.56%   |
| Darmstadt         | 2        | 5.56%   |
| Wellington        | 1        | 2.78%   |
| Székesfehérvár | 1        | 2.78%   |
| Southampton       | 1        | 2.78%   |
| South Deerfield   | 1        | 2.78%   |
| Sindelfingen      | 1        | 2.78%   |
| San Gabriel       | 1        | 2.78%   |
| Richardson        | 1        | 2.78%   |
| Redwood City      | 1        | 2.78%   |
| Ramenskoye        | 1        | 2.78%   |
| Pisa              | 1        | 2.78%   |
| Osasco            | 1        | 2.78%   |
| Oakville          | 1        | 2.78%   |
| Montreal          | 1        | 2.78%   |
| Melrose           | 1        | 2.78%   |
| Kuybyshev         | 1        | 2.78%   |
| Kharkiv           | 1        | 2.78%   |
| Karlsruhe         | 1        | 2.78%   |
| Heusweiler        | 1        | 2.78%   |
| Goleta            | 1        | 2.78%   |
| Gdansk            | 1        | 2.78%   |
| Esbjerg           | 1        | 2.78%   |
| Dietikon          | 1        | 2.78%   |
| Didcot            | 1        | 2.78%   |
| Belgrade          | 1        | 2.78%   |
| Austin            | 1        | 2.78%   |
| Andover           | 1        | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 45     | 30%     |
| Seagate             | 9        | 12     | 12.86%  |
| Toshiba             | 7        | 12     | 10%     |
| WDC                 | 6        | 13     | 8.57%   |
| Crucial             | 6        | 7      | 8.57%   |
| SanDisk             | 5        | 9      | 7.14%   |
| Kingston            | 5        | 5      | 7.14%   |
| Intel               | 4        | 6      | 5.71%   |
| Plextor             | 1        | 1      | 1.43%   |
| Phison Electronics  | 1        | 2      | 1.43%   |
| Phison              | 1        | 1      | 1.43%   |
| Lexar               | 1        | 1      | 1.43%   |
| HGST                | 1        | 3      | 1.43%   |
| China               | 1        | 1      | 1.43%   |
| ASMT                | 1        | 1      | 1.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB               | 4        | 4.55%   |
| Samsung SSD 970 EVO Plus 2TB          | 3        | 3.41%   |
| Seagate ST3000DM001-1ER166 3TB        | 2        | 2.27%   |
| SanDisk SSD PLUS 240GB                | 2        | 2.27%   |
| Samsung SSD 980 PRO 1TB               | 2        | 2.27%   |
| Samsung SSD 970 EVO Plus 1TB          | 2        | 2.27%   |
| Samsung SSD 970 EVO 500GB             | 2        | 2.27%   |
| Samsung SSD 970 EVO 1TB               | 2        | 2.27%   |
| Samsung SSD 860 QVO 1TB               | 2        | 2.27%   |
| Samsung SSD 860 EVO 500GB             | 2        | 2.27%   |
| Samsung SSD 860 EVO 2TB               | 2        | 2.27%   |
| Samsung NVMe SSD Drive 1TB            | 2        | 2.27%   |
| Crucial CT1000MX500SSD1 1TB           | 2        | 2.27%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1        | 1.14%   |
| WDC WD80EDAZ-11TA3A0 8TB              | 1        | 1.14%   |
| WDC WD40EFRX-68N32N0 4TB              | 1        | 1.14%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1        | 1.14%   |
| WDC WD10EZEX-21WN4A0 1TB              | 1        | 1.14%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1        | 1.14%   |
| WDC WD10EZEX-00KUWA0 1TB              | 1        | 1.14%   |
| Toshiba TR150 960GB SSD               | 1        | 1.14%   |
| Toshiba HDWR180 8TB                   | 1        | 1.14%   |
| Toshiba HDWL120 2TB                   | 1        | 1.14%   |
| Toshiba HDWE160 6TB                   | 1        | 1.14%   |
| Toshiba HDWD130 3TB                   | 1        | 1.14%   |
| Toshiba HDWD120 2TB                   | 1        | 1.14%   |
| Toshiba BG3 NVMe SSD Controller 128GB | 1        | 1.14%   |
| Seagate ST4000DM004-2CV104 4TB        | 1        | 1.14%   |
| Seagate ST3000VX010-2H916L 3TB        | 1        | 1.14%   |
| Seagate ST3000DM001-1CH166 3TB        | 1        | 1.14%   |
| Seagate ST2000DM006-2DM164 2TB        | 1        | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1.14%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1.14%   |
| Seagate Backup+ Hub BK 8TB            | 1        | 1.14%   |
| SanDisk Ultra II 960GB SSD            | 1        | 1.14%   |
| SanDisk SSD PLUS 240 GB               | 1        | 1.14%   |
| SanDisk SSD PLUS 120 GB               | 1        | 1.14%   |
| SanDisk SDSSDHII240G 240GB            | 1        | 1.14%   |
| SanDisk SDSSDA240G 240GB              | 1        | 1.14%   |
| SanDisk NVMe SSD Drive 1TB            | 1        | 1.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 12     | 40.91%  |
| WDC     | 6        | 11     | 27.27%  |
| Toshiba | 5        | 9      | 22.73%  |
| HGST    | 1        | 3      | 4.55%   |
| ASMT    | 1        | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 21     | 34.38%  |
| Crucial             | 6        | 7      | 18.75%  |
| SanDisk             | 4        | 7      | 12.5%   |
| Kingston            | 4        | 4      | 12.5%   |
| Intel               | 4        | 6      | 12.5%   |
| WDC                 | 1        | 2      | 3.13%   |
| Toshiba             | 1        | 1      | 3.13%   |
| China               | 1        | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 27       | 49     | 42.86%  |
| NVMe | 20       | 34     | 31.75%  |
| HDD  | 16       | 36     | 25.4%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 32       | 83     | 59.26%  |
| NVMe | 20       | 34     | 37.04%  |
| SAS  | 2        | 2      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 19       | 29     | 37.25%  |
| 0.51-1.0   | 15       | 27     | 29.41%  |
| 1.01-2.0   | 6        | 9      | 11.76%  |
| 2.01-3.0   | 5        | 7      | 9.8%    |
| 4.01-10.0  | 4        | 9      | 7.84%   |
| 3.01-4.0   | 2        | 4      | 3.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 21       | 58.33%  |
| 1-20           | 5        | 13.89%  |
| 2001-3000      | 3        | 8.33%   |
| 501-1000       | 3        | 8.33%   |
| 101-250        | 2        | 5.56%   |
| More than 3000 | 1        | 2.78%   |
| 1001-2000      | 1        | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 21       | 58.33%  |
| 1-20           | 7        | 19.44%  |
| 101-250        | 2        | 5.56%   |
| 1001-2000      | 2        | 5.56%   |
| More than 3000 | 1        | 2.78%   |
| 251-500        | 1        | 2.78%   |
| 2001-3000      | 1        | 2.78%   |
| 501-1000       | 1        | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 970 EVO 1TB | 1        | 1      | 25%     |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 25%     |
| Intel SSDSC2BW240A4 240GB           | 1        | 1      | 25%     |
| ASMT 2115 16GB                      | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 50%     |
| Intel               | 1        | 1      | 25%     |
| ASMT                | 1        | 1      | 25%     |

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
| SSD  | 2        | 2      | 50%     |
| NVMe | 1        | 1      | 25%     |
| HDD  | 1        | 1      | 25%     |

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
| Works    | 34       | 106    | 82.93%  |
| Detected | 4        | 9      | 9.76%   |
| Malfunc  | 3        | 4      | 7.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 21       | 32.31%  |
| Intel                        | 15       | 23.08%  |
| Samsung Electronics          | 14       | 21.54%  |
| ASMedia Technology           | 4        | 6.15%   |
| Phison Electronics           | 2        | 3.08%   |
| LSI Logic / Symbios Logic    | 2        | 3.08%   |
| Kingston Technology Company  | 2        | 3.08%   |
| Toshiba America Info Systems | 1        | 1.54%   |
| Shenzhen Longsys Electronics | 1        | 1.54%   |
| SanDisk                      | 1        | 1.54%   |
| Lite-On Technology           | 1        | 1.54%   |
| Broadcom / LSI               | 1        | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 13       | 18.06%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 11       | 15.28%  |
| AMD 500 Series Chipset SATA Controller                                        | 6        | 8.33%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 4        | 5.56%   |
| AMD 400 Series Chipset SATA Controller                                        | 3        | 4.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2        | 2.78%   |
| Phison E12 NVMe Controller                                                    | 2        | 2.78%   |
| Kingston Company A2000 NVMe SSD                                               | 2        | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 2.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 2.78%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 2        | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2        | 2.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2        | 2.78%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1        | 1.39%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                   | 1        | 1.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1        | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 1.39%   |
| Samsung NVMe SSD Controller 980                                               | 1        | 1.39%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                | 1        | 1.39%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]       | 1        | 1.39%   |
| Lite-On Non-Volatile memory controller                                        | 1        | 1.39%   |
| Intel SATA Controller [RAID mode]                                             | 1        | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1        | 1.39%   |
| Intel Comet Lake PCH-H RAID                                                   | 1        | 1.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1        | 1.39%   |
| Intel C610/X99 series chipset IDE-r Controller                                | 1        | 1.39%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1        | 1.39%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 1.39%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                           | 1        | 1.39%   |
| AMD X399 Series Chipset SATA Controller                                       | 1        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1        | 1.39%   |
| AMD 300 Series Chipset SATA Controller                                        | 1        | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 34       | 55.74%  |
| NVMe | 21       | 34.43%  |
| SAS  | 3        | 4.92%   |
| RAID | 2        | 3.28%   |
| IDE  | 1        | 1.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 21       | 58.33%  |
| Intel  | 15       | 41.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 5        | 13.89%  |
| AMD Ryzen 7 3800X 8-Core Processor             | 3        | 8.33%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 5.56%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 5.56%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 5.56%   |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1        | 2.78%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz            | 1        | 2.78%   |
| Intel Core i9-9900X CPU @ 3.50GHz              | 1        | 2.78%   |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1        | 2.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 2.78%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 2.78%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 2.78%   |
| Intel Core i5-4570S CPU @ 2.90GHz              | 1        | 2.78%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 1        | 2.78%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1        | 2.78%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 2.78%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 2.78%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1        | 2.78%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 2.78%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 2.78%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 2.78%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 2.78%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 2.78%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 2.78%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 2.78%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 2.78%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 8        | 22.22%  |
| Intel Core i5          | 6        | 16.67%  |
| AMD Ryzen 7            | 6        | 16.67%  |
| Intel Core i7          | 4        | 11.11%  |
| AMD Ryzen 9            | 4        | 11.11%  |
| Intel Xeon             | 2        | 5.56%   |
| AMD Ryzen Threadripper | 2        | 5.56%   |
| Intel Core i9          | 1        | 2.78%   |
| Intel Core i3          | 1        | 2.78%   |
| Intel Celeron          | 1        | 2.78%   |
| AMD FX                 | 1        | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 12       | 33.33%  |
| 4      | 7        | 19.44%  |
| 8      | 6        | 16.67%  |
| 12     | 3        | 8.33%   |
| 16     | 2        | 5.56%   |
| 10     | 2        | 5.56%   |
| 2      | 2        | 5.56%   |
| 32     | 1        | 2.78%   |
| 24     | 1        | 2.78%   |

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
| 2      | 31       | 86.11%  |
| 1      | 5        | 13.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 36       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 7        | 18.92%  |
| Unknown    | 6        | 16.22%  |
| 0x08701013 | 4        | 10.81%  |
| 0x906ea    | 2        | 5.41%   |
| 0x506e3    | 2        | 5.41%   |
| 0x306c3    | 2        | 5.41%   |
| 0x306a9    | 2        | 5.41%   |
| 0x0a201204 | 2        | 5.41%   |
| 0x0a201009 | 2        | 5.41%   |
| 0xa0653    | 1        | 2.7%    |
| 0x906e9    | 1        | 2.7%    |
| 0x406f1    | 1        | 2.7%    |
| 0x306f2    | 1        | 2.7%    |
| 0x08301025 | 1        | 2.7%    |
| 0x0800820d | 1        | 2.7%    |
| 0x08001137 | 1        | 2.7%    |
| 0x06000852 | 1        | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 13       | 36.11%  |
| Zen 3         | 4        | 11.11%  |
| Skylake       | 3        | 8.33%   |
| KabyLake      | 3        | 8.33%   |
| Haswell       | 3        | 8.33%   |
| Zen+          | 2        | 5.56%   |
| IvyBridge     | 2        | 5.56%   |
| CometLake     | 2        | 5.56%   |
| Zen           | 1        | 2.78%   |
| Piledriver    | 1        | 2.78%   |
| Goldmont plus | 1        | 2.78%   |
| Broadwell     | 1        | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 20       | 50%     |
| AMD    | 13       | 32.5%   |
| Intel  | 7        | 17.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 6        | 15%     |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 5        | 12.5%   |
| Nvidia TU106 [GeForce RTX 2070]                                  | 2        | 5%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 2        | 5%      |
| Nvidia GK104 [GeForce GTX 760]                                   | 2        | 5%      |
| Intel HD Graphics 530                                            | 2        | 5%      |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 2        | 5%      |
| Nvidia TU116 [GeForce GTX 1660 Ti]                               | 1        | 2.5%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                            | 1        | 2.5%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                            | 1        | 2.5%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                            | 1        | 2.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                               | 1        | 2.5%    |
| Nvidia GP104 [GeForce GTX 1080]                                  | 1        | 2.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                  | 1        | 2.5%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                               | 1        | 2.5%    |
| Nvidia GM206 [GeForce GTX 960]                                   | 1        | 2.5%    |
| Nvidia GM204 [GeForce GTX 970]                                   | 1        | 2.5%    |
| Nvidia GM200 [GeForce GTX 980 Ti]                                | 1        | 2.5%    |
| Nvidia GK107 [NVS 510]                                           | 1        | 2.5%    |
| Nvidia GK104 [GeForce GTX 660 Ti]                                | 1        | 2.5%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                   | 1        | 2.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 2.5%    |
| Intel HD Graphics 630                                            | 1        | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                              | 1        | 2.5%    |
| Intel Comet Lake-S GT2 [UHD Graphics P630]                       | 1        | 2.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                        | 1        | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 16       | 44.44%  |
| 1 x AMD        | 10       | 27.78%  |
| 1 x Intel      | 5        | 13.89%  |
| AMD + Nvidia   | 3        | 8.33%   |
| Other          | 1        | 2.78%   |
| Intel + Nvidia | 1        | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 55.56%  |
| Proprietary | 14       | 38.89%  |
| Unknown     | 2        | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 67.57%  |
| 7.01-8.0   | 10       | 27.03%  |
| 1.01-2.0   | 1        | 2.7%    |
| 8.01-16.0  | 1        | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 10       | 29.41%  |
| Goldstar             | 8        | 23.53%  |
| Acer                 | 4        | 11.76%  |
| Ancor Communications | 3        | 8.82%   |
| Vizio                | 1        | 2.94%   |
| Unknown (AAA)        | 1        | 2.94%   |
| Samsung Electronics  | 1        | 2.94%   |
| MPI                  | 1        | 2.94%   |
| Iiyama               | 1        | 2.94%   |
| HVR                  | 1        | 2.94%   |
| Hewlett-Packard      | 1        | 2.94%   |
| BenQ                 | 1        | 2.94%   |
| AOC                  | 1        | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 2        | 5.41%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                        | 2        | 5.41%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                       | 2        | 5.41%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                    | 2        | 5.41%   |
| Vizio E50-C1 VIZ1004 1920x1080 1095x616mm 49.5-inch                     | 1        | 2.7%    |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch             | 1        | 2.7%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 1        | 2.7%    |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                        | 1        | 2.7%    |
| Iiyama PLE2208HDS IVM560A 1920x1080 477x268mm 21.5-inch                 | 1        | 2.7%    |
| HVR HTC-VIVE HVRAA01 2160x1200                                          | 1        | 2.7%    |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch            | 1        | 2.7%    |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch                | 1        | 2.7%    |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch                | 1        | 2.7%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 1        | 2.7%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch             | 1        | 2.7%    |
| Goldstar LG HDR 4K GSM7750 3840x2160 700x400mm 31.7-inch                | 1        | 2.7%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 1        | 2.7%    |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                       | 1        | 2.7%    |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                       | 1        | 2.7%    |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                       | 1        | 2.7%    |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                       | 1        | 2.7%    |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                        | 1        | 2.7%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                       | 1        | 2.7%    |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                      | 1        | 2.7%    |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                       | 1        | 2.7%    |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                       | 1        | 2.7%    |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                         | 1        | 2.7%    |
| AOC 2280W AOC2280 1920x1080 477x268mm 21.5-inch                         | 1        | 2.7%    |
| Ancor Communications VX239 ACI23E1 1920x1080 510x290mm 23.1-inch        | 1        | 2.7%    |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch        | 1        | 2.7%    |
| Ancor Communications ASUS VC239HE ACI23C4 1920x1080 509x286mm 23.0-inch | 1        | 2.7%    |
| Acer G247HYL ACR0427 1920x1080 527x296mm 23.8-inch                      | 1        | 2.7%    |
| Acer AL1717 ACRAD60 1280x1024 338x270mm 17.0-inch                       | 1        | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 12       | 37.5%   |
| 3840x2160 (4K)    | 7        | 21.88%  |
| 2560x1440 (QHD)   | 4        | 12.5%   |
| 2560x1080         | 4        | 12.5%   |
| 1920x1200 (WUXGA) | 2        | 6.25%   |
| 2160x1200         | 1        | 3.13%   |
| 1280x720 (HD)     | 1        | 3.13%   |
| 1280x1024 (SXGA)  | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 21.21%  |
| 23      | 7        | 21.21%  |
| 24      | 6        | 18.18%  |
| 34      | 4        | 12.12%  |
| 25      | 2        | 6.06%   |
| 21      | 2        | 6.06%   |
| 49      | 1        | 3.03%   |
| 31      | 1        | 3.03%   |
| 17      | 1        | 3.03%   |
| 8       | 1        | 3.03%   |
| Unknown | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 19       | 63.33%  |
| 701-800     | 4        | 13.33%  |
| 401-500     | 2        | 6.67%   |
| 601-700     | 1        | 3.33%   |
| 301-350     | 1        | 3.33%   |
| 101-200     | 1        | 3.33%   |
| 1001-1500   | 1        | 3.33%   |
| Unknown     | 1        | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 18       | 64.29%  |
| 21/9  | 4        | 14.29%  |
| 16/10 | 4        | 14.29%  |
| 5/4   | 1        | 3.57%   |
| 4/3   | 1        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 30.3%   |
| 301-350        | 7        | 21.21%  |
| 351-500        | 5        | 15.15%  |
| 251-300        | 5        | 15.15%  |
| 151-200        | 2        | 6.06%   |
| More than 1000 | 1        | 3.03%   |
| 1-40           | 1        | 3.03%   |
| 141-150        | 1        | 3.03%   |
| Unknown        | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 54.84%  |
| 161-240 | 6        | 19.35%  |
| 101-120 | 5        | 16.13%  |
| 1-50    | 1        | 3.23%   |
| 121-160 | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 52.78%  |
| 0     | 8        | 22.22%  |
| 2     | 7        | 19.44%  |
| 3     | 2        | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 24       | 44.44%  |
| Intel                 | 22       | 40.74%  |
| Aquantia              | 2        | 3.7%    |
| TP-Link               | 1        | 1.85%   |
| Texas Instruments     | 1        | 1.85%   |
| Qualcomm Atheros      | 1        | 1.85%   |
| Oculus VR             | 1        | 1.85%   |
| Microsoft             | 1        | 1.85%   |
| MediaTek              | 1        | 1.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 31.58%  |
| Intel Wi-Fi 6 AX200                                               | 6        | 10.53%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 8.77%   |
| Intel I211 Gigabit Network Connection                             | 5        | 8.77%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 3.51%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.51%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 3.51%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 1.75%   |
| Texas Instruments CC2538 USB CDC                                  | 1        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.75%   |
| Oculus VR Rift S                                                  | 1        | 1.75%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.75%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 1.75%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.75%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.75%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.75%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 1.75%   |

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


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                              | 6        | 54.55%  |
| TP-Link 802.11ac WLAN Adapter                    | 1        | 9.09%   |
| Microsoft Xbox 360 Wireless Adapter              | 1        | 9.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz          | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak] | 1        | 9.09%   |
| Intel Comet Lake PCH CNVi WiFi                   | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 24       | 54.55%  |
| Intel                 | 17       | 38.64%  |
| Aquantia              | 2        | 4.55%   |
| Qualcomm Atheros      | 1        | 2.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 40.91%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 11.36%  |
| Intel I211 Gigabit Network Connection                             | 5        | 11.36%  |
| Intel Ethernet Connection (7) I219-V                              | 2        | 4.55%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 4.55%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 4.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 2.27%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.27%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 2.27%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.27%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.27%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.27%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 36       | 73.47%  |
| WiFi     | 11       | 22.45%  |
| Modem    | 2        | 4.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 91.43%  |
| WiFi     | 3        | 8.57%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 58.33%  |
| 2     | 12       | 33.33%  |
| 3     | 2        | 5.56%   |
| 0     | 1        | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 66.67%  |
| Yes  | 12       | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 6        | 35.29%  |
| ASUSTek Computer         | 3        | 17.65%  |
| Realtek Semiconductor    | 2        | 11.76%  |
| Cambridge Silicon Radio  | 2        | 11.76%  |
| Broadcom                 | 2        | 11.76%  |
| MediaTek                 | 1        | 5.88%   |
| HTC (High Tech Computer) | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 4        | 23.53%  |
| Realtek Bluetooth Radio                                              | 2        | 11.76%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 11.76%  |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 11.76%  |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 11.76%  |
| MediaTek Wireless_Device                                             | 1        | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 5.88%   |
| Intel AX201 Bluetooth                                                | 1        | 5.88%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 5.88%   |
| ASUS ASUS USB-BT500                                                  | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 22       | 28.57%  |
| Nvidia                               | 20       | 25.97%  |
| Intel                                | 15       | 19.48%  |
| Texas Instruments                    | 3        | 3.9%    |
| C-Media Electronics                  | 3        | 3.9%    |
| Sennheiser Communications            | 2        | 2.6%    |
| Unknown                              | 1        | 1.3%    |
| Thomann                              | 1        | 1.3%    |
| Thesycon Systemsoftware & Consulting | 1        | 1.3%    |
| Sony                                 | 1        | 1.3%    |
| Schiit Audio                         | 1        | 1.3%    |
| Razer USA                            | 1        | 1.3%    |
| PreSonus Audio Electronics           | 1        | 1.3%    |
| Kingston Technology                  | 1        | 1.3%    |
| GYROCOM C&C                          | 1        | 1.3%    |
| Creative Technology                  | 1        | 1.3%    |
| Creative Labs                        | 1        | 1.3%    |
| Antlion Audio                        | 1        | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 16       | 18.18%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 6        | 6.82%   |
| AMD Navi 10 HDMI Audio                                              | 5        | 5.68%   |
| Nvidia TU106 High Definition Audio Controller                       | 3        | 3.41%   |
| Nvidia GK104 HDMI Audio Controller                                  | 3        | 3.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 3        | 3.41%   |
| Texas Instruments PCM2902 Audio Codec                               | 2        | 2.27%   |
| Nvidia TU116 High Definition Audio Controller                       | 2        | 2.27%   |
| Nvidia GP106 High Definition Audio Controller                       | 2        | 2.27%   |
| Nvidia GP104 High Definition Audio Controller                       | 2        | 2.27%   |
| Intel Comet Lake PCH cAVS                                           | 2        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                          | 2        | 2.27%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2        | 2.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2        | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2        | 2.27%   |
| Intel 200 Series PCH HD Audio                                       | 2        | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2        | 2.27%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2        | 2.27%   |
| Unknown USB Audio                                                   | 1        | 1.14%   |
| Thomann SC450USB                                                    | 1        | 1.14%   |
| Thesycon Systemsoftware & Consulting D90                            | 1        | 1.14%   |
| Texas Instruments PCM2902C Audio CODEC                              | 1        | 1.14%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1        | 1.14%   |
| Sennheiser Communications Sennheiser SC630 for Lync                 | 1        | 1.14%   |
| Sennheiser Communications Headset [PC 8]                            | 1        | 1.14%   |
| Schiit Audio Schiit Modi 3+                                         | 1        | 1.14%   |
| Razer USA Razer BlackShark V2 Pro                                   | 1        | 1.14%   |
| PreSonus Audio Electronics AudioBox                                 | 1        | 1.14%   |
| Nvidia TU104 HD Audio Controller                                    | 1        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1        | 1.14%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1        | 1.14%   |
| Nvidia GM206 High Definition Audio Controller                       | 1        | 1.14%   |
| Nvidia GM204 High Definition Audio Controller                       | 1        | 1.14%   |
| Nvidia GM200 High Definition Audio                                  | 1        | 1.14%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1        | 1.14%   |
| Nvidia GA106 High Definition Audio Controller                       | 1        | 1.14%   |
| Kingston Technology HyperX 7.1 Audio                                | 1        | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1        | 1.14%   |
| GYROCOM C&C Fiio E10                                                | 1        | 1.14%   |
| Creative Technology Sound BlasterX G1                               | 1        | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 13       | 31.71%  |
| Kingston            | 9        | 21.95%  |
| G.Skill             | 6        | 14.63%  |
| Samsung Electronics | 3        | 7.32%   |
| Micron Technology   | 3        | 7.32%   |
| Crucial             | 3        | 7.32%   |
| Unknown (ABCD)      | 1        | 2.44%   |
| Unknown             | 1        | 2.44%   |
| Strontium           | 1        | 2.44%   |
| Goodram             | 1        | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s       | 3        | 6.67%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 2        | 4.44%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 2        | 4.44%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s          | 2        | 4.44%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 2        | 4.44%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s       | 2        | 4.44%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                | 1        | 2.22%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 2.22%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s           | 1        | 2.22%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s               | 1        | 2.22%   |
| Samsung RAM M393A4K40BB0-CPB 32GB RIMM DDR4 2133MT/s         | 1        | 2.22%   |
| Samsung RAM M391A1K43BB1-CRC 8GB DIMM DDR4 2400MT/s          | 1        | 2.22%   |
| Micron RAM 4ATF1G64AZ-3G2E1 8GB DIMM DDR4 3200MT/s           | 1        | 2.22%   |
| Micron RAM 36ASF4G72PZ-2G1A1 32GB RIMM DDR4 2133MT/s         | 1        | 2.22%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16384MB DIMM DDR4 3200MT/s      | 1        | 2.22%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s      | 1        | 2.22%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 1        | 2.22%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s          | 1        | 2.22%   |
| Kingston RAM 9965745-021.A00G 32GB DIMM DDR4 2933MT/s        | 1        | 2.22%   |
| Kingston RAM 9965684-028.A00G 8GB DIMM DDR4 3200MT/s         | 1        | 2.22%   |
| Kingston RAM 9965669-008.A03G 16GB DIMM DDR4 2134MT/s        | 1        | 2.22%   |
| Goodram RAM GR1600D364L9/4G 4096MB DIMM DDR3 1333MT/s        | 1        | 2.22%   |
| Goodram RAM GR1600D364L11/4G 4GB DIMM DDR3 1600MT/s          | 1        | 2.22%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 1        | 2.22%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 1        | 2.22%   |
| G.Skill RAM F3-2133C10-8GXM 8GB DIMM DDR3 2132MT/s           | 1        | 2.22%   |
| G.Skill RAM F3-1600C9-8GSR 8GB DIMM DDR3 1333MT/s            | 1        | 2.22%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s        | 1        | 2.22%   |
| Crucial RAM BLS16G4D32AESE.M16FE 16GB DIMM DDR4 3733MT/s     | 1        | 2.22%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s     | 1        | 2.22%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s        | 1        | 2.22%   |
| Corsair RAM CMY16GX3M2A2400C11 8GB DIMM DDR3 2400MT/s        | 1        | 2.22%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s        | 1        | 2.22%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s       | 1        | 2.22%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 1        | 2.22%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s       | 1        | 2.22%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s        | 1        | 2.22%   |
| Corsair RAM CMD64GX4M4A2666C15 16384MB DIMM DDR4 2133MT/s    | 1        | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 29       | 82.86%  |
| DDR3   | 5        | 14.29%  |
| LPDDR4 | 1        | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 33       | 94.29%  |
| SODIMM | 1        | 2.86%   |
| RIMM   | 1        | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 16       | 41.03%  |
| 8192  | 14       | 35.9%   |
| 32768 | 7        | 17.95%  |
| 4096  | 2        | 5.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 12       | 28.57%  |
| 3600  | 6        | 14.29%  |
| 2400  | 4        | 9.52%   |
| 2133  | 4        | 9.52%   |
| 3000  | 3        | 7.14%   |
| 1600  | 3        | 7.14%   |
| 3733  | 2        | 4.76%   |
| 3334  | 2        | 4.76%   |
| 3866  | 1        | 2.38%   |
| 3400  | 1        | 2.38%   |
| 2933  | 1        | 2.38%   |
| 2134  | 1        | 2.38%   |
| 2132  | 1        | 2.38%   |
| 1333  | 1        | 2.38%   |

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
| Logitech     | 6        | 60%     |
| MacroSilicon | 2        | 20%     |
| Microdia     | 1        | 10%     |
| Apple        | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| MacroSilicon USB Video      | 2        | 20%     |
| Microdia Camera             | 1        | 10%     |
| Logitech Webcam C930e       | 1        | 10%     |
| Logitech Webcam C270        | 1        | 10%     |
| Logitech Webcam C120        | 1        | 10%     |
| Logitech StreamCam          | 1        | 10%     |
| Logitech HD Pro Webcam C920 | 1        | 10%     |
| Logitech C930c              | 1        | 10%     |
| Apple iPhone 5/5C/5S/6/SE   | 1        | 10%     |

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
| 0     | 27       | 72.97%  |
| 1     | 8        | 21.62%  |
| 2     | 2        | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 30%     |
| Net/wireless     | 2        | 20%     |
| Bluetooth        | 2        | 20%     |
| Graphics card    | 1        | 10%     |
| Dvb card         | 1        | 10%     |
| Camera           | 1        | 10%     |

