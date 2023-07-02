Trisquel - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Trisquel.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Trisquel/Desktop/README.md) and [notebooks](/Dist/Trisquel/Notebook/README.md).

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

Total: 43

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | NB510                       | Notebook    | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [4f777df0e8](https://linux-hardware.org/?probe=4f777df0e8) | Apr 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [c5824f9cae](https://linux-hardware.org/?probe=c5824f9cae) | Apr 25, 2023 |
| Itautec       | Infoway                     | Notebook    | [c046d6e093](https://linux-hardware.org/?probe=c046d6e093) | Apr 16, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [185c4824b7](https://linux-hardware.org/?probe=185c4824b7) | Apr 07, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [89a021b8f6](https://linux-hardware.org/?probe=89a021b8f6) | Dec 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [5b13c289e1](https://linux-hardware.org/?probe=5b13c289e1) | Nov 26, 2022 |
| Libiquity     | Taurinus X200               | Notebook    | [75c0f41e26](https://linux-hardware.org/?probe=75c0f41e26) | Nov 09, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [ab06dd40c4](https://linux-hardware.org/?probe=ab06dd40c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [5b08d764b4](https://linux-hardware.org/?probe=5b08d764b4) | Sep 27, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [08a8ad598f](https://linux-hardware.org/?probe=08a8ad598f) | Sep 23, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [8e620e891f](https://linux-hardware.org/?probe=8e620e891f) | Sep 23, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [a9e525c695](https://linux-hardware.org/?probe=a9e525c695) | Sep 16, 2022 |
| Timi          | TM1709                      | Notebook    | [2fb5436031](https://linux-hardware.org/?probe=2fb5436031) | Sep 04, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [8d7c5df586](https://linux-hardware.org/?probe=8d7c5df586) | Sep 03, 2022 |
| ASUSTek       | K55A                        | Notebook    | [5d11054a36](https://linux-hardware.org/?probe=5d11054a36) | Aug 28, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [4b8f3feaa7](https://linux-hardware.org/?probe=4b8f3feaa7) | Aug 25, 2022 |
| Lenovo        | ThinkPad T420 4177QKU       | Notebook    | [a18ab36f34](https://linux-hardware.org/?probe=a18ab36f34) | Aug 17, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [f6abe5392b](https://linux-hardware.org/?probe=f6abe5392b) | Aug 03, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7682000c35](https://linux-hardware.org/?probe=7682000c35) | Jul 30, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [b25d6bf66c](https://linux-hardware.org/?probe=b25d6bf66c) | Jul 27, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fc499e7600](https://linux-hardware.org/?probe=fc499e7600) | Jul 27, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [0145453c1a](https://linux-hardware.org/?probe=0145453c1a) | May 27, 2022 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | Desktop     | [a9d7621b8d](https://linux-hardware.org/?probe=a9d7621b8d) | May 26, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [92fd051a13](https://linux-hardware.org/?probe=92fd051a13) | May 15, 2022 |
| Lenovo        | ThinkPad T420 4177QKU       | Notebook    | [215758ad8a](https://linux-hardware.org/?probe=215758ad8a) | Apr 30, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [1126937638](https://linux-hardware.org/?probe=1126937638) | Apr 28, 2022 |
| HP            | 8299                        | Desktop     | [7a54bfae05](https://linux-hardware.org/?probe=7a54bfae05) | Apr 28, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [f41f324f01](https://linux-hardware.org/?probe=f41f324f01) | Apr 25, 2022 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [53753f59d3](https://linux-hardware.org/?probe=53753f59d3) | Feb 13, 2022 |
| Toshiba       | Satellite C800D             | Notebook    | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Samsung       | N130                        | Notebook    | [1a88380af6](https://linux-hardware.org/?probe=1a88380af6) | Nov 27, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [89cf2685e2](https://linux-hardware.org/?probe=89cf2685e2) | Nov 01, 2021 |
| ASUSTek       | U56E                        | Notebook    | [99bd7dbfdf](https://linux-hardware.org/?probe=99bd7dbfdf) | Sep 09, 2021 |
| Lenovo        | ThinkPad X200 7455FNG       | Notebook    | [6fcadf1396](https://linux-hardware.org/?probe=6fcadf1396) | Mar 20, 2021 |
| Samsung       | Galaxy TabPro S             | Tablet      | [4e4ef907a0](https://linux-hardware.org/?probe=4e4ef907a0) | Feb 05, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [49fde2499f](https://linux-hardware.org/?probe=49fde2499f) | Jul 18, 2020 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [5ea27e2813](https://linux-hardware.org/?probe=5ea27e2813) | Jul 18, 2020 |
| Acer          | TravelMate B115-M           | Notebook    | [62239072f1](https://linux-hardware.org/?probe=62239072f1) | Nov 26, 2019 |
| GPD           | MicroPC                     | Notebook    | [8fc0176f69](https://linux-hardware.org/?probe=8fc0176f69) | Sep 28, 2019 |
| ECS           | H61H2-M2                    | Desktop     | [add4f52268](https://linux-hardware.org/?probe=add4f52268) | Mar 06, 2019 |
| ECS           | H61H2-M2                    | Desktop     | [f9376ff405](https://linux-hardware.org/?probe=f9376ff405) | May 03, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Trisquel 10.0.1 | 17        | 51.52%  |
| Trisquel 9.0    | 5         | 15.15%  |
| Trisquel 11.0   | 5         | 15.15%  |
| Trisquel 8.0    | 3         | 9.09%   |
| Trisquel 10.0   | 3         | 9.09%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Trisquel | 33        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.4.0-96-generic     | 4         | 11.11%  |
| 5.4.0-122-generic    | 4         | 11.11%  |
| 5.4.0-125-generic    | 3         | 8.33%   |
| 5.4.0-113-generic    | 3         | 8.33%   |
| 5.4.0-126-generic    | 2         | 5.56%   |
| 5.4.0-109-generic    | 2         | 5.56%   |
| 5.15.0-69-generic    | 2         | 5.56%   |
| 6.0.12-x64v1-xanmod1 | 1         | 2.78%   |
| 5.4.0-135-generic    | 1         | 2.78%   |
| 5.4.0-132-generic    | 1         | 2.78%   |
| 5.4.0-131-generic    | 1         | 2.78%   |
| 5.4.0-110-generic    | 1         | 2.78%   |
| 5.3.13-gnu           | 1         | 2.78%   |
| 5.3.1-gnu            | 1         | 2.78%   |
| 5.15.0-73-generic    | 1         | 2.78%   |
| 5.15.0-67-generic    | 1         | 2.78%   |
| 5.10.177-gnu1        | 1         | 2.78%   |
| 4.4.0-119-generic    | 1         | 2.78%   |
| 4.15.0-161-generic   | 1         | 2.78%   |
| 4.15.0-156-generic   | 1         | 2.78%   |
| 4.15.0-136-generic   | 1         | 2.78%   |
| 4.15.0-121-generic   | 1         | 2.78%   |
| 4.15.0-108-generic   | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 19        | 57.58%  |
| 4.15.0   | 5         | 15.15%  |
| 5.15.0   | 4         | 12.12%  |
| 6.0.12   | 1         | 3.03%   |
| 5.3.13   | 1         | 3.03%   |
| 5.3.1    | 1         | 3.03%   |
| 5.10.177 | 1         | 3.03%   |
| 4.4.0    | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 57.58%  |
| 4.15    | 5         | 15.15%  |
| 5.15    | 4         | 12.12%  |
| 5.3     | 2         | 6.06%   |
| 6.0     | 1         | 3.03%   |
| 5.10    | 1         | 3.03%   |
| 4.4     | 1         | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 93.94%  |
| i686   | 1         | 3.03%   |
| armv7l | 1         | 3.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 24        | 72.73%  |
| LXDE    | 3         | 9.09%   |
| Unknown | 2         | 6.06%   |
| KDE     | 1         | 3.03%   |
| GNOME   | 1         | 3.03%   |
| dwm     | 1         | 3.03%   |
| default | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 31        | 93.94%  |
| Wayland | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 21        | 63.64%  |
| Unknown | 7         | 21.21%  |
| TDM     | 4         | 12.12%  |
| GDM     | 1         | 3.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 14        | 42.42%  |
| fr_FR   | 4         | 12.12%  |
| ru_RU   | 3         | 9.09%   |
| C       | 3         | 9.09%   |
| Unknown | 3         | 9.09%   |
| ru_UA   | 1         | 3.03%   |
| pt_BR   | 1         | 3.03%   |
| es_MX   | 1         | 3.03%   |
| es_ES   | 1         | 3.03%   |
| en_GB   | 1         | 3.03%   |
| en_CA   | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 17        | 51.52%  |
| EFI  | 16        | 48.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 29        | 87.88%  |
| Overlay | 2         | 6.06%   |
| Xfs     | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 23        | 69.7%   |
| Unknown | 7         | 21.21%  |
| MBR     | 3         | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 77.14%  |
| Yes       | 8         | 22.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 81.82%  |
| Yes       | 6         | 18.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 5         | 15.15%  |
| Dell                | 4         | 12.12%  |
| ASUSTek Computer    | 4         | 12.12%  |
| Toshiba             | 2         | 6.06%   |
| Samsung Electronics | 2         | 6.06%   |
| Hewlett-Packard     | 2         | 6.06%   |
| Acer                | 2         | 6.06%   |
| Timi                | 1         | 3.03%   |
| Packard Bell        | 1         | 3.03%   |
| MSI                 | 1         | 3.03%   |
| Libiquity           | 1         | 3.03%   |
| Itautec             | 1         | 3.03%   |
| Huanan              | 1         | 3.03%   |
| GPD                 | 1         | 3.03%   |
| Gigabyte Technology | 1         | 3.03%   |
| Fujitsu Siemens     | 1         | 3.03%   |
| ECS                 | 1         | 3.03%   |
| Apple               | 1         | 3.03%   |
| Unknown             | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                  | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo ThinkPad T420 4177QKU                                          | 2         | 6.06%   |
| Toshiba Satellite C800D                                               | 1         | 3.03%   |
| Toshiba NB510                                                         | 1         | 3.03%   |
| Timi TM1709                                                           | 1         | 3.03%   |
| Samsung N130                                                          | 1         | 3.03%   |
| Samsung Galaxy TabPro S                                               | 1         | 3.03%   |
| Packard Bell IMEDIA S1300                                             | 1         | 3.03%   |
| MSI MS-7917                                                           | 1         | 3.03%   |
| Libiquity Taurinus X200                                               | 1         | 3.03%   |
| Lenovo ThinkPad X200 7455FNG                                          | 1         | 3.03%   |
| Lenovo ThinkPad T430 2347G2U                                          | 1         | 3.03%   |
| Lenovo G505s 20255                                                    | 1         | 3.03%   |
| Itautec Infoway                                                       | 1         | 3.03%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1         | 3.03%   |
| HP Stream Laptop 11-y0XX                                              | 1         | 3.03%   |
| HP EliteDesk 800 G3 SFF                                               | 1         | 3.03%   |
| GPD MicroPC                                                           | 1         | 3.03%   |
| Gigabyte M68MT-D3P                                                    | 1         | 3.03%   |
| Fujitsu Siemens ESPRIMO EDITION P2540                                 | 1         | 3.03%   |
| ECS H61H2-M2                                                          | 1         | 3.03%   |
| Dell XPS 13 9360                                                      | 1         | 3.03%   |
| Dell OptiPlex 3020                                                    | 1         | 3.03%   |
| Dell Inspiron 1545                                                    | 1         | 3.03%   |
| Dell Inspiron 15-3567                                                 | 1         | 3.03%   |
| ASUS U56E                                                             | 1         | 3.03%   |
| ASUS P8H61                                                            | 1         | 3.03%   |
| ASUS K55A                                                             | 1         | 3.03%   |
| ASUS A55BM-PLUS                                                       | 1         | 3.03%   |
| Apple MacPro5,1                                                       | 1         | 3.03%   |
| Acer TravelMate B115-M                                                | 1         | 3.03%   |
| Acer Nitro AN517-54                                                   | 1         | 3.03%   |
| Unknown                                                               | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 4         | 12.12%  |
| Dell Inspiron           | 2         | 6.06%   |
| Toshiba Satellite       | 1         | 3.03%   |
| Toshiba NB510           | 1         | 3.03%   |
| Timi TM1709             | 1         | 3.03%   |
| Samsung N130            | 1         | 3.03%   |
| Samsung Galaxy          | 1         | 3.03%   |
| Packard Bell IMEDIA     | 1         | 3.03%   |
| MSI MS-7917             | 1         | 3.03%   |
| Libiquity Taurinus      | 1         | 3.03%   |
| Lenovo G505s            | 1         | 3.03%   |
| Itautec Infoway         | 1         | 3.03%   |
| Huanan X79              | 1         | 3.03%   |
| HP Stream               | 1         | 3.03%   |
| HP EliteDesk            | 1         | 3.03%   |
| GPD MicroPC             | 1         | 3.03%   |
| Gigabyte M68MT-D3P      | 1         | 3.03%   |
| Fujitsu Siemens ESPRIMO | 1         | 3.03%   |
| ECS H61H2-M2            | 1         | 3.03%   |
| Dell XPS                | 1         | 3.03%   |
| Dell OptiPlex           | 1         | 3.03%   |
| ASUS U56E               | 1         | 3.03%   |
| ASUS P8H61              | 1         | 3.03%   |
| ASUS K55A               | 1         | 3.03%   |
| ASUS A55BM-PLUS         | 1         | 3.03%   |
| Apple MacPro5           | 1         | 3.03%   |
| Acer TravelMate         | 1         | 3.03%   |
| Acer Nitro              | 1         | 3.03%   |
| Unknown                 | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 5         | 15.15%  |
| 2016    | 4         | 12.12%  |
| 2012    | 4         | 12.12%  |
| 2008    | 4         | 12.12%  |
| 2014    | 3         | 9.09%   |
| 2010    | 3         | 9.09%   |
| 2018    | 2         | 6.06%   |
| 2013    | 2         | 6.06%   |
| 2021    | 1         | 3.03%   |
| 2019    | 1         | 3.03%   |
| 2017    | 1         | 3.03%   |
| 2015    | 1         | 3.03%   |
| 2009    | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 20        | 60.61%  |
| Desktop  | 12        | 36.36%  |
| Tablet   | 1         | 3.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 33        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 93.94%  |
| Yes  | 2         | 6.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 12        | 36.36%  |
| 8.01-16.0  | 7         | 21.21%  |
| 3.01-4.0   | 4         | 12.12%  |
| 16.01-24.0 | 4         | 12.12%  |
| 1.01-2.0   | 4         | 12.12%  |
| 32.01-64.0 | 1         | 3.03%   |
| 0.51-1.0   | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 21        | 60%     |
| 2.01-3.0 | 4         | 11.43%  |
| 0.51-1.0 | 3         | 8.57%   |
| 0.01-0.5 | 3         | 8.57%   |
| 4.01-8.0 | 2         | 5.71%   |
| 3.01-4.0 | 2         | 5.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 22        | 64.71%  |
| 2      | 9         | 26.47%  |
| 4      | 1         | 2.94%   |
| 3      | 1         | 2.94%   |
| 0      | 1         | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 57.58%  |
| No        | 14        | 42.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 96.97%  |
| No        | 1         | 3.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 79.41%  |
| No        | 7         | 20.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 19        | 57.58%  |
| Yes       | 14        | 42.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 10        | 30.3%   |
| France      | 6         | 18.18%  |
| Russia      | 3         | 9.09%   |
| China       | 3         | 9.09%   |
| Spain       | 2         | 6.06%   |
| Brazil      | 2         | 6.06%   |
| Ukraine     | 1         | 3.03%   |
| Netherlands | 1         | 3.03%   |
| Mexico      | 1         | 3.03%   |
| Ireland     | 1         | 3.03%   |
| Indonesia   | 1         | 3.03%   |
| Germany     | 1         | 3.03%   |
| Canada      | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Lincoln           | 3         | 9.09%   |
| Corbeil-Essonnes  | 3         | 9.09%   |
| Omaha             | 2         | 6.06%   |
| Moscow            | 2         | 6.06%   |
| Malvern           | 2         | 6.06%   |
| Wylie             | 1         | 3.03%   |
| Wiesbaden         | 1         | 3.03%   |
| Vienne-le-Chateau | 1         | 3.03%   |
| St Petersburg     | 1         | 3.03%   |
| Shenzhen          | 1         | 3.03%   |
| Sabadell          | 1         | 3.03%   |
| Rivne             | 1         | 3.03%   |
| Pinangsia         | 1         | 3.03%   |
| Paris             | 1         | 3.03%   |
| Oviedo            | 1         | 3.03%   |
| Ottawa            | 1         | 3.03%   |
| Missoula          | 1         | 3.03%   |
| Guangzhou         | 1         | 3.03%   |
| Cork              | 1         | 3.03%   |
| Ciudad del Carmen | 1         | 3.03%   |
| Chengdu           | 1         | 3.03%   |
| Cerons            | 1         | 3.03%   |
| Blumenau          | 1         | 3.03%   |
| Amsterdam         | 1         | 3.03%   |
| Americana         | 1         | 3.03%   |
| Acworth           | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 14     | 17.5%   |
| Samsung Electronics | 7         | 7      | 17.5%   |
| Toshiba             | 4         | 4      | 10%     |
| WDC                 | 3         | 3      | 7.5%    |
| Sandisk             | 3         | 3      | 7.5%    |
| HGST HTS            | 2         | 4      | 5%      |
| Crucial             | 2         | 2      | 5%      |
| China               | 2         | 2      | 5%      |
| Unknown             | 1         | 1      | 2.5%    |
| Transcend           | 1         | 1      | 2.5%    |
| Silicon Motion      | 1         | 2      | 2.5%    |
| Qumo                | 1         | 1      | 2.5%    |
| Plextor             | 1         | 1      | 2.5%    |
| NFHK                | 1         | 1      | 2.5%    |
| LITEON              | 1         | 1      | 2.5%    |
| Kingston            | 1         | 1      | 2.5%    |
| Hitachi             | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 2         | 4.65%   |
| Seagate ST4000NM 0033-9ZM170 4TB     | 2         | 4.65%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 4.65%   |
| HGST HTS 721010A9E630 1TB            | 2         | 4.65%   |
| WDC WD6400BPVT-80HXZT3 640GB         | 1         | 2.33%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 2.33%   |
| WDC WD3200AAKX-221CA1 320GB          | 1         | 2.33%   |
| Unknown SA32G  32GB                  | 1         | 2.33%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 2.33%   |
| Toshiba THNSN5256GPUK NVMe 256GB     | 1         | 2.33%   |
| Toshiba MK3275GSX 320GB              | 1         | 2.33%   |
| Toshiba HDWL110 1TB                  | 1         | 2.33%   |
| Toshiba DT01ACA100 1TB               | 1         | 2.33%   |
| Silicon Motion MS10 1TB              | 1         | 2.33%   |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 2.33%   |
| Seagate ST31000524AS 1TB             | 1         | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 2.33%   |
| Seagate ST1000DM003-9YN162 1TB       | 1         | 2.33%   |
| Sandisk WD Blue SN570 1TB            | 1         | 2.33%   |
| SanDisk SSD PLUS 240GB               | 1         | 2.33%   |
| SanDisk DF4032  32GB                 | 1         | 2.33%   |
| Samsung SSD 860 EVO 500GB            | 1         | 2.33%   |
| Samsung SSD 840 EVO 120GB            | 1         | 2.33%   |
| Samsung MZVLW256HEHP-000H1 256GB     | 1         | 2.33%   |
| Samsung MZVLQ512HBLU-00BTW 512GB     | 1         | 2.33%   |
| Samsung MZNLN128HAHQ-00000 128GB SSD | 1         | 2.33%   |
| Samsung HM251JI 250GB                | 1         | 2.33%   |
| Samsung HM160HI 160GB                | 1         | 2.33%   |
| Qumo SSD 120GB                       | 1         | 2.33%   |
| Plextor PX-512M5Pro 512GB SSD        | 1         | 2.33%   |
| NFHK USB 3.0 120GB                   | 1         | 2.33%   |
| LITEON CV1-8B128 128GB SSD           | 1         | 2.33%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 2.33%   |
| Hitachi HTS547575A9E384 752GB        | 1         | 2.33%   |
| Crucial CT250BX100SSD1 250GB         | 1         | 2.33%   |
| Crucial CT240BX200SSD1 240GB         | 1         | 2.33%   |
| China SSD 512GB                      | 1         | 2.33%   |
| China 240GB SSD                      | 1         | 2.33%   |
| A-DATA SU650 120GB SSD               | 1         | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 14     | 38.89%  |
| WDC                 | 3         | 3      | 16.67%  |
| Toshiba             | 3         | 3      | 16.67%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| HGST HTS            | 2         | 4      | 11.11%  |
| Hitachi             | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 21.43%  |
| Crucial             | 2         | 2      | 14.29%  |
| China               | 2         | 2      | 14.29%  |
| Transcend           | 1         | 1      | 7.14%   |
| SanDisk             | 1         | 1      | 7.14%   |
| Qumo                | 1         | 1      | 7.14%   |
| Plextor             | 1         | 1      | 7.14%   |
| LITEON              | 1         | 1      | 7.14%   |
| Kingston            | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 15        | 27     | 42.86%  |
| SSD     | 13        | 14     | 37.14%  |
| NVMe    | 4         | 6      | 11.43%  |
| MMC     | 2         | 2      | 5.71%   |
| Unknown | 1         | 1      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 33     | 74.29%  |
| NVMe | 4         | 6      | 11.43%  |
| SAS  | 3         | 9      | 8.57%   |
| MMC  | 2         | 2      | 5.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 22     | 59.38%  |
| 0.51-1.0   | 11        | 15     | 34.38%  |
| 3.01-4.0   | 2         | 4      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 42.42%  |
| 501-1000       | 6         | 18.18%  |
| 251-500        | 3         | 9.09%   |
| 51-100         | 3         | 9.09%   |
| More than 3000 | 2         | 6.06%   |
| 21-50          | 2         | 6.06%   |
| 1-20           | 2         | 6.06%   |
| 2001-3000      | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 18        | 51.43%  |
| 21-50          | 7         | 20%     |
| 101-250        | 3         | 8.57%   |
| 51-100         | 3         | 8.57%   |
| 2001-3000      | 2         | 5.71%   |
| More than 3000 | 1         | 2.86%   |
| 501-1000       | 1         | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 2         | 2      | 25%     |
| HGST HTS 721010A9E630 1TB       | 2         | 4      | 25%     |
| WDC WD3200BEVT-75ZCT2 320GB     | 1         | 1      | 12.5%   |
| Toshiba MK3275GSX 320GB         | 1         | 1      | 12.5%   |
| Seagate ST320LT007-9ZV142 320GB | 1         | 3      | 12.5%   |
| Crucial CT240BX200SSD1 240GB    | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 5      | 37.5%   |
| HGST HTS | 2         | 4      | 25%     |
| WDC      | 1         | 1      | 12.5%   |
| Toshiba  | 1         | 1      | 12.5%   |
| Crucial  | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 5      | 42.86%  |
| HGST HTS | 2         | 4      | 28.57%  |
| WDC      | 1         | 1      | 14.29%  |
| Toshiba  | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 11     | 85.71%  |
| SSD  | 1         | 1      | 14.29%  |

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
| Works    | 19        | 27     | 54.29%  |
| Detected | 9         | 11     | 25.71%  |
| Malfunc  | 7         | 12     | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 25        | 71.43%  |
| AMD                          | 3         | 8.57%   |
| Samsung Electronics          | 2         | 5.71%   |
| Nvidia                       | 2         | 5.71%   |
| Toshiba America Info Systems | 1         | 2.86%   |
| Silicon Motion               | 1         | 2.86%   |
| SanDisk                      | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 7.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 7.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 7.5%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3         | 7.5%    |
| Nvidia MCP61 SATA Controller                                                            | 2         | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 5%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 5%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 5%      |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 2.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 2.5%    |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1         | 2.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 2.5%    |
| Samsung NVMe SSD Controller 980                                                         | 1         | 2.5%    |
| Nvidia MCP61 IDE                                                                        | 1         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 2.5%    |
| Intel Tiger Lake SATA AHCI Controller                                                   | 1         | 2.5%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 2.5%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 2.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 2.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 2.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 2.5%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 2.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 2.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 66.67%  |
| IDE  | 7         | 19.44%  |
| NVMe | 4         | 11.11%  |
| RAID | 1         | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 27        | 81.82%  |
| AMD    | 5         | 15.15%  |
| ARM    | 1         | 3.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 6.06%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 6.06%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 3.03%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 3.03%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 3.03%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 3.03%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 3.03%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 3.03%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 3.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 3.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 3.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 3.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 3.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 3.03%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 3.03%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 3.03%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 3.03%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 1         | 3.03%   |
| Intel Core 2 CPU P8700 @ 2.53GHz            | 1         | 3.03%   |
| Intel Core 2 CPU P8600 @ 2.40GHz            | 1         | 3.03%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 3.03%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 1         | 3.03%   |
| Intel Atom CPU N270 @ 1.60GHz               | 1         | 3.03%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 1         | 3.03%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz     | 1         | 3.03%   |
| ARM Allwinner sun8i Family Processor        | 1         | 3.03%   |
| AMD Phenom II X4 955 Processor              | 1         | 3.03%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 1         | 3.03%   |
| AMD Athlon II X2 215 Processor              | 1         | 3.03%   |
| AMD A8-5550M APU with Radeon HD Graphics    | 1         | 3.03%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 10        | 30.3%   |
| Intel Xeon              | 2         | 6.06%   |
| Intel Core i3           | 2         | 6.06%   |
| Intel Core 2            | 2         | 6.06%   |
| Intel Celeron           | 2         | 6.06%   |
| Intel Atom              | 2         | 6.06%   |
| Other                   | 1         | 3.03%   |
| Intel Pentium Dual-Core | 1         | 3.03%   |
| Intel Pentium Dual      | 1         | 3.03%   |
| Intel Pentium           | 1         | 3.03%   |
| Intel Core m3           | 1         | 3.03%   |
| Intel Core i7           | 1         | 3.03%   |
| Intel Core 2 Duo        | 1         | 3.03%   |
| ARM Allwinner           | 1         | 3.03%   |
| AMD Phenom II X4        | 1         | 3.03%   |
| AMD E1                  | 1         | 3.03%   |
| AMD Athlon II X2        | 1         | 3.03%   |
| AMD A8                  | 1         | 3.03%   |
| AMD A4                  | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 19        | 57.58%  |
| 4      | 9         | 27.27%  |
| 8      | 2         | 6.06%   |
| 1      | 2         | 6.06%   |
| 6      | 1         | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 96.97%  |
| 2      | 1         | 3.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 54.55%  |
| 1      | 15        | 45.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 93.94%  |
| 32-bit         | 1         | 3.03%   |
| Unknown        | 1         | 3.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 4         | 12.12%  |
| 0x1067a    | 4         | 12.12%  |
| Unknown    | 4         | 12.12%  |
| 0x406e3    | 2         | 6.06%   |
| 0x306c3    | 2         | 6.06%   |
| 0x306a9    | 2         | 6.06%   |
| 0x06001119 | 2         | 6.06%   |
| 0x906e9    | 1         | 3.03%   |
| 0x806ea    | 1         | 3.03%   |
| 0x806e9    | 1         | 3.03%   |
| 0x806d1    | 1         | 3.03%   |
| 0x706a1    | 1         | 3.03%   |
| 0x406c4    | 1         | 3.03%   |
| 0x30678    | 1         | 3.03%   |
| 0x206d7    | 1         | 3.03%   |
| 0x206c2    | 1         | 3.03%   |
| 0x106c2    | 1         | 3.03%   |
| 0x0500010d | 1         | 3.03%   |
| 0x010000c8 | 1         | 3.03%   |
| 0x010000b7 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| SandyBridge   | 5         | 15.15%  |
| Penryn        | 4         | 12.12%  |
| KabyLake      | 3         | 9.09%   |
| IvyBridge     | 3         | 9.09%   |
| Skylake       | 2         | 6.06%   |
| Silvermont    | 2         | 6.06%   |
| Piledriver    | 2         | 6.06%   |
| K10           | 2         | 6.06%   |
| Haswell       | 2         | 6.06%   |
| Bonnell       | 2         | 6.06%   |
| Westmere      | 1         | 3.03%   |
| Icelake       | 1         | 3.03%   |
| Goldmont plus | 1         | 3.03%   |
| Core          | 1         | 3.03%   |
| Bobcat        | 1         | 3.03%   |
| Unknown       | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 60%     |
| Nvidia | 11        | 31.43%  |
| AMD    | 3         | 8.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 8.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 8.11%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 5.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 5.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 5.41%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 2.7%    |
| Nvidia GP107GL [Quadro P600]                                                             | 1         | 2.7%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 2.7%    |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 2.7%    |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 2.7%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 2.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.7%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1         | 2.7%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 2.7%    |
| Intel UHD Graphics 620                                                                   | 1         | 2.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.7%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 2.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.7%    |
| Intel HD Graphics 620                                                                    | 1         | 2.7%    |
| Intel HD Graphics 515                                                                    | 1         | 2.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.7%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 2.7%    |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 2.7%    |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 2.7%    |
| AMD Juniper XT [Radeon HD 5770]                                                          | 1         | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 54.55%  |
| 1 x Nvidia     | 8         | 24.24%  |
| Intel + Nvidia | 3         | 9.09%   |
| 1 x AMD        | 3         | 9.09%   |
| Other          | 1         | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 30        | 90.91%  |
| Unknown | 3         | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 54.55%  |
| 1.01-2.0   | 5         | 15.15%  |
| 0.01-0.5   | 4         | 12.12%  |
| 0.51-1.0   | 3         | 9.09%   |
| 7.01-8.0   | 1         | 3.03%   |
| 5.01-6.0   | 1         | 3.03%   |
| 3.01-4.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 6         | 19.35%  |
| LG Display              | 4         | 12.9%   |
| Iiyama                  | 3         | 9.68%   |
| AU Optronics            | 3         | 9.68%   |
| Lenovo                  | 2         | 6.45%   |
| Dell                    | 2         | 6.45%   |
| BOE                     | 2         | 6.45%   |
| Acer                    | 2         | 6.45%   |
| Sharp                   | 1         | 3.23%   |
| Plain Tree Systems      | 1         | 3.23%   |
| Philips                 | 1         | 3.23%   |
| CPT                     | 1         | 3.23%   |
| Chimei Innolux          | 1         | 3.23%   |
| Chi Mei Optoelectronics | 1         | 3.23%   |
| Ancor Communications    | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                    | 3         | 9.68%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 6.45%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 3.23%   |
| Samsung Electronics SyncMaster SAM0216 1280x1024 338x270mm 17.0-inch     | 1         | 3.23%   |
| Samsung Electronics SMC27A550U SAM07F6 1920x1080 598x336mm 27.0-inch     | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC374E 1024x600 223x125mm 10.1-inch     | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 1         | 3.23%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 1         | 3.23%   |
| Plain Tree Systems Monitor PTS076D 1280x1024 376x301mm 19.0-inch         | 1         | 3.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                  | 1         | 3.23%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 3.23%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 1         | 3.23%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 1         | 3.23%   |
| Dell E151FPp DEL7006 1024x768 304x228mm 15.0-inch                        | 1         | 3.23%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                          | 1         | 3.23%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                     | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 1         | 3.23%   |
| BOE LCD Monitor BOE07C5 1920x1080 344x194mm 15.5-inch                    | 1         | 3.23%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO215C 1366x768 256x144mm 11.6-inch            | 1         | 3.23%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch    | 1         | 3.23%   |
| Acer KG251Q ACR0591 1920x1080 544x303mm 24.5-inch                        | 1         | 3.23%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                        | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 11        | 36.67%  |
| 1366x768 (WXGA)  | 10        | 33.33%  |
| 1280x800 (WXGA)  | 3         | 10%     |
| 1600x900 (HD+)   | 2         | 6.67%   |
| 3840x2160 (4K)   | 1         | 3.33%   |
| 1440x900 (WXGA+) | 1         | 3.33%   |
| 1280x1024 (SXGA) | 1         | 3.33%   |
| 1024x768 (XGA)   | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 10        | 32.26%  |
| 23     | 5         | 16.13%  |
| 14     | 4         | 12.9%   |
| 19     | 2         | 6.45%   |
| 17     | 2         | 6.45%   |
| 12     | 2         | 6.45%   |
| 11     | 2         | 6.45%   |
| 27     | 1         | 3.23%   |
| 24     | 1         | 3.23%   |
| 21     | 1         | 3.23%   |
| 13     | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 43.33%  |
| 501-600     | 7         | 23.33%  |
| 201-300     | 5         | 16.67%  |
| 351-400     | 3         | 10%     |
| 401-500     | 2         | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 80%     |
| 16/10 | 3         | 10%     |
| 5/4   | 1         | 3.33%   |
| 4/3   | 1         | 3.33%   |
| 3/2   | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 32.26%  |
| 201-250        | 6         | 19.35%  |
| 81-90          | 4         | 12.9%   |
| 61-70          | 2         | 6.45%   |
| 51-60          | 2         | 6.45%   |
| 151-200        | 2         | 6.45%   |
| 71-80          | 1         | 3.23%   |
| 301-350        | 1         | 3.23%   |
| 251-300        | 1         | 3.23%   |
| 141-150        | 1         | 3.23%   |
| 121-130        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 11        | 37.93%  |
| 121-160       | 8         | 27.59%  |
| 101-120       | 8         | 27.59%  |
| More than 240 | 1         | 3.45%   |
| 161-240       | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 91.18%  |
| 0     | 2         | 5.88%   |
| 3     | 1         | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 16        | 27.59%  |
| Qualcomm Atheros                | 15        | 25.86%  |
| Intel                           | 12        | 20.69%  |
| Qualcomm Atheros Communications | 4         | 6.9%    |
| Ralink Technology               | 2         | 3.45%   |
| Nvidia                          | 2         | 3.45%   |
| Marvell Technology Group        | 2         | 3.45%   |
| Broadcom                        | 2         | 3.45%   |
| Samsung Electronics             | 1         | 1.72%   |
| Qualcomm                        | 1         | 1.72%   |
| Microsoft                       | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 8         | 12.31%  |
| Qualcomm Atheros AR9271 802.11n                                     | 4         | 6.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3         | 4.62%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2         | 3.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2         | 3.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2         | 3.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 2         | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2         | 3.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2         | 3.08%   |
| Nvidia MCP61 Ethernet                                               | 2         | 3.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                        | 2         | 3.08%   |
| Samsung HSPA Modem                                                  | 1         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 1.54%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                     | 1         | 1.54%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1         | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1         | 1.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1         | 1.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 1.54%   |
| Ralink MT7601U Wireless Adapter                                     | 1         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1         | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 1         | 1.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                              | 1         | 1.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1         | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1         | 1.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                               | 1         | 1.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1         | 1.54%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1         | 1.54%   |
| Qualcomm Android                                                    | 1         | 1.54%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                   | 1         | 1.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller             | 1         | 1.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                | 1         | 1.54%   |
| Intel Wireless 7265                                                 | 1         | 1.54%   |
| Intel Wireless 3165                                                 | 1         | 1.54%   |
| Intel WiFi Link 5100                                                | 1         | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 1         | 1.54%   |
| Intel Ethernet Connection (5) I219-LM                               | 1         | 1.54%   |
| Intel Centrino Wireless-N 6150                                      | 1         | 1.54%   |
| Intel Centrino Wireless-N + WiMAX 6150                              | 1         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 1         | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 11        | 35.48%  |
| Intel                           | 8         | 25.81%  |
| Realtek Semiconductor           | 5         | 16.13%  |
| Qualcomm Atheros Communications | 4         | 12.9%   |
| Ralink Technology               | 2         | 6.45%   |
| Broadcom                        | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9271 802.11n                                     | 4         | 12.5%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2         | 6.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2         | 6.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 2         | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2         | 6.25%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                        | 2         | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 3.13%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                     | 1         | 3.13%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1         | 3.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 3.13%   |
| Ralink MT7601U Wireless Adapter                                     | 1         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 1         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1         | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1         | 3.13%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1         | 3.13%   |
| Intel Wireless 7265                                                 | 1         | 3.13%   |
| Intel Wireless 3165                                                 | 1         | 3.13%   |
| Intel WiFi Link 5100                                                | 1         | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 1         | 3.13%   |
| Intel Centrino Wireless-N 6150                                      | 1         | 3.13%   |
| Intel Centrino Wireless-N + WiMAX 6150                              | 1         | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 1         | 3.13%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 12        | 37.5%   |
| Intel                    | 7         | 21.88%  |
| Qualcomm Atheros         | 6         | 18.75%  |
| Nvidia                   | 2         | 6.25%   |
| Marvell Technology Group | 2         | 6.25%   |
| Qualcomm                 | 1         | 3.13%   |
| Microsoft                | 1         | 3.13%   |
| Broadcom                 | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 25%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 9.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 6.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 6.25%   |
| Nvidia MCP61 Ethernet                                             | 2         | 6.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.13%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.13%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 3.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 3.13%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 3.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.13%   |
| Qualcomm Android                                                  | 1         | 3.13%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 1         | 3.13%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 3.13%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.13%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 3.13%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 3.13%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.13%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 3.13%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 32        | 53.33%  |
| WiFi     | 27        | 45%     |
| Modem    | 1         | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 18        | 56.25%  |
| WiFi     | 14        | 43.75%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 18        | 54.55%  |
| 1     | 13        | 39.39%  |
| 3     | 1         | 3.03%   |
| 0     | 1         | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 78.79%  |
| Yes  | 7         | 21.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 3         | 21.43%  |
| Intel                           | 3         | 21.43%  |
| Broadcom                        | 3         | 21.43%  |
| Toshiba                         | 2         | 14.29%  |
| Realtek Semiconductor           | 1         | 7.14%   |
| Foxconn / Hon Hai               | 1         | 7.14%   |
| Apple                           | 1         | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                 | 2         | 14.29%  |
| Intel Bluetooth wireless interface                 | 2         | 14.29%  |
| Toshiba RT Bluetooth Radio                         | 1         | 7.14%   |
| Toshiba Bluetooth Device                           | 1         | 7.14%   |
| Realtek Bluetooth Radio                            | 1         | 7.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 7.14%   |
| Intel AX201 Bluetooth                              | 1         | 7.14%   |
| Foxconn / Hon Hai Bluetooth Device                 | 1         | 7.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                  | 1         | 7.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 7.14%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 7.14%   |
| Apple Built-in Bluetooth 2.0+EDR HCI               | 1         | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 27        | 67.5%   |
| Nvidia        | 9         | 22.5%   |
| AMD           | 3         | 7.5%    |
| Creative Labs | 1         | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 13.64%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 9.09%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 6.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 6.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 6.82%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 4.55%   |
| AMD FCH Azalia Controller                                                                         | 2         | 4.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.27%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 2.27%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 2.27%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 2.27%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.27%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 2.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.27%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 2.27%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                                            | 1         | 2.27%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 2.27%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 24.14%  |
| SK hynix            | 5         | 17.24%  |
| Micron Technology   | 5         | 17.24%  |
| Kingston            | 3         | 10.34%  |
| Unknown             | 2         | 6.9%    |
| Ramaxel Technology  | 1         | 3.45%   |
| Qimonda             | 1         | 3.45%   |
| PNY                 | 1         | 3.45%   |
| Goodram             | 1         | 3.45%   |
| G.Skill             | 1         | 3.45%   |
| Crucial             | 1         | 3.45%   |
| A-DATA Technology   | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                              | 1         | 3.45%   |
| Unknown RAM 3634543235363032304555322E3543322020 2048MB DIMM DDR2 800MT/s | 1         | 3.45%   |
| SK hynix RAM Module 1024MB DIMM DDR3 1066MT/s                             | 1         | 3.45%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s                      | 1         | 3.45%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s                      | 1         | 3.45%   |
| SK hynix RAM HMT41GS6AFR8A-H9 8192MB SODIMM DDR3 1333MT/s                 | 1         | 3.45%   |
| SK hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 3.45%   |
| Samsung RAM Module 4096MB DIMM DDR4 2400MT/s                              | 1         | 3.45%   |
| Samsung RAM Module 4096MB DIMM DDR3 1066MT/s                              | 1         | 3.45%   |
| Samsung RAM Module 2GB Row Of Chips DDR3 1600MT/s                         | 1         | 3.45%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 3.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 3.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 3.45%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s                    | 1         | 3.45%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 3.45%   |
| Qimonda RAM 64T512022EDL2.5A 4096MB SODIMM DDR 800MT/s                    | 1         | 3.45%   |
| PNY RAM Module 4096MB DIMM DDR3 1066MT/s                                  | 1         | 3.45%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s         | 1         | 3.45%   |
| Micron RAM Module 2048MB DIMM DDR3 1066MT/s                               | 1         | 3.45%   |
| Micron RAM H6451U64F7066G 4096MB SODIMM DDR3 1067MT/s                     | 1         | 3.45%   |
| Micron RAM 4ATF51264HZ-2G3H1R 4GB SODIMM DDR4 2400MT/s                    | 1         | 3.45%   |
| Micron RAM 36JSF1G72PZ-1 8192MB DIMM DDR3 1866MT/s                        | 1         | 3.45%   |
| Kingston RAM ASU1600S11-4G-EDEG 4GB SODIMM DDR3 1600MT/s                  | 1         | 3.45%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s                     | 1         | 3.45%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s                    | 1         | 3.45%   |
| Goodram RAM GY1600D364L9/4G 4GB DIMM DDR3 1333MT/s                        | 1         | 3.45%   |
| G.Skill RAM F3-2400C11-8GXM 8GB DIMM DDR3 2400MT/s                        | 1         | 3.45%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s                   | 1         | 3.45%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s                             | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 15        | 65.22%  |
| DDR4   | 4         | 17.39%  |
| DDR2   | 2         | 8.7%    |
| LPDDR3 | 1         | 4.35%   |
| DDR    | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 45.45%  |
| DIMM         | 10        | 45.45%  |
| Row Of Chips | 2         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 15        | 57.69%  |
| 8192 | 5         | 19.23%  |
| 2048 | 5         | 19.23%  |
| 1024 | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 8         | 32%     |
| 2400  | 4         | 16%     |
| 1333  | 2         | 8%      |
| 1066  | 2         | 8%      |
| 800   | 2         | 8%      |
| 3200  | 1         | 4%      |
| 2133  | 1         | 4%      |
| 1867  | 1         | 4%      |
| 1866  | 1         | 4%      |
| 1334  | 1         | 4%      |
| 1067  | 1         | 4%      |
| 975   | 1         | 4%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP Deskjet 3510 series | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 4         | 22.22%  |
| Microdia                               | 3         | 16.67%  |
| Sunplus Innovation Technology          | 2         | 11.11%  |
| Lenovo                                 | 2         | 11.11%  |
| Z-Star Microelectronics                | 1         | 5.56%   |
| Realtek Semiconductor                  | 1         | 5.56%   |
| Quanta                                 | 1         | 5.56%   |
| Logitech                               | 1         | 5.56%   |
| Importek                               | 1         | 5.56%   |
| IMC Networks                           | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Webcam                                     | 2         | 11.11%  |
| Z-Star Webcam                                                | 1         | 5.56%   |
| Sunplus HD WebCam                                            | 1         | 5.56%   |
| Sunplus Asus Webcam                                          | 1         | 5.56%   |
| Realtek Lenovo EasyCamera                                    | 1         | 5.56%   |
| Quanta HD User Facing                                        | 1         | 5.56%   |
| Microdia Integrated_Webcam_HD                                | 1         | 5.56%   |
| Microdia Integrated_Webcam_1.3M                              | 1         | 5.56%   |
| Microdia Integrated Webcam HD                                | 1         | 5.56%   |
| Logitech C505 HD Webcam                                      | 1         | 5.56%   |
| Importek TOSHIBA Web Camera                                  | 1         | 5.56%   |
| IMC Networks UVC VGA Webcam                                  | 1         | 5.56%   |
| Chicony TOSHIBA Web Camera                                   | 1         | 5.56%   |
| Chicony Thinkpad T430 camera                                 | 1         | 5.56%   |
| Chicony integrated camera                                    | 1         | 5.56%   |
| Chicony HP Webcam                                            | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 5.56%   |

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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 22        | 64.71%  |
| 1     | 11        | 32.35%  |
| 2     | 1         | 2.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 5         | 45.45%  |
| Net/wireless          | 2         | 18.18%  |
| Multimedia controller | 2         | 18.18%  |
| Chipcard              | 1         | 9.09%   |
| Bluetooth             | 1         | 9.09%   |

