LinuxFX 10 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for LinuxFX 10.

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

Total: 35

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | P8Z77-V PRO/THUNDERBOLT | [793f82cda7](https://linux-hardware.org/?probe=793f82cda7) | Sep 03, 2022 |
| ASUSTek  | M5A78L-M/USB3           | [3db0355713](https://linux-hardware.org/?probe=3db0355713) | Aug 12, 2022 |
| Apple    | Mac-F221BEC8            | [92c20deb50](https://linux-hardware.org/?probe=92c20deb50) | May 17, 2022 |
| Gigabyte | GA-78LMT-S2P            | [b8194d3077](https://linux-hardware.org/?probe=b8194d3077) | May 01, 2022 |
| Gigabyte | GA-78LMT-S2P            | [3aeeaee161](https://linux-hardware.org/?probe=3aeeaee161) | Apr 23, 2022 |
| ASRock   | 970 Extreme4            | [a30d1aa4b9](https://linux-hardware.org/?probe=a30d1aa4b9) | Dec 29, 2021 |
| Gigabyte | G31M-ES2C               | [5afa9a7018](https://linux-hardware.org/?probe=5afa9a7018) | Dec 23, 2021 |
| ASRock   | 970 Extreme4            | [85b942a5c3](https://linux-hardware.org/?probe=85b942a5c3) | Oct 30, 2021 |
| ASRock   | 970 Extreme4            | [022942c4aa](https://linux-hardware.org/?probe=022942c4aa) | Oct 30, 2021 |
| MSI      | MS-7309                 | [33faf5dbef](https://linux-hardware.org/?probe=33faf5dbef) | Oct 14, 2021 |
| MSI      | MS-7309                 | [b0ddfaaa86](https://linux-hardware.org/?probe=b0ddfaaa86) | Oct 12, 2021 |
| PCWare   | IPMH61R2                | [62d2476431](https://linux-hardware.org/?probe=62d2476431) | Sep 27, 2021 |
| Gigabyte | X570 UD                 | [e1777d09cb](https://linux-hardware.org/?probe=e1777d09cb) | Sep 10, 2021 |
| MSI      | A88XI AC                | [1306310e52](https://linux-hardware.org/?probe=1306310e52) | Aug 02, 2021 |
| MSI      | A88XI AC                | [ebdf5c76be](https://linux-hardware.org/?probe=ebdf5c76be) | Aug 02, 2021 |
| Intel    | DG31PR AAD97573-306     | [a81005ef0b](https://linux-hardware.org/?probe=a81005ef0b) | Jul 10, 2021 |
| ASRock   | B450M Steel Legend      | [42869f7bb5](https://linux-hardware.org/?probe=42869f7bb5) | Jun 20, 2021 |
| Dell     | 0TVR1F A01              | [4022d93b8a](https://linux-hardware.org/?probe=4022d93b8a) | Apr 18, 2021 |
| ASRock   | N68-GE3 UCC             | [f2a9721ca5](https://linux-hardware.org/?probe=f2a9721ca5) | Feb 25, 2021 |
| Gigabyte | G31M-S2C                | [95c9698f2b](https://linux-hardware.org/?probe=95c9698f2b) | Feb 24, 2021 |
| ASRock   | ConRoe1333-D667         | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| MSI      | B450M PRO-M2 MAX        | [ecbdfd2c54](https://linux-hardware.org/?probe=ecbdfd2c54) | Jan 17, 2021 |
| HP       | 2B1E                    | [940750f549](https://linux-hardware.org/?probe=940750f549) | Jan 05, 2021 |
| ASUSTek  | P8Z68-V LE              | [356c40c60b](https://linux-hardware.org/?probe=356c40c60b) | Dec 27, 2020 |
| ASUSTek  | H87-PRO                 | [e2287834ae](https://linux-hardware.org/?probe=e2287834ae) | Dec 10, 2020 |
| ASUSTek  | H87-PRO                 | [17bd61ae55](https://linux-hardware.org/?probe=17bd61ae55) | Dec 09, 2020 |
| Gigabyte | B450 AORUS M            | [8e3b4356b7](https://linux-hardware.org/?probe=8e3b4356b7) | Dec 03, 2020 |
| Dell     | 0V6D8J A00              | [5b4385cd10](https://linux-hardware.org/?probe=5b4385cd10) | Nov 09, 2020 |
| Dell     | 0V6D8J A00              | [13e1111610](https://linux-hardware.org/?probe=13e1111610) | Nov 09, 2020 |
| Acer     | Aspire TC-105           | [0ee92155a3](https://linux-hardware.org/?probe=0ee92155a3) | Nov 04, 2020 |
| ECS      | A780GM-A                | [cf03b0c26b](https://linux-hardware.org/?probe=cf03b0c26b) | Nov 04, 2020 |
| Gigabyte | 970A-DS3P               | [c5a0f02633](https://linux-hardware.org/?probe=c5a0f02633) | Jul 24, 2020 |
| Dell     | 0Y644J A02              | [96f0709424](https://linux-hardware.org/?probe=96f0709424) | Jul 16, 2020 |
| Gigabyte | B85M-D3H                | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Intel    | B75                     | [dc59852769](https://linux-hardware.org/?probe=dc59852769) | Jul 11, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.4.0-52-generic            | 6        | 24%     |
| 5.4.0-72-generic            | 4        | 16%     |
| 5.6.15-windowsfx-10-generic | 2        | 8%      |
| 5.5.19-050519-generic       | 2        | 8%      |
| 5.4.0-56-generic            | 2        | 8%      |
| 5.7.8-windowsfx-generic     | 1        | 4%      |
| 5.7.15-050715-generic       | 1        | 4%      |
| 5.4.0-88-generic            | 1        | 4%      |
| 5.4.0-66-generic            | 1        | 4%      |
| 5.4.0-65-generic            | 1        | 4%      |
| 5.4.0-125-generic           | 1        | 4%      |
| 5.4.0-124-generic           | 1        | 4%      |
| 5.4.0-110-generic           | 1        | 4%      |
| 5.4.0-107-generic           | 1        | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 19       | 76%     |
| 5.6.15  | 2        | 8%      |
| 5.5.19  | 2        | 8%      |
| 5.7.8   | 1        | 4%      |
| 5.7.15  | 1        | 4%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 19       | 76%     |
| 5.7     | 2        | 8%      |
| 5.6     | 2        | 8%      |
| 5.5     | 2        | 8%      |

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


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 18       | 72%     |
| KDE        | 5        | 20%     |
| KDE5       | 1        | 4%      |
| Unknown    | 1        | 4%      |

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
| Unknown | 15       | 60%     |
| SDDM    | 6        | 24%     |
| TDM     | 3        | 12%     |
| LightDM | 1        | 4%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| pt_BR | 6        | 24%     |
| en_US | 5        | 20%     |
| de_DE | 4        | 16%     |
| C     | 2        | 8%      |
| sv_SE | 1        | 4%      |
| sr_RS | 1        | 4%      |
| fr_FR | 1        | 4%      |
| fr_CA | 1        | 4%      |
| es_CL | 1        | 4%      |
| en_ZA | 1        | 4%      |
| en_IN | 1        | 4%      |
| cs_CZ | 1        | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 72%     |
| EFI  | 7        | 28%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 23       | 92%     |
| Xfs     | 1        | 4%      |
| Overlay | 1        | 4%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 84%     |
| MBR     | 2        | 8%      |
| GPT     | 2        | 8%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 76%     |
| Yes       | 6        | 24%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 56%     |
| Yes       | 11       | 44%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 5        | 20%     |
| ASUSTek Computer    | 4        | 16%     |
| ASRock              | 4        | 16%     |
| MSI                 | 3        | 12%     |
| Dell                | 3        | 12%     |
| Intel               | 2        | 8%      |
| PCWare              | 1        | 4%      |
| Hewlett-Packard     | 1        | 4%      |
| ECS                 | 1        | 4%      |
| Apple               | 1        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| PCWare IPMH61R2              | 1        | 4%      |
| MSI MS-7B84                  | 1        | 4%      |
| MSI MS-7913                  | 1        | 4%      |
| MSI MS-7309                  | 1        | 4%      |
| Intel DG31PR AAD97573-306    | 1        | 4%      |
| Intel B75                    | 1        | 4%      |
| HP 202 G2 MT                 | 1        | 4%      |
| Gigabyte X570 UD             | 1        | 4%      |
| Gigabyte GA-78LMT-S2P        | 1        | 4%      |
| Gigabyte G31M-ES2C           | 1        | 4%      |
| Gigabyte B450 AORUS M        | 1        | 4%      |
| Gigabyte 970A-DS3P           | 1        | 4%      |
| ECS A780GM-A                 | 1        | 4%      |
| Dell OptiPlex 360            | 1        | 4%      |
| Dell OptiPlex 3010           | 1        | 4%      |
| Dell Inspiron 3646           | 1        | 4%      |
| ASUS P8Z77-V PRO/THUNDERBOLT | 1        | 4%      |
| ASUS P8Z68-V LE              | 1        | 4%      |
| ASUS M5A78L-M/USB3           | 1        | 4%      |
| ASUS All Series              | 1        | 4%      |
| ASRock N68-GE3 UCC           | 1        | 4%      |
| ASRock ConRoe1333-D667       | 1        | 4%      |
| ASRock B450M Steel Legend    | 1        | 4%      |
| ASRock 970 Extreme4          | 1        | 4%      |
| Apple MacPro5,1              | 1        | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 2        | 8%      |
| PCWare IPMH61R2        | 1        | 4%      |
| MSI MS-7B84            | 1        | 4%      |
| MSI MS-7913            | 1        | 4%      |
| MSI MS-7309            | 1        | 4%      |
| Intel DG31PR           | 1        | 4%      |
| Intel B75              | 1        | 4%      |
| HP 202                 | 1        | 4%      |
| Gigabyte X570          | 1        | 4%      |
| Gigabyte GA-78LMT-S2P  | 1        | 4%      |
| Gigabyte G31M-ES2C     | 1        | 4%      |
| Gigabyte B450          | 1        | 4%      |
| Gigabyte 970A-DS3P     | 1        | 4%      |
| ECS A780GM-A           | 1        | 4%      |
| Dell Inspiron          | 1        | 4%      |
| ASUS P8Z77-V           | 1        | 4%      |
| ASUS P8Z68-V           | 1        | 4%      |
| ASUS M5A78L-M          | 1        | 4%      |
| ASUS All               | 1        | 4%      |
| ASRock N68-GE3         | 1        | 4%      |
| ASRock ConRoe1333-D667 | 1        | 4%      |
| ASRock B450M           | 1        | 4%      |
| ASRock 970             | 1        | 4%      |
| Apple MacPro5          | 1        | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 4        | 16%     |
| 2013 | 3        | 12%     |
| 2010 | 3        | 12%     |
| 2019 | 2        | 8%      |
| 2018 | 2        | 8%      |
| 2014 | 2        | 8%      |
| 2012 | 2        | 8%      |
| 2009 | 2        | 8%      |
| 2008 | 2        | 8%      |
| 2007 | 2        | 8%      |
| 2015 | 1        | 4%      |

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


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 10       | 40%     |
| 16.01-24.0 | 6        | 24%     |
| 8.01-16.0  | 4        | 16%     |
| 32.01-64.0 | 3        | 12%     |
| 1.01-2.0   | 2        | 8%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 9        | 36%     |
| 1.01-2.0  | 9        | 36%     |
| 3.01-4.0  | 5        | 20%     |
| 4.01-8.0  | 1        | 4%      |
| 8.01-16.0 | 1        | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 40%     |
| 2      | 7        | 28%     |
| 3      | 5        | 20%     |
| 7      | 2        | 8%      |
| 4      | 1        | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 53.85%  |
| Yes       | 12       | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 60%     |
| Yes       | 10       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 76%     |
| Yes       | 6        | 24%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Brazil       | 6        | 24%     |
| USA          | 5        | 20%     |
| Germany      | 4        | 16%     |
| South Africa | 2        | 8%      |
| Sweden       | 1        | 4%      |
| Serbia       | 1        | 4%      |
| India        | 1        | 4%      |
| France       | 1        | 4%      |
| Czechia      | 1        | 4%      |
| Croatia      | 1        | 4%      |
| Chile        | 1        | 4%      |
| Canada       | 1        | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Curitiba        | 2        | 8%      |
| Zagreb          | 1        | 4%      |
| Wiesbaden       | 1        | 4%      |
| Taboao da Serra | 1        | 4%      |
| Södertälje    | 1        | 4%      |
| Sidney          | 1        | 4%      |
| Schweinfurt     | 1        | 4%      |
| Santiago        | 1        | 4%      |
| Rio de Janeiro  | 1        | 4%      |
| Pretoria        | 1        | 4%      |
| Port Elizabeth  | 1        | 4%      |
| Paris           | 1        | 4%      |
| Ostrava         | 1        | 4%      |
| Moreno Valley   | 1        | 4%      |
| Montreal        | 1        | 4%      |
| Karlsruhe       | 1        | 4%      |
| Douglas         | 1        | 4%      |
| Coos Bay        | 1        | 4%      |
| Bochum          | 1        | 4%      |
| Bhopal          | 1        | 4%      |
| Belo Horizonte  | 1        | 4%      |
| Belgrade        | 1        | 4%      |
| Atascosa        | 1        | 4%      |
| Altamira        | 1        | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 15     | 26.09%  |
| Seagate             | 6        | 12     | 13.04%  |
| Samsung Electronics | 4        | 6      | 8.7%    |
| SanDisk             | 3        | 5      | 6.52%   |
| Hitachi             | 3        | 3      | 6.52%   |
| Toshiba             | 2        | 2      | 4.35%   |
| Maxtor              | 2        | 2      | 4.35%   |
| Kingston            | 2        | 3      | 4.35%   |
| XPG                 | 1        | 1      | 2.17%   |
| TO Exter            | 1        | 1      | 2.17%   |
| PNY                 | 1        | 1      | 2.17%   |
| Phison              | 1        | 1      | 2.17%   |
| Patriot             | 1        | 1      | 2.17%   |
| OCZ                 | 1        | 1      | 2.17%   |
| Mushkin             | 1        | 1      | 2.17%   |
| Hewlett-Packard     | 1        | 1      | 2.17%   |
| Crucial             | 1        | 1      | 2.17%   |
| China               | 1        | 1      | 2.17%   |
| ASMT109x            | 1        | 1      | 2.17%   |
| A-DATA Technology   | 1        | 2      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WD5000AAKX-001CA0 500GB        | 2        | 3.51%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 3.51%   |
| XPG GAMMIX S11 Pro 512GB           | 1        | 1.75%   |
| WDC WD60EZRX-00MVLB1 6TB           | 1        | 1.75%   |
| WDC WD5000AACS-00G8B1 500GB        | 1        | 1.75%   |
| WDC WD400JD-55MSA1 40GB            | 1        | 1.75%   |
| WDC WD4001FAEX-00MJRA0 4TB         | 1        | 1.75%   |
| WDC WD2500BEVS-22UST0 250GB        | 1        | 1.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1        | 1.75%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 1.75%   |
| WDC WD10EAVS-00D7B1 1TB            | 1        | 1.75%   |
| WDC WD10EARX-00N0YB0 1TB           | 1        | 1.75%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 1.75%   |
| Toshiba MQ01ACF050 500GB           | 1        | 1.75%   |
| Toshiba MQ01ABD050 500GB           | 1        | 1.75%   |
| TO Exter nal USB 3.0 180GB         | 1        | 1.75%   |
| Seagate ST8000AS0002-1NA17Z 8TB    | 1        | 1.75%   |
| Seagate ST500LX012-SSHD-8GB        | 1        | 1.75%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1.75%   |
| Seagate ST3200826AS 200GB          | 1        | 1.75%   |
| Seagate ST3160318AS 160GB          | 1        | 1.75%   |
| Seagate ST3160215A 160GB           | 1        | 1.75%   |
| Seagate ST31500341AS 1TB           | 1        | 1.75%   |
| Seagate ST250DM000-1BD141 250GB    | 1        | 1.75%   |
| Seagate ST2000DM001-1CH164 2TB     | 1        | 1.75%   |
| Seagate ST18000NM000J-2TV103 18TB  | 1        | 1.75%   |
| Seagate ST12000NM0007-2A1101 12TB  | 1        | 1.75%   |
| Seagate ST1000DM003-1CH162 1TB     | 1        | 1.75%   |
| SanDisk X400 2.5 7MM 256GB SSD     | 1        | 1.75%   |
| SanDisk Ultra II 480GB SSD         | 1        | 1.75%   |
| SanDisk SDSSDHII240G 240GB         | 1        | 1.75%   |
| SanDisk SD9SN8W256G1002 256GB SSD  | 1        | 1.75%   |
| Samsung SSD 860 EVO 1TB            | 1        | 1.75%   |
| Samsung SSD 840 PRO Series 256GB   | 1        | 1.75%   |
| Samsung HD501LJ 500GB              | 1        | 1.75%   |
| Samsung HD321KJ 320GB              | 1        | 1.75%   |
| Samsung HD161HJ 41R0186LEN 160GB   | 1        | 1.75%   |
| Samsung HD081GJ 80GB               | 1        | 1.75%   |
| PNY SSD2SC240G1SA754D117-443 240GB | 1        | 1.75%   |
| Phison NVMe SSD Drive 1TB          | 1        | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 15     | 41.38%  |
| Seagate             | 6        | 12     | 20.69%  |
| Samsung Electronics | 3        | 4      | 10.34%  |
| Hitachi             | 3        | 3      | 10.34%  |
| Toshiba             | 2        | 2      | 6.9%    |
| Maxtor              | 2        | 2      | 6.9%    |
| ASMT109x            | 1        | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 3        | 5      | 20%     |
| Kingston            | 2        | 3      | 13.33%  |
| TO Exter            | 1        | 1      | 6.67%   |
| Samsung Electronics | 1        | 2      | 6.67%   |
| PNY                 | 1        | 1      | 6.67%   |
| Patriot             | 1        | 1      | 6.67%   |
| OCZ                 | 1        | 1      | 6.67%   |
| Mushkin             | 1        | 1      | 6.67%   |
| Hewlett-Packard     | 1        | 1      | 6.67%   |
| Crucial             | 1        | 1      | 6.67%   |
| China               | 1        | 1      | 6.67%   |
| A-DATA Technology   | 1        | 2      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 39     | 58.33%  |
| SSD  | 13       | 20     | 36.11%  |
| NVMe | 2        | 2      | 5.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 25       | 57     | 86.21%  |
| SAS  | 2        | 2      | 6.9%    |
| NVMe | 2        | 2      | 6.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 25       | 40     | 65.79%  |
| 0.51-1.0   | 7        | 10     | 18.42%  |
| 3.01-4.0   | 2        | 2      | 5.26%   |
| 1.01-2.0   | 2        | 3      | 5.26%   |
| 10.01-20.0 | 1        | 2      | 2.63%   |
| 4.01-10.0  | 1        | 2      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 8        | 32%     |
| 251-500    | 6        | 24%     |
| 1001-2000  | 3        | 12%     |
| 51-100     | 3        | 12%     |
| 21-50      | 2        | 8%      |
| 2001-3000  | 1        | 4%      |
| 1-20       | 1        | 4%      |
| 501-1000   | 1        | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 10       | 38.46%  |
| 101-250  | 5        | 19.23%  |
| 21-50    | 4        | 15.38%  |
| 51-100   | 3        | 11.54%  |
| 251-500  | 2        | 7.69%   |
| 501-1000 | 2        | 7.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD4001FAEX-00MJRA0 4TB                   | 1        | 1      | 33.33%  |
| Samsung Electronics SSD 840 PRO Series 256GB | 1        | 1      | 33.33%  |
| Samsung Electronics HD081GJ 80GB             | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 66.67%  |
| WDC                 | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Detected | 23       | 44     | 79.31%  |
| Works    | 4        | 14     | 13.79%  |
| Malfunc  | 2        | 3      | 6.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 13       | 43.33%  |
| AMD                | 10       | 33.33%  |
| ASMedia Technology | 3        | 10%     |
| Nvidia             | 2        | 6.67%   |
| Phison Electronics | 1        | 3.33%   |
| ADATA Technology   | 1        | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 11.11%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 11.11%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 8.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 6.67%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 6.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 6.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 6.67%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 4.44%   |
| Nvidia MCP61 IDE                                                                        | 2        | 4.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 4.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 4.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 4.44%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 2.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 2.22%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.22%   |
| ASMedia 106x SATA/RAID Controller                                                       | 1        | 2.22%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 56.25%  |
| IDE  | 12       | 37.5%   |
| NVMe | 2        | 6.25%   |

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


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 4%      |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 4%      |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1        | 4%      |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 4%      |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 4%      |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 4%      |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 4%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 4%      |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 4%      |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 4%      |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 1        | 4%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 4%      |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 4%      |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 4%      |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 4%      |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 4%      |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 4%      |
| AMD Phenom 9650 Quad-Core Processor         | 1        | 4%      |
| AMD FX-8320 Eight-Core Processor            | 1        | 4%      |
| AMD FX-6300 Six-Core Processor              | 1        | 4%      |
| AMD FX-6100 Six-Core Processor              | 1        | 4%      |
| AMD Athlon II X4 640 Processor              | 1        | 4%      |
| AMD Athlon II X2 260 Processor              | 1        | 4%      |
| AMD Athlon 64 X2 Dual Core Processor 4400+  | 1        | 4%      |
| AMD A8-6600K APU with Radeon HD Graphics    | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i7      | 3        | 12%     |
| AMD FX             | 3        | 12%     |
| Intel Pentium      | 2        | 8%      |
| Intel Core i3      | 2        | 8%      |
| Intel Core 2 Duo   | 2        | 8%      |
| Intel Xeon         | 1        | 4%      |
| Intel Pentium Dual | 1        | 4%      |
| Intel Core i5      | 1        | 4%      |
| Intel Core 2 Quad  | 1        | 4%      |
| AMD Ryzen 9        | 1        | 4%      |
| AMD Ryzen 7        | 1        | 4%      |
| AMD Ryzen 5        | 1        | 4%      |
| AMD Ryzen 3        | 1        | 4%      |
| AMD Phenom         | 1        | 4%      |
| AMD Athlon II X4   | 1        | 4%      |
| AMD Athlon II X2   | 1        | 4%      |
| AMD Athlon 64 X2   | 1        | 4%      |
| AMD A8             | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 10       | 40%     |
| 2      | 9        | 36%     |
| 12     | 2        | 8%      |
| 3      | 2        | 8%      |
| 8      | 1        | 4%      |
| 6      | 1        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 96%     |
| 2      | 1        | 4%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 52%     |
| 1      | 12       | 48%     |

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
| Unknown    | 7        | 28%     |
| 0x306a9    | 3        | 12%     |
| 0x6fd      | 2        | 8%      |
| 0x306c3    | 2        | 8%      |
| 0x206a7    | 2        | 8%      |
| 0x010000c8 | 2        | 8%      |
| 0x30678    | 1        | 4%      |
| 0x206c2    | 1        | 4%      |
| 0x08701013 | 1        | 4%      |
| 0x08108109 | 1        | 4%      |
| 0x06000852 | 1        | 4%      |
| 0x0600063e | 1        | 4%      |
| 0x01000095 | 1        | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 3        | 12%     |
| Piledriver  | 3        | 12%     |
| K10         | 3        | 12%     |
| IvyBridge   | 3        | 12%     |
| SandyBridge | 2        | 8%      |
| Penryn      | 2        | 8%      |
| Haswell     | 2        | 8%      |
| Core        | 2        | 8%      |
| Zen+        | 1        | 4%      |
| Westmere    | 1        | 4%      |
| Silvermont  | 1        | 4%      |
| K8 Hammer   | 1        | 4%      |
| Bulldozer   | 1        | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 10       | 38.46%  |
| Nvidia | 9        | 34.62%  |
| Intel  | 7        | 26.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 7.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 7.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 7.69%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 7.69%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 3.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.85%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 3.85%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                       | 1        | 3.85%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 3.85%   |
| Nvidia GF110 [GeForce GTX 570]                                              | 1        | 3.85%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 3.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.85%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 3.85%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                          | 1        | 3.85%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 3.85%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 3.85%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 3.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 3.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 3.85%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x AMD    | 10       | 40%     |
| 1 x Nvidia | 9        | 36%     |
| 1 x Intel  | 6        | 24%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 76.92%  |
| Unknown     | 4        | 15.38%  |
| Proprietary | 2        | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 46.15%  |
| 0.01-0.5   | 4        | 15.38%  |
| 1.01-2.0   | 3        | 11.54%  |
| 0.51-1.0   | 3        | 11.54%  |
| 3.01-4.0   | 2        | 7.69%   |
| 5.01-6.0   | 1        | 3.85%   |
| 2.01-3.0   | 1        | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 21.74%  |
| Goldstar            | 5        | 21.74%  |
| Acer                | 4        | 17.39%  |
| Philips             | 2        | 8.7%    |
| ViewSonic           | 1        | 4.35%   |
| Sceptre Tech        | 1        | 4.35%   |
| Panasonic           | 1        | 4.35%   |
| Iiyama              | 1        | 4.35%   |
| Hewlett-Packard     | 1        | 4.35%   |
| BenQ                | 1        | 4.35%   |
| AOC                 | 1        | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                    | 2        | 8%      |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 1        | 4%      |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                 | 1        | 4%      |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1        | 4%      |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch   | 1        | 4%      |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch     | 1        | 4%      |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch     | 1        | 4%      |
| Samsung Electronics S/T 77/76DFX STN0006 1280x1024 312x234mm 15.4-inch | 1        | 4%      |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                     | 1        | 4%      |
| Philips 170B PHL081D 1280x1024 338x270mm 17.0-inch                     | 1        | 4%      |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 1        | 4%      |
| Iiyama PLX2481H IVM611D 1920x1080 520x290mm 23.4-inch                  | 1        | 4%      |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch           | 1        | 4%      |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch                   | 1        | 4%      |
| Goldstar W1953 GSM4BA6 1360x768 406x229mm 18.4-inch                    | 1        | 4%      |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                   | 1        | 4%      |
| BenQ LCD Monitor GL951A 2880x900                                       | 1        | 4%      |
| BenQ LCD Monitor GL951A                                                | 1        | 4%      |
| BenQ GL951A BNQ7897 1440x900 408x255mm 18.9-inch                       | 1        | 4%      |
| AOC 2790WG5 AOC2790 1920x1080 600x340mm 27.2-inch                      | 1        | 4%      |
| Acer V226WL ACR0339 1680x1050 474x296mm 22.0-inch                      | 1        | 4%      |
| Acer P225HQ ACR00EA 1920x1080 477x268mm 21.5-inch                      | 1        | 4%      |
| Acer G226HQL ACR02EA 1920x1080 477x268mm 21.5-inch                     | 1        | 4%      |
| Acer G185HV ACR019F 1366x768 410x230mm 18.5-inch                       | 1        | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 8        | 33.33%  |
| 1600x900 (HD+)     | 3        | 12.5%   |
| 1366x768 (WXGA)    | 3        | 12.5%   |
| 3840x2160 (4K)     | 2        | 8.33%   |
| 1280x1024 (SXGA)   | 2        | 8.33%   |
| 2880x900           | 1        | 4.17%   |
| 2560x1440 (QHD)    | 1        | 4.17%   |
| 1680x1050 (WSXGA+) | 1        | 4.17%   |
| 1440x900 (WXGA+)   | 1        | 4.17%   |
| 1360x768           | 1        | 4.17%   |
| Unknown            | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 4        | 16.67%  |
| 23      | 3        | 12.5%   |
| 21      | 3        | 12.5%   |
| 31      | 2        | 8.33%   |
| 27      | 2        | 8.33%   |
| 20      | 2        | 8.33%   |
| 19      | 2        | 8.33%   |
| 84      | 1        | 4.17%   |
| 24      | 1        | 4.17%   |
| 22      | 1        | 4.17%   |
| 17      | 1        | 4.17%   |
| 15      | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 12       | 50%     |
| 501-600     | 5        | 20.83%  |
| 601-700     | 3        | 12.5%   |
| 301-350     | 2        | 8.33%   |
| 1501-2000   | 1        | 4.17%   |
| Unknown     | 1        | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 78.26%  |
| 16/10   | 2        | 8.7%    |
| 5/4     | 1        | 4.35%   |
| 4/3     | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 33.33%  |
| 141-150        | 5        | 20.83%  |
| 151-200        | 4        | 16.67%  |
| 351-500        | 2        | 8.33%   |
| 301-350        | 2        | 8.33%   |
| More than 1000 | 1        | 4.17%   |
| 111-120        | 1        | 4.17%   |
| Unknown        | 1        | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 70.83%  |
| 101-120 | 5        | 20.83%  |
| 121-160 | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 84%     |
| 2     | 2        | 8%      |
| 0     | 2        | 8%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 57.14%  |
| Qualcomm Atheros      | 4        | 11.43%  |
| Intel                 | 3        | 8.57%   |
| TP-Link               | 2        | 5.71%   |
| Nvidia                | 2        | 5.71%   |
| Qualcomm              | 1        | 2.86%   |
| CyberTAN Technology   | 1        | 2.86%   |
| Broadcom              | 1        | 2.86%   |
| AVM                   | 1        | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 17       | 42.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 2        | 5%      |
| Realtek 802.11ac NIC                                                                  | 2        | 5%      |
| Nvidia MCP61 Ethernet                                                                 | 2        | 5%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 1        | 2.5%    |
| TP-Link Archer T4U ver.3                                                              | 1        | 2.5%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1        | 2.5%    |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                                  | 1        | 2.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 2.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 2.5%    |
| Qualcomm Redmi 5 Plus                                                                 | 1        | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1        | 2.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1        | 2.5%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 2.5%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                            | 1        | 2.5%    |
| Intel Wireless 7260                                                                   | 1        | 2.5%    |
| Intel 82579V Gigabit Network Connection                                               | 1        | 2.5%    |
| Intel 82574L Gigabit Network Connection                                               | 1        | 2.5%    |
| CyberTAN Siemens S30853-S1031-R351 802.11g Wireless Adapter [Atheros AR5523]          | 1        | 2.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                       | 1        | 2.5%    |
| AVM FRITZ WLAN N v2 [RT5572/rt2870.bin]                                               | 1        | 2.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 38.46%  |
| Qualcomm Atheros      | 3        | 23.08%  |
| TP-Link               | 2        | 15.38%  |
| Intel                 | 1        | 7.69%   |
| CyberTAN Technology   | 1        | 7.69%   |
| AVM                   | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek 802.11ac NIC                                                                  | 2        | 14.29%  |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 1        | 7.14%   |
| TP-Link Archer T4U ver.3                                                              | 1        | 7.14%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1        | 7.14%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                                  | 1        | 7.14%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 7.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 7.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1        | 7.14%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 7.14%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                            | 1        | 7.14%   |
| Intel Wireless 7260                                                                   | 1        | 7.14%   |
| CyberTAN Siemens S30853-S1031-R351 802.11g Wireless Adapter [Atheros AR5523]          | 1        | 7.14%   |
| AVM FRITZ WLAN N v2 [RT5572/rt2870.bin]                                               | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 73.08%  |
| Nvidia                | 2        | 7.69%   |
| Intel                 | 2        | 7.69%   |
| Qualcomm Atheros      | 1        | 3.85%   |
| Qualcomm              | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17       | 65.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 7.69%   |
| Nvidia MCP61 Ethernet                                             | 2        | 7.69%   |
| Qualcomm Redmi 5 Plus                                             | 1        | 3.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 3.85%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 3.85%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 3.85%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 69.44%  |
| WiFi     | 11       | 30.56%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 77.78%  |
| WiFi     | 6        | 22.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 76%     |
| 2     | 5        | 20%     |
| 3     | 1        | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 2        | 33.33%  |
| Cambridge Silicon Radio         | 2        | 33.33%  |
| Integrated System Solution      | 1        | 16.67%  |
| Apple                           | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 33.33%  |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 16.67%  |
| Qualcomm Atheros AR3011 Bluetooth                     | 1        | 16.67%  |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 16.67%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 14       | 31.82%  |
| Intel               | 13       | 29.55%  |
| Nvidia              | 10       | 22.73%  |
| C-Media Electronics | 3        | 6.82%   |
| Texas Instruments   | 1        | 2.27%   |
| Logitech            | 1        | 2.27%   |
| Creative Labs       | 1        | 2.27%   |
| Corsair             | 1        | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 9.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 7.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 5.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 5.88%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 3.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 3.92%   |
| Nvidia GF110 High Definition Audio Controller                              | 2        | 3.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 3.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 3.92%   |
| C-Media Electronics Audio Adapter                                          | 2        | 3.92%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 3.92%   |
| Texas Instruments PCM2900 Audio Codec                                      | 1        | 1.96%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.96%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.96%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 1.96%   |
| Logitech Logitech USB Microphone                                           | 1        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 1.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.96%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 1.96%   |
| Corsair Corsair VOID PRO Surround USB Adapter                              | 1        | 1.96%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 1.96%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 1.96%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 1.96%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1        | 1.96%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1        | 1.96%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.96%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.96%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.96%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 3        | 33.33%  |
| G.Skill             | 2        | 22.22%  |
| Unknown             | 1        | 11.11%  |
| Samsung Electronics | 1        | 11.11%  |
| Kingston            | 1        | 11.11%  |
| Elpida              | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 1        | 10%     |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 1        | 10%     |
| Samsung RAM Module 8192MB DIMM DDR3 1333MT/s           | 1        | 10%     |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s   | 1        | 10%     |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s    | 1        | 10%     |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s     | 1        | 10%     |
| Elpida RAM Module 8192MB DIMM DDR3 1333MT/s            | 1        | 10%     |
| Corsair RAM CMY8GX3M2C1600C9 4096MB DIMM DDR3 1600MT/s | 1        | 10%     |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s  | 1        | 10%     |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s  | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 4        | 57.14%  |
| DDR4    | 2        | 28.57%  |
| Unknown | 1        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 7        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 5        | 62.5%   |
| 4096 | 1        | 12.5%   |
| 2048 | 1        | 12.5%   |
| 1024 | 1        | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 2        | 22.22%  |
| 1600  | 2        | 22.22%  |
| 3466  | 1        | 11.11%  |
| 3266  | 1        | 11.11%  |
| 1333  | 1        | 11.11%  |
| 800   | 1        | 11.11%  |
| 667   | 1        | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP LaserJet 3052       | 1        | 50%     |
| Brother HL-2130 series | 1        | 50%     |

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


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 33.33%  |
| Microdia  | 1        | 33.33%  |
| Logitech  | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Microsoft LifeCam HD-3000  | 1        | 33.33%  |
| Microdia Webcam Vitade AF  | 1        | 33.33%  |
| Logitech QuickCam Pro 9000 | 1        | 33.33%  |

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
| 0     | 18       | 69.23%  |
| 1     | 8        | 30.77%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 5        | 55.56%  |
| Graphics card | 4        | 44.44%  |

