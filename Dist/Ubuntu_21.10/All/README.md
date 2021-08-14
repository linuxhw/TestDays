Ubuntu 21.10 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_21.10/Desktop/README.md) and [notebooks](/Dist/Ubuntu_21.10/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-21.10

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

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu  | D3400-B2 S26361-D3400-B2    | Desktop     | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| ASUSTek  | ROG Strix G533QS_G533QS     | Notebook    | [612dda8fba](https://linux-hardware.org/?probe=612dda8fba) | Aug 13, 2021 |
| ASUSTek  | ROG Strix G533QS_G533QS     | Notebook    | [1eb6008b88](https://linux-hardware.org/?probe=1eb6008b88) | Aug 13, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | Notebook    | [808cfab06b](https://linux-hardware.org/?probe=808cfab06b) | Aug 12, 2021 |
| Lenovo   | ThinkPad T510 4484A63       | Notebook    | [c1bcb3451f](https://linux-hardware.org/?probe=c1bcb3451f) | Aug 09, 2021 |
| Lenovo   | ThinkPad T510 4484A63       | Notebook    | [4336b50906](https://linux-hardware.org/?probe=4336b50906) | Aug 06, 2021 |
| MSI      | MAG B550M MORTAR            | Desktop     | [912b2a77a2](https://linux-hardware.org/?probe=912b2a77a2) | Aug 05, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X530... | Notebook    | [961031411d](https://linux-hardware.org/?probe=961031411d) | Aug 03, 2021 |
| Lenovo   | ZhaoYang K3-ITL 82E3        | Notebook    | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| ASUSTek  | GL753VD                     | Notebook    | [eabe6a8723](https://linux-hardware.org/?probe=eabe6a8723) | Jul 31, 2021 |
| Acer     | Aspire 5920                 | Notebook    | [f41defe215](https://linux-hardware.org/?probe=f41defe215) | Jul 31, 2021 |
| Dell     | XPS 13 7390                 | Notebook    | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| Teclast  | F6 Pro                      | Notebook    | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| Huanan   | X99 F8D V2.2                | Desktop     | [74e4c61bbf](https://linux-hardware.org/?probe=74e4c61bbf) | Jul 23, 2021 |
| Huanan   | X99 F8D V2.2                | Desktop     | [02ad72fb54](https://linux-hardware.org/?probe=02ad72fb54) | Jul 21, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X421... | Notebook    | [f5458b4f56](https://linux-hardware.org/?probe=f5458b4f56) | Jul 19, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X421... | Notebook    | [5ac65f3389](https://linux-hardware.org/?probe=5ac65f3389) | Jul 18, 2021 |
| Lenovo   | Z50-70 20354                | Notebook    | [85aadf8abd](https://linux-hardware.org/?probe=85aadf8abd) | Jul 16, 2021 |
| Gigabyte | F2A55M-HD2                  | Desktop     | [6a69f09403](https://linux-hardware.org/?probe=6a69f09403) | Jul 15, 2021 |
| Lenovo   | Z50-70 20354                | Notebook    | [b2c80f450e](https://linux-hardware.org/?probe=b2c80f450e) | Jul 14, 2021 |
| HP       | Pavilion Gaming Laptop 1... | Notebook    | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo   | ThinkPad X201 3626FAG       | Notebook    | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Positivo | H14BT58                     | Notebook    | [51b9ba65e0](https://linux-hardware.org/?probe=51b9ba65e0) | Jun 18, 2021 |
| ASUSTek  | ROG Strix G533QR_G533QR     | Notebook    | [4befd5f360](https://linux-hardware.org/?probe=4befd5f360) | Jun 04, 2021 |
| Dell     | XPS 13 9343                 | Notebook    | [4ee08e92ae](https://linux-hardware.org/?probe=4ee08e92ae) | May 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.11.0-20-generic     | 5         | 26.32%  |
| 5.13.0-12-generic     | 2         | 10.53%  |
| 5.11.0-25-generic     | 2         | 10.53%  |
| 5.11.0-18-generic     | 2         | 10.53%  |
| 5.13.6-xanmod2-edge   | 1         | 5.26%   |
| 5.13.4-051304-generic | 1         | 5.26%   |
| 5.13.2-051302-generic | 1         | 5.26%   |
| 5.13.0-13-generic     | 1         | 5.26%   |
| 5.13.0-051300-generic | 1         | 5.26%   |
| 5.11.0-26-generic     | 1         | 5.26%   |
| 5.11.0-22-generic     | 1         | 5.26%   |
| 5.11.0-16-generic     | 1         | 5.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 12        | 63.16%  |
| 5.13.0  | 4         | 21.05%  |
| 5.13.6  | 1         | 5.26%   |
| 5.13.4  | 1         | 5.26%   |
| 5.13.2  | 1         | 5.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 63.16%  |
| 5.13    | 7         | 36.84%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 19        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 13        | 68.42%  |
| X-Cinnamon      | 3         | 15.79%  |
| Unity           | 1         | 5.26%   |
| GNOME Flashback | 1         | 5.26%   |
| Cinnamon        | 1         | 5.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 10        | 52.63%  |
| X11     | 9         | 47.37%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 9         | 47.37%  |
| Unknown | 9         | 47.37%  |
| TDM     | 1         | 5.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_GB | 7         | 36.84%  |
| fr_FR | 3         | 15.79%  |
| en_US | 2         | 10.53%  |
| zh_CN | 1         | 5.26%   |
| sv_SE | 1         | 5.26%   |
| ru_RU | 1         | 5.26%   |
| pt_BR | 1         | 5.26%   |
| ko_KR | 1         | 5.26%   |
| es_MX | 1         | 5.26%   |
| es_AR | 1         | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 10        | 52.63%  |
| BIOS | 9         | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 19        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 9         | 47.37%  |
| Unknown | 9         | 47.37%  |
| MBR     | 1         | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 12        | 63.16%  |
| Yes       | 7         | 36.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11        | 57.89%  |
| No        | 8         | 42.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 6         | 31.58%  |
| Lenovo              | 3         | 15.79%  |
| Dell                | 2         | 10.53%  |
| Teclast             | 1         | 5.26%   |
| Positivo            | 1         | 5.26%   |
| MSI                 | 1         | 5.26%   |
| Huanan              | 1         | 5.26%   |
| Hewlett-Packard     | 1         | 5.26%   |
| Gigabyte Technology | 1         | 5.26%   |
| Fujitsu             | 1         | 5.26%   |
| Acer                | 1         | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Teclast F6 Pro                          | 1         | 5.26%   |
| Positivo H14BT58                        | 1         | 5.26%   |
| MSI MS-7C94                             | 1         | 5.26%   |
| Lenovo ZhaoYang K3-ITL 82E3             | 1         | 5.26%   |
| Lenovo Z50-70 20354                     | 1         | 5.26%   |
| Lenovo ThinkPad X201 3626FAG            | 1         | 5.26%   |
| Huanan X99 F8D V2.2                     | 1         | 5.26%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 5.26%   |
| Gigabyte F2A55M-HD2                     | 1         | 5.26%   |
| Fujitsu S1100F                          | 1         | 5.26%   |
| Dell XPS 13 9343                        | 1         | 5.26%   |
| Dell XPS 13 7390                        | 1         | 5.26%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN  | 1         | 5.26%   |
| ASUS VivoBook_ASUSLaptop X509DJ_M509DJ  | 1         | 5.26%   |
| ASUS VivoBook_ASUSLaptop X421UAY_M413UA | 1         | 5.26%   |
| ASUS ROG Strix G533QS_G533QS            | 1         | 5.26%   |
| ASUS ROG Strix G533QR_G533QR            | 1         | 5.26%   |
| ASUS GL753VD                            | 1         | 5.26%   |
| Acer Aspire 5920                        | 1         | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUS VivoBook       | 3         | 15.79%  |
| Dell XPS            | 2         | 10.53%  |
| ASUS ROG            | 2         | 10.53%  |
| Teclast F6          | 1         | 5.26%   |
| Positivo H14BT58    | 1         | 5.26%   |
| MSI MS-7C94         | 1         | 5.26%   |
| Lenovo ZhaoYang     | 1         | 5.26%   |
| Lenovo Z50-70       | 1         | 5.26%   |
| Lenovo ThinkPad     | 1         | 5.26%   |
| Huanan X99          | 1         | 5.26%   |
| HP Pavilion         | 1         | 5.26%   |
| Gigabyte F2A55M-HD2 | 1         | 5.26%   |
| Fujitsu S1100F      | 1         | 5.26%   |
| ASUS GL753VD        | 1         | 5.26%   |
| Acer Aspire         | 1         | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 8         | 42.11%  |
| 2020 | 2         | 10.53%  |
| 2019 | 2         | 10.53%  |
| 2018 | 1         | 5.26%   |
| 2017 | 1         | 5.26%   |
| 2015 | 1         | 5.26%   |
| 2014 | 1         | 5.26%   |
| 2013 | 1         | 5.26%   |
| 2010 | 1         | 5.26%   |
| 2008 | 1         | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 15        | 78.95%  |
| Desktop  | 4         | 21.05%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 18        | 94.74%  |
| Enabled  | 1         | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 19        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 36.84%  |
| 32.01-64.0 | 4         | 21.05%  |
| 8.01-16.0  | 3         | 15.79%  |
| 16.01-24.0 | 2         | 10.53%  |
| 3.01-4.0   | 1         | 5.26%   |
| 24.01-32.0 | 1         | 5.26%   |
| 1.01-2.0   | 1         | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 8         | 42.11%  |
| 4.01-8.0 | 5         | 26.32%  |
| 1.01-2.0 | 4         | 21.05%  |
| 3.01-4.0 | 2         | 10.53%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 11        | 57.89%  |
| 2      | 5         | 26.32%  |
| 3      | 2         | 10.53%  |
| 5      | 1         | 5.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 16        | 84.21%  |
| Yes       | 3         | 15.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 63.16%  |
| No        | 7         | 36.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 78.95%  |
| No        | 4         | 21.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 73.68%  |
| No        | 5         | 26.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| UK          | 5         | 26.32%  |
| France      | 3         | 15.79%  |
| Brazil      | 2         | 10.53%  |
| USA         | 1         | 5.26%   |
| Sweden      | 1         | 5.26%   |
| South Korea | 1         | 5.26%   |
| Russia      | 1         | 5.26%   |
| Lithuania   | 1         | 5.26%   |
| Germany     | 1         | 5.26%   |
| China       | 1         | 5.26%   |
| Chile       | 1         | 5.26%   |
| Argentina   | 1         | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Yongin-si              | 1         | 5.26%   |
| Trakai                 | 1         | 5.26%   |
| Tottenham              | 1         | 5.26%   |
| Shanghai               | 1         | 5.26%   |
| Santiago               | 1         | 5.26%   |
| Rosario                | 1         | 5.26%   |
| Rio de Janeiro         | 1         | 5.26%   |
| Paris                  | 1         | 5.26%   |
| Osasco                 | 1         | 5.26%   |
| Nizhny Tagil           | 1         | 5.26%   |
| Maidstone              | 1         | 5.26%   |
| Lyon                   | 1         | 5.26%   |
| Leiston                | 1         | 5.26%   |
| Helsingborg            | 1         | 5.26%   |
| Haselhorst             | 1         | 5.26%   |
| Glasgow                | 1         | 5.26%   |
| Crewe                  | 1         | 5.26%   |
| Charleville-M?�zi??res | 1         | 5.26%   |
| Austin                 | 1         | 5.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 20%     |
| Seagate             | 3         | 3      | 10%     |
| WDC                 | 2         | 2      | 6.67%   |
| Toshiba             | 2         | 2      | 6.67%   |
| SK Hynix            | 2         | 2      | 6.67%   |
| Sandisk             | 2         | 2      | 6.67%   |
| Kingston            | 2         | 2      | 6.67%   |
| Intel               | 2         | 3      | 6.67%   |
| Unknown             | 1         | 1      | 3.33%   |
| SP                  | 1         | 1      | 3.33%   |
| Silicon Motion      | 1         | 1      | 3.33%   |
| PNY                 | 1         | 1      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |
| KIOXIA-EXCERIA      | 1         | 1      | 3.33%   |
| KingDian            | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| China               | 1         | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix HFM001TD3JX013N 1TB            | 2         | 6.25%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 3.13%   |
| WDC WD3200AAJS-56B4A0 320GB             | 1         | 3.13%   |
| Unknown SB64G  64GB                     | 1         | 3.13%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 3.13%   |
| Toshiba HDWL120 2TB                     | 1         | 3.13%   |
| SP PC60 1TB                             | 1         | 3.13%   |
| Silicon Motion NVMe SSD Drive 256GB     | 1         | 3.13%   |
| Seagate ST9320423AS 320GB               | 1         | 3.13%   |
| Seagate Expansion 2TB                   | 1         | 3.13%   |
| Seagate BUP Slim BK 1TB                 | 1         | 3.13%   |
| SanDisk SD9SN8W256G1102 256GB SSD       | 1         | 3.13%   |
| Sandisk NVMe SSD Drive 500GB            | 1         | 3.13%   |
| Samsung SSD 980 PRO 500GB               | 1         | 3.13%   |
| Samsung SSD 970 EVO 500GB               | 1         | 3.13%   |
| Samsung SSD 860 EVO 500GB               | 1         | 3.13%   |
| Samsung SSD 850 EVO 500GB               | 1         | 3.13%   |
| Samsung SSD 650 120GB                   | 1         | 3.13%   |
| Samsung MZVLQ512HALU-00000 512GB        | 1         | 3.13%   |
| Samsung MZALQ512HALU-000L2 512GB        | 1         | 3.13%   |
| PNY CS900 240GB SSD                     | 1         | 3.13%   |
| LITEON L8H-256V2G-11 M.2 2280 256GB SSD | 1         | 3.13%   |
| KIOXIA-EXCERIA SATA SSD 480GB           | 1         | 3.13%   |
| Kingston SKC300S37A240G 240GB SSD       | 1         | 3.13%   |
| Kingston SHFS37A120G 120GB SSD          | 1         | 3.13%   |
| KingDian N400 240GB SSD                 | 1         | 3.13%   |
| Intel NVMe SSD Drive 512GB              | 1         | 3.13%   |
| Intel HBRPEKNX0101AHO 16GB              | 1         | 3.13%   |
| Intel HBRPEKNX0101AH 256GB              | 1         | 3.13%   |
| HGST HTS721010A9E630 1TB                | 1         | 3.13%   |
| China SATA SSD 240GB                    | 1         | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| WDC     | 2         | 2      | 25%     |
| Toshiba | 2         | 2      | 25%     |
| HGST    | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 27.27%  |
| Kingston            | 2         | 2      | 18.18%  |
| SanDisk             | 1         | 1      | 9.09%   |
| PNY                 | 1         | 1      | 9.09%   |
| LITEON              | 1         | 1      | 9.09%   |
| KIOXIA-EXCERIA      | 1         | 1      | 9.09%   |
| KingDian            | 1         | 1      | 9.09%   |
| China               | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 10        | 11     | 35.71%  |
| SSD     | 8         | 11     | 28.57%  |
| HDD     | 8         | 8      | 28.57%  |
| MMC     | 1         | 1      | 3.57%   |
| Unknown | 1         | 1      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12        | 17     | 46.15%  |
| NVMe | 10        | 11     | 38.46%  |
| SAS  | 3         | 3      | 11.54%  |
| MMC  | 1         | 1      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 14     | 68.75%  |
| 0.51-1.0   | 3         | 3      | 18.75%  |
| 1.01-2.0   | 2         | 2      | 12.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 6         | 31.58%  |
| 251-500    | 5         | 26.32%  |
| 1001-2000  | 3         | 15.79%  |
| 51-100     | 3         | 15.79%  |
| 21-50      | 1         | 5.26%   |
| 501-1000   | 1         | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 101-250   | 5         | 26.32%  |
| 51-100    | 4         | 21.05%  |
| 21-50     | 3         | 15.79%  |
| 1-20      | 3         | 15.79%  |
| 501-1000  | 2         | 10.53%  |
| 251-500   | 1         | 5.26%   |
| 1001-2000 | 1         | 5.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 13        | 16     | 56.52%  |
| Works    | 10        | 16     | 43.48%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 12        | 50%     |
| Samsung Electronics | 4         | 16.67%  |
| AMD                 | 4         | 16.67%  |
| SK Hynix            | 2         | 8.33%   |
| Silicon Motion      | 1         | 4.17%   |
| Sandisk             | 1         | 4.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Controller                                                  | 2         | 7.41%   |
| Samsung NVMe Controller                                                       | 2         | 7.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 7.41%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 2         | 7.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 3.7%    |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1         | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 3.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 3.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 1         | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 3.7%    |
| Intel SSD 660P Series                                                         | 1         | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 3.7%    |
| Intel Non-Volatile memory controller                                          | 1         | 3.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 3.7%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1         | 3.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 1         | 3.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 3.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 3.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 3.7%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                      | 1         | 3.7%    |
| AMD FCH SATA Controller [IDE mode]                                            | 1         | 3.7%    |
| AMD FCH IDE Controller                                                        | 1         | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 13        | 48.15%  |
| NVMe | 10        | 37.04%  |
| RAID | 2         | 7.41%   |
| IDE  | 2         | 7.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 13        | 68.42%  |
| AMD    | 6         | 31.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 10.53%  |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz           | 1         | 5.26%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 5.26%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 5.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 5.26%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 5.26%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 5.26%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 5.26%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 5.26%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 5.26%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 5.26%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 5.26%   |
| Intel Celeron CPU N2807 @ 1.58GHz             | 1         | 5.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 5.26%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1         | 5.26%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 5.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 5.26%   |
| AMD A4-4000 APU with Radeon HD Graphics       | 1         | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 4         | 21.05%  |
| Intel Core i5    | 4         | 21.05%  |
| AMD Ryzen 5      | 3         | 15.79%  |
| AMD Ryzen 9      | 2         | 10.53%  |
| Other            | 1         | 5.26%   |
| Intel Xeon       | 1         | 5.26%   |
| Intel Core m3    | 1         | 5.26%   |
| Intel Core 2 Duo | 1         | 5.26%   |
| Intel Celeron    | 1         | 5.26%   |
| AMD A4           | 1         | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 7         | 36.84%  |
| 2      | 6         | 31.58%  |
| 8      | 2         | 10.53%  |
| 6      | 2         | 10.53%  |
| 28     | 1         | 5.26%   |
| 1      | 1         | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 18        | 94.74%  |
| 2      | 1         | 5.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 16        | 84.21%  |
| 1      | 3         | 15.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 19        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 52.63%  |
| 0x906ea    | 1         | 5.26%   |
| 0x906e9    | 1         | 5.26%   |
| 0x806ec    | 1         | 5.26%   |
| 0x806eb    | 1         | 5.26%   |
| 0x806e9    | 1         | 5.26%   |
| 0x806c1    | 1         | 5.26%   |
| 0x306d4    | 1         | 5.26%   |
| 0x0a50000b | 1         | 5.26%   |
| 0x08608103 | 1         | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KabyLake   | 6         | 31.58%  |
| Zen 3      | 3         | 15.79%  |
| Broadwell  | 2         | 10.53%  |
| Zen+       | 1         | 5.26%   |
| Westmere   | 1         | 5.26%   |
| TigerLake  | 1         | 5.26%   |
| Silvermont | 1         | 5.26%   |
| Piledriver | 1         | 5.26%   |
| Penryn     | 1         | 5.26%   |
| Haswell    | 1         | 5.26%   |
| Unknown    | 1         | 5.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 12        | 46.15%  |
| Nvidia | 9         | 34.62%  |
| AMD    | 5         | 19.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 630                                                | 2         | 7.14%   |
| AMD Cezanne                                                          | 2         | 7.14%   |
| Nvidia GP108M [GeForce MX230]                                        | 1         | 3.57%   |
| Nvidia GP108M [GeForce MX150]                                        | 1         | 3.57%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 3.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 3.57%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                          | 1         | 3.57%   |
| Nvidia GK208B [GeForce GT 710]                                       | 1         | 3.57%   |
| Nvidia GK104 [GeForce GTX 680]                                       | 1         | 3.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M] | 1         | 3.57%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]             | 1         | 3.57%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 3.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 1         | 3.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)  | 1         | 3.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)    | 1         | 3.57%   |
| Intel HD Graphics 615                                                | 1         | 3.57%   |
| Intel HD Graphics 5500                                               | 1         | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 1         | 3.57%   |
| Intel Core Processor Integrated Graphics Controller                  | 1         | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 1         | 3.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 1         | 3.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display         | 1         | 3.57%   |
| AMD Trinity 2 [Radeon HD 7480D]                                      | 1         | 3.57%   |
| AMD Picasso                                                          | 1         | 3.57%   |
| AMD Lucienne                                                         | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 8         | 42.11%  |
| Intel + Nvidia | 4         | 21.05%  |
| AMD + Nvidia   | 3         | 15.79%  |
| 1 x AMD        | 2         | 10.53%  |
| 2 x Nvidia     | 1         | 5.26%   |
| 1 x Nvidia     | 1         | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 13        | 68.42%  |
| Proprietary | 6         | 31.58%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 68.42%  |
| 1.01-2.0   | 4         | 21.05%  |
| 0.01-0.5   | 2         | 10.53%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 3         | 14.29%  |
| AU Optronics        | 3         | 14.29%  |
| Sharp               | 2         | 9.52%   |
| Lenovo              | 2         | 9.52%   |
| Chimei Innolux      | 2         | 9.52%   |
| Acer                | 2         | 9.52%   |
| SKY                 | 1         | 4.76%   |
| Samsung Electronics | 1         | 4.76%   |
| PANDA               | 1         | 4.76%   |
| LG Electronics      | 1         | 4.76%   |
| LG Display          | 1         | 4.76%   |
| InfoVision          | 1         | 4.76%   |
| Dell                | 1         | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Acer XV340CK P ACR06F3 3440x1440 800x335mm 34.1-inch                 | 2         | 9.09%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                 | 1         | 4.55%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 4.55%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch | 1         | 4.55%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch              | 1         | 4.55%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 1         | 4.55%   |
| LG Electronics LCD Monitor LG ULTRAWIDE                              | 1         | 4.55%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 1         | 4.55%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch             | 1         | 4.55%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 4.55%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch         | 1         | 4.55%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                    | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 4.55%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                | 1         | 4.55%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                | 1         | 4.55%   |
| BOE LCD Monitor BOE05EC 1366x768 309x173mm 13.9-inch                 | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch       | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 11        | 50%     |
| 3440x1440         | 2         | 9.09%   |
| 2560x1440 (QHD)   | 2         | 9.09%   |
| 1280x800 (WXGA)   | 2         | 9.09%   |
| 3200x1800 (QHD+)  | 1         | 4.55%   |
| 2560x1080         | 1         | 4.55%   |
| 1920x1200 (WUXGA) | 1         | 4.55%   |
| 1366x768 (WXGA)   | 1         | 4.55%   |
| Unknown           | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 7         | 33.33%  |
| 13      | 6         | 28.57%  |
| 34      | 2         | 9.52%   |
| 40      | 1         | 4.76%   |
| 27      | 1         | 4.76%   |
| 24      | 1         | 4.76%   |
| 17      | 1         | 4.76%   |
| 12      | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 42.86%  |
| 201-300     | 5         | 23.81%  |
| 701-800     | 2         | 9.52%   |
| 501-600     | 2         | 9.52%   |
| 801-900     | 1         | 4.76%   |
| 351-400     | 1         | 4.76%   |
| Unknown     | 1         | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 15        | 71.43%  |
| 21/9    | 2         | 9.52%   |
| 16/10   | 2         | 9.52%   |
| 3/2     | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 33.33%  |
| 71-80          | 4         | 19.05%  |
| 81-90          | 2         | 9.52%   |
| 351-500        | 2         | 9.52%   |
| 61-70          | 1         | 4.76%   |
| 301-350        | 1         | 4.76%   |
| 201-250        | 1         | 4.76%   |
| 121-130        | 1         | 4.76%   |
| 501-1000       | 1         | 4.76%   |
| Unknown        | 1         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 9         | 42.86%  |
| 161-240       | 4         | 19.05%  |
| 101-120       | 3         | 14.29%  |
| 51-100        | 2         | 9.52%   |
| More than 240 | 1         | 4.76%   |
| 1-50          | 1         | 4.76%   |
| Unknown       | 1         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 17        | 89.47%  |
| 2     | 2         | 10.53%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 50%     |
| Intel                 | 7         | 29.17%  |
| MEDIATEK              | 2         | 8.33%   |
| Qualcomm Atheros      | 1         | 4.17%   |
| Broadcom Limited      | 1         | 4.17%   |
| Broadcom              | 1         | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 33.33%  |
| MEDIATEK Network controller                                       | 2         | 7.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.7%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 3.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 3.7%    |
| Intel Wireless 8265 / 8275                                        | 1         | 3.7%    |
| Intel Wireless 7265                                               | 1         | 3.7%    |
| Intel Wireless 3165                                               | 1         | 3.7%    |
| Intel Wi-Fi 6 AX201                                               | 1         | 3.7%    |
| Intel Wi-Fi 6 AX200                                               | 1         | 3.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 3.7%    |
| Intel Centrino Advanced-N 6200                                    | 1         | 3.7%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.7%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.7%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 3.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 7         | 46.67%  |
| Realtek Semiconductor | 4         | 26.67%  |
| MEDIATEK              | 2         | 13.33%  |
| Qualcomm Atheros      | 1         | 6.67%   |
| Broadcom Limited      | 1         | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| MEDIATEK Network controller                                | 2         | 13.33%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 6.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 6.67%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 6.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 6.67%   |
| Intel Wireless 8265 / 8275                                 | 1         | 6.67%   |
| Intel Wireless 7265                                        | 1         | 6.67%   |
| Intel Wireless 3165                                        | 1         | 6.67%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 6.67%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 6.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 6.67%   |
| Intel Centrino Advanced-N 6200                             | 1         | 6.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 10        | 83.33%  |
| Intel                 | 1         | 8.33%   |
| Broadcom              | 1         | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 75%     |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 8.33%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 8.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 55.56%  |
| Ethernet | 12        | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 12        | 60%     |
| Ethernet | 8         | 40%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 10        | 52.63%  |
| 2     | 9         | 47.37%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 16        | 84.21%  |
| Yes  | 3         | 15.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5         | 35.71%  |
| IMC Networks                    | 3         | 21.43%  |
| Realtek Semiconductor           | 2         | 14.29%  |
| Qualcomm Atheros Communications | 1         | 7.14%   |
| Lite-On Technology              | 1         | 7.14%   |
| Cambridge Silicon Radio         | 1         | 7.14%   |
| Broadcom                        | 1         | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 21.43%  |
| IMC Networks Wireless_Device                        | 2         | 14.29%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 7.14%   |
| Realtek Bluetooth Radio                             | 1         | 7.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 7.14%   |
| Lite-On Bluetooth Radio                             | 1         | 7.14%   |
| Intel Bluetooth Device                              | 1         | 7.14%   |
| Intel AX200 Bluetooth                               | 1         | 7.14%   |
| IMC Networks Bluetooth Radio                        | 1         | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 7.14%   |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 13        | 46.43%  |
| Nvidia                            | 5         | 17.86%  |
| AMD                               | 5         | 17.86%  |
| Elitegroup Computer Systems (ECS) | 2         | 7.14%   |
| XMOS                              | 1         | 3.57%   |
| Focusrite-Novation                | 1         | 3.57%   |
| Corsair                           | 1         | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 4         | 11.11%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 8.33%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 5.56%   |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                   | 2         | 5.56%   |
| XMOS HIFI DSD                                                              | 1         | 2.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 2.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 2.78%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.78%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.78%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.78%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 2.78%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.78%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.78%   |
| Focusrite-Novation Scarlett 18i20 3rd Gen                                  | 1         | 2.78%   |
| Corsair HS70 Pro Wireless Gaming Headset                                   | 1         | 2.78%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.78%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 28.57%  |
| SK Hynix            | 3         | 21.43%  |
| Micron Technology   | 3         | 21.43%  |
| Crucial             | 2         | 14.29%  |
| Unknown             | 1         | 7.14%   |
| Elpida              | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 14.29%  |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 7.14%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 7.14%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 7.14%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 7.14%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DIMM DDR4 2667MT/s              | 1         | 7.14%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s              | 1         | 7.14%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 7.14%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 7.14%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 1         | 7.14%   |
| Elpida RAM Module 4GB Row Of Chips LPDDR3 1867MT/s               | 1         | 7.14%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s       | 1         | 7.14%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s            | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 66.67%  |
| LPDDR3 | 2         | 16.67%  |
| LPDDR4 | 1         | 8.33%   |
| DDR3   | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 5         | 41.67%  |
| Row Of Chips | 3         | 25%     |
| DIMM         | 3         | 25%     |
| Chip         | 1         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 6         | 46.15%  |
| 16384 | 3         | 23.08%  |
| 4096  | 3         | 23.08%  |
| 2048  | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 4         | 30.77%  |
| 2667  | 3         | 23.08%  |
| 4267  | 1         | 7.69%   |
| 3733  | 1         | 7.69%   |
| 3400  | 1         | 7.69%   |
| 2133  | 1         | 7.69%   |
| 1867  | 1         | 7.69%   |
| 1600  | 1         | 7.69%   |

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


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| IMC Networks        | 3         | 21.43%  |
| Microdia            | 2         | 14.29%  |
| Chicony Electronics | 2         | 14.29%  |
| Syntek              | 1         | 7.14%   |
| Suyin               | 1         | 7.14%   |
| Samsung Electronics | 1         | 7.14%   |
| Quanta              | 1         | 7.14%   |
| Lenovo              | 1         | 7.14%   |
| Alcor Micro         | 1         | 7.14%   |
| Acer                | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam  | 2         | 14.29%  |
| Syntek Lenovo EasyCamera           | 1         | 7.14%   |
| Suyin Acer CrystalEye Webcam       | 1         | 7.14%   |
| Samsung Galaxy A5 (MTP)            | 1         | 7.14%   |
| Quanta USB2.0 HD UVC WebCam        | 1         | 7.14%   |
| Microdia Integrated_Webcam_HD      | 1         | 7.14%   |
| Microdia Integrated Webcam HD      | 1         | 7.14%   |
| Lenovo Integrated Webcam           | 1         | 7.14%   |
| IMC Networks USB2.0 VGA UVC WebCam | 1         | 7.14%   |
| Chicony USB 2.0 Camera             | 1         | 7.14%   |
| Chicony HP Wide Vision HD Camera   | 1         | 7.14%   |
| Alcor Micro USB 2.0 PC Camera      | 1         | 7.14%   |
| Acer Integrated Camera             | 1         | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Upek                       | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| Elan Microelectronics      | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 33.33%  |
| Elan ELAN:Fingerprint                                  | 1         | 33.33%  |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 12        | 63.16%  |
| 1     | 6         | 31.58%  |
| 2     | 1         | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 3         | 37.5%   |
| Net/wireless       | 2         | 25%     |
| Unassigned class   | 1         | 12.5%   |
| Graphics card      | 1         | 12.5%   |
| Bluetooth          | 1         | 12.5%   |

