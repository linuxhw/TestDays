Ubuntu 21.10 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | ROG Strix G533QS_G533QS     | [b8aa2e41d5](https://linux-hardware.org/?probe=b8aa2e41d5) | Aug 16, 2021 |
| ASUSTek  | ROG Strix G533QS_G533QS     | [612dda8fba](https://linux-hardware.org/?probe=612dda8fba) | Aug 13, 2021 |
| ASUSTek  | ROG Strix G533QS_G533QS     | [1eb6008b88](https://linux-hardware.org/?probe=1eb6008b88) | Aug 13, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | [808cfab06b](https://linux-hardware.org/?probe=808cfab06b) | Aug 12, 2021 |
| Lenovo   | ThinkPad T510 4484A63       | [c1bcb3451f](https://linux-hardware.org/?probe=c1bcb3451f) | Aug 09, 2021 |
| Lenovo   | ThinkPad T510 4484A63       | [4336b50906](https://linux-hardware.org/?probe=4336b50906) | Aug 06, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X530... | [961031411d](https://linux-hardware.org/?probe=961031411d) | Aug 03, 2021 |
| Lenovo   | ZhaoYang K3-ITL 82E3        | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| ASUSTek  | GL753VD                     | [eabe6a8723](https://linux-hardware.org/?probe=eabe6a8723) | Jul 31, 2021 |
| Acer     | Aspire 5920                 | [f41defe215](https://linux-hardware.org/?probe=f41defe215) | Jul 31, 2021 |
| Dell     | XPS 13 7390                 | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| Teclast  | F6 Pro                      | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X421... | [f5458b4f56](https://linux-hardware.org/?probe=f5458b4f56) | Jul 19, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X421... | [5ac65f3389](https://linux-hardware.org/?probe=5ac65f3389) | Jul 18, 2021 |
| Lenovo   | Z50-70 20354                | [85aadf8abd](https://linux-hardware.org/?probe=85aadf8abd) | Jul 16, 2021 |
| Lenovo   | Z50-70 20354                | [b2c80f450e](https://linux-hardware.org/?probe=b2c80f450e) | Jul 14, 2021 |
| HP       | Pavilion Gaming Laptop 1... | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo   | ThinkPad X201 3626FAG       | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Positivo | H14BT58                     | [51b9ba65e0](https://linux-hardware.org/?probe=51b9ba65e0) | Jun 18, 2021 |
| ASUSTek  | ROG Strix G533QR_G533QR     | [4befd5f360](https://linux-hardware.org/?probe=4befd5f360) | Jun 04, 2021 |
| Dell     | XPS 13 9343                 | [4ee08e92ae](https://linux-hardware.org/?probe=4ee08e92ae) | May 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.11.0-20-generic     | 4         | 26.67%  |
| 5.11.0-25-generic     | 2         | 13.33%  |
| 5.11.0-18-generic     | 2         | 13.33%  |
| 5.13.6-xanmod2-edge   | 1         | 6.67%   |
| 5.13.4-051304-generic | 1         | 6.67%   |
| 5.13.2-051302-generic | 1         | 6.67%   |
| 5.13.0-13-generic     | 1         | 6.67%   |
| 5.11.0-26-generic     | 1         | 6.67%   |
| 5.11.0-22-generic     | 1         | 6.67%   |
| 5.11.0-16-generic     | 1         | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 11        | 73.33%  |
| 5.13.6  | 1         | 6.67%   |
| 5.13.4  | 1         | 6.67%   |
| 5.13.2  | 1         | 6.67%   |
| 5.13.0  | 1         | 6.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 11        | 73.33%  |
| 5.13    | 4         | 26.67%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 15        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 10        | 66.67%  |
| X-Cinnamon      | 2         | 13.33%  |
| Unity           | 1         | 6.67%   |
| GNOME Flashback | 1         | 6.67%   |
| Cinnamon        | 1         | 6.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 9         | 60%     |
| X11     | 6         | 40%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 7         | 46.67%  |
| Unknown | 7         | 46.67%  |
| TDM     | 1         | 6.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_GB | 5         | 33.33%  |
| fr_FR | 3         | 20%     |
| zh_CN | 1         | 6.67%   |
| sv_SE | 1         | 6.67%   |
| ru_RU | 1         | 6.67%   |
| pt_BR | 1         | 6.67%   |
| ko_KR | 1         | 6.67%   |
| es_MX | 1         | 6.67%   |
| en_US | 1         | 6.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 8         | 53.33%  |
| BIOS | 7         | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 15        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 7         | 46.67%  |
| Unknown | 7         | 46.67%  |
| MBR     | 1         | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10        | 66.67%  |
| Yes       | 5         | 33.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 8         | 53.33%  |
| Yes       | 7         | 46.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 6         | 40%     |
| Lenovo           | 3         | 20%     |
| Dell             | 2         | 13.33%  |
| Teclast          | 1         | 6.67%   |
| Positivo         | 1         | 6.67%   |
| Hewlett-Packard  | 1         | 6.67%   |
| Acer             | 1         | 6.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Teclast F6 Pro                          | 1         | 6.67%   |
| Positivo H14BT58                        | 1         | 6.67%   |
| Lenovo ZhaoYang K3-ITL 82E3             | 1         | 6.67%   |
| Lenovo Z50-70 20354                     | 1         | 6.67%   |
| Lenovo ThinkPad X201 3626FAG            | 1         | 6.67%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 6.67%   |
| Dell XPS 13 9343                        | 1         | 6.67%   |
| Dell XPS 13 7390                        | 1         | 6.67%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN  | 1         | 6.67%   |
| ASUS VivoBook_ASUSLaptop X509DJ_M509DJ  | 1         | 6.67%   |
| ASUS VivoBook_ASUSLaptop X421UAY_M413UA | 1         | 6.67%   |
| ASUS ROG Strix G533QS_G533QS            | 1         | 6.67%   |
| ASUS ROG Strix G533QR_G533QR            | 1         | 6.67%   |
| ASUS GL753VD                            | 1         | 6.67%   |
| Acer Aspire 5920                        | 1         | 6.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUS VivoBook    | 3         | 20%     |
| Dell XPS         | 2         | 13.33%  |
| ASUS ROG         | 2         | 13.33%  |
| Teclast F6       | 1         | 6.67%   |
| Positivo H14BT58 | 1         | 6.67%   |
| Lenovo ZhaoYang  | 1         | 6.67%   |
| Lenovo Z50-70    | 1         | 6.67%   |
| Lenovo ThinkPad  | 1         | 6.67%   |
| HP Pavilion      | 1         | 6.67%   |
| ASUS GL753VD     | 1         | 6.67%   |
| Acer Aspire      | 1         | 6.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 6         | 40%     |
| 2020 | 2         | 13.33%  |
| 2019 | 2         | 13.33%  |
| 2018 | 1         | 6.67%   |
| 2015 | 1         | 6.67%   |
| 2014 | 1         | 6.67%   |
| 2010 | 1         | 6.67%   |
| 2008 | 1         | 6.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 15        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 14        | 93.33%  |
| Enabled  | 1         | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 15        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 5         | 33.33%  |
| 8.01-16.0  | 3         | 20%     |
| 32.01-64.0 | 2         | 13.33%  |
| 16.01-24.0 | 2         | 13.33%  |
| 3.01-4.0   | 1         | 6.67%   |
| 24.01-32.0 | 1         | 6.67%   |
| 1.01-2.0   | 1         | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 7         | 46.67%  |
| 4.01-8.0 | 4         | 26.67%  |
| 1.01-2.0 | 4         | 26.67%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 10        | 66.67%  |
| 2      | 3         | 20%     |
| 3      | 2         | 13.33%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 86.67%  |
| Yes       | 2         | 13.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8         | 53.33%  |
| No        | 7         | 46.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 80%     |
| No        | 3         | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| UK          | 4         | 26.67%  |
| France      | 3         | 20%     |
| USA         | 1         | 6.67%   |
| Sweden      | 1         | 6.67%   |
| South Korea | 1         | 6.67%   |
| Russia      | 1         | 6.67%   |
| Germany     | 1         | 6.67%   |
| China       | 1         | 6.67%   |
| Chile       | 1         | 6.67%   |
| Brazil      | 1         | 6.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Yongin-si              | 1         | 6.67%   |
| Tottenham              | 1         | 6.67%   |
| Shanghai               | 1         | 6.67%   |
| Santiago               | 1         | 6.67%   |
| Rio de Janeiro         | 1         | 6.67%   |
| Paris                  | 1         | 6.67%   |
| Nizhny Tagil           | 1         | 6.67%   |
| Maidstone              | 1         | 6.67%   |
| Lyon                   | 1         | 6.67%   |
| Helsingborg            | 1         | 6.67%   |
| Haselhorst             | 1         | 6.67%   |
| Glasgow                | 1         | 6.67%   |
| Crewe                  | 1         | 6.67%   |
| Charleville-M?�zi??res | 1         | 6.67%   |
| Austin                 | 1         | 6.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 19.05%  |
| Seagate             | 3         | 3      | 14.29%  |
| SK Hynix            | 2         | 2      | 9.52%   |
| SanDisk             | 2         | 2      | 9.52%   |
| Intel               | 2         | 3      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| Unknown             | 1         | 1      | 4.76%   |
| Toshiba             | 1         | 1      | 4.76%   |
| SP                  | 1         | 1      | 4.76%   |
| LITEON              | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| KingDian            | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix HFM001TD3JX013N 1TB            | 2         | 9.09%   |
| Seagate Expansion 1TB                   | 2         | 9.09%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 4.55%   |
| Unknown SB64G  64GB                     | 1         | 4.55%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 4.55%   |
| SP PC60 1TB                             | 1         | 4.55%   |
| Seagate ST9320423AS 320GB               | 1         | 4.55%   |
| SanDisk SD9SN8W256G1102 256GB SSD       | 1         | 4.55%   |
| Sandisk NVMe SSD Drive 500GB            | 1         | 4.55%   |
| Samsung SSD 970 EVO 500GB               | 1         | 4.55%   |
| Samsung SSD 850 EVO 500GB               | 1         | 4.55%   |
| Samsung MZVLQ512HALU-00000 512GB        | 1         | 4.55%   |
| Samsung MZALQ512HALU-000L2 512GB        | 1         | 4.55%   |
| LITEON L8H-256V2G-11 M.2 2280 256GB SSD | 1         | 4.55%   |
| Kingston SKC300S37A240G 240GB SSD       | 1         | 4.55%   |
| KingDian N400 240GB SSD                 | 1         | 4.55%   |
| Intel NVMe SSD Drive 512GB              | 1         | 4.55%   |
| Intel HBRPEKNX0101AHO 16GB              | 1         | 4.55%   |
| Intel HBRPEKNX0101AH 256GB              | 1         | 4.55%   |
| HGST HTS721010A9E630 1TB                | 1         | 4.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| WDC     | 1         | 1      | 16.67%  |
| Toshiba | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| LITEON              | 1         | 1      | 20%     |
| Kingston            | 1         | 1      | 20%     |
| KingDian            | 1         | 1      | 20%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 8         | 9      | 38.1%   |
| HDD     | 6         | 6      | 28.57%  |
| SSD     | 5         | 5      | 23.81%  |
| MMC     | 1         | 1      | 4.76%   |
| Unknown | 1         | 1      | 4.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 8         | 9      | 42.11%  |
| SATA | 8         | 9      | 42.11%  |
| SAS  | 2         | 3      | 10.53%  |
| MMC  | 1         | 1      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7         | 7      | 63.64%  |
| 0.51-1.0   | 4         | 4      | 36.36%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 4         | 26.67%  |
| 101-250    | 4         | 26.67%  |
| 51-100     | 3         | 20%     |
| 1001-2000  | 2         | 13.33%  |
| 21-50      | 1         | 6.67%   |
| 501-1000   | 1         | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 3         | 20%     |
| 101-250  | 3         | 20%     |
| 1-20     | 3         | 20%     |
| 51-100   | 3         | 20%     |
| 501-1000 | 2         | 13.33%  |
| 251-500  | 1         | 6.67%   |

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
| Detected | 10        | 13     | 55.56%  |
| Works    | 8         | 9      | 44.44%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 10        | 55.56%  |
| Samsung Electronics | 3         | 16.67%  |
| SK Hynix            | 2         | 11.11%  |
| AMD                 | 2         | 11.11%  |
| Sandisk             | 1         | 5.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Controller                                   | 2         | 10%     |
| Samsung NVMe Controller                                        | 2         | 10%     |
| Intel 82801 Mobile SATA Controller [RAID mode]                 | 2         | 10%     |
| AMD FCH SATA Controller [AHCI mode]                            | 2         | 10%     |
| Sandisk WD Blue SN550 NVMe SSD                                 | 1         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                  | 1         | 5%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]             | 1         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]             | 1         | 5%      |
| Intel SSD 660P Series                                          | 1         | 5%      |
| Intel Non-Volatile memory controller                           | 1         | 5%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]          | 1         | 5%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller         | 1         | 5%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]  | 1         | 5%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller               | 1         | 5%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                   | 1         | 5%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller | 1         | 5%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 9         | 45%     |
| NVMe | 8         | 40%     |
| RAID | 2         | 10%     |
| IDE  | 1         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 11        | 73.33%  |
| AMD    | 4         | 26.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 13.33%  |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 6.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 6.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 6.67%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 6.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 6.67%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 6.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 6.67%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 6.67%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 6.67%   |
| Intel Celeron CPU N2807 @ 1.58GHz             | 1         | 6.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 6.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 6.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 6.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 4         | 26.67%  |
| Intel Core i5    | 3         | 20%     |
| AMD Ryzen 9      | 2         | 13.33%  |
| AMD Ryzen 5      | 2         | 13.33%  |
| Other            | 1         | 6.67%   |
| Intel Core m3    | 1         | 6.67%   |
| Intel Core 2 Duo | 1         | 6.67%   |
| Intel Celeron    | 1         | 6.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 6         | 40%     |
| 2      | 6         | 40%     |
| 8      | 2         | 13.33%  |
| 6      | 1         | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 15        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 86.67%  |
| 1      | 2         | 13.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 15        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 46.67%  |
| 0x906ea    | 1         | 6.67%   |
| 0x806ec    | 1         | 6.67%   |
| 0x806eb    | 1         | 6.67%   |
| 0x806e9    | 1         | 6.67%   |
| 0x806c1    | 1         | 6.67%   |
| 0x306d4    | 1         | 6.67%   |
| 0x0a50000b | 1         | 6.67%   |
| 0x08608103 | 1         | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KabyLake   | 5         | 33.33%  |
| Zen 3      | 2         | 13.33%  |
| Zen+       | 1         | 6.67%   |
| Westmere   | 1         | 6.67%   |
| TigerLake  | 1         | 6.67%   |
| Silvermont | 1         | 6.67%   |
| Penryn     | 1         | 6.67%   |
| Haswell    | 1         | 6.67%   |
| Broadwell  | 1         | 6.67%   |
| Unknown    | 1         | 6.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 11        | 50%     |
| Nvidia | 7         | 31.82%  |
| AMD    | 4         | 18.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Cezanne                                                          | 2         | 8.7%    |
| Nvidia GP108M [GeForce MX230]                                        | 1         | 4.35%   |
| Nvidia GP108M [GeForce MX150]                                        | 1         | 4.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 4.35%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                          | 1         | 4.35%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M] | 1         | 4.35%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]             | 1         | 4.35%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 4.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 4.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 1         | 4.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)  | 1         | 4.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)    | 1         | 4.35%   |
| Intel HD Graphics 630                                                | 1         | 4.35%   |
| Intel HD Graphics 615                                                | 1         | 4.35%   |
| Intel HD Graphics 5500                                               | 1         | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 1         | 4.35%   |
| Intel Core Processor Integrated Graphics Controller                  | 1         | 4.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 1         | 4.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 1         | 4.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display         | 1         | 4.35%   |
| AMD Picasso                                                          | 1         | 4.35%   |
| AMD Lucienne                                                         | 1         | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 7         | 46.67%  |
| Intel + Nvidia | 4         | 26.67%  |
| AMD + Nvidia   | 3         | 20%     |
| 1 x AMD        | 1         | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 11        | 73.33%  |
| Proprietary | 4         | 26.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 73.33%  |
| 1.01-2.0   | 2         | 13.33%  |
| 0.01-0.5   | 2         | 13.33%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 3         | 17.65%  |
| AU Optronics        | 3         | 17.65%  |
| Sharp               | 2         | 11.76%  |
| Chimei Innolux      | 2         | 11.76%  |
| Acer                | 2         | 11.76%  |
| Samsung Electronics | 1         | 5.88%   |
| PANDA               | 1         | 5.88%   |
| LG Display          | 1         | 5.88%   |
| Lenovo              | 1         | 5.88%   |
| InfoVision          | 1         | 5.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Acer XV340CK P ACR06F3 3440x1440 800x335mm 34.1-inch                 | 2         | 11.76%  |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 5.88%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 1         | 5.88%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch | 1         | 5.88%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch              | 1         | 5.88%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 1         | 5.88%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 5.88%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch         | 1         | 5.88%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 1         | 5.88%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 5.88%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                | 1         | 5.88%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                | 1         | 5.88%   |
| BOE LCD Monitor BOE05EC 1366x768 309x173mm 13.9-inch                 | 1         | 5.88%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch       | 1         | 5.88%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 1         | 5.88%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 5.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 9         | 52.94%  |
| 3440x1440         | 2         | 11.76%  |
| 1280x800 (WXGA)   | 2         | 11.76%  |
| 3200x1800 (QHD+)  | 1         | 5.88%   |
| 2560x1440 (QHD)   | 1         | 5.88%   |
| 1920x1200 (WUXGA) | 1         | 5.88%   |
| 1366x768 (WXGA)   | 1         | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 7         | 41.18%  |
| 13     | 6         | 35.29%  |
| 34     | 2         | 11.76%  |
| 17     | 1         | 5.88%   |
| 12     | 1         | 5.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 52.94%  |
| 201-300     | 5         | 29.41%  |
| 701-800     | 2         | 11.76%  |
| 351-400     | 1         | 5.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 12        | 70.59%  |
| 21/9  | 2         | 11.76%  |
| 16/10 | 2         | 11.76%  |
| 3/2   | 1         | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 41.18%  |
| 71-80          | 4         | 23.53%  |
| 81-90          | 2         | 11.76%  |
| 351-500        | 2         | 11.76%  |
| 61-70          | 1         | 5.88%   |
| 121-130        | 1         | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 8         | 47.06%  |
| 161-240       | 4         | 23.53%  |
| 101-120       | 3         | 17.65%  |
| More than 240 | 1         | 5.88%   |
| 51-100        | 1         | 5.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 13        | 86.67%  |
| 2     | 2         | 13.33%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 8         | 38.1%   |
| Intel                 | 7         | 33.33%  |
| MEDIATEK              | 2         | 9.52%   |
| Xiaomi                | 1         | 4.76%   |
| Qualcomm Atheros      | 1         | 4.76%   |
| Broadcom Limited      | 1         | 4.76%   |
| Broadcom              | 1         | 4.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 25%     |
| MEDIATEK Network controller                                       | 2         | 8.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 4.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 4.17%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 4.17%   |
| Intel Wireless 8265 / 8275                                        | 1         | 4.17%   |
| Intel Wireless 7265                                               | 1         | 4.17%   |
| Intel Wireless 3165                                               | 1         | 4.17%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 4.17%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 4.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 4.17%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 4.17%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 4.17%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 4.17%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
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


| Model                                                      | Notebooks | Percent |
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


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 6         | 66.67%  |
| Xiaomi                | 1         | 11.11%  |
| Intel                 | 1         | 11.11%  |
| Broadcom              | 1         | 11.11%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 66.67%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 11.11%  |
| Intel 82577LM Gigabit Network Connection                          | 1         | 11.11%  |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 11.11%  |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 65.22%  |
| Ethernet | 8         | 34.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 12        | 70.59%  |
| Ethernet | 5         | 29.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 8         | 53.33%  |
| 1     | 7         | 46.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 13        | 86.67%  |
| Yes  | 2         | 13.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5         | 41.67%  |
| IMC Networks                    | 3         | 25%     |
| Realtek Semiconductor           | 1         | 8.33%   |
| Qualcomm Atheros Communications | 1         | 8.33%   |
| Lite-On Technology              | 1         | 8.33%   |
| Broadcom                        | 1         | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface    | 2         | 16.67%  |
| Intel Bluetooth Device                | 2         | 16.67%  |
| IMC Networks Wireless_Device          | 2         | 16.67%  |
| Realtek  Bluetooth 4.2 Adapter        | 1         | 8.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0 | 1         | 8.33%   |
| Lite-On Bluetooth Radio               | 1         | 8.33%   |
| Intel AX200 Bluetooth                 | 1         | 8.33%   |
| IMC Networks Bluetooth Radio          | 1         | 8.33%   |
| Broadcom BCM20702A0 Bluetooth         | 1         | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 11        | 50%     |
| AMD                               | 4         | 18.18%  |
| Nvidia                            | 3         | 13.64%  |
| Elitegroup Computer Systems (ECS) | 2         | 9.09%   |
| Focusrite-Novation                | 1         | 4.55%   |
| Corsair                           | 1         | 4.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 4         | 14.29%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 10.71%  |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 7.14%   |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                   | 2         | 7.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 3.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 3.57%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 3.57%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 3.57%   |
| Intel CM238 HD Audio Controller                                            | 1         | 3.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 3.57%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 3.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 3.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 3.57%   |
| Focusrite-Novation Scarlett 18i20 3rd Gen                                  | 1         | 3.57%   |
| Corsair HS70 Pro Wireless Gaming Headset                                   | 1         | 3.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 3.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 3         | 30%     |
| Micron Technology   | 3         | 30%     |
| Samsung Electronics | 2         | 20%     |
| Elpida              | 1         | 10%     |
| Crucial             | 1         | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 20%     |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 10%     |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 10%     |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 10%     |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 10%     |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 10%     |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 1         | 10%     |
| Elpida RAM Module 4GB Row Of Chips LPDDR3 1867MT/s               | 1         | 10%     |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s       | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 5         | 55.56%  |
| LPDDR3 | 2         | 22.22%  |
| LPDDR4 | 1         | 11.11%  |
| DDR3   | 1         | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 5         | 55.56%  |
| Row Of Chips | 3         | 33.33%  |
| Chip         | 1         | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 3         | 30%     |
| 8192  | 3         | 30%     |
| 4096  | 3         | 30%     |
| 2048  | 1         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 4         | 40%     |
| 2667  | 2         | 20%     |
| 4267  | 1         | 10%     |
| 2133  | 1         | 10%     |
| 1867  | 1         | 10%     |
| 1600  | 1         | 10%     |

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


| Vendor              | Notebooks | Percent |
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


| Model                              | Notebooks | Percent |
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


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Upek                       | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| Elan Microelectronics      | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 9         | 60%     |
| 1     | 5         | 33.33%  |
| 2     | 1         | 6.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 3         | 42.86%  |
| Net/wireless       | 2         | 28.57%  |
| Graphics card      | 1         | 14.29%  |
| Bluetooth          | 1         | 14.29%  |

