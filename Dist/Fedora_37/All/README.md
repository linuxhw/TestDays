Fedora 37 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 37.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_37/Desktop/README.md) and [notebooks](/Dist/Fedora_37/Notebook/README.md).

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

Total: 17

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | HVY-WXX9                    | Notebook    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [47dbe77b54](https://linux-hardware.org/?probe=47dbe77b54) | Sep 02, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | Notebook    | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [d1f2245fb4](https://linux-hardware.org/?probe=d1f2245fb4) | Jul 18, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [93eb00c3c5](https://linux-hardware.org/?probe=93eb00c3c5) | Jun 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [2cd65296c2](https://linux-hardware.org/?probe=2cd65296c2) | May 08, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [b2b1324db9](https://linux-hardware.org/?probe=b2b1324db9) | Apr 22, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [2477951c04](https://linux-hardware.org/?probe=2477951c04) | Apr 15, 2022 |
| HP            | 0B54h D                     | Desktop     | [7153ec172b](https://linux-hardware.org/?probe=7153ec172b) | Mar 21, 2022 |
| HP            | 0B54h D                     | Desktop     | [399cc50503](https://linux-hardware.org/?probe=399cc50503) | Mar 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| 5.19.7-300.fc37.x86_64                                 | 3         | 18.75%  |
| 5.19.0-65.fc37.x86_64                                  | 2         | 12.5%   |
| 5.18.0-0.rc2.23.fc37.x86_64                            | 2         | 12.5%   |
| 5.19.8-300.fc37.x86_64                                 | 1         | 6.25%   |
| 5.19.6-300.fc37.aarch64                                | 1         | 6.25%   |
| 5.19.4-300.fc37.x86_64                                 | 1         | 6.25%   |
| 5.19.0-xm2.0.fc37.x86_64                               | 1         | 6.25%   |
| 5.19.0-0.rc6.20220714git4a57a8400075.49.fc37.x86_64    | 1         | 6.25%   |
| 5.19.0-0.rc1.20220610git874c8ca1e60b.18.fc37.x86_64    | 1         | 6.25%   |
| 5.18.0-0.rc5.20220505gita7391ad3572431a.43.fc37.x86_64 | 1         | 6.25%   |
| 5.18.0-0.rc3.27.fc37.x86_64                            | 1         | 6.25%   |
| 5.17.0-0.rc6.109.fc37.x86_64                           | 1         | 6.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 5         | 31.25%  |
| 5.18.0  | 4         | 25%     |
| 5.19.7  | 3         | 18.75%  |
| 5.19.8  | 1         | 6.25%   |
| 5.19.6  | 1         | 6.25%   |
| 5.19.4  | 1         | 6.25%   |
| 5.17.0  | 1         | 6.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 11        | 68.75%  |
| 5.18    | 4         | 25%     |
| 5.17    | 1         | 6.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 15        | 93.75%  |
| aarch64 | 1         | 6.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 13        | 81.25%  |
| XFCE       | 2         | 12.5%   |
| X-Cinnamon | 1         | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 10        | 62.5%   |
| X11     | 6         | 37.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 62.5%   |
| GDM     | 4         | 25%     |
| LightDM | 2         | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 8         | 50%     |
| en_GB | 3         | 18.75%  |
| ro_RO | 1         | 6.25%   |
| pt_BR | 1         | 6.25%   |
| nl_NL | 1         | 6.25%   |
| es_ES | 1         | 6.25%   |
| es_AR | 1         | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 11        | 68.75%  |
| BIOS | 5         | 31.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 12        | 75%     |
| Ext4  | 3         | 18.75%  |
| Xfs   | 1         | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 62.5%   |
| GPT     | 5         | 31.25%  |
| MBR     | 1         | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 15        | 93.75%  |
| Yes       | 1         | 6.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 14        | 87.5%   |
| Yes       | 2         | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HUAWEI                  | 3         | 18.75%  |
| Hewlett-Packard         | 3         | 18.75%  |
| Lenovo                  | 2         | 12.5%   |
| ASUSTek Computer        | 2         | 12.5%   |
| TUXEDO                  | 1         | 6.25%   |
| Samsung Electronics     | 1         | 6.25%   |
| Raspberry Pi Foundation | 1         | 6.25%   |
| MSI                     | 1         | 6.25%   |
| Dell                    | 1         | 6.25%   |
| AXDIA International     | 1         | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| HUAWEI HVY-WXX9                          | 2         | 12.5%   |
| TUXEDO InfinityBook S 15/17 Gen7         | 1         | 6.25%   |
| Samsung 270E5G/270E5U                    | 1         | 6.25%   |
| RPi Raspberry Pi 4 Model B Rev 1.1       | 1         | 6.25%   |
| MSI MS-7B47                              | 1         | 6.25%   |
| Lenovo ThinkPad W510 4391F66             | 1         | 6.25%   |
| Lenovo Legion 5 Pro 16ITH6H 82JD         | 1         | 6.25%   |
| HUAWEI DRC-WXX                           | 1         | 6.25%   |
| HP Z600 Workstation                      | 1         | 6.25%   |
| HP Laptop 14-dq2xxx                      | 1         | 6.25%   |
| HP EliteBook 820 G1                      | 1         | 6.25%   |
| Dell OptiPlex 3050                       | 1         | 6.25%   |
| AXDIA International WINPAD V10           | 1         | 6.25%   |
| ASUS P8Z68-V LX                          | 1         | 6.25%   |
| ASUS ASUS TUF Gaming F15 FX506LI_FX506LI | 1         | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| HUAWEI HVY-WXX9            | 2         | 12.5%   |
| TUXEDO InfinityBook        | 1         | 6.25%   |
| Samsung 270E5G             | 1         | 6.25%   |
| RPi Raspberry              | 1         | 6.25%   |
| MSI MS-7B47                | 1         | 6.25%   |
| Lenovo ThinkPad            | 1         | 6.25%   |
| Lenovo Legion              | 1         | 6.25%   |
| HUAWEI DRC-WXX             | 1         | 6.25%   |
| HP Z600                    | 1         | 6.25%   |
| HP Laptop                  | 1         | 6.25%   |
| HP EliteBook               | 1         | 6.25%   |
| Dell OptiPlex              | 1         | 6.25%   |
| AXDIA International WINPAD | 1         | 6.25%   |
| ASUS P8Z68-V               | 1         | 6.25%   |
| ASUS ASUS                  | 1         | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 3         | 18.75%  |
| 2020 | 3         | 18.75%  |
| 2021 | 2         | 12.5%   |
| 2017 | 2         | 12.5%   |
| 2013 | 2         | 12.5%   |
| 2010 | 2         | 12.5%   |
| 2014 | 1         | 6.25%   |
| 2011 | 1         | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 10        | 62.5%   |
| Desktop        | 4         | 25%     |
| System on chip | 1         | 6.25%   |
| Tablet         | 1         | 6.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 16        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 16        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 7         | 43.75%  |
| 8.01-16.0   | 4         | 25%     |
| 1.01-2.0    | 2         | 12.5%   |
| 4.01-8.0    | 1         | 6.25%   |
| 32.01-64.0  | 1         | 6.25%   |
| 64.01-256.0 | 1         | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 8.01-16.0 | 5         | 31.25%  |
| 2.01-3.0  | 4         | 25%     |
| 4.01-8.0  | 3         | 18.75%  |
| 1.01-2.0  | 3         | 18.75%  |
| 3.01-4.0  | 1         | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 11        | 68.75%  |
| 4      | 2         | 12.5%   |
| 3      | 1         | 6.25%   |
| 2      | 1         | 6.25%   |
| 0      | 1         | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 13        | 81.25%  |
| Yes       | 3         | 18.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 62.5%   |
| No        | 6         | 37.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11        | 68.75%  |
| No        | 5         | 31.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 62.5%   |
| No        | 6         | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 3         | 18.75%  |
| UK           | 1         | 6.25%   |
| Sweden       | 1         | 6.25%   |
| Spain        | 1         | 6.25%   |
| South Africa | 1         | 6.25%   |
| Poland       | 1         | 6.25%   |
| Norway       | 1         | 6.25%   |
| Netherlands  | 1         | 6.25%   |
| Moldova      | 1         | 6.25%   |
| Mexico       | 1         | 6.25%   |
| France       | 1         | 6.25%   |
| Brazil       | 1         | 6.25%   |
| Austria      | 1         | 6.25%   |
| Argentina    | 1         | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Zierikzee          | 1         | 6.25%   |
| Warsaw             | 1         | 6.25%   |
| Valencia           | 1         | 6.25%   |
| Valbonne           | 1         | 6.25%   |
| Sao Paulo          | 1         | 6.25%   |
| San Antonio        | 1         | 6.25%   |
| San Andres Cholula | 1         | 6.25%   |
| Rosario            | 1         | 6.25%   |
| Queens             | 1         | 6.25%   |
| Oslo               | 1         | 6.25%   |
| New York           | 1         | 6.25%   |
| Matzendorf         | 1         | 6.25%   |
| Laenghem           | 1         | 6.25%   |
| Centurion          | 1         | 6.25%   |
| Bristol            | 1         | 6.25%   |
| Bălţi            | 1         | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 6         | 9      | 35.29%  |
| WDC                         | 2         | 4      | 11.76%  |
| Seagate                     | 2         | 3      | 11.76%  |
| Kingston                    | 2         | 2      | 11.76%  |
| YMTC                        | 1         | 1      | 5.88%   |
| Yangtze Memory Technologies | 1         | 1      | 5.88%   |
| Unknown                     | 1         | 2      | 5.88%   |
| Silicon Motion              | 1         | 1      | 5.88%   |
| Micron Technology           | 1         | 1      | 5.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB               | 3         | 14.29%  |
| Samsung NVMe SSD Drive 1024GB            | 2         | 9.52%   |
| YMTC PC005 512GB                         | 1         | 4.76%   |
| Yangtze Memory NVMe SSD Drive 512GB      | 1         | 4.76%   |
| WDC WDS500G2B0B-00YS70 500GB SSD         | 1         | 4.76%   |
| WDC WD40PURX-64GVNY0 4TB                 | 1         | 4.76%   |
| WDC WD40EZRZ-00GXCB0 4TB                 | 1         | 4.76%   |
| WDC WD10EVDS-63U8B1 1TB                  | 1         | 4.76%   |
| Unknown SL64G  64GB                      | 1         | 4.76%   |
| Unknown 032GE4  32GB                     | 1         | 4.76%   |
| Silicon Motion PCIe-8 SSD 512GB          | 1         | 4.76%   |
| Seagate ST4000DM000-1F2168 4TB           | 1         | 4.76%   |
| Seagate ST2000DM008-2FR102 2TB           | 1         | 4.76%   |
| Samsung SSD 860 PRO 512GB                | 1         | 4.76%   |
| Samsung SSD 840 Series 250GB             | 1         | 4.76%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 4.76%   |
| Kingston SUV400S37240G 240GB SSD         | 1         | 4.76%   |
| Kingston OM8PCP3512F-AB 512GB            | 1         | 4.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 3      | 50%     |
| Seagate | 2         | 3      | 50%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 40%     |
| WDC                 | 1         | 1      | 20%     |
| Micron Technology   | 1         | 1      | 20%     |
| Kingston            | 1         | 1      | 20%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 9         | 10     | 50%     |
| SSD  | 5         | 6      | 27.78%  |
| HDD  | 3         | 6      | 16.67%  |
| MMC  | 1         | 2      | 5.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 9         | 10     | 52.94%  |
| SATA | 7         | 12     | 41.18%  |
| MMC  | 1         | 2      | 5.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4         | 4      | 50%     |
| 0.51-1.0   | 2         | 3      | 25%     |
| 3.01-4.0   | 1         | 3      | 12.5%   |
| 1.01-2.0   | 1         | 2      | 12.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 6         | 37.5%   |
| 251-500        | 3         | 18.75%  |
| 101-250        | 3         | 18.75%  |
| 1001-2000      | 2         | 12.5%   |
| More than 3000 | 1         | 6.25%   |
| 21-50          | 1         | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 101-250   | 4         | 25%     |
| 1-20      | 4         | 25%     |
| 21-50     | 2         | 12.5%   |
| 501-1000  | 2         | 12.5%   |
| 51-100    | 2         | 12.5%   |
| 251-500   | 1         | 6.25%   |
| 1001-2000 | 1         | 6.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Micron Technology | 1         | 1      | 100%    |

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
| SSD  | 1         | 1      | 100%    |

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
| Detected | 10        | 19     | 66.67%  |
| Works    | 4         | 4      | 26.67%  |
| Malfunc  | 1         | 1      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 11        | 55%     |
| Samsung Electronics         | 5         | 25%     |
| Yangtze Memory Technologies | 2         | 10%     |
| Silicon Motion              | 1         | 5%      |
| Kingston Technology Company | 1         | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 3         | 15%     |
| Yangtze Memory Non-Volatile memory controller                                 | 2         | 10%     |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 10%     |
| Intel SATA Controller [RAID mode]                                             | 2         | 10%     |
| Silicon Motion Non-Volatile memory controller                                 | 1         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 5%      |
| Samsung NVMe SSD Controller 980                                               | 1         | 5%      |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 5%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 1         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1         | 5%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 1         | 5%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 5%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1         | 5%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1         | 5%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 9         | 45%     |
| SATA | 7         | 35%     |
| RAID | 4         | 20%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 13        | 81.25%  |
| AMD    | 2         | 12.5%   |
| ARM    | 1         | 6.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 12.5%   |
| Intel Xeon CPU X5675 @ 3.07GHz          | 1         | 6.25%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 6.25%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1         | 6.25%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 1         | 6.25%   |
| Intel Core i5-7500 CPU @ 3.40GHz        | 1         | 6.25%   |
| Intel Core i5-4310U CPU @ 2.00GHz       | 1         | 6.25%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 6.25%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 6.25%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 1         | 6.25%   |
| Intel 12th Gen Core i5-1240P            | 1         | 6.25%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 6.25%   |
| Intel 11th Gen Core i5-1130G7 @ 1.10GHz | 1         | 6.25%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz | 1         | 6.25%   |
| ARM Processor                           | 1         | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Other         | 5         | 31.25%  |
| Intel Core i5 | 4         | 25%     |
| Intel Core i7 | 3         | 18.75%  |
| AMD Ryzen 5   | 2         | 12.5%   |
| Intel Xeon    | 1         | 6.25%   |
| Intel Atom    | 1         | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 7         | 43.75%  |
| 6       | 3         | 18.75%  |
| 12      | 2         | 12.5%   |
| 2       | 2         | 12.5%   |
| 8       | 1         | 6.25%   |
| Unknown | 1         | 6.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 14        | 87.5%   |
| 2       | 1         | 6.25%   |
| Unknown | 1         | 6.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 13        | 81.25%  |
| 1       | 2         | 12.5%   |
| Unknown | 1         | 6.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 15        | 93.75%  |
| 64-bit         | 1         | 6.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3         | 18.75%  |
| 0x08600106 | 2         | 12.5%   |
| 0xa0652    | 1         | 6.25%   |
| 0x906ea    | 1         | 6.25%   |
| 0x906e9    | 1         | 6.25%   |
| 0x906a3    | 1         | 6.25%   |
| 0x806d1    | 1         | 6.25%   |
| 0x806c1    | 1         | 6.25%   |
| 0x40651    | 1         | 6.25%   |
| 0x306a9    | 1         | 6.25%   |
| 0x30678    | 1         | 6.25%   |
| 0x206c2    | 1         | 6.25%   |
| 0x206a7    | 1         | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 2            | 2         | 12.5%   |
| TigerLake        | 2         | 12.5%   |
| KabyLake         | 2         | 12.5%   |
| Westmere         | 1         | 6.25%   |
| Silvermont       | 1         | 6.25%   |
| SandyBridge      | 1         | 6.25%   |
| Nehalem          | 1         | 6.25%   |
| IvyBridge        | 1         | 6.25%   |
| Icelake          | 1         | 6.25%   |
| Haswell          | 1         | 6.25%   |
| CometLake        | 1         | 6.25%   |
| Alderlake Hybrid | 1         | 6.25%   |
| Unknown          | 1         | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 10        | 52.63%  |
| Nvidia | 7         | 36.84%  |
| AMD    | 2         | 10.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 2         | 10.53%  |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 1         | 5.26%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                | 1         | 5.26%   |
| Nvidia GT216GLM [Quadro FX 880M]                                     | 1         | 5.26%   |
| Nvidia GP107 [GeForce GTX 1050]                                      | 1         | 5.26%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M] | 1         | 5.26%   |
| Nvidia GF114 [GeForce GTX 560]                                       | 1         | 5.26%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 5.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 1         | 5.26%   |
| Intel Tiger Lake UHD Graphics                                        | 1         | 5.26%   |
| Intel Tiger Lake Iris Xe Graphics                                    | 1         | 5.26%   |
| Intel HD Graphics 630                                                | 1         | 5.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 1         | 5.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 1         | 5.26%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                            | 1         | 5.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display         | 1         | 5.26%   |
| Intel Alder Lake-P Integrated Graphics Controller                    | 1         | 5.26%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 1         | 5.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 6         | 37.5%   |
| 1 x Nvidia     | 4         | 25%     |
| Intel + Nvidia | 3         | 18.75%  |
| 1 x AMD        | 2         | 12.5%   |
| Other          | 1         | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 11        | 68.75%  |
| Proprietary | 3         | 18.75%  |
| Unknown     | 2         | 12.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 56.25%  |
| 1.01-2.0   | 2         | 12.5%   |
| 0.01-0.5   | 2         | 12.5%   |
| 7.01-8.0   | 1         | 6.25%   |
| 3.01-4.0   | 1         | 6.25%   |
| 0.51-1.0   | 1         | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 4         | 23.53%  |
| Samsung Electronics     | 2         | 11.76%  |
| Hewlett-Packard         | 2         | 11.76%  |
| Dell                    | 2         | 11.76%  |
| Toshiba                 | 1         | 5.88%   |
| PANDA                   | 1         | 5.88%   |
| Lenovo                  | 1         | 5.88%   |
| KTC                     | 1         | 5.88%   |
| CSO                     | 1         | 5.88%   |
| Chimei Innolux          | 1         | 5.88%   |
| Chi Mei Optoelectronics | 1         | 5.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 2         | 10%     |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                        | 1         | 5%      |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch       | 1         | 5%      |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch       | 1         | 5%      |
| Samsung Electronics C34H89x SAM0E25 3440x1440 797x333mm 34.0-inch        | 1         | 5%      |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                  | 1         | 5%      |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 1         | 5%      |
| KTC 42 TV KTC4200 1920x1080 983x576mm 44.9-inch                          | 1         | 5%      |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch            | 1         | 5%      |
| Hewlett-Packard E271i HWP3106 1920x1080 600x340mm 27.2-inch              | 1         | 5%      |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                       | 1         | 5%      |
| Dell AW2518HF DELA101 1920x1080 544x303mm 24.5-inch                      | 1         | 5%      |
| Dell AW2518H DELA0F6 1920x1080 544x303mm 24.5-inch                       | 1         | 5%      |
| CSO LCD Monitor CSO1606 2560x1600 345x215mm 16.0-inch                    | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch         | 1         | 5%      |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 1         | 5%      |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                    | 1         | 5%      |
| BOE LCD Monitor BOE05F5 1366x768 277x156mm 12.5-inch                     | 1         | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 10        | 66.67%  |
| 1366x768 (WXGA) | 2         | 13.33%  |
| 3440x1440       | 1         | 6.67%   |
| 2560x1600       | 1         | 6.67%   |
| 1600x900 (HD+)  | 1         | 6.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 5         | 27.78%  |
| 24     | 3         | 16.67%  |
| 16     | 3         | 16.67%  |
| 50     | 1         | 5.56%   |
| 44     | 1         | 5.56%   |
| 34     | 1         | 5.56%   |
| 27     | 1         | 5.56%   |
| 23     | 1         | 5.56%   |
| 13     | 1         | 5.56%   |
| 12     | 1         | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 6         | 37.5%   |
| 501-600     | 4         | 25%     |
| 351-400     | 2         | 12.5%   |
| 701-800     | 1         | 6.25%   |
| 201-300     | 1         | 6.25%   |
| 1001-1500   | 1         | 6.25%   |
| 901-1000    | 1         | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 11        | 78.57%  |
| 16/10 | 2         | 14.29%  |
| 21/9  | 1         | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 41.18%  |
| 251-300        | 2         | 11.76%  |
| More than 1000 | 1         | 5.88%   |
| 81-90          | 1         | 5.88%   |
| 61-70          | 1         | 5.88%   |
| 351-500        | 1         | 5.88%   |
| 301-350        | 1         | 5.88%   |
| 201-250        | 1         | 5.88%   |
| 111-120        | 1         | 5.88%   |
| 501-1000       | 1         | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 6         | 37.5%   |
| 51-100  | 5         | 31.25%  |
| 1-50    | 2         | 12.5%   |
| 101-120 | 2         | 12.5%   |
| 161-240 | 1         | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 9         | 56.25%  |
| 2     | 4         | 25%     |
| 0     | 2         | 12.5%   |
| 4     | 1         | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 42.86%  |
| Realtek Semiconductor | 7         | 33.33%  |
| Broadcom              | 2         | 9.52%   |
| Qualcomm Atheros      | 1         | 4.76%   |
| NetGear               | 1         | 4.76%   |
| Hewlett-Packard       | 1         | 4.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 20.83%  |
| Intel Wi-Fi 6 AX200                                               | 3         | 12.5%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 4.17%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]            | 1         | 4.17%   |
| Intel Wireless 7260                                               | 1         | 4.17%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 4.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 4.17%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.17%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 4.17%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 4.17%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 4.17%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 4.17%   |
| HP lt4112 Gobi 4G Module Network Device                           | 1         | 4.17%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet Multi Function | 1         | 4.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 8         | 61.54%  |
| Realtek Semiconductor | 2         | 15.38%  |
| Qualcomm Atheros      | 1         | 7.69%   |
| NetGear               | 1         | 7.69%   |
| Hewlett-Packard       | 1         | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 3         | 23.08%  |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 7.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 7.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 7.69%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]     | 1         | 7.69%   |
| Intel Wireless 7260                                        | 1         | 7.69%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 7.69%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 7.69%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 7.69%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 7.69%   |
| HP lt4112 Gobi 4G Module Network Device                    | 1         | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 6         | 54.55%  |
| Intel                 | 3         | 27.27%  |
| Broadcom              | 2         | 18.18%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 45.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 9.09%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 9.09%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 9.09%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 9.09%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet Multi Function | 1         | 9.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 9.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 11        | 52.38%  |
| Ethernet | 10        | 47.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 8         | 53.33%  |
| Ethernet | 7         | 46.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 7         | 43.75%  |
| 2     | 6         | 37.5%   |
| 0     | 2         | 12.5%   |
| 9     | 1         | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 13        | 81.25%  |
| Yes  | 3         | 18.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 70%     |
| Realtek Semiconductor           | 1         | 10%     |
| Qualcomm Atheros Communications | 1         | 10%     |
| Broadcom                        | 1         | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                 | 3         | 30%     |
| Intel AX200 Bluetooth                 | 3         | 30%     |
| Realtek Bluetooth Radio               | 1         | 10%     |
| Qualcomm Atheros AR3012 Bluetooth 4.0 | 1         | 10%     |
| Intel Bluetooth wireless interface    | 1         | 10%     |
| Broadcom BCM20702A0 Bluetooth 4.0     | 1         | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 12        | 60%     |
| Nvidia | 6         | 30%     |
| AMD    | 2         | 10%     |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 9.52%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 9.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 9.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 4.76%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 4.76%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 4.76%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 4.76%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 4.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 4.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 4.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 4.76%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 4.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 4.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 4.76%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 4.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 4.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 37.5%   |
| Unknown             | 1         | 12.5%   |
| Micron Technology   | 1         | 12.5%   |
| Kingston            | 1         | 12.5%   |
| Corsair             | 1         | 12.5%   |
| A-DATA Technology   | 1         | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                | 1         | 12.5%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 12.5%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s   | 1         | 12.5%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 12.5%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 12.5%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s    | 1         | 12.5%   |
| Corsair RAM CMX8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s        | 1         | 12.5%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s       | 1         | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 3         | 50%     |
| DDR4   | 2         | 33.33%  |
| LPDDR4 | 1         | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3         | 50%     |
| Row Of Chips | 2         | 33.33%  |
| DIMM         | 1         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 4         | 66.67%  |
| 4096 | 1         | 16.67%  |
| 2048 | 1         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 2         | 25%     |
| 2667  | 2         | 25%     |
| 4267  | 1         | 12.5%   |
| 1800  | 1         | 12.5%   |
| 1600  | 1         | 12.5%   |
| 1333  | 1         | 12.5%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson Printer | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2         | 22.22%  |
| Silicon Motion                         | 1         | 11.11%  |
| Quanta                                 | 1         | 11.11%  |
| Microsoft                              | 1         | 11.11%  |
| Lenovo                                 | 1         | 11.11%  |
| IMC Networks                           | 1         | 11.11%  |
| Goodong Industry                       | 1         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) | 1         | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Silicon Motion WebCam SC-10HDD12636N             | 1         | 11.11%  |
| Quanta HP TrueVision HD Camera                   | 1         | 11.11%  |
| Microsoft LifeCam VX-2000                        | 1         | 11.11%  |
| Lenovo Integrated Webcam [R5U877]                | 1         | 11.11%  |
| IMC Networks HD Camera                           | 1         | 11.11%  |
| Goodong Industry USB2.0 HD UVC WebCam            | 1         | 11.11%  |
| Chicony USB2.0 Camera                            | 1         | 11.11%  |
| Chicony HP HD Webcam                             | 1         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 11.11%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 3         | 60%     |
| Validity Sensors           | 1         | 20%     |
| Elan Microelectronics      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device        | 3         | 60%     |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 20%     |
| Elan ELAN:ARM-M4                           | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Lenovo | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 8         | 50%     |
| 1     | 6         | 37.5%   |
| 3     | 1         | 6.25%   |
| 2     | 1         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 45.45%  |
| Graphics card         | 3         | 27.27%  |
| Net/wireless          | 2         | 18.18%  |
| Multimedia controller | 1         | 9.09%   |

