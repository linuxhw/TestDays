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
| 5.14.0-0.rc5.42.fc35.x86_64                          | 5         | 38.46%  |
| 5.14.0-0.rc6.46.fc35.x86_64                          | 1         | 7.69%   |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 7.69%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 7.69%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 7.69%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 7.69%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 7.69%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 7.69%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 7.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 8         | 66.67%  |
| 5.12.0  | 2         | 16.67%  |
| 5.13.0  | 1         | 8.33%   |
| 5.12.8  | 1         | 8.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 8         | 66.67%  |
| 5.12    | 3         | 25%     |
| 5.13    | 1         | 8.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 11        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 11        | 91.67%  |
| KDE   | 1         | 8.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 10        | 90.91%  |
| X11     | 1         | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 9         | 81.82%  |
| Unknown | 2         | 18.18%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 7         | 58.33%  |
| sv_SE | 1         | 8.33%   |
| ru_RU | 1         | 8.33%   |
| pl_PL | 1         | 8.33%   |
| es_ES | 1         | 8.33%   |
| en_CA | 1         | 8.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 10        | 90.91%  |
| BIOS | 1         | 9.09%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 6         | 50%     |
| Btrfs | 5         | 41.67%  |
| Xfs   | 1         | 8.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 9         | 81.82%  |
| Unknown | 2         | 18.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6         | 50%     |
| No        | 6         | 50%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10        | 83.33%  |
| Yes       | 2         | 16.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Dell     | 4         | 36.36%  |
| Lenovo   | 2         | 18.18%  |
| HUAWEI   | 2         | 18.18%  |
| Acer     | 2         | 18.18%  |
| Notebook | 1         | 9.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Notebook P377SM-A               | 1         | 9.09%   |
| Lenovo ThinkPad W541 20EF000UMN | 1         | 9.09%   |
| Lenovo IdeaPad 530S-14IKB 81EU  | 1         | 9.09%   |
| HUAWEI KLVL-WXX9                | 1         | 9.09%   |
| HUAWEI BOHK-WAX9X               | 1         | 9.09%   |
| Dell XPS 15 9570                | 1         | 9.09%   |
| Dell XPS 15 9550                | 1         | 9.09%   |
| Dell XPS 13 9380                | 1         | 9.09%   |
| Dell Latitude E5470             | 1         | 9.09%   |
| Acer Aspire ES1-572             | 1         | 9.09%   |
| Acer Aspire A315-42             | 1         | 9.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell XPS          | 3         | 27.27%  |
| Acer Aspire       | 2         | 18.18%  |
| Notebook P377SM-A | 1         | 9.09%   |
| Lenovo ThinkPad   | 1         | 9.09%   |
| Lenovo IdeaPad    | 1         | 9.09%   |
| HUAWEI KLVL-WXX9  | 1         | 9.09%   |
| HUAWEI BOHK-WAX9X | 1         | 9.09%   |
| Dell Latitude     | 1         | 9.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 54.55%  |
| 2021 | 2         | 18.18%  |
| 2019 | 2         | 18.18%  |
| 2015 | 1         | 9.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 11        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 8         | 72.73%  |
| Enabled  | 3         | 27.27%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 11        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 63.64%  |
| 32.01-64.0 | 2         | 18.18%  |
| 3.01-4.0   | 1         | 9.09%   |
| 8.01-16.0  | 1         | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 5         | 41.67%  |
| 3.01-4.0 | 4         | 33.33%  |
| 1.01-2.0 | 2         | 16.67%  |
| 4.01-8.0 | 1         | 8.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 8         | 72.73%  |
| 2      | 2         | 18.18%  |
| 5      | 1         | 9.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10        | 90.91%  |
| Yes       | 1         | 9.09%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6         | 54.55%  |
| Yes       | 5         | 45.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 11        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 90.91%  |
| No        | 1         | 9.09%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| USA     | 3         | 27.27%  |
| Canada  | 2         | 18.18%  |
| Sweden  | 1         | 9.09%   |
| Spain   | 1         | 9.09%   |
| Poland  | 1         | 9.09%   |
| Japan   | 1         | 9.09%   |
| Germany | 1         | 9.09%   |
| Brazil  | 1         | 9.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Yakima         | 1         | 7.69%   |
| Wroclaw        | 1         | 7.69%   |
| Whittier       | 1         | 7.69%   |
| Seattle        | 1         | 7.69%   |
| Raesfeld       | 1         | 7.69%   |
| Porto Ferreira | 1         | 7.69%   |
| Osaka          | 1         | 7.69%   |
| Montreal       | 1         | 7.69%   |
| Madrid         | 1         | 7.69%   |
| Laurel         | 1         | 7.69%   |
| Handen         | 1         | 7.69%   |
| Concord        | 1         | 7.69%   |
| Bolszewo       | 1         | 7.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 4      | 20%     |
| Unknown             | 2         | 2      | 13.33%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Sandisk             | 2         | 3      | 13.33%  |
| Samsung Electronics | 2         | 9      | 13.33%  |
| SK Hynix            | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| LITEON              | 1         | 1      | 6.67%   |
| ASMT                | 1         | 1      | 6.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 6.25%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 1         | 6.25%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB | 1         | 6.25%   |
| Unknown SSD0240S00 240GB             | 1         | 6.25%   |
| Unknown SD256  249GB                 | 1         | 6.25%   |
| Toshiba KXG60ZNV256G NVMe 256GB      | 1         | 6.25%   |
| Toshiba KXG50ZNV512G NVMe 512GB      | 1         | 6.25%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 6.25%   |
| SanDisk SDSSDH3512G 512GB            | 1         | 6.25%   |
| Sandisk NVMe SSD Drive 256GB         | 1         | 6.25%   |
| Samsung SSD 850 PRO 1TB              | 1         | 6.25%   |
| Samsung SSD 850 EVO mSATA 1TB        | 1         | 6.25%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 1         | 6.25%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 6.25%   |
| LITEON CX2-8B256-Q11 NVMe 256GB      | 1         | 6.25%   |
| ASMT ASM105x 250GB                   | 1         | 6.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| ASMT   | 1         | 1      | 50%     |

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
| NVMe | 7         | 9      | 53.85%  |
| SSD  | 3         | 12     | 23.08%  |
| HDD  | 2         | 2      | 15.38%  |
| MMC  | 1         | 1      | 7.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 7         | 9      | 53.85%  |
| SATA | 4         | 13     | 30.77%  |
| SAS  | 1         | 1      | 7.69%   |
| MMC  | 1         | 1      | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3         | 3      | 60%     |
| 0.51-1.0   | 2         | 11     | 40%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 4         | 33.33%  |
| 1-20       | 4         | 33.33%  |
| 101-250    | 2         | 16.67%  |
| 21-50      | 1         | 8.33%   |
| 501-1000   | 1         | 8.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 6         | 54.55%  |
| 21-50   | 3         | 27.27%  |
| 101-250 | 2         | 18.18%  |

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
| Works    | 9         | 10     | 64.29%  |
| Detected | 5         | 14     | 35.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 7         | 46.67%  |
| Toshiba America Info Systems | 2         | 13.33%  |
| Sandisk                      | 2         | 13.33%  |
| SK Hynix                     | 1         | 6.67%   |
| Samsung Electronics          | 1         | 6.67%   |
| Lite-On Technology           | 1         | 6.67%   |
| AMD                          | 1         | 6.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 13.33%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 13.33%  |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 6.67%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 6.67%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 6.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 6.67%   |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 6.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 6.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 6.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 6.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 6.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 6.67%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 6.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 7         | 46.67%  |
| SATA | 7         | 46.67%  |
| RAID | 1         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 8         | 72.73%  |
| AMD    | 3         | 27.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 9.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 9.09%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 9.09%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 9.09%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 9.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 9.09%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 9.09%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 9.09%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 9.09%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 9.09%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 9.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 5         | 45.45%  |
| Intel Core i5 | 2         | 18.18%  |
| AMD Ryzen 5   | 2         | 18.18%  |
| Intel Core i3 | 1         | 9.09%   |
| AMD Ryzen 3   | 1         | 9.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 7         | 63.64%  |
| 6      | 2         | 18.18%  |
| 2      | 2         | 18.18%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 11        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 10        | 90.91%  |
| 1      | 1         | 9.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x506e3    | 2         | 18.18%  |
| 0x306c3    | 2         | 18.18%  |
| 0x08108109 | 2         | 18.18%  |
| 0x906ea    | 1         | 9.09%   |
| 0x806ec    | 1         | 9.09%   |
| 0x806ea    | 1         | 9.09%   |
| 0x406e3    | 1         | 9.09%   |
| 0x08600104 | 1         | 9.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Skylake  | 3         | 27.27%  |
| KabyLake | 3         | 27.27%  |
| Zen+     | 2         | 18.18%  |
| Haswell  | 2         | 18.18%  |
| Zen 2    | 1         | 9.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 7         | 50%     |
| Nvidia | 4         | 28.57%  |
| AMD    | 3         | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 530                                       | 2         | 14.29%  |
| AMD Picasso                                                 | 2         | 14.29%  |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                  | 1         | 7.14%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                     | 1         | 7.14%   |
| Nvidia GM107M [GeForce GTX 960M]                            | 1         | 7.14%   |
| Nvidia GK106GLM [Quadro K2100M]                             | 1         | 7.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                  | 1         | 7.14%   |
| Intel UHD Graphics 620                                      | 1         | 7.14%   |
| Intel Skylake GT2 [HD Graphics 520]                         | 1         | 7.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                   | 1         | 7.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller | 1         | 7.14%   |
| AMD Renoir                                                  | 1         | 7.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 4         | 36.36%  |
| Intel + Nvidia | 3         | 27.27%  |
| 1 x AMD        | 3         | 27.27%  |
| 1 x Nvidia     | 1         | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 11        | 91.67%  |
| Proprietary | 1         | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 41.67%  |
| 1.01-2.0   | 3         | 25%     |
| 7.01-8.0   | 1         | 8.33%   |
| 3.01-4.0   | 1         | 8.33%   |
| 0.51-1.0   | 1         | 8.33%   |
| 0.01-0.5   | 1         | 8.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| AU Optronics   | 5         | 41.67%  |
| Sharp          | 2         | 16.67%  |
| Chimei Innolux | 2         | 16.67%  |
| LG Display     | 1         | 8.33%   |
| Dell           | 1         | 8.33%   |
| BOE            | 1         | 8.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch          | 1         | 7.69%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch          | 1         | 7.69%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch     | 1         | 7.69%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                | 1         | 7.69%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                | 1         | 7.69%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch  | 1         | 7.69%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch | 1         | 7.69%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch            | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch   | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch   | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch   | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch   | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch   | 1         | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 8         | 72.73%  |
| 3840x2160 (4K)  | 1         | 9.09%   |
| 2160x1440       | 1         | 9.09%   |
| 1366x768 (WXGA) | 1         | 9.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 6         | 50%     |
| 14     | 2         | 16.67%  |
| 13     | 2         | 16.67%  |
| 21     | 1         | 8.33%   |
| 17     | 1         | 8.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 8         | 66.67%  |
| 201-300     | 2         | 16.67%  |
| 401-500     | 1         | 8.33%   |
| 351-400     | 1         | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 10        | 90.91%  |
| 3/2   | 1         | 9.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 6         | 50%     |
| 81-90          | 3         | 25%     |
| 71-80          | 1         | 8.33%   |
| 201-250        | 1         | 8.33%   |
| 121-130        | 1         | 8.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 7         | 58.33%  |
| 161-240       | 2         | 16.67%  |
| 101-120       | 2         | 16.67%  |
| More than 240 | 1         | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11        | 91.67%  |
| 3     | 1         | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 6         | 42.86%  |
| Intel                 | 5         | 35.71%  |
| Qualcomm Atheros      | 3         | 21.43%  |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 18.75%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 12.5%   |
| Intel Wireless-AC 9260                                            | 2         | 12.5%   |
| Intel Wireless 7260                                               | 2         | 12.5%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 6.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 6.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 6.25%   |
| Intel Wireless 8260                                               | 1         | 6.25%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 6.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 6.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5         | 45.45%  |
| Realtek Semiconductor | 3         | 27.27%  |
| Qualcomm Atheros      | 3         | 27.27%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 18.18%  |
| Intel Wireless-AC 9260                                     | 2         | 18.18%  |
| Intel Wireless 7260                                        | 2         | 18.18%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 9.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 9.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 9.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 9.09%   |
| Intel Wireless 8260                                        | 1         | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 3         | 60%     |
| Intel                 | 2         | 40%     |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 60%     |
| Intel Ethernet Connection I217-LM                                 | 1         | 20%     |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 20%     |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 11        | 68.75%  |
| Ethernet | 5         | 31.25%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9         | 64.29%  |
| Ethernet | 5         | 35.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6         | 54.55%  |
| 2     | 5         | 45.45%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 9         | 81.82%  |
| Yes  | 2         | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 4         | 40%     |
| Realtek               | 2         | 20%     |
| Foxconn / Hon Hai     | 2         | 20%     |
| Realtek Semiconductor | 1         | 10%     |
| Lite-On Technology    | 1         | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                    | 2         | 20%     |
| Intel Wireless-AC 9260 Bluetooth Adapter   | 2         | 20%     |
| Intel Bluetooth wireless interface         | 2         | 20%     |
| Foxconn / Hon Hai Bluetooth Device         | 2         | 20%     |
| Realtek RTL8822BE Bluetooth 4.2 Adapter    | 1         | 10%     |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 8         | 57.14%  |
| AMD      | 3         | 21.43%  |
| Nvidia   | 2         | 14.29%  |
| Micronas | 1         | 7.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 3         | 16.67%  |
| Intel Sunrise Point-LP HD Audio                                     | 2         | 11.11%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 11.11%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 11.11%  |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 11.11%  |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 5.56%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 5.56%   |
| Micronas BLUE USB Audio 2.0                                         | 1         | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 5.56%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 5.56%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 5.56%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 5.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 4         | 40%     |
| Samsung Electronics | 3         | 30%     |
| Micron Technology   | 1         | 10%     |
| Crucial             | 1         | 10%     |
| A-DATA Technology   | 1         | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s     | 1         | 10%     |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 10%     |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 10%     |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s     | 1         | 10%     |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s   | 1         | 10%     |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s   | 1         | 10%     |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s  | 1         | 10%     |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s         | 1         | 10%     |
| Crucial RAM CT16G4SFD8266.C16FD1 16384MB SODIMM DDR4 2667MT/s | 1         | 10%     |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s          | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 7         | 70%     |
| LPDDR4 | 1         | 10%     |
| LPDDR3 | 1         | 10%     |
| DDR3   | 1         | 10%     |

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
| 8192  | 5         | 50%     |
| 4096  | 4         | 40%     |
| 16384 | 1         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 7         | 70%     |
| 2400  | 1         | 10%     |
| 2133  | 1         | 10%     |
| 1867  | 1         | 10%     |

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
| IMC Networks                  | 3         | 30%     |
| Chicony Electronics           | 3         | 30%     |
| Microdia                      | 2         | 20%     |
| Sunplus Innovation Technology | 1         | 10%     |
| Quanta                        | 1         | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD        | 2         | 18.18%  |
| Sunplus Dell E5570 integrated webcam | 1         | 9.09%   |
| Quanta VGA WebCam                    | 1         | 9.09%   |
| IMC Networks ov9734_azurewave_camera | 1         | 9.09%   |
| IMC Networks Integrated Camera       | 1         | 9.09%   |
| IMC Networks HD Camera               | 1         | 9.09%   |
| Chicony VGA Webcam                   | 1         | 9.09%   |
| Chicony USB2.0 2M WebCam             | 1         | 9.09%   |
| Chicony USB 5M WebCam                | 1         | 9.09%   |
| Chicony Integrated Camera            | 1         | 9.09%   |

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
| LighTuning EgisTec_ES603                     | 1         | 25%     |

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
| 0     | 7         | 63.64%  |
| 1     | 4         | 36.36%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 4         | 100%    |

