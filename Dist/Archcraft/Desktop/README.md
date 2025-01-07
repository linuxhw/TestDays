Archcraft - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Archcraft.

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

Total: 29

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock   | X570 Taichi Razer Editio... | [6d2e60df3c](https://linux-hardware.org/?probe=6d2e60df3c) | Nov 12, 2024 |
| Gigabyte | X470 AORUS GAMING 7 WIFI... | [ce62db7f6c](https://linux-hardware.org/?probe=ce62db7f6c) | Nov 09, 2024 |
| MSI      | MPG X570 GAMING PRO CARB... | [b97d8e4203](https://linux-hardware.org/?probe=b97d8e4203) | Jun 23, 2024 |
| ASUSTek  | TUF Gaming X570-PLUS_BR     | [86c5400c85](https://linux-hardware.org/?probe=86c5400c85) | May 13, 2024 |
| ASUSTek  | TUF Gaming X570-PLUS        | [f9daac6faa](https://linux-hardware.org/?probe=f9daac6faa) | May 04, 2024 |
| ASUSTek  | TUF Gaming B550M-E          | [518e259c3c](https://linux-hardware.org/?probe=518e259c3c) | Dec 23, 2023 |
| HP       | 18E4                        | [db6b92644b](https://linux-hardware.org/?probe=db6b92644b) | Dec 12, 2023 |
| Lenovo   | 3706 SDK0J40700 WIN 3258... | [82b916eb4a](https://linux-hardware.org/?probe=82b916eb4a) | Nov 24, 2023 |
| Dell     | 0KP561                      | [90055b146d](https://linux-hardware.org/?probe=90055b146d) | Sep 06, 2023 |
| ASUSTek  | K30BF_M32BF_A_F_K31BF_6     | [08d5b71848](https://linux-hardware.org/?probe=08d5b71848) | Jul 22, 2023 |
| Gigabyte | B650 AORUS ELITE AX         | [e59862f167](https://linux-hardware.org/?probe=e59862f167) | Jul 05, 2023 |
| Lenovo   | Win8 Pro DPK TPG            | [0efc49ca3a](https://linux-hardware.org/?probe=0efc49ca3a) | Jun 28, 2023 |
| Lenovo   | Win8 Pro DPK TPG            | [72514911c8](https://linux-hardware.org/?probe=72514911c8) | Jun 28, 2023 |
| MSI      | A320M-A PRO                 | [09b5be9c77](https://linux-hardware.org/?probe=09b5be9c77) | Jun 24, 2023 |
| ASUSTek  | P8H61-M LX R2.0             | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| ASRock   | B550M Pro4                  | [8529d01687](https://linux-hardware.org/?probe=8529d01687) | May 27, 2023 |
| ASRock   | B550M Pro4                  | [8301ca5155](https://linux-hardware.org/?probe=8301ca5155) | May 27, 2023 |
| ASUSTek  | PRIME X470-PRO              | [f9df27503f](https://linux-hardware.org/?probe=f9df27503f) | Feb 03, 2023 |
| ASUSTek  | H110M-E/M.2                 | [82584d7e83](https://linux-hardware.org/?probe=82584d7e83) | Dec 20, 2022 |
| ASUSTek  | H110M-E/M.2                 | [fb73fb5efc](https://linux-hardware.org/?probe=fb73fb5efc) | Oct 18, 2022 |
| ASUSTek  | H110M-E/M.2                 | [77fd87ca91](https://linux-hardware.org/?probe=77fd87ca91) | Oct 18, 2022 |
| Gigabyte | B550I AORUS PRO AX          | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Gigabyte | F2A68HM-DS2                 | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| Lenovo   | 3111 SDK0J40705 WIN 3425... | [543fe6b6a7](https://linux-hardware.org/?probe=543fe6b6a7) | Aug 07, 2022 |
| MSI      | MAG B550 TOMAHAWK           | [bede15789b](https://linux-hardware.org/?probe=bede15789b) | Jun 02, 2022 |
| ECS      | G31T-M                      | [3820396d91](https://linux-hardware.org/?probe=3820396d91) | Jan 29, 2022 |
| ASRock   | H97M Pro4                   | [232f2dad91](https://linux-hardware.org/?probe=232f2dad91) | Dec 15, 2021 |
| ASUSTek  | ROG DOMINUS EXTREME         | [0adc8fc04d](https://linux-hardware.org/?probe=0adc8fc04d) | Oct 12, 2021 |
| ASUSTek  | ROG DOMINUS EXTREME         | [b977489e9c](https://linux-hardware.org/?probe=b977489e9c) | Oct 12, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Archcraft Rolling | 19       | 79.17%  |
| Archcraft         | 5        | 20.83%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Archcraft | 24       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 6.3.9-arch1-1         | 2        | 8%      |
| 5.19.13-arch1-1       | 2        | 8%      |
| 6.9.7-arch1-1         | 1        | 4%      |
| 6.8.9-zen1-2-zen      | 1        | 4%      |
| 6.8.9-arch1-1         | 1        | 4%      |
| 6.8.4-arch1-1         | 1        | 4%      |
| 6.6.7-arch1-1         | 1        | 4%      |
| 6.6.6-arch1-1         | 1        | 4%      |
| 6.6.1-arch1-1         | 1        | 4%      |
| 6.4.4-zen1-1-zen      | 1        | 4%      |
| 6.4.12-arch1-1        | 1        | 4%      |
| 6.4.1-arch2-1         | 1        | 4%      |
| 6.3.8-arch1-1         | 1        | 4%      |
| 6.3.4-arch1-1         | 1        | 4%      |
| 6.11.1-arch1-1        | 1        | 4%      |
| 6.1.9-x64v1-xanmod1-1 | 1        | 4%      |
| 6.0.12-arch1-1        | 1        | 4%      |
| 5.19.9-arch1-1        | 1        | 4%      |
| 5.18.16-arch1-1       | 1        | 4%      |
| 5.18.0-arch1-1        | 1        | 4%      |
| 5.16.3-arch1-1        | 1        | 4%      |
| 5.15.7-zen1-1-zen     | 1        | 4%      |
| 5.14.10-arch1-1       | 1        | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.8.9   | 2        | 8%      |
| 6.3.9   | 2        | 8%      |
| 5.19.13 | 2        | 8%      |
| 6.9.7   | 1        | 4%      |
| 6.8.4   | 1        | 4%      |
| 6.6.7   | 1        | 4%      |
| 6.6.6   | 1        | 4%      |
| 6.6.1   | 1        | 4%      |
| 6.4.4   | 1        | 4%      |
| 6.4.12  | 1        | 4%      |
| 6.4.1   | 1        | 4%      |
| 6.3.8   | 1        | 4%      |
| 6.3.4   | 1        | 4%      |
| 6.11.1  | 1        | 4%      |
| 6.1.9   | 1        | 4%      |
| 6.0.12  | 1        | 4%      |
| 5.19.9  | 1        | 4%      |
| 5.18.16 | 1        | 4%      |
| 5.18.0  | 1        | 4%      |
| 5.16.3  | 1        | 4%      |
| 5.15.7  | 1        | 4%      |
| 5.14.10 | 1        | 4%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3     | 4        | 16%     |
| 6.8     | 3        | 12%     |
| 6.6     | 3        | 12%     |
| 6.4     | 3        | 12%     |
| 5.19    | 3        | 12%     |
| 5.18    | 2        | 8%      |
| 6.9     | 1        | 4%      |
| 6.11    | 1        | 4%      |
| 6.1     | 1        | 4%      |
| 6.0     | 1        | 4%      |
| 5.16    | 1        | 4%      |
| 5.15    | 1        | 4%      |
| 5.14    | 1        | 4%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 24       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| XFCE    | 7        | 29.17%  |
| openbox | 6        | 25%     |
| bspwm   | 4        | 16.67%  |
| KDE5    | 2        | 8.33%   |
| Unknown | 2        | 8.33%   |
| qtile   | 1        | 4.17%   |
| i3      | 1        | 4.17%   |
| awesome | 1        | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 20       | 83.33%  |
| Wayland | 2        | 8.33%   |
| Unknown | 2        | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 16       | 66.67%  |
| Unknown | 6        | 25%     |
| LightDM | 2        | 8.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 18       | 75%     |
| en_GB   | 2        | 8.33%   |
| pt_BR   | 1        | 4.17%   |
| es_MX   | 1        | 4.17%   |
| en_IN   | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 16       | 66.67%  |
| BIOS | 8        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 16       | 66.67%  |
| Btrfs | 5        | 20.83%  |
| Xfs   | 3        | 12.5%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 19       | 79.17%  |
| Unknown | 4        | 16.67%  |
| MBR     | 1        | 4.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 70.83%  |
| Yes       | 7        | 29.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 54.17%  |
| Yes       | 11       | 45.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 33.33%  |
| Gigabyte Technology | 4        | 16.67%  |
| MSI                 | 3        | 12.5%   |
| Lenovo              | 3        | 12.5%   |
| ASRock              | 3        | 12.5%   |
| Hewlett-Packard     | 1        | 4.17%   |
| ECS                 | 1        | 4.17%   |
| Dell                | 1        | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| MSI MS-7C91                             | 1        | 4.17%   |
| MSI MS-7C51                             | 1        | 4.17%   |
| MSI MS-7B93                             | 1        | 4.17%   |
| Lenovo ThinkCentre M710q 10MR0047US     | 1        | 4.17%   |
| Lenovo ThinkCentre Edge72 3484HPU       | 1        | 4.17%   |
| Lenovo IdeaCentre 510A-15ARR 90J00061US | 1        | 4.17%   |
| HP EliteDesk 800 G1 TWR                 | 1        | 4.17%   |
| Gigabyte X470 AORUS GAMING 7 WIFI       | 1        | 4.17%   |
| Gigabyte F2A68HM-DS2                    | 1        | 4.17%   |
| Gigabyte B650 AORUS ELITE AX            | 1        | 4.17%   |
| Gigabyte B550I AORUS PRO AX             | 1        | 4.17%   |
| ECS G31T-M                              | 1        | 4.17%   |
| Dell OptiPlex 330                       | 1        | 4.17%   |
| ASUS TUF Gaming X570-PLUS_BR            | 1        | 4.17%   |
| ASUS TUF Gaming X570-PLUS               | 1        | 4.17%   |
| ASUS TUF Gaming B550M-E                 | 1        | 4.17%   |
| ASUS ROG DOMINUS EXTREME                | 1        | 4.17%   |
| ASUS PRIME X470-PRO                     | 1        | 4.17%   |
| ASUS P8H61-M LX R2.0                    | 1        | 4.17%   |
| ASUS K30BF_M32BF_A_F_K31BF_6            | 1        | 4.17%   |
| ASUS H110M-E/M.2                        | 1        | 4.17%   |
| ASRock X570 Taichi Razer Edition        | 1        | 4.17%   |
| ASRock H97M Pro4                        | 1        | 4.17%   |
| ASRock B550M Pro4                       | 1        | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS TUF             | 3        | 12.5%   |
| Lenovo ThinkCentre   | 2        | 8.33%   |
| MSI MS-7C91          | 1        | 4.17%   |
| MSI MS-7C51          | 1        | 4.17%   |
| MSI MS-7B93          | 1        | 4.17%   |
| Lenovo IdeaCentre    | 1        | 4.17%   |
| HP EliteDesk         | 1        | 4.17%   |
| Gigabyte X470        | 1        | 4.17%   |
| Gigabyte F2A68HM-DS2 | 1        | 4.17%   |
| Gigabyte B650        | 1        | 4.17%   |
| Gigabyte B550I       | 1        | 4.17%   |
| ECS G31T-M           | 1        | 4.17%   |
| Dell OptiPlex        | 1        | 4.17%   |
| ASUS ROG             | 1        | 4.17%   |
| ASUS PRIME           | 1        | 4.17%   |
| ASUS P8H61-M         | 1        | 4.17%   |
| ASUS K30BF           | 1        | 4.17%   |
| ASUS H110M-E         | 1        | 4.17%   |
| ASRock X570          | 1        | 4.17%   |
| ASRock H97M          | 1        | 4.17%   |
| ASRock B550M         | 1        | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 5        | 20.83%  |
| 2020 | 4        | 16.67%  |
| 2018 | 2        | 8.33%   |
| 2014 | 2        | 8.33%   |
| 2012 | 2        | 8.33%   |
| 2007 | 2        | 8.33%   |
| 2023 | 1        | 4.17%   |
| 2022 | 1        | 4.17%   |
| 2021 | 1        | 4.17%   |
| 2017 | 1        | 4.17%   |
| 2016 | 1        | 4.17%   |
| 2015 | 1        | 4.17%   |
| 2013 | 1        | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 24       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 24       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 7        | 29.17%  |
| 4.01-8.0    | 5        | 20.83%  |
| 64.01-256.0 | 3        | 12.5%   |
| 16.01-24.0  | 3        | 12.5%   |
| 8.01-16.0   | 3        | 12.5%   |
| 3.01-4.0    | 2        | 8.33%   |
| 2.01-3.0    | 1        | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 8        | 32%     |
| 3.01-4.0  | 4        | 16%     |
| 2.01-3.0  | 4        | 16%     |
| 1.01-2.0  | 4        | 16%     |
| 8.01-16.0 | 4        | 16%     |
| 0.51-1.0  | 1        | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 25%     |
| 3      | 5        | 20.83%  |
| 2      | 5        | 20.83%  |
| 4      | 4        | 16.67%  |
| 5      | 2        | 8.33%   |
| 8      | 1        | 4.17%   |
| 7      | 1        | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 87.5%   |
| Yes       | 3        | 12.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 54.17%  |
| No        | 11       | 45.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 50%     |
| No        | 12       | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| USA      | 10       | 41.67%  |
| Brazil   | 4        | 16.67%  |
| UK       | 2        | 8.33%   |
| Mexico   | 2        | 8.33%   |
| Thailand | 1        | 4.17%   |
| Slovakia | 1        | 4.17%   |
| Poland   | 1        | 4.17%   |
| India    | 1        | 4.17%   |
| Hungary  | 1        | 4.17%   |
| Czechia  | 1        | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Theodore              | 1        | 4.17%   |
| Tábor                | 1        | 4.17%   |
| Sparta                | 1        | 4.17%   |
| Sao Paulo             | 1        | 4.17%   |
| Paulista              | 1        | 4.17%   |
| Osasco                | 1        | 4.17%   |
| Milton Keynes         | 1        | 4.17%   |
| Mesa                  | 1        | 4.17%   |
| Manchester            | 1        | 4.17%   |
| Guadalajara           | 1        | 4.17%   |
| Gdansk                | 1        | 4.17%   |
| Frisco                | 1        | 4.17%   |
| Fort Gibson           | 1        | 4.17%   |
| Dallas                | 1        | 4.17%   |
| Clio                  | 1        | 4.17%   |
| Ciudad Nezahualcoyotl | 1        | 4.17%   |
| Chapecó              | 1        | 4.17%   |
| Čadca                | 1        | 4.17%   |
| Budapest              | 1        | 4.17%   |
| Brookville            | 1        | 4.17%   |
| Bengaluru             | 1        | 4.17%   |
| Bangkok               | 1        | 4.17%   |
| Atlanta               | 1        | 4.17%   |
| Abilene               | 1        | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 9        | 14     | 16.07%  |
| WDC                       | 8        | 10     | 14.29%  |
| Sandisk                   | 7        | 9      | 12.5%   |
| Samsung Electronics       | 5        | 6      | 8.93%   |
| Kingston                  | 4        | 8      | 7.14%   |
| Hitachi                   | 3        | 3      | 5.36%   |
| Toshiba                   | 2        | 2      | 3.57%   |
| Phison Electronics        | 2        | 2      | 3.57%   |
| Intel                     | 2        | 5      | 3.57%   |
| A-DATA Technology         | 2        | 3      | 3.57%   |
| Unknown                   | 1        | 1      | 1.79%   |
| SUNEAST                   | 1        | 1      | 1.79%   |
| SPCC                      | 1        | 1      | 1.79%   |
| ROG                       | 1        | 1      | 1.79%   |
| Patriot                   | 1        | 1      | 1.79%   |
| Micron/Crucial Technology | 1        | 1      | 1.79%   |
| MaxDigital                | 1        | 1      | 1.79%   |
| Crucial                   | 1        | 1      | 1.79%   |
| China                     | 1        | 2      | 1.79%   |
| Apacer                    | 1        | 1      | 1.79%   |
| ADATA Technology          | 1        | 1      | 1.79%   |
| Unknown                   | 1        | 1      | 1.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 4        | 6.25%   |
| Kingston SA400S37480G 480GB SSD                     | 2        | 3.13%   |
| WDC WDS200T2B0B 2TB SSD                             | 1        | 1.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1        | 1.56%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1        | 1.56%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1        | 1.56%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1        | 1.56%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1        | 1.56%   |
| WDC WD20 EARX-00PASB0 2TB                           | 1        | 1.56%   |
| WDC WD10EZEX-22RKKA0 1TB                            | 1        | 1.56%   |
| WDC WD10EZEX-21M2NA0 1TB                            | 1        | 1.56%   |
| WDC WD10EARS-00MVWB0 1TB                            | 1        | 1.56%   |
| Unknown NVMe SSD Drive 2TB                          | 1        | 1.56%   |
| Toshiba DT01ACA200 2TB                              | 1        | 1.56%   |
| Toshiba DT01ACA100 1TB                              | 1        | 1.56%   |
| SUNEAST SSD SE800 128GB                             | 1        | 1.56%   |
| SPCC M.2 PCIe SSD 4TB                               | 1        | 1.56%   |
| Seagate ST6000DM003-2CY186 6TB                      | 1        | 1.56%   |
| Seagate ST500DM002-1BD142 500GB                     | 1        | 1.56%   |
| Seagate ST4000DM004-2CV104 4TB                      | 1        | 1.56%   |
| Seagate ST3500410AS 500GB                           | 1        | 1.56%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1        | 1.56%   |
| Seagate ST3160815AS 160GB                           | 1        | 1.56%   |
| Seagate ST31500341AS 1TB                            | 1        | 1.56%   |
| Seagate ST3000DM003-1F216N 3TB                      | 1        | 1.56%   |
| Seagate ST2000DM 008-2FR102 2TB                     | 1        | 1.56%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 1.56%   |
| Seagate Expansion Desk 5TB                          | 1        | 1.56%   |
| Sandisk WD_BLACK SN770 1TB                          | 1        | 1.56%   |
| Sandisk WD Green SN350 500GB 2G0C                   | 1        | 1.56%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 1        | 1.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 1        | 1.56%   |
| SanDisk SSD PLUS 240 GB                             | 1        | 1.56%   |
| SanDisk SDSSDA240G 240GB                            | 1        | 1.56%   |
| SanDisk NVMe SSD Drive 1TB                          | 1        | 1.56%   |
| SanDisk Extreme 55AE 2TB SSD                        | 1        | 1.56%   |
| Samsung SSD 970 EVO Plus 1TB                        | 1        | 1.56%   |
| ROG ESD-S1C 1024GB                                  | 1        | 1.56%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 1        | 1.56%   |
| Phison E12 NVMe Controller 480GB                    | 1        | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor     | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| Seagate    | 9        | 14     | 42.86%  |
| WDC        | 6        | 8      | 28.57%  |
| Hitachi    | 3        | 3      | 14.29%  |
| Toshiba    | 2        | 2      | 9.52%   |
| MaxDigital | 1        | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| SanDisk           | 3        | 4      | 17.65%  |
| Kingston          | 3        | 5      | 17.65%  |
| WDC               | 2        | 2      | 11.76%  |
| A-DATA Technology | 2        | 3      | 11.76%  |
| SUNEAST           | 1        | 1      | 5.88%   |
| Patriot           | 1        | 1      | 5.88%   |
| Intel             | 1        | 1      | 5.88%   |
| Crucial           | 1        | 1      | 5.88%   |
| China             | 1        | 2      | 5.88%   |
| Apacer            | 1        | 1      | 5.88%   |
| Unknown           | 1        | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 13       | 24     | 33.33%  |
| HDD     | 13       | 28     | 33.33%  |
| SSD     | 12       | 22     | 30.77%  |
| Unknown | 1        | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 18       | 44     | 51.43%  |
| NVMe | 13       | 24     | 37.14%  |
| SAS  | 4        | 7      | 11.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 14       | 28     | 48.28%  |
| 0.51-1.0   | 6        | 11     | 20.69%  |
| 1.01-2.0   | 4        | 6      | 13.79%  |
| 3.01-4.0   | 2        | 2      | 6.9%    |
| 4.01-10.0  | 2        | 2      | 6.9%    |
| 2.01-3.0   | 1        | 1      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 6        | 25%     |
| 251-500        | 4        | 16.67%  |
| 501-1000       | 4        | 16.67%  |
| More than 3000 | 3        | 12.5%   |
| 1001-2000      | 3        | 12.5%   |
| Unknown        | 2        | 8.33%   |
| 2001-3000      | 1        | 4.17%   |
| 51-100         | 1        | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 5        | 20.83%  |
| 101-250        | 4        | 16.67%  |
| 51-100         | 4        | 16.67%  |
| 251-500        | 3        | 12.5%   |
| 21-50          | 3        | 12.5%   |
| 1001-2000      | 2        | 8.33%   |
| Unknown        | 2        | 8.33%   |
| More than 3000 | 1        | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB  | 1        | 1      | 20%     |
| WDC WD5000AAKX-60U6AA0 500GB  | 1        | 1      | 20%     |
| WDC WD10EARS-00MVWB0 1TB      | 1        | 1      | 20%     |
| MaxDigital MD4000GBDS 4TB     | 1        | 1      | 20%     |
| Hitachi HTS547550A9E384 500GB | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor     | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| WDC        | 3        | 3      | 60%     |
| MaxDigital | 1        | 1      | 20%     |
| Hitachi    | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor     | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| WDC        | 3        | 3      | 60%     |
| MaxDigital | 1        | 1      | 20%     |
| Hitachi    | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 5      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500410AS 500GB | 1        | 2      | 50%     |
| Seagate ST31500341AS 1TB  | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 19       | 44     | 57.58%  |
| Detected | 9        | 22     | 27.27%  |
| Malfunc  | 4        | 5      | 12.12%  |
| Failed   | 1        | 4      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 15       | 34.09%  |
| Intel                       | 9        | 20.45%  |
| Samsung Electronics         | 5        | 11.36%  |
| SanDisk                     | 4        | 9.09%   |
| Kingston Technology Company | 3        | 6.82%   |
| Phison Electronics          | 2        | 4.55%   |
| ASMedia Technology          | 2        | 4.55%   |
| Solidigm                    | 1        | 2.27%   |
| Micron/Crucial Technology   | 1        | 2.27%   |
| INNOGRIT                    | 1        | 2.27%   |
| ADATA Technology            | 1        | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9        | 17.31%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 9.62%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 7.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 3.85%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 2        | 3.85%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 3.85%   |
| Solidigm P44 Pro NVMe SSD [Hollywood Beach]                                    | 1        | 1.92%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1        | 1.92%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1        | 1.92%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 1.92%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 1        | 1.92%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1        | 1.92%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.92%   |
| Phison E12 NVMe Controller                                                     | 1        | 1.92%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 1.92%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 1        | 1.92%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 1        | 1.92%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 1        | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 1.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.92%   |
| Intel Optane SSD 900P Series                                                   | 1        | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 1.92%   |
| Intel C620 Series Chipset Family IDE Redirection                               | 1        | 1.92%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 1.92%   |
| INNOGRIT NVMe SSD Controller IG5236                                            | 1        | 1.92%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1        | 1.92%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 1        | 1.92%   |
| AMD 600 Series Chipset SATA Controller                                         | 1        | 1.92%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 57.5%   |
| NVMe | 13       | 32.5%   |
| IDE  | 3        | 7.5%    |
| RAID | 1        | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 15       | 62.5%   |
| Intel  | 9        | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 3800X 8-Core Processor             | 2        | 8.33%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 8.33%   |
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 2        | 8.33%   |
| Intel Xeon W-3175X CPU @ 3.10GHz               | 1        | 4.17%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 4.17%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 4.17%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 4.17%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1        | 4.17%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 4.17%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 4.17%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz           | 1        | 4.17%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1        | 4.17%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 4.17%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 4.17%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 4.17%   |
| AMD Ryzen 7 7700X 8-Core Processor             | 1        | 4.17%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 4.17%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 4.17%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 4.17%   |
| AMD Ryzen 5 4600G with Radeon Graphics         | 1        | 4.17%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 1        | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| AMD Ryzen 7      | 5        | 20.83%  |
| AMD Ryzen 5      | 5        | 20.83%  |
| Intel Core i5    | 4        | 16.67%  |
| AMD Ryzen 9      | 3        | 12.5%   |
| Intel Core 2 Duo | 2        | 8.33%   |
| AMD A10          | 2        | 8.33%   |
| Intel Xeon       | 1        | 4.17%   |
| Intel Core i7    | 1        | 4.17%   |
| Intel Core i3    | 1        | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 25%     |
| 8      | 5        | 20.83%  |
| 2      | 5        | 20.83%  |
| 6      | 4        | 16.67%  |
| 12     | 2        | 8.33%   |
| 28     | 1        | 4.17%   |
| 16     | 1        | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 18       | 75%     |
| 1      | 6        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 24       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 50%     |
| 0x906e9    | 1        | 4.17%   |
| 0x6fd      | 1        | 4.17%   |
| 0x506e3    | 1        | 4.17%   |
| 0x50654    | 1        | 4.17%   |
| 0x306c3    | 1        | 4.17%   |
| 0x0a601203 | 1        | 4.17%   |
| 0x0a201016 | 1        | 4.17%   |
| 0x0a201009 | 1        | 4.17%   |
| 0x08701030 | 1        | 4.17%   |
| 0x08701021 | 1        | 4.17%   |
| 0x08108102 | 1        | 4.17%   |
| 0x06003106 | 1        | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 7        | 29.17%  |
| Zen 3       | 3        | 12.5%   |
| Zen+        | 2        | 8.33%   |
| Steamroller | 2        | 8.33%   |
| Skylake     | 2        | 8.33%   |
| Haswell     | 2        | 8.33%   |
| Core        | 2        | 8.33%   |
| SandyBridge | 1        | 4.17%   |
| KabyLake    | 1        | 4.17%   |
| IvyBridge   | 1        | 4.17%   |
| Unknown     | 1        | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 13       | 48.15%  |
| Nvidia | 9        | 33.33%  |
| Intel  | 5        | 18.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 10%     |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 6.67%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 2        | 6.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 6.67%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 6.67%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 3.33%   |
| Nvidia TU102 [TITAN RTX]                                                    | 1        | 3.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 3.33%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 3.33%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 3.33%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.33%   |
| Intel HD Graphics 630                                                       | 1        | 3.33%   |
| Intel HD Graphics 530                                                       | 1        | 3.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 3.33%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 3.33%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 1        | 3.33%   |
| AMD Raphael                                                                 | 1        | 3.33%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 3.33%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 3.33%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 9        | 37.5%   |
| 1 x Nvidia     | 7        | 29.17%  |
| 2 x AMD        | 3        | 12.5%   |
| 1 x Intel      | 2        | 8.33%   |
| 2 x Intel      | 1        | 4.17%   |
| Intel + Nvidia | 1        | 4.17%   |
| AMD + Nvidia   | 1        | 4.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 17       | 68%     |
| Proprietary | 8        | 32%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 7        | 28%     |
| Unknown    | 6        | 24%     |
| 16.01-24.0 | 3        | 12%     |
| 1.01-2.0   | 3        | 12%     |
| 8.01-16.0  | 2        | 8%      |
| 0.51-1.0   | 2        | 8%      |
| 5.01-6.0   | 1        | 4%      |
| 3.01-4.0   | 1        | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 6        | 20.69%  |
| Samsung Electronics  | 5        | 17.24%  |
| Dell                 | 4        | 13.79%  |
| Ancor Communications | 3        | 10.34%  |
| Acer                 | 3        | 10.34%  |
| Toshiba              | 1        | 3.45%   |
| Roku                 | 1        | 3.45%   |
| Lenovo               | 1        | 3.45%   |
| Hewlett-Packard      | 1        | 3.45%   |
| BenQ                 | 1        | 3.45%   |
| ASUSTek Computer     | 1        | 3.45%   |
| AGO                  | 1        | 3.45%   |
| Unknown              | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1        | 3.13%   |
| Samsung Electronics S34CG50 SAM730F 3440x1440 798x334mm 34.1-inch     | 1        | 3.13%   |
| Samsung Electronics LS24AG32x SAM71DA 1920x1080 527x296mm 23.8-inch   | 1        | 3.13%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 1        | 3.13%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1        | 3.13%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.13%   |
| Roku TV RKU8518 1920x1080 698x392mm 31.5-inch                         | 1        | 3.13%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                  | 1        | 3.13%   |
| Hewlett-Packard V320 HPN3363 1920x1080 698x393mm 31.5-inch            | 1        | 3.13%   |
| Goldstar L1742 GSM449C 1280x1024 338x270mm 17.0-inch                  | 1        | 3.13%   |
| Goldstar HDR WFHD GSM5BB9 2560x1080 798x334mm 34.1-inch               | 1        | 3.13%   |
| Goldstar HDR WFHD GSM5BA0 2560x1080 798x334mm 34.1-inch               | 1        | 3.13%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 1        | 3.13%   |
| Goldstar FULL HD GSM5BFB 1920x1080 480x270mm 21.7-inch                | 1        | 3.13%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 3.13%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                   | 1        | 3.13%   |
| Dell SE2417HG DELD08D 1920x1080 521x293mm 23.5-inch                   | 1        | 3.13%   |
| Dell S2421NX DEL41FB 1920x1080 527x296mm 23.8-inch                    | 1        | 3.13%   |
| Dell S2240T DELA094 1920x1080 477x268mm 21.5-inch                     | 1        | 3.13%   |
| Dell E198WFP DELF005 1440x900 408x255mm 18.9-inch                     | 1        | 3.13%   |
| BenQ BL3200 BNQ8017 2560x1440 708x398mm 32.0-inch                     | 1        | 3.13%   |
| ASUSTek Computer ROG PG65UQ AUS65A1 3840x2160 1430x800mm 64.5-inch    | 1        | 3.13%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 1        | 3.13%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 3.13%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 1        | 3.13%   |
| AGO LCD Monitor AGO0001 1920x1080 300x230mm 14.9-inch                 | 1        | 3.13%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                 | 1        | 3.13%   |
| Acer XF251Q ACR0624 1920x1080 544x303mm 24.5-inch                     | 1        | 3.13%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                     | 1        | 3.13%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 1        | 3.13%   |
| Acer G235H ACR0120 1920x1080 521x293mm 23.5-inch                      | 1        | 3.13%   |
| Unknown                                                               | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 12       | 42.86%  |
| 3840x2160 (4K)   | 3        | 10.71%  |
| 2560x1440 (QHD)  | 3        | 10.71%  |
| 3840x1080        | 2        | 7.14%   |
| 3440x1440        | 2        | 7.14%   |
| 2560x1080        | 2        | 7.14%   |
| 3200x1080        | 1        | 3.57%   |
| 1440x900 (WXGA+) | 1        | 3.57%   |
| 1280x1024 (SXGA) | 1        | 3.57%   |
| Unknown          | 1        | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 16.13%  |
| 34      | 4        | 12.9%   |
| 31      | 4        | 12.9%   |
| 23      | 3        | 9.68%   |
| 21      | 3        | 9.68%   |
| 48      | 2        | 6.45%   |
| 27      | 2        | 6.45%   |
| 74      | 1        | 3.23%   |
| 64      | 1        | 3.23%   |
| 32      | 1        | 3.23%   |
| 19      | 1        | 3.23%   |
| 17      | 1        | 3.23%   |
| 14      | 1        | 3.23%   |
| 12      | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 31.03%  |
| 701-800     | 5        | 17.24%  |
| 601-700     | 4        | 13.79%  |
| 401-500     | 4        | 13.79%  |
| 1001-1500   | 3        | 10.34%  |
| 301-350     | 1        | 3.45%   |
| 201-300     | 1        | 3.45%   |
| 1501-2000   | 1        | 3.45%   |
| Unknown     | 1        | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 15       | 57.69%  |
| 21/9    | 4        | 15.38%  |
| 32/9    | 2        | 7.69%   |
| 16/10   | 2        | 7.69%   |
| 5/4     | 1        | 3.85%   |
| 4/3     | 1        | 3.85%   |
| Unknown | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 351-500        | 9        | 30%     |
| 201-250        | 8        | 26.67%  |
| More than 1000 | 2        | 6.67%   |
| 301-350        | 2        | 6.67%   |
| 151-200        | 2        | 6.67%   |
| 501-1000       | 2        | 6.67%   |
| 71-80          | 1        | 3.33%   |
| 251-300        | 1        | 3.33%   |
| 141-150        | 1        | 3.33%   |
| 101-110        | 1        | 3.33%   |
| Unknown        | 1        | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 60.71%  |
| 101-120 | 5        | 17.86%  |
| 121-160 | 3        | 10.71%  |
| 1-50    | 1        | 3.57%   |
| 161-240 | 1        | 3.57%   |
| Unknown | 1        | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 62.5%   |
| 2     | 8        | 33.33%  |
| 3     | 1        | 4.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 53.13%  |
| Intel                 | 10       | 31.25%  |
| Ralink Technology     | 1        | 3.13%   |
| Microsoft             | 1        | 3.13%   |
| MediaTek              | 1        | 3.13%   |
| Broadcom Limited      | 1        | 3.13%   |
| Aquantia              | 1        | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 12       | 27.91%  |
| Realtek RTL8125 2.5GbE Controller                                              | 3        | 6.98%   |
| Intel Wi-Fi 6 AX200                                                            | 3        | 6.98%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 3        | 6.98%   |
| Intel I211 Gigabit Network Connection                                          | 3        | 6.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 2        | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 2.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 1        | 2.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 2.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 2.33%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 2.33%   |
| Realtek 802.11ac NIC                                                           | 1        | 2.33%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 2.33%   |
| Microsoft Xbox Wireless Adapter for Windows                                    | 1        | 2.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 1        | 2.33%   |
| Intel Wireless 8265 / 8275                                                     | 1        | 2.33%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 2.33%   |
| Intel Ethernet Connection (3) I219-LM                                          | 1        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 2.33%   |
| Intel Ethernet Connection (2) I218-V                                           | 1        | 2.33%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express                  | 1        | 2.33%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 50%     |
| Realtek Semiconductor | 4        | 28.57%  |
| Ralink Technology     | 1        | 7.14%   |
| Microsoft             | 1        | 7.14%   |
| MediaTek              | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 3        | 20%     |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 3        | 20%     |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2        | 13.33%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 6.67%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 1        | 6.67%   |
| Realtek 802.11ac NIC                                          | 1        | 6.67%   |
| Ralink MT7601U Wireless Adapter                               | 1        | 6.67%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 1        | 6.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1        | 6.67%   |
| Intel Wireless 8265 / 8275                                    | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 64%     |
| Intel                 | 7        | 28%     |
| Broadcom Limited      | 1        | 4%      |
| Aquantia              | 1        | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 12       | 42.86%  |
| Realtek RTL8125 2.5GbE Controller                                              | 3        | 10.71%  |
| Intel I211 Gigabit Network Connection                                          | 3        | 10.71%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 3.57%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 3.57%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 3.57%   |
| Intel Ethernet Connection (3) I219-LM                                          | 1        | 3.57%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 3.57%   |
| Intel Ethernet Connection (2) I218-V                                           | 1        | 3.57%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express                  | 1        | 3.57%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 64.86%  |
| WiFi     | 13       | 35.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 66.67%  |
| WiFi     | 8        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 12       | 50%     |
| 1     | 11       | 45.83%  |
| 3     | 1        | 4.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 62.5%   |
| Yes  | 9        | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 53.85%  |
| Cambridge Silicon Radio | 2        | 15.38%  |
| Realtek Semiconductor   | 1        | 7.69%   |
| MediaTek                | 1        | 7.69%   |
| IMC Networks            | 1        | 7.69%   |
| Actions                 | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 23.08%  |
| Intel AX200 Bluetooth                               | 3        | 23.08%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 15.38%  |
| Realtek Bluetooth Radio                             | 1        | 7.69%   |
| MediaTek Wireless_Device                            | 1        | 7.69%   |
| Intel Bluetooth wireless interface                  | 1        | 7.69%   |
| IMC Networks Bluetooth Radio                        | 1        | 7.69%   |
| Actions general adapter                             | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 18       | 35.29%  |
| Nvidia              | 9        | 17.65%  |
| Intel               | 9        | 17.65%  |
| Logitech            | 3        | 5.88%   |
| Kingston Technology | 2        | 3.92%   |
| C-Media Electronics | 2        | 3.92%   |
| Texas Instruments   | 1        | 1.96%   |
| Samson Technologies | 1        | 1.96%   |
| Oculus VR           | 1        | 1.96%   |
| KTMicro             | 1        | 1.96%   |
| JMTek               | 1        | 1.96%   |
| Focusrite-Novation  | 1        | 1.96%   |
| Blue Microphones    | 1        | 1.96%   |
| Astro Gaming        | 1        | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 13.85%  |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 3        | 4.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 4.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 3.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 3.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 3.08%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2        | 3.08%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 3.08%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 3.08%   |
| AMD FCH Azalia Controller                                                  | 2        | 3.08%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.54%   |
| Samson Technologies C01U condenser microphone                              | 1        | 1.54%   |
| Oculus VR Rift CV1 Audio                                                   | 1        | 1.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.54%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 1.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.54%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.54%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.54%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.54%   |
| Logitech Logitech USB Microphone                                           | 1        | 1.54%   |
| Logitech H390 headset with microphone                                      | 1        | 1.54%   |
| Logitech G432 Gaming Headset                                               | 1        | 1.54%   |
| KTMicro KT_USB_AUDIO                                                       | 1        | 1.54%   |
| Kingston Technology HyperX QuadCast S                                      | 1        | 1.54%   |
| Kingston Technology HyperX QuadCast                                        | 1        | 1.54%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.54%   |
| Intel Lewisburg MROM 0                                                     | 1        | 1.54%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 1.54%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.54%   |
| Focusrite-Novation Scarlett 2i2 3rd Gen                                    | 1        | 1.54%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.54%   |
| C-Media Electronics Antlion USB adapter                                    | 1        | 1.54%   |
| Blue Microphones Yeti Nano                                                 | 1        | 1.54%   |
| Astro Gaming Astro MixAmp Pro                                              | 1        | 1.54%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 1.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 5        | 22.73%  |
| A-DATA Technology   | 3        | 13.64%  |
| Unknown             | 2        | 9.09%   |
| Team                | 2        | 9.09%   |
| G.Skill             | 2        | 9.09%   |
| Crucial             | 2        | 9.09%   |
| Corsair             | 2        | 9.09%   |
| SK hynix            | 1        | 4.55%   |
| Samsung Electronics | 1        | 4.55%   |
| Ramaxel Technology  | 1        | 4.55%   |
| Micron Technology   | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 4.17%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 4.17%   |
| Unknown RAM Module 1GB DIMM SDRAM                       | 1        | 4.17%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s     | 1        | 4.17%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s      | 1        | 4.17%   |
| SK hynix RAM HYMP512U64CP8-S6 1GB DIMM DDR2 800MT/s     | 1        | 4.17%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s   | 1        | 4.17%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 1        | 4.17%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s | 1        | 4.17%   |
| Micron RAM F6451U64F9333G 4GB DIMM DDR3 1333MT/s        | 1        | 4.17%   |
| Kingston RAM KF552C40-8 8GB DIMM DDR5 4800MT/s          | 1        | 4.17%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s   | 1        | 4.17%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 4.17%   |
| Kingston RAM CL16-20-20 D4-3200 8GB DIMM DDR4 3200MT/s  | 1        | 4.17%   |
| Kingston RAM 9905402-532.A00LF 4GB DIMM DDR3 1600MT/s   | 1        | 4.17%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 1        | 4.17%   |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 1        | 4.17%   |
| Crucial RAM CT51264BA1339.M16F 4GB DIMM DDR3 1333MT/s   | 1        | 4.17%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s   | 1        | 4.17%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Corsair RAM CMT16GX4M2K4266C19 8GB DIMM DDR4 2133MT/s   | 1        | 4.17%   |
| A-DATA RAM Module 8GB DIMM DDR4 2133MT/s                | 1        | 4.17%   |
| A-DATA RAM DDR4 3600 2OZ 8GB DIMM DDR4 2667MT/s         | 1        | 4.17%   |
| A-DATA RAM DDR4 3200 2OZ 16GB DIMM DDR4 3200MT/s        | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 13       | 65%     |
| DDR3  | 4        | 20%     |
| SDRAM | 1        | 5%      |
| DDR5  | 1        | 5%      |
| DDR2  | 1        | 5%      |

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
| 8192  | 9        | 40.91%  |
| 32768 | 3        | 13.64%  |
| 16384 | 3        | 13.64%  |
| 4096  | 3        | 13.64%  |
| 2048  | 2        | 9.09%   |
| 1024  | 2        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 3        | 13.64%  |
| 3200    | 3        | 13.64%  |
| 2667    | 3        | 13.64%  |
| 1600    | 3        | 13.64%  |
| 3800    | 2        | 9.09%   |
| 2133    | 2        | 9.09%   |
| 49926   | 1        | 4.55%   |
| 4800    | 1        | 4.55%   |
| 3733    | 1        | 4.55%   |
| 1333    | 1        | 4.55%   |
| 800     | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP DeskJet 4720 series | 1        | 100%    |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Samsung Electronics    | 2        | 33.33%  |
| Generalplus Technology | 2        | 33.33%  |
| Logitech               | 1        | 16.67%  |
| ARC International      | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)  | 2        | 33.33%  |
| Logitech HD Pro Webcam C920              | 1        | 16.67%  |
| Generalplus GENERAL WEBCAM               | 1        | 16.67%  |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 16.67%  |
| ARC International Camera                 | 1        | 16.67%  |

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
| 0     | 21       | 87.5%   |
| 1     | 2        | 8.33%   |
| 2     | 1        | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 1        | 33.33%  |
| Net/wireless     | 1        | 33.33%  |
| Graphics card    | 1        | 33.33%  |

