Solus 4.3 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Solus 4.3.

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

Total: 30

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | Z50-70 20354                | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| Dell      | XPS 13 7390                 | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Lenovo    | ThinkPad T15 Gen 2i 20W4... | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Lenovo    | ThinkPad T15 Gen 2i 20W4... | [28c8bc52b8](https://linux-hardware.org/?probe=28c8bc52b8) | Mar 22, 2022 |
| Lenovo    | ThinkPad T15 Gen 2i 20W4... | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Dell      | XPS 13 9380                 | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
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
| 5.14.21-210.current | 3         | 15%     |
| 5.13.1-187.current  | 3         | 15%     |
| 5.15.32-213.current | 2         | 10%     |
| 5.14.16-205.current | 2         | 10%     |
| 5.13.6-190.current  | 2         | 10%     |
| 5.13.12-193.current | 2         | 10%     |
| 5.15.26-211.current | 1         | 5%      |
| 5.14.7-198.current  | 1         | 5%      |
| 5.14.16-204.current | 1         | 5%      |
| 5.14.15-203.current | 1         | 5%      |
| 5.14.12-201.current | 1         | 5%      |
| 5.13.15-194.current | 1         | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.21 | 3         | 15%     |
| 5.14.16 | 3         | 15%     |
| 5.13.1  | 3         | 15%     |
| 5.15.32 | 2         | 10%     |
| 5.13.6  | 2         | 10%     |
| 5.13.12 | 2         | 10%     |
| 5.15.26 | 1         | 5%      |
| 5.14.7  | 1         | 5%      |
| 5.14.15 | 1         | 5%      |
| 5.14.12 | 1         | 5%      |
| 5.13.15 | 1         | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 9         | 45%     |
| 5.13    | 8         | 40%     |
| 5.15    | 3         | 15%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 20        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 10        | 50%     |
| Unknown | 3         | 15%     |
| MATE    | 2         | 10%     |
| KDE     | 2         | 10%     |
| GNOME   | 2         | 10%     |
| KDE5    | 1         | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 20        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 75%     |
| LightDM | 3         | 15%     |
| SDDM    | 1         | 5%      |
| GDM     | 1         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 13        | 65%     |
| en_GB | 3         | 15%     |
| de_DE | 2         | 10%     |
| pt_BR | 1         | 5%      |
| en_IN | 1         | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 16        | 80%     |
| BIOS | 4         | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 20        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 70%     |
| GPT     | 6         | 30%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 75%     |
| Yes       | 5         | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell             | 7         | 35%     |
| Lenovo           | 3         | 15%     |
| Acer             | 3         | 15%     |
| Toshiba          | 1         | 5%      |
| Sony             | 1         | 5%      |
| Hewlett-Packard  | 1         | 5%      |
| Google           | 1         | 5%      |
| Framework        | 1         | 5%      |
| AZW              | 1         | 5%      |
| ASUSTek Computer | 1         | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba TECRA R840                     | 1         | 5%      |
| Sony VPCYB15AB                         | 1         | 5%      |
| Lenovo Z50-70 20354                    | 1         | 5%      |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW  | 1         | 5%      |
| Lenovo IdeaPad 320-15ISK 80XH          | 1         | 5%      |
| HP OMEN Laptop 15-en0xxx               | 1         | 5%      |
| Google Delbin                          | 1         | 5%      |
| Framework Laptop                       | 1         | 5%      |
| Dell XPS 13 9380                       | 1         | 5%      |
| Dell XPS 13 7390                       | 1         | 5%      |
| Dell Vostro 15-3568                    | 1         | 5%      |
| Dell Latitude E6220                    | 1         | 5%      |
| Dell Latitude 5580                     | 1         | 5%      |
| Dell Inspiron 1525                     | 1         | 5%      |
| Dell Inspiron 15-3573                  | 1         | 5%      |
| AZW SEi                                | 1         | 5%      |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 1         | 5%      |
| Acer Swift SF114-34                    | 1         | 5%      |
| Acer Nitro AN515-45                    | 1         | 5%      |
| Acer Aspire A315-54                    | 1         | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell XPS         | 2         | 10%     |
| Dell Latitude    | 2         | 10%     |
| Dell Inspiron    | 2         | 10%     |
| Toshiba TECRA    | 1         | 5%      |
| Sony VPCYB15AB   | 1         | 5%      |
| Lenovo Z50-70    | 1         | 5%      |
| Lenovo ThinkPad  | 1         | 5%      |
| Lenovo IdeaPad   | 1         | 5%      |
| HP OMEN          | 1         | 5%      |
| Google Delbin    | 1         | 5%      |
| Framework Laptop | 1         | 5%      |
| Dell Vostro      | 1         | 5%      |
| AZW SEi          | 1         | 5%      |
| ASUS VivoBook    | 1         | 5%      |
| Acer Swift       | 1         | 5%      |
| Acer Nitro       | 1         | 5%      |
| Acer Aspire      | 1         | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 4         | 20%     |
| 2020 | 3         | 15%     |
| 2019 | 3         | 15%     |
| 2018 | 2         | 10%     |
| 2017 | 2         | 10%     |
| 2011 | 2         | 10%     |
| 2016 | 1         | 5%      |
| 2014 | 1         | 5%      |
| 2010 | 1         | 5%      |
| 2008 | 1         | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 20        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 20        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 95%     |
| Yes  | 1         | 5%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 6         | 30%     |
| 32.01-64.0 | 3         | 15%     |
| 3.01-4.0   | 3         | 15%     |
| 16.01-24.0 | 3         | 15%     |
| 8.01-16.0  | 3         | 15%     |
| 2.01-3.0   | 1         | 5%      |
| 1.01-2.0   | 1         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 10        | 50%     |
| 1.01-2.0 | 4         | 20%     |
| 3.01-4.0 | 3         | 15%     |
| 4.01-8.0 | 2         | 10%     |
| 0.51-1.0 | 1         | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 80%     |
| 2      | 4         | 20%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 75%     |
| Yes       | 5         | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 70%     |
| No        | 6         | 30%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 85%     |
| No        | 3         | 15%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 4         | 20%     |
| India       | 3         | 15%     |
| UK          | 2         | 10%     |
| Netherlands | 2         | 10%     |
| Brazil      | 2         | 10%     |
| Vietnam     | 1         | 5%      |
| Switzerland | 1         | 5%      |
| Poland      | 1         | 5%      |
| Nepal       | 1         | 5%      |
| Germany     | 1         | 5%      |
| Belgium     | 1         | 5%      |
| Australia   | 1         | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Zoutleeuw         | 1         | 5%      |
| Yverdon-les-Bains | 1         | 5%      |
| Vineland          | 1         | 5%      |
| Red Oak           | 1         | 5%      |
| NieporÄ™t      | 1         | 5%      |
| Navelim           | 1         | 5%      |
| Naaldwijk         | 1         | 5%      |
| Mohali            | 1         | 5%      |
| Milwaukee         | 1         | 5%      |
| Melbourne         | 1         | 5%      |
| Kathmandu         | 1         | 5%      |
| Hanoi             | 1         | 5%      |
| Groningen         | 1         | 5%      |
| Greenwich         | 1         | 5%      |
| GoiÃ¢nia        | 1         | 5%      |
| Duisburg          | 1         | 5%      |
| Dagenham          | 1         | 5%      |
| Coimbatore        | 1         | 5%      |
| Belo Horizonte    | 1         | 5%      |
| Anacortes         | 1         | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 12.5%   |
| SK Hynix            | 3         | 3      | 12.5%   |
| Sandisk             | 3         | 4      | 12.5%   |
| Samsung Electronics | 3         | 4      | 12.5%   |
| Unknown             | 2         | 2      | 8.33%   |
| Toshiba             | 2         | 2      | 8.33%   |
| Seagate             | 2         | 2      | 8.33%   |
| Silicon Motion      | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| KIOXIA              | 1         | 1      | 4.17%   |
| Kingston            | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Advantech           | 1         | 1      | 4.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Sandisk NVMe SSD Drive 256GB           | 2         | 7.69%   |
| WDC WD3200BEVT-75ZCT2 320GB            | 1         | 3.85%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 3.85%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 3.85%   |
| Unknown USB DISK 3.2 500GB             | 1         | 3.85%   |
| Unknown MMC Card  128GB                | 1         | 3.85%   |
| Toshiba MQ01ABF050 500GB               | 1         | 3.85%   |
| Toshiba KXG60ZNV512G NVMe 512GB        | 1         | 3.85%   |
| SK Hynix NVMe SSD Drive 500GB          | 1         | 3.85%   |
| SK Hynix NVMe SSD Drive 256GB          | 1         | 3.85%   |
| SK Hynix NVMe SSD Drive 128GB          | 1         | 3.85%   |
| Silicon Motion NVMe SSD Drive 512GB    | 1         | 3.85%   |
| Seagate ST1000LM049-2GH172 1TB         | 1         | 3.85%   |
| Seagate ST1000LM035-1RK172 1TB         | 1         | 3.85%   |
| Sandisk NVMe SSD Drive 1TB             | 1         | 3.85%   |
| SanDisk Extreme Pro 1TB                | 1         | 3.85%   |
| Samsung SSD 850 EVO 250GB              | 1         | 3.85%   |
| Samsung NVMe SSD Drive 512GB           | 1         | 3.85%   |
| Samsung NVMe SSD Drive 2TB             | 1         | 3.85%   |
| Samsung MZVL22T0HBLB-00BL7 2TB         | 1         | 3.85%   |
| PNY CS900 240GB SSD                    | 1         | 3.85%   |
| KIOXIA KXG60ZNV512G NVMe 512GB         | 1         | 3.85%   |
| Kingston SA400S37240G 240GB SSD        | 1         | 3.85%   |
| Intel NVMe SSD Drive 512GB             | 1         | 3.85%   |
| Advantech SQF-S25M8-128G-AAG 128GB SSD | 1         | 3.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 50%     |
| Seagate | 2         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |

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
| NVMe    | 11        | 14     | 47.83%  |
| HDD     | 6         | 6      | 26.09%  |
| SSD     | 4         | 4      | 17.39%  |
| MMC     | 1         | 1      | 4.35%   |
| Unknown | 1         | 1      | 4.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 11        | 14     | 47.83%  |
| SATA | 10        | 10     | 43.48%  |
| SAS  | 1         | 1      | 4.35%   |
| MMC  | 1         | 1      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 6         | 6      | 60%     |
| 0.51-1.0   | 4         | 4      | 40%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 8         | 40%     |
| 251-500    | 6         | 30%     |
| 501-1000   | 4         | 20%     |
| 21-50      | 1         | 5%      |
| 51-100     | 1         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 10        | 50%     |
| 21-50   | 4         | 20%     |
| 51-100  | 3         | 15%     |
| 101-250 | 2         | 10%     |
| 251-500 | 1         | 5%      |

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
| Detected | 16        | 20     | 72.73%  |
| Works    | 6         | 6      | 27.27%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 11        | 42.31%  |
| AMD                          | 4         | 15.38%  |
| SK Hynix                     | 3         | 11.54%  |
| Sandisk                      | 3         | 11.54%  |
| Toshiba America Info Systems | 2         | 7.69%   |
| Samsung Electronics          | 2         | 7.69%   |
| Silicon Motion               | 1         | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 11.11%  |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 2         | 7.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 7.41%   |
| SK Hynix PC300 NVMe Solid State Drive 256GB                                   | 1         | 3.7%    |
| SK Hynix Gold P31 SSD                                                         | 1         | 3.7%    |
| SK Hynix BC501 NVMe Solid State Drive                                         | 1         | 3.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 3.7%    |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1         | 3.7%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 3.7%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 3.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 3.7%    |
| Intel SSD 660P Series                                                         | 1         | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 3.7%    |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 3.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 3.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 3.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 3.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 3.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1         | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 13        | 50%     |
| NVMe | 11        | 42.31%  |
| RAID | 1         | 3.85%   |
| IDE  | 1         | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 16        | 80%     |
| AMD    | 4         | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 10%     |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 10%     |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 5%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 5%      |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 5%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 5%      |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 5%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 5%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 5%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 5%      |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 5%      |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 5%      |
| Intel Celeron CPU 540 @ 1.86GHz               | 1         | 5%      |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 5%      |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 5%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 5%      |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 5%      |
| AMD E-350 Processor                           | 1         | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 5         | 25%     |
| Intel Core i5        | 4         | 20%     |
| Other                | 3         | 15%     |
| Intel Celeron        | 2         | 10%     |
| AMD Ryzen 7          | 2         | 10%     |
| Intel Pentium Silver | 1         | 5%      |
| Intel Core i3        | 1         | 5%      |
| AMD Ryzen 5          | 1         | 5%      |
| AMD E                | 1         | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 9         | 45%     |
| 2      | 8         | 40%     |
| 8      | 1         | 5%      |
| 6      | 1         | 5%      |
| 1      | 1         | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 80%     |
| 1      | 4         | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 3         | 15%     |
| 0x806c1    | 3         | 15%     |
| 0x206a7    | 2         | 10%     |
| 0x906e9    | 1         | 5%      |
| 0x906c0    | 1         | 5%      |
| 0x806ea    | 1         | 5%      |
| 0x706a1    | 1         | 5%      |
| 0x406e3    | 1         | 5%      |
| 0x40651    | 1         | 5%      |
| 0x10661    | 1         | 5%      |
| 0x0a50000c | 1         | 5%      |
| 0x08600106 | 1         | 5%      |
| 0x08108109 | 1         | 5%      |
| 0x05000029 | 1         | 5%      |
| Unknown    | 1         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 30%     |
| TigerLake     | 3         | 15%     |
| SandyBridge   | 2         | 10%     |
| Zen+          | 1         | 5%      |
| Zen 3         | 1         | 5%      |
| Zen 2         | 1         | 5%      |
| Tremont       | 1         | 5%      |
| Skylake       | 1         | 5%      |
| Haswell       | 1         | 5%      |
| Goldmont plus | 1         | 5%      |
| Core          | 1         | 5%      |
| Bobcat        | 1         | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 60%     |
| AMD    | 6         | 24%     |
| Nvidia | 4         | 16%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 7.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 7.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 3.85%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 3.85%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 3.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 3.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 3.85%   |
| Intel Tiger Lake UHD Graphics                                             | 1         | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 3.85%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 3.85%   |
| Intel HD Graphics 630                                                     | 1         | 3.85%   |
| Intel HD Graphics 620                                                     | 1         | 3.85%   |
| Intel HD Graphics 520                                                     | 1         | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 3.85%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 3.85%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 1         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 3.85%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 3.85%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                    | 1         | 3.85%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 3.85%   |
| AMD Renoir                                                                | 1         | 3.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 3.85%   |
| AMD Cezanne                                                               | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 60%     |
| 1 x AMD        | 3         | 15%     |
| Intel + Nvidia | 2         | 10%     |
| AMD + Nvidia   | 2         | 10%     |
| Intel + AMD    | 1         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 17        | 85%     |
| Proprietary | 3         | 15%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 65%     |
| 1.01-2.0   | 2         | 10%     |
| 0.01-0.5   | 2         | 10%     |
| 5.01-6.0   | 1         | 5%      |
| 3.01-4.0   | 1         | 5%      |
| 0.51-1.0   | 1         | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 6         | 26.09%  |
| Samsung Electronics     | 3         | 13.04%  |
| BOE                     | 3         | 13.04%  |
| LG Display              | 2         | 8.7%    |
| AU Optronics            | 2         | 8.7%    |
| Toshiba                 | 1         | 4.35%   |
| Philips                 | 1         | 4.35%   |
| PANDA                   | 1         | 4.35%   |
| Lenovo                  | 1         | 4.35%   |
| CSO                     | 1         | 4.35%   |
| Chi Mei Optoelectronics | 1         | 4.35%   |
| Acer                    | 1         | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Toshiba Internal LCD TOS5091 1366x768 340x190mm 15.3-inch                | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 4.17%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 4.17%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch        | 1         | 4.17%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                    | 1         | 4.17%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 4.17%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch             | 1         | 4.17%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                      | 1         | 4.17%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 4.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 1         | 4.17%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 4.17%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                    | 1         | 4.17%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch           | 1         | 4.17%   |
| Acer K242HYL ACR064A 1920x1080 527x296mm 23.8-inch                       | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 11        | 50%     |
| 1366x768 (WXGA) | 7         | 31.82%  |
| 3840x2160 (4K)  | 2         | 9.09%   |
| 2256x1504       | 1         | 4.55%   |
| 1280x800 (WXGA) | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 60.87%  |
| 13     | 3         | 13.04%  |
| 27     | 2         | 8.7%    |
| 23     | 1         | 4.35%   |
| 21     | 1         | 4.35%   |
| 14     | 1         | 4.35%   |
| 11     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 60.87%  |
| 201-300     | 4         | 17.39%  |
| 501-600     | 3         | 13.04%  |
| 401-500     | 1         | 4.35%   |
| 351-400     | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 90%     |
| 3/2   | 1         | 5%      |
| 16/10 | 1         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 60.87%  |
| 81-90          | 2         | 8.7%    |
| 71-80          | 2         | 8.7%    |
| 301-350        | 2         | 8.7%    |
| 51-60          | 1         | 4.35%   |
| 201-250        | 1         | 4.35%   |
| 151-200        | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 8         | 38.1%   |
| 101-120       | 5         | 23.81%  |
| 51-100        | 4         | 19.05%  |
| More than 240 | 2         | 9.52%   |
| 161-240       | 2         | 9.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 85%     |
| 2     | 2         | 10%     |
| 3     | 1         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 11        | 37.93%  |
| Realtek Semiconductor    | 8         | 27.59%  |
| Qualcomm Atheros         | 5         | 17.24%  |
| TP-Link                  | 1         | 3.45%   |
| MEDIATEK                 | 1         | 3.45%   |
| Marvell Technology Group | 1         | 3.45%   |
| Dell                     | 1         | 3.45%   |
| Broadcom                 | 1         | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 17.14%  |
| Intel Wi-Fi 6 AX200                                               | 3         | 8.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 5.71%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.71%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2.86%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.86%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 2.86%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.86%   |
| Intel Wireless 8265 / 8275                                        | 1         | 2.86%   |
| Intel Wireless 3165                                               | 1         | 2.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2.86%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 2.86%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.86%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.86%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2.86%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 2.86%   |
| Dell DW5550                                                       | 1         | 2.86%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 1         | 2.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 55%     |
| Qualcomm Atheros      | 5         | 25%     |
| Realtek Semiconductor | 2         | 10%     |
| MEDIATEK              | 1         | 5%      |
| Broadcom              | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3         | 15%     |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 10%     |
| Intel Wi-Fi 6 AX201                                            | 2         | 10%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 5%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 5%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 5%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 5%      |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 5%      |
| Intel Wireless 8265 / 8275                                     | 1         | 5%      |
| Intel Wireless 3165                                            | 1         | 5%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 5%      |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 5%      |
| Intel Centrino Ultimate-N 6300                                 | 1         | 5%      |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 5%      |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 7         | 50%     |
| Intel                    | 4         | 28.57%  |
| TP-Link                  | 1         | 7.14%   |
| Qualcomm Atheros         | 1         | 7.14%   |
| Marvell Technology Group | 1         | 7.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 42.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 14.29%  |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 7.14%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 7.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 7.14%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 7.14%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 7.14%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 7.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 57.14%  |
| Ethernet | 14        | 40%     |
| Modem    | 1         | 2.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 61.54%  |
| Ethernet | 10        | 38.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 13        | 65%     |
| 1     | 7         | 35%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 14        | 70%     |
| Yes  | 6         | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 52.94%  |
| Qualcomm Atheros Communications | 2         | 11.76%  |
| Lite-On Technology              | 2         | 11.76%  |
| Realtek Semiconductor           | 1         | 5.88%   |
| IMC Networks                    | 1         | 5.88%   |
| Foxconn / Hon Hai               | 1         | 5.88%   |
| Dell                            | 1         | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel Bluetooth Device                | 3         | 17.65%  |
| Intel AX200 Bluetooth                 | 3         | 17.65%  |
| Intel Bluetooth wireless interface    | 2         | 11.76%  |
| Realtek RTL8821A Bluetooth            | 1         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device    | 1         | 5.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0 | 1         | 5.88%   |
| Lite-On Wireless_Device               | 1         | 5.88%   |
| Lite-On Bluetooth Device              | 1         | 5.88%   |
| Intel AX210 Bluetooth                 | 1         | 5.88%   |
| IMC Networks Bluetooth Radio          | 1         | 5.88%   |
| Foxconn / Hon Hai Bluetooth Device    | 1         | 5.88%   |
| Dell DW375 Bluetooth Module           | 1         | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 16        | 61.54%  |
| AMD                 | 5         | 19.23%  |
| Nvidia              | 3         | 11.54%  |
| Samsung Electronics | 1         | 3.85%   |
| Conexant Systems    | 1         | 3.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 10.34%  |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 10.34%  |
| Intel Sunrise Point-LP HD Audio                                                   | 2         | 6.9%    |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 6.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2         | 6.9%    |
| Samsung Electronics USBC Headset                                                  | 1         | 3.45%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 3.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1         | 3.45%   |
| Nvidia Audio device                                                               | 1         | 3.45%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 3.45%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 3.45%   |
| Intel CM238 HD Audio Controller                                                   | 1         | 3.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1         | 3.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1         | 3.45%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 3.45%   |
| Conexant Systems Hi-Res Audio                                                     | 1         | 3.45%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 3.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 3.45%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 30.77%  |
| SK Hynix            | 3         | 23.08%  |
| Micron Technology   | 2         | 15.38%  |
| Unknown             | 1         | 7.69%   |
| Team                | 1         | 7.69%   |
| G.Skill             | 1         | 7.69%   |
| A-DATA Technology   | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 7.69%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 7.69%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 7.69%   |
| SK Hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 7.69%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 7.69%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 7.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 7.69%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 7.69%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 7.69%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 7.69%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 7.69%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 7.69%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 7.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 5         | 45.45%  |
| LPDDR3 | 2         | 18.18%  |
| LPDDR4 | 1         | 9.09%   |
| DDR3   | 1         | 9.09%   |
| DDR2   | 1         | 9.09%   |
| DDR    | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 7         | 70%     |
| Row Of Chips | 3         | 30%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 3         | 30%     |
| 4096  | 3         | 30%     |
| 16384 | 2         | 20%     |
| 32768 | 1         | 10%     |
| 1024  | 1         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 3         | 27.27%  |
| 2133    | 3         | 27.27%  |
| 4267    | 1         | 9.09%   |
| 2667    | 1         | 9.09%   |
| 1333    | 1         | 9.09%   |
| 667     | 1         | 9.09%   |
| Unknown | 1         | 9.09%   |

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
| Quanta                                 | 4         | 22.22%  |
| Realtek Semiconductor                  | 3         | 16.67%  |
| Sunplus Innovation Technology          | 2         | 11.11%  |
| Microdia                               | 2         | 11.11%  |
| IMC Networks                           | 2         | 11.11%  |
| Chicony Electronics                    | 2         | 11.11%  |
| Logitech                               | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.56%   |
| Acer                                   | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Quanta HD User Facing                                           | 2         | 11.11%  |
| Microdia Integrated_Webcam_HD                                   | 2         | 11.11%  |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 5.56%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 5.56%   |
| Realtek Laptop Camera                                           | 1         | 5.56%   |
| Realtek Integrated Webcam_HD                                    | 1         | 5.56%   |
| Realtek Integrated Webcam                                       | 1         | 5.56%   |
| Quanta VGA WebCam                                               | 1         | 5.56%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 5.56%   |
| Logitech Webcam C270                                            | 1         | 5.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 5.56%   |
| IMC Networks Integrated Camera                                  | 1         | 5.56%   |
| Chicony Sony Visual Communication Camera                        | 1         | 5.56%   |
| Chicony EasyCamera                                              | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 5.56%   |
| Acer Lenovo EasyCamera                                          | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 33.33%  |
| Synaptics        | 1         | 33.33%  |
| AuthenTec        | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS Fingerprint sensor           | 1         | 33.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 33.33%  |
| AuthenTec Fingerprint Sensor                      | 1         | 33.33%  |

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
| 0     | 13        | 65%     |
| 2     | 4         | 20%     |
| 1     | 3         | 15%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 3         | 25%     |
| Fingerprint reader    | 3         | 25%     |
| Chipcard              | 3         | 25%     |
| Unassigned class      | 1         | 8.33%   |
| Storage               | 1         | 8.33%   |
| Multimedia controller | 1         | 8.33%   |

