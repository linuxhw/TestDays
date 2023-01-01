Solus 4.2 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Solus 4.2.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Solus_4.2/Desktop/README.md) and [notebooks](/Dist/Solus_4.2/Notebook/README.md).

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

Total: 37

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 15-3568              | Notebook    | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [53fef6a61a](https://linux-hardware.org/?probe=53fef6a61a) | Jul 08, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [48cb73de41](https://linux-hardware.org/?probe=48cb73de41) | Jul 01, 2021 |
| Biostar       | A320MH                      | Desktop     | [2c478119e9](https://linux-hardware.org/?probe=2c478119e9) | Jun 30, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [6fc3976633](https://linux-hardware.org/?probe=6fc3976633) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [0e1e07507e](https://linux-hardware.org/?probe=0e1e07507e) | Jun 15, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [4fc48865ef](https://linux-hardware.org/?probe=4fc48865ef) | Jun 15, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [f5c8f64400](https://linux-hardware.org/?probe=f5c8f64400) | Jun 03, 2021 |
| Howard Com... | W350                        | Notebook    | [3e55c8284e](https://linux-hardware.org/?probe=3e55c8284e) | May 28, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [dfa5c022b3](https://linux-hardware.org/?probe=dfa5c022b3) | May 26, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [ce04df7bae](https://linux-hardware.org/?probe=ce04df7bae) | May 23, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [a33e231e6b](https://linux-hardware.org/?probe=a33e231e6b) | May 23, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e53c63ba89](https://linux-hardware.org/?probe=e53c63ba89) | May 19, 2021 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [f759ad1793](https://linux-hardware.org/?probe=f759ad1793) | May 13, 2021 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [f28f1ea67d](https://linux-hardware.org/?probe=f28f1ea67d) | May 13, 2021 |
| Intel         | X99 V102                    | Desktop     | [bc57aedd09](https://linux-hardware.org/?probe=bc57aedd09) | May 02, 2021 |
| Gigabyte      | AORUS 17G KB                | Notebook    | [fd9385ff3c](https://linux-hardware.org/?probe=fd9385ff3c) | Apr 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b5f3f78ddb](https://linux-hardware.org/?probe=b5f3f78ddb) | Apr 25, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [5c51b7f289](https://linux-hardware.org/?probe=5c51b7f289) | Apr 25, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | Notebook    | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| Dell          | 0FH884                      | Desktop     | [93acc58efb](https://linux-hardware.org/?probe=93acc58efb) | Apr 10, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e8b5a1786b](https://linux-hardware.org/?probe=e8b5a1786b) | Apr 08, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [c7c0f7323d](https://linux-hardware.org/?probe=c7c0f7323d) | Mar 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [accdafb993](https://linux-hardware.org/?probe=accdafb993) | Mar 08, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [f4e39d4730](https://linux-hardware.org/?probe=f4e39d4730) | Mar 04, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [e507a57307](https://linux-hardware.org/?probe=e507a57307) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f1c277189f](https://linux-hardware.org/?probe=f1c277189f) | Feb 16, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [d8b7b99dd0](https://linux-hardware.org/?probe=d8b7b99dd0) | Feb 16, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [cdd0998f7c](https://linux-hardware.org/?probe=cdd0998f7c) | Feb 14, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f4ee71d37f](https://linux-hardware.org/?probe=f4ee71d37f) | Feb 12, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [7a2993f67a](https://linux-hardware.org/?probe=7a2993f67a) | Feb 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.11.12-177.current | 5         | 17.24%  |
| 5.11.22-180.current | 4         | 13.79%  |
| 5.10.15-172.current | 4         | 13.79%  |
| 5.13.0-186.current  | 2         | 6.9%    |
| 5.12.10-182.current | 2         | 6.9%    |
| 5.11.9-176.current  | 2         | 6.9%    |
| 5.11.21-179.current | 2         | 6.9%    |
| 5.11.16-178.current | 2         | 6.9%    |
| 5.10.12-171.current | 2         | 6.9%    |
| 5.6.19-159.current  | 1         | 3.45%   |
| 5.12.13-185.current | 1         | 3.45%   |
| 5.10.7-168.current  | 1         | 3.45%   |
| 4.14.221-168.lts    | 1         | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.11.12  | 5         | 17.24%  |
| 5.11.22  | 4         | 13.79%  |
| 5.10.15  | 4         | 13.79%  |
| 5.13.0   | 2         | 6.9%    |
| 5.12.10  | 2         | 6.9%    |
| 5.11.9   | 2         | 6.9%    |
| 5.11.21  | 2         | 6.9%    |
| 5.11.16  | 2         | 6.9%    |
| 5.10.12  | 2         | 6.9%    |
| 5.6.19   | 1         | 3.45%   |
| 5.12.13  | 1         | 3.45%   |
| 5.10.7   | 1         | 3.45%   |
| 4.14.221 | 1         | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 14        | 50%     |
| 5.10    | 7         | 25%     |
| 5.12    | 3         | 10.71%  |
| 5.13    | 2         | 7.14%   |
| 5.6     | 1         | 3.57%   |
| 4.14    | 1         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 25        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 15        | 55.56%  |
| GNOME   | 4         | 14.81%  |
| MATE    | 3         | 11.11%  |
| Unknown | 3         | 11.11%  |
| KDE     | 2         | 7.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 25        | 96.15%  |
| Unknown | 1         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 84.62%  |
| TDM     | 3         | 11.54%  |
| GDM     | 1         | 3.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 12        | 48%     |
| pt_BR | 3         | 12%     |
| ru_RU | 2         | 8%      |
| en_GB | 2         | 8%      |
| tr_TR | 1         | 4%      |
| pt_PT | 1         | 4%      |
| pl_PL | 1         | 4%      |
| fr_FR | 1         | 4%      |
| en_NZ | 1         | 4%      |
| en_IE | 1         | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 13        | 50%     |
| EFI  | 13        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 24        | 96%     |
| Xfs  | 1         | 4%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 20        | 76.92%  |
| GPT     | 5         | 19.23%  |
| MBR     | 1         | 3.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 96%     |
| Yes       | 1         | 4%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 92%     |
| Yes       | 2         | 8%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 4         | 16%     |
| Lenovo              | 3         | 12%     |
| Gigabyte Technology | 3         | 12%     |
| Dell                | 3         | 12%     |
| Hewlett-Packard     | 2         | 8%      |
| Acer                | 2         | 8%      |
| Toshiba             | 1         | 4%      |
| Shuttle             | 1         | 4%      |
| Packard Bell        | 1         | 4%      |
| MSI                 | 1         | 4%      |
| Intel               | 1         | 4%      |
| Howard Computers    | 1         | 4%      |
| Biostar             | 1         | 4%      |
| Apple               | 1         | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite L855                   | 1         | 4%      |
| Shuttle XS35V4                           | 1         | 4%      |
| Packard Bell EasyNote TS11HR             | 1         | 4%      |
| MSI MS-7B85                              | 1         | 4%      |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00 | 1         | 4%      |
| Lenovo ThinkPad T430 2349CV2             | 1         | 4%      |
| Lenovo Legion Y530-15ICH 81FV            | 1         | 4%      |
| Intel X99 V102                           | 1         | 4%      |
| Howard Computers W350                    | 1         | 4%      |
| HP ProBook 650 G1                        | 1         | 4%      |
| HP Pavilion dv7                          | 1         | 4%      |
| Gigabyte J4005ND2P-CF                    | 1         | 4%      |
| Gigabyte B360M AORUS Gaming 3            | 1         | 4%      |
| Gigabyte AORUS 17G KB                    | 1         | 4%      |
| Dell OptiPlex GX620                      | 1         | 4%      |
| Dell OptiPlex 9020                       | 1         | 4%      |
| Dell Inspiron 3537                       | 1         | 4%      |
| Biostar A320MH                           | 1         | 4%      |
| ASUS ROG CROSSHAIR VIII HERO             | 1         | 4%      |
| ASUS PRIME Z390-P                        | 1         | 4%      |
| ASUS P9X79 DELUXE                        | 1         | 4%      |
| ASUS N53SV                               | 1         | 4%      |
| Apple iMac17,1                           | 1         | 4%      |
| Acer Aspire E5-575G                      | 1         | 4%      |
| Acer Aspire 5735                         | 1         | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 2         | 8%      |
| Dell OptiPlex         | 2         | 8%      |
| Acer Aspire           | 2         | 8%      |
| Toshiba Satellite     | 1         | 4%      |
| Shuttle XS35V4        | 1         | 4%      |
| Packard Bell EasyNote | 1         | 4%      |
| MSI MS-7B85           | 1         | 4%      |
| Lenovo Legion         | 1         | 4%      |
| Intel X99             | 1         | 4%      |
| Howard Computers W350 | 1         | 4%      |
| HP ProBook            | 1         | 4%      |
| HP Pavilion           | 1         | 4%      |
| Gigabyte J4005ND2P-CF | 1         | 4%      |
| Gigabyte B360M        | 1         | 4%      |
| Gigabyte AORUS        | 1         | 4%      |
| Dell Inspiron         | 1         | 4%      |
| Biostar A320MH        | 1         | 4%      |
| ASUS ROG              | 1         | 4%      |
| ASUS PRIME            | 1         | 4%      |
| ASUS P9X79            | 1         | 4%      |
| ASUS N53SV            | 1         | 4%      |
| Apple iMac17          | 1         | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 6         | 24%     |
| 2012 | 3         | 12%     |
| 2019 | 2         | 8%      |
| 2016 | 2         | 8%      |
| 2014 | 2         | 8%      |
| 2013 | 2         | 8%      |
| 2011 | 2         | 8%      |
| 2008 | 2         | 8%      |
| 2021 | 1         | 4%      |
| 2020 | 1         | 4%      |
| 2010 | 1         | 4%      |
| 2006 | 1         | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 13        | 52%     |
| Desktop    | 11        | 44%     |
| All in one | 1         | 4%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 25        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 7         | 28%     |
| 3.01-4.0    | 4         | 16%     |
| 16.01-24.0  | 4         | 16%     |
| 32.01-64.0  | 3         | 12%     |
| 24.01-32.0  | 2         | 8%      |
| 8.01-16.0   | 2         | 8%      |
| 2.01-3.0    | 1         | 4%      |
| 64.01-256.0 | 1         | 4%      |
| 1.01-2.0    | 1         | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 12        | 48%     |
| 2.01-3.0  | 4         | 16%     |
| 3.01-4.0  | 3         | 12%     |
| 4.01-8.0  | 2         | 8%      |
| 8.01-16.0 | 2         | 8%      |
| 0.51-1.0  | 2         | 8%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 13        | 50%     |
| 2      | 8         | 30.77%  |
| 3      | 3         | 11.54%  |
| 6      | 1         | 3.85%   |
| 4      | 1         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 60%     |
| No        | 10        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 84%     |
| No        | 4         | 16%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 56%     |
| No        | 11        | 44%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 5         | 20%     |
| Brazil      | 3         | 12%     |
| Sweden      | 2         | 8%      |
| Russia      | 2         | 8%      |
| UK          | 1         | 4%      |
| Turkey      | 1         | 4%      |
| Spain       | 1         | 4%      |
| Portugal    | 1         | 4%      |
| Poland      | 1         | 4%      |
| New Zealand | 1         | 4%      |
| Netherlands | 1         | 4%      |
| Mexico      | 1         | 4%      |
| Ireland     | 1         | 4%      |
| India       | 1         | 4%      |
| Guatemala   | 1         | 4%      |
| Greece      | 1         | 4%      |
| France      | 1         | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| St Petersburg             | 2         | 7.41%   |
| Severna Park              | 2         | 7.41%   |
| SГЈo Pedro              | 1         | 3.7%    |
| Santa Maria               | 1         | 3.7%    |
| Santa Cruz                | 1         | 3.7%    |
| San Francisco del Rincón | 1         | 3.7%    |
| San Francisco             | 1         | 3.7%    |
| Moita Bonita              | 1         | 3.7%    |
| Miami                     | 1         | 3.7%    |
| Malmo                     | 1         | 3.7%    |
| Málaga                   | 1         | 3.7%    |
| Lexington                 | 1         | 3.7%    |
| Istanbul                  | 1         | 3.7%    |
| Guatemala City            | 1         | 3.7%    |
| Gray-la-Ville             | 1         | 3.7%    |
| Gdansk                    | 1         | 3.7%    |
| Enfield                   | 1         | 3.7%    |
| Dublin                    | 1         | 3.7%    |
| Dijon                     | 1         | 3.7%    |
| Delhi                     | 1         | 3.7%    |
| Bossier City              | 1         | 3.7%    |
| Auckland                  | 1         | 3.7%    |
| Athens                    | 1         | 3.7%    |
| Ängelholm                | 1         | 3.7%    |
| Amsterdam                 | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 12     | 18.42%  |
| WDC                 | 5         | 6      | 13.16%  |
| SanDisk             | 4         | 5      | 10.53%  |
| Samsung Electronics | 4         | 7      | 10.53%  |
| Toshiba             | 2         | 3      | 5.26%   |
| Micron Technology   | 2         | 3      | 5.26%   |
| Kingston            | 2         | 3      | 5.26%   |
| A-DATA Technology   | 2         | 2      | 5.26%   |
| Unknown             | 1         | 1      | 2.63%   |
| Transcend           | 1         | 1      | 2.63%   |
| SK hynix            | 1         | 1      | 2.63%   |
| Patriot             | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| Gigabyte Technology | 1         | 1      | 2.63%   |
| Corsair             | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |
| Apple               | 1         | 3      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB          | 2         | 4.44%   |
| Seagate ST31000524AS 1TB                 | 2         | 4.44%   |
| Samsung SSD 850 EVO 250GB                | 2         | 4.44%   |
| Samsung NVMe SSD Drive 500GB             | 2         | 4.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 1         | 2.22%   |
| WDC WD40EZRZ-00GXCB0 4TB                 | 1         | 2.22%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 2.22%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 2.22%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 2.22%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1         | 2.22%   |
| Unknown R5M120G8 120GB SSD               | 1         | 2.22%   |
| Transcend TS240GSSD220S 240GB            | 1         | 2.22%   |
| Toshiba MK7575GSX 752GB                  | 1         | 2.22%   |
| Toshiba MK3275GSX 320GB                  | 1         | 2.22%   |
| SK hynix NVMe SSD Drive 128GB            | 1         | 2.22%   |
| Seagate ST9750420AS 752GB                | 1         | 2.22%   |
| Seagate ST9320325AS 320GB                | 1         | 2.22%   |
| Seagate ST2000DX002-2DV164 2TB           | 1         | 2.22%   |
| Seagate ST2000DX001-1NS164 2TB           | 1         | 2.22%   |
| Seagate ST1000DM010-2EP102 1TB           | 1         | 2.22%   |
| Seagate ST1000DM003-1CH162 1TB           | 1         | 2.22%   |
| SanDisk SDSSDP064G 64GB                  | 1         | 2.22%   |
| SanDisk SDSSDA240G 240GB                 | 1         | 2.22%   |
| SanDisk SD7SN6S512G1001 512GB SSD        | 1         | 2.22%   |
| SanDisk Extreme SSD 500GB                | 1         | 2.22%   |
| Samsung SSD 970 EVO Plus 2TB             | 1         | 2.22%   |
| Samsung SSD 970 EVO 500GB                | 1         | 2.22%   |
| Samsung PSSD T7 500GB                    | 1         | 2.22%   |
| Patriot Spark 256GB SSD                  | 1         | 2.22%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 2.22%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD      | 1         | 2.22%   |
| Kingston SA400S37240G 240GB SSD          | 1         | 2.22%   |
| Kingston NVMe SSD Drive 1TB              | 1         | 2.22%   |
| Intel SSDSC2CW120A3 120GB                | 1         | 2.22%   |
| HGST HTS721010A9E630 1TB                 | 1         | 2.22%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD     | 1         | 2.22%   |
| Corsair Force LS SSD 64GB                | 1         | 2.22%   |
| China SATA SSD 240GB                     | 1         | 2.22%   |
| Apple SSD SM1024G 1TB                    | 1         | 2.22%   |
| A-DATA SX8200PNP-512GT 512GB             | 1         | 2.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 12     | 50%     |
| WDC     | 4         | 5      | 28.57%  |
| Toshiba | 2         | 3      | 14.29%  |
| HGST    | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 5      | 20%     |
| Samsung Electronics | 3         | 3      | 15%     |
| Micron Technology   | 2         | 3      | 10%     |
| WDC                 | 1         | 1      | 5%      |
| Unknown             | 1         | 1      | 5%      |
| Transcend           | 1         | 1      | 5%      |
| Patriot             | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| Gigabyte Technology | 1         | 1      | 5%      |
| Corsair             | 1         | 1      | 5%      |
| China               | 1         | 1      | 5%      |
| Apple               | 1         | 3      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 18        | 24     | 48.65%  |
| HDD  | 14        | 21     | 37.84%  |
| NVMe | 5         | 8      | 13.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 42     | 76.67%  |
| NVMe | 5         | 8      | 16.67%  |
| SAS  | 2         | 3      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 25     | 62.5%   |
| 0.51-1.0   | 10        | 15     | 31.25%  |
| 3.01-4.0   | 1         | 1      | 3.13%   |
| 1.01-2.0   | 1         | 4      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 9         | 36%     |
| 251-500        | 7         | 28%     |
| 501-1000       | 3         | 12%     |
| 1001-2000      | 2         | 8%      |
| 51-100         | 2         | 8%      |
| More than 3000 | 1         | 4%      |
| 21-50          | 1         | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 10        | 40%     |
| 21-50     | 5         | 20%     |
| 51-100    | 3         | 12%     |
| 101-250   | 2         | 8%      |
| 1001-2000 | 2         | 8%      |
| 501-1000  | 2         | 8%      |
| 251-500   | 1         | 4%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 970 EVO 500GB          | 1         | 1      | 50%     |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Micron Technology   | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 50%     |
| SSD  | 1         | 1      | 50%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 21        | 41     | 72.41%  |
| Works    | 6         | 10     | 20.69%  |
| Malfunc  | 2         | 2      | 6.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 21        | 63.64%  |
| Samsung Electronics         | 4         | 12.12%  |
| AMD                         | 3         | 9.09%   |
| SK hynix                    | 1         | 3.03%   |
| Marvell Technology Group    | 1         | 3.03%   |
| Kingston Technology Company | 1         | 3.03%   |
| ASMedia Technology          | 1         | 3.03%   |
| ADATA Technology            | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 11.43%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 5.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 5.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 5.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 5.71%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 5.71%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.86%   |
| Samsung Electronics SATA controller                                            | 1         | 2.86%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo          | 1         | 2.86%   |
| Kingston Company KC2000 NVMe SSD                                               | 1         | 2.86%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.86%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 2.86%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                          | 1         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.86%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 2.86%   |
| AMD FCH SATA Controller D                                                      | 1         | 2.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 2.86%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 22        | 73.33%  |
| NVMe | 5         | 16.67%  |
| IDE  | 2         | 6.67%   |
| RAID | 1         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 88%     |
| AMD    | 3         | 12%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 8%      |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1         | 4%      |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 4%      |
| Intel Pentium D CPU 3.00GHz                 | 1         | 4%      |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 4%      |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 4%      |
| Intel Core i7-4600M CPU @ 2.90GHz           | 1         | 4%      |
| Intel Core i7-3960X CPU @ 3.30GHz           | 1         | 4%      |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 4%      |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 4%      |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 4%      |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 4%      |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1         | 4%      |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 4%      |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 4%      |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 4%      |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 4%      |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 4%      |
| Intel Celeron J4005 CPU @ 2.00GHz           | 1         | 4%      |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1         | 4%      |
| Intel Celeron CPU B830 @ 1.80GHz            | 1         | 4%      |
| AMD Ryzen 9 5950X 16-Core Processor         | 1         | 4%      |
| AMD Ryzen 7 3700X 8-Core Processor          | 1         | 4%      |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 1         | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 7         | 28%     |
| Intel Core i5      | 7         | 28%     |
| Intel Celeron      | 3         | 12%     |
| Intel Core i3      | 2         | 8%      |
| Intel Xeon         | 1         | 4%      |
| Intel Pentium Dual | 1         | 4%      |
| Intel Pentium D    | 1         | 4%      |
| AMD Ryzen 9        | 1         | 4%      |
| AMD Ryzen 7        | 1         | 4%      |
| AMD Ryzen 5        | 1         | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 11        | 44%     |
| 4      | 7         | 28%     |
| 6      | 4         | 16%     |
| 8      | 2         | 8%      |
| 16     | 1         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 68%     |
| 1      | 8         | 32%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 25        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 5         | 20%     |
| 0x306c3    | 2         | 8%      |
| 0xf62      | 1         | 4%      |
| 0xa0652    | 1         | 4%      |
| 0x906ed    | 1         | 4%      |
| 0x906eb    | 1         | 4%      |
| 0x906ea    | 1         | 4%      |
| 0x806e9    | 1         | 4%      |
| 0x706a1    | 1         | 4%      |
| 0x6fd      | 1         | 4%      |
| 0x506e3    | 1         | 4%      |
| 0x406e3    | 1         | 4%      |
| 0x40651    | 1         | 4%      |
| 0x306a9    | 1         | 4%      |
| 0x30678    | 1         | 4%      |
| 0x206d7    | 1         | 4%      |
| 0x0a201009 | 1         | 4%      |
| 0x08701021 | 1         | 4%      |
| 0x08101016 | 1         | 4%      |
| Unknown    | 1         | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| SandyBridge   | 6         | 24%     |
| KabyLake      | 4         | 16%     |
| Haswell       | 4         | 16%     |
| Skylake       | 2         | 8%      |
| Zen 3         | 1         | 4%      |
| Zen 2         | 1         | 4%      |
| Zen           | 1         | 4%      |
| Silvermont    | 1         | 4%      |
| NetBurst      | 1         | 4%      |
| IvyBridge     | 1         | 4%      |
| Goldmont plus | 1         | 4%      |
| Core          | 1         | 4%      |
| CometLake     | 1         | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 18        | 54.55%  |
| Nvidia | 9         | 27.27%  |
| AMD    | 6         | 18.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 15.15%  |
| Nvidia GF108M [GeForce GT 540M]                                             | 2         | 6.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 6.06%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 3.03%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 3.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 3.03%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 3.03%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1         | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 3.03%   |
| Intel HD Graphics 620                                                       | 1         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1         | 3.03%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 3.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 3.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1         | 3.03%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                               | 1         | 3.03%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1         | 3.03%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1         | 3.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1         | 3.03%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1         | 3.03%   |
| AMD Amethyst [Radeon R9 M395/ M395X Mac Edition]                            | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 10        | 38.46%  |
| Intel + Nvidia | 5         | 19.23%  |
| 1 x Nvidia     | 4         | 15.38%  |
| 1 x AMD        | 4         | 15.38%  |
| Intel + AMD    | 3         | 11.54%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 20        | 80%     |
| Proprietary | 5         | 20%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 36%     |
| 1.01-2.0   | 5         | 20%     |
| 3.01-4.0   | 3         | 12%     |
| 0.51-1.0   | 3         | 12%     |
| 7.01-8.0   | 2         | 8%      |
| 5.01-6.0   | 2         | 8%      |
| 2.01-3.0   | 1         | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 7         | 24.14%  |
| LG Display           | 4         | 13.79%  |
| Samsung Electronics  | 3         | 10.34%  |
| Ancor Communications | 3         | 10.34%  |
| Goldstar             | 2         | 6.9%    |
| Unknown              | 1         | 3.45%   |
| LG Electronics       | 1         | 3.45%   |
| JRY                  | 1         | 3.45%   |
| Iiyama               | 1         | 3.45%   |
| Hewlett-Packard      | 1         | 3.45%   |
| Dell                 | 1         | 3.45%   |
| BenQ                 | 1         | 3.45%   |
| Apple                | 1         | 3.45%   |
| AOC                  | 1         | 3.45%   |
| Acer                 | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor HIC 3200x1080                                    | 1         | 3.45%   |
| Samsung Electronics S19C200 SAM09B3 1440x900 408x255mm 18.9-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch | 1         | 3.45%   |
| LG Electronics LCD Monitor W1952 1440x900                            | 1         | 3.45%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 1         | 3.45%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch          | 1         | 3.45%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 3.45%   |
| LG Display LCD Monitor LGD020C 1600x900 345x194mm 15.6-inch          | 1         | 3.45%   |
| JRY LCD Monitor JRY1950 1600x900 368x207mm 16.6-inch                 | 1         | 3.45%   |
| Iiyama PLE2483H IVM6113 1920x1080 530x300mm 24.0-inch                | 1         | 3.45%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch          | 1         | 3.45%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1         | 3.45%   |
| Goldstar E1911 GSM4BF9 1366x768 410x230mm 18.5-inch                  | 1         | 3.45%   |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                    | 1         | 3.45%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                    | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO509D 1920x1080 382x215mm 17.3-inch       | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 309x173mm 13.9-inch       | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO15ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 1         | 3.45%   |
| Apple iMac APPAE05 3840x2160 597x336mm 27.0-inch                     | 1         | 3.45%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                      | 1         | 3.45%   |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch     | 1         | 3.45%   |
| Ancor Communications LCD Monitor VX229                               | 1         | 3.45%   |
| Ancor Communications LCD Monitor MG248 1920x1080                     | 1         | 3.45%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                   | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 10        | 35.71%  |
| 1366x768 (WXGA)   | 6         | 21.43%  |
| 1600x900 (HD+)    | 3         | 10.71%  |
| 1440x900 (WXGA+)  | 3         | 10.71%  |
| 3840x2160 (4K)    | 1         | 3.57%   |
| 3200x1080         | 1         | 3.57%   |
| 2560x1440 (QHD)   | 1         | 3.57%   |
| 1920x1200 (WUXGA) | 1         | 3.57%   |
| 1280x1024 (SXGA)  | 1         | 3.57%   |
| Unknown           | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 32.14%  |
| 24      | 3         | 10.71%  |
| 18      | 3         | 10.71%  |
| 17      | 3         | 10.71%  |
| Unknown | 3         | 10.71%  |
| 21      | 2         | 7.14%   |
| 13      | 2         | 7.14%   |
| 27      | 1         | 3.57%   |
| 25      | 1         | 3.57%   |
| 19      | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 44.44%  |
| 401-500     | 6         | 22.22%  |
| 501-600     | 4         | 14.81%  |
| Unknown     | 3         | 11.11%  |
| 351-400     | 2         | 7.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 18        | 69.23%  |
| 16/10   | 4         | 15.38%  |
| Unknown | 3         | 11.54%  |
| 5/4     | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 32.14%  |
| 201-250        | 4         | 14.29%  |
| 151-200        | 3         | 10.71%  |
| Unknown        | 3         | 10.71%  |
| 81-90          | 2         | 7.14%   |
| 251-300        | 2         | 7.14%   |
| 141-150        | 2         | 7.14%   |
| 121-130        | 2         | 7.14%   |
| 301-350        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 37.04%  |
| 51-100  | 8         | 29.63%  |
| 121-160 | 5         | 18.52%  |
| Unknown | 3         | 11.11%  |
| 161-240 | 1         | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 21        | 84%     |
| 2     | 4         | 16%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 15        | 34.88%  |
| Intel                         | 11        | 25.58%  |
| Qualcomm Atheros              | 6         | 13.95%  |
| Broadcom                      | 3         | 6.98%   |
| TP-Link                       | 1         | 2.33%   |
| Ralink Technology             | 1         | 2.33%   |
| Ralink                        | 1         | 2.33%   |
| OnePlus Technology (Shenzhen) | 1         | 2.33%   |
| NetGear                       | 1         | 2.33%   |
| Marvell Technology Group      | 1         | 2.33%   |
| Hewlett-Packard               | 1         | 2.33%   |
| Broadcom Limited              | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 18.87%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 3.77%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.89%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.89%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 1.89%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.89%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.89%   |
| Realtek 802.11ac NIC                                              | 1         | 1.89%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 1.89%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.89%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:3BB6B401                        | 1         | 1.89%   |
| NetGear A6150                                                     | 1         | 1.89%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.89%   |
| Intel Wireless-AC 9260                                            | 1         | 1.89%   |
| Intel Wireless 8260                                               | 1         | 1.89%   |
| Intel Wireless 7260                                               | 1         | 1.89%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.89%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.89%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.89%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.89%   |
| HP lt4112 Gobi 4G Module Network Device                           | 1         | 1.89%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 1.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.89%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 7         | 29.17%  |
| Realtek Semiconductor | 5         | 20.83%  |
| Qualcomm Atheros      | 5         | 20.83%  |
| TP-Link               | 1         | 4.17%   |
| Ralink Technology     | 1         | 4.17%   |
| Ralink                | 1         | 4.17%   |
| NetGear               | 1         | 4.17%   |
| Hewlett-Packard       | 1         | 4.17%   |
| Broadcom Limited      | 1         | 4.17%   |
| Broadcom              | 1         | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 8.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 4.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 4.17%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 4.17%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 4.17%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 4.17%   |
| Realtek 802.11ac NIC                                           | 1         | 4.17%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 4.17%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 4.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 4.17%   |
| NetGear A6150                                                  | 1         | 4.17%   |
| Intel Wireless-AC 9260                                         | 1         | 4.17%   |
| Intel Wireless 8260                                            | 1         | 4.17%   |
| Intel Wireless 7260                                            | 1         | 4.17%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 4.17%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 4.17%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 4.17%   |
| HP lt4112 Gobi 4G Module Network Device                        | 1         | 4.17%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 1         | 4.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 13        | 48.15%  |
| Intel                    | 9         | 33.33%  |
| Broadcom                 | 3         | 11.11%  |
| Qualcomm Atheros         | 1         | 3.7%    |
| Marvell Technology Group | 1         | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 35.71%  |
| Intel I211 Gigabit Network Connection                             | 2         | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 7.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 3.57%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 3.57%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.57%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.57%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.57%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 3.57%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.57%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.57%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 3.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 53.19%  |
| WiFi     | 21        | 44.68%  |
| Unknown  | 1         | 2.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 59.26%  |
| Ethernet | 11        | 40.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 18        | 69.23%  |
| 1     | 7         | 26.92%  |
| 3     | 1         | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 22        | 84.62%  |
| Yes  | 4         | 15.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 40%     |
| Realtek Semiconductor           | 2         | 13.33%  |
| Qualcomm Atheros Communications | 2         | 13.33%  |
| Apple                           | 2         | 13.33%  |
| Toshiba                         | 1         | 6.67%   |
| Lite-On Technology              | 1         | 6.67%   |
| Broadcom                        | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 2         | 13.33%  |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 2         | 13.33%  |
| Intel Bluetooth wireless interface               | 2         | 13.33%  |
| Apple Bluetooth USB Host Controller              | 2         | 13.33%  |
| Toshiba RT Bluetooth Radio                       | 1         | 6.67%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 6.67%   |
| Qualcomm Atheros AR3011 Bluetooth                | 1         | 6.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 6.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 1         | 6.67%   |
| Intel AX200 Bluetooth                            | 1         | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 22        | 56.41%  |
| Nvidia                  | 8         | 20.51%  |
| AMD                     | 6         | 15.38%  |
| Logitech                | 1         | 2.56%   |
| Blue Microphones        | 1         | 2.56%   |
| BEHRINGER International | 1         | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 9.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 6.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 6.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 4.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 4.55%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 4.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 4.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 2.27%   |
| Logitech USB Headset                                                       | 1         | 2.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.27%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.27%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 2.27%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.27%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1         | 2.27%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.27%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 2.27%   |
| BEHRINGER International UMC202HD 192k                                      | 1         | 2.27%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1         | 2.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 2.27%   |
| AMD Navi 10 HDMI Audio                                                     | 1         | 2.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 2.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 2.27%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 2         | 22.22%  |
| Unknown             | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| Nanya Technology    | 1         | 11.11%  |
| Kingston            | 1         | 11.11%  |
| G.Skill             | 1         | 11.11%  |
| Crucial             | 1         | 11.11%  |
| A-DATA Technology   | 1         | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB SODIMM DDR3 1867MT/s            | 1         | 11.11%  |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 1         | 11.11%  |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s      | 1         | 11.11%  |
| Micron RAM Module 4096MB SODIMM DDR3 1867MT/s             | 1         | 11.11%  |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 11.11%  |
| Kingston RAM 9905624-044.A00G 8192MB SODIMM DDR4 2400MT/s | 1         | 11.11%  |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 1         | 11.11%  |
| Crucial RAM CT32G4SFD832A.M16FB 32GB SODIMM DDR4 3200MT/s | 1         | 11.11%  |
| A-DATA RAM AO1P24HC8T1-B2NS 8GB SODIMM DDR4 2133MT/s      | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 3         | 50%     |
| DDR3 | 3         | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 5         | 83.33%  |
| DIMM   | 1         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2         | 28.57%  |
| 4096  | 2         | 28.57%  |
| 32768 | 1         | 14.29%  |
| 16384 | 1         | 14.29%  |
| 2048  | 1         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3866  | 1         | 14.29%  |
| 3200  | 1         | 14.29%  |
| 2400  | 1         | 14.29%  |
| 2133  | 1         | 14.29%  |
| 1867  | 1         | 14.29%  |
| 1600  | 1         | 14.29%  |
| 1334  | 1         | 14.29%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP DeskJet 3630 series | 1         | 100%    |

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


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chicony Electronics | 3         | 21.43%  |
| Suyin               | 2         | 14.29%  |
| Lite-On Technology  | 2         | 14.29%  |
| Apple               | 2         | 14.29%  |
| Microsoft           | 1         | 7.14%   |
| Microdia            | 1         | 7.14%   |
| Logitech            | 1         | 7.14%   |
| Importek            | 1         | 7.14%   |
| IMC Networks        | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Suyin HP TrueVision HD Integrated Webcam  | 1         | 7.14%   |
| Suyin 1.3M HD WebCam                      | 1         | 7.14%   |
| Microsoft LifeCam HD-3000                 | 1         | 7.14%   |
| Microdia Dell Laptop Integrated Webcam HD | 1         | 7.14%   |
| Logitech Logitech Webcam C160             | 1         | 7.14%   |
| Lite-On Integrated Camera                 | 1         | 7.14%   |
| Lite-On HP HD Webcam                      | 1         | 7.14%   |
| Importek TOSHIBA Web Camera - HD          | 1         | 7.14%   |
| IMC Networks USB2.0 HD UVC WebCam         | 1         | 7.14%   |
| Chicony Integrated Camera                 | 1         | 7.14%   |
| Chicony HD WebCam                         | 1         | 7.14%   |
| Chicony 2.0M UVC WebCam                   | 1         | 7.14%   |
| Apple iPhone5/5C/5S/6                     | 1         | 7.14%   |
| Apple FaceTime HD Camera (Built-in)       | 1         | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 75%     |
| Upek             | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 25%     |
| Validity Sensors Fingerprint scanner              | 1         | 25%     |
| Upek TCS5B Fingerprint sensor                     | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Upek   | 1         | 33.33%  |
| Lenovo | 1         | 33.33%  |
| BIT4ID | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 33.33%  |
| Lenovo Integrated Smart Card Reader                        | 1         | 33.33%  |
| BIT4ID miniLector EVO                                      | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 17        | 65.38%  |
| 1     | 6         | 23.08%  |
| 2     | 3         | 11.54%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 4         | 36.36%  |
| Fingerprint reader | 4         | 36.36%  |
| Chipcard           | 2         | 18.18%  |
| Unassigned class   | 1         | 9.09%   |

