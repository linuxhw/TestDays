Ubuntu 21.10 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad T400 2768WGB       | [77d801bf3c](https://linux-hardware.org/?probe=77d801bf3c) | Sep 15, 2021 |
| HP       | ProBook 455 G6              | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| Lenovo   | ThinkPad T400 2768WGB       | [c105819db0](https://linux-hardware.org/?probe=c105819db0) | Sep 13, 2021 |
| Lenovo   | ThinkPad T400 2768WGB       | [04299c1c72](https://linux-hardware.org/?probe=04299c1c72) | Sep 10, 2021 |
| Lenovo   | G570 20079                  | [070f80905a](https://linux-hardware.org/?probe=070f80905a) | Sep 09, 2021 |
| Dell     | XPS 13 9310                 | [ce30239886](https://linux-hardware.org/?probe=ce30239886) | Sep 08, 2021 |
| Lenovo   | ThinkPad T470 20JNS3M500    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo   | V310-14IKB 80T2             | [9036570a3d](https://linux-hardware.org/?probe=9036570a3d) | Sep 07, 2021 |
| Dell     | XPS 13 9310                 | [a23d662013](https://linux-hardware.org/?probe=a23d662013) | Sep 06, 2021 |
| Lenovo   | G570 20079                  | [92d47c8db5](https://linux-hardware.org/?probe=92d47c8db5) | Sep 05, 2021 |
| Google   | Nautilus                    | [3b25f1b84a](https://linux-hardware.org/?probe=3b25f1b84a) | Sep 05, 2021 |
| Lenovo   | G570 20079                  | [897adf5520](https://linux-hardware.org/?probe=897adf5520) | Sep 04, 2021 |
| Lenovo   | ThinkPad T400 2768WGB       | [a66a6f00e4](https://linux-hardware.org/?probe=a66a6f00e4) | Sep 03, 2021 |
| Lenovo   | V310-14IKB 80T2             | [682d409384](https://linux-hardware.org/?probe=682d409384) | Sep 02, 2021 |
| Dell     | Latitude E6410              | [8b57d50d95](https://linux-hardware.org/?probe=8b57d50d95) | Sep 02, 2021 |
| ASUSTek  | GL753VD                     | [d17c6ba3fc](https://linux-hardware.org/?probe=d17c6ba3fc) | Sep 01, 2021 |
| ASUSTek  | ROG Strix G533QS_G533QS     | [cae806f49d](https://linux-hardware.org/?probe=cae806f49d) | Aug 22, 2021 |
| ASUSTek  | ROG Strix G533QS_G533QS     | [b8aa2e41d5](https://linux-hardware.org/?probe=b8aa2e41d5) | Aug 16, 2021 |
| ASUSTek  | ROG Strix G533QS_G533QS     | [612dda8fba](https://linux-hardware.org/?probe=612dda8fba) | Aug 13, 2021 |
| ASUSTek  | ROG Strix G533QS_G533QS     | [1eb6008b88](https://linux-hardware.org/?probe=1eb6008b88) | Aug 13, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | [808cfab06b](https://linux-hardware.org/?probe=808cfab06b) | Aug 12, 2021 |
| Lenovo   | ThinkPad T510 4484A63       | [c1bcb3451f](https://linux-hardware.org/?probe=c1bcb3451f) | Aug 09, 2021 |
| Lenovo   | ThinkPad T510 4484A63       | [4336b50906](https://linux-hardware.org/?probe=4336b50906) | Aug 06, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X530... | [961031411d](https://linux-hardware.org/?probe=961031411d) | Aug 03, 2021 |
| Lenovo   | ZhaoYang K3-ITL 82E3        | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| ASUSTek  | GL753VD                     | [eabe6a8723](https://linux-hardware.org/?probe=eabe6a8723) | Jul 31, 2021 |
| Acer     | Aspire 5920                 | [f41defe215](https://linux-hardware.org/?probe=f41defe215) | Jul 31, 2021 |
| Dell     | XPS 13 7390                 | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| Teclast  | F6 Pro                      | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X421... | [f5458b4f56](https://linux-hardware.org/?probe=f5458b4f56) | Jul 19, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X421... | [5ac65f3389](https://linux-hardware.org/?probe=5ac65f3389) | Jul 18, 2021 |
| Lenovo   | Z50-70 20354                | [85aadf8abd](https://linux-hardware.org/?probe=85aadf8abd) | Jul 16, 2021 |
| Lenovo   | Z50-70 20354                | [b2c80f450e](https://linux-hardware.org/?probe=b2c80f450e) | Jul 14, 2021 |
| HP       | Pavilion Gaming Laptop 1... | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo   | ThinkPad X201 3626FAG       | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Positivo | H14BT58                     | [51b9ba65e0](https://linux-hardware.org/?probe=51b9ba65e0) | Jun 18, 2021 |
| ASUSTek  | ROG Strix G533QR_G533QR     | [4befd5f360](https://linux-hardware.org/?probe=4befd5f360) | Jun 04, 2021 |
| Dell     | XPS 13 9343                 | [4ee08e92ae](https://linux-hardware.org/?probe=4ee08e92ae) | May 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.13.0-14-generic     | 8         | 33.33%  |
| 5.11.0-20-generic     | 4         | 16.67%  |
| 5.11.0-25-generic     | 2         | 8.33%   |
| 5.11.0-18-generic     | 2         | 8.33%   |
| 5.13.6-xanmod2-edge   | 1         | 4.17%   |
| 5.13.4-051304-generic | 1         | 4.17%   |
| 5.13.2-051302-generic | 1         | 4.17%   |
| 5.13.0-13-generic     | 1         | 4.17%   |
| 5.11.0-31-generic     | 1         | 4.17%   |
| 5.11.0-26-generic     | 1         | 4.17%   |
| 5.11.0-22-generic     | 1         | 4.17%   |
| 5.11.0-16-generic     | 1         | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 12        | 52.17%  |
| 5.13.0  | 8         | 34.78%  |
| 5.13.6  | 1         | 4.35%   |
| 5.13.4  | 1         | 4.35%   |
| 5.13.2  | 1         | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 52.17%  |
| 5.13    | 11        | 47.83%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 23        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 16        | 69.57%  |
| X-Cinnamon      | 2         | 8.7%    |
| Unknown         | 2         | 8.7%    |
| Unity           | 1         | 4.35%   |
| GNOME Flashback | 1         | 4.35%   |
| Cinnamon        | 1         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 15        | 65.22%  |
| X11     | 8         | 34.78%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 11        | 47.83%  |
| Unknown | 11        | 47.83%  |
| TDM     | 1         | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 7         | 30.43%  |
| en_GB | 5         | 21.74%  |
| fr_FR | 3         | 13.04%  |
| zh_CN | 1         | 4.35%   |
| sv_SE | 1         | 4.35%   |
| ru_RU | 1         | 4.35%   |
| pt_BR | 1         | 4.35%   |
| ko_KR | 1         | 4.35%   |
| hu_HU | 1         | 4.35%   |
| es_MX | 1         | 4.35%   |
| en_IN | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 12        | 52.17%  |
| EFI  | 11        | 47.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 21        | 91.3%   |
| Zfs   | 1         | 4.35%   |
| Btrfs | 1         | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 11        | 47.83%  |
| Unknown | 10        | 43.48%  |
| MBR     | 2         | 8.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 70.83%  |
| Yes       | 7         | 29.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 65.22%  |
| Yes       | 8         | 34.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 7         | 30.43%  |
| ASUSTek Computer | 6         | 26.09%  |
| Dell             | 4         | 17.39%  |
| Hewlett-Packard  | 2         | 8.7%    |
| Teclast          | 1         | 4.35%   |
| Positivo         | 1         | 4.35%   |
| Google           | 1         | 4.35%   |
| Acer             | 1         | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Teclast F6 Pro                          | 1         | 4.35%   |
| Positivo H14BT58                        | 1         | 4.35%   |
| Lenovo ZhaoYang K3-ITL 82E3             | 1         | 4.35%   |
| Lenovo Z50-70 20354                     | 1         | 4.35%   |
| Lenovo V310-14IKB 80T2                  | 1         | 4.35%   |
| Lenovo ThinkPad X201 3626FAG            | 1         | 4.35%   |
| Lenovo ThinkPad T470 20JNS3M500         | 1         | 4.35%   |
| Lenovo ThinkPad T400 2768WGB            | 1         | 4.35%   |
| Lenovo G570 20079                       | 1         | 4.35%   |
| HP ProBook 455 G6                       | 1         | 4.35%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 4.35%   |
| Google Nautilus                         | 1         | 4.35%   |
| Dell XPS 13 9343                        | 1         | 4.35%   |
| Dell XPS 13 9310                        | 1         | 4.35%   |
| Dell XPS 13 7390                        | 1         | 4.35%   |
| Dell Latitude E6410                     | 1         | 4.35%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN  | 1         | 4.35%   |
| ASUS VivoBook_ASUSLaptop X509DJ_M509DJ  | 1         | 4.35%   |
| ASUS VivoBook_ASUSLaptop X421UAY_M413UA | 1         | 4.35%   |
| ASUS ROG Strix G533QS_G533QS            | 1         | 4.35%   |
| ASUS ROG Strix G533QR_G533QR            | 1         | 4.35%   |
| ASUS GL753VD                            | 1         | 4.35%   |
| Acer Aspire 5920                        | 1         | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 3         | 13.04%  |
| Dell XPS          | 3         | 13.04%  |
| ASUS VivoBook     | 3         | 13.04%  |
| ASUS ROG          | 2         | 8.7%    |
| Teclast F6        | 1         | 4.35%   |
| Positivo H14BT58  | 1         | 4.35%   |
| Lenovo ZhaoYang   | 1         | 4.35%   |
| Lenovo Z50-70     | 1         | 4.35%   |
| Lenovo V310-14IKB | 1         | 4.35%   |
| Lenovo G570       | 1         | 4.35%   |
| HP ProBook        | 1         | 4.35%   |
| HP Pavilion       | 1         | 4.35%   |
| Google Nautilus   | 1         | 4.35%   |
| Dell Latitude     | 1         | 4.35%   |
| ASUS GL753VD      | 1         | 4.35%   |
| Acer Aspire       | 1         | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 8         | 34.78%  |
| 2020 | 5         | 21.74%  |
| 2019 | 2         | 8.7%    |
| 2018 | 1         | 4.35%   |
| 2017 | 1         | 4.35%   |
| 2015 | 1         | 4.35%   |
| 2014 | 1         | 4.35%   |
| 2012 | 1         | 4.35%   |
| 2011 | 1         | 4.35%   |
| 2010 | 1         | 4.35%   |
| 2008 | 1         | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 23        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 21        | 91.3%   |
| Enabled  | 2         | 8.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 95.65%  |
| Yes  | 1         | 4.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 34.78%  |
| 8.01-16.0  | 5         | 21.74%  |
| 32.01-64.0 | 3         | 13.04%  |
| 3.01-4.0   | 3         | 13.04%  |
| 16.01-24.0 | 2         | 8.7%    |
| 24.01-32.0 | 1         | 4.35%   |
| 1.01-2.0   | 1         | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 9         | 37.5%   |
| 4.01-8.0  | 6         | 25%     |
| 1.01-2.0  | 6         | 25%     |
| 3.01-4.0  | 2         | 8.33%   |
| 8.01-16.0 | 1         | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 73.91%  |
| 2      | 4         | 17.39%  |
| 3      | 2         | 8.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 78.26%  |
| Yes       | 5         | 21.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 65.22%  |
| No        | 8         | 34.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 78.26%  |
| No        | 5         | 21.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| UK          | 4         | 17.39%  |
| USA         | 3         | 13.04%  |
| France      | 3         | 13.04%  |
| Germany     | 2         | 8.7%    |
| Sweden      | 1         | 4.35%   |
| South Korea | 1         | 4.35%   |
| Russia      | 1         | 4.35%   |
| India       | 1         | 4.35%   |
| Hungary     | 1         | 4.35%   |
| Finland     | 1         | 4.35%   |
| Czechia     | 1         | 4.35%   |
| Cyprus      | 1         | 4.35%   |
| China       | 1         | 4.35%   |
| Chile       | 1         | 4.35%   |
| Brazil      | 1         | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Yongin-si              | 1         | 4.35%   |
| Turku                  | 1         | 4.35%   |
| Trivandrum             | 1         | 4.35%   |
| Tottenham              | 1         | 4.35%   |
| Toms River             | 1         | 4.35%   |
| Tatab??nya             | 1         | 4.35%   |
| Shanghai               | 1         | 4.35%   |
| Santiago               | 1         | 4.35%   |
| Rio de Janeiro         | 1         | 4.35%   |
| Prague                 | 1         | 4.35%   |
| Paris                  | 1         | 4.35%   |
| Nizhny Tagil           | 1         | 4.35%   |
| Nicosia                | 1         | 4.35%   |
| Maidstone              | 1         | 4.35%   |
| Lyon                   | 1         | 4.35%   |
| Helsingborg            | 1         | 4.35%   |
| Haselhorst             | 1         | 4.35%   |
| Glasgow                | 1         | 4.35%   |
| Fellbach               | 1         | 4.35%   |
| Crewe                  | 1         | 4.35%   |
| Charleville-M?�zi??res | 1         | 4.35%   |
| Brooklyn               | 1         | 4.35%   |
| Austin                 | 1         | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 16.67%  |
| Samsung Electronics | 5         | 5      | 16.67%  |
| Toshiba             | 3         | 3      | 10%     |
| Sandisk             | 3         | 4      | 10%     |
| Unknown             | 2         | 2      | 6.67%   |
| SK Hynix            | 2         | 2      | 6.67%   |
| Intel               | 2         | 3      | 6.67%   |
| WDC                 | 1         | 1      | 3.33%   |
| SPCC                | 1         | 1      | 3.33%   |
| SP                  | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |
| Kingston            | 1         | 1      | 3.33%   |
| KingDian            | 1         | 1      | 3.33%   |
| HGST                | 1         | 2      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix HFM001TD3JX013N 1TB            | 2         | 6.45%   |
| Seagate Expansion+ 1TB                  | 2         | 6.45%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 3.23%   |
| Unknown SB64G  64GB                     | 1         | 3.23%   |
| Unknown MMC Card  64GB                  | 1         | 3.23%   |
| Toshiba NVMe SSD Drive 256GB            | 1         | 3.23%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 3.23%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 3.23%   |
| SPCC Solid State Disk 128GB             | 1         | 3.23%   |
| SP PC60 1TB                             | 1         | 3.23%   |
| Seagate ST9320423AS 320GB               | 1         | 3.23%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 3.23%   |
| Seagate BUP Slim RD 2TB                 | 1         | 3.23%   |
| SanDisk SD9SN8W256G1102 256GB SSD       | 1         | 3.23%   |
| SanDisk SD7SB3Q064G 56GB SSD            | 1         | 3.23%   |
| Sandisk NVMe SSD Drive 500GB            | 1         | 3.23%   |
| Samsung SSD 970 EVO 500GB               | 1         | 3.23%   |
| Samsung SSD 850 EVO 500GB               | 1         | 3.23%   |
| Samsung NVMe SSD Drive 512GB            | 1         | 3.23%   |
| Samsung MZVLQ512HALU-00000 512GB        | 1         | 3.23%   |
| Samsung MZALQ512HALU-000L2 512GB        | 1         | 3.23%   |
| Micron 2300 NVMe 1024GB                 | 1         | 3.23%   |
| LITEON L8H-256V2G-11 M.2 2280 256GB SSD | 1         | 3.23%   |
| Kingston SKC300S37A240G 240GB SSD       | 1         | 3.23%   |
| KingDian N400 240GB SSD                 | 1         | 3.23%   |
| Intel NVMe SSD Drive 512GB              | 1         | 3.23%   |
| Intel HBRPEKNX0101AHO 16GB              | 1         | 3.23%   |
| Intel HBRPEKNX0101AH 256GB              | 1         | 3.23%   |
| HGST HTS721010A9E630 1TB                | 1         | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 55.56%  |
| Toshiba | 2         | 2      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |
| HGST    | 1         | 2      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 28.57%  |
| SPCC                | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| LITEON              | 1         | 1      | 14.29%  |
| Kingston            | 1         | 1      | 14.29%  |
| KingDian            | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 11        | 13     | 36.67%  |
| HDD     | 9         | 10     | 30%     |
| SSD     | 7         | 7      | 23.33%  |
| MMC     | 2         | 2      | 6.67%   |
| Unknown | 1         | 1      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12        | 14     | 42.86%  |
| NVMe | 11        | 13     | 39.29%  |
| SAS  | 3         | 4      | 10.71%  |
| MMC  | 2         | 2      | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 10     | 62.5%   |
| 0.51-1.0   | 5         | 6      | 31.25%  |
| 1.01-2.0   | 1         | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 51-100     | 8         | 33.33%  |
| 101-250    | 5         | 20.83%  |
| 251-500    | 4         | 16.67%  |
| 1001-2000  | 4         | 16.67%  |
| 21-50      | 1         | 4.17%   |
| 1-20       | 1         | 4.17%   |
| 501-1000   | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 6         | 25%     |
| 1-20     | 6         | 25%     |
| 51-100   | 4         | 16.67%  |
| 101-250  | 3         | 12.5%   |
| 501-1000 | 3         | 12.5%   |
| 251-500  | 2         | 8.33%   |

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
| Detected | 15        | 20     | 55.56%  |
| Works    | 12        | 13     | 44.44%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 15        | 55.56%  |
| Samsung Electronics          | 4         | 14.81%  |
| AMD                          | 3         | 11.11%  |
| SK Hynix                     | 2         | 7.41%   |
| Toshiba America Info Systems | 1         | 3.7%    |
| Sandisk                      | 1         | 3.7%    |
| Micron Technology            | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 10.34%  |
| SK Hynix NVMe SSD Controller                                                     | 2         | 6.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 6.9%    |
| Samsung NVMe SSD Controller 980                                                  | 2         | 6.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 6.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 6.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 6.9%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 3.45%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 3.45%   |
| Micron Non-Volatile memory controller                                            | 1         | 3.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 3.45%   |
| Intel SSD 660P Series                                                            | 1         | 3.45%   |
| Intel Non-Volatile memory controller                                             | 1         | 3.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 3.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 3.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 14        | 48.28%  |
| NVMe | 11        | 37.93%  |
| RAID | 3         | 10.34%  |
| IDE  | 1         | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 78.26%  |
| AMD    | 5         | 21.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core m3-7Y30 CPU @ 1.00GHz                | 2         | 8.7%    |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 2         | 8.7%    |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 2         | 8.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 4.35%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 4.35%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 4.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 4.35%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 4.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 4.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 4.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 4.35%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 4.35%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 1         | 4.35%   |
| Intel Celeron CPU N2807 @ 1.58GHz               | 1         | 4.35%   |
| Intel Celeron CPU B800 @ 1.50GHz                | 1         | 4.35%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 4.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 4.35%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 4.35%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 4.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 6         | 26.09%  |
| Intel Core i7    | 4         | 17.39%  |
| Other            | 2         | 8.7%    |
| Intel Core m3    | 2         | 8.7%    |
| Intel Core 2 Duo | 2         | 8.7%    |
| Intel Celeron    | 2         | 8.7%    |
| AMD Ryzen 9      | 2         | 8.7%    |
| AMD Ryzen 5      | 2         | 8.7%    |
| AMD Ryzen 7 PRO  | 1         | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 52.17%  |
| 4      | 8         | 34.78%  |
| 8      | 2         | 8.7%    |
| 6      | 1         | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 82.61%  |
| 1      | 4         | 17.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 23        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 39.13%  |
| 0x806e9    | 3         | 13.04%  |
| 0x806c1    | 2         | 8.7%    |
| 0x906ea    | 1         | 4.35%   |
| 0x806ec    | 1         | 4.35%   |
| 0x806eb    | 1         | 4.35%   |
| 0x306d4    | 1         | 4.35%   |
| 0x206a7    | 1         | 4.35%   |
| 0x20652    | 1         | 4.35%   |
| 0x1067a    | 1         | 4.35%   |
| 0x0a50000b | 1         | 4.35%   |
| 0x08608103 | 1         | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 30.43%  |
| Zen 3       | 2         | 8.7%    |
| Westmere    | 2         | 8.7%    |
| TigerLake   | 2         | 8.7%    |
| Penryn      | 2         | 8.7%    |
| Zen+        | 1         | 4.35%   |
| Zen         | 1         | 4.35%   |
| Skylake     | 1         | 4.35%   |
| Silvermont  | 1         | 4.35%   |
| SandyBridge | 1         | 4.35%   |
| Haswell     | 1         | 4.35%   |
| Broadwell   | 1         | 4.35%   |
| Unknown     | 1         | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 56.67%  |
| Nvidia | 7         | 23.33%  |
| AMD    | 6         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 6.45%   |
| Intel HD Graphics 615                                                     | 2         | 6.45%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 6.45%   |
| AMD Cezanne                                                               | 2         | 6.45%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 3.23%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 3.23%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 3.23%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                               | 1         | 3.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 3.23%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 1         | 3.23%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 1         | 3.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 3.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 3.23%   |
| Intel HD Graphics 630                                                     | 1         | 3.23%   |
| Intel HD Graphics 620                                                     | 1         | 3.23%   |
| Intel HD Graphics 5500                                                    | 1         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 3.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 3.23%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                              | 1         | 3.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 3.23%   |
| AMD Picasso                                                               | 1         | 3.23%   |
| AMD Lucienne                                                              | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 56.52%  |
| Intel + Nvidia | 4         | 17.39%  |
| AMD + Nvidia   | 3         | 13.04%  |
| 1 x AMD        | 3         | 13.04%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 19        | 82.61%  |
| Proprietary | 4         | 17.39%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 78.26%  |
| 0.01-0.5   | 3         | 13.04%  |
| 1.01-2.0   | 2         | 8.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 19.23%  |
| Sharp               | 3         | 11.54%  |
| Chimei Innolux      | 3         | 11.54%  |
| BOE                 | 3         | 11.54%  |
| Samsung Electronics | 2         | 7.69%   |
| LG Display          | 2         | 7.69%   |
| Lenovo              | 2         | 7.69%   |
| Acer                | 2         | 7.69%   |
| PANDA               | 1         | 3.85%   |
| KDC                 | 1         | 3.85%   |
| InfoVision          | 1         | 3.85%   |
| Dell                | 1         | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Acer XV340CK P ACR06F3 3440x1440 800x335mm 34.1-inch                 | 2         | 7.69%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 3.85%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch              | 1         | 3.85%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch | 1         | 3.85%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch              | 1         | 3.85%   |
| LG Display LCD Monitor LGD05CE 1920x1080 344x194mm 15.5-inch         | 1         | 3.85%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 1         | 3.85%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch              | 1         | 3.85%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 3.85%   |
| KDC LCD Monitor KDC0001 1920x1200 263x164mm 12.2-inch                | 1         | 3.85%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch         | 1         | 3.85%   |
| Dell S2721DS DELA19D 2560x1440 597x336mm 27.0-inch                   | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 1         | 3.85%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                | 1         | 3.85%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                | 1         | 3.85%   |
| BOE LCD Monitor BOE05EC 1366x768 309x173mm 13.9-inch                 | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch       | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 12        | 46.15%  |
| 3440x1440         | 2         | 7.69%   |
| 2560x1440 (QHD)   | 2         | 7.69%   |
| 1920x1200 (WUXGA) | 2         | 7.69%   |
| 1440x900 (WXGA+)  | 2         | 7.69%   |
| 1366x768 (WXGA)   | 2         | 7.69%   |
| 1280x800 (WXGA)   | 2         | 7.69%   |
| 3840x2400         | 1         | 3.85%   |
| 3200x1800 (QHD+)  | 1         | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 34.62%  |
| 13     | 8         | 30.77%  |
| 34     | 2         | 7.69%   |
| 17     | 2         | 7.69%   |
| 14     | 2         | 7.69%   |
| 12     | 2         | 7.69%   |
| 27     | 1         | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 53.85%  |
| 201-300     | 7         | 26.92%  |
| 701-800     | 2         | 7.69%   |
| 351-400     | 2         | 7.69%   |
| 501-600     | 1         | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 64%     |
| 16/10 | 6         | 24%     |
| 21/9  | 2         | 8%      |
| 3/2   | 1         | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 34.62%  |
| 81-90          | 5         | 19.23%  |
| 71-80          | 5         | 19.23%  |
| 61-70          | 2         | 7.69%   |
| 351-500        | 2         | 7.69%   |
| 301-350        | 1         | 3.85%   |
| 131-140        | 1         | 3.85%   |
| 121-130        | 1         | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 46.15%  |
| 161-240       | 5         | 19.23%  |
| 101-120       | 5         | 19.23%  |
| More than 240 | 2         | 7.69%   |
| 51-100        | 2         | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 20        | 86.96%  |
| 2     | 3         | 13.04%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 11        | 33.33%  |
| Intel                         | 11        | 33.33%  |
| Qualcomm Atheros              | 4         | 12.12%  |
| MEDIATEK                      | 2         | 6.06%   |
| Xiaomi                        | 1         | 3.03%   |
| Qualcomm                      | 1         | 3.03%   |
| OnePlus Technology (Shenzhen) | 1         | 3.03%   |
| Broadcom Limited              | 1         | 3.03%   |
| Broadcom                      | 1         | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 20%     |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 5%      |
| MEDIATEK Network controller                                       | 2         | 5%      |
| Intel Wireless 7265                                               | 2         | 5%      |
| Intel 82577LM Gigabit Network Connection                          | 2         | 5%      |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 1         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.5%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.5%    |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 1         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.5%    |
| OnePlus (Shenzhen) IN2013                                         | 1         | 2.5%    |
| Intel Wireless 8265 / 8275                                        | 1         | 2.5%    |
| Intel Wireless 8260                                               | 1         | 2.5%    |
| Intel Wireless 3165                                               | 1         | 2.5%    |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.5%    |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 2.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 2.5%    |
| Intel Ethernet Connection I219-V                                  | 1         | 2.5%    |
| Intel Centrino Advanced-N 6200                                    | 1         | 2.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.5%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 2.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 43.48%  |
| Realtek Semiconductor | 5         | 21.74%  |
| Qualcomm Atheros      | 4         | 17.39%  |
| MEDIATEK              | 2         | 8.7%    |
| Qualcomm              | 1         | 4.35%   |
| Broadcom Limited      | 1         | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 8.7%    |
| MEDIATEK Network controller                                    | 2         | 8.7%    |
| Intel Wireless 7265                                            | 2         | 8.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 4.35%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 4.35%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 1         | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 4.35%   |
| Intel Wireless 8265 / 8275                                     | 1         | 4.35%   |
| Intel Wireless 8260                                            | 1         | 4.35%   |
| Intel Wireless 3165                                            | 1         | 4.35%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 4.35%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 4.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 4.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 4.35%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 4.35%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 9         | 52.94%  |
| Intel                         | 4         | 23.53%  |
| Xiaomi                        | 1         | 5.88%   |
| Qualcomm Atheros              | 1         | 5.88%   |
| OnePlus Technology (Shenzhen) | 1         | 5.88%   |
| Broadcom                      | 1         | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 47.06%  |
| Intel 82577LM Gigabit Network Connection                          | 2         | 11.76%  |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 1         | 5.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 5.88%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 5.88%   |
| Intel Ethernet Connection I219-V                                  | 1         | 5.88%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 5.88%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 60.53%  |
| Ethernet | 15        | 39.47%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 68.97%  |
| Ethernet | 9         | 31.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 14        | 60.87%  |
| 1     | 9         | 39.13%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 82.61%  |
| Yes  | 4         | 17.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 38.89%  |
| Qualcomm Atheros Communications | 3         | 16.67%  |
| IMC Networks                    | 3         | 16.67%  |
| Realtek Semiconductor           | 2         | 11.11%  |
| Lite-On Technology              | 1         | 5.56%   |
| Foxconn / Hon Hai               | 1         | 5.56%   |
| Broadcom                        | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface              | 3         | 16.67%  |
| Intel Bluetooth Device                          | 3         | 16.67%  |
| Realtek  Bluetooth 4.2 Adapter                  | 2         | 11.11%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0           | 2         | 11.11%  |
| IMC Networks Wireless_Device                    | 2         | 11.11%  |
| Qualcomm Atheros  Bluetooth Device              | 1         | 5.56%   |
| Lite-On Bluetooth Radio                         | 1         | 5.56%   |
| Intel AX200 Bluetooth                           | 1         | 5.56%   |
| IMC Networks Bluetooth Radio                    | 1         | 5.56%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device | 1         | 5.56%   |
| Broadcom BCM20702A0 Bluetooth                   | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 18        | 60%     |
| AMD                               | 5         | 16.67%  |
| Nvidia                            | 3         | 10%     |
| Elitegroup Computer Systems (ECS) | 2         | 6.67%   |
| Focusrite-Novation                | 1         | 3.33%   |
| Corsair                           | 1         | 3.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 5         | 13.51%  |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 10.81%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 8.11%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 5.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 5.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 5.41%   |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                   | 2         | 5.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 5.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.7%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.7%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.7%    |
| Intel CM238 HD Audio Controller                                            | 1         | 2.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.7%    |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.7%    |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.7%    |
| Focusrite-Novation Scarlett 18i20 3rd Gen                                  | 1         | 2.7%    |
| Corsair HS70 Pro Wireless Gaming Headset                                   | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 33.33%  |
| SK Hynix            | 5         | 27.78%  |
| Micron Technology   | 4         | 22.22%  |
| Unknown             | 1         | 5.56%   |
| Elpida              | 1         | 5.56%   |
| Crucial             | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 11.11%  |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 11.11%  |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 5.56%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 5.56%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 5.56%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 5.56%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 5.56%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 5.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 5.56%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 5.56%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 5.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 5.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 5.56%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 5.56%   |
| Elpida RAM Module 4GB Row Of Chips LPDDR3 1867MT/s               | 1         | 5.56%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s       | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 7         | 43.75%  |
| DDR3   | 4         | 25%     |
| LPDDR3 | 3         | 18.75%  |
| LPDDR4 | 2         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 68.75%  |
| Row Of Chips | 4         | 25%     |
| Chip         | 1         | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 38.89%  |
| 8192  | 4         | 22.22%  |
| 2048  | 4         | 22.22%  |
| 16384 | 3         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 4         | 23.53%  |
| 2667  | 4         | 23.53%  |
| 4267  | 2         | 11.76%  |
| 1867  | 2         | 11.76%  |
| 1600  | 2         | 11.76%  |
| 2133  | 1         | 5.88%   |
| 1334  | 1         | 5.88%   |
| 1067  | 1         | 5.88%   |

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


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chicony Electronics | 6         | 27.27%  |
| IMC Networks        | 4         | 18.18%  |
| Microdia            | 3         | 13.64%  |
| Lenovo              | 2         | 9.09%   |
| Syntek              | 1         | 4.55%   |
| Suyin               | 1         | 4.55%   |
| Samsung Electronics | 1         | 4.55%   |
| Ricoh               | 1         | 4.55%   |
| Quanta              | 1         | 4.55%   |
| Alcor Micro         | 1         | 4.55%   |
| Acer                | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD      | 2         | 9.09%   |
| Lenovo Integrated Webcam           | 2         | 9.09%   |
| IMC Networks USB2.0 HD UVC WebCam  | 2         | 9.09%   |
| Syntek Lenovo EasyCamera           | 1         | 4.55%   |
| Suyin Acer CrystalEye Webcam       | 1         | 4.55%   |
| Samsung Galaxy A5 (MTP)            | 1         | 4.55%   |
| Ricoh HD Webcam                    | 1         | 4.55%   |
| Quanta USB2.0 HD UVC WebCam        | 1         | 4.55%   |
| Microdia Integrated Webcam HD      | 1         | 4.55%   |
| IMC Networks USB2.0 VGA UVC WebCam | 1         | 4.55%   |
| IMC Networks Integrated Camera     | 1         | 4.55%   |
| Chicony USB 2.0 Camera             | 1         | 4.55%   |
| Chicony Lenovo EasyCamera          | 1         | 4.55%   |
| Chicony HP Wide Vision HD Camera   | 1         | 4.55%   |
| Chicony HP HD Camera               | 1         | 4.55%   |
| Chicony EasyCamera                 | 1         | 4.55%   |
| Chicony 720p HD Camera             | 1         | 4.55%   |
| Alcor Micro USB 2.0 PC Camera      | 1         | 4.55%   |
| Acer Integrated Camera             | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 16.67%  |
| Upek                       | 1         | 16.67%  |
| Synaptics                  | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| Goodix                     | 1         | 16.67%  |
| Elan Microelectronics      | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 16.67%  |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 16.67%  |
| Goodix FingerPrint                                         | 1         | 16.67%  |
| Elan ELAN:Fingerprint                                      | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11        | 47.83%  |
| 0     | 11        | 47.83%  |
| 2     | 1         | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 6         | 46.15%  |
| Chipcard           | 3         | 23.08%  |
| Net/wireless       | 2         | 15.38%  |
| Graphics card      | 1         | 7.69%   |
| Bluetooth          | 1         | 7.69%   |

