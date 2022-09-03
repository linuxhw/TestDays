Slackware 15.0 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Slackware_15.0/Desktop/README.md) and [notebooks](/Dist/Slackware_15.0/Notebook/README.md).

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

Total: 58

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a954ba4e86](https://linux-hardware.org/?probe=a954ba4e86) | Aug 26, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [e5785106f1](https://linux-hardware.org/?probe=e5785106f1) | Aug 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [e2f44a8274](https://linux-hardware.org/?probe=e2f44a8274) | May 31, 2022 |
| Sony          | SVE1713A1EW                 | Notebook    | [c3a65d695d](https://linux-hardware.org/?probe=c3a65d695d) | May 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI           | GE76 Raider 11UE            | Notebook    | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Notebook      | X170KM-G                    | Notebook    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| MSI           | MS-7365                     | Desktop     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown       | X79-P3                      | Desktop     | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| Dell          | Latitude 3520               | Notebook    | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP            | ProBook 6570b               | Notebook    | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| HP            | 0A08h                       | Desktop     | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| ASRock        | H410M-ITX/ac                | Desktop     | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c8289cd264](https://linux-hardware.org/?probe=c8289cd264) | Mar 26, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5c6b1616fa](https://linux-hardware.org/?probe=5c6b1616fa) | Mar 21, 2022 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [5f36bc3969](https://linux-hardware.org/?probe=5f36bc3969) | Mar 12, 2022 |
| ASRock        | H270 Pro4                   | Desktop     | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| HP            | 86F3 00100                  | All in one  | [7de0381db8](https://linux-hardware.org/?probe=7de0381db8) | Mar 11, 2022 |
| Lenovo        | ThinkPad X230 2325P38       | Notebook    | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework     | Laptop                      | Notebook    | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Dell          | 068NXX A00                  | Server      | [85004f427a](https://linux-hardware.org/?probe=85004f427a) | Mar 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| TYAN Compu... | S7012                       | Server      | [fec98b51da](https://linux-hardware.org/?probe=fec98b51da) | Feb 27, 2022 |
| TYAN Compu... | S7012                       | Server      | [81a490184b](https://linux-hardware.org/?probe=81a490184b) | Feb 26, 2022 |
| Biostar       | X470GTA                     | Desktop     | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP            | 212B                        | Desktop     | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | Notebook    | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI           | H61M-P31                    | Desktop     | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76      | Oryx Pro                    | Notebook    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 12        | 23.08%  |
| 5.15.27           | 4         | 7.69%   |
| 5.17.2            | 2         | 3.85%   |
| 5.17.1            | 2         | 3.85%   |
| 5.16.13           | 2         | 3.85%   |
| 5.15.38           | 2         | 3.85%   |
| 5.15.30-Unraid    | 2         | 3.85%   |
| 5.13.8            | 2         | 3.85%   |
| 5.17.5            | 1         | 1.92%   |
| 5.17.0-custom     | 1         | 1.92%   |
| 5.16.9-joe1       | 1         | 1.92%   |
| 5.16.18           | 1         | 1.92%   |
| 5.16.12           | 1         | 1.92%   |
| 5.16.11           | 1         | 1.92%   |
| 5.15.6            | 1         | 1.92%   |
| 5.15.37.a         | 1         | 1.92%   |
| 5.15.33.kjh       | 1         | 1.92%   |
| 5.15.21-hardened1 | 1         | 1.92%   |
| 5.15.14           | 1         | 1.92%   |
| 5.15.13           | 1         | 1.92%   |
| 5.15.1            | 1         | 1.92%   |
| 5.14.9            | 1         | 1.92%   |
| 5.14.8            | 1         | 1.92%   |
| 5.14.15-Unraid    | 1         | 1.92%   |
| 5.14.15           | 1         | 1.92%   |
| 5.14.11           | 1         | 1.92%   |
| 5.14.10           | 1         | 1.92%   |
| 5.14.0            | 1         | 1.92%   |
| 5.13.5            | 1         | 1.92%   |
| 5.13.12           | 1         | 1.92%   |
| 5.13.11           | 1         | 1.92%   |
| 5.10.91           | 1         | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 12        | 23.08%  |
| 5.15.27 | 4         | 7.69%   |
| 5.17.2  | 2         | 3.85%   |
| 5.17.1  | 2         | 3.85%   |
| 5.16.13 | 2         | 3.85%   |
| 5.15.38 | 2         | 3.85%   |
| 5.15.30 | 2         | 3.85%   |
| 5.14.15 | 2         | 3.85%   |
| 5.13.8  | 2         | 3.85%   |
| 5.17.5  | 1         | 1.92%   |
| 5.17.0  | 1         | 1.92%   |
| 5.16.9  | 1         | 1.92%   |
| 5.16.18 | 1         | 1.92%   |
| 5.16.12 | 1         | 1.92%   |
| 5.16.11 | 1         | 1.92%   |
| 5.15.6  | 1         | 1.92%   |
| 5.15.37 | 1         | 1.92%   |
| 5.15.33 | 1         | 1.92%   |
| 5.15.21 | 1         | 1.92%   |
| 5.15.14 | 1         | 1.92%   |
| 5.15.13 | 1         | 1.92%   |
| 5.15.1  | 1         | 1.92%   |
| 5.14.9  | 1         | 1.92%   |
| 5.14.8  | 1         | 1.92%   |
| 5.14.11 | 1         | 1.92%   |
| 5.14.10 | 1         | 1.92%   |
| 5.14.0  | 1         | 1.92%   |
| 5.13.5  | 1         | 1.92%   |
| 5.13.12 | 1         | 1.92%   |
| 5.13.11 | 1         | 1.92%   |
| 5.10.91 | 1         | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 27        | 52.94%  |
| 5.17    | 6         | 11.76%  |
| 5.16    | 6         | 11.76%  |
| 5.14    | 6         | 11.76%  |
| 5.13    | 5         | 9.8%    |
| 5.10    | 1         | 1.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 51        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 26        | 50%     |
| XFCE      | 12        | 23.08%  |
| Unknown   | 8         | 15.38%  |
| GNOME     | 2         | 3.85%   |
| xwmconfig | 1         | 1.92%   |
| MATE      | 1         | 1.92%   |
| KDE       | 1         | 1.92%   |
| FVWM      | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 27        | 50.94%  |
| Tty     | 20        | 37.74%  |
| Wayland | 3         | 5.66%   |
| Unknown | 3         | 5.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 33        | 64.71%  |
| Unknown | 10        | 19.61%  |
| XDM     | 6         | 11.76%  |
| LightDM | 2         | 3.92%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 37        | 72.55%  |
| Unknown     | 5         | 9.8%    |
| it_IT       | 2         | 3.92%   |
| fr_FR       | 2         | 3.92%   |
| ru_RU       | 1         | 1.96%   |
| pt_BR       | 1         | 1.96%   |
| es_ES.UTF8  | 1         | 1.96%   |
| en_US.ASCII | 1         | 1.96%   |
| de_DE       | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 30        | 58.82%  |
| BIOS | 21        | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 36        | 70.59%  |
| Btrfs   | 7         | 13.73%  |
| Overlay | 4         | 7.84%   |
| Xfs     | 2         | 3.92%   |
| Zfs     | 1         | 1.96%   |
| F2fs    | 1         | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 40        | 76.92%  |
| MBR     | 9         | 17.31%  |
| Unknown | 3         | 5.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 73.08%  |
| Yes       | 14        | 26.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 62.75%  |
| Yes       | 19        | 37.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| MSI                 | 10        | 19.61%  |
| Hewlett-Packard     | 9         | 17.65%  |
| Dell                | 6         | 11.76%  |
| Lenovo              | 5         | 9.8%    |
| ASUSTek Computer    | 5         | 9.8%    |
| ASRock              | 3         | 5.88%   |
| Apple               | 2         | 3.92%   |
| TYAN Computer       | 1         | 1.96%   |
| System76            | 1         | 1.96%   |
| Sony                | 1         | 1.96%   |
| Notebook            | 1         | 1.96%   |
| Gigabyte Technology | 1         | 1.96%   |
| Fujitsu             | 1         | 1.96%   |
| Framework           | 1         | 1.96%   |
| Dynabook            | 1         | 1.96%   |
| Biostar             | 1         | 1.96%   |
| Acer                | 1         | 1.96%   |
| Unknown             | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| TYAN S7012                               | 1         | 1.96%   |
| System76 Oryx Pro                        | 1         | 1.96%   |
| Sony SVE1713A1EW                         | 1         | 1.96%   |
| Notebook X170KM-G                        | 1         | 1.96%   |
| MSI MS-7C52                              | 1         | 1.96%   |
| MSI MS-7C02                              | 1         | 1.96%   |
| MSI MS-7788                              | 1         | 1.96%   |
| MSI MS-7693                              | 1         | 1.96%   |
| MSI MS-7529                              | 1         | 1.96%   |
| MSI MS-7365                              | 1         | 1.96%   |
| MSI Modern 14 B11MO                      | 1         | 1.96%   |
| MSI Modern 14 B10MW                      | 1         | 1.96%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.96%   |
| MSI GE76 Raider 11UE                     | 1         | 1.96%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.96%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.96%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.96%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.96%   |
| Lenovo H50-05 90BH001WIX                 | 1         | 1.96%   |
| HP Z440 Workstation                      | 1         | 1.96%   |
| HP xw8400 Workstation                    | 1         | 1.96%   |
| HP ProBook 6570b                         | 1         | 1.96%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.96%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.96%   |
| HP Laptop 15-bs1xx                       | 1         | 1.96%   |
| HP EliteBook 840 G5                      | 1         | 1.96%   |
| HP 245 G7 Notebook PC                    | 1         | 1.96%   |
| HP 205 G4 22 All-in-One PC               | 1         | 1.96%   |
| Gigabyte N3160TN                         | 1         | 1.96%   |
| Fujitsu LIFEBOOK A544                    | 1         | 1.96%   |
| Framework Laptop                         | 1         | 1.96%   |
| Dynabook P1-C7MP-BL                      | 1         | 1.96%   |
| Dell Vostro 3500                         | 1         | 1.96%   |
| Dell Precision M4700                     | 1         | 1.96%   |
| Dell PowerEdge R6515                     | 1         | 1.96%   |
| Dell OptiPlex 780                        | 1         | 1.96%   |
| Dell Latitude 3520                       | 1         | 1.96%   |
| Dell Inspiron 15-3552                    | 1         | 1.96%   |
| Biostar X470GTA                          | 1         | 1.96%   |
| ASUS TUF B450-PLUS GAMING                | 1         | 1.96%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 1.96%   |
| ASUS ROG CROSSHAIR VIII HERO             | 1         | 1.96%   |
| ASUS PRIME Z390-A                        | 1         | 1.96%   |
| ASUS All Series                          | 1         | 1.96%   |
| ASRock N68-S3 FX                         | 1         | 1.96%   |
| ASRock H410M-ITX/ac                      | 1         | 1.96%   |
| ASRock H270 Pro4                         | 1         | 1.96%   |
| Apple Macmini6,2                         | 1         | 1.96%   |
| Apple iMac7,1                            | 1         | 1.96%   |
| Acer Aspire R3610                        | 1         | 1.96%   |
| Unknown                                  | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 5.88%   |
| MSI Modern          | 2         | 3.92%   |
| HP Pavilion         | 2         | 3.92%   |
| ASUS ROG            | 2         | 3.92%   |
| TYAN S7012          | 1         | 1.96%   |
| System76 Oryx       | 1         | 1.96%   |
| Sony SVE1713A1EW    | 1         | 1.96%   |
| Notebook X170KM-G   | 1         | 1.96%   |
| MSI MS-7C52         | 1         | 1.96%   |
| MSI MS-7C02         | 1         | 1.96%   |
| MSI MS-7788         | 1         | 1.96%   |
| MSI MS-7693         | 1         | 1.96%   |
| MSI MS-7529         | 1         | 1.96%   |
| MSI MS-7365         | 1         | 1.96%   |
| MSI GP76            | 1         | 1.96%   |
| MSI GE76            | 1         | 1.96%   |
| Lenovo IdeaPad      | 1         | 1.96%   |
| Lenovo H50-05       | 1         | 1.96%   |
| HP Z440             | 1         | 1.96%   |
| HP xw8400           | 1         | 1.96%   |
| HP ProBook          | 1         | 1.96%   |
| HP Laptop           | 1         | 1.96%   |
| HP EliteBook        | 1         | 1.96%   |
| HP 245              | 1         | 1.96%   |
| HP 205              | 1         | 1.96%   |
| Gigabyte N3160TN    | 1         | 1.96%   |
| Fujitsu LIFEBOOK    | 1         | 1.96%   |
| Framework Laptop    | 1         | 1.96%   |
| Dynabook P1-C7MP-BL | 1         | 1.96%   |
| Dell Vostro         | 1         | 1.96%   |
| Dell Precision      | 1         | 1.96%   |
| Dell PowerEdge      | 1         | 1.96%   |
| Dell OptiPlex       | 1         | 1.96%   |
| Dell Latitude       | 1         | 1.96%   |
| Dell Inspiron       | 1         | 1.96%   |
| Biostar X470GTA     | 1         | 1.96%   |
| ASUS TUF            | 1         | 1.96%   |
| ASUS PRIME          | 1         | 1.96%   |
| ASUS All            | 1         | 1.96%   |
| ASRock N68-S3       | 1         | 1.96%   |
| ASRock H410M-ITX    | 1         | 1.96%   |
| ASRock H270         | 1         | 1.96%   |
| Apple Macmini6      | 1         | 1.96%   |
| Apple iMac7         | 1         | 1.96%   |
| Acer Aspire         | 1         | 1.96%   |
| Unknown             | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 8         | 15.69%  |
| 2020 | 8         | 15.69%  |
| 2012 | 5         | 9.8%    |
| 2019 | 4         | 7.84%   |
| 2017 | 4         | 7.84%   |
| 2011 | 4         | 7.84%   |
| 2018 | 3         | 5.88%   |
| 2015 | 3         | 5.88%   |
| 2016 | 2         | 3.92%   |
| 2014 | 2         | 3.92%   |
| 2009 | 2         | 3.92%   |
| 2007 | 2         | 3.92%   |
| 2022 | 1         | 1.96%   |
| 2013 | 1         | 1.96%   |
| 2010 | 1         | 1.96%   |
| 2008 | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 25        | 49.02%  |
| Desktop    | 21        | 41.18%  |
| All in one | 2         | 3.92%   |
| Server     | 2         | 3.92%   |
| Mini pc    | 1         | 1.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 51        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 96.08%  |
| Yes  | 2         | 3.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 11        | 21.57%  |
| 4.01-8.0    | 9         | 17.65%  |
| 3.01-4.0    | 9         | 17.65%  |
| 8.01-16.0   | 8         | 15.69%  |
| 32.01-64.0  | 5         | 9.8%    |
| 64.01-256.0 | 5         | 9.8%    |
| 24.01-32.0  | 2         | 3.92%   |
| 1.01-2.0    | 2         | 3.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 14        | 26.42%  |
| 2.01-3.0   | 13        | 24.53%  |
| 4.01-8.0   | 12        | 22.64%  |
| 0.51-1.0   | 7         | 13.21%  |
| 3.01-4.0   | 2         | 3.77%   |
| 16.01-24.0 | 2         | 3.77%   |
| 0.01-0.5   | 2         | 3.77%   |
| 32.01-64.0 | 1         | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 47.06%  |
| 2      | 12        | 23.53%  |
| 3      | 6         | 11.76%  |
| 4      | 5         | 9.8%    |
| 6      | 2         | 3.92%   |
| 9      | 1         | 1.96%   |
| 0      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 60.78%  |
| Yes       | 20        | 39.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 90.2%   |
| No        | 5         | 9.8%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 74.51%  |
| No        | 13        | 25.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 68.63%  |
| No        | 16        | 31.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 12        | 23.53%  |
| Kazakhstan   | 6         | 11.76%  |
| Italy        | 4         | 7.84%   |
| South Africa | 3         | 5.88%   |
| Japan        | 3         | 5.88%   |
| Brazil       | 3         | 5.88%   |
| UK           | 2         | 3.92%   |
| Spain        | 2         | 3.92%   |
| Hong Kong    | 2         | 3.92%   |
| Greece       | 2         | 3.92%   |
| France       | 2         | 3.92%   |
| Canada       | 2         | 3.92%   |
| Switzerland  | 1         | 1.96%   |
| Sweden       | 1         | 1.96%   |
| Serbia       | 1         | 1.96%   |
| Russia       | 1         | 1.96%   |
| Portugal     | 1         | 1.96%   |
| Netherlands  | 1         | 1.96%   |
| Mexico       | 1         | 1.96%   |
| Germany      | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 4         | 7.84%   |
| Tsukuba           | 2         | 3.92%   |
| Karaganda         | 2         | 3.92%   |
| Chania            | 2         | 3.92%   |
| Cape Town         | 2         | 3.92%   |
| Toronto           | 1         | 1.96%   |
| St Petersburg     | 1         | 1.96%   |
| Skövde           | 1         | 1.96%   |
| Sham Shui Po      | 1         | 1.96%   |
| Santa Cruz do Sul | 1         | 1.96%   |
| Saint Paul        | 1         | 1.96%   |
| Round Rock        | 1         | 1.96%   |
| Rome              | 1         | 1.96%   |
| Reno              | 1         | 1.96%   |
| Renazzo           | 1         | 1.96%   |
| Porto Alegre      | 1         | 1.96%   |
| Plainwell         | 1         | 1.96%   |
| Ōtsu             | 1         | 1.96%   |
| Oberstreit        | 1         | 1.96%   |
| Naaldwijk         | 1         | 1.96%   |
| Montreal          | 1         | 1.96%   |
| Milwaukee         | 1         | 1.96%   |
| Milan             | 1         | 1.96%   |
| Mexico City       | 1         | 1.96%   |
| Mead              | 1         | 1.96%   |
| McKinney          | 1         | 1.96%   |
| Luxeuil-les-Bains | 1         | 1.96%   |
| London            | 1         | 1.96%   |
| Lisbon            | 1         | 1.96%   |
| Liebefeld         | 1         | 1.96%   |
| League City       | 1         | 1.96%   |
| Johannesburg      | 1         | 1.96%   |
| Hayward           | 1         | 1.96%   |
| Granada           | 1         | 1.96%   |
| Frosinone         | 1         | 1.96%   |
| Fortaleza         | 1         | 1.96%   |
| Colorado Springs  | 1         | 1.96%   |
| Chicago           | 1         | 1.96%   |
| Chessy            | 1         | 1.96%   |
| Central           | 1         | 1.96%   |
| Belgrade          | 1         | 1.96%   |
| Belfast           | 1         | 1.96%   |
| Algeciras         | 1         | 1.96%   |
| Abingdon          | 1         | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 23     | 17.86%  |
| Samsung Electronics | 15        | 21     | 17.86%  |
| WDC                 | 11        | 13     | 13.1%   |
| Toshiba             | 6         | 9      | 7.14%   |
| Kingston            | 5         | 6      | 5.95%   |
| Hitachi             | 4         | 7      | 4.76%   |
| HGST                | 3         | 3      | 3.57%   |
| Crucial             | 3         | 3      | 3.57%   |
| SK hynix            | 2         | 2      | 2.38%   |
| SanDisk             | 2         | 2      | 2.38%   |
| Hewlett-Packard     | 2         | 3      | 2.38%   |
| Gigabyte Technology | 2         | 2      | 2.38%   |
| ZHITAI              | 1         | 2      | 1.19%   |
| Plextor             | 1         | 1      | 1.19%   |
| Patriot             | 1         | 1      | 1.19%   |
| Micron Technology   | 1         | 1      | 1.19%   |
| KIOXIA              | 1         | 1      | 1.19%   |
| JMicron Technology  | 1         | 1      | 1.19%   |
| Intenso             | 1         | 1      | 1.19%   |
| Intel               | 1         | 1      | 1.19%   |
| GOODRAM             | 1         | 1      | 1.19%   |
| External            | 1         | 1      | 1.19%   |
| DUEX                | 1         | 1      | 1.19%   |
| China               | 1         | 1      | 1.19%   |
| Apple               | 1         | 1      | 1.19%   |
| A-DATA Technology   | 1         | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 2.11%   |
| WDC WD10SPZX-60Z10T0 1TB                | 2         | 2.11%   |
| Seagate ST1000DM003-1SB102 1TB          | 2         | 2.11%   |
| Samsung SSD 970 EVO 250GB               | 2         | 2.11%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 2.11%   |
| ZHITAI SC001 Active 1TB SSD             | 1         | 1.05%   |
| ZHITAI PC005 Active 512GB               | 1         | 1.05%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 1         | 1.05%   |
| WDC WD40EJRX-89T1XY0 4TB                | 1         | 1.05%   |
| WDC WD400BD-60LTA0 40GB                 | 1         | 1.05%   |
| WDC WD3200AAJS-65B4A0 320GB             | 1         | 1.05%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 1.05%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 1.05%   |
| WDC WD10JPVT-08A1YT2 1TB                | 1         | 1.05%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB      | 1         | 1.05%   |
| Toshiba THNSF5512GPUK 512GB             | 1         | 1.05%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 1.05%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.05%   |
| Toshiba MD04ABA400V 4TB                 | 1         | 1.05%   |
| Toshiba HDWD240 4TB                     | 1         | 1.05%   |
| Toshiba DT01ACA300 3TB                  | 1         | 1.05%   |
| SK hynix HFM001TD3JX013N 1TB            | 1         | 1.05%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 1         | 1.05%   |
| Seagate ST4000VX000-2AG166 4TB          | 1         | 1.05%   |
| Seagate ST4000DM000-1F2168 4TB          | 1         | 1.05%   |
| Seagate ST380011A 80GB                  | 1         | 1.05%   |
| Seagate ST3500630AS 500GB               | 1         | 1.05%   |
| Seagate ST3250820AS Q 250GB             | 1         | 1.05%   |
| Seagate ST3160211AS 160GB               | 1         | 1.05%   |
| Seagate ST3000VX006-1HH166 3TB          | 1         | 1.05%   |
| Seagate ST3000NM0033-9ZM178 3TB         | 1         | 1.05%   |
| Seagate ST3000DM001-1ER166 3TB          | 1         | 1.05%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 1.05%   |
| Seagate ST2000DL003-9VT166 2TB          | 1         | 1.05%   |
| Seagate ST1000NM004A-2MN130 1TB         | 1         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.05%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 1.05%   |
| Seagate ST1000DM003-1ER162 1TB          | 1         | 1.05%   |
| Seagate ST10000DM005-3AW101 10TB        | 1         | 1.05%   |
| Seagate Expansion Desk 4TB              | 1         | 1.05%   |
| SanDisk Ultra II 960GB SSD              | 1         | 1.05%   |
| SanDisk SDSSDA240G 240GB                | 1         | 1.05%   |
| Samsung SSD 980 PRO 500GB               | 1         | 1.05%   |
| Samsung SSD 980 PRO 2TB                 | 1         | 1.05%   |
| Samsung SSD 970 EVO Plus 500GB          | 1         | 1.05%   |
| Samsung SSD 970 EVO Plus 2TB            | 1         | 1.05%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 1.05%   |
| Samsung SSD 970 EVO 2TB                 | 1         | 1.05%   |
| Samsung SSD 870 EVO 1TB                 | 1         | 1.05%   |
| Samsung SSD 860 QVO 2TB                 | 1         | 1.05%   |
| Samsung SSD 860 EVO mSATA 500GB         | 1         | 1.05%   |
| Samsung SSD 860 EVO 500GB               | 1         | 1.05%   |
| Samsung SSD 860 500GB                   | 1         | 1.05%   |
| Samsung SSD 840 Series 250GB            | 1         | 1.05%   |
| Samsung NVMe SSD Drive 256GB            | 1         | 1.05%   |
| Samsung MZVLQ512HALU-000H1 512GB        | 1         | 1.05%   |
| Samsung MZVL21T0HCLR-00B00 1TB          | 1         | 1.05%   |
| Samsung MZVKW512HMJP-000H1 512GB        | 1         | 1.05%   |
| Samsung MZHPV512HDGL-00000 512GB SSD    | 1         | 1.05%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD    | 1         | 1.05%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 23     | 40.54%  |
| WDC     | 10        | 12     | 27.03%  |
| Toshiba | 5         | 7      | 13.51%  |
| Hitachi | 4         | 7      | 10.81%  |
| HGST    | 3         | 3      | 8.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 23.08%  |
| Kingston            | 5         | 6      | 19.23%  |
| SanDisk             | 2         | 2      | 7.69%   |
| Crucial             | 2         | 2      | 7.69%   |
| ZHITAI              | 1         | 1      | 3.85%   |
| Plextor             | 1         | 1      | 3.85%   |
| Patriot             | 1         | 1      | 3.85%   |
| JMicron Technology  | 1         | 1      | 3.85%   |
| Intenso             | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |
| GOODRAM             | 1         | 1      | 3.85%   |
| Gigabyte Technology | 1         | 1      | 3.85%   |
| DUEX                | 1         | 1      | 3.85%   |
| China               | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 52     | 36.62%  |
| SSD  | 23        | 29     | 32.39%  |
| NVMe | 22        | 28     | 30.99%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 79     | 60.66%  |
| NVMe | 21        | 27     | 34.43%  |
| SAS  | 3         | 3      | 4.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 36     | 48.28%  |
| 0.51-1.0   | 14        | 18     | 24.14%  |
| 1.01-2.0   | 6         | 8      | 10.34%  |
| 3.01-4.0   | 5         | 10     | 8.62%   |
| 2.01-3.0   | 3         | 7      | 5.17%   |
| 4.01-10.0  | 2         | 2      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 13        | 25%     |
| 101-250        | 11        | 21.15%  |
| 251-500        | 10        | 19.23%  |
| 1-20           | 5         | 9.62%   |
| 1001-2000      | 4         | 7.69%   |
| Unknown        | 4         | 7.69%   |
| More than 3000 | 2         | 3.85%   |
| 2001-3000      | 2         | 3.85%   |
| 51-100         | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 31.37%  |
| 1-20           | 9         | 17.65%  |
| 251-500        | 7         | 13.73%  |
| 21-50          | 7         | 13.73%  |
| 501-1000       | 5         | 9.8%    |
| Unknown        | 4         | 7.84%   |
| More than 3000 | 1         | 1.96%   |
| 1001-2000      | 1         | 1.96%   |
| 51-100         | 1         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 1      | 6.67%   |
| WDC WD3200AAJS-65B4A0 320GB         | 1         | 1      | 6.67%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 6.67%   |
| Seagate ST380011A 80GB              | 1         | 1      | 6.67%   |
| Seagate ST3500630AS 500GB           | 1         | 1      | 6.67%   |
| Seagate ST3000VX006-1HH166 3TB      | 1         | 1      | 6.67%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 6.67%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 2      | 6.67%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 6.67%   |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 6.67%   |
| Hitachi HUA723030ALA640 3TB         | 1         | 1      | 6.67%   |
| Hitachi HDS721016CLA382 160GB       | 1         | 1      | 6.67%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 6.67%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 6.67%   |
| DUEX DX300256A5xnEMLC 256GB SSD     | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 6      | 28.57%  |
| WDC                 | 3         | 4      | 21.43%  |
| Hitachi             | 2         | 2      | 14.29%  |
| HGST                | 2         | 2      | 14.29%  |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Plextor             | 1         | 1      | 7.14%   |
| DUEX                | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 6      | 36.36%  |
| WDC     | 3         | 4      | 27.27%  |
| Hitachi | 2         | 2      | 18.18%  |
| HGST    | 2         | 2      | 18.18%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 14     | 75%     |
| SSD  | 3         | 3      | 25%     |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 44        | 81     | 70.97%  |
| Malfunc  | 12        | 17     | 19.35%  |
| Detected | 6         | 11     | 9.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 29        | 42.03%  |
| AMD                          | 12        | 17.39%  |
| Samsung Electronics          | 10        | 14.49%  |
| SK hynix                     | 2         | 2.9%    |
| Nvidia                       | 2         | 2.9%    |
| Yangtze Memory Technologies  | 1         | 1.45%   |
| Toshiba America Info Systems | 1         | 1.45%   |
| SanDisk                      | 1         | 1.45%   |
| Realtek Semiconductor        | 1         | 1.45%   |
| Phison Electronics           | 1         | 1.45%   |
| Micron/Crucial Technology    | 1         | 1.45%   |
| Micron Technology            | 1         | 1.45%   |
| Marvell Technology Group     | 1         | 1.45%   |
| KIOXIA                       | 1         | 1.45%   |
| JMicron Technology           | 1         | 1.45%   |
| Broadcom / LSI               | 1         | 1.45%   |
| Biwin Storage Technology     | 1         | 1.45%   |
| ASMedia Technology           | 1         | 1.45%   |
| Adaptec                      | 1         | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 12.05%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 6.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 4.82%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 4.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 3.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 3.61%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 2.41%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 2.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 2.41%   |
| Yangtze Memory Non-Volatile memory controller                                           | 1         | 1.2%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 1.2%    |
| SK hynix Gold P31 SSD                                                                   | 1         | 1.2%    |
| SK hynix BC511                                                                          | 1         | 1.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 1.2%    |
| Samsung Electronics SATA controller                                                     | 1         | 1.2%    |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 1.2%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 1.2%    |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 1.2%    |
| Nvidia MCP61 SATA Controller                                                            | 1         | 1.2%    |
| Nvidia MCP61 IDE                                                                        | 1         | 1.2%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 1.2%    |
| Micron Non-Volatile memory controller                                                   | 1         | 1.2%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 1.2%    |
| KIOXIA NVMe SSD Controller BG4                                                          | 1         | 1.2%    |
| JMicron JMB58x AHCI SATA controller                                                     | 1         | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.2%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 1.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.2%    |
| Intel SSD 600P Series                                                                   | 1         | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.2%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.2%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 1.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 1.2%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1         | 1.2%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 1.2%    |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 1         | 1.2%    |
| Intel 631xESB/632xESB IDE Controller                                                    | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.2%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 1         | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.2%    |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                      | 1         | 1.2%    |
| Biwin Storage Non-Volatile memory controller                                            | 1         | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 1.2%    |
| Adaptec SCSI storage controller                                                         | 1         | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 34        | 49.28%  |
| NVMe | 21        | 30.43%  |
| IDE  | 8         | 11.59%  |
| RAID | 4         | 5.8%    |
| SCSI | 2         | 2.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 74.51%  |
| AMD    | 13        | 25.49%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 5.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 3.92%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 1.96%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 1.96%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 1.96%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 1.96%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 1.96%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 1.96%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.96%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 1.96%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.96%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.96%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.96%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.96%   |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1         | 1.96%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 1.96%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.96%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 1         | 1.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.96%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.96%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.96%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.96%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 1         | 1.96%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 1.96%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 1         | 1.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 1.96%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 1.96%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.96%   |
| Intel Atom CPU 330 @ 1.60GHz                  | 1         | 1.96%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 1.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.96%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1         | 1.96%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 1.96%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 1.96%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1         | 1.96%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 1.96%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 1.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.96%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 1         | 1.96%   |
| AMD FX-8320 Eight-Core Processor              | 1         | 1.96%   |
| AMD FX-6300 Six-Core Processor                | 1         | 1.96%   |
| AMD EPYC 7232P 8-Core Processor               | 1         | 1.96%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 1.96%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 8         | 15.69%  |
| Intel Core i5      | 8         | 15.69%  |
| Other              | 7         | 13.73%  |
| Intel Xeon         | 5         | 9.8%    |
| Intel Core 2 Duo   | 3         | 5.88%   |
| AMD Ryzen 9        | 3         | 5.88%   |
| AMD Ryzen 5        | 3         | 5.88%   |
| Intel Core i3      | 2         | 3.92%   |
| Intel Celeron      | 2         | 3.92%   |
| AMD Ryzen 7        | 2         | 3.92%   |
| AMD FX             | 2         | 3.92%   |
| Intel Pentium Dual | 1         | 1.96%   |
| Intel Pentium      | 1         | 1.96%   |
| Intel Atom         | 1         | 1.96%   |
| AMD EPYC           | 1         | 1.96%   |
| AMD Athlon         | 1         | 1.96%   |
| AMD A8             | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 17        | 33.33%  |
| 2      | 16        | 31.37%  |
| 8      | 10        | 19.61%  |
| 12     | 2         | 3.92%   |
| 6      | 2         | 3.92%   |
| 16     | 1         | 1.96%   |
| 14     | 1         | 1.96%   |
| 10     | 1         | 1.96%   |
| 3      | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 96.08%  |
| 2      | 2         | 3.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 39        | 76.47%  |
| 1      | 12        | 23.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 7         | 13.73%  |
| Unknown    | 6         | 11.76%  |
| 0x806d1    | 3         | 5.88%   |
| 0x806c1    | 3         | 5.88%   |
| 0x406c4    | 2         | 3.92%   |
| 0x306f2    | 2         | 3.92%   |
| 0x1067a    | 2         | 3.92%   |
| 0x0a201016 | 2         | 3.92%   |
| 0x08108109 | 2         | 3.92%   |
| 0xa0671    | 1         | 1.96%   |
| 0xa0653    | 1         | 1.96%   |
| 0xa0652    | 1         | 1.96%   |
| 0x906ea    | 1         | 1.96%   |
| 0x906e9    | 1         | 1.96%   |
| 0x806ec    | 1         | 1.96%   |
| 0x806ea    | 1         | 1.96%   |
| 0x6fd      | 1         | 1.96%   |
| 0x6fa      | 1         | 1.96%   |
| 0x406e3    | 1         | 1.96%   |
| 0x306e4    | 1         | 1.96%   |
| 0x306d4    | 1         | 1.96%   |
| 0x306c3    | 1         | 1.96%   |
| 0x206c2    | 1         | 1.96%   |
| 0x106c2    | 1         | 1.96%   |
| 0x08701021 | 1         | 1.96%   |
| 0x08600106 | 1         | 1.96%   |
| 0x0830104d | 1         | 1.96%   |
| 0x0810100b | 1         | 1.96%   |
| 0x07030105 | 1         | 1.96%   |
| 0x06000822 | 1         | 1.96%   |
| 0x00000000 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| IvyBridge  | 8         | 15.69%  |
| KabyLake   | 6         | 11.76%  |
| Zen 2      | 5         | 9.8%    |
| Icelake    | 4         | 7.84%   |
| TigerLake  | 3         | 5.88%   |
| Haswell    | 3         | 5.88%   |
| Core       | 3         | 5.88%   |
| Zen+       | 2         | 3.92%   |
| Zen 3      | 2         | 3.92%   |
| Westmere   | 2         | 3.92%   |
| Silvermont | 2         | 3.92%   |
| Piledriver | 2         | 3.92%   |
| Penryn     | 2         | 3.92%   |
| CometLake  | 2         | 3.92%   |
| Zen        | 1         | 1.96%   |
| Skylake    | 1         | 1.96%   |
| Puma       | 1         | 1.96%   |
| Broadwell  | 1         | 1.96%   |
| Bonnell    | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 22        | 37.93%  |
| Nvidia                     | 19        | 32.76%  |
| AMD                        | 16        | 27.59%  |
| Matrox Electronics Systems | 1         | 1.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 5.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 5.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 5.17%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 3.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 3.45%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 3.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 3.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.45%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 3.45%   |
| AMD Renoir                                                                               | 2         | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.45%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 3.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 3.45%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.72%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 1.72%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.72%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1         | 1.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.72%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1         | 1.72%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 1.72%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1         | 1.72%   |
| Nvidia C79 [ION]                                                                         | 1         | 1.72%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.72%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.72%   |
| Intel HD Graphics 620                                                                    | 1         | 1.72%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.72%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.72%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                               | 1         | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.72%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 1.72%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 1.72%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.72%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 33.33%  |
| 1 x AMD        | 15        | 29.41%  |
| 1 x Nvidia     | 12        | 23.53%  |
| Intel + Nvidia | 5         | 9.8%    |
| 1 x Matrox     | 1         | 1.96%   |
| AMD + Nvidia   | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 42        | 82.35%  |
| Proprietary | 8         | 15.69%  |
| Unknown     | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 47.06%  |
| 0.51-1.0   | 8         | 15.69%  |
| 7.01-8.0   | 5         | 9.8%    |
| 0.01-0.5   | 5         | 9.8%    |
| 5.01-6.0   | 3         | 5.88%   |
| 8.01-16.0  | 3         | 5.88%   |
| 1.01-2.0   | 2         | 3.92%   |
| 2.01-3.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 8         | 14.29%  |
| Samsung Electronics  | 7         | 12.5%   |
| LG Display           | 6         | 10.71%  |
| Hewlett-Packard      | 5         | 8.93%   |
| AU Optronics         | 4         | 7.14%   |
| Dell                 | 3         | 5.36%   |
| Ancor Communications | 3         | 5.36%   |
| Sharp                | 2         | 3.57%   |
| Chimei Innolux       | 2         | 3.57%   |
| BenQ                 | 2         | 3.57%   |
| Acer                 | 2         | 3.57%   |
| Wacom                | 1         | 1.79%   |
| UGD                  | 1         | 1.79%   |
| Sony                 | 1         | 1.79%   |
| PANDA                | 1         | 1.79%   |
| Lenovo               | 1         | 1.79%   |
| IOD                  | 1         | 1.79%   |
| Iiyama               | 1         | 1.79%   |
| Goldstar             | 1         | 1.79%   |
| GDH                  | 1         | 1.79%   |
| Apple                | 1         | 1.79%   |
| AOC                  | 1         | 1.79%   |
| Unknown              | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 1.75%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 1.75%   |
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                         | 1         | 1.75%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch               | 1         | 1.75%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.75%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 1.75%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 380x300mm 19.1-inch  | 1         | 1.75%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 1.75%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 1.75%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 1.75%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 1.75%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.75%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 1.75%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.75%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.75%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1         | 1.75%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1         | 1.75%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                  | 1         | 1.75%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 520x320mm 24.0-inch            | 1         | 1.75%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.75%   |
| Hewlett-Packard ALL-in-One HPN4021 1920x1080 476x268mm 21.5-inch      | 1         | 1.75%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1         | 1.75%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 1.75%   |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                   | 1         | 1.75%   |
| GDH CHHWJT GDH0030 1440x900 1150x650mm 52.0-inch                      | 1         | 1.75%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                      | 1         | 1.75%   |
| Dell LCD Monitor P190S 3200x1080                                      | 1         | 1.75%   |
| Dell LCD Monitor DELA026 1920x1200 520x330mm 24.2-inch                | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 1.75%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                 | 1         | 1.75%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 1.75%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                 | 1         | 1.75%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 1         | 1.75%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 1         | 1.75%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 1.75%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 1         | 1.75%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                  | 1         | 1.75%   |
| BenQ VZ2770H BNQ7B3C 1920x1080 598x336mm 27.0-inch                    | 1         | 1.75%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 381x214mm 17.2-inch        | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 1         | 1.75%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                 | 1         | 1.75%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1         | 1.75%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 800x340mm 34.2-inch | 1         | 1.75%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1         | 1.75%   |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 621x341mm 27.9-inch | 1         | 1.75%   |
| Acer GN246HL ACR02F9 1920x1080 530x300mm 24.0-inch                    | 1         | 1.75%   |
| Acer AL1714 ACRAD18 1280x1024 338x270mm 17.0-inch                     | 1         | 1.75%   |
| Unknown                                                               | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 48.15%  |
| 1366x768 (WXGA)    | 10        | 18.52%  |
| 3840x2160 (4K)     | 3         | 5.56%   |
| 1280x1024 (SXGA)   | 3         | 5.56%   |
| 1920x1200 (WUXGA)  | 2         | 3.7%    |
| 1360x768           | 2         | 3.7%    |
| 3440x1440          | 1         | 1.85%   |
| 3200x1080          | 1         | 1.85%   |
| 2560x1440 (QHD)    | 1         | 1.85%   |
| 2256x1504          | 1         | 1.85%   |
| 1680x1050 (WSXGA+) | 1         | 1.85%   |
| 1600x900 (HD+)     | 1         | 1.85%   |
| 1600x1200          | 1         | 1.85%   |
| Unknown            | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 23.64%  |
| 27      | 6         | 10.91%  |
| 24      | 5         | 9.09%   |
| 21      | 5         | 9.09%   |
| 17      | 5         | 9.09%   |
| 13      | 5         | 9.09%   |
| 20      | 3         | 5.45%   |
| 14      | 3         | 5.45%   |
| 18      | 2         | 3.64%   |
| 72      | 1         | 1.82%   |
| 52      | 1         | 1.82%   |
| 34      | 1         | 1.82%   |
| 23      | 1         | 1.82%   |
| 19      | 1         | 1.82%   |
| 16      | 1         | 1.82%   |
| 12      | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 38.89%  |
| 501-600     | 11        | 20.37%  |
| 401-500     | 9         | 16.67%  |
| 351-400     | 5         | 9.26%   |
| 201-300     | 3         | 5.56%   |
| 701-800     | 1         | 1.85%   |
| 601-700     | 1         | 1.85%   |
| 1501-2000   | 1         | 1.85%   |
| 1001-1500   | 1         | 1.85%   |
| Unknown     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 37        | 77.08%  |
| 16/10   | 4         | 8.33%   |
| 5/4     | 3         | 6.25%   |
| 4/3     | 1         | 2.08%   |
| 3/2     | 1         | 2.08%   |
| 21/9    | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 25.93%  |
| 81-90          | 7         | 12.96%  |
| 301-350        | 6         | 11.11%  |
| 151-200        | 6         | 11.11%  |
| 201-250        | 5         | 9.26%   |
| 141-150        | 4         | 7.41%   |
| 251-300        | 3         | 5.56%   |
| 121-130        | 3         | 5.56%   |
| More than 1000 | 2         | 3.7%    |
| 71-80          | 1         | 1.85%   |
| 61-70          | 1         | 1.85%   |
| 351-500        | 1         | 1.85%   |
| Unknown        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 19        | 35.19%  |
| 121-160       | 15        | 27.78%  |
| 101-120       | 14        | 25.93%  |
| 1-50          | 2         | 3.7%    |
| 161-240       | 2         | 3.7%    |
| More than 240 | 1         | 1.85%   |
| Unknown       | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 39        | 76.47%  |
| 2     | 6         | 11.76%  |
| 0     | 4         | 7.84%   |
| 4     | 1         | 1.96%   |
| 3     | 1         | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 39.19%  |
| Intel                    | 29        | 39.19%  |
| Qualcomm Atheros         | 4         | 5.41%   |
| Broadcom                 | 4         | 5.41%   |
| Ralink Technology        | 2         | 2.7%    |
| Broadcom Limited         | 2         | 2.7%    |
| Ralink                   | 1         | 1.35%   |
| Nvidia                   | 1         | 1.35%   |
| Marvell Technology Group | 1         | 1.35%   |
| Hewlett-Packard          | 1         | 1.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 21.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 3.3%    |
| Intel Wi-Fi 6 AX200                                               | 3         | 3.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.2%    |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.2%    |
| Ralink MT7601U Wireless Adapter                                   | 2         | 2.2%    |
| Intel Wireless 8265 / 8275                                        | 2         | 2.2%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.2%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.1%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.1%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.1%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 1.1%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.1%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.1%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 1.1%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.1%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.1%    |
| Intel Wireless-AC 9260                                            | 1         | 1.1%    |
| Intel Wireless 7260                                               | 1         | 1.1%    |
| Intel Wireless 3165                                               | 1         | 1.1%    |
| Intel I211 Gigabit Network Connection                             | 1         | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.1%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.1%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.1%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.1%    |
| HP hs2350 HSPA+ MobileBroadband                                   | 1         | 1.1%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.1%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.1%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.1%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.1%    |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 1         | 1.1%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 1.1%    |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 60.53%  |
| Realtek Semiconductor | 5         | 13.16%  |
| Qualcomm Atheros      | 4         | 10.53%  |
| Ralink Technology     | 2         | 5.26%   |
| Broadcom              | 2         | 5.26%   |
| Ralink                | 1         | 2.63%   |
| Broadcom Limited      | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 7.89%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 7.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 7.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 5.26%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 5.26%   |
| Intel Wireless 8265 / 8275                                     | 2         | 5.26%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 5.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 5.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.63%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 2.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 2.63%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 2.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.63%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1         | 2.63%   |
| Intel Wireless-AC 9260                                         | 1         | 2.63%   |
| Intel Wireless 7260                                            | 1         | 2.63%   |
| Intel Wireless 3165                                            | 1         | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.63%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.63%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                        | 1         | 2.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.63%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 58%     |
| Intel                    | 14        | 28%     |
| Broadcom                 | 3         | 6%      |
| Qualcomm Atheros         | 1         | 2%      |
| Nvidia                   | 1         | 2%      |
| Marvell Technology Group | 1         | 2%      |
| Broadcom Limited         | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 38.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.85%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 3.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.85%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.92%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.92%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.92%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.92%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.92%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.92%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.92%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.92%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.92%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.92%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.92%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.92%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.92%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.92%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 54.12%  |
| WiFi     | 38        | 44.71%  |
| Modem    | 1         | 1.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 50.91%  |
| Ethernet | 27        | 49.09%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 56.86%  |
| 1     | 18        | 35.29%  |
| 4     | 2         | 3.92%   |
| 3     | 2         | 3.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 88.24%  |
| Yes  | 6         | 11.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 19        | 54.29%  |
| Realtek Semiconductor    | 4         | 11.43%  |
| Cambridge Silicon Radio  | 4         | 11.43%  |
| Broadcom                 | 4         | 11.43%  |
| Apple                    | 2         | 5.71%   |
| Micro Star International | 1         | 2.86%   |
| Foxconn / Hon Hai        | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 14.29%  |
| Intel AX201 Bluetooth                               | 5         | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 11.43%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 8.57%   |
| Intel AX210 Bluetooth                               | 3         | 8.57%   |
| Intel AX200 Bluetooth                               | 3         | 8.57%   |
| Realtek Bluetooth Radio                             | 1         | 2.86%   |
| Micro Star International Bluetooth Dongle           | 1         | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.86%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 2.86%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.86%   |
| Broadcom BCM20702A0                                 | 1         | 2.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.86%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.86%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 32        | 43.24%  |
| Nvidia                 | 17        | 22.97%  |
| AMD                    | 17        | 22.97%  |
| Creative Labs          | 4         | 5.41%   |
| C-Media Electronics    | 2         | 2.7%    |
| Generalplus Technology | 1         | 1.35%   |
| ASUSTek Computer       | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 7.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.88%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 4.71%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 4.71%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 3.53%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 3.53%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 3.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.53%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.35%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2         | 2.35%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 2.35%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 2.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 2.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.18%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.18%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.18%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.18%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.18%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.18%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.18%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.18%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 1.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.18%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.18%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 1.18%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1         | 1.18%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1         | 1.18%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 1         | 1.18%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 1.18%   |
| ASUSTek Computer XONAR SOUND CARD                                                                 | 1         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.18%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.18%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.18%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.18%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.18%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 12        | 20.69%  |
| SK hynix            | 11        | 18.97%  |
| Samsung Electronics | 8         | 13.79%  |
| Crucial             | 5         | 8.62%   |
| Micron Technology   | 3         | 5.17%   |
| Unknown             | 2         | 3.45%   |
| Team                | 2         | 3.45%   |
| Corsair             | 2         | 3.45%   |
| A-DATA Technology   | 2         | 3.45%   |
| Transcend           | 1         | 1.72%   |
| Strontium           | 1         | 1.72%   |
| Silicon Power       | 1         | 1.72%   |
| Neo Forza           | 1         | 1.72%   |
| Nanya Technology    | 1         | 1.72%   |
| Goodram             | 1         | 1.72%   |
| GLOWAY              | 1         | 1.72%   |
| G.Skill             | 1         | 1.72%   |
| Essencore Limited   | 1         | 1.72%   |
| AMD                 | 1         | 1.72%   |
| Unknown             | 1         | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                                 | 2         | 3.13%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s                | 1         | 1.56%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s                  | 1         | 1.56%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s                  | 1         | 1.56%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s                | 1         | 1.56%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s          | 1         | 1.56%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                     | 1         | 1.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 1.56%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s              | 1         | 1.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 1.56%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 1.56%   |
| SK hynix RAM HMT31GR7BFR4A-H9 16GB DIMM 1333MT/s                     | 1         | 1.56%   |
| SK hynix RAM HMT125R7BFR8C-H9 4GB DIMM 1333MT/s                      | 1         | 1.56%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.56%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s               | 1         | 1.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 1.56%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 1.56%   |
| SK hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s              | 1         | 1.56%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8192MB Row Of Chips LPDDR3 1867MT/s  | 1         | 1.56%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s            | 1         | 1.56%   |
| Samsung RAM M471B5273DH0-YK0 4096MB SODIMM DDR3 1600MT/s             | 1         | 1.56%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 1.56%   |
| Samsung RAM M471A5244BB0-CPB 4096MB SODIMM DDR4 2400MT/s             | 1         | 1.56%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s            | 1         | 1.56%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s                 | 1         | 1.56%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s                  | 1         | 1.56%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s                  | 1         | 1.56%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                  | 1         | 1.56%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 1.56%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.56%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.56%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.56%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 1.56%   |
| Kingston RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 1.56%   |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s                      | 1         | 1.56%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.56%   |
| Kingston RAM KKRVFX-MIE 8192MB SODIMM DDR4 3200MT/s                  | 1         | 1.56%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s                 | 1         | 1.56%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                 | 1         | 1.56%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                | 1         | 1.56%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s                  | 1         | 1.56%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 1.56%   |
| Kingston RAM ACR128X64D2S800C6 1GB SODIMM DDR2 975MT/s               | 1         | 1.56%   |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 1.56%   |
| Kingston RAM 9905711-032.A00G 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.56%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 1.56%   |
| Goodram RAM GR2400S464L17S/4G 4096MB SODIMM DDR4 2400MT/s            | 1         | 1.56%   |
| GLOWAY RAM TYA4U2666D19161C 16GB DIMM DDR4 2667MT/s                  | 1         | 1.56%   |
| G.Skill RAM F4-3200C16-16GTZSW 16384MB DIMM DDR4 3200MT/s            | 1         | 1.56%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 1.56%   |
| Crucial RAM Module 2048MB SODIMM DDR2 667MT/s                        | 1         | 1.56%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 1.56%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 1.56%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s               | 1         | 1.56%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s                | 1         | 1.56%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 2667MT/s                | 1         | 1.56%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s                 | 1         | 1.56%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 1.56%   |
| AMD RAM R534G1601S1SL 4GB DIMM DDR3 1600MT/s                         | 1         | 1.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 25        | 51.02%  |
| DDR3    | 17        | 34.69%  |
| DDR2    | 3         | 6.12%   |
| SDRAM   | 2         | 4.08%   |
| LPDDR3  | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 26        | 54.17%  |
| DIMM         | 19        | 39.58%  |
| Row Of Chips | 1         | 2.08%   |
| RIMM         | 1         | 2.08%   |
| FB-DIMM      | 1         | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 19        | 35.19%  |
| 4096  | 19        | 35.19%  |
| 16384 | 7         | 12.96%  |
| 2048  | 4         | 7.41%   |
| 32768 | 3         | 5.56%   |
| 1024  | 2         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 24.53%  |
| 3200    | 12        | 22.64%  |
| 2667    | 5         | 9.43%   |
| 2400    | 5         | 9.43%   |
| 1333    | 4         | 7.55%   |
| 3600    | 2         | 3.77%   |
| 2133    | 2         | 3.77%   |
| 667     | 2         | 3.77%   |
| Unknown | 2         | 3.77%   |
| 65535   | 1         | 1.89%   |
| 3800    | 1         | 1.89%   |
| 1867    | 1         | 1.89%   |
| 1866    | 1         | 1.89%   |
| 975     | 1         | 1.89%   |
| 701     | 1         | 1.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Dell                | 1         | 25%     |
| Canon               | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 1         | 25%     |
| HP OfficeJet Pro 9010 series | 1         | 25%     |
| Dell 2330d Laser Printer     | 1         | 25%     |
| Canon CanoScan LiDE 300      | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 21.88%  |
| Acer                                   | 7         | 21.88%  |
| Logitech                               | 5         | 15.63%  |
| Microdia                               | 4         | 12.5%   |
| Realtek Semiconductor                  | 2         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.25%   |
| Syntek                                 | 1         | 3.13%   |
| Samsung Electronics                    | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Luxvisions Innotech Limited            | 1         | 3.13%   |
| Apple                                  | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                                 | 3         | 9.38%   |
| Logitech Webcam C270                                           | 2         | 6.25%   |
| Acer BisonCam,NB Pro                                           | 2         | 6.25%   |
| Syntek USB2.0 Camera                                           | 1         | 3.13%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 3.13%   |
| Realtek Laptop Camera                                          | 1         | 3.13%   |
| Realtek EasyCamera                                             | 1         | 3.13%   |
| Quanta HP Webcam                                               | 1         | 3.13%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 3.13%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 3.13%   |
| Microdia Integrated Webcam                                     | 1         | 3.13%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 3.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 3.13%   |
| Logitech QuickCam Pro 9000                                     | 1         | 3.13%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 3.13%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 3.13%   |
| Chicony Web Camera - FHD                                       | 1         | 3.13%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 3.13%   |
| Chicony Integrated Camera                                      | 1         | 3.13%   |
| Chicony HP TrueVision HD Camera                                | 1         | 3.13%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 3.13%   |
| Chicony HP HD Camera                                           | 1         | 3.13%   |
| Chicony FJ Camera                                              | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP 5M Camera            | 1         | 3.13%   |
| Apple Built-in iSight                                          | 1         | 3.13%   |
| Acer ThinkPad Integrated Camera                                | 1         | 3.13%   |
| Acer Integrated Camera                                         | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| Synaptics        | 2         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 2         | 50%     |
| Validity Sensors VFS300 Fingerprint Reader | 1         | 25%     |
| Validity Sensors Synaptics WBDI            | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 37        | 72.55%  |
| 1     | 10        | 19.61%  |
| 2     | 2         | 3.92%   |
| 4     | 1         | 1.96%   |
| 3     | 1         | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 4         | 19.05%  |
| Sound                    | 3         | 14.29%  |
| Graphics card            | 3         | 14.29%  |
| Unassigned class         | 2         | 9.52%   |
| Net/wireless             | 2         | 9.52%   |
| Multimedia controller    | 2         | 9.52%   |
| Communication controller | 2         | 9.52%   |
| Net/ethernet             | 1         | 4.76%   |
| Chipcard                 | 1         | 4.76%   |
| Bluetooth                | 1         | 4.76%   |

