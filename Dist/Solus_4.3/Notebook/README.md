Solus 4.3 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Solus 4.3.

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Google    | Delbin                      | [fbf8763bd4](https://linux-hardware.org/?probe=fbf8763bd4) | Feb 05, 2022 |
| Acer      | Aspire A315-54              | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| Acer      | Swift SF114-34              | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Toshiba   | TECRA R840                  | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| Sony      | VPCYB15AB                   | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| Dell      | Latitude 5580               | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Framework | Laptop                      | [7995a7a4de](https://linux-hardware.org/?probe=7995a7a4de) | Nov 18, 2021 |
| Dell      | Latitude E6220              | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| Framework | Laptop                      | [72a07a2e81](https://linux-hardware.org/?probe=72a07a2e81) | Nov 11, 2021 |
| AZW       | SEi                         | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| ASUSTek   | VivoBook_ASUSLaptop X509... | [c7f1620c1c](https://linux-hardware.org/?probe=c7f1620c1c) | Oct 05, 2021 |
| HP        | OMEN Laptop 15-en0xxx       | [f19ad7cba2](https://linux-hardware.org/?probe=f19ad7cba2) | Sep 16, 2021 |
| HP        | OMEN Laptop 15-en0xxx       | [1cca1c6ce5](https://linux-hardware.org/?probe=1cca1c6ce5) | Sep 13, 2021 |
| HP        | OMEN Laptop 15-en0xxx       | [888bf75e20](https://linux-hardware.org/?probe=888bf75e20) | Sep 13, 2021 |
| Acer      | Nitro AN515-45              | [5bad88330d](https://linux-hardware.org/?probe=5bad88330d) | Sep 01, 2021 |
| Dell      | Inspiron 1525               | [3f3cd9c9e2](https://linux-hardware.org/?probe=3f3cd9c9e2) | Aug 25, 2021 |
| Dell      | Inspiron 1525               | [de3cb038ef](https://linux-hardware.org/?probe=de3cb038ef) | Aug 25, 2021 |
| Acer      | Nitro AN515-45              | [d98d816e7f](https://linux-hardware.org/?probe=d98d816e7f) | Aug 18, 2021 |
| Acer      | Nitro AN515-45              | [49cd3453c7](https://linux-hardware.org/?probe=49cd3453c7) | Aug 16, 2021 |
| Acer      | Nitro AN515-45              | [5320b136ea](https://linux-hardware.org/?probe=5320b136ea) | Aug 12, 2021 |
| Dell      | Vostro 15-3568              | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| HP        | ProBook 650 G2              | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Dell      | Inspiron 15-3573            | [52916532a3](https://linux-hardware.org/?probe=52916532a3) | Aug 06, 2021 |
| Lenovo    | IdeaPad 320-15ISK 80XH      | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.13.1-187.current  | 3         | 18.75%  |
| 5.14.21-210.current | 2         | 12.5%   |
| 5.14.16-205.current | 2         | 12.5%   |
| 5.13.6-190.current  | 2         | 12.5%   |
| 5.13.12-193.current | 2         | 12.5%   |
| 5.14.7-198.current  | 1         | 6.25%   |
| 5.14.16-204.current | 1         | 6.25%   |
| 5.14.15-203.current | 1         | 6.25%   |
| 5.14.12-201.current | 1         | 6.25%   |
| 5.13.15-194.current | 1         | 6.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.16 | 3         | 18.75%  |
| 5.13.1  | 3         | 18.75%  |
| 5.14.21 | 2         | 12.5%   |
| 5.13.6  | 2         | 12.5%   |
| 5.13.12 | 2         | 12.5%   |
| 5.14.7  | 1         | 6.25%   |
| 5.14.15 | 1         | 6.25%   |
| 5.14.12 | 1         | 6.25%   |
| 5.13.15 | 1         | 6.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 8         | 50%     |
| 5.13    | 8         | 50%     |

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


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 8         | 50%     |
| MATE    | 2         | 12.5%   |
| KDE     | 2         | 12.5%   |
| GNOME   | 2         | 12.5%   |
| Unknown | 2         | 12.5%   |

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
| Unknown | 12        | 75%     |
| LightDM | 2         | 12.5%   |
| SDDM    | 1         | 6.25%   |
| GDM     | 1         | 6.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 10        | 62.5%   |
| en_GB | 2         | 12.5%   |
| de_DE | 2         | 12.5%   |
| pt_BR | 1         | 6.25%   |
| en_IN | 1         | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 12        | 75%     |
| BIOS | 4         | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 16        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 75%     |
| GPT     | 4         | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 12        | 75%     |
| Yes       | 4         | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell             | 5         | 31.25%  |
| Acer             | 3         | 18.75%  |
| Toshiba          | 1         | 6.25%   |
| Sony             | 1         | 6.25%   |
| Lenovo           | 1         | 6.25%   |
| Hewlett-Packard  | 1         | 6.25%   |
| Google           | 1         | 6.25%   |
| Framework        | 1         | 6.25%   |
| AZW              | 1         | 6.25%   |
| ASUSTek Computer | 1         | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba TECRA R840                     | 1         | 6.25%   |
| Sony VPCYB15AB                         | 1         | 6.25%   |
| Lenovo IdeaPad 320-15ISK 80XH          | 1         | 6.25%   |
| HP OMEN Laptop 15-en0xxx               | 1         | 6.25%   |
| Google Delbin                          | 1         | 6.25%   |
| Framework Laptop                       | 1         | 6.25%   |
| Dell Vostro 15-3568                    | 1         | 6.25%   |
| Dell Latitude E6220                    | 1         | 6.25%   |
| Dell Latitude 5580                     | 1         | 6.25%   |
| Dell Inspiron 1525                     | 1         | 6.25%   |
| Dell Inspiron 15-3573                  | 1         | 6.25%   |
| AZW SEi                                | 1         | 6.25%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 1         | 6.25%   |
| Acer Swift SF114-34                    | 1         | 6.25%   |
| Acer Nitro AN515-45                    | 1         | 6.25%   |
| Acer Aspire A315-54                    | 1         | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell Latitude    | 2         | 12.5%   |
| Dell Inspiron    | 2         | 12.5%   |
| Toshiba TECRA    | 1         | 6.25%   |
| Sony VPCYB15AB   | 1         | 6.25%   |
| Lenovo IdeaPad   | 1         | 6.25%   |
| HP OMEN          | 1         | 6.25%   |
| Google Delbin    | 1         | 6.25%   |
| Framework Laptop | 1         | 6.25%   |
| Dell Vostro      | 1         | 6.25%   |
| AZW SEi          | 1         | 6.25%   |
| ASUS VivoBook    | 1         | 6.25%   |
| Acer Swift       | 1         | 6.25%   |
| Acer Nitro       | 1         | 6.25%   |
| Acer Aspire      | 1         | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 3         | 18.75%  |
| 2020 | 3         | 18.75%  |
| 2019 | 2         | 12.5%   |
| 2017 | 2         | 12.5%   |
| 2011 | 2         | 12.5%   |
| 2018 | 1         | 6.25%   |
| 2016 | 1         | 6.25%   |
| 2010 | 1         | 6.25%   |
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
| No   | 15        | 93.75%  |
| Yes  | 1         | 6.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 6         | 37.5%   |
| 32.01-64.0 | 2         | 12.5%   |
| 3.01-4.0   | 2         | 12.5%   |
| 16.01-24.0 | 2         | 12.5%   |
| 8.01-16.0  | 2         | 12.5%   |
| 2.01-3.0   | 1         | 6.25%   |
| 1.01-2.0   | 1         | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 7         | 43.75%  |
| 1.01-2.0 | 4         | 25%     |
| 4.01-8.0 | 2         | 12.5%   |
| 3.01-4.0 | 2         | 12.5%   |
| 0.51-1.0 | 1         | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 12        | 75%     |
| 2      | 4         | 25%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 12        | 75%     |
| Yes       | 4         | 25%     |

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
| Yes       | 13        | 81.25%  |
| No        | 3         | 18.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 4         | 25%     |
| Netherlands | 2         | 12.5%   |
| India       | 2         | 12.5%   |
| Brazil      | 2         | 12.5%   |
| Vietnam     | 1         | 6.25%   |
| UK          | 1         | 6.25%   |
| Poland      | 1         | 6.25%   |
| Nepal       | 1         | 6.25%   |
| Germany     | 1         | 6.25%   |
| Belgium     | 1         | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Zoutleeuw      | 1         | 6.25%   |
| Vineland       | 1         | 6.25%   |
| Red Oak        | 1         | 6.25%   |
| NieporÄ™t   | 1         | 6.25%   |
| Navelim        | 1         | 6.25%   |
| Naaldwijk      | 1         | 6.25%   |
| Milwaukee      | 1         | 6.25%   |
| Kathmandu      | 1         | 6.25%   |
| Hanoi          | 1         | 6.25%   |
| Groningen      | 1         | 6.25%   |
| GoiÃ¢nia     | 1         | 6.25%   |
| Duisburg       | 1         | 6.25%   |
| Dagenham       | 1         | 6.25%   |
| Coimbatore     | 1         | 6.25%   |
| Belo Horizonte | 1         | 6.25%   |
| Anacortes      | 1         | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK Hynix            | 3         | 3      | 15%     |
| Sandisk             | 3         | 4      | 15%     |
| WDC                 | 2         | 2      | 10%     |
| Unknown             | 2         | 2      | 10%     |
| Seagate             | 2         | 2      | 10%     |
| Samsung Electronics | 2         | 2      | 10%     |
| Toshiba             | 1         | 1      | 5%      |
| Silicon Motion      | 1         | 1      | 5%      |
| PNY                 | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| Advantech           | 1         | 1      | 5%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Sandisk NVMe SSD Drive 256GB           | 2         | 9.52%   |
| WDC WD3200BEVT-75ZCT2 320GB            | 1         | 4.76%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 4.76%   |
| Unknown USB DISK 3.2 500GB             | 1         | 4.76%   |
| Unknown MMC Card  128GB                | 1         | 4.76%   |
| Toshiba MQ01ABF050 500GB               | 1         | 4.76%   |
| SK Hynix NVMe SSD Drive 500GB          | 1         | 4.76%   |
| SK Hynix NVMe SSD Drive 256GB          | 1         | 4.76%   |
| SK Hynix NVMe SSD Drive 128GB          | 1         | 4.76%   |
| Silicon Motion NVMe SSD Drive 512GB    | 1         | 4.76%   |
| Seagate ST1000LM049-2GH172 1TB         | 1         | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB         | 1         | 4.76%   |
| Sandisk NVMe SSD Drive 1TB             | 1         | 4.76%   |
| SanDisk Extreme Pro 1TB                | 1         | 4.76%   |
| Samsung SSD 850 EVO 250GB              | 1         | 4.76%   |
| Samsung NVMe SSD Drive 512GB           | 1         | 4.76%   |
| PNY CS900 240GB SSD                    | 1         | 4.76%   |
| Kingston SA400S37240G 240GB SSD        | 1         | 4.76%   |
| Intel NVMe SSD Drive 512GB             | 1         | 4.76%   |
| Advantech SQF-S25M8-128G-AAG 128GB SSD | 1         | 4.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Seagate | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 25%     |
| PNY                 | 1         | 1      | 25%     |
| Kingston            | 1         | 1      | 25%     |
| Advantech           | 1         | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 8         | 10     | 42.11%  |
| HDD     | 5         | 5      | 26.32%  |
| SSD     | 4         | 4      | 21.05%  |
| MMC     | 1         | 1      | 5.26%   |
| Unknown | 1         | 1      | 5.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9         | 9      | 47.37%  |
| NVMe | 8         | 10     | 42.11%  |
| SAS  | 1         | 1      | 5.26%   |
| MMC  | 1         | 1      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 6         | 6      | 66.67%  |
| 0.51-1.0   | 3         | 3      | 33.33%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 7         | 43.75%  |
| 251-500    | 5         | 31.25%  |
| 501-1000   | 2         | 12.5%   |
| 21-50      | 1         | 6.25%   |
| 51-100     | 1         | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 8         | 50%     |
| 21-50   | 3         | 18.75%  |
| 101-250 | 2         | 12.5%   |
| 51-100  | 2         | 12.5%   |
| 251-500 | 1         | 6.25%   |

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
| Detected | 14        | 18     | 82.35%  |
| Works    | 3         | 3      | 17.65%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 10        | 45.45%  |
| AMD                 | 4         | 18.18%  |
| SK Hynix            | 3         | 13.64%  |
| Sandisk             | 3         | 13.64%  |
| Silicon Motion      | 1         | 4.55%   |
| Samsung Electronics | 1         | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 13.04%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 8.7%    |
| SK Hynix PC300 NVMe Solid State Drive 256GB                                   | 1         | 4.35%   |
| SK Hynix Gold P31 SSD                                                         | 1         | 4.35%   |
| SK Hynix BC501 NVMe Solid State Drive                                         | 1         | 4.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 4.35%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1         | 4.35%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 4.35%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 4.35%   |
| Intel SSD 660P Series                                                         | 1         | 4.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 4.35%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 4.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 4.35%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 4.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 4.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1         | 4.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 4.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 12        | 54.55%  |
| NVMe | 8         | 36.36%  |
| RAID | 1         | 4.55%   |
| IDE  | 1         | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 12        | 75%     |
| AMD    | 4         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 12.5%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 6.25%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 6.25%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 6.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 6.25%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 6.25%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 6.25%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 6.25%   |
| Intel Celeron CPU 540 @ 1.86GHz               | 1         | 6.25%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 6.25%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 6.25%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 6.25%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 6.25%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 6.25%   |
| AMD E-350 Processor                           | 1         | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 3         | 18.75%  |
| Intel Core i5        | 3         | 18.75%  |
| Other                | 2         | 12.5%   |
| Intel Celeron        | 2         | 12.5%   |
| AMD Ryzen 7          | 2         | 12.5%   |
| Intel Pentium Silver | 1         | 6.25%   |
| Intel Core i3        | 1         | 6.25%   |
| AMD Ryzen 5          | 1         | 6.25%   |
| AMD E                | 1         | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 7         | 43.75%  |
| 4      | 6         | 37.5%   |
| 8      | 1         | 6.25%   |
| 6      | 1         | 6.25%   |
| 1      | 1         | 6.25%   |

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
| 2      | 12        | 75%     |
| 1      | 4         | 25%     |

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
| 0x806c1    | 2         | 12.5%   |
| 0x206a7    | 2         | 12.5%   |
| 0x906e9    | 1         | 6.25%   |
| 0x906c0    | 1         | 6.25%   |
| 0x806ec    | 1         | 6.25%   |
| 0x806ea    | 1         | 6.25%   |
| 0x706a1    | 1         | 6.25%   |
| 0x406e3    | 1         | 6.25%   |
| 0x10661    | 1         | 6.25%   |
| 0x0a50000c | 1         | 6.25%   |
| 0x08600106 | 1         | 6.25%   |
| 0x08108109 | 1         | 6.25%   |
| 0x05000029 | 1         | 6.25%   |
| Unknown    | 1         | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 4         | 25%     |
| TigerLake     | 2         | 12.5%   |
| SandyBridge   | 2         | 12.5%   |
| Zen+          | 1         | 6.25%   |
| Zen 3         | 1         | 6.25%   |
| Zen 2         | 1         | 6.25%   |
| Tremont       | 1         | 6.25%   |
| Skylake       | 1         | 6.25%   |
| Goldmont plus | 1         | 6.25%   |
| Core          | 1         | 6.25%   |
| Bobcat        | 1         | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 11        | 55%     |
| AMD    | 6         | 30%     |
| Nvidia | 3         | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 4.76%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 4.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 4.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 4.76%   |
| Intel Tiger Lake UHD Graphics                                             | 1         | 4.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 4.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 4.76%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 4.76%   |
| Intel HD Graphics 630                                                     | 1         | 4.76%   |
| Intel HD Graphics 620                                                     | 1         | 4.76%   |
| Intel HD Graphics 520                                                     | 1         | 4.76%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 4.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 4.76%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 1         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 4.76%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 4.76%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                    | 1         | 4.76%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 4.76%   |
| AMD Renoir                                                                | 1         | 4.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 4.76%   |
| AMD Cezanne                                                               | 1         | 4.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 9         | 56.25%  |
| 1 x AMD        | 3         | 18.75%  |
| AMD + Nvidia   | 2         | 12.5%   |
| Intel + Nvidia | 1         | 6.25%   |
| Intel + AMD    | 1         | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 14        | 87.5%   |
| Proprietary | 2         | 12.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 62.5%   |
| 1.01-2.0   | 2         | 12.5%   |
| 0.01-0.5   | 2         | 12.5%   |
| 5.01-6.0   | 1         | 6.25%   |
| 0.51-1.0   | 1         | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 5         | 26.32%  |
| Samsung Electronics     | 3         | 15.79%  |
| BOE                     | 3         | 15.79%  |
| LG Display              | 2         | 10.53%  |
| Toshiba                 | 1         | 5.26%   |
| Philips                 | 1         | 5.26%   |
| PANDA                   | 1         | 5.26%   |
| Lenovo                  | 1         | 5.26%   |
| Chi Mei Optoelectronics | 1         | 5.26%   |
| Acer                    | 1         | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Toshiba Internal LCD TOS5091 1366x768 340x190mm 15.3-inch                | 1         | 5%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 5%      |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 5%      |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 5%      |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 5%      |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                    | 1         | 5%      |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 5%      |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch             | 1         | 5%      |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch             | 1         | 5%      |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                      | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 5%      |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 1         | 5%      |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 5%      |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                    | 1         | 5%      |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 5%      |
| Acer K242HYL ACR064A 1920x1080 527x296mm 23.8-inch                       | 1         | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 9         | 50%     |
| 1366x768 (WXGA) | 7         | 38.89%  |
| 2256x1504       | 1         | 5.56%   |
| 1280x800 (WXGA) | 1         | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 63.16%  |
| 27     | 2         | 10.53%  |
| 23     | 1         | 5.26%   |
| 21     | 1         | 5.26%   |
| 14     | 1         | 5.26%   |
| 13     | 1         | 5.26%   |
| 11     | 1         | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 63.16%  |
| 501-600     | 3         | 15.79%  |
| 201-300     | 2         | 10.53%  |
| 401-500     | 1         | 5.26%   |
| 351-400     | 1         | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 14        | 87.5%   |
| 3/2   | 1         | 6.25%   |
| 16/10 | 1         | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 63.16%  |
| 81-90          | 2         | 10.53%  |
| 301-350        | 2         | 10.53%  |
| 51-60          | 1         | 5.26%   |
| 201-250        | 1         | 5.26%   |
| 151-200        | 1         | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 7         | 41.18%  |
| 101-120 | 5         | 29.41%  |
| 51-100  | 4         | 23.53%  |
| 161-240 | 1         | 5.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 13        | 81.25%  |
| 2     | 2         | 12.5%   |
| 3     | 1         | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 9         | 37.5%   |
| Realtek Semiconductor    | 7         | 29.17%  |
| Qualcomm Atheros         | 3         | 12.5%   |
| TP-Link                  | 1         | 4.17%   |
| MEDIATEK                 | 1         | 4.17%   |
| Marvell Technology Group | 1         | 4.17%   |
| Dell                     | 1         | 4.17%   |
| Broadcom                 | 1         | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 17.24%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 6.9%    |
| Intel Wi-Fi 6 AX200                                               | 2         | 6.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.9%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 3.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 3.45%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 3.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.45%   |
| Intel Wireless 8265 / 8275                                        | 1         | 3.45%   |
| Intel Wireless 3165                                               | 1         | 3.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 3.45%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 3.45%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 3.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 3.45%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 3.45%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 3.45%   |
| Dell DW5550                                                       | 1         | 3.45%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 1         | 3.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 56.25%  |
| Qualcomm Atheros      | 3         | 18.75%  |
| Realtek Semiconductor | 2         | 12.5%   |
| MEDIATEK              | 1         | 6.25%   |
| Broadcom              | 1         | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 12.5%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 12.5%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 6.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 6.25%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 6.25%   |
| Intel Wireless 8265 / 8275                                     | 1         | 6.25%   |
| Intel Wireless 3165                                            | 1         | 6.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 6.25%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 6.25%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 6.25%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 6.25%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 6.25%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 6         | 50%     |
| Intel                    | 3         | 25%     |
| TP-Link                  | 1         | 8.33%   |
| Qualcomm Atheros         | 1         | 8.33%   |
| Marvell Technology Group | 1         | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 41.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 16.67%  |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 8.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 8.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 8.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 8.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 55.17%  |
| Ethernet | 12        | 41.38%  |
| Modem    | 1         | 3.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 12        | 54.55%  |
| Ethernet | 10        | 45.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 11        | 68.75%  |
| 1     | 5         | 31.25%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 10        | 62.5%   |
| Yes  | 6         | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 53.85%  |
| Lite-On Technology              | 2         | 15.38%  |
| Realtek Semiconductor           | 1         | 7.69%   |
| Qualcomm Atheros Communications | 1         | 7.69%   |
| IMC Networks                    | 1         | 7.69%   |
| Dell                            | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Intel Bluetooth Device             | 2         | 15.38%  |
| Intel AX201 Bluetooth              | 2         | 15.38%  |
| Intel AX200 Bluetooth              | 2         | 15.38%  |
| Realtek RTL8821A Bluetooth         | 1         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device | 1         | 7.69%   |
| Lite-On Wireless_Device            | 1         | 7.69%   |
| Lite-On Bluetooth Device           | 1         | 7.69%   |
| Intel Bluetooth wireless interface | 1         | 7.69%   |
| IMC Networks Bluetooth Radio       | 1         | 7.69%   |
| Dell DW375 Bluetooth Module        | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 12        | 54.55%  |
| AMD                 | 5         | 22.73%  |
| Nvidia              | 3         | 13.64%  |
| Samsung Electronics | 1         | 4.55%   |
| Conexant Systems    | 1         | 4.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 12.5%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                                   | 2         | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2         | 8.33%   |
| Samsung Electronics USBC Headset                                                  | 1         | 4.17%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 4.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1         | 4.17%   |
| Nvidia Audio device                                                               | 1         | 4.17%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 4.17%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 4.17%   |
| Intel CM238 HD Audio Controller                                                   | 1         | 4.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1         | 4.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1         | 4.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1         | 4.17%   |
| Conexant Systems Hi-Res Audio                                                     | 1         | 4.17%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 4.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 4.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 4.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 2         | 22.22%  |
| Samsung Electronics | 2         | 22.22%  |
| Unknown             | 1         | 11.11%  |
| Team                | 1         | 11.11%  |
| Micron Technology   | 1         | 11.11%  |
| G.Skill             | 1         | 11.11%  |
| A-DATA Technology   | 1         | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1GB SODIMM DDR                              | 1         | 11.11%  |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 1         | 11.11%  |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 11.11%  |
| SK Hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 1         | 11.11%  |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 11.11%  |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s       | 1         | 11.11%  |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s          | 1         | 11.11%  |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s         | 1         | 11.11%  |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 4         | 50%     |
| LPDDR4 | 1         | 12.5%   |
| DDR3   | 1         | 12.5%   |
| DDR2   | 1         | 12.5%   |
| DDR    | 1         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 6         | 85.71%  |
| Row Of Chips | 1         | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 3         | 42.86%  |
| 32768 | 1         | 14.29%  |
| 16384 | 1         | 14.29%  |
| 8192  | 1         | 14.29%  |
| 1024  | 1         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 2         | 25%     |
| 4267    | 1         | 12.5%   |
| 2667    | 1         | 12.5%   |
| 2133    | 1         | 12.5%   |
| 1333    | 1         | 12.5%   |
| 667     | 1         | 12.5%   |
| Unknown | 1         | 12.5%   |

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
| Quanta                                 | 4         | 28.57%  |
| Realtek Semiconductor                  | 3         | 21.43%  |
| Sunplus Innovation Technology          | 2         | 14.29%  |
| Chicony Electronics                    | 2         | 14.29%  |
| Logitech                               | 1         | 7.14%   |
| IMC Networks                           | 1         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Quanta HD User Facing                                           | 2         | 14.29%  |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 7.14%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 7.14%   |
| Realtek Laptop Camera                                           | 1         | 7.14%   |
| Realtek Integrated Webcam_HD                                    | 1         | 7.14%   |
| Realtek Integrated Webcam                                       | 1         | 7.14%   |
| Quanta VGA WebCam                                               | 1         | 7.14%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 7.14%   |
| Logitech Webcam C270                                            | 1         | 7.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 7.14%   |
| Chicony Sony Visual Communication Camera                        | 1         | 7.14%   |
| Chicony EasyCamera                                              | 1         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| AuthenTec        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Validity Sensors VFS Fingerprint sensor | 1         | 50%     |
| AuthenTec Fingerprint Sensor            | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 10        | 62.5%   |
| 2     | 3         | 18.75%  |
| 1     | 3         | 18.75%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 3         | 30%     |
| Chipcard              | 3         | 30%     |
| Fingerprint reader    | 2         | 20%     |
| Storage               | 1         | 10%     |
| Multimedia controller | 1         | 10%     |

