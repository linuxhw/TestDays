Void Linux - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Void Linux.

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
| Gigabyte | B450M DS3H-CF               | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Gigabyte | B550M AORUS PRO-P           | [61374a4048](https://linux-hardware.org/?probe=61374a4048) | Jan 25, 2022 |
| ASUSTek  | PRIME X470-PRO              | [24fedcca0a](https://linux-hardware.org/?probe=24fedcca0a) | Jan 18, 2022 |
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
| 5.8.18_1  | 2        | 5.71%   |
| 5.13.19_1 | 2        | 5.71%   |
| 5.11.9_1  | 2        | 5.71%   |
| 5.10.14_1 | 2        | 5.71%   |
| 5.9.14_1  | 1        | 2.86%   |
| 5.8.5_1   | 1        | 2.86%   |
| 5.8.16_1  | 1        | 2.86%   |
| 5.8.11_1  | 1        | 2.86%   |
| 5.8.10_1  | 1        | 2.86%   |
| 5.6.14_1  | 1        | 2.86%   |
| 5.4.15_1  | 1        | 2.86%   |
| 5.4.13_2  | 1        | 2.86%   |
| 5.3.16_1  | 1        | 2.86%   |
| 5.15.22_1 | 1        | 2.86%   |
| 5.15.16_1 | 1        | 2.86%   |
| 5.15.11_1 | 1        | 2.86%   |
| 5.13.15_1 | 1        | 2.86%   |
| 5.13.13_1 | 1        | 2.86%   |
| 5.13.10_1 | 1        | 2.86%   |
| 5.12.14_1 | 1        | 2.86%   |
| 5.12.10_1 | 1        | 2.86%   |
| 5.11.18_1 | 1        | 2.86%   |
| 5.10.8_1  | 1        | 2.86%   |
| 5.10.7_1  | 1        | 2.86%   |
| 5.10.67_1 | 1        | 2.86%   |
| 5.10.3_1  | 1        | 2.86%   |
| 5.10.17_1 | 1        | 2.86%   |
| 4.19.67_1 | 1        | 2.86%   |
| 4.19.66_1 | 1        | 2.86%   |
| 4.19.34_1 | 1        | 2.86%   |
| 4.19.31_1 | 1        | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.18  | 2        | 5.71%   |
| 5.13.19 | 2        | 5.71%   |
| 5.11.9  | 2        | 5.71%   |
| 5.10.14 | 2        | 5.71%   |
| 5.9.14  | 1        | 2.86%   |
| 5.8.5   | 1        | 2.86%   |
| 5.8.16  | 1        | 2.86%   |
| 5.8.11  | 1        | 2.86%   |
| 5.8.10  | 1        | 2.86%   |
| 5.6.14  | 1        | 2.86%   |
| 5.4.15  | 1        | 2.86%   |
| 5.4.13  | 1        | 2.86%   |
| 5.3.16  | 1        | 2.86%   |
| 5.15.22 | 1        | 2.86%   |
| 5.15.16 | 1        | 2.86%   |
| 5.15.11 | 1        | 2.86%   |
| 5.13.15 | 1        | 2.86%   |
| 5.13.13 | 1        | 2.86%   |
| 5.13.10 | 1        | 2.86%   |
| 5.12.14 | 1        | 2.86%   |
| 5.12.10 | 1        | 2.86%   |
| 5.11.18 | 1        | 2.86%   |
| 5.10.8  | 1        | 2.86%   |
| 5.10.7  | 1        | 2.86%   |
| 5.10.67 | 1        | 2.86%   |
| 5.10.3  | 1        | 2.86%   |
| 5.10.17 | 1        | 2.86%   |
| 4.19.67 | 1        | 2.86%   |
| 4.19.66 | 1        | 2.86%   |
| 4.19.34 | 1        | 2.86%   |
| 4.19.31 | 1        | 2.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 7        | 20%     |
| 5.8     | 6        | 17.14%  |
| 5.13    | 5        | 14.29%  |
| 4.19    | 4        | 11.43%  |
| 5.15    | 3        | 8.57%   |
| 5.11    | 3        | 8.57%   |
| 5.4     | 2        | 5.71%   |
| 5.12    | 2        | 5.71%   |
| 5.9     | 1        | 2.86%   |
| 5.6     | 1        | 2.86%   |
| 5.3     | 1        | 2.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 29       | 93.55%  |
| ppc64le | 1        | 3.23%   |
| i686    | 1        | 3.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 56.25%  |
| XFCE       | 4        | 12.5%   |
| X-Cinnamon | 2        | 6.25%   |
| KDE        | 2        | 6.25%   |
| GNOME      | 2        | 6.25%   |
| Lumina     | 1        | 3.13%   |
| KDE5       | 1        | 3.13%   |
| bspwm      | 1        | 3.13%   |
| awesome    | 1        | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 24       | 77.42%  |
| Wayland | 3        | 9.68%   |
| Tty     | 3        | 9.68%   |
| Unknown | 1        | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 96.77%  |
| LXDM    | 1        | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 13       | 39.39%  |
| Unknown | 9        | 27.27%  |
| ru_RU   | 2        | 6.06%   |
| pt_BR   | 1        | 3.03%   |
| fr_FR   | 1        | 3.03%   |
| en_GB   | 1        | 3.03%   |
| en_DK   | 1        | 3.03%   |
| en_AU   | 1        | 3.03%   |
| el_GR   | 1        | 3.03%   |
| de_DE   | 1        | 3.03%   |
| cs_CZ   | 1        | 3.03%   |
| bg_BG   | 1        | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 20       | 62.5%   |
| EFI  | 12       | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 20       | 64.52%  |
| Btrfs   | 5        | 16.13%  |
| Zfs     | 3        | 9.68%   |
| Xfs     | 2        | 6.45%   |
| Unknown | 1        | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 14       | 45.16%  |
| Unknown | 12       | 38.71%  |
| MBR     | 5        | 16.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 87.1%   |
| Yes       | 4        | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 83.87%  |
| Yes       | 5        | 16.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 38.71%  |
| ASRock              | 6        | 19.35%  |
| MSI                 | 5        | 16.13%  |
| Gigabyte Technology | 4        | 12.9%   |
| Dell                | 2        | 6.45%   |
| Unknown             | 2        | 6.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS PRIME Z390-P           | 2        | 6.45%   |
| Unknown                     | 2        | 6.45%   |
| MSI MS-7C92                 | 1        | 3.23%   |
| MSI MS-7C52                 | 1        | 3.23%   |
| MSI MS-7C02                 | 1        | 3.23%   |
| MSI MS-7A68                 | 1        | 3.23%   |
| MSI MS-7A39                 | 1        | 3.23%   |
| Gigabyte H310M M.2 2.0      | 1        | 3.23%   |
| Gigabyte GA-78LMT-S2        | 1        | 3.23%   |
| Gigabyte B550M AORUS PRO-P  | 1        | 3.23%   |
| Gigabyte B450M DS3H         | 1        | 3.23%   |
| Dell OptiPlex GX520         | 1        | 3.23%   |
| Dell OptiPlex 780           | 1        | 3.23%   |
| ASUS ROG CROSSHAIR VII HERO | 1        | 3.23%   |
| ASUS PRIME Z270-AR          | 1        | 3.23%   |
| ASUS PRIME X470-PRO         | 1        | 3.23%   |
| ASUS PRIME A320M-K/BR       | 1        | 3.23%   |
| ASUS P8Z77-V LX2            | 1        | 3.23%   |
| ASUS P8H67-V                | 1        | 3.23%   |
| ASUS M5A78L-M LX            | 1        | 3.23%   |
| ASUS M4A89GTD-PRO/USB3      | 1        | 3.23%   |
| ASUS H110M-PLUS             | 1        | 3.23%   |
| ASUS B150M PRO GAMING       | 1        | 3.23%   |
| ASRock N68-S3 FX            | 1        | 3.23%   |
| ASRock J4005B-ITX           | 1        | 3.23%   |
| ASRock H61M-VG4             | 1        | 3.23%   |
| ASRock B450 Pro4            | 1        | 3.23%   |
| ASRock AB350M               | 1        | 3.23%   |
| ASRock 970 Pro3 R2.0        | 1        | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 5        | 16.13%  |
| Dell OptiPlex        | 2        | 6.45%   |
| Unknown              | 2        | 6.45%   |
| MSI MS-7C92          | 1        | 3.23%   |
| MSI MS-7C52          | 1        | 3.23%   |
| MSI MS-7C02          | 1        | 3.23%   |
| MSI MS-7A68          | 1        | 3.23%   |
| MSI MS-7A39          | 1        | 3.23%   |
| Gigabyte H310M       | 1        | 3.23%   |
| Gigabyte GA-78LMT-S2 | 1        | 3.23%   |
| Gigabyte B550M       | 1        | 3.23%   |
| Gigabyte B450M       | 1        | 3.23%   |
| ASUS ROG             | 1        | 3.23%   |
| ASUS P8Z77-V         | 1        | 3.23%   |
| ASUS P8H67-V         | 1        | 3.23%   |
| ASUS M5A78L-M        | 1        | 3.23%   |
| ASUS M4A89GTD-PRO    | 1        | 3.23%   |
| ASUS H110M-PLUS      | 1        | 3.23%   |
| ASUS B150M           | 1        | 3.23%   |
| ASRock N68-S3        | 1        | 3.23%   |
| ASRock J4005B-ITX    | 1        | 3.23%   |
| ASRock H61M-VG4      | 1        | 3.23%   |
| ASRock B450          | 1        | 3.23%   |
| ASRock AB350M        | 1        | 3.23%   |
| ASRock 970           | 1        | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 8        | 25.81%  |
| 2017    | 4        | 12.9%   |
| 2020    | 3        | 9.68%   |
| 2019    | 3        | 9.68%   |
| 2012    | 3        | 9.68%   |
| 2011    | 3        | 9.68%   |
| 2016    | 2        | 6.45%   |
| 2010    | 2        | 6.45%   |
| 2013    | 1        | 3.23%   |
| 2006    | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 31       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 31       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 10       | 32.26%  |
| 16.01-24.0  | 9        | 29.03%  |
| 4.01-8.0    | 4        | 12.9%   |
| 32.01-64.0  | 4        | 12.9%   |
| 3.01-4.0    | 2        | 6.45%   |
| 2.01-3.0    | 1        | 3.23%   |
| 64.01-256.0 | 1        | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 10       | 28.57%  |
| 1.01-2.0   | 6        | 17.14%  |
| 3.01-4.0   | 5        | 14.29%  |
| 0.51-1.0   | 5        | 14.29%  |
| 4.01-8.0   | 4        | 11.43%  |
| 8.01-16.0  | 4        | 11.43%  |
| 16.01-24.0 | 1        | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 38.71%  |
| 3      | 10       | 32.26%  |
| 2      | 8        | 25.81%  |
| 4      | 1        | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 80.65%  |
| Yes       | 6        | 19.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 67.74%  |
| Yes       | 10       | 32.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 81.25%  |
| Yes       | 6        | 18.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 9        | 29.03%  |
| Germany    | 3        | 9.68%   |
| Brazil     | 3        | 9.68%   |
| Russia     | 2        | 6.45%   |
| Czechia    | 2        | 6.45%   |
| UK         | 1        | 3.23%   |
| Turkey     | 1        | 3.23%   |
| Sweden     | 1        | 3.23%   |
| Spain      | 1        | 3.23%   |
| Poland     | 1        | 3.23%   |
| India      | 1        | 3.23%   |
| Greece     | 1        | 3.23%   |
| France     | 1        | 3.23%   |
| Bulgaria   | 1        | 3.23%   |
| Bangladesh | 1        | 3.23%   |
| Australia  | 1        | 3.23%   |
| Argentina  | 1        | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Denver              | 3        | 9.38%   |
| Munich              | 2        | 6.25%   |
| Zagnansk            | 1        | 3.13%   |
| Yekaterinburg       | 1        | 3.13%   |
| Varna               | 1        | 3.13%   |
| Sydney              | 1        | 3.13%   |
| South Shields       | 1        | 3.13%   |
| Saint Paul          | 1        | 3.13%   |
| Rosario             | 1        | 3.13%   |
| Rio de Janeiro      | 1        | 3.13%   |
| Richmond            | 1        | 3.13%   |
| Prague              | 1        | 3.13%   |
| New York            | 1        | 3.13%   |
| Miedziana Gora      | 1        | 3.13%   |
| Kotlas              | 1        | 3.13%   |
| Kolkata             | 1        | 3.13%   |
| Ioannina            | 1        | 3.13%   |
| Huisseau-sur-Cosson | 1        | 3.13%   |
| Horice              | 1        | 3.13%   |
| Gothenburg          | 1        | 3.13%   |
| Elgin               | 1        | 3.13%   |
| Dhaka               | 1        | 3.13%   |
| Denizli             | 1        | 3.13%   |
| Contagem            | 1        | 3.13%   |
| Burgau              | 1        | 3.13%   |
| Blumenau            | 1        | 3.13%   |
| Beaver              | 1        | 3.13%   |
| Allenton            | 1        | 3.13%   |
| Alaraz              | 1        | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 20     | 24.56%  |
| Samsung Electronics | 11       | 18     | 19.3%   |
| Seagate             | 8        | 9      | 14.04%  |
| Kingston            | 6        | 6      | 10.53%  |
| Toshiba             | 3        | 4      | 5.26%   |
| Intel               | 2        | 3      | 3.51%   |
| Corsair             | 2        | 2      | 3.51%   |
| SPCC                | 1        | 1      | 1.75%   |
| SanDisk             | 1        | 1      | 1.75%   |
| Phison              | 1        | 1      | 1.75%   |
| Patriot             | 1        | 1      | 1.75%   |
| OCZ                 | 1        | 1      | 1.75%   |
| MAXTOR              | 1        | 1      | 1.75%   |
| LITEONIT            | 1        | 1      | 1.75%   |
| HGST                | 1        | 1      | 1.75%   |
| Gigabyte Technology | 1        | 1      | 1.75%   |
| Crucial             | 1        | 2      | 1.75%   |
| A-DATA Technology   | 1        | 2      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                 | 3        | 4.62%   |
| Samsung SSD 970 EVO Plus 1TB             | 2        | 3.08%   |
| Kingston SHFS37A120G 120GB SSD           | 2        | 3.08%   |
| Kingston SA400S37240G 240GB SSD          | 2        | 3.08%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 1.54%   |
| WDC WD7500AYYS-01RCA0 752GB              | 1        | 1.54%   |
| WDC WD5000AADS-00S9B0 500GB              | 1        | 1.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 1.54%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1        | 1.54%   |
| WDC WD15EARS-00MVWB0 1TB                 | 1        | 1.54%   |
| WDC WD10JPVX-08JC3T6 1TB                 | 1        | 1.54%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1        | 1.54%   |
| WDC WD10EZRX-00L4HB0 1TB                 | 1        | 1.54%   |
| WDC WD10EFRX-68PJCN0 1TB                 | 1        | 1.54%   |
| WDC WD10EFRX-68FYTN0 1TB                 | 1        | 1.54%   |
| WDC WD10EARX-00PASB0 1TB                 | 1        | 1.54%   |
| WDC WD1002FAEX-00Z3A0 1TB                | 1        | 1.54%   |
| WDC WD1001FALS-00K1B0 1TB                | 1        | 1.54%   |
| Toshiba MQ04ABF100 1TB                   | 1        | 1.54%   |
| Toshiba HDWD110 1TB                      | 1        | 1.54%   |
| Toshiba DT01ACA200 2TB                   | 1        | 1.54%   |
| SPCC Solid State Disk 128GB              | 1        | 1.54%   |
| Seagate ST9500325AS 500GB                | 1        | 1.54%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1.54%   |
| Seagate ST3500413AS 500GB                | 1        | 1.54%   |
| Seagate ST3360320AS 360GB                | 1        | 1.54%   |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1.54%   |
| Seagate ST2000DM006-2DM164 2TB           | 1        | 1.54%   |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1.54%   |
| Seagate ST1000LM035-1RK172 1TB           | 1        | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1.54%   |
| SanDisk Ultra 3D NVMe 500GB              | 1        | 1.54%   |
| Samsung SSD 980 PRO 500GB                | 1        | 1.54%   |
| Samsung SSD 970 EVO Plus 500GB           | 1        | 1.54%   |
| Samsung SSD 970 EVO 500GB                | 1        | 1.54%   |
| Samsung SSD 970 EVO 1TB                  | 1        | 1.54%   |
| Samsung SSD 860 EVO 500GB                | 1        | 1.54%   |
| Samsung SSD 860 EVO 250GB                | 1        | 1.54%   |
| Samsung SSD 850 EVO 500GB                | 1        | 1.54%   |
| Samsung SSD 840 PRO Series 512GB         | 1        | 1.54%   |
| Samsung SSD 750 EVO 500GB                | 1        | 1.54%   |
| Samsung NVMe SSD Drive 500GB             | 1        | 1.54%   |
| Samsung NVMe SSD Drive 1TB               | 1        | 1.54%   |
| Samsung HD322HJ 320GB                    | 1        | 1.54%   |
| Phison NVMe SSD Drive 1TB                | 1        | 1.54%   |
| Patriot Burst 120GB SSD                  | 1        | 1.54%   |
| OCZ AGILITY4 256GB SSD                   | 1        | 1.54%   |
| MAXTOR 7L250S0 256GB                     | 1        | 1.54%   |
| LITEONIT LCS-256L9S-11 2.5 7mm 256GB SSD | 1        | 1.54%   |
| Kingston SUV500MS120G 120GB SSD          | 1        | 1.54%   |
| Kingston SA400S37120G 120GB SSD          | 1        | 1.54%   |
| Intel SSDSC2BW240H6 240GB                | 1        | 1.54%   |
| Intel SSDPEKKW256G8 256GB                | 1        | 1.54%   |
| Intel SSDPEKKW256G7 256GB                | 1        | 1.54%   |
| HGST HTS545050A7E380 500GB               | 1        | 1.54%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD     | 1        | 1.54%   |
| Crucial CT960M500SSD1 960GB              | 1        | 1.54%   |
| Corsair Force MP600 1TB                  | 1        | 1.54%   |
| Corsair CSSD-V128GB2                     | 1        | 1.54%   |
| A-DATA SU700 120GB SSD                   | 1        | 1.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 19     | 48.15%  |
| Seagate             | 8        | 9      | 29.63%  |
| Toshiba             | 3        | 4      | 11.11%  |
| Samsung Electronics | 1        | 1      | 3.7%    |
| MAXTOR              | 1        | 1      | 3.7%    |
| HGST                | 1        | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 6      | 28.57%  |
| Samsung Electronics | 5        | 6      | 23.81%  |
| WDC                 | 1        | 1      | 4.76%   |
| SPCC                | 1        | 1      | 4.76%   |
| Patriot             | 1        | 1      | 4.76%   |
| OCZ                 | 1        | 1      | 4.76%   |
| LITEONIT            | 1        | 1      | 4.76%   |
| Intel               | 1        | 1      | 4.76%   |
| Gigabyte Technology | 1        | 1      | 4.76%   |
| Crucial             | 1        | 2      | 4.76%   |
| Corsair             | 1        | 1      | 4.76%   |
| A-DATA Technology   | 1        | 2      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 35     | 42.86%  |
| SSD  | 19       | 24     | 38.78%  |
| NVMe | 9        | 16     | 18.37%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 59     | 76.32%  |
| NVMe | 9        | 16     | 23.68%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 30     | 53.49%  |
| 0.51-1.0   | 14       | 21     | 32.56%  |
| 1.01-2.0   | 6        | 8      | 13.95%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 21.88%  |
| 251-500        | 6        | 18.75%  |
| 1001-2000      | 4        | 12.5%   |
| 501-1000       | 4        | 12.5%   |
| Unknown        | 4        | 12.5%   |
| More than 3000 | 3        | 9.38%   |
| 2001-3000      | 3        | 9.38%   |
| 1-20           | 1        | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 22.86%  |
| 1-20           | 7        | 20%     |
| 251-500        | 4        | 11.43%  |
| 1001-2000      | 4        | 11.43%  |
| Unknown        | 4        | 11.43%  |
| 501-1000       | 3        | 8.57%   |
| 51-100         | 3        | 8.57%   |
| More than 3000 | 1        | 2.86%   |
| 21-50          | 1        | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB       | 1        | 2      | 14.29%  |
| WDC WD10EZEX-08WN4A0 1TB          | 1        | 1      | 14.29%  |
| Toshiba MQ04ABF100 1TB            | 1        | 2      | 14.29%  |
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
| Toshiba             | 1        | 2      | 14.29%  |
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
| Toshiba             | 1        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 8      | 83.33%  |
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
| Works    | 21       | 40     | 53.85%  |
| Detected | 13       | 26     | 33.33%  |
| Malfunc  | 5        | 9      | 12.82%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 15       | 34.88%  |
| AMD                      | 15       | 34.88%  |
| Samsung Electronics      | 6        | 13.95%  |
| Phison Electronics       | 2        | 4.65%   |
| Sandisk                  | 1        | 2.33%   |
| Nvidia                   | 1        | 2.33%   |
| Marvell Technology Group | 1        | 2.33%   |
| JMicron Technology       | 1        | 2.33%   |
| ASMedia Technology       | 1        | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 7        | 12.73%  |
| AMD 400 Series Chipset SATA Controller                                        | 6        | 10.91%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5        | 9.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 3        | 5.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 3        | 5.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 3        | 5.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 3.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 3.64%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                      | 2        | 3.64%   |
| AMD 300 Series Chipset SATA Controller                                        | 2        | 3.64%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1        | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 1.82%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 1.82%   |
| Phison E12 NVMe Controller                                                    | 1        | 1.82%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 1.82%   |
| Nvidia MCP61 IDE                                                              | 1        | 1.82%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller              | 1        | 1.82%   |
| JMicron JMB361 AHCI/IDE                                                       | 1        | 1.82%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 1        | 1.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1        | 1.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1        | 1.82%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                          | 1        | 1.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1        | 1.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 1        | 1.82%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1        | 1.82%   |
| AMD FCH SATA Controller D                                                     | 1        | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 29       | 65.91%  |
| NVMe | 9        | 20.45%  |
| IDE  | 6        | 13.64%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 16       | 51.61%  |
| Intel                    | 14       | 45.16%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 3.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 3        | 9.68%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2        | 6.45%   |
| AMD FX-4300 Quad-Core Processor                    | 2        | 6.45%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1        | 3.23%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1        | 3.23%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1        | 3.23%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1        | 3.23%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 1        | 3.23%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1        | 3.23%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1        | 3.23%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1        | 3.23%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1        | 3.23%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1        | 3.23%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1        | 3.23%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1        | 3.23%   |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1        | 3.23%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 1        | 3.23%   |
| AMD Ryzen 7 1700X Eight-Core Processor             | 1        | 3.23%   |
| AMD Ryzen 7 1700 Eight-Core Processor              | 1        | 3.23%   |
| AMD Ryzen 5 5600G with Radeon Graphics             | 1        | 3.23%   |
| AMD Ryzen 5 3600 6-Core Processor                  | 1        | 3.23%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 1        | 3.23%   |
| AMD Ryzen 5 1600 Six-Core Processor                | 1        | 3.23%   |
| AMD Ryzen 3 3100 4-Core Processor                  | 1        | 3.23%   |
| AMD Phenom II X4 980 Processor                     | 1        | 3.23%   |
| AMD Athlon II X3 455 Processor                     | 1        | 3.23%   |
| AMD Athlon II X2 280 Processor                     | 1        | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| AMD Ryzen 5        | 7        | 22.58%  |
| Intel Core i5      | 5        | 16.13%  |
| Intel Core i3      | 3        | 9.68%   |
| AMD Ryzen 7        | 3        | 9.68%   |
| AMD FX             | 2        | 6.45%   |
| Other              | 1        | 3.23%   |
| Intel Pentium Gold | 1        | 3.23%   |
| Intel Pentium 4    | 1        | 3.23%   |
| Intel Core i9      | 1        | 3.23%   |
| Intel Core i7      | 1        | 3.23%   |
| Intel Core 2 Duo   | 1        | 3.23%   |
| Intel Celeron      | 1        | 3.23%   |
| AMD Ryzen 3        | 1        | 3.23%   |
| AMD Phenom II X4   | 1        | 3.23%   |
| AMD Athlon II X3   | 1        | 3.23%   |
| AMD Athlon II X2   | 1        | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 29.03%  |
| 2      | 8        | 25.81%  |
| 6      | 7        | 22.58%  |
| 8      | 5        | 16.13%  |
| 3      | 1        | 3.23%   |
| 1      | 1        | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 18       | 58.06%  |
| 1      | 12       | 38.71%  |
| 4      | 1        | 3.23%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 27       | 87.1%   |
| Unknown        | 3        | 9.68%   |
| 32-bit         | 1        | 3.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 34.38%  |
| 0x906e9    | 2        | 6.25%   |
| 0x08701021 | 2        | 6.25%   |
| 0x06000852 | 2        | 6.25%   |
| 0x010000c8 | 2        | 6.25%   |
| 0x906ed    | 1        | 3.13%   |
| 0x906ea    | 1        | 3.13%   |
| 0x706a1    | 1        | 3.13%   |
| 0x506e3    | 1        | 3.13%   |
| 0x306a9    | 1        | 3.13%   |
| 0x1067a    | 1        | 3.13%   |
| 0x0a50000c | 1        | 3.13%   |
| 0x0a201009 | 1        | 3.13%   |
| 0x08701013 | 1        | 3.13%   |
| 0x0800820d | 1        | 3.13%   |
| 0x08001138 | 1        | 3.13%   |
| 0x08001136 | 1        | 3.13%   |
| 0x08001129 | 1        | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 6        | 19.35%  |
| Zen 3         | 4        | 12.9%   |
| Zen           | 3        | 9.68%   |
| K10           | 3        | 9.68%   |
| IvyBridge     | 3        | 9.68%   |
| Zen+          | 2        | 6.45%   |
| Zen 2         | 2        | 6.45%   |
| Piledriver    | 2        | 6.45%   |
| Skylake       | 1        | 3.23%   |
| Penryn        | 1        | 3.23%   |
| NetBurst      | 1        | 3.23%   |
| Haswell       | 1        | 3.23%   |
| Goldmont plus | 1        | 3.23%   |
| Unknown       | 1        | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 15       | 44.12%  |
| AMD               | 13       | 38.24%  |
| Intel             | 5        | 14.71%  |
| ASPEED Technology | 1        | 2.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                               | 3        | 8.57%   |
| Nvidia GM204 [GeForce GTX 970]                                   | 2        | 5.71%   |
| Nvidia GK208B [GeForce GT 710]                                   | 2        | 5.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 2        | 5.71%   |
| Nvidia TU106 [GeForce RTX 2070]                                  | 1        | 2.86%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                            | 1        | 2.86%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                        | 1        | 2.86%   |
| Nvidia GP108 [GeForce GT 1030]                                   | 1        | 2.86%   |
| Nvidia GP107 [GeForce GTX 1050]                                  | 1        | 2.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 1        | 2.86%   |
| Nvidia GK110 [GeForce GTX 780]                                   | 1        | 2.86%   |
| Nvidia GF108 [GeForce GT 420]                                    | 1        | 2.86%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                          | 1        | 2.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 2.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                 | 1        | 2.86%   |
| Intel GeminiLake [UHD Graphics 600]                              | 1        | 2.86%   |
| Intel 82945G/GZ Integrated Graphics Controller                   | 1        | 2.86%   |
| Intel 4 Series Chipset Integrated Graphics Controller            | 1        | 2.86%   |
| ASPEED Technology ASPEED Graphics Family                         | 1        | 2.86%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 1        | 2.86%   |
| AMD Tonga PRO [Radeon R9 285/380]                                | 1        | 2.86%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                | 1        | 2.86%   |
| AMD RS880 [Radeon HD 4290]                                       | 1        | 2.86%   |
| AMD RS780L [Radeon 3000]                                         | 1        | 2.86%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                   | 1        | 2.86%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                     | 1        | 2.86%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                   | 1        | 2.86%   |
| AMD Juniper XT [Radeon HD 6770]                                  | 1        | 2.86%   |
| AMD Cezanne                                                      | 1        | 2.86%   |
| AMD Bonaire [FirePro W5100]                                      | 1        | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 14       | 43.75%  |
| 1 x AMD      | 12       | 37.5%   |
| 1 x Intel    | 4        | 12.5%   |
| 2 x Nvidia   | 1        | 3.13%   |
| AMD + ASPEED | 1        | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 18       | 56.25%  |
| Proprietary | 14       | 43.75%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 31.25%  |
| 3.01-4.0   | 7        | 21.88%  |
| 1.01-2.0   | 6        | 18.75%  |
| 7.01-8.0   | 2        | 6.25%   |
| 2.01-3.0   | 2        | 6.25%   |
| 8.01-16.0  | 2        | 6.25%   |
| 5.01-6.0   | 1        | 3.13%   |
| 0.51-1.0   | 1        | 3.13%   |
| 0.01-0.5   | 1        | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 13.89%  |
| Dell                 | 5        | 13.89%  |
| Hewlett-Packard      | 4        | 11.11%  |
| Acer                 | 4        | 11.11%  |
| Philips              | 3        | 8.33%   |
| Goldstar             | 2        | 5.56%   |
| BenQ                 | 2        | 5.56%   |
| Ancor Communications | 2        | 5.56%   |
| Unknown              | 1        | 2.78%   |
| Sceptre Tech         | 1        | 2.78%   |
| Sceptre              | 1        | 2.78%   |
| ONN                  | 1        | 2.78%   |
| MSI                  | 1        | 2.78%   |
| Lenovo               | 1        | 2.78%   |
| Iiyama               | 1        | 2.78%   |
| FUN                  | 1        | 2.78%   |
| Fujitsu Siemens      | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1        | 2.56%   |
| Sceptre Tech E24 SPT099D 1920x1080 409x230mm 18.5-inch                | 1        | 2.56%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1        | 2.56%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1        | 2.56%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1        | 2.56%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 2.56%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 2.56%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1        | 2.56%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1        | 2.56%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1        | 2.56%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1        | 2.56%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1        | 2.56%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1        | 2.56%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                | 1        | 2.56%   |
| MSI Optix G24C MSI1462 1920x1080 521x293mm 23.5-inch                  | 1        | 2.56%   |
| Lenovo LEN-V5S5/S4-B LEN1201 1920x1080 527x296mm 23.8-inch            | 1        | 2.56%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1        | 2.56%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1        | 2.56%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1        | 2.56%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1        | 2.56%   |
| Hewlett-Packard 21kd HWP3329 1920x1080 458x258mm 20.7-inch            | 1        | 2.56%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 1        | 2.56%   |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1        | 2.56%   |
| FUN HDMI Monitor FUN9D31 3840x2160 480x270mm 21.7-inch                | 1        | 2.56%   |
| Fujitsu Siemens SL27T-1 LED FUS07E4 1920x1080 598x336mm 27.0-inch     | 1        | 2.56%   |
| Dell U3818DW DELA0F4 3840x1600 880x367mm 37.5-inch                    | 1        | 2.56%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                     | 1        | 2.56%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 1        | 2.56%   |
| Dell U2415 DELA0B8 1920x1200 520x320mm 24.0-inch                      | 1        | 2.56%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1        | 2.56%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1        | 2.56%   |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                     | 1        | 2.56%   |
| BenQ GW2470 BNQ78D9 1920x1080 530x300mm 24.0-inch                     | 1        | 2.56%   |
| Ancor Communications VW222 ACI22A2 1680x1050 473x296mm 22.0-inch      | 1        | 2.56%   |
| Ancor Communications LCD Monitor ASUS ML239 1920x1080                 | 1        | 2.56%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 1        | 2.56%   |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                     | 1        | 2.56%   |
| Acer LCD Monitor S181HL 1366x768                                      | 1        | 2.56%   |
| Acer KG251Q ACR0591 1920x1080 544x303mm 24.5-inch                     | 1        | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 51.43%  |
| 1680x1050 (WSXGA+) | 4        | 11.43%  |
| 3840x2160 (4K)     | 2        | 5.71%   |
| 2560x1440 (QHD)    | 2        | 5.71%   |
| 1920x1200 (WUXGA)  | 2        | 5.71%   |
| 1366x768 (WXGA)    | 2        | 5.71%   |
| 7680x1080          | 1        | 2.86%   |
| 3840x1600          | 1        | 2.86%   |
| 3440x1440          | 1        | 2.86%   |
| 1280x1024 (SXGA)   | 1        | 2.86%   |
| Unknown            | 1        | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 21.62%  |
| Unknown | 8        | 21.62%  |
| 21      | 5        | 13.51%  |
| 22      | 4        | 10.81%  |
| 27      | 3        | 8.11%   |
| 23      | 2        | 5.41%   |
| 40      | 1        | 2.7%    |
| 37      | 1        | 2.7%    |
| 34      | 1        | 2.7%    |
| 31      | 1        | 2.7%    |
| 25      | 1        | 2.7%    |
| 20      | 1        | 2.7%    |
| 17      | 1        | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 36.11%  |
| 401-500     | 10       | 27.78%  |
| Unknown     | 8        | 22.22%  |
| 801-900     | 2        | 5.56%   |
| 701-800     | 1        | 2.78%   |
| 601-700     | 1        | 2.78%   |
| 301-350     | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 54.29%  |
| Unknown | 8        | 22.86%  |
| 16/10   | 5        | 14.29%  |
| 21/9    | 2        | 5.71%   |
| 5/4     | 1        | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 38.89%  |
| Unknown        | 8        | 22.22%  |
| 251-300        | 5        | 13.89%  |
| 301-350        | 3        | 8.33%   |
| 351-500        | 2        | 5.56%   |
| 501-1000       | 2        | 5.56%   |
| 151-200        | 1        | 2.78%   |
| 141-150        | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 19       | 51.35%  |
| 101-120 | 9        | 24.32%  |
| Unknown | 8        | 21.62%  |
| 161-240 | 1        | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 81.25%  |
| 2     | 6        | 18.75%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 21       | 47.73%  |
| Intel                           | 10       | 22.73%  |
| TP-Link                         | 2        | 4.55%   |
| Qualcomm Atheros Communications | 2        | 4.55%   |
| Broadcom                        | 2        | 4.55%   |
| Tenda                           | 1        | 2.27%   |
| Ralink Technology               | 1        | 2.27%   |
| Qualcomm Atheros                | 1        | 2.27%   |
| Nvidia                          | 1        | 2.27%   |
| MediaTek                        | 1        | 2.27%   |
| ASIX Electronics                | 1        | 2.27%   |
| Apple                           | 1        | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 40.91%  |
| Intel Ethernet Connection (2) I219-V                              | 3        | 6.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 4.55%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 4.55%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 4.55%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 2.27%   |
| TP-Link 802.11ac NIC                                              | 1        | 2.27%   |
| Tenda U12                                                         | 1        | 2.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 2.27%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.27%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.27%   |
| MediaTek Wiko U316AT                                              | 1        | 2.27%   |
| Intel Ethernet Connection I218-V                                  | 1        | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.27%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 2.27%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 2.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 2.27%   |
| Apple iPad 4/Mini1                                                | 1        | 2.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 30%     |
| TP-Link                         | 2        | 20%     |
| Qualcomm Atheros Communications | 2        | 20%     |
| Tenda                           | 1        | 10%     |
| Realtek Semiconductor           | 1        | 10%     |
| Ralink Technology               | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                 | 2        | 20%     |
| Intel Wi-Fi 6 AX200                             | 2        | 20%     |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]    | 1        | 10%     |
| TP-Link 802.11ac NIC                            | 1        | 10%     |
| Tenda U12                                       | 1        | 10%     |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter | 1        | 10%     |
| Ralink MT7601U Wireless Adapter                 | 1        | 10%     |
| Intel Cannon Lake PCH CNVi WiFi                 | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 58.82%  |
| Intel                 | 7        | 20.59%  |
| Broadcom              | 2        | 5.88%   |
| Qualcomm Atheros      | 1        | 2.94%   |
| Nvidia                | 1        | 2.94%   |
| MediaTek              | 1        | 2.94%   |
| ASIX Electronics      | 1        | 2.94%   |
| Apple                 | 1        | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 52.94%  |
| Intel Ethernet Connection (2) I219-V                              | 3        | 8.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 5.88%   |
| Intel I211 Gigabit Network Connection                             | 2        | 5.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.94%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.94%   |
| MediaTek Wiko U316AT                                              | 1        | 2.94%   |
| Intel Ethernet Connection I218-V                                  | 1        | 2.94%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.94%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 2.94%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 2.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 2.94%   |
| Apple iPad 4/Mini1                                                | 1        | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 75.61%  |
| WiFi     | 10       | 24.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 78.95%  |
| WiFi     | 8        | 21.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 83.87%  |
| 2     | 4        | 12.9%   |
| 3     | 1        | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 90.32%  |
| Yes  | 3        | 9.68%   |

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
| Intel Bluetooth Device                              | 1        | 14.29%  |
| Broadcom BCM2045 Bluetooth                          | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 18       | 31.03%  |
| Nvidia              | 15       | 25.86%  |
| Intel               | 13       | 22.41%  |
| JMTek               | 3        | 5.17%   |
| C-Media Electronics | 3        | 5.17%   |
| Logitech            | 2        | 3.45%   |
| VIA Technologies    | 1        | 1.72%   |
| SAVITECH            | 1        | 1.72%   |
| Elgato Systems      | 1        | 1.72%   |
| Cambridge Audio     | 1        | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 7.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 7.25%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 5.8%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 5.8%    |
| JMTek USB PnP Audio Device                                                 | 3        | 4.35%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 4.35%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 2.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.9%    |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 2        | 2.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.9%    |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 1.45%   |
| SAVITECH SA9023 audio controller                                           | 1        | 1.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.45%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.45%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 1.45%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.45%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.45%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.45%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.45%   |
| Logitech G633 Gaming Headset                                               | 1        | 1.45%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1        | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.45%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.45%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.45%   |
| Elgato Systems Elgato Wave:3                                               | 1        | 1.45%   |
| Cambridge Audio USB Audio 2.0                                              | 1        | 1.45%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.45%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 1.45%   |
| C-Media Electronics Antlion USB adapter                                    | 1        | 1.45%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 1.45%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.45%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 1.45%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 1.45%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.45%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1        | 1.45%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 5        | 23.81%  |
| Corsair             | 4        | 19.05%  |
| Unknown             | 3        | 14.29%  |
| Kingston            | 3        | 14.29%  |
| Crucial             | 2        | 9.52%   |
| A-DATA Technology   | 2        | 9.52%   |
| Samsung Electronics | 1        | 4.76%   |
| Patriot             | 1        | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s   | 2        | 7.69%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                  | 1        | 3.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 3.85%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 3.85%   |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s        | 1        | 3.85%   |
| Patriot RAM PSD48G24002 8192MB DIMM DDR4 2400MT/s          | 1        | 3.85%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s          | 1        | 3.85%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 3.85%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 3.85%   |
| Kingston RAM 9905701-017.A00G 16384MB DIMM DDR4 2666MT/s   | 1        | 3.85%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s       | 1        | 3.85%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s        | 1        | 3.85%   |
| G.Skill RAM F4-2800C17-8GIS 8192MB DIMM DDR4 2800MT/s      | 1        | 3.85%   |
| G.Skill RAM F4-2666C18-4GRS 4096MB SODIMM DDR4 2400MT/s    | 1        | 3.85%   |
| G.Skill RAM F3-10666CL7-2GBRH 2048MB DIMM DDR3 1333MT/s    | 1        | 3.85%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s       | 1        | 3.85%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s       | 1        | 3.85%   |
| Crucial RAM CT16G4DFD824A.M16FJ 16384MB DIMM DDR4 2400MT/s | 1        | 3.85%   |
| Crucial RAM CT16G4DFD824A.M16FD 16GB DIMM DDR4 2400MT/s    | 1        | 3.85%   |
| Crucial RAM BL25664TN1608.16FF 2048MB DIMM DDR3 1333MT/s   | 1        | 3.85%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s        | 1        | 3.85%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s       | 1        | 3.85%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s       | 1        | 3.85%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s                | 1        | 3.85%   |
| A-DATA RAM DDR4 2666 2OZ 16GB DIMM DDR4 3200MT/s           | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 14       | 66.67%  |
| DDR3    | 5        | 23.81%  |
| Unknown | 2        | 9.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 95.24%  |
| SODIMM | 1        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 45.45%  |
| 4096  | 5        | 22.73%  |
| 16384 | 4        | 18.18%  |
| 2048  | 2        | 9.09%   |
| 1024  | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 5        | 20.83%  |
| 1333  | 5        | 20.83%  |
| 3200  | 4        | 16.67%  |
| 3600  | 3        | 12.5%   |
| 3000  | 2        | 8.33%   |
| 2933  | 1        | 4.17%   |
| 2800  | 1        | 4.17%   |
| 2666  | 1        | 4.17%   |
| 1867  | 1        | 4.17%   |
| 1067  | 1        | 4.17%   |

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
| Logitech              | 4        | 33.33%  |
| Microdia              | 2        | 16.67%  |
| MacroSilicon          | 2        | 16.67%  |
| Realtek Semiconductor | 1        | 8.33%   |
| Microsoft             | 1        | 8.33%   |
| GEMBIRD               | 1        | 8.33%   |
| Chicony Electronics   | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek FULL HD 1080P Webcam                      | 1        | 8.33%   |
| Microsoft LifeCam HD-3000                         | 1        | 8.33%   |
| Microdia USB 2.0 Camera                           | 1        | 8.33%   |
| Microdia Camera                                   | 1        | 8.33%   |
| MacroSilicon USB Video                            | 1        | 8.33%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1        | 8.33%   |
| Logitech Webcam C930e                             | 1        | 8.33%   |
| Logitech Webcam C270                              | 1        | 8.33%   |
| Logitech HD Webcam C615                           | 1        | 8.33%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 8.33%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 8.33%   |
| Chicony HP 720p HD Monitor Webcam                 | 1        | 8.33%   |

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
| 0     | 26       | 83.87%  |
| 1     | 3        | 9.68%   |
| 2     | 2        | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Sound         | 2        | 28.57%  |
| Net/wireless  | 2        | 28.57%  |
| Graphics card | 2        | 28.57%  |
| Camera        | 1        | 14.29%  |

