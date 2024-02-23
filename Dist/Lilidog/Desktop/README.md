Lilidog - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Lilidog.

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

Total: 26

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | 1998                        | [b193235ba4](https://linux-hardware.org/?probe=b193235ba4) | Jan 17, 2024 |
| Dell      | 0M5DCD A00                  | [6f8ca5724f](https://linux-hardware.org/?probe=6f8ca5724f) | Aug 10, 2023 |
| Dell      | 0GM819                      | [744413006e](https://linux-hardware.org/?probe=744413006e) | Apr 20, 2023 |
| Unknown   | X79M2-Q                     | [d985b7fa11](https://linux-hardware.org/?probe=d985b7fa11) | Apr 05, 2023 |
| Foxconn   | NETBOX NT-425/525 Ver       | [dfb8c476f9](https://linux-hardware.org/?probe=dfb8c476f9) | Jan 21, 2023 |
| Lenovo    | 374F SDK0R32862 WIN 3258... | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell      | 0WMJ54 A01                  | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Dell      | 03NVJ6 A02                  | [a16b955eed](https://linux-hardware.org/?probe=a16b955eed) | Jan 15, 2023 |
| ASUSTek   | PRIME H510M-K               | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| HP        | 805B                        | [111fb196ff](https://linux-hardware.org/?probe=111fb196ff) | Nov 16, 2022 |
| Dell      | 0DF42J A00                  | [52e8355edf](https://linux-hardware.org/?probe=52e8355edf) | Nov 12, 2022 |
| Biostar   | A320MH                      | [d01d91204f](https://linux-hardware.org/?probe=d01d91204f) | Oct 27, 2022 |
| Biostar   | A320MH                      | [768dff7065](https://linux-hardware.org/?probe=768dff7065) | Oct 27, 2022 |
| Gigabyte  | B365M DS3H                  | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Gigabyte  | B450 AORUS PRO-CF           | [4bc8ad9e5f](https://linux-hardware.org/?probe=4bc8ad9e5f) | Oct 12, 2022 |
| Lenovo    | 374F SDK0R32862 WIN 3258... | [b30ac8d979](https://linux-hardware.org/?probe=b30ac8d979) | Oct 05, 2022 |
| Dell      | 0GM819                      | [7778e245a9](https://linux-hardware.org/?probe=7778e245a9) | Sep 06, 2022 |
| HP        | 805B                        | [602a9470ab](https://linux-hardware.org/?probe=602a9470ab) | Aug 22, 2022 |
| ASUSTek   | H110M-A/DP                  | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| ASUSTek   | H110M-A/DP                  | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Gigabyte  | MZBAYAP-00                  | [f8a734d114](https://linux-hardware.org/?probe=f8a734d114) | Jun 20, 2022 |
| Gigabyte  | MZBAYAP-00                  | [8fb623d313](https://linux-hardware.org/?probe=8fb623d313) | Jun 17, 2022 |
| eMachines | EL1352                      | [562e729c18](https://linux-hardware.org/?probe=562e729c18) | May 15, 2022 |
| HP        | 212B                        | [d6deb6ed52](https://linux-hardware.org/?probe=d6deb6ed52) | May 04, 2022 |
| HP        | 21EF                        | [f619d0dfc0](https://linux-hardware.org/?probe=f619d0dfc0) | Apr 14, 2022 |
| Dell      | 0HJ054                      | [77ae3bc631](https://linux-hardware.org/?probe=77ae3bc631) | Apr 11, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Lilidog 22 | 17       | 89.47%  |
| Lilidog 23 | 2        | 10.53%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Lilidog | 19       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.10.0-18-amd64           | 3        | 13.64%  |
| 5.10.0-13-amd64           | 3        | 13.64%  |
| 6.0.8-x64v1-xanmod1       | 2        | 9.09%   |
| 6.5.0-0.deb12.4-amd64     | 1        | 4.55%   |
| 6.2.11-x64v1-xanmod1      | 1        | 4.55%   |
| 6.1.0-7.2-liquorix-amd64  | 1        | 4.55%   |
| 6.1.0-10-amd64            | 1        | 4.55%   |
| 6.0.0-5-amd64             | 1        | 4.55%   |
| 6.0.0-0.deb11.6-amd64     | 1        | 4.55%   |
| 5.19.0-7.1-liquorix-amd64 | 1        | 4.55%   |
| 5.19.0-0.deb11.2-amd64    | 1        | 4.55%   |
| 5.18.0-1-amd64            | 1        | 4.55%   |
| 5.10.0-21-amd64           | 1        | 4.55%   |
| 5.10.0-20-amd64           | 1        | 4.55%   |
| 5.10.0-19-amd64           | 1        | 4.55%   |
| 5.10.0-16-amd64           | 1        | 4.55%   |
| 5.10.0-14-amd64           | 1        | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 11       | 50%     |
| 6.1.0   | 2        | 9.09%   |
| 6.0.8   | 2        | 9.09%   |
| 6.0.0   | 2        | 9.09%   |
| 5.19.0  | 2        | 9.09%   |
| 6.5.0   | 1        | 4.55%   |
| 6.2.11  | 1        | 4.55%   |
| 5.18.0  | 1        | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 11       | 50%     |
| 6.0     | 4        | 18.18%  |
| 6.1     | 2        | 9.09%   |
| 5.19    | 2        | 9.09%   |
| 6.5     | 1        | 4.55%   |
| 6.2     | 1        | 4.55%   |
| 5.18    | 1        | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 19       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| lightdm-xsession | 18       | 90%     |
| openbox          | 2        | 10%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 19       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 19       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 84.21%  |
| ru_RU | 1        | 5.26%   |
| es_MX | 1        | 5.26%   |
| en_GB | 1        | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 10       | 52.63%  |
| BIOS | 9        | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 15       | 75%     |
| Overlay | 4        | 20%     |
| Btrfs   | 1        | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 15       | 78.95%  |
| MBR  | 4        | 21.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 57.89%  |
| Yes       | 8        | 42.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 84.21%  |
| Yes       | 3        | 15.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 6        | 31.58%  |
| Hewlett-Packard     | 3        | 15.79%  |
| Gigabyte Technology | 3        | 15.79%  |
| ASUSTek Computer    | 2        | 10.53%  |
| Lenovo              | 1        | 5.26%   |
| Foxconn             | 1        | 5.26%   |
| eMachines           | 1        | 5.26%   |
| Biostar             | 1        | 5.26%   |
| Unknown             | 1        | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Lenovo Legion T7 34IMZ5 90Q800AJMH | 1        | 5.26%   |
| HP t520 Flexible Series TC         | 1        | 5.26%   |
| HP EliteDesk 800 G1 SFF            | 1        | 5.26%   |
| HP EliteDesk 705 G2 MINI           | 1        | 5.26%   |
| Gigabyte PERSONAL COMPUTER         | 1        | 5.26%   |
| Gigabyte B450 AORUS PRO            | 1        | 5.26%   |
| Gigabyte B365M DS3H                | 1        | 5.26%   |
| Foxconn NETBOX NT-425/525          | 1        | 5.26%   |
| eMachines EL1352                   | 1        | 5.26%   |
| Dell XPS 8930                      | 1        | 5.26%   |
| Dell OptiPlex 780                  | 1        | 5.26%   |
| Dell OptiPlex 755                  | 1        | 5.26%   |
| Dell OptiPlex 390                  | 1        | 5.26%   |
| Dell OptiPlex 3020                 | 1        | 5.26%   |
| Dell DM051                         | 1        | 5.26%   |
| Biostar A320MH                     | 1        | 5.26%   |
| ASUS PRIME H510M-K                 | 1        | 5.26%   |
| ASUS H110M-A/DP                    | 1        | 5.26%   |
| Unknown                            | 1        | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Dell OptiPlex     | 4        | 21.05%  |
| HP EliteDesk      | 2        | 10.53%  |
| Lenovo Legion     | 1        | 5.26%   |
| HP t520           | 1        | 5.26%   |
| Gigabyte PERSONAL | 1        | 5.26%   |
| Gigabyte B450     | 1        | 5.26%   |
| Gigabyte B365M    | 1        | 5.26%   |
| Foxconn NETBOX    | 1        | 5.26%   |
| eMachines EL1352  | 1        | 5.26%   |
| Dell XPS          | 1        | 5.26%   |
| Dell DM051        | 1        | 5.26%   |
| Biostar A320MH    | 1        | 5.26%   |
| ASUS PRIME        | 1        | 5.26%   |
| ASUS H110M-A      | 1        | 5.26%   |
| Unknown           | 1        | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 3        | 15.79%  |
| 2018 | 3        | 15.79%  |
| 2010 | 3        | 15.79%  |
| 2021 | 2        | 10.53%  |
| 2014 | 2        | 10.53%  |
| 2017 | 1        | 5.26%   |
| 2015 | 1        | 5.26%   |
| 2013 | 1        | 5.26%   |
| 2011 | 1        | 5.26%   |
| 2007 | 1        | 5.26%   |
| 2006 | 1        | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 19       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 19       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 8        | 42.11%  |
| 16.01-24.0 | 3        | 15.79%  |
| 3.01-4.0   | 2        | 10.53%  |
| 2.01-3.0   | 2        | 10.53%  |
| 8.01-16.0  | 2        | 10.53%  |
| 32.01-64.0 | 1        | 5.26%   |
| 0.51-1.0   | 1        | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 12       | 63.16%  |
| 1.01-2.0  | 3        | 15.79%  |
| 0.01-0.5  | 2        | 10.53%  |
| 2.01-3.0  | 1        | 5.26%   |
| 8.01-16.0 | 1        | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 42.11%  |
| 1      | 8        | 42.11%  |
| 3      | 3        | 15.79%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 65%     |
| Yes       | 7        | 35%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 52.63%  |
| Yes       | 9        | 47.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 84.21%  |
| Yes       | 3        | 15.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 36.84%  |
| UK          | 2        | 10.53%  |
| Taiwan      | 1        | 5.26%   |
| Russia      | 1        | 5.26%   |
| Poland      | 1        | 5.26%   |
| Netherlands | 1        | 5.26%   |
| Mexico      | 1        | 5.26%   |
| Italy       | 1        | 5.26%   |
| Indonesia   | 1        | 5.26%   |
| Germany     | 1        | 5.26%   |
| Austria     | 1        | 5.26%   |
| Argentina   | 1        | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Travelers Rest              | 2        | 9.52%   |
| Fayetteville                | 2        | 9.52%   |
| Zapopan                     | 1        | 4.76%   |
| Workum                      | 1        | 4.76%   |
| Vienna                      | 1        | 4.76%   |
| St Petersburg               | 1        | 4.76%   |
| San Nicolás de los Arroyos | 1        | 4.76%   |
| Rzeszów                    | 1        | 4.76%   |
| Rome                        | 1        | 4.76%   |
| Palembang                   | 1        | 4.76%   |
| Memphis                     | 1        | 4.76%   |
| Langelsheim                 | 1        | 4.76%   |
| Idsegahuizum                | 1        | 4.76%   |
| Golden Valley               | 1        | 4.76%   |
| Fongshan District           | 1        | 4.76%   |
| Conway                      | 1        | 4.76%   |
| Charlotte                   | 1        | 4.76%   |
| Bradford                    | 1        | 4.76%   |
| Barnsley                    | 1        | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 10     | 30%     |
| WDC                 | 5        | 9      | 16.67%  |
| Kingston            | 4        | 5      | 13.33%  |
| SanDisk             | 2        | 2      | 6.67%   |
| Crucial             | 2        | 2      | 6.67%   |
| Toshiba             | 1        | 1      | 3.33%   |
| SK hynix            | 1        | 1      | 3.33%   |
| Silicon Motion      | 1        | 1      | 3.33%   |
| Samsung Electronics | 1        | 1      | 3.33%   |
| OWC                 | 1        | 2      | 3.33%   |
| Intel               | 1        | 1      | 3.33%   |
| Hitachi             | 1        | 1      | 3.33%   |
| A-DATA Technology   | 1        | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB       | 2        | 6.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1        | 3.33%   |
| WDC WD800JD-75MSA3 80GB              | 1        | 3.33%   |
| WDC WD50 00AAKX-08U6AA0 500GB        | 1        | 3.33%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1        | 3.33%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1        | 3.33%   |
| Toshiba MQ01ABF050 500GB             | 1        | 3.33%   |
| SK hynix C2S3T/480G 480GB SSD        | 1        | 3.33%   |
| Silicon Motion NE-128 128GB          | 1        | 3.33%   |
| Seagate ST500VM000-1SD101 500GB      | 1        | 3.33%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 3.33%   |
| Seagate ST3160023AS 160GB            | 1        | 3.33%   |
| Seagate ST2000DX002-2DV164 2TB       | 1        | 3.33%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 3.33%   |
| Seagate Expansion 1TB                | 1        | 3.33%   |
| Seagate BUP Slim BK 1TB              | 1        | 3.33%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD   | 1        | 3.33%   |
| SanDisk SD7SB6S128G1122 128GB SSD    | 1        | 3.33%   |
| Samsung MZ7TE128HMGR-000L1 128GB SSD | 1        | 3.33%   |
| OWC Mercury EXTREME Pro 6G SSD       | 1        | 3.33%   |
| Kingston SV300S37A120G 120GB SSD     | 1        | 3.33%   |
| Kingston SUV500M8120G 120GB SSD      | 1        | 3.33%   |
| Kingston SHSS37A240G 240GB SSD       | 1        | 3.33%   |
| Kingston SA400S37240G 240GB SSD      | 1        | 3.33%   |
| Intel MEMPEK1W032GA 32GB             | 1        | 3.33%   |
| Hitachi HDS721016CLA382 160GB        | 1        | 3.33%   |
| Crucial CT250MX500SSD1 250GB         | 1        | 3.33%   |
| Crucial CT240BX500SSD1 240GB         | 1        | 3.33%   |
| A-DATA SU800 256GB SSD               | 1        | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 10     | 64.29%  |
| WDC     | 3        | 3      | 21.43%  |
| Toshiba | 1        | 1      | 7.14%   |
| Hitachi | 1        | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 4        | 5      | 30.77%  |
| SanDisk             | 2        | 2      | 15.38%  |
| Crucial             | 2        | 2      | 15.38%  |
| WDC                 | 1        | 2      | 7.69%   |
| SK hynix            | 1        | 1      | 7.69%   |
| Samsung Electronics | 1        | 1      | 7.69%   |
| OWC                 | 1        | 2      | 7.69%   |
| A-DATA Technology   | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 12       | 16     | 48%     |
| HDD  | 10       | 15     | 40%     |
| NVMe | 3        | 6      | 12%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 19       | 28     | 76%     |
| SAS  | 3        | 3      | 12%     |
| NVMe | 3        | 6      | 12%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 21     | 65.22%  |
| 0.51-1.0   | 6        | 7      | 26.09%  |
| 1.01-2.0   | 2        | 3      | 8.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 9        | 45%     |
| 251-500    | 3        | 15%     |
| 1001-2000  | 3        | 15%     |
| 1-20       | 3        | 15%     |
| 501-1000   | 1        | 5%      |
| 51-100     | 1        | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 16       | 84.21%  |
| 101-250   | 2        | 10.53%  |
| 1001-2000 | 1        | 5.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1        | 2      | 20%     |
| WDC WD800JD-75MSA3 80GB            | 1        | 1      | 20%     |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 20%     |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1        | 1      | 20%     |
| OWC Mercury EXTREME Pro 6G SSD     | 1        | 2      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 3      | 40%     |
| Seagate | 1        | 1      | 20%     |
| SanDisk | 1        | 1      | 20%     |
| OWC     | 1        | 2      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 3        | 5      | 60%     |
| HDD  | 2        | 2      | 40%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 15       | 27     | 65.22%  |
| Malfunc  | 5        | 7      | 21.74%  |
| Detected | 3        | 3      | 13.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Intel          | 15       | 68.18%  |
| AMD            | 4        | 18.18%  |
| Silicon Motion | 1        | 4.55%   |
| SanDisk        | 1        | 4.55%   |
| Nvidia         | 1        | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 13.33%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 6.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 6.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 6.67%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 3.33%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1        | 3.33%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 3.33%   |
| Nvidia MCP61 IDE                                                                        | 1        | 3.33%   |
| Intel SATA Controller [RAID Mode]                                                       | 1        | 3.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 3.33%   |
| Intel NVMe Optane Memory Series                                                         | 1        | 3.33%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 3.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 3.33%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 3.33%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 3.33%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 3.33%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 3.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 3.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 3.33%   |
| AMD FCH SATA Controller D                                                               | 1        | 3.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 3.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 14       | 58.33%  |
| IDE  | 6        | 25%     |
| NVMe | 3        | 12.5%   |
| RAID | 1        | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 73.68%  |
| AMD    | 5        | 26.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 10.53%  |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz             | 1        | 5.26%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz         | 1        | 5.26%   |
| Intel Pentium D CPU 2.80GHz                    | 1        | 5.26%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 5.26%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 5.26%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 5.26%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 5.26%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1        | 5.26%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 5.26%   |
| Intel Celeron CPU N2807 @ 1.58GHz              | 1        | 5.26%   |
| Intel Atom CPU D525 @ 1.80GHz                  | 1        | 5.26%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz       | 1        | 5.26%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 1        | 5.26%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G   | 1        | 5.26%   |
| AMD GX-212JC SOC with Radeon R2E Graphics      | 1        | 5.26%   |
| AMD Athlon II 170u Processor                   | 1        | 5.26%   |
| AMD A12-9800 RADEON R7, 12 COMPUTE CORES 4C+8G | 1        | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 3        | 15.79%  |
| Intel Core i3      | 2        | 10.53%  |
| Intel Core 2 Duo   | 2        | 10.53%  |
| Other              | 1        | 5.26%   |
| Intel Xeon         | 1        | 5.26%   |
| Intel Pentium Gold | 1        | 5.26%   |
| Intel Pentium D    | 1        | 5.26%   |
| Intel Core i7      | 1        | 5.26%   |
| Intel Celeron      | 1        | 5.26%   |
| Intel Atom         | 1        | 5.26%   |
| AMD Ryzen 5        | 1        | 5.26%   |
| AMD PRO A10        | 1        | 5.26%   |
| AMD GX             | 1        | 5.26%   |
| AMD Athlon II      | 1        | 5.26%   |
| AMD A12            | 1        | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 11       | 57.89%  |
| 4      | 4        | 21.05%  |
| 6      | 2        | 10.53%  |
| 8      | 1        | 5.26%   |
| 1      | 1        | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 52.63%  |
| 1      | 9        | 47.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 19       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 2        | 10%     |
| 0x0600611a | 2        | 10%     |
| Unknown    | 2        | 10%     |
| 0xf44      | 1        | 5%      |
| 0xa0671    | 1        | 5%      |
| 0xa0653    | 1        | 5%      |
| 0x906ed    | 1        | 5%      |
| 0x906ea    | 1        | 5%      |
| 0x906e9    | 1        | 5%      |
| 0x306c3    | 1        | 5%      |
| 0x30678    | 1        | 5%      |
| 0x206d7    | 1        | 5%      |
| 0x206a7    | 1        | 5%      |
| 0x106ca    | 1        | 5%      |
| 0x0810100b | 1        | 5%      |
| 0x07030104 | 1        | 5%      |
| 0x010000c8 | 1        | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 3        | 15%     |
| SandyBridge | 2        | 10%     |
| Penryn      | 2        | 10%     |
| Haswell     | 2        | 10%     |
| Excavator   | 2        | 10%     |
| Zen         | 1        | 5%      |
| Silvermont  | 1        | 5%      |
| Puma        | 1        | 5%      |
| NetBurst    | 1        | 5%      |
| K10         | 1        | 5%      |
| Icelake     | 1        | 5%      |
| CometLake   | 1        | 5%      |
| Bonnell     | 1        | 5%      |
| Unknown     | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 10       | 47.62%  |
| AMD    | 7        | 33.33%  |
| Nvidia | 4        | 19.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 9.09%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 4.55%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 4.55%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 4.55%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 4.55%   |
| Intel HD Graphics 630                                                       | 1        | 4.55%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 1        | 4.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 4.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 4.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 4.55%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 4.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 4.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 4.55%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                       | 1        | 4.55%   |
| AMD RV370 [Radeon X600/X600 SE]                                             | 1        | 4.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 4.55%   |
| AMD Mullins [Radeon R1E/R2E Graphics]                                       | 1        | 4.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 4.55%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 9        | 45%     |
| 1 x AMD    | 6        | 30%     |
| 1 x Nvidia | 4        | 20%     |
| 2 x AMD    | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 95%     |
| Proprietary | 1        | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 47.62%  |
| 0.01-0.5   | 5        | 23.81%  |
| 0.51-1.0   | 2        | 9.52%   |
| 7.01-8.0   | 1        | 4.76%   |
| 3.01-4.0   | 1        | 4.76%   |
| 1.01-2.0   | 1        | 4.76%   |
| 8.01-16.0  | 1        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 3        | 16.67%  |
| Samsung Electronics | 2        | 11.11%  |
| Goldstar            | 2        | 11.11%  |
| Zoran               | 1        | 5.56%   |
| Sony                | 1        | 5.56%   |
| Sceptre Tech        | 1        | 5.56%   |
| SAC                 | 1        | 5.56%   |
| Philips             | 1        | 5.56%   |
| Packard Bell        | 1        | 5.56%   |
| Lenovo              | 1        | 5.56%   |
| Insignia            | 1        | 5.56%   |
| Hewlett-Packard     | 1        | 5.56%   |
| eMachines           | 1        | 5.56%   |
| ASUSTek Computer    | 1        | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Zoran HDMI TV ZRN0294 1360x768 500x281mm 22.6-inch                | 1        | 5.56%   |
| Sony TV SNY0101 1360x768                                          | 1        | 5.56%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch    | 1        | 5.56%   |
| Samsung Electronics C32R50x SAM7001 1920x1080 698x393mm 31.5-inch | 1        | 5.56%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch | 1        | 5.56%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch             | 1        | 5.56%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                | 1        | 5.56%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch  | 1        | 5.56%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch              | 1        | 5.56%   |
| Insignia DX-LCD32 BBYCD32 1360x768 709x399mm 32.0-inch            | 1        | 5.56%   |
| Hewlett-Packard W2271d HWP3102 1920x1080 477x268mm 21.5-inch      | 1        | 5.56%   |
| Goldstar ULTRAGEAR GSM776E 2560x1440 697x392mm 31.5-inch          | 1        | 5.56%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch            | 1        | 5.56%   |
| eMachines E15T4W EMA05E1 1280x800 332x207mm 15.4-inch             | 1        | 5.56%   |
| Dell P2415Q DELA0C0 3840x2160 527x296mm 23.8-inch                 | 1        | 5.56%   |
| Dell P2319H DELD0D5 1920x1080 510x290mm 23.1-inch                 | 1        | 5.56%   |
| Dell E152FP DELA009 1024x768 304x228mm 15.0-inch                  | 1        | 5.56%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch      | 1        | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 10       | 58.82%  |
| 1360x768        | 3        | 17.65%  |
| 3840x2160 (4K)  | 1        | 5.88%   |
| 2560x1440 (QHD) | 1        | 5.88%   |
| 1280x800 (WXGA) | 1        | 5.88%   |
| 1024x768 (XGA)  | 1        | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 5        | 27.78%  |
| 24      | 4        | 22.22%  |
| 31      | 2        | 11.11%  |
| 23      | 2        | 11.11%  |
| 15      | 2        | 11.11%  |
| 32      | 1        | 5.56%   |
| 22      | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 33.33%  |
| 401-500     | 6        | 33.33%  |
| 601-700     | 2        | 11.11%  |
| 301-350     | 2        | 11.11%  |
| 701-800     | 1        | 5.56%   |
| Unknown     | 1        | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 14       | 87.5%   |
| 4/3   | 1        | 6.25%   |
| 16/10 | 1        | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 61.11%  |
| 351-500        | 3        | 16.67%  |
| 101-110        | 2        | 11.11%  |
| 151-200        | 1        | 5.56%   |
| Unknown        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 55.56%  |
| 101-120 | 5        | 27.78%  |
| 1-50    | 1        | 5.56%   |
| 161-240 | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 90%     |
| 2     | 1        | 5%      |
| 0     | 1        | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 10       | 40%     |
| Intel                           | 7        | 28%     |
| Qualcomm Atheros Communications | 2        | 8%      |
| Qualcomm Atheros                | 2        | 8%      |
| Ralink Technology               | 1        | 4%      |
| Nvidia                          | 1        | 4%      |
| MediaTek                        | 1        | 4%      |
| Broadcom                        | 1        | 4%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 9        | 30%     |
| Realtek RTL8188EE Wireless Network Adapter                             | 2        | 6.67%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2        | 6.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 3.33%   |
| Realtek RTL8191SEvA Wireless LAN Controller                            | 1        | 3.33%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1        | 3.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 3.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 3.33%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 3.33%   |
| MediaTek moto e22                                                      | 1        | 3.33%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 3.33%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 3.33%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 3.33%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 3.33%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 3.33%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 3.33%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1        | 3.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 4        | 40%     |
| Qualcomm Atheros Communications | 2        | 20%     |
| Intel                           | 2        | 20%     |
| Ralink Technology               | 1        | 10%     |
| Qualcomm Atheros                | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek RTL8188EE Wireless Network Adapter                 | 2        | 20%     |
| Qualcomm Atheros AR9271 802.11n                            | 2        | 20%     |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 10%     |
| Realtek RTL8191SEvA Wireless LAN Controller                | 1        | 10%     |
| Ralink MT7601U Wireless Adapter                            | 1        | 10%     |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 10%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 10%     |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 45%     |
| Intel                 | 6        | 30%     |
| Qualcomm Atheros      | 2        | 10%     |
| Nvidia                | 1        | 5%      |
| MediaTek              | 1        | 5%      |
| Broadcom              | 1        | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 9        | 45%     |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 5%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 5%      |
| Nvidia MCP61 Ethernet                                                  | 1        | 5%      |
| MediaTek moto e22                                                      | 1        | 5%      |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 5%      |
| Intel I211 Gigabit Network Connection                                  | 1        | 5%      |
| Intel Ethernet Connection I217-LM                                      | 1        | 5%      |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 5%      |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 5%      |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 5%      |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1        | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 67.86%  |
| WiFi     | 9        | 32.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 70%     |
| WiFi     | 6        | 30%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 65%     |
| 2     | 6        | 30%     |
| 3     | 1        | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 70%     |
| Yes  | 6        | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 1        | 33.33%  |
| Intel                           | 1        | 33.33%  |
| IMC Networks                    | 1        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Qualcomm Atheros  Bluetooth Device | 1        | 33.33%  |
| Intel AX201 Bluetooth              | 1        | 33.33%  |
| IMC Networks Bluetooth Radio       | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 58.33%  |
| AMD    | 6        | 25%     |
| Nvidia | 4        | 16.67%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Kabini HDMI/DP Audio                                                          | 3        | 10%     |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 6.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 6.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 6.67%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 6.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 2        | 6.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 3.33%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 3.33%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 3.33%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 3.33%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 1        | 3.33%   |
| Intel HD Graphics SGPC                                                            | 1        | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 3.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1        | 3.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 3.33%   |
| AMD FCH Azalia Controller                                                         | 1        | 3.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 3.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 3.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 4        | 15.38%  |
| Crucial             | 4        | 15.38%  |
| Samsung Electronics | 3        | 11.54%  |
| Kingston            | 3        | 11.54%  |
| Corsair             | 3        | 11.54%  |
| Unknown             | 2        | 7.69%   |
| Unknown (08C8)      | 1        | 3.85%   |
| Team                | 1        | 3.85%   |
| Micron Technology   | 1        | 3.85%   |
| Infineon            | 1        | 3.85%   |
| G.Skill             | 1        | 3.85%   |
| A-DATA Technology   | 1        | 3.85%   |
| Unknown             | 1        | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 2        | 7.14%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                    | 1        | 3.57%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1        | 3.57%   |
| Unknown (08C8) RAM LMKUFG68AHFHD-32A 16GB DIMM DDR4 3200MT/s | 1        | 3.57%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s          | 1        | 3.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1        | 3.57%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s         | 1        | 3.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 3.57%   |
| Samsung RAM M393B1K70CH0 8GB DIMM DDR3 1866MT/s              | 1        | 3.57%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 1        | 3.57%   |
| Micron RAM 16HTF12864AY-53EB1 1GB DIMM DDR 533MT/s           | 1        | 3.57%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                    | 1        | 3.57%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                    | 1        | 3.57%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s         | 1        | 3.57%   |
| Kingston RAM HP655410-150-HYCG 4GB DIMM DDR3 1600MT/s        | 1        | 3.57%   |
| Infineon RAM 64T64000HU3.7A 512MB DIMM DDR 533MT/s           | 1        | 3.57%   |
| G.Skill RAM F2-6400CL5-2GBPQ 2GB DIMM DDR2 800MT/s           | 1        | 3.57%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s        | 1        | 3.57%   |
| Crucial RAM CT25664AA800.C16FH 2GB DIMM DDR2 800MT/s         | 1        | 3.57%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 1        | 3.57%   |
| Crucial RAM BLS4G4D26BFSE.8FB 4GB DIMM DDR4 2667MT/s         | 1        | 3.57%   |
| Crucial RAM BLS4G4D26BFSC.8FB 4GB DIMM DDR4 2400MT/s         | 1        | 3.57%   |
| Corsair RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                | 1        | 3.57%   |
| Corsair RAM CMV8GX4M1A2133C15 8192MB DIMM DDR4 2733MT/s      | 1        | 3.57%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s         | 1        | 3.57%   |
| A-DATA RAM Module 8GB DIMM DDR4 3200MT/s                     | 1        | 3.57%   |
| Unknown                                                      | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 9        | 45%     |
| DDR4 | 7        | 35%     |
| DDR2 | 3        | 15%     |
| DDR  | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 84.21%  |
| SODIMM | 3        | 15.79%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 36.36%  |
| 4096  | 6        | 27.27%  |
| 1024  | 3        | 13.64%  |
| 2048  | 2        | 9.09%   |
| 32768 | 1        | 4.55%   |
| 16384 | 1        | 4.55%   |
| 512   | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 6        | 25%     |
| 3733  | 2        | 8.33%   |
| 3200  | 2        | 8.33%   |
| 1800  | 2        | 8.33%   |
| 667   | 2        | 8.33%   |
| 3066  | 1        | 4.17%   |
| 2733  | 1        | 4.17%   |
| 2667  | 1        | 4.17%   |
| 2666  | 1        | 4.17%   |
| 2400  | 1        | 4.17%   |
| 1866  | 1        | 4.17%   |
| 1333  | 1        | 4.17%   |
| 1066  | 1        | 4.17%   |
| 800   | 1        | 4.17%   |
| 533   | 1        | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 66.67%  |
| Samsung Electronics | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 1        | 33.33%  |
| HP DeskJet F4200 series               | 1        | 33.33%  |
| HP DeskJet 2130 series                | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Logitech Webcam C160 | 1        | 100%    |

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
| 0     | 17       | 89.47%  |
| 2     | 1        | 5.26%   |
| 1     | 1        | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Multimedia controller    | 1        | 33.33%  |
| Graphics card            | 1        | 33.33%  |
| Communication controller | 1        | 33.33%  |

