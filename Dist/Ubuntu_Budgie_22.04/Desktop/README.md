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

Total: 34

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu  | D3183-A1 S26361-D3183-A1    | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| Lenovo   | 36F7 SDK0J40700 WIN 3258... | [831fd897ec](https://linux-hardware.org/?probe=831fd897ec) | Jan 25, 2023 |
| Lenovo   | ThinkStation C20 4263BA7    | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| Fujitsu  | D3348-B2 S26361-D3348-B2    | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu  | D3348-B2 S26361-D3348-B2    | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Fujitsu  | D3348-B2 S26361-D3348-B2    | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Dell     | 0RW199                      | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| MSI      | B550M PRO-VDH WIFI          | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| Dell     | 0C27VV A01                  | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI      | B450-A PRO MAX              | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| Dell     | 0C27VV A01                  | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell     | 0C27VV A01                  | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Gigabyte | M68MT-S2                    | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| Gigabyte | B75M-D3P                    | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte | M68MT-S2                    | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Gigabyte | X570S AORUS PRO AX          | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel    | DP55WB AAE64798-206         | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek  | A88X-PRO                    | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Intel    | X79M-S                      | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| HP       | 828A                        | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| Biostar  | A960D+V3                    | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock   | A300M-STX                   | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock   | A300M-STX                   | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Intel    | STK1A32SC H95551-301        | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Gigabyte | GA-890GPA-UD3H              | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP       | 212B                        | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| Gigabyte | B75M-D3H                    | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte | F2A78M-HD2                  | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek  | PRIME B560M-A               | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| MSI      | X370 GAMING PRO CARBON      | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Gigabyte | B75M-D3H                    | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte | B450 I AORUS PRO WIFI-CF    | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| HP       | 1825                        | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Gigabyte | B550 AORUS ELITE AX V2      | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.15.0-52-generic     | 4        | 14.81%  |
| 5.15.0-46-generic     | 3        | 11.11%  |
| 5.15.0-30-generic     | 3        | 11.11%  |
| 5.15.0-57-generic     | 2        | 7.41%   |
| 5.15.0-43-generic     | 2        | 7.41%   |
| 5.15.0-33-generic     | 2        | 7.41%   |
| 5.15.0-27-generic     | 2        | 7.41%   |
| 5.15.0-25-generic     | 2        | 7.41%   |
| 5.17.2-051702-generic | 1        | 3.7%    |
| 5.15.0-56-generic     | 1        | 3.7%    |
| 5.15.0-50-generic     | 1        | 3.7%    |
| 5.15.0-48-generic     | 1        | 3.7%    |
| 5.15.0-47-generic     | 1        | 3.7%    |
| 5.15.0-41-generic     | 1        | 3.7%    |
| 5.13.0-44-generic     | 1        | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 23       | 92%     |
| 5.17.2  | 1        | 4%      |
| 5.13.0  | 1        | 4%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 23       | 92%     |
| 5.17    | 1        | 4%      |
| 5.13    | 1        | 4%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 25       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 25       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 25       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 17       | 68%     |
| Unknown | 7        | 28%     |
| GDM     | 1        | 4%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 12       | 48%     |
| de_DE | 4        | 16%     |
| fr_FR | 2        | 8%      |
| es_ES | 2        | 8%      |
| en_GB | 2        | 8%      |
| es_MX | 1        | 4%      |
| en_CA | 1        | 4%      |
| el_GR | 1        | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 69.23%  |
| EFI  | 8        | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 20       | 80%     |
| Overlay | 3        | 12%     |
| Zfs     | 1        | 4%      |
| Btrfs   | 1        | 4%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 56%     |
| GPT     | 11       | 44%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 80%     |
| Yes       | 5        | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 68%     |
| Yes       | 8        | 32%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 8        | 32%     |
| MSI                 | 3        | 12%     |
| Hewlett-Packard     | 3        | 12%     |
| Intel               | 2        | 8%      |
| Fujitsu             | 2        | 8%      |
| Dell                | 2        | 8%      |
| ASUSTek Computer    | 2        | 8%      |
| Lenovo              | 1        | 4%      |
| Biostar             | 1        | 4%      |
| ASRock              | 1        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7C95                      | 1        | 4%      |
| MSI MS-7B86                      | 1        | 4%      |
| MSI MS-7A32                      | 1        | 4%      |
| Lenovo ThinkStation C20 4263BA7  | 1        | 4%      |
| Intel STK1A32SC                  | 1        | 4%      |
| Intel DP55WB AAE64798-206        | 1        | 4%      |
| HP Z440 Workstation              | 1        | 4%      |
| HP EliteDesk 800 G1 DM           | 1        | 4%      |
| HP 750-417c                      | 1        | 4%      |
| Gigabyte X570S AORUS PRO AX      | 1        | 4%      |
| Gigabyte M68MT-S2                | 1        | 4%      |
| Gigabyte GA-890GPA-UD3H          | 1        | 4%      |
| Gigabyte F2A78M-HD2              | 1        | 4%      |
| Gigabyte B75M-D3P                | 1        | 4%      |
| Gigabyte B75M-D3H                | 1        | 4%      |
| Gigabyte B550 AORUS ELITE AX V2  | 1        | 4%      |
| Gigabyte B450 I AORUS PRO WIFI   | 1        | 4%      |
| Fujitsu ESPRIMO Q910             | 1        | 4%      |
| Fujitsu D3348-B2                 | 1        | 4%      |
| Dell Precision WorkStation T7400 | 1        | 4%      |
| Dell OptiPlex 780                | 1        | 4%      |
| Biostar A960D+V3                 | 1        | 4%      |
| ASUS PRIME B560M-A               | 1        | 4%      |
| ASUS A88X-PRO                    | 1        | 4%      |
| ASRock A300M-STX                 | 1        | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| MSI MS-7C95             | 1        | 4%      |
| MSI MS-7B86             | 1        | 4%      |
| MSI MS-7A32             | 1        | 4%      |
| Lenovo ThinkStation     | 1        | 4%      |
| Intel STK1A32SC         | 1        | 4%      |
| Intel DP55WB            | 1        | 4%      |
| HP Z440                 | 1        | 4%      |
| HP EliteDesk            | 1        | 4%      |
| HP 750-417c             | 1        | 4%      |
| Gigabyte X570S          | 1        | 4%      |
| Gigabyte M68MT-S2       | 1        | 4%      |
| Gigabyte GA-890GPA-UD3H | 1        | 4%      |
| Gigabyte F2A78M-HD2     | 1        | 4%      |
| Gigabyte B75M-D3P       | 1        | 4%      |
| Gigabyte B75M-D3H       | 1        | 4%      |
| Gigabyte B550           | 1        | 4%      |
| Gigabyte B450           | 1        | 4%      |
| Fujitsu ESPRIMO         | 1        | 4%      |
| Fujitsu D3348-B2        | 1        | 4%      |
| Dell Precision          | 1        | 4%      |
| Dell OptiPlex           | 1        | 4%      |
| Biostar A960D+V3        | 1        | 4%      |
| ASUS PRIME              | 1        | 4%      |
| ASUS A88X-PRO           | 1        | 4%      |
| ASRock A300M-STX        | 1        | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 3        | 12%     |
| 2010 | 3        | 12%     |
| 2021 | 2        | 8%      |
| 2020 | 2        | 8%      |
| 2017 | 2        | 8%      |
| 2016 | 2        | 8%      |
| 2015 | 2        | 8%      |
| 2014 | 2        | 8%      |
| 2012 | 2        | 8%      |
| 2019 | 1        | 4%      |
| 2013 | 1        | 4%      |
| 2011 | 1        | 4%      |
| 2009 | 1        | 4%      |
| 2008 | 1        | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 25       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 25       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 7        | 28%     |
| 8.01-16.0       | 7        | 28%     |
| 4.01-8.0        | 6        | 24%     |
| 32.01-64.0      | 2        | 8%      |
| More than 256.0 | 1        | 4%      |
| 24.01-32.0      | 1        | 4%      |
| 1.01-2.0        | 1        | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 11       | 40.74%  |
| 2.01-3.0  | 8        | 29.63%  |
| 4.01-8.0  | 5        | 18.52%  |
| 3.01-4.0  | 2        | 7.41%   |
| 8.01-16.0 | 1        | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 36%     |
| 1      | 8        | 32%     |
| 4      | 3        | 12%     |
| 6      | 2        | 8%      |
| 3      | 2        | 8%      |
| 7      | 1        | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 52%     |
| Yes       | 12       | 48%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 96%     |
| No        | 1        | 4%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 52%     |
| No        | 12       | 48%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 64%     |
| Yes       | 9        | 36%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 8        | 32%     |
| Germany     | 3        | 12%     |
| UK          | 2        | 8%      |
| Switzerland | 2        | 8%      |
| Spain       | 1        | 4%      |
| Slovenia    | 1        | 4%      |
| Norway      | 1        | 4%      |
| Mexico      | 1        | 4%      |
| Greece      | 1        | 4%      |
| France      | 1        | 4%      |
| Croatia     | 1        | 4%      |
| Brazil      | 1        | 4%      |
| Austria     | 1        | 4%      |
| Argentina   | 1        | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milwaukee             | 2        | 7.69%   |
| Zurich                | 1        | 3.85%   |
| Walled Lake           | 1        | 3.85%   |
| Trondheim             | 1        | 3.85%   |
| Tocantins             | 1        | 3.85%   |
| Tann                  | 1        | 3.85%   |
| Seattle               | 1        | 3.85%   |
| San Luis Potosí City | 1        | 3.85%   |
| Rueil-Malmaison       | 1        | 3.85%   |
| Pula                  | 1        | 3.85%   |
| Pine Island           | 1        | 3.85%   |
| New York              | 1        | 3.85%   |
| Maribor               | 1        | 3.85%   |
| Madrid                | 1        | 3.85%   |
| London                | 1        | 3.85%   |
| Kittsee               | 1        | 3.85%   |
| Kirkcaldy             | 1        | 3.85%   |
| Hamburg               | 1        | 3.85%   |
| Ennepetal             | 1        | 3.85%   |
| Delbrueck             | 1        | 3.85%   |
| Colon                 | 1        | 3.85%   |
| Caslano               | 1        | 3.85%   |
| Camp Hill             | 1        | 3.85%   |
| Bradenton             | 1        | 3.85%   |
| Athens                | 1        | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 15     | 20.41%  |
| Sandisk             | 5        | 6      | 10.2%   |
| Samsung Electronics | 5        | 20     | 10.2%   |
| WDC                 | 4        | 5      | 8.16%   |
| Toshiba             | 2        | 2      | 4.08%   |
| OCZ                 | 2        | 2      | 4.08%   |
| Micron Technology   | 2        | 2      | 4.08%   |
| Kingston            | 2        | 3      | 4.08%   |
| Crucial             | 2        | 2      | 4.08%   |
| Zheino              | 1        | 1      | 2.04%   |
| Unknown             | 1        | 1      | 2.04%   |
| Transcend           | 1        | 1      | 2.04%   |
| SPCC                | 1        | 1      | 2.04%   |
| SK hynix            | 1        | 1      | 2.04%   |
| PNY                 | 1        | 1      | 2.04%   |
| Phison              | 1        | 1      | 2.04%   |
| Mushkin             | 1        | 1      | 2.04%   |
| Maxtor              | 1        | 1      | 2.04%   |
| JMicron Technology  | 1        | 1      | 2.04%   |
| Intel               | 1        | 1      | 2.04%   |
| HGST                | 1        | 1      | 2.04%   |
| China               | 1        | 1      | 2.04%   |
| ASMT109x            | 1        | 1      | 2.04%   |
| A-DATA Technology   | 1        | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST1000LM048-2E7172 1TB       | 2        | 3.39%   |
| SanDisk SDSSDA120G 120GB             | 2        | 3.39%   |
| Samsung SSD 870 EVO 250GB            | 2        | 3.39%   |
| Zheino CHN-25SATAC3-120 120GB        | 1        | 1.69%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1        | 1.69%   |
| WDC WD40PURZ-85TTDY0 4TB             | 1        | 1.69%   |
| WDC WD1600AAJS-60WAA0 160GB          | 1        | 1.69%   |
| WDC WD10EARS-00Y5B1 1TB              | 1        | 1.69%   |
| WDC WD10EADS-00M2B0 1TB              | 1        | 1.69%   |
| Unknown SD/MMC/MS PRO 2GB            | 1        | 1.69%   |
| Transcend TS128GMTE110S 128GB        | 1        | 1.69%   |
| Toshiba HDWD240 4TB                  | 1        | 1.69%   |
| Toshiba HDWD220 2TB                  | 1        | 1.69%   |
| SPCC Solid State Disk 256GB          | 1        | 1.69%   |
| SK hynix SC210 2.5 7MM 128GB SSD     | 1        | 1.69%   |
| Seagate ST9500325AS 500GB            | 1        | 1.69%   |
| Seagate ST500LT012-1DG142 500GB      | 1        | 1.69%   |
| Seagate ST380815AS 80GB              | 1        | 1.69%   |
| Seagate ST3500418AS 500GB            | 1        | 1.69%   |
| Seagate ST3500412AS 500GB            | 1        | 1.69%   |
| Seagate ST3160815AS 160GB            | 1        | 1.69%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1.69%   |
| Seagate ST2000DM001-1ER164 2TB       | 1        | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1        | 1.69%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1        | 1.69%   |
| Seagate ST1000DM010-2EP102 1TB       | 1        | 1.69%   |
| Seagate ST1000DM003-1SB10C 1TB       | 1        | 1.69%   |
| Seagate NVMe SSD Drive 500GB         | 1        | 1.69%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB   | 1        | 1.69%   |
| SanDisk NVMe SSD Drive 500GB         | 1        | 1.69%   |
| SanDisk DF4032  32GB                 | 1        | 1.69%   |
| Samsung SSD 850 PRO 256GB            | 1        | 1.69%   |
| Samsung SSD 850 EVO 1TB              | 1        | 1.69%   |
| Samsung SSD 840 EVO 250GB            | 1        | 1.69%   |
| Samsung SSD 840 EVO 1TB              | 1        | 1.69%   |
| Samsung NVMe SSD Controller 172X 3TB | 1        | 1.69%   |
| Samsung MZVLW256HEHP-000H1 256GB     | 1        | 1.69%   |
| Samsung HD250HJ 250GB                | 1        | 1.69%   |
| PNY CS900 120GB SSD                  | 1        | 1.69%   |
| Phison NVMe SSD Drive 512GB          | 1        | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 14     | 47.62%  |
| WDC                 | 4        | 5      | 19.05%  |
| Toshiba             | 2        | 2      | 9.52%   |
| Unknown             | 1        | 1      | 4.76%   |
| Samsung Electronics | 1        | 2      | 4.76%   |
| Maxtor              | 1        | 1      | 4.76%   |
| HGST                | 1        | 1      | 4.76%   |
| ASMT109x            | 1        | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 15     | 16.67%  |
| SanDisk             | 2        | 2      | 11.11%  |
| Crucial             | 2        | 2      | 11.11%  |
| Zheino              | 1        | 1      | 5.56%   |
| SPCC                | 1        | 1      | 5.56%   |
| SK hynix            | 1        | 1      | 5.56%   |
| PNY                 | 1        | 1      | 5.56%   |
| OCZ                 | 1        | 1      | 5.56%   |
| Mushkin             | 1        | 1      | 5.56%   |
| Micron Technology   | 1        | 1      | 5.56%   |
| Kingston            | 1        | 2      | 5.56%   |
| JMicron Technology  | 1        | 1      | 5.56%   |
| China               | 1        | 1      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 15       | 31     | 37.5%   |
| HDD  | 15       | 27     | 37.5%   |
| NVMe | 9        | 13     | 22.5%   |
| MMC  | 1        | 1      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 23       | 55     | 63.89%  |
| NVMe | 9        | 13     | 25%     |
| SAS  | 3        | 3      | 8.33%   |
| MMC  | 1        | 1      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 37     | 60%     |
| 0.51-1.0   | 9        | 15     | 25.71%  |
| 3.01-4.0   | 3        | 3      | 8.57%   |
| 1.01-2.0   | 2        | 3      | 5.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 32%     |
| 51-100         | 4        | 16%     |
| 251-500        | 3        | 12%     |
| 1-20           | 3        | 12%     |
| More than 3000 | 2        | 8%      |
| 1001-2000      | 2        | 8%      |
| 21-50          | 1        | 4%      |
| 2001-3000      | 1        | 4%      |
| 501-1000       | 1        | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 8        | 32%     |
| 1-20      | 7        | 28%     |
| 51-100    | 4        | 16%     |
| 101-250   | 3        | 12%     |
| 251-500   | 1        | 4%      |
| 2001-3000 | 1        | 4%      |
| 1001-2000 | 1        | 4%      |

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
| Detected | 19       | 54     | 65.52%  |
| Works    | 8        | 16     | 27.59%  |
| Malfunc  | 2        | 2      | 6.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 13       | 35.14%  |
| AMD                         | 11       | 29.73%  |
| SanDisk                     | 2        | 5.41%   |
| Samsung Electronics         | 2        | 5.41%   |
| Transcend                   | 1        | 2.7%    |
| Seagate Technology          | 1        | 2.7%    |
| Phison Electronics          | 1        | 2.7%    |
| OCZ Technology Group        | 1        | 2.7%    |
| Nvidia                      | 1        | 2.7%    |
| Micron Technology           | 1        | 2.7%    |
| Marvell Technology Group    | 1        | 2.7%    |
| Kingston Technology Company | 1        | 2.7%    |
| JMicron Technology          | 1        | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 10.64%  |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 4.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 4.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 4.26%   |
| Transcend Non-Volatile memory controller                                       | 1        | 2.13%   |
| Seagate Non-Volatile memory controller                                         | 1        | 2.13%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 2.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 2.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 2.13%   |
| Samsung NVMe SSD Controller 172X                                               | 1        | 2.13%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 2.13%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 2.13%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 2.13%   |
| Micron Non-Volatile memory controller                                          | 1        | 2.13%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 2.13%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 2.13%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.13%   |
| Intel Non-Volatile memory controller                                           | 1        | 2.13%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                     | 1        | 2.13%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 2.13%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 2.13%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 2.13%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 2.13%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.13%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 2.13%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 2.13%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                     | 1        | 2.13%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1        | 2.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 2.13%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 2.13%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 1        | 2.13%   |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 2.13%   |
| AMD FCH IDE Controller                                                         | 1        | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 52.63%  |
| NVMe | 9        | 23.68%  |
| IDE  | 8        | 21.05%  |
| RAID | 1        | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 52%     |
| AMD    | 12       | 48%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 8%      |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 2        | 8%      |
| Intel Xeon CPU X5492 @ 3.40GHz                  | 1        | 4%      |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 4%      |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz            | 1        | 4%      |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz             | 1        | 4%      |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 4%      |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 4%      |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 4%      |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 4%      |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 4%      |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 4%      |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 4%      |
| Intel Atom x5-Z8330 CPU @ 1.44GHz               | 1        | 4%      |
| Intel 11th Gen Core i5-11600 @ 2.80GHz          | 1        | 4%      |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 4%      |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 4%      |
| AMD Phenom II X4 965 Processor                  | 1        | 4%      |
| AMD FX-8150 Eight-Core Processor                | 1        | 4%      |
| AMD Athlon II X3 445 Processor                  | 1        | 4%      |
| AMD Athlon 3000G with Radeon Vega Graphics      | 1        | 4%      |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 4%      |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AMD Ryzen 5       | 5        | 20%     |
| Intel Xeon        | 4        | 16%     |
| Intel Core i5     | 4        | 16%     |
| Other             | 1        | 4%      |
| Intel Core i7     | 1        | 4%      |
| Intel Core i3     | 1        | 4%      |
| Intel Core 2 Quad | 1        | 4%      |
| Intel Atom        | 1        | 4%      |
| AMD Ryzen 9       | 1        | 4%      |
| AMD Phenom II X4  | 1        | 4%      |
| AMD FX            | 1        | 4%      |
| AMD Athlon II X3  | 1        | 4%      |
| AMD Athlon        | 1        | 4%      |
| AMD A4            | 1        | 4%      |
| AMD A10           | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 44%     |
| 6      | 4        | 16%     |
| 2      | 4        | 16%     |
| 8      | 2        | 8%      |
| 16     | 1        | 4%      |
| 12     | 1        | 4%      |
| 3      | 1        | 4%      |
| 1      | 1        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 92%     |
| 2      | 2        | 8%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 17       | 68%     |
| 1      | 8        | 32%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 25       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 55.56%  |
| 0x306a9    | 3        | 11.11%  |
| 0x406f1    | 2        | 7.41%   |
| 0xa0671    | 1        | 3.7%    |
| 0x406c4    | 1        | 3.7%    |
| 0x10677    | 1        | 3.7%    |
| 0x0a50000c | 1        | 3.7%    |
| 0x08108109 | 1        | 3.7%    |
| 0x08108102 | 1        | 3.7%    |
| 0x06001119 | 1        | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 4        | 16%     |
| Zen 3       | 3        | 12%     |
| IvyBridge   | 3        | 12%     |
| Penryn      | 2        | 8%      |
| K10         | 2        | 8%      |
| Broadwell   | 2        | 8%      |
| Westmere    | 1        | 4%      |
| Steamroller | 1        | 4%      |
| Skylake     | 1        | 4%      |
| Silvermont  | 1        | 4%      |
| Piledriver  | 1        | 4%      |
| Nehalem     | 1        | 4%      |
| Icelake     | 1        | 4%      |
| Haswell     | 1        | 4%      |
| Bulldozer   | 1        | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 13       | 48.15%  |
| Nvidia | 8        | 29.63%  |
| Intel  | 6        | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 11.11%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 7.41%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 7.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 7.41%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 3.7%    |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 3.7%    |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1        | 3.7%    |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 3.7%    |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1        | 3.7%    |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 3.7%    |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 3.7%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 3.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 3.7%    |
| Intel HD Graphics 530                                                                    | 1        | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 3.7%    |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 3.7%    |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 3.7%    |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 1        | 3.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 3.7%    |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 3.7%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 12       | 48%     |
| 1 x Nvidia   | 7        | 28%     |
| 1 x Intel    | 5        | 20%     |
| AMD + Nvidia | 1        | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 80%     |
| Proprietary | 4        | 16%     |
| Unknown     | 1        | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 64%     |
| 1.01-2.0   | 3        | 12%     |
| 7.01-8.0   | 2        | 8%      |
| 0.01-0.5   | 2        | 8%      |
| 3.01-4.0   | 1        | 4%      |
| 0.51-1.0   | 1        | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 10       | 40%     |
| Hewlett-Packard     | 3        | 12%     |
| SANYO               | 2        | 8%      |
| Philips             | 2        | 8%      |
| AOC                 | 2        | 8%      |
| Unknown (XXX)       | 1        | 4%      |
| Sony                | 1        | 4%      |
| Panasonic           | 1        | 4%      |
| Fujitsu Siemens     | 1        | 4%      |
| Dell                | 1        | 4%      |
| BenQ                | 1        | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 3.85%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 3.85%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 3.85%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 3.85%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1        | 3.85%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1        | 3.85%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 1        | 3.85%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1        | 3.85%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1        | 3.85%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 3.85%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1        | 3.85%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 3.85%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch     | 1        | 3.85%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 3.85%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1        | 3.85%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch               | 1        | 3.85%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                   | 1        | 3.85%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                               | 1        | 3.85%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 3.85%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 3.85%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 3.85%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 3.85%   |
| Dell LCD Monitor 1704FPV 1280x1024                                    | 1        | 3.85%   |
| BenQ GW2750H BNQ78C3 1920x1080 598x336mm 27.0-inch                    | 1        | 3.85%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 3.85%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 1        | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 56%     |
| 1920x540           | 3        | 12%     |
| 1920x1200 (WUXGA)  | 2        | 8%      |
| 3840x2160 (4K)     | 1        | 4%      |
| 3440x1440          | 1        | 4%      |
| 2560x1440 (QHD)    | 1        | 4%      |
| 1680x1050 (WSXGA+) | 1        | 4%      |
| 1366x768 (WXGA)    | 1        | 4%      |
| 1280x1024 (SXGA)   | 1        | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 23.08%  |
| 23      | 4        | 15.38%  |
| 27      | 3        | 11.54%  |
| 21      | 2        | 7.69%   |
| Unknown | 2        | 7.69%   |
| 72      | 1        | 3.85%   |
| 54      | 1        | 3.85%   |
| 47      | 1        | 3.85%   |
| 40      | 1        | 3.85%   |
| 34      | 1        | 3.85%   |
| 33      | 1        | 3.85%   |
| 31      | 1        | 3.85%   |
| 28      | 1        | 3.85%   |
| 18      | 1        | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 48%     |
| 401-500     | 3        | 12%     |
| 701-800     | 2        | 8%      |
| 601-700     | 2        | 8%      |
| 1001-1500   | 2        | 8%      |
| Unknown     | 2        | 8%      |
| 801-900     | 1        | 4%      |
| 1501-2000   | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 75%     |
| 16/10   | 3        | 12.5%   |
| 32/9    | 1        | 4.17%   |
| 21/9    | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 33.33%  |
| 351-500        | 4        | 16.67%  |
| 301-350        | 3        | 12.5%   |
| More than 1000 | 2        | 8.33%   |
| 251-300        | 2        | 8.33%   |
| 501-1000       | 2        | 8.33%   |
| Unknown        | 2        | 8.33%   |
| 141-150        | 1        | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 66.67%  |
| 1-50    | 3        | 12.5%   |
| 101-120 | 2        | 8.33%   |
| Unknown | 2        | 8.33%   |
| 121-160 | 1        | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 23       | 92%     |
| 2     | 2        | 8%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 15       | 45.45%  |
| Realtek Semiconductor | 12       | 36.36%  |
| Broadcom              | 2        | 6.06%   |
| Ralink Technology     | 1        | 3.03%   |
| Nvidia                | 1        | 3.03%   |
| MediaTek              | 1        | 3.03%   |
| Broadcom Limited      | 1        | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 25.64%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 7.69%   |
| Intel I211 Gigabit Network Connection                             | 2        | 5.13%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 5.13%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 2.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.56%   |
| Realtek 802.11ac NIC                                              | 1        | 2.56%   |
| Ralink RT3072 Wireless Adapter                                    | 1        | 2.56%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 2.56%   |
| Intel Wireless-AC 9260                                            | 1        | 2.56%   |
| Intel Wireless 7265                                               | 1        | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 2.56%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.56%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.56%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.56%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2.56%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.56%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.56%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 2.56%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 2.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 2.56%   |

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
| Realtek Semiconductor | 11       | 45.83%  |
| Intel                 | 10       | 41.67%  |
| Nvidia                | 1        | 4.17%   |
| Broadcom Limited      | 1        | 4.17%   |
| Broadcom              | 1        | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 38.46%  |
| Intel I211 Gigabit Network Connection                             | 2        | 7.69%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 7.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.85%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.85%   |
| Intel I210 Gigabit Network Connection                             | 1        | 3.85%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.85%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 3.85%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.85%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 3.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 3.85%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 3.85%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 3.85%   |

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
| Ethernet | 17       | 68%     |
| WiFi     | 8        | 32%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 60%     |
| 2     | 10       | 40%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 88%     |
| Yes  | 3        | 12%     |

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
| AMD                   | 15       | 41.67%  |
| Intel                 | 11       | 30.56%  |
| Nvidia                | 8        | 22.22%  |
| Texas Instruments     | 1        | 2.78%   |
| Realtek Semiconductor | 1        | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                | 5        | 10.87%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller   | 3        | 6.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                   | 3        | 6.52%   |
| Nvidia GK106 HDMI Audio Controller                                    | 2        | 4.35%   |
| Intel C610/X99 series chipset HD Audio Controller                     | 2        | 4.35%   |
| AMD SBx00 Azalia (Intel HDA)                                          | 2        | 4.35%   |
| AMD Renoir Radeon High Definition Audio Controller                    | 2        | 4.35%   |
| AMD FCH Azalia Controller                                             | 2        | 4.35%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                | 2        | 4.35%   |
| Texas Instruments PCM2902 Audio Codec                                 | 1        | 2.17%   |
| Realtek Semiconductor USB Audio                                       | 1        | 2.17%   |
| Nvidia MCP61 High Definition Audio                                    | 1        | 2.17%   |
| Nvidia GP108 High Definition Audio Controller                         | 1        | 2.17%   |
| Nvidia GP104 High Definition Audio Controller                         | 1        | 2.17%   |
| Nvidia GK110 High Definition Audio Controller                         | 1        | 2.17%   |
| Nvidia GF110 High Definition Audio Controller                         | 1        | 2.17%   |
| Nvidia GA106 High Definition Audio Controller                         | 1        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller      | 1        | 2.17%   |
| Intel Tiger Lake-H HD Audio Controller                                | 1        | 2.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                      | 1        | 2.17%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                   | 1        | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller   | 1        | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio              | 1        | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller       | 1        | 2.17%   |
| AMD Trinity HDMI Audio Controller                                     | 1        | 2.17%   |
| AMD Starship/Matisse HD Audio Controller                              | 1        | 2.17%   |
| AMD Kaveri HDMI/DP Audio Controller                                   | 1        | 2.17%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                        | 1        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                   | 1        | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]            | 1        | 2.17%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand] | 1        | 2.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]          | 1        | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 25%     |
| SK hynix            | 2        | 12.5%   |
| Samsung Electronics | 2        | 12.5%   |
| Micron Technology   | 2        | 12.5%   |
| Crucial             | 2        | 12.5%   |
| Transcend           | 1        | 6.25%   |
| Elpida              | 1        | 6.25%   |
| Corsair             | 1        | 6.25%   |
| A-DATA Technology   | 1        | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 11.76%  |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s     | 1        | 5.88%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 5.88%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 5.88%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s   | 1        | 5.88%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 5.88%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 1        | 5.88%   |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s   | 1        | 5.88%   |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s      | 1        | 5.88%   |
| Kingston RAM 9905403-011.A02LF 2GB DIMM DDR3 1333MT/s  | 1        | 5.88%   |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s    | 1        | 5.88%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s | 1        | 5.88%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s  | 1        | 5.88%   |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s    | 1        | 5.88%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s    | 1        | 5.88%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 1        | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 6        | 50%     |
| DDR3  | 5        | 41.67%  |
| SDRAM | 1        | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 9        | 81.82%  |
| SODIMM | 2        | 18.18%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 4        | 30.77%  |
| 16384 | 3        | 23.08%  |
| 8192  | 3        | 23.08%  |
| 2048  | 2        | 15.38%  |
| 32768 | 1        | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 35.71%  |
| 3200  | 2        | 14.29%  |
| 2400  | 2        | 14.29%  |
| 1333  | 2        | 14.29%  |
| 3600  | 1        | 7.14%   |
| 2667  | 1        | 7.14%   |
| 1066  | 1        | 7.14%   |

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
| 0     | 20       | 80%     |
| 1     | 3        | 12%     |
| 4     | 1        | 4%      |
| 2     | 1        | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 2        | 28.57%  |
| Sound            | 2        | 28.57%  |
| Net/wireless     | 1        | 14.29%  |
| Net/ethernet     | 1        | 14.29%  |
| Graphics card    | 1        | 14.29%  |

