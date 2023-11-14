RHEL 9 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for RHEL 9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 42

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [1c3bf8f6ef](https://linux-hardware.org/?probe=1c3bf8f6ef) | Oct 19, 2023 |
| System76 | Galago Pro                  | [fbdb665814](https://linux-hardware.org/?probe=fbdb665814) | Oct 03, 2023 |
| Dell     | Inspiron N5010              | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Dell     | G16 7620                    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| Dell     | Precision 7720              | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo   | ThinkPad T490 20N3S77601    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| MSI      | Katana GF66 12UC            | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| HP       | EliteBook 2570p             | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| HP       | EliteBook 855 G7 Noteboo... | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo   | ThinkBook 14-IIL 20SL       | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell     | Precision 7510              | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Lenovo   | ThinkPad X1 Nano Gen 2 2... | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| HP       | ProBook 640 G2              | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP       | ProBook 640 G2              | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek  | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo   | ThinkPad L14 Gen 3 21C2S... | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Dell     | Precision 7560              | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI      | GP75 Leopard 9SD            | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Dell     | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell     | Latitude 3410               | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| MSI      | GE72VR 7RF                  | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo   | ThinkPad X1 Nano Gen 2 2... | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP       | Laptop 14s-dk0xxx           | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Dell     | Latitude E7450              | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| Lenovo   | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo   | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek  | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek  | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP       | 340S G7                     | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer    | Blade 15 Mid 2019-Base      | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Dell     | Precision 7510              | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Dell     | Inspiron 5559               | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo   | ThinkPad E14 20RA001MMZ     | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo   | ThinkPad Edge E431 62771... | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| ASUSTek  | TUF Gaming Z690-PLUS WIF... | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Dell     | XPS 17 9710                 | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell     | XPS 17 9710                 | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| Lenovo   | ThinkBook 13s-IWL 20R9      | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Samsung  | 730QCJ/730QCR               | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| HP       | Pavilion Gaming Laptop 1... | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Gigabyte | AERO 15 KD                  | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-284.30.1.el9_2.x86_64 | 5         | 14.71%  |
| 5.14.0-162.6.1.el9_1.x86_64  | 4         | 11.76%  |
| 5.14.0-70.5.1.el9_0.x86_64   | 3         | 8.82%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 3         | 8.82%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 3         | 8.82%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 3         | 8.82%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 3         | 8.82%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 2         | 5.88%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 5.88%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 5.88%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 2.94%   |
| 5.14.0-39.el9.x86_64         | 1         | 2.94%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 1         | 2.94%   |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 32        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 32        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 32        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 30        | 90.91%  |
| KDE5            | 1         | 3.03%   |
| GNOME Flashback | 1         | 3.03%   |
| GNOME Classic   | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 24        | 75%     |
| X11     | 8         | 25%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 65.63%  |
| GDM     | 11        | 34.38%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 26        | 81.25%  |
| pt_BR | 2         | 6.25%   |
| en_GB | 2         | 6.25%   |
| en_IN | 1         | 3.13%   |
| cs_CZ | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 31        | 96.88%  |
| BIOS | 1         | 3.13%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 31        | 96.88%  |
| Ext4 | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 65.63%  |
| GPT     | 11        | 34.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 93.75%  |
| Yes       | 2         | 6.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 87.5%   |
| Yes       | 4         | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 9         | 28.13%  |
| Lenovo              | 8         | 25%     |
| Hewlett-Packard     | 5         | 15.63%  |
| MSI                 | 3         | 9.38%   |
| ASUSTek Computer    | 3         | 9.38%   |
| System76            | 1         | 3.13%   |
| Samsung Electronics | 1         | 3.13%   |
| Razer               | 1         | 3.13%   |
| Gigabyte Technology | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| System76 Galago Pro                      | 1         | 3.13%   |
| Samsung 730QCJ/730QCR                    | 1         | 3.13%   |
| Razer Blade 15 Mid 2019-Base             | 1         | 3.13%   |
| MSI Katana GF66 12UC                     | 1         | 3.13%   |
| MSI GP75 Leopard 9SD                     | 1         | 3.13%   |
| MSI GE72VR 7RF                           | 1         | 3.13%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US | 1         | 3.13%   |
| Lenovo ThinkPad T490 20N3S77601          | 1         | 3.13%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 3.13%   |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00     | 1         | 3.13%   |
| Lenovo ThinkPad Edge E431 62771L7        | 1         | 3.13%   |
| Lenovo ThinkPad E14 20RA001MMZ           | 1         | 3.13%   |
| Lenovo ThinkBook 14-IIL 20SL             | 1         | 3.13%   |
| Lenovo ThinkBook 13s-IWL 20R9            | 1         | 3.13%   |
| HP ProBook 640 G2                        | 1         | 3.13%   |
| HP Laptop 14s-dk0xxx                     | 1         | 3.13%   |
| HP EliteBook 855 G7 Notebook PC          | 1         | 3.13%   |
| HP EliteBook 2570p                       | 1         | 3.13%   |
| HP 340S G7                               | 1         | 3.13%   |
| Gigabyte AERO 15 KD                      | 1         | 3.13%   |
| Dell XPS 17 9710                         | 1         | 3.13%   |
| Dell Precision 7720                      | 1         | 3.13%   |
| Dell Precision 7560                      | 1         | 3.13%   |
| Dell Precision 7510                      | 1         | 3.13%   |
| Dell Latitude E7450                      | 1         | 3.13%   |
| Dell Latitude 3410                       | 1         | 3.13%   |
| Dell Inspiron N5010                      | 1         | 3.13%   |
| Dell Inspiron 5559                       | 1         | 3.13%   |
| Dell G16 7620                            | 1         | 3.13%   |
| ASUS Z450LA                              | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X515MA_A516MA   | 1         | 3.13%   |
| ASUS TUF Gaming Z690-PLUS WIFI D4        | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo ThinkPad  | 6         | 18.75%  |
| Dell Precision   | 3         | 9.38%   |
| Lenovo ThinkBook | 2         | 6.25%   |
| HP EliteBook     | 2         | 6.25%   |
| Dell Latitude    | 2         | 6.25%   |
| Dell Inspiron    | 2         | 6.25%   |
| System76 Galago  | 1         | 3.13%   |
| Samsung 730QCJ   | 1         | 3.13%   |
| Razer Blade      | 1         | 3.13%   |
| MSI Katana       | 1         | 3.13%   |
| MSI GP75         | 1         | 3.13%   |
| MSI GE72VR       | 1         | 3.13%   |
| HP ProBook       | 1         | 3.13%   |
| HP Laptop        | 1         | 3.13%   |
| HP 340S          | 1         | 3.13%   |
| Gigabyte AERO    | 1         | 3.13%   |
| Dell XPS         | 1         | 3.13%   |
| Dell G16         | 1         | 3.13%   |
| ASUS Z450LA      | 1         | 3.13%   |
| ASUS VivoBook    | 1         | 3.13%   |
| ASUS TUF         | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 8         | 25%     |
| 2021 | 6         | 18.75%  |
| 2020 | 5         | 15.63%  |
| 2015 | 3         | 9.38%   |
| 2022 | 2         | 6.25%   |
| 2017 | 2         | 6.25%   |
| 2023 | 1         | 3.13%   |
| 2016 | 1         | 3.13%   |
| 2014 | 1         | 3.13%   |
| 2013 | 1         | 3.13%   |
| 2012 | 1         | 3.13%   |
| 2010 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 32        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 25        | 75.76%  |
| Enabled  | 8         | 24.24%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 96.88%  |
| Yes  | 1         | 3.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 14        | 43.75%  |
| 4.01-8.0    | 6         | 18.75%  |
| 32.01-64.0  | 5         | 15.63%  |
| 3.01-4.0    | 3         | 9.38%   |
| 64.01-256.0 | 3         | 9.38%   |
| 16.01-24.0  | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 11        | 32.35%  |
| 4.01-8.0   | 9         | 26.47%  |
| 3.01-4.0   | 7         | 20.59%  |
| 8.01-16.0  | 4         | 11.76%  |
| 1.01-2.0   | 2         | 5.88%   |
| 32.01-64.0 | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 58.82%  |
| 2      | 10        | 29.41%  |
| 3      | 3         | 8.82%   |
| 4      | 1         | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 84.38%  |
| Yes       | 5         | 15.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 81.25%  |
| No        | 6         | 18.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 96.88%  |
| No        | 1         | 3.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 84.85%  |
| No        | 5         | 15.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 31.25%  |
| India       | 3         | 9.38%   |
| Turkey      | 2         | 6.25%   |
| Guatemala   | 2         | 6.25%   |
| Chile       | 2         | 6.25%   |
| Brazil      | 2         | 6.25%   |
| UK          | 1         | 3.13%   |
| Switzerland | 1         | 3.13%   |
| Sri Lanka   | 1         | 3.13%   |
| Norway      | 1         | 3.13%   |
| Kenya       | 1         | 3.13%   |
| Jordan      | 1         | 3.13%   |
| Italy       | 1         | 3.13%   |
| Indonesia   | 1         | 3.13%   |
| Finland     | 1         | 3.13%   |
| Egypt       | 1         | 3.13%   |
| Czechia     | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Santiago       | 2         | 5.88%   |
| Guatemala City | 2         | 5.88%   |
| Whiteley       | 1         | 2.94%   |
| Stratham       | 1         | 2.94%   |
| Skien          | 1         | 2.94%   |
| Sao Paulo      | 1         | 2.94%   |
| Saint Paul     | 1         | 2.94%   |
| Providence     | 1         | 2.94%   |
| Prairieville   | 1         | 2.94%   |
| Piracicaba     | 1         | 2.94%   |
| Parker         | 1         | 2.94%   |
| New Delhi      | 1         | 2.94%   |
| Nairobi        | 1         | 2.94%   |
| Montgomery     | 1         | 2.94%   |
| Milano         | 1         | 2.94%   |
| Maltepe        | 1         | 2.94%   |
| Liberec        | 1         | 2.94%   |
| Kolkata        | 1         | 2.94%   |
| Houston        | 1         | 2.94%   |
| Helsinki       | 1         | 2.94%   |
| Fort Collins   | 1         | 2.94%   |
| Denizli        | 1         | 2.94%   |
| Corona         | 1         | 2.94%   |
| Colombo        | 1         | 2.94%   |
| Christiansburg | 1         | 2.94%   |
| Chennai        | 1         | 2.94%   |
| Cairo          | 1         | 2.94%   |
| Bern           | 1         | 2.94%   |
| Bay Shore      | 1         | 2.94%   |
| Bandung        | 1         | 2.94%   |
| Baltimore      | 1         | 2.94%   |
| Amman          | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 12        | 14     | 24.49%  |
| Sandisk                     | 5         | 6      | 10.2%   |
| Toshiba                     | 4         | 4      | 8.16%   |
| Unknown                     | 3         | 3      | 6.12%   |
| Seagate                     | 3         | 4      | 6.12%   |
| Micron Technology           | 3         | 3      | 6.12%   |
| KIOXIA                      | 3         | 4      | 6.12%   |
| SK hynix                    | 2         | 2      | 4.08%   |
| Intel                       | 2         | 3      | 4.08%   |
| WDC                         | 1         | 1      | 2.04%   |
| SSSTC                       | 1         | 1      | 2.04%   |
| SABRENT                     | 1         | 1      | 2.04%   |
| Plextor                     | 1         | 1      | 2.04%   |
| Phison                      | 1         | 1      | 2.04%   |
| Kingston Technology Company | 1         | 1      | 2.04%   |
| Kingston                    | 1         | 1      | 2.04%   |
| KingSpec                    | 1         | 1      | 2.04%   |
| HGST                        | 1         | 1      | 2.04%   |
| Golden                      | 1         | 1      | 2.04%   |
| China                       | 1         | 1      | 2.04%   |
| A-DATA Technology           | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  256GB                            | 2         | 3.92%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB    | 2         | 3.92%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 2         | 3.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 3.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 3.92%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                         | 2         | 3.92%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 1.96%   |
| Unknown MMC Card  512GB                            | 1         | 1.96%   |
| Toshiba MQ01ACF050 500GB                           | 1         | 1.96%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 1.96%   |
| Toshiba MQ01ABF032 320GB                           | 1         | 1.96%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1.96%   |
| SSSTC CL1-3D512-Q11 NVMe 512GB                     | 1         | 1.96%   |
| SK hynix SHGP31-1000GM 1TB                         | 1         | 1.96%   |
| SK hynix NVMe SSD Drive 1024GB                     | 1         | 1.96%   |
| Seagate ST500LT012-9WS142 500GB                    | 1         | 1.96%   |
| Seagate ST1000LM049-2GH172 1TB                     | 1         | 1.96%   |
| Seagate Backup+ Hub BK 8TB                         | 1         | 1.96%   |
| Sandisk WD Blue SN570 500GB                        | 1         | 1.96%   |
| SanDisk NVMe SSD Drive 1TB                         | 1         | 1.96%   |
| Samsung SSD PM830 2.5 7mm 128GB                    | 1         | 1.96%   |
| Samsung SSD 980 1TB                                | 1         | 1.96%   |
| Samsung SSD 883 DCT 960GB                          | 1         | 1.96%   |
| Samsung SSD 870 EVO 1TB                            | 1         | 1.96%   |
| Samsung NVMe SSD Drive 2TB                         | 1         | 1.96%   |
| Samsung NVMe SSD Drive 1TB                         | 1         | 1.96%   |
| Samsung MZALQ256HBJD-00BL2 256GB                   | 1         | 1.96%   |
| Samsung MZALQ256HAJD-000L2 256GB                   | 1         | 1.96%   |
| Samsung MZ7LN256HAJQ-000L7 256GB SSD               | 1         | 1.96%   |
| SABRENT Disk 240GB SSD                             | 1         | 1.96%   |
| Plextor PX-128S1G 128GB SSD                        | 1         | 1.96%   |
| Phison NVMe SSD Drive 960GB                        | 1         | 1.96%   |
| Micron MTFDHBA256TCK-1AS1AABHA 256GB               | 1         | 1.96%   |
| Micron 2450_MTFDKBA256TFK 256GB                    | 1         | 1.96%   |
| Micron 2400_MTFDKBA512QFM 512GB                    | 1         | 1.96%   |
| KIOXIA NVMe SSD Drive 512GB                        | 1         | 1.96%   |
| Kingston Company SNV2S250G 250GB                   | 1         | 1.96%   |
| Kingston NVMe SSD Drive 2TB                        | 1         | 1.96%   |
| KingSpec NT-256 256GB SSD                          | 1         | 1.96%   |
| Intel SSDSC2BA800G4R 800GB                         | 1         | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 44.44%  |
| Seagate | 3         | 4      | 33.33%  |
| WDC     | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 44.44%  |
| SABRENT             | 1         | 1      | 11.11%  |
| Plextor             | 1         | 1      | 11.11%  |
| KingSpec            | 1         | 1      | 11.11%  |
| Intel               | 1         | 2      | 11.11%  |
| China               | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 25        | 31     | 54.35%  |
| HDD     | 9         | 10     | 19.57%  |
| SSD     | 8         | 10     | 17.39%  |
| MMC     | 3         | 3      | 6.52%   |
| Unknown | 1         | 1      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 25        | 31     | 56.82%  |
| SATA | 14        | 18     | 31.82%  |
| MMC  | 3         | 3      | 6.82%   |
| SAS  | 2         | 3      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 8         | 9      | 50%     |
| 0.01-0.5   | 7         | 9      | 43.75%  |
| 4.01-10.0  | 1         | 2      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 42.42%  |
| 251-500        | 5         | 15.15%  |
| 1001-2000      | 5         | 15.15%  |
| 501-1000       | 5         | 15.15%  |
| 51-100         | 2         | 6.06%   |
| More than 3000 | 1         | 3.03%   |
| Unknown        | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 11        | 33.33%  |
| 21-50     | 7         | 21.21%  |
| 51-100    | 7         | 21.21%  |
| 251-500   | 3         | 9.09%   |
| 101-250   | 2         | 6.06%   |
| 1001-2000 | 2         | 6.06%   |
| Unknown   | 1         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 50%     |
| Intel SSDSC2BA800G4R 800GB      | 1         | 2      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Intel   | 1         | 2      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 2      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Detected | 23        | 38     | 65.71%  |
| Works    | 10        | 14     | 28.57%  |
| Malfunc  | 2         | 3      | 5.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 22        | 45.83%  |
| Samsung Electronics         | 8         | 16.67%  |
| SanDisk                     | 5         | 10.42%  |
| Micron Technology           | 3         | 6.25%   |
| KIOXIA                      | 3         | 6.25%   |
| SK hynix                    | 2         | 4.17%   |
| Kingston Technology Company | 2         | 4.17%   |
| Phison Electronics          | 1         | 2.08%   |
| AMD                         | 1         | 2.08%   |
| ADATA Technology            | 1         | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 3         | 6%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 3         | 6%      |
| Intel Comet Lake SATA AHCI Controller                                         | 3         | 6%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 6%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 4%      |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 2         | 4%      |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 2         | 4%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 2         | 4%      |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 2         | 4%      |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 4%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 4%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 4%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 2         | 4%      |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 2%      |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 1         | 2%      |
| Phison E12 NVMe Controller                                                    | 1         | 2%      |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 2%      |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 1         | 2%      |
| Micron 2200S NVMe SSD [Cassandra]                                             | 1         | 2%      |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 1         | 2%      |
| Kingston Company NV2 NVMe SSD E21T                                            | 1         | 2%      |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                            | 1         | 2%      |
| Intel SSD 660P Series                                                         | 1         | 2%      |
| Intel SATA Controller [RAID mode]                                             | 1         | 2%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 1         | 2%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 2%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 2%      |
| Intel Alder Lake-P SATA AHCI Controller                                       | 1         | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 2%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 2%      |
| AMD FCH SATA Controller [AHCI mode]                                           | 1         | 2%      |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                           | 1         | 2%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 24        | 51.06%  |
| SATA | 17        | 36.17%  |
| RAID | 6         | 12.77%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 93.75%  |
| AMD    | 2         | 6.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 9.38%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 6.25%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 6.25%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 6.25%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 6.25%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 3.13%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 3.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 3.13%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 3.13%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 3.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 3.13%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 3.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.13%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 3.13%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 3.13%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.13%   |
| Intel 12th Gen Core i9-12900K                 | 1         | 3.13%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 3.13%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 3.13%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 3.13%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 3.13%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 3.13%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 3.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 9         | 28.13%  |
| Intel Core i5   | 9         | 28.13%  |
| Other           | 8         | 25%     |
| Intel Core i3   | 2         | 6.25%   |
| Intel Xeon      | 1         | 3.13%   |
| Intel Celeron   | 1         | 3.13%   |
| AMD Ryzen 7 PRO | 1         | 3.13%   |
| AMD Ryzen 5     | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 12        | 37.5%   |
| 2      | 8         | 25%     |
| 8      | 5         | 15.63%  |
| 6      | 3         | 9.38%   |
| 14     | 2         | 6.25%   |
| 12     | 1         | 3.13%   |
| 10     | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 30        | 93.75%  |
| 1      | 2         | 6.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 32        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 6         | 18.75%  |
| 0x806d1    | 4         | 12.5%   |
| 0x906a3    | 3         | 9.38%   |
| 0x706e5    | 2         | 6.25%   |
| 0x506e3    | 2         | 6.25%   |
| 0x406e3    | 2         | 6.25%   |
| 0x306a9    | 2         | 6.25%   |
| 0x906ed    | 1         | 3.13%   |
| 0x906ea    | 1         | 3.13%   |
| 0x906e9    | 1         | 3.13%   |
| 0x906a4    | 1         | 3.13%   |
| 0x90672    | 1         | 3.13%   |
| 0x706a8    | 1         | 3.13%   |
| 0x40651    | 1         | 3.13%   |
| 0x306d4    | 1         | 3.13%   |
| 0x20655    | 1         | 3.13%   |
| 0x08600106 | 1         | 3.13%   |
| 0x08108109 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 9         | 28.13%  |
| Icelake          | 6         | 18.75%  |
| Alderlake Hybrid | 5         | 15.63%  |
| Skylake          | 4         | 12.5%   |
| IvyBridge        | 2         | 6.25%   |
| Zen+             | 1         | 3.13%   |
| Zen 2            | 1         | 3.13%   |
| Westmere         | 1         | 3.13%   |
| Haswell          | 1         | 3.13%   |
| Goldmont plus    | 1         | 3.13%   |
| Broadwell        | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 63.41%  |
| Nvidia | 11        | 26.83%  |
| AMD    | 4         | 9.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 9.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 7.32%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 3         | 7.32%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 4.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 4.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 4.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 4.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 4.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 4.88%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 4.88%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 2.44%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 2.44%   |
| Nvidia GP104GLM [Quadro P3000 Mobile]                                         | 1         | 2.44%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 2.44%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                            | 1         | 2.44%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 1         | 2.44%   |
| Intel HD Graphics 630                                                         | 1         | 2.44%   |
| Intel HD Graphics 5500                                                        | 1         | 2.44%   |
| Intel HD Graphics 530                                                         | 1         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 2.44%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2.44%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 2.44%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 2.44%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                              | 1         | 2.44%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 2.44%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 1         | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 2.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 53.13%  |
| Intel + Nvidia | 7         | 21.88%  |
| 1 x Nvidia     | 4         | 12.5%   |
| Intel + AMD    | 2         | 6.25%   |
| 1 x AMD        | 2         | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 26        | 81.25%  |
| Proprietary | 5         | 15.63%  |
| Unknown     | 1         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 59.38%  |
| 5.01-6.0   | 5         | 15.63%  |
| 1.01-2.0   | 3         | 9.38%   |
| 3.01-4.0   | 1         | 3.13%   |
| 2.01-3.0   | 1         | 3.13%   |
| 16.01-24.0 | 1         | 3.13%   |
| 8.01-16.0  | 1         | 3.13%   |
| 0.01-0.5   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 10        | 25%     |
| Chimei Innolux       | 5         | 12.5%   |
| LG Display           | 4         | 10%     |
| AU Optronics         | 4         | 10%     |
| Samsung Electronics  | 3         | 7.5%    |
| Sharp                | 2         | 5%      |
| Lenovo               | 2         | 5%      |
| Goldstar             | 2         | 5%      |
| Dell                 | 2         | 5%      |
| InfoVision           | 1         | 2.5%    |
| Hewlett-Packard      | 1         | 2.5%    |
| Gigabyte Technology  | 1         | 2.5%    |
| CSO                  | 1         | 2.5%    |
| BOE Technology Group | 1         | 2.5%    |
| ASUSTek Computer     | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch               | 1         | 2.44%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 2.44%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch     | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 2.44%   |
| LG Display LCD Monitor LGD0625 1920x1080 340x190mm 15.3-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 2.44%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch              | 1         | 2.44%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 1         | 2.44%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 1         | 2.44%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 2.44%   |
| Hewlett-Packard LCD Monitor Pavilion32                                | 1         | 2.44%   |
| Goldstar UltraFine GSM5B11 2560x2880 600x340mm 27.2-inch              | 1         | 2.44%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 1         | 2.44%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1         | 2.44%   |
| Dell P2419HC DELA11D 1920x1080 527x296mm 23.8-inch                    | 1         | 2.44%   |
| Dell E2218HN DELF09E 1920x1080 476x268mm 21.5-inch                    | 1         | 2.44%   |
| CSO LCD Monitor CSO1303 2160x1350 280x175mm 13.0-inch                 | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1760 1920x1080 381x214mm 17.2-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 1         | 2.44%   |
| BOE Technology Group LCD Monitor 5120x1440                            | 1         | 2.44%   |
| BOE LCD Monitor BOE0AD5 2560x1600 345x215mm 16.0-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE0A62 1920x1080 309x174mm 14.0-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE08FA 1920x1080 294x165mm 13.3-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE07D7 1920x1080 294x165mm 13.3-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                  | 1         | 2.44%   |
| BOE LCD Monitor BOE06F2 1920x1080 309x173mm 13.9-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE069A 1366x768 309x173mm 13.9-inch                  | 1         | 2.44%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                  | 1         | 2.44%   |
| AU Optronics LCD Monitor AUOD0A2 1920x1080 344x193mm 15.5-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 1         | 2.44%   |
| AU Optronics LCD Monitor 1920x1080                                    | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 18        | 48.65%  |
| 1366x768 (WXGA)   | 7         | 18.92%  |
| 3840x2160 (4K)    | 3         | 8.11%   |
| 2560x1440 (QHD)   | 3         | 8.11%   |
| Unknown           | 2         | 5.41%   |
| 5120x1440         | 1         | 2.7%    |
| 2560x1600         | 1         | 2.7%    |
| 2160x1350         | 1         | 2.7%    |
| 1920x1200 (WUXGA) | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 12        | 30.77%  |
| 15      | 7         | 17.95%  |
| 14      | 5         | 12.82%  |
| 17      | 3         | 7.69%   |
| 27      | 2         | 5.13%   |
| 24      | 2         | 5.13%   |
| 23      | 2         | 5.13%   |
| Unknown | 2         | 5.13%   |
| 72      | 1         | 2.56%   |
| 31      | 1         | 2.56%   |
| 21      | 1         | 2.56%   |
| 16      | 1         | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 55.26%  |
| 501-600     | 5         | 13.16%  |
| 201-300     | 4         | 10.53%  |
| 351-400     | 3         | 7.89%   |
| Unknown     | 2         | 5.26%   |
| 601-700     | 1         | 2.63%   |
| 401-500     | 1         | 2.63%   |
| 1501-2000   | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 26        | 81.25%  |
| 16/10   | 4         | 12.5%   |
| Unknown | 2         | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 33.33%  |
| 101-110        | 7         | 17.95%  |
| 71-80          | 4         | 10.26%  |
| 201-250        | 4         | 10.26%  |
| 121-130        | 3         | 7.69%   |
| 301-350        | 2         | 5.13%   |
| Unknown        | 2         | 5.13%   |
| More than 1000 | 1         | 2.56%   |
| 351-500        | 1         | 2.56%   |
| 251-300        | 1         | 2.56%   |
| 111-120        | 1         | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 41.67%  |
| 101-120       | 9         | 25%     |
| 161-240       | 5         | 13.89%  |
| 51-100        | 3         | 8.33%   |
| More than 240 | 2         | 5.56%   |
| Unknown       | 2         | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 72.73%  |
| 2     | 7         | 21.21%  |
| 5     | 1         | 3.03%   |
| 4     | 1         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 56%     |
| Realtek Semiconductor | 16        | 32%     |
| Qualcomm Atheros      | 3         | 6%      |
| Ralink Technology     | 1         | 2%      |
| DisplayLink           | 1         | 2%      |
| Broadcom              | 1         | 2%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 12.9%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 6.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 6.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 4.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.84%   |
| Intel Wireless 8260                                               | 2         | 3.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 3.23%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 3.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.61%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.61%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.61%   |
| Intel Wireless 7265                                               | 1         | 1.61%   |
| Intel Wireless 3160                                               | 1         | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.61%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.61%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.61%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.61%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1         | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.61%   |
| DisplayLink Dell D3100 Docking Station                            | 1         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 81.25%  |
| Realtek Semiconductor | 3         | 9.38%   |
| Ralink Technology     | 1         | 3.13%   |
| Qualcomm Atheros      | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                          | 4         | 12.5%   |
| Intel Alder Lake-P PCH CNVi WiFi                           | 3         | 9.38%   |
| Intel Wireless 8260                                        | 2         | 6.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 2         | 6.25%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 6.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 2         | 6.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.13%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 1         | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1         | 3.13%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                 | 1         | 3.13%   |
| Intel Wireless 7265                                        | 1         | 3.13%   |
| Intel Wireless 3160                                        | 1         | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 3.13%   |
| Intel Centrino Wireless-N 2230                             | 1         | 3.13%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 1         | 3.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 51.72%  |
| Intel                 | 11        | 37.93%  |
| Qualcomm Atheros      | 2         | 6.9%    |
| DisplayLink           | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 26.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 10%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 10%     |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 3.33%   |
| Intel Ethernet Controller I225-V                                  | 1         | 3.33%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 3.33%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.33%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 3.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 3.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.33%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 3.33%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 3.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.33%   |
| DisplayLink Dell D3100 Docking Station                            | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 54.39%  |
| Ethernet | 26        | 45.61%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 74.29%  |
| Ethernet | 9         | 25.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 78.13%  |
| 1     | 7         | 21.88%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 75%     |
| Yes  | 8         | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 79.31%  |
| Realtek Semiconductor | 2         | 6.9%    |
| Broadcom              | 2         | 6.9%    |
| IMC Networks          | 1         | 3.45%   |
| ASUSTek Computer      | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 7         | 24.14%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 5         | 17.24%  |
| Intel Bluetooth wireless interface             | 4         | 13.79%  |
| Intel AX210 Bluetooth                          | 2         | 6.9%    |
| Intel AX200 Bluetooth                          | 2         | 6.9%    |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 3.45%   |
| Realtek Bluetooth Radio                        | 1         | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 3.45%   |
| Intel Bluetooth Device                         | 1         | 3.45%   |
| IMC Networks Bluetooth Radio                   | 1         | 3.45%   |
| Broadcom HP Portable SoftSailing               | 1         | 3.45%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 3.45%   |
| ASUS ASUS USB-BT500                            | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 30        | 57.69%  |
| Nvidia                  | 10        | 19.23%  |
| Texas Instruments       | 3         | 5.77%   |
| AMD                     | 3         | 5.77%   |
| Sony                    | 1         | 1.92%   |
| Realtek Semiconductor   | 1         | 1.92%   |
| LG Electronics          | 1         | 1.92%   |
| Hewlett-Packard         | 1         | 1.92%   |
| Corsair                 | 1         | 1.92%   |
| BEHRINGER International | 1         | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 7.14%   |
| Intel Comet Lake PCH-LP cAVS                                            | 4         | 7.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 4         | 7.14%   |
| Nvidia GA106 High Definition Audio Controller                           | 3         | 5.36%   |
| Texas Instruments PCM2902 Audio Codec                                   | 2         | 3.57%   |
| Nvidia TU116 High Definition Audio Controller                           | 2         | 3.57%   |
| Intel Sunrise Point-LP HD Audio                                         | 2         | 3.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller               | 2         | 3.57%   |
| Intel CM238 HD Audio Controller                                         | 2         | 3.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 2         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                              | 2         | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 2         | 3.57%   |
| AMD Family 17h/19h HD Audio Controller                                  | 2         | 3.57%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                       | 1         | 1.79%   |
| Sony DualSense wireless controller (PS5)                                | 1         | 1.79%   |
| Realtek Semiconductor USB Audio                                         | 1         | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 1.79%   |
| Nvidia GP106 High Definition Audio Controller                           | 1         | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                           | 1         | 1.79%   |
| Nvidia GA104 High Definition Audio Controller                           | 1         | 1.79%   |
| Nvidia GA102 High Definition Audio Controller                           | 1         | 1.79%   |
| LG Electronics USB Audio                                                | 1         | 1.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 1         | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                   | 1         | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 1         | 1.79%   |
| Intel Broadwell-U Audio Controller                                      | 1         | 1.79%   |
| Intel Alder Lake-S HD Audio Controller                                  | 1         | 1.79%   |
| Intel 8 Series HD Audio Controller                                      | 1         | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                | 1         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 1         | 1.79%   |
| Hewlett-Packard USB Audio                                               | 1         | 1.79%   |
| Corsair HS65 SURROUND                                                   | 1         | 1.79%   |
| BEHRINGER International UMC404HD 192k                                   | 1         | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 1         | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 1         | 1.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 3         | 30%     |
| Samsung Electronics | 3         | 30%     |
| Kingston            | 2         | 20%     |
| Smart               | 1         | 10%     |
| Elpida              | 1         | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Smart RAM SF564128CJ8NWMNSEG 4096MB SODIMM DDR3 1600MT/s     | 1         | 9.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 9.09%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 9.09%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 9.09%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 9.09%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 9.09%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 9.09%   |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 9.09%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2667MT/s        | 1         | 9.09%   |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 9.09%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 1         | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 66.67%  |
| DDR3   | 2         | 22.22%  |
| LPDDR5 | 1         | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 8         | 88.89%  |
| Row Of Chips | 1         | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 4         | 40%     |
| 16384 | 3         | 30%     |
| 4096  | 2         | 20%     |
| 2048  | 1         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 3         | 30%     |
| 3200  | 2         | 20%     |
| 2133  | 2         | 20%     |
| 1600  | 2         | 20%     |
| 6400  | 1         | 10%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3210 Series | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 21.88%  |
| Microdia                               | 3         | 9.38%   |
| IMC Networks                           | 3         | 9.38%   |
| Sunplus Innovation Technology          | 2         | 6.25%   |
| Realtek Semiconductor                  | 2         | 6.25%   |
| Bison Electronics                      | 2         | 6.25%   |
| Syntek                                 | 1         | 3.13%   |
| Suyin                                  | 1         | 3.13%   |
| Sonix Technology                       | 1         | 3.13%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 3.13%   |
| Samsung Electronics                    | 1         | 3.13%   |
| Remo Tech                              | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Microsoft                              | 1         | 3.13%   |
| Luxvisions Innotech Limited            | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| LG Electronics                         | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |
| 8SSC21D67422V1SR28902JL                | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 2         | 6.25%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 6.25%   |
| Chicony Integrated Camera                                      | 2         | 6.25%   |
| Syntek Integrated Camera                                       | 1         | 3.13%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 3.13%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 3.13%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                | 1         | 3.13%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 3.13%   |
| Remo Tech OBSBOT Tiny 4K                                       | 1         | 3.13%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 3.13%   |
| Realtek Integrated Webcam_HD                                   | 1         | 3.13%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 3.13%   |
| Microsoft LifeCam VX-2000                                      | 1         | 3.13%   |
| Microdia 1.3 MPixel Integrated Webcam                          | 1         | 3.13%   |
| Luxvisions Innotech Limited Integrated Camera                  | 1         | 3.13%   |
| Lite-On HP HD Camera                                           | 1         | 3.13%   |
| LG LG UltraFine Display Camera                                 | 1         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 3.13%   |
| IMC Networks USB Camera                                        | 1         | 3.13%   |
| IMC Networks Integrated Camera                                 | 1         | 3.13%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 3.13%   |
| Chicony ThinkPad T490 Webcam                                   | 1         | 3.13%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 3.13%   |
| Chicony HP HD Camera                                           | 1         | 3.13%   |
| Chicony HD Webcam                                              | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.13%   |
| Bison Integrated Camera                                        | 1         | 3.13%   |
| Bison BisonCam, NB Pro                                         | 1         | 3.13%   |
| 8SSC21D67422V1SR28902JL Integrated RGB Camera                  | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 44.44%  |
| Validity Sensors           | 2         | 22.22%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |
| Samsung Electronics        | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 22.22%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 11.11%  |
| Validity Sensors VFS491                                   | 1         | 11.11%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 18        | 56.25%  |
| 1     | 13        | 40.63%  |
| 2     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 52.94%  |
| Multimedia controller | 3         | 17.65%  |
| Graphics card         | 2         | 11.76%  |
| Net/wireless          | 1         | 5.88%   |
| Chipcard              | 1         | 5.88%   |
| Card reader           | 1         | 5.88%   |

