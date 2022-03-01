Gentoo 2.8 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | Yoga Slim 7 14IIL05 82A1    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| ASUSTek   | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| MSI       | GS63VR 6RF                  | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| HP        | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo    | Legion Y7000 2019 PG0 81... | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| MSI       | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Lenovo    | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi      | RedmiBook 13                | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Timi      | RedmiBook 13                | [b424ef43c2](https://linux-hardware.org/?probe=b424ef43c2) | Jan 25, 2022 |
| Lenovo    | IdeaPad 5 15ITL05 82FG      | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo    | IdeaPad 5 15ITL05 82FG      | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| MSI       | GE73 Raider RGB 8RF         | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo    | ThinkPad 20FMCT01WW         | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Timi      | Mi Laptop Pro 15            | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo    | ThinkPad X1 Carbon 7th 2... | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo    | ThinkPad X1 Carbon 7th 2... | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell      | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo    | Legion 5 Pro 16ACH6H 82J... | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| Lenovo    | Legion R7000 2020 82B6      | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer      | Nitro AN515-54              | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Timi      | RedmiBook 13                | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| Dell      | XPS 15 9570                 | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Framework | Laptop                      | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| ASUSTek   | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Toshiba   | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| HP        | Laptop 15s-eq0xxx           | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP        | Laptop 15s-eq0xxx           | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo    | IdeaPad 5 Pro 16ACH6 82L... | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo    | ThinkPad T470p 20J7S06Q0... | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo    | ThinkPad T470p 20J7S06Q0... | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Acer      | Aspire A715-42G             | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer      | Aspire A715-42G             | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Lenovo    | ThinkPad E495 20NE000BGE    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Dell      | Latitude 7490               | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| Lenovo    | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| Lenovo    | ThinkPad E15 Gen 2 20T80... | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Acer      | Aspire A515-55              | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Lenovo    | ThinkBook 14 G3 ACL 21A2    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo    | ThinkBook 14 G3 ACL 21A2    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Timi      | Mi Laptop Pro 15            | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Dell      | Inspiron 5415               | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.9-gentoo-x86_64         | 3         | 8.57%   |
| 5.16.0-gentoo-x86_64         | 2         | 5.71%   |
| 5.15.10-gentoo-x86_64        | 2         | 5.71%   |
| 5.16.8-gentoo-gentoo-dist    | 1         | 2.86%   |
| 5.16.5-gentoo-x86_64         | 1         | 2.86%   |
| 5.16.2-gentoo-x86_64         | 1         | 2.86%   |
| 5.16.2-gentoo                | 1         | 2.86%   |
| 5.16.10-gentoo--20-feb-2022  | 1         | 2.86%   |
| 5.16.10-gentoo               | 1         | 2.86%   |
| 5.16.1-gentoo-x86_64         | 1         | 2.86%   |
| 5.16.1-gentoo                | 1         | 2.86%   |
| 5.16.0-xanmod1               | 1         | 2.86%   |
| 5.16.0-gentoo-gentoo-dist    | 1         | 2.86%   |
| 5.16.0-gentoo                | 1         | 2.86%   |
| 5.15.7-gentoo                | 1         | 2.86%   |
| 5.15.6-gentoo                | 1         | 2.86%   |
| 5.15.5-gentoo-x86_64         | 1         | 2.86%   |
| 5.15.5-gentoo-dist           | 1         | 2.86%   |
| 5.15.5-gentoo                | 1         | 2.86%   |
| 5.15.19-gentoo-112-overlayfs | 1         | 2.86%   |
| 5.15.13-gentoo-dist          | 1         | 2.86%   |
| 5.15.13-gentoo               | 1         | 2.86%   |
| 5.15.12-gentoo               | 1         | 2.86%   |
| 5.15.1-gentoo-x86_64         | 1         | 2.86%   |
| 5.14.9-gentoo                | 1         | 2.86%   |
| 5.14.7-gentoo-x86_64         | 1         | 2.86%   |
| 5.14.14-gentoo-x86_64        | 1         | 2.86%   |
| 5.14.14-gentoo-dist          | 1         | 2.86%   |
| 5.10.83-gentoo-dist          | 1         | 2.86%   |
| 5.10.76-gentoo-r1            | 1         | 2.86%   |
| 5.10.70-1-lts                | 1         | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.0  | 5         | 14.29%  |
| 5.14.9  | 4         | 11.43%  |
| 5.15.5  | 3         | 8.57%   |
| 5.16.2  | 2         | 5.71%   |
| 5.16.10 | 2         | 5.71%   |
| 5.16.1  | 2         | 5.71%   |
| 5.15.13 | 2         | 5.71%   |
| 5.15.10 | 2         | 5.71%   |
| 5.14.14 | 2         | 5.71%   |
| 5.16.8  | 1         | 2.86%   |
| 5.16.5  | 1         | 2.86%   |
| 5.15.7  | 1         | 2.86%   |
| 5.15.6  | 1         | 2.86%   |
| 5.15.19 | 1         | 2.86%   |
| 5.15.12 | 1         | 2.86%   |
| 5.15.1  | 1         | 2.86%   |
| 5.14.7  | 1         | 2.86%   |
| 5.10.83 | 1         | 2.86%   |
| 5.10.76 | 1         | 2.86%   |
| 5.10.70 | 1         | 2.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 12        | 35.29%  |
| 5.15    | 12        | 35.29%  |
| 5.14    | 7         | 20.59%  |
| 5.10    | 3         | 8.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Unknown  | 15        | 45.45%  |
| KDE5     | 9         | 27.27%  |
| GNOME    | 3         | 9.09%   |
| XFCE     | 2         | 6.06%   |
| sway     | 1         | 3.03%   |
| fvwm     | 1         | 3.03%   |
| DWM      | 1         | 3.03%   |
| Cinnamon | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 13        | 38.24%  |
| X11     | 10        | 29.41%  |
| Tty     | 6         | 17.65%  |
| Unknown | 5         | 14.71%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 50%     |
| SDDM    | 10        | 29.41%  |
| GDM     | 3         | 8.82%   |
| LightDM | 2         | 5.88%   |
| SLiM    | 1         | 2.94%   |
| GREETD  | 1         | 2.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 16        | 48.48%  |
| ru_RU      | 2         | 6.06%   |
| de_DE      | 2         | 6.06%   |
| C          | 2         | 6.06%   |
| Unknown    | 2         | 6.06%   |
| tr_TR      | 1         | 3.03%   |
| it_IT      | 1         | 3.03%   |
| es_AR      | 1         | 3.03%   |
| en_US.UTF8 | 1         | 3.03%   |
| en_NZ      | 1         | 3.03%   |
| en_GB      | 1         | 3.03%   |
| en_AU      | 1         | 3.03%   |
| el_GR      | 1         | 3.03%   |
| C.UTF8     | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 31        | 93.94%  |
| BIOS | 2         | 6.06%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 17        | 51.52%  |
| Btrfs | 15        | 45.45%  |
| F2fs  | 1         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 31        | 93.94%  |
| MBR  | 2         | 6.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 85.29%  |
| Yes       | 5         | 14.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 75.76%  |
| Yes       | 8         | 24.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 14        | 42.42%  |
| Dell             | 4         | 12.12%  |
| Hewlett-Packard  | 3         | 9.09%   |
| ASUSTek Computer | 3         | 9.09%   |
| Acer             | 3         | 9.09%   |
| Timi             | 2         | 6.06%   |
| MSI              | 2         | 6.06%   |
| Toshiba          | 1         | 3.03%   |
| Framework        | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP Laptop 15s-eq0xxx                     | 2         | 6.06%   |
| Toshiba Satellite C850D-118              | 1         | 3.03%   |
| Timi RedmiBook 13                        | 1         | 3.03%   |
| Timi Mi Laptop Pro 15                    | 1         | 3.03%   |
| MSI GS63VR 6RF                           | 1         | 3.03%   |
| MSI GE73 Raider RGB 8RF                  | 1         | 3.03%   |
| Lenovo Yoga Slim 7 14IIL05 82A1          | 1         | 3.03%   |
| Lenovo Yoga S740-14IIL 81RS              | 1         | 3.03%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0039RI | 1         | 3.03%   |
| Lenovo ThinkPad T470p 20J7S06Q00         | 1         | 3.03%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437      | 1         | 3.03%   |
| Lenovo ThinkPad E495 20NE000BGE          | 1         | 3.03%   |
| Lenovo ThinkPad E15 Gen 2 20T8001STX     | 1         | 3.03%   |
| Lenovo ThinkPad 20FMCT01WW               | 1         | 3.03%   |
| Lenovo ThinkBook 14 G3 ACL 21A2          | 1         | 3.03%   |
| Lenovo Legion Y7000 2019 PG0 81T0        | 1         | 3.03%   |
| Lenovo Legion R7000 2020 82B6            | 1         | 3.03%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ         | 1         | 3.03%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 1         | 3.03%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 3.03%   |
| HP Pavilion Notebook                     | 1         | 3.03%   |
| Framework Laptop                         | 1         | 3.03%   |
| Dell XPS 15 9570                         | 1         | 3.03%   |
| Dell Precision 3561                      | 1         | 3.03%   |
| Dell Latitude 7490                       | 1         | 3.03%   |
| Dell Inspiron 5415                       | 1         | 3.03%   |
| ASUS UX430UAR                            | 1         | 3.03%   |
| ASUS ROG Zephyrus G14 GA401QE_GA401QE    | 1         | 3.03%   |
| ASUS ROG Strix G513QY_G513QY             | 1         | 3.03%   |
| Acer Nitro AN515-54                      | 1         | 3.03%   |
| Acer Aspire A715-42G                     | 1         | 3.03%   |
| Acer Aspire A515-55                      | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 6         | 18.18%  |
| Lenovo Legion     | 3         | 9.09%   |
| Lenovo Yoga       | 2         | 6.06%   |
| Lenovo IdeaPad    | 2         | 6.06%   |
| HP Laptop         | 2         | 6.06%   |
| ASUS ROG          | 2         | 6.06%   |
| Acer Aspire       | 2         | 6.06%   |
| Toshiba Satellite | 1         | 3.03%   |
| Timi RedmiBook    | 1         | 3.03%   |
| Timi Mi           | 1         | 3.03%   |
| MSI GS63VR        | 1         | 3.03%   |
| MSI GE73          | 1         | 3.03%   |
| Lenovo ThinkBook  | 1         | 3.03%   |
| HP Pavilion       | 1         | 3.03%   |
| Framework Laptop  | 1         | 3.03%   |
| Dell XPS          | 1         | 3.03%   |
| Dell Precision    | 1         | 3.03%   |
| Dell Latitude     | 1         | 3.03%   |
| Dell Inspiron     | 1         | 3.03%   |
| ASUS UX430UAR     | 1         | 3.03%   |
| Acer Nitro        | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 10        | 30.3%   |
| 2021 | 9         | 27.27%  |
| 2020 | 7         | 21.21%  |
| 2018 | 3         | 9.09%   |
| 2017 | 2         | 6.06%   |
| 2016 | 1         | 3.03%   |
| 2012 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 33        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 31        | 93.94%  |
| Enabled  | 2         | 6.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 11        | 33.33%  |
| 16.01-24.0  | 8         | 24.24%  |
| 4.01-8.0    | 6         | 18.18%  |
| 32.01-64.0  | 5         | 15.15%  |
| 24.01-32.0  | 1         | 3.03%   |
| 64.01-256.0 | 1         | 3.03%   |
| 1.01-2.0    | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 10        | 28.57%  |
| 4.01-8.0  | 8         | 22.86%  |
| 3.01-4.0  | 6         | 17.14%  |
| 8.01-16.0 | 5         | 14.29%  |
| 2.01-3.0  | 3         | 8.57%   |
| 0.51-1.0  | 3         | 8.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 69.7%   |
| 2      | 8         | 24.24%  |
| 4      | 1         | 3.03%   |
| 3      | 1         | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 90.91%  |
| Yes       | 3         | 9.09%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 60.61%  |
| No        | 13        | 39.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 93.94%  |
| No        | 2         | 6.06%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 5         | 14.71%  |
| USA         | 4         | 11.76%  |
| Russia      | 4         | 11.76%  |
| India       | 2         | 5.88%   |
| Greece      | 2         | 5.88%   |
| Uruguay     | 1         | 2.94%   |
| Turkey      | 1         | 2.94%   |
| Sweden      | 1         | 2.94%   |
| Spain       | 1         | 2.94%   |
| Romania     | 1         | 2.94%   |
| Poland      | 1         | 2.94%   |
| Philippines | 1         | 2.94%   |
| Norway      | 1         | 2.94%   |
| New Zealand | 1         | 2.94%   |
| Italy       | 1         | 2.94%   |
| Hong Kong   | 1         | 2.94%   |
| Finland     | 1         | 2.94%   |
| Czechia     | 1         | 2.94%   |
| China       | 1         | 2.94%   |
| Belarus     | 1         | 2.94%   |
| Australia   | 1         | 2.94%   |
| Argentina   | 1         | 2.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Athens                        | 2         | 5.71%   |
| Zebulon                       | 1         | 2.86%   |
| Yekaterinburg                 | 1         | 2.86%   |
| West Orange                   | 1         | 2.86%   |
| Sydney                        | 1         | 2.86%   |
| Storsteinnes                  | 1         | 2.86%   |
| Sestao                        | 1         | 2.86%   |
| Ratingen                      | 1         | 2.86%   |
| NykÃ¶ping                   | 1         | 2.86%   |
| Nuremberg                     | 1         | 2.86%   |
| Novosibirsk                   | 1         | 2.86%   |
| Nizhniy Novgorod              | 1         | 2.86%   |
| Moscow                        | 1         | 2.86%   |
| Minsk                         | 1         | 2.86%   |
| Milan                         | 1         | 2.86%   |
| Maldonado                     | 1         | 2.86%   |
| Kulmbach                      | 1         | 2.86%   |
| Hyderabad                     | 1         | 2.86%   |
| Helsinki                      | 1         | 2.86%   |
| Harsum                        | 1         | 2.86%   |
| Guangzhou                     | 1         | 2.86%   |
| Gmina LwÃ³wek ÅšlÄ…ski | 1         | 2.86%   |
| Foshan                        | 1         | 2.86%   |
| Chicago                       | 1         | 2.86%   |
| Cerritos                      | 1         | 2.86%   |
| Central                       | 1         | 2.86%   |
| CÃ³rdoba                    | 1         | 2.86%   |
| Calamba                       | 1         | 2.86%   |
| Brno                          | 1         | 2.86%   |
| Brasov                        | 1         | 2.86%   |
| Bhavnagar                     | 1         | 2.86%   |
| Berlin                        | 1         | 2.86%   |
| Auckland                      | 1         | 2.86%   |
| Ankara                        | 1         | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 21.43%  |
| Samsung Electronics | 8         | 8      | 19.05%  |
| Intel               | 6         | 7      | 14.29%  |
| SK Hynix            | 5         | 5      | 11.9%   |
| Seagate             | 4         | 5      | 9.52%   |
| Toshiba             | 2         | 2      | 4.76%   |
| Unknown             | 1         | 3      | 2.38%   |
| SanDisk             | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| KIOXIA-EXCERIA      | 1         | 2      | 2.38%   |
| KIOXIA              | 1         | 1      | 2.38%   |
| Kingston            | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |
| Crucial             | 1         | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung MZVLB512HBJQ-000L2 512GB        | 2         | 4.76%   |
| Intel SSDPEKNW010T8 1TB                 | 2         | 4.76%   |
| Intel SSDPEKNU512GZ 512GB               | 2         | 4.76%   |
| WDC WDS250G2X0C-00L350 250GB            | 1         | 2.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 2.38%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 2.38%   |
| WDC WD2500BEVS-22UST0 250GB             | 1         | 2.38%   |
| WDC WD10SPSX-08A6W 1TB                  | 1         | 2.38%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 2.38%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 1         | 2.38%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB    | 1         | 2.38%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 2.38%   |
| Unknown USB DISK 3.2 500GB              | 1         | 2.38%   |
| Toshiba KXG6AZNV512G 512GB              | 1         | 2.38%   |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD | 1         | 2.38%   |
| SK Hynix SKHynix_HFS001TDE9X084N 1TB    | 1         | 2.38%   |
| SK Hynix PC711 NVMe 512GB               | 1         | 2.38%   |
| SK Hynix HFM512GDHTNG-8710B 512GB       | 1         | 2.38%   |
| SK Hynix HFM512GD3JX016N 512GB          | 1         | 2.38%   |
| SK Hynix BC711 NVMe 512GB               | 1         | 2.38%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 2.38%   |
| Seagate ST1000LM035-1RK1 1TB            | 1         | 2.38%   |
| Seagate FireCuda 530 ZP4000GM30013 4TB  | 1         | 2.38%   |
| SanDisk SD9SN8W256G1002 256GB SSD       | 1         | 2.38%   |
| Samsung SSD 980 PRO 2TB                 | 1         | 2.38%   |
| Samsung SSD 970 EVO 500GB               | 1         | 2.38%   |
| Samsung MZVLW1T0HMLH-000L7 1TB          | 1         | 2.38%   |
| Samsung MZVLB1T0HBLR-000L2 1TB          | 1         | 2.38%   |
| Samsung MZNLN512HAJQ-00000 512GB SSD    | 1         | 2.38%   |
| Samsung MZALQ512HALU-000L2 512GB        | 1         | 2.38%   |
| Micron MTFDHBA256TCK 256GB              | 1         | 2.38%   |
| KIOXIA-EXCERIA SSD 500GB                | 1         | 2.38%   |
| KIOXIA KBG30ZMV256G 256GB               | 1         | 2.38%   |
| Kingston RBUSNS8154P3256GJ 256GB        | 1         | 2.38%   |
| Intel SSDPEKNW020T8 2TB                 | 1         | 2.38%   |
| Intel SSDPEKKF256G8L 256GB              | 1         | 2.38%   |
| HGST HTS721010A9E630 1TB                | 1         | 2.38%   |
| Crucial CT1000P1SSD8 1TB                | 1         | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 50%     |
| WDC     | 2         | 2      | 33.33%  |
| HGST    | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Toshiba             | 1         | 1      | 25%     |
| SanDisk             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 27        | 34     | 71.05%  |
| HDD     | 6         | 7      | 15.79%  |
| SSD     | 4         | 4      | 10.53%  |
| Unknown | 1         | 3      | 2.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 27        | 34     | 71.05%  |
| SATA | 10        | 11     | 26.32%  |
| SAS  | 1         | 3      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 7         | 8      | 70%     |
| 0.01-0.5   | 3         | 3      | 30%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 11        | 33.33%  |
| 1001-2000      | 6         | 18.18%  |
| 501-1000       | 6         | 18.18%  |
| 101-250        | 5         | 15.15%  |
| 1-20           | 2         | 6.06%   |
| More than 3000 | 1         | 3.03%   |
| 21-50          | 1         | 3.03%   |
| 2001-3000      | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 8         | 24.24%  |
| 1-20      | 7         | 21.21%  |
| 21-50     | 6         | 18.18%  |
| 251-500   | 4         | 12.12%  |
| 1001-2000 | 3         | 9.09%   |
| 501-1000  | 3         | 9.09%   |
| 51-100    | 2         | 6.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000LM049-2GH172 1TB | 1         | 1      | 25%     |
| Seagate ST1000LM035-1RK172 1TB | 1         | 2      | 25%     |
| Intel SSDPEKKF256G8L 256GB     | 1         | 1      | 25%     |
| Crucial CT1000P1SSD8 1TB       | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 50%     |
| Intel   | 1         | 1      | 25%     |
| Crucial | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2         | 2      | 50%     |
| HDD  | 2         | 3      | 50%     |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 31        | 40     | 86.11%  |
| Malfunc  | 4         | 5      | 11.11%  |
| Detected | 1         | 3      | 2.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 18        | 36%     |
| Samsung Electronics          | 7         | 14%     |
| AMD                          | 7         | 14%     |
| Sandisk                      | 6         | 12%     |
| SK Hynix                     | 5         | 10%     |
| Toshiba America Info Systems | 2         | 4%      |
| Seagate Technology           | 1         | 2%      |
| Micron/Crucial Technology    | 1         | 2%      |
| Micron Technology            | 1         | 2%      |
| KIOXIA                       | 1         | 2%      |
| Kingston Technology Company  | 1         | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                   | 7         | 13.73%  |
| SK Hynix Gold P31 SSD                                 | 4         | 7.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983         | 4         | 7.84%   |
| Intel SSD 660P Series                                 | 3         | 5.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller     | 3         | 5.88%   |
| Sandisk Non-Volatile memory controller                | 2         | 3.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]    | 2         | 3.92%   |
| Intel Non-Volatile memory controller                  | 2         | 3.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller  | 1         | 1.96%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller  | 1         | 1.96%   |
| SK Hynix BC501 NVMe Solid State Drive                 | 1         | 1.96%   |
| Seagate FireCuda 530 SSD                              | 1         | 1.96%   |
| Sandisk WD Blue SN550 NVMe SSD                        | 1         | 1.96%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD             | 1         | 1.96%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD            | 1         | 1.96%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD       | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963         | 1         | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO        | 1         | 1.96%   |
| Samsung NVMe SSD Controller 980                       | 1         | 1.96%   |
| Micron/Crucial P1 NVMe PCIe SSD                       | 1         | 1.96%   |
| Micron Non-Volatile memory controller                 | 1         | 1.96%   |
| KIOXIA NVMe SSD                                       | 1         | 1.96%   |
| Kingston Company U-SNS8154P3 NVMe SSD                 | 1         | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]    | 1         | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller   | 1         | 1.96%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]       | 1         | 1.96%   |
| Intel SSD Pro 7600p/760p/E 6100p Series               | 1         | 1.96%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]         | 1         | 1.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode] | 1         | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                 | 1         | 1.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]        | 1         | 1.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller  | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 27        | 57.45%  |
| SATA | 18        | 38.3%   |
| RAID | 2         | 4.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 60.61%  |
| AMD    | 13        | 39.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 9.09%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 6.06%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 6.06%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 6.06%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 3.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 3.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 3.03%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 3.03%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 3.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 3.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.03%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 3.03%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 3.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.03%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 3.03%   |
| AMD Ryzen 7 5800HS with Radeon Graphics       | 1         | 3.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 11        | 33.33%  |
| AMD Ryzen 7   | 7         | 21.21%  |
| Intel Core i5 | 6         | 18.18%  |
| Other         | 3         | 9.09%   |
| AMD Ryzen 5   | 3         | 9.09%   |
| AMD Ryzen 9   | 1         | 3.03%   |
| AMD Ryzen 3   | 1         | 3.03%   |
| AMD E1        | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 16        | 48.48%  |
| 8      | 8         | 24.24%  |
| 6      | 6         | 18.18%  |
| 2      | 3         | 9.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 30        | 90.91%  |
| 1      | 3         | 9.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x906ea    | 5         | 15.15%  |
| 0x0a50000c | 4         | 12.12%  |
| 0x806ec    | 3         | 9.09%   |
| Unknown    | 3         | 9.09%   |
| 0x706e5    | 2         | 6.06%   |
| 0x08608103 | 2         | 6.06%   |
| 0x08600103 | 2         | 6.06%   |
| 0x08108109 | 2         | 6.06%   |
| 0xa0652    | 1         | 3.03%   |
| 0x906e9    | 1         | 3.03%   |
| 0x806ea    | 1         | 3.03%   |
| 0x806d1    | 1         | 3.03%   |
| 0x806c1    | 1         | 3.03%   |
| 0x506e3    | 1         | 3.03%   |
| 0x306d4    | 1         | 3.03%   |
| 0x08608102 | 1         | 3.03%   |
| 0x08108102 | 1         | 3.03%   |
| 0x05000119 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 11        | 33.33%  |
| Zen 3     | 4         | 12.12%  |
| IceLake   | 4         | 12.12%  |
| Zen+      | 3         | 9.09%   |
| Unknown   | 3         | 9.09%   |
| Zen 2     | 2         | 6.06%   |
| TigerLake | 2         | 6.06%   |
| Skylake   | 1         | 3.03%   |
| CometLake | 1         | 3.03%   |
| Broadwell | 1         | 3.03%   |
| Bobcat    | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 41.67%  |
| Nvidia | 16        | 33.33%  |
| AMD    | 12        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 5         | 10.2%   |
| AMD Cezanne                                                          | 4         | 8.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 3         | 6.12%   |
| Nvidia GP108M [GeForce MX250]                                        | 3         | 6.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 3         | 6.12%   |
| AMD Lucienne                                                         | 3         | 6.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 2         | 4.08%   |
| Intel UHD Graphics 620                                               | 2         | 4.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 2         | 4.08%   |
| Intel Iris Plus Graphics G7                                          | 2         | 4.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 2         | 4.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 1         | 2.04%   |
| Nvidia TU117GLM [T600 Mobile]                                        | 1         | 2.04%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                              | 1         | 2.04%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                              | 1         | 2.04%   |
| Nvidia GM108M [GeForce 940M]                                         | 1         | 2.04%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 2.04%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                           | 1         | 2.04%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 2.04%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 1         | 2.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                               | 1         | 2.04%   |
| Intel HD Graphics 630                                                | 1         | 2.04%   |
| Intel HD Graphics 5500                                               | 1         | 2.04%   |
| Intel HD Graphics 530                                                | 1         | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 1         | 2.04%   |
| AMD Wrestler [Radeon HD 7310]                                        | 1         | 2.04%   |
| AMD Renoir                                                           | 1         | 2.04%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                         | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 12        | 36.36%  |
| 1 x Intel      | 8         | 24.24%  |
| 1 x AMD        | 8         | 24.24%  |
| AMD + Nvidia   | 3         | 9.09%   |
| 2 x AMD        | 1         | 3.03%   |
| 1 x Nvidia     | 1         | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 21        | 63.64%  |
| Proprietary | 12        | 36.36%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 48.48%  |
| 1.01-2.0   | 6         | 18.18%  |
| 0.01-0.5   | 4         | 12.12%  |
| 3.01-4.0   | 3         | 9.09%   |
| 0.51-1.0   | 2         | 6.06%   |
| 5.01-6.0   | 1         | 3.03%   |
| 8.01-16.0  | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 11        | 27.5%   |
| AU Optronics        | 9         | 22.5%   |
| Chimei Innolux      | 5         | 12.5%   |
| Sharp               | 3         | 7.5%    |
| Samsung Electronics | 2         | 5%      |
| Goldstar            | 2         | 5%      |
| PANDA               | 1         | 2.5%    |
| LG Display          | 1         | 2.5%    |
| Lenovo              | 1         | 2.5%    |
| Hewlett-Packard     | 1         | 2.5%    |
| CSO                 | 1         | 2.5%    |
| BenQ                | 1         | 2.5%    |
| ASUSTek Computer    | 1         | 2.5%    |
| AOC                 | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 2         | 5%      |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 2.5%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch              | 1         | 2.5%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 1         | 2.5%    |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 1         | 2.5%    |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                 | 1         | 2.5%    |
| Hewlett-Packard E273q HPN3473 2560x1440 597x336mm 27.0-inch          | 1         | 2.5%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 1         | 2.5%    |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 1         | 2.5%    |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 1         | 2.5%    |
| BOE LCD Monitor BOE09B6 2560x1600 345x215mm 16.0-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0928 1920x1080 344x194mm 15.5-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0821 3840x2160 309x174mm 14.0-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 1         | 2.5%    |
| BenQ EX2780Q BNQ7F76 2560x1440 597x336mm 27.0-inch                   | 1         | 2.5%    |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO32EB 3840x2160 344x193mm 15.5-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO233D 1920x1080 309x174mm 14.0-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 2.5%    |
| ASUSTek Computer VG27AQL1A AUS2704 2560x1440 596x336mm 26.9-inch     | 1         | 2.5%    |
| AOC U34G2G1 AOC3402 3440x1440 797x334mm 34.0-inch                    | 1         | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 24        | 63.16%  |
| 3840x2160 (4K)  | 4         | 10.53%  |
| 2560x1440 (QHD) | 4         | 10.53%  |
| 2560x1600       | 2         | 5.26%   |
| 1366x768 (WXGA) | 2         | 5.26%   |
| 3440x1440       | 1         | 2.63%   |
| 2256x1504       | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 18        | 46.15%  |
| 13     | 7         | 17.95%  |
| 14     | 5         | 12.82%  |
| 27     | 4         | 10.26%  |
| 16     | 2         | 5.13%   |
| 34     | 1         | 2.56%   |
| 23     | 1         | 2.56%   |
| 17     | 1         | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 78.95%  |
| 501-600     | 4         | 10.53%  |
| 201-300     | 2         | 5.26%   |
| 701-800     | 1         | 2.63%   |
| 351-400     | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 30        | 88.24%  |
| 16/10 | 2         | 5.88%   |
| 3/2   | 1         | 2.94%   |
| 21/9  | 1         | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 46.15%  |
| 81-90          | 11        | 28.21%  |
| 301-350        | 4         | 10.26%  |
| 111-120        | 2         | 5.13%   |
| 71-80          | 1         | 2.56%   |
| 351-500        | 1         | 2.56%   |
| 201-250        | 1         | 2.56%   |
| 121-130        | 1         | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 23        | 58.97%  |
| 161-240       | 6         | 15.38%  |
| 101-120       | 5         | 12.82%  |
| More than 240 | 3         | 7.69%   |
| 51-100        | 2         | 5.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 29        | 85.29%  |
| 2     | 3         | 8.82%   |
| 3     | 2         | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 56.52%  |
| Realtek Semiconductor | 14        | 30.43%  |
| Qualcomm Atheros      | 2         | 4.35%   |
| MEDIATEK              | 2         | 4.35%   |
| Samsung Electronics   | 1         | 2.17%   |
| ICS Advent            | 1         | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 18.52%  |
| Intel Wi-Fi 6 AX200                                               | 7         | 12.96%  |
| Intel Wireless 8265 / 8275                                        | 3         | 5.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 5.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.7%    |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 3.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 3.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.85%   |
| Intel Wireless-AC 9260                                            | 1         | 1.85%   |
| Intel Wireless 8260                                               | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.85%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.85%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.85%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.85%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 78.79%  |
| Realtek Semiconductor | 5         | 15.15%  |
| MEDIATEK              | 2         | 6.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 7         | 21.21%  |
| Intel Wireless 8265 / 8275                                    | 3         | 9.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 3         | 9.09%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 9.09%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 6.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 6.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 6.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 3.03%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter               | 1         | 3.03%   |
| Intel Wireless-AC 9260                                        | 1         | 3.03%   |
| Intel Wireless 8260                                           | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 3.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 3.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 57.14%  |
| Intel                 | 5         | 23.81%  |
| Qualcomm Atheros      | 2         | 9.52%   |
| Samsung Electronics   | 1         | 4.76%   |
| ICS Advent            | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 47.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 9.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 4.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 4.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 4.76%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 4.76%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 4.76%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 4.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.76%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 4.76%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 62.26%  |
| Ethernet | 20        | 37.74%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 77.5%   |
| Ethernet | 9         | 22.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 57.58%  |
| 1     | 14        | 42.42%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 76.47%  |
| Yes  | 8         | 23.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 77.42%  |
| Realtek Semiconductor | 4         | 12.9%   |
| Toshiba               | 1         | 3.23%   |
| IMC Networks          | 1         | 3.23%   |
| Foxconn / Hon Hai     | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Bluetooth Device                   | 10        | 32.26%  |
| Intel AX200 Bluetooth                    | 7         | 22.58%  |
| Intel AX201 Bluetooth                    | 6         | 19.35%  |
| Realtek Bluetooth Radio                  | 3         | 9.68%   |
| Toshiba RT Bluetooth Radio               | 1         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter           | 1         | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1         | 3.23%   |
| IMC Networks Wireless_Device             | 1         | 3.23%   |
| Foxconn / Hon Hai Wireless_Device        | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 20        | 48.78%  |
| AMD     | 13        | 31.71%  |
| Nvidia  | 7         | 17.07%  |
| ACTIONS | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                          | 12        | 21.82%  |
| AMD Renoir Radeon High Definition Audio Controller              | 7         | 12.73%  |
| Intel Cannon Lake PCH cAVS                                      | 5         | 9.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller  | 3         | 5.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller       | 3         | 5.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller             | 3         | 5.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller     | 2         | 3.64%   |
| Intel Sunrise Point-LP HD Audio                                 | 2         | 3.64%   |
| Intel Comet Lake PCH-LP cAVS                                    | 2         | 3.64%   |
| Nvidia GP107GL High Definition Audio Controller                 | 1         | 1.82%   |
| Nvidia GP106 High Definition Audio Controller                   | 1         | 1.82%   |
| Nvidia GP104 High Definition Audio Controller                   | 1         | 1.82%   |
| Nvidia Audio device                                             | 1         | 1.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller         | 1         | 1.82%   |
| Intel USB PnP Sound Device                                      | 1         | 1.82%   |
| Intel Tiger Lake-H HD Audio Controller                          | 1         | 1.82%   |
| Intel Comet Lake PCH cAVS                                       | 1         | 1.82%   |
| Intel CM238 HD Audio Controller                                 | 1         | 1.82%   |
| Intel Cannon Point-LP High Definition Audio Controller          | 1         | 1.82%   |
| Intel Broadwell-U Audio Controller                              | 1         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller | 1         | 1.82%   |
| AMD Wrestler HDMI Audio                                         | 1         | 1.82%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]       | 1         | 1.82%   |
| AMD FCH Azalia Controller                                       | 1         | 1.82%   |
| ACTIONS EDIFIER M380                                            | 1         | 1.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 50%     |
| SK Hynix            | 11        | 27.5%   |
| Kingston            | 4         | 10%     |
| Micron Technology   | 3         | 7.5%    |
| Patriot             | 1         | 2.5%    |
| Crucial             | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 7.32%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 4.88%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 4.88%   |
| SK Hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4267MT/s | 2         | 4.88%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 4.88%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 4.88%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 4.88%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 2.44%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 2.44%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 2.44%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.44%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 2.44%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 2.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s            | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.44%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.44%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2.44%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.44%   |
| Patriot RAM PSD416G24002S 16GB SODIMM DDR4 2667MT/s              | 1         | 2.44%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 2.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 1         | 2.44%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 2.44%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s          | 1         | 2.44%   |
| Kingston RAM HP26D4S9S8HJ-8 8GB SODIMM DDR4 2667MT/s             | 1         | 2.44%   |
| Kingston RAM 99U5624-013.A00G 8GB SODIMM DDR4 2400MT/s           | 1         | 2.44%   |
| Kingston RAM 9905700-053.A00G 8192MB SODIMM DDR4 3200MT/s        | 1         | 2.44%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 81.82%  |
| LPDDR4 | 2         | 6.06%   |
| LPDDR3 | 2         | 6.06%   |
| DDR3   | 2         | 6.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 81.82%  |
| Row Of Chips | 6         | 18.18%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 22        | 62.86%  |
| 16384 | 6         | 17.14%  |
| 32768 | 3         | 8.57%   |
| 4096  | 3         | 8.57%   |
| 2048  | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 15        | 42.86%  |
| 3200  | 13        | 37.14%  |
| 4267  | 2         | 5.71%   |
| 2133  | 2         | 5.71%   |
| 1600  | 2         | 5.71%   |
| 2400  | 1         | 2.86%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| IMC Networks                  | 7         | 25.93%  |
| Chicony Electronics           | 7         | 25.93%  |
| Sunplus Innovation Technology | 2         | 7.41%   |
| Realtek Semiconductor         | 2         | 7.41%   |
| Luxvisions Innotech Limited   | 2         | 7.41%   |
| Lite-On Technology            | 2         | 7.41%   |
| Acer                          | 2         | 7.41%   |
| Syntek                        | 1         | 3.7%    |
| Quanta                        | 1         | 3.7%    |
| Microdia                      | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 6         | 22.22%  |
| Chicony Integrated Camera                           | 3         | 11.11%  |
| Sunplus Integrated_Webcam_HD                        | 2         | 7.41%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 7.41%   |
| Chicony HD User Facing                              | 2         | 7.41%   |
| Syntek Integrated Camera                            | 1         | 3.7%    |
| Realtek Integrated Webcam HD                        | 1         | 3.7%    |
| Realtek Integrated Camera                           | 1         | 3.7%    |
| Quanta HD Webcam                                    | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD                       | 1         | 3.7%    |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 3.7%    |
| Lite-On Integrated Camera                           | 1         | 3.7%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 3.7%    |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 3.7%    |
| Chicony HP Truevision HD                            | 1         | 3.7%    |
| Acer NEC HD WebCam                                  | 1         | 3.7%    |
| Acer HD Webcam                                      | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Elan Microelectronics      | 2         | 40%     |
| Validity Sensors           | 1         | 20%     |
| Synaptics                  | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                             | 2         | 40%     |
| Validity Sensors Synaptics WBDI                   | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device               | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 33.33%  |
| Broadcom 58200                      | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 18        | 54.55%  |
| 1     | 9         | 27.27%  |
| 3     | 3         | 9.09%   |
| 2     | 3         | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 5         | 20.83%  |
| Camera                   | 4         | 16.67%  |
| Multimedia controller    | 3         | 12.5%   |
| Chipcard                 | 3         | 12.5%   |
| Graphics card            | 2         | 8.33%   |
| Communication controller | 2         | 8.33%   |
| Bluetooth                | 2         | 8.33%   |
| Storage/ata              | 1         | 4.17%   |
| Net/wireless             | 1         | 4.17%   |
| Card reader              | 1         | 4.17%   |

