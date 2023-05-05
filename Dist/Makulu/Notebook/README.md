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

Total: 30

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu | STYLISTIC Q665              | [438b08fb3d](https://linux-hardware.org/?probe=438b08fb3d) | Mar 06, 2023 |
| HUAWEI  | MateBook X                  | [cae415dee6](https://linux-hardware.org/?probe=cae415dee6) | Feb 20, 2023 |
| HUAWEI  | MateBook X                  | [6fed527c1b](https://linux-hardware.org/?probe=6fed527c1b) | Feb 20, 2023 |
| Fujitsu | STYLISTIC Q665              | [268703bd9e](https://linux-hardware.org/?probe=268703bd9e) | Feb 13, 2023 |
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
| Makulu 2020              | 10        | 52.63%  |
| Makulu Build: 2021.12.15 | 4         | 21.05%  |
| Makulu Buildvar          | 1         | 5.26%   |
| Makulu Build: 2022.01.06 | 1         | 5.26%   |
| Makulu Bld-2022.12.04    | 1         | 5.26%   |
| Makulu Bld-2022.11.03    | 1         | 5.26%   |
| Makulu 68                | 1         | 5.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Makulu | 18        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.11.0-41-generic      | 3         | 15.79%  |
| 5.15.0-53-generic      | 2         | 10.53%  |
| 5.11.0-43-generic      | 2         | 10.53%  |
| 5.10.0-8-amd64         | 2         | 10.53%  |
| 6.1.6-060106-generic   | 1         | 5.26%   |
| 6.1.11-060111-generic  | 1         | 5.26%   |
| 5.8.0-50-generic       | 1         | 5.26%   |
| 5.8.0-49-generic       | 1         | 5.26%   |
| 5.8.0-44-generic       | 1         | 5.26%   |
| 5.8.0-38-generic       | 1         | 5.26%   |
| 5.4.0-48-generic       | 1         | 5.26%   |
| 5.4.0-42-generic       | 1         | 5.26%   |
| 5.15.10-051510-generic | 1         | 5.26%   |
| 5.11.0-36-generic      | 1         | 5.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 6         | 31.58%  |
| 5.8.0   | 4         | 21.05%  |
| 5.4.0   | 2         | 10.53%  |
| 5.15.0  | 2         | 10.53%  |
| 5.10.0  | 2         | 10.53%  |
| 6.1.6   | 1         | 5.26%   |
| 6.1.11  | 1         | 5.26%   |
| 5.15.10 | 1         | 5.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 6         | 33.33%  |
| 5.8     | 4         | 22.22%  |
| 5.15    | 3         | 16.67%  |
| 5.4     | 2         | 11.11%  |
| 5.10    | 2         | 11.11%  |
| 6.1     | 1         | 5.56%   |

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


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 14        | 77.78%  |
| X-Cinnamon | 4         | 22.22%  |

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
| Unknown | 15        | 83.33%  |
| LightDM | 3         | 16.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 7         | 36.84%  |
| en_CA | 3         | 15.79%  |
| de_DE | 3         | 15.79%  |
| it_IT | 2         | 10.53%  |
| en_GB | 2         | 10.53%  |
| pl_PL | 1         | 5.26%   |
| nl_NL | 1         | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 10        | 52.63%  |
| EFI  | 9         | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 16        | 88.89%  |
| Tmpfs | 1         | 5.56%   |
| Btrfs | 1         | 5.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 94.44%  |
| GPT     | 1         | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 94.44%  |
| Yes       | 1         | 5.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 94.44%  |
| Yes       | 1         | 5.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 22.22%  |
| Dell                | 4         | 22.22%  |
| Lenovo              | 3         | 16.67%  |
| HUAWEI              | 2         | 11.11%  |
| ASUSTek Computer    | 2         | 11.11%  |
| Samsung Electronics | 1         | 5.56%   |
| Fujitsu             | 1         | 5.56%   |
| Apple               | 1         | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Samsung R580                  | 1         | 5.56%   |
| Lenovo V14-IIL 82C4           | 1         | 5.56%   |
| Lenovo ThinkPad T420 4236W1W  | 1         | 5.56%   |
| Lenovo IdeaPad Y530           | 1         | 5.56%   |
| HUAWEI MateBook X             | 1         | 5.56%   |
| HUAWEI KPL-W0X                | 1         | 5.56%   |
| HP Pavilion Laptop 15z-cw100  | 1         | 5.56%   |
| HP Pavilion 17                | 1         | 5.56%   |
| HP ENVY Notebook              | 1         | 5.56%   |
| HP Compaq 15                  | 1         | 5.56%   |
| Fujitsu STYLISTIC Q665        | 1         | 5.56%   |
| Dell Latitude E64406342Q0286/ | 1         | 5.56%   |
| Dell Latitude 3540            | 1         | 5.56%   |
| Dell Inspiron 5565            | 1         | 5.56%   |
| Dell Inspiron 3521            | 1         | 5.56%   |
| ASUS N55SL                    | 1         | 5.56%   |
| ASUS K55VD                    | 1         | 5.56%   |
| Apple MacBookAir6,2           | 1         | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| HP Pavilion       | 2         | 11.11%  |
| Dell Latitude     | 2         | 11.11%  |
| Dell Inspiron     | 2         | 11.11%  |
| Samsung R580      | 1         | 5.56%   |
| Lenovo V14-IIL    | 1         | 5.56%   |
| Lenovo ThinkPad   | 1         | 5.56%   |
| Lenovo IdeaPad    | 1         | 5.56%   |
| HUAWEI MateBook   | 1         | 5.56%   |
| HUAWEI KPL-W0X    | 1         | 5.56%   |
| HP ENVY           | 1         | 5.56%   |
| HP Compaq         | 1         | 5.56%   |
| Fujitsu STYLISTIC | 1         | 5.56%   |
| ASUS N55SL        | 1         | 5.56%   |
| ASUS K55VD        | 1         | 5.56%   |
| Apple MacBookAir6 | 1         | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 4         | 22.22%  |
| 2019 | 2         | 11.11%  |
| 2018 | 2         | 11.11%  |
| 2015 | 2         | 11.11%  |
| 2012 | 2         | 11.11%  |
| 2011 | 2         | 11.11%  |
| 2016 | 1         | 5.56%   |
| 2014 | 1         | 5.56%   |
| 2009 | 1         | 5.56%   |
| 2008 | 1         | 5.56%   |

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
| 4.01-8.0   | 9         | 47.37%  |
| 3.01-4.0   | 6         | 31.58%  |
| 8.01-16.0  | 3         | 15.79%  |
| 16.01-24.0 | 1         | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 8         | 40%     |
| 2.01-3.0 | 7         | 35%     |
| 3.01-4.0 | 3         | 15%     |
| 4.01-8.0 | 2         | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 84.21%  |
| 3      | 2         | 10.53%  |
| 2      | 1         | 5.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 55.56%  |
| No        | 8         | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 72.22%  |
| No        | 5         | 27.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 100%    |

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


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 4         | 22.22%  |
| UK          | 3         | 16.67%  |
| Germany     | 3         | 16.67%  |
| Italy       | 2         | 11.11%  |
| Canada      | 2         | 11.11%  |
| Uganda      | 1         | 5.56%   |
| Poland      | 1         | 5.56%   |
| Netherlands | 1         | 5.56%   |
| Australia   | 1         | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Steinfeld      | 1         | 4.76%   |
| Saint John     | 1         | 4.76%   |
| Oschersleben   | 1         | 4.76%   |
| Northborough   | 1         | 4.76%   |
| New York       | 1         | 4.76%   |
| Munich         | 1         | 4.76%   |
| Millers Creek  | 1         | 4.76%   |
| Melbourne      | 1         | 4.76%   |
| Manchester     | 1         | 4.76%   |
| Lodz           | 1         | 4.76%   |
| Kampala        | 1         | 4.76%   |
| Jamestown      | 1         | 4.76%   |
| Imperia        | 1         | 4.76%   |
| Hillegom       | 1         | 4.76%   |
| Freisbach      | 1         | 4.76%   |
| Etobicoke      | 1         | 4.76%   |
| Dover          | 1         | 4.76%   |
| Dallas         | 1         | 4.76%   |
| Brunswick West | 1         | 4.76%   |
| Brugherio      | 1         | 4.76%   |
| Ballygowan     | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 17.39%  |
| Samsung Electronics | 4         | 7      | 17.39%  |
| Toshiba             | 3         | 3      | 13.04%  |
| SanDisk             | 3         | 3      | 13.04%  |
| Unknown             | 1         | 1      | 4.35%   |
| Transcend           | 1         | 1      | 4.35%   |
| LITEON              | 1         | 2      | 4.35%   |
| Lite-On Technology  | 1         | 1      | 4.35%   |
| KIOXIA              | 1         | 1      | 4.35%   |
| JMicron Technology  | 1         | 1      | 4.35%   |
| Hitachi             | 1         | 1      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 2         | 8.33%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 8.33%   |
| Unknown SD/MMC/MS PRO 249GB          | 1         | 4.17%   |
| Transcend TS64GMSA230S 64GB SSD      | 1         | 4.17%   |
| Toshiba MQ01ABF050M 500GB            | 1         | 4.17%   |
| Seagate ST9320325AS 320GB            | 1         | 4.17%   |
| Seagate Expansion Desk 8TB           | 1         | 4.17%   |
| SanDisk SSD U110 128GB               | 1         | 4.17%   |
| SanDisk SSD PLUS 1000GB              | 1         | 4.17%   |
| SanDisk NVMe SSD Drive 512GB         | 1         | 4.17%   |
| Samsung NVMe SSD Drive 1TB           | 1         | 4.17%   |
| Samsung NVMe SSD Drive 1024GB        | 1         | 4.17%   |
| Samsung MZNLN256HCHP-00000 256GB SSD | 1         | 4.17%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD | 1         | 4.17%   |
| Samsung HM500JI 500GB                | 1         | 4.17%   |
| LITEON L8H-256V2G-HP 256GB SSD       | 1         | 4.17%   |
| Lite-On LITEON CB1-SD256 256GB       | 1         | 4.17%   |
| KIOXIA NVMe SSD Drive 256GB          | 1         | 4.17%   |
| JMicron Tech 250GB                   | 1         | 4.17%   |
| Hitachi HTS545025B9A300 250GB        | 1         | 4.17%   |
| HGST HTS721010A9E630 1TB             | 1         | 4.17%   |
| Apple SSD SM0256F 256GB              | 1         | 4.17%   |

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
| SanDisk             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 4      | 28.57%  |
| Transcend           | 1         | 1      | 14.29%  |
| LITEON              | 1         | 2      | 14.29%  |
| Apple               | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 10        | 12     | 47.62%  |
| SSD     | 6         | 10     | 28.57%  |
| NVMe    | 4         | 5      | 19.05%  |
| Unknown | 1         | 1      | 4.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 15        | 20     | 71.43%  |
| NVMe | 4         | 5      | 19.05%  |
| SAS  | 2         | 3      | 9.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 17     | 68.75%  |
| 0.51-1.0   | 4         | 4      | 25%     |
| 4.01-10.0  | 1         | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 9         | 47.37%  |
| 251-500        | 4         | 21.05%  |
| 501-1000       | 2         | 10.53%  |
| More than 3000 | 1         | 5.26%   |
| 21-50          | 1         | 5.26%   |
| 1-20           | 1         | 5.26%   |
| 51-100         | 1         | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 9         | 42.86%  |
| 1-20           | 7         | 33.33%  |
| 51-100         | 2         | 9.52%   |
| More than 3000 | 1         | 4.76%   |
| 251-500        | 1         | 4.76%   |
| 101-250        | 1         | 4.76%   |

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
| Detected | 18        | 28     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 11        | 55%     |
| AMD                 | 4         | 20%     |
| Samsung Electronics | 2         | 10%     |
| SanDisk             | 1         | 5%      |
| Lite-On Technology  | 1         | 5%      |
| KIOXIA              | 1         | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 20%     |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 10%     |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 10%     |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 5%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 5%      |
| Samsung Apple PCIe SSD                                                         | 1         | 5%      |
| Lite-On Non-Volatile memory controller                                         | 1         | 5%      |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 5%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 5%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 5%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 5%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 5%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 5%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 16        | 80%     |
| NVMe | 4         | 20%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 72.22%  |
| AMD    | 5         | 27.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 5.56%   |
| Intel Core M-5Y71 CPU @ 1.20GHz                 | 1         | 5.56%   |
| Intel Core i7-4600M CPU @ 2.90GHz               | 1         | 5.56%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 5.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 5.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 5.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 5.56%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 1         | 5.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 5.56%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 5.56%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 1         | 5.56%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1         | 5.56%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 1         | 5.56%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 5.56%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 1         | 5.56%   |
| AMD E1-2100 APU with Radeon HD Graphics         | 1         | 5.56%   |
| AMD A4-5000 APU with Radeon HD Graphics         | 1         | 5.56%   |
| AMD A12-9700P RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 5         | 27.78%  |
| Intel Core i7           | 3         | 16.67%  |
| Intel Core i3           | 3         | 16.67%  |
| Intel Pentium Dual-Core | 1         | 5.56%   |
| Intel Core M            | 1         | 5.56%   |
| AMD Ryzen 7             | 1         | 5.56%   |
| AMD Ryzen 5             | 1         | 5.56%   |
| AMD E1                  | 1         | 5.56%   |
| AMD A4                  | 1         | 5.56%   |
| AMD A12                 | 1         | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 72.22%  |
| 4      | 5         | 27.78%  |

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
| 2      | 15        | 83.33%  |
| 1      | 3         | 16.67%  |

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
| Unknown    | 5         | 25%     |
| 0x40651    | 2         | 10%     |
| 0x206a7    | 2         | 10%     |
| 0x806e9    | 1         | 5%      |
| 0x406e3    | 1         | 5%      |
| 0x306c3    | 1         | 5%      |
| 0x306a9    | 1         | 5%      |
| 0x20652    | 1         | 5%      |
| 0x1067a    | 1         | 5%      |
| 0x08108102 | 1         | 5%      |
| 0x08101007 | 1         | 5%      |
| 0x07000110 | 1         | 5%      |
| 0x0700010f | 1         | 5%      |
| 0x06006118 | 1         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Haswell     | 3         | 16.67%  |
| SandyBridge | 2         | 11.11%  |
| Jaguar      | 2         | 11.11%  |
| IvyBridge   | 2         | 11.11%  |
| Zen+        | 1         | 5.56%   |
| Zen         | 1         | 5.56%   |
| Westmere    | 1         | 5.56%   |
| Skylake     | 1         | 5.56%   |
| Penryn      | 1         | 5.56%   |
| KabyLake    | 1         | 5.56%   |
| IceLake     | 1         | 5.56%   |
| Excavator   | 1         | 5.56%   |
| Broadwell   | 1         | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 11        | 55%     |
| AMD    | 5         | 25%     |
| Nvidia | 4         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 10%     |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 10%     |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 10%     |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 5%      |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 5%      |
| Nvidia GF116M [GeForce GT 555M/635M]                                      | 1         | 5%      |
| Nvidia G96CM [GeForce 9600M GS]                                           | 1         | 5%      |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 5%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 5%      |
| Intel HD Graphics 620                                                     | 1         | 5%      |
| Intel HD Graphics 5300                                                    | 1         | 5%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 5%      |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 1         | 5%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 5%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 5%      |
| AMD Kabini [Radeon HD 8330]                                               | 1         | 5%      |
| AMD Kabini [Radeon HD 8210]                                               | 1         | 5%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 9         | 50%     |
| 1 x AMD        | 5         | 27.78%  |
| 1 x Nvidia     | 2         | 11.11%  |
| Intel + Nvidia | 2         | 11.11%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 18        | 94.74%  |
| Unknown | 1         | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 50%     |
| 0.01-0.5   | 4         | 22.22%  |
| 1.01-2.0   | 3         | 16.67%  |
| 0.51-1.0   | 2         | 11.11%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 5         | 27.78%  |
| Samsung Electronics     | 4         | 22.22%  |
| Chimei Innolux          | 3         | 16.67%  |
| BOE                     | 2         | 11.11%  |
| Sharp                   | 1         | 5.56%   |
| Chi Mei Optoelectronics | 1         | 5.56%   |
| AU Optronics            | 1         | 5.56%   |
| Apple                   | 1         | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LQ116M1JW02 SHP1440 1920x1080 256x144mm 11.6-inch                  | 1         | 5.56%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 5.56%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 5.56%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch    | 1         | 5.56%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 5.56%   |
| LG Display LCD Monitor LGD062B 1920x1080 344x194mm 15.5-inch             | 1         | 5.56%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch             | 1         | 5.56%   |
| LG Display LCD Monitor LGD03E5 1366x768 309x174mm 14.0-inch              | 1         | 5.56%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 1         | 5.56%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 5.56%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 1         | 5.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch | 1         | 5.56%   |
| BOE LCD Monitor BOE083C 1920x1080 309x173mm 13.9-inch                    | 1         | 5.56%   |
| BOE LCD Monitor BOE07D3 1920x1080 309x174mm 14.0-inch                    | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO9274 1280x800 331x207mm 15.4-inch            | 1         | 5.56%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 1         | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 7         | 38.89%  |
| 1366x768 (WXGA)  | 6         | 33.33%  |
| 3840x2400        | 1         | 5.56%   |
| 2160x1440        | 1         | 5.56%   |
| 1600x900 (HD+)   | 1         | 5.56%   |
| 1440x900 (WXGA+) | 1         | 5.56%   |
| 1280x800 (WXGA)  | 1         | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 55.56%  |
| 14     | 3         | 16.67%  |
| 13     | 3         | 16.67%  |
| 17     | 1         | 5.56%   |
| 11     | 1         | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 66.67%  |
| 351-400     | 3         | 16.67%  |
| 201-300     | 3         | 16.67%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 14        | 77.78%  |
| 16/10 | 3         | 16.67%  |
| 3/2   | 1         | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 55.56%  |
| 81-90          | 5         | 27.78%  |
| 71-80          | 1         | 5.56%   |
| 51-60          | 1         | 5.56%   |
| 121-130        | 1         | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 5         | 27.78%  |
| 101-120       | 5         | 27.78%  |
| 51-100        | 5         | 27.78%  |
| 161-240       | 2         | 11.11%  |
| More than 240 | 1         | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 18        | 94.74%  |
| 0     | 1         | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 27.59%  |
| Realtek Semiconductor           | 7         | 24.14%  |
| Qualcomm Atheros                | 6         | 20.69%  |
| Broadcom Limited                | 2         | 6.9%    |
| Broadcom                        | 2         | 6.9%    |
| Ralink Technology               | 1         | 3.45%   |
| Qualcomm Atheros Communications | 1         | 3.45%   |
| Marvell Technology Group        | 1         | 3.45%   |
| D-Link                          | 1         | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Notebooks | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 4         | 11.43%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 3         | 8.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2         | 5.71%   |
| Intel Wireless 7265                                                                  | 2         | 5.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 2.86%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 2.86%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 2.86%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1         | 2.86%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 2.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1         | 2.86%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB]       | 1         | 2.86%   |
| Intel Wireless-AC 9260                                                               | 1         | 2.86%   |
| Intel Wireless 8265 / 8275                                                           | 1         | 2.86%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 2.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 2.86%   |
| Intel Ethernet Connection I217-LM                                                    | 1         | 2.86%   |
| Intel Ethernet Connection (3) I218-LM                                                | 1         | 2.86%   |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 2.86%   |
| Intel Centrino Advanced-N 6235                                                       | 1         | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 1         | 2.86%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 2.86%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                          | 1         | 2.86%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                           | 1         | 2.86%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 1         | 2.86%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 2.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 38.1%   |
| Qualcomm Atheros                | 5         | 23.81%  |
| Realtek Semiconductor           | 2         | 9.52%   |
| Broadcom                        | 2         | 9.52%   |
| Ralink Technology               | 1         | 4.76%   |
| Qualcomm Atheros Communications | 1         | 4.76%   |
| D-Link                          | 1         | 4.76%   |
| Broadcom Limited                | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Notebooks | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2         | 9.09%   |
| Intel Wireless 7265                                                                  | 2         | 9.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 4.55%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 4.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 4.55%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1         | 4.55%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 4.55%   |
| Intel Wireless-AC 9260                                                               | 1         | 4.55%   |
| Intel Wireless 8265 / 8275                                                           | 1         | 4.55%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 4.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 4.55%   |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 4.55%   |
| Intel Centrino Advanced-N 6235                                                       | 1         | 4.55%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 4.55%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                           | 1         | 4.55%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 1         | 4.55%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 7         | 53.85%  |
| Intel                    | 3         | 23.08%  |
| Qualcomm Atheros         | 1         | 7.69%   |
| Marvell Technology Group | 1         | 7.69%   |
| Broadcom Limited         | 1         | 7.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 30.77%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3         | 23.08%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 7.69%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 7.69%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 7.69%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 7.69%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 7.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 58.06%  |
| Ethernet | 13        | 41.94%  |

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
| No   | 13        | 68.42%  |
| Yes  | 6         | 31.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5         | 35.71%  |
| Broadcom                        | 4         | 28.57%  |
| Qualcomm Atheros Communications | 2         | 14.29%  |
| Realtek Semiconductor           | 1         | 7.14%   |
| IMC Networks                    | 1         | 7.14%   |
| Apple                           | 1         | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 3         | 21.43%  |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 7.14%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 7.14%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 1         | 7.14%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 7.14%   |
| Broadcom Bluetooth 2.1 Device                     | 1         | 7.14%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 7.14%   |
| Broadcom BCM2046 Bluetooth Device                 | 1         | 7.14%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 7.14%   |
| Apple Bluetooth USB Host Controller               | 1         | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 65%     |
| AMD    | 5         | 25%     |
| Nvidia | 2         | 10%     |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Kabini HDMI/DP Audio                                                   | 3         | 10.71%  |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 7.14%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 7.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 7.14%   |
| AMD FCH Azalia Controller                                                  | 2         | 7.14%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 7.14%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 3.57%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 3.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 3.57%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 3.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 3.57%   |

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
| Chicony Electronics                    | 4         | 25%     |
| Suyin                                  | 3         | 18.75%  |
| Realtek Semiconductor                  | 2         | 12.5%   |
| Microdia                               | 2         | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 12.5%   |
| Z-Star Microelectronics                | 1         | 6.25%   |
| Lite-On Technology                     | 1         | 6.25%   |
| IMC Networks                           | 1         | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 12.5%   |
| Z-Star WebCam SCB-1900N                                 | 1         | 6.25%   |
| Suyin UVC HD Webcam                                     | 1         | 6.25%   |
| Suyin Integrated_Webcam_HD                              | 1         | 6.25%   |
| Suyin HP Truevision HD                                  | 1         | 6.25%   |
| Realtek Integrated Webcam HD                            | 1         | 6.25%   |
| Realtek FJ Camera                                       | 1         | 6.25%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 1         | 6.25%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 6.25%   |
| Lite-On HP Wide Vision HD Camera                        | 1         | 6.25%   |
| IMC Networks Huawei Web Camera - HD                     | 1         | 6.25%   |
| Chicony UVC 1.00 device HD UVC WebCam                   | 1         | 6.25%   |
| Chicony Lenovo EasyCamera                               | 1         | 6.25%   |
| Chicony Integrated Camera                               | 1         | 6.25%   |
| Chicony FJ 5M Camera                                    | 1         | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor | 2         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| O2 Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 78.95%  |
| 1     | 2         | 10.53%  |
| 3     | 1         | 5.26%   |
| 2     | 1         | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 2         | 40%     |
| Multimedia controller | 1         | 20%     |
| Graphics card         | 1         | 20%     |
| Chipcard              | 1         | 20%     |

