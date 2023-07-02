Cyber Infra - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Cyber Infra.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Cyber_Infra/Desktop/README.md) and [notebooks](/Dist/Cyber_Infra/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 50

| Vendor        | Model                   | Form-Factor | Probe                                                      | Date         |
|---------------|-------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME Z270-A            | Desktop     | [e2531ea6c8](https://linux-hardware.org/?probe=e2531ea6c8) | Jun 16, 2023 |
| Supermicro    | X11DDW-NT               | Server      | [6e0ca764b5](https://linux-hardware.org/?probe=6e0ca764b5) | Jun 14, 2023 |
| Intel         | M50CYP2SBSTD K42381-351 | Server      | [b1b7037d4f](https://linux-hardware.org/?probe=b1b7037d4f) | Jun 14, 2023 |
| Lenovo        | 7X06CTO1WW              | Server      | [dc3ea6dbb8](https://linux-hardware.org/?probe=dc3ea6dbb8) | Jun 14, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+   | Server      | [b4eb1cdd06](https://linux-hardware.org/?probe=b4eb1cdd06) | Jun 07, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [5950749033](https://linux-hardware.org/?probe=5950749033) | Jun 07, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [f8a6482d0e](https://linux-hardware.org/?probe=f8a6482d0e) | May 29, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [18b2bf9ff4](https://linux-hardware.org/?probe=18b2bf9ff4) | Apr 05, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [844c562cb6](https://linux-hardware.org/?probe=844c562cb6) | Apr 05, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [a7057f367a](https://linux-hardware.org/?probe=a7057f367a) | Apr 05, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [0ce29ba75c](https://linux-hardware.org/?probe=0ce29ba75c) | Apr 05, 2023 |
| Supermicro    | X10DRL-i                | Server      | [5e92e7fe1e](https://linux-hardware.org/?probe=5e92e7fe1e) | Apr 05, 2023 |
| Supermicro    | X10SRi-FB               | Server      | [16a0245a41](https://linux-hardware.org/?probe=16a0245a41) | Apr 05, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+   | Server      | [c4b4851a88](https://linux-hardware.org/?probe=c4b4851a88) | Apr 05, 2023 |
| Delta Comp... | DSS-C621LTG             | Server      | [97e6e94ed2](https://linux-hardware.org/?probe=97e6e94ed2) | Apr 04, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [3e3cb25241](https://linux-hardware.org/?probe=3e3cb25241) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [19fddb0a01](https://linux-hardware.org/?probe=19fddb0a01) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [80e5cfeea5](https://linux-hardware.org/?probe=80e5cfeea5) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [83ff998a9a](https://linux-hardware.org/?probe=83ff998a9a) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [61af44de6d](https://linux-hardware.org/?probe=61af44de6d) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [dd8597fd65](https://linux-hardware.org/?probe=dd8597fd65) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [090720bc72](https://linux-hardware.org/?probe=090720bc72) | Mar 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [8b83576100](https://linux-hardware.org/?probe=8b83576100) | Feb 28, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [c33e8fab03](https://linux-hardware.org/?probe=c33e8fab03) | Feb 28, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [2f3379adb9](https://linux-hardware.org/?probe=2f3379adb9) | Feb 28, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [efc03f8d68](https://linux-hardware.org/?probe=efc03f8d68) | Feb 27, 2023 |
| Supermicro    | X12DAi-N6               | Server      | [814fc144ef](https://linux-hardware.org/?probe=814fc144ef) | Feb 03, 2023 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [bdfa203c78](https://linux-hardware.org/?probe=bdfa203c78) | Jan 16, 2023 |
| Supermicro    | X11SSM-F                | Server      | [b0100c59bb](https://linux-hardware.org/?probe=b0100c59bb) | Dec 12, 2022 |
| Supermicro    | X11SSL-F                | Server      | [7aa0eb0936](https://linux-hardware.org/?probe=7aa0eb0936) | Dec 12, 2022 |
| Supermicro    | X11SSL-F                | Server      | [1a5e57e9ef](https://linux-hardware.org/?probe=1a5e57e9ef) | Oct 31, 2022 |
| Supermicro    | X11SSM-F                | Server      | [c54a576ec0](https://linux-hardware.org/?probe=c54a576ec0) | Oct 31, 2022 |
| Supermicro    | X11SSL-F                | Server      | [c13d2d5610](https://linux-hardware.org/?probe=c13d2d5610) | Oct 31, 2022 |
| Supermicro    | X11SSL-F                | Server      | [2de30f0154](https://linux-hardware.org/?probe=2de30f0154) | Aug 30, 2022 |
| Supermicro    | X11SSL-F                | Server      | [3f8bec5c1b](https://linux-hardware.org/?probe=3f8bec5c1b) | Aug 30, 2022 |
| Supermicro    | X11SSM-F                | Server      | [f715802815](https://linux-hardware.org/?probe=f715802815) | Aug 30, 2022 |
| Supermicro    | X10DRL-i                | Server      | [5281defed3](https://linux-hardware.org/?probe=5281defed3) | Aug 15, 2022 |
| Supermicro    | X10DRL-i                | Server      | [88a4a3d13f](https://linux-hardware.org/?probe=88a4a3d13f) | Aug 04, 2022 |
| Supermicro    | X10DRL-i                | Server      | [9b4576c901](https://linux-hardware.org/?probe=9b4576c901) | Aug 03, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [60ec07883b](https://linux-hardware.org/?probe=60ec07883b) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [912e712657](https://linux-hardware.org/?probe=912e712657) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [3229b1f14c](https://linux-hardware.org/?probe=3229b1f14c) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [ad5b15b222](https://linux-hardware.org/?probe=ad5b15b222) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [6539922005](https://linux-hardware.org/?probe=6539922005) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [0c77bbd30d](https://linux-hardware.org/?probe=0c77bbd30d) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [85a5b4c02f](https://linux-hardware.org/?probe=85a5b4c02f) | May 14, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [d9f3fb8d37](https://linux-hardware.org/?probe=d9f3fb8d37) | May 14, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [fdf91b6130](https://linux-hardware.org/?probe=fdf91b6130) | May 13, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [9c97cfa2bc](https://linux-hardware.org/?probe=9c97cfa2bc) | May 13, 2022 |
| Supermicro    | B11SPE-CPU-TF           | Server      | [6f63fd533c](https://linux-hardware.org/?probe=6f63fd533c) | May 13, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Cyber Infra 5.0.1 | 37        | 97.37%  |
| Cyber Infra 4.0.1 | 1         | 2.63%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Cyber Infra | 38        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 3.10.0-1160.41.1.vz7.183.5 | 37        | 97.37%  |
| 3.10.0-1127.8.2.vz7.158.8  | 1         | 2.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10.0  | 38        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10    | 38        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 38        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 38        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 38        | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 22        | 57.89%  |
| BIOS | 16        | 42.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 38        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 38        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 94.87%  |
| Yes       | 2         | 5.13%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Supermicro       | 31        | 81.58%  |
| Delta Computers  | 4         | 10.53%  |
| Lenovo           | 1         | 2.63%   |
| Intel            | 1         | 2.63%   |
| ASUSTek Computer | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Supermicro SBI-6119P-T3N                | 10        | 26.32%  |
| Supermicro AS -1014S-WTRT               | 10        | 26.32%  |
| Supermicro Super Server                 | 8         | 21.05%  |
| Delta Computers DSS-C621LTG             | 4         | 10.53%  |
| Supermicro X9DRi-LN4+/X9DR3-LN4+        | 1         | 2.63%   |
| Supermicro X12DAi-N6                    | 1         | 2.63%   |
| Supermicro SYS-6029P-WTRT               | 1         | 2.63%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]- | 1         | 2.63%   |
| Intel M50CYP2SBSTD                      | 1         | 2.63%   |
| ASUS PRIME Z270-A                       | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Supermicro SBI-6119P-T3N    | 10        | 26.32%  |
| Supermicro AS               | 10        | 26.32%  |
| Supermicro Super            | 8         | 21.05%  |
| Delta Computers DSS-C621LTG | 4         | 10.53%  |
| Supermicro X9DRi-LN4+       | 1         | 2.63%   |
| Supermicro X12DAi-N6        | 1         | 2.63%   |
| Supermicro SYS-6029P-WTRT   | 1         | 2.63%   |
| Lenovo ThinkSystem          | 1         | 2.63%   |
| Intel M50CYP2SBSTD          | 1         | 2.63%   |
| ASUS PRIME                  | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 21        | 55.26%  |
| 2015 | 7         | 18.42%  |
| 2022 | 6         | 15.79%  |
| 2021 | 1         | 2.63%   |
| 2019 | 1         | 2.63%   |
| 2018 | 1         | 2.63%   |
| 2016 | 1         | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Server  | 37        | 97.37%  |
| Desktop | 1         | 2.63%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 38        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 38        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| More than 256.0 | 19        | 47.5%   |
| 64.01-256.0     | 15        | 37.5%   |
| 32.01-64.0      | 4         | 10%     |
| 16.01-24.0      | 2         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 18        | 42.86%  |
| 4.01-8.0   | 12        | 28.57%  |
| 32.01-64.0 | 3         | 7.14%   |
| 3.01-4.0   | 3         | 7.14%   |
| 16.01-24.0 | 2         | 4.76%   |
| 1.01-2.0   | 2         | 4.76%   |
| 24.01-32.0 | 1         | 2.38%   |
| 2.01-3.0   | 1         | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 5      | 14        | 32.56%  |
| 3      | 11        | 25.58%  |
| 8      | 4         | 9.3%    |
| 4      | 4         | 9.3%    |
| 1      | 3         | 6.98%   |
| 9      | 2         | 4.65%   |
| 6      | 2         | 4.65%   |
| 17     | 1         | 2.33%   |
| 10     | 1         | 2.33%   |
| 2      | 1         | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 100%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 38        | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City   | Computers | Percent |
|--------|-----------|---------|
| Moscow | 37        | 97.37%  |
| Perm   | 1         | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Intel               | 15        | 39     | 20.83%  |
| Seagate             | 14        | 19     | 19.44%  |
| Samsung Electronics | 13        | 61     | 18.06%  |
| Micron Technology   | 9         | 36     | 12.5%   |
| Toshiba             | 6         | 31     | 8.33%   |
| HGST                | 5         | 9      | 6.94%   |
| WDC                 | 2         | 3      | 2.78%   |
| SCST_BIO            | 2         | 6      | 2.78%   |
| Hitachi             | 2         | 5      | 2.78%   |
| VSTORAGE            | 1         | 1      | 1.39%   |
| Lenovo              | 1         | 14     | 1.39%   |
| Kingston            | 1         | 1      | 1.39%   |
| Foxline             | 1         | 2      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Seagate ST4000NM000A-2HZ100 4TB                              | 11        | 10.68%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB           | 11        | 10.68%  |
| Samsung MZ7L3480HBLT-00A07 480GB SSD                         | 10        | 9.71%   |
| Intel SSDSC2KG240G8 240GB                                    | 10        | 9.71%   |
| Intel SSDSC2KB960G8 960GB                                    | 10        | 9.71%   |
| Micron 7300_MTFDHBE3T8TDF 4TB                                | 4         | 3.88%   |
| Intel PCIe Data Center SSD 1TB                               | 4         | 3.88%   |
| Toshiba MG04ACA400E 4TB                                      | 3         | 2.91%   |
| Seagate ST4000NM0035-1V4107 4TB                              | 3         | 2.91%   |
| Toshiba MG03ACA100 1TB                                       | 2         | 1.94%   |
| Toshiba HDWD130 3TB                                          | 2         | 1.94%   |
| Micron 5300_MTFDDAK480TDS 480GB SSD                          | 2         | 1.94%   |
| Micron 5200_MTFDDAK480TDN 480GB SSD                          | 2         | 1.94%   |
| Micron 5100_MTFDDAK960TCB 960GB SSD                          | 2         | 1.94%   |
| Micron 1100_MTFDDAK512TBN 512GB SSD                          | 2         | 1.94%   |
| WDC WD4002FYYZ-01B7CB1 4TB                                   | 1         | 0.97%   |
| WDC WD1003FBYZ-010FB0 1TB                                    | 1         | 0.97%   |
| VSTORAGE VSTOR-DISK 5.4TB                                    | 1         | 0.97%   |
| Toshiba XG6 NVMe SSD Controller 2TB                          | 1         | 0.97%   |
| Toshiba MG03SCA100 1TB                                       | 1         | 0.97%   |
| SCST_BIO LD4 4TB                                             | 1         | 0.97%   |
| SCST_BIO LD33 1TB                                            | 1         | 0.97%   |
| SCST_BIO LD3 1TB                                             | 1         | 0.97%   |
| SCST_BIO LD22 1TB                                            | 1         | 0.97%   |
| Samsung SSD 850 PRO 512GB                                    | 1         | 0.97%   |
| Samsung MZ7LH240HAHQ-00005 240GB SSD                         | 1         | 0.97%   |
| Micron 7400_MTFDKBA480TDZ 480GB                              | 1         | 0.97%   |
| Micron 5300_MTFDDAK7T6TDS 8TB SSD                            | 1         | 0.97%   |
| Lenovo ST600MM0009 600GB                                     | 1         | 0.97%   |
| Lenovo MZILS400HEGRV3 400GB                                  | 1         | 0.97%   |
| Kingston SEDC1000BM8240G 240GB                               | 1         | 0.97%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller] 1TB | 1         | 0.97%   |
| Hitachi HUC106060CSS600 600GB                                | 1         | 0.97%   |
| Hitachi HDS721010CLA330 1TB                                  | 1         | 0.97%   |
| HGST HUS726T6TALE6L4 6TB                                     | 1         | 0.97%   |
| HGST HUS726T4TALE6L4 4TB                                     | 1         | 0.97%   |
| HGST HUS726040ALE614 4TB                                     | 1         | 0.97%   |
| HGST HUS726020ALE614 2TB                                     | 1         | 0.97%   |
| HGST HUS724040ALA640 4TB                                     | 1         | 0.97%   |
| Foxline FLSSD256X5SE 256GB                                   | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 14        | 19     | 42.42%  |
| Toshiba  | 6         | 30     | 18.18%  |
| HGST     | 5         | 9      | 15.15%  |
| WDC      | 2         | 3      | 6.06%   |
| SCST_BIO | 2         | 6      | 6.06%   |
| Hitachi  | 2         | 5      | 6.06%   |
| VSTORAGE | 1         | 1      | 3.03%   |
| Lenovo   | 1         | 10     | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 34     | 37.5%   |
| Intel               | 10        | 32     | 31.25%  |
| Micron Technology   | 8         | 15     | 25%     |
| Lenovo              | 1         | 4      | 3.13%   |
| Foxline             | 1         | 2      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 30        | 87     | 37.5%   |
| HDD  | 27        | 83     | 33.75%  |
| NVMe | 23        | 57     | 28.75%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 163    | 58.73%  |
| NVMe | 23        | 57     | 36.51%  |
| SAS  | 3         | 7      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 56     | 37.5%   |
| 3.01-4.0   | 21        | 47     | 29.17%  |
| 0.51-1.0   | 19        | 56     | 26.39%  |
| 2.01-3.0   | 2         | 6      | 2.78%   |
| 4.01-10.0  | 2         | 4      | 2.78%   |
| 1.01-2.0   | 1         | 1      | 1.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 15        | 35.71%  |
| More than 3000 | 12        | 28.57%  |
| 2001-3000      | 7         | 16.67%  |
| 251-500        | 6         | 14.29%  |
| 501-1000       | 2         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 23        | 51.11%  |
| 21-50          | 9         | 20%     |
| 251-500        | 7         | 15.56%  |
| 51-100         | 3         | 6.67%   |
| More than 3000 | 1         | 2.22%   |
| 2001-3000      | 1         | 2.22%   |
| 501-1000       | 1         | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD | 1         | 3      | 50%     |
| Hitachi HDS721010CLA330 1TB                    | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Micron Technology | 1         | 3      | 50%     |
| Hitachi           | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 3      | 50%     |
| HDD  | 1         | 1      | 50%     |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 38        | 222    | 92.68%  |
| Malfunc  | 2         | 4      | 4.88%   |
| Detected | 1         | 1      | 2.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 28        | 36.84%  |
| ASMedia Technology           | 14        | 18.42%  |
| Samsung Electronics          | 11        | 14.47%  |
| AMD                          | 10        | 13.16%  |
| Micron Technology            | 5         | 6.58%   |
| Broadcom / LSI               | 3         | 3.95%   |
| LSI Logic / Symbios Logic    | 2         | 2.63%   |
| Toshiba America Info Systems | 1         | 1.32%   |
| Kingston Technology Company  | 1         | 1.32%   |
| Areca Technology             | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                 | 16        | 15.69%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 11        | 10.78%  |
| ASMedia ASM1062 Serial ATA Controller                                         | 10        | 9.8%    |
| AMD FCH SATA Controller [AHCI mode]                                           | 10        | 9.8%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                  | 9         | 8.82%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 9         | 8.82%   |
| Micron 7300 PRO NVMe SSD                                                      | 4         | 3.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 4         | 3.92%   |
| Intel PCIe Data Center SSD                                                    | 4         | 3.92%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 4         | 3.92%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 4         | 3.92%   |
| ASMedia 106x SATA/RAID Controller                                             | 4         | 3.92%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                          | 2         | 1.96%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 0.98%   |
| Micron 7400 PRO NVMe SSD                                                      | 1         | 0.98%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 0.98%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                      | 1         | 0.98%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1         | 0.98%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 1         | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1         | 0.98%   |
| Broadcom / LSI MegaRAID Tri-Mode SAS3508                                      | 1         | 0.98%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                  | 1         | 0.98%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                | 1         | 0.98%   |
| Areca ARC-1886 series PCIe 4.0 to NVMe/SAS/SATA 16/12/6Gb RAID Controller     | 1         | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 49.35%  |
| NVMe | 23        | 29.87%  |
| RAID | 14        | 18.18%  |
| SAS  | 2         | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 73.68%  |
| AMD    | 10        | 26.32%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel Xeon Silver 4208 CPU @ 2.10GHz  | 10        | 26.32%  |
| AMD EPYC 7352 24-Core Processor       | 10        | 26.32%  |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz   | 2         | 5.26%   |
| Intel Xeon CPU E3-1230 v6 @ 3.50GHz   | 2         | 5.26%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz   | 2         | 5.26%   |
| Intel Xeon Silver 4210R CPU @ 2.40GHz | 1         | 2.63%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz  | 1         | 2.63%   |
| Intel Xeon Gold 6346 CPU @ 3.10GHz    | 1         | 2.63%   |
| Intel Xeon Gold 6326 CPU @ 2.90GHz    | 1         | 2.63%   |
| Intel Xeon Gold 6248 CPU @ 2.50GHz    | 1         | 2.63%   |
| Intel Xeon Gold 6238R CPU @ 2.20GHz   | 1         | 2.63%   |
| Intel Xeon Gold 6140 CPU @ 2.30GHz    | 1         | 2.63%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz   | 1         | 2.63%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz    | 1         | 2.63%   |
| Intel Xeon CPU E5-2630 v4 @ 2.20GHz   | 1         | 2.63%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz   | 1         | 2.63%   |
| Intel Core i7-7700 CPU @ 3.60GHz      | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Xeon Silver | 12        | 31.58%  |
| AMD EPYC          | 10        | 26.32%  |
| Intel Xeon        | 9         | 23.68%  |
| Intel Xeon Gold   | 6         | 15.79%  |
| Intel Core i7     | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 24     | 10        | 26.32%  |
| 8      | 10        | 26.32%  |
| 4      | 5         | 13.16%  |
| 20     | 4         | 10.53%  |
| 32     | 2         | 5.26%   |
| 56     | 1         | 2.63%   |
| 48     | 1         | 2.63%   |
| 40     | 1         | 2.63%   |
| 36     | 1         | 2.63%   |
| 16     | 1         | 2.63%   |
| 12     | 1         | 2.63%   |
| 10     | 1         | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 68.42%  |
| 2      | 12        | 31.58%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 97.37%  |
| 1      | 1         | 2.63%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x50657    | 15        | 37.5%   |
| 0x08301055 | 10        | 25%     |
| 0x406f1    | 4         | 10%     |
| 0x906e9    | 3         | 7.5%    |
| 0x606a6    | 2         | 5%      |
| 0x506e3    | 2         | 5%      |
| Unknown    | 2         | 5%      |
| 0x50654    | 1         | 2.5%    |
| 0x206d7    | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Skylake     | 18        | 47.37%  |
| Zen 2       | 10        | 26.32%  |
| Broadwell   | 4         | 10.53%  |
| KabyLake    | 3         | 7.89%   |
| Unknown     | 2         | 5.26%   |
| SandyBridge | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| ASPEED Technology          | 35        | 87.5%   |
| Nvidia                     | 2         | 5%      |
| Matrox Electronics Systems | 2         | 5%      |
| Intel                      | 1         | 2.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                          | 35        | 85.37%  |
| Nvidia GV100GL [Tesla V100 PCIe 32GB]                             | 1         | 2.44%   |
| Nvidia GA107GL [A2 / A16]                                         | 1         | 2.44%   |
| Nvidia GA100 [A100 PCIe 40GB]                                     | 1         | 2.44%   |
| Matrox Electronics Systems MGA G200eW WPCM450                     | 1         | 2.44%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1) | 1         | 2.44%   |
| Intel HD Graphics 630                                             | 1         | 2.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x ASPEED              | 34        | 89.47%  |
| 2 x Nvidia + 1 x ASPEED | 1         | 2.63%   |
| Nvidia + Matrox         | 1         | 2.63%   |
| 1 x Matrox              | 1         | 2.63%   |
| 1 x Intel               | 1         | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 38        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 97.37%  |
| 24.01-32.0 | 1         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| ViewSonic        | 1         | 25%     |
| Dell             | 1         | 25%     |
| BenQ             | 1         | 25%     |
| ASUSTek Computer | 1         | 25%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| ViewSonic VA2245 Series VSCF42E 1920x1080 477x268mm 21.5-inch  | 1         | 25%     |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch              | 1         | 25%     |
| BenQ E2220HD BNQ7912 1920x1080 477x268mm 21.5-inch             | 1         | 25%     |
| ASUSTek Computer PA247CV AUS2464 1920x1080 527x296mm 23.8-inch | 1         | 25%     |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 3         | 100%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 21     | 2         | 50%     |
| 24     | 1         | 25%     |
| 23     | 1         | 25%     |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 401-500     | 2         | 66.67%  |
| 501-600     | 1         | 33.33%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 3         | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 151-200        | 2         | 66.67%  |
| 201-250        | 1         | 33.33%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 2         | 66.67%  |
| 51-100  | 1         | 33.33%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 35        | 89.74%  |
| 1     | 3         | 7.69%   |
| 2     | 1         | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 46.91%  |
| Mellanox Technologies | 25        | 30.86%  |
| Broadcom              | 10        | 12.35%  |
| Emulex                | 5         | 6.17%   |
| Insyde Software       | 2         | 2.47%   |
| IBM                   | 1         | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Mellanox MT27700 Family [ConnectX-4]                                          | 13        | 15.66%  |
| Intel I210 Gigabit Network Connection                                         | 12        | 14.46%  |
| Intel Ethernet Controller E810-XXV for SFP                                    | 11        | 13.25%  |
| Intel Ethernet Connection X722 for 10GbE backplane                            | 10        | 12.05%  |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller         | 10        | 12.05%  |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 8         | 9.64%   |
| Emulex OneConnect NIC (Skyhawk)                                               | 5         | 6.02%   |
| Mellanox MT27800 Family [ConnectX-5]                                          | 3         | 3.61%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 2.41%   |
| Intel I350 Gigabit Network Connection                                         | 2         | 2.41%   |
| Insyde Software RNDIS/Ethernet Gadget                                         | 2         | 2.41%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 1         | 1.2%    |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 1.2%    |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 1.2%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.2%    |
| IBM RNDIS/CDC ETHER                                                           | 1         | 1.2%    |

Wireless Vendor
---------------

Wireless vendors

Zero info for selected period =(

Wireless Model
--------------

Wireless models

Zero info for selected period =(

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 52.05%  |
| Mellanox Technologies | 17        | 23.29%  |
| Broadcom              | 10        | 13.7%   |
| Emulex                | 5         | 6.85%   |
| Insyde Software       | 2         | 2.74%   |
| IBM                   | 1         | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I210 Gigabit Network Connection                                         | 12        | 16%     |
| Intel Ethernet Controller E810-XXV for SFP                                    | 11        | 14.67%  |
| Intel Ethernet Connection X722 for 10GbE backplane                            | 10        | 13.33%  |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller         | 10        | 13.33%  |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 8         | 10.67%  |
| Mellanox MT27700 Family [ConnectX-4]                                          | 5         | 6.67%   |
| Emulex OneConnect NIC (Skyhawk)                                               | 5         | 6.67%   |
| Mellanox MT27800 Family [ConnectX-5]                                          | 3         | 4%      |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 2.67%   |
| Intel I350 Gigabit Network Connection                                         | 2         | 2.67%   |
| Insyde Software RNDIS/Ethernet Gadget                                         | 2         | 2.67%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 1         | 1.33%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 1.33%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 1.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.33%   |
| IBM RNDIS/CDC ETHER                                                           | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 82.61%  |
| Unknown  | 8         | 17.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 97.44%  |
| Unknown  | 1         | 2.56%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 6     | 14        | 35%     |
| 2     | 14        | 35%     |
| 4     | 5         | 12.5%   |
| 3     | 4         | 10%     |
| 8     | 1         | 2.5%    |
| 5     | 1         | 2.5%    |
| 1     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 38        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

Zero info for selected period =(

Bluetooth Model
---------------

Controller models

Zero info for selected period =(

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2         | 100%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel Lewisburg MROM 0        | 1         | 50%     |
| Intel 200 Series PCH HD Audio | 1         | 50%     |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 41.03%  |
| Micron Technology   | 13        | 33.33%  |
| Nanya Technology    | 4         | 10.26%  |
| Kingston            | 4         | 10.26%  |
| SK hynix            | 2         | 5.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M393A8G40BB4-CWE 64GB DIMM DDR4 3200MT/s    | 10        | 25.64%  |
| Micron RAM 36ASF4G72PZ-2G9E2 32GB DIMM DDR4 2933MT/s    | 10        | 25.64%  |
| Nanya RAM NT32GA72D4NBX3P-IX 32GB DIMM DDR4 2933MT/s    | 4         | 10.26%  |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s    | 2         | 5.13%   |
| Micron RAM 18ASF2G72AZ-2G3B1 16GB DIMM DDR4 2400MT/s    | 2         | 5.13%   |
| SK hynix RAM HMT42GR7MFR4C-PB 16GB DIMM DDR3 1600MT/s   | 1         | 2.56%   |
| SK hynix RAM HMA84GR7AFR4N-VK 32GB DIMM DDR4 2667MT/s   | 1         | 2.56%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s    | 1         | 2.56%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s    | 1         | 2.56%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s    | 1         | 2.56%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s    | 1         | 2.56%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16384MB DIMM DDR4 2667MT/s | 1         | 2.56%   |
| Kingston RAM 9965742-055.B00G 32GB DIMM DDR4 3200MT/s   | 1         | 2.56%   |
| Kingston RAM 9965669-008.A03G 16GB DIMM DDR4 2134MT/s   | 1         | 2.56%   |
| Kingston RAM 9965640-016.A00G 32GB DIMM DDR4 2133MT/s   | 1         | 2.56%   |
| Kingston RAM 9965516-071.A00LF 16GB DIMM DDR3 1066MT/s  | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 37        | 97.37%  |
| DDR3 | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| DIMM | 38        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 32768 | 22        | 57.89%  |
| 65536 | 10        | 26.32%  |
| 16384 | 6         | 15.79%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2933  | 14        | 35.9%   |
| 3200  | 13        | 33.33%  |
| 2400  | 5         | 12.82%  |
| 2667  | 2         | 5.13%   |
| 3466  | 1         | 2.56%   |
| 2134  | 1         | 2.56%   |
| 2133  | 1         | 2.56%   |
| 1600  | 1         | 2.56%   |
| 1066  | 1         | 2.56%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 15        | 39.47%  |
| 4     | 14        | 36.84%  |
| 2     | 4         | 10.53%  |
| 5     | 3         | 7.89%   |
| 3     | 1         | 2.63%   |
| 1     | 1         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 23        | 46%     |
| Unassigned class         | 22        | 44%     |
| Graphics card            | 4         | 8%      |
| Storage/raid             | 1         | 2%      |

