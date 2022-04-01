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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Void Linux Rolling | 17       | 51.52%  |
| Void Linux         | 16       | 48.48%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Void Linux | 32       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Desktops | Percent |
|-----------|----------|---------|
| 5.8.18_1  | 2        | 5.56%   |
| 5.13.19_1 | 2        | 5.56%   |
| 5.11.9_1  | 2        | 5.56%   |
| 5.10.14_1 | 2        | 5.56%   |
| 5.9.14_1  | 1        | 2.78%   |
| 5.8.5_1   | 1        | 2.78%   |
| 5.8.16_1  | 1        | 2.78%   |
| 5.8.11_1  | 1        | 2.78%   |
| 5.8.10_1  | 1        | 2.78%   |
| 5.6.14_1  | 1        | 2.78%   |
| 5.4.15_1  | 1        | 2.78%   |
| 5.4.13_2  | 1        | 2.78%   |
| 5.3.16_1  | 1        | 2.78%   |
| 5.15.30_1 | 1        | 2.78%   |
| 5.15.22_1 | 1        | 2.78%   |
| 5.15.16_1 | 1        | 2.78%   |
| 5.15.11_1 | 1        | 2.78%   |
| 5.13.15_1 | 1        | 2.78%   |
| 5.13.13_1 | 1        | 2.78%   |
| 5.13.10_1 | 1        | 2.78%   |
| 5.12.14_1 | 1        | 2.78%   |
| 5.12.10_1 | 1        | 2.78%   |
| 5.11.18_1 | 1        | 2.78%   |
| 5.10.8_1  | 1        | 2.78%   |
| 5.10.7_1  | 1        | 2.78%   |
| 5.10.67_1 | 1        | 2.78%   |
| 5.10.3_1  | 1        | 2.78%   |
| 5.10.17_1 | 1        | 2.78%   |
| 4.19.67_1 | 1        | 2.78%   |
| 4.19.66_1 | 1        | 2.78%   |
| 4.19.34_1 | 1        | 2.78%   |
| 4.19.31_1 | 1        | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.18  | 2        | 5.56%   |
| 5.13.19 | 2        | 5.56%   |
| 5.11.9  | 2        | 5.56%   |
| 5.10.14 | 2        | 5.56%   |
| 5.9.14  | 1        | 2.78%   |
| 5.8.5   | 1        | 2.78%   |
| 5.8.16  | 1        | 2.78%   |
| 5.8.11  | 1        | 2.78%   |
| 5.8.10  | 1        | 2.78%   |
| 5.6.14  | 1        | 2.78%   |
| 5.4.15  | 1        | 2.78%   |
| 5.4.13  | 1        | 2.78%   |
| 5.3.16  | 1        | 2.78%   |
| 5.15.30 | 1        | 2.78%   |
| 5.15.22 | 1        | 2.78%   |
| 5.15.16 | 1        | 2.78%   |
| 5.15.11 | 1        | 2.78%   |
| 5.13.15 | 1        | 2.78%   |
| 5.13.13 | 1        | 2.78%   |
| 5.13.10 | 1        | 2.78%   |
| 5.12.14 | 1        | 2.78%   |
| 5.12.10 | 1        | 2.78%   |
| 5.11.18 | 1        | 2.78%   |
| 5.10.8  | 1        | 2.78%   |
| 5.10.7  | 1        | 2.78%   |
| 5.10.67 | 1        | 2.78%   |
| 5.10.3  | 1        | 2.78%   |
| 5.10.17 | 1        | 2.78%   |
| 4.19.67 | 1        | 2.78%   |
| 4.19.66 | 1        | 2.78%   |
| 4.19.34 | 1        | 2.78%   |
| 4.19.31 | 1        | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 7        | 19.44%  |
| 5.8     | 6        | 16.67%  |
| 5.13    | 5        | 13.89%  |
| 5.15    | 4        | 11.11%  |
| 4.19    | 4        | 11.11%  |
| 5.11    | 3        | 8.33%   |
| 5.4     | 2        | 5.56%   |
| 5.12    | 2        | 5.56%   |
| 5.9     | 1        | 2.78%   |
| 5.6     | 1        | 2.78%   |
| 5.3     | 1        | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 30       | 93.75%  |
| ppc64le | 1        | 3.13%   |
| i686    | 1        | 3.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 54.55%  |
| XFCE       | 4        | 12.12%  |
| X-Cinnamon | 2        | 6.06%   |
| KDE        | 2        | 6.06%   |
| GNOME      | 2        | 6.06%   |
| sway       | 1        | 3.03%   |
| Lumina     | 1        | 3.03%   |
| KDE5       | 1        | 3.03%   |
| bspwm      | 1        | 3.03%   |
| awesome    | 1        | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 24       | 75%     |
| Wayland | 4        | 12.5%   |
| Tty     | 3        | 9.38%   |
| Unknown | 1        | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 31       | 96.88%  |
| LXDM    | 1        | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 14       | 41.18%  |
| Unknown | 9        | 26.47%  |
| ru_RU   | 2        | 5.88%   |
| pt_BR   | 1        | 2.94%   |
| fr_FR   | 1        | 2.94%   |
| en_GB   | 1        | 2.94%   |
| en_DK   | 1        | 2.94%   |
| en_AU   | 1        | 2.94%   |
| el_GR   | 1        | 2.94%   |
| de_DE   | 1        | 2.94%   |
| cs_CZ   | 1        | 2.94%   |
| bg_BG   | 1        | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 20       | 60.61%  |
| EFI  | 13       | 39.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 21       | 65.63%  |
| Btrfs   | 5        | 15.63%  |
| Zfs     | 3        | 9.38%   |
| Xfs     | 2        | 6.25%   |
| Unknown | 1        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 15       | 46.88%  |
| Unknown | 12       | 37.5%   |
| MBR     | 5        | 15.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 87.5%   |
| Yes       | 4        | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 84.38%  |
| Yes       | 5        | 15.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 37.5%   |
| MSI                 | 6        | 18.75%  |
| ASRock              | 6        | 18.75%  |
| Gigabyte Technology | 4        | 12.5%   |
| Dell                | 2        | 6.25%   |
| Unknown             | 2        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS PRIME Z390-P           | 2        | 6.25%   |
| Unknown                     | 2        | 6.25%   |
| MSI MS-7D14                 | 1        | 3.13%   |
| MSI MS-7C92                 | 1        | 3.13%   |
| MSI MS-7C52                 | 1        | 3.13%   |
| MSI MS-7C02                 | 1        | 3.13%   |
| MSI MS-7A68                 | 1        | 3.13%   |
| MSI MS-7A39                 | 1        | 3.13%   |
| Gigabyte H310M M.2 2.0      | 1        | 3.13%   |
| Gigabyte GA-78LMT-S2        | 1        | 3.13%   |
| Gigabyte B550M AORUS PRO-P  | 1        | 3.13%   |
| Gigabyte B450M DS3H         | 1        | 3.13%   |
| Dell OptiPlex GX520         | 1        | 3.13%   |
| Dell OptiPlex 780           | 1        | 3.13%   |
| ASUS ROG CROSSHAIR VII HERO | 1        | 3.13%   |
| ASUS PRIME Z270-AR          | 1        | 3.13%   |
| ASUS PRIME X470-PRO         | 1        | 3.13%   |
| ASUS PRIME A320M-K/BR       | 1        | 3.13%   |
| ASUS P8Z77-V LX2            | 1        | 3.13%   |
| ASUS P8H67-V                | 1        | 3.13%   |
| ASUS M5A78L-M LX            | 1        | 3.13%   |
| ASUS M4A89GTD-PRO/USB3      | 1        | 3.13%   |
| ASUS H110M-PLUS             | 1        | 3.13%   |
| ASUS B150M PRO GAMING       | 1        | 3.13%   |
| ASRock N68-S3 FX            | 1        | 3.13%   |
| ASRock J4005B-ITX           | 1        | 3.13%   |
| ASRock H61M-VG4             | 1        | 3.13%   |
| ASRock B450 Pro4            | 1        | 3.13%   |
| ASRock AB350M               | 1        | 3.13%   |
| ASRock 970 Pro3 R2.0        | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 5        | 15.63%  |
| Dell OptiPlex        | 2        | 6.25%   |
| Unknown              | 2        | 6.25%   |
| MSI MS-7D14          | 1        | 3.13%   |
| MSI MS-7C92          | 1        | 3.13%   |
| MSI MS-7C52          | 1        | 3.13%   |
| MSI MS-7C02          | 1        | 3.13%   |
| MSI MS-7A68          | 1        | 3.13%   |
| MSI MS-7A39          | 1        | 3.13%   |
| Gigabyte H310M       | 1        | 3.13%   |
| Gigabyte GA-78LMT-S2 | 1        | 3.13%   |
| Gigabyte B550M       | 1        | 3.13%   |
| Gigabyte B450M       | 1        | 3.13%   |
| ASUS ROG             | 1        | 3.13%   |
| ASUS P8Z77-V         | 1        | 3.13%   |
| ASUS P8H67-V         | 1        | 3.13%   |
| ASUS M5A78L-M        | 1        | 3.13%   |
| ASUS M4A89GTD-PRO    | 1        | 3.13%   |
| ASUS H110M-PLUS      | 1        | 3.13%   |
| ASUS B150M           | 1        | 3.13%   |
| ASRock N68-S3        | 1        | 3.13%   |
| ASRock J4005B-ITX    | 1        | 3.13%   |
| ASRock H61M-VG4      | 1        | 3.13%   |
| ASRock B450          | 1        | 3.13%   |
| ASRock AB350M        | 1        | 3.13%   |
| ASRock 970           | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 8        | 25%     |
| 2020    | 4        | 12.5%   |
| 2017    | 4        | 12.5%   |
| 2019    | 3        | 9.38%   |
| 2012    | 3        | 9.38%   |
| 2011    | 3        | 9.38%   |
| 2016    | 2        | 6.25%   |
| 2010    | 2        | 6.25%   |
| 2013    | 1        | 3.13%   |
| 2006    | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 32       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 32       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 10       | 31.25%  |
| 8.01-16.0   | 10       | 31.25%  |
| 4.01-8.0    | 4        | 12.5%   |
| 32.01-64.0  | 4        | 12.5%   |
| 3.01-4.0    | 2        | 6.25%   |
| 2.01-3.0    | 1        | 3.13%   |
| 64.01-256.0 | 1        | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 10       | 27.78%  |
| 1.01-2.0   | 6        | 16.67%  |
| 3.01-4.0   | 5        | 13.89%  |
| 8.01-16.0  | 5        | 13.89%  |
| 0.51-1.0   | 5        | 13.89%  |
| 4.01-8.0   | 4        | 11.11%  |
| 16.01-24.0 | 1        | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 37.5%   |
| 3      | 11       | 34.38%  |
| 2      | 8        | 25%     |
| 4      | 1        | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 81.25%  |
| Yes       | 6        | 18.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 32       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 65.63%  |
| Yes       | 11       | 34.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 78.79%  |
| Yes       | 7        | 21.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 10       | 31.25%  |
| Germany    | 3        | 9.38%   |
| Brazil     | 3        | 9.38%   |
| Russia     | 2        | 6.25%   |
| Czechia    | 2        | 6.25%   |
| UK         | 1        | 3.13%   |
| Turkey     | 1        | 3.13%   |
| Sweden     | 1        | 3.13%   |
| Spain      | 1        | 3.13%   |
| Poland     | 1        | 3.13%   |
| India      | 1        | 3.13%   |
| Greece     | 1        | 3.13%   |
| France     | 1        | 3.13%   |
| Bulgaria   | 1        | 3.13%   |
| Bangladesh | 1        | 3.13%   |
| Australia  | 1        | 3.13%   |
| Argentina  | 1        | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Denver              | 3        | 9.09%   |
| Munich              | 2        | 6.06%   |
| Zagnansk            | 1        | 3.03%   |
| Yekaterinburg       | 1        | 3.03%   |
| Varna               | 1        | 3.03%   |
| Sydney              | 1        | 3.03%   |
| South Shields       | 1        | 3.03%   |
| Saint Paul          | 1        | 3.03%   |
| Rosario             | 1        | 3.03%   |
| Rio de Janeiro      | 1        | 3.03%   |
| Richmond            | 1        | 3.03%   |
| Prague              | 1        | 3.03%   |
| New York            | 1        | 3.03%   |
| Miedziana Gora      | 1        | 3.03%   |
| Kotlas              | 1        | 3.03%   |
| Kolkata             | 1        | 3.03%   |
| Ioannina            | 1        | 3.03%   |
| Huisseau-sur-Cosson | 1        | 3.03%   |
| Horice              | 1        | 3.03%   |
| Gothenburg          | 1        | 3.03%   |
| Elgin               | 1        | 3.03%   |
| Dhaka               | 1        | 3.03%   |
| Denizli             | 1        | 3.03%   |
| Contagem            | 1        | 3.03%   |
| Burgau              | 1        | 3.03%   |
| Blumenau            | 1        | 3.03%   |
| Beaver              | 1        | 3.03%   |
| Amsterdam           | 1        | 3.03%   |
| Allenton            | 1        | 3.03%   |
| Alaraz              | 1        | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 21     | 25%     |
| Samsung Electronics | 11       | 18     | 18.33%  |
| Seagate             | 9        | 10     | 15%     |
| Kingston            | 6        | 6      | 10%     |
| Toshiba             | 3        | 4      | 5%      |
| Intel               | 2        | 3      | 3.33%   |
| Corsair             | 2        | 2      | 3.33%   |
| SPCC                | 1        | 1      | 1.67%   |
| SanDisk             | 1        | 1      | 1.67%   |
| Phison              | 1        | 1      | 1.67%   |
| Patriot             | 1        | 1      | 1.67%   |
| OCZ                 | 1        | 1      | 1.67%   |
| MAXTOR              | 1        | 1      | 1.67%   |
| LITEONIT            | 1        | 1      | 1.67%   |
| Hitachi             | 1        | 1      | 1.67%   |
| HGST                | 1        | 1      | 1.67%   |
| Gigabyte Technology | 1        | 1      | 1.67%   |
| Crucial             | 1        | 2      | 1.67%   |
| A-DATA Technology   | 1        | 2      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                 | 3        | 4.41%   |
| Seagate ST2000DM008-2FR102 2TB           | 2        | 2.94%   |
| Samsung SSD 970 EVO Plus 1TB             | 2        | 2.94%   |
| Kingston SHFS37A120G 120GB SSD           | 2        | 2.94%   |
| Kingston SA400S37240G 240GB SSD          | 2        | 2.94%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 1.47%   |
| WDC WD7500AYYS-01RCA0 752GB              | 1        | 1.47%   |
| WDC WD5000AADS-00S9B0 500GB              | 1        | 1.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 1.47%   |
| WDC WD20EZBX-00AYRA0 2TB                 | 1        | 1.47%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1        | 1.47%   |
| WDC WD15EARS-00MVWB0 1TB                 | 1        | 1.47%   |
| WDC WD10JPVX-08JC3T6 1TB                 | 1        | 1.47%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1        | 1.47%   |
| WDC WD10EZRX-00L4HB0 1TB                 | 1        | 1.47%   |
| WDC WD10EFRX-68PJCN0 1TB                 | 1        | 1.47%   |
| WDC WD10EFRX-68FYTN0 1TB                 | 1        | 1.47%   |
| WDC WD10EARX-00PASB0 1TB                 | 1        | 1.47%   |
| WDC WD1002FAEX-00Z3A0 1TB                | 1        | 1.47%   |
| WDC WD1001FALS-00K1B0 1TB                | 1        | 1.47%   |
| Toshiba MQ04ABF100 1TB                   | 1        | 1.47%   |
| Toshiba HDWD110 1TB                      | 1        | 1.47%   |
| Toshiba DT01ACA200 2TB                   | 1        | 1.47%   |
| SPCC Solid State Disk 128GB              | 1        | 1.47%   |
| Seagate ST9500325AS 500GB                | 1        | 1.47%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1.47%   |
| Seagate ST3500413AS 500GB                | 1        | 1.47%   |
| Seagate ST3360320AS 360GB                | 1        | 1.47%   |
| Seagate ST2000DM006-2DM164 2TB           | 1        | 1.47%   |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1.47%   |
| Seagate ST1000LM035-1RK172 1TB           | 1        | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1.47%   |
| SanDisk Ultra 3D NVMe 1TB                | 1        | 1.47%   |
| Samsung SSD 980 PRO 500GB                | 1        | 1.47%   |
| Samsung SSD 970 EVO Plus 500GB           | 1        | 1.47%   |
| Samsung SSD 970 EVO 500GB                | 1        | 1.47%   |
| Samsung SSD 970 EVO 1TB                  | 1        | 1.47%   |
| Samsung SSD 860 EVO 500GB                | 1        | 1.47%   |
| Samsung SSD 860 EVO 250GB                | 1        | 1.47%   |
| Samsung SSD 850 EVO 500GB                | 1        | 1.47%   |
| Samsung SSD 840 PRO Series 512GB         | 1        | 1.47%   |
| Samsung SSD 750 EVO 500GB                | 1        | 1.47%   |
| Samsung NVMe SSD Drive 500GB             | 1        | 1.47%   |
| Samsung NVMe SSD Drive 1TB               | 1        | 1.47%   |
| Samsung HD322HJ 320GB                    | 1        | 1.47%   |
| Phison NVMe SSD Drive 1TB                | 1        | 1.47%   |
| Patriot Burst 120GB SSD                  | 1        | 1.47%   |
| OCZ AGILITY4 256GB SSD                   | 1        | 1.47%   |
| MAXTOR 7L250S0 256GB                     | 1        | 1.47%   |
| LITEONIT LCS-256L9S-11 2.5 7mm 256GB SSD | 1        | 1.47%   |
| Kingston SUV500MS120G 120GB SSD          | 1        | 1.47%   |
| Kingston SA400S37120G 120GB SSD          | 1        | 1.47%   |
| Intel SSDSC2BW240H6 240GB                | 1        | 1.47%   |
| Intel SSDPEKKW256G8 256GB                | 1        | 1.47%   |
| Intel NVMe SSD Drive 256GB               | 1        | 1.47%   |
| Hitachi HTS545050B9A300 500GB            | 1        | 1.47%   |
| HGST HTS545050A7E380 500GB               | 1        | 1.47%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD     | 1        | 1.47%   |
| Crucial CT960M500SSD1 960GB              | 1        | 1.47%   |
| Corsair Force MP600 1TB                  | 1        | 1.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 20     | 46.67%  |
| Seagate             | 9        | 10     | 30%     |
| Toshiba             | 3        | 4      | 10%     |
| Samsung Electronics | 1        | 1      | 3.33%   |
| MAXTOR              | 1        | 1      | 3.33%   |
| Hitachi             | 1        | 1      | 3.33%   |
| HGST                | 1        | 1      | 3.33%   |

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
| HDD  | 22       | 38     | 44%     |
| SSD  | 19       | 24     | 38%     |
| NVMe | 9        | 16     | 18%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 62     | 76.92%  |
| NVMe | 9        | 16     | 23.08%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 31     | 53.33%  |
| 0.51-1.0   | 14       | 21     | 31.11%  |
| 1.01-2.0   | 7        | 10     | 15.56%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 7        | 21.21%  |
| 101-250        | 7        | 21.21%  |
| 1001-2000      | 4        | 12.12%  |
| 501-1000       | 4        | 12.12%  |
| Unknown        | 4        | 12.12%  |
| More than 3000 | 3        | 9.09%   |
| 2001-3000      | 3        | 9.09%   |
| 1-20           | 1        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 22.22%  |
| 1-20           | 8        | 22.22%  |
| 251-500        | 4        | 11.11%  |
| 1001-2000      | 4        | 11.11%  |
| Unknown        | 4        | 11.11%  |
| 501-1000       | 3        | 8.33%   |
| 51-100         | 3        | 8.33%   |
| More than 3000 | 1        | 2.78%   |
| 21-50          | 1        | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB       | 1        | 2      | 12.5%   |
| WDC WD10EZEX-08WN4A0 1TB          | 1        | 1      | 12.5%   |
| Toshiba MQ04ABF100 1TB            | 1        | 2      | 12.5%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 12.5%   |
| Samsung Electronics HD322HJ 320GB | 1        | 1      | 12.5%   |
| Hitachi HTS545050B9A300 500GB     | 1        | 1      | 12.5%   |
| A-DATA Technology SU700 120GB SSD | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 3      | 25%     |
| Seagate             | 2        | 2      | 25%     |
| Toshiba             | 1        | 2      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Hitachi             | 1        | 1      | 12.5%   |
| A-DATA Technology   | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 3      | 28.57%  |
| Seagate             | 2        | 2      | 28.57%  |
| Toshiba             | 1        | 2      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| Hitachi             | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 9      | 85.71%  |
| SSD  | 1        | 1      | 14.29%  |

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
| Works    | 22       | 42     | 53.66%  |
| Detected | 13       | 26     | 31.71%  |
| Malfunc  | 6        | 10     | 14.63%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 16       | 36.36%  |
| Intel                    | 15       | 34.09%  |
| Samsung Electronics      | 6        | 13.64%  |
| Phison Electronics       | 2        | 4.55%   |
| Sandisk                  | 1        | 2.27%   |
| Nvidia                   | 1        | 2.27%   |
| Marvell Technology Group | 1        | 2.27%   |
| JMicron Technology       | 1        | 2.27%   |
| ASMedia Technology       | 1        | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 7        | 12.5%   |
| AMD 400 Series Chipset SATA Controller                                        | 6        | 10.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5        | 8.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 3        | 5.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 3        | 5.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 3        | 5.36%   |
| AMD 500 Series Chipset SATA Controller                                        | 3        | 5.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 3.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 3.57%   |
| AMD 300 Series Chipset SATA Controller                                        | 2        | 3.57%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1        | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 1.79%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 1.79%   |
| Phison E12 NVMe Controller                                                    | 1        | 1.79%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 1.79%   |
| Nvidia MCP61 IDE                                                              | 1        | 1.79%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller              | 1        | 1.79%   |
| JMicron JMB361 AHCI/IDE                                                       | 1        | 1.79%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 1        | 1.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1        | 1.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1        | 1.79%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                          | 1        | 1.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1        | 1.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 1        | 1.79%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1        | 1.79%   |
| AMD FCH SATA Controller D                                                     | 1        | 1.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 30       | 68.18%  |
| NVMe | 9        | 20.45%  |
| IDE  | 5        | 11.36%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 17       | 53.13%  |
| Intel                    | 14       | 43.75%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 3.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4        | 12.5%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2        | 6.25%   |
| AMD FX-4300 Quad-Core Processor                    | 2        | 6.25%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1        | 3.13%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1        | 3.13%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1        | 3.13%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1        | 3.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 1        | 3.13%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1        | 3.13%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1        | 3.13%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1        | 3.13%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1        | 3.13%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1        | 3.13%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1        | 3.13%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1        | 3.13%   |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1        | 3.13%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 1        | 3.13%   |
| AMD Ryzen 7 1700X Eight-Core Processor             | 1        | 3.13%   |
| AMD Ryzen 7 1700 Eight-Core Processor              | 1        | 3.13%   |
| AMD Ryzen 5 5600G with Radeon Graphics             | 1        | 3.13%   |
| AMD Ryzen 5 3600 6-Core Processor                  | 1        | 3.13%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 1        | 3.13%   |
| AMD Ryzen 5 1600 Six-Core Processor                | 1        | 3.13%   |
| AMD Ryzen 3 3100 4-Core Processor                  | 1        | 3.13%   |
| AMD Phenom II X4 980 Processor                     | 1        | 3.13%   |
| AMD Athlon II X3 455 Processor                     | 1        | 3.13%   |
| AMD Athlon II X2 280 Processor                     | 1        | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| AMD Ryzen 5        | 8        | 25%     |
| Intel Core i5      | 5        | 15.63%  |
| Intel Core i3      | 3        | 9.38%   |
| AMD Ryzen 7        | 3        | 9.38%   |
| AMD FX             | 2        | 6.25%   |
| Other              | 1        | 3.13%   |
| Intel Pentium Gold | 1        | 3.13%   |
| Intel Pentium 4    | 1        | 3.13%   |
| Intel Core i9      | 1        | 3.13%   |
| Intel Core i7      | 1        | 3.13%   |
| Intel Core 2 Duo   | 1        | 3.13%   |
| Intel Celeron      | 1        | 3.13%   |
| AMD Ryzen 3        | 1        | 3.13%   |
| AMD Phenom II X4   | 1        | 3.13%   |
| AMD Athlon II X3   | 1        | 3.13%   |
| AMD Athlon II X2   | 1        | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 28.13%  |
| 6      | 8        | 25%     |
| 2      | 8        | 25%     |
| 8      | 5        | 15.63%  |
| 3      | 1        | 3.13%   |
| 1      | 1        | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 59.38%  |
| 1      | 12       | 37.5%   |
| 4      | 1        | 3.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 28       | 87.5%   |
| Unknown        | 3        | 9.38%   |
| 32-bit         | 1        | 3.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 33.33%  |
| 0x906e9    | 2        | 6.06%   |
| 0x08701021 | 2        | 6.06%   |
| 0x06000852 | 2        | 6.06%   |
| 0x010000c8 | 2        | 6.06%   |
| 0x906ed    | 1        | 3.03%   |
| 0x906ea    | 1        | 3.03%   |
| 0x706a1    | 1        | 3.03%   |
| 0x506e3    | 1        | 3.03%   |
| 0x306a9    | 1        | 3.03%   |
| 0x1067a    | 1        | 3.03%   |
| 0x0a50000c | 1        | 3.03%   |
| 0x0a201205 | 1        | 3.03%   |
| 0x0a201009 | 1        | 3.03%   |
| 0x08701013 | 1        | 3.03%   |
| 0x0800820d | 1        | 3.03%   |
| 0x08001138 | 1        | 3.03%   |
| 0x08001136 | 1        | 3.03%   |
| 0x08001129 | 1        | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 6        | 18.75%  |
| Zen 3         | 5        | 15.63%  |
| Zen           | 3        | 9.38%   |
| K10           | 3        | 9.38%   |
| IvyBridge     | 3        | 9.38%   |
| Zen+          | 2        | 6.25%   |
| Zen 2         | 2        | 6.25%   |
| Piledriver    | 2        | 6.25%   |
| Skylake       | 1        | 3.13%   |
| Penryn        | 1        | 3.13%   |
| NetBurst      | 1        | 3.13%   |
| Haswell       | 1        | 3.13%   |
| Goldmont plus | 1        | 3.13%   |
| Unknown       | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 15       | 42.86%  |
| AMD               | 14       | 40%     |
| Intel             | 5        | 14.29%  |
| ASPEED Technology | 1        | 2.86%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                               | 3        | 8.33%   |
| Nvidia GM204 [GeForce GTX 970]                                   | 2        | 5.56%   |
| Nvidia GK208B [GeForce GT 710]                                   | 2        | 5.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 2        | 5.56%   |
| Nvidia TU106 [GeForce RTX 2070]                                  | 1        | 2.78%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                            | 1        | 2.78%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                        | 1        | 2.78%   |
| Nvidia GP108 [GeForce GT 1030]                                   | 1        | 2.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                  | 1        | 2.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 1        | 2.78%   |
| Nvidia GK110 [GeForce GTX 780]                                   | 1        | 2.78%   |
| Nvidia GF108 [GeForce GT 420]                                    | 1        | 2.78%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                          | 1        | 2.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                 | 1        | 2.78%   |
| Intel GeminiLake [UHD Graphics 600]                              | 1        | 2.78%   |
| Intel 82945G/GZ Integrated Graphics Controller                   | 1        | 2.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller            | 1        | 2.78%   |
| ASPEED Technology ASPEED Graphics Family                         | 1        | 2.78%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 1        | 2.78%   |
| AMD Tonga PRO [Radeon R9 285/380]                                | 1        | 2.78%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                | 1        | 2.78%   |
| AMD RS880 [Radeon HD 4290]                                       | 1        | 2.78%   |
| AMD RS780L [Radeon 3000]                                         | 1        | 2.78%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                   | 1        | 2.78%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]             | 1        | 2.78%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                   | 1        | 2.78%   |
| AMD Juniper XT [Radeon HD 6770]                                  | 1        | 2.78%   |
| AMD Cezanne                                                      | 1        | 2.78%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]               | 1        | 2.78%   |
| AMD Bonaire [FirePro W5100]                                      | 1        | 2.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 14       | 42.42%  |
| 1 x AMD      | 13       | 39.39%  |
| 1 x Intel    | 4        | 12.12%  |
| 2 x Nvidia   | 1        | 3.03%   |
| AMD + ASPEED | 1        | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 57.58%  |
| Proprietary | 14       | 42.42%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 30.3%   |
| 3.01-4.0   | 7        | 21.21%  |
| 1.01-2.0   | 7        | 21.21%  |
| 7.01-8.0   | 2        | 6.06%   |
| 2.01-3.0   | 2        | 6.06%   |
| 8.01-16.0  | 2        | 6.06%   |
| 5.01-6.0   | 1        | 3.03%   |
| 0.51-1.0   | 1        | 3.03%   |
| 0.01-0.5   | 1        | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 13.51%  |
| Hewlett-Packard      | 5        | 13.51%  |
| Dell                 | 5        | 13.51%  |
| Acer                 | 4        | 10.81%  |
| Philips              | 3        | 8.11%   |
| Goldstar             | 2        | 5.41%   |
| BenQ                 | 2        | 5.41%   |
| Ancor Communications | 2        | 5.41%   |
| Unknown              | 1        | 2.7%    |
| Sceptre Tech         | 1        | 2.7%    |
| Sceptre              | 1        | 2.7%    |
| ONN                  | 1        | 2.7%    |
| MSI                  | 1        | 2.7%    |
| Lenovo               | 1        | 2.7%    |
| Iiyama               | 1        | 2.7%    |
| FUN                  | 1        | 2.7%    |
| Fujitsu Siemens      | 1        | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1        | 2.5%    |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1        | 2.5%    |
| Sceptre LCD Monitor E24 1920x1080                                     | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1        | 2.5%    |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1        | 2.5%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1        | 2.5%    |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1        | 2.5%    |
| Samsung Electronics LCD Monitor C49HG9x                               | 1        | 2.5%    |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1        | 2.5%    |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1        | 2.5%    |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1        | 2.5%    |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1        | 2.5%    |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                | 1        | 2.5%    |
| Lenovo LEN-22ICB-C LEN1201 1920x1080 476x268mm 21.5-inch              | 1        | 2.5%    |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1        | 2.5%    |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 1        | 2.5%    |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1        | 2.5%    |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1        | 2.5%    |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1        | 2.5%    |
| Hewlett-Packard 21kd HWP3329 1920x1080 458x258mm 20.7-inch            | 1        | 2.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 2.5%    |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1        | 2.5%    |
| FUN HDMI Monitor FUN9D31 3840x2160 480x270mm 21.7-inch                | 1        | 2.5%    |
| Fujitsu Siemens SL27T-1 LED FUS07E4 1920x1080 598x336mm 27.0-inch     | 1        | 2.5%    |
| Dell U3818DW DELA0F4 3840x1600 880x367mm 37.5-inch                    | 1        | 2.5%    |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                     | 1        | 2.5%    |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 1        | 2.5%    |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 1        | 2.5%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1        | 2.5%    |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1        | 2.5%    |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                     | 1        | 2.5%    |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 1        | 2.5%    |
| Ancor Communications VW222 ACI22A2 1680x1050 473x296mm 22.0-inch      | 1        | 2.5%    |
| Ancor Communications LCD Monitor ASUS ML239 1920x1080                 | 1        | 2.5%    |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 1        | 2.5%    |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 1        | 2.5%    |
| Acer LCD Monitor S181HL 1366x768                                      | 1        | 2.5%    |
| Acer KG251Q ACR0591 1920x1080 544x303mm 24.5-inch                     | 1        | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 50%     |
| 1680x1050 (WSXGA+) | 4        | 11.11%  |
| 1920x1200 (WUXGA)  | 3        | 8.33%   |
| 3840x2160 (4K)     | 2        | 5.56%   |
| 2560x1440 (QHD)    | 2        | 5.56%   |
| 1366x768 (WXGA)    | 2        | 5.56%   |
| 7680x1080          | 1        | 2.78%   |
| 3840x1600          | 1        | 2.78%   |
| 3440x1440          | 1        | 2.78%   |
| 1280x1024 (SXGA)   | 1        | 2.78%   |
| Unknown            | 1        | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 23.68%  |
| Unknown | 8        | 21.05%  |
| 21      | 5        | 13.16%  |
| 22      | 4        | 10.53%  |
| 27      | 3        | 7.89%   |
| 23      | 2        | 5.26%   |
| 40      | 1        | 2.63%   |
| 37      | 1        | 2.63%   |
| 34      | 1        | 2.63%   |
| 31      | 1        | 2.63%   |
| 25      | 1        | 2.63%   |
| 20      | 1        | 2.63%   |
| 17      | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 37.84%  |
| 401-500     | 10       | 27.03%  |
| Unknown     | 8        | 21.62%  |
| 801-900     | 2        | 5.41%   |
| 701-800     | 1        | 2.7%    |
| 601-700     | 1        | 2.7%    |
| 301-350     | 1        | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 52.78%  |
| Unknown | 8        | 22.22%  |
| 16/10   | 6        | 16.67%  |
| 21/9    | 2        | 5.56%   |
| 5/4     | 1        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 37.84%  |
| Unknown        | 8        | 21.62%  |
| 251-300        | 6        | 16.22%  |
| 301-350        | 3        | 8.11%   |
| 351-500        | 2        | 5.41%   |
| 501-1000       | 2        | 5.41%   |
| 151-200        | 1        | 2.7%    |
| 141-150        | 1        | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 52.63%  |
| 101-120 | 9        | 23.68%  |
| Unknown | 8        | 21.05%  |
| 161-240 | 1        | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 81.82%  |
| 2     | 6        | 18.18%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 22       | 47.83%  |
| Intel                           | 10       | 21.74%  |
| TP-Link                         | 2        | 4.35%   |
| Ralink Technology               | 2        | 4.35%   |
| Qualcomm Atheros Communications | 2        | 4.35%   |
| Broadcom                        | 2        | 4.35%   |
| Tenda                           | 1        | 2.17%   |
| Qualcomm Atheros                | 1        | 2.17%   |
| Nvidia                          | 1        | 2.17%   |
| MediaTek                        | 1        | 2.17%   |
| ASIX Electronics                | 1        | 2.17%   |
| Apple                           | 1        | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 41.3%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 6.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 4.35%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 4.35%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 2.17%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 2.17%   |
| Tenda U12                                                         | 1        | 2.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 2.17%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 2.17%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.17%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.17%   |
| MediaTek U FEEL                                                   | 1        | 2.17%   |
| Intel Ethernet Connection I218-V                                  | 1        | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.17%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 2.17%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 2.17%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 2.17%   |
| Apple iPad 4/Mini1                                                | 1        | 2.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 27.27%  |
| TP-Link                         | 2        | 18.18%  |
| Ralink Technology               | 2        | 18.18%  |
| Qualcomm Atheros Communications | 2        | 18.18%  |
| Tenda                           | 1        | 9.09%   |
| Realtek Semiconductor           | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                 | 2        | 18.18%  |
| Intel Wi-Fi 6 AX200                             | 2        | 18.18%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]    | 1        | 9.09%   |
| TP-Link Archer T3U [Realtek RTL8812BU]          | 1        | 9.09%   |
| Tenda U12                                       | 1        | 9.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter | 1        | 9.09%   |
| Ralink RT5572 Wireless Adapter                  | 1        | 9.09%   |
| Ralink MT7601U Wireless Adapter                 | 1        | 9.09%   |
| Intel Cannon Lake PCH CNVi WiFi                 | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 60%     |
| Intel                 | 7        | 20%     |
| Broadcom              | 2        | 5.71%   |
| Qualcomm Atheros      | 1        | 2.86%   |
| Nvidia                | 1        | 2.86%   |
| MediaTek              | 1        | 2.86%   |
| ASIX Electronics      | 1        | 2.86%   |
| Apple                 | 1        | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 54.29%  |
| Intel Ethernet Connection (2) I219-V                              | 3        | 8.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 5.71%   |
| Intel I211 Gigabit Network Connection                             | 2        | 5.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.86%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.86%   |
| MediaTek U FEEL                                                   | 1        | 2.86%   |
| Intel Ethernet Connection I218-V                                  | 1        | 2.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.86%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 2.86%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 2.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 2.86%   |
| Apple iPad 4/Mini1                                                | 1        | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 74.42%  |
| WiFi     | 11       | 25.58%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 76.92%  |
| WiFi     | 9        | 23.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 84.38%  |
| 2     | 4        | 12.5%   |
| 3     | 1        | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 87.5%   |
| Yes  | 4        | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 37.5%   |
| Cambridge Silicon Radio | 3        | 37.5%   |
| Broadcom                | 2        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 37.5%   |
| Intel AX200 Bluetooth                               | 2        | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 12.5%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 12.5%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 19       | 32.2%   |
| Nvidia              | 15       | 25.42%  |
| Intel               | 13       | 22.03%  |
| JMTek               | 3        | 5.08%   |
| C-Media Electronics | 3        | 5.08%   |
| Logitech            | 2        | 3.39%   |
| VIA Technologies    | 1        | 1.69%   |
| SAVITECH            | 1        | 1.69%   |
| Elgato Systems      | 1        | 1.69%   |
| Cambridge Audio     | 1        | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 8.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 7.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 5.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 5.63%   |
| JMTek USB PnP Audio Device                                                 | 3        | 4.23%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 4.23%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 2.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 2.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.82%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 1.41%   |
| SAVITECH SA9023 audio controller                                           | 1        | 1.41%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.41%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.41%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.41%   |
| Logitech G633 Gaming Headset                                               | 1        | 1.41%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1        | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.41%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.41%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 1.41%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.41%   |
| Elgato Systems Elgato Wave:3                                               | 1        | 1.41%   |
| Cambridge Audio USB Audio 2.0                                              | 1        | 1.41%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.41%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 1.41%   |
| C-Media Electronics Antlion USB adapter                                    | 1        | 1.41%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 1.41%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.41%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 1.41%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 1.41%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.41%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1        | 1.41%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 5        | 22.73%  |
| Corsair             | 4        | 18.18%  |
| Unknown             | 3        | 13.64%  |
| Kingston            | 3        | 13.64%  |
| Crucial             | 2        | 9.09%   |
| A-DATA Technology   | 2        | 9.09%   |
| Samsung Electronics | 1        | 4.55%   |
| Patriot             | 1        | 4.55%   |
| Avant               | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s   | 2        | 7.41%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                  | 1        | 3.7%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 3.7%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 3.7%    |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s        | 1        | 3.7%    |
| Patriot RAM PSD48G24002 8192MB DIMM DDR4 2400MT/s          | 1        | 3.7%    |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s          | 1        | 3.7%    |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 3.7%    |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 3.7%    |
| Kingston RAM 9905701-017.A00G 16384MB DIMM DDR4 2666MT/s   | 1        | 3.7%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s       | 1        | 3.7%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s        | 1        | 3.7%    |
| G.Skill RAM F4-2800C17-8GIS 8192MB DIMM DDR4 2800MT/s      | 1        | 3.7%    |
| G.Skill RAM F4-2666C18-4GRS 4096MB SODIMM DDR4 2400MT/s    | 1        | 3.7%    |
| G.Skill RAM F3-10666CL7-2GBRH 2048MB DIMM DDR3 1333MT/s    | 1        | 3.7%    |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s       | 1        | 3.7%    |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s       | 1        | 3.7%    |
| Crucial RAM CT16G4DFD824A.M16FJ 16384MB DIMM DDR4 2400MT/s | 1        | 3.7%    |
| Crucial RAM CT16G4DFD824A.M16FD 16GB DIMM DDR4 2400MT/s    | 1        | 3.7%    |
| Crucial RAM BL25664TN1608.16FF 2048MB DIMM DDR3 1333MT/s   | 1        | 3.7%    |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s        | 1        | 3.7%    |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s       | 1        | 3.7%    |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s       | 1        | 3.7%    |
| Avant RAM W641GU42J7240NC 8192MB DIMM DDR4 2400MT/s        | 1        | 3.7%    |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s                | 1        | 3.7%    |
| A-DATA RAM DDR4 2666 2OZ 16GB DIMM DDR4 3200MT/s           | 1        | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 15       | 68.18%  |
| DDR3    | 5        | 22.73%  |
| Unknown | 2        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 21       | 95.45%  |
| SODIMM | 1        | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 11       | 47.83%  |
| 4096  | 5        | 21.74%  |
| 16384 | 4        | 17.39%  |
| 2048  | 2        | 8.7%    |
| 1024  | 1        | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 6        | 24%     |
| 1333  | 5        | 20%     |
| 3200  | 4        | 16%     |
| 3600  | 3        | 12%     |
| 3000  | 2        | 8%      |
| 2933  | 1        | 4%      |
| 2800  | 1        | 4%      |
| 2666  | 1        | 4%      |
| 1867  | 1        | 4%      |
| 1067  | 1        | 4%      |

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
| Microdia Hy-HD-Camera                             | 1        | 7.69%   |
| Microdia Camera                                   | 1        | 7.69%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1        | 7.69%   |
| MacroSilicon MiraBox Capture                      | 1        | 7.69%   |
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
| 0     | 27       | 84.38%  |
| 1     | 3        | 9.38%   |
| 2     | 2        | 6.25%   |

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

