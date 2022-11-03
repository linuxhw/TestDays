Rocky Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 37

| Vendor        | Model               | Probe                                                      | Date         |
|---------------|---------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Crosshair V Formula | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| Gigabyte      | H81M-S2PV           | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| BESSTAR Te... | HM90                | [fd411132f6](https://linux-hardware.org/?probe=fd411132f6) | Oct 15, 2022 |
| ASUSTek       | M5A97 R2.0          | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| ASUSTek       | PRIME H570-PLUS     | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| ASUSTek       | PRIME B550M-K       | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| ASUSTek       | P8B WS              | [bd82f7708c](https://linux-hardware.org/?probe=bd82f7708c) | Sep 02, 2022 |
| Lenovo        | 1046 NO DPK         | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| ASUSTek       | PRIME B460M-A R2.0  | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| ASUSTek       | PRIME B365-PLUS     | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| Gigabyte      | 970A-UD3P           | [0d503b2789](https://linux-hardware.org/?probe=0d503b2789) | Jul 27, 2022 |
| Unknown       | X31_ICH7            | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | 0GWHMW A01          | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell          | 06CV2N A00          | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte      | G41MT-USB3          | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte      | G41MT-USB3          | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR           | Pocono BIOS.5.1     | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| Dell          | 0NK70N A03          | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Dell          | 0WN7Y6 A01          | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell          | 0PC5F7 A02          | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek       | PRIME B450-PLUS     | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| ASRock        | B450M Pro4          | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI           | Z97A GAMING 6       | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| AZW           | Gemini M            | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW           | Gemini M            | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google        | Panther             | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Gigabyte      | X570 AORUS ULTRA    | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte      | H87-D3H-CF          | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Dell          | 0N4YC8 A00          | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| ASUSTek       | PRIME B450M-A II    | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II    | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | P5Q DELUXE          | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo        | NOK                 | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Dell          | 0M5DCD A00          | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| ASUSTek       | PRIME TRX40-PRO S   | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell          | 0M5DCD A00          | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| HP            | 0B54h D             | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Rocky Linux 8.5 | 12       | 36.36%  |
| Rocky Linux 8.4 | 9        | 27.27%  |
| Rocky Linux 8.6 | 7        | 21.21%  |
| Rocky Linux 9.0 | 4        | 12.12%  |
| Rocky Linux 8.3 | 1        | 3.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 33       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64     | 6        | 18.18%  |
| 4.18.0-348.7.1.el8_5.x86_64      | 3        | 9.09%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 3        | 9.09%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2        | 6.06%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2        | 6.06%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2        | 6.06%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2        | 6.06%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2        | 6.06%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2        | 6.06%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1        | 3.03%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 1        | 3.03%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1        | 3.03%   |
| 4.18.0-372.9.1.el8.x86_64        | 1        | 3.03%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 1        | 3.03%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 1        | 3.03%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1        | 3.03%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 1        | 3.03%   |
| 4.18.0-240.22.1.el8.x86_64       | 1        | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 28       | 84.85%  |
| 5.14.0  | 4        | 12.12%  |
| 5.14.1  | 1        | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 28       | 84.85%  |
| 5.14    | 5        | 15.15%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 33       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 21       | 63.64%  |
| Unknown       | 5        | 15.15%  |
| KDE5          | 3        | 9.09%   |
| MATE          | 2        | 6.06%   |
| GNOME Classic | 2        | 6.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 15       | 45.45%  |
| Wayland | 15       | 45.45%  |
| Unknown | 3        | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 16       | 48.48%  |
| Unknown | 15       | 45.45%  |
| SDDM    | 2        | 6.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 20       | 60.61%  |
| en_IL | 3        | 9.09%   |
| ru_RU | 2        | 6.06%   |
| en_SG | 2        | 6.06%   |
| pl_PL | 1        | 3.03%   |
| ja_JP | 1        | 3.03%   |
| es_CO | 1        | 3.03%   |
| en_CA | 1        | 3.03%   |
| en_AU | 1        | 3.03%   |
| af_ZA | 1        | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 19       | 57.58%  |
| EFI  | 14       | 42.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 28       | 84.85%  |
| Ext4 | 5        | 15.15%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 14       | 42.42%  |
| Unknown | 10       | 30.3%   |
| MBR     | 9        | 27.27%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 78.79%  |
| Yes       | 7        | 21.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 93.94%  |
| Yes       | 2        | 6.06%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 33.33%  |
| Dell                | 7        | 21.21%  |
| Gigabyte Technology | 5        | 15.15%  |
| Lenovo              | 2        | 6.06%   |
| NCR                 | 1        | 3.03%   |
| MSI                 | 1        | 3.03%   |
| Hewlett-Packard     | 1        | 3.03%   |
| Google              | 1        | 3.03%   |
| BESSTAR Tech        | 1        | 3.03%   |
| AZW                 | 1        | 3.03%   |
| ASRock              | 1        | 3.03%   |
| Unknown             | 1        | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 9020                  | 2        | 6.06%   |
| NCR xxxx-xxxx-xxxx                  | 1        | 3.03%   |
| MSI MS-7917                         | 1        | 3.03%   |
| Lenovo ThinkStation P620 30E0S0PR00 | 1        | 3.03%   |
| Lenovo ThinkCentre M72e 36601Y8     | 1        | 3.03%   |
| HP Z600 Workstation                 | 1        | 3.03%   |
| Google Panther                      | 1        | 3.03%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 3.03%   |
| Gigabyte H87-D3H                    | 1        | 3.03%   |
| Gigabyte H81M-S2PV                  | 1        | 3.03%   |
| Gigabyte G41MT-USB3                 | 1        | 3.03%   |
| Gigabyte 970A-UD3P                  | 1        | 3.03%   |
| Dell Vostro 3681                    | 1        | 3.03%   |
| Dell Precision Tower 7810           | 1        | 3.03%   |
| Dell Precision T7610                | 1        | 3.03%   |
| Dell Precision T5610                | 1        | 3.03%   |
| Dell OptiPlex 390                   | 1        | 3.03%   |
| BESSTAR Tech HM90                   | 1        | 3.03%   |
| AZW Gemini M                        | 1        | 3.03%   |
| ASUS PRIME TRX40-PRO S              | 1        | 3.03%   |
| ASUS PRIME H570-PLUS                | 1        | 3.03%   |
| ASUS PRIME B550M-K                  | 1        | 3.03%   |
| ASUS PRIME B460M-A R2.0             | 1        | 3.03%   |
| ASUS PRIME B450M-A II               | 1        | 3.03%   |
| ASUS PRIME B450-PLUS                | 1        | 3.03%   |
| ASUS PRIME B365-PLUS                | 1        | 3.03%   |
| ASUS P8B WS                         | 1        | 3.03%   |
| ASUS P5Q DELUXE                     | 1        | 3.03%   |
| ASUS M5A97 R2.0                     | 1        | 3.03%   |
| ASUS Crosshair V Formula            | 1        | 3.03%   |
| ASRock B450M Pro4                   | 1        | 3.03%   |
| Unknown                             | 1        | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 7        | 21.21%  |
| Dell Precision      | 3        | 9.09%   |
| Dell OptiPlex       | 3        | 9.09%   |
| NCR xxxx-xxxx-xxxx  | 1        | 3.03%   |
| MSI MS-7917         | 1        | 3.03%   |
| Lenovo ThinkStation | 1        | 3.03%   |
| Lenovo ThinkCentre  | 1        | 3.03%   |
| HP Z600             | 1        | 3.03%   |
| Google Panther      | 1        | 3.03%   |
| Gigabyte X570       | 1        | 3.03%   |
| Gigabyte H87-D3H    | 1        | 3.03%   |
| Gigabyte H81M-S2PV  | 1        | 3.03%   |
| Gigabyte G41MT-USB3 | 1        | 3.03%   |
| Gigabyte 970A-UD3P  | 1        | 3.03%   |
| Dell Vostro         | 1        | 3.03%   |
| BESSTAR Tech HM90   | 1        | 3.03%   |
| AZW Gemini          | 1        | 3.03%   |
| ASUS P8B            | 1        | 3.03%   |
| ASUS P5Q            | 1        | 3.03%   |
| ASUS M5A97          | 1        | 3.03%   |
| ASUS Crosshair      | 1        | 3.03%   |
| ASRock B450M        | 1        | 3.03%   |
| Unknown             | 1        | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 5        | 15.15%  |
| 2013 | 5        | 15.15%  |
| 2021 | 4        | 12.12%  |
| 2011 | 4        | 12.12%  |
| 2015 | 3        | 9.09%   |
| 2014 | 3        | 9.09%   |
| 2019 | 2        | 6.06%   |
| 2018 | 2        | 6.06%   |
| 2012 | 2        | 6.06%   |
| 2008 | 2        | 6.06%   |
| 2010 | 1        | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 33       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 33       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 96.97%  |
| Yes  | 1        | 3.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 8        | 24.24%  |
| 16.01-24.0  | 6        | 18.18%  |
| 4.01-8.0    | 5        | 15.15%  |
| 8.01-16.0   | 5        | 15.15%  |
| 64.01-256.0 | 3        | 9.09%   |
| 3.01-4.0    | 2        | 6.06%   |
| 1.01-2.0    | 2        | 6.06%   |
| 24.01-32.0  | 1        | 3.03%   |
| 2.01-3.0    | 1        | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 10       | 30.3%   |
| 4.01-8.0  | 7        | 21.21%  |
| 3.01-4.0  | 6        | 18.18%  |
| 1.01-2.0  | 5        | 15.15%  |
| 8.01-16.0 | 2        | 6.06%   |
| 0.51-1.0  | 2        | 6.06%   |
| 0.01-0.5  | 1        | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 39.39%  |
| 2      | 9        | 27.27%  |
| 3      | 6        | 18.18%  |
| 4      | 3        | 9.09%   |
| 8      | 1        | 3.03%   |
| 5      | 1        | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 51.52%  |
| No        | 16       | 48.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 63.64%  |
| Yes       | 12       | 36.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 72.73%  |
| Yes       | 9        | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 7        | 21.21%  |
| Singapore    | 3        | 9.09%   |
| Israel       | 3        | 9.09%   |
| Russia       | 2        | 6.06%   |
| Germany      | 2        | 6.06%   |
| Australia    | 2        | 6.06%   |
| Sweden       | 1        | 3.03%   |
| South Korea  | 1        | 3.03%   |
| South Africa | 1        | 3.03%   |
| Portugal     | 1        | 3.03%   |
| Poland       | 1        | 3.03%   |
| Norway       | 1        | 3.03%   |
| Mexico       | 1        | 3.03%   |
| Japan        | 1        | 3.03%   |
| Italy        | 1        | 3.03%   |
| India        | 1        | 3.03%   |
| France       | 1        | 3.03%   |
| Czechia      | 1        | 3.03%   |
| Colombia     | 1        | 3.03%   |
| Canada       | 1        | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Singapore              | 3        | 9.09%   |
| Haifa                  | 2        | 6.06%   |
| Waltham                | 1        | 3.03%   |
| Toronto                | 1        | 3.03%   |
| Tlaxcala City          | 1        | 3.03%   |
| St Petersburg          | 1        | 3.03%   |
| Sobral de Monte Agraco | 1        | 3.03%   |
| Rehovot                | 1        | 3.03%   |
| Prague                 | 1        | 3.03%   |
| Paris                  | 1        | 3.03%   |
| Ōtsu                  | 1        | 3.03%   |
| Oslo                   | 1        | 3.03%   |
| Moscow                 | 1        | 3.03%   |
| Monza                  | 1        | 3.03%   |
| Mequon                 | 1        | 3.03%   |
| Melbourne              | 1        | 3.03%   |
| Lebanon                | 1        | 3.03%   |
| Krakow                 | 1        | 3.03%   |
| Imphal                 | 1        | 3.03%   |
| Giessen                | 1        | 3.03%   |
| Fredericksburg         | 1        | 3.03%   |
| Florence               | 1        | 3.03%   |
| Enebyberg              | 1        | 3.03%   |
| Corvallis              | 1        | 3.03%   |
| Centurion              | 1        | 3.03%   |
| Burlington             | 1        | 3.03%   |
| Bucaramanga            | 1        | 3.03%   |
| Brisbane               | 1        | 3.03%   |
| Berlin                 | 1        | 3.03%   |
| Ansan-si               | 1        | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 18     | 18.87%  |
| Seagate             | 10       | 18     | 18.87%  |
| Toshiba             | 6        | 6      | 11.32%  |
| Samsung Electronics | 6        | 9      | 11.32%  |
| Hitachi             | 3        | 4      | 5.66%   |
| Crucial             | 3        | 3      | 5.66%   |
| SanDisk             | 2        | 2      | 3.77%   |
| HGST                | 2        | 2      | 3.77%   |
| Team                | 1        | 1      | 1.89%   |
| SK hynix            | 1        | 1      | 1.89%   |
| PNY                 | 1        | 1      | 1.89%   |
| Phison              | 1        | 1      | 1.89%   |
| Kingston            | 1        | 1      | 1.89%   |
| Intel               | 1        | 1      | 1.89%   |
| Gigabyte Technology | 1        | 1      | 1.89%   |
| Corsair             | 1        | 1      | 1.89%   |
| China               | 1        | 1      | 1.89%   |
| Apacer              | 1        | 1      | 1.89%   |
| A-DATA Technology   | 1        | 1      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 3        | 5%      |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 3.33%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD | 1        | 1.67%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 1.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1.67%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD   | 1        | 1.67%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1        | 1.67%   |
| WDC WD5000AUDX-63WNHY0 500GB     | 1        | 1.67%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 1.67%   |
| WDC WD5000AAKX-001CA0 500GB      | 1        | 1.67%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1        | 1.67%   |
| WDC WD2500AAJS-22VTA0 250GB      | 1        | 1.67%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 1.67%   |
| WDC WD2002FAEX-007BA0 2TB        | 1        | 1.67%   |
| WDC WD1001FALS-00J7B0 1TB        | 1        | 1.67%   |
| Toshiba THNSNJ128GCSU 128GB SSD  | 1        | 1.67%   |
| Toshiba MK1059GSM 1TB            | 1        | 1.67%   |
| Toshiba MG07ACA12TE 12TB         | 1        | 1.67%   |
| Toshiba MG04ACA400E 4TB          | 1        | 1.67%   |
| Toshiba DT01ACA100 1TB           | 1        | 1.67%   |
| Toshiba DT01ACA050 500GB         | 1        | 1.67%   |
| Team L5 LITE SSD 240GB           | 1        | 1.67%   |
| SK hynix SH920 2.5 7MM 256GB SSD | 1        | 1.67%   |
| Seagate ST9500420AS 500GB        | 1        | 1.67%   |
| Seagate ST9500325AS 500GB        | 1        | 1.67%   |
| Seagate ST9320325AS 320GB        | 1        | 1.67%   |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 1.67%   |
| Seagate ST3160318AS 160GB        | 1        | 1.67%   |
| Seagate ST2000DM008-2FR102 2TB   | 1        | 1.67%   |
| Seagate ST1000VX005-2EZ102 1TB   | 1        | 1.67%   |
| SanDisk SSD U110 16GB            | 1        | 1.67%   |
| SanDisk SDSSDH3500G 500GB        | 1        | 1.67%   |
| Samsung SSD 980 PRO 1TB          | 1        | 1.67%   |
| Samsung SSD 860 EVO 1TB          | 1        | 1.67%   |
| Samsung SP2004C 200GB            | 1        | 1.67%   |
| Samsung NVMe SSD Drive 500GB     | 1        | 1.67%   |
| Samsung MZVL21T0HCLR-00BL7 1TB   | 1        | 1.67%   |
| Samsung HD501LJ 500GB            | 1        | 1.67%   |
| Samsung HD103SJ 1TB              | 1        | 1.67%   |
| PNY CS900 120GB SSD              | 1        | 1.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 18     | 33.33%  |
| WDC                 | 8        | 12     | 26.67%  |
| Toshiba             | 5        | 5      | 16.67%  |
| Hitachi             | 3        | 4      | 10%     |
| Samsung Electronics | 2        | 3      | 6.67%   |
| HGST                | 2        | 2      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 6      | 18.75%  |
| SanDisk             | 2        | 2      | 12.5%   |
| Crucial             | 2        | 2      | 12.5%   |
| Toshiba             | 1        | 1      | 6.25%   |
| Team                | 1        | 1      | 6.25%   |
| SK hynix            | 1        | 1      | 6.25%   |
| Samsung Electronics | 1        | 1      | 6.25%   |
| PNY                 | 1        | 1      | 6.25%   |
| Gigabyte Technology | 1        | 1      | 6.25%   |
| Corsair             | 1        | 1      | 6.25%   |
| China               | 1        | 1      | 6.25%   |
| Apacer              | 1        | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 44     | 47.73%  |
| SSD  | 15       | 19     | 34.09%  |
| NVMe | 8        | 10     | 18.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 63     | 78.38%  |
| NVMe | 8        | 10     | 21.62%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 34     | 54.05%  |
| 0.51-1.0   | 9        | 16     | 24.32%  |
| 1.01-2.0   | 4        | 4      | 10.81%  |
| 3.01-4.0   | 2        | 7      | 5.41%   |
| 2.01-3.0   | 1        | 1      | 2.7%    |
| 10.01-20.0 | 1        | 1      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 21.21%  |
| 1001-2000      | 7        | 21.21%  |
| 501-1000       | 7        | 21.21%  |
| 251-500        | 5        | 15.15%  |
| More than 3000 | 3        | 9.09%   |
| 2001-3000      | 1        | 3.03%   |
| 1-20           | 1        | 3.03%   |
| 51-100         | 1        | 3.03%   |
| Unknown        | 1        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 9        | 27.27%  |
| 21-50          | 7        | 21.21%  |
| 51-100         | 5        | 15.15%  |
| 251-500        | 4        | 12.12%  |
| 501-1000       | 3        | 9.09%   |
| More than 3000 | 2        | 6.06%   |
| 101-250        | 1        | 3.03%   |
| 1001-2000      | 1        | 3.03%   |
| Unknown        | 1        | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB     | 1        | 4      | 14.29%  |
| Toshiba MK1059GSM 1TB         | 1        | 1      | 14.29%  |
| Seagate ST9500325AS 500GB     | 1        | 1      | 14.29%  |
| Seagate ST9320325AS 320GB     | 1        | 1      | 14.29%  |
| Hitachi HTS727575A9E364 752GB | 1        | 1      | 14.29%  |
| Hitachi HDS721010CLA632 1TB   | 1        | 1      | 14.29%  |
| Corsair Neutron SSD 64GB      | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 28.57%  |
| Hitachi | 2        | 2      | 28.57%  |
| WDC     | 1        | 4      | 14.29%  |
| Toshiba | 1        | 1      | 14.29%  |
| Corsair | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 33.33%  |
| Hitachi | 2        | 2      | 33.33%  |
| WDC     | 1        | 4      | 16.67%  |
| Toshiba | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 9      | 83.33%  |
| SSD  | 1        | 1      | 16.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST9500420AS 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 22       | 43     | 56.41%  |
| Detected | 10       | 19     | 25.64%  |
| Malfunc  | 6        | 10     | 15.38%  |
| Failed   | 1        | 1      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 22       | 47.83%  |
| AMD                         | 11       | 23.91%  |
| Samsung Electronics         | 2        | 4.35%   |
| Broadcom / LSI              | 2        | 4.35%   |
| ASMedia Technology          | 2        | 4.35%   |
| VIA Technologies            | 1        | 2.17%   |
| Realtek Semiconductor       | 1        | 2.17%   |
| Phison Electronics          | 1        | 2.17%   |
| Micron/Crucial Technology   | 1        | 2.17%   |
| Marvell Technology Group    | 1        | 2.17%   |
| Kingston Technology Company | 1        | 2.17%   |
| Adaptec                     | 1        | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 10.53%  |
| Intel SATA Controller [RAID mode]                                                       | 3        | 5.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 5.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 5.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 3.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.51%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 3.51%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 3.51%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.75%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 1.75%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.75%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.75%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.75%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 1.75%   |
| Intel PCIe Data Center SSD                                                              | 1        | 1.75%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 1.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.75%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 1.75%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1        | 1.75%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.75%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.75%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.75%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 1.75%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.75%   |
| AMD RAID Bottom Device                                                                  | 1        | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.75%   |
| Adaptec ASC-39320A U320                                                                 | 1        | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 48.94%  |
| NVMe | 8        | 17.02%  |
| IDE  | 7        | 14.89%  |
| RAID | 6        | 12.77%  |
| SAS  | 2        | 4.26%   |
| SCSI | 1        | 2.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 22       | 66.67%  |
| AMD    | 11       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 6.06%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 3.03%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1        | 3.03%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 3.03%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1        | 3.03%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 3.03%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 3.03%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 3.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 3.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 3.03%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 3.03%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 3.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 3.03%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 3.03%   |
| Intel Core i5-10600KF CPU @ 4.10GHz            | 1        | 3.03%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 3.03%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 3.03%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1        | 3.03%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 3.03%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1        | 3.03%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz         | 1        | 3.03%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores     | 1        | 3.03%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 3.03%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 3.03%   |
| AMD Ryzen 9 4900H with Radeon Graphics         | 1        | 3.03%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics     | 1        | 3.03%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 3.03%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 3.03%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 3.03%   |
| AMD Phenom II X6 1100T Processor               | 1        | 3.03%   |
| AMD FX-8350 Eight-Core Processor               | 1        | 3.03%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 6        | 18.18%  |
| Intel Xeon              | 4        | 12.12%  |
| Intel Core i5           | 4        | 12.12%  |
| Intel Core i3           | 2        | 6.06%   |
| Intel Celeron           | 2        | 6.06%   |
| AMD Ryzen Threadripper  | 2        | 6.06%   |
| AMD Ryzen 9             | 2        | 6.06%   |
| AMD FX                  | 2        | 6.06%   |
| Other                   | 1        | 3.03%   |
| Intel Pentium Dual-Core | 1        | 3.03%   |
| Intel Pentium Dual      | 1        | 3.03%   |
| Intel Core 2 Quad       | 1        | 3.03%   |
| AMD Ryzen 7 PRO         | 1        | 3.03%   |
| AMD Ryzen 7             | 1        | 3.03%   |
| AMD Ryzen 5             | 1        | 3.03%   |
| AMD Ryzen 3             | 1        | 3.03%   |
| AMD Phenom II X6        | 1        | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 33.33%  |
| 8      | 7        | 21.21%  |
| 6      | 5        | 15.15%  |
| 2      | 5        | 15.15%  |
| 12     | 2        | 6.06%   |
| 24     | 1        | 3.03%   |
| 16     | 1        | 3.03%   |
| 3      | 1        | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 93.94%  |
| 2      | 2        | 6.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 66.67%  |
| 1      | 11       | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 33       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 4        | 12.12%  |
| 0xa0655    | 2        | 6.06%   |
| 0x306e4    | 2        | 6.06%   |
| 0x306a9    | 2        | 6.06%   |
| 0x206a7    | 2        | 6.06%   |
| 0x08600106 | 2        | 6.06%   |
| 0x06000852 | 2        | 6.06%   |
| 0xa0671    | 1        | 3.03%   |
| 0x906ed    | 1        | 3.03%   |
| 0x706a8    | 1        | 3.03%   |
| 0x6fd      | 1        | 3.03%   |
| 0x40651    | 1        | 3.03%   |
| 0x306f2    | 1        | 3.03%   |
| 0x206c2    | 1        | 3.03%   |
| 0x10677    | 1        | 3.03%   |
| 0x10676    | 1        | 3.03%   |
| 0x0a201009 | 1        | 3.03%   |
| 0x0870100a | 1        | 3.03%   |
| 0x0830104d | 1        | 3.03%   |
| 0x08301039 | 1        | 3.03%   |
| 0x08108109 | 1        | 3.03%   |
| 0x0800820d | 1        | 3.03%   |
| 0x010000dc | 1        | 3.03%   |
| Unknown    | 1        | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 7        | 21.21%  |
| Zen 2         | 5        | 15.15%  |
| IvyBridge     | 4        | 12.12%  |
| Zen+          | 2        | 6.06%   |
| SandyBridge   | 2        | 6.06%   |
| Piledriver    | 2        | 6.06%   |
| Penryn        | 2        | 6.06%   |
| CometLake     | 2        | 6.06%   |
| Zen 3         | 1        | 3.03%   |
| Westmere      | 1        | 3.03%   |
| KabyLake      | 1        | 3.03%   |
| K10           | 1        | 3.03%   |
| Icelake       | 1        | 3.03%   |
| Goldmont plus | 1        | 3.03%   |
| Core          | 1        | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 14       | 41.18%  |
| Intel  | 13       | 38.24%  |
| AMD    | 7        | 20.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 5.88%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 5.88%   |
| AMD Renoir                                                                  | 2        | 5.88%   |
| Nvidia TU117GL [T600]                                                       | 1        | 2.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.94%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 2.94%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 2.94%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 2.94%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.94%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 2.94%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 2.94%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 2.94%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 2.94%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 2.94%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 2.94%   |
| Nvidia GA102GL [RTX A6000]                                                  | 1        | 2.94%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 2.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.94%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 2.94%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 2.94%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 2.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 2.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.94%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 2.94%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 13       | 39.39%  |
| 1 x Intel      | 12       | 36.36%  |
| 1 x AMD        | 7        | 21.21%  |
| Intel + Nvidia | 1        | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 24       | 72.73%  |
| Proprietary | 6        | 18.18%  |
| Unknown     | 3        | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 42.42%  |
| 1.01-2.0   | 5        | 15.15%  |
| 0.01-0.5   | 5        | 15.15%  |
| 0.51-1.0   | 3        | 9.09%   |
| 7.01-8.0   | 2        | 6.06%   |
| 32.01-64.0 | 1        | 3.03%   |
| 5.01-6.0   | 1        | 3.03%   |
| 3.01-4.0   | 1        | 3.03%   |
| 8.01-16.0  | 1        | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 7        | 24.14%  |
| Samsung Electronics  | 4        | 13.79%  |
| Iiyama               | 3        | 10.34%  |
| Goldstar             | 3        | 10.34%  |
| Philips              | 2        | 6.9%    |
| Acer                 | 2        | 6.9%    |
| Sony                 | 1        | 3.45%   |
| OEM                  | 1        | 3.45%   |
| Hewlett-Packard      | 1        | 3.45%   |
| HCL                  | 1        | 3.45%   |
| Eizo                 | 1        | 3.45%   |
| ASUSTek Computer     | 1        | 3.45%   |
| AOC                  | 1        | 3.45%   |
| Ancor Communications | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Sony LG TV SNY045B 1920x540                                         | 1        | 3.23%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch   | 1        | 3.23%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch   | 1        | 3.23%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch | 1        | 3.23%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch  | 1        | 3.23%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch             | 1        | 3.23%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch            | 1        | 3.23%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                     | 1        | 3.23%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                | 1        | 3.23%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                | 1        | 3.23%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                 | 1        | 3.23%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch        | 1        | 3.23%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                 | 1        | 3.23%   |
| Goldstar WFHD GSM7748 2560x1080 798x334mm 34.1-inch                 | 1        | 3.23%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch            | 1        | 3.23%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1        | 3.23%   |
| Goldstar LG ULTRAWIDE GSM7770 2560x1080 800x340mm 34.2-inch         | 1        | 3.23%   |
| Eizo CG247X ENC2801 1920x1200 520x330mm 24.2-inch                   | 1        | 3.23%   |
| Dell P2416D DELA0C4 2560x1440 530x300mm 24.0-inch                   | 1        | 3.23%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                    | 1        | 3.23%   |
| Dell P1913 DELA088 1440x900 410x260mm 19.1-inch                     | 1        | 3.23%   |
| Dell LCD Monitor U2414H 3840x1080                                   | 1        | 3.23%   |
| Dell LCD Monitor U2414H                                             | 1        | 3.23%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                   | 1        | 3.23%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                   | 1        | 3.23%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                   | 1        | 3.23%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch        | 1        | 3.23%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                     | 1        | 3.23%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch    | 1        | 3.23%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                     | 1        | 3.23%   |
| Acer G277HL ACR03FB 1920x1080 598x336mm 27.0-inch                   | 1        | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 10       | 33.33%  |
| 3840x2160 (4K)    | 2        | 6.67%   |
| 3840x1080         | 2        | 6.67%   |
| 1920x540          | 2        | 6.67%   |
| 1920x1200 (WUXGA) | 2        | 6.67%   |
| 1600x900 (HD+)    | 2        | 6.67%   |
| 1440x900 (WXGA+)  | 2        | 6.67%   |
| 1280x1024 (SXGA)  | 2        | 6.67%   |
| 3440x1440         | 1        | 3.33%   |
| 2560x1440 (QHD)   | 1        | 3.33%   |
| 2560x1080         | 1        | 3.33%   |
| 1366x768 (WXGA)   | 1        | 3.33%   |
| 1280x768          | 1        | 3.33%   |
| Unknown           | 1        | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 20.69%  |
| 27      | 5        | 17.24%  |
| 23      | 3        | 10.34%  |
| 19      | 3        | 10.34%  |
| 34      | 2        | 6.9%    |
| 17      | 2        | 6.9%    |
| 65      | 1        | 3.45%   |
| 48      | 1        | 3.45%   |
| 40      | 1        | 3.45%   |
| 31      | 1        | 3.45%   |
| 28      | 1        | 3.45%   |
| 20      | 1        | 3.45%   |
| 18      | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 50%     |
| 401-500     | 5        | 17.86%  |
| 701-800     | 2        | 7.14%   |
| 301-350     | 2        | 7.14%   |
| 1001-1500   | 2        | 7.14%   |
| 801-900     | 1        | 3.57%   |
| 601-700     | 1        | 3.57%   |
| Unknown     | 1        | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 67.86%  |
| 16/10   | 3        | 10.71%  |
| 5/4     | 2        | 7.14%   |
| 32/9    | 1        | 3.57%   |
| 3/2     | 1        | 3.57%   |
| 21/9    | 1        | 3.57%   |
| Unknown | 1        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 24.14%  |
| 301-350        | 5        | 17.24%  |
| 151-200        | 4        | 13.79%  |
| 351-500        | 3        | 10.34%  |
| 141-150        | 3        | 10.34%  |
| 501-1000       | 3        | 10.34%  |
| 251-300        | 2        | 6.9%    |
| More than 1000 | 1        | 3.45%   |
| Unknown        | 1        | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 79.31%  |
| 1-50    | 2        | 6.9%    |
| 121-160 | 2        | 6.9%    |
| 161-240 | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 75.76%  |
| 0     | 5        | 15.15%  |
| 2     | 3        | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 18       | 37.5%   |
| Intel                     | 16       | 33.33%  |
| Ralink Technology         | 2        | 4.17%   |
| Qualcomm Atheros          | 2        | 4.17%   |
| Marvell Technology Group  | 2        | 4.17%   |
| Linksys                   | 2        | 4.17%   |
| Solarflare Communications | 1        | 2.08%   |
| Microsoft                 | 1        | 2.08%   |
| MediaTek                  | 1        | 2.08%   |
| BUFFALO                   | 1        | 2.08%   |
| Broadcom                  | 1        | 2.08%   |
| Aquantia                  | 1        | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 29.63%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 5.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                   | 2        | 3.7%    |
| Intel Wireless 3165                                               | 2        | 3.7%    |
| Intel I211 Gigabit Network Connection                             | 2        | 3.7%    |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.85%   |
| Realtek 802.11ac NIC                                              | 1        | 1.85%   |
| Ralink RT3071 Wireless Adapter                                    | 1        | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.85%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.85%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 1.85%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.85%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 1.85%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]    | 1        | 1.85%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.85%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.85%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.85%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.85%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.85%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.85%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]          | 1        | 1.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.85%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 3        | 20%     |
| Intel                 | 3        | 20%     |
| Ralink Technology     | 2        | 13.33%  |
| Qualcomm Atheros      | 2        | 13.33%  |
| Linksys               | 2        | 13.33%  |
| Microsoft             | 1        | 6.67%   |
| MediaTek              | 1        | 6.67%   |
| BUFFALO               | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 11.76%  |
| Ralink MT7601U Wireless Adapter                                | 2        | 11.76%  |
| Intel Wireless 3165                                            | 2        | 11.76%  |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 5.88%   |
| Realtek 802.11ac NIC                                           | 1        | 5.88%   |
| Ralink RT3071 Wireless Adapter                                 | 1        | 5.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 5.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 5.88%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1        | 5.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 5.88%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1        | 5.88%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1        | 5.88%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 5.88%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]       | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 17       | 47.22%  |
| Intel                     | 14       | 38.89%  |
| Marvell Technology Group  | 2        | 5.56%   |
| Solarflare Communications | 1        | 2.78%   |
| Broadcom                  | 1        | 2.78%   |
| Aquantia                  | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 43.24%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 8.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 8.11%   |
| Intel I211 Gigabit Network Connection                             | 2        | 5.41%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 2.7%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 2.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 2.7%    |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 2.7%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 2.7%    |
| Intel Ethernet Controller I225-V                                  | 1        | 2.7%    |
| Intel Ethernet Connection I217-V                                  | 1        | 2.7%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.7%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.7%    |
| Intel 82583V Gigabit Network Connection                           | 1        | 2.7%    |
| Intel 82574L Gigabit Network Connection                           | 1        | 2.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.7%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 73.33%  |
| WiFi     | 12       | 26.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 90.63%  |
| WiFi     | 3        | 9.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 66.67%  |
| 2     | 10       | 30.3%   |
| 3     | 1        | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 84.85%  |
| Yes  | 5        | 15.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 3        | 33.33%  |
| Cambridge Silicon Radio    | 2        | 22.22%  |
| MediaTek                   | 1        | 11.11%  |
| Integrated System Solution | 1        | 11.11%  |
| IMC Networks               | 1        | 11.11%  |
| Broadcom                   | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                    | 2        | 22.22%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 22.22%  |
| MediaTek Wireless_Device                              | 1        | 11.11%  |
| Intel AX200 Bluetooth                                 | 1        | 11.11%  |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 11.11%  |
| IMC Networks Bluetooth Device                         | 1        | 11.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 22       | 41.51%  |
| Nvidia              | 13       | 24.53%  |
| AMD                 | 12       | 22.64%  |
| C-Media Electronics | 3        | 5.66%   |
| Unknown             | 1        | 1.89%   |
| Nektar              | 1        | 1.89%   |
| ASUSTek Computer    | 1        | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 6.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 6.35%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 4.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 4.76%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 4.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 3.17%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 3.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 3.17%   |
| C-Media Electronics Anua Mic CM 900                                        | 2        | 3.17%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2        | 3.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 3.17%   |
| Unknown Realtek USB Audio Rear                                             | 1        | 1.59%   |
| Unknown Realtek USB Audio Front                                            | 1        | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.59%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.59%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1.59%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 1.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.59%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.59%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.59%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.59%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.59%   |
| Nektar Impact GX61                                                         | 1        | 1.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.59%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.59%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.59%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.59%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.59%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.59%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.59%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.59%   |
| ASUSTek Computer USB Audio                                                 | 1        | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.59%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 1.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 4        | 16%     |
| Samsung Electronics | 4        | 16%     |
| Kingston            | 4        | 16%     |
| G.Skill             | 4        | 16%     |
| Micron Technology   | 3        | 12%     |
| Corsair             | 3        | 12%     |
| SK hynix            | 1        | 4%      |
| Patriot             | 1        | 4%      |
| A-DATA Technology   | 1        | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 3.7%    |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 3.7%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s           | 1        | 3.7%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 1        | 3.7%    |
| Unknown RAM Module 1GB DIMM 667MT/s                      | 1        | 3.7%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 3.7%    |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s     | 1        | 3.7%    |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s      | 1        | 3.7%    |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s     | 1        | 3.7%    |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s     | 1        | 3.7%    |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s         | 1        | 3.7%    |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                 | 1        | 3.7%    |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s      | 1        | 3.7%    |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s       | 1        | 3.7%    |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s      | 1        | 3.7%    |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s  | 1        | 3.7%    |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s    | 1        | 3.7%    |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s    | 1        | 3.7%    |
| Kingston RAM 9905402-670.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 3.7%    |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3600MT/s      | 1        | 3.7%    |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s     | 1        | 3.7%    |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s       | 1        | 3.7%    |
| G.Skill RAM F3-12800CL10 8GB DIMM DDR3 1600MT/s          | 1        | 3.7%    |
| Corsair RAM CMX4GX3M2A1333C8 2GB DIMM DDR3 1333MT/s      | 1        | 3.7%    |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s     | 1        | 3.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 1        | 3.7%    |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s             | 1        | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 12       | 52.17%  |
| DDR3    | 9        | 39.13%  |
| DDR2    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 86.96%  |
| SODIMM | 2        | 8.7%    |
| RIMM   | 1        | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 36%     |
| 32768 | 4        | 16%     |
| 4096  | 4        | 16%     |
| 16384 | 3        | 12%     |
| 2048  | 3        | 12%     |
| 1024  | 2        | 8%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 6        | 25%     |
| 1600  | 3        | 12.5%   |
| 3600  | 2        | 8.33%   |
| 2400  | 2        | 8.33%   |
| 2133  | 2        | 8.33%   |
| 1333  | 2        | 8.33%   |
| 667   | 2        | 8.33%   |
| 3400  | 1        | 4.17%   |
| 2666  | 1        | 4.17%   |
| 2200  | 1        | 4.17%   |
| 1866  | 1        | 4.17%   |
| 1800  | 1        | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 66.67%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson XP-4100 Series    | 1        | 33.33%  |
| Seiko Epson Printer           | 1        | 33.33%  |
| Brother HL-2030 Laser Printer | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| HP OfficeJet 6110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 2        | 33.33%  |
| Huawei Technologies    | 1        | 16.67%  |
| Generalplus Technology | 1        | 16.67%  |
| Elgato Systems         | 1        | 16.67%  |
| 2M UVC CAMERA          | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech Webcam C270                | 1        | 16.67%  |
| Logitech HD Pro Webcam C920         | 1        | 16.67%  |
| Huawei HiCamera                     | 1        | 16.67%  |
| Generalplus GENERAL WEBCAM          | 1        | 16.67%  |
| Elgato Systems Elgato Facecam       | 1        | 16.67%  |
| 2M UVC CAMERA NexiGo N60 FHD Webcam | 1        | 16.67%  |

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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 22       | 66.67%  |
| 1     | 7        | 21.21%  |
| 2     | 4        | 12.12%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Net/wireless        | 5        | 38.46%  |
| Graphics card       | 2        | 15.38%  |
| Unassigned class    | 1        | 7.69%   |
| Storage/raid        | 1        | 7.69%   |
| Storage             | 1        | 7.69%   |
| Sound               | 1        | 7.69%   |
| Net/ethernet        | 1        | 7.69%   |
| Firewire controller | 1        | 7.69%   |

