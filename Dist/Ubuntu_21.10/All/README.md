Ubuntu 21.10 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_21.10/Desktop/README.md) and [notebooks](/Dist/Ubuntu_21.10/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-21.10

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Huanan        | X99 F8D V2.2                | Desktop     | [30fe8d6bb3](https://linux-hardware.org/?probe=30fe8d6bb3) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [cae806f49d](https://linux-hardware.org/?probe=cae806f49d) | Aug 22, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [b7af19f2f4](https://linux-hardware.org/?probe=b7af19f2f4) | Aug 20, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f194373e42](https://linux-hardware.org/?probe=f194373e42) | Aug 20, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [1a371ea24e](https://linux-hardware.org/?probe=1a371ea24e) | Aug 16, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [b8aa2e41d5](https://linux-hardware.org/?probe=b8aa2e41d5) | Aug 16, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | Desktop     | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [612dda8fba](https://linux-hardware.org/?probe=612dda8fba) | Aug 13, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [1eb6008b88](https://linux-hardware.org/?probe=1eb6008b88) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [808cfab06b](https://linux-hardware.org/?probe=808cfab06b) | Aug 12, 2021 |
| Lenovo        | ThinkPad T510 4484A63       | Notebook    | [c1bcb3451f](https://linux-hardware.org/?probe=c1bcb3451f) | Aug 09, 2021 |
| Lenovo        | ThinkPad T510 4484A63       | Notebook    | [4336b50906](https://linux-hardware.org/?probe=4336b50906) | Aug 06, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [912b2a77a2](https://linux-hardware.org/?probe=912b2a77a2) | Aug 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [961031411d](https://linux-hardware.org/?probe=961031411d) | Aug 03, 2021 |
| Lenovo        | ZhaoYang K3-ITL 82E3        | Notebook    | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| ASUSTek       | GL753VD                     | Notebook    | [eabe6a8723](https://linux-hardware.org/?probe=eabe6a8723) | Jul 31, 2021 |
| Acer          | Aspire 5920                 | Notebook    | [f41defe215](https://linux-hardware.org/?probe=f41defe215) | Jul 31, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| Teclast       | F6 Pro                      | Notebook    | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [74e4c61bbf](https://linux-hardware.org/?probe=74e4c61bbf) | Jul 23, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [02ad72fb54](https://linux-hardware.org/?probe=02ad72fb54) | Jul 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f5458b4f56](https://linux-hardware.org/?probe=f5458b4f56) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [5ac65f3389](https://linux-hardware.org/?probe=5ac65f3389) | Jul 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [85aadf8abd](https://linux-hardware.org/?probe=85aadf8abd) | Jul 16, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [6a69f09403](https://linux-hardware.org/?probe=6a69f09403) | Jul 15, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b2c80f450e](https://linux-hardware.org/?probe=b2c80f450e) | Jul 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Positivo      | H14BT58                     | Notebook    | [51b9ba65e0](https://linux-hardware.org/?probe=51b9ba65e0) | Jun 18, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [4befd5f360](https://linux-hardware.org/?probe=4befd5f360) | Jun 04, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [4ee08e92ae](https://linux-hardware.org/?probe=4ee08e92ae) | May 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.11.0-20-generic     | 5         | 22.73%  |
| 5.13.0-14-generic     | 3         | 13.64%  |
| 5.13.0-12-generic     | 2         | 9.09%   |
| 5.11.0-25-generic     | 2         | 9.09%   |
| 5.11.0-18-generic     | 2         | 9.09%   |
| 5.13.6-xanmod2-edge   | 1         | 4.55%   |
| 5.13.4-051304-generic | 1         | 4.55%   |
| 5.13.2-051302-generic | 1         | 4.55%   |
| 5.13.0-13-generic     | 1         | 4.55%   |
| 5.13.0-051300-generic | 1         | 4.55%   |
| 5.11.0-26-generic     | 1         | 4.55%   |
| 5.11.0-22-generic     | 1         | 4.55%   |
| 5.11.0-16-generic     | 1         | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 12        | 54.55%  |
| 5.13.0  | 7         | 31.82%  |
| 5.13.6  | 1         | 4.55%   |
| 5.13.4  | 1         | 4.55%   |
| 5.13.2  | 1         | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 54.55%  |
| 5.13    | 10        | 45.45%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 21        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 15        | 71.43%  |
| X-Cinnamon      | 3         | 14.29%  |
| Unity           | 1         | 4.76%   |
| GNOME Flashback | 1         | 4.76%   |
| Cinnamon        | 1         | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 11        | 52.38%  |
| X11     | 10        | 47.62%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 10        | 47.62%  |
| Unknown | 10        | 47.62%  |
| TDM     | 1         | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_GB | 7         | 33.33%  |
| fr_FR | 3         | 14.29%  |
| pt_BR | 2         | 9.52%   |
| en_US | 2         | 9.52%   |
| zh_CN | 1         | 4.76%   |
| sv_SE | 1         | 4.76%   |
| ru_UA | 1         | 4.76%   |
| ru_RU | 1         | 4.76%   |
| ko_KR | 1         | 4.76%   |
| es_MX | 1         | 4.76%   |
| es_AR | 1         | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 11        | 52.38%  |
| BIOS | 10        | 47.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 20        | 95.24%  |
| Btrfs | 1         | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 10        | 47.62%  |
| Unknown | 10        | 47.62%  |
| MBR     | 1         | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 14        | 66.67%  |
| Yes       | 7         | 33.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 61.9%   |
| No        | 8         | 38.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 7         | 33.33%  |
| Lenovo              | 3         | 14.29%  |
| Dell                | 2         | 9.52%   |
| Teclast             | 1         | 4.76%   |
| Positivo            | 1         | 4.76%   |
| MSI                 | 1         | 4.76%   |
| LG Electronics      | 1         | 4.76%   |
| Huanan              | 1         | 4.76%   |
| Hewlett-Packard     | 1         | 4.76%   |
| Gigabyte Technology | 1         | 4.76%   |
| Fujitsu             | 1         | 4.76%   |
| Acer                | 1         | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Teclast F6 Pro                          | 1         | 4.76%   |
| Positivo H14BT58                        | 1         | 4.76%   |
| MSI MS-7C94                             | 1         | 4.76%   |
| LG 22V280-L.BY31P1                      | 1         | 4.76%   |
| Lenovo ZhaoYang K3-ITL 82E3             | 1         | 4.76%   |
| Lenovo Z50-70 20354                     | 1         | 4.76%   |
| Lenovo ThinkPad X201 3626FAG            | 1         | 4.76%   |
| Huanan X99 F8D V2.2                     | 1         | 4.76%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 4.76%   |
| Gigabyte F2A55M-HD2                     | 1         | 4.76%   |
| Fujitsu S1100F                          | 1         | 4.76%   |
| Dell XPS 13 9343                        | 1         | 4.76%   |
| Dell XPS 13 7390                        | 1         | 4.76%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN  | 1         | 4.76%   |
| ASUS VivoBook_ASUSLaptop X509DJ_M509DJ  | 1         | 4.76%   |
| ASUS VivoBook_ASUSLaptop X421UAY_M413UA | 1         | 4.76%   |
| ASUS ROG ZENITH II EXTREME              | 1         | 4.76%   |
| ASUS ROG Strix G533QS_G533QS            | 1         | 4.76%   |
| ASUS ROG Strix G533QR_G533QR            | 1         | 4.76%   |
| ASUS GL753VD                            | 1         | 4.76%   |
| Acer Aspire 5920                        | 1         | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUS VivoBook       | 3         | 14.29%  |
| ASUS ROG            | 3         | 14.29%  |
| Dell XPS            | 2         | 9.52%   |
| Teclast F6          | 1         | 4.76%   |
| Positivo H14BT58    | 1         | 4.76%   |
| MSI MS-7C94         | 1         | 4.76%   |
| LG 22V280-L.BY31P1  | 1         | 4.76%   |
| Lenovo ZhaoYang     | 1         | 4.76%   |
| Lenovo Z50-70       | 1         | 4.76%   |
| Lenovo ThinkPad     | 1         | 4.76%   |
| Huanan X99          | 1         | 4.76%   |
| HP Pavilion         | 1         | 4.76%   |
| Gigabyte F2A55M-HD2 | 1         | 4.76%   |
| Fujitsu S1100F      | 1         | 4.76%   |
| ASUS GL753VD        | 1         | 4.76%   |
| Acer Aspire         | 1         | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 9         | 42.86%  |
| 2020 | 2         | 9.52%   |
| 2019 | 2         | 9.52%   |
| 2018 | 2         | 9.52%   |
| 2017 | 1         | 4.76%   |
| 2015 | 1         | 4.76%   |
| 2014 | 1         | 4.76%   |
| 2013 | 1         | 4.76%   |
| 2010 | 1         | 4.76%   |
| 2008 | 1         | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 15        | 71.43%  |
| Desktop    | 5         | 23.81%  |
| All in one | 1         | 4.76%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 20        | 95.24%  |
| Enabled  | 1         | 4.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 21        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 8         | 36.36%  |
| 32.01-64.0  | 4         | 18.18%  |
| 8.01-16.0   | 3         | 13.64%  |
| 64.01-256.0 | 2         | 9.09%   |
| 16.01-24.0  | 2         | 9.09%   |
| 3.01-4.0    | 1         | 4.55%   |
| 24.01-32.0  | 1         | 4.55%   |
| 1.01-2.0    | 1         | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 8         | 36.36%  |
| 4.01-8.0 | 6         | 27.27%  |
| 1.01-2.0 | 5         | 22.73%  |
| 3.01-4.0 | 3         | 13.64%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 12        | 57.14%  |
| 2      | 5         | 23.81%  |
| 3      | 3         | 14.29%  |
| 5      | 1         | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 85.71%  |
| Yes       | 3         | 14.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 66.67%  |
| No        | 7         | 33.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 80.95%  |
| No        | 4         | 19.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 76.19%  |
| No        | 5         | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| UK          | 5         | 23.81%  |
| France      | 3         | 14.29%  |
| Brazil      | 3         | 14.29%  |
| USA         | 1         | 4.76%   |
| Ukraine     | 1         | 4.76%   |
| Sweden      | 1         | 4.76%   |
| South Korea | 1         | 4.76%   |
| Russia      | 1         | 4.76%   |
| Lithuania   | 1         | 4.76%   |
| Germany     | 1         | 4.76%   |
| China       | 1         | 4.76%   |
| Chile       | 1         | 4.76%   |
| Argentina   | 1         | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Yongin-si              | 1         | 4.76%   |
| Trakai                 | 1         | 4.76%   |
| Tottenham              | 1         | 4.76%   |
| Shanghai               | 1         | 4.76%   |
| S??o Paulo             | 1         | 4.76%   |
| Santiago               | 1         | 4.76%   |
| Rosario                | 1         | 4.76%   |
| Rio de Janeiro         | 1         | 4.76%   |
| Paris                  | 1         | 4.76%   |
| Osasco                 | 1         | 4.76%   |
| Nizhny Tagil           | 1         | 4.76%   |
| Maidstone              | 1         | 4.76%   |
| Lyon                   | 1         | 4.76%   |
| Leiston                | 1         | 4.76%   |
| Kyiv                   | 1         | 4.76%   |
| Helsingborg            | 1         | 4.76%   |
| Haselhorst             | 1         | 4.76%   |
| Glasgow                | 1         | 4.76%   |
| Crewe                  | 1         | 4.76%   |
| Charleville-M?�zi??res | 1         | 4.76%   |
| Austin                 | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 21.21%  |
| Seagate             | 5         | 5      | 15.15%  |
| WDC                 | 2         | 2      | 6.06%   |
| Toshiba             | 2         | 2      | 6.06%   |
| SK Hynix            | 2         | 2      | 6.06%   |
| Sandisk             | 2         | 2      | 6.06%   |
| Kingston            | 2         | 3      | 6.06%   |
| Intel               | 2         | 3      | 6.06%   |
| Unknown             | 1         | 1      | 3.03%   |
| SP                  | 1         | 1      | 3.03%   |
| Silicon Motion      | 1         | 2      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| LITEON              | 1         | 1      | 3.03%   |
| KIOXIA-EXCERIA      | 1         | 1      | 3.03%   |
| KingDian            | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| SK Hynix HFM001TD3JX013N 1TB             | 2         | 5.71%   |
| Seagate Expansion 1TB                    | 2         | 5.71%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 2.86%   |
| WDC WD3200AAJS-56B4A0 320GB              | 1         | 2.86%   |
| Unknown SB64G  64GB                      | 1         | 2.86%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 2.86%   |
| Toshiba HDWL120 2TB                      | 1         | 2.86%   |
| SP PC60 1TB                              | 1         | 2.86%   |
| Silicon Motion NVMe SSD Drive 256GB      | 1         | 2.86%   |
| Seagate ST9320423AS 320GB                | 1         | 2.86%   |
| Seagate BUP Slim BK 1TB                  | 1         | 2.86%   |
| Seagate BarraCuda SSD ZA500CM10002 500GB | 1         | 2.86%   |
| SanDisk SD9SN8W256G1102 256GB SSD        | 1         | 2.86%   |
| Sandisk NVMe SSD Drive 500GB             | 1         | 2.86%   |
| Samsung SSD 980 PRO 500GB                | 1         | 2.86%   |
| Samsung SSD 980 PRO 2TB                  | 1         | 2.86%   |
| Samsung SSD 970 EVO 500GB                | 1         | 2.86%   |
| Samsung SSD 860 EVO 500GB                | 1         | 2.86%   |
| Samsung SSD 850 EVO 500GB                | 1         | 2.86%   |
| Samsung SSD 650 120GB                    | 1         | 2.86%   |
| Samsung MZVLQ512HALU-00000 512GB         | 1         | 2.86%   |
| Samsung MZALQ512HALU-000L2 512GB         | 1         | 2.86%   |
| PNY CS900 240GB SSD                      | 1         | 2.86%   |
| LITEON L8H-256V2G-11 M.2 2280 256GB SSD  | 1         | 2.86%   |
| KIOXIA-EXCERIA SATA SSD 480GB            | 1         | 2.86%   |
| Kingston SKC300S37A240G 240GB SSD        | 1         | 2.86%   |
| Kingston SHFS37A120G 120GB SSD           | 1         | 2.86%   |
| KingDian N400 240GB SSD                  | 1         | 2.86%   |
| Intel NVMe SSD Drive 512GB               | 1         | 2.86%   |
| Intel HBRPEKNX0101AHO 16GB               | 1         | 2.86%   |
| Intel HBRPEKNX0101AH 256GB               | 1         | 2.86%   |
| HGST HTS721010A9E630 1TB                 | 1         | 2.86%   |
| China SATA SSD 240GB                     | 1         | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 2         | 2      | 22.22%  |
| HGST    | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 25%     |
| Kingston            | 2         | 3      | 16.67%  |
| Seagate             | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| PNY                 | 1         | 1      | 8.33%   |
| LITEON              | 1         | 1      | 8.33%   |
| KIOXIA-EXCERIA      | 1         | 1      | 8.33%   |
| KingDian            | 1         | 1      | 8.33%   |
| China               | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 11        | 14     | 35.48%  |
| SSD     | 9         | 13     | 29.03%  |
| HDD     | 9         | 9      | 29.03%  |
| MMC     | 1         | 1      | 3.23%   |
| Unknown | 1         | 1      | 3.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 19     | 46.43%  |
| NVMe | 11        | 14     | 39.29%  |
| SAS  | 3         | 4      | 10.71%  |
| MMC  | 1         | 1      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 16     | 66.67%  |
| 0.51-1.0   | 5         | 5      | 27.78%  |
| 1.01-2.0   | 1         | 1      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 6         | 28.57%  |
| 251-500    | 5         | 23.81%  |
| 51-100     | 4         | 19.05%  |
| 1001-2000  | 3         | 14.29%  |
| 501-1000   | 2         | 9.52%   |
| 21-50      | 1         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 101-250   | 6         | 28.57%  |
| 1-20      | 4         | 19.05%  |
| 51-100    | 4         | 19.05%  |
| 21-50     | 3         | 14.29%  |
| 501-1000  | 2         | 9.52%   |
| 251-500   | 1         | 4.76%   |
| 1001-2000 | 1         | 4.76%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 14        | 20     | 56%     |
| Works    | 11        | 18     | 44%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 13        | 46.43%  |
| Samsung Electronics | 5         | 17.86%  |
| AMD                 | 5         | 17.86%  |
| SK Hynix            | 2         | 7.14%   |
| Silicon Motion      | 1         | 3.57%   |
| Sandisk             | 1         | 3.57%   |
| ASMedia Technology  | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 9.68%   |
| SK Hynix NVMe SSD Controller                                                  | 2         | 6.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 6.45%   |
| Samsung NVMe Controller                                                       | 2         | 6.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 6.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 3.23%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1         | 3.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 3.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 1         | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 3.23%   |
| Intel SSD 660P Series                                                         | 1         | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 3.23%   |
| Intel Non-Volatile memory controller                                          | 1         | 3.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 3.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 3.23%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1         | 3.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 1         | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 3.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 3.23%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1         | 3.23%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                      | 1         | 3.23%   |
| AMD FCH SATA Controller [IDE mode]                                            | 1         | 3.23%   |
| AMD FCH IDE Controller                                                        | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 15        | 50%     |
| NVMe | 11        | 36.67%  |
| RAID | 2         | 6.67%   |
| IDE  | 2         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 14        | 66.67%  |
| AMD    | 7         | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| AMD Ryzen 9 5900HX with Radeon Graphics        | 2         | 9.52%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz            | 1         | 4.76%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz               | 1         | 4.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 4.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 4.76%   |
| Intel Core i7-4510U CPU @ 2.00GHz              | 1         | 4.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 1         | 4.76%   |
| Intel Core i5-9300H CPU @ 2.40GHz              | 1         | 4.76%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 4.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 1         | 4.76%   |
| Intel Core i5 CPU M 540 @ 2.53GHz              | 1         | 4.76%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz           | 1         | 4.76%   |
| Intel Celeron N4100 CPU @ 1.10GHz              | 1         | 4.76%   |
| Intel Celeron CPU N2807 @ 1.58GHz              | 1         | 4.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 4.76%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1         | 4.76%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 4.76%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 1         | 4.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 4.76%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 4         | 19.05%  |
| Intel Core i5          | 4         | 19.05%  |
| AMD Ryzen 5            | 3         | 14.29%  |
| Intel Celeron          | 2         | 9.52%   |
| AMD Ryzen 9            | 2         | 9.52%   |
| Other                  | 1         | 4.76%   |
| Intel Xeon             | 1         | 4.76%   |
| Intel Core m3          | 1         | 4.76%   |
| Intel Core 2 Duo       | 1         | 4.76%   |
| AMD Ryzen Threadripper | 1         | 4.76%   |
| AMD A4                 | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 8         | 38.1%   |
| 2      | 6         | 28.57%  |
| 8      | 2         | 9.52%   |
| 6      | 2         | 9.52%   |
| 32     | 1         | 4.76%   |
| 28     | 1         | 4.76%   |
| 1      | 1         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 95.24%  |
| 2      | 1         | 4.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 80.95%  |
| 1      | 4         | 19.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 21        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 57.14%  |
| 0x906ea    | 1         | 4.76%   |
| 0x906e9    | 1         | 4.76%   |
| 0x806ec    | 1         | 4.76%   |
| 0x806eb    | 1         | 4.76%   |
| 0x806e9    | 1         | 4.76%   |
| 0x806c1    | 1         | 4.76%   |
| 0x306d4    | 1         | 4.76%   |
| 0x0a50000b | 1         | 4.76%   |
| 0x08608103 | 1         | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 28.57%  |
| Zen 3         | 3         | 14.29%  |
| Broadwell     | 2         | 9.52%   |
| Zen+          | 1         | 4.76%   |
| Zen 2         | 1         | 4.76%   |
| Westmere      | 1         | 4.76%   |
| TigerLake     | 1         | 4.76%   |
| Silvermont    | 1         | 4.76%   |
| Piledriver    | 1         | 4.76%   |
| Penryn        | 1         | 4.76%   |
| Haswell       | 1         | 4.76%   |
| Goldmont plus | 1         | 4.76%   |
| Unknown       | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 13        | 46.43%  |
| Nvidia | 10        | 35.71%  |
| AMD    | 5         | 17.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 630                                                | 2         | 6.45%   |
| AMD Cezanne                                                          | 2         | 6.45%   |
| Nvidia NV44 [GeForce 6200 LE]                                        | 1         | 3.23%   |
| Nvidia GP108M [GeForce MX230]                                        | 1         | 3.23%   |
| Nvidia GP108M [GeForce MX150]                                        | 1         | 3.23%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 3.23%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 3.23%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                          | 1         | 3.23%   |
| Nvidia GK208B [GeForce GT 710]                                       | 1         | 3.23%   |
| Nvidia GK104 [GeForce GTX 680]                                       | 1         | 3.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M] | 1         | 3.23%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]             | 1         | 3.23%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 3.23%   |
| Nvidia GA102 [GeForce RTX 3090]                                      | 1         | 3.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)  | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)    | 1         | 3.23%   |
| Intel HD Graphics 615                                                | 1         | 3.23%   |
| Intel HD Graphics 5500                                               | 1         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 1         | 3.23%   |
| Intel GeminiLake [UHD Graphics 600]                                  | 1         | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                  | 1         | 3.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 1         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 1         | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display         | 1         | 3.23%   |
| AMD Trinity 2 [Radeon HD 7480D]                                      | 1         | 3.23%   |
| AMD Picasso                                                          | 1         | 3.23%   |
| AMD Lucienne                                                         | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 9         | 42.86%  |
| Intel + Nvidia | 4         | 19.05%  |
| AMD + Nvidia   | 3         | 14.29%  |
| 2 x Nvidia     | 2         | 9.52%   |
| 1 x AMD        | 2         | 9.52%   |
| 1 x Nvidia     | 1         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 14        | 66.67%  |
| Proprietary | 6         | 28.57%  |
| Unknown     | 1         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 71.43%  |
| 1.01-2.0   | 4         | 19.05%  |
| 0.01-0.5   | 2         | 9.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 3         | 13.04%  |
| AU Optronics        | 3         | 13.04%  |
| Sharp               | 2         | 8.7%    |
| Lenovo              | 2         | 8.7%    |
| Chimei Innolux      | 2         | 8.7%    |
| Acer                | 2         | 8.7%    |
| SKY                 | 1         | 4.35%   |
| Samsung Electronics | 1         | 4.35%   |
| RTK                 | 1         | 4.35%   |
| PANDA               | 1         | 4.35%   |
| LG Electronics      | 1         | 4.35%   |
| LG Display          | 1         | 4.35%   |
| InfoVision          | 1         | 4.35%   |
| Dell                | 1         | 4.35%   |
| AOC                 | 1         | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Acer XV340CK P ACR06F3 3440x1440 800x335mm 34.1-inch                 | 2         | 8.33%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                 | 1         | 4.17%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 4.17%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch | 1         | 4.17%   |
| RTK LCD Monitor RTK2136 1280x800 473x296mm 22.0-inch                 | 1         | 4.17%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch              | 1         | 4.17%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 1         | 4.17%   |
| LG Electronics LCD Monitor LG ULTRAWIDE                              | 1         | 4.17%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 1         | 4.17%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch             | 1         | 4.17%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 4.17%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch         | 1         | 4.17%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                    | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 4.17%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                | 1         | 4.17%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                | 1         | 4.17%   |
| BOE LCD Monitor BOE05EC 1366x768 309x173mm 13.9-inch                 | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch       | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 4.17%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                     | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 12        | 52.17%  |
| 3440x1440         | 2         | 8.7%    |
| 2560x1440 (QHD)   | 2         | 8.7%    |
| 1280x800 (WXGA)   | 2         | 8.7%    |
| 3200x1800 (QHD+)  | 1         | 4.35%   |
| 2560x1080         | 1         | 4.35%   |
| 1920x1200 (WUXGA) | 1         | 4.35%   |
| 1366x768 (WXGA)   | 1         | 4.35%   |
| Unknown           | 1         | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 7         | 30.43%  |
| 13      | 6         | 26.09%  |
| 34      | 2         | 8.7%    |
| 24      | 2         | 8.7%    |
| 40      | 1         | 4.35%   |
| 27      | 1         | 4.35%   |
| 23      | 1         | 4.35%   |
| 17      | 1         | 4.35%   |
| 12      | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 40.91%  |
| 201-300     | 5         | 22.73%  |
| 501-600     | 3         | 13.64%  |
| 701-800     | 2         | 9.09%   |
| 801-900     | 1         | 4.55%   |
| 351-400     | 1         | 4.55%   |
| Unknown     | 1         | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 16        | 69.57%  |
| 16/10   | 3         | 13.04%  |
| 21/9    | 2         | 8.7%    |
| 3/2     | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 30.43%  |
| 71-80          | 4         | 17.39%  |
| 81-90          | 2         | 8.7%    |
| 351-500        | 2         | 8.7%    |
| 201-250        | 2         | 8.7%    |
| 61-70          | 1         | 4.35%   |
| 301-350        | 1         | 4.35%   |
| 251-300        | 1         | 4.35%   |
| 121-130        | 1         | 4.35%   |
| 501-1000       | 1         | 4.35%   |
| Unknown        | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 9         | 40.91%  |
| 161-240       | 4         | 18.18%  |
| 101-120       | 3         | 13.64%  |
| 51-100        | 3         | 13.64%  |
| More than 240 | 1         | 4.55%   |
| 1-50          | 1         | 4.55%   |
| Unknown       | 1         | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 17        | 80.95%  |
| 2     | 3         | 14.29%  |
| 0     | 1         | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 13        | 44.83%  |
| Intel                 | 9         | 31.03%  |
| MEDIATEK              | 2         | 6.9%    |
| Xiaomi                | 1         | 3.45%   |
| Qualcomm Atheros      | 1         | 3.45%   |
| Broadcom Limited      | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |
| Aquantia              | 1         | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 30.3%   |
| MEDIATEK Network controller                                       | 2         | 6.06%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 6.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.03%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 3.03%   |
| Intel Wireless 8265 / 8275                                        | 1         | 3.03%   |
| Intel Wireless 7265                                               | 1         | 3.03%   |
| Intel Wireless 3165                                               | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 3.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 3.03%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 3.03%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 3.03%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.03%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.03%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 3.03%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 52.94%  |
| Realtek Semiconductor | 4         | 23.53%  |
| MEDIATEK              | 2         | 11.76%  |
| Qualcomm Atheros      | 1         | 5.88%   |
| Broadcom Limited      | 1         | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| MEDIATEK Network controller                                | 2         | 11.76%  |
| Intel Wi-Fi 6 AX200                                        | 2         | 11.76%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 5.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 5.88%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 5.88%   |
| Intel Wireless 8265 / 8275                                 | 1         | 5.88%   |
| Intel Wireless 7265                                        | 1         | 5.88%   |
| Intel Wireless 3165                                        | 1         | 5.88%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 5.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 5.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 5.88%   |
| Intel Centrino Advanced-N 6200                             | 1         | 5.88%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 11        | 68.75%  |
| Intel                 | 2         | 12.5%   |
| Xiaomi                | 1         | 6.25%   |
| Broadcom              | 1         | 6.25%   |
| Aquantia              | 1         | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 62.5%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 6.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 6.25%   |
| Intel I211 Gigabit Network Connection                             | 1         | 6.25%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 6.25%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 6.25%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 54.84%  |
| Ethernet | 14        | 45.16%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 14        | 60.87%  |
| Ethernet | 9         | 39.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 10        | 47.62%  |
| 1     | 10        | 47.62%  |
| 3     | 1         | 4.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 18        | 85.71%  |
| Yes  | 3         | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 43.75%  |
| IMC Networks                    | 3         | 18.75%  |
| Realtek Semiconductor           | 2         | 12.5%   |
| Qualcomm Atheros Communications | 1         | 6.25%   |
| Lite-On Technology              | 1         | 6.25%   |
| Cambridge Silicon Radio         | 1         | 6.25%   |
| Broadcom                        | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 18.75%  |
| Intel Bluetooth Device                              | 2         | 12.5%   |
| Intel AX200 Bluetooth                               | 2         | 12.5%   |
| IMC Networks Wireless_Device                        | 2         | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 6.25%   |
| Realtek Bluetooth Radio                             | 1         | 6.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 6.25%   |
| Lite-On Bluetooth Radio                             | 1         | 6.25%   |
| IMC Networks Bluetooth Radio                        | 1         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.25%   |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 14        | 43.75%  |
| Nvidia                            | 6         | 18.75%  |
| AMD                               | 6         | 18.75%  |
| Elitegroup Computer Systems (ECS) | 2         | 6.25%   |
| XMOS                              | 1         | 3.13%   |
| Focusrite-Novation                | 1         | 3.13%   |
| Corsair                           | 1         | 3.13%   |
| ASUSTek Computer                  | 1         | 3.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 4         | 10%     |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 7.5%    |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 5%      |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                   | 2         | 5%      |
| XMOS HIFI DSD                                                              | 1         | 2.5%    |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 2.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 2.5%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.5%    |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.5%    |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.5%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.5%    |
| Intel CM238 HD Audio Controller                                            | 1         | 2.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.5%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.5%    |
| Focusrite-Novation Scarlett 18i20 3rd Gen                                  | 1         | 2.5%    |
| Corsair HS70 Pro Wireless Gaming Headset                                   | 1         | 2.5%    |
| ASUSTek Computer USB Audio                                                 | 1         | 2.5%    |
| AMD Trinity HDMI Audio Controller                                          | 1         | 2.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.5%    |
| AMD FCH Azalia Controller                                                  | 1         | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 26.67%  |
| SK Hynix            | 3         | 20%     |
| Micron Technology   | 3         | 20%     |
| Crucial             | 2         | 13.33%  |
| Unknown             | 1         | 6.67%   |
| Kingston            | 1         | 6.67%   |
| Elpida              | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 13.33%  |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                           | 1         | 6.67%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s                | 1         | 6.67%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 1         | 6.67%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 6.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DIMM DDR4 2667MT/s                 | 1         | 6.67%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s                 | 1         | 6.67%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s         | 1         | 6.67%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 1         | 6.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s             | 1         | 6.67%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s              | 1         | 6.67%   |
| Elpida RAM Module 4GB Row Of Chips LPDDR3 1867MT/s                  | 1         | 6.67%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s          | 1         | 6.67%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8192MB DIMM DDR4 3733MT/s            | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 69.23%  |
| LPDDR3 | 2         | 15.38%  |
| LPDDR4 | 1         | 7.69%   |
| DDR3   | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 5         | 38.46%  |
| DIMM         | 4         | 30.77%  |
| Row Of Chips | 3         | 23.08%  |
| Chip         | 1         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 6         | 42.86%  |
| 16384 | 3         | 21.43%  |
| 4096  | 3         | 21.43%  |
| 32768 | 1         | 7.14%   |
| 2048  | 1         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 4         | 28.57%  |
| 2667  | 3         | 21.43%  |
| 4267  | 1         | 7.14%   |
| 3733  | 1         | 7.14%   |
| 3600  | 1         | 7.14%   |
| 3400  | 1         | 7.14%   |
| 2133  | 1         | 7.14%   |
| 1867  | 1         | 7.14%   |
| 1600  | 1         | 7.14%   |

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
| IMC Networks        | 3         | 20%     |
| Chicony Electronics | 3         | 20%     |
| Microdia            | 2         | 13.33%  |
| Syntek              | 1         | 6.67%   |
| Suyin               | 1         | 6.67%   |
| Samsung Electronics | 1         | 6.67%   |
| Quanta              | 1         | 6.67%   |
| Lenovo              | 1         | 6.67%   |
| Alcor Micro         | 1         | 6.67%   |
| Acer                | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam       | 2         | 13.33%  |
| Syntek Lenovo EasyCamera                | 1         | 6.67%   |
| Suyin Acer CrystalEye Webcam            | 1         | 6.67%   |
| Samsung Galaxy series, misc. (MTP mode) | 1         | 6.67%   |
| Quanta USB2.0 HD UVC WebCam             | 1         | 6.67%   |
| Microdia Integrated_Webcam_HD           | 1         | 6.67%   |
| Microdia Integrated Webcam HD           | 1         | 6.67%   |
| Lenovo Integrated Webcam                | 1         | 6.67%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 1         | 6.67%   |
| Chicony USB 2.0 Camera                  | 1         | 6.67%   |
| Chicony LG HD WebCam                    | 1         | 6.67%   |
| Chicony HP Wide Vision HD Camera        | 1         | 6.67%   |
| Alcor Micro USB 2.0 PC Camera           | 1         | 6.67%   |
| Acer Integrated Camera                  | 1         | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Upek                       | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| Elan Microelectronics      | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 33.33%  |
| Elan ELAN:Fingerprint                                  | 1         | 33.33%  |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 13        | 61.9%   |
| 1     | 6         | 28.57%  |
| 2     | 2         | 9.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 3         | 33.33%  |
| Net/wireless       | 2         | 22.22%  |
| Graphics card      | 2         | 22.22%  |
| Unassigned class   | 1         | 11.11%  |
| Bluetooth          | 1         | 11.11%  |

