Fedora 35 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 35 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_35/Desktop/README.md) and [notebooks](/Dist/Fedora_35/Notebook/README.md).

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

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell      | 0KC9NP A01                  | Desktop     | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [f48bc9ac9d](https://linux-hardware.org/?probe=f48bc9ac9d) | Aug 07, 2021 |
| Notebook  | P377SM-A                    | Notebook    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI    | KLVL-WXX9                   | Notebook    | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| ASUSTek   | Maximus V FORMULA           | Desktop     | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [7dcd16d3fd](https://linux-hardware.org/?probe=7dcd16d3fd) | Jul 14, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [eedd464065](https://linux-hardware.org/?probe=eedd464065) | Jul 14, 2021 |
| HUAWEI    | KLVL-WXX9                   | Notebook    | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [8d1e68aad0](https://linux-hardware.org/?probe=8d1e68aad0) | Jul 07, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [852a8a103d](https://linux-hardware.org/?probe=852a8a103d) | Jul 04, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [3a0ca9b90c](https://linux-hardware.org/?probe=3a0ca9b90c) | Jul 01, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [3ed1ee1f81](https://linux-hardware.org/?probe=3ed1ee1f81) | Jun 25, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [f611d9ec88](https://linux-hardware.org/?probe=f611d9ec88) | Jun 23, 2021 |
| ASUSTek   | Maximus V FORMULA           | Desktop     | [95ba18d5da](https://linux-hardware.org/?probe=95ba18d5da) | Jun 23, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [511e8019e0](https://linux-hardware.org/?probe=511e8019e0) | Jun 19, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte  | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek   | Maximus V FORMULA           | Desktop     | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| Notebook  | P377SM-A                    | Notebook    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook  | P377SM-A                    | Notebook    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Microsoft | Surface Pro                 | Tablet      | [7a294509de](https://linux-hardware.org/?probe=7a294509de) | May 15, 2021 |
| Microsoft | Surface Pro                 | Tablet      | [4238374bcc](https://linux-hardware.org/?probe=4238374bcc) | Apr 26, 2021 |
| HP        | Pavilion x360 Convertibl... | Convertible | [89892d4957](https://linux-hardware.org/?probe=89892d4957) | Apr 18, 2021 |
| HP        | Pavilion x360 Convertibl... | Convertible | [97c124c8a3](https://linux-hardware.org/?probe=97c124c8a3) | Apr 18, 2021 |
| ECS       | MCP61M-M3                   | Desktop     | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek   | PRIME X570-PRO              | Desktop     | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |
| Lenovo    | ThinkPad W541 20EF000UMN    | Notebook    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HP        | Pavilion x360 Convertibl... | Convertible | [c0901f4607](https://linux-hardware.org/?probe=c0901f4607) | Mar 29, 2021 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                              | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| 5.12.0-0.rc7.189.fc35.x86_64                         | 2         | 10.53%  |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 5.26%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 5.26%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 5.26%   |
| 5.13.0-58.fc35.x86_64                                | 1         | 5.26%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64  | 1         | 5.26%   |
| 5.13.0-0.rc6.45.fc35.x86_64                          | 1         | 5.26%   |
| 5.13.0-0.rc2.20210521git79a106fc6585.22.fc35.x86_64  | 1         | 5.26%   |
| 5.13.0-0.rc2.19.fc35.x86_64                          | 1         | 5.26%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 5.26%   |
| 5.13.0-0.rc1.13.fc35.x86_64                          | 1         | 5.26%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 5.26%   |
| 5.12.0-0.rc8.20210423git7af08140979a.193.fc35.x86_64 | 1         | 5.26%   |
| 5.12.0-0.rc8.191.fc35.x86_64                         | 1         | 5.26%   |
| 5.12.0-0.rc7.20210416git7e25f40eab52.191.fc35.x86_64 | 1         | 5.26%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 5.26%   |
| 5.12.0-0.rc4.20210326gitdb24726bfefa.178.fc35.x86_64 | 1         | 5.26%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 5.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.12.0  | 7         | 50%     |
| 5.13.0  | 4         | 28.57%  |
| 5.14.0  | 2         | 14.29%  |
| 5.12.8  | 1         | 7.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.12    | 8         | 57.14%  |
| 5.13    | 4         | 28.57%  |
| 5.14    | 2         | 14.29%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 12        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 7         | 53.85%  |
| KDE     | 4         | 30.77%  |
| MATE    | 1         | 7.69%   |
| Unknown | 1         | 7.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 7         | 58.33%  |
| X11     | 4         | 33.33%  |
| Tty     | 1         | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7         | 58.33%  |
| GDM     | 4         | 33.33%  |
| TDM     | 1         | 8.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 6         | 46.15%  |
| sv_SE | 1         | 7.69%   |
| ru_RU | 1         | 7.69%   |
| pl_PL | 1         | 7.69%   |
| es_ES | 1         | 7.69%   |
| es_CL | 1         | 7.69%   |
| en_GB | 1         | 7.69%   |
| en_CA | 1         | 7.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 10        | 83.33%  |
| BIOS | 2         | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 8         | 61.54%  |
| Ext4  | 3         | 23.08%  |
| Xfs   | 2         | 15.38%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 6         | 46.15%  |
| Unknown | 6         | 46.15%  |
| MBR     | 1         | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 11        | 78.57%  |
| Yes       | 3         | 21.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 12        | 85.71%  |
| Yes       | 2         | 14.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| HUAWEI              | 2         | 16.67%  |
| Hewlett-Packard     | 2         | 16.67%  |
| ASUSTek Computer    | 2         | 16.67%  |
| Notebook            | 1         | 8.33%   |
| Microsoft           | 1         | 8.33%   |
| Lenovo              | 1         | 8.33%   |
| Gigabyte Technology | 1         | 8.33%   |
| ECS                 | 1         | 8.33%   |
| Dell                | 1         | 8.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Notebook P377SM-A                      | 1         | 8.33%   |
| Microsoft Surface Pro                  | 1         | 8.33%   |
| Lenovo ThinkPad W541 20EF000UMN        | 1         | 8.33%   |
| HUAWEI KLVL-WXX9                       | 1         | 8.33%   |
| HUAWEI BOHK-WAX9X                      | 1         | 8.33%   |
| HP Pavilion x360 Convertible 15-cr0xxx | 1         | 8.33%   |
| HP Pavilion x360 Convertible 14-dh0xxx | 1         | 8.33%   |
| Gigabyte F2A88XN-WIFI                  | 1         | 8.33%   |
| ECS MCP61M-M3                          | 1         | 8.33%   |
| Dell OptiPlex 9020                     | 1         | 8.33%   |
| ASUS PRIME X570-PRO                    | 1         | 8.33%   |
| ASUS Maximus V FORMULA                 | 1         | 8.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| HP Pavilion           | 2         | 16.67%  |
| Notebook P377SM-A     | 1         | 8.33%   |
| Microsoft Surface     | 1         | 8.33%   |
| Lenovo ThinkPad       | 1         | 8.33%   |
| HUAWEI KLVL-WXX9      | 1         | 8.33%   |
| HUAWEI BOHK-WAX9X     | 1         | 8.33%   |
| Gigabyte F2A88XN-WIFI | 1         | 8.33%   |
| ECS MCP61M-M3         | 1         | 8.33%   |
| Dell OptiPlex         | 1         | 8.33%   |
| ASUS PRIME            | 1         | 8.33%   |
| ASUS Maximus          | 1         | 8.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 4         | 33.33%  |
| 2019 | 3         | 25%     |
| 2015 | 3         | 25%     |
| 2013 | 1         | 8.33%   |
| 2010 | 1         | 8.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 5         | 41.67%  |
| Notebook    | 4         | 33.33%  |
| Convertible | 2         | 16.67%  |
| Tablet      | 1         | 8.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8         | 61.54%  |
| Enabled  | 5         | 38.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 12        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 5         | 38.46%  |
| 8.01-16.0  | 4         | 30.77%  |
| 32.01-64.0 | 2         | 15.38%  |
| 3.01-4.0   | 2         | 15.38%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 3.01-4.0 | 5         | 31.25%  |
| 2.01-3.0 | 4         | 25%     |
| 1.01-2.0 | 3         | 18.75%  |
| 4.01-8.0 | 2         | 12.5%   |
| 0.51-1.0 | 1         | 6.25%   |
| 0.01-0.5 | 1         | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 9         | 75%     |
| 5      | 1         | 8.33%   |
| 4      | 1         | 8.33%   |
| 2      | 1         | 8.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 9         | 75%     |
| Yes       | 3         | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8         | 66.67%  |
| No        | 4         | 33.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 83.33%  |
| No        | 2         | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8         | 66.67%  |
| No        | 4         | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 2         | 16.67%  |
| Turkey      | 1         | 8.33%   |
| Switzerland | 1         | 8.33%   |
| Sweden      | 1         | 8.33%   |
| Spain       | 1         | 8.33%   |
| Russia      | 1         | 8.33%   |
| Poland      | 1         | 8.33%   |
| Netherlands | 1         | 8.33%   |
| Hong Kong   | 1         | 8.33%   |
| Chile       | 1         | 8.33%   |
| Canada      | 1         | 8.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Yakima        | 2         | 14.29%  |
| Zurich        | 1         | 7.14%   |
| Wroclaw       | 1         | 7.14%   |
| Wateringen    | 1         | 7.14%   |
| Vancouver     | 1         | 7.14%   |
| St Petersburg | 1         | 7.14%   |
| Seattle       | 1         | 7.14%   |
| Madrid        | 1         | 7.14%   |
| La Florida    | 1         | 7.14%   |
| Kwu Tung      | 1         | 7.14%   |
| Istanbul      | 1         | 7.14%   |
| Handen        | 1         | 7.14%   |
| Bolszewo      | 1         | 7.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 17     | 29.41%  |
| WDC                 | 4         | 7      | 23.53%  |
| Seagate             | 2         | 7      | 11.76%  |
| Sandisk             | 2         | 3      | 11.76%  |
| Unknown             | 1         | 1      | 5.88%   |
| Toshiba             | 1         | 1      | 5.88%   |
| SK Hynix            | 1         | 2      | 5.88%   |
| LITEON              | 1         | 1      | 5.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 5%      |
| WDC WD30EZRX-00MMMB0 3TB                | 1         | 5%      |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 5%      |
| WDC PC SN730 SDBPNTY-256G-1027 256GB    | 1         | 5%      |
| Unknown SSD0240S00 240GB                | 1         | 5%      |
| Toshiba MG05ACA800E 8TB                 | 1         | 5%      |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 5%      |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 5%      |
| Seagate ST3500630AS 500GB               | 1         | 5%      |
| Seagate ST3000DM001-1CH166 3TB          | 1         | 5%      |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 5%      |
| SanDisk SDSSDH3512G 512GB               | 1         | 5%      |
| Sandisk NVMe SSD Drive 256GB            | 1         | 5%      |
| Samsung SSD 860 EVO 250GB               | 1         | 5%      |
| Samsung SSD 850 PRO 1TB                 | 1         | 5%      |
| Samsung SSD 850 EVO mSATA 1TB           | 1         | 5%      |
| Samsung SSD 840 EVO 250GB               | 1         | 5%      |
| Samsung NVMe SSD Drive 500GB            | 1         | 5%      |
| Samsung KUS020203M-B000 128GB           | 1         | 5%      |
| LITEON CV8-8E128-HP 128GB SSD           | 1         | 5%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 7      | 50%     |
| WDC     | 1         | 3      | 25%     |
| Toshiba | 1         | 1      | 25%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 14     | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Unknown             | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 2      | 14.29%  |
| LITEON              | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 6         | 19     | 42.86%  |
| NVMe | 5         | 9      | 35.71%  |
| HDD  | 3         | 11     | 21.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 8         | 30     | 61.54%  |
| NVMe | 5         | 9      | 38.46%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5         | 12     | 55.56%  |
| 2.01-3.0   | 1         | 6      | 11.11%  |
| 1.01-2.0   | 1         | 1      | 11.11%  |
| 4.01-10.0  | 1         | 1      | 11.11%  |
| 0.51-1.0   | 1         | 10     | 11.11%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 5         | 35.71%  |
| 101-250    | 3         | 21.43%  |
| 1-20       | 2         | 14.29%  |
| 21-50      | 1         | 7.14%   |
| 1001-2000  | 1         | 7.14%   |
| 501-1000   | 1         | 7.14%   |
| 51-100     | 1         | 7.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 5         | 38.46%  |
| 21-50    | 3         | 23.08%  |
| 251-500  | 2         | 15.38%  |
| 101-250  | 1         | 7.69%   |
| 501-1000 | 1         | 7.69%   |
| 51-100   | 1         | 7.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD30EZRX-00MMMB0 3TB      | 1         | 1      | 33.33%  |
| Seagate ST3500630AS 500GB     | 1         | 1      | 33.33%  |
| LITEON CV8-8E128-HP 128GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| LITEON  | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 2      | 50%     |

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
| Detected | 7         | 24     | 43.75%  |
| Works    | 7         | 12     | 43.75%  |
| Malfunc  | 2         | 3      | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 6         | 40%     |
| Sandisk             | 2         | 13.33%  |
| Samsung Electronics | 2         | 13.33%  |
| AMD                 | 2         | 13.33%  |
| SK Hynix            | 1         | 6.67%   |
| Nvidia              | 1         | 6.67%   |
| ASMedia Technology  | 1         | 6.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 12.5%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 12.5%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 12.5%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 12.5%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 6.25%   |
| Samsung Electronics Non-Volatile memory controller                             | 1         | 6.25%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 6.25%   |
| Nvidia MCP61 IDE                                                               | 1         | 6.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 6.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 6.25%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 6.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6         | 42.86%  |
| NVMe | 5         | 35.71%  |
| RAID | 2         | 14.29%  |
| IDE  | 1         | 7.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 7         | 58.33%  |
| AMD    | 5         | 41.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 8.33%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 8.33%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1         | 8.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 8.33%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 8.33%   |
| Intel Core i5-4590S CPU @ 3.00GHz               | 1         | 8.33%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 8.33%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 8.33%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 8.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 8.33%   |
| AMD Athlon II X2 250 Processor                  | 1         | 8.33%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1         | 8.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 3         | 25%     |
| Intel Core i5    | 3         | 25%     |
| AMD Ryzen 5      | 3         | 25%     |
| Intel Core i3    | 1         | 8.33%   |
| AMD Athlon II X2 | 1         | 8.33%   |
| AMD A10          | 1         | 8.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 6         | 50%     |
| 2      | 4         | 33.33%  |
| 6      | 2         | 16.67%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 12        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 10        | 83.33%  |
| 1      | 2         | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 12        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 3         | 25%     |
| 0x806ec    | 1         | 8.33%   |
| 0x806ea    | 1         | 8.33%   |
| 0x806e9    | 1         | 8.33%   |
| 0x306a9    | 1         | 8.33%   |
| 0x08701021 | 1         | 8.33%   |
| 0x08600104 | 1         | 8.33%   |
| 0x08108109 | 1         | 8.33%   |
| 0x06003106 | 1         | 8.33%   |
| 0x010000b6 | 1         | 8.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 3         | 25%     |
| Haswell     | 3         | 25%     |
| Zen 2       | 2         | 16.67%  |
| Zen+        | 1         | 8.33%   |
| Steamroller | 1         | 8.33%   |
| K10         | 1         | 8.33%   |
| IvyBridge   | 1         | 8.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 6         | 42.86%  |
| AMD    | 5         | 35.71%  |
| Nvidia | 3         | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1         | 7.14%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 1         | 7.14%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1         | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 7.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 7.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 7.14%   |
| Intel UHD Graphics 620                                                      | 1         | 7.14%   |
| Intel HD Graphics 620                                                       | 1         | 7.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 7.14%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1         | 7.14%   |
| AMD Renoir                                                                  | 1         | 7.14%   |
| AMD Picasso                                                                 | 1         | 7.14%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1         | 7.14%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1         | 7.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 5         | 41.67%  |
| 1 x Intel      | 4         | 33.33%  |
| 1 x Nvidia     | 2         | 16.67%  |
| Intel + Nvidia | 1         | 8.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 11        | 84.62%  |
| Proprietary | 2         | 15.38%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 42.86%  |
| 1.01-2.0   | 2         | 14.29%  |
| 0.51-1.0   | 2         | 14.29%  |
| 0.01-0.5   | 2         | 14.29%  |
| 7.01-8.0   | 1         | 7.14%   |
| 3.01-4.0   | 1         | 7.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 3         | 27.27%  |
| BOE                  | 2         | 18.18%  |
| Hewlett-Packard      | 1         | 9.09%   |
| Dell                 | 1         | 9.09%   |
| Chimei Innolux       | 1         | 9.09%   |
| AU Optronics         | 1         | 9.09%   |
| AOC                  | 1         | 9.09%   |
| Ancor Communications | 1         | 9.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 8.33%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch           | 1         | 8.33%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch           | 1         | 8.33%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch          | 1         | 8.33%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                      | 1         | 8.33%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                      | 1         | 8.33%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch       | 1         | 8.33%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 8.33%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                  | 1         | 8.33%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch         | 1         | 8.33%   |
| AOC LE22H037 AOC2207 1920x1080 480x270mm 21.7-inch                     | 1         | 8.33%   |
| Ancor Communications ASUS VW266H ACI26A4 1920x1200 550x340mm 25.5-inch | 1         | 8.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 6         | 60%     |
| 2736x1824         | 1         | 10%     |
| 2560x1440 (QHD)   | 1         | 10%     |
| 2160x1440         | 1         | 10%     |
| 1920x1200 (WUXGA) | 1         | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 3         | 27.27%  |
| 21     | 2         | 18.18%  |
| 14     | 2         | 18.18%  |
| 27     | 1         | 9.09%   |
| 25     | 1         | 9.09%   |
| 17     | 1         | 9.09%   |
| 12     | 1         | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 4         | 36.36%  |
| 501-600     | 2         | 18.18%  |
| 401-500     | 2         | 18.18%  |
| 201-300     | 2         | 18.18%  |
| 351-400     | 1         | 9.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 7         | 70%     |
| 3/2   | 2         | 20%     |
| 16/10 | 1         | 10%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3         | 27.27%  |
| 81-90          | 2         | 18.18%  |
| 201-250        | 2         | 18.18%  |
| 71-80          | 1         | 9.09%   |
| 301-350        | 1         | 9.09%   |
| 251-300        | 1         | 9.09%   |
| 121-130        | 1         | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 6         | 54.55%  |
| 101-120 | 3         | 27.27%  |
| 161-240 | 1         | 9.09%   |
| 51-100  | 1         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 11        | 84.62%  |
| 3     | 1         | 7.69%   |
| 0     | 1         | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 6         | 35.29%  |
| Intel                    | 6         | 35.29%  |
| TP-Link                  | 1         | 5.88%   |
| Nvidia                   | 1         | 5.88%   |
| Marvell Technology Group | 1         | 5.88%   |
| Broadcom                 | 1         | 5.88%   |
| ASIX Electronics         | 1         | 5.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 11.11%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2         | 11.11%  |
| Intel Wireless 7260                                               | 2         | 11.11%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 11.11%  |
| TP-Link TL WN823N RTL8192EU                                       | 1         | 5.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 5.56%   |
| Nvidia MCP61 Ethernet                                             | 1         | 5.56%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 5.56%   |
| Intel I211 Gigabit Network Connection                             | 1         | 5.56%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 5.56%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 5.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 5.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 5.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 4         | 40%     |
| Intel                    | 3         | 30%     |
| TP-Link                  | 1         | 10%     |
| Marvell Technology Group | 1         | 10%     |
| Broadcom                 | 1         | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 2         | 20%     |
| Intel Wireless 7260                                      | 2         | 20%     |
| TP-Link TL WN823N RTL8192EU                              | 1         | 10%     |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter          | 1         | 10%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 1         | 10%     |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless        | 1         | 10%     |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]            | 1         | 10%     |
| Broadcom BCM43228 802.11a/b/g/n                          | 1         | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 4         | 50%     |
| Realtek Semiconductor | 2         | 25%     |
| Nvidia                | 1         | 12.5%   |
| ASIX Electronics      | 1         | 12.5%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2         | 25%     |
| Intel Ethernet Connection I217-LM                                 | 2         | 25%     |
| Nvidia MCP61 Ethernet                                             | 1         | 12.5%   |
| Intel I211 Gigabit Network Connection                             | 1         | 12.5%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 12.5%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 12.5%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 10        | 55.56%  |
| Ethernet | 8         | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 10        | 58.82%  |
| Ethernet | 7         | 41.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 8         | 66.67%  |
| 2     | 4         | 33.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7         | 58.33%  |
| Yes  | 5         | 41.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Realtek Semiconductor   | 2         | 22.22%  |
| Realtek                 | 2         | 22.22%  |
| Intel                   | 2         | 22.22%  |
| Marvell Semiconductor   | 1         | 11.11%  |
| Cambridge Silicon Radio | 1         | 11.11%  |
| ASUSTek Computer        | 1         | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 2         | 22.22%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 11.11%  |
| Realtek Bluetooth Radio                             | 1         | 11.11%  |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 11.11%  |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 11.11%  |
| Intel Bluetooth wireless interface                  | 1         | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 11.11%  |
| ASUS BCM20702A0                                     | 1         | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 7         | 41.18%  |
| AMD      | 5         | 29.41%  |
| Nvidia   | 4         | 23.53%  |
| Micronas | 1         | 5.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 3         | 13.04%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 8.7%    |
| Intel Sunrise Point-LP HD Audio                                     | 2         | 8.7%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 2         | 8.7%    |
| Nvidia MCP61 High Definition Audio                                  | 1         | 4.35%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 4.35%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 4.35%   |
| Nvidia GK104 HDMI Audio Controller                                  | 1         | 4.35%   |
| Micronas BLUE USB Audio 2.0                                         | 1         | 4.35%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 4.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 4.35%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 1         | 4.35%   |
| AMD Starship/Matisse HD Audio Controller                            | 1         | 4.35%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 4.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 4.35%   |
| AMD Kaveri HDMI/DP Audio Controller                                 | 1         | 4.35%   |
| AMD FCH Azalia Controller                                           | 1         | 4.35%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1         | 4.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 44.44%  |
| Micron Technology   | 2         | 22.22%  |
| Corsair             | 2         | 22.22%  |
| SK Hynix            | 1         | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 10%     |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 1         | 10%     |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 10%     |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 10%     |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 10%     |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 10%     |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s            | 1         | 10%     |
| Corsair RAM VS2GB1333D4 2048MB DIMM DDR3 1600MT/s                | 1         | 10%     |
| Corsair RAM VS2GB1333D3 2GB DIMM DDR3 1333MT/s                   | 1         | 10%     |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s            | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 4         | 44.44%  |
| DDR3   | 4         | 44.44%  |
| LPDDR3 | 1         | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3         | 33.33%  |
| Row Of Chips | 3         | 33.33%  |
| DIMM         | 3         | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 5         | 50%     |
| 8192 | 4         | 40%     |
| 2048 | 1         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 4         | 40%     |
| 1867  | 2         | 20%     |
| 1600  | 2         | 20%     |
| 1333  | 2         | 20%     |

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


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Quanta              | 2         | 28.57%  |
| IMC Networks        | 2         | 28.57%  |
| Chicony Electronics | 2         | 28.57%  |
| Logitech            | 1         | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Quanta HP Wide Vision HD Camera      | 2         | 25%     |
| Logitech QuickCam Pro 9000           | 1         | 12.5%   |
| IMC Networks ov9734_azurewave_camera | 1         | 12.5%   |
| IMC Networks HD Camera               | 1         | 12.5%   |
| Chicony USB2.0 2M WebCam             | 1         | 12.5%   |
| Chicony USB 5M WebCam                | 1         | 12.5%   |
| Chicony Integrated Camera            | 1         | 12.5%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 50%     |
| Validity Sensors           | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device          | 2         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 25%     |
| LighTuning EgisTec_ES603                     | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 7         | 58.33%  |
| 1     | 5         | 41.67%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 80%     |
| Multimedia controller | 1         | 20%     |

