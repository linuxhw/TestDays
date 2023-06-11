antiX - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for antiX.

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

Total: 23

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | MPG Z390 GAMING PRO CARB... | [4551c437bf](https://linux-hardware.org/?probe=4551c437bf) | May 18, 2023 |
| Intel    | H61                         | [aa4606c36c](https://linux-hardware.org/?probe=aa4606c36c) | May 02, 2023 |
| Pegatron | NARRA5                      | [4c8bb5eff0](https://linux-hardware.org/?probe=4c8bb5eff0) | Apr 30, 2023 |
| MSI      | B550-A PRO                  | [d8b51c995c](https://linux-hardware.org/?probe=d8b51c995c) | Apr 23, 2023 |
| Gigabyte | Z790 AERO G                 | [f33074a4c8](https://linux-hardware.org/?probe=f33074a4c8) | Apr 03, 2023 |
| Gigabyte | Z790 AERO G                 | [2f380f0d1a](https://linux-hardware.org/?probe=2f380f0d1a) | Apr 03, 2023 |
| VXL      | M6V90AI-VL                  | [935d6b4b24](https://linux-hardware.org/?probe=935d6b4b24) | Feb 21, 2023 |
| Intel    | D525MW AAE93082-401         | [a225baa8a4](https://linux-hardware.org/?probe=a225baa8a4) | Aug 05, 2022 |
| Biostar  | G31-M7 TE                   | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Dell     | 0F428D A00                  | [fb8a6009f7](https://linux-hardware.org/?probe=fb8a6009f7) | Jul 16, 2022 |
| MSI      | B560M PRO-VDH WIFI [CEC]    | [af73739875](https://linux-hardware.org/?probe=af73739875) | Jul 14, 2022 |
| Unknown  | K8NF3-VSTA                  | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI      | B560M PRO-VDH WIFI [CEC]    | [8654086b85](https://linux-hardware.org/?probe=8654086b85) | Jun 20, 2022 |
| Gigabyte | F2A85XM-D3H                 | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte | 945GCMX-S2                  | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| Unknown  | NF-CK804                    | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| ASUSTek  | A8R-MVP                     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek  | M2N-MX SE Plus              | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock   | H81M-ITX                    | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| HP       | 3641h                       | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| Unknown  | Unknown                     | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek  | P5KPL/1600                  | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo   | ThinkCentre M91p 4480B9U    | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| antiX 21       | 9        | 45%     |
| antiX 22       | 3        | 15%     |
| antiX 19.2     | 2        | 10%     |
| antiX 17.4.1   | 2        | 10%     |
| antiX 21-runit | 1        | 5%      |
| antiX 19.3     | 1        | 5%      |
| antiX 17.1     | 1        | 5%      |
| antiX 15       | 1        | 5%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| antiX | 20       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.57-antix.1-amd64-smp   | 4        | 20%     |
| 5.10.142-antix.2-amd64-smp  | 3        | 15%     |
| 4.9.0-279-antix.1-amd64-smp | 3        | 15%     |
| 4.9.160-antix.2-486-smp     | 2        | 10%     |
| 6.2.9-1-liquorix-amd64      | 1        | 5%      |
| 5.10.88-antix.1-amd64-smp   | 1        | 5%      |
| 4.9.87-antix.1-amd64-smp    | 1        | 5%      |
| 4.9.235-antix.1-amd64-smp   | 1        | 5%      |
| 4.9.212-antix.1-amd64-smp   | 1        | 5%      |
| 4.9.212-antix.1-486-smp     | 1        | 5%      |
| 4.9.0-326-antix.1-amd64-smp | 1        | 5%      |
| 4.9.0-279-antix.1-486-smp   | 1        | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.9.0    | 5        | 25%     |
| 5.10.57  | 4        | 20%     |
| 5.10.142 | 3        | 15%     |
| 4.9.212  | 2        | 10%     |
| 4.9.160  | 2        | 10%     |
| 6.2.9    | 1        | 5%      |
| 5.10.88  | 1        | 5%      |
| 4.9.87   | 1        | 5%      |
| 4.9.235  | 1        | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 11       | 55%     |
| 5.10    | 8        | 40%     |
| 6.2     | 1        | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 16       | 80%     |
| i686   | 4        | 20%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| icewm        | 9        | 45%     |
| Unknown      | 8        | 40%     |
| XFCE         | 1        | 5%      |
| jwm          | 1        | 5%      |
| herbstluftwm | 1        | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 18       | 90%     |
| Tty  | 2        | 10%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 9        | 45%     |
| SLiM    | 6        | 30%     |
| SLIMSKI | 4        | 20%     |
| LightDM | 1        | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 6        | 30%     |
| Unknown | 3        | 15%     |
| pt_BR   | 2        | 10%     |
| pl_PL   | 2        | 10%     |
| en_GB   | 2        | 10%     |
| sk_SK   | 1        | 5%      |
| ru_RU   | 1        | 5%      |
| it_IT   | 1        | 5%      |
| fr_FR   | 1        | 5%      |
| es_AR   | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 14       | 70%     |
| EFI  | 6        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 17       | 85%     |
| Overlay | 2        | 10%     |
| Xfs     | 1        | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 13       | 65%     |
| GPT     | 6        | 30%     |
| Unknown | 1        | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 70%     |
| Yes       | 6        | 30%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 70%     |
| Yes       | 6        | 30%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 4        | 20%     |
| Gigabyte Technology | 3        | 15%     |
| Unknown             | 3        | 15%     |
| Intel               | 2        | 10%     |
| ASUSTek Computer    | 2        | 10%     |
| VXL                 | 1        | 5%      |
| Pegatron            | 1        | 5%      |
| Lenovo              | 1        | 5%      |
| Hewlett-Packard     | 1        | 5%      |
| Dell                | 1        | 5%      |
| Biostar             | 1        | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 3        | 15%     |
| MSI US Desktop                  | 2        | 10%     |
| VXL TC7520d                     | 1        | 5%      |
| Pegatron VC902AA-ABF p6136fr    | 1        | 5%      |
| MSI MS-7C56                     | 1        | 5%      |
| MSI MS-7B17                     | 1        | 5%      |
| Lenovo ThinkCentre M91p 4480B9U | 1        | 5%      |
| Intel H61                       | 1        | 5%      |
| Intel D525MW AAE93082-401       | 1        | 5%      |
| HP t5740                        | 1        | 5%      |
| Gigabyte Z790 AERO G            | 1        | 5%      |
| Gigabyte F2A85XM-D3H            | 1        | 5%      |
| Gigabyte 945GCMX-S2             | 1        | 5%      |
| Dell OptiPlex 960               | 1        | 5%      |
| Biostar G31-M7 TE               | 1        | 5%      |
| ASUS P5KPL/1600                 | 1        | 5%      |
| ASUS A8R-MVP                    | 1        | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 3        | 15%     |
| MSI US               | 2        | 10%     |
| VXL TC7520d          | 1        | 5%      |
| Pegatron VC902AA-ABF | 1        | 5%      |
| MSI MS-7C56          | 1        | 5%      |
| MSI MS-7B17          | 1        | 5%      |
| Lenovo ThinkCentre   | 1        | 5%      |
| Intel H61            | 1        | 5%      |
| Intel D525MW         | 1        | 5%      |
| HP t5740             | 1        | 5%      |
| Gigabyte Z790        | 1        | 5%      |
| Gigabyte F2A85XM-D3H | 1        | 5%      |
| Gigabyte 945GCMX-S2  | 1        | 5%      |
| Dell OptiPlex        | 1        | 5%      |
| Biostar G31-M7       | 1        | 5%      |
| ASUS P5KPL           | 1        | 5%      |
| ASUS A8R-MVP         | 1        | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2009    | 3        | 15%     |
| 2008    | 3        | 15%     |
| 2021    | 2        | 10%     |
| 2011    | 2        | 10%     |
| 2007    | 2        | 10%     |
| 2022    | 1        | 5%      |
| 2020    | 1        | 5%      |
| 2018    | 1        | 5%      |
| 2017    | 1        | 5%      |
| 2014    | 1        | 5%      |
| 2012    | 1        | 5%      |
| 2005    | 1        | 5%      |
| Unknown | 1        | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 20       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 20       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 4        | 20%     |
| 32.01-64.0  | 3        | 15%     |
| 3.01-4.0    | 3        | 15%     |
| 4.01-8.0    | 2        | 10%     |
| 2.01-3.0    | 2        | 10%     |
| 64.01-256.0 | 2        | 10%     |
| 16.01-24.0  | 1        | 5%      |
| 8.01-16.0   | 1        | 5%      |
| 0.51-1.0    | 1        | 5%      |
| 0.01-0.5    | 1        | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 7        | 35%     |
| 0.01-0.5   | 6        | 30%     |
| 1.01-2.0   | 3        | 15%     |
| 4.01-8.0   | 2        | 10%     |
| 32.01-64.0 | 1        | 5%      |
| 2.01-3.0   | 1        | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 50%     |
| 4      | 3        | 15%     |
| 3      | 3        | 15%     |
| 2      | 2        | 10%     |
| 5      | 1        | 5%      |
| 0      | 1        | 5%      |

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
| Yes       | 20       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 65%     |
| Yes       | 7        | 35%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 70%     |
| Yes       | 6        | 30%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 5        | 25%     |
| UK        | 2        | 10%     |
| Russia    | 2        | 10%     |
| Poland    | 2        | 10%     |
| France    | 2        | 10%     |
| Brazil    | 2        | 10%     |
| Slovakia  | 1        | 5%      |
| Italy     | 1        | 5%      |
| Greece    | 1        | 5%      |
| Germany   | 1        | 5%      |
| Argentina | 1        | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zagnansk          | 1        | 5%      |
| Violes            | 1        | 5%      |
| Romilly-sur-Seine | 1        | 5%      |
| Padova            | 1        | 5%      |
| Otwock            | 1        | 5%      |
| Nova Londrina     | 1        | 5%      |
| Miami             | 1        | 5%      |
| Mason             | 1        | 5%      |
| Maringá          | 1        | 5%      |
| Maidstone         | 1        | 5%      |
| Kazan’          | 1        | 5%      |
| Houston           | 1        | 5%      |
| Heraklion         | 1        | 5%      |
| Greenwich         | 1        | 5%      |
| Frankfurt am Main | 1        | 5%      |
| Covington         | 1        | 5%      |
| Buenos Aires      | 1        | 5%      |
| Bryansk           | 1        | 5%      |
| Bratislava        | 1        | 5%      |
| Boulder           | 1        | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 7        | 9      | 21.21%  |
| Samsung Electronics       | 6        | 8      | 18.18%  |
| Seagate                   | 4        | 4      | 12.12%  |
| Toshiba                   | 3        | 4      | 9.09%   |
| Micron/Crucial Technology | 2        | 2      | 6.06%   |
| Kingston                  | 2        | 3      | 6.06%   |
| BHT                       | 2        | 2      | 6.06%   |
| Unknown                   | 1        | 1      | 3.03%   |
| SanDisk                   | 1        | 1      | 3.03%   |
| Maxtor                    | 1        | 1      | 3.03%   |
| Intel                     | 1        | 1      | 3.03%   |
| Hitachi                   | 1        | 2      | 3.03%   |
| Crucial                   | 1        | 1      | 3.03%   |
| Apacer                    | 1        | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| WDC WD800AAJS-75M0A0 80GB                          | 2        | 5.56%   |
| WDC WD10SPZX-80Z10T2 1TB                           | 2        | 5.56%   |
| Toshiba MQ01ABD050V -63 500GB                      | 2        | 5.56%   |
| Kingston SA400S37240G 240GB SSD                    | 2        | 5.56%   |
| BHT WR202F0032G 670270F5 32GB SSD                  | 2        | 5.56%   |
| WDC WD800JB-00ETA0 80GB                            | 1        | 2.78%   |
| WDC WD205BA 21GB                                   | 1        | 2.78%   |
| WDC WD2003FZEX-00Z4SA0 2TB                         | 1        | 2.78%   |
| WDC WD1600AAJS-00PSA0 160GB                        | 1        | 2.78%   |
| WDC WD10EADS-65M2B0 1TB                            | 1        | 2.78%   |
| Unknown 2GB ATA Flash Disk                         | 1        | 2.78%   |
| Toshiba MG06ACA600E 6TB                            | 1        | 2.78%   |
| Seagate ST500DM002-1BD142 500GB                    | 1        | 2.78%   |
| Seagate ST3320620AS 320GB                          | 1        | 2.78%   |
| Seagate ST3320413CS 320GB                          | 1        | 2.78%   |
| Seagate ST1000DM010-2EP102 1TB                     | 1        | 2.78%   |
| SanDisk sandisk120 120GB SSD                       | 1        | 2.78%   |
| Samsung SSD 860 EVO 500GB                          | 1        | 2.78%   |
| Samsung SSD 850 EVO 120GB                          | 1        | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1        | 2.78%   |
| Samsung HD250HJ 250GB                              | 1        | 2.78%   |
| Samsung HD162GJ 160GB                              | 1        | 2.78%   |
| Samsung HD160JJ 160GB                              | 1        | 2.78%   |
| Samsung HD080HJ/ 80GB                              | 1        | 2.78%   |
| Micron/Crucial P1 NVMe PCIe SSD 500GB              | 1        | 2.78%   |
| Micron/Crucial CT2000P5PSSD8 2TB                   | 1        | 2.78%   |
| Maxtor Z1 SSD 240GB                                | 1        | 2.78%   |
| Intel SSDPEKNW010T8 1TB                            | 1        | 2.78%   |
| Hitachi HTS723232A7A364 320GB                      | 1        | 2.78%   |
| Crucial CT500MX500SSD1 500GB                       | 1        | 2.78%   |
| Apacer 32GB SATA Flash Drive SSD                   | 1        | 2.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 36.84%  |
| Seagate             | 4        | 4      | 21.05%  |
| Toshiba             | 3        | 4      | 15.79%  |
| Samsung Electronics | 3        | 4      | 15.79%  |
| Unknown             | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 2      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 20%     |
| Kingston            | 2        | 3      | 20%     |
| BHT                 | 2        | 2      | 20%     |
| SanDisk             | 1        | 1      | 10%     |
| Maxtor              | 1        | 1      | 10%     |
| Crucial             | 1        | 1      | 10%     |
| Apacer              | 1        | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 24     | 51.85%  |
| SSD  | 10       | 11     | 37.04%  |
| NVMe | 3        | 5      | 11.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 19       | 35     | 86.36%  |
| NVMe | 3        | 5      | 13.64%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 28     | 75%     |
| 0.51-1.0   | 4        | 4      | 16.67%  |
| 1.01-2.0   | 1        | 1      | 4.17%   |
| 4.01-10.0  | 1        | 2      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 5        | 25%     |
| 251-500        | 3        | 15%     |
| 21-50          | 3        | 15%     |
| 501-1000       | 3        | 15%     |
| 1-20           | 2        | 10%     |
| 51-100         | 2        | 10%     |
| More than 3000 | 1        | 5%      |
| 1001-2000      | 1        | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 13       | 65%     |
| 101-250        | 3        | 15%     |
| More than 3000 | 1        | 5%      |
| 21-50          | 1        | 5%      |
| 501-1000       | 1        | 5%      |
| 51-100         | 1        | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB                   | 2        | 2      | 18.18%  |
| WDC WD800JB-00ETA0 80GB                     | 1        | 1      | 9.09%   |
| WDC WD205BA 21GB                            | 1        | 1      | 9.09%   |
| WDC WD10EADS-65M2B0 1TB                     | 1        | 1      | 9.09%   |
| Seagate ST500DM002-1BD142 500GB             | 1        | 1      | 9.09%   |
| Seagate ST3320620AS 320GB                   | 1        | 1      | 9.09%   |
| Seagate ST3320413CS 320GB                   | 1        | 1      | 9.09%   |
| SanDisk sandisk120 120GB SSD                | 1        | 1      | 9.09%   |
| Micron/Crucial Technology CT2000P5PSSD8 2TB | 1        | 1      | 9.09%   |
| Apacer 32GB SATA Flash Drive SSD            | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 5        | 5      | 45.45%  |
| Seagate                   | 3        | 3      | 27.27%  |
| SanDisk                   | 1        | 1      | 9.09%   |
| Micron/Crucial Technology | 1        | 1      | 9.09%   |
| Apacer                    | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 5      | 62.5%   |
| Seagate | 3        | 3      | 37.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 8      | 72.73%  |
| SSD  | 2        | 2      | 18.18%  |
| NVMe | 1        | 1      | 9.09%   |

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
| Malfunc  | 11       | 11     | 44%     |
| Works    | 11       | 25     | 44%     |
| Detected | 3        | 4      | 12%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 13       | 46.43%  |
| ASMedia Technology        | 4        | 14.29%  |
| Nvidia                    | 3        | 10.71%  |
| Micron/Crucial Technology | 2        | 7.14%   |
| AMD                       | 2        | 7.14%   |
| VIA Technologies          | 1        | 3.57%   |
| ULi Electronics           | 1        | 3.57%   |
| Samsung Electronics       | 1        | 3.57%   |
| LSI Logic / Symbios Logic | 1        | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 3        | 8.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 3        | 8.11%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 3        | 8.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 5.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2        | 5.41%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 2        | 5.41%   |
| VIA VX900 Series Serial-ATA Controller                                        | 1        | 2.7%    |
| ULi ULi M5288 SATA                                                            | 1        | 2.7%    |
| ULi M5229 IDE                                                                 | 1        | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 2.7%    |
| Nvidia nForce3 Serial ATA Controller                                          | 1        | 2.7%    |
| Nvidia MCP61 SATA Controller                                                  | 1        | 2.7%    |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                    | 1        | 2.7%    |
| Nvidia CK804 Serial ATA Controller                                            | 1        | 2.7%    |
| Nvidia CK804 IDE                                                              | 1        | 2.7%    |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1        | 2.7%    |
| Micron/Crucial P1 NVMe PCIe SSD                                               | 1        | 2.7%    |
| LSI Logic / Symbios Logic SAS3008 PCI-Express Fusion-MPT SAS-3                | 1        | 2.7%    |
| Intel SSD 660P Series                                                         | 1        | 2.7%    |
| Intel SATA Controller [RAID mode]                                             | 1        | 2.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1        | 2.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 1        | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 2.7%    |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 1        | 2.7%    |
| Intel 700 Series Chipset Family SATA AHCI Controller                          | 1        | 2.7%    |
| Intel 4 Series Chipset PT IDER Controller                                     | 1        | 2.7%    |
| ASMedia ASM1061 SATA IDE Controller                                           | 1        | 2.7%    |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 11       | 42.31%  |
| SATA | 10       | 38.46%  |
| NVMe | 3        | 11.54%  |
| RAID | 1        | 3.85%   |
| SAS  | 1        | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 13       | 65%     |
| AMD          | 6        | 30%     |
| CentaurHauls | 1        | 5%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2        | 10%     |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1        | 5%      |
| Intel Pentium II (Deschutes)                | 1        | 5%      |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 5%      |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 5%      |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 5%      |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 5%      |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 5%      |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 5%      |
| Intel Atom CPU N280 @ 1.66GHz               | 1        | 5%      |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 5%      |
| Intel 13th Gen Core i9-13900K               | 1        | 5%      |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz   | 1        | 5%      |
| AMD Sempron Processor 3000+                 | 1        | 5%      |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 5%      |
| AMD Phenom 9650 Quad-Core Processor         | 1        | 5%      |
| AMD Athlon 64 X2 Dual Core Processor 4600+  | 1        | 5%      |
| AMD Athlon 64 Processor 3200+               | 1        | 5%      |
| AMD A6-5400K APU with Radeon HD Graphics    | 1        | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Other                   | 3        | 15%     |
| Intel Atom              | 2        | 10%     |
| Intel Xeon              | 1        | 5%      |
| Intel Pentium Dual-Core | 1        | 5%      |
| Intel Pentium Dual      | 1        | 5%      |
| Intel Pentium           | 1        | 5%      |
| Intel Core i9           | 1        | 5%      |
| Intel Core i7           | 1        | 5%      |
| Intel Core i5           | 1        | 5%      |
| Intel Core 2 Quad       | 1        | 5%      |
| CentaurHauls VIA Eden   | 1        | 5%      |
| AMD Sempron             | 1        | 5%      |
| AMD Ryzen 7             | 1        | 5%      |
| AMD Phenom              | 1        | 5%      |
| AMD Athlon 64 X2        | 1        | 5%      |
| AMD Athlon 64           | 1        | 5%      |
| AMD A6                  | 1        | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 5        | 25%     |
| 2      | 5        | 25%     |
| 1      | 5        | 25%     |
| 8      | 2        | 10%     |
| 6      | 2        | 10%     |
| 24     | 1        | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 55%     |
| 2      | 9        | 45%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 18       | 90%     |
| 32-bit         | 2        | 10%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 30%     |
| 0xa0671    | 2        | 10%     |
| 0x206a7    | 2        | 10%     |
| 0x1067a    | 2        | 10%     |
| 0x906ed    | 1        | 5%      |
| 0x6fd      | 1        | 5%      |
| 0x652      | 1        | 5%      |
| 0x106ca    | 1        | 5%      |
| 0x106c2    | 1        | 5%      |
| 0x10676    | 1        | 5%      |
| 0x06001116 | 1        | 5%      |
| 0x01000095 | 1        | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 4        | 20%     |
| Penryn           | 3        | 15%     |
| K8 Hammer        | 3        | 15%     |
| SandyBridge      | 2        | 10%     |
| Bonnell          | 2        | 10%     |
| Zen+             | 1        | 5%      |
| Piledriver       | 1        | 5%      |
| KabyLake         | 1        | 5%      |
| K10              | 1        | 5%      |
| Core             | 1        | 5%      |
| Alderlake Hybrid | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 8        | 38.1%   |
| Intel            | 6        | 28.57%  |
| AMD              | 6        | 28.57%  |
| VIA Technologies | 1        | 4.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 2        | 8.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2        | 8.33%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                              | 1        | 4.17%   |
| Nvidia GT218 [GeForce G210]                                               | 1        | 4.17%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1        | 4.17%   |
| Nvidia GF119 [GeForce GT 520]                                             | 1        | 4.17%   |
| Nvidia GF108 [GeForce GT 630]                                             | 1        | 4.17%   |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                        | 1        | 4.17%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                       | 1        | 4.17%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1        | 4.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1        | 4.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 4.17%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1        | 4.17%   |
| Intel 82945G/GZ Integrated Graphics Controller                            | 1        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 4.17%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 4.17%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                     | 1        | 4.17%   |
| AMD RV515 [Radeon X1300/X1550]                                            | 1        | 4.17%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 4.17%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                   | 1        | 4.17%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                        | 1        | 4.17%   |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                           | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 7        | 35%     |
| 1 x Intel      | 5        | 25%     |
| 2 x AMD        | 3        | 15%     |
| 1 x AMD        | 3        | 15%     |
| 1 x VIA        | 1        | 5%      |
| Intel + Nvidia | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 60%     |
| Proprietary | 4        | 20%     |
| Unknown     | 4        | 20%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 45%     |
| 0.01-0.5   | 6        | 30%     |
| 1.01-2.0   | 2        | 10%     |
| 5.01-6.0   | 1        | 5%      |
| 16.01-24.0 | 1        | 5%      |
| 0.51-1.0   | 1        | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Acer                 | 4        | 28.57%  |
| Samsung Electronics  | 2        | 14.29%  |
| Goldstar             | 2        | 14.29%  |
| Vizio                | 1        | 7.14%   |
| LG Electronics       | 1        | 7.14%   |
| Dell                 | 1        | 7.14%   |
| AOC                  | 1        | 7.14%   |
| Ancor Communications | 1        | 7.14%   |
| Unknown              | 1        | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E320i-A0 VIZ1002 1366x768 698x392mm 31.5-inch                   | 1        | 7.14%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch  | 1        | 7.14%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 1        | 7.14%   |
| LG Electronics LCD Monitor LG Ultra HD 4480x3600                      | 1        | 7.14%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 7.14%   |
| Goldstar M198WA GSM4B36 1440x900 410x260mm 19.1-inch                  | 1        | 7.14%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                      | 1        | 7.14%   |
| AOC 2280W AOC2280 1920x1080 477x268mm 21.5-inch                       | 1        | 7.14%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 1        | 7.14%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 1        | 7.14%   |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                      | 1        | 7.14%   |
| Acer V223HQV ACR025D 1920x1080 510x287mm 23.0-inch                    | 1        | 7.14%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                     | 1        | 7.14%   |
| Unknown                                                               | 1        | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 7        | 50%     |
| 1366x768 (WXGA)  | 2        | 14.29%  |
| 4480x3600        | 1        | 7.14%   |
| 2560x1080        | 1        | 7.14%   |
| 1600x1200        | 1        | 7.14%   |
| 1440x900 (WXGA+) | 1        | 7.14%   |
| Unknown          | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 5        | 38.46%  |
| 38      | 1        | 7.69%   |
| 34      | 1        | 7.69%   |
| 27      | 1        | 7.69%   |
| 24      | 1        | 7.69%   |
| 23      | 1        | 7.69%   |
| 19      | 1        | 7.69%   |
| 18      | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 7        | 53.85%  |
| 501-600     | 3        | 23.08%  |
| 801-900     | 1        | 7.69%   |
| 701-800     | 1        | 7.69%   |
| Unknown     | 1        | 7.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 9        | 69.23%  |
| 4/3     | 1        | 7.69%   |
| 21/9    | 1        | 7.69%   |
| 16/10   | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 46.15%  |
| 151-200        | 2        | 15.38%  |
| 351-500        | 1        | 7.69%   |
| 301-350        | 1        | 7.69%   |
| 141-150        | 1        | 7.69%   |
| 501-1000       | 1        | 7.69%   |
| Unknown        | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 7        | 53.85%  |
| 101-120 | 4        | 30.77%  |
| 1-50    | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 70%     |
| 0     | 5        | 25%     |
| 2     | 1        | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 13       | 44.83%  |
| Intel                           | 6        | 20.69%  |
| Nvidia                          | 3        | 10.34%  |
| Ralink Technology               | 2        | 6.9%    |
| Samsung Electronics             | 1        | 3.45%   |
| Qualcomm Atheros Communications | 1        | 3.45%   |
| Marvell Technology Group        | 1        | 3.45%   |
| LSI                             | 1        | 3.45%   |
| Broadcom                        | 1        | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 4        | 12.12%  |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 6.06%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 6.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 6.06%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2        | 6.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 6.06%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 6.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 6.06%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 3.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 3.03%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 3.03%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 3.03%   |
| Nvidia CK8S Ethernet Controller                                               | 1        | 3.03%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 3.03%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 3.03%   |
| LSI 56k WinModem                                                              | 1        | 3.03%   |
| Intel Ethernet Controller I225-V                                              | 1        | 3.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 3.03%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 3.03%   |
| Intel 700 Series Chipset Family Wi-Fi                                         | 1        | 3.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 44.44%  |
| Realtek Semiconductor           | 2        | 22.22%  |
| Ralink Technology               | 2        | 22.22%  |
| Qualcomm Atheros Communications | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 22.22%  |
| Ralink RT5370 Wireless Adapter                                                | 2        | 22.22%  |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 22.22%  |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 11.11%  |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 11.11%  |
| Intel 700 Series Chipset Family Wi-Fi                                         | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 13       | 59.09%  |
| Intel                    | 4        | 18.18%  |
| Nvidia                   | 3        | 13.64%  |
| Marvell Technology Group | 1        | 4.55%   |
| Broadcom                 | 1        | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 18.18%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 9.09%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 9.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 9.09%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 4.55%   |
| Nvidia MCP61 Ethernet                                             | 1        | 4.55%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 4.55%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 4.55%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 4.55%   |
| Intel Ethernet Controller I225-V                                  | 1        | 4.55%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 4.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 68.97%  |
| WiFi     | 7        | 24.14%  |
| Modem    | 2        | 6.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 80.95%  |
| WiFi     | 4        | 19.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 70%     |
| 2     | 6        | 30%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 80%     |
| Yes  | 4        | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 66.67%  |
| Cambridge Silicon Radio | 2        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                               | 2        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 33.33%  |
| Intel Bluetooth Device                              | 1        | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 11       | 37.93%  |
| Nvidia              | 8        | 27.59%  |
| AMD                 | 3        | 10.34%  |
| Creative Labs       | 2        | 6.9%    |
| C-Media Electronics | 2        | 6.9%    |
| VIA Technologies    | 1        | 3.45%   |
| ULi Electronics     | 1        | 3.45%   |
| Ensoniq             | 1        | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 9.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 6.45%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 6.45%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 6.45%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 3.23%   |
| VIA Technologies High Definition Audio Controller                          | 1        | 3.23%   |
| ULi Electronics HD Audio Controller                                        | 1        | 3.23%   |
| Nvidia High Definition Audio Controller                                    | 1        | 3.23%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 3.23%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 3.23%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 3.23%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 3.23%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1        | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 3.23%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 3.23%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 1        | 3.23%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1        | 3.23%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 3.23%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 3.23%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 3.23%   |
| C-Media Electronics CM6501                                                 | 1        | 3.23%   |
| AMD FCH Azalia Controller                                                  | 1        | 3.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 3.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 30.43%  |
| Samsung Electronics | 3        | 13.04%  |
| Kingston            | 3        | 13.04%  |
| SK hynix            | 2        | 8.7%    |
| Corsair             | 2        | 8.7%    |
| Unknown (0x0DA2)    | 1        | 4.35%   |
| Smart               | 1        | 4.35%   |
| Ramaxel Technology  | 1        | 4.35%   |
| Patriot             | 1        | 4.35%   |
| Kllisre             | 1        | 4.35%   |
| A-DATA Technology   | 1        | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 2        | 8%      |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1        | 4%      |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                | 1        | 4%      |
| Unknown RAM Module 512MB DIMM                            | 1        | 4%      |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 4%      |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 1        | 4%      |
| Unknown RAM Module 1GB DIMM SDRAM                        | 1        | 4%      |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                  | 1        | 4%      |
| Unknown RAM Module 1GB DIMM 667MT/s                      | 1        | 4%      |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s              | 1        | 4%      |
| Unknown (0x0DA2) RAM SB-DR5U-32G 32GB DIMM DDR5 4800MT/s | 1        | 4%      |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s       | 1        | 4%      |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 4%      |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s   | 1        | 4%      |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 1333MT/s          | 1        | 4%      |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s     | 1        | 4%      |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 1        | 4%      |
| Ramaxel RAM RMUA5180MH78HBF-2666 16GB DIMM DDR4 2400MT/s | 1        | 4%      |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s       | 1        | 4%      |
| Kllisre RAM DDR2 2G 2GB DIMM DDR2 800MT/s                | 1        | 4%      |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 1        | 4%      |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 4%      |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s        | 1        | 4%      |
| A-DATA RAM DDR4 2666 2OZ 16GB DIMM DDR4 2667MT/s         | 1        | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 31.58%  |
| DDR4    | 4        | 21.05%  |
| SDRAM   | 2        | 10.53%  |
| DDR2    | 2        | 10.53%  |
| DDR     | 2        | 10.53%  |
| Unknown | 2        | 10.53%  |
| DDR5    | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 17       | 89.47%  |
| SODIMM | 2        | 10.53%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 6        | 27.27%  |
| 16384 | 4        | 18.18%  |
| 1024  | 4        | 18.18%  |
| 4096  | 3        | 13.64%  |
| 512   | 3        | 13.64%  |
| 32768 | 1        | 4.55%   |
| 8192  | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 19.05%  |
| 3534    | 2        | 9.52%   |
| 2400    | 2        | 9.52%   |
| 800     | 2        | 9.52%   |
| 667     | 2        | 9.52%   |
| Unknown | 2        | 9.52%   |
| 4800    | 1        | 4.76%   |
| 3200    | 1        | 4.76%   |
| 2667    | 1        | 4.76%   |
| 2048    | 1        | 4.76%   |
| 1333    | 1        | 4.76%   |
| 400     | 1        | 4.76%   |
| 333     | 1        | 4.76%   |

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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 15       | 75%     |
| 2     | 2        | 10%     |
| 1     | 2        | 10%     |
| 3     | 1        | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 55.56%  |
| Communication controller | 2        | 22.22%  |
| Net/ethernet             | 1        | 11.11%  |
| Modem                    | 1        | 11.11%  |

