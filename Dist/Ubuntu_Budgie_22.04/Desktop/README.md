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

Total: 36

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | X99S SLI PLUS               | [8c6fb84b12](https://linux-hardware.org/?probe=8c6fb84b12) | Feb 09, 2023 |
| ASRock   | FM2A88X Extreme4+           | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
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


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-52-generic      | 4        | 13.79%  |
| 5.15.0-46-generic      | 3        | 10.34%  |
| 5.15.0-43-generic      | 3        | 10.34%  |
| 5.15.0-30-generic      | 3        | 10.34%  |
| 5.15.0-57-generic      | 2        | 6.9%    |
| 5.15.0-33-generic      | 2        | 6.9%    |
| 5.15.0-27-generic      | 2        | 6.9%    |
| 5.15.0-25-generic      | 2        | 6.9%    |
| 5.17.2-051702-generic  | 1        | 3.45%   |
| 5.15.92-051592-generic | 1        | 3.45%   |
| 5.15.0-56-generic      | 1        | 3.45%   |
| 5.15.0-50-generic      | 1        | 3.45%   |
| 5.15.0-48-generic      | 1        | 3.45%   |
| 5.15.0-47-generic      | 1        | 3.45%   |
| 5.15.0-41-generic      | 1        | 3.45%   |
| 5.13.0-44-generic      | 1        | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 24       | 88.89%  |
| 5.17.2  | 1        | 3.7%    |
| 5.15.92 | 1        | 3.7%    |
| 5.13.0  | 1        | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 25       | 92.59%  |
| 5.17    | 1        | 3.7%    |
| 5.13    | 1        | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 27       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 27       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 27       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 19       | 70.37%  |
| Unknown | 7        | 25.93%  |
| GDM     | 1        | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 13       | 48.15%  |
| de_DE | 5        | 18.52%  |
| fr_FR | 2        | 7.41%   |
| es_ES | 2        | 7.41%   |
| en_GB | 2        | 7.41%   |
| es_MX | 1        | 3.7%    |
| en_CA | 1        | 3.7%    |
| el_GR | 1        | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 19       | 67.86%  |
| EFI  | 9        | 32.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 22       | 81.48%  |
| Overlay | 3        | 11.11%  |
| Zfs     | 1        | 3.7%    |
| Btrfs   | 1        | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 51.85%  |
| GPT     | 13       | 48.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 77.78%  |
| Yes       | 6        | 22.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 62.96%  |
| Yes       | 10       | 37.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 8        | 29.63%  |
| MSI                 | 4        | 14.81%  |
| Hewlett-Packard     | 3        | 11.11%  |
| Intel               | 2        | 7.41%   |
| Fujitsu             | 2        | 7.41%   |
| Dell                | 2        | 7.41%   |
| ASUSTek Computer    | 2        | 7.41%   |
| ASRock              | 2        | 7.41%   |
| Lenovo              | 1        | 3.7%    |
| Biostar             | 1        | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7C95                      | 1        | 3.7%    |
| MSI MS-7B86                      | 1        | 3.7%    |
| MSI MS-7A32                      | 1        | 3.7%    |
| MSI MS-7885                      | 1        | 3.7%    |
| Lenovo ThinkStation C20 4263BA7  | 1        | 3.7%    |
| Intel STK1A32SC                  | 1        | 3.7%    |
| Intel DP55WB AAE64798-206        | 1        | 3.7%    |
| HP Z440 Workstation              | 1        | 3.7%    |
| HP EliteDesk 800 G1 DM           | 1        | 3.7%    |
| HP 750-417c                      | 1        | 3.7%    |
| Gigabyte X570S AORUS PRO AX      | 1        | 3.7%    |
| Gigabyte M68MT-S2                | 1        | 3.7%    |
| Gigabyte GA-890GPA-UD3H          | 1        | 3.7%    |
| Gigabyte F2A78M-HD2              | 1        | 3.7%    |
| Gigabyte B75M-D3P                | 1        | 3.7%    |
| Gigabyte B75M-D3H                | 1        | 3.7%    |
| Gigabyte B550 AORUS ELITE AX V2  | 1        | 3.7%    |
| Gigabyte B450 I AORUS PRO WIFI   | 1        | 3.7%    |
| Fujitsu ESPRIMO Q910             | 1        | 3.7%    |
| Fujitsu D3348-B2                 | 1        | 3.7%    |
| Dell Precision WorkStation T7400 | 1        | 3.7%    |
| Dell OptiPlex 780                | 1        | 3.7%    |
| Biostar A960D+V3                 | 1        | 3.7%    |
| ASUS PRIME B560M-A               | 1        | 3.7%    |
| ASUS A88X-PRO                    | 1        | 3.7%    |
| ASRock FM2A88X Extreme4+         | 1        | 3.7%    |
| ASRock A300M-STX                 | 1        | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| MSI MS-7C95             | 1        | 3.7%    |
| MSI MS-7B86             | 1        | 3.7%    |
| MSI MS-7A32             | 1        | 3.7%    |
| MSI MS-7885             | 1        | 3.7%    |
| Lenovo ThinkStation     | 1        | 3.7%    |
| Intel STK1A32SC         | 1        | 3.7%    |
| Intel DP55WB            | 1        | 3.7%    |
| HP Z440                 | 1        | 3.7%    |
| HP EliteDesk            | 1        | 3.7%    |
| HP 750-417c             | 1        | 3.7%    |
| Gigabyte X570S          | 1        | 3.7%    |
| Gigabyte M68MT-S2       | 1        | 3.7%    |
| Gigabyte GA-890GPA-UD3H | 1        | 3.7%    |
| Gigabyte F2A78M-HD2     | 1        | 3.7%    |
| Gigabyte B75M-D3P       | 1        | 3.7%    |
| Gigabyte B75M-D3H       | 1        | 3.7%    |
| Gigabyte B550           | 1        | 3.7%    |
| Gigabyte B450           | 1        | 3.7%    |
| Fujitsu ESPRIMO         | 1        | 3.7%    |
| Fujitsu D3348-B2        | 1        | 3.7%    |
| Dell Precision          | 1        | 3.7%    |
| Dell OptiPlex           | 1        | 3.7%    |
| Biostar A960D+V3        | 1        | 3.7%    |
| ASUS PRIME              | 1        | 3.7%    |
| ASUS A88X-PRO           | 1        | 3.7%    |
| ASRock FM2A88X          | 1        | 3.7%    |
| ASRock A300M-STX        | 1        | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 4        | 14.81%  |
| 2018 | 3        | 11.11%  |
| 2010 | 3        | 11.11%  |
| 2021 | 2        | 7.41%   |
| 2020 | 2        | 7.41%   |
| 2017 | 2        | 7.41%   |
| 2016 | 2        | 7.41%   |
| 2015 | 2        | 7.41%   |
| 2012 | 2        | 7.41%   |
| 2019 | 1        | 3.7%    |
| 2013 | 1        | 3.7%    |
| 2011 | 1        | 3.7%    |
| 2009 | 1        | 3.7%    |
| 2008 | 1        | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 27       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 27       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 8        | 29.63%  |
| 8.01-16.0       | 7        | 25.93%  |
| 4.01-8.0        | 6        | 22.22%  |
| 32.01-64.0      | 2        | 7.41%   |
| More than 256.0 | 1        | 3.7%    |
| 24.01-32.0      | 1        | 3.7%    |
| 64.01-256.0     | 1        | 3.7%    |
| 1.01-2.0        | 1        | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 11       | 37.93%  |
| 2.01-3.0   | 9        | 31.03%  |
| 4.01-8.0   | 5        | 17.24%  |
| 3.01-4.0   | 2        | 6.9%    |
| 16.01-24.0 | 1        | 3.45%   |
| 8.01-16.0  | 1        | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 33.33%  |
| 1      | 9        | 33.33%  |
| 4      | 3        | 11.11%  |
| 6      | 2        | 7.41%   |
| 3      | 2        | 7.41%   |
| 8      | 1        | 3.7%    |
| 7      | 1        | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 51.85%  |
| Yes       | 13       | 48.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 96.3%   |
| No        | 1        | 3.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 55.56%  |
| No        | 12       | 44.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 62.96%  |
| Yes       | 10       | 37.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 8        | 29.63%  |
| Germany     | 4        | 14.81%  |
| UK          | 2        | 7.41%   |
| Switzerland | 2        | 7.41%   |
| France      | 2        | 7.41%   |
| Spain       | 1        | 3.7%    |
| Slovenia    | 1        | 3.7%    |
| Norway      | 1        | 3.7%    |
| Mexico      | 1        | 3.7%    |
| Greece      | 1        | 3.7%    |
| Croatia     | 1        | 3.7%    |
| Brazil      | 1        | 3.7%    |
| Austria     | 1        | 3.7%    |
| Argentina   | 1        | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milwaukee             | 2        | 7.14%   |
| Zurich                | 1        | 3.57%   |
| Walled Lake           | 1        | 3.57%   |
| Trondheim             | 1        | 3.57%   |
| Tocantins             | 1        | 3.57%   |
| Tann                  | 1        | 3.57%   |
| Seattle               | 1        | 3.57%   |
| San Luis Potosí City | 1        | 3.57%   |
| Rueil-Malmaison       | 1        | 3.57%   |
| Pula                  | 1        | 3.57%   |
| Pine Island           | 1        | 3.57%   |
| New York              | 1        | 3.57%   |
| Maribor               | 1        | 3.57%   |
| Madrid                | 1        | 3.57%   |
| London                | 1        | 3.57%   |
| Limay                 | 1        | 3.57%   |
| Kittsee               | 1        | 3.57%   |
| Kirkcaldy             | 1        | 3.57%   |
| Hamburg               | 1        | 3.57%   |
| Ennepetal             | 1        | 3.57%   |
| Dortmund              | 1        | 3.57%   |
| Delbrueck             | 1        | 3.57%   |
| Colon                 | 1        | 3.57%   |
| Caslano               | 1        | 3.57%   |
| Camp Hill             | 1        | 3.57%   |
| Bradenton             | 1        | 3.57%   |
| Athens                | 1        | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 17     | 20.75%  |
| Samsung Electronics | 6        | 25     | 11.32%  |
| WDC                 | 5        | 6      | 9.43%   |
| Sandisk             | 5        | 6      | 9.43%   |
| Toshiba             | 3        | 3      | 5.66%   |
| OCZ                 | 2        | 2      | 3.77%   |
| Micron Technology   | 2        | 2      | 3.77%   |
| Kingston            | 2        | 3      | 3.77%   |
| Crucial             | 2        | 2      | 3.77%   |
| Zheino              | 1        | 1      | 1.89%   |
| Unknown             | 1        | 1      | 1.89%   |
| Transcend           | 1        | 1      | 1.89%   |
| SPCC                | 1        | 1      | 1.89%   |
| SK hynix            | 1        | 1      | 1.89%   |
| PNY                 | 1        | 1      | 1.89%   |
| Phison              | 1        | 1      | 1.89%   |
| Mushkin             | 1        | 1      | 1.89%   |
| Maxtor              | 1        | 1      | 1.89%   |
| JMicron Technology  | 1        | 1      | 1.89%   |
| Intel               | 1        | 1      | 1.89%   |
| HGST                | 1        | 1      | 1.89%   |
| China               | 1        | 1      | 1.89%   |
| ASMT109x            | 1        | 1      | 1.89%   |
| A-DATA Technology   | 1        | 1      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000LM048-2E7172 1TB     | 2        | 3.08%   |
| SanDisk SDSSDA120G 120GB           | 2        | 3.08%   |
| Samsung SSD 870 EVO 250GB          | 2        | 3.08%   |
| Samsung SSD 850 PRO 256GB          | 2        | 3.08%   |
| Zheino CHN-25SATAC3-120 120GB      | 1        | 1.54%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 1.54%   |
| WDC WD40PURZ-85TTDY0 4TB           | 1        | 1.54%   |
| WDC WD3200LPVX-22V0TT0 320GB       | 1        | 1.54%   |
| WDC WD1600AAJS-60WAA0 160GB        | 1        | 1.54%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1.54%   |
| WDC WD10EADS-00M2B0 1TB            | 1        | 1.54%   |
| Unknown SD/MMC/MS PRO 16GB         | 1        | 1.54%   |
| Transcend TS128GMTE110S 128GB      | 1        | 1.54%   |
| Toshiba MD04ACA400 4TB             | 1        | 1.54%   |
| Toshiba HDWD240 4TB                | 1        | 1.54%   |
| Toshiba HDWD220 2TB                | 1        | 1.54%   |
| SPCC Solid State Disk 256GB        | 1        | 1.54%   |
| SK hynix SC210 2.5 7MM 128GB SSD   | 1        | 1.54%   |
| Seagate ST9500325AS 500GB          | 1        | 1.54%   |
| Seagate ST8000VN0022-2EL112 8TB    | 1        | 1.54%   |
| Seagate ST500LT012-1DG142 500GB    | 1        | 1.54%   |
| Seagate ST380815AS 80GB            | 1        | 1.54%   |
| Seagate ST3500418AS 500GB          | 1        | 1.54%   |
| Seagate ST3500412AS 500GB          | 1        | 1.54%   |
| Seagate ST3160815AS 160GB          | 1        | 1.54%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 1.54%   |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 1.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1.54%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1        | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1.54%   |
| Seagate ST1000DM003-1SB10C 1TB     | 1        | 1.54%   |
| Seagate NVMe SSD Drive 500GB       | 1        | 1.54%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB | 1        | 1.54%   |
| SanDisk NVMe SSD Drive 500GB       | 1        | 1.54%   |
| SanDisk DF4032  32GB               | 1        | 1.54%   |
| Samsung SSD 960 PRO 512GB          | 1        | 1.54%   |
| Samsung SSD 850 EVO 500GB          | 1        | 1.54%   |
| Samsung SSD 850 EVO 1TB            | 1        | 1.54%   |
| Samsung SSD 840 EVO 250GB          | 1        | 1.54%   |
| Samsung SSD 840 EVO 1TB            | 1        | 1.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 16     | 44%     |
| WDC                 | 5        | 6      | 20%     |
| Toshiba             | 3        | 3      | 12%     |
| Unknown             | 1        | 1      | 4%      |
| Samsung Electronics | 1        | 2      | 4%      |
| Maxtor              | 1        | 1      | 4%      |
| JMicron Technology  | 1        | 1      | 4%      |
| HGST                | 1        | 1      | 4%      |
| ASMT109x            | 1        | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 19     | 22.22%  |
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
| China               | 1        | 1      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 32     | 38.64%  |
| SSD  | 16       | 34     | 36.36%  |
| NVMe | 10       | 14     | 22.73%  |
| MMC  | 1        | 1      | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 25       | 63     | 64.1%   |
| NVMe | 10       | 14     | 25.64%  |
| SAS  | 3        | 3      | 7.69%   |
| MMC  | 1        | 1      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 42     | 58.97%  |
| 0.51-1.0   | 9        | 15     | 23.08%  |
| 3.01-4.0   | 4        | 4      | 10.26%  |
| 1.01-2.0   | 2        | 3      | 5.13%   |
| 4.01-10.0  | 1        | 2      | 2.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 29.63%  |
| 1-20           | 4        | 14.81%  |
| 51-100         | 4        | 14.81%  |
| More than 3000 | 3        | 11.11%  |
| 251-500        | 3        | 11.11%  |
| 1001-2000      | 2        | 7.41%   |
| 21-50          | 1        | 3.7%    |
| 2001-3000      | 1        | 3.7%    |
| 501-1000       | 1        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 8        | 29.63%  |
| 1-20           | 8        | 29.63%  |
| 51-100         | 4        | 14.81%  |
| 101-250        | 3        | 11.11%  |
| More than 3000 | 1        | 3.7%    |
| 251-500        | 1        | 3.7%    |
| 2001-3000      | 1        | 3.7%    |
| 1001-2000      | 1        | 3.7%    |

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
| Detected | 20       | 55     | 64.52%  |
| Works    | 9        | 24     | 29.03%  |
| Malfunc  | 2        | 2      | 6.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 14       | 35%     |
| AMD                         | 12       | 30%     |
| Samsung Electronics         | 3        | 7.5%    |
| SanDisk                     | 2        | 5%      |
| Transcend                   | 1        | 2.5%    |
| Seagate Technology          | 1        | 2.5%    |
| Phison Electronics          | 1        | 2.5%    |
| OCZ Technology Group        | 1        | 2.5%    |
| Nvidia                      | 1        | 2.5%    |
| Micron Technology           | 1        | 2.5%    |
| Marvell Technology Group    | 1        | 2.5%    |
| Kingston Technology Company | 1        | 2.5%    |
| JMicron Technology          | 1        | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6        | 11.54%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 3.85%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 3.85%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 3.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 3.85%   |
| AMD FCH IDE Controller                                                         | 2        | 3.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 3.85%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 3.85%   |
| Transcend Non-Volatile memory controller                                       | 1        | 1.92%   |
| Seagate Non-Volatile memory controller                                         | 1        | 1.92%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 1.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 1.92%   |
| Samsung NVMe SSD Controller 172X                                               | 1        | 1.92%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 1.92%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 1.92%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.92%   |
| Micron Non-Volatile memory controller                                          | 1        | 1.92%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.92%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 1.92%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 1.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.92%   |
| Intel Non-Volatile memory controller                                           | 1        | 1.92%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                     | 1        | 1.92%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 1.92%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.92%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 1.92%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                     | 1        | 1.92%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1        | 1.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 1.92%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 1.92%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 1        | 1.92%   |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 22       | 52.38%  |
| NVMe | 10       | 23.81%  |
| IDE  | 9        | 21.43%  |
| RAID | 1        | 2.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 51.85%  |
| AMD    | 13       | 48.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 7.41%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 2        | 7.41%   |
| Intel Xeon CPU X5492 @ 3.40GHz                  | 1        | 3.7%    |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 3.7%    |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz            | 1        | 3.7%    |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz             | 1        | 3.7%    |
| Intel Core i7-5820K CPU @ 3.30GHz               | 1        | 3.7%    |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 3.7%    |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 3.7%    |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 3.7%    |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 3.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 3.7%    |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 3.7%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 3.7%    |
| Intel Atom x5-Z8330 CPU @ 1.44GHz               | 1        | 3.7%    |
| Intel 11th Gen Core i5-11600 @ 2.80GHz          | 1        | 3.7%    |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 3.7%    |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 3.7%    |
| AMD Phenom II X4 965 Processor                  | 1        | 3.7%    |
| AMD FX-8150 Eight-Core Processor                | 1        | 3.7%    |
| AMD Athlon X4 845 Quad Core Processor           | 1        | 3.7%    |
| AMD Athlon II X3 445 Processor                  | 1        | 3.7%    |
| AMD Athlon 3000G with Radeon Vega Graphics      | 1        | 3.7%    |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 3.7%    |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AMD Ryzen 5       | 5        | 18.52%  |
| Intel Xeon        | 4        | 14.81%  |
| Intel Core i5     | 4        | 14.81%  |
| Intel Core i7     | 2        | 7.41%   |
| Other             | 1        | 3.7%    |
| Intel Core i3     | 1        | 3.7%    |
| Intel Core 2 Quad | 1        | 3.7%    |
| Intel Atom        | 1        | 3.7%    |
| AMD Ryzen 9       | 1        | 3.7%    |
| AMD Phenom II X4  | 1        | 3.7%    |
| AMD FX            | 1        | 3.7%    |
| AMD Athlon X4     | 1        | 3.7%    |
| AMD Athlon II X3  | 1        | 3.7%    |
| AMD Athlon        | 1        | 3.7%    |
| AMD A4            | 1        | 3.7%    |
| AMD A10           | 1        | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 40.74%  |
| 6      | 5        | 18.52%  |
| 2      | 5        | 18.52%  |
| 8      | 2        | 7.41%   |
| 16     | 1        | 3.7%    |
| 12     | 1        | 3.7%    |
| 3      | 1        | 3.7%    |
| 1      | 1        | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 92.59%  |
| 2      | 2        | 7.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 70.37%  |
| 1      | 8        | 29.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 27       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 58.62%  |
| 0x306a9    | 3        | 10.34%  |
| 0x406f1    | 2        | 6.9%    |
| 0xa0671    | 1        | 3.45%   |
| 0x406c4    | 1        | 3.45%   |
| 0x10677    | 1        | 3.45%   |
| 0x0a50000c | 1        | 3.45%   |
| 0x08108109 | 1        | 3.45%   |
| 0x08108102 | 1        | 3.45%   |
| 0x06001119 | 1        | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 4        | 14.81%  |
| Zen 3       | 3        | 11.11%  |
| IvyBridge   | 3        | 11.11%  |
| Penryn      | 2        | 7.41%   |
| K10         | 2        | 7.41%   |
| Haswell     | 2        | 7.41%   |
| Broadwell   | 2        | 7.41%   |
| Westmere    | 1        | 3.7%    |
| Steamroller | 1        | 3.7%    |
| Skylake     | 1        | 3.7%    |
| Silvermont  | 1        | 3.7%    |
| Piledriver  | 1        | 3.7%    |
| Nehalem     | 1        | 3.7%    |
| Icelake     | 1        | 3.7%    |
| Excavator   | 1        | 3.7%    |
| Bulldozer   | 1        | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 13       | 44.83%  |
| Nvidia | 10       | 34.48%  |
| Intel  | 6        | 20.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 10.34%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 6.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 6.9%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 6.9%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 3.45%   |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 3.45%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 3.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 3.45%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1        | 3.45%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 3.45%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1        | 3.45%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 3.45%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 3.45%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 3.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 3.45%   |
| Intel HD Graphics 530                                                                    | 1        | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 3.45%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 3.45%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 3.45%   |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 1        | 3.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 3.45%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 3.45%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 12       | 44.44%  |
| 1 x Nvidia   | 9        | 33.33%  |
| 1 x Intel    | 5        | 18.52%  |
| AMD + Nvidia | 1        | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 21       | 77.78%  |
| Proprietary | 5        | 18.52%  |
| Unknown     | 1        | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 62.96%  |
| 1.01-2.0   | 3        | 11.11%  |
| 7.01-8.0   | 2        | 7.41%   |
| 3.01-4.0   | 2        | 7.41%   |
| 0.01-0.5   | 2        | 7.41%   |
| 0.51-1.0   | 1        | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 10       | 37.04%  |
| Hewlett-Packard     | 3        | 11.11%  |
| SANYO               | 2        | 7.41%   |
| Philips             | 2        | 7.41%   |
| AOC                 | 2        | 7.41%   |
| Unknown (XXX)       | 1        | 3.7%    |
| Sony                | 1        | 3.7%    |
| Panasonic           | 1        | 3.7%    |
| LG Electronics      | 1        | 3.7%    |
| HKC                 | 1        | 3.7%    |
| Fujitsu Siemens     | 1        | 3.7%    |
| Dell                | 1        | 3.7%    |
| BenQ                | 1        | 3.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 3.57%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 3.57%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 3.57%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1        | 3.57%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1        | 3.57%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch     | 1        | 3.57%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1        | 3.57%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 3.57%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1        | 3.57%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 3.57%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch     | 1        | 3.57%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 3.57%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1        | 3.57%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch               | 1        | 3.57%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                   | 1        | 3.57%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                               | 1        | 3.57%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                      | 1        | 3.57%   |
| HKC LCD Monitor HKC2160 1920x1080 360x270mm 17.7-inch                 | 1        | 3.57%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 3.57%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 3.57%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 3.57%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 3.57%   |
| Dell LCD Monitor 1704FPV 1280x1024                                    | 1        | 3.57%   |
| BenQ GW2750H BNQ78C3 1920x1080 598x336mm 27.0-inch                    | 1        | 3.57%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 3.57%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 1        | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 55.56%  |
| 1920x540           | 3        | 11.11%  |
| 3840x2160 (4K)     | 2        | 7.41%   |
| 1920x1200 (WUXGA)  | 2        | 7.41%   |
| 3440x1440          | 1        | 3.7%    |
| 2560x1440 (QHD)    | 1        | 3.7%    |
| 1680x1050 (WSXGA+) | 1        | 3.7%    |
| 1366x768 (WXGA)    | 1        | 3.7%    |
| 1280x1024 (SXGA)   | 1        | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 21.43%  |
| 23      | 4        | 14.29%  |
| 27      | 3        | 10.71%  |
| Unknown | 3        | 10.71%  |
| 21      | 2        | 7.14%   |
| 72      | 1        | 3.57%   |
| 54      | 1        | 3.57%   |
| 47      | 1        | 3.57%   |
| 40      | 1        | 3.57%   |
| 34      | 1        | 3.57%   |
| 33      | 1        | 3.57%   |
| 31      | 1        | 3.57%   |
| 28      | 1        | 3.57%   |
| 18      | 1        | 3.57%   |
| 17      | 1        | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 44.44%  |
| 401-500     | 3        | 11.11%  |
| Unknown     | 3        | 11.11%  |
| 701-800     | 2        | 7.41%   |
| 601-700     | 2        | 7.41%   |
| 1001-1500   | 2        | 7.41%   |
| 801-900     | 1        | 3.7%    |
| 351-400     | 1        | 3.7%    |
| 1501-2000   | 1        | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 69.23%  |
| 16/10   | 3        | 11.54%  |
| Unknown | 2        | 7.69%   |
| 4/3     | 1        | 3.85%   |
| 32/9    | 1        | 3.85%   |
| 21/9    | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 30.77%  |
| 351-500        | 4        | 15.38%  |
| 301-350        | 3        | 11.54%  |
| Unknown        | 3        | 11.54%  |
| More than 1000 | 2        | 7.69%   |
| 251-300        | 2        | 7.69%   |
| 501-1000       | 2        | 7.69%   |
| 151-200        | 1        | 3.85%   |
| 141-150        | 1        | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 61.54%  |
| 1-50    | 3        | 11.54%  |
| Unknown | 3        | 11.54%  |
| 121-160 | 2        | 7.69%   |
| 101-120 | 2        | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 92.59%  |
| 2     | 2        | 7.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 16       | 43.24%  |
| Realtek Semiconductor | 13       | 35.14%  |
| Broadcom              | 2        | 5.41%   |
| Ralink Technology     | 1        | 2.7%    |
| Qualcomm Atheros      | 1        | 2.7%    |
| Nvidia                | 1        | 2.7%    |
| Microsoft             | 1        | 2.7%    |
| MediaTek              | 1        | 2.7%    |
| Broadcom Limited      | 1        | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 23.26%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 6.98%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.65%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 4.65%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 2.33%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 2.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.33%   |
| Realtek 802.11ac NIC                                              | 1        | 2.33%   |
| Ralink RT3072 Wireless Adapter                                    | 1        | 2.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.33%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.33%   |
| Microsoft Wireless XBox Controller Dongle                         | 1        | 2.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 2.33%   |
| Intel Wireless-AC 9260                                            | 1        | 2.33%   |
| Intel Wireless 7265                                               | 1        | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 2.33%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.33%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.33%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.33%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.33%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2.33%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.33%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.33%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 2.33%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 2.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 46.67%  |
| Realtek Semiconductor | 4        | 26.67%  |
| Ralink Technology     | 1        | 6.67%   |
| Microsoft             | 1        | 6.67%   |
| MediaTek              | 1        | 6.67%   |
| Broadcom              | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]    | 3        | 20%     |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter | 1        | 6.67%   |
| Realtek RTL8188EE Wireless Network Adapter          | 1        | 6.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter             | 1        | 6.67%   |
| Realtek 802.11ac NIC                                | 1        | 6.67%   |
| Ralink RT3072 Wireless Adapter                      | 1        | 6.67%   |
| Microsoft Wireless XBox Controller Dongle           | 1        | 6.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz             | 1        | 6.67%   |
| Intel Wireless-AC 9260                              | 1        | 6.67%   |
| Intel Wireless 7265                                 | 1        | 6.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz              | 1        | 6.67%   |
| Intel Wi-Fi 6 AX200                                 | 1        | 6.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter  | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 42.31%  |
| Intel                 | 11       | 42.31%  |
| Qualcomm Atheros      | 1        | 3.85%   |
| Nvidia                | 1        | 3.85%   |
| Broadcom Limited      | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 35.71%  |
| Intel I211 Gigabit Network Connection                             | 2        | 7.14%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 7.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 3.57%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.57%   |
| Intel I210 Gigabit Network Connection                             | 1        | 3.57%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.57%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.57%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 3.57%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.57%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 3.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 3.57%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 3.57%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 63.41%  |
| WiFi     | 15       | 36.59%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 70.37%  |
| WiFi     | 8        | 29.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 59.26%  |
| 2     | 11       | 40.74%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 85.19%  |
| Yes  | 4        | 14.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 60%     |
| Cambridge Silicon Radio | 2        | 20%     |
| MediaTek                | 1        | 10%     |
| Broadcom                | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 20%     |
| MediaTek Wireless_Device                            | 1        | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 10%     |
| Intel Bluetooth wireless interface                  | 1        | 10%     |
| Intel AX210 Bluetooth                               | 1        | 10%     |
| Intel AX200 Bluetooth                               | 1        | 10%     |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 16       | 40%     |
| Intel                 | 12       | 30%     |
| Nvidia                | 10       | 25%     |
| Texas Instruments     | 1        | 2.5%    |
| Realtek Semiconductor | 1        | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                | 5        | 10%     |
| Intel C610/X99 series chipset HD Audio Controller                     | 3        | 6%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller   | 3        | 6%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                   | 3        | 6%      |
| AMD FCH Azalia Controller                                             | 3        | 6%      |
| Nvidia GK106 HDMI Audio Controller                                    | 2        | 4%      |
| AMD SBx00 Azalia (Intel HDA)                                          | 2        | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                    | 2        | 4%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                | 2        | 4%      |
| Texas Instruments PCM2902 Audio Codec                                 | 1        | 2%      |
| Realtek Semiconductor USB Audio                                       | 1        | 2%      |
| Nvidia MCP61 High Definition Audio                                    | 1        | 2%      |
| Nvidia GP108 High Definition Audio Controller                         | 1        | 2%      |
| Nvidia GP104 High Definition Audio Controller                         | 1        | 2%      |
| Nvidia GM204 High Definition Audio Controller                         | 1        | 2%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]         | 1        | 2%      |
| Nvidia GK110 High Definition Audio Controller                         | 1        | 2%      |
| Nvidia GF110 High Definition Audio Controller                         | 1        | 2%      |
| Nvidia GA106 High Definition Audio Controller                         | 1        | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller      | 1        | 2%      |
| Intel Tiger Lake-H HD Audio Controller                                | 1        | 2%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                      | 1        | 2%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                   | 1        | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller   | 1        | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio              | 1        | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller       | 1        | 2%      |
| AMD Trinity HDMI Audio Controller                                     | 1        | 2%      |
| AMD Starship/Matisse HD Audio Controller                              | 1        | 2%      |
| AMD Kaveri HDMI/DP Audio Controller                                   | 1        | 2%      |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                        | 1        | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                   | 1        | 2%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]            | 1        | 2%      |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand] | 1        | 2%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]          | 1        | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 23.53%  |
| Crucial             | 3        | 17.65%  |
| SK hynix            | 2        | 11.76%  |
| Samsung Electronics | 2        | 11.76%  |
| Micron Technology   | 2        | 11.76%  |
| Transcend           | 1        | 5.88%   |
| Elpida              | 1        | 5.88%   |
| Corsair             | 1        | 5.88%   |
| A-DATA Technology   | 1        | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 11.11%  |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s     | 1        | 5.56%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 5.56%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 5.56%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s   | 1        | 5.56%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 5.56%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 1        | 5.56%   |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s   | 1        | 5.56%   |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s      | 1        | 5.56%   |
| Kingston RAM 9905403-011.A02LF 2GB DIMM DDR3 1333MT/s  | 1        | 5.56%   |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s    | 1        | 5.56%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s | 1        | 5.56%   |
| Crucial RAM CT8G4DFD8213.C16FAD 8GB DIMM DDR4 2133MT/s | 1        | 5.56%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM 1600MT/s       | 1        | 5.56%   |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s    | 1        | 5.56%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s    | 1        | 5.56%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 7        | 53.85%  |
| DDR3  | 5        | 38.46%  |
| SDRAM | 1        | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 10       | 83.33%  |
| SODIMM | 2        | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 28.57%  |
| 4096  | 4        | 28.57%  |
| 16384 | 3        | 21.43%  |
| 2048  | 2        | 14.29%  |
| 32768 | 1        | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 33.33%  |
| 3200  | 2        | 13.33%  |
| 2400  | 2        | 13.33%  |
| 1333  | 2        | 13.33%  |
| 3600  | 1        | 6.67%   |
| 2667  | 1        | 6.67%   |
| 2133  | 1        | 6.67%   |
| 1066  | 1        | 6.67%   |

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
| Logitech            | 2        | 50%     |
| Samsung Electronics | 1        | 25%     |
| Microdia            | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech HD Pro Webcam C920 | 2        | 50%     |
| Samsung Galaxy A5 (MTP)     | 1        | 25%     |
| Microdia Camera             | 1        | 25%     |

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
| 0     | 21       | 77.78%  |
| 1     | 3        | 11.11%  |
| 2     | 2        | 7.41%   |
| 4     | 1        | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 33.33%  |
| Sound            | 2        | 22.22%  |
| Net/wireless     | 1        | 11.11%  |
| Net/ethernet     | 1        | 11.11%  |
| Graphics card    | 1        | 11.11%  |
| Bluetooth        | 1        | 11.11%  |

