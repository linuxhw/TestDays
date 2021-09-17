Fedora 35 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | ZBook 15u G5                | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| Dell     | XPS 17 9700                 | [ebac1c499f](https://linux-hardware.org/?probe=ebac1c499f) | Sep 15, 2021 |
| ASUSTek  | G71V                        | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Lenovo   | ThinkPad X1 Carbon Gen 8... | [2b21ef140a](https://linux-hardware.org/?probe=2b21ef140a) | Sep 05, 2021 |
| Lenovo   | ThinkPad P51s 20HBCTO1WW    | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
| Dell     | Latitude E5470              | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
| Dell     | XPS 15 9550                 | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer     | Aspire A315-42              | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer     | Aspire ES1-572              | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell     | XPS 15 9570                 | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell     | XPS 13 9380                 | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo   | IdeaPad 530S-14IKB 81EU     | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| Notebook | P377SM-A                    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI   | KLVL-WXX9                   | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| HUAWEI   | KLVL-WXX9                   | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Notebook | P377SM-A                    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook | P377SM-A                    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Lenovo   | ThinkPad W541 20EF000UMN    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI   | BOHK-WAX9X                  | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                              | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| 5.14.0-0.rc5.42.fc35.x86_64                          | 5         | 27.78%  |
| 5.14.3-300.fc35.x86_64                               | 2         | 11.11%  |
| 5.14.1-300.fc35.x86_64                               | 1         | 5.56%   |
| 5.14.0-60.fc35.x86_64                                | 1         | 5.56%   |
| 5.14.0-0.rc6.46.fc35.x86_64                          | 1         | 5.56%   |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 5.56%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 5.56%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 5.56%   |
| 5.13.4-200.fc34.x86_64                               | 1         | 5.56%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 5.56%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 5.56%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 5.56%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 5.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 9         | 52.94%  |
| 5.14.3  | 2         | 11.76%  |
| 5.12.0  | 2         | 11.76%  |
| 5.14.1  | 1         | 5.88%   |
| 5.13.4  | 1         | 5.88%   |
| 5.13.0  | 1         | 5.88%   |
| 5.12.8  | 1         | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 12        | 70.59%  |
| 5.12    | 3         | 17.65%  |
| 5.13    | 2         | 11.76%  |

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


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 15        | 88.24%  |
| MATE  | 1         | 5.88%   |
| KDE   | 1         | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 13        | 81.25%  |
| X11     | 3         | 18.75%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 12        | 75%     |
| Unknown | 3         | 18.75%  |
| LightDM | 1         | 6.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 12        | 70.59%  |
| sv_SE | 1         | 5.88%   |
| ru_RU | 1         | 5.88%   |
| pl_PL | 1         | 5.88%   |
| es_ES | 1         | 5.88%   |
| en_CA | 1         | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 14        | 87.5%   |
| BIOS | 2         | 12.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 10        | 58.82%  |
| Btrfs | 6         | 35.29%  |
| Xfs   | 1         | 5.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 12        | 75%     |
| Unknown | 3         | 18.75%  |
| MBR     | 1         | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 9         | 52.94%  |
| Yes       | 8         | 47.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14        | 82.35%  |
| Yes       | 3         | 17.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell             | 5         | 31.25%  |
| Lenovo           | 4         | 25%     |
| HUAWEI           | 2         | 12.5%   |
| Acer             | 2         | 12.5%   |
| Notebook         | 1         | 6.25%   |
| Hewlett-Packard  | 1         | 6.25%   |
| ASUSTek Computer | 1         | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Notebook P377SM-A                          | 1         | 6.25%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 6.25%   |
| Lenovo ThinkPad W541 20EF000UMN            | 1         | 6.25%   |
| Lenovo ThinkPad P51s 20HBCTO1WW            | 1         | 6.25%   |
| Lenovo IdeaPad 530S-14IKB 81EU             | 1         | 6.25%   |
| HUAWEI KLVL-WXX9                           | 1         | 6.25%   |
| HUAWEI BOHK-WAX9X                          | 1         | 6.25%   |
| HP ZBook 15u G5                            | 1         | 6.25%   |
| Dell XPS 17 9700                           | 1         | 6.25%   |
| Dell XPS 15 9570                           | 1         | 6.25%   |
| Dell XPS 15 9550                           | 1         | 6.25%   |
| Dell XPS 13 9380                           | 1         | 6.25%   |
| Dell Latitude E5470                        | 1         | 6.25%   |
| ASUS G71V                                  | 1         | 6.25%   |
| Acer Aspire ES1-572                        | 1         | 6.25%   |
| Acer Aspire A315-42                        | 1         | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell XPS          | 4         | 25%     |
| Lenovo ThinkPad   | 3         | 18.75%  |
| Acer Aspire       | 2         | 12.5%   |
| Notebook P377SM-A | 1         | 6.25%   |
| Lenovo IdeaPad    | 1         | 6.25%   |
| HUAWEI KLVL-WXX9  | 1         | 6.25%   |
| HUAWEI BOHK-WAX9X | 1         | 6.25%   |
| HP ZBook          | 1         | 6.25%   |
| Dell Latitude     | 1         | 6.25%   |
| ASUS G71V         | 1         | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 7         | 43.75%  |
| 2021 | 4         | 25%     |
| 2019 | 2         | 12.5%   |
| 2018 | 1         | 6.25%   |
| 2015 | 1         | 6.25%   |
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
| Disabled | 12        | 75%     |
| Enabled  | 4         | 25%     |

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
| 4.01-8.0   | 7         | 43.75%  |
| 32.01-64.0 | 3         | 18.75%  |
| 16.01-24.0 | 3         | 18.75%  |
| 8.01-16.0  | 2         | 12.5%   |
| 3.01-4.0   | 1         | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 6         | 35.29%  |
| 3.01-4.0 | 5         | 29.41%  |
| 1.01-2.0 | 4         | 23.53%  |
| 4.01-8.0 | 2         | 11.76%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13        | 81.25%  |
| 2      | 2         | 12.5%   |
| 5      | 1         | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14        | 87.5%   |
| Yes       | 2         | 12.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 62.5%   |
| No        | 6         | 37.5%   |

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
| Yes       | 15        | 93.75%  |
| No        | 1         | 6.25%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| USA     | 5         | 31.25%  |
| Canada  | 2         | 12.5%   |
| Sweden  | 1         | 6.25%   |
| Spain   | 1         | 6.25%   |
| Poland  | 1         | 6.25%   |
| Norway  | 1         | 6.25%   |
| Japan   | 1         | 6.25%   |
| India   | 1         | 6.25%   |
| Germany | 1         | 6.25%   |
| Brazil  | 1         | 6.25%   |
| Belarus | 1         | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Yakima         | 1         | 5.56%   |
| Wroclaw        | 1         | 5.56%   |
| Whittier       | 1         | 5.56%   |
| Seattle        | 1         | 5.56%   |
| Royse          | 1         | 5.56%   |
| Raesfeld       | 1         | 5.56%   |
| Porto Ferreira | 1         | 5.56%   |
| Osaka          | 1         | 5.56%   |
| Montreal       | 1         | 5.56%   |
| Minsk          | 1         | 5.56%   |
| Miami          | 1         | 5.56%   |
| Madrid         | 1         | 5.56%   |
| Laurel         | 1         | 5.56%   |
| Handen         | 1         | 5.56%   |
| Concord        | 1         | 5.56%   |
| Bolszewo       | 1         | 5.56%   |
| Bengaluru      | 1         | 5.56%   |
| Atlanta        | 1         | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 20%     |
| Samsung Electronics | 4         | 11     | 20%     |
| SanDisk             | 3         | 4      | 15%     |
| Unknown             | 2         | 2      | 10%     |
| Toshiba             | 2         | 2      | 10%     |
| SK Hynix            | 1         | 1      | 5%      |
| Micron Technology   | 1         | 1      | 5%      |
| LITEON              | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| ASMT                | 1         | 1      | 5%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Sandisk NVMe SSD Drive 256GB         | 2         | 9.52%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 4.76%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 4.76%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 1         | 4.76%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB | 1         | 4.76%   |
| Unknown SSD0240S00 240GB             | 1         | 4.76%   |
| Unknown SD256  249GB                 | 1         | 4.76%   |
| Toshiba KXG60ZNV256G NVMe 256GB      | 1         | 4.76%   |
| Toshiba KXG50ZNV512G NVMe 512GB      | 1         | 4.76%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 4.76%   |
| SanDisk SDSSDH3512G 512GB            | 1         | 4.76%   |
| Samsung SSD 850 PRO 1TB              | 1         | 4.76%   |
| Samsung SSD 850 EVO mSATA 1TB        | 1         | 4.76%   |
| Samsung PM9A1 NVMe 512GB             | 1         | 4.76%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 1         | 4.76%   |
| Samsung MZVLB512HAJQ-000H1 512GB     | 1         | 4.76%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 4.76%   |
| LITEON CX2-8B256-Q11 NVMe 256GB      | 1         | 4.76%   |
| Kingston SA400S37480G 480GB SSD      | 1         | 4.76%   |
| ASMT ASM105x 400GB SSD               | 1         | 4.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 1         | 1      | 16.67%  |
| SanDisk             | 1         | 2      | 16.67%  |
| Samsung Electronics | 1         | 8      | 16.67%  |
| Micron Technology   | 1         | 1      | 16.67%  |
| Kingston            | 1         | 1      | 16.67%  |
| ASMT                | 1         | 1      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 10        | 12     | 55.56%  |
| SSD  | 5         | 14     | 27.78%  |
| HDD  | 2         | 2      | 11.11%  |
| MMC  | 1         | 1      | 5.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 10        | 12     | 55.56%  |
| SATA | 6         | 15     | 33.33%  |
| SAS  | 1         | 1      | 5.56%   |
| MMC  | 1         | 1      | 5.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5         | 5      | 62.5%   |
| 0.51-1.0   | 2         | 7      | 25%     |
| 1.01-2.0   | 1         | 4      | 12.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 5         | 29.41%  |
| 101-250    | 5         | 29.41%  |
| 1-20       | 5         | 29.41%  |
| 21-50      | 1         | 5.88%   |
| 501-1000   | 1         | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 8         | 50%     |
| 21-50   | 4         | 25%     |
| 101-250 | 2         | 12.5%   |
| 251-500 | 1         | 6.25%   |
| 51-100  | 1         | 6.25%   |

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
| Works    | 13        | 14     | 68.42%  |
| Detected | 6         | 15     | 31.58%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 9         | 45%     |
| Sandisk                      | 3         | 15%     |
| Samsung Electronics          | 3         | 15%     |
| Toshiba America Info Systems | 2         | 10%     |
| SK Hynix                     | 1         | 5%      |
| Lite-On Technology           | 1         | 5%      |
| AMD                          | 1         | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 15%     |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 15%     |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 5%      |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 5%      |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 5%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 5%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 5%      |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 5%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 5%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 5%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 5%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 5%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 5%      |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 5%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 10        | 50%     |
| SATA | 9         | 45%     |
| RAID | 1         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 81.25%  |
| AMD    | 3         | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 6.25%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 6.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 6.25%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 6.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 6.25%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 6.25%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 6.25%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 6.25%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 6.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 6.25%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 6.25%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 6.25%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 6.25%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 6.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 6.25%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 9         | 56.25%  |
| Intel Core i5    | 2         | 12.5%   |
| AMD Ryzen 5      | 2         | 12.5%   |
| Intel Core i3    | 1         | 6.25%   |
| Intel Core 2 Duo | 1         | 6.25%   |
| AMD Ryzen 3      | 1         | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 9         | 56.25%  |
| 2      | 4         | 25%     |
| 6      | 3         | 18.75%  |

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
| 2      | 14        | 87.5%   |
| 1      | 2         | 12.5%   |

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
| 0x806ec    | 2         | 12.5%   |
| 0x806ea    | 2         | 12.5%   |
| 0x506e3    | 2         | 12.5%   |
| 0x306c3    | 2         | 12.5%   |
| 0x08108109 | 2         | 12.5%   |
| 0xa0652    | 1         | 6.25%   |
| 0x906ea    | 1         | 6.25%   |
| 0x806e9    | 1         | 6.25%   |
| 0x406e3    | 1         | 6.25%   |
| 0x10676    | 1         | 6.25%   |
| 0x08600104 | 1         | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 6         | 37.5%   |
| Skylake   | 3         | 18.75%  |
| Zen+      | 2         | 12.5%   |
| Haswell   | 2         | 12.5%   |
| Zen 2     | 1         | 6.25%   |
| Penryn    | 1         | 6.25%   |
| CometLake | 1         | 6.25%   |

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


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                      | 2         | 9.09%   |
| Intel HD Graphics 530                                       | 2         | 9.09%   |
| AMD Picasso                                                 | 2         | 9.09%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                  | 1         | 4.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                  | 1         | 4.55%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                     | 1         | 4.55%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                        | 1         | 4.55%   |
| Nvidia GM107M [GeForce GTX 960M]                            | 1         | 4.55%   |
| Nvidia GK106GLM [Quadro K2100M]                             | 1         | 4.55%   |
| Nvidia G96M [GeForce 9700M GT]                              | 1         | 4.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                  | 1         | 4.55%   |
| Intel Skylake GT2 [HD Graphics 520]                         | 1         | 4.55%   |
| Intel HD Graphics 620                                       | 1         | 4.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                        | 1         | 4.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                        | 1         | 4.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                   | 1         | 4.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller | 1         | 4.55%   |
| AMD Renoir                                                  | 1         | 4.55%   |
| AMD Lexa XT [Radeon PRO WX 3100]                            | 1         | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 5         | 31.25%  |
| 1 x Intel      | 5         | 31.25%  |
| 1 x AMD        | 3         | 18.75%  |
| 1 x Nvidia     | 2         | 12.5%   |
| Intel + AMD    | 1         | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 14        | 82.35%  |
| Proprietary | 3         | 17.65%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 47.06%  |
| 1.01-2.0   | 4         | 23.53%  |
| 0.01-0.5   | 2         | 11.76%  |
| 7.01-8.0   | 1         | 5.88%   |
| 3.01-4.0   | 1         | 5.88%   |
| 0.51-1.0   | 1         | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| AU Optronics    | 6         | 30%     |
| Sharp           | 3         | 15%     |
| LG Display      | 3         | 15%     |
| Chimei Innolux  | 3         | 15%     |
| Dell            | 2         | 10%     |
| Hewlett-Packard | 1         | 5%      |
| Goldstar        | 1         | 5%      |
| BOE             | 1         | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14D7 1920x1200 366x229mm 17.0-inch          | 1         | 4.76%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch          | 1         | 4.76%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch          | 1         | 4.76%   |
| LG Display LCD Monitor LGD05EE 2560x1440 309x174mm 14.0-inch     | 1         | 4.76%   |
| LG Display LCD Monitor LGD056E 1920x1080 344x194mm 15.5-inch     | 1         | 4.76%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch     | 1         | 4.76%   |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch       | 1         | 4.76%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch        | 1         | 4.76%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                | 1         | 4.76%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                | 1         | 4.76%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch  | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch | 1         | 4.76%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch            | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch   | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch   | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch   | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch   | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch   | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO1088 1920x1200 367x229mm 17.0-inch   | 1         | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 10        | 58.82%  |
| 3840x2160 (4K)    | 2         | 11.76%  |
| 1920x1200 (WUXGA) | 2         | 11.76%  |
| 2560x1440 (QHD)   | 1         | 5.88%   |
| 2160x1440         | 1         | 5.88%   |
| 1366x768 (WXGA)   | 1         | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 8         | 38.1%   |
| 17     | 3         | 14.29%  |
| 14     | 3         | 14.29%  |
| 27     | 2         | 9.52%   |
| 21     | 2         | 9.52%   |
| 13     | 2         | 9.52%   |
| 24     | 1         | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 52.38%  |
| 501-600     | 3         | 14.29%  |
| 351-400     | 3         | 14.29%  |
| 401-500     | 2         | 9.52%   |
| 201-300     | 2         | 9.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 13        | 81.25%  |
| 16/10 | 2         | 12.5%   |
| 3/2   | 1         | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 38.1%   |
| 81-90          | 4         | 19.05%  |
| 121-130        | 3         | 14.29%  |
| 301-350        | 2         | 9.52%   |
| 201-250        | 2         | 9.52%   |
| 71-80          | 1         | 4.76%   |
| 251-300        | 1         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 52.38%  |
| 161-240       | 4         | 19.05%  |
| 101-120       | 3         | 14.29%  |
| 51-100        | 2         | 9.52%   |
| More than 240 | 1         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 13        | 76.47%  |
| 2     | 3         | 17.65%  |
| 3     | 1         | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 41.67%  |
| Realtek Semiconductor | 9         | 37.5%   |
| Qualcomm Atheros      | 3         | 12.5%   |
| Sierra Wireless       | 1         | 4.17%   |
| Broadcom              | 1         | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 13.79%  |
| Intel Wireless 7260                                               | 3         | 10.34%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 6.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 6.9%    |
| Intel Wireless-AC 9260                                            | 2         | 6.9%    |
| Intel Wireless 8265 / 8275                                        | 2         | 6.9%    |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 1         | 3.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 3.45%   |
| Intel Wireless 8260                                               | 1         | 3.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.45%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 3.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 3.45%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 3.45%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 3.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 58.82%  |
| Realtek Semiconductor | 3         | 17.65%  |
| Qualcomm Atheros      | 3         | 17.65%  |
| Sierra Wireless       | 1         | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                        | 3         | 17.65%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 11.76%  |
| Intel Wireless-AC 9260                                     | 2         | 11.76%  |
| Intel Wireless 8265 / 8275                                 | 2         | 11.76%  |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A        | 1         | 5.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 5.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 5.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 5.88%   |
| Intel Wireless 8260                                        | 1         | 5.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 5.88%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 6         | 50%     |
| Intel                 | 5         | 41.67%  |
| Broadcom              | 1         | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 33.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 16.67%  |
| Intel Ethernet Connection I217-LM                                 | 1         | 8.33%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 8.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 8.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 8.33%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 8.33%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 61.54%  |
| Ethernet | 10        | 38.46%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 13        | 61.9%   |
| Ethernet | 8         | 38.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 8         | 50%     |
| 1     | 7         | 43.75%  |
| 3     | 1         | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12        | 75%     |
| Yes  | 4         | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 8         | 53.33%  |
| Realtek               | 2         | 13.33%  |
| Foxconn / Hon Hai     | 2         | 13.33%  |
| Realtek Semiconductor | 1         | 6.67%   |
| Lite-On Technology    | 1         | 6.67%   |
| ASUSTek Computer      | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Bluetooth Device                     | 5         | 33.33%  |
| Realtek Bluetooth Radio                    | 2         | 13.33%  |
| Intel Wireless-AC 9260 Bluetooth Adapter   | 2         | 13.33%  |
| Foxconn / Hon Hai Bluetooth Device         | 2         | 13.33%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter    | 1         | 6.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 6.67%   |
| Intel Bluetooth wireless interface         | 1         | 6.67%   |
| ASUS BT-253 Bluetooth Adapter              | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 61.9%   |
| AMD                   | 3         | 14.29%  |
| Nvidia                | 2         | 9.52%   |
| Realtek Semiconductor | 1         | 4.76%   |
| Micronas              | 1         | 4.76%   |
| Conexant Systems      | 1         | 4.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 4         | 16%     |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 3         | 12%     |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 8%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 8%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 8%      |
| Realtek Semiconductor USB Audio                                     | 1         | 4%      |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 4%      |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 4%      |
| Micronas BLUE USB Audio 2.0                                         | 1         | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 4%      |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 4%      |
| Intel Comet Lake PCH cAVS                                           | 1         | 4%      |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 4%      |
| Intel Cannon Lake PCH cAVS                                          | 1         | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 4%      |
| Conexant Systems HP Dock Audio                                      | 1         | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 4         | 28.57%  |
| Samsung Electronics | 4         | 28.57%  |
| Micron Technology   | 3         | 21.43%  |
| Unknown             | 1         | 7.14%   |
| Crucial             | 1         | 7.14%   |
| A-DATA Technology   | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM 1066MT/s                       | 1         | 7.14%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 7.14%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 1         | 7.14%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 7.14%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s    | 1         | 7.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 1         | 7.14%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 1         | 7.14%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s  | 1         | 7.14%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 7.14%   |
| Micron RAM Module 16GB SODIMM DDR4 2400MT/s                  | 1         | 7.14%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 1         | 7.14%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s        | 1         | 7.14%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2667MT/s   | 1         | 7.14%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4096MB SODIMM DDR4 2400MT/s      | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 71.43%  |
| LPDDR4  | 1         | 7.14%   |
| LPDDR3  | 1         | 7.14%   |
| DDR3    | 1         | 7.14%   |
| Unknown | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 78.57%  |
| Row Of Chips | 3         | 21.43%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 50%     |
| 4096  | 5         | 35.71%  |
| 16384 | 2         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 8         | 57.14%  |
| 2400  | 2         | 14.29%  |
| 3200  | 1         | 7.14%   |
| 2133  | 1         | 7.14%   |
| 1867  | 1         | 7.14%   |
| 1066  | 1         | 7.14%   |

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
| IMC Networks                  | 4         | 26.67%  |
| Chicony Electronics           | 4         | 26.67%  |
| Microdia                      | 3         | 20%     |
| Sunplus Innovation Technology | 1         | 6.67%   |
| Quanta                        | 1         | 6.67%   |
| Lite-On Technology            | 1         | 6.67%   |
| Acer                          | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD        | 3         | 18.75%  |
| IMC Networks Integrated Camera       | 2         | 12.5%   |
| Sunplus Dell E5570 integrated webcam | 1         | 6.25%   |
| Quanta VGA WebCam                    | 1         | 6.25%   |
| Lite-On HP HD Camera                 | 1         | 6.25%   |
| IMC Networks ov9734_azurewave_camera | 1         | 6.25%   |
| IMC Networks HD Camera               | 1         | 6.25%   |
| Chicony VGA Webcam                   | 1         | 6.25%   |
| Chicony USB2.0 2M WebCam             | 1         | 6.25%   |
| Chicony USB 5M WebCam                | 1         | 6.25%   |
| Chicony Integrated Camera            | 1         | 6.25%   |
| Chicony CNF7246                      | 1         | 6.25%   |
| Acer Integrated Camera               | 1         | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 33.33%  |
| Shenzhen Goodix Technology | 2         | 33.33%  |
| Synaptics                  | 1         | 16.67%  |
| LighTuning Technology      | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 2         | 33.33%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI                   | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 16.67%  |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 16.67%  |

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
| 0     | 10        | 62.5%   |
| 1     | 6         | 37.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 6         | 100%    |

