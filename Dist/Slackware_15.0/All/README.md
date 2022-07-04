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

Total: 54

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 10        | 20.83%  |
| 5.15.27           | 4         | 8.33%   |
| 5.17.2            | 2         | 4.17%   |
| 5.17.1            | 2         | 4.17%   |
| 5.16.13           | 2         | 4.17%   |
| 5.15.30-Unraid    | 2         | 4.17%   |
| 5.13.8            | 2         | 4.17%   |
| 5.17.5            | 1         | 2.08%   |
| 5.17.0-custom     | 1         | 2.08%   |
| 5.16.9-joe1       | 1         | 2.08%   |
| 5.16.18           | 1         | 2.08%   |
| 5.16.12           | 1         | 2.08%   |
| 5.16.11           | 1         | 2.08%   |
| 5.15.6            | 1         | 2.08%   |
| 5.15.37.a         | 1         | 2.08%   |
| 5.15.33.kjh       | 1         | 2.08%   |
| 5.15.21-hardened1 | 1         | 2.08%   |
| 5.15.14           | 1         | 2.08%   |
| 5.15.13           | 1         | 2.08%   |
| 5.15.1            | 1         | 2.08%   |
| 5.14.9            | 1         | 2.08%   |
| 5.14.8            | 1         | 2.08%   |
| 5.14.15-Unraid    | 1         | 2.08%   |
| 5.14.15           | 1         | 2.08%   |
| 5.14.11           | 1         | 2.08%   |
| 5.14.10           | 1         | 2.08%   |
| 5.14.0            | 1         | 2.08%   |
| 5.13.5            | 1         | 2.08%   |
| 5.13.12           | 1         | 2.08%   |
| 5.13.11           | 1         | 2.08%   |
| 5.10.91           | 1         | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 10        | 20.83%  |
| 5.15.27 | 4         | 8.33%   |
| 5.17.2  | 2         | 4.17%   |
| 5.17.1  | 2         | 4.17%   |
| 5.16.13 | 2         | 4.17%   |
| 5.15.30 | 2         | 4.17%   |
| 5.14.15 | 2         | 4.17%   |
| 5.13.8  | 2         | 4.17%   |
| 5.17.5  | 1         | 2.08%   |
| 5.17.0  | 1         | 2.08%   |
| 5.16.9  | 1         | 2.08%   |
| 5.16.18 | 1         | 2.08%   |
| 5.16.12 | 1         | 2.08%   |
| 5.16.11 | 1         | 2.08%   |
| 5.15.6  | 1         | 2.08%   |
| 5.15.37 | 1         | 2.08%   |
| 5.15.33 | 1         | 2.08%   |
| 5.15.21 | 1         | 2.08%   |
| 5.15.14 | 1         | 2.08%   |
| 5.15.13 | 1         | 2.08%   |
| 5.15.1  | 1         | 2.08%   |
| 5.14.9  | 1         | 2.08%   |
| 5.14.8  | 1         | 2.08%   |
| 5.14.11 | 1         | 2.08%   |
| 5.14.10 | 1         | 2.08%   |
| 5.14.0  | 1         | 2.08%   |
| 5.13.5  | 1         | 2.08%   |
| 5.13.12 | 1         | 2.08%   |
| 5.13.11 | 1         | 2.08%   |
| 5.10.91 | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 23        | 48.94%  |
| 5.17    | 6         | 12.77%  |
| 5.16    | 6         | 12.77%  |
| 5.14    | 6         | 12.77%  |
| 5.13    | 5         | 10.64%  |
| 5.10    | 1         | 2.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 47        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 24        | 50%     |
| XFCE      | 11        | 22.92%  |
| Unknown   | 7         | 14.58%  |
| GNOME     | 2         | 4.17%   |
| xwmconfig | 1         | 2.08%   |
| MATE      | 1         | 2.08%   |
| KDE       | 1         | 2.08%   |
| FVWM      | 1         | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 26        | 53.06%  |
| Tty     | 17        | 34.69%  |
| Wayland | 3         | 6.12%   |
| Unknown | 3         | 6.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 30        | 63.83%  |
| Unknown | 9         | 19.15%  |
| XDM     | 6         | 12.77%  |
| LightDM | 2         | 4.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 36        | 76.6%   |
| Unknown     | 4         | 8.51%   |
| ru_RU       | 1         | 2.13%   |
| pt_BR       | 1         | 2.13%   |
| it_IT       | 1         | 2.13%   |
| fr_FR       | 1         | 2.13%   |
| es_ES.UTF8  | 1         | 2.13%   |
| en_US.ASCII | 1         | 2.13%   |
| de_DE       | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 27        | 57.45%  |
| BIOS | 20        | 42.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 32        | 68.09%  |
| Btrfs   | 7         | 14.89%  |
| Overlay | 4         | 8.51%   |
| Xfs     | 2         | 4.26%   |
| Zfs     | 1         | 2.13%   |
| F2fs    | 1         | 2.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 36        | 75%     |
| MBR     | 9         | 18.75%  |
| Unknown | 3         | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 70.83%  |
| Yes       | 14        | 29.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 63.83%  |
| Yes       | 17        | 36.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| MSI                 | 9         | 19.15%  |
| Hewlett-Packard     | 9         | 19.15%  |
| Lenovo              | 5         | 10.64%  |
| Dell                | 5         | 10.64%  |
| ASUSTek Computer    | 4         | 8.51%   |
| ASRock              | 3         | 6.38%   |
| Apple               | 2         | 4.26%   |
| TYAN Computer       | 1         | 2.13%   |
| System76            | 1         | 2.13%   |
| Sony                | 1         | 2.13%   |
| Notebook            | 1         | 2.13%   |
| Gigabyte Technology | 1         | 2.13%   |
| Framework           | 1         | 2.13%   |
| Dynabook            | 1         | 2.13%   |
| Biostar             | 1         | 2.13%   |
| Acer                | 1         | 2.13%   |
| Unknown             | 1         | 2.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| TYAN S7012                               | 1         | 2.13%   |
| System76 Oryx Pro                        | 1         | 2.13%   |
| Sony SVE1713A1EW                         | 1         | 2.13%   |
| Notebook X170KM-G                        | 1         | 2.13%   |
| MSI MS-7C52                              | 1         | 2.13%   |
| MSI MS-7C02                              | 1         | 2.13%   |
| MSI MS-7788                              | 1         | 2.13%   |
| MSI MS-7693                              | 1         | 2.13%   |
| MSI MS-7529                              | 1         | 2.13%   |
| MSI MS-7365                              | 1         | 2.13%   |
| MSI Modern 14 B11MO                      | 1         | 2.13%   |
| MSI GP76 Leopard 11UG                    | 1         | 2.13%   |
| MSI GE76 Raider 11UE                     | 1         | 2.13%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 2.13%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 2.13%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 2.13%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 2.13%   |
| Lenovo H50-05 90BH001WIX                 | 1         | 2.13%   |
| HP Z440 Workstation                      | 1         | 2.13%   |
| HP xw8400 Workstation                    | 1         | 2.13%   |
| HP ProBook 6570b                         | 1         | 2.13%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 2.13%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 2.13%   |
| HP Laptop 15-bs1xx                       | 1         | 2.13%   |
| HP EliteBook 840 G5                      | 1         | 2.13%   |
| HP 245 G7 Notebook PC                    | 1         | 2.13%   |
| HP 205 G4 22 All-in-One PC               | 1         | 2.13%   |
| Gigabyte N3160TN                         | 1         | 2.13%   |
| Framework Laptop                         | 1         | 2.13%   |
| Dynabook P1-C7MP-BL                      | 1         | 2.13%   |
| Dell Vostro 3500                         | 1         | 2.13%   |
| Dell Precision M4700                     | 1         | 2.13%   |
| Dell PowerEdge R6515                     | 1         | 2.13%   |
| Dell Latitude 3520                       | 1         | 2.13%   |
| Dell Inspiron 15-3552                    | 1         | 2.13%   |
| Biostar X470GTA                          | 1         | 2.13%   |
| ASUS TUF B450-PLUS GAMING                | 1         | 2.13%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 2.13%   |
| ASUS PRIME Z390-A                        | 1         | 2.13%   |
| ASUS All Series                          | 1         | 2.13%   |
| ASRock N68-S3 FX                         | 1         | 2.13%   |
| ASRock H410M-ITX/ac                      | 1         | 2.13%   |
| ASRock H270 Pro4                         | 1         | 2.13%   |
| Apple Macmini6,2                         | 1         | 2.13%   |
| Apple iMac7,1                            | 1         | 2.13%   |
| Acer Aspire R3610                        | 1         | 2.13%   |
| Unknown                                  | 1         | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 6.38%   |
| HP Pavilion         | 2         | 4.26%   |
| TYAN S7012          | 1         | 2.13%   |
| System76 Oryx       | 1         | 2.13%   |
| Sony SVE1713A1EW    | 1         | 2.13%   |
| Notebook X170KM-G   | 1         | 2.13%   |
| MSI MS-7C52         | 1         | 2.13%   |
| MSI MS-7C02         | 1         | 2.13%   |
| MSI MS-7788         | 1         | 2.13%   |
| MSI MS-7693         | 1         | 2.13%   |
| MSI MS-7529         | 1         | 2.13%   |
| MSI MS-7365         | 1         | 2.13%   |
| MSI Modern          | 1         | 2.13%   |
| MSI GP76            | 1         | 2.13%   |
| MSI GE76            | 1         | 2.13%   |
| Lenovo IdeaPad      | 1         | 2.13%   |
| Lenovo H50-05       | 1         | 2.13%   |
| HP Z440             | 1         | 2.13%   |
| HP xw8400           | 1         | 2.13%   |
| HP ProBook          | 1         | 2.13%   |
| HP Laptop           | 1         | 2.13%   |
| HP EliteBook        | 1         | 2.13%   |
| HP 245              | 1         | 2.13%   |
| HP 205              | 1         | 2.13%   |
| Gigabyte N3160TN    | 1         | 2.13%   |
| Framework Laptop    | 1         | 2.13%   |
| Dynabook P1-C7MP-BL | 1         | 2.13%   |
| Dell Vostro         | 1         | 2.13%   |
| Dell Precision      | 1         | 2.13%   |
| Dell PowerEdge      | 1         | 2.13%   |
| Dell Latitude       | 1         | 2.13%   |
| Dell Inspiron       | 1         | 2.13%   |
| Biostar X470GTA     | 1         | 2.13%   |
| ASUS TUF            | 1         | 2.13%   |
| ASUS ROG            | 1         | 2.13%   |
| ASUS PRIME          | 1         | 2.13%   |
| ASUS All            | 1         | 2.13%   |
| ASRock N68-S3       | 1         | 2.13%   |
| ASRock H410M-ITX    | 1         | 2.13%   |
| ASRock H270         | 1         | 2.13%   |
| Apple Macmini6      | 1         | 2.13%   |
| Apple iMac7         | 1         | 2.13%   |
| Acer Aspire         | 1         | 2.13%   |
| Unknown             | 1         | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 8         | 17.02%  |
| 2020 | 7         | 14.89%  |
| 2012 | 5         | 10.64%  |
| 2019 | 4         | 8.51%   |
| 2017 | 4         | 8.51%   |
| 2018 | 3         | 6.38%   |
| 2015 | 3         | 6.38%   |
| 2011 | 3         | 6.38%   |
| 2016 | 2         | 4.26%   |
| 2014 | 2         | 4.26%   |
| 2009 | 2         | 4.26%   |
| 2007 | 2         | 4.26%   |
| 2010 | 1         | 2.13%   |
| 2008 | 1         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 23        | 48.94%  |
| Desktop    | 19        | 40.43%  |
| All in one | 2         | 4.26%   |
| Server     | 2         | 4.26%   |
| Mini pc    | 1         | 2.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 47        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 95.74%  |
| Yes  | 2         | 4.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 10        | 21.28%  |
| 3.01-4.0    | 9         | 19.15%  |
| 8.01-16.0   | 8         | 17.02%  |
| 4.01-8.0    | 7         | 14.89%  |
| 32.01-64.0  | 5         | 10.64%  |
| 64.01-256.0 | 4         | 8.51%   |
| 24.01-32.0  | 2         | 4.26%   |
| 1.01-2.0    | 2         | 4.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 13        | 26.53%  |
| 4.01-8.0   | 12        | 24.49%  |
| 2.01-3.0   | 11        | 22.45%  |
| 0.51-1.0   | 6         | 12.24%  |
| 3.01-4.0   | 2         | 4.08%   |
| 16.01-24.0 | 2         | 4.08%   |
| 0.01-0.5   | 2         | 4.08%   |
| 32.01-64.0 | 1         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 44.68%  |
| 2      | 12        | 25.53%  |
| 4      | 5         | 10.64%  |
| 3      | 5         | 10.64%  |
| 6      | 2         | 4.26%   |
| 9      | 1         | 2.13%   |
| 0      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 63.83%  |
| Yes       | 17        | 36.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 91.49%  |
| No        | 4         | 8.51%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 74.47%  |
| No        | 12        | 25.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 65.96%  |
| No        | 16        | 34.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 11        | 23.4%   |
| Kazakhstan   | 6         | 12.77%  |
| South Africa | 3         | 6.38%   |
| Japan        | 3         | 6.38%   |
| Italy        | 3         | 6.38%   |
| Brazil       | 3         | 6.38%   |
| UK           | 2         | 4.26%   |
| Spain        | 2         | 4.26%   |
| Greece       | 2         | 4.26%   |
| Canada       | 2         | 4.26%   |
| Switzerland  | 1         | 2.13%   |
| Sweden       | 1         | 2.13%   |
| Serbia       | 1         | 2.13%   |
| Russia       | 1         | 2.13%   |
| Portugal     | 1         | 2.13%   |
| Netherlands  | 1         | 2.13%   |
| Mexico       | 1         | 2.13%   |
| Hong Kong    | 1         | 2.13%   |
| Germany      | 1         | 2.13%   |
| France       | 1         | 2.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 4         | 8.51%   |
| Tsukuba           | 2         | 4.26%   |
| Karaganda         | 2         | 4.26%   |
| Chania            | 2         | 4.26%   |
| Cape Town         | 2         | 4.26%   |
| Toronto           | 1         | 2.13%   |
| St Petersburg     | 1         | 2.13%   |
| Skövde           | 1         | 2.13%   |
| Sham Shui Po      | 1         | 2.13%   |
| Santa Cruz do Sul | 1         | 2.13%   |
| Saint Paul        | 1         | 2.13%   |
| Round Rock        | 1         | 2.13%   |
| Rome              | 1         | 2.13%   |
| Reno              | 1         | 2.13%   |
| Porto Alegre      | 1         | 2.13%   |
| Plainwell         | 1         | 2.13%   |
| Ōtsu             | 1         | 2.13%   |
| Oberstreit        | 1         | 2.13%   |
| Naaldwijk         | 1         | 2.13%   |
| Montreal          | 1         | 2.13%   |
| Milwaukee         | 1         | 2.13%   |
| Milan             | 1         | 2.13%   |
| Mexico City       | 1         | 2.13%   |
| Mead              | 1         | 2.13%   |
| McKinney          | 1         | 2.13%   |
| London            | 1         | 2.13%   |
| Lisbon            | 1         | 2.13%   |
| Liebefeld         | 1         | 2.13%   |
| League City       | 1         | 2.13%   |
| Johannesburg      | 1         | 2.13%   |
| Hayward           | 1         | 2.13%   |
| Granada           | 1         | 2.13%   |
| Frosinone         | 1         | 2.13%   |
| Fortaleza         | 1         | 2.13%   |
| Chicago           | 1         | 2.13%   |
| Chessy            | 1         | 2.13%   |
| Belgrade          | 1         | 2.13%   |
| Belfast           | 1         | 2.13%   |
| Algeciras         | 1         | 2.13%   |
| Abingdon          | 1         | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 21     | 18.99%  |
| Seagate             | 14        | 22     | 17.72%  |
| WDC                 | 11        | 13     | 13.92%  |
| Toshiba             | 5         | 7      | 6.33%   |
| Kingston            | 4         | 5      | 5.06%   |
| Hitachi             | 4         | 7      | 5.06%   |
| HGST                | 3         | 3      | 3.8%    |
| Crucial             | 3         | 3      | 3.8%    |
| SK hynix            | 2         | 2      | 2.53%   |
| SanDisk             | 2         | 2      | 2.53%   |
| Hewlett-Packard     | 2         | 3      | 2.53%   |
| Gigabyte Technology | 2         | 2      | 2.53%   |
| ZHITAI              | 1         | 2      | 1.27%   |
| Plextor             | 1         | 1      | 1.27%   |
| Patriot             | 1         | 1      | 1.27%   |
| KIOXIA              | 1         | 1      | 1.27%   |
| JMicron Technology  | 1         | 1      | 1.27%   |
| Intenso             | 1         | 1      | 1.27%   |
| Intel               | 1         | 1      | 1.27%   |
| Goodram             | 1         | 1      | 1.27%   |
| External            | 1         | 1      | 1.27%   |
| China               | 1         | 1      | 1.27%   |
| Apple               | 1         | 1      | 1.27%   |
| A-DATA Technology   | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 2.22%   |
| WDC WD10SPZX-60Z10T0 1TB                | 2         | 2.22%   |
| Samsung SSD 970 EVO 250GB               | 2         | 2.22%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 2.22%   |
| ZHITAI SC001 Active 1TB SSD             | 1         | 1.11%   |
| ZHITAI PC005 Active 512GB               | 1         | 1.11%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 1         | 1.11%   |
| WDC WD40EJRX-89T1XY0 4TB                | 1         | 1.11%   |
| WDC WD400BD-60LTA0 40GB                 | 1         | 1.11%   |
| WDC WD3200AAJS-65B4A0 320GB             | 1         | 1.11%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 1.11%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 1.11%   |
| WDC WD10JPVT-08A1YT2 1TB                | 1         | 1.11%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB      | 1         | 1.11%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 1.11%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.11%   |
| Toshiba MD04ABA400V 4TB                 | 1         | 1.11%   |
| Toshiba HDWD240 4TB                     | 1         | 1.11%   |
| Toshiba DT01ACA300 3TB                  | 1         | 1.11%   |
| SK hynix HFM001TD3JX013N 1TB            | 1         | 1.11%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 1         | 1.11%   |
| Seagate ST4000VX000-2AG166 4TB          | 1         | 1.11%   |
| Seagate ST4000DM000-1F2168 4TB          | 1         | 1.11%   |
| Seagate ST380011A 80GB                  | 1         | 1.11%   |
| Seagate ST3500630AS 500GB               | 1         | 1.11%   |
| Seagate ST3250820AS Q 250GB             | 1         | 1.11%   |
| Seagate ST3160211AS 160GB               | 1         | 1.11%   |
| Seagate ST3000VX006-1HH166 3TB          | 1         | 1.11%   |
| Seagate ST3000NM0033-9ZM178 3TB         | 1         | 1.11%   |
| Seagate ST3000DM001-1ER166 3TB          | 1         | 1.11%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 1.11%   |
| Seagate ST2000DL003-9VT166 2TB          | 1         | 1.11%   |
| Seagate ST1000NM004A-2MN130 1TB         | 1         | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.11%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 1.11%   |
| Seagate ST1000DM003-1SB102 1TB          | 1         | 1.11%   |
| Seagate ST1000DM003-1ER162 1TB          | 1         | 1.11%   |
| Seagate ST10000DM005-3AW101 10TB        | 1         | 1.11%   |
| Seagate Expansion+ Desk 4TB             | 1         | 1.11%   |
| SanDisk Ultra II 960GB SSD              | 1         | 1.11%   |
| SanDisk SDSSDA240G 240GB                | 1         | 1.11%   |
| Samsung SSD 980 PRO 500GB               | 1         | 1.11%   |
| Samsung SSD 980 PRO 2TB                 | 1         | 1.11%   |
| Samsung SSD 970 EVO Plus 500GB          | 1         | 1.11%   |
| Samsung SSD 970 EVO Plus 2TB            | 1         | 1.11%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 1.11%   |
| Samsung SSD 970 EVO 2TB                 | 1         | 1.11%   |
| Samsung SSD 870 EVO 1TB                 | 1         | 1.11%   |
| Samsung SSD 860 QVO 2TB                 | 1         | 1.11%   |
| Samsung SSD 860 EVO mSATA 500GB         | 1         | 1.11%   |
| Samsung SSD 860 EVO 500GB               | 1         | 1.11%   |
| Samsung SSD 860 500GB                   | 1         | 1.11%   |
| Samsung SSD 840 Series 250GB            | 1         | 1.11%   |
| Samsung NVMe SSD Drive 256GB            | 1         | 1.11%   |
| Samsung MZVLQ512HALU-000H1 512GB        | 1         | 1.11%   |
| Samsung MZVL21T0HCLR-00B00 1TB          | 1         | 1.11%   |
| Samsung MZVKW512HMJP-000H1 512GB        | 1         | 1.11%   |
| Samsung MZHPV512HDGL-00000 512GB SSD    | 1         | 1.11%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD    | 1         | 1.11%   |
| Plextor PX-128M6S 128GB SSD             | 1         | 1.11%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 14        | 22     | 37.84%  |
| WDC                | 10        | 12     | 27.03%  |
| Toshiba            | 5         | 7      | 13.51%  |
| Hitachi            | 4         | 7      | 10.81%  |
| HGST               | 3         | 3      | 8.11%   |
| JMicron Technology | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 26.09%  |
| Kingston            | 4         | 5      | 17.39%  |
| SanDisk             | 2         | 2      | 8.7%    |
| Crucial             | 2         | 2      | 8.7%    |
| ZHITAI              | 1         | 1      | 4.35%   |
| Plextor             | 1         | 1      | 4.35%   |
| Patriot             | 1         | 1      | 4.35%   |
| Intenso             | 1         | 1      | 4.35%   |
| Hewlett-Packard     | 1         | 1      | 4.35%   |
| Goodram             | 1         | 1      | 4.35%   |
| Gigabyte Technology | 1         | 1      | 4.35%   |
| China               | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 52     | 37.88%  |
| SSD  | 21        | 26     | 31.82%  |
| NVMe | 20        | 25     | 30.3%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 76     | 60.71%  |
| NVMe | 19        | 24     | 33.93%  |
| SAS  | 3         | 3      | 5.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 33     | 47.27%  |
| 0.51-1.0   | 13        | 17     | 23.64%  |
| 1.01-2.0   | 6         | 9      | 10.91%  |
| 3.01-4.0   | 5         | 10     | 9.09%   |
| 2.01-3.0   | 3         | 7      | 5.45%   |
| 4.01-10.0  | 2         | 2      | 3.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 11        | 22.92%  |
| 101-250        | 10        | 20.83%  |
| 251-500        | 9         | 18.75%  |
| 1-20           | 5         | 10.42%  |
| 1001-2000      | 4         | 8.33%   |
| Unknown        | 4         | 8.33%   |
| More than 3000 | 2         | 4.17%   |
| 2001-3000      | 2         | 4.17%   |
| 51-100         | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 27.66%  |
| 1-20           | 9         | 19.15%  |
| 251-500        | 7         | 14.89%  |
| 21-50          | 6         | 12.77%  |
| 501-1000       | 5         | 10.64%  |
| Unknown        | 4         | 8.51%   |
| More than 3000 | 1         | 2.13%   |
| 1001-2000      | 1         | 2.13%   |
| 51-100         | 1         | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 1      | 7.14%   |
| WDC WD3200AAJS-65B4A0 320GB         | 1         | 1      | 7.14%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 7.14%   |
| Seagate ST380011A 80GB              | 1         | 1      | 7.14%   |
| Seagate ST3500630AS 500GB           | 1         | 1      | 7.14%   |
| Seagate ST3000VX006-1HH166 3TB      | 1         | 1      | 7.14%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 7.14%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 2      | 7.14%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 7.14%   |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 7.14%   |
| Hitachi HUA723030ALA640 3TB         | 1         | 1      | 7.14%   |
| Hitachi HDS721016CLA382 160GB       | 1         | 1      | 7.14%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 7.14%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 6      | 30.77%  |
| WDC                 | 3         | 4      | 23.08%  |
| Hitachi             | 2         | 2      | 15.38%  |
| HGST                | 2         | 2      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Plextor             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 6      | 36.36%  |
| WDC     | 3         | 4      | 27.27%  |
| Hitachi | 2         | 2      | 18.18%  |
| HGST    | 2         | 2      | 18.18%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 14     | 81.82%  |
| SSD  | 2         | 2      | 18.18%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 40        | 76     | 70.18%  |
| Malfunc  | 11        | 16     | 19.3%   |
| Detected | 6         | 11     | 10.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 27        | 42.19%  |
| AMD                         | 11        | 17.19%  |
| Samsung Electronics         | 10        | 15.63%  |
| SK hynix                    | 2         | 3.13%   |
| Nvidia                      | 2         | 3.13%   |
| Yangtze Memory Technologies | 1         | 1.56%   |
| SanDisk                     | 1         | 1.56%   |
| Realtek Semiconductor       | 1         | 1.56%   |
| Phison Electronics          | 1         | 1.56%   |
| Micron/Crucial Technology   | 1         | 1.56%   |
| Marvell Technology Group    | 1         | 1.56%   |
| KIOXIA                      | 1         | 1.56%   |
| JMicron Technology          | 1         | 1.56%   |
| Broadcom / LSI              | 1         | 1.56%   |
| Biwin Storage Technology    | 1         | 1.56%   |
| ASMedia Technology          | 1         | 1.56%   |
| Adaptec                     | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 11.69%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 6.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 5.19%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 5.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 3.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 3.9%    |
| Samsung NVMe SSD Controller 980                                                         | 2         | 2.6%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 2.6%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 2.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 2.6%    |
| Yangtze Memory Non-Volatile memory controller                                           | 1         | 1.3%    |
| SK hynix Gold P31 SSD                                                                   | 1         | 1.3%    |
| SK hynix BC511                                                                          | 1         | 1.3%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 1.3%    |
| Samsung Electronics SATA controller                                                     | 1         | 1.3%    |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 1.3%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 1.3%    |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 1.3%    |
| Nvidia MCP61 SATA Controller                                                            | 1         | 1.3%    |
| Nvidia MCP61 IDE                                                                        | 1         | 1.3%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 1.3%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 1.3%    |
| KIOXIA Non-Volatile memory controller                                                   | 1         | 1.3%    |
| JMicron JMB58x AHCI SATA controller                                                     | 1         | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.3%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 1.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.3%    |
| Intel SSD 600P Series                                                                   | 1         | 1.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.3%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.3%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 1.3%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 1.3%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1         | 1.3%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 1.3%    |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 1         | 1.3%    |
| Intel 631xESB/632xESB IDE Controller                                                    | 1         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.3%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 1.3%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.3%    |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                      | 1         | 1.3%    |
| Biwin Storage Non-Volatile memory controller                                            | 1         | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 1.3%    |
| Adaptec SCSI storage controller                                                         | 1         | 1.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 31        | 49.21%  |
| NVMe | 19        | 30.16%  |
| IDE  | 7         | 11.11%  |
| RAID | 4         | 6.35%   |
| SCSI | 2         | 3.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 74.47%  |
| AMD    | 12        | 25.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 6.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 4.26%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 2.13%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 2.13%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 2.13%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 2.13%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 2.13%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 2.13%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 2.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.13%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 2.13%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.13%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.13%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 2.13%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 2.13%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 2.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.13%   |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1         | 2.13%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 2.13%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 1         | 2.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.13%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.13%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.13%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.13%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 1         | 2.13%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.13%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 2.13%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2.13%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 2.13%   |
| Intel Atom CPU 330 @ 1.60GHz                  | 1         | 2.13%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 2.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.13%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1         | 2.13%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 2.13%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1         | 2.13%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 2.13%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.13%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 1         | 2.13%   |
| AMD FX-8320 Eight-Core Processor              | 1         | 2.13%   |
| AMD FX-6300 Six-Core Processor                | 1         | 2.13%   |
| AMD EPYC 7232P 8-Core Processor               | 1         | 2.13%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 2.13%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 2.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 8         | 17.02%  |
| Other              | 7         | 14.89%  |
| Intel Core i5      | 6         | 12.77%  |
| Intel Xeon         | 5         | 10.64%  |
| AMD Ryzen 5        | 3         | 6.38%   |
| Intel Core i3      | 2         | 4.26%   |
| Intel Core 2 Duo   | 2         | 4.26%   |
| Intel Celeron      | 2         | 4.26%   |
| AMD Ryzen 9        | 2         | 4.26%   |
| AMD Ryzen 7        | 2         | 4.26%   |
| AMD FX             | 2         | 4.26%   |
| Intel Pentium Dual | 1         | 2.13%   |
| Intel Pentium      | 1         | 2.13%   |
| Intel Atom         | 1         | 2.13%   |
| AMD EPYC           | 1         | 2.13%   |
| AMD Athlon         | 1         | 2.13%   |
| AMD A8             | 1         | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 16        | 34.04%  |
| 2      | 14        | 29.79%  |
| 8      | 10        | 21.28%  |
| 6      | 2         | 4.26%   |
| 16     | 1         | 2.13%   |
| 14     | 1         | 2.13%   |
| 12     | 1         | 2.13%   |
| 10     | 1         | 2.13%   |
| 3      | 1         | 2.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 95.74%  |
| 2      | 2         | 4.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 36        | 76.6%   |
| 1      | 11        | 23.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 47        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 7         | 14.89%  |
| Unknown    | 6         | 12.77%  |
| 0x806d1    | 3         | 6.38%   |
| 0x806c1    | 3         | 6.38%   |
| 0x406c4    | 2         | 4.26%   |
| 0x306f2    | 2         | 4.26%   |
| 0x08108109 | 2         | 4.26%   |
| 0xa0671    | 1         | 2.13%   |
| 0xa0653    | 1         | 2.13%   |
| 0xa0652    | 1         | 2.13%   |
| 0x906ea    | 1         | 2.13%   |
| 0x906e9    | 1         | 2.13%   |
| 0x806ea    | 1         | 2.13%   |
| 0x6fd      | 1         | 2.13%   |
| 0x6fa      | 1         | 2.13%   |
| 0x406e3    | 1         | 2.13%   |
| 0x306e4    | 1         | 2.13%   |
| 0x306d4    | 1         | 2.13%   |
| 0x206c2    | 1         | 2.13%   |
| 0x106c2    | 1         | 2.13%   |
| 0x1067a    | 1         | 2.13%   |
| 0x0a201016 | 1         | 2.13%   |
| 0x08701021 | 1         | 2.13%   |
| 0x08600106 | 1         | 2.13%   |
| 0x0830104d | 1         | 2.13%   |
| 0x0810100b | 1         | 2.13%   |
| 0x07030105 | 1         | 2.13%   |
| 0x06000822 | 1         | 2.13%   |
| 0x00000000 | 1         | 2.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| IvyBridge  | 8         | 17.02%  |
| Zen 2      | 5         | 10.64%  |
| KabyLake   | 5         | 10.64%  |
| Icelake    | 4         | 8.51%   |
| TigerLake  | 3         | 6.38%   |
| Core       | 3         | 6.38%   |
| Zen+       | 2         | 4.26%   |
| Westmere   | 2         | 4.26%   |
| Silvermont | 2         | 4.26%   |
| Piledriver | 2         | 4.26%   |
| Haswell    | 2         | 4.26%   |
| CometLake  | 2         | 4.26%   |
| Zen 3      | 1         | 2.13%   |
| Zen        | 1         | 2.13%   |
| Skylake    | 1         | 2.13%   |
| Puma       | 1         | 2.13%   |
| Penryn     | 1         | 2.13%   |
| Broadwell  | 1         | 2.13%   |
| Bonnell    | 1         | 2.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 20        | 37.04%  |
| Nvidia                     | 17        | 31.48%  |
| AMD                        | 16        | 29.63%  |
| Matrox Electronics Systems | 1         | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 5.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 5.56%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 3.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 3.7%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 3.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.7%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 3.7%    |
| AMD Renoir                                                                               | 2         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.7%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 3.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 3.7%    |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.85%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 1.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.85%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 1.85%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1         | 1.85%   |
| Nvidia C79 [ION]                                                                         | 1         | 1.85%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.85%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.85%   |
| Intel HD Graphics 620                                                                    | 1         | 1.85%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.85%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                               | 1         | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.85%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 1.85%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 1.85%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.85%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 31.91%  |
| 1 x AMD        | 15        | 31.91%  |
| 1 x Nvidia     | 10        | 21.28%  |
| Intel + Nvidia | 5         | 10.64%  |
| 1 x Matrox     | 1         | 2.13%   |
| AMD + Nvidia   | 1         | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 40        | 85.11%  |
| Proprietary | 6         | 12.77%  |
| Unknown     | 1         | 2.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 46.81%  |
| 0.51-1.0   | 7         | 14.89%  |
| 7.01-8.0   | 5         | 10.64%  |
| 0.01-0.5   | 5         | 10.64%  |
| 5.01-6.0   | 3         | 6.38%   |
| 1.01-2.0   | 2         | 4.26%   |
| 8.01-16.0  | 2         | 4.26%   |
| 2.01-3.0   | 1         | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 8         | 15.69%  |
| Samsung Electronics  | 7         | 13.73%  |
| LG Display           | 5         | 9.8%    |
| Hewlett-Packard      | 4         | 7.84%   |
| AU Optronics         | 4         | 7.84%   |
| Ancor Communications | 3         | 5.88%   |
| Sharp                | 2         | 3.92%   |
| Dell                 | 2         | 3.92%   |
| BenQ                 | 2         | 3.92%   |
| Acer                 | 2         | 3.92%   |
| Wacom                | 1         | 1.96%   |
| UGD                  | 1         | 1.96%   |
| Sony                 | 1         | 1.96%   |
| PANDA                | 1         | 1.96%   |
| Lenovo               | 1         | 1.96%   |
| IOD                  | 1         | 1.96%   |
| Iiyama               | 1         | 1.96%   |
| Goldstar             | 1         | 1.96%   |
| GDH                  | 1         | 1.96%   |
| Chimei Innolux       | 1         | 1.96%   |
| Apple                | 1         | 1.96%   |
| AOC                  | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 1.92%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 1.92%   |
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                         | 1         | 1.92%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch               | 1         | 1.92%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.92%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 1.92%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 1.92%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 1.92%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch   | 1         | 1.92%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1         | 1.92%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1         | 1.92%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.92%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.92%   |
| LG Display LCD Monitor LGD0625 1920x1080 340x190mm 15.3-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.92%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1         | 1.92%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1         | 1.92%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                  | 1         | 1.92%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.92%   |
| Hewlett-Packard ALL-in-One HPN4021 1920x1080 476x268mm 21.5-inch      | 1         | 1.92%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch             | 1         | 1.92%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 1.92%   |
| Goldstar E1641 GSM8B3E 1366x768 350x200mm 15.9-inch                   | 1         | 1.92%   |
| GDH CHHWJT GDH0030 1440x900 1150x650mm 52.0-inch                      | 1         | 1.92%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 1.92%   |
| Dell DELL2407WFPHC DELA026 1920x1200 519x324mm 24.1-inch              | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 1.92%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 1.92%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 1         | 1.92%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                  | 1         | 1.92%   |
| BenQ VZ2770H BNQ7B3C 1920x1080 598x336mm 27.0-inch                    | 1         | 1.92%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 381x214mm 17.2-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 1         | 1.92%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                 | 1         | 1.92%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1         | 1.92%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 800x340mm 34.2-inch | 1         | 1.92%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1         | 1.92%   |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 621x341mm 27.9-inch | 1         | 1.92%   |
| Acer GN246HL ACR02F9 1920x1080 530x300mm 24.0-inch                    | 1         | 1.92%   |
| Acer AL1714 ACRAD18 1280x1024 338x270mm 17.0-inch                     | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 25        | 51.02%  |
| 1366x768 (WXGA)    | 9         | 18.37%  |
| 3840x2160 (4K)     | 3         | 6.12%   |
| 1280x1024 (SXGA)   | 3         | 6.12%   |
| 1360x768           | 2         | 4.08%   |
| 3440x1440          | 1         | 2.04%   |
| 2560x1440 (QHD)    | 1         | 2.04%   |
| 2256x1504          | 1         | 2.04%   |
| 1920x1200 (WUXGA)  | 1         | 2.04%   |
| 1680x1050 (WSXGA+) | 1         | 2.04%   |
| 1600x900 (HD+)     | 1         | 2.04%   |
| 1600x1200          | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 23.53%  |
| 27     | 6         | 11.76%  |
| 21     | 5         | 9.8%    |
| 17     | 5         | 9.8%    |
| 24     | 4         | 7.84%   |
| 13     | 4         | 7.84%   |
| 20     | 3         | 5.88%   |
| 14     | 3         | 5.88%   |
| 18     | 2         | 3.92%   |
| 72     | 1         | 1.96%   |
| 52     | 1         | 1.96%   |
| 34     | 1         | 1.96%   |
| 23     | 1         | 1.96%   |
| 19     | 1         | 1.96%   |
| 16     | 1         | 1.96%   |
| 12     | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 38%     |
| 501-600     | 10        | 20%     |
| 401-500     | 9         | 18%     |
| 351-400     | 5         | 10%     |
| 201-300     | 3         | 6%      |
| 701-800     | 1         | 2%      |
| 601-700     | 1         | 2%      |
| 1501-2000   | 1         | 2%      |
| 1001-1500   | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 79.55%  |
| 5/4   | 3         | 6.82%   |
| 16/10 | 3         | 6.82%   |
| 4/3   | 1         | 2.27%   |
| 3/2   | 1         | 2.27%   |
| 21/9  | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 26%     |
| 81-90          | 6         | 12%     |
| 301-350        | 6         | 12%     |
| 151-200        | 6         | 12%     |
| 201-250        | 5         | 10%     |
| 141-150        | 4         | 8%      |
| 121-130        | 3         | 6%      |
| More than 1000 | 2         | 4%      |
| 251-300        | 2         | 4%      |
| 71-80          | 1         | 2%      |
| 61-70          | 1         | 2%      |
| 351-500        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 17        | 34%     |
| 121-160       | 14        | 28%     |
| 101-120       | 14        | 28%     |
| 1-50          | 2         | 4%      |
| 161-240       | 2         | 4%      |
| More than 240 | 1         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 36        | 76.6%   |
| 2     | 5         | 10.64%  |
| 0     | 4         | 8.51%   |
| 4     | 1         | 2.13%   |
| 3     | 1         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 39.71%  |
| Intel                    | 25        | 36.76%  |
| Qualcomm Atheros         | 4         | 5.88%   |
| Broadcom                 | 4         | 5.88%   |
| Ralink Technology        | 2         | 2.94%   |
| Broadcom Limited         | 2         | 2.94%   |
| Ralink                   | 1         | 1.47%   |
| Nvidia                   | 1         | 1.47%   |
| Marvell Technology Group | 1         | 1.47%   |
| Hewlett-Packard          | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 22.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.38%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.38%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 2.38%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.38%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.38%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.38%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.19%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.19%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.19%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 1.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.19%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 1.19%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.19%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.19%   |
| Intel Wireless-AC 9260                                            | 1         | 1.19%   |
| Intel Wireless 3165                                               | 1         | 1.19%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.19%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.19%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.19%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.19%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.19%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.19%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.19%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.19%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.19%   |
| HP hs2350 HSPA+ MobileBroadband                                   | 1         | 1.19%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.19%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.19%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.19%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.19%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 1         | 1.19%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 1.19%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.19%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 57.14%  |
| Realtek Semiconductor | 5         | 14.29%  |
| Qualcomm Atheros      | 4         | 11.43%  |
| Ralink Technology     | 2         | 5.71%   |
| Broadcom              | 2         | 5.71%   |
| Ralink                | 1         | 2.86%   |
| Broadcom Limited      | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 8.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 8.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 5.71%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 5.71%   |
| Intel Wireless 8265 / 8275                                     | 2         | 5.71%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 5.71%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 5.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 5.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.86%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 2.86%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 2.86%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 2.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.86%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1         | 2.86%   |
| Intel Wireless-AC 9260                                         | 1         | 2.86%   |
| Intel Wireless 3165                                            | 1         | 2.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.86%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.86%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                        | 1         | 2.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.86%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 58.7%   |
| Intel                    | 12        | 26.09%  |
| Broadcom                 | 3         | 6.52%   |
| Qualcomm Atheros         | 1         | 2.17%   |
| Nvidia                   | 1         | 2.17%   |
| Marvell Technology Group | 1         | 2.17%   |
| Broadcom Limited         | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 39.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6.25%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 4.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.17%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.08%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.08%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.08%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.08%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.08%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 2.08%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 2.08%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.08%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 2.08%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.08%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 2.08%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 2.08%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 54.43%  |
| WiFi     | 35        | 44.3%   |
| Modem    | 1         | 1.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 50.98%  |
| Ethernet | 25        | 49.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 59.57%  |
| 1     | 16        | 34.04%  |
| 4     | 2         | 4.26%   |
| 3     | 1         | 2.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 91.49%  |
| Yes  | 4         | 8.51%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 16        | 51.61%  |
| Realtek Semiconductor   | 4         | 12.9%   |
| Cambridge Silicon Radio | 4         | 12.9%   |
| Broadcom                | 4         | 12.9%   |
| Apple                   | 2         | 6.45%   |
| Foxconn / Hon Hai       | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 5         | 16.13%  |
| Intel Bluetooth wireless interface                  | 4         | 12.9%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 12.9%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 9.68%   |
| Intel AX210 Bluetooth                               | 3         | 9.68%   |
| Intel AX200 Bluetooth                               | 2         | 6.45%   |
| Realtek Bluetooth Radio                             | 1         | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.23%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 3.23%   |
| Broadcom HP Portable SoftSailing                    | 1         | 3.23%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 3.23%   |
| Broadcom BCM20702A0                                 | 1         | 3.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.23%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.23%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 29        | 42.65%  |
| AMD                    | 16        | 23.53%  |
| Nvidia                 | 15        | 22.06%  |
| Creative Labs          | 4         | 5.88%   |
| C-Media Electronics    | 2         | 2.94%   |
| Generalplus Technology | 1         | 1.47%   |
| ASUSTek Computer       | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 7.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 6.41%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 5.13%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 3.85%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 3.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.85%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.56%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2         | 2.56%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 2.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 2.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 2.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.28%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.28%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.28%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.28%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.28%   |
| Nvidia Audio device                                                                               | 1         | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.28%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.28%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.28%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.28%   |
| Generalplus Technology IMYB 7.1 Channel                                                           | 1         | 1.28%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1         | 1.28%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1         | 1.28%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 1         | 1.28%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 1.28%   |
| ASUSTek Computer XONAR SOUND CARD                                                                 | 1         | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.28%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.28%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.28%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.28%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 11        | 20.37%  |
| SK hynix            | 9         | 16.67%  |
| Samsung Electronics | 8         | 14.81%  |
| Crucial             | 5         | 9.26%   |
| Micron Technology   | 3         | 5.56%   |
| Unknown             | 2         | 3.7%    |
| Corsair             | 2         | 3.7%    |
| A-DATA Technology   | 2         | 3.7%    |
| Transcend           | 1         | 1.85%   |
| Team                | 1         | 1.85%   |
| Strontium           | 1         | 1.85%   |
| Silicon Power       | 1         | 1.85%   |
| Neo Forza           | 1         | 1.85%   |
| Nanya Technology    | 1         | 1.85%   |
| Goodram             | 1         | 1.85%   |
| GLOWAY              | 1         | 1.85%   |
| G.Skill             | 1         | 1.85%   |
| Essencore Limited   | 1         | 1.85%   |
| AMD                 | 1         | 1.85%   |
| Unknown             | 1         | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                                 | 2         | 3.33%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s                | 1         | 1.67%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s                  | 1         | 1.67%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s                | 1         | 1.67%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s          | 1         | 1.67%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                     | 1         | 1.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 1.67%   |
| SK hynix RAM HMT31GR7BFR4A-H9 16GB DIMM 1333MT/s                     | 1         | 1.67%   |
| SK hynix RAM HMT125R7BFR8C-H9 4GB DIMM 1333MT/s                      | 1         | 1.67%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 1.67%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s               | 1         | 1.67%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 1.67%   |
| SK hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s              | 1         | 1.67%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8192MB Row Of Chips LPDDR3 1867MT/s  | 1         | 1.67%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.67%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 1.67%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 1.67%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s            | 1         | 1.67%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s                 | 1         | 1.67%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s                  | 1         | 1.67%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s                  | 1         | 1.67%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                  | 1         | 1.67%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 1.67%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.67%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.67%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.67%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 1.67%   |
| Kingston RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 1.67%   |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s                      | 1         | 1.67%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.67%   |
| Kingston RAM KKRVFX-MIE 8192MB SODIMM DDR4 3200MT/s                  | 1         | 1.67%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s                 | 1         | 1.67%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s              | 1         | 1.67%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s                  | 1         | 1.67%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 1.67%   |
| Kingston RAM ACR128X64D2S800C6 1GB SODIMM DDR2 800MT/s               | 1         | 1.67%   |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 1.67%   |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s               | 1         | 1.67%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 1.67%   |
| Goodram RAM GR2400S464L17S/4G 4096MB SODIMM DDR4 2400MT/s            | 1         | 1.67%   |
| GLOWAY RAM TYA4U2666D19161C 16GB DIMM DDR4 2667MT/s                  | 1         | 1.67%   |
| G.Skill RAM F4-3200C16-16GTZSW 16384MB DIMM DDR4 3200MT/s            | 1         | 1.67%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 1.67%   |
| Crucial RAM Module 2048MB SODIMM DDR2 667MT/s                        | 1         | 1.67%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 1.67%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 1.67%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s               | 1         | 1.67%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s                | 1         | 1.67%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 2667MT/s                | 1         | 1.67%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 800MT/s                  | 1         | 1.67%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| AMD RAM R534G1601S1SL 4GB DIMM DDR3 1600MT/s                         | 1         | 1.67%   |
| A-DATA RAM Module 4096MB DIMM DDR3 1333MT/s                          | 1         | 1.67%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.67%   |
| Unknown                                                              | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 23        | 51.11%  |
| DDR3    | 15        | 33.33%  |
| DDR2    | 3         | 6.67%   |
| SDRAM   | 2         | 4.44%   |
| LPDDR3  | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 54.55%  |
| DIMM         | 17        | 38.64%  |
| Row Of Chips | 1         | 2.27%   |
| RIMM         | 1         | 2.27%   |
| FB-DIMM      | 1         | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 18        | 36%     |
| 8192  | 17        | 34%     |
| 16384 | 7         | 14%     |
| 2048  | 4         | 8%      |
| 32768 | 2         | 4%      |
| 1024  | 2         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 12        | 24.49%  |
| 3200    | 11        | 22.45%  |
| 2667    | 5         | 10.2%   |
| 2400    | 5         | 10.2%   |
| 1333    | 3         | 6.12%   |
| 2133    | 2         | 4.08%   |
| 667     | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| 65535   | 1         | 2.04%   |
| 3800    | 1         | 2.04%   |
| 3533    | 1         | 2.04%   |
| 1867    | 1         | 2.04%   |
| 1866    | 1         | 2.04%   |
| 800     | 1         | 2.04%   |
| 701     | 1         | 2.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Dell                | 1         | 25%     |
| Canon               | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 1         | 25%     |
| HP OfficeJet Pro 9010 series | 1         | 25%     |
| Dell 2330d Laser Printer     | 1         | 25%     |
| Canon LiDE 300               | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 20.69%  |
| Acer                                   | 6         | 20.69%  |
| Microdia                               | 4         | 13.79%  |
| Logitech                               | 4         | 13.79%  |
| Realtek Semiconductor                  | 2         | 6.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.9%    |
| Syntek                                 | 1         | 3.45%   |
| Samsung Electronics                    | 1         | 3.45%   |
| Quanta                                 | 1         | 3.45%   |
| Luxvisions Innotech Limited            | 1         | 3.45%   |
| Apple                                  | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                                 | 2         | 6.9%    |
| Acer BisonCam,NB Pro                                           | 2         | 6.9%    |
| Syntek USB2.0 Camera                                           | 1         | 3.45%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 3.45%   |
| Realtek Laptop Camera                                          | 1         | 3.45%   |
| Realtek EasyCamera                                             | 1         | 3.45%   |
| Quanta HP Webcam                                               | 1         | 3.45%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 3.45%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 3.45%   |
| Microdia Integrated Webcam                                     | 1         | 3.45%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 3.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 3.45%   |
| Logitech Webcam C270                                           | 1         | 3.45%   |
| Logitech QuickCam Pro 9000                                     | 1         | 3.45%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 3.45%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 3.45%   |
| Chicony Web Camera - FHD                                       | 1         | 3.45%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 3.45%   |
| Chicony Integrated Camera                                      | 1         | 3.45%   |
| Chicony HP TrueVision HD Camera                                | 1         | 3.45%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 3.45%   |
| Chicony HP HD Camera                                           | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP 5M Camera            | 1         | 3.45%   |
| Apple Built-in iSight                                          | 1         | 3.45%   |
| Acer ThinkPad Integrated Camera                                | 1         | 3.45%   |
| Acer Integrated Camera                                         | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| Synaptics        | 2         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 2         | 50%     |
| Validity Sensors VFS300 Fingerprint Reader | 1         | 25%     |
| Validity Sensors Synaptics WBDI            | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 33        | 70.21%  |
| 1     | 10        | 21.28%  |
| 2     | 2         | 4.26%   |
| 4     | 1         | 2.13%   |
| 3     | 1         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


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

