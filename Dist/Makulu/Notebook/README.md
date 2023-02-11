Makulu - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Makulu.

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

Total: 26

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Dell    | Latitude E64406342Q0286/    | [e044c94514](https://linux-hardware.org/?probe=e044c94514) | Dec 26, 2022 |
| Dell    | Latitude E64406342Q0286/    | [41b2b27a91](https://linux-hardware.org/?probe=41b2b27a91) | Dec 16, 2022 |
| Dell    | Latitude E64406342Q0286/    | [e8b2c9218f](https://linux-hardware.org/?probe=e8b2c9218f) | Dec 15, 2022 |
| Dell    | Inspiron 5565               | [a583bbdc35](https://linux-hardware.org/?probe=a583bbdc35) | May 19, 2022 |
| Dell    | Latitude 3540               | [6fb057646a](https://linux-hardware.org/?probe=6fb057646a) | Feb 25, 2022 |
| Samsung | R580                        | [b796f42cc3](https://linux-hardware.org/?probe=b796f42cc3) | Jan 31, 2022 |
| HP      | Pavilion Laptop 15z-cw10... | [c014435339](https://linux-hardware.org/?probe=c014435339) | Dec 29, 2021 |
| HP      | Pavilion Laptop 15z-cw10... | [97cfd9951b](https://linux-hardware.org/?probe=97cfd9951b) | Dec 29, 2021 |
| Lenovo  | V14-IIL 82C4                | [cb48d8f436](https://linux-hardware.org/?probe=cb48d8f436) | Dec 28, 2021 |
| HUAWEI  | KPL-W0X                     | [0551e72ef6](https://linux-hardware.org/?probe=0551e72ef6) | Dec 27, 2021 |
| HUAWEI  | KPL-W0X                     | [64d4de98ff](https://linux-hardware.org/?probe=64d4de98ff) | Dec 27, 2021 |
| Lenovo  | V14-IIL 82C4                | [e3873f9847](https://linux-hardware.org/?probe=e3873f9847) | Dec 23, 2021 |
| ASUSTek | N55SL                       | [11ed4def95](https://linux-hardware.org/?probe=11ed4def95) | Oct 24, 2021 |
| Lenovo  | IdeaPad Y530                | [6ca5521110](https://linux-hardware.org/?probe=6ca5521110) | Sep 24, 2021 |
| Dell    | Inspiron 3521               | [9787940762](https://linux-hardware.org/?probe=9787940762) | Aug 29, 2021 |
| Apple   | MacBookAir6,2               | [66f7c33d00](https://linux-hardware.org/?probe=66f7c33d00) | Jun 08, 2021 |
| Apple   | MacBookAir6,2               | [1ce8c5e2c7](https://linux-hardware.org/?probe=1ce8c5e2c7) | Jun 03, 2021 |
| HP      | ENVY Notebook               | [61cb15af98](https://linux-hardware.org/?probe=61cb15af98) | Apr 28, 2021 |
| ASUSTek | K55VD                       | [b9086bf814](https://linux-hardware.org/?probe=b9086bf814) | Apr 14, 2021 |
| ASUSTek | K55VD                       | [10987a7dec](https://linux-hardware.org/?probe=10987a7dec) | Apr 13, 2021 |
| HP      | Compaq 15                   | [455bc50dc9](https://linux-hardware.org/?probe=455bc50dc9) | Mar 15, 2021 |
| HP      | ENVY Notebook               | [f71898211e](https://linux-hardware.org/?probe=f71898211e) | Feb 25, 2021 |
| Lenovo  | ThinkPad T420 4236W1W       | [3c3ff4f10e](https://linux-hardware.org/?probe=3c3ff4f10e) | Dec 02, 2020 |
| Lenovo  | ThinkPad T420 4236W1W       | [73279e52cd](https://linux-hardware.org/?probe=73279e52cd) | Oct 01, 2020 |
| HP      | Pavilion 17                 | [a6aa670ab4](https://linux-hardware.org/?probe=a6aa670ab4) | Sep 02, 2020 |
| HP      | Pavilion 17                 | [03171f4dbe](https://linux-hardware.org/?probe=03171f4dbe) | Aug 30, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Makulu 2020              | 10        | 62.5%   |
| Makulu Build: 2021.12.15 | 4         | 25%     |
| Makulu Buildvar          | 1         | 6.25%   |
| Makulu Build: 2022.01.06 | 1         | 6.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Makulu | 16        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.11.0-41-generic      | 3         | 18.75%  |
| 5.11.0-43-generic      | 2         | 12.5%   |
| 5.10.0-8-amd64         | 2         | 12.5%   |
| 5.8.0-50-generic       | 1         | 6.25%   |
| 5.8.0-49-generic       | 1         | 6.25%   |
| 5.8.0-44-generic       | 1         | 6.25%   |
| 5.8.0-38-generic       | 1         | 6.25%   |
| 5.4.0-48-generic       | 1         | 6.25%   |
| 5.4.0-42-generic       | 1         | 6.25%   |
| 5.15.10-051510-generic | 1         | 6.25%   |
| 5.15.0-53-generic      | 1         | 6.25%   |
| 5.11.0-36-generic      | 1         | 6.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 6         | 37.5%   |
| 5.8.0   | 4         | 25%     |
| 5.4.0   | 2         | 12.5%   |
| 5.10.0  | 2         | 12.5%   |
| 5.15.10 | 1         | 6.25%   |
| 5.15.0  | 1         | 6.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 6         | 37.5%   |
| 5.8     | 4         | 25%     |
| 5.4     | 2         | 12.5%   |
| 5.15    | 2         | 12.5%   |
| 5.10    | 2         | 12.5%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 16        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 12        | 75%     |
| X-Cinnamon | 4         | 25%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 16        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 87.5%   |
| LightDM | 2         | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 6         | 35.29%  |
| en_CA | 3         | 17.65%  |
| de_DE | 3         | 17.65%  |
| it_IT | 2         | 11.76%  |
| pl_PL | 1         | 5.88%   |
| nl_NL | 1         | 5.88%   |
| en_GB | 1         | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 9         | 52.94%  |
| EFI  | 8         | 47.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 14        | 87.5%   |
| Tmpfs | 1         | 6.25%   |
| Btrfs | 1         | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 93.75%  |
| Yes       | 1         | 6.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 25%     |
| Dell                | 4         | 25%     |
| Lenovo              | 3         | 18.75%  |
| ASUSTek Computer    | 2         | 12.5%   |
| Samsung Electronics | 1         | 6.25%   |
| HUAWEI              | 1         | 6.25%   |
| Apple               | 1         | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Samsung R580                  | 1         | 6.25%   |
| Lenovo V14-IIL 82C4           | 1         | 6.25%   |
| Lenovo ThinkPad T420 4236W1W  | 1         | 6.25%   |
| Lenovo IdeaPad Y530           | 1         | 6.25%   |
| HUAWEI KPL-W0X                | 1         | 6.25%   |
| HP Pavilion Laptop 15z-cw100  | 1         | 6.25%   |
| HP Pavilion 17                | 1         | 6.25%   |
| HP ENVY Notebook              | 1         | 6.25%   |
| HP Compaq 15                  | 1         | 6.25%   |
| Dell Latitude E64406342Q0286/ | 1         | 6.25%   |
| Dell Latitude 3540            | 1         | 6.25%   |
| Dell Inspiron 5565            | 1         | 6.25%   |
| Dell Inspiron 3521            | 1         | 6.25%   |
| ASUS N55SL                    | 1         | 6.25%   |
| ASUS K55VD                    | 1         | 6.25%   |
| Apple MacBookAir6,2           | 1         | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| HP Pavilion       | 2         | 12.5%   |
| Dell Latitude     | 2         | 12.5%   |
| Dell Inspiron     | 2         | 12.5%   |
| Samsung R580      | 1         | 6.25%   |
| Lenovo V14-IIL    | 1         | 6.25%   |
| Lenovo ThinkPad   | 1         | 6.25%   |
| Lenovo IdeaPad    | 1         | 6.25%   |
| HUAWEI KPL-W0X    | 1         | 6.25%   |
| HP ENVY           | 1         | 6.25%   |
| HP Compaq         | 1         | 6.25%   |
| ASUS N55SL        | 1         | 6.25%   |
| ASUS K55VD        | 1         | 6.25%   |
| Apple MacBookAir6 | 1         | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 4         | 25%     |
| 2019 | 2         | 12.5%   |
| 2012 | 2         | 12.5%   |
| 2011 | 2         | 12.5%   |
| 2018 | 1         | 6.25%   |
| 2016 | 1         | 6.25%   |
| 2015 | 1         | 6.25%   |
| 2014 | 1         | 6.25%   |
| 2009 | 1         | 6.25%   |
| 2008 | 1         | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 16        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 16        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 16        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 41.18%  |
| 3.01-4.0   | 6         | 35.29%  |
| 8.01-16.0  | 3         | 17.65%  |
| 16.01-24.0 | 1         | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 8         | 47.06%  |
| 2.01-3.0 | 6         | 35.29%  |
| 3.01-4.0 | 2         | 11.76%  |
| 4.01-8.0 | 1         | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 82.35%  |
| 3      | 2         | 11.76%  |
| 2      | 1         | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 62.5%   |
| No        | 6         | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 75%     |
| No        | 4         | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 75%     |
| No        | 4         | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 3         | 18.75%  |
| Germany     | 3         | 18.75%  |
| UK          | 2         | 12.5%   |
| Italy       | 2         | 12.5%   |
| Canada      | 2         | 12.5%   |
| Uganda      | 1         | 6.25%   |
| Poland      | 1         | 6.25%   |
| Netherlands | 1         | 6.25%   |
| Australia   | 1         | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Steinfeld      | 1         | 5.56%   |
| Saint John     | 1         | 5.56%   |
| Oschersleben   | 1         | 5.56%   |
| Munich         | 1         | 5.56%   |
| Millers Creek  | 1         | 5.56%   |
| Melbourne      | 1         | 5.56%   |
| Manchester     | 1         | 5.56%   |
| Lodz           | 1         | 5.56%   |
| Kampala        | 1         | 5.56%   |
| Jamestown      | 1         | 5.56%   |
| Imperia        | 1         | 5.56%   |
| Hillegom       | 1         | 5.56%   |
| Freisbach      | 1         | 5.56%   |
| Etobicoke      | 1         | 5.56%   |
| Dallas         | 1         | 5.56%   |
| Brunswick West | 1         | 5.56%   |
| Brugherio      | 1         | 5.56%   |
| Ballygowan     | 1         | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 19.05%  |
| Toshiba             | 3         | 3      | 14.29%  |
| SanDisk             | 3         | 3      | 14.29%  |
| Samsung Electronics | 3         | 5      | 14.29%  |
| Unknown             | 1         | 1      | 4.76%   |
| Transcend           | 1         | 1      | 4.76%   |
| LITEON              | 1         | 2      | 4.76%   |
| KIOXIA              | 1         | 1      | 4.76%   |
| JMicron Technology  | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 2         | 9.09%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 9.09%   |
| Unknown SD/MMC/MS PRO 2GB            | 1         | 4.55%   |
| Transcend TS64GMSA230S 64GB SSD      | 1         | 4.55%   |
| Toshiba MQ01ABF050M 500GB            | 1         | 4.55%   |
| Seagate ST9320325AS 320GB            | 1         | 4.55%   |
| Seagate Expansion Desk 6TB           | 1         | 4.55%   |
| SanDisk SSD U110 128GB               | 1         | 4.55%   |
| SanDisk SSD PLUS 1000GB              | 1         | 4.55%   |
| SanDisk NVMe SSD Drive 512GB         | 1         | 4.55%   |
| Samsung NVMe SSD Drive 1TB           | 1         | 4.55%   |
| Samsung NVMe SSD Drive 1024GB        | 1         | 4.55%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD | 1         | 4.55%   |
| Samsung HM500JI 500GB                | 1         | 4.55%   |
| LITEON L8H-256V2G-HP 256GB SSD       | 1         | 4.55%   |
| KIOXIA NVMe SSD Drive 256GB          | 1         | 4.55%   |
| JMicron Tech 250GB                   | 1         | 4.55%   |
| Hitachi HTS545025B9A300 250GB        | 1         | 4.55%   |
| HGST HTS721010A9E630 1TB             | 1         | 4.55%   |
| Apple SSD SM0256F 256GB              | 1         | 4.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 36.36%  |
| Toshiba             | 3         | 3      | 27.27%  |
| Unknown             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |
| HGST                | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 33.33%  |
| Transcend           | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 2      | 16.67%  |
| LITEON              | 1         | 2      | 16.67%  |
| Apple               | 1         | 1      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 10        | 12     | 52.63%  |
| SSD     | 5         | 8      | 26.32%  |
| NVMe    | 3         | 4      | 15.79%  |
| Unknown | 1         | 1      | 5.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 14        | 18     | 73.68%  |
| NVMe | 3         | 4      | 15.79%  |
| SAS  | 2         | 3      | 10.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 15     | 66.67%  |
| 0.51-1.0   | 4         | 4      | 26.67%  |
| 4.01-10.0  | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 7         | 41.18%  |
| 251-500        | 4         | 23.53%  |
| 501-1000       | 2         | 11.76%  |
| More than 3000 | 1         | 5.88%   |
| 21-50          | 1         | 5.88%   |
| 1-20           | 1         | 5.88%   |
| 51-100         | 1         | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 7         | 36.84%  |
| 1-20           | 7         | 36.84%  |
| 51-100         | 2         | 10.53%  |
| More than 3000 | 1         | 5.26%   |
| 251-500        | 1         | 5.26%   |
| 101-250        | 1         | 5.26%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 16        | 25     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 10        | 55.56%  |
| AMD                 | 4         | 22.22%  |
| Samsung Electronics | 2         | 11.11%  |
| SanDisk             | 1         | 5.56%   |
| KIOXIA              | 1         | 5.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 22.22%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 11.11%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 11.11%  |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 5.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 5.56%   |
| Samsung Apple PCIe SSD                                                         | 1         | 5.56%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 5.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 5.56%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 5.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 5.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 5.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 5.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 5.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 15        | 83.33%  |
| NVMe | 3         | 16.67%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 11        | 68.75%  |
| AMD    | 5         | 31.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 6.25%   |
| Intel Core i7-4600M CPU @ 2.90GHz               | 1         | 6.25%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 6.25%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 6.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 6.25%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 1         | 6.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 6.25%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 6.25%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 1         | 6.25%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1         | 6.25%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 1         | 6.25%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 6.25%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 1         | 6.25%   |
| AMD E1-2100 APU with Radeon HD Graphics         | 1         | 6.25%   |
| AMD A4-5000 APU with Radeon HD Graphics         | 1         | 6.25%   |
| AMD A12-9700P RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 4         | 25%     |
| Intel Core i7           | 3         | 18.75%  |
| Intel Core i3           | 3         | 18.75%  |
| Intel Pentium Dual-Core | 1         | 6.25%   |
| AMD Ryzen 7             | 1         | 6.25%   |
| AMD Ryzen 5             | 1         | 6.25%   |
| AMD E1                  | 1         | 6.25%   |
| AMD A4                  | 1         | 6.25%   |
| AMD A12                 | 1         | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 11        | 68.75%  |
| 4      | 5         | 31.25%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 81.25%  |
| 1      | 3         | 18.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 16        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 22.22%  |
| 0x40651    | 2         | 11.11%  |
| 0x206a7    | 2         | 11.11%  |
| 0x406e3    | 1         | 5.56%   |
| 0x306c3    | 1         | 5.56%   |
| 0x306a9    | 1         | 5.56%   |
| 0x20652    | 1         | 5.56%   |
| 0x1067a    | 1         | 5.56%   |
| 0x08108102 | 1         | 5.56%   |
| 0x08101007 | 1         | 5.56%   |
| 0x07000110 | 1         | 5.56%   |
| 0x0700010f | 1         | 5.56%   |
| 0x06006118 | 1         | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Haswell     | 3         | 18.75%  |
| SandyBridge | 2         | 12.5%   |
| Jaguar      | 2         | 12.5%   |
| IvyBridge   | 2         | 12.5%   |
| Zen+        | 1         | 6.25%   |
| Zen         | 1         | 6.25%   |
| Westmere    | 1         | 6.25%   |
| Skylake     | 1         | 6.25%   |
| Penryn      | 1         | 6.25%   |
| IceLake     | 1         | 6.25%   |
| Excavator   | 1         | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 9         | 50%     |
| AMD    | 5         | 27.78%  |
| Nvidia | 4         | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 11.11%  |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 11.11%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 11.11%  |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 5.56%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 5.56%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                      | 1         | 5.56%   |
| Nvidia G96CM [GeForce 9600M GS]                                           | 1         | 5.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 5.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 5.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 5.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 1         | 5.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 5.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 5.56%   |
| AMD Kabini [Radeon HD 8330]                                               | 1         | 5.56%   |
| AMD Kabini [Radeon HD 8210]                                               | 1         | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 7         | 43.75%  |
| 1 x AMD        | 5         | 31.25%  |
| 1 x Nvidia     | 2         | 12.5%   |
| Intel + Nvidia | 2         | 12.5%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 16        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 43.75%  |
| 0.01-0.5   | 4         | 25%     |
| 1.01-2.0   | 3         | 18.75%  |
| 0.51-1.0   | 2         | 12.5%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 5         | 31.25%  |
| Samsung Electronics     | 4         | 25%     |
| Chimei Innolux          | 2         | 12.5%   |
| BOE                     | 2         | 12.5%   |
| Chi Mei Optoelectronics | 1         | 6.25%   |
| AU Optronics            | 1         | 6.25%   |
| Apple                   | 1         | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 6.25%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch     | 1         | 6.25%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch    | 1         | 6.25%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 6.25%   |
| LG Display LCD Monitor LGD062B 1920x1080 344x194mm 15.5-inch             | 1         | 6.25%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch             | 1         | 6.25%   |
| LG Display LCD Monitor LGD03E5 1366x768 309x174mm 14.0-inch              | 1         | 6.25%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 1         | 6.25%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 6.25%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 6.25%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 1         | 6.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch | 1         | 6.25%   |
| BOE LCD Monitor BOE083C 1920x1080 309x173mm 13.9-inch                    | 1         | 6.25%   |
| BOE LCD Monitor BOE07D3 1920x1080 309x174mm 14.0-inch                    | 1         | 6.25%   |
| AU Optronics LCD Monitor AUO9274 1280x800 331x207mm 15.4-inch            | 1         | 6.25%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 1         | 6.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 6         | 37.5%   |
| 1366x768 (WXGA)  | 6         | 37.5%   |
| 3840x2400        | 1         | 6.25%   |
| 1600x900 (HD+)   | 1         | 6.25%   |
| 1440x900 (WXGA+) | 1         | 6.25%   |
| 1280x800 (WXGA)  | 1         | 6.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 62.5%   |
| 14     | 3         | 18.75%  |
| 13     | 2         | 12.5%   |
| 17     | 1         | 6.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 75%     |
| 351-400     | 3         | 18.75%  |
| 201-300     | 1         | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 13        | 81.25%  |
| 16/10 | 3         | 18.75%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 62.5%   |
| 81-90          | 5         | 31.25%  |
| 121-130        | 1         | 6.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 5         | 31.25%  |
| 101-120       | 5         | 31.25%  |
| 51-100        | 5         | 31.25%  |
| More than 240 | 1         | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 16        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 7         | 25.93%  |
| Qualcomm Atheros                | 6         | 22.22%  |
| Intel                           | 6         | 22.22%  |
| Broadcom Limited                | 2         | 7.41%   |
| Broadcom                        | 2         | 7.41%   |
| Ralink Technology               | 1         | 3.7%    |
| Qualcomm Atheros Communications | 1         | 3.7%    |
| Marvell Technology Group        | 1         | 3.7%    |
| D-Link                          | 1         | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Notebooks | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 4         | 12.5%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 3         | 9.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2         | 6.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 3.13%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 3.13%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1         | 3.13%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 3.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1         | 3.13%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB]       | 1         | 3.13%   |
| Intel Wireless-AC 9260                                                               | 1         | 3.13%   |
| Intel Wireless 7265                                                                  | 1         | 3.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 3.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 3.13%   |
| Intel Ethernet Connection I217-LM                                                    | 1         | 3.13%   |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 3.13%   |
| Intel Centrino Advanced-N 6235                                                       | 1         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 1         | 3.13%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 3.13%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                          | 1         | 3.13%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                           | 1         | 3.13%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 1         | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 3.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 31.58%  |
| Qualcomm Atheros                | 5         | 26.32%  |
| Realtek Semiconductor           | 2         | 10.53%  |
| Broadcom                        | 2         | 10.53%  |
| Ralink Technology               | 1         | 5.26%   |
| Qualcomm Atheros Communications | 1         | 5.26%   |
| D-Link                          | 1         | 5.26%   |
| Broadcom Limited                | 1         | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Notebooks | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2         | 10%     |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 5%      |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 5%      |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 5%      |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1         | 5%      |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 5%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 5%      |
| Intel Wireless-AC 9260                                                               | 1         | 5%      |
| Intel Wireless 7265                                                                  | 1         | 5%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 5%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 5%      |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 5%      |
| Intel Centrino Advanced-N 6235                                                       | 1         | 5%      |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 5%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                           | 1         | 5%      |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 1         | 5%      |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 7         | 58.33%  |
| Intel                    | 2         | 16.67%  |
| Qualcomm Atheros         | 1         | 8.33%   |
| Marvell Technology Group | 1         | 8.33%   |
| Broadcom Limited         | 1         | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 33.33%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3         | 25%     |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 8.33%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 8.33%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 8.33%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 57.14%  |
| Ethernet | 12        | 42.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 12        | 75%     |
| Ethernet | 4         | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 12        | 75%     |
| 1     | 4         | 25%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 11        | 68.75%  |
| Yes  | 5         | 31.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Broadcom                        | 4         | 33.33%  |
| Intel                           | 3         | 25%     |
| Qualcomm Atheros Communications | 2         | 16.67%  |
| Realtek Semiconductor           | 1         | 8.33%   |
| IMC Networks                    | 1         | 8.33%   |
| Apple                           | 1         | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 8.33%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 8.33%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 8.33%   |
| Intel Bluetooth wireless interface                | 1         | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 1         | 8.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 8.33%   |
| Broadcom Bluetooth 2.1 Device                     | 1         | 8.33%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 8.33%   |
| Broadcom BCM2046 Bluetooth Device                 | 1         | 8.33%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 8.33%   |
| Apple Bluetooth USB Host Controller               | 1         | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 11        | 61.11%  |
| AMD    | 5         | 27.78%  |
| Nvidia | 2         | 11.11%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Kabini HDMI/DP Audio                                                   | 3         | 12%     |
| Intel 8 Series HD Audio Controller                                         | 2         | 8%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 8%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 8%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 8%      |
| AMD FCH Azalia Controller                                                  | 2         | 8%      |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 8%      |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 4%      |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 4%      |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 4%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 4%      |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 4%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 4%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

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
| Suyin                                  | 3         | 23.08%  |
| Chicony Electronics                    | 3         | 23.08%  |
| Microdia                               | 2         | 15.38%  |
| Cheng Uei Precision Industry (Foxlink) | 2         | 15.38%  |
| Z-Star Microelectronics                | 1         | 7.69%   |
| Realtek Semiconductor                  | 1         | 7.69%   |
| Lite-On Technology                     | 1         | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 15.38%  |
| Z-Star WebCam SCB-1900N                                 | 1         | 7.69%   |
| Suyin UVC HD Webcam                                     | 1         | 7.69%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 1         | 7.69%   |
| Suyin HP Truevision HD                                  | 1         | 7.69%   |
| Realtek Integrated Webcam HD                            | 1         | 7.69%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 1         | 7.69%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 7.69%   |
| Lite-On HP Wide Vision HD Camera                        | 1         | 7.69%   |
| Chicony UVC 1.00 device HD UVC WebCam                   | 1         | 7.69%   |
| Chicony Lenovo EasyCamera                               | 1         | 7.69%   |
| Chicony Integrated Camera                               | 1         | 7.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor | 1         | 100%    |

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
| 0     | 14        | 87.5%   |
| 1     | 2         | 12.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 1         | 50%     |
| Fingerprint reader    | 1         | 50%     |

