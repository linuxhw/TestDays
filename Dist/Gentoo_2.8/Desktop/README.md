Gentoo 2.8 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 50

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock   | Z170A-X1                    | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI      | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Gigabyte | Z590 UD                     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [f4e6e46fc5](https://linux-hardware.org/?probe=f4e6e46fc5) | Mar 23, 2022 |
| ASUSTek  | ROG STRIX Z370-H GAMING     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| MSI      | MAG B550M MORTAR            | [78b6d2b02e](https://linux-hardware.org/?probe=78b6d2b02e) | Mar 21, 2022 |
| MSI      | MAG B550M MORTAR            | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| ASUSTek  | Z170 PRO GAMING             | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| Dell     | 0J37VM A00                  | [bbcd3639ab](https://linux-hardware.org/?probe=bbcd3639ab) | Mar 15, 2022 |
| ASUSTek  | ROG STRIX Z390-E GAMING     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| Dell     | 0J37VM A00                  | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| Gigabyte | Z590 UD                     | [392c7890c2](https://linux-hardware.org/?probe=392c7890c2) | Mar 08, 2022 |
| ASUSTek  | TUF GAMING X570-PRO         | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| Gigabyte | Z590 UD                     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Gigabyte | Z590 UD                     | [06d8d67698](https://linux-hardware.org/?probe=06d8d67698) | Feb 24, 2022 |
| Gigabyte | Z590 UD                     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| Gigabyte | Z490 UD                     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| ASRock   | AB350M Pro4                 | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Gigabyte | B450M S2H                   | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Gigabyte | B450M S2H                   | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Gigabyte | Z490 UD                     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| ASRock   | X370 Gaming X               | [e233d7c495](https://linux-hardware.org/?probe=e233d7c495) | Jan 09, 2022 |
| EVGA     | Z390 DARK                   | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| ASUSTek  | P5LD2-Deluxe                | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock   | H110M-HDV R3.0              | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| ASUSTek  | PRIME X570-P                | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek  | TUF GAMING B550-PLUS        | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| ASUSTek  | ROG ZENITH II EXTREME       | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| MSI      | H110M PRO-D                 | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI      | H110M PRO-D                 | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek  | Z170-A                      | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [cb6d9e548b](https://linux-hardware.org/?probe=cb6d9e548b) | Oct 26, 2021 |
| Gigabyte | X570 AORUS MASTER           | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock   | X370 Killer SLI/ac          | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Gigabyte | Z87X-UD3H-CF                | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.10-gentoo               | 3        | 8.57%   |
| 5.14.12-gentoo               | 2        | 5.71%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1        | 2.86%   |
| 5.17.1-gentoo-r1             | 1        | 2.86%   |
| 5.17.0-gentoo-x86_64         | 1        | 2.86%   |
| 5.17.0-gentoo                | 1        | 2.86%   |
| 5.16.8-gentoo-x86_64         | 1        | 2.86%   |
| 5.16.7-tkg-cacule            | 1        | 2.86%   |
| 5.16.5-gentoo-dist           | 1        | 2.86%   |
| 5.16.4-gentoo                | 1        | 2.86%   |
| 5.16.2-gentoo                | 1        | 2.86%   |
| 5.16.15                      | 1        | 2.86%   |
| 5.16.14-gentoo-x86_64        | 1        | 2.86%   |
| 5.16.14-gentoo-girlhog       | 1        | 2.86%   |
| 5.16.12-gentoo-x86_64        | 1        | 2.86%   |
| 5.16.11-gentoo-x86_64        | 1        | 2.86%   |
| 5.16.10-gentoo-x86_64        | 1        | 2.86%   |
| 5.15.6-gentoo                | 1        | 2.86%   |
| 5.15.4-gentoo-deimos         | 1        | 2.86%   |
| 5.15.2-gentoo20210917        | 1        | 2.86%   |
| 5.15.2-gentoo-x86_64         | 1        | 2.86%   |
| 5.15.16-gentoo-dist          | 1        | 2.86%   |
| 5.15.1-gentoo-x86_64         | 1        | 2.86%   |
| 5.15.0-gentoo-x86_64         | 1        | 2.86%   |
| 5.14.6                       | 1        | 2.86%   |
| 5.14.15-gentoo20210917       | 1        | 2.86%   |
| 5.14.14-gentoo-x86_64        | 1        | 2.86%   |
| 5.14.14-gentoo               | 1        | 2.86%   |
| 5.14.13-gentoo               | 1        | 2.86%   |
| 5.14.11-zen1                 | 1        | 2.86%   |
| 5.10.84-gentoo-112-overlayfs | 1        | 2.86%   |
| 5.10.74-gentoo-x86_64        | 1        | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.10 | 3        | 8.57%   |
| 5.17.0  | 2        | 5.71%   |
| 5.16.14 | 2        | 5.71%   |
| 5.15.2  | 2        | 5.71%   |
| 5.14.14 | 2        | 5.71%   |
| 5.14.12 | 2        | 5.71%   |
| 6.0.0   | 1        | 2.86%   |
| 5.17.1  | 1        | 2.86%   |
| 5.16.8  | 1        | 2.86%   |
| 5.16.7  | 1        | 2.86%   |
| 5.16.5  | 1        | 2.86%   |
| 5.16.4  | 1        | 2.86%   |
| 5.16.2  | 1        | 2.86%   |
| 5.16.15 | 1        | 2.86%   |
| 5.16.12 | 1        | 2.86%   |
| 5.16.11 | 1        | 2.86%   |
| 5.16.10 | 1        | 2.86%   |
| 5.15.6  | 1        | 2.86%   |
| 5.15.4  | 1        | 2.86%   |
| 5.15.16 | 1        | 2.86%   |
| 5.15.1  | 1        | 2.86%   |
| 5.15.0  | 1        | 2.86%   |
| 5.14.6  | 1        | 2.86%   |
| 5.14.15 | 1        | 2.86%   |
| 5.14.13 | 1        | 2.86%   |
| 5.14.11 | 1        | 2.86%   |
| 5.10.84 | 1        | 2.86%   |
| 5.10.74 | 1        | 2.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 10       | 29.41%  |
| 5.15    | 10       | 29.41%  |
| 5.14    | 8        | 23.53%  |
| 5.17    | 3        | 8.82%   |
| 5.10    | 2        | 5.88%   |
| 6.0     | 1        | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 30       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 15       | 48.39%  |
| GNOME   | 6        | 19.35%  |
| Unknown | 6        | 19.35%  |
| XFCE    | 2        | 6.45%   |
| LXQt    | 1        | 3.23%   |
| KDE     | 1        | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 15       | 48.39%  |
| Wayland | 8        | 25.81%  |
| Tty     | 6        | 19.35%  |
| Unknown | 2        | 6.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 13       | 41.94%  |
| Unknown | 13       | 41.94%  |
| GDM     | 4        | 12.9%   |
| LXDM    | 1        | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 11       | 36.67%  |
| en_GB   | 6        | 20%     |
| ru_RU   | 2        | 6.67%   |
| pl_PL   | 2        | 6.67%   |
| Unknown | 2        | 6.67%   |
| sl_SI   | 1        | 3.33%   |
| fr_FR   | 1        | 3.33%   |
| es_ES   | 1        | 3.33%   |
| el_GR   | 1        | 3.33%   |
| de_DE   | 1        | 3.33%   |
| de_CH   | 1        | 3.33%   |
| C.UTF8  | 1        | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 26       | 83.87%  |
| BIOS | 5        | 16.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 17       | 56.67%  |
| Btrfs | 10       | 33.33%  |
| F2fs  | 2        | 6.67%   |
| Zfs   | 1        | 3.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 27       | 87.1%   |
| Unknown | 4        | 12.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 60%     |
| Yes       | 12       | 40%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 63.33%  |
| Yes       | 11       | 36.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 14       | 46.67%  |
| Gigabyte Technology | 5        | 16.67%  |
| ASRock              | 5        | 16.67%  |
| MSI                 | 4        | 13.33%  |
| EVGA                | 1        | 3.33%   |
| Dell                | 1        | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| MSI MS-7D31                       | 1        | 3.33%   |
| MSI MS-7C94                       | 1        | 3.33%   |
| MSI MS-7C56                       | 1        | 3.33%   |
| MSI MS-7996                       | 1        | 3.33%   |
| Gigabyte Z87X-UD3H                | 1        | 3.33%   |
| Gigabyte Z590 UD                  | 1        | 3.33%   |
| Gigabyte Z490 UD                  | 1        | 3.33%   |
| Gigabyte X570 AORUS MASTER        | 1        | 3.33%   |
| Gigabyte B450M S2H                | 1        | 3.33%   |
| EVGA Z390 DARK                    | 1        | 3.33%   |
| Dell OptiPlex 7080                | 1        | 3.33%   |
| ASUS Z170-A                       | 1        | 3.33%   |
| ASUS Z170 PRO GAMING              | 1        | 3.33%   |
| ASUS TUF GAMING X570-PRO          | 1        | 3.33%   |
| ASUS TUF GAMING B550-PLUS         | 1        | 3.33%   |
| ASUS TUF B450-PLUS GAMING         | 1        | 3.33%   |
| ASUS ROG ZENITH II EXTREME        | 1        | 3.33%   |
| ASUS ROG STRIX Z390-E GAMING      | 1        | 3.33%   |
| ASUS ROG STRIX Z370-H GAMING      | 1        | 3.33%   |
| ASUS ROG STRIX X570-E GAMING      | 1        | 3.33%   |
| ASUS ROG STRIX B550-F GAMING      | 1        | 3.33%   |
| ASUS ROG CROSSHAIR VIII HERO      | 1        | 3.33%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 1        | 3.33%   |
| ASUS PRIME X570-P                 | 1        | 3.33%   |
| ASUS P5LD2-Deluxe                 | 1        | 3.33%   |
| ASRock Z170A-X1                   | 1        | 3.33%   |
| ASRock X370 Killer SLI/ac         | 1        | 3.33%   |
| ASRock X370 Gaming X              | 1        | 3.33%   |
| ASRock H110M-HDV R3.0             | 1        | 3.33%   |
| ASRock AB350M Pro4                | 1        | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS ROG           | 7        | 23.33%  |
| ASUS TUF           | 3        | 10%     |
| ASRock X370        | 2        | 6.67%   |
| MSI MS-7D31        | 1        | 3.33%   |
| MSI MS-7C94        | 1        | 3.33%   |
| MSI MS-7C56        | 1        | 3.33%   |
| MSI MS-7996        | 1        | 3.33%   |
| Gigabyte Z87X-UD3H | 1        | 3.33%   |
| Gigabyte Z590      | 1        | 3.33%   |
| Gigabyte Z490      | 1        | 3.33%   |
| Gigabyte X570      | 1        | 3.33%   |
| Gigabyte B450M     | 1        | 3.33%   |
| EVGA Z390          | 1        | 3.33%   |
| Dell OptiPlex      | 1        | 3.33%   |
| ASUS Z170-A        | 1        | 3.33%   |
| ASUS Z170          | 1        | 3.33%   |
| ASUS PRIME         | 1        | 3.33%   |
| ASUS P5LD2-Deluxe  | 1        | 3.33%   |
| ASRock Z170A-X1    | 1        | 3.33%   |
| ASRock H110M-HDV   | 1        | 3.33%   |
| ASRock AB350M      | 1        | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 8        | 26.67%  |
| 2019 | 5        | 16.67%  |
| 2017 | 4        | 13.33%  |
| 2021 | 3        | 10%     |
| 2016 | 3        | 10%     |
| 2018 | 2        | 6.67%   |
| 2015 | 2        | 6.67%   |
| 2022 | 1        | 3.33%   |
| 2013 | 1        | 3.33%   |
| 2005 | 1        | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 30       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 29       | 96.67%  |
| Enabled  | 1        | 3.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 12       | 40%     |
| 64.01-256.0 | 7        | 23.33%  |
| 16.01-24.0  | 6        | 20%     |
| 24.01-32.0  | 3        | 10%     |
| 2.01-3.0    | 1        | 3.33%   |
| 8.01-16.0   | 1        | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 11       | 35.48%  |
| 8.01-16.0  | 7        | 22.58%  |
| 1.01-2.0   | 5        | 16.13%  |
| 3.01-4.0   | 2        | 6.45%   |
| 2.01-3.0   | 2        | 6.45%   |
| 16.01-24.0 | 2        | 6.45%   |
| 24.01-32.0 | 1        | 3.23%   |
| 0.51-1.0   | 1        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 9        | 29.03%  |
| 5      | 6        | 19.35%  |
| 2      | 6        | 19.35%  |
| 4      | 4        | 12.9%   |
| 1      | 3        | 9.68%   |
| 6      | 2        | 6.45%   |
| 7      | 1        | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 83.33%  |
| Yes       | 5        | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 96.67%  |
| No        | 1        | 3.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 53.33%  |
| Yes       | 14       | 46.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 58.06%  |
| No        | 13       | 41.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 23.33%  |
| Russia      | 4        | 13.33%  |
| Poland      | 4        | 13.33%  |
| UK          | 2        | 6.67%   |
| Spain       | 2        | 6.67%   |
| Germany     | 2        | 6.67%   |
| Switzerland | 1        | 3.33%   |
| Slovenia    | 1        | 3.33%   |
| Mexico      | 1        | 3.33%   |
| Ireland     | 1        | 3.33%   |
| Hong Kong   | 1        | 3.33%   |
| Greece      | 1        | 3.33%   |
| France      | 1        | 3.33%   |
| Czechia     | 1        | 3.33%   |
| Bangladesh  | 1        | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Swansea           | 2        | 6.45%   |
| Moscow            | 2        | 6.45%   |
| Zurich            | 1        | 3.23%   |
| Vigo              | 1        | 3.23%   |
| Ufa               | 1        | 3.23%   |
| Svobodnyy         | 1        | 3.23%   |
| RzeszÃ³w        | 1        | 3.23%   |
| Redmond           | 1        | 3.23%   |
| Prague            | 1        | 3.23%   |
| Orange            | 1        | 3.23%   |
| Morcenx           | 1        | 3.23%   |
| Monroe            | 1        | 3.23%   |
| Los Angeles       | 1        | 3.23%   |
| Laziska Gorne     | 1        | 3.23%   |
| Kulmbach          | 1        | 3.23%   |
| Krakow            | 1        | 3.23%   |
| IvanÄna Gorica | 1        | 3.23%   |
| Hyannis           | 1        | 3.23%   |
| Glen Ellyn        | 1        | 3.23%   |
| Fort Collins      | 1        | 3.23%   |
| Essen             | 1        | 3.23%   |
| Dublin            | 1        | 3.23%   |
| Dhaka             | 1        | 3.23%   |
| Ciudad JuÃ¡rez  | 1        | 3.23%   |
| Cieszyn           | 1        | 3.23%   |
| Central           | 1        | 3.23%   |
| Blagoveshchensk   | 1        | 3.23%   |
| Bellaterra        | 1        | 3.23%   |
| Athens            | 1        | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 32     | 23.68%  |
| Samsung Electronics | 16       | 30     | 21.05%  |
| Seagate             | 9        | 14     | 11.84%  |
| Toshiba             | 5        | 5      | 6.58%   |
| SanDisk             | 4        | 5      | 5.26%   |
| Kingston            | 3        | 3      | 3.95%   |
| Hitachi             | 3        | 4      | 3.95%   |
| KIOXIA-EXCERIA      | 2        | 3      | 2.63%   |
| Intel               | 2        | 3      | 2.63%   |
| Crucial             | 2        | 6      | 2.63%   |
| Corsair             | 2        | 2      | 2.63%   |
| Team                | 1        | 2      | 1.32%   |
| SK Hynix            | 1        | 1      | 1.32%   |
| PNY                 | 1        | 1      | 1.32%   |
| PLEXTOR             | 1        | 2      | 1.32%   |
| Phison              | 1        | 1      | 1.32%   |
| OCZ-VERTEX          | 1        | 1      | 1.32%   |
| Kingchuxing         | 1        | 2      | 1.32%   |
| HGST                | 1        | 1      | 1.32%   |
| GOODRAM             | 1        | 1      | 1.32%   |
| A-DATA Technology   | 1        | 1      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| WDC WD30EFRX-68EUZN0 3TB                   | 2        | 2.04%   |
| WDC WD10EZEX-08M2NA0 1TB                   | 2        | 2.04%   |
| Toshiba DT01ACA100 1TB                     | 2        | 2.04%   |
| Seagate ST2000DM001-1ER164 2TB             | 2        | 2.04%   |
| Samsung SSD 970 EVO Plus 250GB             | 2        | 2.04%   |
| Samsung NVMe SSD Drive 512GB               | 2        | 2.04%   |
| WDC WDS500G2X0C-00L350 500GB               | 1        | 1.02%   |
| WDC WDS500G2B0B-00YS70 500GB SSD           | 1        | 1.02%   |
| WDC WDS500G2B0A-00SM50 500GB SSD           | 1        | 1.02%   |
| WDC WDS240G2G0A 240GB SSD                  | 1        | 1.02%   |
| WDC WDS100T2B0A-00SM50 1TB SSD             | 1        | 1.02%   |
| WDC WD8003FFBX-68B9AN0 8TB                 | 1        | 1.02%   |
| WDC WD60EZRX-00MVLB1 6TB                   | 1        | 1.02%   |
| WDC WD60EFRX-68L0BN1 6TB                   | 1        | 1.02%   |
| WDC WD5000AZLX-00JKKA0 500GB               | 1        | 1.02%   |
| WDC WD30EFRX-68AX9N0 3TB                   | 1        | 1.02%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1.02%   |
| WDC WD20EFRX-68EUZN0 2TB                   | 1        | 1.02%   |
| WDC WD2003FZEX-00Z4SA0 2TB                 | 1        | 1.02%   |
| WDC WD10PURX-64E5EY0 1TB                   | 1        | 1.02%   |
| WDC WD10EZEX-60WN4A1 1TB                   | 1        | 1.02%   |
| WDC WD10EZEX-22M                           | 1        | 1.02%   |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 1.02%   |
| WDC WD10EARS-00MVWB0 1TB                   | 1        | 1.02%   |
| WDC WD10EADS-00L5B1 1TB                    | 1        | 1.02%   |
| WDC WD1002FBYS-18W8B0 1TB                  | 1        | 1.02%   |
| WDC WD1001FALS-00J7B1 1TB                  | 1        | 1.02%   |
| Toshiba TR200 480GB SSD                    | 1        | 1.02%   |
| Toshiba THNSN5512GPUK NVMe 512GB           | 1        | 1.02%   |
| Toshiba HDWQ140 4TB                        | 1        | 1.02%   |
| Team TM8FP2240G 240GB                      | 1        | 1.02%   |
| SK Hynix PC611 NVMe 512GB                  | 1        | 1.02%   |
| Seagate ST8000DM004-2CX188 8TB             | 1        | 1.02%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 1.02%   |
| Seagate ST4000DM005-2DP166 4TB             | 1        | 1.02%   |
| Seagate ST4000DM004-2CV104 4TB             | 1        | 1.02%   |
| Seagate ST4000DM000-1F2168 4TB             | 1        | 1.02%   |
| Seagate ST3500630AS 500GB                  | 1        | 1.02%   |
| Seagate ST3250318AS 250GB                  | 1        | 1.02%   |
| Seagate ST3160023AS 160GB                  | 1        | 1.02%   |
| Seagate ST2000LX001-1RG174 2TB             | 1        | 1.02%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 1.02%   |
| SanDisk Ultra II 480GB SSD                 | 1        | 1.02%   |
| SanDisk SSD PLUS 240GB                     | 1        | 1.02%   |
| SanDisk SSD PLUS 1000GB                    | 1        | 1.02%   |
| SanDisk SDSSDHII480G 480GB                 | 1        | 1.02%   |
| Samsung SSD 980 PRO 2TB                    | 1        | 1.02%   |
| Samsung SSD 980 PRO 1TB                    | 1        | 1.02%   |
| Samsung SSD 980 1TB                        | 1        | 1.02%   |
| Samsung SSD 970 PRO 512GB                  | 1        | 1.02%   |
| Samsung SSD 970 EVO Plus 2TB               | 1        | 1.02%   |
| Samsung SSD 970 EVO Plus 1TB               | 1        | 1.02%   |
| Samsung SSD 970 EVO 500GB                  | 1        | 1.02%   |
| Samsung SSD 860 QVO 4TB                    | 1        | 1.02%   |
| Samsung SSD 860 QVO 2TB                    | 1        | 1.02%   |
| Samsung SSD 860 QVO 1TB                    | 1        | 1.02%   |
| Samsung SSD 860 PRO 1TB                    | 1        | 1.02%   |
| Samsung SSD 860 EVO 2TB                    | 1        | 1.02%   |
| Samsung SSD 850 PRO 256GB                  | 1        | 1.02%   |
| Samsung SSD 850 EVO 500GB                  | 1        | 1.02%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 15       | 27     | 50%     |
| Seagate | 8        | 13     | 26.67%  |
| Toshiba | 3        | 3      | 10%     |
| Hitachi | 3        | 4      | 10%     |
| HGST    | 1        | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 12     | 35.71%  |
| WDC                 | 4        | 4      | 14.29%  |
| SanDisk             | 4        | 5      | 14.29%  |
| Kingston            | 3        | 3      | 10.71%  |
| Toshiba             | 1        | 1      | 3.57%   |
| PNY                 | 1        | 1      | 3.57%   |
| OCZ-VERTEX          | 1        | 1      | 3.57%   |
| Intel               | 1        | 1      | 3.57%   |
| GOODRAM             | 1        | 1      | 3.57%   |
| Crucial             | 1        | 4      | 3.57%   |
| Corsair             | 1        | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 22       | 34     | 35.48%  |
| NVMe | 20       | 38     | 32.26%  |
| HDD  | 20       | 48     | 32.26%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 28       | 82     | 58.33%  |
| NVMe | 20       | 38     | 41.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 16       | 25     | 32.65%  |
| 0.51-1.0   | 15       | 23     | 30.61%  |
| 1.01-2.0   | 9        | 13     | 18.37%  |
| 3.01-4.0   | 5        | 7      | 10.2%   |
| 2.01-3.0   | 2        | 5      | 4.08%   |
| 4.01-10.0  | 2        | 9      | 4.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 8        | 25.81%  |
| More than 3000 | 6        | 19.35%  |
| 1001-2000      | 6        | 19.35%  |
| 251-500        | 4        | 12.9%   |
| 2001-3000      | 2        | 6.45%   |
| 1-20           | 2        | 6.45%   |
| 101-250        | 1        | 3.23%   |
| 51-100         | 1        | 3.23%   |
| Unknown        | 1        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 9        | 29.03%  |
| More than 3000 | 4        | 12.9%   |
| 1001-2000      | 4        | 12.9%   |
| 501-1000       | 4        | 12.9%   |
| 1-20           | 3        | 9.68%   |
| 21-50          | 2        | 6.45%   |
| 51-100         | 2        | 6.45%   |
| 2001-3000      | 1        | 3.23%   |
| 101-250        | 1        | 3.23%   |
| Unknown        | 1        | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB       | 1        | 3      | 10%     |
| WDC WD30EFRX-68AX9N0 3TB       | 1        | 2      | 10%     |
| WDC WD20EZRX-00D8PB0 2TB       | 1        | 1      | 10%     |
| WDC WD1002FBYS-18W8B0 1TB      | 1        | 1      | 10%     |
| Seagate ST3160023AS 160GB      | 1        | 1      | 10%     |
| SanDisk SSD PLUS 1000GB        | 1        | 1      | 10%     |
| Kingston SV100S2128G 128GB SSD | 1        | 1      | 10%     |
| Hitachi HUA721010KLA330 1TB    | 1        | 1      | 10%     |
| Hitachi HDS722020ALA330 2TB    | 1        | 2      | 10%     |
| Crucial CT525MX300SSD1 528GB   | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 4        | 7      | 40%     |
| Hitachi  | 2        | 3      | 20%     |
| Seagate  | 1        | 1      | 10%     |
| SanDisk  | 1        | 1      | 10%     |
| Kingston | 1        | 1      | 10%     |
| Crucial  | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 7      | 57.14%  |
| Hitachi | 2        | 3      | 28.57%  |
| Seagate | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 11     | 62.5%   |
| SSD  | 3        | 3      | 37.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 27       | 91     | 67.5%   |
| Malfunc  | 8        | 14     | 20%     |
| Detected | 4        | 14     | 10%     |
| Failed   | 1        | 1      | 2.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 16       | 27.12%  |
| Intel                          | 14       | 23.73%  |
| Samsung Electronics            | 11       | 18.64%  |
| Phison Electronics             | 3        | 5.08%   |
| ASMedia Technology             | 3        | 5.08%   |
| KIOXIA                         | 2        | 3.39%   |
| Toshiba America Info Systems   | 1        | 1.69%   |
| Solid State Storage Technology | 1        | 1.69%   |
| SK Hynix                       | 1        | 1.69%   |
| Silicon Motion                 | 1        | 1.69%   |
| Silicon Image                  | 1        | 1.69%   |
| Seagate Technology             | 1        | 1.69%   |
| Sandisk                        | 1        | 1.69%   |
| Micron/Crucial Technology      | 1        | 1.69%   |
| Marvell Technology Group       | 1        | 1.69%   |
| ADATA Technology               | 1        | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12       | 18.18%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8        | 12.12%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 7.58%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 6.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 4.55%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 4.55%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 3.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 3.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 3.03%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 3.03%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 1.52%   |
| Solid State Storage Non-Volatile memory controller                             | 1        | 1.52%   |
| SK Hynix Non-Volatile memory controller                                        | 1        | 1.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.52%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 1.52%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 1.52%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 1.52%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.52%   |
| Phison E7 NVMe Controller                                                      | 1        | 1.52%   |
| Micron/Crucial NVMe Controller                                                 | 1        | 1.52%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.52%   |
| KIOXIA NVMe SSD                                                                | 1        | 1.52%   |
| KIOXIA Non-Volatile memory controller                                          | 1        | 1.52%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.52%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 1.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.52%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 1.52%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 1.52%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 29       | 56.86%  |
| NVMe | 20       | 39.22%  |
| RAID | 1        | 1.96%   |
| IDE  | 1        | 1.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 16       | 53.33%  |
| Intel  | 14       | 46.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 9 3950X 16-Core Processor            | 3        | 10%     |
| Intel Core i9-9900K CPU @ 3.60GHz              | 2        | 6.67%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 6.67%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 2        | 6.67%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 6.67%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 3.33%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 3.33%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 3.33%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 3.33%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 3.33%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 3.33%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 3.33%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 3.33%   |
| Intel 12th Gen Core i7-12700K                  | 1        | 3.33%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 3.33%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 3.33%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 3.33%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 3.33%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1        | 3.33%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 3.33%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 3.33%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1        | 3.33%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 3.33%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 9            | 7        | 23.33%  |
| Intel Core i7          | 5        | 16.67%  |
| Intel Core i5          | 4        | 13.33%  |
| AMD Ryzen 5            | 4        | 13.33%  |
| AMD Ryzen 7            | 3        | 10%     |
| Other                  | 2        | 6.67%   |
| Intel Core i9          | 2        | 6.67%   |
| Intel Pentium 4        | 1        | 3.33%   |
| AMD Ryzen Threadripper | 1        | 3.33%   |
| AMD Ryzen 7 PRO        | 1        | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 8      | 9        | 30%     |
| 4      | 6        | 20%     |
| 6      | 5        | 16.67%  |
| 16     | 4        | 13.33%  |
| 12     | 4        | 13.33%  |
| 24     | 1        | 3.33%   |
| 1      | 1        | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 26       | 86.67%  |
| 1      | 4        | 13.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 30       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 5        | 16.13%  |
| Unknown    | 5        | 16.13%  |
| 0x506e3    | 3        | 9.68%   |
| 0x08001138 | 3        | 9.68%   |
| 0xa0655    | 2        | 6.45%   |
| 0x906ed    | 2        | 6.45%   |
| 0x0a201016 | 2        | 6.45%   |
| 0xf43      | 1        | 3.23%   |
| 0xa0671    | 1        | 3.23%   |
| 0x906e9    | 1        | 3.23%   |
| 0x90672    | 1        | 3.23%   |
| 0x0a50000c | 1        | 3.23%   |
| 0x0a50000b | 1        | 3.23%   |
| 0x0a201205 | 1        | 3.23%   |
| 0x08301039 | 1        | 3.23%   |
| 0x0800820d | 1        | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 7        | 23.33%  |
| Zen 3            | 5        | 16.67%  |
| Skylake          | 4        | 13.33%  |
| KabyLake         | 4        | 13.33%  |
| Zen              | 3        | 10%     |
| CometLake        | 2        | 6.67%   |
| Zen+             | 1        | 3.33%   |
| NetBurst         | 1        | 3.33%   |
| Icelake          | 1        | 3.33%   |
| Haswell          | 1        | 3.33%   |
| Alderlake Hybrid | 1        | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 17       | 48.57%  |
| Nvidia | 13       | 37.14%  |
| Intel  | 5        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]             | 7        | 18.92%  |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                      | 3        | 8.11%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                           | 2        | 5.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                 | 2        | 5.41%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                               | 1        | 2.7%    |
| Nvidia TU116 [GeForce GTX 1650]                                     | 1        | 2.7%    |
| Nvidia TU106 [GeForce RTX 2070]                                     | 1        | 2.7%    |
| Nvidia GP108 [GeForce GT 1030]                                      | 1        | 2.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                 | 1        | 2.7%    |
| Nvidia GP104 [GeForce GTX 1070]                                     | 1        | 2.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                  | 1        | 2.7%    |
| Nvidia GM206 [GeForce GTX 960]                                      | 1        | 2.7%    |
| Nvidia GM204 [GeForce GTX 970]                                      | 1        | 2.7%    |
| Nvidia GA106 [Geforce RTX 3050]                                     | 1        | 2.7%    |
| Intel HD Graphics 630                                               | 1        | 2.7%    |
| Intel HD Graphics 530                                               | 1        | 2.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                            | 1        | 2.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                           | 1        | 2.7%    |
| Intel AlderLake-S GT1                                               | 1        | 2.7%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                            | 1        | 2.7%    |
| AMD Turks PRO [Radeon HD 7570]                                      | 1        | 2.7%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                      | 1        | 2.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                | 1        | 2.7%    |
| AMD Cezanne                                                         | 1        | 2.7%    |
| AMD Bonaire XTX [Radeon R7 260X/360]                                | 1        | 2.7%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 2.7%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 1        | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 12       | 40%     |
| 1 x Nvidia     | 9        | 30%     |
| AMD + Nvidia   | 3        | 10%     |
| 1 x Intel      | 2        | 6.67%   |
| Other          | 1        | 3.33%   |
| 2 x AMD        | 1        | 3.33%   |
| Intel + Nvidia | 1        | 3.33%   |
| Intel + AMD    | 1        | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 18       | 60%     |
| Proprietary | 10       | 33.33%  |
| Unknown     | 2        | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 28.13%  |
| 7.01-8.0   | 7        | 21.88%  |
| 8.01-16.0  | 6        | 18.75%  |
| 3.01-4.0   | 4        | 12.5%   |
| 5.01-6.0   | 2        | 6.25%   |
| 1.01-2.0   | 2        | 6.25%   |
| 0.51-1.0   | 2        | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 5        | 11.36%  |
| Lenovo                  | 3        | 6.82%   |
| Hewlett-Packard         | 3        | 6.82%   |
| Goldstar                | 3        | 6.82%   |
| AOC                     | 3        | 6.82%   |
| Philips                 | 2        | 4.55%   |
| Dell                    | 2        | 4.55%   |
| BenQ                    | 2        | 4.55%   |
| ASUSTek Computer        | 2        | 4.55%   |
| Ancor Communications    | 2        | 4.55%   |
| Acer                    | 2        | 4.55%   |
| ViewSonic               | 1        | 2.27%   |
| Valve                   | 1        | 2.27%   |
| Toshiba                 | 1        | 2.27%   |
| Onkyo                   | 1        | 2.27%   |
| NEC Computers           | 1        | 2.27%   |
| MStar                   | 1        | 2.27%   |
| Mi                      | 1        | 2.27%   |
| LYC                     | 1        | 2.27%   |
| KTC                     | 1        | 2.27%   |
| Iiyama                  | 1        | 2.27%   |
| HannStar                | 1        | 2.27%   |
| Gigabyte Technology     | 1        | 2.27%   |
| Gateway                 | 1        | 2.27%   |
| Chi Mei Optoelectronics | 1        | 2.27%   |
| Belinea                 | 1        | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch             | 1        | 2.08%   |
| Valve Index HMD VLV91A8                                                | 1        | 2.08%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                   | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch   | 1        | 2.08%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch    | 1        | 2.08%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch      | 1        | 2.08%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch    | 1        | 2.08%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch     | 1        | 2.08%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 2.08%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch                | 1        | 2.08%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                   | 1        | 2.08%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch           | 1        | 2.08%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                         | 1        | 2.08%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1        | 2.08%   |
| LYC L2106 LYC0001 1920x1080 476x268mm 21.5-inch                        | 1        | 2.08%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                   | 1        | 2.08%   |
| Lenovo M14t LEN62A3 1920x1080 309x174mm 14.0-inch                      | 1        | 2.08%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch               | 1        | 2.08%   |
| KTC Q2711SH KTC2700 2560x1440 597x336mm 27.0-inch                      | 1        | 2.08%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                   | 1        | 2.08%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                   | 1        | 2.08%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch           | 1        | 2.08%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch          | 1        | 2.08%   |
| Hewlett-Packard 27fh HPN354A 1920x1080 598x336mm 27.0-inch             | 1        | 2.08%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch             | 1        | 2.08%   |
| HannStar JC198D HSD0CC6 1280x1024 376x301mm 19.0-inch                  | 1        | 2.08%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 1        | 2.08%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1        | 2.08%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch               | 1        | 2.08%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 1        | 2.08%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 609x355mm 27.8-inch | 1        | 2.08%   |
| Gateway FPD1765 GWY06E9 1280x1024 338x270mm 17.0-inch                  | 1        | 2.08%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 1        | 2.08%   |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                      | 1        | 2.08%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 1        | 2.08%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch  | 1        | 2.08%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 1        | 2.08%   |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                     | 1        | 2.08%   |
| Belinea Belinea101735 MAX06B2 1280x1024 338x270mm 17.0-inch            | 1        | 2.08%   |
| ASUSTek Computer XG27WQ AUS2724 2560x1440 597x336mm 27.0-inch          | 1        | 2.08%   |
| ASUSTek Computer VG27A AUS2723 2560x1440 600x340mm 27.2-inch           | 1        | 2.08%   |
| AOC 2757 AOC2757 1920x1080 598x336mm 27.0-inch                         | 1        | 2.08%   |
| AOC 2437 AOC2437 1920x1080 521x293mm 23.5-inch                         | 1        | 2.08%   |
| AOC 2269W AOC2269 1920x1080 480x270mm 21.7-inch                        | 1        | 2.08%   |
| Ancor Communications VN279 ACI27A4 1920x1080 597x336mm 27.0-inch       | 1        | 2.08%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 1        | 2.08%   |
| Acer VG270U P ACR06CF 2560x1440 600x340mm 27.2-inch                    | 1        | 2.08%   |
| Acer K272HUL ACR03DD 2560x1440 597x336mm 27.0-inch                     | 1        | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 2560x1440 (QHD)    | 13       | 31.71%  |
| 1920x1080 (FHD)    | 13       | 31.71%  |
| 3840x2160 (4K)     | 4        | 9.76%   |
| 3440x1440          | 2        | 4.88%   |
| 1280x1024 (SXGA)   | 2        | 4.88%   |
| 3840x1080          | 1        | 2.44%   |
| 2560x1080          | 1        | 2.44%   |
| 1920x1200 (WUXGA)  | 1        | 2.44%   |
| 1680x1050 (WSXGA+) | 1        | 2.44%   |
| 1440x900 (WXGA+)   | 1        | 2.44%   |
| 1366x768 (WXGA)    | 1        | 2.44%   |
| Unknown            | 1        | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 15       | 33.33%  |
| 23      | 7        | 15.56%  |
| 34      | 3        | 6.67%   |
| 24      | 3        | 6.67%   |
| 21      | 3        | 6.67%   |
| 49      | 2        | 4.44%   |
| 25      | 2        | 4.44%   |
| 19      | 2        | 4.44%   |
| 17      | 2        | 4.44%   |
| 31      | 1        | 2.22%   |
| 28      | 1        | 2.22%   |
| 20      | 1        | 2.22%   |
| 15      | 1        | 2.22%   |
| 14      | 1        | 2.22%   |
| Unknown | 1        | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 21       | 52.5%   |
| 401-500     | 5        | 12.5%   |
| 301-350     | 4        | 10%     |
| 701-800     | 3        | 7.5%    |
| 601-700     | 3        | 7.5%    |
| 1001-1500   | 2        | 5%      |
| 351-400     | 1        | 2.5%    |
| Unknown     | 1        | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 24       | 68.57%  |
| 16/10   | 4        | 11.43%  |
| 21/9    | 3        | 8.57%   |
| 5/4     | 2        | 5.71%   |
| 32/9    | 1        | 2.86%   |
| Unknown | 1        | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 15       | 34.09%  |
| 201-250        | 10       | 22.73%  |
| 351-500        | 5        | 11.36%  |
| 151-200        | 4        | 9.09%   |
| 251-300        | 3        | 6.82%   |
| 141-150        | 2        | 4.55%   |
| More than 1000 | 1        | 2.27%   |
| 81-90          | 1        | 2.27%   |
| 101-110        | 1        | 2.27%   |
| 501-1000       | 1        | 2.27%   |
| Unknown        | 1        | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 16       | 42.11%  |
| 51-100  | 16       | 42.11%  |
| 121-160 | 3        | 7.89%   |
| 1-50    | 1        | 2.63%   |
| 161-240 | 1        | 2.63%   |
| Unknown | 1        | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 45.16%  |
| 2     | 11       | 35.48%  |
| 4     | 2        | 6.45%   |
| 3     | 2        | 6.45%   |
| 0     | 2        | 6.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 19       | 45.24%  |
| Realtek Semiconductor    | 14       | 33.33%  |
| Aquantia                 | 3        | 7.14%   |
| Raspberry Pi             | 1        | 2.38%   |
| Ralink Technology        | 1        | 2.38%   |
| Qualcomm Atheros         | 1        | 2.38%   |
| Microsoft                | 1        | 2.38%   |
| MEDIATEK                 | 1        | 2.38%   |
| Marvell Technology Group | 1        | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 12.73%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 10.91%  |
| Intel Wi-Fi 6 AX200                                               | 5        | 9.09%   |
| Intel I211 Gigabit Network Connection                             | 5        | 9.09%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 7.27%   |
| Intel Ethernet Controller I225-V                                  | 3        | 5.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 5.45%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 3.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 3.64%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 3.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.82%   |
| Raspberry Pi Pico                                                 | 1        | 1.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1.82%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1.82%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 1.82%   |
| Microsoft XBOX ACC                                                | 1        | 1.82%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                     | 1        | 1.82%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.82%   |
| Intel Wireless-AC 9260                                            | 1        | 1.82%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.82%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 1.82%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.82%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.82%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 66.67%  |
| Realtek Semiconductor | 1        | 6.67%   |
| Ralink Technology     | 1        | 6.67%   |
| Qualcomm Atheros      | 1        | 6.67%   |
| Microsoft             | 1        | 6.67%   |
| MEDIATEK              | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 5        | 31.25%  |
| Intel Cannon Lake PCH CNVi WiFi                            | 2        | 12.5%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1        | 6.25%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 6.25%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 6.25%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1        | 6.25%   |
| Microsoft XBOX ACC                                         | 1        | 6.25%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                              | 1        | 6.25%   |
| Intel Wireless-AC 9260                                     | 1        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 6.25%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 17       | 48.57%  |
| Realtek Semiconductor    | 14       | 40%     |
| Aquantia                 | 3        | 8.57%   |
| Marvell Technology Group | 1        | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 18.42%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 15.79%  |
| Intel I211 Gigabit Network Connection                             | 5        | 13.16%  |
| Intel Ethernet Connection (2) I219-V                              | 4        | 10.53%  |
| Intel Ethernet Controller I225-V                                  | 3        | 7.89%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 7.89%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 5.26%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.63%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 2.63%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.63%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 2.63%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.63%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 65.91%  |
| WiFi     | 14       | 31.82%  |
| Modem    | 1        | 2.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 75.76%  |
| WiFi     | 8        | 24.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 40%     |
| 2     | 11       | 36.67%  |
| 3     | 6        | 20%     |
| 0     | 1        | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 73.33%  |
| Yes  | 8        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 61.11%  |
| Cambridge Silicon Radio | 4        | 22.22%  |
| Realtek Semiconductor   | 1        | 5.56%   |
| MediaTek                | 1        | 5.56%   |
| ASUSTek Computer        | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 6        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 22.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 11.11%  |
| Realtek Bluetooth Radio                             | 1        | 5.56%   |
| MediaTek Wireless_Device                            | 1        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.56%   |
| Intel Bluetooth Device                              | 1        | 5.56%   |
| Intel AX201 Bluetooth                               | 1        | 5.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 22       | 31.43%  |
| Nvidia                               | 13       | 18.57%  |
| Intel                                | 13       | 18.57%  |
| Thesycon Systemsoftware & Consulting | 3        | 4.29%   |
| Logitech                             | 2        | 2.86%   |
| Creative Labs                        | 2        | 2.86%   |
| C-Media Electronics                  | 2        | 2.86%   |
| AudioQuest                           | 2        | 2.86%   |
| ASUSTek Computer                     | 2        | 2.86%   |
| Yamaha                               | 1        | 1.43%   |
| Valve Software                       | 1        | 1.43%   |
| SteelSeries ApS                      | 1        | 1.43%   |
| Sony                                 | 1        | 1.43%   |
| Sennheiser Communications            | 1        | 1.43%   |
| SAVITECH                             | 1        | 1.43%   |
| RODE Microphones                     | 1        | 1.43%   |
| FiiO Electronics Technology          | 1        | 1.43%   |
| Creative Technology                  | 1        | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 9        | 10.98%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 7        | 8.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 5        | 6.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 4        | 4.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4        | 4.88%   |
| Thesycon Systemsoftware & Consulting D30 Pro                            | 3        | 3.66%   |
| Nvidia GP106 High Definition Audio Controller                           | 3        | 3.66%   |
| Nvidia TU102 High Definition Audio Controller                           | 2        | 2.44%   |
| Intel Comet Lake PCH cAVS                                               | 2        | 2.44%   |
| Intel Cannon Lake PCH cAVS                                              | 2        | 2.44%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]           | 2        | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 2        | 2.44%   |
| AMD Family 17h/19h HD Audio Controller                                  | 2        | 2.44%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]            | 2        | 2.44%   |
| Yamaha Steinberg UR22mkII                                               | 1        | 1.22%   |
| Valve Software Valve VR Radio & HMD Mic                                 | 1        | 1.22%   |
| SteelSeries ApS Arctis 7 wireless adapter                               | 1        | 1.22%   |
| Sony DualShock 4 [CUH-ZCT2x]                                            | 1        | 1.22%   |
| Sennheiser Communications GSX 1200 Pro Main Audio                       | 1        | 1.22%   |
| SAVITECH SA9023 audio controller                                        | 1        | 1.22%   |
| RODE Microphones RODE VideoMic NTG                                      | 1        | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                           | 1        | 1.22%   |
| Nvidia TU106 High Definition Audio Controller                           | 1        | 1.22%   |
| Nvidia GP108 High Definition Audio Controller                           | 1        | 1.22%   |
| Nvidia GP104 High Definition Audio Controller                           | 1        | 1.22%   |
| Nvidia GP102 HDMI Audio Controller                                      | 1        | 1.22%   |
| Nvidia GM206 High Definition Audio Controller                           | 1        | 1.22%   |
| Nvidia GM204 High Definition Audio Controller                           | 1        | 1.22%   |
| Nvidia Audio device                                                     | 1        | 1.22%   |
| Logitech Z-5 Speakers                                                   | 1        | 1.22%   |
| Logitech Yeti X                                                         | 1        | 1.22%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 1        | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1        | 1.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 1        | 1.22%   |
| Intel 200 Series PCH HD Audio                                           | 1        | 1.22%   |
| FiiO Electronics Technology BTR5                                        | 1        | 1.22%   |
| Creative Technology Sound BlasterX G6                                   | 1        | 1.22%   |
| C-Media Electronics USB Advanced Audio Device                           | 1        | 1.22%   |
| C-Media Electronics CM108 Audio Controller                              | 1        | 1.22%   |
| AudioQuest SDAC                                                         | 1        | 1.22%   |
| AudioQuest DragonFly Red                                                | 1        | 1.22%   |
| ASUSTek Computer Xonar U1 Audio Station                                 | 1        | 1.22%   |
| ASUSTek Computer USB Audio                                              | 1        | 1.22%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                              | 1        | 1.22%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]               | 1        | 1.22%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                      | 1        | 1.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1        | 1.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 8        | 26.67%  |
| Kingston            | 7        | 23.33%  |
| G.Skill             | 6        | 20%     |
| Corsair             | 3        | 10%     |
| Unknown             | 1        | 3.33%   |
| Team                | 1        | 3.33%   |
| Samsung Electronics | 1        | 3.33%   |
| Patriot             | 1        | 3.33%   |
| Micron Technology   | 1        | 3.33%   |
| A-DATA Technology   | 1        | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM SDRAM                         | 1        | 2.94%   |
| Unknown RAM Module 1GB DIMM SDRAM                           | 1        | 2.94%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s         | 1        | 2.94%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 2667MT/s        | 1        | 2.94%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s          | 1        | 2.94%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s          | 1        | 2.94%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s        | 1        | 2.94%   |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s   | 1        | 2.94%   |
| Kingston RAM KHX2133C14D4/4G 4096MB DIMM DDR4 2933MT/s      | 1        | 2.94%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s           | 1        | 2.94%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 1867MT/s      | 1        | 2.94%   |
| Kingston RAM KF3200C16D4/16GX 16384MB DIMM DDR4 3200MT/s    | 1        | 2.94%   |
| Kingston RAM HX426C16FB/8 8GB DIMM DDR4 2667MT/s            | 1        | 2.94%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s        | 1        | 2.94%   |
| G.Skill RAM F4-3600C17-16GTZR 16384MB DIMM DDR4 3666MT/s    | 1        | 2.94%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s      | 1        | 2.94%   |
| G.Skill RAM F4-3600C16-8GTZN 8GB DIMM DDR4 3666MT/s         | 1        | 2.94%   |
| G.Skill RAM F4-3600C16-16GVKC 16384MB DIMM DDR4 3866MT/s    | 1        | 2.94%   |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2133MT/s         | 1        | 2.94%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1800MT/s        | 1        | 2.94%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s       | 1        | 2.94%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s     | 1        | 2.94%   |
| Crucial RAM CT16G4DFD8213.C16FAD 16GB DIMM DDR4 2133MT/s    | 1        | 2.94%   |
| Crucial RAM BLS4G4D26BFSE.8FE 4GB DIMM DDR4 2667MT/s        | 1        | 2.94%   |
| Crucial RAM BL8G32C16U4R.M8FE1 8GB DIMM DDR4 3400MT/s       | 1        | 2.94%   |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4             | 1        | 2.94%   |
| Crucial RAM BL32G32C16U4B.M16FB1 32GB DIMM DDR4 3200MT/s    | 1        | 2.94%   |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s    | 1        | 2.94%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16384MB DIMM DDR4 3200MT/s | 1        | 2.94%   |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3200MT/s     | 1        | 2.94%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s   | 1        | 2.94%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s       | 1        | 2.94%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s       | 1        | 2.94%   |
| A-DATA RAM DDR4 3000 2OZ 8GB DIMM DDR4 3000MT/s             | 1        | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 25       | 92.59%  |
| SDRAM | 1        | 3.7%    |
| DDR3  | 1        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 27       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 12       | 37.5%   |
| 8192  | 12       | 37.5%   |
| 32768 | 3        | 9.38%   |
| 4096  | 3        | 9.38%   |
| 1024  | 1        | 3.13%   |
| 512   | 1        | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 6        | 18.75%  |
| 3600    | 4        | 12.5%   |
| 2133    | 4        | 12.5%   |
| 2667    | 3        | 9.38%   |
| 3666    | 2        | 6.25%   |
| 3400    | 2        | 6.25%   |
| 2400    | 2        | 6.25%   |
| 4000    | 1        | 3.13%   |
| 3866    | 1        | 3.13%   |
| 3533    | 1        | 3.13%   |
| 3466    | 1        | 3.13%   |
| 3000    | 1        | 3.13%   |
| 2933    | 1        | 3.13%   |
| 2733    | 1        | 3.13%   |
| 1800    | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

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
| Logitech                      | 4        | 50%     |
| Valve Software                | 1        | 12.5%   |
| Sunplus Innovation Technology | 1        | 12.5%   |
| Generalplus Technology        | 1        | 12.5%   |
| Creative Technology           | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Valve Software 3D Camera          | 1        | 12.5%   |
| Sunplus Full HD webcam            | 1        | 12.5%   |
| Logitech Webcam C270              | 1        | 12.5%   |
| Logitech StreamCam                | 1        | 12.5%   |
| Logitech QuickCam Orbit/Sphere AF | 1        | 12.5%   |
| Logitech BRIO                     | 1        | 12.5%   |
| Generalplus GENERAL WEBCAM        | 1        | 12.5%   |
| Creative Live! Cam Sync 1080p     | 1        | 12.5%   |

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
| 0     | 23       | 71.88%  |
| 1     | 6        | 18.75%  |
| 4     | 2        | 6.25%   |
| 2     | 1        | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 5        | 38.46%  |
| Graphics card            | 2        | 15.38%  |
| Storage/ata              | 1        | 7.69%   |
| Sound                    | 1        | 7.69%   |
| Net/wireless             | 1        | 7.69%   |
| Modem                    | 1        | 7.69%   |
| Camera                   | 1        | 7.69%   |
| Bluetooth                | 1        | 7.69%   |

