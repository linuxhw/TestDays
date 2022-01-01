LinuxFX 11 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for LinuxFX 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| Foxconn  | D270S/D250S MP       | [82580ebcb5](https://linux-hardware.org/?probe=82580ebcb5) | Dec 28, 2021 |
| MSI      | X470 GAMING PLUS MAX | [dd7335ec13](https://linux-hardware.org/?probe=dd7335ec13) | Dec 27, 2021 |
| Gigabyte | GA-970A-D3           | [135d34c579](https://linux-hardware.org/?probe=135d34c579) | Dec 26, 2021 |
| Gigabyte | GA-970A-D3           | [84b16824bd](https://linux-hardware.org/?probe=84b16824bd) | Dec 26, 2021 |
| ASRock   | N68-S3 UCC           | [ae1acd8bbe](https://linux-hardware.org/?probe=ae1acd8bbe) | Dec 24, 2021 |
| HP       | 2AF7                 | [3b7ab440c6](https://linux-hardware.org/?probe=3b7ab440c6) | Dec 23, 2021 |
| Pegatron | Maureen              | [4bb6b10ba4](https://linux-hardware.org/?probe=4bb6b10ba4) | Dec 23, 2021 |
| Positivo | POS-EIBTPDC          | [882c4d6758](https://linux-hardware.org/?probe=882c4d6758) | Dec 17, 2021 |
| Dell     | 0R6JMP A00           | [7bc4106877](https://linux-hardware.org/?probe=7bc4106877) | Dec 12, 2021 |
| Dell     | 0R6JMP A00           | [2b3e03c89b](https://linux-hardware.org/?probe=2b3e03c89b) | Dec 12, 2021 |
| ASUSTek  | CM6650               | [ef34d60843](https://linux-hardware.org/?probe=ef34d60843) | Dec 09, 2021 |
| Dell     | 040DDP A01           | [6808d41bfe](https://linux-hardware.org/?probe=6808d41bfe) | Dec 08, 2021 |
| Gigabyte | GA-970A-D3           | [543f25da6d](https://linux-hardware.org/?probe=543f25da6d) | Dec 06, 2021 |
| ASUSTek  | H110-PLUS            | [78a4619b31](https://linux-hardware.org/?probe=78a4619b31) | Dec 05, 2021 |
| Gigabyte | GA-970A-D3           | [f4b7b56b1b](https://linux-hardware.org/?probe=f4b7b56b1b) | Dec 05, 2021 |
| Acer     | Aspire X1930         | [68d51a9af5](https://linux-hardware.org/?probe=68d51a9af5) | Dec 03, 2021 |
| Intel    | H55                  | [57390a46ad](https://linux-hardware.org/?probe=57390a46ad) | Dec 02, 2021 |
| ASRock   | Q1900-ITX            | [878cd074fb](https://linux-hardware.org/?probe=878cd074fb) | Nov 30, 2021 |
| ASRock   | Q1900-ITX            | [3468f76ee4](https://linux-hardware.org/?probe=3468f76ee4) | Nov 30, 2021 |
| Positivo | POS-EIBTPDC          | [1e36050d80](https://linux-hardware.org/?probe=1e36050d80) | Nov 18, 2021 |
| Positivo | POS-PIQ67CG POSITIVO | [bcec39d0de](https://linux-hardware.org/?probe=bcec39d0de) | Nov 16, 2021 |
| Positivo | POS-PIQ67CG POSITIVO | [8f7dd03e2d](https://linux-hardware.org/?probe=8f7dd03e2d) | Nov 15, 2021 |
| HP       | 8054                 | [0a502d18dd](https://linux-hardware.org/?probe=0a502d18dd) | Nov 03, 2021 |
| ASUSTek  | M5A78L-M PLUS/USB3   | [24fe21040d](https://linux-hardware.org/?probe=24fe21040d) | Oct 30, 2021 |
| Pegatron | 2A99                 | [29fd6eae29](https://linux-hardware.org/?probe=29fd6eae29) | Oct 27, 2021 |
| Gigabyte | B85-HD3-A            | [23bb246149](https://linux-hardware.org/?probe=23bb246149) | Oct 20, 2021 |
| Gigabyte | H61M-S2PV            | [d08969a0a4](https://linux-hardware.org/?probe=d08969a0a4) | Oct 17, 2021 |
| Intel    | DG35EC AAE29266-202  | [d61f31abf0](https://linux-hardware.org/?probe=d61f31abf0) | Oct 10, 2021 |
| Intel    | DG35EC AAE29266-202  | [24fa8f8f31](https://linux-hardware.org/?probe=24fa8f8f31) | Oct 10, 2021 |
| MSI      | P67A-GD65            | [13a07c6b4d](https://linux-hardware.org/?probe=13a07c6b4d) | Oct 09, 2021 |
| MSI      | P67A-GD65            | [78c9f06350](https://linux-hardware.org/?probe=78c9f06350) | Oct 08, 2021 |
| MSI      | 970 GAMING           | [0778440642](https://linux-hardware.org/?probe=0778440642) | Oct 02, 2021 |
| Intel    | DG35EC AAE29266-202  | [74d233db8b](https://linux-hardware.org/?probe=74d233db8b) | Oct 02, 2021 |
| Intel    | DG35EC AAE29266-202  | [f29471dfd6](https://linux-hardware.org/?probe=f29471dfd6) | Oct 01, 2021 |
| Dell     | 0DN075               | [1d0145e3e0](https://linux-hardware.org/?probe=1d0145e3e0) | Oct 01, 2021 |
| MSI      | G31TM-P25            | [efe15b35ca](https://linux-hardware.org/?probe=efe15b35ca) | Sep 29, 2021 |
| ASRock   | A55M-HVS             | [3061a2007b](https://linux-hardware.org/?probe=3061a2007b) | Sep 27, 2021 |
| ASRock   | A55M-HVS             | [4748ccb729](https://linux-hardware.org/?probe=4748ccb729) | Sep 25, 2021 |
| ASRock   | A55M-HVS             | [a367ec462a](https://linux-hardware.org/?probe=a367ec462a) | Sep 23, 2021 |
| ASRock   | A55M-HVS             | [f0081639fb](https://linux-hardware.org/?probe=f0081639fb) | Sep 22, 2021 |
| MSI      | P67A-GD65            | [b23b139081](https://linux-hardware.org/?probe=b23b139081) | Sep 20, 2021 |
| MSI      | P67A-GD65            | [e42a9da750](https://linux-hardware.org/?probe=e42a9da750) | Sep 20, 2021 |
| Gigabyte | 970A-D3              | [8daebb1450](https://linux-hardware.org/?probe=8daebb1450) | Sep 19, 2021 |
| MSI      | Z270-A PRO           | [6488569b77](https://linux-hardware.org/?probe=6488569b77) | Sep 19, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-41-generic | 6        | 20.69%  |
| 5.11.0-37-generic | 6        | 20.69%  |
| 5.11.0-40-generic | 5        | 17.24%  |
| 5.11.0-43-generic | 4        | 13.79%  |
| 5.11.0-38-generic | 4        | 13.79%  |
| 5.11.0-34-generic | 3        | 10.34%  |
| 5.11.0-36-generic | 1        | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 28       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 28       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 28       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 26       | 89.66%  |
| KDE  | 3        | 10.34%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 28       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 71.43%  |
| SDDM    | 8        | 28.57%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| pt_BR | 7        | 25%     |
| en_US | 7        | 25%     |
| en_GB | 2        | 7.14%   |
| en_CA | 2        | 7.14%   |
| C     | 2        | 7.14%   |
| sv_SE | 1        | 3.57%   |
| ru_RU | 1        | 3.57%   |
| it_IT | 1        | 3.57%   |
| fr_FR | 1        | 3.57%   |
| es_MX | 1        | 3.57%   |
| es_ES | 1        | 3.57%   |
| es_AR | 1        | 3.57%   |
| en_IN | 1        | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 20       | 71.43%  |
| EFI  | 8        | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 26       | 92.86%  |
| Overlay | 2        | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 96.43%  |
| GPT     | 1        | 3.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 85.71%  |
| Yes       | 4        | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 78.57%  |
| Yes       | 6        | 21.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 5        | 17.86%  |
| Gigabyte Technology | 4        | 14.29%  |
| Dell                | 3        | 10.71%  |
| ASUSTek Computer    | 3        | 10.71%  |
| ASRock              | 3        | 10.71%  |
| Positivo            | 2        | 7.14%   |
| Pegatron            | 2        | 7.14%   |
| Intel               | 2        | 7.14%   |
| Hewlett-Packard     | 2        | 7.14%   |
| Foxconn             | 1        | 3.57%   |
| Acer                | 1        | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Positivo POS-PIQ67CG           | 1        | 3.57%   |
| Positivo POS-EIBTPDC           | 1        | 3.57%   |
| Pegatron p6745br               | 1        | 3.57%   |
| Pegatron NC045AA-ABU IQ525uk   | 1        | 3.57%   |
| MSI MS-7B79                    | 1        | 3.57%   |
| MSI MS-7A71                    | 1        | 3.57%   |
| MSI MS-7693                    | 1        | 3.57%   |
| MSI MS-7681                    | 1        | 3.57%   |
| MSI MS-7529                    | 1        | 3.57%   |
| Intel H55                      | 1        | 3.57%   |
| Intel DG35EC AAE29266-202      | 1        | 3.57%   |
| HP EliteDesk 800 G2 SFF        | 1        | 3.57%   |
| HP 700-214                     | 1        | 3.57%   |
| Gigabyte H61M-S2PV             | 1        | 3.57%   |
| Gigabyte GA-970A-D3            | 1        | 3.57%   |
| Gigabyte 970A-D3               | 1        | 3.57%   |
| Gigabyte 7200-5121B            | 1        | 3.57%   |
| Foxconn D270S/D250S MP         | 1        | 3.57%   |
| Dell Precision WorkStation 390 | 1        | 3.57%   |
| Dell OptiPlex 3020             | 1        | 3.57%   |
| Dell Inspiron 3670             | 1        | 3.57%   |
| ASUS M5A78L-M PLUS/USB3        | 1        | 3.57%   |
| ASUS H110-PLUS                 | 1        | 3.57%   |
| ASUS CM6650                    | 1        | 3.57%   |
| ASRock Q1900-ITX               | 1        | 3.57%   |
| ASRock N68-S3 UCC              | 1        | 3.57%   |
| ASRock A55M-HVS                | 1        | 3.57%   |
| Acer Aspire X1930              | 1        | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Positivo POS-PIQ67CG | 1        | 3.57%   |
| Positivo POS-EIBTPDC | 1        | 3.57%   |
| Pegatron p6745br     | 1        | 3.57%   |
| Pegatron NC045AA-ABU | 1        | 3.57%   |
| MSI MS-7B79          | 1        | 3.57%   |
| MSI MS-7A71          | 1        | 3.57%   |
| MSI MS-7693          | 1        | 3.57%   |
| MSI MS-7681          | 1        | 3.57%   |
| MSI MS-7529          | 1        | 3.57%   |
| Intel H55            | 1        | 3.57%   |
| Intel DG35EC         | 1        | 3.57%   |
| HP EliteDesk         | 1        | 3.57%   |
| HP 700-214           | 1        | 3.57%   |
| Gigabyte H61M-S2PV   | 1        | 3.57%   |
| Gigabyte GA-970A-D3  | 1        | 3.57%   |
| Gigabyte 970A-D3     | 1        | 3.57%   |
| Gigabyte 7200-5121B  | 1        | 3.57%   |
| Foxconn D270S        | 1        | 3.57%   |
| Dell Precision       | 1        | 3.57%   |
| Dell OptiPlex        | 1        | 3.57%   |
| Dell Inspiron        | 1        | 3.57%   |
| ASUS M5A78L-M        | 1        | 3.57%   |
| ASUS H110-PLUS       | 1        | 3.57%   |
| ASUS CM6650          | 1        | 3.57%   |
| ASRock Q1900-ITX     | 1        | 3.57%   |
| ASRock N68-S3        | 1        | 3.57%   |
| ASRock A55M-HVS      | 1        | 3.57%   |
| Acer Aspire          | 1        | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 6        | 21.43%  |
| 2014 | 4        | 14.29%  |
| 2012 | 3        | 10.71%  |
| 2021 | 2        | 7.14%   |
| 2018 | 2        | 7.14%   |
| 2015 | 2        | 7.14%   |
| 2010 | 2        | 7.14%   |
| 2008 | 2        | 7.14%   |
| 2020 | 1        | 3.57%   |
| 2019 | 1        | 3.57%   |
| 2017 | 1        | 3.57%   |
| 2016 | 1        | 3.57%   |
| 2013 | 1        | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 28       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 27       | 96.43%  |
| Enabled  | 1        | 3.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 7        | 25%     |
| 3.01-4.0   | 6        | 21.43%  |
| 16.01-24.0 | 6        | 21.43%  |
| 4.01-8.0   | 4        | 14.29%  |
| 32.01-64.0 | 2        | 7.14%   |
| 1.01-2.0   | 2        | 7.14%   |
| 24.01-32.0 | 1        | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 11       | 39.29%  |
| 2.01-3.0  | 7        | 25%     |
| 0.51-1.0  | 4        | 14.29%  |
| 4.01-8.0  | 2        | 7.14%   |
| 3.01-4.0  | 2        | 7.14%   |
| 8.01-16.0 | 2        | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 51.72%  |
| 2      | 9        | 31.03%  |
| 3      | 4        | 13.79%  |
| 5      | 1        | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 60.71%  |
| No        | 11       | 39.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 51.72%  |
| No        | 14       | 48.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 67.86%  |
| Yes       | 9        | 32.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 25%     |
| Brazil      | 7        | 25%     |
| Canada      | 3        | 10.71%  |
| UK          | 1        | 3.57%   |
| Sweden      | 1        | 3.57%   |
| Spain       | 1        | 3.57%   |
| Russia      | 1        | 3.57%   |
| Puerto Rico | 1        | 3.57%   |
| Poland      | 1        | 3.57%   |
| Namibia     | 1        | 3.57%   |
| Mexico      | 1        | 3.57%   |
| Italy       | 1        | 3.57%   |
| India       | 1        | 3.57%   |
| Argentina   | 1        | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Rio de Janeiro      | 3        | 10.71%  |
| Windhoek            | 1        | 3.57%   |
| Toronto             | 1        | 3.57%   |
| Stockholm           | 1        | 3.57%   |
| S??o Paulo          | 1        | 3.57%   |
| Saloa               | 1        | 3.57%   |
| Port Coquitlam      | 1        | 3.57%   |
| Patchogue           | 1        | 3.57%   |
| Niter??i            | 1        | 3.57%   |
| Newcastle upon Tyne | 1        | 3.57%   |
| Newburgh            | 1        | 3.57%   |
| Missoula            | 1        | 3.57%   |
| Madrid              | 1        | 3.57%   |
| Lares               | 1        | 3.57%   |
| Kochi               | 1        | 3.57%   |
| Holmen              | 1        | 3.57%   |
| Guadalajara         | 1        | 3.57%   |
| Genoa               | 1        | 3.57%   |
| Duluth              | 1        | 3.57%   |
| Chorz??w            | 1        | 3.57%   |
| Chicago             | 1        | 3.57%   |
| Campinas            | 1        | 3.57%   |
| Buenos Aires        | 1        | 3.57%   |
| Brampton            | 1        | 3.57%   |
| Bolshoy Kamen       | 1        | 3.57%   |
| Battle Creek        | 1        | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 16     | 30.23%  |
| WDC                 | 10       | 13     | 23.26%  |
| Samsung Electronics | 5        | 5      | 11.63%  |
| SanDisk             | 4        | 4      | 9.3%    |
| Toshiba             | 2        | 2      | 4.65%   |
| SPCC                | 1        | 1      | 2.33%   |
| SATAFIRM            | 1        | 1      | 2.33%   |
| OCZ                 | 1        | 1      | 2.33%   |
| MAXTOR              | 1        | 1      | 2.33%   |
| Kingston            | 1        | 1      | 2.33%   |
| JMicron             | 1        | 1      | 2.33%   |
| Crucial             | 1        | 1      | 2.33%   |
| AFOX                | 1        | 1      | 2.33%   |
| A-DATA Technology   | 1        | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB      | 3        | 6.38%   |
| SanDisk SDSSDX240GG25 240GB         | 2        | 4.26%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1        | 2.13%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1        | 2.13%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 2.13%   |
| WDC WDBNCE5000PNC 500GB SSD         | 1        | 2.13%   |
| WDC WD5000AAKS-75A7B2 500GB         | 1        | 2.13%   |
| WDC WD3200AAKS-61L9A0 320GB         | 1        | 2.13%   |
| WDC WD30EZRZ-00WN9B0 3TB            | 1        | 2.13%   |
| WDC WD20EADS-00R6B0 2TB             | 1        | 2.13%   |
| WDC WD1600JB-32FUA0 160GB           | 1        | 2.13%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 2.13%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 2.13%   |
| WDC WD1001FALS-00J7B0 1TB           | 1        | 2.13%   |
| Toshiba MQ01ABD050 500GB            | 1        | 2.13%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1        | 2.13%   |
| SPCC Solid State Disk 128GB         | 1        | 2.13%   |
| Seagate ST500LT012-9WS142 500GB     | 1        | 2.13%   |
| Seagate ST500DM009-2F110A 500GB     | 1        | 2.13%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 2.13%   |
| Seagate ST3750640NS 752GB           | 1        | 2.13%   |
| Seagate ST3160811AS 160GB           | 1        | 2.13%   |
| Seagate ST31000528AS 1TB            | 1        | 2.13%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 2.13%   |
| Seagate ST2000DM 008-2FR102 2TB     | 1        | 2.13%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 2.13%   |
| Seagate Expansion Desk 5TB          | 1        | 2.13%   |
| Seagate Expansion 1TB               | 1        | 2.13%   |
| Seagate Backup+ Hub BK 8TB          | 1        | 2.13%   |
| SATAFIRM S11 500GB                  | 1        | 2.13%   |
| SanDisk SDSSDA120G 120GB            | 1        | 2.13%   |
| SanDisk SD8SBAT128G1122 128GB SSD   | 1        | 2.13%   |
| Samsung SSD 860 EVO 500GB           | 1        | 2.13%   |
| Samsung SSD 840 Series 120GB        | 1        | 2.13%   |
| Samsung SSD 840 EVO 500GB mSATA     | 1        | 2.13%   |
| Samsung HD103SJ 1TB                 | 1        | 2.13%   |
| Samsung HD103SI 1TB                 | 1        | 2.13%   |
| OCZ AGILITY3 64GB SSD               | 1        | 2.13%   |
| MAXTOR 6V080E0 81GB                 | 1        | 2.13%   |
| Kingston SA400S37480G 480GB SSD     | 1        | 2.13%   |
| JMicron Disk 250GB                  | 1        | 2.13%   |
| Crucial CT1000MX500SSD1 1TB         | 1        | 2.13%   |
| AFOX 120GB                          | 1        | 2.13%   |
| A-DATA SP600 256GB SSD              | 1        | 2.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 15     | 50%     |
| WDC                 | 7        | 9      | 26.92%  |
| Samsung Electronics | 2        | 2      | 7.69%   |
| Toshiba             | 1        | 1      | 3.85%   |
| SATAFIRM            | 1        | 1      | 3.85%   |
| MAXTOR              | 1        | 1      | 3.85%   |
| JMicron             | 1        | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 4        | 4      | 26.67%  |
| WDC                 | 3        | 3      | 20%     |
| Samsung Electronics | 3        | 3      | 20%     |
| SPCC                | 1        | 1      | 6.67%   |
| OCZ                 | 1        | 1      | 6.67%   |
| Kingston            | 1        | 1      | 6.67%   |
| Crucial             | 1        | 1      | 6.67%   |
| A-DATA Technology   | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 18       | 30     | 51.43%  |
| SSD     | 13       | 15     | 37.14%  |
| NVMe    | 2        | 2      | 5.71%   |
| Unknown | 2        | 2      | 5.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 28       | 42     | 82.35%  |
| SAS  | 4        | 5      | 11.76%  |
| NVMe | 2        | 2      | 5.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 25     | 57.14%  |
| 0.51-1.0   | 10       | 15     | 28.57%  |
| 1.01-2.0   | 3        | 3      | 8.57%   |
| 2.01-3.0   | 1        | 1      | 2.86%   |
| 4.01-10.0  | 1        | 1      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 6        | 21.43%  |
| 101-250        | 6        | 21.43%  |
| 501-1000       | 5        | 17.86%  |
| 21-50          | 4        | 14.29%  |
| 1001-2000      | 3        | 10.71%  |
| More than 3000 | 1        | 3.57%   |
| 2001-3000      | 1        | 3.57%   |
| 1-20           | 1        | 3.57%   |
| 51-100         | 1        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 13       | 44.83%  |
| 1-20      | 6        | 20.69%  |
| 51-100    | 5        | 17.24%  |
| 251-500   | 2        | 6.9%    |
| 101-250   | 2        | 6.9%    |
| 2001-3000 | 1        | 3.45%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 27       | 47     | 96.43%  |
| Works    | 1        | 2      | 3.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 19       | 54.29%  |
| AMD                           | 6        | 17.14%  |
| Nvidia                        | 2        | 5.71%   |
| JMicron Technology            | 2        | 5.71%   |
| Toshiba America Info Systems  | 1        | 2.86%   |
| Sandisk                       | 1        | 2.86%   |
| Promise Technology            | 1        | 2.86%   |
| Marvell Technology Group      | 1        | 2.86%   |
| Integrated Technology Express | 1        | 2.86%   |
| ASMedia Technology            | 1        | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 6.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 6.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 6.52%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 4.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 4.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 4.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 4.35%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 2.17%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 2.17%   |
| Promise PDC20262 (FastTrak66/Ultra66)                                                   | 1        | 2.17%   |
| Nvidia MCP61 IDE                                                                        | 1        | 2.17%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 2.17%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 2.17%   |
| JMicron JMB368 IDE controller                                                           | 1        | 2.17%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 2.17%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 2.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1        | 2.17%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 2.17%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 2.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.17%   |
| Integrated Express IT8212 Dual channel ATA RAID controller                              | 1        | 2.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.17%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 2.17%   |
| AMD FCH IDE Controller                                                                  | 1        | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 21       | 56.76%  |
| IDE  | 12       | 32.43%  |
| RAID | 2        | 5.41%   |
| NVMe | 2        | 5.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 71.43%  |
| AMD    | 8        | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 2        | 7.14%   |
| AMD FX-8350 Eight-Core Processor        | 2        | 7.14%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz  | 1        | 3.57%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1        | 3.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 3.57%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 1        | 3.57%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 1        | 3.57%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1        | 3.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1        | 3.57%   |
| Intel Core i5-2310 CPU @ 2.90GHz        | 1        | 3.57%   |
| Intel Core i5-2300 CPU @ 2.80GHz        | 1        | 3.57%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 1        | 3.57%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 1        | 3.57%   |
| Intel Core i3 CPU 530 @ 2.93GHz         | 1        | 3.57%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz   | 1        | 3.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 1        | 3.57%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz    | 1        | 3.57%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 1        | 3.57%   |
| Intel Celeron CPU J1800 @ 2.41GHz       | 1        | 3.57%   |
| Intel Atom CPU D2700 @ 2.13GHz          | 1        | 3.57%   |
| AMD Ryzen 5 3600 6-Core Processor       | 1        | 3.57%   |
| AMD Phenom II X4 830 Processor          | 1        | 3.57%   |
| AMD Phenom II X2 565 Processor          | 1        | 3.57%   |
| AMD FX-6100 Six-Core Processor          | 1        | 3.57%   |
| AMD Athlon II X2 220 Processor          | 1        | 3.57%   |
| AMD A8-3850 APU with Radeon HD Graphics | 1        | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 8        | 28.57%  |
| Intel Core i3      | 3        | 10.71%  |
| AMD FX             | 3        | 10.71%  |
| Intel Core i7      | 2        | 7.14%   |
| Intel Core 2 Quad  | 2        | 7.14%   |
| Intel Celeron      | 2        | 7.14%   |
| Intel Pentium Dual | 1        | 3.57%   |
| Intel Core 2 Duo   | 1        | 3.57%   |
| Intel Atom         | 1        | 3.57%   |
| AMD Ryzen 5        | 1        | 3.57%   |
| AMD Phenom II X4   | 1        | 3.57%   |
| AMD Phenom II X2   | 1        | 3.57%   |
| AMD Athlon II X2   | 1        | 3.57%   |
| AMD A8             | 1        | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 16       | 57.14%  |
| 2      | 9        | 32.14%  |
| 6      | 2        | 7.14%   |
| 3      | 1        | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 64.29%  |
| 2      | 10       | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 28       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 3        | 10.71%  |
| 0x010000c8 | 3        | 10.71%  |
| 0x506e3    | 2        | 7.14%   |
| 0x306a9    | 2        | 7.14%   |
| 0x06000852 | 2        | 7.14%   |
| Unknown    | 2        | 7.14%   |
| 0x906ed    | 1        | 3.57%   |
| 0x906e9    | 1        | 3.57%   |
| 0x6fd      | 1        | 3.57%   |
| 0x6fb      | 1        | 3.57%   |
| 0x306c3    | 1        | 3.57%   |
| 0x30678    | 1        | 3.57%   |
| 0x30673    | 1        | 3.57%   |
| 0x30661    | 1        | 3.57%   |
| 0x20652    | 1        | 3.57%   |
| 0x1067a    | 1        | 3.57%   |
| 0x10676    | 1        | 3.57%   |
| 0x08701021 | 1        | 3.57%   |
| 0x0600063e | 1        | 3.57%   |
| 0x03000027 | 1        | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 3        | 10.71%  |
| K10         | 3        | 10.71%  |
| Haswell     | 3        | 10.71%  |
| Skylake     | 2        | 7.14%   |
| Silvermont  | 2        | 7.14%   |
| Piledriver  | 2        | 7.14%   |
| Penryn      | 2        | 7.14%   |
| KabyLake    | 2        | 7.14%   |
| IvyBridge   | 2        | 7.14%   |
| Core        | 2        | 7.14%   |
| Zen 2       | 1        | 3.57%   |
| Westmere    | 1        | 3.57%   |
| K10 Llano   | 1        | 3.57%   |
| Bulldozer   | 1        | 3.57%   |
| Bonnell     | 1        | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 12       | 38.71%  |
| Nvidia | 11       | 35.48%  |
| AMD    | 8        | 25.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 6.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 6.45%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 3.23%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 3.23%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 3.23%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 3.23%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 3.23%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 3.23%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 3.23%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 3.23%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.23%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 3.23%   |
| Nvidia G96CM [GeForce 9600M GS]                                             | 1        | 3.23%   |
| Intel HD Graphics 630                                                       | 1        | 3.23%   |
| Intel HD Graphics 530                                                       | 1        | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 3.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 3.23%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 3.23%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 3.23%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.23%   |
| AMD Sumo [Radeon HD 6550D]                                                  | 1        | 3.23%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 3.23%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 3.23%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 3.23%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 3.23%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 10       | 35.71%  |
| 1 x Intel      | 9        | 32.14%  |
| 1 x AMD        | 8        | 28.57%  |
| Intel + Nvidia | 1        | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 23       | 82.14%  |
| Proprietary | 4        | 14.29%  |
| Unknown     | 1        | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 35.71%  |
| 1.01-2.0   | 5        | 17.86%  |
| 0.51-1.0   | 5        | 17.86%  |
| 0.01-0.5   | 3        | 10.71%  |
| 3.01-4.0   | 2        | 7.14%   |
| 7.01-8.0   | 1        | 3.57%   |
| 5.01-6.0   | 1        | 3.57%   |
| 2.01-3.0   | 1        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 17.24%  |
| Philips              | 3        | 10.34%  |
| Hewlett-Packard      | 3        | 10.34%  |
| Goldstar             | 3        | 10.34%  |
| AOC                  | 3        | 10.34%  |
| Ancor Communications | 3        | 10.34%  |
| Dell                 | 2        | 6.9%    |
| ___                  | 1        | 3.45%   |
| ViewSonic            | 1        | 3.45%   |
| Tech Concepts        | 1        | 3.45%   |
| Microstep            | 1        | 3.45%   |
| Insignia             | 1        | 3.45%   |
| BenQ                 | 1        | 3.45%   |
| Unknown              | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ___ AAA ___01FF 1366x768 700x390mm 31.5-inch                          | 1        | 3.23%   |
| ViewSonic LCD Monitor VSCDE2E 1920x1080 520x290mm 23.4-inch           | 1        | 3.23%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                            | 1        | 3.23%   |
| Samsung Electronics T24C310 SAM0AEA 1920x1080 531x299mm 24.0-inch     | 1        | 3.23%   |
| Samsung Electronics SMT22A550 SAM07AE 1920x1080 477x268mm 21.5-inch   | 1        | 3.23%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch     | 1        | 3.23%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                      | 1        | 3.23%   |
| Samsung Electronics LCD Monitor S24B300 3840x1080                     | 1        | 3.23%   |
| Philips PHL 241P4 PHL08D5 1920x1080 531x299mm 24.0-inch               | 1        | 3.23%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch             | 1        | 3.23%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 1        | 3.23%   |
| Microstep LCD Monitor MSI MAG341CQ 3440x1440                          | 1        | 3.23%   |
| Insignia NS28D310NA15 BBY0028 1680x1050 640x384mm 29.4-inch           | 1        | 3.23%   |
| Hewlett-Packard v185e HWP2838 1366x768 410x230mm 18.5-inch            | 1        | 3.23%   |
| Hewlett-Packard LCD Monitor w2338h                                    | 1        | 3.23%   |
| Hewlett-Packard Compaq W185q HWP284F 1366x768 410x230mm 18.5-inch     | 1        | 3.23%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                  | 1        | 3.23%   |
| Goldstar RZ32LZ55 GSM7546 1360x768 930x523mm 42.0-inch                | 1        | 3.23%   |
| Goldstar M237WDP GSM5778 1920x1080 510x290mm 23.1-inch                | 1        | 3.23%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1        | 3.23%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                 | 1        | 3.23%   |
| Dell DELL2407WFPHC DELA026 1920x1200 519x324mm 24.1-inch              | 1        | 3.23%   |
| BenQ FP71V+ BNQ76A2 1280x1024 376x301mm 19.0-inch                     | 1        | 3.23%   |
| AOC e2752Vq AOC2752 1920x1080 598x336mm 27.0-inch                     | 1        | 3.23%   |
| AOC 519W AOC1519 1280x720 340x270mm 17.1-inch                         | 1        | 3.23%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 1        | 3.23%   |
| Ancor Communications VG248 ACI24E1 1680x1050 530x300mm 24.0-inch      | 1        | 3.23%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 1        | 3.23%   |
| Ancor Communications MW221 ACI22B1 1680x1050 473x296mm 22.0-inch      | 1        | 3.23%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch | 1        | 3.23%   |
| Unknown                                                               | 1        | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 39.29%  |
| 1366x768 (WXGA)    | 5        | 17.86%  |
| 1360x768           | 3        | 10.71%  |
| 3840x2160 (4K)     | 1        | 3.57%   |
| 3840x1080          | 1        | 3.57%   |
| 3440x1440          | 1        | 3.57%   |
| 1920x1200 (WUXGA)  | 1        | 3.57%   |
| 1680x1050 (WSXGA+) | 1        | 3.57%   |
| 1600x900 (HD+)     | 1        | 3.57%   |
| 1280x720 (HD)      | 1        | 3.57%   |
| 1280x1024 (SXGA)   | 1        | 3.57%   |
| Unknown            | 1        | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 17.24%  |
| 27      | 4        | 13.79%  |
| 18      | 4        | 13.79%  |
| 31      | 3        | 10.34%  |
| 21      | 3        | 10.34%  |
| Unknown | 3        | 10.34%  |
| 23      | 2        | 6.9%    |
| 19      | 2        | 6.9%    |
| 42      | 1        | 3.45%   |
| 22      | 1        | 3.45%   |
| 17      | 1        | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 33.33%  |
| 401-500     | 9        | 33.33%  |
| 601-700     | 3        | 11.11%  |
| Unknown     | 3        | 11.11%  |
| 351-400     | 1        | 3.7%    |
| 301-350     | 1        | 3.7%    |
| 901-1000    | 1        | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 73.08%  |
| Unknown | 3        | 11.54%  |
| 5/4     | 2        | 7.69%   |
| 16/10   | 2        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 28.57%  |
| 141-150        | 5        | 17.86%  |
| 301-350        | 4        | 14.29%  |
| 351-500        | 3        | 10.71%  |
| 151-200        | 3        | 10.71%  |
| Unknown        | 3        | 10.71%  |
| 251-300        | 1        | 3.57%   |
| 501-1000       | 1        | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 61.54%  |
| 1-50    | 4        | 15.38%  |
| 101-120 | 3        | 11.54%  |
| Unknown | 3        | 11.54%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 78.57%  |
| 2     | 4        | 14.29%  |
| 3     | 1        | 3.57%   |
| 0     | 1        | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 22       | 51.16%  |
| Intel                           | 6        | 13.95%  |
| Ralink                          | 3        | 6.98%   |
| Qualcomm Atheros                | 3        | 6.98%   |
| TP-Link                         | 2        | 4.65%   |
| Nvidia                          | 2        | 4.65%   |
| Qualcomm Atheros Communications | 1        | 2.33%   |
| Motorola PCS                    | 1        | 2.33%   |
| Huawei Technologies             | 1        | 2.33%   |
| D-Link                          | 1        | 2.33%   |
| Broadcom Limited                | 1        | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 19       | 38.78%  |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 6.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2        | 4.08%   |
| Nvidia MCP61 Ethernet                                                                         | 2        | 4.08%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 4.08%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 2.04%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 2.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 2.04%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1        | 2.04%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 2.04%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.04%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 2.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 2.04%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1        | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 2.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 2.04%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1        | 2.04%   |
| Motorola PCS moto g 5G                                                                        | 1        | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 1        | 2.04%   |
| Intel 82566DC Gigabit Network Connection                                                      | 1        | 2.04%   |
| Huawei E353/E3131                                                                             | 1        | 2.04%   |
| D-Link DWL-G132 [Atheros AR5523]                                                              | 1        | 2.04%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express                               | 1        | 2.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 6        | 33.33%  |
| Ralink                          | 3        | 16.67%  |
| Intel                           | 3        | 16.67%  |
| TP-Link                         | 2        | 11.11%  |
| Qualcomm Atheros                | 2        | 11.11%  |
| Qualcomm Atheros Communications | 1        | 5.56%   |
| D-Link                          | 1        | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 3        | 16.67%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 11.11%  |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 5.56%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 5.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 5.56%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                        | 1        | 5.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 5.56%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 5.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 5.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 5.56%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1        | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 5.56%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 5.56%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]                        | 1        | 5.56%   |
| D-Link DWL-G132 [Atheros AR5523]                                                              | 1        | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 67.74%  |
| Intel                 | 4        | 12.9%   |
| Nvidia                | 2        | 6.45%   |
| Qualcomm Atheros      | 1        | 3.23%   |
| Motorola PCS          | 1        | 3.23%   |
| Huawei Technologies   | 1        | 3.23%   |
| Broadcom Limited      | 1        | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 61.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 6.45%   |
| Nvidia MCP61 Ethernet                                             | 2        | 6.45%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 6.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.23%   |
| Motorola PCS moto g 5G                                            | 1        | 3.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 3.23%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 3.23%   |
| Huawei E353/E3131                                                 | 1        | 3.23%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1        | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 65.12%  |
| WiFi     | 15       | 34.88%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 68.42%  |
| WiFi     | 12       | 31.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 67.86%  |
| 2     | 9        | 32.14%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 60.71%  |
| Yes  | 11       | 39.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 33.33%  |
| Cambridge Silicon Radio         | 2        | 22.22%  |
| Ralink                          | 1        | 11.11%  |
| Qualcomm Atheros Communications | 1        | 11.11%  |
| Hewlett-Packard                 | 1        | 11.11%  |
| ASUSTek Computer                | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 3        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 22.22%  |
| Ralink RT3290 Bluetooth                             | 1        | 11.11%  |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 11.11%  |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1        | 11.11%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 18       | 38.3%   |
| Nvidia                    | 11       | 23.4%   |
| AMD                       | 10       | 21.28%  |
| C-Media Electronics       | 3        | 6.38%   |
| Texas Instruments         | 1        | 2.13%   |
| Sennheiser Communications | 1        | 2.13%   |
| Microsoft                 | 1        | 2.13%   |
| JMTek                     | 1        | 2.13%   |
| Creative Labs             | 1        | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 9.62%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 5.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 3.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 3.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 3.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 3.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 3.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 3.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 3.85%   |
| Texas Instruments PCM2903B Audio CODEC                                     | 1        | 1.92%   |
| Sennheiser Communications PXC 550                                          | 1        | 1.92%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.92%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.92%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.92%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.92%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.92%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.92%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 1.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.92%   |
| Microsoft LifeChat LX-3000 Headset                                         | 1        | 1.92%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.92%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 1.92%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 1.92%   |
| C-Media Electronics Blue Snowball                                          | 1        | 1.92%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 1.92%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 1.92%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.92%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1        | 1.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Corsair | 1        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s | 1        | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 1        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 1        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 1        | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 1        | 100%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Seiko Epson L395 Series | 1        | 100%    |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Logitech                  | 2        | 20%     |
| YGTek                     | 1        | 10%     |
| Silicon Motion            | 1        | 10%     |
| SHENZHEN EMEET TECHNOLOGY | 1        | 10%     |
| Microsoft                 | 1        | 10%     |
| Jieli Technology          | 1        | 10%     |
| HD WEBCAM                 | 1        | 10%     |
| Creative Technology       | 1        | 10%     |
| Chicony Electronics       | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| YGTek Webcam                                   | 1        | 10%     |
| Silicon Motion SM731 Camera                    | 1        | 10%     |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1        | 10%     |
| Microsoft LifeCam VX-500 [1357]                | 1        | 10%     |
| Logitech Webcam C600                           | 1        | 10%     |
| Logitech C922 Pro Stream Webcam                | 1        | 10%     |
| Jieli USB PHY 2.0                              | 1        | 10%     |
| HD WEBCAM HD WEBCAM                            | 1        | 10%     |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 10%     |
| Chicony CNF7042                                | 1        | 10%     |

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
| 0     | 21       | 75%     |
| 1     | 7        | 25%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 4        | 57.14%  |
| Graphics card | 2        | 28.57%  |
| Bluetooth     | 1        | 14.29%  |

