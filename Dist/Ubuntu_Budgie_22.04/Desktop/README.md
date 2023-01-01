Ubuntu Budgie 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

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

Total: 31

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Fujitsu  | D3348-B2 S26361-D3348-B2 | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu  | D3348-B2 S26361-D3348-B2 | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Fujitsu  | D3348-B2 S26361-D3348-B2 | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Dell     | 0RW199                   | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| MSI      | B550M PRO-VDH WIFI       | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| Dell     | 0C27VV A01               | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI      | B450-A PRO MAX           | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| Dell     | 0C27VV A01               | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell     | 0C27VV A01               | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Gigabyte | M68MT-S2                 | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| Gigabyte | B75M-D3P                 | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte | M68MT-S2                 | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Gigabyte | X570S AORUS PRO AX       | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel    | DP55WB AAE64798-206      | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek  | A88X-PRO                 | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Intel    | X79M-S                   | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| HP       | 828A                     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| Biostar  | A960D+V3                 | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock   | A300M-STX                | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock   | A300M-STX                | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Intel    | STK1A32SC H95551-301     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Gigabyte | GA-890GPA-UD3H           | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP       | 212B                     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| Gigabyte | B75M-D3H                 | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte | F2A78M-HD2               | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek  | PRIME B560M-A            | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| MSI      | X370 GAMING PRO CARBON   | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Gigabyte | B75M-D3H                 | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| HP       | 1825                     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Gigabyte | B550 AORUS ELITE AX V2   | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.15.0-52-generic     | 4        | 16%     |
| 5.15.0-46-generic     | 3        | 12%     |
| 5.15.0-30-generic     | 3        | 12%     |
| 5.15.0-43-generic     | 2        | 8%      |
| 5.15.0-33-generic     | 2        | 8%      |
| 5.15.0-27-generic     | 2        | 8%      |
| 5.15.0-25-generic     | 2        | 8%      |
| 5.17.2-051702-generic | 1        | 4%      |
| 5.15.0-56-generic     | 1        | 4%      |
| 5.15.0-50-generic     | 1        | 4%      |
| 5.15.0-48-generic     | 1        | 4%      |
| 5.15.0-47-generic     | 1        | 4%      |
| 5.15.0-41-generic     | 1        | 4%      |
| 5.13.0-44-generic     | 1        | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 21       | 91.3%   |
| 5.17.2  | 1        | 4.35%   |
| 5.13.0  | 1        | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 21       | 91.3%   |
| 5.17    | 1        | 4.35%   |
| 5.13    | 1        | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 23       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 23       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 23       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 16       | 69.57%  |
| Unknown | 6        | 26.09%  |
| GDM     | 1        | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 47.83%  |
| de_DE | 4        | 17.39%  |
| fr_FR | 2        | 8.7%    |
| es_ES | 2        | 8.7%    |
| es_MX | 1        | 4.35%   |
| en_GB | 1        | 4.35%   |
| en_CA | 1        | 4.35%   |
| el_GR | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 16       | 66.67%  |
| EFI  | 8        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 19       | 82.61%  |
| Overlay | 3        | 13.04%  |
| Btrfs   | 1        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 56.52%  |
| GPT     | 10       | 43.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 78.26%  |
| Yes       | 5        | 21.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 65.22%  |
| Yes       | 8        | 34.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 8        | 34.78%  |
| MSI                 | 3        | 13.04%  |
| Hewlett-Packard     | 3        | 13.04%  |
| Intel               | 2        | 8.7%    |
| Dell                | 2        | 8.7%    |
| ASUSTek Computer    | 2        | 8.7%    |
| Fujitsu             | 1        | 4.35%   |
| Biostar             | 1        | 4.35%   |
| ASRock              | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7C95                      | 1        | 4.35%   |
| MSI MS-7B86                      | 1        | 4.35%   |
| MSI MS-7A32                      | 1        | 4.35%   |
| Intel STK1A32SC                  | 1        | 4.35%   |
| Intel DP55WB AAE64798-206        | 1        | 4.35%   |
| HP Z440 Workstation              | 1        | 4.35%   |
| HP EliteDesk 800 G1 DM           | 1        | 4.35%   |
| HP 750-417c                      | 1        | 4.35%   |
| Gigabyte X570S AORUS PRO AX      | 1        | 4.35%   |
| Gigabyte M68MT-S2                | 1        | 4.35%   |
| Gigabyte GA-890GPA-UD3H          | 1        | 4.35%   |
| Gigabyte F2A78M-HD2              | 1        | 4.35%   |
| Gigabyte B75M-D3P                | 1        | 4.35%   |
| Gigabyte B75M-D3H                | 1        | 4.35%   |
| Gigabyte B550 AORUS ELITE AX V2  | 1        | 4.35%   |
| Gigabyte B450 I AORUS PRO WIFI   | 1        | 4.35%   |
| Fujitsu D3348-B2                 | 1        | 4.35%   |
| Dell Precision WorkStation T7400 | 1        | 4.35%   |
| Dell OptiPlex 780                | 1        | 4.35%   |
| Biostar A960D+V3                 | 1        | 4.35%   |
| ASUS PRIME B560M-A               | 1        | 4.35%   |
| ASUS A88X-PRO                    | 1        | 4.35%   |
| ASRock A300M-STX                 | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| MSI MS-7C95             | 1        | 4.35%   |
| MSI MS-7B86             | 1        | 4.35%   |
| MSI MS-7A32             | 1        | 4.35%   |
| Intel STK1A32SC         | 1        | 4.35%   |
| Intel DP55WB            | 1        | 4.35%   |
| HP Z440                 | 1        | 4.35%   |
| HP EliteDesk            | 1        | 4.35%   |
| HP 750-417c             | 1        | 4.35%   |
| Gigabyte X570S          | 1        | 4.35%   |
| Gigabyte M68MT-S2       | 1        | 4.35%   |
| Gigabyte GA-890GPA-UD3H | 1        | 4.35%   |
| Gigabyte F2A78M-HD2     | 1        | 4.35%   |
| Gigabyte B75M-D3P       | 1        | 4.35%   |
| Gigabyte B75M-D3H       | 1        | 4.35%   |
| Gigabyte B550           | 1        | 4.35%   |
| Gigabyte B450           | 1        | 4.35%   |
| Fujitsu D3348-B2        | 1        | 4.35%   |
| Dell Precision          | 1        | 4.35%   |
| Dell OptiPlex           | 1        | 4.35%   |
| Biostar A960D+V3        | 1        | 4.35%   |
| ASUS PRIME              | 1        | 4.35%   |
| ASUS A88X-PRO           | 1        | 4.35%   |
| ASRock A300M-STX        | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 3        | 13.04%  |
| 2010 | 3        | 13.04%  |
| 2021 | 2        | 8.7%    |
| 2020 | 2        | 8.7%    |
| 2017 | 2        | 8.7%    |
| 2016 | 2        | 8.7%    |
| 2015 | 2        | 8.7%    |
| 2014 | 2        | 8.7%    |
| 2019 | 1        | 4.35%   |
| 2013 | 1        | 4.35%   |
| 2012 | 1        | 4.35%   |
| 2009 | 1        | 4.35%   |
| 2008 | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 23       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 7        | 30.43%  |
| 8.01-16.0       | 6        | 26.09%  |
| 4.01-8.0        | 5        | 21.74%  |
| 32.01-64.0      | 2        | 8.7%    |
| More than 256.0 | 1        | 4.35%   |
| 24.01-32.0      | 1        | 4.35%   |
| 1.01-2.0        | 1        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 10       | 40%     |
| 2.01-3.0  | 8        | 32%     |
| 4.01-8.0  | 4        | 16%     |
| 3.01-4.0  | 2        | 8%      |
| 8.01-16.0 | 1        | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 39.13%  |
| 1      | 6        | 26.09%  |
| 4      | 3        | 13.04%  |
| 6      | 2        | 8.7%    |
| 3      | 2        | 8.7%    |
| 7      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 56.52%  |
| Yes       | 10       | 43.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 95.65%  |
| No        | 1        | 4.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 56.52%  |
| No        | 10       | 43.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 60.87%  |
| Yes       | 9        | 39.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 8        | 34.78%  |
| Germany     | 3        | 13.04%  |
| Switzerland | 2        | 8.7%    |
| UK          | 1        | 4.35%   |
| Spain       | 1        | 4.35%   |
| Slovenia    | 1        | 4.35%   |
| Norway      | 1        | 4.35%   |
| Mexico      | 1        | 4.35%   |
| Greece      | 1        | 4.35%   |
| France      | 1        | 4.35%   |
| Croatia     | 1        | 4.35%   |
| Brazil      | 1        | 4.35%   |
| Argentina   | 1        | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milwaukee             | 2        | 8.33%   |
| Zurich                | 1        | 4.17%   |
| Walled Lake           | 1        | 4.17%   |
| Trondheim             | 1        | 4.17%   |
| Tocantins             | 1        | 4.17%   |
| Tann                  | 1        | 4.17%   |
| Seattle               | 1        | 4.17%   |
| San Luis Potosí City | 1        | 4.17%   |
| Rueil-Malmaison       | 1        | 4.17%   |
| Pula                  | 1        | 4.17%   |
| Pine Island           | 1        | 4.17%   |
| New York              | 1        | 4.17%   |
| Maribor               | 1        | 4.17%   |
| Madrid                | 1        | 4.17%   |
| Kirkcaldy             | 1        | 4.17%   |
| Hamburg               | 1        | 4.17%   |
| Ennepetal             | 1        | 4.17%   |
| Delbrueck             | 1        | 4.17%   |
| Colon                 | 1        | 4.17%   |
| Caslano               | 1        | 4.17%   |
| Camp Hill             | 1        | 4.17%   |
| Bradenton             | 1        | 4.17%   |
| Athens                | 1        | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 14     | 19.15%  |
| SanDisk             | 5        | 6      | 10.64%  |
| Samsung Electronics | 5        | 20     | 10.64%  |
| WDC                 | 4        | 5      | 8.51%   |
| Toshiba             | 2        | 2      | 4.26%   |
| OCZ                 | 2        | 2      | 4.26%   |
| Kingston            | 2        | 3      | 4.26%   |
| Crucial             | 2        | 2      | 4.26%   |
| Zheino              | 1        | 1      | 2.13%   |
| Unknown             | 1        | 1      | 2.13%   |
| Transcend           | 1        | 1      | 2.13%   |
| SPCC                | 1        | 1      | 2.13%   |
| SK hynix            | 1        | 1      | 2.13%   |
| PNY                 | 1        | 1      | 2.13%   |
| Phison              | 1        | 1      | 2.13%   |
| Mushkin             | 1        | 1      | 2.13%   |
| Micron Technology   | 1        | 1      | 2.13%   |
| Maxtor              | 1        | 1      | 2.13%   |
| JMicron Technology  | 1        | 1      | 2.13%   |
| Intel               | 1        | 1      | 2.13%   |
| HGST                | 1        | 1      | 2.13%   |
| China               | 1        | 1      | 2.13%   |
| ASMT109x            | 1        | 1      | 2.13%   |
| A-DATA Technology   | 1        | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST1000LM048-2E7172 1TB       | 2        | 3.51%   |
| SanDisk SDSSDA120G 120GB             | 2        | 3.51%   |
| Samsung SSD 870 EVO 250GB            | 2        | 3.51%   |
| Zheino CHN-25SATAC3-120 120GB        | 1        | 1.75%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1        | 1.75%   |
| WDC WD40PURZ-85TTDY0 4TB             | 1        | 1.75%   |
| WDC WD1600AAJS-60WAA0 160GB          | 1        | 1.75%   |
| WDC WD10EARS-00Y5B1 1TB              | 1        | 1.75%   |
| WDC WD10EADS-00M2B0 1TB              | 1        | 1.75%   |
| Unknown SD/MMC/MS PRO 64GB           | 1        | 1.75%   |
| Transcend TS128GMTE110S 128GB        | 1        | 1.75%   |
| Toshiba HDWD240 4TB                  | 1        | 1.75%   |
| Toshiba HDWD220 2TB                  | 1        | 1.75%   |
| SPCC Solid State Disk 256GB          | 1        | 1.75%   |
| SK hynix SC210 2.5 7MM 128GB SSD     | 1        | 1.75%   |
| Seagate ST9500325AS 500GB            | 1        | 1.75%   |
| Seagate ST500LT012-1DG142 500GB      | 1        | 1.75%   |
| Seagate ST380815AS 80GB              | 1        | 1.75%   |
| Seagate ST3500418AS 500GB            | 1        | 1.75%   |
| Seagate ST3500412AS 500GB            | 1        | 1.75%   |
| Seagate ST3160815AS 160GB            | 1        | 1.75%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1.75%   |
| Seagate ST2000DM001-1ER164 2TB       | 1        | 1.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1        | 1.75%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1        | 1.75%   |
| Seagate ST1000DM003-1SB10C 1TB       | 1        | 1.75%   |
| Seagate NVMe SSD Drive 500GB         | 1        | 1.75%   |
| Sandisk WD Blue SN550 NVMe SSD 500GB | 1        | 1.75%   |
| SanDisk NVMe SSD Drive 500GB         | 1        | 1.75%   |
| SanDisk DF4032  32GB                 | 1        | 1.75%   |
| Samsung SSD 850 PRO 256GB            | 1        | 1.75%   |
| Samsung SSD 850 EVO 1TB              | 1        | 1.75%   |
| Samsung SSD 840 EVO 250GB            | 1        | 1.75%   |
| Samsung SSD 840 EVO 1TB              | 1        | 1.75%   |
| Samsung NVMe SSD Controller 172X 3TB | 1        | 1.75%   |
| Samsung MZVLW256HEHP-000H1 256GB     | 1        | 1.75%   |
| Samsung HD250HJ 250GB                | 1        | 1.75%   |
| PNY CS900 120GB SSD                  | 1        | 1.75%   |
| Phison NVMe SSD Drive 512GB          | 1        | 1.75%   |
| OCZ TRION150 240GB SSD               | 1        | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 13     | 45%     |
| WDC                 | 4        | 5      | 20%     |
| Toshiba             | 2        | 2      | 10%     |
| Unknown             | 1        | 1      | 5%      |
| Samsung Electronics | 1        | 2      | 5%      |
| Maxtor              | 1        | 1      | 5%      |
| HGST                | 1        | 1      | 5%      |
| ASMT109x            | 1        | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 15     | 17.65%  |
| SanDisk             | 2        | 2      | 11.76%  |
| Crucial             | 2        | 2      | 11.76%  |
| Zheino              | 1        | 1      | 5.88%   |
| SPCC                | 1        | 1      | 5.88%   |
| SK hynix            | 1        | 1      | 5.88%   |
| PNY                 | 1        | 1      | 5.88%   |
| OCZ                 | 1        | 1      | 5.88%   |
| Mushkin             | 1        | 1      | 5.88%   |
| Kingston            | 1        | 2      | 5.88%   |
| JMicron Technology  | 1        | 1      | 5.88%   |
| China               | 1        | 1      | 5.88%   |
| A-DATA Technology   | 1        | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 14       | 30     | 36.84%  |
| HDD  | 14       | 26     | 36.84%  |
| NVMe | 9        | 13     | 23.68%  |
| MMC  | 1        | 1      | 2.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 21       | 53     | 61.76%  |
| NVMe | 9        | 13     | 26.47%  |
| SAS  | 3        | 3      | 8.82%   |
| MMC  | 1        | 1      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 36     | 60.61%  |
| 0.51-1.0   | 8        | 14     | 24.24%  |
| 3.01-4.0   | 3        | 3      | 9.09%   |
| 1.01-2.0   | 2        | 3      | 6.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 34.78%  |
| 251-500        | 3        | 13.04%  |
| 51-100         | 3        | 13.04%  |
| More than 3000 | 2        | 8.7%    |
| 1001-2000      | 2        | 8.7%    |
| 1-20           | 2        | 8.7%    |
| 21-50          | 1        | 4.35%   |
| 2001-3000      | 1        | 4.35%   |
| 501-1000       | 1        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 8        | 34.78%  |
| 1-20      | 6        | 26.09%  |
| 101-250   | 3        | 13.04%  |
| 51-100    | 3        | 13.04%  |
| 251-500   | 1        | 4.35%   |
| 2001-3000 | 1        | 4.35%   |
| 1001-2000 | 1        | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Detected | 18       | 53     | 66.67%  |
| Works    | 7        | 15     | 25.93%  |
| Malfunc  | 2        | 2      | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 11       | 31.43%  |
| AMD                         | 11       | 31.43%  |
| SanDisk                     | 2        | 5.71%   |
| Samsung Electronics         | 2        | 5.71%   |
| Transcend                   | 1        | 2.86%   |
| Seagate Technology          | 1        | 2.86%   |
| Phison Electronics          | 1        | 2.86%   |
| OCZ Technology Group        | 1        | 2.86%   |
| Nvidia                      | 1        | 2.86%   |
| Micron Technology           | 1        | 2.86%   |
| Marvell Technology Group    | 1        | 2.86%   |
| Kingston Technology Company | 1        | 2.86%   |
| JMicron Technology          | 1        | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 11.11%  |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 4.44%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 4.44%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 4.44%   |
| Transcend Non-Volatile memory controller                                       | 1        | 2.22%   |
| Seagate Non-Volatile memory controller                                         | 1        | 2.22%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 2.22%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 2.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 2.22%   |
| Samsung NVMe SSD Controller 172X                                               | 1        | 2.22%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 2.22%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 2.22%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 2.22%   |
| Micron Non-Volatile memory controller                                          | 1        | 2.22%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 2.22%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 2.22%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.22%   |
| Intel Non-Volatile memory controller                                           | 1        | 2.22%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                     | 1        | 2.22%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 2.22%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 2.22%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 2.22%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 2.22%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                     | 1        | 2.22%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1        | 2.22%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 2.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 2.22%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 2.22%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 1        | 2.22%   |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 2.22%   |
| AMD FCH IDE Controller                                                         | 1        | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 50%     |
| NVMe | 9        | 25%     |
| IDE  | 8        | 22.22%  |
| RAID | 1        | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 12       | 52.17%  |
| Intel  | 11       | 47.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 8.7%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 2        | 8.7%    |
| Intel Xeon CPU X5492 @ 3.40GHz                  | 1        | 4.35%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz            | 1        | 4.35%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz             | 1        | 4.35%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 4.35%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 4.35%   |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 4.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 4.35%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 4.35%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 4.35%   |
| Intel Atom x5-Z8330 CPU @ 1.44GHz               | 1        | 4.35%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz          | 1        | 4.35%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 4.35%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 4.35%   |
| AMD Phenom II X4 965 Processor                  | 1        | 4.35%   |
| AMD FX-8150 Eight-Core Processor                | 1        | 4.35%   |
| AMD Athlon II X3 445 Processor                  | 1        | 4.35%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 1        | 4.35%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 4.35%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AMD Ryzen 5       | 5        | 21.74%  |
| Intel Xeon        | 3        | 13.04%  |
| Intel Core i5     | 3        | 13.04%  |
| Other             | 1        | 4.35%   |
| Intel Core i7     | 1        | 4.35%   |
| Intel Core i3     | 1        | 4.35%   |
| Intel Core 2 Quad | 1        | 4.35%   |
| Intel Atom        | 1        | 4.35%   |
| AMD Ryzen 9       | 1        | 4.35%   |
| AMD Phenom II X4  | 1        | 4.35%   |
| AMD FX            | 1        | 4.35%   |
| AMD Athlon II X3  | 1        | 4.35%   |
| AMD Athlon        | 1        | 4.35%   |
| AMD A4            | 1        | 4.35%   |
| AMD A10           | 1        | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 47.83%  |
| 6      | 4        | 17.39%  |
| 2      | 3        | 13.04%  |
| 16     | 1        | 4.35%   |
| 12     | 1        | 4.35%   |
| 8      | 1        | 4.35%   |
| 3      | 1        | 4.35%   |
| 1      | 1        | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 95.65%  |
| 2      | 1        | 4.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 65.22%  |
| 1      | 8        | 34.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 23       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 56%     |
| 0x406f1    | 2        | 8%      |
| 0x306a9    | 2        | 8%      |
| 0xa0671    | 1        | 4%      |
| 0x406c4    | 1        | 4%      |
| 0x10677    | 1        | 4%      |
| 0x0a50000c | 1        | 4%      |
| 0x08108109 | 1        | 4%      |
| 0x08108102 | 1        | 4%      |
| 0x06001119 | 1        | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 4        | 17.39%  |
| Zen 3       | 3        | 13.04%  |
| Penryn      | 2        | 8.7%    |
| K10         | 2        | 8.7%    |
| IvyBridge   | 2        | 8.7%    |
| Broadwell   | 2        | 8.7%    |
| Steamroller | 1        | 4.35%   |
| Skylake     | 1        | 4.35%   |
| Silvermont  | 1        | 4.35%   |
| Piledriver  | 1        | 4.35%   |
| Nehalem     | 1        | 4.35%   |
| Icelake     | 1        | 4.35%   |
| Haswell     | 1        | 4.35%   |
| Bulldozer   | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 13       | 52%     |
| Nvidia | 7        | 28%     |
| Intel  | 5        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 12%     |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 8%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 8%      |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 4%      |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1        | 4%      |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 4%      |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1        | 4%      |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 4%      |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 4%      |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 4%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 4%      |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 4%      |
| Intel HD Graphics 530                                                                    | 1        | 4%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 4%      |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 4%      |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 4%      |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 1        | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 4%      |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 4%      |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 12       | 52.17%  |
| 1 x Nvidia   | 6        | 26.09%  |
| 1 x Intel    | 4        | 17.39%  |
| AMD + Nvidia | 1        | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 82.61%  |
| Proprietary | 3        | 13.04%  |
| Unknown     | 1        | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 65.22%  |
| 7.01-8.0   | 2        | 8.7%    |
| 1.01-2.0   | 2        | 8.7%    |
| 0.01-0.5   | 2        | 8.7%    |
| 3.01-4.0   | 1        | 4.35%   |
| 0.51-1.0   | 1        | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 9        | 39.13%  |
| Hewlett-Packard     | 3        | 13.04%  |
| SANYO               | 2        | 8.7%    |
| Philips             | 2        | 8.7%    |
| Unknown (XXX)       | 1        | 4.35%   |
| Sony                | 1        | 4.35%   |
| Panasonic           | 1        | 4.35%   |
| Fujitsu Siemens     | 1        | 4.35%   |
| Dell                | 1        | 4.35%   |
| BenQ                | 1        | 4.35%   |
| AOC                 | 1        | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 4.17%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 4.17%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 4.17%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1        | 4.17%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 4.17%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1        | 4.17%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 4.17%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 480x270mm 21.7-inch     | 1        | 4.17%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 4.17%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch     | 1        | 4.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 4.17%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1        | 4.17%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch               | 1        | 4.17%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                   | 1        | 4.17%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                               | 1        | 4.17%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 4.17%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 4.17%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 4.17%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 4.17%   |
| Dell LCD Monitor 1704FPV 1280x1024                                    | 1        | 4.17%   |
| BenQ GW2750H BNQ78C3 1920x1080 598x336mm 27.0-inch                    | 1        | 4.17%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 13       | 56.52%  |
| 1920x540           | 3        | 13.04%  |
| 1920x1200 (WUXGA)  | 2        | 8.7%    |
| 3440x1440          | 1        | 4.35%   |
| 2560x1440 (QHD)    | 1        | 4.35%   |
| 1680x1050 (WSXGA+) | 1        | 4.35%   |
| 1366x768 (WXGA)    | 1        | 4.35%   |
| 1280x1024 (SXGA)   | 1        | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 25%     |
| 27      | 4        | 16.67%  |
| 23      | 3        | 12.5%   |
| 21      | 2        | 8.33%   |
| Unknown | 2        | 8.33%   |
| 72      | 1        | 4.17%   |
| 54      | 1        | 4.17%   |
| 47      | 1        | 4.17%   |
| 34      | 1        | 4.17%   |
| 33      | 1        | 4.17%   |
| 31      | 1        | 4.17%   |
| 18      | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 52.17%  |
| 401-500     | 3        | 13.04%  |
| 701-800     | 2        | 8.7%    |
| 1001-1500   | 2        | 8.7%    |
| Unknown     | 2        | 8.7%    |
| 601-700     | 1        | 4.35%   |
| 1501-2000   | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 16       | 72.73%  |
| 16/10   | 3        | 13.64%  |
| 32/9    | 1        | 4.55%   |
| 21/9    | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 31.82%  |
| 301-350        | 4        | 18.18%  |
| 351-500        | 3        | 13.64%  |
| More than 1000 | 2        | 9.09%   |
| 251-300        | 2        | 9.09%   |
| Unknown        | 2        | 9.09%   |
| 141-150        | 1        | 4.55%   |
| 501-1000       | 1        | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 68.18%  |
| 1-50    | 3        | 13.64%  |
| 101-120 | 2        | 9.09%   |
| Unknown | 2        | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 91.3%   |
| 2     | 2        | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 45.16%  |
| Realtek Semiconductor | 12       | 38.71%  |
| Broadcom              | 2        | 6.45%   |
| Ralink Technology     | 1        | 3.23%   |
| Nvidia                | 1        | 3.23%   |
| MediaTek              | 1        | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 27.03%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 8.11%   |
| Intel I211 Gigabit Network Connection                             | 2        | 5.41%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 5.41%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 2.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.7%    |
| Realtek 802.11ac NIC                                              | 1        | 2.7%    |
| Ralink RT3072 Wireless Adapter                                    | 1        | 2.7%    |
| Nvidia MCP61 Ethernet                                             | 1        | 2.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 2.7%    |
| Intel Wireless-AC 9260                                            | 1        | 2.7%    |
| Intel Wireless 7265                                               | 1        | 2.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 2.7%    |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.7%    |
| Intel I210 Gigabit Network Connection                             | 1        | 2.7%    |
| Intel Ethernet Controller I225-V                                  | 1        | 2.7%    |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2.7%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.7%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.7%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 2.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 2.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 53.85%  |
| Realtek Semiconductor | 3        | 23.08%  |
| Ralink Technology     | 1        | 7.69%   |
| MediaTek              | 1        | 7.69%   |
| Broadcom              | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]    | 3        | 23.08%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter | 1        | 7.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter             | 1        | 7.69%   |
| Realtek 802.11ac NIC                                | 1        | 7.69%   |
| Ralink RT3072 Wireless Adapter                      | 1        | 7.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz             | 1        | 7.69%   |
| Intel Wireless-AC 9260                              | 1        | 7.69%   |
| Intel Wireless 7265                                 | 1        | 7.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz              | 1        | 7.69%   |
| Intel Wi-Fi 6 AX200                                 | 1        | 7.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter  | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 50%     |
| Intel                 | 9        | 40.91%  |
| Nvidia                | 1        | 4.55%   |
| Broadcom              | 1        | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 41.67%  |
| Intel I211 Gigabit Network Connection                             | 2        | 8.33%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 4.17%   |
| Nvidia MCP61 Ethernet                                             | 1        | 4.17%   |
| Intel I210 Gigabit Network Connection                             | 1        | 4.17%   |
| Intel Ethernet Controller I225-V                                  | 1        | 4.17%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 4.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 4.17%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 4.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 4.17%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 62.86%  |
| WiFi     | 13       | 37.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 65.22%  |
| WiFi     | 8        | 34.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 56.52%  |
| 2     | 10       | 43.48%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 86.96%  |
| Yes  | 3        | 13.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 66.67%  |
| Cambridge Silicon Radio | 2        | 22.22%  |
| MediaTek                | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 22.22%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 22.22%  |
| MediaTek Wireless_Device                            | 1        | 11.11%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 11.11%  |
| Intel Bluetooth wireless interface                  | 1        | 11.11%  |
| Intel AX210 Bluetooth                               | 1        | 11.11%  |
| Intel AX200 Bluetooth                               | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 15       | 45.45%  |
| Intel                 | 9        | 27.27%  |
| Nvidia                | 7        | 21.21%  |
| Texas Instruments     | 1        | 3.03%   |
| Realtek Semiconductor | 1        | 3.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                | 5        | 11.63%  |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                   | 3        | 6.98%   |
| Nvidia GK106 HDMI Audio Controller                                    | 2        | 4.65%   |
| Intel C610/X99 series chipset HD Audio Controller                     | 2        | 4.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller   | 2        | 4.65%   |
| AMD SBx00 Azalia (Intel HDA)                                          | 2        | 4.65%   |
| AMD Renoir Radeon High Definition Audio Controller                    | 2        | 4.65%   |
| AMD FCH Azalia Controller                                             | 2        | 4.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                | 2        | 4.65%   |
| Texas Instruments PCM2902 Audio Codec                                 | 1        | 2.33%   |
| Realtek Semiconductor USB Audio                                       | 1        | 2.33%   |
| Nvidia MCP61 High Definition Audio                                    | 1        | 2.33%   |
| Nvidia GP104 High Definition Audio Controller                         | 1        | 2.33%   |
| Nvidia GK110 High Definition Audio Controller                         | 1        | 2.33%   |
| Nvidia GF110 High Definition Audio Controller                         | 1        | 2.33%   |
| Nvidia GA106 High Definition Audio Controller                         | 1        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller      | 1        | 2.33%   |
| Intel Tiger Lake-H HD Audio Controller                                | 1        | 2.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                   | 1        | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller   | 1        | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio              | 1        | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller       | 1        | 2.33%   |
| AMD Trinity HDMI Audio Controller                                     | 1        | 2.33%   |
| AMD Starship/Matisse HD Audio Controller                              | 1        | 2.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                   | 1        | 2.33%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                        | 1        | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                   | 1        | 2.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]            | 1        | 2.33%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand] | 1        | 2.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]          | 1        | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 26.67%  |
| SK hynix            | 2        | 13.33%  |
| Samsung Electronics | 2        | 13.33%  |
| Crucial             | 2        | 13.33%  |
| Transcend           | 1        | 6.67%   |
| Micron Technology   | 1        | 6.67%   |
| Elpida              | 1        | 6.67%   |
| Corsair             | 1        | 6.67%   |
| A-DATA Technology   | 1        | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 12.5%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s     | 1        | 6.25%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 6.25%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 6.25%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s   | 1        | 6.25%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 6.25%   |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s   | 1        | 6.25%   |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s      | 1        | 6.25%   |
| Kingston RAM 9905403-011.A02LF 2GB DIMM DDR3 1333MT/s  | 1        | 6.25%   |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2048MB DIMM DDR3 1333MT/s | 1        | 6.25%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s | 1        | 6.25%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s  | 1        | 6.25%   |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s    | 1        | 6.25%   |
| Corsair RAM CMV4GX3M1A1333C9 4096MB DIMM DDR3 1600MT/s | 1        | 6.25%   |
| A-DATA RAM DDR4 3000 16384MB DIMM DDR4 3600MT/s        | 1        | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 6        | 54.55%  |
| DDR3  | 4        | 36.36%  |
| SDRAM | 1        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 9        | 90%     |
| SODIMM | 1        | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 3        | 25%     |
| 8192  | 3        | 25%     |
| 4096  | 3        | 25%     |
| 2048  | 2        | 16.67%  |
| 32768 | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 4        | 30.77%  |
| 3200  | 2        | 15.38%  |
| 2400  | 2        | 15.38%  |
| 1333  | 2        | 15.38%  |
| 3600  | 1        | 7.69%   |
| 2667  | 1        | 7.69%   |
| 1066  | 1        | 7.69%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 33.33%  |
| Microdia            | 1        | 33.33%  |
| Logitech            | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)     | 1        | 33.33%  |
| Microdia Camera             | 1        | 33.33%  |
| Logitech HD Pro Webcam C920 | 1        | 33.33%  |

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
| 0     | 19       | 82.61%  |
| 1     | 3        | 13.04%  |
| 4     | 1        | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 2        | 33.33%  |
| Sound            | 1        | 16.67%  |
| Net/wireless     | 1        | 16.67%  |
| Net/ethernet     | 1        | 16.67%  |
| Graphics card    | 1        | 16.67%  |

