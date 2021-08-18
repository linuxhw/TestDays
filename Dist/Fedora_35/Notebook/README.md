Fedora 35 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 35 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=fedora-35

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

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Dell     | XPS 15 9550              | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer     | Aspire A315-42           | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer     | Aspire ES1-572           | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell     | XPS 15 9570              | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell     | XPS 13 9380              | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo   | IdeaPad 530S-14IKB 81EU  | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| Notebook | P377SM-A                 | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI   | KLVL-WXX9                | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| HUAWEI   | KLVL-WXX9                | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Notebook | P377SM-A                 | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook | P377SM-A                 | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Lenovo   | ThinkPad W541 20EF000UMN | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HUAWEI   | BOHK-WAX9X               | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI   | BOHK-WAX9X               | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI   | BOHK-WAX9X               | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                              | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| 5.14.0-0.rc5.42.fc35.x86_64                          | 5         | 41.67%  |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 8.33%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 8.33%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 8.33%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 8.33%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 8.33%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 8.33%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 8.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 7         | 63.64%  |
| 5.12.0  | 2         | 18.18%  |
| 5.13.0  | 1         | 9.09%   |
| 5.12.8  | 1         | 9.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 7         | 63.64%  |
| 5.12    | 3         | 27.27%  |
| 5.13    | 1         | 9.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 10        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 10        | 90.91%  |
| KDE   | 1         | 9.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 9         | 90%     |
| X11     | 1         | 10%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 8         | 80%     |
| Unknown | 2         | 20%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 6         | 54.55%  |
| sv_SE | 1         | 9.09%   |
| ru_RU | 1         | 9.09%   |
| pl_PL | 1         | 9.09%   |
| es_ES | 1         | 9.09%   |
| en_CA | 1         | 9.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 9         | 90%     |
| BIOS | 1         | 10%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 5         | 45.45%  |
| Btrfs | 5         | 45.45%  |
| Xfs   | 1         | 9.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 8         | 80%     |
| Unknown | 2         | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6         | 54.55%  |
| Yes       | 5         | 45.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 9         | 81.82%  |
| Yes       | 2         | 18.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Dell     | 3         | 30%     |
| Lenovo   | 2         | 20%     |
| HUAWEI   | 2         | 20%     |
| Acer     | 2         | 20%     |
| Notebook | 1         | 10%     |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Notebook P377SM-A               | 1         | 10%     |
| Lenovo ThinkPad W541 20EF000UMN | 1         | 10%     |
| Lenovo IdeaPad 530S-14IKB 81EU  | 1         | 10%     |
| HUAWEI KLVL-WXX9                | 1         | 10%     |
| HUAWEI BOHK-WAX9X               | 1         | 10%     |
| Dell XPS 15 9570                | 1         | 10%     |
| Dell XPS 15 9550                | 1         | 10%     |
| Dell XPS 13 9380                | 1         | 10%     |
| Acer Aspire ES1-572             | 1         | 10%     |
| Acer Aspire A315-42             | 1         | 10%     |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell XPS          | 3         | 30%     |
| Acer Aspire       | 2         | 20%     |
| Notebook P377SM-A | 1         | 10%     |
| Lenovo ThinkPad   | 1         | 10%     |
| Lenovo IdeaPad    | 1         | 10%     |
| HUAWEI KLVL-WXX9  | 1         | 10%     |
| HUAWEI BOHK-WAX9X | 1         | 10%     |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 60%     |
| 2019 | 2         | 20%     |
| 2021 | 1         | 10%     |
| 2015 | 1         | 10%     |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 10        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 7         | 70%     |
| Enabled  | 3         | 30%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 10        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 6         | 60%     |
| 32.01-64.0 | 2         | 20%     |
| 3.01-4.0   | 1         | 10%     |
| 8.01-16.0  | 1         | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 5         | 45.45%  |
| 3.01-4.0 | 4         | 36.36%  |
| 4.01-8.0 | 1         | 9.09%   |
| 1.01-2.0 | 1         | 9.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 8         | 80%     |
| 5      | 1         | 10%     |
| 2      | 1         | 10%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 9         | 90%     |
| Yes       | 1         | 10%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6         | 60%     |
| Yes       | 4         | 40%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9         | 90%     |
| No        | 1         | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| USA     | 2         | 20%     |
| Canada  | 2         | 20%     |
| Sweden  | 1         | 10%     |
| Spain   | 1         | 10%     |
| Poland  | 1         | 10%     |
| Japan   | 1         | 10%     |
| Germany | 1         | 10%     |
| Brazil  | 1         | 10%     |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Yakima         | 1         | 8.33%   |
| Wroclaw        | 1         | 8.33%   |
| Whittier       | 1         | 8.33%   |
| Seattle        | 1         | 8.33%   |
| Raesfeld       | 1         | 8.33%   |
| Porto Ferreira | 1         | 8.33%   |
| Osaka          | 1         | 8.33%   |
| Montreal       | 1         | 8.33%   |
| Madrid         | 1         | 8.33%   |
| Handen         | 1         | 8.33%   |
| Concord        | 1         | 8.33%   |
| Bolszewo       | 1         | 8.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 4      | 23.08%  |
| Unknown             | 2         | 2      | 15.38%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Sandisk             | 2         | 3      | 15.38%  |
| SK Hynix            | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 8      | 7.69%   |
| Micron Technology   | 1         | 1      | 7.69%   |
| LITEON              | 1         | 1      | 7.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 7.14%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 1         | 7.14%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB | 1         | 7.14%   |
| Unknown SSD0240S00 240GB             | 1         | 7.14%   |
| Unknown SD256  249GB                 | 1         | 7.14%   |
| Toshiba KXG60ZNV256G NVMe 256GB      | 1         | 7.14%   |
| Toshiba KXG50ZNV512G NVMe 512GB      | 1         | 7.14%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 7.14%   |
| SanDisk SDSSDH3512G 512GB            | 1         | 7.14%   |
| Sandisk NVMe SSD Drive 256GB         | 1         | 7.14%   |
| Samsung SSD 850 PRO 1TB              | 1         | 7.14%   |
| Samsung SSD 850 EVO mSATA 1TB        | 1         | 7.14%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 7.14%   |
| LITEON CX2-8B256-Q11 NVMe 256GB      | 1         | 7.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 1         | 1      | 25%     |
| SanDisk             | 1         | 2      | 25%     |
| Samsung Electronics | 1         | 8      | 25%     |
| Micron Technology   | 1         | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 6         | 8      | 54.55%  |
| SSD  | 3         | 12     | 27.27%  |
| MMC  | 1         | 1      | 9.09%   |
| HDD  | 1         | 1      | 9.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 6         | 8      | 54.55%  |
| SATA | 4         | 13     | 36.36%  |
| MMC  | 1         | 1      | 9.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 2         | 11     | 50%     |
| 0.01-0.5   | 2         | 2      | 50%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 4         | 36.36%  |
| 1-20       | 3         | 27.27%  |
| 101-250    | 2         | 18.18%  |
| 21-50      | 1         | 9.09%   |
| 501-1000   | 1         | 9.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 5         | 50%     |
| 21-50   | 3         | 30%     |
| 101-250 | 2         | 20%     |

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
| Works    | 8         | 9      | 66.67%  |
| Detected | 4         | 13     | 33.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 6         | 46.15%  |
| Toshiba America Info Systems | 2         | 15.38%  |
| Sandisk                      | 2         | 15.38%  |
| SK Hynix                     | 1         | 7.69%   |
| Lite-On Technology           | 1         | 7.69%   |
| AMD                          | 1         | 7.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 15.38%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 15.38%  |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 7.69%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 7.69%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 7.69%   |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 7.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 7.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 7.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 7.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 7.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 6         | 46.15%  |
| SATA | 6         | 46.15%  |
| RAID | 1         | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 7         | 70%     |
| AMD    | 3         | 30%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 10%     |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 10%     |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 10%     |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 10%     |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 10%     |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 10%     |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 10%     |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 10%     |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 10%     |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 10%     |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 5         | 50%     |
| AMD Ryzen 5   | 2         | 20%     |
| Intel Core i5 | 1         | 10%     |
| Intel Core i3 | 1         | 10%     |
| AMD Ryzen 3   | 1         | 10%     |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 6         | 60%     |
| 6      | 2         | 20%     |
| 2      | 2         | 20%     |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 10        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 10        | 100%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306c3    | 2         | 20%     |
| 0x08108109 | 2         | 20%     |
| 0x906ea    | 1         | 10%     |
| 0x806ec    | 1         | 10%     |
| 0x806ea    | 1         | 10%     |
| 0x506e3    | 1         | 10%     |
| 0x406e3    | 1         | 10%     |
| 0x08600104 | 1         | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KabyLake | 3         | 30%     |
| Zen+     | 2         | 20%     |
| Skylake  | 2         | 20%     |
| Haswell  | 2         | 20%     |
| Zen 2    | 1         | 10%     |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 6         | 46.15%  |
| Nvidia | 4         | 30.77%  |
| AMD    | 3         | 23.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| AMD Picasso                                                 | 2         | 15.38%  |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                  | 1         | 7.69%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                     | 1         | 7.69%   |
| Nvidia GM107M [GeForce GTX 960M]                            | 1         | 7.69%   |
| Nvidia GK106GLM [Quadro K2100M]                             | 1         | 7.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                  | 1         | 7.69%   |
| Intel UHD Graphics 620                                      | 1         | 7.69%   |
| Intel Skylake GT2 [HD Graphics 520]                         | 1         | 7.69%   |
| Intel HD Graphics 530                                       | 1         | 7.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                   | 1         | 7.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller | 1         | 7.69%   |
| AMD Renoir                                                  | 1         | 7.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 3         | 30%     |
| 1 x Intel      | 3         | 30%     |
| 1 x AMD        | 3         | 30%     |
| 1 x Nvidia     | 1         | 10%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 10        | 90.91%  |
| Proprietary | 1         | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 36.36%  |
| 1.01-2.0   | 3         | 27.27%  |
| 7.01-8.0   | 1         | 9.09%   |
| 3.01-4.0   | 1         | 9.09%   |
| 0.51-1.0   | 1         | 9.09%   |
| 0.01-0.5   | 1         | 9.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| AU Optronics   | 4         | 36.36%  |
| Sharp          | 2         | 18.18%  |
| Chimei Innolux | 2         | 18.18%  |
| LG Display     | 1         | 9.09%   |
| Dell           | 1         | 9.09%   |
| BOE            | 1         | 9.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch          | 1         | 8.33%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch          | 1         | 8.33%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch     | 1         | 8.33%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                | 1         | 8.33%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                | 1         | 8.33%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch  | 1         | 8.33%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch | 1         | 8.33%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch            | 1         | 8.33%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch   | 1         | 8.33%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch   | 1         | 8.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch   | 1         | 8.33%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch   | 1         | 8.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 7         | 70%     |
| 3840x2160 (4K)  | 1         | 10%     |
| 2160x1440       | 1         | 10%     |
| 1366x768 (WXGA) | 1         | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 6         | 54.55%  |
| 14     | 2         | 18.18%  |
| 21     | 1         | 9.09%   |
| 17     | 1         | 9.09%   |
| 13     | 1         | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 7         | 63.64%  |
| 201-300     | 2         | 18.18%  |
| 401-500     | 1         | 9.09%   |
| 351-400     | 1         | 9.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 9         | 90%     |
| 3/2   | 1         | 10%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 6         | 54.55%  |
| 81-90          | 2         | 18.18%  |
| 71-80          | 1         | 9.09%   |
| 201-250        | 1         | 9.09%   |
| 121-130        | 1         | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 6         | 54.55%  |
| 161-240       | 2         | 18.18%  |
| 101-120       | 2         | 18.18%  |
| More than 240 | 1         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 10        | 90.91%  |
| 3     | 1         | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 6         | 46.15%  |
| Intel                 | 4         | 30.77%  |
| Qualcomm Atheros      | 3         | 23.08%  |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 21.43%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 14.29%  |
| Intel Wireless-AC 9260                                            | 2         | 14.29%  |
| Intel Wireless 7260                                               | 2         | 14.29%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 7.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 7.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 7.14%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 7.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 4         | 40%     |
| Realtek Semiconductor | 3         | 30%     |
| Qualcomm Atheros      | 3         | 30%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 20%     |
| Intel Wireless-AC 9260                                     | 2         | 20%     |
| Intel Wireless 7260                                        | 2         | 20%     |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 10%     |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 10%     |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 10%     |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 3         | 75%     |
| Intel                 | 1         | 25%     |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 75%     |
| Intel Ethernet Connection I217-LM                                 | 1         | 25%     |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 10        | 71.43%  |
| Ethernet | 4         | 28.57%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 8         | 66.67%  |
| Ethernet | 4         | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6         | 60%     |
| 2     | 4         | 40%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 8         | 80%     |
| Yes  | 2         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 3         | 33.33%  |
| Realtek               | 2         | 22.22%  |
| Foxconn / Hon Hai     | 2         | 22.22%  |
| Realtek Semiconductor | 1         | 11.11%  |
| Lite-On Technology    | 1         | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                    | 2         | 22.22%  |
| Intel Wireless-AC 9260 Bluetooth Adapter   | 2         | 22.22%  |
| Foxconn / Hon Hai Bluetooth Device         | 2         | 22.22%  |
| Realtek Bluetooth Radio                    | 1         | 11.11%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 11.11%  |
| Intel Bluetooth wireless interface         | 1         | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 7         | 53.85%  |
| AMD      | 3         | 23.08%  |
| Nvidia   | 2         | 15.38%  |
| Micronas | 1         | 7.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 3         | 17.65%  |
| Intel Sunrise Point-LP HD Audio                                     | 2         | 11.76%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 11.76%  |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 11.76%  |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 5.88%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 5.88%   |
| Micronas BLUE USB Audio 2.0                                         | 1         | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 5.88%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 5.88%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 5.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1         | 5.88%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 5.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 3         | 33.33%  |
| Samsung Electronics | 3         | 33.33%  |
| Micron Technology   | 1         | 11.11%  |
| Crucial             | 1         | 11.11%  |
| A-DATA Technology   | 1         | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s        | 1         | 11.11%  |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 11.11%  |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 11.11%  |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s   | 1         | 11.11%  |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s   | 1         | 11.11%  |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s  | 1         | 11.11%  |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s         | 1         | 11.11%  |
| Crucial RAM CT16G4SFD8266.C16FD1 16384MB SODIMM DDR4 2667MT/s | 1         | 11.11%  |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s          | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 66.67%  |
| LPDDR4 | 1         | 11.11%  |
| LPDDR3 | 1         | 11.11%  |
| DDR3   | 1         | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 6         | 66.67%  |
| Row Of Chips | 3         | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 4         | 44.44%  |
| 4096  | 4         | 44.44%  |
| 16384 | 1         | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 6         | 66.67%  |
| 2400  | 1         | 11.11%  |
| 2133  | 1         | 11.11%  |
| 1867  | 1         | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-3200 Series | 1         | 100%    |

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
| IMC Networks        | 3         | 33.33%  |
| Chicony Electronics | 3         | 33.33%  |
| Microdia            | 2         | 22.22%  |
| Quanta              | 1         | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD        | 2         | 20%     |
| Quanta VGA WebCam                    | 1         | 10%     |
| IMC Networks ov9734_azurewave_camera | 1         | 10%     |
| IMC Networks Integrated Camera       | 1         | 10%     |
| IMC Networks HD Camera               | 1         | 10%     |
| Chicony VGA Webcam                   | 1         | 10%     |
| Chicony USB2.0 2M WebCam             | 1         | 10%     |
| Chicony USB 5M WebCam                | 1         | 10%     |
| Chicony Integrated Camera            | 1         | 10%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 50%     |
| Validity Sensors           | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device          | 2         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 25%     |
| LighTuning ES603 Swipe Fingerprint Sensor    | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 6         | 60%     |
| 1     | 4         | 40%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 4         | 100%    |

