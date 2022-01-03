Void - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for Void.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | B450M-A PRO MAX             | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI      | B450M-A PRO MAX             | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| Gigabyte | B450M DS3H-CF               | [093a7d451a](https://linux-hardware.org/?probe=093a7d451a) | Oct 16, 2021 |
| Gigabyte | B450M DS3H-CF               | [7917f7d57f](https://linux-hardware.org/?probe=7917f7d57f) | Oct 12, 2021 |
| Gigabyte | H310M M.2 x.x               | [6ad302377d](https://linux-hardware.org/?probe=6ad302377d) | Sep 30, 2021 |
| MSI      | B450 TOMAHAWK MAX II        | [a0d3015e21](https://linux-hardware.org/?probe=a0d3015e21) | Sep 15, 2021 |
| ASUSTek  | M4A89GTD-PRO/USB3           | [d3c1b5c10c](https://linux-hardware.org/?probe=d3c1b5c10c) | Sep 11, 2021 |
| ASUSTek  | ROG CROSSHAIR VII HERO      | [bc2b986f06](https://linux-hardware.org/?probe=bc2b986f06) | Aug 19, 2021 |
| ASUSTek  | ROG CROSSHAIR VII HERO      | [85d1c86c68](https://linux-hardware.org/?probe=85d1c86c68) | Aug 19, 2021 |
| Dell     | 03NVJ6 A02                  | [5dec53ee3f](https://linux-hardware.org/?probe=5dec53ee3f) | Jul 26, 2021 |
| ASRock   | J4005B-ITX                  | [053a28a1b7](https://linux-hardware.org/?probe=053a28a1b7) | Jun 13, 2021 |
| ASRock   | H61M-VG4                    | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| ASRock   | H61M-VG4                    | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| ASUSTek  | M5A78L-M LX                 | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek  | M5A78L-M LX                 | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| ASRock   | B450 Pro4                   | [42d648695d](https://linux-hardware.org/?probe=42d648695d) | Mar 26, 2021 |
| Unknown  | Unknown                     | [35af7cfd3d](https://linux-hardware.org/?probe=35af7cfd3d) | Feb 22, 2021 |
| ASRock   | B450 Pro4                   | [09b0e87eec](https://linux-hardware.org/?probe=09b0e87eec) | Feb 12, 2021 |
| ASUSTek  | PRIME Z390-P                | [5d02f20d1d](https://linux-hardware.org/?probe=5d02f20d1d) | Feb 10, 2021 |
| MSI      | MPG B550I GAMING EDGE WI... | [624f71f228](https://linux-hardware.org/?probe=624f71f228) | Jan 21, 2021 |
| ASUSTek  | PRIME Z390-P                | [73c3fdc605](https://linux-hardware.org/?probe=73c3fdc605) | Jan 16, 2021 |
| ASUSTek  | PRIME Z270-AR               | [35d08fe710](https://linux-hardware.org/?probe=35d08fe710) | Dec 30, 2020 |
| MSI      | MPG B550I GAMING EDGE WI... | [1f66d0eb72](https://linux-hardware.org/?probe=1f66d0eb72) | Dec 22, 2020 |
| MSI      | MPG B550I GAMING EDGE WI... | [61887011a6](https://linux-hardware.org/?probe=61887011a6) | Dec 22, 2020 |
| ASUSTek  | B150M PRO GAMING            | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| ASUSTek  | B150M PRO GAMING            | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| ASUSTek  | H110M-PLUS                  | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| ASUSTek  | PRIME B360M-A               | [438477ec85](https://linux-hardware.org/?probe=438477ec85) | Nov 14, 2020 |
| ASUSTek  | PRIME B360M-A               | [ac5adde915](https://linux-hardware.org/?probe=ac5adde915) | Nov 13, 2020 |
| ASRock   | 970 Pro3 R2.0               | [d889341667](https://linux-hardware.org/?probe=d889341667) | Oct 28, 2020 |
| MSI      | Z270 TOMAHAWK               | [66f15fef73](https://linux-hardware.org/?probe=66f15fef73) | Sep 28, 2020 |
| ASUSTek  | P8Z77-V LX2                 | [ee56035e75](https://linux-hardware.org/?probe=ee56035e75) | Sep 24, 2020 |
| ASUSTek  | P8H67-V                     | [9bc61b31d4](https://linux-hardware.org/?probe=9bc61b31d4) | Sep 02, 2020 |
| Gigabyte | GA-78LMT-S2                 | [efac4b3e2b](https://linux-hardware.org/?probe=efac4b3e2b) | May 25, 2020 |
| Dell     | 0H8052                      | [18169ce984](https://linux-hardware.org/?probe=18169ce984) | Jan 29, 2020 |
| Unknown  | Unknown                     | [b9eb4a5652](https://linux-hardware.org/?probe=b9eb4a5652) | Jan 24, 2020 |
| Unknown  | Unknown                     | [ac87dc43f3](https://linux-hardware.org/?probe=ac87dc43f3) | Jan 24, 2020 |
| ASUSTek  | H110M-PLUS                  | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| ASRock   | AB350M                      | [1ec4015426](https://linux-hardware.org/?probe=1ec4015426) | Sep 01, 2019 |
| ASRock   | N68-S3 FX                   | [69e86c050b](https://linux-hardware.org/?probe=69e86c050b) | Aug 18, 2019 |
| ASRock   | N68-S3 FX                   | [ef4f02af88](https://linux-hardware.org/?probe=ef4f02af88) | Aug 16, 2019 |
| ASUSTek  | Z97-A                       | [c2458d18f6](https://linux-hardware.org/?probe=c2458d18f6) | Aug 03, 2019 |
| MSI      | B350M GAMING PRO            | [20e1f5d7a1](https://linux-hardware.org/?probe=20e1f5d7a1) | Apr 17, 2019 |
| ASUSTek  | PRIME A320M-K/BR            | [1b0a4407c7](https://linux-hardware.org/?probe=1b0a4407c7) | Mar 27, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Desktops | Percent |
|-----------|----------|---------|
| 5.8.18_1  | 2        | 6.25%   |
| 5.13.19_1 | 2        | 6.25%   |
| 5.11.9_1  | 2        | 6.25%   |
| 5.10.14_1 | 2        | 6.25%   |
| 5.9.14_1  | 1        | 3.13%   |
| 5.8.5_1   | 1        | 3.13%   |
| 5.8.16_1  | 1        | 3.13%   |
| 5.8.11_1  | 1        | 3.13%   |
| 5.8.10_1  | 1        | 3.13%   |
| 5.6.14_1  | 1        | 3.13%   |
| 5.4.15_1  | 1        | 3.13%   |
| 5.4.13_2  | 1        | 3.13%   |
| 5.3.16_1  | 1        | 3.13%   |
| 5.13.15_1 | 1        | 3.13%   |
| 5.13.13_1 | 1        | 3.13%   |
| 5.13.10_1 | 1        | 3.13%   |
| 5.12.14_1 | 1        | 3.13%   |
| 5.12.10_1 | 1        | 3.13%   |
| 5.11.18_1 | 1        | 3.13%   |
| 5.10.8_1  | 1        | 3.13%   |
| 5.10.7_1  | 1        | 3.13%   |
| 5.10.67_1 | 1        | 3.13%   |
| 5.10.3_1  | 1        | 3.13%   |
| 5.10.17_1 | 1        | 3.13%   |
| 4.19.67_1 | 1        | 3.13%   |
| 4.19.66_1 | 1        | 3.13%   |
| 4.19.34_1 | 1        | 3.13%   |
| 4.19.31_1 | 1        | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.18  | 2        | 6.25%   |
| 5.13.19 | 2        | 6.25%   |
| 5.11.9  | 2        | 6.25%   |
| 5.10.14 | 2        | 6.25%   |
| 5.9.14  | 1        | 3.13%   |
| 5.8.5   | 1        | 3.13%   |
| 5.8.16  | 1        | 3.13%   |
| 5.8.11  | 1        | 3.13%   |
| 5.8.10  | 1        | 3.13%   |
| 5.6.14  | 1        | 3.13%   |
| 5.4.15  | 1        | 3.13%   |
| 5.4.13  | 1        | 3.13%   |
| 5.3.16  | 1        | 3.13%   |
| 5.13.15 | 1        | 3.13%   |
| 5.13.13 | 1        | 3.13%   |
| 5.13.10 | 1        | 3.13%   |
| 5.12.14 | 1        | 3.13%   |
| 5.12.10 | 1        | 3.13%   |
| 5.11.18 | 1        | 3.13%   |
| 5.10.8  | 1        | 3.13%   |
| 5.10.7  | 1        | 3.13%   |
| 5.10.67 | 1        | 3.13%   |
| 5.10.3  | 1        | 3.13%   |
| 5.10.17 | 1        | 3.13%   |
| 4.19.67 | 1        | 3.13%   |
| 4.19.66 | 1        | 3.13%   |
| 4.19.34 | 1        | 3.13%   |
| 4.19.31 | 1        | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 7        | 21.88%  |
| 5.8     | 6        | 18.75%  |
| 5.13    | 5        | 15.63%  |
| 4.19    | 4        | 12.5%   |
| 5.11    | 3        | 9.38%   |
| 5.4     | 2        | 6.25%   |
| 5.12    | 2        | 6.25%   |
| 5.9     | 1        | 3.13%   |
| 5.6     | 1        | 3.13%   |
| 5.3     | 1        | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 27       | 93.1%   |
| ppc64le | 1        | 3.45%   |
| i686    | 1        | 3.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 60%     |
| XFCE       | 3        | 10%     |
| X-Cinnamon | 2        | 6.67%   |
| GNOME      | 2        | 6.67%   |
| Lumina     | 1        | 3.33%   |
| KDE5       | 1        | 3.33%   |
| KDE        | 1        | 3.33%   |
| bspwm      | 1        | 3.33%   |
| awesome    | 1        | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 22       | 75.86%  |
| Wayland | 3        | 10.34%  |
| Tty     | 3        | 10.34%  |
| Unknown | 1        | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 96.55%  |
| LXDM    | 1        | 3.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 12       | 38.71%  |
| Unknown | 9        | 29.03%  |
| ru_RU   | 2        | 6.45%   |
| pt_BR   | 1        | 3.23%   |
| en_GB   | 1        | 3.23%   |
| en_DK   | 1        | 3.23%   |
| en_AU   | 1        | 3.23%   |
| el_GR   | 1        | 3.23%   |
| de_DE   | 1        | 3.23%   |
| cs_CZ   | 1        | 3.23%   |
| bg_BG   | 1        | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 19       | 65.52%  |
| EFI  | 10       | 34.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 18       | 62.07%  |
| Btrfs   | 5        | 17.24%  |
| Zfs     | 3        | 10.34%  |
| Xfs     | 2        | 6.9%    |
| Unknown | 1        | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 13       | 44.83%  |
| Unknown | 11       | 37.93%  |
| MBR     | 5        | 17.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 86.21%  |
| Yes       | 4        | 13.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 86.21%  |
| Yes       | 4        | 13.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 37.93%  |
| ASRock              | 6        | 20.69%  |
| MSI                 | 5        | 17.24%  |
| Gigabyte Technology | 3        | 10.34%  |
| Dell                | 2        | 6.9%    |
| Unknown             | 2        | 6.9%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS PRIME Z390-P           | 2        | 6.9%    |
| Unknown                     | 2        | 6.9%    |
| MSI MS-7C92                 | 1        | 3.45%   |
| MSI MS-7C52                 | 1        | 3.45%   |
| MSI MS-7C02                 | 1        | 3.45%   |
| MSI MS-7A68                 | 1        | 3.45%   |
| MSI MS-7A39                 | 1        | 3.45%   |
| Gigabyte H310M M.2 2.0      | 1        | 3.45%   |
| Gigabyte GA-78LMT-S2        | 1        | 3.45%   |
| Gigabyte B450M DS3H         | 1        | 3.45%   |
| Dell OptiPlex GX520         | 1        | 3.45%   |
| Dell OptiPlex 780           | 1        | 3.45%   |
| ASUS ROG CROSSHAIR VII HERO | 1        | 3.45%   |
| ASUS PRIME Z270-AR          | 1        | 3.45%   |
| ASUS PRIME A320M-K/BR       | 1        | 3.45%   |
| ASUS P8Z77-V LX2            | 1        | 3.45%   |
| ASUS P8H67-V                | 1        | 3.45%   |
| ASUS M5A78L-M LX            | 1        | 3.45%   |
| ASUS M4A89GTD-PRO/USB3      | 1        | 3.45%   |
| ASUS H110M-PLUS             | 1        | 3.45%   |
| ASUS B150M PRO GAMING       | 1        | 3.45%   |
| ASRock N68-S3 FX            | 1        | 3.45%   |
| ASRock J4005B-ITX           | 1        | 3.45%   |
| ASRock H61M-VG4             | 1        | 3.45%   |
| ASRock B450 Pro4            | 1        | 3.45%   |
| ASRock AB350M               | 1        | 3.45%   |
| ASRock 970 Pro3 R2.0        | 1        | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 4        | 13.79%  |
| Dell OptiPlex        | 2        | 6.9%    |
| Unknown              | 2        | 6.9%    |
| MSI MS-7C92          | 1        | 3.45%   |
| MSI MS-7C52          | 1        | 3.45%   |
| MSI MS-7C02          | 1        | 3.45%   |
| MSI MS-7A68          | 1        | 3.45%   |
| MSI MS-7A39          | 1        | 3.45%   |
| Gigabyte H310M       | 1        | 3.45%   |
| Gigabyte GA-78LMT-S2 | 1        | 3.45%   |
| Gigabyte B450M       | 1        | 3.45%   |
| ASUS ROG             | 1        | 3.45%   |
| ASUS P8Z77-V         | 1        | 3.45%   |
| ASUS P8H67-V         | 1        | 3.45%   |
| ASUS M5A78L-M        | 1        | 3.45%   |
| ASUS M4A89GTD-PRO    | 1        | 3.45%   |
| ASUS H110M-PLUS      | 1        | 3.45%   |
| ASUS B150M           | 1        | 3.45%   |
| ASRock N68-S3        | 1        | 3.45%   |
| ASRock J4005B-ITX    | 1        | 3.45%   |
| ASRock H61M-VG4      | 1        | 3.45%   |
| ASRock B450          | 1        | 3.45%   |
| ASRock AB350M        | 1        | 3.45%   |
| ASRock 970           | 1        | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 7        | 24.14%  |
| 2018    | 6        | 20.69%  |
| 2016    | 3        | 10.34%  |
| 2013    | 3        | 10.34%  |
| 2012    | 3        | 10.34%  |
| 2019    | 2        | 6.9%    |
| 2021    | 1        | 3.45%   |
| 2014    | 1        | 3.45%   |
| 2011    | 1        | 3.45%   |
| 2006    | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 29       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 29       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 29       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 10       | 34.48%  |
| 16.01-24.0  | 7        | 24.14%  |
| 4.01-8.0    | 4        | 13.79%  |
| 32.01-64.0  | 4        | 13.79%  |
| 3.01-4.0    | 2        | 6.9%    |
| 2.01-3.0    | 1        | 3.45%   |
| 64.01-256.0 | 1        | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 9        | 28.13%  |
| 3.01-4.0   | 5        | 15.63%  |
| 1.01-2.0   | 5        | 15.63%  |
| 0.51-1.0   | 5        | 15.63%  |
| 4.01-8.0   | 4        | 12.5%   |
| 8.01-16.0  | 3        | 9.38%   |
| 16.01-24.0 | 1        | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 37.93%  |
| 3      | 10       | 34.48%  |
| 2      | 7        | 24.14%  |
| 4      | 1        | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 82.76%  |
| Yes       | 5        | 17.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 68.97%  |
| Yes       | 9        | 31.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 80%     |
| Yes       | 6        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 8        | 27.59%  |
| Germany    | 3        | 10.34%  |
| Brazil     | 3        | 10.34%  |
| Russia     | 2        | 6.9%    |
| Czechia    | 2        | 6.9%    |
| UK         | 1        | 3.45%   |
| Turkey     | 1        | 3.45%   |
| Sweden     | 1        | 3.45%   |
| Spain      | 1        | 3.45%   |
| Poland     | 1        | 3.45%   |
| India      | 1        | 3.45%   |
| Greece     | 1        | 3.45%   |
| Bulgaria   | 1        | 3.45%   |
| Bangladesh | 1        | 3.45%   |
| Australia  | 1        | 3.45%   |
| Argentina  | 1        | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Denver         | 3        | 10.34%  |
| Munich         | 2        | 6.9%    |
| Yekaterinburg  | 1        | 3.45%   |
| Varna          | 1        | 3.45%   |
| Sydney         | 1        | 3.45%   |
| South Shields  | 1        | 3.45%   |
| Rosario        | 1        | 3.45%   |
| Rio de Janeiro | 1        | 3.45%   |
| Richmond       | 1        | 3.45%   |
| Prague         | 1        | 3.45%   |
| New York       | 1        | 3.45%   |
| Miedziana Gora | 1        | 3.45%   |
| Kotlas         | 1        | 3.45%   |
| Kolkata        | 1        | 3.45%   |
| Ioannina       | 1        | 3.45%   |
| Horice         | 1        | 3.45%   |
| Gothenburg     | 1        | 3.45%   |
| Elgin          | 1        | 3.45%   |
| Dhaka          | 1        | 3.45%   |
| Denizli        | 1        | 3.45%   |
| Contagem       | 1        | 3.45%   |
| Burgau         | 1        | 3.45%   |
| Blumenau       | 1        | 3.45%   |
| Beaver         | 1        | 3.45%   |
| Allenton       | 1        | 3.45%   |
| Alaraz         | 1        | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 18     | 22.64%  |
| Samsung Electronics | 11       | 17     | 20.75%  |
| Seagate             | 7        | 8      | 13.21%  |
| Kingston            | 6        | 6      | 11.32%  |
| Toshiba             | 3        | 3      | 5.66%   |
| Intel               | 2        | 3      | 3.77%   |
| Corsair             | 2        | 2      | 3.77%   |
| SPCC                | 1        | 1      | 1.89%   |
| SanDisk             | 1        | 1      | 1.89%   |
| Phison              | 1        | 1      | 1.89%   |
| Patriot             | 1        | 1      | 1.89%   |
| OCZ                 | 1        | 1      | 1.89%   |
| MAXTOR              | 1        | 1      | 1.89%   |
| LITEONIT            | 1        | 1      | 1.89%   |
| Gigabyte Technology | 1        | 1      | 1.89%   |
| Crucial             | 1        | 2      | 1.89%   |
| A-DATA Technology   | 1        | 2      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                 | 3        | 4.92%   |
| Samsung SSD 970 EVO Plus 1TB             | 2        | 3.28%   |
| Kingston SHFS37A120G 120GB SSD           | 2        | 3.28%   |
| Kingston SA400S37240G 240GB SSD          | 2        | 3.28%   |
| WDC WD7500AYYS-01RCA0 752GB              | 1        | 1.64%   |
| WDC WD5000AADS-00S9B0 500GB              | 1        | 1.64%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 1.64%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1        | 1.64%   |
| WDC WD15EARS-00MVWB0 1TB                 | 1        | 1.64%   |
| WDC WD10JPVX-08JC3T6 1TB                 | 1        | 1.64%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1        | 1.64%   |
| WDC WD10EZRX-00L4HB0 1TB                 | 1        | 1.64%   |
| WDC WD10EFRX-68PJCN0 1TB                 | 1        | 1.64%   |
| WDC WD10EFRX-68FYTN0 1TB                 | 1        | 1.64%   |
| WDC WD1002FAEX-00Z3A0 1TB                | 1        | 1.64%   |
| WDC WD1001FALS-00K1B0 1TB                | 1        | 1.64%   |
| Toshiba MQ04ABF100 1TB                   | 1        | 1.64%   |
| Toshiba HDWD110 1TB                      | 1        | 1.64%   |
| Toshiba DT01ACA200 2TB                   | 1        | 1.64%   |
| SPCC Solid State Disk 128GB              | 1        | 1.64%   |
| Seagate ST9500325AS 500GB                | 1        | 1.64%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1.64%   |
| Seagate ST3500413AS 500GB                | 1        | 1.64%   |
| Seagate ST3360320AS 360GB                | 1        | 1.64%   |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1.64%   |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB           | 1        | 1.64%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1.64%   |
| SanDisk Ultra 3D NVMe 1TB                | 1        | 1.64%   |
| Samsung SSD 980 PRO 500GB                | 1        | 1.64%   |
| Samsung SSD 970 EVO Plus 500GB           | 1        | 1.64%   |
| Samsung SSD 970 EVO 500GB                | 1        | 1.64%   |
| Samsung SSD 970 EVO 1TB                  | 1        | 1.64%   |
| Samsung SSD 860 EVO 500GB                | 1        | 1.64%   |
| Samsung SSD 860 EVO 250GB                | 1        | 1.64%   |
| Samsung SSD 850 EVO 500GB                | 1        | 1.64%   |
| Samsung SSD 840 PRO Series 512GB         | 1        | 1.64%   |
| Samsung SSD 750 EVO 500GB                | 1        | 1.64%   |
| Samsung NVMe SSD Drive 500GB             | 1        | 1.64%   |
| Samsung NVMe SSD Drive 1TB               | 1        | 1.64%   |
| Samsung HD322HJ 320GB                    | 1        | 1.64%   |
| Phison NVMe SSD Drive 1TB                | 1        | 1.64%   |
| Patriot Burst 120GB SSD                  | 1        | 1.64%   |
| OCZ AGILITY4 256GB SSD                   | 1        | 1.64%   |
| MAXTOR 7L250S0 256GB                     | 1        | 1.64%   |
| LITEONIT LCS-256L9S-11 2.5 7mm 256GB SSD | 1        | 1.64%   |
| Kingston SUV500MS120G 120GB SSD          | 1        | 1.64%   |
| Kingston SA400S37120G 120GB SSD          | 1        | 1.64%   |
| Intel SSDSC2BW240H6 240GB                | 1        | 1.64%   |
| Intel SSDPEKKW256G8 256GB                | 1        | 1.64%   |
| Intel NVMe SSD Drive 256GB               | 1        | 1.64%   |
| Gigabyte GP-GSTFS31240GNTD 240GB         | 1        | 1.64%   |
| Crucial CT960M500SSD1 960GB              | 1        | 1.64%   |
| Corsair Force MP600 1TB                  | 1        | 1.64%   |
| Corsair CSSD-V128GB2                     | 1        | 1.64%   |
| A-DATA SU700 120GB SSD                   | 1        | 1.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 18     | 50%     |
| Seagate             | 7        | 8      | 29.17%  |
| Toshiba             | 3        | 3      | 12.5%   |
| Samsung Electronics | 1        | 1      | 4.17%   |
| MAXTOR              | 1        | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 6      | 30%     |
| Samsung Electronics | 5        | 5      | 25%     |
| SPCC                | 1        | 1      | 5%      |
| Patriot             | 1        | 1      | 5%      |
| OCZ                 | 1        | 1      | 5%      |
| LITEONIT            | 1        | 1      | 5%      |
| Intel               | 1        | 1      | 5%      |
| Gigabyte Technology | 1        | 1      | 5%      |
| Crucial             | 1        | 2      | 5%      |
| Corsair             | 1        | 1      | 5%      |
| A-DATA Technology   | 1        | 2      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 31     | 42.55%  |
| SSD  | 18       | 22     | 38.3%   |
| NVMe | 9        | 16     | 19.15%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 27       | 53     | 75%     |
| NVMe | 9        | 16     | 25%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 27     | 52.5%   |
| 0.51-1.0   | 14       | 19     | 35%     |
| 1.01-2.0   | 5        | 7      | 12.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 24.14%  |
| 251-500        | 5        | 17.24%  |
| 501-1000       | 4        | 13.79%  |
| Unknown        | 4        | 13.79%  |
| More than 3000 | 3        | 10.34%  |
| 1001-2000      | 3        | 10.34%  |
| 2001-3000      | 2        | 6.9%    |
| 1-20           | 1        | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 25%     |
| 1-20           | 6        | 18.75%  |
| Unknown        | 4        | 12.5%   |
| 251-500        | 3        | 9.38%   |
| 1001-2000      | 3        | 9.38%   |
| 501-1000       | 3        | 9.38%   |
| 51-100         | 3        | 9.38%   |
| More than 3000 | 1        | 3.13%   |
| 21-50          | 1        | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB       | 1        | 2      | 14.29%  |
| WDC WD10EZEX-08WN4A0 1TB          | 1        | 1      | 14.29%  |
| Toshiba MQ04ABF100 1TB            | 1        | 1      | 14.29%  |
| Seagate ST9500325AS 500GB         | 1        | 1      | 14.29%  |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 14.29%  |
| Samsung Electronics HD322HJ 320GB | 1        | 1      | 14.29%  |
| A-DATA Technology SU700 120GB SSD | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 3      | 28.57%  |
| Seagate             | 2        | 2      | 28.57%  |
| Toshiba             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| A-DATA Technology   | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 3      | 33.33%  |
| Seagate             | 2        | 2      | 33.33%  |
| Toshiba             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 7      | 83.33%  |
| SSD  | 1        | 1      | 16.67%  |

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
| Works    | 20       | 36     | 54.05%  |
| Detected | 12       | 25     | 32.43%  |
| Malfunc  | 5        | 8      | 13.51%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 15       | 36.59%  |
| AMD                      | 13       | 31.71%  |
| Samsung Electronics      | 6        | 14.63%  |
| Phison Electronics       | 2        | 4.88%   |
| Sandisk                  | 1        | 2.44%   |
| Nvidia                   | 1        | 2.44%   |
| Marvell Technology Group | 1        | 2.44%   |
| JMicron Technology       | 1        | 2.44%   |
| ASMedia Technology       | 1        | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 6        | 11.54%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5        | 9.62%   |
| AMD 400 Series Chipset SATA Controller                                        | 5        | 9.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 3        | 5.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 3        | 5.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 3        | 5.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 3.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 3.85%   |
| AMD 300 Series Chipset SATA Controller                                        | 2        | 3.85%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1        | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 1.92%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 1.92%   |
| Phison E12 NVMe Controller                                                    | 1        | 1.92%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 1.92%   |
| Nvidia MCP61 IDE                                                              | 1        | 1.92%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller              | 1        | 1.92%   |
| JMicron JMB361 AHCI/IDE                                                       | 1        | 1.92%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 1        | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1        | 1.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1        | 1.92%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                          | 1        | 1.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1        | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 1        | 1.92%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 1.92%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                      | 1        | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1        | 1.92%   |
| AMD FCH SATA Controller D                                                     | 1        | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 27       | 64.29%  |
| NVMe | 9        | 21.43%  |
| IDE  | 6        | 14.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 14       | 48.28%  |
| AMD                      | 14       | 48.28%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 3.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2        | 6.9%    |
| AMD Ryzen 5 5600X 6-Core Processor                 | 2        | 6.9%    |
| AMD FX-4300 Quad-Core Processor                    | 2        | 6.9%    |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1        | 3.45%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1        | 3.45%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1        | 3.45%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1        | 3.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 1        | 3.45%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1        | 3.45%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1        | 3.45%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1        | 3.45%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1        | 3.45%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1        | 3.45%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1        | 3.45%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1        | 3.45%   |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1        | 3.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 1        | 3.45%   |
| AMD Ryzen 7 1700 Eight-Core Processor              | 1        | 3.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics             | 1        | 3.45%   |
| AMD Ryzen 5 3600 6-Core Processor                  | 1        | 3.45%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 1        | 3.45%   |
| AMD Ryzen 5 1600 Six-Core Processor                | 1        | 3.45%   |
| AMD Ryzen 3 3100 4-Core Processor                  | 1        | 3.45%   |
| AMD Phenom II X4 980 Processor                     | 1        | 3.45%   |
| AMD Athlon II X3 455 Processor                     | 1        | 3.45%   |
| AMD Athlon II X2 280 Processor                     | 1        | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| AMD Ryzen 5        | 6        | 20.69%  |
| Intel Core i5      | 5        | 17.24%  |
| Intel Core i3      | 3        | 10.34%  |
| AMD Ryzen 7        | 2        | 6.9%    |
| AMD FX             | 2        | 6.9%    |
| Other              | 1        | 3.45%   |
| Intel Pentium Gold | 1        | 3.45%   |
| Intel Pentium 4    | 1        | 3.45%   |
| Intel Core i9      | 1        | 3.45%   |
| Intel Core i7      | 1        | 3.45%   |
| Intel Core 2 Duo   | 1        | 3.45%   |
| Intel Celeron      | 1        | 3.45%   |
| AMD Ryzen 3        | 1        | 3.45%   |
| AMD Phenom II X4   | 1        | 3.45%   |
| AMD Athlon II X3   | 1        | 3.45%   |
| AMD Athlon II X2   | 1        | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 31.03%  |
| 2      | 8        | 27.59%  |
| 6      | 6        | 20.69%  |
| 8      | 4        | 13.79%  |
| 3      | 1        | 3.45%   |
| 1      | 1        | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 16       | 55.17%  |
| 1      | 12       | 41.38%  |
| 4      | 1        | 3.45%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 25       | 86.21%  |
| Unknown        | 3        | 10.34%  |
| 32-bit         | 1        | 3.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 34.48%  |
| 0x906e9    | 2        | 6.9%    |
| 0x06000852 | 2        | 6.9%    |
| 0x010000c8 | 2        | 6.9%    |
| 0x906ed    | 1        | 3.45%   |
| 0x906ea    | 1        | 3.45%   |
| 0x706a1    | 1        | 3.45%   |
| 0x506e3    | 1        | 3.45%   |
| 0x306a9    | 1        | 3.45%   |
| 0x1067a    | 1        | 3.45%   |
| 0x0a50000c | 1        | 3.45%   |
| 0x0a201009 | 1        | 3.45%   |
| 0x08701021 | 1        | 3.45%   |
| 0x08701013 | 1        | 3.45%   |
| 0x0800820d | 1        | 3.45%   |
| 0x08001136 | 1        | 3.45%   |
| 0x08001129 | 1        | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 6        | 20.69%  |
| Zen 3         | 3        | 10.34%  |
| K10           | 3        | 10.34%  |
| IvyBridge     | 3        | 10.34%  |
| Zen+          | 2        | 6.9%    |
| Zen 2         | 2        | 6.9%    |
| Zen           | 2        | 6.9%    |
| Piledriver    | 2        | 6.9%    |
| Skylake       | 1        | 3.45%   |
| Penryn        | 1        | 3.45%   |
| NetBurst      | 1        | 3.45%   |
| Haswell       | 1        | 3.45%   |
| Goldmont plus | 1        | 3.45%   |
| Unknown       | 1        | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 14       | 43.75%  |
| AMD               | 12       | 37.5%   |
| Intel             | 5        | 15.63%  |
| ASPEED Technology | 1        | 3.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                               | 3        | 9.09%   |
| Nvidia GM204 [GeForce GTX 970]                                   | 2        | 6.06%   |
| Nvidia GK208B [GeForce GT 710]                                   | 2        | 6.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 2        | 6.06%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                            | 1        | 3.03%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                        | 1        | 3.03%   |
| Nvidia GP108 [GeForce GT 1030]                                   | 1        | 3.03%   |
| Nvidia GP107 [GeForce GTX 1050]                                  | 1        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 1        | 3.03%   |
| Nvidia GK110 [GeForce GTX 780]                                   | 1        | 3.03%   |
| Nvidia GF108 [GeForce GT 420]                                    | 1        | 3.03%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                          | 1        | 3.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                 | 1        | 3.03%   |
| Intel GeminiLake [UHD Graphics 600]                              | 1        | 3.03%   |
| Intel 82945G/GZ Integrated Graphics Controller                   | 1        | 3.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller            | 1        | 3.03%   |
| ASPEED Technology ASPEED Graphics Family                         | 1        | 3.03%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 1        | 3.03%   |
| AMD Tonga PRO [Radeon R9 285/380]                                | 1        | 3.03%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                | 1        | 3.03%   |
| AMD RS880 [Radeon HD 4290]                                       | 1        | 3.03%   |
| AMD RS780L [Radeon 3000]                                         | 1        | 3.03%   |
| AMD Oland PRO [Radeon R7 240/340]                                | 1        | 3.03%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                   | 1        | 3.03%   |
| AMD Juniper XT [Radeon HD 6770]                                  | 1        | 3.03%   |
| AMD Cezanne                                                      | 1        | 3.03%   |
| AMD Bonaire [FirePro W5100]                                      | 1        | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 13       | 43.33%  |
| 1 x AMD      | 11       | 36.67%  |
| 1 x Intel    | 4        | 13.33%  |
| 2 x Nvidia   | 1        | 3.33%   |
| AMD + ASPEED | 1        | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 17       | 56.67%  |
| Proprietary | 13       | 43.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 30%     |
| 3.01-4.0   | 7        | 23.33%  |
| 1.01-2.0   | 6        | 20%     |
| 2.01-3.0   | 2        | 6.67%   |
| 8.01-16.0  | 2        | 6.67%   |
| 7.01-8.0   | 1        | 3.33%   |
| 5.01-6.0   | 1        | 3.33%   |
| 0.51-1.0   | 1        | 3.33%   |
| 0.01-0.5   | 1        | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 15.15%  |
| Dell                 | 5        | 15.15%  |
| Philips              | 3        | 9.09%   |
| Hewlett-Packard      | 3        | 9.09%   |
| Acer                 | 3        | 9.09%   |
| Goldstar             | 2        | 6.06%   |
| BenQ                 | 2        | 6.06%   |
| Ancor Communications | 2        | 6.06%   |
| Unknown              | 1        | 3.03%   |
| Sceptre Tech         | 1        | 3.03%   |
| Sceptre              | 1        | 3.03%   |
| ONN                  | 1        | 3.03%   |
| MSI                  | 1        | 3.03%   |
| Lenovo               | 1        | 3.03%   |
| FUN                  | 1        | 3.03%   |
| Fujitsu Siemens      | 1        | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1        | 2.78%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch         | 1        | 2.78%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1        | 2.78%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1        | 2.78%   |
| Samsung Electronics SMS22A350H SAM07D2 1920x1080 480x270mm 21.7-inch  | 1        | 2.78%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1        | 2.78%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1        | 2.78%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1        | 2.78%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1        | 2.78%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1        | 2.78%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1        | 2.78%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1        | 2.78%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 1        | 2.78%   |
| Lenovo LEN-V510Z-B LEN1201 1920x1080 509x286mm 23.0-inch              | 1        | 2.78%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1        | 2.78%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1        | 2.78%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1        | 2.78%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 2.78%   |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1        | 2.78%   |
| FUN HDMI Monitor FUN9D31 3840x2160 480x270mm 21.7-inch                | 1        | 2.78%   |
| Fujitsu Siemens SL27T-1 LED FUS07E4 1920x1080 598x336mm 27.0-inch     | 1        | 2.78%   |
| Dell U3818DW DELA0F4 3840x1600 880x367mm 37.5-inch                    | 1        | 2.78%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                     | 1        | 2.78%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 1        | 2.78%   |
| Dell U2415 DELA0B8 1920x1080 520x320mm 24.0-inch                      | 1        | 2.78%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1        | 2.78%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1        | 2.78%   |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                     | 1        | 2.78%   |
| BenQ GW2470 BNQ78D9 1920x1080 530x300mm 24.0-inch                     | 1        | 2.78%   |
| Ancor Communications VW222 ACI22A2 1680x1050 473x296mm 22.0-inch      | 1        | 2.78%   |
| Ancor Communications LCD Monitor ASUS ML239 1920x1080                 | 1        | 2.78%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 1        | 2.78%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 1        | 2.78%   |
| Acer LCD Monitor S181HL 1366x768                                      | 1        | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 16       | 48.48%  |
| 1680x1050 (WSXGA+) | 4        | 12.12%  |
| 3840x2160 (4K)     | 2        | 6.06%   |
| 2560x1440 (QHD)    | 2        | 6.06%   |
| 1920x1200 (WUXGA)  | 2        | 6.06%   |
| 1366x768 (WXGA)    | 2        | 6.06%   |
| 7680x1080          | 1        | 3.03%   |
| 3840x1600          | 1        | 3.03%   |
| 3440x1440          | 1        | 3.03%   |
| 1280x1024 (SXGA)   | 1        | 3.03%   |
| Unknown            | 1        | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 23.53%  |
| 24      | 6        | 17.65%  |
| 21      | 5        | 14.71%  |
| 22      | 4        | 11.76%  |
| 27      | 3        | 8.82%   |
| 23      | 2        | 5.88%   |
| 40      | 1        | 2.94%   |
| 37      | 1        | 2.94%   |
| 34      | 1        | 2.94%   |
| 31      | 1        | 2.94%   |
| 25      | 1        | 2.94%   |
| 17      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 33.33%  |
| 401-500     | 9        | 27.27%  |
| Unknown     | 8        | 24.24%  |
| 801-900     | 2        | 6.06%   |
| 701-800     | 1        | 3.03%   |
| 601-700     | 1        | 3.03%   |
| 301-350     | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 17       | 51.52%  |
| Unknown | 8        | 24.24%  |
| 16/10   | 5        | 15.15%  |
| 21/9    | 2        | 6.06%   |
| 5/4     | 1        | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 39.39%  |
| Unknown        | 8        | 24.24%  |
| 301-350        | 3        | 9.09%   |
| 251-300        | 3        | 9.09%   |
| 351-500        | 2        | 6.06%   |
| 501-1000       | 2        | 6.06%   |
| 151-200        | 1        | 3.03%   |
| 141-150        | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 50%     |
| 101-120 | 8        | 23.53%  |
| Unknown | 8        | 23.53%  |
| 161-240 | 1        | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 83.33%  |
| 2     | 5        | 16.67%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 20       | 48.78%  |
| Intel                           | 9        | 21.95%  |
| Qualcomm Atheros Communications | 2        | 4.88%   |
| Broadcom                        | 2        | 4.88%   |
| TP-Link                         | 1        | 2.44%   |
| Tenda                           | 1        | 2.44%   |
| Ralink Technology               | 1        | 2.44%   |
| Qualcomm Atheros                | 1        | 2.44%   |
| Nvidia                          | 1        | 2.44%   |
| MediaTek                        | 1        | 2.44%   |
| ASIX Electronics                | 1        | 2.44%   |
| Apple                           | 1        | 2.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 43.9%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 7.32%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 4.88%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 4.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 2.44%   |
| Tenda U12                                                         | 1        | 2.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 2.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.44%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.44%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.44%   |
| MediaTek WP5 Pro                                                  | 1        | 2.44%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.44%   |
| Intel Ethernet Connection I218-V                                  | 1        | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.44%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 2.44%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 2.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 2.44%   |
| Apple iPad 4/Mini1                                                | 1        | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 33.33%  |
| Qualcomm Atheros Communications | 2        | 22.22%  |
| TP-Link                         | 1        | 11.11%  |
| Tenda                           | 1        | 11.11%  |
| Realtek Semiconductor           | 1        | 11.11%  |
| Ralink Technology               | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                 | 2        | 22.22%  |
| Intel Wi-Fi 6 AX200                             | 2        | 22.22%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]    | 1        | 11.11%  |
| Tenda U12                                       | 1        | 11.11%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter | 1        | 11.11%  |
| Ralink MT7601U Wireless Adapter                 | 1        | 11.11%  |
| Intel Cannon Lake PCH CNVi WiFi                 | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 59.38%  |
| Intel                 | 6        | 18.75%  |
| Broadcom              | 2        | 6.25%   |
| Qualcomm Atheros      | 1        | 3.13%   |
| Nvidia                | 1        | 3.13%   |
| MediaTek              | 1        | 3.13%   |
| ASIX Electronics      | 1        | 3.13%   |
| Apple                 | 1        | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 56.25%  |
| Intel Ethernet Connection (2) I219-V                              | 3        | 9.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 3.13%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.13%   |
| MediaTek WP5 Pro                                                  | 1        | 3.13%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.13%   |
| Intel Ethernet Connection I218-V                                  | 1        | 3.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 3.13%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 3.13%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 3.13%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 3.13%   |
| Apple iPad 4/Mini1                                                | 1        | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 76.32%  |
| WiFi     | 9        | 23.68%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 77.78%  |
| WiFi     | 8        | 22.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 82.76%  |
| 2     | 4        | 13.79%  |
| 3     | 1        | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 93.1%   |
| Yes  | 2        | 6.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 42.86%  |
| Cambridge Silicon Radio | 3        | 42.86%  |
| Broadcom                | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 42.86%  |
| Intel AX200 Bluetooth                               | 2        | 28.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 14.29%  |
| Broadcom BCM2045 Bluetooth                          | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 16       | 29.63%  |
| Nvidia              | 14       | 25.93%  |
| Intel               | 13       | 24.07%  |
| C-Media Electronics | 3        | 5.56%   |
| Logitech            | 2        | 3.7%    |
| JMTek               | 2        | 3.7%    |
| VIA Technologies    | 1        | 1.85%   |
| SAVITECH            | 1        | 1.85%   |
| Elgato Systems      | 1        | 1.85%   |
| Cambridge Audio     | 1        | 1.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 6.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 6.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 6.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 6.25%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 4.69%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 3.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 3.13%   |
| JMTek USB PnP Audio Device                                                 | 2        | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 3.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 3.13%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 1.56%   |
| SAVITECH SA9023 audio controller                                           | 1        | 1.56%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.56%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.56%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.56%   |
| Logitech G633 Gaming Headset                                               | 1        | 1.56%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1        | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.56%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 1.56%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.56%   |
| Elgato Systems Elgato Wave:3                                               | 1        | 1.56%   |
| Cambridge Audio USB Audio 2.0                                              | 1        | 1.56%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.56%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 1.56%   |
| C-Media Electronics Antlion USB adapter                                    | 1        | 1.56%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 1.56%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.56%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 1.56%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 1.56%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.56%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 1        | 1.56%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1        | 1.56%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1        | 1.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 5        | 25%     |
| Corsair             | 4        | 20%     |
| Unknown             | 3        | 15%     |
| Kingston            | 2        | 10%     |
| Crucial             | 2        | 10%     |
| A-DATA Technology   | 2        | 10%     |
| Samsung Electronics | 1        | 5%      |
| Patriot             | 1        | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 2        | 8%      |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                  | 1        | 4%      |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 4%      |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 4%      |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s        | 1        | 4%      |
| Patriot RAM PSD48G24002 8192MB DIMM DDR4 2400MT/s          | 1        | 4%      |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s          | 1        | 4%      |
| Kingston RAM 99U5474-016.A00LF 4096MB DIMM DDR3 1333MT/s   | 1        | 4%      |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 4%      |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s       | 1        | 4%      |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s        | 1        | 4%      |
| G.Skill RAM F4-2800C17-8GIS 8192MB DIMM DDR4 2800MT/s      | 1        | 4%      |
| G.Skill RAM F4-2666C18-4GRS 4096MB SODIMM DDR4 2400MT/s    | 1        | 4%      |
| G.Skill RAM F3-10666CL7-2GBRH 2048MB DIMM DDR3 1333MT/s    | 1        | 4%      |
| Crucial RAM CT8G4DFS824A.M8FE 8192MB DIMM DDR4 2933MT/s    | 1        | 4%      |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s       | 1        | 4%      |
| Crucial RAM CT16G4DFD824A.M16FJ 16384MB DIMM DDR4 2400MT/s | 1        | 4%      |
| Crucial RAM CT16G4DFD824A.M16FD 16GB DIMM DDR4 2400MT/s    | 1        | 4%      |
| Crucial RAM BL25664TN1608.16FF 2048MB DIMM DDR3 1333MT/s   | 1        | 4%      |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s        | 1        | 4%      |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s       | 1        | 4%      |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s       | 1        | 4%      |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s                | 1        | 4%      |
| A-DATA RAM DDR4 2666 2OZ 8192MB DIMM DDR4 3200MT/s         | 1        | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 13       | 65%     |
| DDR3    | 5        | 25%     |
| Unknown | 2        | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 19       | 95%     |
| SODIMM | 1        | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 47.62%  |
| 4096  | 5        | 23.81%  |
| 16384 | 3        | 14.29%  |
| 2048  | 2        | 9.52%   |
| 1024  | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 5        | 21.74%  |
| 1333  | 5        | 21.74%  |
| 3200  | 4        | 17.39%  |
| 3600  | 3        | 13.04%  |
| 3000  | 2        | 8.7%    |
| 2933  | 1        | 4.35%   |
| 2800  | 1        | 4.35%   |
| 1867  | 1        | 4.35%   |
| 1067  | 1        | 4.35%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Logitech              | 4        | 36.36%  |
| Microdia              | 2        | 18.18%  |
| Realtek Semiconductor | 1        | 9.09%   |
| Microsoft             | 1        | 9.09%   |
| MacroSilicon          | 1        | 9.09%   |
| MACROSIL              | 1        | 9.09%   |
| Chicony Electronics   | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek FULL HD 1080P Webcam      | 1        | 9.09%   |
| Microsoft LifeCam HD-3000         | 1        | 9.09%   |
| Microdia USB Live camera          | 1        | 9.09%   |
| Microdia Camera                   | 1        | 9.09%   |
| MacroSilicon USB Video            | 1        | 9.09%   |
| MACROSIL AV TO USB2.0             | 1        | 9.09%   |
| Logitech Webcam C930e             | 1        | 9.09%   |
| Logitech Webcam C270              | 1        | 9.09%   |
| Logitech HD Webcam C615           | 1        | 9.09%   |
| Logitech C922 Pro Stream Webcam   | 1        | 9.09%   |
| Chicony HP 720p HD Monitor Webcam | 1        | 9.09%   |

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
| 0     | 25       | 86.21%  |
| 2     | 2        | 6.9%    |
| 1     | 2        | 6.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Sound         | 2        | 33.33%  |
| Graphics card | 2        | 33.33%  |
| Net/wireless  | 1        | 16.67%  |
| Camera        | 1        | 16.67%  |

