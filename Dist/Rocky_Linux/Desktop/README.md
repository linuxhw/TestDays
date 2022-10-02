Rocky Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

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

Total: 32

| Vendor   | Model              | Probe                                                      | Date         |
|----------|--------------------|------------------------------------------------------------|--------------|
| ASUSTek  | PRIME B550M-K      | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| ASUSTek  | P8B WS             | [bd82f7708c](https://linux-hardware.org/?probe=bd82f7708c) | Sep 02, 2022 |
| Lenovo   | 1046 NO DPK        | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| ASUSTek  | PRIME B460M-A R2.0 | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| ASUSTek  | PRIME B365-PLUS    | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| Gigabyte | 970A-UD3P          | [0d503b2789](https://linux-hardware.org/?probe=0d503b2789) | Jul 27, 2022 |
| Unknown  | X31_ICH7           | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell     | 0GWHMW A01         | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell     | 06CV2N A00         | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte | G41MT-USB3         | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte | G41MT-USB3         | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR      | Pocono BIOS.5.1    | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| Dell     | 0NK70N A03         | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Dell     | 0WN7Y6 A01         | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell     | 0PC5F7 A02         | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek  | PRIME B450-PLUS    | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| ASRock   | B450M Pro4         | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI      | Z97A GAMING 6      | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| AZW      | Gemini M           | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW      | Gemini M           | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google   | Panther            | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Gigabyte | X570 AORUS ULTRA   | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte | H87-D3H-CF         | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Dell     | 0N4YC8 A00         | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| ASUSTek  | PRIME B450M-A II   | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek  | PRIME B450M-A II   | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek  | P5Q DELUXE         | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo   | NOK                | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Dell     | 0M5DCD A00         | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| ASUSTek  | PRIME TRX40-PRO S  | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell     | 0M5DCD A00         | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| HP       | 0B54h D            | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Rocky Linux 8.5 | 12       | 42.86%  |
| Rocky Linux 8.4 | 9        | 32.14%  |
| Rocky Linux 8.6 | 4        | 14.29%  |
| Rocky Linux 9.0 | 2        | 7.14%   |
| Rocky Linux 8.3 | 1        | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 28       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64     | 6        | 21.43%  |
| 4.18.0-348.7.1.el8_5.x86_64      | 3        | 10.71%  |
| 4.18.0-305.10.2.el8_4.x86_64     | 3        | 10.71%  |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2        | 7.14%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2        | 7.14%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2        | 7.14%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2        | 7.14%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1        | 3.57%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 1        | 3.57%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1        | 3.57%   |
| 4.18.0-372.9.1.el8.x86_64        | 1        | 3.57%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 1        | 3.57%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1        | 3.57%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 1        | 3.57%   |
| 4.18.0-240.22.1.el8.x86_64       | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 25       | 89.29%  |
| 5.14.0  | 2        | 7.14%   |
| 5.14.1  | 1        | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 25       | 89.29%  |
| 5.14    | 3        | 10.71%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 28       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 17       | 60.71%  |
| Unknown       | 5        | 17.86%  |
| KDE5          | 3        | 10.71%  |
| GNOME Classic | 2        | 7.14%   |
| MATE          | 1        | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 13       | 46.43%  |
| Wayland | 12       | 42.86%  |
| Unknown | 3        | 10.71%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 13       | 46.43%  |
| Unknown | 13       | 46.43%  |
| SDDM    | 2        | 7.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 17       | 60.71%  |
| en_IL | 3        | 10.71%  |
| ru_RU | 2        | 7.14%   |
| en_SG | 2        | 7.14%   |
| pl_PL | 1        | 3.57%   |
| ja_JP | 1        | 3.57%   |
| es_CO | 1        | 3.57%   |
| af_ZA | 1        | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 17       | 60.71%  |
| EFI  | 11       | 39.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 23       | 82.14%  |
| Ext4 | 5        | 17.86%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 12       | 42.86%  |
| Unknown | 9        | 32.14%  |
| MBR     | 7        | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 82.14%  |
| Yes       | 5        | 17.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 92.86%  |
| Yes       | 2        | 7.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 28.57%  |
| Dell                | 7        | 25%     |
| Gigabyte Technology | 4        | 14.29%  |
| Lenovo              | 2        | 7.14%   |
| NCR                 | 1        | 3.57%   |
| MSI                 | 1        | 3.57%   |
| Hewlett-Packard     | 1        | 3.57%   |
| Google              | 1        | 3.57%   |
| AZW                 | 1        | 3.57%   |
| ASRock              | 1        | 3.57%   |
| Unknown             | 1        | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 9020                  | 2        | 7.14%   |
| NCR xxxx-xxxx-xxxx                  | 1        | 3.57%   |
| MSI MS-7917                         | 1        | 3.57%   |
| Lenovo ThinkStation P620 30E0S0PR00 | 1        | 3.57%   |
| Lenovo ThinkCentre M72e 36601Y8     | 1        | 3.57%   |
| HP Z600 Workstation                 | 1        | 3.57%   |
| Google Panther                      | 1        | 3.57%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 3.57%   |
| Gigabyte H87-D3H                    | 1        | 3.57%   |
| Gigabyte G41MT-USB3                 | 1        | 3.57%   |
| Gigabyte 970A-UD3P                  | 1        | 3.57%   |
| Dell Vostro 3681                    | 1        | 3.57%   |
| Dell Precision Tower 7810           | 1        | 3.57%   |
| Dell Precision T7610                | 1        | 3.57%   |
| Dell Precision T5610                | 1        | 3.57%   |
| Dell OptiPlex 390                   | 1        | 3.57%   |
| AZW Gemini M                        | 1        | 3.57%   |
| ASUS PRIME TRX40-PRO S              | 1        | 3.57%   |
| ASUS PRIME B550M-K                  | 1        | 3.57%   |
| ASUS PRIME B460M-A R2.0             | 1        | 3.57%   |
| ASUS PRIME B450M-A II               | 1        | 3.57%   |
| ASUS PRIME B450-PLUS                | 1        | 3.57%   |
| ASUS PRIME B365-PLUS                | 1        | 3.57%   |
| ASUS P8B WS                         | 1        | 3.57%   |
| ASUS P5Q DELUXE                     | 1        | 3.57%   |
| ASRock B450M Pro4                   | 1        | 3.57%   |
| Unknown                             | 1        | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 6        | 21.43%  |
| Dell Precision      | 3        | 10.71%  |
| Dell OptiPlex       | 3        | 10.71%  |
| NCR xxxx-xxxx-xxxx  | 1        | 3.57%   |
| MSI MS-7917         | 1        | 3.57%   |
| Lenovo ThinkStation | 1        | 3.57%   |
| Lenovo ThinkCentre  | 1        | 3.57%   |
| HP Z600             | 1        | 3.57%   |
| Google Panther      | 1        | 3.57%   |
| Gigabyte X570       | 1        | 3.57%   |
| Gigabyte H87-D3H    | 1        | 3.57%   |
| Gigabyte G41MT-USB3 | 1        | 3.57%   |
| Gigabyte 970A-UD3P  | 1        | 3.57%   |
| Dell Vostro         | 1        | 3.57%   |
| AZW Gemini          | 1        | 3.57%   |
| ASUS P8B            | 1        | 3.57%   |
| ASUS P5Q            | 1        | 3.57%   |
| ASRock B450M        | 1        | 3.57%   |
| Unknown             | 1        | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 5        | 17.86%  |
| 2013 | 4        | 14.29%  |
| 2015 | 3        | 10.71%  |
| 2014 | 3        | 10.71%  |
| 2011 | 3        | 10.71%  |
| 2021 | 2        | 7.14%   |
| 2019 | 2        | 7.14%   |
| 2018 | 2        | 7.14%   |
| 2008 | 2        | 7.14%   |
| 2012 | 1        | 3.57%   |
| 2010 | 1        | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 28       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 28       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 96.43%  |
| Yes  | 1        | 3.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 8        | 28.57%  |
| 4.01-8.0    | 5        | 17.86%  |
| 16.01-24.0  | 5        | 17.86%  |
| 64.01-256.0 | 3        | 10.71%  |
| 3.01-4.0    | 2        | 7.14%   |
| 1.01-2.0    | 2        | 7.14%   |
| 8.01-16.0   | 2        | 7.14%   |
| 2.01-3.0    | 1        | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 7        | 25%     |
| 3.01-4.0  | 6        | 21.43%  |
| 4.01-8.0  | 5        | 17.86%  |
| 1.01-2.0  | 5        | 17.86%  |
| 8.01-16.0 | 2        | 7.14%   |
| 0.51-1.0  | 2        | 7.14%   |
| 0.01-0.5  | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 42.86%  |
| 2      | 8        | 28.57%  |
| 3      | 5        | 17.86%  |
| 4      | 2        | 7.14%   |
| 8      | 1        | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 53.57%  |
| No        | 13       | 46.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 60.71%  |
| Yes       | 11       | 39.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 75%     |
| Yes       | 7        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 6        | 21.43%  |
| Singapore    | 3        | 10.71%  |
| Israel       | 3        | 10.71%  |
| Russia       | 2        | 7.14%   |
| Germany      | 2        | 7.14%   |
| South Korea  | 1        | 3.57%   |
| South Africa | 1        | 3.57%   |
| Portugal     | 1        | 3.57%   |
| Poland       | 1        | 3.57%   |
| Norway       | 1        | 3.57%   |
| Mexico       | 1        | 3.57%   |
| Japan        | 1        | 3.57%   |
| India        | 1        | 3.57%   |
| France       | 1        | 3.57%   |
| Czechia      | 1        | 3.57%   |
| Colombia     | 1        | 3.57%   |
| Australia    | 1        | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Singapore              | 3        | 10.71%  |
| Haifa                  | 2        | 7.14%   |
| Waltham                | 1        | 3.57%   |
| Tlaxcala City          | 1        | 3.57%   |
| St Petersburg          | 1        | 3.57%   |
| Sobral de Monte Agraco | 1        | 3.57%   |
| Rehovot                | 1        | 3.57%   |
| Prague                 | 1        | 3.57%   |
| Paris                  | 1        | 3.57%   |
| Ōtsu                  | 1        | 3.57%   |
| Oslo                   | 1        | 3.57%   |
| Moscow                 | 1        | 3.57%   |
| Mequon                 | 1        | 3.57%   |
| Melbourne              | 1        | 3.57%   |
| Lebanon                | 1        | 3.57%   |
| Krakow                 | 1        | 3.57%   |
| Imphal                 | 1        | 3.57%   |
| Giessen                | 1        | 3.57%   |
| Fredericksburg         | 1        | 3.57%   |
| Corvallis              | 1        | 3.57%   |
| Centurion              | 1        | 3.57%   |
| Burlington             | 1        | 3.57%   |
| Bucaramanga            | 1        | 3.57%   |
| Berlin                 | 1        | 3.57%   |
| Ansan-si               | 1        | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 14     | 18.6%   |
| WDC                 | 7        | 12     | 16.28%  |
| Samsung Electronics | 6        | 9      | 13.95%  |
| Toshiba             | 5        | 5      | 11.63%  |
| Hitachi             | 3        | 4      | 6.98%   |
| SanDisk             | 2        | 2      | 4.65%   |
| Crucial             | 2        | 2      | 4.65%   |
| SK hynix            | 1        | 1      | 2.33%   |
| PNY                 | 1        | 1      | 2.33%   |
| Phison              | 1        | 1      | 2.33%   |
| Intel               | 1        | 1      | 2.33%   |
| HGST                | 1        | 1      | 2.33%   |
| Gigabyte Technology | 1        | 1      | 2.33%   |
| Corsair             | 1        | 1      | 2.33%   |
| China               | 1        | 1      | 2.33%   |
| Apacer              | 1        | 1      | 2.33%   |
| A-DATA Technology   | 1        | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 2        | 4.26%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 2.13%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 2.13%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1        | 2.13%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 2.13%   |
| WDC WD5000AAKX-001CA0 500GB      | 1        | 2.13%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1        | 2.13%   |
| WDC WD2500AAJS-22VTA0 250GB      | 1        | 2.13%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 2.13%   |
| WDC WD1001FALS-00J7B0 1TB        | 1        | 2.13%   |
| Toshiba THNSNJ128GCSU 128GB SSD  | 1        | 2.13%   |
| Toshiba MG07ACA12TE 12TB         | 1        | 2.13%   |
| Toshiba MG04ACA400E 4TB          | 1        | 2.13%   |
| Toshiba DT01ACA100 1TB           | 1        | 2.13%   |
| Toshiba DT01ACA050 500GB         | 1        | 2.13%   |
| SK hynix SH920 2.5 7MM 256GB SSD | 1        | 2.13%   |
| Seagate ST9320325AS 320GB        | 1        | 2.13%   |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 2.13%   |
| Seagate ST3160318AS 160GB        | 1        | 2.13%   |
| Seagate ST2000DM008-2FR102 2TB   | 1        | 2.13%   |
| Seagate ST1000VX005-2EZ102 1TB   | 1        | 2.13%   |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 2.13%   |
| SanDisk SSD U110 16GB            | 1        | 2.13%   |
| SanDisk SDSSDH3500G 500GB        | 1        | 2.13%   |
| Samsung SSD 980 PRO 1TB          | 1        | 2.13%   |
| Samsung SSD 860 EVO 1TB          | 1        | 2.13%   |
| Samsung SP2004C 200GB            | 1        | 2.13%   |
| Samsung NVMe SSD Drive 500GB     | 1        | 2.13%   |
| Samsung MZVL21T0HCLR-00BL7 1TB   | 1        | 2.13%   |
| Samsung HD501LJ 500GB            | 1        | 2.13%   |
| Samsung HD103SJ 1TB              | 1        | 2.13%   |
| PNY CS900 120GB SSD              | 1        | 2.13%   |
| Phison Sabrent 256GB             | 1        | 2.13%   |
| Intel SSDPEDMW012T4 1TB          | 1        | 2.13%   |
| Hitachi HTS727575A9E364 752GB    | 1        | 2.13%   |
| Hitachi HDS723020BLA642 2TB      | 1        | 2.13%   |
| Hitachi HDS721010CLA632 1TB      | 1        | 2.13%   |
| Hitachi HDP725050GLA360 500GB    | 1        | 2.13%   |
| HGST HTS721010A9E630 1TB         | 1        | 2.13%   |
| Gigabyte GP-GSTFS31240GNTD 240GB | 1        | 2.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 14     | 33.33%  |
| WDC                 | 6        | 10     | 25%     |
| Toshiba             | 4        | 4      | 16.67%  |
| Hitachi             | 3        | 4      | 12.5%   |
| Samsung Electronics | 2        | 3      | 8.33%   |
| HGST                | 1        | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 15.38%  |
| SanDisk             | 2        | 2      | 15.38%  |
| Toshiba             | 1        | 1      | 7.69%   |
| SK hynix            | 1        | 1      | 7.69%   |
| Samsung Electronics | 1        | 1      | 7.69%   |
| PNY                 | 1        | 1      | 7.69%   |
| Gigabyte Technology | 1        | 1      | 7.69%   |
| Crucial             | 1        | 1      | 7.69%   |
| Corsair             | 1        | 1      | 7.69%   |
| China               | 1        | 1      | 7.69%   |
| Apacer              | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 36     | 47.37%  |
| SSD  | 13       | 13     | 34.21%  |
| NVMe | 7        | 9      | 18.42%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 49     | 77.42%  |
| NVMe | 7        | 9      | 22.58%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 16       | 25     | 53.33%  |
| 0.51-1.0   | 7        | 12     | 23.33%  |
| 1.01-2.0   | 3        | 3      | 10%     |
| 3.01-4.0   | 2        | 7      | 6.67%   |
| 2.01-3.0   | 1        | 1      | 3.33%   |
| 10.01-20.0 | 1        | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 25%     |
| 501-1000       | 7        | 25%     |
| 1001-2000      | 6        | 21.43%  |
| More than 3000 | 3        | 10.71%  |
| 251-500        | 3        | 10.71%  |
| 2001-3000      | 1        | 3.57%   |
| 1-20           | 1        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 8        | 28.57%  |
| 21-50          | 6        | 21.43%  |
| 51-100         | 4        | 14.29%  |
| 251-500        | 3        | 10.71%  |
| 501-1000       | 3        | 10.71%  |
| More than 3000 | 2        | 7.14%   |
| 101-250        | 1        | 3.57%   |
| 1001-2000      | 1        | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB     | 1        | 4      | 20%     |
| Seagate ST9320325AS 320GB     | 1        | 1      | 20%     |
| Hitachi HTS727575A9E364 752GB | 1        | 1      | 20%     |
| Hitachi HDS721010CLA632 1TB   | 1        | 1      | 20%     |
| Corsair Neutron SSD 64GB      | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 2        | 2      | 40%     |
| WDC     | 1        | 4      | 20%     |
| Seagate | 1        | 1      | 20%     |
| Corsair | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 2        | 2      | 50%     |
| WDC     | 1        | 4      | 25%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 7      | 80%     |
| SSD  | 1        | 1      | 20%     |

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
| Works    | 18       | 33     | 56.25%  |
| Detected | 9        | 17     | 28.13%  |
| Malfunc  | 5        | 8      | 15.63%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 20       | 52.63%  |
| AMD                       | 8        | 21.05%  |
| Samsung Electronics       | 2        | 5.26%   |
| Broadcom / LSI            | 2        | 5.26%   |
| Realtek Semiconductor     | 1        | 2.63%   |
| Phison Electronics        | 1        | 2.63%   |
| Micron/Crucial Technology | 1        | 2.63%   |
| Marvell Technology Group  | 1        | 2.63%   |
| ASMedia Technology        | 1        | 2.63%   |
| Adaptec                   | 1        | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 10.2%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 6.12%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 6.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 4.08%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 4.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 2.04%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 2.04%   |
| Phison E12 NVMe Controller                                                              | 1        | 2.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 2.04%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 2.04%   |
| Intel PCIe Data Center SSD                                                              | 1        | 2.04%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 2.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 2.04%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 2.04%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1        | 2.04%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 2.04%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 2.04%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 2.04%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 2.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 2.04%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 2.04%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 2.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.04%   |
| AMD RAID Bottom Device                                                                  | 1        | 2.04%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 2.04%   |
| Adaptec ASC-39320A U320                                                                 | 1        | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 45%     |
| NVMe | 7        | 17.5%   |
| IDE  | 7        | 17.5%   |
| RAID | 5        | 12.5%   |
| SAS  | 2        | 5%      |
| SCSI | 1        | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 71.43%  |
| AMD    | 8        | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 7.14%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 3.57%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1        | 3.57%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 3.57%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1        | 3.57%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 3.57%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 3.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 3.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 3.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 3.57%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 3.57%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 3.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 3.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 3.57%   |
| Intel Core i5-10600KF CPU @ 4.10GHz            | 1        | 3.57%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 3.57%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1        | 3.57%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 3.57%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1        | 3.57%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores     | 1        | 3.57%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 3.57%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 3.57%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics     | 1        | 3.57%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 3.57%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 3.57%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 3.57%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 6        | 21.43%  |
| Intel Xeon              | 4        | 14.29%  |
| Intel Core i5           | 4        | 14.29%  |
| Intel Celeron           | 2        | 7.14%   |
| AMD Ryzen Threadripper  | 2        | 7.14%   |
| Intel Pentium Dual-Core | 1        | 3.57%   |
| Intel Pentium Dual      | 1        | 3.57%   |
| Intel Core i3           | 1        | 3.57%   |
| Intel Core 2 Quad       | 1        | 3.57%   |
| AMD Ryzen 9             | 1        | 3.57%   |
| AMD Ryzen 7 PRO         | 1        | 3.57%   |
| AMD Ryzen 7             | 1        | 3.57%   |
| AMD Ryzen 5             | 1        | 3.57%   |
| AMD Ryzen 3             | 1        | 3.57%   |
| AMD FX                  | 1        | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 10       | 35.71%  |
| 8      | 6        | 21.43%  |
| 2      | 4        | 14.29%  |
| 6      | 3        | 10.71%  |
| 12     | 2        | 7.14%   |
| 24     | 1        | 3.57%   |
| 16     | 1        | 3.57%   |
| 3      | 1        | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 92.86%  |
| 2      | 2        | 7.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 18       | 64.29%  |
| 1      | 10       | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 28       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 3        | 10.71%  |
| 0xa0655    | 2        | 7.14%   |
| 0x306e4    | 2        | 7.14%   |
| 0x306a9    | 2        | 7.14%   |
| 0x206a7    | 2        | 7.14%   |
| 0x906ed    | 1        | 3.57%   |
| 0x706a8    | 1        | 3.57%   |
| 0x6fd      | 1        | 3.57%   |
| 0x40651    | 1        | 3.57%   |
| 0x306f2    | 1        | 3.57%   |
| 0x206c2    | 1        | 3.57%   |
| 0x10677    | 1        | 3.57%   |
| 0x10676    | 1        | 3.57%   |
| 0x0a201009 | 1        | 3.57%   |
| 0x0870100a | 1        | 3.57%   |
| 0x08600106 | 1        | 3.57%   |
| 0x0830104d | 1        | 3.57%   |
| 0x08301039 | 1        | 3.57%   |
| 0x08108109 | 1        | 3.57%   |
| 0x0800820d | 1        | 3.57%   |
| 0x06000852 | 1        | 3.57%   |
| Unknown    | 1        | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 6        | 21.43%  |
| Zen 2         | 4        | 14.29%  |
| IvyBridge     | 4        | 14.29%  |
| Zen+          | 2        | 7.14%   |
| SandyBridge   | 2        | 7.14%   |
| Penryn        | 2        | 7.14%   |
| CometLake     | 2        | 7.14%   |
| Zen 3         | 1        | 3.57%   |
| Westmere      | 1        | 3.57%   |
| Piledriver    | 1        | 3.57%   |
| KabyLake      | 1        | 3.57%   |
| Goldmont plus | 1        | 3.57%   |
| Core          | 1        | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 12       | 41.38%  |
| Intel  | 11       | 37.93%  |
| AMD    | 6        | 20.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 6.9%    |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 6.9%    |
| Nvidia TU117GL [T600]                                                       | 1        | 3.45%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 3.45%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 3.45%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 3.45%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 3.45%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 3.45%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 3.45%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 3.45%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 3.45%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 3.45%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 3.45%   |
| Nvidia GA102GL [RTX A6000]                                                  | 1        | 3.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 3.45%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 3.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.45%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 3.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 3.45%   |
| AMD Renoir                                                                  | 1        | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 3.45%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 3.45%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 11       | 39.29%  |
| 1 x Intel      | 10       | 35.71%  |
| 1 x AMD        | 6        | 21.43%  |
| Intel + Nvidia | 1        | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 21       | 75%     |
| Proprietary | 5        | 17.86%  |
| Unknown     | 2        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 39.29%  |
| 1.01-2.0   | 4        | 14.29%  |
| 0.01-0.5   | 4        | 14.29%  |
| 0.51-1.0   | 3        | 10.71%  |
| 7.01-8.0   | 2        | 7.14%   |
| 32.01-64.0 | 1        | 3.57%   |
| 5.01-6.0   | 1        | 3.57%   |
| 3.01-4.0   | 1        | 3.57%   |
| 8.01-16.0  | 1        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 6        | 26.09%  |
| Samsung Electronics | 4        | 17.39%  |
| Iiyama              | 3        | 13.04%  |
| Goldstar            | 2        | 8.7%    |
| Acer                | 2        | 8.7%    |
| Sony                | 1        | 4.35%   |
| OEM                 | 1        | 4.35%   |
| Hewlett-Packard     | 1        | 4.35%   |
| HCL                 | 1        | 4.35%   |
| Eizo                | 1        | 4.35%   |
| ASUSTek Computer    | 1        | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Sony LG TV SNY045B 1920x540                                         | 1        | 4%      |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch   | 1        | 4%      |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch   | 1        | 4%      |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch | 1        | 4%      |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch  | 1        | 4%      |
| OEM 19W_LCD_TV OEM3700 1920x540                                     | 1        | 4%      |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                | 1        | 4%      |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                | 1        | 4%      |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                 | 1        | 4%      |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch        | 1        | 4%      |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                 | 1        | 4%      |
| Goldstar WFHD GSM7748 2560x1080 798x334mm 34.1-inch                 | 1        | 4%      |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch            | 1        | 4%      |
| Goldstar ULTRAWIDE GSM76F6 1920x1080 800x335mm 34.1-inch            | 1        | 4%      |
| Eizo CG247X ENC2801 1920x1200 520x330mm 24.2-inch                   | 1        | 4%      |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                    | 1        | 4%      |
| Dell P1913 DELA088 1440x900 410x260mm 19.1-inch                     | 1        | 4%      |
| Dell LCD Monitor U2414H 3840x1080                                   | 1        | 4%      |
| Dell LCD Monitor U2414H                                             | 1        | 4%      |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                   | 1        | 4%      |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                   | 1        | 4%      |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                   | 1        | 4%      |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch        | 1        | 4%      |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                     | 1        | 4%      |
| Acer G277HL ACR03FB 1920x1080 598x336mm 27.0-inch                   | 1        | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 7        | 29.17%  |
| 3840x1080         | 2        | 8.33%   |
| 1920x540          | 2        | 8.33%   |
| 1920x1200 (WUXGA) | 2        | 8.33%   |
| 1600x900 (HD+)    | 2        | 8.33%   |
| 1440x900 (WXGA+)  | 2        | 8.33%   |
| 1280x1024 (SXGA)  | 2        | 8.33%   |
| 3840x2160 (4K)    | 1        | 4.17%   |
| 3440x1440         | 1        | 4.17%   |
| 2560x1080         | 1        | 4.17%   |
| 1366x768 (WXGA)   | 1        | 4.17%   |
| Unknown           | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 4        | 17.39%  |
| 27      | 3        | 13.04%  |
| 19      | 3        | 13.04%  |
| 23      | 2        | 8.7%    |
| 17      | 2        | 8.7%    |
| 65      | 1        | 4.35%   |
| 48      | 1        | 4.35%   |
| 40      | 1        | 4.35%   |
| 34      | 1        | 4.35%   |
| 31      | 1        | 4.35%   |
| 28      | 1        | 4.35%   |
| 20      | 1        | 4.35%   |
| 18      | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 43.48%  |
| 401-500     | 5        | 21.74%  |
| 301-350     | 2        | 8.7%    |
| 1001-1500   | 2        | 8.7%    |
| 801-900     | 1        | 4.35%   |
| 701-800     | 1        | 4.35%   |
| 601-700     | 1        | 4.35%   |
| Unknown     | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 14       | 60.87%  |
| 16/10   | 3        | 13.04%  |
| 5/4     | 2        | 8.7%    |
| 32/9    | 1        | 4.35%   |
| 3/2     | 1        | 4.35%   |
| 21/9    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 4        | 17.39%  |
| 151-200        | 4        | 17.39%  |
| 351-500        | 3        | 13.04%  |
| 301-350        | 3        | 13.04%  |
| 141-150        | 3        | 13.04%  |
| 251-300        | 2        | 8.7%    |
| 501-1000       | 2        | 8.7%    |
| More than 1000 | 1        | 4.35%   |
| Unknown        | 1        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 86.96%  |
| 1-50    | 1        | 4.35%   |
| 121-160 | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 75%     |
| 0     | 5        | 17.86%  |
| 2     | 2        | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 14       | 36.84%  |
| Intel                     | 13       | 34.21%  |
| Qualcomm Atheros          | 2        | 5.26%   |
| Marvell Technology Group  | 2        | 5.26%   |
| Solarflare Communications | 1        | 2.63%   |
| Ralink Technology         | 1        | 2.63%   |
| Microsoft                 | 1        | 2.63%   |
| Linksys                   | 1        | 2.63%   |
| BUFFALO                   | 1        | 2.63%   |
| Broadcom                  | 1        | 2.63%   |
| Aquantia                  | 1        | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 29.27%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 7.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 7.32%   |
| Intel Wireless 3165                                               | 2        | 4.88%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.88%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 2.44%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 2.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 2.44%   |
| Realtek 802.11ac NIC                                              | 1        | 2.44%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 2.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 2.44%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 2.44%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 2.44%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 2.44%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 2.44%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.44%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.44%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.44%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 2.44%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]          | 1        | 2.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 27.27%  |
| Realtek Semiconductor | 2        | 18.18%  |
| Qualcomm Atheros      | 2        | 18.18%  |
| Ralink Technology     | 1        | 9.09%   |
| Microsoft             | 1        | 9.09%   |
| Linksys               | 1        | 9.09%   |
| BUFFALO               | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                      | 2        | 18.18%  |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter  | 1        | 9.09%   |
| Realtek 802.11ac NIC                                     | 1        | 9.09%   |
| Ralink MT7601U Wireless Adapter                          | 1        | 9.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter         | 1        | 9.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter         | 1        | 9.09%   |
| Microsoft Xbox 360 Wireless Adapter                      | 1        | 9.09%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter      | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                      | 1        | 9.09%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070] | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 13       | 44.83%  |
| Intel                     | 11       | 37.93%  |
| Marvell Technology Group  | 2        | 6.9%    |
| Solarflare Communications | 1        | 3.45%   |
| Broadcom                  | 1        | 3.45%   |
| Aquantia                  | 1        | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 40%     |
| Intel Ethernet Connection I217-LM                                 | 3        | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 10%     |
| Intel I211 Gigabit Network Connection                             | 2        | 6.67%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 3.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 3.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 3.33%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 3.33%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 3.33%   |
| Intel Ethernet Connection I217-V                                  | 1        | 3.33%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 3.33%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 3.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 3.33%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 71.79%  |
| WiFi     | 11       | 28.21%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 88.89%  |
| WiFi     | 3        | 11.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 67.86%  |
| 2     | 9        | 32.14%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 82.14%  |
| Yes  | 5        | 17.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 3        | 42.86%  |
| Integrated System Solution | 1        | 14.29%  |
| IMC Networks               | 1        | 14.29%  |
| Cambridge Silicon Radio    | 1        | 14.29%  |
| Broadcom                   | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                    | 2        | 28.57%  |
| Intel AX200 Bluetooth                                 | 1        | 14.29%  |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 14.29%  |
| IMC Networks Bluetooth Device                         | 1        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1        | 14.29%  |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 20       | 43.48%  |
| Nvidia              | 12       | 26.09%  |
| AMD                 | 9        | 19.57%  |
| C-Media Electronics | 2        | 4.35%   |
| Unknown             | 1        | 2.17%   |
| Nektar              | 1        | 2.17%   |
| ASUSTek Computer    | 1        | 2.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4        | 7.41%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3        | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 5.56%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 3.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 3.7%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 3.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 3.7%    |
| C-Media Electronics USB MICROPHONE                                                | 2        | 3.7%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2        | 3.7%    |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 3.7%    |
| Unknown Realtek USB Audio Rear                                                    | 1        | 1.85%   |
| Unknown Realtek USB Audio Front                                                   | 1        | 1.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.85%   |
| Nvidia High Definition Audio Controller                                           | 1        | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 1.85%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 1.85%   |
| Nvidia GM200 High Definition Audio                                                | 1        | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 1.85%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1        | 1.85%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 1.85%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 1.85%   |
| Nektar Impact GX61                                                                | 1        | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 1.85%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 1.85%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 1.85%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 1        | 1.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 1.85%   |
| Intel 8 Series HD Audio Controller                                                | 1        | 1.85%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 1.85%   |
| ASUSTek Computer USB Audio                                                        | 1        | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 1.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 1.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.85%   |
| AMD Navi 10 HDMI Audio                                                            | 1        | 1.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 1.85%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 20%     |
| G.Skill             | 4        | 20%     |
| Unknown             | 3        | 15%     |
| Micron Technology   | 3        | 15%     |
| Kingston            | 2        | 10%     |
| SK hynix            | 1        | 5%      |
| Patriot             | 1        | 5%      |
| Corsair             | 1        | 5%      |
| A-DATA Technology   | 1        | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 667MT/s                    | 1        | 4.55%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1        | 4.55%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 1        | 4.55%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 1        | 4.55%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s   | 1        | 4.55%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s   | 1        | 4.55%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s    | 1        | 4.55%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s   | 1        | 4.55%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s   | 1        | 4.55%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s       | 1        | 4.55%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s               | 1        | 4.55%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s    | 1        | 4.55%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s     | 1        | 4.55%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s | 1        | 4.55%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s  | 1        | 4.55%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s  | 1        | 4.55%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3600MT/s    | 1        | 4.55%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s   | 1        | 4.55%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s     | 1        | 4.55%   |
| G.Skill RAM F3-12800CL10 8GB DIMM DDR3 1600MT/s        | 1        | 4.55%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s   | 1        | 4.55%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s           | 1        | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 10       | 52.63%  |
| DDR3    | 7        | 36.84%  |
| DDR2    | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 17       | 89.47%  |
| SODIMM | 1        | 5.26%   |
| RIMM   | 1        | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 40%     |
| 32768 | 4        | 20%     |
| 16384 | 2        | 10%     |
| 4096  | 2        | 10%     |
| 2048  | 2        | 10%     |
| 1024  | 2        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 5        | 25%     |
| 2400  | 2        | 10%     |
| 2133  | 2        | 10%     |
| 1600  | 2        | 10%     |
| 667   | 2        | 10%     |
| 3600  | 1        | 5%      |
| 3400  | 1        | 5%      |
| 2666  | 1        | 5%      |
| 2200  | 1        | 5%      |
| 1866  | 1        | 5%      |
| 1800  | 1        | 5%      |
| 1333  | 1        | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother HL-2030 Laser Printer | 1        | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| HP OfficeJet 6110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 50%     |
| Huawei Technologies | 1        | 25%     |
| Elgato Systems      | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Webcam C270          | 1        | 25%     |
| Logitech HD Pro Webcam C920   | 1        | 25%     |
| Huawei HiCamera               | 1        | 25%     |
| Elgato Systems Elgato Facecam | 1        | 25%     |

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
| 0     | 19       | 67.86%  |
| 1     | 7        | 25%     |
| 2     | 2        | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Net/wireless        | 4        | 40%     |
| Unassigned class    | 1        | 10%     |
| Storage             | 1        | 10%     |
| Sound               | 1        | 10%     |
| Net/ethernet        | 1        | 10%     |
| Graphics card       | 1        | 10%     |
| Firewire controller | 1        | 10%     |

