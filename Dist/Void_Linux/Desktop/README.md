Void Linux - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Void Linux.

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

Total: 52

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | ROG STRIX B450-F GAMING     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| ASRock   | X570 Pro4                   | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| ASRock   | TRX40 Taichi                | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| MSI      | B550M PRO                   | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
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

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Void Linux Rolling | 19       | 52.78%  |
| Void Linux         | 17       | 47.22%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Void Linux | 35       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Desktops | Percent |
|-----------|----------|---------|
| 5.8.18_1  | 2        | 5.13%   |
| 5.13.19_1 | 2        | 5.13%   |
| 5.11.9_1  | 2        | 5.13%   |
| 5.10.14_1 | 2        | 5.13%   |
| 5.9.14_1  | 1        | 2.56%   |
| 5.8.5_1   | 1        | 2.56%   |
| 5.8.16_1  | 1        | 2.56%   |
| 5.8.11_1  | 1        | 2.56%   |
| 5.8.10_1  | 1        | 2.56%   |
| 5.6.14_1  | 1        | 2.56%   |
| 5.4.15_1  | 1        | 2.56%   |
| 5.4.13_2  | 1        | 2.56%   |
| 5.3.16_1  | 1        | 2.56%   |
| 5.16.20_1 | 1        | 2.56%   |
| 5.15.34_1 | 1        | 2.56%   |
| 5.15.32_1 | 1        | 2.56%   |
| 5.15.30_1 | 1        | 2.56%   |
| 5.15.22_1 | 1        | 2.56%   |
| 5.15.16_1 | 1        | 2.56%   |
| 5.15.11_1 | 1        | 2.56%   |
| 5.13.15_1 | 1        | 2.56%   |
| 5.13.13_1 | 1        | 2.56%   |
| 5.13.10_1 | 1        | 2.56%   |
| 5.12.14_1 | 1        | 2.56%   |
| 5.12.10_1 | 1        | 2.56%   |
| 5.11.18_1 | 1        | 2.56%   |
| 5.10.8_1  | 1        | 2.56%   |
| 5.10.7_1  | 1        | 2.56%   |
| 5.10.67_1 | 1        | 2.56%   |
| 5.10.3_1  | 1        | 2.56%   |
| 5.10.17_1 | 1        | 2.56%   |
| 4.19.67_1 | 1        | 2.56%   |
| 4.19.66_1 | 1        | 2.56%   |
| 4.19.34_1 | 1        | 2.56%   |
| 4.19.31_1 | 1        | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.18  | 2        | 5.13%   |
| 5.13.19 | 2        | 5.13%   |
| 5.11.9  | 2        | 5.13%   |
| 5.10.14 | 2        | 5.13%   |
| 5.9.14  | 1        | 2.56%   |
| 5.8.5   | 1        | 2.56%   |
| 5.8.16  | 1        | 2.56%   |
| 5.8.11  | 1        | 2.56%   |
| 5.8.10  | 1        | 2.56%   |
| 5.6.14  | 1        | 2.56%   |
| 5.4.15  | 1        | 2.56%   |
| 5.4.13  | 1        | 2.56%   |
| 5.3.16  | 1        | 2.56%   |
| 5.16.20 | 1        | 2.56%   |
| 5.15.34 | 1        | 2.56%   |
| 5.15.32 | 1        | 2.56%   |
| 5.15.30 | 1        | 2.56%   |
| 5.15.22 | 1        | 2.56%   |
| 5.15.16 | 1        | 2.56%   |
| 5.15.11 | 1        | 2.56%   |
| 5.13.15 | 1        | 2.56%   |
| 5.13.13 | 1        | 2.56%   |
| 5.13.10 | 1        | 2.56%   |
| 5.12.14 | 1        | 2.56%   |
| 5.12.10 | 1        | 2.56%   |
| 5.11.18 | 1        | 2.56%   |
| 5.10.8  | 1        | 2.56%   |
| 5.10.7  | 1        | 2.56%   |
| 5.10.67 | 1        | 2.56%   |
| 5.10.3  | 1        | 2.56%   |
| 5.10.17 | 1        | 2.56%   |
| 4.19.67 | 1        | 2.56%   |
| 4.19.66 | 1        | 2.56%   |
| 4.19.34 | 1        | 2.56%   |
| 4.19.31 | 1        | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 7        | 17.95%  |
| 5.8     | 6        | 15.38%  |
| 5.15    | 6        | 15.38%  |
| 5.13    | 5        | 12.82%  |
| 4.19    | 4        | 10.26%  |
| 5.11    | 3        | 7.69%   |
| 5.4     | 2        | 5.13%   |
| 5.12    | 2        | 5.13%   |
| 5.9     | 1        | 2.56%   |
| 5.6     | 1        | 2.56%   |
| 5.3     | 1        | 2.56%   |
| 5.16    | 1        | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 33       | 94.29%  |
| ppc64le | 1        | 2.86%   |
| i686    | 1        | 2.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 52.78%  |
| XFCE       | 4        | 11.11%  |
| GNOME      | 3        | 8.33%   |
| X-Cinnamon | 2        | 5.56%   |
| KDE        | 2        | 5.56%   |
| sway       | 1        | 2.78%   |
| openbox    | 1        | 2.78%   |
| Lumina     | 1        | 2.78%   |
| KDE5       | 1        | 2.78%   |
| bspwm      | 1        | 2.78%   |
| awesome    | 1        | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 26       | 74.29%  |
| Wayland | 4        | 11.43%  |
| Tty     | 3        | 8.57%   |
| Unknown | 2        | 5.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 32       | 91.43%  |
| LightDM | 2        | 5.71%   |
| LXDM    | 1        | 2.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 15       | 40.54%  |
| Unknown | 9        | 24.32%  |
| ru_RU   | 2        | 5.41%   |
| pt_BR   | 1        | 2.7%    |
| pl_PL   | 1        | 2.7%    |
| fr_FR   | 1        | 2.7%    |
| en_IE   | 1        | 2.7%    |
| en_GB   | 1        | 2.7%    |
| en_DK   | 1        | 2.7%    |
| en_AU   | 1        | 2.7%    |
| el_GR   | 1        | 2.7%    |
| de_DE   | 1        | 2.7%    |
| cs_CZ   | 1        | 2.7%    |
| bg_BG   | 1        | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 22       | 61.11%  |
| EFI  | 14       | 38.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 22       | 62.86%  |
| Btrfs   | 6        | 17.14%  |
| Zfs     | 4        | 11.43%  |
| Xfs     | 2        | 5.71%   |
| Unknown | 1        | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 17       | 48.57%  |
| Unknown | 13       | 37.14%  |
| MBR     | 5        | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 88.57%  |
| Yes       | 4        | 11.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 85.71%  |
| Yes       | 5        | 14.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 13       | 37.14%  |
| ASRock              | 8        | 22.86%  |
| MSI                 | 6        | 17.14%  |
| Gigabyte Technology | 4        | 11.43%  |
| Dell                | 2        | 5.71%   |
| Unknown             | 2        | 5.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS PRIME Z390-P            | 2        | 5.71%   |
| Unknown                      | 2        | 5.71%   |
| MSI MS-7D14                  | 1        | 2.86%   |
| MSI MS-7C92                  | 1        | 2.86%   |
| MSI MS-7C52                  | 1        | 2.86%   |
| MSI MS-7C02                  | 1        | 2.86%   |
| MSI MS-7A68                  | 1        | 2.86%   |
| MSI MS-7A39                  | 1        | 2.86%   |
| Gigabyte H310M M.2 2.0       | 1        | 2.86%   |
| Gigabyte GA-78LMT-S2         | 1        | 2.86%   |
| Gigabyte B550M AORUS PRO-P   | 1        | 2.86%   |
| Gigabyte B450M DS3H          | 1        | 2.86%   |
| Dell OptiPlex GX520          | 1        | 2.86%   |
| Dell OptiPlex 780            | 1        | 2.86%   |
| ASUS ROG STRIX B450-F GAMING | 1        | 2.86%   |
| ASUS ROG CROSSHAIR VII HERO  | 1        | 2.86%   |
| ASUS PRIME Z270-AR           | 1        | 2.86%   |
| ASUS PRIME X470-PRO          | 1        | 2.86%   |
| ASUS PRIME A320M-K/BR        | 1        | 2.86%   |
| ASUS P8Z77-V LX2             | 1        | 2.86%   |
| ASUS P8H67-V                 | 1        | 2.86%   |
| ASUS M5A78L-M LX             | 1        | 2.86%   |
| ASUS M4A89GTD-PRO/USB3       | 1        | 2.86%   |
| ASUS H110M-PLUS              | 1        | 2.86%   |
| ASUS B150M PRO GAMING        | 1        | 2.86%   |
| ASRock X570 Pro4             | 1        | 2.86%   |
| ASRock TRX40 Taichi          | 1        | 2.86%   |
| ASRock N68-S3 FX             | 1        | 2.86%   |
| ASRock J4005B-ITX            | 1        | 2.86%   |
| ASRock H61M-VG4              | 1        | 2.86%   |
| ASRock B450 Pro4             | 1        | 2.86%   |
| ASRock AB350M                | 1        | 2.86%   |
| ASRock 970 Pro3 R2.0         | 1        | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 5        | 14.29%  |
| Dell OptiPlex        | 2        | 5.71%   |
| ASUS ROG             | 2        | 5.71%   |
| Unknown              | 2        | 5.71%   |
| MSI MS-7D14          | 1        | 2.86%   |
| MSI MS-7C92          | 1        | 2.86%   |
| MSI MS-7C52          | 1        | 2.86%   |
| MSI MS-7C02          | 1        | 2.86%   |
| MSI MS-7A68          | 1        | 2.86%   |
| MSI MS-7A39          | 1        | 2.86%   |
| Gigabyte H310M       | 1        | 2.86%   |
| Gigabyte GA-78LMT-S2 | 1        | 2.86%   |
| Gigabyte B550M       | 1        | 2.86%   |
| Gigabyte B450M       | 1        | 2.86%   |
| ASUS P8Z77-V         | 1        | 2.86%   |
| ASUS P8H67-V         | 1        | 2.86%   |
| ASUS M5A78L-M        | 1        | 2.86%   |
| ASUS M4A89GTD-PRO    | 1        | 2.86%   |
| ASUS H110M-PLUS      | 1        | 2.86%   |
| ASUS B150M           | 1        | 2.86%   |
| ASRock X570          | 1        | 2.86%   |
| ASRock TRX40         | 1        | 2.86%   |
| ASRock N68-S3        | 1        | 2.86%   |
| ASRock J4005B-ITX    | 1        | 2.86%   |
| ASRock H61M-VG4      | 1        | 2.86%   |
| ASRock B450          | 1        | 2.86%   |
| ASRock AB350M        | 1        | 2.86%   |
| ASRock 970           | 1        | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 9        | 25.71%  |
| 2020    | 5        | 14.29%  |
| 2019    | 4        | 11.43%  |
| 2017    | 4        | 11.43%  |
| 2012    | 3        | 8.57%   |
| 2010    | 3        | 8.57%   |
| 2016    | 2        | 5.71%   |
| 2011    | 2        | 5.71%   |
| 2013    | 1        | 2.86%   |
| 2006    | 1        | 2.86%   |
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
| 16.01-24.0      | 11       | 31.43%  |
| 8.01-16.0       | 10       | 28.57%  |
| 32.01-64.0      | 5        | 14.29%  |
| 4.01-8.0        | 4        | 11.43%  |
| 3.01-4.0        | 2        | 5.71%   |
| More than 256.0 | 1        | 2.86%   |
| 2.01-3.0        | 1        | 2.86%   |
| 64.01-256.0     | 1        | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 10       | 25.64%  |
| 1.01-2.0    | 6        | 15.38%  |
| 8.01-16.0   | 6        | 15.38%  |
| 4.01-8.0    | 5        | 12.82%  |
| 3.01-4.0    | 5        | 12.82%  |
| 0.51-1.0    | 5        | 12.82%  |
| 64.01-256.0 | 1        | 2.56%   |
| 16.01-24.0  | 1        | 2.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 12       | 34.29%  |
| 1      | 12       | 34.29%  |
| 2      | 9        | 25.71%  |
| 9      | 1        | 2.86%   |
| 4      | 1        | 2.86%   |

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
| Yes       | 35       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 65.71%  |
| Yes       | 12       | 34.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 77.78%  |
| Yes       | 8        | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 10       | 28.57%  |
| Germany    | 3        | 8.57%   |
| Czechia    | 3        | 8.57%   |
| Brazil     | 3        | 8.57%   |
| Russia     | 2        | 5.71%   |
| Poland     | 2        | 5.71%   |
| UK         | 1        | 2.86%   |
| Turkey     | 1        | 2.86%   |
| Sweden     | 1        | 2.86%   |
| Spain      | 1        | 2.86%   |
| India      | 1        | 2.86%   |
| Greece     | 1        | 2.86%   |
| France     | 1        | 2.86%   |
| Bulgaria   | 1        | 2.86%   |
| Belgium    | 1        | 2.86%   |
| Bangladesh | 1        | 2.86%   |
| Australia  | 1        | 2.86%   |
| Argentina  | 1        | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Denver              | 3        | 8.33%   |
| Prague              | 2        | 5.56%   |
| Munich              | 2        | 5.56%   |
| Zagnansk            | 1        | 2.78%   |
| Yekaterinburg       | 1        | 2.78%   |
| Varna               | 1        | 2.78%   |
| Sydney              | 1        | 2.78%   |
| South Shields       | 1        | 2.78%   |
| Saint Paul          | 1        | 2.78%   |
| Rosario             | 1        | 2.78%   |
| Rio de Janeiro      | 1        | 2.78%   |
| Richmond            | 1        | 2.78%   |
| New York            | 1        | 2.78%   |
| Miedziana Gora      | 1        | 2.78%   |
| Lublin              | 1        | 2.78%   |
| Kotlas              | 1        | 2.78%   |
| Kolkata             | 1        | 2.78%   |
| Ioannina            | 1        | 2.78%   |
| Huisseau-sur-Cosson | 1        | 2.78%   |
| Horice              | 1        | 2.78%   |
| Gothenburg          | 1        | 2.78%   |
| Elgin               | 1        | 2.78%   |
| Dhaka               | 1        | 2.78%   |
| Denizli             | 1        | 2.78%   |
| Contagem            | 1        | 2.78%   |
| Burgau              | 1        | 2.78%   |
| Brussels            | 1        | 2.78%   |
| Blumenau            | 1        | 2.78%   |
| Beaver              | 1        | 2.78%   |
| Amsterdam           | 1        | 2.78%   |
| Allenton            | 1        | 2.78%   |
| Alaraz              | 1        | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 22     | 23.88%  |
| Samsung Electronics | 12       | 22     | 17.91%  |
| Seagate             | 10       | 12     | 14.93%  |
| Kingston            | 6        | 6      | 8.96%   |
| Toshiba             | 3        | 4      | 4.48%   |
| SanDisk             | 2        | 2      | 2.99%   |
| Intel               | 2        | 3      | 2.99%   |
| Crucial             | 2        | 3      | 2.99%   |
| Corsair             | 2        | 2      | 2.99%   |
| A-DATA Technology   | 2        | 3      | 2.99%   |
| XPG                 | 1        | 4      | 1.49%   |
| SPCC                | 1        | 1      | 1.49%   |
| Phison              | 1        | 1      | 1.49%   |
| Patriot             | 1        | 1      | 1.49%   |
| OCZ                 | 1        | 1      | 1.49%   |
| MAXTOR              | 1        | 1      | 1.49%   |
| LITEONIT            | 1        | 1      | 1.49%   |
| Hitachi             | 1        | 1      | 1.49%   |
| HGST                | 1        | 1      | 1.49%   |
| Gigabyte Technology | 1        | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                 | 3        | 3.9%    |
| Seagate ST2000DM008-2FR102 2TB           | 2        | 2.6%    |
| Seagate ST1000DM010-2EP102 1TB           | 2        | 2.6%    |
| Samsung SSD 970 EVO Plus 1TB             | 2        | 2.6%    |
| Samsung NVMe SSD Drive 500GB             | 2        | 2.6%    |
| Kingston SHFS37A120G 120GB SSD           | 2        | 2.6%    |
| Kingston SA400S37240G 240GB SSD          | 2        | 2.6%    |
| XPG NVMe SSD Drive 2TB                   | 1        | 1.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 1.3%    |
| WDC WD7500AYYS-01RCA0 752GB              | 1        | 1.3%    |
| WDC WD5000AADS-00S9B0 500GB              | 1        | 1.3%    |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 1.3%    |
| WDC WD20EZBX-00AYRA0 2TB                 | 1        | 1.3%    |
| WDC WD20EFRX-68EUZN0 2TB                 | 1        | 1.3%    |
| WDC WD2003FZEX-00Z4SA0 2TB               | 1        | 1.3%    |
| WDC WD15EARS-00MVWB0 1TB                 | 1        | 1.3%    |
| WDC WD10JPVX-08JC3T6 1TB                 | 1        | 1.3%    |
| WDC WD10JPCX-24UE4T0 1TB                 | 1        | 1.3%    |
| WDC WD10EZRX-00L4HB0 1TB                 | 1        | 1.3%    |
| WDC WD10EFRX-68PJCN0 1TB                 | 1        | 1.3%    |
| WDC WD10EFRX-68FYTN0 1TB                 | 1        | 1.3%    |
| WDC WD10EARX-00PASB0 1TB                 | 1        | 1.3%    |
| WDC WD1002FAEX-00Z3A0 1TB                | 1        | 1.3%    |
| WDC WD1001FALS-00K1B0 1TB                | 1        | 1.3%    |
| Toshiba MQ04ABF100 1TB                   | 1        | 1.3%    |
| Toshiba HDWD110 1TB                      | 1        | 1.3%    |
| Toshiba DT01ACA200 2TB                   | 1        | 1.3%    |
| SPCC Solid State Disk 128GB              | 1        | 1.3%    |
| Seagate ST9500325AS 500GB                | 1        | 1.3%    |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1.3%    |
| Seagate ST3500413AS 500GB                | 1        | 1.3%    |
| Seagate ST3360320AS 360GB                | 1        | 1.3%    |
| Seagate ST2000VX000-1CU164 2TB           | 1        | 1.3%    |
| Seagate ST2000DM006-2DM164 2TB           | 1        | 1.3%    |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1.3%    |
| Seagate ST1000LM035-1RK172 1TB           | 1        | 1.3%    |
| SanDisk Ultra II 960GB SSD               | 1        | 1.3%    |
| SanDisk Ultra 3D NVMe 1TB                | 1        | 1.3%    |
| Samsung SSD 980 PRO 500GB                | 1        | 1.3%    |
| Samsung SSD 970 EVO Plus 500GB           | 1        | 1.3%    |
| Samsung SSD 970 EVO 500GB                | 1        | 1.3%    |
| Samsung SSD 970 EVO 1TB                  | 1        | 1.3%    |
| Samsung SSD 860 EVO 500GB                | 1        | 1.3%    |
| Samsung SSD 860 EVO 4TB                  | 1        | 1.3%    |
| Samsung SSD 860 EVO 250GB                | 1        | 1.3%    |
| Samsung SSD 850 EVO 500GB                | 1        | 1.3%    |
| Samsung SSD 840 PRO Series 512GB         | 1        | 1.3%    |
| Samsung SSD 750 EVO 500GB                | 1        | 1.3%    |
| Samsung NVMe SSD Drive 1TB               | 1        | 1.3%    |
| Samsung HD322HJ 320GB                    | 1        | 1.3%    |
| Phison NVMe SSD Drive 1TB                | 1        | 1.3%    |
| Patriot Burst 120GB SSD                  | 1        | 1.3%    |
| OCZ AGILITY4 256GB SSD                   | 1        | 1.3%    |
| MAXTOR 7L250S0 256GB                     | 1        | 1.3%    |
| LITEONIT LCS-256L9S-11 2.5 7mm 256GB SSD | 1        | 1.3%    |
| Kingston SUV500MS120G 120GB SSD          | 1        | 1.3%    |
| Kingston SA400S37120G 120GB SSD          | 1        | 1.3%    |
| Intel SSDSC2BW240H6 240GB                | 1        | 1.3%    |
| Intel SSDPEKKW256G8 256GB                | 1        | 1.3%    |
| Intel NVMe SSD Drive 256GB               | 1        | 1.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 21     | 46.88%  |
| Seagate             | 10       | 12     | 31.25%  |
| Toshiba             | 3        | 4      | 9.38%   |
| Samsung Electronics | 1        | 1      | 3.13%   |
| MAXTOR              | 1        | 1      | 3.13%   |
| Hitachi             | 1        | 1      | 3.13%   |
| HGST                | 1        | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 26.09%  |
| Kingston            | 6        | 6      | 26.09%  |
| WDC                 | 1        | 1      | 4.35%   |
| SPCC                | 1        | 1      | 4.35%   |
| SanDisk             | 1        | 1      | 4.35%   |
| Patriot             | 1        | 1      | 4.35%   |
| OCZ                 | 1        | 1      | 4.35%   |
| LITEONIT            | 1        | 1      | 4.35%   |
| Intel               | 1        | 1      | 4.35%   |
| Gigabyte Technology | 1        | 1      | 4.35%   |
| Crucial             | 1        | 2      | 4.35%   |
| Corsair             | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 2      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 41     | 42.86%  |
| SSD  | 20       | 27     | 35.71%  |
| NVMe | 12       | 24     | 21.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 33       | 68     | 73.33%  |
| NVMe | 12       | 24     | 26.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 31     | 48%     |
| 0.51-1.0   | 16       | 23     | 32%     |
| 1.01-2.0   | 9        | 12     | 18%     |
| 3.01-4.0   | 1        | 2      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 7        | 19.44%  |
| 101-250        | 7        | 19.44%  |
| 1001-2000      | 6        | 16.67%  |
| More than 3000 | 4        | 11.11%  |
| 501-1000       | 4        | 11.11%  |
| Unknown        | 4        | 11.11%  |
| 2001-3000      | 3        | 8.33%   |
| 1-20           | 1        | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 20.51%  |
| 1-20           | 8        | 20.51%  |
| 251-500        | 5        | 12.82%  |
| 1001-2000      | 4        | 10.26%  |
| 501-1000       | 4        | 10.26%  |
| Unknown        | 4        | 10.26%  |
| 51-100         | 3        | 7.69%   |
| More than 3000 | 1        | 2.56%   |
| 21-50          | 1        | 2.56%   |
| 2001-3000      | 1        | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB       | 1        | 2      | 10%     |
| WDC WD2003FZEX-00Z4SA0 2TB        | 1        | 1      | 10%     |
| WDC WD10EZEX-08WN4A0 1TB          | 1        | 1      | 10%     |
| Toshiba MQ04ABF100 1TB            | 1        | 2      | 10%     |
| Seagate ST9500325AS 500GB         | 1        | 1      | 10%     |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 10%     |
| Seagate ST2000VX000-1CU164 2TB    | 1        | 1      | 10%     |
| Samsung Electronics HD322HJ 320GB | 1        | 1      | 10%     |
| Hitachi HTS545050B9A300 500GB     | 1        | 1      | 10%     |
| A-DATA Technology SU700 120GB SSD | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 4      | 30%     |
| Seagate             | 3        | 3      | 30%     |
| Toshiba             | 1        | 2      | 10%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Hitachi             | 1        | 1      | 10%     |
| A-DATA Technology   | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 4      | 33.33%  |
| Seagate             | 3        | 3      | 33.33%  |
| Toshiba             | 1        | 2      | 11.11%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 11     | 88.89%  |
| SSD  | 1        | 1      | 11.11%  |

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
| Works    | 24       | 45     | 52.17%  |
| Detected | 14       | 35     | 30.43%  |
| Malfunc  | 8        | 12     | 17.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 19       | 37.25%  |
| Intel                     | 15       | 29.41%  |
| Samsung Electronics       | 7        | 13.73%  |
| Phison Electronics        | 2        | 3.92%   |
| ADATA Technology          | 2        | 3.92%   |
| Sandisk                   | 1        | 1.96%   |
| Nvidia                    | 1        | 1.96%   |
| Micron/Crucial Technology | 1        | 1.96%   |
| Marvell Technology Group  | 1        | 1.96%   |
| JMicron Technology        | 1        | 1.96%   |
| ASMedia Technology        | 1        | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 10       | 15.63%  |
| AMD 400 Series Chipset SATA Controller                                        | 7        | 10.94%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 6        | 9.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 3        | 4.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 3        | 4.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 3        | 4.69%   |
| AMD 500 Series Chipset SATA Controller                                        | 3        | 4.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 3.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 3.13%   |
| AMD 300 Series Chipset SATA Controller                                        | 2        | 3.13%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 2        | 3.13%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1        | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 1.56%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 1.56%   |
| Phison E12 NVMe Controller                                                    | 1        | 1.56%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 1.56%   |
| Nvidia MCP61 IDE                                                              | 1        | 1.56%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1        | 1.56%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller              | 1        | 1.56%   |
| JMicron JMB361 AHCI/IDE                                                       | 1        | 1.56%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 1        | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1        | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1        | 1.56%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                          | 1        | 1.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1        | 1.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 1        | 1.56%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1        | 1.56%   |
| AMD FCH SATA Controller D                                                     | 1        | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 33       | 64.71%  |
| NVMe | 12       | 23.53%  |
| IDE  | 6        | 11.76%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 20       | 57.14%  |
| Intel                    | 14       | 40%     |
| PowerNV C1P9S01 REV 1.01 | 1        | 2.86%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4        | 11.43%  |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2        | 5.71%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2        | 5.71%   |
| AMD FX-4300 Quad-Core Processor                    | 2        | 5.71%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1        | 2.86%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1        | 2.86%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1        | 2.86%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1        | 2.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 1        | 2.86%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1        | 2.86%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1        | 2.86%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1        | 2.86%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1        | 2.86%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1        | 2.86%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1        | 2.86%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1        | 2.86%   |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1        | 2.86%   |
| AMD Ryzen Threadripper 3990X 64-Core Processor     | 1        | 2.86%   |
| AMD Ryzen 7 5800X 8-Core Processor                 | 1        | 2.86%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 1        | 2.86%   |
| AMD Ryzen 7 1700X Eight-Core Processor             | 1        | 2.86%   |
| AMD Ryzen 7 1700 Eight-Core Processor              | 1        | 2.86%   |
| AMD Ryzen 5 5600G with Radeon Graphics             | 1        | 2.86%   |
| AMD Ryzen 5 3600 6-Core Processor                  | 1        | 2.86%   |
| AMD Ryzen 5 1600 Six-Core Processor                | 1        | 2.86%   |
| AMD Ryzen 3 3100 4-Core Processor                  | 1        | 2.86%   |
| AMD Phenom II X4 980 Processor                     | 1        | 2.86%   |
| AMD Athlon II X3 455 Processor                     | 1        | 2.86%   |
| AMD Athlon II X2 280 Processor                     | 1        | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 9        | 25.71%  |
| Intel Core i5          | 5        | 14.29%  |
| AMD Ryzen 7            | 4        | 11.43%  |
| Intel Core i3          | 3        | 8.57%   |
| AMD FX                 | 2        | 5.71%   |
| Other                  | 1        | 2.86%   |
| Intel Pentium Gold     | 1        | 2.86%   |
| Intel Pentium 4        | 1        | 2.86%   |
| Intel Core i9          | 1        | 2.86%   |
| Intel Core i7          | 1        | 2.86%   |
| Intel Core 2 Duo       | 1        | 2.86%   |
| Intel Celeron          | 1        | 2.86%   |
| AMD Ryzen Threadripper | 1        | 2.86%   |
| AMD Ryzen 3            | 1        | 2.86%   |
| AMD Phenom II X4       | 1        | 2.86%   |
| AMD Athlon II X3       | 1        | 2.86%   |
| AMD Athlon II X2       | 1        | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 9        | 25.71%  |
| 4      | 9        | 25.71%  |
| 2      | 8        | 22.86%  |
| 8      | 6        | 17.14%  |
| 64     | 1        | 2.86%   |
| 3      | 1        | 2.86%   |
| 1      | 1        | 2.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 62.86%  |
| 1      | 12       | 34.29%  |
| 4      | 1        | 2.86%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 31       | 88.57%  |
| Unknown        | 3        | 8.57%   |
| 32-bit         | 1        | 2.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 33.33%  |
| 0x906e9    | 2        | 5.56%   |
| 0x0a201009 | 2        | 5.56%   |
| 0x08701021 | 2        | 5.56%   |
| 0x0800820d | 2        | 5.56%   |
| 0x06000852 | 2        | 5.56%   |
| 0x010000c8 | 2        | 5.56%   |
| 0x906ed    | 1        | 2.78%   |
| 0x906ea    | 1        | 2.78%   |
| 0x706a1    | 1        | 2.78%   |
| 0x506e3    | 1        | 2.78%   |
| 0x306a9    | 1        | 2.78%   |
| 0x1067a    | 1        | 2.78%   |
| 0x0a50000c | 1        | 2.78%   |
| 0x0a201205 | 1        | 2.78%   |
| 0x08701013 | 1        | 2.78%   |
| 0x08001138 | 1        | 2.78%   |
| 0x08001136 | 1        | 2.78%   |
| 0x08001129 | 1        | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 3         | 6        | 17.14%  |
| KabyLake      | 6        | 17.14%  |
| Zen+          | 3        | 8.57%   |
| Zen 2         | 3        | 8.57%   |
| Zen           | 3        | 8.57%   |
| K10           | 3        | 8.57%   |
| IvyBridge     | 3        | 8.57%   |
| Piledriver    | 2        | 5.71%   |
| Skylake       | 1        | 2.86%   |
| Penryn        | 1        | 2.86%   |
| NetBurst      | 1        | 2.86%   |
| Haswell       | 1        | 2.86%   |
| Goldmont plus | 1        | 2.86%   |
| Unknown       | 1        | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 17       | 44.74%  |
| AMD               | 15       | 39.47%  |
| Intel             | 5        | 13.16%  |
| ASPEED Technology | 1        | 2.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                               | 4        | 10.26%  |
| Nvidia GM204 [GeForce GTX 970]                                   | 2        | 5.13%   |
| Nvidia GK208B [GeForce GT 710]                                   | 2        | 5.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 2        | 5.13%   |
| Nvidia TU106 [GeForce RTX 2070]                                  | 1        | 2.56%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                            | 1        | 2.56%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                        | 1        | 2.56%   |
| Nvidia GP108 [GeForce GT 1030]                                   | 1        | 2.56%   |
| Nvidia GP107 [GeForce GTX 1050]                                  | 1        | 2.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 1        | 2.56%   |
| Nvidia GK110 [GeForce GTX 780]                                   | 1        | 2.56%   |
| Nvidia GF108 [GeForce GT 420]                                    | 1        | 2.56%   |
| Nvidia GA102 [GeForce RTX 3090]                                  | 1        | 2.56%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                          | 1        | 2.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                 | 1        | 2.56%   |
| Intel GeminiLake [UHD Graphics 600]                              | 1        | 2.56%   |
| Intel 82945G/GZ Integrated Graphics Controller                   | 1        | 2.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller            | 1        | 2.56%   |
| ASPEED Technology ASPEED Graphics Family                         | 1        | 2.56%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 1        | 2.56%   |
| AMD Tonga PRO [Radeon R9 285/380]                                | 1        | 2.56%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                | 1        | 2.56%   |
| AMD RS880 [Radeon HD 4290]                                       | 1        | 2.56%   |
| AMD RS780L [Radeon 3000]                                         | 1        | 2.56%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                   | 1        | 2.56%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]             | 1        | 2.56%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                   | 1        | 2.56%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 1        | 2.56%   |
| AMD Juniper XT [Radeon HD 6770]                                  | 1        | 2.56%   |
| AMD Cezanne                                                      | 1        | 2.56%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]               | 1        | 2.56%   |
| AMD Bonaire [FirePro W5100]                                      | 1        | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 16       | 44.44%  |
| 1 x AMD      | 14       | 38.89%  |
| 1 x Intel    | 4        | 11.11%  |
| 2 x Nvidia   | 1        | 2.78%   |
| AMD + ASPEED | 1        | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 55.56%  |
| Proprietary | 16       | 44.44%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 27.78%  |
| 3.01-4.0   | 8        | 22.22%  |
| 1.01-2.0   | 7        | 19.44%  |
| 7.01-8.0   | 2        | 5.56%   |
| 5.01-6.0   | 2        | 5.56%   |
| 2.01-3.0   | 2        | 5.56%   |
| 8.01-16.0  | 2        | 5.56%   |
| 16.01-24.0 | 1        | 2.78%   |
| 0.51-1.0   | 1        | 2.78%   |
| 0.01-0.5   | 1        | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Hewlett-Packard      | 6        | 15%     |
| Dell                 | 6        | 15%     |
| Samsung Electronics  | 5        | 12.5%   |
| Acer                 | 4        | 10%     |
| Philips              | 3        | 7.5%    |
| Iiyama               | 2        | 5%      |
| Goldstar             | 2        | 5%      |
| BenQ                 | 2        | 5%      |
| Ancor Communications | 2        | 5%      |
| Unknown              | 1        | 2.5%    |
| Sceptre Tech         | 1        | 2.5%    |
| Sceptre              | 1        | 2.5%    |
| ONN                  | 1        | 2.5%    |
| MSI                  | 1        | 2.5%    |
| Lenovo               | 1        | 2.5%    |
| FUN                  | 1        | 2.5%    |
| Fujitsu Siemens      | 1        | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1        | 2.27%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1        | 2.27%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1        | 2.27%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1        | 2.27%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1        | 2.27%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1        | 2.27%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1        | 2.27%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1        | 2.27%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1        | 2.27%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1        | 2.27%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1        | 2.27%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1        | 2.27%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 1        | 2.27%   |
| Lenovo LEN-22ICB-C LEN1201 1920x1080 476x268mm 21.5-inch              | 1        | 2.27%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 1        | 2.27%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1        | 2.27%   |
| Iiyama PL2473HD IVM6107 1920x1080 520x290mm 23.4-inch                 | 1        | 2.27%   |
| Hewlett-Packard Z24i G2 HPN3481 1920x1200 518x324mm 24.1-inch         | 1        | 2.27%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 1        | 2.27%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1        | 2.27%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1        | 2.27%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1        | 2.27%   |
| Hewlett-Packard 21kd HWP3329 1920x1080 458x258mm 20.7-inch            | 1        | 2.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 2.27%   |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1        | 2.27%   |
| FUN HDMI Monitor FUN9D31 3840x2160 480x270mm 21.7-inch                | 1        | 2.27%   |
| Fujitsu Siemens SL27T-1 LED FUS07E4 1920x1080 598x336mm 27.0-inch     | 1        | 2.27%   |
| Dell U3818DW DELA0F4 3840x1600 880x367mm 37.5-inch                    | 1        | 2.27%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                     | 1        | 2.27%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 1        | 2.27%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 1        | 2.27%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1        | 2.27%   |
| Dell LCD Monitor U2515H                                               | 1        | 2.27%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1        | 2.27%   |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                     | 1        | 2.27%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 1        | 2.27%   |
| Ancor Communications VW222 ACI22A2 1680x1050 473x296mm 22.0-inch      | 1        | 2.27%   |
| Ancor Communications LCD Monitor ASUS ML239 1920x1080                 | 1        | 2.27%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 1        | 2.27%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 1        | 2.27%   |
| Acer LCD Monitor S181HL 1366x768                                      | 1        | 2.27%   |
| Acer KG251Q ACR0591 1920x1080 544x303mm 24.5-inch                     | 1        | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 20       | 50%     |
| 1680x1050 (WSXGA+) | 4        | 10%     |
| 1920x1200 (WUXGA)  | 3        | 7.5%    |
| 3840x2160 (4K)     | 2        | 5%      |
| 3440x1440          | 2        | 5%      |
| 2560x1440 (QHD)    | 2        | 5%      |
| 1366x768 (WXGA)    | 2        | 5%      |
| Unknown            | 2        | 5%      |
| 7680x1080          | 1        | 2.5%    |
| 3840x1600          | 1        | 2.5%    |
| 1280x1024 (SXGA)   | 1        | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 10       | 23.81%  |
| Unknown | 9        | 21.43%  |
| 21      | 5        | 11.9%   |
| 22      | 4        | 9.52%   |
| 27      | 3        | 7.14%   |
| 23      | 3        | 7.14%   |
| 34      | 2        | 4.76%   |
| 40      | 1        | 2.38%   |
| 37      | 1        | 2.38%   |
| 31      | 1        | 2.38%   |
| 25      | 1        | 2.38%   |
| 20      | 1        | 2.38%   |
| 17      | 1        | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 39.02%  |
| 401-500     | 10       | 24.39%  |
| Unknown     | 9        | 21.95%  |
| 801-900     | 2        | 4.88%   |
| 701-800     | 2        | 4.88%   |
| 601-700     | 1        | 2.44%   |
| 301-350     | 1        | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 20       | 50%     |
| Unknown | 9        | 22.5%   |
| 16/10   | 7        | 17.5%   |
| 21/9    | 3        | 7.5%    |
| 5/4     | 1        | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 36.59%  |
| Unknown        | 9        | 21.95%  |
| 251-300        | 7        | 17.07%  |
| 351-500        | 3        | 7.32%   |
| 301-350        | 3        | 7.32%   |
| 501-1000       | 2        | 4.88%   |
| 151-200        | 1        | 2.44%   |
| 141-150        | 1        | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 52.38%  |
| 101-120 | 10       | 23.81%  |
| Unknown | 9        | 21.43%  |
| 161-240 | 1        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 80.56%  |
| 2     | 7        | 19.44%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 23       | 46%     |
| Intel                           | 13       | 26%     |
| TP-Link                         | 2        | 4%      |
| Ralink Technology               | 2        | 4%      |
| Qualcomm Atheros Communications | 2        | 4%      |
| Broadcom                        | 2        | 4%      |
| Tenda                           | 1        | 2%      |
| Qualcomm Atheros                | 1        | 2%      |
| Nvidia                          | 1        | 2%      |
| MediaTek                        | 1        | 2%      |
| ASIX Electronics                | 1        | 2%      |
| Apple                           | 1        | 2%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 37.25%  |
| Intel I211 Gigabit Network Connection                             | 5        | 9.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 5.88%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 5.88%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 5.88%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 3.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.96%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 1.96%   |
| Tenda U12                                                         | 1        | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 1.96%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 1.96%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.96%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.96%   |
| MediaTek NOA N2                                                   | 1        | 1.96%   |
| Intel Ethernet Connection I218-V                                  | 1        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 1.96%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.96%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.96%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 1.96%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.96%   |
| Apple iPad 4/Mini1                                                | 1        | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 33.33%  |
| TP-Link                         | 2        | 16.67%  |
| Ralink Technology               | 2        | 16.67%  |
| Qualcomm Atheros Communications | 2        | 16.67%  |
| Tenda                           | 1        | 8.33%   |
| Realtek Semiconductor           | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                             | 3        | 25%     |
| Qualcomm Atheros AR9271 802.11n                 | 2        | 16.67%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]    | 1        | 8.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]          | 1        | 8.33%   |
| Tenda U12                                       | 1        | 8.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter | 1        | 8.33%   |
| Ralink RT5572 Wireless Adapter                  | 1        | 8.33%   |
| Ralink MT7601U Wireless Adapter                 | 1        | 8.33%   |
| Intel Cannon Lake PCH CNVi WiFi                 | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 56.41%  |
| Intel                 | 10       | 25.64%  |
| Broadcom              | 2        | 5.13%   |
| Qualcomm Atheros      | 1        | 2.56%   |
| Nvidia                | 1        | 2.56%   |
| MediaTek              | 1        | 2.56%   |
| ASIX Electronics      | 1        | 2.56%   |
| Apple                 | 1        | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 48.72%  |
| Intel I211 Gigabit Network Connection                             | 5        | 12.82%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 7.69%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 7.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.56%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.56%   |
| MediaTek NOA N2                                                   | 1        | 2.56%   |
| Intel Ethernet Connection I218-V                                  | 1        | 2.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.56%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 2.56%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 2.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 2.56%   |
| Apple iPad 4/Mini1                                                | 1        | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 35       | 74.47%  |
| WiFi     | 12       | 25.53%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 78.57%  |
| WiFi     | 9        | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 82.86%  |
| 2     | 4        | 11.43%  |
| 3     | 2        | 5.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 88.57%  |
| Yes  | 4        | 11.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 44.44%  |
| Cambridge Silicon Radio | 3        | 33.33%  |
| Broadcom                | 2        | 22.22%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 3        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 33.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 11.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 11.11%  |
| Broadcom BCM2045 Bluetooth                          | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 22       | 32.84%  |
| Nvidia              | 17       | 25.37%  |
| Intel               | 13       | 19.4%   |
| JMTek               | 3        | 4.48%   |
| C-Media Electronics | 3        | 4.48%   |
| Logitech            | 2        | 2.99%   |
| VIA Technologies    | 1        | 1.49%   |
| Unknown             | 1        | 1.49%   |
| SteelSeries ApS     | 1        | 1.49%   |
| SAVITECH            | 1        | 1.49%   |
| Focusrite-Novation  | 1        | 1.49%   |
| Elgato Systems      | 1        | 1.49%   |
| Cambridge Audio     | 1        | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 10%     |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 7.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 6.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 5%      |
| JMTek USB PnP Audio Device                                                 | 3        | 3.75%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 3.75%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 2.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.5%    |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 1.25%   |
| Unknown USB Audio                                                          | 1        | 1.25%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 1.25%   |
| SAVITECH SA9023 audio controller                                           | 1        | 1.25%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.25%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.25%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 1.25%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.25%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.25%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.25%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.25%   |
| Logitech G633 Gaming Headset                                               | 1        | 1.25%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1        | 1.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.25%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.25%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 1.25%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.25%   |
| Focusrite-Novation Scarlett 2i4                                            | 1        | 1.25%   |
| Elgato Systems Elgato Wave:3                                               | 1        | 1.25%   |
| Cambridge Audio USB Audio 2.0                                              | 1        | 1.25%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.25%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 1.25%   |
| C-Media Electronics Antlion USB adapter                                    | 1        | 1.25%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 1.25%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.25%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 1.25%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 1.25%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.25%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.25%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1        | 1.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 6        | 25%     |
| Kingston            | 4        | 16.67%  |
| Corsair             | 4        | 16.67%  |
| Unknown             | 3        | 12.5%   |
| Crucial             | 2        | 8.33%   |
| A-DATA Technology   | 2        | 8.33%   |
| Samsung Electronics | 1        | 4.17%   |
| Patriot             | 1        | 4.17%   |
| Avant               | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 2        | 6.9%    |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                  | 1        | 3.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 3.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 3.45%   |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s        | 1        | 3.45%   |
| Patriot RAM PSD48G24002 8192MB DIMM DDR4 2400MT/s          | 1        | 3.45%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s        | 1        | 3.45%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s       | 1        | 3.45%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 3.45%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 3.45%   |
| Kingston RAM 9905701-017.A00G 16384MB DIMM DDR4 2666MT/s   | 1        | 3.45%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s      | 1        | 3.45%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s       | 1        | 3.45%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s        | 1        | 3.45%   |
| G.Skill RAM F4-2800C17-8GIS 8192MB DIMM DDR4 2800MT/s      | 1        | 3.45%   |
| G.Skill RAM F4-2666C18-4GRS 4096MB SODIMM DDR4 2400MT/s    | 1        | 3.45%   |
| G.Skill RAM F3-10666CL7-2GBRH 2048MB DIMM DDR3 1333MT/s    | 1        | 3.45%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s       | 1        | 3.45%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s       | 1        | 3.45%   |
| Crucial RAM CT16G4DFD824A.M16FJ 16384MB DIMM DDR4 2400MT/s | 1        | 3.45%   |
| Crucial RAM CT16G4DFD824A.M16FD 16GB DIMM DDR4 2400MT/s    | 1        | 3.45%   |
| Crucial RAM BL25664TN1608.16FF 2048MB DIMM DDR3 1333MT/s   | 1        | 3.45%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s        | 1        | 3.45%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s       | 1        | 3.45%   |
| Corsair RAM CMK8GX4M1A2666C16 8192MB DIMM DDR4 3000MT/s    | 1        | 3.45%   |
| Avant RAM W641GU42J7240NC 8192MB DIMM DDR4 2400MT/s        | 1        | 3.45%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s                | 1        | 3.45%   |
| A-DATA RAM DDR4 2666 2OZ 16GB DIMM DDR4 3200MT/s           | 1        | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 17       | 70.83%  |
| DDR3    | 5        | 20.83%  |
| Unknown | 2        | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 23       | 95.83%  |
| SODIMM | 1        | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 12       | 48%     |
| 16384 | 5        | 20%     |
| 4096  | 5        | 20%     |
| 2048  | 2        | 8%      |
| 1024  | 1        | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 6        | 22.22%  |
| 1333  | 5        | 18.52%  |
| 3200  | 4        | 14.81%  |
| 3600  | 3        | 11.11%  |
| 3000  | 2        | 7.41%   |
| 3866  | 1        | 3.7%    |
| 3333  | 1        | 3.7%    |
| 2933  | 1        | 3.7%    |
| 2800  | 1        | 3.7%    |
| 2666  | 1        | 3.7%    |
| 1867  | 1        | 3.7%    |
| 1067  | 1        | 3.7%    |

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
| Logitech              | 5        | 38.46%  |
| Microdia              | 2        | 15.38%  |
| MacroSilicon          | 2        | 15.38%  |
| Realtek Semiconductor | 1        | 7.69%   |
| Microsoft             | 1        | 7.69%   |
| GEMBIRD               | 1        | 7.69%   |
| Chicony Electronics   | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 2        | 15.38%  |
| Realtek FULL HD 1080P Webcam                      | 1        | 7.69%   |
| Microsoft LifeCam HD-3000                         | 1        | 7.69%   |
| Microdia JP001                                    | 1        | 7.69%   |
| Microdia Camera                                   | 1        | 7.69%   |
| MacroSilicon USB Video                            | 1        | 7.69%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1        | 7.69%   |
| Logitech Webcam C930e                             | 1        | 7.69%   |
| Logitech HD Webcam C615                           | 1        | 7.69%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 7.69%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 7.69%   |
| Chicony HP 720p HD Monitor Webcam                 | 1        | 7.69%   |

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
| 0     | 30       | 85.71%  |
| 1     | 3        | 8.57%   |
| 2     | 2        | 5.71%   |

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

