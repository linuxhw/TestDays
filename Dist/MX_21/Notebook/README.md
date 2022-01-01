MX 21 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | [67cba6d321](https://linux-hardware.org/?probe=67cba6d321) | Dec 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Dell          | Latitude 3190               | [1a96380872](https://linux-hardware.org/?probe=1a96380872) | Dec 20, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Dell          | Latitude 3190               | [5321909b8c](https://linux-hardware.org/?probe=5321909b8c) | Dec 13, 2021 |
| Dell          | Latitude 3190               | [9c532278f1](https://linux-hardware.org/?probe=9c532278f1) | Dec 06, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Dell          | Latitude 3190               | [700dd2459e](https://linux-hardware.org/?probe=700dd2459e) | Nov 29, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Dell          | Latitude 3190               | [7f020f1d1f](https://linux-hardware.org/?probe=7f020f1d1f) | Nov 22, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Dell          | Latitude 3190               | [f24ac635ba](https://linux-hardware.org/?probe=f24ac635ba) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 5.10.0-9-amd64   | 12        | 66.67%  |
| 5.14.0-4mx-amd64 | 2         | 11.11%  |
| 5.10.0-8-amd64   | 2         | 11.11%  |
| 5.10.0-5mx-amd64 | 1         | 5.56%   |
| 5.10.0-10-amd64  | 1         | 5.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 16        | 88.89%  |
| 5.14.0  | 2         | 11.11%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 16        | 88.89%  |
| 5.14    | 2         | 11.11%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 18        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| XFCE   | 11        | 61.11%  |
| KDE5   | 5         | 27.78%  |
| GNOME  | 1         | 5.56%   |
| Budgie | 1         | 5.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 18        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 13        | 72.22%  |
| SDDM    | 5         | 27.78%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 9         | 50%     |
| it_IT   | 2         | 11.11%  |
| Unknown | 2         | 11.11%  |
| sk_SK   | 1         | 5.56%   |
| ru_RU   | 1         | 5.56%   |
| pt_BR   | 1         | 5.56%   |
| fr_FR   | 1         | 5.56%   |
| en_GB   | 1         | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 13        | 72.22%  |
| BIOS | 5         | 27.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 15        | 83.33%  |
| Overlay | 2         | 11.11%  |
| F2fs    | 1         | 5.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 14        | 77.78%  |
| MBR  | 4         | 22.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11        | 61.11%  |
| Yes       | 7         | 38.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10        | 55.56%  |
| Yes       | 8         | 44.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 5         | 27.78%  |
| Lenovo              | 4         | 22.22%  |
| Samsung Electronics | 2         | 11.11%  |
| Hewlett-Packard     | 2         | 11.11%  |
| Sony                | 1         | 5.56%   |
| Fujitsu Siemens     | 1         | 5.56%   |
| Dell                | 1         | 5.56%   |
| Chuwi               | 1         | 5.56%   |
| Apple               | 1         | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Sony VPCEC3S1E                            | 1         | 5.56%   |
| Samsung 350V5C/351V5C/3540VC/3440VC       | 1         | 5.56%   |
| Samsung 340XAA/350XAA/550XAA              | 1         | 5.56%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS      | 1         | 5.56%   |
| Lenovo ThinkBook 13s-IWL 20R9             | 1         | 5.56%   |
| Lenovo IdeaPad Y700-15ISK 80NV            | 1         | 5.56%   |
| Lenovo B590 20208                         | 1         | 5.56%   |
| HP EliteBook 850 G3                       | 1         | 5.56%   |
| HP Compaq Presario CQ60                   | 1         | 5.56%   |
| Fujitsu Siemens ESPRIMO Mobile D9500      | 1         | 5.56%   |
| Dell Latitude 3190                        | 1         | 5.56%   |
| Chuwi GemiBook Pro                        | 1         | 5.56%   |
| ASUS X550CC                               | 1         | 5.56%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 1         | 5.56%   |
| ASUS N53SN                                | 1         | 5.56%   |
| ASUS E402MA                               | 1         | 5.56%   |
| ASUS ASUS TUF Gaming A15 FA506QE_TUF506QE | 1         | 5.56%   |
| Apple MacBook3,1                          | 1         | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Sony VPCEC3S1E          | 1         | 5.56%   |
| Samsung 350V5C          | 1         | 5.56%   |
| Samsung 340XAA          | 1         | 5.56%   |
| Lenovo ThinkPad         | 1         | 5.56%   |
| Lenovo ThinkBook        | 1         | 5.56%   |
| Lenovo IdeaPad          | 1         | 5.56%   |
| Lenovo B590             | 1         | 5.56%   |
| HP EliteBook            | 1         | 5.56%   |
| HP Compaq               | 1         | 5.56%   |
| Fujitsu Siemens ESPRIMO | 1         | 5.56%   |
| Dell Latitude           | 1         | 5.56%   |
| Chuwi GemiBook          | 1         | 5.56%   |
| ASUS X550CC             | 1         | 5.56%   |
| ASUS TUF                | 1         | 5.56%   |
| ASUS N53SN              | 1         | 5.56%   |
| ASUS E402MA             | 1         | 5.56%   |
| ASUS ASUS               | 1         | 5.56%   |
| Apple MacBook3          | 1         | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 5         | 27.78%  |
| 2013    | 2         | 11.11%  |
| 2012    | 2         | 11.11%  |
| 2008    | 2         | 11.11%  |
| 2019    | 1         | 5.56%   |
| 2018    | 1         | 5.56%   |
| 2016    | 1         | 5.56%   |
| 2015    | 1         | 5.56%   |
| 2010    | 1         | 5.56%   |
| 2009    | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 18        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 18        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 50%     |
| 8.01-16.0  | 6         | 33.33%  |
| 3.01-4.0   | 2         | 11.11%  |
| 1.01-2.0   | 1         | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 7         | 36.84%  |
| 2.01-3.0  | 6         | 31.58%  |
| 4.01-8.0  | 2         | 10.53%  |
| 3.01-4.0  | 2         | 10.53%  |
| 8.01-16.0 | 1         | 5.26%   |
| 0.51-1.0  | 1         | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 12        | 66.67%  |
| 2      | 5         | 27.78%  |
| 0      | 1         | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11        | 61.11%  |
| Yes       | 7         | 38.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 83.33%  |
| No        | 3         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 88.89%  |
| No        | 2         | 11.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 77.78%  |
| No        | 4         | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| USA        | 5         | 27.78%  |
| Italy      | 2         | 11.11%  |
| Canada     | 2         | 11.11%  |
| Belgium    | 2         | 11.11%  |
| Slovakia   | 1         | 5.56%   |
| Serbia     | 1         | 5.56%   |
| Russia     | 1         | 5.56%   |
| Poland     | 1         | 5.56%   |
| France     | 1         | 5.56%   |
| Brazil     | 1         | 5.56%   |
| Azerbaijan | 1         | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Warsaw         | 1         | 5.56%   |
| Udine          | 1         | 5.56%   |
| St Petersburg  | 1         | 5.56%   |
| Saskatoon      | 1         | 5.56%   |
| Roseville      | 1         | 5.56%   |
| Powder Springs | 1         | 5.56%   |
| Portland       | 1         | 5.56%   |
| Ottawa         | 1         | 5.56%   |
| Osasco         | 1         | 5.56%   |
| Mussolente     | 1         | 5.56%   |
| Lannion        | 1         | 5.56%   |
| Glendale       | 1         | 5.56%   |
| Gilmer         | 1         | 5.56%   |
| Colfontaine    | 1         | 5.56%   |
| Brussels       | 1         | 5.56%   |
| Bratislava     | 1         | 5.56%   |
| Belgrade       | 1         | 5.56%   |
| Baku           | 1         | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 18.18%  |
| SK Hynix            | 2         | 2      | 9.09%   |
| Seagate             | 2         | 2      | 9.09%   |
| Samsung Electronics | 2         | 2      | 9.09%   |
| LITEON              | 2         | 2      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| Unknown             | 1         | 1      | 4.55%   |
| Toshiba             | 1         | 1      | 4.55%   |
| PNY                 | 1         | 1      | 4.55%   |
| Netac               | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| GeIL                | 1         | 1      | 4.55%   |
| Dogfish             | 1         | 1      | 4.55%   |
| Crucial             | 1         | 2      | 4.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 2         | 9.09%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 4.55%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 4.55%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 4.55%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 4.55%   |
| Unknown SDW32G  32GB                 | 1         | 4.55%   |
| Toshiba MQ01ABD075 752GB             | 1         | 4.55%   |
| SK Hynix HFM512GD3JX013N 512GB       | 1         | 4.55%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 4.55%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 4.55%   |
| Samsung SSD 970 EVO 1TB              | 1         | 4.55%   |
| Samsung HM500JI 500GB                | 1         | 4.55%   |
| PNY CS900 500GB SSD                  | 1         | 4.55%   |
| Netac SSD 256GB                      | 1         | 4.55%   |
| LITEON CV1-8B512-HP 512GB SSD        | 1         | 4.55%   |
| LITEON CV1-8B256 256GB SSD           | 1         | 4.55%   |
| Intel SSDSA2BW120G3H 120GB           | 1         | 4.55%   |
| GeIL R3_128GB SSD                    | 1         | 4.55%   |
| Dogfish SSD 128GB                    | 1         | 4.55%   |
| Crucial CT1000MX500SSD4 1TB          | 1         | 4.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 33.33%  |
| Seagate             | 2         | 2      | 33.33%  |
| Toshiba             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| LITEON   | 2         | 2      | 18.18%  |
| Kingston | 2         | 2      | 18.18%  |
| WDC      | 1         | 1      | 9.09%   |
| PNY      | 1         | 1      | 9.09%   |
| Netac    | 1         | 1      | 9.09%   |
| Intel    | 1         | 1      | 9.09%   |
| GeIL     | 1         | 1      | 9.09%   |
| Dogfish  | 1         | 1      | 9.09%   |
| Crucial  | 1         | 2      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 10        | 12     | 47.62%  |
| HDD  | 6         | 6      | 28.57%  |
| NVMe | 4         | 4      | 19.05%  |
| MMC  | 1         | 1      | 4.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 18     | 72.22%  |
| NVMe | 4         | 4      | 22.22%  |
| MMC  | 1         | 1      | 5.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 12     | 71.43%  |
| 0.51-1.0   | 4         | 6      | 28.57%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 6         | 33.33%  |
| 101-250    | 6         | 33.33%  |
| 1-20       | 2         | 11.11%  |
| 51-100     | 2         | 11.11%  |
| 21-50      | 1         | 5.56%   |
| 501-1000   | 1         | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 9         | 50%     |
| 51-100   | 3         | 16.67%  |
| 251-500  | 2         | 11.11%  |
| 21-50    | 2         | 11.11%  |
| 101-250  | 1         | 5.56%   |
| 501-1000 | 1         | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

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
| Works    | 17        | 21     | 89.47%  |
| Detected | 1         | 1      | 5.26%   |
| Malfunc  | 1         | 1      | 5.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 13        | 72.22%  |
| SK Hynix            | 2         | 11.11%  |
| Sandisk             | 1         | 5.56%   |
| Samsung Electronics | 1         | 5.56%   |
| Nvidia              | 1         | 5.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 14.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 9.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 9.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 9.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 9.52%   |
| SK Hynix Gold P31 SSD                                                        | 1         | 4.76%   |
| SK Hynix BC501 NVMe Solid State Drive                                        | 1         | 4.76%   |
| Sandisk Non-Volatile memory controller                                       | 1         | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 4.76%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                 | 1         | 4.76%   |
| Nvidia MCP78S [GeForce 8200] IDE                                             | 1         | 4.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 4.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 4.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 4.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 13        | 65%     |
| NVMe | 4         | 20%     |
| IDE  | 3         | 15%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 14        | 77.78%  |
| AMD    | 4         | 22.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 5.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 5.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 5.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 5.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 5.56%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 5.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 5.56%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 5.56%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 5.56%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 5.56%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 5.56%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 5.56%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 5.56%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 5.56%   |
| AMD Sempron SI-42                             | 1         | 5.56%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 5.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 5.56%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 6         | 33.33%  |
| AMD Ryzen 7          | 3         | 16.67%  |
| Intel Core i3        | 2         | 11.11%  |
| Intel Core 2 Duo     | 2         | 11.11%  |
| Intel Celeron        | 2         | 11.11%  |
| Intel Pentium Silver | 1         | 5.56%   |
| Intel Core i5        | 1         | 5.56%   |
| AMD Sempron          | 1         | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 8         | 44.44%  |
| 2      | 7         | 38.89%  |
| 8      | 2         | 11.11%  |
| 1      | 1         | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 66.67%  |
| 1      | 6         | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 18        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 2         | 11.11%  |
| 0x806eb    | 1         | 5.56%   |
| 0x806ea    | 1         | 5.56%   |
| 0x706a8    | 1         | 5.56%   |
| 0x706a1    | 1         | 5.56%   |
| 0x6fd      | 1         | 5.56%   |
| 0x6fb      | 1         | 5.56%   |
| 0x506e3    | 1         | 5.56%   |
| 0x406e3    | 1         | 5.56%   |
| 0x30678    | 1         | 5.56%   |
| 0x206a7    | 1         | 5.56%   |
| 0x20655    | 1         | 5.56%   |
| 0x0a50000c | 1         | 5.56%   |
| 0x08608103 | 1         | 5.56%   |
| 0x08108102 | 1         | 5.56%   |
| 0x02000057 | 1         | 5.56%   |
| Unknown    | 1         | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Skylake         | 2         | 11.11%  |
| SandyBridge     | 2         | 11.11%  |
| KabyLake        | 2         | 11.11%  |
| IvyBridge       | 2         | 11.11%  |
| Goldmont plus   | 2         | 11.11%  |
| Core            | 2         | 11.11%  |
| Zen+            | 1         | 5.56%   |
| Zen 3           | 1         | 5.56%   |
| Westmere        | 1         | 5.56%   |
| Silvermont      | 1         | 5.56%   |
| K8 & K10 hybrid | 1         | 5.56%   |
| Unknown         | 1         | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 52%     |
| Nvidia | 7         | 28%     |
| AMD    | 5         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 7.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 7.41%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 7.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 7.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 3.7%    |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 3.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 3.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 3.7%    |
| Nvidia GF108M [GeForce GT 550M]                                           | 1         | 3.7%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 3.7%    |
| Nvidia C77 [GeForce 8200M G]                                              | 1         | 3.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 3.7%    |
| Intel UHD Graphics 620                                                    | 1         | 3.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 3.7%    |
| Intel HD Graphics 530                                                     | 1         | 3.7%    |
| Intel GeminiLake [UHD Graphics 605]                                       | 1         | 3.7%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 3.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 3.7%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 3.7%    |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                  | 1         | 3.7%    |
| AMD Lucienne                                                              | 1         | 3.7%    |
| AMD Cezanne                                                               | 1         | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 8         | 44.44%  |
| Intel + Nvidia | 4         | 22.22%  |
| AMD + Nvidia   | 2         | 11.11%  |
| 1 x AMD        | 2         | 11.11%  |
| 1 x Nvidia     | 1         | 5.56%   |
| Intel + AMD    | 1         | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 14        | 77.78%  |
| Proprietary | 4         | 22.22%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 72.22%  |
| 0.51-1.0   | 2         | 11.11%  |
| 0.01-0.5   | 2         | 11.11%  |
| 3.01-4.0   | 1         | 5.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 4         | 18.18%  |
| AU Optronics            | 4         | 18.18%  |
| Samsung Electronics     | 3         | 13.64%  |
| LG Display              | 3         | 13.64%  |
| Ancor Communications    | 2         | 9.09%   |
| Sony                    | 1         | 4.55%   |
| Sharp                   | 1         | 4.55%   |
| PANDA                   | 1         | 4.55%   |
| Lenovo                  | 1         | 4.55%   |
| Chi Mei Optoelectronics | 1         | 4.55%   |
| Apple                   | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 4.55%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 4.55%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 1         | 4.55%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 4.55%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 4.55%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch             | 1         | 4.55%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 4.55%   |
| Lenovo LEN T2454pA LEN60C9 1920x1080 527x296mm 23.8-inch                 | 1         | 4.55%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch          | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 4.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 4.55%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch           | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 1         | 4.55%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 1         | 4.55%   |
| Ancor Communications VG248 ACI24E1 1680x1050 530x300mm 24.0-inch         | 1         | 4.55%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch    | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 8         | 40%     |
| 1366x768 (WXGA)  | 6         | 30%     |
| 1280x800 (WXGA)  | 2         | 10%     |
| 3840x2160 (4K)   | 1         | 5%      |
| 2160x1440        | 1         | 5%      |
| 1600x900 (HD+)   | 1         | 5%      |
| 1440x900 (WXGA+) | 1         | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 54.55%  |
| 24     | 2         | 9.09%   |
| 14     | 2         | 9.09%   |
| 13     | 2         | 9.09%   |
| 27     | 1         | 4.55%   |
| 19     | 1         | 4.55%   |
| 17     | 1         | 4.55%   |
| 11     | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 54.55%  |
| 201-300     | 4         | 18.18%  |
| 501-600     | 3         | 13.64%  |
| 351-400     | 2         | 9.09%   |
| 401-500     | 1         | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 15        | 75%     |
| 16/10 | 4         | 20%     |
| 3/2   | 1         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 54.55%  |
| 81-90          | 3         | 13.64%  |
| 71-80          | 1         | 4.55%   |
| 51-60          | 1         | 4.55%   |
| 301-350        | 1         | 4.55%   |
| 251-300        | 1         | 4.55%   |
| 201-250        | 1         | 4.55%   |
| 151-200        | 1         | 4.55%   |
| 121-130        | 1         | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 6         | 30%     |
| 51-100        | 6         | 30%     |
| 101-120       | 5         | 25%     |
| 161-240       | 2         | 10%     |
| More than 240 | 1         | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 12        | 66.67%  |
| 2     | 6         | 33.33%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 10        | 33.33%  |
| Intel                    | 8         | 26.67%  |
| Qualcomm Atheros         | 4         | 13.33%  |
| Marvell Technology Group | 3         | 10%     |
| TP-Link                  | 1         | 3.33%   |
| Ralink Technology        | 1         | 3.33%   |
| Nvidia                   | 1         | 3.33%   |
| MEDIATEK                 | 1         | 3.33%   |
| Broadcom                 | 1         | 3.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 8         | 23.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 5.88%   |
| Intel Wireless 8260                                                            | 2         | 5.88%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 5.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 2.94%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 2.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 2.94%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 2.94%   |
| MEDIATEK Network controller                                                    | 1         | 2.94%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.94%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 2.94%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 2.94%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 2.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 2.94%   |
| Intel Ethernet Connection I219-V                                               | 1         | 2.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 2.94%   |
| Broadcom BCM4321 802.11a/b/g/n                                                 | 1         | 2.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 8         | 44.44%  |
| Qualcomm Atheros      | 4         | 22.22%  |
| Realtek Semiconductor | 2         | 11.11%  |
| TP-Link               | 1         | 5.56%   |
| Ralink Technology     | 1         | 5.56%   |
| MEDIATEK              | 1         | 5.56%   |
| Broadcom              | 1         | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 2         | 11.11%  |
| Intel Wi-Fi 6 AX200                                                     | 2         | 11.11%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 5.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 5.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 5.56%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 5.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 5.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 5.56%   |
| MEDIATEK Network controller                                             | 1         | 5.56%   |
| Intel Wireless 8265 / 8275                                              | 1         | 5.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 5.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 5.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 5.56%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 10        | 66.67%  |
| Marvell Technology Group | 3         | 20%     |
| Nvidia                   | 1         | 6.67%   |
| Intel                    | 1         | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 8         | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 12.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 6.25%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 6.25%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 6.25%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 6.25%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 6.25%   |
| Intel Ethernet Connection I219-V                                               | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 51.61%  |
| Ethernet | 15        | 48.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 14        | 77.78%  |
| Ethernet | 4         | 22.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 13        | 72.22%  |
| 1     | 5         | 27.78%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 16        | 88.89%  |
| Yes  | 2         | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 42.86%  |
| Qualcomm Atheros Communications | 2         | 14.29%  |
| IMC Networks                    | 2         | 14.29%  |
| Realtek Semiconductor           | 1         | 7.14%   |
| Foxconn / Hon Hai               | 1         | 7.14%   |
| Cambridge Silicon Radio         | 1         | 7.14%   |
| Apple                           | 1         | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 4         | 28.57%  |
| Intel AX200 Bluetooth                                                               | 2         | 14.29%  |
| Realtek Bluetooth Radio                                                             | 1         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 7.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 7.14%   |
| IMC Networks Wireless_Device                                                        | 1         | 7.14%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 7.14%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 7.14%   |
| Apple Bluetooth HCI                                                                 | 1         | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 14        | 60.87%  |
| Nvidia      | 4         | 17.39%  |
| AMD         | 4         | 17.39%  |
| Plantronics | 1         | 4.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 12%     |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3         | 12%     |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 8%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 8%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 8%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 8%      |
| Plantronics BT600                                                          | 1         | 4%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 4%      |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 4%      |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 4%      |
| Nvidia Audio device                                                        | 1         | 4%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 4%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 4%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 4%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 4%      |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 6         | 28.57%  |
| Samsung Electronics | 6         | 28.57%  |
| Unknown             | 5         | 23.81%  |
| Unknown (ABCD)      | 1         | 4.76%   |
| Smart               | 1         | 4.76%   |
| PNY                 | 1         | 4.76%   |
| Kingston            | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 8.33%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 4.17%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 4.17%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 4.17%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 4.17%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 4.17%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 4.17%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 4.17%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 4.17%   |
| SK Hynix RAM HMT351S6EFR8A 4GB SODIMM DDR3 1600MT/s              | 1         | 4.17%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 4.17%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 4.17%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 4.17%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 4.17%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 4.17%   |
| SK Hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 1         | 4.17%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 4.17%   |
| Samsung RAM Module 4GB SODIMM DDR2 667MT/s                       | 1         | 4.17%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 4.17%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 4.17%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| PNY RAM Module 8GB SODIMM DDR3 1333MT/s                          | 1         | 4.17%   |
| Kingston RAM HP594908-HR1-ELD 2GB SODIMM DDR3 1333MT/s           | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 42.11%  |
| DDR3   | 6         | 31.58%  |
| DDR2   | 2         | 10.53%  |
| SDRAM  | 1         | 5.26%   |
| LPDDR4 | 1         | 5.26%   |
| DRAM   | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 18        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 8         | 38.1%   |
| 4096 | 6         | 28.57%  |
| 2048 | 6         | 28.57%  |
| 1024 | 1         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2400    | 3         | 15.79%  |
| 1333    | 3         | 15.79%  |
| 667     | 3         | 15.79%  |
| 3200    | 2         | 10.53%  |
| 2667    | 2         | 10.53%  |
| 2133    | 2         | 10.53%  |
| 1600    | 2         | 10.53%  |
| 4199    | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 100%    |

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


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 4         | 26.67%  |
| Microdia                    | 3         | 20%     |
| Realtek Semiconductor       | 2         | 13.33%  |
| Z-Star Microelectronics     | 1         | 6.67%   |
| Silicon Motion              | 1         | 6.67%   |
| Luxvisions Innotech Limited | 1         | 6.67%   |
| Lite-On Technology          | 1         | 6.67%   |
| IMC Networks                | 1         | 6.67%   |
| Goodong Industry            | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Z-Star Venus USB2.0 Camera                    | 1         | 6.67%   |
| Silicon Motion Web Camera                     | 1         | 6.67%   |
| Realtek USB Camera                            | 1         | 6.67%   |
| Realtek Integrated Webcam                     | 1         | 6.67%   |
| Microdia Webcam Vitade AF                     | 1         | 6.67%   |
| Microdia WebCam SC-13HDL12639P                | 1         | 6.67%   |
| Microdia Webcam                               | 1         | 6.67%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 6.67%   |
| Lite-On HP HD Camera                          | 1         | 6.67%   |
| IMC Networks USB2.0 HD UVC WebCam             | 1         | 6.67%   |
| Goodong Industry USB2.0 HD UVC WebCam         | 1         | 6.67%   |
| Chicony USB2.0 HD UVC WebCam                  | 1         | 6.67%   |
| Chicony USB2.0 2.0M UVC WebCam                | 1         | 6.67%   |
| Chicony Lenovo EasyCamera                     | 1         | 6.67%   |
| Chicony Integrated Camera                     | 1         | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 66.67%  |
| Validity Sensors           | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device        | 2         | 66.67%  |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 33.33%  |

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
| 0     | 12        | 66.67%  |
| 1     | 5         | 27.78%  |
| 2     | 1         | 5.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 50%     |
| Fingerprint reader | 3         | 50%     |

