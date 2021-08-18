Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| HP      | ProBook 450 G2              | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Acer    | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP      | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo  | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP      | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer    | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell    | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell    | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer    | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell    | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell    | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo  | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo  | ThinkPad E15 Gen 2 20TD0... | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell    | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo  | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell    | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell    | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell    | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo  | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP      | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu | LIFEBOOK AH532              | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell    | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP      | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP      | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP      | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer   | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell    | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell    | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer    | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo  | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo  | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo  | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo  | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-25-generic | 7         | 25%     |
| 5.8.0-53-generic  | 6         | 21.43%  |
| 5.8.0-59-generic  | 5         | 17.86%  |
| 5.8.0-55-generic  | 5         | 17.86%  |
| 5.8.0-50-generic  | 4         | 14.29%  |
| 5.8.0-63-generic  | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.8.0   | 21        | 75%     |
| 5.11.0  | 7         | 25%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.8     | 21        | 75%     |
| 5.11    | 7         | 25%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 28        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 26        | 92.86%  |
| Wayland | 2         | 7.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 75%     |
| GDM     | 7         | 25%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 6         | 21.43%  |
| en_IN | 6         | 21.43%  |
| en_GB | 3         | 10.71%  |
| nl_NL | 2         | 7.14%   |
| hu_HU | 2         | 7.14%   |
| de_DE | 2         | 7.14%   |
| ru_UA | 1         | 3.57%   |
| ru_RU | 1         | 3.57%   |
| pt_BR | 1         | 3.57%   |
| fr_FR | 1         | 3.57%   |
| en_ZA | 1         | 3.57%   |
| en_PH | 1         | 3.57%   |
| en_CA | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 21        | 75%     |
| BIOS | 7         | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 27        | 96.43%  |
| Btrfs | 1         | 3.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 75%     |
| GPT     | 7         | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 89.29%  |
| Yes       | 3         | 10.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 7         | 25%     |
| Lenovo              | 6         | 21.43%  |
| Hewlett-Packard     | 5         | 17.86%  |
| Acer                | 4         | 14.29%  |
| ASUSTek Computer    | 3         | 10.71%  |
| Samsung Electronics | 1         | 3.57%   |
| Razer               | 1         | 3.57%   |
| Fujitsu             | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 3.57%   |
| Razer Book 13 - RZ09-0357                | 1         | 3.57%   |
| Lenovo ThinkPad Yoga 11e 20DAS0SF00      | 1         | 3.57%   |
| Lenovo ThinkPad E15 Gen 2 20TD000HZA     | 1         | 3.57%   |
| Lenovo IdeaPad Y570 0862                 | 1         | 3.57%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 1         | 3.57%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 1         | 3.57%   |
| Lenovo IdeaPad 100-15IBD 80QQ            | 1         | 3.57%   |
| HP ProBook 650 G2                        | 1         | 3.57%   |
| HP ProBook 450 G2                        | 1         | 3.57%   |
| HP ProBook 430 G6                        | 1         | 3.57%   |
| HP 15                                    | 1         | 3.57%   |
| Fujitsu LIFEBOOK AH532                   | 1         | 3.57%   |
| Dell XPS L501X                           | 1         | 3.57%   |
| Dell XPS 13 9370                         | 1         | 3.57%   |
| Dell Vostro 5490                         | 1         | 3.57%   |
| Dell Inspiron 7537                       | 1         | 3.57%   |
| Dell Inspiron 3582                       | 1         | 3.57%   |
| Dell Inspiron 3576                       | 1         | 3.57%   |
| Dell G3 3579                             | 1         | 3.57%   |
| ASUS X406UAR                             | 1         | 3.57%   |
| ASUS TUF Gaming FX505DT_FX505DT          | 1         | 3.57%   |
| ASUS ASUS TUF Gaming A15 FA506IH_FA506IH | 1         | 3.57%   |
| Acer Swift SF313-51                      | 1         | 3.57%   |
| Acer Swift SF114-34                      | 1         | 3.57%   |
| Acer Aspire E5-551G                      | 1         | 3.57%   |
| Acer Aspire E1-571                       | 1         | 3.57%   |
| Unknown                                  | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo IdeaPad   | 4         | 14.29%  |
| HP ProBook       | 3         | 10.71%  |
| Dell Inspiron    | 3         | 10.71%  |
| Lenovo ThinkPad  | 2         | 7.14%   |
| Dell XPS         | 2         | 7.14%   |
| Acer Swift       | 2         | 7.14%   |
| Acer Aspire      | 2         | 7.14%   |
| Samsung 350V5C   | 1         | 3.57%   |
| Razer Book       | 1         | 3.57%   |
| HP 15            | 1         | 3.57%   |
| Fujitsu LIFEBOOK | 1         | 3.57%   |
| Dell Vostro      | 1         | 3.57%   |
| Dell G3          | 1         | 3.57%   |
| ASUS X406UAR     | 1         | 3.57%   |
| ASUS TUF         | 1         | 3.57%   |
| ASUS ASUS        | 1         | 3.57%   |
| Unknown          | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 25%     |
| 2019 | 7         | 25%     |
| 2020 | 5         | 17.86%  |
| 2018 | 2         | 7.14%   |
| 2013 | 2         | 7.14%   |
| 2011 | 2         | 7.14%   |
| 2016 | 1         | 3.57%   |
| 2015 | 1         | 3.57%   |
| 2008 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 28        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 22        | 78.57%  |
| Enabled  | 6         | 21.43%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 10        | 35.71%  |
| 3.01-4.0   | 8         | 28.57%  |
| 16.01-24.0 | 5         | 17.86%  |
| 8.01-16.0  | 5         | 17.86%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 11        | 39.29%  |
| 1.01-2.0 | 9         | 32.14%  |
| 3.01-4.0 | 5         | 17.86%  |
| 4.01-8.0 | 3         | 10.71%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 82.14%  |
| 2      | 5         | 17.86%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 67.86%  |
| Yes       | 9         | 32.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 78.57%  |
| No        | 6         | 21.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 96.43%  |
| No        | 1         | 3.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 85.71%  |
| No        | 4         | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| India        | 6         | 21.43%  |
| USA          | 3         | 10.71%  |
| UK           | 3         | 10.71%  |
| Netherlands  | 2         | 7.14%   |
| Hungary      | 2         | 7.14%   |
| Germany      | 2         | 7.14%   |
| Ukraine      | 1         | 3.57%   |
| South Africa | 1         | 3.57%   |
| Romania      | 1         | 3.57%   |
| Philippines  | 1         | 3.57%   |
| Mexico       | 1         | 3.57%   |
| Madagascar   | 1         | 3.57%   |
| Canada       | 1         | 3.57%   |
| Brazil       | 1         | 3.57%   |
| Azerbaijan   | 1         | 3.57%   |
| Austria      | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Hyderabad        | 2         | 7.14%   |
| Vienna           | 1         | 3.57%   |
| Vancouver        | 1         | 3.57%   |
| Sutton Coldfield | 1         | 3.57%   |
| Stadskanaal      | 1         | 3.57%   |
| San Francisco    | 1         | 3.57%   |
| Quezon City      | 1         | 3.57%   |
| Pretoria         | 1         | 3.57%   |
| Ohmbach          | 1         | 3.57%   |
| Nyiregyhaza      | 1         | 3.57%   |
| Mérida          | 1         | 3.57%   |
| Manchester       | 1         | 3.57%   |
| Kyiv             | 1         | 3.57%   |
| Kolkata          | 1         | 3.57%   |
| Kingston         | 1         | 3.57%   |
| Galgamacsa       | 1         | 3.57%   |
| Fortaleza        | 1         | 3.57%   |
| Ernakulam        | 1         | 3.57%   |
| Dudley           | 1         | 3.57%   |
| Chennai          | 1         | 3.57%   |
| Charlotte        | 1         | 3.57%   |
| Berlin           | 1         | 3.57%   |
| Baku             | 1         | 3.57%   |
| Arad             | 1         | 3.57%   |
| Antananarivo     | 1         | 3.57%   |
| Amsterdam        | 1         | 3.57%   |
| Ahmedabad        | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 15.63%  |
| WDC                 | 4         | 4      | 12.5%   |
| Toshiba             | 4         | 4      | 12.5%   |
| SanDisk             | 4         | 4      | 12.5%   |
| Samsung Electronics | 4         | 4      | 12.5%   |
| Kingston            | 2         | 3      | 6.25%   |
| Intel               | 2         | 2      | 6.25%   |
| A-DATA Technology   | 2         | 2      | 6.25%   |
| Unknown             | 1         | 1      | 3.13%   |
| Phison              | 1         | 1      | 3.13%   |
| KIOXIA              | 1         | 1      | 3.13%   |
| HGST                | 1         | 1      | 3.13%   |
| Crucial             | 1         | 1      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 3         | 9.38%   |
| WDC WD5000LPVT-22G33T0 500GB            | 1         | 3.13%   |
| WDC WD10JPVX-60JC3T1 1TB                | 1         | 3.13%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 3.13%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 3.13%   |
| Unknown SD/MMC/MS PRO 128GB             | 1         | 3.13%   |
| Toshiba THNSNJ128GCSU 128GB SSD         | 1         | 3.13%   |
| Toshiba MQ01ABF050 500GB                | 1         | 3.13%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 1         | 3.13%   |
| Toshiba KBG40ZMT128G MEMORY 128GB       | 1         | 3.13%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 3.13%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 3.13%   |
| SanDisk SSD PLUS 480GB                  | 1         | 3.13%   |
| SanDisk SD8SN8U256G1002 256GB SSD       | 1         | 3.13%   |
| Sandisk NVMe SSD Drive 256GB            | 1         | 3.13%   |
| Sandisk NVMe SSD Drive 128GB            | 1         | 3.13%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 3.13%   |
| Samsung NVMe SSD Drive 512GB            | 1         | 3.13%   |
| Samsung MZVLB512HBJQ-00A00 512GB        | 1         | 3.13%   |
| Samsung HM640JJ 640GB                   | 1         | 3.13%   |
| Phison NVMe SSD Drive 2TB               | 1         | 3.13%   |
| KIOXIA NVMe SSD Drive 512GB             | 1         | 3.13%   |
| Kingston SA400S37480G 480GB SSD         | 1         | 3.13%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 3.13%   |
| Intel SSDSC2KW256G8L 256GB              | 1         | 3.13%   |
| Intel SSDPEKNW512G8 512GB               | 1         | 3.13%   |
| HGST HTS725050A7E630 500GB              | 1         | 3.13%   |
| Crucial CT480BX500SSD1 480GB            | 1         | 3.13%   |
| A-DATA SX900 256GB SSD                  | 1         | 3.13%   |
| A-DATA SX8200PNP 512GB                  | 1         | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 45.45%  |
| WDC                 | 3         | 3      | 27.27%  |
| Toshiba             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| HGST                | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 20%     |
| SanDisk             | 2         | 2      | 20%     |
| Kingston            | 2         | 3      | 20%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Intel               | 1         | 1      | 10%     |
| Crucial             | 1         | 1      | 10%     |
| A-DATA Technology   | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 11        | 11     | 34.38%  |
| NVMe    | 10        | 10     | 31.25%  |
| SSD     | 10        | 11     | 31.25%  |
| Unknown | 1         | 1      | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 22     | 64.52%  |
| NVMe | 10        | 10     | 32.26%  |
| SAS  | 1         | 1      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 15     | 66.67%  |
| 0.51-1.0   | 7         | 7      | 33.33%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 16        | 57.14%  |
| 101-250    | 7         | 25%     |
| 501-1000   | 4         | 14.29%  |
| 1001-2000  | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 10        | 35.71%  |
| 1-20     | 10        | 35.71%  |
| 101-250  | 3         | 10.71%  |
| 51-100   | 3         | 10.71%  |
| 251-500  | 1         | 3.57%   |
| 501-1000 | 1         | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 21        | 25     | 75%     |
| Works    | 6         | 7      | 21.43%  |
| Malfunc  | 1         | 1      | 3.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 20        | 62.5%   |
| Sandisk             | 3         | 9.38%   |
| AMD                 | 3         | 9.38%   |
| Samsung Electronics | 2         | 6.25%   |
| KIOXIA              | 2         | 6.25%   |
| Phison Electronics  | 1         | 3.13%   |
| ADATA Technology    | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 4         | 12.12%  |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 3         | 9.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 3         | 9.09%   |
| KIOXIA Non-Volatile memory controller                                        | 2         | 6.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 6.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 6.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 3.03%   |
| Samsung NVMe Controller                                                      | 1         | 3.03%   |
| Phison E12 NVMe Controller                                                   | 1         | 3.03%   |
| Intel SSD 660P Series                                                        | 1         | 3.03%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 3.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 3.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 3.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 3.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 3.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 3.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 3.03%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                  | 1         | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 63.64%  |
| NVMe | 10        | 30.3%   |
| RAID | 1         | 3.03%   |
| IDE  | 1         | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 85.71%  |
| AMD    | 4         | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 10.71%  |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 7.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 7.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 7.14%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 3.57%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 3.57%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.57%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 3.57%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 3.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 3.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 3.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.57%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 3.57%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 3.57%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 3.57%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.57%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 3.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 3.57%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 3.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.57%   |
| AMD FX-7500 Radeon R7, 10 Compute Cores 4C+6G | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 10        | 35.71%  |
| Intel Core i7        | 6         | 21.43%  |
| Other                | 2         | 7.14%   |
| Intel Core i3        | 2         | 7.14%   |
| Intel Celeron        | 2         | 7.14%   |
| AMD Ryzen 5          | 2         | 7.14%   |
| Intel Pentium Silver | 1         | 3.57%   |
| Intel Core 2 Duo     | 1         | 3.57%   |
| AMD Ryzen 7          | 1         | 3.57%   |
| AMD FX               | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 17        | 60.71%  |
| 2      | 10        | 35.71%  |
| 8      | 1         | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 82.14%  |
| 1      | 5         | 17.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ea    | 5         | 17.86%  |
| 0x306a9    | 3         | 10.71%  |
| 0x806ec    | 2         | 7.14%   |
| 0x806c1    | 2         | 7.14%   |
| 0x40651    | 2         | 7.14%   |
| 0x306d4    | 2         | 7.14%   |
| Unknown    | 2         | 7.14%   |
| 0x906ea    | 1         | 3.57%   |
| 0x906c0    | 1         | 3.57%   |
| 0x706a1    | 1         | 3.57%   |
| 0x6fb      | 1         | 3.57%   |
| 0x30678    | 1         | 3.57%   |
| 0x206a7    | 1         | 3.57%   |
| 0x08600104 | 1         | 3.57%   |
| 0x08108109 | 1         | 3.57%   |
| 0x08108102 | 1         | 3.57%   |
| 0x06003106 | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 28.57%  |
| IvyBridge     | 3         | 10.71%  |
| Zen+          | 2         | 7.14%   |
| TigerLake     | 2         | 7.14%   |
| Haswell       | 2         | 7.14%   |
| Broadwell     | 2         | 7.14%   |
| Zen 2         | 1         | 3.57%   |
| Tremont       | 1         | 3.57%   |
| Steamroller   | 1         | 3.57%   |
| Skylake       | 1         | 3.57%   |
| Silvermont    | 1         | 3.57%   |
| SandyBridge   | 1         | 3.57%   |
| Nehalem       | 1         | 3.57%   |
| Goldmont plus | 1         | 3.57%   |
| Core          | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 60.53%  |
| Nvidia | 9         | 23.68%  |
| AMD    | 6         | 15.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 5         | 12.82%  |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 7.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 5.13%   |
| Intel HD Graphics 5500                                                    | 2         | 5.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 5.13%   |
| AMD Picasso                                                               | 2         | 5.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 2.56%   |
| Nvidia TU117M                                                             | 1         | 2.56%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 2.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 2.56%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 2.56%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 2.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 2.56%   |
| Nvidia GF108M [GeForce GT 555M]                                           | 1         | 2.56%   |
| Nvidia GF108M [GeForce GT 435M]                                           | 1         | 2.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 2.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 2.56%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                 | 1         | 2.56%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 2.56%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 2.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 2.56%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 2.56%   |
| AMD Renoir                                                                | 1         | 2.56%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                   | 1         | 2.56%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                        | 1         | 2.56%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]              | 1         | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 53.57%  |
| Intel + Nvidia | 6         | 21.43%  |
| Intel + AMD    | 2         | 7.14%   |
| AMD + Nvidia   | 2         | 7.14%   |
| 2 x AMD        | 1         | 3.57%   |
| 1 x Nvidia     | 1         | 3.57%   |
| 1 x AMD        | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 21        | 75%     |
| Proprietary | 6         | 21.43%  |
| Unknown     | 1         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 67.86%  |
| 1.01-2.0   | 5         | 17.86%  |
| 3.01-4.0   | 2         | 7.14%   |
| 0.51-1.0   | 1         | 3.57%   |
| 0.01-0.5   | 1         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 8         | 26.67%  |
| BOE                 | 6         | 20%     |
| Chimei Innolux      | 5         | 16.67%  |
| Sharp               | 2         | 6.67%   |
| Samsung Electronics | 2         | 6.67%   |
| PANDA               | 2         | 6.67%   |
| LG Display          | 1         | 3.33%   |
| Lenovo              | 1         | 3.33%   |
| Dell                | 1         | 3.33%   |
| BenQ                | 1         | 3.33%   |
| Acer                | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 6.67%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch               | 1         | 3.33%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch  | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch | 1         | 3.33%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 3.33%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 3.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 3.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 3.33%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch      | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch       | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 350x190mm 15.7-inch       | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN139E 1920x1080 293x165mm 13.2-inch      | 1         | 3.33%   |
| BOE LCD Monitor BOE08F2 1920x1080 310x174mm 14.0-inch                 | 1         | 3.33%   |
| BOE LCD Monitor BOE082E 1920x1080 309x174mm 14.0-inch                 | 1         | 3.33%   |
| BOE LCD Monitor BOE07DD 1920x1080 293x165mm 13.2-inch                 | 1         | 3.33%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                 | 1         | 3.33%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                  | 1         | 3.33%   |
| BOE LCD Monitor BOE05E9 1366x768 256x144mm 11.6-inch                  | 1         | 3.33%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor 1366x768                                     | 1         | 3.33%   |
| Acer ED273 ACR0575 1920x1080 531x299mm 24.0-inch                      | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 14        | 50%     |
| 1366x768 (WXGA) | 11        | 39.29%  |
| 3840x2400       | 1         | 3.57%   |
| 3840x2160 (4K)  | 1         | 3.57%   |
| 1280x800 (WXGA) | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 15        | 50%     |
| 13      | 7         | 23.33%  |
| 24      | 3         | 10%     |
| 14      | 2         | 6.67%   |
| 18      | 1         | 3.33%   |
| 11      | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 66.67%  |
| 201-300     | 5         | 16.67%  |
| 501-600     | 3         | 10%     |
| 401-500     | 1         | 3.33%   |
| Unknown     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 24        | 88.89%  |
| 16/10   | 2         | 7.41%   |
| Unknown | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 50%     |
| 81-90          | 5         | 16.67%  |
| 71-80          | 4         | 13.33%  |
| 201-250        | 3         | 10%     |
| 51-60          | 1         | 3.33%   |
| 141-150        | 1         | 3.33%   |
| Unknown        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 36.67%  |
| 101-120       | 9         | 30%     |
| 51-100        | 5         | 16.67%  |
| More than 240 | 2         | 6.67%   |
| 161-240       | 2         | 6.67%   |
| Unknown       | 1         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 85.71%  |
| 2     | 3         | 10.71%  |
| 0     | 1         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 36.96%  |
| Intel                 | 16        | 34.78%  |
| Qualcomm Atheros      | 6         | 13.04%  |
| Broadcom              | 3         | 6.52%   |
| Samsung Electronics   | 1         | 2.17%   |
| Ralink                | 1         | 2.17%   |
| DisplayLink           | 1         | 2.17%   |
| Broadcom Limited      | 1         | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 27.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.88%   |
| Intel Wireless 7260                                               | 3         | 5.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 3.92%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 3.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 3.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.96%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.96%   |
| Realtek 802.11ac NIC                                              | 1         | 1.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.96%   |
| Intel Wireless 8260                                               | 1         | 1.96%   |
| Intel Wireless 7265                                               | 1         | 1.96%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.96%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.96%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.96%   |
| Intel Centrino Wireless-N 105                                     | 1         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.96%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.96%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 1.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.96%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 1.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 1         | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 53.57%  |
| Qualcomm Atheros      | 6         | 21.43%  |
| Realtek Semiconductor | 4         | 14.29%  |
| Broadcom              | 2         | 7.14%   |
| Ralink                | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                        | 3         | 10.71%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 7.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 2         | 7.14%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 7.14%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]               | 2         | 7.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.57%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.57%   |
| Realtek 802.11ac NIC                                       | 1         | 3.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1         | 3.57%   |
| Intel Wireless 8260                                        | 1         | 3.57%   |
| Intel Wireless 7265                                        | 1         | 3.57%   |
| Intel Wi-Fi 6 AX201 160MHz                                 | 1         | 3.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 3.57%   |
| Intel Centrino Wireless-N 2230                             | 1         | 3.57%   |
| Intel Centrino Wireless-N 105                              | 1         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 3.57%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller     | 1         | 3.57%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 73.91%  |
| Intel                 | 2         | 8.7%    |
| Samsung Electronics   | 1         | 4.35%   |
| DisplayLink           | 1         | 4.35%   |
| Broadcom Limited      | 1         | 4.35%   |
| Broadcom              | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 60.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 13.04%  |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 4.35%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.35%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 4.35%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 4.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 4.35%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 55.1%   |
| Ethernet | 22        | 44.9%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 56.1%   |
| Ethernet | 18        | 43.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 71.43%  |
| 1     | 8         | 28.57%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 75%     |
| Yes  | 7         | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 50%     |
| Qualcomm Atheros Communications | 4         | 16.67%  |
| IMC Networks                    | 3         | 12.5%   |
| Realtek Semiconductor           | 1         | 4.17%   |
| Ralink                          | 1         | 4.17%   |
| Lite-On Technology              | 1         | 4.17%   |
| Foxconn / Hon Hai               | 1         | 4.17%   |
| Broadcom                        | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 5         | 20.83%  |
| Intel Bluetooth Device                         | 5         | 20.83%  |
| Qualcomm Atheros  Bluetooth Device             | 2         | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 8.33%   |
| IMC Networks Bluetooth Radio                   | 2         | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 4.17%   |
| Ralink RT3290 Bluetooth                        | 1         | 4.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 4.17%   |
| Lite-On BCM43142A0                             | 1         | 4.17%   |
| IMC Networks Bluetooth Device                  | 1         | 4.17%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 4.17%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module       | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 70.59%  |
| Nvidia | 6         | 17.65%  |
| AMD    | 4         | 11.76%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 14.63%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 7.32%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3         | 7.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 4.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 4.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 4.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 4.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 4.88%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 4.88%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 4.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 2.44%   |
| Intel Jasper Lake HD Graphics SGPC                                         | 1         | 2.44%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.44%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 2.44%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 41.67%  |
| Micron Technology   | 3         | 25%     |
| SK Hynix            | 1         | 8.33%   |
| Ramaxel Technology  | 1         | 8.33%   |
| Kingston            | 1         | 8.33%   |
| Crucial             | 1         | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 7.14%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s     | 1         | 7.14%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s          | 1         | 7.14%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s          | 1         | 7.14%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s          | 1         | 7.14%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s          | 1         | 7.14%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 1         | 7.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 1         | 7.14%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 7.14%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 7.14%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 1         | 7.14%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s         | 1         | 7.14%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 7.14%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s            | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 4         | 36.36%  |
| DDR3   | 4         | 36.36%  |
| SDRAM  | 1         | 9.09%   |
| LPDDR4 | 1         | 9.09%   |
| LPDDR3 | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 8         | 72.73%  |
| Row Of Chips | 3         | 27.27%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 6         | 54.55%  |
| 8192 | 3         | 27.27%  |
| 2048 | 2         | 18.18%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 4         | 33.33%  |
| 1600  | 4         | 33.33%  |
| 4267  | 1         | 8.33%   |
| 4199  | 1         | 8.33%   |
| 3200  | 1         | 8.33%   |
| 1867  | 1         | 8.33%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 7         | 26.92%  |
| Sunplus Innovation Technology          | 4         | 15.38%  |
| Microdia                               | 3         | 11.54%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 11.54%  |
| Realtek Semiconductor                  | 2         | 7.69%   |
| Quanta                                 | 2         | 7.69%   |
| Chicony Electronics                    | 2         | 7.69%   |
| Acer                                   | 2         | 7.69%   |
| Lite-On Technology                     | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 11.54%  |
| Sunplus Integrated_Webcam_HD                        | 2         | 7.69%   |
| Realtek Integrated_Webcam_HD                        | 2         | 7.69%   |
| IMC Networks Integrated Camera                      | 2         | 7.69%   |
| Sunplus HD WebCam                                   | 1         | 3.85%   |
| Sunplus HD User Facing                              | 1         | 3.85%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 3.85%   |
| Quanta HD User Facing                               | 1         | 3.85%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 3.85%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.85%   |
| Microdia Integrated HD Webcam                       | 1         | 3.85%   |
| Lite-On HP HD Camera                                | 1         | 3.85%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 3.85%   |
| IMC Networks EasyCamera                             | 1         | 3.85%   |
| Chicony HD WebCam                                   | 1         | 3.85%   |
| Chicony FJ Camera                                   | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 3.85%   |
| Acer Lenovo EasyCamera                              | 1         | 3.85%   |
| Acer Integrated Camera                              | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 2         | 66.67%  |
| LighTuning Technology | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 33.33%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 33.33%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 33.33%  |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 20        | 71.43%  |
| 1     | 5         | 17.86%  |
| 2     | 3         | 10.71%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 3         | 30%     |
| Fingerprint reader    | 3         | 30%     |
| Net/wireless          | 2         | 20%     |
| Multimedia controller | 1         | 10%     |
| Bluetooth             | 1         | 10%     |

