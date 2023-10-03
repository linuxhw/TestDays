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

Total: 60

| Vendor        | Model                   | Form-Factor | Probe                                                      | Date         |
|---------------|-------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 04V528 A02              | Server      | [96ef3c9fdd](https://linux-hardware.org/?probe=96ef3c9fdd) | Sep 22, 2023 |
| Dell          | 0JMK61 A00              | Server      | [e0bd072160](https://linux-hardware.org/?probe=e0bd072160) | Sep 21, 2023 |
| Dell          | 0RGP26 A00              | Server      | [d35a82a9ec](https://linux-hardware.org/?probe=d35a82a9ec) | Sep 21, 2023 |
| Dell          | 06DKY5 A03              | Server      | [a86e860c3d](https://linux-hardware.org/?probe=a86e860c3d) | Sep 21, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [29cabf2b17](https://linux-hardware.org/?probe=29cabf2b17) | Jul 09, 2023 |
| Supermicro    | H12SSW-NT               | Server      | [471a0154cb](https://linux-hardware.org/?probe=471a0154cb) | Jul 09, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [7f1e769c28](https://linux-hardware.org/?probe=7f1e769c28) | Jul 05, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [6e33251220](https://linux-hardware.org/?probe=6e33251220) | Jul 05, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [da1eee177b](https://linux-hardware.org/?probe=da1eee177b) | Jul 05, 2023 |
| Unknown       | R182-N20-UNI            | Server      | [f9074e4a79](https://linux-hardware.org/?probe=f9074e4a79) | Jul 05, 2023 |
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
| Cyber Infra 5.0.1 | 45        | 97.83%  |
| Cyber Infra 4.0.1 | 1         | 2.17%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Cyber Infra | 46        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 3.10.0-1160.41.1.vz7.183.5 | 45        | 97.83%  |
| 3.10.0-1127.8.2.vz7.158.8  | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10.0  | 46        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10    | 46        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 46        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 42        | 91.3%   |
| ru_RU | 4         | 8.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 30        | 62.5%   |
| BIOS | 18        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 46        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 46        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 95.74%  |
| Yes       | 2         | 4.26%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Supermicro       | 31        | 67.39%  |
| Delta Computers  | 4         | 8.7%    |
| Dell             | 4         | 8.7%    |
| Unknown          | 4         | 8.7%    |
| Lenovo           | 1         | 2.17%   |
| Intel            | 1         | 2.17%   |
| ASUSTek Computer | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Supermicro SBI-6119P-T3N                | 10        | 21.74%  |
| Supermicro AS -1014S-WTRT               | 10        | 21.74%  |
| Supermicro Super Server                 | 8         | 17.39%  |
| Delta Computers DSS-C621LTG             | 4         | 8.7%    |
| Unknown                                 | 4         | 8.7%    |
| Supermicro X9DRi-LN4+/X9DR3-LN4+        | 1         | 2.17%   |
| Supermicro X12DAi-N6                    | 1         | 2.17%   |
| Supermicro SYS-6029P-WTRT               | 1         | 2.17%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]- | 1         | 2.17%   |
| Intel M50CYP2SBSTD                      | 1         | 2.17%   |
| Dell XC640-10 CORE                      | 1         | 2.17%   |
| Dell PowerEdge R750                     | 1         | 2.17%   |
| Dell PowerEdge R740                     | 1         | 2.17%   |
| Dell PowerEdge R640                     | 1         | 2.17%   |
| ASUS PRIME Z270-A                       | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Supermicro SBI-6119P-T3N    | 10        | 21.74%  |
| Supermicro AS               | 10        | 21.74%  |
| Supermicro Super            | 8         | 17.39%  |
| Delta Computers DSS-C621LTG | 4         | 8.7%    |
| Unknown                     | 4         | 8.7%    |
| Dell PowerEdge              | 3         | 6.52%   |
| Supermicro X9DRi-LN4+       | 1         | 2.17%   |
| Supermicro X12DAi-N6        | 1         | 2.17%   |
| Supermicro SYS-6029P-WTRT   | 1         | 2.17%   |
| Lenovo ThinkSystem          | 1         | 2.17%   |
| Intel M50CYP2SBSTD          | 1         | 2.17%   |
| Dell XC640-10               | 1         | 2.17%   |
| ASUS PRIME                  | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 22        | 47.83%  |
| 2022 | 11        | 23.91%  |
| 2015 | 7         | 15.22%  |
| 2021 | 2         | 4.35%   |
| 2019 | 2         | 4.35%   |
| 2018 | 1         | 2.17%   |
| 2016 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Server  | 45        | 97.83%  |
| Desktop | 1         | 2.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 46        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| More than 256.0 | 22        | 45.83%  |
| 64.01-256.0     | 20        | 41.67%  |
| 32.01-64.0      | 4         | 8.33%   |
| 16.01-24.0      | 2         | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 18        | 36%     |
| 4.01-8.0    | 14        | 28%     |
| 3.01-4.0    | 5         | 10%     |
| 32.01-64.0  | 4         | 8%      |
| 64.01-256.0 | 3         | 6%      |
| 16.01-24.0  | 2         | 4%      |
| 1.01-2.0    | 2         | 4%      |
| 24.01-32.0  | 1         | 2%      |
| 2.01-3.0    | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 5      | 19        | 35.85%  |
| 3      | 11        | 20.75%  |
| 8      | 4         | 7.55%   |
| 6      | 4         | 7.55%   |
| 4      | 4         | 7.55%   |
| 1      | 3         | 5.66%   |
| 9      | 2         | 3.77%   |
| 2      | 2         | 3.77%   |
| 36     | 1         | 1.89%   |
| 17     | 1         | 1.89%   |
| 14     | 1         | 1.89%   |
| 10     | 1         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 100%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 46        | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Moscow      | 41        | 89.13%  |
| Chelyabinsk | 3         | 6.52%   |
| Perm        | 2         | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Intel               | 19        | 55     | 21.84%  |
| Samsung Electronics | 18        | 75     | 20.69%  |
| Seagate             | 15        | 25     | 17.24%  |
| Micron Technology   | 10        | 41     | 11.49%  |
| Toshiba             | 8         | 69     | 9.2%    |
| HGST                | 5         | 9      | 5.75%   |
| WDC                 | 2         | 3      | 2.3%    |
| SCST_BIO            | 2         | 6      | 2.3%    |
| Hitachi             | 2         | 5      | 2.3%    |
| VSTORAGE            | 1         | 1      | 1.15%   |
| Lenovo              | 1         | 14     | 1.15%   |
| Kingston            | 1         | 1      | 1.15%   |
| Foxline             | 1         | 2      | 1.15%   |
| DGC                 | 1         | 6      | 1.15%   |
| DELLBOSS            | 1         | 1      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Seagate ST4000NM000A-2HZ100 4TB                              | 11        | 9.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB           | 11        | 9.02%   |
| Samsung MZ7L3480HBLT-00A07 480GB SSD                         | 10        | 8.2%    |
| Intel SSDSC2KG240G8 240GB                                    | 10        | 8.2%    |
| Intel SSDSC2KB960G8 960GB                                    | 10        | 8.2%    |
| Seagate ST4000NM0035-1V4107 4TB                              | 5         | 4.1%    |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller] 2TB | 5         | 4.1%    |
| Samsung MZ7L31T9HBLT-00A07 2TB SSD                           | 4         | 3.28%   |
| Micron 7300_MTFDHBE3T8TDF 4TB                                | 4         | 3.28%   |
| Intel PCIe Data Center SSD 1TB                               | 4         | 3.28%   |
| Toshiba MG04ACA400E 4TB                                      | 3         | 2.46%   |
| Toshiba MG03ACA100 1TB                                       | 2         | 1.64%   |
| Toshiba HDWD130 3TB                                          | 2         | 1.64%   |
| Micron 5300_MTFDDAK480TDS 480GB SSD                          | 2         | 1.64%   |
| Micron 5200_MTFDDAK480TDN 480GB SSD                          | 2         | 1.64%   |
| Micron 5100_MTFDDAK960TCB 960GB SSD                          | 2         | 1.64%   |
| Micron 1100_MTFDDAK512TBN 512GB SSD                          | 2         | 1.64%   |
| WDC WD4002FYYZ-01B7CB1 4TB                                   | 1         | 0.82%   |
| WDC WD1003FBYZ-010FB0 1TB                                    | 1         | 0.82%   |
| VSTORAGE VSTOR-DISK 5.4TB                                    | 1         | 0.82%   |
| Toshiba XG6 NVMe SSD Controller 512GB                        | 1         | 0.82%   |
| Toshiba MG03SCA100 1TB                                       | 1         | 0.82%   |
| Toshiba KPM5XVUG480G 480GB                                   | 1         | 0.82%   |
| Toshiba AL15SEB24EQY 2TB                                     | 1         | 0.82%   |
| Toshiba AL15SEB24EQY 2.4TB                                   | 1         | 0.82%   |
| Seagate ST1200MM0099 1.2TB                                   | 1         | 0.82%   |
| SCST_BIO LD4 4TB                                             | 1         | 0.82%   |
| SCST_BIO LD33 1TB                                            | 1         | 0.82%   |
| SCST_BIO LD3 1TB                                             | 1         | 0.82%   |
| SCST_BIO LD22 1TB                                            | 1         | 0.82%   |
| Samsung SSD 850 PRO 512GB                                    | 1         | 0.82%   |
| Samsung MZ7LM960HMJP0D3 960GB                                | 1         | 0.82%   |
| Samsung MZ7LH240HAHQ-00005 240GB SSD                         | 1         | 0.82%   |
| Micron MTFDDAK480TDN 480GB                                   | 1         | 0.82%   |
| Micron 7400_MTFDKBA480TDZ 480GB                              | 1         | 0.82%   |
| Micron 5300_MTFDDAK7T6TDS 8TB SSD                            | 1         | 0.82%   |
| Lenovo ST600MM0009 600GB                                     | 1         | 0.82%   |
| Lenovo MZILS400HEGRV3 400GB                                  | 1         | 0.82%   |
| Kingston SEDC1000BM8240G 240GB                               | 1         | 0.82%   |
| Hitachi HUC106060CSS600 600GB                                | 1         | 0.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 15        | 25     | 40.54%  |
| Toshiba  | 7         | 63     | 18.92%  |
| HGST     | 5         | 9      | 13.51%  |
| WDC      | 2         | 3      | 5.41%   |
| SCST_BIO | 2         | 6      | 5.41%   |
| Hitachi  | 2         | 5      | 5.41%   |
| VSTORAGE | 1         | 1      | 2.7%    |
| Lenovo   | 1         | 10     | 2.7%    |
| DGC      | 1         | 6      | 2.7%    |
| DELLBOSS | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 44     | 44.74%  |
| Intel               | 10        | 32     | 26.32%  |
| Micron Technology   | 9         | 20     | 23.68%  |
| Lenovo              | 1         | 4      | 2.63%   |
| Foxline             | 1         | 2      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 36        | 102    | 37.89%  |
| HDD     | 30        | 129    | 31.58%  |
| NVMe    | 27        | 77     | 28.42%  |
| Unknown | 2         | 5      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 218    | 57.69%  |
| NVMe | 27        | 77     | 34.62%  |
| SAS  | 6         | 18     | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 72     | 35.8%   |
| 3.01-4.0   | 21        | 51     | 25.93%  |
| 0.51-1.0   | 20        | 58     | 24.69%  |
| 1.01-2.0   | 6         | 7      | 7.41%   |
| 2.01-3.0   | 3         | 39     | 3.7%    |
| 4.01-10.0  | 2         | 4      | 2.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 21        | 40.38%  |
| More than 3000 | 14        | 26.92%  |
| 2001-3000      | 9         | 17.31%  |
| 251-500        | 6         | 11.54%  |
| 501-1000       | 2         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 26        | 47.27%  |
| 251-500        | 10        | 18.18%  |
| 21-50          | 10        | 18.18%  |
| 501-1000       | 3         | 5.45%   |
| 51-100         | 3         | 5.45%   |
| More than 3000 | 2         | 3.64%   |
| 2001-3000      | 1         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST4000NM0035-1V4107 4TB                | 1         | 1      | 33.33%  |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD | 1         | 3      | 33.33%  |
| Hitachi HDS721010CLA330 1TB                    | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 1         | 1      | 33.33%  |
| Micron Technology | 1         | 3      | 33.33%  |
| Hitachi           | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 3      | 33.33%  |

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
| Works    | 44        | 293    | 84.62%  |
| Detected | 5         | 15     | 9.62%   |
| Malfunc  | 3         | 5      | 5.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 36        | 40.45%  |
| ASMedia Technology           | 14        | 15.73%  |
| Samsung Electronics          | 11        | 12.36%  |
| AMD                          | 10        | 11.24%  |
| Broadcom / LSI               | 6         | 6.74%   |
| Micron Technology            | 5         | 5.62%   |
| LSI Logic / Symbios Logic    | 3         | 3.37%   |
| Toshiba America Info Systems | 1         | 1.12%   |
| Marvell Technology Group     | 1         | 1.12%   |
| Kingston Technology Company  | 1         | 1.12%   |
| Areca Technology             | 1         | 1.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                 | 24        | 18.9%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                  | 17        | 13.39%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 11        | 8.66%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 10        | 7.87%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 10        | 7.87%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 9         | 7.09%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                      | 5         | 3.94%   |
| Micron 7300 PRO NVMe SSD                                                      | 4         | 3.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 4         | 3.15%   |
| Intel PCIe Data Center SSD                                                    | 4         | 3.15%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 4         | 3.15%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 4         | 3.15%   |
| ASMedia 106x SATA/RAID Controller                                             | 4         | 3.15%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                          | 2         | 1.57%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                  | 2         | 1.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 0.79%   |
| Micron 7400 PRO NVMe SSD                                                      | 1         | 0.79%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1         | 0.79%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                       | 1         | 0.79%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 0.79%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1         | 0.79%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 1         | 0.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1         | 0.79%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                           | 1         | 0.79%   |
| Broadcom / LSI MegaRAID Tri-Mode SAS3508                                      | 1         | 0.79%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                | 1         | 0.79%   |
| Broadcom / LSI MegaRAID 12GSAS/PCIe Secure SAS39xx                            | 1         | 0.79%   |
| Areca ARC-1886 series PCIe 4.0 to NVMe/SAS/SATA 16/12/6Gb RAID Controller     | 1         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 46        | 49.46%  |
| NVMe | 27        | 29.03%  |
| RAID | 17        | 18.28%  |
| SAS  | 3         | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 78.26%  |
| AMD    | 10        | 21.74%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel Xeon Silver 4208 CPU @ 2.10GHz  | 10        | 21.74%  |
| AMD EPYC 7352 24-Core Processor       | 10        | 21.74%  |
| Intel Xeon Silver 4310 CPU @ 2.10GHz  | 4         | 8.7%    |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz   | 2         | 4.35%   |
| Intel Xeon CPU E3-1230 v6 @ 3.50GHz   | 2         | 4.35%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz   | 2         | 4.35%   |
| Intel Xeon Silver 4210R CPU @ 2.40GHz | 1         | 2.17%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz  | 1         | 2.17%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz  | 1         | 2.17%   |
| Intel Xeon Gold 6346 CPU @ 3.10GHz    | 1         | 2.17%   |
| Intel Xeon Gold 6338 CPU @ 2.00GHz    | 1         | 2.17%   |
| Intel Xeon Gold 6326 CPU @ 2.90GHz    | 1         | 2.17%   |
| Intel Xeon Gold 6248 CPU @ 2.50GHz    | 1         | 2.17%   |
| Intel Xeon Gold 6238R CPU @ 2.20GHz   | 1         | 2.17%   |
| Intel Xeon Gold 6140 CPU @ 2.30GHz    | 1         | 2.17%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz   | 1         | 2.17%   |
| Intel Xeon Gold 5220 CPU @ 2.20GHz    | 1         | 2.17%   |
| Intel Xeon Gold 5120 CPU @ 2.20GHz    | 1         | 2.17%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz    | 1         | 2.17%   |
| Intel Xeon CPU E5-2630 v4 @ 2.20GHz   | 1         | 2.17%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz   | 1         | 2.17%   |
| Intel Core i7-7700 CPU @ 3.60GHz      | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Xeon Silver | 17        | 36.96%  |
| AMD EPYC          | 10        | 21.74%  |
| Intel Xeon Gold   | 9         | 19.57%  |
| Intel Xeon        | 9         | 19.57%  |
| Intel Core i7     | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 24     | 10        | 21.74%  |
| 8      | 10        | 21.74%  |
| 20     | 5         | 10.87%  |
| 12     | 5         | 10.87%  |
| 4      | 5         | 10.87%  |
| 36     | 2         | 4.35%   |
| 32     | 2         | 4.35%   |
| 64     | 1         | 2.17%   |
| 56     | 1         | 2.17%   |
| 48     | 1         | 2.17%   |
| 40     | 1         | 2.17%   |
| 28     | 1         | 2.17%   |
| 16     | 1         | 2.17%   |
| 10     | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 65.22%  |
| 2      | 16        | 34.78%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 44        | 95.65%  |
| 1      | 2         | 4.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x50657    | 16        | 33.33%  |
| 0x08301055 | 10        | 20.83%  |
| 0x606a6    | 6         | 12.5%   |
| 0x406f1    | 4         | 8.33%   |
| 0x906e9    | 3         | 6.25%   |
| 0x50654    | 3         | 6.25%   |
| Unknown    | 3         | 6.25%   |
| 0x506e3    | 2         | 4.17%   |
| 0x206d7    | 1         | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Skylake     | 21        | 45.65%  |
| Zen 2       | 10        | 21.74%  |
| Unknown     | 7         | 15.22%  |
| Broadwell   | 4         | 8.7%    |
| KabyLake    | 3         | 6.52%   |
| SandyBridge | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| ASPEED Technology          | 39        | 81.25%  |
| Matrox Electronics Systems | 6         | 12.5%   |
| Nvidia                     | 2         | 4.17%   |
| Intel                      | 1         | 2.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                 | 39        | 79.59%  |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller | 4         | 8.16%   |
| Nvidia GV100GL [Tesla V100 PCIe 32GB]                                    | 1         | 2.04%   |
| Nvidia GA107GL [A2 / A16]                                                | 1         | 2.04%   |
| Nvidia GA100 [A100 PCIe 40GB]                                            | 1         | 2.04%   |
| Matrox Electronics Systems MGA G200eW WPCM450                            | 1         | 2.04%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)        | 1         | 2.04%   |
| Intel HD Graphics 630                                                    | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x ASPEED              | 38        | 82.61%  |
| 1 x Matrox              | 5         | 10.87%  |
| 2 x Nvidia + 1 x ASPEED | 1         | 2.17%   |
| Nvidia + Matrox         | 1         | 2.17%   |
| 1 x Intel               | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 46        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 97.83%  |
| 24.01-32.0 | 1         | 2.17%   |

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
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch              | 1         | 25%     |
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
| 0     | 43        | 91.49%  |
| 1     | 3         | 6.38%   |
| 2     | 1         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 45.36%  |
| Mellanox Technologies | 29        | 29.9%   |
| Broadcom              | 11        | 11.34%  |
| Emulex                | 5         | 5.15%   |
| Broadcom Limited      | 3         | 3.09%   |
| Insyde Software       | 2         | 2.06%   |
| Dell                  | 2         | 2.06%   |
| IBM                   | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Mellanox MT27700 Family [ConnectX-4]                                          | 13        | 12.75%  |
| Intel I210 Gigabit Network Connection                                         | 12        | 11.76%  |
| Intel Ethernet Controller E810-XXV for SFP                                    | 11        | 10.78%  |
| Intel Ethernet Connection X722 for 10GbE backplane                            | 10        | 9.8%    |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller         | 10        | 9.8%    |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 8         | 7.84%   |
| Mellanox MT27800 Family [ConnectX-5]                                          | 7         | 6.86%   |
| Intel I350 Gigabit Network Connection                                         | 7         | 6.86%   |
| Emulex OneConnect NIC (Skyhawk)                                               | 5         | 4.9%    |
| Broadcom Limited BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 3         | 2.94%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 1.96%   |
| Insyde Software RNDIS/Ethernet Gadget                                         | 2         | 1.96%   |
| Dell iDRAC Virtual NIC                                                        | 2         | 1.96%   |
| Broadcom Limited NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 2         | 1.96%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1         | 0.98%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 1         | 0.98%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.98%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1         | 0.98%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.98%   |
| IBM XClarity Controller                                                       | 1         | 0.98%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.98%   |

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
| Intel                 | 44        | 49.44%  |
| Mellanox Technologies | 21        | 23.6%   |
| Broadcom              | 11        | 12.36%  |
| Emulex                | 5         | 5.62%   |
| Broadcom Limited      | 3         | 3.37%   |
| Insyde Software       | 2         | 2.25%   |
| Dell                  | 2         | 2.25%   |
| IBM                   | 1         | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I210 Gigabit Network Connection                                         | 12        | 12.77%  |
| Intel Ethernet Controller E810-XXV for SFP                                    | 11        | 11.7%   |
| Intel Ethernet Connection X722 for 10GbE backplane                            | 10        | 10.64%  |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller         | 10        | 10.64%  |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 8         | 8.51%   |
| Mellanox MT27800 Family [ConnectX-5]                                          | 7         | 7.45%   |
| Intel I350 Gigabit Network Connection                                         | 7         | 7.45%   |
| Mellanox MT27700 Family [ConnectX-4]                                          | 5         | 5.32%   |
| Emulex OneConnect NIC (Skyhawk)                                               | 5         | 5.32%   |
| Broadcom Limited BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 3         | 3.19%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 2.13%   |
| Insyde Software RNDIS/Ethernet Gadget                                         | 2         | 2.13%   |
| Dell iDRAC Virtual NIC                                                        | 2         | 2.13%   |
| Broadcom Limited NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 2         | 2.13%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1         | 1.06%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 1         | 1.06%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 1.06%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1         | 1.06%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.06%   |
| IBM XClarity Controller                                                       | 1         | 1.06%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 82.14%  |
| Unknown  | 10        | 17.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 42        | 97.67%  |
| Unknown  | 1         | 2.33%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 6     | 15        | 31.25%  |
| 2     | 14        | 29.17%  |
| 4     | 12        | 25%     |
| 3     | 4         | 8.33%   |
| 8     | 1         | 2.08%   |
| 5     | 1         | 2.08%   |
| 1     | 1         | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 100%    |

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
| Samsung Electronics | 21        | 43.75%  |
| Micron Technology   | 14        | 29.17%  |
| SK hynix            | 5         | 10.42%  |
| Nanya Technology    | 4         | 8.33%   |
| Kingston            | 4         | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M393A8G40BB4-CWE 64GB DIMM DDR4 3200MT/s   | 10        | 20.83%  |
| Micron RAM 36ASF4G72PZ-2G9E2 32GB DIMM DDR4 2933MT/s   | 10        | 20.83%  |
| Samsung RAM M393A2K40DB3-CWE 16GB DIMM DDR4 3200MT/s   | 4         | 8.33%   |
| Nanya RAM NT32GA72D4NBX3P-IX 32GB DIMM DDR4 2933MT/s   | 4         | 8.33%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s   | 2         | 4.17%   |
| Micron RAM 18ASF2G72AZ-2G3B1 16GB DIMM DDR4 2400MT/s   | 2         | 4.17%   |
| SK hynix RAM HMT42GR7MFR4C-PB 16GB DIMM DDR3 1600MT/s  | 1         | 2.08%   |
| SK hynix RAM HMA84GR7DJR4N-WM 32GB DIMM DDR4 2933MT/s  | 1         | 2.08%   |
| SK hynix RAM HMA84GR7CJR4N-VK 32GB DIMM DDR4 2666MT/s  | 1         | 2.08%   |
| SK hynix RAM HMA84GR7AFR4N-VK 32GB DIMM DDR4 2667MT/s  | 1         | 2.08%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2667MT/s  | 1         | 2.08%   |
| Samsung RAM M393A8G40AB2-CWE 64GB DIMM DDR4 3200MT/s   | 1         | 2.08%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s   | 1         | 2.08%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s   | 1         | 2.08%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s   | 1         | 2.08%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s   | 1         | 2.08%   |
| Micron RAM 18ASF2G72PDZ-2G6E1 16GB DIMM DDR4 2667MT/s  | 1         | 2.08%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s   | 1         | 2.08%   |
| Kingston RAM 9965742-055.B00G 32GB DIMM DDR4 3200MT/s  | 1         | 2.08%   |
| Kingston RAM 9965669-008.A03G 16GB DIMM DDR4 2134MT/s  | 1         | 2.08%   |
| Kingston RAM 9965640-016.A00G 32GB DIMM DDR4 2133MT/s  | 1         | 2.08%   |
| Kingston RAM 9965516-071.A00LF 16GB DIMM DDR3 1066MT/s | 1         | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 45        | 97.83%  |
| DDR3 | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| DIMM | 46        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 32768 | 24        | 52.17%  |
| 65536 | 11        | 23.91%  |
| 16384 | 11        | 23.91%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 18        | 38.3%   |
| 2933  | 15        | 31.91%  |
| 2400  | 5         | 10.64%  |
| 2667  | 3         | 6.38%   |
| 3466  | 1         | 2.13%   |
| 2666  | 1         | 2.13%   |
| 2134  | 1         | 2.13%   |
| 2133  | 1         | 2.13%   |
| 1600  | 1         | 2.13%   |
| 1066  | 1         | 2.13%   |

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
| 0     | 15        | 32.61%  |
| 4     | 14        | 30.43%  |
| 3     | 9         | 19.57%  |
| 2     | 4         | 8.7%    |
| 5     | 3         | 6.52%   |
| 1     | 1         | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 31        | 46.97%  |
| Unassigned class         | 30        | 45.45%  |
| Graphics card            | 4         | 6.06%   |
| Storage/raid             | 1         | 1.52%   |

