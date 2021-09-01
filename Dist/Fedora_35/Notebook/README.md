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
| Lenovo   | ThinkPad P51s 20HBCTO1WW | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
| Dell     | Latitude E5470           | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
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
| 5.14.0-0.rc5.42.fc35.x86_64                          | 5         | 35.71%  |
| 5.14.0-0.rc6.46.fc35.x86_64                          | 1         | 7.14%   |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 7.14%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 7.14%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 7.14%   |
| 5.13.4-200.fc34.x86_64                               | 1         | 7.14%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 7.14%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 7.14%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 7.14%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 7.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 8         | 61.54%  |
| 5.12.0  | 2         | 15.38%  |
| 5.13.4  | 1         | 7.69%   |
| 5.13.0  | 1         | 7.69%   |
| 5.12.8  | 1         | 7.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 8         | 61.54%  |
| 5.12    | 3         | 23.08%  |
| 5.13    | 2         | 15.38%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 12        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 12        | 92.31%  |
| KDE   | 1         | 7.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 10        | 83.33%  |
| X11     | 2         | 16.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 10        | 83.33%  |
| Unknown | 2         | 16.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 8         | 61.54%  |
| sv_SE | 1         | 7.69%   |
| ru_RU | 1         | 7.69%   |
| pl_PL | 1         | 7.69%   |
| es_ES | 1         | 7.69%   |
| en_CA | 1         | 7.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 11        | 91.67%  |
| BIOS | 1         | 8.33%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 7         | 53.85%  |
| Btrfs | 5         | 38.46%  |
| Xfs   | 1         | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 10        | 83.33%  |
| Unknown | 2         | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7         | 53.85%  |
| Yes       | 6         | 46.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10        | 76.92%  |
| Yes       | 3         | 23.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Dell     | 4         | 33.33%  |
| Lenovo   | 3         | 25%     |
| HUAWEI   | 2         | 16.67%  |
| Acer     | 2         | 16.67%  |
| Notebook | 1         | 8.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Notebook P377SM-A               | 1         | 8.33%   |
| Lenovo ThinkPad W541 20EF000UMN | 1         | 8.33%   |
| Lenovo ThinkPad P51s 20HBCTO1WW | 1         | 8.33%   |
| Lenovo IdeaPad 530S-14IKB 81EU  | 1         | 8.33%   |
| HUAWEI KLVL-WXX9                | 1         | 8.33%   |
| HUAWEI BOHK-WAX9X               | 1         | 8.33%   |
| Dell XPS 15 9570                | 1         | 8.33%   |
| Dell XPS 15 9550                | 1         | 8.33%   |
| Dell XPS 13 9380                | 1         | 8.33%   |
| Dell Latitude E5470             | 1         | 8.33%   |
| Acer Aspire ES1-572             | 1         | 8.33%   |
| Acer Aspire A315-42             | 1         | 8.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell XPS          | 3         | 25%     |
| Lenovo ThinkPad   | 2         | 16.67%  |
| Acer Aspire       | 2         | 16.67%  |
| Notebook P377SM-A | 1         | 8.33%   |
| Lenovo IdeaPad    | 1         | 8.33%   |
| HUAWEI KLVL-WXX9  | 1         | 8.33%   |
| HUAWEI BOHK-WAX9X | 1         | 8.33%   |
| Dell Latitude     | 1         | 8.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 50%     |
| 2021 | 3         | 25%     |
| 2019 | 2         | 16.67%  |
| 2015 | 1         | 8.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 12        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 9         | 75%     |
| Enabled  | 3         | 25%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 58.33%  |
| 32.01-64.0 | 2         | 16.67%  |
| 3.01-4.0   | 1         | 8.33%   |
| 16.01-24.0 | 1         | 8.33%   |
| 8.01-16.0  | 1         | 8.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 3.01-4.0 | 5         | 38.46%  |
| 2.01-3.0 | 5         | 38.46%  |
| 1.01-2.0 | 2         | 15.38%  |
| 4.01-8.0 | 1         | 7.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 9         | 75%     |
| 2      | 2         | 16.67%  |
| 5      | 1         | 8.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11        | 91.67%  |
| Yes       | 1         | 8.33%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6         | 50%     |
| No        | 6         | 50%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 11        | 91.67%  |
| No        | 1         | 8.33%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| USA     | 3         | 25%     |
| Canada  | 2         | 16.67%  |
| Sweden  | 1         | 8.33%   |
| Spain   | 1         | 8.33%   |
| Poland  | 1         | 8.33%   |
| Japan   | 1         | 8.33%   |
| India   | 1         | 8.33%   |
| Germany | 1         | 8.33%   |
| Brazil  | 1         | 8.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Yakima         | 1         | 7.14%   |
| Wroclaw        | 1         | 7.14%   |
| Whittier       | 1         | 7.14%   |
| Seattle        | 1         | 7.14%   |
| Raesfeld       | 1         | 7.14%   |
| Porto Ferreira | 1         | 7.14%   |
| Osaka          | 1         | 7.14%   |
| Montreal       | 1         | 7.14%   |
| Madrid         | 1         | 7.14%   |
| Laurel         | 1         | 7.14%   |
| Handen         | 1         | 7.14%   |
| Concord        | 1         | 7.14%   |
| Bolszewo       | 1         | 7.14%   |
| Bengaluru      | 1         | 7.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 25%     |
| Unknown             | 2         | 2      | 12.5%   |
| Toshiba             | 2         | 2      | 12.5%   |
| Sandisk             | 2         | 3      | 12.5%   |
| Samsung Electronics | 2         | 9      | 12.5%   |
| SK Hynix            | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| LITEON              | 1         | 1      | 6.25%   |
| ASMT                | 1         | 1      | 6.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 5.88%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 5.88%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 1         | 5.88%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB | 1         | 5.88%   |
| Unknown SSD0240S00 240GB             | 1         | 5.88%   |
| Unknown SD256  249GB                 | 1         | 5.88%   |
| Toshiba KXG60ZNV256G NVMe 256GB      | 1         | 5.88%   |
| Toshiba KXG50ZNV512G NVMe 512GB      | 1         | 5.88%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 5.88%   |
| SanDisk SDSSDH3512G 512GB            | 1         | 5.88%   |
| Sandisk NVMe SSD Drive 256GB         | 1         | 5.88%   |
| Samsung SSD 850 PRO 1TB              | 1         | 5.88%   |
| Samsung SSD 850 EVO mSATA 1TB        | 1         | 5.88%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 1         | 5.88%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 5.88%   |
| LITEON CX2-8B256-Q11 NVMe 256GB      | 1         | 5.88%   |
| ASMT ASM105x 500GB                   | 1         | 5.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 66.67%  |
| ASMT   | 1         | 1      | 33.33%  |

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
| NVMe | 7         | 9      | 50%     |
| SSD  | 3         | 12     | 21.43%  |
| HDD  | 3         | 3      | 21.43%  |
| MMC  | 1         | 1      | 7.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 7         | 9      | 50%     |
| SATA | 5         | 14     | 35.71%  |
| SAS  | 1         | 1      | 7.14%   |
| MMC  | 1         | 1      | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4         | 4      | 66.67%  |
| 0.51-1.0   | 2         | 11     | 33.33%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 4         | 30.77%  |
| 1-20       | 4         | 30.77%  |
| 101-250    | 3         | 23.08%  |
| 21-50      | 1         | 7.69%   |
| 501-1000   | 1         | 7.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 6         | 50%     |
| 21-50   | 4         | 33.33%  |
| 101-250 | 2         | 16.67%  |

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
| Works    | 10        | 11     | 66.67%  |
| Detected | 5         | 14     | 33.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 8         | 50%     |
| Toshiba America Info Systems | 2         | 12.5%   |
| Sandisk                      | 2         | 12.5%   |
| SK Hynix                     | 1         | 6.25%   |
| Samsung Electronics          | 1         | 6.25%   |
| Lite-On Technology           | 1         | 6.25%   |
| AMD                          | 1         | 6.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 18.75%  |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 12.5%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 6.25%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 6.25%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 6.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 6.25%   |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 6.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 6.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 6.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 6.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 6.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 6.25%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 6.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 8         | 50%     |
| NVMe | 7         | 43.75%  |
| RAID | 1         | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 9         | 75%     |
| AMD    | 3         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 8.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 8.33%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 8.33%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 8.33%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 8.33%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 8.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 8.33%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 8.33%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 8.33%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 8.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 8.33%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 8.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 6         | 50%     |
| Intel Core i5 | 2         | 16.67%  |
| AMD Ryzen 5   | 2         | 16.67%  |
| Intel Core i3 | 1         | 8.33%   |
| AMD Ryzen 3   | 1         | 8.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 7         | 58.33%  |
| 2      | 3         | 25%     |
| 6      | 2         | 16.67%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 12        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 11        | 91.67%  |
| 1      | 1         | 8.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 12        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x506e3    | 2         | 16.67%  |
| 0x306c3    | 2         | 16.67%  |
| 0x08108109 | 2         | 16.67%  |
| 0x906ea    | 1         | 8.33%   |
| 0x806ec    | 1         | 8.33%   |
| 0x806ea    | 1         | 8.33%   |
| 0x806e9    | 1         | 8.33%   |
| 0x406e3    | 1         | 8.33%   |
| 0x08600104 | 1         | 8.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KabyLake | 4         | 33.33%  |
| Skylake  | 3         | 25%     |
| Zen+     | 2         | 16.67%  |
| Haswell  | 2         | 16.67%  |
| Zen 2    | 1         | 8.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 8         | 50%     |
| Nvidia | 5         | 31.25%  |
| AMD    | 3         | 18.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 530                                       | 2         | 12.5%   |
| AMD Picasso                                                 | 2         | 12.5%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                  | 1         | 6.25%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                     | 1         | 6.25%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                        | 1         | 6.25%   |
| Nvidia GM107M [GeForce GTX 960M]                            | 1         | 6.25%   |
| Nvidia GK106GLM [Quadro K2100M]                             | 1         | 6.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                  | 1         | 6.25%   |
| Intel UHD Graphics 620                                      | 1         | 6.25%   |
| Intel Skylake GT2 [HD Graphics 520]                         | 1         | 6.25%   |
| Intel HD Graphics 620                                       | 1         | 6.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                   | 1         | 6.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller | 1         | 6.25%   |
| AMD Renoir                                                  | 1         | 6.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 4         | 33.33%  |
| 1 x Intel      | 4         | 33.33%  |
| 1 x AMD        | 3         | 25%     |
| 1 x Nvidia     | 1         | 8.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 11        | 84.62%  |
| Proprietary | 2         | 15.38%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 46.15%  |
| 1.01-2.0   | 3         | 23.08%  |
| 7.01-8.0   | 1         | 7.69%   |
| 3.01-4.0   | 1         | 7.69%   |
| 0.51-1.0   | 1         | 7.69%   |
| 0.01-0.5   | 1         | 7.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| AU Optronics   | 5         | 35.71%  |
| Chimei Innolux | 3         | 21.43%  |
| Sharp          | 2         | 14.29%  |
| LG Display     | 1         | 7.14%   |
| Goldstar       | 1         | 7.14%   |
| Dell           | 1         | 7.14%   |
| BOE            | 1         | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch          | 1         | 6.67%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch          | 1         | 6.67%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch     | 1         | 6.67%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch        | 1         | 6.67%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                | 1         | 6.67%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                | 1         | 6.67%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch | 1         | 6.67%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch  | 1         | 6.67%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch | 1         | 6.67%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch            | 1         | 6.67%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch   | 1         | 6.67%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch   | 1         | 6.67%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch   | 1         | 6.67%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch   | 1         | 6.67%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch   | 1         | 6.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 9         | 75%     |
| 3840x2160 (4K)  | 1         | 8.33%   |
| 2160x1440       | 1         | 8.33%   |
| 1366x768 (WXGA) | 1         | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 7         | 50%     |
| 21     | 2         | 14.29%  |
| 14     | 2         | 14.29%  |
| 13     | 2         | 14.29%  |
| 17     | 1         | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 64.29%  |
| 401-500     | 2         | 14.29%  |
| 201-300     | 2         | 14.29%  |
| 351-400     | 1         | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 11        | 91.67%  |
| 3/2   | 1         | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 50%     |
| 81-90          | 3         | 21.43%  |
| 201-250        | 2         | 14.29%  |
| 71-80          | 1         | 7.14%   |
| 121-130        | 1         | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 8         | 57.14%  |
| 101-120       | 3         | 21.43%  |
| 161-240       | 2         | 14.29%  |
| More than 240 | 1         | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11        | 84.62%  |
| 3     | 1         | 7.69%   |
| 2     | 1         | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 7         | 41.18%  |
| Intel                 | 6         | 35.29%  |
| Qualcomm Atheros      | 3         | 17.65%  |
| Sierra Wireless       | 1         | 5.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 15%     |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 10%     |
| Intel Wireless-AC 9260                                            | 2         | 10%     |
| Intel Wireless 7260                                               | 2         | 10%     |
| Sierra Wireless EM7455                                            | 1         | 5%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 5%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 5%      |
| Intel Wireless 8265 / 8275                                        | 1         | 5%      |
| Intel Wireless 8260                                               | 1         | 5%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 5%      |
| Intel Ethernet Connection (4) I219-V                              | 1         | 5%      |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 5%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 6         | 46.15%  |
| Realtek Semiconductor | 3         | 23.08%  |
| Qualcomm Atheros      | 3         | 23.08%  |
| Sierra Wireless       | 1         | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 15.38%  |
| Intel Wireless-AC 9260                                     | 2         | 15.38%  |
| Intel Wireless 7260                                        | 2         | 15.38%  |
| Sierra Wireless EM7455                                     | 1         | 7.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 7.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 7.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 7.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 7.69%   |
| Intel Wireless 8265 / 8275                                 | 1         | 7.69%   |
| Intel Wireless 8260                                        | 1         | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 4         | 57.14%  |
| Intel                 | 3         | 42.86%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 42.86%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 14.29%  |
| Intel Ethernet Connection I217-LM                                 | 1         | 14.29%  |
| Intel Ethernet Connection (4) I219-V                              | 1         | 14.29%  |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 14.29%  |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 12        | 66.67%  |
| Ethernet | 6         | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 10        | 66.67%  |
| Ethernet | 5         | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6         | 50%     |
| 1     | 6         | 50%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 10        | 83.33%  |
| Yes  | 2         | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5         | 45.45%  |
| Realtek               | 2         | 18.18%  |
| Foxconn / Hon Hai     | 2         | 18.18%  |
| Realtek Semiconductor | 1         | 9.09%   |
| Lite-On Technology    | 1         | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface         | 3         | 27.27%  |
| Realtek Bluetooth Radio                    | 2         | 18.18%  |
| Intel Bluetooth Device                     | 2         | 18.18%  |
| Foxconn / Hon Hai Bluetooth Device         | 2         | 18.18%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter    | 1         | 9.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 56.25%  |
| AMD                   | 3         | 18.75%  |
| Nvidia                | 2         | 12.5%   |
| Realtek Semiconductor | 1         | 6.25%   |
| Micronas              | 1         | 6.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 3         | 15%     |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 3         | 15%     |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 10%     |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 10%     |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 10%     |
| Realtek Semiconductor USB Audio                                     | 1         | 5%      |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 5%      |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 5%      |
| Micronas BLUE USB Audio 2.0                                         | 1         | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 5%      |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 5%      |
| Intel Cannon Lake PCH cAVS                                          | 1         | 5%      |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 5%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 4         | 36.36%  |
| Samsung Electronics | 4         | 36.36%  |
| Micron Technology   | 1         | 9.09%   |
| Crucial             | 1         | 9.09%   |
| A-DATA Technology   | 1         | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s    | 1         | 9.09%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 9.09%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 9.09%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 9.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 1         | 9.09%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 1         | 9.09%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s  | 1         | 9.09%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 9.09%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s        | 1         | 9.09%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2667MT/s   | 1         | 9.09%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s         | 1         | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 72.73%  |
| LPDDR4 | 1         | 9.09%   |
| LPDDR3 | 1         | 9.09%   |
| DDR3   | 1         | 9.09%   |

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


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 6         | 54.55%  |
| 4096  | 4         | 36.36%  |
| 16384 | 1         | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 8         | 72.73%  |
| 2400  | 1         | 9.09%   |
| 2133  | 1         | 9.09%   |
| 1867  | 1         | 9.09%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| IMC Networks                  | 4         | 36.36%  |
| Chicony Electronics           | 3         | 27.27%  |
| Microdia                      | 2         | 18.18%  |
| Sunplus Innovation Technology | 1         | 9.09%   |
| Quanta                        | 1         | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD        | 2         | 16.67%  |
| IMC Networks Integrated Camera       | 2         | 16.67%  |
| Sunplus Dell E5570 integrated webcam | 1         | 8.33%   |
| Quanta VGA WebCam                    | 1         | 8.33%   |
| IMC Networks ov9734_azurewave_camera | 1         | 8.33%   |
| IMC Networks HD Camera               | 1         | 8.33%   |
| Chicony VGA Webcam                   | 1         | 8.33%   |
| Chicony USB2.0 2M WebCam             | 1         | 8.33%   |
| Chicony USB 5M WebCam                | 1         | 8.33%   |
| Chicony Integrated Camera            | 1         | 8.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Shenzhen Goodix Technology | 2         | 40%     |
| LighTuning Technology      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device          | 2         | 40%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 20%     |
| Validity Sensors Synaptics WBDI              | 1         | 20%     |
| LighTuning ES603 Swipe Fingerprint Sensor    | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 7         | 58.33%  |
| 1     | 5         | 41.67%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 5         | 100%    |

