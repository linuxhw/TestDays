Ubuntu 21.10 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10.

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
| Dell          | XPS 13 9310                 | Notebook    | [ce30239886](https://linux-hardware.org/?probe=ce30239886) | Sep 08, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [9036570a3d](https://linux-hardware.org/?probe=9036570a3d) | Sep 07, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [a23d662013](https://linux-hardware.org/?probe=a23d662013) | Sep 06, 2021 |
| Lenovo        | G570 20079                  | Notebook    | [92d47c8db5](https://linux-hardware.org/?probe=92d47c8db5) | Sep 05, 2021 |
| Google        | Nautilus                    | Notebook    | [3b25f1b84a](https://linux-hardware.org/?probe=3b25f1b84a) | Sep 05, 2021 |
| Lenovo        | G570 20079                  | Notebook    | [897adf5520](https://linux-hardware.org/?probe=897adf5520) | Sep 04, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [c080ec772f](https://linux-hardware.org/?probe=c080ec772f) | Sep 03, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [a66a6f00e4](https://linux-hardware.org/?probe=a66a6f00e4) | Sep 03, 2021 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [682d409384](https://linux-hardware.org/?probe=682d409384) | Sep 02, 2021 |
| Dell          | Latitude E6410              | Notebook    | [8b57d50d95](https://linux-hardware.org/?probe=8b57d50d95) | Sep 02, 2021 |
| ASUSTek       | GL753VD                     | Notebook    | [d17c6ba3fc](https://linux-hardware.org/?probe=d17c6ba3fc) | Sep 01, 2021 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.13.0-14-generic     | 10        | 33.33%  |
| 5.11.0-20-generic     | 5         | 16.67%  |
| 5.13.0-12-generic     | 2         | 6.67%   |
| 5.11.0-25-generic     | 2         | 6.67%   |
| 5.11.0-18-generic     | 2         | 6.67%   |
| 5.13.6-xanmod2-edge   | 1         | 3.33%   |
| 5.13.4-051304-generic | 1         | 3.33%   |
| 5.13.2-051302-generic | 1         | 3.33%   |
| 5.13.0-13-generic     | 1         | 3.33%   |
| 5.13.0-051300-generic | 1         | 3.33%   |
| 5.11.0-31-generic     | 1         | 3.33%   |
| 5.11.0-26-generic     | 1         | 3.33%   |
| 5.11.0-22-generic     | 1         | 3.33%   |
| 5.11.0-16-generic     | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 13        | 44.83%  |
| 5.11.0  | 13        | 44.83%  |
| 5.13.6  | 1         | 3.45%   |
| 5.13.4  | 1         | 3.45%   |
| 5.13.2  | 1         | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 16        | 55.17%  |
| 5.11    | 13        | 44.83%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 20        | 68.97%  |
| X-Cinnamon      | 3         | 10.34%  |
| Unknown         | 3         | 10.34%  |
| Unity           | 1         | 3.45%   |
| GNOME Flashback | 1         | 3.45%   |
| Cinnamon        | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 16        | 55.17%  |
| X11     | 12        | 41.38%  |
| Tty     | 1         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 14        | 50%     |
| Unknown | 13        | 46.43%  |
| TDM     | 1         | 3.57%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 7         | 25%     |
| en_GB | 7         | 25%     |
| fr_FR | 3         | 10.71%  |
| pt_BR | 2         | 7.14%   |
| zh_CN | 1         | 3.57%   |
| sv_SE | 1         | 3.57%   |
| ru_UA | 1         | 3.57%   |
| ru_RU | 1         | 3.57%   |
| ko_KR | 1         | 3.57%   |
| hu_HU | 1         | 3.57%   |
| es_MX | 1         | 3.57%   |
| es_AR | 1         | 3.57%   |
| en_IN | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 14        | 50%     |
| EFI  | 14        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 25        | 89.29%  |
| Btrfs | 2         | 7.14%   |
| Zfs   | 1         | 3.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 14        | 50%     |
| Unknown | 12        | 42.86%  |
| MBR     | 2         | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 68.97%  |
| Yes       | 9         | 31.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 50%     |
| No        | 14        | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 25%     |
| ASUSTek Computer    | 7         | 25%     |
| Dell                | 4         | 14.29%  |
| Teclast             | 1         | 3.57%   |
| Positivo            | 1         | 3.57%   |
| MSI                 | 1         | 3.57%   |
| LG Electronics      | 1         | 3.57%   |
| Huanan              | 1         | 3.57%   |
| Hewlett-Packard     | 1         | 3.57%   |
| Google              | 1         | 3.57%   |
| Gigabyte Technology | 1         | 3.57%   |
| Fujitsu             | 1         | 3.57%   |
| Acer                | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Teclast F6 Pro                          | 1         | 3.57%   |
| Positivo H14BT58                        | 1         | 3.57%   |
| MSI MS-7C94                             | 1         | 3.57%   |
| LG 22V280-L.BY31P1                      | 1         | 3.57%   |
| Lenovo ZhaoYang K3-ITL 82E3             | 1         | 3.57%   |
| Lenovo Z50-70 20354                     | 1         | 3.57%   |
| Lenovo V310-14IKB 80T2                  | 1         | 3.57%   |
| Lenovo ThinkPad X201 3626FAG            | 1         | 3.57%   |
| Lenovo ThinkPad T470 20JNS3M500         | 1         | 3.57%   |
| Lenovo ThinkPad T400 2768WGB            | 1         | 3.57%   |
| Lenovo G570 20079                       | 1         | 3.57%   |
| Huanan X99 F8D V2.2                     | 1         | 3.57%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 3.57%   |
| Google Nautilus                         | 1         | 3.57%   |
| Gigabyte F2A55M-HD2                     | 1         | 3.57%   |
| Fujitsu S1100F                          | 1         | 3.57%   |
| Dell XPS 13 9343                        | 1         | 3.57%   |
| Dell XPS 13 9310                        | 1         | 3.57%   |
| Dell XPS 13 7390                        | 1         | 3.57%   |
| Dell Latitude E6410                     | 1         | 3.57%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN  | 1         | 3.57%   |
| ASUS VivoBook_ASUSLaptop X509DJ_M509DJ  | 1         | 3.57%   |
| ASUS VivoBook_ASUSLaptop X421UAY_M413UA | 1         | 3.57%   |
| ASUS ROG ZENITH II EXTREME              | 1         | 3.57%   |
| ASUS ROG Strix G533QS_G533QS            | 1         | 3.57%   |
| ASUS ROG Strix G533QR_G533QR            | 1         | 3.57%   |
| ASUS GL753VD                            | 1         | 3.57%   |
| Acer Aspire 5920                        | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 10.71%  |
| Dell XPS            | 3         | 10.71%  |
| ASUS VivoBook       | 3         | 10.71%  |
| ASUS ROG            | 3         | 10.71%  |
| Teclast F6          | 1         | 3.57%   |
| Positivo H14BT58    | 1         | 3.57%   |
| MSI MS-7C94         | 1         | 3.57%   |
| LG 22V280-L.BY31P1  | 1         | 3.57%   |
| Lenovo ZhaoYang     | 1         | 3.57%   |
| Lenovo Z50-70       | 1         | 3.57%   |
| Lenovo V310-14IKB   | 1         | 3.57%   |
| Lenovo G570         | 1         | 3.57%   |
| Huanan X99          | 1         | 3.57%   |
| HP Pavilion         | 1         | 3.57%   |
| Google Nautilus     | 1         | 3.57%   |
| Gigabyte F2A55M-HD2 | 1         | 3.57%   |
| Fujitsu S1100F      | 1         | 3.57%   |
| Dell Latitude       | 1         | 3.57%   |
| ASUS GL753VD        | 1         | 3.57%   |
| Acer Aspire         | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 11        | 39.29%  |
| 2020 | 4         | 14.29%  |
| 2019 | 2         | 7.14%   |
| 2018 | 2         | 7.14%   |
| 2017 | 2         | 7.14%   |
| 2015 | 1         | 3.57%   |
| 2014 | 1         | 3.57%   |
| 2013 | 1         | 3.57%   |
| 2012 | 1         | 3.57%   |
| 2011 | 1         | 3.57%   |
| 2010 | 1         | 3.57%   |
| 2008 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 22        | 78.57%  |
| Desktop    | 5         | 17.86%  |
| All in one | 1         | 3.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 26        | 92.86%  |
| Enabled  | 2         | 7.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 96.43%  |
| Yes  | 1         | 3.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 37.93%  |
| 32.01-64.0  | 5         | 17.24%  |
| 8.01-16.0   | 4         | 13.79%  |
| 3.01-4.0    | 3         | 10.34%  |
| 64.01-256.0 | 2         | 6.9%    |
| 16.01-24.0  | 2         | 6.9%    |
| 24.01-32.0  | 1         | 3.45%   |
| 1.01-2.0    | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 10        | 33.33%  |
| 4.01-8.0 | 8         | 26.67%  |
| 1.01-2.0 | 7         | 23.33%  |
| 3.01-4.0 | 5         | 16.67%  |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 18        | 64.29%  |
| 2      | 6         | 21.43%  |
| 3      | 3         | 10.71%  |
| 5      | 1         | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 78.57%  |
| Yes       | 6         | 21.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 71.43%  |
| No        | 8         | 28.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 85.71%  |
| No        | 4         | 14.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 75%     |
| No        | 7         | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| UK          | 5         | 17.86%  |
| USA         | 3         | 10.71%  |
| France      | 3         | 10.71%  |
| Brazil      | 3         | 10.71%  |
| Germany     | 2         | 7.14%   |
| Ukraine     | 1         | 3.57%   |
| Sweden      | 1         | 3.57%   |
| South Korea | 1         | 3.57%   |
| Russia      | 1         | 3.57%   |
| Lithuania   | 1         | 3.57%   |
| India       | 1         | 3.57%   |
| Hungary     | 1         | 3.57%   |
| Finland     | 1         | 3.57%   |
| Cyprus      | 1         | 3.57%   |
| China       | 1         | 3.57%   |
| Chile       | 1         | 3.57%   |
| Argentina   | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Yongin-si              | 1         | 3.57%   |
| Turku                  | 1         | 3.57%   |
| Trivandrum             | 1         | 3.57%   |
| Trakai                 | 1         | 3.57%   |
| Tottenham              | 1         | 3.57%   |
| Toms River             | 1         | 3.57%   |
| Tatab??nya             | 1         | 3.57%   |
| Shanghai               | 1         | 3.57%   |
| S??o Paulo             | 1         | 3.57%   |
| Santiago               | 1         | 3.57%   |
| Rosario                | 1         | 3.57%   |
| Rio de Janeiro         | 1         | 3.57%   |
| Paris                  | 1         | 3.57%   |
| Osasco                 | 1         | 3.57%   |
| Nizhny Tagil           | 1         | 3.57%   |
| Nicosia                | 1         | 3.57%   |
| Maidstone              | 1         | 3.57%   |
| Lyon                   | 1         | 3.57%   |
| Leiston                | 1         | 3.57%   |
| Kyiv                   | 1         | 3.57%   |
| Helsingborg            | 1         | 3.57%   |
| Haselhorst             | 1         | 3.57%   |
| Glasgow                | 1         | 3.57%   |
| Fellbach               | 1         | 3.57%   |
| Crewe                  | 1         | 3.57%   |
| Charleville-M?�zi??res | 1         | 3.57%   |
| Brooklyn               | 1         | 3.57%   |
| Austin                 | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 17.07%  |
| Samsung Electronics | 7         | 9      | 17.07%  |
| Toshiba             | 4         | 4      | 9.76%   |
| SanDisk             | 3         | 4      | 7.32%   |
| WDC                 | 2         | 2      | 4.88%   |
| Unknown             | 2         | 2      | 4.88%   |
| SK Hynix            | 2         | 2      | 4.88%   |
| Kingston            | 2         | 4      | 4.88%   |
| Intel               | 2         | 3      | 4.88%   |
| SPCC                | 1         | 1      | 2.44%   |
| SP                  | 1         | 1      | 2.44%   |
| Silicon Motion      | 1         | 3      | 2.44%   |
| PNY                 | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| KIOXIA-EXCERIA      | 1         | 1      | 2.44%   |
| KingDian            | 1         | 1      | 2.44%   |
| HGST                | 1         | 2      | 2.44%   |
| China               | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| SK Hynix HFM001TD3JX013N 1TB             | 2         | 4.65%   |
| Seagate Expansion 1TB                    | 2         | 4.65%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 2.33%   |
| WDC WD3200AAJS-56B4A0 320GB              | 1         | 2.33%   |
| Unknown SB64G  64GB                      | 1         | 2.33%   |
| Unknown MMC Card  64GB                   | 1         | 2.33%   |
| Toshiba NVMe SSD Drive 256GB             | 1         | 2.33%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 2.33%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 2.33%   |
| Toshiba HDWL120 2TB                      | 1         | 2.33%   |
| SPCC Solid State Disk 128GB              | 1         | 2.33%   |
| SP PC60 1TB                              | 1         | 2.33%   |
| Silicon Motion NVMe SSD Drive 256GB      | 1         | 2.33%   |
| Seagate ST9320423AS 320GB                | 1         | 2.33%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 2.33%   |
| Seagate BUP Slim RD 2TB                  | 1         | 2.33%   |
| Seagate BUP Slim BK 1TB                  | 1         | 2.33%   |
| Seagate BarraCuda SSD ZA500CM10002 500GB | 1         | 2.33%   |
| SanDisk SD9SN8W256G1102 256GB SSD        | 1         | 2.33%   |
| SanDisk SD7SB3Q064G 56GB SSD             | 1         | 2.33%   |
| Sandisk NVMe SSD Drive 500GB             | 1         | 2.33%   |
| Samsung SSD 980 PRO 500GB                | 1         | 2.33%   |
| Samsung SSD 980 PRO 2TB                  | 1         | 2.33%   |
| Samsung SSD 970 EVO 500GB                | 1         | 2.33%   |
| Samsung SSD 860 EVO 500GB                | 1         | 2.33%   |
| Samsung SSD 850 EVO 500GB                | 1         | 2.33%   |
| Samsung SSD 650 120GB                    | 1         | 2.33%   |
| Samsung MZVLQ512HALU-00000 512GB         | 1         | 2.33%   |
| Samsung MZALQ512HALU-000L2 512GB         | 1         | 2.33%   |
| PNY CS900 240GB SSD                      | 1         | 2.33%   |
| Micron 2300 NVMe 1024GB                  | 1         | 2.33%   |
| LITEON L8H-256V2G-11 M.2 2280 256GB SSD  | 1         | 2.33%   |
| KIOXIA-EXCERIA SATA SSD 480GB            | 1         | 2.33%   |
| Kingston SKC300S37A240G 240GB SSD        | 1         | 2.33%   |
| Kingston SHFS37A120G 120GB SSD           | 1         | 2.33%   |
| KingDian N400 240GB SSD                  | 1         | 2.33%   |
| Intel NVMe SSD Drive 512GB               | 1         | 2.33%   |
| Intel HBRPEKNX0101AHO 16GB               | 1         | 2.33%   |
| Intel HBRPEKNX0101AH 256GB               | 1         | 2.33%   |
| HGST HTS721010A9E630 1TB                 | 1         | 2.33%   |
| China SATA SSD 240GB                     | 1         | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 50%     |
| Toshiba | 3         | 3      | 25%     |
| WDC     | 2         | 2      | 16.67%  |
| HGST    | 1         | 2      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 21.43%  |
| SanDisk             | 2         | 2      | 14.29%  |
| Kingston            | 2         | 4      | 14.29%  |
| SPCC                | 1         | 1      | 7.14%   |
| Seagate             | 1         | 1      | 7.14%   |
| PNY                 | 1         | 1      | 7.14%   |
| LITEON              | 1         | 1      | 7.14%   |
| KIOXIA-EXCERIA      | 1         | 1      | 7.14%   |
| KingDian            | 1         | 1      | 7.14%   |
| China               | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 13        | 18     | 33.33%  |
| HDD     | 12        | 13     | 30.77%  |
| SSD     | 11        | 16     | 28.21%  |
| MMC     | 2         | 2      | 5.13%   |
| Unknown | 1         | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 17        | 25     | 47.22%  |
| NVMe | 13        | 18     | 36.11%  |
| SAS  | 4         | 5      | 11.11%  |
| MMC  | 2         | 2      | 5.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 20     | 65.22%  |
| 0.51-1.0   | 6         | 7      | 26.09%  |
| 1.01-2.0   | 2         | 2      | 8.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 51-100     | 8         | 27.59%  |
| 101-250    | 7         | 24.14%  |
| 251-500    | 5         | 17.24%  |
| 1001-2000  | 5         | 17.24%  |
| 501-1000   | 2         | 6.9%    |
| 21-50      | 1         | 3.45%   |
| 1-20       | 1         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 7         | 24.14%  |
| 21-50     | 6         | 20.69%  |
| 101-250   | 6         | 20.69%  |
| 51-100    | 4         | 13.79%  |
| 501-1000  | 3         | 10.34%  |
| 251-500   | 2         | 6.9%    |
| 1001-2000 | 1         | 3.45%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 18        | 28     | 54.55%  |
| Works    | 15        | 22     | 45.45%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 18        | 51.43%  |
| Samsung Electronics          | 5         | 14.29%  |
| AMD                          | 5         | 14.29%  |
| SK Hynix                     | 2         | 5.71%   |
| Toshiba America Info Systems | 1         | 2.86%   |
| Silicon Motion               | 1         | 2.86%   |
| Sandisk                      | 1         | 2.86%   |
| Micron Technology            | 1         | 2.86%   |
| ASMedia Technology           | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 7.89%   |
| SK Hynix NVMe SSD Controller                                                     | 2         | 5.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 5.26%   |
| Samsung NVMe Controller                                                          | 2         | 5.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 5.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 5.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 5.26%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 2.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.63%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2.63%   |
| Micron Non-Volatile memory controller                                            | 1         | 2.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.63%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.63%   |
| Intel SSD 660P Series                                                            | 1         | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.63%   |
| Intel Non-Volatile memory controller                                             | 1         | 2.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 2.63%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 2.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.63%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 2.63%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 1         | 2.63%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 2.63%   |
| AMD FCH IDE Controller                                                           | 1         | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 19        | 51.35%  |
| NVMe | 13        | 35.14%  |
| RAID | 3         | 8.11%   |
| IDE  | 2         | 5.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 75%     |
| AMD    | 7         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core m3-7Y30 CPU @ 1.00GHz               | 2         | 7.14%   |
| Intel Core i5 CPU M 540 @ 2.53GHz              | 2         | 7.14%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 2         | 7.14%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz            | 1         | 3.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 3.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 3.57%   |
| Intel Core i7-4510U CPU @ 2.00GHz              | 1         | 3.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 1         | 3.57%   |
| Intel Core i5-9300H CPU @ 2.40GHz              | 1         | 3.57%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 3.57%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 1         | 3.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 1         | 3.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 1         | 3.57%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz           | 1         | 3.57%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 1         | 3.57%   |
| Intel Celeron N4100 CPU @ 1.10GHz              | 1         | 3.57%   |
| Intel Celeron CPU N2807 @ 1.58GHz              | 1         | 3.57%   |
| Intel Celeron CPU B800 @ 1.50GHz               | 1         | 3.57%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 3.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 3.57%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1         | 3.57%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 3.57%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 1         | 3.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 3.57%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 7         | 25%     |
| Intel Core i7          | 4         | 14.29%  |
| Intel Celeron          | 3         | 10.71%  |
| AMD Ryzen 5            | 3         | 10.71%  |
| Other                  | 2         | 7.14%   |
| Intel Core m3          | 2         | 7.14%   |
| Intel Core 2 Duo       | 2         | 7.14%   |
| AMD Ryzen 9            | 2         | 7.14%   |
| Intel Xeon             | 1         | 3.57%   |
| AMD Ryzen Threadripper | 1         | 3.57%   |
| AMD A4                 | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 12        | 42.86%  |
| 4      | 9         | 32.14%  |
| 8      | 2         | 7.14%   |
| 6      | 2         | 7.14%   |
| 32     | 1         | 3.57%   |
| 28     | 1         | 3.57%   |
| 1      | 1         | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 96.43%  |
| 2      | 1         | 3.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 78.57%  |
| 1      | 6         | 21.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 46.43%  |
| 0x806e9    | 3         | 10.71%  |
| 0x806c1    | 2         | 7.14%   |
| 0x906ea    | 1         | 3.57%   |
| 0x906e9    | 1         | 3.57%   |
| 0x806ec    | 1         | 3.57%   |
| 0x806eb    | 1         | 3.57%   |
| 0x306d4    | 1         | 3.57%   |
| 0x206a7    | 1         | 3.57%   |
| 0x20652    | 1         | 3.57%   |
| 0x1067a    | 1         | 3.57%   |
| 0x0a50000b | 1         | 3.57%   |
| 0x08608103 | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 28.57%  |
| Zen 3         | 3         | 10.71%  |
| Westmere      | 2         | 7.14%   |
| TigerLake     | 2         | 7.14%   |
| Penryn        | 2         | 7.14%   |
| Broadwell     | 2         | 7.14%   |
| Zen+          | 1         | 3.57%   |
| Zen 2         | 1         | 3.57%   |
| Skylake       | 1         | 3.57%   |
| Silvermont    | 1         | 3.57%   |
| SandyBridge   | 1         | 3.57%   |
| Piledriver    | 1         | 3.57%   |
| Haswell       | 1         | 3.57%   |
| Goldmont plus | 1         | 3.57%   |
| Unknown       | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 19        | 54.29%  |
| Nvidia | 10        | 28.57%  |
| AMD    | 6         | 17.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 5.26%   |
| Intel HD Graphics 630                                                     | 2         | 5.26%   |
| Intel HD Graphics 615                                                     | 2         | 5.26%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 5.26%   |
| AMD Cezanne                                                               | 2         | 5.26%   |
| Nvidia NV44 [GeForce 6200 LE]                                             | 1         | 2.63%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 2.63%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 2.63%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 2.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 2.63%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                               | 1         | 2.63%   |
| Nvidia GK208B [GeForce GT 710]                                            | 1         | 2.63%   |
| Nvidia GK104 [GeForce GTX 680]                                            | 1         | 2.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 2.63%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 1         | 2.63%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 1         | 2.63%   |
| Nvidia GA102 [GeForce RTX 3090]                                           | 1         | 2.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 2.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 2.63%   |
| Intel HD Graphics 620                                                     | 1         | 2.63%   |
| Intel HD Graphics 5500                                                    | 1         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 2.63%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 2.63%   |
| AMD Trinity 2 [Radeon HD 7480D]                                           | 1         | 2.63%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                              | 1         | 2.63%   |
| AMD Picasso                                                               | 1         | 2.63%   |
| AMD Lucienne                                                              | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 53.57%  |
| Intel + Nvidia | 4         | 14.29%  |
| AMD + Nvidia   | 3         | 10.71%  |
| 1 x AMD        | 3         | 10.71%  |
| 2 x Nvidia     | 2         | 7.14%   |
| 1 x Nvidia     | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 21        | 75%     |
| Proprietary | 6         | 21.43%  |
| Unknown     | 1         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 75%     |
| 1.01-2.0   | 4         | 14.29%  |
| 0.01-0.5   | 3         | 10.71%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 16.13%  |
| Sharp               | 3         | 9.68%   |
| Lenovo              | 3         | 9.68%   |
| Chimei Innolux      | 3         | 9.68%   |
| BOE                 | 3         | 9.68%   |
| Samsung Electronics | 2         | 6.45%   |
| Dell                | 2         | 6.45%   |
| Acer                | 2         | 6.45%   |
| SKY                 | 1         | 3.23%   |
| RTK                 | 1         | 3.23%   |
| PANDA               | 1         | 3.23%   |
| LG Electronics      | 1         | 3.23%   |
| LG Display          | 1         | 3.23%   |
| KDC                 | 1         | 3.23%   |
| InfoVision          | 1         | 3.23%   |
| AOC                 | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Acer XV340CK P ACR06F3 3440x1440 800x335mm 34.1-inch                 | 2         | 6.25%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                 | 1         | 3.13%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 3.13%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch              | 1         | 3.13%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch | 1         | 3.13%   |
| RTK LCD Monitor RTK2136 1280x800 473x296mm 22.0-inch                 | 1         | 3.13%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch              | 1         | 3.13%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 1         | 3.13%   |
| LG Electronics LCD Monitor LG ULTRAWIDE                              | 1         | 3.13%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 1         | 3.13%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch             | 1         | 3.13%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch              | 1         | 3.13%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 3.13%   |
| KDC LCD Monitor KDC0001 1920x1200 263x164mm 12.2-inch                | 1         | 3.13%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch         | 1         | 3.13%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                    | 1         | 3.13%   |
| Dell LCD Monitor P2419H 4480x1080                                    | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 1         | 3.13%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                | 1         | 3.13%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                | 1         | 3.13%   |
| BOE LCD Monitor BOE05EC 1366x768 309x173mm 13.9-inch                 | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 3.13%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                     | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 14        | 45.16%  |
| 3440x1440         | 2         | 6.45%   |
| 2560x1440 (QHD)   | 2         | 6.45%   |
| 1920x1200 (WUXGA) | 2         | 6.45%   |
| 1440x900 (WXGA+)  | 2         | 6.45%   |
| 1366x768 (WXGA)   | 2         | 6.45%   |
| 1280x800 (WXGA)   | 2         | 6.45%   |
| 4480x1080         | 1         | 3.23%   |
| 3840x2400         | 1         | 3.23%   |
| 3200x1800 (QHD+)  | 1         | 3.23%   |
| 2560x1080         | 1         | 3.23%   |
| Unknown           | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 8         | 26.67%  |
| 13      | 8         | 26.67%  |
| 34      | 2         | 6.67%   |
| 24      | 2         | 6.67%   |
| 17      | 2         | 6.67%   |
| 14      | 2         | 6.67%   |
| 12      | 2         | 6.67%   |
| 40      | 1         | 3.33%   |
| 27      | 1         | 3.33%   |
| 23      | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 44.83%  |
| 201-300     | 7         | 24.14%  |
| 501-600     | 3         | 10.34%  |
| 701-800     | 2         | 6.9%    |
| 351-400     | 2         | 6.9%    |
| 801-900     | 1         | 3.45%   |
| Unknown     | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 19        | 63.33%  |
| 16/10   | 7         | 23.33%  |
| 21/9    | 2         | 6.67%   |
| 3/2     | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 26.67%  |
| 81-90          | 5         | 16.67%  |
| 71-80          | 5         | 16.67%  |
| 61-70          | 2         | 6.67%   |
| 351-500        | 2         | 6.67%   |
| 201-250        | 2         | 6.67%   |
| 301-350        | 1         | 3.33%   |
| 251-300        | 1         | 3.33%   |
| 131-140        | 1         | 3.33%   |
| 121-130        | 1         | 3.33%   |
| 501-1000       | 1         | 3.33%   |
| Unknown        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 41.38%  |
| 161-240       | 5         | 17.24%  |
| 101-120       | 4         | 13.79%  |
| 51-100        | 4         | 13.79%  |
| More than 240 | 2         | 6.9%    |
| 1-50          | 1         | 3.45%   |
| Unknown       | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 24        | 82.76%  |
| 2     | 4         | 13.79%  |
| 0     | 1         | 3.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 15        | 37.5%   |
| Intel                         | 13        | 32.5%   |
| Qualcomm Atheros              | 4         | 10%     |
| MEDIATEK                      | 2         | 5%      |
| Xiaomi                        | 1         | 2.5%    |
| Qualcomm                      | 1         | 2.5%    |
| OnePlus Technology (Shenzhen) | 1         | 2.5%    |
| Broadcom Limited              | 1         | 2.5%    |
| Broadcom                      | 1         | 2.5%    |
| Aquantia                      | 1         | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 23.4%   |
| MEDIATEK Network controller                                       | 2         | 4.26%   |
| Intel Wireless 7265                                               | 2         | 4.26%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 4.26%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 4.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.13%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 1         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.13%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 2.13%   |
| Intel Wireless 8265 / 8275                                        | 1         | 2.13%   |
| Intel Wireless 8260                                               | 1         | 2.13%   |
| Intel Wireless 3165                                               | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 2.13%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.13%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 2.13%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 2.13%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.13%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.13%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 2.13%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 50%     |
| Realtek Semiconductor | 4         | 16.67%  |
| Qualcomm Atheros      | 4         | 16.67%  |
| MEDIATEK              | 2         | 8.33%   |
| Qualcomm              | 1         | 4.17%   |
| Broadcom Limited      | 1         | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| MEDIATEK Network controller                                    | 2         | 8.33%   |
| Intel Wireless 7265                                            | 2         | 8.33%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 8.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 4.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 4.17%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 4.17%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 1         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 4.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 4.17%   |
| Intel Wireless 8265 / 8275                                     | 1         | 4.17%   |
| Intel Wireless 8260                                            | 1         | 4.17%   |
| Intel Wireless 3165                                            | 1         | 4.17%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 4.17%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 4.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 4.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 4.17%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 4.17%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 13        | 56.52%  |
| Intel                         | 5         | 21.74%  |
| Xiaomi                        | 1         | 4.35%   |
| Qualcomm Atheros              | 1         | 4.35%   |
| OnePlus Technology (Shenzhen) | 1         | 4.35%   |
| Broadcom                      | 1         | 4.35%   |
| Aquantia                      | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 47.83%  |
| Intel 82577LM Gigabit Network Connection                          | 2         | 8.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 4.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 4.35%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 1         | 4.35%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.35%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4.35%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 4.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 54.55%  |
| Ethernet | 20        | 45.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 63.64%  |
| Ethernet | 12        | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 15        | 53.57%  |
| 1     | 12        | 42.86%  |
| 3     | 1         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 23        | 82.14%  |
| Yes  | 5         | 17.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 42.86%  |
| Qualcomm Atheros Communications | 3         | 14.29%  |
| IMC Networks                    | 3         | 14.29%  |
| Realtek Semiconductor           | 2         | 9.52%   |
| Lite-On Technology              | 1         | 4.76%   |
| Foxconn / Hon Hai               | 1         | 4.76%   |
| Cambridge Silicon Radio         | 1         | 4.76%   |
| Broadcom                        | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 8         | 38.1%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 9.52%   |
| IMC Networks Wireless_Device                        | 2         | 9.52%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.76%   |
| Realtek Bluetooth Radio                             | 1         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.76%   |
| Lite-On Bluetooth Radio                             | 1         | 4.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.76%   |
| IMC Networks Bluetooth Radio                        | 1         | 4.76%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.76%   |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 21        | 53.85%  |
| Nvidia                            | 6         | 15.38%  |
| AMD                               | 6         | 15.38%  |
| Elitegroup Computer Systems (ECS) | 2         | 5.13%   |
| XMOS                              | 1         | 2.56%   |
| Focusrite-Novation                | 1         | 2.56%   |
| Corsair                           | 1         | 2.56%   |
| ASUSTek Computer                  | 1         | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 8.51%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 4         | 8.51%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 6.38%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 4.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 4.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 4.26%   |
| Elitegroup Computer Systems (ECS) FOSTEX USB AUDIO HP-A4                   | 2         | 4.26%   |
| XMOS HIFI DSD                                                              | 1         | 2.13%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 2.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 2.13%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.13%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.13%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.13%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 2.13%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.13%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.13%   |
| Focusrite-Novation Scarlett 18i20 3rd Gen                                  | 1         | 2.13%   |
| Corsair HS70 Pro Wireless Gaming Headset                                   | 1         | 2.13%   |
| ASUSTek Computer USB Audio                                                 | 1         | 2.13%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 2.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.13%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 34.78%  |
| SK Hynix            | 5         | 21.74%  |
| Micron Technology   | 4         | 17.39%  |
| Unknown             | 2         | 8.7%    |
| Crucial             | 2         | 8.7%    |
| Kingston            | 1         | 4.35%   |
| Elpida              | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 8.7%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 8.7%    |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                           | 1         | 4.35%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 4.35%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s                | 1         | 4.35%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 4.35%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 4.35%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 4.35%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s            | 1         | 4.35%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 1         | 4.35%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DIMM DDR4 2667MT/s                 | 1         | 4.35%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s                 | 1         | 4.35%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s              | 1         | 4.35%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s         | 1         | 4.35%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 1         | 4.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 4.35%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s           | 1         | 4.35%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s              | 1         | 4.35%   |
| Elpida RAM Module 4GB Row Of Chips LPDDR3 1867MT/s                  | 1         | 4.35%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s          | 1         | 4.35%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s               | 1         | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 11        | 55%     |
| DDR3   | 4         | 20%     |
| LPDDR3 | 3         | 15%     |
| LPDDR4 | 2         | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 55%     |
| Row Of Chips | 4         | 20%     |
| DIMM         | 4         | 20%     |
| Chip         | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 7         | 31.82%  |
| 4096  | 7         | 31.82%  |
| 2048  | 4         | 18.18%  |
| 16384 | 3         | 13.64%  |
| 32768 | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 5         | 23.81%  |
| 3200  | 4         | 19.05%  |
| 4267  | 2         | 9.52%   |
| 1867  | 2         | 9.52%   |
| 1600  | 2         | 9.52%   |
| 3733  | 1         | 4.76%   |
| 3600  | 1         | 4.76%   |
| 3400  | 1         | 4.76%   |
| 2133  | 1         | 4.76%   |
| 1334  | 1         | 4.76%   |
| 1067  | 1         | 4.76%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor              | Computers | Percent |
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

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                              | Computers | Percent |
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
| Chicony LG HD WebCam               | 1         | 4.55%   |
| Chicony Lenovo EasyCamera          | 1         | 4.55%   |
| Chicony HP Wide Vision HD Camera   | 1         | 4.55%   |
| Chicony EasyCamera                 | 1         | 4.55%   |
| Chicony 720p HD Camera             | 1         | 4.55%   |
| Alcor Micro USB 2.0 PC Camera      | 1         | 4.55%   |
| Acer Integrated Camera             | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 40%     |
| Validity Sensors           | 1         | 20%     |
| Upek                       | 1         | 20%     |
| Elan Microelectronics      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 20%     |
| Shenzhen Goodix FingerPrint                            | 1         | 20%     |
| Elan ELAN:Fingerprint                                  | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 15        | 53.57%  |
| 1     | 11        | 39.29%  |
| 2     | 2         | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 5         | 35.71%  |
| Chipcard           | 3         | 21.43%  |
| Net/wireless       | 2         | 14.29%  |
| Graphics card      | 2         | 14.29%  |
| Unassigned class   | 1         | 7.14%   |
| Bluetooth          | 1         | 7.14%   |

