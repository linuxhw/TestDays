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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Framework | Laptop                      | [95576917c8](https://linux-hardware.org/?probe=95576917c8) | Sep 29, 2021 |
| Notebook  | N2x0WU                      | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Lenovo    | IdeaPad C340-14API 81N6     | [82e0f76133](https://linux-hardware.org/?probe=82e0f76133) | Sep 25, 2021 |
| Lenovo    | ThinkPad E480 20KNS0MC00    | [ba847bc0c4](https://linux-hardware.org/?probe=ba847bc0c4) | Sep 23, 2021 |
| Apple     | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| HP        | G42                         | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
| HP        | ZBook 15u G5                | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| Dell      | XPS 17 9700                 | [ebac1c499f](https://linux-hardware.org/?probe=ebac1c499f) | Sep 15, 2021 |
| ASUSTek   | G71V                        | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 8... | [2b21ef140a](https://linux-hardware.org/?probe=2b21ef140a) | Sep 05, 2021 |
| Lenovo    | ThinkPad P51s 20HBCTO1WW    | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
| Dell      | Latitude E5470              | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
| Dell      | XPS 15 9550                 | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer      | Aspire A315-42              | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer      | Aspire ES1-572              | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell      | XPS 15 9570                 | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell      | XPS 13 9380                 | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo    | IdeaPad 530S-14IKB 81EU     | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| Notebook  | P377SM-A                    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI    | KLVL-WXX9                   | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| HUAWEI    | KLVL-WXX9                   | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Notebook  | P377SM-A                    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook  | P377SM-A                    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Lenovo    | ThinkPad W541 20EF000UMN    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HUAWEI    | BOHK-WAX9X                  | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI    | BOHK-WAX9X                  | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI    | BOHK-WAX9X                  | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                              | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| 5.14.0-0.rc5.42.fc35.x86_64                          | 5         | 20.83%  |
| 5.14.0-60.fc35.x86_64                                | 3         | 12.5%   |
| 5.14.7-300.fc35.x86_64                               | 2         | 8.33%   |
| 5.14.3-300.fc35.x86_64                               | 2         | 8.33%   |
| 5.14.6-300.fc35.x86_64                               | 1         | 4.17%   |
| 5.14.5-300.fc35.x86_64                               | 1         | 4.17%   |
| 5.14.1-300.fc35.x86_64                               | 1         | 4.17%   |
| 5.14.0-0.rc6.46.fc35.x86_64                          | 1         | 4.17%   |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 4.17%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 4.17%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 4.17%   |
| 5.13.4-200.fc34.x86_64                               | 1         | 4.17%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 4.17%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 4.17%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 4.17%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 11        | 47.83%  |
| 5.14.7  | 2         | 8.7%    |
| 5.14.3  | 2         | 8.7%    |
| 5.12.0  | 2         | 8.7%    |
| 5.14.6  | 1         | 4.35%   |
| 5.14.5  | 1         | 4.35%   |
| 5.14.1  | 1         | 4.35%   |
| 5.13.4  | 1         | 4.35%   |
| 5.13.0  | 1         | 4.35%   |
| 5.12.8  | 1         | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 18        | 78.26%  |
| 5.12    | 3         | 13.04%  |
| 5.13    | 2         | 8.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 22        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 20        | 86.96%  |
| MATE  | 1         | 4.35%   |
| KDE5  | 1         | 4.35%   |
| KDE   | 1         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 18        | 81.82%  |
| X11     | 4         | 18.18%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 14        | 63.64%  |
| Unknown | 6         | 27.27%  |
| SDDM    | 1         | 4.55%   |
| LightDM | 1         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 14        | 60.87%  |
| sv_SE | 1         | 4.35%   |
| ru_RU | 1         | 4.35%   |
| pt_BR | 1         | 4.35%   |
| pl_PL | 1         | 4.35%   |
| nl_NL | 1         | 4.35%   |
| ga_IE | 1         | 4.35%   |
| es_ES | 1         | 4.35%   |
| en_IL | 1         | 4.35%   |
| en_CA | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 19        | 86.36%  |
| BIOS | 3         | 13.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 11        | 47.83%  |
| Ext4  | 10        | 43.48%  |
| Xfs   | 2         | 8.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 15        | 68.18%  |
| Unknown | 6         | 27.27%  |
| MBR     | 1         | 4.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 65.22%  |
| Yes       | 8         | 34.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 86.96%  |
| Yes       | 3         | 13.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 6         | 27.27%  |
| Dell             | 5         | 22.73%  |
| Notebook         | 2         | 9.09%   |
| HUAWEI           | 2         | 9.09%   |
| Hewlett-Packard  | 2         | 9.09%   |
| Acer             | 2         | 9.09%   |
| Framework        | 1         | 4.55%   |
| ASUSTek Computer | 1         | 4.55%   |
| Apple            | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Notebook P377SM-A                          | 1         | 4.55%   |
| Notebook N2x0WU                            | 1         | 4.55%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 4.55%   |
| Lenovo ThinkPad W541 20EF000UMN            | 1         | 4.55%   |
| Lenovo ThinkPad P51s 20HBCTO1WW            | 1         | 4.55%   |
| Lenovo ThinkPad E480 20KNS0MC00            | 1         | 4.55%   |
| Lenovo IdeaPad C340-14API 81N6             | 1         | 4.55%   |
| Lenovo IdeaPad 530S-14IKB 81EU             | 1         | 4.55%   |
| HUAWEI KLVL-WXX9                           | 1         | 4.55%   |
| HUAWEI BOHK-WAX9X                          | 1         | 4.55%   |
| HP ZBook 15u G5                            | 1         | 4.55%   |
| HP G42                                     | 1         | 4.55%   |
| Framework Laptop                           | 1         | 4.55%   |
| Dell XPS 17 9700                           | 1         | 4.55%   |
| Dell XPS 15 9570                           | 1         | 4.55%   |
| Dell XPS 15 9550                           | 1         | 4.55%   |
| Dell XPS 13 9380                           | 1         | 4.55%   |
| Dell Latitude E5470                        | 1         | 4.55%   |
| ASUS G71V                                  | 1         | 4.55%   |
| Apple MacBook6,1                           | 1         | 4.55%   |
| Acer Aspire ES1-572                        | 1         | 4.55%   |
| Acer Aspire A315-42                        | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 4         | 18.18%  |
| Dell XPS          | 4         | 18.18%  |
| Lenovo IdeaPad    | 2         | 9.09%   |
| Acer Aspire       | 2         | 9.09%   |
| Notebook P377SM-A | 1         | 4.55%   |
| Notebook N2x0WU   | 1         | 4.55%   |
| HUAWEI KLVL-WXX9  | 1         | 4.55%   |
| HUAWEI BOHK-WAX9X | 1         | 4.55%   |
| HP ZBook          | 1         | 4.55%   |
| HP G42            | 1         | 4.55%   |
| Framework Laptop  | 1         | 4.55%   |
| Dell Latitude     | 1         | 4.55%   |
| ASUS G71V         | 1         | 4.55%   |
| Apple MacBook6    | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 36.36%  |
| 2021 | 5         | 22.73%  |
| 2019 | 4         | 18.18%  |
| 2018 | 1         | 4.55%   |
| 2017 | 1         | 4.55%   |
| 2015 | 1         | 4.55%   |
| 2011 | 1         | 4.55%   |
| 2008 | 1         | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 22        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 15        | 68.18%  |
| Enabled  | 7         | 31.82%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 36.36%  |
| 32.01-64.0 | 5         | 22.73%  |
| 16.01-24.0 | 4         | 18.18%  |
| 8.01-16.0  | 3         | 13.64%  |
| 3.01-4.0   | 2         | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 8         | 34.78%  |
| 3.01-4.0 | 7         | 30.43%  |
| 1.01-2.0 | 5         | 21.74%  |
| 4.01-8.0 | 3         | 13.04%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 72.73%  |
| 2      | 4         | 18.18%  |
| 5      | 1         | 4.55%   |
| 3      | 1         | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 86.36%  |
| Yes       | 3         | 13.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 68.18%  |
| No        | 7         | 31.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 90.91%  |
| No        | 2         | 9.09%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 6         | 27.27%  |
| Canada      | 2         | 9.09%   |
| Brazil      | 2         | 9.09%   |
| Turkey      | 1         | 4.55%   |
| Sweden      | 1         | 4.55%   |
| Spain       | 1         | 4.55%   |
| Poland      | 1         | 4.55%   |
| Norway      | 1         | 4.55%   |
| Netherlands | 1         | 4.55%   |
| Japan       | 1         | 4.55%   |
| Israel      | 1         | 4.55%   |
| Ireland     | 1         | 4.55%   |
| India       | 1         | 4.55%   |
| Germany     | 1         | 4.55%   |
| Belarus     | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Seattle        | 2         | 8.33%   |
| Yakima         | 1         | 4.17%   |
| Wroclaw        | 1         | 4.17%   |
| Whittier       | 1         | 4.17%   |
| Royse          | 1         | 4.17%   |
| Raesfeld       | 1         | 4.17%   |
| Porto Ferreira | 1         | 4.17%   |
| Osaka          | 1         | 4.17%   |
| Montreal       | 1         | 4.17%   |
| Minsk          | 1         | 4.17%   |
| Miami          | 1         | 4.17%   |
| Madrid         | 1         | 4.17%   |
| Laurel         | 1         | 4.17%   |
| Istanbul       | 1         | 4.17%   |
| Handen         | 1         | 4.17%   |
| Haifa          | 1         | 4.17%   |
| Fortaleza      | 1         | 4.17%   |
| Dublin         | 1         | 4.17%   |
| Concord        | 1         | 4.17%   |
| Bolszewo       | 1         | 4.17%   |
| Bengaluru      | 1         | 4.17%   |
| Atlanta        | 1         | 4.17%   |
| Amsterdam      | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 20.69%  |
| Samsung Electronics | 6         | 13     | 20.69%  |
| Unknown             | 3         | 3      | 10.34%  |
| Sandisk             | 3         | 4      | 10.34%  |
| Toshiba             | 2         | 2      | 6.9%    |
| SK Hynix            | 2         | 2      | 6.9%    |
| USB3.1              | 1         | 1      | 3.45%   |
| Seagate             | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| LITEON              | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| ASMT                | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD5000LPLX-08ZNTT0 500GB         | 2         | 6.67%   |
| Sandisk NVMe SSD Drive 256GB         | 2         | 6.67%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 3.33%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 3.33%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 1         | 3.33%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB | 1         | 3.33%   |
| USB3.1 NVME&SATA 1TB                 | 1         | 3.33%   |
| Unknown USB DISK 3.2 1TB             | 1         | 3.33%   |
| Unknown SSD0240S00 240GB             | 1         | 3.33%   |
| Unknown SD256  249GB                 | 1         | 3.33%   |
| Toshiba KXG60ZNV256G NVMe 256GB      | 1         | 3.33%   |
| Toshiba KXG50ZNV512G NVMe 512GB      | 1         | 3.33%   |
| SK Hynix NVMe SSD Drive 512GB        | 1         | 3.33%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 3.33%   |
| Seagate ST9500325AS 500GB            | 1         | 3.33%   |
| SanDisk SDSSDH3512G 512GB            | 1         | 3.33%   |
| Samsung SSD 850 PRO 1TB              | 1         | 3.33%   |
| Samsung SSD 850 EVO mSATA 1TB        | 1         | 3.33%   |
| Samsung PM9A1 NVMe 512GB             | 1         | 3.33%   |
| Samsung NVMe SSD Drive 2TB           | 1         | 3.33%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 1         | 3.33%   |
| Samsung MZVLB512HAJQ-000H1 512GB     | 1         | 3.33%   |
| Samsung MZVLB256HAHQ-000L7 256GB     | 1         | 3.33%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 3.33%   |
| LITEON CX2-8B256-Q11 NVMe 256GB      | 1         | 3.33%   |
| Kingston SA400S37480G 480GB SSD      | 1         | 3.33%   |
| Hitachi HTS545025B9SA02 250GB        | 1         | 3.33%   |
| ASMT ASM105x 400GB SSD               | 1         | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Seagate | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 14.29%  |
| Unknown             | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 2      | 14.29%  |
| Samsung Electronics | 1         | 8      | 14.29%  |
| Micron Technology   | 1         | 1      | 14.29%  |
| Kingston            | 1         | 1      | 14.29%  |
| ASMT                | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 13        | 15     | 50%     |
| SSD     | 6         | 15     | 23.08%  |
| HDD     | 5         | 5      | 19.23%  |
| MMC     | 1         | 1      | 3.85%   |
| Unknown | 1         | 2      | 3.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 13        | 15     | 50%     |
| SATA | 10        | 19     | 38.46%  |
| SAS  | 2         | 3      | 7.69%   |
| MMC  | 1         | 1      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 9      | 81.82%  |
| 0.51-1.0   | 2         | 11     | 18.18%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 6         | 26.09%  |
| 1-20           | 6         | 26.09%  |
| 101-250        | 5         | 21.74%  |
| 501-1000       | 2         | 8.7%    |
| More than 3000 | 1         | 4.35%   |
| 21-50          | 1         | 4.35%   |
| 51-100         | 1         | 4.35%   |
| Unknown        | 1         | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 10        | 45.45%  |
| 21-50   | 6         | 27.27%  |
| 101-250 | 3         | 13.64%  |
| 251-500 | 1         | 4.55%   |
| 51-100  | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545025B9SA02 250GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Works    | 15        | 17     | 60%     |
| Detected | 9         | 20     | 36%     |
| Malfunc  | 1         | 1      | 4%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 12        | 44.44%  |
| Samsung Electronics          | 5         | 18.52%  |
| Sandisk                      | 3         | 11.11%  |
| Toshiba America Info Systems | 2         | 7.41%   |
| SK Hynix                     | 2         | 7.41%   |
| Nvidia                       | 1         | 3.7%    |
| Lite-On Technology           | 1         | 3.7%    |
| AMD                          | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 18.52%  |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 11.11%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 7.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 7.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 3.7%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 3.7%    |
| SK Hynix Non-Volatile memory controller                                          | 1         | 3.7%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 3.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 3.7%    |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 3.7%    |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 3.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 3.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 3.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 3.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 13        | 48.15%  |
| SATA | 13        | 48.15%  |
| RAID | 1         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 81.82%  |
| AMD    | 4         | 18.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 9.09%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 9.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 4.55%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 4.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 4.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 4.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 4.55%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 4.55%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 4.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 4.55%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 4.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 4.55%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 4.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 4.55%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 4.55%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 4.55%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 1         | 4.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 4.55%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 4.55%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 11        | 50%     |
| AMD Ryzen 5      | 3         | 13.64%  |
| Intel Core i5    | 2         | 9.09%   |
| Intel Core i3    | 2         | 9.09%   |
| Intel Core 2 Duo | 2         | 9.09%   |
| Other            | 1         | 4.55%   |
| AMD Ryzen 3      | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 13        | 59.09%  |
| 2      | 6         | 27.27%  |
| 6      | 3         | 13.64%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 86.36%  |
| 1      | 3         | 13.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ea    | 4         | 18.18%  |
| 0x08108109 | 3         | 13.64%  |
| 0x806ec    | 2         | 9.09%   |
| 0x506e3    | 2         | 9.09%   |
| 0x306c3    | 2         | 9.09%   |
| 0xa0652    | 1         | 4.55%   |
| 0x906ea    | 1         | 4.55%   |
| 0x806e9    | 1         | 4.55%   |
| 0x806c1    | 1         | 4.55%   |
| 0x406e3    | 1         | 4.55%   |
| 0x1067a    | 1         | 4.55%   |
| 0x10676    | 1         | 4.55%   |
| 0x08600104 | 1         | 4.55%   |
| Unknown    | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 8         | 36.36%  |
| Zen+      | 3         | 13.64%  |
| Skylake   | 3         | 13.64%  |
| Penryn    | 2         | 9.09%   |
| Haswell   | 2         | 9.09%   |
| Zen 2     | 1         | 4.55%   |
| Westmere  | 1         | 4.55%   |
| TigerLake | 1         | 4.55%   |
| CometLake | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 51.72%  |
| Nvidia | 8         | 27.59%  |
| AMD    | 6         | 20.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                      | 4         | 13.79%  |
| AMD Picasso                                                 | 3         | 10.34%  |
| Intel HD Graphics 530                                       | 2         | 6.9%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                  | 1         | 3.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                  | 1         | 3.45%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                     | 1         | 3.45%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                        | 1         | 3.45%   |
| Nvidia GM107M [GeForce GTX 960M]                            | 1         | 3.45%   |
| Nvidia GK106GLM [Quadro K2100M]                             | 1         | 3.45%   |
| Nvidia G96M [GeForce 9700M GT]                              | 1         | 3.45%   |
| Nvidia C79 [GeForce 9400M]                                  | 1         | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                  | 1         | 3.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                   | 1         | 3.45%   |
| Intel Skylake GT2 [HD Graphics 520]                         | 1         | 3.45%   |
| Intel HD Graphics 620                                       | 1         | 3.45%   |
| Intel Core Processor Integrated Graphics Controller         | 1         | 3.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                        | 1         | 3.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                        | 1         | 3.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                   | 1         | 3.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller | 1         | 3.45%   |
| AMD Renoir                                                  | 1         | 3.45%   |
| AMD Lexa XT [Radeon PRO WX 3100]                            | 1         | 3.45%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]  | 1         | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 8         | 36.36%  |
| Intel + Nvidia | 5         | 22.73%  |
| 1 x AMD        | 4         | 18.18%  |
| 1 x Nvidia     | 3         | 13.64%  |
| Intel + AMD    | 2         | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 20        | 86.96%  |
| Proprietary | 3         | 13.04%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 47.83%  |
| 1.01-2.0   | 6         | 26.09%  |
| 0.01-0.5   | 3         | 13.04%  |
| 7.01-8.0   | 1         | 4.35%   |
| 3.01-4.0   | 1         | 4.35%   |
| 0.51-1.0   | 1         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 6         | 20%     |
| LG Display           | 5         | 16.67%  |
| Chimei Innolux       | 4         | 13.33%  |
| Sharp                | 3         | 10%     |
| BOE                  | 3         | 10%     |
| Dell                 | 2         | 6.67%   |
| Samsung Electronics  | 1         | 3.33%   |
| Philips              | 1         | 3.33%   |
| Hewlett-Packard      | 1         | 3.33%   |
| Goldstar             | 1         | 3.33%   |
| BenQ                 | 1         | 3.33%   |
| Apple                | 1         | 3.33%   |
| Ancor Communications | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14D7 1920x1200 366x229mm 17.0-inch           | 1         | 3.23%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch           | 1         | 3.23%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch           | 1         | 3.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch | 1         | 3.23%   |
| Philips LCD Monitor PHL0001 1920x1080 710x400mm 32.1-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD05EE 2560x1440 309x174mm 14.0-inch      | 1         | 3.23%   |
| LG Display LCD Monitor LGD056E 1920x1080 344x194mm 15.5-inch      | 1         | 3.23%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch      | 1         | 3.23%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch      | 1         | 3.23%   |
| LG Display LCD Monitor LGD02B2 1366x768 310x174mm 14.0-inch       | 1         | 3.23%   |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch        | 1         | 3.23%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch         | 1         | 3.23%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                 | 1         | 3.23%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                 | 1         | 3.23%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                 | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch  | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch   | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch  | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch  | 1         | 3.23%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch             | 1         | 3.23%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch             | 1         | 3.23%   |
| BOE LCD Monitor BOE0742 1920x1080 309x173mm 13.9-inch             | 1         | 3.23%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                 | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch    | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch    | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch    | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch    | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch    | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO1088 1920x1200 367x229mm 17.0-inch    | 1         | 3.23%   |
| Apple Color LCD APP9CC0 1280x800 261x163mm 12.1-inch              | 1         | 3.23%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch  | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 14        | 58.33%  |
| 3840x2160 (4K)    | 2         | 8.33%   |
| 1920x1200 (WUXGA) | 2         | 8.33%   |
| 1366x768 (WXGA)   | 2         | 8.33%   |
| 2560x1440 (QHD)   | 1         | 4.17%   |
| 2256x1504         | 1         | 4.17%   |
| 2160x1440         | 1         | 4.17%   |
| 1280x800 (WXGA)   | 1         | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 8         | 25.81%  |
| 14     | 5         | 16.13%  |
| 13     | 5         | 16.13%  |
| 21     | 3         | 9.68%   |
| 17     | 3         | 9.68%   |
| 27     | 2         | 6.45%   |
| 24     | 2         | 6.45%   |
| 40     | 1         | 3.23%   |
| 23     | 1         | 3.23%   |
| 12     | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 50%     |
| 501-600     | 4         | 13.33%  |
| 201-300     | 4         | 13.33%  |
| 401-500     | 3         | 10%     |
| 351-400     | 3         | 10%     |
| 801-900     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 17        | 77.27%  |
| 16/10 | 3         | 13.64%  |
| 3/2   | 2         | 9.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 30%     |
| 101-110        | 8         | 26.67%  |
| 201-250        | 4         | 13.33%  |
| 121-130        | 3         | 10%     |
| 301-350        | 2         | 6.67%   |
| 71-80          | 1         | 3.33%   |
| 61-70          | 1         | 3.33%   |
| 251-300        | 1         | 3.33%   |
| 501-1000       | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 50%     |
| 161-240       | 5         | 16.67%  |
| 101-120       | 5         | 16.67%  |
| 51-100        | 4         | 13.33%  |
| More than 240 | 1         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 16        | 69.57%  |
| 2     | 5         | 21.74%  |
| 3     | 2         | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 14        | 42.42%  |
| Intel                 | 12        | 36.36%  |
| Qualcomm Atheros      | 3         | 9.09%   |
| Broadcom              | 2         | 6.06%   |
| Sierra Wireless       | 1         | 3.03%   |
| Nvidia                | 1         | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 14.63%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 9.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 7.32%   |
| Intel Wireless 7260                                               | 3         | 7.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.88%   |
| Intel Wireless-AC 9260                                            | 2         | 4.88%   |
| Intel Wireless 8265 / 8275                                        | 2         | 4.88%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 1         | 2.44%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2.44%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.44%   |
| Intel Wireless 8260                                               | 1         | 2.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2.44%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 2.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.44%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 52.17%  |
| Realtek Semiconductor | 6         | 26.09%  |
| Qualcomm Atheros      | 3         | 13.04%  |
| Sierra Wireless       | 1         | 4.35%   |
| Broadcom              | 1         | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 3         | 13.04%  |
| Intel Wireless 7260                                        | 3         | 13.04%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 8.7%    |
| Intel Wireless-AC 9260                                     | 2         | 8.7%    |
| Intel Wireless 8265 / 8275                                 | 2         | 8.7%    |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A        | 1         | 4.35%   |
| Realtek RTL8191SEvA Wireless LAN Controller                | 1         | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 4.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 4.35%   |
| Intel Wireless 8260                                        | 1         | 4.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 4.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 4.35%   |
| Broadcom BCM43224 802.11a/b/g/n                            | 1         | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 10        | 58.82%  |
| Intel                 | 5         | 29.41%  |
| Nvidia                | 1         | 5.88%   |
| Broadcom              | 1         | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 33.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 22.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 5.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 5.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 5.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 5.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 5.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 5.56%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 5.56%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 59.46%  |
| Ethernet | 15        | 40.54%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 65.52%  |
| Ethernet | 10        | 34.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 12        | 54.55%  |
| 1     | 9         | 40.91%  |
| 3     | 1         | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 15        | 68.18%  |
| Yes  | 7         | 31.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 50%     |
| Realtek Semiconductor | 3         | 15%     |
| Realtek               | 2         | 10%     |
| Foxconn / Hon Hai     | 2         | 10%     |
| Lite-On Technology    | 1         | 5%      |
| ASUSTek Computer      | 1         | 5%      |
| Apple                 | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface       | 4         | 20%     |
| Intel Bluetooth Device                   | 4         | 20%     |
| Realtek RTL8822BE Bluetooth 4.2 Adapter  | 3         | 15%     |
| Realtek Bluetooth Radio                  | 2         | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter | 2         | 10%     |
| Foxconn / Hon Hai Bluetooth Device       | 2         | 10%     |
| Lite-On Bluetooth Device                 | 1         | 5%      |
| ASUS BT-253 Bluetooth Adapter            | 1         | 5%      |
| Apple Bluetooth Host Controller          | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 62.96%  |
| AMD                   | 4         | 14.81%  |
| Nvidia                | 3         | 11.11%  |
| Realtek Semiconductor | 1         | 3.7%    |
| Micronas              | 1         | 3.7%    |
| Conexant Systems      | 1         | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 6         | 18.75%  |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 4         | 12.5%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 3         | 9.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 6.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 6.25%   |
| Realtek Semiconductor USB Audio                                     | 1         | 3.13%   |
| Nvidia MCP79 High Definition Audio                                  | 1         | 3.13%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 3.13%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 3.13%   |
| Micronas BLUE USB Audio 2.0                                         | 1         | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 3.13%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 3.13%   |
| Intel Comet Lake PCH cAVS                                           | 1         | 3.13%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 3.13%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 1         | 3.13%   |
| Conexant Systems HP Dock Audio                                      | 1         | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 5         | 27.78%  |
| Samsung Electronics | 4         | 22.22%  |
| Micron Technology   | 4         | 22.22%  |
| Avant               | 2         | 11.11%  |
| Unknown             | 1         | 5.56%   |
| Crucial             | 1         | 5.56%   |
| A-DATA Technology   | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM 1066MT/s                         | 1         | 5.56%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 5.56%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s     | 1         | 5.56%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s      | 1         | 5.56%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 5.56%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s      | 1         | 5.56%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s | 1         | 5.56%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s       | 1         | 5.56%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s    | 1         | 5.56%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s   | 1         | 5.56%   |
| Micron RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 5.56%   |
| Micron RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 5.56%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 1         | 5.56%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s          | 1         | 5.56%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16384MB SODIMM DDR4 2667MT/s  | 1         | 5.56%   |
| Avant RAM J642GU42J7240N2 16GB SODIMM DDR4 2400MT/s            | 1         | 5.56%   |
| Avant RAM J642GU42J5213N2 16GB SODIMM DDR4 2133MT/s            | 1         | 5.56%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4096MB SODIMM DDR4 2400MT/s        | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 12        | 70.59%  |
| DDR3    | 2         | 11.76%  |
| LPDDR4  | 1         | 5.88%   |
| LPDDR3  | 1         | 5.88%   |
| Unknown | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 82.35%  |
| Row Of Chips | 3         | 17.65%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 41.18%  |
| 4096  | 6         | 35.29%  |
| 16384 | 4         | 23.53%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 9         | 50%     |
| 2400  | 3         | 16.67%  |
| 2133  | 2         | 11.11%  |
| 3200  | 1         | 5.56%   |
| 1867  | 1         | 5.56%   |
| 1067  | 1         | 5.56%   |
| 1066  | 1         | 5.56%   |

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
| IMC Networks                  | 5         | 23.81%  |
| Chicony Electronics           | 4         | 19.05%  |
| Microdia                      | 3         | 14.29%  |
| Acer                          | 3         | 14.29%  |
| Suyin                         | 1         | 4.76%   |
| Sunplus Innovation Technology | 1         | 4.76%   |
| Realtek Semiconductor         | 1         | 4.76%   |
| Quanta                        | 1         | 4.76%   |
| Lite-On Technology            | 1         | 4.76%   |
| Apple                         | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD        | 3         | 13.64%  |
| IMC Networks Integrated Camera       | 3         | 13.64%  |
| IMC Networks ov9734_azurewave_camera | 2         | 9.09%   |
| Acer Integrated Camera               | 2         | 9.09%   |
| Suyin HP Webcam-101                  | 1         | 4.55%   |
| Sunplus Integrated_Webcam_HD         | 1         | 4.55%   |
| Realtek Laptop Camera                | 1         | 4.55%   |
| Quanta VGA WebCam                    | 1         | 4.55%   |
| Lite-On HP HD Camera                 | 1         | 4.55%   |
| Chicony VGA Webcam                   | 1         | 4.55%   |
| Chicony USB2.0 2M WebCam             | 1         | 4.55%   |
| Chicony USB 5M WebCam                | 1         | 4.55%   |
| Chicony Integrated Camera            | 1         | 4.55%   |
| Chicony CNF7246                      | 1         | 4.55%   |
| Apple Built-in iSight                | 1         | 4.55%   |
| Acer BisonCam, NB Pro                | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 37.5%   |
| Validity Sensors           | 2         | 25%     |
| Shenzhen Goodix Technology | 2         | 25%     |
| LighTuning Technology      | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 2         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI                   | 1         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 12.5%   |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 12.5%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 12.5%   |
| Unknown                                           | 1         | 12.5%   |

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
| 0     | 14        | 63.64%  |
| 1     | 8         | 36.36%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 8         | 100%    |

